# Real World Face Recognition Application
This project aims to develop an AI-powered facial recognition attendance system that ensures accurate and efficient identity verification. The system operates by building a dedicated face database through the following process:

  1. Face Extraction with Object Detection – Faces are automatically detected and cropped from images using advanced object detection techniques.

  2. Face Embedding Storage with GhostFaceNet – Each extracted face is encoded into a numerical vector embedding using the GhostFaceNet model, enabling robust identity representation.

  3. Face Matching – When a new image is provided, the system compares its embedding against the stored database to determine if it corresponds to an existing registered individual.

  4. User Data Enrollment – To register, each user is required to submit three personal face images. These images are processed and stored in the database as reference embeddings.

By leveraging AI-driven face recognition and vector-based matching, this system ensures secure, fast, and reliable attendance tracking, reducing manual errors and enhancing automation.
