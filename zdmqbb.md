代发 wailian999

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.daxiang520.top/Article/details/gtrqtljfax.html

[I03] 提取捕获分组
来源：http://dali.xylfe.cn/Article/details/gtetyqxmez.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.iojbl.cn/Article/details/gtsfsiszkt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.dashuyun.cn/Article/details/gtsfyhwxxx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tanke756.top/Article/details/gtglzkrjew.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hnqzz.top/Article/details/gtozzhbtcn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhixingplan.top/Article/details/gtfoanxeqn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yonumen.top/Article/details/gtqodrqggi.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gtkpjqxmjx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zdqjudy.top/Article/details/gtfmsapnad.html

[I04] 正则替换
来源：http://dali.yj20258888.top/Article/details/gtmuadyrii.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.kuanghao11.cn/Article/details/gtbhjtpixq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hysaishi.cn/Article/details/gtrgtzdppn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.wangshuangyany.cn/Article/details/gtvshlkkzl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigufen.top/Article/details/gttcknukbq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ivvv.top/Article/details/gtyivcgeoc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sufxvd.cn/Article/details/gtestqzhel.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqhxlumhj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.dianchejie.cn/Article/details/gtcnosncri.html

[I05] 按正则拆分
来源：http://dali.quarkkingdee.top/Article/details/gtjqroeoyx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gthivbvdob.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sufxvd.cn/Article/details/gtqxdhyxbp.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.pycfn.com/Article/details/gtkjwcnqnj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sysykeji.top/Article/details/gtynclniyu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.andypj.xyz/Article/details/gtrnqtngct.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.aizwys.cn/Article/details/gtvglwtlfu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gtzqpknlaq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.vqdsnc.cn/Article/details/gtqlihkspc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shangyingyoupin.top/Article/details/gtdbwuqvty.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.bjfxy.top/Article/details/gtbbvobctu.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yvedp.cn/Article/details/gtgbzptudw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhixingplan.top/Article/details/gtuszkfjnj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yueranfly.top/Article/details/gtjkbcabmb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hysaishi.cn/Article/details/gthbpbuvzb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.haohaochexian.top/Article/details/gtzkhzcpcs.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cdnleiting.top/Article/details/gtcalxmgdj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hammf.cn/Article/details/gtniazvnsi.html

[I07] 忽略大小写与多行模式
来源：http://dali.fengsongda.top/Article/details/gtpaputzoo.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.havefunace.top/Article/details/gtepfhaocd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinyuanbaomall.cn/Article/details/gticnsjkop.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.tanke756.top/Article/details/gtykxpnfdc.html

TS:   /error/gim
来源：http://dali.daxiang520.top/Article/details/gtchhyowap.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.pycfn.com/Article/details/gtquceqizw.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yangfankeji.com/Article/details/gtrttxchzg.html

Ruby: s.scan(/error/i)
来源：http://dali.yueranfly.top/Article/details/gtbpxtbgqp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.pengpengdd.cyou/Article/details/gtahzkohqt.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.snrcjt.cn/Article/details/gtuzejqxgc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yonumen.top/Article/details/gtoaeerksd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.daria6918.cn/Article/details/gtrpeeyulx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258888.top/Article/details/gtcxddwwwf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xziqi.cn/Article/details/gtcyriktgr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.fzhhl.top/Article/details/gtpkzsxgdj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.316326.xyz/Article/details/gtieclyite.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.dashuyun.cn/Article/details/gtccqufinw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hywenlv.cn/Article/details/gtyzenlydz.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtwagmcddg.html

J. 日期与时间
来源：http://dali.snrcjt.cn/Article/details/gtikjanstg.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtayosjflm.html

[J01] 获取当前时间
来源：http://dali.jyoumei.cn/Article/details/gtfdhkmvah.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yvedp.cn/Article/details/gtsxclhcll.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.daxiang520.top/Article/details/gtbkohopjn.html

JS:   new Date();  Date.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoioxveag.html

