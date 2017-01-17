# angular-polymer

Experimental Polymer support for Angular v2.2+. Replaces default `DomRenderer` with Polymer-enabled implementation.

### Warning: proof-of-concept stage, do not use this in production

---

## Usage

In your Angular project, that uses Polymer elements:

1. Install the package with NPM:

        $ npm install angular-polymer --save

2. In `app.module.ts`, import `PolymerModule` and add to `AppModule` imports:

    ```typescript

    import {PolymerModule} from 'angular-polymer';

    @NgModule({
      imports: [
        //...,
        PolymerModule
      ]
    })
    export class AppModule {}
    ```

## Limitations and TODOs

- ViewEncapsulation modes are supported
- Component styles are not supported
- Depends on @angular/core APIs
- No tests yet

## License

Copyright 2017 Anton Platonov <platosha@gmail.com>

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
