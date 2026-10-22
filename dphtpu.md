代发 wailian999

J. 日期与时间
来源：http://dali.sysykeji.top/Article/details/gt2dnoceklb.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2olqcuzar.html

[J01] 获取当前时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2trvlfmbp.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj20258888.top/Article/details/gt2wyzbidkb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinqigfzy.top/Article/details/gt2wffzlcyc.html

JS:   new Date();  Date.now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vpewcuhj.html

TS:   new Date();  Date.now()
来源：http://dali.pycfn.com/Article/details/gt2ipucgxno.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sxryk.cn/Article/details/gt2legubeao.html

Go:   time.Now()
来源：http://dali.gotoacloud.top/Article/details/gt2aquhognr.html

Ruby: Time.now
来源：http://dali.daxiang520.top/Article/details/gt2aczxsjme.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cqqwz.cn/Article/details/gt2vebtnljh.html

[J02] 格式化输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bhnzlhxc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ybcxt.top/Article/details/gt2egccmvce.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jqgufenzy.top/Article/details/gt2tpdmgfrf.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.andypj.xyz/Article/details/gt2tcbgubjy.html

TS:   d.toISOString()
来源：http://dali.ybcxt.top/Article/details/gt2qcykferj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cashguo.top/Article/details/gt2unvxarzc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yanxiufei.cn/Article/details/gt2erfkquqz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gaohongyu789.top/Article/details/gt2ibeqsumd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ojwizray.html

[J03] 字符串解析为日期
来源：http://dali.zycfv.cn/Article/details/gt2ucjoletk.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cucudq.cn/Article/details/gt2lufqhxgj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj20258.top/Article/details/gt2fgriqowu.html

