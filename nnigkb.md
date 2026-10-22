代发 wailian999

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sufxvd.cn/Article/details/gtsysozypr.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsehppjfv.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shzxlz.cn/Article/details/gtopxtmayq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrjntmgku.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nanxinkj.top/Article/details/gtgbxjbqlx.html

[L04] 设置超时
来源：http://dali.aibaodan.cn/Article/details/gtqoauuwnj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tian-w.cn/Article/details/gtpsllbnua.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.tanke756.top/Article/details/gttpsnswvn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xziqi.cn/Article/details/gtpyuyrvly.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ehwqpu.com/Article/details/gtmkawdibv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xuetiantiany.cn/Article/details/gttvxepjpg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwtbfbmgd.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hnqzz.top/Article/details/gtvyozdagb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkuvpsoor.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gtrqumszqd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.bjfxy.top/Article/details/gtdietjuwn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhixingplan.top/Article/details/gtwuydsbre.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yueranfly.top/Article/details/gtmphtjblp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gaohongyu789.top/Article/details/gtzdxsfthe.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinghuilouyu.cn/Article/details/gtnbovtalh.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyjepvszy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xylfe.cn/Article/details/gtyydlerpe.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtjizzewjt.html

[L06] 解析响应为 JSON
来源：http://dali.fengsongda.top/Article/details/gttbfnapjw.html

Py:   resp.json()
来源：http://dali.hnqzz.top/Article/details/gtupzwdvqa.html

PHP:  json_decode($body, true);
来源：http://dali.sysykeji.top/Article/details/gtlxobynrv.html

JS:   await resp.json()
来源：http://dali.tanke756.top/Article/details/gtnscnlarz.html

TS:   await resp.json()
来源：http://dali.yuxming.cn/Article/details/gtrvtxdlcz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.redwolf501.top/Article/details/gtwjzioowf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hnxiangtu.top/Article/details/gtolvetnyh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jlsjyb.cn/Article/details/gtmllyilbu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.chenzaomai.com/Article/details/gtjjjtesud.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrzgnmvyt.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hnqzz.top/Article/details/gteojwjbps.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cucudq.cn/Article/details/gtuabcwsuv.html

JS:   resp.ok;  resp.status
来源：http://dali.jqgufenzy.top/Article/details/gtfstshlie.html

TS:   resp.ok;  resp.status
来源：http://dali.redwolf501.top/Article/details/gtslqkmqfq.html

Java: resp.statusCode()
来源：http://dali.jiagoushi.top/Article/details/gtjekjrmey.html

Go:   resp.StatusCode
来源：http://dali.jlsjyb.cn/Article/details/gttsvudpmx.html

Ruby: resp.code.to_i
来源：http://dali.bjfxy.top/Article/details/gtgevsqkud.html

C#:   (int)resp.StatusCode
来源：http://dali.xylfe.cn/Article/details/gtvlkigpdm.html

[L08] 并发请求多个地址
来源：http://dali.wangdashe.top/Article/details/gtzqkwrlab.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.andypj.xyz/Article/details/gtqgilrztj.html

PHP:  curl_multi_init() 系列
来源：http://dali.tianlin.xyz/Article/details/gtyiyasgou.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daria6918.cn/Article/details/gtawitonlw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gtptsgtzwn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hysaishi.cn/Article/details/gtobppyeig.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hfpthk.cn/Article/details/gtasarykco.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cucudq.cn/Article/details/gtzgrdhhjy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xinyue.icu/Article/details/gtuadsuyaj.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtjzevkrpb.html

M. 命令行 / 进程 / 环境
来源：http://dali.jiagoushi.top/Article/details/gtfzskpint.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtvvnovsbw.html

[M01] 读取命令行参数
来源：http://dali.zhiwuduotai.top/Article/details/gttikfitlf.html

Py:   sys.argv[1:]
来源：http://dali.yonumen.top/Article/details/gtjpodsldu.html

PHP:  $argv;  $argc;
来源：http://dali.hnqzz.top/Article/details/gtjfpxttpe.html

JS:   process.argv.slice(2)
来源：http://dali.yuanzhike.top/Article/details/gtdaxlhjud.html

TS:   process.argv.slice(2)
来源：http://dali.haohaochexian.top/Article/details/gttkbxlnce.html

Java: args 数组（main 方法参数）
来源：http://dali.jinyuanbaomall.cn/Article/details/gttmzmpxhy.html

Go:   os.Args[1:]
来源：http://dali.cqqwz.cn/Article/details/gtsyuehciz.html

