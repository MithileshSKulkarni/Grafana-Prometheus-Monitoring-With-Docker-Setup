This is monitoring setup with grafana-prometheus

Prerequisites: -
Before you begin, ensure your environment meets the following requirements:

Docker and Docker Compose:

Docker is required to containerize and run the services. Docker Compose simplifies managing multi-container applications.
Install Docker and Install Docker Compose on your Linux machine.
Open Ports:
The following ports should be available and not in use by other applications:

Prometheus: 9090
Grafana: 3000
Alertmanager: 9093
Loki (if used): 3100
System Resources:

A minimum of 2 CPU cores and 4 GB RAM is recommended for a smooth experience.
Ensure adequate disk space, as metrics and logs can grow quickly if not managed properly.
Network Configuration:

If running in a cloud environment or VM, ensure the above ports are accessible through your firewall or security groups.
Basic Knowledge (Optional but Recommended):

Familiarity with Docker commands and YAML configuration files will help with setup and troubleshooting.