---
layout: page
title: Hel Ra Citadel
permalink: /trials/hel-ra-citadel/
---
<div class="flex-parent">
  <div class="input-flex-container">
    <input type="radio" class="first node" name="timeline-dot" data-description="notable-enemies" checked>
    <div class="dot-info above" data-description="notable-enemies">
      <span class="label">Notable Enemies</span>
    </div>
    <input type="radio" class="node" name="timeline-dot" data-description="boss-1">
    <div class="dot-info below" data-description="boss-1">
      <span class="label">Boss 1</span>
    </div>
    <input type="radio" class="node" name="timeline-dot" data-description="left">
    <div class="dot-info above" data-description="left">
      <span class="label">Left Route</span>
    </div>
    <input type="radio" class="node" name="timeline-dot" data-description="boss-2-1">
    <div class="dot-info above" data-description="boss-2-1">
      <span class="label">Boss 2 (left)</span>
    </div>
    <input type="radio" class="node" name="timeline-dot" data-description="right">
    <div class="dot-info below" data-description="right">
      <span class="label">Right Route</span>
    </div>
    <input type="radio" class="node" name="timeline-dot" data-description="boss-2-2">
    <div class="dot-info below" data-description="boss-2-2">
      <span class="label">Boss 2 (right)</span>
    </div>
    <input type="radio" class="node" name="timeline-dot" data-description="horn">
    <div class="dot-info above" data-description="horn">
      <span class="label">Citadel Entrance</span>
    </div>
    <input type="radio" class="node" class="last" name="timeline-dot" data-description="boss-3">
    <div class="dot-info below" data-description="boss-3">
      <span class="label">Final Boss</span>
    </div>
    <div id="timeline-descriptions-wrapper">
      <div class="section" data-description="notable-enemies">
        <h2>Notable Enemies</h2>
        <ul>
          <li><b>Destroyers</b> - Melee enemies with two-handed weapons that carry banners (an indicator they are "elite" enemies).  They do fair damage, which can cleave, and have a frontal cone attack which knocks group members down.</li>
          <li><b>Flame-Shapers</b> - Ranged enemies also with a banner.  These will perform an interruptible channeled attack which shoots fireballs at multiple members of the group.</li>
          <li><b>Gargoyles</b> - Melee enemies who hit pretty damn hard.  They have a large frontal cone attack (breath/shout) which will turn anyone caught in it to stone and an AoE continuous ground slam attack which will do a lot of damage to anyone inside the circle (melee range).</li>
        </ul>
        <div class="spoiler">
          <input type="checkbox" class="spoiler-button">
          <div class="spoiler-head">Strategies</div>
          <div class="spoiler-body">
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse non venenatis sem. Integer bibendum blandit varius. Maecenas rhoncus dignissim vulputate. Vivamus et libero consectetur, tempor enim non, sagittis erat. Nullam maximus neque ligula, in porta quam suscipit non. Nam maximus ut ante eu malesuada. Pellentesque auctor quis augue quis eleifend. Donec tincidunt porta ante ac consequat.</p>
          </div>
        </div>
      </div>
      <div class="section" data-description="boss-1">
        <h2>Boss 1 - Ra Kotu</h2>
        <img src="{{ site.baseurl }}/images/trials/hrc/ra-kotu.jpg" alt="Boss 1 - Ra Kotu" />
        A huge air atronach that spawns in with 3 additional enemies and is typically pulled immediately; don't expect to be able to stop to change skills etc!<br>
        His notable attacks are as follows:  
        <ul>
          <li><b>Gusts of wind</b> - Small red AoEs that target a single group member (but can quickly change targets) and will move around the group (following whichever group member they are targeting at the time) continuously though the fight.  A single group member can get targeted by multiple gusts at a time and these will do small amounts of damage to anyone standing in the circle.</li>
          <li><b>Heavy Attack</b> - Indicated by the usual "yellow sparks" the boss wraps his arms around his body and unleashes a powerful attack on whoever has aggro.</li>
          <li><b>Six Sword Assault</b> - The boss throws out four large AoEs in several directions (his "corners") that return the same way and deal damage to anyone in their path.</li>
          <li><b>Sword Swirl</b> - At 35% (and at regular intervals thereafter if the fight goes on for a while) the boss will form a large AoE around him and continuously spin his swords around dealing large amounts of damage to any group member caught inside.</li>
        </ul>
        After defeating Ra Kotu the gate he came out of (somehow) will be accessible. When 6 group members go inside the gate will close and the other 6 are locked out.  To the right is another door that will now be open and the remaining group members can proceed through here.
      </div>
      <div class="section" data-description="left">
        <h2>Left Route</h2>
        Your progress here is controlled by the other group as they will have access to levers which open the gates blocking your route.  You will meet mostly the same enemies here with one addition (see below) but many of them will keep respawning until the right side have finished their section and unlocked the gate for you to move on.
        <ul>
          <li><b>Welwa</b> - A mild introduction to the enemies you'll see on the boss for this side.  They perform a rear kick attack which does moderate damage in a cone behind them.</li>
        </ul>
      </div>
      <div class="section" data-description="boss-2-1">
        <h2>Boss 2 - Yokeda Rok'dun</h2>
        <img src="{{ site.baseurl }}/images/trials/hrc/rokdun.jpg" alt="Boss 2 - Yokeda Rok'dun" />
        An archer that specialises in ranged attacks and controls animal companions who aid him in battle.
        <ul>
          <li><b>Release Flame</b> - A flame arrow will be shot towards a group member which hits the ground and splits into four flame trails, spreading out in different directions from the point of impact.</li>
          <li><b>Teleport</b> - The boss will "jump" away and reappear elsewhere in the arena, looking for the ranged advantage.</li>
          <li><b>Welwas</b> - An upgraded version of the welwas you saw previously - "Armored Welwa" who hit a bit harder and will be summoned continuously throughout the fight (if the fight lasts a long time you will have many of these to deal with).  After being alive for some time these will enrage, growing larger and hitting a lot harder.  Upon death, the boss will resurrect his fallen companions allowing them to rejoin the battle.</li>
        </ul>
      </div>
      <div class="section" data-description="right">
        <h2>Right Route</h2>
        No new enemies for you to face on this side while you make your way up and along the outer walls.  After each pack of enemies you will have access to a lever which will open a gate allowing the other group to proceed further.  Destroying the catapults as you go prevents additional damage being rained down on your team-mates.
      </div>
      <div class="section" data-description="boss-2-2">
        <h2>Boss 2 - Yokeda Kai</h2>
        <img src="{{ site.baseurl }}/images/trials/hrc/kai.jpg" alt="Boss 2 - Yokeda Kai" />
        A fire mage (a superior flame-shaper that you met previously) that specialises in all things flammable.
        <ul>
          <li><b>Impulse</b> - An AoE ability that spreads out from beneath the bosses feet that does a lot of damage to anyone caught inside.</li>
          <li><b>Meteor</b> - A huge, flaming rock is dropped on a random group member dealing a lot of damage to anyone hit.  After impact, a burning AoE is left on the ground.</li>
          <li><b>Inferno</b> - The same interruptible attack that the flame-shapers do.  A channeled ability that shoots fireballs at random group members.</li>
          <li><b>Fiery Deception</b> - The boss splits into four, three of which are clones of himself.  Each will spawn in the same location each time and mimic the boss; performing the Impulse and Inferno ability as described above. After performing their Inferno attack they will despawn, leaving only the real boss again.</li>
        </ul>
      </div>
      <div class="section" data-description="horn">
        <h2>Citadel Entrance</h2>
        Prepare to face a collection of all of the enemies you have faced before.  Using the horn at the back of the room will pull even more enemies into the fight and aggro them immediately, it does give you an achievement though.  There are a few heavy sacks and chests here and through the corridor towards the last boss.
      </div>
      <div class="section" data-description="boss-3">
        <h2>Boss 3 - The Warrior</h2>
        <img src="{{ site.baseurl }}/images/trials/hrc/warrior.jpg" alt="Boss 3 - The Warrior" />
        Despite being one of the oldest, this is still one of the hardest hitting bosses in the game.  The Warrior puts a lot of pressure on the tank, requires some full group co-ordination and a fair lot of effort from your healers to complete it.  There are two circles (to the left and right of the boss as you enter the room), the left increases health recovery and the right increases damage done for anyone standing inside (including the enemies). These are generated by the statues on either side and will be destroyed one by one during the fight.
        <ul>
          <li><b>Channeled Swipes</b> - A series of heavy slashes that each do a lot of damage to whoever has aggro and to anyone standing close enough in front of him.</li>
          <li><b>Shield Throw</b> - A random group member will be targeted, indicated by a large rectangular AoE field, and the boss will throw his shield like a boomerang in that direction. It will hit for a lot of damage and knock down anyone not blocking; it hits on the way out and on the return.</li>
          <li><b>Leap</b> - The boss leaps to any group member that is far enough away from him and does a lot of damage on impact.  This mechanic only happens if someone is standing far away, however.  He will sometimes leap to the statues when he destroys them or leap back from the statues once they have been destroyed (as he is now far from the group).</li>
          <li><b>Cleave</b> - A front-facing, conal, cleave attack which does a lot of damage.  Towards execute this will be done after each shield throw and typically will be in the direction that he threw his shield.</li>
          <li><b>Shehai Storm</b> - The boss points his sword upwards and channels an attack that hits everyone in the group.  Each group member will get a pulsing red circle under their feet that moves with them and overlapping with another group members circle will cause you to take damage from their AoE as well.</li>
        </ul>
      </div>
    </div>
  </div>
</div>
