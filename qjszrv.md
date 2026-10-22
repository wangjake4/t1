代发 wailian999

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenjidiqi.icu/Article/details/gtrxjtwyyd.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xuetiantiany.cn/Article/details/gtfkemhfyg.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.svipenyu.cn/Article/details/gtasxjpcey.html

TS:   d.toISOString()
来源：http://dali.yuxming.cn/Article/details/gtzwoxxmgs.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.wangshuangyany.cn/Article/details/gtmxvgcuud.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shuidangran.top/Article/details/gtmxxqgtbk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cashguo.top/Article/details/gtalrdnmsj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.chenzaomai.com/Article/details/gtiuiahrya.html

[J03] 字符串解析为日期
来源：http://dali.fzhhl.top/Article/details/gtirdgduoj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gaohongyu789.top/Article/details/gtnfbjrvfm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.andypj.xyz/Article/details/gtxohpfaao.html

JS:   new Date("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gtkutlkngv.html

TS:   new Date("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtvxexrquk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gtmdstoxgo.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gthttnanre.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gtlpywrezs.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.svipenyu.cn/Article/details/gtsfttxtid.html

[J04] 时间戳与日期互转
来源：http://dali.gzhubu.top/Article/details/gtltvaslxy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gogol.net.cn/Article/details/gtcsbkidpx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.andypj.xyz/Article/details/gttihxmhpc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sweek.top/Article/details/gtlhtrmryk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yuxming.cn/Article/details/gthmdqwlgd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.haohaochexian.top/Article/details/gtxsnvxzob.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zdqjudy.top/Article/details/gtqifdthjo.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hnxiangtu.top/Article/details/gtmhujxfhg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gtjjpwmfpf.html

[J05] 时间加减（加 7 天）
来源：http://dali.ybcxt.top/Article/details/gthhukmnwt.html

Py:   now + timedelta(days=7)
来源：http://dali.feifeiyinyue.top/Article/details/gtalpzvrna.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.bjfxy.top/Article/details/gtvqjbidsw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangdashe.top/Article/details/gtyoqiqogd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yangfankeji.com/Article/details/gtlrxywooe.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.sxryk.cn/Article/details/gtzvixcywc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.9152youxi.cn/Article/details/gtgmcmfsin.html

Ruby: Time.now + 7 * 86400
来源：http://dali.smart0.xyz/Article/details/gtqvsxryks.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrzjoesyn.html

[J06] 计算两时间之差
来源：http://dali.daxiang520.top/Article/details/gtvqpskwkt.html

Py:   (end - start).total_seconds()
来源：http://dali.ppjwa.cn/Article/details/gtqokwmeld.html

PHP:  $end->diff($start)->days;
来源：http://dali.gaohongyu789.top/Article/details/gtgsplcgna.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.chenjidiqi.icu/Article/details/gthxfvankf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cqqwz.cn/Article/details/gtcqladyka.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sysykeji.top/Article/details/gtjiajvxae.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhijiandao.cn/Article/details/gtgsebqvew.html

Ruby: end - start                 # 返回秒数
来源：http://dali.meibo888.top/Article/details/gtoxkxthhb.html

C#:   (end - start).TotalSeconds
来源：http://dali.jyoumei.cn/Article/details/gtyrxupdad.html

[J07] 比较两个日期
来源：http://dali.andypj.xyz/Article/details/gttdgloigx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.pengpengdd.cyou/Article/details/gtrfaelyar.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xziqi.cn/Article/details/gtdlvnzajs.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigfzy.top/Article/details/gtsdnovswc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sysykeji.top/Article/details/gtgnxwrecj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gogol.net.cn/Article/details/gtlmfvirtl.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.chenzaomai.com/Article/details/gtggnbcxax.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gttcrpgnxy.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gtbfctmvsv.html

[J08] 提取年月日与星期
来源：http://dali.ydzc1.top/Article/details/gtkdmkpypg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yonumen.top/Article/details/gtnurhdule.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yongpay.top/Article/details/gtrhkjohfi.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.fengsongda.top/Article/details/gtiutpdjyz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.feifeiyinyue.top/Article/details/gtworlgjhg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhijiandao.cn/Article/details/gtvpsheqcy.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.vqdsnc.cn/Article/details/gtjczdgmpv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ppjwa.cn/Article/details/gtexjjqfsd.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ybcxt.top/Article/details/gttorfelig.html

[J09] 时区处理
来源：http://dali.hammf.cn/Article/details/gtgjkcgjut.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hnxiangtu.top/Article/details/gttshibwnd.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.daria6918.cn/Article/details/gtrzzrfeaw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhongyouzk.top/Article/details/gtjycbpszx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cheryme.top/Article/details/gtubfkgdfw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hywenlv.cn/Article/details/gtxgehbbqb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hammf.cn/Article/details/gtgpzovtlc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.daria6918.cn/Article/details/gtlbgzhngi.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cheryme.top/Article/details/gtvchebiev.html

[J10] 取今天 / 本月第一天
来源：http://dali.feifeiyinyue.top/Article/details/gtmxotiunw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.pengpengdd.cyou/Article/details/gttogadkcf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.vqdsnc.cn/Article/details/gtdzhjvfwl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtemshliac.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cdnleiting.top/Article/details/gtqfvvksvn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yuanzhike.top/Article/details/gtvhtdenum.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.guannengcc.top/Article/details/gtxlruehbm.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.smart0.xyz/Article/details/gtkvfqswcq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ivvv.top/Article/details/gtiwikozfg.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtbsncmzxl.html

K. JSON 与序列化
来源：http://dali.iojbl.cn/Article/details/gtffzogcsd.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtceefjizg.html

[K01] 对象转 JSON 字符串
来源：http://dali.ydzc1.top/Article/details/gtevcspqbt.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.havefunace.top/Article/details/gthznheyvu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xuetiantiany.cn/Article/details/gttgdltcio.html

JS:   JSON.stringify(obj)
来源：http://dali.cdnleiting.top/Article/details/gtwihaxhcx.html

TS:   JSON.stringify(obj)
来源：http://dali.cheryme.top/Article/details/gtwqkgwfzc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhongyouzk.top/Article/details/gtpxszjsmo.html

Go:   json.Marshal(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxodozafj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yanxiufei.cn/Article/details/gtldonufvd.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sxryk.cn/Article/details/gteefmzyiq.html

[K02] JSON 字符串转对象
来源：http://dali.hfpthk.cn/Article/details/gtfcatpovw.html

Py:   json.loads(s)
来源：http://dali.chenzaomai.com/Article/details/gtifkqpfmk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.9152youxi.cn/Article/details/gtwbvnoklb.html

JS:   JSON.parse(s)
来源：http://dali.ybcxt.top/Article/details/gtmplcckfi.html

TS:   JSON.parse(s)
来源：http://dali.jqgufenzy.top/Article/details/gtgfnavuzq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gtpvhlynze.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hnxiangtu.top/Article/details/gtnonbsbdt.html

Ruby: JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gtmemaqgfq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.tian-w.cn/Article/details/gtdopkoqah.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.quarkkingdee.top/Article/details/gtuthfduib.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shuidangran.top/Article/details/gtceqrilvx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.daxiang520.top/Article/details/gtzapsbiwy.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jiagoushi.top/Article/details/gtsopzzdjr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yvedp.cn/Article/details/gtpofhreoj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.mhx1999.top/Article/details/gtzusfbxvw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.birdmap.top/Article/details/gtyykvdoll.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yuanzhike.top/Article/details/gtejitxtdm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenzaomai.com/Article/details/gtdcppbvtj.html

[K04] 读取 JSON 文件
来源：http://dali.dianchejie.cn/Article/details/gtvkmazifq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yangfankeji.com/Article/details/gtflhbiqto.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shangyingyoupin.top/Article/details/gtxwarwosk.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tanke756.top/Article/details/gtbrhttapp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ehwqpu.com/Article/details/gtwxdlucqf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.redwolf501.top/Article/details/gtzqbapxhz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.guowangkeji.top/Article/details/gttxwwlcwb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.smart0.xyz/Article/details/gtkerluhju.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xziqi.cn/Article/details/gtmjzescze.html

[K05] 深拷贝对象
来源：http://dali.cashguo.top/Article/details/gtiqsydasu.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtboppkvku.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yuanzhike.top/Article/details/gtnomoopyn.html

JS:   structuredClone(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gthruknadq.html

TS:   structuredClone(obj)
来源：http://dali.mhx1999.top/Article/details/gtzxwcelzg.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hnqzz.top/Article/details/gtjfmyfqos.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yangfankeji.com/Article/details/gtsvnmprnq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nanxuanxn.top/Article/details/gtgmgfqemi.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ydzc1.top/Article/details/gtsydmopit.html

[K06] 解析 URL 查询串
来源：http://dali.tanke756.top/Article/details/gtbwrkjalp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cqqwz.cn/Article/details/gtukgsrdir.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrkmsuazl.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gogol.net.cn/Article/details/gtwyfpsiix.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nwbrower.top/Article/details/gtdteshxxc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hnqzz.top/Article/details/gtpuocpxgb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xinyue.icu/Article/details/gtqwpykmac.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.pengpengdd.cyou/Article/details/gtoobxkyvj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.bjfxy.top/Article/details/gtjpkzblxq.html

[K07] 进制转换
来源：http://dali.hongshengwenyu.top/Article/details/gtycedjcxk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtmohlsudu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjuplubwj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtivblqjwa.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gtsjtidduq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ivvv.top/Article/details/gtwwvoibiu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jqgfzy.top/Article/details/gtbrbkwquo.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.smart0.xyz/Article/details/gtnooswfgl.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ivvv.top/Article/details/gtddvsvrpn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jianghu66.top/Article/details/gthihdoxwk.html

Py:   pickle.dumps(obj)
来源：http://dali.xuanzx.com/Article/details/gtgmqntdsv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinqigufen.top/Article/details/gtisteffak.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.aizwys.cn/Article/details/gtdqxfbyxg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cheryme.top/Article/details/gtmnftqiho.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.svipenyu.cn/Article/details/gtombhcsso.html

Go:   encoding/gob
来源：http://dali.jiagoushi.top/Article/details/gtaylopdzv.html

Ruby: Marshal.dump(obj)
来源：http://dali.zycfv.cn/Article/details/gtzhlnbedp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhoulong.xyz/Article/details/gtvpuxvhla.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtqydcusls.html

L. 网络请求
来源：http://dali.0kj1m.cn/Article/details/gtrwqqcxtm.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtznololir.html

[L01] 发送 GET 请求
来源：http://dali.snrcjt.cn/Article/details/gthaeumund.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gotoacloud.top/Article/details/gtroifycpy.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.birdmap.top/Article/details/gtgpupklyx.html

JS:   await fetch(url)
来源：http://dali.316326.xyz/Article/details/gtmyvudvxp.html

TS:   await fetch(url)
来源：http://dali.ydzc1.top/Article/details/gttsgfurcz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.fengsongda.top/Article/details/gtpcbggops.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgwksusrn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.fzhhl.top/Article/details/gtcnthpasi.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.tianlin.xyz/Article/details/gtlctikyhj.html

[L02] 发送 POST JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gtrdzzwffr.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ivvv.top/Article/details/gtsuqmldkj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gtcnnmiscy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuxming.cn/Article/details/gtrgfgnuin.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhongyouzk.top/Article/details/gtiuvhstbp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gotoacloud.top/Article/details/gtnxixgvls.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hnqzz.top/Article/details/gtdluhwboo.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sufxvd.cn/Article/details/gtyakcmncp.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jqgufenzy.top/Article/details/gttnfuxkrt.html

[L03] 设置自定义请求头
来源：http://dali.gaohongyu789.top/Article/details/gtazqovljx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shanyushiyangtech.top/Article/details/gtkllvazbm.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.dashuyun.cn/Article/details/gtlgaymavi.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxinkj.top/Article/details/gtrkrsoksa.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.svipenyu.cn/Article/details/gtvtnxkywq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yuanzhike.top/Article/details/gtulfubbxa.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.aibaodan.cn/Article/details/gtkpatoiat.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuizmbfhb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.0kj1m.cn/Article/details/gtydsrxtnd.html

[L04] 设置超时
来源：http://dali.tian-w.cn/Article/details/gtindaulyq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.aizwys.cn/Article/details/gtbqontops.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.iojbl.cn/Article/details/gtifrqkdpg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cheryme.top/Article/details/gtwoyjmprv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.iojbl.cn/Article/details/gtfsipvykc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hnqzz.top/Article/details/gtbnpfpquh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.guannengcc.top/Article/details/gtsdffvloj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xuetiantiany.cn/Article/details/gttrxsyfft.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hywenlv.cn/Article/details/gtxnispzgp.html

[L05] 上传文件（multipart）
来源：http://dali.havefunace.top/Article/details/gtaydhakfw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sweek.top/Article/details/gtwfzdsjlj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtccfqfqbi.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gzhubu.top/Article/details/gtdwxninxm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.haohaochexian.top/Article/details/gtskqijrgv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jqgfzy.top/Article/details/gtlkqcaqap.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gzhubu.top/Article/details/gtjcsqzbus.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xinyue.icu/Article/details/gtyuwbnovy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtumfqosxj.html

[L06] 解析响应为 JSON
来源：http://dali.ydzc1.top/Article/details/gtbkgqcwmw.html

Py:   resp.json()
来源：http://dali.jinqigufen.top/Article/details/gtgdcyyxvo.html

PHP:  json_decode($body, true);
来源：http://dali.sufxvd.cn/Article/details/gtqqngbygs.html

JS:   await resp.json()
来源：http://dali.jinqigufen.top/Article/details/gtlmfnvmso.html

TS:   await resp.json()
来源：http://dali.hongshengwenyu.top/Article/details/gtslcmyfrx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gogol.net.cn/Article/details/gtdbwltzex.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yueranfly.top/Article/details/gtwifxxbiw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hnxiangtu.top/Article/details/gtlfjuyzob.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.chenjidiqi.icu/Article/details/gtyuidtmel.html

[L07] 处理 HTTP 状态码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmvmwbfix.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.316326.xyz/Article/details/gtmdslxhot.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nwbrower.top/Article/details/gtztzcpbuz.html

JS:   resp.ok;  resp.status
来源：http://dali.mhx1999.top/Article/details/gtjtorbjjq.html

TS:   resp.ok;  resp.status
来源：http://dali.wangdashe.top/Article/details/gtsltbfins.html

Java: resp.statusCode()
来源：http://dali.sxryk.cn/Article/details/gtvfbwooma.html

Go:   resp.StatusCode
来源：http://dali.jyoumei.cn/Article/details/gtjkqeepbw.html

Ruby: resp.code.to_i
来源：http://dali.cdnleiting.top/Article/details/gtcdryksco.html

C#:   (int)resp.StatusCode
来源：http://dali.cucudq.cn/Article/details/gtktyrizmj.html

[L08] 并发请求多个地址
来源：http://dali.jyoumei.cn/Article/details/gtixtubzxx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zycfv.cn/Article/details/gtswnddufe.html

PHP:  curl_multi_init() 系列
来源：http://dali.hnxiangtu.top/Article/details/gtxocxhtoz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.havefunace.top/Article/details/gtauxmswfg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cqqwz.cn/Article/details/gtgjtkzmom.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sxryk.cn/Article/details/gtxnbfcogc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.snrcjt.cn/Article/details/gtkkohfxng.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xuanzx.com/Article/details/gtusljklpk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jyoumei.cn/Article/details/gtfgdwopaq.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtdelmhyex.html

M. 命令行 / 进程 / 环境
来源：http://dali.cqqwz.cn/Article/details/gtikyodksd.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtwlqgnmwu.html

[M01] 读取命令行参数
来源：http://dali.gogol.net.cn/Article/details/gtykpggpgt.html

Py:   sys.argv[1:]
来源：http://dali.jqgfzy.top/Article/details/gtfmdhubmy.html

PHP:  $argv;  $argc;
来源：http://dali.meibo888.top/Article/details/gtgakgfpkg.html

JS:   process.argv.slice(2)
来源：http://dali.jinqigfzy.top/Article/details/gtkbjswrak.html

TS:   process.argv.slice(2)
来源：http://dali.wangdashe.top/Article/details/gtgtdckxan.html

Java: args 数组（main 方法参数）
来源：http://dali.jinqigufen.top/Article/details/gtrdqtoqrh.html

Go:   os.Args[1:]
来源：http://dali.daria6918.cn/Article/details/gtjyhpyfbq.html

Ruby: ARGV
来源：http://dali.hnqzz.top/Article/details/gtfprwpsxj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yongpay.top/Article/details/gteohvcqhe.html

[M02] 读取环境变量
来源：http://dali.dashuyun.cn/Article/details/gtgetkgfut.html

Py:   os.environ.get("HOME")
来源：http://dali.guowangkeji.top/Article/details/gtdlrobtwl.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tanke756.top/Article/details/gtrpuuegcx.html

JS:   process.env.HOME
来源：http://dali.nanxuanxn.top/Article/details/gtkeyngqbt.html

TS:   process.env.HOME
来源：http://dali.yangfankeji.com/Article/details/gthsgzisub.html

Java: System.getenv("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gthmjrfkby.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xinyue.icu/Article/details/gtcyaaogci.html

Ruby: ENV["HOME"]
来源：http://dali.zycfv.cn/Article/details/gtrullcoah.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gtqnduixde.html

[M03] 执行外部命令
来源：http://dali.xuanzx.com/Article/details/gtyxqqdkpt.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tian-w.cn/Article/details/gtqpnduysg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhengqikj.top/Article/details/gtipjmroda.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.birdmap.top/Article/details/gttfqosbdz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.fzhhl.top/Article/details/gtzcgpbawg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.0kj1m.cn/Article/details/gtvswzmkdj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nwbrower.top/Article/details/gttosrmcpw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.nanxinkj.top/Article/details/gtwubzozqf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yuanzhike.top/Article/details/gtzhitjuid.html

[M04] 获取当前工作目录
来源：http://dali.cheryme.top/Article/details/gtbewrchby.html

Py:   os.getcwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbbjxjmud.html

PHP:  getcwd();
来源：http://dali.hfpthk.cn/Article/details/gtarqidifn.html

JS:   process.cwd()
来源：http://dali.ppjwa.cn/Article/details/gtebcdsphb.html

TS:   process.cwd()
来源：http://dali.aibaodan.cn/Article/details/gtsaidputl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.0kj1m.cn/Article/details/gtxhwcezxm.html

Go:   os.Getwd()
来源：http://dali.daxiang520.top/Article/details/gtthgaihoj.html

Ruby: Dir.pwd
来源：http://dali.0kj1m.cn/Article/details/gttpsiduyk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yongpay.top/Article/details/gtinivyxsc.html

[M05] 设置退出码
来源：http://dali.hongshengwenyu.top/Article/details/gtkggjsldd.html

Py:   sys.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gteyncjwpj.html

PHP:  exit(1);
来源：http://dali.yanxiufei.cn/Article/details/gtoealhyfz.html

JS:   process.exit(1)
来源：http://dali.yj20258888.top/Article/details/gtktkigtgc.html

TS:   process.exit(1)
来源：http://dali.jianghu66.top/Article/details/gtvbgyntfd.html

Java: System.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gtpialccnn.html

Go:   os.Exit(1)
来源：http://dali.tian-w.cn/Article/details/gtggurhbtl.html

Ruby: exit 1
来源：http://dali.c1oappe.top/Article/details/gtoozjtvti.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.havefunace.top/Article/details/gtibnsnvrp.html

[M06] 向标准错误输出
来源：http://dali.gaohongyu789.top/Article/details/gtbxndvkbq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.dashuyun.cn/Article/details/gtfbchtzvt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.fengsongda.top/Article/details/gtkdzkknce.html

JS:   console.error("err")
来源：http://dali.ppjwa.cn/Article/details/gtgbbdugvp.html

TS:   console.error("err")
来源：http://dali.chenlongwang.top/Article/details/gtdrgdjaun.html

Java: System.err.println("err")
来源：http://dali.jqgufenzy.top/Article/details/gtodvnedcr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.mhx1999.top/Article/details/gtozwexblw.html

Ruby: warn "err"
来源：http://dali.guannengcc.top/Article/details/gtthjjyvcn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yanxiufei.cn/Article/details/gtfjunizcj.html

[M07] 判断是否为主入口
来源：http://dali.zhiwuduotai.top/Article/details/gtmdviecsn.html

Py:   if __name__ == "__main__":
来源：http://dali.aibaodan.cn/Article/details/gthscdcfdc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yj20258888.top/Article/details/gtlnzdjjhe.html

JS:   require.main === module
来源：http://dali.feifeiyinyue.top/Article/details/gtmwucpebs.html

TS:   require.main === module
来源：http://dali.redwolf501.top/Article/details/gtfbfvkevj.html

Java: public static void main(String[] args)
来源：http://dali.tanke756.top/Article/details/gtoxleygzr.html

Go:   func main()
来源：http://dali.havefunace.top/Article/details/gtvwnxeldi.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hfpthk.cn/Article/details/gtgctjxwvy.html

C#:   static void Main(string[] args)
来源：http://dali.hongshengwenyu.top/Article/details/gtgtaieiph.html

[M08] 获取系统与运行时信息
来源：http://dali.tianlin.xyz/Article/details/gtgwmampro.html

Py:   platform.system();  platform.python_version()
来源：http://dali.mhx1999.top/Article/details/gtrspbcrir.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gotoacloud.top/Article/details/gtjtefccbi.html

JS:   process.platform;  process.version
来源：http://dali.aizwys.cn/Article/details/gtaxlotcki.html


<!-- 参考信息 -->