When initially i set the dropout rate to 0.5 with 32 convolution layer of 3 by 3 and 1 max pooling of 2 by 2
but the interpolation technique of cv2 was cubic the accuracy was around 5 to 5.4 percent was very less as i 
changed the hodden layers from 5 to 100 but as soon as i changed the hidden layers to 200 the acuracy suddenly jumps to 
93.34 percent. But when i changed the interpolation method to linear or area the accuracy decreased and loss increased 
to approx 92 percent and loss to 0.45 from 0.16 which was for cubic so cubic was found the best out of three .
Further increase the filter to 50 and to 100 helped increase accuracy a little to 94 percent approx.
And changing the dropout rate to 0.1 percent helped in high accuracy on data test but decreased accuracy on the test set.
so i found 0.4 dropout rate to be perfect. There was no much increase in accuracy when number of epochs was increased from 10 to 
15 and to 25. Further increasing the number of hidden layers were found no helpful. But when i changed convolution filter to 50
and max pool 3 times the accuracy was found highest which was 95.96 on both test data and similar in training data.