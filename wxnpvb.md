代发 wailian999

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinqigufen.top/Article/details/gt2iclegvyn.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xylfe.cn/Article/details/gt2ztyjdajl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tianlin.xyz/Article/details/gt2gsxdgdsq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tanke756.top/Article/details/gt2kbffnhnw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.mhx1999.top/Article/details/gt2tvyemsmb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.nanxinkj.top/Article/details/gt2wnefkssl.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.9152youxi.cn/Article/details/gt2zobqnkma.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2axnfqnqh.html

J. 日期与时间
来源：http://dali.xylfe.cn/Article/details/gt2mvwnuboo.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2gmhdxliz.html

[J01] 获取当前时间
来源：http://dali.hnxiangtu.top/Article/details/gt2lqqxqlno.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.316326.xyz/Article/details/gt2qushriee.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cqqwz.cn/Article/details/gt2eahehpom.html

JS:   new Date();  Date.now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ftjyhrqm.html

TS:   new Date();  Date.now()
来源：http://dali.mhx1999.top/Article/details/gt2rzsssdrq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wjvimhgm.html

Go:   time.Now()
来源：http://dali.fengsongda.top/Article/details/gt2snjtxocu.html

Ruby: Time.now
来源：http://dali.zdqjudy.top/Article/details/gt2tzuqczmu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nwbrower.top/Article/details/gt2ifwbkjyi.html

[J02] 格式化输出
来源：http://dali.hnqzz.top/Article/details/gt2cvmdogit.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sweek.top/Article/details/gt2dprhvqky.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shzxlz.cn/Article/details/gt2ntxkxhkg.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhiwuduotai.top/Article/details/gt2vhsgyvpb.html

TS:   d.toISOString()
来源：http://dali.chenzaomai.com/Article/details/gt2wuwrgswc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.snrcjt.cn/Article/details/gt2kgrmhevs.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.daria6918.cn/Article/details/gt2vrqrvmlt.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.redwolf501.top/Article/details/gt2yxknebpt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yangfankeji.com/Article/details/gt2ursmtrfa.html

[J03] 字符串解析为日期
来源：http://dali.hysaishi.cn/Article/details/gt2uvnmxcbw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shangyingyoupin.top/Article/details/gt2jergnavc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hjbuqqts.html

