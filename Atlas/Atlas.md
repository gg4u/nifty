# Atlas Log

Atlas log for **Test 0** 
Creation of demo to present knowledge maps for learning and discovery created / edited by users.

Maps are collected in the Nifty.Works' Atlas [1].

[1] Nifty.works platform dedicated to factual knowledge, as per August 2018.
 
# Roadmap definition  [August 2018]

- [x] project writing
  - definition of object, action, results

- [x] project management
  - production of deliverables and documentation


# Discovery engine [August 2018]

## Scripting to import and analyse maps

- [x] creation of automation scripts to generate maps out of selected topics
  - test 4 algorithms to extract knowledge networks
  - exporting files in batch based on parameters
  - merger of networks into a unique map 
  - filters to discard selected maps in merger
  - visualisation of results

- [x] test manual update of knowledge base, with new entities whose article exist in English Wikipedia (syncing UX)

- [ ] creation of scripts to format knowledge maps as per api/share, with *manually selected topics*
- [ ] creation of scripts to format custom knowledge maps as per api/share, *with manually selected topics AND links* from tab space format
- [x]creation of scripts to format custom knowledge maps as per api/share, *with manually selected topics AND links* from excel sheet 

### Examples for formatting manually created maps

Example of a Map, Format Excel


From_node | To_Node | Weight (Scale Anchoring, 0.1 - 1.0)
--------- | ------- | -----------------------------------
Science | Karl Popper | 0.4
Karl Popper | Democracy | 0.6
Democracy | Social Influence | 0.8
Social Influence | Concentration of Media Ownernewship | 0.8
Social Influence | Network Effect | 0.5
Network Effect | e-Democracy | 0.7
Democracy | e-Democracy | 0.8
Network Effect | Physics | 0.8
Network Effect | Quantitative Research | 0.7
Quantitative Research | Science | 0.7

Example of a Map, Format Tab separated

```
Science
  Karl Popper
    Democracy
       Social Influence
          Concentration of Media Ownernewship
          Network Effect
             e-Democracy
             Physics
             Quantitative Research
                Science
       e-Democracy
```



## Extending knowledge discovery platforms APIs 

- [x] creation of API/Atlas to expose collection of knowledge maps
- [x] creation of API/news to expose news associated to a topic


# User Experience for web platform [September 2018]

## Designing UX and interaction 

- [x] creation of Atlas front-end to expose collection of knowledge maps (pinterest look-and-feel version)
- [x] definition of UX to display custom content associated to a map
- [x] definition of UX to display custom content associated to a topic

## Extending knowledge discovery maps logic to support external content
- [x] integration of news content for selected topic 
- [x] integration of video content for current map
- [ ] integration of custom content for selected topic 

## Designing mockup layout
- [x] definition of UI of Atlas, complying with material design principles

## Extending knowledge discovery platforms layout
- [x] adding contextual menu for maps
- [x] adapting scrolling and appearence of menu for mobile and web
- [x] adding news content UI for selected topic
- [x] adding video content UI for current map
- [x] mockup for additional third party content for current topic

- [x] improving readability of maps
  - responsive formatting of label size on zooming ratio
  - responsive formatting of label display on zooming ratio
  - adjusting appearance of image elements on current node
  - adjusting appearance of label element on current node
  - introducing color background for labels
  - introducing highlight on neighborhood of current parent
  - updating rendering logic in function of minimising layout invalidation (CSS3 sheets, SVG)

- [x] improving interactions with maps
  - adjusting layouting of maps to reduce visual drag (background layout adjusting) 

- [x] performance tests for responsive layout 
  - improving events handling ( async visual adjustment of graph elements)
  - reduction of layout invalidation in DOM tree 


