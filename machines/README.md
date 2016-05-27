# CFOffline
## machines
This directory will hold the different 'machines' in this experiment.

##Details
This system is designed to model communications between a master centralized CF instance in a Data Center or the Cloud.  This is being referenced as the *server*.  There will be one or more client machines, also running some version of CF that are out in the field.  These will be referred to as *mobile*.

### server
This is a vagrant VM to assist in mirroring the 'remote' nature it needs to fulfill.

### mobile
This is a commandbox powered local instance of the same code base.  It should communicate with the *server* whenever possible, but fail back to a local index that can later be synced up.
