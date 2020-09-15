# Data Indonesia

Berisikan Data informasi Provinsi, Kabupaten atau Kota, dan Juga Kecamatan dari seluruh Indonesia.

Data diambil dari rajaongkir.com
1. Provinsi
2. Kabupaten/Kota
3. Kecamatan
4. Desa (Soon)


## Format Data
## Provinsi 
File [province.json](json/provinces.json)
```
[
    {
        "id": 1,
        "name": "Bali"
    },
    ....
]
```

## Kabupaten atau Kota
File [cities.json](json/cities.json)
```
[
    {
        "id": 1,
        "province_id": 21,
        "province_name": "Nanggroe Aceh Darussalam (NAD)",
        "type": "Kabupaten",
        "city_name": "Aceh Barat",
        "postal_code": 23681
    },
  ......
]
```

## Kecamatan
File [kecamatan.json](json/kecamatan.json)

```
[
    {
        "id": 1,
        "province_id": 21,
        "city_id": 1,
        "province_name": "Nanggroe Aceh Darussalam (NAD)",
        "city_name": "Aceh Barat",
        "type": "Kabupaten",
        "subdistrict_name": "Arongan Lambalek"
    },
  .....
]
```
