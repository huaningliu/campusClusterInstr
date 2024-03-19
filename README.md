# UIUC Campus Cluster Instruction
1. To begin with, you will need to apply the access of central cluster via the link: https://campuscluster.illinois.edu/new_forms/user_form.php. Select the __primary queue__ as __STAT__ - it seems Prof. Ruoqing Zhu is the manager and you'll get notice of approval via his email soon.
2. Preparatory: The software combo I chose is Ubuntu Windows (Linux-based) for submitting jobs, and Bitverse SSH Client for uploading folders/files to the cloud.
3. Log onto the cloud via Bitverse SSH Client first
4. Job submission
   - In Ubuntu, run command `ssh -X -l <username> cc-login.campuscluster.illinois.edu` to log into the cluster, password is needed then.
   - At this time, you'll see that neither `conda` nor `python` works, so we'll need to first "import" conda, then create an conda environment that adapts our codes.
     (1). run `module load anaconda/3`
     (2). 
