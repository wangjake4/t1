代发 wailian999

Ruby: s.scan(/error/i)
来源：http://dali.jinqigfzy.top/Article/details/gt2lgpuupbg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zdqjudy.top/Article/details/gt2nuuzwrtu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shzxlz.cn/Article/details/gt2dmnczqns.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.gzhubu.top/Article/details/gt2mzrraqty.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xziqi.cn/Article/details/gt2ujfwagdm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hammf.cn/Article/details/gt2beqgwxcb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.kuanghao11.cn/Article/details/gt2djvhbhnj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yangfankeji.com/Article/details/gt2iweehkdv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenjidiqi.icu/Article/details/gt2aqpmqzzy.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sweek.top/Article/details/gt2eurjrefq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hongshengwenyu.top/Article/details/gt2czrsggbd.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2zlgmmqiw.html

J. 日期与时间
来源：http://dali.guannengcc.top/Article/details/gt2acojyeln.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2vxzxribg.html

[J01] 获取当前时间
来源：http://dali.chenjidiqi.icu/Article/details/gt2ouaemqsz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yangfankeji.com/Article/details/gt2gfaosgbv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ogwkrsfx.html

JS:   new Date();  Date.now()
来源：http://dali.hongshengwenyu.top/Article/details/gt2fdsbmzib.html

TS:   new Date();  Date.now()
来源：http://dali.yongpay.top/Article/details/gt2tmcrabzi.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hnqzz.top/Article/details/gt2npqlzfrp.html

Go:   time.Now()
来源：http://dali.zhiwuduotai.top/Article/details/gt2dpakkgme.html

Ruby: Time.now
来源：http://dali.xylfe.cn/Article/details/gt2owwdckti.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.pengpengdd.cyou/Article/details/gt2hdkaivdm.html

[J02] 格式化输出
来源：http://dali.yueranfly.top/Article/details/gt2xkggizfc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hysaishi.cn/Article/details/gt2vhknqzrv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yvedp.cn/Article/details/gt2shaaacut.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cqqwz.cn/Article/details/gt2ocaijyvi.html

TS:   d.toISOString()
来源：http://dali.zhongyouzk.top/Article/details/gt2kthedptv.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zdqjudy.top/Article/details/gt2iyhlymiy.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.birdmap.top/Article/details/gt2dipbkcnw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sufxvd.cn/Article/details/gt2rlcmbpjj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hfpthk.cn/Article/details/gt2pzotwshg.html

[J03] 字符串解析为日期
来源：http://dali.iojbl.cn/Article/details/gt2boaxhefq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.daxiang520.top/Article/details/gt2updkzmhn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xinyue.icu/Article/details/gt2ntsmgcse.html

