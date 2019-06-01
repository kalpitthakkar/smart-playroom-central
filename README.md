# Smart Playroom: Analysis of all subject trials

After flagging the trials with the strategy "Fixate, Approach and Grab", it seems that it is used in a major chunk of the trials.
  * A small movement from the starting spot (while turning around) before fixation is not considered as "locomotion" while flagging the videos.
  * After looking at trial videos for ALL the __forty two__ subjects, according to me, there are three strategies used:
    * Fixate, Approach and Grab (which are flagged)
    * Pure Memory Recall, Approach and Grab
    * Move around, Fixate, Approach and Grab
  * This revelation makes the analysis of Kinect paths using 3D body joints a lost cause, as most of the trials will exhibit _almost_ straight line paths (due to obstacles, the path taken can be curved, but the approach is still in the direction of the object).
  * So, what now? - the analysis of eye fixations, combined with the saliency in absence of prior knowledge (bottom-up) and the saliency in presence of prior knowledge (top-down) are instrumental
    * The top-down scores for the object being searched / similar objects (for example: the textures for Hippo, Elephant and Dinosaur look similar) should be high, when maps until the "grasp time" are averaged.
    * If the fixations for previous trial are considered for the next trial, we can see that "Pure Memory Recall" cases can happen even for the _Far_ object searches if the kid explored triplets other than the one being searched.
    * There is a high possibility that when the kid searches for a _Near_ object, _Far_ object position in the corresponding triplet is encoded. If the next trial is for that _Far_ object, the kid will right away recall the direction in which visual search should be done (explaining some sudden straight paths for _Far_, even when most other searches were "Move around, Fixate, Approach and Grab").
  * The time taken from "start of trial" to "grasp time" can be used as a preliminary indicator for strategy being chosen: __least__ should be "Pure Memory Recall", followed by "Fixate" and "Move around, Fixate".
  * Head movements __should__ be used to understand the process of exploration around the room: Fluctuations indicate search process and relatively steady motion indicate fixation+approach.

For demonstration purposes: (1) Good examples for the strategy "Move around, Fixate, Approach and Grab" are subjects 3918, 3939, 3947 and 3954, (2) For the strategy "Pure Memory Recall, Approach and Grab", the trails cow, pooh, airplane and car for subject 3930 are good examples (there are more which can be found), (3) For the "Fixate, Approach and Grab" strategy, the flagged trials can be used. Subjects 3872 and 3881 are really good examples, as they use it for almost 100% of their trials.

__Fun Fact__: The kids love "Winnie: The Pooh" toy. Most of them find that object right away.
