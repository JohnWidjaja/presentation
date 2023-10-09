<script lang="ts">
	import Slide from './slide.svelte';
	import Code from './code.svelte';
	import Slides from './slides.svelte';
	import Markdown from './markdown.svelte';
	import Icon from './icon.svelte';
	import Rightarrow from '$lib/icons/rightarrow.svelte';
	import Domicon from '$lib/icons/domicon.svelte';
	import Exampleone from './exampleone.svelte';
	import Exampletwo from './exampletwo.svelte';
	import Examplethree from './examplethree.svelte';
	import Examplefour from './examplefour.svelte';
	import Examplefive from './examplefive.svelte';
</script>

<Slide animate>
	<p class="text-8xl">Svelte.js</p>
</Slide>

<Slide animate>
	<p class="text-orange-600">Svelte.js</p>
	<p>A reactive JavaScript Framework</p>
</Slide>

<Slide animate>
	<p class="text-purple-600">Presented By: Team Violet</p>
</Slide>

<Slide animate>
	<p class="text-purple-600">Presented By: Team Violet</p>
	<p>John Widjaya</p>
	<p>Felipe Zukauskas</p>
	<p>Shang Yang</p>
	<p>Natsasion Srithiowat</p>
</Slide>
<Slide>
	<Slide><p class="text-orange-600 text-6xl">Agenda</p></Slide>
	<Slide animate
		><ul>
			<li class="text-orange-600">Introduction to Svelte.js</li>
		</ul>
	</Slide>
	<Slide animate
		><ul>
			<li>Introduction to Svelte.js</li>
			<li class="text-orange-600">How Svelte Differs from Other Frameworks</li>
		</ul>
	</Slide>
	<Slide animate
		><ul>
			<li>Introduction to Svelte.js</li>
			<li>How Svelte Differs from Other Frameworks</li>
			<li class="text-orange-600">Key Features of Svelte</li>
		</ul>
	</Slide>
	<Slide animate
		><ul>
			<li>Introduction to Svelte.js</li>
			<li>How Svelte Differs from Other Frameworks</li>
			<li>Key Features of Svelte</li>
			<li class="text-orange-600">Use Cases and Real-world Examples</li>
		</ul>
	</Slide>
	<Slide animate
		><ul>
			<li>Introduction to Svelte.js</li>
			<li>How Svelte Differs from Other Frameworks</li>
			<li>Key Features of Svelte</li>
			<li>Use Cases and Real-world Examples</li>
			<li class="text-orange-600">Pros and Cons of Svelte</li>
		</ul>
	</Slide>
	<Slide animate
		><ul>
			<li>Introduction to Svelte.js</li>
			<li>How Svelte Differs from Other Frameworks</li>
			<li>Key Features of Svelte</li>
			<li>Use Cases and Real-world Examples</li>
			<li>Pros and Cons of Svelte</li>
			<li class="text-orange-600">Building A Simple Svelte Application</li>
		</ul>
	</Slide>
	<Slide animate
		><ul>
			<li>Introduction to Svelte.js</li>
			<li>How Svelte Differs from Other Frameworks</li>
			<li>Key Features of Svelte</li>
			<li>Use Cases and Real-world Examples</li>
			<li>Pros and Cons of Svelte</li>
			<li>Building A Simple Svelte Application</li>
			<li class="text-orange-600">Svelte Ecosystem and Community</li>
		</ul>
	</Slide>
	<Slide animate
		><ul>
			<li>Introduction to Svelte.js</li>
			<li>How Svelte Differs from Other Frameworks</li>
			<li>Key Features of Svelte</li>
			<li>Use Cases and Real-world Examples</li>
			<li>Pros and Cons of Svelte</li>
			<li>Building A Simple Svelte Application</li>
			<li>Svelte Ecosystem and Community</li>
			<li class="text-orange-600">Conclusion and Q&A</li>
		</ul>
	</Slide>
</Slide>
<Slide>
	<Slide animate><p class="text-orange-600 text-6xl">Introduction to Svelte.js</p></Slide>
	<Slide animate>
		<ul class="text-4xl">
			<li>
				Svelte is a new front-end, open source JavaScript framework for making interactive webpages.
				It was developed by Rich Harris and released in 2016.
			</li>
			<br />
			<li>
				Svelte is a new front-end, open source JavaScript framework for making interactive webpages.
				It was developed by Rich Harris and released in 2016.
			</li>
		</ul>
	</Slide>
