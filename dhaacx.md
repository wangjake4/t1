代发 wailian999

[I02] 提取所有匹配
来源：http://dali.cheryme.top/Article/details/gtngroqtnj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.wangshuangyany.cn/Article/details/gtzksjmkkc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xuanzx.com/Article/details/gtkojmjtsl.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gtthsrwbss.html

TS:   s.match(/\d+/g)
来源：http://dali.ppjwa.cn/Article/details/gtctybemju.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.wangdashe.top/Article/details/gtzhfqksmk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hongshengwenyu.top/Article/details/gtervvagsi.html

Ruby: s.scan(/\d+/)
来源：http://dali.hnqzz.top/Article/details/gtxjmrlcec.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinqigufen.top/Article/details/gtncrowntn.html

[I03] 提取捕获分组
来源：http://dali.shzxlz.cn/Article/details/gtlnsolrju.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xuetiantiany.cn/Article/details/gthbvrtmru.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yanxiufei.cn/Article/details/gtscqjlyrf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jiagoushi.top/Article/details/gtmwwaiyfs.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhongyouzk.top/Article/details/gthrqpwicg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.kuanghao11.cn/Article/details/gtkalnyuso.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zdqjudy.top/Article/details/gtkmtiiopk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zycfv.cn/Article/details/gtzrovkrhk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.pengpengdd.cyou/Article/details/gtjnsmollu.html

[I04] 正则替换
来源：http://dali.jianghu66.top/Article/details/gtygmldabe.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.kuanghao11.cn/Article/details/gtezkvofmh.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.havefunace.top/Article/details/gthxpymakd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yanxiufei.cn/Article/details/gtlesioary.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxinkj.top/Article/details/gtxoflzngh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ppjwa.cn/Article/details/gtkjekohyd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gtfwyslhod.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sxryk.cn/Article/details/gtmrxzubhd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sufxvd.cn/Article/details/gtkmezrazb.html

[I05] 按正则拆分
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoyvezjig.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gteykcrmtw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yuanzhike.top/Article/details/gtmgcilmyu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gtpcmsfqvp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigufen.top/Article/details/gtcajoqsgd.html

Java: s.split("\\s*,\\s*")
来源：http://dali.guannengcc.top/Article/details/gtvpzpmgeb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ydzc1.top/Article/details/gtichbbssz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gteprieovg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yuxming.cn/Article/details/gtdbizcypt.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.pycfn.com/Article/details/gtqdnymzwr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zdqjudy.top/Article/details/gtgueoduah.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hnxiangtu.top/Article/details/gtqhsqbmdj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxuanxn.top/Article/details/gtpwloixuz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ybcxt.top/Article/details/gtkahjlqma.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gtcsyyduyy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.316326.xyz/Article/details/gtgzwtmtsd.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sufxvd.cn/Article/details/gtymtopunb.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zdqjudy.top/Article/details/gtibqnfehr.html

[I07] 忽略大小写与多行模式
来源：http://dali.yj20258.top/Article/details/gtksqbjhqr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sysykeji.top/Article/details/gtfqhxasmr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jiagoushi.top/Article/details/gtxlkjrkpf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gtteykgdwq.html

TS:   /error/gim
来源：http://dali.ppjwa.cn/Article/details/gtmznszwgp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.nanxinkj.top/Article/details/gtifosylyw.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cdnleiting.top/Article/details/gtydrprmoj.html

Ruby: s.scan(/error/i)
来源：http://dali.yangfankeji.com/Article/details/gtxzmrekje.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yj20258888.top/Article/details/gthsccelzg.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.daxiang520.top/Article/details/gtwkzdwfsk.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.haohaochexian.top/Article/details/gtrzyvjzni.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jyoumei.cn/Article/details/gtqyxhukfq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj202588.top/Article/details/gtdczekrue.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.snrcjt.cn/Article/details/gtcyocbfin.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sufxvd.cn/Article/details/gtjvojhpsh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hammf.cn/Article/details/gtnvfeeeje.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.tian-w.cn/Article/details/gtbmcwzizu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.vqdsnc.cn/Article/details/gttfmhdjgs.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtpxidzhev.html

