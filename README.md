### Job description

Event Gates is looking for Deep Learning / Computer Vision engineers who are willing to fulfill following tasks instead of sending a plain old CV. If you think you are a gifted DL/CV developer and would like to show your abilities follow these guidelines below. Do not forget to check out disclaimers at the bottom of the job description.

We would like you to use your abilities in a small python ( use version 3.6) project that is applicable to CV/DL domain. You should consider this as a time-based assignment which should take half a day or a day at the most. Also there won't be any pointers aside from the instructions and requirements section.

### Instructions
- When you feel ready to give this a try, start by creating a private repo in github and add egt-cvdl github account as a collaborator. Also please add your cv to the repo in pdf format and perform an initial commit with the message: 'cv/dl application, initial commit'
- When you're ready to start working on the actual project, create an issue.
- Finally when you're done, submit a PR to the issue you've created to let us know that you're ready to be reviewed
- We will contact successful applicants to proceed with the application. (Please make sure you have given your contact info.)

### Requirements
You're required to create a small project that takes several videos as an input, make small adjustments and saves as a separate single video. The details of the assignment are as follows;

- The videos are of different dimensions, the output should be 1920x1080@5 FPS
- You should number every frame with respect to total frames of the merged videos and with respect to current video's total frames. So if there are 3 videos each consisting 30 frames and we are on the 3rd frame of the second video the current frame should show: current: 3/30, merged: 33/90
- You should save a histogram.pickle that keeps the dominant color in each frame. Continuing with the example in the former item, this should be a dictionary of the form: { 0: 'red', 1:'blue', 2:'green',...,89:'red'}
- The video saving functionality should receive the video frames with a queue in a separate thread and you should try and explain why, in the related part in the code.
- BONUS: if all of this is too easy for you, try doing video saving in a separate process.

### DISCLAIMER

We've already implemented any noteworthy features or functionalities in this document.
This assignment is only for you to demonstrate your expertise in this domain. We still may use any good ideas. By applying to this position you accept to renounce any rights on the work you submit. Event Gates does not commit itself to hire somebody on the basis of this job listing or application to it, completed successfully or not.

We will not respond to applicant who do not complete below steps.
