---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
redirect_from:
  - /projects/
---

{% include base_path %}

<style>
.research-project {
  margin: 0 0 4.5rem;
  padding: 0 0 4.5rem;
  border-bottom: 1px solid #e5e5e5;
}

.research-project:last-of-type {
  margin-bottom: 0;
  padding-bottom: 0;
  border-bottom: 0;
}

.research-project h2 {
  margin-bottom: 1.4rem;
}

.research-project__body {
  display: grid;
  grid-template-columns: minmax(220px, 0.9fr) minmax(0, 1.35fr);
  gap: 2rem;
  align-items: start;
}

.research-project__body--reverse {
  grid-template-columns: minmax(0, 1.35fr) minmax(220px, 0.9fr);
}

.research-project__image {
  margin: 0;
}

.research-project__image img {
  display: block;
  width: 100%;
  height: auto;
  border: 1px solid #dddddd;
  border-radius: 4px;
}

.research-project__image figcaption {
  margin-top: 0.45rem;
  font-size: 0.8em;
  color: #777777;
}

.research-project__text p:first-child {
  margin-top: 0;
}

@media (max-width: 768px) {
  .research-project {
    margin-bottom: 3.25rem;
    padding-bottom: 3.25rem;
  }

  .research-project__body,
  .research-project__body--reverse {
    grid-template-columns: 1fr;
    gap: 1.25rem;
  }

  .research-project__body--reverse .research-project__image {
    order: 1;
  }

  .research-project__body--reverse .research-project__text {
    order: 2;
  }
}
</style>

<section class="research-project">
  <h2>Unprecedented Extreme Precipitation Risk Under Climate Warming</h2>
  <div class="research-project__body">
    <figure class="research-project__image">
      <img src="{{ base_path }}/images/research/precipitation-placeholder.svg" alt="Placeholder for an extreme precipitation research figure">
      <figcaption>Placeholder for future research figure.</figcaption>
    </figure>
    <div class="research-project__text">
      <p>This project quantifies how anthropogenic warming increases the likelihood of record-breaking extreme precipitation events worldwide by combining climate model projections with population exposure and socioeconomic vulnerability. We show that low- and lower-middle-income countries face disproportionately higher risks, with projected exposure to unprecedented storms increasing by up to an order of magnitude by +4 °C warming due to the combined effects of intensifying hazards, rapid population growth, and limited adaptive capacity.</p>
    </div>
  </div>
</section>

<section class="research-project">
  <h2>Drought Synchronicity Across the United States</h2>
  <div class="research-project__body research-project__body--reverse">
    <div class="research-project__text">
      <p>This project examines when and why droughts occur simultaneously across multiple U.S. regions using high-resolution climate data from 1980–2021. We show that drought synchronicity has intensified since the early 2000s, particularly in the Great Plains and Midwest, and that atmospheric evaporative demand and large-scale climate modes (e.g., NPGO, PMM) play a key role in amplifying or suppressing these spatially connected droughts.</p>
    </div>
    <figure class="research-project__image">
      <img src="{{ base_path }}/images/research/drought-placeholder.svg" alt="Placeholder for a drought synchronicity research figure">
      <figcaption>Placeholder for future research figure.</figcaption>
    </figure>
  </div>
</section>

<section class="research-project">
  <h2>Investigating Stratopheric Circulation in the DoE climate model E3SMv2 (CMIP6 protocol)</h2>
  <div class="research-project__text">
    <p>There is a need to understand how well our climate models capture stratospheric motions, especially motivated by climate intervention techniques, such as stratospheric aerosol injections. This work investigates the stratopheric circulation of the DoE's earth system model <a href="https://e3sm.org/">E3SMv2</a>, run under <a href="https://wcrp-cmip.org/cmip-phase-6-cmip6/">CMIP6</a> guidelines. This work will be used in assessing the variability of the stratosphere and is funded by the <a href="https://www.sandia.gov/cldera/">CLDERA Grand Challenge</a>.</p>
  </div>
</section>

<section class="research-project">
  <h2>Proportional-Integral Feedback Controller for simulation Stratospheric Aerosol Injections</h2>
  <div class="research-project__text">
    <p>Simulating stratospheric aerosol injections (SAI) can range from a simple "dimming" of the sun's radiation to representing the complete chemical interactions that occur in the stratosphere. This work uses a proportional-integral feedback controller, adapted from <a href="https://github.com/dan-visioni/feedback_suite">dan-visioni</a> that adjusts the rate of the aerosol injection at specified locations based on simultaneously controlling for three temperature metrics. This was to be used in a modified model of E3SMv2, that included a more complete chemical description of the stratosphere. This work was done at Sandia National Laboratory in the <a href="https://sandia.jobs/albuquerque-nm/intern-future-of-research-for-climate-earth-energy-forcee-rd-undergraduate-summer/80ACD05058474C108C6F99AAABD24CC8/job/?vs=7104&utm_source=PostDocJobs.com-DE&utm_medium=Other&utm_campaign=PostDocJobs.com">FORCEE internship</a>.</p>
  </div>
</section>

<section class="research-project">
  <h2>Precipitation Variance Spectra in Rain Gauges vs Models</h2>
  <div class="research-project__body">
    <figure class="research-project__image">
      <img src="{{ base_path }}/images/research/spectra-placeholder.svg" alt="Placeholder for a precipitation spectra research figure">
      <figcaption>Placeholder for future research figure.</figcaption>
    </figure>
    <div class="research-project__text">
      <p>Precipitation projections in climate models contain large amounts of uncertainty and suffer from a "drizzle effect", where the model output precipitation is always lightly raining. As climate models increase their spatial resolution, we would hope to more accurately capture the more extreme precipitation events that have profound impacts on our society. This study looks at the power spectrum of the precipitation variance of low, medium, and high resolution models and compares them to rain gauge information. The goal is to understand if increasing resolution can capture the high frequency high intensity rain events that we see in observation.</p>
    </div>
  </div>
</section>
