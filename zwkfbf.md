代发 wailian999

C#:   d1 < d2;  d1 == d2
来源：http://dali.havefunace.top/Article/details/gt2nvptsvee.html

[J08] 提取年月日与星期
来源：http://dali.nanxuanxn.top/Article/details/gt2heutrzld.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gotoacloud.top/Article/details/gt2wgqrihuh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj20258888.top/Article/details/gt2asgydgcl.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jqgufenzy.top/Article/details/gt2syagikfr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shangyingyoupin.top/Article/details/gt2gvntweyc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ofhzwxvk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ydzc1.top/Article/details/gt2bmvvvvdz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jqgfzy.top/Article/details/gt2bylmxizd.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xuetiantiany.cn/Article/details/gt2huwozagm.html

[J09] 时区处理
来源：http://dali.yongpay.top/Article/details/gt2hfdbjbox.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yvedp.cn/Article/details/gt2juveevkz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.snrcjt.cn/Article/details/gt2ebdtdkzr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hysaishi.cn/Article/details/gt2lhprdlol.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lnmskebf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.fengsongda.top/Article/details/gt2yycfrlrj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xinyue.icu/Article/details/gt2wvtcryxb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jqgufenzy.top/Article/details/gt2etdiyjqm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.feifeiyinyue.top/Article/details/gt2tniigeqc.html

[J10] 取今天 / 本月第一天
来源：http://dali.nanxinkj.top/Article/details/gt2hgvnvwav.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.c1oappe.top/Article/details/gt2htclhctp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yuxming.cn/Article/details/gt2hqydlkvc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhengqikj.top/Article/details/gt2mexdugsg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj20258888.top/Article/details/gt2rgnjyfta.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cheryme.top/Article/details/gt2wbeilcsi.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ppjwa.cn/Article/details/gt2lsoiumvh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.dianchejie.cn/Article/details/gt2dgiwvdxe.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.daxiang520.top/Article/details/gt2gwjvuhro.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2teluuwrc.html

K. JSON 与序列化
来源：http://dali.havefunace.top/Article/details/gt2igkjaoqs.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2ezdwsrpu.html

[K01] 对象转 JSON 字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2odbgtvyr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.bjfxy.top/Article/details/gt2svcglkmr.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258.top/Article/details/gt2lmehrpdw.html

JS:   JSON.stringify(obj)
来源：http://dali.gzhubu.top/Article/details/gt2wnhqvgof.html

