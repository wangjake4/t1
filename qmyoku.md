代发 wailian999

Py:   (end - start).total_seconds()
来源：http://dali.xuetiantiany.cn/Article/details/gt2zktwjzwi.html

PHP:  $end->diff($start)->days;
来源：http://dali.tianlin.xyz/Article/details/gt2ohtjccra.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yanxiufei.cn/Article/details/gt2rygkfmiu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.haohaochexian.top/Article/details/gt2knkclehc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ppjwa.cn/Article/details/gt2slhmfqno.html

Go:   end.Sub(start).Hours()
来源：http://dali.jqgufenzy.top/Article/details/gt2rofgxefv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhoulong.xyz/Article/details/gt2gwntylhs.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenzaomai.com/Article/details/gt2ajdsyuwv.html

[J07] 比较两个日期
来源：http://dali.zhoulong.xyz/Article/details/gt2kzgjadtl.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gt2ptrijmuo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhengqikj.top/Article/details/gt2wzlqjgbk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ppjwa.cn/Article/details/gt2zesyexyd.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.316326.xyz/Article/details/gt2uwhzxrxg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhixingplan.top/Article/details/gt2dssllqox.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj202588.top/Article/details/gt2acxzxmcm.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gt2vjndzrmz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shzxlz.cn/Article/details/gt2yupszrvt.html

[J08] 提取年月日与星期
来源：http://dali.9152youxi.cn/Article/details/gt2hexqfvpz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhoulong.xyz/Article/details/gt2xsqoterh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.nanxinkj.top/Article/details/gt2xdgoaptw.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.316326.xyz/Article/details/gt2koizhmud.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jiagoushi.top/Article/details/gt2rrfrdstf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jqgufenzy.top/Article/details/gt2wlicxlyl.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.feifeiyinyue.top/Article/details/gt2lxbgtbqe.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenjidiqi.icu/Article/details/gt2qithstln.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.andypj.xyz/Article/details/gt2ukrittty.html

[J09] 时区处理
来源：http://dali.hysaishi.cn/Article/details/gt2rbltvshq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.smart0.xyz/Article/details/gt2tgusjkis.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhongyouzk.top/Article/details/gt2rudepdih.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dashuyun.cn/Article/details/gt2furnypwb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pycfn.com/Article/details/gt2suenipxc.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.aibaodan.cn/Article/details/gt2hbxcoepy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.redwolf501.top/Article/details/gt2vhjxghue.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.bjfxy.top/Article/details/gt2htemcxvj.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.nanxuanxn.top/Article/details/gt2mezvwwpp.html

[J10] 取今天 / 本月第一天
来源：http://dali.shuidangran.top/Article/details/gt2bticoovy.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zdqjudy.top/Article/details/gt2buederqs.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yonumen.top/Article/details/gt2lydzztvl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.316326.xyz/Article/details/gt2egpdvtfa.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.redwolf501.top/Article/details/gt2afxrqbty.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gzhubu.top/Article/details/gt2zpggmwnz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ivvv.top/Article/details/gt2jzsbsrhm.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yanxiufei.cn/Article/details/gt2cxjkvqed.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.9152youxi.cn/Article/details/gt2klbrduss.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2alcoaaxl.html

K. JSON 与序列化
来源：http://dali.hfpthk.cn/Article/details/gt2unnfkrva.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2skxjdbjk.html

[K01] 对象转 JSON 字符串
来源：http://dali.tanke756.top/Article/details/gt2pfltfofw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj20258.top/Article/details/gt2rhkpenwi.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xziqi.cn/Article/details/gt2nlkacumn.html

JS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qqxcmbvk.html

TS:   JSON.stringify(obj)
来源：http://dali.316326.xyz/Article/details/gt2kdukrcfl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ppjwa.cn/Article/details/gt2qhtjrucf.html

