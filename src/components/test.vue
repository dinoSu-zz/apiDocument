<template>
  <div class="content">
  <p><code class="prettyprint">GET http://example.com/api/kittens</code></p>


  <table>
    <thead>
      <tr>
        <th>Parameter</th>
        <th>Type</th>
        <th>Required</th>
        <th>Description</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>include_cats</td>
        <td>false</td>
        <td>false</td>
        <td>If set to true, the result will also include cats.</td>
      </tr>
      <tr>
        <td>available</td>
        <td>true</td>
        <td>false</td>
        <td>If set to false, the result will include kittens that have already been adopted.</td>
      </tr>
    </tbody>
  </table>


<pre class="highlight json">
<code>
{
  "status": {
    "code": "OK",
    "message": ""
  },
  "lastModifiedTime": "",
  "members": [
    {
      "account": "5056",//會員編號
      "name": "王小明",
      "createTime": "2015-01-21 07:30:00",
      "birthday": "1990-03-28",
      "gender": "M",
      "mobile": "0938556897",
      "rank": "VIP",
      "startTime": "2015-06-01",
      "endTime": "2020-06-31",
      "memo": null,
      "status": 0
    },
    {
      "account": "5057",
      "name": "林小華",
      "createTime": "2015-01-21 09:45:00",
      "birthday": "1995-02-11",
      "gender": "F",
      "mobile": "0937123567",
      "rank": "VIP",
      "startTime": "2015-06-01",
      "endTime": "2020-06-31",
      "memo": null,
      "status": 0
    }
  ]
}
</code>

</pre>

  <blockquote>
  <p>To authorize, use this code:</p>
  </blockquote>


  <aside class="warning">
    Inside HTML code blocks like this one, you can’t use Markdown, so use <code>&lt;code&gt;</code> blocks to denote code.
  </aside>
</div>
</template>
<script>
export default{

}
</script>
