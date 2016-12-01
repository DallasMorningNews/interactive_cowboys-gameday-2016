** A note to begin:** Please read all the words (Layne). There's some important stuff in here and I can't get it all at the top.

## THE CONTENT AND WHAT NEEDS TO BE UPDATED

All the content can be found in Newsgate. They usually build these out Thursday night, but leave the content on the bank page. To find it in Newsgate, click "Story Folders" in the bottom left hand corner, then the small arrow icon in the bottom right hand corner. Change "Planning Date" from and to fields to "Bank", then pick Sports as the Desk. Find the files that are for the current week.

### Lead image

The lead image is a duotone blue, but you don't need to worry about that. Computers are magical and this will be done for you. Just make sure you start with a photo that's cropped to 3000 x 1750.

This image is usually some tight shot of a celebration or dejection moment from the previous game. Helps if the subject of the photo is not straight up centered, as they'll have type on their face. Literally.

### Game head

![story head](/build/static/images/github/storyhead.png)

In the logo block, the logos need to be updated. Visiting team is first. The alt text of the logo image tag is the mascot name. The logo sigs already exist. Cowboys is called "_cowSig.jpg", the others are in the format of "_mascotSig.jpg". For example: "_bengalsSig.jpg".

The h1 tag is the same as the logos, visiting mascot at home mascot.

**Important:** Don't forget to update the week number in the h2 tag. This is used by the back end to create the proper routes for the prediction table. If it's a playoff game, the content for seasonWeek is "Wildcard," "Divisional Round," "Conference Championship," and "Super Bowl."

### Predicitions

These are pretty straight forward. Copy paste. Sometimes, the predictors will write their prediction as multiple paragraphs. Homie don't play that. One expert, one paragraph.

Bob Sturm's matchup goes at the end of the Spotlight section.

### User Picks

You shouldn't have to touch anything here. The backend handles replacing placeholder type with the appropriate mascot/team names.

### Matchups

In each of the matchup areas, you'll need to change the image src to the sig of the team that has the edge in that category, along with the alt text of that image to the appropriate mascot name. Sometimes there will be a tie, in which case, a special split sig will need to be created. I'll try to create these in advance of week's I'll be out, so check in the images file. Usually they're called something like "_bengalsSplitSig.jpg." If you are missing or need to create one, the logosheet is kept in the assets file.

![matchups](/build/static/images/github/matchup.png)

Also, make sure to change the opposing team name in the third and fourth matchups: "When the XXX run the ball," "When the XXX pass the ball."

### Spotlight

![spotlight](/build/static/images/github/spotlight.png)

It's best to find an image of the spotlight person (so help me God when Sturm picks an inanimate object for this) that is roughly square, with the subjet on one side or the other, not centered. There's a "leftside" class on the div that holds the spotlight content. If the subject of the image is on the left, simply remove this class.

Bold the name the first time it's mentioned in the spotlight content. The last paragraph of the spotlight is Sturm's spotlight.


## METADATA

You have to fill the metadata in by hand. I know, don't kill me. This is all pretty standard procedure. Anytime the author name is asked for, it's just "sportsday." Unique id numbers can be gathered up by using the metatagger, or just type in some random 12 digit number.

## FILE NAMES

Since all the images are going in one image folder for the entire season, you could imagine that we'll probably be using some pictures of the same player. Since that's the case, try to add in a week prefix/suffix to your image file names. Example: elliot_week6.jpg
