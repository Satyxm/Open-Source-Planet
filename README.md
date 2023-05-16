# Open-Source-Planet
![Black and Cream Minimal Retail Chic Electronics and Appliances Banner](https://github.com/Satyxm/Open-Source-Planet/assets/97077594/588a2387-03d3-443c-bc86-2f1adeea68b1)

Hey Folks! If you want to contribute to the Open-Source Projects but cannot do so because of getting overwhelmed by the large codebases of these projects. Then, You've landed on the perfect Open-Source Planet :) Get your Spaceship 🚀 ready and Start your Open-Source Journey!

## Fork the Repository

<img  alt="IMG_20230516_130918" width="500" src="https://github.com/Satyxm/Open-Source-Planet/assets/97077594/afdf862c-196f-490f-b474-eef9c1f592d1">

* Click on the Fork button and fork the repository

## Clone the Repository
* Go to the green button saying `Code` 

<img  alt="IMG_20230516_130824" width="500" src="https://github.com/Satyxm/Open-Source-Planet/assets/97077594/1ae7d902-70eb-45ae-9df7-b6d8ea1a7188">

* and click on it then, Copy the URL

<img  alt="IMG_20230516_1307544" width="500" src="https://github.com/Satyxm/Open-Source-Planet/assets/97077594/fe79b245-ff22-4393-b562-e2852ec124c1">

* Now Open the Git terminal and type the following:

```bash
git clone "paste the URL here"
```
* Cloning will begin

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
This will open Vim Editor for you and to start typing first click the `insert` button on your keyboard then, 
* Add this at the end of the addname.md file: 
```bash
Hi! I am <your_name> and my GitHub profile is [username](profile_link)
```

Here, Replace:
- `<your_name>` with your actual name
- `username` with your actual GitHub Username
- `profile_link` with your GitHub profile's link
* to save the changes and exit the file at the same time, press `esc` on your keyboard and then type `:wq` and hit enter! 
then,

## Add the changes
* Add the changes:
Currently, if you do 
```bash
git status
```

* Then, You might see: `modified: addname.txt` written in red

<img width="909" alt="Screenshot 2023-05-16 124856" src="https://github.com/Satyxm/Open-Source-Planet/assets/97077594/67dfc5f6-1e85-4781-b7dd-bc4f769679a1">

* So, do this:
```bash
git add addname.txt
```
This will add your changes
And, Now You will see: `modified: addname.txt` written in green

<img width="899" alt="Screenshot 2023-05-16 124921" src="https://github.com/Satyxm/Open-Source-Planet/assets/97077594/3a8ab5b9-af59-4afd-a53a-11cf808f2c34">

* This means that your changes were added

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

* To push your changes to your branch which you created
```bash
git push -u origin your_branch_name
```
here, replace `your_branch_name` with the name of your branch which you created

## Creating a PR
* Go to your repo, 
And, you will be able to see a `Compare & pull request` green button, Click on it
and then, 

## Submit PR
* Now submit your PR by changing the commit message to `Add <your_name>`
Here, Replace:
- `<your_name>` with your actual name

Once you've completed all of the above mentioned steps and created and submitted your PR then, I will be merging your PR to the main branch of this Project and you will recieve a notification via E-mail regarding updates on your PR!

Thanks for Contributing :)
