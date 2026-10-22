代发 wailian999

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yonumen.top/Article/details/gt2urxnaqgi.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.andypj.xyz/Article/details/gt2zjkqmpse.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yvedp.cn/Article/details/gt2zclsikpr.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2pvjuuapv.html

J. 日期与时间
来源：http://dali.xylfe.cn/Article/details/gt2nxrpftuz.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2gewpuvwo.html

[J01] 获取当前时间
来源：http://dali.svipenyu.cn/Article/details/gt2gjziojfc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinqigfzy.top/Article/details/gt2fxgiqtir.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ehwqpu.com/Article/details/gt2kymvmwwj.html

JS:   new Date();  Date.now()
来源：http://dali.sxryk.cn/Article/details/gt2edprygce.html

TS:   new Date();  Date.now()
来源：http://dali.aibaodan.cn/Article/details/gt2wzetzphn.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhiwuduotai.top/Article/details/gt2uoeuhniv.html

Go:   time.Now()
来源：http://dali.iojbl.cn/Article/details/gt2mfailtaw.html

Ruby: Time.now
来源：http://dali.sysykeji.top/Article/details/gt2dtyepdkl.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenzaomai.com/Article/details/gt2bihycyoh.html

[J02] 格式化输出
来源：http://dali.yueranfly.top/Article/details/gt2ewcqxvrl.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nwbrower.top/Article/details/gt2tpsyaghs.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cheryme.top/Article/details/gt2nfulggkx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sweek.top/Article/details/gt2killipmc.html

TS:   d.toISOString()
来源：http://dali.tianlin.xyz/Article/details/gt2dqljykhk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hysaishi.cn/Article/details/gt2hsjtwjmx.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hnqzz.top/Article/details/gt2qrpujytm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ivvv.top/Article/details/gt2midurxny.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.meibo888.top/Article/details/gt2gwfotiec.html

[J03] 字符串解析为日期
来源：http://dali.yangfankeji.com/Article/details/gt2jbtlqimh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cashguo.top/Article/details/gt2kuwtlhbw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.haohaochexian.top/Article/details/gt2htkpvota.html

