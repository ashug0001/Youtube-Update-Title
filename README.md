# Youtube-Update-Title
This project update title or video with number of video on a specific video


# Get YouTube API Auth Key

Step 1: Go to http://code.google.com/apis/console and Login Using Valid Google Account.  
Step 2: Create Project and obtain authorization credentials using  [this](https://developers.google.com/youtube/registering_an_application) link.  
Step 3: Download **JSON** file and save it as `client_secret.json` in the project working directory.  

# Change Title

Step 1: Open  `index.js`.
Step 2: Search for 'CHANNEL-ID' and replace it with your channel ID.  
Step 3: Search for 'VIDEO-ID' and replace it the video id of the video whose Title you want to change as per view and save the file.  
Step 4: First run `npm install` to install all dependencies.  
Step 5: Run `node index.js` to update the title.
