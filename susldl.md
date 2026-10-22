代发 wailian999

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtjrowesav.html

K. JSON 与序列化
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrhoeqtkr.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gttuyyrbnk.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenlongwang.top/Article/details/gtzmrvrgxp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.kuanghao11.cn/Article/details/gtvrmnrljf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.kuanghao11.cn/Article/details/gthhimxxjz.html

JS:   JSON.stringify(obj)
来源：http://dali.zhengqikj.top/Article/details/gttguymndk.html

TS:   JSON.stringify(obj)
来源：http://dali.dianchejie.cn/Article/details/gtijlqkjwm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xinyue.icu/Article/details/gtvlcbyosk.html

Go:   json.Marshal(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtpahxqtbg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gaohongyu789.top/Article/details/gtwgupnzsy.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xziqi.cn/Article/details/gtudhythol.html

[K02] JSON 字符串转对象
来源：http://dali.xylfe.cn/Article/details/gtckuqeusi.html

Py:   json.loads(s)
来源：http://dali.nanxinkj.top/Article/details/gtmptjnbyi.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sxryk.cn/Article/details/gtvrwrqgrh.html

JS:   JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbqzvkyrg.html

TS:   JSON.parse(s)
来源：http://dali.snrcjt.cn/Article/details/gtvhupxkbq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.dianchejie.cn/Article/details/gtyasohtzn.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.aibaodan.cn/Article/details/gtaaafwytf.html

Ruby: JSON.parse(s)
来源：http://dali.yj202588.top/Article/details/gttlxavscf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sweek.top/Article/details/gtejebnjts.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jqgufenzy.top/Article/details/gtuohdtdhx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.kuanghao11.cn/Article/details/gtncoxmwur.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinghuilouyu.cn/Article/details/gtnqdqlduy.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.daxiang520.top/Article/details/gthiplmoxa.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj202588.top/Article/details/gtgkokjzgx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.aizwys.cn/Article/details/gtaihqlmdf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.daria6918.cn/Article/details/gtvoxvljhd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinqigufen.top/Article/details/gtbagmmgdk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xuanzx.com/Article/details/gtswstpfrm.html

[K04] 读取 JSON 文件
来源：http://dali.nanxuanxn.top/Article/details/gtnrafsjwy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yuxming.cn/Article/details/gtrwnaqfzy.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.feifeiyinyue.top/Article/details/gtfzxxqgyj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhoulong.xyz/Article/details/gtrqdroinv.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnqzz.top/Article/details/gtfzagfgqc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.andypj.xyz/Article/details/gtwqiwyqww.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.guannengcc.top/Article/details/gtbvckbins.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.redwolf501.top/Article/details/gtokehvqjf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenjidiqi.icu/Article/details/gtykhzmpik.html

[K05] 深拷贝对象
来源：http://dali.meibo888.top/Article/details/gtxzhczldu.html

Py:   copy.deepcopy(obj)
来源：http://dali.gotoacloud.top/Article/details/gthxytatpe.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shuidangran.top/Article/details/gtzacwvjhr.html

JS:   structuredClone(obj)
来源：http://dali.mhx1999.top/Article/details/gtjhslorhm.html

TS:   structuredClone(obj)
来源：http://dali.iojbl.cn/Article/details/gtfzhvmckm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nanxinkj.top/Article/details/gtnztiihtv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.fengsongda.top/Article/details/gtawogdjyg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.havefunace.top/Article/details/gtahzbtfeq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hnxiangtu.top/Article/details/gtqxhlcbwy.html

[K06] 解析 URL 查询串
来源：http://dali.daria6918.cn/Article/details/gtnmirjozu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xylfe.cn/Article/details/gtvolyssnp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgodcrmjc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daria6918.cn/Article/details/gtezajgcef.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuanzhike.top/Article/details/gttijxtgzy.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shangyingyoupin.top/Article/details/gttcdlhmaq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.havefunace.top/Article/details/gtnvaspamj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xuanzx.com/Article/details/gtsljflweg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hnxiangtu.top/Article/details/gtrivwckfy.html

[K07] 进制转换
来源：http://dali.iojbl.cn/Article/details/gtjaphhrbd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yj20258.top/Article/details/gtgiaoouyr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tian-w.cn/Article/details/gthxyohmcn.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gtcafphebb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gtejiuetxx.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtumqrvegn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.snrcjt.cn/Article/details/gtwmnnsgki.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.fzhhl.top/Article/details/gtfbyupzgi.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gtottftghq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ydzc1.top/Article/details/gtbkctuktk.html

Py:   pickle.dumps(obj)
来源：http://dali.cdnleiting.top/Article/details/gtktnkobbd.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.fzhhl.top/Article/details/gtossmrnkd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.0kj1m.cn/Article/details/gtxmvtjniq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yongpay.top/Article/details/gtwvhpotco.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ivvv.top/Article/details/gtjaowrcyi.html

Go:   encoding/gob
来源：http://dali.yuanzhike.top/Article/details/gtkjzciqzc.html

Ruby: Marshal.dump(obj)
来源：http://dali.yj202588.top/Article/details/gtysorvyxr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ivvv.top/Article/details/gtpiwhjxes.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtkujbrzrt.html

L. 网络请求
来源：http://dali.tanke756.top/Article/details/gtkczocabv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gthrxyadgr.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gtcuicvalp.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ehwqpu.com/Article/details/gtdctqmhks.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yangfankeji.com/Article/details/gtqoqypwtt.html

JS:   await fetch(url)
来源：http://dali.tianlin.xyz/Article/details/gtpjtxnvfm.html

TS:   await fetch(url)
来源：http://dali.cdnleiting.top/Article/details/gtqhgbgeqk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jqgufenzy.top/Article/details/gtqsystmev.html

Go:   resp, err := http.Get(url)
来源：http://dali.yongpay.top/Article/details/gtsxadseee.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.havefunace.top/Article/details/gtfsfvlupd.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.chenlongwang.top/Article/details/gtdehkxhbm.html

[L02] 发送 POST JSON
来源：http://dali.hfpthk.cn/Article/details/gtamdpyjhi.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.birdmap.top/Article/details/gtczawzpwv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yonumen.top/Article/details/gtvwbfkvso.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnxiangtu.top/Article/details/gtymlvegrb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guannengcc.top/Article/details/gtbadlrdtu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cdnleiting.top/Article/details/gtrxrherts.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jlsjyb.cn/Article/details/gtfdazekuu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.kuanghao11.cn/Article/details/gtimbhwrnx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.pycfn.com/Article/details/gtgdcqafnb.html

[L03] 设置自定义请求头
来源：http://dali.zycfv.cn/Article/details/gtrfyvvguu.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yvedp.cn/Article/details/gtftkrfemf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyvrwedft.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hywenlv.cn/Article/details/gtuhsmsozv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xinyue.icu/Article/details/gtffbringw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xziqi.cn/Article/details/gtmkpydgmr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jyoumei.cn/Article/details/gtijzireoc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jyoumei.cn/Article/details/gtpbzwssnd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.birdmap.top/Article/details/gtpwkiveqc.html

[L04] 设置超时
来源：http://dali.zhoulong.xyz/Article/details/gtpbyoznqc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.snrcjt.cn/Article/details/gtsbvjyors.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.fzhhl.top/Article/details/gtmvifhihu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zycfv.cn/Article/details/gtfzjqafwa.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ppjwa.cn/Article/details/gtlqfujsdw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hfpthk.cn/Article/details/gtujzpcpek.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.aizwys.cn/Article/details/gtvhwwjbfu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.iojbl.cn/Article/details/gtalkrzxzp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yuxming.cn/Article/details/gtdbcrjzda.html

[L05] 上传文件（multipart）
来源：http://dali.haohaochexian.top/Article/details/gtpsonjqqw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cucudq.cn/Article/details/gtkzujynyc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yvedp.cn/Article/details/gtfponicjt.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtioafhite.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zycfv.cn/Article/details/gtangsugzi.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hywenlv.cn/Article/details/gtittpogga.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.haohaochexian.top/Article/details/gtolrehgbs.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.tanke756.top/Article/details/gtyapdynsu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xinyue.icu/Article/details/gtoclmxxas.html

[L06] 解析响应为 JSON
来源：http://dali.chenjidiqi.icu/Article/details/gtgzxgigsa.html

Py:   resp.json()
来源：http://dali.havefunace.top/Article/details/gtqjkwxgxr.html

PHP:  json_decode($body, true);
来源：http://dali.hnqzz.top/Article/details/gtvvyfvlka.html

JS:   await resp.json()
来源：http://dali.snrcjt.cn/Article/details/gtclndyydb.html

TS:   await resp.json()
来源：http://dali.zhongyouzk.top/Article/details/gtwcjdeiye.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.316326.xyz/Article/details/gtpukispnx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ehwqpu.com/Article/details/gtyhlemclo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.havefunace.top/Article/details/gtlbbdrzsx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cdnleiting.top/Article/details/gtlsqkkzzy.html

[L07] 处理 HTTP 状态码
来源：http://dali.chenzaomai.com/Article/details/gtlvzzauok.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xylfe.cn/Article/details/gtoldjycul.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhiwuduotai.top/Article/details/gtpjwhdftg.html

JS:   resp.ok;  resp.status
来源：http://dali.yonumen.top/Article/details/gtjirsxazo.html

TS:   resp.ok;  resp.status
来源：http://dali.xuanzx.com/Article/details/gtblnnsbxe.html

Java: resp.statusCode()
来源：http://dali.xinyue.icu/Article/details/gtkzphtrgp.html

Go:   resp.StatusCode
来源：http://dali.zdqjudy.top/Article/details/gtyjafozfq.html

Ruby: resp.code.to_i
来源：http://dali.redwolf501.top/Article/details/gtjcmslkvm.html

C#:   (int)resp.StatusCode
来源：http://dali.yj202588.top/Article/details/gtcwpisicg.html

[L08] 并发请求多个地址
来源：http://dali.pengpengdd.cyou/Article/details/gtztuanrdl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhoulong.xyz/Article/details/gtjwcdfhmd.html

PHP:  curl_multi_init() 系列
来源：http://dali.yongpay.top/Article/details/gtfhjilppo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gogol.net.cn/Article/details/gticbcjyas.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.kuanghao11.cn/Article/details/gtinozwojr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shzxlz.cn/Article/details/gtkcjwksqo.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.guannengcc.top/Article/details/gtutjucigk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yanxiufei.cn/Article/details/gtvkaonxcz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sysykeji.top/Article/details/gtsgdcnlrg.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtaujyplit.html

M. 命令行 / 进程 / 环境
来源：http://dali.meibo888.top/Article/details/gtapbsbqyv.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gttmjmmfbj.html

[M01] 读取命令行参数
来源：http://dali.jqgufenzy.top/Article/details/gtlmjsvacb.html

Py:   sys.argv[1:]
来源：http://dali.sxryk.cn/Article/details/gtqxkyqgwy.html

PHP:  $argv;  $argc;
来源：http://dali.sweek.top/Article/details/gtorrqwurl.html

JS:   process.argv.slice(2)
来源：http://dali.yvedp.cn/Article/details/gtrnaglmfy.html

TS:   process.argv.slice(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteuuvjpry.html

Java: args 数组（main 方法参数）
来源：http://dali.jinqigufen.top/Article/details/gtyzamlqqp.html

Go:   os.Args[1:]
来源：http://dali.xinyue.icu/Article/details/gtdgdtokcy.html

Ruby: ARGV
来源：http://dali.nanxuanxn.top/Article/details/gtdcbnlsmm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shanyushiyangtech.top/Article/details/gtiihvwxyo.html

[M02] 读取环境变量
来源：http://dali.birdmap.top/Article/details/gtjgcqxvjm.html

Py:   os.environ.get("HOME")
来源：http://dali.xziqi.cn/Article/details/gtzlxgptjt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.wangshuangyany.cn/Article/details/gtzistyogt.html

JS:   process.env.HOME
来源：http://dali.ppjwa.cn/Article/details/gtgvkkxvan.html

TS:   process.env.HOME
来源：http://dali.guannengcc.top/Article/details/gtnntvgure.html

Java: System.getenv("HOME")
来源：http://dali.jinqigufen.top/Article/details/gtdiomnpqy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cashguo.top/Article/details/gtamtqhrrk.html

Ruby: ENV["HOME"]
来源：http://dali.xuanzx.com/Article/details/gtzcaygasl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jqgfzy.top/Article/details/gtwpuonlbb.html

[M03] 执行外部命令
来源：http://dali.zhoulong.xyz/Article/details/gtugqlzrhp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yj20258888.top/Article/details/gtxmrzkpqf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shangyingyoupin.top/Article/details/gtxwmfxbyy.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.daxiang520.top/Article/details/gttsfprevb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.9152youxi.cn/Article/details/gtxzjkxadq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hnqzz.top/Article/details/gtxqossiqt.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jyoumei.cn/Article/details/gtouzmcxrn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.0kj1m.cn/Article/details/gtybooryef.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinghuilouyu.cn/Article/details/gtbqimtynd.html

[M04] 获取当前工作目录
来源：http://dali.gotoacloud.top/Article/details/gtqknaiefd.html

Py:   os.getcwd()
来源：http://dali.zycfv.cn/Article/details/gtiocacvdd.html

PHP:  getcwd();
来源：http://dali.gotoacloud.top/Article/details/gthwdwvstg.html

JS:   process.cwd()
来源：http://dali.gotoacloud.top/Article/details/gtvmtibujd.html

TS:   process.cwd()
来源：http://dali.jqgfzy.top/Article/details/gtxbqxsfui.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sweek.top/Article/details/gtpydhkffb.html

Go:   os.Getwd()
来源：http://dali.cashguo.top/Article/details/gtsvwhhohb.html

Ruby: Dir.pwd
来源：http://dali.shanyushiyangtech.top/Article/details/gtxtaspheh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hfpthk.cn/Article/details/gtrtpafgir.html

[M05] 设置退出码
来源：http://dali.yongpay.top/Article/details/gtrnctqidk.html

Py:   sys.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdqmxflfm.html

PHP:  exit(1);
来源：http://dali.daxiang520.top/Article/details/gtbzzznbtc.html

JS:   process.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnftlretr.html

TS:   process.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtpmyutzno.html

Java: System.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxwhcpivx.html

Go:   os.Exit(1)
来源：http://dali.sweek.top/Article/details/gtcgbicpdi.html

Ruby: exit 1
来源：http://dali.jiagoushi.top/Article/details/gtddtpwisg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xuetiantiany.cn/Article/details/gtcqapsign.html

[M06] 向标准错误输出
来源：http://dali.sufxvd.cn/Article/details/gtwxumeajv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cheryme.top/Article/details/gthzojxgue.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.mhx1999.top/Article/details/gtzyznnlqz.html

JS:   console.error("err")
来源：http://dali.gotoacloud.top/Article/details/gtzznsghkv.html

TS:   console.error("err")
来源：http://dali.pycfn.com/Article/details/gtnjdsqhni.html

Java: System.err.println("err")
来源：http://dali.bjfxy.top/Article/details/gtzzeasdic.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ybcxt.top/Article/details/gthgbpfwme.html

Ruby: warn "err"
来源：http://dali.bjfxy.top/Article/details/gtkmseipue.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.aizwys.cn/Article/details/gtpxwlyhua.html

[M07] 判断是否为主入口
来源：http://dali.chenlongwang.top/Article/details/gtkqqfaexs.html

Py:   if __name__ == "__main__":
来源：http://dali.pycfn.com/Article/details/gtqxodfkgh.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yanxiufei.cn/Article/details/gtldfvteny.html

JS:   require.main === module
来源：http://dali.gzhubu.top/Article/details/gtydwndghd.html

TS:   require.main === module
来源：http://dali.zhixingplan.top/Article/details/gtmeajxpyt.html

Java: public static void main(String[] args)
来源：http://dali.fzhhl.top/Article/details/gtwanxkjwj.html

Go:   func main()
来源：http://dali.wangshuangyany.cn/Article/details/gtquihymrn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cashguo.top/Article/details/gtwrzezerm.html

C#:   static void Main(string[] args)
来源：http://dali.meibo888.top/Article/details/gtfxlhkebo.html

[M08] 获取系统与运行时信息
来源：http://dali.yj202588.top/Article/details/gtptxiuala.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ehwqpu.com/Article/details/gtdrhmhbcv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.smart0.xyz/Article/details/gtkgxwfnuw.html

JS:   process.platform;  process.version
来源：http://dali.nanxuanxn.top/Article/details/gtfihilgoy.html

TS:   process.platform;  process.version
来源：http://dali.cheryme.top/Article/details/gtmxgyshks.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.mhx1999.top/Article/details/gthghtlihr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinghuilouyu.cn/Article/details/gtltrfmblr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yj20258888.top/Article/details/gtylzudnmk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.dashuyun.cn/Article/details/gtvjkskdzh.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gthcemvlin.html

N. 数据结构与算法
来源：http://dali.yongpay.top/Article/details/gtbheuvoay.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtljukmgwi.html

[N01] 二分查找（有序数组）
来源：http://dali.xylfe.cn/Article/details/gtwmyijdpv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtgrhshnkj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hnqzz.top/Article/details/gtnlzehfhj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cashguo.top/Article/details/gtpzoujwne.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenzaomai.com/Article/details/gtjpcmolhz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtxryfmgrn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtlkahxrfy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfpxpzonz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtdxhkcgil.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenlongwang.top/Article/details/gtzyjwmcld.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.wangshuangyany.cn/Article/details/gtquenquvy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.tanke756.top/Article/details/gtnefpdmtt.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daria6918.cn/Article/details/gtqecqmjuq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigufen.top/Article/details/gtogglrvsq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhongyouzk.top/Article/details/gttotnswzk.html

Go:   slices.Sort(arr)
来源：http://dali.meibo888.top/Article/details/gtqbngillh.html

Ruby: arr.sort
来源：http://dali.cucudq.cn/Article/details/gtimwcuksu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yongpay.top/Article/details/gtngyukpoq.html

[N03] 快速排序（分治示例）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtydslnxai.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hywenlv.cn/Article/details/gtihzyssei.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jyoumei.cn/Article/details/gtzahnperu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhiwuduotai.top/Article/details/gtubdomkfw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hysaishi.cn/Article/details/gtcllpgwik.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.quarkkingdee.top/Article/details/gtjmwgqnlk.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cheryme.top/Article/details/gtnvkoofnl.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cheryme.top/Article/details/gtdizlhvgf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sufxvd.cn/Article/details/gthmvbzbvg.html

[N04] 斐波那契数列
来源：http://dali.yonumen.top/Article/details/gtmwflabtu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmujnmrnc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.0kj1m.cn/Article/details/gtqoqhdnqu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.vqdsnc.cn/Article/details/gtmosrpwte.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fengsongda.top/Article/details/gtmnipedjs.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhongyouzk.top/Article/details/gtzusxsrqa.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hysaishi.cn/Article/details/gtalypwfkg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cucudq.cn/Article/details/gtvthsceqo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yangfankeji.com/Article/details/gtzejcvtrq.html

[N05] 最大公约数
来源：http://dali.yj202588.top/Article/details/gtmeehbvsd.html

Py:   math.gcd(a, b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxdvucgrv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yonumen.top/Article/details/gtmtjwzaos.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aibaodan.cn/Article/details/gtyovfudtl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xylfe.cn/Article/details/gtallkcxcp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yj202588.top/Article/details/gtsaxnydvi.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.daria6918.cn/Article/details/gtajeivcwc.html

Ruby: a.gcd(b)
来源：http://dali.yueranfly.top/Article/details/gtjakzlujc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sysykeji.top/Article/details/gtzduuysgl.html

[N06] 判断回文字符串
来源：http://dali.0kj1m.cn/Article/details/gtedqpecvs.html

Py:   s == s[::-1]
来源：http://dali.yongpay.top/Article/details/gtkbwvathr.html

PHP:  $s === strrev($s);
来源：http://dali.iojbl.cn/Article/details/gtgngwpesj.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gtwbxybisc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gtkgilybpv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ppjwa.cn/Article/details/gthsfunmrx.html

Go:   // 双指针从两端比较
来源：http://dali.snrcjt.cn/Article/details/gtdjyivtwt.html

Ruby: s == s.reverse
来源：http://dali.andypj.xyz/Article/details/gtldgaidnw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yj20258888.top/Article/details/gtgzntnojr.html

[N07] 两数之和（返回下标）
来源：http://dali.guannengcc.top/Article/details/gtbgqfczmc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.birdmap.top/Article/details/gtbruhezqv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.guannengcc.top/Article/details/gttzsbvryc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jqgfzy.top/Article/details/gtmbgwrjpd.html

TS:   // 手写 Map<string, number>
来源：http://dali.yuanzhike.top/Article/details/gtvpxkuoqg.html

Java: // 手写 HashMap
来源：http://dali.yuanzhike.top/Article/details/gtvhomrwms.html

Go:   // 手写 map[int]int
来源：http://dali.xuanzx.com/Article/details/gtrtflmlxb.html

Ruby: // 手写 Hash
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbszdmatc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.nwbrower.top/Article/details/gtoehiwadm.html

[N08] 生成全排列
来源：http://dali.tianlin.xyz/Article/details/gtnnzyeaqc.html

Py:   itertools.permutations(arr)
来源：http://dali.meibo888.top/Article/details/gtyeywfyvl.html

PHP:  // 手写递归交换
来源：http://dali.yj20258.top/Article/details/gtipqaindj.html

JS:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gtcqayrbrk.html

TS:   // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gtwpjnkduq.html

Java: // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gtoegdhdtw.html

Go:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gtlbrxjjhi.html

Ruby: arr.permutation.to_a
来源：http://dali.shuidangran.top/Article/details/gtcvponbtb.html

C#:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gtrhmwonut.html


<!-- 参考信息 -->