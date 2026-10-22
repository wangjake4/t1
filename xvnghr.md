代发 wailian999

Go:   resp, err := http.Get(url)
来源：http://dali.aizwys.cn/Article/details/gt2jkxuykqr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yangfankeji.com/Article/details/gt2somlkjat.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.pycfn.com/Article/details/gt2veyybcfx.html

[L02] 发送 POST JSON
来源：http://dali.smart0.xyz/Article/details/gt2avlypqzc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.redwolf501.top/Article/details/gt2hbzteega.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jlsjyb.cn/Article/details/gt2tpuzbwem.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnqzz.top/Article/details/gt2flfgscdd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.svipenyu.cn/Article/details/gt2kwnlickq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xziqi.cn/Article/details/gt2gxzuxrfr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.tanke756.top/Article/details/gt2gpgkekvj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.mhx1999.top/Article/details/gt2edqvgsfe.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2wllvfvgn.html

[L03] 设置自定义请求头
来源：http://dali.yueranfly.top/Article/details/gt2qbljlaqa.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2icnnapfu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.smart0.xyz/Article/details/gt2mysqfygw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.feifeiyinyue.top/Article/details/gt2zgcgotqe.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangshuangyany.cn/Article/details/gt2zaqqmbve.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.fzhhl.top/Article/details/gt2mokpfeyg.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hysaishi.cn/Article/details/gt2ljalhztq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nwbrower.top/Article/details/gt2ledywrri.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jyoumei.cn/Article/details/gt2uypcgabl.html

[L04] 设置超时
来源：http://dali.zhoulong.xyz/Article/details/gt2uwaeapxx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cashguo.top/Article/details/gt2rdacygrh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.dianchejie.cn/Article/details/gt2tlezigff.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hysaishi.cn/Article/details/gt2cxmzzlkd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zycfv.cn/Article/details/gt2ojzdidav.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.guannengcc.top/Article/details/gt2irhxqkqs.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.c1oappe.top/Article/details/gt2erlmdoyk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nanxuanxn.top/Article/details/gt2eswzillv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yueranfly.top/Article/details/gt2iultyggn.html

[L05] 上传文件（multipart）
来源：http://dali.cqqwz.cn/Article/details/gt2qllvauwq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vdbqjusg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jqgufenzy.top/Article/details/gt2txhvvixk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ybcxt.top/Article/details/gt2hnjshirn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ivvv.top/Article/details/gt2tlfasbdr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hfpthk.cn/Article/details/gt2rebbzpwb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ehwqpu.com/Article/details/gt2sjoapfdb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sxryk.cn/Article/details/gt2tftqpdfa.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2dglseame.html

[L06] 解析响应为 JSON
来源：http://dali.svipenyu.cn/Article/details/gt2gxlbdtkn.html

Py:   resp.json()
来源：http://dali.yj202588.top/Article/details/gt2cttvadst.html

PHP:  json_decode($body, true);
来源：http://dali.hammf.cn/Article/details/gt2cpftyzns.html

JS:   await resp.json()
来源：http://dali.svipenyu.cn/Article/details/gt2qtzjbecs.html

TS:   await resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gt2ofncxfqw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj202588.top/Article/details/gt2fyxhpcdf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.gaohongyu789.top/Article/details/gt2zitngvsv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.meibo888.top/Article/details/gt2vlydmsex.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhongyouzk.top/Article/details/gt2lmmuiwmm.html

[L07] 处理 HTTP 状态码
来源：http://dali.jiagoushi.top/Article/details/gt2hnsycdhg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj20258888.top/Article/details/gt2qqjjgicb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zdqjudy.top/Article/details/gt2dixvlfnr.html

JS:   resp.ok;  resp.status
来源：http://dali.zhongyouzk.top/Article/details/gt2bvtpqkxo.html

TS:   resp.ok;  resp.status
来源：http://dali.hnqzz.top/Article/details/gt2jytweajs.html

