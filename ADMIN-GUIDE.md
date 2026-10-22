# Guided Admin matchdays

Use the official **Fantasy 5 Admin** app for real matches. Test apps use synthetic local data. The manager edition shows the same named teams, colors, events and keeper/substitution timeline after sync.

## Prepare online

1. Sign in and **Verify admin & download matchday**, or download latest setup from the menu. Check the download time. New matchdays require rules `1.6-matchday` in this download.
2. **Create new gameweek**. Choose the season, unused number, Cairo kickoff, team-edit deadline and match duration. The deadline cannot follow kickoff.
3. **Set player attendance**. Mark every confirmed attendee; doubtful/unknown players are not eligible for a match until confirmed.
4. **Create teams & assign rosters**. Create two or more teams, choose their names/colors and all members, including substitutes. Every confirmed player must belong to exactly one team. Each team needs at least five confirmed members before publication. Team order determines the initial waiting queue.
5. **Save & publish teams to managers**, then **Sync matchday** before the fantasy deadline. Check zero pending actions. Managers need a connection to select their squads; offline preparation cannot backdate their selection window.

## Start and record

1. At kickoff, **Start first match**. Choose the two teams explicitly. Select exactly five actual starters per side, choose any starter as keeper, and confirm you have checked the rosters/transfers. The other team members remain substitutes. Actual keeper duty does not change the footballer's purchased fantasy position.
2. During play use the large event buttons. Set the event minute, player and any assister. Saves means **additional saves**; a saved penalty already includes one save and one shooter miss. Do not enter them twice.
3. **SUB** replaces an active player with a reserve from the same team at the selected minute. If the outgoing player was keeper, the incoming reserve initially inherits that duty. **GK SUB** gives keeper duty to another active player; the former keeper stays outfield. To put a bench player in goal, first use SUB and then GK SUB if needed.
4. The selected minute belongs to the incoming player/keeper. Earlier events remain with their original duties. A change that conflicts with an already saved event is refused; review/void that event with a reason before correcting its duty.
5. **Review & finish match** shows the score and timed event/SUB/GK SUB timeline. Confirm the recap. A drawn first match requires selecting the penalty winner; its fantasy result remains a draw.
6. **Start next match** proposes the winner-stays pairing and next waiting team. Check both lineups and keepers again. With two teams the same teams play again; with four or more, the outgoing team joins the end of the waiting queue.

## Transfers between matches

Finish the active match, then **Transfer players between teams**. Choose the player, destination and reason. Repeat for the other player in a swap. Review the new starters/keeper before the next start. This changes future rosters only; the recorded teams in earlier matches stay intact. During a live match, use same-team SUB rather than transferring a player from another team.

## Finish the gameweek

1. Finish every match and choose **Review confirmed absences**. Answer No when everyone attended, including unused reserves. If Yes, select only confirmed people who were actually absent and mark whether excused. An actual participant cannot be marked absent. Excused is zero penalty; unexcused is -2.
2. Save the attendance review, then **Save gameweek publication**. Any subsequent match/attendance correction requires reviewing absences again.
3. Reconnect and **Sync matchday**. Wait for zero pending actions and a finalised gameweek. Local publication awaiting sync does not publish manager points. Repeat sync safely if a response was lost.

## Keeper points from rules 1.6

Primary GK: 1 point per complete three saves. Any other primary position: 2 points per complete three saves. Emergency +2 still requires neither registered role GK, and now more than five actual keeper minutes in that match (six or more, accumulated across spells). Full-match clean-sheet requirements remain. Existing GW1 retains its original rules.

## Offline and corrections

All preparation, transfers, starts, events, SUB/GK SUB, match recaps, absence review and publication requests save through the durable SQLite journal. Closing or restarting retains them and the selected gameweek. Download the setup before leaving and keep the app installed. Account/catalog/price settings and distribution to managers need connectivity.

Export a backup before resolving a sync conflict. Review the current server record and choose a reasoned retry or keep-server decision; nothing silently overwrites another device's record. **Reopen for correction** retains historical records and requires rotation/price reconciliation acknowledgment. Correct/void the source events, finish the match again, review absences and republish. Later real fixtures are retained with audited reconciliation.
