Lộ trình học DevOps trong 12 tuần
---------------------------------------------------------------------------------------------------------------
Tuần 1: Nền tảng DevOps và Linux cơ bản
Mục tiêu: Hiểu khái niệm DevOps và làm quen với Linux.
Lý thuyết:
DevOps là gì? Văn hóa DevOps, sự khác biệt với Agile.
Các giai đoạn trong DevOps: CI/CD, Infrastructure as Code (IaC), monitoring.
Linux cơ bản: File system, users/permissions, networking.
Thực hành:
Cài Ubuntu trên máy ảo (VirtualBox/VMware) hoặc WSL2 trên Windows.
Làm quen với lệnh Linux: ls, cd, mkdir, rm, chmod, chown, ps, top, netstat.
Viết shell script đơn giản (ví dụ: tự động backup thư mục).
Dự án nhỏ: Tạo script Bash để kiểm tra dung lượng đĩa (df -h) và gửi email thông báo nếu vượt 80%.
Tài liệu:
Roadmap.sh - DevOps
Linux Journey
Video: “Linux for Beginners” (freeCodeCamp trên YouTube).
Thời gian: 10-12 giờ (2-3 giờ/ngày).
---------------------------------------------------------------------------------------------------------------
Tuần 2: Quản lý mã nguồn với Git
Mục tiêu: Thành thạo Git và quy trình làm việc với repository.
Lý thuyết:
Git là gì? Repository, branch, commit, merge.
Quy trình làm việc với Git: feature branch, pull request (PR), code review.
GitHub/GitLab/Bitbucket: Tạo repository, fork, clone.
Thực hành:
Cài Git và cấu hình (git config --global).
Thực hành lệnh: git init, git add, git commit, git branch, git merge, git rebase, git pull, git push.
Tạo repository trên GitHub, đẩy code và tạo PR.
Dự án nhỏ: Tạo repository, thêm README, tạo branch feature/add-readme, merge vào main qua PR.
Tài liệu:
Git Documentation
Atlassian Git Tutorials
Video: “Git & GitHub Crash Course” (Traversy Media).
Thời gian: 8-10 giờ.
---------------------------------------------------------------------------------------------------------------
Tuần 3: Hiểu về networking và web server
Mục tiêu: Nắm cơ bản về networking và cấu hình web server.
Lý thuyết:
Networking: TCP/IP, DNS, HTTP/HTTPS, load balancer, firewall.
Web server: Apache, Nginx, cách xử lý request.
Port, proxy, reverse proxy.
Thực hành:
Cài Nginx trên Ubuntu, cấu hình để chạy website tĩnh.
Tìm hiểu file cấu hình Nginx (/etc/nginx/nginx.conf).
Thiết lập firewall với ufw để mở port 80, 443.
Sử dụng curl và ping để kiểm tra kết nối mạng.
Dự án nhỏ: Triển khai website tĩnh (HTML/CSS) trên Nginx, cấu hình domain giả lập (chỉnh file /etc/hosts).
Tài liệu:
Nginx Beginner’s Guide
Network Basics for DevOps
Video: “Networking for DevOps” (TechWorld with Nana).
Thời gian: 10-12 giờ.
---------------------------------------------------------------------------------------------------------------
Tuần 4: Container hóa với Docker
Mục tiêu: Hiểu và sử dụng Docker để đóng gói ứng dụng.
Lý thuyết:
Docker là gì? Container vs Virtual Machine.
Dockerfile, image, container, Docker Hub.
Docker Compose để quản lý nhiều container.
Thực hành:
Cài Docker trên Ubuntu.
Tạo Dockerfile cho ứng dụng Node.js hoặc PHP (Laravel).
Chạy container: docker build, docker run, docker ps, docker stop.
Sử dụng Docker Compose để chạy ứng dụng đa container (web + DB).
Dự án nhỏ: Container hóa ứng dụng Laravel (web + MySQL) với Docker Compose, truy cập qua localhost.
Tài liệu:
Docker Documentation
Docker for Beginners
Video: “Docker Tutorial for Beginners” (TechWorld with Nana).
Thời gian: 12-15 giờ.
---------------------------------------------------------------------------------------------------------------
Tuần 5: CI/CD cơ bản với GitHub Actions
Mục tiêu: Thiết lập pipeline CI/CD đơn giản.
Lý thuyết:
CI/CD là gì? Continuous Integration, Delivery, Deployment.
Pipeline: Build, test, deploy.
GitHub Actions: Workflow, jobs, steps.
Thực hành:
Tạo workflow YAML trong .github/workflows/ci.yml.
Thiết lập pipeline để:
Build ứng dụng (ví dụ: npm install, composer install).
Chạy unit test (PHPUnit cho Laravel).
Triển khai đến server (ví dụ: SSH vào VPS).
Tích hợp linter (ESLint, PHP_CodeSniffer).
Dự án nhỏ: Tạo pipeline GitHub Actions để build và test ứng dụng Laravel, đẩy image Docker lên Docker Hub.
Tài liệu:
GitHub Actions Documentation
CI/CD with GitHub Actions (TechWorld with Nana).
Thời gian: 10-12 giờ.
---------------------------------------------------------------------------------------------------------------
Tuần 6: Infrastructure as Code với Terraform
Mục tiêu: Quản lý hạ tầng với Terraform.
Lý thuyết:
IaC là gì? Lợi ích so với cấu hình thủ công.
Terraform: Provider, resource, state, module.
Cloud providers: AWS, Azure, GCP.
Thực hành:
Cài Terraform và cấu hình AWS CLI.
Viết file Terraform để tạo EC2 instance và S3 bucket.
Sử dụng lệnh: terraform init, terraform plan, terraform apply, terraform destroy.
Tìm hiểu Terraform state (terraform.tfstate).
Dự án nhỏ: Tạo hạ tầng AWS với Terraform (1 EC2, 1 S3 bucket), triển khai ứng dụng tĩnh lên EC2.
Tài liệu:
Terraform Documentation
Terraform on AWS
Video: “Terraform in 100 Seconds” (Fireship).
Thời gian: 12-15 giờ.
---------------------------------------------------------------------------------------------------------------
Tuần 7: Kubernetes cơ bản
Mục tiêu: Hiểu và triển khai ứng dụng trên Kubernetes.
Lý thuyết:
Kubernetes là gì? Pod, Deployment, Service, Ingress.
Minikube để chạy Kubernetes local.
Cluster, node, kubeconfig.
Thực hành:
Cài Minikube và kubectl.
Tạo Deployment và Service để chạy ứng dụng Docker.
Sử dụng kubectl apply, kubectl get, kubectl describe.
Cấu hình Ingress để truy cập ứng dụng qua domain giả lập.
Dự án nhỏ: Triển khai ứng dụng Laravel trên Minikube, truy cập qua localhost.
Tài liệu:
Kubernetes Documentation
Kubernetes for Beginners (TechWorld with Nana).
Thời gian: 12-15 giờ.
---------------------------------------------------------------------------------------------------------------
Tuần 8: Monitoring và Logging
Mục tiêu: Theo dõi hệ thống với Prometheus và Grafana.
Lý thuyết:
Monitoring vs Observability.
Metrics (CPU, memory), logs, traces.
Prometheus (metrics), Grafana (visualization), ELK Stack (logging).
Thực hành:
Cài Prometheus và Grafana local (dùng Docker).
Cấu hình Prometheus để thu thập metrics từ ứng dụng Node.js.
Tạo dashboard Grafana để hiển thị CPU/memory usage.
Cài ELK Stack (hoặc Loki) để xem log từ container.
Dự án nhỏ: Thiết lập monitoring cho ứng dụng Laravel, thêm alert khi CPU vượt 80%.
Tài liệu:
Prometheus Documentation
Grafana Tutorials
Video: “Prometheus & Grafana” (TechWorld with Nana).
Thời gian: 10-12 giờ.
---------------------------------------------------------------------------------------------------------------
Tuần 9: CI/CD nâng cao với Jenkins hoặc GitLab CI
Mục tiêu: Thiết lập pipeline phức tạp hơn.
Lý thuyết:
Jenkins: Master-agent, plugins, pipeline as code.
GitLab CI: .gitlab-ci.yml, runners.
Blue-green deployment, canary deployment.
Thực hành:
Cài Jenkins trên local hoặc VPS.
Tạo pipeline Jenkins để build, test, deploy ứng dụng lên AWS EC2.
Tích hợp Docker và Kubernetes vào pipeline.
Dự án nhỏ: Tạo pipeline Jenkins để triển khai ứng dụng Laravel lên Kubernetes với chiến lược blue-green.
Tài liệu:
Jenkins Documentation
GitLab CI/CD
Video: “Jenkins Pipeline Tutorial” (TechWorld with Nana).
Thời gian: 12-15 giờ.
---------------------------------------------------------------------------------------------------------------
Tuần 10: Cloud cơ bản (AWS)
Mục tiêu: Làm quen với cloud và triển khai ứng dụng.
Lý thuyết:
AWS services: EC2, S3, RDS, ECS/EKS, CloudWatch.
IAM roles, security groups.
Autoscaling và load balancing.
Thực hành:
Cài AWS CLI, cấu hình credentials.
Triển khai ứng dụng Laravel lên ECS hoặc EKS.
Cấu hình CloudWatch để theo dõi log và metrics.
Dự án nhỏ: Triển khai ứng dụng Laravel lên ECS, sử dụng S3 để lưu trữ file upload.
Tài liệu:
AWS Documentation
AWS Free Tier
Video: “AWS for DevOps” (TechWorld with Nana).
Thời gian: 12-15 giờ.
---------------------------------------------------------------------------------------------------------------
Tuần 11: Bảo mật trong DevOps
Mục tiêu: Tích hợp bảo mật vào quy trình DevOps.
Lý thuyết:
DevSecOps: Bảo mật trong CI/CD.
Quét lỗ hổng container (Trivy, Clair).
Quản lý secrets (AWS Secrets Manager, HashiCorp Vault).
Thực hành:
Cài Trivy để quét Docker image.
Sử dụng AWS Secrets Manager để lưu API keys.
Cấu hình HTTPS cho Nginx với Let’s Encrypt.
Dự án nhỏ: Tích hợp Trivy vào pipeline CI/CD, đảm bảo image không có lỗ hổng trước khi deploy.
Tài liệu:
Trivy Documentation
AWS Secrets Manager
Video: “DevSecOps Tutorial” (TechWorld with Nana).
Thời gian: 10-12 giờ.
---------------------------------------------------------------------------------------------------------------
Tuần 12: Dự án tổng hợp và ôn tập
Mục tiêu: Kết hợp tất cả kiến thức vào một dự án thực tế.
Dự án tổng hợp:
Xây dựng ứng dụng Laravel (hoặc Node.js) với các thành phần:
Container hóa với Docker.
Triển khai pipeline CI/CD với GitHub Actions hoặc Jenkins.
Deploy lên Kubernetes (Minikube hoặc AWS EKS).
Cấu hình Terraform để tạo hạ tầng AWS (EC2, RDS).
Monitoring với Prometheus/Grafana.
Quét bảo mật với Trivy.
Viết tài liệu mô tả pipeline và cách triển khai.
Ôn tập:
Review các khái niệm: CI/CD, IaC, container, cloud.
Chuẩn bị trả lời phỏng vấn (xem câu hỏi phỏng vấn DevOps middle ở bài trước).
Tài liệu:
DevOps Project Ideas (TechWorld with Nana).
Roadmap.sh - DevOps Projects.
Thời gian: 15-20 giờ.
---------------------------------------------------------------------------------------------------------------
Lưu ý quan trọng
Thời gian học: Dành 10-15 giờ/tuần, tùy thuộc vào lịch trình. Nếu có ít thời gian, kéo dài lộ trình thành 16 tuần.
Môi trường thực hành: Sử dụng AWS Free Tier, GCP Free Tier, hoặc Minikube để tiết kiệm chi phí.
Tài liệu bổ sung:
Khóa học: “DevOps Bootcamp” (Udemy, TechWorld with Nana).
Sách: “The DevOps Handbook” (Gene Kim).
Cộng đồng: Tham gia Reddit (r/devops), Discord DevOps.
Portfolio: Lưu các dự án nhỏ lên GitHub, viết README chi tiết để làm nổi bật kỹ năng khi phỏng vấn.
---------------------------------------------------------------------------------------------------------------
Mẹo để thành công
Thực hành là chính: Mỗi tuần, dành 60% thời gian thực hành, 40% học lý thuyết.
Debug lỗi: Khi gặp lỗi (Docker, Terraform), tra cứu trên Stack Overflow hoặc tài liệu chính thức.
Chuẩn bị phỏng vấn: Sau tuần 12, luyện tập trả lời câu hỏi phỏng vấn DevOps (xem bài trước của tôi).
Cập nhật công cụ: Theo dõi các công cụ mới (ArgoCD, Helm) qua blog DevOps hoặc YouTube.
---------------------------------------------------------------------------------------------------------------
Nếu bạn cần chi tiết hơn về một tuần cụ thể (ví dụ: viết Dockerfile, cấu hình pipeline), hoặc muốn tôi điều chỉnh lộ trình cho thời gian ngắn hơn, hãy cho tôi biết! Chúc bạn học tốt và sớm trở thành DevOps Engineer!