Java: resp.statusCode()
来源：http://dali.svipenyu.cn/Article/details/gt2zjphwbya.html

Go:   resp.StatusCode
来源：http://dali.vqdsnc.cn/Article/details/gt2alwgihcv.html

Ruby: resp.code.to_i
来源：http://dali.hnxiangtu.top/Article/details/gt2uendyrts.html

C#:   (int)resp.StatusCode
来源：http://dali.aibaodan.cn/Article/details/gt2ptcqwzuf.html

[L08] 并发请求多个地址
来源：http://dali.jiagoushi.top/Article/details/gt2sljjcaii.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.andypj.xyz/Article/details/gt2bpynwybz.html

PHP:  curl_multi_init() 系列
来源：http://dali.dianchejie.cn/Article/details/gt2rffmeexn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.kuanghao11.cn/Article/details/gt2mmymnuoj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fbiymsew.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhixingplan.top/Article/details/gt2cbvpndlr.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.chenjidiqi.icu/Article/details/gt2hofdbacm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinqigufen.top/Article/details/gt2wfjdqacw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj20258888.top/Article/details/gt2qoybwyxp.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2jiixvwsp.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenlongwang.top/Article/details/gt2wmbfrexm.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ofqutjez.html

[M01] 读取命令行参数
来源：http://dali.andypj.xyz/Article/details/gt2yxzijefv.html

Py:   sys.argv[1:]
来源：http://dali.iojbl.cn/Article/details/gt2tgzhicsa.html

PHP:  $argv;  $argc;
来源：http://dali.yonumen.top/Article/details/gt2itofskll.html

JS:   process.argv.slice(2)
来源：http://dali.kuanghao11.cn/Article/details/gt2eudpjbxc.html

TS:   process.argv.slice(2)
来源：http://dali.jianghu66.top/Article/details/gt2ulkpkear.html

Java: args 数组（main 方法参数）
来源：http://dali.andypj.xyz/Article/details/gt2egyumvgu.html

Go:   os.Args[1:]
来源：http://dali.gaohongyu789.top/Article/details/gt2quhwvpyl.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbiyzjf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.dashuyun.cn/Article/details/gt2labbkbem.html

[M02] 读取环境变量
来源：http://dali.havefunace.top/Article/details/gt2soehigit.html

Py:   os.environ.get("HOME")
来源：http://dali.nanxinkj.top/Article/details/gt2vqfakocv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nanxuanxn.top/Article/details/gt2juzzpram.html

JS:   process.env.HOME
来源：http://dali.yj20258888.top/Article/details/gt2igfldbap.html

TS:   process.env.HOME
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lzxiwuku.html

Java: System.getenv("HOME")
来源：http://dali.jiagoushi.top/Article/details/gt2dlxcutoc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.smart0.xyz/Article/details/gt2tcsxgvle.html

Ruby: ENV["HOME"]
来源：http://dali.hysaishi.cn/Article/details/gt2vbshtytv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gzhubu.top/Article/details/gt2jqhiufvj.html

[M03] 执行外部命令
来源：http://dali.xylfe.cn/Article/details/gt2bfnkhhel.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhengqikj.top/Article/details/gt2jizqxtai.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yonumen.top/Article/details/gt2zkskfgbz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zdqjudy.top/Article/details/gt2dogbobtg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxmcdnk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yvedp.cn/Article/details/gt2dcxkcugh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.aibaodan.cn/Article/details/gt2yqkfnlew.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.guowangkeji.top/Article/details/gt2avkzjdlc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sxryk.cn/Article/details/gt2dpfrennm.html

[M04] 获取当前工作目录
来源：http://dali.shuidangran.top/Article/details/gt2wxfqsitp.html

Py:   os.getcwd()
来源：http://dali.guannengcc.top/Article/details/gt2uvnwowln.html

PHP:  getcwd();
来源：http://dali.shuidangran.top/Article/details/gt2rvbuhknd.html

