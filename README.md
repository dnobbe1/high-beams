# high-beams
An indie folk production project

This is an attempt to use git as a collaboration tool for Reaper projects

# Caveats
Reaper projects are very large. To prevent excessively large load times, it is important that we keep the number of branches to a minimum. 
We probably shouldn't need anything more than just `master`. Feel free to create 1-2 more branches if you'd like, but just keep in mind
it's going to be very slow to pull down changes from multiple branches.

# Setup
If you don't already have git and you're on windows just google git bash and install that. 
Then navigate to where you want your reaper projects to go and run
`git clone https://github.com/dnobbe1/high-beams.git`
That should do it.

When you're done making changes just run 
`git add .`
`git commit -a -m "<COMMIT_MESSAGE_HERE>"`
`git push origin master`
