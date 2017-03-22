# enhance
Enhancer for bootstrap and font-awesome


# For developers

## Test Environment Installation



0. Set the Angular parent project with SCSS style.

1. git submodule add on the parent project.

$ git submodule add https://github.com/thruthesky/enhance src/enhance


2. insert enhance.scss into .angular.cli.json

````
      "styles": [
        "styles.scss",
        "enhance/css/enhance.scss"
      ],
````




3. Test/Build on a sample component by adding it on NgModule.

````
    import { EnhanceSample } from '../enhance/components/sample';
    @NgModule({
    declarations: [ EnhanceSample ]
    });
````

4. And add selector in your project for a test

````
    <enhance-sample></enhance-sample>
````

5. test/edit HTML on enhance/components/sample.html


6. After work, git commit/push

