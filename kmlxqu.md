代发 wailian999

Py:   (end - start).total_seconds()
来源：http://dali.chenzaomai.com/Article/details/gt2hggkzexr.html

PHP:  $end->diff($start)->days;
来源：http://dali.sweek.top/Article/details/gt2ihkoqlle.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xinyue.icu/Article/details/gt2xnvwtryj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gaohongyu789.top/Article/details/gt2vnddyiog.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hywenlv.cn/Article/details/gt2twbqmtdg.html

Go:   end.Sub(start).Hours()
来源：http://dali.andypj.xyz/Article/details/gt2lolrchis.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yongpay.top/Article/details/gt2pzyncbpz.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenlongwang.top/Article/details/gt2mhcojnmj.html

[J07] 比较两个日期
来源：http://dali.gotoacloud.top/Article/details/gt2mhozbqdm.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.feifeiyinyue.top/Article/details/gt2nlbdpobw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hammf.cn/Article/details/gt2azvvyuwe.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.haohaochexian.top/Article/details/gt2ienuzfry.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.meibo888.top/Article/details/gt2jonvvmfs.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yongpay.top/Article/details/gt2jtiyyuil.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yuxming.cn/Article/details/gt2hcgpzlwn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gt2amazptcf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gt2srqosbla.html

[J08] 提取年月日与星期
来源：http://dali.yj202588.top/Article/details/gt2lbtfmral.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhongyouzk.top/Article/details/gt2pldpewxh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gzhubu.top/Article/details/gt2egsxlclg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenlongwang.top/Article/details/gt2qsurftil.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.quarkkingdee.top/Article/details/gt2oftenebm.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2thkfyyfs.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.nwbrower.top/Article/details/gt2lvshzakb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jiagoushi.top/Article/details/gt2cygcftsm.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yuanzhike.top/Article/details/gt2ecwogxvw.html

[J09] 时区处理
来源：http://dali.pycfn.com/Article/details/gt2hxrhxvnj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gzhubu.top/Article/details/gt2cuzsizyk.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yangfankeji.com/Article/details/gt2efxcbycl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.birdmap.top/Article/details/gt2ulzfrpzi.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gt2ylqhqntd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jqgfzy.top/Article/details/gt2hkfradwq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.0kj1m.cn/Article/details/gt2fcexbquj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenzaomai.com/Article/details/gt2tzmdbcrz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.kuanghao11.cn/Article/details/gt2ztrjgyzs.html

[J10] 取今天 / 本月第一天
来源：http://dali.yangfankeji.com/Article/details/gt2txlgutsu.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.kuanghao11.cn/Article/details/gt2enayewte.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.guowangkeji.top/Article/details/gt2ezldpcha.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jqgufenzy.top/Article/details/gt2uosasnuf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ytycqpsj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.iojbl.cn/Article/details/gt2knxhetwd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.daria6918.cn/Article/details/gt2znzdxzfh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.bjfxy.top/Article/details/gt2normytoq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cucudq.cn/Article/details/gt2dwazaqxq.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2jhutqrod.html

K. JSON 与序列化
来源：http://dali.dianchejie.cn/Article/details/gt2upiqcvgn.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2regwllsy.html

[K01] 对象转 JSON 字符串
来源：http://dali.cqqwz.cn/Article/details/gt2tulzhikl.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj20258888.top/Article/details/gt2ubahshhc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hongshengwenyu.top/Article/details/gt2tjeogdex.html

JS:   JSON.stringify(obj)
来源：http://dali.yongpay.top/Article/details/gt2xyiitkze.html

