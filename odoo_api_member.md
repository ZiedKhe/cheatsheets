#Espace Membres - API Odoo
###Mes informations personnelles
```
res.partner

* name
* street
* city
* adult_number_home
* amount_subscription
* mobile
* email
* shift_type
* cooperative_state
* ??? bootstrap_cooperative_state
* date_alert_stop
* date_delay_stop
* final_ftop_point
* final_standard_point
* image (binary)
* is_xxxxxxxxxx (vérifier leur utilisation)
```

### Infos sur les services

```
shift.shift

* name
* date_begin  /  date_begin_tz
* date_end  /  date_end_tz
* registration_ids
* seats_xxxxxxxxxx
* ?????state
```


### Personnes présentes à mon prochain Service
``` 
shift.registration 

* shift_id
* display_name
```



### Liste des prix (par famille de produits)

```

```

### Liste de mes factures
```
**pos.order**

* partner_id
* date_order
* amount_total
* lines 
```
### Mes prochains services
```
shift.registration

* partner_id
* date_begin
```
### Historique de mes services
```
shift.registration

* partner_id
* date_end

```
### Inscription en ligne pour les services volants (coopérateurs volants uniquement)

```

```

### Infos pour contacter mon coordinateur
```

```
### Informations Produits

```
product.product

* name
* barcode
* list_price
* uom_id
* categ_id
* qty_available

```
