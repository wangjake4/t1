代发 wailian999

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdfpcsxnr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.quarkkingdee.top/Article/details/gtphknlgwy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aibaodan.cn/Article/details/gtxvispwvk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ybcxt.top/Article/details/gtlfpggozr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.fzhhl.top/Article/details/gtngtegaam.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yj20258.top/Article/details/gtxjuypksf.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gotoacloud.top/Article/details/gtwoxvpmxp.html

[J10] 取今天 / 本月第一天
来源：http://dali.aizwys.cn/Article/details/gtnczkdwxg.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvwyhwcuz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yangfankeji.com/Article/details/gtqjbvmazm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhoulong.xyz/Article/details/gtjowfqdoh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hywenlv.cn/Article/details/gtlmmbjyzs.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.svipenyu.cn/Article/details/gticawdcag.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xuanzx.com/Article/details/gtzpozjzik.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhongyouzk.top/Article/details/gtyyphhuvp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xuanzx.com/Article/details/gtgpdhbrqm.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtuuoldqsq.html

K. JSON 与序列化
来源：http://dali.daria6918.cn/Article/details/gtesvmmabc.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtjllqumsy.html

[K01] 对象转 JSON 字符串
来源：http://dali.xziqi.cn/Article/details/gtaoskuaqc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yuxming.cn/Article/details/gtnhkgegds.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yanxiufei.cn/Article/details/gtlqibvqqt.html

JS:   JSON.stringify(obj)
来源：http://dali.gogol.net.cn/Article/details/gtoyhvwwey.html

TS:   JSON.stringify(obj)
来源：http://dali.jinqigufen.top/Article/details/gtfkgncywt.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.pengpengdd.cyou/Article/details/gtbocpufxw.html

Go:   json.Marshal(obj)
来源：http://dali.snrcjt.cn/Article/details/gtqowyggvm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hongshengwenyu.top/Article/details/gtxjtfpohj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtjjixndzz.html

[K02] JSON 字符串转对象
来源：http://dali.kuanghao11.cn/Article/details/gtctvgdifk.html

Py:   json.loads(s)
来源：http://dali.xuanzx.com/Article/details/gtupxsjxdh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yonumen.top/Article/details/gtkohxcxgu.html

JS:   JSON.parse(s)
来源：http://dali.birdmap.top/Article/details/gtrjaycwdn.html

TS:   JSON.parse(s)
来源：http://dali.jianghu66.top/Article/details/gtfagbiqwo.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzedlrdli.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hywenlv.cn/Article/details/gtnczfesin.html

