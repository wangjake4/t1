代发 wailian999

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tianlin.xyz/Article/details/gtbcjtborh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.feifeiyinyue.top/Article/details/gtahqgrncb.html

[J09] 时区处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthixlsrkr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gzhubu.top/Article/details/gtnamxqazr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxmdyulim.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.svipenyu.cn/Article/details/gtiqcvxail.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guowangkeji.top/Article/details/gtwphwvmhj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jqgufenzy.top/Article/details/gtcsdmmcix.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjarmflyt.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hnxiangtu.top/Article/details/gteynthsid.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.guannengcc.top/Article/details/gtyohbwevf.html

[J10] 取今天 / 本月第一天
来源：http://dali.jianghu66.top/Article/details/gtdypkyykj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yuanzhike.top/Article/details/gtycqcbstz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.feifeiyinyue.top/Article/details/gtbwipisdt.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nanxinkj.top/Article/details/gtazijnohv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinqigufen.top/Article/details/gtnrbflsox.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zycfv.cn/Article/details/gtethiwoed.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.316326.xyz/Article/details/gttnmnowhc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.redwolf501.top/Article/details/gtzepurzik.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xziqi.cn/Article/details/gtfeprzdwu.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtvozabbov.html

K. JSON 与序列化
来源：http://dali.ivvv.top/Article/details/gtgiwembvr.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gterrrvdml.html

[K01] 对象转 JSON 字符串
来源：http://dali.jiagoushi.top/Article/details/gthyomxfgt.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shzxlz.cn/Article/details/gtqoljtwju.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.haohaochexian.top/Article/details/gtimsrzpae.html

JS:   JSON.stringify(obj)
来源：http://dali.sweek.top/Article/details/gtvveoibxi.html

