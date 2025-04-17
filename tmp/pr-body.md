# 🚨 Trivy Vulnerability Report (High/Critical)
* Target: go.mod
        • Package: github.com/clastix/kamaji
        • Severity: CRITICAL
        • Title: RBAC Roles for `etcd` created by Kamaji are not disjunct
        • Description: Kamaji is the Hosted Control Plane Manager for Kubernetes. In versions 1.0.0 and earlier, Kamaji uses an "open at the top" range definition in RBAC for etcd roles leading to some TCPs API servers being able to read, write, and delete the data of other control planes. This vulnerability is fixed in edge-24.8.2.
        • Installed Version: v1.0.0
        • Fixed Version: N/A
        • CWE: CWE-284
        • CVE: CVE-2024-42480
        • References: https://avd.aquasec.com/nvd/cve-2024-42480
    
