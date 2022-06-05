python-setproctitle-1.2.x-srpm
==============================

SRPM building tools for python-setproctitle, for Samba 4 on RHEL 9.

The "make" command will do these steps.

	make build	# Build the package on the local OS
	make all	# Use "mock" to build the packages with the local
			# samba4repo-8-x96_64 configuration, which needs.
	make install	# Actually install the RPM's in the repo

		Nico Kadel-Garcia <nkadel@gmail.com>
