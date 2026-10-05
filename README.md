# Pulse

Pulse is a place-discovery app that learns what you like. Swipe through restaurants, gyms, parks, climbing spots, community centers and more. Pulse picks up on what you linger over, like and rate, and gets better at suggesting places you'll enjoy.

It's built for people who are new to a city, or who've lived somewhere for years and want to finally explore it, without prompting a chatbot or wading through generic search results.

> **Status:** early development. Nothing is runnable yet. The design is settled and the first scaffolding is next.

## Features (MVP)

- **Discovery feed:** an endless stream of place cards with name, category, drive time from your home address, the top community tags and a photo. Expand a card for the full description, all tags, ratings and a photo carousel.
- **Like / dislike / skip:** one action per place. After a like or dislike you can optionally vote on which tags fit.
- **Tags:** structural tags from Google Places (for example "Indian Restaurant") plus community tags (for example "good for a date", "not crowded", "outdoor seating").
- **Learning recommendations:** time spent on a card, expands, likes, dislikes and post-visit ratings all shape what you see next. Early recommendations are rule-based, using tags, recency and variety.
- **Saved places and playlists:** a master list of everything you liked, plus custom playlists like "date ideas" or "weekend exploration".
- **Search and undo:** simple name search, and an undo for accidental dislikes.
- **Photo testing:** the photo that gets the most engagement for a place is shown more often.
- **Light-first design:** clean, minimal cards with dark mode as an option.

Starting city: Austin, with a location-agnostic design so other cities can follow. Only permanent places are in scope; time-based events are not.

## Tech stack

| Layer | Choice |
|---|---|
| Frontend | React + TypeScript, shipped as a Progressive Web App (installable, no app store needed) |
| Backend | Python + FastAPI |
| Place data | Google Places API |
| Hosting | Render |

## Getting started

Setup and run instructions will land here once the first scaffolding is in.

## Roadmap

- [ ] Database schema and recommender design
- [ ] Backend: auth, Google Places integration, interaction tracking
- [ ] Frontend: discovery feed, swipe actions, expandable cards, tag voting, saved places
- [ ] Recommendations, photo testing, playlists, settings
- [ ] Friends and family beta
- [ ] Public soft launch

Ideas for later: map view, sharing and collaborative lists, location notifications, natural-language search, events.

## Patch notes

No releases yet.