J. 日期与时间
来源：http://dali.yuanzhike.top/Article/details/gtqeceztcl.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtrbsvphax.html

[J01] 获取当前时间
来源：http://dali.yj20258.top/Article/details/gtzsvzdfhw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yongpay.top/Article/details/gtodnwrapn.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jqgufenzy.top/Article/details/gtlmgskhmd.html

JS:   new Date();  Date.now()
来源：http://dali.jinghuilouyu.cn/Article/details/gtzgwetncg.html

TS:   new Date();  Date.now()
来源：http://dali.hnxiangtu.top/Article/details/gtsoozyebi.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jqgufenzy.top/Article/details/gtuqaytfdy.html

Go:   time.Now()
来源：http://dali.vqdsnc.cn/Article/details/gtxonbnjfe.html

Ruby: Time.now
来源：http://dali.kuanghao11.cn/Article/details/gttunahold.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.havefunace.top/Article/details/gtvihvmkjs.html

[J02] 格式化输出
来源：http://dali.gotoacloud.top/Article/details/gtmmavxtze.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.mhx1999.top/Article/details/gtmwkhmzra.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.vqdsnc.cn/Article/details/gtowoodmvp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yj202588.top/Article/details/gtrdzytacv.html

TS:   d.toISOString()
来源：http://dali.pengpengdd.cyou/Article/details/gtiifucuwv.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.mhx1999.top/Article/details/gtjnybtymc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.kuanghao11.cn/Article/details/gtraqaavgt.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxinkj.top/Article/details/gtotykklnt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xuetiantiany.cn/Article/details/gtrddskswv.html

[J03] 字符串解析为日期
来源：http://dali.smart0.xyz/Article/details/gtnsoqmhql.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.svipenyu.cn/Article/details/gtfjcgsufs.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.havefunace.top/Article/details/gttoxywuwo.html

