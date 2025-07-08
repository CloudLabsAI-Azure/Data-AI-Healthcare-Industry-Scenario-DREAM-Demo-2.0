<style>
  table {
    width: 80%;
    margin: 30px auto;
    border-collapse: collapse;
    font-family: 'Segoe UI', sans-serif;
    font-size: 15px;
  }

  th {
    background: #f2f2f2;
    padding: 10px;
    text-align: left;
    border: 1px solid #ddd;
  }

  td {
    width: 900px;
    height: 10px;
    padding: 10px;
    text-align: left;
    border: 1px solid #ddd;
  }

  .description {
    margin: 0 auto;
    font-family: 'Segoe UI', sans-serif;
    font-size: 14px;
    color: #444;
  }

  .highlight-box {
    background: #f8f9fa;
    padding: 12px 24px 12px 32px; /* Top, Right, Bottom, Left */
    border-left: 4px solid #0078d4;
    margin: 20px auto;
    font-size: 14px;
    text-align: left;
}


  }
</style>

<div class="description">
  <h2 style="color: #333;">📄 Description</h2>
  <p>
    This demo highlights how Contoso, a small business, implemented a unified, lake-centric foundation to streamline and manage their data estate. Contoso leverages Task Flow to visualize workflows in their workspace and the Fast Copy feature to quickly copy large datasets, enhancing their data management. Explore how Contoso's data is ingested from diverse sources, including SQL, SaaS application and Amazon S3, while external sources are mapped via Shortcuts and Mirroring. Real-time data from IoT sensors and Azure EventHub is analyzed with Real-time Intelligence. Data is curated in medallion layers using pipelines, notebooks, and Copilot for notebooks. Advanced insights are extracted using ML models and AI skill for conversational Q&A systems. Enhanced Data Warehousing with Copilot. Finally, Power BI Reports are generated seamlessly using Direct Lake and Copilot.
  </p>
</div>

<div class="highlight-box">
  <strong>IMPORTANT:</strong><br>
  Please launch the demo <strong>15 minutes before presenting</strong>. Resources may take a few minutes to provision.<br>
  ODL access provisioning may take <strong>5–7 minutes</strong>.<br>
  If unauthorized errors occur, wait a few minutes and then press <strong>Ctrl + Shift + R</strong> to refresh.
</div>

<!-- Auth Table -->

| **User Login Credentials** |                                       |
|-----------------|---------------------------------------|
| Username    | <inject key="AzureAdUserEmail" />     |
| Password   | <inject key="AzureAdUserPassword" />  |
| Teams Login Username | <inject key="Teams Login UserName" /> |
| Teams Login Password | <inject key="Teams Login Password" /> |


<!-- Resource Details Table -->
<table>
  <thead>
    <tr>
      <th>Resources</th>
      <th>Links</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Web App Link</td>
      <td>
        <a href="https://app-fabric-demo-3-smb.azurewebsites.net" target="_blank">
          https://app-fabric-demo-3-smb.azurewebsites.net
        </a>
      </td>
    </tr>
    <tr>
      <td>Microsoft Fabric Workspace</td>
      <td>
        <a href="https://app.powerbi.com/home?experience=fabric" target="_blank">
          https://app.powerbi.com/home?experience=fabric
        </a>
      </td>
    </tr>
  </tbody>
</table>
