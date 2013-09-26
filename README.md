# Weather Card for CiiMS

ciims-weather-card is a dashboard card for CiiMS 1.8+ that provides basic weather and geolocation information

### Installation

- Login to your CiiMS instance, and navigate to /dashboard/settings/cards
- In the "Add Card" field, type in "charlesportwoodii/ciims-weather-card"
- Wait until the card pops up in the active cards list

### Adding Card to the Dashboard

- Once you've installed the card, you can add it to the dashboard by navigating to /dashboard, and adding weather card under general

### Configuring

This card utilizes two main datasources that are external of CiiMS. Both must be initialized BEFORE the card will function

1) MaxMind GeoIP2 Javascript API Access

- Navigate to [MaxMinds Signup Page](http://www.maxmind.com/en/javascript) and click on "Sign up for Free Service"
- Enter your account details and register for an account
- Navigate to your [Javascript Domains](https://www.maxmind.com/en/javascript_domains) page.
- Add your FQDN (sub)/domain name to the list of authorized domains

2) Forecast.io API Key

- Navigate to [developer.forecast.io](https://developer.forecast.io/), and register a developer account to retrieve an API key.
- Within CiiMS, navigate to the Weather card you want to configure, click the "gear" icon, and add your API Key

3) Once __both__ apis are registered, the card will function.
### Disclaimers

This website [card] uses [GeoIP2 JavaScript from MaxMind](http://www.maxmind.com/en/javascript)


### License
The MIT License (MIT)

Copyright (c) 2013 Charles R. Portwood II

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
