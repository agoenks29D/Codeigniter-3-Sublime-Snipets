# Codeigniter 3 RESTful Snippet

## Introduction

This snippets for [RESTful](https://en.wikipedia.org/wiki/Representational_state_transfer) library from [chriskacerguis](https://github.com/chriskacerguis/codeigniter-restserver)

## Usage

| Name | Tab Trigger |
|------|----------|
| Creating New RESTful Controler | rest |
| Send Response | res_send |
| REST Send Validation Errors | rest_error |

### REST Methods

**Tab Prefix** : `rest_`

[**Snippet Files**](rest-method/)

| Method | Tab Trigger | Description | 
|--------|-------------|-------------|
| HEAD | rest_head | create new **HEAD** method |
| GET | rest_get | create new **GET** method |
| POST | rest_post | create new **POST** method |
| PUT | rest_put | create new **PUT** method |
| PATCH | rest_patch | create new **PATCH** method |
| DELETE | rest_delete | create new **DELETE** method |
| OPTIONS | rest_options | create new **OPTIONS** method |

### REST Parameters

**Tab Prefix** : `_rest_`

[**Snippet Files**](rest-param/)

| Tab Trigger | Description |
|-------------|-------------|
| _head | accessing parameter from **HEAD** method |
| _get | accessing parameter from **GET** method |
| _post | accessing parameter from **POST** method |
| _put | accessing parameter from **PUT** method |
| _patch | accessing parameter from **PATCH** method |
| _delete | accessing parameter from **DELETE** method |
| _options | accessing parameter from **OPTIONS** method |

### HTTP CODE

**Tab Prefix** : `rest_http_`

[**Snippet Files**](http-code/integer)

| HTTP Code | Tab Trigger | Description |
|-----------|-------------|-------------|
| 100 | rest_http_100 | **HTTP_CONTINUE** |
| 101 | rest_http_101 | **HTTP_SWITCHING_PROTOCOLS** |
| 102 | rest_http_102 | **HTTP_PROCESSING** |

| HTTP Code | Tab Trigger | Description |
|-----------|-------------|-------------|
| 200 | rest_http_200 | **HTTP_OK** |
| 201 | rest_http_201 | **HTTP_CREATED** |
| 202 | rest_http_202 | **HTTP_ACCEPTED** |
| 203 | rest_http_203 | **HTTP_NON_AUTHORITATIVE_INFORMATION** |
| 204 | rest_http_204 | **HTTP_NO_CONTENT** |
| 205 | rest_http_205 | **HTTP_RESET_CONTENT** |
| 206 | rest_http_206 | **HTTP_PARTIAL_CONTENT** |
| 207 | rest_http_207 | **HTTP_MULTI_STATUS** |
| 208 | rest_http_208 | **HTTP_ALREADY_REPORTED** |
| 226 | rest_http_226 | **HTTP_IM_USED** |

| HTTP Code | Tab Trigger | Description |
|-----------|-------------|-------------|
| 300 | rest_http_300 | **HTTP_MULTIPLE_CHOICES** |
| 301 | rest_http_301 | **HTTP_MOVED_PERMANENTLY** |
| 302 | rest_http_302 | **HTTP_FOUND** |
| 303 | rest_http_303 | **HTTP_SEE_OTHER** |
| 304 | rest_http_304 | **HTTP_NOT_MODIFIED** |
| 305 | rest_http_305 | **HTTP_USE_PROXY** |
| 306 | rest_http_306 | **HTTP_RESERVED** |
| 307 | rest_http_307 | **HTTP_TEMPORARY_REDIRECT** |
| 308 | rest_http_308 | **HTTP_PERMANENTLY_REDIRECT** |

| HTTP Code | Tab Trigger | Description |
|-----------|-------------|-------------|
| 400 | rest_http_400 | **HTTP_BAD_REQUEST** |
| 401 | rest_http_401 | **HTTP_UNAUTHORIZED** |
| 402 | rest_http_402 | **HTTP_PAYMENT_REQUIRED** |
| 403 | rest_http_403 | **HTTP_FORBIDDEN** |
| 404 | rest_http_404 | **HTTP_NOT_FOUND** |
| 405 | rest_http_405 | **HTTP_METHOD_NOT_ALLOWED** |
| 406 | rest_http_406 | **HTTP_NOT_ACCEPTABLE** |
| 407 | rest_http_407 | **HTTP_PROXY_AUTHENTICATION_REQUIRED** |
| 408 | rest_http_408 | **HTTP_REQUEST_TIMEOUT** |
| 409 | rest_http_409 | **HTTP_CONFLICT** |
| 410 | rest_http_410 | **HTTP_GONE** |
| 411 | rest_http_411 | **HTTP_LENGTH_REQUIRED** |
| 412 | rest_http_412 | **HTTP_PRECONDITION_FAILED** |
| 413 | rest_http_413 | **HTTP_REQUEST_ENTITY_TOO_LARGE** |
| 414 | rest_http_414 | **HTTP_REQUEST_URI_TOO_LONG** |
| 415 | rest_http_415 | **HTTP_UNSUPPORTED_MEDIA_TYPE** |
| 416 | rest_http_416 | **HTTP_REQUESTED_RANGE_NOT_SATISFIABLE** |
| 417 | rest_http_417 | **HTTP_EXPECTATION_FAILED** |
| 418 | rest_http_418 | **HTTP_I_AM_A_TEAPOT** |
| 422 | rest_http_422 | **HTTP_UNPROCESSABLE_ENTITY** |
| 423 | rest_http_423 | **HTTP_LOCKED** |
| 424 | rest_http_424 | **HTTP_FAILED_DEPENDENCY** |
| 425 | rest_http_425 | **HTTP_RESERVED_FOR_WEBDAV_ADVANCED_COLLECTIONS_EXPIRED_PROPOSAL** |
| 426 | rest_http_426 | **HTTP_UPGRADE_REQUIRED** |
| 428 | rest_http_428 | **HTTP_PRECONDITION_REQUIRED** |
| 429 | rest_http_429 | **HTTP_TOO_MANY_REQUESTS** |
| 431 | rest_http_431 | **HTTP_REQUEST_HEADER_FIELDS_TOO_LARGE** |

| HTTP Code | Tab Trigger | Description |
|-----------|-------------|-------------|
| 500 | rest_http_500 | **HTTP_INTERNAL_SERVER_ERROR** |
| 501 | rest_http_501 | **HTTP_NOT_IMPLEMENTED** |
| 502 | rest_http_502 | **HTTP_BAD_GATEWAY** |
| 503 | rest_http_503 | **HTTP_SERVICE_UNAVAILABLE** |
| 504 | rest_http_504 | **HTTP_GATEWAY_TIMEOUT** |
| 505 | rest_http_505 | **HTTP_VERSION_NOT_SUPPORTED** |
| 506 | rest_http_506 | **HTTP_VARIANT_ALSO_NEGOTIATES_EXPERIMENTAL** |
| 507 | rest_http_507 | **HTTP_INSUFFICIENT_STORAGE** |
| 508 | rest_http_508 | **HTTP_LOOP_DETECTED** |
| 510 | rest_http_510 | **HTTP_NOT_EXTENDED** |
| 511 | rest_http_511 | **HTTP_NETWORK_AUTHENTICATION_REQUIRED** |

---

**Tab Prefix** : `rest_`

[**Snippet Files**](http-code/string)

| HTTP Code | Tab Trigger | Description |
|-----------|-------------|-------------|
| 100 | rest_http_continue | **HTTP_CONTINUE** |
| 101 | rest_http_switching_protocols | **HTTP_SWITCHING_PROTOCOLS** |
| 102 | rest_http_processing | **HTTP_PROCESSING** |

| HTTP Code | Tab Trigger | Description |
|-----------|-------------|-------------|
| 200 | rest_http_ok | **HTTP_OK** |
| 201 | rest_http_created | **HTTP_CREATED** |
| 202 | rest_http_accepted | **HTTP_ACCEPTED** |
| 203 | rest_http_non_authoritative_information | **HTTP_NON_AUTHORITATIVE_INFORMATION** |
| 204 | rest_http_no_content | **HTTP_NO_CONTENT** |
| 205 | rest_http_reset_content | **HTTP_RESET_CONTENT** |
| 206 | rest_http_partial_content | **HTTP_PARTIAL_CONTENT** |
| 207 | rest_http_multi_status | **HTTP_MULTI_STATUS** |
| 208 | rest_http_already_reported | **HTTP_ALREADY_REPORTED** |
| 226 | rest_http_im_used | **HTTP_IM_USED** |

| HTTP Code | Tab Trigger | Description |
|-----------|-------------|-------------|
| 300 | rest_http_multiple_choices | **HTTP_MULTIPLE_CHOICES** |
| 301 | rest_http_moved_permanently | **HTTP_MOVED_PERMANENTLY** |
| 302 | rest_http_found | **HTTP_FOUND** |
| 303 | rest_http_see_other | **HTTP_SEE_OTHER** |
| 304 | rest_http_not_modified | **HTTP_NOT_MODIFIED** |
| 305 | rest_http_use_proxy | **HTTP_USE_PROXY** |
| 306 | rest_http_reserved | **HTTP_RESERVED** |
| 307 | rest_http_temporary_redirect | **HTTP_TEMPORARY_REDIRECT** |
| 308 | rest_http_permanently_redirect | **HTTP_PERMANENTLY_REDIRECT** |

| HTTP Code | Tab Trigger | Description |
|-----------|-------------|-------------|
| 400 | rest_http_bad_request | **HTTP_BAD_REQUEST** |
| 401 | rest_http_unauthorized | **HTTP_UNAUTHORIZED** |
| 402 | rest_http_payment_required | **HTTP_PAYMENT_REQUIRED** |
| 403 | rest_http_forbidden | **HTTP_FORBIDDEN** |
| 404 | rest_http_not_found | **HTTP_NOT_FOUND** |
| 405 | rest_http_method_not_allowed | **HTTP_METHOD_NOT_ALLOWED** |
| 406 | rest_http_not_acceptable | **HTTP_NOT_ACCEPTABLE** |
| 407 | rest_http_proxy_authentication_required | **HTTP_PROXY_AUTHENTICATION_REQUIRED** |
| 408 | rest_http_request_timeout | **HTTP_REQUEST_TIMEOUT** |
| 409 | rest_http_conflict | **HTTP_CONFLICT** |
| 410 | rest_http_gone | **HTTP_GONE** |
| 411 | rest_http_length_required | **HTTP_LENGTH_REQUIRED** |
| 412 | rest_http_precondition_failed | **HTTP_PRECONDITION_FAILED** |
| 413 | rest_http_request_entity_too_large | **HTTP_REQUEST_ENTITY_TOO_LARGE** |
| 414 | rest_http_request_uri_too_long | **HTTP_REQUEST_URI_TOO_LONG** |
| 415 | rest_http_unsupported_media_type | **HTTP_UNSUPPORTED_MEDIA_TYPE** |
| 416 | rest_http_requested_range_not_satisfiable | **HTTP_REQUESTED_RANGE_NOT_SATISFIABLE** |
| 417 | rest_http_expectation_failed | **HTTP_EXPECTATION_FAILED** |
| 418 | rest_http_i_am_a_teapot | **HTTP_I_AM_A_TEAPOT** |
| 422 | rest_http_unprocessable_entity | **HTTP_UNPROCESSABLE_ENTITY** |
| 423 | rest_http_locked | **HTTP_LOCKED** |
| 424 | rest_http_failed_dependency | **HTTP_FAILED_DEPENDENCY** |
| 425 | rest_http_reserved_for_webdav_advanced_collections_expired_proposal | **HTTP_RESERVED_FOR_WEBDAV_ADVANCED_COLLECTIONS_EXPIRED_PROPOSAL** |
| 426 | rest_http_upgrade_required | **HTTP_UPGRADE_REQUIRED** |
| 428 | rest_http_precondition_required | **HTTP_PRECONDITION_REQUIRED** |
| 429 | rest_http_too_many_requests | **HTTP_TOO_MANY_REQUESTS** |
| 431 | rest_http_request_header_fields_too_large | **HTTP_REQUEST_HEADER_FIELDS_TOO_LARGE** |

| HTTP Code | Tab Trigger | Description |
|-----------|-------------|-------------|
| 500 | rest_http_internal_server_error | **HTTP_INTERNAL_SERVER_ERROR** |
| 501 | rest_http_not_implemented | **HTTP_NOT_IMPLEMENTED** |
| 502 | rest_http_bad_gateway | **HTTP_BAD_GATEWAY** |
| 503 | rest_http_service_unavailable | **HTTP_SERVICE_UNAVAILABLE** |
| 504 | rest_http_gateway_timeout | **HTTP_GATEWAY_TIMEOUT** |
| 505 | rest_http_version_not_supported | **HTTP_VERSION_NOT_SUPPORTED** |
| 506 | rest_http_variant_also_negotiates_experimental | **HTTP_VARIANT_ALSO_NEGOTIATES_EXPERIMENTAL** |
| 507 | rest_http_insufficient_storage | **HTTP_INSUFFICIENT_STORAGE** |
| 508 | rest_http_loop_detected | **HTTP_LOOP_DETECTED** |
| 510 | rest_http_not_extended | **HTTP_NOT_EXTENDED** |
| 511 | rest_http_network_authentication_required | **HTTP_NETWORK_AUTHENTICATION_REQUIRED** |

---

<p align="center"><img src="https://cdn-images-1.medium.com/max/738/1*G95uyokAH4JC5Ppvx4LmoQ@2x.png" width="280"></p>

[**PATREON**](https://www.patreon.com/agoenks29D)

[**PAYPAL**](https://www.paypal.me/agungdirgantara)

**[ETH](https://www.blockchain.com/eth/address/0x251b36840557cCe9A245f07E1b834bCfb7354FDb) : 0x251b36840557cCe9A245f07E1b834bCfb7354FDb**

**[DOGE](https://dogechain.info/address/DFmES6KZLQXimXduXwKmooykMsjhWmT1tU) : DFmES6KZLQXimXduXwKmooykMsjhWmT1tU**

**[BITCOIN](https://www.blockchain.com/btc/address/1MEqUeg7fXTkBMFWfJZE9yJREsKZ4SUxQM) : 1MEqUeg7fXTkBMFWfJZE9yJREsKZ4SUxQM**

**[BITCOIN CASH](https://www.blockchain.com/bch/address/qzrllcyrjwvpnuur5kpeyp03p246fzsgzvhleswr6f) : qzrllcyrjwvpnuur5kpeyp03p246fzsgzvhleswr6f**

### Social Media : 

<a class="social_link" href="https://fb.me/agoenks29D">
	<img src="https://static.xx.fbcdn.net/rsrc.php/yo/r/iRmz9lCMBD2.ico" width="32" style="margin-bottom: 2px;">
</a>

<a class="social_link" href="https://instragram.com/agoenks29D">
	<img src="https://www.instagram.com/static/images/ico/favicon.ico/36b3ee2d91ed.ico" width="32">
</a>

<a class="social_link" href="https://t.me/agoenks29D">
	<img src="https://web.telegram.org/favicon.ico" width="32">
</a>

<a class="social_link" href="https://api.whatsapp.com/send?phone=6282167368585&text=Hello,i get your contact from github">
	<img src="https://static.whatsapp.net/rsrc.php/v3/yP/r/rYZqPCBaG70.png" width="36">
</a>

<a class="social_link" href="https://www.youtube.com/channel/UCwXyVSMRqAuyyQtXVoMrf2A?view_as=subscriber&sub_cotnfirmation=1">
	<img src="https://s.ytimg.com/yts/img/favicon_48-vflVjB_Qk.png" width="38">
</a> 

<p></p>

<p align="center"><b>Made with ❤️ + ☕ ~ Agung Dirgantara</b></p>