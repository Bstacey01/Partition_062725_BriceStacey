In order to add a Hard Drive to an existing Virtual Machine in Hyper-V, you must follow these steps.

2. **Note**
3. When creating the drive, make sure that it is large enough to support the three partitions you wish to make.

**Adding a new Hard Drive**

1. Go to settings on the Virtual Machine you wish to add the new Hard Drive to.
2. Navigate to the IDE Controller settings, select "Hard Drive" and click Add.
 ![AddingNewHD](https://github.com/user-attachments/assets/67ce1f7e-0d13-49fc-904d-fb87a6129247)
4. Select "New Hard Drive" and follow the prompts to designate the location and size of the new Hard Drive you wish to add. Once that is done click "OK/Apply"
5. Repeat to add a Second Hard Drive.
7. Start your virtual Machine and Navigate to Disk Management, if the prompt does not appear to initialize the disk, right click on the disk and click initialize.

![Initializing Disk](https://github.com/user-attachments/assets/3aa7ea48-ef5f-4e57-94b4-7880edc7a362)



**Formatting the Disk**

1. Right click on the now initialized disk and click format. Set the prompts for the desired name, file type, size, etc.
  ![PartitioningDisk](https://github.com/user-attachments/assets/f440ba64-4ba1-453d-81bd-9726cabeab9d)
3. Repeat until all three partitions are created.
![ThreePartitions](https://github.com/user-attachments/assets/7ced92ac-f510-47c9-a7dc-2afd657cc144)


