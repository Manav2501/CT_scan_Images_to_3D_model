# CT_scan_Images_to_3D_model
This folder contains Special Assignment project of course Embedded System Programming

In this project taken CT scan file of patient and convert into 3D model in STL file format. For that use CT scan images which are in Dicom file format. First I had to understand Dicom File format. 

 
Fig 8.1 Radiant Dicom Viewer Software

For that I Used Radiant Dicom Viewer Software from which I could understand files and how it works. After that I knew that it’s a series of image capture in some distance. And every image contains single slice of scan part. 
Therefore, I had to do some image processing to extract Bones from Images which contains specific pixel values in image.
 
Fig 8.2 Histrogram of Images
From Histrogram mapping I extracted bone data. After Extracting data from every image, I had to convert 3d Model. 
 
Fig 8.3 Sliced images of mapped data
Therefore, first need to find spacing between images means at which distance every image is taken or what is the distance between 2 images.
 From that resample all data and created a mesh to visualize in 3d plot. From Mesh I created vertices and faces for STL file format and export the STL File.

