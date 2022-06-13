# 🚀 SYMFONY COMMANS

# Set Up Your Development Environment

INSTALL SYMFONY WITH COMPOSER:

# Skeleton app
```bash
 composer create-project symfony/skeleton my_project_name
```

# To WEB application
```bash
cd my_project_directory
composer require webapp
```

# Config apache pack
```bash
 composer require symfony/apache-pack
```

# List intalled recipes
```bash
 composer recipes
```

# Show detail intalled recipe
```bash
 composer recipes symfony/apache-pack
```

# Install debug recipes
```bash
 composer require debug
```

# Add support to twig templates
```bash
composer require templates
```

# Add support to assets
```bash
composer require symfony/asset
```

# Add support to encore
```bash
composer require encore
```

# Add pack turbo 
```bash
composer require symfony/ux-turbo
```

# Add pack UX chart - ux-chartjs 
```bash
composer require symfony/ux-chartjs
```

# Create database
```bash
php bin/console doctrine:database:create
```

# Update schema database
```bash
php bin/console doctrine:schema:update --force
```

# Load database fixtures
```bash
php bin/console doctrine:fixtures:load
```

# Browser to funcional test
```bash
composer require --dev browser-kit
```

# Make tool
```bash
composer require --dev maker
```

# Monolog log bundle 
```bash
composer require monolog
```

# Orm pack
```bash
composer require doctrine
```

# Testing pack
```bash
composer require phpunit
```

# Api platform
```bash
composer require api
```


The Security component is divided into several smaller sub-components which can be used separately:


symfony/security-core
It provides all the common security features, from authentication to authorization and from encoding 
passwords to loading users.


symfony/security-http
It integrates the core sub-component with the HTTP protocol to handle HTTP requests and responses.


symfony/security-csrf
It provides protection against CSRF attacks.


symfony/security-guard
It brings many layers of authentication together, allowing the creation of complex authentication systems.
You can install each of them separately in your project:

```bash
 composer require symfony/security-core
 composer require symfony/security-http
 composer require symfony/security-csrf
 composer require symfony/security-guard
```

Generating UUIDs
```bash
composer require symfony/uid
```


Generating Entity
```bash
php bin/console make:entity
```

Generating migration
```bash
php bin/console make:migration
```

Execute migration
```bash
php bin/console doctrine:migrations:migrate
```