JS:   process.cwd()
来源：http://dali.xuanzx.com/Article/details/gt2lncihgxo.html

TS:   process.cwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mzuwqmgw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.iojbl.cn/Article/details/gt2llrqkeor.html

Go:   os.Getwd()
来源：http://dali.birdmap.top/Article/details/gt2ltcwvjeg.html

Ruby: Dir.pwd
来源：http://dali.zhixingplan.top/Article/details/gt2syabzhww.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.fengsongda.top/Article/details/gt2jrhjqxyk.html

[M05] 设置退出码
来源：http://dali.shanyushiyangtech.top/Article/details/gt2joiibpcy.html

Py:   sys.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mjejaygf.html

PHP:  exit(1);
来源：http://dali.jiagoushi.top/Article/details/gt2pcfuqcqc.html

JS:   process.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gt2fsstatzc.html

TS:   process.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gt2ufinayab.html

Java: System.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gt2qgpioeyp.html

Go:   os.Exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2fbvypbpg.html

Ruby: exit 1
来源：http://dali.pengpengdd.cyou/Article/details/gt2vaundpde.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.andypj.xyz/Article/details/gt2qezfxgui.html

[M06] 向标准错误输出
来源：http://dali.chenzaomai.com/Article/details/gt2ggflatox.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gpartlch.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.pycfn.com/Article/details/gt2omebbffi.html

JS:   console.error("err")
来源：http://dali.zhoulong.xyz/Article/details/gt2jnmcsduu.html

TS:   console.error("err")
来源：http://dali.cqqwz.cn/Article/details/gt2mlhqwxie.html

Java: System.err.println("err")
来源：http://dali.birdmap.top/Article/details/gt2qynqzsjs.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.pengpengdd.cyou/Article/details/gt2acqwvknf.html

Ruby: warn "err"
来源：http://dali.yj202588.top/Article/details/gt2kyscinrd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhiwuduotai.top/Article/details/gt2sxhwdnhc.html

[M07] 判断是否为主入口
来源：http://dali.yuxming.cn/Article/details/gt2wcgjgwto.html

Py:   if __name__ == "__main__":
来源：http://dali.fengsongda.top/Article/details/gt2dkyizxji.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.tanke756.top/Article/details/gt2omxrpjdb.html

JS:   require.main === module
来源：http://dali.sysykeji.top/Article/details/gt2vvxluyjj.html

TS:   require.main === module
来源：http://dali.tian-w.cn/Article/details/gt2doiztbim.html

Java: public static void main(String[] args)
来源：http://dali.jianghu66.top/Article/details/gt2lrhsnpzi.html

Go:   func main()
来源：http://dali.xylfe.cn/Article/details/gt2tqwfwmtz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.pycfn.com/Article/details/gt2snpftwix.html

C#:   static void Main(string[] args)
来源：http://dali.sufxvd.cn/Article/details/gt2rdpprkbv.html

[M08] 获取系统与运行时信息
来源：http://dali.fzhhl.top/Article/details/gt2oggnirpi.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jqgfzy.top/Article/details/gt2agwjsvse.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhixingplan.top/Article/details/gt2axurrodd.html

JS:   process.platform;  process.version
来源：http://dali.jinqigufen.top/Article/details/gt2lbcaxqkf.html

TS:   process.platform;  process.version
来源：http://dali.jinghuilouyu.cn/Article/details/gt2thgtohyy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cashguo.top/Article/details/gt2hoordrdf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sufxvd.cn/Article/details/gt2hzjfseni.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ydzc1.top/Article/details/gt2mtlgfxhb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.smart0.xyz/Article/details/gt2rgroqwrf.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2ykxmsyri.html

N. 数据结构与算法
来源：http://dali.havefunace.top/Article/details/gt2zqecsvbi.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2rsjbfcjs.html

