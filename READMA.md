# vbps - An XBPS (X Binary Package System) package management helper for VoidLinux

***vbps*** is a simple front-end script for the x binary package system, initially designed as a helper tool for use with VoidLinux.

### Features
- Single front-end to the xbps utility suite
- Single front-end to the xtools utility suite  

***vbps*** is just an addon helper tool for XBPS/xtools to make your life easier. 

### Usage

*Example:*
```sh
$ vbps --help
vbps - backend for xbps/xtools collection of utilities
usage:
	vbps  [-h|--help] action  [options ...]

	-h|--help	- show this message and exit
	action		- appropriate action for xbps/xtools utility(if not set, default: query)
	options		- appropriate list of options for the selected xbps/xtools utility

	 Example:
		vbps -vRs query locate
		vbps install --repository /tmp/void locate
		vbps ilog
		vbps locate vim
```

### Installation
To install ***vbps*** use `git clone` and manually resolve the dependencies.

```sh
git clone https://github.com/mzujev/vbps
```

### Dependencies
***vbps*** requires BASH (Bourne Again SHell), which should be installed by default. You also will need put ***vbps*** into a place that is in your $PATH.

### Copyright
See [Copyright.txt](https://github.com/mzujev/vbps/blob/master/Copyright.txt) file for details
