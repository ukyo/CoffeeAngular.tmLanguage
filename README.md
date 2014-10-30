# CoffeeAngular.tmLanguage

CoffeeAngular.tmLanguage is forked from Default CoffeeScript.tmLanguage.

## Features

You can highlight inline templates if you write code as below.

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
