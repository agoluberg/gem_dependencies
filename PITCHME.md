# gem dependencies

---

### Lightning talk inspired by

### **Andrew Nesbitt**'s _With a Little Help from My Friends_

### which he gave as a 30 minute talk on Bath Ruby 2018

---

### Data from Libraries.io and Rubygems.org

---

### ~25 Million open source repositories

### On avg 52 gems per Gemfile.lock

---

### 46% of gems have not been updated in 3 years

---

### 28% of gems (> 37 thousand gems) have no license declared

### Which means you are not allowed to use them.

---

### 90% of gems have a bus factor of 1

### Avg gem has 1.2 owners

---

### Every gem is a potential attack vector

### It's not a bug, it's a feature of rubygems

---

### `gem install arbitrary code execution via extconf.rb`

---

### ~ 500,000 Ruby developers

### ~ 144,000 gems

### ~ 50,000 gem owners

---

### Some gems are more equal than others

### 80% of all downloads are of 160 gems

---

### Those 160 gems are maintained by 262 people

---

### We are not only standing on the shoulders of giants

### we are crushing them

---

https://www.commitstrip.com/2014/05/07/the-truth-behind-open-source-apps/

---

### What can we do for the maintainers?

### Send them user data

---

### Maintainers don't know

* Ruby version
* OS make and version
* Which other gems are (often) used together
* When and which errors happen and why
* Which parts of their code are used most

---

### Rubygems collects install stats already, but does not make them accessible

* Ruby version
* Rubygems version
* OS version
* CPU architecture

---

### Bugsnag (and others) could share error stats

* Exception classes
* Stack traces
* Environment details

---

### Performance stats are collected by New Relic (and others)

* Most frequently called methods
* Least frequently called methods
* Slowest methods
* Hot code paths

---

### What else can we do for the maintainers?

### Companies should sponsor owners and maintainers

---

### Owners should give people that open PRs push rights on repos quickly

### This does fuel the motivation to become a maintainer

---

### Having multiple active owners and better incentivized maintainers will make gem development more robust

---

Watch the whole talk: https://www.youtube.com/watch?v=hW4wUpoBHr8

---

## Thanks :-)

## Andreas

## @mediafinger
