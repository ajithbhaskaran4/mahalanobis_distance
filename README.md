# mahalanobis_distance
to find mahalanobis distance with respect two template image layers 
in mahahasv function you need to pass the original image, template image, and the index of layers for which u need to calculate the covariance.
eg here i need to calculate the covariance between hue layer and saturation layer
index_of_layer1=1; %corresponds to hue
index_of_layer1=2;%corresponds to saturation
out=mahahsv(original_image,template_image,index_of_layer1, index_of_layer2);

in mahaycbcr function you need to pass the original image, template image, and the index of layers for which u need to calculate the covariance.
eg here i need to calculate the covariance between cb layer and cr layer
index_of_layer1=2; %corresponds to hue
index_of_layer1=3;%corresponds to saturation
out=mahahsv(original_image,template_image,index_of_layer1, index_of_layer2);
