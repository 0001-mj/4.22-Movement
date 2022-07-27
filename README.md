# Example: 


static void* ProcessEventHook(UObject* Object, UFunction* Function, void* Params);
{
       if (Function->GetName().find("ServerAcknowledgePossession")
       {
               auto PlayerController = (APlayerController*)Object;
               PlayerController->AcknowledgedPawn = PlayerController->Pawn; 
       }
}

# I Care Nothing About How It Looks Just Take The Code
and yes its my fix.
