# Commits and Draft pull requests
## Case

I created a [pull request](https://github.com/IBM/platform-services-java-sdk/pull/85) and made it draft. Honestly, I didn't have a slight idea what draft PR are for, and I haven't read the documentation. It didn't seemed a big thing. A few days and push later I realized a few commits are missing from the aforementioned PR. Furthermore it showed that there is a conflict. The conflict cannot be resolved due to that the UI cannot handle it. I can't resolve the conflict on my machine because the code is already pushed. So the situation is that I had a state on my machine which wasn't mirrored by Github due to that I couldn't resolve the conflict on origin. I assume the missing commits were held back due to this conflict. If I remember correctly I pushed multiple times during the days without any conflict. So part of the commits should be displayed on the PR.

Teh funny thing is that the branch had the commits, only the PR had problems with it. Did I hit a temporary issue? Who knows... But, the fact is that I know more about git and github.

The result is that I tried to recreate the case, I failed. Everything works fine.
The other result is that I played a bith with Draft pull requests, according to the steps below. It works fine, moreover, the whole Draft concept does what its name suggest. You can pile up your stuff in a draft PR without pinging folks and once it is ok, you can ask review or you can drop it.

The relevant documentation from [Github](https://github.blog/2019-02-14-introducing-draft-pull-requests/)

Since I couldn't resolve the conflict I closed the mentioned PR without merge, and I created a new one.

## Step

- Create a feature branch
- add a few commits
- push these commits to Github
- create a pull request (at this stage it is not draft yet)
- make a few commits and push them
- check whether the new commits are displayed in the pull request (they shoudl be there)
- go to the pull request and make it to Draft
- make a few commits to the feature branch
- push the commits to Github
- check whether the commits are displayed in the pull request
- make a few commits more and push them
- check whether the commits are displayed in the pull request
- make the pull request "Ready for Review"
- check what commits are displayed in the pull request
