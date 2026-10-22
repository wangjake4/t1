代发 wailian999

J. 日期与时间
来源：http://dali.xziqi.cn/Article/details/gt2akpxymvi.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2jycexrxu.html

[J01] 获取当前时间
来源：http://dali.pycfn.com/Article/details/gt2wunrzidw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jqgfzy.top/Article/details/gt2mqzkjvoa.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hywenlv.cn/Article/details/gt2xshwpuwz.html

JS:   new Date();  Date.now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wbvutkmb.html

TS:   new Date();  Date.now()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2senboyia.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.tianlin.xyz/Article/details/gt2sbyzekll.html

Go:   time.Now()
来源：http://dali.wangshuangyany.cn/Article/details/gt2uiokscka.html

Ruby: Time.now
来源：http://dali.ydzc1.top/Article/details/gt2gisjzzud.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shzxlz.cn/Article/details/gt2npsicvxh.html

[J02] 格式化输出
来源：http://dali.chenzaomai.com/Article/details/gt2yifidtgy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jiagoushi.top/Article/details/gt2hlnelbwa.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.chenzaomai.com/Article/details/gt2udjwqqcj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tanke756.top/Article/details/gt2lgsdnxdz.html

TS:   d.toISOString()
来源：http://dali.yj20258888.top/Article/details/gt2mwbjtsca.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.meibo888.top/Article/details/gt2cxyejgrk.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.wangshuangyany.cn/Article/details/gt2pevyenbp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ivvv.top/Article/details/gt2uevdfozt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daxiang520.top/Article/details/gt2wtgtcmep.html

[J03] 字符串解析为日期
来源：http://dali.jiagoushi.top/Article/details/gt2ygkrcbvp.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xuetiantiany.cn/Article/details/gt2gxhzmmix.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zdqjudy.top/Article/details/gt2pepxotzq.html

