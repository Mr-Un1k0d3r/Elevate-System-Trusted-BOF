# Elevate-System-Trusted-BOF

This BOF can be used to elevate the current beacon to SYSTEM and obtain the TrustedInstaller group privilege. The impersonation is done through the `SetThreadToken` API.

![bof](https://raw.githubusercontent.com/Mr-Un1k0d3r/Elevate-System-Trusted-BOF/main/output.png)

# Compiling

```
gcc elevate_x64.c -c -o elevate_x64.o
```

# Usage 

```
inline-execute C:\elevate_x64.o
```

# Credit 

Mr.Un1k0d3r RingZer0 Team
