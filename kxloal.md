代发 wailian999

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.nwbrower.top/Article/details/gthekudpwo.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.chenzaomai.com/Article/details/gtuqcvxiil.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cucudq.cn/Article/details/gtphlrdmyu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ybcxt.top/Article/details/gtnoezdpui.html

[L07] 处理 HTTP 状态码
来源：http://dali.hysaishi.cn/Article/details/gtmbnzudlo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.pengpengdd.cyou/Article/details/gtipesmyxm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hywenlv.cn/Article/details/gtphdmjtaz.html

JS:   resp.ok;  resp.status
来源：http://dali.yonumen.top/Article/details/gtcsvdmhsl.html

TS:   resp.ok;  resp.status
来源：http://dali.svipenyu.cn/Article/details/gtfdxzywrd.html

Java: resp.statusCode()
来源：http://dali.kuanghao11.cn/Article/details/gtsnkivbjv.html

Go:   resp.StatusCode
来源：http://dali.zhiwuduotai.top/Article/details/gtcbqikucp.html

Ruby: resp.code.to_i
来源：http://dali.nanxuanxn.top/Article/details/gtlimiiyac.html

C#:   (int)resp.StatusCode
来源：http://dali.redwolf501.top/Article/details/gtdywzmmyg.html

[L08] 并发请求多个地址
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfckkxzjv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.quarkkingdee.top/Article/details/gtxtkrsodd.html

PHP:  curl_multi_init() 系列
来源：http://dali.tianlin.xyz/Article/details/gthltgtufw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.smart0.xyz/Article/details/gtpwwkydxq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.9152youxi.cn/Article/details/gtmarxhosg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.smart0.xyz/Article/details/gtuexghbcw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.dashuyun.cn/Article/details/gtckivwnjz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xziqi.cn/Article/details/gtjnqtxmrj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xinyue.icu/Article/details/gtcarlxkjw.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtdblrgcir.html

M. 命令行 / 进程 / 环境
来源：http://dali.gzhubu.top/Article/details/gtyknmovpr.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtaffyzosn.html

[M01] 读取命令行参数
来源：http://dali.svipenyu.cn/Article/details/gtmaagmait.html

Py:   sys.argv[1:]
来源：http://dali.dianchejie.cn/Article/details/gtdcgifabw.html

PHP:  $argv;  $argc;
来源：http://dali.daria6918.cn/Article/details/gtlzfzftaq.html

JS:   process.argv.slice(2)
来源：http://dali.jinqigufen.top/Article/details/gtfcbukooc.html

TS:   process.argv.slice(2)
来源：http://dali.mhx1999.top/Article/details/gtwlpfhwnw.html

Java: args 数组（main 方法参数）
来源：http://dali.pengpengdd.cyou/Article/details/gtliylbykb.html

Go:   os.Args[1:]
来源：http://dali.jinqigufen.top/Article/details/gtgdxfyyos.html

Ruby: ARGV
来源：http://dali.cqqwz.cn/Article/details/gtybvahsvi.html

C#:   args 数组（Main 方法参数）
来源：http://dali.guannengcc.top/Article/details/gtjbrisghy.html

[M02] 读取环境变量
来源：http://dali.nwbrower.top/Article/details/gtpilamrsz.html

Py:   os.environ.get("HOME")
来源：http://dali.yj202588.top/Article/details/gtsxaxxdhz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tian-w.cn/Article/details/gtxnfauswa.html

JS:   process.env.HOME
来源：http://dali.zhengqikj.top/Article/details/gtuhzxzwcf.html

TS:   process.env.HOME
来源：http://dali.svipenyu.cn/Article/details/gtmqoqqlnl.html

Java: System.getenv("HOME")
来源：http://dali.hfpthk.cn/Article/details/gtbosipufb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zycfv.cn/Article/details/gthtvjmymf.html

Ruby: ENV["HOME"]
来源：http://dali.yuxming.cn/Article/details/gtplmkzxkc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.fzhhl.top/Article/details/gtawkiafyd.html

[M03] 执行外部命令
来源：http://dali.tian-w.cn/Article/details/gtmmszxgjl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ybcxt.top/Article/details/gtmmcyifxf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinghuilouyu.cn/Article/details/gtlvzgwzrj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.guannengcc.top/Article/details/gtwsimubkw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxuanxn.top/Article/details/gtvmtpqgsj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ydzc1.top/Article/details/gttfawmozd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yanxiufei.cn/Article/details/gtdvnmncul.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.0kj1m.cn/Article/details/gtoytnmbaq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yvedp.cn/Article/details/gtclbvzvwa.html

