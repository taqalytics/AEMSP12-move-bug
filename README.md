# AEMSP12-move-delete-bug
There is a known issue with move and delete functionality inAEM 6.5.12 but there is a workaround to fix this issue

Download the package in this repo and  follow the steps:
1. Go to /system/console/configMgr
2. Find Day CQ WCM Page Manager Factory
3. Check Page Subtree Activation Check checkbox and save it
4. Try moving or renaming the page.
This should work. Once you move the page, you could uncheck Page Subtree Activation Check and this need not be checked again for another move/rename operation.
![Screen Shot 2022-05-12 at 4 35 19 PM](https://user-images.githubusercontent.com/4964968/168163432-35fffb80-c822-44e8-afdd-ce6fc388e3aa.png)
