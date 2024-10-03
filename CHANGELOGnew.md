# Changelog

## [Unreleased](https://github.com/puppetlabs/puppetlabs-bootstrap/tree/HEAD)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-bootstrap/compare/v2.1.0...HEAD)

**Breaking changes:**

- pdksync - Remove Puppet 5 from testing and bump minimal version to 6.0.0 [\#159](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/159) ([carabasdaniel](https://github.com/carabasdaniel))

**Closed issues:**

- Add the ability to specify puppet.conf options to bootstrap task [\#166](https://github.com/puppetlabs/puppetlabs-bootstrap/issues/166)
- Task fails with no descriptive error if tar isn't installed on target host. [\#156](https://github.com/puppetlabs/puppetlabs-bootstrap/issues/156)
- Specifying extension requests and custom attributes as per README fails with data type validation error [\#80](https://github.com/puppetlabs/puppetlabs-bootstrap/issues/80)

**Merged pull requests:**

- Added the ability to set puppet.conf settings via a parameter. [\#167](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/167) ([benjamin-robertson](https://github.com/benjamin-robertson))
- add support clarification notice [\#164](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/164) ([binford2k](https://github.com/binford2k))
- \(docs\) correct install docs link [\#163](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/163) ([binford2k](https://github.com/binford2k))
- \[ISSUE-80\] Update the README to improve the instructions for use of ex… [\#162](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/162) ([nebakke](https://github.com/nebakke))
- pdksync - Remove EL6 testing from Travis [\#158](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/158) ([carabasdaniel](https://github.com/carabasdaniel))
- pdksync - \(IAC-973\) - Update travis/appveyor to run on new default branch main [\#147](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/147) ([david22swan](https://github.com/david22swan))
- pdksync - \(IAC-890\) - Implement CentOS 8 travis tests [\#145](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/145) ([david22swan](https://github.com/david22swan))
- pdksync - Use abs instead of vmpooler to provision test resources [\#144](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/144) ([carabasdaniel](https://github.com/carabasdaniel))
- pdksync - \(maint\) - Pdk Update [\#143](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/143) ([david22swan](https://github.com/david22swan))
- \(maint\) Update CODEOWNERS [\#142](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/142) ([DavidS](https://github.com/DavidS))
- Ensure '$set\_noop' is lowercase for consistency [\#141](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/141) ([zoojar](https://github.com/zoojar))
- pdksync - Add dependency gems to development group [\#140](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/140) ([carabasdaniel](https://github.com/carabasdaniel))
- add set\_noop parameter [\#139](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/139) ([zoojar](https://github.com/zoojar))
- \(MAINT\) Update docker image names [\#136](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/136) ([michaeltlombardi](https://github.com/michaeltlombardi))
- \(IAC-555\) pdksync - Remove distelli-manifest.yml [\#135](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/135) ([david22swan](https://github.com/david22swan))
- pdksync - \(maint\) - Pdk Update [\#134](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/134) ([david22swan](https://github.com/david22swan))
- pdksync - Update weekly scheduled workflows [\#133](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/133) ([carabasdaniel](https://github.com/carabasdaniel))
- pdksync - Add weekly scheduled workflows [\#130](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/130) ([carabasdaniel](https://github.com/carabasdaniel))
- pdksync - \(IAC-215\) - Implement use\_litmus:true [\#129](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/129) ([david22swan](https://github.com/david22swan))

## [v2.1.0](https://github.com/puppetlabs/puppetlabs-bootstrap/tree/v2.1.0) (2020-02-07)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-bootstrap/compare/v2.0.0...v2.1.0)

**Merged pull requests:**

- \(IAC-365\) updating tokens and dataset for honeycomb [\#126](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/126) ([sheenaajay](https://github.com/sheenaajay))
- \(MODULES-10465\) Mergeback from release 2.1.0 [\#125](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/125) ([michaeltlombardi](https://github.com/michaeltlombardi))
- \(FM-8581\) - Debian 10 added to travis and provision file refactored [\#124](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/124) ([david22swan](https://github.com/david22swan))
- pdksync - FM-8834 - Add GitHub action workflow [\#123](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/123) ([lionce](https://github.com/lionce))
- pdksync - \(maint\) travis updates: bundler and slack [\#121](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/121) ([DavidS](https://github.com/DavidS))
- pdksync - "MODULES-10236 disable deploy\_to\_forge for the module" [\#120](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/120) ([sheenaajay](https://github.com/sheenaajay))
- \(MODULES-10242\) Re-Add Ubuntu 14 as supported OS [\#119](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/119) ([sheenaajay](https://github.com/sheenaajay))
- \(MODULES-10120\) enable simplecov; update to PDK 1.14.1; minor cleanups [\#118](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/118) ([DavidS](https://github.com/DavidS))
- \(FM-8686\) - Addition of Support for CentOS 8 [\#117](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/117) ([david22swan](https://github.com/david22swan))
- \(MODULES-10077\) - v2.0.0 Release Merge Back [\#116](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/116) ([david22swan](https://github.com/david22swan))

## [v2.0.0](https://github.com/puppetlabs/puppetlabs-bootstrap/tree/v2.0.0) (2019-11-11)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-bootstrap/compare/v1.0.0...v2.0.0)

**Breaking changes:**

- pdksync - FM-8499 - remove ubuntu14 support [\#114](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/114) ([lionce](https://github.com/lionce))

**Merged pull requests:**

- \(PDK-1501\) Allow Appveyor CI config to be templated [\#115](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/115) ([glennsarti](https://github.com/glennsarti))
- \(PDK-1501\) Fix acceptance stages in Travis CI [\#113](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/113) ([glennsarti](https://github.com/glennsarti))
- pdksync - \(FM-8634\) ensure encrypted communication for fixtures [\#112](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/112) ([DavidS](https://github.com/DavidS))
- \(FM-8391\) Update README per team practices [\#109](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/109) ([michaeltlombardi](https://github.com/michaeltlombardi))
- \(PDK-1501\) Allow Travis CI config to be templated [\#108](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/108) ([glennsarti](https://github.com/glennsarti))
- pdksync - \(maint\) Override pdk gem version to master branch \(PDK-1525 workaround until release\) [\#107](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/107) ([sanfrancrisko](https://github.com/sanfrancrisko))
- \(MAINT\) Ensure TLS is enabled first on Windows [\#106](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/106) ([michaeltlombardi](https://github.com/michaeltlombardi))
- \(FM-8275\) Add vagrant provision list [\#104](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/104) ([michaeltlombardi](https://github.com/michaeltlombardi))
- pdksync - Remove nodesets [\#103](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/103) ([florindragos](https://github.com/florindragos))
- \(maint\) Add a codeowners file [\#102](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/102) ([tphoney](https://github.com/tphoney))
- pdksync - \(MAINT\) pdksync: fix for net-ssh 5 host\_key check [\#100](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/100) ([florindragos](https://github.com/florindragos))
- pdksync - MODULES-9692 - pdksync\_1.12.0-0-g55d9ae2 [\#99](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/99) ([sheenaajay](https://github.com/sheenaajay))
- v1.0.0 mergeback [\#98](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/98) ([tphoney](https://github.com/tphoney))

## [v1.0.0](https://github.com/puppetlabs/puppetlabs-bootstrap/tree/v1.0.0) (2019-07-25)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-bootstrap/compare/0.5.0...v1.0.0)

**Breaking changes:**

- pdksync - \(MODULES-8444\) - Raise lower Puppet bound [\#78](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/78) ([david22swan](https://github.com/david22swan))

**Merged pull requests:**

- MODULES-9557 Release Prep v1.0.0 [\#97](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/97) ([sheenaajay](https://github.com/sheenaajay))
- pdksync - pdksync\_heads/master-0-gb096033 [\#96](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/96) ([lionce](https://github.com/lionce))
- \(FM-7709\) pdksync and remove beaker [\#95](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/95) ([tphoney](https://github.com/tphoney))
- \(FM-8216\) Switch testing to use Litmus [\#94](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/94) ([eimlav](https://github.com/eimlav))
- pdksync - pdksync\_heads/master-0-g7827fc2 [\#93](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/93) ([ThoughtCrhyme](https://github.com/ThoughtCrhyme))
- \(FM-8150\) Add Windows Server 2019 support [\#92](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/92) ([eimlav](https://github.com/eimlav))
- \(FM-8112\) Ensure TLS set before other actions [\#91](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/91) ([michaeltlombardi](https://github.com/michaeltlombardi))
- \(FM-8112\) Ensure TLS 1.2 in Windows Task  [\#90](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/90) ([michaeltlombardi](https://github.com/michaeltlombardi))
- \(FM-8038\) Add RedHat 8 support [\#87](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/87) ([eimlav](https://github.com/eimlav))
- \[FM-7942\] Puppet Strings [\#86](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/86) ([carabasdaniel](https://github.com/carabasdaniel))
- \(maint\) add note about WMF/.NET versions supported [\#85](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/85) ([steveax](https://github.com/steveax))
- \(FM-7919\) Ensure TLSv1.2 is used when temporarily disabling ssl [\#84](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/84) ([steveax](https://github.com/steveax))
- pdksync - \(maint\) Update pdk-template to f778803 [\#83](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/83) ([eimlav](https://github.com/eimlav))
- \(MODULES-8848\) - Release mergeback 0.5.0 [\#75](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/75) ([pmcmaw](https://github.com/pmcmaw))

## [0.5.0](https://github.com/puppetlabs/puppetlabs-bootstrap/tree/0.5.0) (2019-04-04)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-bootstrap/compare/0.4.1...0.5.0)

**Closed issues:**

- install documentation on forge incorrect for puppet install [\#63](https://github.com/puppetlabs/puppetlabs-bootstrap/issues/63)
- Install task allows uppercase certnames [\#62](https://github.com/puppetlabs/puppetlabs-bootstrap/issues/62)

**Merged pull requests:**

- \(MODULES-8844\) - 0.5.0 Release Prep [\#74](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/74) ([david22swan](https://github.com/david22swan))
- \(SEN-787\) Make linux and windows private [\#73](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/73) ([conormurray95](https://github.com/conormurray95))
- \(SEN-787\) Add discovery extension metadata [\#72](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/72) ([conormurray95](https://github.com/conormurray95))
- \(SEN-787\) Add implementation metadata [\#71](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/71) ([conormurray95](https://github.com/conormurray95))
- pdksync - Remove .project from .gitignore [\#68](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/68) ([eimlav](https://github.com/eimlav))
- Ensure certnames are \*always\* lowercase [\#67](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/67) ([dylanratcliffe](https://github.com/dylanratcliffe))
- \(MODULES-3958\) enable rspec-mock and code coverage [\#66](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/66) ([tphoney](https://github.com/tphoney))
- Revert "\(FM-7720/FM-7722/FM-7723\) Consolidate Windows Metadata" [\#65](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/65) ([david22swan](https://github.com/david22swan))
- \(MODULES-6989\) Multiple extension\_requests/custom\_attributes Linux task [\#61](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/61) ([eimlav](https://github.com/eimlav))
- pdksync - pdksync\_1.9.0-0-g7281db5 [\#60](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/60) ([lionce](https://github.com/lionce))
- \(FM-7720/FM-7722/FM-7723\) Consolidate Windows Metadata [\#59](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/59) ([david22swan](https://github.com/david22swan))
- pdksync - pdksync\_heads/master-0-g6814a87 [\#58](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/58) ([david22swan](https://github.com/david22swan))
- pdksync - pdksync\_heads/master-0-g9c815ea [\#57](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/57) ([david22swan](https://github.com/david22swan))
- pdksync - \(FM-7655\) Fix rubygems-update for ruby \< 2.3 [\#56](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/56) ([tphoney](https://github.com/tphoney))
- pdksync - pdksync\_heads/master-0-gbf720df [\#55](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/55) ([eimlav](https://github.com/eimlav))
- pdksync - pdksync\_heads/master-0-gabccfb1 [\#54](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/54) ([david22swan](https://github.com/david22swan))
- Release merge back 0.4.1 [\#53](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/53) ([eimlav](https://github.com/eimlav))

## [0.4.1](https://github.com/puppetlabs/puppetlabs-bootstrap/tree/0.4.1) (2018-11-05)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-bootstrap/compare/0.4.0...0.4.1)

**Merged pull requests:**

- \(FM-7512\) - Add in Windows OS Support [\#52](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/52) ([pmcmaw](https://github.com/pmcmaw))
- \(FM-7512\) - Updating to include additional platforms [\#51](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/51) ([pmcmaw](https://github.com/pmcmaw))
- \(MODULES-8203\) Prepare 0.4.1 release [\#50](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/50) ([MikaelSmith](https://github.com/MikaelSmith))
- \(MODULES-8154\) Correct environment argument [\#49](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/49) ([MikaelSmith](https://github.com/MikaelSmith))
- \(MODULES-7933\) - 0.4.0 Merge Back [\#48](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/48) ([david22swan](https://github.com/david22swan))

## [0.4.0](https://github.com/puppetlabs/puppetlabs-bootstrap/tree/0.4.0) (2018-09-27)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-bootstrap/compare/0.3.0...0.4.0)

**Merged pull requests:**

- \(MODULES-7933\) - Release prep for 0.4.0 [\#47](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/47) ([eimlav](https://github.com/eimlav))
- pdksync - \(FM-7392\) - Puppet 6 Testing Changes [\#46](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/46) ([pmcmaw](https://github.com/pmcmaw))
- \(MODULES-7838\) Windows task contains typo which causes failure. [\#45](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/45) ([davejohnston](https://github.com/davejohnston))
- pdksync - \(MODULES-6805\) metadata.json shows support for puppet 6 [\#44](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/44) ([tphoney](https://github.com/tphoney))
- \(FM-7399\) - Prepare for changelog generator [\#42](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/42) ([pmcmaw](https://github.com/pmcmaw))
- pdksync - \(MODULES-7658\) use beaker4 in puppet-module-gems [\#40](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/40) ([tphoney](https://github.com/tphoney))
- \(maint\) clarify master parameter [\#39](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/39) ([steveax](https://github.com/steveax))
- pdksync - Update using 1.7.0 [\#38](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/38) ([pmcmaw](https://github.com/pmcmaw))
- pdksync - \(MODULES-7658\) use beaker3 in puppet-module-gems [\#37](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/37) ([tphoney](https://github.com/tphoney))
- \(MODULES-7647\) - Update README Limitations section [\#36](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/36) ([eimlav](https://github.com/eimlav))
- \(MODULES-7511\) Add Environment option for Windows [\#35](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/35) ([MikaelSmith](https://github.com/MikaelSmith))
- \(FM-7269\) - Addition of support for ubuntu 1804 [\#34](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/34) ([david22swan](https://github.com/david22swan))
- \(MODULES-7511\) - Add ability to insert environment name during agent install [\#33](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/33) ([raj-andy1](https://github.com/raj-andy1))
- Update requirements [\#32](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/32) ([gabe-sky](https://github.com/gabe-sky))
- Add tags and text to improve searchability [\#31](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/31) ([gabe-sky](https://github.com/gabe-sky))
- \[FM-7063\] Addition of Debian 9 support to Bootstrap [\#30](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/30) ([david22swan](https://github.com/david22swan))

## [0.3.0](https://github.com/puppetlabs/puppetlabs-bootstrap/tree/0.3.0) (2018-06-04)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-bootstrap/compare/0.2.0...0.3.0)

**Merged pull requests:**

- Release prep 0.3.0 [\#29](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/29) ([hunner](https://github.com/hunner))
- \(maint\) Update beaker-task\_helper path [\#28](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/28) ([cthorn42](https://github.com/cthorn42))
- pdksync - Update using 1.5.0 [\#27](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/27) ([HelenCampbell](https://github.com/HelenCampbell))
- Revert "pdksync - Update using 1.5.0" [\#25](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/25) ([david22swan](https://github.com/david22swan))
- pdksync - Update using 1.5.0 [\#24](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/24) ([HelenCampbell](https://github.com/HelenCampbell))
- \(MODULES-7153\) - Update release checks to run against ruby 2.4.1 and unmanage gitlabs-ci.yml [\#23](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/23) ([pmcmaw](https://github.com/pmcmaw))
- \(FM-6926\) Better checks when running install.bash [\#22](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/22) ([tphoney](https://github.com/tphoney))
- Inconsistent periods in task metadata descriptions [\#21](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/21) ([kenazk](https://github.com/kenazk))
- \(MODULES-6881\) - Removing duplicaton in .sync.yml [\#20](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/20) ([pmcmaw](https://github.com/pmcmaw))
- \(MODULES-6831\) Add Windows support  [\#18](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/18) ([Iristyle](https://github.com/Iristyle))
- \(feature\) add extension\_request custom\_attribute [\#17](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/17) ([tphoney](https://github.com/tphoney))
- Release Mergeback 0.2.0 [\#16](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/16) ([HelenCampbell](https://github.com/HelenCampbell))

## [0.2.0](https://github.com/puppetlabs/puppetlabs-bootstrap/tree/0.2.0) (2018-03-08)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-bootstrap/compare/0.1.1...0.2.0)

**Merged pull requests:**

- \(MODULES-6793\) - Release Prep 0.2.0 [\#15](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/15) ([pmcmaw](https://github.com/pmcmaw))
- \(MODULES-6468\) - PDK Convert [\#14](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/14) ([david22swan](https://github.com/david22swan))
- \(maint\) - modulesync [\#12](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/12) ([tphoney](https://github.com/tphoney))
- Test Cleanup [\#11](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/11) ([willmeek](https://github.com/willmeek))

## [0.1.1](https://github.com/puppetlabs/puppetlabs-bootstrap/tree/0.1.1) (2017-10-11)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-bootstrap/compare/0.1.0...0.1.1)

**Merged pull requests:**

- release prep 0.1.1 and fix bash script [\#10](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/10) ([tphoney](https://github.com/tphoney))

## [0.1.0](https://github.com/puppetlabs/puppetlabs-bootstrap/tree/0.1.0) (2017-10-09)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-bootstrap/compare/e3474bc145d2d4e32832a3518ef4e92bfaa317a4...0.1.0)

**Merged pull requests:**

- Update readme \(though differently from the rest\) [\#9](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/9) ([hunner](https://github.com/hunner))
- \(maint\) fix metadata [\#8](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/8) ([adreyer](https://github.com/adreyer))
- Update metadata.json [\#7](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/7) ([gregohardy](https://github.com/gregohardy))
- release prep 0.1.0 [\#6](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/6) ([tphoney](https://github.com/tphoney))
- FM-6481 fix project name [\#5](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/5) ([tphoney](https://github.com/tphoney))
- \(maint\) Typo in readme [\#4](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/4) ([hunner](https://github.com/hunner))
- Update readme [\#3](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/3) ([hunner](https://github.com/hunner))
- Cat cert content instead of checking fingerprint [\#2](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/2) ([hunner](https://github.com/hunner))
- Convert bootstrap from ruby to shell [\#1](https://github.com/puppetlabs/puppetlabs-bootstrap/pull/1) ([hunner](https://github.com/hunner))



\* *This Changelog was automatically generated by [github_changelog_generator](https://github.com/github-changelog-generator/github-changelog-generator)*
