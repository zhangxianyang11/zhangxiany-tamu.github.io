---
title: "Xianyang Zhang - Softwares"
layout: default
excerpt: "Xianyang Zhang -- Softwares"
sitemap: false
permalink: /software
---

<div markdown="0" class="hero-body">
  <div class="container">
    <article class="media">
      <div class="media-content">
        <div class="content">
          <h1>Softwares</h1>
        </div>
      </div>
    </article>
    <hr />
    <div class="columns">
      <div class="column is-1">
        <figure class="image is-1by1">
          <img src="/images/Rlogo.png" />
        </figure>
      </div>
      <div class="column">
        <div class="content">
          <p>
            <strong>MicrobiomeStat</strong>: Statistical Methods for Microbiome
            Compositional Data <span class="tag is-white">2022</span><br />
            A suite of methods for powerful and robust microbiome data analysis
            addressing zero-inflation, phylogenetic structure and compositional
            effects (Zhou et al., 2021). The methods can be applied to the
            analysis of other (high-dimensional) compositional data arising from
            sequencing experiments.
          </p>
          <div class="field is-grouped is-grouped-multiline">
            <div class="control">
              <div class="tags has-addons">
                <span class="tag is-dark"
                  ><i class="fa fa-code-fork" aria-hidden="true"></i
                ></span>
                <a
                  class="tag"
                  href="https://cran.r-project.org/web/packages/MicrobiomeStat/index.html"
                  >CRAN</a
                >
              </div>
            </div>
            <div class="control">
              <div class="tags has-addons">
                <span class="tag is-dark"
                  ><i class="fa fa-book" aria-hidden="true"></i
                ></span>
                <a
                  class="tag"
                  href="https://cran.r-project.org/web/packages/MicrobiomeStat/MicrobiomeStat.pdf"
                  >Documentation</a
                >
              </div>
            </div>
            <div class="control">
              <div class="tags has-addons">
                <span class="tag is-dark"
                  ><i class="fa fa-book" aria-hidden="true"></i
                ></span>
                <a class="tag" href="https://arxiv.org/abs/2104.00242"
                  >Paper</a
                >
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <hr />
    <div class="columns">
      <div class="column is-1">
        <figure class="image is-1by1">
          <img src="/images/Rlogo.png" />
        </figure>
      </div>
      <div class="column">
        <div class="content">
          <p>
            <strong>TDFDR</strong>: Two-dimensional false discovery rate control for powerful confounder adjustment in omics association studies <span class="tag is-white">2021</span><br />
            The package implements the two-dimensional false discovery rate control for powerful confounder adjustment in omics association analysis. The method is based on the idea that the confounder(s) usually affect part of the omics features, and thus adjusting the confounder(s) for ALL omics features will be over-adjustment, leading to reduced statistical power. The proposed procedure starts with performing the unadjusted analysis (first dimension - filtering) to narrow down the list of omics features that are more likely to be affected by either the confounder or the variable of interest or both. In the second dimension, we conduct confounder-adjusted analysis on these 'top' candidates, which are enriched in signals, to reduce multiple testing burden and increase the power. The method belongs to the general topic of using auxiliary data to increase the power of multiple testing, which has recently received tremendous research interest. In our case, the auxiliary data are the the unadjusted statistics, which could inform the probability of the null hypotheses being true. The difficulty here is to take into account the correlation between the auxiliary data (unadjusted statistics) and the main data (adjusted statistics). We provide a procedure that is theoretically guaranteed to control the false discovery rate while maximizing the power.
          </p>
          <div class="field is-grouped is-grouped-multiline">
            <div class="control">
              <div class="tags has-addons">
                <span class="tag is-dark"
                  ><i class="fa fa-code-fork" aria-hidden="true"></i
                ></span>
                <a
                  class="tag"
                  href="https://github.com/jchen1981/TDFDR/"
                  >GitHub</a
                >
              </div>
            </div>
            <div class="control">
              <div class="tags has-addons">
                <span class="tag is-dark"
                  ><i class="fa fa-book" aria-hidden="true"></i
                ></span>
                <a class="tag" href="https://genomebiology.biomedcentral.com/articles/10.1186/s13059-021-02418-8"
                  >Paper</a
                >
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <hr />
    <div class="columns">
      <div class="column is-1">
        <figure class="image is-1by1">
          <img src="/images/Rlogo.png" />
        </figure>
      </div>
      <div class="column">
        <div class="content">
          <p>
            <strong>OrderShapeEM</strong> <span class="tag is-white">2021</span
            ><br />
            OrderShapeEM implements the optimal false discovery rate (FDR)
            control procedure with auxiliary information, particularly for prior
            ordering information. The framework is based on local FDR with
            hypothesis-specific null probability. The prior null proabilities
            are estimated using isotonic regression (PAVA algorithm) with
            respect to the prior ordering information. The inputs of our
            OrderShapeEM are simply P-values and their prior ordering.
          </p>
          <div class="field is-grouped is-grouped-multiline">
            <div class="control">
              <div class="tags has-addons">
                <span class="tag is-dark"
                  ><i class="fa fa-code-fork" aria-hidden="true"></i
                ></span>
                <a class="tag" href="https://github.com/jchen1981/OrderShapeEM"
                  >GitHub</a
                >
              </div>
            </div>
            <div class="control">
              <div class="tags has-addons">
                <span class="tag is-dark"
                  ><i class="fa fa-book" aria-hidden="true"></i
                ></span>
                <a class="tag" href="https://arxiv.org/abs/2103.15311"
                  >Paper</a
                >
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <hr />
    <div class="columns">
      <div class="column is-1">
        <figure class="image is-1by1">
          <img src="/images/Rlogo.png" />
        </figure>
      </div>
      <div class="column">
        <div class="content">
          <p>
            <strong>CAMT</strong> <span class="tag is-white">2020</span><br />
            The CAMT package implements two covariate adaptive multiple testing
            procedures (FDR and FWER) described in Covariate Adaptive False
            Discovery Rate Control with Applications to Omics-Wide Multiple
            Testing and Covariate Adaptive Family-wise Error Control with
            Applications to Genome-wide Association Studies. CAMT allows the
            prior null probability and/or the alternative distribution to depend
            on covariates. It is robust to model mis-specification and is
            computationally efficient. The package also contains functions for
            testing the informativeness of the covariates for multiple testing,
            and a comprehensive simulation function, which covers a wide range
            of settings.
          </p>
          <div class="field is-grouped is-grouped-multiline">
            <div class="control">
              <div class="tags has-addons">
                <span class="tag is-dark"
                  ><i class="fa fa-code-fork" aria-hidden="true"></i
                ></span>
                <a class="tag" href="https://github.com/jchen1981/CAMT"
                  >GitHub</a
                >
              </div>
            </div>
            <div class="control">
              <div class="tags has-addons">
                <span class="tag is-dark"
                  ><i class="fa fa-book" aria-hidden="true"></i
                ></span>
                <a class="tag" href="https://www.tandfonline.com/doi/abs/10.1080/01621459.2020.1783273?journalCode=uasa20"
                  >Paper on FDR</a
                >
              </div>
            </div>
            <div class="control">
              <div class="tags has-addons">
                <span class="tag is-dark"
                  ><i class="fa fa-book" aria-hidden="true"></i
                ></span>
                <a class="tag" href="https://academic.oup.com/biomet/article-abstract/108/4/915/6007465?redirectedFrom=fulltext&login=false"
                  >Paper on FWER</a
                >
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <hr />
    <div class="columns">
      <div class="column is-1">
        <figure class="image is-1by1">
          <img src="/images/Rlogo.png" />
        </figure>
      </div>
      <div class="column">
        <div class="content">
          <p>
            <strong>GUniFrac</strong>: Generalized UniFrac Distances,
            Distance-Based Multivariate Methods and Feature-Based Univariate
            Methods for Microbiome Data Analysis
            <span class="tag is-white">2021</span><br />
            A suite of methods for powerful and robust microbiome data analysis
            including data normalization, data simulation, community-level
            association testing and differential abundance analysis. It
            implements generalized UniFrac distances, Geometric Mean of Pairwise
            Ratios (GMPR) normalization, semiparametric data simulator,
            distance-based statistical methods, and feature-based statistical
            methods. The distance-based statistical methods include three
            extensions of PERMANOVA: (1) PERMANOVA using the Freedman-Lane
            permutation scheme, (2) PERMANOVA omnibus test using multiple
            matrices, and (3) analytical approach to approximating PERMANOVA
            p-value. Feature-based statistical methods include linear
            model-based methods for differential abundance analysis of
            zero-inflated high-dimensional compositional data.
          </p>
          <div class="field is-grouped is-grouped-multiline">
            <div class="control">
              <div class="tags has-addons">
                <span class="tag is-dark"
                  ><i class="fa fa-code-fork" aria-hidden="true"></i
                ></span>
                <a
                  class="tag"
                  href="https://cran.r-project.org/web/packages/GUniFrac/index.html"
                  >CRAN</a
                >
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <hr />
    <div class="columns">
      <div class="column is-1">
        <figure class="image is-1by1">
          <img src="/images/Rlogo.png" />
        </figure>
      </div>
      <div class="column">
        <div class="content">
          <p>
            <strong>jdcov</strong> <span class="tag is-white">2019</span><br />
            jdov computes joint distance covariance (JdCov) among more than two
            random vectors of arbitrary dimensions (see Chakraborty and Zhang,
            2019) and implements a bootstrap based test for joint independence
            among the random vectors based on JdCov.
          </p>
          <div class="field is-grouped is-grouped-multiline">
            <div class="control">
              <div class="tags has-addons">
                <span class="tag is-dark"
                  ><i class="fa fa-code-fork" aria-hidden="true"></i
                ></span>
                <a class="tag" href="https://rdrr.io/github/shubhadeep4/jdcov/"
                  >rdrr</a
                >
              </div>
            </div>
            <div class="control">
              <div class="tags has-addons">
                <span class="tag is-dark"
                  ><i class="fa fa-code-fork" aria-hidden="true"></i
                ></span>
                <a class="tag" href="https://github.com/shubhadeep4/jdcov/"
                  >GitHub</a
                >
              </div>
            </div>
            <div class="control">
              <div class="tags has-addons">
                <span class="tag is-dark"
                  ><i class="fa fa-book" aria-hidden="true"></i
                ></span>
                <a class="tag" href="https://www.tandfonline.com/doi/abs/10.1080/01621459.2018.1513364?journalCode=uasa20"
                  >Paper</a
                >
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <hr />
    <div class="columns">
      <div class="column is-1">
        <figure class="image is-1by1">
          <img src="/images/Rlogo.png" />
        </figure>
      </div>
      <div class="column">
        <div class="content">
          <p>
            <strong>SILM</strong>: Simultaneous Inference for Linear Models
            <span class="tag is-white">2019</span><br />
            Simultaneous inference procedures for high-dimensional linear models
            as described by Zhang and Cheng (2017).
          </p>
          <div class="field is-grouped is-grouped-multiline">
            <div class="control">
              <div class="tags has-addons">
                <span class="tag is-dark"
                  ><i class="fa fa-code-fork" aria-hidden="true"></i
                ></span>
                <a
                  class="tag"
                  href="https://cran.r-project.org/web/packages/SILM/index.html"
                  >CRAN</a
                >
              </div>
            </div>
            <div class="control">
              <div class="tags has-addons">
                <span class="tag is-dark"
                  ><i class="fa fa-book" aria-hidden="true"></i
                ></span>
                <a
                  class="tag"
                  href="https://doi.org/10.1080/01621459.2016.1166114"
                  >Paper</a
                >
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
