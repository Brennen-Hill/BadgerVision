# With Badger Vision, We won at Hack Midwest!

## The Competition: Hack Midwest
Hack Midwest is the largest hackathon in the region, attracting top talent from across the country. Over 300 developers were selected to compete, including experts from leading organizations and universities.

## The Best Enterprise Scale Buisness Solution: $2,500
We were awarded $2,500 for building the best enterprise-scale business solution using Pinata's Files API or IPFS API. After 23 intense hours of coding with only a 1 hour break to sleep, we presented our solution to the judge and were victorious. Here’s how we made it happen.

## The Problem: Prosopagnosia
Prosopagnosia, or face blindness, affects around 2.5% of the population—more than 8 million people in the U.S. alone. This condition makes it difficult to recognize faces or interpret facial expressions, and as of now, no therapies offer lasting improvements (PsyPost).

## Our Solution: Badger Vision
Introducing Badger Vision, an open-source and easy to use tool designed to help individuals with face blindness by identifying both faces and emotions. If a recognized face is detected, the tool announces the person’s name. For unknown faces, a unique chime is played, with the exact same chime repeating upon subsequent encounters. This use of audio cues makes it easier to recognize faces. Additionally, our model detects and announces emotions, making it easier to interpret social cues.

## How it Works:
Users authenticate the Badger Vision app via a QR code, which downloads pre-configured AI artifacts and settings stored on Pinata. The app streams video through our RTMP server to AI recognition servers, leveraging the Zoom Video SDK. The camera, which can be discreetly placed in a shirt pocket, identifies faces and emotions using deep learning and convolutional neural networks. Detections are sent back to the app in real time over a WebSocket connection,

## Solving the Unsolvable
When we ran into challenges working with Zoom, we talked with one of the present sponsors, who had been working as a Zoom engineer for over a decade. The seasoned Zoom engineer said our idea of live-streaming video through Zoom to a server for real-time data analysis was almost certainly impossible. We engineered a solution by writing our own Python API, proving that live-streaming video for this use case was possible.

## Future Work:
If we acquire the funding to continue work on this project, we would like to pursue several goals. We would perform clinical trials on a diverse population to evaluate effectiveness. We would further refine the codebase and mobile client. We would expand the functionality of the application to AR and VR headsets, including smart glasses.

## Team Members
Brennen Hill, Rahul Hathwar, Max Maeder, Utkarsh Sharma, and Jeremy Kintana. I am grateful to have worked with such an amazing team.
