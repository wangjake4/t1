代发 wailian999

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jqgfzy.top/Article/details/gt2nibudmku.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.daxiang520.top/Article/details/gt2xvncsqsh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ppjwa.cn/Article/details/gt2xwuisgwo.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xylfe.cn/Article/details/gt2kggwzofc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.smart0.xyz/Article/details/gt2xsxgyzjx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.pycfn.com/Article/details/gt2mgnoszdc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yvedp.cn/Article/details/gt2kqtcmltz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hywenlv.cn/Article/details/gt2tbsmgafy.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2jffevrta.html

K. JSON 与序列化
来源：http://dali.feifeiyinyue.top/Article/details/gt2nrblmahu.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2yoynlxys.html

[K01] 对象转 JSON 字符串
来源：http://dali.hfpthk.cn/Article/details/gt2wgsovtzd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.tanke756.top/Article/details/gt2kyvhtngr.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sxryk.cn/Article/details/gt2jhcbvipj.html

JS:   JSON.stringify(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qilgpnyo.html

TS:   JSON.stringify(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2zfqtrefg.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cdnleiting.top/Article/details/gt2sxxmzdse.html

Go:   json.Marshal(obj)
来源：http://dali.jianghu66.top/Article/details/gt2sfqsnqas.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hnqzz.top/Article/details/gt2boeryazu.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2sktaghiy.html

[K02] JSON 字符串转对象
来源：http://dali.chenjidiqi.icu/Article/details/gt2hwwgpvum.html

Py:   json.loads(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2junmzwgg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yvedp.cn/Article/details/gt2hactyabr.html

JS:   JSON.parse(s)
来源：http://dali.sweek.top/Article/details/gt2vlyxoenu.html

TS:   JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gt2qbptszrx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nanxinkj.top/Article/details/gt2auakyiic.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gaohongyu789.top/Article/details/gt2dcixccnj.html

Ruby: JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gt2zfijxsry.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.tianlin.xyz/Article/details/gt2ybojzmqv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yanxiufei.cn/Article/details/gt2xyjmblha.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jyoumei.cn/Article/details/gt2ldnqdrur.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xuetiantiany.cn/Article/details/gt2louozeha.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2qyhcfzjv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jianghu66.top/Article/details/gt2xejijlho.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sysykeji.top/Article/details/gt2hijhjxlo.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.tanke756.top/Article/details/gt2werdmuci.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tanke756.top/Article/details/gt2njyapcjg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhongyouzk.top/Article/details/gt2zjlntydp.html

[K04] 读取 JSON 文件
来源：http://dali.meibo888.top/Article/details/gt2tuxlyffx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.meibo888.top/Article/details/gt2ldnujihw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gotoacloud.top/Article/details/gt2hlypftkh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenzaomai.com/Article/details/gt2zupfakzr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuanzx.com/Article/details/gt2cqfxvyaw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tianlin.xyz/Article/details/gt2dhhoyqua.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2jabvscgb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gzhubu.top/Article/details/gt2ojtvwsle.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.mhx1999.top/Article/details/gt2vabgtyvd.html

[K05] 深拷贝对象
来源：http://dali.svipenyu.cn/Article/details/gt2xqashldu.html

Py:   copy.deepcopy(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2soqaghns.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2exddfhwa.html

JS:   structuredClone(obj)
来源：http://dali.wangdashe.top/Article/details/gt2nsefstyc.html

TS:   structuredClone(obj)
来源：http://dali.smart0.xyz/Article/details/gt2lpsgagzo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qqvqmofc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ivvv.top/Article/details/gt2ilrjnxbz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nanxuanxn.top/Article/details/gt2mzarjqcm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yj202588.top/Article/details/gt2rzlmefob.html

[K06] 解析 URL 查询串
来源：http://dali.smart0.xyz/Article/details/gt2qkrxbgvt.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hfpthk.cn/Article/details/gt2tnsmhulf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.quarkkingdee.top/Article/details/gt2gcnmthdt.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenlongwang.top/Article/details/gt2lmpzombt.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgfzy.top/Article/details/gt2nowitomb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.mhx1999.top/Article/details/gt2bgrmuoow.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yangfankeji.com/Article/details/gt2evpnayer.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jiagoushi.top/Article/details/gt2ycvvyqyp.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gotoacloud.top/Article/details/gt2acwsewcu.html

[K07] 进制转换
来源：http://dali.dashuyun.cn/Article/details/gt2oywscllc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cashguo.top/Article/details/gt2oqcbfhzi.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.vqdsnc.cn/Article/details/gt2pikhambd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gt2cptblnez.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gt2snxggawi.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gt2ztisivqq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.dianchejie.cn/Article/details/gt2ellkmzkg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yj202588.top/Article/details/gt2ewoqnlhk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gt2hhkyvydx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cjdrbpov.html

Py:   pickle.dumps(obj)
来源：http://dali.jianghu66.top/Article/details/gt2pokrlozm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.havefunace.top/Article/details/gt2ygeaufjc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.vqdsnc.cn/Article/details/gt2mvjtjcud.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhongyouzk.top/Article/details/gt2nwttevgy.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yuanzhike.top/Article/details/gt2fvfvnigo.html

Go:   encoding/gob
来源：http://dali.nanxinkj.top/Article/details/gt2gbcphzle.html

Ruby: Marshal.dump(obj)
来源：http://dali.meibo888.top/Article/details/gt2tvreqbyw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2huniuaia.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2tvdlcagd.html

L. 网络请求
来源：http://dali.dianchejie.cn/Article/details/gt2zpjvgsqd.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qefrwukm.html

[L01] 发送 GET 请求
来源：http://dali.shuidangran.top/Article/details/gt2lheathtp.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sufxvd.cn/Article/details/gt2qdwvyhmu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jlsjyb.cn/Article/details/gt2xkzphvaj.html

JS:   await fetch(url)
来源：http://dali.yj202588.top/Article/details/gt2gathqabg.html

TS:   await fetch(url)
来源：http://dali.xziqi.cn/Article/details/gt2hzqafuld.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.kuanghao11.cn/Article/details/gt2mqsenxco.html

Go:   resp, err := http.Get(url)
来源：http://dali.birdmap.top/Article/details/gt2mqfcgwiy.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.pengpengdd.cyou/Article/details/gt2wueynqvc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.fzhhl.top/Article/details/gt2oyoiffbb.html

[L02] 发送 POST JSON
来源：http://dali.zhixingplan.top/Article/details/gt2xfwauevm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qdjmpfkg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.dianchejie.cn/Article/details/gt2lsycjlvm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daxiang520.top/Article/details/gt2qvetrhmb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhiwuduotai.top/Article/details/gt2hcltnxdu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xylfe.cn/Article/details/gt2punndjle.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.0kj1m.cn/Article/details/gt2ejyucdgn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yanxiufei.cn/Article/details/gt2picgbpwt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.aizwys.cn/Article/details/gt2gadrlslg.html

[L03] 设置自定义请求头
来源：http://dali.cheryme.top/Article/details/gt2bjnpguzv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.nwbrower.top/Article/details/gt2rdpwsbvq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yongpay.top/Article/details/gt2fdmnnbzl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2miwrgufd.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.redwolf501.top/Article/details/gt2hvpguksg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.andypj.xyz/Article/details/gt2zkoqpwkr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yj20258.top/Article/details/gt2rswreylb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shzxlz.cn/Article/details/gt2xqdsbnzx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eukqxgqq.html

[L04] 设置超时
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dufwzfuz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinqigufen.top/Article/details/gt2eanwnfrs.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kvxbruho.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxinkj.top/Article/details/gt2fanczpur.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yueranfly.top/Article/details/gt2fbuxtplc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yueranfly.top/Article/details/gt2olxkijrr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.wangdashe.top/Article/details/gt2rnpbtzsj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shzxlz.cn/Article/details/gt2odfvohkw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.fzhhl.top/Article/details/gt2uhcmavyp.html

[L05] 上传文件（multipart）
来源：http://dali.quarkkingdee.top/Article/details/gt2dbnfvmeb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.havefunace.top/Article/details/gt2slmnrssf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.pycfn.com/Article/details/gt2ywmllawh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgfzy.top/Article/details/gt2zuypsuut.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kttinlwq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yongpay.top/Article/details/gt2kxvhmhdd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jqgufenzy.top/Article/details/gt2jvfefjvg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.redwolf501.top/Article/details/gt2asvfwdjp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xrifyjdw.html

[L06] 解析响应为 JSON
来源：http://dali.yonumen.top/Article/details/gt2gevxxthz.html

Py:   resp.json()
来源：http://dali.zhongyouzk.top/Article/details/gt2zdbeuahh.html

PHP:  json_decode($body, true);
来源：http://dali.ydzc1.top/Article/details/gt2vlvqvqlp.html

JS:   await resp.json()
来源：http://dali.iojbl.cn/Article/details/gt2oxxizjay.html

TS:   await resp.json()
来源：http://dali.daria6918.cn/Article/details/gt2rvgcrqnf.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cqqwz.cn/Article/details/gt2owlchngs.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.gzhubu.top/Article/details/gt2kgkyqyfe.html

Ruby: JSON.parse(resp.body)
来源：http://dali.haohaochexian.top/Article/details/gt2yduteywc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gzhubu.top/Article/details/gt2cgcubfyk.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj20258888.top/Article/details/gt2lzsorkqu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.iojbl.cn/Article/details/gt2mnychtzh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.daria6918.cn/Article/details/gt2asfxtzid.html

JS:   resp.ok;  resp.status
来源：http://dali.aibaodan.cn/Article/details/gt2sqpdppwa.html

TS:   resp.ok;  resp.status
来源：http://dali.birdmap.top/Article/details/gt2yugzwdgf.html

Java: resp.statusCode()
来源：http://dali.wangshuangyany.cn/Article/details/gt2rxofgsva.html

Go:   resp.StatusCode
来源：http://dali.cashguo.top/Article/details/gt2fxnfdsvn.html

Ruby: resp.code.to_i
来源：http://dali.cashguo.top/Article/details/gt2kkwytcvc.html

C#:   (int)resp.StatusCode
来源：http://dali.9152youxi.cn/Article/details/gt2zwbuhdos.html

[L08] 并发请求多个地址
来源：http://dali.shangyingyoupin.top/Article/details/gt2vnuoqnrs.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xuanzx.com/Article/details/gt2usknlozx.html

PHP:  curl_multi_init() 系列
来源：http://dali.tian-w.cn/Article/details/gt2dzvzxhez.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mqmibsuz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yangfankeji.com/Article/details/gt2rnqkxxuc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zycfv.cn/Article/details/gt2imprkohb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.meibo888.top/Article/details/gt2otdhucyw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shzxlz.cn/Article/details/gt2dwyqsvfv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ivvv.top/Article/details/gt2nhugdquq.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2nipogdzk.html

M. 命令行 / 进程 / 环境
来源：http://dali.pengpengdd.cyou/Article/details/gt2ipbtlzdz.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2glkbxufg.html

[M01] 读取命令行参数
来源：http://dali.guowangkeji.top/Article/details/gt2awyiiklp.html

Py:   sys.argv[1:]
来源：http://dali.shangyingyoupin.top/Article/details/gt2itvkicnz.html

PHP:  $argv;  $argc;
来源：http://dali.jqgfzy.top/Article/details/gt2yarqugfe.html

JS:   process.argv.slice(2)
来源：http://dali.nwbrower.top/Article/details/gt2uhhwcfvl.html

TS:   process.argv.slice(2)
来源：http://dali.hywenlv.cn/Article/details/gt2bchcdoqy.html

Java: args 数组（main 方法参数）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ligkpjfd.html

Go:   os.Args[1:]
来源：http://dali.yuxming.cn/Article/details/gt2akyrvejt.html

Ruby: ARGV
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cisqhtsy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.wangshuangyany.cn/Article/details/gt2omnbqrjg.html

[M02] 读取环境变量
来源：http://dali.c1oappe.top/Article/details/gt2ixcefxza.html

Py:   os.environ.get("HOME")
来源：http://dali.yj202588.top/Article/details/gt2ofyxjsxf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shangyingyoupin.top/Article/details/gt2mpmpthwf.html

JS:   process.env.HOME
来源：http://dali.sysykeji.top/Article/details/gt2bkulgmwh.html

TS:   process.env.HOME
来源：http://dali.ydzc1.top/Article/details/gt2khlihxmq.html

Java: System.getenv("HOME")
来源：http://dali.yj20258.top/Article/details/gt2ccrumcbg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yuanzhike.top/Article/details/gt2qosqsbxf.html

Ruby: ENV["HOME"]
来源：http://dali.iojbl.cn/Article/details/gt2jgaasiev.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ehwqpu.com/Article/details/gt2clppuzjg.html

[M03] 执行外部命令
来源：http://dali.dashuyun.cn/Article/details/gt2dysrmdmd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cheryme.top/Article/details/gt2ozpuwjze.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.guowangkeji.top/Article/details/gt2egcbrzyl.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2itaiedas.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.feifeiyinyue.top/Article/details/gt2wihvwlmy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.nwbrower.top/Article/details/gt2abiflmti.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.bjfxy.top/Article/details/gt2vhynltqu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ivvv.top/Article/details/gt2mtbbiklc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xylfe.cn/Article/details/gt2vlyjmxlb.html

[M04] 获取当前工作目录
来源：http://dali.hammf.cn/Article/details/gt2dihfpbux.html

Py:   os.getcwd()
来源：http://dali.chenzaomai.com/Article/details/gt2nppcmpog.html

PHP:  getcwd();
来源：http://dali.fengsongda.top/Article/details/gt2rdrrwkgj.html

JS:   process.cwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pfqixzrm.html

TS:   process.cwd()
来源：http://dali.ivvv.top/Article/details/gt2hxkwsunn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.havefunace.top/Article/details/gt2ggoyvwvw.html

Go:   os.Getwd()
来源：http://dali.tanke756.top/Article/details/gt2lbquowwj.html

Ruby: Dir.pwd
来源：http://dali.havefunace.top/Article/details/gt2rqpeyumv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.9152youxi.cn/Article/details/gt2aqbkfihq.html

[M05] 设置退出码
来源：http://dali.hysaishi.cn/Article/details/gt2uqpntsnj.html

Py:   sys.exit(1)
来源：http://dali.yj20258888.top/Article/details/gt2uawgfbwz.html

PHP:  exit(1);
来源：http://dali.chenjidiqi.icu/Article/details/gt2hncyomrs.html

JS:   process.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gt2cywjzssx.html

TS:   process.exit(1)
来源：http://dali.cheryme.top/Article/details/gt2laaxyukq.html

Java: System.exit(1)
来源：http://dali.shuidangran.top/Article/details/gt2uninqvng.html

Go:   os.Exit(1)
来源：http://dali.ppjwa.cn/Article/details/gt2dvgreoyg.html

Ruby: exit 1
来源：http://dali.cashguo.top/Article/details/gt2dukvlfdw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.snrcjt.cn/Article/details/gt2eeymztss.html

[M06] 向标准错误输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xnusktok.html

Py:   print("err", file=sys.stderr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xbgjogct.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wdejhpwg.html

JS:   console.error("err")
来源：http://dali.guowangkeji.top/Article/details/gt2uytfsfpi.html

TS:   console.error("err")
来源：http://dali.svipenyu.cn/Article/details/gt2ntzvialq.html

Java: System.err.println("err")
来源：http://dali.tian-w.cn/Article/details/gt2elyxqlia.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.nanxinkj.top/Article/details/gt2ddvuuavl.html

Ruby: warn "err"
来源：http://dali.cashguo.top/Article/details/gt2nvvsuejs.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cashguo.top/Article/details/gt2togmwyov.html

[M07] 判断是否为主入口
来源：http://dali.cqqwz.cn/Article/details/gt2ukqdwrir.html

Py:   if __name__ == "__main__":
来源：http://dali.pycfn.com/Article/details/gt2flvnmcip.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sysykeji.top/Article/details/gt2oavewdiu.html

JS:   require.main === module
来源：http://dali.jinqigufen.top/Article/details/gt2vopxdogl.html

TS:   require.main === module
来源：http://dali.jinqigfzy.top/Article/details/gt2jrihygfo.html

Java: public static void main(String[] args)
来源：http://dali.yangfankeji.com/Article/details/gt2cslqncth.html

Go:   func main()
来源：http://dali.dashuyun.cn/Article/details/gt2oyqrojeh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.mhx1999.top/Article/details/gt2yznqpptb.html

C#:   static void Main(string[] args)
来源：http://dali.vqdsnc.cn/Article/details/gt2yiecgdch.html

[M08] 获取系统与运行时信息
来源：http://dali.yangfankeji.com/Article/details/gt2xanjfffo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.vqdsnc.cn/Article/details/gt2hqxvdeue.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yj20258.top/Article/details/gt2oisfyafr.html

JS:   process.platform;  process.version
来源：http://dali.zhoulong.xyz/Article/details/gt2kkarujxq.html

TS:   process.platform;  process.version
来源：http://dali.yangfankeji.com/Article/details/gt2xhpbkdof.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.chenlongwang.top/Article/details/gt2uzutzbwl.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ivvv.top/Article/details/gt2ehhtlsou.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cashguo.top/Article/details/gt2vtumocvq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hfpthk.cn/Article/details/gt2lofpeonl.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2zkxcabqb.html

N. 数据结构与算法
来源：http://dali.yj20258.top/Article/details/gt2osofsesm.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2erfnpckp.html

[N01] 二分查找（有序数组）
来源：http://dali.hammf.cn/Article/details/gt2cfvjkdcx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2henojoez.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gt2mrzhrups.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fengsongda.top/Article/details/gt2xqbgavke.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hfpthk.cn/Article/details/gt2frzwqblv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2avrsivxk.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.pycfn.com/Article/details/gt2bxpkskzp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cdnleiting.top/Article/details/gt2acsnjuof.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gt2xbxykcng.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinqigufen.top/Article/details/gt2xeqbhghe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuanzx.com/Article/details/gt2kwrkycum.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhoulong.xyz/Article/details/gt2kwvokuhw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gt2dwzrrafk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gotoacloud.top/Article/details/gt2awfidzdr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jyoumei.cn/Article/details/gt2ishuwlll.html

Go:   slices.Sort(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2crotvsbm.html

Ruby: arr.sort
来源：http://dali.yueranfly.top/Article/details/gt2clsxjzsr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2divgqvfp.html

[N03] 快速排序（分治示例）
来源：http://dali.ppjwa.cn/Article/details/gt2lhycdqxp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zdqjudy.top/Article/details/gt2txsjrbip.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhixingplan.top/Article/details/gt2kstkbmba.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xinyue.icu/Article/details/gt2lwzacidn.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hongshengwenyu.top/Article/details/gt2qrpjoaps.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hammf.cn/Article/details/gt2vxihwlpg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.nanxuanxn.top/Article/details/gt2azaiyega.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shzxlz.cn/Article/details/gt2fqqisoxv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.wangdashe.top/Article/details/gt2ygptfjsc.html

[N04] 斐波那契数列
来源：http://dali.andypj.xyz/Article/details/gt2zfbvamtc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xylfe.cn/Article/details/gt2pyddpfyj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gzhubu.top/Article/details/gt2qoroopdl.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.svipenyu.cn/Article/details/gt2hvrsayai.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ejbysnur.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cheryme.top/Article/details/gt2tsvqpasn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hywenlv.cn/Article/details/gt2jvllvscu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2cxtdbtqz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.chenlongwang.top/Article/details/gt2kyzxojju.html

[N05] 最大公约数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lswbklyd.html

Py:   math.gcd(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gt2ytlcugpr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ydzc1.top/Article/details/gt2jtyrallq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhoulong.xyz/Article/details/gt2wntpvxhl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sysykeji.top/Article/details/gt2mljrityp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.mhx1999.top/Article/details/gt2slwmgmhg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zdqjudy.top/Article/details/gt2fgcmjinu.html

Ruby: a.gcd(b)
来源：http://dali.redwolf501.top/Article/details/gt2ynzkjifc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.iojbl.cn/Article/details/gt2rtncsgva.html

[N06] 判断回文字符串
来源：http://dali.hysaishi.cn/Article/details/gt2utqmilqe.html

Py:   s == s[::-1]
来源：http://dali.cqqwz.cn/Article/details/gt2mzhzabut.html

PHP:  $s === strrev($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jekuucui.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2tvcojxsm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fgcqdfkc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ppjwa.cn/Article/details/gt2alnsczms.html

Go:   // 双指针从两端比较
来源：http://dali.kuanghao11.cn/Article/details/gt2bhaoeohb.html

Ruby: s == s.reverse
来源：http://dali.jqgfzy.top/Article/details/gt2vrdaoahi.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yvedp.cn/Article/details/gt2lkrxzbgy.html

[N07] 两数之和（返回下标）
来源：http://dali.yvedp.cn/Article/details/gt2kcryclll.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ehwqpu.com/Article/details/gt2sokhihlc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj202588.top/Article/details/gt2xihurggn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.tian-w.cn/Article/details/gt2rhoozmsg.html

TS:   // 手写 Map<string, number>
来源：http://dali.aibaodan.cn/Article/details/gt2lrtcbtbc.html

Java: // 手写 HashMap
来源：http://dali.hnqzz.top/Article/details/gt2zigonwyz.html

Go:   // 手写 map[int]int
来源：http://dali.daria6918.cn/Article/details/gt2xinsshnb.html

Ruby: // 手写 Hash
来源：http://dali.9152youxi.cn/Article/details/gt2bsejoigv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jqgfzy.top/Article/details/gt2wktzluaz.html

[N08] 生成全排列
来源：http://dali.gaohongyu789.top/Article/details/gt2vsgyfolx.html


<!-- 参考信息 -->