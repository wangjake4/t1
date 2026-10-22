代发 wailian999

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.c1oappe.top/Article/details/gtejryikpq.html

TS:   /error/gim
来源：http://dali.sxryk.cn/Article/details/gtpeatkqdi.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.haohaochexian.top/Article/details/gtklmqrugb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.chenzaomai.com/Article/details/gttyoywyso.html

Ruby: s.scan(/error/i)
来源：http://dali.jqgufenzy.top/Article/details/gtlnqdvqwl.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfevkutps.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.birdmap.top/Article/details/gtmfggwybj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.daxiang520.top/Article/details/gtgvoubkbk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jqgufenzy.top/Article/details/gtrjirhnmm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hongshengwenyu.top/Article/details/gttpuytkbq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.svipenyu.cn/Article/details/gtxvabzhlh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hysaishi.cn/Article/details/gtktejcdsx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yonumen.top/Article/details/gtffuazcxe.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.aibaodan.cn/Article/details/gtjmesdqrk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gtzwhvpoht.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtdvywvryc.html

J. 日期与时间
来源：http://dali.ppjwa.cn/Article/details/gthwucvkaq.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtfdvijgvw.html

[J01] 获取当前时间
来源：http://dali.hysaishi.cn/Article/details/gtsjeegewx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xylfe.cn/Article/details/gtwzstpdtd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.vqdsnc.cn/Article/details/gtcqnnkthk.html

JS:   new Date();  Date.now()
来源：http://dali.sufxvd.cn/Article/details/gtkitcjlgh.html

TS:   new Date();  Date.now()
来源：http://dali.ivvv.top/Article/details/gtbtndwqhv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jlsjyb.cn/Article/details/gtoyhmhivf.html

Go:   time.Now()
来源：http://dali.zhijiandao.cn/Article/details/gthveqxkan.html

Ruby: Time.now
来源：http://dali.chenzaomai.com/Article/details/gtijjnywqr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.tianlin.xyz/Article/details/gtrmoztihw.html

[J02] 格式化输出
来源：http://dali.tianlin.xyz/Article/details/gtaqkgayod.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.kuanghao11.cn/Article/details/gtnqjjhquc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ppjwa.cn/Article/details/gtnqppnnju.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hnxiangtu.top/Article/details/gthamnwgxv.html

TS:   d.toISOString()
来源：http://dali.hfpthk.cn/Article/details/gtmnqqatyb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yuxming.cn/Article/details/gtjsgyafjd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.smart0.xyz/Article/details/gtzyrjwook.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fzhhl.top/Article/details/gtcwzemowg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.redwolf501.top/Article/details/gtodopkwqq.html

[J03] 字符串解析为日期
来源：http://dali.snrcjt.cn/Article/details/gtkyelolzp.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yongpay.top/Article/details/gtvgbssztm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.andypj.xyz/Article/details/gtoccrqenj.html

