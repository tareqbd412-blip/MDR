MASTER PROMPT: AMAR HISAB (আমার হিসাব)

1. APP IDENTITY

Build a complete Islamic daily self-accountability and personal development application named:

আমার হিসাব (Amar Hisab)

Tagline: নিজের হিসাব নিজে রাখুন, প্রতিদিন নিজেকে উন্নত করুন।

The app should help Muslims track their daily worship, Islamic learning, good deeds, personal responsibilities, relationships, charity, and self-development.

The app must support both individual use and WhatsApp-style group-based management.

The design should be peaceful, clean, modern, minimal, respectful, and inspired by Islamic values. Avoid unnecessary decoration, competitive rankings, public shaming, or judgmental language.

2. MAIN QURANIC THEME

Display this Quranic verse as the central theme of the application:

ٱقْرَأْ كِتَـٰبَكَ كَفَىٰ بِنَفْسِكَ ٱلْيَوْمَ عَلَيْكَ حَسِيبًا

Reference: Surah Al-Isra, 17:14.

Bangla meaning:

“(তাকে বলা হবে) তুমি তোমার কিতাব (আমলনামা) পাঠ করো; আজ তোমার হিসাব নেওয়ার জন্য তুমি নিজেই যথেষ্ট।”

Keep the Arabic text unchanged in every language version. Display the translation according to the user's selected language.

3. USER ACCOUNT AND AUTHENTICATION

Every user must have an independent personal account.

Provide:

- Sign up and login.
- Secure authentication.
- User profile with name and profile photo.
- Password and account security settings.
- Language preference.
- Time zone and country settings.
- Account logout and account management.

A user account must remain independent of group membership.

If a member leaves a group, their personal account and historical personal records must not be deleted.

4. GROUP-BASED MANAGEMENT SYSTEM

The application must use a WhatsApp-style group management structure.

There must not be one global administrator controlling every group.

Group creation

- Any registered user can create multiple groups without a fixed group-count limit.
- The person creating a group automatically becomes its Primary Admin.
- A user can create several groups and join several other groups simultaneously.
- Every group must have its own independent members, administrators, settings, reports, and privacy controls.

Group information

Allow group creators to set:

- Group name.
- Group description.
- Group logo or image.
- Group privacy settings.
- Invitation link and invitation code.
- Join request and approval settings.
- Daily report submission deadline.

Joining a group

Support both methods:

1. Invitation Link / Code: An admin can generate and share an invitation link or code. Users can use it to join the group.
2. Join Request: A user can request to join a group. An authorized admin can approve or reject the request.

Allow admins to:

- Enable direct joining or require approval.
- Revoke an invitation link.
- Generate a new invitation link or code.
- Manage membership requests.

Multiple administrators

Each group must support multiple administrators.

Roles:

A. Primary Admin

- Highest administrative responsibility in the group.
- Full visibility of every member's submitted information.
- Can appoint and manage Co-Admins.
- Can remove members and administrators.
- Can manage group settings.
- Can transfer Primary Admin responsibility.
- Can configure the group's daily submission deadline.

B. Co-Admin

- Has full visibility of all members' submitted information.
- Can manage the group according to permissions assigned by the Primary Admin.
- May approve joining requests, manage members, and perform other authorized administrative tasks.
- Cannot appoint a new Primary Admin or independently transfer Primary Admin ownership.

C. Former Primary Admin / Advisor
When Primary Admin responsibility is transferred:

- The new Primary Admin receives the Primary Admin role.
- The previous Primary Admin becomes a Former Primary Admin / Advisor.
- The previous Primary Admin must not automatically become an ordinary member.
- The Advisor retains full visibility of all group members' information.
- The Advisor retains a special administrative status and may continue participating in group administration.
- The new Primary Admin and Former Primary Admin / Advisor both retain full access to member information.
- Preserve the complete history of administrative transfers.

Require the new Primary Admin to accept the transfer before it becomes effective.

Group independence

- One group's admin must not automatically have access to another group's information.
- A person can be an admin in one group and an ordinary member in another.
- Each group's membership and data permissions must remain independent.
- Leaving a group must not delete the user's account or personal records.

