# Team Onboarding Guide

Welcome to the new Operations Dashboard! This guide will help your team get up to speed quickly.

## 🎯 What's New?

Your team now has a centralized, web-based system for:
- ✅ Documenting shift handovers
- ✅ Monitoring global data center timings
- ✅ Tracking 24/7 operations
- ✅ Planning deployments around business hours

## 👥 For Your Team Members

### Getting Started (First Time)

1. **Access the Dashboard**
   - Open: `https://YOUR-DOMAIN.github.io/GIthubpage_for_time/landing.html`
   - Bookmark this page!

2. **Explore the Tools**
   - Click on "Open Handover Generator"
   - Click on "View DC Timings"
   - Read the quick tips on the landing page

3. **Run Your First Handover**
   - Go to Handover Generator
   - Select your agent name
   - Fill in sample data
   - Click "Generate Handover"
   - Click "Copy to Clipboard"
   - Send to your team lead

### Daily Usage

#### **At Start of Shift:**
1. Open landing page
2. Check DC timings for any business hour windows
3. Read any handover notes from previous agent

#### **During Shift:**
1. Monitor DC timings dashboard
2. Check if any systems in business hours
3. Note tasks for handover

#### **Before End of Shift:**
1. Open Handover Generator
2. Document:
   - ✅ Tasks you received at start
   - ✅ Tasks you completed
   - ✅ Tasks pending for next shift
   - ✅ Any tickets worked on
   - ✅ Any special notes or blockers
3. Copy and send to next agent
4. Include link to DC timings dashboard

## 📋 Handover Generator - Team Instructions

### What to Document:

**Tasks from Previous Agent:**
- What did the previous agent hand over to you?
- What was your start-of-shift status?

Example:
```
- Monitor ticket-001 (waiting for client response)
- Support for customers in APAC region
- Monitor DB performance alerts
- Check email for escalations
```

**Tasks Completed:**
- What did you accomplish during your shift?
- What tickets did you close?
- What issues did you resolve?

Example:
```
- Completed ticket-001 (client responded)
- Resolved 3 support tickets
- Updated DB indexes for performance
- Cleared alert queue
```

**Pending Tasks:**
- What needs attention from the next agent?
- What's in progress?
- What's waiting on something?

Example:
```
- Ticket-042: Under investigation - potential network issue
- Customer ABC: Waiting on resource approval
- Performance optimization: In progress, 50% complete
- Awaiting API response from vendor
```

**Ticket Details:**
- What specific tickets need attention?
- What's their status?

Example:
```
TK-001: Customer login issue - RESOLVED
TK-042: Network slowness - INVESTIGATING - 2hrs
TK-089: Feature request - PENDING APPROVAL
TK-105: Bug fix - IN DEVELOPMENT
```

**Special Notes:**
- Anything unusual?
- Any blockers?
- Any urgent matters?
- Important customer info?

Example:
```
⚠️ Database server hitting 95% CPU - monitor closely
🔴 VIP Customer ABC having connectivity issues
⚡ New deployment scheduled for 3 PM - coordinate with infra team
📞 Client escalation call scheduled at 2 PM
```

## 📊 DC Timings Dashboard - Team Instructions

### What Each Component Shows:

- **Clock Display**: Current time in that data center
- **Business Hours Indicator**: 
  - 🟢 Green = Business Hours (no deployments)
  - 🔴 Red = Non-Business Hours (safe for deployments)
- **Countdown Timer**: When will business hours end?
- **Product List**: What systems run in that DC

### How to Use for Planning:

1. **Before Maintenance:**
   - Open DC Timings
   - Check which DCs are in non-business hours
   - Plan your work for those windows

2. **Deployment Planning:**
   - Use "Check Availability" button
   - Select product and time
   - See which DCs are available

3. **Monitoring:**
   - Keep dashboard open during shifts
   - Watch for approaching business hour windows
   - Plan work accordingly

### Understanding Shift Times:

**Shift 1 (IST):** 5:30 AM - 3:00 PM  
- ✅ Morning and early afternoon coverage in India

**Shift 2 (IST):** 2:30 PM - 11:00 PM  
- ✅ Afternoon and evening coverage in India

**Shift 3 (PST):** 9:00 PM - 5:50 AM  
- ✅ Night shift covering US and early morning

## 🎓 Training Checklist

Complete this during your first week:

- [ ] Access the landing page without help
- [ ] Generate a sample handover
- [ ] Copy a handover to clipboard
- [ ] Understand your shift times
- [ ] Find DC timings dashboard
- [ ] Identify your team's DCs
- [ ] Check countdown timers
- [ ] Use status filters (business/non-business)
- [ ] Understand ticket notation
- [ ] Practice writing handover notes

## 🆘 Common Questions

### Q: Do I need to install anything?
**A:** No! It's all web-based. Just use any browser.

### Q: Is my data private?
**A:** Yes! Everything stays on your device. Nothing is sent to servers.

### Q: Can I access from my phone?
**A:** Yes! All tools are mobile-friendly.

### Q: What if I make a mistake in handover?
**A:** The document is for reference only. Just copy it again with correct info.

### Q: Can I change agent names?
**A:** Yes! Ask your tech lead to update the dropdown list.

### Q: Why does the time look wrong?
**A:** Check your device's clock settings. Times are based on your system clock.

### Q: What timezone is each DC in?
**A:** Hover over the DC name to see timezone info, or check README.md

## 📞 Support

### For Questions:
- Ask your team lead
- Check README.md for documentation
- Check browser console (F12) for error messages

### For Customizations:
- Contact your tech lead
- Can be updated without code knowledge

## 🔄 Handover Best Practices

### ✅ DO:
- Be specific and clear
- Include ticket numbers
- Mention any blockers
- Note urgent items
- Copy immediately and send
- Include DC timings link
- Update handover regularly

### ❌ DON'T:
- Leave fields blank
- Use vague descriptions
- Forget special notes
- Assume next agent knows context
- Copy old handovers
- Ignore pending items
- Miss deadline to send handover

## 💡 Pro Tips

1. **Template for Pending Tasks:**
   ```
   [TICKET]: [Description] - [Status] - [Blockers]
   Example: TK-042: Customer complaint - In Investigation - Waiting for logs
   ```

2. **Priority Notation:**
   ```
   🔴 CRITICAL - needs immediate attention
   🟡 HIGH - needs attention soon
   🟢 NORMAL - routine tasks
   ```

3. **Copy the Dashboard Link:**
   - Share: `https://github.io/landing.html`
   - Team can check timings anytime

4. **Set Shift Reminders:**
   - Set phone alarm 30 mins before handover
   - Start preparing documentation early

## 📱 Bookmarks to Save

Save these in your browser:

1. **Dashboard Home**
   ```
   https://YOUR-DOMAIN.github.io/GIthubpage_for_time/landing.html
   ```

2. **Handover Generator**
   ```
   https://YOUR-DOMAIN.github.io/GIthubpage_for_time/handover-generator.html
   ```

3. **DC Timings**
   ```
   https://YOUR-DOMAIN.github.io/GIthubpage_for_time/index.html
   ```

## 🎉 You're Ready!

You now have everything needed to:
- Document handovers professionally
- Monitor global operations
- Plan around business hours
- Collaborate smoothly with your team

**Questions?** Ask your team lead or tech administrator.

---

**Last Updated:** March 2026  
**Version:** 1.0  
**Status:** Ready to Use

