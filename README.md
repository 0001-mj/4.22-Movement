# Example: 


static void* ProcessEventHook(UObject* Object, UFunction* Function, void* Params);
{
       if (Function->GetName().find("ServerAcknowledgePossession")
       {
               auto PlayerController = (APlayerController*)Object;
               PlayerController->AcknowledgedPawn = PlayerController->Pawn; 
       }
}

static APlayerController* SpawnPlayActor(UWorld*, UNetConnection* Connection, ENetRole RemoteRole, FURL& InURL, void* UniqueId, FString& Error, uint8_t InNetPlayerIndex)
{
       Pawn->bReplicateMovement = true;
       Pawn->OnRep_ReplicateMovent();
       Pawn->OnRep_ReplicatedMovement();
       Pawn->OnRep_ReplicatedBasedMovement(); i think im too lazy to check the func name
}

# I Care Nothing About How It Looks Just Take The Code
and yes its my fix.
