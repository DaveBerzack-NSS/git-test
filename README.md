
# Set up the Repository on Github

One person, navigate to github.com, log in and create a repository in the Nashville Software School organization. Be sure it is public, and check the checkbox to include a readme.md file

Click the create button, and it should set up a repository and navigate to the page, where you will see it has a readme file. That file is included as an overview of the project, and currently it just shows the project's name.

Each member of the group should visit the repository url, click on the green **CODE** button, then under SSH, copy the git URL.

Open your terminal and navigate to your workspace. On the command line, type: `git clone {pasted_git_url_goes_here}`

CD into the new folder and note that there's a readme.md file there. Now everyone is set up to collaborate with this repo.


# Make a Change 

One person, create a story.txt file in your project folder and paste the story text from the bottom of this guide into that file.

Type `git add .` in your terminal (while in the project folder) to have git track your latest changes

Type `git commit -m "started story"` to tag this revised version of the project and provide a brief description of changes.

Type `git push origin main`

view changes online
other people: pull from main. view changes locally


one person: make a branch. update one character's description.
add, commit and push the branch to origin. view that branch online
do a pull request
someone approve the pull request. see changes in main branch.
everyone pull latest to their local main

two people: pull latest from main, then make a branch. update one character's description. Then add, commit and push the branch to origin. 
one person do a pull request and merge it.
the other person do a pull request. There'll be a conflict. 
resolve it manually, approve the pull request.
everyone can pull main.




### Source text:
```
Once upon a time, in the mystical land of Eldoria, a great evil cast its shadow upon the realm. The people lived in fear as dark forces spread, threatening to plunge the entire world into eternal darkness. In response, a party of unlikely heroes gathered, each with their own unique skills and personalities.

Sir Cedric the Chivalrous, a knight of noble birth, clad in shining armor and wielding a sword that gleamed with the righteousness of his cause, led the group. His unwavering commitment to justice and the protection of the innocent made him the heart of the party.

By his side, the sage old wizard, Merlin the Wise, brought centuries of arcane knowledge. His long white beard flowed with the magic that coursed through his veins, and his staff crackled with the power of ancient spells. Merlin's wisdom guided the group through the darkest of times.

The trickster rogue, Seraphina Shadowheart, a master of stealth and cunning, moved silently in the shadows. With her dagger, she cut through obstacles, and with her quick wit, she outsmarted any foe. Seraphina's skills were essential for gathering information and infiltrating the enemy's lairs.

The party's bard, Lyra Melodious, added a touch of magic to their journey. With her enchanted voice and musical talents, she inspired her comrades and struck fear into the hearts of their enemies. Her words and melodies weaved tales of courage that echoed through the ages.

And then there was Alaric Gearspark, the clever artificer with a knack for tinkering. He invented ingenious gadgets and crafted magical artifacts to aid the party. Alaric's love for machinery and knowledge of arcane engineering made him an indispensable member of the team.

Together, this diverse group set forth on a perilous quest to find the legendary Crystal of Radiance, the only artifact capable of dispelling the encroaching darkness. Their journey took them through enchanted forests, treacherous mountains, and mysterious caverns.

Along the way, they encountered vile creatures and cunning adversaries, testing the strength of their fellowship. Sir Cedric's sword clashed with the minions of darkness, Merlin's spells illuminated the shadows, Seraphina's cunning outsmarted traps, Lyra's melodies inspired hope, and Alaric's gadgets provided ingenious solutions to unforeseen challenges.

As the party neared the heart of the evil's domain, they faced their greatest challenge yet – the Dark Sorcerer, a malevolent being who sought to use the power of the Crystal of Radiance for his own twisted purposes. A fierce battle ensued, with the heroes combining their strengths to overcome the sorcerer's dark magic.

In the end, it was Sir Cedric who delivered the final blow, his sword infused with the light of the crystal. The darkness retreated, and the land of Eldoria was saved. The party of heroes stood triumphant, their unity and diversity proving to be the key to victory.

The people of Eldoria celebrated the return of light and peace, and the heroes' names became legendary. Sir Cedric, Merlin, Seraphina, Lyra, and Alaric, unlikely companions brought together by destiny, had not only defeated the forces of darkness but had also forged bonds that would last a lifetime. And so, their adventures continued, as they set their sights on new horizons, ready to face whatever challenges awaited them in the magical realms of Eldoria.
```