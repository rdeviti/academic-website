---
# Display name
title: Roberta De Viti

# Username (this should match the folder name)
authors:
- admin

# Is this the primary user of the site?
superuser: true

# Role/position
role: PhD Student

# Organizations/Affiliations
organizations:
- name: Max Planck Institute for Software Systems (MPI-SWS)
  url: "https://www.mpi-sws.org"

# Short bio (displayed in user profile at end of posts)
bio: My research interests include (...)

interests:
- Security and Privacy
- Applied Cryptography
- Multi-Party Computation
- Distributed Systems
- Mobile Systems

education:
  courses:
  - course: MSc in Computer Engineering
    institution: Universita' degli Studi di Napoli "Federico II"
  - course: BSc in Computer Engineering
    institution: Universita' degli Studi di Napoli "Federico II"

# Social/Academic Networking
# For available icons, see: https://sourcethemes.com/academic/docs/page-builder/#icons
#   For an email link, use "fas" icon pack, "envelope" icon, and a link in the
#   form "mailto:your-email@example.com" or "#contact" for contact widget.
social:
- icon: envelope
  icon_pack: fas
  link: 'mailto:rdeviti-at-mpi-sws.org'  # For a direct email link, use "mailto:test@example.org".
- icon: twitter
  icon_pack: fab
  link: "https://twitter.com/rdeviti"
#- icon: skype
#  icon_pack: fab
#  link: roberta.de.viti
#- icon: github
#  icon_pack: fab
#  link: https://github.com/gcushen
# Link to a PDF of your resume/CV from the About widget.
# To enable, copy your resume/CV to `static/files/cv.pdf` and uncomment the lines below.
# - icon: cv
#   icon_pack: ai
#   link: files/cv.pdf

# Enter email to display Gravatar (if Gravatar enabled in Config)
email: ""

# Organizational groups that you belong to (for People widget)
#   Set this to `[]` or comment out if you are not using People widget.
# user_groups:
# - Researchers
# - Visitors
---

<div style="text-align: justify;">

I'm a PhD student at the <b>Max Planck Institute for Software Systems</b> (<a href="https://www.mpi-sws.org">MPI-SWS</a>).

I work in the Distributed Systems and Security & Privacy groups, where I am co-advised by <a href="https://people.mpi-sws.org/~druschel/">Peter Druschel</a> and <a href="https://people.mpi-sws.org/~dg/">Deepak Garg</a>. I am broadly interested in designing, building, and analyzing <b>secure</b> and <b>privacy-preserving distributed systems</b>. In particular, I am studying cryptographic techniques that run computation on sensitive private data; my research focus is to apply these techniques to real-world large-scale distributed systems, and to explore the consequent trade-offs between security, efficiency, and functionality.

Recently, I have been working on a secure selective analytics (SSA) platform. This platform is <i>secure</i> under a strong threat model that leverages <b>Multi-Party Computation (MPC)</b> to place trust on a set of independent <b>Trusted Execution Environments</b>. This platform is <i>selective</i> as it allows data sources to a priori restrict the use of their sensitive data to a pre-defined set of queries, run by specific analysts, and for a limited period. Currently, I am working on extending its use cases to support <i>practical</i> MPC-based ML training over very large sensitive datasets under the same threat model.

Previously, I explored different areas such as network side channels and secure mobile systems: I worked on <a href="https://www.usenix.org/system/files/sec22-mehta.pdf">Pacer</a>, a project aimed to ensure data privacy in Cloud services against <b>network side-channel</b> leaks, and <a href="https://dl.acm.org/doi/pdf/10.1145/3307334.3326101">enClosure</a>, a project on secure and private communication enabled by chains of <b>mobile encounters</b>.

Besides research, I'm quite enthusiastic about a bunch of things: traveling, cinema, books, comics, guitar, food, complaining, and complaining about food -- especially if claimed to be Italian.
</div>
