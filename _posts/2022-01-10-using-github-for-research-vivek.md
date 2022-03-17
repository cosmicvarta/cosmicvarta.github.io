---
layout: post
title:  "Using GitHub for Academic Research"
author: Vivek
permalink: /using-github-for-research-vivek
categories: [General]
tags: [General, Popular]
class: [Tools and Techniques]
image: assets/images/github_article.png
featured: False
hidden: False
popular: true
---

> GitHub has become the go-to tool for software engineers across the world to keep their codes together and collaborate with each other. Being easy, seamless, and available on all the platforms makes it a brilliant choice indeed.
>
---


I am involved in academic research for quite some time now and can find some pretty good uses for this platform. Of course, GitHub was designed to keep the codes together and collaborate and this is the backbone of research too, which is why I find GitHub quite appealing.

There are obvious benefits of using GitHub:
- Keeping all the codes and data files together offline as well as a backup on the GitHub servers.
- Version control for all the files.
- Collaborating on projects together.
- Managing the research projects and keeping track of the issues.
- Free hosting for websites.

For beginners, it is helpful to go through the basic documentation about GitHub. For example a YouTube video introducing GitHub is available below:


<iframe width="560" height="315" src="https://www.youtube.com/embed/w3jLJU7DT5E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---


Besides the [GitHub](https://docs.github.com/en) website itself, there are plenty of other websites and tutorials available on the web. I am including a few bare essentials that one needs to go through in order to understand what GitHub is:

- [Creating a git repository](https://docs.github.com/en/github/getting-started-with-github/create-a-repo)
- [Cloning a git repository](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository)
- [A tutorial for git usage](https://docs.gitlab.com/ee/gitlab-basics/start-using-git.html)
- [Guide to git version control](https://medium.com/faun/beginners-guide-to-version-control-using-git-and-github-8bf44b421140)
- [Introduction to Branches](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-branches)
- [GitHub Project Boards](https://docs.github.com/en/github/managing-your-work-on-github/about-project-boards)
- [Github pages](https://pages.github.com/)


The idea of having a single repository (in git terminology folder is repository) for a project helps a lot in reducing confusion and saves a lot of time. It indeed is a good habit. Making that repository a git repository and putting it on GitHub is an even better habit. People working with Jupyter notebooks may find GitHub extremely helpful, especially in terms of executing the notebooks in the clouds. [nbviewer](https://nbviewer.jupyter.org/) can load the notebooks directly from the git repository which can then be executed directly on [binder](https://mybinder.org/). Even [Google colab](https://colab.research.google.com/) allows the import of notebooks from GitHub directly to be executed there. [HackMD](https://hackmd.io/), a Markdown editor allows the files to be pushed to and pulled from GitHub.

In astronomy, most of the code is often open-source and available to the community. Some researchers provide links to their codes hosted on GitHub which becomes easier to obtain and raise any issues. The point is that the familiarity with GitHub is advantageous. People sometimes present their entire work, including the codes, plots, and related text files on GitHub as a repository which indeed serves as a welcome step towards reproducible research.

Now, my personal bent towards git is motivated by the reproducibility of research. In the world of academic research reproducibility has often been cited as a problem (see this [BBC report](https://www.bbc.com/news/science-environment-39054778) or [Nature article](https://www.nature.com/articles/sc201717)). Reproducibility should be the backbone of research as scientific findings work on this principle. Maintaining a git project should help in establishing this easily. One may put the link to the entire working repository once their findings are published so that anyone willing to re-do the analysis does that seamlessly. [People have even proposed](https://slate.com/technology/2017/04/we-need-a-github-for-academic-research.html) a GitHub type of social network for academic research.


I have tried to implement GitHub for all my research projects, and the workflow has only gone smoother with time. The project management becomes easy, versions are easy to track and overall the repository structure becomes more transparent with time. I don’t waste time looking for individual files anymore, as they have been neatly arranged in the respective places. With a backup on the GitHub cloud server, it becomes easy to access any item from any device. Working on multiple devices too becomes easy as I can run multiple items in parallel and then push to the respective branches and merge them subsequently. Moreover, the project boards are a neat way to organize all the work. We can have work in progress, work to be done, and work that has been completed arranged in the form of cards. We may open an issue from these cards themselves.

*Github pages* are also one of the noticeable features of Github as it lets one host personal webpages on GitHub, which again I feel is well suited for us. The static website can be put up easily using [Jekyll](https://jekyllrb.com/). The [academic pages template](https://academicpages.github.io/) is used by thousands of researchers and scientists around the world to keep their content together on a static web page. My [personal website](https://viveikjha.github.io/) is hosted on GitHub too. Pushing things on the website is as easy as typing up a markdown or HTML file and pushing it onto GitHub.


GitHub as a service provides us with an option to manage our workflow in an eficient way, without worrying about versions of documents and provides seamless collaboration features. I hope with this article I have provided some useful insight into this service.

---

<div id="disqus_thread"></div>
<script>
    /**
    *  RECOMMENDED CONFIGURATION VARIABLES: EDIT AND UNCOMMENT THE SECTION BELOW TO INSERT DYNAMIC VALUES FROM YOUR PLATFORM OR CMS.
    *  LEARN WHY DEFINING THESE VARIABLES IS IMPORTANT: https://disqus.com/admin/universalcode/#configuration-variables    */
    /*
    var disqus_config = function () {
    this.page.url = PAGE_URL;  // Replace PAGE_URL with your page's canonical URL variable
    this.page.identifier = PAGE_IDENTIFIER; // Replace PAGE_IDENTIFIER with your page's unique identifier variable
    };
    */
    (function() { // DON'T EDIT BELOW THIS LINE
    var d = document, s = d.createElement('script');
    s.src = 'https://cosmicvarta-in.disqus.com/embed.js';
    s.setAttribute('data-timestamp', +new Date());
    (d.head || d.body).appendChild(s);
    })();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>

----
----
