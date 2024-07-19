# Spring Boot Microservices Configuration Repository

This repository contains the configuration files for a suite of Spring Boot microservices. Each configuration is tailored for different environments such as development, testing, and production.

## Structure

- `config/` - Contains global configuration applicable to all services.
- `services/` - Contains service-specific configurations.
    - `service-name-dev.yml` - Development environment configuration for a specific service.
    - `service-name-test.yml` - Test environment configuration for a specific service.
    - `service-name-prod.yml` - Production environment configuration for a specific service.

## Usage

To use these configurations in your Spring Boot applications, set up Spring Cloud Config Server and point it to this repository. Ensure that your microservices are configured to fetch their configurations from the Config Server.

## Contributing

To contribute to this repository:
1. Fork it ( https://github.com/yourusername/spring-boot-microservices-config/fork )
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.