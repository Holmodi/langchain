# Spreedly

>[Spreedly](https://docs.spreedly.com/) is a service that allows you to securely store credit cards and use them to transact against any number of payment gateways and third party APIs. It does this by simultaneously providing a card tokenization/vault service as well as a gateway and receiver integration service. Payment methods tokenized by Spreedly are stored at `Spreedly`, allowing you to independently store a card and then pass that card to different end points based on your business requirements.
 
## Installation and Setup

See [setup instructions](../modules/indexes/document_loaders/examples/spreedly.ipynb).

## Document Loader

See a [usage example](../modules/indexes/document_loaders/examples/spreedly.ipynb).

```python
from langchain.document_loaders import SpreedlyLoader
```