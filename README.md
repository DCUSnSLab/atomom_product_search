# atomom_product_search

## Overview
Depending on a person's skin disease, certain ingredients included in cosmetics may be harmful. However, if all ingredients are not labeled on the cosmetic container, it is difficult for consumers to know the ingredients.</br></br> 
We propose a system that recognizes the product name from the image taken by the user and allows the consumer to check all ingredients and the harmfulness of each ingredient only by photographing the product name on the cosmetic container.</br>

The system consists of the main component(server) and sub-component(android app).
The android app sends the specified data to the deep learning server, which stores the cosmetics product images and analyzes them. Then, it parses the processing result of the server and displays the most similar product and the ingredient analysis result for it to the user.</br>

### For instructions on how to install and use each submodule, go to check each submodule guide.

## Sub Project Lists (meaning submodules)
- [atomom_product_server](https://github.com/DCUSnSLab/atomom_product_server)
- [atomom_product_android](https://github.com/DCUSnSLab/atomom_product_android)
