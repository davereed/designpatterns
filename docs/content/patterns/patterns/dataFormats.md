---
title: "Data formats"
preview: true
---

[pattern]
### Date and time

#### Formats
<table class="table table-bordered" style="max-width: 600px;">
    <colgroup>
        <col style="width: 60%">
        <col style="width: 40%;">
    </colgroup>
    <tbody>
        <tr>
            <td><code>time</code></td>
            <td>10:00 AM</td>
        </tr>
        <tr>
            <td><code>short date</code></td>
            <td> Jan 11</td>
        </tr>
        <tr>
            <td><code>long date</code></td>
            <td> Apr 23, 2010</td>
        </tr>
        <tr>
            <td><code>short date, time</code></td>
            <td> Feb 5, 8:00 AM</td>
        </tr>
        <tr>
            <td><code>long date, time</code></td>
            <td> Feb 8, 2014, 1:00 PM</td>
        </tr>
        <tr>
            <td><code>day of week, time</code></td>
            <td> Mon, 7:30 AM</td>
        </tr>
        <tr>
            <td><code>day of week, short date, time</code></td>
            <td> Mon, Mar 15, 3:25 PM</td>
        </tr>
    </tbody>
</table>

#### Smart format

For dates/times associated with user generated data (e.g., notes, documents), use the `smart format`, which changes depending on the current date and the date to display.
<table class="table table-bordered" style="max-width: 600px;">
    <colgroup>
        <col style="width: 60%">
        <col style="width: 40%;">
    </colgroup>
    <tbody>
        <tr>
            <td>If the date is in the past or future on the current day, format as <code>time</code> only</td>
            <td>10:00 AM</td>
        </tr>
        <tr>
            <td>If the date is in the past or future within the current calendar year, format as <code>short date</code></td>
            <td>Jan 11</td>
        </tr>
        <tr>
            <td>If the date is in the past or future outside the current calendar year, format as <code>long date</code></td>
            <td>Apr 23, 2010</td>
        </tr>
    </tbody>
</table>

#### Other

<table class="table table-bordered" style="max-width: 600px">
    <colgroup>
        <col style="width: 60%">
        <col style="width: 40%;">
    </colgroup>
    <tbody>
        <tr>
            <td>For reminders or appointments, show both time and date</td>
            <td>Jun 8, 8:00 AM <br>Today, 8:00 AM</td>
        </tr>
        <tr>
            <td>Separate ranges with an en-dash without a space</td>
            <td>Jun 15–Jun 16 <br> Dec 20, 2014–Jan 2, 2015</td>
        </tr>
        <tr>
            <td>If a time range shares a common AM/PM, append only on the end of the range</td>
            <td>10:00–11:00 AM <br>10:00 AM–12:30 PM</td>
        </tr>
    </tbody>
</table>

[/pattern]

[pattern]
### File sizes

- 340 KB (round to nearest KB)
- 4.13 MB (two decimal max)
- 3.22 GB (two decimal max)
- 1.13 TB (two decimal max)

[/pattern]
