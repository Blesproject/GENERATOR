# MODULS

## Endpoint example
```
endpoint:
  point_test:
    auth: False
    insert:
      fields:
        nm_pointest:
          name: name search for domain
          desc: Domain Variabel To Search
          type: fields
        value_pointest:
          name: name search for domain
          desc: Domain Variabel To Search
          type: fields
      others:
        method:
          name: name search for domain
          desc: Domain Variabel To Search
      moduls:
        test:
          action: insert
          parameters:
            table : point_test
            fields: $fields
    remove:
      fields:
        id_pointest:
          name: ID search
          desc: Domain Variabel To Search
          type: tags
      others:
        method:
          name: methode name
          desc: Domain Variabel To Search
      moduls:
        test:
          action: remove
          parameters:
            table : point_test
            fields: $fields

    get:
      fields:
        id_pointest:
          name: ID search
          desc: Domain Variabel To Search
          type: tags
          default:
      others:
        method:
          name: methode name
          desc: Domain Variabel To Search
      moduls:
        test:
          action: get
          parameters:
            table : point_test

    where:
      fields:
        id_pointest:
          name: ID search
          desc: Domain Variabel To Search
          type: tags
          default:
      others:
        method:
          name: methode name
          desc: Domain Variabel To Search
      moduls:
        test:
          action: where
          parameters:
            table : point_test
            fields: $fields
```