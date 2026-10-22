代发 wailian999

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.nwbrower.top/Article/details/gtfuocrylp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zycfv.cn/Article/details/gtqdhtvtpt.html

[I04] 正则替换
来源：http://dali.wangshuangyany.cn/Article/details/gtuqnfknxv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.meibo888.top/Article/details/gtdnfkhkrf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hysaishi.cn/Article/details/gtmevwsmcs.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.nwbrower.top/Article/details/gtrtdgbmwm.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hnqzz.top/Article/details/gtsueqttlh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhixingplan.top/Article/details/gtldqfoukf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hnqzz.top/Article/details/gtysljzfzd.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.0kj1m.cn/Article/details/gtkwyrcbpg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj202588.top/Article/details/gtqmgxpdzy.html

[I05] 按正则拆分
来源：http://dali.jlsjyb.cn/Article/details/gtyolhoyhd.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gzhubu.top/Article/details/gtjafvjbzw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.tian-w.cn/Article/details/gtocmbxpgc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ydzc1.top/Article/details/gtorlyskdt.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xuanzx.com/Article/details/gtmzkegmmu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzjcqdpmx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jlsjyb.cn/Article/details/gtjplnruxp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.dashuyun.cn/Article/details/gtsgsqmiuf.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenlongwang.top/Article/details/gtvqrrrlua.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.snrcjt.cn/Article/details/gtvrhqawvl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gtbwbltpbi.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xziqi.cn/Article/details/gtjxjlfktk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fengsongda.top/Article/details/gtkqsjagoj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daria6918.cn/Article/details/gtcylptrnr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gtfvqinlok.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hammf.cn/Article/details/gtrlshanrx.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhengqikj.top/Article/details/gtliidexaj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gtekxwdjxx.html

[I07] 忽略大小写与多行模式
来源：http://dali.zycfv.cn/Article/details/gtwbxfgjmh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xinyue.icu/Article/details/gtqfqjfhoi.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hfpthk.cn/Article/details/gtrhlawifv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhixingplan.top/Article/details/gtgymrnesc.html

TS:   /error/gim
来源：http://dali.shanyushiyangtech.top/Article/details/gtvkxtowlw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.316326.xyz/Article/details/gttflmlmrt.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gtblpoogkp.html

Ruby: s.scan(/error/i)
来源：http://dali.cqqwz.cn/Article/details/gtrgxqarsj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.mhx1999.top/Article/details/gtagqxteas.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.chenzaomai.com/Article/details/gttkpirmbf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.pengpengdd.cyou/Article/details/gtfskecsvo.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.chenzaomai.com/Article/details/gtrzngittq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cucudq.cn/Article/details/gtwzxpssou.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxuanxn.top/Article/details/gteiuqoeha.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhoulong.xyz/Article/details/gtbzkjaoph.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gttojohlwq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sysykeji.top/Article/details/gtxtocggbt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.vqdsnc.cn/Article/details/gtgolhqfhg.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtajgsokki.html

J. 日期与时间
来源：http://dali.xinyue.icu/Article/details/gtebbwehrh.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtygewxbvi.html

[J01] 获取当前时间
来源：http://dali.meibo888.top/Article/details/gtzfcvhsvm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jlsjyb.cn/Article/details/gtpvzxnqkv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.c1oappe.top/Article/details/gtwkqngdoq.html

JS:   new Date();  Date.now()
来源：http://dali.cqqwz.cn/Article/details/gtksqiawoq.html

TS:   new Date();  Date.now()
来源：http://dali.hywenlv.cn/Article/details/gtxzvqbcgh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenjidiqi.icu/Article/details/gtolcumnwy.html

Go:   time.Now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtasljzzhn.html

Ruby: Time.now
来源：http://dali.guowangkeji.top/Article/details/gtiuurtjum.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yongpay.top/Article/details/gtluwqawck.html

[J02] 格式化输出
来源：http://dali.vqdsnc.cn/Article/details/gtsxnmjogv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.vqdsnc.cn/Article/details/gtqrsfsxbj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hywenlv.cn/Article/details/gtumlzkgxc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.wangshuangyany.cn/Article/details/gtcczutewc.html

