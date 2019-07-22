# SSHFS Snap package for Multipass

This creates a Snap package for use with Multipass launched virtual machine
instances.  When launching an instance, Multipass will automatically install
the SSHFS Snap in the instance for allowing mounts from the host machine into
the instance via `multipass mount`.

# Note

This package is not intended to be used for stand-alone SSHFS mounts on a system.
Only Multipass should be used for this.
