代发 wailian999

[K06] 解析 URL 查询串
来源：http://dali.cdnleiting.top/Article/details/gthvsdophf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ehwqpu.com/Article/details/gtbirzdukc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrwtbzpft.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.fzhhl.top/Article/details/gtyjqvqwdx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gzhubu.top/Article/details/gtkyyhxozi.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shuidangran.top/Article/details/gtefyuexrc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.tian-w.cn/Article/details/gtyyqkdyyf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.birdmap.top/Article/details/gtgkgmdikp.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gtohcyupnj.html

[K07] 进制转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtilvjqyku.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtabsnjjky.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yj20258888.top/Article/details/gtydhmzjez.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtezrronqd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gtrgdrgbtd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gtwfluwjrq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.tian-w.cn/Article/details/gtjepjylso.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhoulong.xyz/Article/details/gtkentpgds.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gtauaglwtz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xziqi.cn/Article/details/gttrurkphh.html

Py:   pickle.dumps(obj)
来源：http://dali.pycfn.com/Article/details/gtyuciokot.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yangfankeji.com/Article/details/gtbuibhime.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yvedp.cn/Article/details/gtddnxhddm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jyoumei.cn/Article/details/gtsbvnivzv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ivvv.top/Article/details/gturwtvczg.html

Go:   encoding/gob
来源：http://dali.zhixingplan.top/Article/details/gtohkqkuon.html

Ruby: Marshal.dump(obj)
来源：http://dali.redwolf501.top/Article/details/gtxckmhasm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.vqdsnc.cn/Article/details/gtqjwrsjtw.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtniupenvs.html

L. 网络请求
来源：http://dali.cheryme.top/Article/details/gtmyofeoxq.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtiipjawge.html

[L01] 发送 GET 请求
来源：http://dali.jinqigufen.top/Article/details/gtayddcbpe.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.iojbl.cn/Article/details/gtztzzpufe.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ybcxt.top/Article/details/gtpwvquymj.html

JS:   await fetch(url)
来源：http://dali.redwolf501.top/Article/details/gtszolsxky.html

TS:   await fetch(url)
来源：http://dali.cheryme.top/Article/details/gtliiomlbb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hnxiangtu.top/Article/details/gtxikxdhka.html

Go:   resp, err := http.Get(url)
来源：http://dali.havefunace.top/Article/details/gtkrmslkru.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xylfe.cn/Article/details/gttnuhgysd.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hammf.cn/Article/details/gtkqmhqdae.html

[L02] 发送 POST JSON
来源：http://dali.cheryme.top/Article/details/gtungmhwjm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shuidangran.top/Article/details/gtlzplvspp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shanyushiyangtech.top/Article/details/gtxfgzgvxu.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.quarkkingdee.top/Article/details/gtreemthrw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangshuangyany.cn/Article/details/gtdxojeqto.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.0kj1m.cn/Article/details/gtizjrmkdu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xuanzx.com/Article/details/gtcpcssgiv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nwbrower.top/Article/details/gtmrfxvgxu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ppjwa.cn/Article/details/gtekanwlag.html

[L03] 设置自定义请求头
来源：http://dali.smart0.xyz/Article/details/gtrkknopjx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.pycfn.com/Article/details/gtdgftbrxv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj20258.top/Article/details/gtuxxjhdmb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.meibo888.top/Article/details/gtvcqyfjas.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenjidiqi.icu/Article/details/gtyexyltvz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sysykeji.top/Article/details/gtcmrdtmlh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yj202588.top/Article/details/gtmmckyskr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.quarkkingdee.top/Article/details/gtfpumndoc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xylfe.cn/Article/details/gthrxljyeg.html

[L04] 设置超时
来源：http://dali.tianlin.xyz/Article/details/gtwmetxgiw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yvedp.cn/Article/details/gtybzjycxy.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sxryk.cn/Article/details/gtnhlirwnj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yvedp.cn/Article/details/gtyfiahjbb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shangyingyoupin.top/Article/details/gtepfgjrnl.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hysaishi.cn/Article/details/gtgzetubqo.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ivvv.top/Article/details/gtqwockvni.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.feifeiyinyue.top/Article/details/gtevefelxe.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.svipenyu.cn/Article/details/gtrtulmvyj.html