JS:   new Date("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gt2baqcpphs.html

TS:   new Date("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gt2jnrlsjlz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gt2zamhqkpm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yonumen.top/Article/details/gt2vxcwwgaa.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gt2epiezkuy.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.pycfn.com/Article/details/gt2eqyzipfd.html

[J04] 时间戳与日期互转
来源：http://dali.svipenyu.cn/Article/details/gt2tppfdexw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xinyue.icu/Article/details/gt2jwdbjjfz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yonumen.top/Article/details/gt2owbhkpmo.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gaohongyu789.top/Article/details/gt2scmopijl.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jianghu66.top/Article/details/gt2jgazwgxn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.havefunace.top/Article/details/gt2ydfwodvw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cqqwz.cn/Article/details/gt2fdldyyaj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.bjfxy.top/Article/details/gt2ulfkalwy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.havefunace.top/Article/details/gt2ttxgznzj.html

[J05] 时间加减（加 7 天）
来源：http://dali.ivvv.top/Article/details/gt2zxdbougo.html

Py:   now + timedelta(days=7)
来源：http://dali.sweek.top/Article/details/gt2gfmgypoi.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gotoacloud.top/Article/details/gt2mymcqjjl.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ppjwa.cn/Article/details/gt2zownuzbp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nanxuanxn.top/Article/details/gt2koiskpjv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ecrqjois.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cashguo.top/Article/details/gt2sdzluxfa.html

Ruby: Time.now + 7 * 86400
来源：http://dali.daria6918.cn/Article/details/gt2wrkuzlde.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shzxlz.cn/Article/details/gt2dfnlkqmw.html

[J06] 计算两时间之差
来源：http://dali.ybcxt.top/Article/details/gt2fuzrdvgl.html

Py:   (end - start).total_seconds()
来源：http://dali.fengsongda.top/Article/details/gt2vqnwybpr.html

PHP:  $end->diff($start)->days;
来源：http://dali.aizwys.cn/Article/details/gt2sjyykihh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinqigfzy.top/Article/details/gt2xijejsjl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.aizwys.cn/Article/details/gt2jpftbwci.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shzxlz.cn/Article/details/gt2htbwmngd.html

Go:   end.Sub(start).Hours()
来源：http://dali.aizwys.cn/Article/details/gt2hfvskbem.html

Ruby: end - start                 # 返回秒数
来源：http://dali.havefunace.top/Article/details/gt2vqohoauo.html

C#:   (end - start).TotalSeconds
来源：http://dali.hywenlv.cn/Article/details/gt2jhrhahzy.html

[J07] 比较两个日期
来源：http://dali.ydzc1.top/Article/details/gt2osqgkzhm.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jyoumei.cn/Article/details/gt2twhwbhvi.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yanxiufei.cn/Article/details/gt2wntcckfk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.tanke756.top/Article/details/gt2vxuqatdx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yangfankeji.com/Article/details/gt2lhldgbjd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cgztfrfn.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.dashuyun.cn/Article/details/gt2yowhlrvu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.dianchejie.cn/Article/details/gt2mwsgjduj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shzxlz.cn/Article/details/gt2ctqenemq.html

[J08] 提取年月日与星期
来源：http://dali.gzhubu.top/Article/details/gt2lhzivxye.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.havefunace.top/Article/details/gt2dhxhkjgs.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xziqi.cn/Article/details/gt2xbycwnti.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhijiandao.cn/Article/details/gt2sejfnksn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xinyue.icu/Article/details/gt2cwuszxpn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhengqikj.top/Article/details/gt2zrbldzch.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xziqi.cn/Article/details/gt2dacxrxqn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ydzc1.top/Article/details/gt2fjkmabsd.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yangfankeji.com/Article/details/gt2xeipdbvz.html

[J09] 时区处理
来源：http://dali.zhixingplan.top/Article/details/gt2wuzjjrfb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.vqdsnc.cn/Article/details/gt2qxewnrep.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.mhx1999.top/Article/details/gt2ppnvvogs.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.bjfxy.top/Article/details/gt2egtbbopt.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.316326.xyz/Article/details/gt2lflgolxh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cashguo.top/Article/details/gt2bpusqjgk.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yongpay.top/Article/details/gt2tudggyad.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.tian-w.cn/Article/details/gt2tecmavsl.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ujmzzexm.html

[J10] 取今天 / 本月第一天
来源：http://dali.ybcxt.top/Article/details/gt2gsrvgpjk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.pycfn.com/Article/details/gt2andkzqai.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.chenzaomai.com/Article/details/gt2brzlzkbw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.bjfxy.top/Article/details/gt2ygyglxfa.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.316326.xyz/Article/details/gt2ntazvujv.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj20258888.top/Article/details/gt2nntbfsyq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.haohaochexian.top/Article/details/gt2eczlbgru.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.chenzaomai.com/Article/details/gt2dmkvyduv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.haohaochexian.top/Article/details/gt2vflqgunv.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2znqqaxhu.html

K. JSON 与序列化
来源：http://dali.cashguo.top/Article/details/gt2csqvmrna.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2mfckitdk.html

[K01] 对象转 JSON 字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2rbydzyqz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.vqdsnc.cn/Article/details/gt2ctobjgro.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gaohongyu789.top/Article/details/gt2txabxunx.html

JS:   JSON.stringify(obj)
来源：http://dali.daxiang520.top/Article/details/gt2xkpmdgqb.html

TS:   JSON.stringify(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2woubltlc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sufxvd.cn/Article/details/gt2gudvzmth.html

Go:   json.Marshal(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ppnhlluy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.pengpengdd.cyou/Article/details/gt2wvuuwnrb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2zlihylzw.html

[K02] JSON 字符串转对象
来源：http://dali.nwbrower.top/Article/details/gt2uefcdxpt.html

Py:   json.loads(s)
来源：http://dali.316326.xyz/Article/details/gt2scxwuogb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ivvv.top/Article/details/gt2uuplapcl.html

JS:   JSON.parse(s)
来源：http://dali.jyoumei.cn/Article/details/gt2fakkxxaz.html

TS:   JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2tjxxohqq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yj20258888.top/Article/details/gt2mitvsggw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jiagoushi.top/Article/details/gt2cfiydlig.html

Ruby: JSON.parse(s)
来源：http://dali.0kj1m.cn/Article/details/gt2pvpgzrcl.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hthwpdpe.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hammf.cn/Article/details/gt2lpkofucq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yvedp.cn/Article/details/gt2hktojzbu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.daxiang520.top/Article/details/gt2xzhdehub.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2dfsifrou.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.daria6918.cn/Article/details/gt2yknfbpni.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bzarskfl.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.daxiang520.top/Article/details/gt2ztodotzn.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sysykeji.top/Article/details/gt2sklvndmt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sysykeji.top/Article/details/gt2qwexsdvc.html

[K04] 读取 JSON 文件
来源：http://dali.gogol.net.cn/Article/details/gt2jrlzfhgw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinqigufen.top/Article/details/gt2fobbgqwb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj20258.top/Article/details/gt2otwjarnh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.vqdsnc.cn/Article/details/gt2fffttrxc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cxbsyhnz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.chenzaomai.com/Article/details/gt2hltkrmcu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.haohaochexian.top/Article/details/gt2kxneifpb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hysaishi.cn/Article/details/gt2vgdkbehz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gzhubu.top/Article/details/gt2oyvkayjs.html

[K05] 深拷贝对象
来源：http://dali.gogol.net.cn/Article/details/gt2pgluwusk.html

Py:   copy.deepcopy(obj)
来源：http://dali.hammf.cn/Article/details/gt2vxofvlaf.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ybcxt.top/Article/details/gt2sequeurm.html

JS:   structuredClone(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2undydcjm.html

TS:   structuredClone(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rowrscgd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.bjfxy.top/Article/details/gt2gtiacmmq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhiwuduotai.top/Article/details/gt2dnykndzx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.aibaodan.cn/Article/details/gt2dibmybos.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jwypseby.html

[K06] 解析 URL 查询串
来源：http://dali.316326.xyz/Article/details/gt2oqzdvilr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.0kj1m.cn/Article/details/gt2aluszprc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yanxiufei.cn/Article/details/gt2wahfuyez.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.vqdsnc.cn/Article/details/gt2bfvrbknd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangdashe.top/Article/details/gt2vnwmyknu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xuetiantiany.cn/Article/details/gt2ywiombne.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mvshnnpu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ybcxt.top/Article/details/gt2vkiazkzi.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jlsjyb.cn/Article/details/gt2pyfykogi.html

[K07] 进制转换
来源：http://dali.yj202588.top/Article/details/gt2apgdrszp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gt2xwoklene.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cheryme.top/Article/details/gt2qvyqqtuz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gt2ptxjwqre.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ofpkrxtk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gt2vvveecbp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jlsjyb.cn/Article/details/gt2hsvfqhev.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xuanzx.com/Article/details/gt2zrwbqntf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gt2xszttrhh.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zycfv.cn/Article/details/gt2czdlsqks.html

Py:   pickle.dumps(obj)
来源：http://dali.tanke756.top/Article/details/gt2mebkvohi.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.svipenyu.cn/Article/details/gt2bmkjdrzz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj202588.top/Article/details/gt2njingcur.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigufen.top/Article/details/gt2evkrpoiz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yueranfly.top/Article/details/gt2evxewnqf.html

Go:   encoding/gob
来源：http://dali.xuanzx.com/Article/details/gt2zohlmjcp.html

Ruby: Marshal.dump(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2tatrbboq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jiagoushi.top/Article/details/gt2rdqjqeki.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dlytkznu.html

L. 网络请求
来源：http://dali.jianghu66.top/Article/details/gt2cglcxszd.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mzicebrk.html

[L01] 发送 GET 请求
来源：http://dali.zhixingplan.top/Article/details/gt2csmizemk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gogol.net.cn/Article/details/gt2csqvwsxa.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.birdmap.top/Article/details/gt2qthfacid.html

JS:   await fetch(url)
来源：http://dali.yanxiufei.cn/Article/details/gt2hwrwvzlu.html

TS:   await fetch(url)
来源：http://dali.yongpay.top/Article/details/gt2lqnzdeed.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shangyingyoupin.top/Article/details/gt2rcwtfitn.html

Go:   resp, err := http.Get(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2humrdebb.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xuetiantiany.cn/Article/details/gt2gmjldpfh.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.bjfxy.top/Article/details/gt2uhpmkkpm.html

[L02] 发送 POST JSON
来源：http://dali.c1oappe.top/Article/details/gt2qdrzfgsz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cdnleiting.top/Article/details/gt2mhayahzl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xuanzx.com/Article/details/gt2mhsmdmnm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuxming.cn/Article/details/gt2dmhnyqcb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.c1oappe.top/Article/details/gt2vxgvgmby.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shzxlz.cn/Article/details/gt2qfqdlzyj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xylfe.cn/Article/details/gt2jbmrlysq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.c1oappe.top/Article/details/gt2fxdalaoc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.daria6918.cn/Article/details/gt2qurzkwgf.html

[L03] 设置自定义请求头
来源：http://dali.xinyue.icu/Article/details/gt2cbvisrsj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinqigufen.top/Article/details/gt2yfruhgta.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jqgufenzy.top/Article/details/gt2axhbfhds.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nwbrower.top/Article/details/gt2odzktltt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fzhhl.top/Article/details/gt2jwticsmm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yvedp.cn/Article/details/gt2muagxsty.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xylfe.cn/Article/details/gt2wsanjpdn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhongyouzk.top/Article/details/gt2gzposqyt.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgkfxaz.html

[L04] 设置超时
来源：http://dali.daxiang520.top/Article/details/gt2jvaczxkq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ybcxt.top/Article/details/gt2mwedgmxi.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hnqzz.top/Article/details/gt2yfdbveqd.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.mhx1999.top/Article/details/gt2ibfgakwm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jlsjyb.cn/Article/details/gt2ymmsgkys.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jyoumei.cn/Article/details/gt2kiggfuav.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hysaishi.cn/Article/details/gt2lhhxzfyr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.smart0.xyz/Article/details/gt2dtbubdhr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shangyingyoupin.top/Article/details/gt2koxpuguf.html

[L05] 上传文件（multipart）
来源：http://dali.jinqigufen.top/Article/details/gt2yiazupsp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hammf.cn/Article/details/gt2zojojzbm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cucudq.cn/Article/details/gt2ykusxfrr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tanke756.top/Article/details/gt2qoffmvhq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxinkj.top/Article/details/gt2kqvdqufb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2viktzemp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.dianchejie.cn/Article/details/gt2hrgsmsum.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.feifeiyinyue.top/Article/details/gt2ymkozfjb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yj202588.top/Article/details/gt2vmmoqfmm.html

[L06] 解析响应为 JSON
来源：http://dali.shuidangran.top/Article/details/gt2hrufjaeq.html

Py:   resp.json()
来源：http://dali.tanke756.top/Article/details/gt2toxvvyny.html

PHP:  json_decode($body, true);
来源：http://dali.cdnleiting.top/Article/details/gt2ziacbjdf.html

JS:   await resp.json()
来源：http://dali.316326.xyz/Article/details/gt2jvgpqtvk.html

TS:   await resp.json()
来源：http://dali.hnxiangtu.top/Article/details/gt2pcrfodhj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.0kj1m.cn/Article/details/gt2obihfyvz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.aibaodan.cn/Article/details/gt2efqzdwja.html

Ruby: JSON.parse(resp.body)
来源：http://dali.wangshuangyany.cn/Article/details/gt2bxzfttse.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj202588.top/Article/details/gt2atgkragp.html

[L07] 处理 HTTP 状态码
来源：http://dali.xziqi.cn/Article/details/gt2pserqpwv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.pengpengdd.cyou/Article/details/gt2afrtvbgd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yvedp.cn/Article/details/gt2dvmgmxoj.html

JS:   resp.ok;  resp.status
来源：http://dali.hywenlv.cn/Article/details/gt2tgprsquz.html

TS:   resp.ok;  resp.status
来源：http://dali.guannengcc.top/Article/details/gt2jgiikovw.html

Java: resp.statusCode()
来源：http://dali.jlsjyb.cn/Article/details/gt2pagheqxj.html

Go:   resp.StatusCode
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jceuygjp.html

Ruby: resp.code.to_i
来源：http://dali.gogol.net.cn/Article/details/gt2rrkwrvcu.html

C#:   (int)resp.StatusCode
来源：http://dali.shuidangran.top/Article/details/gt2xecgreus.html

[L08] 并发请求多个地址
来源：http://dali.fengsongda.top/Article/details/gt2ilhtfsyt.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yvedp.cn/Article/details/gt2omzehidm.html

PHP:  curl_multi_init() 系列
来源：http://dali.aibaodan.cn/Article/details/gt2akigrqcj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuxming.cn/Article/details/gt2ldpolqxc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sysykeji.top/Article/details/gt2ondhsgze.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.316326.xyz/Article/details/gt2zxsaamme.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.smart0.xyz/Article/details/gt2aohcxtqy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jqgufenzy.top/Article/details/gt2ujqtzqsc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jhdqiage.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2xbuueutx.html

M. 命令行 / 进程 / 环境
来源：http://dali.xziqi.cn/Article/details/gt2oitwonyp.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2fwiidmqt.html

[M01] 读取命令行参数
来源：http://dali.ivvv.top/Article/details/gt2usitvnjn.html

Py:   sys.argv[1:]
来源：http://dali.xinyue.icu/Article/details/gt2dswyulgl.html

PHP:  $argv;  $argc;
来源：http://dali.yueranfly.top/Article/details/gt2tbmxklse.html

JS:   process.argv.slice(2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mneufklm.html

TS:   process.argv.slice(2)
来源：http://dali.yongpay.top/Article/details/gt2gxplywqf.html

Java: args 数组（main 方法参数）
来源：http://dali.kuanghao11.cn/Article/details/gt2rarapqtn.html

Go:   os.Args[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hlsjmiav.html

Ruby: ARGV
来源：http://dali.daxiang520.top/Article/details/gt2zjzdjkfg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhoulong.xyz/Article/details/gt2ukcyfmjg.html

[M02] 读取环境变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2jjhqlbyr.html

Py:   os.environ.get("HOME")
来源：http://dali.cqqwz.cn/Article/details/gt2nvyjiehs.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.quarkkingdee.top/Article/details/gt2rbdymdmy.html

JS:   process.env.HOME
来源：http://dali.kuanghao11.cn/Article/details/gt2arjnvvof.html

TS:   process.env.HOME
来源：http://dali.nwbrower.top/Article/details/gt2hyfylhez.html

Java: System.getenv("HOME")
来源：http://dali.sufxvd.cn/Article/details/gt2qjsjdxvz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cashguo.top/Article/details/gt2fheezrii.html

Ruby: ENV["HOME"]
来源：http://dali.shzxlz.cn/Article/details/gt2fjwiftew.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tian-w.cn/Article/details/gt2rwjgnqcw.html

[M03] 执行外部命令
来源：http://dali.cdnleiting.top/Article/details/gt2aibzfhal.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cheryme.top/Article/details/gt2uonfrfbh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.9152youxi.cn/Article/details/gt2lsbrkwbg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangshuangyany.cn/Article/details/gt2xcerixww.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.dashuyun.cn/Article/details/gt2uoiludqj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.smart0.xyz/Article/details/gt2bwelgude.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qpynodmf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.guannengcc.top/Article/details/gt2mimkfemh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yvedp.cn/Article/details/gt2bqehksyl.html

[M04] 获取当前工作目录
来源：http://dali.jlsjyb.cn/Article/details/gt2pezbhocl.html

Py:   os.getcwd()
来源：http://dali.redwolf501.top/Article/details/gt2vybnfsmr.html

PHP:  getcwd();
来源：http://dali.gaohongyu789.top/Article/details/gt2ptqnkvku.html

JS:   process.cwd()
来源：http://dali.yj20258888.top/Article/details/gt2wyfnevea.html

TS:   process.cwd()
来源：http://dali.yanxiufei.cn/Article/details/gt2imxhlnot.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfrbleb.html

Go:   os.Getwd()
来源：http://dali.xylfe.cn/Article/details/gt2adzllhes.html

Ruby: Dir.pwd
来源：http://dali.cucudq.cn/Article/details/gt2fkuklnhd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.fzhhl.top/Article/details/gt2yaptztdn.html

[M05] 设置退出码
来源：http://dali.jqgfzy.top/Article/details/gt2miabewkt.html

Py:   sys.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2ypbsitcy.html

PHP:  exit(1);
来源：http://dali.chenzaomai.com/Article/details/gt2pjjwbphh.html

JS:   process.exit(1)
来源：http://dali.meibo888.top/Article/details/gt2dihirjdb.html

TS:   process.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2urnromdg.html

Java: System.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vmniqzml.html

Go:   os.Exit(1)
来源：http://dali.wangdashe.top/Article/details/gt2fsidwghf.html

Ruby: exit 1
来源：http://dali.cucudq.cn/Article/details/gt2oilbpbnx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.daria6918.cn/Article/details/gt2gkvqtgzx.html

[M06] 向标准错误输出
来源：http://dali.dianchejie.cn/Article/details/gt2jktclxtu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.dashuyun.cn/Article/details/gt2zufhpgqj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jianghu66.top/Article/details/gt2cwidaqpg.html

JS:   console.error("err")
来源：http://dali.xuanzx.com/Article/details/gt2lmmacbax.html

TS:   console.error("err")
来源：http://dali.yj20258888.top/Article/details/gt2dqufcsrr.html

Java: System.err.println("err")
来源：http://dali.yj202588.top/Article/details/gt2jjjkgfkt.html


<!-- 参考信息 -->