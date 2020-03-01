# Mattermost Suggestor Bot

This is the mattermost suggestor bot which recommends channels to users.

**Collaborative filtering** of the channels is done using the NearestNeighbors algorithm. We calculate the scores of each user in a channel as the number of messages posted in the channel.

## Features

K Nearest Neighbors finds the K most similar channels to particular user based on user score on certain channels.

Collaborative Filtering using Nearest Neighbors Classifier uses a cosine similarity matrix.

## Installation

1. Clone the repo:
```bash
git clone https://github.com/sbis04/mattermost_suggestor_bot.git
```

2. Navigate to the cloned directory:
```bash
cd mattermost_suggestor_bot
```

3. Run the following command to run the bot:
```bash
make
```

## Usage
Suggestions can be triggered using the slash command `/suggestor channels`.

## Future Prospects
* Use Neural Networks
