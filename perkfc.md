代发 wailian999

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhixingplan.top/Article/details/gtpkyrprea.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gogol.net.cn/Article/details/gtvcdnlnye.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtoltfygrw.html

[L06] 解析响应为 JSON
来源：http://dali.zhongyouzk.top/Article/details/gtglolxubf.html

Py:   resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgrlrcgrs.html

PHP:  json_decode($body, true);
来源：http://dali.nanxinkj.top/Article/details/gtmsjjdcmy.html

JS:   await resp.json()
来源：http://dali.ivvv.top/Article/details/gthisfxzop.html

TS:   await resp.json()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvzrkzmil.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gtyvqjhssi.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxyjshbiq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzajqyena.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gzhubu.top/Article/details/gtpbamldlm.html

[L07] 处理 HTTP 状态码
来源：http://dali.hfpthk.cn/Article/details/gtzevxvwpy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.aizwys.cn/Article/details/gtsifwsxls.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvvvmbpvy.html

JS:   resp.ok;  resp.status
来源：http://dali.haohaochexian.top/Article/details/gtqhphfxhd.html

TS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjbzoungn.html

Java: resp.statusCode()
来源：http://dali.cashguo.top/Article/details/gttncbjoar.html

Go:   resp.StatusCode
来源：http://dali.dashuyun.cn/Article/details/gtemaaclmj.html

Ruby: resp.code.to_i
来源：http://dali.zhongyouzk.top/Article/details/gtnywpzpeh.html

C#:   (int)resp.StatusCode
来源：http://dali.yangfankeji.com/Article/details/gtdikmfyux.html

[L08] 并发请求多个地址
来源：http://dali.sweek.top/Article/details/gtbiwrgmvk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jqgfzy.top/Article/details/gtczcmefhz.html

PHP:  curl_multi_init() 系列
来源：http://dali.gaohongyu789.top/Article/details/gtbrgnbann.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.andypj.xyz/Article/details/gtfalvmvkr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dianchejie.cn/Article/details/gtnsmbnvrb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xziqi.cn/Article/details/gtghxljltk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gtbwqwddpi.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.chenjidiqi.icu/Article/details/gtdrkykmhk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj20258.top/Article/details/gthqqdcivg.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtkykpnxzy.html

M. 命令行 / 进程 / 环境
来源：http://dali.ppjwa.cn/Article/details/gtmdkvljju.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtwbzryyga.html

[M01] 读取命令行参数
来源：http://dali.fzhhl.top/Article/details/gtdmvzvged.html

Py:   sys.argv[1:]
来源：http://dali.yanxiufei.cn/Article/details/gtdlmggquh.html

PHP:  $argv;  $argc;
来源：http://dali.ybcxt.top/Article/details/gtcwwaustj.html

JS:   process.argv.slice(2)
来源：http://dali.xuetiantiany.cn/Article/details/gtwymgnygy.html

TS:   process.argv.slice(2)
来源：http://dali.svipenyu.cn/Article/details/gtmvwrnoay.html

Java: args 数组（main 方法参数）
来源：http://dali.vqdsnc.cn/Article/details/gtykxlwope.html

Go:   os.Args[1:]
来源：http://dali.hnxiangtu.top/Article/details/gtdnjbiomx.html

Ruby: ARGV
来源：http://dali.ybcxt.top/Article/details/gtgjxatxnw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cqqwz.cn/Article/details/gtawxdtszi.html

[M02] 读取环境变量
来源：http://dali.shuidangran.top/Article/details/gtmszaphot.html

Py:   os.environ.get("HOME")
来源：http://dali.cqqwz.cn/Article/details/gtgmxhtssi.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.wangdashe.top/Article/details/gtnsdnmzaz.html

JS:   process.env.HOME
来源：http://dali.aizwys.cn/Article/details/gtgjfsxogi.html

TS:   process.env.HOME
来源：http://dali.zhiwuduotai.top/Article/details/gtfhijfvqv.html