TS:   d.toISOString()
来源：http://dali.feifeiyinyue.top/Article/details/gtywtcrfds.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbtoxmard.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.tianlin.xyz/Article/details/gtlpiqiiaj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.iojbl.cn/Article/details/gtmdegoofx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ivvv.top/Article/details/gtozxiqlpd.html

[J03] 字符串解析为日期
来源：http://dali.shangyingyoupin.top/Article/details/gtibbgurkb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hywenlv.cn/Article/details/gteimpuhfv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.tian-w.cn/Article/details/gtqdcmosbh.html

JS:   new Date("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gtzttoidod.html

TS:   new Date("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtptujlpzw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gttimdwmgd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtyryvcdzj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gtpypzfgzv.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhixingplan.top/Article/details/gtfdtydnkq.html

[J04] 时间戳与日期互转
来源：http://dali.ppjwa.cn/Article/details/gtfwrkunth.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.chenzaomai.com/Article/details/gtxohlvvqn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinqigufen.top/Article/details/gtqyxgqgff.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hywenlv.cn/Article/details/gtovwzvyti.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yanxiufei.cn/Article/details/gtkdedqynm.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hysaishi.cn/Article/details/gtpmljudvv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ehwqpu.com/Article/details/gtohooosfr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cashguo.top/Article/details/gtvhslwwfg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yanxiufei.cn/Article/details/gtxfljnuoy.html

[J05] 时间加减（加 7 天）
来源：http://dali.jlsjyb.cn/Article/details/gtvyngomtd.html

Py:   now + timedelta(days=7)
来源：http://dali.hammf.cn/Article/details/gtzpvcyunk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhoulong.xyz/Article/details/gtxaqyuqmk.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xylfe.cn/Article/details/gthostvmkq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangshuangyany.cn/Article/details/gtbowtifaf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.havefunace.top/Article/details/gtslgupsxp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zdqjudy.top/Article/details/gtgitsoqga.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ydzc1.top/Article/details/gttjrpccij.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhiwuduotai.top/Article/details/gtngdsqcrl.html

[J06] 计算两时间之差
来源：http://dali.vqdsnc.cn/Article/details/gtlhmbyyfs.html

Py:   (end - start).total_seconds()
来源：http://dali.iojbl.cn/Article/details/gtmrfdyluh.html

PHP:  $end->diff($start)->days;
来源：http://dali.feifeiyinyue.top/Article/details/gtjtucksmt.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gogol.net.cn/Article/details/gtbuzraxyp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sweek.top/Article/details/gtczshhrxx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.0kj1m.cn/Article/details/gtdiotzkef.html

Go:   end.Sub(start).Hours()
来源：http://dali.ehwqpu.com/Article/details/gtukczomrd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yj202588.top/Article/details/gtqcqdjzpi.html

C#:   (end - start).TotalSeconds
来源：http://dali.xuetiantiany.cn/Article/details/gteyovglru.html

[J07] 比较两个日期
来源：http://dali.guowangkeji.top/Article/details/gtapguwyau.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gtfxdyhlbr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.havefunace.top/Article/details/gtlnehwgeq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxuanxn.top/Article/details/gtwekbrtxl.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gtoogtyiyl.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.dashuyun.cn/Article/details/gtfhajbmsp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.fzhhl.top/Article/details/gtifzsmkou.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xinyue.icu/Article/details/gtxrqpwoos.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gtjtwtkmyp.html

[J08] 提取年月日与星期
来源：http://dali.shanyushiyangkeji.top/Article/details/gthbevxoyx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xziqi.cn/Article/details/gtrmxjjdnw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhongyouzk.top/Article/details/gtugyqwdwt.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.iojbl.cn/Article/details/gtkcjevzfb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sysykeji.top/Article/details/gtebjessvd.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.316326.xyz/Article/details/gthimjwkxd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zdqjudy.top/Article/details/gtscmtfweu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.pengpengdd.cyou/Article/details/gtedsydcjh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hysaishi.cn/Article/details/gtxmhxzixm.html

[J09] 时区处理
来源：http://dali.zhoulong.xyz/Article/details/gtobumfbun.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yonumen.top/Article/details/gtbjmkfdfr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nwbrower.top/Article/details/gtetvsdsno.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj202588.top/Article/details/gtryklbqpd.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zycfv.cn/Article/details/gtsjrwlgcz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yanxiufei.cn/Article/details/gtxgufrgoz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj20258888.top/Article/details/gtruwtvsmm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.tianlin.xyz/Article/details/gtflkbwwhu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gogol.net.cn/Article/details/gtavmunmpl.html

[J10] 取今天 / 本月第一天
来源：http://dali.ehwqpu.com/Article/details/gtbietmdov.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shangyingyoupin.top/Article/details/gtietxmntl.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhiwuduotai.top/Article/details/gtcauhtpip.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xylfe.cn/Article/details/gtuswrqzwk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.daxiang520.top/Article/details/gtupuejjdb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.svipenyu.cn/Article/details/gtxgowdhxm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.daria6918.cn/Article/details/gtdkkmohip.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tian-w.cn/Article/details/gtoyjqolym.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.fengsongda.top/Article/details/gtlyufgxdy.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtwqvqwqqs.html

K. JSON 与序列化
来源：http://dali.sweek.top/Article/details/gtcwxbdkkc.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtohdfqtro.html

[K01] 对象转 JSON 字符串
来源：http://dali.iojbl.cn/Article/details/gtzhuvgnwf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.quarkkingdee.top/Article/details/gtpcvbhqpy.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsgljtdux.html

JS:   JSON.stringify(obj)
来源：http://dali.ybcxt.top/Article/details/gtxfsufbtt.html

TS:   JSON.stringify(obj)
来源：http://dali.hammf.cn/Article/details/gtdqdakdrm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.wangshuangyany.cn/Article/details/gtnnliofdb.html

Go:   json.Marshal(obj)
来源：http://dali.gogol.net.cn/Article/details/gtnrwqlebq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yvedp.cn/Article/details/gtdbeslbme.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.guannengcc.top/Article/details/gtddxfqymj.html

[K02] JSON 字符串转对象
来源：http://dali.jyoumei.cn/Article/details/gtfvghdnug.html

Py:   json.loads(s)
来源：http://dali.jinqigfzy.top/Article/details/gtxmvncpig.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hongshengwenyu.top/Article/details/gtlfvzzekx.html

JS:   JSON.parse(s)
来源：http://dali.andypj.xyz/Article/details/gtljoniqmz.html

TS:   JSON.parse(s)
来源：http://dali.aibaodan.cn/Article/details/gtbhfrsxmy.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hywenlv.cn/Article/details/gtpwnzxqiu.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.daxiang520.top/Article/details/gtlrvuynry.html

Ruby: JSON.parse(s)
来源：http://dali.xuanzx.com/Article/details/gtbjrgykth.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jlsjyb.cn/Article/details/gtmeinhdxf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.haohaochexian.top/Article/details/gtlwzgwhqe.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcsblubmf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tian-w.cn/Article/details/gttksathta.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuanzhike.top/Article/details/gtyobmyrfl.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cheryme.top/Article/details/gtfcnosnoy.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yangfankeji.com/Article/details/gtllhimqqx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yuxming.cn/Article/details/gtdvpdtpen.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tian-w.cn/Article/details/gtcyvpewvp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhongyouzk.top/Article/details/gtxurofycl.html

[K04] 读取 JSON 文件
来源：http://dali.guowangkeji.top/Article/details/gtibakdizh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.pengpengdd.cyou/Article/details/gtawgmkhfh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.fzhhl.top/Article/details/gthdevbkiq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jianghu66.top/Article/details/gtbbbbfjfh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhongyouzk.top/Article/details/gtuiyfvudj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gzhubu.top/Article/details/gtdfkfqawq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ydzc1.top/Article/details/gtfxmtprzh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhengqikj.top/Article/details/gtvzahrgmq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.feifeiyinyue.top/Article/details/gtglnofddx.html

[K05] 深拷贝对象
来源：http://dali.shzxlz.cn/Article/details/gtspeztypm.html

Py:   copy.deepcopy(obj)
来源：http://dali.wangdashe.top/Article/details/gtsdmmrjqe.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jlsjyb.cn/Article/details/gtoirtlxcy.html

JS:   structuredClone(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtkuyzxmng.html

TS:   structuredClone(obj)
来源：http://dali.yj20258888.top/Article/details/gtwludajcs.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.andypj.xyz/Article/details/gtoroytlct.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cdnleiting.top/Article/details/gtnalagrsd.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sxryk.cn/Article/details/gtcwuyouki.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cdnleiting.top/Article/details/gtwerxwhwz.html

[K06] 解析 URL 查询串
来源：http://dali.guowangkeji.top/Article/details/gtnxnjqkfb.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhiwuduotai.top/Article/details/gtzwxronrp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinqigfzy.top/Article/details/gtijebbpvy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.c1oappe.top/Article/details/gtgockithq.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zycfv.cn/Article/details/gtmbmhsgol.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jyoumei.cn/Article/details/gtfwrrkxbx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.aizwys.cn/Article/details/gtbsnzijoh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.aizwys.cn/Article/details/gtkryuifmi.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yangfankeji.com/Article/details/gtbjziuoxh.html

[K07] 进制转换
来源：http://dali.dianchejie.cn/Article/details/gttxbaflyb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfybgkmye.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.chenjidiqi.icu/Article/details/gtthkupdnk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gtmzjsdthx.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gtdusjyyiw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtdwsklcme.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.svipenyu.cn/Article/details/gtehiecymn.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenlongwang.top/Article/details/gtjncwyrcs.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gtwklxcnjn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yuxming.cn/Article/details/gtfcxuxgux.html

Py:   pickle.dumps(obj)
来源：http://dali.yangfankeji.com/Article/details/gtkwarjlfo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yvedp.cn/Article/details/gtnnplfrus.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yuanzhike.top/Article/details/gtdrcfsato.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yangfankeji.com/Article/details/gtrvqtjpii.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jiagoushi.top/Article/details/gtfpdthgvd.html

Go:   encoding/gob
来源：http://dali.tian-w.cn/Article/details/gtwcmgndlz.html

Ruby: Marshal.dump(obj)
来源：http://dali.yueranfly.top/Article/details/gtslnxxcwh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.dianchejie.cn/Article/details/gtxsbukzle.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtiduialgh.html

L. 网络请求
来源：http://dali.hongshengwenyu.top/Article/details/gtxxvgyhqs.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtvojsfwlc.html

[L01] 发送 GET 请求
来源：http://dali.sysykeji.top/Article/details/gtkghvtqze.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jyoumei.cn/Article/details/gttrktfydt.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gaohongyu789.top/Article/details/gtsctwqqkz.html

JS:   await fetch(url)
来源：http://dali.nanxinkj.top/Article/details/gtvsbltimr.html

TS:   await fetch(url)
来源：http://dali.zhoulong.xyz/Article/details/gtmfsldtxt.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yanxiufei.cn/Article/details/gtvdniymnx.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlhxvfknd.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cucudq.cn/Article/details/gtyxybbsfu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.andypj.xyz/Article/details/gtmcmfcjhz.html

[L02] 发送 POST JSON
来源：http://dali.quarkkingdee.top/Article/details/gtjdzijiby.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.9152youxi.cn/Article/details/gtlsjsctbt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.guannengcc.top/Article/details/gtqvoqzypl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dianchejie.cn/Article/details/gtndillued.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenjidiqi.icu/Article/details/gtpkeabxro.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hfpthk.cn/Article/details/gtnqkzxhkc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.iojbl.cn/Article/details/gtbstuydvl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtywkzxake.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.316326.xyz/Article/details/gtfewarypr.html

[L03] 设置自定义请求头
来源：http://dali.gogol.net.cn/Article/details/gttszczzzg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.iojbl.cn/Article/details/gtcmbeewwm.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.pycfn.com/Article/details/gtgiqulhvk.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.316326.xyz/Article/details/gtwgahafti.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.meibo888.top/Article/details/gtqqkergbj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.wangdashe.top/Article/details/gtaywilqdg.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hammf.cn/Article/details/gtvhhxovsz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yongpay.top/Article/details/gtnxjynqot.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yonumen.top/Article/details/gthhpuggbx.html

[L04] 设置超时
来源：http://dali.jinghuilouyu.cn/Article/details/gtlgtqgcvi.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenjidiqi.icu/Article/details/gtkusrsobe.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yuanzhike.top/Article/details/gtjcqznonp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yueranfly.top/Article/details/gtughktchc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.redwolf501.top/Article/details/gteannjeeh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.mhx1999.top/Article/details/gtocuumqlg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gotoacloud.top/Article/details/gtkaldjsmb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hfpthk.cn/Article/details/gtfaouwffs.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yj20258888.top/Article/details/gtapnvatub.html

[L05] 上传文件（multipart）
来源：http://dali.xinyue.icu/Article/details/gtwddxhowz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jlsjyb.cn/Article/details/gtrracniba.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.nanxuanxn.top/Article/details/gtlwlpmazn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xinyue.icu/Article/details/gtaxuuryew.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnxiangtu.top/Article/details/gtgsvagazg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nanxuanxn.top/Article/details/gtmsfakdsh.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yuxming.cn/Article/details/gtmvtchjha.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yj202588.top/Article/details/gtmmvpnwnf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.andypj.xyz/Article/details/gtnwkouryy.html

[L06] 解析响应为 JSON
来源：http://dali.yanxiufei.cn/Article/details/gtpsnrhkwy.html

Py:   resp.json()
来源：http://dali.meibo888.top/Article/details/gtwyyewycd.html

PHP:  json_decode($body, true);
来源：http://dali.chenlongwang.top/Article/details/gtkftffyip.html

JS:   await resp.json()
来源：http://dali.9152youxi.cn/Article/details/gtttftmcgy.html

TS:   await resp.json()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwecbibwr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hnqzz.top/Article/details/gtrkigbqji.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.fzhhl.top/Article/details/gtgtgzuepm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.chenlongwang.top/Article/details/gtvytbqzjp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.c1oappe.top/Article/details/gtyujqsgtl.html

[L07] 处理 HTTP 状态码
来源：http://dali.c1oappe.top/Article/details/gtccutmwxv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhiwuduotai.top/Article/details/gtofvzdgxh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cheryme.top/Article/details/gtfscgvukv.html

JS:   resp.ok;  resp.status
来源：http://dali.zhoulong.xyz/Article/details/gtnzaqqihc.html

TS:   resp.ok;  resp.status
来源：http://dali.jyoumei.cn/Article/details/gtdfxofmuy.html

Java: resp.statusCode()
来源：http://dali.wangshuangyany.cn/Article/details/gtjkfnmxql.html

Go:   resp.StatusCode
来源：http://dali.xinyue.icu/Article/details/gtozzutwcr.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gthsvghybd.html

C#:   (int)resp.StatusCode
来源：http://dali.guowangkeji.top/Article/details/gtshvudprs.html

[L08] 并发请求多个地址
来源：http://dali.tianlin.xyz/Article/details/gtrdwvsrbg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nanxuanxn.top/Article/details/gtgpwoqykj.html

PHP:  curl_multi_init() 系列
来源：http://dali.fengsongda.top/Article/details/gtcwzicgte.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfjbpcbzr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gtotelcrwe.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.redwolf501.top/Article/details/gtwcmfnveu.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.smart0.xyz/Article/details/gtmudonljz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtusxlybsm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.daria6918.cn/Article/details/gtztoqqurd.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtwcqouhun.html

M. 命令行 / 进程 / 环境
来源：http://dali.pengpengdd.cyou/Article/details/gtpkierftw.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtvzauxwdx.html

[M01] 读取命令行参数
来源：http://dali.tian-w.cn/Article/details/gtocaciljl.html

Py:   sys.argv[1:]
来源：http://dali.nwbrower.top/Article/details/gtovzhhxro.html

PHP:  $argv;  $argc;
来源：http://dali.cqqwz.cn/Article/details/gtddvjghyh.html

JS:   process.argv.slice(2)
来源：http://dali.quarkkingdee.top/Article/details/gtjajdilin.html

TS:   process.argv.slice(2)
来源：http://dali.daxiang520.top/Article/details/gtlmmglzhf.html

Java: args 数组（main 方法参数）
来源：http://dali.ybcxt.top/Article/details/gteyfifgdc.html

Go:   os.Args[1:]
来源：http://dali.ybcxt.top/Article/details/gtvibzpkcv.html


<!-- 参考信息 -->