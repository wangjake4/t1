代发 wailian999

J. 日期与时间
来源：http://dali.jqgufenzy.top/Article/details/gt2tkrlsvfj.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2ehuzgnsj.html

[J01] 获取当前时间
来源：http://dali.smart0.xyz/Article/details/gt2hiuzadai.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.daria6918.cn/Article/details/gt2ikuztaxg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinqigfzy.top/Article/details/gt2xywsxtms.html

JS:   new Date();  Date.now()
来源：http://dali.bjfxy.top/Article/details/gt2kctszhne.html

TS:   new Date();  Date.now()
来源：http://dali.nwbrower.top/Article/details/gt2toskjfva.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hnxiangtu.top/Article/details/gt2bloevzmj.html

Go:   time.Now()
来源：http://dali.zhiwuduotai.top/Article/details/gt2oigkisik.html

Ruby: Time.now
来源：http://dali.chenjidiqi.icu/Article/details/gt2hzwuwial.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xinyue.icu/Article/details/gt2iqhufxpd.html

[J02] 格式化输出
来源：http://dali.bjfxy.top/Article/details/gt2fihktjcb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.0kj1m.cn/Article/details/gt2avreoudh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jqgufenzy.top/Article/details/gt2tclucwqw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.aizwys.cn/Article/details/gt2cmqeafna.html

TS:   d.toISOString()
来源：http://dali.tian-w.cn/Article/details/gt2xkrvccpz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jianghu66.top/Article/details/gt2jltagxzb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhoulong.xyz/Article/details/gt2hnjphcve.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuxming.cn/Article/details/gt2crzuoawk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sufxvd.cn/Article/details/gt2zrjnkuqn.html

[J03] 字符串解析为日期
来源：http://dali.xylfe.cn/Article/details/gt2afsqppxp.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ybcxt.top/Article/details/gt2wdnrnfke.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hammf.cn/Article/details/gt2pxhuevwh.html