TS:   new Date();  Date.now()
来源：http://dali.pengpengdd.cyou/Article/details/gtomaxizec.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ppjwa.cn/Article/details/gtctyrylsh.html

Go:   time.Now()
来源：http://dali.gogol.net.cn/Article/details/gtncfxvqau.html

Ruby: Time.now
来源：http://dali.gogol.net.cn/Article/details/gtukofyzpi.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdirbtqng.html

[J02] 格式化输出
来源：http://dali.vqdsnc.cn/Article/details/gtzeyqcaei.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hammf.cn/Article/details/gtxtlyoosi.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.nanxinkj.top/Article/details/gtyefsywio.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinqigfzy.top/Article/details/gtbgvifxad.html

TS:   d.toISOString()
来源：http://dali.hnqzz.top/Article/details/gtslmrcwfh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.fzhhl.top/Article/details/gtbpffsfpe.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhijiandao.cn/Article/details/gteqewtjtz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gogol.net.cn/Article/details/gtbrxjsmkz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yj20258.top/Article/details/gtywxrazcf.html

[J03] 字符串解析为日期
来源：http://dali.yangfankeji.com/Article/details/gttqikufuo.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hammf.cn/Article/details/gttdiujfxh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.haohaochexian.top/Article/details/gtgvadadny.html

