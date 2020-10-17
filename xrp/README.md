## Dependencies

These tools use the ripple-api found [here](https://xrpl.org/get-started-with-rippleapi-for-javascript.html).

### Install Node Version Manager

```sudo apt update```\
```sudo apt install build-essential checkinstall libssl-dev```\
```curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.35.1/install.sh | bash```

The above will modify your `.bashrc` file.

```source ~/.bashrc```\
```nvm --version```

Check for current npm releases:
```nvm ls-remote```

Install the your preferred `npm` version:
```nvm install <version>.<number>```

### Install ripple-api
From`./xrp`:\
`yarn`

## Tools

* To submit a transaction:\
```node submit_transaction.js <transaction hash>```