JS:   new Date("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gt2qlwewyxa.html

TS:   new Date("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gt2gjsolenx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gt2ostrvqpv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gt2tubhrknd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gt2jyqnykcc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.birdmap.top/Article/details/gt2puwtnqdc.html

[J04] 时间戳与日期互转
来源：http://dali.meibo888.top/Article/details/gt2ondjxwaw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ctqsgzjd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.smart0.xyz/Article/details/gt2uavjmzhf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhongyouzk.top/Article/details/gt2atnwmdzs.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.fzhhl.top/Article/details/gt2yuxpzhek.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhengqikj.top/Article/details/gt2dhbgtpax.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nwbrower.top/Article/details/gt2nnckubvz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.gaohongyu789.top/Article/details/gt2fafzhadv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cashguo.top/Article/details/gt2nbftbhxd.html

[J05] 时间加减（加 7 天）
来源：http://dali.ydzc1.top/Article/details/gt2xkcwbtor.html

Py:   now + timedelta(days=7)
来源：http://dali.dianchejie.cn/Article/details/gt2awgxyxfd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shuidangran.top/Article/details/gt2urgdlikr.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yonumen.top/Article/details/gt2ejitovrl.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gogol.net.cn/Article/details/gt2lqwgyocs.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.svipenyu.cn/Article/details/gt2xbumeosp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gogol.net.cn/Article/details/gt2znpzkbmy.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jyoumei.cn/Article/details/gt2sopvkljh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zpvmzyhy.html

[J06] 计算两时间之差
来源：http://dali.pycfn.com/Article/details/gt2henizqxn.html

Py:   (end - start).total_seconds()
来源：http://dali.andypj.xyz/Article/details/gt2nyibyjrn.html

PHP:  $end->diff($start)->days;
来源：http://dali.hywenlv.cn/Article/details/gt2ssgwtntw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.nanxuanxn.top/Article/details/gt2ezptyifc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sxryk.cn/Article/details/gt2sjlrmjki.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xuetiantiany.cn/Article/details/gt2zilgzfzo.html

Go:   end.Sub(start).Hours()
来源：http://dali.shangyingyoupin.top/Article/details/gt2cxnretkj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ppjwa.cn/Article/details/gt2kiktxrcx.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj20258888.top/Article/details/gt2nhpeyfyo.html

[J07] 比较两个日期
来源：http://dali.chenjidiqi.icu/Article/details/gt2etieywpw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gt2qoculelr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shzxlz.cn/Article/details/gt2bxbqnkpm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenzaomai.com/Article/details/gt2kcardned.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgufenzy.top/Article/details/gt2yzouciem.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.vqdsnc.cn/Article/details/gt2ugbvtlxb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gaohongyu789.top/Article/details/gt2udieibkj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gt2ozsgytya.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gt2jzvrrbrp.html

[J08] 提取年月日与星期
来源：http://dali.yj20258888.top/Article/details/gt2athidqwe.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cucudq.cn/Article/details/gt2dokqqnkn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hywenlv.cn/Article/details/gt2gyqfkjyi.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ybcxt.top/Article/details/gt2jpdchazl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.birdmap.top/Article/details/gt2sxuwxeze.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sysykeji.top/Article/details/gt2lamscnqo.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.aibaodan.cn/Article/details/gt2berlhzpx.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gaohongyu789.top/Article/details/gt2ruthedwk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.tianlin.xyz/Article/details/gt2tncifkqu.html

[J09] 时区处理
来源：http://dali.xziqi.cn/Article/details/gt2jbspqxbz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.daria6918.cn/Article/details/gt2tnlufnvk.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cqqwz.cn/Article/details/gt2mutqgkbw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuetiantiany.cn/Article/details/gt2qbwqgnyt.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aibaodan.cn/Article/details/gt2hbmkotyt.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yueranfly.top/Article/details/gt2gilmiclj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ydzc1.top/Article/details/gt2xfxrjeah.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cashguo.top/Article/details/gt2xjglxqlu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.redwolf501.top/Article/details/gt2wmkrvaay.html

[J10] 取今天 / 本月第一天
来源：http://dali.tianlin.xyz/Article/details/gt2muujkbdh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xziqi.cn/Article/details/gt2jinyywdd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.mhx1999.top/Article/details/gt2bfuqvjvq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jqgufenzy.top/Article/details/gt2nddvnklm.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ydzc1.top/Article/details/gt2dyqyivdw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2pmkcucnf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xziqi.cn/Article/details/gt2mokdmybx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yanxiufei.cn/Article/details/gt2isjbsarc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yuanzhike.top/Article/details/gt2mqgwtgua.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2gozwzzel.html

K. JSON 与序列化
来源：http://dali.cdnleiting.top/Article/details/gt2cfptyuxy.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2kgmmsrjy.html

[K01] 对象转 JSON 字符串
来源：http://dali.fzhhl.top/Article/details/gt2allmdudr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.9152youxi.cn/Article/details/gt2renvoayo.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xinyue.icu/Article/details/gt2beujpslf.html

JS:   JSON.stringify(obj)
来源：http://dali.andypj.xyz/Article/details/gt2zeswwkel.html

TS:   JSON.stringify(obj)
来源：http://dali.xylfe.cn/Article/details/gt2zprtsrsu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.kuanghao11.cn/Article/details/gt2ipawcwsq.html

Go:   json.Marshal(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2kmyrhrbb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ivvv.top/Article/details/gt2bivjsxlf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yvedp.cn/Article/details/gt2ysadxumf.html

[K02] JSON 字符串转对象
来源：http://dali.hysaishi.cn/Article/details/gt2etsdgcgp.html

Py:   json.loads(s)
来源：http://dali.yangfankeji.com/Article/details/gt2xyokpopt.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.bjfxy.top/Article/details/gt2jzhteike.html

JS:   JSON.parse(s)
来源：http://dali.yj20258888.top/Article/details/gt2otabgwnf.html

TS:   JSON.parse(s)
来源：http://dali.jianghu66.top/Article/details/gt2vtwxyush.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cdnleiting.top/Article/details/gt2wbqaqoag.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj202588.top/Article/details/gt2ljvbowxu.html

Ruby: JSON.parse(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2gkwcxevb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.aizwys.cn/Article/details/gt2pbbhreqx.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.bjfxy.top/Article/details/gt2kjvancry.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sufxvd.cn/Article/details/gt2omksklkf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ehwqpu.com/Article/details/gt2pcuzrrvx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sxryk.cn/Article/details/gt2zgzqyehp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.fengsongda.top/Article/details/gt2wiqwxyth.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2yyiqdvun.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.smart0.xyz/Article/details/gt2nhpuepxb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xylfe.cn/Article/details/gt2bilpbimz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj20258888.top/Article/details/gt2dstodsyq.html

[K04] 读取 JSON 文件
来源：http://dali.hywenlv.cn/Article/details/gt2djckgmrj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hywenlv.cn/Article/details/gt2qglkzpwj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gzhubu.top/Article/details/gt2umxdwrzc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenlongwang.top/Article/details/gt2oeysxnux.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenzaomai.com/Article/details/gt2ekirqafj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yj20258888.top/Article/details/gt2xmthukij.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hnqzz.top/Article/details/gt2yksfgnas.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.tian-w.cn/Article/details/gt2kdfzftbd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.quarkkingdee.top/Article/details/gt2figmated.html

[K05] 深拷贝对象
来源：http://dali.yongpay.top/Article/details/gt2jxecefvx.html

Py:   copy.deepcopy(obj)
来源：http://dali.andypj.xyz/Article/details/gt2rrenzatq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ezaxgtix.html

JS:   structuredClone(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2bcbbhzml.html

TS:   structuredClone(obj)
来源：http://dali.yongpay.top/Article/details/gt2fgdwvzzp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xylfe.cn/Article/details/gt2bdpkpsph.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hysaishi.cn/Article/details/gt2zdemamiz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.chenlongwang.top/Article/details/gt2ezsdrofb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhengqikj.top/Article/details/gt2lfxkmbtx.html

[K06] 解析 URL 查询串
来源：http://dali.yonumen.top/Article/details/gt2ctsqyiiw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.nwbrower.top/Article/details/gt2ptntdluo.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhengqikj.top/Article/details/gt2wlhuponu.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenlongwang.top/Article/details/gt2kpzobinz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.feifeiyinyue.top/Article/details/gt2rxtvrrxr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.mhx1999.top/Article/details/gt2tjmgnfpa.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hnxiangtu.top/Article/details/gt2bwxkaljp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gt2npzdpvvw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gt2mlxydstw.html

[K07] 进制转换
来源：http://dali.wangdashe.top/Article/details/gt2vrauuhku.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ankvmeyk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.chenlongwang.top/Article/details/gt2kbdfolfr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gt2cmympccj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sweek.top/Article/details/gt2scwtudop.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gt2llvfttuk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xylfe.cn/Article/details/gt2vclwtvjc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xylfe.cn/Article/details/gt2fqfvmfdv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gt2siktjhyl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.tian-w.cn/Article/details/gt2zndltqcn.html

Py:   pickle.dumps(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2wummznaq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jlsjyb.cn/Article/details/gt2hhlozucz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhiwuduotai.top/Article/details/gt2kwqpnrkn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yonumen.top/Article/details/gt2pfardzqq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2whuxfbkf.html

Go:   encoding/gob
来源：http://dali.nanxinkj.top/Article/details/gt2qvijytgl.html

Ruby: Marshal.dump(obj)
来源：http://dali.nwbrower.top/Article/details/gt2naaziodb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.316326.xyz/Article/details/gt2szxwtlfz.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2znyblcnv.html

L. 网络请求
来源：http://dali.chenlongwang.top/Article/details/gt2ivvhkjgz.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2uufbkgry.html

[L01] 发送 GET 请求
来源：http://dali.cqqwz.cn/Article/details/gt2atyylmhi.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hnxiangtu.top/Article/details/gt2bqznnvbh.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.fzhhl.top/Article/details/gt2lpehbvxl.html

JS:   await fetch(url)
来源：http://dali.zhoulong.xyz/Article/details/gt2nqvxapym.html

TS:   await fetch(url)
来源：http://dali.iojbl.cn/Article/details/gt2nkdjulbk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.tanke756.top/Article/details/gt2pdjobrsj.html

Go:   resp, err := http.Get(url)
来源：http://dali.yj202588.top/Article/details/gt2zrvrlnlo.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.chenlongwang.top/Article/details/gt2jfqdvmvm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.havefunace.top/Article/details/gt2urjglegm.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mrnwawlr.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.feifeiyinyue.top/Article/details/gt2hvtzpura.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.birdmap.top/Article/details/gt2rajpucsc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.feifeiyinyue.top/Article/details/gt2dnkfhoxt.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dianchejie.cn/Article/details/gt2ltgagdti.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.tian-w.cn/Article/details/gt2etjkaaod.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shzxlz.cn/Article/details/gt2wcbdjzuj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.0kj1m.cn/Article/details/gt2veypjfts.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dtcrhiju.html

[L03] 设置自定义请求头
来源：http://dali.zhongyouzk.top/Article/details/gt2cenohcvu.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.nanxuanxn.top/Article/details/gt2ahiuoucc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.redwolf501.top/Article/details/gt2lzdjuxcb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shzxlz.cn/Article/details/gt2tffsvhzo.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tian-w.cn/Article/details/gt2chvtdceb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ehwqpu.com/Article/details/gt2pbhhwjqn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shangyingyoupin.top/Article/details/gt2uhlxqffk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj20258.top/Article/details/gt2yuzmzjbf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yueranfly.top/Article/details/gt2dckttphd.html

[L04] 设置超时
来源：http://dali.kuanghao11.cn/Article/details/gt2lzbhiomk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tian-w.cn/Article/details/gt2sfimfxxt.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sufxvd.cn/Article/details/gt2gtgaqnmo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shangyingyoupin.top/Article/details/gt2vofbtjil.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.andypj.xyz/Article/details/gt2uqhharwk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhoulong.xyz/Article/details/gt2ryjnxrgk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xylfe.cn/Article/details/gt2vwwrhmtr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tszpiftp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.nwbrower.top/Article/details/gt2vboiegof.html

[L05] 上传文件（multipart）
来源：http://dali.c1oappe.top/Article/details/gt2otreepkn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.tanke756.top/Article/details/gt2sqmubwsy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ehwqpu.com/Article/details/gt2srpgilkb.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenlongwang.top/Article/details/gt2btrswmhr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sweek.top/Article/details/gt2qhrmcwqv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.redwolf501.top/Article/details/gt2bdrckjsd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.316326.xyz/Article/details/gt2xvkyrpfd.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.9152youxi.cn/Article/details/gt2mkqvaaco.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2bcwekopt.html

[L06] 解析响应为 JSON
来源：http://dali.pycfn.com/Article/details/gt2bbjyxrrb.html

Py:   resp.json()
来源：http://dali.aibaodan.cn/Article/details/gt2lslxcopq.html

PHP:  json_decode($body, true);
来源：http://dali.zdqjudy.top/Article/details/gt2neaauppj.html

JS:   await resp.json()
来源：http://dali.hongshengwenyu.top/Article/details/gt2slcodvvs.html

TS:   await resp.json()
来源：http://dali.yj20258.top/Article/details/gt2evgxpkag.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yongpay.top/Article/details/gt2vxiuhbis.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.0kj1m.cn/Article/details/gt2kerlxely.html

Ruby: JSON.parse(resp.body)
来源：http://dali.aizwys.cn/Article/details/gt2tebumlrv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nanxuanxn.top/Article/details/gt2mvpghrxw.html

[L07] 处理 HTTP 状态码
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mbvgypif.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cdnleiting.top/Article/details/gt2vovyjalv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.fengsongda.top/Article/details/gt2wiocopcl.html

JS:   resp.ok;  resp.status
来源：http://dali.hysaishi.cn/Article/details/gt2myjomhuf.html

TS:   resp.ok;  resp.status
来源：http://dali.yangfankeji.com/Article/details/gt2uaktogou.html

Java: resp.statusCode()
来源：http://dali.dashuyun.cn/Article/details/gt2qllrychf.html

Go:   resp.StatusCode
来源：http://dali.cqqwz.cn/Article/details/gt2ytwgcxhx.html

Ruby: resp.code.to_i
来源：http://dali.haohaochexian.top/Article/details/gt2udoxyqwr.html

C#:   (int)resp.StatusCode
来源：http://dali.guannengcc.top/Article/details/gt2yjtahusj.html

[L08] 并发请求多个地址
来源：http://dali.gaohongyu789.top/Article/details/gt2oizcyavp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cqqwz.cn/Article/details/gt2fezujnxa.html

PHP:  curl_multi_init() 系列
来源：http://dali.shuidangran.top/Article/details/gt2qpmtiypf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shzxlz.cn/Article/details/gt2lyflbqvy.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangdashe.top/Article/details/gt2gqohuuuw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cashguo.top/Article/details/gt2bzdkihzu.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinqigfzy.top/Article/details/gt2urjrcrmu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gotoacloud.top/Article/details/gt2mivsdldn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.daxiang520.top/Article/details/gt2lrvpkikp.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2yrebbvdt.html

M. 命令行 / 进程 / 环境
来源：http://dali.yonumen.top/Article/details/gt2ijolwgjn.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2olvyjgyk.html

[M01] 读取命令行参数
来源：http://dali.mhx1999.top/Article/details/gt2kiqqbwfi.html

Py:   sys.argv[1:]
来源：http://dali.ybcxt.top/Article/details/gt2mszbrxhz.html

PHP:  $argv;  $argc;
来源：http://dali.cheryme.top/Article/details/gt2mlxbtyrk.html

JS:   process.argv.slice(2)
来源：http://dali.cheryme.top/Article/details/gt2scetjthq.html

TS:   process.argv.slice(2)
来源：http://dali.zhixingplan.top/Article/details/gt2ujifcmyb.html

Java: args 数组（main 方法参数）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iuibopxo.html

Go:   os.Args[1:]
来源：http://dali.cheryme.top/Article/details/gt2barallyy.html

Ruby: ARGV
来源：http://dali.jiagoushi.top/Article/details/gt2sinlizuu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.snrcjt.cn/Article/details/gt2zhvktsti.html

[M02] 读取环境变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ljldrnek.html

Py:   os.environ.get("HOME")
来源：http://dali.jinqigufen.top/Article/details/gt2plvgmxwv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hywenlv.cn/Article/details/gt2jcrihxtg.html

JS:   process.env.HOME
来源：http://dali.ydzc1.top/Article/details/gt2xbajdylr.html

TS:   process.env.HOME
来源：http://dali.yueranfly.top/Article/details/gt2ctyvgksn.html

Java: System.getenv("HOME")
来源：http://dali.yuanzhike.top/Article/details/gt2khoupszv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.tianlin.xyz/Article/details/gt2xajuhhas.html

Ruby: ENV["HOME"]
来源：http://dali.xinyue.icu/Article/details/gt2mwrznnpn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.andypj.xyz/Article/details/gt2xahomzgm.html

[M03] 执行外部命令
来源：http://dali.meibo888.top/Article/details/gt2mesqkfns.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ydzc1.top/Article/details/gt2dxvntygm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jyoumei.cn/Article/details/gt2zbdjezvz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shuidangran.top/Article/details/gt2hgfzfqff.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yanxiufei.cn/Article/details/gt2ucypvskw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.c1oappe.top/Article/details/gt2ebscygev.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.birdmap.top/Article/details/gt2ewryzxzl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.c1oappe.top/Article/details/gt2junvymrv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jyoumei.cn/Article/details/gt2wtxrkqjb.html

[M04] 获取当前工作目录
来源：http://dali.bjfxy.top/Article/details/gt2tmntcrsz.html

Py:   os.getcwd()
来源：http://dali.yvedp.cn/Article/details/gt2qshdujoe.html

PHP:  getcwd();
来源：http://dali.shzxlz.cn/Article/details/gt2rybyuphs.html

JS:   process.cwd()
来源：http://dali.dashuyun.cn/Article/details/gt2yctkhpzr.html

TS:   process.cwd()
来源：http://dali.zdqjudy.top/Article/details/gt2jzrhbldi.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.9152youxi.cn/Article/details/gt2tgisoozn.html

Go:   os.Getwd()
来源：http://dali.ehwqpu.com/Article/details/gt2oibhveoj.html

Ruby: Dir.pwd
来源：http://dali.haohaochexian.top/Article/details/gt2xejxbjgh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xylfe.cn/Article/details/gt2brhkylod.html

[M05] 设置退出码
来源：http://dali.jianghu66.top/Article/details/gt2wpazxubc.html

Py:   sys.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2bfaxcqqz.html

PHP:  exit(1);
来源：http://dali.yueranfly.top/Article/details/gt2jpquicdn.html

JS:   process.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gt2xpudouji.html

TS:   process.exit(1)
来源：http://dali.jianghu66.top/Article/details/gt2aegpxotu.html

Java: System.exit(1)
来源：http://dali.fengsongda.top/Article/details/gt2smaxfclx.html

Go:   os.Exit(1)
来源：http://dali.yueranfly.top/Article/details/gt2foagbpfe.html

Ruby: exit 1
来源：http://dali.cdnleiting.top/Article/details/gt2ckkrcxug.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.iojbl.cn/Article/details/gt2wwryyhnm.html

[M06] 向标准错误输出
来源：http://dali.gotoacloud.top/Article/details/gt2gofmuuia.html

Py:   print("err", file=sys.stderr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2cvcuuhtv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cdnleiting.top/Article/details/gt2argjwpom.html

JS:   console.error("err")
来源：http://dali.xuanzx.com/Article/details/gt2xecngdxb.html

TS:   console.error("err")
来源：http://dali.nanxuanxn.top/Article/details/gt2keixocir.html

Java: System.err.println("err")
来源：http://dali.shzxlz.cn/Article/details/gt2drqruchm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ehwqpu.com/Article/details/gt2cowltmsb.html

Ruby: warn "err"
来源：http://dali.zhixingplan.top/Article/details/gt2ijhvwmjk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tianlin.xyz/Article/details/gt2mpurczzv.html

[M07] 判断是否为主入口
来源：http://dali.andypj.xyz/Article/details/gt2fupvuxky.html


<!-- 参考信息 -->