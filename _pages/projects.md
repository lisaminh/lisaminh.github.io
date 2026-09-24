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
  grid-template-columns: minmax(0, 0.65fr) minmax(0, 1.35fr);
  gap: 2rem;
  align-items: start;
}

.research-project__body--reverse {
  grid-template-columns: minmax(0, 1.35fr) minmax(0, 0.65fr);
}

.research-project__image {
  margin: 0;
  width: 100%;
  max-width: 260px;
  min-width: 0;
}

.research-project__body--reverse .research-project__image {
  justify-self: end;
}

.research-project__text {
  min-width: 0;
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

.research-project__panels {
  display: grid;
  gap: 1rem;
}

.research-project__panel-label {
  display: block;
  margin-bottom: 0.25rem;
}

.research-project__math {
  white-space: nowrap;
}

.research-project__text p:first-child {
  margin-top: 0;
}

@media (max-width: 599px) {
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
    justify-self: start;
    order: 1;
  }

  .research-project__body--reverse .research-project__text {
    order: 2;
  }
}
</style>

<section class="research-project">
  <h2><a href="https://www.nature.com/articles/s43247-026-03649-y" target="_blank" rel="noopener noreferrer">Unprecedented Extreme Precipitation Risk Under Climate Warming</a></h2>
  <div class="research-project__body">
    <figure class="research-project__image">
      <a href="{{ base_path }}/images/research/uepe_exp_fig.webp" target="_blank" rel="noopener noreferrer" aria-label="Open the UEPE exposure figure at full resolution in a new tab">
        <img src="{{ base_path }}/images/research/uepe_exp_fig.webp" alt="Four maps of country-level UEPE exposure at +1.5, +2.0, +3.0, and +4.0 degrees Celsius of global warming, with a stacked area plot of exposure by income group.">
      </a>
      <!-- Edit the UEPE figure caption below. -->
      <figcaption><strong>a</strong>–<strong>d</strong>) Total country-level exposure to unprecedented extreme precipitation events (UEPEs) in billion person-events per decade at +1.5 °C, +2.0 °C, +3.0 °C, and +4.0 °C GWL. <strong>e)</strong> Stacked area plot of projected exposure to unprecedented events by income group for each GWL. Exposure is calculated according to Eq. (<a href="https://www.nature.com/articles/s43247-026-03649-y#Equ4" target="_blank" rel="noopener noreferrer">4</a>). All exposures are aggregated per decade.</figcaption>
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
      <div class="research-project__panels">
        <div class="research-project__panel">
          <strong class="research-project__panel-label">a)</strong>
          <a href="{{ base_path }}/images/research/eca_r_in.jpg" target="_blank" rel="noopener noreferrer" aria-label="Open panel a, drought synchronization strength, at full resolution in a new tab">
            <img src="{{ base_path }}/images/research/eca_r_in.jpg" alt="Panel a: Map of aggregate incoming drought coincidence rates across 20 regions of the contiguous United States.">
          </a>
        </div>
        <div class="research-project__panel">
          <strong class="research-project__panel-label">b)</strong>
          <a href="{{ base_path }}/images/research/pet_eca_r_in.jpg" target="_blank" rel="noopener noreferrer" aria-label="Open panel b, PET contributions to drought synchronization, at full resolution in a new tab">
            <img src="{{ base_path }}/images/research/pet_eca_r_in.jpg" alt="Panel b: Map of the difference between SPEI and SPI aggregate incoming drought coincidence rates across 20 regions of the contiguous United States.">
          </a>
        </div>
      </div>
      <!-- Edit the drought synchronicity figure caption below. -->
      <figcaption><strong>a)</strong> Synchronization strength indicated by aggregated incoming coincidence rates (<span class="research-project__math"><i>r</i><sub>agg</sub><sup>in</sup></span>) for each region. The “Incoming” rate is the weighted fraction of how often the region's drought is preceded by another region's drought. <strong>b)</strong> Contributions of PET to synchronization rates, highlighted by the difference between SPEI and SPI aggregate incoming rate (<span class="research-project__math">Δ<i>r</i><sub>agg</sub><sup>in</sup></span>).</figcaption>
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
  <div class="research-project__text">
      <p>Precipitation projections in climate models contain large amounts of uncertainty and suffer from a "drizzle effect", where the model output precipitation is always lightly raining. As climate models increase their spatial resolution, we would hope to more accurately capture the more extreme precipitation events that have profound impacts on our society. This study looks at the power spectrum of the precipitation variance of low, medium, and high resolution models and compares them to rain gauge information. The goal is to understand if increasing resolution can capture the high frequency high intensity rain events that we see in observation.</p>
    </div>
</section>
