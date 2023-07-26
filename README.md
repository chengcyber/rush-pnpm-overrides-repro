# Reproduce repo for pnpm.overrides issue

# Steps

```shell
git clone git@github.com:chengcyber/rush-pnpm-overrides-repro.git

cd rush-pnpm-overrides-repro

rush install
```

Outputs

```
The shrinkwrap file contains the following issues:
  Dependencies of project "foo" do not match the current shrinkwrap.


The shrinkwrap file is out of date. You need to run "rush update".
```

Rerunning `rush update` won't solve this issue.
