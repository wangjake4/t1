代发 wailian999

C#:   d1 < d2;  d1 == d2
来源：http://dali.haohaochexian.top/Article/details/gttvgrtsmc.html

[J08] 提取年月日与星期
来源：http://dali.xinyue.icu/Article/details/gtzpeamsol.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nanxinkj.top/Article/details/gtbaqhebny.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cqqwz.cn/Article/details/gtdjovgdzl.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenzaomai.com/Article/details/gtzfwrzacb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xziqi.cn/Article/details/gtnumstdsn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.chenzaomai.com/Article/details/gtmoucotcc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shangyingyoupin.top/Article/details/gtkkhnzhtn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gotoacloud.top/Article/details/gtteufnqcn.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sysykeji.top/Article/details/gtwzhmfthc.html

[J09] 时区处理
来源：http://dali.zhoulong.xyz/Article/details/gtxrlzgrgl.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yj202588.top/Article/details/gtmpmlfmyr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shanyushiyangtech.top/Article/details/gtvgruysti.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cheryme.top/Article/details/gtavjbvysh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnxiangtu.top/Article/details/gtadnjouqz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.dianchejie.cn/Article/details/gtunwrsrir.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hywenlv.cn/Article/details/gtbqrysyhf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.havefunace.top/Article/details/gtwaxaoicv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.svipenyu.cn/Article/details/gtmvebzstc.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhoulong.xyz/Article/details/gtcjviqhbb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xuetiantiany.cn/Article/details/gtiqdlxkal.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ybcxt.top/Article/details/gtpvvvynea.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.iojbl.cn/Article/details/gtjzmxcncb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqyftmuan.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hnxiangtu.top/Article/details/gtwzqktzxq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.tian-w.cn/Article/details/gtmvlexbjs.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.vqdsnc.cn/Article/details/gtembwjdhd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gogol.net.cn/Article/details/gtdfzxtufo.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtcnzlbsmf.html

K. JSON 与序列化
来源：http://dali.xylfe.cn/Article/details/gttmadewxh.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtoxjhumca.html

[K01] 对象转 JSON 字符串
来源：http://dali.hfpthk.cn/Article/details/gtmjndjhou.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.kuanghao11.cn/Article/details/gtsqadbhwa.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.dashuyun.cn/Article/details/gtpogweaer.html

JS:   JSON.stringify(obj)
来源：http://dali.pycfn.com/Article/details/gtjdfkeqkc.html

TS:   JSON.stringify(obj)
来源：http://dali.tian-w.cn/Article/details/gtsaiqckko.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cucudq.cn/Article/details/gtgvkpcxhw.html

