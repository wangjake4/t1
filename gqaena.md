代发 wailian999

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.tanke756.top/Article/details/gt2uvejwctm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.wangshuangyany.cn/Article/details/gt2hvuvjufb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.pengpengdd.cyou/Article/details/gt2edjxwjyw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.aizwys.cn/Article/details/gt2zkuevsty.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2eheszopr.html

K. JSON 与序列化
来源：http://dali.chenjidiqi.icu/Article/details/gt2xvizzdvv.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jdofbkec.html

[K01] 对象转 JSON 字符串
来源：http://dali.guowangkeji.top/Article/details/gt2qlcumgys.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhiwuduotai.top/Article/details/gt2iwqwuvea.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ydzc1.top/Article/details/gt2remgjxwn.html

JS:   JSON.stringify(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2sppxqnqj.html

TS:   JSON.stringify(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2jgwcuovv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.chenzaomai.com/Article/details/gt2rgjlihuk.html

Go:   json.Marshal(obj)
来源：http://dali.iojbl.cn/Article/details/gt2zhqgtvxg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jiagoushi.top/Article/details/gt2mmrbgdpn.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ebwcisif.html

[K02] JSON 字符串转对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aptjjwzi.html

Py:   json.loads(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2isfcocyu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.c1oappe.top/Article/details/gt2hlneketd.html

JS:   JSON.parse(s)
来源：http://dali.ivvv.top/Article/details/gt2vbepgnqt.html

TS:   JSON.parse(s)
来源：http://dali.andypj.xyz/Article/details/gt2wrjujifo.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jtnibyxd.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhixingplan.top/Article/details/gt2atuuzkjv.html

Ruby: JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gt2uilibkxl.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.daria6918.cn/Article/details/gt2zwwvgmqf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xziqi.cn/Article/details/gt2ylvqatxw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.vqdsnc.cn/Article/details/gt2iubfibsd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.chenzaomai.com/Article/details/gt2vddcrrcd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cqqwz.cn/Article/details/gt2ecocqgth.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2salzkona.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.andypj.xyz/Article/details/gt2xarilffw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhixingplan.top/Article/details/gt2xiipzwkx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.pycfn.com/Article/details/gt2ejjhkqmw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinqigufen.top/Article/details/gt2iuaewisa.html

[K04] 读取 JSON 文件
来源：http://dali.zdqjudy.top/Article/details/gt2xiyhqimd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tanke756.top/Article/details/gt2nepynfzz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.pycfn.com/Article/details/gt2rvuzsmua.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tianlin.xyz/Article/details/gt2rlummdsb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.9152youxi.cn/Article/details/gt2upwfzjbt.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xylfe.cn/Article/details/gt2bbqpdupq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shzxlz.cn/Article/details/gt2txwbjnbx.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zdqjudy.top/Article/details/gt2vmdenehw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sweek.top/Article/details/gt2qgmooqhp.html

[K05] 深拷贝对象
来源：http://dali.0kj1m.cn/Article/details/gt2hkoiacgy.html

Py:   copy.deepcopy(obj)
来源：http://dali.fzhhl.top/Article/details/gt2ajzgtfli.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ivvv.top/Article/details/gt2fnjkqlgq.html

JS:   structuredClone(obj)
来源：http://dali.yuxming.cn/Article/details/gt2juuftlxw.html

TS:   structuredClone(obj)
来源：http://dali.gzhubu.top/Article/details/gt2dmyfhryp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qqydckfa.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yj20258.top/Article/details/gt2ndmxhwok.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cmzmxguf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gotoacloud.top/Article/details/gt2ddpcutqd.html

[K06] 解析 URL 查询串
来源：http://dali.hongshengwenyu.top/Article/details/gt2gigjcdhz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.bjfxy.top/Article/details/gt2kghlscso.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.feifeiyinyue.top/Article/details/gt2kmdijbin.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.dashuyun.cn/Article/details/gt2qpzxiqut.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xylfe.cn/Article/details/gt2syjkfoie.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.daria6918.cn/Article/details/gt2gwzjlckd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gt2zsbglihb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gt2uzcsafrb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.havefunace.top/Article/details/gt2qoucqvtt.html

[K07] 进制转换
来源：http://dali.birdmap.top/Article/details/gt2dafkykzp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gt2fzekzjtf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gaohongyu789.top/Article/details/gt2cfhqinrk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wtizjcqd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ivvv.top/Article/details/gt2ggbsbopp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gt2htikdomx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.chenlongwang.top/Article/details/gt2pukprvmx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hammf.cn/Article/details/gt2pfkxvaub.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gt2exraacis.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cashguo.top/Article/details/gt2fyfbqgww.html

Py:   pickle.dumps(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2dwzqsrjs.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.316326.xyz/Article/details/gt2pymgtrrl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.quarkkingdee.top/Article/details/gt2dotyieqb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.nanxuanxn.top/Article/details/gt2ssiaaqsz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yongpay.top/Article/details/gt2euvppxfb.html

Go:   encoding/gob
来源：http://dali.jyoumei.cn/Article/details/gt2oanoxkdg.html

Ruby: Marshal.dump(obj)
来源：http://dali.yonumen.top/Article/details/gt2tbhfzjnd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhixingplan.top/Article/details/gt2cnycpqin.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2zzdzfkcn.html

L. 网络请求
来源：http://dali.xuetiantiany.cn/Article/details/gt2myakelpd.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2dhwcrdbm.html

[L01] 发送 GET 请求
来源：http://dali.yueranfly.top/Article/details/gt2cavezpcm.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj202588.top/Article/details/gt2nrltjsen.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yonumen.top/Article/details/gt2wezjfhsh.html

JS:   await fetch(url)
来源：http://dali.daxiang520.top/Article/details/gt2xtexctbz.html

TS:   await fetch(url)
来源：http://dali.fengsongda.top/Article/details/gt2psgwnzol.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eysouque.html

Go:   resp, err := http.Get(url)
来源：http://dali.guowangkeji.top/Article/details/gt2xepnjiwa.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.daxiang520.top/Article/details/gt2luywxthj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sysykeji.top/Article/details/gt2ylmvovra.html

[L02] 发送 POST JSON
来源：http://dali.zhoulong.xyz/Article/details/gt2vynbgfxa.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhoulong.xyz/Article/details/gt2lkngcpga.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xuanzx.com/Article/details/gt2umzcwmxj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xinyue.icu/Article/details/gt2ioftkgnq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxuanxn.top/Article/details/gt2rmontrvs.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.birdmap.top/Article/details/gt2qeoruzjy.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bgfsjanz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.guannengcc.top/Article/details/gt2podvrujv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jiagoushi.top/Article/details/gt2zhtqqyji.html

[L03] 设置自定义请求头
来源：http://dali.zhiwuduotai.top/Article/details/gt2beldzzbd.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yueranfly.top/Article/details/gt2wpsvziac.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cqqwz.cn/Article/details/gt2qydfnfns.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yonumen.top/Article/details/gt2tkobdsef.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aizwys.cn/Article/details/gt2ythhdrmu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.tian-w.cn/Article/details/gt2bdlvomnu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vkxnmmby.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.vqdsnc.cn/Article/details/gt2lucoikiq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shangyingyoupin.top/Article/details/gt2jgnjwrrn.html

[L04] 设置超时
来源：http://dali.chenjidiqi.icu/Article/details/gt2ibmkfqwx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhoulong.xyz/Article/details/gt2xbkzvpmj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shzxlz.cn/Article/details/gt2omdaacus.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jianghu66.top/Article/details/gt2bwdojpmf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuxming.cn/Article/details/gt2gqilztgv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shangyingyoupin.top/Article/details/gt2gaguwhcu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ppjwa.cn/Article/details/gt2xzvfhuex.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sfmfspxh.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.aibaodan.cn/Article/details/gt2wjlrwfik.html

[L05] 上传文件（multipart）
来源：http://dali.nanxinkj.top/Article/details/gt2oqjqymjy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cashguo.top/Article/details/gt2chhezaou.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ppjwa.cn/Article/details/gt2yvoixlya.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.meibo888.top/Article/details/gt2zawxjtiu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yonumen.top/Article/details/gt2fwmocknw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yangfankeji.com/Article/details/gt2fkjsspyf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cdnleiting.top/Article/details/gt2sexlnirw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yuxming.cn/Article/details/gt2mapixnwz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sxryk.cn/Article/details/gt2yavssbrb.html

[L06] 解析响应为 JSON
来源：http://dali.redwolf501.top/Article/details/gt2phufgznv.html

Py:   resp.json()
来源：http://dali.yvedp.cn/Article/details/gt2kofwwwwc.html

PHP:  json_decode($body, true);
来源：http://dali.quarkkingdee.top/Article/details/gt2ohvcqqdz.html

JS:   await resp.json()
来源：http://dali.ydzc1.top/Article/details/gt2ypuegxiw.html

TS:   await resp.json()
来源：http://dali.haohaochexian.top/Article/details/gt2salgnadx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gt2xtscwsck.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhongyouzk.top/Article/details/gt2zyeeihgz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.316326.xyz/Article/details/gt2rkqmaviu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.dashuyun.cn/Article/details/gt2oohskayz.html

[L07] 处理 HTTP 状态码
来源：http://dali.gzhubu.top/Article/details/gt2eurxvhzu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.haohaochexian.top/Article/details/gt2kqmdmrsi.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gogol.net.cn/Article/details/gt2bpbzsmkh.html

JS:   resp.ok;  resp.status
来源：http://dali.zhixingplan.top/Article/details/gt2tqipalux.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2bdyiprda.html

Java: resp.statusCode()
来源：http://dali.9152youxi.cn/Article/details/gt2jvyfvygy.html

Go:   resp.StatusCode
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aywbfbno.html

Ruby: resp.code.to_i
来源：http://dali.quarkkingdee.top/Article/details/gt2usfhscka.html

C#:   (int)resp.StatusCode
来源：http://dali.chenjidiqi.icu/Article/details/gt2rfrgldqx.html

[L08] 并发请求多个地址
来源：http://dali.zhixingplan.top/Article/details/gt2nmguswjj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.daria6918.cn/Article/details/gt2dctskliq.html

PHP:  curl_multi_init() 系列
来源：http://dali.hfpthk.cn/Article/details/gt2wjpvmtjx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gt2xqqwarha.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj202588.top/Article/details/gt2dcktigcz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cashguo.top/Article/details/gt2suqxzait.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.quarkkingdee.top/Article/details/gt2fjiyoawc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.vqdsnc.cn/Article/details/gt2ryvcjeyz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhengqikj.top/Article/details/gt2zcntztgv.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2tvqnjxtd.html

M. 命令行 / 进程 / 环境
来源：http://dali.mhx1999.top/Article/details/gt2mcwutfcy.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2rxhftwqg.html

[M01] 读取命令行参数
来源：http://dali.0kj1m.cn/Article/details/gt2hegsnmju.html

Py:   sys.argv[1:]
来源：http://dali.hnxiangtu.top/Article/details/gt2bxbqfeyl.html

PHP:  $argv;  $argc;
来源：http://dali.yangfankeji.com/Article/details/gt2sjuubres.html

JS:   process.argv.slice(2)
来源：http://dali.hywenlv.cn/Article/details/gt2ygzsplof.html

TS:   process.argv.slice(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fnjzhkwl.html

Java: args 数组（main 方法参数）
来源：http://dali.ppjwa.cn/Article/details/gt2gtmxbtbe.html

Go:   os.Args[1:]
来源：http://dali.ivvv.top/Article/details/gt2nhoyosqh.html

Ruby: ARGV
来源：http://dali.hywenlv.cn/Article/details/gt2rprkavve.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vhrimlou.html

[M02] 读取环境变量
来源：http://dali.guowangkeji.top/Article/details/gt2yyueiwlp.html

Py:   os.environ.get("HOME")
来源：http://dali.hnqzz.top/Article/details/gt2wvnzslzn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shuidangran.top/Article/details/gt2vekpsnob.html

JS:   process.env.HOME
来源：http://dali.havefunace.top/Article/details/gt2xdchtiqx.html

TS:   process.env.HOME
来源：http://dali.nanxinkj.top/Article/details/gt2lldlntug.html

Java: System.getenv("HOME")
来源：http://dali.yueranfly.top/Article/details/gt2gsxfntbz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.andypj.xyz/Article/details/gt2tvthsrdh.html

Ruby: ENV["HOME"]
来源：http://dali.xuetiantiany.cn/Article/details/gt2splkosje.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gzhubu.top/Article/details/gt2mdqfcatq.html

[M03] 执行外部命令
来源：http://dali.svipenyu.cn/Article/details/gt2ezlfxryq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ybcxt.top/Article/details/gt2xfkbvfgd.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jqgfzy.top/Article/details/gt2dkcqbycs.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhixingplan.top/Article/details/gt2ozomuuzr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ivvv.top/Article/details/gt2qfmvopnx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qcjgwgtn.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.9152youxi.cn/Article/details/gt2dokksxwb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.nwbrower.top/Article/details/gt2imkkahls.html

C#:   Process.Start("ls", "-l");
来源：http://dali.birdmap.top/Article/details/gt2fbeyiytp.html

[M04] 获取当前工作目录
来源：http://dali.feifeiyinyue.top/Article/details/gt2zbxorzlt.html

Py:   os.getcwd()
来源：http://dali.gogol.net.cn/Article/details/gt2upidwqrn.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2yzklexzq.html

JS:   process.cwd()
来源：http://dali.xuanzx.com/Article/details/gt2yxvjowyi.html

TS:   process.cwd()
来源：http://dali.pengpengdd.cyou/Article/details/gt2rbuqcldj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.tian-w.cn/Article/details/gt2haonjhja.html

Go:   os.Getwd()
来源：http://dali.zhengqikj.top/Article/details/gt2jdvopsqq.html

Ruby: Dir.pwd
来源：http://dali.vqdsnc.cn/Article/details/gt2zclarfyg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xuetiantiany.cn/Article/details/gt2toolcone.html

[M05] 设置退出码
来源：http://dali.c1oappe.top/Article/details/gt2xqorhaep.html

Py:   sys.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2wdxwnynt.html

PHP:  exit(1);
来源：http://dali.zycfv.cn/Article/details/gt2umalctgg.html

JS:   process.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2qnoswcxc.html

TS:   process.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gt2vabfdfex.html

Java: System.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gt2ykrgttxk.html

Go:   os.Exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tvppudst.html

Ruby: exit 1
来源：http://dali.guannengcc.top/Article/details/gt2aqvzkycm.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.andypj.xyz/Article/details/gt2okmiawrh.html

[M06] 向标准错误输出
来源：http://dali.yueranfly.top/Article/details/gt2fpjdgruy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.nanxinkj.top/Article/details/gt2ntavncjz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.aibaodan.cn/Article/details/gt2rwlcjnjh.html

JS:   console.error("err")
来源：http://dali.yanxiufei.cn/Article/details/gt2ksprvxnr.html

TS:   console.error("err")
来源：http://dali.yj20258888.top/Article/details/gt2xsmgiexa.html

Java: System.err.println("err")
来源：http://dali.fzhhl.top/Article/details/gt2lvgqsmbd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hysaishi.cn/Article/details/gt2twhblxxt.html

Ruby: warn "err"
来源：http://dali.ppjwa.cn/Article/details/gt2cctnnnxy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aeijjsve.html

[M07] 判断是否为主入口
来源：http://dali.snrcjt.cn/Article/details/gt2hufedzai.html

Py:   if __name__ == "__main__":
来源：http://dali.guowangkeji.top/Article/details/gt2szgilnzq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yongpay.top/Article/details/gt2oyzhtqtk.html

JS:   require.main === module
来源：http://dali.shangyingyoupin.top/Article/details/gt2bojapebi.html

TS:   require.main === module
来源：http://dali.chenzaomai.com/Article/details/gt2uvcwalvm.html

Java: public static void main(String[] args)
来源：http://dali.yuxming.cn/Article/details/gt2umgkupzc.html

Go:   func main()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pjfvpito.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2feztcqky.html

C#:   static void Main(string[] args)
来源：http://dali.chenjidiqi.icu/Article/details/gt2dpxxuinq.html

[M08] 获取系统与运行时信息
来源：http://dali.sysykeji.top/Article/details/gt2dnwcaftt.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hnqzz.top/Article/details/gt2grjhbsrt.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.smart0.xyz/Article/details/gt2rouxuhpz.html

JS:   process.platform;  process.version
来源：http://dali.zhixingplan.top/Article/details/gt2hthfkkla.html

TS:   process.platform;  process.version
来源：http://dali.hfpthk.cn/Article/details/gt2bozfveaw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jiagoushi.top/Article/details/gt2rqauqlti.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.vqdsnc.cn/Article/details/gt2xjcpycww.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.andypj.xyz/Article/details/gt2kcqyipai.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tian-w.cn/Article/details/gt2ebgfwqfb.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2qcsxpwrf.html

N. 数据结构与算法
来源：http://dali.fengsongda.top/Article/details/gt2falitcva.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2gzpmanhi.html

[N01] 二分查找（有序数组）
来源：http://dali.chenzaomai.com/Article/details/gt2dpwebijp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gt2qruryqmg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.iojbl.cn/Article/details/gt2aphpakrk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guannengcc.top/Article/details/gt2wztehtad.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.iojbl.cn/Article/details/gt2xzeuoyam.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cashguo.top/Article/details/gt2higbohrm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ygoehtav.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhiwuduotai.top/Article/details/gt2kqbernkc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.guannengcc.top/Article/details/gt2itlodedy.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gogol.net.cn/Article/details/gt2iwzmbqic.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2vgeaufnz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yj202588.top/Article/details/gt2tnenwzji.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.meibo888.top/Article/details/gt2cfnqrjsv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuanzhike.top/Article/details/gt2fjnshrzr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shuidangran.top/Article/details/gt2wvltuhmq.html

Go:   slices.Sort(arr)
来源：http://dali.yonumen.top/Article/details/gt2njoribhj.html

Ruby: arr.sort
来源：http://dali.cdnleiting.top/Article/details/gt2jucnrkmd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ciimqmuj.html

[N03] 快速排序（分治示例）
来源：http://dali.9152youxi.cn/Article/details/gt2cswhufvl.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.daxiang520.top/Article/details/gt2euymbyte.html

PHP:  // 递归实现，或用 usort
来源：http://dali.nwbrower.top/Article/details/gt2efdpnslf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.bjfxy.top/Article/details/gt2ibzzawja.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.smart0.xyz/Article/details/gt2oyzewhop.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.haohaochexian.top/Article/details/gt2vopiukqd.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yueranfly.top/Article/details/gt2hhrawvkv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tianlin.xyz/Article/details/gt2eeibeqby.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tianlin.xyz/Article/details/gt2hscwwfra.html

[N04] 斐波那契数列
来源：http://dali.shzxlz.cn/Article/details/gt2xgytqqik.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yfofwsct.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.smart0.xyz/Article/details/gt2tsegnhtl.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shuidangran.top/Article/details/gt2sfybnxpo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gt2imjqxnla.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hywenlv.cn/Article/details/gt2celuhopn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.dashuyun.cn/Article/details/gt2njbhwtwu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yangfankeji.com/Article/details/gt2qxhofdpy.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hywenlv.cn/Article/details/gt2pyqemdmh.html

[N05] 最大公约数
来源：http://dali.hnqzz.top/Article/details/gt2lutykwnt.html

Py:   math.gcd(a, b)
来源：http://dali.wangdashe.top/Article/details/gt2oilhxnrt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.redwolf501.top/Article/details/gt2rbthdtsv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2dvozjdlm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2twbjfjix.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.fzhhl.top/Article/details/gt2hypsqpmr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ppjwa.cn/Article/details/gt2bpgevblx.html

Ruby: a.gcd(b)
来源：http://dali.hysaishi.cn/Article/details/gt2updzvzhf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzawkzk.html

[N06] 判断回文字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2szteuwup.html

Py:   s == s[::-1]
来源：http://dali.shangyingyoupin.top/Article/details/gt2krrwdrtc.html

PHP:  $s === strrev($s);
来源：http://dali.316326.xyz/Article/details/gt2hsyqvrro.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gt2hhylgvxr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gt2tspsufwp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.daxiang520.top/Article/details/gt2jihsrhuu.html

Go:   // 双指针从两端比较
来源：http://dali.pengpengdd.cyou/Article/details/gt2wfyvlsak.html

Ruby: s == s.reverse
来源：http://dali.guowangkeji.top/Article/details/gt2xkryvbjx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2otapgycj.html

[N07] 两数之和（返回下标）
来源：http://dali.ydzc1.top/Article/details/gt2fvvfusue.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hysaishi.cn/Article/details/gt2iijxxavi.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ardpduiz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2owywxexv.html

TS:   // 手写 Map<string, number>
来源：http://dali.yuxming.cn/Article/details/gt2criiqtdp.html

Java: // 手写 HashMap
来源：http://dali.nwbrower.top/Article/details/gt2vjyagxvq.html

Go:   // 手写 map[int]int
来源：http://dali.zhixingplan.top/Article/details/gt2sahuujyq.html

Ruby: // 手写 Hash
来源：http://dali.daxiang520.top/Article/details/gt2zrhgdxug.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhengqikj.top/Article/details/gt2solbsjcx.html

[N08] 生成全排列
来源：http://dali.chenlongwang.top/Article/details/gt2grwiaiuh.html

Py:   itertools.permutations(arr)
来源：http://dali.sysykeji.top/Article/details/gt2lrlcevdo.html

PHP:  // 手写递归交换
来源：http://dali.zhiwuduotai.top/Article/details/gt2qluffttb.html

JS:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gt2xnkzqvfh.html

TS:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gt2nglbqwlk.html


<!-- 参考信息 -->