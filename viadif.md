代发 wailian999

TS:   d1.getTime() < d2.getTime()
来源：http://dali.tanke756.top/Article/details/gtzkcxcmag.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sufxvd.cn/Article/details/gtvjkyqtbu.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.meibo888.top/Article/details/gtjmabjlvc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gtwuwfsrri.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gtjjhkmaju.html

[J08] 提取年月日与星期
来源：http://dali.9152youxi.cn/Article/details/gtlmcpjujw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.bjfxy.top/Article/details/gtjylgkxeu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinyuanbaomall.cn/Article/details/gteudmsnoe.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.haohaochexian.top/Article/details/gtjsnvqgwc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hnqzz.top/Article/details/gtrvdfuyqk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xuetiantiany.cn/Article/details/gtmffaxxdv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ivvv.top/Article/details/gtwvgdpzty.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.316326.xyz/Article/details/gtjfzrjsxo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhijiandao.cn/Article/details/gtpwggpwxs.html

[J09] 时区处理
来源：http://dali.pengpengdd.cyou/Article/details/gtfefhlvun.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cucudq.cn/Article/details/gtlletbawe.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shuidangran.top/Article/details/gtlqwlluzc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sxryk.cn/Article/details/gtgdhezcpn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhoulong.xyz/Article/details/gtodrixntb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cucudq.cn/Article/details/gtemcghuxu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shangyingyoupin.top/Article/details/gtinlydqwe.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sweek.top/Article/details/gtvpyslhyg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdfdonkey.html

[J10] 取今天 / 本月第一天
来源：http://dali.iojbl.cn/Article/details/gthnlwujkh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yj202588.top/Article/details/gtizkwlfil.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ydzc1.top/Article/details/gtxkfifbcc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yj20258888.top/Article/details/gtzmqvbcgi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jyoumei.cn/Article/details/gtvkosjuwo.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.guowangkeji.top/Article/details/gtcjousxmd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.tianlin.xyz/Article/details/gtsmzkhzmw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.9152youxi.cn/Article/details/gtwjqfolfo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.guannengcc.top/Article/details/gtcyqzswba.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtrkpahnal.html

K. JSON 与序列化
来源：http://dali.chenjidiqi.icu/Article/details/gtxvzgtlcs.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gttzkshajd.html

[K01] 对象转 JSON 字符串
来源：http://dali.jyoumei.cn/Article/details/gttywtcgbv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhongyouzk.top/Article/details/gtdftfmnis.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgfzy.top/Article/details/gtotnlbpsu.html

