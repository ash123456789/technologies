# Laravel Standards

Laravel is the core PHP framework we use to develop our web applications, as with everything there are a set of best 
practices to ensure we end up with a reliable bit of software that will stand up to the test of time.

_Note: This is still a work in progress_

## Resources
- [Laravel documentation](https://laravel.com/docs)

## Structure

#### Models
Models should be placed into their own folder and namespace. This is to ensure that the Project explorer window doesn't
become clogged over time on projects.

```php
//This
App\User::class

//Becomes this
App\Models\User::class
```