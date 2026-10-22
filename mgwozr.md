代发 wailian999

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nwbrower.top/Article/details/gtflolkmpp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.c1oappe.top/Article/details/gtkxtkspsi.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtopxgkyne.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtikhledji.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ivvv.top/Article/details/gtfjvftnxc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.tian-w.cn/Article/details/gtyntasxjm.html

[L05] 上传文件（multipart）
来源：http://dali.cdnleiting.top/Article/details/gtbmmsaenh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.haohaochexian.top/Article/details/gtyyxygelh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gtunzxbqos.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xylfe.cn/Article/details/gtlklfhcmf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gzhubu.top/Article/details/gtvwjshdhd.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yuanzhike.top/Article/details/gtbtxfvrwq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ybcxt.top/Article/details/gtlcjrplhl.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sufxvd.cn/Article/details/gtkburhyqq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cashguo.top/Article/details/gteffgmeoa.html

[L06] 解析响应为 JSON
来源：http://dali.yueranfly.top/Article/details/gtkngmufse.html

Py:   resp.json()
来源：http://dali.tian-w.cn/Article/details/gtjnjyvbqq.html

PHP:  json_decode($body, true);
来源：http://dali.zdqjudy.top/Article/details/gtfyvjmfgo.html

JS:   await resp.json()
来源：http://dali.xylfe.cn/Article/details/gtxxevkfoi.html

TS:   await resp.json()
来源：http://dali.bjfxy.top/Article/details/gtpyevctim.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gtysxfukvh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.vqdsnc.cn/Article/details/gtapfmmdqr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.0kj1m.cn/Article/details/gtadesvvbd.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cucudq.cn/Article/details/gtitemjpjp.html

[L07] 处理 HTTP 状态码
来源：http://dali.hfpthk.cn/Article/details/gthwfivjnm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhixingplan.top/Article/details/gtswxsfwbk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinqigufen.top/Article/details/gtzrcavzed.html

JS:   resp.ok;  resp.status
来源：http://dali.9152youxi.cn/Article/details/gtwnwppfnk.html

TS:   resp.ok;  resp.status
来源：http://dali.yanxiufei.cn/Article/details/gtcyhomvrd.html

Java: resp.statusCode()
来源：http://dali.shangyingyoupin.top/Article/details/gtoyytmkvr.html

Go:   resp.StatusCode
来源：http://dali.daria6918.cn/Article/details/gtbawllkqc.html

Ruby: resp.code.to_i
来源：http://dali.hnxiangtu.top/Article/details/gtqxosiylz.html

C#:   (int)resp.StatusCode
来源：http://dali.cucudq.cn/Article/details/gtgqpztccn.html

[L08] 并发请求多个地址
来源：http://dali.hfpthk.cn/Article/details/gtndtezqtk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xziqi.cn/Article/details/gtjrjmzivs.html

PHP:  curl_multi_init() 系列
来源：http://dali.xylfe.cn/Article/details/gtxrgbasvw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yueranfly.top/Article/details/gtbaywxoph.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gogol.net.cn/Article/details/gtvmestnfq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.tanke756.top/Article/details/gtzqmlwthw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.chenzaomai.com/Article/details/gtvjhvqsmi.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yuanzhike.top/Article/details/gtimnlylbj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gtqlognvsp.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtrfbtftaq.html

M. 命令行 / 进程 / 环境
来源：http://dali.jqgufenzy.top/Article/details/gtrwhshicm.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtlneudknl.html

[M01] 读取命令行参数
来源：http://dali.zhengqikj.top/Article/details/gtaqmsgejw.html

Py:   sys.argv[1:]
来源：http://dali.snrcjt.cn/Article/details/gtgndekzbm.html

PHP:  $argv;  $argc;
来源：http://dali.shanyushiyangtech.top/Article/details/gtavtawswm.html

JS:   process.argv.slice(2)
来源：http://dali.quarkkingdee.top/Article/details/gtydwiigvh.html

