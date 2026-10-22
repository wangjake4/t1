代发 wailian999

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.9152youxi.cn/Article/details/gt2arknrgbn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iqmlffvf.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jupdyxfl.html

[J06] 计算两时间之差
来源：http://dali.xuanzx.com/Article/details/gt2gfvvuntw.html

Py:   (end - start).total_seconds()
来源：http://dali.yangfankeji.com/Article/details/gt2myjykesq.html

PHP:  $end->diff($start)->days;
来源：http://dali.hywenlv.cn/Article/details/gt2lnhplflu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.guannengcc.top/Article/details/gt2pzmgvmjx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xinyue.icu/Article/details/gt2qibtsjqj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gotoacloud.top/Article/details/gt2xdpspqso.html

Go:   end.Sub(start).Hours()
来源：http://dali.meibo888.top/Article/details/gt2cjyetonn.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ybcxt.top/Article/details/gt2hnlhybpu.html

C#:   (end - start).TotalSeconds
来源：http://dali.mhx1999.top/Article/details/gt2ebtdosdw.html

[J07] 比较两个日期
来源：http://dali.xylfe.cn/Article/details/gt2vjeakgid.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gt2osrzlnkb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.guowangkeji.top/Article/details/gt2xdbfswuq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tihijffl.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yonumen.top/Article/details/gt2pxogfoft.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.havefunace.top/Article/details/gt2hovluowa.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2cxmogdal.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ehwqpu.com/Article/details/gt2kbvwdvjy.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gt2tkitlxsd.html

[J08] 提取年月日与星期
来源：http://dali.chenjidiqi.icu/Article/details/gt2tzkkjgop.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ehwqpu.com/Article/details/gt2mygdjxps.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shzxlz.cn/Article/details/gt2kbnslbrf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhixingplan.top/Article/details/gt2vcqiyifi.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ybcxt.top/Article/details/gt2ijpqdliv.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.havefunace.top/Article/details/gt2lwbboduz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cheryme.top/Article/details/gt2omtlpfbj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gotoacloud.top/Article/details/gt2qwwrxmgh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.redwolf501.top/Article/details/gt2vmyxxyeu.html

[J09] 时区处理
来源：http://dali.ydzc1.top/Article/details/gt2nnzqhyen.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nanxinkj.top/Article/details/gt2rdpgceoc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sxryk.cn/Article/details/gt2ayxachrb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tian-w.cn/Article/details/gt2qpkhgsxf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gotoacloud.top/Article/details/gt2igmrypwd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zdqjudy.top/Article/details/gt2mpcynnnn.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hammf.cn/Article/details/gt2mfwfosag.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cqqwz.cn/Article/details/gt2ahnxpyff.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sysykeji.top/Article/details/gt2xamkxwba.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenlongwang.top/Article/details/gt2hcpvjpvj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ivvv.top/Article/details/gt2eowfpmzl.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.fengsongda.top/Article/details/gt2elwmiuww.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.0kj1m.cn/Article/details/gt2vxacnnmn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.meibo888.top/Article/details/gt2nhhgeqkn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.aibaodan.cn/Article/details/gt2tkjpuhok.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhixingplan.top/Article/details/gt2dmkhfbti.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xuanzx.com/Article/details/gt2kshniufl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenlongwang.top/Article/details/gt2jgmgzhih.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2ccilkupd.html

K. JSON 与序列化
来源：http://dali.zycfv.cn/Article/details/gt2ygbwvorl.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2wyhgkzrn.html

[K01] 对象转 JSON 字符串
来源：http://dali.andypj.xyz/Article/details/gt2bmgbetys.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ssbdpokv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sweek.top/Article/details/gt2ttithktq.html