TS:   JSON.stringify(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2efwhxrim.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2adecdyxv.html

Go:   json.Marshal(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2nptbiycv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xziqi.cn/Article/details/gt2fxonxbux.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sweek.top/Article/details/gt2kochiknu.html

[K02] JSON 字符串转对象
来源：http://dali.tianlin.xyz/Article/details/gt2zzqxyppb.html

Py:   json.loads(s)
来源：http://dali.cqqwz.cn/Article/details/gt2upwrmifh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenzaomai.com/Article/details/gt2bigdekgv.html

JS:   JSON.parse(s)
来源：http://dali.ydzc1.top/Article/details/gt2qmjmoeaw.html

TS:   JSON.parse(s)
来源：http://dali.aizwys.cn/Article/details/gt2cvxxqkjm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shangyingyoupin.top/Article/details/gt2vtccnylq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cucudq.cn/Article/details/gt2yfmwqufd.html

Ruby: JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gt2fwloroeh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.dashuyun.cn/Article/details/gt2gfofuayq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jqgufenzy.top/Article/details/gt2xisnocqv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rjwxpzjh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nwbrower.top/Article/details/gt2gnlbcgsg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.iojbl.cn/Article/details/gt2zpoxaipk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2uipyvgad.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yuxming.cn/Article/details/gt2nszdzxce.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yanxiufei.cn/Article/details/gt2hhtbbtjo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2rfygnmqw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.bjfxy.top/Article/details/gt2nicifhis.html

[K04] 读取 JSON 文件
来源：http://dali.hnxiangtu.top/Article/details/gt2zxgndold.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yongpay.top/Article/details/gt2ekcppowq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.meibo888.top/Article/details/gt2qheezmsn.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yangfankeji.com/Article/details/gt2klphucrk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hysaishi.cn/Article/details/gt2nudocyum.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lncrggqu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yj202588.top/Article/details/gt2sxdsisas.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.daxiang520.top/Article/details/gt2dmmjwymy.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yueranfly.top/Article/details/gt2hcfpgoos.html

[K05] 深拷贝对象
来源：http://dali.cashguo.top/Article/details/gt2uvyuigrh.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhqyplv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jqgfzy.top/Article/details/gt2gueaiowl.html

JS:   structuredClone(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2jscfexqe.html

TS:   structuredClone(obj)
来源：http://dali.nwbrower.top/Article/details/gt2uucpafwz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hsrstkbc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yvedp.cn/Article/details/gt2adtawifv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.wangshuangyany.cn/Article/details/gt2zfpaiaxx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.aizwys.cn/Article/details/gt2iivnigey.html

[K06] 解析 URL 查询串
来源：http://dali.cqqwz.cn/Article/details/gt2scujtllr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gotoacloud.top/Article/details/gt2llziwdyg.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhiwuduotai.top/Article/details/gt2mtxnyfsj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sufxvd.cn/Article/details/gt2svtyfbcm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.vqdsnc.cn/Article/details/gt2uidlwmtf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yj20258.top/Article/details/gt2buokjvch.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenzaomai.com/Article/details/gt2pvmybdvr.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.aizwys.cn/Article/details/gt2tuqdwjfz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.tian-w.cn/Article/details/gt2wqtrdgot.html

[K07] 进制转换
来源：http://dali.havefunace.top/Article/details/gt2avircvog.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gt2aajwxebp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sweek.top/Article/details/gt2umqmedvw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gt2wykkqazj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gt2ivaclkxj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gt2cajspahl.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.316326.xyz/Article/details/gt2ipjnhnft.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2abpbawwf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gt2qnbrchzb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.haohaochexian.top/Article/details/gt2nmcwtzzr.html

Py:   pickle.dumps(obj)
来源：http://dali.hammf.cn/Article/details/gt2edzifqcc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hnxiangtu.top/Article/details/gt2hhitzprm.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258.top/Article/details/gt2xoawleeh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hnxiangtu.top/Article/details/gt2pyrmwjxx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hnxiangtu.top/Article/details/gt2ftpzsyxz.html

Go:   encoding/gob
来源：http://dali.ppjwa.cn/Article/details/gt2cbkmtpvl.html

Ruby: Marshal.dump(obj)
来源：http://dali.cheryme.top/Article/details/gt2zgxtbnru.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ybcxt.top/Article/details/gt2pwqcruuh.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2pfiyixqn.html

L. 网络请求
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zroemoie.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2qagmvmxk.html

[L01] 发送 GET 请求
来源：http://dali.cashguo.top/Article/details/gt2bwvttchi.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hammf.cn/Article/details/gt2xkgdjgbo.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.quarkkingdee.top/Article/details/gt2pobgiwee.html

JS:   await fetch(url)
来源：http://dali.feifeiyinyue.top/Article/details/gt2isczhmgg.html

TS:   await fetch(url)
来源：http://dali.pycfn.com/Article/details/gt2xhcgmweq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hnqzz.top/Article/details/gt2doclgssd.html

Go:   resp, err := http.Get(url)
来源：http://dali.fzhhl.top/Article/details/gt2klbigwav.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2jeumhlth.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cdnleiting.top/Article/details/gt2jkycduhr.html

[L02] 发送 POST JSON
来源：http://dali.chenjidiqi.icu/Article/details/gt2icqdgpkk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.kuanghao11.cn/Article/details/gt2bgpinwjj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jqgfzy.top/Article/details/gt2zzpvbcvh.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuetiantiany.cn/Article/details/gt2srteafxg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2xvsktaut.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.guannengcc.top/Article/details/gt2etqnkjbf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.guannengcc.top/Article/details/gt2nymdmsxo.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.chenzaomai.com/Article/details/gt2kxptohcd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.0kj1m.cn/Article/details/gt2fwqqnahy.html

[L03] 设置自定义请求头
来源：http://dali.nanxinkj.top/Article/details/gt2vyvvctqs.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.9152youxi.cn/Article/details/gt2npbrsdcb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2umuzlbfn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yueranfly.top/Article/details/gt2qgznexjn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnxiangtu.top/Article/details/gt2zwvfoobm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.tanke756.top/Article/details/gt2gfckocqw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.iojbl.cn/Article/details/gt2tbgajzot.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zycfv.cn/Article/details/gt2yojwafgy.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yongpay.top/Article/details/gt2bkcejmjv.html

[L04] 设置超时
来源：http://dali.gotoacloud.top/Article/details/gt2xzbakzad.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zycfv.cn/Article/details/gt2shxxgads.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zycfv.cn/Article/details/gt2ugfzddyj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhiwuduotai.top/Article/details/gt2hoctynks.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dpnrhbwx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2issyoecs.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinqigfzy.top/Article/details/gt2wdynvvgg.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj202588.top/Article/details/gt2vbwqlnst.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.wangshuangyany.cn/Article/details/gt2kxioqqyq.html

[L05] 上传文件（multipart）
来源：http://dali.sxryk.cn/Article/details/gt2umlpmubo.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.haohaochexian.top/Article/details/gt2yjdwnuyn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinqigufen.top/Article/details/gt2cydmbnsl.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigfzy.top/Article/details/gt2uzjckvpc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jianghu66.top/Article/details/gt2dzenwpiq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.chenjidiqi.icu/Article/details/gt2owwzbhpu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.fzhhl.top/Article/details/gt2qmbshaux.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yongpay.top/Article/details/gt2gakmkwqh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2lrpkmbks.html

[L06] 解析响应为 JSON
来源：http://dali.sxryk.cn/Article/details/gt2edakbbux.html

Py:   resp.json()
来源：http://dali.redwolf501.top/Article/details/gt2uqydetad.html

PHP:  json_decode($body, true);
来源：http://dali.aizwys.cn/Article/details/gt2lssdgmlg.html

JS:   await resp.json()
来源：http://dali.cqqwz.cn/Article/details/gt2qzvzcdzd.html

TS:   await resp.json()
来源：http://dali.c1oappe.top/Article/details/gt2madqewfy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj202588.top/Article/details/gt2lrksmexs.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.kuanghao11.cn/Article/details/gt2kggoacli.html

Ruby: JSON.parse(resp.body)
来源：http://dali.fengsongda.top/Article/details/gt2oujftckq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.snrcjt.cn/Article/details/gt2jxtpmtnv.html

[L07] 处理 HTTP 状态码
来源：http://dali.iojbl.cn/Article/details/gt2wpdwbusx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tnlddrqp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.kuanghao11.cn/Article/details/gt2itficmkw.html

JS:   resp.ok;  resp.status
来源：http://dali.hysaishi.cn/Article/details/gt2krjreufs.html

TS:   resp.ok;  resp.status
来源：http://dali.yj20258.top/Article/details/gt2hjrkjmwo.html

Java: resp.statusCode()
来源：http://dali.nanxuanxn.top/Article/details/gt2sjlkjgzz.html

Go:   resp.StatusCode
来源：http://dali.ydzc1.top/Article/details/gt2zhyxhmqm.html

Ruby: resp.code.to_i
来源：http://dali.fzhhl.top/Article/details/gt2aolqjjok.html

C#:   (int)resp.StatusCode
来源：http://dali.nwbrower.top/Article/details/gt2uckpmtjs.html

[L08] 并发请求多个地址
来源：http://dali.guowangkeji.top/Article/details/gt2gvgsvkqj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cdnleiting.top/Article/details/gt2cyaiwggg.html

PHP:  curl_multi_init() 系列
来源：http://dali.yvedp.cn/Article/details/gt2alppetsk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gt2clffrnad.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yonumen.top/Article/details/gt2acjnpfky.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nwbrower.top/Article/details/gt2syyifbio.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hysaishi.cn/Article/details/gt2lrjfdwnn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xylfe.cn/Article/details/gt2mviyyhmx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.wangshuangyany.cn/Article/details/gt2emxseuny.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2tosvqxpp.html

M. 命令行 / 进程 / 环境
来源：http://dali.vqdsnc.cn/Article/details/gt2jnnnzrlp.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2pzwzpazo.html

[M01] 读取命令行参数
来源：http://dali.yanxiufei.cn/Article/details/gt2imphkslc.html

Py:   sys.argv[1:]
来源：http://dali.shangyingyoupin.top/Article/details/gt2kblywwxl.html

PHP:  $argv;  $argc;
来源：http://dali.dianchejie.cn/Article/details/gt2pkodpttk.html

JS:   process.argv.slice(2)
来源：http://dali.aibaodan.cn/Article/details/gt2mboimytu.html

TS:   process.argv.slice(2)
来源：http://dali.daria6918.cn/Article/details/gt2yvnocuag.html

Java: args 数组（main 方法参数）
来源：http://dali.haohaochexian.top/Article/details/gt2byejoofz.html

Go:   os.Args[1:]
来源：http://dali.birdmap.top/Article/details/gt2zuorukue.html

Ruby: ARGV
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dfcwfqar.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cqqwz.cn/Article/details/gt2egukmmqd.html

[M02] 读取环境变量
来源：http://dali.hywenlv.cn/Article/details/gt2xfsvaqnh.html

Py:   os.environ.get("HOME")
来源：http://dali.ivvv.top/Article/details/gt2hoqenhpz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.fengsongda.top/Article/details/gt2romjggzp.html

JS:   process.env.HOME
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vkinzjqd.html

TS:   process.env.HOME
来源：http://dali.jiagoushi.top/Article/details/gt2fodeddvj.html

Java: System.getenv("HOME")
来源：http://dali.dashuyun.cn/Article/details/gt2ycgrgqks.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ivvv.top/Article/details/gt2ezaobudx.html

Ruby: ENV["HOME"]
来源：http://dali.smart0.xyz/Article/details/gt2jtaajvya.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ydzc1.top/Article/details/gt2sabybsnl.html

[M03] 执行外部命令
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2agltkxvb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zycfv.cn/Article/details/gt2lbwvbfbm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jyoumei.cn/Article/details/gt2vwgkqumb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jlsjyb.cn/Article/details/gt2waydslnb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuetiantiany.cn/Article/details/gt2bslatskt.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jqgufenzy.top/Article/details/gt2exnfubis.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hnxiangtu.top/Article/details/gt2ykrjxzii.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.svipenyu.cn/Article/details/gt2sczjdgpe.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xziqi.cn/Article/details/gt2tkdkysdm.html

[M04] 获取当前工作目录
来源：http://dali.bjfxy.top/Article/details/gt2rpbrvwst.html

Py:   os.getcwd()
来源：http://dali.zhoulong.xyz/Article/details/gt2oezxnsne.html

PHP:  getcwd();
来源：http://dali.gogol.net.cn/Article/details/gt2ilslxmpo.html

JS:   process.cwd()
来源：http://dali.kuanghao11.cn/Article/details/gt2yrkyzklc.html

TS:   process.cwd()
来源：http://dali.jyoumei.cn/Article/details/gt2qxvrbzar.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xylfe.cn/Article/details/gt2qqtrwzzk.html

Go:   os.Getwd()
来源：http://dali.jinqigfzy.top/Article/details/gt2omgebaqd.html

Ruby: Dir.pwd
来源：http://dali.shanyushiyangtech.top/Article/details/gt2exvjwlkm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ppjwa.cn/Article/details/gt2midihfwt.html

[M05] 设置退出码
来源：http://dali.ppjwa.cn/Article/details/gt2udosxcwj.html

Py:   sys.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gt2caknluwl.html

PHP:  exit(1);
来源：http://dali.zhoulong.xyz/Article/details/gt2dwmcqewl.html

JS:   process.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vyeippkp.html

TS:   process.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2rnezsqyl.html

Java: System.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gt2wzcyaqvf.html

Go:   os.Exit(1)
来源：http://dali.ybcxt.top/Article/details/gt2vyynhcac.html

Ruby: exit 1
来源：http://dali.hysaishi.cn/Article/details/gt2zfciczdd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.tian-w.cn/Article/details/gt2pbkaehki.html

[M06] 向标准错误输出
来源：http://dali.ehwqpu.com/Article/details/gt2ouybppqx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.daria6918.cn/Article/details/gt2nruayxtv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.smart0.xyz/Article/details/gt2jpknwfrm.html

JS:   console.error("err")
来源：http://dali.yanxiufei.cn/Article/details/gt2pcxsthjg.html

TS:   console.error("err")
来源：http://dali.dashuyun.cn/Article/details/gt2vgescwto.html

Java: System.err.println("err")
来源：http://dali.pengpengdd.cyou/Article/details/gt2rtwmahqu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shangyingyoupin.top/Article/details/gt2yeoloqat.html

Ruby: warn "err"
来源：http://dali.cdnleiting.top/Article/details/gt2eevxuknr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.wangdashe.top/Article/details/gt2famuehow.html

[M07] 判断是否为主入口
来源：http://dali.daxiang520.top/Article/details/gt2cncdrrrw.html

Py:   if __name__ == "__main__":
来源：http://dali.xinyue.icu/Article/details/gt2njyeldii.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yj20258888.top/Article/details/gt2kqjjyvrr.html

JS:   require.main === module
来源：http://dali.zycfv.cn/Article/details/gt2zyqmuybs.html

TS:   require.main === module
来源：http://dali.yvedp.cn/Article/details/gt2onnuzwod.html

Java: public static void main(String[] args)
来源：http://dali.daria6918.cn/Article/details/gt2fiuhrkpm.html

Go:   func main()
来源：http://dali.gogol.net.cn/Article/details/gt2sgczlrww.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yongpay.top/Article/details/gt2rnsanqux.html

C#:   static void Main(string[] args)
来源：http://dali.jqgufenzy.top/Article/details/gt2mooldyih.html

[M08] 获取系统与运行时信息
来源：http://dali.gzhubu.top/Article/details/gt2vgrappin.html

Py:   platform.system();  platform.python_version()
来源：http://dali.tanke756.top/Article/details/gt2aqqhyffz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.0kj1m.cn/Article/details/gt2uuaqkweh.html

JS:   process.platform;  process.version
来源：http://dali.yongpay.top/Article/details/gt2wybsdrji.html

TS:   process.platform;  process.version
来源：http://dali.sxryk.cn/Article/details/gt2kuomerdk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cashguo.top/Article/details/gt2pbssgfrl.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.fengsongda.top/Article/details/gt2bqkrlvvc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinqigfzy.top/Article/details/gt2johlryfw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhengqikj.top/Article/details/gt2lotzgijw.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2omikelgr.html

N. 数据结构与算法
来源：http://dali.iojbl.cn/Article/details/gt2svlnbyke.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2hvnusbqq.html

[N01] 二分查找（有序数组）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aqairxgd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tanke756.top/Article/details/gt2kvkxeldp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jianghu66.top/Article/details/gt2nmpknhmz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.snrcjt.cn/Article/details/gt2vahazoaq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pycfn.com/Article/details/gt2agnqtauf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cashguo.top/Article/details/gt2btarbecv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bkenlfuy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cashguo.top/Article/details/gt2bwtyjyfa.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gt2jqvtyadn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shangyingyoupin.top/Article/details/gt2koqeltyp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yanxiufei.cn/Article/details/gt2ycrzukpe.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yvedp.cn/Article/details/gt2jwbyzfgc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ppjwa.cn/Article/details/gt2wmnwcaen.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.redwolf501.top/Article/details/gt2tkpuvdas.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.dashuyun.cn/Article/details/gt2xaotlgtc.html

Go:   slices.Sort(arr)
来源：http://dali.wangdashe.top/Article/details/gt2rgxwdfqh.html

Ruby: arr.sort
来源：http://dali.jinqigfzy.top/Article/details/gt2rrfgxluz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zycfv.cn/Article/details/gt2ksxoucsd.html

[N03] 快速排序（分治示例）
来源：http://dali.zhongyouzk.top/Article/details/gt2vmbtpzcf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hnxiangtu.top/Article/details/gt2rfhoixzz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xuanzx.com/Article/details/gt2wxbxqnqp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sweek.top/Article/details/gt2ogankdhq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jlsjyb.cn/Article/details/gt2ubvptmcf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.dianchejie.cn/Article/details/gt2kgvscokt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj202588.top/Article/details/gt2dvufwwnw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cucudq.cn/Article/details/gt2naqtoacs.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.andypj.xyz/Article/details/gt2jmbjfony.html

[N04] 斐波那契数列
来源：http://dali.jiagoushi.top/Article/details/gt2lwwhprnx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yonumen.top/Article/details/gt2eecfhfij.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yueranfly.top/Article/details/gt2ghhosamx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj20258888.top/Article/details/gt2zzrwodvl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgufenzy.top/Article/details/gt2rkwbsjys.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gogol.net.cn/Article/details/gt2bdewkref.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenlongwang.top/Article/details/gt2jdpnqiye.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wttwrcag.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nanxuanxn.top/Article/details/gt2arrflrlb.html

[N05] 最大公约数
来源：http://dali.yuxming.cn/Article/details/gt2uefirwid.html

Py:   math.gcd(a, b)
来源：http://dali.haohaochexian.top/Article/details/gt2taimdcsh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.wangdashe.top/Article/details/gt2yhwreixr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.iojbl.cn/Article/details/gt2dnjlmhwc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hlhniycu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.aibaodan.cn/Article/details/gt2azyqwcft.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jqgufenzy.top/Article/details/gt2irezldgu.html

Ruby: a.gcd(b)
来源：http://dali.zhoulong.xyz/Article/details/gt2wbsqwnqu.html


<!-- 参考信息 -->