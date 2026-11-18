              INITIAL SWITCH CONFIGURATION
       
  what was done in this lab;

1. i configured passwords on the switches to prevent unauthorized access.
2. i configured a 'hostname' for the switches
3. i configured a password on 'line console 0', so 'line console 0' is for physical access to the switches which the
    password will be prompted when an Authorized or unauthorized personnel is trying to gain access to the switch.
4. i also configured an enable password for security purpose but it's not encrypted, it's just being displayed in
    plain text just like the 'line console 0 password'.
5. 'enable secret', this particular command automatically encrypts the password that is being configured with it.
6. 'service password encryption', this particular command is used to automatically encrypt all the passwords that is 
   configured in a device.

 so for this lab is just a project that explains the configuration done. 
 