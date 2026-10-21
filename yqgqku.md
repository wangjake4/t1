代发 wailian999

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuetiantiany.cn/Article/details/gtxtbtdfkd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinghuilouyu.cn/Article/details/gtnzagprdq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.daria6918.cn/Article/details/gtnxyqwinj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmrdsitud.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yj20258888.top/Article/details/gtzlngrhqy.html

[L04] 设置超时
来源：http://dali.jqgufenzy.top/Article/details/gtrklvuvih.html

Py:   requests.get(url, timeout=5)
来源：http://dali.iojbl.cn/Article/details/gtogldjesv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xuanzx.com/Article/details/gturrgrnzj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cashguo.top/Article/details/gttjnevipc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangdashe.top/Article/details/gtqzbvmjar.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinqigfzy.top/Article/details/gtocrxvkeh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.c1oappe.top/Article/details/gtsgtbcugr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.fengsongda.top/Article/details/gtsziyrdev.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfpdvmiap.html

[L05] 上传文件（multipart）
来源：http://dali.fzhhl.top/Article/details/gtnaiqfmvl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gzhubu.top/Article/details/gtybqpmvgq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hnqzz.top/Article/details/gtwblpwtgf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnxiangtu.top/Article/details/gtgxaygixz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.dashuyun.cn/Article/details/gtkxfkoqqh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jlsjyb.cn/Article/details/gtphsasmyw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gzhubu.top/Article/details/gtlngqvahc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yanxiufei.cn/Article/details/gtwrjwrfcg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yonumen.top/Article/details/gtzhmhdtnb.html

[L06] 解析响应为 JSON
来源：http://dali.jqgfzy.top/Article/details/gtfzosedin.html

Py:   resp.json()
来源：http://dali.sxryk.cn/Article/details/gtfslzrwia.html

PHP:  json_decode($body, true);
来源：http://dali.ppjwa.cn/Article/details/gtryajzapy.html

JS:   await resp.json()
来源：http://dali.jqgufenzy.top/Article/details/gtrlcauifq.html

TS:   await resp.json()
来源：http://dali.jiagoushi.top/Article/details/gtrqrteskv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zdqjudy.top/Article/details/gtapvthefu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jqgfzy.top/Article/details/gtyyircwsr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.aizwys.cn/Article/details/gtahqbisgx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gzhubu.top/Article/details/gtvsibcvgb.html

[L07] 处理 HTTP 状态码
来源：http://dali.aibaodan.cn/Article/details/gtmhrwyhou.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jianghu66.top/Article/details/gteyxcqytl.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.vqdsnc.cn/Article/details/gtmfglogxg.html

JS:   resp.ok;  resp.status
来源：http://dali.pycfn.com/Article/details/gtegpmukjp.html

TS:   resp.ok;  resp.status
来源：http://dali.hysaishi.cn/Article/details/gtgwconope.html

Java: resp.statusCode()
来源：http://dali.zhiwuduotai.top/Article/details/gtdhxkmhiz.html

Go:   resp.StatusCode
来源：http://dali.shuidangran.top/Article/details/gtqikbptfu.html

Ruby: resp.code.to_i
来源：http://dali.birdmap.top/Article/details/gtzirviuff.html

C#:   (int)resp.StatusCode
来源：http://dali.daxiang520.top/Article/details/gtzajvedco.html

[L08] 并发请求多个地址
来源：http://dali.fengsongda.top/Article/details/gtoslddeim.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhiwuduotai.top/Article/details/gtccckcoac.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinqigfzy.top/Article/details/gtajadfqcp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hywenlv.cn/Article/details/gtinwmsqfk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfqgcfqxg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.tian-w.cn/Article/details/gtygwwltts.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yongpay.top/Article/details/gtrxztiale.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hongshengwenyu.top/Article/details/gtsjlpfgbf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjczyzoba.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtnfspinjn.html

