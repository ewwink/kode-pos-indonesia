

# Kode Pos Indonesia
Kode Pos Indonesia dalam format Json

## kodepos.json
Berisi Kode pos kelurahan seluruh Indonesia

    {
      "46122":{
        "bps":"3278",
        "nama":"Cihideung"
      }
    }

- `46122`: Nomor Kode Pos 
- `3278` : Nomor Kode Provinsi dan  Kota/Kabupaten 
-   `Cihideung`: Nama Kecamatan

## kota-kabupaten.json
Berisi ID dan nama Kota/Kabupaten

    {
      "3278": "Kota Tasikmalaya",
    }

- `32`: Dua angka pertama merupakan Kode Provinsi dalam hal ini `Jawa Barat`
- `78`: kode kota/kab. untuk `Kota Tasikmalaya` 

## provinsi.json
Berisi ID dan nama Provinsi

    {
      "32" : "Jawa Barat",
    }