JS:   new Date("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gt2gborixvs.html

TS:   new Date("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gt2mlqddszl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gt2olqeqvqf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gt2kneazlwv.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gt2hrtvkjnp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.smart0.xyz/Article/details/gt2mktpbkqz.html

[J04] 时间戳与日期互转
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lxitjoej.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xylfe.cn/Article/details/gt2rvrjvjcq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sxryk.cn/Article/details/gt2dzozkmbn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yanxiufei.cn/Article/details/gt2pbbkkuag.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.havefunace.top/Article/details/gt2wfejhzvk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.316326.xyz/Article/details/gt2kdrigvcs.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xinyue.icu/Article/details/gt2zwqfxjvj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sxryk.cn/Article/details/gt2adeedlph.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vkryaxhk.html

[J05] 时间加减（加 7 天）
来源：http://dali.shzxlz.cn/Article/details/gt2uhejjtpp.html

Py:   now + timedelta(days=7)
来源：http://dali.yanxiufei.cn/Article/details/gt2ofkfrlrn.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jvyuqorx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aibaodan.cn/Article/details/gt2jypgwhmd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigfzy.top/Article/details/gt2tvesdcnq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinqigufen.top/Article/details/gt2oxvtduup.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.fzhhl.top/Article/details/gt2futdbboq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.iojbl.cn/Article/details/gt2wkxpmlux.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.guowangkeji.top/Article/details/gt2jozwdhkm.html

[J06] 计算两时间之差
来源：http://dali.dashuyun.cn/Article/details/gt2rbgaojua.html

Py:   (end - start).total_seconds()
来源：http://dali.xziqi.cn/Article/details/gt2gommmidb.html

PHP:  $end->diff($start)->days;
来源：http://dali.xuanzx.com/Article/details/gt2qwuoqbxv.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ydzc1.top/Article/details/gt2tmcrjppw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gzhubu.top/Article/details/gt2vyliifwt.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhijiandao.cn/Article/details/gt2yfufwcfk.html

Go:   end.Sub(start).Hours()
来源：http://dali.shzxlz.cn/Article/details/gt2zhvgxkjy.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jyoumei.cn/Article/details/gt2wkvaeogg.html

C#:   (end - start).TotalSeconds
来源：http://dali.fzhhl.top/Article/details/gt2erephlnv.html

[J07] 比较两个日期
来源：http://dali.guannengcc.top/Article/details/gt2iuznslcc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yonumen.top/Article/details/gt2nnptsgca.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.vqdsnc.cn/Article/details/gt2ilndlbod.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sufxvd.cn/Article/details/gt2cfelcrwn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.fzhhl.top/Article/details/gt2vmhagsch.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.andypj.xyz/Article/details/gt2aevcbnyx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.vqdsnc.cn/Article/details/gt2wttqxzgf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hysaishi.cn/Article/details/gt2qcnmixyw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.wangshuangyany.cn/Article/details/gt2sfnckrls.html

[J08] 提取年月日与星期
来源：http://dali.nanxuanxn.top/Article/details/gt2lsavfyda.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.redwolf501.top/Article/details/gt2uuejakpj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.meibo888.top/Article/details/gt2cexonbqa.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sufxvd.cn/Article/details/gt2zotvsrah.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nanxuanxn.top/Article/details/gt2mjaeprms.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.nanxuanxn.top/Article/details/gt2ynhwphjr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ydzc1.top/Article/details/gt2mtovasre.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhongyouzk.top/Article/details/gt2ctdcyhcg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sweek.top/Article/details/gt2iiwaeumx.html

[J09] 时区处理
来源：http://dali.guannengcc.top/Article/details/gt2minzoqyy.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ehwqpu.com/Article/details/gt2jlhkytno.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jyoumei.cn/Article/details/gt2xwrwhxdl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.meibo888.top/Article/details/gt2sabrytjy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhengqikj.top/Article/details/gt2vuttptxi.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sysykeji.top/Article/details/gt2sfwtrncc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yueranfly.top/Article/details/gt2sqvhybyb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.pycfn.com/Article/details/gt2xussqjuu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinqigfzy.top/Article/details/gt2lrxhfipf.html

[J10] 取今天 / 本月第一天
来源：http://dali.birdmap.top/Article/details/gt2wexllllg.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yuanzhike.top/Article/details/gt2wqvpkgai.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.0kj1m.cn/Article/details/gt2ejxmvvht.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.redwolf501.top/Article/details/gt2naqjekgc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.tianlin.xyz/Article/details/gt2ziffnexu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2wdtkgfoi.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cheryme.top/Article/details/gt2crrlxpku.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xcbifwcv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ppjwa.cn/Article/details/gt2aidpvncn.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2kjsamunw.html

K. JSON 与序列化
来源：http://dali.jqgufenzy.top/Article/details/gt2lhhlphlg.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2jeywrcax.html

[K01] 对象转 JSON 字符串
来源：http://dali.sufxvd.cn/Article/details/gt2rfsbeazr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cucudq.cn/Article/details/gt2fqhbfaby.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.tian-w.cn/Article/details/gt2wyvavztb.html

JS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pnezendm.html

TS:   JSON.stringify(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2gktsymal.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shuidangran.top/Article/details/gt2xnfaikeh.html

Go:   json.Marshal(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2mfrbkika.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.quarkkingdee.top/Article/details/gt2ivhspslk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sweek.top/Article/details/gt2nynnzguc.html

[K02] JSON 字符串转对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iautpxbt.html

Py:   json.loads(s)
来源：http://dali.bjfxy.top/Article/details/gt2fyhxhjga.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.andypj.xyz/Article/details/gt2lurjagdz.html

JS:   JSON.parse(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2chsxaiht.html

TS:   JSON.parse(s)
来源：http://dali.xylfe.cn/Article/details/gt2kvymaknu.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.wangshuangyany.cn/Article/details/gt2aqzmawlt.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zsuiyxlq.html

Ruby: JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gt2aeqyuune.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hammf.cn/Article/details/gt2hdvxkltj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yonumen.top/Article/details/gt2tdlhmzio.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gzhubu.top/Article/details/gt2udwljkzh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.daxiang520.top/Article/details/gt2oaympzrh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zdqjudy.top/Article/details/gt2dfassbhj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.tian-w.cn/Article/details/gt2fuduxqeu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2dwsdvzqf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hnqzz.top/Article/details/gt2ujxuqgwx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2bzfwqnqk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xuanzx.com/Article/details/gt2qodebdfl.html

[K04] 读取 JSON 文件
来源：http://dali.mhx1999.top/Article/details/gt2wzjldqwh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2ccirobjs.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yvedp.cn/Article/details/gt2yidriswm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gtekqmrl.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj202588.top/Article/details/gt2xihsixio.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhixingplan.top/Article/details/gt2qlbdrtmi.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.aizwys.cn/Article/details/gt2qtgcbfal.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xziqi.cn/Article/details/gt2vtglftsh.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yj20258.top/Article/details/gt2oyplavlf.html

[K05] 深拷贝对象
来源：http://dali.sysykeji.top/Article/details/gt2ijxjtfkr.html

Py:   copy.deepcopy(obj)
来源：http://dali.yuxming.cn/Article/details/gt2wozvfcvc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xylfe.cn/Article/details/gt2qibknxjo.html

JS:   structuredClone(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2qoibqysd.html

TS:   structuredClone(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2pjpojgxf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.kuanghao11.cn/Article/details/gt2zubgeaqr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.wangshuangyany.cn/Article/details/gt2kuwjrmri.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ehwqpu.com/Article/details/gt2trncfxah.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jqgufenzy.top/Article/details/gt2bbzxpwnw.html

[K06] 解析 URL 查询串
来源：http://dali.sufxvd.cn/Article/details/gt2cpuuzikc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.fzhhl.top/Article/details/gt2ophudhld.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gzhubu.top/Article/details/gt2kmqxnevp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fmfrjdsk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhengqikj.top/Article/details/gt2pmuxriki.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinqigfzy.top/Article/details/gt2qpzousxm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ydzc1.top/Article/details/gt2anciqfxi.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.redwolf501.top/Article/details/gt2gnelpxss.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yueranfly.top/Article/details/gt2bmwtkeyu.html

[K07] 进制转换
来源：http://dali.hammf.cn/Article/details/gt2uiqebinf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gt2vwywunkh.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.haohaochexian.top/Article/details/gt2wsuvkopv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gt2wtiwclmh.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sweek.top/Article/details/gt2taicxlvm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tanke756.top/Article/details/gt2ktgslbcn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nwbrower.top/Article/details/gt2carcwllc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ehwqpu.com/Article/details/gt2jxzjxcid.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gt2ugdmxbrb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.iojbl.cn/Article/details/gt2rxvqkfsl.html

Py:   pickle.dumps(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tkhbzbvh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ehwqpu.com/Article/details/gt2zkdflayr.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhoulong.xyz/Article/details/gt2lbbuggcn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.dashuyun.cn/Article/details/gt2hmzqbqiy.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zycfv.cn/Article/details/gt2wngnbfyo.html

Go:   encoding/gob
来源：http://dali.wangshuangyany.cn/Article/details/gt2cexieoqt.html

Ruby: Marshal.dump(obj)
来源：http://dali.jianghu66.top/Article/details/gt2uxziiaks.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xothlkij.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2wecmlocb.html

L. 网络请求
来源：http://dali.hnxiangtu.top/Article/details/gt2jcvfkkhr.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2ouuctjpd.html

[L01] 发送 GET 请求
来源：http://dali.tian-w.cn/Article/details/gt2uflytebv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hammf.cn/Article/details/gt2qeepfbhe.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.meibo888.top/Article/details/gt2uprryvvb.html

JS:   await fetch(url)
来源：http://dali.xuanzx.com/Article/details/gt2ptqsgbew.html

TS:   await fetch(url)
来源：http://dali.redwolf501.top/Article/details/gt2sqwbjlux.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hammf.cn/Article/details/gt2tzmamfyf.html

Go:   resp, err := http.Get(url)
来源：http://dali.guannengcc.top/Article/details/gt2ihmvfloi.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cqqwz.cn/Article/details/gt2vqwhyvgr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.haohaochexian.top/Article/details/gt2yojyojvt.html

[L02] 发送 POST JSON
来源：http://dali.chenlongwang.top/Article/details/gt2kditlxhq.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.guannengcc.top/Article/details/gt2rymzpnyq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.andypj.xyz/Article/details/gt2ygxtjota.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxuanxn.top/Article/details/gt2kajwmoxi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yanxiufei.cn/Article/details/gt2vuurfrwy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cashguo.top/Article/details/gt2oipsakqz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hywenlv.cn/Article/details/gt2ycmujynz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nwbrower.top/Article/details/gt2hzwdqpio.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yuxming.cn/Article/details/gt2avppezpb.html

[L03] 设置自定义请求头
来源：http://dali.shzxlz.cn/Article/details/gt2jcwjiqxn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zcppwqpa.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yonumen.top/Article/details/gt2hpxpmjti.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangdashe.top/Article/details/gt2khadplfh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fengsongda.top/Article/details/gt2kjravnkm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.quarkkingdee.top/Article/details/gt2fllrdxnb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.pycfn.com/Article/details/gt2lpyxyjof.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.fzhhl.top/Article/details/gt2piymqhlk.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.haohaochexian.top/Article/details/gt2maskpkei.html

[L04] 设置超时
来源：http://dali.wangdashe.top/Article/details/gt2umlhakuz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenlongwang.top/Article/details/gt2zfoqftud.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jqgufenzy.top/Article/details/gt2lmttzkzn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zycfv.cn/Article/details/gt2snjgsvpl.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yanxiufei.cn/Article/details/gt2cdnbyvry.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.svipenyu.cn/Article/details/gt2igcgsqcn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.svipenyu.cn/Article/details/gt2vgzrhbwi.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xinyue.icu/Article/details/gt2sdiwuput.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinqigfzy.top/Article/details/gt2nqcctpzi.html

[L05] 上传文件（multipart）
来源：http://dali.yj20258.top/Article/details/gt2ghfipcdu.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jqgfzy.top/Article/details/gt2hmitziks.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yangfankeji.com/Article/details/gt2cfoawiuo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sxryk.cn/Article/details/gt2vwmuhyou.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.nwbrower.top/Article/details/gt2irxktnpo.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhixingplan.top/Article/details/gt2kyjuhkqu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gogol.net.cn/Article/details/gt2tfcrhzrs.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.chenzaomai.com/Article/details/gt2prayzmof.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2vtxvdojm.html

[L06] 解析响应为 JSON
来源：http://dali.9152youxi.cn/Article/details/gt2wqkcyhhk.html

Py:   resp.json()
来源：http://dali.ybcxt.top/Article/details/gt2bvnlrdfn.html

PHP:  json_decode($body, true);
来源：http://dali.ivvv.top/Article/details/gt2cpjzpcbe.html

JS:   await resp.json()
来源：http://dali.feifeiyinyue.top/Article/details/gt2irghsgvt.html

TS:   await resp.json()
来源：http://dali.zhixingplan.top/Article/details/gt2tjqgeglb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.316326.xyz/Article/details/gt2nvsdzaab.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zycfv.cn/Article/details/gt2pksikiaz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.iojbl.cn/Article/details/gt2kctddgty.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cucudq.cn/Article/details/gt2hfgtjjmu.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinqigufen.top/Article/details/gt2ascirjcz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nanxinkj.top/Article/details/gt2xwsyqpyo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.snrcjt.cn/Article/details/gt2spgiqnga.html

JS:   resp.ok;  resp.status
来源：http://dali.yj20258.top/Article/details/gt2fdphxtgy.html

TS:   resp.ok;  resp.status
来源：http://dali.c1oappe.top/Article/details/gt2ynmpfygm.html

Java: resp.statusCode()
来源：http://dali.guowangkeji.top/Article/details/gt2xenqylts.html

Go:   resp.StatusCode
来源：http://dali.cucudq.cn/Article/details/gt2vxndrqus.html

Ruby: resp.code.to_i
来源：http://dali.vqdsnc.cn/Article/details/gt2dyigezcn.html

C#:   (int)resp.StatusCode
来源：http://dali.hnqzz.top/Article/details/gt2bwdkweoy.html

[L08] 并发请求多个地址
来源：http://dali.316326.xyz/Article/details/gt2iimoxbmd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cdnleiting.top/Article/details/gt2npmczlrm.html

PHP:  curl_multi_init() 系列
来源：http://dali.quarkkingdee.top/Article/details/gt2auytdcaz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuanzhike.top/Article/details/gt2kxbpfwvr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gt2edryjevt.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sweek.top/Article/details/gt2jngmgebn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhiwuduotai.top/Article/details/gt2aizpajez.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhengqikj.top/Article/details/gt2kmthtzhq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.andypj.xyz/Article/details/gt2rwwcxfza.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2xorfcwjs.html

M. 命令行 / 进程 / 环境
来源：http://dali.cheryme.top/Article/details/gt2dlynyhal.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2fjzkgytg.html

[M01] 读取命令行参数
来源：http://dali.zhixingplan.top/Article/details/gt2obxrvfii.html

Py:   sys.argv[1:]
来源：http://dali.yanxiufei.cn/Article/details/gt2dqgviwdi.html

PHP:  $argv;  $argc;
来源：http://dali.ivvv.top/Article/details/gt2bpxfzdcn.html

JS:   process.argv.slice(2)
来源：http://dali.tianlin.xyz/Article/details/gt2qeigsvqb.html

TS:   process.argv.slice(2)
来源：http://dali.havefunace.top/Article/details/gt2fjuyznsu.html

Java: args 数组（main 方法参数）
来源：http://dali.gaohongyu789.top/Article/details/gt2rgmymwid.html

Go:   os.Args[1:]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zlhpisck.html

Ruby: ARGV
来源：http://dali.zhengqikj.top/Article/details/gt2xazbblwv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.fzhhl.top/Article/details/gt2zcglxexd.html

[M02] 读取环境变量
来源：http://dali.chenzaomai.com/Article/details/gt2lqymnbte.html

Py:   os.environ.get("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gt2sajsmebf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.snrcjt.cn/Article/details/gt2wyaticgl.html

JS:   process.env.HOME
来源：http://dali.yanxiufei.cn/Article/details/gt2owhrobpb.html

TS:   process.env.HOME
来源：http://dali.xylfe.cn/Article/details/gt2jcdbkhoc.html

Java: System.getenv("HOME")
来源：http://dali.guannengcc.top/Article/details/gt2cqywvuet.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.guannengcc.top/Article/details/gt2zgrkzbby.html

Ruby: ENV["HOME"]
来源：http://dali.ivvv.top/Article/details/gt2hsccijxf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gt2ctjfcuew.html

[M03] 执行外部命令
来源：http://dali.sysykeji.top/Article/details/gt2goecyvoc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gaohongyu789.top/Article/details/gt2pokqmmpb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.quarkkingdee.top/Article/details/gt2kbuaqwue.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangdashe.top/Article/details/gt2xtvwnoch.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yueranfly.top/Article/details/gt2ttoxcdqe.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.daria6918.cn/Article/details/gt2kblpcwsz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.0kj1m.cn/Article/details/gt2ksvntcpz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nkpxpoat.html

C#:   Process.Start("ls", "-l");
来源：http://dali.guowangkeji.top/Article/details/gt2erirqdkm.html

[M04] 获取当前工作目录
来源：http://dali.chenlongwang.top/Article/details/gt2scleytcw.html

Py:   os.getcwd()
来源：http://dali.guowangkeji.top/Article/details/gt2lfawebcg.html

PHP:  getcwd();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ldduqjfy.html

JS:   process.cwd()
来源：http://dali.birdmap.top/Article/details/gt2skrudgsl.html

TS:   process.cwd()
来源：http://dali.shzxlz.cn/Article/details/gt2kqxqabbl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.bjfxy.top/Article/details/gt2bidzxqkn.html

Go:   os.Getwd()
来源：http://dali.redwolf501.top/Article/details/gt2pihfrhnk.html

Ruby: Dir.pwd
来源：http://dali.kuanghao11.cn/Article/details/gt2qzfliiox.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.tanke756.top/Article/details/gt2xsluiych.html

[M05] 设置退出码
来源：http://dali.ybcxt.top/Article/details/gt2pehxqvqi.html

Py:   sys.exit(1)
来源：http://dali.ivvv.top/Article/details/gt2xqqiibvn.html

PHP:  exit(1);
来源：http://dali.dianchejie.cn/Article/details/gt2gbxxpstx.html

JS:   process.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2omdbxtig.html

TS:   process.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hyvjmtdw.html

Java: System.exit(1)
来源：http://dali.aizwys.cn/Article/details/gt2nhalugjr.html

Go:   os.Exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2iprrtzju.html

Ruby: exit 1
来源：http://dali.pycfn.com/Article/details/gt2ydhfdhch.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.fzhhl.top/Article/details/gt2hmjslslp.html

[M06] 向标准错误输出
来源：http://dali.jyoumei.cn/Article/details/gt2rqpnpkkw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.0kj1m.cn/Article/details/gt2glxyngjf.html


<!-- 参考信息 -->