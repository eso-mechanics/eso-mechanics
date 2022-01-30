---
layout: page
title: Maw of Lorkhaj
permalink: /trials/maw-of-lorkhaj/
---

<div class="flex-parent">
  <div class="input-flex-container">
    <input type="radio" class="first node" name="timeline-dot" data-description="one" checked>
    <div class="dot-info above" data-description="one">
      <span class="label">Khajiit Enemies</span>
    </div>
    <input type="radio" class="node" name="timeline-dot" data-description="two">
    <div class="dot-info below" data-description="two">
      <span class="label">Boss One</span>
    </div>
    <input type="radio" class="node" name="timeline-dot" data-description="three">
    <div class="dot-info above" data-description="three">
      <span class="label">Ogres & Arena One</span>
    </div>
    <input type="radio" class="node" name="timeline-dot" data-description="four">
    <div class="dot-info below" data-description="four">
      <span class="label">Boss Two</span>
    </div>
    <input type="radio" class="node" name="timeline-dot" data-description="five">
    <div class="dot-info above" data-description="five">
      <span class="label">Arena Two</span>
    </div>
    <input type="radio" class="node" name="timeline-dot" data-description="six">
    <div class="dot-info below" data-description="six">
      <span class="label">Final Hallway</span>
    </div>
    <input type="radio" class="last node" name="timeline-dot" data-description="seven">
    <div class="dot-info above" data-description="seven">
      <span class="label">Final Boss</span>
    </div>
    <div id="timeline-descriptions-wrapper">
      <div class="section" data-description="one">
        <h2>Khajiit Enemies</h2>
        <img src="{{ site.baseurl }}/images/trials/mol/dro-mathra.jpg" alt="Maw of Lorkhaj - Dro-m'Athra" />
        <p>After entering the second door and moving forward a group of cursed monks, scholars and war-priests (non-elite mobs) will rush and attack before some bigger, elite, Khajiit enemies drop in.  These will be repeatedly encountered through the trial in some arena-style fights with several waves of enemies that result in a reward chest.</p>
        <ul>
          <li><b>Dro-m'Athra Sun-Eater</b> - Ranged casters that do little damage with their simple attacks but have one painful mechanic:
            <ul>
              <li><b>Eclipse Field</b> - Targets a random player and drops a large negate field on them which will leave a lingering AoE on the ground.  This AoE will damage, slow and silence any players inside it as well as clear that area of your own AoE abilities.</li>
            </ul>
          </li>
          <li><b>Dro-m'Athra Dreadstalker</b> - Ranged enemies (archers) that perform two attacks to be aware of:
            <ul>
              <li><b>Sinister Shot</b> - A large conal attack focussed on whoever has aggro which has several gaps that can be utilised to avoid the damage.</li>
              <li><b>Marked for Death</b> - A random player will be marked and attacked by the archers pet cat/s (Ghostly Sar-m'Athra) which cannot be taunted.  The targeted player will have a dark glow rising from them and more cats will spawn in if the player/s are marked for a long time.</li>
            </ul>
          </li>
          <li><b>Dro-m'Athra Shadowguard</b> - Melee enemies (sword & shield) that have several attacks but can easily be managed by the tank.  Their abilities include:
            <ul>
              <li><b>Shadow Slash</b> - A large AoE, spin attack that does a lot of damage to anyone caught inside.</li>
              <li><b>Void Rush</b> - Charges to and knocks down a random player if they do not block in time.</li>
              <li><b>Lunar Slam</b> - This enemys heavy attack.</li>
            </ul>
          </li>
          <li><b>Dro-m'Athra Savage</b> - Melee enemies (two hander) that have a couple of attacks to be aware of:
            <ul>
              <li><b>Vicious Cleave</b> - This enemys light attack will cleave anyone in front of him.</li>
              <li><b>Shattering Strike</b> - Swings his weapon over his head and slams it into the ground.  If the player targeted by this attack does not manage to dodge it then it will inflict them (and any nearby players) with a Shattered debuff (shown as a buff in the log files) which reduces physical resistance.</li>
              <li><b>Crescent Swing</b> - This enemys heavy attack does a lot of damage.</li>
            </ul>
          </li>
        </ul>
        <div class="spoiler">
          <input type="checkbox" class="spoiler-button">
          <div class="spoiler-head">Strategies</div>
          <div class="spoiler-body">
            <p>There are several approaches to dealing with these mobs but a common one is to keep the Savages out of the group (typically one tank holds these a little way away) to avoid the groups armor becoming shattered.  In trash packs where there are no Savages then one tank can grab the Dreadstalkers and try to run them onto the stack of melee adds that the other tank can control.  Prioritising Sun-Eaters is a good idea to avoid multiple negate fields being dropped in the group, this is the one mechanic that can really cause trouble here.</p>
            <p>Any melee DDs standing near the Shadowguard should block its AoE attack as if they are hit by this and something else they will likely die.  The ghostly cats can be ignored for the most part (they can be CC'd if they become a problem) as killing the Dreadstalkers will despawn them.  Just make sure to not run away if they are on you as you will run away from the healing circles.</p>
            <p>An in-depth guide to handling all of the trash packs found throughout this trial can be found <a href="https://www.youtube.com/watch?v=IINj53bJeZs" target="_blank">here</a></p>
          </div>
        </div>
      </div>
      <div class="section" data-description="two">
        <h2>Boss One - Zhaj'hassa the Forgotten</h2>
        <img src="{{ site.baseurl }}/images/trials/mol/zhajhassa.jpg" alt="Maw of Lorkhaj - Zhaj'hassa the Forgotten" />
        <p>A giant Khajiit wielding a huge two handed weapon and specialising in curses and summon abilities.  Group positioning and communication is crucial for this fight.</p>
        <ul>
          <li><b>Grip of Lorkhaj</b> - Often called the "curse".  The boss will target three players with blue orbs which will curse them, causing them to take a small amount of damage, slow them down and turn their screen a blueish colour.  This debuffed can be spread to anyone too close to a targeted player on intial impact and can only be removed by standing on an active (lit) cleanse pad around the edge of the room.  Failure to remove the debuff will result in death after a short while.</li>
          <li><b>Dark Aegis</b> - When the boss health reaches 70% and 30% he will shield himself and become invulnerable to damage.  The shield can be destroyed and while it is active everyone in the group will continuously take damage, indicated by a spreading AoE under each players feet.  If you stand in another players AoE you will take damage from their one as well as your own.</li>
          <li><b>Thunderous Impact</b> - The boss slams its weapon into the ground on whoever has aggro doing a lot of damage.  The "Aftershock" from this attack can hit other players.</li>
          <li><b>Dark Monolith</b> - The furthest player away will be targeted and a huge pillar will spawn on them, bursting from the ground.  When it spawns this AoE around the pillar will damage anyone inside and knock them back if they are not blocking.</li>
          <li><b>Void Explosion</b> - The boss raises its weapon up above its head and begins channeling.  After a short time there is a huge explosion that will kill anyone who is in the boss' line of sight.</li>
          <li><b>Ghostly Sar-m'Athra</b> - At set intervals, based on the boss' health, cats will be spawned in to attack random players and do a lot of damage compared to those accompanying the Dreadstalkers.  They cannot be taunted but can be CC'd.</li>
          <li><b>Raging Cleave</b> - A frontal, cleave attack which will do damage to anyone in the 180° in front of the boss.</li>
          <li><b>Strike</b> - The boss' light attack.</li>
        </ul>
        <div class="spoiler">
          <input type="checkbox" class="spoiler-button">
          <div class="spoiler-head">Strategies</div>
          <div class="spoiler-body">
            <p>The main things here to deal with are the Grip of Lorkhaj (curse) and Dark Aegis (shield) mechanics.  In order to avoid hitting additional players with these mechanics it is advised that you organise group positions before starting.  Ideally, the group should be positioned in two semi-circles behind the boss (melee close to the boss, ranged behind them) and each player should stay a few metres apart.  When a player is cursed they should move to a cleanse pad and then back to their assigned position quickly.  There are six cleanse pads and only three players are cursed each time (as long as the curse is not spread to others).  This means that there will always be enough cleanse pads available if the group is co-ordinated.  If players move to cleanse immediately after the AoE disappears then the cleanse pad should refresh in time for the next cursed player to use (the timing on this is tight, however) and you can get to your cleanse pad quickly by dodge rolling there.</p>
            <p>When the shield phase begins, all players should maintain their positions and drop as much damage on the boss as possible to end the phase.  The cats can be pulled in by the off tank and focussed by the DDs as these will cause issues if they stack up.</p>
            <p>When the boss has spawned in five pillars he will start channeling the first explosion and the whole group should move behind a pillar to make sure they are out of line of sight of the boss, when the pillars are shattered it is safe once again and everyone should return to their positions.  As the fight progresses there will be less pillar spawns and less time between each of these explosions.</p>
            <p>One safe way to handle this fight is to assign a cleanse pad to be for tanks only (you can also assign a pad for each healer as well).  If a DD is sharing a pad with a healer and they both get cursed then the DD can simply maintain his position while the healer cleanses.  Once the curse has run its course the DD will die but can easily be resurrected from their position.  This is obviously not ideal due to players dying but is a very safe way to handle this fight.</p>
          </div>
        </div>
      </div>
      <div class="section" data-description="three">
        <h2>Ogres & Arena One</h2>
        <img src="{{ site.baseurl }}/images/trials/mol/ogres.jpg" alt="Maw of Lorkhaj - Ogres" />
        <p>In the next trash pack you encounter you will see some new mobs: Ogres (the Ogre Shaman is particularly nasty).  Upon dispatching the Ogres some more Khajiit will drop in, all of which you have faced previously.  Making your way down the slope you will encounter some more Ogres and discover the last new trash mob of the trial: Oger Flesh-Render.  A few more Khajiit will drop in which need to be taken care of before you can head down the slope to an arena-style fight where you will need to face multiple waves of enemies, all of which you have already faced.  If the group wipes during this encounter you will need to start from the beginning but completion will reward a chest.</p>
        <ul>
          <li><b>Ogre Brute</b> - Smaller mobs that pose no serious threat on their own.</li>
          <li><b>Ogre Shaman</b> - This mob performs a channeled ability, raising his arm up into the air and firing heals onto himself and other Ogres around (Primal Heal).  When the Ogres are healed an AoE will pulse out from under their feet causing a lot of damage to anyone inside.</li>
          <li><b>Ogre Flesh-Render</b> - These have one key attack (Savage Onslaught) which can cause issues as it knocks down players in a large AoE around him, snares them and applies a bleed.  This attack has a build up where the ogre will bend forward slightly then rear up and scream and can be interrupted at any point during this build up.  The attack will be continuously repeated once it has started.</li>
        </ul>
        <div class="spoiler">
          <input type="checkbox" class="spoiler-button">
          <div class="spoiler-head">Strategies</div>
          <div class="spoiler-body">
            <p>It is advised that the Ogre Shamans are handled first to avoid the damage they can do in a large area when they start healing; if they do start the healing attack, however, it is advised to either move away from any mobs and attack from a ranged position or block cast.</p>
            <p>The Ogre Flesh-Renders need to be monitored closely and interrupted continuously (roughly once every 1-2seconds) once they begin channeling their attacks.  This is most easily handled by one tank while the other picks up and tries to stack the other mobs.  During the arena-style fight you will have one wave with two Ogre Flesh-Renders so we would typically have the tanks take one of these each (other group members can help with the interrupts also).  You will also get Dro-m'Athra Savages which should be handled as described previously.</p>
          </div>
        </div>
      </div>
      <div class="section" data-description="four">
        <h2>Boss Two - The Twins (S'Kinrai & Vashai)</h2>
        <img src="{{ site.baseurl }}/images/trials/mol/twins.jpg" alt="Maw of Lorkhaj - The Twins" />
        <p>This fight has a very unique mechanic that requires the whole group to pay attention to the mechanics, their surroundings and other players.  It can also go very wrong, very quickly if you have some deaths within the group as in order to manage the main mechanics effectively twelve (living) players are required.  Both bosses will fight with melee weapons but while the light (yellow) adds are melee, the dark (blue) adds are ranged.</p>
        <ul>
          <li><b>S'Kinrai</b> - The "light" or "yellow" boss shares similar animations and attacks to the Templar class and has three unique skills that you need to be aware of:
            <ul>
              <li><b>Fearsome Cleave</b> - The bosses light attack will cleave anyone in front of them.</li>
              <li><b>Lunar Flare</b> - The boss turns to a random player and inflicts them with a strong DoT that can be cleansed.</li>
              <li><b>Lunar Destruction</b> - A channeled, interruptible beam that is cast on the player with aggro.  This player is stunned for the duration of the attack.</li>
            </ul>
          </li>
          <li><b>Vashai</b> - The "dark" or "blue" boss will inflict a bleed with its attacks and perform a hard hitting heavy attack (Shield Bash) but only has one really troublesome skill:
            <ul>
              <li><b>Shadow Vortex</b> - The boss summons a large negate fields centred on the player with aggro.  This field will damage, slow and clear friendly AoEs in the area.</li>
            </ul>
          </li>
          <li>Both bosses share all of the other attacks and perform them at the same time:
            <ul>
              <li><b>Holy Aspect</b> - Shortly after the fight begins and shortly after the bosses teleport they will enter a praying animation and inflict debuffs on the closest players to them.  Those closest to S'Kinrai will be inflicted with "Lunar Aspect" causing them to glow yellow and those closest to Vashai will be inflicted with "Shadow Aspect" and glow a dark blue.  These debuffs have a few notable effects:
                <ul>
                  <li>Any damage you deal to an enemy with the matching colour to yourself will be massively reduced.</li>
                  <li>Moving too close to a player with the opposite colour to yourself will cause you both to die in a wonderful explosion.</li>
                  <li>Immediately after the bosses teleport they will channel an explosion (Lunar/Shadow Tempest) that will one shot any players in the wrong position.  You are only protected from this explosion if you position yourself on the side of the room with the boss of the opposite colour to yourself.</li>
                </ul>
              </li>
              <li><b>Conversion</b> - The bosses both pray and three players in each group will get converted (whoever has aggro will avoid this mechanic).  This conversation changes the targeted players colour so if you were dark/blue then you will become light/yellow.  This is indicated by a circle of the upcoming colour under your feet and, if you have combat cues turned on in the settings, some text alerting you that you are being converted.</li>
              <li><b>Teleport</b> - The bosses will vanish and reappear at the entrance and exit of the room, which side each boss is on is random.</li>
              <li><b>Lunar/Shadow Tempest</b> - Immediately after the bosses reappear they will channel an attack which will one shot any player that is positioned on their side of the room who has the same colour as them e.g. if you have the dark blue colour (Shadow Aspect) and are on the same side of the room as Vashai when the channel ends the explosion will kill you.  After these explosions all players will lose their debuffs and thus lose their colours.</li>
              <li><b>Final Countdown</b> - When one boss is killed four additional adds will spawn and the boss will pray to channel one final explosion.  All players will lose their colours (and protection from the explosion) and will have twenty seconds to kill the remaining boss before the channel ends and wipes the group.</li>
              <li><b>Adds</b> - Both bosses summon adds that share their own colours and the same damage reduction applies if you attack those with the same colour to yourself.  The dark adds (Will of Vashai) are ranged enemies with a hard hitting frontal cone attack which shoots three small AoEs along the floor at the targeted player (Dark Torrent).  The light adds (Rage of S'Kinrai) are melee adds that perform the same interruptible, beam attack: Lunar Destruction, which will stun the targeted player.  The number of adds that spawn in after each teleport phase increases as the fight goes on; first you will have one of each then one, two, two, three, three, then four until the fight ends.  All of these adds can be pulled.</li>
            </ul>
          </li>
        </ul>
        <div class="spoiler">
          <input type="checkbox" class="spoiler-button">
          <div class="spoiler-head">Strategies</div>
          <div class="spoiler-body">
            <p>Due to the unique mechanics here the group will need to split into two six-player teams (one healer and one tank in each) and each team will focus on the boss with the opposite colour to that which they are assigned.  The room itself has a dark and light side which is split by a line of candles running across the centre.  Half of the group should start on the dark side while the other half remains in the light.  It does not matter which tank taunts which boss but this should be decided beforehand and the tanks should pull their chosen boss to them with a single taunt.  Shortly after the pull both bosses will start praying which debuffs the closest six players to them assigns those players with their colour.  During this prayer the tanks should taunt the opposite boss but remain on their side of the room, this will effectively swap the bosses around and cause the boss of the opposite colour to move to the correct group (e.g. the group that is given the dark colour will now have the light boss), allowing them to deal damage.</p>
            <p>When players are converted they should quickly move to the opposite side of the room and join the other group (they will now share the colour of this groups members and the boss attacking this group will be of the opposite colour).  A predefined direction to dictate player movement is a good idea here to avoid players running into others with opposite colours; most groups will move clockwise and so we will assume this is the chosen direction here.</p>
            <p>After the bosses teleport players should look to the door on their side of the room, wait for the boss to appear there and quickly make a decision on whether they need to move to the otherside of the room or not.  If the boss you have been attacking appears on your side of the room you do not need to move.  If the opposite boss (the boss that shares your colour) appears on your side then you do need to move quickly to the otherside to avoid getting killed by the explosion.  Immediately after the explosion everyones debuffs will disappear and the bosses will perform another prayer to assign new colours.  As with the initial pull, tanks can now taunt the boss on the other side of the room (during this prayer) so that the opposite coloured boss will run to their side (swap bosses).</p>
            <p>It is recommended that the light boss is turned away from the group to avoid cleave damage and positioned in such a way that allows the group members to cross over to the otherside when required.  The dark boss will drop large negate fields that should be positioned against the wall where possible to avoid cluttering up the arena.  You should aim to start with the dark boss a little left of the door (if you are facing the door on your side from the middle) and move clockwise each time a negate is dropped.  Positioning in this manner will always move you closer to the middle of the room in case you do need to move during the teleport.</p>
            <p>When the adds spawn in the tank with the light boss (S'Kinrai) should use a ranged taunt to aggro all the light adds and all players should watch out for their channeled attacks as they will need to be interrupted quickly.  The dark adds should be pulled in by the tank with the dark boss (Vashai) and taunted to try to keep them facing away from the group in order to avoid their conal attack.  The adds can spawn far away from the tanks so it can be incredibly helpful to have some DDs with pull abilities (DK Chains or Silver Leash) in order to help pull in the adds if the tanks are struggling.  It is recommended to focus the adds, even if they are not stacked on the boss, as they can cause issues, especially later in the fight when four of them can spawn in.</p>
            <p>You should aim to watch both bosses healthbars throughout the fight to try and kill them as close together as possible to avoid wiping to the Final Countdown mechanic.  We typically handle this by calling the health percentage of each boss during the fight and if one is going down more quickly we either stop damage on that boss or ensure any ultimates are only dropped on the boss with more health.  Once one boss dies additional adds spawn in so the tank that no longer has a boss to deal with can taunt the adds and try to keep them busy while the group drops everything they have on the remaining boss in order to kill it within the alloted time (20s).</p>
          </div>
        </div>
      </div>
      <div class="section" data-description="five">
        <h2>Arena Two</h2>
        <img src="{{ site.baseurl }}/images/trials/mol/panthers.jpg" alt="Maw of Lorkhaj - Panthers" />
        <p>Engaging with the enemies through the next gate will start the next arena.  The pace of this one is controlled by the group but a wipe will result in having to restart it.  You will have two large cats to deal with intially (mechanics described below) and after this there will only be Khajiit that you have come across before and they can be handled in the same way (although there are sometimes quite a few to deal with).  There is a chain at the top of each of the wooden ramps and pulling each one will spawn in enemies on that side of the room in three waves (they do not need to be pulled at the same time but this can be done if you want to increase the difficulty).</p>
        <ul>
          <li><b>Colossal Sar-m'Athra</b> - These behave the in a similar manner to the smaller cats but only have one attack (Deadly Claw) which really is deadly; this will one-shot anyone that gets hit by it.  These cats will only attack the player they target (they cannot be CC'd or taunted) indicated by the dark blue beam rising from the players head.  After a short while or if the targeted player dies the cats will choose another target and repeat this until they are dead.</li>
        </ul>
        <div class="spoiler">
          <input type="checkbox" class="spoiler-button">
          <div class="spoiler-head">Strategies</div>
          <div class="spoiler-body">
            <p>The safe method of dealing with the cats is simply have the targeted players run away and the rest of the group follows while attacking them.  They move quite quickly and their attacks have a fair range so it advisable to turn away from them and move away quickly if you are targeted.  Players often die here because they believe they can out manoeuvre the cats while still doing damage.  There is a trick here to force particular players to get aggro of these cats initially by utilising range.  If you have your whole group stack in the corner on the left after entering the gate, the two players chosen to get aggro can move towards the enemies to initiate the pull and once they have the colours the rest of the group follow.  This allows the tanks (typically) to get aggro, hold the cats in a central location and dodge roll the attacks.  This is much riskier but does allow the group to burn the cats down much more quickly if it's done correctly.</p>
            <p>For the next enemy waves it is advised to start with one chain (one DD can go up one of the ramps and pull the chain) at a time.  Once the chain is pulled enemies will spawn in front of that platform and they should be dealt with as before: one tank takes the Savage/s away and the group focuses the Sun-Eaters first.  If the other tank can stack everything on the Sun-Eaters then everything can be burnt down together.  Once cleared, the second chain can be pulled and a very similar three waves of enemies spawn in.  More advanced groups can pull both of these chains at the same time (this is also an achievement: Unchained Ambush) which will result in the enemies spawning in on both sides.  These enemies do not automatically aggro, however, so can still be killed spearately.  While clearing one side additional waves can spawn in on the opposite side so this can be quite a lot more difficult.</p>
          </div>
        </div>
      </div>
      <div class="section" data-description="six">
        <h2>Final Hallway</h2>
        <p>The next door leads to a long, dark hallway which is perfect for an ambush.  Stepping forward will initiate the pull and you will have the same Khajiit enemies you have already faced spawning in at different locations in three waves.  Additionally you will have Cursed Monks continously spawning in at the entrance and exit of the hallway, running towards a random player and exploding; dealing moderate damage in an AoE.  The mechanics for each of the enemies has already been explained in the first section of this guide along with methods of handling them so I won't repeat that here.</p>
      </div>
      <div class="section" data-description="seven">
        <h2>Final Boss - Rakkhat</h2>
        <img src="{{ site.baseurl }}/images/trials/mol/rakkhat.jpg" alt="Maw of Lorkhaj - Rakkhat" />
        <p>Rakkhat is a monstrous Grievous Twilight (a beefier version of those seen in Imperial City) with very powerful attacks.  During this fight the main tank will need to mitigate a lot of damage and the group will need to tread carefully and coordinate well to avoid killing each other.  There is an additional area (often called the "Backyard") through the blue portal-type doorway on the far side of the room which requires a couple of group members to complete a challenge within a time limit at certain points during the fight to avoid a wipe.  Nowadays, most groups do not see an additional phase of this fight known as the "Lunar Phase" as DPS creep allows this to be bypassed by many groups.  If the DPS is lower, however, this is another phase you should be aware of and will be described below.</p>
        <ul>
          <li><b>Environment/Phases</b>
            <ul>
              <li><b>Pads</b> - It's hard to miss the large pad in the centre of the room where the boss spawns and the surrounding eight pads.  Once the fight starts the pad on the far side of the room will glow gold while all of the others turn blue.  As the fight progresses the gold glow will move clockwise to the next pad and the pad that was gold will turn blue.  These colours have two very important mechanics:
                <ul>
                  <li><b>Gold glow</b> - The first player to step onto a pad that is glowing gold will receive a Lunar Bastion buff that provides huge mitigation and is essential to survive Rakkhats direct attacks.  I believe this buff can be switched to another player if the buffed player dies or leaves the pad and another player steps onto it.</li>
                  <li><b>Dark blue, cloudy glow</b> - Any player that touches these pads will receive a curse similar to that on the first fight.  This curse does not kill you after a set duration, however, but does apply a healing debuff and apply a small DoT.  This curse is only removed when the affected player dies or stands on one of the cleanse pad located in the corners of the room (these pads only refresh once the Lunar Phase has been completed, however).  Performing an action that afflicts you with a curse while you have a curse already will kill you (e.g. standing on a blue pad or entering the portal doorway).</li>
              </li>
              <li><b>Dro-m'Athra Hulk</b> - One of these adds will spawn from the centre pad when Rakkhat activates pads two, four, six and eight.  It has two attacks that need to be dealt with:
                <ul>
                  <li><b>Thunderous Roar</b> - The Hulk lets out a scream that will stun everyone around him and cause moderate damage.  This can be interrupted and can be devastating if a player is stunned while dealing with another heavy-hitting mechanic.</li>
                  <li><b>Thunderous Smash</b> - This attack operates similarly to that of the Savages that you encountered previously.  The tank will get debuffed from this attack and have their armor weakened, if they are hit three times in a row by this attack then it will kill them.</li>
                </ul>
              </li>
              <li><b>Backyard/Running</b> - When Rakkhat activates the third, fifth and seventh pads six shadowy figures will rise up from the centre pad.  These six figures indicate hidden Void Callers that are present in the Backyard area and they are channeling an attack which will wipe the group if it is not interrupted.  To stop this attack players will need to enter the Backyard, expose and kill these Void Callers within a time limit.  Each time a Void Caller is killed its corresponding shadowy figure disappears from the main boss room.  Its position on the centre pad indicates roughly where it is located in the Backyard; there will be two on the left, two in the middle and two on the right.  The runners will obtain a synergy when passing through the portal doorway which can be used to put out the blue fires found within bowls scattered throughout the Backyard.  Once the fire is out at a particular location the Void Caller will be revealed if they were hidden there and can then be killed.  Passing through the portal door also afflicts players with the curse (the same as touching a blue pad) so they will need to cleanse when returning.</li>
              <li><b>Lunar Phase</b> - If the boss is not pushed into the execute phase (12% health remaining) by the time he reaches the eighth pad the Lunar Phase will start.  Rakkhat will rise up high into the air, all of the pads will glow gold and provide the Lunar Bastion buff to the first player to stand on each one (the middle pad will supply this buff to up to four players).  Any player that is not on a pad will get projectiles shot at them from Rakkhat while he is hovering.  An elite enemy will spawn on each of the smaller, gold pads and anyone standing on the middle pad will get access to a synergy called Celestial Purge which can be used on an enemy.  Using the synergy will channel a beam onto that enemy, dealing damage and debuff the enemy causing them to take a lot more damage.  Once this phase ends the fight will start again from the beginning but the boss will not regain any of his health.  Any of the elite enemies that are not killed will need to be dealt with.</li>
            </ul>
          </li>
          <li><b>Rakkhats Attacks</b>
            <ul>
              <li><b>Dark Barrage</b> - The boss brings his hands together and then turns his palms out towards the player with aggro.  This shoots out a barrage of projectiles that hit incredibly hard and will pass through the targeted player hitting anyone else in its trajectory.</li>
              <li><b>Changing Pads</b> - When the boss jumps up and curls into a ball before moving to the centre of the current pad it indicates that he is going to activate the next.  You will see the next pad, in a clockwise direction, glow gold.</li>
              <li><b>Lunar Smash</b> - With the next pad activated (glowing gold) the boss will perform a powerful ground slam on the current pad which will deactivate it (turn it blue).  This will do a lot of damage to anyone on the pad and they will get cursed if they don't die.  After this the boss will jump to whoever has aggro.</li>
              <li><b>Dark Empowerment</b> - The boss turns to the Hulk and starts casting an interruptible channel.  If it is not interrupted it will empower the Hulk.</li>
              <li><b>Darkness Falls (Meteors)</b> - When the boss spreads his wings and raises both hands into the air several group members will be targeted with falling projectiles.  The player with aggro will always get targeted as well as the two (three on hardmode) players away from the boss.  These are indicated by an AoE around that player and they can be kited, dropping them off and moving out of the AoE before the projectile hits.</li>
              <li><b>Thrashing Wings</b> - The boss will jump and spin slightly with his wings, hover for a second and then slam down onto the group and attack with his wings.  When he lands he will throw back any players that are not blocking.</li>
              <li><b>Execute</b> - At 12% the boss will move to the centre large pad in the middle of the room, cease attacking and begin channeling/summoning.  During this phase the large pad will lose its colour and no longer apply a curse to players but all outside (smaller) pads will be blue.  Shortly after he moves to the middle a blue orb will spawn on pad one (the first pad that turned gold) and link to the boss via a blue beam.  This orb increases the boss' resistances further but can be disrupted/removed if it is touched by a player.  Every few seconds an orb will spawn on a pad in this manner, starting from pad one moving clockwise each time.  All other mechanics (described below) will be ongoing during the execute phase.</li>
            </ul>
          </li>
        </ul>
        <h2>Hardmode</h2>
        <p>There is nothing mechanically different in this fight for the hardmode but everything hits harder so it is a fair step up in difficulty.</p>
        <div class="spoiler">
          <input type="checkbox" class="spoiler-button">
          <div class="spoiler-head">Strategies</div>
          <div class="spoiler-body">
            <p>I'll cover two approaches to this fight that are commonly used.  The first is a safer approach and the second is a more optimised but riskier tactic that will be harder with lower DPS.  A couple of things are common for both approaches:</p>
            <ul>
              <li>Each group member should be assigned a position in the centre square before starting so you are not stacked up on top of each other.  We typically put two DDs at the end of each of the blade tracks, healers on opposite corners and tanks on the other corners.  Remember your positions and get there as soon as possible in execute.</li>
              <li>Only two terminals need to be killed to avoid a one-shot from Terminal Feedback and organising which terminals you will kill will help you stay together as a group.  Typically we would opt to always turn right when navigating the corridors.</li>
              <li>In execute everyone should stick to their role and trust the others; there needs to be enough damage here as your healers will not be able to sustain indefinitely.  Tanks can supply additional healing with Echoing Vigor and Healing Orbs but DDs should focus on parsing on the boss here rather than shielding etc.</li>
            </ul>
            <ol>
              <li>The whole group, excluding the main tank, positions themselves directly underneath the boss' left arm (fire) up on the platform to the right (as you face the boss).  The main tank taunts the boss and stands directly in front of him, blocking the Stomp of his left foot and tanking the damage from the blades of his right arm.  The group damages the boss until 90% and then takes damage off the boss (you may need to focus the boss a little more to push him to 87% but usually DoTs will accomplish this, you do not want to push the boss to 85% yet) and focuses on the adds which can be picked up by the off tank and taken to the corner of the platform towards the centre of the room.  This will allow the healers to keep an eye on the group and main tank but keep damage off of the boss.  Once the adds are dead the group can push the boss to 85% forcing him to the middle.  The group will need to jump down to the main tank immediately after this and can focus their damage where the boss was positioned as a terminal will pop up here.  Once this terminal is down the group should move together to another terminal (it makes sense to turn right as you will be in position for the next boss phase) and burn it down.  Here you can stay together and stay alive making sure you are away from the edges (poison) and healing through the blades and meteors.  Make sure that nobody is attacking the boss during this phase as damage is reflected (this includes pets)!
              Once the boss starts to move to the new position the group can once again move up to the platform under his left arm and repeat this process.  In execute (25%) the group should move to their positions quickly and burn the boss down before they get killed.  If there are adds still alive you can ease damage on the boss before 25% to kill them as you did previously.  Otherwise the tank can take them to his corner in execute and play with them there.</li>
              <li>The group stacks directly behind the main tank and makes sure to block the stomp of the boss' left foot.  One DD or a healer starts up on the platfrom below the boss' left arm (fire) and positions themselves directly underneath the arm to avoid taking damage from the fire.  The off tank takes position on the platform under the boss' right arm and kites it around waiting for the adds to spawn.  The group keeps up damage on the boss, aiming to push from 90%-87% veru quickly to spawn in the adds closely together.  The off tank lets the melee adds run down to the group (they will nearly always aggro someone in the group) and the main tank picks these up.  The off tank taunts the adds on the opposite platform and positions themselves towards the top of the ramp leading to the boss, this should force the adds to run down the ramp behind the boss on their side to get line of sight.  Once they are down the ramp the boss should be at 85% and moving towards the middle, the adds are grouped up close to the terminal and the group can drop all of their damage to burn down everything together.  Here you can either split off some DDs with a healer to kill another terminal or all move as one group (this can depends a little on group DPS).  This can be repeated for each phase and execute remains the same as the previous strategy.</li>
            </ol>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