[N01] 二分查找（有序数组）
来源：http://dali.jlsjyb.cn/Article/details/gt2bjhlbyhe.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zbjrcubw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ydzc1.top/Article/details/gt2pivaeskm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxinkj.top/Article/details/gt2qpmplsji.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nwbrower.top/Article/details/gt2afabdrjz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gt2hwaqtvgz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.iojbl.cn/Article/details/gt2wkkalelb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhiwuduotai.top/Article/details/gt2pfjqcjqe.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gt2nkeybviz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinqigfzy.top/Article/details/gt2npnbnhvu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhiwuduotai.top/Article/details/gt2paweefhy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2subdxmue.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yonumen.top/Article/details/gt2hbzzjchf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.9152youxi.cn/Article/details/gt2cpnovzax.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.havefunace.top/Article/details/gt2yhdnpxdb.html

Go:   slices.Sort(arr)
来源：http://dali.haohaochexian.top/Article/details/gt2abtyidig.html

Ruby: arr.sort
来源：http://dali.0kj1m.cn/Article/details/gt2ntnxfgyk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.pycfn.com/Article/details/gt2onptkqin.html

[N03] 快速排序（分治示例）
来源：http://dali.gzhubu.top/Article/details/gt2dcvhpiee.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gzhubu.top/Article/details/gt2zfikhcme.html

PHP:  // 递归实现，或用 usort
来源：http://dali.aibaodan.cn/Article/details/gt2oiyeafcg.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuxming.cn/Article/details/gt2reuzbqav.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cashguo.top/Article/details/gt2cqcbspvr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2lddobwcn.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cheryme.top/Article/details/gt2pfugrxni.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.chenjidiqi.icu/Article/details/gt2rnqtcpuz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ivvv.top/Article/details/gt2vrqnihji.html

[N04] 斐波那契数列
来源：http://dali.ivvv.top/Article/details/gt2pbcvjmat.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2ulqvghok.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yangfankeji.com/Article/details/gt2vnvahaqg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daxiang520.top/Article/details/gt2sidbzfmk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.iojbl.cn/Article/details/gt2hyvjpcwz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cqqwz.cn/Article/details/gt2uzutxcny.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hongshengwenyu.top/Article/details/gt2zpriwcbr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ydzc1.top/Article/details/gt2bfnxyrto.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj20258.top/Article/details/gt2cktwxxfm.html

[N05] 最大公约数
来源：http://dali.dashuyun.cn/Article/details/gt2lngignzx.html

Py:   math.gcd(a, b)
来源：http://dali.nwbrower.top/Article/details/gt2szuttwrg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sxryk.cn/Article/details/gt2zggcczhg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenzaomai.com/Article/details/gt2akdnvefi.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.mhx1999.top/Article/details/gt2tutsiyxg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yueranfly.top/Article/details/gt2yiyyvgba.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zvtndtxy.html