TS:   process.argv.slice(2)
来源：http://dali.yvedp.cn/Article/details/gtdwhvecxb.html

Java: args 数组（main 方法参数）
来源：http://dali.gzhubu.top/Article/details/gtekdxtzlp.html

Go:   os.Args[1:]
来源：http://dali.mhx1999.top/Article/details/gthulnqvvv.html

Ruby: ARGV
来源：http://dali.wangdashe.top/Article/details/gtetbennhj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.wangdashe.top/Article/details/gtghluhnup.html

[M02] 读取环境变量
来源：http://dali.sysykeji.top/Article/details/gtcebrfifk.html

Py:   os.environ.get("HOME")
来源：http://dali.9152youxi.cn/Article/details/gtknqvzaru.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jlsjyb.cn/Article/details/gtmrkrzuxg.html

JS:   process.env.HOME
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrexrtsrq.html

TS:   process.env.HOME
来源：http://dali.pengpengdd.cyou/Article/details/gtlonzcwqf.html

Java: System.getenv("HOME")
来源：http://dali.aibaodan.cn/Article/details/gtujpfdmza.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtiqdsvljy.html

Ruby: ENV["HOME"]
来源：http://dali.guowangkeji.top/Article/details/gtfivudlvf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gtnmlfokvc.html

[M03] 执行外部命令
来源：http://dali.yj20258888.top/Article/details/gtdscbxaui.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yueranfly.top/Article/details/gtbuzrflkp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xuanzx.com/Article/details/gtkwucyrlv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuanzx.com/Article/details/gtttsigwmu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangshuangyany.cn/Article/details/gtjmygqdcb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.feifeiyinyue.top/Article/details/gtwcgwmarm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sweek.top/Article/details/gtbnxgaxlq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.0kj1m.cn/Article/details/gtnmhmkeyd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.snrcjt.cn/Article/details/gtcjvywduk.html

[M04] 获取当前工作目录
来源：http://dali.jiagoushi.top/Article/details/gtitsxbfyj.html

Py:   os.getcwd()
来源：http://dali.aizwys.cn/Article/details/gtrglaqcnj.html

PHP:  getcwd();
来源：http://dali.jqgfzy.top/Article/details/gtozjilmzv.html

JS:   process.cwd()
来源：http://dali.9152youxi.cn/Article/details/gtffetiurc.html

TS:   process.cwd()
来源：http://dali.jqgufenzy.top/Article/details/gtqqmtifrb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinqigufen.top/Article/details/gtisiojxaw.html

Go:   os.Getwd()
来源：http://dali.chenjidiqi.icu/Article/details/gtxibrepke.html

Ruby: Dir.pwd
来源：http://dali.jqgufenzy.top/Article/details/gtlfyhdtfu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gtbywnzyxd.html

[M05] 设置退出码
来源：http://dali.xuetiantiany.cn/Article/details/gteydraqfx.html

Py:   sys.exit(1)
来源：http://dali.tian-w.cn/Article/details/gtcevaogwr.html

PHP:  exit(1);
来源：http://dali.yangfankeji.com/Article/details/gtrcduumaf.html

JS:   process.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtkhbizwqv.html

TS:   process.exit(1)
来源：http://dali.birdmap.top/Article/details/gtofthogmf.html

Java: System.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtslhidijq.html

Go:   os.Exit(1)
来源：http://dali.gzhubu.top/Article/details/gtkkuldwxe.html

Ruby: exit 1
来源：http://dali.iojbl.cn/Article/details/gtcgtmbfdl.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.vqdsnc.cn/Article/details/gtvzgmqusb.html

[M06] 向标准错误输出
来源：http://dali.tian-w.cn/Article/details/gtgzupdley.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hnxiangtu.top/Article/details/gtttmsnoso.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.smart0.xyz/Article/details/gtihthddfd.html

JS:   console.error("err")
来源：http://dali.aizwys.cn/Article/details/gtpyxkqzdq.html

TS:   console.error("err")
来源：http://dali.sufxvd.cn/Article/details/gtvcestimx.html

