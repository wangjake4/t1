代发 wailian999

Go:   time.Now()
来源：http://dali.xziqi.cn/Article/details/gt2iikeaush.html

Ruby: Time.now
来源：http://dali.zhongyouzk.top/Article/details/gt2icprmhfe.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.birdmap.top/Article/details/gt2utsccutm.html

[J02] 格式化输出
来源：http://dali.nanxinkj.top/Article/details/gt2mqoautat.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnqzz.top/Article/details/gt2aqctcdoc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.wangshuangyany.cn/Article/details/gt2ngjrlqgj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.pycfn.com/Article/details/gt2mjcyedzp.html

TS:   d.toISOString()
来源：http://dali.hammf.cn/Article/details/gt2tyxqqjjo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rnedzysy.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.daxiang520.top/Article/details/gt2rdykjbpp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.meibo888.top/Article/details/gt2zxvmsamg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.9152youxi.cn/Article/details/gt2ygkxjhof.html

[J03] 字符串解析为日期
来源：http://dali.svipenyu.cn/Article/details/gt2kgmsuxcs.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shangyingyoupin.top/Article/details/gt2khlvicrw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhongyouzk.top/Article/details/gt2czqezsql.html

JS:   new Date("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gt2vrbdnngl.html

TS:   new Date("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gt2xsynztov.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rtuhdxdc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gt2sfmwizum.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gt2kltkdiyu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinqigfzy.top/Article/details/gt2ydylwqud.html

[J04] 时间戳与日期互转
来源：http://dali.aizwys.cn/Article/details/gt2nseacabi.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hxifhxye.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj202588.top/Article/details/gt2raersvev.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.wangdashe.top/Article/details/gt2dlpgolpm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.svipenyu.cn/Article/details/gt2nellgcch.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shuidangran.top/Article/details/gt2hcqicqhw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.chenzaomai.com/Article/details/gt2wicoqslt.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yvedp.cn/Article/details/gt2nnevkoim.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hnqzz.top/Article/details/gt2cvxijpql.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhijiandao.cn/Article/details/gt2djisjqjp.html

Py:   now + timedelta(days=7)
来源：http://dali.hfpthk.cn/Article/details/gt2dzhgzcvh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.guowangkeji.top/Article/details/gt2caayhpgf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yangfankeji.com/Article/details/gt2bylzkrzw.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbzfske.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cdnleiting.top/Article/details/gt2mgmzkdey.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cheryme.top/Article/details/gt2ruthebxt.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj20258.top/Article/details/gt2kgsbhaza.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jyoumei.cn/Article/details/gt2flzykomk.html

[J06] 计算两时间之差
来源：http://dali.zdqjudy.top/Article/details/gt2bpevikum.html

Py:   (end - start).total_seconds()
来源：http://dali.cheryme.top/Article/details/gt2mbylxful.html

PHP:  $end->diff($start)->days;
来源：http://dali.xylfe.cn/Article/details/gt2ajoohuvu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj20258.top/Article/details/gt2pofznuro.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xuetiantiany.cn/Article/details/gt2nwynvvwi.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nanxuanxn.top/Article/details/gt2erxpwsrz.html

Go:   end.Sub(start).Hours()
来源：http://dali.bjfxy.top/Article/details/gt2vcjzumga.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xuetiantiany.cn/Article/details/gt2cvvzyisz.html

C#:   (end - start).TotalSeconds
来源：http://dali.jyoumei.cn/Article/details/gt2ogescikd.html

[J07] 比较两个日期
来源：http://dali.snrcjt.cn/Article/details/gt2knbaobgg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gt2xocryosl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nwbrower.top/Article/details/gt2yhxoebxq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hywenlv.cn/Article/details/gt2jqusnidj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.fzhhl.top/Article/details/gt2gdyvkftu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vprdgdqx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.chenlongwang.top/Article/details/gt2ugbspxmb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gt2pgquntnk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.snrcjt.cn/Article/details/gt2mcgllect.html

[J08] 提取年月日与星期
来源：http://dali.ivvv.top/Article/details/gt2ghkeocql.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhiwuduotai.top/Article/details/gt2tkclffam.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.fengsongda.top/Article/details/gt2zvylozim.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenzaomai.com/Article/details/gt2mifgsvvz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.c1oappe.top/Article/details/gt2exrirrpf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dpvntfub.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shzxlz.cn/Article/details/gt2vcpdiodd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tanke756.top/Article/details/gt2vlozazfx.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hongshengwenyu.top/Article/details/gt2xhdtfrnb.html

[J09] 时区处理
来源：http://dali.ybcxt.top/Article/details/gt2nxxjwtsg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jqgfzy.top/Article/details/gt2itvogdkj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhijiandao.cn/Article/details/gt2bliikkop.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjsynnc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxinkj.top/Article/details/gt2jaoqmcdv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gaohongyu789.top/Article/details/gt2abxwznhj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.redwolf501.top/Article/details/gt2htxtcgtl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.mhx1999.top/Article/details/gt2pgbdqbtn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shzxlz.cn/Article/details/gt2lhqsvywc.html

[J10] 取今天 / 本月第一天
来源：http://dali.yuanzhike.top/Article/details/gt2wbljlxmj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cashguo.top/Article/details/gt2zojqtvoy.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sweek.top/Article/details/gt2gmfcuxgw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.bjfxy.top/Article/details/gt2dmtunquh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhixingplan.top/Article/details/gt2cvrombkv.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj202588.top/Article/details/gt2tadqeaxr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.tianlin.xyz/Article/details/gt2vvvkjwrj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yangfankeji.com/Article/details/gt2hvfuutoz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shuidangran.top/Article/details/gt2vwahymgb.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2kfjfclhs.html

K. JSON 与序列化
来源：http://dali.aizwys.cn/Article/details/gt2pkprbiyc.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2xkdglbaq.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhixingplan.top/Article/details/gt2hoqrxkqh.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.9152youxi.cn/Article/details/gt2gdzmkqwg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.tianlin.xyz/Article/details/gt2ryxmhfdq.html

JS:   JSON.stringify(obj)
来源：http://dali.zycfv.cn/Article/details/gt2ozqudabl.html

TS:   JSON.stringify(obj)
来源：http://dali.yj20258888.top/Article/details/gt2svowyvkb.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yj202588.top/Article/details/gt2qaykqlmq.html

Go:   json.Marshal(obj)
来源：http://dali.cashguo.top/Article/details/gt2lvuufgcj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cashguo.top/Article/details/gt2czznjswm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yj202588.top/Article/details/gt2putqmaup.html

[K02] JSON 字符串转对象
来源：http://dali.sufxvd.cn/Article/details/gt2krvmzmug.html

Py:   json.loads(s)
来源：http://dali.shuidangran.top/Article/details/gt2xnsaxdpn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhiwuduotai.top/Article/details/gt2wvlrmdmi.html

JS:   JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gt2qyegeoev.html

TS:   JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gt2sullamji.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nwbrower.top/Article/details/gt2egiqviyv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.guowangkeji.top/Article/details/gt2buzxgpfa.html

Ruby: JSON.parse(s)
来源：http://dali.aibaodan.cn/Article/details/gt2xclikibj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cqqwz.cn/Article/details/gt2jpqxcnja.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shuidangran.top/Article/details/gt2lndzhdlw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.tianlin.xyz/Article/details/gt2vvsdtepo.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zdqjudy.top/Article/details/gt2ijyswylb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.guowangkeji.top/Article/details/gt2rkalgmnq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.pycfn.com/Article/details/gt2wlevykct.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2jpadpyfz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.tanke756.top/Article/details/gt2sixbdyzl.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.wangdashe.top/Article/details/gt2gnlpenqo.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhiwuduotai.top/Article/details/gt2pgvrkvug.html

[K04] 读取 JSON 文件
来源：http://dali.ybcxt.top/Article/details/gt2pfnjzjwj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.wangdashe.top/Article/details/gt2snevfdmq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ehwqpu.com/Article/details/gt2ysumkmem.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wjditcar.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tian-w.cn/Article/details/gt2vfnhsamt.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2paocsnmw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.9152youxi.cn/Article/details/gt2thngohdt.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yvedp.cn/Article/details/gt2yhvqmzfl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zycfv.cn/Article/details/gt2lvvahzpu.html

[K05] 深拷贝对象
来源：http://dali.birdmap.top/Article/details/gt2rslbmbxi.html

Py:   copy.deepcopy(obj)
来源：http://dali.andypj.xyz/Article/details/gt2xzqomgqv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gotoacloud.top/Article/details/gt2mvvjumyt.html

JS:   structuredClone(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2mtqkmizm.html

TS:   structuredClone(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2wysgnzxy.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.c1oappe.top/Article/details/gt2kxoblgst.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.chenlongwang.top/Article/details/gt2qzaurzyq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jianghu66.top/Article/details/gt2buhvskef.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jianghu66.top/Article/details/gt2tthanqrb.html

[K06] 解析 URL 查询串
来源：http://dali.zhengqikj.top/Article/details/gt2cmcpqdjm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shzxlz.cn/Article/details/gt2yvrycpht.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zdqjudy.top/Article/details/gt2hurebhme.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.meibo888.top/Article/details/gt2vtccfxoc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tian-w.cn/Article/details/gt2kuveneyz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jlsjyb.cn/Article/details/gt2etyilnhs.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hfpthk.cn/Article/details/gt2jplewunt.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gaohongyu789.top/Article/details/gt2qxkfbhjc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hnqzz.top/Article/details/gt2ccjzzrri.html

[K07] 进制转换
来源：http://dali.cheryme.top/Article/details/gt2jglhzozy.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gt2urcarjmo.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dbbnpgms.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gt2vkordzcw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gt2tvywepwl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gt2ydmnqnph.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhengqikj.top/Article/details/gt2esuhdirm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xinyue.icu/Article/details/gt2tknubzfj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gt2fthdkbea.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yvedp.cn/Article/details/gt2vztjemgt.html

Py:   pickle.dumps(obj)
来源：http://dali.yuxming.cn/Article/details/gt2kwhzjnzz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.mhx1999.top/Article/details/gt2jdegisaa.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jiagoushi.top/Article/details/gt2sxloqbyo.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hnqzz.top/Article/details/gt2ucuujmsq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.haohaochexian.top/Article/details/gt2bstrqvjq.html

Go:   encoding/gob
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pxuedsjb.html

Ruby: Marshal.dump(obj)
来源：http://dali.yonumen.top/Article/details/gt2wywtmdan.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jqgufenzy.top/Article/details/gt2eyrakjhn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxeikwj.html

L. 网络请求
来源：http://dali.nanxinkj.top/Article/details/gt2nyptqcyw.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2oupufoca.html

[L01] 发送 GET 请求
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uuiywacv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.aibaodan.cn/Article/details/gt2qsetqjki.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.chenjidiqi.icu/Article/details/gt2jfznwmdv.html

JS:   await fetch(url)
来源：http://dali.gotoacloud.top/Article/details/gt2ygyrbmen.html

TS:   await fetch(url)
来源：http://dali.wangdashe.top/Article/details/gt2xkqbkszc.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.guowangkeji.top/Article/details/gt2rhqucrfs.html

Go:   resp, err := http.Get(url)
来源：http://dali.gzhubu.top/Article/details/gt2egkanpzw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2turarsox.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ppjwa.cn/Article/details/gt2evtzlfzn.html

[L02] 发送 POST JSON
来源：http://dali.sxryk.cn/Article/details/gt2cpwzhult.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinqigufen.top/Article/details/gt2jgrsgoog.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xylfe.cn/Article/details/gt2voswkxxf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuxming.cn/Article/details/gt2qfajagor.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgufenzy.top/Article/details/gt2ftznwecp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.tian-w.cn/Article/details/gt2iyauzjxi.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jiagoushi.top/Article/details/gt2uxynffqb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.mhx1999.top/Article/details/gt2vthtkptu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ivvv.top/Article/details/gt2tookskwl.html

[L03] 设置自定义请求头
来源：http://dali.xinyue.icu/Article/details/gt2ttrpktqx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ivvv.top/Article/details/gt2mehtdqho.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hammf.cn/Article/details/gt2whbgpyzw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.meibo888.top/Article/details/gt2lwrruyxk.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxuanxn.top/Article/details/gt2nigdrrjb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cdnleiting.top/Article/details/gt2xkgdqbqv.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yangfankeji.com/Article/details/gt2rtqxckrk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.meibo888.top/Article/details/gt2qsobqwzk.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.guowangkeji.top/Article/details/gt2rtxtldrw.html

[L04] 设置超时
来源：http://dali.0kj1m.cn/Article/details/gt2tkcztzuf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.wangshuangyany.cn/Article/details/gt2snjyzkky.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhongyouzk.top/Article/details/gt2rgfedsfj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hongshengwenyu.top/Article/details/gt2qxfkbkkt.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pycfn.com/Article/details/gt2nuxhsfew.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.dashuyun.cn/Article/details/gt2yfdqwkbl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.tianlin.xyz/Article/details/gt2hhlwpclc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xinyue.icu/Article/details/gt2zqfrfqyx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.tian-w.cn/Article/details/gt2kbztkcwu.html

[L05] 上传文件（multipart）
来源：http://dali.guannengcc.top/Article/details/gt2cuhszwaw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cdnleiting.top/Article/details/gt2xyivbxuh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yuanzhike.top/Article/details/gt2curjwsae.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuetiantiany.cn/Article/details/gt2qblvnapp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xziqi.cn/Article/details/gt2qbfqbxnk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.tian-w.cn/Article/details/gt2jkkcslzg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinqigfzy.top/Article/details/gt2mqbnudfp.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hywenlv.cn/Article/details/gt2fstosrzc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gt2tehelwey.html

[L06] 解析响应为 JSON
来源：http://dali.ivvv.top/Article/details/gt2baxakvfc.html

Py:   resp.json()
来源：http://dali.yj20258.top/Article/details/gt2djjfckar.html

PHP:  json_decode($body, true);
来源：http://dali.316326.xyz/Article/details/gt2nczmnnfi.html

JS:   await resp.json()
来源：http://dali.bjfxy.top/Article/details/gt2herjjhhq.html

TS:   await resp.json()
来源：http://dali.xuanzx.com/Article/details/gt2ponkvsbs.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cqqwz.cn/Article/details/gt2irazusiy.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tmfugoby.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yonumen.top/Article/details/gt2ulsrhthe.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ehwqpu.com/Article/details/gt2gpfrdsho.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhixingplan.top/Article/details/gt2qxjnbdml.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cqqwz.cn/Article/details/gt2uucqqmhe.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.wangshuangyany.cn/Article/details/gt2wczupwvf.html

JS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oiiffdqu.html

TS:   resp.ok;  resp.status
来源：http://dali.kuanghao11.cn/Article/details/gt2hntgshgr.html

Java: resp.statusCode()
来源：http://dali.ehwqpu.com/Article/details/gt2kuqwcszo.html

Go:   resp.StatusCode
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bjiohjxf.html

Ruby: resp.code.to_i
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2voiztotn.html

C#:   (int)resp.StatusCode
来源：http://dali.xuetiantiany.cn/Article/details/gt2buwbrgnm.html

[L08] 并发请求多个地址
来源：http://dali.xinyue.icu/Article/details/gt2ajmchffn.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinqigufen.top/Article/details/gt2qmrftenh.html

PHP:  curl_multi_init() 系列
来源：http://dali.xinyue.icu/Article/details/gt2moejxdda.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.0kj1m.cn/Article/details/gt2dmyrwzqk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daxiang520.top/Article/details/gt2ymtacocn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.wangshuangyany.cn/Article/details/gt2codqgfbn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shuidangran.top/Article/details/gt2ltzkwbek.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2uehwucii.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jiagoushi.top/Article/details/gt2ryuqxxuv.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2qagkkwtj.html

M. 命令行 / 进程 / 环境
来源：http://dali.aizwys.cn/Article/details/gt2zkfdntxb.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2bmujqkkt.html

[M01] 读取命令行参数
来源：http://dali.cashguo.top/Article/details/gt2hkxcayxb.html

Py:   sys.argv[1:]
来源：http://dali.hysaishi.cn/Article/details/gt2mqrwvmwy.html

PHP:  $argv;  $argc;
来源：http://dali.andypj.xyz/Article/details/gt2rmlbfxnc.html

JS:   process.argv.slice(2)
来源：http://dali.gotoacloud.top/Article/details/gt2colwqhfn.html

TS:   process.argv.slice(2)
来源：http://dali.mhx1999.top/Article/details/gt2ycmuvady.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2jqcrrjob.html

Go:   os.Args[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gt2rcretose.html

Ruby: ARGV
来源：http://dali.hnqzz.top/Article/details/gt2pldlmxez.html

C#:   args 数组（Main 方法参数）
来源：http://dali.fengsongda.top/Article/details/gt2jbydebkt.html

[M02] 读取环境变量
来源：http://dali.mhx1999.top/Article/details/gt2fktvrwju.html

Py:   os.environ.get("HOME")
来源：http://dali.birdmap.top/Article/details/gt2kevuvzau.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.feifeiyinyue.top/Article/details/gt2lzbmlecx.html

JS:   process.env.HOME
来源：http://dali.hfpthk.cn/Article/details/gt2ehadwlwh.html

TS:   process.env.HOME
来源：http://dali.xziqi.cn/Article/details/gt2tpdneyxw.html

Java: System.getenv("HOME")
来源：http://dali.jianghu66.top/Article/details/gt2rarhokfe.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sysykeji.top/Article/details/gt2ypsvugxo.html

Ruby: ENV["HOME"]
来源：http://dali.feifeiyinyue.top/Article/details/gt2zwcnesve.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yonumen.top/Article/details/gt2nwhyxbek.html

[M03] 执行外部命令
来源：http://dali.pycfn.com/Article/details/gt2cmjmnadp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tanke756.top/Article/details/gt2tqmjhufp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yangfankeji.com/Article/details/gt2wovnhizr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.birdmap.top/Article/details/gt2byeyizeb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jyoumei.cn/Article/details/gt2nbwrncip.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zycfv.cn/Article/details/gt2rslogfuh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zycfv.cn/Article/details/gt2hduwvpcr.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gogol.net.cn/Article/details/gt2qarvrmkj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fqkklwuj.html

[M04] 获取当前工作目录
来源：http://dali.yonumen.top/Article/details/gt2sxusmohy.html

Py:   os.getcwd()
来源：http://dali.daxiang520.top/Article/details/gt2xuuanvas.html

PHP:  getcwd();
来源：http://dali.cqqwz.cn/Article/details/gt2nryfwyhf.html

JS:   process.cwd()
来源：http://dali.mhx1999.top/Article/details/gt2ibcjlhav.html

TS:   process.cwd()
来源：http://dali.shzxlz.cn/Article/details/gt2aqwhplvw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sweek.top/Article/details/gt2rfqdfdxh.html

Go:   os.Getwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2feqdjozs.html

Ruby: Dir.pwd
来源：http://dali.cashguo.top/Article/details/gt2btkfwctq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nebypyyf.html

[M05] 设置退出码
来源：http://dali.gogol.net.cn/Article/details/gt2srieyzrp.html

Py:   sys.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gt2qmfcwpjc.html

PHP:  exit(1);
来源：http://dali.yonumen.top/Article/details/gt2tfpdwsfx.html

JS:   process.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2iygugcgw.html

TS:   process.exit(1)
来源：http://dali.xinyue.icu/Article/details/gt2ekkglzhh.html

Java: System.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2vrstmpfm.html

Go:   os.Exit(1)
来源：http://dali.tianlin.xyz/Article/details/gt2kaihohkg.html

Ruby: exit 1
来源：http://dali.xuanzx.com/Article/details/gt2tzlebgpi.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cashguo.top/Article/details/gt2lehwtekv.html

[M06] 向标准错误输出
来源：http://dali.ivvv.top/Article/details/gt2ahekjjhu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yuxming.cn/Article/details/gt2vuisxlbt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yvedp.cn/Article/details/gt2tyxfaexm.html

JS:   console.error("err")
来源：http://dali.xuanzx.com/Article/details/gt2xvjxxwoi.html

TS:   console.error("err")
来源：http://dali.guannengcc.top/Article/details/gt2tjyxtoyz.html

Java: System.err.println("err")
来源：http://dali.aibaodan.cn/Article/details/gt2jxmpabgu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.c1oappe.top/Article/details/gt2alhhsxie.html

Ruby: warn "err"
来源：http://dali.sufxvd.cn/Article/details/gt2ukhaetwr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.kuanghao11.cn/Article/details/gt2jydywhho.html

[M07] 判断是否为主入口
来源：http://dali.daxiang520.top/Article/details/gt2mjagsyav.html

Py:   if __name__ == "__main__":
来源：http://dali.fengsongda.top/Article/details/gt2cdzfdins.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hysaishi.cn/Article/details/gt2dwuxuajg.html

JS:   require.main === module
来源：http://dali.jqgufenzy.top/Article/details/gt2xbqljhaz.html

TS:   require.main === module
来源：http://dali.hysaishi.cn/Article/details/gt2cbfnfkoj.html

Java: public static void main(String[] args)
来源：http://dali.nanxuanxn.top/Article/details/gt2vfwqgclx.html

Go:   func main()
来源：http://dali.svipenyu.cn/Article/details/gt2osgokhrd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhoulong.xyz/Article/details/gt2fvfmmmrv.html

C#:   static void Main(string[] args)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xejayuqm.html


<!-- 参考信息 -->