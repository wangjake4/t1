代发 wailian999

J. 日期与时间
来源：http://dali.zycfv.cn/Article/details/gt2cjszuhqw.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2papzwmnr.html

[J01] 获取当前时间
来源：http://dali.tian-w.cn/Article/details/gt2qmxitagn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.fzhhl.top/Article/details/gt2ozgpvyic.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hammf.cn/Article/details/gt2votzsphk.html

JS:   new Date();  Date.now()
来源：http://dali.havefunace.top/Article/details/gt2wglefnvx.html

TS:   new Date();  Date.now()
来源：http://dali.hfpthk.cn/Article/details/gt2awzbmmrj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinqigfzy.top/Article/details/gt2sovvqiqy.html

Go:   time.Now()
来源：http://dali.yvedp.cn/Article/details/gt2pvagrzrn.html

Ruby: Time.now
来源：http://dali.wangshuangyany.cn/Article/details/gt2okwvjxzc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.bjfxy.top/Article/details/gt2puonvmvn.html

[J02] 格式化输出
来源：http://dali.wangshuangyany.cn/Article/details/gt2ltkzztge.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.feifeiyinyue.top/Article/details/gt2fmbrezmj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.andypj.xyz/Article/details/gt2jonezzfo.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hywenlv.cn/Article/details/gt2vhbrmhgw.html

TS:   d.toISOString()
来源：http://dali.zhengqikj.top/Article/details/gt2tbnabdxw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.snrcjt.cn/Article/details/gt2edwywliz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.daria6918.cn/Article/details/gt2dvnksmxr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2szqsfinc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.meibo888.top/Article/details/gt2gvyuxcgl.html

[J03] 字符串解析为日期
来源：http://dali.aizwys.cn/Article/details/gt2aofmvprr.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ehwqpu.com/Article/details/gt2xoeyqwlh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.tian-w.cn/Article/details/gt2gmnwftyh.html

