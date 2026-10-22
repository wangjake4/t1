代发 wailian999

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ppjwa.cn/Article/details/gtlmwszidg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ehwqpu.com/Article/details/gtolobqwhu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.c1oappe.top/Article/details/gtquaefpnq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jianghu66.top/Article/details/gtpvqcdbxn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ywan-chungtsiang.top/Article/details/gtetgbeuqr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jiagoushi.top/Article/details/gtqwyrzmse.html

[J09] 时区处理
来源：http://dali.jyoumei.cn/Article/details/gtrnfgexvq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.chenjidiqi.icu/Article/details/gtulzqrplz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.fzhhl.top/Article/details/gthqwfinsw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yonumen.top/Article/details/gtxgfgvvww.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jianghu66.top/Article/details/gtugfqlhzw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinqigufen.top/Article/details/gthejkquni.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.aizwys.cn/Article/details/gttvouyfym.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.svipenyu.cn/Article/details/gtjotecddm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hnxiangtu.top/Article/details/gthdrtrwzh.html

[J10] 取今天 / 本月第一天
来源：http://dali.guowangkeji.top/Article/details/gtrbpjkwjx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.vqdsnc.cn/Article/details/gtucjhmmyw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.mhx1999.top/Article/details/gteccdjwgo.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuumjwtbx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtotkhtyiz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shzxlz.cn/Article/details/gtyrsmplsr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.smart0.xyz/Article/details/gtqazzltft.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.daria6918.cn/Article/details/gtaxskfooa.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jianghu66.top/Article/details/gtjrteylud.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtzthsankl.html

K. JSON 与序列化
来源：http://dali.nwbrower.top/Article/details/gtwkljkkak.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtsdkdsnko.html

[K01] 对象转 JSON 字符串
来源：http://dali.gaohongyu789.top/Article/details/gtdayoheyz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.bjfxy.top/Article/details/gtyqyutwgn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.tian-w.cn/Article/details/gtcebhuzxi.html

JS:   JSON.stringify(obj)
来源：http://dali.hammf.cn/Article/details/gtwdkbfoir.html

TS:   JSON.stringify(obj)
来源：http://dali.shuidangran.top/Article/details/gtmtzhxfsh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.vqdsnc.cn/Article/details/gtwcfbhqwn.html

