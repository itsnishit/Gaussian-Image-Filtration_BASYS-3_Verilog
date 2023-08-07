# Project Description
The input image is converted to a grayscale image which has values between 0-255 (8 bits) and then to a coefficient (.coe) file using Python script which has values between 0-255 (8 bits). This coe file is used to initiate a Dual-Port Block RAM which is then accessed to do the convolution operation with the gaussian kernel (3X3). This convolved data is then again stored in the same Block RAM using the dual port (optimizing storage space).


