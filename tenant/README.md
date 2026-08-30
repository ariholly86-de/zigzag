# Sigma Cafe Commercial Tenants

This repository is the isolated commercial control center for cafe subscribers.

Each tenant has its own tenant code/slug and six application module routes:
- QR Meja
- Pelanggan
- Kasir
- Dapur
- Owner
- Stokis Barang

Production Issho Cafe data is not used by the Sigma tenant control tables. Tenant-specific application pages should use the tenant slug and the `sigma_*` commercial namespace.