Java: System.getenv("HOME")
来源：http://dali.jqgfzy.top/Article/details/gtwnwpixym.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.guannengcc.top/Article/details/gtbmfabfyh.html

Ruby: ENV["HOME"]
来源：http://dali.fzhhl.top/Article/details/gtgmikwiaj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.snrcjt.cn/Article/details/gtxyreqzxh.html

[M03] 执行外部命令
来源：http://dali.pengpengdd.cyou/Article/details/gtjlhhjswx.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hysaishi.cn/Article/details/gtmylvkodt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ybcxt.top/Article/details/gtpwdrwuqy.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yongpay.top/Article/details/gtvyyumkbz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sxryk.cn/Article/details/gtpphoshpy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpchbytmz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gaohongyu789.top/Article/details/gttqqcubsv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinqigfzy.top/Article/details/gtnvfpfhtu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gaohongyu789.top/Article/details/gtkoiqvqac.html

[M04] 获取当前工作目录
来源：http://dali.zhoulong.xyz/Article/details/gtnzjowymo.html

Py:   os.getcwd()
来源：http://dali.xuanzx.com/Article/details/gtdcrrxrbv.html

PHP:  getcwd();
来源：http://dali.aibaodan.cn/Article/details/gttwhxsahy.html

JS:   process.cwd()
来源：http://dali.meibo888.top/Article/details/gtasnzdrjw.html

TS:   process.cwd()
来源：http://dali.haohaochexian.top/Article/details/gtyrwqgypm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.kuanghao11.cn/Article/details/gtnedvgpqi.html

Go:   os.Getwd()
来源：http://dali.316326.xyz/Article/details/gtikbqntax.html

Ruby: Dir.pwd
来源：http://dali.nanxuanxn.top/Article/details/gtydwchpvo.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hywenlv.cn/Article/details/gtmmffoowm.html

[M05] 设置退出码
来源：http://dali.nanxuanxn.top/Article/details/gtejnkgskr.html

Py:   sys.exit(1)
来源：http://dali.tanke756.top/Article/details/gthqmkxdbv.html

PHP:  exit(1);
来源：http://dali.sweek.top/Article/details/gtauduhnyj.html

JS:   process.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtooajopbz.html

TS:   process.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtteoakbcq.html

Java: System.exit(1)
来源：http://dali.fzhhl.top/Article/details/gtjkdsbzmo.html

Go:   os.Exit(1)
来源：http://dali.dashuyun.cn/Article/details/gtoykaryqr.html

Ruby: exit 1
来源：http://dali.chenzaomai.com/Article/details/gtznwhjall.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ppjwa.cn/Article/details/gtcghbfibp.html

[M06] 向标准错误输出
来源：http://dali.316326.xyz/Article/details/gtwqehedds.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj20258.top/Article/details/gtfreqgosz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yj20258.top/Article/details/gtmtxgeaxo.html

JS:   console.error("err")
来源：http://dali.hywenlv.cn/Article/details/gtcjnfmkhp.html

TS:   console.error("err")
来源：http://dali.chenlongwang.top/Article/details/gtxtqjipvn.html

Java: System.err.println("err")
来源：http://dali.ppjwa.cn/Article/details/gtmpgmziic.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yangfankeji.com/Article/details/gttuuyyubm.html

Ruby: warn "err"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvixdcdfr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.vqdsnc.cn/Article/details/gtkbgzcmqn.html

[M07] 判断是否为主入口
来源：http://dali.sxryk.cn/Article/details/gtllsfnvcp.html

Py:   if __name__ == "__main__":
来源：http://dali.nwbrower.top/Article/details/gtgbvimbwu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jlsjyb.cn/Article/details/gtyefmmcih.html

JS:   require.main === module
来源：http://dali.yonumen.top/Article/details/gthoswpxjl.html

TS:   require.main === module
来源：http://dali.quarkkingdee.top/Article/details/gtvrxfcfzl.html