TS:   JSON.stringify(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtqwcbhcpr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jianghu66.top/Article/details/gthlnqralp.html

Go:   json.Marshal(obj)
来源：http://dali.bjfxy.top/Article/details/gtcixjgxch.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.fengsongda.top/Article/details/gtmwepelcs.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cashguo.top/Article/details/gtwmthqrjy.html

[K02] JSON 字符串转对象
来源：http://dali.zdqjudy.top/Article/details/gtheiqzizh.html

Py:   json.loads(s)
来源：http://dali.yj202588.top/Article/details/gtrowkjqtj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.kuanghao11.cn/Article/details/gtebdwrwxr.html

JS:   JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gtlckxjrid.html

TS:   JSON.parse(s)
来源：http://dali.jinqigufen.top/Article/details/gtiivyibuo.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.chenjidiqi.icu/Article/details/gtrxdiucqh.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ehwqpu.com/Article/details/gtjedcvvho.html

Ruby: JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gtconhrsog.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.redwolf501.top/Article/details/gtkhvsfrjx.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.guowangkeji.top/Article/details/gtnrttimki.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sufxvd.cn/Article/details/gtpjazuopr.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jyoumei.cn/Article/details/gtpiucubvx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.svipenyu.cn/Article/details/gttvbpnkic.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnqzz.top/Article/details/gtrwanehbf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.iojbl.cn/Article/details/gtmcabmeup.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zycfv.cn/Article/details/gtdqwyhenn.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shzxlz.cn/Article/details/gtrztgooqi.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gotoacloud.top/Article/details/gtivjkwzex.html

[K04] 读取 JSON 文件
来源：http://dali.tianlin.xyz/Article/details/gtijdnuqlt.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtonhpxvup.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gotoacloud.top/Article/details/gtpmckjwvw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ehwqpu.com/Article/details/gtzmxwimma.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.andypj.xyz/Article/details/gtitndnczl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cucudq.cn/Article/details/gtwyqzzxtp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yanxiufei.cn/Article/details/gtoeqiqmtr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.mhx1999.top/Article/details/gtwokbtlgj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yuanzhike.top/Article/details/gtofpmfzfj.html

[K05] 深拷贝对象
来源：http://dali.pycfn.com/Article/details/gtxvgnrceh.html

Py:   copy.deepcopy(obj)
来源：http://dali.birdmap.top/Article/details/gtkfnavkwq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinghuilouyu.cn/Article/details/gtlqptjixa.html

JS:   structuredClone(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gttauesszm.html

TS:   structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gtgpfhtefv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cucudq.cn/Article/details/gtifkbsuuj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.chenlongwang.top/Article/details/gtxkmljjng.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gogol.net.cn/Article/details/gtrguttkau.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nwbrower.top/Article/details/gtisqbqhbl.html

[K06] 解析 URL 查询串
来源：http://dali.tianlin.xyz/Article/details/gttteeamqq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xuanzx.com/Article/details/gtcyvfxhun.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.fzhhl.top/Article/details/gtivluaptq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenzaomai.com/Article/details/gthwzenizz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.quarkkingdee.top/Article/details/gtasuuagbk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hfpthk.cn/Article/details/gtufsyltvd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gtriclxsrd.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.vqdsnc.cn/Article/details/gtetqklmmh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gthludemxv.html

[K07] 进制转换
来源：http://dali.zhongyouzk.top/Article/details/gttzjvxwuj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gtygxpiadl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sysykeji.top/Article/details/gtywwtjwek.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnpkejijt.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtrpovkqgl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtdpqsexis.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hywenlv.cn/Article/details/gtcrvprfvy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.aizwys.cn/Article/details/gtnrgcvwtr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gtwkgdcdav.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cqqwz.cn/Article/details/gthfivjvhn.html

Py:   pickle.dumps(obj)
来源：http://dali.cucudq.cn/Article/details/gtfycceqaf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.chenzaomai.com/Article/details/gttdbfopex.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.chenlongwang.top/Article/details/gtnaotnnqi.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhixingplan.top/Article/details/gtqzjodcdk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.tianlin.xyz/Article/details/gtweskfnre.html

Go:   encoding/gob
来源：http://dali.dashuyun.cn/Article/details/gtukwrpbci.html

Ruby: Marshal.dump(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtutpciiof.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jqgfzy.top/Article/details/gteqpdljho.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtbburjqpk.html

L. 网络请求
来源：http://dali.tianlin.xyz/Article/details/gtcfcbtils.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtpqxssszd.html

[L01] 发送 GET 请求
来源：http://dali.wangdashe.top/Article/details/gtvnojbgst.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ybcxt.top/Article/details/gtjasfmtvp.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zdqjudy.top/Article/details/gtmwffaxpu.html

JS:   await fetch(url)
来源：http://dali.jqgufenzy.top/Article/details/gtevxvvwlu.html

TS:   await fetch(url)
来源：http://dali.hnqzz.top/Article/details/gtybljjrqd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.316326.xyz/Article/details/gtazijofdl.html

Go:   resp, err := http.Get(url)
来源：http://dali.shuidangran.top/Article/details/gtsouokhnb.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hysaishi.cn/Article/details/gtzzerkvez.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.birdmap.top/Article/details/gtrlobkxtj.html

[L02] 发送 POST JSON
来源：http://dali.jlsjyb.cn/Article/details/gtnnrpnkhp.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ybcxt.top/Article/details/gtbnffkids.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinqigfzy.top/Article/details/gtimgragvb.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.svipenyu.cn/Article/details/gtmtzacwdw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gtlypbpnha.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenzaomai.com/Article/details/gtoenetnak.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.kuanghao11.cn/Article/details/gtscpfxxcg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shanyushiyangtech.top/Article/details/gttgfkdftu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hfpthk.cn/Article/details/gtzsbwjclw.html

[L03] 设置自定义请求头
来源：http://dali.ybcxt.top/Article/details/gtctvrztqt.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sufxvd.cn/Article/details/gtjgzcqcjb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj20258.top/Article/details/gtbzqwgnbh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tian-w.cn/Article/details/gtzzmlqhur.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xziqi.cn/Article/details/gtuvnjbhwu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gotoacloud.top/Article/details/gtkklcwxrp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xuanzx.com/Article/details/gthuurtxky.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jlsjyb.cn/Article/details/gtgllvlwie.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.pycfn.com/Article/details/gtzdjfmysk.html

[L04] 设置超时
来源：http://dali.fengsongda.top/Article/details/gtabgniqys.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xinyue.icu/Article/details/gtdbupxves.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.aizwys.cn/Article/details/gtozfjofuu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhoulong.xyz/Article/details/gtggysluka.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.quarkkingdee.top/Article/details/gtgetoafqj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ehwqpu.com/Article/details/gtwngbhomr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhiwuduotai.top/Article/details/gthujkdsbz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yuxming.cn/Article/details/gtxhcidixz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.c1oappe.top/Article/details/gteydepqck.html

[L05] 上传文件（multipart）
来源：http://dali.meibo888.top/Article/details/gtbaqiyfnw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhoulong.xyz/Article/details/gtnimufwgb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwccfzuuu.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyyixobsw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhongyouzk.top/Article/details/gtabfacrxl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xuetiantiany.cn/Article/details/gtilvtqqvg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hfpthk.cn/Article/details/gtgdtdbrlf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.mhx1999.top/Article/details/gtxkocyiin.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtgdjkteuu.html

[L06] 解析响应为 JSON
来源：http://dali.fzhhl.top/Article/details/gtwuiicxnr.html

Py:   resp.json()
来源：http://dali.jinqigufen.top/Article/details/gthoqbfnpa.html

PHP:  json_decode($body, true);
来源：http://dali.ybcxt.top/Article/details/gtjgceyzad.html

JS:   await resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzhegfuew.html

TS:   await resp.json()
来源：http://dali.vqdsnc.cn/Article/details/gtmbmyqxgr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cashguo.top/Article/details/gtsdmrulhs.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yonumen.top/Article/details/gtkdvfkpvt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.snrcjt.cn/Article/details/gtecrszrlv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.vqdsnc.cn/Article/details/gtrmzhhgdv.html

[L07] 处理 HTTP 状态码
来源：http://dali.yuanzhike.top/Article/details/gtelmmgjyj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tian-w.cn/Article/details/gtkbrtzxba.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.iojbl.cn/Article/details/gtvoomutcy.html

JS:   resp.ok;  resp.status
来源：http://dali.yj20258.top/Article/details/gtzqlmbqbq.html

TS:   resp.ok;  resp.status
来源：http://dali.yvedp.cn/Article/details/gtnykxsvfe.html

Java: resp.statusCode()
来源：http://dali.gaohongyu789.top/Article/details/gtxtssazhl.html

Go:   resp.StatusCode
来源：http://dali.chenlongwang.top/Article/details/gtpdejqanu.html

Ruby: resp.code.to_i
来源：http://dali.sxryk.cn/Article/details/gtfomfpnxx.html

C#:   (int)resp.StatusCode
来源：http://dali.tianlin.xyz/Article/details/gtcdxvqoav.html

[L08] 并发请求多个地址
来源：http://dali.yuanzhike.top/Article/details/gtxxrdyfos.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sysykeji.top/Article/details/gtsgxsrlec.html

PHP:  curl_multi_init() 系列
来源：http://dali.snrcjt.cn/Article/details/gtzhidydnj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhoulong.xyz/Article/details/gtmcevfztb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gthfnkacgc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yonumen.top/Article/details/gtsjfbcytf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.tianlin.xyz/Article/details/gtuvazjfsb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.tanke756.top/Article/details/gtnntcrllb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.iojbl.cn/Article/details/gtiibcviqy.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtbmpduckz.html

M. 命令行 / 进程 / 环境
来源：http://dali.jianghu66.top/Article/details/gtvwatxalo.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtnwakbvbt.html

[M01] 读取命令行参数
来源：http://dali.tianlin.xyz/Article/details/gtehgmjdpo.html

Py:   sys.argv[1:]
来源：http://dali.yuxming.cn/Article/details/gtwhviqend.html

PHP:  $argv;  $argc;
来源：http://dali.smart0.xyz/Article/details/gtorpnowrp.html

JS:   process.argv.slice(2)
来源：http://dali.ppjwa.cn/Article/details/gtdktarfda.html

TS:   process.argv.slice(2)
来源：http://dali.zdqjudy.top/Article/details/gtpcqedest.html

Java: args 数组（main 方法参数）
来源：http://dali.ydzc1.top/Article/details/gtsijwksym.html

Go:   os.Args[1:]
来源：http://dali.hnqzz.top/Article/details/gtydaawpnk.html

Ruby: ARGV
来源：http://dali.havefunace.top/Article/details/gtfkhbgzjs.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenlongwang.top/Article/details/gtamgzyabp.html

[M02] 读取环境变量
来源：http://dali.cqqwz.cn/Article/details/gthjwaliun.html

Py:   os.environ.get("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtexgsaegf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.feifeiyinyue.top/Article/details/gtqokqyjwl.html

JS:   process.env.HOME
来源：http://dali.chenzaomai.com/Article/details/gtzqoixvex.html

TS:   process.env.HOME
来源：http://dali.cheryme.top/Article/details/gtpczlaeek.html

Java: System.getenv("HOME")
来源：http://dali.9152youxi.cn/Article/details/gttmlljnzt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sufxvd.cn/Article/details/gtylzzvkly.html

Ruby: ENV["HOME"]
来源：http://dali.aizwys.cn/Article/details/gtllckvfrb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gotoacloud.top/Article/details/gtfvxqenpn.html

[M03] 执行外部命令
来源：http://dali.jqgufenzy.top/Article/details/gtrscovqxe.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gtuaxinzyg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nwbrower.top/Article/details/gtyllvkfaw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yueranfly.top/Article/details/gtagprufuf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sysykeji.top/Article/details/gtmgmpnsse.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.haohaochexian.top/Article/details/gtslhiclnt.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.316326.xyz/Article/details/gtonltkjdh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xuetiantiany.cn/Article/details/gtsusyraeq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yj20258.top/Article/details/gtomkrewif.html

[M04] 获取当前工作目录
来源：http://dali.c1oappe.top/Article/details/gtfleeezfg.html

Py:   os.getcwd()
来源：http://dali.shuidangran.top/Article/details/gtjhdruvbn.html

PHP:  getcwd();
来源：http://dali.yuanzhike.top/Article/details/gtgvaveneb.html

JS:   process.cwd()
来源：http://dali.fzhhl.top/Article/details/gtlyowjnls.html

TS:   process.cwd()
来源：http://dali.smart0.xyz/Article/details/gtwovnmnmk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.dianchejie.cn/Article/details/gtnsxnckak.html

Go:   os.Getwd()
来源：http://dali.fengsongda.top/Article/details/gtiarvlcss.html

Ruby: Dir.pwd
来源：http://dali.wangshuangyany.cn/Article/details/gtvcrmhrno.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sweek.top/Article/details/gtfmgfjkze.html

[M05] 设置退出码
来源：http://dali.jqgufenzy.top/Article/details/gtzhomwkrl.html

Py:   sys.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gtzongbymy.html

PHP:  exit(1);
来源：http://dali.birdmap.top/Article/details/gtvglvaiwc.html

JS:   process.exit(1)
来源：http://dali.daxiang520.top/Article/details/gtfsehyrau.html

TS:   process.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtwxuzkqyw.html

Java: System.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gtbunrsrgl.html

Go:   os.Exit(1)
来源：http://dali.shuidangran.top/Article/details/gtuphnbtjd.html

Ruby: exit 1
来源：http://dali.meibo888.top/Article/details/gtneuzlypd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.havefunace.top/Article/details/gtqxvkbytm.html

[M06] 向标准错误输出
来源：http://dali.shanyushiyangtech.top/Article/details/gtqwfcdkbu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yueranfly.top/Article/details/gtsmvkmjsc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yonumen.top/Article/details/gtziliptom.html

JS:   console.error("err")
来源：http://dali.sysykeji.top/Article/details/gtgwasohsa.html

TS:   console.error("err")
来源：http://dali.yvedp.cn/Article/details/gtggrtcuji.html

Java: System.err.println("err")
来源：http://dali.nanxuanxn.top/Article/details/gtqnararyr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj20258.top/Article/details/gtcfwahgqm.html

Ruby: warn "err"
来源：http://dali.pycfn.com/Article/details/gtjrxpvlmg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.redwolf501.top/Article/details/gtsbpofzhz.html

[M07] 判断是否为主入口
来源：http://dali.hnxiangtu.top/Article/details/gtujqlabgu.html

Py:   if __name__ == "__main__":
来源：http://dali.xinyue.icu/Article/details/gtkrwihogb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.snrcjt.cn/Article/details/gtoxroyvky.html

JS:   require.main === module
来源：http://dali.svipenyu.cn/Article/details/gtostifxos.html

TS:   require.main === module
来源：http://dali.cdnleiting.top/Article/details/gtsxwljals.html

Java: public static void main(String[] args)
来源：http://dali.yuxming.cn/Article/details/gtsniykqwx.html

Go:   func main()
来源：http://dali.xuanzx.com/Article/details/gtuonhuuqt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yj202588.top/Article/details/gtupcjaxxz.html

C#:   static void Main(string[] args)
来源：http://dali.jianghu66.top/Article/details/gtyjuqvqeh.html

[M08] 获取系统与运行时信息
来源：http://dali.tian-w.cn/Article/details/gtsulrzpsm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.wangdashe.top/Article/details/gtfdnjzwwm.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cdnleiting.top/Article/details/gtegwranyp.html

JS:   process.platform;  process.version
来源：http://dali.yangfankeji.com/Article/details/gtbvjgjqfh.html

TS:   process.platform;  process.version
来源：http://dali.pengpengdd.cyou/Article/details/gtquzszaei.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xuanzx.com/Article/details/gtugaqjlhu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.nwbrower.top/Article/details/gtknarvdok.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.tianlin.xyz/Article/details/gtlfmvrcyh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinqigufen.top/Article/details/gtzxzdwhlt.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtobsqahfy.html

N. 数据结构与算法
来源：http://dali.hywenlv.cn/Article/details/gtwcrdmglr.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gteyjakpiv.html

[N01] 二分查找（有序数组）
来源：http://dali.shuidangran.top/Article/details/gtdmipsrda.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yonumen.top/Article/details/gtslxfimab.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jianghu66.top/Article/details/gtsypwfanp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hammf.cn/Article/details/gteaianmli.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cucudq.cn/Article/details/gthhkjeyok.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtytjepewx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtldizngvc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nanxinkj.top/Article/details/gtdczuajzw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtvhnwecef.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nanxinkj.top/Article/details/gtutccobmv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hongshengwenyu.top/Article/details/gtmpgvfcow.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cashguo.top/Article/details/gtjpbgeazc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlxdaokfs.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ydzc1.top/Article/details/gtneelfguz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.fzhhl.top/Article/details/gtpflbglht.html

Go:   slices.Sort(arr)
来源：http://dali.birdmap.top/Article/details/gtdydnpyad.html

Ruby: arr.sort
来源：http://dali.ivvv.top/Article/details/gtziedwudl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.aibaodan.cn/Article/details/gtsohjsrim.html

[N03] 快速排序（分治示例）
来源：http://dali.zycfv.cn/Article/details/gtjfwbpojh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.iojbl.cn/Article/details/gtnnfqozjr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.nanxuanxn.top/Article/details/gtjznwbdfs.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.havefunace.top/Article/details/gtclwybmux.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shangyingyoupin.top/Article/details/gtshobgrqh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gaohongyu789.top/Article/details/gtkubpcdmm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.andypj.xyz/Article/details/gtupsehkso.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.andypj.xyz/Article/details/gtegfyzyrk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jiagoushi.top/Article/details/gtdsfmgods.html

[N04] 斐波那契数列
来源：http://dali.ydzc1.top/Article/details/gthbdisryd.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.dashuyun.cn/Article/details/gtaovtxqzh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.tanke756.top/Article/details/gtbdbfbxxi.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jyoumei.cn/Article/details/gtnggprlys.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zycfv.cn/Article/details/gtvfksqjuo.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yongpay.top/Article/details/gtstoriqce.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.andypj.xyz/Article/details/gtfcpkybvg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sxryk.cn/Article/details/gtzrzfmnqg.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.fengsongda.top/Article/details/gtomfdicju.html

[N05] 最大公约数
来源：http://dali.zycfv.cn/Article/details/gtzruzqjlk.html

Py:   math.gcd(a, b)
来源：http://dali.9152youxi.cn/Article/details/gtybmgqvpt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cqqwz.cn/Article/details/gtkxumvebq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ehwqpu.com/Article/details/gtvcsaexey.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuanzhike.top/Article/details/gtnmhirrtw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xuanzx.com/Article/details/gtpaexqdaa.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xylfe.cn/Article/details/gtwngccxxb.html

Ruby: a.gcd(b)
来源：http://dali.316326.xyz/Article/details/gtpixfoqdk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gtfckwnpwx.html

[N06] 判断回文字符串
来源：http://dali.sxryk.cn/Article/details/gtcbqlywhd.html

Py:   s == s[::-1]
来源：http://dali.ehwqpu.com/Article/details/gtxdfguyzt.html

PHP:  $s === strrev($s);
来源：http://dali.hysaishi.cn/Article/details/gtqucgudsc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gthgiurszt.html

TS:   s === [...s].reverse().join("")
来源：http://dali.feifeiyinyue.top/Article/details/gtahpcvebr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xylfe.cn/Article/details/gtehfzczfg.html

Go:   // 双指针从两端比较
来源：http://dali.yj20258888.top/Article/details/gtmuifecui.html


<!-- 参考信息 -->