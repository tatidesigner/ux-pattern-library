---
layout:         pattern
title:          Alerts
date:           2016-01-28 00:00:00

categories:     component
tags:
- atomic
- pattern
- alerts

slug:           alerts

url_styles:     "patterns/_alerts.scss"

description:    Examples of alerts in a semi-real world context.

info:           When something goes wrong, alerts clarify an issue and/or notify users of the problem, communicate the severity of the issue, and provide an actionable next step, if necessary. When implementing the alert pattern, consider the alert’s location; closer proximity to the action/event associates the issue (and hence resolution) with a specific page element, whereas more distant placement communicates a more systematic issue. Seek to balance graphic and content elements, where less is usually more. We recommend reading stuff about "microcopy."
---

<h3 class="hd-6 example-set-hd">Error Alert with Message and Button</h3>
<div class="example-set">
    <div class="alert alert-error" role="alert" aria-labelledby="alert-title-error"
         tabindex="-1">
        <span class="icon alert-icon icon-warning" aria-hidden="true"></span>

        <div class="alert-message-with-action">
            <h3 class="sr-only alert-title" id="alert-title-error">
                Unable to load chart.
            </h3>

            <p class="alert-copy">
                We are unable to load this chart.
            </p>
        </div>

        <button type="button" class="alert-action btn-neutral btn">
            Read More <span class="sr-only">about charts</span>
        </button>
    </div>
</div>

<h3 class="hd-6 example-set-hd">Success Alert with Title and Message</h3>
<div class="example-set">
    <div class="alert alert-success" role="alert" aria-labelledby="alert-title-success"
         tabindex="-1">
        <span class="icon alert-icon icon-check" aria-hidden="true"></span>

        <div class="alert-message">
            <h3 class="alert-title" id="alert-title-success">
                We've received your essay submission!
            </h3>

            <p class="alert-copy-with-title">
                Hang tight while the rest of the class catches up.  We'll let you know
                when your peers have graded your essay and when you can help grade theirs
                as well.  In the meantime,
                <a href="http://example.com">check out what's next in the course</a>.
            </p>
        </div>
    </div>
</div>

<h3 class="hd-6 example-set-hd">Warning Alert with Title, Message, and Button</h3>
<div class="example-set">
    <div class="alert alert-warning" role="alert" aria-labelledby="alert-title-warning"
         tabindex="-1">
        <span class="icon alert-icon icon-warning" aria-hidden="true"></span>

        <div class="alert-message-with-action">
            <h3 class="alert-title" id="alert-title-warning">
                Waiting for Peer Responses
            </h3>

            <p class="alert-copy-with-title">
                All submitted peer responses have been assessed.  Check back later to see if
                more students have submitted responses.  You'll receive your grade after you've
                completed all the steps for this problem and your peers have assessed your
                responses.
            </p>
        </div>

        <button type="button" class="alert-action btn-neutral btn">
            Reload <span class="sr-only">peer responses</span>
        </button>
    </div>
</div>


<h3 class="hd-6 example-set-hd">Warning Alert with Message Only</h3>
<div class="example-set">
    <div class="alert alert-warning" role="alert" aria-labelledby="alert-warning-publish-title"
         tabindex="-1">
        <span class="icon alert-icon icon-warning" aria-hidden="true"></span>

        <div class="alert-message">
            <h3 class="sr-only alert-title" id="alert-warning-publish-title">
                Caution: The last published version of this unit is live.
            </h3>

            <p class="alert-copy">
                Caution: The last published version of this unit is live.  By publishing
                changes you will change the student experience.
            </p>
        </div>

    </div>
</div>

<h3 class="hd-6 example-set-hd">Information Alert with Title and Message</h3>
<div class="example-set">
    <div class="alert alert-information" role="alert" aria-labelledby="alert-title-information"
         tabindex="-1">
        <span class="icon alert-icon icon-bullhorn" aria-hidden="true"></span>

        <div class="alert-message">
            <h3 class="alert-title" id="alert-title-information">
                A better measure of total interest in your course
            </h3>

            <p class="alert-copy-with-title">
                The total enrollment metric below now includes all students who
                have ever registered for this course.
            </p>
        </div>
    </div>
</div>
