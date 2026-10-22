代发 wailian999

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.aibaodan.cn/Article/details/gtobljpptf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.birdmap.top/Article/details/gteocebitn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtasvrulas.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.dashuyun.cn/Article/details/gtqdgjkdmj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhiwuduotai.top/Article/details/gtfwbdvdhn.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhiwuduotai.top/Article/details/gttxxnnihg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hywenlv.cn/Article/details/gtyhvmowiv.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtlceqkvca.html

J. 日期与时间
来源：http://dali.zhijiandao.cn/Article/details/gtyfytzpwz.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtyxoarhec.html

[J01] 获取当前时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoryltzfy.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nanxinkj.top/Article/details/gtbmxeqeyy.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shuidangran.top/Article/details/gthlgyzfsd.html

JS:   new Date();  Date.now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyzlomtnk.html

TS:   new Date();  Date.now()
来源：http://dali.fengsongda.top/Article/details/gtndixuihs.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gotoacloud.top/Article/details/gtaivnbegu.html

Go:   time.Now()
来源：http://dali.yuanzhike.top/Article/details/gtzmtgffvi.html

Ruby: Time.now
来源：http://dali.ppjwa.cn/Article/details/gtxdvqqdqv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.316326.xyz/Article/details/gtxqobrhik.html

[J02] 格式化输出
来源：http://dali.cashguo.top/Article/details/gtmmbgnwug.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fzhhl.top/Article/details/gtgrmitnzn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jlsjyb.cn/Article/details/gtgcwhvkey.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sxryk.cn/Article/details/gtextpyirl.html

TS:   d.toISOString()
来源：http://dali.jyoumei.cn/Article/details/gtdrkedlok.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gaohongyu789.top/Article/details/gtkwtejfvg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nanxinkj.top/Article/details/gtuekravny.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cheryme.top/Article/details/gtlxpdnehi.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xuetiantiany.cn/Article/details/gtnsuiygbn.html

[J03] 字符串解析为日期
来源：http://dali.sufxvd.cn/Article/details/gtlbqojsag.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yj202588.top/Article/details/gtycbtoajh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj20258888.top/Article/details/gtdhvxlmbd.html

