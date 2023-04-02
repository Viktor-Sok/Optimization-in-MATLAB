1. Install YALMIPb (look official installiation instruction)
2. run yalmiptest to check dependencies
3. install dependencies if needed (suxh as optimizers SDPT3)
4. Install SDPT3 optimizer
Do not forget to set and save paths to installed libs
addpath(genpath([pwd filesep 'sdpt3']))
savepath