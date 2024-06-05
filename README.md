# **Face Recognition Image Matcher**
## Description
# This Python script utilizes the face_recognition library to compare a reference image against a set of images in a specified directory to identify matches based on facial features. The script loads a reference image, processes it to extract facial feature vectors, and then iterates through a collection of images to detect and compare faces.

## Features
# Load and Encode Faces: Converts images into a facial feature vector using deep learning models.
# Face Matching: Compares each image in the directory against a reference image to check for facial similarities.
# Robust Handling: Efficiently handles multiple images and detects if no faces are found within an image.
## How It Works
# Setting the Environment: The script defines a path to the directory containing images and specifies the reference image.
# Image Loading and Encoding: Each image, including the reference image, is loaded and encoded into a unique facial feature vector.
# Comparison: The script compares the encoded vector of each image against the encoded vector of the reference image to determine a match based on a similarity threshold.
#  Results: Outputs whether each image matches the reference image and handles cases where no faces are detected.
# Usage
To run this script, ensure you have Python installed along with the face_recognition library. Place the script in your project directory:

# Install the required library using pip install face_recognition.
# Modify the images_directory and reference_image_path in the script to point to your images and reference image.
# Run the script using Python to see the matching results.
## Requirements
# Python 3.x
# face_recognition library
# Images with detectable faces for accurate comparison
# This script is ideal for developers and researchers needing to perform facial recognition tasks to identify similar or duplicate faces across multiple images.

# **Images Analyzed **
![bushsr](https://github.com/Elliott-dev/Simple-Facial-Recognition-Application/assets/94668201/abadf6ea-45d4-47a1-808f-57ebe93582ef)
![bush02](https://github.com/Elliott-dev/Simple-Facial-Recognition-Application/assets/94668201/ce57c95f-9b2c-41eb-881e-a6c966c0dba5)
![bush](https://github.com/Elliott-dev/Simple-Facial-Recognition-Application/assets/94668201/c04a49f1-b121-496a-b018-4ce7ef9ce4e6)
![trump02](https://github.com/Elliott-dev/Simple-Facial-Recognition-Application/assets/94668201/371ef291-b8ca-4179-98cc-f9972ba2762a)
![trump01](https://github.com/Elliott-dev/Simple-Facial-Recognition-Application/assets/94668201/ddecb328-08fa-4c38-98c6-fb06843abf94)
![trump](https://github.com/Elliott-dev/Simple-Facial-Recognition-Application/assets/94668201/57d3e5f0-95fe-40ad-8e1b-1a5666fa5731)
![reagan02](https://github.com/Elliott-dev/Simple-Facial-Recognition-Application/assets/94668201/385bb659-1302-48d5-ae50-651ff4a714f1)
![reagan](https://github.com/Elliott-dev/Simple-Facial-Recognition-Application/assets/94668201/2ba8217b-5832-4453-b766-787bbcce5917)
![obama02](https://github.com/Elliott-dev/Simple-Facial-Recognition-Application/assets/94668201/b4342bc7-4d2e-456c-8222-99048d5eddd0)
![obama](https://github.com/Elliott-dev/Simple-Facial-Recognition-Application/assets/94668201/c5a8e6ad-9ae4-4041-8241-8aef8801bcd0)
![clinton02](https://github.com/Elliott-dev/Simple-Facial-Recognition-Application/assets/94668201/211a9d16-7fd2-44d3-b0a0-1fbc94c03657)
![clinton](https://github.com/Elliott-dev/Simple-Facial-Recognition-Application/assets/94668201/08781fd5-84e4-409b-a194-dbb9c2189ddc)
![carter](https://github.com/Elliott-dev/Simple-Facial-Recognition-Application/assets/94668201/a06ee517-d16d-4c84-83e9-bfb2b32dcb0e)
