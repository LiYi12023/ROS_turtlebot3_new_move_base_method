# ROS_turtlebot3_new_move_base_method
The new move base method for turtlebot3. 

## 事前作業：  
**1.將以下資料複製到turtlebot3_navigation/param/ 中**
  * nb1_dummy.yaml
  * nb1_costmap_common_params.yaml
  * nb1_local_costmap_params.yaml
  * nb1_global_costmap_params.yaml
  * nb1_dwa_local_planner_params.yaml
  * nb1_move_base_params.yaml
  * nb1_global_planner_params.yaml
  * nb1_navfn_global_planner_params.yaml
  * nb1_lidar_costmap_params.yaml
  
**2.將以下資料複製到turtlebot3_navigation/launch中**
  * turtlebot3_navigation_simulation.launch
  
**3.在turlteobt3_navigation/launch中建立一個includes資料夾，並將以下資料複製進去**
  * nb1_move_base.launch.xml
  
## 執行:  
使用時，直接launch turtelbot3_navigation turtlebot3_navigation_simulation 既可。
