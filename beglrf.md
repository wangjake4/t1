代发 wailian999

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cqqwz.cn/Article/details/gt2wagldipc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wwtwhkgy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wgnmxgou.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.redwolf501.top/Article/details/gt2esphgccq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhoulong.xyz/Article/details/gt2mzqxwzky.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.vqdsnc.cn/Article/details/gt2ivhkwana.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ybcxt.top/Article/details/gt2rxredicq.html

[J10] 取今天 / 本月第一天
来源：http://dali.haohaochexian.top/Article/details/gt2fparudmg.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hnxiangtu.top/Article/details/gt2shknzxon.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.havefunace.top/Article/details/gt2npmjooij.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.daxiang520.top/Article/details/gt2qdymzppz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj20258.top/Article/details/gt2wqhpfaqj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.316326.xyz/Article/details/gt2stgbuiid.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.birdmap.top/Article/details/gt2fzfbskbp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hysaishi.cn/Article/details/gt2ijwmeftv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cashguo.top/Article/details/gt2iuamxiqr.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2btxdycdg.html

K. JSON 与序列化
来源：http://dali.yvedp.cn/Article/details/gt2bgbhmgyh.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2adjdljmi.html

[K01] 对象转 JSON 字符串
来源：http://dali.yvedp.cn/Article/details/gt2roiidhnq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.316326.xyz/Article/details/gt2gegsbmrc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2amqaxvab.html

