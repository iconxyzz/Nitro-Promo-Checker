# Nitro Promo Checker
A Python tool to check the validity of Discord Nitro promotion codes with detailed status reporting and automatic categorization.

## Features
- Smart Categorization: Automatically sorts codes into:
  - Valid (1 month or 3 months)
  - Already redeemed
  - Invalid/expired
 
- File Management:
  - Reads codes from `input.txt`
  - Saves results to categorized files:
    - `1mvalid.txt`
    - `3mvalid.txt`
    - `redeemed.txt`
    - `invalid.txt`
   
- ## Requirements
    - Python 3
    - requests
    - colorama
    - pip install requests colorama
