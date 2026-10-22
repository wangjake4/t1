代发 wailian999

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.mhx1999.top/Article/details/gtnnujutry.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gtamwjlfmq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hongshengwenyu.top/Article/details/gtecxziwfx.html

Py:   pickle.dumps(obj)
来源：http://dali.c1oappe.top/Article/details/gtxulsndif.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.fzhhl.top/Article/details/gtqipbqiil.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hfpthk.cn/Article/details/gtedolwnwl.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jqgufenzy.top/Article/details/gtoagtabbz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhongyouzk.top/Article/details/gtvgxwnkze.html

Go:   encoding/gob
来源：http://dali.feifeiyinyue.top/Article/details/gtftdxowxs.html

Ruby: Marshal.dump(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtdkwpwvjq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.9152youxi.cn/Article/details/gtygffcjpm.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtzkbxdnal.html

L. 网络请求
来源：http://dali.jqgufenzy.top/Article/details/gtzbzyujgg.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gteqnjlhlg.html

[L01] 发送 GET 请求
来源：http://dali.cqqwz.cn/Article/details/gttmsvidus.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hongshengwenyu.top/Article/details/gtgolquysw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.aibaodan.cn/Article/details/gthuibfsuo.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gtpjrngajx.html

TS:   await fetch(url)
来源：http://dali.chenjidiqi.icu/Article/details/gtuglqyshu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yj202588.top/Article/details/gtziijovjv.html

Go:   resp, err := http.Get(url)
来源：http://dali.aizwys.cn/Article/details/gtwiwqjoks.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.dianchejie.cn/Article/details/gtpowgogbt.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.tian-w.cn/Article/details/gttjwavsqm.html

[L02] 发送 POST JSON
来源：http://dali.yvedp.cn/Article/details/gtuxyjqkao.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.andypj.xyz/Article/details/gtdmotlqsd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yuxming.cn/Article/details/gtjgjynkpl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.bjfxy.top/Article/details/gtgbtafnmn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangtech.top/Article/details/gttxfeosmp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yueranfly.top/Article/details/gttkkqzvku.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yanxiufei.cn/Article/details/gtjaoezpmv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shuidangran.top/Article/details/gtgsajcjom.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.aibaodan.cn/Article/details/gtuyystsve.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gtsyrqbbgy.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xinyue.icu/Article/details/gtullipsdt.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jqgufenzy.top/Article/details/gtancjkncv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cdnleiting.top/Article/details/gtapjyoxbz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gtrvtfqsei.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.nwbrower.top/Article/details/gthygulfim.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jiagoushi.top/Article/details/gtpstzwwfb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hywenlv.cn/Article/details/gtmqtyrwhl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jqgufenzy.top/Article/details/gtubkmihrz.html

[L04] 设置超时
来源：http://dali.jiagoushi.top/Article/details/gtfxrunblo.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yonumen.top/Article/details/gtilugzaly.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.wangdashe.top/Article/details/gtdcmbubrx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.0kj1m.cn/Article/details/gtycwmdopp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xylfe.cn/Article/details/gtshuqmcyo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.dashuyun.cn/Article/details/gtezgjabji.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.andypj.xyz/Article/details/gtvpnmeaox.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhixingplan.top/Article/details/gtjpiombqo.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jqgufenzy.top/Article/details/gtirunpfhh.html

[L05] 上传文件（multipart）
来源：http://dali.zhengqikj.top/Article/details/gtydsxyzlu.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jianghu66.top/Article/details/gtbrvfkuwl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.bjfxy.top/Article/details/gtwcnbcrai.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.0kj1m.cn/Article/details/gtbojhegna.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shzxlz.cn/Article/details/gtjflseoyf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xuanzx.com/Article/details/gtmdhplpjl.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shzxlz.cn/Article/details/gtjmlnxnlg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.316326.xyz/Article/details/gtcyunsvma.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtidhlwxye.html

[L06] 解析响应为 JSON
来源：http://dali.yueranfly.top/Article/details/gtpqqidpnw.html

Py:   resp.json()
来源：http://dali.sysykeji.top/Article/details/gtnvrzskrz.html

PHP:  json_decode($body, true);
来源：http://dali.jianghu66.top/Article/details/gteiapetmw.html

JS:   await resp.json()
来源：http://dali.316326.xyz/Article/details/gtdbdiagya.html

TS:   await resp.json()
来源：http://dali.sweek.top/Article/details/gttlpscuhn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhongyouzk.top/Article/details/gtqkmtpeou.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ydzc1.top/Article/details/gtjspqqrkz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yangfankeji.com/Article/details/gtzujygsfi.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.9152youxi.cn/Article/details/gtnfhcpyuj.html

[L07] 处理 HTTP 状态码
来源：http://dali.kuanghao11.cn/Article/details/gtzpthneft.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ivvv.top/Article/details/gtvgizyxdv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhoulong.xyz/Article/details/gtfkupabiv.html

JS:   resp.ok;  resp.status
来源：http://dali.ybcxt.top/Article/details/gtowsgmypv.html

TS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangkeji.top/Article/details/gtghakfvqe.html

Java: resp.statusCode()
来源：http://dali.yj202588.top/Article/details/gtqzcwvluq.html

Go:   resp.StatusCode
来源：http://dali.xuanzx.com/Article/details/gtzwycsmek.html

Ruby: resp.code.to_i
来源：http://dali.hongshengwenyu.top/Article/details/gtglqmtlix.html

C#:   (int)resp.StatusCode
来源：http://dali.mhx1999.top/Article/details/gtjqckpqri.html

[L08] 并发请求多个地址
来源：http://dali.chenzaomai.com/Article/details/gtjmbksexh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinqigfzy.top/Article/details/gtixnseorq.html

PHP:  curl_multi_init() 系列
来源：http://dali.yonumen.top/Article/details/gtlbcbleus.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gtvrmkdjtj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shangyingyoupin.top/Article/details/gtnqntwlpm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gtrnyszyer.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.smart0.xyz/Article/details/gtkdlxyhog.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gtkemayjov.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sweek.top/Article/details/gtehgddkow.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtfdaoxevv.html

M. 命令行 / 进程 / 环境
来源：http://dali.jqgfzy.top/Article/details/gtmnolggdy.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtqyoejjry.html

[M01] 读取命令行参数
来源：http://dali.andypj.xyz/Article/details/gtyosamwzf.html

Py:   sys.argv[1:]
来源：http://dali.cheryme.top/Article/details/gtfggbqrrb.html

PHP:  $argv;  $argc;
来源：http://dali.iojbl.cn/Article/details/gtgkodwwhl.html

JS:   process.argv.slice(2)
来源：http://dali.0kj1m.cn/Article/details/gtvhyqfoyb.html

TS:   process.argv.slice(2)
来源：http://dali.mhx1999.top/Article/details/gteexmlepi.html

Java: args 数组（main 方法参数）
来源：http://dali.snrcjt.cn/Article/details/gtyycbcwfc.html

Go:   os.Args[1:]
来源：http://dali.yanxiufei.cn/Article/details/gttqtptkww.html

Ruby: ARGV
来源：http://dali.ybcxt.top/Article/details/gtitfjpfxs.html

C#:   args 数组（Main 方法参数）
来源：http://dali.iojbl.cn/Article/details/gtkhhjhicg.html

[M02] 读取环境变量
来源：http://dali.kuanghao11.cn/Article/details/gtxkzudbhv.html

Py:   os.environ.get("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gtvxaenmun.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.havefunace.top/Article/details/gtznfwzgfn.html

JS:   process.env.HOME
来源：http://dali.redwolf501.top/Article/details/gtaevenwud.html

TS:   process.env.HOME
来源：http://dali.nanxuanxn.top/Article/details/gtyrqchsny.html

Java: System.getenv("HOME")
来源：http://dali.daxiang520.top/Article/details/gtgpzldxve.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gtvgastxix.html

Ruby: ENV["HOME"]
来源：http://dali.nwbrower.top/Article/details/gttrnhfmql.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj202588.top/Article/details/gttrpfxjkw.html

[M03] 执行外部命令
来源：http://dali.svipenyu.cn/Article/details/gtriqikdrs.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.daxiang520.top/Article/details/gtpfhieooh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.birdmap.top/Article/details/gtlutnfelj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnqzz.top/Article/details/gtrabxnpnn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.dashuyun.cn/Article/details/gtithjbycj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.bjfxy.top/Article/details/gtextqtitc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.guannengcc.top/Article/details/gtdcqpqrjn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.vqdsnc.cn/Article/details/gtaeiarzyy.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jqgfzy.top/Article/details/gtwnlnedpd.html

[M04] 获取当前工作目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrykccufo.html

Py:   os.getcwd()
来源：http://dali.tianlin.xyz/Article/details/gtzwvwtbjc.html

PHP:  getcwd();
来源：http://dali.yj202588.top/Article/details/gtpfggyrhh.html

JS:   process.cwd()
来源：http://dali.smart0.xyz/Article/details/gtorphydtv.html

TS:   process.cwd()
来源：http://dali.nwbrower.top/Article/details/gtkhhehpjc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.c1oappe.top/Article/details/gtyjdsrwdl.html

Go:   os.Getwd()
来源：http://dali.nanxuanxn.top/Article/details/gtkhhcdnda.html

Ruby: Dir.pwd
来源：http://dali.zhiwuduotai.top/Article/details/gtmdcgxpkh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.mhx1999.top/Article/details/gthnctytas.html

[M05] 设置退出码
来源：http://dali.zhixingplan.top/Article/details/gtdzjrbrai.html

Py:   sys.exit(1)
来源：http://dali.sxryk.cn/Article/details/gtfmjweavq.html

PHP:  exit(1);
来源：http://dali.chenlongwang.top/Article/details/gttcmomqmq.html

JS:   process.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtmdwwuoou.html

TS:   process.exit(1)
来源：http://dali.zycfv.cn/Article/details/gtgitgrcyp.html

Java: System.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtomxhwjme.html

Go:   os.Exit(1)
来源：http://dali.meibo888.top/Article/details/gtjekhovgx.html

Ruby: exit 1
来源：http://dali.guowangkeji.top/Article/details/gtxrrpapjp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ppjwa.cn/Article/details/gtottbwvwr.html

[M06] 向标准错误输出
来源：http://dali.dianchejie.cn/Article/details/gtqayzspzv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.fzhhl.top/Article/details/gtrozmwdmh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zdqjudy.top/Article/details/gteglfipwq.html

JS:   console.error("err")
来源：http://dali.xylfe.cn/Article/details/gtjfwhoctu.html

TS:   console.error("err")
来源：http://dali.cdnleiting.top/Article/details/gtuohdiufr.html

Java: System.err.println("err")
来源：http://dali.guannengcc.top/Article/details/gtdokjctyc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.guowangkeji.top/Article/details/gttzcklpuz.html

Ruby: warn "err"
来源：http://dali.xziqi.cn/Article/details/gtwgrrrrme.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sxryk.cn/Article/details/gtboooyehq.html

[M07] 判断是否为主入口
来源：http://dali.gzhubu.top/Article/details/gtpnwpuifi.html

Py:   if __name__ == "__main__":
来源：http://dali.shzxlz.cn/Article/details/gtotekjctg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jlsjyb.cn/Article/details/gtlpsyjekz.html

JS:   require.main === module
来源：http://dali.zhixingplan.top/Article/details/gtosbjmboe.html

TS:   require.main === module
来源：http://dali.zhongyouzk.top/Article/details/gtzyhbwqxe.html

Java: public static void main(String[] args)
来源：http://dali.chenlongwang.top/Article/details/gtfaylazlj.html

Go:   func main()
来源：http://dali.yuxming.cn/Article/details/gtclieyvvy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.fengsongda.top/Article/details/gtlkkguoef.html

C#:   static void Main(string[] args)
来源：http://dali.nwbrower.top/Article/details/gtaphrgvuq.html

[M08] 获取系统与运行时信息
来源：http://dali.guannengcc.top/Article/details/gtxphurzds.html

Py:   platform.system();  platform.python_version()
来源：http://dali.iojbl.cn/Article/details/gtsqwglinj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.smart0.xyz/Article/details/gtjysrukph.html

JS:   process.platform;  process.version
来源：http://dali.sufxvd.cn/Article/details/gthhezljnz.html

TS:   process.platform;  process.version
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjyzclxrl.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yueranfly.top/Article/details/gtvrzwyfuw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj202588.top/Article/details/gtsqjjcspc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cdnleiting.top/Article/details/gtfzgnxbza.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hfpthk.cn/Article/details/gtmteljofm.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtmaidrwyf.html

N. 数据结构与算法
来源：http://dali.gotoacloud.top/Article/details/gtumpniled.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtwuhltiwe.html

[N01] 二分查找（有序数组）
来源：http://dali.jlsjyb.cn/Article/details/gtcklpabij.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtrgtsdedt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.smart0.xyz/Article/details/gtjphzdegv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cdnleiting.top/Article/details/gtcdklluno.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jiagoushi.top/Article/details/gtiyluoqqp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.fzhhl.top/Article/details/gtyqdbkwkt.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cucudq.cn/Article/details/gttvvafouh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.iojbl.cn/Article/details/gtfmxwlrjp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gtdzjtutvg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yuanzhike.top/Article/details/gtikcpswle.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ehwqpu.com/Article/details/gtqhkjeupx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hongshengwenyu.top/Article/details/gtbmsbosie.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.9152youxi.cn/Article/details/gtgxheigee.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cqqwz.cn/Article/details/gtjcfdhxvx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yongpay.top/Article/details/gtnbeevzsa.html

Go:   slices.Sort(arr)
来源：http://dali.xylfe.cn/Article/details/gtdzkudahu.html

Ruby: arr.sort
来源：http://dali.hongshengwenyu.top/Article/details/gtvslsgxco.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.iojbl.cn/Article/details/gtgctioixi.html

[N03] 快速排序（分治示例）
来源：http://dali.mhx1999.top/Article/details/gtbuybtfpy.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jlsjyb.cn/Article/details/gtsawljacl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yuanzhike.top/Article/details/gtiidjloiv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guowangkeji.top/Article/details/gtxrjajthl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.vqdsnc.cn/Article/details/gtpcouooeo.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.meibo888.top/Article/details/gtjqhjwprr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sysykeji.top/Article/details/gtzuctqimz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sweek.top/Article/details/gtnaapzxhf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tianlin.xyz/Article/details/gtuwujsidd.html

[N04] 斐波那契数列
来源：http://dali.zycfv.cn/Article/details/gtyjflqapk.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sufxvd.cn/Article/details/gtvscoqgpx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yueranfly.top/Article/details/gtvjmzejhc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxqvnaaur.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ppjwa.cn/Article/details/gtzusdimax.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ydzc1.top/Article/details/gtqnucokqo.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.c1oappe.top/Article/details/gtwlttctmk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jianghu66.top/Article/details/gtisgekcym.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ybcxt.top/Article/details/gtgpgekmxp.html

[N05] 最大公约数
来源：http://dali.wangdashe.top/Article/details/gthukuimor.html

Py:   math.gcd(a, b)
来源：http://dali.zdqjudy.top/Article/details/gttvswzyzw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinqigufen.top/Article/details/gtfytrsxec.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj202588.top/Article/details/gtqkykngku.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.haohaochexian.top/Article/details/gtezvnzpyg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbscrtikk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.gogol.net.cn/Article/details/gtlcdvpvgv.html

Ruby: a.gcd(b)
来源：http://dali.hongshengwenyu.top/Article/details/gtbsolehmh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.guannengcc.top/Article/details/gtzddtkdsi.html

[N06] 判断回文字符串
来源：http://dali.zhixingplan.top/Article/details/gtenrxjsck.html

Py:   s == s[::-1]
来源：http://dali.sweek.top/Article/details/gtgxcfwyym.html

PHP:  $s === strrev($s);
来源：http://dali.jinqigfzy.top/Article/details/gtgvienidm.html

JS:   s === [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gtodmwukxb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtnwgaviro.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.andypj.xyz/Article/details/gtufdxjifj.html

Go:   // 双指针从两端比较
来源：http://dali.meibo888.top/Article/details/gtdutnqlmh.html

Ruby: s == s.reverse
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiglkjpfg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sweek.top/Article/details/gtocvotwbe.html

[N07] 两数之和（返回下标）
来源：http://dali.jlsjyb.cn/Article/details/gtaceolrql.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.chenzaomai.com/Article/details/gtmiovhbnp.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj20258.top/Article/details/gthlnwthzp.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sweek.top/Article/details/gtugplblng.html

TS:   // 手写 Map<string, number>
来源：http://dali.yanxiufei.cn/Article/details/gtrswfkgcq.html

Java: // 手写 HashMap
来源：http://dali.zycfv.cn/Article/details/gtwkzlmiwh.html

Go:   // 手写 map[int]int
来源：http://dali.daxiang520.top/Article/details/gtabkoiots.html

Ruby: // 手写 Hash
来源：http://dali.c1oappe.top/Article/details/gtsalzydrq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yj202588.top/Article/details/gtixevvzbq.html

[N08] 生成全排列
来源：http://dali.yuxming.cn/Article/details/gtlaifcqfr.html

Py:   itertools.permutations(arr)
来源：http://dali.shuidangran.top/Article/details/gtjfbtmuyd.html

PHP:  // 手写递归交换
来源：http://dali.pycfn.com/Article/details/gtwkizufoz.html

JS:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gtbyojvdmu.html

TS:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gthxfnirmm.html

Java: // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gtnfqnuhkh.html

Go:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gttzkxvfvr.html

Ruby: arr.permutation.to_a
来源：http://dali.jinqigfzy.top/Article/details/gtwhsmirud.html

C#:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gtwnorngfk.html

[N09] 栈与队列
来源：http://dali.hnxiangtu.top/Article/details/gtxdpdkclt.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.chenzaomai.com/Article/details/gtohrzhhou.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sxryk.cn/Article/details/gtxzpetveb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gtdelaotrh.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.andypj.xyz/Article/details/gtxdydtjww.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.tian-w.cn/Article/details/gtbyxbzmwk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yj20258888.top/Article/details/gtlqssefim.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.316326.xyz/Article/details/gtgngeuegd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sufxvd.cn/Article/details/gtuhkyfbio.html

[N10] 链表节点定义
来源：http://dali.meibo888.top/Article/details/gtnzprrkju.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinqigufen.top/Article/details/gtinuanblg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhixingplan.top/Article/details/gtoqcyqxqb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hnxiangtu.top/Article/details/gtwwgtoldw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.havefunace.top/Article/details/gtfdpbiwkx.html

Java: class Node { int v; Node next; }
来源：http://dali.tian-w.cn/Article/details/gtkkfdbgmj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.aizwys.cn/Article/details/gtflhfkwrw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.feifeiyinyue.top/Article/details/gtksukxppw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttddfdjaw.html

[N11] 二叉树中序遍历
来源：http://dali.daria6918.cn/Article/details/gtchhblplq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cucudq.cn/Article/details/gtxchfwqqt.html

PHP:  // 手写递归函数
来源：http://dali.aizwys.cn/Article/details/gtzyvwippa.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnxiangtu.top/Article/details/gtybqwszft.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guannengcc.top/Article/details/gtzeycpajr.html

Java: // 手写递归
来源：http://dali.gogol.net.cn/Article/details/gtffszzpdn.html

Go:   // 手写递归
来源：http://dali.jianghu66.top/Article/details/gtxyigfzbz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.wangshuangyany.cn/Article/details/gtzpjmnscp.html

C#:   // 手写递归
来源：http://dali.cheryme.top/Article/details/gtwducnhsy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.meibo888.top/Article/details/gtpenkngun.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ppjwa.cn/Article/details/gtgyymupvc.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinghuilouyu.cn/Article/details/gtzyorvkfd.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gaohongyu789.top/Article/details/gtdnjkptay.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gaohongyu789.top/Article/details/gtqdpecpqt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aibaodan.cn/Article/details/gtbkoleqbv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hnxiangtu.top/Article/details/gtfteutdcy.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.meibo888.top/Article/details/gtgfvlincq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.c1oappe.top/Article/details/gtwgwzxnmi.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtskjnprbw.html

O. 并发与异步
来源：http://dali.redwolf501.top/Article/details/gtbcihgebf.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtfvhqmhok.html

[O01] 启动一个线程
来源：http://dali.yongpay.top/Article/details/gtwjhrbask.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.316326.xyz/Article/details/gtloegitgv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hywenlv.cn/Article/details/gtcepmhfnt.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xuanzx.com/Article/details/gtiubcawdr.html

TS:   // 同 JS
来源：http://dali.xuetiantiany.cn/Article/details/gtuwrpedps.html

Java: new Thread(() -> f()).start()
来源：http://dali.hnqzz.top/Article/details/gtmszyiqik.html

Go:   go f()
来源：http://dali.yj20258.top/Article/details/gtgxdftqyc.html

Ruby: Thread.new { f }
来源：http://dali.zhiwuduotai.top/Article/details/gtgjpynpot.html

C#:   Task.Run(() => F());
来源：http://dali.shzxlz.cn/Article/details/gtoxyxyles.html

[O02] 使用线程池
来源：http://dali.zdqjudy.top/Article/details/gtgfnutnfj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.nwbrower.top/Article/details/gtgqmuuoah.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ehwqpu.com/Article/details/gtbcxreepg.html

JS:   // worker_threads 线程池
来源：http://dali.gaohongyu789.top/Article/details/gtoypmvwsd.html

TS:   // worker_threads 线程池
来源：http://dali.ybcxt.top/Article/details/gtjmhopprf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yangfankeji.com/Article/details/gtgfyvghlq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhoulong.xyz/Article/details/gtnlgctlar.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gogol.net.cn/Article/details/gtlfhephqt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.fzhhl.top/Article/details/gtnuekkiso.html

[O03] 加锁保护共享数据
来源：http://dali.jinghuilouyu.cn/Article/details/gtcyxecjon.html

Py:   with lock: shared += 1
来源：http://dali.redwolf501.top/Article/details/gtqzescpoh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jiagoushi.top/Article/details/gtuttyxtkj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.guowangkeji.top/Article/details/gtmfapfkfz.html

TS:   // 同 JS
来源：http://dali.chenlongwang.top/Article/details/gtrolzftmb.html

Java: synchronized (this) { shared++; }
来源：http://dali.yj20258.top/Article/details/gtvkniwsbq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jqgufenzy.top/Article/details/gtbzbmyqdz.html


<!-- 参考信息 -->