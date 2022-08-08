# awsasdi_agriculturevision_jgc

Project for Amazon Sustainability Data Initiative (ASDI) Global Hackathon

# Explanation

Plants that have a lack or deficiency of nitrogen have performance problems and show chlorosis or yellow or light green coloration. They are more prone to pests and diseases. 

 The lack of potassium in the soil also causes the leaves to appear yellowish or blue-green, with dark yellow edges. They are more susceptible to fungal attack. 

 With lack of water, dry soil, the leaves are decayed and also show a yellow hue. The soles look dull in color and remain limp. 

Sometimes the consequences of a malnourished plantation can be very similar to those of a harvest with a lack of water and even their origins, motives and causes can be interrelated, but on other occasions this is not the case. 

In the same way, the visible effects in the plantation can sometimes be very similar between a crop with a lack of water and a crop with a lack of nutrients, but on other occasions such differences are very difficult for the human eye to distinguish. 

And, even if the effect can be distinguished when it comes to large plantation areas, when it comes to many hectares or areas that are not easily accessible, it is not always easy to personally check the state of the soil. 

To all this is added the factor of climate change, which adds more modifications to the patterns in the plantations and generates new problems associated with the lack of water or with malnourished land. 

Given all this, having automated systems powered by machine learning that can accurately distinguish the cause of the poor state of the land can be transcendent and of vital importance for crops. 

NOTE: for the purposes of this project, it should be understood that it is simply a demo development carried out for the sole purpose of this competition and that, although the system is operational, obviously the dataset with which it has been fed is simply in an incipient state and that to take it to production it should be fed and balanced. 

For the purposes of this project, we have simply chosen two images that show a lot of contrast with each other, for demonstration purposes and an increase in data (x1000) has been carried out, but logically to continue with this development, the images to choose from each part of the classification (drydown or nutrient) should be the least contrasted with each other and not the other way around. 

The system has been proposed as follows: based on the ASDI data, a dataset is generated that allows classification between lack of nutrients or lack of water, and data augmentation is performed with SageMaker. The resulting data is ingested into Rekognition to train a model that puts an operational API that can be easily integrated on any device, anytime, anywhere. 

ASDI source:  https://aws.amazon.com/marketplace/pp/prodview-a5p4wkdat6cnc?sr=0-109&ref_=beagle&applicationId=AWSMPContessa#resources 

The members of the jury can request access to the resource in Rekognition, to the API at the time they want to be able to check the operation of the system if they wish. 

Link to the video of the project: https://youtu.be/lCBzdOD6U-s 
