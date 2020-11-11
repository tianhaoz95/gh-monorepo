# GH Monorepo

## Objective

The project aims to propose a all-in-one solution to manage GitHub monorepo projects.

## Background

Recently, GitHub launched many automation tools like GitHub Actions, Automated dependency updates and CodeSpace, making GitHub a center for development instead of just a source code hosting service.

However, some tools GitHub provided are based on polyrepo assumptions. For example, although it's possible to define GitHub Actions workflows for monorepo with the attribute `working-directory`, it's hard to define the relationship between projects (e.g. dependencies).

## Overview

The project aim to define a configuration that is necessary for all monorepo projects and can be extended with tools.

## Detailed Design

### Information required

The following information is required for each sub-project:

* Project ID
* Dependencies
* Workflows
