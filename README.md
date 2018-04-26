# pluswerk/grumphp-req-package

This package is to require all needed packages to sniff the code in a project. Beside
this it contains a example grumphp.yml `doc/geumphp.example.yml` for projects.

## Usage

	composer config repositories.grumphp-req '{"type": "vcs", "url": "https://github.com/plus-muc/grumphp-req-package.git"}'
	composer require --dev pluswerk/grumphp-req-package
	./vendor/bin/grumphp git:init