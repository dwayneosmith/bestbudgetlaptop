# budgetlaptops-extension

budgetlaptops-extension is a simple nodejs package & Google chrome extension which is helpful to search the best budget laptop for yourself. There is already Google chrome extension available for this package.

## Installation

```bash
npm i budgetlaptops-extension --save
```

## Usage
Add different specifications of the laptop and this tool returns the perfect budget for the machine.
- This node.js package is a small version of budget laptops Google Chrome extension. You need to give the laptop specifications manually like laptop RAM, your purpose behind using a laptop, storage and the operating system you require. This package returns the required budget for the laptop.

Get the best budget laptop:
```python
var budget = require('budgetlaptops-extension')
let a = ["Gaming", 32, 512, "Windows"]

budget.budget(a)
