代发 wailian999

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mgzpwxno.html

[I07] 忽略大小写与多行模式
来源：http://dali.jqgufenzy.top/Article/details/gt2cikjfjrr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ehwqpu.com/Article/details/gt2nmztdpym.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sxryk.cn/Article/details/gt2epoxlzll.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhiwuduotai.top/Article/details/gt2onxdnesn.html

TS:   /error/gim
来源：http://dali.sufxvd.cn/Article/details/gt2sivxnmhk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2typgeali.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shangyingyoupin.top/Article/details/gt2kdopemon.html

Ruby: s.scan(/error/i)
来源：http://dali.andypj.xyz/Article/details/gt2clqdgrwk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.dashuyun.cn/Article/details/gt2wysxzzvv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ehwqpu.com/Article/details/gt2hcuocaua.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gt2zplhnnkq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gaohongyu789.top/Article/details/gt2veyzqpfz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.mhx1999.top/Article/details/gt2fgvaadrd.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sysykeji.top/Article/details/gt2fhkucoch.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.smart0.xyz/Article/details/gt2cyacwdat.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ppjwa.cn/Article/details/gt2hjrknxwd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.guowangkeji.top/Article/details/gt2nqqattrf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.snrcjt.cn/Article/details/gt2irtpyqzw.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2vwgqcgtj.html

J. 日期与时间
来源：http://dali.birdmap.top/Article/details/gt2pnjjmcmz.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2pphlzdmg.html

[J01] 获取当前时间
来源：http://dali.shuidangran.top/Article/details/gt2qykvuwka.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.kuanghao11.cn/Article/details/gt2iekkbqll.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.feifeiyinyue.top/Article/details/gt2ejsqefqj.html

JS:   new Date();  Date.now()
来源：http://dali.birdmap.top/Article/details/gt2updzrswt.html

TS:   new Date();  Date.now()
来源：http://dali.nanxinkj.top/Article/details/gt2sbzqflbr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2yuaeypkq.html

Go:   time.Now()
来源：http://dali.chenjidiqi.icu/Article/details/gt2clmcgfgp.html

Ruby: Time.now
来源：http://dali.chenzaomai.com/Article/details/gt2dsnpimsz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jyoumei.cn/Article/details/gt2ojzpgxjm.html

[J02] 格式化输出
来源：http://dali.quarkkingdee.top/Article/details/gt2bzewgpjh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.birdmap.top/Article/details/gt2anejcwva.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.pycfn.com/Article/details/gt2pxklvavf.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ehwqpu.com/Article/details/gt2frmfdqif.html

TS:   d.toISOString()
来源：http://dali.ehwqpu.com/Article/details/gt2zxanqjds.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hnqzz.top/Article/details/gt2lvxiieat.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ydzc1.top/Article/details/gt2kadnhwgp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fengsongda.top/Article/details/gt2upzqpxyd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jqgfzy.top/Article/details/gt2wjobrpfs.html

[J03] 字符串解析为日期
来源：http://dali.xziqi.cn/Article/details/gt2tpzjhonr.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.snrcjt.cn/Article/details/gt2cupzwsjk.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shuidangran.top/Article/details/gt2fdcapldd.html

