# libCTF
A little toy tool to read mrc file and ctffind output file to do ctf corretion.  

Dependency:
+ numpy
+ matplotlib
+ mrcfile
+ tqdm


Run  
`python CTFcorrect.py -i "mrcfile_path" --workspace "ctffind out path (also save path)" -- filename "ctffind out file name" -p "pixel size"`
