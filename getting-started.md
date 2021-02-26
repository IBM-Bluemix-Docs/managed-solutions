---


copyright:
  years: 2018, 2019
lastupdated: "2019-08-09"


---

{:new_window: target="_blank"} 
{:shortdesc: .shortdesc} 
{:codeblock: .codeblock} 
{:pre: .pre} 
{:screen: .screen} 
{:tsSymptoms: .tsSymptoms} 
{:tsCauses: .tsCauses} 
{:tsResolve: .tsResolve} 
{:tip: .tip} 
{:important: .important} 
{:note: .note} 
{:download: .download} 
{:external: target= .external} 

# Getting started
{: #getting-started } 

Get started with managed applications by enabling your IBM Cloud account for IBM Services for Managed Applications.
{: shortdesc} 

Get started by enabling your organization's IBM Cloud account for IBM
Services for Managed Applications.

Managed Applications Portal, the management console for IBM Services for
Managed Applications, is hosted in IBM Cloud. Access to IBM Cloud
resources is governed by an IBM Cloud account. Access to IBM Services
for Managed Applications must be enabled for that IBM Cloud account.
Anyone who wants to use Managed Applications Portal must also be a
member of the IBM Cloud account for which access has been enabled.

For any given organization, just one person, one time, must enable
access to IBM Services for Managed Applications for the IBM Cloud
account of that organization. To enable access for that IBM Cloud
account, one person enters an access code on the home page of IBM
Services for Managed Applications. Once enabled, no further action is
required.

Your sales representative or Delivery Project Executive will give you
the access code to enable your IBM Services for Managed Applications.

Until you enable access to IBM Services for Managed
Applications, when you enter IBM Cloud Console and navigate to IBM
Services for Managed Applications you receive only a welcome page on
which you can enter your access code.
{: note} 

## Proceed to the Managed Solutions welcome page
{: #13231-proceed-to-the-managed-solutions-welcom } 

Because Managed Applications Portal is hosted in IBM Cloud, you must
open the [IBM Cloud Console](https://cloud.ibm.com/login){: external} login page in
your browser. How you proceed to the Managed Solutions welcome page
depends on whether you have an IBM Cloud
account.

### I have IBM Services for Managed Applications but no IBM Cloud account
{: #13231-i-have-ibm-services-for-managed-applica } 

When you create an account the name of the account is based on the name
of the individual who created that account, To avoid confusion, after
you create the master account you should change the name of the account
to a name more suitable for your organization as discussed later in this
topic.

1.  [Create an IBM Cloud
    account](/docs/account/account_faq.html#create-account)
    with `IBMid` using an email address that you want to own the account
    for all your users.
2.  Ask your Delivery Project Executive for an access code.
3.  Log in to [IBM Cloud Console](https://cloud.ibm.com/login){: external} with that
    email address.
4.  Continue with *_Enable access to IBM Services for Managed
    Applications_* later in this topic.

### I have an IBM Cloud account...
{: #13231-i-have-an-ibm-cloud-account } 

#### And I have IBM Services for Managed Applications
{: #13231-and-i-have-ibm-services-for-managed-app } 

1.  Ask your Delivery Project Executive for an access code.
2.  Log in to [IBM Cloud Console](https://cloud.ibm.com/login){: external}.
3.  Continue with *_Enable access to IBM Services for Managed
    Applications_* later in this topic.

#### But I do not have IBM Services for Managed Applications
{: #13231-but-i-do-not-have-ibm-services-for-mana } 

1.  Contact sales and purchase IBM Services for Managed Applications.
2.  Ask your Delivery Project Executive for an access code.
3.  Log in to [IBM Cloud Console](https://cloud.ibm.com/login){: external}.
4.  Continue with *_Enable access to IBM Services for Managed
    Applications_* later in this topic.

## Enable access to IBM Services for Managed Applications
{: #13231-enable-access-to-ibm-services-for-manag } 

if you have access to more than one IBM Cloud account, ensure you select
the account you want enabled for access before validating the access
code.

1.  Open IBM Cloud Console.

2.  From the list next to <svg aria-label="pencil with paper"
    alt="pencil with paper" viewBox="0 0 32 32" width="16"
    height="16"><path d="M22 22v6H6V4h10V2H6a2 2 0 0 0-2 2v24a2 2 0 0
    0 2 2h16a2 2 0 0 0 2-2v-6z"/><path d="M29.537 5.76L26.24
    2.463a1.58 1.58 0 0 0-2.236 0L10 16.467V22h5.533L29.537 7.995a1.58
    1.58 0 0 0 0-2.235zM14.704 20H12v-2.704l9.44-9.441 2.705
    2.704zM25.56 9.145l-2.704-2.704 2.267-2.267 2.704
    2.704z"/></svg>, select the account with your managed
    applications.

3.  Click **Menu**, ≡.

4.  Select **Managed Solutions**.
    
    The Managed Solutions menu appears.

5.  Click **Overview**.
    
    The Welcome to Managed Application Portal page appears.

6.  Type your access code in **Have you already started the onboarding
    process and have a code**?

7.  Click **Validate**.
    
    If your access code does not validate, you return to the Welcome to
    Managed Application Portal page to try again. If your access code
    successfully validates, the Link Account dialog appears.

8.  Click **Yes** to enable IBM Services for Managed Applications for
    the IBM Cloud account shown on the dialog.
    
    Your access is enabled, you can manage your IBM Services for Managed
    Applications from IBM Cloud Console, and the welcome dialog appears.

9.  Click **Get Started**.

## Add users to your account
{: #13231-add-users-to-your-account } 

You can add users to the IBM Cloud account you created. You invite a
user to an IBM cloud account by adding their email address to the
invitation. The user receives no notification. The invitation only
permits access to your account by an IBM Cloud user whose username
matches the email address you added to the invitation. The invitee must
have, or create, an IBM Cloud account with the same email address.

1.  To invite a user to the account, follow the instructions in
    [Inviting
    users](/docs/account?topic=account-iamuserinv)
    from the IBM Cloud documentation. Under **Assign access to**, select
    `Resource` and under **Services**, select `Managed Solutions`. If
    `Managed Solutions` is not available under **Services**, select `All
    Identity and Access enabled services`.
2.  To elevate permissions of a user to allow that user to invite other
    users to the account, follow the instructions in [Assigning access
    to account management
    services](/docs/account?topic=account-account-services)
    to modify the user. As discussed in the article, you can provide
    very granular permission to invite users with a policy that gives
    the user access to all account management services in the account by
    selecting **All account management services** with the
    `Administrator` role assigned.

## Change the account name
{: #13231-change-the-account-name } 

The account name appears in the list next to your profile in the header
of IBM Cloud Console. When you create an IBM Cloud account, its account
name defaults to the name of the user that created the account; for
example, `John Doe's Account`. Most organizations prefer their company
name rather than the name of some user. You can change the default
account name to something more appropriate to your company. Follow the
instructions in [Editing the account
name](/docs/account?topic=account-account_settings#change-acct-name).
