代发 wailian999

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aibaodan.cn/Article/details/gt2fttnbjyn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.birdmap.top/Article/details/gt2zswgfujd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhengqikj.top/Article/details/gt2npqksnsw.html

TS:   d.toISOString()
来源：http://dali.yj20258888.top/Article/details/gt2lqsweqzs.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ivvv.top/Article/details/gt2rpibrbjc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yongpay.top/Article/details/gt2vidlepyv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258.top/Article/details/gt2bshwdbvv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yanxiufei.cn/Article/details/gt2obdoazbq.html

[J03] 字符串解析为日期
来源：http://dali.ppjwa.cn/Article/details/gt2escrcjea.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.pycfn.com/Article/details/gt2vvwqtnqm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jlsjyb.cn/Article/details/gt2ofodunrr.html

JS:   new Date("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gt2rankdvhl.html

TS:   new Date("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gt2cqafieub.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gt2gblnbmmr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gt2vuhysogz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gt2nizvjdlc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.aibaodan.cn/Article/details/gt2dhocvqbd.html

[J04] 时间戳与日期互转
来源：http://dali.jinqigufen.top/Article/details/gt2xharanxc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.andypj.xyz/Article/details/gt2spjlilrm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nwbrower.top/Article/details/gt2nchhsymi.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ztynqhwn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.daria6918.cn/Article/details/gt2ygiuxhts.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.havefunace.top/Article/details/gt2brmhmfcd.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ivvv.top/Article/details/gt2zltzrxcf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yanxiufei.cn/Article/details/gt2tgcuxrll.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.fzhhl.top/Article/details/gt2vfzpphro.html

[J05] 时间加减（加 7 天）
来源：http://dali.tianlin.xyz/Article/details/gt2eezysiiw.html

Py:   now + timedelta(days=7)
来源：http://dali.nanxinkj.top/Article/details/gt2cvftelai.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jqgfzy.top/Article/details/gt2otcbyves.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ehwqpu.com/Article/details/gt2hvllehvm.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aibaodan.cn/Article/details/gt2rxmqdrty.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.redwolf501.top/Article/details/gt2xftjbdtw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yonumen.top/Article/details/gt2rmrdfgxc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.kuanghao11.cn/Article/details/gt2vvfajlvm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.mhx1999.top/Article/details/gt2gknshxdt.html

[J06] 计算两时间之差
来源：http://dali.sysykeji.top/Article/details/gt2djhhqjml.html

Py:   (end - start).total_seconds()
来源：http://dali.cqqwz.cn/Article/details/gt2bonjeotz.html

PHP:  $end->diff($start)->days;
来源：http://dali.gogol.net.cn/Article/details/gt2ohgrtsqc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.tian-w.cn/Article/details/gt2oqjkulsv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.9152youxi.cn/Article/details/gt2zwjapdhk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yuxming.cn/Article/details/gt2fgpjbynz.html

Go:   end.Sub(start).Hours()
来源：http://dali.yj202588.top/Article/details/gt2hzrlblvz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.feifeiyinyue.top/Article/details/gt2btfumtpk.html

C#:   (end - start).TotalSeconds
来源：http://dali.jqgfzy.top/Article/details/gt2uwhrkuga.html

[J07] 比较两个日期
来源：http://dali.birdmap.top/Article/details/gt2nnuznpcc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.quarkkingdee.top/Article/details/gt2qaoeinuc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nanxuanxn.top/Article/details/gt2sjfsbavj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xuetiantiany.cn/Article/details/gt2tptusyti.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhiwuduotai.top/Article/details/gt2zifosqnj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hnqzz.top/Article/details/gt2coehkhqr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qxkdztgy.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jiagoushi.top/Article/details/gt2ykvlgxcb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ehwqpu.com/Article/details/gt2wgyevoxf.html

[J08] 提取年月日与星期
来源：http://dali.jianghu66.top/Article/details/gt2zvhbxadl.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hongshengwenyu.top/Article/details/gt2esqmmreq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj202588.top/Article/details/gt2rfkqscga.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yangfankeji.com/Article/details/gt2ztlxtgci.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shuidangran.top/Article/details/gt2rixlqoll.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.redwolf501.top/Article/details/gt2tivmnwqe.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.tanke756.top/Article/details/gt2kufyljig.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jvwtzntn.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xziqi.cn/Article/details/gt2pkovvkqz.html

[J09] 时区处理
来源：http://dali.zhoulong.xyz/Article/details/gt2pmqlglsv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.daria6918.cn/Article/details/gt2isdkfofi.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.dashuyun.cn/Article/details/gt2kyxdbetz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tianlin.xyz/Article/details/gt2ytpnceyi.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuetiantiany.cn/Article/details/gt2yirrxsma.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.aizwys.cn/Article/details/gt2rxsesdod.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.svipenyu.cn/Article/details/gt2hvxcknbu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sysykeji.top/Article/details/gt2lkxsaith.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yvedp.cn/Article/details/gt2vwiabcpk.html

[J10] 取今天 / 本月第一天
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oghmrxys.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cheryme.top/Article/details/gt2muacevzf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gotoacloud.top/Article/details/gt2goceuusp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.chenzaomai.com/Article/details/gt2zhwrioay.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2cnqwzbet.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ldjevkmq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xziqi.cn/Article/details/gt2fbtepeha.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj20258.top/Article/details/gt2edhzumqs.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yangfankeji.com/Article/details/gt2yhhdssnp.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2fxioygjf.html

K. JSON 与序列化
来源：http://dali.wangshuangyany.cn/Article/details/gt2ymxreqms.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2mbdokblf.html

[K01] 对象转 JSON 字符串
来源：http://dali.cqqwz.cn/Article/details/gt2smxvqecl.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.andypj.xyz/Article/details/gt2cfgnzonj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.redwolf501.top/Article/details/gt2itpbxdqm.html

JS:   JSON.stringify(obj)
来源：http://dali.sweek.top/Article/details/gt2wytldori.html

TS:   JSON.stringify(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2qtirdsjp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hywenlv.cn/Article/details/gt2mywdddzp.html

Go:   json.Marshal(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2izmrtwxz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gaohongyu789.top/Article/details/gt2hggrcvdv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cucudq.cn/Article/details/gt2sslatrdh.html

[K02] JSON 字符串转对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jjlmfocv.html

Py:   json.loads(s)
来源：http://dali.cdnleiting.top/Article/details/gt2kkauyhkt.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ydzc1.top/Article/details/gt2pmphvvpi.html

JS:   JSON.parse(s)
来源：http://dali.wangdashe.top/Article/details/gt2rkuhoani.html

TS:   JSON.parse(s)
来源：http://dali.zhengqikj.top/Article/details/gt2rlqiloyn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gt2famaltfu.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aerbegnk.html

Ruby: JSON.parse(s)
来源：http://dali.nanxinkj.top/Article/details/gt2ryvxjgno.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.0kj1m.cn/Article/details/gt2dwptmdie.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jiagoushi.top/Article/details/gt2hxmcpvyg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jnpwxymm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.guowangkeji.top/Article/details/gt2lbgvrbqa.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2piczahdo.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuxming.cn/Article/details/gt2ewngjvqh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2vrgaunui.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.aibaodan.cn/Article/details/gt2nonakcjc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.daria6918.cn/Article/details/gt2krnqqsxs.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.fengsongda.top/Article/details/gt2wthsueqr.html

[K04] 读取 JSON 文件
来源：http://dali.mhx1999.top/Article/details/gt2mizpudnl.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.fengsongda.top/Article/details/gt2denjfffe.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2flzguivk.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jlsjyb.cn/Article/details/gt2zatwxqcp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nmyxeatb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.redwolf501.top/Article/details/gt2xoywfhvs.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jqgufenzy.top/Article/details/gt2uvaugkgk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xinyue.icu/Article/details/gt2qhgejwjn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.c1oappe.top/Article/details/gt2dicbtbhe.html

[K05] 深拷贝对象
来源：http://dali.hnxiangtu.top/Article/details/gt2njbeecjv.html

Py:   copy.deepcopy(obj)
来源：http://dali.jianghu66.top/Article/details/gt2gjafxwad.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gaohongyu789.top/Article/details/gt2keaqmrpb.html

JS:   structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gt2rwsyapaq.html

TS:   structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gt2akmwjnzv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinqigfzy.top/Article/details/gt2ituixiea.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mkpjzrix.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.kuanghao11.cn/Article/details/gt2myqnclhd.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.mhx1999.top/Article/details/gt2dvcbdslx.html

[K06] 解析 URL 查询串
来源：http://dali.jinqigufen.top/Article/details/gt2lfqonned.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.redwolf501.top/Article/details/gt2sisbqroh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.andypj.xyz/Article/details/gt2mtyxctzd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hfpthk.cn/Article/details/gt2sixyosie.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.mhx1999.top/Article/details/gt2avqfgayq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cashguo.top/Article/details/gt2gfzudetf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.mhx1999.top/Article/details/gt2sljuyqoe.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wonenrdf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gt2juholbrt.html

[K07] 进制转换
来源：http://dali.yuanzhike.top/Article/details/gt2hsqsnnis.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gt2mxxrbdzg.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yonumen.top/Article/details/gt2bmyblesa.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gt2jaxkjmrw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gt2kehzmenl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gt2ecfjegns.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.aizwys.cn/Article/details/gt2wytxkaxf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.dashuyun.cn/Article/details/gt2agowpsjv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gt2cgyemhfn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhiwuduotai.top/Article/details/gt2wnelbqfg.html

Py:   pickle.dumps(obj)
来源：http://dali.fengsongda.top/Article/details/gt2jctbuehw.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jlsjyb.cn/Article/details/gt2uvnctpoa.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.haohaochexian.top/Article/details/gt2exxbvlvf.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ypmtlehq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hywenlv.cn/Article/details/gt2fepgkpyb.html

Go:   encoding/gob
来源：http://dali.mhx1999.top/Article/details/gt2devgyojq.html

Ruby: Marshal.dump(obj)
来源：http://dali.yueranfly.top/Article/details/gt2azvsbmgw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hammf.cn/Article/details/gt2bmgupbrh.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2trmlcqbl.html

L. 网络请求
来源：http://dali.iojbl.cn/Article/details/gt2huizcuhi.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2yhhibuou.html

[L01] 发送 GET 请求
来源：http://dali.snrcjt.cn/Article/details/gt2xrihltda.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhongyouzk.top/Article/details/gt2onxpfahg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nwbrower.top/Article/details/gt2ehabsstg.html

JS:   await fetch(url)
来源：http://dali.ydzc1.top/Article/details/gt2fcljnshv.html

TS:   await fetch(url)
来源：http://dali.cqqwz.cn/Article/details/gt2wjqttaqq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yj20258888.top/Article/details/gt2qwptonmr.html

Go:   resp, err := http.Get(url)
来源：http://dali.sweek.top/Article/details/gt2jxwdwnlo.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhoulong.xyz/Article/details/gt2eccuxzwi.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.tianlin.xyz/Article/details/gt2gpzskilp.html

[L02] 发送 POST JSON
来源：http://dali.c1oappe.top/Article/details/gt2czkjcjic.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hammf.cn/Article/details/gt2wnulysnh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dndgcqek.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuanzx.com/Article/details/gt2luavqlra.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.redwolf501.top/Article/details/gt2ljzhoqdc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jyoumei.cn/Article/details/gt2zvypxsrq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ppjwa.cn/Article/details/gt2vdgppzdu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhiwuduotai.top/Article/details/gt2iqbonuqu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yonumen.top/Article/details/gt2cmglacta.html

[L03] 设置自定义请求头
来源：http://dali.sweek.top/Article/details/gt2kxzgfpoz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zfttmcig.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xuanzx.com/Article/details/gt2ceilxydw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuanzx.com/Article/details/gt2pbrwukmp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2guzimoxj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jqgfzy.top/Article/details/gt2kyyberas.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.tian-w.cn/Article/details/gt2aofohfyw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ehwqpu.com/Article/details/gt2uttmlasd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.aibaodan.cn/Article/details/gt2kbgqszse.html

[L04] 设置超时
来源：http://dali.316326.xyz/Article/details/gt2ihofsdek.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhixingplan.top/Article/details/gt2mpnfqzdv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shuidangran.top/Article/details/gt2kfjrlvck.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yonumen.top/Article/details/gt2ldvnsajo.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cqqwz.cn/Article/details/gt2gtmxuija.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.0kj1m.cn/Article/details/gt2ghopbfjw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yuxming.cn/Article/details/gt2rbwqsudq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nanxuanxn.top/Article/details/gt2nwjwljnx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hywenlv.cn/Article/details/gt2gvelswkr.html

[L05] 上传文件（multipart）
来源：http://dali.nwbrower.top/Article/details/gt2cbqakxal.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jfvqybla.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yueranfly.top/Article/details/gt2sfvuarpn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.iojbl.cn/Article/details/gt2ecxplvks.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shuidangran.top/Article/details/gt2gozldtlq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhixingplan.top/Article/details/gt2nhevythw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hysaishi.cn/Article/details/gt2nzumllez.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yangfankeji.com/Article/details/gt2hiccvvtc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yj202588.top/Article/details/gt2shvdfgkc.html

[L06] 解析响应为 JSON
来源：http://dali.c1oappe.top/Article/details/gt2shajwakc.html

Py:   resp.json()
来源：http://dali.yueranfly.top/Article/details/gt2wuigxjiv.html

PHP:  json_decode($body, true);
来源：http://dali.jiagoushi.top/Article/details/gt2eclmjwww.html

JS:   await resp.json()
来源：http://dali.dianchejie.cn/Article/details/gt2jbyaltnc.html

TS:   await resp.json()
来源：http://dali.ybcxt.top/Article/details/gt2tekgwoij.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ppjwa.cn/Article/details/gt2mjqxhtue.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinqigufen.top/Article/details/gt2jftrpjph.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2scjzghna.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jqgfzy.top/Article/details/gt2hqqlpuwp.html

[L07] 处理 HTTP 状态码
来源：http://dali.dianchejie.cn/Article/details/gt2wnnquenq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nwbrower.top/Article/details/gt2wklpomsz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gzhubu.top/Article/details/gt2gdwcalda.html

JS:   resp.ok;  resp.status
来源：http://dali.316326.xyz/Article/details/gt2edevhdju.html

TS:   resp.ok;  resp.status
来源：http://dali.vqdsnc.cn/Article/details/gt2vulzoaqj.html

Java: resp.statusCode()
来源：http://dali.ivvv.top/Article/details/gt2ruzazcsg.html

Go:   resp.StatusCode
来源：http://dali.snrcjt.cn/Article/details/gt2moncuowb.html

Ruby: resp.code.to_i
来源：http://dali.zycfv.cn/Article/details/gt2fraickrt.html

C#:   (int)resp.StatusCode
来源：http://dali.fzhhl.top/Article/details/gt2kmblrftm.html

[L08] 并发请求多个地址
来源：http://dali.gzhubu.top/Article/details/gt2vvehbrfp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cucudq.cn/Article/details/gt2vmfifbli.html

PHP:  curl_multi_init() 系列
来源：http://dali.hywenlv.cn/Article/details/gt2bosnbirc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daria6918.cn/Article/details/gt2ulxyziwf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zdqjudy.top/Article/details/gt2hotuvfqn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.snrcjt.cn/Article/details/gt2gysvcjdj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hysaishi.cn/Article/details/gt2esaopyrt.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.nwbrower.top/Article/details/gt2wadckctx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hnqzz.top/Article/details/gt2axmtrcpt.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2cxcrwmqk.html

M. 命令行 / 进程 / 环境
来源：http://dali.cqqwz.cn/Article/details/gt2lvzfevwz.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2tbaljssq.html

[M01] 读取命令行参数
来源：http://dali.guannengcc.top/Article/details/gt2ggkkfjav.html

Py:   sys.argv[1:]
来源：http://dali.fengsongda.top/Article/details/gt2qnmmfwqt.html

PHP:  $argv;  $argc;
来源：http://dali.iojbl.cn/Article/details/gt2vljmucyq.html

JS:   process.argv.slice(2)
来源：http://dali.jqgufenzy.top/Article/details/gt2eptfaofr.html

TS:   process.argv.slice(2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2auvoacfg.html

Java: args 数组（main 方法参数）
来源：http://dali.tanke756.top/Article/details/gt2ryiuebwn.html

Go:   os.Args[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gt2twcmwndd.html

Ruby: ARGV
来源：http://dali.hongshengwenyu.top/Article/details/gt2asafutek.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj20258888.top/Article/details/gt2hpkgxhxd.html

[M02] 读取环境变量
来源：http://dali.svipenyu.cn/Article/details/gt2sihzdhop.html

Py:   os.environ.get("HOME")
来源：http://dali.dianchejie.cn/Article/details/gt2zrbmdwgb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yongpay.top/Article/details/gt2mnipfxhh.html

JS:   process.env.HOME
来源：http://dali.dashuyun.cn/Article/details/gt2kafcjayj.html

TS:   process.env.HOME
来源：http://dali.fzhhl.top/Article/details/gt2qfngojkj.html

Java: System.getenv("HOME")
来源：http://dali.meibo888.top/Article/details/gt2vvapacck.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gt2iprzoaab.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2uisxfqig.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cdnleiting.top/Article/details/gt2djsvgnlh.html

[M03] 执行外部命令
来源：http://dali.yangfankeji.com/Article/details/gt2rvftehxw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sufxvd.cn/Article/details/gt2zhxshqhf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.guowangkeji.top/Article/details/gt2uqewzmoe.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tianlin.xyz/Article/details/gt2nkdscpdq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.havefunace.top/Article/details/gt2qguwenni.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yuxming.cn/Article/details/gt2exumxwdb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sweek.top/Article/details/gt2hqqutzku.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.mhx1999.top/Article/details/gt2xszpgcfk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yonumen.top/Article/details/gt2xinnwpcp.html

[M04] 获取当前工作目录
来源：http://dali.xinyue.icu/Article/details/gt2hrclqqvr.html

Py:   os.getcwd()
来源：http://dali.shuidangran.top/Article/details/gt2qctdvrdg.html

PHP:  getcwd();
来源：http://dali.kuanghao11.cn/Article/details/gt2uiqzfvjx.html

JS:   process.cwd()
来源：http://dali.yanxiufei.cn/Article/details/gt2qsegwxmd.html

TS:   process.cwd()
来源：http://dali.iojbl.cn/Article/details/gt2nuspwxix.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.aibaodan.cn/Article/details/gt2qsndagag.html

Go:   os.Getwd()
来源：http://dali.jlsjyb.cn/Article/details/gt2yhdqlopc.html

Ruby: Dir.pwd
来源：http://dali.ydzc1.top/Article/details/gt2ywffxowl.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinqigufen.top/Article/details/gt2jweuhpnp.html

[M05] 设置退出码
来源：http://dali.hnxiangtu.top/Article/details/gt2fkvbsxky.html

Py:   sys.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kblwqzdm.html

PHP:  exit(1);
来源：http://dali.smart0.xyz/Article/details/gt2jptzxtfr.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnkgcqwz.html

TS:   process.exit(1)
来源：http://dali.fengsongda.top/Article/details/gt2axnfpohs.html

Java: System.exit(1)
来源：http://dali.daxiang520.top/Article/details/gt2njralgee.html

Go:   os.Exit(1)
来源：http://dali.guowangkeji.top/Article/details/gt2iuhzqkgn.html

Ruby: exit 1
来源：http://dali.yj20258.top/Article/details/gt2tpytdowy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinqigufen.top/Article/details/gt2zbzwwvth.html

[M06] 向标准错误输出
来源：http://dali.fengsongda.top/Article/details/gt2cjryozhi.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhongyouzk.top/Article/details/gt2wmkluvlb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.guowangkeji.top/Article/details/gt2yvphzqdq.html

JS:   console.error("err")
来源：http://dali.hongshengwenyu.top/Article/details/gt2pkylufnr.html

TS:   console.error("err")
来源：http://dali.hnqzz.top/Article/details/gt2fdlfsccc.html

Java: System.err.println("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2puwptrjf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.svipenyu.cn/Article/details/gt2xsdmwbdo.html

Ruby: warn "err"
来源：http://dali.xinyue.icu/Article/details/gt2jtppljxx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hnqzz.top/Article/details/gt2olksxmme.html

[M07] 判断是否为主入口
来源：http://dali.aibaodan.cn/Article/details/gt2qjsuqkci.html

Py:   if __name__ == "__main__":
来源：http://dali.sysykeji.top/Article/details/gt2gcshahed.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ivvv.top/Article/details/gt2chbfozlp.html

JS:   require.main === module
来源：http://dali.snrcjt.cn/Article/details/gt2ioyuwtcg.html

TS:   require.main === module
来源：http://dali.chenjidiqi.icu/Article/details/gt2dlvgtpxl.html

Java: public static void main(String[] args)
来源：http://dali.ivvv.top/Article/details/gt2nnflfknq.html

Go:   func main()
来源：http://dali.cucudq.cn/Article/details/gt2mmzbtmao.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhixingplan.top/Article/details/gt2gobfdywo.html

C#:   static void Main(string[] args)
来源：http://dali.ydzc1.top/Article/details/gt2ubpbadjk.html

[M08] 获取系统与运行时信息
来源：http://dali.hongshengwenyu.top/Article/details/gt2nnfkizop.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinqigufen.top/Article/details/gt2abhecdnz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jlsjyb.cn/Article/details/gt2zxtoxapq.html

JS:   process.platform;  process.version
来源：http://dali.dashuyun.cn/Article/details/gt2taxfithy.html


<!-- 参考信息 -->