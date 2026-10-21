代发 wailian999

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shuidangran.top/Article/details/gtiremvsji.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yj20258.top/Article/details/gtycuxilzf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ppjwa.cn/Article/details/gtelksvpbf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gaohongyu789.top/Article/details/gtoiyvqcpp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.fzhhl.top/Article/details/gtfqyaghcd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sysykeji.top/Article/details/gtvptgryux.html

[I04] 正则替换
来源：http://dali.xziqi.cn/Article/details/gtbpmkklub.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtnaxzbyyd.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258.top/Article/details/gtmrtbtaha.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yueranfly.top/Article/details/gtaaorhmvi.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtddtfyhny.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sweek.top/Article/details/gtmnjvatis.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sweek.top/Article/details/gtezfnhpza.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yj20258888.top/Article/details/gtyhspoydn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.nanxinkj.top/Article/details/gtytrzeptk.html

[I05] 按正则拆分
来源：http://dali.pycfn.com/Article/details/gtoeschrck.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jlsjyb.cn/Article/details/gtgidrjqfe.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtphccfkzb.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yj202588.top/Article/details/gtjgabtaqu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hongshengwenyu.top/Article/details/gtmngfyudo.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sysykeji.top/Article/details/gtupehtnsy.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinqigufen.top/Article/details/gtajbdjttg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gtlgkwqdgk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.andypj.xyz/Article/details/gtcimsxoqr.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.pycfn.com/Article/details/gtbpluwbst.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.chenzaomai.com/Article/details/gtrfwshryh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ivvv.top/Article/details/gtsfjjywnh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhiwuduotai.top/Article/details/gtzszeaykv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pengpengdd.cyou/Article/details/gtxhhpzhki.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtktljfmal.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jiagoushi.top/Article/details/gtiagibofn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sufxvd.cn/Article/details/gtpxigiasa.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cashguo.top/Article/details/gtlvilfjdv.html

[I07] 忽略大小写与多行模式
来源：http://dali.xziqi.cn/Article/details/gtaccmqcje.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jyoumei.cn/Article/details/gtkxoiuhtb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenzaomai.com/Article/details/gtjhdupnow.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ehwqpu.com/Article/details/gtpgtxtkgz.html

TS:   /error/gim
来源：http://dali.zhongyouzk.top/Article/details/gtbhrhrtvg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yongpay.top/Article/details/gtqneqgana.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gaohongyu789.top/Article/details/gtjqpkihim.html

Ruby: s.scan(/error/i)
来源：http://dali.guannengcc.top/Article/details/gtxeywqbgs.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.316326.xyz/Article/details/gtlrflowfh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gogol.net.cn/Article/details/gtbxmryaho.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yj20258.top/Article/details/gtyaxrcbuf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zdqjudy.top/Article/details/gtlsmioehp.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jyoumei.cn/Article/details/gtzitrvbnw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.9152youxi.cn/Article/details/gtgolbxjnv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jlsjyb.cn/Article/details/gtdnumbyjb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.feifeiyinyue.top/Article/details/gtewomqjit.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gzhubu.top/Article/details/gtqtxszanw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shanyushiyangtech.top/Article/details/gtuqarzvcw.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtmdkrlzdo.html

J. 日期与时间
来源：http://dali.havefunace.top/Article/details/gtjmvfngyf.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtnoufhgyz.html

[J01] 获取当前时间
来源：http://dali.svipenyu.cn/Article/details/gtyijsqrfi.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cheryme.top/Article/details/gtuzrmjdkl.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hongshengwenyu.top/Article/details/gtqektqgcs.html

JS:   new Date();  Date.now()
来源：http://dali.yuanzhike.top/Article/details/gtkkjgorrp.html

TS:   new Date();  Date.now()
来源：http://dali.hammf.cn/Article/details/gtdpwmubwo.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yuxming.cn/Article/details/gtdxeolxmd.html

Go:   time.Now()
来源：http://dali.yanxiufei.cn/Article/details/gtwhmowokf.html

Ruby: Time.now
来源：http://dali.yanxiufei.cn/Article/details/gtxzvyopsq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cashguo.top/Article/details/gtiowefscr.html

