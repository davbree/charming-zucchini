# ✨ charming-zucchini ✨

<img src="https://themes.stackbit.com/images/diy-demo-1024x768.png" width="600">

This is a [Gatsby](https://gatsbyjs.com) site using [Contentful](https://www.contentful.com) as a [CMS](https://en.wikipedia.org/wiki/Content_management_system). It was created with [Stackbit](https://www.stackbit.com?utm_source=project-readme&utm_medium=referral&utm_campaign=user_themes) in under a minute.

You can [create a site](https://app.stackbit.com/create?theme=https://github.com/stackbithq/stackbit-theme-diy) just like this one, or explore some variations. How about a different:

<details>
        <summary>🎨 &nbsp;<strong>Look</strong></summary>
        <ul>
                <li><a href="https://app.stackbit.com/create?theme=https://github.com/stackbithq/stackbit-theme-azimuth&utm_source=project-readme&utm_medium=referral&utm_campaign=user_themes">A sleek SaaS theme</a></li>
                <li><a href="https://app.stackbit.com/create?theme=https://github.com/stackbithq/stackbit-theme-libris&utm_source=project-readme&utm_medium=referral&utm_campaign=user_themes">A documentation theme</a></li>
                <li><a href="https://app.stackbit.com/create?theme=https://github.com/stackbithq/stackbit-theme-fresh&utm_source=project-readme&utm_medium=referral&utm_campaign=user_themes">A personal theme with a blog</a></li>
                </ul>
</details>

<details>
        <summary>✏️ &nbsp;<strong>CMS</strong></summary>
        <ul>
                <li><a href="https://app.stackbit.com/create?cms=sanity&utm_source=project-readme&utm_medium=referral&utm_campaign=user_themes">Sanity</a></li>
                <li><a href="https://app.stackbit.com/create?cms=netlifycms&utm_source=project-readme&utm_medium=referral&utm_campaign=user_themes">Netlify CMS</a></li>
                <li><a href="https://app.stackbit.com/create?cms=datocms&utm_source=project-readme&utm_medium=referral&utm_campaign=user_themes">Dato CMS</a></li>
                </ul>
</details>

<details>
        <summary>⚙️ &nbsp;<strong>Static site generator</strong></summary>
        <ul>
                <li><a href="https://app.stackbit.com/create?ssg=nextjs&utm_source=project-readme&utm_medium=referral&utm_campaign=user_themes">Next.js</a></li>
                <li><a href="https://app.stackbit.com/create?ssg=hugo&utm_source=project-readme&utm_medium=referral&utm_campaign=user_themes">Hugo</a></li>
                <li><a href="https://app.stackbit.com/create?ssg=jekyll&utm_source=project-readme&utm_medium=referral&utm_campaign=user_themes">Jekyll</a></li>
                </ul>
</details>

## Develop Locally

1. Install [Node.js and npm](https://nodejs.org/en/)

1. Install npm dependencies:

        npm install

1. Get the project's `stackbit-api-key` from the [Stackbit dashboard](https://app.stackbit.com/dashboard)

1. Assign this key to the `STACKBIT_API_KEY` environment variable (replace `{stackbit_api_key}` with the actual key):

        export STACKBIT_API_KEY={stackbit_api_key}

1. Fetch the content from Contentful:

        npx @stackbit/stackbit-pull --stackbit-pull-api-url=https://api.stackbit.com/pull/5fc7946d8ebc68001c2072d9

1. Start the Gatsby local development server:

        npm run develop

1. Open [http://localhost:8000/](http://localhost:8000/) in the browser

1. 🎉

## Editing Content

To start editing your site, you can use the Contentful interface at [https://app.contentful.com/spaces/4fyuov8ntgf1](https://app.contentful.com/spaces/4fyuov8ntgf1).

Alternatively, you can use the free on-page editing experience provided by the [Stackbit Studio](https://stackbit.com?utm_source=project-readme&utm_medium=referral&utm_campaign=user_themes).

[![](https://i3.ytimg.com/vi/zd9lGRLVDm4/hqdefault.jpg)](https://link.stackbit.com/project-readme-lead-video)

Here's a few resources to get you started:

- 📺 &nbsp; [Editing Content](https://link.stackbit.com/project-readme-editing-video)
- 📺 &nbsp; [Adding, Reordering and Deleting Items](https://link.stackbit.com/project-readme-adding-video)
- 📺 &nbsp; [Collaboration](https://link.stackbit.com/project-readme-collaboration-video)
- 📺 &nbsp; [Publishing](https://link.stackbit.com/project-readme-publishing-video)
- 📚 &nbsp; [Stackbit Documentation](https://www.stackbit.com/docs/)

If you need a hand, make sure to check the [Stackbit support page](https://www.stackbit.com/support?utm_source=project-readme&utm_medium=referral&utm_campaign=user_themes).

## Colophon

Generated at `2020-12-02T13:20:13.999Z` by Stackbit version `0.3.38`.