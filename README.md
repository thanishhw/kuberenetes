🐳 K8s – 3/3
 Kubernetes Project – 1/2
Enough theory — time to do a real project! 💻🔥
There’s still more to share (Volumes, HPA/VPA, Affinities, Taints, Tolerations, Ingress...) — but let’s build practical end-to-end Kubernetes project.

📄 Check the attached file for a full breakdown.

End-to-End Kubernetes Workflow:
🔹 Clone code from a private GitHub repo → write a Dockerfile → build & run the container
 🔹 Modify the app inside a running container → commit changes → create a versioned image
 🔹 Push both v1 and v2 images to a private Docker Hub repo
 🔹 Launch an AWS EC2 instance and set up the environment
 🔹 Provision an EKS cluster with spot nodes using eksctl
 🔹 Use Kubernetes Secrets to securely pull private images
 🔹 Deploy using a LoadBalancer service with readiness/liveness probes
 🔹 Apply a zero-downtime rolling update by switching to image v2 ✅

⚙️ There’s a fair bit of manual work involved in this pipeline — but every step can and should be automated. This is where true DevOps value shines: making deployments consistent, reliable, and fast.

💡 This isn’t just a demo — it’s a practical DevOps workflow from local containerization to secure cloud-native deployment on AWS.

