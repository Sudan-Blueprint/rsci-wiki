# Rural Social Industrial Complex (RSIC) Wiki

![RSIC Logo](assets/images/rsic-logo.png)

The **Rural Social Industrial Complex (RSIC) Wiki** is a public, replicable knowledge base for **community-driven rural industrialization in Sudan**.\
It documents the vision, roadmap, facilities, factories, shared resources, and replication model of the RSIC initiative — designed to serve as a **blueprint for scaling industrial transformation** across the country.

------------------------------------------------------------------------

## 🌍 What is RSIC?

The RSIC model aims to: - Leverage **local resources** (agriculture, minerals, human capital) for value-added production. - Establish **factories and shared facilities** that create jobs and strengthen communities. - Provide **training and research centers** to ensure sustainability, quality, and innovation. - Act as a **replicable unit** for rural revival and industrial growth across Sudan.

------------------------------------------------------------------------

## 📖 Wiki Structure

The documentation site (built with [Quarto](https://quarto.org/)) is organized into:

-   [**Introduction**](intro/index.qmd)**:** Vision, philosophy, and strategy.\
-   [**Roadmap**](roadmap/index.qmd)**:** Phases, milestones, and next steps.\
-   [**Facilities**](facilities/index.qmd)**:** Site profile, utilities, and layout.\
-   [**Factories**](factories/index.qmd)**:** Catalogue of proposed factories with detailed templates.\
-   [**Shared Resources**](shared/index.qmd)**:** Industrial Transformation Technical Center (ITTC), research, labs, logistics, training.\
-   [**Replication Model**](replication/index.qmd)**:** Practical steps, checklists, and policy guidance to replicate RSICs in other cities.

------------------------------------------------------------------------

## 🛠️ Technology & Setup

The site is built using **Quarto** and hosted on **GitHub Pages**.

### Quick Start

1.  Install [Quarto](https://quarto.org/docs/get-started/).\

2.  Clone this repo:

    ``` bash
    git clone https://github.com/<your-username>/rsic-wiki.git
    cd rsic-wiki
    ```

3.  Preview locally:

    ``` bash
    quarto preview
    ```

4.  Render for deployment:

    ``` bash
    quarto render
    ```

    Builds the site into the `docs/` folder.

### Deployment

-   Enable **GitHub Pages** under repo **Settings → Pages** and choose:
    -   Branch: `main`
    -   Folder: `/docs`

Or use the included **GitHub Actions workflow** to publish automatically to the `gh-pages` branch.

------------------------------------------------------------------------

## 🤝 Contributing

We welcome contributions from researchers, practitioners, and community members.

-   Fork the repo and submit a **Pull Request**.\

-   Add or edit wiki pages (`.qmd` files) under the relevant folder.\

-   Use front matter (`title`, `tags`, `status`, etc.) to keep metadata consistent.\

-   For right-to-left text (Arabic), wrap content in:

    ``` html
    <div class="rtl">
    النص العربي هنا
    </div>
    ```