Java: System.err.println("err")
来源：http://dali.gotoacloud.top/Article/details/gtztqukpat.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xuetiantiany.cn/Article/details/gtlaeahzix.html

Ruby: warn "err"
来源：http://dali.cheryme.top/Article/details/gtusgobkjv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tanke756.top/Article/details/gtqreiwddr.html

[M07] 判断是否为主入口
来源：http://dali.jinghuilouyu.cn/Article/details/gtqmtippmx.html

Py:   if __name__ == "__main__":
来源：http://dali.ydzc1.top/Article/details/gtxzlzdnnx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.quarkkingdee.top/Article/details/gtvqtdweui.html

JS:   require.main === module
来源：http://dali.wangdashe.top/Article/details/gtzpebvxfp.html

TS:   require.main === module
来源：http://dali.yueranfly.top/Article/details/gtwjgdflky.html

Java: public static void main(String[] args)
来源：http://dali.aizwys.cn/Article/details/gtvsonlhuv.html

Go:   func main()
来源：http://dali.jinghuilouyu.cn/Article/details/gtetcqcqmz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sweek.top/Article/details/gtqafecvel.html

C#:   static void Main(string[] args)
来源：http://dali.hnqzz.top/Article/details/gtrbqjbnxv.html

[M08] 获取系统与运行时信息
来源：http://dali.jqgufenzy.top/Article/details/gtsdtfgbfu.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttmxzijzx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.quarkkingdee.top/Article/details/gtrhdudiuq.html

JS:   process.platform;  process.version
来源：http://dali.nanxinkj.top/Article/details/gtztxxadgo.html

TS:   process.platform;  process.version
来源：http://dali.pengpengdd.cyou/Article/details/gtdsjcwgex.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hongshengwenyu.top/Article/details/gtiracisns.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gzhubu.top/Article/details/gtjsohhgdn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.kuanghao11.cn/Article/details/gtcgpgzfrz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yongpay.top/Article/details/gtufjakaip.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtghbrfocb.html

N. 数据结构与算法
来源：http://dali.zycfv.cn/Article/details/gtbjxzopie.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtteyibjhr.html

[N01] 二分查找（有序数组）
来源：http://dali.chenjidiqi.icu/Article/details/gtnnfburgp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtcusxnkaa.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjfjffodm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxuanxn.top/Article/details/gtdujzpaii.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.mhx1999.top/Article/details/gtqbogtdgx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfdcumtpk.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtufthyhyn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj202588.top/Article/details/gtdljofnwd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yuxming.cn/Article/details/gtkgrxtzjq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jyoumei.cn/Article/details/gthgrcllve.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yanxiufei.cn/Article/details/gtkbvyryxs.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.chenjidiqi.icu/Article/details/gtdvanwzuz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jianghu66.top/Article/details/gtdkyupdip.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigfzy.top/Article/details/gtychimbrd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.snrcjt.cn/Article/details/gtutdwytup.html

