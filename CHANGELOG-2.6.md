## RubyInstaller-2.6.5-1 - 2019-10-02

### Changed
- Update to ruby-2.6.5, see [release notes](https://www.ruby-lang.org/en/news/2019/10/01/ruby-2-6-5-released/).
- Fix code signatures of installer executables. They were invalid at the 2.6.4-1 release.
- Fix automatic generation of irbrc. #158
- Update to OpenSSL-1.1.1d .


## RubyInstaller-2.6.4-1 - 2019-09-09

### Added
- Add support for scoop installer. #152

### Changed
- Update to ruby-2.6.4, see [release notes](https://www.ruby-lang.org/en/news/2019/08/28/ruby-2-6-4-released/).
- Ignore registry entries with invalid installer data when looking for MSYS2. #154


## RubyInstaller-2.6.3-1 - 2019-04-18

### Changed
- Update to ruby-2.6.3, see [release notes](https://www.ruby-lang.org/en/news/2019/04/17/ruby-2-6-3-released/).


## RubyInstaller-2.6.2-1 - 2019-04-13

### Changed
- Update to ruby-2.6.2, see [release notes](https://www.ruby-lang.org/en/news/2019/03/13/ruby-2-6-2-released/).
- Build with "-O3" instead of "-O2" optimization and update x64 compiler from gcc-8.2.1 to 8.3.0.
- Update of the SSL CA certificate list.


## RubyInstaller-2.6.1-1 - 2019-01-30

### Changed
- Update to ruby-2.6.1, see [release notes](https://www.ruby-lang.org/en/news/2019/01/30/ruby-2-6-1-released/).


## RubyInstaller-2.6.0-1 - 2019-01-03

### Added
- New tool `ridk use` to switch between installed ruby versions
- Add ruby-2.6.0, see [release notes](https://www.ruby-lang.org/en/news/2018/12/25/ruby-2-6-0-released/).
- Add `bundle` command, since bundler is now a bundled gem in ruby-2.6


### Changed
- Update of the SSL CA certificate list.
