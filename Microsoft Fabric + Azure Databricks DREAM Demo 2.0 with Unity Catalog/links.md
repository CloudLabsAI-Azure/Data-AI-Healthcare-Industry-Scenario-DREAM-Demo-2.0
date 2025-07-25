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

</style>

<div class="description">
  <h2 style="color: #333;">📄 Description</h2>
  <p>
    This demo illustrates the combined capabilities of Microsoft Fabric and Azure Databricks to build an end-to-end analytics project focusing on persona-based experiences. Data products can then be served to end users through Azure Databricks or any compute engine in Microsoft Fabric - a unified analytics platform that brings together all the data and analytics tools that organizations need. Explore how to eliminate data silos by connecting to existing data with shortcuts, reuse data without copying it with the OneLake feature, and seamlessly update Azure Databricks notebooks using OneLake endpoints for the data.
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
        <a href="https://app-fabric-with-databricks-2-demo-prod.azurewebsites.net/" target="_blank">
          https://app-fabric-with-databricks-2-demo-prod.azurewebsites.net/
        </a>
      </td>
    </tr>
    <tr>
    <td>Microsoft Fabric Workspace</td>
    <td>
        <a href="https://app.fabric.microsoft.com/home" target="_blank">
          https://app.fabric.microsoft.com/home
        </a>
    </td>
    </tr>
    <tr>
    <td>Azure Databricks</td>
    <td>
        <a href="https://adb-3218079371877032.12.azuredatabricks.net" target="_blank">
          https://adb-3218079371877032.12.azuredatabricks.net
        </a>
    </td>
    </tr>
        <tr>
    <td>Azure Cosmos DB</td>
    <td>
        <a href="https://portal.azure.com/#@CloudLabsAIoutlook.onmicrosoft.com/resource/subscriptions/506e86fc-853c-4557-a6e5-ad72114efd2b/resourceGroups/rg-fabric-with-databricks-prod/providers/Microsoft.DocumentDB/databaseAccounts/cosmos-fabric-databricks2-prod/overview" target="_blank">
          https://portal.azure.com/#@CloudLabsAIoutlook.onmicrosoft.com/resource/subscriptions/506e86fc-853c-4557-a6e5-ad72114efd2b/resourceGroups/rg-fabric-with-databricks-prod/providers/Microsoft.DocumentDB/databaseAccounts/cosmos-fabric-databricks2-prod/overview
        </a>
    </td>
    </tr>
  </tbody>
</table>
