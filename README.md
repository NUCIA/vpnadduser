# VPN Add User Script

A quick script for adding users to a specific gateway

## Introduction

This is a script used to add users to an OpenVPN server. This was designed specifically for a deployment. But this can be used as a good starting point for creating your own script.

## Caveats

It should be quickly apparent that lines used to set a password are commented
out. This was old code used before the server was configured for Kerberos
password authentication. But it would not be difficult to add the functionality
back into the script. You just need to uncomment the code and of course provide $pword some password. It would then be up to you to decide how you want to do
it.

This also includes some internal firewalling used as a stop-gap solution for restricting access to some internal parts of the VPN. But what that is exactly is not included here. A future version of this script may separate that code.

## Pull Requests

I welcome pull requests if you see any way to improve the script. In fact, I
know of several pieces of the script that could be improved.