Ruby: a.gcd(b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2btszngzt.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.nanxuanxn.top/Article/details/gt2qyfdevis.html

[N06] 判断回文字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2kucmzgro.html

Py:   s == s[::-1]
来源：http://dali.cheryme.top/Article/details/gt2wuazkyuv.html

PHP:  $s === strrev($s);
来源：http://dali.wangdashe.top/Article/details/gt2nbjozedh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ycjftmbf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gt2upsjlgrq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2juyfrqtl.html

Go:   // 双指针从两端比较
来源：http://dali.ehwqpu.com/Article/details/gt2upekvycv.html

Ruby: s == s.reverse
来源：http://dali.0kj1m.cn/Article/details/gt2skbzjbut.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shangyingyoupin.top/Article/details/gt2bxobljwp.html

[N07] 两数之和（返回下标）
来源：http://dali.9152youxi.cn/Article/details/gt2ksuhmshm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhongyouzk.top/Article/details/gt2yvgusnxz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.daria6918.cn/Article/details/gt2rdmwwcdt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.haohaochexian.top/Article/details/gt2usyjeqzk.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhengqikj.top/Article/details/gt2oapmzzjo.html

Java: // 手写 HashMap
来源：http://dali.yanxiufei.cn/Article/details/gt2rdiedtre.html

Go:   // 手写 map[int]int
来源：http://dali.shanyushiyangtech.top/Article/details/gt2imrijqha.html

Ruby: // 手写 Hash
来源：http://dali.nanxuanxn.top/Article/details/gt2cznbfwut.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shangyingyoupin.top/Article/details/gt2whfdhawz.html

[N08] 生成全排列
来源：http://dali.hywenlv.cn/Article/details/gt2urmryeyc.html

Py:   itertools.permutations(arr)
来源：http://dali.bjfxy.top/Article/details/gt2pepeybvn.html

PHP:  // 手写递归交换
来源：http://dali.havefunace.top/Article/details/gt2zmsgfvcd.html

JS:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gt2nrwjmnmm.html

TS:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ehetypkd.html

Java: // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gt2bgdlrosu.html

Go:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gt2oxajghpa.html

Ruby: arr.permutation.to_a
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zpdqpojb.html

C#:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gt2ljxtnpyn.html

[N09] 栈与队列
来源：http://dali.yongpay.top/Article/details/gt2nazuqgdx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hfpthk.cn/Article/details/gt2zjddymrv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gt2ooyxwfae.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.svipenyu.cn/Article/details/gt2abiwezfs.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cucudq.cn/Article/details/gt2uhmxqisk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.havefunace.top/Article/details/gt2cpdjpnaw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.nwbrower.top/Article/details/gt2isaijcjk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yongpay.top/Article/details/gt2ptxcbzer.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yanxiufei.cn/Article/details/gt2nkjzyejq.html

[N10] 链表节点定义
来源：http://dali.gzhubu.top/Article/details/gt2szvbmlbn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yangfankeji.com/Article/details/gt2igbxmuii.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.aibaodan.cn/Article/details/gt2epxerclc.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.meibo888.top/Article/details/gt2zmzhembt.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shuidangran.top/Article/details/gt2pblgfhgi.html

Java: class Node { int v; Node next; }
来源：http://dali.aizwys.cn/Article/details/gt2mtkovfer.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yanxiufei.cn/Article/details/gt2xzfgxovi.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mvetblky.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cxepxjoa.html

[N11] 二叉树中序遍历
来源：http://dali.zycfv.cn/Article/details/gt2moeuafvj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yuxming.cn/Article/details/gt2xwueifww.html

PHP:  // 手写递归函数
来源：http://dali.gogol.net.cn/Article/details/gt2zcytklzm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnxiangtu.top/Article/details/gt2acntdgkr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yangfankeji.com/Article/details/gt2scajbbvb.html

Java: // 手写递归
来源：http://dali.nanxinkj.top/Article/details/gt2ufhhjbfm.html

Go:   // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gt2tqbhqkaw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shzxlz.cn/Article/details/gt2axroxjbb.html

C#:   // 手写递归
来源：http://dali.aizwys.cn/Article/details/gt2scttdidi.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhixingplan.top/Article/details/gt2hkqbeojn.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ehwqpu.com/Article/details/gt2srurajno.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xuetiantiany.cn/Article/details/gt2zrffskhq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daxiang520.top/Article/details/gt2gbnjmsdv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ybcxt.top/Article/details/gt2qohugwhg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hfpthk.cn/Article/details/gt2zptwjwso.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jqgufenzy.top/Article/details/gt2xstmmjbc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zdqjudy.top/Article/details/gt2vipgholu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sxryk.cn/Article/details/gt2gwhyivic.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sryeozlc.html

O. 并发与异步
来源：http://dali.pengpengdd.cyou/Article/details/gt2obuaqmap.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2ujhtdlem.html

[O01] 启动一个线程
来源：http://dali.fzhhl.top/Article/details/gt2hrtbbbow.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zdqjudy.top/Article/details/gt2hkjhgweu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zycfv.cn/Article/details/gt2wukgzkqq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yongpay.top/Article/details/gt2mieabqee.html

TS:   // 同 JS
来源：http://dali.shanyushiyangtech.top/Article/details/gt2owhudmbg.html

Java: new Thread(() -> f()).start()
来源：http://dali.sweek.top/Article/details/gt2esiewkky.html

Go:   go f()
来源：http://dali.xylfe.cn/Article/details/gt2qjuujjzf.html

Ruby: Thread.new { f }
来源：http://dali.zhongyouzk.top/Article/details/gt2rawjnkaw.html

C#:   Task.Run(() => F());
来源：http://dali.hfpthk.cn/Article/details/gt2kdsghbgl.html

[O02] 使用线程池
来源：http://dali.jinqigufen.top/Article/details/gt2ozybswmw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhoulong.xyz/Article/details/gt2zwnpnvqu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xuanzx.com/Article/details/gt2fsufqppj.html

JS:   // worker_threads 线程池
来源：http://dali.jinqigfzy.top/Article/details/gt2rurbivjc.html

TS:   // worker_threads 线程池
来源：http://dali.yuanzhike.top/Article/details/gt2anxpvxad.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.smart0.xyz/Article/details/gt2wpehxhlm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.guowangkeji.top/Article/details/gt2tziyjetp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jlsjyb.cn/Article/details/gt2xaufpsuc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hnxiangtu.top/Article/details/gt2crkvqtae.html

[O03] 加锁保护共享数据
来源：http://dali.nanxinkj.top/Article/details/gt2ibqtrzsj.html

Py:   with lock: shared += 1
来源：http://dali.yvedp.cn/Article/details/gt2nnfluoxp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.redwolf501.top/Article/details/gt2bkwhutmd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.quarkkingdee.top/Article/details/gt2ilqxevxu.html

TS:   // 同 JS
来源：http://dali.ehwqpu.com/Article/details/gt2vvqhojmt.html

Java: synchronized (this) { shared++; }
来源：http://dali.hfpthk.cn/Article/details/gt2shkdxlnr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hnqzz.top/Article/details/gt2apliarxf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yongpay.top/Article/details/gt2jnwhanyd.html

C#:   lock (gate) { shared++; }
来源：http://dali.smart0.xyz/Article/details/gt2kezkoxqr.html

[O04] 定义异步函数并等待
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ervlrlbd.html

Py:   async def f():⏎    await g()
来源：http://dali.tanke756.top/Article/details/gt2czzufbpk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hnqzz.top/Article/details/gt2mokiagco.html

JS:   async function f() { await g(); }
来源：http://dali.0kj1m.cn/Article/details/gt2kymnfffe.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.bjfxy.top/Article/details/gt2pulyybbk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.vqdsnc.cn/Article/details/gt2pmqpszjk.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yangfankeji.com/Article/details/gt2zigvacjz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.pengpengdd.cyou/Article/details/gt2xbbfkjeu.html

C#:   async Task F() { await G(); }
来源：http://dali.yangfankeji.com/Article/details/gt2irujhpza.html

[O05] 并发执行并等待全部完成
来源：http://dali.hfpthk.cn/Article/details/gt2ahcsyeqz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hnxiangtu.top/Article/details/gt2glwxbjnv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yangfankeji.com/Article/details/gt2eovconpc.html

JS:   await Promise.all(tasks)
来源：http://dali.cqqwz.cn/Article/details/gt2hsubwren.html

TS:   await Promise.all(tasks)
来源：http://dali.shuidangran.top/Article/details/gt2mklruddx.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yuanzhike.top/Article/details/gt2tfnhucqb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yuanzhike.top/Article/details/gt2uffuhdar.html

Ruby: threads.map(&:join)
来源：http://dali.jiagoushi.top/Article/details/gt2hugxaibq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.tian-w.cn/Article/details/gt2oyxhbnpp.html


<!-- 参考信息 -->