</Slide>
<Slide>
	<Slide><p class="text-orange-600 text-6xl">How Svelte Differs from Other Frameworks</p></Slide>
	<Slide animate>
		<div>
			<table class="w-full text-sm sm:text-base md:text-lg lg:text-xl xl:text-2xl">
				<tr>
					<th>Framework</th>
					<th><p class="text-orange-600">Svelte</p></th>
					<td><p class="text-sky-300">React</p></td>
					<td><p class="text-red-500">Angular</p></td>
				</tr>
				<tr>
					<th />
					<td
						>It complies the application code during the build process and eliminates the need for a
						large runtime library.</td
					>
					<td
						>Stronger emphasis on runtime efficiency, using a virtual DOM and reconciliation
						algorithm for updates.</td
					>
					<td
						>Have a more substantial runtime presence due to the Angular runtime and core libraries.</td
					>
				</tr>
				<tr>
					<th>DOM</th>
					<td>No Virtual DOM</td>
					<td>Virtual DOM</td>
					<td>Regular DOM</td>
				</tr>
				<tr>
					<th>Library Size</th>
					<td>1.6 KB</td>
					<td>42.2 KB</td>
					<td>45 KB</td>
				</tr>
				<tr>
					<th>Language</th>
					<td>JavaScript, TypeScript</td>
					<td>JavaScript, TypesScript, JSX</td>
					<td>TypeCcript</td>
				</tr>
				<tr>
					<th>Documentation</th>
					<td>Moderate</td>
					<td>Poor</td>
					<td>Detailed</td>
				</tr>
				<tr>
					<th>Learning Curve</th>
					<td>Easy</td>
					<td>Gradual</td>
					<td>Steep</td>
				</tr>
			</table>
		</div>
	</Slide>
</Slide>
<Slide>
	<Slide animate><p class="text-orange-600 text-6xl">How Svelte Differs By Code Size</p></Slide>
	<Slide>
		<div class="flex gap-1 place-content-center">
			<div>
				<p class="text-orange-600">Svelte</p>
				<Code id="code" lines>
					{`
                    <h1>Hello World</h1>
                `}
				</Code>
			</div>
			<div>
				<p class="text-sky-300">React</p>
				<Code id="code" lines>
					{`
                    import React from 'react';
                    
                    function App() {
                        return (
                            <div>
                                Hello World
                            </div>
                        );
                    }
                `}
				</Code>
			</div>
			<div>
				<p class="text-red-500">Angular</p>
				<Code id="code" lines>
					{`
                    import { Component } from '@angular/core';
                    
                    @Component ({
                        selector: 'my-app',
                        template: '<h1>Hello World</h1>'
                    })
        
                    export class AppComponent;
                `}
				</Code>
			</div>
		</div>
	</Slide>
</Slide>
<Slide>
	<Slide>
		<p class="text-orange-600 text-4xl">Execution Speed</p>
		<img
			src="https://www.softermii.com/assets/uploads/blog/20221014/svelte-vs-angular-vs-react@2x.webp"
			alt="Execution Speed"
			class="scale-100"
		/>
	</Slide>
	<Slide>
		<p class="text-orange-600 text-4xl">Startup Test</p>
		<img
			src="https://www.softermii.com/assets/uploads/blog/20221014/svelte-vs-react-vs-angular@2x.webp"
			alt="Startup Test"
			class="scale-100"
		/>
	</Slide>
	<Slide>
		<p class="text-orange-600 text-2xl">Memory Allocation Test</p>
		<img
			src="https://www.softermii.com/assets/uploads/blog/20221014/svelte-and-react@2x.webp"
			alt="Memory Allocation Test"
			class="scale-100"
		/>
		<table class="w-full text-sm sm:text-base md:text-lg lg:text-xl xl:text-2xl">
			<tr>
				<td />
				<th><span class="text-orange-600">Svelte</span></th>
				<th><span class="text-sky-300">React</span></th>
				<th><span class="text-red-500">Angular</span></th>
			</tr>
			<tr>
				<th>Performance</th>
				<td>Most performant/faster load times</td>
				<td>Averagely performant</td>
				<td>Least performant</td>
			</tr>
		</table>
		<a class="text-xl" href="https://www.stefankrause.net/wp/"
			>Link: JavaScript Framework Benchmark Tool</a
		>
	</Slide>
