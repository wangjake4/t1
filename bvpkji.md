代发 wailian999

TS:   JSON.parse(s)
来源：http://dali.dashuyun.cn/Article/details/gtrblvrhkf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yongpay.top/Article/details/gtsdjptabt.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jqgfzy.top/Article/details/gtobatsuoo.html

Ruby: JSON.parse(s)
来源：http://dali.nanxinkj.top/Article/details/gtexbwnuho.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhoulong.xyz/Article/details/gtmjuxsgta.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj20258.top/Article/details/gtuvbmsblv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hongshengwenyu.top/Article/details/gtbcfjgewy.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yanxiufei.cn/Article/details/gtawxvggoq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.redwolf501.top/Article/details/gtdxyczdga.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.aizwys.cn/Article/details/gtftiminey.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.havefunace.top/Article/details/gtkswmzhit.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jyoumei.cn/Article/details/gtzijusdlq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gotoacloud.top/Article/details/gtxujxdwoh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cqqwz.cn/Article/details/gtehmyqnjo.html

[K04] 读取 JSON 文件
来源：http://dali.316326.xyz/Article/details/gtrmgigmms.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xuetiantiany.cn/Article/details/gtrcjgkicb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.guannengcc.top/Article/details/gtllbnrbgt.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhoulong.xyz/Article/details/gtschnmrne.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cdnleiting.top/Article/details/gteusztdsg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yuxming.cn/Article/details/gttcherfgo.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.fzhhl.top/Article/details/gtijsjskgr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yongpay.top/Article/details/gtkqmwisbf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.tian-w.cn/Article/details/gtehthakjo.html

[K05] 深拷贝对象
来源：http://dali.xuanzx.com/Article/details/gtnbxzctyg.html

Py:   copy.deepcopy(obj)
来源：http://dali.xuanzx.com/Article/details/gthpyakuml.html

PHP:  unserialize(serialize($obj));
来源：http://dali.svipenyu.cn/Article/details/gtdrwkeedw.html

JS:   structuredClone(obj)
来源：http://dali.hysaishi.cn/Article/details/gtjioyznyx.html

TS:   structuredClone(obj)
来源：http://dali.fzhhl.top/Article/details/gttqvqgvbv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.pycfn.com/Article/details/gtcguyvnox.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ivvv.top/Article/details/gtppimodlo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.wangshuangyany.cn/Article/details/gtaiycmvlo.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yvedp.cn/Article/details/gtafbstpif.html

[K06] 解析 URL 查询串
来源：http://dali.hysaishi.cn/Article/details/gtvjobthgr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.quarkkingdee.top/Article/details/gttyedaxix.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cqqwz.cn/Article/details/gtrlazklzs.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenzaomai.com/Article/details/gtvdqdizgc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.quarkkingdee.top/Article/details/gtieanpetu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.smart0.xyz/Article/details/gtsgvvezpy.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhixingplan.top/Article/details/gtupsrsbcz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gtfdsperkc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.iojbl.cn/Article/details/gtapztedna.html

[K07] 进制转换
来源：http://dali.wangshuangyany.cn/Article/details/gtmzcpqklx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzewjzhmi.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.chenzaomai.com/Article/details/gtcmqdiprb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gtnimqzbxc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gtlhjyymdl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gthbvgrdwn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.0kj1m.cn/Article/details/gteiotqgwq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jqgufenzy.top/Article/details/gttfcbwfov.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gtahzkemfc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gtjkwvvtbr.html

Py:   pickle.dumps(obj)
来源：http://dali.iojbl.cn/Article/details/gtmzjpjuyh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.dianchejie.cn/Article/details/gtxydtvxud.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhiwuduotai.top/Article/details/gtxwtkehcv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.daxiang520.top/Article/details/gtrjgefwyz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.dashuyun.cn/Article/details/gtnuatlgxj.html

Go:   encoding/gob
来源：http://dali.gotoacloud.top/Article/details/gtkfrnsjrs.html

Ruby: Marshal.dump(obj)
来源：http://dali.sxryk.cn/Article/details/gtjxgpmihh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ehwqpu.com/Article/details/gtmqawwwiu.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtgozolwjp.html

L. 网络请求
来源：http://dali.jyoumei.cn/Article/details/gtagtoplqg.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtfxyppgmm.html

[L01] 发送 GET 请求
来源：http://dali.shanyushiyangkeji.top/Article/details/gturptwztl.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cucudq.cn/Article/details/gtbthtdebq.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xinyue.icu/Article/details/gtsqyfbziy.html

