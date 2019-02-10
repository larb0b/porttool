# porttool

porttool is a simple script to upload or remove a port to/from [ports.sgi.sh](http://ports.sgi.sh).

### Usage

##### To timestamp a package:
porttool stamp [name]  
Ex. porttool stamp emacs-26.1.tardist

##### To upload or remove a package:
porttool [up/rm] [category] [name] [package]  
Ex.: porttool up editors emacs emacs-26.1-201901171502.tardist
