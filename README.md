## Medical Image Analysis
Medical Image Analysis for Malaria Detection

**Malaria** is caused by protozoan parasites of the genus **Plasmodium** that are transmitted through the bites of infected female Anopheles mosquitoes and that infect the red blood cells.

### How could I help the fight against malaria?

Deep learning + medical imaging system can help reduce the 400,000+ deaths per year caused by malaria. We’ll explore malaria database which contains blood smear images that fall into one of two classes: positive for malaria or negative for malaria.


### **A world map of areas currently affected by malaria**
Malaria is an infectious disease that causes over 400,000 deaths per year. Malaria is a true endemic in some areas of the world, meaning that the disease is regularly found in the region. In other areas of the world, malaria is an epidemic — it’s widespread in the area but not yet at endemic proportions. Yet in other areas of the world malaria is rarely, if ever, found at all.

![](https://assets.treated.com/doctorartical/By-CDC-Estimated-Risk.png)


### How can we test for malaria?
Two methods of testing for malaria include: 
1. Blood smears
2. Antigen testing (i.e., rapid tests)

The blood smear process can be visualized in Figure below:
1. First, a blood sample is taken from a patient and then placed on a slide.
2. The sample is stained with a contrasting agent to help highlight malaria parasites in red blood cells
3. A clinician then examines the slide under a microscope and manually counts the number of red blood cells that are infected.

![](https://miro.medium.com/max/2400/1*VWxRC2BePykk3xVVEDzbdg.png)

### Malaria datasets
 The National Institute of Health (NIH) has made their Malaria Dataset available to the public on their [website](https://ceb.nlm.nih.gov/repositories/malaria-datasets/)
 
![](https://github.com/shejz/Medical-Image-Analysis/blob/main/Malaria%20Dataset.jpg)

**The dataset consists of 27,588 images belonging to two separate classes**:

- Parasitized: Implying that the region contains malaria.
- Uninfected: Meaning there is no evidence of malaria in the region.

The number of images per class is equally distributed with 13,794 images per each respective class.

### Medical image analysis results

Malaria classifier model training/testing accuracy and loss plot shows that we’ve achieved high accuracy and low loss. The model isn’t exhibiting signs of over/underfitting. This deep learning medical imaging “malaria classifier” model was created with **ResNet** architecture using Keras/TensorFlow.

![](https://github.com/shejz/Medical-Image-Analysis/blob/main/plot.png)

Here we can see that our model was trained for a total of 50 epochs. A smaller variant of ResNet whose model size is only 17.7MB, we were able to obtain 96% accuracy


