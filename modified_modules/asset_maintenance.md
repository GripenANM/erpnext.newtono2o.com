# Asset Maintenance Schedule Flow

For Asset Maintenance, follow: https://docs.erpnext.com/docs/user/manual/en/asset-maintenance
To create an asset: https://docs.erpnext.com/docs/user/manual/en/asset-asset
To create a company: https://docs.erpnext.com/docs/user/manual/en/company-setup


![image](https://github.com/user-attachments/assets/5936ede1-0808-485e-8aa1-85540aad3302)
![image](https://github.com/user-attachments/assets/1831800f-51c9-4e58-9a59-daf5cf591ab7)
![image](https://github.com/user-attachments/assets/416943dd-4fb7-4fb7-9802-7abd28405e83)
![image](https://github.com/user-attachments/assets/98aebd10-64fb-4309-935b-1494837d0f56)



- 4.1: The asset that you want to create scheduled maintenance
- 4.2: The owner company of the assset (if the asset owner here is different than the one in the asset item info, than no item will show up in the asset name field 4.1)
- 4.4: The asset maintenance team that the maintenance will be assigned to, see https://docs.erpnext.com/docs/user/manual/en/asset-maintenance-team for more information
- 4.4: task items that is planned
- 4.5: click to fill in more details

once the schedule is created, the emeployee/person selected will have the assigned take appear on their todo and calender. Note that the next due date will automatically update once the planned log is submited


# Asset Maintenance Log Flow
once the schedule is created, based on the period of manintenace, the Maintenance Log will be gernerated. The log will have 3 state: Draft, pending for approval, planned, completed. maintenance team user will double check the task detail and add a material request where they can request a list of tools and material that is required to complete the job.
once maintence team user if done, they can submit the task log for approval where the maintenance tema managger can reject of approve it. once approved, the task will be now marked as planned and maintenance user can complete the end of job report once they are done and change the maintenance status to the status that they decide.
> Please note that in the maintenance schedule record view, the status will be based on maintenace status and not the status of the log itself and the status will all be planned regardless of the approval situation unless maintenace status is changed. Once the log is submited, not further change can be done.

![image](https://github.com/user-attachments/assets/75dda559-9a32-435e-9706-e06e89288cb0)
![image](https://github.com/user-attachments/assets/4ba1d193-c6de-41e2-9332-f9d6fac70ff4)
![image](https://github.com/user-attachments/assets/fc88be19-1446-4c77-85f8-16f74f096948)



more reading:
- https://docs.erpnext.com/docs/user/manual/en/asset-maintenance-log
- https://docs.erpnext.com/docs/user/manual/en/material-request


