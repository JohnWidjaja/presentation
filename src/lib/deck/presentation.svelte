<script lang="ts">
	import Slide from './slide.svelte';
	import Code from './code.svelte';
	import Slides from './slides.svelte';
	import Markdown from './markdown.svelte';
	import Icon from './icon.svelte';
	import Rightarrow from '$lib/icons/rightarrow.svelte';
	import Domicon from '$lib/icons/domicon.svelte';
	import Exampleone from './exampleone.svelte';
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
			<li class="text-orange-600">Building A Simple Svelte Application</li>
		</ul>
	</Slide>
	<Slide animate
		><ul>
			<li>Introduction to Svelte.js</li>
			<li>How Svelte Differs from Other Frameworks</li>
			<li>Key Features of Svelte</li>
			<li>Building A Simple Svelte Application</li>
			<li class="text-orange-600">Svelte Ecosystem and Community</li>
		</ul>
	</Slide>
	<Slide animate
		><ul>
			<li>Introduction to Svelte.js</li>
			<li>How Svelte Differs from Other Frameworks</li>
			<li>Key Features of Svelte</li>
			<li>Building A Simple Svelte Application</li>
			<li>Svelte Ecosystem and Community</li>
			<li class="text-orange-600">Pros and Cons of Svelte</li>
		</ul>
	</Slide>
	<Slide animate
		><ul>
			<li>Introduction to Svelte.js</li>
			<li>How Svelte Differs from Other Frameworks</li>
			<li>Key Features of Svelte</li>
			<li>Building A Simple Svelte Application</li>
			<li>Svelte Ecosystem and Community</li>
			<li>Pros and Cons of Svelte</li>
			<li class="text-orange-600">A brief introduction to SvelteKit</li>
		</ul>
	</Slide>
	<Slide animate
		><ul>
			<li>Introduction to Svelte.js</li>
			<li>How Svelte Differs from Other Frameworks</li>
			<li>Key Features of Svelte</li>
			<li>Building A Simple Svelte Application</li>
			<li>Svelte Ecosystem and Community</li>
			<li>Pros and Cons of Svelte</li>
			<li>A brief introduction to SvelteKit</li>
			<li class="text-orange-600">Use Cases and Real-world Examples</li>
		</ul>
	</Slide>
	<Slide animate
		><ul>
			<li>Introduction to Svelte.js</li>
			<li>How Svelte Differs from Other Frameworks</li>
			<li>Key Features of Svelte</li>
			<li>Building A Simple Svelte Application</li>
			<li>Svelte Ecosystem and Community</li>
			<li>Pros and Cons of Svelte</li>
			<li>A brief introduction to SvelteKit</li>
			<li>Use Cases and Real-world Examples</li>
			<li class="text-orange-600">Conclusion and Q&A</li>
		</ul>
	</Slide>
