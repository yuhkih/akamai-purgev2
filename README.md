# Akamai Purge Python Sample Script with API v2
Sample purge request using API v2

# What you need.

## 1. get a credential from LUNA portal
It'like following information. There are four kind of information.  
(the following is dummy and doesn't work. you need to get your own credential from LUNA portal)  

    client_secret = NRkv6et17nqkr8WelIEinr53534643fgH9XvLriss7PY4SJo=  
    host = akab-jza67c2hm2nupbwq-taeredwob5vr67wf.luna.akamaiapis.net  
    access_token = akab-ape6flkotadfaefhrl-532hlfdttj2sxxq6  
    client_token = akab-vqzjnqjelbzwwqve-ysfgrrrfsys5mt  

## 2.python environment 
This script was made under Python 2.7.12  

## 3.Edgegird tool for python by Akamai 
edgegrid is a set of script to make it easy to create the signature needed for an API request. 
  
You need to set up edgegrid-python to use this script  
https://github.com/akamai/AkamaiOPEN-edgegrid-python  
  
edgegrid will generenate the signature which is to be put in HTTP header in a request. The signature is created from the information you get at step 1.  


