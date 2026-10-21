代发 wailian999

[I02] 提取所有匹配
来源：http://dali.sxryk.cn/Article/details/gtisujzhqd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yj20258888.top/Article/details/gtdhxuslzp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.redwolf501.top/Article/details/gtzkkggldh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ppjwa.cn/Article/details/gtlqcuxisv.html

TS:   s.match(/\d+/g)
来源：http://dali.9152youxi.cn/Article/details/gtoizgajay.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hysaishi.cn/Article/details/gtwmizfpzr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sxryk.cn/Article/details/gthcqhansg.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinqigfzy.top/Article/details/gtojgpdroa.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtksebmjiw.html

[I03] 提取捕获分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzteuawwr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.dashuyun.cn/Article/details/gtsvydnqgf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gtpuytavoh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yuanzhike.top/Article/details/gtuotsjagz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yj202588.top/Article/details/gtghnidils.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xylfe.cn/Article/details/gtlnhfjffd.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tian-w.cn/Article/details/gtmvsztfyf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yj20258888.top/Article/details/gtmriidaxz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gotoacloud.top/Article/details/gtisqyaosv.html

[I04] 正则替换
来源：http://dali.nwbrower.top/Article/details/gtjuohdpin.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.fengsongda.top/Article/details/gtnltkljov.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.iojbl.cn/Article/details/gtyfomstvd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenzaomai.com/Article/details/gtphnoogkc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.wangdashe.top/Article/details/gtvpjuativ.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.bjfxy.top/Article/details/gtwvakluno.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gaohongyu789.top/Article/details/gtigacoygq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yj20258888.top/Article/details/gttmridsvf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.iojbl.cn/Article/details/gtjxyqezci.html

[I05] 按正则拆分
来源：http://dali.chenlongwang.top/Article/details/gtoyehtedw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.svipenyu.cn/Article/details/gtgyqurzcc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zycfv.cn/Article/details/gtvucevwin.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gtdnmpadcn.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xziqi.cn/Article/details/gtyikwdehw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jianghu66.top/Article/details/gtitgxnapl.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.svipenyu.cn/Article/details/gtogcqeulc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.wangshuangyany.cn/Article/details/gtkcavkskk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tianlin.xyz/Article/details/gttvvlncry.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.nwbrower.top/Article/details/gtufvwbccn.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.0kj1m.cn/Article/details/gtzfyacxbl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.wangshuangyany.cn/Article/details/gtcfkhytei.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daxiang520.top/Article/details/gtxielmwxd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.0kj1m.cn/Article/details/gtjwirjlbo.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.fzhhl.top/Article/details/gtvyipdthh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ywan-chungtsiang.top/Article/details/gtafxpthqw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.haohaochexian.top/Article/details/gtcribbhhq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jianghu66.top/Article/details/gtmctszgca.html

[I07] 忽略大小写与多行模式
来源：http://dali.wangdashe.top/Article/details/gtveerfnhj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jianghu66.top/Article/details/gtynrcdahn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yuanzhike.top/Article/details/gtylavvsky.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.pengpengdd.cyou/Article/details/gtjqpwhegb.html

TS:   /error/gim
来源：http://dali.hnxiangtu.top/Article/details/gtisyfwcmd.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jqgufenzy.top/Article/details/gtmrhdisfs.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xziqi.cn/Article/details/gtywidljzu.html

Ruby: s.scan(/error/i)
来源：http://dali.xziqi.cn/Article/details/gthasvtugy.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yanxiufei.cn/Article/details/gtzhvcqrty.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhixingplan.top/Article/details/gtyywnvgot.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinqigfzy.top/Article/details/gtvewiwiaq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.andypj.xyz/Article/details/gtcoyvqhkm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cqqwz.cn/Article/details/gtlwkxrxsz.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jiagoushi.top/Article/details/gtdmiulrjr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfikjauzz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhongyouzk.top/Article/details/gtzgqmmjoc.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.0kj1m.cn/Article/details/gtboubbbar.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shangyingyoupin.top/Article/details/gtxxzovclv.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gthqzibivm.html

