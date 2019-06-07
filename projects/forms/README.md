# @ng-bucket/forms
This package tends to help when working with Reactive Forms.

I hope one day I will be able to deprecated this libraries in favor to native solutions :wink: until then

![Hello](https://render.bitstrips.com/v2/cpanel/fb695398-7ef1-4461-987b-73d3a97805fd-bdc2f301-a578-49ad-a6e1-f1fe69b63df9-v1.png?transparent=1&palette=1)

### Installation
`npm i @ng-bucket/forms`

Peer dependencies:
 * `@angular/forms` >= 6
 * `rxjs` >= 6

### Documentation:
1. [Form observer](./docs/form-observer.md) - allows to observe all form state changes, including `pristine` / `dirty` and `touched` / `untouched`, which current native API dose not support.
2. [Form types](./docs/typed-form.md) - adds type safety to Reactive Forms
3. [Form utility methods](./docs/utility.md)
    * [dirtyValues](./docs/utility.md#dirtyValues)
    * [enableAll](./docs/utility.md#enableAll)
    * [keyOf](./docs/utility.md#keyOf)