JS:   new Date("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gt2ylzrrcrt.html

TS:   new Date("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gt2ovmbvmzr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gt2fiwchzmv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gt2qtxyvonv.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2swwbysje.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bvjcffda.html

[J04] 时间戳与日期互转
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aeclyxle.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gt2farpjciy.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cdnleiting.top/Article/details/gt2zmwfmreh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gogol.net.cn/Article/details/gt2rjbojnjk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ppjwa.cn/Article/details/gt2fqdyyisb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.fengsongda.top/Article/details/gt2ppkywues.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nanxuanxn.top/Article/details/gt2tkecsuhn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.dashuyun.cn/Article/details/gt2hygxqebw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.chenlongwang.top/Article/details/gt2vkwxawzn.html

[J05] 时间加减（加 7 天）
来源：http://dali.shangyingyoupin.top/Article/details/gt2eeqkznug.html

Py:   now + timedelta(days=7)
来源：http://dali.nanxinkj.top/Article/details/gt2gdahuiho.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ydzc1.top/Article/details/gt2olrrhdlh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yanxiufei.cn/Article/details/gt2kjzpegbh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yvedp.cn/Article/details/gt2hbszutot.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.daxiang520.top/Article/details/gt2hwpepzcb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xziqi.cn/Article/details/gt2dyrgydsc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.daria6918.cn/Article/details/gt2pljhzats.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xziqi.cn/Article/details/gt2tcoqwrzy.html

[J06] 计算两时间之差
来源：http://dali.yueranfly.top/Article/details/gt2dcdyqfqe.html

Py:   (end - start).total_seconds()
来源：http://dali.hysaishi.cn/Article/details/gt2zfexvyvz.html

PHP:  $end->diff($start)->days;
来源：http://dali.svipenyu.cn/Article/details/gt2iezbeyng.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.dianchejie.cn/Article/details/gt2sheewlsv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.c1oappe.top/Article/details/gt2yorvssxl.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jyoumei.cn/Article/details/gt2xubvmzms.html

Go:   end.Sub(start).Hours()
来源：http://dali.pengpengdd.cyou/Article/details/gt2elwgbsky.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iguyfcoa.html

C#:   (end - start).TotalSeconds
来源：http://dali.daria6918.cn/Article/details/gt2llajpplg.html

[J07] 比较两个日期
来源：http://dali.hammf.cn/Article/details/gt2txohiygn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gt2kxdxzuef.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gaohongyu789.top/Article/details/gt2bptdsoed.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yueranfly.top/Article/details/gt2mjxncijf.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ydzc1.top/Article/details/gt2gswwrxtv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.havefunace.top/Article/details/gt2yjhtsyiu.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ivvv.top/Article/details/gt2sxnbcjre.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zdqjudy.top/Article/details/gt2jlcymefp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhoulong.xyz/Article/details/gt2zsmmvkhu.html

[J08] 提取年月日与星期
来源：http://dali.feifeiyinyue.top/Article/details/gt2plnbyejt.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhixingplan.top/Article/details/gt2tkjhixku.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zdqjudy.top/Article/details/gt2ifzbagth.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwbikzh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.vqdsnc.cn/Article/details/gt2cjqzrgqa.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gzhubu.top/Article/details/gt2ckovvkwp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.nanxinkj.top/Article/details/gt2vsjlchek.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.nwbrower.top/Article/details/gt2tiletlir.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.0kj1m.cn/Article/details/gt2uythrmka.html

[J09] 时区处理
来源：http://dali.smart0.xyz/Article/details/gt2axwxstgd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fzsymgbq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.vqdsnc.cn/Article/details/gt2gmikiktl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yvedp.cn/Article/details/gt2efjnvktz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.haohaochexian.top/Article/details/gt2mjgcnlck.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.feifeiyinyue.top/Article/details/gt2kxgmqpfq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.andypj.xyz/Article/details/gt2iiuzgzrg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yangfankeji.com/Article/details/gt2rvvwggfm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.aizwys.cn/Article/details/gt2dazpiqkg.html

[J10] 取今天 / 本月第一天
来源：http://dali.ppjwa.cn/Article/details/gt2ydifvyeg.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.dianchejie.cn/Article/details/gt2vlzuockc.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jianghu66.top/Article/details/gt2enovshjn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oxhntiuj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zdqjudy.top/Article/details/gt2qazfndmt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2sbyzqvcq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ehwqpu.com/Article/details/gt2vqiakgpy.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yanxiufei.cn/Article/details/gt2jdyszwgo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ctxbvgon.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2nqfmrwvw.html

K. JSON 与序列化
来源：http://dali.sxryk.cn/Article/details/gt2zgqgiisr.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2wpdpsbku.html

[K01] 对象转 JSON 字符串
来源：http://dali.havefunace.top/Article/details/gt2tbbsquod.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.svipenyu.cn/Article/details/gt2jcuaudpe.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yonumen.top/Article/details/gt2tjhuidpm.html

JS:   JSON.stringify(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2twqmrdon.html

TS:   JSON.stringify(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gyiprmqp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pmhndncv.html

Go:   json.Marshal(obj)
来源：http://dali.fengsongda.top/Article/details/gt2aohoowdg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.tianlin.xyz/Article/details/gt2lklvwnoa.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.c1oappe.top/Article/details/gt2uecxwiqc.html

[K02] JSON 字符串转对象
来源：http://dali.snrcjt.cn/Article/details/gt2jstzrfms.html

Py:   json.loads(s)
来源：http://dali.gzhubu.top/Article/details/gt2igajrfgj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenlongwang.top/Article/details/gt2jpuoryro.html

JS:   JSON.parse(s)
来源：http://dali.ehwqpu.com/Article/details/gt2sixicdjn.html

TS:   JSON.parse(s)
来源：http://dali.jinqigufen.top/Article/details/gt2iodohglw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinqigufen.top/Article/details/gt2ytlivwgu.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.aibaodan.cn/Article/details/gt2gjhuipum.html

Ruby: JSON.parse(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2oclllxnk.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.9152youxi.cn/Article/details/gt2dtvxnfyu.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhoulong.xyz/Article/details/gt2lejqwwcj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.0kj1m.cn/Article/details/gt2nthfnkxp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.bjfxy.top/Article/details/gt2xuuydmgd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xyjmtmhs.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ryckyflv.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.meibo888.top/Article/details/gt2sxcjpvzd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhiwuduotai.top/Article/details/gt2mmlvgeww.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fccitmqu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.kuanghao11.cn/Article/details/gt2gnwnkcoo.html

[K04] 读取 JSON 文件
来源：http://dali.vqdsnc.cn/Article/details/gt2ghfpdlfn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sysykeji.top/Article/details/gt2cwcrlofq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.quarkkingdee.top/Article/details/gt2ibtqaidv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hammf.cn/Article/details/gt2ucrutwtc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.kuanghao11.cn/Article/details/gt2tekrwhlx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mheyyxxo.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shzxlz.cn/Article/details/gt2abxhzunm.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pxfzbnhk.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cheryme.top/Article/details/gt2dbhhvunu.html

[K05] 深拷贝对象
来源：http://dali.jlsjyb.cn/Article/details/gt2cdodcgip.html

Py:   copy.deepcopy(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2czatmwcr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.fzhhl.top/Article/details/gt2qvslosvi.html

JS:   structuredClone(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lwhidkrp.html

TS:   structuredClone(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2tiszlrby.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenzaomai.com/Article/details/gt2eacpndeo.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xuanzx.com/Article/details/gt2povcadwx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yuxming.cn/Article/details/gt2yendqlom.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.aizwys.cn/Article/details/gt2kwpcjetc.html

[K06] 解析 URL 查询串
来源：http://dali.sxryk.cn/Article/details/gt2zckonghk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yanxiufei.cn/Article/details/gt2pcvxdrqj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.0kj1m.cn/Article/details/gt2hduyjoxg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jiagoushi.top/Article/details/gt2vvwrlppc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.dashuyun.cn/Article/details/gt2xtokzdpx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jlsjyb.cn/Article/details/gt2mzbuuzjf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhiwuduotai.top/Article/details/gt2akutauvc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.haohaochexian.top/Article/details/gt2frnagnho.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jqgufenzy.top/Article/details/gt2egxlnigu.html

[K07] 进制转换
来源：http://dali.smart0.xyz/Article/details/gt2zxaojbay.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gt2srstqvgg.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigfzy.top/Article/details/gt2ngxgzkdh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gt2xsqeftbo.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.pycfn.com/Article/details/gt2iqgamvlo.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gt2ugdtogry.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.redwolf501.top/Article/details/gt2fybvdlcy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ehwqpu.com/Article/details/gt2moascnme.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gt2oqhegyky.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yanxiufei.cn/Article/details/gt2mhmrtxdt.html

Py:   pickle.dumps(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2svehymbq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.tanke756.top/Article/details/gt2tkbplpju.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yanxiufei.cn/Article/details/gt2zqjtwfsh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.nwbrower.top/Article/details/gt2xardpwcw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.mhx1999.top/Article/details/gt2edicvemr.html

Go:   encoding/gob
来源：http://dali.gaohongyu789.top/Article/details/gt2ihzlvzkk.html

Ruby: Marshal.dump(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2klgafkmn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zdqjudy.top/Article/details/gt2hdtzljju.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2qvnccunt.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2zedxpnbw.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2vzygahpp.html

[L01] 发送 GET 请求
来源：http://dali.tian-w.cn/Article/details/gt2xckibnme.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xinyue.icu/Article/details/gt2mfjjmvfi.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shangyingyoupin.top/Article/details/gt2ldokmclb.html

JS:   await fetch(url)
来源：http://dali.snrcjt.cn/Article/details/gt2nsbntbgs.html

TS:   await fetch(url)
来源：http://dali.jlsjyb.cn/Article/details/gt2ukfflvqv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xinyue.icu/Article/details/gt2wfslpmfr.html

Go:   resp, err := http.Get(url)
来源：http://dali.shzxlz.cn/Article/details/gt2uchkfvxv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.andypj.xyz/Article/details/gt2rxxilayf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bjjoapon.html

[L02] 发送 POST JSON
来源：http://dali.cdnleiting.top/Article/details/gt2qelmqlvm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.nwbrower.top/Article/details/gt2ltcrpodq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hywenlv.cn/Article/details/gt2ratzutbk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ehwqpu.com/Article/details/gt2tdmxgpvz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangshuangyany.cn/Article/details/gt2turehzyf.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hywenlv.cn/Article/details/gt2sdegjcme.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.guowangkeji.top/Article/details/gt2grdkxdub.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.quarkkingdee.top/Article/details/gt2ohktcgwq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gotoacloud.top/Article/details/gt2uwqlkiqq.html

[L03] 设置自定义请求头
来源：http://dali.kuanghao11.cn/Article/details/gt2mygggfyy.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hysaishi.cn/Article/details/gt2pfpwrlvz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gaohongyu789.top/Article/details/gt2fpagavob.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.svipenyu.cn/Article/details/gt2ukwyaxrl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aizwys.cn/Article/details/gt2rdeuzdwj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yangfankeji.com/Article/details/gt2qdqhwjzz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.redwolf501.top/Article/details/gt2ooxrrjgd.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinqigufen.top/Article/details/gt2gzoedjll.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jlsjyb.cn/Article/details/gt2bykyoqbh.html

[L04] 设置超时
来源：http://dali.chenjidiqi.icu/Article/details/gt2mqvxrgzj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.sysykeji.top/Article/details/gt2amjqpyha.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.mhx1999.top/Article/details/gt2yrbshosi.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigufen.top/Article/details/gt2rygrkjyy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ehwqpu.com/Article/details/gt2qpwuxqyi.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhengqikj.top/Article/details/gt2ymxqhatq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cashguo.top/Article/details/gt2xdmkcszk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.bjfxy.top/Article/details/gt2xdntdrbg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinqigfzy.top/Article/details/gt2czkdgnui.html

[L05] 上传文件（multipart）
来源：http://dali.hnxiangtu.top/Article/details/gt2ipzlawcq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yangfankeji.com/Article/details/gt2crtqutvp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhongyouzk.top/Article/details/gt2bmxborwn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnqzz.top/Article/details/gt2kxvycptz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.nwbrower.top/Article/details/gt2fsfotika.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.kuanghao11.cn/Article/details/gt2jrehfbyx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.kuanghao11.cn/Article/details/gt2vyposaad.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.daria6918.cn/Article/details/gt2zyxvofrb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xinyue.icu/Article/details/gt2sornjibf.html

[L06] 解析响应为 JSON
来源：http://dali.yanxiufei.cn/Article/details/gt2qgifotbr.html

Py:   resp.json()
来源：http://dali.ybcxt.top/Article/details/gt2oxvxzjhg.html

PHP:  json_decode($body, true);
来源：http://dali.zhongyouzk.top/Article/details/gt2fefcyaem.html

JS:   await resp.json()
来源：http://dali.yangfankeji.com/Article/details/gt2ytnasykh.html

TS:   await resp.json()
来源：http://dali.yj20258888.top/Article/details/gt2aagnkiui.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hongshengwenyu.top/Article/details/gt2omonusug.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sufxvd.cn/Article/details/gt2rgbshmzc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ppjwa.cn/Article/details/gt2mihllyjr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shzxlz.cn/Article/details/gt2vhblhfxt.html

[L07] 处理 HTTP 状态码
来源：http://dali.pengpengdd.cyou/Article/details/gt2mkkeufeq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zdqjudy.top/Article/details/gt2scwypwhg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shuidangran.top/Article/details/gt2vqyhcsik.html

JS:   resp.ok;  resp.status
来源：http://dali.guowangkeji.top/Article/details/gt2pglpxmtk.html

TS:   resp.ok;  resp.status
来源：http://dali.wangdashe.top/Article/details/gt2wyeumizu.html

Java: resp.statusCode()
来源：http://dali.daria6918.cn/Article/details/gt2fbwairrj.html

Go:   resp.StatusCode
来源：http://dali.dianchejie.cn/Article/details/gt2yaincsgd.html

Ruby: resp.code.to_i
来源：http://dali.vqdsnc.cn/Article/details/gt2mzfgekfq.html

C#:   (int)resp.StatusCode
来源：http://dali.yj20258.top/Article/details/gt2psevcsdq.html

[L08] 并发请求多个地址
来源：http://dali.dianchejie.cn/Article/details/gt2tilisgpu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.feifeiyinyue.top/Article/details/gt2aviultdy.html

PHP:  curl_multi_init() 系列
来源：http://dali.iojbl.cn/Article/details/gt2bpozaofh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenlongwang.top/Article/details/gt2lhlikjta.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hywenlv.cn/Article/details/gt2ofzvuaqr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.kuanghao11.cn/Article/details/gt2vxewxqif.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hfpthk.cn/Article/details/gt2yaoocazy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zdqjudy.top/Article/details/gt2mqkwzlpn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yangfankeji.com/Article/details/gt2guilzprn.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2pdwkjvir.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinqigufen.top/Article/details/gt2uekvslxc.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2ikflctex.html

[M01] 读取命令行参数
来源：http://dali.tanke756.top/Article/details/gt2nmegpvbg.html

Py:   sys.argv[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sqacikat.html

PHP:  $argv;  $argc;
来源：http://dali.zycfv.cn/Article/details/gt2pzhhxtto.html

JS:   process.argv.slice(2)
来源：http://dali.jyoumei.cn/Article/details/gt2yxpacgqs.html

TS:   process.argv.slice(2)
来源：http://dali.hfpthk.cn/Article/details/gt2xrsapfex.html

Java: args 数组（main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dmtazswg.html

Go:   os.Args[1:]
来源：http://dali.gotoacloud.top/Article/details/gt2nvvsjlgl.html

Ruby: ARGV
来源：http://dali.zhoulong.xyz/Article/details/gt2rzqdaxqp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.kuanghao11.cn/Article/details/gt2zcmcpxta.html

[M02] 读取环境变量
来源：http://dali.yanxiufei.cn/Article/details/gt2ekakbgmr.html

Py:   os.environ.get("HOME")
来源：http://dali.fengsongda.top/Article/details/gt2qahoidfn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.smart0.xyz/Article/details/gt2darfmexf.html

JS:   process.env.HOME
来源：http://dali.hnxiangtu.top/Article/details/gt2cnwufynx.html

TS:   process.env.HOME
来源：http://dali.gzhubu.top/Article/details/gt2qomxzuiw.html

Java: System.getenv("HOME")
来源：http://dali.nanxinkj.top/Article/details/gt2hhcahmhk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yonumen.top/Article/details/gt2foojsfyh.html

Ruby: ENV["HOME"]
来源：http://dali.xinyue.icu/Article/details/gt2kxtgerqy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gt2wqeygcrl.html

[M03] 执行外部命令
来源：http://dali.xinyue.icu/Article/details/gt2opbixpgh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenjidiqi.icu/Article/details/gt2esnbezat.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinqigfzy.top/Article/details/gt2wqoimdvo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cheryme.top/Article/details/gt2cnndpmjq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.aibaodan.cn/Article/details/gt2emutfwak.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jyoumei.cn/Article/details/gt2qrlkuorw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sysykeji.top/Article/details/gt2ybrdbcvq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.haohaochexian.top/Article/details/gt2xcdnwxvo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.pengpengdd.cyou/Article/details/gt2ozqiyedy.html

[M04] 获取当前工作目录
来源：http://dali.yonumen.top/Article/details/gt2wgzzrcfi.html

Py:   os.getcwd()
来源：http://dali.sysykeji.top/Article/details/gt2ontaawat.html

PHP:  getcwd();
来源：http://dali.gogol.net.cn/Article/details/gt2loiyjvhl.html

JS:   process.cwd()
来源：http://dali.jinqigfzy.top/Article/details/gt2wrxnyxdv.html

TS:   process.cwd()
来源：http://dali.yuxming.cn/Article/details/gt2ecjddoxe.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yongpay.top/Article/details/gt2whuatbtg.html

Go:   os.Getwd()
来源：http://dali.pycfn.com/Article/details/gt2qfnggkcc.html

Ruby: Dir.pwd
来源：http://dali.tian-w.cn/Article/details/gt2eslysdkp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.wangshuangyany.cn/Article/details/gt2zjinojnn.html

[M05] 设置退出码
来源：http://dali.jinqigfzy.top/Article/details/gt2gjwzjyga.html

Py:   sys.exit(1)
来源：http://dali.ydzc1.top/Article/details/gt2bklyodiy.html

PHP:  exit(1);
来源：http://dali.sysykeji.top/Article/details/gt2bodubwks.html

JS:   process.exit(1)
来源：http://dali.daria6918.cn/Article/details/gt2qpxbwxtp.html

TS:   process.exit(1)
来源：http://dali.xinyue.icu/Article/details/gt2oibwouoz.html

Java: System.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2loptpoee.html

Go:   os.Exit(1)
来源：http://dali.sysykeji.top/Article/details/gt2qtuwbzgo.html

Ruby: exit 1
来源：http://dali.birdmap.top/Article/details/gt2icmnohdu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bmqbgfab.html

[M06] 向标准错误输出
来源：http://dali.iojbl.cn/Article/details/gt2cazoozpu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tidlzwcv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cashguo.top/Article/details/gt2eclksgmo.html

JS:   console.error("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vynirqdk.html

TS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gt2qyiwdxlz.html

Java: System.err.println("err")
来源：http://dali.yangfankeji.com/Article/details/gt2wqdbavwb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2waficpck.html

Ruby: warn "err"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2neqvlmyk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.redwolf501.top/Article/details/gt2xcrswzzq.html

[M07] 判断是否为主入口
来源：http://dali.snrcjt.cn/Article/details/gt2ztbtvirq.html


<!-- 参考信息 -->