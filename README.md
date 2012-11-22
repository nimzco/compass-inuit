# ![inuit.css](http://csswizardry.com/inuitcss/img/logo.jpg)

A powerful little Compass extension for inuit.css for _insanely serious_ developers who use Compass.

## Installation

### Bundler
If you want to bundle into your app, install bundler.
	
	$ sudo gem install bundler

With Bundler installed, add this to your Gemfile.

	group :assets do
		gem 'compass-inuit'
	end

Run this in the command line:

	$ bundle install
	$ git add Gemfile Gemfile.lock

### Manual
If bundler isn't your thing, install this gem.
	
	$ sudo gem install compass-inuit

Next in your Compass project add this to your config.rb

	require 'compass-inuit'

## Documentation

To get started install into your project.

	compass install compass-inuit

Then verify it's installed.

	compass help compass-inuit

Imports have been branched out in this extension, additionally you can use these:

	@import "inuit/generic";

	@import "inuit/base";

	@import "inuit/objects";

## Support inuit.css

If you use and/or like inuit.css, perhaps you might consider [supporting it
through Gumroad](http://gum.co/nOoht).

## Credits
Based on **[Harry Roberts's](http://github.com/csswizardry)** inuit.css framework.

This extension was created by **[Stephen Way](http://github.com/stephenway)**

**inuit.css is the most powerful little framework out there, and it’s ready to
go!**