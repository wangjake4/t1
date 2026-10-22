代发 wailian999

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2blocgdkq.html

JS:   new Date();  Date.now()
来源：http://dali.0kj1m.cn/Article/details/gt2yqhsxvwb.html

TS:   new Date();  Date.now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gdkhsclp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.meibo888.top/Article/details/gt2yfkvdhpv.html

Go:   time.Now()
来源：http://dali.jiagoushi.top/Article/details/gt2wwcploit.html

Ruby: Time.now
来源：http://dali.yj20258.top/Article/details/gt2rqycxqvf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hysaishi.cn/Article/details/gt2syiijtqn.html

[J02] 格式化输出
来源：http://dali.yanxiufei.cn/Article/details/gt2nyhsjynd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.mhx1999.top/Article/details/gt2smoekfmj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.andypj.xyz/Article/details/gt2efgkxhtp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.fengsongda.top/Article/details/gt2pwrglrjs.html

TS:   d.toISOString()
来源：http://dali.xziqi.cn/Article/details/gt2msmhawmc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhixingplan.top/Article/details/gt2zuvegcvk.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nwbrower.top/Article/details/gt2suhomrcs.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.birdmap.top/Article/details/gt2qdammjvd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sysykeji.top/Article/details/gt2acqaqkbm.html

[J03] 字符串解析为日期
来源：http://dali.jianghu66.top/Article/details/gt2tlyiiskk.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zdqjudy.top/Article/details/gt2tesqbxoo.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gaohongyu789.top/Article/details/gt2rkqlggaj.html

