# cpu-ram-storage-display--dojo-derby

These scripts create a simple panel yuo can add to your projects to see what the current rsource utilization of your vehicle is (CPU/RAM/Storage)

The .py script has to be running for this to work.  The best idea is to have it run when the vehicle boots (add to the rc.local file)

The panel is the .php script which can added to otehr pages as an iFrame.  The script auto refreshes every 5 seconds to give current, but delayed readings.
(Note: I'll probably rewrite this into Javascript, but this proves the point and functions)

<img width="722" alt="Screen Shot 2022-05-06 at 10 30 50 AM" src="https://user-images.githubusercontent.com/60199254/167153941-efa98f2f-6bb4-430a-a498-3912eb82ad9d.png">