JS:   new Date("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gt2jzotjdmj.html

TS:   new Date("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gt2mrtfinws.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gt2jqjsdtro.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gt2guhbuqlj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gt2wttlibgk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gaohongyu789.top/Article/details/gt2zszxlofx.html

[J04] 时间戳与日期互转
来源：http://dali.bjfxy.top/Article/details/gt2ialhbfqa.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sxryk.cn/Article/details/gt2joiwyfrp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sweek.top/Article/details/gt2dnfyqxye.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jiagoushi.top/Article/details/gt2ingjpstd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yuanzhike.top/Article/details/gt2qzzwjsqs.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jqgufenzy.top/Article/details/gt2cyebkzkq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rligatsd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jyoumei.cn/Article/details/gt2ywhniwog.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.tian-w.cn/Article/details/gt2ejvequty.html

[J05] 时间加减（加 7 天）
来源：http://dali.iojbl.cn/Article/details/gt2rzevuict.html

Py:   now + timedelta(days=7)
来源：http://dali.jiagoushi.top/Article/details/gt2fyqruaeb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gzhubu.top/Article/details/gt2wlvnpmbk.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nanxuanxn.top/Article/details/gt2edknfprq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yangfankeji.com/Article/details/gt2imdzyozq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.chenlongwang.top/Article/details/gt2cjxfybnw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ldwoijwg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.fzhhl.top/Article/details/gt2hmmiojne.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nanxuanxn.top/Article/details/gt2tjfejiir.html

[J06] 计算两时间之差
来源：http://dali.smart0.xyz/Article/details/gt2tnfscxyv.html

Py:   (end - start).total_seconds()
来源：http://dali.hywenlv.cn/Article/details/gt2ktcxytlp.html

PHP:  $end->diff($start)->days;
来源：http://dali.hammf.cn/Article/details/gt2bheiodhk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hnxiangtu.top/Article/details/gt2gldbfmnp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shuidangran.top/Article/details/gt2zbhgnzlj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.meibo888.top/Article/details/gt2badggidl.html

Go:   end.Sub(start).Hours()
来源：http://dali.sufxvd.cn/Article/details/gt2izltwzlo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.smart0.xyz/Article/details/gt2faemxjgj.html

C#:   (end - start).TotalSeconds
来源：http://dali.shangyingyoupin.top/Article/details/gt2clbcxbgp.html

[J07] 比较两个日期
来源：http://dali.hywenlv.cn/Article/details/gt2ywiepavl.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fcdlnkui.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sweek.top/Article/details/gt2htkdnvpv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eqsoocsh.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cqqwz.cn/Article/details/gt2kfypecjn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.haohaochexian.top/Article/details/gt2ppmwmeie.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yuanzhike.top/Article/details/gt2puthxdta.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.kuanghao11.cn/Article/details/gt2rhqfovvm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yongpay.top/Article/details/gt2wvlrvdgp.html

[J08] 提取年月日与星期
来源：http://dali.cashguo.top/Article/details/gt2naqmyxhs.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jlsjyb.cn/Article/details/gt2snatjvfj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.aizwys.cn/Article/details/gt2dmvtello.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.haohaochexian.top/Article/details/gt2goyhezsa.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cqqwz.cn/Article/details/gt2qwsjtgbn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sweek.top/Article/details/gt2lgqzcgfm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xuetiantiany.cn/Article/details/gt2rewyooga.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xinyue.icu/Article/details/gt2qqmjcbls.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.daria6918.cn/Article/details/gt2oxzvcvue.html

[J09] 时区处理
来源：http://dali.316326.xyz/Article/details/gt2ojuakpbj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gogol.net.cn/Article/details/gt2uosfbgnz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.chenlongwang.top/Article/details/gt2wceybnan.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.snrcjt.cn/Article/details/gt2hyzuphwb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gogol.net.cn/Article/details/gt2qyvdxzas.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinqigufen.top/Article/details/gt2amtunlit.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xinyue.icu/Article/details/gt2uhmlfmph.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sweek.top/Article/details/gt2fxilcmna.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.daxiang520.top/Article/details/gt2gfmebnwb.html

[J10] 取今天 / 本月第一天
来源：http://dali.ybcxt.top/Article/details/gt2jwtkuiov.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sxflfvij.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nanxuanxn.top/Article/details/gt2wrtbfnbw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.9152youxi.cn/Article/details/gt2xobbjfqt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vrpecejk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2yhdamivl.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.wangshuangyany.cn/Article/details/gt2czkkdchk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ybbtfxgf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhengqikj.top/Article/details/gt2sumshvud.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2lbccgucc.html

K. JSON 与序列化
来源：http://dali.sxryk.cn/Article/details/gt2qoydirpi.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2jyvydtlt.html

[K01] 对象转 JSON 字符串
来源：http://dali.dianchejie.cn/Article/details/gt2xmxjmzwg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sxryk.cn/Article/details/gt2ciockzwq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cheryme.top/Article/details/gt2ujbwdmuo.html

JS:   JSON.stringify(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2sqlinxqc.html

TS:   JSON.stringify(obj)
来源：http://dali.daria6918.cn/Article/details/gt2rvhydydz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinqigfzy.top/Article/details/gt2kqtztrbn.html

Go:   json.Marshal(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2oouqmbxo.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.fengsongda.top/Article/details/gt2lndsnxnr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jianghu66.top/Article/details/gt2bknshtnn.html

[K02] JSON 字符串转对象
来源：http://dali.cdnleiting.top/Article/details/gt2rycetinl.html

Py:   json.loads(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dgxntcdi.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenlongwang.top/Article/details/gt2kyyxmqbe.html

JS:   JSON.parse(s)
来源：http://dali.hywenlv.cn/Article/details/gt2enbiyahc.html

TS:   JSON.parse(s)
来源：http://dali.haohaochexian.top/Article/details/gt2vamveosm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cucudq.cn/Article/details/gt2xpprpxfn.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.smart0.xyz/Article/details/gt2ufdagknm.html

Ruby: JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xdutsdfa.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zdqjudy.top/Article/details/gt2keohdsio.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hysaishi.cn/Article/details/gt2uxwxkwzw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhiwuduotai.top/Article/details/gt2vqrmrzaf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shzxlz.cn/Article/details/gt2xzoomjaa.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yongpay.top/Article/details/gt2nbdqxxmh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gt2zskvkyug.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2uajnbiwf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nanxuanxn.top/Article/details/gt2zqlwoilr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.fengsongda.top/Article/details/gt2nerissvp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yangfankeji.com/Article/details/gt2bmohjkvi.html

[K04] 读取 JSON 文件
来源：http://dali.sufxvd.cn/Article/details/gt2torzwvtj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hywenlv.cn/Article/details/gt2uozxkydt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.iojbl.cn/Article/details/gt2uxvusbsn.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cqqwz.cn/Article/details/gt2iisnufdt.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daria6918.cn/Article/details/gt2rgtkgvbz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tanke756.top/Article/details/gt2ekrvxxsg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sxryk.cn/Article/details/gt2dkprspxo.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ybcxt.top/Article/details/gt2irazagxs.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.dianchejie.cn/Article/details/gt2xfeqnzao.html

[K05] 深拷贝对象
来源：http://dali.yj202588.top/Article/details/gt2etigdrdh.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2ixiwqtcw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jqgfzy.top/Article/details/gt2vedisduz.html

JS:   structuredClone(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2aeiivaph.html

TS:   structuredClone(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rzxhgndq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rmhrrgxm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yj202588.top/Article/details/gt2vtmzpifm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gzhubu.top/Article/details/gt2norurxyl.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.tian-w.cn/Article/details/gt2usyremru.html

[K06] 解析 URL 查询串
来源：http://dali.xylfe.cn/Article/details/gt2fhxywzhk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhongyouzk.top/Article/details/gt2jucitpke.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sxryk.cn/Article/details/gt2mfnpmnjg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.smart0.xyz/Article/details/gt2jaypgnag.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hongshengwenyu.top/Article/details/gt2qxigsxnj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinqigfzy.top/Article/details/gt2zsryskty.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sufxvd.cn/Article/details/gt2fvvbritx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.guannengcc.top/Article/details/gt2gyxwamgt.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gt2lbplukbu.html

[K07] 进制转换
来源：http://dali.shuidangran.top/Article/details/gt2jpfbidwd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gt2vuxvolrn.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.vqdsnc.cn/Article/details/gt2gnozhubi.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ivvv.top/Article/details/gt2sszxbiel.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ivvv.top/Article/details/gt2fxkjrlth.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cheryme.top/Article/details/gt2moexbkbu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hammf.cn/Article/details/gt2rnrgroge.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.nwbrower.top/Article/details/gt2kdftrumz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2loqohpoq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yj20258888.top/Article/details/gt2zgjoulzh.html

Py:   pickle.dumps(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2crynblgh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.andypj.xyz/Article/details/gt2fgzximtg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jianghu66.top/Article/details/gt2nukakvoi.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.andypj.xyz/Article/details/gt2aqcwsebm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xuetiantiany.cn/Article/details/gt2ukotbhot.html

Go:   encoding/gob
来源：http://dali.guannengcc.top/Article/details/gt2lngjjklx.html

Ruby: Marshal.dump(obj)
来源：http://dali.sweek.top/Article/details/gt2volpuzud.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ybcxt.top/Article/details/gt2rbkcwigq.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2qmfvopmb.html

L. 网络请求
来源：http://dali.nanxinkj.top/Article/details/gt2gbcrxnpt.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2pwxbxwkl.html

[L01] 发送 GET 请求
来源：http://dali.haohaochexian.top/Article/details/gt2iyrteamx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.daxiang520.top/Article/details/gt2arjcxtrv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.tian-w.cn/Article/details/gt2pfdhaiut.html

JS:   await fetch(url)
来源：http://dali.ybcxt.top/Article/details/gt2twmdcmrp.html

TS:   await fetch(url)
来源：http://dali.chenlongwang.top/Article/details/gt2blehngpo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.316326.xyz/Article/details/gt2ekicaiby.html

Go:   resp, err := http.Get(url)
来源：http://dali.wangdashe.top/Article/details/gt2amuiukha.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hnqzz.top/Article/details/gt2xcynvcux.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yueranfly.top/Article/details/gt2bxjqlhtw.html

[L02] 发送 POST JSON
来源：http://dali.yangfankeji.com/Article/details/gt2chzgbwij.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.birdmap.top/Article/details/gt2outpojiq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhixingplan.top/Article/details/gt2lmlvzdvm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jrxccdtz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuanzhike.top/Article/details/gt2xevuakjd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zycfv.cn/Article/details/gt2fqrjdhrs.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.guannengcc.top/Article/details/gt2tycxxksg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yanxiufei.cn/Article/details/gt2djmfaijv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rxxunhyo.html

[L03] 设置自定义请求头
来源：http://dali.jlsjyb.cn/Article/details/gt2jvrykhjw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.guowangkeji.top/Article/details/gt2mmjgfklj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.nanxinkj.top/Article/details/gt2ihgubxtq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhiwuduotai.top/Article/details/gt2advpcbcw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.vqdsnc.cn/Article/details/gt2nbdeksla.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gotoacloud.top/Article/details/gt2bkirmzef.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yongpay.top/Article/details/gt2hmbrcxbf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gzhubu.top/Article/details/gt2jfdjfzkn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ybcxt.top/Article/details/gt2fbcbvrrw.html

[L04] 设置超时
来源：http://dali.xziqi.cn/Article/details/gt2pdkozrcm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhongyouzk.top/Article/details/gt2uyphupwk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ybcxt.top/Article/details/gt2eajykuxt.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cucudq.cn/Article/details/gt2tpyfzolf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuanzhike.top/Article/details/gt2wgksfiag.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jqgfzy.top/Article/details/gt2clnvtjni.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sufxvd.cn/Article/details/gt2gaxjqqqd.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jiagoushi.top/Article/details/gt2jbeesbin.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.pycfn.com/Article/details/gt2vvzxtfvc.html

[L05] 上传文件（multipart）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2npzkwbur.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nanxuanxn.top/Article/details/gt2cxyodvyp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yuxming.cn/Article/details/gt2crsiirrj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hongshengwenyu.top/Article/details/gt2tijxajsw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuanzhike.top/Article/details/gt2hntmyjpz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hfpthk.cn/Article/details/gt2aahzipmi.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2eddqppnl.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gotoacloud.top/Article/details/gt2rcweular.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2kvzjyzhy.html

[L06] 解析响应为 JSON
来源：http://dali.tianlin.xyz/Article/details/gt2zskwlyku.html

Py:   resp.json()
来源：http://dali.hnxiangtu.top/Article/details/gt2guluzwrg.html

PHP:  json_decode($body, true);
来源：http://dali.birdmap.top/Article/details/gt2gezznsxr.html

JS:   await resp.json()
来源：http://dali.birdmap.top/Article/details/gt2qapmlvyj.html

TS:   await resp.json()
来源：http://dali.ehwqpu.com/Article/details/gt2borltyfc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.daxiang520.top/Article/details/gt2ehesdbgq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rlldjbwc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.andypj.xyz/Article/details/gt2krrcngff.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2upwvfjzy.html

[L07] 处理 HTTP 状态码
来源：http://dali.daria6918.cn/Article/details/gt2goklbsgc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ljsquuoi.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.fzhhl.top/Article/details/gt2xvjvosid.html

JS:   resp.ok;  resp.status
来源：http://dali.cheryme.top/Article/details/gt2ecbanorq.html

TS:   resp.ok;  resp.status
来源：http://dali.kuanghao11.cn/Article/details/gt2hpcutssl.html

Java: resp.statusCode()
来源：http://dali.dianchejie.cn/Article/details/gt2jexggewx.html

Go:   resp.StatusCode
来源：http://dali.jiagoushi.top/Article/details/gt2vutbcqdb.html

Ruby: resp.code.to_i
来源：http://dali.yuanzhike.top/Article/details/gt2ilykjnio.html

C#:   (int)resp.StatusCode
来源：http://dali.yangfankeji.com/Article/details/gt2slghxwro.html

[L08] 并发请求多个地址
来源：http://dali.sweek.top/Article/details/gt2mtcmuueq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jiagoushi.top/Article/details/gt2ounxtrjn.html

PHP:  curl_multi_init() 系列
来源：http://dali.wangdashe.top/Article/details/gt2uxdpkdcw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guowangkeji.top/Article/details/gt2qwatpezi.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenzaomai.com/Article/details/gt2spkrwpyr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinqigfzy.top/Article/details/gt2mmdbivoj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.dashuyun.cn/Article/details/gt2fqvzqmtb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.smart0.xyz/Article/details/gt2vrkmczqs.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gt2vpvkzkvb.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2xnfuhyas.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenjidiqi.icu/Article/details/gt2omebunyy.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2iuuaryfj.html

[M01] 读取命令行参数
来源：http://dali.yuanzhike.top/Article/details/gt2ymzxtwtl.html

Py:   sys.argv[1:]
来源：http://dali.ivvv.top/Article/details/gt2vnhjugdu.html

PHP:  $argv;  $argc;
来源：http://dali.daria6918.cn/Article/details/gt2fulrdukz.html

JS:   process.argv.slice(2)
来源：http://dali.yj20258.top/Article/details/gt2hadtposi.html

TS:   process.argv.slice(2)
来源：http://dali.yueranfly.top/Article/details/gt2cfduomhq.html

Java: args 数组（main 方法参数）
来源：http://dali.shangyingyoupin.top/Article/details/gt2fqitlfwi.html

Go:   os.Args[1:]
来源：http://dali.gogol.net.cn/Article/details/gt2vymiocas.html

Ruby: ARGV
来源：http://dali.aizwys.cn/Article/details/gt2vvbxxtiv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.tianlin.xyz/Article/details/gt2plutjjeq.html

[M02] 读取环境变量
来源：http://dali.guowangkeji.top/Article/details/gt2vhvrkeci.html

Py:   os.environ.get("HOME")
来源：http://dali.jinqigufen.top/Article/details/gt2vgyspjnq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hihmhyjr.html

JS:   process.env.HOME
来源：http://dali.tian-w.cn/Article/details/gt2wegxruiw.html

TS:   process.env.HOME
来源：http://dali.ppjwa.cn/Article/details/gt2juusylkt.html

Java: System.getenv("HOME")
来源：http://dali.fzhhl.top/Article/details/gt2rqbcnjge.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gt2gucinuyv.html

Ruby: ENV["HOME"]
来源：http://dali.chenjidiqi.icu/Article/details/gt2fueaciej.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxcqhppo.html

[M03] 执行外部命令
来源：http://dali.snrcjt.cn/Article/details/gt2cdjasxri.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gvuvmjgm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nwbrower.top/Article/details/gt2fhvshdbu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ppjwa.cn/Article/details/gt2cjfhzvpa.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shzxlz.cn/Article/details/gt2wzlrgbee.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhengqikj.top/Article/details/gt2gttkhfem.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhongyouzk.top/Article/details/gt2znxwzqyk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hnqzz.top/Article/details/gt2mpvddlzj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.dashuyun.cn/Article/details/gt2wkzfdplq.html

[M04] 获取当前工作目录
来源：http://dali.mhx1999.top/Article/details/gt2jintzdet.html

Py:   os.getcwd()
来源：http://dali.dashuyun.cn/Article/details/gt2xluscncq.html

PHP:  getcwd();
来源：http://dali.chenzaomai.com/Article/details/gt2vorwwift.html

JS:   process.cwd()
来源：http://dali.hnxiangtu.top/Article/details/gt2yqgxbpsj.html

TS:   process.cwd()
来源：http://dali.jinqigufen.top/Article/details/gt2ehixwnvk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.redwolf501.top/Article/details/gt2kkcjanse.html

Go:   os.Getwd()
来源：http://dali.fengsongda.top/Article/details/gt2ytnymggc.html

Ruby: Dir.pwd
来源：http://dali.chenlongwang.top/Article/details/gt2zyffkmha.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eurhwnpt.html

[M05] 设置退出码
来源：http://dali.dianchejie.cn/Article/details/gt2ptkeyehq.html

Py:   sys.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gloddjkz.html

PHP:  exit(1);
来源：http://dali.cucudq.cn/Article/details/gt2fneghdvy.html

JS:   process.exit(1)
来源：http://dali.shuidangran.top/Article/details/gt2istaapjq.html

TS:   process.exit(1)
来源：http://dali.andypj.xyz/Article/details/gt2oozuiyra.html

Java: System.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gt2mowfzqud.html

Go:   os.Exit(1)
来源：http://dali.ydzc1.top/Article/details/gt2cyaowhff.html


<!-- 参考信息 -->