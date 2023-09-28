{
  // ...
  import React from 'react';
import Head from '@docusaurus/Head';

const MySEO = () => (
  <Head>
    <meta property="og:description" content="My custom description" />
    <meta charSet="utf-8" />
    <title>My Title</title>
    <link rel="canonical" href="http://mysite.com/example" />
  </Head>
  <Parent>
  <Head>
    <title>My Title</title>
    <meta name="description" content="Helmet application" />
  </Head>
  <Child>
    <Head>
      <title>Nested Title</title>
      <meta name="description" content="Nested component" />
    </Head>
  </Child>
</Parent>
);
}
