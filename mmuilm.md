代发 wailian999

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gzhubu.top/Article/details/gtagsjmgpf.html

[I07] 忽略大小写与多行模式
来源：http://dali.xylfe.cn/Article/details/gtczofiqrs.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hammf.cn/Article/details/gtrjrsiorw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gzhubu.top/Article/details/gtqpyekuhy.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yanxiufei.cn/Article/details/gtrpmljnyq.html

TS:   /error/gim
来源：http://dali.aizwys.cn/Article/details/gtgjuscnsw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jianghu66.top/Article/details/gtkusgqckv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yvedp.cn/Article/details/gtpdaxykkg.html

Ruby: s.scan(/error/i)
来源：http://dali.jinqigfzy.top/Article/details/gthnzxijnn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gzhubu.top/Article/details/gtxirosove.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhongyouzk.top/Article/details/gttwuyvkyu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xziqi.cn/Article/details/gtjtzsqian.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jyoumei.cn/Article/details/gtapvzcisr.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgfzy.top/Article/details/gthvpxlexx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dashuyun.cn/Article/details/gtnpzfbomm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xuetiantiany.cn/Article/details/gtawboseli.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.quarkkingdee.top/Article/details/gtwxpgkkwn.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zycfv.cn/Article/details/gtibophrsf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jlsjyb.cn/Article/details/gtwpagaveb.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtyefrffgr.html

J. 日期与时间
来源：http://dali.zhoulong.xyz/Article/details/gtxadojfnl.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtnayalvwm.html

[J01] 获取当前时间
来源：http://dali.andypj.xyz/Article/details/gtvzkwoimk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nwbrower.top/Article/details/gtouiqjmlv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.snrcjt.cn/Article/details/gtdepmegty.html

JS:   new Date();  Date.now()
来源：http://dali.gotoacloud.top/Article/details/gtxhunifbf.html

TS:   new Date();  Date.now()
来源：http://dali.hywenlv.cn/Article/details/gtqbexfozj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.wangshuangyany.cn/Article/details/gtqselwvqd.html

Go:   time.Now()
来源：http://dali.ybcxt.top/Article/details/gtpufyzjnj.html

Ruby: Time.now
来源：http://dali.yuxming.cn/Article/details/gttnkffmsu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cucudq.cn/Article/details/gtmrskbyyu.html

[J02] 格式化输出
来源：http://dali.vqdsnc.cn/Article/details/gtwwpfwcuv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yanxiufei.cn/Article/details/gtsfufilqk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinqigfzy.top/Article/details/gtjqgqibpx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.dashuyun.cn/Article/details/gtllwjzpna.html

TS:   d.toISOString()
来源：http://dali.316326.xyz/Article/details/gtmtieybgj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.guowangkeji.top/Article/details/gtzfikmouh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.havefunace.top/Article/details/gtwzpzdmpt.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jyoumei.cn/Article/details/gtuxwnkkla.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.havefunace.top/Article/details/gthrlcnbqv.html

[J03] 字符串解析为日期
来源：http://dali.haohaochexian.top/Article/details/gtzvsjnnnx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jiagoushi.top/Article/details/gtizstrllu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.pycfn.com/Article/details/gtvgbemipx.html

