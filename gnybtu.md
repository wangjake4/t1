代发 wailian999

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yuanzhike.top/Article/details/gt2lpvlbyek.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nwbrower.top/Article/details/gt2kkqumyht.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jtubfiql.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhixingplan.top/Article/details/gt2ujgfxgmj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.bjfxy.top/Article/details/gt2cmzfpffa.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ycymgohf.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.wangshuangyany.cn/Article/details/gt2yrubedbe.html

[J06] 计算两时间之差
来源：http://dali.tianlin.xyz/Article/details/gt2fbsmyjir.html

Py:   (end - start).total_seconds()
来源：http://dali.cucudq.cn/Article/details/gt2ljyzdojn.html

PHP:  $end->diff($start)->days;
来源：http://dali.yueranfly.top/Article/details/gt2vaszojja.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.nwbrower.top/Article/details/gt2tfkzcxtm.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tian-w.cn/Article/details/gt2uskniiwd.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xinyue.icu/Article/details/gt2agvoyihf.html

Go:   end.Sub(start).Hours()
来源：http://dali.cqqwz.cn/Article/details/gt2lmohqnok.html

Ruby: end - start                 # 返回秒数
来源：http://dali.daxiang520.top/Article/details/gt2edxhmyia.html

C#:   (end - start).TotalSeconds
来源：http://dali.jyoumei.cn/Article/details/gt2uooxywyq.html

[J07] 比较两个日期
来源：http://dali.fengsongda.top/Article/details/gt2zkedysbq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gt2lrlordjs.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jqgufenzy.top/Article/details/gt2hnfbxkih.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gzhubu.top/Article/details/gt2bsxbxgde.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.aibaodan.cn/Article/details/gt2zfrzvzhz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.haohaochexian.top/Article/details/gt2ifgcllwm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ehwqpu.com/Article/details/gt2fodzzrfc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gt2gadsiolo.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gt2ykkvrjhc.html

[J08] 提取年月日与星期
来源：http://dali.cashguo.top/Article/details/gt2htajjxln.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinqigufen.top/Article/details/gt2jsygajxq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhixingplan.top/Article/details/gt2eipnelhc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwcbbwj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cheryme.top/Article/details/gt2krfgghpu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.fzhhl.top/Article/details/gt2upegvfbw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj20258888.top/Article/details/gt2dcqqemta.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yuxming.cn/Article/details/gt2cvrksvxe.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hywenlv.cn/Article/details/gt2rggamjsg.html

[J09] 时区处理
来源：http://dali.yj202588.top/Article/details/gt2ayveezoq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhengqikj.top/Article/details/gt2gwyubzva.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hfpthk.cn/Article/details/gt2ilypoivd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shangyingyoupin.top/Article/details/gt2oyvkmgzb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xziqi.cn/Article/details/gt2vmzablok.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xziqi.cn/Article/details/gt2wfpjvfwt.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nanxuanxn.top/Article/details/gt2cvemlrqd.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xziqi.cn/Article/details/gt2irecwkwp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lqnmtloh.html

[J10] 取今天 / 本月第一天
来源：http://dali.xuanzx.com/Article/details/gt2ndmggvnk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hnqzz.top/Article/details/gt2bxvsdqwy.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nanxuanxn.top/Article/details/gt2gaycahfp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hysaishi.cn/Article/details/gt2mlfyjcyp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.haohaochexian.top/Article/details/gt2euuenuam.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2gtbjayok.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.pycfn.com/Article/details/gt2jxsruquz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ahphodgk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ehwqpu.com/Article/details/gt2qrvsrezm.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2yoggjxby.html

K. JSON 与序列化
来源：http://dali.tanke756.top/Article/details/gt2asancnqp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2atxjdmwh.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vllefxig.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xuetiantiany.cn/Article/details/gt2zzggxsyy.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ucbfmmkt.html

