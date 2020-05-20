Where you go from here depends largely on what you wanna do with your Plugins.

If you...

{% if hide != 'overview' %}
...want to understand more about what Plugins are <span class="icon"><i class="fas fa-long-arrow-alt-right"></i></span> [Plugins: Overview][plugins-overview]
{% endif %}

{% if hide != 'services' %}
...want to provide services to the `Injector` <span class="icon"><i class="fas fa-long-arrow-alt-right"></i></span> [Plugins: Registering Services][plugins-registering-services]
{% endif %}

{% if hide != 'boot' %}
...want to run some asynchronous code when Plugins load <span class="icon"><i class="fas fa-long-arrow-alt-right"></i></span> [Plugins: Booting Up][plugins-booting]
{% endif %}

{% if hide != 'events' %}
...want to listen to events triggered by Labrador or your application <span class="icon"><i class="fas fa-long-arrow-alt-right"></i></span> [Plugins: Handling Events][plugins-event-handling]
{% endif %}

{% if hide != 'depend' %}
...want to depend on some services provided by another Plugin <span class="icon"><i class="fas fa-long-arrow-alt-right"></i></span> [Plugins: Depending on Other Plugins][plugins-depending-plugins]
{% endif %}

{% if hide != 'custom' %}
...want to implement your own `Plugin` type <span class="icon"><i class="fas fa-long-arrow-alt-right"></i></span> [Implement Custom Plugin Types][custom-plugin-types]
{% endif %}

{% if hide != 'deep' %}
...want to know more about the technicals of Plugins &amp; Pluggables <span class="icon"><i class="fas fa-long-arrow-alt-right"></i></span> [Deep Dive: Plugins &amp; Pluggables][deep-dive-plugins]
{% endif %}

[plugins-booting]: {{site.baseurl}}/tutorials/plugins-booting-up
[plugins-registering-services]: {{site.baseurl}}/tutorials/plugins-registering-services
[plugins-event-handling]: {{site.baseurl}}/tutorials/plugins-handling-events
[deep-dive-plugins]: {{site.baseurl}}/references/plugins-deep-dive
[custom-plugin-types]: {{site.baseurl}}/how-tos/implementing-custom-plugin-types
[plugins-depending-plugins]: {{site.baseurl}}/tutorials/plugins-depending-other-plugins
[plugins-overview]: {{site.baseurl}}/tutorials/plugins-overview