5. PRIVACY AND DATA ACCESS RULES

This is a critical requirement.

All group administrators must have full visibility of every member's submitted information within their own group.

This includes:

- Quran study.
- Quran memorization.
- Hadith study.
- Hadith memorization.
- Salah records.
- Sadaqah status and amounts.
- Friendship and relationship records.
- Islamic literature.
- Language learning.
- Dawah activities.
- Personal development.
- All other daily report fields.

No member can hide submitted information from the administrators of their own group.

Ordinary member privacy

- Members can always view their own complete personal records.
- Ordinary members cannot view another member's private daily records.
- Members may choose which information to share with other ordinary group members.
- Group-wide aggregate statistics may be shared without exposing individual private records.
- Never expose private records through public group pages, search results, or member lists.

Security enforcement

Implement privacy and access permissions at the backend database and security-rule level.

Do not rely only on hiding fields or buttons in the user interface.

A user must never be able to access unauthorized information by changing a URL, document ID, or application request.

6. ADMINISTRATORS MUST ALSO TRACK THEIR OWN RECORDS

Every administrator must use the same daily tracking system as ordinary members.

- Primary Admin must submit their own daily report.
- Every Co-Admin must submit their own daily report.
- A Former Primary Admin / Advisor who remains active in the group must also be able to submit personal reports.
- Administrators must not receive automatic exemptions from daily reporting.
- The same daily tracking rules apply to everyone.

The principle of the application is:

Nobody is here only to check other people's accounts. Everyone must maintain their own account.

7. DAILY REPORT SYSTEM

Create one unified Daily Update page containing all tracking categories.

The user should be able to complete the entire daily report in one place.

Provide:

- Save Draft.
- Review Report.
- Submit All.

Users must be able to save a draft and update it throughout the day.

Before final submission, show a review screen containing the entered information and any incomplete fields.

Allow the user to submit all entered daily information together with one action.

After submission:

- Show a submission confirmation.
- Mark the report as submitted.
- Lock the report against further member editing.
- Do not provide a special correction or revision system after submission.
- The next day's report must remain separate.

Do not automatically treat missing entries as zero.

Distinguish clearly between:

- Not started.
- Draft.
- Submitted.

Allow optional pre-filling from the previous day, but require the user to verify the new day's information before submission.

Automatically calculate daily, monthly, and annual totals.

8. DAILY TRACKING CATEGORIES

A. Quran Study

Only two input options:

1. Meaning-based Quran study: Number of verses studied with meaning.
2. New Quran memorization: Number of new verses memorized.

Do not add additional Quran study input categories.

B. Hadith Study

Only two input options:

1. Meaning-based Hadith study: Number of Hadith studied with meaning.
2. New Hadith memorization: Number of new Hadith memorized.

Do not add additional Hadith study input categories.

Automatically calculate:

- Total study days.
- Total verses studied with meaning.
- Total new verses memorized.
- Total Hadith studied with meaning.
- Total new Hadith memorized.

C. Islamic Literature

Input:

- Number of pages read daily.

Automatically calculate:

- Total reading days.
- Monthly pages.
- Annual pages.

D. Salah Tracking

Track all five daily prayers:

- Fajr.
- Dhuhr.
- Asr.
- Maghrib.
- Isha.

Allow the user to record:

- Whether each prayer was performed.
- Number of prayers performed in congregation.
- Number of missed prayers (Qaza).

Provide daily, monthly, and annual summaries.

E. Dawah and Communication

Allow daily counts in these categories:

- Known Bangladeshi brothers.
- New or previously unknown Bangladeshi brothers.
- Coworkers.
- Family members.
- Other people.

Automatically calculate daily and monthly totals.

F. Friendship and Relationships

Track:

- Current total number of friends.
- Number of new friends made today.
- Monthly new friend count.

Administrators can view all friendship and relationship information of members in their group.

G. Sadaqah

Track:

- Did the member give Sadaqah today? Yes / No.
- Amount given, if applicable.
- Currency according to the user's settings.

Automatically calculate:

- Monthly Sadaqah amount.
- Annual Sadaqah amount.
- Number of days Sadaqah was given.

Administrators can view all Sadaqah records, including status and amounts.

H. Language Learning

Track daily learning for:

- English.
- Arabic.

Allow the user to record time spent and daily progress.

Automatically calculate monthly and annual learning time.

I. World News

Track:

- Whether the user read world news.
- Time spent reading.

J. Amal-e-Salihah

Provide a short text field for recording other good deeds and beneficial activities.

K. Personal Responsibilities

Track:

- Daily work or duty hours.
- Personal cleanliness.
- Surrounding cleanliness.

Provide a simple self-assessment system.

L. Rest and Sleep

Track:

- Daily sleep hours.
- Additional rest hours.

Automatically calculate monthly and annual totals.

9. MONTHLY PERSONAL PLAN

Every member must have an individual monthly plan.

Provide editable default targets:

Activity| Suggested monthly target
Quran study with meaning| 90 verses
Hadith study with meaning| 60 Hadith
Islamic literature| 300 pages
New Quran memorization| 4 verses
New Hadith memorization| 8 Hadith
Congregational Salah| Personal regularity target

These are suggested defaults, not compulsory targets.

Each member can change their targets.

Automatically show:

- Monthly target.
- Actual achievement.
- Remaining target.
- Completion percentage.
- Number of active study days.

10. ANNUAL PERSONAL PLAN

Allow every member to create an individual annual plan for:

- Quran study with meaning.
- Hadith study with meaning.
- Islamic literature.
- Quran memorization.
- Hadith memorization.
- Congregational Salah.
- English learning.
- Arabic learning.
- Other personal development goals.

Daily reports must automatically update monthly and annual progress.

Provide plan-versus-actual reports.

Never shame members for incomplete targets.

11. DASHBOARD AND REPORTING SYSTEM

Personal Dashboard

Show:

- Today's daily report status.
- Daily activity summary.
- Quran and Hadith progress.
- Salah summary.
- Sadaqah summary.
- Monthly plan progress.
- Annual plan progress.
- Personal development overview.

Group Admin Dashboard

Create a comprehensive Submission Dashboard.

Display:

- Total group members.
- Reports submitted today.
- Reports not submitted.
- Draft reports.
- Submission percentage.
- Monthly submission summary.
- Annual submission summary.

Allow administrators to:

- Search members by name.
- Filter by submission status.
- View individual member records.
- View daily, monthly, and annual reports.
- View group-level aggregate statistics.

Ordinary members must not have access to other members' private reports.

Large Group Performance

The application must efficiently support groups containing thousands of members.

Implement:

- Server-side pagination.
- Search and filtering.
- Indexed database queries.
- Server-side aggregation.
- Efficient data loading.
- Avoid loading all member records simultaneously.
- Role-based access control.

Do not use client-side loading of thousands of records as the primary management approach.

Do not create public competitive rankings or shaming leaderboards.

12. DAILY REPORT DEADLINE

The Primary Admin must be able to set the daily report submission deadline for their group.

Examples:

- 10:00 PM.
- 11:00 PM.
- 11:59 PM.

These are examples only. The Primary Admin chooses the actual deadline.

Rules:

- Every member and administrator follows the same group deadline.
- The Primary Admin can change the deadline.
- Use the group's configured time zone.
- Reports not submitted by the deadline must remain marked as not submitted or incomplete.
- Never automatically copy the previous day's report into a new day.

13. MULTILINGUAL SUPPORT

The app must support international Muslim users.

Initial languages:

1. Bengali.
2. English.
3. Arabic.
4. Urdu.
5. Indonesian.
6. Malay.
7. Turkish.
8. French.
9. German.
10. Spanish.

Architecture must allow additional languages in the future.

Requirements:

- Each member independently selects their preferred language.
- Different-language users can belong to the same group.
- Translate menus, buttons, forms, notifications, reports, and dashboards.
- Support right-to-left layouts for Arabic and Urdu.
- Support country-specific date formats.
- Support local time zones.
- Support different currencies.
- Keep Quranic Arabic unchanged.
- Keep original Hadith Arabic unchanged.
- Display appropriate reviewed translations in the selected language.

