# Context

> 管理一次请求生命周期中的数据 [![Build Status](https://travis-ci.org/LingxiTeam/laravel-context.svg?branch=master)](https://travis-ci.org/LingxiTeam/laravel-context.svg?branch=master)[![StyleCI](https://styleci.io/repos/72192760/shield)](https://styleci.io/repos/72192760)[![Latest Stable Version](https://poser.pugx.org/lingxi/context/v/stable)](https://packagist.org/packages/lingxi/context)[![Total Downloads](https://poser.pugx.org/lingxi/context/downloads)](https://packagist.org/packages/lingxi/context)[![License](https://poser.pugx.org/lingxi/context/license)](https://packagist.org/packages/lingxi/context)

### Install

```bash
composer require kenuocn/context

Kenuocn\Context\ContextServiceProvider::class,

'Context' => Kenuocn\Context\ContextFacade::class,
```

### Usage

```
<?php

Context::set('user', User::find(request('user_id')));

Context::get('user');

Context::all();
```
