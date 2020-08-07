# eventstore-docker-local-cert
Custom Docker image with a Self signed certificate and configuration

Since there are breaking changes in the way EventStore 20.6 is working, I had to create docker containers with custom EventStore configuration and a self sined certificate.
This configuration will preserve data and work in production mode.