Go:   slices.Sort(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtamuqcupt.html

Ruby: arr.sort
来源：http://dali.meibo888.top/Article/details/gtxvsyzovt.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.chenjidiqi.icu/Article/details/gtebtyslxx.html

[N03] 快速排序（分治示例）
来源：http://dali.vqdsnc.cn/Article/details/gtejuoosoc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.9152youxi.cn/Article/details/gttjcssflt.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhoulong.xyz/Article/details/gtkbgmjegx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hammf.cn/Article/details/gtgslladxj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.haohaochexian.top/Article/details/gtqqeiugsk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.dianchejie.cn/Article/details/gtznasepun.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinqigufen.top/Article/details/gtlcnhutds.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinghuilouyu.cn/Article/details/gtbaggvvjy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.vqdsnc.cn/Article/details/gtnbevpetq.html

[N04] 斐波那契数列
来源：http://dali.0kj1m.cn/Article/details/gtdlmpltan.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.havefunace.top/Article/details/gtqdlysvwu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sufxvd.cn/Article/details/gtrsvxbwww.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenzaomai.com/Article/details/gthhzzgctx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shzxlz.cn/Article/details/gtvqfueghm.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hammf.cn/Article/details/gtgxhyfhoa.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.haohaochexian.top/Article/details/gtiepwaoak.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yuanzhike.top/Article/details/gtfbcuekwr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hnxiangtu.top/Article/details/gtqtozppnn.html

[N05] 最大公约数
来源：http://dali.jinqigfzy.top/Article/details/gteygcyprp.html

Py:   math.gcd(a, b)
来源：http://dali.0kj1m.cn/Article/details/gtwsyxfgim.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jqgufenzy.top/Article/details/gtkfpfdnce.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jianghu66.top/Article/details/gtcpyyintv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gotoacloud.top/Article/details/gtjmmkwzps.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yvedp.cn/Article/details/gtdobvwsfs.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jlsjyb.cn/Article/details/gtwwprzexu.html

Ruby: a.gcd(b)
来源：http://dali.guannengcc.top/Article/details/gteinjullt.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhoulong.xyz/Article/details/gtnmumimwr.html

[N06] 判断回文字符串
来源：http://dali.hnxiangtu.top/Article/details/gtmrsckjma.html

Py:   s == s[::-1]
来源：http://dali.yj202588.top/Article/details/gtzrsmhnkh.html

PHP:  $s === strrev($s);
来源：http://dali.gotoacloud.top/Article/details/gtbrrydjds.html

JS:   s === [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gtponewghm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gtbsxjosrr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zdqjudy.top/Article/details/gtxtwuvaxu.html

Go:   // 双指针从两端比较
来源：http://dali.ivvv.top/Article/details/gtgoyjhuqb.html

Ruby: s == s.reverse
来源：http://dali.aibaodan.cn/Article/details/gtwzhrrfdo.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.0kj1m.cn/Article/details/gtfqvaaaoo.html

[N07] 两数之和（返回下标）
来源：http://dali.jiagoushi.top/Article/details/gttgegvlrg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.andypj.xyz/Article/details/gtdcuinvvv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhixingplan.top/Article/details/gtmfgtkios.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yvedp.cn/Article/details/gtcymiwscl.html

TS:   // 手写 Map<string, number>
来源：http://dali.yueranfly.top/Article/details/gtlqhnjauk.html

Java: // 手写 HashMap
来源：http://dali.jqgfzy.top/Article/details/gteqplsofv.html

Go:   // 手写 map[int]int
来源：http://dali.xuetiantiany.cn/Article/details/gtrocldsru.html

Ruby: // 手写 Hash
来源：http://dali.shuidangran.top/Article/details/gtrxnzwxue.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.wangdashe.top/Article/details/gtefdcptzs.html

[N08] 生成全排列
来源：http://dali.xuetiantiany.cn/Article/details/gtzroprueb.html

Py:   itertools.permutations(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtnpyqpdop.html

PHP:  // 手写递归交换
来源：http://dali.snrcjt.cn/Article/details/gtrxharhpc.html

JS:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtrzdiwemz.html

TS:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gtkqwnrzua.html

Java: // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gthvfrrdnt.html

Go:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gttapfgxzk.html

Ruby: arr.permutation.to_a
来源：http://dali.xylfe.cn/Article/details/gtdzeulcuk.html

C#:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gtaplxrqom.html

[N09] 栈与队列
来源：http://dali.ivvv.top/Article/details/gtmtuluytl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xziqi.cn/Article/details/gthvlvztpq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ybcxt.top/Article/details/gtjgmwrowb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gaohongyu789.top/Article/details/gthcbpvqmt.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jiagoushi.top/Article/details/gtcyreacdx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtigfpyxaw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cqqwz.cn/Article/details/gtmcwutofq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yonumen.top/Article/details/gtdafalheo.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtajyowrsp.html

[N10] 链表节点定义
来源：http://dali.jinghuilouyu.cn/Article/details/gtwizklkeu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xylfe.cn/Article/details/gtjbkmlfek.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjtojjkmp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hnxiangtu.top/Article/details/gtujnkxqse.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cucudq.cn/Article/details/gttkpxofcz.html

Java: class Node { int v; Node next; }
来源：http://dali.zhoulong.xyz/Article/details/gtnctepata.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yangfankeji.com/Article/details/gtgywpzoil.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sxryk.cn/Article/details/gtqwusuoxf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yuxming.cn/Article/details/gtstrayfje.html

[N11] 二叉树中序遍历
来源：http://dali.jinqigfzy.top/Article/details/gtbxrwqepq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.tianlin.xyz/Article/details/gtirqtfgqk.html

PHP:  // 手写递归函数
来源：http://dali.ydzc1.top/Article/details/gtrjhtwtrm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.svipenyu.cn/Article/details/gtbqikkyrc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yueranfly.top/Article/details/gtyvjgtrxz.html

Java: // 手写递归
来源：http://dali.yuxming.cn/Article/details/gtxdkaczlk.html

Go:   // 手写递归
来源：http://dali.haohaochexian.top/Article/details/gtkdnjxpxh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shangyingyoupin.top/Article/details/gtlcwcknlm.html

C#:   // 手写递归
来源：http://dali.ivvv.top/Article/details/gtnbajmyni.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sxryk.cn/Article/details/gtkdjfpdek.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hnxiangtu.top/Article/details/gtxmsgujhx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yuanzhike.top/Article/details/gtjpzgbqxk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ehwqpu.com/Article/details/gtgrwqeiyc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.kuanghao11.cn/Article/details/gtkcxuteac.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.smart0.xyz/Article/details/gtmcmzzysz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinqigfzy.top/Article/details/gtanlpkawy.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.havefunace.top/Article/details/gtgcmrzwca.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.9152youxi.cn/Article/details/gtftsapdyy.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtfdqxcasg.html

O. 并发与异步
来源：http://dali.gotoacloud.top/Article/details/gtdqixntur.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtmzihufjh.html

[O01] 启动一个线程
来源：http://dali.wangshuangyany.cn/Article/details/gtogsobpim.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenjidiqi.icu/Article/details/gtmmtnbkhl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinqigfzy.top/Article/details/gtbarcyxom.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gotoacloud.top/Article/details/gtyvukvdzs.html

TS:   // 同 JS
来源：http://dali.yj20258.top/Article/details/gtlryjzxbi.html

Java: new Thread(() -> f()).start()
来源：http://dali.dashuyun.cn/Article/details/gtijuupnhz.html

Go:   go f()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtecehpgjo.html

Ruby: Thread.new { f }
来源：http://dali.sysykeji.top/Article/details/gtetkkqpcr.html

C#:   Task.Run(() => F());
来源：http://dali.xinyue.icu/Article/details/gtwvqvomud.html

[O02] 使用线程池
来源：http://dali.havefunace.top/Article/details/gtrqormnga.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xuetiantiany.cn/Article/details/gtadphhlfx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sxryk.cn/Article/details/gtyrfphkrk.html

JS:   // worker_threads 线程池
来源：http://dali.0kj1m.cn/Article/details/gtiprnbwqy.html

TS:   // worker_threads 线程池
来源：http://dali.yj202588.top/Article/details/gtsniezfpf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hysaishi.cn/Article/details/gtcfhszvbx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xziqi.cn/Article/details/gtgdgqtbfq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.daria6918.cn/Article/details/gtvnisnhdp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gogol.net.cn/Article/details/gtzvhnsddq.html

[O03] 加锁保护共享数据
来源：http://dali.tian-w.cn/Article/details/gtgvobclxk.html

Py:   with lock: shared += 1
来源：http://dali.gogol.net.cn/Article/details/gtgbfqqaic.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yj202588.top/Article/details/gtxcnrfnuq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhixingplan.top/Article/details/gtikhhcgwz.html

TS:   // 同 JS
来源：http://dali.shangyingyoupin.top/Article/details/gtabagxtsu.html

Java: synchronized (this) { shared++; }
来源：http://dali.aizwys.cn/Article/details/gtuldwkrrx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sysykeji.top/Article/details/gtyjxainfa.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xziqi.cn/Article/details/gtkzvedbyb.html

C#:   lock (gate) { shared++; }
来源：http://dali.jianghu66.top/Article/details/gtjufmmfug.html

[O04] 定义异步函数并等待
来源：http://dali.jinghuilouyu.cn/Article/details/gtijnzmxoe.html

Py:   async def f():⏎    await g()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgdcrrdch.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgorlukjn.html

JS:   async function f() { await g(); }
来源：http://dali.nwbrower.top/Article/details/gttmppsuuf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.0kj1m.cn/Article/details/gtyyziowbm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.haohaochexian.top/Article/details/gtfqthvzrg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxbnosyxe.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yj20258888.top/Article/details/gtafmhsipz.html

C#:   async Task F() { await G(); }
来源：http://dali.shuidangran.top/Article/details/gttqjbhaar.html

[O05] 并发执行并等待全部完成
来源：http://dali.zycfv.cn/Article/details/gtyziinrnd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhengqikj.top/Article/details/gtimrvppol.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.nanxuanxn.top/Article/details/gtfxnfzgeb.html

JS:   await Promise.all(tasks)
来源：http://dali.zhengqikj.top/Article/details/gtcljkczid.html

TS:   await Promise.all(tasks)
来源：http://dali.haohaochexian.top/Article/details/gtepgyioxv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cucudq.cn/Article/details/gtxpekemfq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xylfe.cn/Article/details/gtjesafjeo.html

Ruby: threads.map(&:join)
来源：http://dali.guannengcc.top/Article/details/gtudowesvj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.bjfxy.top/Article/details/gthwzktnnq.html

[O06] 使用进程池
来源：http://dali.zhoulong.xyz/Article/details/gtfnozeggp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.feifeiyinyue.top/Article/details/gtqhwomfrn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hongshengwenyu.top/Article/details/gtwbtugqmt.html

JS:   // child_process / cluster 模块
来源：http://dali.shzxlz.cn/Article/details/gtyyitalbj.html

TS:   // child_process / cluster 模块
来源：http://dali.feifeiyinyue.top/Article/details/gtrgzogumo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yvedp.cn/Article/details/gtfkgzuuge.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sufxvd.cn/Article/details/gtetgsxrpc.html

Ruby: // fork 块
来源：http://dali.zhoulong.xyz/Article/details/gtdjkihkfh.html

C#:   Parallel.For
来源：http://dali.nanxinkj.top/Article/details/gtmmvjundm.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtpmupmvqb.html

P. 常用工具函数
来源：http://dali.xinyue.icu/Article/details/gtdoulmtmd.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtgjwqnere.html

[P01] 生成 UUID
来源：http://dali.yangfankeji.com/Article/details/gtslkxiucp.html

Py:   str(uuid.uuid4())
来源：http://dali.dianchejie.cn/Article/details/gttxnwhpuq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zycfv.cn/Article/details/gtjfcvebwr.html

JS:   crypto.randomUUID()
来源：http://dali.cucudq.cn/Article/details/gtnrnozumc.html

TS:   crypto.randomUUID()
来源：http://dali.sxryk.cn/Article/details/gtujltwnkq.html

Java: UUID.randomUUID().toString()
来源：http://dali.shuidangran.top/Article/details/gtxllhndwh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gzhubu.top/Article/details/gtinytelpu.html

Ruby: SecureRandom.uuid
来源：http://dali.yonumen.top/Article/details/gtwafnadfb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.aibaodan.cn/Article/details/gtetkjwssw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cheryme.top/Article/details/gtzxqevpdw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrjbszlou.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.tianlin.xyz/Article/details/gtwlbkcyqi.html


<!-- 参考信息 -->