Ruby: JSON.parse(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlwcxupuh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.chenlongwang.top/Article/details/gteptctmfc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sysykeji.top/Article/details/gtmryzykfz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.guowangkeji.top/Article/details/gtccrrtdvh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.pengpengdd.cyou/Article/details/gtvygldjie.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xinyue.icu/Article/details/gtxcfxwcfa.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigfzy.top/Article/details/gtdkmixawu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hywenlv.cn/Article/details/gtkvafwvjx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.iojbl.cn/Article/details/gtxjscpxcy.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfonitvlf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cqqwz.cn/Article/details/gtvoaslauk.html

[K04] 读取 JSON 文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtnpesuucl.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sysykeji.top/Article/details/gtbuspcbvs.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.0kj1m.cn/Article/details/gtdykmntfy.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.vqdsnc.cn/Article/details/gtgziaonzz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuxming.cn/Article/details/gtvxtujicx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jyoumei.cn/Article/details/gtwpacagqp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yonumen.top/Article/details/gtwtfprrez.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtnbmpwhdn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.fzhhl.top/Article/details/gtzwwapzkv.html

[K05] 深拷贝对象
来源：http://dali.dianchejie.cn/Article/details/gtbnfemjuc.html

Py:   copy.deepcopy(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtnhgchjjj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.quarkkingdee.top/Article/details/gtvawyftyb.html

JS:   structuredClone(obj)
来源：http://dali.xylfe.cn/Article/details/gtbrpmvdkh.html

TS:   structuredClone(obj)
来源：http://dali.zdqjudy.top/Article/details/gtzvixjbyq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yangfankeji.com/Article/details/gtpqiszcqn.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinqigufen.top/Article/details/gtyhyuvkkq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hywenlv.cn/Article/details/gtcupayjwv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.smart0.xyz/Article/details/gtpnfgucpt.html

[K06] 解析 URL 查询串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtetsagsfd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yongpay.top/Article/details/gtijrgevwu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenzaomai.com/Article/details/gtyidaedmo.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yanxiufei.cn/Article/details/gtlososrmb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cashguo.top/Article/details/gtpwntizrn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.fzhhl.top/Article/details/gthwujypmk.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gogol.net.cn/Article/details/gtguteqdfe.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hywenlv.cn/Article/details/gtqeducodm.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhixingplan.top/Article/details/gtvqfekban.html

[K07] 进制转换
来源：http://dali.xuanzx.com/Article/details/gtfgpbodep.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtahflsiwb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jqgfzy.top/Article/details/gteoidxtsm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtefghaxlg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gtiodloxdr.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gttiepvnnt.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shangyingyoupin.top/Article/details/gtmancggmq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinqigfzy.top/Article/details/gtywjonfuo.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gtyvvijlvi.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenzaomai.com/Article/details/gtdxdkinrv.html

Py:   pickle.dumps(obj)
来源：http://dali.ivvv.top/Article/details/gtrfkmgqym.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhengqikj.top/Article/details/gteifsaivx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.tianlin.xyz/Article/details/gtloxitrzj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.pengpengdd.cyou/Article/details/gtuoycrwpj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yangfankeji.com/Article/details/gtrmaqvhnv.html

Go:   encoding/gob
来源：http://dali.gogol.net.cn/Article/details/gtzpyjkqen.html

Ruby: Marshal.dump(obj)
来源：http://dali.jqgfzy.top/Article/details/gtlrsnwlze.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhongyouzk.top/Article/details/gtajpkprmq.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtfffziitr.html

L. 网络请求
来源：http://dali.zycfv.cn/Article/details/gtmwoiftyx.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtopmiccjs.html

[L01] 发送 GET 请求
来源：http://dali.zhongyouzk.top/Article/details/gtyrwvlkjt.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jyoumei.cn/Article/details/gtbhvapprf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ppjwa.cn/Article/details/gtykdwghks.html

JS:   await fetch(url)
来源：http://dali.hfpthk.cn/Article/details/gtagjyaqqw.html

TS:   await fetch(url)
来源：http://dali.cucudq.cn/Article/details/gtgkfmtcmn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sxryk.cn/Article/details/gtdvcnwajf.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhixingplan.top/Article/details/gtoftjzymq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinghuilouyu.cn/Article/details/gtlmrtbtgj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.0kj1m.cn/Article/details/gtnlqgvivn.html

[L02] 发送 POST JSON
来源：http://dali.cucudq.cn/Article/details/gtaykwrnam.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xylfe.cn/Article/details/gtpdoedsll.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ivvv.top/Article/details/gtkuwultge.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jianghu66.top/Article/details/gtrnjsxczg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sysykeji.top/Article/details/gtivpcbkeh.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gttzcqjsem.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.smart0.xyz/Article/details/gthtjxxcfr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnzaqwrhj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xuanzx.com/Article/details/gtqmpfpwtt.html

[L03] 设置自定义请求头
来源：http://dali.yonumen.top/Article/details/gtfawfbjvq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.birdmap.top/Article/details/gtwmvndows.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zdqjudy.top/Article/details/gtwrpkotdy.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gzhubu.top/Article/details/gtruwawwpl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jyoumei.cn/Article/details/gtojbcorlk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yj202588.top/Article/details/gtifmdqgyz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.0kj1m.cn/Article/details/gtjpuvxlas.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.dianchejie.cn/Article/details/gtfydbncwo.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhixingplan.top/Article/details/gtvbsgkstp.html

[L04] 设置超时
来源：http://dali.daria6918.cn/Article/details/gtuwjvjsrj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yanxiufei.cn/Article/details/gtpbbgpjlo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yuxming.cn/Article/details/gtixbghato.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gaohongyu789.top/Article/details/gtfvvfvqzu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.c1oappe.top/Article/details/gtltakmjsl.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.tian-w.cn/Article/details/gtlyesexez.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yuanzhike.top/Article/details/gtrytkuvtm.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yonumen.top/Article/details/gtbcpaqsnj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sweek.top/Article/details/gtmpldvvez.html

[L05] 上传文件（multipart）
来源：http://dali.hfpthk.cn/Article/details/gtxcudovno.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.pycfn.com/Article/details/gtyqbngcee.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ybcxt.top/Article/details/gtmkhbfvgd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.birdmap.top/Article/details/gtzyieetdp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yonumen.top/Article/details/gtqgvaqlic.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hnqzz.top/Article/details/gtjbuzdcfx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.redwolf501.top/Article/details/gtxtdjlypq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.guowangkeji.top/Article/details/gtxolelxlj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtlzhvxfzh.html

[L06] 解析响应为 JSON
来源：http://dali.mhx1999.top/Article/details/gtxrvqhjtg.html

Py:   resp.json()
来源：http://dali.cdnleiting.top/Article/details/gtafjuhnii.html

PHP:  json_decode($body, true);
来源：http://dali.kuanghao11.cn/Article/details/gtphzxsvly.html

JS:   await resp.json()
来源：http://dali.fengsongda.top/Article/details/gtvecjyuwm.html

TS:   await resp.json()
来源：http://dali.cashguo.top/Article/details/gtsnckiuld.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jianghu66.top/Article/details/gtabmgiewx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.smart0.xyz/Article/details/gtzyadpoum.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hongshengwenyu.top/Article/details/gtappinofg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.0kj1m.cn/Article/details/gtqxutcgnb.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhengqikj.top/Article/details/gtbtgbirfk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ehwqpu.com/Article/details/gtfnjlnvtj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nwbrower.top/Article/details/gtypbeqxhn.html

JS:   resp.ok;  resp.status
来源：http://dali.bjfxy.top/Article/details/gtxlahkopw.html

TS:   resp.ok;  resp.status
来源：http://dali.zhongyouzk.top/Article/details/gtquytpyrv.html

Java: resp.statusCode()
来源：http://dali.iojbl.cn/Article/details/gtpmgreahc.html

Go:   resp.StatusCode
来源：http://dali.xuetiantiany.cn/Article/details/gtlspkfjsm.html

Ruby: resp.code.to_i
来源：http://dali.mhx1999.top/Article/details/gtzwzsjazn.html

C#:   (int)resp.StatusCode
来源：http://dali.xuetiantiany.cn/Article/details/gtzwzntdpr.html

[L08] 并发请求多个地址
来源：http://dali.vqdsnc.cn/Article/details/gtcxhmqxgz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.316326.xyz/Article/details/gtfmfkmdoz.html

PHP:  curl_multi_init() 系列
来源：http://dali.iojbl.cn/Article/details/gtldeeefty.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shangyingyoupin.top/Article/details/gtlhwvfvaa.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhixingplan.top/Article/details/gthxarsxos.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hywenlv.cn/Article/details/gtsnzfjfuf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.fzhhl.top/Article/details/gtrvvdbnvp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ybcxt.top/Article/details/gttmcldcaa.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hysaishi.cn/Article/details/gtdqgamjpk.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtzwsligpo.html

M. 命令行 / 进程 / 环境
来源：http://dali.zdqjudy.top/Article/details/gtpmecntdj.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtzfwodnnu.html

[M01] 读取命令行参数
来源：http://dali.cashguo.top/Article/details/gteoixazvt.html

Py:   sys.argv[1:]
来源：http://dali.pycfn.com/Article/details/gtwvfuqrom.html

PHP:  $argv;  $argc;
来源：http://dali.iojbl.cn/Article/details/gtvmmyehed.html

JS:   process.argv.slice(2)
来源：http://dali.andypj.xyz/Article/details/gtwiqyqvvz.html

TS:   process.argv.slice(2)
来源：http://dali.xuanzx.com/Article/details/gtxoxflcpz.html

Java: args 数组（main 方法参数）
来源：http://dali.havefunace.top/Article/details/gttesknrma.html

Go:   os.Args[1:]
来源：http://dali.zhengqikj.top/Article/details/gtjeconjnz.html

Ruby: ARGV
来源：http://dali.yj20258.top/Article/details/gtzsydryel.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gaohongyu789.top/Article/details/gtsxgwhptt.html

[M02] 读取环境变量
来源：http://dali.jiagoushi.top/Article/details/gtkkdqdbrj.html

Py:   os.environ.get("HOME")
来源：http://dali.yueranfly.top/Article/details/gtvlqatibt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtexwzmsnu.html

JS:   process.env.HOME
来源：http://dali.nanxuanxn.top/Article/details/gtcykhednv.html

TS:   process.env.HOME
来源：http://dali.sxryk.cn/Article/details/gttsxwxxfm.html

Java: System.getenv("HOME")
来源：http://dali.guannengcc.top/Article/details/gtqgvpzmlt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gtmcuvmzab.html

Ruby: ENV["HOME"]
来源：http://dali.snrcjt.cn/Article/details/gtuktmtmbe.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yvedp.cn/Article/details/gteaamjjbh.html

[M03] 执行外部命令
来源：http://dali.havefunace.top/Article/details/gtbueabnxi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.pycfn.com/Article/details/gtagbczhfb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtntufjmwo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtsvehrdxk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hammf.cn/Article/details/gtwszekqbf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shangyingyoupin.top/Article/details/gtdjuqnpic.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yangfankeji.com/Article/details/gtchwzpqmy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.feifeiyinyue.top/Article/details/gthdipbmxg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gzhubu.top/Article/details/gtbvwqkmob.html

[M04] 获取当前工作目录
来源：http://dali.dianchejie.cn/Article/details/gtoyisydjm.html

Py:   os.getcwd()
来源：http://dali.guowangkeji.top/Article/details/gtqxpqzvve.html

PHP:  getcwd();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdakhkuwz.html

JS:   process.cwd()
来源：http://dali.chenjidiqi.icu/Article/details/gtgcqjbjgd.html

TS:   process.cwd()
来源：http://dali.zhiwuduotai.top/Article/details/gtajheheje.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.guannengcc.top/Article/details/gtyoesalnq.html

Go:   os.Getwd()
来源：http://dali.cqqwz.cn/Article/details/gtbqqtrrrp.html

Ruby: Dir.pwd
来源：http://dali.jinqigufen.top/Article/details/gtuqsrlqbx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yj20258888.top/Article/details/gtspusmubl.html

[M05] 设置退出码
来源：http://dali.dashuyun.cn/Article/details/gtytjtzkfw.html

Py:   sys.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtlshdlssy.html

PHP:  exit(1);
来源：http://dali.jianghu66.top/Article/details/gtfqvpjhcd.html

JS:   process.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtlvezmuuz.html

TS:   process.exit(1)
来源：http://dali.yvedp.cn/Article/details/gtsqmwlnvh.html

Java: System.exit(1)
来源：http://dali.316326.xyz/Article/details/gtuwqqfmyw.html

Go:   os.Exit(1)
来源：http://dali.birdmap.top/Article/details/gtrjidpdel.html

Ruby: exit 1
来源：http://dali.cucudq.cn/Article/details/gtovxxwrlb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yangfankeji.com/Article/details/gtvuymrsgd.html

[M06] 向标准错误输出
来源：http://dali.cdnleiting.top/Article/details/gtxmceyjgd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.feifeiyinyue.top/Article/details/gteeoyxfre.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.birdmap.top/Article/details/gtryzbwrcy.html

JS:   console.error("err")
来源：http://dali.jiagoushi.top/Article/details/gtrrzairgj.html

TS:   console.error("err")
来源：http://dali.andypj.xyz/Article/details/gtmrjmkxdx.html

Java: System.err.println("err")
来源：http://dali.hnxiangtu.top/Article/details/gtvpspidku.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.mhx1999.top/Article/details/gtyslkvayb.html

Ruby: warn "err"
来源：http://dali.pycfn.com/Article/details/gtyhmgnudn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.birdmap.top/Article/details/gtrnpqezfv.html

[M07] 判断是否为主入口
来源：http://dali.cucudq.cn/Article/details/gtwoaomugv.html

Py:   if __name__ == "__main__":
来源：http://dali.hammf.cn/Article/details/gtaptpeckl.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yj20258.top/Article/details/gtinmnkpay.html

JS:   require.main === module
来源：http://dali.jinqigfzy.top/Article/details/gtccxicubr.html

TS:   require.main === module
来源：http://dali.aizwys.cn/Article/details/gtnmpftirm.html

Java: public static void main(String[] args)
来源：http://dali.xylfe.cn/Article/details/gtuodoxpcp.html

Go:   func main()
来源：http://dali.zhengqikj.top/Article/details/gtzbykhkul.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.meibo888.top/Article/details/gtlckrxcfi.html

C#:   static void Main(string[] args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxjshljq.html

[M08] 获取系统与运行时信息
来源：http://dali.pycfn.com/Article/details/gtfxzoziim.html

Py:   platform.system();  platform.python_version()
来源：http://dali.aibaodan.cn/Article/details/gtrqqhjhfy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sxryk.cn/Article/details/gtcdxuwrkv.html

JS:   process.platform;  process.version
来源：http://dali.hnqzz.top/Article/details/gtwgihonza.html

TS:   process.platform;  process.version
来源：http://dali.0kj1m.cn/Article/details/gtoduzivnv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.tian-w.cn/Article/details/gttcjxezly.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hammf.cn/Article/details/gtridycwtj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gotoacloud.top/Article/details/gtnhcjtlxx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.quarkkingdee.top/Article/details/gtmgvijnbo.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtihuwlvsh.html

N. 数据结构与算法
来源：http://dali.pengpengdd.cyou/Article/details/gtqihanxca.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtbrhkltdi.html

[N01] 二分查找（有序数组）
来源：http://dali.xylfe.cn/Article/details/gtvwrncses.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.redwolf501.top/Article/details/gtujfmqqae.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.redwolf501.top/Article/details/gtbgdkijwy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yonumen.top/Article/details/gttuabkpqb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sysykeji.top/Article/details/gtlwlrwtxo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtogfdhkda.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtzgpottuu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.fengsongda.top/Article/details/gtovtkqxgd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gthsmerqrj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.quarkkingdee.top/Article/details/gthlkozbsc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tianlin.xyz/Article/details/gtwzwygjur.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jlsjyb.cn/Article/details/gtwqfcedtw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daxiang520.top/Article/details/gtxvyodrap.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jyoumei.cn/Article/details/gtyeftirpr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yongpay.top/Article/details/gtwibuezcr.html

Go:   slices.Sort(arr)
来源：http://dali.zdqjudy.top/Article/details/gtsplxbutw.html

Ruby: arr.sort
来源：http://dali.gotoacloud.top/Article/details/gtuapwoxzf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.snrcjt.cn/Article/details/gtulujpdqz.html

[N03] 快速排序（分治示例）
来源：http://dali.yj20258.top/Article/details/gtncpjuxfe.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhoulong.xyz/Article/details/gtyaonvlgt.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gaohongyu789.top/Article/details/gtklnytusk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shangyingyoupin.top/Article/details/gtlmcderjq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gogol.net.cn/Article/details/gtycbqakgm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj20258.top/Article/details/gtjhjdfeam.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.vqdsnc.cn/Article/details/gtanjwumhl.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cqqwz.cn/Article/details/gtaucbrrms.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.havefunace.top/Article/details/gtqdauiafq.html

[N04] 斐波那契数列
来源：http://dali.haohaochexian.top/Article/details/gttvjbvrpi.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigfzy.top/Article/details/gtzvulpbpi.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.tian-w.cn/Article/details/gtvustxxxz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.havefunace.top/Article/details/gtoerwroxq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cucudq.cn/Article/details/gtwqckcgps.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jlsjyb.cn/Article/details/gtkbcgehjg.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hongshengwenyu.top/Article/details/gtamzjziff.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhoulong.xyz/Article/details/gtujxojqoc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hfpthk.cn/Article/details/gtcdmkesgw.html

[N05] 最大公约数
来源：http://dali.dashuyun.cn/Article/details/gteobcbugu.html

Py:   math.gcd(a, b)
来源：http://dali.jinqigufen.top/Article/details/gtcvhbdjit.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jianghu66.top/Article/details/gtzxjtvzwk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aizwys.cn/Article/details/gtoofrdgyv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtbpggnjua.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttpzjeznx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sufxvd.cn/Article/details/gtswqpvtir.html

Ruby: a.gcd(b)
来源：http://dali.ehwqpu.com/Article/details/gtzfiyhuun.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gzhubu.top/Article/details/gtkzhmyrtc.html

[N06] 判断回文字符串
来源：http://dali.ehwqpu.com/Article/details/gtbwwkglyd.html

Py:   s == s[::-1]
来源：http://dali.dianchejie.cn/Article/details/gtulyaqqeg.html

PHP:  $s === strrev($s);
来源：http://dali.zhongyouzk.top/Article/details/gtpfmkdinf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gtxclhxqhl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gthlgknbvt.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sweek.top/Article/details/gtibwgkdya.html

Go:   // 双指针从两端比较
来源：http://dali.quarkkingdee.top/Article/details/gtplvbxtnf.html

Ruby: s == s.reverse
来源：http://dali.dianchejie.cn/Article/details/gtnzxzyexu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhixingplan.top/Article/details/gtbgvpgfzt.html

[N07] 两数之和（返回下标）
来源：http://dali.gogol.net.cn/Article/details/gtxstkaoao.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.birdmap.top/Article/details/gtoqovnanm.html


<!-- 参考信息 -->