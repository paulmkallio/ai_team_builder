<!-- This markdown describies the final project by Paul Kallio for the Building of AI course, 
that is created by Reaktor Innovations and University of Helsinki. -->

# AI Team Builder

## Summary

AI project to create application, that is capable of select the team, that is good enough to execute the given task.

## Background

Most companies that work in teams have various resources with key persons, inexperienced workers and bag of professionals with different technical knowledge. Also the tasks are differenet and competence needed to manage them variates. For example consultant company has few lead designers, some administrators and many programmers UI and server side. Key players and other sparse resources are used only, when needed and workload got to speared evenly to the others. This same aplies to any business area usings teams like construction companies and also team sports. Football team can give rest for overloaded players and make better use of reserve players as well. In many European leagues this problem is encountered almost weekly by most of the teams. Clubs are fighting for the money received from the league as well as from attendances, advertisers and media time.

## How is it used?

This solution is needed expecially, when the next task is not critical based on the situation in the league is of great importance. Team management can use this as an aid, when they plan the next game. Approximation of the quality of the palyer can be used as a weight of position in the pitch. Vulnerabilities of the team in some areas can be used as an bias in calculation.

Images will make your README look nice!
Once you upload an image to your repository, you can link link to it like this (replace the URL with file path, if you've uploaded an image to Github.)
![Cat](https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg)

If you need to resize images, you have to use an HTML tag, like this:
<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg" width="300">

This is how you create code examples:
```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]

   totPop = sum(pop)
   totFish = sum(fishers)

   # write your solution here

   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%

main()
```


## Data sources and AI methods
Data used is taken from
If you need to use links, here's an example:
[Twitter API](https://developer.twitter.com/en/docs)

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

## Challenges

Of course the quality of the players are dependant of the money the club has, so output of the team has always limitations.

## What next?

Next step is to create models how different coaches are working, and to predict what different tactics they might use against us.


## Acknowledgments

Sources of inspiration:
https://buildingai.elementsofai.com/ by Reaktor Innovations and University of Helsinki.

* do not use code, images, data etc. from others without permission
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used
  <br>For example: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
* etc
