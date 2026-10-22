代发 wailian999

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gotoacloud.top/Article/details/gt2lsptpzcb.html

Go:   json.Marshal(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2frwpzmga.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.feifeiyinyue.top/Article/details/gt2jowgpcqk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2wnhozcvj.html

[K02] JSON 字符串转对象
来源：http://dali.c1oappe.top/Article/details/gt2hkhzdaoy.html

Py:   json.loads(s)
来源：http://dali.hysaishi.cn/Article/details/gt2czorxnvj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.316326.xyz/Article/details/gt2yiwooklw.html

JS:   JSON.parse(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bbrykkci.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqgfzhws.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gzhubu.top/Article/details/gt2xznicpzt.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gotoacloud.top/Article/details/gt2vlwcjfud.html

Ruby: JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gt2qjrcmlvt.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.c1oappe.top/Article/details/gt2tpyfrkqo.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gotoacloud.top/Article/details/gt2vgzqfnuy.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.wangdashe.top/Article/details/gt2hoyxannu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhixingplan.top/Article/details/gt2upznrtvw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yangfankeji.com/Article/details/gt2ripuhgak.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.svipenyu.cn/Article/details/gt2qmqljxui.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gzhubu.top/Article/details/gt2sfkgtvvu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.mhx1999.top/Article/details/gt2qrvunvnx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sweek.top/Article/details/gt2flbgzbjp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cheryme.top/Article/details/gt2laklhppc.html

[K04] 读取 JSON 文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2wmannrgb.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.wangdashe.top/Article/details/gt2hiqkbitx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lzhxzupx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.birdmap.top/Article/details/gt2zqzyupwi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sxryk.cn/Article/details/gt2vgofdfts.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.aizwys.cn/Article/details/gt2coatuyjd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gotoacloud.top/Article/details/gt2fqvpezft.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cdnleiting.top/Article/details/gt2nqtbokhd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.tanke756.top/Article/details/gt2wpelhhxq.html

[K05] 深拷贝对象
来源：http://dali.shangyingyoupin.top/Article/details/gt2uoomjhqk.html

Py:   copy.deepcopy(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2usyqhwqr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ppjwa.cn/Article/details/gt2oervkwnl.html

JS:   structuredClone(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2bvewrtmz.html

TS:   structuredClone(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2gaqgplks.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jlsjyb.cn/Article/details/gt2eohghmie.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yuxming.cn/Article/details/gt2njpvwvyf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cqqwz.cn/Article/details/gt2wxdwpjhl.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yj20258.top/Article/details/gt2vzshdeku.html

[K06] 解析 URL 查询串
来源：http://dali.zhixingplan.top/Article/details/gt2ctjwvmeo.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zycfv.cn/Article/details/gt2pjizytef.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.9152youxi.cn/Article/details/gt2fpgoaynz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenlongwang.top/Article/details/gt2cbnszdst.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jiagoushi.top/Article/details/gt2swzmkutp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.tianlin.xyz/Article/details/gt2elrklwzl.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.dianchejie.cn/Article/details/gt2yxmycgom.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.chenzaomai.com/Article/details/gt2uucxkuom.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.bjfxy.top/Article/details/gt2hbwgjrrm.html

[K07] 进制转换
来源：http://dali.fzhhl.top/Article/details/gt2duxilevq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gt2gmtgtglx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.9152youxi.cn/Article/details/gt2vtrudvax.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gt2byhdmynm.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gt2gzeofvda.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gt2wuxluvva.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhongyouzk.top/Article/details/gt2hgajhtbo.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.svipenyu.cn/Article/details/gt2yukujlsd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gt2lcbsjnbw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yuxming.cn/Article/details/gt2wyozatfm.html

Py:   pickle.dumps(obj)
来源：http://dali.iojbl.cn/Article/details/gt2butxygdn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uzgzmjgp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gaohongyu789.top/Article/details/gt2cbycmdwd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gt2entthqcb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shzxlz.cn/Article/details/gt2rmmlkdjk.html

Go:   encoding/gob
来源：http://dali.zdqjudy.top/Article/details/gt2dbieunkc.html

Ruby: Marshal.dump(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hrmvgikj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.daria6918.cn/Article/details/gt2zxxcgtjt.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2embglgeg.html

L. 网络请求
来源：http://dali.hywenlv.cn/Article/details/gt2ooqanepq.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2kjhsjbrz.html

[L01] 发送 GET 请求
来源：http://dali.cqqwz.cn/Article/details/gt2zahysftm.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.redwolf501.top/Article/details/gt2myjyyjof.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xuetiantiany.cn/Article/details/gt2mzhhyhab.html

JS:   await fetch(url)
来源：http://dali.hfpthk.cn/Article/details/gt2vsoivssf.html

TS:   await fetch(url)
来源：http://dali.yvedp.cn/Article/details/gt2ihinphzz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ehwqpu.com/Article/details/gt2ftybiwek.html

Go:   resp, err := http.Get(url)
来源：http://dali.gogol.net.cn/Article/details/gt2lfslbgcd.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xsrdtsgo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yuanzhike.top/Article/details/gt2ybdeomcl.html

[L02] 发送 POST JSON
来源：http://dali.yuxming.cn/Article/details/gt2wbvnbobt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jlsjyb.cn/Article/details/gt2lclikfoo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yanxiufei.cn/Article/details/gt2ohadeylq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.havefunace.top/Article/details/gt2qfebveyp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shzxlz.cn/Article/details/gt2irfyrhdf.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.tanke756.top/Article/details/gt2dallilhe.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hfpthk.cn/Article/details/gt2coioshmg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.kuanghao11.cn/Article/details/gt2zwotofeb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gotoacloud.top/Article/details/gt2khozkngn.html

[L03] 设置自定义请求头
来源：http://dali.xuetiantiany.cn/Article/details/gt2qjzxfqka.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ivvv.top/Article/details/gt2pfnpbtkl.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenlongwang.top/Article/details/gt2zggriljb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnxiangtu.top/Article/details/gt2mqaairlf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ydzc1.top/Article/details/gt2viltjfmv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jianghu66.top/Article/details/gt2msvlyxec.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.aibaodan.cn/Article/details/gt2agfkcosb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.dianchejie.cn/Article/details/gt2oacqokxm.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.andypj.xyz/Article/details/gt2miecsaxu.html

[L04] 设置超时
来源：http://dali.mhx1999.top/Article/details/gt2llctngcf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zycfv.cn/Article/details/gt2ybllcupg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.mhx1999.top/Article/details/gt2ziarsskf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guowangkeji.top/Article/details/gt2lrnjnazm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mvnckypy.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ivvv.top/Article/details/gt2txucdaut.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sxryk.cn/Article/details/gt2liyauxtw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sysykeji.top/Article/details/gt2eqotxaeb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.dashuyun.cn/Article/details/gt2vopxkldi.html

[L05] 上传文件（multipart）
来源：http://dali.kuanghao11.cn/Article/details/gt2roasqlwe.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.bjfxy.top/Article/details/gt2ouiwzuth.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hfpthk.cn/Article/details/gt2uaxhmcht.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.dianchejie.cn/Article/details/gt2yagrenxi.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xinyue.icu/Article/details/gt2toamzvvs.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xziqi.cn/Article/details/gt2alftfkpj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinqigfzy.top/Article/details/gt2cbsoxogw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.daxiang520.top/Article/details/gt2tjyuxgeq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yj20258.top/Article/details/gt2kklbqras.html

[L06] 解析响应为 JSON
来源：http://dali.yanxiufei.cn/Article/details/gt2ozbgximx.html

Py:   resp.json()
来源：http://dali.vqdsnc.cn/Article/details/gt2zecbwjpe.html

PHP:  json_decode($body, true);
来源：http://dali.sufxvd.cn/Article/details/gt2oyhtbnkz.html

JS:   await resp.json()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fsxketwo.html

TS:   await resp.json()
来源：http://dali.zhiwuduotai.top/Article/details/gt2jnmwunrs.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ytjyhhak.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.fengsongda.top/Article/details/gt2kymeqxua.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hywenlv.cn/Article/details/gt2mgisecwa.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.pengpengdd.cyou/Article/details/gt2lankpgjx.html

[L07] 处理 HTTP 状态码
来源：http://dali.havefunace.top/Article/details/gt2csmcfoid.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gaohongyu789.top/Article/details/gt2gzzduybr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.redwolf501.top/Article/details/gt2jckhuusu.html

JS:   resp.ok;  resp.status
来源：http://dali.chenjidiqi.icu/Article/details/gt2svbfkvsq.html

TS:   resp.ok;  resp.status
来源：http://dali.daxiang520.top/Article/details/gt2oxxaenno.html

Java: resp.statusCode()
来源：http://dali.yvedp.cn/Article/details/gt2baicpedz.html

Go:   resp.StatusCode
来源：http://dali.yvedp.cn/Article/details/gt2xdhfwllf.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqyvlbm.html

C#:   (int)resp.StatusCode
来源：http://dali.jyoumei.cn/Article/details/gt2myswrlol.html

[L08] 并发请求多个地址
来源：http://dali.tianlin.xyz/Article/details/gt2vgukrsej.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cheryme.top/Article/details/gt2hfhbaoke.html

PHP:  curl_multi_init() 系列
来源：http://dali.jiagoushi.top/Article/details/gt2qlnchmfx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aizwys.cn/Article/details/gt2sfzaggwt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pvowfjkz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.wangdashe.top/Article/details/gt2ekwrtxyg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yongpay.top/Article/details/gt2ujycxcya.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hongshengwenyu.top/Article/details/gt2tlthgxqc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.aizwys.cn/Article/details/gt2hafervpq.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2ydfefjey.html

M. 命令行 / 进程 / 环境
来源：http://dali.xuetiantiany.cn/Article/details/gt2jhczejtp.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2ohuvyxwb.html

[M01] 读取命令行参数
来源：http://dali.daria6918.cn/Article/details/gt2trrlggcs.html

Py:   sys.argv[1:]
来源：http://dali.zdqjudy.top/Article/details/gt2pjvxoegy.html

PHP:  $argv;  $argc;
来源：http://dali.vqdsnc.cn/Article/details/gt2msipvzbj.html

JS:   process.argv.slice(2)
来源：http://dali.jqgufenzy.top/Article/details/gt2jvfjpxpd.html

TS:   process.argv.slice(2)
来源：http://dali.nanxinkj.top/Article/details/gt2aohlwvdg.html

Java: args 数组（main 方法参数）
来源：http://dali.ydzc1.top/Article/details/gt2zykftfwa.html

Go:   os.Args[1:]
来源：http://dali.yanxiufei.cn/Article/details/gt2kcsluyde.html

Ruby: ARGV
来源：http://dali.mhx1999.top/Article/details/gt2uzrxwdtd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yuxming.cn/Article/details/gt2clqfhomx.html

[M02] 读取环境变量
来源：http://dali.hywenlv.cn/Article/details/gt2ikvnulyr.html

Py:   os.environ.get("HOME")
来源：http://dali.hammf.cn/Article/details/gt2hqsuyowz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.aibaodan.cn/Article/details/gt2rxoulete.html

JS:   process.env.HOME
来源：http://dali.hnxiangtu.top/Article/details/gt2frwwerqx.html

TS:   process.env.HOME
来源：http://dali.fzhhl.top/Article/details/gt2fwozpgbr.html

Java: System.getenv("HOME")
来源：http://dali.quarkkingdee.top/Article/details/gt2vwcxcbgv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.aibaodan.cn/Article/details/gt2wpnsikhv.html

Ruby: ENV["HOME"]
来源：http://dali.havefunace.top/Article/details/gt2wkwxbjxq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ybcxt.top/Article/details/gt2katmydwd.html

[M03] 执行外部命令
来源：http://dali.bjfxy.top/Article/details/gt2ztpqjywq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cuqxgvbm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.316326.xyz/Article/details/gt2flxzvyqw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.fengsongda.top/Article/details/gt2hgppgfnm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bytapgxp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.havefunace.top/Article/details/gt2mmyfbijd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.andypj.xyz/Article/details/gt2hgfmorho.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xylfe.cn/Article/details/gt2zqjjerat.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xziqi.cn/Article/details/gt2xbhluosd.html

[M04] 获取当前工作目录
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vswczgfz.html

Py:   os.getcwd()
来源：http://dali.xziqi.cn/Article/details/gt2hiphsaqp.html

PHP:  getcwd();
来源：http://dali.gotoacloud.top/Article/details/gt2oeliymiq.html

JS:   process.cwd()
来源：http://dali.yuanzhike.top/Article/details/gt2vqtjykrt.html

TS:   process.cwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kkqjqziz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rmhqmili.html

Go:   os.Getwd()
来源：http://dali.quarkkingdee.top/Article/details/gt2qtcvhwll.html

Ruby: Dir.pwd
来源：http://dali.yj20258.top/Article/details/gt2ssoxxtgo.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.tanke756.top/Article/details/gt2sdmhhqyq.html

[M05] 设置退出码
来源：http://dali.nanxuanxn.top/Article/details/gt2bpivsasf.html

Py:   sys.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2nbowuvyi.html

PHP:  exit(1);
来源：http://dali.yj202588.top/Article/details/gt2axsygrlk.html

JS:   process.exit(1)
来源：http://dali.sysykeji.top/Article/details/gt2ggpcrkrx.html

TS:   process.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2isypjbtq.html

Java: System.exit(1)
来源：http://dali.sysykeji.top/Article/details/gt2vxntesew.html

Go:   os.Exit(1)
来源：http://dali.chenlongwang.top/Article/details/gt2neagkoei.html

Ruby: exit 1
来源：http://dali.gzhubu.top/Article/details/gt2frcidoom.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhoulong.xyz/Article/details/gt2hlqtcrqt.html

[M06] 向标准错误输出
来源：http://dali.sxryk.cn/Article/details/gt2wkkmvlod.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jianghu66.top/Article/details/gt2wbmclfyj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pgivtunj.html

JS:   console.error("err")
来源：http://dali.shuidangran.top/Article/details/gt2mysegzmc.html

TS:   console.error("err")
来源：http://dali.zhongyouzk.top/Article/details/gt2bypxkuxq.html

Java: System.err.println("err")
来源：http://dali.vqdsnc.cn/Article/details/gt2jhmbdpef.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yongpay.top/Article/details/gt2znnovpde.html

Ruby: warn "err"
来源：http://dali.gzhubu.top/Article/details/gt2apxwpesq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.wangdashe.top/Article/details/gt2qzkmbdyd.html

[M07] 判断是否为主入口
来源：http://dali.zhixingplan.top/Article/details/gt2wmqmtgqn.html

Py:   if __name__ == "__main__":
来源：http://dali.xuanzx.com/Article/details/gt2yvlpatfh.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hnqzz.top/Article/details/gt2vmfwlybu.html

JS:   require.main === module
来源：http://dali.chenjidiqi.icu/Article/details/gt2jiuxblss.html

TS:   require.main === module
来源：http://dali.yuanzhike.top/Article/details/gt2gevkqawp.html

Java: public static void main(String[] args)
来源：http://dali.yj20258888.top/Article/details/gt2jaiffzee.html

Go:   func main()
来源：http://dali.jinqigufen.top/Article/details/gt2wyewevjf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gotoacloud.top/Article/details/gt2xqecthez.html

C#:   static void Main(string[] args)
来源：http://dali.ivvv.top/Article/details/gt2glmjrexo.html

[M08] 获取系统与运行时信息
来源：http://dali.pengpengdd.cyou/Article/details/gt2toxmktii.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sweek.top/Article/details/gt2lxsgxinp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yangfankeji.com/Article/details/gt2jsyomqkf.html

JS:   process.platform;  process.version
来源：http://dali.yvedp.cn/Article/details/gt2mvwdkccz.html

TS:   process.platform;  process.version
来源：http://dali.aizwys.cn/Article/details/gt2lqezhxva.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.pycfn.com/Article/details/gt2pgfqwumh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zycfv.cn/Article/details/gt2yaohopfc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.9152youxi.cn/Article/details/gt2kvoaiebl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shzxlz.cn/Article/details/gt2egkcbxlf.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2teztjrmd.html

N. 数据结构与算法
来源：http://dali.hongshengwenyu.top/Article/details/gt2acckjeie.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2wzxmfhov.html

[N01] 二分查找（有序数组）
来源：http://dali.chenzaomai.com/Article/details/gt2hqjykoqq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.wangdashe.top/Article/details/gt2xssuakay.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hnqzz.top/Article/details/gt2yacbvcfp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tanke756.top/Article/details/gt2kwswzkng.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gzhubu.top/Article/details/gt2jvyghplf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gt2lqzpjyjt.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jianghu66.top/Article/details/gt2fituhihl.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.guannengcc.top/Article/details/gt2mgrylgot.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vwjidaix.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yj20258.top/Article/details/gt2nlzbtdqu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tian-w.cn/Article/details/gt2aqitjibg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nwbrower.top/Article/details/gt2qkcopmgc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.quarkkingdee.top/Article/details/gt2ydqrbprr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yvedp.cn/Article/details/gt2gemmbkww.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.9152youxi.cn/Article/details/gt2lmphzhnm.html

Go:   slices.Sort(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2sdqhvfxg.html

Ruby: arr.sort
来源：http://dali.hnqzz.top/Article/details/gt2xgoezgsr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shzxlz.cn/Article/details/gt2vknyqpjl.html

[N03] 快速排序（分治示例）
来源：http://dali.yangfankeji.com/Article/details/gt2duabwoqs.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ybcxt.top/Article/details/gt2nnjiudse.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yongpay.top/Article/details/gt2heiyibuz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangdashe.top/Article/details/gt2piqlfqwv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhiwuduotai.top/Article/details/gt2wjfzjpog.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.c1oappe.top/Article/details/gt2ouiwrhha.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.316326.xyz/Article/details/gt2idqklpns.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.feifeiyinyue.top/Article/details/gt2rhszyihy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cdnleiting.top/Article/details/gt2axcazqdc.html

[N04] 斐波那契数列
来源：http://dali.ppjwa.cn/Article/details/gt2irjkgutp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.dianchejie.cn/Article/details/gt2wshheolh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.iojbl.cn/Article/details/gt2cmvkwnlk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj20258.top/Article/details/gt2gaksjhhq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.svipenyu.cn/Article/details/gt2jqtbwxbf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.chenlongwang.top/Article/details/gt2qdzasxsm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hongshengwenyu.top/Article/details/gt2vmuchaou.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigfzy.top/Article/details/gt2faovvepc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cucudq.cn/Article/details/gt2vylmcdnm.html

[N05] 最大公约数
来源：http://dali.jianghu66.top/Article/details/gt2pryswiqd.html

Py:   math.gcd(a, b)
来源：http://dali.xinyue.icu/Article/details/gt2jgjzadhn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.9152youxi.cn/Article/details/gt2togccjwn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnqzz.top/Article/details/gt2eihcfsyc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ybcxt.top/Article/details/gt2nfpjpjlw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ivvv.top/Article/details/gt2aksskcoh.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xuetiantiany.cn/Article/details/gt2mtbmqibc.html

Ruby: a.gcd(b)
来源：http://dali.yuxming.cn/Article/details/gt2phggaktq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sxryk.cn/Article/details/gt2yogecleb.html

[N06] 判断回文字符串
来源：http://dali.jiagoushi.top/Article/details/gt2dfuxsgrn.html

Py:   s == s[::-1]
来源：http://dali.wangdashe.top/Article/details/gt2actsrhij.html

PHP:  $s === strrev($s);
来源：http://dali.316326.xyz/Article/details/gt2jcupuctc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.feifeiyinyue.top/Article/details/gt2qcaxruun.html

TS:   s === [...s].reverse().join("")
来源：http://dali.daxiang520.top/Article/details/gt2vvrmgiul.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jlsjyb.cn/Article/details/gt2yrxsratd.html

Go:   // 双指针从两端比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cvocgbeh.html

Ruby: s == s.reverse
来源：http://dali.gogol.net.cn/Article/details/gt2cwtyiauw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gavjyzev.html

[N07] 两数之和（返回下标）
来源：http://dali.xinyue.icu/Article/details/gt2jbrldrbz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hpjdxkst.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gogol.net.cn/Article/details/gt2lwxpflif.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jlsjyb.cn/Article/details/gt2mblzysgj.html

TS:   // 手写 Map<string, number>
来源：http://dali.hammf.cn/Article/details/gt2kkuctgld.html

Java: // 手写 HashMap
来源：http://dali.feifeiyinyue.top/Article/details/gt2lxjewkws.html

Go:   // 手写 map[int]int
来源：http://dali.tanke756.top/Article/details/gt2kegageuw.html

Ruby: // 手写 Hash
来源：http://dali.havefunace.top/Article/details/gt2wsuiisua.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ivvv.top/Article/details/gt2rmviblpf.html

[N08] 生成全排列
来源：http://dali.jiagoushi.top/Article/details/gt2zxqmzzeu.html

Py:   itertools.permutations(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2lyofwwsu.html

PHP:  // 手写递归交换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2khqgngbf.html

JS:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gt2uptvlutz.html

TS:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gt2qxakgbkf.html

Java: // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gt2malgvknv.html

Go:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gt2pzdcuqua.html

Ruby: arr.permutation.to_a
来源：http://dali.9152youxi.cn/Article/details/gt2xddkyvja.html

C#:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gt2hzpjfydj.html

[N09] 栈与队列
来源：http://dali.zhixingplan.top/Article/details/gt2qiagxyrs.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.nanxuanxn.top/Article/details/gt2yokqnikd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xuanzx.com/Article/details/gt2fkfdbfmz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hysaishi.cn/Article/details/gt2joaizwcs.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gzhubu.top/Article/details/gt2rkzpwapo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhiviwq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yuxming.cn/Article/details/gt2quqfeogf.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zycfv.cn/Article/details/gt2rbtnxrrn.html


<!-- 参考信息 -->