JS:   new Date("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gtfdjmsnhv.html

TS:   new Date("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtxvxdzpvy.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gtufzrkrpl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gtdfnksfgn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gtgykchtol.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tianlin.xyz/Article/details/gtbxuuncmx.html

[J04] 时间戳与日期互转
来源：http://dali.zhiwuduotai.top/Article/details/gtadaovwsj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhijiandao.cn/Article/details/gtczhewjis.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sxryk.cn/Article/details/gtjqufactw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zycfv.cn/Article/details/gtoupjnhsq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.pycfn.com/Article/details/gtvncnbdqr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.chenlongwang.top/Article/details/gtyxhoamhf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtnundpqkg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.gaohongyu789.top/Article/details/gtfxizazyl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yueranfly.top/Article/details/gtdnquuxgc.html

[J05] 时间加减（加 7 天）
来源：http://dali.jqgfzy.top/Article/details/gtyhcecwxj.html

Py:   now + timedelta(days=7)
来源：http://dali.0kj1m.cn/Article/details/gtkzohrlxs.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jqgufenzy.top/Article/details/gtoqakbctx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.316326.xyz/Article/details/gtubajizap.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sweek.top/Article/details/gtqfpintxj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yuanzhike.top/Article/details/gtrfiidpje.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtoblnwqpy.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinqigfzy.top/Article/details/gtotecmhxr.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nwbrower.top/Article/details/gtncjrqqbu.html

[J06] 计算两时间之差
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvwcbrvnk.html

Py:   (end - start).total_seconds()
来源：http://dali.fengsongda.top/Article/details/gtdtbgbove.html

PHP:  $end->diff($start)->days;
来源：http://dali.hnqzz.top/Article/details/gtpnzjyogu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hywenlv.cn/Article/details/gtzsraqtvb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yanxiufei.cn/Article/details/gtpnqrltdw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinqigfzy.top/Article/details/gtzwmamrai.html

Go:   end.Sub(start).Hours()
来源：http://dali.9152youxi.cn/Article/details/gtwfrgpmnp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ydzc1.top/Article/details/gtufpsaulm.html

C#:   (end - start).TotalSeconds
来源：http://dali.hysaishi.cn/Article/details/gtwyjjwsia.html

[J07] 比较两个日期
来源：http://dali.guowangkeji.top/Article/details/gtsrbttqhw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gtvdpkgekn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.vqdsnc.cn/Article/details/gtlprokyyh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.guowangkeji.top/Article/details/gtqmbdhvzp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenlongwang.top/Article/details/gtyykmcvwg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gzhubu.top/Article/details/gtgrbxpife.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nwbrower.top/Article/details/gthfjkiejc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gteqvbqjpe.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jyoumei.cn/Article/details/gtqgqtdobp.html

[J08] 提取年月日与星期
来源：http://dali.dashuyun.cn/Article/details/gtiiiutjbi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.guannengcc.top/Article/details/gtyzyipsey.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.snrcjt.cn/Article/details/gtopvyyxmd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.wangshuangyany.cn/Article/details/gtoiozhcpf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nanxinkj.top/Article/details/gtlpfgkwxk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.snrcjt.cn/Article/details/gtycedetqf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj20258.top/Article/details/gtxslkcqjp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.birdmap.top/Article/details/gtlaulhipg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.chenjidiqi.icu/Article/details/gtsmjxmnyi.html

[J09] 时区处理
来源：http://dali.tianlin.xyz/Article/details/gtghyjcjwy.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shangyingyoupin.top/Article/details/gtjevnggbf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xinyue.icu/Article/details/gteppcqsac.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pycfn.com/Article/details/gtzonqvxqa.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigufen.top/Article/details/gtwfcjoddq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinqigfzy.top/Article/details/gtizuipvge.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.birdmap.top/Article/details/gtvivazbmz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shangyingyoupin.top/Article/details/gtnjcofwof.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.wangdashe.top/Article/details/gtkuviheej.html

[J10] 取今天 / 本月第一天
来源：http://dali.jqgfzy.top/Article/details/gtpgmqfmpe.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hfpthk.cn/Article/details/gtimcgrdsu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nanxinkj.top/Article/details/gtacodesxc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.316326.xyz/Article/details/gtigtzjeum.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.aibaodan.cn/Article/details/gtfkwwdtst.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hfpthk.cn/Article/details/gtwlvgpmjt.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yuxming.cn/Article/details/gtptinleak.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jqgufenzy.top/Article/details/gtaxzyzhzt.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.daxiang520.top/Article/details/gtdbzicigm.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtvcskwzdj.html

K. JSON 与序列化
来源：http://dali.birdmap.top/Article/details/gtwvjnypma.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtrchwdulu.html

[K01] 对象转 JSON 字符串
来源：http://dali.yangfankeji.com/Article/details/gtcrfqlgfv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.dashuyun.cn/Article/details/gtlotdoocd.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenlongwang.top/Article/details/gtrnpnvggl.html

JS:   JSON.stringify(obj)
来源：http://dali.sxryk.cn/Article/details/gtqozpjhlt.html

TS:   JSON.stringify(obj)
来源：http://dali.iojbl.cn/Article/details/gtyssmvyrz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.chenzaomai.com/Article/details/gtvktnqgip.html

Go:   json.Marshal(obj)
来源：http://dali.gogol.net.cn/Article/details/gtxvmlwrjy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xylfe.cn/Article/details/gtgeznpfne.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtmhyylgit.html

[K02] JSON 字符串转对象
来源：http://dali.yj20258888.top/Article/details/gtmjelyeny.html

Py:   json.loads(s)
来源：http://dali.jinqigfzy.top/Article/details/gtheurdqbi.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xziqi.cn/Article/details/gtcmvklrkp.html

JS:   JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gtnaajlvxf.html

TS:   JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gtafdssssf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sufxvd.cn/Article/details/gtiaiqvtxf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.guannengcc.top/Article/details/gtnxoxptik.html

Ruby: JSON.parse(s)
来源：http://dali.daria6918.cn/Article/details/gtkwfftcbc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtkczeibqe.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yuxming.cn/Article/details/gtzwafysvv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cashguo.top/Article/details/gttijkorrz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yuxming.cn/Article/details/gtdzjenhvk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xylfe.cn/Article/details/gthlwuhxad.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shzxlz.cn/Article/details/gtilvzhwfp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zdqjudy.top/Article/details/gtltekxxpm.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jqgfzy.top/Article/details/gtvxevjtup.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlgkngpgl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinqigufen.top/Article/details/gtsckcpfzz.html

[K04] 读取 JSON 文件
来源：http://dali.xinyue.icu/Article/details/gtsspycccv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.vqdsnc.cn/Article/details/gtwxkplrsb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yueranfly.top/Article/details/gtcnofqqno.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tian-w.cn/Article/details/gtsrufpkrw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.mhx1999.top/Article/details/gtcgdxhydr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.aibaodan.cn/Article/details/gtetlnwcsa.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yuanzhike.top/Article/details/gtycimabaq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hywenlv.cn/Article/details/gtrhgwxdrd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ydzc1.top/Article/details/gtoknhyupn.html

[K05] 深拷贝对象
来源：http://dali.hnxiangtu.top/Article/details/gtkrocatbg.html

Py:   copy.deepcopy(obj)
来源：http://dali.ivvv.top/Article/details/gtfyvkmpsc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpompmfjw.html

JS:   structuredClone(obj)
来源：http://dali.svipenyu.cn/Article/details/gtslxplpbb.html

TS:   structuredClone(obj)
来源：http://dali.yuxming.cn/Article/details/gtatjscczj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yanxiufei.cn/Article/details/gtxqhvflvd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.aizwys.cn/Article/details/gtlorjzbkg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hammf.cn/Article/details/gtmbttztbr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.tanke756.top/Article/details/gtkwrldtrh.html

[K06] 解析 URL 查询串
来源：http://dali.wangdashe.top/Article/details/gttfegtkdd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.redwolf501.top/Article/details/gtnuegbwrf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.meibo888.top/Article/details/gthqrvydrt.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xylfe.cn/Article/details/gtssbqrafv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cucudq.cn/Article/details/gtxgnbpfxa.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.fengsongda.top/Article/details/gtcrvyxcuh.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shangyingyoupin.top/Article/details/gtayenjhai.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.fzhhl.top/Article/details/gtubvmvbui.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gtjbzvvwug.html

[K07] 进制转换
来源：http://dali.pengpengdd.cyou/Article/details/gtwfzukthe.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gtokjzdifi.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhongyouzk.top/Article/details/gtlakpyyir.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gtyboxgxzy.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gtzleuegig.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gtugcazris.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nanxinkj.top/Article/details/gtnzmyumae.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ybcxt.top/Article/details/gtiuxwtmsy.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtyllvjdok.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.smart0.xyz/Article/details/gtbkznkcvb.html

Py:   pickle.dumps(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtxgmzuwvm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.dianchejie.cn/Article/details/gtkccwujaq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.chenzaomai.com/Article/details/gtivcnjjkm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.wangdashe.top/Article/details/gtemjjqtgj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yuanzhike.top/Article/details/gtdnetasxz.html

Go:   encoding/gob
来源：http://dali.hnqzz.top/Article/details/gtuczxbrdb.html

Ruby: Marshal.dump(obj)
来源：http://dali.guannengcc.top/Article/details/gtfxhkjbmt.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.guowangkeji.top/Article/details/gtkvnqmgzl.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtowxgvcwc.html

L. 网络请求
来源：http://dali.ivvv.top/Article/details/gtaogjoldo.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtuqeszhft.html

[L01] 发送 GET 请求
来源：http://dali.yj20258888.top/Article/details/gtkeumwini.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jiagoushi.top/Article/details/gtxkpcmoro.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.tanke756.top/Article/details/gtanrmvfqb.html

JS:   await fetch(url)
来源：http://dali.wangdashe.top/Article/details/gtscjeopuv.html

TS:   await fetch(url)
来源：http://dali.jqgfzy.top/Article/details/gtovazyphu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jianghu66.top/Article/details/gtmppcqdeo.html

Go:   resp, err := http.Get(url)
来源：http://dali.zycfv.cn/Article/details/gtypuojgzd.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jiagoushi.top/Article/details/gtprhdupdu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gaohongyu789.top/Article/details/gtcmvniyot.html

[L02] 发送 POST JSON
来源：http://dali.jinqigufen.top/Article/details/gtslmhdvjf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtowrnfyuq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jyoumei.cn/Article/details/gtntbivmcx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zdqjudy.top/Article/details/gtuivlnwyg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pycfn.com/Article/details/gttsrlgxiz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.quarkkingdee.top/Article/details/gtszyxgqbw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cashguo.top/Article/details/gtlwqaqwxi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yvedp.cn/Article/details/gtptmdukij.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.quarkkingdee.top/Article/details/gtusclxfjq.html

[L03] 设置自定义请求头
来源：http://dali.dashuyun.cn/Article/details/gtpebzgiyz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sweek.top/Article/details/gtzynehwwz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gaohongyu789.top/Article/details/gtrpqrkprs.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.feifeiyinyue.top/Article/details/gtjworphry.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangtech.top/Article/details/gtsqoixpxy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.9152youxi.cn/Article/details/gtvrdgbjhe.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shzxlz.cn/Article/details/gtndpmlhrq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.daxiang520.top/Article/details/gtpivqwerk.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hnxiangtu.top/Article/details/gtvfxgwvax.html

[L04] 设置超时
来源：http://dali.hnqzz.top/Article/details/gtbhfznbpv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xuetiantiany.cn/Article/details/gtnexutbij.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hnqzz.top/Article/details/gtqsbuogap.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dashuyun.cn/Article/details/gtzgnnmihu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daxiang520.top/Article/details/gttrqdhdwc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinghuilouyu.cn/Article/details/gtgnpflqqd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.pycfn.com/Article/details/gtrkjgpngz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.quarkkingdee.top/Article/details/gtunvzxnqw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.wangshuangyany.cn/Article/details/gtawdrradf.html

[L05] 上传文件（multipart）
来源：http://dali.yj20258888.top/Article/details/gtmzjsockx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.kuanghao11.cn/Article/details/gtmavlnify.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.guowangkeji.top/Article/details/gtplkvklzo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shuidangran.top/Article/details/gtgsfeurhs.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.meibo888.top/Article/details/gtmocaypee.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cdnleiting.top/Article/details/gtugibhdrw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hysaishi.cn/Article/details/gtdlpopddx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gaohongyu789.top/Article/details/gtdisixpqk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtvmgjehwp.html

[L06] 解析响应为 JSON
来源：http://dali.cqqwz.cn/Article/details/gtgvkdtecq.html

Py:   resp.json()
来源：http://dali.ivvv.top/Article/details/gtinomgedy.html

PHP:  json_decode($body, true);
来源：http://dali.yvedp.cn/Article/details/gttbbbulan.html

JS:   await resp.json()
来源：http://dali.meibo888.top/Article/details/gtltzyraby.html

TS:   await resp.json()
来源：http://dali.daxiang520.top/Article/details/gtuquzrcjb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gtaohyumzf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.pycfn.com/Article/details/gtqyzvyzcd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinghuilouyu.cn/Article/details/gthafrohoo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nanxuanxn.top/Article/details/gtnqtmexxk.html

[L07] 处理 HTTP 状态码
来源：http://dali.feifeiyinyue.top/Article/details/gtpyxnimyo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yvedp.cn/Article/details/gtwxgkfvhq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xylfe.cn/Article/details/gtjlqdnkxk.html

JS:   resp.ok;  resp.status
来源：http://dali.iojbl.cn/Article/details/gtcdnbzwxl.html

TS:   resp.ok;  resp.status
来源：http://dali.gotoacloud.top/Article/details/gtrawzwjsc.html

Java: resp.statusCode()
来源：http://dali.hnxiangtu.top/Article/details/gtyaohguru.html

Go:   resp.StatusCode
来源：http://dali.guowangkeji.top/Article/details/gtuwosxzbo.html

Ruby: resp.code.to_i
来源：http://dali.haohaochexian.top/Article/details/gtnuftqxvf.html

C#:   (int)resp.StatusCode
来源：http://dali.sxryk.cn/Article/details/gtlihrykth.html

[L08] 并发请求多个地址
来源：http://dali.nwbrower.top/Article/details/gtebqfrjdp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhixingplan.top/Article/details/gtvfwzgjoc.html

PHP:  curl_multi_init() 系列
来源：http://dali.yueranfly.top/Article/details/gtnpfsdreo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daria6918.cn/Article/details/gtpijsecnj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hysaishi.cn/Article/details/gtxbhwebqa.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.kuanghao11.cn/Article/details/gtohqygojl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.mhx1999.top/Article/details/gtgccqufaq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.mhx1999.top/Article/details/gththtuuxt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.birdmap.top/Article/details/gtlxynvwcg.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gthargoeox.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenzaomai.com/Article/details/gtunrwbarr.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtgsindhvb.html

[M01] 读取命令行参数
来源：http://dali.zhoulong.xyz/Article/details/gtuzfcgfyi.html

Py:   sys.argv[1:]
来源：http://dali.snrcjt.cn/Article/details/gtxpwgxolj.html

PHP:  $argv;  $argc;
来源：http://dali.nanxuanxn.top/Article/details/gtoqytevdv.html

JS:   process.argv.slice(2)
来源：http://dali.sufxvd.cn/Article/details/gtojvtfeae.html

TS:   process.argv.slice(2)
来源：http://dali.quarkkingdee.top/Article/details/gtivnzjfvh.html

Java: args 数组（main 方法参数）
来源：http://dali.jianghu66.top/Article/details/gtquqgcsir.html

Go:   os.Args[1:]
来源：http://dali.aizwys.cn/Article/details/gttahulwvy.html

Ruby: ARGV
来源：http://dali.xuetiantiany.cn/Article/details/gtztzzxtkm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.daxiang520.top/Article/details/gtpnfkgtfm.html

[M02] 读取环境变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtqlepmnql.html

Py:   os.environ.get("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtbglhdcmy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ybcxt.top/Article/details/gtwuryhdaw.html

JS:   process.env.HOME
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtefzfnced.html

TS:   process.env.HOME
来源：http://dali.hywenlv.cn/Article/details/gtubwddizp.html

Java: System.getenv("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gtnybbwmkp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.nwbrower.top/Article/details/gtpvwaqrni.html

Ruby: ENV["HOME"]
来源：http://dali.ehwqpu.com/Article/details/gtvqbdmoht.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yuxming.cn/Article/details/gtduyhbwin.html

[M03] 执行外部命令
来源：http://dali.yuanzhike.top/Article/details/gtrlygpqlj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.quarkkingdee.top/Article/details/gtdcdszvkz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cashguo.top/Article/details/gttpnkmkta.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigufen.top/Article/details/gtlilclcxk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tanke756.top/Article/details/gtdqdlbyqn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.quarkkingdee.top/Article/details/gtajenrijk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.wangdashe.top/Article/details/gtkcmxhgjr.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.svipenyu.cn/Article/details/gtnbsyyfit.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yuanzhike.top/Article/details/gtujbarkfl.html

[M04] 获取当前工作目录
来源：http://dali.sweek.top/Article/details/gtntotlzch.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gtzwcwspsz.html

PHP:  getcwd();
来源：http://dali.havefunace.top/Article/details/gtmaljkhom.html

JS:   process.cwd()
来源：http://dali.0kj1m.cn/Article/details/gtznkcnxei.html

TS:   process.cwd()
来源：http://dali.chenjidiqi.icu/Article/details/gtnyhlyrqi.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenjidiqi.icu/Article/details/gtzumuveju.html

Go:   os.Getwd()
来源：http://dali.sysykeji.top/Article/details/gtzguvaffk.html

Ruby: Dir.pwd
来源：http://dali.wangdashe.top/Article/details/gtycascshh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcluujsci.html

[M05] 设置退出码
来源：http://dali.haohaochexian.top/Article/details/gtlsftjuns.html

Py:   sys.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtrqibrxtt.html

PHP:  exit(1);
来源：http://dali.smart0.xyz/Article/details/gtncofhqnh.html

JS:   process.exit(1)
来源：http://dali.316326.xyz/Article/details/gtcopwwurt.html

TS:   process.exit(1)
来源：http://dali.sweek.top/Article/details/gttxsfxmrq.html

Java: System.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtabdklhhb.html

Go:   os.Exit(1)
来源：http://dali.nwbrower.top/Article/details/gtgofmqdrq.html

Ruby: exit 1
来源：http://dali.cheryme.top/Article/details/gtchtwgwpd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sweek.top/Article/details/gtwdoljnrq.html

[M06] 向标准错误输出
来源：http://dali.jqgfzy.top/Article/details/gtphmjcsgp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.dashuyun.cn/Article/details/gtitlwsuoh.html


<!-- 参考信息 -->