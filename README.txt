PayFlex NG PWA package

Contents:
- index.html: your current PayFlex NG HTML interface
- manifest.json: app metadata for installation/package tools
- sw.js: basic service worker
- icons/: generated app icons

Important:
This package is NOT an APK. To package it with PWABuilder, first upload these files to a public HTTPS website, then enter that website URL at https://www.pwabuilder.com and choose Package for stores > Android. This app's payment functions are still prototype-only; Paystack and bill-payment APIs are not connected. Do not accept real customer money until a secure backend, verified payment flow, provider approval, and appropriate compliance are complete.
