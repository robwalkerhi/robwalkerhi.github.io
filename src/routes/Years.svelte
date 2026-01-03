<script lang="ts">
    import Month from './Month.svelte'

	let {selectedRingId} = $props();
</script>

<div class="flex flex-col space-y-3 mt-8">
{#if selectedRingId === 1}
    <Month month="April">
        Turn 1 years old, I am a blob.
    </Month>
{/if}
{#if selectedRingId === 2}
    <Month month="April">
        Turn 2 years old, likely start babbling a couple words.
    </Month>
{/if}
{#if selectedRingId === 3}
    <Month month="April">
        Turn 3 years old, start anunciating.
    </Month>
{/if}
{#if selectedRingId === 4}
    <Month month="April">
        Turn 4 years old.
    </Month>
{/if}
{#if selectedRingId === 5}
    <Month month="April">
        Turn 5 years old.
    </Month>
{/if}
{#if selectedRingId === 6}
    <Month month="September">
        Start Grade 1 at the York School.
    </Month>
{/if}
{#if selectedRingId === 7}
    <Month month="September">
        Start Grade 2 at the York School.
    </Month>
{/if}
{#if selectedRingId === 8}
    <Month month="September">
        Start Grade 3 at the York School.
    </Month>
{/if}
{#if selectedRingId === 9}
    <Month month="September">
        Start Grade 4 at the York School.
    </Month>
{/if}
{#if selectedRingId === 10}
    <Month month="September">
        Start Grade 5 at UCC.
    </Month>
{/if}
{#if selectedRingId === 11}
    <Month month="September">
        Start Grade 6 at UCC.
    </Month>
{/if}
{#if selectedRingId === 12}
    <Month month="January">
        Concussion from skiing.
    </Month>
    <Month month="September">
        Start Grade 7 at UCC.
    </Month>
{/if}
{#if selectedRingId === 13}
    <Month month="September">
        Start Grade 8 at UCC.
    </Month>
{/if}
{#if selectedRingId === 14}
    <Month month="September">
        Start Grade 9 at UCC.
    </Month>
    <Month month="November">
        Join the crew team.
    </Month>
{/if}
{#if selectedRingId === 15}
    <Month month="September">
        Start Grade 10 at UCC.
    </Month>
{/if}
{#if selectedRingId === 16}
    <Month month="September">
        Start Grade 11 at UCC.
    </Month>
{/if}
{#if selectedRingId === 17}
    <Month month="September">
        Start Grade 12 at UCC.
    </Month>
{/if}
{#if selectedRingId === 18}
    <Month month="May">
        Decide to take a Gap Year before college.
    </Month>
    <Month month="September">
        Start working at startup.
    </Month>
{/if}
{#if selectedRingId === 19}
    <Month month="February">
        Stop working at startup, start travelling in Southeast Asia.
    </Month>
    <Month month="May">
        Stop travelling in Southeast Asia, take Canadian Securities Course.
    </Month>
    <Month month="September">
        Start first year at Harvard.
    </Month>
{/if}
{#if selectedRingId === 20}
    <Month month="September">
        Start sophomore year at Harvard.
    </Month>
{/if}
{#if selectedRingId === 21}
    <Month month="March">
        COVID pandemic hits, move home during spring break.
    </Month>
    <Month month="May">
        Decide to take gap year during COVID.
    </Month>
    <Month month="September">
        Start working at Shopify.
    </Month>
{/if}
{#if selectedRingId === 22}
    <Month month="June">
        Stop working at Shopify.
    </Month>
    <Month month="July">
        Travel to Michigan and Boston and Montana.
    </Month>
    <Month month="August">
        Lead digital FOP.
    </Month>
    <Month month="September">
        Start junior year at Harvard.
    </Month>
{/if}
{#if selectedRingId === 23}
    <Month month="September">
        Start senior year at Harvard.
    </Month>
{/if}
{#if selectedRingId === 24}
    <Month month="May">
        Graduate from Harvard.
    </Month>
    <Month month="June">
        Hike the Sawtooths, hike the Skyline Trail, hike the Rockwall Trail.
    </Month>
    <Month month="June">
        Visit Prague and Munich, hike the TMB, visit Berlin.
    </Month>
    <Month month="August">
        Hike an ECT section (solo), hike the Collegiate Peaks West, canoe trip in Boundary Waters, support FOP base camp.
    </Month>
    <Month month="September">
        Move to SF, romantic weekend.
    </Month>
    <Month month="October">
        Start working at Meta.
    </Month>
{/if}
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