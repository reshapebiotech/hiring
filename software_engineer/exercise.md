# Introduction

We aim to evaluate your programming skills in a comfortable setting by discussing a piece of code you've written. This approach ensures a stress-free dialogue about your solution, allowing us to better understand your engineering capabilities.

Thank you for participating in this process.

# Task Description

Your task is to develop a small Python API service that manipulates images in various ways, reflecting the central role of image processing in our RIS imaging machine. If Python is not your preferred language, please let us know so we can accommodate your preferences.

The API should support `jpeg` and `png` formats. All endpoints must support having the image included in the request as binary data and provided via URLs for the service to download (but not both at the same time).

There are some example images are in `images` subdirectory. Feel free to use these or any other you prefer.

### Endpoints

- **Center Crop**: Crop an image from the center using specified width and height.
- **Image Difference**: Compute and return a score representing the difference between two images. Explain the rationale behind your chosen method.
- **Image Hash**: Generate and return a hash that can uniquely identify an image. 

All endpoints must perform appropriate validation and return relevant HTTP status codes.

# Submission Guidelines

Please submit your solution including the source code, instructions necessary to run it, and any assumptions you've made during development.

## Evaluation Criteria

We will assess your submission based on the following:

- Compatibility with Mac/Linux
- Code clarity and structure.
- Fulfillment of the task objectives.
- Build reproducibility.

We look forward to discussing your solution and understanding your approach.
