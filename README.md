# aws-face-recognition-autoscaler
Cloud-based face recognition system using Python/Flask that auto-scales EC2 instances (0-15) via custom logic. Uses SQS for decoupled messaging, S3 for storage, and a PyTorch model. Handles 100+ requests at &lt;1.2s latency while cost-optimizing through scale-to-zero architecture. Built with Boto3 without AWS Auto Scaling service.
