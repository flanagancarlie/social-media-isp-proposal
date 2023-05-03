# Independent Study: Visualizing Social Media Data

## Data
The data I have visualized is from my [Social Media MQP](https://socialsight.glitch.me/index.html), and the dataset can be found [here](https://gist.githubusercontent.com/flanagancarlie/985c6e920016a7e0039d5105cc4fdb22/raw/9213b64f32e1ba5d076a96c9307a0be9de143f84/mqp_data.csv). This dataset is comprised of survey responses, where each respondant answered Likert scale questions on their recent social media use. Each question correlates to one of four scales: community building, self-expression, content discovery and user agency. Users optionally provided their age range, race, gender and sexual orientation.

Explanations of our scales from our MQP website are as follows: 
>Community on social media measures our social tendencies to connect with others on the internet. If social media encourages empathy, talking with your friends, family, and loved ones, or enables discussion amongst a like-minded group, it encourages community. All social media will have some community, as they are all social, but some may have features that distract from connections or make it harder to stick with a community, and will score lower.

>Discovery relates to a user’s desire to see something new. Scrolling through social media for non-social reasons often means looking for something new to entertain, educate, or fascinate. We are interested to see how satisfied users are with the content they find and if content by small creators can be discovered by other audiences on the platform. For there to be new content for a user to discover, new creators need to be encouraged by the platform.

>Agency is related to user safety and comfort. Sometimes users are not looking for anything new, but instead old comfortable memories or their favorite videos from a while ago. Although users may want something new, they might find something they don't like and need tools to avoid it in the future. Social media feeds are tailored to the user, so the user needs to have some control over the space they want to create. Blocking people can protect from harassment, while muting words or tags (like on Twitter and Tumblr) can help you avoid posts that make a user uncomfortable. Moderation teams are necessary to keep content safe, and community lead moderation can create rules to fit a communities custom needs. We hope to measure how customizable, comfortable, and safe a platform is using this scale.

>Self-Expression relates to how social media enables self-presentation, self-exploration, and the ego. Profile customization options can allow many to create authentic or inauthentic personas. Posts are often linked with virtual “achievements” such as likes or re-shares that can affect the ego. This scale aims to measure how a platform encourages identity presentation or getting lost in the crowd.

## Questions & Tasks
I want to visualize the perception of twelve social media with relation to demographics. The demographics include age, race, gender and whether the user identifies as LGBT. The twelve social media are BeReal, Facebook, Instagram, LinkedIn, Reddit, Snapchat, Tumblr, Twitch, Twitter, YouTube and 4chan.
* How well do social media encourage or inhibit community building, self-expression, content discovery and user agency?
* How varied are the demographics that responded to our survey?
* How do different demographics view social media as a whole?
* Does social media encourage some groups more than others? 

## Final Deliverables 

### Video Presentation [(YouTube)](https://youtu.be/VPD-r8Y5wMQ)
### Survey Histograms
[![image](https://github.com/flanagancarlie/social-media-isp-proposal/blob/final/final-isp/duration_hist.png?raw=true)](https://vizhub.com/flanagancarlie/84ae95a4edab41ba94c8146f77c17064)

[![image](https://github.com/flanagancarlie/social-media-isp-proposal/blob/final/final-isp/gender%20hist.png?raw=true)](https://vizhub.com/flanagancarlie/1d1e71fcda994cabb58f497ba5764659)

[![image](https://github.com/flanagancarlie/social-media-isp-proposal/blob/final/final-isp/social%20media%20hist.png?raw=true)](https://vizhub.com/flanagancarlie/639196d39a5a4a49ae559031fec45dd0)

### Social Media Comparisons
[![image](https://github.com/flanagancarlie/social-media-isp-proposal/blob/final/final-isp/bubble%20self.png?raw=true)](https://vizhub.com/flanagancarlie/b98cd56e8ba24d199e66aee898af281d)

[![image](https://github.com/flanagancarlie/social-media-isp-proposal/blob/final/final-isp/social%20media%20viz.png?raw=true)](https://vizhub.com/flanagancarlie/dee28e9e2da543f69ca1f93ba4b61bdd)

## Prototypes
![image](https://github.com/flanagancarlie/social-media-isp-proposal/blob/final/mqp_prototype.png?raw=true)

The first prototype created was during prototyping of my MQP. We envisioned that for each scale we defined, we would plot each social media as well as a toggle of our demographic options.

![image](https://github.com/flanagancarlie/social-media-isp-proposal/blob/final/mqp_viz.png?raw=true)

The next prototype created is on our [MQP website](https://socialsight.glitch.me/). This scatterplot counters community and self, and discovery and agency. During our MQP we were unable to integrate demographic data. Additionally, this obfuscates the actual values by contrasting the scales.

[![image](https://github.com/flanagancarlie/social-media-isp-proposal/blob/final/Histogram%20Basic.png?raw=true)](https://vizhub.com/flanagancarlie/099531ffa546434ebf740355944cbb9d)
Instead of a psuedo-visual, I have created a histogram using simple data. This histogram is a prototype, which I then forked and modified for the final visuals.

[![image](https://github.com/flanagancarlie/social-media-isp-proposal/blob/final/Bubble%20Psuedo-Viz.png?raw=true)](https://vizhub.com/flanagancarlie/b1307d07feac405e85726a4ecb135abc)
Additionally, I have created a psuedo-visual of a bubble chart. This would later become the final bubble chart visualization.

## Sketches
![image](https://github.com/flanagancarlie/social-media-isp-proposal/blob/final/viz_sketches.png?raw=true)

View 1 displays a bubble chart, which will show all social media. The size of the bubble will correspond to the Likert scale value, where a Strongly Inhibits is a 1, and a 7 will correspond to Strongly Encourages. A dropdown will allow the user to change the scale being displayed.
View 2 displays a radar pie chart. The pie chart will be divided into quadrants, with each quadrant representing a scale. This visualization was scrapped because it felt too cluttered, but I encourage others interested in trying out this visual.
For both views, a checkbox would be displayed next to the view to allow the user to pick and choose demographics. On default, all boxes will be checked and all data will be displayed.

## Future Work
Some ideas for future visualizations are as follows: 
* Checkboxes to narrow down data between demographics
* Integrating current visuals into our [MQP website](https://socialsight.glitch.me/)
