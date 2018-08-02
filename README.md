# mafqood

## Inspiration
One of the main objectives of The Ministry of Haj and Umra based on their official website is guiding the lost pilgrims in coordination with The Saudi Arabian Boy Scouts Association (SABSA). It has established about 30 comprehensive service centers to receive pilgrims’ complaints and guiding lost pilgrims in the central region in Makkah Al-Mukarramah, Al-Madinah Al-Munawwarah, and the Holy Shrines. Moreover, critical personal identification documents or belongings that are lost are extremely difficult to find. All of the previous makes locating people or belongings a very time and energy consuming process for all parties concerned. Building on those efforts, our idea is to provide a fully automated system to locate and connect lost people to their group, family or friends using facial recognition; in addition to, locating lost objects using image processing.

## What it does
The system is composed of the following components:
- A web-based, mobile compatible app in which a user can register and create a profile with images and info of friends, family or group’s members, in addition to taking pictures of important documents (E.G: Passport, National ID)
- In the web app, a user can report a lost person an submitting his/her data as full name, recent photo, age and country name. The app will do matching with the current data, and it will notify the user of the lost person is detected.
- In the web app, a user can report that he/she has found a lost person and just take a recent picture to match with any lost reports.
- A user that finds any personal documents or belongings can just take a photo and upload it to the app along with which lost & found booth he dropped the item in. The system shall match with any previously saved item by any user and if not found will cache it until any user reports that it is missing from him.
- Well marked “Lost People” booths or control centers spread around the Holy Shrines that contain any smart device with a camera that the user can interact with for an automated experience. Any lost person can interact with the app to gather some info and take a picture for the facial recognition.
- All of the system's interfaces will be minimal and support multi languages for easier user experience.

## How we built it
- Vue.js for the web app and interface on the booth
- Firebase that supports the serverless architecture and acts as an integration layer for all system components
- Face-api.js for facial recognition
- Yolo9000 for object recognition
- Notification system through firebase and the webapp ui