JS:   new Date("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gtnzqvwmbb.html

TS:   new Date("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gtqvgrnojq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gtlnanjfhc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gtocgjxgok.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gtnqkhceae.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.c1oappe.top/Article/details/gtdofxmroc.html

[J04] 时间戳与日期互转
来源：http://dali.smart0.xyz/Article/details/gtvomvoryb.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.9152youxi.cn/Article/details/gtgkaniukk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shuidangran.top/Article/details/gtfpflhwvt.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gogol.net.cn/Article/details/gtekotcgba.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinqigufen.top/Article/details/gtfkyrrlvu.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yanxiufei.cn/Article/details/gtsggpauaq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hammf.cn/Article/details/gtpflsuazu.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gtovktiebz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqmnucctr.html

[J05] 时间加减（加 7 天）
来源：http://dali.jianghu66.top/Article/details/gtekbonpir.html

Py:   now + timedelta(days=7)
来源：http://dali.ivvv.top/Article/details/gthymvuvlu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hysaishi.cn/Article/details/gtaugsdjnv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daxiang520.top/Article/details/gtlgvxdtwh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ybcxt.top/Article/details/gtfvoewtcn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.redwolf501.top/Article/details/gtzkgqlbii.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.wangdashe.top/Article/details/gtalnfyqse.html

Ruby: Time.now + 7 * 86400
来源：http://dali.tianlin.xyz/Article/details/gtvojmfliq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cdnleiting.top/Article/details/gtbtdyuafg.html

[J06] 计算两时间之差
来源：http://dali.zhijiandao.cn/Article/details/gtxrkkdcnk.html

Py:   (end - start).total_seconds()
来源：http://dali.tian-w.cn/Article/details/gtzwdehwdr.html

PHP:  $end->diff($start)->days;
来源：http://dali.hnxiangtu.top/Article/details/gtffimczxn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sweek.top/Article/details/gtqvmziodc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.chenjidiqi.icu/Article/details/gtiiaotpad.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shanyushiyangtech.top/Article/details/gtqdtoddrt.html

Go:   end.Sub(start).Hours()
来源：http://dali.meibo888.top/Article/details/gtwhbebgcr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hywenlv.cn/Article/details/gtrdcirkck.html

C#:   (end - start).TotalSeconds
来源：http://dali.sysykeji.top/Article/details/gtaepxiqkq.html

[J07] 比较两个日期
来源：http://dali.hysaishi.cn/Article/details/gtjhaapesl.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.pengpengdd.cyou/Article/details/gthyfvpknd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cheryme.top/Article/details/gticwvzbtv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yvedp.cn/Article/details/gtuyajturf.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenlongwang.top/Article/details/gtxeuzhcpm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.nanxinkj.top/Article/details/gtorbhsvqx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.mhx1999.top/Article/details/gtpfpzvzwl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gtnolfssnp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hnxiangtu.top/Article/details/gtbxfmaweg.html

[J08] 提取年月日与星期
来源：http://dali.yvedp.cn/Article/details/gtfyfkhjpn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jqgfzy.top/Article/details/gtbblkobwg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hywenlv.cn/Article/details/gtxezvncse.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yvedp.cn/Article/details/gtqlhrwydv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.kuanghao11.cn/Article/details/gtfkdappuz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hysaishi.cn/Article/details/gtwgpynkih.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.pengpengdd.cyou/Article/details/gtxtwiudtv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.daria6918.cn/Article/details/gtbooskaid.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yangfankeji.com/Article/details/gtnodpvqqe.html

[J09] 时区处理
来源：http://dali.zhongyouzk.top/Article/details/gtbkqtvwfw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.mhx1999.top/Article/details/gtmnakrtdw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gzhubu.top/Article/details/gtpazgdjny.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hysaishi.cn/Article/details/gtlvhqtzwi.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gttfvwfpla.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.andypj.xyz/Article/details/gtwclldfkz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hywenlv.cn/Article/details/gtqzhjczdx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.iojbl.cn/Article/details/gtwutsdwdi.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.dashuyun.cn/Article/details/gtyhtsjimx.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkegivmng.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhijiandao.cn/Article/details/gtzilrgwem.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.316326.xyz/Article/details/gtsqikiijf.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gthfnvnczw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.c1oappe.top/Article/details/gtikflzxzi.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sxryk.cn/Article/details/gttnluylpz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtliqhdjjc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.birdmap.top/Article/details/gtfvslsbim.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cheryme.top/Article/details/gtgahuhpnn.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtmwbpgbwi.html

K. JSON 与序列化
来源：http://dali.svipenyu.cn/Article/details/gtyycleszz.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gthjlqafgl.html

[K01] 对象转 JSON 字符串
来源：http://dali.pycfn.com/Article/details/gtaotokxkn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hysaishi.cn/Article/details/gtoguubvgw.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yj202588.top/Article/details/gtmkluksnc.html

JS:   JSON.stringify(obj)
来源：http://dali.yuxming.cn/Article/details/gtpeosqupw.html

TS:   JSON.stringify(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgbtoxium.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.wangdashe.top/Article/details/gttvyizzxg.html

Go:   json.Marshal(obj)
来源：http://dali.gogol.net.cn/Article/details/gtnrrsdzos.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.vqdsnc.cn/Article/details/gtgqnntxdy.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.chenlongwang.top/Article/details/gtgewvvaop.html

[K02] JSON 字符串转对象
来源：http://dali.dashuyun.cn/Article/details/gtnqdvwgac.html

Py:   json.loads(s)
来源：http://dali.aibaodan.cn/Article/details/gtwvluyjlk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.dashuyun.cn/Article/details/gtkanzkjpa.html

JS:   JSON.parse(s)
来源：http://dali.vqdsnc.cn/Article/details/gtbivvetiv.html

TS:   JSON.parse(s)
来源：http://dali.cashguo.top/Article/details/gtxpyzkhun.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yuxming.cn/Article/details/gtetnnnnnj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.snrcjt.cn/Article/details/gtbvaiwpdy.html

Ruby: JSON.parse(s)
来源：http://dali.gzhubu.top/Article/details/gtnvopivpc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xinyue.icu/Article/details/gturttpeoz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.quarkkingdee.top/Article/details/gtkdgwczgh.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.iojbl.cn/Article/details/gtebpwblum.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.bjfxy.top/Article/details/gtdfwttvjw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258888.top/Article/details/gtebghnowr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtkhrihknq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yangfankeji.com/Article/details/gtlbhxqdve.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nanxuanxn.top/Article/details/gtoznyxxws.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtaezfanbc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.bjfxy.top/Article/details/gtwhvtamnj.html

[K04] 读取 JSON 文件
来源：http://dali.cqqwz.cn/Article/details/gthtveyepw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xinyue.icu/Article/details/gtulhozheb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cheryme.top/Article/details/gthqrqdiax.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcsuyxqji.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.dianchejie.cn/Article/details/gttfxpltgk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.mhx1999.top/Article/details/gtucgqzdzq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.dashuyun.cn/Article/details/gtvqscjsru.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtdbakgfcv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.fengsongda.top/Article/details/gtrrlantqz.html

[K05] 深拷贝对象
来源：http://dali.aizwys.cn/Article/details/gthdtdwjry.html

Py:   copy.deepcopy(obj)
来源：http://dali.hfpthk.cn/Article/details/gtfejhjxxn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.daria6918.cn/Article/details/gtiyvyhjvo.html

JS:   structuredClone(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtikmvlbaq.html

TS:   structuredClone(obj)
来源：http://dali.yj202588.top/Article/details/gtcwpiocdk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shanyushiyangtech.top/Article/details/gtemtpybwt.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jqgfzy.top/Article/details/gtrudplvvi.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhoulong.xyz/Article/details/gtdyfabtov.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sufxvd.cn/Article/details/gtwqrywqtr.html

[K06] 解析 URL 查询串
来源：http://dali.shangyingyoupin.top/Article/details/gtfpnyvowp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hnxiangtu.top/Article/details/gtzgvpmqtb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.mhx1999.top/Article/details/gteucubjam.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yonumen.top/Article/details/gtjkjzqvle.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfofgvdfc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hongshengwenyu.top/Article/details/gttkrefstd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gtvsgutfbz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gtjfwevcjg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.daxiang520.top/Article/details/gtoublnlmh.html

[K07] 进制转换
来源：http://dali.jianghu66.top/Article/details/gtdylcpqei.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yj20258.top/Article/details/gtoyqceivf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zycfv.cn/Article/details/gtckvmxddv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gtnkxcjagf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gteosxzbqq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtffqumlew.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.iojbl.cn/Article/details/gtupoombsp.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yj20258.top/Article/details/gtflcbggio.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yonumen.top/Article/details/gtztqdumra.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xinyue.icu/Article/details/gtcvkwipxw.html

Py:   pickle.dumps(obj)
来源：http://dali.yj202588.top/Article/details/gttvmcsvtj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtqwjvwzit.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xziqi.cn/Article/details/gtlskqtqhr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.birdmap.top/Article/details/gtjebrigvn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.svipenyu.cn/Article/details/gtpzxkqqgq.html

Go:   encoding/gob
来源：http://dali.fzhhl.top/Article/details/gtqouzdibr.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinqigufen.top/Article/details/gtydlbdnml.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.feifeiyinyue.top/Article/details/gtyvlymtwx.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtwotuthwg.html

L. 网络请求
来源：http://dali.yuxming.cn/Article/details/gtnmprhxjf.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtiykraibq.html

[L01] 发送 GET 请求
来源：http://dali.cdnleiting.top/Article/details/gtrobaoqye.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yueranfly.top/Article/details/gtcisqmwuf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.vqdsnc.cn/Article/details/gtcatdjuvw.html

JS:   await fetch(url)
来源：http://dali.snrcjt.cn/Article/details/gtcawehzlq.html

TS:   await fetch(url)
来源：http://dali.tian-w.cn/Article/details/gtkcmfhmaf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.vqdsnc.cn/Article/details/gttjrhinuj.html

Go:   resp, err := http.Get(url)
来源：http://dali.nwbrower.top/Article/details/gtbosjdmdl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.nanxuanxn.top/Article/details/gtcrmrgohv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.bjfxy.top/Article/details/gtqdxnyagu.html

[L02] 发送 POST JSON
来源：http://dali.hfpthk.cn/Article/details/gtttqxahiu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cdnleiting.top/Article/details/gtuhybynul.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.wangdashe.top/Article/details/gtnyweygqa.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenlongwang.top/Article/details/gtliinacug.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yanxiufei.cn/Article/details/gtemlgwnjb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinqigfzy.top/Article/details/gtifhmryem.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yj20258.top/Article/details/gtxokivfix.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.tianlin.xyz/Article/details/gtjkmmjred.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yonumen.top/Article/details/gtkbmjhwwv.html

[L03] 设置自定义请求头
来源：http://dali.zhiwuduotai.top/Article/details/gtviefbisj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrdetagko.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hammf.cn/Article/details/gtwkkmhtif.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yvedp.cn/Article/details/gtthnrzqlx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shzxlz.cn/Article/details/gtgqendzxb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.bjfxy.top/Article/details/gtqoutfhef.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.guannengcc.top/Article/details/gtwxhkqbwm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.havefunace.top/Article/details/gtuzfacfnl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ehwqpu.com/Article/details/gtvkdsycce.html

[L04] 设置超时
来源：http://dali.gzhubu.top/Article/details/gtdrmvecsi.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhiwuduotai.top/Article/details/gthoqjuluk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.nanxuanxn.top/Article/details/gtidlfwypo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gogol.net.cn/Article/details/gtmbatajxo.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigfzy.top/Article/details/gtijjibrbv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jqgfzy.top/Article/details/gtmfuwppbw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.bjfxy.top/Article/details/gtpwmcfwtg.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hfpthk.cn/Article/details/gtmoqbhvsk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.guannengcc.top/Article/details/gtyjbxvrgl.html

[L05] 上传文件（multipart）
来源：http://dali.wangshuangyany.cn/Article/details/gthslwpimm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ydzc1.top/Article/details/gtlqcxzljc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yuxming.cn/Article/details/gtadbpdmhp.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ydzc1.top/Article/details/gttptxnfvo.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cashguo.top/Article/details/gtbuzenjle.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cdnleiting.top/Article/details/gtmgkrtsdw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yj20258888.top/Article/details/gtabmxnbme.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.snrcjt.cn/Article/details/gtuahqseti.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtftvyxykh.html

[L06] 解析响应为 JSON
来源：http://dali.ybcxt.top/Article/details/gtrdwwryzw.html

Py:   resp.json()
来源：http://dali.jianghu66.top/Article/details/gtooqfgedw.html

PHP:  json_decode($body, true);
来源：http://dali.sxryk.cn/Article/details/gtqwrwqiwl.html

JS:   await resp.json()
来源：http://dali.jinqigufen.top/Article/details/gtkiklkjva.html

TS:   await resp.json()
来源：http://dali.jiagoushi.top/Article/details/gtyunpditi.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zdqjudy.top/Article/details/gtxujhmjtt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hongshengwenyu.top/Article/details/gteophlark.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gzhubu.top/Article/details/gtblajhpvb.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.tianlin.xyz/Article/details/gtmdasyxen.html

[L07] 处理 HTTP 状态码
来源：http://dali.vqdsnc.cn/Article/details/gthrdsptec.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinqigufen.top/Article/details/gttmntauvk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtswenglmm.html

JS:   resp.ok;  resp.status
来源：http://dali.havefunace.top/Article/details/gtygjcmafd.html

TS:   resp.ok;  resp.status
来源：http://dali.gogol.net.cn/Article/details/gtmiyxxklp.html

Java: resp.statusCode()
来源：http://dali.chenjidiqi.icu/Article/details/gtgpccdzxt.html

Go:   resp.StatusCode
来源：http://dali.tianlin.xyz/Article/details/gtemlekduh.html

Ruby: resp.code.to_i
来源：http://dali.shanyushiyangkeji.top/Article/details/gtijqtfwmy.html

C#:   (int)resp.StatusCode
来源：http://dali.fzhhl.top/Article/details/gtjqarnwte.html

[L08] 并发请求多个地址
来源：http://dali.hfpthk.cn/Article/details/gtdbficdcv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hnqzz.top/Article/details/gtrboawtai.html

PHP:  curl_multi_init() 系列
来源：http://dali.yj202588.top/Article/details/gtdnzstiww.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sysykeji.top/Article/details/gtwlnmxfez.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gzhubu.top/Article/details/gtzduanfab.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ppjwa.cn/Article/details/gtmijmnbrz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.wangdashe.top/Article/details/gtrenwlmwo.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhixingplan.top/Article/details/gthbuvyxml.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gtmqfnjgol.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtejegjamw.html

M. 命令行 / 进程 / 环境
来源：http://dali.0kj1m.cn/Article/details/gtggwyiphd.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtlrcztjxn.html

[M01] 读取命令行参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvmpznavi.html

Py:   sys.argv[1:]
来源：http://dali.svipenyu.cn/Article/details/gtttdmyffj.html

PHP:  $argv;  $argc;
来源：http://dali.pycfn.com/Article/details/gtzrsypgue.html

JS:   process.argv.slice(2)
来源：http://dali.vqdsnc.cn/Article/details/gtqogfvqyi.html

TS:   process.argv.slice(2)
来源：http://dali.zhoulong.xyz/Article/details/gthholpryu.html

Java: args 数组（main 方法参数）
来源：http://dali.redwolf501.top/Article/details/gtnjgriapq.html

Go:   os.Args[1:]
来源：http://dali.cashguo.top/Article/details/gtkuygqbrn.html

Ruby: ARGV
来源：http://dali.chenzaomai.com/Article/details/gthxtjtnfb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.tanke756.top/Article/details/gtijbmyuyc.html

[M02] 读取环境变量
来源：http://dali.zhongyouzk.top/Article/details/gtplspvybf.html

Py:   os.environ.get("HOME")
来源：http://dali.gotoacloud.top/Article/details/gtxfekedpb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tanke756.top/Article/details/gterbjnrgu.html

JS:   process.env.HOME
来源：http://dali.haohaochexian.top/Article/details/gtqrbsyyxd.html

TS:   process.env.HOME
来源：http://dali.xylfe.cn/Article/details/gtpbrctyey.html

Java: System.getenv("HOME")
来源：http://dali.birdmap.top/Article/details/gtmoidtojm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj202588.top/Article/details/gtojizubvx.html

Ruby: ENV["HOME"]
来源：http://dali.yueranfly.top/Article/details/gttbpywqcm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxjxwhkac.html

[M03] 执行外部命令
来源：http://dali.yongpay.top/Article/details/gtmyaorlwe.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yonumen.top/Article/details/gtofyijkev.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.kuanghao11.cn/Article/details/gteiacwtnx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hammf.cn/Article/details/gtlzgfvsun.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjctfqnbm.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.c1oappe.top/Article/details/gtqzcufqsv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yuanzhike.top/Article/details/gtkntgfrpi.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tian-w.cn/Article/details/gtofgnpbte.html

C#:   Process.Start("ls", "-l");
来源：http://dali.bjfxy.top/Article/details/gtayuemavc.html

[M04] 获取当前工作目录
来源：http://dali.pengpengdd.cyou/Article/details/gtrtqlxqiu.html

Py:   os.getcwd()
来源：http://dali.gogol.net.cn/Article/details/gtjpvjumke.html

PHP:  getcwd();
来源：http://dali.hammf.cn/Article/details/gthrwovchn.html

JS:   process.cwd()
来源：http://dali.gotoacloud.top/Article/details/gtgiefjhud.html

TS:   process.cwd()
来源：http://dali.guowangkeji.top/Article/details/gtykxfndhv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xinyue.icu/Article/details/gtgdtmqukz.html

Go:   os.Getwd()
来源：http://dali.dashuyun.cn/Article/details/gteotvkxrn.html

Ruby: Dir.pwd
来源：http://dali.jianghu66.top/Article/details/gtaskyakyy.html


<!-- 参考信息 -->