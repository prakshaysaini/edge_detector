# edge_detector
detect vertical and horizontal edges using convolution, no library function used.
Convulation matrix used -> [[ 0.25,  0.5 ,  0.25],    for vertical edges
                           [ 0.  ,  0.  ,  0.  ],
                           [-0.25, -0.5 , -0.25]]
                           

Convulation matrix used-> [[ 0.25,  0.  , -0.25],  for horizontal edges
                          [ 0.5 ,  0.  , -0.5 ],
                          [ 0.25,  0.  , -0.25]]


Images greater then 1024*1024px are shorten by 25% untill they are less then 1024