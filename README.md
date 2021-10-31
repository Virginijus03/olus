# Olus

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 12.2.10.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
 

 //uzduotis

 Angular projektas - Alaus megėjų platforma
Sukurkite platformą alaus megėjams, jūsų Angular projekte privalo būti bent 2 skirtingi routes, 3 skirtingi komponentai ir bent vienas service.
Jūsų platforma privalo turėti alaus modelį (klasę arba interface) su tokiais parametrais:

id: number - unikalus alaus rūšies id
name: string - alaus rūšies pavadinimas
description: string - alaus rūšies aprašymas
image_url: string - alaus paveikslėlis
food_pairing: string[] - string masyvas, kuriame saugoma informacija, su kokiu maistu reikėtų derinti šią alau rūšį
abv: number - alchoholio kiekio aluje rodiklis (stiprumas)
ph: number - alaus pH lygis (rūgštingumas/šarmingumas)
Platformos funkcionalumą sugalvokite patys, svarbu įgyvendinti aukščiau pateiktus kriterijus. Idėjos:

Alaus rušių atvaizdavimas ir rikiavimas
Alaus rušių filtravimas pagal kriterijus
Mėgstamiausiu alaus rušių pridėjimas
Alaus rušių rinkinių sudarymas