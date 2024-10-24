# KoiLoader-Config-Extractor
Extract KoiLoader C2/payload

## Running the Extractor
> python3 decode_koiloader.py -f /path/to/unpacked_encoded_koiloader.bin -o /path/to/koiloader_decoded.bin

## Example output
```javascript
{
  "C2": [
    "http://91.202.233.209/hypermetropia.php",
    "https://admiralpub.ca/wp-content/uploads/2017"
  ]
}```
