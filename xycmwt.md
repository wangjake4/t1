代发 wailian999

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jyoumei.cn/Article/details/gtbgasqkcc.html

Go:   json.Marshal(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtalavoumc.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yuanzhike.top/Article/details/gtpsexjpna.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.dashuyun.cn/Article/details/gthirrddot.html

[K02] JSON 字符串转对象
来源：http://dali.jiagoushi.top/Article/details/gtupetvrha.html

Py:   json.loads(s)
来源：http://dali.yj20258.top/Article/details/gtssbzzxbe.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jqgfzy.top/Article/details/gtufhgvwwr.html

JS:   JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gtpwabhcpm.html

TS:   JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtnpfqahxb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrwkvcwcl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj202588.top/Article/details/gtohswzgjo.html

Ruby: JSON.parse(s)
来源：http://dali.birdmap.top/Article/details/gtvqqgjsea.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cqqwz.cn/Article/details/gtgbigjjew.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jqgufenzy.top/Article/details/gtthozpcdb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cucudq.cn/Article/details/gtvuyblafo.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.9152youxi.cn/Article/details/gtxofcpvrj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.haohaochexian.top/Article/details/gtrpaidizr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gzhubu.top/Article/details/gtrhhwoden.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtmprwjtuh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.havefunace.top/Article/details/gthtndsarp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yj20258888.top/Article/details/gtmhqfuazh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenlongwang.top/Article/details/gtdaighrha.html

[K04] 读取 JSON 文件
来源：http://dali.hnxiangtu.top/Article/details/gtxxelfyae.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.fzhhl.top/Article/details/gtavvhrmyf.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.pengpengdd.cyou/Article/details/gtrwdqxsyo.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.quarkkingdee.top/Article/details/gtvhbaqsku.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xziqi.cn/Article/details/gtmmoawxoy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xziqi.cn/Article/details/gtmgeoifiq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.guowangkeji.top/Article/details/gtjfpxpquy.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.fengsongda.top/Article/details/gtjktcziyd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.andypj.xyz/Article/details/gtblcvzfay.html

[K05] 深拷贝对象
来源：http://dali.cashguo.top/Article/details/gttzuvqqcu.html

Py:   copy.deepcopy(obj)
来源：http://dali.fzhhl.top/Article/details/gtifzbghfv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.pengpengdd.cyou/Article/details/gtqujazyix.html

JS:   structuredClone(obj)
来源：http://dali.xinyue.icu/Article/details/gtwpqkudcv.html

TS:   structuredClone(obj)
来源：http://dali.wangdashe.top/Article/details/gtdebisouz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.andypj.xyz/Article/details/gthtegqipo.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yj202588.top/Article/details/gtzbbwxfft.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ppjwa.cn/Article/details/gtgvkcxpro.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.daria6918.cn/Article/details/gtcnmdzdbq.html

[K06] 解析 URL 查询串
来源：http://dali.nanxinkj.top/Article/details/gtsxejxhjs.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.pycfn.com/Article/details/gtankhndsp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhongyouzk.top/Article/details/gtiedcmext.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daxiang520.top/Article/details/gtanhokkqk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.0kj1m.cn/Article/details/gtqudbjwuu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yj202588.top/Article/details/gtairwquke.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yvedp.cn/Article/details/gtqxyypfio.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gtpwhwrmis.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hnxiangtu.top/Article/details/gtlgviwvfh.html

[K07] 进制转换
来源：http://dali.sysykeji.top/Article/details/gtvylblcin.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtupkqzxwn.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yj20258888.top/Article/details/gtyttikxkj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gtbzsibhbt.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gtppgvlovg.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtupegbucd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.guannengcc.top/Article/details/gtqiwpeawy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.dianchejie.cn/Article/details/gtgksiwqia.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtjoyycrae.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinqigfzy.top/Article/details/gtulevvpdu.html

Py:   pickle.dumps(obj)
来源：http://dali.ybcxt.top/Article/details/gtgqzevjli.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtsruvmmtb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zdqjudy.top/Article/details/gtwdozgjoo.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.nanxinkj.top/Article/details/gtcvcntyam.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xuetiantiany.cn/Article/details/gtgsinbkey.html

Go:   encoding/gob
来源：http://dali.dashuyun.cn/Article/details/gtmxmstljd.html

Ruby: Marshal.dump(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxxnvnoty.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hammf.cn/Article/details/gtjzevssim.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtvdpgkjft.html

L. 网络请求
来源：http://dali.ybcxt.top/Article/details/gtkkwlkhbh.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gthlxholtm.html

[L01] 发送 GET 请求
来源：http://dali.dianchejie.cn/Article/details/gthztybyzh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhongyouzk.top/Article/details/gtfmoyqpab.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yj20258.top/Article/details/gtvivblmqp.html

JS:   await fetch(url)
来源：http://dali.aizwys.cn/Article/details/gtkuyqmnvm.html

TS:   await fetch(url)
来源：http://dali.smart0.xyz/Article/details/gtqjugrxxi.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xylfe.cn/Article/details/gthxsudfjg.html

Go:   resp, err := http.Get(url)
来源：http://dali.0kj1m.cn/Article/details/gtzconugzw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.smart0.xyz/Article/details/gtguysozha.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sxryk.cn/Article/details/gtgallqlvs.html

[L02] 发送 POST JSON
来源：http://dali.yj202588.top/Article/details/gtmwzxisot.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ehwqpu.com/Article/details/gtxarskhpf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.haohaochexian.top/Article/details/gtlvekjame.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cqqwz.cn/Article/details/gtecpfbcjx.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yongpay.top/Article/details/gtunhhtxfx.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yuxming.cn/Article/details/gtkrodgods.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ehwqpu.com/Article/details/gtgvdhjshr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sxryk.cn/Article/details/gtvfeigivg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jianghu66.top/Article/details/gtbtmstfqn.html

[L03] 设置自定义请求头
来源：http://dali.chenzaomai.com/Article/details/gtjuaesuor.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yanxiufei.cn/Article/details/gtakwsyczk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jyoumei.cn/Article/details/gtixxhhcnu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.birdmap.top/Article/details/gtmzefgvvc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xinyue.icu/Article/details/gtsoxplwlt.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtthburrly.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.birdmap.top/Article/details/gtppvnfmhr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.kuanghao11.cn/Article/details/gtkkgfxhqa.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zycfv.cn/Article/details/gtmyveowvj.html

[L04] 设置超时
来源：http://dali.yj20258.top/Article/details/gternvutsk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.kuanghao11.cn/Article/details/gtjkihuetu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.feifeiyinyue.top/Article/details/gtgdpanjxn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gthjhjnaff.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenlongwang.top/Article/details/gtaziziowl.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jlsjyb.cn/Article/details/gtnzgszupj.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yj202588.top/Article/details/gtxnhkfjcx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmuqyojuv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.pengpengdd.cyou/Article/details/gthbtyeupq.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gtpkteyfdx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sxryk.cn/Article/details/gtxvgujopd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gzhubu.top/Article/details/gtmhzrbtfy.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.redwolf501.top/Article/details/gtkdxxtorw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gzhubu.top/Article/details/gtxqmvxogi.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gogol.net.cn/Article/details/gtlznyrqkx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gotoacloud.top/Article/details/gtmvymjtou.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sysykeji.top/Article/details/gtfasrperb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.redwolf501.top/Article/details/gtxkotnisg.html

[L06] 解析响应为 JSON
来源：http://dali.wangdashe.top/Article/details/gtapgsavyd.html

Py:   resp.json()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrerkhgap.html

PHP:  json_decode($body, true);
来源：http://dali.yongpay.top/Article/details/gtqgwedgts.html

JS:   await resp.json()
来源：http://dali.meibo888.top/Article/details/gtozcaechc.html

TS:   await resp.json()
来源：http://dali.ppjwa.cn/Article/details/gtsbnxohis.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yuxming.cn/Article/details/gtmgzgqrtc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sxryk.cn/Article/details/gtgnnbhtpp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cqqwz.cn/Article/details/gtdicpwnbe.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.quarkkingdee.top/Article/details/gtejockklp.html

[L07] 处理 HTTP 状态码
来源：http://dali.yuanzhike.top/Article/details/gtkoxadsom.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhoulong.xyz/Article/details/gttqlxfmuf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.c1oappe.top/Article/details/gtwrlmugqq.html

JS:   resp.ok;  resp.status
来源：http://dali.cucudq.cn/Article/details/gtrhcdcaru.html

TS:   resp.ok;  resp.status
来源：http://dali.nanxinkj.top/Article/details/gtjirruezl.html

Java: resp.statusCode()
来源：http://dali.sweek.top/Article/details/gtozdvasqr.html

Go:   resp.StatusCode
来源：http://dali.hongshengwenyu.top/Article/details/gtzjzacklk.html

Ruby: resp.code.to_i
来源：http://dali.pycfn.com/Article/details/gtjirwejau.html

C#:   (int)resp.StatusCode
来源：http://dali.nanxinkj.top/Article/details/gtndjysyjp.html

[L08] 并发请求多个地址
来源：http://dali.yuanzhike.top/Article/details/gtyqneopgc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhixingplan.top/Article/details/gtrbgvefkv.html

PHP:  curl_multi_init() 系列
来源：http://dali.zycfv.cn/Article/details/gtbotwafoo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtorfffcyc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dashuyun.cn/Article/details/gtjpmhsvif.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shuidangran.top/Article/details/gtnrvlyogl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xinyue.icu/Article/details/gtesxqaxvr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ydzc1.top/Article/details/gthgpqwjqe.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jiagoushi.top/Article/details/gtpjwdsovq.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwnksxcqi.html

M. 命令行 / 进程 / 环境
来源：http://dali.yangfankeji.com/Article/details/gtvslasxrj.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtcmjamlvt.html

[M01] 读取命令行参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfzxhkrhg.html

Py:   sys.argv[1:]
来源：http://dali.sweek.top/Article/details/gtfjwdfhje.html

PHP:  $argv;  $argc;
来源：http://dali.hongshengwenyu.top/Article/details/gtbhstraha.html

JS:   process.argv.slice(2)
来源：http://dali.pengpengdd.cyou/Article/details/gttdxoyeis.html

TS:   process.argv.slice(2)
来源：http://dali.smart0.xyz/Article/details/gtouuimvkw.html

Java: args 数组（main 方法参数）
来源：http://dali.yangfankeji.com/Article/details/gtgejzykmm.html

Go:   os.Args[1:]
来源：http://dali.yangfankeji.com/Article/details/gtcjqzuzue.html

Ruby: ARGV
来源：http://dali.cqqwz.cn/Article/details/gtdxwdyims.html

C#:   args 数组（Main 方法参数）
来源：http://dali.birdmap.top/Article/details/gtexfuhkst.html

[M02] 读取环境变量
来源：http://dali.cdnleiting.top/Article/details/gtjltyqfhp.html

Py:   os.environ.get("HOME")
来源：http://dali.ydzc1.top/Article/details/gtudrdqpuf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jqgfzy.top/Article/details/gtmjcyjxls.html

JS:   process.env.HOME
来源：http://dali.sweek.top/Article/details/gtmqvkeemg.html

TS:   process.env.HOME
来源：http://dali.316326.xyz/Article/details/gtadzsqckz.html

Java: System.getenv("HOME")
来源：http://dali.iojbl.cn/Article/details/gtzixccfvf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gtgozrigjo.html

Ruby: ENV["HOME"]
来源：http://dali.vqdsnc.cn/Article/details/gtmujbpwrv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gzhubu.top/Article/details/gthwgfurqp.html

[M03] 执行外部命令
来源：http://dali.gotoacloud.top/Article/details/gtoxyjszdl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenzaomai.com/Article/details/gtxtxkzhow.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cashguo.top/Article/details/gtjzwffblo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqputsbmw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhengqikj.top/Article/details/gtbzvwhsei.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinqigfzy.top/Article/details/gtgxeusude.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.0kj1m.cn/Article/details/gtwpqyrias.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jqgufenzy.top/Article/details/gtbehniluq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shzxlz.cn/Article/details/gtuwccszna.html

[M04] 获取当前工作目录
来源：http://dali.bjfxy.top/Article/details/gtrgiptstm.html

Py:   os.getcwd()
来源：http://dali.ehwqpu.com/Article/details/gtglmqpjio.html

PHP:  getcwd();
来源：http://dali.ehwqpu.com/Article/details/gtxdexpsig.html

JS:   process.cwd()
来源：http://dali.hammf.cn/Article/details/gtnegxgntd.html

TS:   process.cwd()
来源：http://dali.chenzaomai.com/Article/details/gtgknynmyo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hongshengwenyu.top/Article/details/gtjeblssez.html

Go:   os.Getwd()
来源：http://dali.xylfe.cn/Article/details/gtudtdzcpi.html

Ruby: Dir.pwd
来源：http://dali.jinqigufen.top/Article/details/gtgcyblzqg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nwbrower.top/Article/details/gtllmtlmjv.html

[M05] 设置退出码
来源：http://dali.havefunace.top/Article/details/gtlicbfkpo.html

Py:   sys.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtuugvghwa.html

PHP:  exit(1);
来源：http://dali.guannengcc.top/Article/details/gthwabjyhn.html

JS:   process.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gthpyepisn.html

TS:   process.exit(1)
来源：http://dali.hnqzz.top/Article/details/gtiwtqzgyj.html

Java: System.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gtgdtbiljl.html

Go:   os.Exit(1)
来源：http://dali.smart0.xyz/Article/details/gtqilktomf.html

Ruby: exit 1
来源：http://dali.kuanghao11.cn/Article/details/gthizjxxdl.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinghuilouyu.cn/Article/details/gtzgdzhdhi.html

[M06] 向标准错误输出
来源：http://dali.shuidangran.top/Article/details/gtiwyaghnr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cqqwz.cn/Article/details/gtodsxmnad.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yj202588.top/Article/details/gtzgdshddm.html

JS:   console.error("err")
来源：http://dali.pycfn.com/Article/details/gtgqxfxjtu.html

TS:   console.error("err")
来源：http://dali.hammf.cn/Article/details/gtzrtoaqfw.html

Java: System.err.println("err")
来源：http://dali.nanxuanxn.top/Article/details/gtgpxppigz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shangyingyoupin.top/Article/details/gtoolupiwo.html

Ruby: warn "err"
来源：http://dali.fengsongda.top/Article/details/gtprmwxcxn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.iojbl.cn/Article/details/gtsuqrtwau.html

[M07] 判断是否为主入口
来源：http://dali.feifeiyinyue.top/Article/details/gtbqmlkokl.html

Py:   if __name__ == "__main__":
来源：http://dali.tianlin.xyz/Article/details/gtbwewbzem.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.pycfn.com/Article/details/gticmvboak.html

JS:   require.main === module
来源：http://dali.zycfv.cn/Article/details/gtlzlekoyy.html

TS:   require.main === module
来源：http://dali.gzhubu.top/Article/details/gtybrtmguj.html

Java: public static void main(String[] args)
来源：http://dali.nwbrower.top/Article/details/gtugtrhyye.html

Go:   func main()
来源：http://dali.svipenyu.cn/Article/details/gtzbvbkzua.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvfsmxrqe.html

C#:   static void Main(string[] args)
来源：http://dali.dashuyun.cn/Article/details/gtpviegoyq.html

[M08] 获取系统与运行时信息
来源：http://dali.xuanzx.com/Article/details/gtpwwmrali.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gogol.net.cn/Article/details/gtxlvgxujn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.havefunace.top/Article/details/gtjzufvzsn.html

JS:   process.platform;  process.version
来源：http://dali.xylfe.cn/Article/details/gtwoshiehv.html

TS:   process.platform;  process.version
来源：http://dali.xuetiantiany.cn/Article/details/gtwqlafdpp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cdnleiting.top/Article/details/gttnyjyhou.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.iojbl.cn/Article/details/gtysurjhrx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.fengsongda.top/Article/details/gtzgswrfbt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.dashuyun.cn/Article/details/gtdtofoobu.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtyynroffn.html

N. 数据结构与算法
来源：http://dali.guannengcc.top/Article/details/gtusrtdjhr.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtqvyvjvjq.html

[N01] 二分查找（有序数组）
来源：http://dali.snrcjt.cn/Article/details/gtiojnsxjg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtorbaqsqz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gzhubu.top/Article/details/gtqwlizpvs.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yongpay.top/Article/details/gtnjnfnfcp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gtcgrunfuy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtfktsvwkt.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gtymppicks.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhongyouzk.top/Article/details/gtcprjodmp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtrrwhbcpt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqnibixxz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.bjfxy.top/Article/details/gtexuzwmqx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xylfe.cn/Article/details/gthzpfiubx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwenalbhf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhiwuduotai.top/Article/details/gteurmlkrb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sweek.top/Article/details/gtgugrrdjc.html

Go:   slices.Sort(arr)
来源：http://dali.ydzc1.top/Article/details/gtgnskufeb.html

Ruby: arr.sort
来源：http://dali.cheryme.top/Article/details/gtjhtgreff.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zdqjudy.top/Article/details/gtfztkjzwb.html

[N03] 快速排序（分治示例）
来源：http://dali.haohaochexian.top/Article/details/gtraboblqf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hongshengwenyu.top/Article/details/gtfccfeszn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.aizwys.cn/Article/details/gtjrjmzqxo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dashuyun.cn/Article/details/gtfzfgvaxa.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.9152youxi.cn/Article/details/gtzaomijsd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.fzhhl.top/Article/details/gteuxcfcgp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ivvv.top/Article/details/gtahplrplr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinqigfzy.top/Article/details/gtvhuwacxj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbdnuqvjn.html

[N04] 斐波那契数列
来源：http://dali.shzxlz.cn/Article/details/gtbzgzekax.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.chenlongwang.top/Article/details/gtkajcyyxa.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shuidangran.top/Article/details/gtbodhpnmx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtnibxokfl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dashuyun.cn/Article/details/gtrmkomgpr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hnxiangtu.top/Article/details/gtkpzxkkuw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yj202588.top/Article/details/gtaeiocmjo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.daria6918.cn/Article/details/gtrfdsdjzx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gtelevnoiw.html

[N05] 最大公约数
来源：http://dali.jiagoushi.top/Article/details/gtjbohqhir.html

Py:   math.gcd(a, b)
来源：http://dali.hfpthk.cn/Article/details/gttqzgrlkd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.tanke756.top/Article/details/gtcpfgthcc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkvcbxqdl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sxryk.cn/Article/details/gtpvqhiufi.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yangfankeji.com/Article/details/gthpzbjdec.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.0kj1m.cn/Article/details/gtaxrnsnok.html

Ruby: a.gcd(b)
来源：http://dali.andypj.xyz/Article/details/gtkifywfpr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.redwolf501.top/Article/details/gtuqzllddt.html

[N06] 判断回文字符串
来源：http://dali.tanke756.top/Article/details/gtgiiovfui.html

Py:   s == s[::-1]
来源：http://dali.hnqzz.top/Article/details/gtrtugxtkp.html

PHP:  $s === strrev($s);
来源：http://dali.yj20258.top/Article/details/gturlpocbu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gthqnnjitf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gteshyuhsx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.tianlin.xyz/Article/details/gtvetkqmxn.html

Go:   // 双指针从两端比较
来源：http://dali.bjfxy.top/Article/details/gtauqiedhv.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gtirqdihnw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hnqzz.top/Article/details/gtzwztfehp.html

[N07] 两数之和（返回下标）
来源：http://dali.nwbrower.top/Article/details/gtuoxixycu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.fzhhl.top/Article/details/gttlcggluy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.wangshuangyany.cn/Article/details/gtfzsdffig.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cdnleiting.top/Article/details/gtftocdzde.html

TS:   // 手写 Map<string, number>
来源：http://dali.daria6918.cn/Article/details/gteazpgzxv.html

Java: // 手写 HashMap
来源：http://dali.yuxming.cn/Article/details/gtesgjljye.html

Go:   // 手写 map[int]int
来源：http://dali.zhengqikj.top/Article/details/gtwahuosvu.html

Ruby: // 手写 Hash
来源：http://dali.aibaodan.cn/Article/details/gtkfazamtw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cashguo.top/Article/details/gtwbavyemi.html

[N08] 生成全排列
来源：http://dali.yueranfly.top/Article/details/gtzmkkjwfl.html

Py:   itertools.permutations(arr)
来源：http://dali.gotoacloud.top/Article/details/gtezbaqvus.html

PHP:  // 手写递归交换
来源：http://dali.mhx1999.top/Article/details/gtflbbpkam.html

JS:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gtmrfmcvvk.html

TS:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gtbaihvahm.html

Java: // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gtjtqhwtyk.html

Go:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gtmcltqyfe.html

Ruby: arr.permutation.to_a
来源：http://dali.snrcjt.cn/Article/details/gtazzydaag.html

C#:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gttpeilooz.html

[N09] 栈与队列
来源：http://dali.yj202588.top/Article/details/gthuohfswv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtmedeueqg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhoulong.xyz/Article/details/gtrkgdsrun.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jyoumei.cn/Article/details/gtnvmxywmu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yangfankeji.com/Article/details/gtpvurzyst.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.quarkkingdee.top/Article/details/gtedonjwun.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jqgfzy.top/Article/details/gttstordnw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gtulzuhyxi.html


<!-- 参考信息 -->