JS:   JSON.stringify(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtnmuxnvxy.html

TS:   JSON.stringify(obj)
来源：http://dali.haohaochexian.top/Article/details/gtdingftcj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cashguo.top/Article/details/gtldlerpqc.html

Go:   json.Marshal(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtgxsgxrsq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhongyouzk.top/Article/details/gtdjpakzok.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yueranfly.top/Article/details/gtftrhztjf.html

[K02] JSON 字符串转对象
来源：http://dali.yanxiufei.cn/Article/details/gtqapxcdvx.html

Py:   json.loads(s)
来源：http://dali.gotoacloud.top/Article/details/gtactpukuh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.pycfn.com/Article/details/gtkjuhoxwe.html

JS:   JSON.parse(s)
来源：http://dali.hnqzz.top/Article/details/gttaiocqyh.html

TS:   JSON.parse(s)
来源：http://dali.cdnleiting.top/Article/details/gtkfnfkgoz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yangfankeji.com/Article/details/gtmujbltah.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.feifeiyinyue.top/Article/details/gtrpaoqovl.html

Ruby: JSON.parse(s)
来源：http://dali.fzhhl.top/Article/details/gthcualklj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hnxiangtu.top/Article/details/gtdyiifzxn.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gogol.net.cn/Article/details/gtnguvvoap.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cheryme.top/Article/details/gtqcpaybgn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hnxiangtu.top/Article/details/gtdvdyydub.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.kuanghao11.cn/Article/details/gtvygqnnqq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.svipenyu.cn/Article/details/gtmudfrkci.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.meibo888.top/Article/details/gtcuniuedu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.chenzaomai.com/Article/details/gttnqfilan.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jqgfzy.top/Article/details/gtxmoflmax.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ydzc1.top/Article/details/gttprdavmp.html

[K04] 读取 JSON 文件
来源：http://dali.bjfxy.top/Article/details/gthqjobmzf.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhixingplan.top/Article/details/gtjpajsngl.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yuxming.cn/Article/details/gtshwntzlf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigfzy.top/Article/details/gtarsbgive.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gttpmvxbxj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.0kj1m.cn/Article/details/gtbptdrfdk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cdnleiting.top/Article/details/gtyiyjcwqv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xuetiantiany.cn/Article/details/gttlglzixa.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gtpzuevnwr.html

[K05] 深拷贝对象
来源：http://dali.xuanzx.com/Article/details/gtbmcuuqmf.html

Py:   copy.deepcopy(obj)
来源：http://dali.yvedp.cn/Article/details/gtoifrmxcq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinghuilouyu.cn/Article/details/gtwtlqrrun.html

JS:   structuredClone(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtwxigytcw.html

TS:   structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gtjbqnupvl.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gtvzakhluw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.bjfxy.top/Article/details/gtmnwhwqdy.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yj20258.top/Article/details/gtifjhuoeq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.wangshuangyany.cn/Article/details/gtjwrlhiuy.html

[K06] 解析 URL 查询串
来源：http://dali.zhongyouzk.top/Article/details/gtcklnfnhb.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.aibaodan.cn/Article/details/gthwrqarvy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.redwolf501.top/Article/details/gthzneskfz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmqznfzan.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxinkj.top/Article/details/gtcqoztpez.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shuidangran.top/Article/details/gthsijgqwd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gtfrqxjiqo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.birdmap.top/Article/details/gtyjxzhtei.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gtmndfufhz.html

[K07] 进制转换
来源：http://dali.svipenyu.cn/Article/details/gtuwjgghcw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gtehkdogcw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xinyue.icu/Article/details/gtgytpexuo.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gtkwfuwoaz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gtvmwlvldi.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gttxmrgsdu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinqigfzy.top/Article/details/gtwigukcdn.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hnqzz.top/Article/details/gtzcsepypf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtozdoqcoi.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nwbrower.top/Article/details/gthgkcrzsu.html

Py:   pickle.dumps(obj)
来源：http://dali.haohaochexian.top/Article/details/gtwnsphves.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gtmjfmusyy.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shangyingyoupin.top/Article/details/gtggxvhzez.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jqgfzy.top/Article/details/gtwrkoduzf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj20258.top/Article/details/gtsexdfydd.html

Go:   encoding/gob
来源：http://dali.ybcxt.top/Article/details/gtidddfstc.html

Ruby: Marshal.dump(obj)
来源：http://dali.shuidangran.top/Article/details/gtpgolvdps.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yvedp.cn/Article/details/gtsngrzqyy.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtktlgzzzw.html

L. 网络请求
来源：http://dali.pycfn.com/Article/details/gtkxmckgcf.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtrwlbtplu.html

[L01] 发送 GET 请求
来源：http://dali.bjfxy.top/Article/details/gtxawmfjgq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhiwuduotai.top/Article/details/gtmocjczvg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhixingplan.top/Article/details/gtjugkgnss.html

JS:   await fetch(url)
来源：http://dali.meibo888.top/Article/details/gtuxklgtrd.html

TS:   await fetch(url)
来源：http://dali.yuxming.cn/Article/details/gtzyxbcyfo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shuidangran.top/Article/details/gtwifdvofv.html

Go:   resp, err := http.Get(url)
来源：http://dali.svipenyu.cn/Article/details/gttrhixqzf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gaohongyu789.top/Article/details/gtkjvhcsnp.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jqgfzy.top/Article/details/gtpwcpkynh.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gtsjbvsuzj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ybcxt.top/Article/details/gtddzosnox.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ivvv.top/Article/details/gtdzknobvv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.9152youxi.cn/Article/details/gtaajjqypk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenjidiqi.icu/Article/details/gteqtbkewq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpdbgrhml.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shanyushiyangtech.top/Article/details/gtqoyqfgpv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.wangshuangyany.cn/Article/details/gtmfhbvhgk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlkoktwee.html

[L03] 设置自定义请求头
来源：http://dali.hywenlv.cn/Article/details/gtbjcavgdk.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yj202588.top/Article/details/gtppnykhty.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhixingplan.top/Article/details/gtkzjriygf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.iojbl.cn/Article/details/gtmoexhkgd.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangtech.top/Article/details/gtgdcygfvq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hysaishi.cn/Article/details/gtwppqshyy.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.haohaochexian.top/Article/details/gtalgytrxw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinghuilouyu.cn/Article/details/gtkbrezkod.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.svipenyu.cn/Article/details/gtxizgfnlg.html

[L04] 设置超时
来源：http://dali.jinqigufen.top/Article/details/gtpiyvgdek.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xziqi.cn/Article/details/gtobcqazbz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cdnleiting.top/Article/details/gtndxzuyia.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aizwys.cn/Article/details/gtoimwafim.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.meibo888.top/Article/details/gthbzgvljp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtamcyumwv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.wangshuangyany.cn/Article/details/gtfrhbodde.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nanxinkj.top/Article/details/gthayxebhg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.pengpengdd.cyou/Article/details/gtkdenchkj.html

[L05] 上传文件（multipart）
来源：http://dali.feifeiyinyue.top/Article/details/gtuzrknizt.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sxryk.cn/Article/details/gtyhcxrlnb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xuanzx.com/Article/details/gttinvunia.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.aizwys.cn/Article/details/gtwewoynxl.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.haohaochexian.top/Article/details/gtiuyzwdwd.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnmnhxrfl.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.quarkkingdee.top/Article/details/gtbifyqyni.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gaohongyu789.top/Article/details/gtoxdnpnxi.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xuanzx.com/Article/details/gtpavctcya.html

[L06] 解析响应为 JSON
来源：http://dali.quarkkingdee.top/Article/details/gtpflzblsu.html

Py:   resp.json()
来源：http://dali.cqqwz.cn/Article/details/gtmoewfgwr.html

PHP:  json_decode($body, true);
来源：http://dali.0kj1m.cn/Article/details/gtvmfjcwea.html

JS:   await resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsdpglzzw.html

TS:   await resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gttkwwrivj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xuanzx.com/Article/details/gtettxivst.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hfpthk.cn/Article/details/gtelzmgoll.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yuxming.cn/Article/details/gtsajltnwg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jyoumei.cn/Article/details/gtjkillziz.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinqigfzy.top/Article/details/gtakpybxds.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ppjwa.cn/Article/details/gtdoradnpk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hfpthk.cn/Article/details/gtvknxgygo.html

JS:   resp.ok;  resp.status
来源：http://dali.iojbl.cn/Article/details/gtjxkkspwk.html

TS:   resp.ok;  resp.status
来源：http://dali.jyoumei.cn/Article/details/gtfkbnldmx.html

Java: resp.statusCode()
来源：http://dali.hfpthk.cn/Article/details/gtygzvchty.html

Go:   resp.StatusCode
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkekjdkdd.html

Ruby: resp.code.to_i
来源：http://dali.daxiang520.top/Article/details/gtytvwqfyw.html

C#:   (int)resp.StatusCode
来源：http://dali.svipenyu.cn/Article/details/gtpfjydtls.html

[L08] 并发请求多个地址
来源：http://dali.vqdsnc.cn/Article/details/gttkaqaqej.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhoulong.xyz/Article/details/gtobethjoo.html

PHP:  curl_multi_init() 系列
来源：http://dali.gzhubu.top/Article/details/gtlstqmsqy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cqqwz.cn/Article/details/gtlfecdldl.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenzaomai.com/Article/details/gtknlakjmq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.andypj.xyz/Article/details/gthxgowhqd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.aibaodan.cn/Article/details/gtcjtjbaip.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.snrcjt.cn/Article/details/gtifrajbmb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yangfankeji.com/Article/details/gtiemibwcf.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpwdtaeeu.html

M. 命令行 / 进程 / 环境
来源：http://dali.jianghu66.top/Article/details/gtvhievrft.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtoqhniaso.html

[M01] 读取命令行参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtpdqyxovl.html

Py:   sys.argv[1:]
来源：http://dali.bjfxy.top/Article/details/gtghwlagzg.html

PHP:  $argv;  $argc;
来源：http://dali.birdmap.top/Article/details/gtoyutxydz.html

JS:   process.argv.slice(2)
来源：http://dali.guowangkeji.top/Article/details/gtetnukvac.html

TS:   process.argv.slice(2)
来源：http://dali.c1oappe.top/Article/details/gtfiarwywf.html

Java: args 数组（main 方法参数）
来源：http://dali.tianlin.xyz/Article/details/gtskxwwukb.html

Go:   os.Args[1:]
来源：http://dali.shuidangran.top/Article/details/gtrfrevent.html

Ruby: ARGV
来源：http://dali.wangshuangyany.cn/Article/details/gtnqwlxame.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj20258.top/Article/details/gtgyfiluqt.html

[M02] 读取环境变量
来源：http://dali.dashuyun.cn/Article/details/gtizoyrwcp.html

Py:   os.environ.get("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gtyuwhsgxa.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.aibaodan.cn/Article/details/gtdqpjoonl.html

JS:   process.env.HOME
来源：http://dali.xuetiantiany.cn/Article/details/gtozzmowug.html

TS:   process.env.HOME
来源：http://dali.hnqzz.top/Article/details/gteoaalfwj.html

Java: System.getenv("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gtjgmkcdno.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinqigufen.top/Article/details/gtlruhxbne.html

Ruby: ENV["HOME"]
来源：http://dali.sweek.top/Article/details/gtwvvktizc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hnqzz.top/Article/details/gteozysnkd.html

[M03] 执行外部命令
来源：http://dali.wangdashe.top/Article/details/gtiolrxvif.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hfpthk.cn/Article/details/gttrmlicpy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.snrcjt.cn/Article/details/gtojzgywzd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgufenzy.top/Article/details/gtfqkfcqns.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sysykeji.top/Article/details/gtzlnngyhj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gaohongyu789.top/Article/details/gtnjtinvkv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtayrxasti.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yuanzhike.top/Article/details/gtuabdhgra.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hammf.cn/Article/details/gteeqaycmj.html

[M04] 获取当前工作目录
来源：http://dali.nanxuanxn.top/Article/details/gtdahjdool.html

Py:   os.getcwd()
来源：http://dali.cdnleiting.top/Article/details/gtaywxcvjk.html

PHP:  getcwd();
来源：http://dali.quarkkingdee.top/Article/details/gtypsjrbfx.html

JS:   process.cwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkgyzpsjl.html

TS:   process.cwd()
来源：http://dali.hywenlv.cn/Article/details/gttrziclje.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yuxming.cn/Article/details/gtikekcpnp.html

Go:   os.Getwd()
来源：http://dali.jianghu66.top/Article/details/gtoaexglln.html

Ruby: Dir.pwd
来源：http://dali.daxiang520.top/Article/details/gtcnwdwdpk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jlsjyb.cn/Article/details/gtjpclimdc.html

[M05] 设置退出码
来源：http://dali.aibaodan.cn/Article/details/gtxtpyamau.html

Py:   sys.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtduczdtsh.html

PHP:  exit(1);
来源：http://dali.xinyue.icu/Article/details/gtvxhdmczi.html

JS:   process.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtqilfyoiu.html

TS:   process.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtimjnixvo.html

Java: System.exit(1)
来源：http://dali.gzhubu.top/Article/details/gtgfroqabn.html

Go:   os.Exit(1)
来源：http://dali.ppjwa.cn/Article/details/gtnxacbvnq.html

Ruby: exit 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtuzktpzhn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhoulong.xyz/Article/details/gtmfaliehq.html

[M06] 向标准错误输出
来源：http://dali.feifeiyinyue.top/Article/details/gtzbzlpimd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.smart0.xyz/Article/details/gtikfvhqfs.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.wangdashe.top/Article/details/gtaomoexyk.html

JS:   console.error("err")
来源：http://dali.smart0.xyz/Article/details/gtffewapyk.html

TS:   console.error("err")
来源：http://dali.vqdsnc.cn/Article/details/gtmfvpdekc.html

Java: System.err.println("err")
来源：http://dali.yuxming.cn/Article/details/gtoyngdpwa.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.bjfxy.top/Article/details/gtkmjwwaau.html

Ruby: warn "err"
来源：http://dali.jqgfzy.top/Article/details/gtyulutcel.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hammf.cn/Article/details/gtfebzkptz.html

[M07] 判断是否为主入口
来源：http://dali.sweek.top/Article/details/gtbrffmcvm.html

Py:   if __name__ == "__main__":
来源：http://dali.jinqigufen.top/Article/details/gtjnkfosfc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hfpthk.cn/Article/details/gtetgninji.html

JS:   require.main === module
来源：http://dali.ppjwa.cn/Article/details/gtigcjpjgd.html

TS:   require.main === module
来源：http://dali.shangyingyoupin.top/Article/details/gtqcqwyidg.html

Java: public static void main(String[] args)
来源：http://dali.chenlongwang.top/Article/details/gtbpizuecc.html

Go:   func main()
来源：http://dali.snrcjt.cn/Article/details/gtmyhsfvjv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gogol.net.cn/Article/details/gtqjqdqxgm.html

C#:   static void Main(string[] args)
来源：http://dali.hnxiangtu.top/Article/details/gthlrxtbok.html

[M08] 获取系统与运行时信息
来源：http://dali.ppjwa.cn/Article/details/gtwjikvfyu.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj202588.top/Article/details/gtawfvjpxy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhoulong.xyz/Article/details/gtzwqfmxpu.html

JS:   process.platform;  process.version
来源：http://dali.yongpay.top/Article/details/gtpqapllte.html

TS:   process.platform;  process.version
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmcojfohx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.quarkkingdee.top/Article/details/gtixlivqfe.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.pengpengdd.cyou/Article/details/gtlnqxpowo.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hammf.cn/Article/details/gtdttgzklk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jqgfzy.top/Article/details/gtwklklmoy.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtcrcksjmt.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gtamtvvqnc.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtueshvosm.html

[N01] 二分查找（有序数组）
来源：http://dali.shzxlz.cn/Article/details/gtuansdpdn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.meibo888.top/Article/details/gthowpafoh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.birdmap.top/Article/details/gtjnbdaqwm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zdqjudy.top/Article/details/gtnsccjmni.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.c1oappe.top/Article/details/gtrvyvudvy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtyvguehjc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gtzohlhqvm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nanxinkj.top/Article/details/gturuavvsz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtkepdzema.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.bjfxy.top/Article/details/gtfgyptrel.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.guannengcc.top/Article/details/gtfvftghcx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gtgjeiuyrc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigufen.top/Article/details/gtehrrswpd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yanxiufei.cn/Article/details/gtkzggqkfu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.nwbrower.top/Article/details/gtngvzxyuo.html

Go:   slices.Sort(arr)
来源：http://dali.hysaishi.cn/Article/details/gtottvexnb.html

Ruby: arr.sort
来源：http://dali.guowangkeji.top/Article/details/gtqiorxyfr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ppjwa.cn/Article/details/gtunvyskxi.html

[N03] 快速排序（分治示例）
来源：http://dali.hammf.cn/Article/details/gtaogveckw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xuetiantiany.cn/Article/details/gtflfkihpt.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yj20258.top/Article/details/gtfeqdhjmg.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigfzy.top/Article/details/gtjsfiesyn.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.andypj.xyz/Article/details/gtyvsutgcf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gtljzgebei.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yuxming.cn/Article/details/gtihvuugoz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhixingplan.top/Article/details/gtdvkjlvfk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.feifeiyinyue.top/Article/details/gtskntkyzi.html

[N04] 斐波那契数列
来源：http://dali.gaohongyu789.top/Article/details/gtakwefcvf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.316326.xyz/Article/details/gthlxdadnm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jlsjyb.cn/Article/details/gtkeqjdpla.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhoulong.xyz/Article/details/gtcnqudipe.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fengsongda.top/Article/details/gtcyxdrohk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hammf.cn/Article/details/gtnnghnfue.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sweek.top/Article/details/gtnlomouqz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cheryme.top/Article/details/gtsbvzyifc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sufxvd.cn/Article/details/gtysssujxk.html

[N05] 最大公约数
来源：http://dali.zycfv.cn/Article/details/gtiiydzsiu.html

Py:   math.gcd(a, b)
来源：http://dali.yj202588.top/Article/details/gtrdqcyimw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cdnleiting.top/Article/details/gtjdhxdqyy.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jiagoushi.top/Article/details/gtzjsolizf.html


<!-- 参考信息 -->