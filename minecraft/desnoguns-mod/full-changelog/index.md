---
layout: page
title: DesnoGuns Mod full changelog
excerpt: "DesnoGuns Mod full changelog"
page-level-ads: true
---


**DesnoGuns Mod r021**
{% highlight text %}
- FIX: volume option not applied to miniguns
- FIX: explosion too powerful due to changes in the latest versions of MCPE
- UPDATE: smoother aiming animation
{% endhighlight %}

**DesnoGuns Mod r020**
{% highlight text %}
- UPDATE: full support for 1.0.0 (use the latest version of BlockLauncher)
- FIX: huge lags when shooting explosive arrows in the air
- FIX: lags caused by arrows on the ground
- FIX: wrong health damage when hitting the mob multiple times
- FIX: bouncing back arrows workaround not working
{% endhighlight %}

**DesnoGuns Mod r019**
{% highlight text %}
- NEW: support 0.16.x (check on the Play Store if you're using the latest version of BlockLauncher!)
- NEW: the Iron Sights update!
- NEW: some guns will show their iron sight when aiming (currently available for AK47, AUG, Desert Eagle, FNSCAR, Mini-Uzi, MP5, P90, Skorpion)
- NEW: option for disabling iron sight if you don't like them
- FIX: explosions not destroying blocks
- ADDONS: fix custom guns with buttonType "on_touch_with_wait" not shooting when using an aim image
- ADDONS: add isIronSight property that must be set to true when using an iron sight and not a full-screen scope for the gun (see Example Addon)
{% endhighlight %}

**DesnoGuns Mod r018**
{% highlight text %}
- NEW: a new Sniper Rifle, the M40A3 Night Vision
- NEW: Night Binoculars
- NEW: Jungle Camo Armor
- UPDATE: the Juggernaut is now stronger than the Diamond Armor but it also adds a slowness effect
- UPDATE: more realistic binoculars images
- FIX: the UI of the mod and of the guns now is closed when opening the inventory or the chat menu
- FIX: fixed Sniper Ammo item not added in the creative inventory
- ADDONS: new APIs for Addons Developers! Support for a custom image when aiming (customAimImageLayerPath String), night vision effect when aiming (hasNightVision boolean), custom sound of the countdown when using bullet type "normal_explosive_on_time" (countdownSoundExplosiveOnTime String)
{% endhighlight %}

**DesnoGuns Mod r017**
{% highlight text %}
- FIX: workaround fix for crash at startup caused by a bug of BlockLauncher with armors. I had to remove the Juggernaut (temporarily) to fix the problem
{% endhighlight %}

**DesnoGuns Mod r016**
{% highlight text %}
- FIX: fixed lags when shooting and improved performance
- FIX: other bug fixes
{% endhighlight %}

**DesnoGuns Mod r015**
{% highlight text %}
- UPDATE: added ammunition items and the medical kit in the food & potions tab in the creative inventory
- FIX: fixed sounds interruptions
- FIX: fixed crash when clicking the reload text while shooting
{% endhighlight %}

**DesnoGuns Mod r014**
{% highlight text %}
- FIX: finally fixed the arrows bouncing back bug! (only with BlockLauncher 1.12.3 or up)
- FIX: fixed a critical bug when creating addons
- UPDATE: reload in creative now is enabled by default (can be disabled in Settings)
- UPDATE: some sounds improvements and changes
{% endhighlight %}

**DesnoGuns Mod r013**
{% highlight text %}
- NEW: easier installation, with just one .modpkg file that can be imported in BlockLauncher in the ModPE section
- UPDATE: offline sounds installation
- UPDATE: better information UI for guns specifications when using addons
- FIX: binoculars not craftable
- FIX: fixed a bug that showed the user a non-existent error with addons
{% endhighlight %}

**DesnoGuns Mod r012**
{% highlight text %}
- NEW: support for Minecraft PE 0.14.0
- NEW: support for DesnoGuns addons, a new way to add new guns in the game for everyone!
- NEW: Ray Gun
- NEW: Binoculars
- NEW: Zoom Binoculars (Pro item)
- UPDATE: added the Juggernaut armor to the creative inventory
- FIX: many bugs fixed
{% endhighlight %}

**DesnoGuns Mod r011**
{% highlight text %}
- NEW: support for Minecraft PE 0.13.1
- WARNING: since BlockLauncher is not yet updated for 0.13.1 grenades are buggy
{% endhighlight %}

**DesnoGuns Mod r010**
{% highlight text %}
- NEW: added the Multiple Rocket Launcher
- UPDATE: added a smoke trail behind bullets of rocket launchers
- FIX: fixed explosive bullets sometimes exploding in air
- FIX: enchanted golden apple and other items were recognized as guns
- FIX: fixed the crash with the Minecraft style buttons
{% endhighlight %}

**DesnoGuns Mod r009**
{% highlight text %}
- NEW: support for Minecraft PE 0.13.x
- UPDATE: add blindness effect for the smoke grenade
- UPDATE: add immersive mode support
- FIX: some IDs have been changed to fix a bug of the Creative inventory, IDs changed: AK47, AK74, AT4, AUG, Bizon
{% endhighlight %}

**DesnoGuns Mod r008**
{% highlight text %}
- NEW: support for Minecraft PE 0.12.x
{% endhighlight %}

**DesnoGuns Mod r007**
{% highlight text %}
- NEW: Crossbow
- NEW: Crossbow Explosive
- NEW: Smoke Grenade
- NEW: Riot Shield
- NEW: MSR (pro item)
- UPDATE: many IDs changed! (IDs changed: all the ammunitions and these items: Molotov, Fragment Grenade, Grenade, Medical Kit, Parachute, Knife, DesnoGuns Info, .44Magnum)
- FIX: fixed Settings section not working on Android 4.0
- FIX: fixed a crash with grenades when leaving the game
- FIX: fixed volume options not applied to reload sounds and miniguns
{% endhighlight %}

**DesnoGuns Mod r006**
{% highlight text %}
- NEW: Minecraft style for UIs
- NEW: new option in Settings to enable Minecraft style for the "fire" and "aim" buttons
- NEW: volume option in Settings
- NEW: slightly better animation when aiming with a Sniper Rifle
- NEW: volume of sound based on the distance from the source (for Molotov and Incendiary Grenade Launcher)
- UPDATE: The Juggernaut armor now doesn't override the Chain armor (IDs changed!)
- UPDATE: code re-written in many parts and improved: this should increase performance when loading the script at startup
- FIX: fixed disappearing items from the creative menu
- FIX: fixed the "double tap fast the aim button" bug that caused glitches with zoom
- FIX: fixed shadows and collision size of grenades
- FIX: fixed a graphical glitch that was happening when using other Texture Packs at the same time
{% endhighlight %}

**DesnoGuns Mod r005**
{% highlight text %}
- NEW: support for Minecraft PE 0.11.x
- NEW: compatibility with Android M
- UPDATE: some IDs have been changed because some of them were overriding beetroot and related items, IDs changed: DesnoGuns Info, .44Magnum, Grenade, Fragment Grenade, Molotov.
- FIX: fix the "resurrector knife" bug
- FIX: fix the "shooting while reload" bug
- FIX: fix the "parachute not working on grass" bug
- FIX: before, on some devices, while aiming with a sniper rifle there was one line of pixels not black. Now it has been fixed
{% endhighlight %}

**DesnoGuns Mod r004**
{% highlight text %}
- UPDATE: items and guns moved in the Tool category in the Creative inventory
- NEW: new weapon: .44 Magnum
- NEW: new armor: Juggernaut
- NEW: option in Settings to switch the position of the "fire" and "aim" buttons
- UPDATE: improvements in the Settings page
- FIX: fix bug of sounds installation when there isn't any Internet connection available
- FIX: guns now render vertically instead of horizontally in the third person view
{% endhighlight %}

**DesnoGuns Mod r003**
{% highlight text %}
- NEW: automatic sounds installation
- NEW: added recoil for all the guns
- NEW: new weapon: Flamethrower
- NEW: new weapon: Minigun Explosive
- NEW: new weapon: Makarov
- NEW: new weapon: AA-12 (pro item)
- NEW: new weapon: Incendiary Grenade Launcher (pro item)
- NEW: added texture pack with bullet texture instead of arrow
- NEW: option in Settings to enable reloading for guns also in Creative
- NEW: option in Settings to enable instant reload in Creative (only when reload in Creative is enabled)
- NEW: option to display the gun's name near the ammo text
- NEW: added an Easter Egg :P
- UPDATE: updated the Medical Kit with a new UI
- UPDATE: improved memory management
- UPDATE: improved start-up speed
- UPDATE: added sound when the parachute opens
- UPDATE: added sound when you try to shoot but the ammo is 0
- UPDATE: guns are displayed in alphabetical order in the Creative inventory
- FIX: fix molotov didn't burn grass
- FIX: fix shadow for buttons in Android Lollipop
{% endhighlight %}

**DesnoGuns Mod r002**
{% highlight text %}
- FIX: gun's sounds won't be displayed in your music player
- FIX: other bug fixes (here more informations https://bitbucket.org/Desno365/desnoguns-mod/commits/de888e7d698451d049e66c74f27e3f8598c6a5c9 )
{% endhighlight %}

**DesnoGuns Mod r001**
{% highlight text %}
- Initial release
{% endhighlight %}


<br>Return to the DesnoGuns Mod web page:

<div markdown="0"><a href="{{ site.url }}/minecraft/desnoguns-mod/#changelog" class="btn">DesnoGuns Mod</a></div>

