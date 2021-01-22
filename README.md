<h1 align="center">
	<img src="public/favicon.png" alt="Logo" width="50px"></a>
  QuickMark
</h1>

<h4 align="center">A robust tool that helps teachers mark their students' tests in one convenient location.</h4>


---

## About

**QuickMark** is a web-app which allows teachers to upload and mark students' tests in one convenient location. The inputted marks and/or comments are then available to be downloaded in a .csv file containing all the results.

**Try it here:** https://quickmark.online/ <br>

**[Hack the North 2020++](https://devpost.com/software/quickmark-arjq6v?ref_content=user-portfolio&ref_feature=in_progress): Selected as Hack the North 2020++ overall finalist.**

## Inspiration

In general, teachers are having difficulty teaching online during COVID, especially when marking digital tests. This is a result of many file types in different places, no good way to record scores or comments for each individual question, and even harder to return the students’ test back to them with the feedback.

## How we built it

Using the OpenCV module in Python, our application automatically crops each question for the teacher to mark, saving them a lot of time and unnecessary stress. The cropped images are displayed on the UI in a slideshow using Owl Carousel. We also used Node.js and Socket.io as an intermediary to connect the front-end with the image processing program written in Python. And lastly, our UI is built with vanilla HTML/CSS/JS to provide a minimalistic yet powerful experience for teachers.


## What's next for QuickMark

In the future, we hope to implement OCR (using the Google Cloud Vision API) to detect each question in case they are not in order, create a system to send the scores and comments back to the students, and incorporate with the Google Classroom API as many tests are turned in on that platform and to make it compatible with the Google Education Suite.
