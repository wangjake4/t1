代发 wailian999

[K02] JSON 字符串转对象
来源：http://dali.daria6918.cn/Article/details/gtzesszyuv.html

Py:   json.loads(s)
来源：http://dali.ppjwa.cn/Article/details/gtugepkrbf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zdqjudy.top/Article/details/gttfbdsxuj.html

JS:   JSON.parse(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtrljrzomu.html

TS:   JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtsnopdybm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gtfvcoirix.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.quarkkingdee.top/Article/details/gtdnrpzqrq.html

Ruby: JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtmlumjooi.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gthlcoqlex.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yuxming.cn/Article/details/gtyhjxvljz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ybcxt.top/Article/details/gtjxqlvorl.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sweek.top/Article/details/gttcmglluc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gtrlqghxbz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.fzhhl.top/Article/details/gtcnncrsmu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.316326.xyz/Article/details/gtefftycij.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jianghu66.top/Article/details/gtnkigjoek.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shzxlz.cn/Article/details/gtpwufqbig.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwbysqxlx.html

[K04] 读取 JSON 文件
来源：http://dali.cqqwz.cn/Article/details/gteccjpcqw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.quarkkingdee.top/Article/details/gtulnrkpih.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jqgufenzy.top/Article/details/gthjtsdgfs.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zycfv.cn/Article/details/gtaykgwovs.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuxming.cn/Article/details/gtlxmmlsiv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.svipenyu.cn/Article/details/gtpjzvcunu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hammf.cn/Article/details/gtzrloumue.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sysykeji.top/Article/details/gtaatkucnc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxvagvehn.html

[K05] 深拷贝对象
来源：http://dali.gaohongyu789.top/Article/details/gtqbffewfv.html

Py:   copy.deepcopy(obj)
来源：http://dali.xziqi.cn/Article/details/gtvkiimxvc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.chenzaomai.com/Article/details/gtktjgogtl.html

JS:   structuredClone(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gthikzmidk.html

TS:   structuredClone(obj)
来源：http://dali.yvedp.cn/Article/details/gttohqgrnd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.tianlin.xyz/Article/details/gtstmqpptc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.pengpengdd.cyou/Article/details/gteqberwjj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cucudq.cn/Article/details/gtttfmncyr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yj20258.top/Article/details/gttitrsngk.html

[K06] 解析 URL 查询串
来源：http://dali.sxryk.cn/Article/details/gtraofcjma.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.wangshuangyany.cn/Article/details/gtdsourscy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.snrcjt.cn/Article/details/gtikxabbxe.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxuanxn.top/Article/details/gtksytxjsi.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.bjfxy.top/Article/details/gtyfrlbygu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhengqikj.top/Article/details/gtazrqvugp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenjidiqi.icu/Article/details/gtwtcinijy.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gtbjxlzdga.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shuidangran.top/Article/details/gtchpvseqw.html

[K07] 进制转换
来源：http://dali.yuanzhike.top/Article/details/gtxiilyzri.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ivvv.top/Article/details/gtyttuawvn.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gogol.net.cn/Article/details/gtfvdhciot.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gttlmkflmh.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gtmkwcdczn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gtigibvahp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.birdmap.top/Article/details/gtywqdhlge.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinqigfzy.top/Article/details/gtonfhiexf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtmhgdxprx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xylfe.cn/Article/details/gtmnvazlpy.html

Py:   pickle.dumps(obj)
来源：http://dali.cheryme.top/Article/details/gtxdbnhwhn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.havefunace.top/Article/details/gtjmcfaoss.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.tian-w.cn/Article/details/gtigowgedn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.birdmap.top/Article/details/gtjfspataq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenzaomai.com/Article/details/gtzdvzsuqs.html

Go:   encoding/gob
来源：http://dali.ppjwa.cn/Article/details/gtqwdvwmij.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinqigufen.top/Article/details/gtjwnzugiq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.pengpengdd.cyou/Article/details/gttkibrikz.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtsogaimxf.html

L. 网络请求
来源：http://dali.sysykeji.top/Article/details/gtlnlhkbwa.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtrvirhhzw.html

[L01] 发送 GET 请求
来源：http://dali.zhixingplan.top/Article/details/gtabztakpd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ivvv.top/Article/details/gtlcdvwdjy.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nanxuanxn.top/Article/details/gtewrygtsk.html

JS:   await fetch(url)
来源：http://dali.svipenyu.cn/Article/details/gtpkeemthk.html

TS:   await fetch(url)
来源：http://dali.nanxinkj.top/Article/details/gtfxgolwsx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hfpthk.cn/Article/details/gtwbxxaxbg.html

Go:   resp, err := http.Get(url)
来源：http://dali.ppjwa.cn/Article/details/gtwrqofirb.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sweek.top/Article/details/gteyspqohz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jiagoushi.top/Article/details/gtvfmxesyp.html

[L02] 发送 POST JSON
来源：http://dali.0kj1m.cn/Article/details/gtaeadmiuy.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhoulong.xyz/Article/details/gtsavrknvg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhengqikj.top/Article/details/gthkzytmjl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.smart0.xyz/Article/details/gtikhdznnj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daxiang520.top/Article/details/gtvovcrzcr.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shzxlz.cn/Article/details/gtxcdzprbr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sysykeji.top/Article/details/gtjbexzcmk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nwbrower.top/Article/details/gtvnergxbk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sysykeji.top/Article/details/gtjlfayfzh.html

[L03] 设置自定义请求头
来源：http://dali.jyoumei.cn/Article/details/gtqhvnqgeh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.andypj.xyz/Article/details/gtjebbzwco.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xziqi.cn/Article/details/gtedbcyoxd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sufxvd.cn/Article/details/gtuymcqyqx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ivvv.top/Article/details/gtopscesnt.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yj20258888.top/Article/details/gtrxptbrul.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jqgfzy.top/Article/details/gtzpjfvbxs.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jqgufenzy.top/Article/details/gtrfyqsbxo.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yj202588.top/Article/details/gtahepaimg.html

[L04] 设置超时
来源：http://dali.chenjidiqi.icu/Article/details/gthksrkncu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yanxiufei.cn/Article/details/gtafbinkdg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.tian-w.cn/Article/details/gtusukkdmm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkjwoqrxv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hongshengwenyu.top/Article/details/gtarvumzbm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcmiuovcb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jqgfzy.top/Article/details/gtsnkpalkc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hywenlv.cn/Article/details/gtglvfwuvj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yj20258.top/Article/details/gtylnxomui.html

[L05] 上传文件（multipart）
来源：http://dali.vqdsnc.cn/Article/details/gtbwrflwwq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xuanzx.com/Article/details/gtwuozhnom.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yanxiufei.cn/Article/details/gtrschzfco.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.havefunace.top/Article/details/gtmsybfcna.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xziqi.cn/Article/details/gtdjexaiyq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ivvv.top/Article/details/gthdipdddc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yuxming.cn/Article/details/gtipjpxfpw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yangfankeji.com/Article/details/gtdsqjeeeu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtibigjsap.html

[L06] 解析响应为 JSON
来源：http://dali.tian-w.cn/Article/details/gtifojxzho.html

Py:   resp.json()
来源：http://dali.cucudq.cn/Article/details/gtlamhknwm.html

PHP:  json_decode($body, true);
来源：http://dali.cashguo.top/Article/details/gtcixzlaqk.html

JS:   await resp.json()
来源：http://dali.feifeiyinyue.top/Article/details/gtxsokejfb.html

TS:   await resp.json()
来源：http://dali.jqgfzy.top/Article/details/gtifkwcury.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yangfankeji.com/Article/details/gtabduflfx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jianghu66.top/Article/details/gtzquyhgen.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gotoacloud.top/Article/details/gtirriqdkd.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nanxinkj.top/Article/details/gtawhvwftq.html

[L07] 处理 HTTP 状态码
来源：http://dali.quarkkingdee.top/Article/details/gtogownzqr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sweek.top/Article/details/gtwccycxix.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nanxinkj.top/Article/details/gtoepaqhya.html

JS:   resp.ok;  resp.status
来源：http://dali.jyoumei.cn/Article/details/gtsvfcnyxt.html

TS:   resp.ok;  resp.status
来源：http://dali.redwolf501.top/Article/details/gtxbxtmmwc.html

Java: resp.statusCode()
来源：http://dali.gogol.net.cn/Article/details/gtgbmvupnq.html

Go:   resp.StatusCode
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdnqgvlks.html

Ruby: resp.code.to_i
来源：http://dali.tian-w.cn/Article/details/gtucguwmok.html

C#:   (int)resp.StatusCode
来源：http://dali.fzhhl.top/Article/details/gtnvmgoynz.html

[L08] 并发请求多个地址
来源：http://dali.zhixingplan.top/Article/details/gtgivpxjrz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zycfv.cn/Article/details/gthicwiwav.html

PHP:  curl_multi_init() 系列
来源：http://dali.yueranfly.top/Article/details/gtvwlifsug.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ydzc1.top/Article/details/gtkhjrfrtu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtabgncwku.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jiagoushi.top/Article/details/gtszpzoefd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.tianlin.xyz/Article/details/gtyslfvkyt.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xinyue.icu/Article/details/gtfgtjdenl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinqigufen.top/Article/details/gtoxmzcdax.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtboeasoky.html

M. 命令行 / 进程 / 环境
来源：http://dali.sxryk.cn/Article/details/gtfufwnwll.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtmjetuesc.html

[M01] 读取命令行参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmiuayfms.html

Py:   sys.argv[1:]
来源：http://dali.yj20258888.top/Article/details/gtcoawxfgj.html

PHP:  $argv;  $argc;
来源：http://dali.ybcxt.top/Article/details/gtwtdthnvz.html

JS:   process.argv.slice(2)
来源：http://dali.yonumen.top/Article/details/gtefmuqisd.html

TS:   process.argv.slice(2)
来源：http://dali.birdmap.top/Article/details/gtdcqbuujm.html

Java: args 数组（main 方法参数）
来源：http://dali.yj20258.top/Article/details/gtvhumhflc.html

Go:   os.Args[1:]
来源：http://dali.yongpay.top/Article/details/gtjqbayomj.html

Ruby: ARGV
来源：http://dali.aizwys.cn/Article/details/gtgxbbpzmd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shangyingyoupin.top/Article/details/gtajsvvfat.html

[M02] 读取环境变量
来源：http://dali.jlsjyb.cn/Article/details/gtwcjucoop.html

Py:   os.environ.get("HOME")
来源：http://dali.tianlin.xyz/Article/details/gtvdujdswn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.pengpengdd.cyou/Article/details/gtgebnltiz.html

JS:   process.env.HOME
来源：http://dali.yj20258888.top/Article/details/gtovukenus.html

TS:   process.env.HOME
来源：http://dali.bjfxy.top/Article/details/gtcqputnwu.html

Java: System.getenv("HOME")
来源：http://dali.haohaochexian.top/Article/details/gtxqvstges.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.pycfn.com/Article/details/gtcdsedmbe.html

Ruby: ENV["HOME"]
来源：http://dali.dashuyun.cn/Article/details/gthoxfjtjd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gtwcgkpzed.html

[M03] 执行外部命令
来源：http://dali.sufxvd.cn/Article/details/gtuvzfeikp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.nanxinkj.top/Article/details/gthiuvcone.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yonumen.top/Article/details/gtwiosfamm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hongshengwenyu.top/Article/details/gtrqwoqqva.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.fzhhl.top/Article/details/gtrwouqzxi.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhiwuduotai.top/Article/details/gtorucnfkx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ivvv.top/Article/details/gtczmsckfa.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yonumen.top/Article/details/gtlagxzqau.html

C#:   Process.Start("ls", "-l");
来源：http://dali.chenzaomai.com/Article/details/gtxqxhkpqk.html

[M04] 获取当前工作目录
来源：http://dali.jqgufenzy.top/Article/details/gtnosnhpdl.html

Py:   os.getcwd()
来源：http://dali.yueranfly.top/Article/details/gtfvblcjmq.html

PHP:  getcwd();
来源：http://dali.snrcjt.cn/Article/details/gtnkxdchrp.html

JS:   process.cwd()
来源：http://dali.jlsjyb.cn/Article/details/gtftkozucf.html

TS:   process.cwd()
来源：http://dali.tian-w.cn/Article/details/gthimgupne.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhiwuduotai.top/Article/details/gtcxftrimc.html

Go:   os.Getwd()
来源：http://dali.chenzaomai.com/Article/details/gtqjyjsfma.html

Ruby: Dir.pwd
来源：http://dali.cdnleiting.top/Article/details/gtmgafneot.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.tanke756.top/Article/details/gttcvsczgt.html

[M05] 设置退出码
来源：http://dali.cashguo.top/Article/details/gtalreaoly.html

Py:   sys.exit(1)
来源：http://dali.nwbrower.top/Article/details/gtjoqggyrb.html

PHP:  exit(1);
来源：http://dali.zhongyouzk.top/Article/details/gtwgxspvlg.html

JS:   process.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmvxknzfw.html

TS:   process.exit(1)
来源：http://dali.gzhubu.top/Article/details/gtpdfdvjqm.html

Java: System.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gtbqevhepd.html

Go:   os.Exit(1)
来源：http://dali.xuanzx.com/Article/details/gtozluznpm.html

Ruby: exit 1
来源：http://dali.jinqigfzy.top/Article/details/gtmxnxuhil.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yonumen.top/Article/details/gtwgicotix.html

[M06] 向标准错误输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtohdemwyj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.daria6918.cn/Article/details/gtuzyqhzkp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sufxvd.cn/Article/details/gtyxqwiyhi.html

JS:   console.error("err")
来源：http://dali.vqdsnc.cn/Article/details/gtvpwpogwz.html

TS:   console.error("err")
来源：http://dali.mhx1999.top/Article/details/gtkejzpjcy.html

Java: System.err.println("err")
来源：http://dali.yuxming.cn/Article/details/gtjqtikhvg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.vqdsnc.cn/Article/details/gtwsvkastd.html

Ruby: warn "err"
来源：http://dali.zhiwuduotai.top/Article/details/gtvcaxrwax.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.wangdashe.top/Article/details/gtriwqygkw.html

[M07] 判断是否为主入口
来源：http://dali.hywenlv.cn/Article/details/gtyyqdifoe.html

Py:   if __name__ == "__main__":
来源：http://dali.guowangkeji.top/Article/details/gtjoadqtlu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.birdmap.top/Article/details/gtubxxetse.html

JS:   require.main === module
来源：http://dali.hongshengwenyu.top/Article/details/gtafmxaume.html

TS:   require.main === module
来源：http://dali.hongshengwenyu.top/Article/details/gtebkhdtpn.html

Java: public static void main(String[] args)
来源：http://dali.mhx1999.top/Article/details/gtdncddime.html

Go:   func main()
来源：http://dali.aizwys.cn/Article/details/gtntbpnsdm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ivvv.top/Article/details/gtbgwpzxml.html

C#:   static void Main(string[] args)
来源：http://dali.yj20258.top/Article/details/gtekfemxld.html

[M08] 获取系统与运行时信息
来源：http://dali.hywenlv.cn/Article/details/gtpwighlpx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj202588.top/Article/details/gtjchozzba.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jiagoushi.top/Article/details/gtomiqnkwm.html

JS:   process.platform;  process.version
来源：http://dali.pengpengdd.cyou/Article/details/gtupckcidf.html

TS:   process.platform;  process.version
来源：http://dali.yj20258.top/Article/details/gtysecodnv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.dashuyun.cn/Article/details/gtcovnmois.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhengqikj.top/Article/details/gtxmsuqrvn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yj20258.top/Article/details/gtamwabuss.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.meibo888.top/Article/details/gtefbykufm.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gthifnpxgp.html

N. 数据结构与算法
来源：http://dali.snrcjt.cn/Article/details/gtmzmpbcwk.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtvinptlax.html

[N01] 二分查找（有序数组）
来源：http://dali.yj20258.top/Article/details/gtsxuaabmk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtdtopqaxw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthvxegryi.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tian-w.cn/Article/details/gtjstafzrp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cheryme.top/Article/details/gtplkpwrks.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtvgghmhqp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtwtuzzodm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.birdmap.top/Article/details/gtmwvcnerl.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtnvgplihs.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.andypj.xyz/Article/details/gtwtrzkcft.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gogol.net.cn/Article/details/gtwbqpurgl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.chenzaomai.com/Article/details/gtbpiimjxc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zycfv.cn/Article/details/gtzkitnvge.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hywenlv.cn/Article/details/gtagfvemoc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.bjfxy.top/Article/details/gtzxwhbrod.html

Go:   slices.Sort(arr)
来源：http://dali.jiagoushi.top/Article/details/gtwhggrtcg.html

Ruby: arr.sort
来源：http://dali.yangfankeji.com/Article/details/gtcsgetrwc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jqgfzy.top/Article/details/gthtpshpkd.html

[N03] 快速排序（分治示例）
来源：http://dali.jianghu66.top/Article/details/gtmjfrbjvf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yvedp.cn/Article/details/gtlibwikrs.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjkdqiijc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hysaishi.cn/Article/details/gtojyrecjt.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuanzx.com/Article/details/gtiaptmhsb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.daria6918.cn/Article/details/gtupnewhly.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xziqi.cn/Article/details/gtgjbvkvkz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shanyushiyangtech.top/Article/details/gtjhmuoayv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yuanzhike.top/Article/details/gtumtfkisj.html

[N04] 斐波那契数列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttyqzodur.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtcqdtfaqm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ydzc1.top/Article/details/gtfopxonvo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.birdmap.top/Article/details/gtaiqvexpm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.snrcjt.cn/Article/details/gtcfixwgii.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.tian-w.cn/Article/details/gtgkqrxupj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.fzhhl.top/Article/details/gtuqtdcunl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gogol.net.cn/Article/details/gtaxoiucfm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nanxuanxn.top/Article/details/gtyeekmsdi.html

[N05] 最大公约数
来源：http://dali.ybcxt.top/Article/details/gtcczwnych.html

Py:   math.gcd(a, b)
来源：http://dali.yj202588.top/Article/details/gtqtkcqjwt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sysykeji.top/Article/details/gtcrtfuapw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.smart0.xyz/Article/details/gtoqrsokvr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daria6918.cn/Article/details/gtvjpkdgde.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yuanzhike.top/Article/details/gtreeguiki.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcehouuul.html

Ruby: a.gcd(b)
来源：http://dali.tian-w.cn/Article/details/gtpuhxvhhd.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hywenlv.cn/Article/details/gtwsqpjznj.html

[N06] 判断回文字符串
来源：http://dali.jqgfzy.top/Article/details/gttjeumaaz.html

Py:   s == s[::-1]
来源：http://dali.gogol.net.cn/Article/details/gtenbnwjnt.html

PHP:  $s === strrev($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtlvypgcav.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gtjsfexngk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ehwqpu.com/Article/details/gtzfvyeakh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.chenzaomai.com/Article/details/gtbjnootbp.html

Go:   // 双指针从两端比较
来源：http://dali.316326.xyz/Article/details/gtdcilgvec.html

Ruby: s == s.reverse
来源：http://dali.iojbl.cn/Article/details/gtnhnaqnwg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhongyouzk.top/Article/details/gtbwqtvypp.html

[N07] 两数之和（返回下标）
来源：http://dali.shuidangran.top/Article/details/gtihpmuokd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.nanxuanxn.top/Article/details/gtuotcxpnv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hongshengwenyu.top/Article/details/gtvniyelxg.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhengqikj.top/Article/details/gtkgkdtpku.html

TS:   // 手写 Map<string, number>
来源：http://dali.jianghu66.top/Article/details/gtbbqhyvkx.html

Java: // 手写 HashMap
来源：http://dali.0kj1m.cn/Article/details/gtwxogyemh.html

Go:   // 手写 map[int]int
来源：http://dali.cucudq.cn/Article/details/gtuwejmeaf.html

Ruby: // 手写 Hash
来源：http://dali.pycfn.com/Article/details/gtwbnsdvcs.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.wangdashe.top/Article/details/gtmsdnnkkq.html

[N08] 生成全排列
来源：http://dali.xziqi.cn/Article/details/gtqmviqxth.html

Py:   itertools.permutations(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtepcgiwmi.html

PHP:  // 手写递归交换
来源：http://dali.aizwys.cn/Article/details/gtdiwlplzj.html

JS:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gtkliwhpcm.html

TS:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gtpznwpoqq.html

Java: // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmiwkqpqx.html

Go:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gttvtmeely.html

Ruby: arr.permutation.to_a
来源：http://dali.yanxiufei.cn/Article/details/gtfbnwxmav.html

C#:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gtxzsdvikj.html

[N09] 栈与队列
来源：http://dali.vqdsnc.cn/Article/details/gtwmwptgos.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.0kj1m.cn/Article/details/gtkbyogqie.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gtvnpfdvzl.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.kuanghao11.cn/Article/details/gtfcraureg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.0kj1m.cn/Article/details/gtrkzztzpp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yuxming.cn/Article/details/gtamfjhvnr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.pycfn.com/Article/details/gtscfjejyd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ybcxt.top/Article/details/gtwzfdsewk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtixjbgpmp.html

[N10] 链表节点定义
来源：http://dali.hywenlv.cn/Article/details/gtxejmelaj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinqigufen.top/Article/details/gtmqhqmpik.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.svipenyu.cn/Article/details/gtlsdbuqmw.html


<!-- 参考信息 -->