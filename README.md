# AngularTourOfHeroes

This is a practice for learning Angular.   

The steps are as follow   
___
- Initial the application
  - change application title and style.
- The Hero Editor
  - create a hero component.
  - use the cli comment to create HeroesComponent
    ```sh
    ng g c heroes
    ```
    or   
    ```sh
    ng generate component heroes
    ```
  - display the HeroesComponent
  - create hero class and show the object
  - applied the uppercasePipe to format hero name
  - let hero name editable
    - two-way data binding (ngModel)
- create mock heroes, style and display heroes
  - show detail when click one of the hero list
- create hero-detail component
  - pass the hero property from heros to hero-detail
    import step: add @Input() hero property to hero-detail
  - show detail when click one of the master hero list
