# JsonResponder Class

The `JsonResponder` class is a simple PHP class that provides a convenient way to generate JSON responses in a PHP application. It utilizes PHP 8.3 features such as constructor property promotion and JSON exception handling.

## Namespace

The class is part of the `CustomNamespace\ResponseHandler` namespace.

## Requirements

- PHP 8.3 or higher

## Installation

You can include the `JsonResponder` class in your project by using Composer (recommended) or by manually including the file.

### Composer

If you are using Composer, you can add this repository to your `composer.json` file:

```json
{
    "autoload": {
        "psr-4": {
            "CustomNamespace\\ResponseHandler\\": "src/"
        }
    }
}
