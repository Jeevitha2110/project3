Task 3: Image Optimization Workflow
Objective: Automate image optimization (resizing, compression, etc.) upon image upload to reduce storage space and improve performance.

Steps:

Research image optimization tools or libraries (e.g., Sharp for Node.js).
Set up an AWS Lambda function triggered by S3 uploads (via S3 events) to automatically optimize uploaded images.
Store both the original and optimized images in the S3 bucket in different folders (e.g., /original/ and /optimized/).
Test image optimization and ensure optimized images are smaller but maintain good quality.
Deliverable: A workflow that automatically optimizes images upon upload to S3.



https://github.com/user-attachments/assets/42eadac8-349b-422d-a5d1-908a4aaaf81f

