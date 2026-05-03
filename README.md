# BME-450-Stroke-CT-Project
Team members: Mattie Midkiff (GitHubUserA), Chloe McGuire (GitHubUserB) 

Stroke is the second largest cause of worldwide mortality. Efficient stroke diagnosis and differentiation between ischemic and hemorrhagic strokes are critical to providing timely intervention. Delays and misdiagnoses lead to severe complications and a likelihood of more brain damage occurring. Artificial intelligence that can reduce or eliminate these misdiagnoses without compromising the speed of diagnosis could improve stroke patient treatment and outcomes.

The goal of this project is to develop an AI-powered program capable of accepting a CT image of the brain and determining if the patient has experienced a stroke. This will assist healthcare professionals in making faster, more reliable decisions in emergency settings. 

The project will involve collecting and preprocessing a dataset of labeled brain scans. The dataset we have chosen is the Brain Stroke CT Dataset on Kaggle. It was created using data collected in 2019 and 2020 by the Republic of Türkiye Ministry of Health. There is a total of 6653 CT slices of the brain, provided in both PNG and DICOM format. Of these images, 4428 are healthy brains (no stroke), 1131 have evidence of an ischemic stroke, and 1094 have evidence of a hemorrhagic stroke. There is also a folder of test images with their correct label for verification of correct training. All folders contain copies of the images with the affected area (if any) highlighted, which have the potential to be used for training purposes

The model will be evaluated based on accuracy, sensitivity, and specificity. Additional features may include returning information about the brain area affected or highlighting affected regions to improve interpretability for clinicians.

Dataset Link: https://nam04.safelinks.protection.outlook.com/?url=https%3A%2F%2Fwww.kaggle.com%2Fdatasets%2Fozguraslank%2Fbrain-stroke-ct-dataset%2Fdata&data=05%7C02%7Cmmidkif%40purdue.edu%7Cd85ca88687be4bf0881608dea93dd1bf%7C4130bd397c53419cb1e58758d6d63f21%7C1%7C0%7C639134280155664673%7CUnknown%7CTWFpbGZsb3d8eyJFbXB0eU1hcGkiOnRydWUsIlYiOiIwLjAuMDAwMCIsIlAiOiJXaW4zMiIsIkFOIjoiTWFpbCIsIldUIjoyfQ%3D%3D%7C0%7C%7C%7C&sdata=GUj%2FRWe607dCFYkPN%2Bla3J2DqWytcWUSwLC3%2Fp3lIyA%3D&reserved=0