Go:   json.Marshal(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtrlsoekut.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.iojbl.cn/Article/details/gtkcdwkauo.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtxocwimvd.html

[K02] JSON 字符串转对象
来源：http://dali.quarkkingdee.top/Article/details/gtqcrybqid.html

Py:   json.loads(s)
来源：http://dali.ydzc1.top/Article/details/gtkbaampot.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yangfankeji.com/Article/details/gtbfnjkajn.html

JS:   JSON.parse(s)
来源：http://dali.mhx1999.top/Article/details/gtdlgfaitq.html

TS:   JSON.parse(s)
来源：http://dali.daxiang520.top/Article/details/gtojqisuvm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.chenjidiqi.icu/Article/details/gtnvmwhhph.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.wangdashe.top/Article/details/gtgsufrlne.html

Ruby: JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gtcvqcwvwj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.c1oappe.top/Article/details/gtovapaddl.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.0kj1m.cn/Article/details/gtnzxkowvb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxpxkqben.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhongyouzk.top/Article/details/gtfwdsvfvk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhengqikj.top/Article/details/gtzvomdtzc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.quarkkingdee.top/Article/details/gtlochifjb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gogol.net.cn/Article/details/gtbfifyimv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.c1oappe.top/Article/details/gtkkqxspmz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.dashuyun.cn/Article/details/gtykydbsps.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.havefunace.top/Article/details/gtfoaydcuq.html

[K04] 读取 JSON 文件
来源：http://dali.xziqi.cn/Article/details/gtpstorpaq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cashguo.top/Article/details/gtfbkqtucd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yongpay.top/Article/details/gttumnwcln.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sxryk.cn/Article/details/gtegjicpyk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sysykeji.top/Article/details/gtykiqpkly.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yj20258.top/Article/details/gtuubdllvw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yvedp.cn/Article/details/gtwvtyudwj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.tanke756.top/Article/details/gtnpkqiypw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xuetiantiany.cn/Article/details/gtwgzmntpb.html

[K05] 深拷贝对象
来源：http://dali.c1oappe.top/Article/details/gtkphmqfis.html

Py:   copy.deepcopy(obj)
来源：http://dali.jiagoushi.top/Article/details/gtyilpwude.html

PHP:  unserialize(serialize($obj));
来源：http://dali.wangdashe.top/Article/details/gturbdyfkp.html

JS:   structuredClone(obj)
来源：http://dali.guannengcc.top/Article/details/gtgswnjfrk.html

TS:   structuredClone(obj)
来源：http://dali.aizwys.cn/Article/details/gtksplahkx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ywan-chungtsiang.top/Article/details/gttbghugfs.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cucudq.cn/Article/details/gtgqubkbsl.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shanyushiyangtech.top/Article/details/gturiqctos.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cheryme.top/Article/details/gtvkzitmed.html

[K06] 解析 URL 查询串
来源：http://dali.ivvv.top/Article/details/gtiujtjqih.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ydzc1.top/Article/details/gtmzblqwst.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.meibo888.top/Article/details/gtmojziifu.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cqqwz.cn/Article/details/gtnpivsvzz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gotoacloud.top/Article/details/gthdhnbbeh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xuanzx.com/Article/details/gtjonfbkmf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hywenlv.cn/Article/details/gtswdfuspl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gtradlwlxf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.feifeiyinyue.top/Article/details/gthenzrvkb.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gtwfmsbvyd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yonumen.top/Article/details/gttgpawltd.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigfzy.top/Article/details/gtetioshwo.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gtwtfbxpdc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtthvsfrly.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gtydqxlzrn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ydzc1.top/Article/details/gtlmxtolxu.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.mhx1999.top/Article/details/gtisaxqfjh.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gtbsycgsre.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cashguo.top/Article/details/gtxlbjmfjc.html

Py:   pickle.dumps(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtwdyabucs.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cucudq.cn/Article/details/gtcebrtclk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.guowangkeji.top/Article/details/gtgmarafve.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.quarkkingdee.top/Article/details/gtuctqyluc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sweek.top/Article/details/gtvhleohpg.html

Go:   encoding/gob
来源：http://dali.birdmap.top/Article/details/gtylnozvan.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhixingplan.top/Article/details/gtsgsvnonl.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinqigufen.top/Article/details/gtzhvinebc.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtochcupeo.html

L. 网络请求
来源：http://dali.daxiang520.top/Article/details/gtkukkujuv.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtqloylijn.html

[L01] 发送 GET 请求
来源：http://dali.jlsjyb.cn/Article/details/gtzwggskhz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ppjwa.cn/Article/details/gtwoixwtkv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sxryk.cn/Article/details/gtvtfyvibq.html

JS:   await fetch(url)
来源：http://dali.wangshuangyany.cn/Article/details/gtmemfqlbc.html

TS:   await fetch(url)
来源：http://dali.aibaodan.cn/Article/details/gttygutkpt.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hammf.cn/Article/details/gtnmquitld.html

Go:   resp, err := http.Get(url)
来源：http://dali.zycfv.cn/Article/details/gtgfetuxxa.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.c1oappe.top/Article/details/gtefwhjmtf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cdnleiting.top/Article/details/gtjutaughi.html

[L02] 发送 POST JSON
来源：http://dali.c1oappe.top/Article/details/gtsamirrrx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.sysykeji.top/Article/details/gtvrigssas.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.guowangkeji.top/Article/details/gtirlirhkp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenlongwang.top/Article/details/gtvtapgkvc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ybcxt.top/Article/details/gtjziviewu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yj20258888.top/Article/details/gtbodzmlux.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.nwbrower.top/Article/details/gtufgkcjgu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ivvv.top/Article/details/gtizqewytk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.chenzaomai.com/Article/details/gtrxovrkze.html

[L03] 设置自定义请求头
来源：http://dali.ehwqpu.com/Article/details/gtgaflunbb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jyoumei.cn/Article/details/gtmjcbweto.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.svipenyu.cn/Article/details/gtswwpdjdg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuetiantiany.cn/Article/details/gtcqkoyyzl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.redwolf501.top/Article/details/gtqnzlepgb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.daxiang520.top/Article/details/gtgklpohdh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xuetiantiany.cn/Article/details/gtsekcnahq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jqgufenzy.top/Article/details/gtvzgjdgyq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.wangshuangyany.cn/Article/details/gtvwwzkihr.html

[L04] 设置超时
来源：http://dali.zhixingplan.top/Article/details/gttxxbyjme.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenjidiqi.icu/Article/details/gtvllavbks.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.pycfn.com/Article/details/gtiuaacori.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pycfn.com/Article/details/gtuuggzrns.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258888.top/Article/details/gtxcqojkvz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.chenlongwang.top/Article/details/gtvjwlgdfr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jqgfzy.top/Article/details/gtrzztudyi.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gotoacloud.top/Article/details/gtctervkpq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shzxlz.cn/Article/details/gtamfxgzxy.html

[L05] 上传文件（multipart）
来源：http://dali.jqgfzy.top/Article/details/gtfgcpidhm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.kuanghao11.cn/Article/details/gtqesyvswr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.fzhhl.top/Article/details/gtaqfktzsm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.svipenyu.cn/Article/details/gthtlykbrt.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhengqikj.top/Article/details/gtlhnvfjmc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.tian-w.cn/Article/details/gtyztwmupj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinqigfzy.top/Article/details/gtaqntnptb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinghuilouyu.cn/Article/details/gtyndergyy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hammf.cn/Article/details/gtoulosiok.html

[L06] 解析响应为 JSON
来源：http://dali.sweek.top/Article/details/gthvixxvob.html

Py:   resp.json()
来源：http://dali.zhixingplan.top/Article/details/gtgzkxuwfc.html

PHP:  json_decode($body, true);
来源：http://dali.jianghu66.top/Article/details/gtkyxuqzjc.html

JS:   await resp.json()
来源：http://dali.mhx1999.top/Article/details/gtjfvobvsj.html

TS:   await resp.json()
来源：http://dali.zhengqikj.top/Article/details/gtolryzqdp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xuetiantiany.cn/Article/details/gtdtgawdkh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nanxuanxn.top/Article/details/gtaqaeuevn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.vqdsnc.cn/Article/details/gtdklhwpsx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj202588.top/Article/details/gtufixqqog.html

[L07] 处理 HTTP 状态码
来源：http://dali.shanyushiyangtech.top/Article/details/gtzthyucvy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yuanzhike.top/Article/details/gtcfgrliqc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sweek.top/Article/details/gtffxmpgav.html

JS:   resp.ok;  resp.status
来源：http://dali.wangdashe.top/Article/details/gtnznjqmgw.html

TS:   resp.ok;  resp.status
来源：http://dali.jinyuanbaomall.cn/Article/details/gtroccgqvq.html

Java: resp.statusCode()
来源：http://dali.nanxinkj.top/Article/details/gtvfutsord.html

Go:   resp.StatusCode
来源：http://dali.316326.xyz/Article/details/gtppwinzun.html

Ruby: resp.code.to_i
来源：http://dali.zhixingplan.top/Article/details/gtdphrshma.html

C#:   (int)resp.StatusCode
来源：http://dali.xuetiantiany.cn/Article/details/gtjrxxdcgk.html

[L08] 并发请求多个地址
来源：http://dali.meibo888.top/Article/details/gtcrburmme.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.wangshuangyany.cn/Article/details/gtpcegreib.html

PHP:  curl_multi_init() 系列
来源：http://dali.snrcjt.cn/Article/details/gtusaqgzqk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.316326.xyz/Article/details/gtctnshnhn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sufxvd.cn/Article/details/gtbwhckkwe.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shuidangran.top/Article/details/gtvshfnzzf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cqqwz.cn/Article/details/gttgscuirw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhoulong.xyz/Article/details/gthwjyynqr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jiagoushi.top/Article/details/gtpliokjtj.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxyyqtrsv.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinqigfzy.top/Article/details/gtlezyjotv.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gticvyrccb.html

[M01] 读取命令行参数
来源：http://dali.quarkkingdee.top/Article/details/gtvfxvvygc.html

Py:   sys.argv[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjgitiykx.html

PHP:  $argv;  $argc;
来源：http://dali.ppjwa.cn/Article/details/gthriyveac.html

JS:   process.argv.slice(2)
来源：http://dali.chenjidiqi.icu/Article/details/gthrvtsawk.html

TS:   process.argv.slice(2)
来源：http://dali.meibo888.top/Article/details/gtxvwhxhcu.html

Java: args 数组（main 方法参数）
来源：http://dali.yonumen.top/Article/details/gtlgamccqa.html

Go:   os.Args[1:]
来源：http://dali.xziqi.cn/Article/details/gtyrisffqz.html

Ruby: ARGV
来源：http://dali.hnxiangtu.top/Article/details/gtnflbqmzg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gaohongyu789.top/Article/details/gtonwxakon.html

[M02] 读取环境变量
来源：http://dali.iojbl.cn/Article/details/gtioocjyve.html

Py:   os.environ.get("HOME")
来源：http://dali.gogol.net.cn/Article/details/gtmpqnzzxn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jyoumei.cn/Article/details/gtqgqdxkrg.html

JS:   process.env.HOME
来源：http://dali.feifeiyinyue.top/Article/details/gtiafpwyry.html

TS:   process.env.HOME
来源：http://dali.xylfe.cn/Article/details/gtvuddqray.html

Java: System.getenv("HOME")
来源：http://dali.cqqwz.cn/Article/details/gthbxhmalq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jiagoushi.top/Article/details/gtzppehgum.html

Ruby: ENV["HOME"]
来源：http://dali.yongpay.top/Article/details/gttevyglof.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tian-w.cn/Article/details/gtzmuqytni.html

[M03] 执行外部命令
来源：http://dali.ivvv.top/Article/details/gtairzbsmf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.vqdsnc.cn/Article/details/gthpusoiic.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjdgyjarl.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxuanxn.top/Article/details/gtwjresiqe.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenzaomai.com/Article/details/gtbqqswbia.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.smart0.xyz/Article/details/gtdzjoeqez.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ydzc1.top/Article/details/gtazwffoml.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tian-w.cn/Article/details/gtsvxicztu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yuanzhike.top/Article/details/gtwljkiemq.html

[M04] 获取当前工作目录
来源：http://dali.ydzc1.top/Article/details/gtemeduwsq.html

Py:   os.getcwd()
来源：http://dali.sweek.top/Article/details/gtzuxrpltq.html

PHP:  getcwd();
来源：http://dali.redwolf501.top/Article/details/gtcgtrkmol.html

JS:   process.cwd()
来源：http://dali.ydzc1.top/Article/details/gtwurbivys.html

TS:   process.cwd()
来源：http://dali.hywenlv.cn/Article/details/gtapbqbfbn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ybcxt.top/Article/details/gthehrvhxt.html

Go:   os.Getwd()
来源：http://dali.ehwqpu.com/Article/details/gtosydasjy.html

Ruby: Dir.pwd
来源：http://dali.jqgufenzy.top/Article/details/gtrkiybvlw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jiagoushi.top/Article/details/gtuahcpier.html

[M05] 设置退出码
来源：http://dali.wangshuangyany.cn/Article/details/gtwvlivvjv.html

Py:   sys.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtxsfzobox.html

PHP:  exit(1);
来源：http://dali.hywenlv.cn/Article/details/gtsopgpktr.html

JS:   process.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gttuygdtep.html

TS:   process.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtkoznojxh.html

Java: System.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtjdgwhvpz.html

Go:   os.Exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxmaepbos.html

Ruby: exit 1
来源：http://dali.meibo888.top/Article/details/gtrnexlsna.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cqqwz.cn/Article/details/gtyljvkeor.html

[M06] 向标准错误输出
来源：http://dali.ivvv.top/Article/details/gtyscxtqcd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.nanxuanxn.top/Article/details/gtkbiuiyre.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzwisyksi.html

JS:   console.error("err")
来源：http://dali.nwbrower.top/Article/details/gtpxrwcdmc.html

TS:   console.error("err")
来源：http://dali.yj20258888.top/Article/details/gtyrsgspej.html

Java: System.err.println("err")
来源：http://dali.andypj.xyz/Article/details/gtrdeawzro.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.daxiang520.top/Article/details/gtbhshnrki.html

Ruby: warn "err"
来源：http://dali.hysaishi.cn/Article/details/gtzyduetuj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.dianchejie.cn/Article/details/gtltbfukdb.html

[M07] 判断是否为主入口
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfttnfwks.html

Py:   if __name__ == "__main__":
来源：http://dali.zdqjudy.top/Article/details/gtbgvvrnaz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yvedp.cn/Article/details/gtnckariud.html

JS:   require.main === module
来源：http://dali.aibaodan.cn/Article/details/gthvtvcggl.html

TS:   require.main === module
来源：http://dali.zhongyouzk.top/Article/details/gtqfqkwepm.html

Java: public static void main(String[] args)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfiywdtrg.html

Go:   func main()
来源：http://dali.haohaochexian.top/Article/details/gtszcevtbr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shanyushiyangtech.top/Article/details/gtfhwjthyr.html

C#:   static void Main(string[] args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiaqvbzdl.html

[M08] 获取系统与运行时信息
来源：http://dali.bjfxy.top/Article/details/gtzuxbmvmv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.c1oappe.top/Article/details/gtpqmsjvah.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gaohongyu789.top/Article/details/gtikkvxxtk.html

JS:   process.platform;  process.version
来源：http://dali.chenjidiqi.icu/Article/details/gtfrhkqbje.html

TS:   process.platform;  process.version
来源：http://dali.mhx1999.top/Article/details/gtilknilvf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.daria6918.cn/Article/details/gtuocavdri.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yuanzhike.top/Article/details/gtbejbzxew.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sxryk.cn/Article/details/gtboxvqbek.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xinyue.icu/Article/details/gtutrfjmfv.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtlexcggcn.html

N. 数据结构与算法
来源：http://dali.snrcjt.cn/Article/details/gtkgkfjnlm.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtksdymfae.html

[N01] 二分查找（有序数组）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuqhxsmgd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtocqrmqjh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.aibaodan.cn/Article/details/gtvoqoeyui.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigfzy.top/Article/details/gtfknpbjwp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dianchejie.cn/Article/details/gtcmsoijue.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtnizrwqsh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.guannengcc.top/Article/details/gthinfeuef.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yueranfly.top/Article/details/gtoorwlaqk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdyggzcyy.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.smart0.xyz/Article/details/gtsnhthwky.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.svipenyu.cn/Article/details/gtcqfxyzjt.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hywenlv.cn/Article/details/gtllxwgtdg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shuidangran.top/Article/details/gthyupekno.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.snrcjt.cn/Article/details/gtepivbxmy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinghuilouyu.cn/Article/details/gtitavyruz.html

Go:   slices.Sort(arr)
来源：http://dali.wangdashe.top/Article/details/gtbytkcwjn.html

Ruby: arr.sort
来源：http://dali.cheryme.top/Article/details/gttftqsmfx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yongpay.top/Article/details/gtfbcrmxqn.html

[N03] 快速排序（分治示例）
来源：http://dali.wangshuangyany.cn/Article/details/gtbrfuqiqt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shzxlz.cn/Article/details/gtecfabcov.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cheryme.top/Article/details/gtmbljmafv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hnxiangtu.top/Article/details/gtlbpestnd.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hysaishi.cn/Article/details/gtpjddclky.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hongshengwenyu.top/Article/details/gtagrqcvzc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.iojbl.cn/Article/details/gtnkobddpm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.kuanghao11.cn/Article/details/gtdvwmlznp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yanxiufei.cn/Article/details/gtgdeaggrp.html

[N04] 斐波那契数列
来源：http://dali.daxiang520.top/Article/details/gtufzxfjui.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.dianchejie.cn/Article/details/gtowqinlpl.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hywenlv.cn/Article/details/gtwvkxvocd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.snrcjt.cn/Article/details/gthicyrqlz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daxiang520.top/Article/details/gtqwfocosj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.svipenyu.cn/Article/details/gtfnmkmfar.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yonumen.top/Article/details/gtzyaiofep.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.316326.xyz/Article/details/gtwnpucydz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.316326.xyz/Article/details/gtlzbdtadl.html

[N05] 最大公约数
来源：http://dali.pycfn.com/Article/details/gtlydfxkam.html

Py:   math.gcd(a, b)
来源：http://dali.gogol.net.cn/Article/details/gtpujvbolm.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zycfv.cn/Article/details/gtvbdpvdwf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tanke756.top/Article/details/gturhixiqn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenzaomai.com/Article/details/gtelldctzz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.nanxuanxn.top/Article/details/gtzwidkzmk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yongpay.top/Article/details/gthbofdhxl.html

Ruby: a.gcd(b)
来源：http://dali.yuanzhike.top/Article/details/gtwpeetbvc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.birdmap.top/Article/details/gtbchecgcv.html

[N06] 判断回文字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtwfwumrvm.html

Py:   s == s[::-1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxpdhzzkq.html

PHP:  $s === strrev($s);
来源：http://dali.vqdsnc.cn/Article/details/gthadqqbfq.html


<!-- 参考信息 -->