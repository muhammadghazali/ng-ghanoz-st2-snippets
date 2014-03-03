ng-ghanoz-st2-snippets
======================

My own collection of AngularJS snippets. The abbreviation of snippets is
prefixed with my namespace, `gnz-snippet-abbreviation`.

## Notice

I only use this snippets on Sublime Text 2.

## How to install

```
# Locate your `sublime-text-2/Packages/User` directory
# In my Linux box

$ cd ~/.config/sublime-text-2/Packages/User

Clone this repository

# git clone https://github.com/muhammadghazali/ng-ghanoz-st2-snippets.git
```

## Test snippets

### Service Unit Test Suites

Tab trigger:

```
gnz-test-service
```

Snippets:

```
'use strict';

describe('Service: ServiceName', function() {

  var ServiceName;

  // load the service's module
  beforeEach(module('ModuleName'));

  beforeEach(inject(function($injector) {
    ServiceName = $injector.get('ServiceName');
  }));

  it('should load the module', function() {
    expect(ServiceName).toBeDefined();
  });
});
```