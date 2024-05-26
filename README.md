# ed-php-84-new

## New Features in PHP 8.4

- Sodium: AEGIS-128L and AEGIS256 support
- New mb_ucfirst and mb_lcfirst functions
- New http_(get|clear)_last_response_headers functions
- Curl: curl_version() feature_list support
- PCRE2 Upgrade and Regular Expression Changes
- New request_parse_body function
- Date: New DateTime(Immutable)::get/setMicrosecond methods
- phpinfo: Show PHP Integer Size information
- New rounding modes in round() function
- Date: New DateTime(Immutable)::createFromTimestamp methods
- Mbstring: New mb_trim, mb_ltrim, and mb_rtrim functions

## Syntax/Functionality Changes in PHP 8.4

- round() - Invalid rounding modes throw \ValueError exceptions
- OpenSSL: Minimum required OpenSSL version increased to 1.1.1
- Curl: Minimum required libcurl version increased to 7.61.0
- Opcache: INI changes on how JIT is enabled
- PHP_ZTS and PHP_DEBUG constant value type changed from int to bool
- Password Hashing: Default Bcrypt cost changed from 10 to 12

## Deprecations in PHP 8.4

- Implicitly nullable parameter declarations deprecated
- Curl: CURLOPT_BINARYTRANSFER deprecated

## Removed Features and Functionality in PHP 8.4

- OCI8 and PDO-OCI extensions from PHP Core to PECL
- IMAP extension moved from PHP Core to PECL
- Pspell extension moved from PHP Core to PECL
