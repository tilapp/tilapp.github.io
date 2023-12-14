<!-- omit in toc -->
# Today I Learned

<!-- omit in toc -->
### Table of Contents

- [Motivation](#motivation)
- [Usage](#usage)
- [Usability Test](#usability-test)
- [Deployment](#deployment)
- [Installation](#installation)
- [Development Status](#development-status)
- [About Us](#about-us)
  - [Winston Co](#winston-co)

## Motivation

There are many benefits to learning something new every day, but it is difficult to consistently find the motivation to learn and stick to your goals with countless distractions literally at your fingertips. On average, in 2023, people spend 2.5 hours daily on social media [^1]. **Today I Learned** tries to bridge the gap between the desire to learn and the urge to check your feed by being a learning-focused social media platform.

> A note from the creator: The original inspiration was realizing I'm best motivated by seeing my friends also being productive. I envisioned an app dedicated to seeing other people's progress on their learning journeys, where everyone can motivate each other.

<!-- omit in toc -->
### Problems:

- **Lack of Genuine Learning Community:** Most social media platforms primarily encourage superficial interactions and personal branding. The abundance of noise makes it difficult to find supportive learning communities.

- **Anonymity and Trolling:** Many online platforms allow users to remain anonymous, enabling a breeding ground for trolls and toxic behavior. This anonymity hinders constructive conversations and knowledge sharing.

- **Limited Access to Relevant Connections:** Finding like-minded individuals who share similar interests or are learning about the same topics can be a challenging and time-consuming process on existing platforms. This limits the potential for creating meaningful connections and sharing insights with people who truly matter.

- **Disconnect from Educational Institutions:** There is often a disconnect between the knowledge-seeking endeavors of students and the resources provided by educational institutions. There isn't always a class for what you want to learn. Fostering a seamless connection between students and universities or learning organizations remains a challenge.

<!-- omit in toc -->
### Solution:

The "Today I Learned" app aims to tackle these problems by providing a dedicated platform for learning enthusiasts. It encourages users to share their learning experiences, with each post beginning with "Today I learned...". The app analyzes posts based on keywords, allowing users to find others who are learning similar things and connect with them. Through direct integration with university networks and organizations, it fosters a community that is closely tied to the world of education, reducing anonymity and trolling. Users can now engage in meaningful, knowledge-focused conversations and build authentic connections with peers who share their passion for learning.

## Usage

<img src="/assets/images/home.png" alt="Home Page" />
<img src="/assets/images/home-2.png" alt="Home Page filtered by friends" />
<img src="/assets/images/search-user.png" alt="Search User Page" />

On the home page, you can see posts from other users, filtered by various categories (e.g. From your friends). By clicking on the search icon in the bottom-right, you can navigate to a search page where you can search for specific users by name.

<img src="/assets/images/my-profile.png" alt="My Profile Page" />
<img src="/assets/images/other-profile.png" alt="Other Page" />

Of course, you can see the details of a user, on either your own profile or the profile of another user. You can see all their posts and the organization their account is tied to. And if you aren't friends with them yet, here you can send another user a friend request.

<img src="/assets/images/friends.png" alt="Friends Page" />

On your friends page, you can see your list of friends.

In the future, you will see a list of suggested users, who recently made posts about similar topics as you. If allowed, it will also look at your contacts for other profiles.

<img src="/assets/images/new-post.png" alt="New Post Page" />

And of course, you can make posts of your own by clicking the **+** icon at the bottom.

## [Usability Test](/evaluation)

## Deployment

This app is currently not deployed.

## Installation

_Make sure Flutter is installed locally._

The app is open source on [GitHub](https://github.com/tilapp/til).

```sh
git clone https://github.com/tilapp/til.git
cd til
flutter run
```

Or [open with GitHub Desktop](x-github-client://openRepo/https://github.com/tilapp/til)

## Development Status

[https://github.com/orgs/tilapp/projects/1/views/1](https://github.com/orgs/tilapp/projects/1/views/1)

## About Us

### Winston Co
Aspiring web developer

| Liked learning | Currently learning | Wants to learn |
| -------------- | ------------------ | -------------- |
| TypeScript     | HTMX               | Rust           |
| React          | Flutter            |                |
| Blazor         | OCaml              |                |
|                | Vim motions        |                |

[^1]: [https://www.statista.com/statistics/433871/daily-social-media-usage-worldwide/](https://www.statista.com/statistics/433871/daily-social-media-usage-worldwide/)

