## 1.1.0 - 2018/09/30
### Added
* PowerShell Core support.
* Update-AppveyorBuild -Version.
### Changes
* Pester from PowerShellGallery.
### Fixed
* Compress-Archive replaced with IO.Compression.ZipFile as Compress-Archive don't work on opened files.
* Fix text files encoding.
* AppVeyor Git CRLF encoding fix.

## 1.0.4 - 2018/09/29
### Changes
* Module rename.
* AppVeyor image: Visual Studio 2017.
### Added
* Deploy.ps1 -PowerShellGallery -AppVeyorZip.
* VSCode launch.json PowerShell Pester Tests.
* AppVeyor Get-EnvironmentInfo
### Fixed
* Fixed module name

## 1.0.3 - 2017/10/05
### Added
* PowerShell module structure
* Rearranged files
* Add .psd1 file
* Test-Q Added
### Fixed
* Fixed module name