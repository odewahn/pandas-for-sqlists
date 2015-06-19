# Pandas for SQL-ists

## Andrew Odewahn |  @odewahn

http://odewahn.github.io/publishing-workflows-for-jupyter

---
# Goal

<div style="font-size: 150%">
Demonstrate an authoring and publishing process for long-form content (books, courses, tutorials, etc) that can include the IPython Notebook computing environment, but are authored outside of the IPython authoring environment.  (And, hopefully, Jupyter very soon!)
</div>

---

# Write in Markdown, AsciiDoc, or HTML

* Easily diff-able formats (vs. JSON, which is not)
* Collaboration / GitHub friendly 
* Specify executable code cells using a simple, declarative format.  For example:

<pre data-executable='true'>
print "hello world!"
</pre>

---
# Now make a plot

<pre data-executable='true'>
%pylab inline
x = np.linspace(0, 10)
plt.plot(x, np.sin(x), x, np.cos(x))
</pre>

