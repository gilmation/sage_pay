# Changelog

## 0.2.13

* If the country for an address is the US, then the US state is required.
  Otherwise, it should not be supplied since it only make sense in the context
  of US states.

* Use Bundler to track development dependencies.

* Record that ActiveSupport is actually a dependency.

## 0.2.12

* Somehow didn't make it into the ChangeLog. Some bug fix or other I'd
  imagine. :)

## 0.2.11

* Cancel support for cancelling existing authorised transactions.

## 0.2.10

* Authorise support, I hope, which, again I hope, will make repeat actually work.

## 0.2.9

* Repeat transaction implementation.

## 0.2.8

* Refund implementation

## 0.2.7

* Is abort now implemented?

## 0.2.6

* Is release implemented?

## 0.2.5

* Carriage return and line feed. These will all be compressed into a 0.3
  release, but I need to keep releasing so that Heroku can pick 'em up... :-/

## 0.2.4

* Generate the appropriate response.

## 0.2.3

* yield for the signature verification details if there's a block given in the
  notification.

## 0.2.2

* Incorporate additional fields I'd missed from the notification. That'll make
  it easier to find payments from the notification.

## 0.2.1

* [FIX] SagePay think it's OK to have curly braces in a URL query string.
  Ruby's URI library thinks otherwise. No matter who's right, one of these is
  easier to change than the other.

## 0.2.0

* Initial release. This should support the full workflow for making payments,
  but the notification side hasn't been tested again SagePay in the wild so
  you mileage probably will vary.