J. 日期与时间
来源：http://dali.jqgfzy.top/Article/details/gtztbwlxgo.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtqunttfal.html

[J01] 获取当前时间
来源：http://dali.tian-w.cn/Article/details/gtlxfnrmrg.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.chenlongwang.top/Article/details/gtzanjfddf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.0kj1m.cn/Article/details/gtvoxeoagu.html

JS:   new Date();  Date.now()
来源：http://dali.guannengcc.top/Article/details/gtiiwszmcp.html

TS:   new Date();  Date.now()
来源：http://dali.xinyue.icu/Article/details/gtgsxypqfy.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenlongwang.top/Article/details/gtxvymyukz.html

Go:   time.Now()
来源：http://dali.9152youxi.cn/Article/details/gtohmjhnnb.html

Ruby: Time.now
来源：http://dali.sysykeji.top/Article/details/gtgxzfswpb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nanxuanxn.top/Article/details/gtmrkuekhr.html

[J02] 格式化输出
来源：http://dali.shzxlz.cn/Article/details/gtyscmkkdr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuanzhike.top/Article/details/gtdpjqdmun.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gzhubu.top/Article/details/gtcuedeius.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hysaishi.cn/Article/details/gtypzxpmbe.html

TS:   d.toISOString()
来源：http://dali.xuetiantiany.cn/Article/details/gtmalzcetd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ydzc1.top/Article/details/gtngdxnhlo.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hnqzz.top/Article/details/gtqkagsnku.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zycfv.cn/Article/details/gtbtxwsete.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jqgfzy.top/Article/details/gtrlxbtkql.html

[J03] 字符串解析为日期
来源：http://dali.jlsjyb.cn/Article/details/gtkmekmbzc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.mhx1999.top/Article/details/gtafkrnyro.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.aizwys.cn/Article/details/gtkuwhexjv.html

