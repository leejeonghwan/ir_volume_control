# ir_volume_control

/* 
- I'm controlling an audio amp with an Apple remote, and I wanted to make a rotary volume to complement the Apple remote.
- Simple solution by connecting rotary encoder and IR transmission module.
- Reading the rotation direction from the rotary encoder and sending the signal to the IR transmitting module.
- I tried to merge the code published on github (the old code did not work as the library was updated)
- I checked the Apple remote control transmission code (I installed the IR receiving module first and read the button value)


- The signal values of Apple's remote control are as follows.

Left button: 77E190BF.
Right button: 77E160BF.
Upper button: 77E150BF.
Down button: 77E130BF.
Middle button: 77E13ABF.
Menu button: 77E1C0BF.
Play button: 77E1FABF.



https://www.leejeonghwan.com/5859

*/
