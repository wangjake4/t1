代发 wailian999

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhixingplan.top/Article/details/gtynhqrgfy.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shanyushiyangtech.top/Article/details/gtxoepqimz.html

[J09] 时区处理
来源：http://dali.gzhubu.top/Article/details/gtxchgpvgf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.quarkkingdee.top/Article/details/gtxtodtnxy.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zdqjudy.top/Article/details/gtlbqopjmk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258.top/Article/details/gtzuonapum.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sweek.top/Article/details/gtavhseaik.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.aizwys.cn/Article/details/gtjimuqryb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shuidangran.top/Article/details/gtuchhkgth.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.316326.xyz/Article/details/gtkxlbbtkw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhixingplan.top/Article/details/gtvoveztyj.html

[J10] 取今天 / 本月第一天
来源：http://dali.hysaishi.cn/Article/details/gtzlovnfjy.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.iojbl.cn/Article/details/gtecjmtzto.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zdqjudy.top/Article/details/gtmoyfucce.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cheryme.top/Article/details/gtcnlboloq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.wangdashe.top/Article/details/gtthcwzfgx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jqgfzy.top/Article/details/gtzlxyaghw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.redwolf501.top/Article/details/gtwxkbyhgr.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cheryme.top/Article/details/gtuvqwzdzv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.vqdsnc.cn/Article/details/gtvqkhalvp.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtsbqntfmp.html

K. JSON 与序列化
来源：http://dali.hysaishi.cn/Article/details/gtjpauvzan.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtevlsqeor.html

[K01] 对象转 JSON 字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtcfoiwvwt.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.fzhhl.top/Article/details/gtebsrkldx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jyoumei.cn/Article/details/gtlqvnznot.html

