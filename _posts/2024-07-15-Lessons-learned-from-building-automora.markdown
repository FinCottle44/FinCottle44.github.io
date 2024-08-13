---
layout: post
title: Lessons Learned from Building Automora
date: 2024-07-13 12:00:00 +0000
image: '/images/automora-dashboard.jpg'
tags: [technology, AWS, machine learning]
---
A month ago, if you had asked me what I thought I would have learned from developing and launching Automora, I would have talked about the technical challenges, the long hours, and the excitement of bringing a new product to market. But the reality of what I’ve learned goes far deeper than that. Building Automora—a system that leverages a suite of AWS services to provide car dealerships with a much faster alternative to the traditional 48-hour image processing turnaround—has been a crash course in adaptability, customer service, and the relentless pursuit of perfection.

The concept behind Automora was simple: provide car dealerships with a way to process and label images in near real-time, eliminating the need to rely on third-party companies with painfully slow turnarounds. However, taking this idea from concept to reality has been anything but straightforward.

<h4>The Challenge of Building with AWS</h4>
From the start, we knew we would be relying heavily on AWS services to build Automora. The cloud offers flexibility, scalability, and a range of powerful tools, but integrating these services to work seamlessly with our custom image processing algorithms was a challenge in itself. AWS provides the building blocks, but it’s up to you to assemble them into something that not only works but works well under the pressure of real-world demands.

We’ve had to implement everything from image labeling for machine learning models to building an infrastructure that could handle errors on the fly—because when you’re dealing with paying customers, there’s no room for downtime. Learning how to fix issues as they arise while keeping the system live has been one of the most valuable lessons. It’s taught me the importance of resilience in system design and the necessity of having robust monitoring and alerting systems in place.

<div class="gallery-box">
  <div class="gallery">
    <img src="/images/am repro.png" alt="Automora Development">
    <img src="https://d2908q01vomqb2.cloudfront.net/972a67c48192728a34979d9a35164c1295401b71/2020/10/15/Sampledashboard.png" alt="AWS Integration">
  </div>
</div>
<h4>The Importance of Customer-Centric Development</h4>
Another critical lesson has been the need to keep the customer at the forefront of every decision. The initial version of Automora was built to solve a specific problem: speed up image processing. But as we rolled out the service, customer feedback made it clear that we needed to do more than just deliver speed; we needed to ensure accuracy, provide an intuitive interface, and offer robust customer support.

This meant continuously implementing new features and refining existing ones. Each feature was born out of a direct response to customer needs or complaints. Whether it was adding new labeling options, improving the AI's accuracy, or integrating with other dealership management software, the work has been non-stop. It’s a reminder that launching a product is just the beginning—the real work starts when you have to maintain and improve it under the scrutiny of active users.

<h4>Adaptability is Key</h4>
Finally, adaptability has been crucial. No matter how much planning and foresight you put into a project, unexpected challenges will arise. We’ve had to pivot quickly, troubleshoot issues we never anticipated, and roll out patches and updates at a moment’s notice. These experiences have underscored the importance of being flexible and willing to adapt on the fly.

For instance, when we encountered an unexpected bug that affected image processing times for some users, we had to diagnose the issue, implement a fix, and roll it out across all active instances—all without disrupting service. These are the moments that test your resolve as a developer and entrepreneur, but they also provide invaluable lessons that no amount of planning can teach.

<p><iframe src="https://player.vimeo.com/video/946263441?h=314c1ea1b6" frameborder="0" allowfullscreen></iframe></p>
<h4>Looking Ahead</h4>
As Automora continues to grow, the lessons learned over the past month will shape how we evolve. We’re not just building a tool; we’re building a service that car dealerships rely on to keep their operations running smoothly. This responsibility drives us to continually improve, innovate, and stay ahead of the curve.