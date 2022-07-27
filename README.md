# Example: 


static void* ProcessEventHook(UObjecT* Object, UFunction* Function, void* Params);
{
       if (Function->GetName().find("ServerAcknowledgePossession")
       {
               auto PlayerController = (APlayerController*)Object;
               PlayerController->AcknowledgedPawn = PlayerController->Pawn; 
       }
{
