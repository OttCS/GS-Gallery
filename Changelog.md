<h1>GravityShade Changelog</h1>
<h2>Version 21.12.20</h2>
<code>Major Changes</code>
<br><br>
<p><b>Underwater Fog!</b> Not perfect at the moment, but completely usable. Known bug is that the sky isn't fogged underwater, which leads to some weird visuals.</p>
<p><b>Dynamic Handlights!</b> Dynamic handlights have been added, but as a result the original method of block lighting has changed. I'm working on getting blocklighting to where it was and keeping handlighting.</p>
<p>Fog fixed for any render distance, from 2 to 32 chunks.</p>
<code>Minor Changes</code>
<br><br>
<p>Horizon fog-band bug fixed. An alpha-blending issue on water led to a very visible line where water was fog-occluded, opacity is not smoothly transitioned between on water.</p>
<p>Better sky is in progress.</p>
<p>Separate reflections for "metallic part" blocks (ie chests and rails) are also in progress.</p>
<h2>Version 21.12.16</h2>
<code>Major Changes</code>
<br><br>
<p><b>FOG HAS BEEN ADDED!</b> While slightly buggy at the moment, optimizations ARE in place to reduce work done on fog-occluded textures.</p>
<p><b>Shadowmapping has been reduced.</b> Shadowmap scale is now set to 1024 at a distance of 4 chunks, which more machines are capable of handling.</p>
<code>Minor Fixes</code>
<br><br>
<p>Fog color set to match the time of day and the horizon color.</p>
<p>Sunset lighting has been adjusted to be a less purple, more coral hue.</p>
<p>Emissive ores now have separate block IDs to allow for better a emissive effect.</p>
<h2>Version 21.12.14</h2>
<p>Code is now loosely based on the Sildurs Enhanced Default shaderpack</p>
<p>Lighting now has proper coloring:
<br>~ Overworld sky light changes realistically based on the time of day.
<br>~ Block light has been changed to be warmer, but blend better with the environment.
<br>~ End lighting has been changed to a less-greenish tone.
<br>Feel free to change these values inside the shaderpack.
</p>
<p>Emissive blocks get tonemapped separately for better visual effect.</p>
<p>Calmer and nicer-looking water has been added.</p>
<p>Emissive Ores have been added, inspired by Complementary Shaders.</p>
<p>Shadowmapping has been added, see note below regarding the resolution.</p>
<p><b>NOTE: </b>Default shadowmap resolution is 2048. This is generally attainable with medium graphics cards, but do feel free to change this value or disable shadows in the settings file.</p>
