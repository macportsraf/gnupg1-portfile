# README

My version of the gnupg1 macports Portfile.

It differs from the official Portfile in that it doesn't conflict with the
gnupg2 port, so it doesn't force the user to choose between gnupg2 and
gnupg1.

It does this by naming the binary "gpg1" instead of "gpg".

Just because someone might really still need to use gnupg1, it doesn't mean
that they don't also need gnupg2, or any of the ports that depend on it.