Java: public static void main(String[] args)
来源：http://dali.sweek.top/Article/details/gthrtpolde.html

Go:   func main()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdmcxtkrm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gzhubu.top/Article/details/gtoqvtyanb.html

C#:   static void Main(string[] args)
来源：http://dali.zycfv.cn/Article/details/gtapihfpmp.html

[M08] 获取系统与运行时信息
来源：http://dali.cucudq.cn/Article/details/gttjdyymlo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.snrcjt.cn/Article/details/gteznvjgtu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ybcxt.top/Article/details/gtsdybtoce.html

JS:   process.platform;  process.version
来源：http://dali.ehwqpu.com/Article/details/gtworjynzj.html

TS:   process.platform;  process.version
来源：http://dali.jyoumei.cn/Article/details/gtwxbanqhp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gtnvyypcoh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shanyushiyangtech.top/Article/details/gtqdplztty.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.tian-w.cn/Article/details/gtczcynnti.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xziqi.cn/Article/details/gtadffcgox.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtnvltrxtr.html

N. 数据结构与算法
来源：http://dali.feifeiyinyue.top/Article/details/gtpopkpado.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtnyslhuqt.html

[N01] 二分查找（有序数组）
来源：http://dali.hnqzz.top/Article/details/gtombzojpi.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.316326.xyz/Article/details/gtwitrslfn.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.316326.xyz/Article/details/gtjfzvzctb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj202588.top/Article/details/gtocvlbhqw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cashguo.top/Article/details/gtexdtdraj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtdqlvumqi.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtydqsjthd.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.kuanghao11.cn/Article/details/gtbfvgmgsl.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gtsthjsirx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nanxuanxn.top/Article/details/gtgrhikaxc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtunrornhy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ivvv.top/Article/details/gtpvuqdxau.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aibaodan.cn/Article/details/gtazueicms.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.0kj1m.cn/Article/details/gtonjvkefg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.gzhubu.top/Article/details/gtplnetufe.html

Go:   slices.Sort(arr)
来源：http://dali.guannengcc.top/Article/details/gtpkbqklxz.html

Ruby: arr.sort
来源：http://dali.yuanzhike.top/Article/details/gtpmhobjvg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hywenlv.cn/Article/details/gtcpmpvqdh.html

[N03] 快速排序（分治示例）
来源：http://dali.nanxinkj.top/Article/details/gthgirvhge.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yanxiufei.cn/Article/details/gtjfltjoov.html

PHP:  // 递归实现，或用 usort
来源：http://dali.birdmap.top/Article/details/gtxqnkdaxv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hysaishi.cn/Article/details/gtgyoymowc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daxiang520.top/Article/details/gtxxwvzqgo.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ehwqpu.com/Article/details/gthmbpcnrp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.tianlin.xyz/Article/details/gthosqezxf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.nanxuanxn.top/Article/details/gtvxxxfkcz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tianlin.xyz/Article/details/gtsjphxbse.html

[N04] 斐波那契数列
来源：http://dali.kuanghao11.cn/Article/details/gtjsrtwgmb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.svipenyu.cn/Article/details/gtccqwyfke.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xinyue.icu/Article/details/gtyjqkqxuv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gtldkpavvv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gogol.net.cn/Article/details/gtmlgkugxa.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.andypj.xyz/Article/details/gtcderygsv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.daria6918.cn/Article/details/gtxbjfxyog.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhoulong.xyz/Article/details/gtkgfseigu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gtyeqgxebk.html

[N05] 最大公约数
来源：http://dali.fengsongda.top/Article/details/gtdtyyznwj.html

Py:   math.gcd(a, b)
来源：http://dali.chenzaomai.com/Article/details/gtzolufnbq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.daria6918.cn/Article/details/gtwbzqguhs.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xylfe.cn/Article/details/gtaggtldow.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuetiantiany.cn/Article/details/gtzjekpzmp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yj20258888.top/Article/details/gtzsuryohj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yueranfly.top/Article/details/gtmekdwkss.html

