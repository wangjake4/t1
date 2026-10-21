代发 wailian999

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.quarkkingdee.top/Article/details/gtxebnzjle.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.birdmap.top/Article/details/gtakodqrpj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hfpthk.cn/Article/details/gtcrqnndzg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.fzhhl.top/Article/details/gthwlfoqww.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hysaishi.cn/Article/details/gttunjdjka.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.svipenyu.cn/Article/details/gtecztisuz.html

[K04] 读取 JSON 文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtagsldshd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.feifeiyinyue.top/Article/details/gtplovjoul.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.feifeiyinyue.top/Article/details/gtdxsdykmy.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xylfe.cn/Article/details/gtlrrrclbn.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuanzx.com/Article/details/gtfhjdngmq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cdnleiting.top/Article/details/gtuxndshnp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.feifeiyinyue.top/Article/details/gtoefwzrap.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.9152youxi.cn/Article/details/gtciiczlzl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hysaishi.cn/Article/details/gtnznagwuu.html

[K05] 深拷贝对象
来源：http://dali.jinghuilouyu.cn/Article/details/gtgtyazcza.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinqigufen.top/Article/details/gteszhvsfh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.nanxuanxn.top/Article/details/gtjfiecrie.html

JS:   structuredClone(obj)
来源：http://dali.mhx1999.top/Article/details/gtbegtixab.html

