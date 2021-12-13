# Motivation


We would like to base our evaluation of your skills based on an some code written by you. Our intent is to have an evaluation session with you, where we talk about the solution, so we can have a relaxed discussion. The idea is to avoid stressing anyone out but still allow us room to identify your engineering skills.

Thank you for your time.


# Exercise

You are to build a small API service that can transform images in various ways. We have chosen this task, as images are central to our current imaging-machine; RIS. 


You should support `jpeg` and `png`. Images should be either supplied as binaries or urls that the service will download and use.

Endpoints:
- Center crop: Given width, height and an image. Crop it from the center with width and height
- Image difference: Given two images, output some score that measures the difference between two images. No right or wrong here, please just write some motivation your specific solution.
- Image hash: Given an image, output a hash that can be used to uniquely identify the image

All endpoints should be properly validated and provide relevant status codes. We will deeply appreciate if you are able to provide your solution in a containerized format.


# Solution
In your solution, please include the code, any information we may need to run it as well as any assumptions you have made that we should be aware of.

## Goals and scoring

These are the points we will evaluate your code based on:

- Runnable on our machines (mac/linux x86) 
- Code readability
- If the requirements were fulfilled
- Build reproducibility - as much as possible, make your build reproducible