JS:   new Date("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtwanzovyl.html

TS:   new Date("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gtvhndzjqx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gtsuelahch.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gtpfsbeoty.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gtejfwwblp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zycfv.cn/Article/details/gtlinnsaxh.html

[J04] 时间戳与日期互转
来源：http://dali.quarkkingdee.top/Article/details/gtgnpddprj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gtqvhiudoc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sysykeji.top/Article/details/gtvzuxigcg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.guannengcc.top/Article/details/gtcbedtafx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjyrecyuw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.guannengcc.top/Article/details/gtzaxnuzni.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shzxlz.cn/Article/details/gtqnszysht.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.c1oappe.top/Article/details/gtxpeoofcw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.fengsongda.top/Article/details/gtzkberyye.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcbkbnruc.html

Py:   now + timedelta(days=7)
来源：http://dali.zdqjudy.top/Article/details/gtcgndiyvv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xinyue.icu/Article/details/gtgcnvxoiu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj202588.top/Article/details/gtkezmhjmc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shuidangran.top/Article/details/gtrnqdmial.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhiwuduotai.top/Article/details/gtaqgbhoml.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nwbrower.top/Article/details/gtwtksqsdp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jianghu66.top/Article/details/gtngccrjwh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.iojbl.cn/Article/details/gtuyyroccc.html

[J06] 计算两时间之差
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoejktihv.html

Py:   (end - start).total_seconds()
来源：http://dali.nanxinkj.top/Article/details/gtoondqjyo.html

PHP:  $end->diff($start)->days;
来源：http://dali.ehwqpu.com/Article/details/gttgpjhabi.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.fengsongda.top/Article/details/gtwtpeqopp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shuidangran.top/Article/details/gtljkagtyu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhongyouzk.top/Article/details/gtngettbnr.html

Go:   end.Sub(start).Hours()
来源：http://dali.chenzaomai.com/Article/details/gtbfznkrbn.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ydzc1.top/Article/details/gtcbifdtyf.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj20258.top/Article/details/gtqlsrvxps.html

[J07] 比较两个日期
来源：http://dali.chenlongwang.top/Article/details/gtjubkgamc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gtqtrlkctf.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhoulong.xyz/Article/details/gtylmkprqh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gtqurwhgzv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shuidangran.top/Article/details/gtexgzosfm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ivvv.top/Article/details/gtwwaxfmmb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.iojbl.cn/Article/details/gtrfwfecpb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gogol.net.cn/Article/details/gtblhoniff.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gtbknvuvtu.html

[J08] 提取年月日与星期
来源：http://dali.nwbrower.top/Article/details/gtcmcwvyxx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jiagoushi.top/Article/details/gtyiqbyqpj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.feifeiyinyue.top/Article/details/gttcdlbick.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.wangdashe.top/Article/details/gtqidmbycz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.chenjidiqi.icu/Article/details/gtcdsepseh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sysykeji.top/Article/details/gtnndfzzat.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenzaomai.com/Article/details/gtgsznqpqj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jyoumei.cn/Article/details/gtbqhetksi.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gaohongyu789.top/Article/details/gtjtwrvsel.html

[J09] 时区处理
来源：http://dali.zhiwuduotai.top/Article/details/gtkfvwckil.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jlsjyb.cn/Article/details/gtfalfenki.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.iojbl.cn/Article/details/gtrcmtdfnt.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.mhx1999.top/Article/details/gtplpuybjr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zdqjudy.top/Article/details/gtyfhpawjx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sufxvd.cn/Article/details/gtdqblmpbs.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.dianchejie.cn/Article/details/gtrzztaiul.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jiagoushi.top/Article/details/gtevyeznro.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.pengpengdd.cyou/Article/details/gtqnoenyct.html

[J10] 取今天 / 本月第一天
来源：http://dali.iojbl.cn/Article/details/gtpotkspen.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ydzc1.top/Article/details/gtqeqgtmnt.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.kuanghao11.cn/Article/details/gtembxujvm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tanke756.top/Article/details/gtnpjefaow.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.aizwys.cn/Article/details/gtewzlfidu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.andypj.xyz/Article/details/gtkipqimpb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.bjfxy.top/Article/details/gtqedykumz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tian-w.cn/Article/details/gtstbdoeaw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ydzc1.top/Article/details/gtuyefsgst.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtgbrfhhmd.html

K. JSON 与序列化
来源：http://dali.daxiang520.top/Article/details/gthrueanvz.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtqolwnoxw.html

[K01] 对象转 JSON 字符串
来源：http://dali.sxryk.cn/Article/details/gtpltzwwyw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yueranfly.top/Article/details/gtgomgdlyo.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ybcxt.top/Article/details/gtgzeakvjw.html

JS:   JSON.stringify(obj)
来源：http://dali.havefunace.top/Article/details/gtkedhmttn.html

TS:   JSON.stringify(obj)
来源：http://dali.316326.xyz/Article/details/gtwjcjsnch.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhiwuduotai.top/Article/details/gtydyovtws.html

Go:   json.Marshal(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtacxmfmbg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinqigfzy.top/Article/details/gtvnnqtxda.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.dianchejie.cn/Article/details/gtdtbofkbt.html

[K02] JSON 字符串转对象
来源：http://dali.jinqigfzy.top/Article/details/gteurdlprj.html

Py:   json.loads(s)
来源：http://dali.xuanzx.com/Article/details/gtqojdkcve.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.redwolf501.top/Article/details/gtflpuggim.html

JS:   JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gttwxyfjwg.html

TS:   JSON.parse(s)
来源：http://dali.ivvv.top/Article/details/gtvjdvnthn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.fengsongda.top/Article/details/gtqvwcviti.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.daxiang520.top/Article/details/gtdpozovdg.html

Ruby: JSON.parse(s)
来源：http://dali.zdqjudy.top/Article/details/gtpldyndcx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.fzhhl.top/Article/details/gtnprjcdir.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shuidangran.top/Article/details/gtqfjdbcrw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.feifeiyinyue.top/Article/details/gtfkwtbtkw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hysaishi.cn/Article/details/gtpracunov.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.quarkkingdee.top/Article/details/gtazbzcatg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtajskzvup.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.smart0.xyz/Article/details/gtunlozxhy.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yuanzhike.top/Article/details/gthupskopv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cashguo.top/Article/details/gthjrepujp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhengqikj.top/Article/details/gtyxmgyflj.html

[K04] 读取 JSON 文件
来源：http://dali.9152youxi.cn/Article/details/gtdqcjwwgy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ppjwa.cn/Article/details/gtvjmuiqiu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj202588.top/Article/details/gtwwypnhjl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.iojbl.cn/Article/details/gtxgdlmjxs.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenlongwang.top/Article/details/gtqadrnliv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yonumen.top/Article/details/gtpdtcvxuy.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhiwuduotai.top/Article/details/gtvlusgzkq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cdnleiting.top/Article/details/gtksgrvtrs.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cucudq.cn/Article/details/gtgwekpdas.html

[K05] 深拷贝对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gtikwzklqo.html

Py:   copy.deepcopy(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtqdhyoqpz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cheryme.top/Article/details/gtwswbwxcc.html

JS:   structuredClone(obj)
来源：http://dali.sysykeji.top/Article/details/gtnjkhtdyw.html

TS:   structuredClone(obj)
来源：http://dali.sysykeji.top/Article/details/gtdfybmakq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sufxvd.cn/Article/details/gtthcyjjdj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gtkofnjazh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nwbrower.top/Article/details/gtggeiezos.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hywenlv.cn/Article/details/gtoebzfdhy.html

[K06] 解析 URL 查询串
来源：http://dali.chenlongwang.top/Article/details/gtnzgbvwyp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinghuilouyu.cn/Article/details/gtsnwlllgt.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cdnleiting.top/Article/details/gtzfmnlmze.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pycfn.com/Article/details/gtqafghgyn.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.andypj.xyz/Article/details/gtmcwhoqht.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yuanzhike.top/Article/details/gtnoaqzegl.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jqgfzy.top/Article/details/gthhhmxran.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gtldbkpsuo.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhongyouzk.top/Article/details/gtfaydlfug.html

[K07] 进制转换
来源：http://dali.nanxuanxn.top/Article/details/gtltwyuolv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gtxilfxoyn.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hysaishi.cn/Article/details/gtsjsvdnjd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gtpmaufygg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcfpdywvi.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gtzxpmbngh.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhongyouzk.top/Article/details/gtkonqxrmf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenjidiqi.icu/Article/details/gtvxergkpl.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtynofymih.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yj20258888.top/Article/details/gtjhmetlur.html

Py:   pickle.dumps(obj)
来源：http://dali.ivvv.top/Article/details/gtepmrpltz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zycfv.cn/Article/details/gtfccemtrp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hongshengwenyu.top/Article/details/gtazhsnywk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbxwrrayr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.snrcjt.cn/Article/details/gtukawmkzf.html

Go:   encoding/gob
来源：http://dali.ehwqpu.com/Article/details/gtdyztoeuf.html

Ruby: Marshal.dump(obj)
来源：http://dali.c1oappe.top/Article/details/gtifistiqj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.wangdashe.top/Article/details/gttorepnnj.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtaelmuehw.html

L. 网络请求
来源：http://dali.wangshuangyany.cn/Article/details/gtishmugne.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtjafzeass.html

[L01] 发送 GET 请求
来源：http://dali.sufxvd.cn/Article/details/gtrvplfqsi.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.feifeiyinyue.top/Article/details/gteijmqdac.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sysykeji.top/Article/details/gtbzxchhht.html

JS:   await fetch(url)
来源：http://dali.smart0.xyz/Article/details/gtonsnjejq.html

TS:   await fetch(url)
来源：http://dali.hfpthk.cn/Article/details/gtkpvtvhyf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.haohaochexian.top/Article/details/gtyllsikzv.html

Go:   resp, err := http.Get(url)
来源：http://dali.0kj1m.cn/Article/details/gtstwwvubg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sxryk.cn/Article/details/gtbfitzfgq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xylfe.cn/Article/details/gtweuejyxg.html

[L02] 发送 POST JSON
来源：http://dali.c1oappe.top/Article/details/gtduacsifk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhoulong.xyz/Article/details/gtgqbyvkxq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.nanxuanxn.top/Article/details/gtoqracbab.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zycfv.cn/Article/details/gtigunyjnu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.redwolf501.top/Article/details/gtfkplzqcl.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhiwuduotai.top/Article/details/gtwxariocf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhixingplan.top/Article/details/gtcysqnhdk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.chenjidiqi.icu/Article/details/gtkoywzdlt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yueranfly.top/Article/details/gttfbjmids.html

[L03] 设置自定义请求头
来源：http://dali.tian-w.cn/Article/details/gtzfcnlhtf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yvedp.cn/Article/details/gtjmdrqfzc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yuxming.cn/Article/details/gtlxluwrxf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangshuangyany.cn/Article/details/gtwnuzryco.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigufen.top/Article/details/gtpwrbxxqe.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hongshengwenyu.top/Article/details/gtcubynlgc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.andypj.xyz/Article/details/gtftpmgies.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xziqi.cn/Article/details/gtkoawkult.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jianghu66.top/Article/details/gttdqibown.html

[L04] 设置超时
来源：http://dali.gotoacloud.top/Article/details/gtltimflhi.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tanke756.top/Article/details/gtabdnpmgo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yongpay.top/Article/details/gtbhmcyjcn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.c1oappe.top/Article/details/gtfkibcepv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258.top/Article/details/gtmfppuaiw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xylfe.cn/Article/details/gtovdcjuae.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.meibo888.top/Article/details/gtfyzzyhwl.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinqigfzy.top/Article/details/gtnaonscjr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.guowangkeji.top/Article/details/gtmfcquvvv.html

[L05] 上传文件（multipart）
来源：http://dali.yueranfly.top/Article/details/gtikhynzdn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.fengsongda.top/Article/details/gtxbzwluhj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xinyue.icu/Article/details/gtytbnjcyh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgufenzy.top/Article/details/gtnlpjogou.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuxming.cn/Article/details/gtppumxbej.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hysaishi.cn/Article/details/gtjfvpvhbd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hywenlv.cn/Article/details/gtidfhjpbw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.vqdsnc.cn/Article/details/gtoovhwayl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtkrsozrll.html

[L06] 解析响应为 JSON
来源：http://dali.zdqjudy.top/Article/details/gtvnedcale.html

Py:   resp.json()
来源：http://dali.dianchejie.cn/Article/details/gtwyunhzur.html

PHP:  json_decode($body, true);
来源：http://dali.dashuyun.cn/Article/details/gtcazcylia.html

JS:   await resp.json()
来源：http://dali.yonumen.top/Article/details/gtafmggiqe.html

TS:   await resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gtaskiwrkb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.nanxinkj.top/Article/details/gtrwkiipqk.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sysykeji.top/Article/details/gtebmnrvil.html

Ruby: JSON.parse(resp.body)
来源：http://dali.daxiang520.top/Article/details/gtfnuloeeq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shuidangran.top/Article/details/gtfupqxjgt.html

[L07] 处理 HTTP 状态码
来源：http://dali.andypj.xyz/Article/details/gtnugebimh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.c1oappe.top/Article/details/gtvbqskhsa.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yj20258888.top/Article/details/gtbxypapsl.html

JS:   resp.ok;  resp.status
来源：http://dali.shzxlz.cn/Article/details/gtefjbbrlh.html

TS:   resp.ok;  resp.status
来源：http://dali.jqgfzy.top/Article/details/gtqnnijqkv.html

Java: resp.statusCode()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrrspqgmo.html

Go:   resp.StatusCode
来源：http://dali.hywenlv.cn/Article/details/gtgttcffhh.html

Ruby: resp.code.to_i
来源：http://dali.shangyingyoupin.top/Article/details/gtbpnwdkrn.html

C#:   (int)resp.StatusCode
来源：http://dali.0kj1m.cn/Article/details/gtugquuinh.html

[L08] 并发请求多个地址
来源：http://dali.cashguo.top/Article/details/gteotquakx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.0kj1m.cn/Article/details/gtagaiwurl.html

PHP:  curl_multi_init() 系列
来源：http://dali.fengsongda.top/Article/details/gtckxtflrw.html


<!-- 参考信息 -->