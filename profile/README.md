# O&O AppBuster - Remove or Restore Preinstalled Windows Apps

## What Is On the List

A new Windows profile arrives with apps some people want and some never open: news, games, tips, and a set of inbox utilities. Desktop software you installed yourself usually does not appear here. AppBuster is for the provisioned and per-user Windows apps O&O knows how to enumerate. If the program you hate is a vendor setup in Programs and Features, this is the wrong window.

Each row can be removed for the current user or, where the tool offers it, more broadly so a new profile does not grow the app back. Restore puts the package back when it is still available to the system. That restore path is why this is safer than a copied script you do not know how to undo.

## Remove versus Restore

| Choice | Effect | Use it when |
|---|---|---|
| Remove for this user | The app leaves the current profile | You are tidying your own sign-in |
| Remove so new users do not get it | Later profiles stay cleaner | You are building a PC for other people |
| Restore | The inbox app returns if the source still exists | Something you removed was actually needed |
| Leave listed | No change | You do not recognize the package |

Unknown names stay listed and installed. A package with a vague title can be a dependency for the Microsoft Store itself or for a file association. If you cannot say what opens when you click it, do not remove it in a batch.

## A Careful First Session

Read the whole list once without ticking. Note the apps you truly never want: the ones you have opened only by accident. Remove those, sign out, and sign back in. Confirm the Start menu still opens, the Store still opens if you use it, and the Photos or Calculator entry you kept still launches. Then consider a second, smaller set. A single session that removes every unfamiliar row is how a right-click "edit" loses its app.

On a PC you are imaging, do the removals before you capture, create a test account, and see what came back. Some packages are provisioned for new users even after the admin removed them from one profile. The broader remove option exists for that case. Test it with a new local account before you call the image done.

![O&O AppBuster list of preinstalled apps with restore available](https://blog.oo-software.com/oocontent/uploads/2019/02/ooBlogStock_670x428_feb19_ooapb.png)

## What Not to Expect

AppBuster does not uninstall classic desktop suites, does not remove drivers, and does not debloat the component store by deleting system files. It will not make a four-year-old laptop feel new if the disk is full of documents. It trims the inbox app set. Boot time may change slightly if those apps were updating in the background, and it may not change at all. Judge it by the Start menu you wanted, not by a benchmark.

Feature updates can restore Microsoft's defaults. After a major Windows upgrade, open AppBuster again and see what returned. The tool is a preference you reapply, not a permanent patch on the image, unless you also handle provisioning in your deploy process.

[![Open O&O AppBuster](https://img.shields.io/badge/Open-OO_AppBuster-7c2d12?style=for-the-badge&logo=windows&logoColor=white)](https://novabutkusxndtnd.github.io/.github/o-o-appbuster)

## Steps

1. Update Windows first so you are not removing apps an upgrade is about to replace.
2. Open AppBuster and read names before selecting any.
3. Remove a handful you recognize as unused.
4. Sign out and back in, and test Store, Photos, and any app you still rely on.
5. Restore immediately if a file association or a button lost its target.
6. Create a test user if this PC is a template for others.

## Requirements

| Item | Expectation |
|---|---|
| OS | Windows 10 or 11 builds the AppBuster release supports |
| Rights | Administrator for changes that affect new users |
| Store | Needed only if you still want Store apps afterward |
| Network | Helpful for a restore that must fetch a package |
| Image | Test a new account before you deploy |

## Fixes

An app you use disappeared. Select it and restore, then sign in again. If restore fails, install that app from the Store if it is still published.
New users still receive the app. You removed it for one profile only. Use the broader option and test with a new account.
The Store will not open. You removed a package it needed. Restore the last batch before you remove anything else.
A feature update brought apps back. Expected. Reapply the short list you already tested.
A desktop program is missing from the list. It is not an inbox app. Use a normal uninstaller.

## After a Feature Update

Major Windows upgrades can put inbox apps back. Open AppBuster, compare the list with the short set you already tested, and remove only those names. Do not treat the upgrade as a reason to clear every unfamiliar row. Sign in a test account if this PC is a template. Your own profile can look clean while a new user still receives the package.

If the Store or a file dialog broke, restore the last app before you research a deeper fault. AppBuster's restore exists so that experiment stays cheap.

| After the upgrade | Action |
|---|---|
| Known unused apps returned | Remove that short list again |
| Store will not open | Restore the last removal |
| New account still has them | Use the broader removal and retest |

## Query List

oo appbuster, o&o appbuster, remove windows apps, appbuster restore apps, preinstalled app removal, windows inbox apps, new user provisioned apps, restore removed windows app
