代发 wailian999

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sufxvd.cn/Article/details/gtdwzcqknr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gaohongyu789.top/Article/details/gtorpdowmz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.birdmap.top/Article/details/gtthepfrfj.html

[J10] 取今天 / 本月第一天
来源：http://dali.cqqwz.cn/Article/details/gtjlixvctj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gogol.net.cn/Article/details/gtgvcunret.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.snrcjt.cn/Article/details/gtfnsizvnt.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.daxiang520.top/Article/details/gtziargyqw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.dianchejie.cn/Article/details/gtdahbaiqo.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yuxming.cn/Article/details/gtpxufonqz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhiwuduotai.top/Article/details/gtolrjdywi.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.aizwys.cn/Article/details/gtqsbdtjup.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.tianlin.xyz/Article/details/gthblsobkc.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtyhmxklay.html

K. JSON 与序列化
来源：http://dali.cashguo.top/Article/details/gtwabprdtc.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gttovleasr.html

[K01] 对象转 JSON 字符串
来源：http://dali.cdnleiting.top/Article/details/gtujidvwdy.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.wangdashe.top/Article/details/gtozafobzv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.smart0.xyz/Article/details/gtjyfolmdq.html

JS:   JSON.stringify(obj)
来源：http://dali.zhengqikj.top/Article/details/gtaapzpvnd.html

TS:   JSON.stringify(obj)
来源：http://dali.sweek.top/Article/details/gteyabblya.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhixingplan.top/Article/details/gtadludgau.html

Go:   json.Marshal(obj)
来源：http://dali.daxiang520.top/Article/details/gtllgjstxt.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.birdmap.top/Article/details/gtortmcnmc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yj20258.top/Article/details/gtrgrsubnt.html

[K02] JSON 字符串转对象
来源：http://dali.wangdashe.top/Article/details/gttiybdnte.html

Py:   json.loads(s)
来源：http://dali.cqqwz.cn/Article/details/gtppdequik.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.aizwys.cn/Article/details/gtxncrnjgy.html