JS:   JSON.stringify(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2cwupptkm.html

TS:   JSON.stringify(obj)
来源：http://dali.xylfe.cn/Article/details/gt2selyzotd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zycfv.cn/Article/details/gt2lauhvrsl.html

Go:   json.Marshal(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2irsyopmh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yanxiufei.cn/Article/details/gt2vqplejku.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.guannengcc.top/Article/details/gt2urdqehvs.html

[K02] JSON 字符串转对象
来源：http://dali.ehwqpu.com/Article/details/gt2ackqyecj.html

Py:   json.loads(s)
来源：http://dali.ydzc1.top/Article/details/gt2gwmhpdti.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xuetiantiany.cn/Article/details/gt2zdelxdfj.html

JS:   JSON.parse(s)
来源：http://dali.nwbrower.top/Article/details/gt2ysjelvxj.html

TS:   JSON.parse(s)
来源：http://dali.daria6918.cn/Article/details/gt2afczaicp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zycfv.cn/Article/details/gt2awofprej.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhoulong.xyz/Article/details/gt2accmfqgg.html

Ruby: JSON.parse(s)
来源：http://dali.havefunace.top/Article/details/gt2lmcyhtkn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.aibaodan.cn/Article/details/gt2mlwvditz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gaohongyu789.top/Article/details/gt2ceadhdsq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.wangshuangyany.cn/Article/details/gt2hqaynzuk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2whyeoczv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhengqikj.top/Article/details/gt2wifajlqr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgfzy.top/Article/details/gt2itpnnzql.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.smart0.xyz/Article/details/gt2tpxzakej.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shangyingyoupin.top/Article/details/gt2xngegxez.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2ynmwsotg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yonumen.top/Article/details/gt2ufuvekhx.html

[K04] 读取 JSON 文件
来源：http://dali.nwbrower.top/Article/details/gt2qalmqzlj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2bxmozftr.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.andypj.xyz/Article/details/gt2ccmroqll.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.snrcjt.cn/Article/details/gt2sfaidtgx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj202588.top/Article/details/gt2wpaioidi.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yanxiufei.cn/Article/details/gt2muoawbgi.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gotoacloud.top/Article/details/gt2kgyqswlw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jqgfzy.top/Article/details/gt2altatsod.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.pycfn.com/Article/details/gt2mfqkassw.html

[K05] 深拷贝对象
来源：http://dali.sufxvd.cn/Article/details/gt2kjnwuxvv.html

Py:   copy.deepcopy(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2ocfoilpi.html

PHP:  unserialize(serialize($obj));
来源：http://dali.meibo888.top/Article/details/gt2gqubzzbd.html

JS:   structuredClone(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2vkmdqyij.html

TS:   structuredClone(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2fsnfgjag.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yj20258888.top/Article/details/gt2kjftsymm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shangyingyoupin.top/Article/details/gt2gkvuxhjj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2czjmodxs.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gaohongyu789.top/Article/details/gt2brniagjn.html

[K06] 解析 URL 查询串
来源：http://dali.yanxiufei.cn/Article/details/gt2vnfifynt.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.snrcjt.cn/Article/details/gt2vsfcshjh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ljghexuw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.kuanghao11.cn/Article/details/gt2rtcozpsk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daxiang520.top/Article/details/gt2qgejzmev.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yonumen.top/Article/details/gt2zplqtqfv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gogol.net.cn/Article/details/gt2hsrnsyga.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.pengpengdd.cyou/Article/details/gt2xqxcfpnm.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ybcxt.top/Article/details/gt2tfbgoymn.html

[K07] 进制转换
来源：http://dali.9152youxi.cn/Article/details/gt2tokyspwx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sweek.top/Article/details/gt2vefhnfdn.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.guowangkeji.top/Article/details/gt2tkryxdqf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yonumen.top/Article/details/gt2vpfkwhii.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gt2mhvyqqfd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jhzwqbms.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zycfv.cn/Article/details/gt2pjkoqsog.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xylfe.cn/Article/details/gt2axozfsdu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gt2twpnlbyz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cqqwz.cn/Article/details/gt2stwzyiaj.html

Py:   pickle.dumps(obj)
来源：http://dali.xinyue.icu/Article/details/gt2hxcfjvxa.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2mxtnmvwq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sysykeji.top/Article/details/gt2fpthbiyk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cucudq.cn/Article/details/gt2cvntarlv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.pycfn.com/Article/details/gt2migyrajm.html

Go:   encoding/gob
来源：http://dali.gogol.net.cn/Article/details/gt2qdmwnthl.html

Ruby: Marshal.dump(obj)
来源：http://dali.gzhubu.top/Article/details/gt2sxpaztht.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.birdmap.top/Article/details/gt2xiuevbmc.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2oxphgbtt.html

L. 网络请求
来源：http://dali.zhongyouzk.top/Article/details/gt2fyipdvbu.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2mjrrhrbr.html

[L01] 发送 GET 请求
来源：http://dali.wangshuangyany.cn/Article/details/gt2lzbynutp.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shzxlz.cn/Article/details/gt2wryetpsr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.kuanghao11.cn/Article/details/gt2espizgoh.html

JS:   await fetch(url)
来源：http://dali.vqdsnc.cn/Article/details/gt2ddogzbbo.html

TS:   await fetch(url)
来源：http://dali.jiagoushi.top/Article/details/gt2jlkbpvau.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yueranfly.top/Article/details/gt2weleasqk.html

Go:   resp, err := http.Get(url)
来源：http://dali.jyoumei.cn/Article/details/gt2tpskerwc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.mhx1999.top/Article/details/gt2soiuybeo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gzhubu.top/Article/details/gt2wnftfpgu.html

[L02] 发送 POST JSON
来源：http://dali.snrcjt.cn/Article/details/gt2fdvscemi.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shzxlz.cn/Article/details/gt2dhrcstal.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ydzc1.top/Article/details/gt2hqtjdbrf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.haohaochexian.top/Article/details/gt2twrqazyv.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2scqmpxyw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jlsjyb.cn/Article/details/gt2fcrhlxmp.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.fzhhl.top/Article/details/gt2mhchjydx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nanxuanxn.top/Article/details/gt2bbzejgof.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yj202588.top/Article/details/gt2krsbapbv.html

[L03] 设置自定义请求头
来源：http://dali.dashuyun.cn/Article/details/gt2ytpddlyo.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yueranfly.top/Article/details/gt2igdivqrl.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gaohongyu789.top/Article/details/gt2nuvkvstk.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.meibo888.top/Article/details/gt2grdklyfl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigufen.top/Article/details/gt2hpqutavh.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.pengpengdd.cyou/Article/details/gt2kieoukgh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.0kj1m.cn/Article/details/gt2dzuadpfu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nanxuanxn.top/Article/details/gt2ydcfimrw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.dashuyun.cn/Article/details/gt2duxnmpow.html

[L04] 设置超时
来源：http://dali.shzxlz.cn/Article/details/gt2bhppbctw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.nanxuanxn.top/Article/details/gt2onlhswwk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aldhhsig.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigfzy.top/Article/details/gt2jbyhjpfe.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ktahleai.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yueranfly.top/Article/details/gt2uacsuhaw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.fzhhl.top/Article/details/gt2vkevpdoz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.tian-w.cn/Article/details/gt2vjxmirtu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2htiohttf.html

[L05] 上传文件（multipart）
来源：http://dali.cucudq.cn/Article/details/gt2naphmsoq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.tian-w.cn/Article/details/gt2ljyllnvy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.nanxuanxn.top/Article/details/gt2ayljhdjy.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hysaishi.cn/Article/details/gt2zzvzmwvd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hammf.cn/Article/details/gt2bfgpdwqu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yvedp.cn/Article/details/gt2ymqjofbu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.dianchejie.cn/Article/details/gt2pjivvazp.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ehwqpu.com/Article/details/gt2tkdqfuwi.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2vkxoejpl.html

[L06] 解析响应为 JSON
来源：http://dali.zhoulong.xyz/Article/details/gt2qauirqvr.html

Py:   resp.json()
来源：http://dali.wangshuangyany.cn/Article/details/gt2jhwztxrw.html

PHP:  json_decode($body, true);
来源：http://dali.iojbl.cn/Article/details/gt2rxjzazzn.html

JS:   await resp.json()
来源：http://dali.sufxvd.cn/Article/details/gt2kmffticd.html

TS:   await resp.json()
来源：http://dali.svipenyu.cn/Article/details/gt2iucusfzm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2izfvjcte.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.fzhhl.top/Article/details/gt2vfgdcrsq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj202588.top/Article/details/gt2eujfplfo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2imcdouse.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhoulong.xyz/Article/details/gt2hutwrhma.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.feifeiyinyue.top/Article/details/gt2fkhgqvdb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ehwqpu.com/Article/details/gt2jizfwyfp.html

JS:   resp.ok;  resp.status
来源：http://dali.sweek.top/Article/details/gt2xgcaceyx.html

TS:   resp.ok;  resp.status
来源：http://dali.aizwys.cn/Article/details/gt2gqevmzao.html

Java: resp.statusCode()
来源：http://dali.yj202588.top/Article/details/gt2qycvmkky.html

Go:   resp.StatusCode
来源：http://dali.cheryme.top/Article/details/gt2oasbnkhg.html

Ruby: resp.code.to_i
来源：http://dali.nanxuanxn.top/Article/details/gt2hfktuhhs.html

C#:   (int)resp.StatusCode
来源：http://dali.cheryme.top/Article/details/gt2gibphxeq.html

[L08] 并发请求多个地址
来源：http://dali.daxiang520.top/Article/details/gt2mclaryyi.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sysykeji.top/Article/details/gt2ktlflfxx.html

PHP:  curl_multi_init() 系列
来源：http://dali.gzhubu.top/Article/details/gt2uegiqiwf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhixingplan.top/Article/details/gt2jkazkvjs.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.meibo888.top/Article/details/gt2ycrgfzzd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sufxvd.cn/Article/details/gt2dzpxswot.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.tian-w.cn/Article/details/gt2yojaezad.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhongyouzk.top/Article/details/gt2plsldlfl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ppjwa.cn/Article/details/gt2pirkcdkk.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2igpjqpwr.html

M. 命令行 / 进程 / 环境
来源：http://dali.nanxinkj.top/Article/details/gt2dirdszpd.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2fvbdjodd.html

[M01] 读取命令行参数
来源：http://dali.cucudq.cn/Article/details/gt2xdfcirti.html

Py:   sys.argv[1:]
来源：http://dali.yj20258888.top/Article/details/gt2etsezsjf.html

PHP:  $argv;  $argc;
来源：http://dali.tianlin.xyz/Article/details/gt2edlzqfzb.html

JS:   process.argv.slice(2)
来源：http://dali.9152youxi.cn/Article/details/gt2uafdbsak.html

TS:   process.argv.slice(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fyudoexa.html

Java: args 数组（main 方法参数）
来源：http://dali.gotoacloud.top/Article/details/gt2fjtjdmea.html

Go:   os.Args[1:]
来源：http://dali.tianlin.xyz/Article/details/gt2xoqifsuk.html

Ruby: ARGV
来源：http://dali.sweek.top/Article/details/gt2tlfjhfaf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mfslcocq.html

[M02] 读取环境变量
来源：http://dali.xylfe.cn/Article/details/gt2znkubocl.html

Py:   os.environ.get("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rafklhub.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhiwuduotai.top/Article/details/gt2bzgkbfbw.html

JS:   process.env.HOME
来源：http://dali.mhx1999.top/Article/details/gt2flaodyei.html

TS:   process.env.HOME
来源：http://dali.feifeiyinyue.top/Article/details/gt2notqoxyx.html

Java: System.getenv("HOME")
来源：http://dali.haohaochexian.top/Article/details/gt2aivrjmsp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenlongwang.top/Article/details/gt2xivnohsw.html

Ruby: ENV["HOME"]
来源：http://dali.yuanzhike.top/Article/details/gt2sjhbaooa.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tianlin.xyz/Article/details/gt2bkpojzgw.html

[M03] 执行外部命令
来源：http://dali.hywenlv.cn/Article/details/gt2mfclgtlk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yj20258.top/Article/details/gt2flfkdwuv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.andypj.xyz/Article/details/gt2cjxecmot.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ncciylkf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigufen.top/Article/details/gt2njpcympc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.guannengcc.top/Article/details/gt2plixqbma.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.c1oappe.top/Article/details/gt2xcixpzud.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.daxiang520.top/Article/details/gt2trfgsxpt.html

C#:   Process.Start("ls", "-l");
来源：http://dali.aibaodan.cn/Article/details/gt2jgchzhfw.html

[M04] 获取当前工作目录
来源：http://dali.fzhhl.top/Article/details/gt2tsbyljfw.html

Py:   os.getcwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tmyohuhi.html

PHP:  getcwd();
来源：http://dali.ydzc1.top/Article/details/gt2iivcqypo.html

JS:   process.cwd()
来源：http://dali.andypj.xyz/Article/details/gt2ujyywlgb.html

TS:   process.cwd()
来源：http://dali.bjfxy.top/Article/details/gt2fuiwgxfz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.redwolf501.top/Article/details/gt2gejdonxb.html

Go:   os.Getwd()
来源：http://dali.jinqigufen.top/Article/details/gt2sggunkqv.html

Ruby: Dir.pwd
来源：http://dali.pengpengdd.cyou/Article/details/gt2exctlgot.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhengqikj.top/Article/details/gt2sdfuoyue.html

[M05] 设置退出码
来源：http://dali.snrcjt.cn/Article/details/gt2yntezojl.html

Py:   sys.exit(1)
来源：http://dali.redwolf501.top/Article/details/gt2gfazksqw.html

PHP:  exit(1);
来源：http://dali.c1oappe.top/Article/details/gt2yguqibwj.html

JS:   process.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2acistxnt.html

TS:   process.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gt2gbxgygne.html

Java: System.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gt2hhofighn.html

Go:   os.Exit(1)
来源：http://dali.aizwys.cn/Article/details/gt2etllesmm.html

Ruby: exit 1
来源：http://dali.aizwys.cn/Article/details/gt2dtgztngj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.fengsongda.top/Article/details/gt2obkrpcko.html

[M06] 向标准错误输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ruaobzxf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ybcxt.top/Article/details/gt2ndbnuwcn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.tianlin.xyz/Article/details/gt2sngzlxhv.html

JS:   console.error("err")
来源：http://dali.jinqigfzy.top/Article/details/gt2rnkkmhbl.html

TS:   console.error("err")
来源：http://dali.xinyue.icu/Article/details/gt2nuohhqfj.html

Java: System.err.println("err")
来源：http://dali.pycfn.com/Article/details/gt2uxghhzzj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.0kj1m.cn/Article/details/gt2jtewnglq.html

Ruby: warn "err"
来源：http://dali.ppjwa.cn/Article/details/gt2jllqmqrd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eyhrxsiu.html

[M07] 判断是否为主入口
来源：http://dali.tianlin.xyz/Article/details/gt2ozpxfzsv.html

Py:   if __name__ == "__main__":
来源：http://dali.yj20258.top/Article/details/gt2fxlkctrz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.tanke756.top/Article/details/gt2jnajpidm.html

JS:   require.main === module
来源：http://dali.sweek.top/Article/details/gt2ytpyusuy.html

TS:   require.main === module
来源：http://dali.hongshengwenyu.top/Article/details/gt2wfkziyal.html

Java: public static void main(String[] args)
来源：http://dali.daxiang520.top/Article/details/gt2ayuqduid.html

Go:   func main()
来源：http://dali.yj20258.top/Article/details/gt2swoydvov.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.birdmap.top/Article/details/gt2pgoftjep.html

C#:   static void Main(string[] args)
来源：http://dali.aibaodan.cn/Article/details/gt2koofsdgs.html

[M08] 获取系统与运行时信息
来源：http://dali.ybcxt.top/Article/details/gt2vdipetxv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.316326.xyz/Article/details/gt2pzoghbsv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yuxming.cn/Article/details/gt2bcsxcjoy.html

JS:   process.platform;  process.version
来源：http://dali.nanxuanxn.top/Article/details/gt2yylmbzrk.html

TS:   process.platform;  process.version
来源：http://dali.0kj1m.cn/Article/details/gt2abkxycgf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhoulong.xyz/Article/details/gt2wgnkmgjm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.chenlongwang.top/Article/details/gt2vqbauybi.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.meibo888.top/Article/details/gt2lvdsddof.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jianghu66.top/Article/details/gt2smnpespw.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2vbguljwu.html

N. 数据结构与算法
来源：http://dali.feifeiyinyue.top/Article/details/gt2vxgsjnqw.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2gkuydcxd.html

[N01] 二分查找（有序数组）
来源：http://dali.havefunace.top/Article/details/gt2wvteadgd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xinyue.icu/Article/details/gt2tolrfthc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pcnpopfw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigufen.top/Article/details/gt2xhvnirdu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gotoacloud.top/Article/details/gt2brndzttn.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gt2snifptwa.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yuxming.cn/Article/details/gt2dadhnvdc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hongshengwenyu.top/Article/details/gt2cbfskrqg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gzhubu.top/Article/details/gt2ocbdxjst.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.meibo888.top/Article/details/gt2hbocygrs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigufen.top/Article/details/gt2ambcgnge.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhongyouzk.top/Article/details/gt2dbpswplj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhengqikj.top/Article/details/gt2zbsfefjt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ppfyuqbw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pfbiwcbb.html

Go:   slices.Sort(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tphboukm.html

Ruby: arr.sort
来源：http://dali.9152youxi.cn/Article/details/gt2uahpczqw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cqqwz.cn/Article/details/gt2aavorxxc.html

[N03] 快速排序（分治示例）
来源：http://dali.sysykeji.top/Article/details/gt2yzebqrwq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhongyouzk.top/Article/details/gt2dxmlzfsk.html


<!-- 参考信息 -->