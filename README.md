# ROS-Warehouse-Robot
ROS based Volta robot equipped with Navigation and PBVS capabilities


Instructions for running the project: 

	1. Launching Simulation + robot spawner : (terminal tab-1)

			` roslaunch volta_simulation warehouse_complete.launch `


	2. Launching the navigation node: (terminal tab-2) 

			` roslaunch volta_navigation navigation.launch `
			

	3. Launching the send_goals and PBVS nodes: (terminal tab-3)

			` roslaunch vision_align align_nav.launch `


https://user-images.githubusercontent.com/76431286/180832913-282d9a6e-6250-4d6d-858d-f8581731d151.mp4