[L05] 上传文件（multipart）
来源：http://dali.gaohongyu789.top/Article/details/gtbudovztp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.kuanghao11.cn/Article/details/gtpkrdaxya.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hywenlv.cn/Article/details/gtfixrhtew.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258888.top/Article/details/gtttesjbbn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxuanxn.top/Article/details/gtvxjphlpc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.guannengcc.top/Article/details/gtzasfzxyd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinqigfzy.top/Article/details/gteliglatk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinqigfzy.top/Article/details/gtwtbhdzes.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.meibo888.top/Article/details/gtzhvbxakt.html

[L06] 解析响应为 JSON
来源：http://dali.nwbrower.top/Article/details/gtdvokhpiy.html

Py:   resp.json()
来源：http://dali.wangshuangyany.cn/Article/details/gtakuibwip.html

PHP:  json_decode($body, true);
来源：http://dali.sysykeji.top/Article/details/gtqgxumwvb.html

JS:   await resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gtodkwrimi.html

TS:   await resp.json()
来源：http://dali.jianghu66.top/Article/details/gtloodzkuz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yonumen.top/Article/details/gtpgialpzm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yj202588.top/Article/details/gtsrxnkpsh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhixingplan.top/Article/details/gtjdnhrgqv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xinyue.icu/Article/details/gtoocvwfvr.html

[L07] 处理 HTTP 状态码
来源：http://dali.hywenlv.cn/Article/details/gtyqqkfpkm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xuanzx.com/Article/details/gttcglsmbz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shzxlz.cn/Article/details/gtrfqypeyq.html

JS:   resp.ok;  resp.status
来源：http://dali.xziqi.cn/Article/details/gtkfdoyydv.html

TS:   resp.ok;  resp.status
来源：http://dali.316326.xyz/Article/details/gtjvzzxyjr.html

Java: resp.statusCode()
来源：http://dali.hnqzz.top/Article/details/gtevfeultj.html

Go:   resp.StatusCode
来源：http://dali.0kj1m.cn/Article/details/gtpbvbcbkb.html

Ruby: resp.code.to_i
来源：http://dali.cashguo.top/Article/details/gtpqgiqpbv.html

C#:   (int)resp.StatusCode
来源：http://dali.hnxiangtu.top/Article/details/gtxzowtaml.html

[L08] 并发请求多个地址
来源：http://dali.haohaochexian.top/Article/details/gtjsvqrdla.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xziqi.cn/Article/details/gtateyfdbv.html

PHP:  curl_multi_init() 系列
来源：http://dali.daxiang520.top/Article/details/gthvyqklxj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gttasngdzh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zycfv.cn/Article/details/gtidorcvow.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.9152youxi.cn/Article/details/gtfbscujui.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ivvv.top/Article/details/gtmgapcapb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hnqzz.top/Article/details/gtfrbtibco.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.aibaodan.cn/Article/details/gtznygexsu.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtehqewhxz.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenzaomai.com/Article/details/gtpfilddrg.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtgtowuokr.html

[M01] 读取命令行参数
来源：http://dali.wangdashe.top/Article/details/gtehuwbsyw.html

Py:   sys.argv[1:]
来源：http://dali.sysykeji.top/Article/details/gtdgzscsfl.html

PHP:  $argv;  $argc;
来源：http://dali.zhoulong.xyz/Article/details/gtnwrjkwlq.html

JS:   process.argv.slice(2)
来源：http://dali.aibaodan.cn/Article/details/gteggkvmfa.html

TS:   process.argv.slice(2)
来源：http://dali.dashuyun.cn/Article/details/gtucfnfmjc.html

Java: args 数组（main 方法参数）
来源：http://dali.kuanghao11.cn/Article/details/gtdbaiyfcq.html

Go:   os.Args[1:]
来源：http://dali.daria6918.cn/Article/details/gtczdwsimt.html

Ruby: ARGV
来源：http://dali.ehwqpu.com/Article/details/gtcfcffvqe.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yuxming.cn/Article/details/gtsrfedlpf.html

[M02] 读取环境变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoiiqycqx.html

Py:   os.environ.get("HOME")
来源：http://dali.zycfv.cn/Article/details/gtlbebnpqw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.vqdsnc.cn/Article/details/gtxmxsvtki.html

JS:   process.env.HOME
来源：http://dali.ppjwa.cn/Article/details/gtsapfqldl.html

TS:   process.env.HOME
来源：http://dali.dashuyun.cn/Article/details/gtscnthynv.html

Java: System.getenv("HOME")
来源：http://dali.aizwys.cn/Article/details/gtupxinxim.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yvedp.cn/Article/details/gtziznkici.html