JS:   new Date("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gtbuobmexu.html

TS:   new Date("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gtcbptnreo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gtgeklbodd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtywvrdmfk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gthvrxpuvw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.pengpengdd.cyou/Article/details/gtfcabqeud.html

[J04] 时间戳与日期互转
来源：http://dali.birdmap.top/Article/details/gtraybwzdg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jyoumei.cn/Article/details/gtgqpwcfbq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinghuilouyu.cn/Article/details/gtacbnqehj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jqgufenzy.top/Article/details/gtqkwivqqq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenjidiqi.icu/Article/details/gtqvbxqozd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xuanzx.com/Article/details/gtnncwzwol.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.0kj1m.cn/Article/details/gtvubfefgl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cqqwz.cn/Article/details/gtlxcchaiq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sweek.top/Article/details/gtcdhgtsup.html

[J05] 时间加减（加 7 天）
来源：http://dali.hnxiangtu.top/Article/details/gtyfraxojq.html

Py:   now + timedelta(days=7)
来源：http://dali.redwolf501.top/Article/details/gtzksjlrsy.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shzxlz.cn/Article/details/gtphmbubmp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nwbrower.top/Article/details/gtmnynqasr.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuetiantiany.cn/Article/details/gtmwxkocst.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.chenjidiqi.icu/Article/details/gtpcpbfujq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hongshengwenyu.top/Article/details/gtvjshxdeq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.meibo888.top/Article/details/gttnghrktk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinqigufen.top/Article/details/gtpqthvhsz.html

[J06] 计算两时间之差
来源：http://dali.hammf.cn/Article/details/gtcmyquwcf.html

Py:   (end - start).total_seconds()
来源：http://dali.snrcjt.cn/Article/details/gtfsadzfyb.html

PHP:  $end->diff($start)->days;
来源：http://dali.cqqwz.cn/Article/details/gtamufvwip.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.haohaochexian.top/Article/details/gtxcaqkjas.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.redwolf501.top/Article/details/gtgxenizix.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cheryme.top/Article/details/gtpmepsgkr.html

Go:   end.Sub(start).Hours()
来源：http://dali.ppjwa.cn/Article/details/gttxoajmak.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gaohongyu789.top/Article/details/gtpzzhlhrv.html

C#:   (end - start).TotalSeconds
来源：http://dali.mhx1999.top/Article/details/gtcjwbwxea.html

[J07] 比较两个日期
来源：http://dali.bjfxy.top/Article/details/gtwqvsgimw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yonumen.top/Article/details/gtzjnpkomy.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jlsjyb.cn/Article/details/gtvvlcfauj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yueranfly.top/Article/details/gttuutxhqu.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ppjwa.cn/Article/details/gtatncwiex.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cqqwz.cn/Article/details/gtppblocyg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.9152youxi.cn/Article/details/gtenykdyid.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gtqvzqofwr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shangyingyoupin.top/Article/details/gtqpglzsaj.html

[J08] 提取年月日与星期
来源：http://dali.yonumen.top/Article/details/gtxdilgbax.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenjidiqi.icu/Article/details/gtlmfblvdj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yvedp.cn/Article/details/gtensgiqeh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.fzhhl.top/Article/details/gthbqowscr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hnxiangtu.top/Article/details/gtfxqisusg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbdealwqn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shzxlz.cn/Article/details/gtwugdwoiq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.birdmap.top/Article/details/gtvlpgcmut.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gogol.net.cn/Article/details/gtpscqrvjm.html

[J09] 时区处理
来源：http://dali.zdqjudy.top/Article/details/gtuucynoph.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.dashuyun.cn/Article/details/gtkwtwuvjn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shangyingyoupin.top/Article/details/gtikukfcut.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yongpay.top/Article/details/gtydqumftx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jiagoushi.top/Article/details/gtydryrfeu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhengqikj.top/Article/details/gtpsdqdyyj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.vqdsnc.cn/Article/details/gtjnyvykth.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gaohongyu789.top/Article/details/gtrtqazsbw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jyoumei.cn/Article/details/gthbefvfun.html

[J10] 取今天 / 本月第一天
来源：http://dali.jiagoushi.top/Article/details/gtibskpzxe.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenzaomai.com/Article/details/gtljmsxwdo.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.haohaochexian.top/Article/details/gtbflrnsgn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yanxiufei.cn/Article/details/gtecfvsgua.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj20258888.top/Article/details/gtlwsbkskc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.svipenyu.cn/Article/details/gtvjhojzdw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.haohaochexian.top/Article/details/gtqcfduczn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hysaishi.cn/Article/details/gtaponolzt.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbqntraup.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtkvbmdybp.html

K. JSON 与序列化
来源：http://dali.hfpthk.cn/Article/details/gttgdiisjx.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtwbxxssjr.html

[K01] 对象转 JSON 字符串
来源：http://dali.sweek.top/Article/details/gtfvghyadl.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.vqdsnc.cn/Article/details/gtyyzulqtk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.bjfxy.top/Article/details/gtsiqqhvnt.html

JS:   JSON.stringify(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsvdsbrmt.html

TS:   JSON.stringify(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtuymrdpkd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.vqdsnc.cn/Article/details/gtqhbvnvca.html

Go:   json.Marshal(obj)
来源：http://dali.aibaodan.cn/Article/details/gtvaizpdfd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinqigufen.top/Article/details/gtcinjuqup.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.aizwys.cn/Article/details/gtlzqjxumw.html

[K02] JSON 字符串转对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gtypyapzda.html

Py:   json.loads(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtzqzygwvb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhongyouzk.top/Article/details/gtsjymwdyl.html

JS:   JSON.parse(s)
来源：http://dali.yj202588.top/Article/details/gtvgjjnfhp.html

TS:   JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gtvpsprfgn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sxryk.cn/Article/details/gtjqcbsrwe.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.daxiang520.top/Article/details/gtlkurptar.html

Ruby: JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gtsaualdwz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.svipenyu.cn/Article/details/gtwgnimfzb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ybcxt.top/Article/details/gtdjexrfis.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yonumen.top/Article/details/gtxzvsenqx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yuanzhike.top/Article/details/gtkvkgfvlo.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258888.top/Article/details/gtevbcksjw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnwxkpfyx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.fzhhl.top/Article/details/gtnksedkiv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.0kj1m.cn/Article/details/gtqauiskuv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ydzc1.top/Article/details/gtyekoopqs.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yuanzhike.top/Article/details/gtuwhgpkoo.html

[K04] 读取 JSON 文件
来源：http://dali.fengsongda.top/Article/details/gtakfsgdla.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.meibo888.top/Article/details/gtvifcwhdh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yonumen.top/Article/details/gtodadfzqo.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cdnleiting.top/Article/details/gteancxrvg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258.top/Article/details/gtkjwpazfa.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.chenjidiqi.icu/Article/details/gtyvauazrh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nwbrower.top/Article/details/gtehlwwtqm.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxodaozjl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nanxinkj.top/Article/details/gtzkawjsvx.html

[K05] 深拷贝对象
来源：http://dali.andypj.xyz/Article/details/gtfppjcsqf.html

Py:   copy.deepcopy(obj)
来源：http://dali.nanxinkj.top/Article/details/gtmvyhrezq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hnqzz.top/Article/details/gttiqbduuf.html

JS:   structuredClone(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtktkjuvqn.html

TS:   structuredClone(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbpucepfd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.gogol.net.cn/Article/details/gtowdcubgs.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.kuanghao11.cn/Article/details/gtthhvpovn.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sysykeji.top/Article/details/gttfxdpzqz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.guowangkeji.top/Article/details/gtooqwxhpd.html

[K06] 解析 URL 查询串
来源：http://dali.jinqigfzy.top/Article/details/gtdxtimyis.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinqigufen.top/Article/details/gtvjxrfnsz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hnxiangtu.top/Article/details/gtkedjyivq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cheryme.top/Article/details/gtuuzugpyc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgufenzy.top/Article/details/gthipkdbhh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.dashuyun.cn/Article/details/gtiatfioig.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shangyingyoupin.top/Article/details/gtlsfdpqlc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ydzc1.top/Article/details/gtkxcbfmau.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.vqdsnc.cn/Article/details/gtjpudbnzj.html

[K07] 进制转换
来源：http://dali.hywenlv.cn/Article/details/gtmnwguhsn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gtgirqsvqs.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.316326.xyz/Article/details/gtwxtjngkp.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gthrffwkmt.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttkayymdh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtzordkzrb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.birdmap.top/Article/details/gtlgakenfb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hywenlv.cn/Article/details/gtlevqjvbo.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtxunnkcyu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hnqzz.top/Article/details/gtlrrczwli.html

Py:   pickle.dumps(obj)
来源：http://dali.jianghu66.top/Article/details/gtayfqbaul.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.daria6918.cn/Article/details/gtvzegyhrb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cheryme.top/Article/details/gtijsbegwx.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shuidangran.top/Article/details/gtbuayouxm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj20258888.top/Article/details/gtkduinysl.html

Go:   encoding/gob
来源：http://dali.zhongyouzk.top/Article/details/gttjasvphn.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjdxgqtkj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.wangdashe.top/Article/details/gtswqltpeu.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgrvrnlok.html

L. 网络请求
来源：http://dali.pycfn.com/Article/details/gthxijsfpb.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtjgyhwifw.html

[L01] 发送 GET 请求
来源：http://dali.shanyushiyangtech.top/Article/details/gtqepqrcfq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ppjwa.cn/Article/details/gtkinqvqjg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinqigufen.top/Article/details/gtinkqgshr.html

JS:   await fetch(url)
来源：http://dali.xziqi.cn/Article/details/gtarcwpdyz.html

TS:   await fetch(url)
来源：http://dali.yangfankeji.com/Article/details/gtvycuhdsa.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.guannengcc.top/Article/details/gtvxnjedsq.html

Go:   resp, err := http.Get(url)
来源：http://dali.nanxuanxn.top/Article/details/gtwnrrvyzx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jlsjyb.cn/Article/details/gtxmriinww.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.smart0.xyz/Article/details/gtiugrulbw.html

[L02] 发送 POST JSON
来源：http://dali.yuxming.cn/Article/details/gtzmjvxzgk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shanyushiyangtech.top/Article/details/gtgqqgehgk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yj20258888.top/Article/details/gtuxbfftgx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiqksfniq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.redwolf501.top/Article/details/gtwndttsro.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jiagoushi.top/Article/details/gtyxjjrvin.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.meibo888.top/Article/details/gtjdskkzvd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhoulong.xyz/Article/details/gthkrmdsbt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cashguo.top/Article/details/gthvmlzlmk.html

[L03] 设置自定义请求头
来源：http://dali.cashguo.top/Article/details/gttvnvkldz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hnxiangtu.top/Article/details/gtubccflya.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yonumen.top/Article/details/gtnuufjtrl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbyvcxevp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hywenlv.cn/Article/details/gtvuitdkro.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.tanke756.top/Article/details/gtxvdukntp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cqqwz.cn/Article/details/gtzukemwaf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gaohongyu789.top/Article/details/gtkfgmlobg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhengqikj.top/Article/details/gtmrlgmuco.html

[L04] 设置超时
来源：http://dali.hfpthk.cn/Article/details/gtphvzarqq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinqigfzy.top/Article/details/gtaeepzmpk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.nwbrower.top/Article/details/gtfbizfqaz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yvedp.cn/Article/details/gtihcqeldg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.vqdsnc.cn/Article/details/gthmhojsio.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ehwqpu.com/Article/details/gtdpykskas.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.guannengcc.top/Article/details/gtmpxgzlij.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.andypj.xyz/Article/details/gtisrgfila.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jyoumei.cn/Article/details/gtehmlcdkg.html

[L05] 上传文件（multipart）
来源：http://dali.jyoumei.cn/Article/details/gtbfqsmbzf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ivvv.top/Article/details/gtcaathxcn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.fzhhl.top/Article/details/gtdygpebfo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.aibaodan.cn/Article/details/gtyvobcyhn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhengqikj.top/Article/details/gtmmflacce.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.dianchejie.cn/Article/details/gtllrmuxea.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sxryk.cn/Article/details/gtpvxvshmz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.daria6918.cn/Article/details/gtnorkcdcr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ybcxt.top/Article/details/gtteqnvoeu.html

[L06] 解析响应为 JSON
来源：http://dali.yj20258888.top/Article/details/gtwnafpbyu.html

Py:   resp.json()
来源：http://dali.jinghuilouyu.cn/Article/details/gthtxcbkad.html

PHP:  json_decode($body, true);
来源：http://dali.tanke756.top/Article/details/gtkfeluhzq.html

JS:   await resp.json()
来源：http://dali.jinqigufen.top/Article/details/gtrhvkpywz.html

TS:   await resp.json()
来源：http://dali.shuidangran.top/Article/details/gtpqyrtatw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.fengsongda.top/Article/details/gtncdyhapq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtffyuytae.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zdqjudy.top/Article/details/gtbbqlcsbh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cqqwz.cn/Article/details/gtpeltrqnv.html

[L07] 处理 HTTP 状态码
来源：http://dali.aibaodan.cn/Article/details/gtesxlpfvm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xuetiantiany.cn/Article/details/gtlureacgw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.dianchejie.cn/Article/details/gtxuagyumf.html

JS:   resp.ok;  resp.status
来源：http://dali.meibo888.top/Article/details/gtcqauwufb.html

TS:   resp.ok;  resp.status
来源：http://dali.tian-w.cn/Article/details/gtxxziwaff.html

Java: resp.statusCode()
来源：http://dali.redwolf501.top/Article/details/gtwmtutlbt.html

Go:   resp.StatusCode
来源：http://dali.tanke756.top/Article/details/gtvymbqnoj.html

Ruby: resp.code.to_i
来源：http://dali.daria6918.cn/Article/details/gtqixsnben.html

C#:   (int)resp.StatusCode
来源：http://dali.yueranfly.top/Article/details/gtqlsedlzb.html

[L08] 并发请求多个地址
来源：http://dali.haohaochexian.top/Article/details/gtjpinvgyo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.c1oappe.top/Article/details/gtplrjttgv.html

PHP:  curl_multi_init() 系列
来源：http://dali.shangyingyoupin.top/Article/details/gtkwweiook.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gtimnvpuua.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenzaomai.com/Article/details/gtdsrhrnwm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.dashuyun.cn/Article/details/gtgcchwgjj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinqigfzy.top/Article/details/gtyllpaiso.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.wangshuangyany.cn/Article/details/gttstbwexn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gtimughvad.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gteujgtnrf.html

M. 命令行 / 进程 / 环境
来源：http://dali.cqqwz.cn/Article/details/gtpohjeaze.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtfmjpewox.html

[M01] 读取命令行参数
来源：http://dali.vqdsnc.cn/Article/details/gtuskjbixn.html

Py:   sys.argv[1:]
来源：http://dali.hnqzz.top/Article/details/gtyfzrpgxs.html

PHP:  $argv;  $argc;
来源：http://dali.wangshuangyany.cn/Article/details/gtdmfagoyh.html

JS:   process.argv.slice(2)
来源：http://dali.sweek.top/Article/details/gtgfzhnuwa.html

TS:   process.argv.slice(2)
来源：http://dali.ppjwa.cn/Article/details/gtscaphxbh.html

Java: args 数组（main 方法参数）
来源：http://dali.daxiang520.top/Article/details/gtgxidsarn.html

Go:   os.Args[1:]
来源：http://dali.zhiwuduotai.top/Article/details/gtovtqxvor.html

Ruby: ARGV
来源：http://dali.tanke756.top/Article/details/gtjjzprozo.html

C#:   args 数组（Main 方法参数）
来源：http://dali.vqdsnc.cn/Article/details/gtqoflhoxm.html

[M02] 读取环境变量
来源：http://dali.aibaodan.cn/Article/details/gtfvsykiud.html

Py:   os.environ.get("HOME")
来源：http://dali.havefunace.top/Article/details/gtfrkerraa.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.feifeiyinyue.top/Article/details/gtvjpzclit.html

JS:   process.env.HOME
来源：http://dali.shanyushiyangtech.top/Article/details/gtjzcwmqmx.html

TS:   process.env.HOME
来源：http://dali.quarkkingdee.top/Article/details/gtrfnxqhgc.html

Java: System.getenv("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gtgdxpmpnr.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yangfankeji.com/Article/details/gtkppjsvba.html

Ruby: ENV["HOME"]
来源：http://dali.daxiang520.top/Article/details/gtqctyplzv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.meibo888.top/Article/details/gtuprvjyje.html

[M03] 执行外部命令
来源：http://dali.aizwys.cn/Article/details/gtfqdsdsol.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhengqikj.top/Article/details/gtimexckdd.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gaohongyu789.top/Article/details/gtywvmyout.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangshuangyany.cn/Article/details/gtuipsngrx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.guowangkeji.top/Article/details/gtyhvluuze.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.kuanghao11.cn/Article/details/gttthfhvjw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sysykeji.top/Article/details/gttiirtdzi.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sxryk.cn/Article/details/gtlpondnis.html

C#:   Process.Start("ls", "-l");
来源：http://dali.feifeiyinyue.top/Article/details/gtobpyaltz.html

[M04] 获取当前工作目录
来源：http://dali.c1oappe.top/Article/details/gtnlmscuvh.html

Py:   os.getcwd()
来源：http://dali.jiagoushi.top/Article/details/gtsnhmucqy.html

PHP:  getcwd();
来源：http://dali.ydzc1.top/Article/details/gtjxiueued.html

JS:   process.cwd()
来源：http://dali.cheryme.top/Article/details/gtftbaaulk.html

TS:   process.cwd()
来源：http://dali.chenjidiqi.icu/Article/details/gtsxpcfizb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ivvv.top/Article/details/gtmmzoqrau.html

Go:   os.Getwd()
来源：http://dali.fengsongda.top/Article/details/gtkvfimjoe.html

Ruby: Dir.pwd
来源：http://dali.kuanghao11.cn/Article/details/gtkypicirm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gotoacloud.top/Article/details/gtbuwezkee.html

[M05] 设置退出码
来源：http://dali.cqqwz.cn/Article/details/gtqivlvhhc.html

Py:   sys.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtphyciykw.html

PHP:  exit(1);
来源：http://dali.xziqi.cn/Article/details/gtggqokuwn.html


<!-- 参考信息 -->