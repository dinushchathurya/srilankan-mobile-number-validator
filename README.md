<p align="center">
    <img src="https://img.shields.io/badge/version-1.0.0-blue">
    <img alt="Scrutinizer build (GitHub/Bitbucket)" src="https://img.shields.io/scrutinizer/build/g/dinushchathurya/srilankan-mobile-number-validator/main">
    <img alt="Scrutinizer code quality (GitHub/Bitbucket)" src="https://scrutinizer-ci.com/g/dinushchathurya/srilankan-mobile-number-validator/badges/quality-score.png?b=main">
    <img src="https://img.shields.io/badge/dependencies-up%20to%20date-orange">
    <img src="https://img.shields.io/badge/coverage-100%25-yellowgreen">
    <img src="https://img.shields.io/badge/rating-★★★★★-brightgreen">
    <img src="https://img.shields.io/badge/uptime-100%25-brightgreen">
</p>

<h1 align="center">Laravel Srilankan Telephone Number Validator</h1>
  <p align="center">
    This package is a Laravel package that validates all Sri Lankan telephone numbers including mobile & landline numbers.
  </p><br><br>
</div>

## Table of Contents
<ol>
    <li><a href="#installation">Installation</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#translations">Translations</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#author">Author</a></li>
    <li><a href="#credits">Credit</a></li>
    <li><a href="#license">License</a></li>
</ol>

## Installation

via composer

`composer require dinushchathurya/srilankan-mobile-number-validator`

## Usage 

Add the ```srilankan-mobilecode``` rule to the field you want to validate.

```sh
'mobile' => 'required|srilankan-mobilecode'
```

## Translations
Publish the translations with the following command.
```bash
php artisan vendor:publish --provider="Dinushchathurya\SrilankanMobilecodeValidator\MobilecodeValidatorServiceProvider" --tag="translations"
```
You can now update the validation message in the ```resources/lang/vendor/mobile-validator``` folder.


## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Author 

Author [Dinush Chathurya](https://dinushchathurya.github.io/)

## Author 

Regex Credit [Ayesh Karunaratne](https://github.com/Ayesh)

## License

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Copyright (c) 2022 <a href="https://dinushchathurya.github.io/">Dinush Chathurya</a> and <a href="https://codingtricks.io/">codingtricks.io</a>
