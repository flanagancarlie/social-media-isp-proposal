# Independent Project Proposal: Visualizing Social Media Data

## Data
The data I propose to visualize is from my [Social Media MQP](https://socialsight.glitch.me/index.html), and the dataset can be found [here](https://gist.githubusercontent.com/flanagancarlie/985c6e920016a7e0039d5105cc4fdb22/raw/9213b64f32e1ba5d076a96c9307a0be9de143f84/mqp_data.csv). This dataset is comprised of survey responses, where each respondant answered Likert scale questions on their recent social media use. Each question correlates to one of four scales: community building, self-expression, content discovery and user agency. Users optionally provided their age range, race, gender and sexuality.

Explanations of our scales from our MQP website are as follows: 


Community on social media measures our social tendencies to connect with others on the internet. If social media encourages empathy, talking with your friends, family, and loved ones, or enables discussion amongst a like-minded group, it encourages community. All social media will have some community, as they are all social, but some may have features that distract from connections or make it harder to stick with a community, and will score lower.

The Discovery scale relates to a user’s desire to see something new. Scrolling through social media for non-social reasons often means looking for something new to entertain, educate, or fascinate. We are interested to see how satisfied users are with the content they find and if content by small creators can be discovered by other audiences on the platform. For there to be new content for a user to discover, new creators need to be encouraged by the platform.

Agency is related to user safety and comfort. Sometimes users are not looking for anything new, but instead old comfortable memories or their favorite videos from a while ago. Although users may want something new, they might find something they don't like and need tools to avoid it in the future. Social media feeds are tailored to the user, so the user needs to have some control over the space they want to create. Blocking people can protect from harassment, while muting words or tags (like on Twitter and Tumblr) can help you avoid posts that make a user uncomfortable. Moderation teams are necessary to keep content safe, and community lead moderation can create rules to fit a communities custom needs. We hope to measure how customizable, comfortable, and safe a platform is using this scale.

The Self scale relates to how social media enables self-presentation, self-exploration, and the ego. Profile customization options can allow many to create authentic or inauthentic personas. Posts are often linked with virtual “achievements” such as likes or re-shares that can affect the ego. This scale aims to measure how a platform encourages identity presentation or getting lost in the crowd.

## Prototypes
![image](https://github.com/flanagancarlie/social-media-isp-proposal/blob/main/mqp_prototype.png?raw=true)

The first prototype created was during prototyping of my MQP. We envisioned that for each scale we defined, we would plot each social media as well as a toggle of our demographic options.

![image](https://github.com/flanagancarlie/social-media-isp-proposal/blob/main/mqp_viz.png?raw=true)

The next prototype created is on our [MQP website](https://socialsight.glitch.me/). This scatterplot counters community and self, and discovery and agency. During our MQP we were unable to integrate demographic data. Additionally, this obfuscates the actual values by contrasting the scales.

## Questions & Tasks
I want to visualize the perception of twelve social media with relation to use demographics. The demographics include age, race, gender and whether the user identifies as LGBT. The twelve social media are BeReal, Facebook, Instagram, LinkedIn, Reddit, Snapchat, Tumblr, Twitch, Twitter, YouTube and 4chan.
* How well do social media encourage or inhibit community building, self-expression, content discovery and user agency?
* How do different demographics view social media as a whole?
* Does social media encourage some groups more than others? 
* Which group does each social media encourage post?

## Sketches
![image](https://github.com/flanagancarlie/social-media-isp-proposal/blob/main/viz_sketches.png?raw=true)

View 1 displays a bubble chart, which will show all social media. The size of the bubble will correspond to the Likert scale value, where a Strongly Inhibits is a 1, and a 7 will correspond to Strongly Encourages. A dropdown will allow the user to change the scale being displayed.
View 2 displays a radar pie chart. The pie chart will be divided into quadrants, with each quadrant representing a scale. Clicking on a quadrant's label will expand it to the entire circle to make it easier to view.
For both views, a checkbox will be displayed next to the view to allow the user to pick and choose demographics. On default, all boxes will be checked and all data will be displayed.

## Milestones
Week 1 - Load and modify data. Pseudo-viz of view 1, including HTML dropdowns and checkboxes. 

Week 2 - Pseudo-viz of view 2, including HTML dropdowns. 

Week 3 - First visual of view 1.

Week 4 - Iterate on view 1. Mid-point meeting or demo video. 

Week 5 - First visual of view 2.

Week 6 - Expand view 2 quadrants.

Week 7 - Add interactions and tooltips. Finalize views with color. 

Week 8 - Finalize submission, wrap-up meeting or demo video.


