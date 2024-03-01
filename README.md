# accepted_friend
Write a query to determine the number of Accepted friend requests.

Select count(action_taken) from friend_request where action_taken= ‘Accepted’;
