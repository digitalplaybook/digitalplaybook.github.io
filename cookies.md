---
layout: page
title: Cookies
---

# Cookies Policy
{: .govuk-heading-xl}

We do not collect any personal information that could be used to identify you.
{: .govuk-body}

Find out more about [how to manage cookies](https://ico.org.uk/your-data-matters/online/cookies/).
{: .govuk-body}

## How cookies are used
{: .govuk-heading-l}
### Our cookie banner
{: .govuk-heading-m}

When you first visit the website, you will see a banner asking if you accept cookies. We’ll store a cookie to remember which option you selected. You can always change your mind and change your choice on this page.
{: .govuk-body}

Next time you visit the site, we will remember your preference and not show the banner again.
{: .govuk-body}

To do this, the website sets the following cookies:
{: .govuk-body}

<table class="govuk-table">
<thead class="govuk-table__head">
<tr class="govuk-table__row">
<th scope="row" class="govuk-table__header">Name</th>
<th scope="row" class="govuk-table__header">Purpose</th>
<th scope="row" class="govuk-table__header">Expires</th>
</tr>
</thead>
<tbody class="govuk-table__body">
<tr class="govuk-table__row">
<td class="govuk-table__cell">cookies_preferences_set</td>
<td class="govuk-table__cell">Lets us know you've seen our cookie message.</td>
<td class="govuk-table__cell">1 month</td>
</tr>
<tr class="govuk-table__row">
<td class="govuk-table__cell">cookies_policy</td>
<td class="govuk-table__cell">Saves your cookie choices.</td>
<td class="govuk-table__cell">1 month</td>
</tr>
</tbody>
</table>

<form id="cookie-form" class="govuk-form govuk-!-margin-top-9" onsubmit="return false;">
    <fieldset class="govuk-fieldset">
        <legend class="govuk-fieldset__legend govuk-fieldset__legend--l govuk-!-margin-bottom-6">Change your cookie options</legend>
        <div class="govuk-form-group govuk-radios">
            <div class="govuk-radios__item" data-children-count="1">
                <input type="radio" name="cookies-usage" id="radio-ga-on" value="on" class="govuk-radios__input">
                <label for="radio-ga-on" class="govuk-label govuk-radios__label">Use cookies that measure my website use</label>
            </div>
            <div class="govuk-radios__item" data-children-count="1">
                <input type="radio" name="cookies-usage" id="radio-ga-off" value="off" class="govuk-radios__input">
                <label for="radio-ga-off" class="govuk-label govuk-radios__label">Do not use cookies that measure my website use</label>
            </div>
        </div>
    </fieldset>

    <button class="govuk-button" type="submit" onclick="saveCookiePrefs();">Save changes</button>
</form>

<script language="javascript">
    document.addEventListener('DOMContentLoaded', function(event) {
        event.preventDefault()
        var _cookie_options_saved_el = document.querySelector(".cookie-message__confirmation")
        function saveCookiePrefs() {
            if (document.getElementById("radio-ga-on").checked) {
                acceptCookies()
            } else {
                declineCookies()
            }
            _cookie_options_saved_el.classList.add('saved')
            scroll(0,0)
        }

        var cookiesPolicy = JSON.parse(getCookie("cookies_policy"))
        if (cookiesPolicy != null) {
            if (cookiesPolicy.usage) {
                document.getElementById("radio-ga-on").checked = true
            } else {
                document.getElementById("radio-ga-off").checked = true
            }
        }

        // expose save function to window
        window.saveCookiePrefs = saveCookiePrefs;
    });
</script>
