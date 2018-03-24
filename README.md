# GitLab Provider

## Installation

```
composer require socialite-manager/gitlab-provider
```

## Usage

```php
use Socialite\Provider\GitLabProvider;
use Socialite\Socialite;

Socialite::driver(GitLabProvider::class, $config);
```
