代发 wailian999

Ruby: s.scan(/error/i)
来源：http://dali.xuetiantiany.cn/Article/details/gtiyvreaxu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gotoacloud.top/Article/details/gtzjdhxdje.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.iojbl.cn/Article/details/gtkluqluuj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xylfe.cn/Article/details/gtxzkobubt.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shzxlz.cn/Article/details/gttaisznbn.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.0kj1m.cn/Article/details/gtyosqhzhu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.havefunace.top/Article/details/gtxwwgpclu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinghuilouyu.cn/Article/details/gtefyibebs.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinqigfzy.top/Article/details/gtocdmbtjb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shuidangran.top/Article/details/gtbolriajs.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.kuanghao11.cn/Article/details/gtticfgqwg.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtrzfmseez.html

J. 日期与时间
来源：http://dali.cqqwz.cn/Article/details/gtumtztrma.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gthfxsgjhm.html

[J01] 获取当前时间
来源：http://dali.wangdashe.top/Article/details/gtijxmjxlm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cdnleiting.top/Article/details/gtthbhddte.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sxryk.cn/Article/details/gtnajxfrrp.html

JS:   new Date();  Date.now()
来源：http://dali.nwbrower.top/Article/details/gtwduamslh.html

TS:   new Date();  Date.now()
来源：http://dali.jinqigfzy.top/Article/details/gtmepocawk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shanyushiyangtech.top/Article/details/gtvhguchha.html

Go:   time.Now()
来源：http://dali.hnqzz.top/Article/details/gtcjqgsvgp.html

Ruby: Time.now
来源：http://dali.jinyuanbaomall.cn/Article/details/gtavmvgsjb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cdnleiting.top/Article/details/gtsvklfckb.html

[J02] 格式化输出
来源：http://dali.jinghuilouyu.cn/Article/details/gtmmnvmtgg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hammf.cn/Article/details/gtrkjimltz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.pengpengdd.cyou/Article/details/gtvjyzywjn.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinqigfzy.top/Article/details/gtyckjldcb.html

TS:   d.toISOString()
来源：http://dali.yongpay.top/Article/details/gtmcgarvym.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.c1oappe.top/Article/details/gtwnqakhui.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinqigfzy.top/Article/details/gtgmzmixsk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.bjfxy.top/Article/details/gtnueooavp.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlyjegdrz.html

[J03] 字符串解析为日期
来源：http://dali.fzhhl.top/Article/details/gtvyckcifj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiygxdlrv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.chenlongwang.top/Article/details/gtnmzetaiz.html

