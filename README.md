# MicroFront

## Instalar servidor cross
```
npm i -g http-server --save
```

## Instalar las siguientes dependencias en cada proyecto
```
ng add @angular/elements

ng add ngx-build-plus
```

## En cada proyecto suplantar en angular.json
`"builder": "ngx-build-plus:browser"` por `"builder": "ngx-build-plus:build"`

## Compilar cada proyecto por separado
```
ng build --prod --output-hashing none --single-bundle true
```

## Ejecutar servicios foo y bar
```
http-server ./dist/foo -p 8081

http-server ./dist/bar -p 8082
```

## ejecutar proyecto foo-bar
```
ng serve -o
```