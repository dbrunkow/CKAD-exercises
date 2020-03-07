# Practice Questions and Notes

alias k=kubectl

## Core Concepts

### List all namespaces

<details><summary>show</summary>
<p>
```bash
  k get ns
  k get namespace
```
</p>
</details>


### Create a namespace named mynamespace and run a pod in it

<details><summary>show</summary>
<p>
```bash
  k create namespace mynamespace
  k run mypod --image=nginx --namespace=mynamespace
```
</p>
</details>


Delete everything in the namespace

<details><summary>show</summary>
<p>
```bash
  -bash-4.2$ k delete pods,deploy,rs --all --namespace=mynamespace
  pod "mypod-8cdb8c645-j5gm7" deleted
  deployment.extensions "mypod" deleted
  replicaset.extensions "mypod-8cdb8c645" deleted
```
</p>
</details>

<details><summary>show</summary>
<p>
```bash


```
</p>
</details>
<details><summary>show</summary>
<p>
```bash


```
</p>
</details>
<details><summary>show</summary>
<p>
```bash


```
</p>
</details>
<details><summary>show</summary>
<p>
```bash


```
</p>
</details>
<details><summary>show</summary>
<p>
```bash


```
</p>
</details>
<details><summary>show</summary>
<p>
```bash


```
</p>
</details>
