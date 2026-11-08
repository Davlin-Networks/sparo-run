# Sparo ISP Billing

**ISP billing software for internet providers in Africa.** PPPoE and hotspot
billing, M-Pesa auto-activation, MikroTik and RADIUS control, WhatsApp and
SMS alerts, a customer app in your name, and remote management of your
customers' fibre routers - in one hosted dashboard.

- Website: [sparo.run/products/isp-billing](https://sparo.run/products/isp-billing)
- Open the app: [app.sparo.run](https://app.sparo.run/login)
- Android app for operators: [app.sparo.run/android-app](https://app.sparo.run/android-app)
- My ISP, the customer app: [sparo.run/products/my-isp](https://sparo.run/products/my-isp)
- Sparo CPE, customer router management: [sparo.run/products/sparo-ops](https://sparo.run/products/sparo-ops)
- Documentation: [docs.sparo.run](https://docs.sparo.run)
- Blog: [sparo.run/blog](https://sparo.run/blog)

> This repository is the public home of Sparo ISP Billing on GitHub. The
> product is a hosted service; its source code is not published here. Use this
> page for an overview, pricing, the FAQ and links.

**14-day free trial. No card required.** → [Start free](https://app.sparo.run/login)

---

## What it does

Sparo ISP Billing is a **MikroTik hotspot and PPPoE billing system** built for
small and mid-sized ISPs and WISPs. A subscriber pays by M-Pesa, the service
switches on, the expiry is scheduled, the reminder goes out - without anyone
at the ISP touching a router.

### Billing and payments

- **M-Pesa auto-activation** - STK push or paybill. Payment is matched to the
  account and the service is enabled in seconds, at 11 pm on a Sunday too.
- **PPPoE billing** - monthly packages, scheduled expiry, reminders before the
  internet stops, and reconnection the moment a payment lands.
- **Hotspot billing** - pay-as-you-go packages by the hour, day, week or month,
  or by data allowance.
- **Night bundles** - cheap overnight hotspot packages that only work in the
  hours you choose, so they never eat into daytime sales.
- **Hotspot vouchers** - printable voucher batches for agents, redemption
  tracking and end-of-day reconciliation, so you know what each agent owes.
- **Payment gateways** - your own Safaricom Daraja paybill, KCB Buni, or TUMA,
  which settles hotspot payments straight into your bank account. Your money
  never sits in our account.
- **Subscriber wallet** (optional) - an overpayment, or a payment made before
  the plan is due, is kept as credit instead of lost, and can pay for the next
  renewal.
- **Self-service renewal portal** - PPPoE customers check their plan and pay
  from a branded page, and QR stickers on the router take them straight to it.
- **Outage compensation** - after an outage, give affected customers their
  lost time back in one step, instead of arguing it out account by account.
- **Revenue reports** - real-time collections, subscriber and voucher reports,
  so hotspot revenue is a number you trust rather than an estimate.

### Network control

- **MikroTik RouterOS** - hotspot and PPPoE, connected over the API or through
  RADIUS, with a setup wizard for new routers.
- **RADIUS with CoA** - authentication, accounting, and Change-of-Authorization
  so a package change or expiry takes effect immediately, no reboot.
- **Routers behind CGNAT** - a managed secure tunnel reaches routers without
  a public IP. No port forwarding, no static IP from the upstream.
- **Multi-router** - one dashboard for every site.
- **Router health and backups** - uptime and downtime alerts, configuration
  backups you can download, WebFig access from the dashboard.
- **Live sessions** - who is online, on which router, since when, using how much.
- **One login, one connection** - each PPPoE account can be online on only one
  of your routers at a time, so a shared username and password does not become
  a second, unbilled customer.
- **Fair usage policy** - "unlimited" packages can slow a heavy user down after
  a set amount of data, without disconnecting them, and restore full speed when
  the next window starts.
- **Free-internet app detection** - hotspot devices using DNS tunnelling apps
  (HTTP Injector, SlowDNS) to get online without paying are flagged on the
  router.

### Customer routers (TR-069 add-on)

Your customers' fibre routers report to Sparo over TR-069, so your team can
see what is happening in the home without a site visit.

- **Why is this customer offline?** - each router's fibre signal, PPPoE
  session, WiFi and connected devices beside the customer's account, with one
  plain answer: fibre fault, no power, not dialling, or an expired account.
- **Network health** - how many routers are online, which have gone quiet, and
  watch lists for weak fibre signal and lines that keep dropping.
- **Remote actions** - reboot a router, or change its WiFi name and password
  while the customer is on the phone. The new password is shown once and never
  stored.
- **Install by scanning** - technicians scan the serial on the router's label
  and it links to the right customer.
- **On the web and in Sparo CPE** - the Customer Routers page and map in the
  dashboard, and the Sparo CPE Android app for field staff, with fingerprint
  log-in.

### Running the business

- **WhatsApp and SMS notifications** - expiry reminders, payment receipts,
  downtime alerts, in the channels subscribers actually read.
- **Android app for operators** - the same account as the web dashboard, for
  activations and reports from the tower or the road.
- **My ISP, the customer app** - an Android app for your PPPoE customers in your
  name and colours: days left, M-Pesa renewal, usage, receipts, your
  promotions, and support requests that read like a chat, with a notification
  when you reply.
- **Branded portals** - your name and colours on the hotspot login page and
  the PPPoE renewal portal, optionally on your own domain, with an ads and
  cross-sell carousel.
- **Team roles** - give each member of staff only what their job needs, with
  your own custom roles.
- **Network map** - routers and subscriber installs on a map, with each site's
  details a tap away.
- **Tenant API** - a REST API with scoped tokens you create in the dashboard:
  read subscribers, plans, payments and routers, and start an M-Pesa checkout
  for a subscriber, so you can build your own customer app or connect your own
  systems.
- **Assisted setup** - we connect your routers, configure billing and payment
  workflows, and bring your existing subscribers into the system.

---

## Pricing

Pay as your ISP grows: a small share of hotspot revenue plus a simple fee per
active PPPoE account. **No licence fee. No per-router charges.** All prices in
USD.

| Plan | Hotspot commission | Per active PPPoE account | Minimum | Limits |
|------|-------------------:|-------------------------:|--------:|--------|
| **Starter** | 3% | $0.20 / month | none | 2 routers, 50 PPPoE accounts, the customer app |
| **Growth** (most popular) | 2.5% | $0.15 / month | none | 5 routers, 400 PPPoE accounts, promotions in the customer app, custom team roles |
| **Scale** | 2% | $0.12 / month | $20 / month | 20 routers, 1,500 PPPoE accounts, your own portal domain, priority support |

Every plan starts with a **14-day free trial** and no card. After the trial
there is a one-time **$8 activation fee**, which covers connecting your routers
and importing your subscribers.

**Dedicated** - for ISPs with 500 or more subscribers who want their own
servers: from $60 a month plus a banded fee per subscriber, 15% off yearly.
Work it out with the calculator on the product page.

**Customer router management (TR-069 add-on)** - from KES 500 a month for up
to 100 customer routers, then KES 5 per extra router. First month free.

Current figures are always on the
[pricing section of the product page](https://sparo.run/products/isp-billing#pricing).

---

## Who it is for

- **Hotspot operators** selling WiFi by the hour in estates, markets, campuses
  and matatu stages, often through agents and vouchers.
- **Small ISPs and WISPs** with a few MikroTiks and PPPoE subscribers on
  monthly plans, still activating by hand from an M-Pesa statement.
- **Growing ISPs** running several sites who need one revenue number they can
  trust, and alerts before the customer calls.

If you are still on a spreadsheet, start with
[Running an ISP on spreadsheets: when it stops working](https://sparo.run/blog/running-an-isp-with-spreadsheets).

---

## Frequently asked questions

**Which routers does it work with?**
MikroTik RouterOS for your network, connected over the API and through
RADIUS. Hotspot and PPPoE are both supported, and a secure tunnel reaches
routers behind CGNAT. For customers' homes, the router management add-on works
with fibre routers that support TR-069.

**How do M-Pesa payments work?**
Subscribers pay via STK push or paybill. The payment is matched to the account
and the service is activated automatically. You choose the gateway: your own
paybill through Safaricom Daraja, KCB Buni, or TUMA.

**Does it work outside Kenya?**
The platform is built for African ISPs. M-Pesa is the first payment rail;
MikroTik, RADIUS, vouchers, SMS and WhatsApp work anywhere. Ask us about
your market at sales@sparo.run.

**Is there a free trial?**
Yes. 14 days on any plan, no card. There is no activation fee during the trial.

**Is there a mobile app?**
Three Android apps: Sparo for operators (the same account as the web
dashboard), My ISP for your customers, and Sparo CPE for the staff who manage
customers' routers.

**Can my customers renew from their phone?**
Yes. My ISP shows their days left and renews by M-Pesa, in your name and
colours, and the same is available as a web portal for anyone without the app.

**Can I change a customer's WiFi password remotely?**
Yes, with the router management add-on: set a new WiFi name and password
from the dashboard or Sparo CPE while the customer is on the line. It reaches
the router within about five minutes, and the password is never stored.

**Is the source code open?**
No. Sparo ISP Billing is a hosted service. This repository exists so operators
searching GitHub for ISP billing, MikroTik hotspot billing or M-Pesa billing
can find it.

**Can a customer share their PPPoE login with a neighbour?**
Not at the same time. Each PPPoE account is limited to one session across all
your routers, enforced by RADIUS, so a second router using the same username
and password is refused. See
[PPPoE account sharing](https://sparo.run/blog/stop-pppoe-account-sharing).

**Can people get free internet on my hotspot with tunnel apps?**
Apps like HTTP Injector and SlowDNS hide traffic inside DNS lookups, which every
captive portal has to allow before payment. Sparo adds rules to each hotspot
router that flag devices doing it. See
[Free internet apps on your hotspot](https://sparo.run/blog/free-internet-apps-dns-tunnelling-hotspot).

**Where is the documentation?**
[docs.sparo.run](https://docs.sparo.run)

---

## Further reading

- [ISP billing systems in Kenya in 2026: what are your options](https://sparo.run/blog/isp-billing-systems-kenya-2026-options)
- [How much does ISP billing software cost?](https://sparo.run/blog/isp-billing-software-cost-kenya)
- [From M-Pesa payment to internet access: what happens in between](https://sparo.run/blog/from-mpesa-payment-to-internet-access)
- [PPPoE vs hotspot: which should your ISP use?](https://sparo.run/blog/pppoe-vs-hotspot-which-should-your-isp-use)
- [What is RADIUS and why does an ISP need it?](https://sparo.run/blog/what-is-freeradius-and-why-does-an-isp-need-it)
- [Hotspot voucher management: where does the money go?](https://sparo.run/blog/hotspot-voucher-management-where-does-the-money-go)
- [Manage MikroTik routers remotely, behind CGNAT](https://sparo.run/blog/manage-mikrotik-routers-remotely)
- [Free internet apps on your hotspot: what DNS tunnelling is and how to spot it](https://sparo.run/blog/free-internet-apps-dns-tunnelling-hotspot)
- [PPPoE account sharing: stopping one login from running two connections](https://sparo.run/blog/stop-pppoe-account-sharing)
- [Give your customers an app - without building one](https://sparo.run/blog/a-customer-app-for-your-subscribers)
- [Your portal, on your own domain](https://sparo.run/blog/your-portal-on-your-own-domain)
- [Night bundles: sell cheap overnight WiFi without giving away the day](https://sparo.run/blog/night-bundles-on-your-hotspot)
- [Why is this customer offline? Ask the router](https://sparo.run/blog/sparo-ops-manage-customer-fibre-routers)
- [TR-069 for home internet: better WiFi for your customers, fewer site visits for you](https://sparo.run/blog/tr-069-better-home-wifi-fewer-site-visits)
- [Outage compensation: give customers their time back without the argument](https://sparo.run/blog/outage-compensation)

---

## Contact

- Sales: sales@sparo.run
- Support: support@sparo.run
- Website: [sparo.run](https://sparo.run)

Sparo is a product of Davlin Networks.
