# Today I Learned

## Motivation

There are many benefits to learning something new every day, but it is difficult to consistently find the motivation to learn and stick to your goals with countless distractions literally at your fingertips. On average, in 2023, people spend 2.5 hours daily on social media [^1]. **Today I Learned** tries to bridge the gap between the desire to learn and the urge to check your feed by being a learning-focused social media platform.

> A note from the creator: The original inspiration was realizing I'm best motivated by seeing my friends also being productive. I envisioned an app dedicated to seeing other people's progress on their learning journeys, where everyone can motivate each other.

### Problems:

- **Lack of Genuine Learning Community:** Most social media platforms primarily encourage superficial interactions and personal branding. The abundance of noise makes it difficult to find supportive learning communities.

- **Anonymity and Trolling:** Many online platforms allow users to remain anonymous, enabling a breeding ground for trolls and toxic behavior. This anonymity hinders constructive conversations and knowledge sharing.

- **Limited Access to Relevant Connections:** Finding like-minded individuals who share similar interests or are learning about the same topics can be a challenging and time-consuming process on existing platforms. This limits the potential for creating meaningful connections and sharing insights with people who truly matter.

- **Disconnect from Educational Institutions:** There is often a disconnect between the knowledge-seeking endeavors of students and the resources provided by educational institutions. There isn't always a class for what you want to learn. Fostering a seamless connection between students and universities or learning organizations remains a challenge.

### Solution:

The "Today I Learned" app aims to tackle these problems by providing a dedicated platform for learning enthusiasts. It encourages users to share their learning experiences, with each post beginning with "Today I learned...". The app analyzes posts based on keywords, allowing users to find others who are learning similar things and connect with them. Through direct integration with university networks and organizations, it fosters a community that is closely tied to the world of education, reducing anonymity and trolling. Users can now engage in meaningful, knowledge-focused conversations and build authentic connections with peers who share their passion for learning.

## Goals

### Home Feed

On the home feed, you can see what people are learning all over the world, with filters to sort by relevancy (about topics similar to those you've learned) or date posted, or you can see posts from other members of your organization or your friends. To promote a healthy community, you can report messages or users that go against our Code of Conduct.

### Connections

The app analyzes your posts for keywords and suggests people who are learning similar things. Making friends unlocks additional features in the app. For example, you can only comment on posts from your friends.

Potential features to add:
- Friend groups
- Learning challenges that you can set up between friends or within groups

## Usage

### Normal User

When users register an account, they must provide the email tied to their organization or university in order to prove their identity. The email will be verified automatically, but can also be manually verified by an organization admin. While the email is being processed, a user will only be able to view global posts.

### Organization Administrator

When new organizations are integrated with the app, a base administrator account is created that can manage the organization within the app. When making a new admin account, it must be approved by another admin account from the same  organization.

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

https://github.com/orgs/tilapp/projects/1/views/1

## About Us

### Winston Co
Aspiring web developer

| Liked learning | Currently learning | Wants to learn |
|----------------|--------------------|----------------|
| TypeScript     | HTMX               | Rust           |
| React          | Flutter            |                |
| Blazor         | OCaml              |                |
|                | Vim motions        |                |

[^1]: https://www.statista.com/statistics/433871/daily-social-media-usage-worldwide/

