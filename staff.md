---
layout: page
title: Staff
description: Data 8 Fall 2022 Staff
---

# Staff

## Instructors

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}

<div class="role flex">
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}
</div>

## Lead TAs

_All office hours are held in-person in Warren 101 unless otherwise specified_

{% assign leads = site.staffers | where: 'role', 'Lead GSI' %}

<div class="role flex">
{% for staffer in leads %}
{{ staffer }}
{% endfor %}
</div>

## Teaching Assistants

_All office hours are held in-person in Warren 101 unless otherwise specified_

{% assign teaching_assistants = site.staffers | where: 'role', 'GSI' %}

<div class="role flex">
{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
</div>

## Tutors

{% assign tutors = site.staffers | where: 'role', 'Tutor' %}

<div class="role flex">
{% for staffer in tutors %}
{{ staffer }}
{% endfor %}
</div>

## Readers

{% assign readers = site.staffers | where: 'role', 'Reader' %}

<div class="role flex">
{% for staffer in readers %}
{{ staffer }}
{% endfor %}
</div>

<script src="../assets/darkmode.js"></script>
<script>
  window.addEventListener("DOMContentLoaded", (event) => {
    onLoad();
});
</script>
