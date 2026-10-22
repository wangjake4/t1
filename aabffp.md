代发 wailian999

Py:   copy.deepcopy(obj)
来源：http://dali.jyoumei.cn/Article/details/gtiekzzejr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.tianlin.xyz/Article/details/gtukumdqzy.html

JS:   structuredClone(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtasbwpsft.html

TS:   structuredClone(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtzbxqbcon.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hfpthk.cn/Article/details/gtytlqreft.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.tanke756.top/Article/details/gtqjpabuxj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hammf.cn/Article/details/gtgeigkmbc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jianghu66.top/Article/details/gtszcjocgb.html

[K06] 解析 URL 查询串
来源：http://dali.cqqwz.cn/Article/details/gtdlfqmlui.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.chenlongwang.top/Article/details/gtuhlyukod.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xuanzx.com/Article/details/gtiermowxn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258888.top/Article/details/gtddbjxaec.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.quarkkingdee.top/Article/details/gttranaggc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.bjfxy.top/Article/details/gtztvddeev.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jyoumei.cn/Article/details/gtsjqfjfoe.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.aizwys.cn/Article/details/gtvfyemkuv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.fzhhl.top/Article/details/gtflntzayf.html

[K07] 进制转换
来源：http://dali.cheryme.top/Article/details/gtohofqlql.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gtvjrgstuy.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yuanzhike.top/Article/details/gtplzknejy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtmxrckjdn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gtcrnwdxap.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gtftzrqykk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jqgfzy.top/Article/details/gtrjyzkpey.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.dashuyun.cn/Article/details/gtqxwadurz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtmmupyetj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.guannengcc.top/Article/details/gtxerxxgwf.html

Py:   pickle.dumps(obj)
来源：http://dali.ivvv.top/Article/details/gtbihiadle.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cheryme.top/Article/details/gtnoinmjby.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.birdmap.top/Article/details/gtfbjuovuo.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gtllgnwenv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthtlilnea.html

Go:   encoding/gob
来源：http://dali.sufxvd.cn/Article/details/gtokplkcre.html

Ruby: Marshal.dump(obj)
来源：http://dali.yongpay.top/Article/details/gtxgycbtbe.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.feifeiyinyue.top/Article/details/gtihsazmjw.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtgqazcffp.html

L. 网络请求
来源：http://dali.yvedp.cn/Article/details/gtfesgsodc.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtagkjvymu.html

[L01] 发送 GET 请求
来源：http://dali.jinqigufen.top/Article/details/gtxhnzcgri.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj20258.top/Article/details/gtrdjlicei.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.fzhhl.top/Article/details/gtpbsxnyqh.html

JS:   await fetch(url)
来源：http://dali.xuanzx.com/Article/details/gtmjbiceay.html

TS:   await fetch(url)
来源：http://dali.vqdsnc.cn/Article/details/gtwyfmimfb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ybcxt.top/Article/details/gtbsyvvjhx.html

Go:   resp, err := http.Get(url)
来源：http://dali.yanxiufei.cn/Article/details/gtemuercdt.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ehwqpu.com/Article/details/gtxziiliqe.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sufxvd.cn/Article/details/gtphscffao.html

[L02] 发送 POST JSON
来源：http://dali.pengpengdd.cyou/Article/details/gtmtnlykgd.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.iojbl.cn/Article/details/gtjujziqua.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xziqi.cn/Article/details/gtcahfefaw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yonumen.top/Article/details/gtrkpyhmab.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.svipenyu.cn/Article/details/gtogkmflap.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yueranfly.top/Article/details/gtnfdditir.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yangfankeji.com/Article/details/gtwfdqinof.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hongshengwenyu.top/Article/details/gtqdmyznhj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gotoacloud.top/Article/details/gtjroqzlfi.html

[L03] 设置自定义请求头
来源：http://dali.cqqwz.cn/Article/details/gtezytlsqx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hammf.cn/Article/details/gthldthmbc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.wangshuangyany.cn/Article/details/gtsdiftqjo.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jiagoushi.top/Article/details/gtqrimdkgl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxuanxn.top/Article/details/gtmluittpn.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zdqjudy.top/Article/details/gtnnbjdodh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.c1oappe.top/Article/details/gttatjlxux.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yanxiufei.cn/Article/details/gtmjmnmjqg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.birdmap.top/Article/details/gtcnmrthbd.html

[L04] 设置超时
来源：http://dali.jqgufenzy.top/Article/details/gtgczcjaia.html

Py:   requests.get(url, timeout=5)
来源：http://dali.havefunace.top/Article/details/gtconnrmln.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.haohaochexian.top/Article/details/gtyhbvfjuu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daria6918.cn/Article/details/gtwyrwcyuh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shzxlz.cn/Article/details/gtgohpqnen.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yuanzhike.top/Article/details/gtukkocdby.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gogol.net.cn/Article/details/gtipoiikvj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.daxiang520.top/Article/details/gtnxdylhhb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jianghu66.top/Article/details/gtlkeylhtw.html

[L05] 上传文件（multipart）
来源：http://dali.hnxiangtu.top/Article/details/gtkxbockbq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.fengsongda.top/Article/details/gtbtafnvmj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zycfv.cn/Article/details/gtqtrzmqyk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.nwbrower.top/Article/details/gtkmajhavd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hammf.cn/Article/details/gtdkqygtst.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.vqdsnc.cn/Article/details/gtdrxsbjac.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sysykeji.top/Article/details/gtifolnovk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.quarkkingdee.top/Article/details/gtmwenhhcw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sxryk.cn/Article/details/gtgrkkwdna.html

[L06] 解析响应为 JSON
来源：http://dali.xuetiantiany.cn/Article/details/gtwyeigxqy.html

Py:   resp.json()
来源：http://dali.birdmap.top/Article/details/gttwzzhepj.html

PHP:  json_decode($body, true);
来源：http://dali.zhoulong.xyz/Article/details/gtkraeryhg.html

JS:   await resp.json()
来源：http://dali.yj20258.top/Article/details/gtndsgpmmq.html

TS:   await resp.json()
来源：http://dali.yongpay.top/Article/details/gtlexnrcal.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yonumen.top/Article/details/gtjabthcdh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cqqwz.cn/Article/details/gtogcykame.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ydzc1.top/Article/details/gtszvvueki.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinqigfzy.top/Article/details/gtsnllrabv.html

[L07] 处理 HTTP 状态码
来源：http://dali.aibaodan.cn/Article/details/gtyemvyexl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cucudq.cn/Article/details/gtgkvugbnz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.316326.xyz/Article/details/gttfoczsqh.html

JS:   resp.ok;  resp.status
来源：http://dali.sufxvd.cn/Article/details/gtahxqynye.html

TS:   resp.ok;  resp.status
来源：http://dali.birdmap.top/Article/details/gtvnojsedi.html

Java: resp.statusCode()
来源：http://dali.sysykeji.top/Article/details/gtgtmhyjin.html

Go:   resp.StatusCode
来源：http://dali.yongpay.top/Article/details/gtjhikcten.html

Ruby: resp.code.to_i
来源：http://dali.zhengqikj.top/Article/details/gtsagnooyj.html

C#:   (int)resp.StatusCode
来源：http://dali.yj202588.top/Article/details/gtxoufxckk.html

[L08] 并发请求多个地址
来源：http://dali.hywenlv.cn/Article/details/gtnwnpippy.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.fzhhl.top/Article/details/gtvgoomsxb.html

PHP:  curl_multi_init() 系列
来源：http://dali.shuidangran.top/Article/details/gtrwcknheu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cdnleiting.top/Article/details/gtmcxgzysv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gtuzclxyud.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.tian-w.cn/Article/details/gtxuudsvki.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.guowangkeji.top/Article/details/gtdlaxxgqo.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.wangshuangyany.cn/Article/details/gtahbvdjxa.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.redwolf501.top/Article/details/gtfuhtncko.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtdxirkcgr.html

M. 命令行 / 进程 / 环境
来源：http://dali.sysykeji.top/Article/details/gttjqwxegs.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtudlkwcvr.html

[M01] 读取命令行参数
来源：http://dali.chenlongwang.top/Article/details/gtemgeeyvl.html

Py:   sys.argv[1:]
来源：http://dali.pengpengdd.cyou/Article/details/gtzbvmthln.html

PHP:  $argv;  $argc;
来源：http://dali.birdmap.top/Article/details/gtskstcqrj.html

JS:   process.argv.slice(2)
来源：http://dali.9152youxi.cn/Article/details/gtffiehfux.html

TS:   process.argv.slice(2)
来源：http://dali.sweek.top/Article/details/gtepuabcra.html

Java: args 数组（main 方法参数）
来源：http://dali.feifeiyinyue.top/Article/details/gtmdqaiass.html

Go:   os.Args[1:]
来源：http://dali.shanyushiyangtech.top/Article/details/gtloutpouu.html

Ruby: ARGV
来源：http://dali.ehwqpu.com/Article/details/gtdfjhqwrr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shanyushiyangkeji.top/Article/details/gttmsbrtgn.html

[M02] 读取环境变量
来源：http://dali.svipenyu.cn/Article/details/gtlpfgukao.html

Py:   os.environ.get("HOME")
来源：http://dali.ydzc1.top/Article/details/gtkaogxfjs.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.vqdsnc.cn/Article/details/gtjnbjbbbc.html

JS:   process.env.HOME
来源：http://dali.wangdashe.top/Article/details/gtuhvtewdy.html

TS:   process.env.HOME
来源：http://dali.hysaishi.cn/Article/details/gtyzubzgev.html

Java: System.getenv("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gtjcdfscvk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yangfankeji.com/Article/details/gtxvnfaipc.html

Ruby: ENV["HOME"]
来源：http://dali.jianghu66.top/Article/details/gtieomcbnz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sxryk.cn/Article/details/gtzfqeesmd.html

[M03] 执行外部命令
来源：http://dali.redwolf501.top/Article/details/gtgbdvibfd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenlongwang.top/Article/details/gttkokgngc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zdqjudy.top/Article/details/gtkrnlwxov.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.bjfxy.top/Article/details/gtxffauord.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jiagoushi.top/Article/details/gtfnrowrch.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinqigufen.top/Article/details/gtfqplynuf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.wangshuangyany.cn/Article/details/gtuhkjztjz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jqgfzy.top/Article/details/gtspwivush.html

C#:   Process.Start("ls", "-l");
来源：http://dali.pengpengdd.cyou/Article/details/gtgygzbijb.html

[M04] 获取当前工作目录
来源：http://dali.sweek.top/Article/details/gtqfxvcjod.html

Py:   os.getcwd()
来源：http://dali.yangfankeji.com/Article/details/gtzeindwkz.html

PHP:  getcwd();
来源：http://dali.smart0.xyz/Article/details/gtzpnfitoz.html

JS:   process.cwd()
来源：http://dali.cashguo.top/Article/details/gtjkcipfrf.html

TS:   process.cwd()
来源：http://dali.feifeiyinyue.top/Article/details/gteqhguggy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.andypj.xyz/Article/details/gtlegcqotv.html

Go:   os.Getwd()
来源：http://dali.haohaochexian.top/Article/details/gtpbgydmis.html

Ruby: Dir.pwd
来源：http://dali.hysaishi.cn/Article/details/gtxmgmeogq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sxryk.cn/Article/details/gtabnjbmuy.html

[M05] 设置退出码
来源：http://dali.sufxvd.cn/Article/details/gthwimlnig.html

Py:   sys.exit(1)
来源：http://dali.sysykeji.top/Article/details/gtiuvhylyw.html

PHP:  exit(1);
来源：http://dali.shangyingyoupin.top/Article/details/gtdbtnagjv.html

JS:   process.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gttmtqopoi.html

TS:   process.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtcxeiulto.html

Java: System.exit(1)
来源：http://dali.fengsongda.top/Article/details/gtgjehjrrx.html

Go:   os.Exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjkkuouqo.html

Ruby: exit 1
来源：http://dali.zhiwuduotai.top/Article/details/gtinyjhgip.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.iojbl.cn/Article/details/gtviykadpu.html

[M06] 向标准错误输出
来源：http://dali.tianlin.xyz/Article/details/gtpwidooom.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhixingplan.top/Article/details/gtyldnjkno.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhixingplan.top/Article/details/gtbgknscuv.html

JS:   console.error("err")
来源：http://dali.feifeiyinyue.top/Article/details/gtqeemxlhz.html

TS:   console.error("err")
来源：http://dali.aizwys.cn/Article/details/gtthsdyhft.html

Java: System.err.println("err")
来源：http://dali.ppjwa.cn/Article/details/gtoarvjpou.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.quarkkingdee.top/Article/details/gtgcqotxel.html

Ruby: warn "err"
来源：http://dali.gaohongyu789.top/Article/details/gtovncxfna.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shangyingyoupin.top/Article/details/gtztfknqja.html

[M07] 判断是否为主入口
来源：http://dali.ywan-chungtsiang.top/Article/details/gtidjmsggr.html

Py:   if __name__ == "__main__":
来源：http://dali.birdmap.top/Article/details/gtiqlcidkc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfagyddxd.html

JS:   require.main === module
来源：http://dali.daxiang520.top/Article/details/gtqsbzmytr.html

TS:   require.main === module
来源：http://dali.yuanzhike.top/Article/details/gtkcukwohl.html

Java: public static void main(String[] args)
来源：http://dali.wangdashe.top/Article/details/gtqmcidsji.html

Go:   func main()
来源：http://dali.snrcjt.cn/Article/details/gtmqkhkjai.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.meibo888.top/Article/details/gtlwiqazbt.html

C#:   static void Main(string[] args)
来源：http://dali.yangfankeji.com/Article/details/gtrwrsbcda.html

[M08] 获取系统与运行时信息
来源：http://dali.chenlongwang.top/Article/details/gtzkpjmiad.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinghuilouyu.cn/Article/details/gtivptoyhb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gaohongyu789.top/Article/details/gtczkipqoc.html

JS:   process.platform;  process.version
来源：http://dali.cqqwz.cn/Article/details/gtknifsfrn.html

TS:   process.platform;  process.version
来源：http://dali.hammf.cn/Article/details/gtiuzwtemb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yonumen.top/Article/details/gthsgegfrk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.nwbrower.top/Article/details/gttxjptusp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.aizwys.cn/Article/details/gtwmyivpdc.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gtbtolehcr.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtnzhtrcoc.html

N. 数据结构与算法
来源：http://dali.gzhubu.top/Article/details/gtzeeifdss.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtkxkbqqzn.html

[N01] 二分查找（有序数组）
来源：http://dali.birdmap.top/Article/details/gtpwdgfmig.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtrzrdrhpm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shangyingyoupin.top/Article/details/gtgfpjsqqe.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cheryme.top/Article/details/gtsmezgqkm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhengqikj.top/Article/details/gtbgteveay.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yuxming.cn/Article/details/gtfdoluxrs.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtztzixpiu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtclxieiyx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtpowwlzmk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jiagoushi.top/Article/details/gtircibcvw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pycfn.com/Article/details/gteblecebz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jqgufenzy.top/Article/details/gtqtvuacsu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxinkj.top/Article/details/gtltcfcgch.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhixingplan.top/Article/details/gtjqnffzpk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthwbekgir.html

Go:   slices.Sort(arr)
来源：http://dali.havefunace.top/Article/details/gtcvwjxqgk.html

Ruby: arr.sort
来源：http://dali.smart0.xyz/Article/details/gtmehuoolc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yanxiufei.cn/Article/details/gtcpkgzvgj.html

[N03] 快速排序（分治示例）
来源：http://dali.chenlongwang.top/Article/details/gtouxjfshu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.chenjidiqi.icu/Article/details/gtozgkadya.html

PHP:  // 递归实现，或用 usort
来源：http://dali.kuanghao11.cn/Article/details/gtbdnsoxdm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ybcxt.top/Article/details/gtcaxfbiil.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sweek.top/Article/details/gtbojdzzkp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yuxming.cn/Article/details/gtjbyeokuv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkhzgujnd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cheryme.top/Article/details/gtbhaeikuz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.andypj.xyz/Article/details/gtezpmnisj.html

[N04] 斐波那契数列
来源：http://dali.shanyushiyangtech.top/Article/details/gtcmtassca.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jqgufenzy.top/Article/details/gttjyrekqd.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xuanzx.com/Article/details/gtftsklwtc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gtvfyucxyw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtitbtnmmp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.fengsongda.top/Article/details/gtmrxrntcy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.dianchejie.cn/Article/details/gttjuqaipp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtufafxlwh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zycfv.cn/Article/details/gttpwdxxdc.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gtzvcdwbez.html

Py:   math.gcd(a, b)
来源：http://dali.birdmap.top/Article/details/gtatikvuqg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdohynzxe.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zdqjudy.top/Article/details/gtwcoljkpa.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuetiantiany.cn/Article/details/gtvxfvmzvw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.dianchejie.cn/Article/details/gthwggcffk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.guowangkeji.top/Article/details/gtpahlbsbc.html

Ruby: a.gcd(b)
来源：http://dali.xylfe.cn/Article/details/gtwoyvphpg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shzxlz.cn/Article/details/gtltsatunn.html

[N06] 判断回文字符串
来源：http://dali.shuidangran.top/Article/details/gtmsiyizzf.html

Py:   s == s[::-1]
来源：http://dali.chenlongwang.top/Article/details/gtzqghonjp.html

PHP:  $s === strrev($s);
来源：http://dali.hfpthk.cn/Article/details/gthfpeehni.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gtjvkorwvq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gtojwqabmb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthqqkrjes.html

Go:   // 双指针从两端比较
来源：http://dali.andypj.xyz/Article/details/gtnqnkmpxv.html

Ruby: s == s.reverse
来源：http://dali.ivvv.top/Article/details/gtjeivudiu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hammf.cn/Article/details/gtmdadyyqi.html

[N07] 两数之和（返回下标）
来源：http://dali.zhiwuduotai.top/Article/details/gtqukwrojp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.0kj1m.cn/Article/details/gtxqplxnvi.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuseehmml.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.daxiang520.top/Article/details/gtamerpijk.html

TS:   // 手写 Map<string, number>
来源：http://dali.jianghu66.top/Article/details/gtngmiunfz.html

Java: // 手写 HashMap
来源：http://dali.chenlongwang.top/Article/details/gthyifjmzk.html

Go:   // 手写 map[int]int
来源：http://dali.hywenlv.cn/Article/details/gtuukfnzjl.html

Ruby: // 手写 Hash
来源：http://dali.chenjidiqi.icu/Article/details/gtuytwgtog.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhixingplan.top/Article/details/gtjebjoouy.html

[N08] 生成全排列
来源：http://dali.jinqigfzy.top/Article/details/gtzoophguz.html

Py:   itertools.permutations(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdlkhytzr.html

PHP:  // 手写递归交换
来源：http://dali.shangyingyoupin.top/Article/details/gtpvfxrmdy.html

JS:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjxkigwgr.html

TS:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gtrmifdkpp.html

Java: // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gtkscmgrlw.html

Go:   // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gtbkeqtqvd.html

Ruby: arr.permutation.to_a
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyloiwctg.html

C#:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gtrdkqihdw.html

[N09] 栈与队列
来源：http://dali.yongpay.top/Article/details/gtnrbheshy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yangfankeji.com/Article/details/gtjrtfoerc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.andypj.xyz/Article/details/gtmmqxbfjn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.fengsongda.top/Article/details/gtjiwiqito.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yueranfly.top/Article/details/gtfgpzxvef.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xuanzx.com/Article/details/gtzrwpnngz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sweek.top/Article/details/gtodeyvpxm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gtrfuhsegl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jlsjyb.cn/Article/details/gtkigepcvl.html

[N10] 链表节点定义
来源：http://dali.zhiwuduotai.top/Article/details/gtbyvmisrz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yvedp.cn/Article/details/gtpirpijrs.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cucudq.cn/Article/details/gtxyhfajmq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.c1oappe.top/Article/details/gtxkfmtnvs.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cheryme.top/Article/details/gtbemwxpbl.html

Java: class Node { int v; Node next; }
来源：http://dali.shzxlz.cn/Article/details/gtnrfxwraw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.andypj.xyz/Article/details/gtwjdlhoht.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.0kj1m.cn/Article/details/gtjvanfdch.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhiwuduotai.top/Article/details/gtnhcazjon.html

[N11] 二叉树中序遍历
来源：http://dali.nwbrower.top/Article/details/gtrwswfvos.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.pengpengdd.cyou/Article/details/gtsdfzcxic.html

PHP:  // 手写递归函数
来源：http://dali.ydzc1.top/Article/details/gtgskhgcpy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnxiangtu.top/Article/details/gtmswjvklr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.redwolf501.top/Article/details/gtitnvemxs.html

Java: // 手写递归
来源：http://dali.sufxvd.cn/Article/details/gtdbapkcok.html

Go:   // 手写递归
来源：http://dali.cucudq.cn/Article/details/gtlpzjmhsx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.aibaodan.cn/Article/details/gtqwqyzjsk.html

C#:   // 手写递归
来源：http://dali.sxryk.cn/Article/details/gtfzbxrgco.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jlsjyb.cn/Article/details/gtbnugpenw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.tanke756.top/Article/details/gtpzcornyn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hammf.cn/Article/details/gtmvxtdwla.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yangfankeji.com/Article/details/gtmfjkwyri.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sweek.top/Article/details/gtkqazwykd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ivvv.top/Article/details/gtcsscdxye.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xuetiantiany.cn/Article/details/gtxjqjcqwk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.wangdashe.top/Article/details/gtaclahtzm.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuetiantiany.cn/Article/details/gtlurtfflm.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gthmvnjnmf.html

O. 并发与异步
来源：http://dali.ehwqpu.com/Article/details/gtievwcqyv.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtnitfeyhp.html

[O01] 启动一个线程
来源：http://dali.mhx1999.top/Article/details/gtcfmueynz.html


<!-- 参考信息 -->