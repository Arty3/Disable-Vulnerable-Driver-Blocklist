# Disable Vulnerable Driver Blocklist

This is a simple registry edit that disables the vulnerable driver blocklist on Windows 11.
This is a useful utility for security related development purposes.

## Usage

Run the [disable_vulnerable_driver_blocklist.reg](./registry/disable_vulnerable_driver_blocklist.reg) file.

You will probably get a security warning, feel free to simply click "run" (or whichever option shows up for you) and now the blocklist should be disabled.

To undo run the [enable_vulnerable_driver_blocklist.reg](./registry/enable_vulnerable_driver_blocklist.reg) file.

Again, you will probably get a security warning, and again feel free to simply click "run" (or whichever option shows up for you) and now the blocklist should be enabled.

If you want to do this process avoiding the registry, head to Windows Security, then Device Security, Core Isolation Details, and at the bottom of the page you will find a switch for enabling/disabling the vulnerable driver blocklist. 

## License

Apache 2.0 (see [LICENSE](./LICENSE))
