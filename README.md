# Forum-App
Machine Coding Round Four


App Features:#
User Feed

a. Create a landing page with a list of user posts/questions.

Sidebar

a. Show a left sidebar with “Home”, “Explore”, “Bookmarks” and “Profile” options. The items are not clickable for this question.

Upvote-Downvote

a. Clicking on the "Upvote button" will increase the upvote count of the post.

b. Clicking on the "Downvote button" will decrease the upvote count of the post.

c. If the downvotes are more than upvotes, the votes count should be in negative.

Post/Question Options

a. Show tags associated with each post in the form of pills.

b. Show a "Comment", “Share” and “Bookmark” icon for each post.

c. On clicking the Bookmarks icon, the color of the icon should change, indicating that the post is bookmarked.

d. On clicking the Comments icon, that post should open in a separate page with the comments view expanded.

e. For this question, the share icon should not be clickable.

Sort

a. Create feature to sort the post by the date created(latest on top) and most upvoted post.

Forum App View:
![forum app view](https://neog-lms.vercel.app/Screenshot_2023-06-24_at_2.54.54_PM.png)

Single Post View:
![single post view](https://neog-lms.vercel.app/Screenshot_2023-06-24_at_2.51.09_PM.png)

JSON Data:
```{const forumData = {
  accountId: '98767-888-78767',
  username: 'tanaypratap',
  name: 'Tanay Pratap',
  picUrl: 'http://bit.ly/42Zm7tM',
  posts: [
    {
      postId: '36635-787-65778',
      username: 'tanaypratap',
      name: 'Tanay Pratap',
      picUrl: 'http://bit.ly/42Zm7tM',
      post: 'Join InvactHQ for MBA',
      postDescription:
        'Non programmers on my timeline. Attention! After placing 100+ programmers i in top Indian startups, I am thinking of coming up with a program for business roles as well. Interested in helping me build this course? Join me at Invact.',
      upvotes: 350,
      downvotes: 50,
      tags: ['mba', 'business', 'bootcamp'],
      createdAt: '2023-06-24T12:00:00Z',
      comments: [
        {
          commentId: '89898-856-87576',
          username: 'ashwin4real',
          picUrl: 'http://bit.ly/42Zm7tM',
          likes: 0,
          comment: 'Interested',
          createdAt: '2023-06-24T12:01:00Z',
        },
      ],
      isBookmarked: false,
    },
    {
      postId: '36698-343-321232',
      username: 'trishajain',
      name: 'Trisha Jain',
      picUrl: 'http://bit.ly/42Zm7tM',
      post: 'Can I learn HTML, CSS, and JavaScript in 1 year?',
      postDescription:
        'I am looking to make my career in web development and want to learn these technologies. Can I learn these in 1 year and get a job?',
      upvotes: 150,
      downvotes: 0,
      tags: ['html', 'javascript', 'web development'],
      createdAt: '2023-06-24T12:54:00Z',
      comments: [],
      isBookmarked: false,
    },
  ],
}}```
