# OpenFOAM Docker image

An OpenFOAM image which is mainly designed to execute openfoam jobs.

# Usage

Executing an OpenFOAM case from the current directory:
```bash
cd path/to/case/dir
docker run -it --rm -v $PWD:/data tefe/openfoamplus:v2006 ./Allrun   
```

Get a bash with all containg OpenFOAM commands:
```bash
docker run -it --rm -v $PWD:/data tefe/openfoamplus:v2006 bash    
```

**Notice**

You can change ```$PWD``` to any directory or environment variable that contains the OpenFOAM case files.

