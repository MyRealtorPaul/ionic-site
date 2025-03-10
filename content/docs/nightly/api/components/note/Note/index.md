---
layout: "fluid/docs_base"
version: "nightly"
versionHref: "/docs/nightly"
path: ""
category: api
id: "note"
title: "Note"
header_sub_title: "Ionic API Documentation"
doc: "Note"
docType: "class"

---









<h1 class="api-title">
<a class="anchor" name="note" href="#note"></a>

Note
<h3><code>ion-note</code></h3>






</h1>

<a class="improve-v2-docs" href="http://github.com/ionic-team/ionic/edit/master/src/components/note/note.ts#L3">
Improve this doc
</a>






<p>A note is detailed item in an ion-item. It creates greyed out element that can be on the left or right side of an item.</p>




<!-- @usage tag -->

<h2><a class="anchor" name="usage" href="#usage">Usage</a></h2>

<pre><code class="lang-html">&lt;ion-content&gt;
  &lt;ion-list&gt;
    &lt;ion-item&gt;
      &lt;ion-note item-start&gt;
        Left Note
      &lt;/ion-note&gt;
      My Item
      &lt;ion-note item-end&gt;
        Right Note
      &lt;/ion-note&gt;
    &lt;/ion-item&gt;
  &lt;/ion-list&gt;
&lt;/ion-content&gt;
</code></pre>
<p><a href="/docs/api/components/api/components/item/item">ion-item</a></p>




<!-- @property tags -->



<!-- instance methods on the class -->


  <h2 id="sass-variable-header"><a class="anchor" name="sass-variables" href="#sass-variables">Sass Variables</a></h2>
  <div id="sass-variables" ng-controller="SassToggleCtrl">
  <div class="sass-platform-toggle">
    
      
      
      <a ng-init="setSassPlatform('ios')" ng-class="{ active: active === 'ios' }" ng-click="setSassPlatform('ios')" >iOS</a>
      
      
      
      <a ng-class="{ active: active === 'md' }" ng-click="setSassPlatform('md')">Material Design</a>
      
      
      
      <a ng-class="{ active: active === 'wp' }" ng-click="setSassPlatform('wp')">Windows Platform</a>
      
      
    
  </div>


  
  <table ng-show="active === 'ios'" id="sass-ios" class="table param-table" style="margin:0;">
    <thead>
      <tr>
        <th>Property</th>
        <th>Default</th>
        <th>Description</th>
      </tr>
    </thead>
    <tbody>
      
      <tr>
        <td><code>$note-ios-color</code></td>
        
          <td><code>darken($list-ios-border-color, 10%)</code></td>
        
        <td><p>Text color of the note</p>
</td>
      </tr>
      
    </tbody>
  </table>
  
  <table ng-show="active === 'md'" id="sass-md" class="table param-table" style="margin:0;">
    <thead>
      <tr>
        <th>Property</th>
        <th>Default</th>
        <th>Description</th>
      </tr>
    </thead>
    <tbody>
      
      <tr>
        <td><code>$note-md-color</code></td>
        
          <td><code>darken($list-md-border-color, 10%)</code></td>
        
        <td><p>Text color of the note</p>
</td>
      </tr>
      
    </tbody>
  </table>
  
  <table ng-show="active === 'wp'" id="sass-wp" class="table param-table" style="margin:0;">
    <thead>
      <tr>
        <th>Property</th>
        <th>Default</th>
        <th>Description</th>
      </tr>
    </thead>
    <tbody>
      
      <tr>
        <td><code>$note-wp-color</code></td>
        
          <td><code>$input-wp-border-color</code></td>
        
        <td><p>Text color of the note</p>
</td>
      </tr>
      
    </tbody>
  </table>
  
</div>



<!-- related link --><!-- end content block -->


<!-- end body block -->

