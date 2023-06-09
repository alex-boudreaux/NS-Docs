# [NeuralSeek Integration with Watson Assistant and Discovery ](https://app.tango.us/app/workflow/a5fafae1-abe9-4d04-9196-4be39eb9f941?utm_source=markdown&utm_medium=markdown&utm_campaign=workflow%20export%20links)

Created by Alex Boudreaux.

I used Data, AI & Automation Demobuilder on TechZone to spin up the 3 services we need in this tutorial.

[https://techzone.ibm.com/collection/data-ai--automation-demobuilder/environments](https://techzone.ibm.com/collection/data-ai--automation-demobuilder/environments)

It has custom code that runs on initialization that will scrape a given URL to provide our Discovery instance with thousands of documents.

__Creation Date:__ June 8, 2023  
__Created By:__ Alex Boudreaux  
[View most recent version on Tango.us](https://app.tango.us/app/workflow/a5fafae1-abe9-4d04-9196-4be39eb9f941?utm_source=markdown&utm_medium=markdown&utm_campaign=workflow%20export%20links)



***




## # [IBM Watson Discovery](https://us-south.discovery.watson.cloud.ibm.com/v2/instances/crn%3Av1%3Abluemix%3Apublic%3Adiscovery%3Aus-south%3Aa%2Fead8711ba2cc4d08a16fd37427f4f01a%3A94115f22-a839-4316-b868-9a3b7680108d%3A%3A/projects)
Go to your Watson Discovery instance.


### 1. Click on your Discovery project…
![Step 1 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/92320ec8-e90a-4675-8071-149a0317bd80/ac363fc4-163a-44e5-b78b-69d339689b66.png?crop=focalpoint&fit=crop&fp-x=0.1032&fp-y=0.5074&fp-z=2.0373&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=19&mark-y=218&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz00NjcmaD0yNDQmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D)


### 2. Click on Manage collections
![Step 2 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/ae712c9a-69c1-4a70-9f2b-679e76e0fa56/afcffaa6-c149-4daf-8a0c-3179e7cabf32.png?crop=focalpoint&fit=crop&fp-x=0.0711&fp-y=0.1122&fp-z=2.2383&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=-6&mark-y=132&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0zOTQmaD03OCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 3. See how the environment scraped the given URL for thousands of documents...
![Step 3 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/833fe4af-d2b1-4969-8657-5d2eac10ac86/85234220-7222-4567-92f5-bcfef0143a4b.png?crop=focalpoint&fit=crop&fp-x=0.1311&fp-y=0.2406&fp-z=2.0560&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=94&mark-y=211&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz00NjAmaD0yNTImZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D)


### 4. Click on Integrate and deploy
![Step 4 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/10fa5777-2b47-4f45-b495-b0bbe36e3b9f/c37728d3-640d-4a9d-8b49-ff359184af02.png?crop=focalpoint&fit=crop&fp-x=0.0711&fp-y=0.1555&fp-z=2.2383&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=-6&mark-y=198&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0zOTQmaD03OCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 5. Click on API Information
![Step 5 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/de8e33aa-2f1d-43d2-85d8-e2ceef79f7a7/f3dd5ea2-59e2-4ca0-85c1-893edf887116.png?crop=focalpoint&fit=crop&fp-x=0.2578&fp-y=0.1580&fp-z=2.5397&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=457&mark-y=233&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0yODYmaD04MCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 6. Click on Copy for the Project ID and save for later...
![Step 6 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/06e272a6-9cbd-45ea-8b26-1822549b4789/ef573a81-6771-488d-8f55-7d167315c6c2.png?crop=focalpoint&fit=crop&fp-x=0.0469&fp-y=0.2372&fp-z=2.8798&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=116&mark-y=294&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz05MyZoPTkzJmZpdD1jcm9wJmNvcm5lci1yYWRpdXM9MTA%3D)


## # [NeuralSeek](https://console.neuralseek.com/crn%3Av1%3Abluemix%3Apublic%3Aneuralseek%3Aus-south%3Aa%2Fead8711ba2cc4d08a16fd37427f4f01a%3A5673c612-c185-4ad6-a9d5-9413ee46f61a%3A%3A/home)
Go to your Neural Seek instance.


### 7. Click on Data
![Step 7 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/e6755983-f9e5-4ea9-a8be-5ad2f0de93a2/4d93ae03-51e9-471d-b433-845a4720d1c8.png?crop=focalpoint&fit=crop&fp-x=0.0770&fp-y=0.1811&fp-z=3.0529&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=243&mark-y=312&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz03OCZoPTU3JmZpdD1jcm9wJmNvcm5lci1yYWRpdXM9MTA%3D)


### 8. Click on Watson Discovery and add your credentials. (Project ID found in the step above, API key and Service URL found on IBM Cloud dashboard of your Discovery instance.)
![Step 8 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/b0788712-261c-4033-a173-9acd76a4f913/2d882a75-9fb9-4437-8404-6bd7fbb579a8.png?crop=focalpoint&fit=crop&fp-x=0.2528&fp-y=0.2884&fp-z=2.2524&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=405&mark-y=304&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0zODkmaD03MiZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 9. Click on button
![Step 9 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/ba8861ab-1200-4819-95c9-1ed45a48ea1a/50b1057e-dce4-421e-a077-e6a48728cdf2.png?crop=focalpoint&fit=crop&fp-x=0.2109&fp-y=0.5433&fp-z=2.7757&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=500&mark-y=294&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0yMDEmaD05MyZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 10. Click on Tune
![Step 10 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/8c634cbd-ee61-41ca-8722-b05b73e14ac7/486823ba-e282-41a5-b94b-4e9bf3a3e3b3.png?crop=focalpoint&fit=crop&fp-x=0.0776&fp-y=0.3701&fp-z=3.0529&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=243&mark-y=312&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz04MiZoPTU3JmZpdD1jcm9wJmNvcm5lci1yYWRpdXM9MTA%3D)


### 11. Click on button
![Step 11 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/628ce019-6dc5-484c-8edf-750a078c2ec5/ce56b9bb-c53e-44ce-aced-8fe2f188b5c5.png?crop=focalpoint&fit=crop&fp-x=0.8795&fp-y=0.6083&fp-z=2.8636&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=663&mark-y=292&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0yNDUmaD05NiZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 12. Click on highlight
![Step 12 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/c36c5065-99fc-4ffe-8ae3-8c6ca168187a/6383917d-1219-42ad-9fd5-58b297a9c758.png?crop=focalpoint&fit=crop&fp-x=0.2656&fp-y=0.3691&fp-z=2.4697&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=445&mark-y=292&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0zMTEmaD05NiZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 13. Neural Seek will give you sample questions to ask. Save them in a note...
![Step 13 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/6453ce8a-6358-429f-808e-341bf61bb230/33da062e-c8aa-4b66-ab02-019d991a2ef7.png?crop=focalpoint&fit=crop&fp-x=0.5402&fp-y=0.7534&fp-z=1.2207&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=74&mark-y=299&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0xMDUzJmg9MzUyJmZpdD1jcm9wJmNvcm5lci1yYWRpdXM9MTA%3D)


### 14. Click on Integrate
![Step 14 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/12b049ed-e1f2-4dcc-94e9-82f8fe51e329/ecaa6d8e-6cc0-4ebe-bae1-a9f62da21626.png?crop=focalpoint&fit=crop&fp-x=0.2249&fp-y=0.0231&fp-z=2.7930&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=503&mark-y=-7&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0xOTUmaD0xMDMmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D)


### 15. Click to copy the API Key to your clipboard
![Step 15 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/e5ad8b5a-3dcb-458f-bd8d-717b602aee82/cb12a65a-aca0-4288-9f6e-b676bc3eac42.png?crop=focalpoint&fit=crop&fp-x=0.4900&fp-y=0.3091&fp-z=2.8798&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=554&mark-y=294&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz05MyZoPTkzJmZpdD1jcm9wJmNvcm5lci1yYWRpdXM9MTA%3D)


### 16. Click on Custom Extension OpenAPI File to download file
![Step 16 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/7fd81243-8562-463b-ad07-75ae9ccc23d7/a19815de-c889-454d-9067-0612d433409a.png?crop=focalpoint&fit=crop&fp-x=0.2528&fp-y=0.4695&fp-z=2.1653&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=390&mark-y=304&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz00MjAmaD03MiZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


## # [IBM Watson Assistant](https://us-south.assistant.watson.cloud.ibm.com/crn%3Av1%3Abluemix%3Apublic%3Aconversation%3Aus-south%3Aa%2Fead8711ba2cc4d08a16fd37427f4f01a%3A7708e433-aad9-40eb-affd-bd155c95b4cf%3A%3A/assistants/6a13008d-7853-49e7-aa06-a21c512176a2/home)
Go to your Watson Assistant instance.


### 17. Click on Integrations in the left hand menu
![Step 17 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/6e1fc3aa-ea5d-46e0-a107-481f10de8a15/29a00ac7-ecc7-4871-a8e2-c64986f980f5.png?crop=focalpoint&fit=crop&fp-x=0.0670&fp-y=0.8425&fp-z=2.2811&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=-6&mark-y=381&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0zNzkmaD02MSZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 18. Click on Build custom extension
![Step 18 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/1f17f2a5-d8cb-4332-be76-e7ab088cd86c/f0d8ec8f-3ff0-4216-95a9-8f9937d0e4bb.png?crop=focalpoint&fit=crop&fp-x=0.1002&fp-y=0.5297&fp-z=2.3075&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=93&mark-y=278&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0zNjkmaD04NyZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 19. Click on Next
![Step 19 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/6b4a7deb-2fbf-45c7-9293-e1a6aaa0a527/3d6cc30e-ae50-41e6-98ca-9f780dc7a408.png?crop=focalpoint&fit=crop&fp-x=0.9515&fp-y=0.1084&fp-z=2.7902&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=927&mark-y=142&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0yMjAmaD0xMDUmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D)


### 20. Type "NS-Extension"
![Step 20 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/e68d20da-b2ae-48de-85f0-1eb1b4572633/71e5c6f0-90e6-4989-8c1f-7d0130c1d6d1.png?crop=focalpoint&fit=crop&fp-x=0.2210&fp-y=0.4171&fp-z=1.6944&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=154&mark-y=294&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz01OTAmaD01NCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 21. Click on Next
![Step 21 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/8d0c30c7-b2d6-4bac-a90c-8f0c11487acb/34a7449c-32cc-4953-805b-33e6e836bdd8.png?crop=focalpoint&fit=crop&fp-x=0.9515&fp-y=0.1084&fp-z=2.7902&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=927&mark-y=142&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0yMjAmaD0xMDUmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D)


### 22. Click on Drag and drop your OpenAPI file from Neural Seek here or click to upload
![Step 22 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/b127881b-6cb3-480c-a144-710afc8251a2/dbd96341-59e9-42f5-a0c4-ab563c0a360b.png?crop=focalpoint&fit=crop&fp-x=0.2734&fp-y=0.4213&fp-z=1.4387&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=131&mark-y=271&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz02ODImaD0xMDAmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D)


### 23. Click on Next
![Step 23 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/5fa196ee-dae2-4d40-8ecb-2be0b9342ddd/c840d4fd-35eb-47fb-a028-42ea6c138099.png?crop=focalpoint&fit=crop&fp-x=0.9515&fp-y=0.1084&fp-z=2.7902&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=927&mark-y=142&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0yMjAmaD0xMDUmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D)


### 24. Click on Add on your NS-Extension
![Step 24 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/d13049b5-5185-4e97-8862-2e796a7c51bf/8cb41d31-b5c7-4515-9147-f38557419b5b.png?crop=focalpoint&fit=crop&fp-x=0.7617&fp-y=0.6361&fp-z=2.7902&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=488&mark-y=269&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0yMjQmaD0xMDUmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D)


### 25. Click on Add
![Step 25 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/3f0a9908-0aaf-41d1-956f-1c80515e7c58/c6ca138b-b0be-4f20-bf7d-0c35ee7d7639.png?crop=focalpoint&fit=crop&fp-x=0.6200&fp-y=0.5683&fp-z=1.9911&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=308&mark-y=273&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz01ODQmaD05NiZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 26. Click on Next
![Step 26 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/cf8bec73-f9ef-4398-84d4-d2eb2525fa43/10e35da4-3677-40dc-b786-d1748ca7b056.png?crop=focalpoint&fit=crop&fp-x=0.9487&fp-y=0.1084&fp-z=2.7902&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=909&mark-y=142&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0yMzkmaD0xMDUmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D)


### 27. Click on No authentication
![Step 27 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/3410a212-456e-4153-8dd8-356d68d02cae/4cf99e87-9f01-41c8-8bac-1f3eb4fb552e.png?crop=focalpoint&fit=crop&fp-x=0.2171&fp-y=0.4088&fp-z=1.6944&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=146&mark-y=294&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz01OTAmaD01NCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 28. Click on API key auth
![Step 28 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/5a656232-eabd-4fd2-974a-0e6f5d84931e/3392c678-f2ef-4ae6-ab18-4a26d0269f35.png?crop=focalpoint&fit=crop&fp-x=0.2171&fp-y=0.4922&fp-z=1.6944&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=146&mark-y=294&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz01OTAmaD01NCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 29. Paste input
![Step 29 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/9fbfd5d6-0752-4b73-b1ef-eca6f09ca349/e61097d5-4643-47ba-9a30-8dd8d113c6d7.png?crop=focalpoint&fit=crop&fp-x=0.2171&fp-y=0.4922&fp-z=1.6944&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=146&mark-y=294&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz01OTAmaD01NCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 30. Click on Next
![Step 30 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/09206b24-1f66-4042-9ea3-adba3af00c04/b8621cda-7ab1-41c5-96b4-462f89d0735b.png?crop=focalpoint&fit=crop&fp-x=0.9403&fp-y=0.1084&fp-z=2.7902&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=880&mark-y=142&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0yMzkmaD0xMDUmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D)


### 31. Click on Close
![Step 31 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/2c0bc7a0-02f0-4ff1-ae03-4f9316e0b85a/36631c4a-7656-4317-ad43-50a903c70157.png?crop=focalpoint&fit=crop&fp-x=0.8404&fp-y=0.1084&fp-z=2.7902&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=550&mark-y=142&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0yMzImaD0xMDUmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D)


### 32. Click on Actions
![Step 32 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/ff7e33ff-d793-4781-b40e-3e864346c023/51b650b9-ef28-4018-9c62-ed0def86985c.png?crop=focalpoint&fit=crop&fp-x=0.0670&fp-y=0.1270&fp-z=2.2811&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=-6&mark-y=166&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0zNzkmaD02MSZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 33. Click on Create action
![Step 33 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/1af51ae3-bcee-4d5c-aa92-18bd9f58517e/77cdefca-4ef4-4eca-b124-9e3f64003554.png?crop=focalpoint&fit=crop&fp-x=0.2868&fp-y=0.5728&fp-z=2.5183&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=453&mark-y=293&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0yOTMmaD05NCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 34. Click on Quick start with templates…
![Step 34 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/d64147e5-94ef-47ab-9764-c3ea06b55151/2a89351e-2a57-4c23-9aa4-bebced3a8ce5.png?crop=focalpoint&fit=crop&fp-x=0.5960&fp-y=0.4724&fp-z=2.0189&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=363&mark-y=209&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz00NzMmaD0yNjImZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D)


### 35. Click on NeuralSeek Starter kit
![Step 35 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/250bc614-f943-4cf6-b5ce-08bfbef797c2/a7b51d74-b615-4162-99e7-42a4c9fd8a34.png?crop=focalpoint&fit=crop&fp-x=0.5000&fp-y=0.5399&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=-3&mark-y=29&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0xMjA1Jmg9Njc2JmZpdD1jcm9wJmNvcm5lci1yYWRpdXM9MTA%3D)


### 36. Click on Select this starter kit
![Step 36 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/734b39f1-fd9f-4ac6-84c7-90e9bfb7d71c/3bf1d590-07ee-4d84-85a5-0253f209d97f.png?crop=focalpoint&fit=crop&fp-x=0.8147&fp-y=0.1585&fp-z=2.8475&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=394&mark-y=257&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz00MTImaD05OSZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 37. Click on Add templates
![Step 37 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/0a7eeb47-9bd7-45b0-b145-45fecaebe2d8/39172879-a2f9-4744-9a6d-a3ac0d78eb2f.png?crop=focalpoint&fit=crop&fp-x=0.9336&fp-y=0.9764&fp-z=4.0000&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=549&mark-y=520&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz02NjQmaD0xOTMmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D)


### 38. Click on NeuralSeek search
![Step 38 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/869d544e-2bd8-4561-8013-549c6bf879c5/fbab32cf-1c75-42da-a522-ba16c7162aeb.png?crop=focalpoint&fit=crop&fp-x=0.3108&fp-y=0.2559&fp-z=1.8368&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=331&mark-y=301&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz01MzkmaD0zNyZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 39. Click on Step 3…
![Step 39 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/99124610-5ea6-4277-943c-e96dc6450b3b/8b5fa60f-9b80-46de-8c6f-a55b6306b298.png?crop=focalpoint&fit=crop&fp-x=0.1074&fp-y=0.4877&fp-z=1.9256&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=-5&mark-y=266&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz01MDcmaD0xNDgmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D)


### 40. Click on Edit extension
![Step 40 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/ec01c66c-2147-430c-a3cd-338d009432a6/32f0cc90-ef07-4344-a8f2-cba505b80fb0.png?crop=focalpoint&fit=crop&fp-x=0.2804&fp-y=0.8140&fp-z=2.6722&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=481&mark-y=306&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0yMzgmaD03MiZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 41. Click on Missing extension
![Step 41 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/309e3e42-146e-436a-8ae2-781585ef6cb3/948c1e74-3dbb-49a5-8ec5-877afb8e2df3.png?crop=focalpoint&fit=crop&fp-x=0.5000&fp-y=0.3081&fp-z=1.3638&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=218&mark-y=264&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz03NjMmaD00NCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 42. Click on NS-Extension
![Step 42 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/9d49a57d-8995-49af-a241-3c6512a55b67/cdae08c1-63c5-4dca-b9cb-e8fe9bbfddc6.png?crop=focalpoint&fit=crop&fp-x=0.5000&fp-y=0.3474&fp-z=1.3638&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=218&mark-y=300&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz03NjMmaD00NCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 43. Click on Choose an operation
![Step 43 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/c4068e0b-980f-4d8f-9932-f0d0edbda7c4/c8ac9f24-5546-418e-a99f-43bb608273b0.png?crop=focalpoint&fit=crop&fp-x=0.5000&fp-y=0.4163&fp-z=1.3638&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=218&mark-y=318&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz03NjMmaD00NCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 44. Click on Seek an answer from NeuralSeek
![Step 44 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/19b6049e-a870-4768-ae29-e72d5566df2e/5eec6685-8da8-4e9c-aaa7-41b84b81f242.png?crop=focalpoint&fit=crop&fp-x=0.4958&fp-y=0.2579&fp-z=1.3638&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=225&mark-y=217&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz03NTAmaD00NCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 45. Click on Set variable:  question
![Step 45 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/2a121f7a-2e48-4fa7-8fdc-143199b03dd2/a2254fa8-b0f5-4df1-8186-9714b4221546.png?crop=focalpoint&fit=crop&fp-x=0.5000&fp-y=0.5000&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=645&mark-y=541&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz01MTQmaD01MyZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 46. Click on Session variables
![Step 46 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/7bbbd9b3-c2bb-4bb9-aa17-2dcdc555e0d5/ea3e476c-cf53-4500-8a9a-96e68f9284e9.png?crop=focalpoint&fit=crop&fp-x=0.6032&fp-y=0.4380&fp-z=2.1192&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=381&mark-y=306&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz00MzcmaD02OCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 47. Click on query_text
![Step 47 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/2474553d-5852-4301-ab13-7fef6221f4a0/52ccac16-8140-4a5f-a29a-5a12382aa652.png?crop=focalpoint&fit=crop&fp-x=0.5951&fp-y=0.4321&fp-z=2.1575&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=388&mark-y=306&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz00MjMmaD02OSZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 48. Click on Set variable:  context
![Step 48 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/40d4035b-810b-4619-b5e6-b773641c0078/e4927bad-37ab-48dd-8f50-0784dbc41962.png?crop=focalpoint&fit=crop&fp-x=0.5000&fp-y=0.5000&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=592&mark-y=286&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz00MTQmaD00NiZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 49. Click on Session variables
![Step 49 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/d4a35489-f023-476c-8da1-a57551c1deee/8fa39e4b-b5d9-448a-8546-4eefa729b476.png?crop=focalpoint&fit=crop&fp-x=0.5893&fp-y=0.4557&fp-z=2.1192&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=381&mark-y=306&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz00MzcmaD02OCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 50. Click on query_context
![Step 50 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/2f13533a-2aa0-4535-a570-5ef27ed07980/946458d4-b867-47af-94bd-ac5dbf34e66e.png?crop=focalpoint&fit=crop&fp-x=0.5851&fp-y=0.4951&fp-z=2.1575&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=388&mark-y=306&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz00MjMmaD02OSZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 51. Click on Apply
![Step 51 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/44b460aa-dca9-437e-87c1-7878347a57c6/932f4baf-647f-4eb2-b099-11fa9d4e04ae.png?crop=focalpoint&fit=crop&fp-x=0.6200&fp-y=0.8888&fp-z=1.9911&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=308&mark-y=482&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz01ODQmaD05NiZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 52. Click on Save
![Step 52 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/399e893d-ec1d-4f21-a26f-ab3047c1b3f3/84471334-b6bb-4416-913d-7ca975fe43e6.png?crop=focalpoint&fit=crop&fp-x=0.9593&fp-y=0.0709&fp-z=2.8160&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=1010&mark-y=83&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0xMDYmaD0xMDYmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D)


### 53. Click on Set by assistant
![Step 53 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/b19de088-8c8e-4eda-b1a8-7a68170da325/9f32031f-1a14-476c-92be-c88f0f54116d.png?crop=focalpoint&fit=crop&fp-x=0.0787&fp-y=0.1890&fp-z=2.4494&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=72&mark-y=282&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0zMTgmaD02NiZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 54. Click on No action matches
![Step 54 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/ab118bd0-04fa-47e3-b7da-cacc603d464a/10753d5a-5b32-424e-8696-1b02d7f50206.png?crop=focalpoint&fit=crop&fp-x=0.1908&fp-y=0.2303&fp-z=2.6923&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=485&mark-y=313&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0yMzEmaD01NCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 55. Click on Step 2 Delete
![Step 55 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/7eaefc1c-c22d-4fc6-b407-69db8908b11d/1fc463f0-ebfb-413f-92d9-3ce669907b77.png?crop=focalpoint&fit=crop&fp-x=0.2026&fp-y=0.4321&fp-z=2.8798&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=554&mark-y=294&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz05MyZoPTkzJmZpdD1jcm9wJmNvcm5lci1yYWRpdXM9MTA%3D)


### 56. Click on delete…
![Step 56 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/c7849dce-8e3c-417c-9574-595701304051/fc96c12e-3884-488d-adf2-f21138fc469b.png?crop=focalpoint&fit=crop&fp-x=0.5901&fp-y=0.5591&fp-z=2.0631&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=371&mark-y=290&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz00NTcmaD05OSZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 57. Click on Step 1…
![Step 57 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/a4ceafee-e805-4761-abd2-676f202e3ad0/abd55445-2bae-402e-bc76-7268346574c7.png?crop=focalpoint&fit=crop&fp-x=0.1116&fp-y=0.2643&fp-z=1.8951&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=-5&mark-y=251&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz01MTgmaD0xNzkmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D)


### 58. Click on Delete condition in Conditions
![Step 58 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/00db9806-6cd0-4364-af28-04f13b18f0b3/24af48ad-dbda-4987-b629-72add99eec13.png?crop=focalpoint&fit=crop&fp-x=0.5000&fp-y=0.5000&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=954&mark-y=226&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz00OCZoPTQ4JmZpdD1jcm9wJmNvcm5lci1yYWRpdXM9MTA%3D)


### 59. Click on End the action
![Step 59 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/46280c9d-e808-409d-a769-7bb3a79f2907/916edeb6-bfd7-44ac-89f2-8a240323d87a.png?crop=focalpoint&fit=crop&fp-x=0.4710&fp-y=0.5246&fp-z=1.3239&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=238&mark-y=315&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz03MjMmaD01MCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 60. Click on Go to another action
![Step 60 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/d368a1c4-a8d7-41a3-81dd-f5aeb34429d6/f358f0c2-81c6-4812-859f-3fa5ea8b9237.png?crop=focalpoint&fit=crop&fp-x=0.3066&fp-y=0.6344&fp-z=2.3437&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=422&mark-y=306&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0zNTYmaD02NyZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 61. Click on Go to
![Step 61 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/981bb9f3-55df-414f-8eda-442ac6035e0b/9281995e-8171-417d-aee9-de9f7c7ecfa3.png?crop=focalpoint&fit=crop&fp-x=0.4997&fp-y=0.4793&fp-z=1.5467&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=278&mark-y=315&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz02NDMmaD01MCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 62. Click on NeuralSeek search
![Step 62 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/44d49e04-71d4-46f5-b6da-139ee6c0b3c0/a2f940bf-c927-4146-bb11-d93933943f73.png?crop=focalpoint&fit=crop&fp-x=0.4997&fp-y=0.5581&fp-z=1.5467&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=278&mark-y=315&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz02NDMmaD01MCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 63. Click on Apply
![Step 63 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/e9486e26-908d-42f9-8546-ca6dd26d59e7/baa2c460-0bcd-4df7-ad46-96789fb17f2a.png?crop=focalpoint&fit=crop&fp-x=0.5901&fp-y=0.6043&fp-z=2.0631&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=371&mark-y=290&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz00NTcmaD05OSZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 64. Click on Save
![Step 64 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/e0d1f13a-3ac1-4145-bf61-7baeb20e4088/305dd390-1de3-4a9b-b822-961f5ed46fb1.png?crop=focalpoint&fit=crop&fp-x=0.9593&fp-y=0.0709&fp-z=2.8160&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=1010&mark-y=83&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0xMDYmaD0xMDYmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D)


### 65. Click on Close
![Step 65 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/241cbebf-4496-4f6e-9192-78fc8d60ea26/564638f5-6f11-442c-aa8d-f55b22a254f1.png?crop=focalpoint&fit=crop&fp-x=0.9866&fp-y=0.0709&fp-z=2.8160&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=1102&mark-y=83&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0xMDYmaD0xMDYmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D)


### 66. Click on Preview
![Step 66 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/b617a1cd-4431-46c0-b385-96e712e1b618/5b8f2790-7b0a-4275-8923-fd8be22f85e1.png?crop=focalpoint&fit=crop&fp-x=0.0670&fp-y=0.1594&fp-z=2.2811&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=-6&mark-y=217&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0zNzkmaD02MSZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 67. Click on Copy link to share
![Step 67 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/bc62c0f7-a80e-4f85-ab0f-3659b61ee3d5/8fac8226-2f39-4000-aaec-e143805c2748.png?crop=focalpoint&fit=crop&fp-x=0.6688&fp-y=0.0728&fp-z=2.5896&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=429&mark-y=94&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0zNDImaD02OSZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 68. Click on Open the chat window
![Step 68 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/bcb93368-753b-48bf-9024-1e8eba67bfd5/ee014236-63ba-4baf-9d04-d0511d59ce3a.png?crop=focalpoint&fit=crop&fp-x=0.9420&fp-y=0.9114&fp-z=4.0000&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=793&mark-y=311&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0yNTcmaD0yNTcmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D)


### 69. Type "How can Cloud Pak 4 Data help my business?"
![Step 69 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/cb8004a0-fabf-42e8-9f79-a34e3abb7aa9/50bfa269-4e09-4ef7-a9e4-3c48a3878d39.png?crop=focalpoint&fit=crop&fp-x=0.7955&fp-y=0.9055&fp-z=3.0219&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=142&mark-y=383&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz05MTcmaD0yMDYmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D)


### 70. You now have your Watson Assistant set up with NeuralSeek
![Step 70 screenshot](https://images.tango.us/workflows/a5fafae1-abe9-4d04-9196-4be39eb9f941/steps/a9ff59eb-d9e3-4934-9fd8-9ea12ff93fc8/0b65374b-049b-4844-b9ef-51d9f8117c87.png?crop=focalpoint&fit=crop&fp-x=0.5000&fp-y=0.5000&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n)

<br/>