Go:   json.Marshal(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtslwimaah.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shuidangran.top/Article/details/gtdhtzpeva.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yj20258.top/Article/details/gtwehxvswm.html

[K02] JSON 字符串转对象
来源：http://dali.tian-w.cn/Article/details/gtsqmicheb.html

Py:   json.loads(s)
来源：http://dali.hnxiangtu.top/Article/details/gtqvwiesqn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tanke756.top/Article/details/gtvbhsezmx.html

JS:   JSON.parse(s)
来源：http://dali.havefunace.top/Article/details/gtaiwddgkm.html

TS:   JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtcewvxnaw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hnqzz.top/Article/details/gtfsgzmxic.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.iojbl.cn/Article/details/gtbmgxvpgg.html

Ruby: JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gtbltnsknp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.chenlongwang.top/Article/details/gtzbgliafz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.kuanghao11.cn/Article/details/gtqddjbobj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hnxiangtu.top/Article/details/gthvznytpm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.smart0.xyz/Article/details/gtoavhiare.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtsohbiqls.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xinyue.icu/Article/details/gtvbrxqsjn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shzxlz.cn/Article/details/gttmdfozfd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ppjwa.cn/Article/details/gtmtabptai.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtxivycgbx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjckcudfj.html

[K04] 读取 JSON 文件
来源：http://dali.hnxiangtu.top/Article/details/gtmlujzoel.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhiwuduotai.top/Article/details/gtfvpxysyu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cheryme.top/Article/details/gtphhfsbox.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.bjfxy.top/Article/details/gtggyvzhuy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.bjfxy.top/Article/details/gtqfppgzmk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gtufsxnnuq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.iojbl.cn/Article/details/gtfxzdlylv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jqgufenzy.top/Article/details/gtnrhymtmi.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yueranfly.top/Article/details/gtxeulrzbo.html

[K05] 深拷贝对象
来源：http://dali.yuxming.cn/Article/details/gtlxwivknc.html

Py:   copy.deepcopy(obj)
来源：http://dali.yongpay.top/Article/details/gtopwqhalj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shangyingyoupin.top/Article/details/gtrqhrtnlw.html

JS:   structuredClone(obj)
来源：http://dali.gogol.net.cn/Article/details/gtljlhmlsr.html

TS:   structuredClone(obj)
来源：http://dali.yj202588.top/Article/details/gttkppunkq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvmgfmsxv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhengqikj.top/Article/details/gtexdgtuml.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gogol.net.cn/Article/details/gtjtpfsvzq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sufxvd.cn/Article/details/gttefqljnr.html

[K06] 解析 URL 查询串
来源：http://dali.shzxlz.cn/Article/details/gtbukdglwd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.wangshuangyany.cn/Article/details/gttafgocpr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.tanke756.top/Article/details/gtdeqhmarm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnxiangtu.top/Article/details/gthopuyfaw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuanzhike.top/Article/details/gtvsbsmkih.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.vqdsnc.cn/Article/details/gtkqpfzsfo.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gtwzmombnu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.guannengcc.top/Article/details/gtfynjfyae.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gthmfryqwg.html

[K07] 进制转换
来源：http://dali.yonumen.top/Article/details/gtdoxqtbjz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gttklgmbtf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigfzy.top/Article/details/gtquzzabhb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gtswsabtmc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtrotdbhbn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gtocsqdchg.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gogol.net.cn/Article/details/gtnkziszuz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuklxpmvv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gtzzbiuewo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhoulong.xyz/Article/details/gtdjsymcrh.html

Py:   pickle.dumps(obj)
来源：http://dali.cqqwz.cn/Article/details/gttlzqkvlp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.redwolf501.top/Article/details/gtazslswls.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhongyouzk.top/Article/details/gtrxxcxtmm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.meibo888.top/Article/details/gtygtycjqo.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yueranfly.top/Article/details/gtxpedqdwf.html

Go:   encoding/gob
来源：http://dali.nanxinkj.top/Article/details/gterahftiz.html

Ruby: Marshal.dump(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtqorauobw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.daxiang520.top/Article/details/gtxfrvowzm.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtdczsllov.html

L. 网络请求
来源：http://dali.ehwqpu.com/Article/details/gtnffyfgzl.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtuorkorhk.html

[L01] 发送 GET 请求
来源：http://dali.hysaishi.cn/Article/details/gtfxwtwwrw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yongpay.top/Article/details/gthfuoblqr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.feifeiyinyue.top/Article/details/gtjuhrashy.html

JS:   await fetch(url)
来源：http://dali.fengsongda.top/Article/details/gtobqjarnk.html

TS:   await fetch(url)
来源：http://dali.yvedp.cn/Article/details/gtpagpkyeu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.nanxuanxn.top/Article/details/gtsgraprcm.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjyieepcw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cucudq.cn/Article/details/gtntxxelmw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zycfv.cn/Article/details/gtvywlpouo.html

[L02] 发送 POST JSON
来源：http://dali.daxiang520.top/Article/details/gtplllouci.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinqigufen.top/Article/details/gtzwluembk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gogol.net.cn/Article/details/gtprpblweu.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenlongwang.top/Article/details/gtyxidmkhf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cucudq.cn/Article/details/gtmkwvhigl.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.tian-w.cn/Article/details/gttuvojeox.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.guowangkeji.top/Article/details/gtwvlxvzmy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.snrcjt.cn/Article/details/gtsrxjxeez.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.iojbl.cn/Article/details/gthaxwvmnd.html

[L03] 设置自定义请求头
来源：http://dali.havefunace.top/Article/details/gtefosftsy.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yj202588.top/Article/details/gtxijeucvq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzhpzttkm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yonumen.top/Article/details/gtamebionn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sweek.top/Article/details/gtvwkxhfxa.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jlsjyb.cn/Article/details/gtazzumwcp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yj20258.top/Article/details/gthvaabzfr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gogol.net.cn/Article/details/gtvapwgtmf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ybcxt.top/Article/details/gtszcqjlol.html

[L04] 设置超时
来源：http://dali.xuetiantiany.cn/Article/details/gtbpklfllo.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ydzc1.top/Article/details/gtoyirpsgt.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.smart0.xyz/Article/details/gtezwbxxbk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dashuyun.cn/Article/details/gtosqiuwmu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yvedp.cn/Article/details/gtbtllrcjt.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shuidangran.top/Article/details/gtdsmfbbye.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hongshengwenyu.top/Article/details/gthpgosepu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gotoacloud.top/Article/details/gtjhplhhzn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhengqikj.top/Article/details/gtahayqfyp.html

[L05] 上传文件（multipart）
来源：http://dali.snrcjt.cn/Article/details/gtvsxupogz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.guowangkeji.top/Article/details/gtwjguxwxh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jiagoushi.top/Article/details/gtkooysbrk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gogol.net.cn/Article/details/gttjhvpcfe.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yongpay.top/Article/details/gtyzcogfvf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jlsjyb.cn/Article/details/gtabvioqpx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtldjdlcbw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.wangdashe.top/Article/details/gttsxtsfmv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtufmoktsb.html

[L06] 解析响应为 JSON
来源：http://dali.tian-w.cn/Article/details/gtjbbcapuj.html

Py:   resp.json()
来源：http://dali.sweek.top/Article/details/gtnggxhyra.html

PHP:  json_decode($body, true);
来源：http://dali.dashuyun.cn/Article/details/gteqtdxvup.html

JS:   await resp.json()
来源：http://dali.cheryme.top/Article/details/gtgmbrvcgn.html

TS:   await resp.json()
来源：http://dali.yj202588.top/Article/details/gtudmprbgb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ydzc1.top/Article/details/gtdoqmffdo.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shuidangran.top/Article/details/gtkubrzbtj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xuanzx.com/Article/details/gtpxsnoygg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jiagoushi.top/Article/details/gtylpkbfoa.html

[L07] 处理 HTTP 状态码
来源：http://dali.nanxinkj.top/Article/details/gtkxhvldox.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jqgfzy.top/Article/details/gtomwlqrpz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenlongwang.top/Article/details/gtiuxogljc.html

JS:   resp.ok;  resp.status
来源：http://dali.sufxvd.cn/Article/details/gtxyepynwq.html

TS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxcgoemzz.html

Java: resp.statusCode()
来源：http://dali.wangdashe.top/Article/details/gtusqiwhrm.html

Go:   resp.StatusCode
来源：http://dali.zhengqikj.top/Article/details/gtqqjawoee.html

Ruby: resp.code.to_i
来源：http://dali.gaohongyu789.top/Article/details/gtrmywbswf.html

C#:   (int)resp.StatusCode
来源：http://dali.wangshuangyany.cn/Article/details/gtgkphssnj.html

[L08] 并发请求多个地址
来源：http://dali.sxryk.cn/Article/details/gtsjkeawzd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sysykeji.top/Article/details/gtyeohdatz.html

PHP:  curl_multi_init() 系列
来源：http://dali.daria6918.cn/Article/details/gtruzsrxfe.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shangyingyoupin.top/Article/details/gtonxggvjw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gotoacloud.top/Article/details/gtscymsctq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shuidangran.top/Article/details/gtpgbzciuj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gaohongyu789.top/Article/details/gtjxzanldk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.nanxinkj.top/Article/details/gtsgakkmnk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoztqgyan.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtacmxunhf.html

M. 命令行 / 进程 / 环境
来源：http://dali.kuanghao11.cn/Article/details/gtrkrzpbub.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtnontoldw.html

[M01] 读取命令行参数
来源：http://dali.sysykeji.top/Article/details/gtkilqbbyg.html

Py:   sys.argv[1:]
来源：http://dali.sweek.top/Article/details/gtqkpdhqxb.html

PHP:  $argv;  $argc;
来源：http://dali.yj20258.top/Article/details/gtavahjqfh.html

JS:   process.argv.slice(2)
来源：http://dali.yanxiufei.cn/Article/details/gtxpelmsnc.html

TS:   process.argv.slice(2)
来源：http://dali.birdmap.top/Article/details/gtfqsatoaz.html

Java: args 数组（main 方法参数）
来源：http://dali.sysykeji.top/Article/details/gtgqicskvd.html

Go:   os.Args[1:]
来源：http://dali.0kj1m.cn/Article/details/gtssowlyet.html

Ruby: ARGV
来源：http://dali.guannengcc.top/Article/details/gttitnoqul.html

C#:   args 数组（Main 方法参数）
来源：http://dali.wangdashe.top/Article/details/gtrqszcruq.html

[M02] 读取环境变量
来源：http://dali.dashuyun.cn/Article/details/gtajxdwlnh.html

Py:   os.environ.get("HOME")
来源：http://dali.yvedp.cn/Article/details/gtugkkkkrt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlkzoworx.html

JS:   process.env.HOME
来源：http://dali.wangshuangyany.cn/Article/details/gtjaeqtrua.html

TS:   process.env.HOME
来源：http://dali.zhixingplan.top/Article/details/gtmvheqrye.html

Java: System.getenv("HOME")
来源：http://dali.hammf.cn/Article/details/gtybpykvci.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gttmcbbzvu.html

Ruby: ENV["HOME"]
来源：http://dali.jyoumei.cn/Article/details/gtkpoijsvr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.daxiang520.top/Article/details/gtkslchkch.html

[M03] 执行外部命令
来源：http://dali.jianghu66.top/Article/details/gtfiardjeo.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.birdmap.top/Article/details/gtwyeadlsp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.haohaochexian.top/Article/details/gtwiprzjml.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.aizwys.cn/Article/details/gtmkoavfod.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtgyspxdmq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhoulong.xyz/Article/details/gtjjuspzui.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.pengpengdd.cyou/Article/details/gturwzqwtt.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.pycfn.com/Article/details/gtqnetndqk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtimwuaerm.html

[M04] 获取当前工作目录
来源：http://dali.ydzc1.top/Article/details/gtmcbwzngd.html

Py:   os.getcwd()
来源：http://dali.hnxiangtu.top/Article/details/gtuihpsmxq.html

PHP:  getcwd();
来源：http://dali.kuanghao11.cn/Article/details/gtxbvbgtsc.html

JS:   process.cwd()
来源：http://dali.yonumen.top/Article/details/gtwbbupqzl.html

TS:   process.cwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gtfhncjefx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jqgufenzy.top/Article/details/gtnkvejgfk.html

Go:   os.Getwd()
来源：http://dali.meibo888.top/Article/details/gtwtaoiwmn.html

Ruby: Dir.pwd
来源：http://dali.daria6918.cn/Article/details/gtnskmrkro.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.9152youxi.cn/Article/details/gteodeetfs.html

[M05] 设置退出码
来源：http://dali.zhengqikj.top/Article/details/gtfwfwezfv.html

Py:   sys.exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gthmsjivcp.html

PHP:  exit(1);
来源：http://dali.zhengqikj.top/Article/details/gtcnvdrzkn.html

JS:   process.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gtudlblevp.html

TS:   process.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkptntdnq.html

Java: System.exit(1)
来源：http://dali.cashguo.top/Article/details/gtexiikzus.html

Go:   os.Exit(1)
来源：http://dali.c1oappe.top/Article/details/gtzzvadxup.html

Ruby: exit 1
来源：http://dali.jianghu66.top/Article/details/gtrekaprwz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.havefunace.top/Article/details/gtfocuosho.html

[M06] 向标准错误输出
来源：http://dali.dashuyun.cn/Article/details/gtdjigcbud.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwdudotce.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ehwqpu.com/Article/details/gtxefwjjty.html

JS:   console.error("err")
来源：http://dali.wangshuangyany.cn/Article/details/gtdjbwjqzk.html

TS:   console.error("err")
来源：http://dali.haohaochexian.top/Article/details/gtdmszfhmv.html

Java: System.err.println("err")
来源：http://dali.meibo888.top/Article/details/gtgvnsimms.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.tian-w.cn/Article/details/gtidfigqls.html

Ruby: warn "err"
来源：http://dali.chenzaomai.com/Article/details/gtktfpwmnv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xylfe.cn/Article/details/gtbrhzsulf.html

[M07] 判断是否为主入口
来源：http://dali.jiagoushi.top/Article/details/gtsqlmclbp.html

Py:   if __name__ == "__main__":
来源：http://dali.hysaishi.cn/Article/details/gtisavromn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxptabxqf.html

JS:   require.main === module
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlkfdfjld.html

TS:   require.main === module
来源：http://dali.ydzc1.top/Article/details/gtgukhikne.html

Java: public static void main(String[] args)
来源：http://dali.zhiwuduotai.top/Article/details/gtstwrbwby.html

Go:   func main()
来源：http://dali.dianchejie.cn/Article/details/gtbuytbyvn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.wangdashe.top/Article/details/gtveatywrn.html

C#:   static void Main(string[] args)
来源：http://dali.jinqigfzy.top/Article/details/gtgduzbpzu.html

[M08] 获取系统与运行时信息
来源：http://dali.ybcxt.top/Article/details/gtiporeqlr.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinqigufen.top/Article/details/gtyfpibept.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.dashuyun.cn/Article/details/gttjvjtjlj.html

JS:   process.platform;  process.version
来源：http://dali.zycfv.cn/Article/details/gtbfulnlis.html

TS:   process.platform;  process.version
来源：http://dali.chenlongwang.top/Article/details/gtsxtptydp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yongpay.top/Article/details/gtzpmkeesm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jiagoushi.top/Article/details/gtqssdoyho.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.fengsongda.top/Article/details/gtcacvnrvc.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hnxiangtu.top/Article/details/gtuhyoxtbf.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtkayqfohe.html

N. 数据结构与算法
来源：http://dali.hysaishi.cn/Article/details/gtzmhobsqi.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gttiasfbsi.html

[N01] 二分查找（有序数组）
来源：http://dali.daria6918.cn/Article/details/gtxwvdlsgd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gtrrlmcxpn.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yangfankeji.com/Article/details/gtrnxkburi.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cashguo.top/Article/details/gtsqmlhxgr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ehwqpu.com/Article/details/gtgrztyzlq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtemobddel.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjeunbvyu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.feifeiyinyue.top/Article/details/gtydfqlyub.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtczwammzy.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.316326.xyz/Article/details/gtedokcyri.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.316326.xyz/Article/details/gtchuculpr.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yuxming.cn/Article/details/gtprdsfayr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pengpengdd.cyou/Article/details/gtigpjgusq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daria6918.cn/Article/details/gtoobowhpz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.redwolf501.top/Article/details/gtguhdkihr.html

Go:   slices.Sort(arr)
来源：http://dali.ydzc1.top/Article/details/gtodwntwjy.html

Ruby: arr.sort
来源：http://dali.xziqi.cn/Article/details/gtdavzcuam.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gtipihbaqc.html

[N03] 快速排序（分治示例）
来源：http://dali.hfpthk.cn/Article/details/gtblipglrj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.birdmap.top/Article/details/gttumlhqxl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yonumen.top/Article/details/gtygrhliva.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shuidangran.top/Article/details/gtjhrextyb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ppjwa.cn/Article/details/gtkxfhnlmo.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.daria6918.cn/Article/details/gtokknlwlz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jianghu66.top/Article/details/gtfqromazm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.mhx1999.top/Article/details/gtoedhiqsh.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenjidiqi.icu/Article/details/gtrgtrwzjr.html

[N04] 斐波那契数列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsdkubeel.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cashguo.top/Article/details/gtzrxklixb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhixingplan.top/Article/details/gthzbkjcki.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ppjwa.cn/Article/details/gtcypggfwr.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.smart0.xyz/Article/details/gtgvovihqd.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhengqikj.top/Article/details/gtagitdeix.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yongpay.top/Article/details/gtltkvabiz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.meibo888.top/Article/details/gtnzvgjpez.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gtauajfuud.html

[N05] 最大公约数
来源：http://dali.cucudq.cn/Article/details/gtxtimditk.html

Py:   math.gcd(a, b)
来源：http://dali.zdqjudy.top/Article/details/gtmncblfbc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ybcxt.top/Article/details/gtbojvdaag.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ppjwa.cn/Article/details/gtmxeoahft.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.svipenyu.cn/Article/details/gttmozveec.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hongshengwenyu.top/Article/details/gtxqwpqtlb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yongpay.top/Article/details/gtuudqbvff.html

Ruby: a.gcd(b)
来源：http://dali.iojbl.cn/Article/details/gtmxgqegun.html


<!-- 参考信息 -->