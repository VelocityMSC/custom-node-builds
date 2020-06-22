# Custom Node.js binaries for CentOS 6 and 7

Builds Node.js without exporting OpenSSL symbols to ensure they don't clash with the system copy of OpenSSL in dynamically loaded libraries. Also adds needed build flags to build version 10+ on CentOS 6.

When a change to `NODE_VERSION` in `.github/workflows/ci.yml` is pushed new builds will be made automatically and added to the project releases.
