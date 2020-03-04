# The-Vision
An interactive glove for blind people that identifies the objects in front of them using Arduino Spy Camera and Microphone.

Inspiration -The fact that this project might help so many people in the world. There are so many cool technologies available out there but there are not as many cheap products available that would help people with disabilities. So we thought why not create a product at minimum cost and make it available to the people in need.

What it does -When you run the code, your webcam will start and on pressing key 'c', you will be able to listen to the description of the objects that you show to the camera.

How we built it -We used Google Could API to read an image and detect the objects in that image. Then we wrote code to take live video and used image detector on this video to get the description of the objects in the video. Then we used Google Could API to convert text to speech and converted a text file in mp3 file and then read the mp3 file to the user.

Challenges we ran into -Linking credentials file for APIs with the code and linking python code with arduino.

Accomplishments that we're proud of -We are proud of our project because we are going to help a lot of people in the world.

What we learned -We learned a lot about Google Cloud APIs and Arduino. Also it was a good opportunity to realize that there can be so many cool things that can be done with these APIs.

What's next for The-Vision -I am going to try to sensor technology to this project to know how far away the object is. Also, we are planning on creating a chrome extension that helps blind people listen to the websites including pictures, videos, etc. We are going to try to make this product as cheaper as possible so that most people can make use of it.

Built With -Python, Google Cloud APIs (Text to speech, Image detector), Arduino, ArduCam.

To run it-First run the python code, then start the ArduCam and capture the live video.