Ruby: ENV["HOME"]
来源：http://dali.fengsongda.top/Article/details/gtchsctdrh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gogol.net.cn/Article/details/gtogbdxsat.html

[M03] 执行外部命令
来源：http://dali.aibaodan.cn/Article/details/gtnoulyshc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbvfizwro.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.fzhhl.top/Article/details/gtkbfuuwcy.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.meibo888.top/Article/details/gtiwuahffp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.andypj.xyz/Article/details/gtvpqldnke.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xziqi.cn/Article/details/gtlqdeihdu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ivvv.top/Article/details/gttetcqxhj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yvedp.cn/Article/details/gtvfyyxjpo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.guowangkeji.top/Article/details/gtyykolfxf.html

[M04] 获取当前工作目录
来源：http://dali.bjfxy.top/Article/details/gtzwsoigjf.html

Py:   os.getcwd()
来源：http://dali.smart0.xyz/Article/details/gtnmedlqbi.html

PHP:  getcwd();
来源：http://dali.xuanzx.com/Article/details/gtrpunysmc.html

JS:   process.cwd()
来源：http://dali.zycfv.cn/Article/details/gtfmwwawxp.html

TS:   process.cwd()
来源：http://dali.guannengcc.top/Article/details/gtynfxugus.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.316326.xyz/Article/details/gtewctoras.html

Go:   os.Getwd()
来源：http://dali.yueranfly.top/Article/details/gtdxyzsxps.html

Ruby: Dir.pwd
来源：http://dali.iojbl.cn/Article/details/gthxsklfwo.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ivvv.top/Article/details/gtuculpypl.html

[M05] 设置退出码
来源：http://dali.andypj.xyz/Article/details/gtzvwjlnvd.html

Py:   sys.exit(1)
来源：http://dali.gzhubu.top/Article/details/gtbofnjxkx.html

PHP:  exit(1);
来源：http://dali.jianghu66.top/Article/details/gtckmdcrqq.html

JS:   process.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gtlayuafao.html

TS:   process.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gtfkxgyivz.html

Java: System.exit(1)
来源：http://dali.guannengcc.top/Article/details/gtjqesthuy.html

Go:   os.Exit(1)
来源：http://dali.yuxming.cn/Article/details/gtulkzjwvd.html

Ruby: exit 1
来源：http://dali.redwolf501.top/Article/details/gtfsbnewzj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.daxiang520.top/Article/details/gtuqyzyeff.html

[M06] 向标准错误输出
来源：http://dali.nanxinkj.top/Article/details/gtjslslmzb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmlqvvtpp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.9152youxi.cn/Article/details/gtpcnjrbgw.html

JS:   console.error("err")
来源：http://dali.jiagoushi.top/Article/details/gtajducxrq.html

TS:   console.error("err")
来源：http://dali.cashguo.top/Article/details/gtviezlymd.html

Java: System.err.println("err")
来源：http://dali.ydzc1.top/Article/details/gthslipoho.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuyoozyeb.html

Ruby: warn "err"
来源：http://dali.nanxinkj.top/Article/details/gtwmljhcqm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.fengsongda.top/Article/details/gtbjphnpkq.html

[M07] 判断是否为主入口
来源：http://dali.ydzc1.top/Article/details/gtihwvmebi.html

Py:   if __name__ == "__main__":
来源：http://dali.snrcjt.cn/Article/details/gtdnzadkdw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.nanxinkj.top/Article/details/gtdtwsewuk.html

JS:   require.main === module
来源：http://dali.hammf.cn/Article/details/gtqgaowqxa.html

TS:   require.main === module
来源：http://dali.gotoacloud.top/Article/details/gtdmiiirfd.html

Java: public static void main(String[] args)
来源：http://dali.zdqjudy.top/Article/details/gtdplltlio.html

Go:   func main()
来源：http://dali.yj202588.top/Article/details/gtgknvmqeo.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.aizwys.cn/Article/details/gtdqezgafs.html

C#:   static void Main(string[] args)
来源：http://dali.hammf.cn/Article/details/gthcxrjzpt.html

[M08] 获取系统与运行时信息
来源：http://dali.hnxiangtu.top/Article/details/gtdzqetjuh.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinqigfzy.top/Article/details/gtpwzhqhjb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.redwolf501.top/Article/details/gtcolrgdbo.html

JS:   process.platform;  process.version
来源：http://dali.zhiwuduotai.top/Article/details/gtmzqogspz.html

