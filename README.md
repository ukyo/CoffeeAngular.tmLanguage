# CoffeeAngular.tmLanguage

CoffeeAngular.tmLanguage is forked from Default CoffeeScript.tmLanguage.

## Features

You can highlight inline templates if you write codes as below.

```coffee
template = """
	<div ng-click="bar()">foo</div>
"""

fooTemplate = '''
	<div ng-click="bar()">foo</div>
'''

app.directive 'fooDirective', ->
  template: """
  	<div></div>
  """
```

![image](https://raw.githubusercontent.com/ukyo/CoffeeAngular.tmLanguage/master/coffeeangular.png)
