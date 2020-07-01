Usage

<orxe-rating-bar> </orxe-rating-bar>

Linear Rating Bar

<orxe-rating-bar type="linear" rating="60"></orxe-rating-bar>

Donut Rating Bar

<orxe-rating-bar type="donut" rating="30"></orxe-rating-bar>

Methods

| Method Name | Return Type | Access Modifier | Description                                                                   |
| ----------- | ----------- | --------------- | ----------------------------------------------------------------------------- |
| `getRating` | `number`    | public          | This method converts the rating based on the scale of 100 to the scale of 10. |

Properties

| Property | Attribute | Description                                    | Type     | Default  |
| -------- | --------- | ---------------------------------------------- | -------- | -------- |
| `type`   | `type`    | Used to display the type of rating bar.        | `string` | `linear` |
| `rating` | `rating`  | Used to pass a value/rating to the rating bar. | `number` | `0`      |
| `label`  | `label`   | To provide a label for the linear rating bar.  | `string` |          |