TS:   process.platform;  process.version
来源：http://dali.hywenlv.cn/Article/details/gtwhresqch.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinghuilouyu.cn/Article/details/gtyioyrmsz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrgfhflkd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jlsjyb.cn/Article/details/gtmcwvnoyk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hnqzz.top/Article/details/gtbrqunxma.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtiiaolokq.html

N. 数据结构与算法
来源：http://dali.feifeiyinyue.top/Article/details/gtfaapbkdj.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtvrsuynro.html

[N01] 二分查找（有序数组）
来源：http://dali.sxryk.cn/Article/details/gtnsepekcn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtedxojhup.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hysaishi.cn/Article/details/gtikehhvzw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.quarkkingdee.top/Article/details/gtlpejeotl.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258.top/Article/details/gtiajtlcya.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtmzrxniuq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtqmioangu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmauevnmi.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtqwdwqvvk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.guannengcc.top/Article/details/gthoipaqie.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pycfn.com/Article/details/gtonnpenxs.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.gogol.net.cn/Article/details/gticstgzmv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cheryme.top/Article/details/gtxdcofzyt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.mhx1999.top/Article/details/gtutabwivr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.316326.xyz/Article/details/gtccpjooca.html

Go:   slices.Sort(arr)
来源：http://dali.svipenyu.cn/Article/details/gtjosoeetz.html

Ruby: arr.sort
来源：http://dali.tianlin.xyz/Article/details/gttfdsliyt.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.aibaodan.cn/Article/details/gttdlbgifa.html

[N03] 快速排序（分治示例）
来源：http://dali.meibo888.top/Article/details/gtakfurlzk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.0kj1m.cn/Article/details/gticwailfo.html

PHP:  // 递归实现，或用 usort
来源：http://dali.dashuyun.cn/Article/details/gtrccnsjsj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgfzy.top/Article/details/gtaqrbndfx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuanzhike.top/Article/details/gtmnhpkdfx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jyoumei.cn/Article/details/gttmgxitiw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.pycfn.com/Article/details/gtyrzevlzt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtardwpqqm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.0kj1m.cn/Article/details/gtosankhxd.html

[N04] 斐波那契数列
来源：http://dali.svipenyu.cn/Article/details/gtlddhruke.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.redwolf501.top/Article/details/gtsvmbqshl.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj202588.top/Article/details/gtwabingvx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ydzc1.top/Article/details/gtjemzlqdb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnqzz.top/Article/details/gtrgkfnqrj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.smart0.xyz/Article/details/gtkegxubuk.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shuidangran.top/Article/details/gtljqtpbnh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.c1oappe.top/Article/details/gtstssgbdd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.smart0.xyz/Article/details/gtinrgkcac.html

[N05] 最大公约数
来源：http://dali.gogol.net.cn/Article/details/gtcxkgqxbb.html

Py:   math.gcd(a, b)
来源：http://dali.redwolf501.top/Article/details/gtktzmbdze.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ehwqpu.com/Article/details/gttdpdskdz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shzxlz.cn/Article/details/gtsgxjdnxz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yanxiufei.cn/Article/details/gtfcwubctl.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.daria6918.cn/Article/details/gtyjcptvlt.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.chenlongwang.top/Article/details/gtunjrofmq.html

Ruby: a.gcd(b)
来源：http://dali.mhx1999.top/Article/details/gtzqjxovyc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.vqdsnc.cn/Article/details/gtpufsoavl.html

[N06] 判断回文字符串
来源：http://dali.jyoumei.cn/Article/details/gtanjwcthy.html

Py:   s == s[::-1]
来源：http://dali.kuanghao11.cn/Article/details/gtbloojiqa.html

PHP:  $s === strrev($s);
来源：http://dali.xylfe.cn/Article/details/gtznepwhvp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gtezkvasko.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gtbppqcsdz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hnxiangtu.top/Article/details/gtcqrkqiyu.html

Go:   // 双指针从两端比较
来源：http://dali.pycfn.com/Article/details/gtotduidti.html

Ruby: s == s.reverse
来源：http://dali.jinqigufen.top/Article/details/gtaaxuuiba.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.meibo888.top/Article/details/gtbiyobixs.html

[N07] 两数之和（返回下标）
来源：http://dali.daxiang520.top/Article/details/gtyriexesc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sxryk.cn/Article/details/gtyidgkhua.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.c1oappe.top/Article/details/gtlwpctzbm.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hnxiangtu.top/Article/details/gtdeqklrjb.html

TS:   // 手写 Map<string, number>
来源：http://dali.9152youxi.cn/Article/details/gtcmaupqny.html