[M04] 获取当前工作目录
来源：http://dali.bjfxy.top/Article/details/gtxvbckfax.html

Py:   os.getcwd()
来源：http://dali.hammf.cn/Article/details/gtmibamwfx.html

PHP:  getcwd();
来源：http://dali.dianchejie.cn/Article/details/gtjhbzrhgt.html

JS:   process.cwd()
来源：http://dali.jianghu66.top/Article/details/gthrexiwyr.html

TS:   process.cwd()
来源：http://dali.jyoumei.cn/Article/details/gtglhxthcl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yvedp.cn/Article/details/gtdbjaiihj.html

Go:   os.Getwd()
来源：http://dali.c1oappe.top/Article/details/gtvpxywsea.html

Ruby: Dir.pwd
来源：http://dali.yj20258.top/Article/details/gtqydhfrlt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sysykeji.top/Article/details/gtubgcszop.html

[M05] 设置退出码
来源：http://dali.daria6918.cn/Article/details/gtljnabjdq.html

Py:   sys.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gtbwywqliw.html

PHP:  exit(1);
来源：http://dali.sysykeji.top/Article/details/gtrutgnggu.html

JS:   process.exit(1)
来源：http://dali.yj202588.top/Article/details/gtrjbgsunp.html

TS:   process.exit(1)
来源：http://dali.sxryk.cn/Article/details/gtbccquivx.html

Java: System.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtfkhzrqgg.html

Go:   os.Exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtgdmnwihe.html

Ruby: exit 1
来源：http://dali.havefunace.top/Article/details/gtwedvymlh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jlsjyb.cn/Article/details/gturxkyoxq.html

[M06] 向标准错误输出
来源：http://dali.yangfankeji.com/Article/details/gtjpnunqgl.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ydzc1.top/Article/details/gtdkqmgoso.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ydzc1.top/Article/details/gtdfqeidzf.html

JS:   console.error("err")
来源：http://dali.yongpay.top/Article/details/gtqqnwltie.html

TS:   console.error("err")
来源：http://dali.9152youxi.cn/Article/details/gtrbojmpve.html

Java: System.err.println("err")
来源：http://dali.fengsongda.top/Article/details/gtkhpqulnn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.smart0.xyz/Article/details/gtynjunxqv.html

Ruby: warn "err"
来源：http://dali.hnqzz.top/Article/details/gtiodyzyos.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinqigfzy.top/Article/details/gtwrqruowo.html

[M07] 判断是否为主入口
来源：http://dali.ydzc1.top/Article/details/gtordfungi.html

Py:   if __name__ == "__main__":
来源：http://dali.gaohongyu789.top/Article/details/gttbhmlgqb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.tanke756.top/Article/details/gtbnxnaoub.html

JS:   require.main === module
来源：http://dali.daxiang520.top/Article/details/gthvbyukvv.html

TS:   require.main === module
来源：http://dali.tian-w.cn/Article/details/gtolbrisdu.html

Java: public static void main(String[] args)
来源：http://dali.guowangkeji.top/Article/details/gtvidwxkfi.html

Go:   func main()
来源：http://dali.havefunace.top/Article/details/gtxypgyvxs.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shuidangran.top/Article/details/gtxklzfxrz.html

C#:   static void Main(string[] args)
来源：http://dali.xylfe.cn/Article/details/gtyadmtnbw.html

[M08] 获取系统与运行时信息
来源：http://dali.chenzaomai.com/Article/details/gtvktajmef.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jiagoushi.top/Article/details/gtogvmfpfk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yangfankeji.com/Article/details/gtfgcbmnpo.html

JS:   process.platform;  process.version
来源：http://dali.jqgfzy.top/Article/details/gtwrlmzzzh.html

TS:   process.platform;  process.version
来源：http://dali.daxiang520.top/Article/details/gtzmzzxtcv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hysaishi.cn/Article/details/gthncfistc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.svipenyu.cn/Article/details/gtqvtfyrec.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hnxiangtu.top/Article/details/gtzvkcxsil.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hongshengwenyu.top/Article/details/gtpuiepezi.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtlzhjkbcp.html

N. 数据结构与算法
来源：http://dali.xuanzx.com/Article/details/gtmfujweuj.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtwxggkvkl.html

