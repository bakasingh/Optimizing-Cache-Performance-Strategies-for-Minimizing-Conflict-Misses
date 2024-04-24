How to run the program 
 
1> Clone the repository: 
     git clone  :https://github.com/bakasingh/Optimizing-Cache-Performance-Strategies-for-Minimizing-Conflict-Misses
 
2> Open in UNIX based system and navigate to the directory containing the codebase. 
 
3>For granting permissions, run for both build_champsim.sh and run_champsim.sh 


    chmod +x script.sh                             example :     chmod +x build_champsim.sh 
    sed -i -e 's/\r$/\n/' script.sh                example:      sed -i -e 's/\r$/\n/' build_champsim.sh 
 
4>Build the ChampSim simulator: 

    ./build_champsim.sh bimodal no no no no srrip 1 
 
5> Run the ChampSim simulator with the desired configuration: 

     ./run_champsim.sh bimodal-no-no-no-no-srrip-1core 1 10 <trace_file_name> 


Replace <trace_file_name> with the name of the trace file you want to simulate. 
 
You can also replace 10 by how many number of instruction you want to run the code for. 
 
6> You can check the new file made in the same folder by name of trace and number of instructions. 


Trances  Link: https://drive.google.com/drive/folders/1lxbyLJ30uXWaxK7uy_84BHyr5WjlC8Qu
