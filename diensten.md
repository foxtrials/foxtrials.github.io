---
feature_row:
  - image_path: '/assets/img/storyset/secure-data-animate.svg'
    # image_caption: "[Illustratie door Freepik Storyset](https://storyset.com)"
    alt: 'Beveiliging'
    title: 'Beveiliging'
    excerpt: '<p><em>Netwerk en Infrastructuur</em></p><ul>
      <li><a href="/diensten#penetration-testing">Penetration Testing</a></li>
      <li><a href="/diensten#vulnerability-scanning">Vulnerability Scanning</a></li>
      <li><a href="/diensten#public-footprint-analysis">Public Footprint Analysis</a></li>
      <li><a href="/diensten#ransomware-simulations">Ransomware Simulations</a></li>
      <li><a href="/diensten#security-maturity-assessments">Security Maturity Assessments</a></li>
      </ul>'
    url: "/diensten#beveiliging"
    btn_label: "Meer Informatie"
    btn_class: "btn--danger"
  - image_path: '/assets/img/storyset/onboarding-animate.svg'
    # image_caption: "[Illustratie door Freepik Storyset](https://storyset.com)"
    alt: 'Bewustzijn'
    title: 'Bewustzijn'
    excerpt: '<p><em>De Menselijke Factor</em></p><ul>
      <li><a href="/diensten#phishing-campaigns">Phishing Campaigns</a></li>
      <li><a href="/diensten#awareness-trainings">Awareness Trainings</a></li>
      <li><a href="/diensten#social-engineering">Social Engineering</a></li>
      <li><a href="/diensten#hacking-demos">Hacking Demos</a></li>
      <li><a href="/diensten#policy-analysis">Policy Analysis</a></li>
      </ul>'
    url: "/diensten#bewustzijn"
    btn_label: "Meer Informatie"
    btn_class: "btn--success"
  - image_path: '/assets/img/storyset/gdpr-animate.svg'
    # image_caption: "[Illustratie door Freepik Storyset](https://storyset.com)"
    alt: 'Bescherming'
    title: 'Bescherming'
    excerpt: '<p><em>Detectie en Respons</em></p><ul>
      <li><a href="/diensten#disaster-recovery-plans">Disaster Recovery Plans</a></li>
      <li><a href="/diensten#network-monitoring">Network Monitoring</a></li>
      <li><a href="/diensten#incident-response">Incident Response</a></li>
      <li><a href="/diensten#digital-forensics">Digital Forensics</a></li>
      <li><a href="/diensten#data-recovery">Data Recovery</a></li>
      </ul>'
    url: "/diensten#bescherming"
    btn_label: "Meer Informatie"
    btn_class: "btn--info"
---

<h1>Onze Diensten</h1>

{% include feature_row %}

<h2 id="beveiliging">Beveiliging<br/><small><em>Netwerk en Infrastructuur</em></small></h2>

{% include service-description.html
    align='left'
    family='infrastructure'
    service='penetration-testing'
    image='hacker'
%}

{% include service-description.html
    align='right'
    family='infrastructure'
    service='vulnerability-scanning'
    image='server'
%}

{% include service-description.html
    align='left'
    family='infrastructure'
    service='public-footprint-analysis'
    image='people-search'
%}

{% include service-description.html
    align='right'
    family='infrastructure'
    service='ransomware-simulations'
    image='no-data'
%}

{% include service-description.html
    align='left'
    family='infrastructure'
    service='security-maturity-assessments'
    image='endpoint'
%}

<h2 id="bewustzijn">Bewustzijn<br/><small><em>De Menselijke Factor</em></small></h2>

{% include service-description.html
    align='left'
    family='awareness'
    service='phishing-campaigns'
    image='phishing-account'
%}

{% include service-description.html
    align='right'
    family='awareness'
    service='awareness-trainings'
    image='attached-files'
%}

{% include service-description.html
    align='left'
    family='awareness'
    service='social-engineering'
    image='id-card'
%}

{% include service-description.html
    align='right'
    family='awareness'
    service='hacking-demos'
    image='programming'
%}

{% include service-description.html
    align='left'
    family='awareness'
    service='policy-analysis'
    image='qa-engineers'
%}

<h2 id="bescherming">Bescherming<br/><small><em>Detectie en Respons</em></small></h2>

{% include service-description.html
    align='left'
    family='governance'
    service='disaster-recovery-plans'
    image='gdpr'
%}

{% include service-description.html
    align='right'
    family='governance'
    service='network-monitoring'
    image='gdpr'
%}

{% include service-description.html
    align='left'
    family='governance'
    service='incident-response'
    image='gdpr'
%}

{% include service-description.html
    align='right'
    family='governance'
    service='digital-forensics'
    image='gdpr'
%}

{% include service-description.html
    align='left'
    family='governance'
    service='data-recovery'
    image='gdpr'
%}