The following bot is in charge of update work items provided by ACME1 platform, generate a SHA Code and update the work item.

Consider:
- The bot needs the work items already in the ACME Portal to perform a correct task.
- The process was created in the UiPath REFramework, because I do not have access to the E5 Framework, I asked for it by replaying the "Welcome Onboard Luis" email on October 12 but I got no answer.
- The process has the dispatcher (Located in the InitAllApplications module) and the performer (in the Process module), the ideal is to separate them, but just to do it in one single frame I decided to do it this way.
- The bot has a Records File if you want to re-process a WorkItem the records file must not contain that work item.

Regards.

I'm pending for any comment

Luis Efrén García Sánchez