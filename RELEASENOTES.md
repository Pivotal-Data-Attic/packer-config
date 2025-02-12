# packer-config Release Notes

## 1.3.0

* Add support for vmware-vmx building (via [tduehr][])

## 1.2.0

* Add support for docker-save post-processor (via [frasercobb][])
* Add support for docker-tab post-processor (via [frasercobb][])

## 1.1.0
* Thanks to [grepory][] we have a `vmware-vmx` builder

## 1.0.0
* A 1.0.0 release because...why not? You're either working or you're not and this is working so let's drop the `0.x.x` pretense and tango.
* Thanks to [frasercobb][] we have `puppet-server` and `puppet-masterless` provisioner interfaces
* There's also `ansible`, `chef-client`, `chef-solo` and `salt` provisioners for you to use now
* Added the `null` builder because it seemed handy to have
* Updated the example in the README (and the integration test) to CentOS 6.6
* Moved the legalese in to COPYRIGHT and got it out of the all of the individual files

## 0.0.4

* Added the ability to call `#build` with a quiet option. This option turns streaming to stdout off/on. With `quiet: false`, you will see the output of the Packer call on your screen while `#build` is executing it. This can be handy for view Packer status for long running Packer jobs.
* Started writing release notes!


  [tduehr]: https://github.com/tduehr
  [frasercobb]: https://github.com/frasercobb
  [grepory]: https://github.com/grepory
  [ianchesal]: https://github.com/ianchesal
