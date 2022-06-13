Create deployment ~ prefect deployment create homework.py

Clear database ~ prefect orion database reset -y

Preview all auto-scheduled runs for the next 6 months, 
i.e. 24 hours per day for 30 days for 6 months (24 * 30 * 6) ~
prefect work-queue preview aa5d72de-b3b2-45b5-a6e4-d6339e2b54a0 -h 4320

Start agent to look for work from work queue <ID>
~ 
prefect agent start aa5d72de-b3b2-45b5-a6e4-d6339e2b54a0

List all work queues ~ prefect work-queue ls
