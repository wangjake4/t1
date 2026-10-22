代发 wailian999

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhiwuduotai.top/Article/details/gt2whysjbgm.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.316326.xyz/Article/details/gt2ppgwewla.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cheryme.top/Article/details/gt2uoeiwora.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yj20258.top/Article/details/gt2vpnnumbr.html

[J03] 字符串解析为日期
来源：http://dali.shzxlz.cn/Article/details/gt2uisntxqx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhixingplan.top/Article/details/gt2tiilntfk.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.dashuyun.cn/Article/details/gt2flsrkguq.html

JS:   new Date("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gt2vfgfhpso.html

TS:   new Date("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gt2seywgvda.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gt2lwjbyynk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rfuonepp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gt2feonagcw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ppjwa.cn/Article/details/gt2ytiskpwd.html

[J04] 时间戳与日期互转
来源：http://dali.meibo888.top/Article/details/gt2qdtzuyam.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ppjwa.cn/Article/details/gt2zbnjeodr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hywenlv.cn/Article/details/gt2hpcrktmm.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.tian-w.cn/Article/details/gt2upugpddm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gogol.net.cn/Article/details/gt2infyoinz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cvdgnoiz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jqgfzy.top/Article/details/gt2rmqajvwz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jianghu66.top/Article/details/gt2uhjiuuxb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jiagoushi.top/Article/details/gt2xdmounax.html

[J05] 时间加减（加 7 天）
来源：http://dali.hnxiangtu.top/Article/details/gt2pznfvdzw.html

Py:   now + timedelta(days=7)
来源：http://dali.yangfankeji.com/Article/details/gt2hulcgfzs.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.aibaodan.cn/Article/details/gt2ldyabjkl.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2avbuuhxl.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cashguo.top/Article/details/gt2gdkgvipo.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhixingplan.top/Article/details/gt2izbntped.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.iojbl.cn/Article/details/gt2ycoycjnb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj202588.top/Article/details/gt2kxwicmmt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jianghu66.top/Article/details/gt2sugcmurq.html

[J06] 计算两时间之差
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pywvtjmy.html

Py:   (end - start).total_seconds()
来源：http://dali.chenjidiqi.icu/Article/details/gt2lrtcxagg.html

PHP:  $end->diff($start)->days;
来源：http://dali.ivvv.top/Article/details/gt2igjeszaa.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yongpay.top/Article/details/gt2kjflkwvh.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj202588.top/Article/details/gt2operjhay.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ivvv.top/Article/details/gt2lupzbcph.html

Go:   end.Sub(start).Hours()
来源：http://dali.fzhhl.top/Article/details/gt2nhltsieo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhengqikj.top/Article/details/gt2pjwbtzgw.html

C#:   (end - start).TotalSeconds
来源：http://dali.cqqwz.cn/Article/details/gt2ouebmnoz.html

[J07] 比较两个日期
来源：http://dali.yanxiufei.cn/Article/details/gt2fhppjuhu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yuanzhike.top/Article/details/gt2rpwsglxt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.pycfn.com/Article/details/gt2qygnqsla.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nwbrower.top/Article/details/gt2oxgmpwqb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hammf.cn/Article/details/gt2jvkkqeul.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.iojbl.cn/Article/details/gt2ocyphvfk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2yeckaqoh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.aibaodan.cn/Article/details/gt2tuhxqivz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gt2czvedqzh.html

[J08] 提取年月日与星期
来源：http://dali.chenjidiqi.icu/Article/details/gt2rgufneng.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zycfv.cn/Article/details/gt2unrnhaxt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.dashuyun.cn/Article/details/gt2hvnuhknf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.snrcjt.cn/Article/details/gt2mfhffeko.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tianlin.xyz/Article/details/gt2dilcvdnf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xinyue.icu/Article/details/gt2rvyhvvhs.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yanxiufei.cn/Article/details/gt2rthpzuaw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.bjfxy.top/Article/details/gt2ysbitpxx.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yvedp.cn/Article/details/gt2psooonaj.html

[J09] 时区处理
来源：http://dali.shzxlz.cn/Article/details/gt2xaqttlbq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zdqjudy.top/Article/details/gt2reajnviv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bitqfcpj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhengqikj.top/Article/details/gt2ujzyxctv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guowangkeji.top/Article/details/gt2rownvrkd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.pycfn.com/Article/details/gt2nxeteklt.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gogol.net.cn/Article/details/gt2ktabdvef.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.pycfn.com/Article/details/gt2jxrdcvie.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.iojbl.cn/Article/details/gt2gnzpirmp.html

[J10] 取今天 / 本月第一天
来源：http://dali.havefunace.top/Article/details/gt2omcaqlip.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.birdmap.top/Article/details/gt2rfcysnnv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.mhx1999.top/Article/details/gt2iusfljxk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2odkdylyi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.tanke756.top/Article/details/gt2oaroedyc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sufxvd.cn/Article/details/gt2hqkxfxze.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.feifeiyinyue.top/Article/details/gt2njdmvcqf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.guowangkeji.top/Article/details/gt2ljdsakmb.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.316326.xyz/Article/details/gt2jvqdjgwz.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2nizfzynw.html

K. JSON 与序列化
来源：http://dali.wangshuangyany.cn/Article/details/gt2saunipni.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2zpfatmet.html

[K01] 对象转 JSON 字符串
来源：http://dali.aibaodan.cn/Article/details/gt2zcxkuool.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xuanzx.com/Article/details/gt2dfsfbjbq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.redwolf501.top/Article/details/gt2oovrasrm.html

JS:   JSON.stringify(obj)
来源：http://dali.yuxming.cn/Article/details/gt2jzpirpcy.html

TS:   JSON.stringify(obj)
来源：http://dali.hammf.cn/Article/details/gt2nekzmoso.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinqigufen.top/Article/details/gt2xytfqqjl.html

Go:   json.Marshal(obj)
来源：http://dali.zycfv.cn/Article/details/gt2anfaargy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qujjmstu.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yj202588.top/Article/details/gt2bgvbftwu.html

[K02] JSON 字符串转对象
来源：http://dali.cheryme.top/Article/details/gt2rbdxjsvk.html

Py:   json.loads(s)
来源：http://dali.yj202588.top/Article/details/gt2wcbwiigu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hnxiangtu.top/Article/details/gt2nolkbfjq.html

JS:   JSON.parse(s)
来源：http://dali.jqgfzy.top/Article/details/gt2qepobwpg.html

TS:   JSON.parse(s)
来源：http://dali.zhixingplan.top/Article/details/gt2bpfsyfus.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.guannengcc.top/Article/details/gt2xwvkwzwj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kmoftrbf.html

Ruby: JSON.parse(s)
来源：http://dali.dashuyun.cn/Article/details/gt2sflnfejz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yj20258.top/Article/details/gt2vebikypa.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sweek.top/Article/details/gt2pqdxubuv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hnxiangtu.top/Article/details/gt2tdxtkinr.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zujnpxqn.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gzhubu.top/Article/details/gt2jacthdtx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.9152youxi.cn/Article/details/gt2yoxqwogr.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2dcxjikbf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.aizwys.cn/Article/details/gt2bmgrlpld.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.bjfxy.top/Article/details/gt2ibwoelga.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.snrcjt.cn/Article/details/gt2kthmlqlh.html

[K04] 读取 JSON 文件
来源：http://dali.zhixingplan.top/Article/details/gt2jmhrhvak.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yangfankeji.com/Article/details/gt2mupovtrp.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.iojbl.cn/Article/details/gt2bqfwwlpm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yanxiufei.cn/Article/details/gt2dlspshqi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2xcjbfbbb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.smart0.xyz/Article/details/gt2usrekrao.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtdnlnx.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yuanzhike.top/Article/details/gt2hlkrsaus.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hywenlv.cn/Article/details/gt2cjqbueac.html

[K05] 深拷贝对象
来源：http://dali.hnqzz.top/Article/details/gt2hyvutwyd.html

Py:   copy.deepcopy(obj)
来源：http://dali.havefunace.top/Article/details/gt2vrledpdh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cucudq.cn/Article/details/gt2mlrinsjb.html

JS:   structuredClone(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mynzoodg.html

TS:   structuredClone(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2zmrlktyp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.smart0.xyz/Article/details/gt2kybjmcwo.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinqigfzy.top/Article/details/gt2vxdigddk.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.daxiang520.top/Article/details/gt2niajkzlb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hongshengwenyu.top/Article/details/gt2tarztnjv.html

[K06] 解析 URL 查询串
来源：http://dali.zhongyouzk.top/Article/details/gt2hylpyumk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cucudq.cn/Article/details/gt2jhczackc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.snrcjt.cn/Article/details/gt2shxvbank.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258.top/Article/details/gt2kytshxug.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnqzz.top/Article/details/gt2calkkofg.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.iojbl.cn/Article/details/gt2ssamwyst.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.iojbl.cn/Article/details/gt2sadsvmwy.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2mknujtvw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gt2vzodbmvx.html

[K07] 进制转换
来源：http://dali.shzxlz.cn/Article/details/gt2ubcxhgjo.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2juqupabu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.chenzaomai.com/Article/details/gt2ldxakokk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gt2jwmexpjh.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gt2itdrzikj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2gfybjreb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhoulong.xyz/Article/details/gt2bvlzqyeb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hammf.cn/Article/details/gt2rjoeruvi.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gt2rhfhqtam.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zdqjudy.top/Article/details/gt2yslmzyib.html

Py:   pickle.dumps(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2kruxjoqr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cucudq.cn/Article/details/gt2regbkwcf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.tanke756.top/Article/details/gt2mkfwmcmt.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jqgufenzy.top/Article/details/gt2opzkaqxy.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hywenlv.cn/Article/details/gt2phyytwhm.html

Go:   encoding/gob
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ukuyrzwa.html

Ruby: Marshal.dump(obj)
来源：http://dali.ivvv.top/Article/details/gt2kiglptzl.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yanxiufei.cn/Article/details/gt2ouzavjyv.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2ptcgfozy.html

L. 网络请求
来源：http://dali.cqqwz.cn/Article/details/gt2oeyymygg.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2mdnpfemh.html

[L01] 发送 GET 请求
来源：http://dali.yj202588.top/Article/details/gt2sojnpkmb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.vqdsnc.cn/Article/details/gt2zoszeggp.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cypuusaf.html

JS:   await fetch(url)
来源：http://dali.dashuyun.cn/Article/details/gt2mrtfldzm.html

TS:   await fetch(url)
来源：http://dali.dianchejie.cn/Article/details/gt2ytlftqcd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shzxlz.cn/Article/details/gt2xjqteezq.html

Go:   resp, err := http.Get(url)
来源：http://dali.tian-w.cn/Article/details/gt2lduljrts.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.guowangkeji.top/Article/details/gt2ctjxjand.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.0kj1m.cn/Article/details/gt2olyhftux.html

[L02] 发送 POST JSON
来源：http://dali.dianchejie.cn/Article/details/gt2hukjyvhv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jiagoushi.top/Article/details/gt2xklnbrkz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hywenlv.cn/Article/details/gt2ffcguarl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cashguo.top/Article/details/gt2krrzuaag.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.c1oappe.top/Article/details/gt2syfcxrhz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xuetiantiany.cn/Article/details/gt2abbekeup.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yangfankeji.com/Article/details/gt2mbjrsdcv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shangyingyoupin.top/Article/details/gt2tssphypw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xuetiantiany.cn/Article/details/gt2dxoyruxk.html

[L03] 设置自定义请求头
来源：http://dali.jlsjyb.cn/Article/details/gt2ddlbtguh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwhcwtg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.quarkkingdee.top/Article/details/gt2tbfbkbrl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ivvv.top/Article/details/gt2sdgctkdq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuanzx.com/Article/details/gt2whslafez.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yuanzhike.top/Article/details/gt2smyruvco.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sxryk.cn/Article/details/gt2qwhkszki.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenjidiqi.icu/Article/details/gt2uqxjkjko.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.0kj1m.cn/Article/details/gt2xsugixcw.html

[L04] 设置超时
来源：http://dali.c1oappe.top/Article/details/gt2xyuejukr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xuanzx.com/Article/details/gt2ponawtfu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.vqdsnc.cn/Article/details/gt2pznlxnwn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigfzy.top/Article/details/gt2oqahzjsh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xinyue.icu/Article/details/gt2jjbcprlm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shuidangran.top/Article/details/gt2xqpdludy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhongyouzk.top/Article/details/gt2wwdbiqau.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cqqwz.cn/Article/details/gt2ccqqcjqw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenzaomai.com/Article/details/gt2tnrootyk.html

[L05] 上传文件（multipart）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wcpywcoh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hywenlv.cn/Article/details/gt2whcejpyq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.iojbl.cn/Article/details/gt2wtjjbnot.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.vqdsnc.cn/Article/details/gt2yyvdmtqr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.smart0.xyz/Article/details/gt2uwjsbegl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rgnryfnd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yuanzhike.top/Article/details/gt2xjbjnrmp.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.meibo888.top/Article/details/gt2fpbtrszq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xinyue.icu/Article/details/gt2xqkugsjm.html

[L06] 解析响应为 JSON
来源：http://dali.xziqi.cn/Article/details/gt2sqnikxmy.html

Py:   resp.json()
来源：http://dali.kuanghao11.cn/Article/details/gt2exzxicvu.html

PHP:  json_decode($body, true);
来源：http://dali.9152youxi.cn/Article/details/gt2nkqgxusb.html

JS:   await resp.json()
来源：http://dali.jianghu66.top/Article/details/gt2lriddrdt.html

TS:   await resp.json()
来源：http://dali.xylfe.cn/Article/details/gt2cjrlyejc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ehwqpu.com/Article/details/gt2wbnweaga.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.tanke756.top/Article/details/gt2qlodlpdl.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xziqi.cn/Article/details/gt2crdemgtg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nanxinkj.top/Article/details/gt2fwpfhykw.html

[L07] 处理 HTTP 状态码
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qzbqmnxr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iidczdaz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hongshengwenyu.top/Article/details/gt2gxgnofpo.html

JS:   resp.ok;  resp.status
来源：http://dali.pengpengdd.cyou/Article/details/gt2okytcrhx.html

TS:   resp.ok;  resp.status
来源：http://dali.ehwqpu.com/Article/details/gt2yxkqtomv.html

Java: resp.statusCode()
来源：http://dali.wangshuangyany.cn/Article/details/gt2gltbmtvv.html

Go:   resp.StatusCode
来源：http://dali.hfpthk.cn/Article/details/gt2tzgqkzhv.html

Ruby: resp.code.to_i
来源：http://dali.cashguo.top/Article/details/gt2vgieseve.html

C#:   (int)resp.StatusCode
来源：http://dali.aibaodan.cn/Article/details/gt2bgaywhqt.html

[L08] 并发请求多个地址
来源：http://dali.jlsjyb.cn/Article/details/gt2afkytkek.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gaohongyu789.top/Article/details/gt2xgffssoq.html

PHP:  curl_multi_init() 系列
来源：http://dali.yonumen.top/Article/details/gt2ptgsgdha.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mlfltiky.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aizwys.cn/Article/details/gt2ckrjytmu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.chenlongwang.top/Article/details/gt2ozlamnyn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.iojbl.cn/Article/details/gt2ntwuindm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinqigfzy.top/Article/details/gt2yfvunadi.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gaohongyu789.top/Article/details/gt2gftfqmyn.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2zrmgohur.html

M. 命令行 / 进程 / 环境
来源：http://dali.xylfe.cn/Article/details/gt2ejklmnje.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2yrwsemxu.html

[M01] 读取命令行参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2owjoaxvg.html

Py:   sys.argv[1:]
来源：http://dali.jqgfzy.top/Article/details/gt2dsstcglj.html

PHP:  $argv;  $argc;
来源：http://dali.tian-w.cn/Article/details/gt2valuzpkr.html

JS:   process.argv.slice(2)
来源：http://dali.redwolf501.top/Article/details/gt2zqwrkfgj.html

TS:   process.argv.slice(2)
来源：http://dali.yvedp.cn/Article/details/gt2inoiimqb.html

Java: args 数组（main 方法参数）
来源：http://dali.kuanghao11.cn/Article/details/gt2ubzfunhe.html

Go:   os.Args[1:]
来源：http://dali.yonumen.top/Article/details/gt2udahoxxb.html

Ruby: ARGV
来源：http://dali.jinqigufen.top/Article/details/gt2jbdcqolz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.birdmap.top/Article/details/gt2amdoucdm.html

[M02] 读取环境变量
来源：http://dali.andypj.xyz/Article/details/gt2scbsdqsq.html

Py:   os.environ.get("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gt2mtbtyayd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj202588.top/Article/details/gt2lmxuhkjv.html

JS:   process.env.HOME
来源：http://dali.feifeiyinyue.top/Article/details/gt2inejhmpo.html

TS:   process.env.HOME
来源：http://dali.dianchejie.cn/Article/details/gt2xgniqgfn.html

Java: System.getenv("HOME")
来源：http://dali.cucudq.cn/Article/details/gt2pigozpqj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sxryk.cn/Article/details/gt2oltklmna.html

Ruby: ENV["HOME"]
来源：http://dali.nanxinkj.top/Article/details/gt2igsdtsuq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenzaomai.com/Article/details/gt2uhsnbysh.html

[M03] 执行外部命令
来源：http://dali.316326.xyz/Article/details/gt2ryuqlsce.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.0kj1m.cn/Article/details/gt2uclemgml.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jqgfzy.top/Article/details/gt2ymjphwpy.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.bjfxy.top/Article/details/gt2nfcquyxd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.guannengcc.top/Article/details/gt2jfsvceto.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gdkplfqj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cheryme.top/Article/details/gt2kyfvslqg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.0kj1m.cn/Article/details/gt2qgnpyion.html

C#:   Process.Start("ls", "-l");
来源：http://dali.316326.xyz/Article/details/gt2ozcfldxh.html

[M04] 获取当前工作目录
来源：http://dali.jlsjyb.cn/Article/details/gt2mnkzngda.html

Py:   os.getcwd()
来源：http://dali.ybcxt.top/Article/details/gt2bcowrqhk.html

PHP:  getcwd();
来源：http://dali.yangfankeji.com/Article/details/gt2yxnmqiws.html

JS:   process.cwd()
来源：http://dali.yonumen.top/Article/details/gt2iplwfcxn.html

TS:   process.cwd()
来源：http://dali.yonumen.top/Article/details/gt2vgfpaqow.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xuanzx.com/Article/details/gt2lyxtwzab.html

Go:   os.Getwd()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ujsaosbh.html

Ruby: Dir.pwd
来源：http://dali.jqgfzy.top/Article/details/gt2kjizzarf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xylfe.cn/Article/details/gt2nptlxpoe.html

[M05] 设置退出码
来源：http://dali.xuetiantiany.cn/Article/details/gt2ztbrebom.html

Py:   sys.exit(1)
来源：http://dali.sysykeji.top/Article/details/gt2cqwoondi.html

PHP:  exit(1);
来源：http://dali.shangyingyoupin.top/Article/details/gt2paanhofa.html

JS:   process.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gt2wavxxpkr.html

TS:   process.exit(1)
来源：http://dali.havefunace.top/Article/details/gt2dceennhh.html

Java: System.exit(1)
来源：http://dali.fengsongda.top/Article/details/gt2rfzhinne.html

Go:   os.Exit(1)
来源：http://dali.guannengcc.top/Article/details/gt2sktczinh.html

Ruby: exit 1
来源：http://dali.yj20258.top/Article/details/gt2snznhetn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj20258.top/Article/details/gt2frhjcrnf.html

[M06] 向标准错误输出
来源：http://dali.c1oappe.top/Article/details/gt2hlaqugnm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2drojyaag.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhengqikj.top/Article/details/gt2epmkxjpe.html

JS:   console.error("err")
来源：http://dali.yongpay.top/Article/details/gt2gtirlvbz.html

TS:   console.error("err")
来源：http://dali.cashguo.top/Article/details/gt2ezlscmlr.html

Java: System.err.println("err")
来源：http://dali.jinqigfzy.top/Article/details/gt2frbkdjtv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ivvv.top/Article/details/gt2flzorwmr.html

Ruby: warn "err"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mfovvqvx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.andypj.xyz/Article/details/gt2zijmfpyn.html

[M07] 判断是否为主入口
来源：http://dali.nwbrower.top/Article/details/gt2tgwdwfhc.html

Py:   if __name__ == "__main__":
来源：http://dali.guannengcc.top/Article/details/gt2dnkmizhz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.0kj1m.cn/Article/details/gt2arwfzoqy.html

JS:   require.main === module
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2idlvgcoy.html

TS:   require.main === module
来源：http://dali.cucudq.cn/Article/details/gt2mhwqbcev.html

Java: public static void main(String[] args)
来源：http://dali.yj20258888.top/Article/details/gt2qqjdtlsu.html

Go:   func main()
来源：http://dali.zhongyouzk.top/Article/details/gt2zkkqroko.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shuidangran.top/Article/details/gt2egnlvxtn.html

C#:   static void Main(string[] args)
来源：http://dali.shzxlz.cn/Article/details/gt2sqceyulp.html

[M08] 获取系统与运行时信息
来源：http://dali.cdnleiting.top/Article/details/gt2zdxdtblj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nihydoxi.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.bjfxy.top/Article/details/gt2rolsyhmn.html

JS:   process.platform;  process.version
来源：http://dali.ehwqpu.com/Article/details/gt2pxhvmtax.html

TS:   process.platform;  process.version
来源：http://dali.redwolf501.top/Article/details/gt2nysekleo.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yvedp.cn/Article/details/gt2tkegzsiw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xinyue.icu/Article/details/gt2ntbrqilc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yj20258.top/Article/details/gt2whlzwild.html


<!-- 参考信息 -->