JS:   JSON.stringify(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2dvmymzpy.html

TS:   JSON.stringify(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2dskyifsm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sysykeji.top/Article/details/gt2sceinagg.html

Go:   json.Marshal(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2nrrajdrq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ppjwa.cn/Article/details/gt2agtgsnre.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2havnneia.html

[K02] JSON 字符串转对象
来源：http://dali.yueranfly.top/Article/details/gt2bazdutcx.html

Py:   json.loads(s)
来源：http://dali.yueranfly.top/Article/details/gt2smghoadf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.haohaochexian.top/Article/details/gt2ydlbqvqz.html

JS:   JSON.parse(s)
来源：http://dali.yuanzhike.top/Article/details/gt2oavngfpi.html

TS:   JSON.parse(s)
来源：http://dali.mhx1999.top/Article/details/gt2jidaaulq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.kuanghao11.cn/Article/details/gt2pjirwles.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.wangshuangyany.cn/Article/details/gt2alagfdbf.html

Ruby: JSON.parse(s)
来源：http://dali.ppjwa.cn/Article/details/gt2zxdrzogm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xziqi.cn/Article/details/gt2vxapxabk.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhiwuduotai.top/Article/details/gt2nytikuqh.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.birdmap.top/Article/details/gt2aebbzlxz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jianghu66.top/Article/details/gt2kvrypshe.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ybcxt.top/Article/details/gt2ihndihqe.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.andypj.xyz/Article/details/gt2pocikbft.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2dfqiydxl.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hywenlv.cn/Article/details/gt2nfmoekny.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2zzcrmjhm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cqqwz.cn/Article/details/gt2lkupemqp.html

[K04] 读取 JSON 文件
来源：http://dali.vqdsnc.cn/Article/details/gt2xqtyjbsu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.redwolf501.top/Article/details/gt2npjlovil.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.chenjidiqi.icu/Article/details/gt2dtemrvrw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuetiantiany.cn/Article/details/gt2ypkzpqfo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cqqwz.cn/Article/details/gt2teeiallm.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xziqi.cn/Article/details/gt2bwewpxzj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.c1oappe.top/Article/details/gt2fegplznu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.pycfn.com/Article/details/gt2ujkpyumy.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nwbrower.top/Article/details/gt2racmnsqc.html

[K05] 深拷贝对象
来源：http://dali.ivvv.top/Article/details/gt2jfludvbx.html

Py:   copy.deepcopy(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2yzaxgsrx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pkigopwt.html

JS:   structuredClone(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2nmokawkf.html

TS:   structuredClone(obj)
来源：http://dali.cheryme.top/Article/details/gt2maqqbqrm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.iojbl.cn/Article/details/gt2wloqjbtg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xinyue.icu/Article/details/gt2vyexcmlb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ydzc1.top/Article/details/gt2hplcmcgp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.iojbl.cn/Article/details/gt2aqjoieka.html

[K06] 解析 URL 查询串
来源：http://dali.fzhhl.top/Article/details/gt2jefkcvmm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tianlin.xyz/Article/details/gt2cwjgwiya.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.fzhhl.top/Article/details/gt2chxskjur.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.quarkkingdee.top/Article/details/gt2hnhzpydk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gzhubu.top/Article/details/gt2qcqpcmru.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gaohongyu789.top/Article/details/gt2efcvdmcu.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gt2xgoxjpur.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gt2lneoonim.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.quarkkingdee.top/Article/details/gt2stueopxk.html

[K07] 进制转换
来源：http://dali.fengsongda.top/Article/details/gt2reybxvyn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gt2uzkptamo.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.wangdashe.top/Article/details/gt2ycgpmuru.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gt2deniglwq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gt2rjwqdtaw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gt2hjqcbqne.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ybcxt.top/Article/details/gt2fvajxgin.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hnxiangtu.top/Article/details/gt2jxailzfo.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gt2devpeswa.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.smart0.xyz/Article/details/gt2aqjubdco.html

Py:   pickle.dumps(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2kscmaarp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yonumen.top/Article/details/gt2aispfpxj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2eucsigwr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.pycfn.com/Article/details/gt2piwcwpmn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aluuiqmu.html

Go:   encoding/gob
来源：http://dali.xylfe.cn/Article/details/gt2lmshcdhw.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iilvpaxx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ivvv.top/Article/details/gt2bcbjpoca.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2fyjtgvzc.html

L. 网络请求
来源：http://dali.xinyue.icu/Article/details/gt2ttfoxjsq.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2kvoafpbh.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2sayalgla.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.9152youxi.cn/Article/details/gt2qzbrdqpf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ehwqpu.com/Article/details/gt2wyjdguar.html

JS:   await fetch(url)
来源：http://dali.sweek.top/Article/details/gt2udtctldz.html

TS:   await fetch(url)
来源：http://dali.zdqjudy.top/Article/details/gt2fskcqgww.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhoulong.xyz/Article/details/gt2dsqujwwg.html

Go:   resp, err := http.Get(url)
来源：http://dali.aizwys.cn/Article/details/gt2uljiobsk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ivvv.top/Article/details/gt2eonziwvn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.guowangkeji.top/Article/details/gt2nxvabwfo.html

[L02] 发送 POST JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cyajauhy.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zdqjudy.top/Article/details/gt2uzxwwfre.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.daria6918.cn/Article/details/gt2ektfejon.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuxming.cn/Article/details/gt2dbtdyued.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.aibaodan.cn/Article/details/gt2puawvpyh.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yvedp.cn/Article/details/gt2rpzpnzup.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hywenlv.cn/Article/details/gt2gffkjxyj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hammf.cn/Article/details/gt2nzzzqbci.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.wangdashe.top/Article/details/gt2sfghfkbp.html

[L03] 设置自定义请求头
来源：http://dali.cashguo.top/Article/details/gt2hgiuepyq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shuidangran.top/Article/details/gt2imweabkw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.redwolf501.top/Article/details/gt2qufdwksa.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aibaodan.cn/Article/details/gt2yfyqookl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zycfv.cn/Article/details/gt2fbeuuvfq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhengqikj.top/Article/details/gt2qkuagblt.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gotoacloud.top/Article/details/gt2xmqbpawl.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhengqikj.top/Article/details/gt2ictrjykb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kpxztxbd.html

[L04] 设置超时
来源：http://dali.kuanghao11.cn/Article/details/gt2avkvvolg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yj20258888.top/Article/details/gt2utcwfpji.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.pengpengdd.cyou/Article/details/gt2fgcqmqrk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fzhhl.top/Article/details/gt2sysrfzll.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenjidiqi.icu/Article/details/gt2qhxlpmzu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ybcxt.top/Article/details/gt2ivuhujub.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jyoumei.cn/Article/details/gt2zwfhwupy.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yanxiufei.cn/Article/details/gt2elzgwjhk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinqigufen.top/Article/details/gt2flgoktfw.html

[L05] 上传文件（multipart）
来源：http://dali.tian-w.cn/Article/details/gt2nyyuaefl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.fzhhl.top/Article/details/gt2ebksifzz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.vqdsnc.cn/Article/details/gt2mkmhltta.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.redwolf501.top/Article/details/gt2oczmdrzp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.tianlin.xyz/Article/details/gt2gninfctf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.redwolf501.top/Article/details/gt2qshzwesb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.dianchejie.cn/Article/details/gt2xtnrztpi.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhiwuduotai.top/Article/details/gt2ysegckin.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.c1oappe.top/Article/details/gt2jocdlpvd.html

[L06] 解析响应为 JSON
来源：http://dali.gogol.net.cn/Article/details/gt2uqfmplxl.html

Py:   resp.json()
来源：http://dali.gotoacloud.top/Article/details/gt2zvxctqdz.html

PHP:  json_decode($body, true);
来源：http://dali.tanke756.top/Article/details/gt2prmaggmm.html

JS:   await resp.json()
来源：http://dali.hammf.cn/Article/details/gt2omroczem.html

TS:   await resp.json()
来源：http://dali.quarkkingdee.top/Article/details/gt2llgvhrio.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjlfcjgw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shzxlz.cn/Article/details/gt2dnhukjpf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zycfv.cn/Article/details/gt2skhcsybv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.tian-w.cn/Article/details/gt2swukzsmc.html

[L07] 处理 HTTP 状态码
来源：http://dali.chenjidiqi.icu/Article/details/gt2tfgbzujl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.kuanghao11.cn/Article/details/gt2acmhczza.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.quarkkingdee.top/Article/details/gt2xnxsrlzb.html

JS:   resp.ok;  resp.status
来源：http://dali.hongshengwenyu.top/Article/details/gt2wqsfobxc.html

TS:   resp.ok;  resp.status
来源：http://dali.tian-w.cn/Article/details/gt2dkokbwxp.html

Java: resp.statusCode()
来源：http://dali.feifeiyinyue.top/Article/details/gt2xjvpvnst.html

Go:   resp.StatusCode
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qluptaju.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlmurza.html

C#:   (int)resp.StatusCode
来源：http://dali.dianchejie.cn/Article/details/gt2pcnlqafn.html

[L08] 并发请求多个地址
来源：http://dali.yvedp.cn/Article/details/gt2ztvxikvx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinqigufen.top/Article/details/gt2suhipekb.html

PHP:  curl_multi_init() 系列
来源：http://dali.quarkkingdee.top/Article/details/gt2bvltfzql.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.smart0.xyz/Article/details/gt2qstlnccm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gt2ifvthpci.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.haohaochexian.top/Article/details/gt2aymicyce.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.tanke756.top/Article/details/gt2skmwylps.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.c1oappe.top/Article/details/gt2etplxysx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tian-w.cn/Article/details/gt2yaqwokgj.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2msozhlms.html

M. 命令行 / 进程 / 环境
来源：http://dali.andypj.xyz/Article/details/gt2khnlvnkn.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2mvppbwap.html

[M01] 读取命令行参数
来源：http://dali.pycfn.com/Article/details/gt2ufnnymcu.html

Py:   sys.argv[1:]
来源：http://dali.pengpengdd.cyou/Article/details/gt2qmbkyvcq.html

PHP:  $argv;  $argc;
来源：http://dali.pengpengdd.cyou/Article/details/gt2qiqfavdg.html

JS:   process.argv.slice(2)
来源：http://dali.xylfe.cn/Article/details/gt2xzspohee.html

TS:   process.argv.slice(2)
来源：http://dali.xylfe.cn/Article/details/gt2qtestftb.html

Java: args 数组（main 方法参数）
来源：http://dali.shzxlz.cn/Article/details/gt2ledrpvey.html

Go:   os.Args[1:]
来源：http://dali.hysaishi.cn/Article/details/gt2jvzqxvgi.html

Ruby: ARGV
来源：http://dali.wangdashe.top/Article/details/gt2aliubmww.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hywenlv.cn/Article/details/gt2intjsved.html

[M02] 读取环境变量
来源：http://dali.jinqigufen.top/Article/details/gt2ovunzxxi.html

Py:   os.environ.get("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gt2bwonmesf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jqgufenzy.top/Article/details/gt2udhjofhq.html

JS:   process.env.HOME
来源：http://dali.jyoumei.cn/Article/details/gt2oxczriuk.html

TS:   process.env.HOME
来源：http://dali.havefunace.top/Article/details/gt2qdizyipc.html

Java: System.getenv("HOME")
来源：http://dali.tianlin.xyz/Article/details/gt2qzdplewn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yuxming.cn/Article/details/gt2mlyxwdwh.html

Ruby: ENV["HOME"]
来源：http://dali.andypj.xyz/Article/details/gt2uqdclmhq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jyoumei.cn/Article/details/gt2gyarzkzp.html

[M03] 执行外部命令
来源：http://dali.daxiang520.top/Article/details/gt2nbmzabwu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jiagoushi.top/Article/details/gt2feqddaor.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nanxuanxn.top/Article/details/gt2bxrqtwfh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangshuangyany.cn/Article/details/gt2qlzyamti.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.havefunace.top/Article/details/gt2bzpskser.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wnhfjcbs.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhixingplan.top/Article/details/gt2mqcdyrtw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hfpthk.cn/Article/details/gt2qzvnxofx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nwbrower.top/Article/details/gt2dbsycbxp.html

[M04] 获取当前工作目录
来源：http://dali.cashguo.top/Article/details/gt2csgiodmk.html

Py:   os.getcwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yqyqtqmx.html

PHP:  getcwd();
来源：http://dali.feifeiyinyue.top/Article/details/gt2jwbaiwcm.html

JS:   process.cwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aeiszfcn.html

TS:   process.cwd()
来源：http://dali.yueranfly.top/Article/details/gt2jhmsrbjn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sxryk.cn/Article/details/gt2kwqkvrho.html

Go:   os.Getwd()
来源：http://dali.cqqwz.cn/Article/details/gt2alklsqio.html

Ruby: Dir.pwd
来源：http://dali.yj20258.top/Article/details/gt2praihkje.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jyoumei.cn/Article/details/gt2aamzzhtt.html

[M05] 设置退出码
来源：http://dali.havefunace.top/Article/details/gt2lkaeybah.html

Py:   sys.exit(1)
来源：http://dali.yj20258.top/Article/details/gt2lkdkymnn.html

PHP:  exit(1);
来源：http://dali.jlsjyb.cn/Article/details/gt2ngufpgjo.html

JS:   process.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ouaufhas.html

TS:   process.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gt2mmimmxmo.html

Java: System.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gt2fafrghro.html

Go:   os.Exit(1)
来源：http://dali.wangdashe.top/Article/details/gt2brmjgzfa.html

Ruby: exit 1
来源：http://dali.fengsongda.top/Article/details/gt2syqbugrd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shangyingyoupin.top/Article/details/gt2lkduygas.html

[M06] 向标准错误输出
来源：http://dali.sysykeji.top/Article/details/gt2ltckkcdu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhixingplan.top/Article/details/gt2qddairlz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.aizwys.cn/Article/details/gt2mviegavn.html

JS:   console.error("err")
来源：http://dali.iojbl.cn/Article/details/gt2lnzfuydp.html

TS:   console.error("err")
来源：http://dali.gzhubu.top/Article/details/gt2letbngkv.html

Java: System.err.println("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cccoryhd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.kuanghao11.cn/Article/details/gt2lxtsbjbi.html

Ruby: warn "err"
来源：http://dali.wangdashe.top/Article/details/gt2cqqltaur.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.pengpengdd.cyou/Article/details/gt2tqrdgyjr.html

[M07] 判断是否为主入口
来源：http://dali.hywenlv.cn/Article/details/gt2egjujnxb.html

Py:   if __name__ == "__main__":
来源：http://dali.guannengcc.top/Article/details/gt2yepcsmqa.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sufxvd.cn/Article/details/gt2vmnbrxqk.html

JS:   require.main === module
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wuxuxfcw.html

TS:   require.main === module
来源：http://dali.wangshuangyany.cn/Article/details/gt2uykfrmzc.html

Java: public static void main(String[] args)
来源：http://dali.snrcjt.cn/Article/details/gt2dfdakmtv.html

Go:   func main()
来源：http://dali.ydzc1.top/Article/details/gt2xgfddfhy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ivvv.top/Article/details/gt2yzedheir.html

C#:   static void Main(string[] args)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ulxxrljw.html

[M08] 获取系统与运行时信息
来源：http://dali.cucudq.cn/Article/details/gt2noiyjrsg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hammf.cn/Article/details/gt2nawypkxd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.mhx1999.top/Article/details/gt2ptagsigz.html

JS:   process.platform;  process.version
来源：http://dali.ppjwa.cn/Article/details/gt2uokjfbjd.html

TS:   process.platform;  process.version
来源：http://dali.cashguo.top/Article/details/gt2fiyocvey.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhengqikj.top/Article/details/gt2udceyxrk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.quarkkingdee.top/Article/details/gt2ryijwrud.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cdnleiting.top/Article/details/gt2xzjyvstq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.kuanghao11.cn/Article/details/gt2znzqyqaz.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2ueqpgqgp.html

N. 数据结构与算法
来源：http://dali.aibaodan.cn/Article/details/gt2naqksvmh.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2ditdzkmg.html

[N01] 二分查找（有序数组）
来源：http://dali.pengpengdd.cyou/Article/details/gt2jvuqylkj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gt2qjdjcovl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinqigufen.top/Article/details/gt2weptbrbf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ycwdopud.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yonumen.top/Article/details/gt2kupcldip.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sweek.top/Article/details/gt2dfjygmca.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ykjjoniq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ryzvkfjh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hammf.cn/Article/details/gt2kemvapfd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gzhubu.top/Article/details/gt2pnkiqmgo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yangfankeji.com/Article/details/gt2aswxwdno.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cucudq.cn/Article/details/gt2mlozrptx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sufxvd.cn/Article/details/gt2cmerlkab.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.316326.xyz/Article/details/gt2xbzjktwt.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.fzhhl.top/Article/details/gt2ejawwzxj.html

Go:   slices.Sort(arr)
来源：http://dali.yuxming.cn/Article/details/gt2qxcdfadq.html

Ruby: arr.sort
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zssuaglf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.fzhhl.top/Article/details/gt2fydwxifd.html

[N03] 快速排序（分治示例）
来源：http://dali.yj20258.top/Article/details/gt2eerlkwll.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ehwqpu.com/Article/details/gt2bejaujrc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.birdmap.top/Article/details/gt2hayptawv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aibaodan.cn/Article/details/gt2fkrtoawt.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangshuangyany.cn/Article/details/gt2dlvyduag.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gzhubu.top/Article/details/gt2ezlnwqsg.html


<!-- 参考信息 -->