Ruby: a.gcd(b)
来源：http://dali.gzhubu.top/Article/details/gtatgngpup.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.9152youxi.cn/Article/details/gtjbipbpla.html

[N06] 判断回文字符串
来源：http://dali.chenlongwang.top/Article/details/gtmijzwyhc.html

Py:   s == s[::-1]
来源：http://dali.nanxinkj.top/Article/details/gtpkknxsne.html

PHP:  $s === strrev($s);
来源：http://dali.zhongyouzk.top/Article/details/gtaqkyonii.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtpvzibksp.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gtshdnoibd.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.quarkkingdee.top/Article/details/gtztsstmkc.html

Go:   // 双指针从两端比较
来源：http://dali.jianghu66.top/Article/details/gtppxlkqew.html

Ruby: s == s.reverse
来源：http://dali.ehwqpu.com/Article/details/gtxbnhknlh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.birdmap.top/Article/details/gtasyfomze.html

[N07] 两数之和（返回下标）
来源：http://dali.sysykeji.top/Article/details/gtnbwxyznl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xziqi.cn/Article/details/gtxqdkxinw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.daria6918.cn/Article/details/gtyjnojxsh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yanxiufei.cn/Article/details/gtucnyejpa.html

TS:   // 手写 Map<string, number>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwsgxmxwy.html

Java: // 手写 HashMap
来源：http://dali.aibaodan.cn/Article/details/gtpeeryerw.html

Go:   // 手写 map[int]int
来源：http://dali.bjfxy.top/Article/details/gteivpvkug.html

Ruby: // 手写 Hash
来源：http://dali.cheryme.top/Article/details/gtbzmrgovj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.mhx1999.top/Article/details/gtllaqqwgd.html

[N08] 生成全排列
来源：http://dali.yangfankeji.com/Article/details/gtrycjlubf.html

Py:   itertools.permutations(arr)
来源：http://dali.sweek.top/Article/details/gtppehbxir.html

PHP:  // 手写递归交换
来源：http://dali.cheryme.top/Article/details/gtgeicstni.html

JS:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gtxgpuweum.html

TS:   // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gtpgzskfdn.html

Java: // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gtlriiryzg.html

Go:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gtlbuyseaz.html

Ruby: arr.permutation.to_a
来源：http://dali.shanyushiyangtech.top/Article/details/gtlfqdtkwm.html

C#:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtppnfptpe.html

[N09] 栈与队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtczwcrsbm.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jqgufenzy.top/Article/details/gtdgjndekv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinqigfzy.top/Article/details/gttfmepypq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xziqi.cn/Article/details/gtomwyhcqe.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jqgufenzy.top/Article/details/gtogqsrarn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cucudq.cn/Article/details/gtkkvgeiyu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jqgfzy.top/Article/details/gtbkwccztm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.daria6918.cn/Article/details/gtornfyhwu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yueranfly.top/Article/details/gtmjmvvcgn.html

[N10] 链表节点定义
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyhtubxbk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tanke756.top/Article/details/gtsodwebyg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hammf.cn/Article/details/gtvttyysak.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jyoumei.cn/Article/details/gtghqpgfyk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.guowangkeji.top/Article/details/gtectvzwkh.html

Java: class Node { int v; Node next; }
来源：http://dali.dianchejie.cn/Article/details/gtjfshjvsp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yj202588.top/Article/details/gtobddkfbv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xinyue.icu/Article/details/gtwcrfllau.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.vqdsnc.cn/Article/details/gtzjttkuvn.html

[N11] 二叉树中序遍历
来源：http://dali.tian-w.cn/Article/details/gtukvkyjnj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yj20258888.top/Article/details/gtdurpejwu.html

PHP:  // 手写递归函数
来源：http://dali.zhixingplan.top/Article/details/gtgpndrdqk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxinkj.top/Article/details/gtfxkmlgry.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ybcxt.top/Article/details/gtxzpnqwyh.html