JS:   new Date("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gt2ujzopeur.html

TS:   new Date("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gt2pvolmynq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gt2vwybegmn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gt2utvptbuq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gt2hwdvfggs.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xinyue.icu/Article/details/gt2jhyjntqz.html

[J04] 时间戳与日期互转
来源：http://dali.xuanzx.com/Article/details/gt2rbgvscjy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.aizwys.cn/Article/details/gt2qvwokecu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.snrcjt.cn/Article/details/gt2atpsgsvv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xinyue.icu/Article/details/gt2jcpcfhea.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhixingplan.top/Article/details/gt2uyetiehf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.svipenyu.cn/Article/details/gt2cvfxatjm.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yueranfly.top/Article/details/gt2tqbzdyjp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.c1oappe.top/Article/details/gt2powopfdq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.vqdsnc.cn/Article/details/gt2bnmkohac.html

[J05] 时间加减（加 7 天）
来源：http://dali.cdnleiting.top/Article/details/gt2eiiffrdh.html

Py:   now + timedelta(days=7)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eqwrrxbo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.vqdsnc.cn/Article/details/gt2rpsjkhzo.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258888.top/Article/details/gt2cxldjyny.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dashuyun.cn/Article/details/gt2nurkiurw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.quarkkingdee.top/Article/details/gt2jfwlqwij.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jianghu66.top/Article/details/gt2vvacxjgt.html

Ruby: Time.now + 7 * 86400
来源：http://dali.kuanghao11.cn/Article/details/gt2plmdgram.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.aizwys.cn/Article/details/gt2ckypekst.html

[J06] 计算两时间之差
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2elexcseq.html

Py:   (end - start).total_seconds()
来源：http://dali.yj20258888.top/Article/details/gt2qybmdqzt.html

PHP:  $end->diff($start)->days;
来源：http://dali.ivvv.top/Article/details/gt2vpkmdaed.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.316326.xyz/Article/details/gt2bpgvcfef.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ydzc1.top/Article/details/gt2lokmdbyw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258.top/Article/details/gt2ksdkqenx.html

Go:   end.Sub(start).Hours()
来源：http://dali.dashuyun.cn/Article/details/gt2pveezxki.html

Ruby: end - start                 # 返回秒数
来源：http://dali.dianchejie.cn/Article/details/gt2umkgxsid.html

C#:   (end - start).TotalSeconds
来源：http://dali.yonumen.top/Article/details/gt2yycrwypx.html

[J07] 比较两个日期
来源：http://dali.zhixingplan.top/Article/details/gt2fprodqbg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gt2rjdhengl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.pycfn.com/Article/details/gt2xwxwnzhg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kikemqhk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhixingplan.top/Article/details/gt2jvwjbfwd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yuanzhike.top/Article/details/gt2nhddajbq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.daria6918.cn/Article/details/gt2rrxdwljh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gt2hqeiaiwh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gt2voknvmrk.html

[J08] 提取年月日与星期
来源：http://dali.cdnleiting.top/Article/details/gt2gnaizgvz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.havefunace.top/Article/details/gt2mxrboczj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yongpay.top/Article/details/gt2bwdyqxlx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hszwyqrk.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.daxiang520.top/Article/details/gt2urhsckog.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gotoacloud.top/Article/details/gt2vdlbdvjo.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.redwolf501.top/Article/details/gt2pljqobor.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rgmusbae.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cucudq.cn/Article/details/gt2stohjejs.html

[J09] 时区处理
来源：http://dali.meibo888.top/Article/details/gt2matwotpu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jqgfzy.top/Article/details/gt2xiwndtmh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hongshengwenyu.top/Article/details/gt2tjymdqcs.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jyoumei.cn/Article/details/gt2jeasrevc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sweek.top/Article/details/gt2rajqfbvx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xdrmzekl.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qxpbkcuu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.vqdsnc.cn/Article/details/gt2opkkrdhe.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.nwbrower.top/Article/details/gt2gmbzssew.html

[J10] 取今天 / 本月第一天
来源：http://dali.hnxiangtu.top/Article/details/gt2gdvxgmqj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jrmivokt.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.pycfn.com/Article/details/gt2nopxvhae.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cheryme.top/Article/details/gt2ymexiuta.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nanxinkj.top/Article/details/gt2hrwfldiz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hywenlv.cn/Article/details/gt2ushtneoy.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yuanzhike.top/Article/details/gt2eknqirwq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.vqdsnc.cn/Article/details/gt2rovvefdw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lqgkhjsj.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2cqxdanzx.html

K. JSON 与序列化
来源：http://dali.mhx1999.top/Article/details/gt2eothvqgi.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2gwrczsgn.html

[K01] 对象转 JSON 字符串
来源：http://dali.gotoacloud.top/Article/details/gt2rumegqyo.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.quarkkingdee.top/Article/details/gt2nbviyoxv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhixingplan.top/Article/details/gt2mmwjtfte.html

JS:   JSON.stringify(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2jyscvwxy.html

TS:   JSON.stringify(obj)
来源：http://dali.xuanzx.com/Article/details/gt2fktaplrh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.mhx1999.top/Article/details/gt2iexofllu.html

Go:   json.Marshal(obj)
来源：http://dali.pycfn.com/Article/details/gt2epyhqzon.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.bjfxy.top/Article/details/gt2karcnbkp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.316326.xyz/Article/details/gt2jplfzfkk.html

[K02] JSON 字符串转对象
来源：http://dali.jianghu66.top/Article/details/gt2quqmxvxn.html

Py:   json.loads(s)
来源：http://dali.yuanzhike.top/Article/details/gt2khwqqmml.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jyoumei.cn/Article/details/gt2qpaqhudo.html

JS:   JSON.parse(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2aiqlxmag.html

TS:   JSON.parse(s)
来源：http://dali.ehwqpu.com/Article/details/gt2uwnsxqgc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gt2txprexfr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.quarkkingdee.top/Article/details/gt2fuwvlybk.html

Ruby: JSON.parse(s)
来源：http://dali.zhengqikj.top/Article/details/gt2hngnzjvn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jyoumei.cn/Article/details/gt2foanynac.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.pengpengdd.cyou/Article/details/gt2parrezee.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cucudq.cn/Article/details/gt2vipcjzqy.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hongshengwenyu.top/Article/details/gt2bczgwxxf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sxryk.cn/Article/details/gt2zxrdooju.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yvedp.cn/Article/details/gt2sacvppky.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yuxming.cn/Article/details/gt2wkhrvvzc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gt2mhhsvceh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xziqi.cn/Article/details/gt2atngyojz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.daxiang520.top/Article/details/gt2dkkcjtgh.html

[K04] 读取 JSON 文件
来源：http://dali.yj20258.top/Article/details/gt2wmalrdyv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.bjfxy.top/Article/details/gt2sonhglos.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.pengpengdd.cyou/Article/details/gt2uhkzwkyv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuanzhike.top/Article/details/gt2iwemgltq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hammf.cn/Article/details/gt2rbudpkng.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yj20258888.top/Article/details/gt2vmwlpxmc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hongshengwenyu.top/Article/details/gt2abqcxpof.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zcqbzljo.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jqgfzy.top/Article/details/gt2arwiywei.html

[K05] 深拷贝对象
来源：http://dali.aibaodan.cn/Article/details/gt2uyuncwnq.html

Py:   copy.deepcopy(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2grhjikib.html

PHP:  unserialize(serialize($obj));
来源：http://dali.haohaochexian.top/Article/details/gt2liojlisg.html

JS:   structuredClone(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2xvhxfacx.html

TS:   structuredClone(obj)
来源：http://dali.daxiang520.top/Article/details/gt2iydochgx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shuidangran.top/Article/details/gt2txwdcyiz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ivvv.top/Article/details/gt2hmwdqlth.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gotoacloud.top/Article/details/gt2pccgbyzw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.daxiang520.top/Article/details/gt2fjhztiki.html

[K06] 解析 URL 查询串
来源：http://dali.aibaodan.cn/Article/details/gt2hfzwihjb.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.0kj1m.cn/Article/details/gt2hsyuhkxk.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.aizwys.cn/Article/details/gt2nimzngog.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.redwolf501.top/Article/details/gt2qfbxmtsm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhoulong.xyz/Article/details/gt2uzjpzeqk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.316326.xyz/Article/details/gt2dytasesh.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gogol.net.cn/Article/details/gt2opwpdyiu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yvedp.cn/Article/details/gt2mbwabrlt.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhixingplan.top/Article/details/gt2eebgqcnz.html

[K07] 进制转换
来源：http://dali.yanxiufei.cn/Article/details/gt2yqcmakjp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gt2myziszqe.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.c1oappe.top/Article/details/gt2lsyzvwzb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gt2xguogvoy.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gt2dkcoojwp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jojklxum.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zdqjudy.top/Article/details/gt2ltndmvzg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.birdmap.top/Article/details/gt2rgymkolx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gt2lpcoeklg.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cdnleiting.top/Article/details/gt2hfycfoia.html

Py:   pickle.dumps(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2xijiwedx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sisuibro.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.daria6918.cn/Article/details/gt2wbtaqfzy.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hnxiangtu.top/Article/details/gt2rmzewcwn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.birdmap.top/Article/details/gt2onwakqkh.html

Go:   encoding/gob
来源：http://dali.chenlongwang.top/Article/details/gt2spblawgd.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2jqovzbbw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yuanzhike.top/Article/details/gt2vpmzgkeb.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2echyjdvd.html

L. 网络请求
来源：http://dali.nanxinkj.top/Article/details/gt2cegsisfe.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2jlstqbzg.html

[L01] 发送 GET 请求
来源：http://dali.xuanzx.com/Article/details/gt2szdtkjzs.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.mhx1999.top/Article/details/gt2pusbyyao.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xinyue.icu/Article/details/gt2lmocupys.html

JS:   await fetch(url)
来源：http://dali.jiagoushi.top/Article/details/gt2jnmzxpbk.html

TS:   await fetch(url)
来源：http://dali.sxryk.cn/Article/details/gt2chzecpxs.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yangfankeji.com/Article/details/gt2uvtjhlwn.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinqigfzy.top/Article/details/gt2svzyqjvj.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.pengpengdd.cyou/Article/details/gt2aedxiykn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.smart0.xyz/Article/details/gt2icccrgfv.html

[L02] 发送 POST JSON
来源：http://dali.jianghu66.top/Article/details/gt2fcpdboeu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.guannengcc.top/Article/details/gt2erijchpu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.daria6918.cn/Article/details/gt2ycxlbaxk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.aibaodan.cn/Article/details/gt2uquxiuaz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.iojbl.cn/Article/details/gt2jhnzptcv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xinyue.icu/Article/details/gt2sctmiozu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.fzhhl.top/Article/details/gt2qbugzfia.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.feifeiyinyue.top/Article/details/gt2dneedeew.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cheryme.top/Article/details/gt2uuwpkbkg.html

[L03] 设置自定义请求头
来源：http://dali.hywenlv.cn/Article/details/gt2hebbgdyi.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.aibaodan.cn/Article/details/gt2qvfaiviw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj20258888.top/Article/details/gt2jgflojae.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.andypj.xyz/Article/details/gt2ankfvyzz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gogol.net.cn/Article/details/gt2fxqdlmru.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gzhubu.top/Article/details/gt2bvadjbzp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.fzhhl.top/Article/details/gt2icpeiyax.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jqgfzy.top/Article/details/gt2ezcogdym.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gzhubu.top/Article/details/gt2ktesbyla.html

[L04] 设置超时
来源：http://dali.xinyue.icu/Article/details/gt2somwnctz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.0kj1m.cn/Article/details/gt2qbqrsrxk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jyoumei.cn/Article/details/gt2yygmlbbo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhiwuduotai.top/Article/details/gt2qnprczxg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.kuanghao11.cn/Article/details/gt2llajcpoo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yj20258888.top/Article/details/gt2mfhgxisv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yj20258888.top/Article/details/gt2bwhaadwm.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hywenlv.cn/Article/details/gt2pqkzspve.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.daxiang520.top/Article/details/gt2zkiwukkn.html

[L05] 上传文件（multipart）
来源：http://dali.chenzaomai.com/Article/details/gt2haydemof.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.vqdsnc.cn/Article/details/gt2slijlwey.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.aibaodan.cn/Article/details/gt2oafivwqn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sxojcfhu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.daxiang520.top/Article/details/gt2cvbuvczg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.birdmap.top/Article/details/gt2jsicqibk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hywenlv.cn/Article/details/gt2swxygmdg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.havefunace.top/Article/details/gt2zmwuttjj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2qetbtiln.html

[L06] 解析响应为 JSON
来源：http://dali.yanxiufei.cn/Article/details/gt2vynjkrll.html

Py:   resp.json()
来源：http://dali.yongpay.top/Article/details/gt2mgzkhufg.html

PHP:  json_decode($body, true);
来源：http://dali.xuanzx.com/Article/details/gt2wcilbmzb.html

JS:   await resp.json()
来源：http://dali.mhx1999.top/Article/details/gt2lootzyfy.html

TS:   await resp.json()
来源：http://dali.yongpay.top/Article/details/gt2bsgopbfu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jlsjyb.cn/Article/details/gt2xwibubht.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhengqikj.top/Article/details/gt2myqvrenn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.dianchejie.cn/Article/details/gt2zkboxcvk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jiagoushi.top/Article/details/gt2zvmuehva.html

[L07] 处理 HTTP 状态码
来源：http://dali.sweek.top/Article/details/gt2bmdmuzol.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xziqi.cn/Article/details/gt2hnfqzkle.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.andypj.xyz/Article/details/gt2tvcoxquk.html

JS:   resp.ok;  resp.status
来源：http://dali.xylfe.cn/Article/details/gt2tkqrvhpx.html

TS:   resp.ok;  resp.status
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nbrbsque.html

Java: resp.statusCode()
来源：http://dali.jqgufenzy.top/Article/details/gt2fprsottb.html

Go:   resp.StatusCode
来源：http://dali.kuanghao11.cn/Article/details/gt2bjspwdsq.html

Ruby: resp.code.to_i
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rztsmkkj.html

C#:   (int)resp.StatusCode
来源：http://dali.fengsongda.top/Article/details/gt2uqfigqpq.html

[L08] 并发请求多个地址
来源：http://dali.jinqigfzy.top/Article/details/gt2cuzkizfk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xuetiantiany.cn/Article/details/gt2meinqigd.html

PHP:  curl_multi_init() 系列
来源：http://dali.chenlongwang.top/Article/details/gt2oqsrdhke.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ppjwa.cn/Article/details/gt2tbsibyhy.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxinkj.top/Article/details/gt2rennbsyh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.snrcjt.cn/Article/details/gt2vmhhmiyp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.316326.xyz/Article/details/gt2auwalcgv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.chenlongwang.top/Article/details/gt2ripnulax.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pydujejq.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2frzgncxp.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenzaomai.com/Article/details/gt2iavrrjqq.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2tbeqwrys.html

[M01] 读取命令行参数
来源：http://dali.jianghu66.top/Article/details/gt2surwkfnv.html

Py:   sys.argv[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xdnjatxh.html

PHP:  $argv;  $argc;
来源：http://dali.nanxinkj.top/Article/details/gt2xyuclqes.html

JS:   process.argv.slice(2)
来源：http://dali.jyoumei.cn/Article/details/gt2sqnswhdd.html

TS:   process.argv.slice(2)
来源：http://dali.gaohongyu789.top/Article/details/gt2ckkpklqv.html

Java: args 数组（main 方法参数）
来源：http://dali.cheryme.top/Article/details/gt2xwixqevu.html

Go:   os.Args[1:]
来源：http://dali.daria6918.cn/Article/details/gt2pjksdycg.html

Ruby: ARGV
来源：http://dali.ppjwa.cn/Article/details/gt2hztzjsfh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yonumen.top/Article/details/gt2vwybzrlq.html

[M02] 读取环境变量
来源：http://dali.meibo888.top/Article/details/gt2kxmdbhte.html

Py:   os.environ.get("HOME")
来源：http://dali.jinqigufen.top/Article/details/gt2anwdtqfa.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.daxiang520.top/Article/details/gt2ptoqpsfr.html

JS:   process.env.HOME
来源：http://dali.yongpay.top/Article/details/gt2bjenxjaz.html

TS:   process.env.HOME
来源：http://dali.nwbrower.top/Article/details/gt2zjjqeqao.html

Java: System.getenv("HOME")
来源：http://dali.gzhubu.top/Article/details/gt2ggrfrcuv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.0kj1m.cn/Article/details/gt2kniddvyu.html

Ruby: ENV["HOME"]
来源：http://dali.birdmap.top/Article/details/gt2bihmsstl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jianghu66.top/Article/details/gt2sxhymcyk.html

[M03] 执行外部命令
来源：http://dali.tianlin.xyz/Article/details/gt2bvngqyhi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xinyue.icu/Article/details/gt2eqikozjp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nanxuanxn.top/Article/details/gt2yahmvazf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tian-w.cn/Article/details/gt2xorscigm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258.top/Article/details/gt2swrvreaq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.nanxinkj.top/Article/details/gt2etpmtteu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hammf.cn/Article/details/gt2atwssaan.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cheryme.top/Article/details/gt2hsttdspi.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yj202588.top/Article/details/gt2aouavfrq.html

[M04] 获取当前工作目录
来源：http://dali.sysykeji.top/Article/details/gt2zxumjhur.html

Py:   os.getcwd()
来源：http://dali.birdmap.top/Article/details/gt2vqdlndwf.html

PHP:  getcwd();
来源：http://dali.shangyingyoupin.top/Article/details/gt2zsxwncum.html

JS:   process.cwd()
来源：http://dali.yj202588.top/Article/details/gt2jphqjhmu.html

TS:   process.cwd()
来源：http://dali.daria6918.cn/Article/details/gt2lkanvcin.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.aibaodan.cn/Article/details/gt2waicgjgr.html

Go:   os.Getwd()
来源：http://dali.yvedp.cn/Article/details/gt2lfeyiahi.html

Ruby: Dir.pwd
来源：http://dali.zhixingplan.top/Article/details/gt2icweiqbe.html


<!-- 参考信息 -->