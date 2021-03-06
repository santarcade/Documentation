---
ID_PAGE: 25151
PG_TITLE: Action
PG_VERSION: 2.1
TAGS:
    - Action
---
## Description

class [Action](/classes/3.0/Action)



## Constructor

## new [Action](/classes/3.0/Action)(triggerOptions, condition)

Actions are a simple way to add interactions in your scenes. An action is launched when its trigger is fired.
See more here

#### Parameters
 | Name | Type | Description
---|---|---|---
 | triggerOptions | any |      Options of the trigger
optional | condition | [Condition](/classes/3.0/Condition) |      [Condition](/classes/3.0/Condition) to trigger the action
## Members

### triggerOptions : any

The trigger options

### trigger : number

Number of the trigger

## Methods

### getTriggerParameter() &rarr; any

Get the trigger parameter
### execute(evt) &rarr; void

Execute the trigger

#### Parameters
 | Name | Type | Description
---|---|---|---
 | evt | [ActionEvent](/classes/3.0/ActionEvent) |      An event to trigger

### skipToNextActiveAction() &rarr; void


### then(action) &rarr; [Action](/classes/3.0/Action)



#### Parameters
 | Name | Type | Description
---|---|---|---
 | action | [Action](/classes/3.0/Action) |      The action to do

### serialize(parent) &rarr; any



#### Parameters
 | Name | Type | Description
---|---|---|---
 | parent | any |   

