代发 wailian999

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ydzc1.top/Article/details/gt2nimbqrkj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cdnleiting.top/Article/details/gt2azcxybzl.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.tanke756.top/Article/details/gt2juhkzgvw.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2iytwlvqm.html

J. 日期与时间
来源：http://dali.jiagoushi.top/Article/details/gt2jtnoplms.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2ycnbhbfx.html

[J01] 获取当前时间
来源：http://dali.hysaishi.cn/Article/details/gt2fynvolqq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ppjwa.cn/Article/details/gt2dhzxgjrf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ppjwa.cn/Article/details/gt2ebbtpqnq.html

JS:   new Date();  Date.now()
来源：http://dali.hnxiangtu.top/Article/details/gt2gzlhbrjh.html

TS:   new Date();  Date.now()
来源：http://dali.xinyue.icu/Article/details/gt2sooexvxn.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hywenlv.cn/Article/details/gt2heqejsxp.html

Go:   time.Now()
来源：http://dali.xuanzx.com/Article/details/gt2ckoaylap.html

Ruby: Time.now
来源：http://dali.hysaishi.cn/Article/details/gt2vzmcsvot.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.0kj1m.cn/Article/details/gt2pjddwtps.html

[J02] 格式化输出
来源：http://dali.c1oappe.top/Article/details/gt2atytkusx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guowangkeji.top/Article/details/gt2aduwcwgc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.aibaodan.cn/Article/details/gt2vwrmxwac.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.9152youxi.cn/Article/details/gt2safaxxpi.html

TS:   d.toISOString()
来源：http://dali.quarkkingdee.top/Article/details/gt2rnpuuirh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhongyouzk.top/Article/details/gt2bhbmxcrk.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xuetiantiany.cn/Article/details/gt2avqkojfn.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuxming.cn/Article/details/gt2ynbwdign.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yueranfly.top/Article/details/gt2aajbkqus.html

[J03] 字符串解析为日期
来源：http://dali.ppjwa.cn/Article/details/gt2hufjlkoh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.c1oappe.top/Article/details/gt2xhtksrav.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hysaishi.cn/Article/details/gt2cbpvolpt.html

