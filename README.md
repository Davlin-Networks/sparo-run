# Sparo ISP Billing

**ISP billing software for internet providers in Africa.** PPPoE and hotspot
billing, M-Pesa auto-activation, MikroTik and FreeRADIUS control, WhatsApp and
SMS alerts, and an Android app - in one hosted dashboard.

- Website: [sparo.run/products/isp-billing](https://sparo.run/products/isp-billing)
- Open the app: [app.sparo.run](https://app.sparo.run/login)
- Android app: [app.sparo.run/android-app](https://app.sparo.run/android-app)
- Documentation: [docs.ispninja.co.ke](https://docs.ispninja.co.ke)
- Blog: [sparo.run/blog](https://sparo.run/blog)

> This repository is the public home of Sparo ISP Billing on GitHub. The
> product is a hosted service; its source code is not published here. Use this
> page for an overview, pricing, the FAQ and links.

**30-day free trial. No card required.** → [Start free](https://app.sparo.run/login)

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
- **Hotspot billing** - pay-as-you-go packages by the hour, day, week or month.
- **Hotspot vouchers** - printable voucher batches for agents, redemption
  tracking and end-of-day reconciliation, so you know what each agent owes.
- **Payment gateways** - your own Safaricom Daraja paybill, KCB Buni, or TUMA,
  which settles hotspot payments straight into your bank account. Your money
  never sits in our account.
- **Revenue reports** - real-time collections, subscriber and voucher reports,
  so hotspot revenue is a number you trust rather than an estimate.

### Network control

- **MikroTik RouterOS** - hotspot and PPPoE, connected over the API or through
  RADIUS, with a setup wizard for new routers.
- **FreeRADIUS with CoA** - authentication, accounting, and Change-of-Authorization
  so a package change or expiry takes effect immediately, no reboot.
- **Routers behind CGNAT** - a managed WireGuard tunnel reaches routers without
  a public IP. No port forwarding, no static IP from the upstream.
- **Multi-router** - one dashboard for every site.
- **Router health and backups** - uptime and downtime alerts, configuration
  backups you can download, WebFig access from the dashboard.
- **Live sessions** - who is online, on which router, since when, using how much.

### Running the business

- **WhatsApp and SMS notifications** - expiry reminders, payment receipts,
  downtime alerts, in the channels subscribers actually read.
- **Android app for operators** - the same account as the web dashboard, for
  activations and reports from the tower or the road.
- **Branded hotspot portal** - your name and colours on the login page, with an
  optional ads and cross-sell carousel.
- **Assisted setup** - we connect your routers, configure billing and payment
  workflows, and bring your existing subscribers into the system.

---

## Pricing

Pay as your ISP grows: a small share of hotspot revenue plus a simple fee per
active PPPoE account. **No licence fee. No per-router charges.** All prices in
USD.

| Plan | Hotspot commission | Per active PPPoE account | Minimum | Limits |
|------|-------------------:|-------------------------:|--------:|--------|
| **Starter** | 4% | $0.25 / month | none | 2 routers, 50 PPPoE accounts |
| **Growth** (most popular) | 2.5% | $0.20 / month | none | unlimited routers and subscribers |
| **Scale** | 1.5% | $0.15 / month | $20 / month | 20 routers, 1,500 PPPoE accounts, priority support, branded portal |

Every plan starts with a **30-day free trial** and no card. After the trial
there is a one-time **$8 activation fee**, which covers connecting your routers
and importing your subscribers. Current figures are always on the
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
MikroTik RouterOS, connected over the API or through FreeRADIUS. Hotspot and
PPPoE are both supported, and WireGuard tunnels reach routers behind CGNAT.

**How do M-Pesa payments work?**
Subscribers pay via STK push or paybill. The payment is matched to the account
and the service is activated automatically. You choose the gateway: your own
paybill through Safaricom Daraja, KCB Buni, or TUMA.

**Does it work outside Kenya?**
The platform is built for African ISPs. M-Pesa is the first payment rail;
MikroTik, FreeRADIUS, vouchers, SMS and WhatsApp work anywhere. Ask us about
your market at sales@sparo.run.

**Is there a free trial?**
Yes. 30 days on any plan, no card. There is no activation fee during the trial.

**Is there a mobile app?**
Yes, an Android app for operators. It is the same account as the web dashboard.

**Is the source code open?**
No. Sparo ISP Billing is a hosted service. This repository exists so operators
searching GitHub for ISP billing, MikroTik hotspot billing or M-Pesa billing
can find it.

**Where is the documentation?**
[docs.sparo.run](https://docs.sparo.run) 

---

## Further reading

- [ISP billing systems in Kenya in 2026: what are your options](https://sparo.run/blog/isp-billing-systems-kenya-2026-options)
- [How much does ISP billing software cost?](https://sparo.run/blog/isp-billing-software-cost-kenya)
- [From M-Pesa payment to internet access: what happens in between](https://sparo.run/blog/from-mpesa-payment-to-internet-access)
- [PPPoE vs hotspot: which should your ISP use?](https://sparo.run/blog/pppoe-vs-hotspot-which-should-your-isp-use)
- [What is FreeRADIUS and why does an ISP need it?](https://sparo.run/blog/what-is-freeradius-and-why-does-an-isp-need-it)
- [Hotspot voucher management: where does the money go?](https://sparo.run/blog/hotspot-voucher-management-where-does-the-money-go)
- [Manage MikroTik routers remotely, behind CGNAT](https://sparo.run/blog/manage-mikrotik-routers-remotely)

---

## Contact

- Sales: sales@sparo.run
- Support: support@sparo.run
- Website: [sparo.run](https://sparo.run)

Sparo is a product of Davlin Networks.
