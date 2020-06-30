# Final Project: Image Processing Using X-Rays


### Problem Statement
Can we predict whether a person has Covid-19 or not by using lung X-Ray images?

Covid-19 is an illness caused by a virus that can spread from person to person either through direct contact, airborne droplets, or infected surfaces. This virus has affected many world-wide and spread rapidly. As of June 9th, 2020, There were over 7 million known cases in the world. There is currently no vaccine. People are encouraged to wash their hands, disinfect regularly, not come into close contact to others, not touch their faces, and stay home as much as possible. With limited testing availability, many are looking for alternative ways of identifying the virus. However, these methodologies do not currently replace molecular laboratory tests to diagnose Covid-19 as symptoms range from no or minor symptoms to sever symptoms.

### Executive Summary
Image processing of 5,887 images show us a starting point for identifying Covid-19. Because of the small sample size of Covid-19 images, X-rays of patients with pneumonia are also being processed since they show similar opacities as those in X-rays of Covid-19 patients. In the results, we can see that there were more misclassification of healthy patients. Labeling patients that are healthy as unhealthy I believe is a better outcome than labeling patients that are unhealthy as healthy. Patients can self-isolate and take the precautions necessary to not infect others until they can confirm if they have Covid-19 with the formal molecular lab tests.

### Contents
- [Images](./images)
- [Final Notebook](./lung_image_processing.ipynb)
- [Keras Image Augmentation](./importing_images_with_keras.ipynb)
- [Presentation Slides](./image_processing_presentation.pdf)

### Conclusion
Nothing will currently replace official molecular laboratory tests to identify Covid-19. There is work to be done to improve the image processing model. I look forward to accessing additional images and finding other pre-trained models that focus on X-rays. The data set is unbalanced with more pneumonia cases than healthy which likely led to more healthy images being classified as pneumonia. However, this is preferable over unhealthy patients being told their healthy. The more precautions people take, the better and hopefully sooner the pandemic is controlled. 