</Slide>
<Slide>
	<Slide animate
		><p class="text-6xl">Key Features of <span class="text-orange-600">Svelte</span></p></Slide
	>
	<Slide animate
		><ul>
			<li class="text-orange-600">Reactive Programming Model</li>
		</ul>
	</Slide>
	<Slide animate
		><ul>
			<li>Reactive Programming Model</li>
			<li class="text-orange-600">Zero-runtime Philosophy</li>
		</ul>
	</Slide>
</Slide>
<Slide>
	<Slide animate
		><ul>
			<li class="text-orange-600">Reactive Programming Model</li>
		</ul>
	</Slide>
	<Slide
		><p>
			Svelte's Reactive programming model enables automatic updates to the user interface based on
			changes in data without the developer having to write explicit update code.
		</p></Slide
	>
	<Slide animate>
		<p class="text-red-500">Reactive declarations use <span class="text-orange-600">$</span></p>
		<Code id="code" lines>
			{`
			<scripts>
				let count = 0;​
				$: doubled = count * 2;​
				function increment() {​
				count += 1;​
				}​
			</scripts>
			`}
		</Code>
	</Slide>
	<Slide animate>
		<p class="text-red-500">
			Running arbitrary statements <span class="text-orange-600">reactively</span>
		</p>
		<Code id="code" lines>
			{`
			<scripts>​
				let count = 0;​
				$: if (count >= 10) {​
				alert('count is dangerously high!');​
				count = 0;​
				}​

				function handleClick() {​
				count += 1;​
				}​
			</scripts>
			`}
		</Code>
	</Slide>
</Slide>
<Slide>
	<Slide>
		<p>
			Zero-runtime <span class="text-orange-600">Philosophy</span>
		</p>
	</Slide>
	<Slide>
		<p>
			The Zero-runtime philosophy in Svelte revolves around the idea of shifting as much work as
			possible from the client-side runtime to compile-time, maximizing performance and minimizing
			the amount of JavaScript that needs to run in the browser to power a web application.
		</p>
	</Slide>
	<Slide>
		<p>
			This approach led to the creation of fast and efficient web applications with smaller bundle
			sizes, making it a compelling choice for modern web development.
		</p>
	</Slide>
	<Slide
		><p>
			Key Aspects of the Zero-runtime philosophy in <span class="text-orange-600">Svelte</span>
		</p></Slide
	>
	<Slide animate
		><ul>
			<li class="text-orange-600">Compile-time Components</li>
		</ul>
	</Slide>
	<Slide animate
		><ul>
			<li>Compile-time Components</li>
			<li class="text-orange-600">No Virtual DOM</li>
		</ul>
	</Slide>
	<Slide animate
		><ul>
			<li>Compile-time Components</li>
			<li>No Virtual DOM</li>
			<li class="text-orange-600">Small Bundle Sizes</li>
		</ul>
	</Slide>
	<Slide animate
		><ul>
			<li>Compile-time Components</li>
			<li>No Virtual DOM</li>
			<li>Small Bundle Sizes</li>
			<li class="text-orange-600">Faster Execution</li>
		</ul>
	</Slide>
	<Slide animate
		><ul>
			<li>Compile-time Components</li>
			<li>No Virtual DOM</li>
			<li>Small Bundle Sizes</li>
			<li>Faster Execution</li>
			<li class="text-orange-600">Reactive Declarations</li>
		</ul>
	</Slide>
	<Slide animate
		><ul>
			<li>Compile-time Components</li>
			<li>No Virtual DOM</li>
			<li>Small Bundle Sizes</li>
			<li>Faster Execution</li>
			<li>Reactive Declarations</li>
			<li class="text-orange-600">Event Delegation</li>
		</ul>
	</Slide>
	<Slide animate
		><ul>
			<li>Compile-time Components</li>
			<li>No Virtual DOM</li>
			<li>Small Bundle Sizes</li>
			<li>Faster Execution</li>
			<li>Reactive Declarations</li>
			<li>Event Delegation</li>
			<li class="text-orange-600">Animation Support</li>
		</ul>
	</Slide>
</Slide>
<Slide>
	<Slide animate
		><p class="text-6xl">
			Use <span class="text-orange-600">Cases</span> and Real-world
			<span class="text-orange-600">Examples</span>
		</p></Slide
	>
	<Slide>Enter examples here.</Slide>
