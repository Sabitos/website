## Arhitectură
- includes/functions.php – funcții comune (DB, CSRF, sanitize, upsertUser etc.)
- includes/navbar.php – bara de navigație
- user/ – profile, team, invites, players
- admin/ – panou administratori

## Tabele principale
- users (id, discord_id, display_name, current_rank, rank_status, riot_id, …)
- teams (id, name, captain_id)
- team_members (team_id, user_id, position)
- team_invites (team_id, user_id, invited_by, created_at, accepted_at)
- rank_requests …

## Cum adaug un feature nou
1. Crează branch: git checkout -b feature/<ce-ai-făcut>
2. Modifică fișierul X sau adaugă Y
3. Testează local
4. git push și deschide PR

## Workflow chat‑GPT
> Oricând am nevoie de ceva, copiază blocul de cod relevant + link direct către linia din GitHub.
