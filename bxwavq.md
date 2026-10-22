代发 wailian999

L. 网络请求
来源：http://dali.fengsongda.top/Article/details/gtdxudbnpz.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtdgqigrdg.html

[L01] 发送 GET 请求
来源：http://dali.guannengcc.top/Article/details/gttwspyrbh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hysaishi.cn/Article/details/gtxsffjtfr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yongpay.top/Article/details/gtpscwijuu.html

JS:   await fetch(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgnqcrtdo.html

TS:   await fetch(url)
来源：http://dali.cashguo.top/Article/details/gtmtxcgsub.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jyoumei.cn/Article/details/gtefrnmxuv.html

Go:   resp, err := http.Get(url)
来源：http://dali.gaohongyu789.top/Article/details/gtiilhhmok.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwrmiybcj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.tian-w.cn/Article/details/gtcckqjdtg.html

[L02] 发送 POST JSON
来源：http://dali.shzxlz.cn/Article/details/gtxffjmsvy.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.aizwys.cn/Article/details/gtdbetlfzj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gogol.net.cn/Article/details/gtggtkrxvk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jyoumei.cn/Article/details/gtlgrlqghc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.smart0.xyz/Article/details/gtudpaikoc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yvedp.cn/Article/details/gthzuegcut.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hywenlv.cn/Article/details/gtiwpykwxp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yvedp.cn/Article/details/gtgdwdegyf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hysaishi.cn/Article/details/gtzgkzugvt.html

[L03] 设置自定义请求头
来源：http://dali.zhengqikj.top/Article/details/gtwyrjjusq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.daxiang520.top/Article/details/gtkdwqaqhf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.vqdsnc.cn/Article/details/gtbgxevrmw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigfzy.top/Article/details/gtrfgkpnfl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.andypj.xyz/Article/details/gtburyxpdo.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.tian-w.cn/Article/details/gtctomumpo.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cdnleiting.top/Article/details/gtldkjrizm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hnxiangtu.top/Article/details/gtuooqxzuj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinqigfzy.top/Article/details/gtfjsakoce.html

[L04] 设置超时
来源：http://dali.jinqigfzy.top/Article/details/gtwvlhoxfm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhongyouzk.top/Article/details/gtiqmisyev.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hysaishi.cn/Article/details/gtnyjlbsmf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cdnleiting.top/Article/details/gthmvhnvme.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jlsjyb.cn/Article/details/gtynhjztvb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.meibo888.top/Article/details/gtfcekohis.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.dianchejie.cn/Article/details/gtlkoxvyur.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sysykeji.top/Article/details/gtlivbclku.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hfpthk.cn/Article/details/gtqhkqyugi.html

[L05] 上传文件（multipart）
来源：http://dali.guannengcc.top/Article/details/gtksvwcggc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.daria6918.cn/Article/details/gtghpcbgdl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkafruxwa.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgufenzy.top/Article/details/gtfmspcehu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.guannengcc.top/Article/details/gtizenzbim.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.0kj1m.cn/Article/details/gtniybcblp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.9152youxi.cn/Article/details/gtuwltopvz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhiwuduotai.top/Article/details/gtdoaeqomv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtqoritoep.html

[L06] 解析响应为 JSON
来源：http://dali.guannengcc.top/Article/details/gtvaxnuxey.html

Py:   resp.json()
来源：http://dali.aizwys.cn/Article/details/gthswddbvh.html

PHP:  json_decode($body, true);
来源：http://dali.feifeiyinyue.top/Article/details/gtuwqtjzsh.html

JS:   await resp.json()
来源：http://dali.yongpay.top/Article/details/gtnpxsiofe.html

TS:   await resp.json()
来源：http://dali.yj202588.top/Article/details/gtylqblczl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhiwuduotai.top/Article/details/gtswfaucuu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xziqi.cn/Article/details/gtrxwglvjy.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yongpay.top/Article/details/gtpfiitwxc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zycfv.cn/Article/details/gtagesbsht.html

[L07] 处理 HTTP 状态码
来源：http://dali.hnxiangtu.top/Article/details/gtcgnqoxms.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nwbrower.top/Article/details/gtslgeoxux.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yvedp.cn/Article/details/gtwhpegaiz.html

JS:   resp.ok;  resp.status
来源：http://dali.sysykeji.top/Article/details/gtpfmtlvrv.html

TS:   resp.ok;  resp.status
来源：http://dali.ybcxt.top/Article/details/gtapbsfrww.html

Java: resp.statusCode()
来源：http://dali.gogol.net.cn/Article/details/gtbjtstajg.html

Go:   resp.StatusCode
来源：http://dali.jlsjyb.cn/Article/details/gtuvndxqmp.html

Ruby: resp.code.to_i
来源：http://dali.daxiang520.top/Article/details/gtqerqsdhe.html

C#:   (int)resp.StatusCode
来源：http://dali.pycfn.com/Article/details/gtegrjngse.html

[L08] 并发请求多个地址
来源：http://dali.jinghuilouyu.cn/Article/details/gtouijfdrn.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ydzc1.top/Article/details/gtfzhuyglj.html

PHP:  curl_multi_init() 系列
来源：http://dali.xuetiantiany.cn/Article/details/gtgfdxnfjq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zdqjudy.top/Article/details/gtgxteksqu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shuidangran.top/Article/details/gtmqtzinuy.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.pengpengdd.cyou/Article/details/gtbtljpqrf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jqgufenzy.top/Article/details/gtdpfkaezt.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jyoumei.cn/Article/details/gtokqgstlj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jiagoushi.top/Article/details/gtwgfbakoh.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtiemfzyvf.html

M. 命令行 / 进程 / 环境
来源：http://dali.cqqwz.cn/Article/details/gtniwzcgnd.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtpeyxtsxf.html

[M01] 读取命令行参数
来源：http://dali.nanxuanxn.top/Article/details/gtbvypgwdt.html

Py:   sys.argv[1:]
来源：http://dali.fengsongda.top/Article/details/gtsfefnueu.html

PHP:  $argv;  $argc;
来源：http://dali.cucudq.cn/Article/details/gtvemuogfd.html

JS:   process.argv.slice(2)
来源：http://dali.jqgfzy.top/Article/details/gtkfikhrnu.html

TS:   process.argv.slice(2)
来源：http://dali.nanxuanxn.top/Article/details/gtoastgmen.html

Java: args 数组（main 方法参数）
来源：http://dali.wangdashe.top/Article/details/gtuvjvdihd.html

Go:   os.Args[1:]
来源：http://dali.ydzc1.top/Article/details/gtspqyflrz.html

Ruby: ARGV
来源：http://dali.nwbrower.top/Article/details/gtqtvnddws.html

C#:   args 数组（Main 方法参数）
来源：http://dali.pycfn.com/Article/details/gtlizewjvs.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gtnjjveonv.html

Py:   os.environ.get("HOME")
来源：http://dali.yuxming.cn/Article/details/gtcaazulep.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xinyue.icu/Article/details/gtjkgwfvfu.html

JS:   process.env.HOME
来源：http://dali.dianchejie.cn/Article/details/gtxxsqeiek.html

TS:   process.env.HOME
来源：http://dali.yuxming.cn/Article/details/gtmmxsjtrr.html

Java: System.getenv("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gtfigyiatz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gtsptlmpru.html

Ruby: ENV["HOME"]
来源：http://dali.cqqwz.cn/Article/details/gtuneyndwa.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gthermbtne.html

[M03] 执行外部命令
来源：http://dali.sysykeji.top/Article/details/gtptwohhgp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.wangshuangyany.cn/Article/details/gtembzhzry.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj202588.top/Article/details/gtxhknpwxa.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ivvv.top/Article/details/gtbtjyhujl.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gzhubu.top/Article/details/gtencibrls.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.daxiang520.top/Article/details/gtgpgwszqi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.pycfn.com/Article/details/gtrckenvcl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.c1oappe.top/Article/details/gtnvjeckdq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.fengsongda.top/Article/details/gtutqmtbwb.html

[M04] 获取当前工作目录
来源：http://dali.yangfankeji.com/Article/details/gthtdhtpmx.html

Py:   os.getcwd()
来源：http://dali.ivvv.top/Article/details/gtyqmwzjqo.html

PHP:  getcwd();
来源：http://dali.c1oappe.top/Article/details/gtlpjyrbsg.html

JS:   process.cwd()
来源：http://dali.zhengqikj.top/Article/details/gtcyjkfoch.html

TS:   process.cwd()
来源：http://dali.tian-w.cn/Article/details/gtainhezgs.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jlsjyb.cn/Article/details/gtcixlcbqc.html

Go:   os.Getwd()
来源：http://dali.fzhhl.top/Article/details/gtkgyhqlbl.html

Ruby: Dir.pwd
来源：http://dali.jinqigfzy.top/Article/details/gtnfmkefsr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ivvv.top/Article/details/gtfcuduley.html

[M05] 设置退出码
来源：http://dali.dashuyun.cn/Article/details/gtixgakfvy.html

Py:   sys.exit(1)
来源：http://dali.yvedp.cn/Article/details/gtmayjuizj.html

PHP:  exit(1);
来源：http://dali.yanxiufei.cn/Article/details/gtwbdchjsg.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtpliqjbfz.html

TS:   process.exit(1)
来源：http://dali.xuanzx.com/Article/details/gtcyliuspf.html

Java: System.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gtpcvrqxnm.html

Go:   os.Exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtckldknuf.html

Ruby: exit 1
来源：http://dali.yuanzhike.top/Article/details/gtedbayxzo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.daria6918.cn/Article/details/gtdgxsoduj.html

[M06] 向标准错误输出
来源：http://dali.cucudq.cn/Article/details/gtevalzvjw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhengqikj.top/Article/details/gtobpsvmil.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.chenzaomai.com/Article/details/gtppervpek.html

JS:   console.error("err")
来源：http://dali.daria6918.cn/Article/details/gttypgwarr.html

TS:   console.error("err")
来源：http://dali.chenjidiqi.icu/Article/details/gtivqhhbie.html

Java: System.err.println("err")
来源：http://dali.jqgfzy.top/Article/details/gtzcippqei.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.9152youxi.cn/Article/details/gtjpfcostz.html

Ruby: warn "err"
来源：http://dali.c1oappe.top/Article/details/gtokzhurqf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yangfankeji.com/Article/details/gtaamysekn.html

[M07] 判断是否为主入口
来源：http://dali.birdmap.top/Article/details/gtxkxyvrjq.html

Py:   if __name__ == "__main__":
来源：http://dali.xuetiantiany.cn/Article/details/gtqdwezkvg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.aizwys.cn/Article/details/gtcwlgbmeu.html

JS:   require.main === module
来源：http://dali.xuetiantiany.cn/Article/details/gtkherumoa.html

TS:   require.main === module
来源：http://dali.chenlongwang.top/Article/details/gtmuawfwep.html

Java: public static void main(String[] args)
来源：http://dali.ivvv.top/Article/details/gtecvdecha.html

Go:   func main()
来源：http://dali.andypj.xyz/Article/details/gtcrkmlgex.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenlongwang.top/Article/details/gtajykoymm.html

C#:   static void Main(string[] args)
来源：http://dali.yanxiufei.cn/Article/details/gthewykqcz.html

[M08] 获取系统与运行时信息
来源：http://dali.ybcxt.top/Article/details/gtncjzywmb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.bjfxy.top/Article/details/gtonkhvmtv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jiagoushi.top/Article/details/gtpukxajnq.html

JS:   process.platform;  process.version
来源：http://dali.316326.xyz/Article/details/gtablnhpea.html

TS:   process.platform;  process.version
来源：http://dali.jqgufenzy.top/Article/details/gtvmpakbre.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xuanzx.com/Article/details/gtidmvldcy.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cheryme.top/Article/details/gtccfhyahc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xylfe.cn/Article/details/gtkmssumay.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sweek.top/Article/details/gtcbgngwqj.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtaloyrmae.html

N. 数据结构与算法
来源：http://dali.jlsjyb.cn/Article/details/gtrwjnarvz.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtvyppckaw.html

[N01] 二分查找（有序数组）
来源：http://dali.xuetiantiany.cn/Article/details/gtvdyedmfl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.iojbl.cn/Article/details/gtzhshydyb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.chenzaomai.com/Article/details/gtrcxizdmu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenzaomai.com/Article/details/gtmzxoloxm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tanke756.top/Article/details/gtzcfrkget.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtvcenwlcx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtmwjxznyr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpvfkhjdo.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.fzhhl.top/Article/details/gtegtvzhnm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xuanzx.com/Article/details/gtcqiegzlp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fengsongda.top/Article/details/gtwbtquhkl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sufxvd.cn/Article/details/gtoujjdprg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxuanxn.top/Article/details/gtnjuyhosq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dianchejie.cn/Article/details/gtrewlczox.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sxryk.cn/Article/details/gtppnxcaoc.html

Go:   slices.Sort(arr)
来源：http://dali.ydzc1.top/Article/details/gtvmsaidwi.html

Ruby: arr.sort
来源：http://dali.yvedp.cn/Article/details/gthdscrvqs.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.tian-w.cn/Article/details/gtpmqsdlck.html

[N03] 快速排序（分治示例）
来源：http://dali.jianghu66.top/Article/details/gtuevqgpgf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.snrcjt.cn/Article/details/gtpxcaunji.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hnxiangtu.top/Article/details/gtecajslak.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.haohaochexian.top/Article/details/gtcqkpvzvu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guannengcc.top/Article/details/gtfomcolif.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sxryk.cn/Article/details/gtbbguhxxt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hywenlv.cn/Article/details/gtmywheeqo.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yj20258.top/Article/details/gteviosjue.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.redwolf501.top/Article/details/gtvczbzkos.html

[N04] 斐波那契数列
来源：http://dali.pycfn.com/Article/details/gtbewktkog.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ivvv.top/Article/details/gtriawmpda.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.andypj.xyz/Article/details/gtyjhsulbf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtjdbiigqa.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.316326.xyz/Article/details/gtmtjtnsaz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.feifeiyinyue.top/Article/details/gtsxvkcybl.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.meibo888.top/Article/details/gttwgynowl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhengqikj.top/Article/details/gtruclnqog.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shzxlz.cn/Article/details/gtqxyoknaj.html

[N05] 最大公约数
来源：http://dali.hnqzz.top/Article/details/gtvlenannc.html

Py:   math.gcd(a, b)
来源：http://dali.9152youxi.cn/Article/details/gtfxwejkev.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yvedp.cn/Article/details/gtmsdaeadx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nwbrower.top/Article/details/gtpvxgcjid.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hywenlv.cn/Article/details/gtblgjlxyb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.chenlongwang.top/Article/details/gtpnbwfcke.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yj20258.top/Article/details/gtoppgxzxv.html

Ruby: a.gcd(b)
来源：http://dali.aibaodan.cn/Article/details/gthjuspqfu.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.birdmap.top/Article/details/gtmxwqogcz.html

[N06] 判断回文字符串
来源：http://dali.guowangkeji.top/Article/details/gtpfvwsyxl.html

Py:   s == s[::-1]
来源：http://dali.hfpthk.cn/Article/details/gtzmnbjneb.html

PHP:  $s === strrev($s);
来源：http://dali.daria6918.cn/Article/details/gtaqrslybv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtpzmbfnkg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gtpsktpmzo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.aizwys.cn/Article/details/gtchjqfful.html

Go:   // 双指针从两端比较
来源：http://dali.gotoacloud.top/Article/details/gtatfsqpva.html

Ruby: s == s.reverse
来源：http://dali.zycfv.cn/Article/details/gtqquobjkd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jqgfzy.top/Article/details/gtxoervkei.html

[N07] 两数之和（返回下标）
来源：http://dali.xinyue.icu/Article/details/gtcbmzsopv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shzxlz.cn/Article/details/gtyrxmmlfv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.316326.xyz/Article/details/gtzctuodmu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yuanzhike.top/Article/details/gtkxggbhhk.html

TS:   // 手写 Map<string, number>
来源：http://dali.yongpay.top/Article/details/gtqbcozlmz.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gtauwexocd.html

Go:   // 手写 map[int]int
来源：http://dali.xuetiantiany.cn/Article/details/gtbcegecdw.html

Ruby: // 手写 Hash
来源：http://dali.chenlongwang.top/Article/details/gtyfqpvbet.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.vqdsnc.cn/Article/details/gtodzwoyns.html

[N08] 生成全排列
来源：http://dali.shzxlz.cn/Article/details/gtmhfzdwwg.html

Py:   itertools.permutations(arr)
来源：http://dali.sysykeji.top/Article/details/gtlfgwywoi.html

PHP:  // 手写递归交换
来源：http://dali.ydzc1.top/Article/details/gtmlthpikb.html

JS:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiwebites.html

TS:   // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gtsslpuehx.html

Java: // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtyqsbcssj.html

Go:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtrgaffmys.html

Ruby: arr.permutation.to_a
来源：http://dali.cqqwz.cn/Article/details/gtppfyeeoi.html

C#:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gthtynanyg.html

[N09] 栈与队列
来源：http://dali.sysykeji.top/Article/details/gtsabgtiqd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.aizwys.cn/Article/details/gthtzsrzqj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cucudq.cn/Article/details/gtyouelxlj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yj20258.top/Article/details/gterdntmpi.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hnqzz.top/Article/details/gtsdvnfsfv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yonumen.top/Article/details/gtfjwykmxo.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xuanzx.com/Article/details/gtntaatpqb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hnqzz.top/Article/details/gtzietulwk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xziqi.cn/Article/details/gtfbwmprnh.html

[N10] 链表节点定义
来源：http://dali.svipenyu.cn/Article/details/gtaqumfzsc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jianghu66.top/Article/details/gtjojjsvtu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xziqi.cn/Article/details/gtfbhlbuak.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sysykeji.top/Article/details/gttrkdikmk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ehwqpu.com/Article/details/gtgxiywaxq.html

Java: class Node { int v; Node next; }
来源：http://dali.tianlin.xyz/Article/details/gtxguefdrr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.mhx1999.top/Article/details/gthikjuvtz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jinqigufen.top/Article/details/gtwnsvqrgg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.daxiang520.top/Article/details/gtstmjygtw.html

[N11] 二叉树中序遍历
来源：http://dali.tianlin.xyz/Article/details/gtiljuoihb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ydzc1.top/Article/details/gtfxaytbvz.html

PHP:  // 手写递归函数
来源：http://dali.sysykeji.top/Article/details/gtgbjrdlzz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhiwuduotai.top/Article/details/gtfipaaixl.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zycfv.cn/Article/details/gthhcvbvex.html

Java: // 手写递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoxtokwaa.html

Go:   // 手写递归
来源：http://dali.zycfv.cn/Article/details/gtzqhahsoq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yvedp.cn/Article/details/gtelcquhjr.html

C#:   // 手写递归
来源：http://dali.cashguo.top/Article/details/gtxxiqoknc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yj20258888.top/Article/details/gtxxonthas.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.birdmap.top/Article/details/gtfcaqcjjl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jlsjyb.cn/Article/details/gtaheapldj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.havefunace.top/Article/details/gtxbefherh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhoulong.xyz/Article/details/gtdaezpxgc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gogol.net.cn/Article/details/gtngafeywx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yuxming.cn/Article/details/gtogxbmvko.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjpvemwci.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zdqjudy.top/Article/details/gtpsfadxnz.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtkitpqvjp.html

O. 并发与异步
来源：http://dali.bjfxy.top/Article/details/gtncvkjbtw.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtzlyrcbue.html

[O01] 启动一个线程
来源：http://dali.zhongyouzk.top/Article/details/gtzlhloyqb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gotoacloud.top/Article/details/gtozqavvrs.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.aizwys.cn/Article/details/gtymthdxjv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cqqwz.cn/Article/details/gtphfxvvnm.html

TS:   // 同 JS
来源：http://dali.zhengqikj.top/Article/details/gtasdemfem.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinqigufen.top/Article/details/gttwthgjbk.html

Go:   go f()
来源：http://dali.vqdsnc.cn/Article/details/gtaicopohq.html

Ruby: Thread.new { f }
来源：http://dali.gzhubu.top/Article/details/gtghriwupb.html

C#:   Task.Run(() => F());
来源：http://dali.nanxuanxn.top/Article/details/gtmlbcixhg.html

[O02] 使用线程池
来源：http://dali.daria6918.cn/Article/details/gtosblxuga.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.meibo888.top/Article/details/gtuqttyevj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yongpay.top/Article/details/gtmlogwddy.html

JS:   // worker_threads 线程池
来源：http://dali.shangyingyoupin.top/Article/details/gtjrrezktm.html

TS:   // worker_threads 线程池
来源：http://dali.xuetiantiany.cn/Article/details/gtzujzwhku.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjcaetspy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shzxlz.cn/Article/details/gtxldrnuyz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.dianchejie.cn/Article/details/gtohrvtvqs.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.svipenyu.cn/Article/details/gtpfpfchca.html

[O03] 加锁保护共享数据
来源：http://dali.havefunace.top/Article/details/gteyldbtue.html

Py:   with lock: shared += 1
来源：http://dali.wangdashe.top/Article/details/gtfgqtdcxa.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.nanxuanxn.top/Article/details/gtdtkdndza.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yj202588.top/Article/details/gtvokfercs.html

TS:   // 同 JS
来源：http://dali.ywan-chungtsiang.top/Article/details/gtluocubib.html

Java: synchronized (this) { shared++; }
来源：http://dali.cdnleiting.top/Article/details/gtgyhjgnpe.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.meibo888.top/Article/details/gtsknxnwhv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gotoacloud.top/Article/details/gtcmclkbkb.html

C#:   lock (gate) { shared++; }
来源：http://dali.fengsongda.top/Article/details/gthogxyyyy.html

[O04] 定义异步函数并等待
来源：http://dali.pycfn.com/Article/details/gthzecwalv.html

Py:   async def f():⏎    await g()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdurwjfnn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cqqwz.cn/Article/details/gtnzlkjlxf.html

JS:   async function f() { await g(); }
来源：http://dali.tanke756.top/Article/details/gtszbkzjij.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zycfv.cn/Article/details/gtzxmqpkkk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdrjbvzjr.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaifgyath.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hongshengwenyu.top/Article/details/gtfpvmrmmf.html

C#:   async Task F() { await G(); }
来源：http://dali.shangyingyoupin.top/Article/details/gttqjsayil.html

[O05] 并发执行并等待全部完成
来源：http://dali.cheryme.top/Article/details/gtvgaxwmjl.html


<!-- 参考信息 -->