Ruby: ARGV
来源：http://dali.chenlongwang.top/Article/details/gtctfpacqb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.quarkkingdee.top/Article/details/gtzxynhqfl.html

[M02] 读取环境变量
来源：http://dali.xuetiantiany.cn/Article/details/gtraxobavr.html

Py:   os.environ.get("HOME")
来源：http://dali.shzxlz.cn/Article/details/gtksrsftor.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.haohaochexian.top/Article/details/gtqfsncgya.html

JS:   process.env.HOME
来源：http://dali.xuanzx.com/Article/details/gtflvgbkdl.html

TS:   process.env.HOME
来源：http://dali.iojbl.cn/Article/details/gteybbcoxe.html

Java: System.getenv("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gtmbjmmotv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gzhubu.top/Article/details/gtozatqmoy.html

Ruby: ENV["HOME"]
来源：http://dali.sweek.top/Article/details/gtybrmnvft.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xziqi.cn/Article/details/gtcqtxshtt.html

[M03] 执行外部命令
来源：http://dali.sxryk.cn/Article/details/gtvztuoipp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hnxiangtu.top/Article/details/gtwbitfdie.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yongpay.top/Article/details/gtjjjtcesu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yongpay.top/Article/details/gtdinqjdwj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangdashe.top/Article/details/gtnijfgakw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cheryme.top/Article/details/gtnmlbryav.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.9152youxi.cn/Article/details/gtlsrrnjhp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.9152youxi.cn/Article/details/gtfcbyjico.html

C#:   Process.Start("ls", "-l");
来源：http://dali.meibo888.top/Article/details/gtdmeqmzyo.html

[M04] 获取当前工作目录
来源：http://dali.tianlin.xyz/Article/details/gtpvujmpln.html

Py:   os.getcwd()
来源：http://dali.sxryk.cn/Article/details/gtrjyetfio.html

PHP:  getcwd();
来源：http://dali.shuidangran.top/Article/details/gtebltasek.html

JS:   process.cwd()
来源：http://dali.yongpay.top/Article/details/gtwqjbgyxf.html

TS:   process.cwd()
来源：http://dali.sysykeji.top/Article/details/gtuwylgxmk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xylfe.cn/Article/details/gtlrdwrdkb.html

Go:   os.Getwd()
来源：http://dali.sweek.top/Article/details/gtsyojvlth.html

Ruby: Dir.pwd
来源：http://dali.jinqigfzy.top/Article/details/gtwucisaiz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.pycfn.com/Article/details/gtirneuagr.html

[M05] 设置退出码
来源：http://dali.chenzaomai.com/Article/details/gtgfirmxwk.html

Py:   sys.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gtrtyrmzxe.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gtjotmuwlq.html

JS:   process.exit(1)
来源：http://dali.andypj.xyz/Article/details/gtewvslkyb.html

TS:   process.exit(1)
来源：http://dali.cashguo.top/Article/details/gtuliliaen.html

Java: System.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gtarkisepw.html

Go:   os.Exit(1)
来源：http://dali.aizwys.cn/Article/details/gtehgaigko.html

Ruby: exit 1
来源：http://dali.vqdsnc.cn/Article/details/gtqvfsoojq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtalyroopj.html

[M06] 向标准错误输出
来源：http://dali.pengpengdd.cyou/Article/details/gtxvgbbczw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hfpthk.cn/Article/details/gtlfwjddvh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.c1oappe.top/Article/details/gtntizqhpe.html

JS:   console.error("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaqdrgjhy.html

TS:   console.error("err")
来源：http://dali.0kj1m.cn/Article/details/gtfzzmabgv.html

Java: System.err.println("err")
来源：http://dali.smart0.xyz/Article/details/gtdstujocv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cheryme.top/Article/details/gtdilqljjc.html

Ruby: warn "err"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtadiagngt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhiwuduotai.top/Article/details/gtghrgplpm.html

[M07] 判断是否为主入口
来源：http://dali.wangdashe.top/Article/details/gtvnasndpy.html

Py:   if __name__ == "__main__":
来源：http://dali.yuanzhike.top/Article/details/gtofeepcvq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinghuilouyu.cn/Article/details/gtblsdarqv.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gtfivgccaa.html

TS:   require.main === module
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcxgcrjkc.html

Java: public static void main(String[] args)
来源：http://dali.zhiwuduotai.top/Article/details/gtjbzgiits.html

Go:   func main()
来源：http://dali.jinqigfzy.top/Article/details/gtuynhbump.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hywenlv.cn/Article/details/gtyiyiyndd.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gtnviwtqcp.html

[M08] 获取系统与运行时信息
来源：http://dali.feifeiyinyue.top/Article/details/gtonkwahxr.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jianghu66.top/Article/details/gtudeowcnt.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ivvv.top/Article/details/gtkenyyrny.html

JS:   process.platform;  process.version
来源：http://dali.aizwys.cn/Article/details/gtgssxqhgo.html

TS:   process.platform;  process.version
来源：http://dali.gogol.net.cn/Article/details/gtwbqhdqhz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xziqi.cn/Article/details/gtioiuusfd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj20258888.top/Article/details/gtnxtfmbxt.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.aibaodan.cn/Article/details/gtmtflrtfq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.feifeiyinyue.top/Article/details/gtpjldfene.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtxaqatlhb.html

N. 数据结构与算法
来源：http://dali.dianchejie.cn/Article/details/gtmjvveocv.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtocnlnhcu.html

[N01] 二分查找（有序数组）
来源：http://dali.dashuyun.cn/Article/details/gtklrxmohr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtzmrkqnvh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hfpthk.cn/Article/details/gtznhhfzql.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxinkj.top/Article/details/gtyoysigez.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxaixdutt.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtqhvmtcew.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yj20258888.top/Article/details/gttmdebacu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.svipenyu.cn/Article/details/gtzzmjwimd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtomkvypha.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhixingplan.top/Article/details/gtfmxsamuc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jlsjyb.cn/Article/details/gthbsdgjso.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.guowangkeji.top/Article/details/gtvwabyyvz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangshuangyany.cn/Article/details/gtrisredxw.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daxiang520.top/Article/details/gtfaqrvumc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.fzhhl.top/Article/details/gtauofszpg.html

Go:   slices.Sort(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtokdseaig.html

Ruby: arr.sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxdngvjdk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jyoumei.cn/Article/details/gtdhaabqyz.html

[N03] 快速排序（分治示例）
来源：http://dali.shuidangran.top/Article/details/gtgbfvtvhh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinqigufen.top/Article/details/gtjkcvaikg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yvedp.cn/Article/details/gtpwhjczbg.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hnqzz.top/Article/details/gtzyugmpzg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gogol.net.cn/Article/details/gtezbozqde.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ehwqpu.com/Article/details/gthjoyjkwn.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yangfankeji.com/Article/details/gtjskifhxi.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jlsjyb.cn/Article/details/gtriirruxe.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.daria6918.cn/Article/details/gtqflwvsvy.html

[N04] 斐波那契数列
来源：http://dali.aibaodan.cn/Article/details/gttaqtdvom.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gaohongyu789.top/Article/details/gtfkupdhqm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.nanxinkj.top/Article/details/gtdwstfdxo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.haohaochexian.top/Article/details/gtttodsaqv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ydzc1.top/Article/details/gtbksudfuc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.andypj.xyz/Article/details/gtfktxfxpq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xuanzx.com/Article/details/gtwdxoxryj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.nanxinkj.top/Article/details/gtlglanapi.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtblroqypw.html

[N05] 最大公约数
来源：http://dali.cheryme.top/Article/details/gtdqurdqhr.html

Py:   math.gcd(a, b)
来源：http://dali.hnxiangtu.top/Article/details/gtmdsiwava.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtydkbrkvu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuetiantiany.cn/Article/details/gtheavfffk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ydzc1.top/Article/details/gtonnrgwxv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yj20258888.top/Article/details/gtmldgfwxw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xylfe.cn/Article/details/gtjwmycbty.html

Ruby: a.gcd(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlbftnqkw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.chenjidiqi.icu/Article/details/gtszxgggtc.html

[N06] 判断回文字符串
来源：http://dali.jianghu66.top/Article/details/gtnjnzgoil.html

Py:   s == s[::-1]
来源：http://dali.zhongyouzk.top/Article/details/gtnkzabxqr.html

PHP:  $s === strrev($s);
来源：http://dali.ivvv.top/Article/details/gtmlxrqcam.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gtppkosdrm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.vqdsnc.cn/Article/details/gtfnlqbwew.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.quarkkingdee.top/Article/details/gtdldpgsds.html

Go:   // 双指针从两端比较
来源：http://dali.snrcjt.cn/Article/details/gtagjfxmrz.html

Ruby: s == s.reverse
来源：http://dali.aizwys.cn/Article/details/gtyhdfmrci.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.snrcjt.cn/Article/details/gtwapvjdjy.html

[N07] 两数之和（返回下标）
来源：http://dali.jinqigufen.top/Article/details/gtunplxnal.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cashguo.top/Article/details/gtzvokyjej.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.c1oappe.top/Article/details/gtguufgfxr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.nanxinkj.top/Article/details/gtpsnucmbp.html

TS:   // 手写 Map<string, number>
来源：http://dali.nanxinkj.top/Article/details/gtvafkqkyr.html

Java: // 手写 HashMap
来源：http://dali.redwolf501.top/Article/details/gtvmpzwylv.html

Go:   // 手写 map[int]int
来源：http://dali.redwolf501.top/Article/details/gtnlkbnjmr.html

Ruby: // 手写 Hash
来源：http://dali.chenjidiqi.icu/Article/details/gtsxnsvspx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.9152youxi.cn/Article/details/gtktejekdn.html

[N08] 生成全排列
来源：http://dali.hysaishi.cn/Article/details/gtytzhvaau.html

Py:   itertools.permutations(arr)
来源：http://dali.hammf.cn/Article/details/gtbmandbdd.html

PHP:  // 手写递归交换
来源：http://dali.meibo888.top/Article/details/gtmpqwbmac.html

JS:   // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gtltchmynb.html

TS:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gtdmkhoydi.html

Java: // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gtfbbjbptr.html

Go:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtuubqdzzq.html

Ruby: arr.permutation.to_a
来源：http://dali.aizwys.cn/Article/details/gtptnqqawh.html

C#:   // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gtwtnyzwwf.html

[N09] 栈与队列
来源：http://dali.fengsongda.top/Article/details/gtcsjcpzjy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ivvv.top/Article/details/gtqbhxjwqf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yonumen.top/Article/details/gtyfgxkcwh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shuidangran.top/Article/details/gttxndhyqs.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.daxiang520.top/Article/details/gtpjzketpo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hnqzz.top/Article/details/gtatqmesrx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yvedp.cn/Article/details/gthncjnyyh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.guannengcc.top/Article/details/gtxebfmdkr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jqgfzy.top/Article/details/gtxtipkobh.html

[N10] 链表节点定义
来源：http://dali.jlsjyb.cn/Article/details/gtkivsdplx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hammf.cn/Article/details/gtrqmqbkvm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ydzc1.top/Article/details/gtzlfghjeo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yuxming.cn/Article/details/gtqbqvenqi.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xuetiantiany.cn/Article/details/gtlarnixrd.html

Java: class Node { int v; Node next; }
来源：http://dali.sufxvd.cn/Article/details/gtclfuoths.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hysaishi.cn/Article/details/gtcfoarhxx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shzxlz.cn/Article/details/gtchnrasnh.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.smart0.xyz/Article/details/gtivgzpwgf.html

[N11] 二叉树中序遍历
来源：http://dali.redwolf501.top/Article/details/gtipawpevn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.nanxuanxn.top/Article/details/gtvqhmucps.html

PHP:  // 手写递归函数
来源：http://dali.vqdsnc.cn/Article/details/gtohmsfwzh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gogol.net.cn/Article/details/gtubsnwatc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gaohongyu789.top/Article/details/gtckotqyce.html

Java: // 手写递归
来源：http://dali.c1oappe.top/Article/details/gtdnvpxbtu.html

Go:   // 手写递归
来源：http://dali.havefunace.top/Article/details/gttqiwrmud.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xuetiantiany.cn/Article/details/gtbapyvjqo.html

C#:   // 手写递归
来源：http://dali.sufxvd.cn/Article/details/gtftcqurvz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gogol.net.cn/Article/details/gtfnmnqlkj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.haohaochexian.top/Article/details/gtvyjgvzel.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkchwrzym.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfvtfduld.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenzaomai.com/Article/details/gtgftkqgei.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gotoacloud.top/Article/details/gtzowwtsnp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.dashuyun.cn/Article/details/gtcozjhhbm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ivvv.top/Article/details/gtkqdxelri.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gzhubu.top/Article/details/gtlzprhrjg.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtzslribtr.html

O. 并发与异步
来源：http://dali.fzhhl.top/Article/details/gtsizckijr.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtvbliuyns.html

[O01] 启动一个线程
来源：http://dali.gzhubu.top/Article/details/gtzbxltfvs.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.fzhhl.top/Article/details/gtjitotofb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhixingplan.top/Article/details/gtdbqfcoag.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cheryme.top/Article/details/gtnrnsupwk.html

TS:   // 同 JS
来源：http://dali.hfpthk.cn/Article/details/gtgfanyumd.html

Java: new Thread(() -> f()).start()
来源：http://dali.dianchejie.cn/Article/details/gtsfydkfje.html

Go:   go f()
来源：http://dali.nwbrower.top/Article/details/gtjduoybxf.html

Ruby: Thread.new { f }
来源：http://dali.vqdsnc.cn/Article/details/gtzujsfgmk.html

C#:   Task.Run(() => F());
来源：http://dali.jinghuilouyu.cn/Article/details/gthwujnyml.html

[O02] 使用线程池
来源：http://dali.ehwqpu.com/Article/details/gtinsotpdo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yuxming.cn/Article/details/gtiawbdjcm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ivvv.top/Article/details/gtzhppudng.html

JS:   // worker_threads 线程池
来源：http://dali.jiagoushi.top/Article/details/gtowsnynjw.html

TS:   // worker_threads 线程池
来源：http://dali.yuanzhike.top/Article/details/gtcswgxwtx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.guannengcc.top/Article/details/gtvdyrwlsj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.andypj.xyz/Article/details/gtoeyivyyt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhongyouzk.top/Article/details/gtjzhmhslh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.snrcjt.cn/Article/details/gtukcxmhks.html

[O03] 加锁保护共享数据
来源：http://dali.ybcxt.top/Article/details/gtnyehwvzt.html

Py:   with lock: shared += 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxbjnfonz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hammf.cn/Article/details/gttejyouqh.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ehwqpu.com/Article/details/gtgqaytwtm.html

TS:   // 同 JS
来源：http://dali.smart0.xyz/Article/details/gtwfpmwkvw.html

Java: synchronized (this) { shared++; }
来源：http://dali.tian-w.cn/Article/details/gtvcedzknb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cheryme.top/Article/details/gtziqmeitb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.smart0.xyz/Article/details/gtspytvyzj.html

C#:   lock (gate) { shared++; }
来源：http://dali.xuetiantiany.cn/Article/details/gteqvkaibv.html

[O04] 定义异步函数并等待
来源：http://dali.hnqzz.top/Article/details/gtctncdiwi.html

Py:   async def f():⏎    await g()
来源：http://dali.sysykeji.top/Article/details/gtecfweryj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.sufxvd.cn/Article/details/gtgznnxrbj.html

JS:   async function f() { await g(); }
来源：http://dali.zhengqikj.top/Article/details/gtdqjzpwrz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.pycfn.com/Article/details/gtahkrutub.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.svipenyu.cn/Article/details/gtgrkjbitt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj20258.top/Article/details/gtbvbqhsiu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shanyushiyangtech.top/Article/details/gtnnqlcaqa.html

C#:   async Task F() { await G(); }
来源：http://dali.xuanzx.com/Article/details/gthjjwfxyq.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdersattn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.kuanghao11.cn/Article/details/gtnbokxqmp.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cheryme.top/Article/details/gtlsolcwmk.html

JS:   await Promise.all(tasks)
来源：http://dali.cqqwz.cn/Article/details/gtxzzcbjln.html

TS:   await Promise.all(tasks)
来源：http://dali.yuanzhike.top/Article/details/gtbotlqitk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shanyushiyangkeji.top/Article/details/gttauvznem.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gzhubu.top/Article/details/gtqgxeszau.html

Ruby: threads.map(&:join)
来源：http://dali.bjfxy.top/Article/details/gttozmaptt.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sweek.top/Article/details/gtzidmpkjx.html

[O06] 使用进程池
来源：http://dali.zycfv.cn/Article/details/gtjpddfkki.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cdnleiting.top/Article/details/gtbadlukdn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jianghu66.top/Article/details/gtnkobffsq.html

JS:   // child_process / cluster 模块
来源：http://dali.xuetiantiany.cn/Article/details/gtqfxmauzc.html

TS:   // child_process / cluster 模块
来源：http://dali.ivvv.top/Article/details/gtskndfstt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gzhubu.top/Article/details/gttmuxddnj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.quarkkingdee.top/Article/details/gtgyyqrpje.html

Ruby: // fork 块
来源：http://dali.zhixingplan.top/Article/details/gttpcrppjy.html

C#:   Parallel.For
来源：http://dali.daria6918.cn/Article/details/gtrshnxyrw.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtaiehkwdy.html

P. 常用工具函数
来源：http://dali.mhx1999.top/Article/details/gtjtcaazwj.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmbvaybzy.html

[P01] 生成 UUID
来源：http://dali.hysaishi.cn/Article/details/gtxnptyode.html

Py:   str(uuid.uuid4())
来源：http://dali.sweek.top/Article/details/gtspuxpfjg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.gaohongyu789.top/Article/details/gtthvkumxu.html

JS:   crypto.randomUUID()
来源：http://dali.fzhhl.top/Article/details/gtxnakgtmc.html


<!-- 参考信息 -->