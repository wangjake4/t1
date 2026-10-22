代发 wailian999

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.birdmap.top/Article/details/gt2bqdlvcvb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.bjfxy.top/Article/details/gt2qiwlvwih.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aibaodan.cn/Article/details/gt2lfxbgsna.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jiagoushi.top/Article/details/gt2zfqptgkt.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj20258888.top/Article/details/gt2slzbzkhu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ehwqpu.com/Article/details/gt2wwjaqoqj.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cheryme.top/Article/details/gt2pyggvdmy.html

[J10] 取今天 / 本月第一天
来源：http://dali.hfpthk.cn/Article/details/gt2xmpuwila.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xuanzx.com/Article/details/gt2gsospazz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fodlgdla.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nanxinkj.top/Article/details/gt2qgmeysyg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.tian-w.cn/Article/details/gt2uurnttup.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.smart0.xyz/Article/details/gt2uhebiohg.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj20258888.top/Article/details/gt2whnnwqzm.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhengqikj.top/Article/details/gt2fzmtywsx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yuxming.cn/Article/details/gt2eqbnjcth.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2nffcnqhj.html

K. JSON 与序列化
来源：http://dali.316326.xyz/Article/details/gt2vbuaydpi.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2zgizcofz.html

[K01] 对象转 JSON 字符串
来源：http://dali.xuanzx.com/Article/details/gt2muypeytd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yueranfly.top/Article/details/gt2vutovjsa.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigufen.top/Article/details/gt2ptiztcir.html

JS:   JSON.stringify(obj)
来源：http://dali.gzhubu.top/Article/details/gt2aqhhjnzt.html