</Slide>
<Slide>
	<Slide animate><p class="text-6xl">Pros of <span class="text-orange-600">Svelte</span></p></Slide>
	<Slide animate
		><ul>
			<li class="text-orange-600">No Virtual DOM</li>
		</ul>
	</Slide>
	<Slide animate
		><ul>
			<li>No Virtual DOM</li>
			<li class="text-orange-600">Easy to Learn</li>
		</ul>
	</Slide>
	<Slide animate
		><ul>
			<li>No Virtual DOM</li>
			<li>Easy to Learn</li>
			<li class="text-orange-600">Less Code Needed</li>
		</ul>
	</Slide>
	<Slide animate
		><ul>
			<li>No Virtual DOM</li>
			<li>Easy to Learn</li>
			<li>Less Code Needed</li>
			<li class="text-orange-600">Reactive by Default</li>
		</ul>
	</Slide>
</Slide>
<Slide>
	<Slide animate
		><ul>
			<li class="text-orange-600">No Virtual DOM</li>
		</ul>
	</Slide>
	<Slide>
		What does this mean? Unlike React or Angular, Svelte complies components to highly optimized
		JavaScript that directly manipulates the actual DOM.
	</Slide>
	<Slide>
		During the build, a virtual DOM is not needed. This results in faster performance and smaller
		bundle sizes.
	</Slide>
	<Slide id="boxes" animate>
		<p class="capitalize">Svelte Components</p>
		<div class="flex gap-2 place-content-center">
			<div data-id="box-1" class="w-[50px] h-[50px] bg-gray-400 rounded-lg" />
			<div data-id="box-2" class="w-[50px] h-[50px] bg-gray-400 rounded-lg" />
			<div data-id="box-3" class="w-[50px] h-[50px] bg-gray-400 rounded-lg" />
		</div>
	</Slide>

	<Slide id="boxes" animate>
		<p class="capitalize">Consists of</p>
		<div class="flex gap-2 place-content-center">
			<div
				data-id="box-1"
				class="w-[200px] h-[200px] bg-red-500 flex items-center justify-center rounded-lg"
			>
				HTML
			</div>
			<div
				data-id="box-2"
				class="w-[200px] h-[200px] bg-blue-500 flex items-center justify-center rounded-lg"
			>
				CSS
			</div>
			<div
				data-id="box-3"
				class="w-[200px] h-[200px] bg-yellow-500 flex items-center justify-center rounded-lg"
			>
				JS
			</div>
		</div>
		<p class="capitalize">Three elements</p>
	</Slide>
	<Slide id="boxes" animate>
		<div class="r-stack flex place-content-center">
			<div
				data-id="box-1"
				class="w-[300px] h-[300px] bg-red-500 flex items-center justify-center rounded-full"
			/>

			<div
				data-id="box-2"
				class="w-[200px] h-[200px] bg-red-500 flex items-center justify-center rounded-full"
			/>
			<div
				data-id="box-3"
				class="w-[100px] h-[100px] bg-red-500 flex items-center justify-center rounded-full"
			>
				Component
			</div>
		</div>
	</Slide>
	<Slide id="boxes" animate>
		<div class="flex place-content-center">
			<div
				data-id="box-1"
				class="w-[200px] h-[200px] bg-red-500 flex items-center justify-center rounded-lg"
			>
				Complies
			</div>
		</div>
	</Slide>
	<Slide id="boxes" animate>
		<div class="flex gap-2 place-content-center">
			<div
				data-id="box-1"
				class="w-[300px] h-[100px] bg-red-500 rounded-lg flex items-center justify-center"
			>
				Ideal
			</div>
			<div
				data-id="box-2"
				class="w-[300px] h-[100px] bg-red-500 rounded-lg flex items-center justify-center"
			>
				JavaScript
			</div>
			<div
				data-id="box-3"
				class="w-[300px] h-[100px] bg-red-500 rounded-lg flex items-center justify-center"
			>
				Code
			</div>
		</div>
	</Slide>
	<Slide animate>
		<div class="flex place-content-center">
			<div class="h-[200px] w-[200px]">
				<Rightarrow />
			</div>
		</div>
	</Slide>
	<Slide animate>
		<div class="items-center justify-center">
			<p>Updates Browser DOM</p>
		</div>
		<div class="flex place-content-center">
			<div class="h-[200px] w-[200px]">
				<Domicon />
			</div>
		</div>
	</Slide>
	<Slide animate>
		<p class="text-red-500">Hello World</p>
		<Code id="code" lines>
			{`
			<scripts>
				let name = 'world';
			</scripts>

			<h1 style="color:red">Hello {name}!</h1>
        `}
		</Code>
	</Slide>
	<Slide animate>
		<Code id="code" lines>
			{`
				import {
					SvelteComponent,
					detach,
					element,
					init,
					insert,
					noop,
					safe_not_equal,
					set_style
				} from "svelte/internal";

				import "svelte/internal/disclose-version";

				function create_fragment(ctx) {
					let h1;

					return {
						c() {
							h1 = element("h1");
							h1.textContent = 'Hello '${name}!';
							set_style(h1, "color", "red");
						},
						m(target, anchor) {
							insert(target, h1, anchor);
						},
						p: noop,
						i: noop,
						o: noop,
						d(detaching) {
							if (detaching) {
								detach(h1);
							}
						}
					};
				}

				let name = 'world';

				class App extends SvelteComponent {
					constructor(options) {
						super();
						init(this, options, null, create_fragment, safe_not_equal, {});
					}
				}

				export default App;
				
			`}
		</Code>
	</Slide>