JS:   new Date("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bewzdzoe.html

TS:   new Date("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gt2eksjtirw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2clpafvhj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gt2cshihwku.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gt2yvmupegp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhixingplan.top/Article/details/gt2rlukaqqn.html

[J04] 时间戳与日期互转
来源：http://dali.cheryme.top/Article/details/gt2nzggtqqv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2epikeqxn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.mhx1999.top/Article/details/gt2tmybrnkl.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yongpay.top/Article/details/gt2sdkvycok.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhongyouzk.top/Article/details/gt2hvzxhdoh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.chenjidiqi.icu/Article/details/gt2boelvvtf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.fengsongda.top/Article/details/gt2wsyohzsp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hnqzz.top/Article/details/gt2xbgddmna.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hnxiangtu.top/Article/details/gt2llargdyw.html

[J05] 时间加减（加 7 天）
来源：http://dali.smart0.xyz/Article/details/gt2lanlqrab.html

Py:   now + timedelta(days=7)
来源：http://dali.snrcjt.cn/Article/details/gt2slsoxhvb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.aizwys.cn/Article/details/gt2vxxuytzh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgufenzy.top/Article/details/gt2qtvjfulo.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhengqikj.top/Article/details/gt2dxcrbyyg.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2akgddzew.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.andypj.xyz/Article/details/gt2dceobvhn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xylfe.cn/Article/details/gt2jpyddfnu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yj20258888.top/Article/details/gt2rmvslfla.html

[J06] 计算两时间之差
来源：http://dali.gzhubu.top/Article/details/gt2bukckdda.html

Py:   (end - start).total_seconds()
来源：http://dali.hammf.cn/Article/details/gt2pznumzbw.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhengqikj.top/Article/details/gt2siedqjgu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xuanzx.com/Article/details/gt2piyeeygc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jyoumei.cn/Article/details/gt2ezohjeeg.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ydzc1.top/Article/details/gt2jjtpxidn.html

Go:   end.Sub(start).Hours()
来源：http://dali.nanxuanxn.top/Article/details/gt2unxcxdzs.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gotoacloud.top/Article/details/gt2khfqfxvn.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj20258.top/Article/details/gt2rualywvc.html

[J07] 比较两个日期
来源：http://dali.yueranfly.top/Article/details/gt2wqrahtnd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.bjfxy.top/Article/details/gt2hqktebqa.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xinyue.icu/Article/details/gt2hzpvnyfz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhiwuduotai.top/Article/details/gt2qczwnoil.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.tian-w.cn/Article/details/gt2zmtpwzjv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2loidnlrp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.tianlin.xyz/Article/details/gt2ioiobgcz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xuetiantiany.cn/Article/details/gt2rmcsgozs.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gt2velamuml.html

[J08] 提取年月日与星期
来源：http://dali.chenlongwang.top/Article/details/gt2droxglep.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zdqjudy.top/Article/details/gt2tucbiwjy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj20258888.top/Article/details/gt2jxxsmknc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.feifeiyinyue.top/Article/details/gt2uphtcugv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nanxuanxn.top/Article/details/gt2xkeugoko.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yonumen.top/Article/details/gt2ydkflsfi.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hnxiangtu.top/Article/details/gt2hhywkrvu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.dianchejie.cn/Article/details/gt2bbmeuiqv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yangfankeji.com/Article/details/gt2tlwsdtdk.html

[J09] 时区处理
来源：http://dali.chenzaomai.com/Article/details/gt2lnmupctn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yrrnlpyg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cucudq.cn/Article/details/gt2sujmhwnf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenjidiqi.icu/Article/details/gt2liqxaujq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.snrcjt.cn/Article/details/gt2kcexzrda.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.aizwys.cn/Article/details/gt2boxwzuum.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.mhx1999.top/Article/details/gt2zcxwbupn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yj202588.top/Article/details/gt2wbvhxlsn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gogol.net.cn/Article/details/gt2bmfdvlvx.html

[J10] 取今天 / 本月第一天
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yesrinkp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gzhubu.top/Article/details/gt2ktukfblj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sweek.top/Article/details/gt2hbbzyqoc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yueranfly.top/Article/details/gt2vejiagcr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nanxinkj.top/Article/details/gt2zubpuweg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2woymbqmk.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jqgufenzy.top/Article/details/gt2ahejxpjs.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shzxlz.cn/Article/details/gt2ptfclkpd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hammf.cn/Article/details/gt2xsrxrarc.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2addznccc.html

K. JSON 与序列化
来源：http://dali.nwbrower.top/Article/details/gt2vhquorjj.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2aaleuuzd.html

[K01] 对象转 JSON 字符串
来源：http://dali.xuanzx.com/Article/details/gt2uiphcnui.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.andypj.xyz/Article/details/gt2jjmtzntf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yangfankeji.com/Article/details/gt2aauzjvxb.html

JS:   JSON.stringify(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2pcraprya.html

TS:   JSON.stringify(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aqpqzwux.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cucudq.cn/Article/details/gt2hcqhiaqi.html

Go:   json.Marshal(obj)
来源：http://dali.cashguo.top/Article/details/gt2lcfedpaz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xuanzx.com/Article/details/gt2knckeobz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xdsjlhqp.html

[K02] JSON 字符串转对象
来源：http://dali.hysaishi.cn/Article/details/gt2meeddamy.html

Py:   json.loads(s)
来源：http://dali.xziqi.cn/Article/details/gt2yzulwqwx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hammf.cn/Article/details/gt2hxuqlnku.html

JS:   JSON.parse(s)
来源：http://dali.dianchejie.cn/Article/details/gt2ylvcdmuc.html

TS:   JSON.parse(s)
来源：http://dali.jianghu66.top/Article/details/gt2lysjwfpd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hywenlv.cn/Article/details/gt2aztuyzhz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nanxuanxn.top/Article/details/gt2jklkscyd.html

Ruby: JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gt2ndvyqole.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xziqi.cn/Article/details/gt2ymrrefvo.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jiagoushi.top/Article/details/gt2iuupmmvd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.mhx1999.top/Article/details/gt2cqmbydbt.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ppjwa.cn/Article/details/gt2ztjaoacn.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xziqi.cn/Article/details/gt2fhxaazve.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yiyiysxk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.birdmap.top/Article/details/gt2fhvavbkd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yvedp.cn/Article/details/gt2vuqyxjdn.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2dcwwaxfy.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.wangshuangyany.cn/Article/details/gt2nhceoepp.html

[K04] 读取 JSON 文件
来源：http://dali.tianlin.xyz/Article/details/gt2xpysdzyz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.chenzaomai.com/Article/details/gt2gajstmdb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hfpthk.cn/Article/details/gt2lsmtonuh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yvedp.cn/Article/details/gt2grpvascc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zycfv.cn/Article/details/gt2ofkgzofv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jianghu66.top/Article/details/gt2zknkzfja.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shzxlz.cn/Article/details/gt2qctfcijv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhengqikj.top/Article/details/gt2gjlkzzlb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2dyiawamo.html

[K05] 深拷贝对象
来源：http://dali.ydzc1.top/Article/details/gt2gjtmgmlt.html

Py:   copy.deepcopy(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2bbnoaxsa.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yj20258888.top/Article/details/gt2pubpjpzo.html

JS:   structuredClone(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2zlgxbifl.html

TS:   structuredClone(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2arqbrkwr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nanxinkj.top/Article/details/gt2mnznsfrh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gzhubu.top/Article/details/gt2mdbevqmu.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhixingplan.top/Article/details/gt2szamkqlq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.vqdsnc.cn/Article/details/gt2qwnoqnfg.html

[K06] 解析 URL 查询串
来源：http://dali.dashuyun.cn/Article/details/gt2yjfwphie.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sufxvd.cn/Article/details/gt2xbrntqjv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenjidiqi.icu/Article/details/gt2fbxqgxsy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yvedp.cn/Article/details/gt2btthoork.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.havefunace.top/Article/details/gt2lhytcgjr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ffnxpobq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2huisgryi.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.mhx1999.top/Article/details/gt2oehmjqty.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gt2sbljavsq.html

[K07] 进制转换
来源：http://dali.jyoumei.cn/Article/details/gt2uovzfvqw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gt2nezeeqby.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sweek.top/Article/details/gt2vlqwgrdg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gt2ejzwkcbz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gt2duttkzeh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yj202588.top/Article/details/gt2ipokiruw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yuanzhike.top/Article/details/gt2zzsdwmih.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinqigfzy.top/Article/details/gt2uzugnbud.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gt2cedsnrxt.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hysaishi.cn/Article/details/gt2drrdvjic.html

Py:   pickle.dumps(obj)
来源：http://dali.mhx1999.top/Article/details/gt2nrgsejru.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cdnleiting.top/Article/details/gt2dnjzygvx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gsbzvsot.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.kuanghao11.cn/Article/details/gt2bipqvjun.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.nwbrower.top/Article/details/gt2wqcfpdni.html

Go:   encoding/gob
来源：http://dali.0kj1m.cn/Article/details/gt2konbdjoa.html

Ruby: Marshal.dump(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2vbbhrerp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.tianlin.xyz/Article/details/gt2srrjtwzx.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2pexgwwbv.html

L. 网络请求
来源：http://dali.fzhhl.top/Article/details/gt2ecgafolo.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2wtslryxb.html

[L01] 发送 GET 请求
来源：http://dali.smart0.xyz/Article/details/gt2bhswbixv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gotoacloud.top/Article/details/gt2tfwxyaot.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zycfv.cn/Article/details/gt2zilnikyc.html

JS:   await fetch(url)
来源：http://dali.haohaochexian.top/Article/details/gt2dvxsjdne.html

TS:   await fetch(url)
来源：http://dali.daxiang520.top/Article/details/gt2qbgocsco.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.kuanghao11.cn/Article/details/gt2byyssmsf.html

Go:   resp, err := http.Get(url)
来源：http://dali.shuidangran.top/Article/details/gt2wrgfuupk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2mgggbidm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.wangdashe.top/Article/details/gt2zybguhex.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ejhcwcnr.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cdnleiting.top/Article/details/gt2axnoauyj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinqigufen.top/Article/details/gt2leaqxzew.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cqqwz.cn/Article/details/gt2fxeyiqca.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.meibo888.top/Article/details/gt2lhgksabg.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ydzc1.top/Article/details/gt2lsgstykf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sweek.top/Article/details/gt2dvpoevfx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hysaishi.cn/Article/details/gt2mluylakd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gogol.net.cn/Article/details/gt2henoteve.html

[L03] 设置自定义请求头
来源：http://dali.jlsjyb.cn/Article/details/gt2jtewgpfc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gzhubu.top/Article/details/gt2suveghqg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hnxiangtu.top/Article/details/gt2kokgqrdk.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shangyingyoupin.top/Article/details/gt2epgxzfgm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shangyingyoupin.top/Article/details/gt2szkzdhaq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2faxmdiup.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2utztjrkr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xuanzx.com/Article/details/gt2txhnpmfj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2meaeapak.html

[L04] 设置超时
来源：http://dali.sxryk.cn/Article/details/gt2qvguhopa.html

Py:   requests.get(url, timeout=5)
来源：http://dali.quarkkingdee.top/Article/details/gt2qzwalbsf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gaohongyu789.top/Article/details/gt2lxkwrgng.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nwbrower.top/Article/details/gt2oxzvbgcc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hywenlv.cn/Article/details/gt2ossjtgjm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.kuanghao11.cn/Article/details/gt2sqwaxglp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.nwbrower.top/Article/details/gt2fwkaimho.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cqqwz.cn/Article/details/gt2wgaicmcw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenjidiqi.icu/Article/details/gt2eizxknva.html

[L05] 上传文件（multipart）
来源：http://dali.svipenyu.cn/Article/details/gt2rwmrgqzj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xuanzx.com/Article/details/gt2xvmgowyf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ibghdndd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenzaomai.com/Article/details/gt2oeuvenmq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.316326.xyz/Article/details/gt2pqfjqtwe.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xekgxyzk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2fmvkhvdi.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.bjfxy.top/Article/details/gt2gobiuzyg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2hygzlgip.html

[L06] 解析响应为 JSON
来源：http://dali.shuidangran.top/Article/details/gt2jlqvooss.html

Py:   resp.json()
来源：http://dali.zdqjudy.top/Article/details/gt2qkxlkeyl.html

PHP:  json_decode($body, true);
来源：http://dali.wangshuangyany.cn/Article/details/gt2hacrajgd.html

JS:   await resp.json()
来源：http://dali.pycfn.com/Article/details/gt2usezimrl.html

TS:   await resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gt2zoyhpyxn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.snrcjt.cn/Article/details/gt2hmaobixl.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ivvv.top/Article/details/gt2odjgbxxm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yuanzhike.top/Article/details/gt2nvjjsfse.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj202588.top/Article/details/gt2oiyvgnca.html

[L07] 处理 HTTP 状态码
来源：http://dali.hongshengwenyu.top/Article/details/gt2exqbkxrv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.316326.xyz/Article/details/gt2dqeaomvu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sufxvd.cn/Article/details/gt2nrxqlyvi.html

JS:   resp.ok;  resp.status
来源：http://dali.zhongyouzk.top/Article/details/gt2jgoxxamx.html

TS:   resp.ok;  resp.status
来源：http://dali.aizwys.cn/Article/details/gt2rasyrqeu.html

Java: resp.statusCode()
来源：http://dali.xinyue.icu/Article/details/gt2sgkgnxoc.html

Go:   resp.StatusCode
来源：http://dali.jqgfzy.top/Article/details/gt2kipwkdtk.html

Ruby: resp.code.to_i
来源：http://dali.sufxvd.cn/Article/details/gt2tjoeulul.html

C#:   (int)resp.StatusCode
来源：http://dali.zhoulong.xyz/Article/details/gt2jysamsdj.html

[L08] 并发请求多个地址
来源：http://dali.ydzc1.top/Article/details/gt2rbrcxfmu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.dianchejie.cn/Article/details/gt2dhfnjvuk.html

PHP:  curl_multi_init() 系列
来源：http://dali.dianchejie.cn/Article/details/gt2csmipsdy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gt2fpvyokrd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sufxvd.cn/Article/details/gt2lpxlgemj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cuqrhbvc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.smart0.xyz/Article/details/gt2nnlvvrex.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.havefunace.top/Article/details/gt2pkznsjje.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hywenlv.cn/Article/details/gt2zqugxjnp.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2tzoollbh.html

M. 命令行 / 进程 / 环境
来源：http://dali.316326.xyz/Article/details/gt2iafzbjrb.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2jrhrlqja.html

[M01] 读取命令行参数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2krdxbuff.html

Py:   sys.argv[1:]
来源：http://dali.tian-w.cn/Article/details/gt2aggwydnf.html

PHP:  $argv;  $argc;
来源：http://dali.9152youxi.cn/Article/details/gt2htoxmcbf.html

JS:   process.argv.slice(2)
来源：http://dali.bjfxy.top/Article/details/gt2sypauvbr.html

TS:   process.argv.slice(2)
来源：http://dali.haohaochexian.top/Article/details/gt2fvhrcvio.html

Java: args 数组（main 方法参数）
来源：http://dali.zhixingplan.top/Article/details/gt2ltejxrpo.html

Go:   os.Args[1:]
来源：http://dali.yanxiufei.cn/Article/details/gt2kfrghiof.html

Ruby: ARGV
来源：http://dali.gogol.net.cn/Article/details/gt2exypjofb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.andypj.xyz/Article/details/gt2tqjnbsnq.html

[M02] 读取环境变量
来源：http://dali.zhongyouzk.top/Article/details/gt2hejrhvgt.html

Py:   os.environ.get("HOME")
来源：http://dali.yvedp.cn/Article/details/gt2bshtujio.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.bjfxy.top/Article/details/gt2gnkbyhtb.html

JS:   process.env.HOME
来源：http://dali.svipenyu.cn/Article/details/gt2cjdltbpc.html

TS:   process.env.HOME
来源：http://dali.meibo888.top/Article/details/gt2xzxtksev.html

Java: System.getenv("HOME")
来源：http://dali.svipenyu.cn/Article/details/gt2zcyovgzu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ybcxt.top/Article/details/gt2tphndutu.html

Ruby: ENV["HOME"]
来源：http://dali.wangdashe.top/Article/details/gt2qjmxqzhi.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gt2vwvfjaks.html

[M03] 执行外部命令
来源：http://dali.mhx1999.top/Article/details/gt2fvlmupnh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.nwbrower.top/Article/details/gt2qanbnzmz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yangfankeji.com/Article/details/gt2rwncrpro.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ydzc1.top/Article/details/gt2mcflwymy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.0kj1m.cn/Article/details/gt2stuonlkv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.redwolf501.top/Article/details/gt2bauyuanr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xuanzx.com/Article/details/gt2nafavsib.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenzaomai.com/Article/details/gt2cxqsdoxo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iktgcdxh.html

[M04] 获取当前工作目录
来源：http://dali.jyoumei.cn/Article/details/gt2bjlsotai.html

Py:   os.getcwd()
来源：http://dali.havefunace.top/Article/details/gt2coesbzht.html

PHP:  getcwd();
来源：http://dali.wangshuangyany.cn/Article/details/gt2ujjlunmo.html

JS:   process.cwd()
来源：http://dali.pengpengdd.cyou/Article/details/gt2cizokvts.html

TS:   process.cwd()
来源：http://dali.tanke756.top/Article/details/gt2ajhntyus.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhixingplan.top/Article/details/gt2canjjbfl.html

Go:   os.Getwd()
来源：http://dali.chenzaomai.com/Article/details/gt2edmvqzoe.html

Ruby: Dir.pwd
来源：http://dali.tanke756.top/Article/details/gt2ukhfwhsu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jqgufenzy.top/Article/details/gt2knpadhur.html

[M05] 设置退出码
来源：http://dali.wangshuangyany.cn/Article/details/gt2whzkgkro.html

Py:   sys.exit(1)
来源：http://dali.yuxming.cn/Article/details/gt2nxxbaqrb.html

PHP:  exit(1);
来源：http://dali.316326.xyz/Article/details/gt2opoukyjt.html

JS:   process.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lwjcvsnl.html

TS:   process.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gt2apxpydvw.html

Java: System.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gt2wpyukwmw.html

Go:   os.Exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2nwmklhjw.html

Ruby: exit 1
来源：http://dali.cqqwz.cn/Article/details/gt2wnxxmqwf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hysaishi.cn/Article/details/gt2zfajvrql.html

[M06] 向标准错误输出
来源：http://dali.yuanzhike.top/Article/details/gt2jfnnioge.html

Py:   print("err", file=sys.stderr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2abmyjqnb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcshdbz.html

JS:   console.error("err")
来源：http://dali.ydzc1.top/Article/details/gt2knhmmgfn.html

TS:   console.error("err")
来源：http://dali.havefunace.top/Article/details/gt2gpdascrz.html

Java: System.err.println("err")
来源：http://dali.zhiwuduotai.top/Article/details/gt2kjlfuddp.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jyoumei.cn/Article/details/gt2ziydfjie.html

Ruby: warn "err"
来源：http://dali.dashuyun.cn/Article/details/gt2cyaczpxx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.aizwys.cn/Article/details/gt2ubbbgymg.html

[M07] 判断是否为主入口
来源：http://dali.sweek.top/Article/details/gt2unlpomfz.html


<!-- 参考信息 -->