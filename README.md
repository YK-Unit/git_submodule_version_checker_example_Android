# git_submodule_version_checker_example_Android
A example to show how an Android project install git_submodule_version_checker tool,  and as a test demo for you.



## how to test git_submodule_version_checker

1. 进入供测试的submodule：`cd path/to/git_submodule_version_checker_example_Android/submodules/DemoLibrary`

2. 切换到主分支之前的某个commit，如`tag-1.0.0`指向的一个commit：`git checkout 1.0.0`

3. 运行example工程，将会看到`git_submodule_version_checker`的报错信息：

   ```shell
   Execution failed for task ':app:check_git_submodule_version'.
   > This main repo has bad submodules, please run 'git submodule update --init --recursive' to fix it.
   ```

   

