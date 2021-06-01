NAMF-2019-24 (2021-06-01)

* preparation to migrate to NAMF-2020
* collect SDS reading stats when checking for autoupdate

NAMF-2019-023 (2021-05-11)

* disabled all SSL sending data
* disabled opensense map - this API is SSL only

NAMF-2019-022 (2021-05-11)

* As a workaround with SSL problems - all requests to 3rd API are sent to port 80 (no SSL). This prevents sensor from crashing if it sents data to http://aqi.eco/ Arduino Core upgrade would help, but then binary will be to big - we need to move to NAMF-2020 line