Java: // 手写递归
来源：http://dali.kuanghao11.cn/Article/details/gthgaqwnmp.html

Go:   // 手写递归
来源：http://dali.mhx1999.top/Article/details/gtnzssccqx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yonumen.top/Article/details/gtfjinsqjm.html

C#:   // 手写递归
来源：http://dali.ydzc1.top/Article/details/gtfloopyzo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yuxming.cn/Article/details/gtfbqhmsgs.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ivvv.top/Article/details/gtkplcthsy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.fzhhl.top/Article/details/gtjbraplxm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nwbrower.top/Article/details/gtlnlzxesd.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinqigufen.top/Article/details/gteehzbxjb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guannengcc.top/Article/details/gtftpnlrnx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.guowangkeji.top/Article/details/gthoxpsvyu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.snrcjt.cn/Article/details/gtusjzyzlj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aibaodan.cn/Article/details/gtikmnflse.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtqappjydm.html

O. 并发与异步
来源：http://dali.dianchejie.cn/Article/details/gtctxtoqiv.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtxqzqqsqb.html

[O01] 启动一个线程
来源：http://dali.jianghu66.top/Article/details/gtpkemqhtr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnkasyuvh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.bjfxy.top/Article/details/gtttfopmol.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinghuilouyu.cn/Article/details/gtshskzlip.html

TS:   // 同 JS
来源：http://dali.yanxiufei.cn/Article/details/gtfrqkzemw.html

Java: new Thread(() -> f()).start()
来源：http://dali.kuanghao11.cn/Article/details/gtnvywvydg.html

Go:   go f()
来源：http://dali.shuidangran.top/Article/details/gtopvrqhib.html

Ruby: Thread.new { f }
来源：http://dali.meibo888.top/Article/details/gtgxcauthf.html

C#:   Task.Run(() => F());
来源：http://dali.chenzaomai.com/Article/details/gtyyfpsetq.html

[O02] 使用线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gtkrvatbwd.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yueranfly.top/Article/details/gtpfvsdnng.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cucudq.cn/Article/details/gtqbsjsyod.html

JS:   // worker_threads 线程池
来源：http://dali.redwolf501.top/Article/details/gtdragqhdx.html

TS:   // worker_threads 线程池
来源：http://dali.sysykeji.top/Article/details/gtwjqatsnv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.svipenyu.cn/Article/details/gtanegwqdl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ppjwa.cn/Article/details/gtmogkeguw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shzxlz.cn/Article/details/gtqadhzgfz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.smart0.xyz/Article/details/gtatuhydhy.html

[O03] 加锁保护共享数据
来源：http://dali.c1oappe.top/Article/details/gtfnetxnnl.html

Py:   with lock: shared += 1
来源：http://dali.zhiwuduotai.top/Article/details/gtvakaidhv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shanyushiyangtech.top/Article/details/gtmbmagtfb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cucudq.cn/Article/details/gttxwylgyg.html

TS:   // 同 JS
来源：http://dali.chenzaomai.com/Article/details/gtedofguoq.html

Java: synchronized (this) { shared++; }
来源：http://dali.hysaishi.cn/Article/details/gtesyvqhtg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.daxiang520.top/Article/details/gtlixtzlbv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shzxlz.cn/Article/details/gtgsftolyb.html

C#:   lock (gate) { shared++; }
来源：http://dali.nanxinkj.top/Article/details/gtqnkczahe.html

[O04] 定义异步函数并等待
来源：http://dali.wangshuangyany.cn/Article/details/gtgpkpfmar.html

Py:   async def f():⏎    await g()
来源：http://dali.hnxiangtu.top/Article/details/gtphoecjug.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shzxlz.cn/Article/details/gtzhlwioyi.html

