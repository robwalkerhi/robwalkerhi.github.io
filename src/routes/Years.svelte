<script lang="ts">
    import Month from './Month.svelte'

	let {selectedRingId} = $props();
</script>

<div class="flex flex-col space-y-3 mt-8">
{#if selectedRingId === 25}
    <Month month="January">
        Tahoe skip trip, start growing Indigo and Lavendar and Tobacco from seed.
    </Month>
    <Month month="February">
        Lake Louise ski trip.
    </Month>
    <Month month="March">
        Trail run in Santa Cruz Mountains, brunch at Alice's, play tennis,
        visit the DeYoung for the first time.
    </Month>
    <Month month="April">
        Party bus birthday party, Taco Bell Cantina for the first time.
    </Month>
    <Month month="May">
        Swan Lake at SF symphony, Stanford Law Prom, trail run before work, 
        Big Sur camping trip, Saya Gray at Rickshaw Stop.
    </Month>
    <Month month="June">
        Fred Again at Stanford Frost Ampitheater (and simultaneously learn who Fred Again is), 
        Alexander Stewart at Cafe du Nord, Stanford Law graduatation.
    </Month>
    <Month month="July">
        Yosemite weekend trip, beautiful sunrise, Tahoe summer trip.
    </Month>
    <Month month="August">
        Thru-hike the JMT, visit Toronto.
    </Month>
    <Month month="September">
        Diplo's run club, Hozier at Shoreline, SEB at Rickshaw Stop.
    </Month>
    <Month month="October">
        Seattle work trip, Langdon Hall birthday trip, Tahoe fall trip.
    </Month>
    <Month month="November">
        Sequoia NP during Thanksgiving, ceramics at Stanford, RKS at Bill Graham, sprint at work.
    </Month>
    <Month month="December">
        Stop sprinting at work, fly back to Toronto.
    </Month>
{/if}
{#if selectedRingId === 26}
    <Month month="January">
        Decide to move apartments, try private pilates lessons, first Mycological Society of SF meeting.
    </Month>
    <Month month="February">
        Start new physio, see complete works of Revel at the SF symphony, 
        hike 16mi along Dipsea Trail, attend a film festival, 
        apartment hunt, 
        Sheng Wang at Palace of Fine Arts, 
        travel to New Zealand, try canyoneering, 
        run 8 miles to mail a letter from NZ to SF, hire movers.
    </Month>
    <Month month="March">
        Get promoted to IC4 at work, move apartments, see Maude Latour at the Independent, 
        see Flipturn at Fox, do a Barry's Bootcamp, 
        see a Killing My Lobster comedy sketch on my own,  
        do watercolors on the top of Mt. Tam.
    </Month>
    <Month month="April">
        Drag show at Oasis, experience heartbreak and spin out, 
        run a half marathon through GGP, fall ill w a bad cold, 
        go out for dinners, reconnect w friends, 
        attend SF MoMA Art Bash after-party, celebrate a birthday in Dolores, 
        camp on Angel Island.
    </Month>
    <Month month="May">
        See the Berkeley Botanical Gardens, finish making homemade cigars, 
        host a Tobacco Party w said cigars, 
        host a bday party for myself for the first time, start improv lessons at Endgames, 
        see Overmono at 1015 Folsom, 
        run Bay to Breakers, take a ferry to vallejo and have BBQ.
    </Month>
    <Month month="June">
        Stern Grove, hotpot, bar trivia, 
        Ocean Beach bonfire, game night, 
        weekend Yosemite trip (Clouds Rest), 
        perform improv, skydiving, SF pride, 
        Lake Street Dive at Frost Ampitheater.
    </Month>
    <Month month="July">
        Wine bar, bar trivia, retreat in marin, host a DnD one-shot campaign, 
        travel to Lake Louise for Mom/Dad's 65th and 70th bdays, 
        hike and picnic on Mt. Tam, first time at banya, 
        knitting circle.
    </Month>
    <Month month="August">
        Brother's bachelor party in NYC, scavenger hunt, 
        book club, OSL (Tyler, Doechii, Hozier, Wallows, and more), 
        make skits, perform improv, day trip, Japanese Breakfast.
    </Month>
    <Month month="September">
        Brother's wedding, transition teams at work, 
        visit NYC, host a fanfiction competition, 
        design and professionally print said fanfiction, 
        weekend trip in Desolation Wilderness, 
        film festival.
    </Month>
    <Month month="October">
        Fall ill, spa day (eyebrows threaded, pedicures, banya), 
        work v hard, see community theater, see Wagner's Parsifal, 
        meet two famous SF muralists, perform improv on Halloween, 
        dance at Mission Danceoween.
    </Month>
    <Month month="November">
        Work hard, see Small Pools at the Independent, 
        camp in Point Reyes, 
        make sake, 
        visit Toronto for American Thanksgiving.
    </Month>
    <Month month="December">
        Book club, sell clothes at a party, cave rave in sutro baths, 
        lightscape in GGP, 
        Lake Merced holiday relay (4.5mi in 7min/mi), 
        presidio polar plunge, murder mystery party in Oakland, 
        visit Calgary, downhill/nordic ski in Lake Louise.
    </Month>
{/if}
</div>