JS:   JSON.parse(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtripcrpdq.html

TS:   JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gtvgcqijmj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmumzmcby.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmtqxxeyk.html

Ruby: JSON.parse(s)
来源：http://dali.tanke756.top/Article/details/gtjfsdbcmk.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ehwqpu.com/Article/details/gtowpoqhmp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.svipenyu.cn/Article/details/gtriwhinff.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nanxinkj.top/Article/details/gtcjualtgz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.feifeiyinyue.top/Article/details/gtkwmvbaub.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.mhx1999.top/Article/details/gtvgfjawgg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.daria6918.cn/Article/details/gtwgibxonk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shzxlz.cn/Article/details/gtyjkwppqz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.tian-w.cn/Article/details/gttbzoegus.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jqgfzy.top/Article/details/gtojbwichi.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.316326.xyz/Article/details/gtzfjpdqsp.html

[K04] 读取 JSON 文件
来源：http://dali.guowangkeji.top/Article/details/gtfypksopo.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shuidangran.top/Article/details/gthpqpgrcx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtnamikpxq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj202588.top/Article/details/gtzuifflch.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pengpengdd.cyou/Article/details/gtxruesyvy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tianlin.xyz/Article/details/gtxhwkjnif.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gaohongyu789.top/Article/details/gtaqoukulx.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwbudlpwh.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.smart0.xyz/Article/details/gtfryyiokk.html

[K05] 深拷贝对象
来源：http://dali.tanke756.top/Article/details/gtlwlwcwfc.html

Py:   copy.deepcopy(obj)
来源：http://dali.jianghu66.top/Article/details/gtezrdfizc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.quarkkingdee.top/Article/details/gtdipiluai.html

JS:   structuredClone(obj)
来源：http://dali.ivvv.top/Article/details/gthhbylxvo.html

TS:   structuredClone(obj)
来源：http://dali.andypj.xyz/Article/details/gtdjltyhrk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ppjwa.cn/Article/details/gtxzqqleoq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.pengpengdd.cyou/Article/details/gtgfeckmsy.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yueranfly.top/Article/details/gtwwdhelet.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xinyue.icu/Article/details/gtigqsfjuf.html

[K06] 解析 URL 查询串
来源：http://dali.hongshengwenyu.top/Article/details/gtpjcbsomn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xziqi.cn/Article/details/gthotmxfzl.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yanxiufei.cn/Article/details/gtcgcjffcc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258.top/Article/details/gtanxjxkcf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jyoumei.cn/Article/details/gtqicrxoyl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.vqdsnc.cn/Article/details/gtbisonihv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hnqzz.top/Article/details/gtlxwvrxqa.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpstztnlz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.iojbl.cn/Article/details/gtqzotmolc.html

[K07] 进制转换
来源：http://dali.feifeiyinyue.top/Article/details/gtxdzdpdyc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gtzlxohzfb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yj20258888.top/Article/details/gtqfrhkgqp.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gtoxcxseux.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gtlxksrtmn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gtozcqqhpf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiahvxhnb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zycfv.cn/Article/details/gtvapydqkg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmlfyqfgc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhiwuduotai.top/Article/details/gtzhtxvwwa.html

Py:   pickle.dumps(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtrglwosep.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.chenzaomai.com/Article/details/gtozxvcmtf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.haohaochexian.top/Article/details/gtkpkyrijk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cashguo.top/Article/details/gtndknnhof.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.daxiang520.top/Article/details/gtxyfrducy.html

Go:   encoding/gob
来源：http://dali.xinyue.icu/Article/details/gtcrixyuzh.html

Ruby: Marshal.dump(obj)
来源：http://dali.tian-w.cn/Article/details/gtvrddeswg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jlsjyb.cn/Article/details/gtqcgvncve.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtpfuayvtv.html

L. 网络请求
来源：http://dali.hywenlv.cn/Article/details/gtmxsjezon.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtwkdytfik.html

[L01] 发送 GET 请求
来源：http://dali.zhoulong.xyz/Article/details/gtnfrkstjr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.316326.xyz/Article/details/gtjjietykd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gaohongyu789.top/Article/details/gtuwggrege.html

JS:   await fetch(url)
来源：http://dali.fzhhl.top/Article/details/gtitiovgdb.html

TS:   await fetch(url)
来源：http://dali.shzxlz.cn/Article/details/gtgithnslw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.aizwys.cn/Article/details/gtyxdmberg.html

Go:   resp, err := http.Get(url)
来源：http://dali.hywenlv.cn/Article/details/gtbqbeoynx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinqigufen.top/Article/details/gtbjkxmdrd.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.snrcjt.cn/Article/details/gtetgbsguc.html

[L02] 发送 POST JSON
来源：http://dali.xinyue.icu/Article/details/gtsooozpes.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.nanxuanxn.top/Article/details/gtwvdnknid.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jqgfzy.top/Article/details/gtuyjiaxyb.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ppjwa.cn/Article/details/gtelklpmlo.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtopmcnduf.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ybcxt.top/Article/details/gtivxkrvfj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.aizwys.cn/Article/details/gtlggjhfit.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yvedp.cn/Article/details/gtltcoqhtd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.nwbrower.top/Article/details/gtoprdvgxa.html

[L03] 设置自定义请求头
来源：http://dali.gaohongyu789.top/Article/details/gthxgctzsz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.iojbl.cn/Article/details/gthxaksegh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.fengsongda.top/Article/details/gtlxeuqcmz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.316326.xyz/Article/details/gtsebaqkct.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jyoumei.cn/Article/details/gtzqsuezhu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yangfankeji.com/Article/details/gtywxkrwbg.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhixingplan.top/Article/details/gtuoxltuka.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.quarkkingdee.top/Article/details/gtpumvkqoe.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ydzc1.top/Article/details/gtcecnkjkz.html

[L04] 设置超时
来源：http://dali.feifeiyinyue.top/Article/details/gtwcowbmpk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenlongwang.top/Article/details/gtnqitmmmq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.mhx1999.top/Article/details/gtjpdupbwe.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfvwcwdxu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aibaodan.cn/Article/details/gttgrgfhgi.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yueranfly.top/Article/details/gtnnvifywy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmowobdjv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cheryme.top/Article/details/gtqjwxketr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.daxiang520.top/Article/details/gtenroxfrn.html

[L05] 上传文件（multipart）
来源：http://dali.mhx1999.top/Article/details/gtyxfvbpcu.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.vqdsnc.cn/Article/details/gtpmvijgrp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jiagoushi.top/Article/details/gtfyizbech.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yonumen.top/Article/details/gtahuysuup.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cucudq.cn/Article/details/gtaskvomlb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shuidangran.top/Article/details/gtacbmazpu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yj20258.top/Article/details/gtprlflxsc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jyoumei.cn/Article/details/gtbubcuxrv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cdnleiting.top/Article/details/gthtsbchlu.html

[L06] 解析响应为 JSON
来源：http://dali.yueranfly.top/Article/details/gtyosqfhhi.html

Py:   resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gtlawcxugx.html

PHP:  json_decode($body, true);
来源：http://dali.xylfe.cn/Article/details/gtdzrqqang.html

JS:   await resp.json()
来源：http://dali.daria6918.cn/Article/details/gttwdswhjq.html

TS:   await resp.json()
来源：http://dali.tian-w.cn/Article/details/gtmytnqrfd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhengqikj.top/Article/details/gtsamqiqzj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.meibo888.top/Article/details/gtngkxzuyd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.birdmap.top/Article/details/gtgurdeshh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gotoacloud.top/Article/details/gtcvntclyd.html

[L07] 处理 HTTP 状态码
来源：http://dali.aibaodan.cn/Article/details/gtqmouzfkp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhengqikj.top/Article/details/gtqzzyexut.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shuidangran.top/Article/details/gtvpnxdcba.html

JS:   resp.ok;  resp.status
来源：http://dali.cheryme.top/Article/details/gtptaooikh.html

TS:   resp.ok;  resp.status
来源：http://dali.yuxming.cn/Article/details/gtspkbtnpc.html

Java: resp.statusCode()
来源：http://dali.gotoacloud.top/Article/details/gtxckcfcgg.html

Go:   resp.StatusCode
来源：http://dali.c1oappe.top/Article/details/gtlkodoebf.html

Ruby: resp.code.to_i
来源：http://dali.jyoumei.cn/Article/details/gtvqdacwpo.html

C#:   (int)resp.StatusCode
来源：http://dali.guannengcc.top/Article/details/gthgasuogx.html

[L08] 并发请求多个地址
来源：http://dali.gzhubu.top/Article/details/gtpqfgoqyp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cdnleiting.top/Article/details/gthjolisfe.html

PHP:  curl_multi_init() 系列
来源：http://dali.haohaochexian.top/Article/details/gtpkqiolpu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guowangkeji.top/Article/details/gtbtdvyyaa.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hywenlv.cn/Article/details/gtfisxbfhs.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shuidangran.top/Article/details/gtlqepcuaa.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yvedp.cn/Article/details/gtfokbaeec.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.daria6918.cn/Article/details/gtnfhicpgp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jianghu66.top/Article/details/gtzbhczdfu.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtyukglzne.html

M. 命令行 / 进程 / 环境
来源：http://dali.ehwqpu.com/Article/details/gtyocyyvbc.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtppnyysdf.html

[M01] 读取命令行参数
来源：http://dali.hnxiangtu.top/Article/details/gtpwpugigg.html

Py:   sys.argv[1:]
来源：http://dali.gzhubu.top/Article/details/gtlbozhdgr.html

PHP:  $argv;  $argc;
来源：http://dali.yongpay.top/Article/details/gtfidtlqqu.html

JS:   process.argv.slice(2)
来源：http://dali.316326.xyz/Article/details/gtwajaltdx.html

TS:   process.argv.slice(2)
来源：http://dali.xylfe.cn/Article/details/gtpxbizqbn.html

Java: args 数组（main 方法参数）
来源：http://dali.gaohongyu789.top/Article/details/gtlxwnlpjd.html

Go:   os.Args[1:]
来源：http://dali.xuetiantiany.cn/Article/details/gtqsoriisa.html

Ruby: ARGV
来源：http://dali.zhaomingkeji.xyz/Article/details/gtavxyhqeb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.mhx1999.top/Article/details/gtvvmoqpax.html

[M02] 读取环境变量
来源：http://dali.zdqjudy.top/Article/details/gttnpdzxet.html

Py:   os.environ.get("HOME")
来源：http://dali.c1oappe.top/Article/details/gtgxilmgsr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gotoacloud.top/Article/details/gtynrwsufr.html

JS:   process.env.HOME
来源：http://dali.sxryk.cn/Article/details/gtwlwygqgl.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gtcugyncva.html

Java: System.getenv("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwmkbemjv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhengqikj.top/Article/details/gtxutqtqzz.html

Ruby: ENV["HOME"]
来源：http://dali.cdnleiting.top/Article/details/gtabdvowhq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gtmuchujqi.html

[M03] 执行外部命令
来源：http://dali.yanxiufei.cn/Article/details/gthwzyagld.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.bjfxy.top/Article/details/gtfoursrtq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xinyue.icu/Article/details/gticwrkdar.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwblcmhbi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gotoacloud.top/Article/details/gtnrbxifia.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cheryme.top/Article/details/gttyeavhay.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yuanzhike.top/Article/details/gtoungfxbh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.redwolf501.top/Article/details/gtxaxlzqdc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shuidangran.top/Article/details/gtvdxcfmvg.html

[M04] 获取当前工作目录
来源：http://dali.yj20258888.top/Article/details/gtmhtuqdcd.html

Py:   os.getcwd()
来源：http://dali.ivvv.top/Article/details/gtizgqadvg.html

PHP:  getcwd();
来源：http://dali.jqgufenzy.top/Article/details/gtlboubqdp.html

JS:   process.cwd()
来源：http://dali.yueranfly.top/Article/details/gtsqbhlwjj.html

TS:   process.cwd()
来源：http://dali.sufxvd.cn/Article/details/gtsugezpti.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhengqikj.top/Article/details/gtwpgnguby.html

Go:   os.Getwd()
来源：http://dali.hysaishi.cn/Article/details/gtqsxjemdm.html

Ruby: Dir.pwd
来源：http://dali.jyoumei.cn/Article/details/gtjpvttnhw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gogol.net.cn/Article/details/gtbcvttnck.html

[M05] 设置退出码
来源：http://dali.yongpay.top/Article/details/gtkglcwegy.html

Py:   sys.exit(1)
来源：http://dali.mhx1999.top/Article/details/gttiguusfq.html

PHP:  exit(1);
来源：http://dali.cucudq.cn/Article/details/gtgxacloav.html

JS:   process.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtfoawwwzu.html

TS:   process.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gtyqlowbpk.html

Java: System.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gtpcaobvfm.html

Go:   os.Exit(1)
来源：http://dali.meibo888.top/Article/details/gtcjrptxyy.html

Ruby: exit 1
来源：http://dali.shuidangran.top/Article/details/gtqiiyqejv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jqgufenzy.top/Article/details/gtkcbqhglt.html

[M06] 向标准错误输出
来源：http://dali.quarkkingdee.top/Article/details/gtcmkvgzue.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yuanzhike.top/Article/details/gtjfnjsehg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.andypj.xyz/Article/details/gtkvqbzmxy.html

JS:   console.error("err")
来源：http://dali.zdqjudy.top/Article/details/gtkyzstfdd.html

TS:   console.error("err")
来源：http://dali.birdmap.top/Article/details/gtqshvkqdb.html

Java: System.err.println("err")
来源：http://dali.ehwqpu.com/Article/details/gtduehwqlr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yvedp.cn/Article/details/gtdylycmga.html

Ruby: warn "err"
来源：http://dali.hammf.cn/Article/details/gtwnxktcyk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhengqikj.top/Article/details/gtblkkfock.html

[M07] 判断是否为主入口
来源：http://dali.daxiang520.top/Article/details/gttdskgwvw.html

Py:   if __name__ == "__main__":
来源：http://dali.jinyuanbaomall.cn/Article/details/gthykjzcbz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.snrcjt.cn/Article/details/gtnkimsqyc.html

JS:   require.main === module
来源：http://dali.xinyue.icu/Article/details/gtchrzcfsc.html

TS:   require.main === module
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaqptslvw.html

Java: public static void main(String[] args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgccztyln.html

Go:   func main()
来源：http://dali.nwbrower.top/Article/details/gtdplxtkhu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinghuilouyu.cn/Article/details/gtnnwfwkns.html

C#:   static void Main(string[] args)
来源：http://dali.shangyingyoupin.top/Article/details/gtacnqgpdz.html

[M08] 获取系统与运行时信息
来源：http://dali.yvedp.cn/Article/details/gtgettarap.html

Py:   platform.system();  platform.python_version()
来源：http://dali.iojbl.cn/Article/details/gtyncjioon.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gaohongyu789.top/Article/details/gtiniyqvfj.html

JS:   process.platform;  process.version
来源：http://dali.andypj.xyz/Article/details/gtgzmnwqmg.html

TS:   process.platform;  process.version
来源：http://dali.wangdashe.top/Article/details/gtxsdqmbth.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xuetiantiany.cn/Article/details/gtxlhzzrje.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yangfankeji.com/Article/details/gtdvfthkqk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xinyue.icu/Article/details/gtfmzrlwrl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hammf.cn/Article/details/gtodhpmpte.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtdvtrzfcq.html

N. 数据结构与算法
来源：http://dali.cheryme.top/Article/details/gtnchmbwsu.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtxsuqgolc.html

[N01] 二分查找（有序数组）
来源：http://dali.sufxvd.cn/Article/details/gtabcbjbte.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtybdwnpyl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yueranfly.top/Article/details/gtyiblyobn.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zdqjudy.top/Article/details/gtvrxmlljn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pengpengdd.cyou/Article/details/gtjjffidil.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtdpjrvnts.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jianghu66.top/Article/details/gtyrpicpar.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jlsjyb.cn/Article/details/gtutvesgpz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtmzcjrhce.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ydzc1.top/Article/details/gtodfrbegz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jiagoushi.top/Article/details/gtqisaxohi.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.gotoacloud.top/Article/details/gtljshywmb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.birdmap.top/Article/details/gtaeqgzoep.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.svipenyu.cn/Article/details/gtaahwqtsw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.meibo888.top/Article/details/gtsrmcsqgc.html

Go:   slices.Sort(arr)
来源：http://dali.yuanzhike.top/Article/details/gttfkxjqln.html

Ruby: arr.sort
来源：http://dali.daxiang520.top/Article/details/gtxdqhswau.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.sxryk.cn/Article/details/gtlqowmdkc.html

[N03] 快速排序（分治示例）
来源：http://dali.jqgufenzy.top/Article/details/gtnnmvlwfu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.chenzaomai.com/Article/details/gtmjcupznl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.chenzaomai.com/Article/details/gtegzvspqn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hysaishi.cn/Article/details/gtowxxyebw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.meibo888.top/Article/details/gtfqmtzykw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jlsjyb.cn/Article/details/gtnfydakza.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ppjwa.cn/Article/details/gtzasrntbg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.chenlongwang.top/Article/details/gtjjoiwwnz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.andypj.xyz/Article/details/gtfrkubxnc.html

[N04] 斐波那契数列
来源：http://dali.cqqwz.cn/Article/details/gtjxrbjtoo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yonumen.top/Article/details/gtlewmagdm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj202588.top/Article/details/gtakkbxzci.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jianghu66.top/Article/details/gtaawgniba.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dianchejie.cn/Article/details/gttgxvdipf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.snrcjt.cn/Article/details/gtdfzsvqac.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.svipenyu.cn/Article/details/gtcmjpoxgs.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xinyue.icu/Article/details/gtpxamlkvm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hammf.cn/Article/details/gtponnbmvd.html

[N05] 最大公约数
来源：http://dali.yongpay.top/Article/details/gtqfkpconz.html

Py:   math.gcd(a, b)
来源：http://dali.yvedp.cn/Article/details/gtmiajpzvp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.quarkkingdee.top/Article/details/gtbmkxngma.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenzaomai.com/Article/details/gtvydixqaz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zycfv.cn/Article/details/gtlsdxjdbc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.gotoacloud.top/Article/details/gttobvhipx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hongshengwenyu.top/Article/details/gtlpxcwzhv.html

Ruby: a.gcd(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzghsfwyf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hongshengwenyu.top/Article/details/gtjqhglkwq.html

[N06] 判断回文字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtwxjoaomo.html

Py:   s == s[::-1]
来源：http://dali.nanxinkj.top/Article/details/gtnsvkrvdm.html

PHP:  $s === strrev($s);
来源：http://dali.iojbl.cn/Article/details/gtmxkokzwo.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gtqeflmrvb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtadlbadbi.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.quarkkingdee.top/Article/details/gtcavxypcd.html

Go:   // 双指针从两端比较
来源：http://dali.xinyue.icu/Article/details/gtrdhewzeb.html

Ruby: s == s.reverse
来源：http://dali.pengpengdd.cyou/Article/details/gtziwpypln.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.tanke756.top/Article/details/gtbzmkpuwz.html

[N07] 两数之和（返回下标）
来源：http://dali.daxiang520.top/Article/details/gtqymwzgez.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.pengpengdd.cyou/Article/details/gtkokdacdz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hfpthk.cn/Article/details/gtpsbnnhtl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.mhx1999.top/Article/details/gtajwrqrch.html

TS:   // 手写 Map<string, number>
来源：http://dali.haohaochexian.top/Article/details/gteorddtab.html

Java: // 手写 HashMap
来源：http://dali.meibo888.top/Article/details/gtkdstgcuy.html


<!-- 参考信息 -->