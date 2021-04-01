# The Four Elements of Simple Design

## Long-term erosion of our capacity to deliver features

## Elements

### Passes its tests
#### Nothing else matters if the system behaves incorrectly
#### If not interested, throw it away
#### In the green bar we have confidence in changing the system

### Minimizes duplication
#### Duplicate code in order to make a new test pass,
##### then immediately remove most of that duplication

### Maximizes clarity
#### Extract common code in `foo()` in order to remove duplication
##### Find suitable name
##### Move in the correct place

### Has fewer elements
#### Creating little things with new `foo()` code
##### Looking for cohesive bundles
##### Remove when become obsolete

## Order
### Matter
### Removing duplication and improving clarity in small cycles creates a dynamo that drives simple design
### Passes its tests is routine

## Clarity Is Unclear
### Duplication is objective
### Clarity is subjective
### Focus on removing duplication over improving clarity
### Improving names to improving clarity