Do not assume automatic machine translation is always accurate for Quranic or Hadith content.

14. SETTINGS

Create a complete Settings page containing:

1. Language selection.
2. Profile settings.
3. Profile photo.
4. Account and security.
5. Password management.
6. Privacy settings.
7. Notification settings.
8. Daily report settings.
9. Time zone and date format.
10. Currency selection.
11. Light and Dark themes.
12. Help and Support.
13. About the App.
14. App version.
15. Logout.

Provide separate group settings for:

- Group details.
- Membership.
- Admin roles.
- Invitations.
- Join approvals.
- Privacy.
- Daily submission deadline.
- Group management.

15. NOTIFICATIONS

Provide useful notifications for:

- Daily report reminders.
- Upcoming submission deadlines.
- Successful report submission.
- Group invitation.
- Join request updates.
- Admin announcements.
- Important group changes.

Allow users to manage notification preferences.

16. TECHNICAL ARCHITECTURE

Build the application using:

- FlutterFlow for the application interface.
- Flutter-compatible architecture.
- Firebase Authentication for user authentication.
- Cloud Firestore for data storage.
- Firebase Security Rules for privacy and permissions.
- Cloud Functions or suitable server-side logic for secure aggregation and administrative operations.
- Firebase Cloud Messaging for notifications.

Use a scalable data structure.

Suggested main collections:

- users
- groups
- group_members
- group_invitations
- join_requests
- daily_reports
- monthly_plans
- annual_plans
- group_settings
- notifications
- admin_audit_logs

Use appropriate indexes and secure database access.

Ensure each daily report is associated with the correct user, group, and date.

A user's personal account and records must remain independent from group membership.

For users who belong to multiple groups, make sure each group's membership permissions are applied separately.

17. ADMIN AUDIT AND ACCOUNTABILITY

Maintain a secure history of important administrative actions, including:

- Admin appointments.
- Admin removals.
- Primary Admin transfers.
- Member additions and removals.
- Join request approvals and rejections.
- Group setting changes.
- Invitation link changes.
- Submission deadline changes.

Preserve historical records.

18. IMPORTANT DEVELOPMENT REQUIREMENTS

Do not build only a static visual prototype.

Build a functional application with:

- Working navigation.
- Authentication.
- Database integration.
- Daily report forms.
- Draft saving.
- Final submission.
- Monthly and annual calculations.
- Group creation and joining.
- Multiple administrator roles.
- Secure member privacy.
- Admin dashboards.
- Multilingual interface.

If a feature requires Firebase configuration, backend functions, security rules, or additional setup, identify that requirement clearly.

Do not simulate a working backend with sample data and present it as real functionality.

Use sample data only for preview and testing.

Prioritize a simple, reliable, mobile-friendly interface.

The application must be usable on Android phones and must remain responsive for large groups.

19. DEVELOPMENT PRIORITY

Build in stages:

Phase 1: Authentication, profile, language selection, and personal dashboard.

Phase 2: Daily report form, draft saving, final submission, and tracking calculations.

Phase 3: Monthly and annual plans, reports, and personal progress.

Phase 4: Group creation, invitations, joining requests, and membership management.

Phase 5: Primary Admin, Co-Admin, Former Primary Admin / Advisor roles, privacy, and security rules.

Phase 6: Group Submission Dashboard, search, filtering, pagination, and large-group performance.

Phase 7: Multilingual support, notifications, settings, testing, and Android release.

Before moving to the next phase, verify that the previous phase works correctly.

FINAL PRODUCT PRINCIPLE

The central purpose of Amar Hisab is personal accountability, sincerity, consistency, Islamic learning, and self-improvement.

Every person, whether an ordinary member, Co-Admin, Primary Admin, or Former Primary Admin / Advisor, must maintain their own daily records.

Administrators are responsible for managing their groups, not for replacing the personal accountability of their members.

The app should encourage users to examine their own actions, improve gradually, and remain sincere in their relationship with Allah.

Build Amar Hisab as a secure, scalable, multilingual, group-based Islamic self-accountability application.
