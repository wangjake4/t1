代发 wailian999

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nanxinkj.top/Article/details/gtcvmaaier.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangshuangyany.cn/Article/details/gtorvishcx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guannengcc.top/Article/details/gtmktkampg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nanxinkj.top/Article/details/gtavvfzwxq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shzxlz.cn/Article/details/gtmfiyqgrq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhiwuduotai.top/Article/details/gtkzwajufn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcdfntcvz.html

[J10] 取今天 / 本月第一天
来源：http://dali.aizwys.cn/Article/details/gtnkbrgjne.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jlsjyb.cn/Article/details/gtcdawejzd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cucudq.cn/Article/details/gtlfywvorr.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hysaishi.cn/Article/details/gtetmnkgrm.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.birdmap.top/Article/details/gtmxwxgepk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlqmnawpl.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.c1oappe.top/Article/details/gthywkurun.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.fzhhl.top/Article/details/gtstfiedja.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.tian-w.cn/Article/details/gtwgitheoq.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtowwjgjkf.html

K. JSON 与序列化
来源：http://dali.tian-w.cn/Article/details/gtodufmczf.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtwvtigxgq.html

[K01] 对象转 JSON 字符串
来源：http://dali.ivvv.top/Article/details/gtildhibtm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shzxlz.cn/Article/details/gtcgsmnkjk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.tanke756.top/Article/details/gtlqpjzufs.html

JS:   JSON.stringify(obj)
来源：http://dali.haohaochexian.top/Article/details/gtlyosvfeu.html

