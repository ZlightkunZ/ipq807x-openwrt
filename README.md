# ipq807x-openwrt-builder
Automated builds of robimarko's IPQ807x OpenWRT repository \([ipq807x-5.15-pr branch](https://github.com/robimarko/openwrt/tree/ipq807x-5.15-pr)\) using GitHub Actions

- robimarko's fork is pulled weekly and if last commit is less than a week old a new build is triggered.
- Manual build can also be triggered.
- Build artifacts are stored as releases.
- Build options are embedded in [ipq807x.yaml](/.github/workflows/ipq807x.yaml) file.