</Slide>
<Slide>
	<Slide animate><p class="text-orange-600 text-6xl">Introduction to Svelte.js</p></Slide>
	<Slide animate>
		<ul class="text-4xl">
			<li class="text-orange-600">
				Svelte is a new front-end, open source JavaScript framework for making interactive webpages.
				It was developed by Rich Harris and released in 2016.
			</li>
		</ul>
	</Slide>
	<Slide animate>
		<ul class="text-4xl">
			<li>
				Svelte is a new front-end, open source JavaScript framework for making interactive webpages.
				It was developed by Rich Harris and released in 2016.
			</li>
			<br />
			<li class="text-orange-600">
				It originated from Ractive.js and was designed to succeed Ractive. The first version of
				Svelte was basically Ractive, but with a compiler.
			</li>
		</ul>
	</Slide>
	<Slide animate>
		<ul class="text-4xl">
			<li>
				Svelte is a new front-end, open source JavaScript framework for making interactive webpages.
				It was developed by Rich Harris and released in 2016.
			</li>
			<br />
			<li>
				It originated from Ractive.js and was designed to succeed Ractive. The first version of
				Svelte was basically Ractive, but with a compiler.
			</li>
			<br />
			<li class="text-orange-600">
				It is a compiler that takes your declarative components and converts them into efficient
				JavaScript that surgically updates the DOM.
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
					<th><p class="text-sky-300" /></th>
					<th><p class="text-red-500" /></th>
				</tr>
				<tr>
					<th />
					<td
						>It complies the application code during the build process and eliminates the need for a
						large runtime library.</td
					>
					<td />
					<td />
				</tr>
				<tr>
					<th>DOM</th>
					<td>No Virtual DOM</td>
					<td />
					<td />
				</tr>
				<tr>
					<th>Library Size</th>
					<td>1.6 KB</td>
					<td />
					<td />
				</tr>
				<tr>
					<th>Language</th>
					<td>JavaScript, Typescript</td>
					<td />
					<td />
				</tr>
				<tr>
					<th>Documentation</th>
					<td>Moderate</td>
					<td />
					<td />
				</tr>
				<tr>
					<th>Learning Curve</th>
					<td>Easy</td>
					<td />
					<td />
				</tr>
			</table>
		</div>
	</Slide>
	<Slide animate>
		<div>
			<table class="w-full text-sm sm:text-base md:text-lg lg:text-xl xl:text-2xl">
				<tr>
					<th>Framework</th>
					<th><p class="text-orange-600">Svelte</p></th>
					<th><p class="text-sky-300">React</p></th>
				</tr>

				<th />
				<td
					>It complies the application code during the build process and eliminates the need for a
					large runtime library.</td
				>
				<td
					>Stronger emphasis on runtime efficiency, using a virtual DOM and reconciliation algorithm
					for updates.</td
				>
				<td />
				<tr />
				<tr>
					<th>DOM</th>
					<td>No Virtual DOM</td>
					<td>Virtual DOM</td>
					<td />
				</tr>
				<tr>
					<th>Library Size</th>
					<td>1.6 KB</td>
					<td>42.2 KB</td>
					<td />
				</tr>
				<tr>
					<th>Language</th>
					<td>JavaScript, Typescript</td>
					<td>JavaScript, TypesScript, JSX</td>
					<td />
				</tr>
				<tr>
					<th>Documentation</th>
					<td>Moderate</td>
					<td>Poor</td>
					<td />
				</tr>
				<tr>
					<th>Learning Curve</th>
					<td>Easy</td>
					<td>Gradual</td>
					<td />
				</tr>
			</table>
		</div>
	</Slide>
	<Slide animate>
		<div>
			<table class="w-full text-sm sm:text-base md:text-lg lg:text-xl xl:text-2xl">
				<tr>
					<th>Framework</th>
					<th><p class="text-orange-600">Svelte</p></th>
					<th><p class="text-sky-300">React</p></th>
					<th><p class="text-red-500">Angular</p></th>
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
					<td>JavaScript, Typescript</td>
					<td>JavaScript, TypesScript, JSX</td>
					<td>Typescript</td>
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
	<Slide animate><p class="text-6xl">Hello World</p></Slide>
	<Slide animate>
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
	</Slide>
	<Slide animate>
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
	</Slide>
	<Slide animate>
		<p class="text-orange-600">Svelte</p>
		<Code id="code" lines>
			{`
            <h1>Hello World</h1>
        `}
		</Code>
	</Slide>
</Slide>
<Slide>
	<Slide animate><p class="text-orange-600 text-6xl">Execution Speed</p></Slide>
	<Slide>
		<img
			src="https://www.softermii.com/assets/uploads/blog/20221014/svelte-vs-angular-vs-react@2x.webp"
			alt="Execution Speed"
			class="scale-125"
		/>
	</Slide>
	<Slide animate><p class="text-orange-600 text-6xl">Startup Test</p></Slide>
	<Slide>
		<img
			src="https://www.softermii.com/assets/uploads/blog/20221014/svelte-vs-react-vs-angular@2x.webp"
			alt="Startup Test"
			class="scale-125"
		/>
	</Slide>
	<Slide animate><p class="text-orange-600 text-6xl">Memory Allocation Test</p></Slide>
	<Slide>
		<img
			src="https://www.softermii.com/assets/uploads/blog/20221014/svelte-and-react@2x.webp"
			alt="Memory Allocation Test"
			class="scale-125"
		/>
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
		<p class="text-red-500">Reactive declarations use use <span class="text-orange-600">$</span></p>
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
			RRunning arbitrary statements <span class="text-orange-600">reactively</span>
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
	<Slide>t</Slide>
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
			<li class="text-orange-600">Less Code Needed</li>
		</ul>
	</Slide>
	<Slide animate
		><ul>
			<li>No Virtual DOM</li>
			<li>Less Code Needed</li>
			<li class="text-orange-600">Easy to Learn</li>
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
		<div class="flex place-content-center">
			<div
				data-id="box-1"
				class="w-[300px] h-[300px] bg-red-500 flex items-center justify-center rounded-lg"
			>
				Into Ideal JavaScript Code
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
							h1.textContent = 'Hello ${name}!';
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
	<Slide animate><p class="text-6xl">Less <span class="text-orange-600">Code</span></p></Slide>
	<Slide><Exampleone /></Slide>
</Slide>
<!-- <Markdown>
	{`
    ## Markdown
    Hello
    `}
</Markdown> -->