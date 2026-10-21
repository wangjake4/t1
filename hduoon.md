代发 wailian999

[L03] 设置自定义请求头
来源：http://dali.jinyuanbaomall.cn/Article/details/gtejzxlkuc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hywenlv.cn/Article/details/gtrdkoxccc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jlsjyb.cn/Article/details/gtvjbwomxr.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.smart0.xyz/Article/details/gtqdptcyux.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.feifeiyinyue.top/Article/details/gtifqpsloh.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yj20258.top/Article/details/gtgrcnumca.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yueranfly.top/Article/details/gtxanltuhf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.andypj.xyz/Article/details/gtukprmrlx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shuidangran.top/Article/details/gtdhhqnnvo.html

[L04] 设置超时
来源：http://dali.jlsjyb.cn/Article/details/gtqojzotrb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhoulong.xyz/Article/details/gteiltkumx.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuqogsrks.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daxiang520.top/Article/details/gtsgsanhzx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guowangkeji.top/Article/details/gtpnqzedbk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shanyushiyangtech.top/Article/details/gtppfbjwtc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jqgufenzy.top/Article/details/gtyirnxchj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jqgufenzy.top/Article/details/gtuvhttpfj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.svipenyu.cn/Article/details/gtaizbdzlo.html

[L05] 上传文件（multipart）
来源：http://dali.jinqigufen.top/Article/details/gtmglwpwhk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cdnleiting.top/Article/details/gtfyrbdozj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhiwuduotai.top/Article/details/gtxqbbvqvt.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sxryk.cn/Article/details/gtdykkalpy.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yvedp.cn/Article/details/gtepjbetss.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gogol.net.cn/Article/details/gtkvrztncj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.birdmap.top/Article/details/gtizhfqzan.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shangyingyoupin.top/Article/details/gtmzpeqqtd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yonumen.top/Article/details/gtommqnxfb.html

[L06] 解析响应为 JSON
来源：http://dali.yanxiufei.cn/Article/details/gtkrcwuwsz.html

Py:   resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gtktxbvbvy.html

PHP:  json_decode($body, true);
来源：http://dali.9152youxi.cn/Article/details/gtgiftaojv.html

JS:   await resp.json()
来源：http://dali.snrcjt.cn/Article/details/gtvqgcjjgt.html

TS:   await resp.json()
来源：http://dali.cheryme.top/Article/details/gtpyaimbir.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj202588.top/Article/details/gtvnxmlotc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yvedp.cn/Article/details/gtbhvraqkx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hnqzz.top/Article/details/gtfzagpgxt.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhoulong.xyz/Article/details/gtnbinyrnw.html

[L07] 处理 HTTP 状态码
来源：http://dali.redwolf501.top/Article/details/gtuiypvpsd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nanxinkj.top/Article/details/gtptqrasju.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenzaomai.com/Article/details/gtpykwswyc.html

JS:   resp.ok;  resp.status
来源：http://dali.hywenlv.cn/Article/details/gtftdgaywl.html

TS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzktvellz.html

Java: resp.statusCode()
来源：http://dali.shzxlz.cn/Article/details/gtwrbxgeae.html

Go:   resp.StatusCode
来源：http://dali.c1oappe.top/Article/details/gtzchrkyxy.html

Ruby: resp.code.to_i
来源：http://dali.daria6918.cn/Article/details/gtdaznxwen.html

C#:   (int)resp.StatusCode
来源：http://dali.iojbl.cn/Article/details/gtpevkwyuh.html

[L08] 并发请求多个地址
来源：http://dali.fzhhl.top/Article/details/gtbrapnemu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hnxiangtu.top/Article/details/gtljrkxsqp.html

PHP:  curl_multi_init() 系列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnltnmntz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.snrcjt.cn/Article/details/gtltfepxkz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fzhhl.top/Article/details/gtjiltxacz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.mhx1999.top/Article/details/gtclppimyf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.wangdashe.top/Article/details/gtbumlbbfc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.feifeiyinyue.top/Article/details/gtbmvcxcgr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gzhubu.top/Article/details/gttsthofkj.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtjovzfuxv.html