</Slide>
<Slide>
	<Slide animate><p class="text-6xl">Easy to <span class="text-orange-600">Learn</span></p></Slide>
	<Slide animate
		><ul>
			<li class="text-orange-600">You only need vanilla <span class="text-red-500">HTML</span></li>
		</ul>
	</Slide>
	<Slide animate
		><ul>
			<li>You only need vanilla <span class="text-red-500">HTML</span></li>
			<li class="text-orange-600">You only need vanilla <span class="text-blue-500">CSS</span></li>
		</ul>
	</Slide>
	<Slide animate
		><ul>
			<li>You only need vanilla <span class="text-red-500">HTML</span></li>
			<li>You only need vanilla <span class="text-blue-500">CSS</span></li>
			<li class="text-orange-600">
				You only need vanilla <span class="text-yellow-500">JavaScript</span>
			</li>
		</ul>
	</Slide>
	<Slide
		><p>
			<a href="https://svelte.dev/"><span class="text-orange-600">Svelte's</span></a> documentation is
			strong and provides learners a strong foundation using their built-in tutorial.
		</p></Slide
	>
	<Slide>
		<img src="https://i.imgur.com/yvcTerN.png" alt="Svelte Tutorial" class="scale-125" />
	</Slide>
	<Slide animate>
		<p>String Interpolation</p>
		<br />
		<Code id="code" lines>
			{`
			<scripts>
				let name = 'world';
			</scripts>

			<h1 style="color:red">Hello {name}!</h1>
        `}
		</Code>
		<p class="text-red-500">Hello World</p>
	</Slide>
	<Slide animate>
		<p>Event Binding</p>
		<br />
		<Code id="code" lines>
			{`
			<scripts>
				let name = 'Bob';
			</scripts>
            <label>
                <input type="text" bind:value={name}>
            </label><p>{name}</p>    
        `}
		</Code>
		<Exampletwo />
	</Slide>
	<Slide animate>
		<p>Looping</p>
		<br />
		<Code id="code" lines>
			{`
            <scripts>
                let data = [
                    { id: '1', name: 'John' },
                    { id: '2', name: 'Zuka' },
                    { id: '3', name: 'Shang' },
                    { id: '4', name: 'Joy' }
                ];
            </scripts>

            <ul>
                {#each data as { id, name }, i}
                    <li>My name is {name} with {id}</li>
                {/each}
            </ul>
        `}
		</Code>
	</Slide>
	<Slide>
		<Examplethree />
	</Slide>
</Slide>
<Slide>
	<Slide animate><p class="text-6xl">Less <span class="text-orange-600">Code</span></p></Slide>
	<Slide><Exampleone /></Slide>
	<Slide animate>
		<p class="text-6xl">Code in <span class="text-orange-600">Svelte</span></p>
		<Code id="code" lines>
			{`
            <scripts>
                let a = 1;
                let b = 2;
            </scripts>

            <input type="number" bind:value={a} />
            <input type="number" bind:value={b} />

            <p>{a} + {b} = {a + b}</p>
        `}
		</Code>
	</Slide>
	<Slide animate>
		<p class="text-6xl">Code in <span class="text-sky-300">React</span></p>
		<Code id="code" lines>
			{`
                import { useState } from 'react';

                export default () => {
                const [a, setA] = useState(1);
                const [b, setB] = useState(2);

                function handleChange (event, setValue) {
                    const { value } = event.target;
                    setValue(value);
                };

                return (
                    <div>
                    <input type="number" value={a} onChange={(e) => handleChange(e, setA)} />
                    <input type="number" value={b} onChange={(e) => handleChange(e, setB)} />
                    <p>{a} + {b} = { parseInt(a) + parseInt(b) } </p>
                    </div>
                );
                }
        `}
		</Code>
	</Slide>