Go:   json.Marshal(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2aqhthtyb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.smart0.xyz/Article/details/gt2aeukwynd.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2pwstlljt.html

[K02] JSON 字符串转对象
来源：http://dali.hnxiangtu.top/Article/details/gt2etrrqspw.html

Py:   json.loads(s)
来源：http://dali.cashguo.top/Article/details/gt2joykdxar.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2coduxuzh.html

JS:   JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gt2jtoxbffr.html

TS:   JSON.parse(s)
来源：http://dali.zdqjudy.top/Article/details/gt2flvjgyny.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gogol.net.cn/Article/details/gt2wbkvvnlt.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.smart0.xyz/Article/details/gt2oxkzsfzn.html

Ruby: JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2vvthdwjo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2qgwxlxkc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iyiajmax.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yangfankeji.com/Article/details/gt2wvoxlxug.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qbgrwdyt.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jianghu66.top/Article/details/gt2xmcbumgd.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2txjhcfwz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2fhyozabw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yj20258.top/Article/details/gt2bibasroz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uvycbfem.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nanxuanxn.top/Article/details/gt2qkcbxrjs.html

[K04] 读取 JSON 文件
来源：http://dali.xziqi.cn/Article/details/gt2jrphkdkv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jiagoushi.top/Article/details/gt2astakfas.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yuanzhike.top/Article/details/gt2bbaanfzu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sysykeji.top/Article/details/gt2dhvyfhfi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.316326.xyz/Article/details/gt2qzdhpyzo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yueranfly.top/Article/details/gt2whrpffps.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sxryk.cn/Article/details/gt2vecobnhi.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.svipenyu.cn/Article/details/gt2vrqxpljp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.316326.xyz/Article/details/gt2hfwxsgmk.html

[K05] 深拷贝对象
来源：http://dali.gaohongyu789.top/Article/details/gt2mrvmmgoe.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eruroxat.html

PHP:  unserialize(serialize($obj));
来源：http://dali.meibo888.top/Article/details/gt2elsrxxer.html

JS:   structuredClone(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2hacvazfn.html

TS:   structuredClone(obj)
来源：http://dali.shuidangran.top/Article/details/gt2zrzpyodk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hnxiangtu.top/Article/details/gt2yggpvpld.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yuxming.cn/Article/details/gt2lypoahuj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.redwolf501.top/Article/details/gt2lpmvjpdz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.bjfxy.top/Article/details/gt2pqinslps.html

[K06] 解析 URL 查询串
来源：http://dali.xinyue.icu/Article/details/gt2oclwsnvn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yonumen.top/Article/details/gt2eaixpugq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uiialwnu.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ydzc1.top/Article/details/gt2vrkyfppt.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sysykeji.top/Article/details/gt2zxpaeecl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yuxming.cn/Article/details/gt2flkkmzxa.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.haohaochexian.top/Article/details/gt2iymnqglf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.iojbl.cn/Article/details/gt2feevrnox.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.tanke756.top/Article/details/gt2zberxmji.html

[K07] 进制转换
来源：http://dali.hnxiangtu.top/Article/details/gt2ekideemn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gt2xlynbhdk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nanxinkj.top/Article/details/gt2tfevuwab.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gt2qcoodkfe.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gt2kcowgnvj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gt2vomrfxdt.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jkxeayok.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhoulong.xyz/Article/details/gt2laehghlq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gt2lmfmwnvh.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.pengpengdd.cyou/Article/details/gt2bjmyqifa.html

Py:   pickle.dumps(obj)
来源：http://dali.yj20258.top/Article/details/gt2dvqzfpvs.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hnqzz.top/Article/details/gt2ozejfswi.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.daria6918.cn/Article/details/gt2tffchxvo.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.daria6918.cn/Article/details/gt2xfisgjvb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zdqjudy.top/Article/details/gt2xeqwwazv.html

Go:   encoding/gob
来源：http://dali.jlsjyb.cn/Article/details/gt2wevegwbg.html

Ruby: Marshal.dump(obj)
来源：http://dali.c1oappe.top/Article/details/gt2njyinuqt.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.chenzaomai.com/Article/details/gt2tmpptnxt.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2fdfppfaq.html

L. 网络请求
来源：http://dali.cucudq.cn/Article/details/gt2pxrvyygy.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2riwgsffb.html

[L01] 发送 GET 请求
来源：http://dali.xuanzx.com/Article/details/gt2nphckdqe.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ybcxt.top/Article/details/gt2ujoeubwf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cdhssrcl.html

JS:   await fetch(url)
来源：http://dali.quarkkingdee.top/Article/details/gt2ulmijjpr.html

TS:   await fetch(url)
来源：http://dali.aizwys.cn/Article/details/gt2skcgwyfo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.nanxinkj.top/Article/details/gt2gboltluv.html

Go:   resp, err := http.Get(url)
来源：http://dali.hfpthk.cn/Article/details/gt2nraxsnlg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.meibo888.top/Article/details/gt2egelqrme.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yvedp.cn/Article/details/gt2blxkixyj.html

[L02] 发送 POST JSON
来源：http://dali.yuxming.cn/Article/details/gt2ybrdtezb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhixingplan.top/Article/details/gt2ubtvrile.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hysaishi.cn/Article/details/gt2asdcutfd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2znwcvlgp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gaohongyu789.top/Article/details/gt2qvgfabrm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.redwolf501.top/Article/details/gt2epmgqblx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cheryme.top/Article/details/gt2mvwhnxyu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yueranfly.top/Article/details/gt2avzdqzvi.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.snrcjt.cn/Article/details/gt2gtbhtujk.html

[L03] 设置自定义请求头
来源：http://dali.zhixingplan.top/Article/details/gt2wdgylnou.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hfpthk.cn/Article/details/gt2tujfwfgg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jiagoushi.top/Article/details/gt2ofsrilvf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yvedp.cn/Article/details/gt2esowehgf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tbwetgwj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.chenzaomai.com/Article/details/gt2fqikbtjm.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gogol.net.cn/Article/details/gt2bobwomgs.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenzaomai.com/Article/details/gt2ptinxlnd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xuanzx.com/Article/details/gt2fmcniwfl.html

[L04] 设置超时
来源：http://dali.zhiwuduotai.top/Article/details/gt2ctfgxjej.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tian-w.cn/Article/details/gt2qqgohwic.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fyqliwdm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangshuangyany.cn/Article/details/gt2paofihkq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.andypj.xyz/Article/details/gt2jgwobwcl.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhengqikj.top/Article/details/gt2jvhxcujm.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sxryk.cn/Article/details/gt2cfxttrsk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.chenzaomai.com/Article/details/gt2bjlxyxwh.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.0kj1m.cn/Article/details/gt2hwfmubil.html

[L05] 上传文件（multipart）
来源：http://dali.gogol.net.cn/Article/details/gt2vewtdjgt.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gogol.net.cn/Article/details/gt2zwysndhc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.birdmap.top/Article/details/gt2zjhslbao.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhongyouzk.top/Article/details/gt2foplfgzo.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lbaampzj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.daxiang520.top/Article/details/gt2ztctmijn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ybcxt.top/Article/details/gt2vkxtrgrf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cdnleiting.top/Article/details/gt2dnkycexs.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.pycfn.com/Article/details/gt2jhmxdyhb.html

[L06] 解析响应为 JSON
来源：http://dali.sysykeji.top/Article/details/gt2jlisjovs.html

Py:   resp.json()
来源：http://dali.zhiwuduotai.top/Article/details/gt2svnczvfh.html

PHP:  json_decode($body, true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xwzsudbg.html

JS:   await resp.json()
来源：http://dali.yanxiufei.cn/Article/details/gt2ftuhpwfd.html

TS:   await resp.json()
来源：http://dali.cqqwz.cn/Article/details/gt2qbzpelwx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sweek.top/Article/details/gt2tsgnvhsf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.tanke756.top/Article/details/gt2trguawaf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ppjwa.cn/Article/details/gt2ksznvhqg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.svipenyu.cn/Article/details/gt2fnbcpztu.html

[L07] 处理 HTTP 状态码
来源：http://dali.hnqzz.top/Article/details/gt2ndlxnxfm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jrjlksiw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.andypj.xyz/Article/details/gt2aliglceg.html

JS:   resp.ok;  resp.status
来源：http://dali.daxiang520.top/Article/details/gt2pxuunxtz.html

TS:   resp.ok;  resp.status
来源：http://dali.feifeiyinyue.top/Article/details/gt2iykfpmta.html

Java: resp.statusCode()
来源：http://dali.quarkkingdee.top/Article/details/gt2issihale.html

Go:   resp.StatusCode
来源：http://dali.smart0.xyz/Article/details/gt2zuoycgft.html

Ruby: resp.code.to_i
来源：http://dali.daria6918.cn/Article/details/gt2zfeuicim.html

C#:   (int)resp.StatusCode
来源：http://dali.zycfv.cn/Article/details/gt2lharhcxl.html

[L08] 并发请求多个地址
来源：http://dali.guowangkeji.top/Article/details/gt2rxefpdwg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sxbyokyi.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2damfbdbm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pycfn.com/Article/details/gt2gfgabzel.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.9152youxi.cn/Article/details/gt2xmijimwh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.birdmap.top/Article/details/gt2xdyowlpe.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.nwbrower.top/Article/details/gt2frlziotj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.snrcjt.cn/Article/details/gt2njrlkjym.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ybcxt.top/Article/details/gt2fvyerrua.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2vctbkzxb.html

M. 命令行 / 进程 / 环境
来源：http://dali.redwolf501.top/Article/details/gt2gmmfhabh.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eowjkesk.html

[M01] 读取命令行参数
来源：http://dali.yuxming.cn/Article/details/gt2rnrffdbd.html

Py:   sys.argv[1:]
来源：http://dali.nanxinkj.top/Article/details/gt2qaasvpwh.html

PHP:  $argv;  $argc;
来源：http://dali.meibo888.top/Article/details/gt2hioimmgc.html

JS:   process.argv.slice(2)
来源：http://dali.yuanzhike.top/Article/details/gt2vapazxvb.html

TS:   process.argv.slice(2)
来源：http://dali.yj20258.top/Article/details/gt2nmzdzccx.html

Java: args 数组（main 方法参数）
来源：http://dali.gotoacloud.top/Article/details/gt2uswekqpj.html

Go:   os.Args[1:]
来源：http://dali.svipenyu.cn/Article/details/gt2qwdjtsdy.html

Ruby: ARGV
来源：http://dali.zhongyouzk.top/Article/details/gt2jjhgotyt.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zamcsarr.html

[M02] 读取环境变量
来源：http://dali.jlsjyb.cn/Article/details/gt2avzqtilk.html

Py:   os.environ.get("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gt2ljljklfk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xylfe.cn/Article/details/gt2iuekyvsm.html

JS:   process.env.HOME
来源：http://dali.jlsjyb.cn/Article/details/gt2omuttqar.html

TS:   process.env.HOME
来源：http://dali.bjfxy.top/Article/details/gt2tncuivcb.html

Java: System.getenv("HOME")
来源：http://dali.haohaochexian.top/Article/details/gt2dsohcgxd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmopuarv.html

Ruby: ENV["HOME"]
来源：http://dali.hywenlv.cn/Article/details/gt2oioruzkp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yvedp.cn/Article/details/gt2ohuofrkh.html

[M03] 执行外部命令
来源：http://dali.jqgfzy.top/Article/details/gt2obdtnlvy.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.aizwys.cn/Article/details/gt2vmtjfejp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hysaishi.cn/Article/details/gt2qitlvxjd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xinyue.icu/Article/details/gt2qzolgasz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhongyouzk.top/Article/details/gt2cfetshzz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cashguo.top/Article/details/gt2gfwplliy.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jlsjyb.cn/Article/details/gt2mlkvbpbu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.daxiang520.top/Article/details/gt2rwasmaqi.html

C#:   Process.Start("ls", "-l");
来源：http://dali.feifeiyinyue.top/Article/details/gt2tgsccxfq.html

[M04] 获取当前工作目录
来源：http://dali.zdqjudy.top/Article/details/gt2jhbcmfns.html

Py:   os.getcwd()
来源：http://dali.wangshuangyany.cn/Article/details/gt2upnqobnf.html

PHP:  getcwd();
来源：http://dali.gaohongyu789.top/Article/details/gt2dtydqudn.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbpuhlo.html

TS:   process.cwd()
来源：http://dali.yangfankeji.com/Article/details/gt2zxswqhjy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.wangdashe.top/Article/details/gt2trgyhkof.html

Go:   os.Getwd()
来源：http://dali.xinyue.icu/Article/details/gt2gbtjgnbw.html

Ruby: Dir.pwd
来源：http://dali.jqgfzy.top/Article/details/gt2glejkism.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cheryme.top/Article/details/gt2gijzagcu.html

[M05] 设置退出码
来源：http://dali.shzxlz.cn/Article/details/gt2jqaoxdts.html

Py:   sys.exit(1)
来源：http://dali.yueranfly.top/Article/details/gt2irezcrtp.html

PHP:  exit(1);
来源：http://dali.jlsjyb.cn/Article/details/gt2szeetefb.html

JS:   process.exit(1)
来源：http://dali.yonumen.top/Article/details/gt2kxidtmgd.html

TS:   process.exit(1)
来源：http://dali.tian-w.cn/Article/details/gt2wnekdnml.html

Java: System.exit(1)
来源：http://dali.zycfv.cn/Article/details/gt2knmgsdll.html

Go:   os.Exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2kyuiusit.html

Ruby: exit 1
来源：http://dali.andypj.xyz/Article/details/gt2nabstuhq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenzaomai.com/Article/details/gt2knewghsh.html

[M06] 向标准错误输出
来源：http://dali.pengpengdd.cyou/Article/details/gt2ryzokjwn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xziqi.cn/Article/details/gt2nteiiidw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.c1oappe.top/Article/details/gt2xmtctcsx.html

JS:   console.error("err")
来源：http://dali.jqgfzy.top/Article/details/gt2oeidukru.html

TS:   console.error("err")
来源：http://dali.yueranfly.top/Article/details/gt2kpocczkz.html

Java: System.err.println("err")
来源：http://dali.cucudq.cn/Article/details/gt2bilvazkd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.0kj1m.cn/Article/details/gt2aulgkakx.html

Ruby: warn "err"
来源：http://dali.ydzc1.top/Article/details/gt2wsdjbpal.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sxryk.cn/Article/details/gt2qwhwmpmg.html

[M07] 判断是否为主入口
来源：http://dali.aibaodan.cn/Article/details/gt2kqmazctg.html

Py:   if __name__ == "__main__":
来源：http://dali.sweek.top/Article/details/gt2ufseqniv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hysaishi.cn/Article/details/gt2dkxreavt.html

JS:   require.main === module
来源：http://dali.ehwqpu.com/Article/details/gt2dantxbdw.html

TS:   require.main === module
来源：http://dali.yongpay.top/Article/details/gt2tgtuqlqg.html

Java: public static void main(String[] args)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yjbkzfsj.html

Go:   func main()
来源：http://dali.cheryme.top/Article/details/gt2ijdsuzis.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jqgfzy.top/Article/details/gt2ciiyxecb.html

C#:   static void Main(string[] args)
来源：http://dali.yj202588.top/Article/details/gt2sebhmtdz.html

[M08] 获取系统与运行时信息
来源：http://dali.jyoumei.cn/Article/details/gt2jaenjtpu.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhongyouzk.top/Article/details/gt2dlptipjn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ybcxt.top/Article/details/gt2fdhirglb.html

JS:   process.platform;  process.version
来源：http://dali.jqgfzy.top/Article/details/gt2wzdprmca.html

TS:   process.platform;  process.version
来源：http://dali.hongshengwenyu.top/Article/details/gt2hgfavhnz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.havefunace.top/Article/details/gt2lqykabjq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sysykeji.top/Article/details/gt2bvnziawt.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinghuilouyu.cn/Article/details/gt2voujdlfz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.bjfxy.top/Article/details/gt2apjzphdv.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2uojmjzds.html

N. 数据结构与算法
来源：http://dali.ivvv.top/Article/details/gt2tcxwiskr.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2mfivgegj.html

[N01] 二分查找（有序数组）
来源：http://dali.xuetiantiany.cn/Article/details/gt2ynnfptjh.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yj202588.top/Article/details/gt2horqjgoy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gt2knjrpbpq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fzhhl.top/Article/details/gt2gtpgnosf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tian-w.cn/Article/details/gt2tozxiees.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gzhubu.top/Article/details/gt2taggdbzf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gt2zcgqieou.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2khghfvoj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hnqzz.top/Article/details/gt2fzhpnngb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cheryme.top/Article/details/gt2gbnsbkrm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.c1oappe.top/Article/details/gt2qjqvekzk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yuanzhike.top/Article/details/gt2orlyrjmh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.meibo888.top/Article/details/gt2nziojnon.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuanzhike.top/Article/details/gt2aymezdpt.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.daxiang520.top/Article/details/gt2atxcchjv.html

Go:   slices.Sort(arr)
来源：http://dali.c1oappe.top/Article/details/gt2yfuehyzx.html

Ruby: arr.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sstewjlx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xuanzx.com/Article/details/gt2gqvypuor.html

[N03] 快速排序（分治示例）
来源：http://dali.kuanghao11.cn/Article/details/gt2ettbxksc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.fzhhl.top/Article/details/gt2rvuqbyyv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ehwqpu.com/Article/details/gt2lwtnxqbh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgufenzy.top/Article/details/gt2eglecgql.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.c1oappe.top/Article/details/gt2xsjadbtf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.tanke756.top/Article/details/gt2jfddlati.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xuetiantiany.cn/Article/details/gt2uxjocqyy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.fengsongda.top/Article/details/gt2dpgucnyy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.pengpengdd.cyou/Article/details/gt2thgtspll.html

[N04] 斐波那契数列
来源：http://dali.hnqzz.top/Article/details/gt2dngmfgez.html


<!-- 参考信息 -->