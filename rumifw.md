代发 wailian999

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj202588.top/Article/details/gt2nnosrwww.html

TS:   /error/gim
来源：http://dali.haohaochexian.top/Article/details/gt2rkpofztt.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.birdmap.top/Article/details/gt2ooxplcro.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.redwolf501.top/Article/details/gt2tgasbtiq.html

Ruby: s.scan(/error/i)
来源：http://dali.svipenyu.cn/Article/details/gt2nnkdqjxj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hnxiangtu.top/Article/details/gt2jpqkshos.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.dianchejie.cn/Article/details/gt2pdzbbjti.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.gotoacloud.top/Article/details/gt2yasmlkaz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ubboljav.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenjidiqi.icu/Article/details/gt2yjdbptdu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nwbrower.top/Article/details/gt2seafjrro.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.dianchejie.cn/Article/details/gt2fpkaezgc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.daxiang520.top/Article/details/gt2gscuikgj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yuanzhike.top/Article/details/gt2nvgnntiw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jianghu66.top/Article/details/gt2zzvhsyio.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2utkeelyj.html

J. 日期与时间
来源：http://dali.hywenlv.cn/Article/details/gt2xqistvcc.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ydkkoyhl.html

[J01] 获取当前时间
来源：http://dali.jiagoushi.top/Article/details/gt2pinugxhd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yanxiufei.cn/Article/details/gt2dbrongws.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cqqwz.cn/Article/details/gt2zpifgpys.html

JS:   new Date();  Date.now()
来源：http://dali.yj202588.top/Article/details/gt2bhjlqfkx.html

TS:   new Date();  Date.now()
来源：http://dali.jqgufenzy.top/Article/details/gt2epumgrqo.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cqqwz.cn/Article/details/gt2hszlgxfl.html

Go:   time.Now()
来源：http://dali.dianchejie.cn/Article/details/gt2uhnyxwzk.html

Ruby: Time.now
来源：http://dali.aibaodan.cn/Article/details/gt2ocwuwafa.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.aibaodan.cn/Article/details/gt2yypddaum.html

[J02] 格式化输出
来源：http://dali.smart0.xyz/Article/details/gt2vzazkxfc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.snrcjt.cn/Article/details/gt2tfrzoiuk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.redwolf501.top/Article/details/gt2zhesdedd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.guannengcc.top/Article/details/gt2bhjcltqp.html

TS:   d.toISOString()
来源：http://dali.daxiang520.top/Article/details/gt2jweqpqdc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cashguo.top/Article/details/gt2vdmbirpb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhongyouzk.top/Article/details/gt2pnrqoywj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hfcprnpc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sufxvd.cn/Article/details/gt2rmbpblge.html

[J03] 字符串解析为日期
来源：http://dali.pengpengdd.cyou/Article/details/gt2bzltmtoo.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.kuanghao11.cn/Article/details/gt2fwnaxbxz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.pycfn.com/Article/details/gt2cvnpcibv.html