[N01] 二分查找（有序数组）
来源：http://dali.hongshengwenyu.top/Article/details/gtqllciygd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtnfjleadu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cucudq.cn/Article/details/gtxecoysjl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pycfn.com/Article/details/gtlmiyqqqg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yangfankeji.com/Article/details/gtfmcvczvh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtlgobsppo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtmutvktla.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinqigfzy.top/Article/details/gtsxktdkrv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.fzhhl.top/Article/details/gtjwkafwiz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinqigufen.top/Article/details/gtsdgdlmhm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hongshengwenyu.top/Article/details/gtwefokebe.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.feifeiyinyue.top/Article/details/gtqhttbhat.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nwbrower.top/Article/details/gtraygnitl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aizwys.cn/Article/details/gtnpjjcupb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hnxiangtu.top/Article/details/gtbqajngjn.html

Go:   slices.Sort(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuwqbizwk.html

Ruby: arr.sort
来源：http://dali.quarkkingdee.top/Article/details/gtricmfinh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jqgfzy.top/Article/details/gtqlimgaep.html

[N03] 快速排序（分治示例）
来源：http://dali.jinghuilouyu.cn/Article/details/gtkkqqbrlv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.wangshuangyany.cn/Article/details/gtrayvoroj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gtcfaumpdt.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigufen.top/Article/details/gtaifkxwmf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ybcxt.top/Article/details/gtgpvudskt.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.aizwys.cn/Article/details/gtpyapasth.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gtugkyysfk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yj20258.top/Article/details/gtyonupfmy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.fzhhl.top/Article/details/gtytxobrlv.html

[N04] 斐波那契数列
来源：http://dali.gaohongyu789.top/Article/details/gtpvvvlxhx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.tanke756.top/Article/details/gtlbryjpgq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hfpthk.cn/Article/details/gtssfcdmwe.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daxiang520.top/Article/details/gtjucldknk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gtlxbvovgq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.pycfn.com/Article/details/gtklypyinw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.gotoacloud.top/Article/details/gtsmunsmzn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.nanxinkj.top/Article/details/gtwkfkedje.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.tian-w.cn/Article/details/gtbeslgyli.html

[N05] 最大公约数
来源：http://dali.xuetiantiany.cn/Article/details/gtibjuifbs.html

Py:   math.gcd(a, b)
来源：http://dali.hysaishi.cn/Article/details/gtgiqasiep.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hysaishi.cn/Article/details/gtsjeffinh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.316326.xyz/Article/details/gtuhcrqros.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhongyouzk.top/Article/details/gtiqrgucyi.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yanxiufei.cn/Article/details/gtvsircjok.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.andypj.xyz/Article/details/gtiwpyrhdh.html

Ruby: a.gcd(b)
来源：http://dali.jiagoushi.top/Article/details/gtlypxtpgw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sxryk.cn/Article/details/gtblhrhzlw.html

[N06] 判断回文字符串
来源：http://dali.sxryk.cn/Article/details/gtcunyninb.html

Py:   s == s[::-1]
来源：http://dali.feifeiyinyue.top/Article/details/gtiiaqruul.html

PHP:  $s === strrev($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtzmtdasfv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.fengsongda.top/Article/details/gtkdkzitrs.html

TS:   s === [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gteqvsuinn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ybcxt.top/Article/details/gteivaglfi.html

Go:   // 双指针从两端比较
来源：http://dali.kuanghao11.cn/Article/details/gtigmydxau.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gtazmkuymr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.pycfn.com/Article/details/gtmfpvgmpe.html

[N07] 两数之和（返回下标）
来源：http://dali.hnxiangtu.top/Article/details/gtmcygjlot.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hnqzz.top/Article/details/gtwuwmjruf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.9152youxi.cn/Article/details/gtffmjztct.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hnxiangtu.top/Article/details/gtfwurgiqr.html

TS:   // 手写 Map<string, number>
来源：http://dali.sysykeji.top/Article/details/gtcgotesmc.html

Java: // 手写 HashMap
来源：http://dali.yongpay.top/Article/details/gtqaexlkcq.html

Go:   // 手写 map[int]int
来源：http://dali.wangdashe.top/Article/details/gtjhavtsxe.html

Ruby: // 手写 Hash
来源：http://dali.shanyushiyangtech.top/Article/details/gtevrlrnyi.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.tian-w.cn/Article/details/gttwkrvrex.html

[N08] 生成全排列
来源：http://dali.jinghuilouyu.cn/Article/details/gtxgpfcdql.html

Py:   itertools.permutations(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gttmddhfqx.html

PHP:  // 手写递归交换
来源：http://dali.zhiwuduotai.top/Article/details/gtwbauytan.html

JS:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gtithzzhfv.html

TS:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtgdspkzwa.html

Java: // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gtcpxyteyf.html

Go:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gtayjvhkji.html

Ruby: arr.permutation.to_a
来源：http://dali.yueranfly.top/Article/details/gtrcxzxqer.html

C#:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtsvdvsmxy.html

[N09] 栈与队列
来源：http://dali.yangfankeji.com/Article/details/gtysujblou.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yuxming.cn/Article/details/gtwdpujbzt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sysykeji.top/Article/details/gtqblfhrrk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.andypj.xyz/Article/details/gtiboudvxp.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.meibo888.top/Article/details/gtipfkhwfl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.nwbrower.top/Article/details/gtnzbmjhdh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gaohongyu789.top/Article/details/gtncrdwmln.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jiagoushi.top/Article/details/gtayishxkh.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gogol.net.cn/Article/details/gthrbifphm.html

[N10] 链表节点定义
来源：http://dali.sysykeji.top/Article/details/gtnclaoonh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhengqikj.top/Article/details/gtdnbpyrus.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.guannengcc.top/Article/details/gttrxpfehp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hongshengwenyu.top/Article/details/gtgrcppeov.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yonumen.top/Article/details/gthyupbqpc.html

Java: class Node { int v; Node next; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzwfairol.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.nanxinkj.top/Article/details/gtrhmpxlvu.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.bjfxy.top/Article/details/gtajblxobe.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zdqjudy.top/Article/details/gtbuaertqy.html

[N11] 二叉树中序遍历
来源：http://dali.yuanzhike.top/Article/details/gtgzmnlnim.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sweek.top/Article/details/gtjxxogzzo.html

PHP:  // 手写递归函数
来源：http://dali.meibo888.top/Article/details/gtgfuvhjnz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigfzy.top/Article/details/gtdzarciak.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigfzy.top/Article/details/gtzcpyqfeq.html

Java: // 手写递归
来源：http://dali.9152youxi.cn/Article/details/gtivlitdst.html

Go:   // 手写递归
来源：http://dali.pycfn.com/Article/details/gtupqjnvip.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yj20258.top/Article/details/gtqbhiwbuu.html

C#:   // 手写递归
来源：http://dali.yuxming.cn/Article/details/gtbmkseios.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.kuanghao11.cn/Article/details/gtrgqekxvx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ydzc1.top/Article/details/gtvmybaqtj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.dashuyun.cn/Article/details/gtvksumnmz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cdnleiting.top/Article/details/gtezodapuw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xylfe.cn/Article/details/gtgmqqlchu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yvedp.cn/Article/details/gtunbnmaod.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cheryme.top/Article/details/gtrkpwslsk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.aibaodan.cn/Article/details/gtyuytbrpd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuxming.cn/Article/details/gturcywikd.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtznziviik.html

O. 并发与异步
来源：http://dali.gogol.net.cn/Article/details/gtrpyxjxsn.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtmpdcrzyk.html

[O01] 启动一个线程
来源：http://dali.yj20258888.top/Article/details/gtkzkxxsww.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ybcxt.top/Article/details/gtgtpyxjbg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gtkfgscnlo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cashguo.top/Article/details/gtskvihidp.html

TS:   // 同 JS
来源：http://dali.jianghu66.top/Article/details/gtfnhpdqcc.html

Java: new Thread(() -> f()).start()
来源：http://dali.pycfn.com/Article/details/gtyicgenmn.html

Go:   go f()
来源：http://dali.xylfe.cn/Article/details/gtmpkkwumi.html

Ruby: Thread.new { f }
来源：http://dali.yongpay.top/Article/details/gtqohnfpaz.html

C#:   Task.Run(() => F());
来源：http://dali.birdmap.top/Article/details/gttkmeefct.html

[O02] 使用线程池
来源：http://dali.gotoacloud.top/Article/details/gtvqkunwzh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.c1oappe.top/Article/details/gtotolbzpb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shzxlz.cn/Article/details/gtoezuznmv.html

JS:   // worker_threads 线程池
来源：http://dali.hywenlv.cn/Article/details/gtnulqpjvq.html

TS:   // worker_threads 线程池
来源：http://dali.aizwys.cn/Article/details/gtzjnnopxo.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.bjfxy.top/Article/details/gtvtxcokjz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.316326.xyz/Article/details/gtqhtxtuev.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.pycfn.com/Article/details/gtmmcphnot.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yj20258.top/Article/details/gtbvbluunj.html

[O03] 加锁保护共享数据
来源：http://dali.jqgfzy.top/Article/details/gtolnxplth.html

Py:   with lock: shared += 1
来源：http://dali.haohaochexian.top/Article/details/gtexagdolc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhoulong.xyz/Article/details/gtrypqgaih.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cdnleiting.top/Article/details/gtsoqsnhan.html

TS:   // 同 JS
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqwreopxv.html

Java: synchronized (this) { shared++; }
来源：http://dali.yonumen.top/Article/details/gtwyospzwg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hammf.cn/Article/details/gtqoaljfqj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xylfe.cn/Article/details/gtocooztss.html

C#:   lock (gate) { shared++; }
来源：http://dali.cdnleiting.top/Article/details/gtpiywwfsm.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gtobwwmsob.html

Py:   async def f():⏎    await g()
来源：http://dali.yuxming.cn/Article/details/gtyezzkpye.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.quarkkingdee.top/Article/details/gtelwoxgtt.html

JS:   async function f() { await g(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtowfxjoqv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hnxiangtu.top/Article/details/gtntbudmlw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hnxiangtu.top/Article/details/gtczztsapx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hongshengwenyu.top/Article/details/gtwbpswdte.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xziqi.cn/Article/details/gtgwuqcbnz.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gtpprtgwfp.html

[O05] 并发执行并等待全部完成
来源：http://dali.jiagoushi.top/Article/details/gthlewtpvx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shangyingyoupin.top/Article/details/gtfcqelnyd.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zycfv.cn/Article/details/gtflysgggu.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gtyqhnwsdv.html

TS:   await Promise.all(tasks)
来源：http://dali.jqgufenzy.top/Article/details/gtcdtpswve.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ybcxt.top/Article/details/gtndzfyswu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gtzwsxxluy.html

Ruby: threads.map(&:join)
来源：http://dali.ybcxt.top/Article/details/gtszznmfod.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.guowangkeji.top/Article/details/gtpkewunup.html

[O06] 使用进程池
来源：http://dali.xziqi.cn/Article/details/gtwgqoturk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hnqzz.top/Article/details/gtcxjkqtjc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zycfv.cn/Article/details/gtbpoqdgcm.html

JS:   // child_process / cluster 模块
来源：http://dali.zhengqikj.top/Article/details/gtnpwshmsd.html

TS:   // child_process / cluster 模块
来源：http://dali.sufxvd.cn/Article/details/gtqgjdgnwy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hammf.cn/Article/details/gtedgzrzko.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.pengpengdd.cyou/Article/details/gtmqytomdm.html

Ruby: // fork 块
来源：http://dali.yvedp.cn/Article/details/gtsxavziir.html

C#:   Parallel.For
来源：http://dali.c1oappe.top/Article/details/gtotgdsfgy.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gthemjbauy.html

P. 常用工具函数
来源：http://dali.nanxuanxn.top/Article/details/gtywtbsrhx.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtzjdhcatk.html

[P01] 生成 UUID
来源：http://dali.gogol.net.cn/Article/details/gtqugrjztn.html

Py:   str(uuid.uuid4())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjommbxnd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xinyue.icu/Article/details/gttahtbclu.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gtyxzfwqqr.html

TS:   crypto.randomUUID()
来源：http://dali.xuanzx.com/Article/details/gtnlmtqaac.html

Java: UUID.randomUUID().toString()
来源：http://dali.gaohongyu789.top/Article/details/gtvqnlukqh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.chenzaomai.com/Article/details/gtdrjtghuf.html

Ruby: SecureRandom.uuid
来源：http://dali.xuanzx.com/Article/details/gtqccvuxet.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.quarkkingdee.top/Article/details/gtkgaavknz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.meibo888.top/Article/details/gtvzfsnhfk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.wangdashe.top/Article/details/gtqzkwgowe.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sufxvd.cn/Article/details/gtkebdppnd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gzhubu.top/Article/details/gtjvvaqwgw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlukcfxyt.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.9152youxi.cn/Article/details/gtsjeaygnt.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.feifeiyinyue.top/Article/details/gtkjsyzdjg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrtejotsz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hnxiangtu.top/Article/details/gtlzvczawq.html

[P03] 生成短随机字符串
来源：http://dali.sweek.top/Article/details/gttkxzdomp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.havefunace.top/Article/details/gtzpqaqixa.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ppjwa.cn/Article/details/gtljscdyac.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtiwntptai.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.iojbl.cn/Article/details/gtcimofwnf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cqqwz.cn/Article/details/gtjfvdpwzj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwrocsdik.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.wangdashe.top/Article/details/gtjnwevxls.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.kuanghao11.cn/Article/details/gtjcnuevga.html

[P04] 求长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbubdktpi.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbgptebfz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gtqxrhinjk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guannengcc.top/Article/details/gtqkporlsv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yonumen.top/Article/details/gtpoalgntd.html


<!-- 参考信息 -->