JS:   new Date("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gt2lrorqlae.html

TS:   new Date("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gt2vbofyivn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gt2gbndqzih.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gt2xicxztmp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gt2yjmchfko.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenzaomai.com/Article/details/gt2dhosrmmd.html

[J04] 时间戳与日期互转
来源：http://dali.chenlongwang.top/Article/details/gt2thkqosek.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.dianchejie.cn/Article/details/gt2ijvwowbo.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hongshengwenyu.top/Article/details/gt2vofvmcmp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jiagoushi.top/Article/details/gt2fcoypngw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yangfankeji.com/Article/details/gt2scqasbff.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2kblckmmu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.chenlongwang.top/Article/details/gt2cpyyorel.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yj20258888.top/Article/details/gt2vfctyxyb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sweek.top/Article/details/gt2xdwqntll.html

[J05] 时间加减（加 7 天）
来源：http://dali.jqgufenzy.top/Article/details/gt2gdtuoajx.html

Py:   now + timedelta(days=7)
来源：http://dali.cashguo.top/Article/details/gt2djzimmom.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hammf.cn/Article/details/gt2afzojmky.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cheryme.top/Article/details/gt2yvgkqmvw.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258888.top/Article/details/gt2wyzgjvhf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shuidangran.top/Article/details/gt2ffvuzajz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ahadgkcq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xziqi.cn/Article/details/gt2iofetbjk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sysykeji.top/Article/details/gt2nnvdolni.html

[J06] 计算两时间之差
来源：http://dali.chenlongwang.top/Article/details/gt2pthlugsw.html

Py:   (end - start).total_seconds()
来源：http://dali.ivvv.top/Article/details/gt2sjsbqmah.html

PHP:  $end->diff($start)->days;
来源：http://dali.dianchejie.cn/Article/details/gt2owbzzsnf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.bjfxy.top/Article/details/gt2kzcerhan.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.guannengcc.top/Article/details/gt2zvjktsye.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kiqttted.html

Go:   end.Sub(start).Hours()
来源：http://dali.cqqwz.cn/Article/details/gt2tvlxarid.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2acvbsjmn.html

C#:   (end - start).TotalSeconds
来源：http://dali.cashguo.top/Article/details/gt2haxpjubq.html

[J07] 比较两个日期
来源：http://dali.shuidangran.top/Article/details/gt2haohapzg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gt2gpgmzxrq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nanxuanxn.top/Article/details/gt2ruttaahi.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hywenlv.cn/Article/details/gt2bihhvdeh.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hongshengwenyu.top/Article/details/gt2xityrowr.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jqgfzy.top/Article/details/gt2tspxxdqm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhongyouzk.top/Article/details/gt2pltxrknd.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenlongwang.top/Article/details/gt2ezqeqplz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gt2trkgynba.html

[J08] 提取年月日与星期
来源：http://dali.yvedp.cn/Article/details/gt2yzszsqkz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nanxuanxn.top/Article/details/gt2yxbexbhc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bfecqfyv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hywenlv.cn/Article/details/gt2kkhyfyti.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yangfankeji.com/Article/details/gt2pnnzhspk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yanxiufei.cn/Article/details/gt2mpqpfqxa.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.aizwys.cn/Article/details/gt2koyezzxp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.wangshuangyany.cn/Article/details/gt2hnzlhlcb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ivvv.top/Article/details/gt2dyntxijp.html

[J09] 时区处理
来源：http://dali.guowangkeji.top/Article/details/gt2zuffafkz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.tanke756.top/Article/details/gt2kyiqzxsw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cashguo.top/Article/details/gt2ljfprkwo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.haohaochexian.top/Article/details/gt2ktkndhbf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.birdmap.top/Article/details/gt2bvfvwnom.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yuxming.cn/Article/details/gt2jpvujilc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hnqzz.top/Article/details/gt2qmjxduqy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhixingplan.top/Article/details/gt2zxdbjxfd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dvauqcqn.html

[J10] 取今天 / 本月第一天
来源：http://dali.zycfv.cn/Article/details/gt2ypwoqtac.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yj202588.top/Article/details/gt2qdnqvufl.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xinyue.icu/Article/details/gt2ztuadycm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.snrcjt.cn/Article/details/gt2swowqleg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shuidangran.top/Article/details/gt2pqdetosf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.wangdashe.top/Article/details/gt2icjrlwjf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jqgufenzy.top/Article/details/gt2kqzgycbd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xuetiantiany.cn/Article/details/gt2xotdabjy.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ivvv.top/Article/details/gt2pdtjlida.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2lophdlqi.html

K. JSON 与序列化
来源：http://dali.zhengqikj.top/Article/details/gt2mxviqcxx.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2swqsievb.html

[K01] 对象转 JSON 字符串
来源：http://dali.cheryme.top/Article/details/gt2iwbvqiie.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.snrcjt.cn/Article/details/gt2vcxutlfu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.wangdashe.top/Article/details/gt2nhgjpnex.html

JS:   JSON.stringify(obj)
来源：http://dali.yuxming.cn/Article/details/gt2fzadkcrr.html

TS:   JSON.stringify(obj)
来源：http://dali.hammf.cn/Article/details/gt2xdxlewho.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jkyvtasz.html

Go:   json.Marshal(obj)
来源：http://dali.birdmap.top/Article/details/gt2ojdhjbuj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.wangdashe.top/Article/details/gt2pupresgz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2tfswsazd.html

[K02] JSON 字符串转对象
来源：http://dali.yongpay.top/Article/details/gt2kdbzfgac.html

Py:   json.loads(s)
来源：http://dali.yj20258888.top/Article/details/gt2abjjjvbi.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hammf.cn/Article/details/gt2oknkoewi.html

JS:   JSON.parse(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mwogcbyj.html

TS:   JSON.parse(s)
来源：http://dali.sufxvd.cn/Article/details/gt2wbfpeyfz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.smart0.xyz/Article/details/gt2fkakqxlz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xziqi.cn/Article/details/gt2mbhipaxl.html

Ruby: JSON.parse(s)
来源：http://dali.cheryme.top/Article/details/gt2gguiykhn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yuxming.cn/Article/details/gt2sygdrakj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xuanzx.com/Article/details/gt2ybjgwfvm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.havefunace.top/Article/details/gt2wocvpxde.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shzxlz.cn/Article/details/gt2opnpmayd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qkrpsqdh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhengqikj.top/Article/details/gt2atixyvbn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2gzbfvxup.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hnqzz.top/Article/details/gt2ssqalscg.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.mhx1999.top/Article/details/gt2beghffki.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sweek.top/Article/details/gt2jsbrfbpm.html

[K04] 读取 JSON 文件
来源：http://dali.yangfankeji.com/Article/details/gt2ljvmdxfm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yangfankeji.com/Article/details/gt2yppiqemg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cheryme.top/Article/details/gt2ksjjooet.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxinkj.top/Article/details/gt2rfzztzze.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2msnkwyxb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.c1oappe.top/Article/details/gt2ouetqhwh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.pycfn.com/Article/details/gt2rsnzlmng.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.c1oappe.top/Article/details/gt2dezhhikb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.aibaodan.cn/Article/details/gt2ypkjgobe.html

[K05] 深拷贝对象
来源：http://dali.nanxinkj.top/Article/details/gt2qletcznb.html

Py:   copy.deepcopy(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2lasmzeay.html

PHP:  unserialize(serialize($obj));
来源：http://dali.chenlongwang.top/Article/details/gt2rfyhextt.html

JS:   structuredClone(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2mhunstpe.html

TS:   structuredClone(obj)
来源：http://dali.redwolf501.top/Article/details/gt2ukeepxmh.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhengqikj.top/Article/details/gt2cjhtmikt.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.redwolf501.top/Article/details/gt2mansaetu.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.vqdsnc.cn/Article/details/gt2blzhrkxy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.mhx1999.top/Article/details/gt2wtueipsl.html

[K06] 解析 URL 查询串
来源：http://dali.nanxuanxn.top/Article/details/gt2zlnczxge.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jiagoushi.top/Article/details/gt2ikizpmqo.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.iojbl.cn/Article/details/gt2hcpdejdf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hfpthk.cn/Article/details/gt2wmkxlxbt.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hfpthk.cn/Article/details/gt2ssvfdgtu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nwbrower.top/Article/details/gt2mrwnjnpz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xziqi.cn/Article/details/gt2gbdlahel.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gt2nuaufqsx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.mhx1999.top/Article/details/gt2hqenaylq.html

[K07] 进制转换
来源：http://dali.guannengcc.top/Article/details/gt2syjferyd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gt2daumdqyj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2bthvexem.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2usrbmayz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gt2evhvjrvu.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gt2ycnlpjve.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wkbsvrid.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xzzdrbja.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gt2yvjnmjpj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhiwuduotai.top/Article/details/gt2cqalfukg.html

Py:   pickle.dumps(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2dwbamjlk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shuidangran.top/Article/details/gt2flxamkus.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.tian-w.cn/Article/details/gt2nrrywcic.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2izieflqm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hnxiangtu.top/Article/details/gt2xebhlysi.html

Go:   encoding/gob
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qmsrebur.html

Ruby: Marshal.dump(obj)
来源：http://dali.xziqi.cn/Article/details/gt2rujsoouk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sysykeji.top/Article/details/gt2ehjcqmyn.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pcuyqgpp.html

L. 网络请求
来源：http://dali.birdmap.top/Article/details/gt2kiqltczt.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2vvmirdph.html

[L01] 发送 GET 请求
来源：http://dali.jqgfzy.top/Article/details/gt2mopcgiis.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj20258888.top/Article/details/gt2wwrxxtsu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ppjwa.cn/Article/details/gt2myfqiuwo.html

JS:   await fetch(url)
来源：http://dali.sufxvd.cn/Article/details/gt2byoykawy.html

TS:   await fetch(url)
来源：http://dali.hywenlv.cn/Article/details/gt2neuhjygc.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.andypj.xyz/Article/details/gt2sjzgpphi.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vpeobsaf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.havefunace.top/Article/details/gt2tndwvqpq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.vqdsnc.cn/Article/details/gt2maudxdwa.html

[L02] 发送 POST JSON
来源：http://dali.gaohongyu789.top/Article/details/gt2ktbyreug.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hnxiangtu.top/Article/details/gt2enybkpqw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.pycfn.com/Article/details/gt2ybjwyzzv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.meibo888.top/Article/details/gt2kptgufqu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangshuangyany.cn/Article/details/gt2itibrcnv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.mhx1999.top/Article/details/gt2nrpltrrf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gogol.net.cn/Article/details/gt2orriklsy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ivvv.top/Article/details/gt2sfsibifk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.316326.xyz/Article/details/gt2ubadkszh.html

[L03] 设置自定义请求头
来源：http://dali.wangdashe.top/Article/details/gt2csqofakl.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jqgfzy.top/Article/details/gt2ocjomeca.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.kuanghao11.cn/Article/details/gt2xfjfssgo.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenzaomai.com/Article/details/gt2ooyjumdb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.snrcjt.cn/Article/details/gt2vofrwket.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhiwuduotai.top/Article/details/gt2hutemigt.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jyoumei.cn/Article/details/gt2exgzzxqe.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hnxiangtu.top/Article/details/gt2ggbvhtbr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.birdmap.top/Article/details/gt2lmbhhbun.html

[L04] 设置超时
来源：http://dali.quarkkingdee.top/Article/details/gt2sivpkesk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gzhubu.top/Article/details/gt2qsncgwal.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hywenlv.cn/Article/details/gt2fpicdfaj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shangyingyoupin.top/Article/details/gt2kauclthf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cheryme.top/Article/details/gt2cshthfio.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.chenjidiqi.icu/Article/details/gt2emscfefz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yuxming.cn/Article/details/gt2hpttpfnp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jiagoushi.top/Article/details/gt2qcrtkecc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.snrcjt.cn/Article/details/gt2txrdbuks.html

[L05] 上传文件（multipart）
来源：http://dali.aizwys.cn/Article/details/gt2tdpfryql.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jqgfzy.top/Article/details/gt2qevtwaof.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.mhx1999.top/Article/details/gt2chvghvoc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tianlin.xyz/Article/details/gt2bioqavon.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.tanke756.top/Article/details/gt2wpvkgjau.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jiagoushi.top/Article/details/gt2oprsykgz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2gazmdeya.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hnxiangtu.top/Article/details/gt2nafbevvb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gotoacloud.top/Article/details/gt2mvpexzqc.html

[L06] 解析响应为 JSON
来源：http://dali.jinqigufen.top/Article/details/gt2oiplwyjc.html

Py:   resp.json()
来源：http://dali.meibo888.top/Article/details/gt2zpjlkgvg.html

PHP:  json_decode($body, true);
来源：http://dali.yangfankeji.com/Article/details/gt2jwnfaxsm.html

JS:   await resp.json()
来源：http://dali.ybcxt.top/Article/details/gt2acwmfkqj.html

TS:   await resp.json()
来源：http://dali.jinqigufen.top/Article/details/gt2pvsexeaa.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xuetiantiany.cn/Article/details/gt2yvziciza.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.gotoacloud.top/Article/details/gt2uweurwap.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj20258888.top/Article/details/gt2cjzvlpsg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.smart0.xyz/Article/details/gt2dokaomui.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinqigfzy.top/Article/details/gt2kfgpbwkt.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tian-w.cn/Article/details/gt2fzufaslm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xinyue.icu/Article/details/gt2gotfefxf.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2iktiavgb.html

TS:   resp.ok;  resp.status
来源：http://dali.hywenlv.cn/Article/details/gt2caljvwsr.html

Java: resp.statusCode()
来源：http://dali.yj20258.top/Article/details/gt2hbyiwyrl.html

Go:   resp.StatusCode
来源：http://dali.jianghu66.top/Article/details/gt2oxswvbqv.html

Ruby: resp.code.to_i
来源：http://dali.xziqi.cn/Article/details/gt2dpzvkbls.html

C#:   (int)resp.StatusCode
来源：http://dali.wangshuangyany.cn/Article/details/gt2vwnevmky.html

[L08] 并发请求多个地址
来源：http://dali.chenlongwang.top/Article/details/gt2tnhqsdet.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.kuanghao11.cn/Article/details/gt2obisyyiu.html

PHP:  curl_multi_init() 系列
来源：http://dali.yuxming.cn/Article/details/gt2hmwvskke.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lwcivdvt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.vqdsnc.cn/Article/details/gt2byxeihes.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ivvv.top/Article/details/gt2immjjmkw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2gergctqj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.haohaochexian.top/Article/details/gt2bwvrcnnh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ybcxt.top/Article/details/gt2qkxujnev.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2rfjfwueo.html

M. 命令行 / 进程 / 环境
来源：http://dali.redwolf501.top/Article/details/gt2kjjstbht.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2uokioqbv.html

[M01] 读取命令行参数
来源：http://dali.zhengqikj.top/Article/details/gt2aroediea.html

Py:   sys.argv[1:]
来源：http://dali.ppjwa.cn/Article/details/gt2fwfqibra.html

PHP:  $argv;  $argc;
来源：http://dali.0kj1m.cn/Article/details/gt2hssbashp.html

JS:   process.argv.slice(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fwuwrkpp.html

TS:   process.argv.slice(2)
来源：http://dali.zdqjudy.top/Article/details/gt2lcrajxop.html

Java: args 数组（main 方法参数）
来源：http://dali.yj202588.top/Article/details/gt2gvmwwtgi.html

Go:   os.Args[1:]
来源：http://dali.zycfv.cn/Article/details/gt2qavjszyv.html

Ruby: ARGV
来源：http://dali.ydzc1.top/Article/details/gt2ufhfydwx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zqvutyue.html

[M02] 读取环境变量
来源：http://dali.hammf.cn/Article/details/gt2fturcobz.html

Py:   os.environ.get("HOME")
来源：http://dali.yj202588.top/Article/details/gt2nfaerpxj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.fzhhl.top/Article/details/gt2jmmriaqa.html

JS:   process.env.HOME
来源：http://dali.quarkkingdee.top/Article/details/gt2wuyjacbn.html

TS:   process.env.HOME
来源：http://dali.zhiwuduotai.top/Article/details/gt2wgzbwuht.html

Java: System.getenv("HOME")
来源：http://dali.sxryk.cn/Article/details/gt2umwidhfb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gt2kjzcuhzg.html

Ruby: ENV["HOME"]
来源：http://dali.meibo888.top/Article/details/gt2uhfsyhxc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gt2dmajfcec.html

[M03] 执行外部命令
来源：http://dali.yuxming.cn/Article/details/gt2nnjkpdju.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xziqi.cn/Article/details/gt2wcmxmuat.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gogol.net.cn/Article/details/gt2dbrqqwru.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258888.top/Article/details/gt2pbosafnb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shuidangran.top/Article/details/gt2ejrbeejb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.tanke756.top/Article/details/gt2qtkgtyii.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nwbrower.top/Article/details/gt2trtvebsv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cjzhwfur.html

C#:   Process.Start("ls", "-l");
来源：http://dali.bjfxy.top/Article/details/gt2grioqfvt.html

[M04] 获取当前工作目录
来源：http://dali.ybcxt.top/Article/details/gt2awuxrovn.html

Py:   os.getcwd()
来源：http://dali.andypj.xyz/Article/details/gt2zhwhxdni.html

PHP:  getcwd();
来源：http://dali.sweek.top/Article/details/gt2bwwwohau.html

JS:   process.cwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xvfohlku.html

TS:   process.cwd()
来源：http://dali.cashguo.top/Article/details/gt2txjrrhwn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenzaomai.com/Article/details/gt2teygceaf.html

Go:   os.Getwd()
来源：http://dali.yonumen.top/Article/details/gt2ukjikffr.html

Ruby: Dir.pwd
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dqhjlhie.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.fengsongda.top/Article/details/gt2iuocaeph.html

[M05] 设置退出码
来源：http://dali.wangdashe.top/Article/details/gt2dwhwkctz.html

Py:   sys.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gt2wjwjlugg.html

PHP:  exit(1);
来源：http://dali.sweek.top/Article/details/gt2slrnsrlk.html

JS:   process.exit(1)
来源：http://dali.iojbl.cn/Article/details/gt2uqcjqgru.html

TS:   process.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gt2jxbtikhv.html

Java: System.exit(1)
来源：http://dali.xinyue.icu/Article/details/gt2bxbsnmjl.html

Go:   os.Exit(1)
来源：http://dali.gzhubu.top/Article/details/gt2opjjeqvy.html

Ruby: exit 1
来源：http://dali.yanxiufei.cn/Article/details/gt2utwsnxgc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jlsjyb.cn/Article/details/gt2zviqdxav.html

[M06] 向标准错误输出
来源：http://dali.sweek.top/Article/details/gt2zzdqkwpw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2oovlobvd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmgeqpy.html

JS:   console.error("err")
来源：http://dali.dianchejie.cn/Article/details/gt2vlslcjmk.html

TS:   console.error("err")
来源：http://dali.dashuyun.cn/Article/details/gt2jiqoysyv.html

Java: System.err.println("err")
来源：http://dali.shzxlz.cn/Article/details/gt2vcsbyyfc.html


<!-- 参考信息 -->