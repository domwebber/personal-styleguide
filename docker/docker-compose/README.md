# Docker Compose

```yaml
# File Signature System/Project Name.
# link-to-project.example.com
# (c) YYYY Owner

# Reused configuration
x-config:
    # Example database global configuration
    database:
        user: &database-user "systemuser"
        password: &database-password "${DATABASE_PASSWORD?err}"

services:
    # Example Container Configuration
    containername:
        # Build & Metadata
        labels:
        image:
        container_name:
        build:
            # Context & Metadata
            labels:
            context:
            dockerfile:

            # Selection & Targeting
            target:

            # Config
            cache_from:
            args:

            # Interconnection
            network:

        # Startup Order & Selection
        profiles:
        platform:
        depends_on:
        restart:
        healthcheck:

        # Runtime Configuration & Permissions
        privileged:
        read_only:
        env_file:
        environment:
        secrets:
        volumes:
        volumes_from:

        # Interconnection & Exposure
        expose:
        ports:
        links: # Prefer networks
        networks:

        # Startup & Run
        deploy:
        working_dir:
        entrypoint:
        command:
        logging:

configs:

secrets:

volumes:

networks:
```
