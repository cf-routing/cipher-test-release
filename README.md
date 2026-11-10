## CIPHER Test Release

BOSH release with an errand to test the configured cipher suites against the router IP and Port.
The probe checks OpenSSL cipher names for TLS 1.2 and lower (colon-separated); TLS 1.3 suites are not tested, and the router must accept TLS 1.2; each entry must be a single exact OpenSSL cipher name, not an alias or cipher string (e.g. HIGH, ECDHE+AESGCM), not an RFC name such as TLS_ECDHE_RSA_WITH_AES_128_GCM_SHA256.