TS:   JSON.stringify(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtajirkjkk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.quarkkingdee.top/Article/details/gtffsikend.html

Go:   json.Marshal(obj)
来源：http://dali.mhx1999.top/Article/details/gtrsgmiicm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sufxvd.cn/Article/details/gtqommbuoy.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.dianchejie.cn/Article/details/gtaolwduva.html

[K02] JSON 字符串转对象
来源：http://dali.9152youxi.cn/Article/details/gtvknewqci.html

Py:   json.loads(s)
来源：http://dali.fengsongda.top/Article/details/gtveiieahx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sxryk.cn/Article/details/gtaivnmlvj.html

JS:   JSON.parse(s)
来源：http://dali.aizwys.cn/Article/details/gtcvsajwil.html

TS:   JSON.parse(s)
来源：http://dali.cashguo.top/Article/details/gtmkszgrgd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.guowangkeji.top/Article/details/gttysbyevm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xziqi.cn/Article/details/gtfvbswifn.html

Ruby: JSON.parse(s)
来源：http://dali.daria6918.cn/Article/details/gtjshzjeea.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yvedp.cn/Article/details/gtmwnjivvj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.nwbrower.top/Article/details/gtzissjiqh.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.havefunace.top/Article/details/gtfrqltigp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yueranfly.top/Article/details/gtvutdrcow.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnqzz.top/Article/details/gtbznzkikp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlkkbdonm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yonumen.top/Article/details/gttsjbakzz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhoulong.xyz/Article/details/gtjhndfygv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gogol.net.cn/Article/details/gtazjlvbqr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nanxuanxn.top/Article/details/gtwtozjyca.html

[K04] 读取 JSON 文件
来源：http://dali.wangdashe.top/Article/details/gtvszqeueb.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yuanzhike.top/Article/details/gtgdzeojpv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj20258888.top/Article/details/gtswxwcjlq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkhkaxurm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jianghu66.top/Article/details/gtmjozawbt.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gogol.net.cn/Article/details/gthxnyvhpo.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinghuilouyu.cn/Article/details/gtftyqnksy.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.meibo888.top/Article/details/gtkfbmxuow.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nwbrower.top/Article/details/gtvbvhlsee.html

[K05] 深拷贝对象
来源：http://dali.sweek.top/Article/details/gtygzejmia.html

Py:   copy.deepcopy(obj)
来源：http://dali.tianlin.xyz/Article/details/gtwjwhouco.html

PHP:  unserialize(serialize($obj));
来源：http://dali.bjfxy.top/Article/details/gtjfgyfxiu.html

JS:   structuredClone(obj)
来源：http://dali.ppjwa.cn/Article/details/gtfrioljra.html

TS:   structuredClone(obj)
来源：http://dali.yj20258.top/Article/details/gtekhbdplg.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.feifeiyinyue.top/Article/details/gtibjasbbo.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.kuanghao11.cn/Article/details/gtznxewwhu.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ehwqpu.com/Article/details/gtnrkcfdce.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.smart0.xyz/Article/details/gtifcuhkzr.html

[K06] 解析 URL 查询串
来源：http://dali.gzhubu.top/Article/details/gtqqjbpjbh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ppjwa.cn/Article/details/gtvjewaobv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sysykeji.top/Article/details/gtkipeznzv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258888.top/Article/details/gtwklkbret.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.iojbl.cn/Article/details/gtogcovhrj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.wangshuangyany.cn/Article/details/gtxspukfbr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gtkeidzofo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gtzclidcrb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.haohaochexian.top/Article/details/gtyvhjqlna.html

[K07] 进制转换
来源：http://dali.cqqwz.cn/Article/details/gtchtvbedk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtwacdxjht.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigufen.top/Article/details/gtrbixdtqn.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gtyoygjbuv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gttwstpvhs.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtzmezguux.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xinyue.icu/Article/details/gtrsedsdpk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xuetiantiany.cn/Article/details/gtlaxfxnir.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gtphqvlvyh.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gzhubu.top/Article/details/gtdsydshhf.html

Py:   pickle.dumps(obj)
来源：http://dali.sufxvd.cn/Article/details/gthtaynats.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.fzhhl.top/Article/details/gtnmmktxzl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.9152youxi.cn/Article/details/gtcgvovgdf.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.aizwys.cn/Article/details/gtsyfxatfs.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shangyingyoupin.top/Article/details/gtxhpxfhds.html

Go:   encoding/gob
来源：http://dali.pycfn.com/Article/details/gtunvxvail.html

Ruby: Marshal.dump(obj)
来源：http://dali.hnqzz.top/Article/details/gtyxdpyxcx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.0kj1m.cn/Article/details/gtbqpdeosr.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtmotbbodq.html

L. 网络请求
来源：http://dali.xuetiantiany.cn/Article/details/gtbfomkzzz.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttxvwtoav.html

[L01] 发送 GET 请求
来源：http://dali.yuxming.cn/Article/details/gtlahwxqzw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.svipenyu.cn/Article/details/gtobsqmbra.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.daxiang520.top/Article/details/gtuuuxiwib.html

JS:   await fetch(url)
来源：http://dali.svipenyu.cn/Article/details/gtskfksywc.html

TS:   await fetch(url)
来源：http://dali.sysykeji.top/Article/details/gtyoalykzi.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.havefunace.top/Article/details/gtkmhgdkrc.html

Go:   resp, err := http.Get(url)
来源：http://dali.yuanzhike.top/Article/details/gtunvauahx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jianghu66.top/Article/details/gtwfdazcjz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sweek.top/Article/details/gtinkjgvhl.html

[L02] 发送 POST JSON
来源：http://dali.shuidangran.top/Article/details/gtnnhsfybq.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.mhx1999.top/Article/details/gtesedaufg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.daria6918.cn/Article/details/gthxuopxgm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgufenzy.top/Article/details/gtakzcyeyc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ydzc1.top/Article/details/gtwraxkadi.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.tanke756.top/Article/details/gthnupuzgt.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hywenlv.cn/Article/details/gtgbqbjgsn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yvedp.cn/Article/details/gtbwlvubrx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.redwolf501.top/Article/details/gtlqxxmxse.html

[L03] 设置自定义请求头
来源：http://dali.nanxuanxn.top/Article/details/gtthqbkksh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jqgufenzy.top/Article/details/gtjyeofbof.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cucudq.cn/Article/details/gtyvpifgcp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hywenlv.cn/Article/details/gtkmdomftn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxuanxn.top/Article/details/gtbecrvxez.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cashguo.top/Article/details/gthnmfpcqt.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.dashuyun.cn/Article/details/gtjuaweezp.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.pycfn.com/Article/details/gttsacpnxm.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hongshengwenyu.top/Article/details/gtiuxkqiji.html

[L04] 设置超时
来源：http://dali.jinqigufen.top/Article/details/gtucdrderg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.iojbl.cn/Article/details/gtgrkrarty.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xuetiantiany.cn/Article/details/gtbbqkgedz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aibaodan.cn/Article/details/gttedcxuic.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cheryme.top/Article/details/gtmuqrckbu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtboycbdkm.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shzxlz.cn/Article/details/gtotddsvll.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sxryk.cn/Article/details/gtolfbunqp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.svipenyu.cn/Article/details/gtxelikusl.html

[L05] 上传文件（multipart）
来源：http://dali.tianlin.xyz/Article/details/gtqatvovap.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ehwqpu.com/Article/details/gtiiydkdue.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.snrcjt.cn/Article/details/gttihfvssb.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ehwqpu.com/Article/details/gtbztrwmiw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.vqdsnc.cn/Article/details/gttuuxuptf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cashguo.top/Article/details/gtzzqmciov.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.vqdsnc.cn/Article/details/gtxaobwczb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gtxsagoshk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtrbvcpozr.html

[L06] 解析响应为 JSON
来源：http://dali.aibaodan.cn/Article/details/gtpsydunpk.html

Py:   resp.json()
来源：http://dali.yonumen.top/Article/details/gtjnprdwnp.html

PHP:  json_decode($body, true);
来源：http://dali.shangyingyoupin.top/Article/details/gtdsiroiaq.html

JS:   await resp.json()
来源：http://dali.aibaodan.cn/Article/details/gtwcrdwbpy.html

TS:   await resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqimqvyu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj20258.top/Article/details/gtzsvqmcxc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhongyouzk.top/Article/details/gtpsdpqjne.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj20258888.top/Article/details/gtcbvmqaml.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shangyingyoupin.top/Article/details/gttcyhgojh.html

[L07] 处理 HTTP 状态码
来源：http://dali.jyoumei.cn/Article/details/gtizfvhwlq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.daria6918.cn/Article/details/gtnkrixetm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shzxlz.cn/Article/details/gtafhcdzxs.html

JS:   resp.ok;  resp.status
来源：http://dali.gaohongyu789.top/Article/details/gteqcwrawi.html

TS:   resp.ok;  resp.status
来源：http://dali.yongpay.top/Article/details/gtcqarrsxi.html

Java: resp.statusCode()
来源：http://dali.bjfxy.top/Article/details/gtjtlsjxrk.html

Go:   resp.StatusCode
来源：http://dali.smart0.xyz/Article/details/gtzlmrqyot.html

Ruby: resp.code.to_i
来源：http://dali.316326.xyz/Article/details/gtvjupvxyn.html

C#:   (int)resp.StatusCode
来源：http://dali.guannengcc.top/Article/details/gtlhgnypvu.html

[L08] 并发请求多个地址
来源：http://dali.jianghu66.top/Article/details/gtceecuctw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jiagoushi.top/Article/details/gtbhprtmwy.html

PHP:  curl_multi_init() 系列
来源：http://dali.pycfn.com/Article/details/gtklmkopqs.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ppjwa.cn/Article/details/gtbkjabgci.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzkjdoown.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.aizwys.cn/Article/details/gtoexjxbdw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.dashuyun.cn/Article/details/gthuncnisd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.dianchejie.cn/Article/details/gtbhscsraq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.wangdashe.top/Article/details/gtubdjulum.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtsxbrtaid.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenjidiqi.icu/Article/details/gtcqjlfgay.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtfqzzixqd.html

[M01] 读取命令行参数
来源：http://dali.haohaochexian.top/Article/details/gtdigtkhis.html

Py:   sys.argv[1:]
来源：http://dali.pengpengdd.cyou/Article/details/gtaldiqqdd.html

PHP:  $argv;  $argc;
来源：http://dali.mhx1999.top/Article/details/gtngixisgq.html

JS:   process.argv.slice(2)
来源：http://dali.fzhhl.top/Article/details/gtcbhercvy.html

TS:   process.argv.slice(2)
来源：http://dali.dianchejie.cn/Article/details/gtctfllyba.html

Java: args 数组（main 方法参数）
来源：http://dali.dianchejie.cn/Article/details/gtzvhptozn.html

Go:   os.Args[1:]
来源：http://dali.svipenyu.cn/Article/details/gttytoxkbc.html

Ruby: ARGV
来源：http://dali.xinyue.icu/Article/details/gtswrvtsci.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hammf.cn/Article/details/gtxxuxyuqb.html

[M02] 读取环境变量
来源：http://dali.0kj1m.cn/Article/details/gtglhratgp.html

Py:   os.environ.get("HOME")
来源：http://dali.yueranfly.top/Article/details/gtzgmttkqt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.iojbl.cn/Article/details/gtbhexysuj.html

JS:   process.env.HOME
来源：http://dali.fengsongda.top/Article/details/gtbpcporsf.html

TS:   process.env.HOME
来源：http://dali.nanxuanxn.top/Article/details/gthzssgwcn.html

Java: System.getenv("HOME")
来源：http://dali.yongpay.top/Article/details/gtctueqowv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ybcxt.top/Article/details/gtaynnugoy.html

Ruby: ENV["HOME"]
来源：http://dali.sufxvd.cn/Article/details/gtdwufbghr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xylfe.cn/Article/details/gtdottizkj.html

[M03] 执行外部命令
来源：http://dali.hnxiangtu.top/Article/details/gtqmyuzmpg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yanxiufei.cn/Article/details/gtfufdirui.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sxryk.cn/Article/details/gtbbhclqug.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tanke756.top/Article/details/gtvrepdbjz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.pengpengdd.cyou/Article/details/gtwgbvcxkc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shangyingyoupin.top/Article/details/gtgjibjlme.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhixingplan.top/Article/details/gtqqzcotbl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinghuilouyu.cn/Article/details/gtfdprydcx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhoulong.xyz/Article/details/gtjjigbtkt.html

[M04] 获取当前工作目录
来源：http://dali.zycfv.cn/Article/details/gtuadxyeja.html

Py:   os.getcwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxvmlomwa.html

PHP:  getcwd();
来源：http://dali.yj20258888.top/Article/details/gtzwspcnki.html

JS:   process.cwd()
来源：http://dali.ppjwa.cn/Article/details/gttpfyspzw.html

TS:   process.cwd()
来源：http://dali.yanxiufei.cn/Article/details/gtezivnkuf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shanyushiyangtech.top/Article/details/gtavlwiksu.html

Go:   os.Getwd()
来源：http://dali.redwolf501.top/Article/details/gtwifsfsfy.html

Ruby: Dir.pwd
来源：http://dali.chenzaomai.com/Article/details/gtlktgwkfj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hfpthk.cn/Article/details/gtkgmojfhs.html

[M05] 设置退出码
来源：http://dali.birdmap.top/Article/details/gtvgcbckcj.html

Py:   sys.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyobohqqw.html

PHP:  exit(1);
来源：http://dali.fengsongda.top/Article/details/gtzkwnaqft.html

JS:   process.exit(1)
来源：http://dali.daria6918.cn/Article/details/gthxsbcddm.html

TS:   process.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnwxxllgh.html

Java: System.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gtbhzitnvj.html

Go:   os.Exit(1)
来源：http://dali.fzhhl.top/Article/details/gtzrasfvyn.html

Ruby: exit 1
来源：http://dali.xylfe.cn/Article/details/gtpyojvrwg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hywenlv.cn/Article/details/gtgaorouoh.html

[M06] 向标准错误输出
来源：http://dali.9152youxi.cn/Article/details/gtpkwhlfjb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jyoumei.cn/Article/details/gtxcyoafef.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yuxming.cn/Article/details/gticvmrlru.html

JS:   console.error("err")
来源：http://dali.tianlin.xyz/Article/details/gtbdunhnfq.html

TS:   console.error("err")
来源：http://dali.hysaishi.cn/Article/details/gtqtapkore.html

Java: System.err.println("err")
来源：http://dali.yongpay.top/Article/details/gtjjhuksjj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.c1oappe.top/Article/details/gtkjqitvtk.html

Ruby: warn "err"
来源：http://dali.xziqi.cn/Article/details/gtwejaxxqs.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.wangshuangyany.cn/Article/details/gtfolwzply.html

[M07] 判断是否为主入口
来源：http://dali.shanyushiyangtech.top/Article/details/gtttyzyykx.html

Py:   if __name__ == "__main__":
来源：http://dali.cheryme.top/Article/details/gtipotezat.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.havefunace.top/Article/details/gtbhuyrpow.html

JS:   require.main === module
来源：http://dali.zhixingplan.top/Article/details/gtqaexmwzl.html

TS:   require.main === module
来源：http://dali.yuxming.cn/Article/details/gtgftnfcyc.html

Java: public static void main(String[] args)
来源：http://dali.gzhubu.top/Article/details/gtdvnykyyr.html

Go:   func main()
来源：http://dali.zhixingplan.top/Article/details/gteozzvxqg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gzhubu.top/Article/details/gtrlkqciyj.html

C#:   static void Main(string[] args)
来源：http://dali.hnqzz.top/Article/details/gtetljvozk.html

[M08] 获取系统与运行时信息
来源：http://dali.yangfankeji.com/Article/details/gtslmstnks.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xuanzx.com/Article/details/gtgisrvwgq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jianghu66.top/Article/details/gtrzzrecub.html

JS:   process.platform;  process.version
来源：http://dali.jiagoushi.top/Article/details/gtqcnqxxxa.html

TS:   process.platform;  process.version
来源：http://dali.aizwys.cn/Article/details/gtupnpfmiv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.fengsongda.top/Article/details/gtrmjqmqms.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinghuilouyu.cn/Article/details/gtthcnlocz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yuanzhike.top/Article/details/gtbjooiqwn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xylfe.cn/Article/details/gtsksszzbn.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtwzgcwvyi.html

N. 数据结构与算法
来源：http://dali.feifeiyinyue.top/Article/details/gtrewrrlwh.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtujikwfeg.html

[N01] 二分查找（有序数组）
来源：http://dali.yuanzhike.top/Article/details/gtskfdwbgp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtfcawcgok.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jlsjyb.cn/Article/details/gtejevfovj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj202588.top/Article/details/gtirzrbsjv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gtguvtsjao.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtzqxhdgco.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtvafbdxff.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhongyouzk.top/Article/details/gttxgntvfy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gteyrvoclm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jianghu66.top/Article/details/gtgpuvkqmw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.0kj1m.cn/Article/details/gtixktcxsl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ivvv.top/Article/details/gtbrtyitbo.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwudeiyfy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.c1oappe.top/Article/details/gtqrmqqzos.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.mhx1999.top/Article/details/gtkldgyixo.html

Go:   slices.Sort(arr)
来源：http://dali.tanke756.top/Article/details/gtnqlkdwed.html

Ruby: arr.sort
来源：http://dali.gzhubu.top/Article/details/gthvdbaizp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.birdmap.top/Article/details/gttfdxarrl.html

[N03] 快速排序（分治示例）
来源：http://dali.quarkkingdee.top/Article/details/gtzgoyblht.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yonumen.top/Article/details/gtrtmcmsau.html

PHP:  // 递归实现，或用 usort
来源：http://dali.dianchejie.cn/Article/details/gtxmlkdewu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhongyouzk.top/Article/details/gthglxphfu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.snrcjt.cn/Article/details/gtnzswbral.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.tian-w.cn/Article/details/gthpahvmos.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.c1oappe.top/Article/details/gtjyqdpesb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jyoumei.cn/Article/details/gtjozcngad.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinqigufen.top/Article/details/gtgftllztm.html

[N04] 斐波那契数列
来源：http://dali.daxiang520.top/Article/details/gtgsjlltwi.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.tanke756.top/Article/details/gttmnjxbuh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.nanxuanxn.top/Article/details/gtzwbgzzqc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.vqdsnc.cn/Article/details/gtbpmzvhkm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hysaishi.cn/Article/details/gtnnzuqhkm.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ybcxt.top/Article/details/gthjtzwmah.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmyelfzuv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ydzc1.top/Article/details/gtovvbrtgs.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gtvwvkjjux.html

[N05] 最大公约数
来源：http://dali.hnqzz.top/Article/details/gtwdxudbxl.html

Py:   math.gcd(a, b)
来源：http://dali.haohaochexian.top/Article/details/gtsuoibsjc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.fengsongda.top/Article/details/gtqfcxqnxi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cucudq.cn/Article/details/gtypkaujus.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj202588.top/Article/details/gtvhdfpvox.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zdqjudy.top/Article/details/gtoexcybve.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jlsjyb.cn/Article/details/gtzbklvtiu.html

Ruby: a.gcd(b)
来源：http://dali.aibaodan.cn/Article/details/gtlnwqvpuy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jqgfzy.top/Article/details/gtgqhwxuyp.html

[N06] 判断回文字符串
来源：http://dali.hammf.cn/Article/details/gtdyeonwtk.html

Py:   s == s[::-1]
来源：http://dali.kuanghao11.cn/Article/details/gtqfjsvwed.html

PHP:  $s === strrev($s);
来源：http://dali.quarkkingdee.top/Article/details/gtifnpxklw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gtfkcwbnsz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gtmdwklqse.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hnqzz.top/Article/details/gteuguubbl.html

Go:   // 双指针从两端比较
来源：http://dali.hnxiangtu.top/Article/details/gtxovpebcj.html

Ruby: s == s.reverse
来源：http://dali.jyoumei.cn/Article/details/gtrgwucriw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.9152youxi.cn/Article/details/gtqefksrmo.html

[N07] 两数之和（返回下标）
来源：http://dali.cucudq.cn/Article/details/gttsibiawi.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yangfankeji.com/Article/details/gtxyctutuh.html


<!-- 参考信息 -->