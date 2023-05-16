# Open-Source-Planet
Hey Folks! If you want to contribute to the Open-Source Projects but cannot do so because of getting overwhelmed by the large codebases of these projects. Then, You've landed on the perfect Open-Source Planet :) Get your Spaceship 🚀 ready and Start your Open-Source Journey!

## Fork the Repository
Click on the Fork button and fork the repository

## Clone the Repository
Go to the green button saying `Code` and click on it then, Copy the URL
```bash
git clone "paste the URL here"
```
Cloning will begin

## Change Directory
Once, the repo is cloned, then:
```bash
cd Open-Source-Planet
```
then,
## Create a Branch
```bash
git switch -c "name_of_your_branch"
```
instead of `name_of_your_branch` write the name of the branch whatever you want
## Make Changes to the File
```bash
vi addname.txt
```
Add this at the end of the addname.txt file: 
```bash
Hi! I am <your_name> and my GitHub profile is [username](profile_link)
```

Here, Replace:
- `<your_name>` with your actual name
- `username` with your actual GitHub Username
- `profile_link` with your GitHub profile's link
to save the changes and exit the file at the same time, press `esc` on your keyboard and then type `:wq` and hit enter! 
then,

## Add the changes
Add the changes:
Currently, if you do 
```bash
git status
```
Then, You might see: `modified: addname.txt` written in red
So, do this:
```bash
git add addname.txt
```
This will add your changes
And, Now You will see: `modified: addname.txt` written in green
This means that your changes were added

## Commit your changes locally

To Commit your changes locally:
```bash
git commit -m "Add <your-name>"
```
Here, Replace:
- `<your_name>` with your actual name

Then, After commiting these changes locally, do `git status` again:
```bash
git status
```
Now, You'll be able to see that your branch is ahead of origin/main by 1 commit

## Push your changes to your branch

To push your changes to your branch which you created
```bash
git push -u origin your_branch_name
```
here, replace `your_branch_name` with the name of your branch which you created

## Creating a PR
Go to your repo, 
And, you will be able to see a `Compare & pull request` green button, Click on it
and then, 

## Submit PR
Now submit your PR by changing the commit message to `Add <your_name>`
Here, Replace:
- `<your_name>` with your actual name

Once you've completed all of the above mentioned steps and created and sub,itted your PR then, I will be merging your PR to the main branch of this Project and you will recieve a notification via E-mail regarding updates on your PR!

Thanks for Contributing :)
