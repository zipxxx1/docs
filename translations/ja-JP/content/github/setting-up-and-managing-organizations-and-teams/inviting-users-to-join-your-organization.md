---
title: Organization に参加するようユーザを招待する
intro: 'Organization のメンバーとして追加したい人がいれば、その人の {% data variables.product.product_name %} ユーザ名またはメール アドレスを使用して招待することができます。'
permissions: Organization owners can invite users to join an organization.
redirect_from:
  - /articles/adding-or-inviting-members-to-a-team-in-an-organization/
  - /articles/inviting-users-to-join-your-organization
versions:
  free-pro-team: '*'
---

{% tip %}

**Tips**:
- Organization がユーザ単位の有料プランである場合、新しいメンバーを招待して参加させる、または Organization の以前のメンバーを復帰させる前に、そのためのライセンスが用意されている必要があります。 詳細は「[ユーザごとの価格付けについて](/articles/about-per-user-pricing)」を参照してください。 {% data reusables.organizations.org-invite-expiration %}
- If your organization requires members to use two-factor authentication, users that you invite must enable two-factor authentication before accepting the invitation. For more information, see "[Requiring two-factor authentication in your organization](/github/setting-up-and-managing-organizations-and-teams/requiring-two-factor-authentication-in-your-organization)" and "[Securing your account with two-factor authentication (2FA)](/github/authenticating-to-github/securing-your-account-with-two-factor-authentication-2fa)."

{% endtip %}

{% data reusables.profile.access_profile %}
{% data reusables.profile.access_org %}
{% data reusables.organizations.people %}
{% data reusables.organizations.invite_member_from_people_tab %}
{% data reusables.organizations.invite_to_org %}
{% data reusables.organizations.choose-to-restore-privileges %}
{% data reusables.organizations.choose-user-role %}
{% data reusables.organizations.add-user-to-teams %}
{% data reusables.organizations.send-invitation %}
{% data reusables.organizations.user_must_accept_invite_email %} {% data reusables.organizations.cancel_org_invite %}

### 参考リンク
- [Team へのOrganization メンバーの追加](/articles/adding-organization-members-to-a-team)
