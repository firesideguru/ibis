
# patterns

    <data as="menu" type="json">
      {
        {
          "link": "http://google.com",
          "label": "Google"
        },
        {
          "link": "http://yahoo.com",
          "label": "Yahoo"
        }
      }
    </data>
    
    <view as="link" type="html">
      <li><a href="{{link}}" key="label"></a></li>
    </view>
    
    <ul view="link" wrap="inner" bind="menu"></ul>
