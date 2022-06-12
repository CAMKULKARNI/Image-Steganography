# Image-Steganography
A python program that hides a message in an image.
The message is first converted to its ASCII equivalent and then embedded into random locations in the image of size H x W x C. Those positions are again encoded into a key. Both the key and the new image are then passed to the relevenat party and they can extract the message from the image using the key. Compression and Encryption of the key are still under progress.