JS:   new Date("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gt2fzfhbmkd.html

TS:   new Date("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gt2essmgnus.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gt2thihzkqa.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gt2ifdniihz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gt2xovtgchm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.haohaochexian.top/Article/details/gt2fyogwtrz.html

[J04] 时间戳与日期互转
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fmvlbmxc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yj20258.top/Article/details/gt2hpbbmxgh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xziqi.cn/Article/details/gt2wouelfib.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.pycfn.com/Article/details/gt2irrfrhxx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.tianlin.xyz/Article/details/gt2nhdhmogc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yj20258888.top/Article/details/gt2mstctjpb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hnqzz.top/Article/details/gt2mfoocyda.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aizwys.cn/Article/details/gt2dkqpgoyx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hfpthk.cn/Article/details/gt2lnjlcuym.html

[J05] 时间加减（加 7 天）
来源：http://dali.ivvv.top/Article/details/gt2phxjmmba.html

Py:   now + timedelta(days=7)
来源：http://dali.0kj1m.cn/Article/details/gt2pxzqxhml.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jianghu66.top/Article/details/gt2icevjnmf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhixingplan.top/Article/details/gt2fpdbxqvs.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gaohongyu789.top/Article/details/gt2eaupichv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinqigfzy.top/Article/details/gt2slxyfxvh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nanxinkj.top/Article/details/gt2bvvcgjup.html

Ruby: Time.now + 7 * 86400
来源：http://dali.bjfxy.top/Article/details/gt2dvfqqist.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.aizwys.cn/Article/details/gt2vaxcmztp.html

[J06] 计算两时间之差
来源：http://dali.cheryme.top/Article/details/gt2jdjcpdpt.html

Py:   (end - start).total_seconds()
来源：http://dali.kuanghao11.cn/Article/details/gt2edkemeqr.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhoulong.xyz/Article/details/gt2gfktjgcp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.fengsongda.top/Article/details/gt2glamteci.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jlsjyb.cn/Article/details/gt2ogqcacbb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hywenlv.cn/Article/details/gt2tyvtsygp.html

Go:   end.Sub(start).Hours()
来源：http://dali.wangshuangyany.cn/Article/details/gt2vhojrsrg.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sufxvd.cn/Article/details/gt2gakcvqie.html

C#:   (end - start).TotalSeconds
来源：http://dali.yonumen.top/Article/details/gt2tnafnpyk.html

[J07] 比较两个日期
来源：http://dali.redwolf501.top/Article/details/gt2mgjvgdch.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.nanxuanxn.top/Article/details/gt2eqhmhhoo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gotoacloud.top/Article/details/gt2ljthrahc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zdqjudy.top/Article/details/gt2ccdqmeeb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ppjwa.cn/Article/details/gt2ahfrhvsx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.daxiang520.top/Article/details/gt2dhqxsllu.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cheryme.top/Article/details/gt2kegqvmnm.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gt2ynkqgooy.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gt2cpezxgau.html

[J08] 提取年月日与星期
来源：http://dali.yj20258.top/Article/details/gt2gsfuuuhr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.316326.xyz/Article/details/gt2avkblziq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.9152youxi.cn/Article/details/gt2hwqbelpc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj20258.top/Article/details/gt2qotuzvzo.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.fengsongda.top/Article/details/gt2rzwygvzf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hnqzz.top/Article/details/gt2pjiwwtli.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gaohongyu789.top/Article/details/gt2yvrnzfbe.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hongshengwenyu.top/Article/details/gt2qtazirec.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhixingplan.top/Article/details/gt2akpccvbu.html

[J09] 时区处理
来源：http://dali.hywenlv.cn/Article/details/gt2adhcvdqd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yj20258.top/Article/details/gt2uzbrrzzd.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.havefunace.top/Article/details/gt2vdwqqeai.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.meibo888.top/Article/details/gt2fdojwvxc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cashguo.top/Article/details/gt2zxaspejs.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gogol.net.cn/Article/details/gt2ldauvpye.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jyoumei.cn/Article/details/gt2zclnolzv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.daria6918.cn/Article/details/gt2ihqpqhwc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cheryme.top/Article/details/gt2qdjliszr.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jpjinqxz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2cdtlnylq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hammf.cn/Article/details/gt2kihmfegt.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xinyue.icu/Article/details/gt2usnicijl.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qrnpzgje.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinqigufen.top/Article/details/gt2bndryzvc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nanxuanxn.top/Article/details/gt2gszwomjb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.iojbl.cn/Article/details/gt2getpoeib.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.dianchejie.cn/Article/details/gt2miqkcvee.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2zkywylbi.html

K. JSON 与序列化
来源：http://dali.jqgufenzy.top/Article/details/gt2clqnqgxs.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2xbkrtmkj.html

[K01] 对象转 JSON 字符串
来源：http://dali.aibaodan.cn/Article/details/gt2knfmnfrm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ifhnwqww.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gogol.net.cn/Article/details/gt2pcmnokyo.html

JS:   JSON.stringify(obj)
来源：http://dali.yongpay.top/Article/details/gt2uwdfgzhz.html

TS:   JSON.stringify(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2obzahaiw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hnxiangtu.top/Article/details/gt2mstfecif.html

Go:   json.Marshal(obj)
来源：http://dali.yj202588.top/Article/details/gt2nltokdkl.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.birdmap.top/Article/details/gt2chmoeuoc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2loszzhst.html

[K02] JSON 字符串转对象
来源：http://dali.hammf.cn/Article/details/gt2kgqdetgk.html

Py:   json.loads(s)
来源：http://dali.guowangkeji.top/Article/details/gt2mmwizhir.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhijiandao.cn/Article/details/gt2yciiykyk.html

JS:   JSON.parse(s)
来源：http://dali.ydzc1.top/Article/details/gt2arenbapk.html

TS:   JSON.parse(s)
来源：http://dali.yuanzhike.top/Article/details/gt2mhfqeaka.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gzhubu.top/Article/details/gt2qbforrzx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qicwbclj.html

Ruby: JSON.parse(s)
来源：http://dali.sxryk.cn/Article/details/gt2hxajijtn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xohncask.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sysykeji.top/Article/details/gt2beuzrvdc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hammf.cn/Article/details/gt2srrvzjdr.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hfpthk.cn/Article/details/gt2znsrftta.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2duqyuzpk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.snrcjt.cn/Article/details/gt2ephynslc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2nuyjgmxk.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nanxinkj.top/Article/details/gt2sonjyvor.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2enrsyduc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nanxinkj.top/Article/details/gt2kbaxowsq.html

[K04] 读取 JSON 文件
来源：http://dali.jinqigufen.top/Article/details/gt2rvpwtiei.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sufxvd.cn/Article/details/gt2gypmkdzg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ybcxt.top/Article/details/gt2ezzrccif.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigfzy.top/Article/details/gt2tkthgmjm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2exwylxlr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.pycfn.com/Article/details/gt2coblmgkc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhongyouzk.top/Article/details/gt2eiqhuxdu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.dashuyun.cn/Article/details/gt2hffneyrr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.pycfn.com/Article/details/gt2pxdyzwwl.html

[K05] 深拷贝对象
来源：http://dali.hongshengwenyu.top/Article/details/gt2vwrvshca.html

Py:   copy.deepcopy(obj)
来源：http://dali.tanke756.top/Article/details/gt2vuoywjdr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.nanxinkj.top/Article/details/gt2ejbnqwlm.html

JS:   structuredClone(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nwyfnilf.html

TS:   structuredClone(obj)
来源：http://dali.gzhubu.top/Article/details/gt2hipywxgs.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sufxvd.cn/Article/details/gt2qrbfksgi.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yj20258888.top/Article/details/gt2qfeleiuw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhixingplan.top/Article/details/gt2sesmegqq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.chenjidiqi.icu/Article/details/gt2mxrsqtbg.html

[K06] 解析 URL 查询串
来源：http://dali.quarkkingdee.top/Article/details/gt2wyybntck.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cdnleiting.top/Article/details/gt2tkrkaeca.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.vqdsnc.cn/Article/details/gt2tgxipopw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.iojbl.cn/Article/details/gt2qpoqewlv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tian-w.cn/Article/details/gt2nlgtmazz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hfpthk.cn/Article/details/gt2rkkkcnah.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hammf.cn/Article/details/gt2uebdzciy.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gt2gqhxkrjc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jyoumei.cn/Article/details/gt2pluyrhkd.html

[K07] 进制转换
来源：http://dali.yj20258.top/Article/details/gt2urovqoth.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gt2gxedagxl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jqgufenzy.top/Article/details/gt2hgnwfrpy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2yvopskfg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.pycfn.com/Article/details/gt2rmlcmtti.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gt2vlqqvvyq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhengqikj.top/Article/details/gt2jdsolknv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2inmmjbdt.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gt2cynrczba.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.fengsongda.top/Article/details/gt2bqndvqxr.html

Py:   pickle.dumps(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zxakaqzd.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ppbaivxs.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xuanzx.com/Article/details/gt2pbuevpeh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jianghu66.top/Article/details/gt2kvbsgqda.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ydzc1.top/Article/details/gt2xmwvmkkh.html

Go:   encoding/gob
来源：http://dali.havefunace.top/Article/details/gt2kwaebthz.html

Ruby: Marshal.dump(obj)
来源：http://dali.smart0.xyz/Article/details/gt2efhfhwpf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.havefunace.top/Article/details/gt2hzngvhtd.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2ybpreoqp.html

L. 网络请求
来源：http://dali.zhoulong.xyz/Article/details/gt2gjvucfwh.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2wvarvhao.html

[L01] 发送 GET 请求
来源：http://dali.svipenyu.cn/Article/details/gt2ccrxzusq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jianghu66.top/Article/details/gt2hxpzmobj.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yongpay.top/Article/details/gt2bkjtzoxv.html

JS:   await fetch(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2euedtbuu.html

TS:   await fetch(url)
来源：http://dali.cucudq.cn/Article/details/gt2tiqoeueq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shzxlz.cn/Article/details/gt2hlujdkqr.html

Go:   resp, err := http.Get(url)
来源：http://dali.wangdashe.top/Article/details/gt2asngpdqt.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hysaishi.cn/Article/details/gt2kpuxalkr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zycfv.cn/Article/details/gt2ukkpyjal.html

[L02] 发送 POST JSON
来源：http://dali.yj20258.top/Article/details/gt2tvhyvwss.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xylfe.cn/Article/details/gt2zpptaazw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.nanxuanxn.top/Article/details/gt2tftdmtxi.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhixingplan.top/Article/details/gt2elauttyp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuanzhike.top/Article/details/gt2zilurcbq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jiagoushi.top/Article/details/gt2wfmhxsnf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinqigfzy.top/Article/details/gt2jectjaeu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.havefunace.top/Article/details/gt2iqdechqu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2ttzllccx.html

[L03] 设置自定义请求头
来源：http://dali.yangfankeji.com/Article/details/gt2hqipslyx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.mhx1999.top/Article/details/gt2erunhsve.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hammf.cn/Article/details/gt2bbcflqsd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tian-w.cn/Article/details/gt2iidfzhow.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.bjfxy.top/Article/details/gt2fohsgufj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.tanke756.top/Article/details/gt2qmupbfgv.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shzxlz.cn/Article/details/gt2rkxhiqiq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.wangdashe.top/Article/details/gt2xoaplisl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jiagoushi.top/Article/details/gt2dcpskssf.html

[L04] 设置超时
来源：http://dali.ybcxt.top/Article/details/gt2rkzadksc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.9152youxi.cn/Article/details/gt2urtkqnwk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ljpdjhwb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ybcxt.top/Article/details/gt2jxutshmv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tian-w.cn/Article/details/gt2janiizla.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yuxming.cn/Article/details/gt2xxmnnqhy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.chenjidiqi.icu/Article/details/gt2wqcamvfj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xylfe.cn/Article/details/gt2gjkpytyv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sufxvd.cn/Article/details/gt2psepwbco.html

[L05] 上传文件（multipart）
来源：http://dali.wangdashe.top/Article/details/gt2xviroctd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gogol.net.cn/Article/details/gt2cwjzdgtw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jyoumei.cn/Article/details/gt2iggultvx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jlsjyb.cn/Article/details/gt2wubszqom.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.redwolf501.top/Article/details/gt2xrzyxbqw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nwbrower.top/Article/details/gt2xqkvytdn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yvedp.cn/Article/details/gt2rttjbdfk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.kuanghao11.cn/Article/details/gt2qkgnemix.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xinyue.icu/Article/details/gt2mfwzxpst.html

[L06] 解析响应为 JSON
来源：http://dali.0kj1m.cn/Article/details/gt2jjzctebj.html

Py:   resp.json()
来源：http://dali.meibo888.top/Article/details/gt2pwqgebuu.html

PHP:  json_decode($body, true);
来源：http://dali.sxryk.cn/Article/details/gt2jsyghhgz.html

JS:   await resp.json()
来源：http://dali.ydzc1.top/Article/details/gt2zyrisoac.html

TS:   await resp.json()
来源：http://dali.ppjwa.cn/Article/details/gt2zfwvapxc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.daria6918.cn/Article/details/gt2egalnmqp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wkjjhuoi.html

Ruby: JSON.parse(resp.body)
来源：http://dali.pycfn.com/Article/details/gt2ciwuuvrz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kzvmwgja.html

[L07] 处理 HTTP 状态码
来源：http://dali.sufxvd.cn/Article/details/gt2tefxliru.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yonumen.top/Article/details/gt2qfjkuycp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gotoacloud.top/Article/details/gt2tytszyme.html

JS:   resp.ok;  resp.status
来源：http://dali.gotoacloud.top/Article/details/gt2pbwajztj.html

TS:   resp.ok;  resp.status
来源：http://dali.jqgufenzy.top/Article/details/gt2vvtwqsfx.html

Java: resp.statusCode()
来源：http://dali.jinqigfzy.top/Article/details/gt2qgoznmdc.html

Go:   resp.StatusCode
来源：http://dali.tian-w.cn/Article/details/gt2thicdxhz.html

Ruby: resp.code.to_i
来源：http://dali.xuetiantiany.cn/Article/details/gt2eyxcphnz.html

C#:   (int)resp.StatusCode
来源：http://dali.sufxvd.cn/Article/details/gt2qxnhlhmb.html

[L08] 并发请求多个地址
来源：http://dali.yj20258888.top/Article/details/gt2dwxqngil.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.fzhhl.top/Article/details/gt2vrugniqa.html

PHP:  curl_multi_init() 系列
来源：http://dali.cashguo.top/Article/details/gt2qtdkpumi.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.redwolf501.top/Article/details/gt2yuqyuxxl.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhqvnvy.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cqqwz.cn/Article/details/gt2nprikzab.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.tian-w.cn/Article/details/gt2qpsxctzx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ivvv.top/Article/details/gt2zosstgwt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.guannengcc.top/Article/details/gt2tlqybksn.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2qrqpkbvo.html

M. 命令行 / 进程 / 环境
来源：http://dali.ivvv.top/Article/details/gt2mzzehoaj.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2xefwrmvb.html

[M01] 读取命令行参数
来源：http://dali.0kj1m.cn/Article/details/gt2tlrffqdf.html

Py:   sys.argv[1:]
来源：http://dali.meibo888.top/Article/details/gt2axfsumge.html

PHP:  $argv;  $argc;
来源：http://dali.hfpthk.cn/Article/details/gt2wxhbehxb.html

JS:   process.argv.slice(2)
来源：http://dali.yuxming.cn/Article/details/gt2ebimovnw.html

TS:   process.argv.slice(2)
来源：http://dali.iojbl.cn/Article/details/gt2rrbzkpwt.html

Java: args 数组（main 方法参数）
来源：http://dali.svipenyu.cn/Article/details/gt2cqpsdjrk.html

Go:   os.Args[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gt2cirxinlg.html

Ruby: ARGV
来源：http://dali.zhoulong.xyz/Article/details/gt2kwmbrcsc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.tianlin.xyz/Article/details/gt2aklknegn.html

[M02] 读取环境变量
来源：http://dali.havefunace.top/Article/details/gt2ixsizvfp.html

Py:   os.environ.get("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jsbwfyun.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jqgfzy.top/Article/details/gt2nznfhvgm.html

JS:   process.env.HOME
来源：http://dali.aizwys.cn/Article/details/gt2pdvyvxko.html

TS:   process.env.HOME
来源：http://dali.chenjidiqi.icu/Article/details/gt2wjzudjwe.html

Java: System.getenv("HOME")
来源：http://dali.pycfn.com/Article/details/gt2znvwndkj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj20258888.top/Article/details/gt2fsopngwv.html

Ruby: ENV["HOME"]
来源：http://dali.sxryk.cn/Article/details/gt2urhlshyv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.c1oappe.top/Article/details/gt2xfcjpzlo.html

[M03] 执行外部命令
来源：http://dali.iojbl.cn/Article/details/gt2cwtsaenw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.aibaodan.cn/Article/details/gt2jfdjgieu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.daxiang520.top/Article/details/gt2huyudliz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhoulong.xyz/Article/details/gt2oxufabpd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.guannengcc.top/Article/details/gt2juzaypzk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2deyfviov.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.0kj1m.cn/Article/details/gt2gcrqpule.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xylfe.cn/Article/details/gt2aaijwpjj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.guannengcc.top/Article/details/gt2ipyarwfg.html

[M04] 获取当前工作目录
来源：http://dali.chenzaomai.com/Article/details/gt2gjhouwxg.html

Py:   os.getcwd()
来源：http://dali.zhoulong.xyz/Article/details/gt2qjfpunnb.html

PHP:  getcwd();
来源：http://dali.pengpengdd.cyou/Article/details/gt2sxmthpfs.html

JS:   process.cwd()
来源：http://dali.hfpthk.cn/Article/details/gt2imytpbfl.html

TS:   process.cwd()
来源：http://dali.zhengqikj.top/Article/details/gt2jititesa.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shuidangran.top/Article/details/gt2cebjkmba.html

Go:   os.Getwd()
来源：http://dali.dianchejie.cn/Article/details/gt2xrekzmpe.html

Ruby: Dir.pwd
来源：http://dali.aibaodan.cn/Article/details/gt2gpnqbcfg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yuxming.cn/Article/details/gt2oelxwgei.html

[M05] 设置退出码
来源：http://dali.tanke756.top/Article/details/gt2lwaenhhb.html

Py:   sys.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kltthrqm.html

PHP:  exit(1);
来源：http://dali.c1oappe.top/Article/details/gt2ovdjvybi.html


<!-- 参考信息 -->