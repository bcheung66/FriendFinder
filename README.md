# FriendFinder

FriendFinder is an application to find a friend using the survey questions and answers to match their common interests, personality, life objective and etc.  The survery have 10 questions of your choosing. Each answer should be on a scale of 1 to 5 based on how much the user agrees or disagrees with a question. The survey scores will be used to determine the cloest match.

     * Example: 
       * User 1: `[5, 1, 4, 4, 5, 1, 2, 5, 4, 1]`
       * User 2: `[3, 2, 6, 4, 5, 1, 2, 5, 4, 1]`
     * Total Difference: **2 + 1 + 2 =** **_5_**
The difference will be an absolute value.
he closest match will be the user with the least amount of difference.

Once you've found the current user's most compatible friend, display the result as a modal pop-up. The modal should display both the name and picture of the closest match. 