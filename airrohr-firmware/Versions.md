NAMF-2019-022 (2021-05-11)

* As a workaround with SSL problems - all requests to 3rd API are sent to port 80 (no SSL). This prevents sensor from crashing if it sents data to http://aqi.eco/ Arduino Core upgrade would help, but then binary will be to big - we need to move to NAMF-2020 line