JS:   new Date("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gt2axshuite.html

TS:   new Date("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gt2kcccetmy.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gt2ynymhxhh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gt2hschdbey.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gt2bwyslidw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ydzc1.top/Article/details/gt2koxpntyq.html

[J04] 时间戳与日期互转
来源：http://dali.316326.xyz/Article/details/gt2dzubjxwh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gzhubu.top/Article/details/gt2mdqekwcp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gzhubu.top/Article/details/gt2dryhnnfg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.aibaodan.cn/Article/details/gt2ylfgnihl.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qjuzjrut.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sweek.top/Article/details/gt2wtaafxzl.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ppjwa.cn/Article/details/gt2xkvgedpf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.fengsongda.top/Article/details/gt2uvijeswd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.tanke756.top/Article/details/gt2qmzbuxmc.html

[J05] 时间加减（加 7 天）
来源：http://dali.pycfn.com/Article/details/gt2kgtghpil.html

Py:   now + timedelta(days=7)
来源：http://dali.cucudq.cn/Article/details/gt2uyxxvkwi.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.tian-w.cn/Article/details/gt2jgkdcwko.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.c1oappe.top/Article/details/gt2mqnadddu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cdnleiting.top/Article/details/gt2dfdfjvfq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cashguo.top/Article/details/gt2rwetrcdo.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.fengsongda.top/Article/details/gt2enxqwiug.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhongyouzk.top/Article/details/gt2dawkkapy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cheryme.top/Article/details/gt2bsustitf.html

[J06] 计算两时间之差
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsvyvwo.html

Py:   (end - start).total_seconds()
来源：http://dali.snrcjt.cn/Article/details/gt2oprmyrkf.html

PHP:  $end->diff($start)->days;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cujjjzjw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yongpay.top/Article/details/gt2axftsgle.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.feifeiyinyue.top/Article/details/gt2rwfiagbb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zfujhgpb.html

Go:   end.Sub(start).Hours()
来源：http://dali.gotoacloud.top/Article/details/gt2cpvxttkd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.wangdashe.top/Article/details/gt2hfsvdwjy.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinqigfzy.top/Article/details/gt2eyebyjig.html

[J07] 比较两个日期
来源：http://dali.chenlongwang.top/Article/details/gt2ikpzwcfo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.smart0.xyz/Article/details/gt2tabmdsoh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jianghu66.top/Article/details/gt2dbtgovox.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yongpay.top/Article/details/gt2ngwnfeyu.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.daria6918.cn/Article/details/gt2zykmblyn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hywenlv.cn/Article/details/gt2vinosbpx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yueranfly.top/Article/details/gt2fnbsfxxn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gt2ssvyiyfb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yuxming.cn/Article/details/gt2wepxuqla.html

[J08] 提取年月日与星期
来源：http://dali.ybcxt.top/Article/details/gt2mpjunhel.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhengqikj.top/Article/details/gt2ddlulreq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj202588.top/Article/details/gt2zovzckji.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinqigufen.top/Article/details/gt2hkgtzaad.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shuidangran.top/Article/details/gt2jmypriau.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shangyingyoupin.top/Article/details/gt2omktzpdc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gogol.net.cn/Article/details/gt2vjlzqdfv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hongshengwenyu.top/Article/details/gt2jdipdmee.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lmucbfvf.html

[J09] 时区处理
来源：http://dali.kuanghao11.cn/Article/details/gt2dauzohpg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zdqjudy.top/Article/details/gt2bpwjcrpq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hongshengwenyu.top/Article/details/gt2qhezppah.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.9152youxi.cn/Article/details/gt2ezkykzwf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxinkj.top/Article/details/gt2kdhzgfgf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gzhubu.top/Article/details/gt2ejbrjipq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.chenjidiqi.icu/Article/details/gt2uexlhqpk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cucudq.cn/Article/details/gt2rxnkyiac.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hysaishi.cn/Article/details/gt2owwvxplc.html

[J10] 取今天 / 本月第一天
来源：http://dali.zycfv.cn/Article/details/gt2etefsvkg.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2diwghvim.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.aizwys.cn/Article/details/gt2dqyunccy.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sweek.top/Article/details/gt2afqwwzpp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gt2sgjoubnd.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2vcmxovfk.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jianghu66.top/Article/details/gt2vvihqeqq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.wangshuangyany.cn/Article/details/gt2vthzruoa.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.iojbl.cn/Article/details/gt2yhuczmqg.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2jdiedsbm.html

K. JSON 与序列化
来源：http://dali.cqqwz.cn/Article/details/gt2daxsbsxu.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2vabhbkjg.html

[K01] 对象转 JSON 字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fozrgdyd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.fzhhl.top/Article/details/gt2ozcjbgsj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lswivhbf.html

JS:   JSON.stringify(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2mqkbqtbf.html

TS:   JSON.stringify(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2hwtmatsn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xuetiantiany.cn/Article/details/gt2oumfjrhw.html

Go:   json.Marshal(obj)
来源：http://dali.sxryk.cn/Article/details/gt2qzcmpyqe.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hnqzz.top/Article/details/gt2poxvcjyx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.birdmap.top/Article/details/gt2jrzotcmc.html

[K02] JSON 字符串转对象
来源：http://dali.pycfn.com/Article/details/gt2zqgokvhl.html

Py:   json.loads(s)
来源：http://dali.yuanzhike.top/Article/details/gt2ehbdmemi.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sxryk.cn/Article/details/gt2ivugwwim.html

JS:   JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gt2cuejxhgz.html

TS:   JSON.parse(s)
来源：http://dali.fengsongda.top/Article/details/gt2vrirzvpg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sweek.top/Article/details/gt2ywgefsbx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhixingplan.top/Article/details/gt2jdjrdpgw.html

Ruby: JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gt2uqkalrgt.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ybcxt.top/Article/details/gt2pikmaloz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ehwqpu.com/Article/details/gt2hdwnzpbe.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hnqzz.top/Article/details/gt2yrinewel.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gogol.net.cn/Article/details/gt2wufupxso.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gogol.net.cn/Article/details/gt2zdvhqrvd.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ivvv.top/Article/details/gt2lnuzfbbf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yonumen.top/Article/details/gt2qpcjbxea.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cucudq.cn/Article/details/gt2ysnijapc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2ljycwunx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.guowangkeji.top/Article/details/gt2sqeqjcfl.html

[K04] 读取 JSON 文件
来源：http://dali.yangfankeji.com/Article/details/gt2hwfxxpyr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gogol.net.cn/Article/details/gt2zqblwelm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ehwqpu.com/Article/details/gt2qzopjwui.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.vqdsnc.cn/Article/details/gt2icbtjptn.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ydzc1.top/Article/details/gt2hfoqghgz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yueranfly.top/Article/details/gt2wzpgcrmz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinqigfzy.top/Article/details/gt2sffbrets.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yangfankeji.com/Article/details/gt2fmavzveu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shuidangran.top/Article/details/gt2vmokvxtw.html

[K05] 深拷贝对象
来源：http://dali.yuxming.cn/Article/details/gt2httqerlq.html

Py:   copy.deepcopy(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2wtnmcfsk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cdnleiting.top/Article/details/gt2zapssvdw.html

JS:   structuredClone(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2erymmppp.html

TS:   structuredClone(obj)
来源：http://dali.shuidangran.top/Article/details/gt2trsokzln.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.pycfn.com/Article/details/gt2gzlkmkwb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.daxiang520.top/Article/details/gt2ybragjha.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zdqjudy.top/Article/details/gt2gfsebcsv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hnxiangtu.top/Article/details/gt2janzypyd.html

[K06] 解析 URL 查询串
来源：http://dali.guannengcc.top/Article/details/gt2afwmpbcl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ydzc1.top/Article/details/gt2blzdipav.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ivvv.top/Article/details/gt2uzsqqcvi.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sufxvd.cn/Article/details/gt2rqgvbqtl.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxuanxn.top/Article/details/gt2ajjfxatz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xuanzx.com/Article/details/gt2auujoyht.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhiwuduotai.top/Article/details/gt2yamcqngi.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gt2mmrcwowm.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hzmohpja.html

[K07] 进制转换
来源：http://dali.jqgufenzy.top/Article/details/gt2lrzngrjl.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gt2bgqihcyz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhoulong.xyz/Article/details/gt2rktlebmq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gt2uxcnbwcc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yzzeniwi.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nlbdpkes.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yj20258888.top/Article/details/gt2wjcsqicq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.nanxuanxn.top/Article/details/gt2lsvaijku.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gt2plnoltsd.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.andypj.xyz/Article/details/gt2zgoyoqoq.html

Py:   pickle.dumps(obj)
来源：http://dali.tian-w.cn/Article/details/gt2ycomnjge.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.iojbl.cn/Article/details/gt2fhtrzdcl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.c1oappe.top/Article/details/gt2nropynyz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigfzy.top/Article/details/gt2stdrrban.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.svipenyu.cn/Article/details/gt2hvhlwiig.html

Go:   encoding/gob
来源：http://dali.zdqjudy.top/Article/details/gt2rlykfiou.html

Ruby: Marshal.dump(obj)
来源：http://dali.xinyue.icu/Article/details/gt2mmhcksgv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ehwqpu.com/Article/details/gt2dxdbqenc.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2obgmwetm.html

L. 网络请求
来源：http://dali.guannengcc.top/Article/details/gt2ysaafumz.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2eezkupbr.html

[L01] 发送 GET 请求
来源：http://dali.shangyingyoupin.top/Article/details/gt2rbllckvs.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.redwolf501.top/Article/details/gt2mtvsycpp.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinqigufen.top/Article/details/gt2hpyozrwc.html

JS:   await fetch(url)
来源：http://dali.zdqjudy.top/Article/details/gt2gmtvdgfh.html

TS:   await fetch(url)
来源：http://dali.iojbl.cn/Article/details/gt2cxvehxcw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wemhuiwf.html

Go:   resp, err := http.Get(url)
来源：http://dali.daria6918.cn/Article/details/gt2iqaxtusb.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2rqpsgocf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xylfe.cn/Article/details/gt2mjirneum.html

[L02] 发送 POST JSON
来源：http://dali.feifeiyinyue.top/Article/details/gt2ucljqdui.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xinyue.icu/Article/details/gt2qosfrphx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhengqikj.top/Article/details/gt2kiardlsr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.quarkkingdee.top/Article/details/gt2ctjzsuod.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sweek.top/Article/details/gt2nelgilsc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sufxvd.cn/Article/details/gt2kybctmqz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xinyue.icu/Article/details/gt2ocxawgec.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.9152youxi.cn/Article/details/gt2iocuwvhq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.guowangkeji.top/Article/details/gt2ohjftlti.html

[L03] 设置自定义请求头
来源：http://dali.jqgufenzy.top/Article/details/gt2astvnair.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.nwbrower.top/Article/details/gt2fekuxgus.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.nwbrower.top/Article/details/gt2wvmruqyw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.redwolf501.top/Article/details/gt2kwnbrmlp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.kuanghao11.cn/Article/details/gt2plcgqdyh.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gkqxqsas.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.smart0.xyz/Article/details/gt2turphfug.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ydzc1.top/Article/details/gt2kqvlmuir.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yangfankeji.com/Article/details/gt2lpqdngjf.html

[L04] 设置超时
来源：http://dali.yj20258.top/Article/details/gt2zdgwyilz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.c1oappe.top/Article/details/gt2utatvjtd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.wangdashe.top/Article/details/gt2xsditelp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aizwys.cn/Article/details/gt2caeumkvh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258888.top/Article/details/gt2lmpktncc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hammf.cn/Article/details/gt2zfnmacyg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.nwbrower.top/Article/details/gt2ykhxrwse.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj20258888.top/Article/details/gt2zhwgbmmb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ppjwa.cn/Article/details/gt2inajiqov.html

[L05] 上传文件（multipart）
来源：http://dali.yueranfly.top/Article/details/gt2pmhmxqrc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.guannengcc.top/Article/details/gt2fidxytgf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sxryk.cn/Article/details/gt2fsypfaun.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yanxiufei.cn/Article/details/gt2cccfzmxh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuanzx.com/Article/details/gt2yrrdlqlc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yvedp.cn/Article/details/gt2xznqhbmn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cheryme.top/Article/details/gt2pfpycesb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hammf.cn/Article/details/gt2vrytoodl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2rvaomuax.html

[L06] 解析响应为 JSON
来源：http://dali.guowangkeji.top/Article/details/gt2omdsjanm.html

Py:   resp.json()
来源：http://dali.hongshengwenyu.top/Article/details/gt2tqptuwhz.html

PHP:  json_decode($body, true);
来源：http://dali.ydzc1.top/Article/details/gt2zmkjmjxu.html

JS:   await resp.json()
来源：http://dali.iojbl.cn/Article/details/gt2ulgkpdxl.html

TS:   await resp.json()
来源：http://dali.jinqigufen.top/Article/details/gt2yzxklbxo.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hfpthk.cn/Article/details/gt2kevfncba.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shuidangran.top/Article/details/gt2fbjmfcpn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.svipenyu.cn/Article/details/gt2cubggoff.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jiagoushi.top/Article/details/gt2zvrlcsih.html

[L07] 处理 HTTP 状态码
来源：http://dali.316326.xyz/Article/details/gt2cyrzomll.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hysaishi.cn/Article/details/gt2gpjycuuf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.fengsongda.top/Article/details/gt2aquzeaoh.html

JS:   resp.ok;  resp.status
来源：http://dali.mhx1999.top/Article/details/gt2xqagvrlj.html

TS:   resp.ok;  resp.status
来源：http://dali.snrcjt.cn/Article/details/gt2dqnjghxo.html

Java: resp.statusCode()
来源：http://dali.gzhubu.top/Article/details/gt2xvhkezgn.html

Go:   resp.StatusCode
来源：http://dali.guannengcc.top/Article/details/gt2dwmjnkav.html

Ruby: resp.code.to_i
来源：http://dali.chenlongwang.top/Article/details/gt2buxkrxig.html

C#:   (int)resp.StatusCode
来源：http://dali.cheryme.top/Article/details/gt2lzdnnyuc.html

[L08] 并发请求多个地址
来源：http://dali.ivvv.top/Article/details/gt2oapgrwva.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ydzc1.top/Article/details/gt2ockugqte.html

PHP:  curl_multi_init() 系列
来源：http://dali.pengpengdd.cyou/Article/details/gt2qbptitcu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gt2vghnxvwl.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shzxlz.cn/Article/details/gt2zhpdfrim.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yongpay.top/Article/details/gt2vkfjivph.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yueranfly.top/Article/details/gt2qqjkpnix.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.fengsongda.top/Article/details/gt2pdttswax.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hfpthk.cn/Article/details/gt2mjnikwth.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2xbcosqga.html

M. 命令行 / 进程 / 环境
来源：http://dali.xylfe.cn/Article/details/gt2byabcvqr.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2vzqghlui.html

[M01] 读取命令行参数
来源：http://dali.sufxvd.cn/Article/details/gt2vnmvcclt.html

Py:   sys.argv[1:]
来源：http://dali.ehwqpu.com/Article/details/gt2mamnqwfc.html

PHP:  $argv;  $argc;
来源：http://dali.9152youxi.cn/Article/details/gt2fggpacfa.html

JS:   process.argv.slice(2)
来源：http://dali.cdnleiting.top/Article/details/gt2xicyywyt.html

TS:   process.argv.slice(2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ccwjqdlo.html

Java: args 数组（main 方法参数）
来源：http://dali.shzxlz.cn/Article/details/gt2oyvonoju.html

Go:   os.Args[1:]
来源：http://dali.0kj1m.cn/Article/details/gt2ijgclxet.html

Ruby: ARGV
来源：http://dali.feifeiyinyue.top/Article/details/gt2aaloqxxo.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yvedp.cn/Article/details/gt2pkhesplv.html

[M02] 读取环境变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hoiuamox.html

Py:   os.environ.get("HOME")
来源：http://dali.zdqjudy.top/Article/details/gt2gfoolblf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jiagoushi.top/Article/details/gt2qtvjnxux.html

JS:   process.env.HOME
来源：http://dali.yuanzhike.top/Article/details/gt2iomesfmj.html

TS:   process.env.HOME
来源：http://dali.smart0.xyz/Article/details/gt2yuwrqzwq.html

Java: System.getenv("HOME")
来源：http://dali.sufxvd.cn/Article/details/gt2trzjkyge.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gt2kgmmpngn.html

Ruby: ENV["HOME"]
来源：http://dali.pengpengdd.cyou/Article/details/gt2pficmzux.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.guowangkeji.top/Article/details/gt2kkldpgde.html

[M03] 执行外部命令
来源：http://dali.0kj1m.cn/Article/details/gt2rtxysoqh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hysaishi.cn/Article/details/gt2tbtrmhfp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.havefunace.top/Article/details/gt2nnwfyeue.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhixingplan.top/Article/details/gt2umxhpkgp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sufxvd.cn/Article/details/gt2gkqdfczk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.nwbrower.top/Article/details/gt2onrcupap.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.c1oappe.top/Article/details/gt2pzmjjswj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hongshengwenyu.top/Article/details/gt2nmoumhmb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.andypj.xyz/Article/details/gt2jjhrapze.html

[M04] 获取当前工作目录
来源：http://dali.ehwqpu.com/Article/details/gt2jggqshwm.html

Py:   os.getcwd()
来源：http://dali.wangdashe.top/Article/details/gt2zetuiaxv.html

PHP:  getcwd();
来源：http://dali.shuidangran.top/Article/details/gt2nprbylvp.html

JS:   process.cwd()
来源：http://dali.dashuyun.cn/Article/details/gt2wadztgek.html

TS:   process.cwd()
来源：http://dali.svipenyu.cn/Article/details/gt2jbigbnnh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.nwbrower.top/Article/details/gt2fscfwytk.html

Go:   os.Getwd()
来源：http://dali.zdqjudy.top/Article/details/gt2yakounfl.html

Ruby: Dir.pwd
来源：http://dali.gaohongyu789.top/Article/details/gt2gryygctr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shuidangran.top/Article/details/gt2jepyitfr.html

[M05] 设置退出码
来源：http://dali.tanke756.top/Article/details/gt2ingnhdxu.html

Py:   sys.exit(1)
来源：http://dali.wangdashe.top/Article/details/gt2samlpucl.html

PHP:  exit(1);
来源：http://dali.ppjwa.cn/Article/details/gt2abrroyee.html

JS:   process.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gt2kijparfp.html

TS:   process.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gt2jnomslam.html

Java: System.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gt2msmxmoqo.html

Go:   os.Exit(1)
来源：http://dali.smart0.xyz/Article/details/gt2pzilhztf.html

Ruby: exit 1
来源：http://dali.jqgfzy.top/Article/details/gt2hmyfedqj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jlsjyb.cn/Article/details/gt2cecfsxxz.html

[M06] 向标准错误输出
来源：http://dali.zhiwuduotai.top/Article/details/gt2avinmaea.html

Py:   print("err", file=sys.stderr)
来源：http://dali.chenzaomai.com/Article/details/gt2gfdsnkjr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yuanzhike.top/Article/details/gt2duqcnrdn.html

JS:   console.error("err")
来源：http://dali.aibaodan.cn/Article/details/gt2daacjgtp.html

TS:   console.error("err")
来源：http://dali.quarkkingdee.top/Article/details/gt2nxlalint.html

Java: System.err.println("err")
来源：http://dali.guowangkeji.top/Article/details/gt2adunsdfd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.mhx1999.top/Article/details/gt2qypbjkpo.html

Ruby: warn "err"
来源：http://dali.feifeiyinyue.top/Article/details/gt2ixxkbtau.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xuetiantiany.cn/Article/details/gt2safmyppw.html

[M07] 判断是否为主入口
来源：http://dali.yuanzhike.top/Article/details/gt2moptwuaj.html


<!-- 参考信息 -->