# [Creating a new Box Application and Connecting it to Watson Discovery ](https://app.tango.us/app/workflow/1c96b5a8-e4e9-4427-b079-f9d074e325e6?utm_source=markdown&utm_medium=markdown&utm_campaign=workflow%20export%20links)

Created by Alex Boudreaux.

This tutorial walks through creating a new Box Application. I had to create it on a personal account not associated with my IBM Box enterprise account.

__Creation Date:__ June 9, 2023  
__Created By:__ Alex Boudreaux  
[View most recent version of the Tutorial on Tango.us](https://app.tango.us/app/workflow/1c96b5a8-e4e9-4427-b079-f9d074e325e6?utm_source=markdown&utm_medium=markdown&utm_campaign=workflow%20export%20links)



***




## # [Box Developers](https://ibmwatsonsandbox.app.box.com/developers/console/newapp)
Go to box.dev to create a Box developer account.


### 1. Once you have created a Box dev account, Click on Create New App
![Step 1 screenshot](https://images.tango.us/workflows/1c96b5a8-e4e9-4427-b079-f9d074e325e6/steps/100c938a-6671-439a-800d-f9afc0c94e2a/c80c1e5a-780b-4c4d-a505-197d9d136eda.png?crop=focalpoint&fit=crop&fp-x=0.9457&fp-y=0.1043&fp-z=2.9466&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=867&mark-y=169&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0yODImaD03OSZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 2. Click on Custom App…
![Step 2 screenshot](https://images.tango.us/workflows/1c96b5a8-e4e9-4427-b079-f9d074e325e6/steps/5b7bd69f-37af-42d5-b606-bc9aa91cb0e7/9a4e5138-28c5-4018-8f15-e9ba29d418a3.png?crop=focalpoint&fit=crop&fp-x=0.2262&fp-y=0.4213&fp-z=1.2141&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=216&mark-y=124&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0yMjcmaD00MzImZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D)


### 3. Type in App Name
![Step 3 screenshot](https://images.tango.us/workflows/1c96b5a8-e4e9-4427-b079-f9d074e325e6/steps/ea67eb07-8af6-465b-9a2e-ca07d9256e97/8f03023d-f100-4472-be4d-34d1a934c690.png?crop=focalpoint&fit=crop&fp-x=0.5003&fp-y=0.4094&fp-z=1.7487&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=315&mark-y=316&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz01NzAmaD00NyZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 4. Select a Purpose
![Step 4 screenshot](https://images.tango.us/workflows/1c96b5a8-e4e9-4427-b079-f9d074e325e6/steps/36636139-2a1c-4960-9134-452e85974b75/0c589705-eff7-404e-90cd-1552bcef1b05.png?crop=focalpoint&fit=crop&fp-x=0.5003&fp-y=0.6496&fp-z=1.7487&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=315&mark-y=315&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz01NzAmaD00OSZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 5. Click on Integration
![Step 5 screenshot](https://images.tango.us/workflows/1c96b5a8-e4e9-4427-b079-f9d074e325e6/steps/f1dc2600-e9f5-4d17-bc39-ce56db52f584/f019c193-deef-4f82-ab34-d8354532359c.png?crop=focalpoint&fit=crop&fp-x=0.4989&fp-y=0.4026&fp-z=1.7607&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=317&mark-y=314&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz01NjYmaD01MiZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 6. Select a Catagory 
![Step 6 screenshot](https://images.tango.us/workflows/1c96b5a8-e4e9-4427-b079-f9d074e325e6/steps/3188ff9c-875a-47ab-b6f7-168af3fcc3b8/bc1230d4-539f-4bae-b38d-48cb7aedfb58.png?crop=focalpoint&fit=crop&fp-x=0.4989&fp-y=0.6024&fp-z=1.7572&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=316&mark-y=315&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz01NjcmaD00OSZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 7. Click on Productivity
![Step 7 screenshot](https://images.tango.us/workflows/1c96b5a8-e4e9-4427-b079-f9d074e325e6/steps/04121196-f73c-45fc-a696-84bd05de36bf/d025af45-789f-4789-be15-ee442818c3ee.png?crop=focalpoint&fit=crop&fp-x=0.4989&fp-y=0.3740&fp-z=1.7607&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=317&mark-y=314&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz01NjYmaD01MiZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 8. Type "Watson Discovery"
![Step 8 screenshot](https://images.tango.us/workflows/1c96b5a8-e4e9-4427-b079-f9d074e325e6/steps/0bd3d620-2954-4f90-bcec-29d1b98a8e0a/b3466575-0b5f-4df2-a496-3c166ebca808.png?crop=focalpoint&fit=crop&fp-x=0.4989&fp-y=0.6791&fp-z=1.7572&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=316&mark-y=316&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz01NjcmaD00NyZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 9. Click on Next
![Step 9 screenshot](https://images.tango.us/workflows/1c96b5a8-e4e9-4427-b079-f9d074e325e6/steps/df9ccb4b-3154-4e86-a43e-19d10aa5166f/7abbbf3e-0cff-462b-91cd-553e0e7447ac.png?crop=focalpoint&fit=crop&fp-x=0.6150&fp-y=0.7441&fp-z=2.9306&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=528&mark-y=293&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0xNDUmaD05NCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 10. Click on Create App
![Step 10 screenshot](https://images.tango.us/workflows/1c96b5a8-e4e9-4427-b079-f9d074e325e6/steps/865737eb-796d-4316-b0d7-90d22bf404bc/6ef146bc-87c0-4f2a-87be-dfeb6a09cc1f.png?crop=focalpoint&fit=crop&fp-x=0.6036&fp-y=0.7441&fp-z=2.7384&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=493&mark-y=296&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0yMTQmaD04OCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 11. Scroll down and Click on App + Enterprise Access…
![Step 11 screenshot](https://images.tango.us/workflows/1c96b5a8-e4e9-4427-b079-f9d074e325e6/steps/cb8ec41e-d7a4-4a5d-bfa4-62a91fee4925/5367accb-a837-46a5-ad71-f7d28fde26c1.png?crop=focalpoint&fit=crop&fp-x=0.5370&fp-y=0.5157&fp-z=1.8313&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=429&mark-y=187&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0zNDMmaD0zMDYmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D)


### 12. Click on Generate a Public/Private Keypair
![Step 12 screenshot](https://images.tango.us/workflows/1c96b5a8-e4e9-4427-b079-f9d074e325e6/steps/69406778-6a33-4019-b262-1704ac0fc1b7/0889dc70-67d1-445a-8e4e-d6ec381f81f1.png?crop=focalpoint&fit=crop&fp-x=0.4579&fp-y=0.5404&fp-z=2.2650&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=408&mark-y=309&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0zODUmaD02MSZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 13. Click on OK. It might ask you to verify with a text code that it sends to your phone. 
![Step 13 screenshot](https://images.tango.us/workflows/1c96b5a8-e4e9-4427-b079-f9d074e325e6/steps/e4b05e06-c3c6-4737-b7b3-ec2475f5cb9a/88bd56f4-b0fe-40e2-8b08-46ed20eace3f.png?crop=focalpoint&fit=crop&fp-x=0.5961&fp-y=0.5683&fp-z=2.8567&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=539&mark-y=275&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0xMjImaD05MiZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 14. Click 
![Step 14 screenshot](https://images.tango.us/workflows/1c96b5a8-e4e9-4427-b079-f9d074e325e6/steps/82370a16-870e-4287-ad79-a0f4d5e6fa61/b61c7733-8870-48aa-9073-926c7472d38d.png?crop=focalpoint&fit=crop&fp-x=0.5000&fp-y=0.5000&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n)


### 15. Create a folder and Add your documents to it
![Step 15 screenshot](https://images.tango.us/workflows/1c96b5a8-e4e9-4427-b079-f9d074e325e6/steps/cb48d3c4-4080-4dae-98e3-b29686c6f498/4f869961-6eed-4d2e-9653-ca08c62d36e4.png?crop=focalpoint&fit=crop&fp-x=0.5000&fp-y=0.5000&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n)


## # [IBM Watson Discovery](https://us-south.discovery.watson.cloud.ibm.com/v2/instances/crn%3Av1%3Abluemix%3Apublic%3Adiscovery%3Aus-south%3Aa%2Fead8711ba2cc4d08a16fd37427f4f01a%3A94115f22-a839-4316-b868-9a3b7680108d%3A%3A/projects/new/setup/type)
Go to your Watson Discovery instance


### 16. Click on New project
![Step 16 screenshot](https://images.tango.us/workflows/1c96b5a8-e4e9-4427-b079-f9d074e325e6/steps/22e2a3c7-4c00-4195-ab6a-960864bb8cd5/c9a55daa-0f98-4371-aa92-999b2de1d21f.png?crop=focalpoint&fit=crop&fp-x=0.9476&fp-y=0.3962&fp-z=2.8567&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=862&mark-y=275&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0zMTcmaD05MiZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 17. Type "box-collection"
![Step 17 screenshot](https://images.tango.us/workflows/1c96b5a8-e4e9-4427-b079-f9d074e325e6/steps/60d25429-568f-4d52-8155-1dfd3b9ab6b1/8d98e4fc-7ab2-48b6-844b-d4f400ea60d1.png?crop=focalpoint&fit=crop&fp-x=0.3822&fp-y=0.2461&fp-z=1.7624&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=317&mark-y=250&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz01NjYmaD01NyZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 18. Select "document_retrieval"
![Step 18 screenshot](https://images.tango.us/workflows/1c96b5a8-e4e9-4427-b079-f9d074e325e6/steps/b31c4055-524e-41b9-974c-fbb1f2aae590/238a09ab-b86a-4ea4-b814-92ab129c3ebc.png?crop=focalpoint&fit=crop&fp-x=0.5000&fp-y=0.5000&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=72&mark-y=204&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0zMzEmaD00NDcmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D)


### 19. Click on Next
![Step 19 screenshot](https://images.tango.us/workflows/1c96b5a8-e4e9-4427-b079-f9d074e325e6/steps/9a3b63ef-5e66-49b6-82b6-5b71e3c78297/6c755720-0e59-4cc4-a78f-e28a5eb7026c.png?crop=focalpoint&fit=crop&fp-x=0.9515&fp-y=0.9625&fp-z=4.0000&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=810&mark-y=470&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0zMTYmaD0xNTAmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D)


### 20. Click on Box
![Step 20 screenshot](https://images.tango.us/workflows/1c96b5a8-e4e9-4427-b079-f9d074e325e6/steps/34f2db2a-c84f-4d8a-8cc6-47cb5d20fdb9/fb7b3f0e-f334-4878-87bd-f44ac8f46cbf.png?crop=focalpoint&fit=crop&fp-x=0.6331&fp-y=0.2998&fp-z=2.0374&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=459&mark-y=196&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0yODImaD0yNDkmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D)


### 21. Click on Next
![Step 21 screenshot](https://images.tango.us/workflows/1c96b5a8-e4e9-4427-b079-f9d074e325e6/steps/9267d13f-a58b-4c9f-85a1-3ac5949477d3/fa94ed4d-fb77-46d8-b610-2f5021f8f63b.png?crop=focalpoint&fit=crop&fp-x=0.9515&fp-y=0.9625&fp-z=4.0000&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=810&mark-y=470&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0zMTYmaD0xNTAmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D)


### 22. Paste Credentials from the JSON file downloaded from Box
![Step 22 screenshot](https://images.tango.us/workflows/1c96b5a8-e4e9-4427-b079-f9d074e325e6/steps/944f86a6-9ec3-4797-873c-e2681fc25234/0b065ac5-6bcc-4682-9aa6-6cd5f647e162.png?crop=focalpoint&fit=crop&fp-x=0.5000&fp-y=0.5000&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=180&mark-y=1177&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz04NjYmaD03NSZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 23. Click on Next and Select the Box folder you would like to sync to Discovery 
![Step 23 screenshot](https://images.tango.us/workflows/1c96b5a8-e4e9-4427-b079-f9d074e325e6/steps/7b856a90-40e8-48ff-9410-5fab3e8421cf/5d5538f7-c533-42ea-9826-9bba26c66cde.png?crop=focalpoint&fit=crop&fp-x=0.9515&fp-y=0.9646&fp-z=4.0000&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=810&mark-y=508&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0zMTYmaD0xNTAmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D)

<br/>
