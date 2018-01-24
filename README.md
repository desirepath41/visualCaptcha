# visualCaptcha

**Please note visualCaptcha is no longer actively developed. It still works and should continue to, but it won't be improved by the initial team anymore. Any PRs will be reviewed and accepted if beneficial, though. Also any help necessary for existing versions setup will _likely_ be provided by [Bruno Bernardino](https://brunobernardino.com)**

visualCaptcha is a configurable captcha solution, focusing on accessibility & simplicity, whilst maintaining security. It's also localizable and free, open-source, and we encourage customizations per site.

It also supports mobile, retina devices, and has an innovative accessibility solution.

It's licensed under MIT, but you can reach us if you want other licenses.

visualCaptcha supports many back-end and front-end languages/frameworks/libraries, which you can look into in more depth below:

## Official demos and packages (built by [Bruno Bernardino](https://brunobernardino.com) & [Clevertech](http://www.clevertech.biz))

Please note each have their own version numbers.

We're calling this new version of visualCaptcha "5.0", even though some of these packages and versions start at 1. It's just internal nomenclature (there were previous visualCaptcha versions that weren't open sourced or even built like this).

### Full-stack demos / implementations

These are samples/demos of how you can integrate visualCaptcha with multiple combinations of the front-end/back-end packages.

| Languages | Build Status |
|-----------|--------------|
|[PHP & jQuery](https://github.com/emotionLoop/visualCaptcha-PHP)|[![Build Status](https://travis-ci.org/emotionLoop/visualCaptcha-PHP.svg?flat=true&branch=master)](https://travis-ci.org/emotionLoop/visualCaptcha-PHP)|
|[Node.js & Vanilla JS](https://github.com/emotionLoop/visualCaptcha-node)|[![Build Status](https://travis-ci.org/emotionLoop/visualCaptcha-node.svg?flat=true&branch=master)](https://travis-ci.org/emotionLoop/visualCaptcha-node)|
|[Ruby & Angular.js](https://github.com/emotionLoop/visualCaptcha-ruby)|[![Build Status](https://travis-ci.org/emotionLoop/visualCaptcha-ruby.svg?flat=true&branch=master)](https://travis-ci.org/emotionLoop/visualCaptcha-ruby)|
|[PHP & jQuery Multiple Captchas](https://github.com/emotionLoop/visualCaptcha-multiple)|[![Build Status](https://travis-ci.org/emotionLoop/visualCaptcha-multiple.svg?flat=true&branch=master)](https://travis-ci.org/emotionLoop/visualCaptcha-multiple)|
|[Django & Vanilla JS](https://github.com/emotionLoop/visualCaptcha-django)|[![Build Status](https://travis-ci.org/emotionLoop/visualCaptcha-django.svg?flat=true&branch=master)](https://travis-ci.org/emotionLoop/visualCaptcha-django)|
  
There's also a [Meteor](https://github.com/emotionLoop/visualCaptcha-meteor) integration, but it's deprecated and outdated, no longer maintained officially.

### Back-end packages

These are the stand-alone back-end packages, available in different package managers, for the different back-end languages. These will usually not need to be changed/customized by you, but you'll need them to implement visualCaptcha.

| Language | Manager | Build Status |
|----------|---------|--------------|
|PHP|[Composer/Packagist](https://github.com/emotionLoop/visualCaptcha-packagist)|[![Build Status](https://travis-ci.org/emotionLoop/visualCaptcha-packagist.svg?flat=true&branch=master)](https://travis-ci.org/emotionLoop/visualCaptcha-packagist)|
|JavaScript/Node.js|[NPM](https://github.com/emotionLoop/visualCaptcha-npm)|[![Build Status](https://travis-ci.org/emotionLoop/visualCaptcha-npm.svg?flat=true&branch=master)](https://travis-ci.org/emotionLoop/visualCaptcha-npm)|
|Ruby|[RubyGem](https://github.com/emotionLoop/visualCaptcha-rubyGem)|[![Build Status](https://travis-ci.org/emotionLoop/visualCaptcha-rubyGem.svg?flat=true&branch=master)](https://travis-ci.org/emotionLoop/visualCaptcha-rubyGem)|
|Python|[Pypi/PIP](https://github.com/emotionLoop/visualCaptcha-python)|[![Build Status](https://travis-ci.org/emotionLoop/visualCaptcha-python.svg?flat=true&branch=master)](https://travis-ci.org/emotionLoop/visualCaptcha-python)|

There's also a [Meteor/Meteorite](https://github.com/emotionLoop/visualCaptcha-meteorite) back-end package, but it's deprecated and outdated, no longer maintained officially.

### Front-end packages

These are the stand-alone front-end packages, available in bower, for different libraries/frameworks. These will usually not need to be changed/customized by you, but you'll need them to implement visualCaptcha.

| Library/Framework | Codacy Analysis |
|-------------------|-----------------|
|[Vanilla JS](https://github.com/emotionLoop/visualCaptcha-frontend-vanilla)|[![Codacy](https://www.codacy.com/project/badge/88cb7475c513459296ef47f479c59dee)](https://www.codacy.com/app/bruno-bernardino/visualCaptcha-frontend-vanilla)|
|[jQuery Plugin](https://github.com/emotionLoop/visualCaptcha-frontend-jquery)|[![Codacy](https://www.codacy.com/project/badge/7ae382cdb96d4a25b6cdceb9bf85d265)](https://www.codacy.com/app/bruno-bernardino/visualCaptcha-frontend-jquery)|
|[Angular.js Directive](https://github.com/emotionLoop/visualCaptcha-frontend-angular)|[![Codacy](https://www.codacy.com/project/badge/c0511ed25fa4454fa1757ac241ddab2b)](https://www.codacy.com/app/bruno-bernardino/visualCaptcha-frontend-angular)|

These are all built by the [Front-end Core Repo](https://github.com/emotionLoop/visualCaptcha-frontend-core) repo, so if you wish to contribute to any of the front-end packages above, that is the repo to contribute to.

### Full-stack Plugins

These are plug-ins for popular CMS' that are plug-and-play.

- [WordPress plugin](https://github.com/emotionLoop/visualCaptcha-WordPress)
- [e107 Bootstrap CMS](https://e107.org/plugins/?id=853)

## Unofficial versions (created by community members)

Please note we don't maintain these and some might be outdated. **Use at your own risk.**

- [CodeIgniter Spark](https://github.com/montch/visualcaptcha-spark)
- [RubyGem](https://github.com/kimenye/visualcaptcha)
- [SailsJS](https://github.com/kavuri/sailsjs-visualcaptcha)
- [Grails/Java](https://github.com/matthew-b-payne/visualCaptcha-Grails)
- [Laravel](https://github.com/Metrakit/VisualCaptcha-Laravel)
- [ASP.NET](https://github.com/lukeautry/visualCaptcha-aspnet)
- [ASP.NET](https://github.com/terabytenz/VisualCaptcha.Net)
- [Java](https://github.com/bdotzour/visualCaptcha-java)
- [Laravel + jQuery](https://github.com/hugocabral/visualCaptcha-Laravel-jQuery)
- [CakePHP + jQuery](https://github.com/hashmode/VisualCaptcha-Cakephp-Plugin)
- [Java + Spring + AngularJS](https://github.com/tillkuhn/visualCaptcha-java-rest)
- [Meteor](https://github.com/andi-bute/captcha-meteor)
- [CakePHP + NetCommons3 + Japanese](https://github.com/NetCommons3/VisualCaptcha)
- [Java JAX-RS + JQuery](https://github.com/raphaeloneves/captcha-ws)

## Want more?

Yeah, this repo exists only to be a place to list all other repos.

If you find value in this, [please consider donating a dollar](https://thoughts.brunobernardino.com/if-i-ve-helped-you-consider-donating/).
