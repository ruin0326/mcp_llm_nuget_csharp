# Nuget MCP LLM

### Search Packages

**Request:**
```json
{
  "name": "search_packages",
  "parameters": {
    "query": "json"
  }
}
```

**Response:**
```text
## Newtonsoft.Json v13.0.3
**Downloads**: 4,500,000,000
**Description**: Json.NET is a popular high-performance JSON framework for .NET
```

</details>

## Project Structure

<details>
<summary>📁 View File Structure</summary>

*   `Program.cs`: Main entry point.
*   `Tools/`: Contains the logic for each MCP tool.
*   `Services/`: Handles NuGet downloads, formatting, and analysis.
*   `Common/`: Shared code and base classes.

</details>


