<svelte:head>
    <link rel="icon" type="image/png" href="/square.png" />
</svelte:head>

<a href="https://hackclub.com" target="_blank" rel="noopener noreferrer" class="fixed top-0 left-0 z-50">
    <img src="https://assets.hackclub.com/flag-orpheus-left.png" alt="Hack Club" class="w-50"/>
    
</a>
 
<section class="min-h-screen flex flex-col items-center justify-center relative">
    <h1 class="font-bubblegum text-white text-7xl sm:text-9xl text-center leading-none mb-8 drop-shadow-[0_8px_0_rgba(0,0,0,0.35)]" style="-webkit-text-stroke: 5px black; text-stroke: 5px black; paint-order: stroke fill;">duckduckduck</h1>
    <h2 class="font-bubblegum text-3xl pb-1 text-white text-center max-w-4xl px-4 drop-shadow-[0_2px_4px_rgba(0,0,0,0.45)]" style="text-shadow: 0 0 12px rgba(0,0,0,0.35), 0 2px 3px rgba(0,0,0,0.5);">
        Make a duck-themed project, get a rubber duck sent to you! Ends July 16th.
    </h2>
    <div class="flex gap-25 mt-5">
        <button class="font-bubblegum bg-white text-black text-3xl py-6 px-18 rounded-lg transition-all cursor-pointer shadow-[0_6px_0_rgba(0,0,0,0.2)] hover:shadow-[0_3px_0_rgba(0,0,0,0.2)] hover:translate-y-[3px] active:shadow-none active:translate-y-[6px] border-2 border-black/10" on:click={() => document.getElementById('faq').scrollIntoView({ behavior: 'smooth' })}>FAQ</button>
        <a href="https://hackclub.com" target="_blank" rel="noopener noreferrer" class="font-bubblegum bg-white text-black text-3xl py-6 px-18 rounded-lg transition-all shadow-[0_6px_0_rgba(0,0,0,0.2)] hover:shadow-[0_3px_0_rgba(0,0,0,0.2)] hover:translate-y-[3px] active:shadow-none active:translate-y-[6px] border-2 border-black/10">Submit!</a>
    </div>
    <h2 class="font-bubblegum text-2xl pb-1 text-white text-center max-w-4xl px-4 drop-shadow-[0_2px_4px_rgba(0,0,0,0.45)] absolute bottom-4 left-0 right-0 mx-auto" style="text-shadow: 0 0 12px rgba(0,0,0,0.35), 0 2px 3px rgba(0,0,0,0.5);">
        A Hack Club YSWS program by @dld
    </h2>
</section>

<div class="flex flex-col items-center justify-center min-h-screen px-10" id="faq"> 
    <div class="w-full max-w-2xl px-4">
        <h2 class="font-bubblegum text-5xl text-white text-center pb-5 drop-shadow-[0_2px_4px_rgba(0,0,0,0.45)]" style="text-shadow: 0 0 12px rgba(0,0,0,0.35), 0 2px 3px rgba(0,0,0,0.5);">FAQs</h2>
        <details class="mb-3 bg-white rounded-lg shadow-[0_4px_0_rgba(0,0,0,0.15)] border-2 border-black/10 transition-shadow hover:shadow-[0_4px_10px_rgba(0,0,0,0.25)]">
            <summary class="font-bubblegum text-xl text-black p-4 cursor-pointer">What is duckduckduck?</summary>
            <p class="font-bubblegum px-4 pb-4 text-black">duckduckduck is a Hack Club YSWS program where you design a duck-related project, and we send you a rubber duck from HQ!</p>
        </details>
        <details class="mb-3 bg-white rounded-lg shadow-[0_4px_0_rgba(0,0,0,0.15)] border-2 border-black/10 transition-shadow hover:shadow-[0_4px_10px_rgba(0,0,0,0.25)]">
            <summary class="font-bubblegum text-xl text-black p-4 cursor-pointer">What can I make?</summary>
            <p class="font-bubblegum px-4 pb-4 text-black">Make any project you want, as long as it's duck themed and original. This could be a duck hunt game, a virtual duck pet, a custom modeled duck, or anything else! It's up to interpretation, so feel free to think outside the box.</p>
        </details>
        <details class="mb-3 bg-white rounded-lg shadow-[0_4px_0_rgba(0,0,0,0.15)] border-2 border-black/10 transition-shadow hover:shadow-[0_4px_10px_rgba(0,0,0,0.25)]">
            <summary class="font-bubblegum text-xl text-black p-4 cursor-pointer">Do I need to use Hackatime?</summary>
            <p class="font-bubblegum px-4 pb-4 text-black">Hackatime is recommended, but not required. If you don't use Hackatime, please make sure you're keeping track of your time some other way!</p>
        </details>
        <details class="mb-3 bg-white rounded-lg shadow-[0_4px_0_rgba(0,0,0,0.15)] border-2 border-black/10 transition-shadow hover:shadow-[0_4px_10px_rgba(0,0,0,0.25)]">
            <summary class="font-bubblegum text-xl text-black p-4 cursor-pointer">When does duckduckduck end?</summary>
            <p class="font-bubblegum px-4 pb-4 text-black">duckduckduck ends Thursday, July 16th at noon EST (12:00 PM).</p>
        </details>
        <details class="mb-3 bg-white rounded-lg shadow-[0_4px_0_rgba(0,0,0,0.15)] border-2 border-black/10 transition-shadow hover:shadow-[0_4px_10px_rgba(0,0,0,0.25)]">
            <summary class="font-bubblegum text-xl text-black p-4 cursor-pointer">Is this double dippable?</summary>
            <p class="font-bubblegum px-4 pb-4 text-black">No, duckduckduck cannot be double dipped with any other Hack Club programs.</p>
        </details>
        <details class="mb-3 bg-white rounded-lg shadow-[0_4px_0_rgba(0,0,0,0.15)] border-2 border-black/10 transition-shadow hover:shadow-[0_4px_10px_rgba(0,0,0,0.25)]">
            <summary class="font-bubblegum text-xl text-black p-4 cursor-pointer">I've finished my project!</summary>
            <p class="font-bubblegum px-4 pb-4 text-black">Great! It's time to <a href="https://hackclub.com" target="_blank" rel="noopener noreferrer" class="underline cursor-pointer">submit</a>!</p>
        </details>
        <details class="mb-3 bg-white rounded-lg shadow-[0_4px_0_rgba(0,0,0,0.15)] border-2 border-black/10 transition-shadow hover:shadow-[0_4px_10px_rgba(0,0,0,0.25)]">
            <summary class="font-bubblegum text-xl text-black p-4 cursor-pointer">I have some other questions!</summary>
            <p class="font-bubblegum px-4 pb-4 text-black">Ask in the <a href="https://hackclub.enterprise.slack.com/archives/C0BGZHQV3RU" target="_blank" rel="noopener noreferrer" class="underline cursor-pointer">#duckduckduck</a> channel in the Slack!</p>
        </details>
    </div>
</div>
