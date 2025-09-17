# Event Schema – Social Listening Rooms

## Events to Track
- `room_created` — host creates a listening room
- `room_joined` — user joins via link/invite
- `track_played` — song starts in a room
- `reaction_sent` — emoji reaction
- `chat_message_sent` — text message sent
- `invite_shared` — link shared externally
- `session_length` — duration of co-listening session

## Metrics Mapping
- **Engagement**: reaction_sent / DAU, chat_message_sent / DAU
- **Virality**: invites_shared per user
- **Retention**: % users returning to rooms in 7 days
- **Time Spent**: avg session_length per user