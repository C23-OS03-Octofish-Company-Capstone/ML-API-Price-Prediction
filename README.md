# Fish Price Prediction

 <h1>API Docs</h1>

[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/15710919-02c12464-72c8-4a52-a955-656d1592b021?action=collection%2Ffork&collection-url=entityId%3D15710919-02c12464-72c8-4a52-a955-656d1592b021%26entityType%3Dcollection%26workspaceId%3D47d7d502-7365-4157-97be-2f07577bb417)

---

Base URL:

 <p >
  <a href="https://price-prediction-mps7ogpvxa-et.a.run.app/">fish-price-prediction</a>
</p>

### Prediksi Harga Ikan
- Endpoint
  - /predict
- Method
  - POST
- Request Body
  - jenis_ikan = string
  - kategori = string
  - jumlah_bulan = int
- Contoh Request dalam RAW
```json
{
    "jenis_ikan": "Bandeng",
    "kategori": "Eceran",
    "jumlah_bulan": 5
}
```
- Response
```json
{
    "predicted_price": [
        "31211.984634399414",
        "30814.451217651367",
        "30739.761352539062",
        "30648.113250732422",
        "30752.580642700195"
    ]
}
```
