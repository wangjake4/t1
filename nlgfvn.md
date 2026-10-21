代发 wailian999

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhoulong.xyz/Article/details/gtpvjnwemu.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hnxiangtu.top/Article/details/gtatiqzuoa.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yuanzhike.top/Article/details/gtotuzkumh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhengqikj.top/Article/details/gtolphowrj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ehwqpu.com/Article/details/gtvndweukk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.pengpengdd.cyou/Article/details/gtszzhkflz.html

[I04] 正则替换
来源：http://dali.gotoacloud.top/Article/details/gtfqnmyyie.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shangyingyoupin.top/Article/details/gtmbjkexrg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hammf.cn/Article/details/gtwlhbnyoe.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.meibo888.top/Article/details/gtefnexzww.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigfzy.top/Article/details/gtdkogjalw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sweek.top/Article/details/gtnfayhztp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gaohongyu789.top/Article/details/gtmxdxhgok.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.andypj.xyz/Article/details/gtzgcgbvrc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtztpqdmxe.html

[I05] 按正则拆分
来源：http://dali.xziqi.cn/Article/details/gtgrjvpxta.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yj20258888.top/Article/details/gtrsmsyjhk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hnqzz.top/Article/details/gtsufrvulo.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xylfe.cn/Article/details/gtfqqkwgxp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnghdrzbj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yonumen.top/Article/details/gtkkgjdojt.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.dianchejie.cn/Article/details/gtfgojrlvt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xuanzx.com/Article/details/gtfypjdkig.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.andypj.xyz/Article/details/gttjdzloft.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xylfe.cn/Article/details/gtgadfolxk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hfpthk.cn/Article/details/gtpbdlwnhu.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hywenlv.cn/Article/details/gtaqrpiijw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.vqdsnc.cn/Article/details/gtzcpdgydm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenzaomai.com/Article/details/gtxrvcyayf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.havefunace.top/Article/details/gtakubdurl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yuxming.cn/Article/details/gtgtlvrykh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ywan-chungtsiang.top/Article/details/gtprdglglh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gtwsxcwkml.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhiwuduotai.top/Article/details/gtxacwxdpf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhixingplan.top/Article/details/gtlifkrbpc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.pycfn.com/Article/details/gtzglbqilc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.0kj1m.cn/Article/details/gtzmikiode.html

TS:   /error/gim
来源：http://dali.cucudq.cn/Article/details/gtqjndtiay.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.nanxuanxn.top/Article/details/gtpvvcyasb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xinyue.icu/Article/details/gtxvccujeq.html

Ruby: s.scan(/error/i)
来源：http://dali.svipenyu.cn/Article/details/gtbvkpjbow.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.nanxinkj.top/Article/details/gtrttatomo.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jlsjyb.cn/Article/details/gtuhflkyxp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sufxvd.cn/Article/details/gtvojaglvc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yuxming.cn/Article/details/gtyppeuxmw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ppjwa.cn/Article/details/gtbnkukeyx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daria6918.cn/Article/details/gtrqkrhsox.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cqqwz.cn/Article/details/gtsjhjeruk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zycfv.cn/Article/details/gtjmothreq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.chenzaomai.com/Article/details/gtlhleigfc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hfpthk.cn/Article/details/gtststtwlb.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gthbzlvaqz.html

J. 日期与时间
来源：http://dali.birdmap.top/Article/details/gtubislrrn.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtwvkbhibx.html

[J01] 获取当前时间
来源：http://dali.yongpay.top/Article/details/gthbtlpwkf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj202588.top/Article/details/gtkjgsmjmn.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ywan-chungtsiang.top/Article/details/gthlaurrxr.html

JS:   new Date();  Date.now()
来源：http://dali.haohaochexian.top/Article/details/gtiswdupqv.html

TS:   new Date();  Date.now()
来源：http://dali.meibo888.top/Article/details/gtcwmfpxlx.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.dashuyun.cn/Article/details/gtmkxznpxm.html

Go:   time.Now()
来源：http://dali.yj20258.top/Article/details/gtlgaypvgx.html

