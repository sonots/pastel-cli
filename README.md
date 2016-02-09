# pastel-cli

cli tool for patel ([bobpp/pastel](https://github.com/bobpp/pastel) or [sonots/go-pastel](https://github.com/sonots/go-pastel))

# How to use

1) Post to pastel

    $ cat /path/to/file | pastel-cli http://your.pastel.name
    #=> http://your.pastel.name/memos/e5c4db3459a13d0b07da7435b0956bc304d2b82d

2) Get from pastel

    $ pastel-cli http://your.pastel.name/memos/e5c4db3459a13d0b07da7435b0956bc304d2b82d
    #=> contents

# Tips

Define `$PASTEL_BASE_URL` in the code to omit typing pastel base url on post command: 

```perl
my $PASTEL_BASE_URL = 'http://your.pastel.name';
```

1) Post to pastel

    $ cat /path/to/file | pastel-cli

# License

MIT License
