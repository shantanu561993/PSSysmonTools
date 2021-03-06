# PSSysmonTools
Sysmon Tools for PowerShell

## Implemented functions
### Get-SysmonConfiguration
Parses a Sysmon driver configuration from the registry. Output is nearly identical to that of "sysmon.exe -c" but without the requirement to run sysmon.exe.
### ConvertFrom-SysmonBinaryConfiguration
Parses a binary Sysmon configuration. ConvertFrom-SysmonBinaryConfiguration is designed to serve as a helper function for Get-SysmonConfiguration.

Please refer to built-in help for each function for more information.

## Notes
These PowerShell functions will need to be manually validated for each new Sysmon and configuration schema version. Please report all bugs and indiscrepencies with new versions by supplying the following information:

1) The Sysmon config XML that's generating the error (only schema versions 3.30 and later).
2) The version of Sysmon being used (only 6.20 and later).

Also, please file feature requests in the form of GitHub issues! Thank you!