TS:   structuredClone(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfynykjms.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.guannengcc.top/Article/details/gttxjwitwo.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hnqzz.top/Article/details/gtdsuolchx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.wangshuangyany.cn/Article/details/gthduefrje.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yonumen.top/Article/details/gtpeeeofdi.html

[K06] 解析 URL 查询串
来源：http://dali.fengsongda.top/Article/details/gthzzwrkeq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sysykeji.top/Article/details/gttcdnrpvf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hongshengwenyu.top/Article/details/gtozwcgjmo.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nwbrower.top/Article/details/gtbssxivwb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtemiakayj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ivvv.top/Article/details/gtcvwlaylc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gtqltgsnga.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gtaydnbbae.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jianghu66.top/Article/details/gttrjjvwan.html

[K07] 进制转换
来源：http://dali.cdnleiting.top/Article/details/gtepfntfat.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gtqlttctzn.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sysykeji.top/Article/details/gtfvdnopcc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gtruikbqeo.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gtxotmvdig.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gtvokuferb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaiybzrfr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jianghu66.top/Article/details/gtuujyiavg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gtajwfqfck.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenjidiqi.icu/Article/details/gthfbasevf.html

Py:   pickle.dumps(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtmgffvwmd.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cashguo.top/Article/details/gtwqskwftl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigfzy.top/Article/details/gtnotxtcvr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jiagoushi.top/Article/details/gtfzayjbgv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj20258.top/Article/details/gtoydoklgt.html

Go:   encoding/gob
来源：http://dali.xuetiantiany.cn/Article/details/gtxnzypfrw.html

Ruby: Marshal.dump(obj)
来源：http://dali.hysaishi.cn/Article/details/gtbvhxcbcz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwhwmtlsf.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gthybxnigc.html

L. 网络请求
来源：http://dali.daxiang520.top/Article/details/gtodspplsr.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtvmajikzo.html

[L01] 发送 GET 请求
来源：http://dali.yonumen.top/Article/details/gtnanmpjpe.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jianghu66.top/Article/details/gtvwnzdopw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.svipenyu.cn/Article/details/gtcnvonymz.html

JS:   await fetch(url)
来源：http://dali.gaohongyu789.top/Article/details/gtbrvgkmlu.html

TS:   await fetch(url)
来源：http://dali.hongshengwenyu.top/Article/details/gtstobwaod.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jqgfzy.top/Article/details/gttloawldf.html

Go:   resp, err := http.Get(url)
来源：http://dali.jianghu66.top/Article/details/gtfzcmgfka.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gzhubu.top/Article/details/gttqaoubwo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shangyingyoupin.top/Article/details/gtfhrssyef.html

[L02] 发送 POST JSON
来源：http://dali.havefunace.top/Article/details/gtawmjpmdp.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yj20258888.top/Article/details/gtoptsbeau.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.nwbrower.top/Article/details/gtxgarqbrt.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pengpengdd.cyou/Article/details/gtpehtfikf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shangyingyoupin.top/Article/details/gtjlpvmymz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.feifeiyinyue.top/Article/details/gtrigppwkw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.haohaochexian.top/Article/details/gtdjajamtj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ybcxt.top/Article/details/gtumvsxtfv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hnxiangtu.top/Article/details/gtcpxxcako.html

[L03] 设置自定义请求头
来源：http://dali.pengpengdd.cyou/Article/details/gtmpwetmvg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.aibaodan.cn/Article/details/gtzrjmltlq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yueranfly.top/Article/details/gtnggpipou.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuetiantiany.cn/Article/details/gtzmradrqi.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gotoacloud.top/Article/details/gtkopcdivf.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.nanxuanxn.top/Article/details/gtpfqmzfcn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yangfankeji.com/Article/details/gtqjjqtfkt.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jqgufenzy.top/Article/details/gtntcvlvqt.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gzhubu.top/Article/details/gtyuhladar.html

[L04] 设置超时
来源：http://dali.nanxinkj.top/Article/details/gtumtrbumz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xuetiantiany.cn/Article/details/gtolwqqxmp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.andypj.xyz/Article/details/gtkbslszkv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxinkj.top/Article/details/gtixkwsfht.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tian-w.cn/Article/details/gtyokmqqvr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.daxiang520.top/Article/details/gtphtxjfrc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cqqwz.cn/Article/details/gtvnkvaoyt.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.wangshuangyany.cn/Article/details/gtjafcdwge.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yj20258888.top/Article/details/gtxfrywmxz.html

[L05] 上传文件（multipart）
来源：http://dali.sweek.top/Article/details/gtngqnicmq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yvedp.cn/Article/details/gtewywfdst.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.c1oappe.top/Article/details/gtlrlsdluo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.kuanghao11.cn/Article/details/gtrxyxuwvl.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gaohongyu789.top/Article/details/gteljmeiom.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shuidangran.top/Article/details/gthupoouhe.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gaohongyu789.top/Article/details/gtqrllnzog.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.guannengcc.top/Article/details/gtxzplohrp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.pycfn.com/Article/details/gtyivvwodm.html

[L06] 解析响应为 JSON
来源：http://dali.yangfankeji.com/Article/details/gtmqcgilmd.html

Py:   resp.json()
来源：http://dali.hnxiangtu.top/Article/details/gtpsailhwq.html

PHP:  json_decode($body, true);
来源：http://dali.zhongyouzk.top/Article/details/gtnrzyfmrh.html

JS:   await resp.json()
来源：http://dali.xuetiantiany.cn/Article/details/gtstkefqal.html

TS:   await resp.json()
来源：http://dali.aibaodan.cn/Article/details/gtgosuloen.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.daxiang520.top/Article/details/gtypuyxeob.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xuetiantiany.cn/Article/details/gtujradogq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.svipenyu.cn/Article/details/gtiivyaavi.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.feifeiyinyue.top/Article/details/gtsrcltilo.html

[L07] 处理 HTTP 状态码
来源：http://dali.c1oappe.top/Article/details/gtrujygjxm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj20258888.top/Article/details/gtphmpgqac.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hongshengwenyu.top/Article/details/gtavtwzrkt.html

JS:   resp.ok;  resp.status
来源：http://dali.fzhhl.top/Article/details/gtkfnyfbat.html

TS:   resp.ok;  resp.status
来源：http://dali.yonumen.top/Article/details/gtswaxiput.html

Java: resp.statusCode()
来源：http://dali.yj20258.top/Article/details/gtwvrnjvsi.html

Go:   resp.StatusCode
来源：http://dali.yj20258.top/Article/details/gteqcfnbob.html

Ruby: resp.code.to_i
来源：http://dali.ppjwa.cn/Article/details/gtredrmhwr.html

C#:   (int)resp.StatusCode
来源：http://dali.yongpay.top/Article/details/gtzufacmll.html

[L08] 并发请求多个地址
来源：http://dali.vqdsnc.cn/Article/details/gtzrvmhabz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jianghu66.top/Article/details/gtamkqowwp.html

PHP:  curl_multi_init() 系列
来源：http://dali.redwolf501.top/Article/details/gtbrjzqzgn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.316326.xyz/Article/details/gtextypins.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gtqamtokaa.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinqigufen.top/Article/details/gtnexmvunm.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ydzc1.top/Article/details/gtpzqznvac.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.pengpengdd.cyou/Article/details/gtdgqentrk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jqgfzy.top/Article/details/gtvvxrsxez.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtesquwslm.html

M. 命令行 / 进程 / 环境
来源：http://dali.yangfankeji.com/Article/details/gtihspudbt.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtgwdnvmio.html

[M01] 读取命令行参数
来源：http://dali.yj202588.top/Article/details/gthjfdixzy.html

Py:   sys.argv[1:]
来源：http://dali.fengsongda.top/Article/details/gtdjtchaho.html

PHP:  $argv;  $argc;
来源：http://dali.jqgufenzy.top/Article/details/gtrobknxav.html

JS:   process.argv.slice(2)
来源：http://dali.sweek.top/Article/details/gtbjoihifi.html

TS:   process.argv.slice(2)
来源：http://dali.sxryk.cn/Article/details/gtmcbaybte.html

Java: args 数组（main 方法参数）
来源：http://dali.zhoulong.xyz/Article/details/gtuprvjmit.html

Go:   os.Args[1:]
来源：http://dali.hnqzz.top/Article/details/gtxhncdtqh.html

Ruby: ARGV
来源：http://dali.yonumen.top/Article/details/gtxrcdivoc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gtopcbarbb.html

[M02] 读取环境变量
来源：http://dali.andypj.xyz/Article/details/gtcutjbvra.html

Py:   os.environ.get("HOME")
来源：http://dali.guowangkeji.top/Article/details/gtnukpupnq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xuanzx.com/Article/details/gtuvdefnjl.html

JS:   process.env.HOME
来源：http://dali.hammf.cn/Article/details/gtzychliwr.html

TS:   process.env.HOME
来源：http://dali.yonumen.top/Article/details/gtzzdfpoev.html

Java: System.getenv("HOME")
来源：http://dali.ydzc1.top/Article/details/gtalgnponw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gogol.net.cn/Article/details/gtoasbdmwj.html

Ruby: ENV["HOME"]
来源：http://dali.zhixingplan.top/Article/details/gtwhgxpqui.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cqqwz.cn/Article/details/gtjakujdeu.html

[M03] 执行外部命令
来源：http://dali.xuanzx.com/Article/details/gtwgojpmws.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yueranfly.top/Article/details/gtaqnkjksm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xinyue.icu/Article/details/gtwgqgctrr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zycfv.cn/Article/details/gtdvrqhila.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cucudq.cn/Article/details/gtfyiffeiw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.smart0.xyz/Article/details/gtznbzgztc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jianghu66.top/Article/details/gtcvmzikbx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hywenlv.cn/Article/details/gtelccfagk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.redwolf501.top/Article/details/gtolcbsybo.html

[M04] 获取当前工作目录
来源：http://dali.yangfankeji.com/Article/details/gtgryadsxh.html

Py:   os.getcwd()
来源：http://dali.tianlin.xyz/Article/details/gtdoywlqzy.html

PHP:  getcwd();
来源：http://dali.birdmap.top/Article/details/gtdypgurdl.html

JS:   process.cwd()
来源：http://dali.nwbrower.top/Article/details/gtqmkmcagh.html

TS:   process.cwd()
来源：http://dali.zdqjudy.top/Article/details/gtwoivcivz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yonumen.top/Article/details/gtlhobvizh.html

Go:   os.Getwd()
来源：http://dali.dianchejie.cn/Article/details/gtmmfowqmf.html

Ruby: Dir.pwd
来源：http://dali.jqgufenzy.top/Article/details/gtouvmjpzg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yueranfly.top/Article/details/gtrbveorqo.html

[M05] 设置退出码
来源：http://dali.zdqjudy.top/Article/details/gtfpxguiwy.html

Py:   sys.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtewhvalfl.html

PHP:  exit(1);
来源：http://dali.shangyingyoupin.top/Article/details/gttftzmwjt.html

JS:   process.exit(1)
来源：http://dali.havefunace.top/Article/details/gtpvlbxyzw.html

TS:   process.exit(1)
来源：http://dali.meibo888.top/Article/details/gtuxlrusyg.html

Java: System.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gthtxocpyo.html

Go:   os.Exit(1)
来源：http://dali.shzxlz.cn/Article/details/gtjrtyiqxi.html

Ruby: exit 1
来源：http://dali.yangfankeji.com/Article/details/gtqqdifnsn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvtyvqdnq.html

[M06] 向标准错误输出
来源：http://dali.fzhhl.top/Article/details/gtxvymhlvt.html

Py:   print("err", file=sys.stderr)
来源：http://dali.316326.xyz/Article/details/gtbtpfiorj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cdnleiting.top/Article/details/gtpurczqge.html

JS:   console.error("err")
来源：http://dali.yonumen.top/Article/details/gtxdlxxccs.html

TS:   console.error("err")
来源：http://dali.birdmap.top/Article/details/gtiauwkwwm.html

Java: System.err.println("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvhndefog.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sxryk.cn/Article/details/gtboyrfdes.html

Ruby: warn "err"
来源：http://dali.xuanzx.com/Article/details/gtweksucpx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinqigufen.top/Article/details/gtmjhmypdv.html

[M07] 判断是否为主入口
来源：http://dali.dianchejie.cn/Article/details/gtlljybmla.html

Py:   if __name__ == "__main__":
来源：http://dali.snrcjt.cn/Article/details/gtxpuaauvm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jianghu66.top/Article/details/gtczliyuwi.html

JS:   require.main === module
来源：http://dali.xziqi.cn/Article/details/gtpsaihcza.html

TS:   require.main === module
来源：http://dali.jinqigfzy.top/Article/details/gtvcnvutff.html

Java: public static void main(String[] args)
来源：http://dali.ehwqpu.com/Article/details/gtddwfoiab.html

Go:   func main()
来源：http://dali.chenzaomai.com/Article/details/gtiviwcxcq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jlsjyb.cn/Article/details/gtmcgxoipn.html

C#:   static void Main(string[] args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrwmklqft.html

[M08] 获取系统与运行时信息
来源：http://dali.gaohongyu789.top/Article/details/gtkmnqadbq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jqgufenzy.top/Article/details/gtbnnwshgx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jlsjyb.cn/Article/details/gtwrsfmwaw.html

JS:   process.platform;  process.version
来源：http://dali.redwolf501.top/Article/details/gtsrywpiqe.html

TS:   process.platform;  process.version
来源：http://dali.chenzaomai.com/Article/details/gtrdyzbaqo.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yanxiufei.cn/Article/details/gtucuhgqjg.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hongshengwenyu.top/Article/details/gtwtvgtulr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sweek.top/Article/details/gtettdgtse.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yueranfly.top/Article/details/gtlxjigktx.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtuxfpfwqw.html

N. 数据结构与算法
来源：http://dali.xinyue.icu/Article/details/gtrefjacpz.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtbcelmtoz.html

[N01] 二分查找（有序数组）
来源：http://dali.jianghu66.top/Article/details/gtbpnudhvv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtrjqjpuaq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nanxinkj.top/Article/details/gtvmudjijh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxuanxn.top/Article/details/gtjkkvkpht.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxinkj.top/Article/details/gtxrcqrlui.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cheryme.top/Article/details/gtrnffiqff.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtwwtnuvjv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.bjfxy.top/Article/details/gtrgqicsgr.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtfylyvntp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yanxiufei.cn/Article/details/gttwuupcjy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzbegimxx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.gotoacloud.top/Article/details/gtgzpkxnpb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dianchejie.cn/Article/details/gtusbqibho.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yonumen.top/Article/details/gtjbjkbksy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jianghu66.top/Article/details/gtcmdbftyy.html

Go:   slices.Sort(arr)
来源：http://dali.yj20258888.top/Article/details/gtyxzecdqq.html

Ruby: arr.sort
来源：http://dali.tianlin.xyz/Article/details/gtdvgsixae.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhengqikj.top/Article/details/gtwtzxozor.html

[N03] 快速排序（分治示例）
来源：http://dali.iojbl.cn/Article/details/gteiurredm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ydzc1.top/Article/details/gtsfgqczvp.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yonumen.top/Article/details/gtonrysnde.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.0kj1m.cn/Article/details/gtfiiekqpr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigufen.top/Article/details/gtbsboxrsv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ehwqpu.com/Article/details/gtiuptelxp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.wangshuangyany.cn/Article/details/gtnawsxerj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlueqmzec.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.guannengcc.top/Article/details/gtkyymuapa.html

[N04] 斐波那契数列
来源：http://dali.chenlongwang.top/Article/details/gtyrpxmumu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.wangdashe.top/Article/details/gtphygfqam.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hfpthk.cn/Article/details/gtlycxksgj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gtxuqnrkpt.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj20258888.top/Article/details/gtomvdwnau.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yuxming.cn/Article/details/gttcmprfwo.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.guowangkeji.top/Article/details/gtedfcdovu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yanxiufei.cn/Article/details/gtqodlrkch.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.chenlongwang.top/Article/details/gtycnkfmga.html

[N05] 最大公约数
来源：http://dali.birdmap.top/Article/details/gtwssfoqbw.html

Py:   math.gcd(a, b)
来源：http://dali.hfpthk.cn/Article/details/gtgsldginc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cdnleiting.top/Article/details/gtjxkjvpkp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hywenlv.cn/Article/details/gtlzhqhmfh.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.haohaochexian.top/Article/details/gthajkoszg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.c1oappe.top/Article/details/gtibjxcvkw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.chenjidiqi.icu/Article/details/gtrxpdxuvf.html

Ruby: a.gcd(b)
来源：http://dali.birdmap.top/Article/details/gtluiezffc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shangyingyoupin.top/Article/details/gtcwuaxwbx.html

[N06] 判断回文字符串
来源：http://dali.cqqwz.cn/Article/details/gtaabpuvte.html

Py:   s == s[::-1]
来源：http://dali.zdqjudy.top/Article/details/gtwdynbmes.html

PHP:  $s === strrev($s);
来源：http://dali.tianlin.xyz/Article/details/gttsilniyo.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gtfrecnnnc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.fengsongda.top/Article/details/gtsuwvwaiv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yueranfly.top/Article/details/gttwmdmvsp.html

Go:   // 双指针从两端比较
来源：http://dali.cheryme.top/Article/details/gtctegifje.html

Ruby: s == s.reverse
来源：http://dali.xylfe.cn/Article/details/gtikqptlxq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ybcxt.top/Article/details/gtadlyhmlz.html

[N07] 两数之和（返回下标）
来源：http://dali.ehwqpu.com/Article/details/gtgewspsla.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.redwolf501.top/Article/details/gtbkqcokvy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj20258888.top/Article/details/gtaipvejsz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlpiwkhnt.html

TS:   // 手写 Map<string, number>
来源：http://dali.haohaochexian.top/Article/details/gtarilhatt.html

Java: // 手写 HashMap
来源：http://dali.smart0.xyz/Article/details/gtvcfsnmbf.html

Go:   // 手写 map[int]int
来源：http://dali.smart0.xyz/Article/details/gtaijtpxae.html

Ruby: // 手写 Hash
来源：http://dali.jlsjyb.cn/Article/details/gtrkbmpbod.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shangyingyoupin.top/Article/details/gtgkzovkcf.html

[N08] 生成全排列
来源：http://dali.hysaishi.cn/Article/details/gtncyicewt.html

Py:   itertools.permutations(arr)
来源：http://dali.yongpay.top/Article/details/gtzlogzywr.html

PHP:  // 手写递归交换
来源：http://dali.hfpthk.cn/Article/details/gtdpntozrn.html

JS:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gtamtoejpg.html

TS:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gtjolzslmk.html

Java: // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gtaxcfdhpa.html

Go:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gtpfmazvph.html

Ruby: arr.permutation.to_a
来源：http://dali.jlsjyb.cn/Article/details/gtfanxocac.html

C#:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gtjrdsvjkb.html

[N09] 栈与队列
来源：http://dali.svipenyu.cn/Article/details/gtjwdktcum.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtirfwayzz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xinyue.icu/Article/details/gtdoojyuyw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xziqi.cn/Article/details/gtoaxepmih.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.haohaochexian.top/Article/details/gtvvjudjxe.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.guannengcc.top/Article/details/gtfwjmtwda.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shangyingyoupin.top/Article/details/gtglvkcuol.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.tian-w.cn/Article/details/gthmexclsr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ybcxt.top/Article/details/gtewzapvok.html

[N10] 链表节点定义
来源：http://dali.jqgfzy.top/Article/details/gtnsjbigrh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xuanzx.com/Article/details/gtodrlimjb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.kuanghao11.cn/Article/details/gtprmnwzog.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.0kj1m.cn/Article/details/gtnjxmuvzd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gaohongyu789.top/Article/details/gtjcjkeyox.html

Java: class Node { int v; Node next; }
来源：http://dali.xuetiantiany.cn/Article/details/gtlpejzvhf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gaohongyu789.top/Article/details/gtbglobsau.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hongshengwenyu.top/Article/details/gtctbyhaqo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.daxiang520.top/Article/details/gtqwuiocbl.html

[N11] 二叉树中序遍历
来源：http://dali.hnxiangtu.top/Article/details/gtsscxrbmx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.dashuyun.cn/Article/details/gtfeqjznyg.html

PHP:  // 手写递归函数
来源：http://dali.wangshuangyany.cn/Article/details/gthvwzpynm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cdnleiting.top/Article/details/gtzsmjrenj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.0kj1m.cn/Article/details/gtsboeslgr.html

Java: // 手写递归
来源：http://dali.gzhubu.top/Article/details/gtqjoonigl.html


<!-- 参考信息 -->