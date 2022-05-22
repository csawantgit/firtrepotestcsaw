---
year: 1883
layout: demo_template
---
{% include footer.txt %}

# firtrepotestcsaw

It all started in the year {{page.year}} by {{site.author}}.

{% for item in site.data.chronology %}
- {{ item.name }}, {{ item.place }}
{% endfor %}

# Markdown Test Content

This is my first markdown **overview** line.
## This is an unordered list

- [AngularJS] - HTML enhanced for web apps!
- [Ace Editor] - awesome web-based text editor
- [markdown-it] - Markdown parser done right. Fast and easy to extend.

## This is an ordered list

1. [AngularJS] - HTML enhanced for web apps!
1. [Ace Editor] - awesome web-based text editor
1. [markdown-it] - Markdown parser done right. Fast and easy to extend


And, this is a link to [www.google.com](google).

| Year | Place |
| ----- | ----- |
| 1825 | New Brunswick |
| 1845 | Oregon |
| 1870 | Quebec |
| 1871 | Wisconsin |

{% if Profile.PREFERED_LANGUAGE == "Spanish" %} 
Hola!
{% elsif Profile.PREFERED_LANGUAGE == "English" %}
Hello! 
This is a conditonal tag example.
{% else %}
Hello!
{% endif %}


{% assign eyes = "stars" %}
The {{ eyes }} sparkled and twinkled like bejewelled
sword handles.

This is a variable test.


| Years | Company |
| ... | ... |
| 1972 | It happened |
| 1999 | Did it happen |

```
imports requests
printf ("This is a code block")
```

Issue the following command : `git clone...`

![test image](https://images.hindustantimes.com/img/2022/05/20/550x309/Grand_Canyon_of_Mars_Instagram_European_Space_Agency_Images_1653028759242_1653028771758.PNG)

<hr>
## Setting up your IBM Cloud account

This tutorial walks you through the steps for setting up an account in IBM Cloud®. By completing this tutorial, you learn how to set up account authentication, manage your account settings, effectively organize resources in your account, and control access to resources.

#### Step 5: Set preferences for receiving notifications

Complete the following steps to set your preferences for receiving various types of notifications:

<ol>
<li>To receive notifications about IBM Cloud platform-related, or resource-related items, go to the **Avatar** icon **Profile** > **Notification preferences**.</li>
	<ul>
		<li>When you set IBM Cloud platform notifications, you receive email notifications that are associated with only the platform. You do not receive notifications about events that are associated with IBM Cloud services. By default, all platform notifications are turned off.</li>
		<li>If you update your preferences on resource activity, such as incidents, maintenance, security bulletins, or infrastructure service updates, the notifications are for only the services you use or the devices that you have provisioned. By default, all infrastructure notifications are turned off.</li>
	</ul>
<li>To receive spending notifications, go to **Manage** > **Billing and usage** > **Spending notifications** in the IBM Cloud console. Or, you can access it directly from the [Notification preferences](https://cloud.ibm.com/user/notifications) page by clicking **Manage** in the **Billing and Usage** section.</li>
</ol>

You receive notifications when you reach 80%, 90%, and 100% of the spending thresholds that you specify. Enter the dollar amount to set a spending threshold when you set up your spending notification. For more information, see [Setting spending notifications](https://cloud.ibm.com/docs/billing-usage?topic=billing-usage-spending).

#### Step 7: Set up access

IAM access groups provide a way for you to quickly and easily assign access to multiple resources in your account at one time.

<ol>
<li>Create an access group.</li>
	<ol>
		<li>Go to **Manage** > **Access (IAM)** > **Access Groups** in the IBM Cloud console.</li>
		<li>Click **Create**.</li>
		<li>Enter a name for your group, and click **Create**. For example, if you know multiple users in your account need to be able to apply subscription codes, track usage, or perform other billed-related tasks, you might name your group `Billing-Editor-Access`.</li>
	</ol>
<li>Assign access to the group.</li>
	<ol>
		<li>Click **Access policies** > **Assign access**.</li>
		<li>Select the type of access to assign:</li>
		<ul>
			<li>**IAM services**: Assigns access to IAM-enabled services, which are services that are managed by using IAM access control and assigned to a resource group.</li>
			<li>**Account management services**: Assigns access to manage platform services, such as billing, license and entitlements, and enterprises.</li>
		</ul>
		<li>Select all roles that apply.</li>
		<li>Click **Add** > **Assign**.</li>
	</ol>
</ol>
See [What makes a good access group strategy?](https://cloud.ibm.com/docs/account?topic=account-account_setup#resource-group-strategy) for details about how to best set-up your access groups.

#### Step 9: Explore your support options

You can use the Support Center to get help with any issues that you might encounter. To access the **Support** Center, click Support in the console menu bar.
<ul>
	<li>The Help just for you section features links to common tasks, troubleshooting, and FAQs specific to the resources in your account.</li>
	<li>The Featured FAQs section provides FAQs related to platform tasks, for example, resetting your password, IAM, and upgrading your account.</li>
	<li>The Contact support section provides the options for getting in touch with a support representative: start a live chat, contact by phone, or create a support case.</li>
</ul>