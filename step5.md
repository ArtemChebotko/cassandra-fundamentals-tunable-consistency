<!-- TOP -->
<div class="top">
  <img src="https://datastax-academy.github.io/katapod-shared-assets/images/ds-academy-logo.svg" />
  <div class="scenario-title-section">
    <span class="scenario-title">Tunable Consistency and Consistency Levels in Apache Cassandra®</span>
    <span class="scenario-subtitle">ℹ️ For technical support, please contact us via <a href="mailto:aleksandr.volochnev@datastax.com">email</a> or <a href="https://dtsx.io/aleks">LinkedIn</a>.</span> 
  </div>
</div>

<!-- NAVIGATION -->
<div id="navigation-top" class="navigation-top">
 <a href='command:katapod.loadPage?[{"step":"step4"}]'
   class="btn btn-dark navigation-top-left">⬅️ Back
 </a>
<span class="step-count"> Step 5 of 8</span>
 <a href='command:katapod.loadPage?[{"step":"step6"}]'
    class="btn btn-dark navigation-top-right">Next ➡️
  </a>
</div>

<!-- CONTENT -->

<div class="step-title">Access and set a consistency level</div>

The CQL shell has the `CONSISTENCY` command to both access and set a consistency level for 
read and write operations. When you write your own application using a driver, there will be a way to 
set a consistency level dynamically, too.

✅ Get the current consistency level:
```
CONSISTENCY;
```

✅ Set the consistency level:
```
CONSISTENCY LOCAL_ONE;
```

<!-- NAVIGATION -->
<div id="navigation-bottom" class="navigation-bottom">
 <a href='command:katapod.loadPage?[{"step":"step4"}]'
   class="btn btn-dark navigation-bottom-left">⬅️ Back
 </a>
 <a href='command:katapod.loadPage?[{"step":"step6"}]'
    class="btn btn-dark navigation-bottom-right">Next ➡️
  </a>
</div>

