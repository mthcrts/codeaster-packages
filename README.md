codeaster-packages
==================

This repository provides *unofficial* Code_Aster packages.

"Unofficial" means *unsupported* by EDF R&D and that the binaries have not been
validated, and may not pass all the testcases.


# Packages for Debian 7:

The package probably on Debian 6 and Ubuntu variants.



Add this entry for `apt` (as `root` or with administration rights):

        cat << EOF > /etc/apt/sources.list.d/codeaster.list
        deb https://raw.githubusercontent.com/mthcrts/codeaster-packages/master/Debian7 debian/
        EOF

Update your packages index files and install with:

        apt-get update
        apt-get install codeaster-full-12.3

Note: The package does not respect the Debian Packaging Guidelines, because it contains
      the products as embeeded in the `aster-full` archive, and there are too many
      products to create individual package.


Do not hesitate to report all problems, even if I work on that only on my free time.

