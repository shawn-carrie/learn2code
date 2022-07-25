# Programming Ideas

by Shawn Carrié

## Web Applications
  ### New Idea  
  Description goes here
  #### Categories
  ##### Sub-Categories
  ###### Sub-Sub-Categories

  ### RateCodingTuts
   A database to discover coding tutorial videos according to categories & user ratings.

   **Problem:** You're trying to learn to code. You've decided to go the self-taught route. When you search for tuts, you find a lot of ads or dumb influencer blog posts who want you to sign up to some bootcamp through their affiliate link. You want an easier way to find vetted coding tuts.

   #### Key Features
   - A user-driven, **open-source algorithm** for rating courses : No profit motive, no Google or Facebook or driving you toward paid courses or bootcamps
   - Perfect for self-learners looking for structure
   - See what is the top community-rated video in a specific category (eg. Ranking for videos on {CSS selectors, bezier curves})

   
   #### Roadmap
   - Plan (In Progress)
   - Iterate
   - Expand
    - User-Specific Suggestions?
    - Design & Share your own curricula (playlist)
    - Browser Extension to add new videos?

   #### Needs
   - relational database
       - schema of tuts (categories, creators, ratings)
        <!-- There must be out there a schema of all topics in programming / computer science... -->
   - add to database functionality
   - user authentication
   - user voting
       - rating system
       - algorithm
       
    ##### Algorithm
     ###### Metadata
      - Format (Video,Article,IDE…)
        <!-- What consistutes a single Tut? A single URL? How to display them? -->
      - Tutorial Type (single, course)
      - Topics []
      - Cost Class : [Free,Paid]
      - Cost Amount : [Amount,Frequency]
      - Platform : [Youtube, EdX, Coursera…]
      - Author []
      - Length -> Length Category
     ###### Rating System 
       - Author Expertise
       - (Comprehensiveness)
       - (Depth)
       - Pacing?
       - [Simplicity/Beginner-Friendliness/Assumption]
       - (Structure)
       - (Language)
       - Specificity
       - Production Value

       See "Five Levels" videos:

        [Simplicity/Beginner-Friendliness/Assumption]
        Mainly a measure of the user's assumed *prerequisite* knowledge, and should be measures as follows:
            1: Absolutely beginner-friendly. No knowledge whatsoever is assumed. A person with no knowledge of the topic would be able to follow.
            2: It's assumed that you already know what the topic is, but not much about it.
            3: It's assumed you know the basics, and are learning to do something properly.
            4: It's assumed you already know some advanced stuff, and are learning……
            5: You're an expert and are learning how to do something advanced.
        [Language] should be measures as follows:
            1: Simple language is used. A non-native English speaker would have no trouble
            2: Intermediate language is used,
            3: Adult Language is used,
            4: Professional Language is used,
            5: Like an academic lecture. This is highly advanced, technical language and it's assumed that the viewer 

        [Pacing] 

        [Structure]
            A measure of how well the tutorials is structured. Is the instructor just rambling, or have they put together a curriculum?
            Perhapsa 1-3 or 1-2 scale?
