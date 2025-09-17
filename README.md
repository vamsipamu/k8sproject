# k8sproject


AWS Fargate is a serverless compute engine for containers. It lets you run containers without managing EC2 instances. When used with Amazon EKS, it allows Kubernetes pods to run directly on Fargate, eliminating the need to provision or manage worker nodes.

How Fargate Works in a Kubernetes Cluster:

No EC2 nodes required: You don’t need to launch or manage EC2 instances for your pods.
Fargate Profiles: You define which pods should run on Fargate using profiles. These profiles match pods based on namespace and labels.
Pod-level isolation: Each pod runs in its own VM-like environment with dedicated CPU, memory, and network resources.
Integrated with EKS: AWS provides Fargate controllers that work alongside the Kubernetes scheduler to place pods on Fargate2
