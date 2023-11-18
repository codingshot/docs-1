---
id: declaring-app
title: Self Declaring An App
---


# How do I get listed as an app?
So You Built A Full Decentralized BOS App but want to get listed as an application on websites like [near.org](https://near.org) and [near.social](https://near.social). 

![near social app](https://ipfs.near.social/ipfs/bafkreibuy4smphjxmtefbs3ropnvxyp57iwkfopn24zzt3hp4lqcbpmsgm)
![near org app](https://ipfs.near.social/ipfs/bafkreifi3edxyxf7a6bm5diyacb542rdw2k3k7qqix35qzrnolepibtlii)

# Component Metadata
Every component has component metadata. If you are using the [near.social](https://near.social) editor all you need to do is add the #app tag to the tag section of component metadata. 

## Navigating from NEAR.social
On NEAR.social go to the [sandbox](https://near.social/edit) then click on the metadata tab
![navigating metadata for near.social](https://ipfs.near.social/ipfs/bafkreicdlniyqqy3ux4sbqwyuzajvxqowncsil22ytyi5itvxjgaemfs3y)
## Navigating from Jutsu.ai
[Jutsu.ai](https:/jutsu.ai) is the go to [Web IDE](https:/jutsu.ai) for developing on BOS, click on the component name and click on the metadata tab on the dropdown
![navigating metadata on jutsu ai](https://ipfs.near.social/ipfs/bafkreicniwedsoyrfutpmlicotiyfvgmszxprlwbediyt3a7bqh2l56gdu)
Then go to the tag section and add an app tag
![navigating metadata on jutsu ai](https://ipfs.near.social/ipfs/bafkreiefhdkorhl47yn7f2g3lxzz3k3g4amfckhy42abcqawbhlufnrvo4)

## Using on BOS Workspace
Some of you maybe using a version of the [BOS Workspace](https://github.com/NEARBuilders/create) to build complex applications with hotloading of locally on the near.org gateway. In order to edit the component metadata check out the [.jsonc](https://github.com/NEARBuilders/create/blob/main/apps/create/widget/home.jsonc) file. Make sure it is in the same directory of the .jsx widget code with the same name. Here is an example of a repo using BOS workspace. Notice 
![example of jsonc on bos workspace](https://ipfs.near.social/ipfs/bafkreigi3ojke2ircttn4h7t77tcnoyzsvfevrs5cv5xqqwzyrjdduvtyu)

```jsx
/*__@noStringify__*/
{
  "metadata": {
    "name": "Create: Seamless Docs, Projects & More",
    "description": "A user friendly content management system for creating BOS websites and documentation. Without the need for coding.",
    "image": {
      "ipfs_cid": "bafkreifbek5xkj33smhzujzdvgpnwidljxwy6o745nbcui74wkaw3cbcga"
    },
    "tags": {
      "app": "",
      "docs": "",
      "blog": "",
      "website": "",
      "markdown": ""
    }
  }
}
```

:::note
To save the component, you'll need to sign in with a NEAR account and to make a deposit of a small amount of NEAR for the storage cost. This is because BOS uses the NEAR blockchain underneath.
:::