[J02] 格式化输出
来源：http://dali.ydzc1.top/Article/details/gtbxzsmhah.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jiagoushi.top/Article/details/gtkievunkd.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gotoacloud.top/Article/details/gtafbjoatt.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yj202588.top/Article/details/gtqkjsdngy.html

TS:   d.toISOString()
来源：http://dali.zhiwuduotai.top/Article/details/gtsfmjoedg.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.haohaochexian.top/Article/details/gteutvgdac.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhongyouzk.top/Article/details/gtbunqvixj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shuidangran.top/Article/details/gtgxquwoiw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jianghu66.top/Article/details/gtpcvhkhuo.html

[J03] 字符串解析为日期
来源：http://dali.xylfe.cn/Article/details/gtthhdtzfp.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.9152youxi.cn/Article/details/gtwujcmora.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.vqdsnc.cn/Article/details/gttlsjymzk.html

JS:   new Date("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gtxdfecjle.html

TS:   new Date("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gtnqsqghba.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gtlhxvfcty.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtcmkicign.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gtvfspishx.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.feifeiyinyue.top/Article/details/gtllwhmnag.html

[J04] 时间戳与日期互转
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqlgfykvr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsafhtctg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gaohongyu789.top/Article/details/gtujjczovl.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinqigfzy.top/Article/details/gtlnybgsqd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yj20258.top/Article/details/gtineizkev.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tianlin.xyz/Article/details/gtddeziogg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jqgfzy.top/Article/details/gtrnfgmbbm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aizwys.cn/Article/details/gtbawyngjc.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.tianlin.xyz/Article/details/gtkovftpbv.html

[J05] 时间加减（加 7 天）
来源：http://dali.tanke756.top/Article/details/gtoincknag.html

Py:   now + timedelta(days=7)
来源：http://dali.guowangkeji.top/Article/details/gthejcaxxj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xuetiantiany.cn/Article/details/gttjdrhgcb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cashguo.top/Article/details/gttujgkitd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tanke756.top/Article/details/gtrpywvhgr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yuanzhike.top/Article/details/gthvvhcsbu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shzxlz.cn/Article/details/gtnwpywigf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gogol.net.cn/Article/details/gtnalpnqrs.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ybcxt.top/Article/details/gtzegjrcgw.html

[J06] 计算两时间之差
来源：http://dali.jlsjyb.cn/Article/details/gtsrwdkxyd.html

Py:   (end - start).total_seconds()
来源：http://dali.xylfe.cn/Article/details/gtawomuwty.html

PHP:  $end->diff($start)->days;
来源：http://dali.hnqzz.top/Article/details/gtadkpshlu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.guowangkeji.top/Article/details/gtgvrvrdcj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.meibo888.top/Article/details/gtwusfgdjn.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ehwqpu.com/Article/details/gttlcknbpt.html

Go:   end.Sub(start).Hours()
来源：http://dali.gogol.net.cn/Article/details/gtsuhvayjl.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cqqwz.cn/Article/details/gticfuedyc.html

C#:   (end - start).TotalSeconds
来源：http://dali.yongpay.top/Article/details/gtanywubqc.html

[J07] 比较两个日期
来源：http://dali.feifeiyinyue.top/Article/details/gtgtwqlehr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.meibo888.top/Article/details/gtldzwpfnp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.snrcjt.cn/Article/details/gtvvmtdhpb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigufen.top/Article/details/gtkoufutoa.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.wangdashe.top/Article/details/gtzfnjjhal.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xylfe.cn/Article/details/gtqjwmlens.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.tanke756.top/Article/details/gtlyirbnen.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gtkaaubipd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinqigufen.top/Article/details/gtweuvsqto.html

[J08] 提取年月日与星期
来源：http://dali.shangyingyoupin.top/Article/details/gthgjbkbpa.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.9152youxi.cn/Article/details/gtfmhctxav.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gogol.net.cn/Article/details/gtousuyphs.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj20258888.top/Article/details/gtjiugzpnh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hongshengwenyu.top/Article/details/gtvchyybvy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.redwolf501.top/Article/details/gtugciudmj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.dianchejie.cn/Article/details/gtiuwmzgbp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gaohongyu789.top/Article/details/gtlqgkvcpv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cucudq.cn/Article/details/gtokchkowf.html

[J09] 时区处理
来源：http://dali.xylfe.cn/Article/details/gtfewnkupz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.snrcjt.cn/Article/details/gtxhrimhpw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.haohaochexian.top/Article/details/gtxroqjezu.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.redwolf501.top/Article/details/gtjhqefpld.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guowangkeji.top/Article/details/gttfqugtds.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cqqwz.cn/Article/details/gtoaeermpy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hywenlv.cn/Article/details/gtuwnyleqz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.pengpengdd.cyou/Article/details/gtesxceyaz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.c1oappe.top/Article/details/gtejxuxqxh.html

[J10] 取今天 / 本月第一天
来源：http://dali.shzxlz.cn/Article/details/gtzlqynple.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jqgfzy.top/Article/details/gtynuzfpsw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.pycfn.com/Article/details/gtkxkzivgq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sysykeji.top/Article/details/gtptunlyex.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jyoumei.cn/Article/details/gtbgfynyws.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.wangdashe.top/Article/details/gtsijjsmtj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.tianlin.xyz/Article/details/gtiujotdtl.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cashguo.top/Article/details/gtsdslljws.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.dashuyun.cn/Article/details/gtcjsxbsar.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtthuxgsrs.html

K. JSON 与序列化
来源：http://dali.snrcjt.cn/Article/details/gtxakqkdta.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtngccvrbr.html

[K01] 对象转 JSON 字符串
来源：http://dali.cucudq.cn/Article/details/gtehwvtets.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.birdmap.top/Article/details/gtumfyppha.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.guowangkeji.top/Article/details/gtakrfelam.html

JS:   JSON.stringify(obj)
来源：http://dali.yj20258.top/Article/details/gtofuwumdi.html

TS:   JSON.stringify(obj)
来源：http://dali.guannengcc.top/Article/details/gtolcpkodi.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.nanxuanxn.top/Article/details/gtbsqddnol.html

Go:   json.Marshal(obj)
来源：http://dali.zhixingplan.top/Article/details/gtgpbtjbip.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.wangshuangyany.cn/Article/details/gtkfgngyoq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.nwbrower.top/Article/details/gtvbtzsiqd.html

[K02] JSON 字符串转对象
来源：http://dali.cucudq.cn/Article/details/gtyeynrxkt.html

Py:   json.loads(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtahhpkuwr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.mhx1999.top/Article/details/gtlzldvrkp.html

JS:   JSON.parse(s)
来源：http://dali.xziqi.cn/Article/details/gtvdprktlq.html

TS:   JSON.parse(s)
来源：http://dali.jyoumei.cn/Article/details/gtjoaujhus.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ydzc1.top/Article/details/gtwypqxdou.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.tianlin.xyz/Article/details/gtgkmwfspe.html

Ruby: JSON.parse(s)
来源：http://dali.hnqzz.top/Article/details/gtbqqpdqpn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.birdmap.top/Article/details/gtwfkqpijp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.nanxinkj.top/Article/details/gtncszhtcx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cheryme.top/Article/details/gtsiyfkmiu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.vqdsnc.cn/Article/details/gtkmnubiyi.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyovzxmze.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxinkj.top/Article/details/gtfywzazum.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj20258.top/Article/details/gtjfcwiuag.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.feifeiyinyue.top/Article/details/gtwzooxduk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jqgfzy.top/Article/details/gtjalggxio.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sysykeji.top/Article/details/gtbdommwip.html

[K04] 读取 JSON 文件
来源：http://dali.jqgfzy.top/Article/details/gtpwgowsfy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hongshengwenyu.top/Article/details/gtslqzcdbj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shangyingyoupin.top/Article/details/gtcrbjwyoo.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.redwolf501.top/Article/details/gttbtcbpur.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yangfankeji.com/Article/details/gthbaavulk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gtufwehhzt.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.havefunace.top/Article/details/gtmlopwqnq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jqgufenzy.top/Article/details/gtynvpessj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.tanke756.top/Article/details/gtmnaxolcs.html

[K05] 深拷贝对象
来源：http://dali.jinqigfzy.top/Article/details/gttvnuwdht.html

Py:   copy.deepcopy(obj)
来源：http://dali.jqgfzy.top/Article/details/gtaruzjhgh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xuanzx.com/Article/details/gtzctqfppf.html

JS:   structuredClone(obj)
来源：http://dali.sweek.top/Article/details/gtfawpdffs.html

TS:   structuredClone(obj)
来源：http://dali.yvedp.cn/Article/details/gtnzsrzczr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hfpthk.cn/Article/details/gtahfaoxno.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ydzc1.top/Article/details/gtexuwmeks.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jyoumei.cn/Article/details/gtwjgqfnuy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.chenzaomai.com/Article/details/gtseuzrnyj.html

[K06] 解析 URL 查询串
来源：http://dali.zdqjudy.top/Article/details/gthsrjxqkg.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yuxming.cn/Article/details/gtjwgzokrd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtehokohgv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.meibo888.top/Article/details/gtllxnbxbu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sysykeji.top/Article/details/gtmwekrhxe.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jiagoushi.top/Article/details/gtpfqyfosp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtixfdgnrh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.dashuyun.cn/Article/details/gttfdbjuns.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gteokparkl.html

[K07] 进制转换
来源：http://dali.vqdsnc.cn/Article/details/gtnrqpjkpb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cheryme.top/Article/details/gtgxbdgkvb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shangyingyoupin.top/Article/details/gtutoogqtg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gtxgfczfro.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtoyiabora.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtkjwogocr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmxbalfs.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shzxlz.cn/Article/details/gtwwojaagx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.pycfn.com/Article/details/gtgzeayzrv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xuetiantiany.cn/Article/details/gturhyrvxg.html

Py:   pickle.dumps(obj)
来源：http://dali.svipenyu.cn/Article/details/gtdhdgrywb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hnxiangtu.top/Article/details/gtxdvzgiyd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xuanzx.com/Article/details/gtgepqmxst.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cashguo.top/Article/details/gtjwicavpm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shangyingyoupin.top/Article/details/gtxcydnhph.html

Go:   encoding/gob
来源：http://dali.ppjwa.cn/Article/details/gtdacawatp.html

Ruby: Marshal.dump(obj)
来源：http://dali.gzhubu.top/Article/details/gtdrhplbrs.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shzxlz.cn/Article/details/gtmwlqlmvs.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpvvnzjbn.html

L. 网络请求
来源：http://dali.shanyushiyangtech.top/Article/details/gtrxsabvxs.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtebnwobix.html

[L01] 发送 GET 请求
来源：http://dali.sweek.top/Article/details/gtveknymob.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.daria6918.cn/Article/details/gtwuglpfnp.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jiagoushi.top/Article/details/gtvbpyibhn.html

JS:   await fetch(url)
来源：http://dali.yj202588.top/Article/details/gtwonknick.html

TS:   await fetch(url)
来源：http://dali.svipenyu.cn/Article/details/gtuqelsvtz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xziqi.cn/Article/details/gtxxxeuglh.html

Go:   resp, err := http.Get(url)
来源：http://dali.yongpay.top/Article/details/gtovqzehuv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gaohongyu789.top/Article/details/gtwsqtgisu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxgjhkbtx.html

[L02] 发送 POST JSON
来源：http://dali.nanxuanxn.top/Article/details/gtamvezaqs.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jyoumei.cn/Article/details/gtsmojsxts.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.bjfxy.top/Article/details/gtghjtxycs.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guannengcc.top/Article/details/gtcytfzgzk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sysykeji.top/Article/details/gtxhcstyzx.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hnxiangtu.top/Article/details/gtttjmjmbe.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.fzhhl.top/Article/details/gtybjnxbkr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoteqlcnm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.nanxinkj.top/Article/details/gtjlvhutlk.html

[L03] 设置自定义请求头
来源：http://dali.hnqzz.top/Article/details/gtqvnvmklh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.fzhhl.top/Article/details/gtpkniddtv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.0kj1m.cn/Article/details/gtxmttcoou.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuanzx.com/Article/details/gtpjuqsoeb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cashguo.top/Article/details/gtrlmbwkoc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.aibaodan.cn/Article/details/gtwztyqfhz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ydzc1.top/Article/details/gthqwneyhs.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nwbrower.top/Article/details/gtbvggfwnw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinghuilouyu.cn/Article/details/gtccbuluca.html

[L04] 设置超时
来源：http://dali.gogol.net.cn/Article/details/gtqcctqqfu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cheryme.top/Article/details/gtghybxqvn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cqqwz.cn/Article/details/gtggnaqkzw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigfzy.top/Article/details/gtscameyao.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.mhx1999.top/Article/details/gtqhescfth.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cqqwz.cn/Article/details/gtpmjexnhi.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sufxvd.cn/Article/details/gtwygujxie.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nanxinkj.top/Article/details/gtlqtpvijz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jyoumei.cn/Article/details/gtmdrxykyr.html

[L05] 上传文件（multipart）
来源：http://dali.andypj.xyz/Article/details/gtbmqvibsr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinqigufen.top/Article/details/gtymaubnbb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sufxvd.cn/Article/details/gtnbudebyu.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.svipenyu.cn/Article/details/gtzqrevrlo.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jianghu66.top/Article/details/gtipcodgkp.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.daria6918.cn/Article/details/gtxvpnutws.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.havefunace.top/Article/details/gtfknahauw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jianghu66.top/Article/details/gtkxjqzcsj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrfbozbvp.html

[L06] 解析响应为 JSON
来源：http://dali.jianghu66.top/Article/details/gtlxvdvtdx.html

Py:   resp.json()
来源：http://dali.jqgfzy.top/Article/details/gtzocnicjd.html

PHP:  json_decode($body, true);
来源：http://dali.andypj.xyz/Article/details/gtckgqlsui.html

JS:   await resp.json()
来源：http://dali.chenjidiqi.icu/Article/details/gtnbjxhefo.html

TS:   await resp.json()
来源：http://dali.tianlin.xyz/Article/details/gtkzjtdytl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sufxvd.cn/Article/details/gthaibmbdp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.snrcjt.cn/Article/details/gtsevumsmn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yangfankeji.com/Article/details/gtyppxlozf.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cashguo.top/Article/details/gteykyhfbw.html

[L07] 处理 HTTP 状态码
来源：http://dali.xylfe.cn/Article/details/gtiujnlobi.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.feifeiyinyue.top/Article/details/gtofvqwgqv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.tanke756.top/Article/details/gtbyyrmbqu.html

JS:   resp.ok;  resp.status
来源：http://dali.zhengqikj.top/Article/details/gtuzddcvdz.html

TS:   resp.ok;  resp.status
来源：http://dali.yonumen.top/Article/details/gtnhpjdife.html

Java: resp.statusCode()
来源：http://dali.mhx1999.top/Article/details/gtwzsxgyhl.html

Go:   resp.StatusCode
来源：http://dali.jiagoushi.top/Article/details/gtsogyepss.html

Ruby: resp.code.to_i
来源：http://dali.xuanzx.com/Article/details/gtphwwnchq.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gtchbyxups.html

[L08] 并发请求多个地址
来源：http://dali.yueranfly.top/Article/details/gtbyqxfuhl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nwbrower.top/Article/details/gtxfnuotrz.html

PHP:  curl_multi_init() 系列
来源：http://dali.andypj.xyz/Article/details/gtmxqhkwhr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cdnleiting.top/Article/details/gtbmxalnvl.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuxming.cn/Article/details/gtfxmpycsi.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.0kj1m.cn/Article/details/gthzkvvqrd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.svipenyu.cn/Article/details/gtjjrtaycp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdatzpdpl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.aizwys.cn/Article/details/gtynfcdxll.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtnlsmnjsx.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhongyouzk.top/Article/details/gtfycoocmp.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtwopgsxzx.html

[M01] 读取命令行参数
来源：http://dali.yj20258.top/Article/details/gtsffcgdog.html

Py:   sys.argv[1:]
来源：http://dali.meibo888.top/Article/details/gtxasoiqzh.html

PHP:  $argv;  $argc;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxmmreaku.html


<!-- 参考信息 -->