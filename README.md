# Restcountry

This is a sample gem to wrap REST Countries API http://restcountries.eu

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'restcountry'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install restcountry

## Usage

```ruby
require 'restcountry'

# Find all countries
countries = Restcountry::Country.all

# Find a country by name
country = Restcountry::Country.find('italy')

# Access the country's attributes
country.capital
#=> Rome

country.region
#=> Europe

country.callingCodes
#=> "39"

```
## Attributes

name, 
capital, 
altSpellings, 
relevance, 
region, 
subregion, 
translations, 
population, 
latlng, 
demonym, 
area, 
gini, 
timezones, 
borders, 
nativeName, 
callingCodes, 
topLevelDomain, 
alpha2Code, 
alpha3Code, 
currencies, 
languages

### Credits
Many thanks to Fayder Florez(https://twitter.com/fayderflorez) for his implementation of the API.

## License
The restcountry GEM is released under the MIT License.

