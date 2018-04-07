[![Build Status](https://travis-ci.org/juju4/msoffice-baseline.svg?branch=master)](https://travis-ci.org/juju4/msoffice-baseline)

msoffice-baseline
================

This Baseline ensures, that all hardening projects keep the same quality.

- https://github.com/juju4/msoffice-baseline

## Standalone Usage

This Compliance Profile requires [InSpec](https://github.com/chef/inspec) for execution:

```
$ git clone https://github.com/juju4/msoffice-baseline
$ inspec exec msoffice-baseline
```

You can also execute the profile directly from Github:

```
$ inspec exec https://github.com/juju4/msoffice-baseline

# run test on remote windows host on WinRM
$ inspec exec test.rb -t winrm://Administrator@windowshost --password 'your-password'
```

## License

BSD 2-clause

