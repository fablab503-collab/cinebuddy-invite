# CineBuddy invitations

The page friends open from a CineBuddy outing invitation: it shows the film, the cinema and who is
coming, and lets them answer with a first name, without installing the app.

It only calls two database functions (`outing_preview` and `answer_invite`) with CineBuddy's public
key; everything else in the database is protected by row-level security. Source: the CineBuddy app
repository, `web/invite/index.html`.
