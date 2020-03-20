# CovidNet 😷😷
![Corona Virus](https://github.com/smaranjitghose/CovidNet/blob/master/assets/covid19_vis.jpg)

## Background: 💀
Coronavirus disease 2019 (COVID-19) is an infectious disease caused by severe acute respiratory syndrome coronavirus 2 (SARS-CoV-2). The disease was first identified in 2019 in Wuhan, China and has since spread globally🌏 , resulting in the [2019–20 coronavirus pandemic](https://en.wikipedia.org/wiki/2019%E2%80%9320_coronavirus_pandemic). We attempt contribute to the cause of relief, we attempt to use deep learning based approaches to predict and understand the infection


## Our attempt #1 👨‍🏭 

COVID-19 is known to attack 🤺 the epithelial cells that line our respiratory tract. Hence X-rays are used to analyze the health of a patient’s lungs. However in the current scenario hospitals are overwhelmed with the number of cases every single day and  the scarcity of radiology experts and the time taken for diagnosis for each patient sums up to an acute delay issue. Thus we attempt to create an automatic analysis system👨‍💻 to resolve the situation.

We used various tranfer learning techniques for creating a first-cut solution to this problem:

|Method|Notebook|Accuracy|Sensivity|Specificity|
|------|---------|--------|---------|------------|
|MobileNetV2|[Link](https://github.com/smaranjitghose/CovidNet/blob/master/coronanet2.ipynb)|90%|80%|100%|
|VGG16|[Link](https://github.com/smaranjitghose/CovidNet/blob/master/coronanet1.ipynb)|70%|80%|60%|


# Dataset: 🙏

![Dataset](https://github.com/smaranjitghose/CovidNet/blob/master/assets/covid_19_dataset.png)

The dataset used for this primararily curated from [COVID-19 Database](https://www.sirm.org/category/senza-categoria/covid-19/), [Radiopedia](https://radiopaedia.org/articles/covid-19-2?lang=us)for the covid-19 infected chest X-ray images and [Chest X-Ray Images (Pneumonia) from Kaggle ](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia) for the non-infected chest X-ray images, as provided by [Adrian Rosebrock in his blog for the same](https://www.pyimagesearch.com/2020/03/16/detecting-covid-19-in-x-ray-images-with-keras-tensorflow-and-deep-learning/)

 # Further Tasks: 🏗
- Curating a dataset with larger number of chest x-ray images for COVID-19 infection as well as ensuring better medical image quality
- Retraining the models on the same
- Obtaining reviews by medical professionals🩺 and tune the work as per feedback
- Extending the work to chest CT-scan images
- Depolying it in an end to end web app to be used by medical professionals
- Taking into account other factors for analyzing infection as suggested by medical professionals🩺 
 
 # License ⚙
 
 [MIT License](https://github.com/smaranjitghose/CovidNet/blob/master/LICENSE)

