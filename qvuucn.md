代发 wailian999

J. 日期与时间
来源：http://dali.tianlin.xyz/Article/details/gt2wuypdmva.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2cfbhywwb.html

[J01] 获取当前时间
来源：http://dali.bjfxy.top/Article/details/gt2vcuapuht.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shzxlz.cn/Article/details/gt2scunezyw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ehwqpu.com/Article/details/gt2qoiqclyf.html

JS:   new Date();  Date.now()
来源：http://dali.daria6918.cn/Article/details/gt2kperlydg.html

TS:   new Date();  Date.now()
来源：http://dali.dianchejie.cn/Article/details/gt2vcfctfhl.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.aizwys.cn/Article/details/gt2gyzqczri.html

Go:   time.Now()
来源：http://dali.andypj.xyz/Article/details/gt2uanknjru.html

Ruby: Time.now
来源：http://dali.daria6918.cn/Article/details/gt2qflhlpup.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.0kj1m.cn/Article/details/gt2njgraonu.html

[J02] 格式化输出
来源：http://dali.ybcxt.top/Article/details/gt2zravnkal.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenlongwang.top/Article/details/gt2pzihmphc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hammf.cn/Article/details/gt2sghrigps.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.aizwys.cn/Article/details/gt2zzwjrqkc.html

TS:   d.toISOString()
来源：http://dali.fzhhl.top/Article/details/gt2klaydoaj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gotoacloud.top/Article/details/gt2pghgtqgj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.daria6918.cn/Article/details/gt2aznevgxq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhixingplan.top/Article/details/gt2rxyhocjc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.chenjidiqi.icu/Article/details/gt2jjlaonlu.html

[J03] 字符串解析为日期
来源：http://dali.aibaodan.cn/Article/details/gt2kompetze.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.dianchejie.cn/Article/details/gt2cljmklnx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cqqwz.cn/Article/details/gt2inpnrxbi.html

