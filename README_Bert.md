## Usage of Daisi

It is recommended to use this application on the daisi platform itself using the link https://app.daisi.io/daisies/vijay/BERT%20Keyword%20Extractor/app. However, you can still use your own editor using the below method:

### First, load the Packages:

```
import pydaisi as pyd
bert_keyword_extractor = pyd.Daisi("vijay/BERT Keyword Extractor")
```

### Now, connect to Daisi and access the functions using the following function:

```
bert_keyword_extractor.extract().value
```

## And done! We have extracted the Keyword using BERT!
