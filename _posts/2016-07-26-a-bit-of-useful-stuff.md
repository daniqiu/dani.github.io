---
layout: post
title: Replicated - An Easier Path from SaaS to Enterprise
---

{{ page.title }}
================

<p class="meta">19 Jun 2015 - San Francisco</p>

<img src="/images/rss.png" alt="Subscribe to RSS Feed" />
<section id="textbooks">
<h1>Textbooks</h1>

<a href="http://statweb.stanford.edu/~tibs/ElemStatLearn/"><img src="images/hastie-1x.png" srcset="images/hastie-1x.png 1x, images/hastie-2x.jpg 2x, images/hastie-3x.jpg 3x" alt="The cover of Elements of Statistical Learning"></a>

<a href="http://www-bcf.usc.edu/~gareth/ISL/"><img src="images/james-1x.jpg" srcset="images/james-1x.jpg 1x, images/james-2x.jpg 2x, images/james-3x.jpg 3x" alt="The cover of An Introduction to Statistical Learning"></a>

<a href="http://web4.cs.ucl.ac.uk/staff/D.Barber/pmwiki/pmwiki.php?n=Brml.HomePage"><img src="images/barber-1x.jpg" srcset="images/barber-1x.jpg 1x, images/barber-2x.jpg 2x, images/barber-3x.jpg 3x" alt="The cover of Bayesian Reasoning and Machine Learning"></a>

<a href="https://research.microsoft.com/en-us/um/people/cmbishop/PRML/"><img src="images/bishop-1x.jpg" srcset="images/bishop-1x.jpg 1x, images/bishop-2x.jpg 2x, images/bishop-3x.jpg 3x" alt="The cover of Pattern Recognition and Machine Learning"></a>

<a href="http://www.cs.ubc.ca/~murphyk/MLbook/index.html"><img src="images/murphy-1x.jpg" srcset="images/murphy-1x.jpg 1x, images/murphy-2x.jpg 2x, images/murphy-3x.jpg 3x" alt="The cover of Machine Learning: a Probabilistic Perspective"></a>

<a href="http://stanford.edu/~boyd/cvxbook/"><img src="images/boyd-1x.jpg" srcset="images/boyd-1x.jpg 1x, images/boyd-2x.jpg 2x, images/boyd-original.jpg 3x" alt="The cover of Convex Optimization"></a>

<dl>

<dt><a href="http://statweb.stanford.edu/~tibs/ElemStatLearn/"><cite>The
Elements of Statistical Learning</cite> (Hastie, Friedman, and Tibshirani)</a>
</dt><dd>This will be our principal textbook for the first part of the course.  It's written by three statisticians who invented many of the techniques discussed. Despite its popularity and the pretty pictures, this is not an easy book.  There's an easier version of this book that covers many of the same topics, described below. (Available for free as a PDF.)

</dd><dt><a href="http://www-bcf.usc.edu/~gareth/ISL/"><cite>An Introduction to Statistical Learning</cite> (James, Witten, Hastie, and Tibshirani)</a>
</dt><dd>This book is written
by two of the same authors as The Elements of Statistical Learning. It's much less intense mathematically, and it's good for a lighter introduction to the topics. (Available for free as a PDF.)

</dd><dt><a href="http://web4.cs.ucl.ac.uk/staff/D.Barber/pmwiki/pmwiki.php?n=Brml.HomePage"><cite>Bayesian Reasoning and Machine Learning</cite> (David Barber)</a>
</dt><dd>We'll use this as a reference for probabilistic modeling, including Bayesian methods, and Bayesian networks. (Available for free as a PDF.)

</dd><dt><a href="https://research.microsoft.com/en-us/um/people/cmbishop/PRML/"><cite>Pattern Recognition and Machine Learning</cite> (Christopher Bishop)</a>
</dt><dd>This book is another very nice reference for probabilistic models and beyond.  It's highly recommended.

</dd><dt><a href="http://www.cs.ubc.ca/~murphyk/MLbook/index.html"><cite>Machine Learning: A Probabilistic Perspective</cite> (Kevin P. Murphy)</a>
</dt><dd>This book covers an unusually broad set of topics, including recent advances in the field. As such, it's a great reference to have, particularly if you continue your study of data science beyond this course.  That said, it was the required textbook for this course in 2015, and
many students found it a bit overwhelming. It's really intended as a comprehensive, PhD-level textbook.

</dd><dt><a href="https://stanford.edu/~boyd/cvxbook/"><cite>Convex Optimization</cite> (Boyd and Vandenberghe)</a>
    </dt><dd>This book was an instant hit in the machine learning community when it was published in 2004.  We will be making light use of this book, mostly for its coverage of Lagrangians and duality.  However, it's a good book to get familiar with, as it's very
well written, and it covers a lot of techniques used in more advanced machine learning literature. (Available for free as a PDF.)

    </dd></dl>
    </section>


Over the last year I've had a chance to learn a lot more about early stage
funding and made angel investments in a handful of startups. So far I've
restricted my involvement to companies with ideas in which I have significant
domain knowledge. I also insist on founders with relentless product focus, a
fierce desire to help their customers be more awesome, and excellent
communication skills. I recently met just such a company, with just such
founders, tackling a problem that has personally caused me much pain.

The company is [Replicated](http://replicated.com), and founders Grant Miller
and Marc Campbell are making it easier to roll out an on-prem Enterprise
offering based on an existing cloud-based SaaS product.

At GitHub, we burned through **a lot** of developer cycles building our own
installer (several times), securing the installation environment, coding an
automated licensing management system, integrating single sign-on services
(LDAP, Active Directory, CAS, etc, etc), building out a searchable audit system,
supporting customer-reviewable support bundles (logs and other diagnostic
output), allowing numerous backup strategies, and countless other
Enterprise-specific features that were killing our Enterprise deals. All of this
on top of hiring and building out the necessary sales, support, and accounting
teams to create a smooth Enterprise experience for our customers.

Replicated provides common Enterprise functionality (much of what I mentioned
above, and all of it eventually) that you can wrap around your SaaS product,
resulting in a first-class on-prem product in a fraction of the time. Beyond
just technology, Replicated will help you understand your Enterprise customers
through documentation on best practices and insight into the requirements and
reasons that large companies desire the features they do. Until you can
empathise with your customer (which is very hard to do as a fast-moving SaaS
startup), you'll never build the best product possible.

Getting into the Enterprise market will always be hard. But by reducing the
technology burden, Replicated plans to erase much of the pain so you can focus
on the other human-centric tasks. Not only am I an investor in Replicated, I
believe in their mission and their founders so much that I've joined as an
advisor. I understand what the uphill slog of the SaaS to Enterprise climb feels
like, and I'm going to do my best to ensure you don't have to suffer it as much
as I did.

I'm also pleased to announce that Travis CI is now shipping their Enterprise
product using Replicated. To see what the installation process is like, [watch
Grant install Travis CI
Enterprise](https://www.youtube.com/watch?v=ViN-qkcovL0&feature=youtu.be) on a
fresh server in about seven minutes. For a deeper dive, Travis CI has also
published a blog post covering some of their process in [getting their
Enterprise installer ready using
Replicated](http://blog.travis-ci.com/2015-06-19-how-we-improved-travis-ci-installation/).

In the coming weeks, you'll start to see other well-known startups launching (or
re-launching) Enterprise versions of their SaaS software on top of Replicated.
If you're looking to do the same, and want to save yourself a lot of heartache,
email [contact@replicated.com](mailto:contact@replicated.com), and start
focusing on what matters the most: your unique and kickass product.
