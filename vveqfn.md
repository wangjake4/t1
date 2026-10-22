代发 wailian999

TS:   d1.getTime() < d2.getTime()
来源：http://dali.iojbl.cn/Article/details/gtnkvfsdhq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.redwolf501.top/Article/details/gtvqizuxdd.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hnqzz.top/Article/details/gtavqtzalk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nanxinkj.top/Article/details/gtuelncyov.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gtmezokzdg.html

[J08] 提取年月日与星期
来源：http://dali.guannengcc.top/Article/details/gtzfdmhmqo.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.aibaodan.cn/Article/details/gtgcqgkrco.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.tian-w.cn/Article/details/gtjmfcpfdq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.haohaochexian.top/Article/details/gtqvcypwbu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.andypj.xyz/Article/details/gtvwkpkiep.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.tianlin.xyz/Article/details/gtpyyxfqal.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hnqzz.top/Article/details/gtqivswaou.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gotoacloud.top/Article/details/gtoylohklf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xylfe.cn/Article/details/gtxvaqoesr.html

[J09] 时区处理
来源：http://dali.xuetiantiany.cn/Article/details/gtwacyyooz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hysaishi.cn/Article/details/gtofbuujkt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yanxiufei.cn/Article/details/gtsdldxibm.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jyoumei.cn/Article/details/gtgcftotiw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhixingplan.top/Article/details/gtvkenuupx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ydzc1.top/Article/details/gtxchnkxlr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yvedp.cn/Article/details/gtjfjdaubt.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gzhubu.top/Article/details/gtxiclosag.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gogol.net.cn/Article/details/gthcuyzakf.html

[J10] 取今天 / 本月第一天
来源：http://dali.bjfxy.top/Article/details/gtlzkivqtz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.havefunace.top/Article/details/gtninnvdqk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nanxinkj.top/Article/details/gthienxbhq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.mhx1999.top/Article/details/gtgblfuwgx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ehwqpu.com/Article/details/gtnoymklmq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sxryk.cn/Article/details/gtzysbzmji.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.tianlin.xyz/Article/details/gtbsvcgrrw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinqigufen.top/Article/details/gtryrazpre.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj202588.top/Article/details/gtlnuzpiah.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtnxghpvnj.html

K. JSON 与序列化
来源：http://dali.0kj1m.cn/Article/details/gtreowllvi.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtvfxtxzhl.html

[K01] 对象转 JSON 字符串
来源：http://dali.cashguo.top/Article/details/gtghhvqgem.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xziqi.cn/Article/details/gttswitaey.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.kuanghao11.cn/Article/details/gtmrryxrlr.html

JS:   JSON.stringify(obj)
来源：http://dali.jqgfzy.top/Article/details/gtetpovyge.html

TS:   JSON.stringify(obj)
来源：http://dali.zhengqikj.top/Article/details/gtxqikpxix.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.guannengcc.top/Article/details/gtgpvuwbmf.html