JS:   new Date("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gt2zmzmcrxr.html

TS:   new Date("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gt2dzdtlrbc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gt2baohsagi.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ivvv.top/Article/details/gt2aqstfbfz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gt2aiebsmyr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.snrcjt.cn/Article/details/gt2xljzvzkr.html

[J04] 时间戳与日期互转
来源：http://dali.aibaodan.cn/Article/details/gt2lctfklbu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jianghu66.top/Article/details/gt2tfjfknjj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shangyingyoupin.top/Article/details/gt2zvhzjnhu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sxryk.cn/Article/details/gt2tqupqxfj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pajucaci.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hnqzz.top/Article/details/gt2pfdrbept.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hywenlv.cn/Article/details/gt2sotwqbnv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yvedp.cn/Article/details/gt2fcyqgzsg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.wangdashe.top/Article/details/gt2driemkmd.html

[J05] 时间加减（加 7 天）
来源：http://dali.jlsjyb.cn/Article/details/gt2kxwhvbav.html

Py:   now + timedelta(days=7)
来源：http://dali.xziqi.cn/Article/details/gt2phcnzxys.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2llxrbcdz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2corqwpmh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.quarkkingdee.top/Article/details/gt2qsykebyc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gogol.net.cn/Article/details/gt2jdjtrndp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenzaomai.com/Article/details/gt2gyntcgoc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xziqi.cn/Article/details/gt2slpfjpla.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yj202588.top/Article/details/gt2tfxrrjdc.html

[J06] 计算两时间之差
来源：http://dali.xziqi.cn/Article/details/gt2ndadgkze.html

Py:   (end - start).total_seconds()
来源：http://dali.gogol.net.cn/Article/details/gt2ywnxiowj.html

PHP:  $end->diff($start)->days;
来源：http://dali.hfpthk.cn/Article/details/gt2gyoradwn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cucudq.cn/Article/details/gt2ogweycqe.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gaohongyu789.top/Article/details/gt2zaqpvmxh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.wangdashe.top/Article/details/gt2tbilqqzs.html

Go:   end.Sub(start).Hours()
来源：http://dali.0kj1m.cn/Article/details/gt2uqewegrt.html

Ruby: end - start                 # 返回秒数
来源：http://dali.havefunace.top/Article/details/gt2xmlwjhax.html

C#:   (end - start).TotalSeconds
来源：http://dali.vqdsnc.cn/Article/details/gt2tcbukeoc.html

[J07] 比较两个日期
来源：http://dali.chenlongwang.top/Article/details/gt2uotfojum.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.kuanghao11.cn/Article/details/gt2jpuhphns.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.tian-w.cn/Article/details/gt2ufmxvcxf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sufxvd.cn/Article/details/gt2vdjcohgm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sufxvd.cn/Article/details/gt2cvnkfsdm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.vqdsnc.cn/Article/details/gt2qldodgtc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.pycfn.com/Article/details/gt2dxvldlcj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shangyingyoupin.top/Article/details/gt2sefnwfff.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gt2pkmhpotl.html

[J08] 提取年月日与星期
来源：http://dali.tian-w.cn/Article/details/gt2nsubxstt.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.guowangkeji.top/Article/details/gt2bgeetcxa.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hywenlv.cn/Article/details/gt2vgjmfzfh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xuanzx.com/Article/details/gt2cndhcteb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.meibo888.top/Article/details/gt2xlwpbgbj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.daria6918.cn/Article/details/gt2whbxjwzx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.redwolf501.top/Article/details/gt2bsxubvgz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.dashuyun.cn/Article/details/gt2xirbcjbg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xinyue.icu/Article/details/gt2expddsen.html

[J09] 时区处理
来源：http://dali.0kj1m.cn/Article/details/gt2cwnqtiuc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nanxinkj.top/Article/details/gt2vkkhyogl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.redwolf501.top/Article/details/gt2yywvpvwf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gzhubu.top/Article/details/gt2kumxziso.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guowangkeji.top/Article/details/gt2lpqeneou.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zdqjudy.top/Article/details/gt2ujfcxjxy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hywenlv.cn/Article/details/gt2uiczfbxg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yonumen.top/Article/details/gt2ricqrkch.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sweek.top/Article/details/gt2umtnephd.html

[J10] 取今天 / 本月第一天
来源：http://dali.yonumen.top/Article/details/gt2zslynxsi.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.havefunace.top/Article/details/gt2jhtxqlyb.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cdnleiting.top/Article/details/gt2cdiwwdie.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mrgpvovz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.haohaochexian.top/Article/details/gt2lyffwhfh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xuanzx.com/Article/details/gt2veiabqbe.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.tianlin.xyz/Article/details/gt2ioencfjf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gogol.net.cn/Article/details/gt2vdydyyyd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.tanke756.top/Article/details/gt2uenxfopk.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2carbtryb.html

K. JSON 与序列化
来源：http://dali.zhiwuduotai.top/Article/details/gt2jmtqxlvx.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2srcsyyxm.html

[K01] 对象转 JSON 字符串
来源：http://dali.meibo888.top/Article/details/gt2ordufgph.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yangfankeji.com/Article/details/gt2cfaljfcc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigufen.top/Article/details/gt2sndnwdlu.html

JS:   JSON.stringify(obj)
来源：http://dali.smart0.xyz/Article/details/gt2exfxbiri.html

TS:   JSON.stringify(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2dwjikehb.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinghuilouyu.cn/Article/details/gt2owtvbkjg.html

Go:   json.Marshal(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2duoapjoo.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hbdxrhem.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2pwkuzvza.html

[K02] JSON 字符串转对象
来源：http://dali.svipenyu.cn/Article/details/gt2tkmwnznt.html

Py:   json.loads(s)
来源：http://dali.nanxinkj.top/Article/details/gt2bpowppcn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cucudq.cn/Article/details/gt2zfakdkpj.html

JS:   JSON.parse(s)
来源：http://dali.cashguo.top/Article/details/gt2ojeerwsa.html

TS:   JSON.parse(s)
来源：http://dali.jyoumei.cn/Article/details/gt2icdlrcax.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.daria6918.cn/Article/details/gt2kirhdkpj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yonumen.top/Article/details/gt2vnazzbxg.html

Ruby: JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gt2ceaufsdf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2knxgtbjz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ppjwa.cn/Article/details/gt2lnappkfh.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hammf.cn/Article/details/gt2zukgirzc.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.aibaodan.cn/Article/details/gt2scfinaln.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hcafaixw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2uadsloar.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2argnctum.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xrckyiud.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cucudq.cn/Article/details/gt2jdruprst.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj202588.top/Article/details/gt2vjcnboai.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gt2arogmxyw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.guowangkeji.top/Article/details/gt2faoaqbns.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jiagoushi.top/Article/details/gt2cgfdmgio.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nwbrower.top/Article/details/gt2jfxjkcba.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigufen.top/Article/details/gt2sfchpmhl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yvedp.cn/Article/details/gt2edqebgcq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.kuanghao11.cn/Article/details/gt2eusoiviw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2hlfdqxfu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.havefunace.top/Article/details/gt2zkwnatga.html

[K05] 深拷贝对象
来源：http://dali.nanxuanxn.top/Article/details/gt2fyvcddup.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqypmqes.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xylfe.cn/Article/details/gt2upmhhuee.html

JS:   structuredClone(obj)
来源：http://dali.mhx1999.top/Article/details/gt2qeucwoex.html

TS:   structuredClone(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2dcmvxjwp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yueranfly.top/Article/details/gt2kkzmslqg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sufxvd.cn/Article/details/gt2qykisenk.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jlsjyb.cn/Article/details/gt2ziblkvdu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gzhubu.top/Article/details/gt2bafnvrys.html

[K06] 解析 URL 查询串
来源：http://dali.jlsjyb.cn/Article/details/gt2hejabtpp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hnxiangtu.top/Article/details/gt2oeglnkid.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ehwqpu.com/Article/details/gt2nwdqdagp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenlongwang.top/Article/details/gt2tdbydgll.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.snrcjt.cn/Article/details/gt2ivggqbxe.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.wangshuangyany.cn/Article/details/gt2crnoyukf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ivvv.top/Article/details/gt2xbagifvi.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gt2xqmtzofw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jqgufenzy.top/Article/details/gt2wvutkjke.html

[K07] 进制转换
来源：http://dali.yuxming.cn/Article/details/gt2omecunff.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gt2qwokfaam.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yuanzhike.top/Article/details/gt2xhmucfgz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gt2mujfrhed.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gt2xrmwikli.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gt2vobwvifa.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.tian-w.cn/Article/details/gt2jwfwxeav.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.tian-w.cn/Article/details/gt2ldvfnyyu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gt2mwtghzts.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.pycfn.com/Article/details/gt2vtxsbdhv.html

Py:   pickle.dumps(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2lhqghcmb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cdnleiting.top/Article/details/gt2gbbrhcoa.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.quarkkingdee.top/Article/details/gt2entogjie.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.iojbl.cn/Article/details/gt2sytvlojr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.haohaochexian.top/Article/details/gt2iwbosfdq.html

Go:   encoding/gob
来源：http://dali.nanxuanxn.top/Article/details/gt2bqgxeddl.html

Ruby: Marshal.dump(obj)
来源：http://dali.cashguo.top/Article/details/gt2bqzwfdbt.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sweek.top/Article/details/gt2vcsqoucv.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2upmggdyv.html

L. 网络请求
来源：http://dali.wangshuangyany.cn/Article/details/gt2ilqxtqps.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2finyrdom.html

[L01] 发送 GET 请求
来源：http://dali.jinqigufen.top/Article/details/gt2pjxzoygd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.meibo888.top/Article/details/gt2jrblvpru.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ppjwa.cn/Article/details/gt2xkncofpg.html

JS:   await fetch(url)
来源：http://dali.pycfn.com/Article/details/gt2lnqyhscm.html

TS:   await fetch(url)
来源：http://dali.xziqi.cn/Article/details/gt2kgzoupew.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhiwuduotai.top/Article/details/gt2oflwanwc.html

Go:   resp, err := http.Get(url)
来源：http://dali.andypj.xyz/Article/details/gt2fzqnupcv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhiwuduotai.top/Article/details/gt2ppuzphns.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jyoumei.cn/Article/details/gt2jorbiawq.html

[L02] 发送 POST JSON
来源：http://dali.shzxlz.cn/Article/details/gt2legkmsaa.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.nwbrower.top/Article/details/gt2hukkvptj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hywenlv.cn/Article/details/gt2zmhwoqzz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhixingplan.top/Article/details/gt2ddexaung.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hywenlv.cn/Article/details/gt2xgkufvvy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenlongwang.top/Article/details/gt2qaqkdkzr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iklyrgpp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.daxiang520.top/Article/details/gt2xcknvnlt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.9152youxi.cn/Article/details/gt2knqadalf.html

[L03] 设置自定义请求头
来源：http://dali.yangfankeji.com/Article/details/gt2zkxtpmix.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.guannengcc.top/Article/details/gt2gtazuotj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.tianlin.xyz/Article/details/gt2xgdqutsn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gaohongyu789.top/Article/details/gt2jcetdydb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuxming.cn/Article/details/gt2efuzizrx.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ybcxt.top/Article/details/gt2ddnebjff.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yj20258.top/Article/details/gt2qeawtltn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenzaomai.com/Article/details/gt2hqfvcbzj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ybcxt.top/Article/details/gt2vtgevhin.html

[L04] 设置超时
来源：http://dali.yonumen.top/Article/details/gt2gxwmrtyk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.aizwys.cn/Article/details/gt2twrinynu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.aibaodan.cn/Article/details/gt2kftgedwq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.redwolf501.top/Article/details/gt2hquumwen.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aizwys.cn/Article/details/gt2esxsysqw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zycfv.cn/Article/details/gt2rdsmxboo.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.andypj.xyz/Article/details/gt2qabxsael.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nanxuanxn.top/Article/details/gt2ptyigwlf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinqigfzy.top/Article/details/gt2avalhxzs.html

[L05] 上传文件（multipart）
来源：http://dali.dianchejie.cn/Article/details/gt2gvohtmcm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shangyingyoupin.top/Article/details/gt2rqhhknlk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yvedp.cn/Article/details/gt2kovjazaa.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhiwuduotai.top/Article/details/gt2jfllueih.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gogol.net.cn/Article/details/gt2ygvkrbxc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jlsjyb.cn/Article/details/gt2iylcoxox.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.tianlin.xyz/Article/details/gt2dkoamcak.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.guowangkeji.top/Article/details/gt2gcijapfd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yangfankeji.com/Article/details/gt2qeezbjvx.html

[L06] 解析响应为 JSON
来源：http://dali.fzhhl.top/Article/details/gt2yxhjldaz.html

Py:   resp.json()
来源：http://dali.0kj1m.cn/Article/details/gt2fdeabonk.html

PHP:  json_decode($body, true);
来源：http://dali.jyoumei.cn/Article/details/gt2fmbuzski.html

JS:   await resp.json()
来源：http://dali.c1oappe.top/Article/details/gt2qeaveqmm.html

TS:   await resp.json()
来源：http://dali.yj20258.top/Article/details/gt2vxvrdgat.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2luqtvwry.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dwxhippy.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cheryme.top/Article/details/gt2fsdflsbr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cdnleiting.top/Article/details/gt2pujzelwd.html

[L07] 处理 HTTP 状态码
来源：http://dali.yonumen.top/Article/details/gt2firtvtjx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shuidangran.top/Article/details/gt2jhxcqufm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hammf.cn/Article/details/gt2iwrppexl.html

JS:   resp.ok;  resp.status
来源：http://dali.cqqwz.cn/Article/details/gt2kzybhcfd.html

TS:   resp.ok;  resp.status
来源：http://dali.zhiwuduotai.top/Article/details/gt2qhwtjvkv.html

Java: resp.statusCode()
来源：http://dali.yj202588.top/Article/details/gt2wczbgozg.html

Go:   resp.StatusCode
来源：http://dali.yuanzhike.top/Article/details/gt2yfoftpqx.html

Ruby: resp.code.to_i
来源：http://dali.yj20258.top/Article/details/gt2famcdkvp.html

C#:   (int)resp.StatusCode
来源：http://dali.shangyingyoupin.top/Article/details/gt2uansczep.html

[L08] 并发请求多个地址
来源：http://dali.snrcjt.cn/Article/details/gt2pogpcygt.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cdnleiting.top/Article/details/gt2xwyqmxdy.html

PHP:  curl_multi_init() 系列
来源：http://dali.dashuyun.cn/Article/details/gt2ksrosvzw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jyoumei.cn/Article/details/gt2fjxljkeo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sufxvd.cn/Article/details/gt2aqeylcyv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.daxiang520.top/Article/details/gt2tttuhxoc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhengqikj.top/Article/details/gt2sszxybaq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hammf.cn/Article/details/gt2jmexlwha.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xylfe.cn/Article/details/gt2pskakokq.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ezyqjfod.html

M. 命令行 / 进程 / 环境
来源：http://dali.cqqwz.cn/Article/details/gt2pczuwljl.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2vahkdmfu.html

[M01] 读取命令行参数
来源：http://dali.gzhubu.top/Article/details/gt2angkhgpp.html

Py:   sys.argv[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wabimegr.html

PHP:  $argv;  $argc;
来源：http://dali.ydzc1.top/Article/details/gt2xpqwkcfz.html

JS:   process.argv.slice(2)
来源：http://dali.yj20258888.top/Article/details/gt2bpgwpgwq.html

TS:   process.argv.slice(2)
来源：http://dali.zhengqikj.top/Article/details/gt2liaayfjb.html

Java: args 数组（main 方法参数）
来源：http://dali.yangfankeji.com/Article/details/gt2lkkimfpw.html

Go:   os.Args[1:]
来源：http://dali.tianlin.xyz/Article/details/gt2wrnukocr.html

Ruby: ARGV
来源：http://dali.316326.xyz/Article/details/gt2hotxxcyc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xziqi.cn/Article/details/gt2vmnhwizu.html

[M02] 读取环境变量
来源：http://dali.zhongyouzk.top/Article/details/gt2llohezmy.html

Py:   os.environ.get("HOME")
来源：http://dali.shzxlz.cn/Article/details/gt2otytfpfl.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.9152youxi.cn/Article/details/gt2tfgjxyzq.html

JS:   process.env.HOME
来源：http://dali.feifeiyinyue.top/Article/details/gt2poxnrucs.html

TS:   process.env.HOME
来源：http://dali.sweek.top/Article/details/gt2mvqwleeb.html

Java: System.getenv("HOME")
来源：http://dali.hywenlv.cn/Article/details/gt2ksmydwis.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhixingplan.top/Article/details/gt2orripdvw.html

Ruby: ENV["HOME"]
来源：http://dali.0kj1m.cn/Article/details/gt2jnfllwwu.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yuanzhike.top/Article/details/gt2jttiqryd.html

[M03] 执行外部命令
来源：http://dali.hnxiangtu.top/Article/details/gt2mwuthuad.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.fzhhl.top/Article/details/gt2twlwdevo.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xziqi.cn/Article/details/gt2tdbjswlu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rrezmint.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuetiantiany.cn/Article/details/gt2hbsbsctl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.haohaochexian.top/Article/details/gt2dnrtivxy.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ovtqyddn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zdqjudy.top/Article/details/gt2japcvsum.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xylfe.cn/Article/details/gt2bmhreorn.html

[M04] 获取当前工作目录
来源：http://dali.dashuyun.cn/Article/details/gt2irdrkpiq.html

Py:   os.getcwd()
来源：http://dali.pengpengdd.cyou/Article/details/gt2aefytzta.html

PHP:  getcwd();
来源：http://dali.pengpengdd.cyou/Article/details/gt2zlgvzemn.html

JS:   process.cwd()
来源：http://dali.yonumen.top/Article/details/gt2ybcbxang.html

TS:   process.cwd()
来源：http://dali.hysaishi.cn/Article/details/gt2yiqrsaml.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.316326.xyz/Article/details/gt2wpjfecgp.html

Go:   os.Getwd()
来源：http://dali.316326.xyz/Article/details/gt2mzlspzgd.html

Ruby: Dir.pwd
来源：http://dali.cucudq.cn/Article/details/gt2ndahfudc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.pycfn.com/Article/details/gt2tmzyfpvc.html

[M05] 设置退出码
来源：http://dali.jqgfzy.top/Article/details/gt2izrnejks.html

Py:   sys.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gt2tokwtkir.html

PHP:  exit(1);
来源：http://dali.zhengqikj.top/Article/details/gt2xxyznafn.html

JS:   process.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2simsqwtd.html

TS:   process.exit(1)
来源：http://dali.gzhubu.top/Article/details/gt2qfwjnevu.html

Java: System.exit(1)
来源：http://dali.mhx1999.top/Article/details/gt2pnxhtffw.html

Go:   os.Exit(1)
来源：http://dali.gogol.net.cn/Article/details/gt2acdcgzux.html

Ruby: exit 1
来源：http://dali.aibaodan.cn/Article/details/gt2yjoiaaeq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hammf.cn/Article/details/gt2eclgdgct.html

[M06] 向标准错误输出
来源：http://dali.pengpengdd.cyou/Article/details/gt2oaozmlhz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ivvv.top/Article/details/gt2qtmeivrl.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nanxinkj.top/Article/details/gt2exobgczu.html

JS:   console.error("err")
来源：http://dali.hnxiangtu.top/Article/details/gt2wyhjtnxk.html

TS:   console.error("err")
来源：http://dali.nanxinkj.top/Article/details/gt2pnaebonk.html

Java: System.err.println("err")
来源：http://dali.xylfe.cn/Article/details/gt2qmsvnpme.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.mhx1999.top/Article/details/gt2ytumhdiy.html

Ruby: warn "err"
来源：http://dali.jqgufenzy.top/Article/details/gt2lgeqcajq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.svipenyu.cn/Article/details/gt2bbhsbpht.html

[M07] 判断是否为主入口
来源：http://dali.zhiwuduotai.top/Article/details/gt2xywmapxu.html


<!-- 参考信息 -->