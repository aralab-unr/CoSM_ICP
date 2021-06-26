# CoSM_ICP
<img src="gif_1.gif" width="1380" height="800"/>****

The last row last column in the figure above shows the CoSM ICP results.

Welcome to CoSM_ICP Algorithm.
Few Notes before proceeding:
1) We don't use the installed pcl library in the system. We have our own modified PCL library (containing our correntropy Matrix implementation) present in the external_libraries folder. 
2) the src/ folder contains 2 main files: CoSM_ICP_demo_Viewer.cpp and CoSM_Results_Collection.cpp.
3) CoSM_ICP_demo_Viewer.cpp is the main file which allows you to compare different methods present in the PCL library. CoSM_Results_Collection.cpp simply collects the same(transformation and RMSE's) in a file.
4) test_files contains our original implementation from scratch. We originally worked in this implementation and it's from libicp from Andreas Gieger.

Steps to Run the Program.
  Open terminal and run setup.sh in the directory. 
  a figure window like the one shown above pops up.
  
  