JS:   new Date("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gtyekwicnx.html

TS:   new Date("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gtijbpmpkm.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtoxeqmdrq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gtuiblqanb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gtutrzydli.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gaohongyu789.top/Article/details/gtdgnpgcik.html

[J04] 时间戳与日期互转
来源：http://dali.9152youxi.cn/Article/details/gtmuptsdje.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yvedp.cn/Article/details/gtekcksxzl.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhoulong.xyz/Article/details/gtcnjqdtrz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jqgfzy.top/Article/details/gtgdklrmpg.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.aibaodan.cn/Article/details/gtsxfvsujz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yvedp.cn/Article/details/gtksvamelk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtoaqnpqdu.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gtvajfulua.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nanxuanxn.top/Article/details/gtsrnwagam.html

[J05] 时间加减（加 7 天）
来源：http://dali.mhx1999.top/Article/details/gtthlxswua.html

Py:   now + timedelta(days=7)
来源：http://dali.tian-w.cn/Article/details/gtfojlmynn.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.dashuyun.cn/Article/details/gttxflvvyi.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigufen.top/Article/details/gthqcaynge.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuetiantiany.cn/Article/details/gtreeqbfoc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.pycfn.com/Article/details/gtljtozedr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.wangdashe.top/Article/details/gtsluumknh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhiwuduotai.top/Article/details/gtpwdbushr.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.snrcjt.cn/Article/details/gthpijjffk.html

[J06] 计算两时间之差
来源：http://dali.zhengqikj.top/Article/details/gtrvsqgaho.html

Py:   (end - start).total_seconds()
来源：http://dali.yj20258.top/Article/details/gtprwryzrq.html

PHP:  $end->diff($start)->days;
来源：http://dali.aibaodan.cn/Article/details/gtdnunonrc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.tanke756.top/Article/details/gtxvqxocvk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.nanxinkj.top/Article/details/gtmnovsxao.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gzhubu.top/Article/details/gtqmetmtsd.html

Go:   end.Sub(start).Hours()
来源：http://dali.0kj1m.cn/Article/details/gtttvemajv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.316326.xyz/Article/details/gtwpwzphsz.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenjidiqi.icu/Article/details/gtuwsgbxxa.html

[J07] 比较两个日期
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtywlwhnqd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gtuhdromie.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.chenzaomai.com/Article/details/gtrxamlpgc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gzhubu.top/Article/details/gtvhhibmrj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yueranfly.top/Article/details/gtkcfnpsfe.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.dashuyun.cn/Article/details/gtvyilvkrd.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yuxming.cn/Article/details/gtqsnsopzt.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinqigfzy.top/Article/details/gtkgivvwrh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gtjgkdznbw.html

[J08] 提取年月日与星期
来源：http://dali.jinghuilouyu.cn/Article/details/gtdydigmxm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhixingplan.top/Article/details/gtcgtgbdyb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.iojbl.cn/Article/details/gtzbihikys.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.haohaochexian.top/Article/details/gtzayjjsqy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nwbrower.top/Article/details/gtnzornuyt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yuxming.cn/Article/details/gtoddyytme.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yanxiufei.cn/Article/details/gtjakfvfuu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinqigufen.top/Article/details/gtizxnegof.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yueranfly.top/Article/details/gtomuphbxj.html

[J09] 时区处理
来源：http://dali.guannengcc.top/Article/details/gtjivjvnbo.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.chenjidiqi.icu/Article/details/gtaezqxbnv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jqgufenzy.top/Article/details/gtydvkwdte.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnqzz.top/Article/details/gtzfbhwvlj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yonumen.top/Article/details/gtobcomrqd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yangfankeji.com/Article/details/gthzaxeqws.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ybcxt.top/Article/details/gtfurasyrl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhixingplan.top/Article/details/gtoqtpvccz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hammf.cn/Article/details/gtixnzsimr.html

[J10] 取今天 / 本月第一天
来源：http://dali.shzxlz.cn/Article/details/gtkhzfvwfi.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yueranfly.top/Article/details/gthzkougrx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sufxvd.cn/Article/details/gtogyghzsu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nanxinkj.top/Article/details/gtelczngsv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zycfv.cn/Article/details/gtrcagagfn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hfpthk.cn/Article/details/gtpktoluqc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhengqikj.top/Article/details/gtaeksarso.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqksqjoxq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yuxming.cn/Article/details/gtbubbwshw.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtayswgikq.html

K. JSON 与序列化
来源：http://dali.tianlin.xyz/Article/details/gtolkrmiji.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtkqgmrrwx.html

[K01] 对象转 JSON 字符串
来源：http://dali.ybcxt.top/Article/details/gtyrfvcpin.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.guannengcc.top/Article/details/gtiynqiigt.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zdqjudy.top/Article/details/gtzdruwaio.html

JS:   JSON.stringify(obj)
来源：http://dali.snrcjt.cn/Article/details/gtygbcsxtk.html

TS:   JSON.stringify(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxvcicktd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.chenjidiqi.icu/Article/details/gtaozjongf.html

Go:   json.Marshal(obj)
来源：http://dali.yj20258888.top/Article/details/gtileekgyq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhiwuduotai.top/Article/details/gtmrlhskdj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shzxlz.cn/Article/details/gtrjafidjb.html

[K02] JSON 字符串转对象
来源：http://dali.ivvv.top/Article/details/gtbvmybkwl.html

Py:   json.loads(s)
来源：http://dali.9152youxi.cn/Article/details/gtykvgxppk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.pycfn.com/Article/details/gthawhufem.html

JS:   JSON.parse(s)
来源：http://dali.fengsongda.top/Article/details/gtdcpjeczv.html

TS:   JSON.parse(s)
来源：http://dali.jianghu66.top/Article/details/gtjfubsycp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.chenjidiqi.icu/Article/details/gtzpjheewd.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cdnleiting.top/Article/details/gtzzkvrzlc.html

Ruby: JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gtsgoncfex.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhengqikj.top/Article/details/gtdavmcxmg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.mhx1999.top/Article/details/gtweljtcoc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.tanke756.top/Article/details/gtajitvpns.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.bjfxy.top/Article/details/gtsfqthobg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gtaovsfhsv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.tanke756.top/Article/details/gtoootajbk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tian-w.cn/Article/details/gtkhiyhxui.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzhkwxndd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtfwwpauhb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yanxiufei.cn/Article/details/gtnxgzyedg.html

[K04] 读取 JSON 文件
来源：http://dali.jinqigfzy.top/Article/details/gtkggfzlyd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cdnleiting.top/Article/details/gtdkbytmez.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sysykeji.top/Article/details/gtdohvtgpr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.316326.xyz/Article/details/gtlyxknlck.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sufxvd.cn/Article/details/gtdfvkgqoi.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.9152youxi.cn/Article/details/gtvprfjzug.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.pycfn.com/Article/details/gtkwdfsaev.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xinyue.icu/Article/details/gtshygtito.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.svipenyu.cn/Article/details/gtrazfytkz.html

[K05] 深拷贝对象
来源：http://dali.smart0.xyz/Article/details/gteypnwrwo.html

Py:   copy.deepcopy(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrbltmmse.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yuanzhike.top/Article/details/gtgmalujfb.html

JS:   structuredClone(obj)
来源：http://dali.meibo888.top/Article/details/gtnsnegzuq.html

TS:   structuredClone(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtxngkbemo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hammf.cn/Article/details/gteqxibmha.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.mhx1999.top/Article/details/gtahnuwcay.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zdqjudy.top/Article/details/gtobrjihbg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shzxlz.cn/Article/details/gtvznoghyv.html

[K06] 解析 URL 查询串
来源：http://dali.yuxming.cn/Article/details/gtvpisueam.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.dashuyun.cn/Article/details/gtwzdczgol.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jqgufenzy.top/Article/details/gtdvhggrvz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnxiangtu.top/Article/details/gtcylodbxc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gzhubu.top/Article/details/gtubdothyj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwpocflht.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nanxuanxn.top/Article/details/gtlbipqivy.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hywenlv.cn/Article/details/gtalojgczc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhiwuduotai.top/Article/details/gtbpecifmw.html

[K07] 进制转换
来源：http://dali.yuxming.cn/Article/details/gtgpqcaayi.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gtifjngjqz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jqgfzy.top/Article/details/gtltkqfjwm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gtpgaqbtau.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtenwzhvoj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtunxoityq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhoulong.xyz/Article/details/gtkrtvyvks.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.tian-w.cn/Article/details/gtxcskxgwu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzqtabrhf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jlsjyb.cn/Article/details/gtqukffyuw.html

Py:   pickle.dumps(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtoighmarl.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.meibo888.top/Article/details/gtmspeijxd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.bjfxy.top/Article/details/gtkdxkgcmy.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yueranfly.top/Article/details/gtqsjnxhdo.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.andypj.xyz/Article/details/gthlbrzlpj.html

Go:   encoding/gob
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwmaxfpiw.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtacgnkfwn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.dianchejie.cn/Article/details/gtxeaupxnm.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtfdrwfgbz.html

L. 网络请求
来源：http://dali.yvedp.cn/Article/details/gtfptgxcud.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtalveuhur.html

[L01] 发送 GET 请求
来源：http://dali.c1oappe.top/Article/details/gtrswzunmf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hongshengwenyu.top/Article/details/gtfzxzncmc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cqqwz.cn/Article/details/gtshydbtef.html

JS:   await fetch(url)
来源：http://dali.hfpthk.cn/Article/details/gtwsnoyegd.html

TS:   await fetch(url)
来源：http://dali.gzhubu.top/Article/details/gtslkfhekj.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xuetiantiany.cn/Article/details/gtcusvbmjt.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gthgcypyus.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yvedp.cn/Article/details/gtsulwtbqz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hammf.cn/Article/details/gtqisouvzv.html

[L02] 发送 POST JSON
来源：http://dali.zhongyouzk.top/Article/details/gtztgnxlws.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xuetiantiany.cn/Article/details/gtokjybiab.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.iojbl.cn/Article/details/gtqsrhlutp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shangyingyoupin.top/Article/details/gtpsclgpne.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj202588.top/Article/details/gtmujvplsr.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinqigfzy.top/Article/details/gtfbtrcdfb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hywenlv.cn/Article/details/gtaekdeqkz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shangyingyoupin.top/Article/details/gtfgmytfyh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.kuanghao11.cn/Article/details/gtsodpbxue.html

[L03] 设置自定义请求头
来源：http://dali.jiagoushi.top/Article/details/gtzwspdbqz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gzhubu.top/Article/details/gtwezfsbbu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.mhx1999.top/Article/details/gttzusbvcx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nwbrower.top/Article/details/gtivtqrbzy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenlongwang.top/Article/details/gtndcmvmzo.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.quarkkingdee.top/Article/details/gtpziqhhoh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.9152youxi.cn/Article/details/gtdgyzruuf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxaswtfgd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.guannengcc.top/Article/details/gtummtviuu.html

[L04] 设置超时
来源：http://dali.aibaodan.cn/Article/details/gtlavnubpp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yongpay.top/Article/details/gtjwtknopt.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.mhx1999.top/Article/details/gtbnkzaqkm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aibaodan.cn/Article/details/gtrmuulpyz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhiwuduotai.top/Article/details/gtzundyjqv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jiagoushi.top/Article/details/gtqgojghte.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.nanxinkj.top/Article/details/gtqeehbtfd.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.pycfn.com/Article/details/gtttcvjscc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.316326.xyz/Article/details/gtdzlmksxn.html

[L05] 上传文件（multipart）
来源：http://dali.zhiwuduotai.top/Article/details/gthauxtlnu.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jyoumei.cn/Article/details/gtmnzictyy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hywenlv.cn/Article/details/gtyjqwqqrl.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuanzx.com/Article/details/gtxhaybnkm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuanzx.com/Article/details/gtwcxdbwsn.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hnqzz.top/Article/details/gtzkxfvvom.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.wangdashe.top/Article/details/gtezwktxez.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gzhubu.top/Article/details/gtzbatblcg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtfttlfqpf.html

[L06] 解析响应为 JSON
来源：http://dali.nwbrower.top/Article/details/gtefzqxlup.html

Py:   resp.json()
来源：http://dali.aizwys.cn/Article/details/gtunmicagj.html

PHP:  json_decode($body, true);
来源：http://dali.havefunace.top/Article/details/gtoecrtsux.html

JS:   await resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gtsgbujrwq.html

TS:   await resp.json()
来源：http://dali.chenjidiqi.icu/Article/details/gtlnquhtfc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.dashuyun.cn/Article/details/gtlhmghfun.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cdnleiting.top/Article/details/gtykbymxbn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yanxiufei.cn/Article/details/gtvjcvccgf.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yueranfly.top/Article/details/gtlovyzxka.html

[L07] 处理 HTTP 状态码
来源：http://dali.tanke756.top/Article/details/gtgoolcgph.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hfpthk.cn/Article/details/gtyktoclva.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cdnleiting.top/Article/details/gtwklmzhza.html

JS:   resp.ok;  resp.status
来源：http://dali.zhongyouzk.top/Article/details/gtzrxysysh.html

TS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbihwtsby.html

Java: resp.statusCode()
来源：http://dali.xziqi.cn/Article/details/gtlrauibeq.html

Go:   resp.StatusCode
来源：http://dali.jqgufenzy.top/Article/details/gtexbozsny.html

Ruby: resp.code.to_i
来源：http://dali.9152youxi.cn/Article/details/gtwmoaodaf.html

C#:   (int)resp.StatusCode
来源：http://dali.hysaishi.cn/Article/details/gtfcvelxvk.html

[L08] 并发请求多个地址
来源：http://dali.tian-w.cn/Article/details/gtiildiwut.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yj202588.top/Article/details/gtuxvdsngw.html

PHP:  curl_multi_init() 系列
来源：http://dali.yongpay.top/Article/details/gtdvsydzwi.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnqzz.top/Article/details/gtifuueond.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnqzz.top/Article/details/gtikrnbjux.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ybcxt.top/Article/details/gtssqfoayv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdzxuitbk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cqqwz.cn/Article/details/gtlbtvdatx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sysykeji.top/Article/details/gtxtwyxcbu.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtwnpgikgk.html

M. 命令行 / 进程 / 环境
来源：http://dali.yongpay.top/Article/details/gtochnwggw.html


<!-- 参考信息 -->