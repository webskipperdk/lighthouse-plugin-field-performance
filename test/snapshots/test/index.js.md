# Snapshot report for `test/index.js`

The actual snapshot is saved in `index.js.snap`.

Generated by [AVA](https://ava.li).

## Measure field perf for site in CruX

> Snapshot 1

    {
      description: 'First Contentful Paint marks the time at which the first text or image painted. The value represents the 90th percentile of the page traffic. [Learn More](https://developers.google.com/speed/docs/insights/v5/about#faq)',
      id: 'field-fcp',
      scoreDisplayMode: 'numeric',
      title: 'First Contentful Paint (URL)',
    }

> Snapshot 2

    {
      headings: [
        {
          itemType: 'text',
          key: 'category',
          text: 'Category',
        },
        {
          itemType: 'text',
          key: 'distribution',
          text: 'Percent of traffic',
        },
      ],
      items: [
        {
          category: 'Fast (faster than 1 s)',
        },
        {
          category: 'Average (from 1 s to 2.5 s)',
        },
        {
          category: 'Slow (longer than 2.5 s)',
        },
      ],
      type: 'table',
    }

> Snapshot 3

    {
      description: 'First Input Delay indicates how fast UI responded after the first interaction. The value represents the 95th percentile of the page traffic. [Learn More](https://developers.google.com/speed/docs/insights/v5/about#faq)',
      id: 'field-fid',
      scoreDisplayMode: 'numeric',
      title: 'First Input Delay (URL)',
    }

> Snapshot 4

    {
      headings: [
        {
          itemType: 'text',
          key: 'category',
          text: 'Category',
        },
        {
          itemType: 'text',
          key: 'distribution',
          text: 'Percent of traffic',
        },
      ],
      items: [
        {
          category: 'Fast (faster than 50 ms)',
        },
        {
          category: 'Average (from 50 ms to 250 ms)',
        },
        {
          category: 'Slow (longer than 250 ms)',
        },
      ],
      type: 'table',
    }

> Snapshot 5

    {
      description: 'First Contentful Paint marks the time at which the first text or image painted. The value represents the 90th percentile of all origin traffic. [Learn More](https://developers.google.com/speed/docs/insights/v5/about#faq)',
      id: 'field-fcp-origin',
      scoreDisplayMode: 'numeric',
      title: 'First Contentful Paint (Origin)',
    }

> Snapshot 6

    {
      headings: [
        {
          itemType: 'text',
          key: 'category',
          text: 'Category',
        },
        {
          itemType: 'text',
          key: 'distribution',
          text: 'Percent of traffic',
        },
      ],
      items: [
        {
          category: 'Fast (faster than 1 s)',
        },
        {
          category: 'Average (from 1 s to 2.5 s)',
        },
        {
          category: 'Slow (longer than 2.5 s)',
        },
      ],
      type: 'table',
    }

> Snapshot 7

    {
      description: 'First Input Delay indicates how fast UI responded after the first interaction. The value represents the 95th percentile of all origin traffic. [Learn More](https://developers.google.com/speed/docs/insights/v5/about#faq)',
      id: 'field-fid-origin',
      scoreDisplayMode: 'numeric',
      title: 'First Input Delay (Origin)',
    }

> Snapshot 8

    {
      headings: [
        {
          itemType: 'text',
          key: 'category',
          text: 'Category',
        },
        {
          itemType: 'text',
          key: 'distribution',
          text: 'Percent of traffic',
        },
      ],
      items: [
        {
          category: 'Fast (faster than 50 ms)',
        },
        {
          category: 'Average (from 50 ms to 250 ms)',
        },
        {
          category: 'Slow (longer than 250 ms)',
        },
      ],
      type: 'table',
    }

> Snapshot 9

    {
      auditRefs: [
        {
          group: 'lighthouse-plugin-field-performance-page',
          id: 'field-fcp',
          weight: 1,
        },
        {
          group: 'lighthouse-plugin-field-performance-page',
          id: 'field-fid',
          weight: 1,
        },
        {
          group: 'lighthouse-plugin-field-performance-origin',
          id: 'field-fcp-origin',
          weight: 0,
        },
        {
          group: 'lighthouse-plugin-field-performance-origin',
          id: 'field-fid-origin',
          weight: 0,
        },
      ],
      description: 'These metrics show the performance of the page for real-world Chrome users over the last 30 days. Data is collected anonymously in the "field" and provided by Chrome UX Report. [Learn More](https://developers.google.com/web/tools/chrome-user-experience-report/)',
      id: 'lighthouse-plugin-field-performance',
      score: 0.71,
      title: 'Field Performance',
    }

## Measure field perf for site site not in CruX

> Snapshot 1

    {
      description: 'First Contentful Paint marks the time at which the first text or image painted. The value represents the 90th percentile of the page traffic. [Learn More](https://developers.google.com/speed/docs/insights/v5/about#faq)',
      explanation: `The Chrome User Experience Report ␊
                does not have sufficient real-world First Contentful Paint (URL) data for this page.`,
      id: 'field-fcp',
      score: null,
      scoreDisplayMode: 'notApplicable',
      title: 'First Contentful Paint (URL)',
    }

> Snapshot 2

    {
      description: 'First Input Delay indicates how fast UI responded after the first interaction. The value represents the 95th percentile of the page traffic. [Learn More](https://developers.google.com/speed/docs/insights/v5/about#faq)',
      explanation: `The Chrome User Experience Report ␊
                does not have sufficient real-world First Input Delay (URL) data for this page.`,
      id: 'field-fid',
      score: null,
      scoreDisplayMode: 'notApplicable',
      title: 'First Input Delay (URL)',
    }

> Snapshot 3

    {
      description: 'First Contentful Paint marks the time at which the first text or image painted. The value represents the 90th percentile of all origin traffic. [Learn More](https://developers.google.com/speed/docs/insights/v5/about#faq)',
      explanation: `The Chrome User Experience Report ␊
                does not have sufficient real-world First Contentful Paint (Origin) data for this page.`,
      id: 'field-fcp-origin',
      score: null,
      scoreDisplayMode: 'notApplicable',
      title: 'First Contentful Paint (Origin)',
    }

> Snapshot 4

    {
      description: 'First Input Delay indicates how fast UI responded after the first interaction. The value represents the 95th percentile of all origin traffic. [Learn More](https://developers.google.com/speed/docs/insights/v5/about#faq)',
      explanation: `The Chrome User Experience Report ␊
                does not have sufficient real-world First Input Delay (Origin) data for this page.`,
      id: 'field-fid-origin',
      score: null,
      scoreDisplayMode: 'notApplicable',
      title: 'First Input Delay (Origin)',
    }

> Snapshot 5

    {
      auditRefs: [
        {
          group: 'lighthouse-plugin-field-performance-page',
          id: 'field-fcp',
          weight: 0,
        },
        {
          group: 'lighthouse-plugin-field-performance-page',
          id: 'field-fid',
          weight: 0,
        },
        {
          group: 'lighthouse-plugin-field-performance-origin',
          id: 'field-fcp-origin',
          weight: 0,
        },
        {
          group: 'lighthouse-plugin-field-performance-origin',
          id: 'field-fid-origin',
          weight: 0,
        },
      ],
      description: 'These metrics show the performance of the page for real-world Chrome users over the last 30 days. Data is collected anonymously in the "field" and provided by Chrome UX Report. [Learn More](https://developers.google.com/web/tools/chrome-user-experience-report/)',
      id: 'lighthouse-plugin-field-performance',
      score: 0,
      title: 'Field Performance',
    }
