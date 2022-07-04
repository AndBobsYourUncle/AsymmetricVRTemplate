# AsymmetricVRTemplate

Developed with Unreal Engine 5

This is the default VR template from Unreal, set up with a migrated third person character from the default third person Unreal template. It also has a new custom game mode, which works with a server/client setup to automatically create and possess new player pawns so that the VR player gets the VR pawn, and the reset of the players get a 3rd person pawn.

The VR player runs as the server, and the third person character runs as the client. All VR controller input then needs to be replicated, and other various actors in game need replication enabled.