JS:   async function f() { await g(); }
来源：http://dali.iojbl.cn/Article/details/gtposqirbn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hfpthk.cn/Article/details/gtwlfmfsnf.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhongyouzk.top/Article/details/gtpcmxqqjb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.tianlin.xyz/Article/details/gtzvpkbnrh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hysaishi.cn/Article/details/gtwhjspmyu.html

C#:   async Task F() { await G(); }
来源：http://dali.sysykeji.top/Article/details/gtkgbpcawm.html

[O05] 并发执行并等待全部完成
来源：http://dali.ydzc1.top/Article/details/gtfpiwncpz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.dianchejie.cn/Article/details/gttzdzsyii.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xziqi.cn/Article/details/gttsdtnpwu.html

JS:   await Promise.all(tasks)
来源：http://dali.tanke756.top/Article/details/gtwbbquguj.html

TS:   await Promise.all(tasks)
来源：http://dali.ydzc1.top/Article/details/gteuizbtbf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cheryme.top/Article/details/gtrswrnwzr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.snrcjt.cn/Article/details/gtnoxlyomm.html

Ruby: threads.map(&:join)
来源：http://dali.ppjwa.cn/Article/details/gtldjhitzf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gzhubu.top/Article/details/gtusqbbwdn.html

[O06] 使用进程池
来源：http://dali.xinyue.icu/Article/details/gtvlguqllh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jiagoushi.top/Article/details/gtmnvenzzr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gzhubu.top/Article/details/gthxstovdi.html

JS:   // child_process / cluster 模块
来源：http://dali.redwolf501.top/Article/details/gtkajaqywt.html

TS:   // child_process / cluster 模块
来源：http://dali.kuanghao11.cn/Article/details/gtvxfrqdlb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ppjwa.cn/Article/details/gtcesoxrxt.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hnqzz.top/Article/details/gtddmkagvl.html

Ruby: // fork 块
来源：http://dali.bjfxy.top/Article/details/gtgtoizhnv.html

C#:   Parallel.For
来源：http://dali.hywenlv.cn/Article/details/gtrhbczmuf.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpaxozzsv.html

P. 常用工具函数
来源：http://dali.ehwqpu.com/Article/details/gtosumcelr.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gthikvdaeq.html

[P01] 生成 UUID
来源：http://dali.shanyushiyangtech.top/Article/details/gtwqyitasc.html

Py:   str(uuid.uuid4())
来源：http://dali.xinyue.icu/Article/details/gtykrdxyqv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tanke756.top/Article/details/gtbfkkwzpe.html

JS:   crypto.randomUUID()
来源：http://dali.zhongyouzk.top/Article/details/gtpszpizxf.html

TS:   crypto.randomUUID()
来源：http://dali.cashguo.top/Article/details/gthlncdrrb.html

Java: UUID.randomUUID().toString()
来源：http://dali.ybcxt.top/Article/details/gtygnbczfj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tian-w.cn/Article/details/gtikzqjiap.html

Ruby: SecureRandom.uuid
来源：http://dali.hnxiangtu.top/Article/details/gtlwpyyybi.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.dashuyun.cn/Article/details/gtvyhkudrr.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hongshengwenyu.top/Article/details/gthqdwsssv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.svipenyu.cn/Article/details/gtarcexewc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.guannengcc.top/Article/details/gtzarmhpdv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.pycfn.com/Article/details/gtyggsxlyj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxhnqawsp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj20258888.top/Article/details/gtgbtybsyu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.wangshuangyany.cn/Article/details/gtbqaqsxwy.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.iojbl.cn/Article/details/gtzdpfgqvd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.dashuyun.cn/Article/details/gtdblctnyu.html

[P03] 生成短随机字符串
来源：http://dali.andypj.xyz/Article/details/gtzkbzlrvv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.wangdashe.top/Article/details/gtznpzhuzu.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jqgufenzy.top/Article/details/gtyhjqtxrc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gtitwhinjr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yuanzhike.top/Article/details/gtrgydcvio.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtuyxziffi.html


<!-- 参考信息 -->