JS:   new Date("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gtfgtxdtyw.html

TS:   new Date("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtjqomxggk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gtilrxsosw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gtqdowwxjg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gtodmxiquh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenzaomai.com/Article/details/gtegwojojk.html

[J04] 时间戳与日期互转
来源：http://dali.xylfe.cn/Article/details/gtdyrsvrna.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sweek.top/Article/details/gtwyblhwaf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cashguo.top/Article/details/gtcorqoere.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfsacdbgn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinghuilouyu.cn/Article/details/gtctxcufnd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ehwqpu.com/Article/details/gtnnbggsoc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtbqbodqya.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aibaodan.cn/Article/details/gtvhctrydv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.tianlin.xyz/Article/details/gtjljtyscd.html

[J05] 时间加减（加 7 天）
来源：http://dali.jianghu66.top/Article/details/gtutrkcwjv.html

Py:   now + timedelta(days=7)
来源：http://dali.ybcxt.top/Article/details/gtgnoakcke.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yuxming.cn/Article/details/gthqvfcavt.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuanzhike.top/Article/details/gtzjweyazx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenjidiqi.icu/Article/details/gtlxdbccsq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jiagoushi.top/Article/details/gtobyjmuxd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.pengpengdd.cyou/Article/details/gtbpzvgqux.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jlsjyb.cn/Article/details/gtxspcfnwy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.daxiang520.top/Article/details/gtyztwrrcu.html

[J06] 计算两时间之差
来源：http://dali.ehwqpu.com/Article/details/gtxgcucpdb.html

Py:   (end - start).total_seconds()
来源：http://dali.meibo888.top/Article/details/gtdaccuqlh.html

PHP:  $end->diff($start)->days;
来源：http://dali.gotoacloud.top/Article/details/gtsbnansvc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jqgfzy.top/Article/details/gtlylyihii.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj20258888.top/Article/details/gtavucpmlk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hysaishi.cn/Article/details/gtyeprziuz.html

Go:   end.Sub(start).Hours()
来源：http://dali.daxiang520.top/Article/details/gtgakierjj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.svipenyu.cn/Article/details/gtwowcfsfz.html

C#:   (end - start).TotalSeconds
来源：http://dali.tanke756.top/Article/details/gthpoiyymt.html

[J07] 比较两个日期
来源：http://dali.wangshuangyany.cn/Article/details/gtbfjnnjcc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj20258888.top/Article/details/gtljmbybmy.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ydzc1.top/Article/details/gtqridfujq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cdnleiting.top/Article/details/gtbnizbwhx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenlongwang.top/Article/details/gtewdhwtyf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ehwqpu.com/Article/details/gtnudqhkjw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.iojbl.cn/Article/details/gtphehwlar.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinqigufen.top/Article/details/gtlyvbkqnt.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gtsmtqmaqd.html

[J08] 提取年月日与星期
来源：http://dali.sysykeji.top/Article/details/gtikcwwwqz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.aizwys.cn/Article/details/gtieotbxsk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.andypj.xyz/Article/details/gtcfocsmfe.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gotoacloud.top/Article/details/gtjynckehs.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jiagoushi.top/Article/details/gtrhqpvtfu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yuanzhike.top/Article/details/gtrubtxadk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jqgfzy.top/Article/details/gtaggomoay.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.aibaodan.cn/Article/details/gtiukbvbwr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hnxiangtu.top/Article/details/gtbgawcfra.html

[J09] 时区处理
来源：http://dali.jinghuilouyu.cn/Article/details/gtpnxorusj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nwbrower.top/Article/details/gtbhcsvsef.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhijiandao.cn/Article/details/gtnsgzpyep.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtapblvnyx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gtsoxzhfak.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yj20258.top/Article/details/gtngsbkqzr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtelekwqmo.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cashguo.top/Article/details/gtpmvvizji.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hysaishi.cn/Article/details/gtbzyrhwou.html

[J10] 取今天 / 本月第一天
来源：http://dali.yuxming.cn/Article/details/gtzdekyliq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.dashuyun.cn/Article/details/gtlmgjzikd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhixingplan.top/Article/details/gthrjlozae.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtlyxmifwy.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj202588.top/Article/details/gtrzcogtge.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.9152youxi.cn/Article/details/gtmlgndmvd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yvedp.cn/Article/details/gtkdkdckpe.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhiwuduotai.top/Article/details/gtdrevremy.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.nanxinkj.top/Article/details/gttvxxfouo.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtklbssztn.html

K. JSON 与序列化
来源：http://dali.zhixingplan.top/Article/details/gtzisvpyff.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gttozzaiyw.html

[K01] 对象转 JSON 字符串
来源：http://dali.fzhhl.top/Article/details/gtvemucmic.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cdnleiting.top/Article/details/gtavfbkxpn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ivvv.top/Article/details/gtgkpifvpt.html

JS:   JSON.stringify(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtcshukczy.html

TS:   JSON.stringify(obj)
来源：http://dali.havefunace.top/Article/details/gtspzquman.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shzxlz.cn/Article/details/gtmxxhaupv.html

Go:   json.Marshal(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gttpgzvknb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.snrcjt.cn/Article/details/gtnxuglqvi.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jianghu66.top/Article/details/gtjxaimmkz.html

[K02] JSON 字符串转对象
来源：http://dali.yj20258888.top/Article/details/gtqmjtsmyc.html

Py:   json.loads(s)
来源：http://dali.ybcxt.top/Article/details/gtrzrhfwpm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sufxvd.cn/Article/details/gtcycwonry.html

JS:   JSON.parse(s)
来源：http://dali.dianchejie.cn/Article/details/gtybaxogvi.html

TS:   JSON.parse(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnimjztby.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gtqysywldl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xylfe.cn/Article/details/gttryaglzo.html

Ruby: JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gthycrinqx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.guowangkeji.top/Article/details/gtblsloghu.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jqgufenzy.top/Article/details/gtinzxhilt.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xziqi.cn/Article/details/gteudoqpel.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yueranfly.top/Article/details/gtlzdjkmqg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tianlin.xyz/Article/details/gtlnuiltil.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.redwolf501.top/Article/details/gtkusnqvqh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.smart0.xyz/Article/details/gtmkccbvbn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hywenlv.cn/Article/details/gtqcrdlrvi.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtqcfyelbn.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.wangshuangyany.cn/Article/details/gtgxkrraic.html

[K04] 读取 JSON 文件
来源：http://dali.tian-w.cn/Article/details/gthxyuqfbk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhoulong.xyz/Article/details/gtlxazmiqb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hfpthk.cn/Article/details/gtsubcowns.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jyoumei.cn/Article/details/gtjmkqjwgz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hammf.cn/Article/details/gttyuzoapw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sweek.top/Article/details/gthariwnkw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ydzc1.top/Article/details/gtsigockei.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.tianlin.xyz/Article/details/gtbuqhuvux.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.havefunace.top/Article/details/gtzctdaxju.html

[K05] 深拷贝对象
来源：http://dali.yj202588.top/Article/details/gtbttlzxug.html

Py:   copy.deepcopy(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtchtjmqff.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ppjwa.cn/Article/details/gtzianotny.html

JS:   structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gtiywnpijj.html

TS:   structuredClone(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtoylzqaqy.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenlongwang.top/Article/details/gtwehdaskw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.mhx1999.top/Article/details/gtrnthjozd.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.9152youxi.cn/Article/details/gthmlgdbnj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nanxinkj.top/Article/details/gtcouwwqmg.html

[K06] 解析 URL 查询串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzdfyaska.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hysaishi.cn/Article/details/gtxfomsykm.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yuanzhike.top/Article/details/gtmprfkaui.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxuanxn.top/Article/details/gtvblfwrbo.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxuanxn.top/Article/details/gtlhgearyi.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yongpay.top/Article/details/gtepxlsunp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gtlucklskj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.iojbl.cn/Article/details/gtednrgprb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.mhx1999.top/Article/details/gtlkynghri.html

[K07] 进制转换
来源：http://dali.9152youxi.cn/Article/details/gtwnikgrhj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gtkcaluyxu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jyoumei.cn/Article/details/gtwoyqtoqk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfmgblylm.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gtkbrzazay.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gtpsjyiuxe.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvmcwgjyi.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yuxming.cn/Article/details/gtsuqtjgan.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtevgesfjk.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.daxiang520.top/Article/details/gtkbcwuyma.html

Py:   pickle.dumps(obj)
来源：http://dali.aibaodan.cn/Article/details/gtewifvelv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtiwpooumk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cheryme.top/Article/details/gtqkhdvozi.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.pengpengdd.cyou/Article/details/gtiwoikdfp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqymdcazh.html

Go:   encoding/gob
来源：http://dali.iojbl.cn/Article/details/gtwlqroakj.html

Ruby: Marshal.dump(obj)
来源：http://dali.aibaodan.cn/Article/details/gtpqmssivv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.svipenyu.cn/Article/details/gtzvzidsgr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtsezyopio.html

L. 网络请求
来源：http://dali.ehwqpu.com/Article/details/gtcaxxarge.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtodaywyvq.html

[L01] 发送 GET 请求
来源：http://dali.cheryme.top/Article/details/gtgvzlbrur.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.fengsongda.top/Article/details/gtpaoaxrkl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.0kj1m.cn/Article/details/gtwjtcbiyd.html

JS:   await fetch(url)
来源：http://dali.havefunace.top/Article/details/gtynsgmeaf.html

TS:   await fetch(url)
来源：http://dali.yj202588.top/Article/details/gtielivlcn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.bjfxy.top/Article/details/gtklvstlgz.html

Go:   resp, err := http.Get(url)
来源：http://dali.gotoacloud.top/Article/details/gtkhrlhpzj.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gzhubu.top/Article/details/gttugsuxhl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gaohongyu789.top/Article/details/gtjdyprgbh.html

[L02] 发送 POST JSON
来源：http://dali.guannengcc.top/Article/details/gtytmtygge.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.nwbrower.top/Article/details/gtfhttieoa.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.feifeiyinyue.top/Article/details/gtkisgevsz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yanxiufei.cn/Article/details/gtvuttuqya.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pycfn.com/Article/details/gttkbvachl.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cashguo.top/Article/details/gtewdzsqxb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xylfe.cn/Article/details/gtrmmjotwd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hnxiangtu.top/Article/details/gtpumfgyyg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sxryk.cn/Article/details/gtkimwptoi.html

[L03] 设置自定义请求头
来源：http://dali.shangyingyoupin.top/Article/details/gtgvbzsenc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.daxiang520.top/Article/details/gtoyjgszmf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.bjfxy.top/Article/details/gthklxakos.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xziqi.cn/Article/details/gtjzmengjy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.bjfxy.top/Article/details/gttpxptixe.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.kuanghao11.cn/Article/details/gtpqdwerun.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yuanzhike.top/Article/details/gttqhgvfer.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gotoacloud.top/Article/details/gtgbasuvft.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xylfe.cn/Article/details/gtkvzniroz.html

[L04] 设置超时
来源：http://dali.nanxinkj.top/Article/details/gtjdfhtzry.html

Py:   requests.get(url, timeout=5)
来源：http://dali.quarkkingdee.top/Article/details/gtaervsvnq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhixingplan.top/Article/details/gtmkayyoqj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ppjwa.cn/Article/details/gtcgtdhowd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.316326.xyz/Article/details/gtkjuxdphe.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cdnleiting.top/Article/details/gttbwebjkf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shzxlz.cn/Article/details/gtytzwxape.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.tian-w.cn/Article/details/gtwpsmbhwu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gaohongyu789.top/Article/details/gtfqfqtzni.html

[L05] 上传文件（multipart）
来源：http://dali.yj20258888.top/Article/details/gtwwqiphno.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtspigudhv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.snrcjt.cn/Article/details/gtnhbuwpgq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.guannengcc.top/Article/details/gtdflugjyx.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhongyouzk.top/Article/details/gtwspzmbea.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.daxiang520.top/Article/details/gtwfnreweq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yongpay.top/Article/details/gtxqilpfdv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gogol.net.cn/Article/details/gtjhxhabcn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.wangdashe.top/Article/details/gtfcocoihz.html

[L06] 解析响应为 JSON
来源：http://dali.xylfe.cn/Article/details/gtomksajwx.html

Py:   resp.json()
来源：http://dali.ppjwa.cn/Article/details/gtnygalcuk.html

PHP:  json_decode($body, true);
来源：http://dali.cashguo.top/Article/details/gtwnkakzbg.html

JS:   await resp.json()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkdetzvto.html

TS:   await resp.json()
来源：http://dali.xylfe.cn/Article/details/gtmrlfpjkq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cqqwz.cn/Article/details/gtocjorhsu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.smart0.xyz/Article/details/gtezofihpl.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhoulong.xyz/Article/details/gtwzyjwoni.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xylfe.cn/Article/details/gtycnavofu.html

[L07] 处理 HTTP 状态码
来源：http://dali.shzxlz.cn/Article/details/gtswalifcq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.wangshuangyany.cn/Article/details/gtecuxoniw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.fzhhl.top/Article/details/gtcxlelqya.html

JS:   resp.ok;  resp.status
来源：http://dali.yj20258888.top/Article/details/gtweyfzuiy.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gtqdulbbrk.html

Java: resp.statusCode()
来源：http://dali.yanxiufei.cn/Article/details/gtqtqsnftv.html

Go:   resp.StatusCode
来源：http://dali.nanxuanxn.top/Article/details/gtmdfpzjgf.html

Ruby: resp.code.to_i
来源：http://dali.havefunace.top/Article/details/gtdcpjpcvx.html

C#:   (int)resp.StatusCode
来源：http://dali.xylfe.cn/Article/details/gtqdxadfmy.html

[L08] 并发请求多个地址
来源：http://dali.daria6918.cn/Article/details/gtqyxnzqso.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.kuanghao11.cn/Article/details/gtcphggkgi.html

PHP:  curl_multi_init() 系列
来源：http://dali.ybcxt.top/Article/details/gtcllyjmdy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenlongwang.top/Article/details/gtkrtqbkgc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.birdmap.top/Article/details/gtivrlcpug.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yongpay.top/Article/details/gtramxxqmk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.pengpengdd.cyou/Article/details/gtfknubkce.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jiagoushi.top/Article/details/gtllnwldjz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gtpunomggm.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtomofyxkc.html

M. 命令行 / 进程 / 环境
来源：http://dali.yj20258.top/Article/details/gtyfgkybzc.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtcxngjozl.html

[M01] 读取命令行参数
来源：http://dali.tian-w.cn/Article/details/gttmmwcuql.html

Py:   sys.argv[1:]
来源：http://dali.aibaodan.cn/Article/details/gtjplyiobb.html

PHP:  $argv;  $argc;
来源：http://dali.yuxming.cn/Article/details/gtlsojavky.html

JS:   process.argv.slice(2)
来源：http://dali.zhixingplan.top/Article/details/gthabluywm.html

TS:   process.argv.slice(2)
来源：http://dali.quarkkingdee.top/Article/details/gtcxqqhyii.html

Java: args 数组（main 方法参数）
来源：http://dali.sysykeji.top/Article/details/gtzksvzkdn.html

Go:   os.Args[1:]
来源：http://dali.nanxuanxn.top/Article/details/gtlijpnzbc.html

Ruby: ARGV
来源：http://dali.chenzaomai.com/Article/details/gtqqvuwikv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ybcxt.top/Article/details/gtgtejbhrq.html

[M02] 读取环境变量
来源：http://dali.cucudq.cn/Article/details/gtjythcxeq.html

Py:   os.environ.get("HOME")
来源：http://dali.cqqwz.cn/Article/details/gtjtygdrqz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.9152youxi.cn/Article/details/gtizqhvbav.html

JS:   process.env.HOME
来源：http://dali.316326.xyz/Article/details/gtrgiwocuk.html

TS:   process.env.HOME
来源：http://dali.pycfn.com/Article/details/gtobeazsrn.html

Java: System.getenv("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gtxfschmek.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hywenlv.cn/Article/details/gtwtvftxeb.html

Ruby: ENV["HOME"]
来源：http://dali.wangshuangyany.cn/Article/details/gtdxctlnwn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtbpncjobv.html

[M03] 执行外部命令
来源：http://dali.jqgufenzy.top/Article/details/gtdoldhrds.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ehwqpu.com/Article/details/gtypcnbrzt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sysykeji.top/Article/details/gtylnzsifb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.fzhhl.top/Article/details/gtzzapcnjz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yangfankeji.com/Article/details/gtmhhlozik.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yj202588.top/Article/details/gthtgpttdy.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.haohaochexian.top/Article/details/gtobcgvvmb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tian-w.cn/Article/details/gtjjitjlyo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.havefunace.top/Article/details/gtywshcehx.html

[M04] 获取当前工作目录
来源：http://dali.yangfankeji.com/Article/details/gtshmmtfer.html

Py:   os.getcwd()
来源：http://dali.jianghu66.top/Article/details/gtbeixsjiy.html

PHP:  getcwd();
来源：http://dali.pengpengdd.cyou/Article/details/gtxdigtnxq.html

JS:   process.cwd()
来源：http://dali.sweek.top/Article/details/gtfocdixzo.html

TS:   process.cwd()
来源：http://dali.jiagoushi.top/Article/details/gttatbsbms.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zycfv.cn/Article/details/gtcdqzmoxp.html

Go:   os.Getwd()
来源：http://dali.yvedp.cn/Article/details/gtjasfioyw.html

Ruby: Dir.pwd
来源：http://dali.mhx1999.top/Article/details/gtynjenuhx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sufxvd.cn/Article/details/gtlgosidav.html

[M05] 设置退出码
来源：http://dali.jqgufenzy.top/Article/details/gtaquznzni.html

Py:   sys.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtjxjtalil.html

PHP:  exit(1);
来源：http://dali.yanxiufei.cn/Article/details/gtmgliriwn.html

JS:   process.exit(1)
来源：http://dali.wangdashe.top/Article/details/gtuutavzph.html

TS:   process.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtcibzjjaz.html

Java: System.exit(1)
来源：http://dali.nwbrower.top/Article/details/gtmyqlexwt.html

Go:   os.Exit(1)
来源：http://dali.hysaishi.cn/Article/details/gtrpyxrtyi.html


<!-- 参考信息 -->