<a name="start-building"></a>
<br>
<p align="center">
<img src="img/banner-build-26.png" alt="Microsoft Build 2026" width="1200"/>
</p>

# [Microsoft Build 2026](https://build.microsoft.com)

## 🔥 DEM300: Supercharged Profiling: Finding Performance Bugs with Agents

### Session Description

Modern performance problems are harder than ever to diagnose: distributed systems, async code, and massive data make traditional profiling insufficient. In this demo-driven session, watch how Visual Studio combines advanced diagnostics with AI-powered agents to surface bottlenecks, explain root causes, and guide fixes faster than ever. From CPU and memory issues to "it only fails in production" bugs, you will see how profiling evolves in an agentic world.

### 🚀 Getting started

If you're following along at your own pace:
- Clone this repository
- Review [src/README.md](src/README.md) for session assets and flow
- Use the backup videos in [src/DEM300-CreateBenchmark.mp4](src/DEM300-CreateBenchmark.mp4) and [src/DEM300-OptimizeCPU.mp4](src/DEM300-OptimizeCPU.mp4) if you want a guided walkthrough of the benchmark creation and CPU optimization sequence

### 🧠 Learning Outcomes

By the end of this session, you will be able to:

- Use Visual Studio profiling and diagnostics tools to isolate CPU and memory bottlenecks in realistic applications
- Use GitHub Copilot agent workflows in Visual Studio to explain likely root causes and propose targeted fixes
- Apply repeatable troubleshooting patterns for intermittent or production-only performance problems

### 💬 Keep Learning with Copilot

Try these prompts with GitHub Copilot to explore the topics from this session in Visual Studio on Windows. Open Copilot Chat in Visual Studio (`Ctrl+\`, then `Ctrl+I`), paste a prompt, and iterate on diagnostics and fixes. Try connecting the [Microsoft Learn MCP Server](#-microsoft-learn-mcp-server) for the latest official documentation.

Use these as a starting point — or write your own!

1. "Walk me through a profiling plan to investigate high CPU usage in this solution. Include which tool to run first and why."
1. "Use the profiler results and suggest the top three code-level optimizations for hot paths, with expected tradeoffs."
1. "Act as a debugging and diagnostics coach: help me investigate a memory growth issue that only appears under sustained load."
1. "Generate a benchmark-first workflow for validating performance improvements and preventing regressions in pull requests."
1. "Given this async code path, identify where contention or blocking could occur and suggest instrumentation points."
1. "Create unit and integration test ideas that protect the optimized code path from future performance regressions."

### 💻 Technologies Used

1. Visual Studio profiling and diagnostics tools
1. GitHub Copilot in Visual Studio (including agent workflows)
1. .NET diagnostics and performance tooling

### 📚 Resources and Next Steps

| Resource | Description |
|:---------|:------------|
| [Visual Studio profiling tools overview](https://learn.microsoft.com/visualstudio/profiling/profiling-feature-tour?view=visualstudio) | Tour of the Performance Profiler and Diagnostic Tools workflows |
| [Analyze CPU usage in Visual Studio](https://learn.microsoft.com/visualstudio/profiling/cpu-usage?view=visualstudio) | Step-by-step guidance for collecting and analyzing CPU traces |
| [Analyze memory usage in Visual Studio](https://learn.microsoft.com/visualstudio/profiling/analyze-memory-usage?view=visualstudio) | Guidance on finding leaks and inefficient allocations |
| [GitHub Copilot agent mode in Visual Studio](https://learn.microsoft.com/visualstudio/ide/copilot-agent-mode?view=visualstudio) | How to use agent mode to iterate on diagnostics and fixes |
| [Built-in and custom GitHub Copilot agents in Visual Studio](https://learn.microsoft.com/visualstudio/ide/copilot-specialized-agents?view=visualstudio) | Overview of built-in agents like @profiler, @debugger, and @test |
| [.NET diagnostics tools overview](https://learn.microsoft.com/dotnet/core/diagnostics/tools-overview#cli-tools) | Command-line diagnostics tools for deeper production troubleshooting |
| [https://aka.ms/build26-next-steps](https://aka.ms/build26-next-steps) | Explore lab and session repos to further your learning from Microsoft Build |


### 🌟 Microsoft Learn MCP Server

The Microsoft Learn MCP Server gives your AI agent direct access to Microsoft's official documentation — grounded, up-to-date answers about the products and services covered in this session.

**Visual Studio Code** — One click installation: 

[![Install in VS Code](https://img.shields.io/badge/VS_Code-Install_Microsoft_Learn_MCP-0098FF?style=flat-square&logo=visualstudiocode&logoColor=white)](https://vscode.dev/redirect/mcp/install?name=microsoft-learn&config=%7B%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A%2F%2Flearn.microsoft.com%2Fapi%2Fmcp%22%7D)


**GitHub Copilot CLI** — Run this to install the Learn MCP Server as a plugin:
```
/plugin install microsoftdocs/mcp
```

For more info, other clients, and to post questions, visit the [Learn MCP Server repo](https://aka.ms/learnmcp).

## Content Owners

<table>
<tr>
    <td align="center"><a href="http://github.com/karpinsn">
        <img src="https://github.com/karpinsn.png" width="100px;" alt="Nik Karpinsky"/><br />
        <sub><b>Nik Karpinsky</b></sub></a><br />
            <a href="https://github.com/karpinsn" title="talk">📢</a>
    </td>
</tr></table>

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit [Contributor License Agreements](https://cla.opensource.microsoft.com).

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft
trademarks or logos is subject to and must follow
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
