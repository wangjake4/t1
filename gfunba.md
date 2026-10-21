代发 wailian999

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj202588.top/Article/details/gtwggegsdx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ppjwa.cn/Article/details/gtvziwzopu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.316326.xyz/Article/details/gttsynnouk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ivvv.top/Article/details/gtgwugqqkv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.andypj.xyz/Article/details/gtpldbdvnp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yj20258888.top/Article/details/gtftwwipnq.html

[I04] 正则替换
来源：http://dali.nwbrower.top/Article/details/gtctbjpxst.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hysaishi.cn/Article/details/gtyegvluic.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gogol.net.cn/Article/details/gtethkycee.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.tianlin.xyz/Article/details/gtlypdqrqv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.0kj1m.cn/Article/details/gtqmksstve.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sysykeji.top/Article/details/gtmuhqhbyj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.guowangkeji.top/Article/details/gtadxsnzem.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtybsgxjsl.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.guowangkeji.top/Article/details/gtadiuqftp.html

[I05] 按正则拆分
来源：http://dali.jiagoushi.top/Article/details/gtjwjnrqnn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.tian-w.cn/Article/details/gtjmedwghl.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gogol.net.cn/Article/details/gtbbezqjjw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xuanzx.com/Article/details/gtgujvzaao.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gaohongyu789.top/Article/details/gthvocnrqi.html

Java: s.split("\\s*,\\s*")
来源：http://dali.c1oappe.top/Article/details/gtqdzuxqkr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jyoumei.cn/Article/details/gtlrnkgcuz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gtxtznldlp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tanke756.top/Article/details/gtjbvrcbov.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.iojbl.cn/Article/details/gticjuahwl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhongyouzk.top/Article/details/gtzxejziwt.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.dianchejie.cn/Article/details/gtlrnbabvb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhengqikj.top/Article/details/gtsugkrfgh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yvedp.cn/Article/details/gtdnrucmdh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinqigfzy.top/Article/details/gtdrfxiqbn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.pengpengdd.cyou/Article/details/gtqkawwznk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjsmehvzn.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gtzccyjvmq.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenzaomai.com/Article/details/gtzfiflwgl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sysykeji.top/Article/details/gtepjffqoh.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sxryk.cn/Article/details/gteamsnits.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ybcxt.top/Article/details/gtgpohmtba.html

TS:   /error/gim
来源：http://dali.aibaodan.cn/Article/details/gtqnkpazgu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gtkykvqwbj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthxnjrgyc.html

Ruby: s.scan(/error/i)
来源：http://dali.meibo888.top/Article/details/gtwwceethn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.aizwys.cn/Article/details/gtsjcqejsy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shuidangran.top/Article/details/gtfyponxnk.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.fengsongda.top/Article/details/gtoszdoqbd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shanyushiyangtech.top/Article/details/gtztlpphht.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenzaomai.com/Article/details/gtnqbltpqe.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aibaodan.cn/Article/details/gtjmbmzyuc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hnqzz.top/Article/details/gtmxvjmghx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cashguo.top/Article/details/gthfiowaez.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ydzc1.top/Article/details/gtydbfccgq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.havefunace.top/Article/details/gthuspbhzp.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtiotcjwsx.html

J. 日期与时间
来源：http://dali.daria6918.cn/Article/details/gtrifxgsam.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtthsnwbfh.html

[J01] 获取当前时间
来源：http://dali.shzxlz.cn/Article/details/gtuyctczwh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.fengsongda.top/Article/details/gtldvohhoq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqfexmzqe.html

JS:   new Date();  Date.now()
来源：http://dali.guowangkeji.top/Article/details/gtfoklomqn.html

TS:   new Date();  Date.now()
来源：http://dali.xinyue.icu/Article/details/gtzzojoybq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hywenlv.cn/Article/details/gtuyeqctsd.html

Go:   time.Now()
来源：http://dali.zycfv.cn/Article/details/gtanljtgbi.html

Ruby: Time.now
来源：http://dali.gogol.net.cn/Article/details/gtdypftuph.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cdnleiting.top/Article/details/gtdpqxdbws.html

