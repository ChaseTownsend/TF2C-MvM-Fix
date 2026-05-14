## MvM Fix for Team Fortress 2: Classified

### Description 

Server plugin that restores full Mann vs Machine (MvM) functionality in Team Fortress 2 Classified.
Designed to fix critical gameplay bugs, synchronization issues, and broken mechanics that prevent MvM from working correctly on community servers.

***Currently Fixed***:

- Setup timer works propperly after wave begins
- Robots no longer spawn with unintended invulnerability
- Jarate and Mad Milk apply debuffs to robots as intended
- Prepare phase properly triggers after a failed wave
  

### TODO 

The following issues are still under investigation and will be addressed in upcoming releases:

- Round resets after all the players press f4: something caouses "Wave Failed" event and all the user upgrades & buildings disappear
- Refund button crashes the game:  Clicking "Refund" in the upgrade menu causes server crash. Currently the plugin disables this functionality, but it's not the best solution 
- Engineer building upgrades are broken:  After wave start, buildings cost $0 and can be instantly upgraded to level 3


### Screenshots


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/200cafaa-9621-43d8-906e-e21bce04ef10" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/2376b1dd-41dc-4175-8455-42e684837911" />