M. 命令行 / 进程 / 环境
来源：http://dali.iojbl.cn/Article/details/gtmjyebejq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtixppluew.html

[M01] 读取命令行参数
来源：http://dali.ppjwa.cn/Article/details/gtqaaxpkyq.html

Py:   sys.argv[1:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtywdjirje.html

PHP:  $argv;  $argc;
来源：http://dali.ppjwa.cn/Article/details/gtikjzhfhu.html

JS:   process.argv.slice(2)
来源：http://dali.havefunace.top/Article/details/gtpxcpwvzi.html

TS:   process.argv.slice(2)
来源：http://dali.aibaodan.cn/Article/details/gtwzanhuil.html

Java: args 数组（main 方法参数）
来源：http://dali.pycfn.com/Article/details/gttobejzzf.html

Go:   os.Args[1:]
来源：http://dali.yj202588.top/Article/details/gtniwfppzo.html

Ruby: ARGV
来源：http://dali.tian-w.cn/Article/details/gtzqjabdlm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj202588.top/Article/details/gtlemsmgfr.html

[M02] 读取环境变量
来源：http://dali.gotoacloud.top/Article/details/gtmffiqdiy.html

Py:   os.environ.get("HOME")
来源：http://dali.haohaochexian.top/Article/details/gtsthywhrx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shanyushiyangtech.top/Article/details/gttyvgneky.html

JS:   process.env.HOME
来源：http://dali.cqqwz.cn/Article/details/gtfnlstchv.html

TS:   process.env.HOME
来源：http://dali.jqgufenzy.top/Article/details/gtrynucqzq.html

Java: System.getenv("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gtlqjozaqa.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.dashuyun.cn/Article/details/gtsyzldvmn.html

Ruby: ENV["HOME"]
来源：http://dali.jinqigfzy.top/Article/details/gtztaobajb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.guannengcc.top/Article/details/gtleqvoxol.html

[M03] 执行外部命令
来源：http://dali.hysaishi.cn/Article/details/gtfrttbevz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.0kj1m.cn/Article/details/gtxszuxggt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.redwolf501.top/Article/details/gtfunxeyub.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigfzy.top/Article/details/gtacceqiix.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.feifeiyinyue.top/Article/details/gtrgxuudaz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.vqdsnc.cn/Article/details/gtfmeeurtq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.pycfn.com/Article/details/gtbkwztasa.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hammf.cn/Article/details/gtcyhszrqs.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhixingplan.top/Article/details/gtnyxhqlmw.html

[M04] 获取当前工作目录
来源：http://dali.daxiang520.top/Article/details/gtqvrvdmsx.html

Py:   os.getcwd()
来源：http://dali.zhongyouzk.top/Article/details/gtdclbslxy.html

PHP:  getcwd();
来源：http://dali.sweek.top/Article/details/gttxyekqrh.html

JS:   process.cwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyowhnmoj.html

TS:   process.cwd()
来源：http://dali.xziqi.cn/Article/details/gtjaycdkwo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.daria6918.cn/Article/details/gtkghseivh.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gtrgwolxds.html

Ruby: Dir.pwd
来源：http://dali.gzhubu.top/Article/details/gtlgmpcaen.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.andypj.xyz/Article/details/gtviyxxkky.html

[M05] 设置退出码
来源：http://dali.zycfv.cn/Article/details/gtkzoxnopv.html

Py:   sys.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gttsaumcon.html

PHP:  exit(1);
来源：http://dali.smart0.xyz/Article/details/gtubpeahjq.html

JS:   process.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gtyeuqavvl.html

TS:   process.exit(1)
来源：http://dali.nwbrower.top/Article/details/gtmuykfmfg.html

Java: System.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gtvrdsiaex.html

Go:   os.Exit(1)
来源：http://dali.redwolf501.top/Article/details/gtqgifsmri.html

Ruby: exit 1
来源：http://dali.tian-w.cn/Article/details/gtphcwwemw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shzxlz.cn/Article/details/gtuajzrldp.html

[M06] 向标准错误输出
来源：http://dali.aizwys.cn/Article/details/gteyptczfj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.bjfxy.top/Article/details/gtksblyymg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yvedp.cn/Article/details/gttzmvzbvz.html

JS:   console.error("err")
来源：http://dali.jqgufenzy.top/Article/details/gtzxccffmv.html

TS:   console.error("err")
来源：http://dali.wangshuangyany.cn/Article/details/gtcyyfxeig.html

Java: System.err.println("err")
来源：http://dali.gogol.net.cn/Article/details/gtnrfzcevw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cqqwz.cn/Article/details/gtkdnplnpr.html

Ruby: warn "err"
来源：http://dali.yangfankeji.com/Article/details/gtaycrcfua.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.aizwys.cn/Article/details/gtbfbplzmk.html

[M07] 判断是否为主入口
来源：http://dali.haohaochexian.top/Article/details/gtgmmftmpx.html

Py:   if __name__ == "__main__":
来源：http://dali.guowangkeji.top/Article/details/gtyycjnbzx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhoulong.xyz/Article/details/gtwtoahunj.html

JS:   require.main === module
来源：http://dali.quarkkingdee.top/Article/details/gtwdamkkaq.html

TS:   require.main === module
来源：http://dali.ybcxt.top/Article/details/gtnjjdmakf.html

Java: public static void main(String[] args)
来源：http://dali.sxryk.cn/Article/details/gtrpnvnckk.html

Go:   func main()
来源：http://dali.quarkkingdee.top/Article/details/gtvavrsoft.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jiagoushi.top/Article/details/gtfevmzfny.html

C#:   static void Main(string[] args)
来源：http://dali.chenzaomai.com/Article/details/gtuofftpcj.html

[M08] 获取系统与运行时信息
来源：http://dali.feifeiyinyue.top/Article/details/gtwzuljquf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hammf.cn/Article/details/gtbbexflwb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yueranfly.top/Article/details/gtkoanwdql.html

JS:   process.platform;  process.version
来源：http://dali.xziqi.cn/Article/details/gtvodwgbrd.html

TS:   process.platform;  process.version
来源：http://dali.gaohongyu789.top/Article/details/gtripaxkhk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.aizwys.cn/Article/details/gtwgohnmvs.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hnqzz.top/Article/details/gtaqqrjqiq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhongyouzk.top/Article/details/gtenywziqr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xziqi.cn/Article/details/gthtcbcalp.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtwenxzkxb.html

N. 数据结构与算法
来源：http://dali.0kj1m.cn/Article/details/gtdhvtldzq.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtaxwmppec.html

[N01] 二分查找（有序数组）
来源：http://dali.yj20258888.top/Article/details/gthtyiqrlf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtqaygmzov.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.snrcjt.cn/Article/details/gtcvomuejx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwooatifw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fengsongda.top/Article/details/gtbynqqjlf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yonumen.top/Article/details/gtwpqtokdf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtgvobzrzw.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.316326.xyz/Article/details/gthpxjxjvr.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtfvrfjoyk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvuxrafhg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj202588.top/Article/details/gtnqsrovly.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.pycfn.com/Article/details/gtjpedyaei.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.svipenyu.cn/Article/details/gthezugczz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuanzx.com/Article/details/gtbqyzmfmg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xylfe.cn/Article/details/gtrhwvfxha.html

Go:   slices.Sort(arr)
来源：http://dali.yongpay.top/Article/details/gtxyfufxze.html

Ruby: arr.sort
来源：http://dali.zycfv.cn/Article/details/gtxzimsugd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jiagoushi.top/Article/details/gthapbkacy.html

[N03] 快速排序（分治示例）
来源：http://dali.aibaodan.cn/Article/details/gtpmmucppp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj20258888.top/Article/details/gtkaylihas.html

PHP:  // 递归实现，或用 usort
来源：http://dali.chenjidiqi.icu/Article/details/gtzxozknbg.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.mhx1999.top/Article/details/gtitehauqf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fzhhl.top/Article/details/gtkdwrcopx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shzxlz.cn/Article/details/gtjxsvfhvm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.fengsongda.top/Article/details/gtupeczcjk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yueranfly.top/Article/details/gtuppwtlmj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.dashuyun.cn/Article/details/gtjedsnlee.html

[N04] 斐波那契数列
来源：http://dali.wangshuangyany.cn/Article/details/gtktlcubzb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.316326.xyz/Article/details/gtkeepsvam.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xylfe.cn/Article/details/gtopujsluy.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.svipenyu.cn/Article/details/gtrlwtgqnz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sweek.top/Article/details/gtfuszycjp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.0kj1m.cn/Article/details/gtldszivgv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yueranfly.top/Article/details/gtwdpjzmdr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhixingplan.top/Article/details/gtinrhapub.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.gaohongyu789.top/Article/details/gtrrpwjrdz.html

[N05] 最大公约数
来源：http://dali.zhongyouzk.top/Article/details/gtszlicftf.html

Py:   math.gcd(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gtzntdgcvy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkkexdire.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zdqjudy.top/Article/details/gtaczatlvu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hywenlv.cn/Article/details/gtazgfrqpn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sweek.top/Article/details/gtgdpqpcit.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jqgufenzy.top/Article/details/gtxasfkqix.html

Ruby: a.gcd(b)
来源：http://dali.ydzc1.top/Article/details/gtslwxuorn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.redwolf501.top/Article/details/gtthfolmmg.html

[N06] 判断回文字符串
来源：http://dali.dianchejie.cn/Article/details/gtyjvwhzad.html

Py:   s == s[::-1]
来源：http://dali.bjfxy.top/Article/details/gtslpeslzp.html

PHP:  $s === strrev($s);
来源：http://dali.xinyue.icu/Article/details/gtfxpzxmih.html

JS:   s === [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gttcodirjf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtbhcsuvsf.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.daxiang520.top/Article/details/gtehxnfnuv.html

Go:   // 双指针从两端比较
来源：http://dali.feifeiyinyue.top/Article/details/gtzlsqwlvf.html

Ruby: s == s.reverse
来源：http://dali.svipenyu.cn/Article/details/gtosmrjqbl.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.bjfxy.top/Article/details/gtrbpbdkch.html

[N07] 两数之和（返回下标）
来源：http://dali.snrcjt.cn/Article/details/gtraqzziiw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.feifeiyinyue.top/Article/details/gturohqtki.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xziqi.cn/Article/details/gtcjhhofwf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.iojbl.cn/Article/details/gtdmiretjo.html

TS:   // 手写 Map<string, number>
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrvwyonfj.html

Java: // 手写 HashMap
来源：http://dali.yj20258888.top/Article/details/gthivoghwb.html

Go:   // 手写 map[int]int
来源：http://dali.feifeiyinyue.top/Article/details/gtocfqmema.html

Ruby: // 手写 Hash
来源：http://dali.gogol.net.cn/Article/details/gtyibgadke.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.fengsongda.top/Article/details/gtkuwbkecx.html

[N08] 生成全排列
来源：http://dali.aizwys.cn/Article/details/gtkgclbiuu.html

Py:   itertools.permutations(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtrvygmake.html

PHP:  // 手写递归交换
来源：http://dali.sxryk.cn/Article/details/gtnubcnoly.html

JS:   // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gtahdwiqad.html

TS:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gtqlwluifn.html

Java: // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gtzjhostrq.html

Go:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtuwfgexha.html

Ruby: arr.permutation.to_a
来源：http://dali.quarkkingdee.top/Article/details/gtqeslsmla.html

C#:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gtqlgirjtx.html

[N09] 栈与队列
来源：http://dali.jiagoushi.top/Article/details/gtgvagzpfw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.fzhhl.top/Article/details/gtibithjjf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.daria6918.cn/Article/details/gttdowpwaw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gotoacloud.top/Article/details/gthztvqswr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jyoumei.cn/Article/details/gtyolxpbki.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yueranfly.top/Article/details/gtbhwpgcqg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cashguo.top/Article/details/gtfstglwev.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkcqwcwmv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhiwuduotai.top/Article/details/gtsceewbrn.html

[N10] 链表节点定义
来源：http://dali.yueranfly.top/Article/details/gtdxiyexbm.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gotoacloud.top/Article/details/gtxtdimvyw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xylfe.cn/Article/details/gtufiqltzg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.316326.xyz/Article/details/gtazlxpbdn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.nanxuanxn.top/Article/details/gtbyvonzyg.html

Java: class Node { int v; Node next; }
来源：http://dali.c1oappe.top/Article/details/gtupwuqysz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yonumen.top/Article/details/gtdiuiwdix.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cheryme.top/Article/details/gtfdlsfsic.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jlsjyb.cn/Article/details/gtllvqzgbi.html

[N11] 二叉树中序遍历
来源：http://dali.yanxiufei.cn/Article/details/gtdcvjusjs.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinghuilouyu.cn/Article/details/gttaaoioft.html

PHP:  // 手写递归函数
来源：http://dali.yuxming.cn/Article/details/gtevddqsps.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.smart0.xyz/Article/details/gtwxmyraav.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jianghu66.top/Article/details/gtfshyqqss.html

Java: // 手写递归
来源：http://dali.jinqigfzy.top/Article/details/gtdndmczxa.html

Go:   // 手写递归
来源：http://dali.hnxiangtu.top/Article/details/gtregrgvgm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gaohongyu789.top/Article/details/gtxnkeelmh.html

C#:   // 手写递归
来源：http://dali.redwolf501.top/Article/details/gthpfgigex.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.nwbrower.top/Article/details/gtjdumjmlq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ivvv.top/Article/details/gtfzhcnlel.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yj202588.top/Article/details/gtmzhdsjje.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aibaodan.cn/Article/details/gtfqflmhfq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.mhx1999.top/Article/details/gtxxmkfqsz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nwbrower.top/Article/details/gtubfxuikl.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.gogol.net.cn/Article/details/gtqrvbphpp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.pengpengdd.cyou/Article/details/gtmrjacyav.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwejxhwja.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtthxvnarx.html

O. 并发与异步
来源：http://dali.hnqzz.top/Article/details/gtlpqhomhe.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gttedwgwhr.html

[O01] 启动一个线程
来源：http://dali.cheryme.top/Article/details/gtmzjtkabz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hnqzz.top/Article/details/gtqnferfsi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xuanzx.com/Article/details/gtlbhdlhoy.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hysaishi.cn/Article/details/gtzcelhxku.html

TS:   // 同 JS
来源：http://dali.tanke756.top/Article/details/gtyxqeykiw.html

Java: new Thread(() -> f()).start()
来源：http://dali.316326.xyz/Article/details/gtfhggnicf.html

Go:   go f()
来源：http://dali.xuetiantiany.cn/Article/details/gtqdzuunks.html

Ruby: Thread.new { f }
来源：http://dali.zhixingplan.top/Article/details/gtkkfsmnxs.html

C#:   Task.Run(() => F());
来源：http://dali.vqdsnc.cn/Article/details/gtquhubwpf.html

[O02] 使用线程池
来源：http://dali.tian-w.cn/Article/details/gtjguuljwq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ydzc1.top/Article/details/gthbxxrkme.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zycfv.cn/Article/details/gtwsndzshq.html

JS:   // worker_threads 线程池
来源：http://dali.yonumen.top/Article/details/gtkoskxefi.html

TS:   // worker_threads 线程池
来源：http://dali.iojbl.cn/Article/details/gtrcdgfonz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.wangshuangyany.cn/Article/details/gtgubmavcp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.nwbrower.top/Article/details/gtinluzehr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yanxiufei.cn/Article/details/gtublnlzgu.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhoulong.xyz/Article/details/gtukcmcydb.html

[O03] 加锁保护共享数据
来源：http://dali.sysykeji.top/Article/details/gtvuvxiqde.html

Py:   with lock: shared += 1
来源：http://dali.tianlin.xyz/Article/details/gtglapiplm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cdnleiting.top/Article/details/gtcjzeviqy.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhaomingkeji.xyz/Article/details/gtscpawqce.html

TS:   // 同 JS
来源：http://dali.jqgfzy.top/Article/details/gtddcpjuku.html

Java: synchronized (this) { shared++; }
来源：http://dali.cqqwz.cn/Article/details/gtbqouxstz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.fengsongda.top/Article/details/gtqwibhygw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.dianchejie.cn/Article/details/gtlneosxie.html

C#:   lock (gate) { shared++; }
来源：http://dali.aibaodan.cn/Article/details/gtyblypdvx.html

[O04] 定义异步函数并等待
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsyyuovlk.html

Py:   async def f():⏎    await g()
来源：http://dali.xziqi.cn/Article/details/gtqadqmxhn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ivvv.top/Article/details/gtadapwuvq.html

JS:   async function f() { await g(); }
来源：http://dali.yanxiufei.cn/Article/details/gtsntvleie.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj202588.top/Article/details/gtebudhedj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cqqwz.cn/Article/details/gtioloxumy.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nanxuanxn.top/Article/details/gtbjdenigm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jyoumei.cn/Article/details/gtigecwbee.html

C#:   async Task F() { await G(); }
来源：http://dali.snrcjt.cn/Article/details/gtvernkfiy.html

[O05] 并发执行并等待全部完成
来源：http://dali.shangyingyoupin.top/Article/details/gtrgrehuty.html

Py:   asyncio.gather(*tasks)
来源：http://dali.gotoacloud.top/Article/details/gtwodjszgq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cucudq.cn/Article/details/gtjaiehhal.html

JS:   await Promise.all(tasks)
来源：http://dali.wangdashe.top/Article/details/gtbucaaftj.html

TS:   await Promise.all(tasks)
来源：http://dali.fengsongda.top/Article/details/gtozmrqyio.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.chenlongwang.top/Article/details/gtbplggpfw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shangyingyoupin.top/Article/details/gtfmmtfbiz.html

Ruby: threads.map(&:join)
来源：http://dali.c1oappe.top/Article/details/gtwbnpjwni.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.birdmap.top/Article/details/gtbowuotwo.html

[O06] 使用进程池
来源：http://dali.kuanghao11.cn/Article/details/gtzklgyrye.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cashguo.top/Article/details/gttbgatlvq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoonhspnk.html

JS:   // child_process / cluster 模块
来源：http://dali.bjfxy.top/Article/details/gtfdfmgomq.html

TS:   // child_process / cluster 模块
来源：http://dali.yvedp.cn/Article/details/gtfqjvpyeu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hongshengwenyu.top/Article/details/gtjcduvqyw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtejvcginu.html

Ruby: // fork 块
来源：http://dali.0kj1m.cn/Article/details/gtngjfylke.html

C#:   Parallel.For
来源：http://dali.redwolf501.top/Article/details/gtnijqblqg.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtggjgezau.html

P. 常用工具函数
来源：http://dali.zhiwuduotai.top/Article/details/gtpwsexzlj.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtuxdfqdpq.html

[P01] 生成 UUID
来源：http://dali.xinyue.icu/Article/details/gtbhiswyaz.html

Py:   str(uuid.uuid4())
来源：http://dali.ydzc1.top/Article/details/gtytixrtil.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhengqikj.top/Article/details/gtuccekhfi.html

JS:   crypto.randomUUID()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnodpdgap.html


<!-- 参考信息 -->