</Slide>
<Slide>
	<Slide animate
		><p class="text-6xl">Reactive by <span class="text-orange-600">Default</span></p></Slide
	>
	<Slide animate>
		<p>A Click Button</p>
		<Code id="code" lines>
			{`
                <scripts>
                let count = 0;

                function handleClick() {
                    count += 1;
                }
                </scripts>

                <button on:click={handleClick}>
                Clicked {count} {count === 1 ? 'time' : 'times'}
                </button>
        `}
		</Code>
		<Examplefour />
	</Slide>
	<Slide animate>
		<p>Conditional Rendering</p>
		<Code id="code" lines>
			{`
                <scripts>
                let x = 7;
                </scripts>

                <input type="number" bind:value={x} />

                {#if x > 10}
                <p>{x} is greater than 10</p>
                {:else if x < 5}
                <p>{x} is less than 5</p>
                {:else}
                <p>{x} is between 5 and 10</p>
                {/if}
        `}
		</Code>
		<Examplefive />
	</Slide>
</Slide>
<Slide>
	<Slide animate><p class="text-6xl">Cons of <span class="text-orange-600">Svelte</span></p></Slide>
	<Slide animate
		><ul>
			<li class="text-orange-600">Smaller Ecosystem</li>
		</ul>
	</Slide>
	<Slide animate
		><ul>
			<li>Smaller Ecosystem</li>
			<li class="text-orange-600">Lack of IDE Support</li>
		</ul>
	</Slide>
	<Slide animate
		><ul>
			<li>Smaller Ecosystem</li>
			<li>Lack of IDE Support</li>
			<li class="text-orange-600">Lack of Dev Tools</li>
		</ul>
	</Slide>
	<Slide animate
		><ul>
			<li>Smaller Ecosystem</li>
			<li>Lack of IDE Support</li>
			<li>Lack of Dev Tools</li>
			<li class="text-orange-600">Smaller Community</li>
		</ul>
	</Slide>
</Slide>
<Slide>
	<Slide animate
		><p class="text-6xl">
			Building a Simple <span class="text-orange-600">Svelte</span> Application
		</p></Slide
	>
</Slide>
<Slide>
	<Slide animate
		><p class="text-6xl">
			<span class="text-orange-600">Svelte</span> Ecosytem and Community
		</p></Slide
	>
	<Slide animate>
		<p class="text-6xl">
			<span>Libraries and Tools</span>
		</p>
	</Slide>
	<Slide animate>
		<p class="text-6xl">
			<span>Libraries and Tools</span>
		</p>
		<br />
		<ul>
			<li class="text-orange-600">SvelteKit</li>
		</ul>
	</Slide>
	<Slide animate>
		<p class="text-6xl">
			<span>Libraries and Tools</span>
		</p>
		<br />
		<ul>
			<li>SvelteKit</li>
			<li class="text-orange-600">Sapper</li>
		</ul>
	</Slide>
	<Slide animate>
		<p class="text-6xl">
			<span>Community and Documentation</span>
		</p>
	</Slide>
	<Slide animate>
		<p class="text-6xl">
			<span>Community and Documentation</span>
		</p>
		<br />
		<ul>
			<li class="text-orange-600">Svelte Society</li>
		</ul>
	</Slide>
	<Slide animate>
		<p class="text-6xl">
			<span>Community and Documentation</span>
		</p>
		<br />
		<ul>
			<li>Svelte Society</li>
			<li class="text-orange-600">Stack Overflow</li>
		</ul>
	</Slide>
</Slide>
<Slide>
	<Slide animate
		><p class="text-6xl">
			Conclusion and <span class="text-orange-600">Q&A</span>
		</p></Slide
	>
</Slide>
<!-- <Markdown>
	{`
    ## Markdown
    Hello
    `}
</Markdown> -->