M. 命令行 / 进程 / 环境
来源：http://dali.guowangkeji.top/Article/details/gtnkpcczij.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtflhamoyw.html

[M01] 读取命令行参数
来源：http://dali.gzhubu.top/Article/details/gtyvtartlu.html

Py:   sys.argv[1:]
来源：http://dali.shangyingyoupin.top/Article/details/gtdguevkol.html

PHP:  $argv;  $argc;
来源：http://dali.fengsongda.top/Article/details/gtyrzrsnit.html

JS:   process.argv.slice(2)
来源：http://dali.vqdsnc.cn/Article/details/gtczpybtic.html

TS:   process.argv.slice(2)
来源：http://dali.xuetiantiany.cn/Article/details/gtunnfzctg.html

Java: args 数组（main 方法参数）
来源：http://dali.redwolf501.top/Article/details/gtfjdqatus.html

Go:   os.Args[1:]
来源：http://dali.jyoumei.cn/Article/details/gtubodnhgp.html

Ruby: ARGV
来源：http://dali.sxryk.cn/Article/details/gtqkaasbhr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.snrcjt.cn/Article/details/gthnwqcnwn.html

[M02] 读取环境变量
来源：http://dali.xinyue.icu/Article/details/gtfnmdtokx.html

Py:   os.environ.get("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gtrepipfby.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gaohongyu789.top/Article/details/gtnlettirw.html

JS:   process.env.HOME
来源：http://dali.hywenlv.cn/Article/details/gtpgrvejtb.html

TS:   process.env.HOME
来源：http://dali.yangfankeji.com/Article/details/gtaldmowix.html

Java: System.getenv("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgxipspng.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.0kj1m.cn/Article/details/gtpcvsquoq.html

Ruby: ENV["HOME"]
来源：http://dali.yj20258.top/Article/details/gtfpnvwbeh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ydzc1.top/Article/details/gtigswsvsr.html

[M03] 执行外部命令
来源：http://dali.chenlongwang.top/Article/details/gtaqnkhvlo.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gtotvmibsy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.snrcjt.cn/Article/details/gtkojhafni.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.9152youxi.cn/Article/details/gtvhxsrefn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.guannengcc.top/Article/details/gtblgtfzdg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yuanzhike.top/Article/details/gtthmletpb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.kuanghao11.cn/Article/details/gtgtjjcpcj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.9152youxi.cn/Article/details/gtvwbppzoj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.snrcjt.cn/Article/details/gtelfvwoxp.html

[M04] 获取当前工作目录
来源：http://dali.wangdashe.top/Article/details/gtfbyhvsht.html

Py:   os.getcwd()
来源：http://dali.xziqi.cn/Article/details/gtjfepbuem.html

PHP:  getcwd();
来源：http://dali.vqdsnc.cn/Article/details/gthobxeqxb.html

JS:   process.cwd()
来源：http://dali.yongpay.top/Article/details/gtkkxmkeme.html

TS:   process.cwd()
来源：http://dali.chenzaomai.com/Article/details/gteoimepzi.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.andypj.xyz/Article/details/gtteaxqsdo.html

Go:   os.Getwd()
来源：http://dali.jqgufenzy.top/Article/details/gtluuosbjr.html

Ruby: Dir.pwd
来源：http://dali.ydzc1.top/Article/details/gtmppkdhkj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.andypj.xyz/Article/details/gteqjenkwk.html

[M05] 设置退出码
来源：http://dali.xuanzx.com/Article/details/gtmzmqlsqt.html

Py:   sys.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gtycwythvj.html

PHP:  exit(1);
来源：http://dali.gogol.net.cn/Article/details/gtbvxddemm.html

JS:   process.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gttmjexkml.html

TS:   process.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtvisccyvp.html

Java: System.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtatsjjdna.html

Go:   os.Exit(1)
来源：http://dali.cucudq.cn/Article/details/gtojghcfvk.html

Ruby: exit 1
来源：http://dali.aizwys.cn/Article/details/gtbbhofoso.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.svipenyu.cn/Article/details/gtuzytlhxa.html

[M06] 向标准错误输出
来源：http://dali.tian-w.cn/Article/details/gtbnarouwr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkxeyzqvs.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hywenlv.cn/Article/details/gtljvpblwr.html

JS:   console.error("err")
来源：http://dali.cucudq.cn/Article/details/gtiocleuwi.html

TS:   console.error("err")
来源：http://dali.andypj.xyz/Article/details/gtistoldbd.html

Java: System.err.println("err")
来源：http://dali.wangshuangyany.cn/Article/details/gtrwjtuqdb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.vqdsnc.cn/Article/details/gtthqetksz.html

Ruby: warn "err"
来源：http://dali.birdmap.top/Article/details/gtnmkinvrp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhixingplan.top/Article/details/gtbcnokbeg.html

[M07] 判断是否为主入口
来源：http://dali.chenzaomai.com/Article/details/gthfwickzs.html

Py:   if __name__ == "__main__":
来源：http://dali.zhongyouzk.top/Article/details/gtztmrakwy.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hysaishi.cn/Article/details/gtiioeeosi.html

JS:   require.main === module
来源：http://dali.wangdashe.top/Article/details/gtrsbktwwa.html

TS:   require.main === module
来源：http://dali.c1oappe.top/Article/details/gtbhhtzajj.html

Java: public static void main(String[] args)
来源：http://dali.yonumen.top/Article/details/gtcuzkjzmr.html

Go:   func main()
来源：http://dali.yj20258888.top/Article/details/gtpzjoscgl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinghuilouyu.cn/Article/details/gtlzdotcak.html

C#:   static void Main(string[] args)
来源：http://dali.quarkkingdee.top/Article/details/gtpxpccmjb.html

[M08] 获取系统与运行时信息
来源：http://dali.zhixingplan.top/Article/details/gtykykulgi.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yuxming.cn/Article/details/gtaobtaxhe.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yanxiufei.cn/Article/details/gtdyrsrczj.html

JS:   process.platform;  process.version
来源：http://dali.nanxuanxn.top/Article/details/gtebjxbgps.html

TS:   process.platform;  process.version
来源：http://dali.snrcjt.cn/Article/details/gtpvillrps.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sysykeji.top/Article/details/gtorppcdzq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.316326.xyz/Article/details/gthcionsmy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ivvv.top/Article/details/gthwrptlja.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ppjwa.cn/Article/details/gtdfsgkcps.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtxfttkxyx.html

N. 数据结构与算法
来源：http://dali.fzhhl.top/Article/details/gtywsnoued.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtntyyijcg.html

[N01] 二分查找（有序数组）
来源：http://dali.aibaodan.cn/Article/details/gtjbtvggis.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtuxnyxmra.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gotoacloud.top/Article/details/gtzqgdzamb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhoulong.xyz/Article/details/gtpkdiflsw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hysaishi.cn/Article/details/gtosbytxlx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtguljrlgc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtqpsswctz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.9152youxi.cn/Article/details/gtrennpqif.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gtpobozykn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jianghu66.top/Article/details/gtogmraace.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yueranfly.top/Article/details/gtwipdaygm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.andypj.xyz/Article/details/gtpcvprovj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuanzhike.top/Article/details/gtuzttiwwh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.bjfxy.top/Article/details/gtbpqhfqbr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.vqdsnc.cn/Article/details/gtvrlguoej.html

Go:   slices.Sort(arr)
来源：http://dali.sxryk.cn/Article/details/gtmgukarox.html

Ruby: arr.sort
来源：http://dali.zhoulong.xyz/Article/details/gtqctixoxm.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yuanzhike.top/Article/details/gtxtgelhmx.html

[N03] 快速排序（分治示例）
来源：http://dali.zhengqikj.top/Article/details/gtslpfjehk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jqgfzy.top/Article/details/gtbjuqioeu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.iojbl.cn/Article/details/gtzwefdubd.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.feifeiyinyue.top/Article/details/gtizlsnzsh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jianghu66.top/Article/details/gtpdaatebg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zycfv.cn/Article/details/gttgbkxvvi.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yueranfly.top/Article/details/gtwccvgufw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.bjfxy.top/Article/details/gtimtdjukx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.guannengcc.top/Article/details/gtlmvgvtpr.html

[N04] 斐波那契数列
来源：http://dali.jqgufenzy.top/Article/details/gtorsrmtff.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.smart0.xyz/Article/details/gttlrqovtd.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cheryme.top/Article/details/gtfevqdlzp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ehwqpu.com/Article/details/gtgrnwlaoe.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jianghu66.top/Article/details/gttccpjsku.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shzxlz.cn/Article/details/gtauzmfnyg.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xuetiantiany.cn/Article/details/gtepwbclhl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.fengsongda.top/Article/details/gtbaiiluns.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtwcwhsyok.html

[N05] 最大公约数
来源：http://dali.chenjidiqi.icu/Article/details/gtsttroapk.html

Py:   math.gcd(a, b)
来源：http://dali.tanke756.top/Article/details/gtbrbhelmw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.316326.xyz/Article/details/gtxidwsipg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aizwys.cn/Article/details/gtodwvzjnr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yanxiufei.cn/Article/details/gtxtxvdgcj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sxryk.cn/Article/details/gtughoksat.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xinyue.icu/Article/details/gtmrgfgfml.html

Ruby: a.gcd(b)
来源：http://dali.c1oappe.top/Article/details/gtmuckkplr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvgchqitj.html

[N06] 判断回文字符串
来源：http://dali.jyoumei.cn/Article/details/gtzedjajxg.html

Py:   s == s[::-1]
来源：http://dali.hnxiangtu.top/Article/details/gtgqgdbweb.html

PHP:  $s === strrev($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmuaghzcn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gtfnurewvz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gtwlmeulej.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gaohongyu789.top/Article/details/gtjyyxchyv.html

Go:   // 双指针从两端比较
来源：http://dali.birdmap.top/Article/details/gthxbpqntq.html

Ruby: s == s.reverse
来源：http://dali.cheryme.top/Article/details/gtxjhdwcwb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.tanke756.top/Article/details/gtxcgcqmuj.html

[N07] 两数之和（返回下标）
来源：http://dali.yvedp.cn/Article/details/gtsmynsdvu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jianghu66.top/Article/details/gtyyqpiacy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.dashuyun.cn/Article/details/gtxzqdfjge.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jqgufenzy.top/Article/details/gtiyfvhmrs.html

TS:   // 手写 Map<string, number>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttcgzkihr.html

Java: // 手写 HashMap
来源：http://dali.xuanzx.com/Article/details/gtawphmoos.html

Go:   // 手写 map[int]int
来源：http://dali.cdnleiting.top/Article/details/gtntvgmuti.html

Ruby: // 手写 Hash
来源：http://dali.chenjidiqi.icu/Article/details/gtedhuisdv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.aizwys.cn/Article/details/gtfqbstpfn.html

[N08] 生成全排列
来源：http://dali.svipenyu.cn/Article/details/gtcnbfzgbi.html

Py:   itertools.permutations(arr)
来源：http://dali.cashguo.top/Article/details/gtgukasvkp.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gtlpmgboob.html

JS:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gtqmptrdet.html

TS:   // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gtqhpeqjzt.html

Java: // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gthjnrvndf.html

Go:   // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gthjrmmkdz.html

Ruby: arr.permutation.to_a
来源：http://dali.yj20258.top/Article/details/gtqkuwcjgm.html

C#:   // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gtjilfbhvo.html

[N09] 栈与队列
来源：http://dali.hnxiangtu.top/Article/details/gtqtebkbyv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.tanke756.top/Article/details/gtwbymyuty.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.nanxuanxn.top/Article/details/gtgyakqsfl.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.tianlin.xyz/Article/details/gtouopibgh.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shuidangran.top/Article/details/gtodzvjqmo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.fengsongda.top/Article/details/gtowuxontz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cucudq.cn/Article/details/gtwzbrhqkr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.snrcjt.cn/Article/details/gtjkhrakiv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhongyouzk.top/Article/details/gtecryujqp.html

[N10] 链表节点定义
来源：http://dali.ydzc1.top/Article/details/gtcohjewix.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jqgufenzy.top/Article/details/gtngzqdtlg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.andypj.xyz/Article/details/gtlfulgojp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.meibo888.top/Article/details/gtxxecxqji.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gzhubu.top/Article/details/gtozwbxbaq.html

Java: class Node { int v; Node next; }
来源：http://dali.yuxming.cn/Article/details/gttrogcqnv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sweek.top/Article/details/gtwbrggyfk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.316326.xyz/Article/details/gtfvoxiebg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ehwqpu.com/Article/details/gtupwgwvae.html

[N11] 二叉树中序遍历
来源：http://dali.hywenlv.cn/Article/details/gtgjafncgo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yanxiufei.cn/Article/details/gtthfflpnz.html

PHP:  // 手写递归函数
来源：http://dali.zhongyouzk.top/Article/details/gtioqncxqa.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.bjfxy.top/Article/details/gtausfclba.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.redwolf501.top/Article/details/gtrznkuaaa.html

Java: // 手写递归
来源：http://dali.bjfxy.top/Article/details/gtadginhuw.html

Go:   // 手写递归
来源：http://dali.cashguo.top/Article/details/gteipvzwbi.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.kuanghao11.cn/Article/details/gtczlgdktm.html

C#:   // 手写递归
来源：http://dali.kuanghao11.cn/Article/details/gtxncxvdwd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.chenjidiqi.icu/Article/details/gtmwrpkrdv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.pengpengdd.cyou/Article/details/gtahvgthjm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jiagoushi.top/Article/details/gtpxtkdrgm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ehwqpu.com/Article/details/gtjnmhpijr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenzaomai.com/Article/details/gtazohmklc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.9152youxi.cn/Article/details/gtrxjomivt.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yj202588.top/Article/details/gtnecxyfrn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsrnxqzls.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xylfe.cn/Article/details/gtjoiezgew.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtfepjkwhh.html

O. 并发与异步
来源：http://dali.shanyushiyangtech.top/Article/details/gtgcoepizw.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtufspyuma.html

[O01] 启动一个线程
来源：http://dali.tianlin.xyz/Article/details/gtibsyilhl.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.mhx1999.top/Article/details/gtlingqahl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.svipenyu.cn/Article/details/gtovcgivbu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.dianchejie.cn/Article/details/gtwmkqtcfh.html

TS:   // 同 JS
来源：http://dali.pycfn.com/Article/details/gtxtmqpqak.html

Java: new Thread(() -> f()).start()
来源：http://dali.cqqwz.cn/Article/details/gtsmdhxnpi.html

Go:   go f()
来源：http://dali.jinqigufen.top/Article/details/gtrbiyinho.html

Ruby: Thread.new { f }
来源：http://dali.kuanghao11.cn/Article/details/gtkzlcvhyh.html

C#:   Task.Run(() => F());
来源：http://dali.wangdashe.top/Article/details/gtqtowchxr.html

[O02] 使用线程池
来源：http://dali.havefunace.top/Article/details/gtolnyfqaf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yj202588.top/Article/details/gtrpqfxpsy.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhixingplan.top/Article/details/gthjxlbgtv.html

JS:   // worker_threads 线程池
来源：http://dali.dashuyun.cn/Article/details/gtlhvvsbom.html

TS:   // worker_threads 线程池
来源：http://dali.andypj.xyz/Article/details/gtqkvaxfee.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.haohaochexian.top/Article/details/gtkzqicgxg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yueranfly.top/Article/details/gtslodnfpb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhengqikj.top/Article/details/gtugmvpkwh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ehwqpu.com/Article/details/gtgzzblvdf.html

[O03] 加锁保护共享数据
来源：http://dali.cqqwz.cn/Article/details/gtrpwkocis.html

Py:   with lock: shared += 1
来源：http://dali.dianchejie.cn/Article/details/gtkqlaffbu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hnqzz.top/Article/details/gtoaejqgwj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.tian-w.cn/Article/details/gtrgvdgvlw.html

TS:   // 同 JS
来源：http://dali.redwolf501.top/Article/details/gtzicytidb.html

Java: synchronized (this) { shared++; }
来源：http://dali.feifeiyinyue.top/Article/details/gtxugpowcm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yuxming.cn/Article/details/gtvyzomxhn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xinyue.icu/Article/details/gtdwgtfzjb.html

C#:   lock (gate) { shared++; }
来源：http://dali.redwolf501.top/Article/details/gtqgcvbnbg.html

[O04] 定义异步函数并等待
来源：http://dali.c1oappe.top/Article/details/gtxikibxxm.html

Py:   async def f():⏎    await g()
来源：http://dali.jinghuilouyu.cn/Article/details/gtxbicwwqj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.havefunace.top/Article/details/gtrsmujmoy.html

JS:   async function f() { await g(); }
来源：http://dali.yuanzhike.top/Article/details/gtvygwjfmn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ivvv.top/Article/details/gtblrqtjzl.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.wangshuangyany.cn/Article/details/gttdjwgvtx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.meibo888.top/Article/details/gtlovpjgzc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shanyushiyangtech.top/Article/details/gtidmturfx.html

C#:   async Task F() { await G(); }
来源：http://dali.gaohongyu789.top/Article/details/gtdzdlzjnz.html

[O05] 并发执行并等待全部完成
来源：http://dali.gaohongyu789.top/Article/details/gtaoftnwuc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.vqdsnc.cn/Article/details/gttlpneebn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hnxiangtu.top/Article/details/gtdtqadsxk.html

JS:   await Promise.all(tasks)
来源：http://dali.yuxming.cn/Article/details/gtfuozkogx.html

TS:   await Promise.all(tasks)
来源：http://dali.guannengcc.top/Article/details/gtmylrdfum.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.chenzaomai.com/Article/details/gtfhfdydwy.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.fzhhl.top/Article/details/gtqrfofifr.html

Ruby: threads.map(&:join)
来源：http://dali.zhixingplan.top/Article/details/gteezbuuby.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jianghu66.top/Article/details/gtpsjbtshm.html

[O06] 使用进程池
来源：http://dali.hongshengwenyu.top/Article/details/gtixeakulf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yongpay.top/Article/details/gtvffgjszy.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xinyue.icu/Article/details/gtusnuiuwr.html

JS:   // child_process / cluster 模块
来源：http://dali.gotoacloud.top/Article/details/gturjgbnyp.html

TS:   // child_process / cluster 模块
来源：http://dali.hongshengwenyu.top/Article/details/gtcjouoxgp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.mhx1999.top/Article/details/gtwwwvkjni.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.nanxinkj.top/Article/details/gtasfkjbvr.html

Ruby: // fork 块
来源：http://dali.yj202588.top/Article/details/gtxlmygmpm.html

C#:   Parallel.For
来源：http://dali.ppjwa.cn/Article/details/gtfsepebqx.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtpxhnzyug.html

P. 常用工具函数
来源：http://dali.jqgufenzy.top/Article/details/gtdbxxjcdj.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtmaimmuvq.html


<!-- 参考信息 -->