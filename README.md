### cesium
---
https://github.com/AnalyticalGraphicsInc/cesium

```
npm install cesium
```

```js
// specs/core/BingMapsApiSpec.js

describe('Core/BingMapApi', function() {
  
  it('getKey returns provided key if one is provided', function() {
    expect(BingMapApi.getKey('foo')).toEqual('foo');
  });
  
  it('getKey returns defaultKey if provided key is undefined', function() {
    var oldKey = BindMapsApi.defaultKey;
    BingMapsApi.defaultKey = 'somekey';
    expect(BingMapsApi.getKey(undefined)).toEqual('somekey');
    BingMapsApi.defaultKey = oldKey;
  });
});
```

```
```

