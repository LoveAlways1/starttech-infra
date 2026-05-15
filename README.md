
## Important Notes

CloudFront was planned as part of the architecture, but AWS account verification blocked creation of new CloudFront distributions during deployment.

The backend Docker image was successfully built and pushed to Amazon ECR. During final infrastructure verification, nginx was temporarily used on the EC2 backend instances to confirm that the ALB, Target Group, EC2 instances, Docker installation, Auto Scaling Group, and network routing were working correctly.
