BigInteger
==========

Instructions
------------
    
Just drop the `BigInt.{h,m}` files into your project.

Create a drawer instance and assign a scroll view that should be scrolled by the drawer:
    
    // Create Big Int Hex Value
    BigInt * bigIntHexValue = [[BigInt alloc] initWithString:@"aa" andRadix:16];
    
    // Create Big Int Decimal
    BigInt * bigIntHexValue = [[BigInt alloc] initWithString:@"9823864523645672345723645" andRadix:10];
    
