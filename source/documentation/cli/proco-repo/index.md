# Proco Repo

{% raw %}
<div class="table-wrap">
  <table>
    <thead>
    <tr>
      <th width="40%"><b>Command</b></th>
      <th width="60%"><b>Description</b></th>
    </tr>
    <thead>
    <tbody>
    <tr>
      <td><b><code>proco repo init</code></b></td>
      <td>
        <p>Initialize default environment and sample catalog.</p>
      </td>
    </tr>
    <tr>
      <td><b><code>proco repo (add|modify) &lt;name&gt; &lt;git-url&gt; <br/> [&lt;branch&gt;] [&lt;file&gt;]</code></b></td>
      <td>
        <p>Add new repo to catalog or modify existing one.</p>
        <p><code>&lt;name&gt;</code> - Name of the catalogue.</p>
        <p><code>&lt;git-url&gt;</code> - URL of catalog's GIT repository.</p>
        <p><code>[&lt;branch&gt;]</code> - Name of the branch that should be checked out. (default : master).</p>
        <p><code>[&lt;file&gt;]</code> - Name of the catalog file in the repository. (default: poco-catalog.yml).</p>
      </td>
    </tr>
    <tr>
      <td><b><code>proco repo (remove|rm) &lt;name&gt;</code></b></td>
      <td>
        <p>Remove repo from catalog.</p>
        <p><code>&lt;name&gt;</code> - Name of the catalog.</p>
      </td>
    </tr>
    <tr>
      <td><b><code>proco repo branch &lt;branch&gt; [&lt;name&gt;] [-f]</code></b></td>
      <td>
        <p>Switch repo branch if it is using GIT.</p>
        <p><code>&lt;branch&gt;</code> - Name of the branch that should be checked out.</p>
        <p><code>[&lt;name&gt;]</code> - Name of the catalog.</p>
        <p><code>[-f]</code> - Force switch.</p>
      </td>
    </tr>
    <tr>
      <td><b><code>proco repo branches [&lt;name&gt;]</code></b></td>
      <td>
        <p>List all available branches of catalog's GIT repository.</p>
        <p><code>[&lt;name&gt;]</code> - Name of the catalog.</p>
      </td>
    </tr>
    <tr>
      <td><b><code>proco repo push [&lt;name&gt;]</code></b></td>
      <td>
        <p>Push changes into catalog's remote GIT repository.</p>
        <p><code>[&lt;name&gt;]</code> - Name of the catalog.</p>
      </td>
    </tr>
    <tr>
      <td><b><code>proco repo ls</code></b></td>
      <td>
        <p>List repos available config(s).</p>
      </td>
    </tr>
    </tbody>
  </table>
</div>
{% endraw %}