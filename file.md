# Admonitions Example  
> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.

# Hacks 
#### Workarounds for things not officially supported by Markdown.

## Overview.
The majority of people using Markdown will find that the [basic](https://www.abc.com)
and [extended](https://www.abc.com) syntax elements cover their needs. But chances are that if you use Markdown long enough, you’ll inevitably discover that it doesn’t support something you need. This page provides tips and tricks for working around Markdown’s limitations.

> [!TIP]
> These hacks aren't guaranteed to work in your Markdown application. If you need to use these hacks frequently, you should consider writing using something other than Markdown.

## Underline
Underlined text is not something you typically see in web writing, probably because underlined text is nearly synonymous with links. However, if you’re writing a paper or a report, you may need the ability to underline words and phrases. A couple of applications like [Bear](www.google.com) and [Simplenote](www.google.com) provide support for underlining text, but Markdown doesn’t natively support underlining. If your Markdown processor supports [HTML](www.google.com), you can use the 
<code class="language-plaintext highlighter-rouge">&lt;ins&gt; </code> HTML tag to underline text in your document.

<code class = "language-plaintext highlighter-rouge" >Some of these words <ins>will be underlined</ins>.

# Indent Tab 
Tabs and whitespace have a special meaning in Markdown. You can use trailing whitespace to create [line breaks](www.a.com), and you can use tabs to create [code blocks](www.b.com). But what if you need to indent a paragraph the old-fashioned way, using the tab key? Markdown doesn’t provide an easy way of doing that.

Your best bet might be to use a Markdown editor that supports indentation. This is common in applications that are more oriented towards desktop publishing. For example, [iA Writer](www.c.com) allows you to customize indentation settings for the editor in the application preferences. It also provides template customization options so that you can make the rendered document look the way you expect it to, indentation and all.

Another option, if your Markdown processor supports [HTML](www.d.com), is to use the HTML entity for non-breaking space 
(<code class="language-plaintext highlighter-rouge">&amp;nbsp;</code>). 
This should probably be your option of last resort as it can get awkward. Basically, every <code class="language-plaintext highlighter-rouge">&amp;nbsp;</code> in your Markdown source will be replaced with a space in the rendered output. So if you stick four instances of <code class="language-plaintext highlighter-rouge">&amp;nbsp;</code> before a paragraph, the paragraph will look like it’s indented four spaces.

# Image Local 
 ![Tux, the Linux mascot](a/tux.avif)
# Image Link 
 ![Sonny and Mariel high fiving.](https://content.codecademy.com/courses/learn-cpp/community-challenge/highfive.gif)