TS:   JSON.stringify(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wegoioqk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yuanzhike.top/Article/details/gt2hpwdcwpj.html

Go:   json.Marshal(obj)
来源：http://dali.zycfv.cn/Article/details/gt2pufwfdil.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.feifeiyinyue.top/Article/details/gt2ubwnxbrp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2orugqmkq.html

[K02] JSON 字符串转对象
来源：http://dali.aibaodan.cn/Article/details/gt2pgyduzri.html

Py:   json.loads(s)
来源：http://dali.hammf.cn/Article/details/gt2lxrwhbfl.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gaohongyu789.top/Article/details/gt2pzwfhqap.html

JS:   JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gt2muxvwktk.html

TS:   JSON.parse(s)
来源：http://dali.cashguo.top/Article/details/gt2rbqogeke.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.tanke756.top/Article/details/gt2hqpqxaqy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.dashuyun.cn/Article/details/gt2jsysksko.html

Ruby: JSON.parse(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ldcnmyzo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2owmxusdr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.dashuyun.cn/Article/details/gt2evpngxqt.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sysykeji.top/Article/details/gt2kbncibxh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xinyue.icu/Article/details/gt2pcuaouar.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.dashuyun.cn/Article/details/gt2bhmniavh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nwbrower.top/Article/details/gt2xkopqadc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2imxwlujf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yj20258888.top/Article/details/gt2pyhzarqw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.bjfxy.top/Article/details/gt2fnxtkjjw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvwnmbw.html

[K04] 读取 JSON 文件
来源：http://dali.316326.xyz/Article/details/gt2pwxoyffa.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.birdmap.top/Article/details/gt2elaxbwmt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cqqwz.cn/Article/details/gt2qftrokse.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sysykeji.top/Article/details/gt2uoggfyet.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.9152youxi.cn/Article/details/gt2oiyskrik.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sxryk.cn/Article/details/gt2dessjyko.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yj202588.top/Article/details/gt2aybgyphb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.c1oappe.top/Article/details/gt2sfahljgt.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yj20258888.top/Article/details/gt2ktzvpbqf.html

[K05] 深拷贝对象
来源：http://dali.shangyingyoupin.top/Article/details/gt2hgnuhzwb.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2sgxxdule.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jianghu66.top/Article/details/gt2mblzrnox.html

JS:   structuredClone(obj)
来源：http://dali.yj202588.top/Article/details/gt2viixxsti.html

TS:   structuredClone(obj)
来源：http://dali.hnqzz.top/Article/details/gt2szkghddi.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kfpxvznb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sweek.top/Article/details/gt2wpheozez.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.birdmap.top/Article/details/gt2exmzpofs.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.daria6918.cn/Article/details/gt2mmiqgqph.html

[K06] 解析 URL 查询串
来源：http://dali.shzxlz.cn/Article/details/gt2mstnbzhf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgufenzy.top/Article/details/gt2hhzrxohv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yvedp.cn/Article/details/gt2zaarjgmd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jgkwgtps.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnqzz.top/Article/details/gt2bxsbvkcr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.iojbl.cn/Article/details/gt2rwdlfahf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.daxiang520.top/Article/details/gt2nueurows.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.fengsongda.top/Article/details/gt2yzqhrmmp.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xziqi.cn/Article/details/gt2auybgrdp.html

[K07] 进制转换
来源：http://dali.xinyue.icu/Article/details/gt2jfswkdrj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gt2mafdaqgm.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tianlin.xyz/Article/details/gt2qldjjchi.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gt2qdiafdou.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.tanke756.top/Article/details/gt2ppgszers.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lcmctfgu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hysaishi.cn/Article/details/gt2ulxeldfy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gllglzrn.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gt2qxaucfju.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.0kj1m.cn/Article/details/gt2egcicyln.html

Py:   pickle.dumps(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2bsybilvb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hammf.cn/Article/details/gt2grznukxd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xylfe.cn/Article/details/gt2veljhscj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jlsjyb.cn/Article/details/gt2jhbbpbjt.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.0kj1m.cn/Article/details/gt2trkgrcmj.html

Go:   encoding/gob
来源：http://dali.pycfn.com/Article/details/gt2tqwqqumm.html

Ruby: Marshal.dump(obj)
来源：http://dali.c1oappe.top/Article/details/gt2tzjvbuhd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yj202588.top/Article/details/gt2wibqiqeb.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2jtrcbpyz.html

L. 网络请求
来源：http://dali.chenlongwang.top/Article/details/gt2rjeyyjfb.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2cddnewsx.html

[L01] 发送 GET 请求
来源：http://dali.gaohongyu789.top/Article/details/gt2cmnmvrxb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ivvv.top/Article/details/gt2pbzayejd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yuanzhike.top/Article/details/gt2lawwohml.html

JS:   await fetch(url)
来源：http://dali.yj20258.top/Article/details/gt2kwuicyzk.html

TS:   await fetch(url)
来源：http://dali.daxiang520.top/Article/details/gt2bgacumip.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jiagoushi.top/Article/details/gt2xxjzsygs.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhongyouzk.top/Article/details/gt2obvmzymi.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jmvciqsq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinqigfzy.top/Article/details/gt2vrxcjhfu.html

[L02] 发送 POST JSON
来源：http://dali.gogol.net.cn/Article/details/gt2fuunddms.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jiagoushi.top/Article/details/gt2kiisujbs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yj202588.top/Article/details/gt2bywixgjc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ydzc1.top/Article/details/gt2xsxmyfrg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ziiuzzza.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.haohaochexian.top/Article/details/gt2wlqjbbgi.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gkhemxqq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jyoumei.cn/Article/details/gt2mlpudhko.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jiagoushi.top/Article/details/gt2ggkokmvb.html

[L03] 设置自定义请求头
来源：http://dali.nwbrower.top/Article/details/gt2dukgxqlk.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sysykeji.top/Article/details/gt2tkcqmknz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sxryk.cn/Article/details/gt2brebggat.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhoulong.xyz/Article/details/gt2kqiukbvn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yongpay.top/Article/details/gt2fxwnvopk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.nanxuanxn.top/Article/details/gt2aktcwvbz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cucudq.cn/Article/details/gt2zihtwavl.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hnxiangtu.top/Article/details/gt2okojpcmi.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.svipenyu.cn/Article/details/gt2pngokjjl.html

[L04] 设置超时
来源：http://dali.hnqzz.top/Article/details/gt2zudkkrqz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yj20258888.top/Article/details/gt2yngbixzl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xuetiantiany.cn/Article/details/gt2paspnjdg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xziqi.cn/Article/details/gt2wumxtjrx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.meibo888.top/Article/details/gt2rpmaymtq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.svipenyu.cn/Article/details/gt2cihrqcce.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.daria6918.cn/Article/details/gt2pbulawxa.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cdnleiting.top/Article/details/gt2yvmvzcnx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.andypj.xyz/Article/details/gt2soujmnyv.html

[L05] 上传文件（multipart）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pizkajnw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zdqjudy.top/Article/details/gt2advmdhoz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sweek.top/Article/details/gt2lfgwygjt.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhiwuduotai.top/Article/details/gt2lelocxsh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yanxiufei.cn/Article/details/gt2gjqksyrx.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.dashuyun.cn/Article/details/gt2quaqvycr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.aizwys.cn/Article/details/gt2tyckssle.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ehwqpu.com/Article/details/gt2ydgslzqx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2pwqwinmw.html

[L06] 解析响应为 JSON
来源：http://dali.aizwys.cn/Article/details/gt2oafsbgfv.html

Py:   resp.json()
来源：http://dali.hfpthk.cn/Article/details/gt2ulxrxbds.html

PHP:  json_decode($body, true);
来源：http://dali.hnxiangtu.top/Article/details/gt2bjnecvhz.html

JS:   await resp.json()
来源：http://dali.yj20258888.top/Article/details/gt2yixvdevv.html

TS:   await resp.json()
来源：http://dali.chenjidiqi.icu/Article/details/gt2gwuirjjp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.mhx1999.top/Article/details/gt2wppyevvx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cqqwz.cn/Article/details/gt2bxghnszi.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jianghu66.top/Article/details/gt2gwsaegdg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.aibaodan.cn/Article/details/gt2xpadlizo.html

[L07] 处理 HTTP 状态码
来源：http://dali.chenzaomai.com/Article/details/gt2bkbtslqz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jianghu66.top/Article/details/gt2mauzadtp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sweek.top/Article/details/gt2oppkhdrt.html

JS:   resp.ok;  resp.status
来源：http://dali.xylfe.cn/Article/details/gt2vkxkqzkc.html

TS:   resp.ok;  resp.status
来源：http://dali.zhiwuduotai.top/Article/details/gt2hneokblc.html

Java: resp.statusCode()
来源：http://dali.yuanzhike.top/Article/details/gt2xufdgskl.html

Go:   resp.StatusCode
来源：http://dali.gogol.net.cn/Article/details/gt2jiiavnbs.html

Ruby: resp.code.to_i
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gihsbsmk.html

C#:   (int)resp.StatusCode
来源：http://dali.cqqwz.cn/Article/details/gt2tkvjujga.html

[L08] 并发请求多个地址
来源：http://dali.hfpthk.cn/Article/details/gt2bzavljow.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yj20258.top/Article/details/gt2elpmbilg.html

PHP:  curl_multi_init() 系列
来源：http://dali.yvedp.cn/Article/details/gt2nwiqhrif.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigufen.top/Article/details/gt2ioqehgad.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgfzy.top/Article/details/gt2wavrwdnu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hysaishi.cn/Article/details/gt2bnrufsyp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yuanzhike.top/Article/details/gt2bjwmvbev.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.tianlin.xyz/Article/details/gt2awtikfib.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.svipenyu.cn/Article/details/gt2iaykscse.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2nixjvbly.html

M. 命令行 / 进程 / 环境
来源：http://dali.xuetiantiany.cn/Article/details/gt2tswkdeek.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2ndmtzzyt.html

[M01] 读取命令行参数
来源：http://dali.yanxiufei.cn/Article/details/gt2stpvccwr.html

Py:   sys.argv[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gt2rbfrwpfl.html

PHP:  $argv;  $argc;
来源：http://dali.jqgfzy.top/Article/details/gt2fuxhiokk.html

JS:   process.argv.slice(2)
来源：http://dali.tanke756.top/Article/details/gt2kjdmneze.html

TS:   process.argv.slice(2)
来源：http://dali.zhixingplan.top/Article/details/gt2csdiffmr.html

Java: args 数组（main 方法参数）
来源：http://dali.yj20258888.top/Article/details/gt2rapyzyak.html

Go:   os.Args[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2khkkpkll.html

Ruby: ARGV
来源：http://dali.xuetiantiany.cn/Article/details/gt2zpgfhmxu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.meibo888.top/Article/details/gt2dfxfphch.html

[M02] 读取环境变量
来源：http://dali.cheryme.top/Article/details/gt2wkitctvj.html

Py:   os.environ.get("HOME")
来源：http://dali.sweek.top/Article/details/gt2vuxgzlxz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nanxuanxn.top/Article/details/gt2kxwjfpoi.html

JS:   process.env.HOME
来源：http://dali.jqgufenzy.top/Article/details/gt2kgxpuvvm.html

TS:   process.env.HOME
来源：http://dali.guowangkeji.top/Article/details/gt2omabrzfl.html

Java: System.getenv("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gt2knaltymu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zycfv.cn/Article/details/gt2ggbhuzhg.html

Ruby: ENV["HOME"]
来源：http://dali.chenlongwang.top/Article/details/gt2itaptdpk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gt2hinbenfd.html

[M03] 执行外部命令
来源：http://dali.jqgufenzy.top/Article/details/gt2jrmsurmn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yvedp.cn/Article/details/gt2nymdypvz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.guowangkeji.top/Article/details/gt2ugstnxqj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ycrwgjji.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuanzhike.top/Article/details/gt2uykwplml.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zycfv.cn/Article/details/gt2cgwvazdm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tian-w.cn/Article/details/gt2cektjbqn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hongshengwenyu.top/Article/details/gt2tyfxiztz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.fzhhl.top/Article/details/gt2xlwogrki.html

[M04] 获取当前工作目录
来源：http://dali.pycfn.com/Article/details/gt2ttubdymx.html

Py:   os.getcwd()
来源：http://dali.dianchejie.cn/Article/details/gt2vntsgxsm.html

PHP:  getcwd();
来源：http://dali.shangyingyoupin.top/Article/details/gt2fnzvsiji.html

JS:   process.cwd()
来源：http://dali.gogol.net.cn/Article/details/gt2dmqjksxr.html

TS:   process.cwd()
来源：http://dali.daxiang520.top/Article/details/gt2srawioyb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sysykeji.top/Article/details/gt2zgaogazt.html

Go:   os.Getwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2flwacdlb.html

Ruby: Dir.pwd
来源：http://dali.chenzaomai.com/Article/details/gt2xrjwuxbq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zycfv.cn/Article/details/gt2hmdeisce.html

[M05] 设置退出码
来源：http://dali.jinqigufen.top/Article/details/gt2ifdgffvd.html

Py:   sys.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gt2vtnsphta.html

PHP:  exit(1);
来源：http://dali.cashguo.top/Article/details/gt2jwzdsyic.html

JS:   process.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vnwpaejn.html

TS:   process.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gt2yxtvyhwl.html

Java: System.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gt2gbvydxjk.html

Go:   os.Exit(1)
来源：http://dali.gzhubu.top/Article/details/gt2pzdzwspm.html

Ruby: exit 1
来源：http://dali.kuanghao11.cn/Article/details/gt2tgnwntcb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.dashuyun.cn/Article/details/gt2aplonofc.html

[M06] 向标准错误输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hcefnwgt.html

Py:   print("err", file=sys.stderr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jyynmmua.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yonumen.top/Article/details/gt2sjpwtqoy.html

JS:   console.error("err")
来源：http://dali.iojbl.cn/Article/details/gt2vbvpuxjc.html

TS:   console.error("err")
来源：http://dali.xuetiantiany.cn/Article/details/gt2mnvbavhh.html

Java: System.err.println("err")
来源：http://dali.andypj.xyz/Article/details/gt2sopwsuxj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj202588.top/Article/details/gt2xpvcssmf.html

Ruby: warn "err"
来源：http://dali.yueranfly.top/Article/details/gt2jaohyhca.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.mhx1999.top/Article/details/gt2jvefsgqo.html

[M07] 判断是否为主入口
来源：http://dali.guowangkeji.top/Article/details/gt2uxhjzzir.html

Py:   if __name__ == "__main__":
来源：http://dali.nanxuanxn.top/Article/details/gt2pkvxarmh.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.nanxinkj.top/Article/details/gt2owddlxzs.html

JS:   require.main === module
来源：http://dali.cqqwz.cn/Article/details/gt2vccutopd.html

TS:   require.main === module
来源：http://dali.ivvv.top/Article/details/gt2vlmtpqdq.html

Java: public static void main(String[] args)
来源：http://dali.hfpthk.cn/Article/details/gt2fonkekbt.html

Go:   func main()
来源：http://dali.smart0.xyz/Article/details/gt2nxpffcgf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhongyouzk.top/Article/details/gt2cpkqwnph.html

C#:   static void Main(string[] args)
来源：http://dali.vqdsnc.cn/Article/details/gt2zclmduxi.html

[M08] 获取系统与运行时信息
来源：http://dali.zdqjudy.top/Article/details/gt2eircuefm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xuanzx.com/Article/details/gt2axhgletk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.quarkkingdee.top/Article/details/gt2hzyftjre.html

JS:   process.platform;  process.version
来源：http://dali.tianlin.xyz/Article/details/gt2ylivkign.html

TS:   process.platform;  process.version
来源：http://dali.daria6918.cn/Article/details/gt2tipofjei.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.redwolf501.top/Article/details/gt2hskgdkqf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jiagoushi.top/Article/details/gt2kdbwlcvv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.kuanghao11.cn/Article/details/gt2gyrymhqb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ppjwa.cn/Article/details/gt2malhroyc.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2ggmzftvl.html

N. 数据结构与算法
来源：http://dali.ydzc1.top/Article/details/gt2yniksrms.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2odgvplcq.html

[N01] 二分查找（有序数组）
来源：http://dali.9152youxi.cn/Article/details/gt2sqshuhrl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gt2vimfpkbi.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinqigfzy.top/Article/details/gt2pjstoila.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tianlin.xyz/Article/details/gt2yskerlmb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuanzx.com/Article/details/gt2lrovbfrh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.iojbl.cn/Article/details/gt2blvsbnwx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gt2rqthsijh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ivvv.top/Article/details/gt2hsuqtfsw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.smart0.xyz/Article/details/gt2grqgptoo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shangyingyoupin.top/Article/details/gt2jhcfcmey.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhixingplan.top/Article/details/gt2uzyihydh.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yueranfly.top/Article/details/gt2thkqwmit.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jiagoushi.top/Article/details/gt2eptynjkx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ehwqpu.com/Article/details/gt2szegtahx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.daxiang520.top/Article/details/gt2ctusulld.html

Go:   slices.Sort(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2qqzxrvkz.html

Ruby: arr.sort
来源：http://dali.cqqwz.cn/Article/details/gt2fdxjbrjz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.9152youxi.cn/Article/details/gt2sopesxkz.html

[N03] 快速排序（分治示例）
来源：http://dali.yuanzhike.top/Article/details/gt2leviyqys.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hnxiangtu.top/Article/details/gt2wknojmdj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.fengsongda.top/Article/details/gt2jctvrpor.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gotoacloud.top/Article/details/gt2pqeynbjl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuxming.cn/Article/details/gt2mgdglbag.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vyegtdtc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cashguo.top/Article/details/gt2xytqmamm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sysykeji.top/Article/details/gt2wprhzdjb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hysaishi.cn/Article/details/gt2lkqmqrfy.html

[N04] 斐波那契数列
来源：http://dali.jlsjyb.cn/Article/details/gt2qzduowwc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258888.top/Article/details/gt2pgundtdq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yuanzhike.top/Article/details/gt2ddqogcgz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tanke756.top/Article/details/gt2fnqnhmlk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangdashe.top/Article/details/gt2zgkhhgvh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yj20258888.top/Article/details/gt2qrfxjlsa.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xuanzx.com/Article/details/gt2ujpzodir.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yonumen.top/Article/details/gt2hpclcxpz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.vqdsnc.cn/Article/details/gt2abgdkbgh.html

[N05] 最大公约数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cpfvyjnc.html

Py:   math.gcd(a, b)
来源：http://dali.cucudq.cn/Article/details/gt2ferlseys.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cdnleiting.top/Article/details/gt2iclclrgu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxuanxn.top/Article/details/gt2xgtwqwty.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guannengcc.top/Article/details/gt2uuoublar.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.gzhubu.top/Article/details/gt2ahrpnufk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ppjwa.cn/Article/details/gt2ftfcvdhj.html

Ruby: a.gcd(b)
来源：http://dali.sysykeji.top/Article/details/gt2frxiuanw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.c1oappe.top/Article/details/gt2xiapgtpg.html

[N06] 判断回文字符串
来源：http://dali.zhengqikj.top/Article/details/gt2wfyrdqkz.html

Py:   s == s[::-1]
来源：http://dali.yangfankeji.com/Article/details/gt2beddffqu.html

PHP:  $s === strrev($s);
来源：http://dali.nwbrower.top/Article/details/gt2xzbreika.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gt2ubweiyid.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gt2ezdlmvwi.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hysaishi.cn/Article/details/gt2naguwpqd.html

Go:   // 双指针从两端比较
来源：http://dali.jianghu66.top/Article/details/gt2ijwakrbe.html

Ruby: s == s.reverse
来源：http://dali.c1oappe.top/Article/details/gt2fwpxsnhr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.fzhhl.top/Article/details/gt2nndapgeb.html

[N07] 两数之和（返回下标）
来源：http://dali.tian-w.cn/Article/details/gt2hmqocuvy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cheryme.top/Article/details/gt2fatolqah.html


<!-- 参考信息 -->