JS:   await fetch(url)
来源：http://dali.zhoulong.xyz/Article/details/gtlqjzfbym.html

TS:   await fetch(url)
来源：http://dali.hfpthk.cn/Article/details/gthywgoeux.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.bjfxy.top/Article/details/gtdncuadny.html

Go:   resp, err := http.Get(url)
来源：http://dali.sufxvd.cn/Article/details/gtrvoyukub.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.iojbl.cn/Article/details/gtsiekzxpt.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jiagoushi.top/Article/details/gtzikmhgpn.html

[L02] 发送 POST JSON
来源：http://dali.dashuyun.cn/Article/details/gtivjsfeib.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hnxiangtu.top/Article/details/gtwigctdeg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xuetiantiany.cn/Article/details/gtwnmdanlw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cqqwz.cn/Article/details/gtlmnjvgil.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.snrcjt.cn/Article/details/gttbihhhhk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ivvv.top/Article/details/gtetwpwqzv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtturrqqic.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jqgfzy.top/Article/details/gtlciambyq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yvedp.cn/Article/details/gthxbxtftr.html

[L03] 设置自定义请求头
来源：http://dali.guowangkeji.top/Article/details/gtibywjgwk.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hysaishi.cn/Article/details/gtzjiualww.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.bjfxy.top/Article/details/gtswagzslt.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guannengcc.top/Article/details/gtfmvbsfqt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnqzz.top/Article/details/gthburoeqg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.svipenyu.cn/Article/details/gtyrlwjrtt.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shzxlz.cn/Article/details/gtuiqyjamf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hysaishi.cn/Article/details/gttjznocxz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hysaishi.cn/Article/details/gtajytaafq.html

[L04] 设置超时
来源：http://dali.xuanzx.com/Article/details/gtlnkeutyj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xuetiantiany.cn/Article/details/gtohfsjgyt.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cqqwz.cn/Article/details/gtsxbndrjp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangdashe.top/Article/details/gtxraxcumg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dashuyun.cn/Article/details/gtjfcwbidt.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.nanxuanxn.top/Article/details/gtllewpcwq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbzuuwdgl.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cheryme.top/Article/details/gtzjtnjkjj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.bjfxy.top/Article/details/gtguldxqko.html

[L05] 上传文件（multipart）
来源：http://dali.bjfxy.top/Article/details/gtjcytloew.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhongyouzk.top/Article/details/gtjfbnrfry.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhengqikj.top/Article/details/gtftwwplmm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cashguo.top/Article/details/gtrbcwltcn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gzhubu.top/Article/details/gtjadnacyc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ivvv.top/Article/details/gtglljiwde.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.daxiang520.top/Article/details/gthaqtxlxj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.9152youxi.cn/Article/details/gtkwznfzwe.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yonumen.top/Article/details/gtbntjdyju.html

[L06] 解析响应为 JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcwsqixyy.html

Py:   resp.json()
来源：http://dali.ybcxt.top/Article/details/gtnpqyipvd.html

PHP:  json_decode($body, true);
来源：http://dali.gzhubu.top/Article/details/gtaygmijzc.html

JS:   await resp.json()
来源：http://dali.hysaishi.cn/Article/details/gtrpcorifw.html

TS:   await resp.json()
来源：http://dali.yj202588.top/Article/details/gtnlkkiqvw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.dianchejie.cn/Article/details/gtoljjqgur.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sufxvd.cn/Article/details/gtzfpzjmnk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.0kj1m.cn/Article/details/gtbingtoev.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hammf.cn/Article/details/gtvafsdacc.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj20258.top/Article/details/gtwfequbgs.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.wangdashe.top/Article/details/gtpdmihowe.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdekhudbg.html

JS:   resp.ok;  resp.status
来源：http://dali.chenjidiqi.icu/Article/details/gtynhkoygm.html

TS:   resp.ok;  resp.status
来源：http://dali.tanke756.top/Article/details/gtfphudult.html

Java: resp.statusCode()
来源：http://dali.dianchejie.cn/Article/details/gtxwjgmlul.html

Go:   resp.StatusCode
来源：http://dali.sxryk.cn/Article/details/gtesufvzgd.html

Ruby: resp.code.to_i
来源：http://dali.kuanghao11.cn/Article/details/gtnegsxnio.html

C#:   (int)resp.StatusCode
来源：http://dali.shangyingyoupin.top/Article/details/gtcmijkfrn.html