TS:   JSON.stringify(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2xmhayjii.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.9152youxi.cn/Article/details/gt2vfgzqbef.html

Go:   json.Marshal(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2iwjyxtvy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.redwolf501.top/Article/details/gt2pevjdcby.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2lzyhbepv.html

[K02] JSON 字符串转对象
来源：http://dali.xuetiantiany.cn/Article/details/gt2dfnbpgnl.html

Py:   json.loads(s)
来源：http://dali.meibo888.top/Article/details/gt2qtxycafz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gzhubu.top/Article/details/gt2punbwvnb.html

JS:   JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gt2sjovsnjy.html

TS:   JSON.parse(s)
来源：http://dali.ybcxt.top/Article/details/gt2gomtuwab.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zegslhll.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhiwuduotai.top/Article/details/gt2efxouhik.html

Ruby: JSON.parse(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2xuxezuja.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yj20258.top/Article/details/gt2omuxoqtm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.fzhhl.top/Article/details/gt2ykbezcbz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sufxvd.cn/Article/details/gt2onhctwad.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ivvv.top/Article/details/gt2ebaakctq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.pycfn.com/Article/details/gt2aghbrkwk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.dianchejie.cn/Article/details/gt2bcpwfckt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj20258888.top/Article/details/gt2rlkvpdyu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.kuanghao11.cn/Article/details/gt2odkdfxgq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hnqzz.top/Article/details/gt2xdgeosza.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhongyouzk.top/Article/details/gt2mvhixzrd.html

[K04] 读取 JSON 文件
来源：http://dali.meibo888.top/Article/details/gt2gjnfpbay.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xylfe.cn/Article/details/gt2frtdqblp.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.fengsongda.top/Article/details/gt2unsejqbx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.dianchejie.cn/Article/details/gt2sirrxugs.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gogol.net.cn/Article/details/gt2kydvengo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sweek.top/Article/details/gt2ceabejcs.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.mhx1999.top/Article/details/gt2jgmtrkfm.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.9152youxi.cn/Article/details/gt2cuwryrtn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.aizwys.cn/Article/details/gt2kssshgom.html

[K05] 深拷贝对象
来源：http://dali.haohaochexian.top/Article/details/gt2mpnynzbt.html

Py:   copy.deepcopy(obj)
来源：http://dali.yvedp.cn/Article/details/gt2dvmkjxie.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ppjwa.cn/Article/details/gt2aepymqsx.html

JS:   structuredClone(obj)
来源：http://dali.smart0.xyz/Article/details/gt2mslwzppf.html

TS:   structuredClone(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2frialjau.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.9152youxi.cn/Article/details/gt2ciunflva.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sysykeji.top/Article/details/gt2slmkhvgt.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhongyouzk.top/Article/details/gt2hvklccwl.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sweek.top/Article/details/gt2wpkgvxpz.html

[K06] 解析 URL 查询串
来源：http://dali.snrcjt.cn/Article/details/gt2joxdkldo.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jiagoushi.top/Article/details/gt2hhukopfn.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.quarkkingdee.top/Article/details/gt2ahbksxbk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuanzhike.top/Article/details/gt2yauigllt.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgfzy.top/Article/details/gt2tzehddkn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.0kj1m.cn/Article/details/gt2mjtflzrp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gt2jkqfdzff.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jyoumei.cn/Article/details/gt2jdrkvfss.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gt2myrvzitw.html

[K07] 进制转换
来源：http://dali.jianghu66.top/Article/details/gt2gwznqjvs.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gt2sypbmhdj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jqgfzy.top/Article/details/gt2kbhzjbpa.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gt2hybonfxs.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gt2nuutgtmb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gt2meiyplaa.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhongyouzk.top/Article/details/gt2vlgexurr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.tanke756.top/Article/details/gt2euxmtlid.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gt2hyixdjgi.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.smart0.xyz/Article/details/gt2bhnbwnfh.html

Py:   pickle.dumps(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2vmwwyvqh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gpzdhhug.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xuanzx.com/Article/details/gt2zoxgvbkv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shuidangran.top/Article/details/gt2oqitubhi.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinqigufen.top/Article/details/gt2skktfefb.html

Go:   encoding/gob
来源：http://dali.yuanzhike.top/Article/details/gt2udjjlwwf.html

Ruby: Marshal.dump(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2hogdccin.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.dianchejie.cn/Article/details/gt2dhjlhuqy.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2syhzfcxq.html

L. 网络请求
来源：http://dali.havefunace.top/Article/details/gt2qdldeoem.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2elpuupcq.html

[L01] 发送 GET 请求
来源：http://dali.yueranfly.top/Article/details/gt2lqiydqvi.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.aibaodan.cn/Article/details/gt2whcqkvqu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.316326.xyz/Article/details/gt2oigicpnf.html

JS:   await fetch(url)
来源：http://dali.chenlongwang.top/Article/details/gt2ytiaqtom.html

TS:   await fetch(url)
来源：http://dali.meibo888.top/Article/details/gt2mrhwoxji.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.andypj.xyz/Article/details/gt2cohwdaxb.html

Go:   resp, err := http.Get(url)
来源：http://dali.yj20258.top/Article/details/gt2mreohlqp.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cucudq.cn/Article/details/gt2oqsqjwgs.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ehwqpu.com/Article/details/gt2molkqqgo.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2eirsuqpt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wtejgxhz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hnxiangtu.top/Article/details/gt2ktmunenn.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jianghu66.top/Article/details/gt2fuhsdoau.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhixingplan.top/Article/details/gt2sdgzjijw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hammf.cn/Article/details/gt2rqwgmmkn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhiwuduotai.top/Article/details/gt2guaogmvq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sufxvd.cn/Article/details/gt2eznwnybb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.haohaochexian.top/Article/details/gt2epfessbp.html

[L03] 设置自定义请求头
来源：http://dali.yvedp.cn/Article/details/gt2buuwkfht.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yj20258888.top/Article/details/gt2iwyygifl.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.nanxinkj.top/Article/details/gt2qvvqxikv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shangyingyoupin.top/Article/details/gt2suhlpoth.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shangyingyoupin.top/Article/details/gt2viypnfdk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.tianlin.xyz/Article/details/gt2bswxwnqt.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.fengsongda.top/Article/details/gt2risaazwu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhongyouzk.top/Article/details/gt2ylmulamn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yonumen.top/Article/details/gt2yohefhic.html

[L04] 设置超时
来源：http://dali.yueranfly.top/Article/details/gt2uzepemkw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xgzarpsi.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gotoacloud.top/Article/details/gt2yokpbltd.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jyoumei.cn/Article/details/gt2guwdqmzr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pengpengdd.cyou/Article/details/gt2hgpoqznk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vlwfnedz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gotoacloud.top/Article/details/gt2gebjtrxv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ydzc1.top/Article/details/gt2svceaimg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sxryk.cn/Article/details/gt2wudcbpod.html

[L05] 上传文件（multipart）
来源：http://dali.xziqi.cn/Article/details/gt2iepdjned.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.kuanghao11.cn/Article/details/gt2vcfgvtlz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.nanxinkj.top/Article/details/gt2bhnjttir.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.quarkkingdee.top/Article/details/gt2gltyozzu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cucudq.cn/Article/details/gt2qjvzerxj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.chenlongwang.top/Article/details/gt2irdktfgz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yuxming.cn/Article/details/gt2dbmkpcgc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.nwbrower.top/Article/details/gt2mcmjpxrt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2vdawtlxz.html

[L06] 解析响应为 JSON
来源：http://dali.xinyue.icu/Article/details/gt2plwdqgzg.html

Py:   resp.json()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rtexsfss.html

PHP:  json_decode($body, true);
来源：http://dali.birdmap.top/Article/details/gt2ylynposb.html

JS:   await resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gt2udglgxyn.html

TS:   await resp.json()
来源：http://dali.mhx1999.top/Article/details/gt2ldqbnwqc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj20258.top/Article/details/gt2usbbfyyo.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.dashuyun.cn/Article/details/gt2knefdtlp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tianlin.xyz/Article/details/gt2megjgzhz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.andypj.xyz/Article/details/gt2kobcfpyn.html

[L07] 处理 HTTP 状态码
来源：http://dali.fzhhl.top/Article/details/gt2ydshpaqx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhongyouzk.top/Article/details/gt2nqnrkskf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ebolkyqx.html

JS:   resp.ok;  resp.status
来源：http://dali.tianlin.xyz/Article/details/gt2dpgkujec.html

TS:   resp.ok;  resp.status
来源：http://dali.wangshuangyany.cn/Article/details/gt2viiqqmwt.html

Java: resp.statusCode()
来源：http://dali.sysykeji.top/Article/details/gt2kszthjia.html

Go:   resp.StatusCode
来源：http://dali.iojbl.cn/Article/details/gt2ehnhamyt.html

Ruby: resp.code.to_i
来源：http://dali.fengsongda.top/Article/details/gt2kzqvizup.html

C#:   (int)resp.StatusCode
来源：http://dali.zdqjudy.top/Article/details/gt2enqtzfcc.html

[L08] 并发请求多个地址
来源：http://dali.yj20258888.top/Article/details/gt2fyougvzw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yj20258.top/Article/details/gt2gaupiipb.html

PHP:  curl_multi_init() 系列
来源：http://dali.ehwqpu.com/Article/details/gt2lhpzuckd.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shangyingyoupin.top/Article/details/gt2wlsttblk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cashguo.top/Article/details/gt2rcmgqbaz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj20258888.top/Article/details/gt2ckgfrkni.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yangfankeji.com/Article/details/gt2ciopgnpq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.fengsongda.top/Article/details/gt2vgdyyrcu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gt2hjjrxrae.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2wzmivqge.html

M. 命令行 / 进程 / 环境
来源：http://dali.cqqwz.cn/Article/details/gt2obqfqqag.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2vqrefusw.html

[M01] 读取命令行参数
来源：http://dali.fzhhl.top/Article/details/gt2dhgktqqg.html

Py:   sys.argv[1:]
来源：http://dali.pycfn.com/Article/details/gt2vqwfbahk.html

PHP:  $argv;  $argc;
来源：http://dali.guannengcc.top/Article/details/gt2citgecuk.html

JS:   process.argv.slice(2)
来源：http://dali.sweek.top/Article/details/gt2sdgmsgik.html

TS:   process.argv.slice(2)
来源：http://dali.meibo888.top/Article/details/gt2jjwzbkjc.html

Java: args 数组（main 方法参数）
来源：http://dali.aizwys.cn/Article/details/gt2tykuszmt.html

Go:   os.Args[1:]
来源：http://dali.tianlin.xyz/Article/details/gt2xtkhtrwl.html

Ruby: ARGV
来源：http://dali.smart0.xyz/Article/details/gt2yfovzpxo.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hywenlv.cn/Article/details/gt2njfjhgyx.html

[M02] 读取环境变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aakxwvbg.html

Py:   os.environ.get("HOME")
来源：http://dali.fengsongda.top/Article/details/gt2iywrfzjr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hongshengwenyu.top/Article/details/gt2hldtvmvk.html

JS:   process.env.HOME
来源：http://dali.jianghu66.top/Article/details/gt2cggmnjrj.html

TS:   process.env.HOME
来源：http://dali.zycfv.cn/Article/details/gt2uhpionxi.html

Java: System.getenv("HOME")
来源：http://dali.c1oappe.top/Article/details/gt2uyynpvqe.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gt2wijtmefh.html

Ruby: ENV["HOME"]
来源：http://dali.haohaochexian.top/Article/details/gt2yxoqdqcx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.9152youxi.cn/Article/details/gt2qhlvtnjt.html

[M03] 执行外部命令
来源：http://dali.shuidangran.top/Article/details/gt2ilfoesbh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hnxiangtu.top/Article/details/gt2tgmpnzgr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nanxuanxn.top/Article/details/gt2lavpqhlb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxuanxn.top/Article/details/gt2ininjceh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shzxlz.cn/Article/details/gt2byrmwejm.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.0kj1m.cn/Article/details/gt2icaciska.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.redwolf501.top/Article/details/gt2tztsiffu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tanke756.top/Article/details/gt2bmmcjwrt.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhengqikj.top/Article/details/gt2xeoybqnp.html

[M04] 获取当前工作目录
来源：http://dali.cdnleiting.top/Article/details/gt2salqnzxi.html

Py:   os.getcwd()
来源：http://dali.zhiwuduotai.top/Article/details/gt2fvxmaiar.html

PHP:  getcwd();
来源：http://dali.feifeiyinyue.top/Article/details/gt2xjniysqn.html

JS:   process.cwd()
来源：http://dali.andypj.xyz/Article/details/gt2izlejway.html

TS:   process.cwd()
来源：http://dali.tianlin.xyz/Article/details/gt2khlaubqb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sufxvd.cn/Article/details/gt2kctnzxcp.html

Go:   os.Getwd()
来源：http://dali.wangdashe.top/Article/details/gt2uswmioav.html

Ruby: Dir.pwd
来源：http://dali.hammf.cn/Article/details/gt2isfwietb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinqigfzy.top/Article/details/gt2ibrqjlfh.html

[M05] 设置退出码
来源：http://dali.wangdashe.top/Article/details/gt2uxpoucdl.html

Py:   sys.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gt2nhxrvmws.html

PHP:  exit(1);
来源：http://dali.jinqigufen.top/Article/details/gt2qwwyjnrh.html

JS:   process.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2ujwhqjet.html

TS:   process.exit(1)
来源：http://dali.fzhhl.top/Article/details/gt2ncblmpjc.html

Java: System.exit(1)
来源：http://dali.cucudq.cn/Article/details/gt2rvbrgfge.html

Go:   os.Exit(1)
来源：http://dali.jqgfzy.top/Article/details/gt2nacvvdus.html

Ruby: exit 1
来源：http://dali.xziqi.cn/Article/details/gt2zsqfeacz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jiagoushi.top/Article/details/gt2qmrsulvs.html

[M06] 向标准错误输出
来源：http://dali.0kj1m.cn/Article/details/gt2mooxwdvx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hammf.cn/Article/details/gt2pbacpqqk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.pengpengdd.cyou/Article/details/gt2mjhvvmfe.html

JS:   console.error("err")
来源：http://dali.nwbrower.top/Article/details/gt2acsdhyct.html

TS:   console.error("err")
来源：http://dali.nanxuanxn.top/Article/details/gt2xzeebknu.html

Java: System.err.println("err")
来源：http://dali.jlsjyb.cn/Article/details/gt2woflhmml.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.wangshuangyany.cn/Article/details/gt2hvvoqkku.html

Ruby: warn "err"
来源：http://dali.gaohongyu789.top/Article/details/gt2bxxihjpx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shzxlz.cn/Article/details/gt2ikzttlth.html

[M07] 判断是否为主入口
来源：http://dali.ybcxt.top/Article/details/gt2denefita.html

Py:   if __name__ == "__main__":
来源：http://dali.9152youxi.cn/Article/details/gt2juogbxbd.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sysykeji.top/Article/details/gt2nyttanog.html

JS:   require.main === module
来源：http://dali.9152youxi.cn/Article/details/gt2zyclknnl.html

TS:   require.main === module
来源：http://dali.pengpengdd.cyou/Article/details/gt2tmxcftpn.html

Java: public static void main(String[] args)
来源：http://dali.jinqigufen.top/Article/details/gt2fwuhirtm.html

Go:   func main()
来源：http://dali.zhoulong.xyz/Article/details/gt2cxovreov.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.daxiang520.top/Article/details/gt2dezbfijp.html

C#:   static void Main(string[] args)
来源：http://dali.redwolf501.top/Article/details/gt2qwhfquvp.html

[M08] 获取系统与运行时信息
来源：http://dali.yongpay.top/Article/details/gt2lkzaoxbj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.nanxuanxn.top/Article/details/gt2itcwktxy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.0kj1m.cn/Article/details/gt2grndneve.html

JS:   process.platform;  process.version
来源：http://dali.chenjidiqi.icu/Article/details/gt2rwsmozab.html

TS:   process.platform;  process.version
来源：http://dali.bjfxy.top/Article/details/gt2fntvqnza.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shzxlz.cn/Article/details/gt2ghaomggh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.wangshuangyany.cn/Article/details/gt2shkwxzvs.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhiwuduotai.top/Article/details/gt2qadajcyn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinqigufen.top/Article/details/gt2pqvonkvv.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2ecjfhzmh.html

N. 数据结构与算法
来源：http://dali.yj20258888.top/Article/details/gt2fxpujtwe.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2llxhptxs.html

[N01] 二分查找（有序数组）
来源：http://dali.9152youxi.cn/Article/details/gt2bbwhmibf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gjajuyma.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sxryk.cn/Article/details/gt2cgdsjuzd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenjidiqi.icu/Article/details/gt2cxsrfrqy.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shuidangran.top/Article/details/gt2tevrkkss.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.daria6918.cn/Article/details/gt2sundxjfv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gt2yjrvnuxl.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.kuanghao11.cn/Article/details/gt2dwmvhpxg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uqcnetoh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yvedp.cn/Article/details/gt2ffjkupxx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tian-w.cn/Article/details/gt2vwcctdue.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.vqdsnc.cn/Article/details/gt2sfotkwic.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhongyouzk.top/Article/details/gt2hsqswjcb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2iczaskzs.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sysykeji.top/Article/details/gt2vrkwtrua.html

Go:   slices.Sort(arr)
来源：http://dali.yj20258.top/Article/details/gt2hwghvzzg.html

Ruby: arr.sort
来源：http://dali.guowangkeji.top/Article/details/gt2erpgbtri.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jqgufenzy.top/Article/details/gt2pbqfhwzs.html

[N03] 快速排序（分治示例）
来源：http://dali.xuetiantiany.cn/Article/details/gt2hbffjgqh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ehwqpu.com/Article/details/gt2xayvzmhm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yj20258.top/Article/details/gt2jqmdlzyq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhiwuduotai.top/Article/details/gt2mxdalzqf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.c1oappe.top/Article/details/gt2erhxyuxg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.smart0.xyz/Article/details/gt2lsqtyvkl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hywenlv.cn/Article/details/gt2sijcgjdd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shzxlz.cn/Article/details/gt2fpzraook.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xinyue.icu/Article/details/gt2qldhtlum.html

[N04] 斐波那契数列
来源：http://dali.cqqwz.cn/Article/details/gt2faeoxuhq.html


<!-- 参考信息 -->