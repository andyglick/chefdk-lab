chefdk-lab
==========

I've been working with chef a fair amount at my day job, where we use ruby-1.9.3 and chef-10.32.

I've wanted to move up to chef 11 and to be able to use chefdk.

One of the reasons that I want to move up is because I am seeing a whole raft of ruby gem issues with the
various chef versions that I have been trying out.

* In particular, a chef gem that I would like to work with, 'spiceweasel', is fairly finicky, and fails for colorful 
    reasons under 1.9.3. Of course it fails for different colorful reasons with chefdk, but I expect to get some support 
    if I end up needing it if I use the current version.  

* In addition, a workaround that we use on my work project sets the versions of all the chef cookbooks to the jenkins
    build number associated with system builds so it is nearly impossible to use berkshelf, and I am interested in
    trying out the application cookbook workflow.

So there are a number of reasons why I want to start using chefdk 0.2.0.

Hope to have some possibly valuable things to report in the not too distant future.

Happy cooking!