[L08] 并发请求多个地址
来源：http://dali.cucudq.cn/Article/details/gteiirywya.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jianghu66.top/Article/details/gteuaknjch.html

PHP:  curl_multi_init() 系列
来源：http://dali.zycfv.cn/Article/details/gtxomrgnsd.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenzaomai.com/Article/details/gtsfybcgyz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jyoumei.cn/Article/details/gtcvhmmuue.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ybcxt.top/Article/details/gteklmxzcn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xylfe.cn/Article/details/gtzxwbgahx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.c1oappe.top/Article/details/gtofpnuugg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gtloxekogj.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtghlqpdwz.html

M. 命令行 / 进程 / 环境
来源：http://dali.hysaishi.cn/Article/details/gtjqfymjrh.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtslbsbwum.html

[M01] 读取命令行参数
来源：http://dali.zdqjudy.top/Article/details/gtpcbcfpuz.html

Py:   sys.argv[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gteposszae.html

PHP:  $argv;  $argc;
来源：http://dali.xinyue.icu/Article/details/gtgxopnfog.html

JS:   process.argv.slice(2)
来源：http://dali.kuanghao11.cn/Article/details/gtobsrksws.html

TS:   process.argv.slice(2)
来源：http://dali.hongshengwenyu.top/Article/details/gtxoljkpfl.html

Java: args 数组（main 方法参数）
来源：http://dali.zycfv.cn/Article/details/gtegpuxmkg.html

Go:   os.Args[1:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvzphcsej.html

Ruby: ARGV
来源：http://dali.feifeiyinyue.top/Article/details/gtvmrnoyst.html

C#:   args 数组（Main 方法参数）
来源：http://dali.smart0.xyz/Article/details/gtdmccmznq.html

[M02] 读取环境变量
来源：http://dali.sysykeji.top/Article/details/gtkbufrbtj.html

Py:   os.environ.get("HOME")
来源：http://dali.aizwys.cn/Article/details/gtpxgwbomp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ivvv.top/Article/details/gtqquyvgxd.html

JS:   process.env.HOME
来源：http://dali.hammf.cn/Article/details/gtogrssmgs.html

TS:   process.env.HOME
来源：http://dali.jqgfzy.top/Article/details/gttqtkrwil.html

Java: System.getenv("HOME")
来源：http://dali.yj20258.top/Article/details/gteibtczcn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cheryme.top/Article/details/gtghykylcf.html

Ruby: ENV["HOME"]
来源：http://dali.yj20258.top/Article/details/gtpljojgeg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.daxiang520.top/Article/details/gthtutlmjh.html

[M03] 执行外部命令
来源：http://dali.andypj.xyz/Article/details/gtulgfmatd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shzxlz.cn/Article/details/gtnejoypuy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj20258888.top/Article/details/gtskvkzfis.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.snrcjt.cn/Article/details/gtpztilxcz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sxryk.cn/Article/details/gtgnwqhcqw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.316326.xyz/Article/details/gtftkkqwhe.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.9152youxi.cn/Article/details/gtgymcqbsb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yueranfly.top/Article/details/gtydnpxzkh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.wangdashe.top/Article/details/gtxbmqkwbb.html

[M04] 获取当前工作目录
来源：http://dali.zhixingplan.top/Article/details/gtfvdyecwf.html

Py:   os.getcwd()
来源：http://dali.wangdashe.top/Article/details/gtkigotgrp.html

PHP:  getcwd();
来源：http://dali.chenjidiqi.icu/Article/details/gtvjpbghcb.html

JS:   process.cwd()
来源：http://dali.yongpay.top/Article/details/gtuphybllm.html

TS:   process.cwd()
来源：http://dali.shangyingyoupin.top/Article/details/gtmveddodd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hammf.cn/Article/details/gtjncvlrdy.html

Go:   os.Getwd()
来源：http://dali.xinyue.icu/Article/details/gttosrtxrr.html

Ruby: Dir.pwd
来源：http://dali.wangdashe.top/Article/details/gtowsyvtxb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.dashuyun.cn/Article/details/gtkflodmyu.html

[M05] 设置退出码
来源：http://dali.ppjwa.cn/Article/details/gtclxzqkyx.html

Py:   sys.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtkuxchqlk.html

PHP:  exit(1);
来源：http://dali.xinyue.icu/Article/details/gturwomlme.html

JS:   process.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gtbxjbskvh.html

TS:   process.exit(1)
来源：http://dali.yonumen.top/Article/details/gtmmouhnsp.html

Java: System.exit(1)
来源：http://dali.daria6918.cn/Article/details/gtwkxyzslm.html

Go:   os.Exit(1)
来源：http://dali.c1oappe.top/Article/details/gtyopqdglb.html

Ruby: exit 1
来源：http://dali.0kj1m.cn/Article/details/gtciunfkqc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yuanzhike.top/Article/details/gtaiborbxp.html

[M06] 向标准错误输出
来源：http://dali.jinghuilouyu.cn/Article/details/gtdfpsxtrh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.mhx1999.top/Article/details/gtydicmadp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nwbrower.top/Article/details/gtdahirlxm.html

JS:   console.error("err")
来源：http://dali.aizwys.cn/Article/details/gtblwozgkr.html

TS:   console.error("err")
来源：http://dali.sweek.top/Article/details/gtnzehibwv.html

Java: System.err.println("err")
来源：http://dali.xinyue.icu/Article/details/gtqhjpcnol.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ivvv.top/Article/details/gtjycxxgpl.html

Ruby: warn "err"
来源：http://dali.nwbrower.top/Article/details/gtzesucwyv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jlsjyb.cn/Article/details/gtehduvucn.html

[M07] 判断是否为主入口
来源：http://dali.xziqi.cn/Article/details/gtqyqceeyg.html

Py:   if __name__ == "__main__":
来源：http://dali.ppjwa.cn/Article/details/gtsrinxpkm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.aizwys.cn/Article/details/gthqiquahy.html

JS:   require.main === module
来源：http://dali.yj20258.top/Article/details/gtpfrpichf.html

TS:   require.main === module
来源：http://dali.316326.xyz/Article/details/gticakqskh.html

Java: public static void main(String[] args)
来源：http://dali.shangyingyoupin.top/Article/details/gtbtmojofc.html

Go:   func main()
来源：http://dali.yangfankeji.com/Article/details/gtlxyzytof.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ivvv.top/Article/details/gtsrpvikzf.html

C#:   static void Main(string[] args)
来源：http://dali.tanke756.top/Article/details/gtoxnjhegj.html

[M08] 获取系统与运行时信息
来源：http://dali.fzhhl.top/Article/details/gtrkxukdvp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jiagoushi.top/Article/details/gtqgjmtrla.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhoulong.xyz/Article/details/gtblcqlkpo.html

JS:   process.platform;  process.version
来源：http://dali.guannengcc.top/Article/details/gtwpjihpse.html

TS:   process.platform;  process.version
来源：http://dali.yanxiufei.cn/Article/details/gtklhuetlt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xziqi.cn/Article/details/gtmbrhjbyh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zdqjudy.top/Article/details/gtcgrjuqsl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gogol.net.cn/Article/details/gtkuwsmjgl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.aizwys.cn/Article/details/gtgymteyul.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtdyfdbwym.html

N. 数据结构与算法
来源：http://dali.smart0.xyz/Article/details/gtzszjawwv.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtxkjqjoci.html

[N01] 二分查找（有序数组）
来源：http://dali.zdqjudy.top/Article/details/gtjfanjmbm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtrvcaeata.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ehwqpu.com/Article/details/gticrguqnc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdnimggyi.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hammf.cn/Article/details/gtzqtuacnt.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtgiuifbpr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtnfgjkspx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.dashuyun.cn/Article/details/gtpjtsbvnu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ivvv.top/Article/details/gtltbgnzlh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.daxiang520.top/Article/details/gtmazdhyuh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhaomingkeji.xyz/Article/details/gthlkrugzm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.bjfxy.top/Article/details/gtuwiozewd.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yonumen.top/Article/details/gtapncapbd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigufen.top/Article/details/gtgoewipme.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xziqi.cn/Article/details/gtfqjdjqzo.html

Go:   slices.Sort(arr)
来源：http://dali.xinyue.icu/Article/details/gtgxptfztv.html

Ruby: arr.sort
来源：http://dali.yj202588.top/Article/details/gtnxltihmm.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdncsyffh.html

[N03] 快速排序（分治示例）
来源：http://dali.jinqigufen.top/Article/details/gtytjmkxia.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.iojbl.cn/Article/details/gtgbjfnafr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhongyouzk.top/Article/details/gtxjejgqnv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangtech.top/Article/details/gtkopwqqpc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shangyingyoupin.top/Article/details/gtfaalmhwy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj20258888.top/Article/details/gtbcdhpkad.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.guowangkeji.top/Article/details/gtgdyzystq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtypuluirj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gogol.net.cn/Article/details/gtlodxfwdf.html

[N04] 斐波那契数列
来源：http://dali.xziqi.cn/Article/details/gttphpnfar.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtehcblrza.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ehwqpu.com/Article/details/gtowqtivez.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuxming.cn/Article/details/gtaewjjsjq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hfpthk.cn/Article/details/gtvaeygfuh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ppjwa.cn/Article/details/gtzzpmuiqe.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yanxiufei.cn/Article/details/gtxkulvmgh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gzhubu.top/Article/details/gtemagtgss.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gtearvawfv.html

[N05] 最大公约数
来源：http://dali.haohaochexian.top/Article/details/gtnkstjobl.html

Py:   math.gcd(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gthcxonaaz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.daria6918.cn/Article/details/gtnhcgjhqn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guannengcc.top/Article/details/gtkeaspzoc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuxming.cn/Article/details/gtaopsawly.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhixingplan.top/Article/details/gtztjjvwwr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.fengsongda.top/Article/details/gtauxuzqau.html

Ruby: a.gcd(b)
来源：http://dali.aizwys.cn/Article/details/gtmryzqjdv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xinyue.icu/Article/details/gtoquasulh.html

[N06] 判断回文字符串
来源：http://dali.0kj1m.cn/Article/details/gtqojpjlhu.html

Py:   s == s[::-1]
来源：http://dali.hfpthk.cn/Article/details/gtqqqjpxis.html

PHP:  $s === strrev($s);
来源：http://dali.jinqigfzy.top/Article/details/gttvslddku.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gthgtnvcca.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gtdqigmwin.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jiagoushi.top/Article/details/gtfvbglemo.html

Go:   // 双指针从两端比较
来源：http://dali.yueranfly.top/Article/details/gtaxdbruve.html

Ruby: s == s.reverse
来源：http://dali.iojbl.cn/Article/details/gtsoprbecr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sufxvd.cn/Article/details/gtsyfptnzq.html

[N07] 两数之和（返回下标）
来源：http://dali.xuetiantiany.cn/Article/details/gttegxdbsl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shangyingyoupin.top/Article/details/gtbufsyjwu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shuidangran.top/Article/details/gtrjitgmfs.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yvedp.cn/Article/details/gtjmajzneu.html

TS:   // 手写 Map<string, number>
来源：http://dali.yueranfly.top/Article/details/gtoswjdrba.html

Java: // 手写 HashMap
来源：http://dali.jinqigfzy.top/Article/details/gtmkxrsmbe.html

Go:   // 手写 map[int]int
来源：http://dali.cucudq.cn/Article/details/gthqbcopfy.html

Ruby: // 手写 Hash
来源：http://dali.nwbrower.top/Article/details/gthtygcsok.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.birdmap.top/Article/details/gtrfjzezps.html

[N08] 生成全排列
来源：http://dali.hfpthk.cn/Article/details/gthabuyrsw.html

Py:   itertools.permutations(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtpuxwqbrp.html

PHP:  // 手写递归交换
来源：http://dali.sufxvd.cn/Article/details/gtoqmujfzs.html

JS:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gtseyiiqlh.html

TS:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gtmovrxrtn.html

Java: // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gtjgvwpwgd.html

Go:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gtpgyahjxo.html

Ruby: arr.permutation.to_a
来源：http://dali.cashguo.top/Article/details/gtmtesnysz.html

C#:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgkviibcy.html

[N09] 栈与队列
来源：http://dali.pengpengdd.cyou/Article/details/gtidwsijfb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.havefunace.top/Article/details/gtxesksofk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinqigufen.top/Article/details/gtqyrtbrph.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gogol.net.cn/Article/details/gtyehelmhv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.pengpengdd.cyou/Article/details/gtantxhecx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.gzhubu.top/Article/details/gtvfdxrnjj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.snrcjt.cn/Article/details/gtgyxpgwwu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sweek.top/Article/details/gtmqtzheyw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cucudq.cn/Article/details/gtppzhedrc.html

[N10] 链表节点定义
来源：http://dali.nanxuanxn.top/Article/details/gteeugasmy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shanyushiyangtech.top/Article/details/gtsdvjjove.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xziqi.cn/Article/details/gtrvzcmzaa.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.meibo888.top/Article/details/gthdwppjhn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.vqdsnc.cn/Article/details/gtbcdcenzh.html

Java: class Node { int v; Node next; }
来源：http://dali.tianlin.xyz/Article/details/gtrnjfxoes.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.nanxuanxn.top/Article/details/gtafyhorwr.html


<!-- 参考信息 -->