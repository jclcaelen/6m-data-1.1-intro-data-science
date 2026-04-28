# **🎬 Case Study: The Netflix Data Engine**

## **The Scenario**

Netflix doesn't just show you movies; it predicts what you want before you know it. This recommendation system is a perfect example of the **Data Lifecycle**.

## **👥 Group Discussion Questions**

Break into small groups and answer the following. Use your knowledge of Structured vs. Unstructured data.

### **Part 1: Collection (What data do they have?)**

*List at least 3 examples for each category that Netflix likely collects about you:*

* **Explicit Data (Things you click):** (e.g., Thumbs up/down...)
  - My Answer (28-Apr-2026):
     i. Thumbnails
    ii. Shows specifically clicked, watched and not watched.
    iii. Favourites list

Didn't list "language preferences for subtitles and audio since netflix resumes what your previous settings are.

* **Implicit Data (Things you do):** (e.g., Did you pause at a scary scene? Did you binge-watch 5 episodes?)
  - My Answer (28-Apr-2026):
     i. Scene replays, fast forwards/scene skips
    ii. Certain actors/actresses/directors
    iii. Genre scrolls/browsing

Didn't list "skip intro" etc because netflix still asks.
    
### **Part 2: Structured vs. Unstructured**

* **Structured Data:** User ID, Movie Genre, Release Year.  
* **Unstructured Data:** The movie thumbnails (images), the movie plot summary (text), the video files themselves.  
  * *Question: How might Netflix use the **Unstructured** data (thumbnails) to trick you into watching a movie?*

- My Answer (28-Apr-2026): Was briefly discussed in class. The thumbnails may have been given a caption to detail the snapshot of the scene. Using vectorisation, similar to LLM prompting, highly similar thumbnails will then be pushed to the user after the end of the show to continue watching the next. 

### **Part 3: The Algorithm (Analysis)**

* If User A watches "Breaking Bad" and "Better Call Saul".  
* And User B watches "Breaking Bad".  
* *What will the algorithm recommend to User B? Why?*

"Better Call Saul". The algorithm could have link both shows as related or similar, and if A would be interested to watch both, B who had watched 1 of them has a likelihood to watch the other.

### **Part 4: Ethics (The "Bubble")**

* *Is it ethical for an algorithm to only show you things it knows you will like? Does this create a 'content bubble' that limits your exposure to new ideas?*

I feel that this is subjective, and may be related to when phones prompt the user if they would like personalised ads. Personalised ads would likely create this "content bubble" and filter out noises that you may not have been interested. If the algorithm is robust, I do not feel a user would have missed something potentially could have interest him/her. Lastly, there is no roadblock for the user to manually scroll or search for new "ideas".


## **💡Please Share Your Answers & Thoughts in Discord💡**