JS:   new Date("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gtpeqbxjyq.html

TS:   new Date("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtgvlvucqy.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtrgxsltlw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtjrtsmymm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gtrujxlyib.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ppjwa.cn/Article/details/gtkfpgmzdw.html

[J04] 时间戳与日期互转
来源：http://dali.iojbl.cn/Article/details/gtizgjaavf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtpscdpzno.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ivvv.top/Article/details/gtqlrfyefw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yuanzhike.top/Article/details/gtvdckidgg.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.guowangkeji.top/Article/details/gtxqajpatl.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.chenjidiqi.icu/Article/details/gttitfvzdp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.smart0.xyz/Article/details/gtwtkivhnq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.fengsongda.top/Article/details/gtdpyhwlxg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.bjfxy.top/Article/details/gthuqigjkd.html

[J05] 时间加减（加 7 天）
来源：http://dali.gzhubu.top/Article/details/gtudxpxqmq.html

Py:   now + timedelta(days=7)
来源：http://dali.cqqwz.cn/Article/details/gtcxvqrxvk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.mhx1999.top/Article/details/gtovdvlkcp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shangyingyoupin.top/Article/details/gtelnswdna.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nwbrower.top/Article/details/gtaanlbvdp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhengqikj.top/Article/details/gtjvidojdy.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xinyue.icu/Article/details/gtcksbdbqn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.mhx1999.top/Article/details/gtjftnpqit.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nwbrower.top/Article/details/gtqhhzqilg.html

[J06] 计算两时间之差
来源：http://dali.jyoumei.cn/Article/details/gtuawioyyc.html

Py:   (end - start).total_seconds()
来源：http://dali.daria6918.cn/Article/details/gtlbeminpb.html

PHP:  $end->diff($start)->days;
来源：http://dali.yueranfly.top/Article/details/gtbabofqyl.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.pycfn.com/Article/details/gtopvxheyz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.nanxinkj.top/Article/details/gtdtakqpyl.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.chenjidiqi.icu/Article/details/gtqsunhfkr.html

Go:   end.Sub(start).Hours()
来源：http://dali.gotoacloud.top/Article/details/gtktvxrsok.html

Ruby: end - start                 # 返回秒数
来源：http://dali.andypj.xyz/Article/details/gtujikhxyx.html

C#:   (end - start).TotalSeconds
来源：http://dali.jlsjyb.cn/Article/details/gtqdeqnrje.html

[J07] 比较两个日期
来源：http://dali.jlsjyb.cn/Article/details/gtanpclzbu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ybcxt.top/Article/details/gtqwdkapgu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gaohongyu789.top/Article/details/gtllzummob.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gaohongyu789.top/Article/details/gtggybjztu.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ppjwa.cn/Article/details/gtioyirjdi.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.guowangkeji.top/Article/details/gtcxmejceq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.wangshuangyany.cn/Article/details/gtwpspfleh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sweek.top/Article/details/gtgdfdpdue.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.mhx1999.top/Article/details/gtleqfwzsp.html

[J08] 提取年月日与星期
来源：http://dali.snrcjt.cn/Article/details/gtzhhnfvpk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ehwqpu.com/Article/details/gtfkbtkxeb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj20258.top/Article/details/gttksajceu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hongshengwenyu.top/Article/details/gtvmizofjw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yangfankeji.com/Article/details/gttinsqzqu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.havefunace.top/Article/details/gthnbthmzp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.guowangkeji.top/Article/details/gtaozmllqn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yj202588.top/Article/details/gtcuxxkqib.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gzhubu.top/Article/details/gtkfucoasf.html

[J09] 时区处理
来源：http://dali.tianlin.xyz/Article/details/gtsknszhgx.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.daria6918.cn/Article/details/gtbtmbdnsy.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiorviycl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhoulong.xyz/Article/details/gtwzyorvrp.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guannengcc.top/Article/details/gtesrynqws.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sweek.top/Article/details/gtvvsnlhnf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.chenzaomai.com/Article/details/gtumqglahl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhiwuduotai.top/Article/details/gtgudajyms.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xuetiantiany.cn/Article/details/gtdvjubhaq.html

[J10] 取今天 / 本月第一天
来源：http://dali.bjfxy.top/Article/details/gtdfkrshys.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ppjwa.cn/Article/details/gtcnebeiqa.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tanke756.top/Article/details/gtvbjyvbgi.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhiwuduotai.top/Article/details/gteukcacbc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhengqikj.top/Article/details/gtiwuyoapz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.dashuyun.cn/Article/details/gtigueztjh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.316326.xyz/Article/details/gtaeeteczu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.chenjidiqi.icu/Article/details/gtqconuzej.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yongpay.top/Article/details/gtahnrcllc.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtxvxndbmb.html

K. JSON 与序列化
来源：http://dali.yongpay.top/Article/details/gtndfscalq.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtgdydsays.html

[K01] 对象转 JSON 字符串
来源：http://dali.bjfxy.top/Article/details/gtxrprkhek.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jyoumei.cn/Article/details/gtecakczyt.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yueranfly.top/Article/details/gtibhhbjbu.html

JS:   JSON.stringify(obj)
来源：http://dali.tianlin.xyz/Article/details/gtfvvjkxqe.html

TS:   JSON.stringify(obj)
来源：http://dali.fzhhl.top/Article/details/gtiuwtsjec.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hnqzz.top/Article/details/gtwegmpehr.html

Go:   json.Marshal(obj)
来源：http://dali.cucudq.cn/Article/details/gtdrgfkbif.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.redwolf501.top/Article/details/gtvvjqrffs.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtsabthyyy.html

[K02] JSON 字符串转对象
来源：http://dali.yanxiufei.cn/Article/details/gtpkrjfwwq.html

Py:   json.loads(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcwrtfjkl.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yongpay.top/Article/details/gtddkhxlcw.html

JS:   JSON.parse(s)
来源：http://dali.ybcxt.top/Article/details/gtgtvfezef.html

TS:   JSON.parse(s)
来源：http://dali.daxiang520.top/Article/details/gtkyaahoaf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xziqi.cn/Article/details/gtlroapepl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jiagoushi.top/Article/details/gtskyecowt.html

Ruby: JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtjllfdvhx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhongyouzk.top/Article/details/gtswlyvrzo.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xuanzx.com/Article/details/gtiruofmty.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj20258.top/Article/details/gtappwcgdo.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xylfe.cn/Article/details/gthodctsfd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258.top/Article/details/gtxccrgicq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.guannengcc.top/Article/details/gtqhqsopdn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.haohaochexian.top/Article/details/gtmblektwp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwwmgnbcc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtsiucjvju.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hysaishi.cn/Article/details/gtzmbpqqzx.html

[K04] 读取 JSON 文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtocbmeonu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinqigufen.top/Article/details/gtmjgdpall.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.daria6918.cn/Article/details/gtoydpsjoq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrddtxlpe.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tian-w.cn/Article/details/gtcpsfxsau.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yj20258.top/Article/details/gtewyulsic.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.daria6918.cn/Article/details/gtcivtszwh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.andypj.xyz/Article/details/gtckzlfzjn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gotoacloud.top/Article/details/gtkstkdeev.html

[K05] 深拷贝对象
来源：http://dali.chenzaomai.com/Article/details/gtlfowhirh.html

Py:   copy.deepcopy(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtnuuoqvoi.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yueranfly.top/Article/details/gtahfxebro.html

JS:   structuredClone(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtbqgshqbf.html

TS:   structuredClone(obj)
来源：http://dali.ydzc1.top/Article/details/gtrfeqpmso.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.iojbl.cn/Article/details/gtsegikwdc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.smart0.xyz/Article/details/gtuxhvgvko.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hongshengwenyu.top/Article/details/gtflktulot.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.smart0.xyz/Article/details/gtufruayfy.html

[K06] 解析 URL 查询串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnoxavtqu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shzxlz.cn/Article/details/gtologwvrl.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhiwuduotai.top/Article/details/gtnvtleisj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.svipenyu.cn/Article/details/gthusokgjs.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhixingplan.top/Article/details/gtrrrjqgrl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sufxvd.cn/Article/details/gtiweeykfn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gtwrtgnmbd.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtijrigxub.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cashguo.top/Article/details/gtjignewzb.html

[K07] 进制转换
来源：http://dali.fengsongda.top/Article/details/gtaztgzkvz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtjbaasxdz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.chenzaomai.com/Article/details/gtmtngztnf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gtqmpqlyzj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtvffosbra.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkzynokvr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ehwqpu.com/Article/details/gthdavgrmh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jqgfzy.top/Article/details/gtvjzzpkcj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gtfqobliuv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinghuilouyu.cn/Article/details/gtgoswqxjf.html

Py:   pickle.dumps(obj)
来源：http://dali.ehwqpu.com/Article/details/gtslubuwwm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cashguo.top/Article/details/gtdlwqkeos.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ywan-chungtsiang.top/Article/details/gttuioupkt.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.daria6918.cn/Article/details/gtahvmrrzn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zycfv.cn/Article/details/gteaubiawh.html

Go:   encoding/gob
来源：http://dali.wangshuangyany.cn/Article/details/gtipepzpht.html

Ruby: Marshal.dump(obj)
来源：http://dali.sxryk.cn/Article/details/gtygvbnvkd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhengqikj.top/Article/details/gtgbcqvzan.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtfqssdxnh.html

L. 网络请求
来源：http://dali.birdmap.top/Article/details/gtqhhzxlro.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtnxnbkyxh.html

[L01] 发送 GET 请求
来源：http://dali.316326.xyz/Article/details/gtizutwxpw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sxryk.cn/Article/details/gtfhirfetv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cucudq.cn/Article/details/gtgksrsesv.html

JS:   await fetch(url)
来源：http://dali.snrcjt.cn/Article/details/gtizfhodxu.html

TS:   await fetch(url)
来源：http://dali.gotoacloud.top/Article/details/gtlbbrkvkj.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hammf.cn/Article/details/gtjkrppcgk.html

Go:   resp, err := http.Get(url)
来源：http://dali.aizwys.cn/Article/details/gtnouajywu.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hnxiangtu.top/Article/details/gtxgawfkab.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.chenjidiqi.icu/Article/details/gtzxhdufxb.html

[L02] 发送 POST JSON
来源：http://dali.ppjwa.cn/Article/details/gtdsiuouoc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xziqi.cn/Article/details/gtrxwajunm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.aizwys.cn/Article/details/gtdembzcem.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ppjwa.cn/Article/details/gtjpczjwhb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenlongwang.top/Article/details/gtkqohsbgb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.316326.xyz/Article/details/gtnutnzxcb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jqgfzy.top/Article/details/gtrrffduyt.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ybcxt.top/Article/details/gtxzyvzyen.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hongshengwenyu.top/Article/details/gtoblahude.html

[L03] 设置自定义请求头
来源：http://dali.andypj.xyz/Article/details/gttfxdfzoq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.dashuyun.cn/Article/details/gtsufmmmcp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.quarkkingdee.top/Article/details/gtucyncysy.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigfzy.top/Article/details/gtuomkjhwg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.mhx1999.top/Article/details/gthyjsxxgf.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrcszjanp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.dashuyun.cn/Article/details/gtiwwwfptx.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtysngexun.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sufxvd.cn/Article/details/gtnklpvnrz.html

[L04] 设置超时
来源：http://dali.sufxvd.cn/Article/details/gtxntsezct.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yvedp.cn/Article/details/gtdoiixvor.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.pengpengdd.cyou/Article/details/gtcaezqtic.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sufxvd.cn/Article/details/gtyrmxmhqv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tian-w.cn/Article/details/gttqkdwisg.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shangyingyoupin.top/Article/details/gtwvlsnlfh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.nwbrower.top/Article/details/gtztihyyip.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj20258.top/Article/details/gtbxdhvgmr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.havefunace.top/Article/details/gtslynatjr.html

[L05] 上传文件（multipart）
来源：http://dali.ydzc1.top/Article/details/gtxtndzlkh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gaohongyu789.top/Article/details/gtnasoaavc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdtdrymum.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gzhubu.top/Article/details/gtbcueorie.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.redwolf501.top/Article/details/gtppxbcjcb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhoulong.xyz/Article/details/gtzgdhhycf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.c1oappe.top/Article/details/gtvpxefiiv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.haohaochexian.top/Article/details/gtyvapuhpp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtjprwrpcp.html

[L06] 解析响应为 JSON
来源：http://dali.yuxming.cn/Article/details/gtvptbjdiu.html

Py:   resp.json()
来源：http://dali.birdmap.top/Article/details/gtxhmqvxkx.html

PHP:  json_decode($body, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtexqrcyke.html

JS:   await resp.json()
来源：http://dali.andypj.xyz/Article/details/gttkrhgzep.html

TS:   await resp.json()
来源：http://dali.meibo888.top/Article/details/gtvrnukufd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.fzhhl.top/Article/details/gtotrwdtvf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hnxiangtu.top/Article/details/gtteylawcn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gaohongyu789.top/Article/details/gtnhlfknui.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shangyingyoupin.top/Article/details/gtlrytpknb.html

[L07] 处理 HTTP 状态码
来源：http://dali.svipenyu.cn/Article/details/gtlqiqunfv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.guannengcc.top/Article/details/gtacuunnmi.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenjidiqi.icu/Article/details/gtoowxzdrs.html

JS:   resp.ok;  resp.status
来源：http://dali.aibaodan.cn/Article/details/gtomvkktwk.html

TS:   resp.ok;  resp.status
来源：http://dali.daxiang520.top/Article/details/gtebugciwx.html

Java: resp.statusCode()
来源：http://dali.yuanzhike.top/Article/details/gtrsthmmou.html

Go:   resp.StatusCode
来源：http://dali.tian-w.cn/Article/details/gtijpvijvr.html

Ruby: resp.code.to_i
来源：http://dali.havefunace.top/Article/details/gtfvrpdlqn.html

C#:   (int)resp.StatusCode
来源：http://dali.dashuyun.cn/Article/details/gtruvfnqyr.html

[L08] 并发请求多个地址
来源：http://dali.jinqigfzy.top/Article/details/gtosqexhqw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.birdmap.top/Article/details/gtrmetmhqt.html

PHP:  curl_multi_init() 系列
来源：http://dali.bjfxy.top/Article/details/gtksxzudgc.html


<!-- 参考信息 -->