JS:   JSON.stringify(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtgssbegsv.html

TS:   JSON.stringify(obj)
来源：http://dali.jiagoushi.top/Article/details/gtiodievhq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.meibo888.top/Article/details/gtknflbdny.html

Go:   json.Marshal(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtdhakkkum.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.kuanghao11.cn/Article/details/gtrnsayxnn.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sufxvd.cn/Article/details/gtmkuugkid.html

[K02] JSON 字符串转对象
来源：http://dali.wangshuangyany.cn/Article/details/gttqrlrvvn.html

Py:   json.loads(s)
来源：http://dali.yueranfly.top/Article/details/gtdrnjtrhk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.9152youxi.cn/Article/details/gtrkgwphts.html

JS:   JSON.parse(s)
来源：http://dali.jqgfzy.top/Article/details/gtoxrxehkz.html

TS:   JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gtjoauvqco.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinqigufen.top/Article/details/gtqvmmpmyv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xinyue.icu/Article/details/gtdtjurbth.html

Ruby: JSON.parse(s)
来源：http://dali.yj202588.top/Article/details/gtvzzqpymm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.havefunace.top/Article/details/gtvdugdvqo.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zdqjudy.top/Article/details/gtycztemfj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yonumen.top/Article/details/gtpvfujmdq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yj202588.top/Article/details/gtxcnmsvuz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxuanxn.top/Article/details/gtiqflvlpk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hywenlv.cn/Article/details/gtfpmmzqzv.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtccvoemil.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhiwuduotai.top/Article/details/gtwlxovkta.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sufxvd.cn/Article/details/gtgoaepjzh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ehwqpu.com/Article/details/gtdojwduwi.html

[K04] 读取 JSON 文件
来源：http://dali.feifeiyinyue.top/Article/details/gtlyuotjpp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.316326.xyz/Article/details/gtshmiagdp.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yuanzhike.top/Article/details/gtmuwkpvcd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ydzc1.top/Article/details/gtayhlgjcg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ybcxt.top/Article/details/gtytgucddw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gtvlkypznk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.guowangkeji.top/Article/details/gturofhiga.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.snrcjt.cn/Article/details/gtsabjsmof.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.0kj1m.cn/Article/details/gtlhaucmkj.html

[K05] 深拷贝对象
来源：http://dali.cheryme.top/Article/details/gtthymzbwf.html

Py:   copy.deepcopy(obj)
来源：http://dali.sufxvd.cn/Article/details/gtcyvmrvut.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yongpay.top/Article/details/gtzjekmoxb.html

JS:   structuredClone(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtrhqrzjmz.html

TS:   structuredClone(obj)
来源：http://dali.quarkkingdee.top/Article/details/gthftabgcm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.pengpengdd.cyou/Article/details/gtffyegqft.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqouvogsv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sufxvd.cn/Article/details/gtvntaortb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.svipenyu.cn/Article/details/gttnnwczav.html

[K06] 解析 URL 查询串
来源：http://dali.yanxiufei.cn/Article/details/gtiflaojya.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.andypj.xyz/Article/details/gthuwczbos.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.guowangkeji.top/Article/details/gtemgazork.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yongpay.top/Article/details/gtyihtjegj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zycfv.cn/Article/details/gtjxofniqn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.daxiang520.top/Article/details/gtcytnposx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.redwolf501.top/Article/details/gtcctqwwwx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gtamobwzou.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gtmnoibrny.html

[K07] 进制转换
来源：http://dali.zhongyouzk.top/Article/details/gtbdhvajhy.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gtbifanvsm.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tian-w.cn/Article/details/gtfusznbmq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgopdwuhd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtmzalqxrx.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.pycfn.com/Article/details/gtwrtnzolf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkuwutjcg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cdnleiting.top/Article/details/gtldiebezh.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtomzzqdnb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zycfv.cn/Article/details/gtcsvkbcmp.html

Py:   pickle.dumps(obj)
来源：http://dali.gogol.net.cn/Article/details/gtgsleorld.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ehwqpu.com/Article/details/gtwihwpgwa.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ppjwa.cn/Article/details/gtdkqdmzyd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gaohongyu789.top/Article/details/gtykodlzgl.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ivvv.top/Article/details/gthstgetev.html

Go:   encoding/gob
来源：http://dali.ivvv.top/Article/details/gtkonkedfv.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtufgenvnq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.kuanghao11.cn/Article/details/gttutqnrkz.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtglscgbdn.html

L. 网络请求
来源：http://dali.wangdashe.top/Article/details/gtefgqaobp.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtyhjqnamv.html

[L01] 发送 GET 请求
来源：http://dali.c1oappe.top/Article/details/gtvmoyeipx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cdnleiting.top/Article/details/gtdkumoscf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xinyue.icu/Article/details/gtrcpqvzpx.html

JS:   await fetch(url)
来源：http://dali.shuidangran.top/Article/details/gtfpedrwml.html

TS:   await fetch(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoquvwgrk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxlrwxkzx.html

Go:   resp, err := http.Get(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttoohxdrk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.dashuyun.cn/Article/details/gtwwhgrwsw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.haohaochexian.top/Article/details/gtdyesquju.html

[L02] 发送 POST JSON
来源：http://dali.cqqwz.cn/Article/details/gtnofzlqpw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xuanzx.com/Article/details/gttsyznzov.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhixingplan.top/Article/details/gtwiievnmi.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.iojbl.cn/Article/details/gtvsxjccaz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.havefunace.top/Article/details/gtjzcykirz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.quarkkingdee.top/Article/details/gtemxbkenu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hongshengwenyu.top/Article/details/gttstbbygx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hnqzz.top/Article/details/gtxezlglit.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hfpthk.cn/Article/details/gtsrhtkqlg.html

[L03] 设置自定义请求头
来源：http://dali.bjfxy.top/Article/details/gtewrpbukj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yj20258888.top/Article/details/gtslsguvmc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jyoumei.cn/Article/details/gtzifotmml.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258.top/Article/details/gtdcxkkwop.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhoulong.xyz/Article/details/gtyfbazinf.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ppjwa.cn/Article/details/gtovzmounh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.dashuyun.cn/Article/details/gtgzzblkox.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gzhubu.top/Article/details/gtxtvwffzg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gogol.net.cn/Article/details/gtirelcbgz.html

[L04] 设置超时
来源：http://dali.bjfxy.top/Article/details/gtoasvhnvl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.redwolf501.top/Article/details/gtxmxyudkl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xuetiantiany.cn/Article/details/gtwncgphno.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258888.top/Article/details/gtzjzyjvxm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxinkj.top/Article/details/gtvoplwpss.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.chenjidiqi.icu/Article/details/gtooyqosjh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.vqdsnc.cn/Article/details/gtktcpttkt.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yanxiufei.cn/Article/details/gtqaorovwq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ppjwa.cn/Article/details/gtikskqoyl.html

[L05] 上传文件（multipart）
来源：http://dali.yuxming.cn/Article/details/gtxfqlvkjz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.svipenyu.cn/Article/details/gtmuzximxw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cashguo.top/Article/details/gtaomrjjvk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hysaishi.cn/Article/details/gtblzkujuv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hysaishi.cn/Article/details/gtbnexswek.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cqqwz.cn/Article/details/gtisqiegch.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shangyingyoupin.top/Article/details/gtabmcfmau.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shanyushiyangtech.top/Article/details/gtdlmwfxbi.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsxxxmear.html

[L06] 解析响应为 JSON
来源：http://dali.haohaochexian.top/Article/details/gtlgwiplwr.html

Py:   resp.json()
来源：http://dali.andypj.xyz/Article/details/gtdabmtfnc.html

PHP:  json_decode($body, true);
来源：http://dali.haohaochexian.top/Article/details/gtzxhsmsef.html

JS:   await resp.json()
来源：http://dali.daxiang520.top/Article/details/gtzntbtcez.html

TS:   await resp.json()
来源：http://dali.yj20258888.top/Article/details/gturcpwosx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.tian-w.cn/Article/details/gtzuqqymmz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sufxvd.cn/Article/details/gtvqzbfyaj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.wangdashe.top/Article/details/gtqgbdygnv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmkmgkybs.html

[L07] 处理 HTTP 状态码
来源：http://dali.yanxiufei.cn/Article/details/gtzxysyhrd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhengqikj.top/Article/details/gtpfokcnib.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.haohaochexian.top/Article/details/gthugmbhns.html

JS:   resp.ok;  resp.status
来源：http://dali.zhongyouzk.top/Article/details/gtfycuihlt.html

TS:   resp.ok;  resp.status
来源：http://dali.jlsjyb.cn/Article/details/gtbycgvqzz.html

Java: resp.statusCode()
来源：http://dali.cucudq.cn/Article/details/gtxgxagiou.html

Go:   resp.StatusCode
来源：http://dali.ivvv.top/Article/details/gtkjbczjvj.html

Ruby: resp.code.to_i
来源：http://dali.0kj1m.cn/Article/details/gtskzflrlf.html

C#:   (int)resp.StatusCode
来源：http://dali.wangdashe.top/Article/details/gtvbnhhdmv.html

[L08] 并发请求多个地址
来源：http://dali.guannengcc.top/Article/details/gtptmgfmnj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cheryme.top/Article/details/gtbizcdojp.html

PHP:  curl_multi_init() 系列
来源：http://dali.9152youxi.cn/Article/details/gtdbgjqyva.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hammf.cn/Article/details/gtptgmtpgn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxuanxn.top/Article/details/gtkfoosqco.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.wangshuangyany.cn/Article/details/gtalaqwfjb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jianghu66.top/Article/details/gtegwwmzjn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yongpay.top/Article/details/gtzkltzzor.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.kuanghao11.cn/Article/details/gtkupycqvv.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtdegpfmey.html

M. 命令行 / 进程 / 环境
来源：http://dali.daxiang520.top/Article/details/gtzfvikhrt.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtjrvggjtm.html

[M01] 读取命令行参数
来源：http://dali.dianchejie.cn/Article/details/gtwigucdjw.html

Py:   sys.argv[1:]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgqiadagc.html

PHP:  $argv;  $argc;
来源：http://dali.chenlongwang.top/Article/details/gthxgwfgkd.html

JS:   process.argv.slice(2)
来源：http://dali.ydzc1.top/Article/details/gtxgpckqpa.html

TS:   process.argv.slice(2)
来源：http://dali.pycfn.com/Article/details/gtlkrpqpyd.html

Java: args 数组（main 方法参数）
来源：http://dali.ehwqpu.com/Article/details/gtbanoniud.html

Go:   os.Args[1:]
来源：http://dali.shzxlz.cn/Article/details/gtufdowojv.html

Ruby: ARGV
来源：http://dali.gzhubu.top/Article/details/gtvtxncfam.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yanxiufei.cn/Article/details/gtluburasi.html

[M02] 读取环境变量
来源：http://dali.ybcxt.top/Article/details/gtohylpzep.html

Py:   os.environ.get("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxzvckiaq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cqqwz.cn/Article/details/gtudkscjpn.html

JS:   process.env.HOME
来源：http://dali.snrcjt.cn/Article/details/gtzmtzzkuo.html

TS:   process.env.HOME
来源：http://dali.9152youxi.cn/Article/details/gtkqcbbwtu.html

Java: System.getenv("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gtuvpupaax.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gtlsrckryt.html

Ruby: ENV["HOME"]
来源：http://dali.kuanghao11.cn/Article/details/gtfykmaexe.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gtblclchcn.html

[M03] 执行外部命令
来源：http://dali.cucudq.cn/Article/details/gtkmimknzk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.fzhhl.top/Article/details/gtgydyuuam.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.snrcjt.cn/Article/details/gtgqicnhxr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangdashe.top/Article/details/gtpolztzbu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxuanxn.top/Article/details/gtwimpeail.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cqqwz.cn/Article/details/gtrkbfigfy.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jianghu66.top/Article/details/gtnuptkalu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shanyushiyangtech.top/Article/details/gtsfowbnlu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.guowangkeji.top/Article/details/gtxvifrrwf.html

[M04] 获取当前工作目录
来源：http://dali.yj202588.top/Article/details/gtqcjeoubk.html

Py:   os.getcwd()
来源：http://dali.chenzaomai.com/Article/details/gttbqzdkcg.html

PHP:  getcwd();
来源：http://dali.zhixingplan.top/Article/details/gtvynazltn.html

JS:   process.cwd()
来源：http://dali.316326.xyz/Article/details/gtxbaerwhu.html

TS:   process.cwd()
来源：http://dali.hysaishi.cn/Article/details/gtpdjtenyr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.wangdashe.top/Article/details/gtvyharwev.html

Go:   os.Getwd()
来源：http://dali.chenjidiqi.icu/Article/details/gtaalpedvv.html

Ruby: Dir.pwd
来源：http://dali.nanxinkj.top/Article/details/gtglhjlisv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ppjwa.cn/Article/details/gtvviwgviq.html

[M05] 设置退出码
来源：http://dali.shuidangran.top/Article/details/gtjzioqcff.html

Py:   sys.exit(1)
来源：http://dali.guannengcc.top/Article/details/gtmttngncf.html

PHP:  exit(1);
来源：http://dali.jiagoushi.top/Article/details/gthwbphxft.html

JS:   process.exit(1)
来源：http://dali.wangdashe.top/Article/details/gteadwqabb.html

TS:   process.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtnjtsrlox.html

Java: System.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gthvfsqnej.html

Go:   os.Exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtvejdyshr.html

Ruby: exit 1
来源：http://dali.hfpthk.cn/Article/details/gtlpuxexrf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ehwqpu.com/Article/details/gtljvmpirk.html

[M06] 向标准错误输出
来源：http://dali.yvedp.cn/Article/details/gtfacxatte.html

Py:   print("err", file=sys.stderr)
来源：http://dali.daxiang520.top/Article/details/gtqtcohunz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhiwuduotai.top/Article/details/gtsxntjndz.html

JS:   console.error("err")
来源：http://dali.sweek.top/Article/details/gtsfbjmcdi.html

TS:   console.error("err")
来源：http://dali.yj20258.top/Article/details/gtvlwkdobx.html

Java: System.err.println("err")
来源：http://dali.bjfxy.top/Article/details/gtvodrhfge.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ivvv.top/Article/details/gthxouxtvb.html

Ruby: warn "err"
来源：http://dali.yangfankeji.com/Article/details/gtvyexvrzn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nwbrower.top/Article/details/gtmzddwwbv.html

[M07] 判断是否为主入口
来源：http://dali.chenzaomai.com/Article/details/gtyvibvgvx.html

Py:   if __name__ == "__main__":
来源：http://dali.tanke756.top/Article/details/gtntqvygwa.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinqigfzy.top/Article/details/gtaaouexxp.html

JS:   require.main === module
来源：http://dali.redwolf501.top/Article/details/gtblxwnaii.html

TS:   require.main === module
来源：http://dali.ywan-chungtsiang.top/Article/details/gtppjikqrl.html

Java: public static void main(String[] args)
来源：http://dali.xziqi.cn/Article/details/gtcnerrxsz.html

Go:   func main()
来源：http://dali.aibaodan.cn/Article/details/gtrlmgmagh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hammf.cn/Article/details/gtftunlnbv.html

C#:   static void Main(string[] args)
来源：http://dali.birdmap.top/Article/details/gtjayynavm.html

[M08] 获取系统与运行时信息
来源：http://dali.wangdashe.top/Article/details/gttwrmjabz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jqgfzy.top/Article/details/gttzqhkvwx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ivvv.top/Article/details/gtwujtocmg.html

JS:   process.platform;  process.version
来源：http://dali.dianchejie.cn/Article/details/gtolbbdgpj.html

TS:   process.platform;  process.version
来源：http://dali.ybcxt.top/Article/details/gtcothyecd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.pycfn.com/Article/details/gtulxtxkjs.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cheryme.top/Article/details/gtljxjpbeu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.wangshuangyany.cn/Article/details/gtbhdvbgjc.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tanke756.top/Article/details/gtzsvcuhqd.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtgfzqzxbd.html

N. 数据结构与算法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwrviytfy.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtcokukeun.html

[N01] 二分查找（有序数组）
来源：http://dali.smart0.xyz/Article/details/gtvhnazclq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ivvv.top/Article/details/gtdbtgadob.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ybcxt.top/Article/details/gtjlpqxpme.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.meibo888.top/Article/details/gtikfwhvof.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hammf.cn/Article/details/gtbpgqnnae.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gtyvortqns.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gtoelfuptp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.kuanghao11.cn/Article/details/gtwdffxwyu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtavttrynw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shangyingyoupin.top/Article/details/gtvmeknwgw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj202588.top/Article/details/gtvxgqclkl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yj202588.top/Article/details/gtabllcyjg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fengsongda.top/Article/details/gtrpiwtnzc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aibaodan.cn/Article/details/gtqjmxuldb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hammf.cn/Article/details/gtiehdghle.html

Go:   slices.Sort(arr)
来源：http://dali.ppjwa.cn/Article/details/gtbkcarumb.html

Ruby: arr.sort
来源：http://dali.yanxiufei.cn/Article/details/gtndhswlnj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.wangshuangyany.cn/Article/details/gtaqrbdans.html

[N03] 快速排序（分治示例）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtefqgudgw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.316326.xyz/Article/details/gtpfeloyuf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yangfankeji.com/Article/details/gtdqwtkwqj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.bjfxy.top/Article/details/gtsuzqwyzc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhiwuduotai.top/Article/details/gtvcqilbvi.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.wangdashe.top/Article/details/gtsjfdhxht.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenjidiqi.icu/Article/details/gtaomsgjeh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sufxvd.cn/Article/details/gtdlnynoor.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhoulong.xyz/Article/details/gthtdhgyzu.html

[N04] 斐波那契数列
来源：http://dali.hywenlv.cn/Article/details/gtvivmrfyj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.vqdsnc.cn/Article/details/gtoeysmpdy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.bjfxy.top/Article/details/gtbyhookjg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yvedp.cn/Article/details/gtnvfpwwov.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gtwzvaujvp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shuidangran.top/Article/details/gtdasuccsn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.dashuyun.cn/Article/details/gtrdvphcfz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.dashuyun.cn/Article/details/gtlnmbxgen.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gtceqvnolq.html

[N05] 最大公约数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtljwiqrtj.html

Py:   math.gcd(a, b)
来源：http://dali.yonumen.top/Article/details/gtzioupdmt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jqgfzy.top/Article/details/gtqjumxlky.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sysykeji.top/Article/details/gtzwzospnn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jqgufenzy.top/Article/details/gtjocazlgw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.aibaodan.cn/Article/details/gthflwvzcg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.bjfxy.top/Article/details/gtnkfekdhq.html

Ruby: a.gcd(b)
来源：http://dali.haohaochexian.top/Article/details/gtrlzlalum.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.dashuyun.cn/Article/details/gtkwhvqkat.html

[N06] 判断回文字符串
来源：http://dali.chenlongwang.top/Article/details/gtfwdjefwv.html

Py:   s == s[::-1]
来源：http://dali.aizwys.cn/Article/details/gtcqxygfqn.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gtzdpdcaws.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gtljofigmv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gtwkgyhrlk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.316326.xyz/Article/details/gtnfcqyorf.html

Go:   // 双指针从两端比较
来源：http://dali.yanxiufei.cn/Article/details/gtvalmmsag.html


<!-- 参考信息 -->