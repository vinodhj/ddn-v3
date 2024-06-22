# Hasura DDN v3 Setup Guide

This guide provides instructions to set up Hasura with Data Delivery Network (DDN) v3.

## Prerequisites

- Docker and Docker Compose installed
- Hasura CLI installed
- A Hasura Cloud or Hasura Enterprise instance (for DDN)
- Your DDN PAT (Personal Access Token)

## Step 1: Authenticate DDN

First, authenticate with the DDN and obtain your PAT (Personal Access Token).

```sh
HASURA_DDN_PAT=$(ddn auth print-pat)