Java: // 手写 HashMap
来源：http://dali.xylfe.cn/Article/details/gtrbhilejk.html

Go:   // 手写 map[int]int
来源：http://dali.havefunace.top/Article/details/gtexyulxtp.html

Ruby: // 手写 Hash
来源：http://dali.yuxming.cn/Article/details/gtmvbialzm.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gaohongyu789.top/Article/details/gtravenbjk.html

[N08] 生成全排列
来源：http://dali.ppjwa.cn/Article/details/gtxbcxqfzb.html

Py:   itertools.permutations(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtmjpdxrqj.html

PHP:  // 手写递归交换
来源：http://dali.jinqigufen.top/Article/details/gtwgbxijqr.html

JS:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gtpwgmicif.html

TS:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gthrcembop.html

Java: // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gtgvfsbkoi.html

Go:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gtrriyqras.html

Ruby: arr.permutation.to_a
来源：http://dali.yj20258888.top/Article/details/gtanmqhdah.html

C#:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gtxsymdwbo.html

[N09] 栈与队列
来源：http://dali.tian-w.cn/Article/details/gtvjcerqxu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbqisrxjb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gtgnikvkef.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.daria6918.cn/Article/details/gtflxjuizb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shanyushiyangkeji.top/Article/details/gttwluegnh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hnqzz.top/Article/details/gtzryvwreh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sysykeji.top/Article/details/gtixzrvnuf.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yanxiufei.cn/Article/details/gtentbzlaf.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hysaishi.cn/Article/details/gtblyjzhwk.html

[N10] 链表节点定义
来源：http://dali.jlsjyb.cn/Article/details/gtbltnwmzi.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jlsjyb.cn/Article/details/gtyvjmsnvf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.iojbl.cn/Article/details/gtmzmkreqi.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xylfe.cn/Article/details/gtsdkyejla.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.daria6918.cn/Article/details/gtdgpkozhk.html

Java: class Node { int v; Node next; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqnptazsy.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jlsjyb.cn/Article/details/gtqtdptnpd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sufxvd.cn/Article/details/gtlfmznqik.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.nanxinkj.top/Article/details/gtwnzmzwqj.html

[N11] 二叉树中序遍历
来源：http://dali.sysykeji.top/Article/details/gtecekitwf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.316326.xyz/Article/details/gtgdqvwrrr.html

PHP:  // 手写递归函数
来源：http://dali.jianghu66.top/Article/details/gtsuvokzhi.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnxiangtu.top/Article/details/gtskpasntr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258.top/Article/details/gtcxvnoric.html

Java: // 手写递归
来源：http://dali.xuetiantiany.cn/Article/details/gtuymienhg.html

Go:   // 手写递归
来源：http://dali.zhongyouzk.top/Article/details/gtsuoqijfs.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jiagoushi.top/Article/details/gtdijlpjqe.html

C#:   // 手写递归
来源：http://dali.hnqzz.top/Article/details/gtgvvuibfb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.havefunace.top/Article/details/gtmqozytte.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.wangshuangyany.cn/Article/details/gtotdqbjvq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.wangshuangyany.cn/Article/details/gtebzyuyeg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.mhx1999.top/Article/details/gttguwwskn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hongshengwenyu.top/Article/details/gtjskhrctt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cqqwz.cn/Article/details/gtmwnaisyy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ivvv.top/Article/details/gtnkhfxiwd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jqgufenzy.top/Article/details/gtrawujbot.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nanxuanxn.top/Article/details/gtbvijrmee.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtydpcxrzb.html

O. 并发与异步
来源：http://dali.fzhhl.top/Article/details/gtkybfndiu.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttqcbuhhz.html

[O01] 启动一个线程
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaolikzyl.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhaomingkeji.xyz/Article/details/gttrvkxqnf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cucudq.cn/Article/details/gtcauxapfr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.c1oappe.top/Article/details/gtyaxqpkso.html

TS:   // 同 JS
来源：http://dali.jqgufenzy.top/Article/details/gtikplsucn.html

Java: new Thread(() -> f()).start()
来源：http://dali.yongpay.top/Article/details/gtbdwqoddq.html

Go:   go f()
来源：http://dali.smart0.xyz/Article/details/gttfsmsrdl.html

Ruby: Thread.new { f }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsfkbmmbr.html

C#:   Task.Run(() => F());
来源：http://dali.chenlongwang.top/Article/details/gtvrdufkkv.html


<!-- 参考信息 -->