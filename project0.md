Taking a look at the data that ranges from December 22, 2020 to March 21, 2021, I see that there are a total of 258 users that represent 252 different organizations and 11 payment plans.

![comp](https://user-images.githubusercontent.com/67920437/112703865-da015800-8e6e-11eb-9913-65b973749b2e.png)

Here you can see the companies that have more than 1 user. The 6 companies all have 2 users that work together.

![frequsers](https://user-images.githubusercontent.com/67920437/112703987-5a27bd80-8e6f-11eb-91d6-fe6240be53f3.png)

Here you can see the top 10 most frequent users and the total amount of times they have imported. User ID 1697454 was the most frequent user at 92 imports and there was a tie for the 10th spot at 23 imports. A lot of users have been very active during this time span.

![statustotals](https://user-images.githubusercontent.com/67920437/112704209-1c776480-8e70-11eb-9e4b-c6b615f338fd.png)

There are a total of 1,359 imports. Broken down, the majority of the imports are completed (948) or errored (397).

![statuspie](https://user-images.githubusercontent.com/67920437/112704508-41200c00-8e71-11eb-8343-5cbc755b7c43.png)

Imports with a completed status make up almost 70%, errored makes up about 29%, and queued and running combined makes up 1%. It is good to see that the majority of imports are being completed.

![deactpie](https://user-images.githubusercontent.com/67920437/112704681-dc18e600-8e71-11eb-9f71-10988830e38b.png)

Diving into the breakdown of users, about 94% of users are still active. It is good to see only a small percentage of the users have deactivated.

![paidpie](https://user-images.githubusercontent.com/67920437/112704693-e0450380-8e71-11eb-8a07-961f2e9feed2.png)

Looking into payment plans, it is about half and half on whether a user pays or has a free payment plan. There are a little bit more users who do not pay at 50.4%.

**After looking at some simple summaries, I decided to see if there were any trends between variables.**

**First I decided to look at the users' role.**

![paidusers](https://user-images.githubusercontent.com/67920437/112704973-1cc52f00-8e73-11eb-9374-bf676f9cb7c9.png)

The majority of users (252) are team owners and it is about half and half on whether they pay or not. Paying team owners take the lead at 51%. Of the 6 team managers, most of them do pay at 83%.

![deactusers](https://user-images.githubusercontent.com/67920437/112705052-7e859900-8e73-11eb-92a6-0c4aecad688d.png)

All of the team managers are still active and only 6% of the team owners have deactivated.

**I was curious to see if deactivation status had anything to do with the users' payment plan.**

![deactpay](https://user-images.githubusercontent.com/67920437/112712632-32544c00-8ea7-11eb-871a-f2eb0be51e50.png)

I found that payment plan 7, which is the free payment plan, had the most users (130) and payment plan 4 had the least (1). This could potentially mean that payment plan 4 is most likely not the best payment plan for users or it is not a popular choice. Payment plan 1 had the biggest percentage of people who deactivated at 40%, but only 5 people had that plan. Payment plan 13 had 33 users and 15% of them deactivated. This was an interesting visualization to look at as payment plan 13 might not be a plan that users like as well.

**Lastly, I decided to look at trends that dealt with imports.**

![importpay](https://user-images.githubusercontent.com/67920437/112712641-3e400e00-8ea7-11eb-9809-062e381c7ad8.png)

The free payment plan (payment plan 7) had the most imports at 352. Looking at import status across payment plans, I see that payment plan 14 had the biggest percentage of imports that were errored at 44% compared to the rest of the plans. This could be a tell that the service of this plan is not good. 

![morn](https://user-images.githubusercontent.com/67920437/112705350-b80ad400-8e74-11eb-9e72-f7a64495ad94.png)

I broke down the import times into morning vs night. This means that if the time is AM, it was in the morning category and if the time was PM, it was in the night category. The majority of the imports (1,055) happened in an hour that ended in PM and a bigger percentage of these imports had an errored status. The imports that happened in an hour ending in AM (304) had a bigger percentage of completed status. This tells me that imports done in the morning were more likely to be completed.














