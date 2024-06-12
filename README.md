# Hands-On Blockchain for Python Developers

<a href="https://www.packtpub.com/product/hands-on-blockchain-for-python-developers/9781788627856"><img src="https://content.packt.com/_/image/original/B09346/cover_image_large.jpg" alt="no-image" height="256px" align="right"></a>

This is the code repository for [Hands-On Blockchain for Python Developers](https://www.packtpub.com/product/hands-on-blockchain-for-python-developers/9781788627856), published by Packt.

**Empowering Python developers in the world of blockchain and smart contracts**

## What is this book about?
This book will help Python developers enhance their productivity in writing DeFi and NFT applications. You’ll gain in-depth knowledge of related technologies such as Layer 2 and IPFS, further expanding your understanding of the blockchain ecosystem.	

This book covers the following exciting features:
* Understand blockchain and smart contracts
* Learn how to write smart contracts with Vyper
* Learn how to use the web3.py library and Ape Framework
* Discover related technologies like Layer 2 and IPFS
* Acquire step-by-step guide to writing an Automatic Market Maker Decentralized Exchange smart contract
* Build innovative, interactive, and token-gated web3 NFTs applications

If you feel this book is for you, get your [copy](https://www.amazon.com/Hands-Blockchain-Python-Developers-decentralized/dp/1788627857/ref=tmm_pap_swatch_0?_encoding=UTF8&dib_tag=se&dib=eyJ2IjoiMSJ9.5yGHuu2XILvZkjvi43jUXS_wTDXnXVqrGF2Gbcj_r6rGjHj071QN20LucGBJIEps.gTuxBJlfeGiFT7ulb69lgTXoCYlJh3QsUId6jE9IMfQ&qid=1718197586&sr=8-1) today!


## Instructions and Navigations
All of the code is organized into folders. For example, Chapter02.

The code will look like the following:
```
from ape import accounts, project
import os

def main():
  password = os.environ["MY_PASSWORD"]
  dev = accounts.load("dev")
  dev.set_autosign(True, passphrase=password)
  contract = project.SimpleStorage.deploy(sender=dev)
  num_value = contract.retrieve.call()
  print(f"The num value is {num_value}")

```

**Following is what you need for this book:**
This blockchain book is for developers interested in understanding blockchain and smart contracts. It is suitable for both technology enthusiasts looking to explore blockchain technology and programmers who aspire to become smart contract engineers. Basic knowledge of GNU/Linux and Python programming is mandatory to get started with this book.	

With the following software and hardware list you can run all code files present in the book (Chapter 1-17).
### Software and Hardware List
| Chapter | Software required | OS required |
| -------- | ------------------------------------ | ----------------------------------- |
| 1-17 | Python (3.10+) | Windows, macOS, Linux |
| 1-17 | Vyper (0.3.10) | Windows, macOS, Linux |
| 1-17 | Ape Framework (0.7.23) | Windows, macOS, Linux |


### Related products
* Solidity Programming Essentials [[Packt]](https://www.packtpub.com/product/solidity-programming-essentials-second-edition/9781803231181) [[Amazon]](https://www.amazon.com/Solidity-Programming-Essentials-building-contracts/dp/1803231181/ref=sr_1_1?dib=eyJ2IjoiMSJ9.OBO2_BPHZ0fx0FDTZ7JgOh6OoI_hxyywMGqkECxlUIHdYDujxzpd1Ca8JUG3_Vj2YXr9l7Mryj0730NKVcab4C1F1dA61E11bceVe7RjYjbtpT7N1CyhT0WmF0KG5Hs08hS-iEumopfkpLZDAAIEQO9xhZiCgKProWLEmgJImTvSRVncNU-PGnEnrx1Sx4oF-I7QDplK9rDWAWxq_Vc7HbAr5U1kMc6p9LTlC2FSt9M.lHC1XH1aeTrVkCDrKE2_R2RBor0wk3KRoRfib7LHnQI&dib_tag=se&keywords=Solidity+Programming+Essentials&qid=1718198207&sr=8-1)

* Applied Computational Thinking with Python [[Packt]](https://www.packtpub.com/product/applied-computational-thinking-with-python-second-edition/9781837632305) [[Amazon]](https://www.amazon.com/Applied-Computational-Thinking-Python-real-world/dp/1837632308/ref=sr_1_1?crid=F5T0RPX6O2AI&dib=eyJ2IjoiMSJ9.CwCuQF8WXs6bOopFImpN4v1OdvHft9IkQ6ecs8WOBuF1G31FoyPOt0MiCIdYZv-pghH39hWF6Ty5AJ3052wGVBofscs8aJJyn5TWCafla5z5ZsBcbs5CPyl7TsXD5F21eamgaslrxlDHC5g9g3DLYz_cZQFSnnLXCqJaB1QseuE4aLkxzhAnS0dJEJuhYLRJ_HKORSQ1do28eVM0W00ISJmfIbSapMobuIQ5uj75yOQ.6YIa_-dJTCMChZ-DCn5M2MYMOA6aLf0GnOazj6UaFSc&dib_tag=se&keywords=Applied+Computational+Thinking+with+Python&qid=1718198257&sprefix=solidity+programming+essentials%2Caps%2C349&sr=8-1)

## Get to Know the Author
**Arjuna Sky Kok** 
is a skilled quantitative software engineer with a passion for all things related to finance and technology. Arjuna lives in Jakarta, where he studied mathematics and programming at a university. Arjuna's academic achievements include double degrees in Computer Science and Mathematics. Right now, he's focusing his talent in the crypto space. Arjuna believes that DeFi and NFTs will serve as the foundation for future finance, and he also has a keen interest in AI, especially Large Language Models (LLM). Outside his job, Arjuna enjoys watching anime and climbing mountains.


