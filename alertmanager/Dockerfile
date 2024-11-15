# Use the official Alertmanager image
FROM prom/alertmanager:latest

# Set the working directory to /etc/alertmanager
WORKDIR /etc/alertmanager

# Copy the local alertmanager.yml into the container
COPY alertmanager.yml /etc/alertmanager/alertmanager.yml

# Expose the default Alertmanager port
EXPOSE 9093

# Command to run the Alertmanager with the specified configuration file
CMD ["--config.file=/etc/alertmanager/alertmanager.yml"]
