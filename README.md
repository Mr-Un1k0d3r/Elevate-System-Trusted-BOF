# Elevate-System-Trusted-BOF

This BOF can be used to elevate the current beacon to SYSTEM and obtain the TrustedInstaller. The impersonation is done through the `SetThreadToken` API

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
