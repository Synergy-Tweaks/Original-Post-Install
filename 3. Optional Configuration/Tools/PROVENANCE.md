# Bundled tool provenance

These are third-party utilities committed into this repository rather than downloaded
at runtime. Anyone installing SynergyOS is trusting *our* copies, so the upstream
source and a checksum for each one are recorded here.

Verify a copy against this list with:

```powershell
Get-FileHash -Algorithm SHA256 ".\Autoruns.exe"
```

| File | Version | Publisher | Upstream |
| --- | --- | --- | --- |
| `Autoruns.exe` | 14.09 | Microsoft Sysinternals | <https://learn.microsoft.com/sysinternals/downloads/autoruns> |
| `DeviceCleanup.exe` | 2013-2021 build | Uwe Sieber (freeware) | <https://www.uwe-sieber.de/misc_tools_e.html> |
| `GoInterruptPolicy.exe` | 1.9.0.0 | spddl | <https://github.com/spddl/GoInterruptPolicy> |
| `PowerRun/PowerRun.exe` | 1.6.0.0 | Sordum | <https://www.sordum.org/downloads/?power-run> |

## SHA-256

```
76ecfda929285dbe75c877455332bbf30218269c03700b4e884345cf9b3ba6b5  DeviceCleanup.exe
64d490783abd017ac36a017b9cb7dcfc2fcee85f7ae8ee203a0c898da6d37533  Autoruns.exe
2fa5d9467fe7baab9bd88274b8abb66e21489dbdb99dd7be38c7ac36df093b91  GoInterruptPolicy.exe
4c82fbafef9bab484a2fbe23e4ec8aac06e8e296d6c9e496f4a589f97fd4ab71  PowerRun/PowerRun.exe
```

Update this file whenever one of the bundled binaries is replaced.