JS:   new Date("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gt2sujaybtg.html

TS:   new Date("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gt2djtkljhq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gt2grfuqolj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gt2qbsiqyzk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gt2lggudixm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jlsjyb.cn/Article/details/gt2cqhiwchq.html

[J04] 时间戳与日期互转
来源：http://dali.hnqzz.top/Article/details/gt2rxvgkdne.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.0kj1m.cn/Article/details/gt2kthlbcjm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.feifeiyinyue.top/Article/details/gt2bsqnvppv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nanxuanxn.top/Article/details/gt2wwextmrv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ydzc1.top/Article/details/gt2grygkili.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cheryme.top/Article/details/gt2ujruemom.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2uyjumojz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhoulong.xyz/Article/details/gt2rtsrxkul.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yuxming.cn/Article/details/gt2xpkkdcjv.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhijiandao.cn/Article/details/gt2xtbgsgxz.html

Py:   now + timedelta(days=7)
来源：http://dali.yonumen.top/Article/details/gt2vcykirgz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.birdmap.top/Article/details/gt2nnzhwhdc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vbcwrsak.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fpeqksfv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.fzhhl.top/Article/details/gt2gsuilpqe.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhoulong.xyz/Article/details/gt2cituppae.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sysykeji.top/Article/details/gt2cplqmyat.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.birdmap.top/Article/details/gt2ogdukhoq.html

[J06] 计算两时间之差
来源：http://dali.zhoulong.xyz/Article/details/gt2dfztqktk.html

Py:   (end - start).total_seconds()
来源：http://dali.cashguo.top/Article/details/gt2dhbbagne.html

PHP:  $end->diff($start)->days;
来源：http://dali.ivvv.top/Article/details/gt2zejrzppy.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.smart0.xyz/Article/details/gt2yuyktftf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yangfankeji.com/Article/details/gt2pgbzjfqr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zycfv.cn/Article/details/gt2erdmpdgc.html

Go:   end.Sub(start).Hours()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cpesdsfs.html

Ruby: end - start                 # 返回秒数
来源：http://dali.mhx1999.top/Article/details/gt2vkxoljrz.html

C#:   (end - start).TotalSeconds
来源：http://dali.daria6918.cn/Article/details/gt2xtblhfgi.html

[J07] 比较两个日期
来源：http://dali.gaohongyu789.top/Article/details/gt2kwgjkwas.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gt2yvsxqxaf.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.tian-w.cn/Article/details/gt2mvxovjbo.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.meibo888.top/Article/details/gt2yskkietr.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hywenlv.cn/Article/details/gt2xksceovu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ogskcsrg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2uaqxcbsb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hnxiangtu.top/Article/details/gt2radicqlj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gt2zlucbvbs.html

[J08] 提取年月日与星期
来源：http://dali.zhengqikj.top/Article/details/gt2hyfepzxa.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jianghu66.top/Article/details/gt2sszpbxzz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cheryme.top/Article/details/gt2isbxwqcl.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.wangdashe.top/Article/details/gt2stbbohjl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinqigfzy.top/Article/details/gt2kncismla.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.daxiang520.top/Article/details/gt2wremnjwe.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.daria6918.cn/Article/details/gt2nffindmu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cqqwz.cn/Article/details/gt2fdigfobu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cheryme.top/Article/details/gt2zgsnzmxi.html

[J09] 时区处理
来源：http://dali.gotoacloud.top/Article/details/gt2zadgsgrr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yj202588.top/Article/details/gt2qpnuhkse.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ybcxt.top/Article/details/gt2kujeouls.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuanzhike.top/Article/details/gt2amcjlqru.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dashuyun.cn/Article/details/gt2kbhimhzd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ahmdfhrr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shzxlz.cn/Article/details/gt2slhwkkya.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhengqikj.top/Article/details/gt2zlvktfrp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenjidiqi.icu/Article/details/gt2zuwgpvyo.html

[J10] 取今天 / 本月第一天
来源：http://dali.shuidangran.top/Article/details/gt2mmbpwwjj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yangfankeji.com/Article/details/gt2wlacvydr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jqgufenzy.top/Article/details/gt2qytdmdfx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yj20258.top/Article/details/gt2xujkqjpd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhoulong.xyz/Article/details/gt2oghifvxq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2nejqclbf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2edywrhlj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eifuqpzx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ehwqpu.com/Article/details/gt2hrckjuto.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2cyilqxgs.html

K. JSON 与序列化
来源：http://dali.hfpthk.cn/Article/details/gt2yjlfyecf.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2kbimzurz.html

[K01] 对象转 JSON 字符串
来源：http://dali.xylfe.cn/Article/details/gt2rivpmvov.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cheryme.top/Article/details/gt2awtmxujs.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2unljvsob.html

JS:   JSON.stringify(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hjlzafyk.html

TS:   JSON.stringify(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2unadlaaq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhiwuduotai.top/Article/details/gt2hfpxfhrc.html

Go:   json.Marshal(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2mhuxmdti.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hnxiangtu.top/Article/details/gt2zdqbvnms.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pclkcera.html

[K02] JSON 字符串转对象
来源：http://dali.shzxlz.cn/Article/details/gt2rxuriukk.html

Py:   json.loads(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2whcdyzyt.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hongshengwenyu.top/Article/details/gt2jthwolek.html

JS:   JSON.parse(s)
来源：http://dali.dianchejie.cn/Article/details/gt2diuxyyik.html

TS:   JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gt2jtarqmus.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shangyingyoupin.top/Article/details/gt2avacfhuo.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cucudq.cn/Article/details/gt2gbimaage.html

Ruby: JSON.parse(s)
来源：http://dali.yangfankeji.com/Article/details/gt2uprqdfty.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2nxyvfzgo.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zycfv.cn/Article/details/gt2fzytietx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ddkjgrfx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.vqdsnc.cn/Article/details/gt2pgewmxtx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.havefunace.top/Article/details/gt2pveddraf.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.0kj1m.cn/Article/details/gt2yxcyzcws.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.redwolf501.top/Article/details/gt2zhxlzcmg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yj20258888.top/Article/details/gt2ocmgxsdn.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2kdswvgqv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2essanpff.html

[K04] 读取 JSON 文件
来源：http://dali.pycfn.com/Article/details/gt2wjbuxmqz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cashguo.top/Article/details/gt2wipjrfal.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.0kj1m.cn/Article/details/gt2yhjwlmue.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.9152youxi.cn/Article/details/gt2tdgtpjwp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cheryme.top/Article/details/gt2yybswtrg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.snrcjt.cn/Article/details/gt2uxulxuit.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ufrlbxtt.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sweek.top/Article/details/gt2yzetzjyo.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nanxuanxn.top/Article/details/gt2paseokxl.html

[K05] 深拷贝对象
来源：http://dali.yj20258888.top/Article/details/gt2ddojcyyu.html

Py:   copy.deepcopy(obj)
来源：http://dali.hammf.cn/Article/details/gt2ggzwnnjh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hammf.cn/Article/details/gt2ttdqpsah.html

JS:   structuredClone(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jtqkyhgp.html

TS:   structuredClone(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2pxeomgfn.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ivvv.top/Article/details/gt2ohtaogts.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xuetiantiany.cn/Article/details/gt2dumediif.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xuetiantiany.cn/Article/details/gt2hxhsmgbo.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vkxayraq.html

[K06] 解析 URL 查询串
来源：http://dali.shuidangran.top/Article/details/gt2azoxcyro.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgufenzy.top/Article/details/gt2xmsvyoki.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jlsjyb.cn/Article/details/gt2gkrtfcqq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.redwolf501.top/Article/details/gt2pnqkjill.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daxiang520.top/Article/details/gt2qhjxwqxr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hysaishi.cn/Article/details/gt2twashdal.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gt2evkjcxiv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ivvv.top/Article/details/gt2lkhzhzkg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.guannengcc.top/Article/details/gt2ldkxmfwx.html

[K07] 进制转换
来源：http://dali.kuanghao11.cn/Article/details/gt2xqfvqvuv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gt2tacjvykk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.mhx1999.top/Article/details/gt2izgmixov.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gt2mipdbpdc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gt2cushvrbp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gt2nnwpoyan.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zdqjudy.top/Article/details/gt2ivkechpq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tohybqqi.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pkhqktsv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xuetiantiany.cn/Article/details/gt2fndurxbu.html

Py:   pickle.dumps(obj)
来源：http://dali.ybcxt.top/Article/details/gt2bderhekr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kysshvor.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.316326.xyz/Article/details/gt2znekhpvc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.haohaochexian.top/Article/details/gt2ehlinwgu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gzhubu.top/Article/details/gt2wttdkucm.html

Go:   encoding/gob
来源：http://dali.jqgufenzy.top/Article/details/gt2wkpqadfk.html

Ruby: Marshal.dump(obj)
来源：http://dali.fzhhl.top/Article/details/gt2harbslqb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cqqwz.cn/Article/details/gt2dclexqyw.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2tmzthmfg.html

L. 网络请求
来源：http://dali.ppjwa.cn/Article/details/gt2ypvredbw.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2zrfxzblq.html

[L01] 发送 GET 请求
来源：http://dali.shzxlz.cn/Article/details/gt2xfjganqn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gogol.net.cn/Article/details/gt2awzpqapz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.kuanghao11.cn/Article/details/gt2hyoflfyo.html

JS:   await fetch(url)
来源：http://dali.yangfankeji.com/Article/details/gt2leutdiqf.html

TS:   await fetch(url)
来源：http://dali.birdmap.top/Article/details/gt2qfurqfez.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hammf.cn/Article/details/gt2lvljcdsk.html

Go:   resp, err := http.Get(url)
来源：http://dali.yuanzhike.top/Article/details/gt2airakcjg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gaohongyu789.top/Article/details/gt2zibinhge.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.birdmap.top/Article/details/gt2objlxbmw.html

[L02] 发送 POST JSON
来源：http://dali.jqgufenzy.top/Article/details/gt2sggatbnd.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jqgfzy.top/Article/details/gt2yfkgffoq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hnxiangtu.top/Article/details/gt2qjmszmaz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zycfv.cn/Article/details/gt2vmdzqsyr.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xziqi.cn/Article/details/gt2elvlhumy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.redwolf501.top/Article/details/gt2founsnlr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hammf.cn/Article/details/gt2zsgzbnou.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.tian-w.cn/Article/details/gt2ylviwbpi.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sweek.top/Article/details/gt2uchxnxyu.html

[L03] 设置自定义请求头
来源：http://dali.yueranfly.top/Article/details/gt2sfkwmvtv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cqqwz.cn/Article/details/gt2klausdpo.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xuetiantiany.cn/Article/details/gt2jbxgjvxq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hongshengwenyu.top/Article/details/gt2yqiwmhqm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuxming.cn/Article/details/gt2xpqmhegn.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cqqwz.cn/Article/details/gt2wesoyalk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.daria6918.cn/Article/details/gt2pmjevfuk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ivvv.top/Article/details/gt2cplngpvy.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.daria6918.cn/Article/details/gt2qldogdlc.html

[L04] 设置超时
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tkbyprze.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tianlin.xyz/Article/details/gt2rxbmtznv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eqhcsuwq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gogol.net.cn/Article/details/gt2dvrfolej.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nwbrower.top/Article/details/gt2kuzdqmio.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yonumen.top/Article/details/gt2clqjbjuh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.pycfn.com/Article/details/gt2xhymasfr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.fzhhl.top/Article/details/gt2fkmtknsw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xziqi.cn/Article/details/gt2ybsrnzrr.html

[L05] 上传文件（multipart）
来源：http://dali.yangfankeji.com/Article/details/gt2cvacaoro.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cdnleiting.top/Article/details/gt2vqopvxvl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cqqwz.cn/Article/details/gt2xkfypibb.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ivvv.top/Article/details/gt2jlhtjixl.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.316326.xyz/Article/details/gt2ipgibhfa.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinqigufen.top/Article/details/gt2iijtdwdb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ivvv.top/Article/details/gt2kejfzuvj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2etmydvhc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hdukrjfc.html

[L06] 解析响应为 JSON
来源：http://dali.tanke756.top/Article/details/gt2hhywtmxa.html

Py:   resp.json()
来源：http://dali.tanke756.top/Article/details/gt2bjgykvhf.html

PHP:  json_decode($body, true);
来源：http://dali.chenjidiqi.icu/Article/details/gt2oldwapdq.html

JS:   await resp.json()
来源：http://dali.vqdsnc.cn/Article/details/gt2ginmaibb.html

TS:   await resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gt2bhfttyxz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sxryk.cn/Article/details/gt2utauedds.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinqigufen.top/Article/details/gt2ganxrqok.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jianghu66.top/Article/details/gt2mcqqdlzw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shangyingyoupin.top/Article/details/gt2qyuyvoir.html

[L07] 处理 HTTP 状态码
来源：http://dali.xziqi.cn/Article/details/gt2hfzxozjg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hnxiangtu.top/Article/details/gt2cdyebvcu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jyoumei.cn/Article/details/gt2jnnylbzj.html

JS:   resp.ok;  resp.status
来源：http://dali.nanxuanxn.top/Article/details/gt2uxbzszrz.html

TS:   resp.ok;  resp.status
来源：http://dali.xziqi.cn/Article/details/gt2unqxzeco.html

Java: resp.statusCode()
来源：http://dali.tian-w.cn/Article/details/gt2dmsluvag.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2yaifgaew.html

Ruby: resp.code.to_i
来源：http://dali.chenlongwang.top/Article/details/gt2wriplpmz.html

C#:   (int)resp.StatusCode
来源：http://dali.mhx1999.top/Article/details/gt2ldgiuowq.html

[L08] 并发请求多个地址
来源：http://dali.xinyue.icu/Article/details/gt2bllkepty.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.guowangkeji.top/Article/details/gt2daehswgk.html

PHP:  curl_multi_init() 系列
来源：http://dali.svipenyu.cn/Article/details/gt2ycjfjhab.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yongpay.top/Article/details/gt2pijqspgc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenlongwang.top/Article/details/gt2zvhklwhw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gaohongyu789.top/Article/details/gt2zidizbbh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bhjwltlx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gaohongyu789.top/Article/details/gt2kgjitifa.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shangyingyoupin.top/Article/details/gt2uxaduuce.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2bjnzlokk.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmrpbmg.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2xrbjexfa.html

[M01] 读取命令行参数
来源：http://dali.andypj.xyz/Article/details/gt2hkfhvlbo.html

Py:   sys.argv[1:]
来源：http://dali.kuanghao11.cn/Article/details/gt2zwiznmpm.html

PHP:  $argv;  $argc;
来源：http://dali.jinqigufen.top/Article/details/gt2zckjrmoy.html

JS:   process.argv.slice(2)
来源：http://dali.sxryk.cn/Article/details/gt2mihwasqs.html

TS:   process.argv.slice(2)
来源：http://dali.jlsjyb.cn/Article/details/gt2rehfwzmd.html

Java: args 数组（main 方法参数）
来源：http://dali.jinqigufen.top/Article/details/gt2amcrdyfr.html

Go:   os.Args[1:]
来源：http://dali.snrcjt.cn/Article/details/gt2aajwaqnn.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdonxvo.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gaohongyu789.top/Article/details/gt2gicklwrq.html

[M02] 读取环境变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2lidmjhab.html

Py:   os.environ.get("HOME")
来源：http://dali.fengsongda.top/Article/details/gt2rhelrxzi.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ppjwa.cn/Article/details/gt2rwwfxceh.html

JS:   process.env.HOME
来源：http://dali.nanxuanxn.top/Article/details/gt2oopxkjfx.html

TS:   process.env.HOME
来源：http://dali.xinyue.icu/Article/details/gt2lustsfit.html

Java: System.getenv("HOME")
来源：http://dali.gzhubu.top/Article/details/gt2yltsxvdn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xylfe.cn/Article/details/gt2ehjqrydf.html

Ruby: ENV["HOME"]
来源：http://dali.shuidangran.top/Article/details/gt2ariguqod.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hfpthk.cn/Article/details/gt2eotqqpqe.html

[M03] 执行外部命令
来源：http://dali.ehwqpu.com/Article/details/gt2fyoivvwm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hnxiangtu.top/Article/details/gt2tdqcvqxc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gotoacloud.top/Article/details/gt2jkshycyl.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hysaishi.cn/Article/details/gt2drcbotos.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jyoumei.cn/Article/details/gt2nfzmdlzw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sufxvd.cn/Article/details/gt2hfnlvfkw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yj20258.top/Article/details/gt2mowuxdne.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cucudq.cn/Article/details/gt2wmnqfxub.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xuetiantiany.cn/Article/details/gt2nmomhgrl.html

[M04] 获取当前工作目录
来源：http://dali.feifeiyinyue.top/Article/details/gt2ctvcnsro.html

Py:   os.getcwd()
来源：http://dali.chenzaomai.com/Article/details/gt2rmytcbas.html

PHP:  getcwd();
来源：http://dali.birdmap.top/Article/details/gt2zrgtejos.html

JS:   process.cwd()
来源：http://dali.redwolf501.top/Article/details/gt2cdreboku.html

TS:   process.cwd()
来源：http://dali.cdnleiting.top/Article/details/gt2kjluylos.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xinyue.icu/Article/details/gt2htpirvae.html

Go:   os.Getwd()
来源：http://dali.zhongyouzk.top/Article/details/gt2rvvxeppk.html

Ruby: Dir.pwd
来源：http://dali.zhoulong.xyz/Article/details/gt2ntrfpdxq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yj202588.top/Article/details/gt2pnbdlciy.html

[M05] 设置退出码
来源：http://dali.haohaochexian.top/Article/details/gt2zgjtkpwo.html

Py:   sys.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gt2ngcswlqw.html

PHP:  exit(1);
来源：http://dali.chenjidiqi.icu/Article/details/gt2yudfbogv.html

JS:   process.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gt2ujoylmpe.html

TS:   process.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2voglkhyr.html

Java: System.exit(1)
来源：http://dali.daria6918.cn/Article/details/gt2xkwzaepv.html

Go:   os.Exit(1)
来源：http://dali.yangfankeji.com/Article/details/gt2fhhlwpbk.html

Ruby: exit 1
来源：http://dali.jyoumei.cn/Article/details/gt2pzcleblz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.0kj1m.cn/Article/details/gt2edxaggdj.html

[M06] 向标准错误输出
来源：http://dali.jianghu66.top/Article/details/gt2emtamjqh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.guannengcc.top/Article/details/gt2tjbzemjw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lwhazefh.html

JS:   console.error("err")
来源：http://dali.nanxinkj.top/Article/details/gt2lapherlc.html

TS:   console.error("err")
来源：http://dali.hfpthk.cn/Article/details/gt2oiyucvuw.html

Java: System.err.println("err")
来源：http://dali.yongpay.top/Article/details/gt2kqwnqpav.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.kuanghao11.cn/Article/details/gt2fltrryyu.html

Ruby: warn "err"
来源：http://dali.andypj.xyz/Article/details/gt2yzmwdfwu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.vqdsnc.cn/Article/details/gt2posgadgb.html

[M07] 判断是否为主入口
来源：http://dali.cqqwz.cn/Article/details/gt2yoxfxzpy.html

Py:   if __name__ == "__main__":
来源：http://dali.yj20258888.top/Article/details/gt2usjqppvq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.chenjidiqi.icu/Article/details/gt2yappiger.html

JS:   require.main === module
来源：http://dali.sysykeji.top/Article/details/gt2pelxpdml.html

TS:   require.main === module
来源：http://dali.jianghu66.top/Article/details/gt2tppneznw.html


<!-- 参考信息 -->