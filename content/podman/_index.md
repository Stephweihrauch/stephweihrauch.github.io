+++
title = "Podman Presentation"
outputs = ["Reveal"]
[reveal_hugo]
custom_css = "/css/custom.css"
custom_js = "/js/text-animation.js"
transition = "zoom"
+++

<section data-noprocess class="present">
  <h2>About me!</h2>
  
  <img alt="avatar" class="avatar" src="/images/me.jpg"/>
  
  <img alt="Github" class="brand-icon" src="/images/icons/github-logo.svg"/>stephanweihrauch
  <br/>
  <img alt="Twitter" class="brand-icon" src="/images/icons/twitter-logo.svg"/>@stephweihrauch
  
  <div class="text-animation-wrapper">
  <p class="text-animation"></p>
  </div>

</section>

---

### Podman

## <font color=Tan> Contents </font>

<font color=RoyalBlue>

1. **_What is podman​_**

2. **_Podman vs Docker​_**

3. **_What‘s a Container Runtime​_**

4. **_Podman advantages and disadvantages​_**

5. **_How to install podman​_**

6. **_List of commands in podman_**

</font>

---

## <font color=Tan> podman </font>

<font color=RoyalBlue>

- Podman is a container engine that‘s compatible with OCI(Open Container Initiative) containers specifications​

- Podman is part of RedHat Linux, but can also be installed in other disturbutions​

- Podman can be used as a drop-in replacement for the better-known Docker runtime. Most docker comands can be directly translated to podman comands​

- [_How to Install and Use Podman on Ubuntu_](https://www.vultr.com/docs/how-to-install-and-use-podman-on-ubuntu-20-04/)

</font>

---

## <font color=Tan> Podman vs Docker </font>

![](/images/podman/dockervspodman.PNG)

---

## <font color=Tan> What is a container runtime?​ </font>

<font color=RoyalBlue>

- Container runtime in general is the part of the system that does everything necessary to run a container.​

- We differ between low-level and high-level runtimes​

- Low-level runtimes like runc mostly focuses only on running a container​

- High-level runtimes like containerd provides APIs and image management etc.​

- Podman relies on OCI (Open Container Initiative) compliant runtimes like (runc, crun, etc.)

</font>

---

## <font color=Tan> Advantages </font>

<font color=RoyalBlue>

- Ability to run Podman as non-root user.​

- Podman can run multiple image formats including OCI and Docker images.

</font>

---

## <font color=Tan> Disadvantages </font>

<font color=RoyalBlue>

- Non-root users can face multiple difficulties in container networking and firewall policy settings.
- Can only run containers in Linux (Podman only offers remote clients for MacOS and Windows).

</font>

---
