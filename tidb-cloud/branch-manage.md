---
title: Manage TiDB Serverless Branches
summary: Learn How to manage TiDB Serverless branches.
---

# Manage TiDB Serverless Branches

This document describes how to manage the TiDB Serverless branches using the [TiDB Cloud console](https://tidbcloud.com). You can also manage it using the [TiDB Cloud CLI](/tidb-cloud/cli-reference.md).

## Create a branch

You can only create branches for TiDB Serverless clusters that are created after July 5, 2023.

> **Note:**
>
> For each organization, the number of branches has a [limit](/tidb-cloud/branch-overview.md#limitations-and-quotas).

To create a branch, perform the following steps:

1. In the [TiDB Cloud console](https://tidbcloud.com/), navigate to the [Clusters](https://tidbcloud.com/console/clusters) page of your project, and then click the name of your target TiDB Serverless cluster to go to its overview page.
2. Click **Branches** in the left navigation pane.
3. Click **Create Branch** in the upper-right corner.
4. Enter the branch name, and then click **Create**.

Depending on the data size in your cluster, the branch creation will be completed in a few minutes.

## View branches

To view branches for your cluster, perform the following steps:

1. In the [TiDB Cloud console](https://tidbcloud.com/), navigate to the [Clusters](https://tidbcloud.com/console/clusters) page of your project, and then click the name of your target TiDB Serverless cluster to go to its overview page.
2. Click **Branches** in the left navigation pane.

    The branch list of the cluster is displayed in the right pane.

## Delete a branch

To delete a branch, perform the following steps:

1. In the [TiDB Cloud console](https://tidbcloud.com/), navigate to the [Clusters](https://tidbcloud.com/console/clusters) page of your project, and then click the name of your target TiDB Serverless cluster to go to its overview page.
2. Click **Branches** in the left navigation pane.
3. In the row of your target branch to be deleted, click **...** in the **Action** column.
4. Click **Delete** in the drop-down list.
5. Confirm the deletion.

## Get branch connection information

To get the connection information of a branch, perform the following steps:

1. In the [TiDB Cloud console](https://tidbcloud.com/), navigate to the [Clusters](https://tidbcloud.com/console/clusters) page of your project, and then click the name of your target TiDB Serverless cluster to go to its overview page.
2. Click **Branches** in the left navigation pane.
3. In the row of your target branch to be deleted, click **...** in the **Action** column.
4. Click **Connect** in the drop-down list. The dialog for the connection information is displayed.
5. Click the **Create password** or **Reset password** to create or reset the root password.

> **Note:**
>
> Currently, branches do not support [private endpoints](/tidb-cloud/set-up-private-endpoint-connections-serverless.md).

## What's next

- [Integrate TiDB Serverless branching into your CI/CD pipeline](/tidb-cloud/branch-github-integration.md)