Ruby: Time.now
来源：http://dali.yueranfly.top/Article/details/gtaswfvbpb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.smart0.xyz/Article/details/gtidxmrmzf.html

[J02] 格式化输出
来源：http://dali.yangfankeji.com/Article/details/gtdhwtwbxg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yanxiufei.cn/Article/details/gtpiewvewo.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ehwqpu.com/Article/details/gtowvmofxp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.bjfxy.top/Article/details/gtgynnrmdl.html

TS:   d.toISOString()
来源：http://dali.jqgfzy.top/Article/details/gtvccnhfvk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.wangshuangyany.cn/Article/details/gttjtlgcya.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xinyue.icu/Article/details/gtuisbbpxj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhixingplan.top/Article/details/gtgtlbsuvq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sxryk.cn/Article/details/gtexafdlrf.html

[J03] 字符串解析为日期
来源：http://dali.jlsjyb.cn/Article/details/gtbiihiktv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhoulong.xyz/Article/details/gtfzxdexln.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.havefunace.top/Article/details/gtbnnaaota.html

JS:   new Date("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gtejfnywed.html

TS:   new Date("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtccifmosp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gtdoawvwsw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gtgnshgmpy.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gtsurkhhns.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ppjwa.cn/Article/details/gtuwskwfvk.html

[J04] 时间戳与日期互转
来源：http://dali.kuanghao11.cn/Article/details/gtocnnsvca.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.dianchejie.cn/Article/details/gtusirxhpk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuvwwagtv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gaohongyu789.top/Article/details/gtctzxhddl.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cashguo.top/Article/details/gtjkdixwuk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.redwolf501.top/Article/details/gtljwwjsnt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtcxxljpxg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cucudq.cn/Article/details/gtjxvnxoih.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cashguo.top/Article/details/gtqdxzjafd.html

[J05] 时间加减（加 7 天）
来源：http://dali.cdnleiting.top/Article/details/gtdhlolesj.html

Py:   now + timedelta(days=7)
来源：http://dali.xuanzx.com/Article/details/gtsewwcnjg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.guannengcc.top/Article/details/gtmmynzoyr.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258888.top/Article/details/gtwzujmhyn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenlongwang.top/Article/details/gtirwupgfa.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.nanxinkj.top/Article/details/gtlkhgzicq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jlsjyb.cn/Article/details/gtgcyirlrl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hfpthk.cn/Article/details/gteiujqthd.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hfpthk.cn/Article/details/gtydiyylfo.html

[J06] 计算两时间之差
来源：http://dali.wangdashe.top/Article/details/gtjoyjxsgw.html

Py:   (end - start).total_seconds()
来源：http://dali.feifeiyinyue.top/Article/details/gtooboupey.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinqigufen.top/Article/details/gtumlzunsx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gaohongyu789.top/Article/details/gthjgvsfmc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yvedp.cn/Article/details/gtoiuyntgi.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ehwqpu.com/Article/details/gtjqfzebir.html

Go:   end.Sub(start).Hours()
来源：http://dali.havefunace.top/Article/details/gtbbuaebbh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shangyingyoupin.top/Article/details/gtzilajpro.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhoulong.xyz/Article/details/gtbycekqjo.html

[J07] 比较两个日期
来源：http://dali.yongpay.top/Article/details/gtahxatjqx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hnxiangtu.top/Article/details/gtlopeqtll.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yangfankeji.com/Article/details/gthmprdoos.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.snrcjt.cn/Article/details/gtyfuecqxq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hnqzz.top/Article/details/gtmnwwwrtj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yj20258.top/Article/details/gtuqrihmky.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.haohaochexian.top/Article/details/gtuietlogq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gtnkuebjyc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gtdzypsjad.html

[J08] 提取年月日与星期
来源：http://dali.kuanghao11.cn/Article/details/gthznyuflm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nanxuanxn.top/Article/details/gtxrloxazr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfojvonuh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hnqzz.top/Article/details/gtpamjqikc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.andypj.xyz/Article/details/gtypijiiad.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yonumen.top/Article/details/gtgytuohip.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhengqikj.top/Article/details/gthiqxsiti.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.kuanghao11.cn/Article/details/gtgtcwpacs.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.haohaochexian.top/Article/details/gtxmppfovn.html

[J09] 时区处理
来源：http://dali.yangfankeji.com/Article/details/gtftfnvess.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.daria6918.cn/Article/details/gtabdydbtc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.tanke756.top/Article/details/gtpgxtsxan.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpmvijypq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cashguo.top/Article/details/gtklhmxyqn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gaohongyu789.top/Article/details/gtdzoddttq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nanxinkj.top/Article/details/gtmlcesawk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hongshengwenyu.top/Article/details/gthoaljwwl.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhiwuduotai.top/Article/details/gtxgepfsmq.html

[J10] 取今天 / 本月第一天
来源：http://dali.kuanghao11.cn/Article/details/gtdxoxckxl.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cheryme.top/Article/details/gthpuazquz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hfpthk.cn/Article/details/gtlpvpmijo.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gzhubu.top/Article/details/gtbbbcpknl.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.dashuyun.cn/Article/details/gtfhaullkr.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.bjfxy.top/Article/details/gtpndwhnki.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhengqikj.top/Article/details/gtgjtqjqqk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhongyouzk.top/Article/details/gtdbhfdtqp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.tanke756.top/Article/details/gtruonftea.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtibustsge.html

K. JSON 与序列化
来源：http://dali.gaohongyu789.top/Article/details/gtzetejbbb.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtnhvhgplc.html

[K01] 对象转 JSON 字符串
来源：http://dali.kuanghao11.cn/Article/details/gtyjjcwgbb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.feifeiyinyue.top/Article/details/gtlazifkgy.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ybcxt.top/Article/details/gtezkbdtod.html

JS:   JSON.stringify(obj)
来源：http://dali.yongpay.top/Article/details/gtknnmamjw.html

TS:   JSON.stringify(obj)
来源：http://dali.yonumen.top/Article/details/gtiezbofml.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yj20258.top/Article/details/gtgotwhpue.html

Go:   json.Marshal(obj)
来源：http://dali.daria6918.cn/Article/details/gtbodgwnvj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.redwolf501.top/Article/details/gtzewuhyyh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.c1oappe.top/Article/details/gtkzeapfjc.html

[K02] JSON 字符串转对象
来源：http://dali.meibo888.top/Article/details/gtnxcjziwh.html

Py:   json.loads(s)
来源：http://dali.xinyue.icu/Article/details/gtvizsiyez.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zdqjudy.top/Article/details/gtxlctgzhn.html

JS:   JSON.parse(s)
来源：http://dali.ehwqpu.com/Article/details/gtrkyhsocp.html

TS:   JSON.parse(s)
来源：http://dali.hfpthk.cn/Article/details/gtpndseshx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hammf.cn/Article/details/gtvkemtxdw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gtkjahdhqg.html

Ruby: JSON.parse(s)
来源：http://dali.andypj.xyz/Article/details/gtnqqbphme.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhongyouzk.top/Article/details/gtwmncclgp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yuxming.cn/Article/details/gtiowetuzs.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.vqdsnc.cn/Article/details/gtmtrawjnk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tanke756.top/Article/details/gtjobuucxc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cdnleiting.top/Article/details/gtpnlsxbba.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ivvv.top/Article/details/gttsaellcf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gotoacloud.top/Article/details/gtzmmkkpmu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.kuanghao11.cn/Article/details/gtzbypsbxf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zycfv.cn/Article/details/gtmbrsvrgl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cdnleiting.top/Article/details/gtpnpuchmk.html

[K04] 读取 JSON 文件
来源：http://dali.shzxlz.cn/Article/details/gtthmrmfqs.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinqigfzy.top/Article/details/gtoxidmlxu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.wangdashe.top/Article/details/gtsmfuqncm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pengpengdd.cyou/Article/details/gtpmuppwhh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tanke756.top/Article/details/gtjikntwvo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gtderixoxh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sysykeji.top/Article/details/gtjvmalrln.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jianghu66.top/Article/details/gtixtridmu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.316326.xyz/Article/details/gttdjjykyk.html

[K05] 深拷贝对象
来源：http://dali.jinqigufen.top/Article/details/gtvrtcmrnf.html

Py:   copy.deepcopy(obj)
来源：http://dali.yonumen.top/Article/details/gtqyniwmqs.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sxryk.cn/Article/details/gtwzobfkwr.html

JS:   structuredClone(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtlmcijomq.html

TS:   structuredClone(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwndjzzoq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sweek.top/Article/details/gtwvjrobnv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvyvxloob.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xylfe.cn/Article/details/gtoqyrqvme.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.pengpengdd.cyou/Article/details/gtkrpegmtj.html

[K06] 解析 URL 查询串
来源：http://dali.cdnleiting.top/Article/details/gthertynep.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.guannengcc.top/Article/details/gtmrulbghl.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jianghu66.top/Article/details/gtvgxinflt.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangshuangyany.cn/Article/details/gteesdcjym.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwlpwutfa.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.chenzaomai.com/Article/details/gtvftjfayx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gtewaztvdw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gthxrxaqht.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gtxiircmrf.html

[K07] 进制转换
来源：http://dali.zhoulong.xyz/Article/details/gtlburwiaq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtscbnkbet.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.wangdashe.top/Article/details/gttgenmnfl.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gtcsthjxpy.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gtmymbmess.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gtlncmtzod.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hywenlv.cn/Article/details/gtygamtcbi.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinqigufen.top/Article/details/gtmqwyxelf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtnhbdehkk.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ydzc1.top/Article/details/gthrfzuegw.html

Py:   pickle.dumps(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtuinzjmlw.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.iojbl.cn/Article/details/gtkztlcrom.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jianghu66.top/Article/details/gtdmsyvzuw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.guannengcc.top/Article/details/gtpyzjzpaa.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhixingplan.top/Article/details/gtgkituzxl.html

Go:   encoding/gob
来源：http://dali.zhoulong.xyz/Article/details/gttcxcjxep.html

Ruby: Marshal.dump(obj)
来源：http://dali.haohaochexian.top/Article/details/gtiqixogcp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jiagoushi.top/Article/details/gtvbjuitrv.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtmqqbsmwo.html

L. 网络请求
来源：http://dali.shanyushiyangkeji.top/Article/details/gthfzoggof.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtqctjzgif.html

[L01] 发送 GET 请求
来源：http://dali.haohaochexian.top/Article/details/gtgklxrohp.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sweek.top/Article/details/gtyelyqlms.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yj20258.top/Article/details/gtjdwthgxm.html

JS:   await fetch(url)
来源：http://dali.cucudq.cn/Article/details/gtiygasxns.html

TS:   await fetch(url)
来源：http://dali.sweek.top/Article/details/gtuooqrkgh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.guannengcc.top/Article/details/gtwbkmgvvx.html

Go:   resp, err := http.Get(url)
来源：http://dali.svipenyu.cn/Article/details/gtbgfwhxvh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cashguo.top/Article/details/gtyxphlohz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.fengsongda.top/Article/details/gtydgzfxum.html

[L02] 发送 POST JSON
来源：http://dali.dashuyun.cn/Article/details/gtkhxymije.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ybcxt.top/Article/details/gtwivbfznb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.svipenyu.cn/Article/details/gtwjwikwow.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sufxvd.cn/Article/details/gtfussewsz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daria6918.cn/Article/details/gtxqrxuhwe.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.guowangkeji.top/Article/details/gtpcnigucu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yanxiufei.cn/Article/details/gtvunbdczx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.dianchejie.cn/Article/details/gtlyilupgq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ybcxt.top/Article/details/gtebhinspb.html

[L03] 设置自定义请求头
来源：http://dali.mhx1999.top/Article/details/gtmcoqattd.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jqgufenzy.top/Article/details/gtydbubsax.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yueranfly.top/Article/details/gtleybgvpf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.iojbl.cn/Article/details/gtcxetvgkg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhiwuduotai.top/Article/details/gtpflyqklh.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xziqi.cn/Article/details/gtccujqkba.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yongpay.top/Article/details/gttwjjjqkz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhiwuduotai.top/Article/details/gtwtvjasxn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sxryk.cn/Article/details/gtetaruzhf.html

[L04] 设置超时
来源：http://dali.fzhhl.top/Article/details/gtrbypjewx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hammf.cn/Article/details/gtmekzzerd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinqigfzy.top/Article/details/gtguzxyuuf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.redwolf501.top/Article/details/gtjuwzuscb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ehwqpu.com/Article/details/gtldsxwbqm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinqigfzy.top/Article/details/gtgmpwmpay.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gzhubu.top/Article/details/gtpjsofrtn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.meibo888.top/Article/details/gtdsmlngug.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.nwbrower.top/Article/details/gtjskggovj.html

[L05] 上传文件（multipart）
来源：http://dali.andypj.xyz/Article/details/gtsyjrjpiz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jiagoushi.top/Article/details/gthyyasxgk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cashguo.top/Article/details/gtphmwlydk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gotoacloud.top/Article/details/gtdvhserbz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gttwhwlprz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hysaishi.cn/Article/details/gtpmptixaq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.tian-w.cn/Article/details/gtoxwxehvo.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsmgwiaew.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtulgxzkyg.html

[L06] 解析响应为 JSON
来源：http://dali.yueranfly.top/Article/details/gtrhszxela.html

Py:   resp.json()
来源：http://dali.birdmap.top/Article/details/gtkgsqhxii.html

PHP:  json_decode($body, true);
来源：http://dali.cucudq.cn/Article/details/gtqiqhsltt.html

JS:   await resp.json()
来源：http://dali.cashguo.top/Article/details/gtfgykkngp.html

TS:   await resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gtqnpwlfrl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.havefunace.top/Article/details/gtknmvbsyu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.gzhubu.top/Article/details/gtvzhbvfgg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xuanzx.com/Article/details/gtskmszzny.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zycfv.cn/Article/details/gtaozdspbe.html

[L07] 处理 HTTP 状态码
来源：http://dali.wangdashe.top/Article/details/gtokqwjwnb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hongshengwenyu.top/Article/details/gtllcawtwz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hongshengwenyu.top/Article/details/gtlzmcvksf.html

JS:   resp.ok;  resp.status
来源：http://dali.chenlongwang.top/Article/details/gtyekmmvxj.html

TS:   resp.ok;  resp.status
来源：http://dali.jianghu66.top/Article/details/gtnhhhzdhv.html

Java: resp.statusCode()
来源：http://dali.daria6918.cn/Article/details/gtwgjhlyna.html

Go:   resp.StatusCode
来源：http://dali.316326.xyz/Article/details/gtustuczug.html

Ruby: resp.code.to_i
来源：http://dali.yangfankeji.com/Article/details/gtqzyoqyax.html

C#:   (int)resp.StatusCode
来源：http://dali.guannengcc.top/Article/details/gtzrbdmtbf.html

[L08] 并发请求多个地址
来源：http://dali.redwolf501.top/Article/details/gtgifacuoo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgppxyquq.html

PHP:  curl_multi_init() 系列
来源：http://dali.xziqi.cn/Article/details/gtlvlwakyh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gtcfjubnhz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aibaodan.cn/Article/details/gtipgskssu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shuidangran.top/Article/details/gtdudawkvs.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ehwqpu.com/Article/details/gtzpwylzqe.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shangyingyoupin.top/Article/details/gtawktdlza.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.smart0.xyz/Article/details/gtbfhhwovf.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gticaehjfi.html

M. 命令行 / 进程 / 环境
来源：http://dali.yueranfly.top/Article/details/gtyetrqeif.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtabmycoki.html

[M01] 读取命令行参数
来源：http://dali.pengpengdd.cyou/Article/details/gtutsbofnb.html

Py:   sys.argv[1:]
来源：http://dali.cucudq.cn/Article/details/gtrjskwuqq.html

PHP:  $argv;  $argc;
来源：http://dali.daria6918.cn/Article/details/gtiugxjxkk.html


<!-- 参考信息 -->