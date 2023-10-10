# User-Engagement-on-YouTube-Videos

User Engagement on YouTube Videos
Overview
This project is focused on creating an application that gauges user engagement for YouTube videos. By analyzing a range of factors, including title sentiment score, comment sentiments, like-to-dislike ratio, comments-to-view ratio, likes-to-view ratio, and view-to-subscriber ratio, our application helps content creators and data analysts gain insights into the engagement levels of their videos.

Features
Title Sentiment Analysis: Utilizing a trained LSTM model, the application evaluates the sentiment of the video title, helping creators understand how the title might influence user engagement.

Comment Sentiment Analysis: Leveraging a trained logistic regression model, the application assesses the sentiments of comments on the video, providing insights into the overall sentiment of the audience.

Like to Dislike Ratio: Calculates the ratio of likes to dislikes, which can indicate the overall positive or negative reception of the video.

Comments to View Ratio: Measures the ratio of comments to views, helping creators identify the level of user interaction with their content.

Likes to View Ratio: Evaluates the ratio of likes to views, offering insights into how engaging the video is for viewers.

View to Subscriber Ratio: Analyzes the ratio of views to subscribers, indicating how effective the video is at attracting and retaining subscribers.

Installation
To run this application locally, follow these steps:

Clone this repository to your local machine:

bash
Copy code
git clone https://github.com/yourusername/user-engagement-on-youtube.git
Navigate to the project directory:

bash
Copy code
cd user-engagement-on-youtube
Install the required dependencies:

bash
Copy code
pip install -r requirements.txt
Start the application:

bash
Copy code
python app.py
Usage
Run the application using the instructions above.

Open a web browser and go to http://localhost:5000 to access the application.

Enter the URL of the YouTube video you want to analyze.

Click the "Analyze" button to obtain insights on user engagement for the specified video.