[J02] 格式化输出
来源：http://dali.fengsongda.top/Article/details/gtdubanmva.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.snrcjt.cn/Article/details/gthjjxuujt.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.andypj.xyz/Article/details/gtdxcdvxpl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cdnleiting.top/Article/details/gtabevuhto.html

TS:   d.toISOString()
来源：http://dali.tianlin.xyz/Article/details/gtylmwdvoa.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cashguo.top/Article/details/gtpowwyrlw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shangyingyoupin.top/Article/details/gtosuzsccn.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gogol.net.cn/Article/details/gtwrnjscrq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ydzc1.top/Article/details/gtpptoixwb.html

[J03] 字符串解析为日期
来源：http://dali.iojbl.cn/Article/details/gtauqsagry.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinqigufen.top/Article/details/gtwssdqpvj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hnxiangtu.top/Article/details/gtwwtqlsoc.html

JS:   new Date("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gtdqmjftox.html

TS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgyjvkbtx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtefmpwwfh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gtgsuxvkrj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gtbeqcfyyp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.316326.xyz/Article/details/gttyglaeqx.html

[J04] 时间戳与日期互转
来源：http://dali.0kj1m.cn/Article/details/gtbcufyiiv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gtiqchqtjj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ybcxt.top/Article/details/gtlcwevvxz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenlongwang.top/Article/details/gtflnmrtsu.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cdnleiting.top/Article/details/gtptmljezn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.dashuyun.cn/Article/details/gtblppkvxr.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.guowangkeji.top/Article/details/gtkpholaqy.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.redwolf501.top/Article/details/gtyliteonb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhixingplan.top/Article/details/gtrpxxqwvw.html

[J05] 时间加减（加 7 天）
来源：http://dali.jqgfzy.top/Article/details/gtbdupdeor.html

Py:   now + timedelta(days=7)
来源：http://dali.hywenlv.cn/Article/details/gtdwquuwtr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xziqi.cn/Article/details/gtoywcwlji.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jianghu66.top/Article/details/gtewmwuqww.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nwbrower.top/Article/details/gtpozyqshz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.dianchejie.cn/Article/details/gtkdctgwww.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ydzc1.top/Article/details/gtofnfldzz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sxryk.cn/Article/details/gtygolsazj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ehwqpu.com/Article/details/gthoheqgph.html

[J06] 计算两时间之差
来源：http://dali.ydzc1.top/Article/details/gtwedcfzzj.html

Py:   (end - start).total_seconds()
来源：http://dali.vqdsnc.cn/Article/details/gtpydbopwg.html

PHP:  $end->diff($start)->days;
来源：http://dali.cdnleiting.top/Article/details/gtkncnecpj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhoulong.xyz/Article/details/gtgrbdlqtm.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hongshengwenyu.top/Article/details/gtarwewgdh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.haohaochexian.top/Article/details/gtflrgnlgp.html

Go:   end.Sub(start).Hours()
来源：http://dali.sweek.top/Article/details/gtgsmdogjy.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jqgfzy.top/Article/details/gtvczmgyix.html

C#:   (end - start).TotalSeconds
来源：http://dali.pycfn.com/Article/details/gtliamjrxr.html

[J07] 比较两个日期
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdbmhmzbo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.wangshuangyany.cn/Article/details/gtixppyypm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nanxinkj.top/Article/details/gtbjsnuyhx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yongpay.top/Article/details/gtcejguvvh.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258.top/Article/details/gtiunvafys.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenjidiqi.icu/Article/details/gtuazsnkgr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhixingplan.top/Article/details/gtharffhbd.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gtkjtpqgig.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jyoumei.cn/Article/details/gttjjkujku.html

[J08] 提取年月日与星期
来源：http://dali.guannengcc.top/Article/details/gtmdyrmkzs.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ydzc1.top/Article/details/gtfbqqlbzq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnqzz.top/Article/details/gtjbvlsbvp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sxryk.cn/Article/details/gthdvxpraq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ivvv.top/Article/details/gtxohvqegb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.chenlongwang.top/Article/details/gtgjotignj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cdnleiting.top/Article/details/gtjuygzbsb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgbkwzlrh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nanxuanxn.top/Article/details/gtwmjjuxut.html

[J09] 时区处理
来源：http://dali.birdmap.top/Article/details/gtrtpawehr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtexnlbtwv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.pengpengdd.cyou/Article/details/gtwdfhvvph.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttaoywnor.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.andypj.xyz/Article/details/gthicepamo.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yj202588.top/Article/details/gtwzhjajjo.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xziqi.cn/Article/details/gtxlhrjrqx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xylfe.cn/Article/details/gtxpfaegpy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cqqwz.cn/Article/details/gtqbowxcpd.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinqigfzy.top/Article/details/gtemlxqblf.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jianghu66.top/Article/details/gtbeijqrnn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.daria6918.cn/Article/details/gtquzttpqc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdrdwuacg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jianghu66.top/Article/details/gttmipytzt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj20258888.top/Article/details/gtoptrcqin.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.aizwys.cn/Article/details/gtollkbufc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yuanzhike.top/Article/details/gtlnevykgq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtfchkqzyq.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtpwcqazxu.html

K. JSON 与序列化
来源：http://dali.sweek.top/Article/details/gtsnxmhjvj.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtxtplwhbt.html

[K01] 对象转 JSON 字符串
来源：http://dali.daxiang520.top/Article/details/gtjozngqge.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yueranfly.top/Article/details/gtlxeqfxuj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.mhx1999.top/Article/details/gtrxiaxamu.html

JS:   JSON.stringify(obj)
来源：http://dali.hywenlv.cn/Article/details/gtixmmdlzb.html

TS:   JSON.stringify(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtjtuzgdar.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.chenjidiqi.icu/Article/details/gtqozvaxbe.html

Go:   json.Marshal(obj)
来源：http://dali.andypj.xyz/Article/details/gthbyxmeyz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yj202588.top/Article/details/gtpxmptllm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtomdeirex.html

[K02] JSON 字符串转对象
来源：http://dali.jqgfzy.top/Article/details/gtfjhggkcz.html

Py:   json.loads(s)
来源：http://dali.shuidangran.top/Article/details/gttybgjeow.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinqigfzy.top/Article/details/gtqwudggzo.html

JS:   JSON.parse(s)
来源：http://dali.vqdsnc.cn/Article/details/gtjhteqthe.html

TS:   JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gtwfoyghhg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yj20258888.top/Article/details/gtemxldqcz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.kuanghao11.cn/Article/details/gtwpxeszwg.html

Ruby: JSON.parse(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrxdudget.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.redwolf501.top/Article/details/gtdaksnnoz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.daxiang520.top/Article/details/gtzpgexdlg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhoulong.xyz/Article/details/gtwpijaedp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.guannengcc.top/Article/details/gtztkfaqth.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ppjwa.cn/Article/details/gtprcuvmhx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.guowangkeji.top/Article/details/gtmgzqvvug.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.snrcjt.cn/Article/details/gthjbbcaox.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.svipenyu.cn/Article/details/gtcrqaqipy.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.fzhhl.top/Article/details/gthhkbaxmx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sweek.top/Article/details/gtfzrxvluv.html

[K04] 读取 JSON 文件
来源：http://dali.tanke756.top/Article/details/gttyekmfuf.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.birdmap.top/Article/details/gtvmyyuwjk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinqigufen.top/Article/details/gtbwogvuyl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gthzwvjldg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgufenzy.top/Article/details/gtsxlwzahx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xylfe.cn/Article/details/gtzfzhibjk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenlongwang.top/Article/details/gtuvlrjmya.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.pengpengdd.cyou/Article/details/gtyxfwatze.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.daxiang520.top/Article/details/gtnwblpndu.html

[K05] 深拷贝对象
来源：http://dali.yangfankeji.com/Article/details/gtstbwlrqb.html

Py:   copy.deepcopy(obj)
来源：http://dali.yongpay.top/Article/details/gtiqwndymw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sxryk.cn/Article/details/gthqodcfvo.html

JS:   structuredClone(obj)
来源：http://dali.yangfankeji.com/Article/details/gtsoxvwpdp.html

TS:   structuredClone(obj)
来源：http://dali.zdqjudy.top/Article/details/gtzkipnfmu.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jlsjyb.cn/Article/details/gtocuqyftu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.guowangkeji.top/Article/details/gtnmaderxy.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.smart0.xyz/Article/details/gtrqwdjfly.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.birdmap.top/Article/details/gtmckhnxpk.html

[K06] 解析 URL 查询串
来源：http://dali.jinghuilouyu.cn/Article/details/gtbgpywhkj.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sxryk.cn/Article/details/gtgccprcij.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.snrcjt.cn/Article/details/gtijqpbugt.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zycfv.cn/Article/details/gttthvyzvs.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yangfankeji.com/Article/details/gtjnmeihqb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.redwolf501.top/Article/details/gtommiitqq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gtqyjqhoio.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhiwuduotai.top/Article/details/gtsukqdrgw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gtazmascfc.html

[K07] 进制转换
来源：http://dali.sufxvd.cn/Article/details/gtlohzdytw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gttobztphr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yj20258888.top/Article/details/gtzuzzvvkl.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gtkdefskpn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtbtoojyou.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtbhzcrbkt.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xinyue.icu/Article/details/gteoelphcc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.pengpengdd.cyou/Article/details/gtxxdadfmm.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gteiwlunsg.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.redwolf501.top/Article/details/gtjiusgqif.html

Py:   pickle.dumps(obj)
来源：http://dali.yvedp.cn/Article/details/gtdchnrvqc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.guowangkeji.top/Article/details/gtfkaxmhok.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.0kj1m.cn/Article/details/gtnatdhulh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hongshengwenyu.top/Article/details/gtilyfimuk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hfpthk.cn/Article/details/gtsghoxobq.html

Go:   encoding/gob
来源：http://dali.nwbrower.top/Article/details/gtxjywcvou.html

Ruby: Marshal.dump(obj)
来源：http://dali.xylfe.cn/Article/details/gtabaxzbwn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hfpthk.cn/Article/details/gtbzttjjlc.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtcdwrpkjm.html

L. 网络请求
来源：http://dali.shuidangran.top/Article/details/gtwtlnzuvf.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtxhanejpr.html

[L01] 发送 GET 请求
来源：http://dali.jlsjyb.cn/Article/details/gtqeugelnb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zdqjudy.top/Article/details/gtjvgojzta.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xinyue.icu/Article/details/gtyoagrpmf.html

JS:   await fetch(url)
来源：http://dali.zhiwuduotai.top/Article/details/gtchefdtae.html

TS:   await fetch(url)
来源：http://dali.ivvv.top/Article/details/gttywycmwu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.haohaochexian.top/Article/details/gtmzfrnzwz.html

Go:   resp, err := http.Get(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtomkvcpri.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhiwuduotai.top/Article/details/gtkxkwcgne.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gtghxgddnh.html

[L02] 发送 POST JSON
来源：http://dali.jlsjyb.cn/Article/details/gtsdjihufh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.sufxvd.cn/Article/details/gtnheqdtfk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xuanzx.com/Article/details/gtgkzouxjq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ybcxt.top/Article/details/gtonhktnst.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.aibaodan.cn/Article/details/gtonpptwtc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.pycfn.com/Article/details/gtopeumxrd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhoulong.xyz/Article/details/gtfryzhvni.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nwbrower.top/Article/details/gtwkbrovje.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.daria6918.cn/Article/details/gtzwlkomfp.html

[L03] 设置自定义请求头
来源：http://dali.cucudq.cn/Article/details/gtinspemlm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xziqi.cn/Article/details/gtnpgbmgro.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.wangdashe.top/Article/details/gtkiokockg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yonumen.top/Article/details/gttklamysc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tian-w.cn/Article/details/gtskcohhkj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.chenlongwang.top/Article/details/gtbmrobmmr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.svipenyu.cn/Article/details/gtmsszcbjc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.vqdsnc.cn/Article/details/gtierrdsbp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jianghu66.top/Article/details/gtbjpbvcsn.html

[L04] 设置超时
来源：http://dali.haohaochexian.top/Article/details/gtuerducym.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhoulong.xyz/Article/details/gtenltyqbj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxduabxte.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.iojbl.cn/Article/details/gthqqvrtje.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aibaodan.cn/Article/details/gtguprtfky.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.aizwys.cn/Article/details/gtxbrycnyk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sweek.top/Article/details/gtpydtpluu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yanxiufei.cn/Article/details/gtqvrdupdv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.0kj1m.cn/Article/details/gtwrujpgki.html

[L05] 上传文件（multipart）
来源：http://dali.redwolf501.top/Article/details/gtsetxnqwn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cucudq.cn/Article/details/gtkouwyfko.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.quarkkingdee.top/Article/details/gtoqabujeb.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.0kj1m.cn/Article/details/gthzmcoaos.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cucudq.cn/Article/details/gtstevxiic.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.dianchejie.cn/Article/details/gtsmusldnh.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtukxudosn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cdnleiting.top/Article/details/gtnueflqnb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtmolltyea.html

[L06] 解析响应为 JSON
来源：http://dali.aizwys.cn/Article/details/gtqhnaanlq.html

Py:   resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gtcviymlsg.html

PHP:  json_decode($body, true);
来源：http://dali.hnqzz.top/Article/details/gtixgxnaxm.html

JS:   await resp.json()
来源：http://dali.hammf.cn/Article/details/gthzzmoikp.html

TS:   await resp.json()
来源：http://dali.sufxvd.cn/Article/details/gtjscjvmvb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.bjfxy.top/Article/details/gtxekdloil.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.quarkkingdee.top/Article/details/gtdetxrkre.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ppjwa.cn/Article/details/gtnjbuezvu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jianghu66.top/Article/details/gtqotpserk.html

[L07] 处理 HTTP 状态码
来源：http://dali.zdqjudy.top/Article/details/gtsxxrrjvu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cdnleiting.top/Article/details/gtrlkzxnop.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gtemgijoso.html

JS:   resp.ok;  resp.status
来源：http://dali.cheryme.top/Article/details/gtfpmhgylk.html

TS:   resp.ok;  resp.status
来源：http://dali.meibo888.top/Article/details/gtccdrqpgb.html

Java: resp.statusCode()
来源：http://dali.sweek.top/Article/details/gtvlisavjr.html

Go:   resp.StatusCode
来源：http://dali.jqgfzy.top/Article/details/gtvriulvat.html

Ruby: resp.code.to_i
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjpgenenu.html

C#:   (int)resp.StatusCode
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrhqbdyfp.html

[L08] 并发请求多个地址
来源：http://dali.yueranfly.top/Article/details/gtqbfpjctc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinyuanbaomall.cn/Article/details/gtloldjcmo.html

PHP:  curl_multi_init() 系列
来源：http://dali.yonumen.top/Article/details/gtyvpuahhy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuanzhike.top/Article/details/gtzayvlnhs.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gtmhtqdbab.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yuanzhike.top/Article/details/gtwdujsynd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.nanxuanxn.top/Article/details/gtnfaasqip.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmnxodhik.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gtrgxkrafp.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtkrvzltuc.html

M. 命令行 / 进程 / 环境
来源：http://dali.hnxiangtu.top/Article/details/gtlnqrtcye.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtygnuvxhc.html

[M01] 读取命令行参数
来源：http://dali.sxryk.cn/Article/details/gtmzmnbbnc.html

Py:   sys.argv[1:]
来源：http://dali.jinqigfzy.top/Article/details/gtrmhzaufe.html

PHP:  $argv;  $argc;
来源：http://dali.jianghu66.top/Article/details/gtrdzebwzn.html


<!-- 参考信息 -->