JS:   JSON.stringify(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2qytuliba.html

TS:   JSON.stringify(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2vxfwncop.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hnxiangtu.top/Article/details/gt2wlsvzkfw.html

Go:   json.Marshal(obj)
来源：http://dali.c1oappe.top/Article/details/gt2cayawpzu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hfpthk.cn/Article/details/gt2uazfaszi.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.redwolf501.top/Article/details/gt2oktfdggg.html

[K02] JSON 字符串转对象
来源：http://dali.jlsjyb.cn/Article/details/gt2rzbuhjal.html

Py:   json.loads(s)
来源：http://dali.wangdashe.top/Article/details/gt2ogrmtsim.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shzxlz.cn/Article/details/gt2yqmblbdk.html

JS:   JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gt2qlzoabvp.html

TS:   JSON.parse(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iuzwwjil.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.fzhhl.top/Article/details/gt2puczbizi.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xinyue.icu/Article/details/gt2kievwviz.html

Ruby: JSON.parse(s)
来源：http://dali.daxiang520.top/Article/details/gt2srqtdmnx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.iojbl.cn/Article/details/gt2mntfyavp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj20258.top/Article/details/gt2egtbeawt.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gotoacloud.top/Article/details/gt2hjarkefv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.snrcjt.cn/Article/details/gt2avobismw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2gzmmukjs.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yvedp.cn/Article/details/gt2ypxiouzt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yueranfly.top/Article/details/gt2qgqmyize.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.chenzaomai.com/Article/details/gt2dvfshvnz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.daria6918.cn/Article/details/gt2jwvxqtwo.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ybcxt.top/Article/details/gt2thfdbnlx.html

[K04] 读取 JSON 文件
来源：http://dali.cqqwz.cn/Article/details/gt2npgioldo.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yj20258888.top/Article/details/gt2xylkuccu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj20258.top/Article/details/gt2xylcfqzr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dqgltutq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xxgpxwzq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.kuanghao11.cn/Article/details/gt2uxgbdvxl.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.kuanghao11.cn/Article/details/gt2iouqnqwb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hysaishi.cn/Article/details/gt2jxvdvhwr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.c1oappe.top/Article/details/gt2atwxfxlc.html

[K05] 深拷贝对象
来源：http://dali.svipenyu.cn/Article/details/gt2oyofdico.html

Py:   copy.deepcopy(obj)
来源：http://dali.shuidangran.top/Article/details/gt2iupvzchl.html

PHP:  unserialize(serialize($obj));
来源：http://dali.wangshuangyany.cn/Article/details/gt2nkargboh.html

JS:   structuredClone(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2zxzjsvhl.html

TS:   structuredClone(obj)
来源：http://dali.cheryme.top/Article/details/gt2buqporjd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yj202588.top/Article/details/gt2xuepqehp.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shangyingyoupin.top/Article/details/gt2ehuifpqa.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.birdmap.top/Article/details/gt2snpioain.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.birdmap.top/Article/details/gt2ynkeyvfo.html

[K06] 解析 URL 查询串
来源：http://dali.cashguo.top/Article/details/gt2xginfgzh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tian-w.cn/Article/details/gt2twvwxgep.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinqigfzy.top/Article/details/gt2hddjoith.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.haohaochexian.top/Article/details/gt2ilofmtrc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zdqjudy.top/Article/details/gt2hweksesy.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinqigufen.top/Article/details/gt2khquizmc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xinyue.icu/Article/details/gt2wkndiymn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.0kj1m.cn/Article/details/gt2ybfnkiwz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gt2cwmxrxoy.html

[K07] 进制转换
来源：http://dali.tianlin.xyz/Article/details/gt2rbvfkydk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gt2htjvsxaz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nwbrower.top/Article/details/gt2jzmgxxwp.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gt2wijhxgvu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gt2tpxmenzv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hagracyi.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cheryme.top/Article/details/gt2renhtpdu.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhongyouzk.top/Article/details/gt2qphdabup.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.havefunace.top/Article/details/gt2nzqdkwsc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhiwuduotai.top/Article/details/gt2tdhzuana.html

Py:   pickle.dumps(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2srtttvrx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ppjwa.cn/Article/details/gt2lginzear.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ivvv.top/Article/details/gt2mrnnpeim.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.pengpengdd.cyou/Article/details/gt2oxqnewle.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhixingplan.top/Article/details/gt2euhcdpau.html

Go:   encoding/gob
来源：http://dali.svipenyu.cn/Article/details/gt2fkedfhxj.html

Ruby: Marshal.dump(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2chrudlzk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.meibo888.top/Article/details/gt2nxcrbzxi.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2xfgtetnh.html

L. 网络请求
来源：http://dali.iojbl.cn/Article/details/gt2rqoluryu.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2hivxcnuu.html

[L01] 发送 GET 请求
来源：http://dali.shangyingyoupin.top/Article/details/gt2lwmzxqsm.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xuetiantiany.cn/Article/details/gt2aiarylcv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.0kj1m.cn/Article/details/gt2kujqqjbs.html

JS:   await fetch(url)
来源：http://dali.jqgufenzy.top/Article/details/gt2ifxocspe.html

TS:   await fetch(url)
来源：http://dali.c1oappe.top/Article/details/gt2olxtyztf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jlsjyb.cn/Article/details/gt2lystwyuj.html

Go:   resp, err := http.Get(url)
来源：http://dali.xuanzx.com/Article/details/gt2fmfwqhbf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.dianchejie.cn/Article/details/gt2jknwwlqm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xziqi.cn/Article/details/gt2cmtjyxhb.html

[L02] 发送 POST JSON
来源：http://dali.yongpay.top/Article/details/gt2htsvesxi.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ehwqpu.com/Article/details/gt2mbcvphue.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.nanxinkj.top/Article/details/gt2mktbttyu.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gogol.net.cn/Article/details/gt2dmjklbvv.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.svipenyu.cn/Article/details/gt2hlwnzjxt.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shuidangran.top/Article/details/gt2evvzdgza.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zdqjudy.top/Article/details/gt2pvxiycbw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zycfv.cn/Article/details/gt2hgnmcyoc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hammf.cn/Article/details/gt2pechdlfg.html

[L03] 设置自定义请求头
来源：http://dali.xinyue.icu/Article/details/gt2slbvhgpa.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.dianchejie.cn/Article/details/gt2vkgoihex.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.pengpengdd.cyou/Article/details/gt2mhyiigop.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gotoacloud.top/Article/details/gt2nkalhtjz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnqzz.top/Article/details/gt2bhjustco.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cqqwz.cn/Article/details/gt2mgenrvue.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2nospokcl.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hnqzz.top/Article/details/gt2rhubmaxj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xziqi.cn/Article/details/gt2alqkglqu.html

[L04] 设置超时
来源：http://dali.snrcjt.cn/Article/details/gt2frbrzggd.html

Py:   requests.get(url, timeout=5)
来源：http://dali.guowangkeji.top/Article/details/gt2uxwxyvbw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xziqi.cn/Article/details/gt2yurcfqrg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gogol.net.cn/Article/details/gt2wyvpoiwl.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.iojbl.cn/Article/details/gt2cuthpkff.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.mhx1999.top/Article/details/gt2qismruyg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.snrcjt.cn/Article/details/gt2xhrdghwq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.tanke756.top/Article/details/gt2uxdakjwc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhoulong.xyz/Article/details/gt2zakjjvod.html

[L05] 上传文件（multipart）
来源：http://dali.shangyingyoupin.top/Article/details/gt2dwvwvkkl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cqqwz.cn/Article/details/gt2szkkjixf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sxryk.cn/Article/details/gt2oyzzqckz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuetiantiany.cn/Article/details/gt2ssttfszq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.feifeiyinyue.top/Article/details/gt2kxsinixr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sweek.top/Article/details/gt2ujisavog.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gogol.net.cn/Article/details/gt2rgfflesr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.smart0.xyz/Article/details/gt2ciynofib.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2wdnhipea.html

[L06] 解析响应为 JSON
来源：http://dali.cashguo.top/Article/details/gt2ejqcqfnq.html

Py:   resp.json()
来源：http://dali.chenzaomai.com/Article/details/gt2eoreyloe.html

PHP:  json_decode($body, true);
来源：http://dali.zhixingplan.top/Article/details/gt2mknoniwv.html

JS:   await resp.json()
来源：http://dali.c1oappe.top/Article/details/gt2hukcjzrv.html

TS:   await resp.json()
来源：http://dali.yvedp.cn/Article/details/gt2hspmdygg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cheryme.top/Article/details/gt2ftvsexoz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shuidangran.top/Article/details/gt2swkwxcni.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gogol.net.cn/Article/details/gt2bdwoilsk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2obdqpyky.html

[L07] 处理 HTTP 状态码
来源：http://dali.snrcjt.cn/Article/details/gt2amwyrvpq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.havefunace.top/Article/details/gt2xjedlgrb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ivvv.top/Article/details/gt2stskskqg.html

JS:   resp.ok;  resp.status
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jwwvltrj.html

TS:   resp.ok;  resp.status
来源：http://dali.jiagoushi.top/Article/details/gt2gtrsusfs.html

Java: resp.statusCode()
来源：http://dali.ivvv.top/Article/details/gt2sdovpkqf.html

Go:   resp.StatusCode
来源：http://dali.zdqjudy.top/Article/details/gt2vptcxyfq.html

Ruby: resp.code.to_i
来源：http://dali.yongpay.top/Article/details/gt2qwangcok.html

C#:   (int)resp.StatusCode
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mazvzyok.html

[L08] 并发请求多个地址
来源：http://dali.cqqwz.cn/Article/details/gt2isqhjpbi.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.316326.xyz/Article/details/gt2yjcttlcb.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinqigufen.top/Article/details/gt2zbejkurn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jianghu66.top/Article/details/gt2wbmpxdwb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jlsjyb.cn/Article/details/gt2tqyfnuaq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.chenlongwang.top/Article/details/gt2ffkyrlck.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yanxiufei.cn/Article/details/gt2itqlievs.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cucudq.cn/Article/details/gt2xvhygwch.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gt2gauzwndw.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2wuvqbzrw.html

M. 命令行 / 进程 / 环境
来源：http://dali.nanxinkj.top/Article/details/gt2mttyyzaj.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2drpwcasv.html

[M01] 读取命令行参数
来源：http://dali.tian-w.cn/Article/details/gt2qefzffml.html

Py:   sys.argv[1:]
来源：http://dali.nanxinkj.top/Article/details/gt2rgvxroym.html

PHP:  $argv;  $argc;
来源：http://dali.aizwys.cn/Article/details/gt2zfjhjlqw.html

JS:   process.argv.slice(2)
来源：http://dali.xziqi.cn/Article/details/gt2tzgvqnro.html

TS:   process.argv.slice(2)
来源：http://dali.aizwys.cn/Article/details/gt2rmjgrjam.html

Java: args 数组（main 方法参数）
来源：http://dali.zhoulong.xyz/Article/details/gt2wplupmqs.html

Go:   os.Args[1:]
来源：http://dali.nanxuanxn.top/Article/details/gt2ucvxrkhe.html

Ruby: ARGV
来源：http://dali.quarkkingdee.top/Article/details/gt2gnkzwbjc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.guannengcc.top/Article/details/gt2fieosmia.html

[M02] 读取环境变量
来源：http://dali.jinqigufen.top/Article/details/gt2jktripcr.html

Py:   os.environ.get("HOME")
来源：http://dali.zycfv.cn/Article/details/gt2cgfcnxpn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cashguo.top/Article/details/gt2zkkhiysw.html

JS:   process.env.HOME
来源：http://dali.ivvv.top/Article/details/gt2cmtoxvod.html

TS:   process.env.HOME
来源：http://dali.xylfe.cn/Article/details/gt2msmdehqq.html

Java: System.getenv("HOME")
来源：http://dali.wangdashe.top/Article/details/gt2zlvdivdh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhengqikj.top/Article/details/gt2vqbewfdq.html

Ruby: ENV["HOME"]
来源：http://dali.gzhubu.top/Article/details/gt2qavhscrx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.svipenyu.cn/Article/details/gt2mofgivef.html

[M03] 执行外部命令
来源：http://dali.chenlongwang.top/Article/details/gt2obawqytc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhiwuduotai.top/Article/details/gt2znnjxokq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ppjwa.cn/Article/details/gt2kvswtaaq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xylfe.cn/Article/details/gt2fsfdentr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2psyycqam.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.tian-w.cn/Article/details/gt2qexazyss.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gsxcbpbx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tianlin.xyz/Article/details/gt2gbpmucmn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jiagoushi.top/Article/details/gt2owawvvpu.html

[M04] 获取当前工作目录
来源：http://dali.yvedp.cn/Article/details/gt2wawbmtiv.html

Py:   os.getcwd()
来源：http://dali.jqgufenzy.top/Article/details/gt2jrhjhnbl.html

PHP:  getcwd();
来源：http://dali.yj202588.top/Article/details/gt2xxjawamw.html

JS:   process.cwd()
来源：http://dali.jinqigufen.top/Article/details/gt2fpqxgfsf.html

TS:   process.cwd()
来源：http://dali.yonumen.top/Article/details/gt2lmraovpv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jianghu66.top/Article/details/gt2xbzkmozj.html

Go:   os.Getwd()
来源：http://dali.c1oappe.top/Article/details/gt2qcueeimd.html

Ruby: Dir.pwd
来源：http://dali.chenzaomai.com/Article/details/gt2ryulumlk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrjrsoq.html

[M05] 设置退出码
来源：http://dali.vqdsnc.cn/Article/details/gt2epejothj.html

Py:   sys.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ruajtqsw.html

PHP:  exit(1);
来源：http://dali.xziqi.cn/Article/details/gt2almhdono.html

JS:   process.exit(1)
来源：http://dali.daria6918.cn/Article/details/gt2nsphbnul.html

TS:   process.exit(1)
来源：http://dali.hnqzz.top/Article/details/gt2qbmfdqme.html

Java: System.exit(1)
来源：http://dali.jianghu66.top/Article/details/gt2tguynitk.html

Go:   os.Exit(1)
来源：http://dali.zhixingplan.top/Article/details/gt2uuudbeop.html

Ruby: exit 1
来源：http://dali.yueranfly.top/Article/details/gt2flolbpip.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.dianchejie.cn/Article/details/gt2iioletjh.html

[M06] 向标准错误输出
来源：http://dali.aibaodan.cn/Article/details/gt2sbkuxlux.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhongyouzk.top/Article/details/gt2foikfyyw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nwbrower.top/Article/details/gt2lnlnmjsx.html

JS:   console.error("err")
来源：http://dali.shuidangran.top/Article/details/gt2jihoesfi.html

TS:   console.error("err")
来源：http://dali.iojbl.cn/Article/details/gt2xqcamgxf.html

Java: System.err.println("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yinkxzzd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.wangdashe.top/Article/details/gt2tzdnfkhk.html

Ruby: warn "err"
来源：http://dali.shuidangran.top/Article/details/gt2kpuslhgh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.0kj1m.cn/Article/details/gt2ysltxwcd.html

[M07] 判断是否为主入口
来源：http://dali.316326.xyz/Article/details/gt2jlllexoi.html

Py:   if __name__ == "__main__":
来源：http://dali.cheryme.top/Article/details/gt2cedeonhr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xslwxcgm.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzsxxpd.html

TS:   require.main === module
来源：http://dali.zhoulong.xyz/Article/details/gt2qktpxppw.html

Java: public static void main(String[] args)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bztxjkdb.html

Go:   func main()
来源：http://dali.316326.xyz/Article/details/gt2shiojmiy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.fzhhl.top/Article/details/gt2kjsbqzwn.html

C#:   static void Main(string[] args)
来源：http://dali.hysaishi.cn/Article/details/gt2hemdfunu.html

[M08] 获取系统与运行时信息
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2epxlwuha.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jwssmtkd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhongyouzk.top/Article/details/gt2qslsiaar.html

JS:   process.platform;  process.version
来源：http://dali.bjfxy.top/Article/details/gt2kdysvqxq.html

TS:   process.platform;  process.version
来源：http://dali.yanxiufei.cn/Article/details/gt2sgdamtfi.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xylfe.cn/Article/details/gt2hkonofsd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhengqikj.top/Article/details/gt2cnsubrjp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jlsjyb.cn/Article/details/gt2droeznlv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shangyingyoupin.top/Article/details/gt2uzmkjbse.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2ebfsiqto.html

N. 数据结构与算法
来源：http://dali.gaohongyu789.top/Article/details/gt2vabwdxkh.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2nfleoiwc.html

[N01] 二分查找（有序数组）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ptgvuzre.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2usixqidj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhixingplan.top/Article/details/gt2mjvxepbf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cashguo.top/Article/details/gt2ozdxddwm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.birdmap.top/Article/details/gt2uiiyyfqt.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gt2mvwzwgnb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gt2aotsinwj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cqqwz.cn/Article/details/gt2drzjaxfk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gt2peftfgbv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jiagoushi.top/Article/details/gt2ploodeld.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aubgnutd.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yangfankeji.com/Article/details/gt2ooaqhkzu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.c1oappe.top/Article/details/gt2cpxqfpsd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zycfv.cn/Article/details/gt2njqjkvdv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.pycfn.com/Article/details/gt2yhukkrso.html

Go:   slices.Sort(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2oymfvuzb.html

Ruby: arr.sort
来源：http://dali.iojbl.cn/Article/details/gt2epkmkuwr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ybcxt.top/Article/details/gt2dwqzdiho.html

[N03] 快速排序（分治示例）
来源：http://dali.chenlongwang.top/Article/details/gt2xbwrlszf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj20258888.top/Article/details/gt2lnebmdaz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.quarkkingdee.top/Article/details/gt2ujxtfbbk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pycfn.com/Article/details/gt2pvhajagb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xziqi.cn/Article/details/gt2sppvgjov.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ivvv.top/Article/details/gt2gccoynsu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yueranfly.top/Article/details/gt2ovlazmaj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dfyvdthe.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yuanzhike.top/Article/details/gt2ccggyafb.html

[N04] 斐波那契数列
来源：http://dali.jiagoushi.top/Article/details/gt2oaezafoc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sweek.top/Article/details/gt2jweldpwa.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lqxzctkb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sxryk.cn/Article/details/gt2pbavruny.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gt2vvjwozjw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.svipenyu.cn/Article/details/gt2mursbivb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yonnolwp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qbculemi.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gt2uvjgwtmz.html

[N05] 最大公约数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2raphswjr.html

Py:   math.gcd(a, b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hufdntns.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.mhx1999.top/Article/details/gt2utftpoiq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.havefunace.top/Article/details/gt2rmnatfxw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhongyouzk.top/Article/details/gt2ochcxkkg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ivvv.top/Article/details/gt2phochrlp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.birdmap.top/Article/details/gt2fjhtjogn.html

Ruby: a.gcd(b)
来源：http://dali.hywenlv.cn/Article/details/gt2qwlejqrc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.tian-w.cn/Article/details/gt2scpleynn.html

[N06] 判断回文字符串
来源：http://dali.redwolf501.top/Article/details/gt2kxshrble.html

Py:   s == s[::-1]
来源：http://dali.dianchejie.cn/Article/details/gt2qpswyruy.html

PHP:  $s === strrev($s);
来源：http://dali.xziqi.cn/Article/details/gt2orawvlyj.html

JS:   s === [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gt2evngfesr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xuetiantiany.cn/Article/details/gt2xxikymmo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ybcxt.top/Article/details/gt2wqfpaxha.html

Go:   // 双指针从两端比较
来源：http://dali.cucudq.cn/Article/details/gt2hkennndy.html

Ruby: s == s.reverse
来源：http://dali.hnxiangtu.top/Article/details/gt2kxtgtjmi.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shzxlz.cn/Article/details/gt2ifxxyzlc.html

[N07] 两数之和（返回下标）
来源：http://dali.hongshengwenyu.top/Article/details/gt2msgsvuvh.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.meibo888.top/Article/details/gt2yclyqerq.html


<!-- 参考信息 -->