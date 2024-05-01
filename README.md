# story-to-video
## Steps of generation 
### 1. Take input of story idea, story logline, story synopsis, outline, script
### 2. If any of the input is given try to extract the Director shot from the given input. can be done by having differnet steps of generation like story -> outline -> script ->  Directors shot. 
### 3. Director shot should contain a Image prompt which will be used further to create image for each shot. 
### 4. Initialise Stable diffusion/Any other text to image model.
### 5. Get All the images genereted by the model for each shot. 
### 6. Add all the image and also generate a Story text or dialouge text for background audio.
### 7. Add both video generated with all the images with any effect if required and audio (TTS) generated in the video file . I am using ffmpeg-python, gtts, pyttsx3.