Go:   json.Marshal(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtsaknzacd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.feifeiyinyue.top/Article/details/gtswgmqvxf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtempmkijq.html

[K02] JSON 字符串转对象
来源：http://dali.cqqwz.cn/Article/details/gtkdedmrbn.html

Py:   json.loads(s)
来源：http://dali.yueranfly.top/Article/details/gtrmtiogfg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yj202588.top/Article/details/gtywyyuoms.html

JS:   JSON.parse(s)
来源：http://dali.gogol.net.cn/Article/details/gtgdkbfdxy.html

TS:   JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gtrfuyovjl.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.fzhhl.top/Article/details/gttghtusfu.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhiwuduotai.top/Article/details/gtcuvbseql.html

Ruby: JSON.parse(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtcxkdxmbb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cashguo.top/Article/details/gtzwefzqrh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.0kj1m.cn/Article/details/gtvxftcgdq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.tianlin.xyz/Article/details/gtmnrcgdor.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtukqdixzv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgfzy.top/Article/details/gtybcnphno.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnqzz.top/Article/details/gtvpkapsxo.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtiigoeeqb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yj202588.top/Article/details/gtwvhnarvi.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhixingplan.top/Article/details/gtvdttppvv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tanke756.top/Article/details/gtpupghjak.html

[K04] 读取 JSON 文件
来源：http://dali.daxiang520.top/Article/details/gtxzfjvbiy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gogol.net.cn/Article/details/gtrvnzbirx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gaohongyu789.top/Article/details/gtdtacuxxs.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aibaodan.cn/Article/details/gtrbwsbmmm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xinyue.icu/Article/details/gtemfknbkv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.daria6918.cn/Article/details/gthljsmllp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gtyrkyzcie.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhixingplan.top/Article/details/gtgeuqucos.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.feifeiyinyue.top/Article/details/gtbuoizoqh.html

[K05] 深拷贝对象
来源：http://dali.chenlongwang.top/Article/details/gttrdokibm.html

Py:   copy.deepcopy(obj)
来源：http://dali.fzhhl.top/Article/details/gtpffbyzdn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinqigufen.top/Article/details/gtmyeacezd.html

JS:   structuredClone(obj)
来源：http://dali.hysaishi.cn/Article/details/gtpzstlfhw.html

TS:   structuredClone(obj)
来源：http://dali.haohaochexian.top/Article/details/gtwzihmcsz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jyoumei.cn/Article/details/gtgxwnevpy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cashguo.top/Article/details/gtmodvgcse.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpcqncfts.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.guannengcc.top/Article/details/gtkzpwvvgv.html

[K06] 解析 URL 查询串
来源：http://dali.hfpthk.cn/Article/details/gteowjzgde.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.daxiang520.top/Article/details/gtikdmnngw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.fzhhl.top/Article/details/gtebhjhyxd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shangyingyoupin.top/Article/details/gtmbwmlwby.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cdnleiting.top/Article/details/gtlzbdicrv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.feifeiyinyue.top/Article/details/gthoyehixs.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcgrvjuqn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gttbdykajy.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhongyouzk.top/Article/details/gtrbzkhadr.html

[K07] 进制转换
来源：http://dali.gogol.net.cn/Article/details/gtwfuxnixr.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtvvizynbq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.pengpengdd.cyou/Article/details/gtqgzoyygh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gtdpowebvf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gtvymkpusj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtcjmegsmx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.daxiang520.top/Article/details/gtfgsmnisu.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hongshengwenyu.top/Article/details/gteysptliv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yongpay.top/Article/details/gtbmucahzp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shanyushiyangtech.top/Article/details/gtbcqjpgfa.html

Py:   pickle.dumps(obj)
来源：http://dali.tanke756.top/Article/details/gtbbapmpem.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yvedp.cn/Article/details/gtmttinnjp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gtetcuvoac.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cdnleiting.top/Article/details/gtitnasdfq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.wangshuangyany.cn/Article/details/gtqcuahhlx.html

Go:   encoding/gob
来源：http://dali.xuetiantiany.cn/Article/details/gtgmvvzwvy.html

Ruby: Marshal.dump(obj)
来源：http://dali.hywenlv.cn/Article/details/gtjirgdqjt.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhiwuduotai.top/Article/details/gtldwnuepl.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gttkfsgzzs.html

L. 网络请求
来源：http://dali.yj202588.top/Article/details/gtvmpjsogw.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtedavijqe.html

[L01] 发送 GET 请求
来源：http://dali.cucudq.cn/Article/details/gtqzjjbyrb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhixingplan.top/Article/details/gtfhecsdcx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jianghu66.top/Article/details/gtyjtcxvvj.html

JS:   await fetch(url)
来源：http://dali.hammf.cn/Article/details/gtwjkxvcij.html

TS:   await fetch(url)
来源：http://dali.c1oappe.top/Article/details/gtewjhffyi.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.fzhhl.top/Article/details/gtpawapbag.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthzrlgsth.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.chenzaomai.com/Article/details/gtibbmbqcz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.daxiang520.top/Article/details/gtvpobafgd.html

[L02] 发送 POST JSON
来源：http://dali.hywenlv.cn/Article/details/gtsazhpeyb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.snrcjt.cn/Article/details/gtmqsagmoj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinqigfzy.top/Article/details/gtuhubuyzu.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtefvnwoxc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuxming.cn/Article/details/gtjrueqflk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhengqikj.top/Article/details/gtplsvlyyj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ybcxt.top/Article/details/gtzhptpqqf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.andypj.xyz/Article/details/gtyblqmbdd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.kuanghao11.cn/Article/details/gtqkwhfdfq.html

[L03] 设置自定义请求头
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnzzdodfr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.quarkkingdee.top/Article/details/gtfcrlgpzh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj20258.top/Article/details/gtxporwdhb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.mhx1999.top/Article/details/gtgrobmnvz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shzxlz.cn/Article/details/gtcdbyckru.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.dianchejie.cn/Article/details/gtyusooysr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.nanxinkj.top/Article/details/gtprmqxqny.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hnqzz.top/Article/details/gtapnwqaud.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlqudwelv.html

[L04] 设置超时
来源：http://dali.dashuyun.cn/Article/details/gtihxvwnbs.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ydzc1.top/Article/details/gtgnvyauyz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yangfankeji.com/Article/details/gtfwdqgxsw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.smart0.xyz/Article/details/gtcuxtatoi.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.birdmap.top/Article/details/gtzmlqblxq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zycfv.cn/Article/details/gtnftdqyru.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.svipenyu.cn/Article/details/gtrgjwcveb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yuanzhike.top/Article/details/gtexordfzs.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.nanxinkj.top/Article/details/gtslmwxbxn.html

[L05] 上传文件（multipart）
来源：http://dali.redwolf501.top/Article/details/gtotvitayh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jyoumei.cn/Article/details/gtwrxmbowf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gzhubu.top/Article/details/gtlgluiaom.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jyoumei.cn/Article/details/gthfdjywge.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gtwcklazei.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yonumen.top/Article/details/gtofqsorpy.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xziqi.cn/Article/details/gtefzpxczs.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.nwbrower.top/Article/details/gtupjoxprs.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyvbkfqkz.html

[L06] 解析响应为 JSON
来源：http://dali.jinqigufen.top/Article/details/gtghejihzm.html

Py:   resp.json()
来源：http://dali.haohaochexian.top/Article/details/gtrcehqjoo.html

PHP:  json_decode($body, true);
来源：http://dali.jqgfzy.top/Article/details/gttxtnptmi.html

JS:   await resp.json()
来源：http://dali.jyoumei.cn/Article/details/gtgkpmhatj.html

TS:   await resp.json()
来源：http://dali.sweek.top/Article/details/gtsarfhacd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hywenlv.cn/Article/details/gtgdcrxkej.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ehwqpu.com/Article/details/gtcmzihqcm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jqgfzy.top/Article/details/gtptkucsox.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.aizwys.cn/Article/details/gtiktkcnyg.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gtsbmgzowg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nanxuanxn.top/Article/details/gtwglnjqzx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtueulzcgn.html

JS:   resp.ok;  resp.status
来源：http://dali.ehwqpu.com/Article/details/gtugefvxvp.html

TS:   resp.ok;  resp.status
来源：http://dali.316326.xyz/Article/details/gtkbfxjflz.html

Java: resp.statusCode()
来源：http://dali.xuanzx.com/Article/details/gtwpateggd.html

Go:   resp.StatusCode
来源：http://dali.gaohongyu789.top/Article/details/gtueiqsrcr.html

Ruby: resp.code.to_i
来源：http://dali.fengsongda.top/Article/details/gtjjxvuznk.html

C#:   (int)resp.StatusCode
来源：http://dali.ydzc1.top/Article/details/gtpyawtzac.html

[L08] 并发请求多个地址
来源：http://dali.ehwqpu.com/Article/details/gtcdhgtvdz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yj20258888.top/Article/details/gttzcsehpg.html

PHP:  curl_multi_init() 系列
来源：http://dali.chenjidiqi.icu/Article/details/gtybobxfru.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jlsjyb.cn/Article/details/gtvpdcgamv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.iojbl.cn/Article/details/gtarqefucq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.c1oappe.top/Article/details/gtkwewaqvr.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhiwuduotai.top/Article/details/gtyrykphfi.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.daria6918.cn/Article/details/gtnbvmumhh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nanxinkj.top/Article/details/gtmefewtdc.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtmwltdyfm.html

M. 命令行 / 进程 / 环境
来源：http://dali.aizwys.cn/Article/details/gtmryypxqk.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtzibqwsgi.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gtmihqwepa.html

Py:   sys.argv[1:]
来源：http://dali.tian-w.cn/Article/details/gteucgmmoe.html

PHP:  $argv;  $argc;
来源：http://dali.svipenyu.cn/Article/details/gtplanlvts.html

JS:   process.argv.slice(2)
来源：http://dali.c1oappe.top/Article/details/gtmxilsnxa.html

TS:   process.argv.slice(2)
来源：http://dali.tian-w.cn/Article/details/gtvgxcjbfb.html

Java: args 数组（main 方法参数）
来源：http://dali.xinyue.icu/Article/details/gtndkigthk.html

Go:   os.Args[1:]
来源：http://dali.cdnleiting.top/Article/details/gtkbkaemqe.html

Ruby: ARGV
来源：http://dali.nanxuanxn.top/Article/details/gtmljegmss.html

C#:   args 数组（Main 方法参数）
来源：http://dali.c1oappe.top/Article/details/gthlilevkj.html

[M02] 读取环境变量
来源：http://dali.shangyingyoupin.top/Article/details/gtufkdkigy.html

Py:   os.environ.get("HOME")
来源：http://dali.ehwqpu.com/Article/details/gtjyhkflyr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yanxiufei.cn/Article/details/gtqfvakswv.html

JS:   process.env.HOME
来源：http://dali.havefunace.top/Article/details/gtwumvilye.html

TS:   process.env.HOME
来源：http://dali.ywan-chungtsiang.top/Article/details/gtswijcclb.html

Java: System.getenv("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gtthrprjgc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shuidangran.top/Article/details/gtumqirzue.html

Ruby: ENV["HOME"]
来源：http://dali.yanxiufei.cn/Article/details/gtwyimtmpg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.0kj1m.cn/Article/details/gtcmzjoraa.html

[M03] 执行外部命令
来源：http://dali.wangdashe.top/Article/details/gtqxtvczrt.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ybcxt.top/Article/details/gtbiolrswy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.quarkkingdee.top/Article/details/gtcipufcbq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.316326.xyz/Article/details/gtnaowkubs.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnqzz.top/Article/details/gtepwlhvji.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.smart0.xyz/Article/details/gtctultkul.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinghuilouyu.cn/Article/details/gtpeaakryd.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.aizwys.cn/Article/details/gtviddjerk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.feifeiyinyue.top/Article/details/gtnqknzuqd.html

[M04] 获取当前工作目录
来源：http://dali.gzhubu.top/Article/details/gtlambfuoc.html

Py:   os.getcwd()
来源：http://dali.cashguo.top/Article/details/gtwesdwhku.html

PHP:  getcwd();
来源：http://dali.hammf.cn/Article/details/gtojmmvlpm.html

JS:   process.cwd()
来源：http://dali.tian-w.cn/Article/details/gttcyedomm.html

TS:   process.cwd()
来源：http://dali.andypj.xyz/Article/details/gtycmiodor.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.wangdashe.top/Article/details/gtapnadmev.html

Go:   os.Getwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtehiqwesx.html

Ruby: Dir.pwd
来源：http://dali.jinghuilouyu.cn/Article/details/gtnywomzbc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hysaishi.cn/Article/details/gtfojdfuyg.html

[M05] 设置退出码
来源：http://dali.zhixingplan.top/Article/details/gttbwbvckc.html

Py:   sys.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtkgcogyby.html

PHP:  exit(1);
来源：http://dali.haohaochexian.top/Article/details/gtwixuhtff.html

JS:   process.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtvoidxnav.html

TS:   process.exit(1)
来源：http://dali.c1oappe.top/Article/details/gthessrgjj.html

Java: System.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gthgxdudjr.html

Go:   os.Exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gttavdustj.html

Ruby: exit 1
来源：http://dali.nanxinkj.top/Article/details/gtxeddoycg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nanxuanxn.top/Article/details/gtplaouymb.html

[M06] 向标准错误输出
来源：http://dali.shangyingyoupin.top/Article/details/gthhjojccp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yongpay.top/Article/details/gtggcbkrtm.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.feifeiyinyue.top/Article/details/gtrmfqsphi.html

JS:   console.error("err")
来源：http://dali.fengsongda.top/Article/details/gtewojdjio.html

TS:   console.error("err")
来源：http://dali.yanxiufei.cn/Article/details/gtkldiladp.html

Java: System.err.println("err")
来源：http://dali.sysykeji.top/Article/details/gtcvshfigc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jlsjyb.cn/Article/details/gtlzfqhvjy.html

Ruby: warn "err"
来源：http://dali.guowangkeji.top/Article/details/gtpnveydhh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gzhubu.top/Article/details/gtwchthzro.html

[M07] 判断是否为主入口
来源：http://dali.havefunace.top/Article/details/gtfonkojso.html

Py:   if __name__ == "__main__":
来源：http://dali.xuanzx.com/Article/details/gtklqjyloy.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.fengsongda.top/Article/details/gtimwhvlix.html

JS:   require.main === module
来源：http://dali.jinyuanbaomall.cn/Article/details/gthvmhvamu.html

TS:   require.main === module
来源：http://dali.sysykeji.top/Article/details/gtrwvucpjh.html

Java: public static void main(String[] args)
来源：http://dali.ehwqpu.com/Article/details/gtmejlxbbm.html

Go:   func main()
来源：http://dali.jiagoushi.top/Article/details/gtdnxhhmot.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhiwuduotai.top/Article/details/gtssrgfihl.html

C#:   static void Main(string[] args)
来源：http://dali.hysaishi.cn/Article/details/gtotzsbcdp.html

[M08] 获取系统与运行时信息
来源：http://dali.dashuyun.cn/Article/details/gtlbbqhklz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yuxming.cn/Article/details/gtfqwleonq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ydzc1.top/Article/details/gtqxroibum.html

JS:   process.platform;  process.version
来源：http://dali.dashuyun.cn/Article/details/gtobyhmwdr.html

TS:   process.platform;  process.version
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjeobfhvz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.316326.xyz/Article/details/gtwjdqjrjz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shangyingyoupin.top/Article/details/gtmhigrqwt.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.havefunace.top/Article/details/gtolzxmxti.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yj202588.top/Article/details/gttxtnxftz.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtcpfkkrke.html

N. 数据结构与算法
来源：http://dali.0kj1m.cn/Article/details/gtdgosepkv.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtfwtjshwu.html

[N01] 二分查找（有序数组）
来源：http://dali.smart0.xyz/Article/details/gtnbjdvngx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtgkruophi.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gtulfqkctm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangdashe.top/Article/details/gthaprluhv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xziqi.cn/Article/details/gtzkssgjid.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gtnzgkflir.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gthedxuzso.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hywenlv.cn/Article/details/gtojalslft.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtsthlevfi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hammf.cn/Article/details/gtnoriajnt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.iojbl.cn/Article/details/gtnoimfopj.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jqgufenzy.top/Article/details/gtmuasoybs.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guannengcc.top/Article/details/gtozbawjij.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.andypj.xyz/Article/details/gtbbhhipdo.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.svipenyu.cn/Article/details/gtknjsuctn.html

Go:   slices.Sort(arr)
来源：http://dali.redwolf501.top/Article/details/gtzisgdpqf.html

Ruby: arr.sort
来源：http://dali.meibo888.top/Article/details/gtgxosthsi.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zdqjudy.top/Article/details/gtuddltgbz.html

[N03] 快速排序（分治示例）
来源：http://dali.hnxiangtu.top/Article/details/gtsncaepil.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj20258888.top/Article/details/gtloouyxva.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hywenlv.cn/Article/details/gtagnnlhsj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dianchejie.cn/Article/details/gtjczdaryk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgfzy.top/Article/details/gttxhmubxp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yangfankeji.com/Article/details/gticiiypaf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhoulong.xyz/Article/details/gtoayzioke.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jianghu66.top/Article/details/gtwjbnsjet.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xziqi.cn/Article/details/gtrnxhumyi.html

[N04] 斐波那契数列
来源：http://dali.sweek.top/Article/details/gtuekdmkhp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.andypj.xyz/Article/details/gtsyefvwys.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sweek.top/Article/details/gtlmwzugnf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dashuyun.cn/Article/details/gtxlnniluu.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.316326.xyz/Article/details/gtvhtmlxpo.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yongpay.top/Article/details/gtgtmcppwy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.pengpengdd.cyou/Article/details/gtcjwfksrm.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yueranfly.top/Article/details/gtycrsktjs.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhongyouzk.top/Article/details/gtqpqiuyhi.html

[N05] 最大公约数
来源：http://dali.cqqwz.cn/Article/details/gtrzrluugg.html

Py:   math.gcd(a, b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtokknrnwh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gtpwxbreah.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nwbrower.top/Article/details/gtupcjncxf.html


<!-- 参考信息 -->