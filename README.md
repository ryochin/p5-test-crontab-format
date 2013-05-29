# NAME

Test::Crontab::Format - Check crontab format validity

# SYNOPSIS

    use Test::Crontab::Format;

    crontab_format_ok("etc/crontab.txt");
    crontab_format_ok( \ $content );

# DESCRIPTION

Test::Crontab::Format checkes your crontab format is valid or not.

# FUNCTIONS

- __crontab\_format\_ok__

    Checkes the validity. You can pass file name or scalar ref.

# NOTE

passing empty file/content always yields failure.

# DEPENDENCY

Parse::Crontab

# REPOSITORY

https://github.com/ryochin/p5-test-crontab-format

# AUTHOR

Ryo Okamoto <ryo@aquahill.net>

# COPYRIGHT & LICENSE

Copyright (c) Ryo Okamoto, all rights reserved.

This program is free software; you can redistribute it and/or modify it
under the same terms as Perl itself.
