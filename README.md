# OctoPetShop
Octopus Pet Shop Example Web app written in .NET Core.  This solution consists of:
 - Octopus Pet Shop Web front end
 - Product Service
 - Shopping Cart Service
 - Database project using Dbup

This is a customised fork from the [Octopus Deploy Sample](https://github.com/OctopusSamples/OctoPetShop). 

[![OctoPetShopAppBuild](https://github.com/weeyin83/SarahOctoPet/actions/workflows/octopetshopbuild.yml/badge.svg?event=push)](https://github.com/weeyin83/SarahOctoPet/actions/workflows/octopetshopbuild.yml)
[![OctoPetShopBicepBuild](https://github.com/weeyin83/SarahOctoPet/actions/workflows/biceppush.yml/badge.svg?branch=main)](https://github.com/weeyin83/SarahOctoPet/actions/workflows/biceppush.yml)

# GitHub Actions Workflow
 Within the .github/workflows folder you will find a GitHub Actions Workflow file entitled 'octopetshopbuild.yml'.  This workflow builds the .NET packages, and then pushes them to an Octopus instance ready for deployment to the relevant infrastructure. 

The 'biceppush.yml' GitHub Actions Workflow file takes the Azure Bicep module and template files within the Bicep folder.  Packs them into a ZIP file and then pushes them to the Octopus Deploy server ready for deployment. 

 # Issue Templates
 Within the .github/ISSUE_TEMPLATES folder I have created some GitHub issue templates to, hopefully make it easier for you to reach out with questions or concerns relating to this repo. If you have a question or concern click [here](https://github.com/weeyin83/SarahOctoPet/issues/new/choose) and raise an issue. 
