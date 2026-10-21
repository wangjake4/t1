代发 wailian999

[L07] 处理 HTTP 状态码
来源：http://dali.jiagoushi.top/Article/details/gtsymokgnz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj20258888.top/Article/details/gtgktrfnqz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinghuilouyu.cn/Article/details/gtjpbjezxz.html

JS:   resp.ok;  resp.status
来源：http://dali.quarkkingdee.top/Article/details/gtfikxuwwm.html

TS:   resp.ok;  resp.status
来源：http://dali.wangdashe.top/Article/details/gtguwualwe.html

Java: resp.statusCode()
来源：http://dali.ybcxt.top/Article/details/gtsyrgezgc.html

Go:   resp.StatusCode
来源：http://dali.iojbl.cn/Article/details/gthqcrsdsf.html

Ruby: resp.code.to_i
来源：http://dali.zhoulong.xyz/Article/details/gtjttjqbck.html

C#:   (int)resp.StatusCode
来源：http://dali.gzhubu.top/Article/details/gtyzbadciv.html

[L08] 并发请求多个地址
来源：http://dali.birdmap.top/Article/details/gtzcxqmhln.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinqigfzy.top/Article/details/gtgkkvibhq.html

PHP:  curl_multi_init() 系列
来源：http://dali.yj202588.top/Article/details/gtnlphlzsu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hammf.cn/Article/details/gtjhvzhrpg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ivvv.top/Article/details/gtxxrclntj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj20258.top/Article/details/gtxhoahfxn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xziqi.cn/Article/details/gtaflojaeb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xinyue.icu/Article/details/gtukoanppj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jyoumei.cn/Article/details/gtzamicjgt.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtmmiwauhq.html

M. 命令行 / 进程 / 环境
来源：http://dali.ydzc1.top/Article/details/gtftdjubrm.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gthyqhttfm.html

[M01] 读取命令行参数
来源：http://dali.guowangkeji.top/Article/details/gtnqpsvces.html

Py:   sys.argv[1:]
来源：http://dali.yuanzhike.top/Article/details/gtdexdafvr.html

PHP:  $argv;  $argc;
来源：http://dali.nanxinkj.top/Article/details/gtejiwcqtr.html

JS:   process.argv.slice(2)
来源：http://dali.0kj1m.cn/Article/details/gtyghismzn.html

TS:   process.argv.slice(2)
来源：http://dali.andypj.xyz/Article/details/gtkbnrzzuc.html

Java: args 数组（main 方法参数）
来源：http://dali.daria6918.cn/Article/details/gtdpyobcdj.html

Go:   os.Args[1:]
来源：http://dali.zycfv.cn/Article/details/gtlzyxndmp.html

Ruby: ARGV
来源：http://dali.yj202588.top/Article/details/gtemyajyxj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.tianlin.xyz/Article/details/gtczoibzil.html

[M02] 读取环境变量
来源：http://dali.nanxinkj.top/Article/details/gtsuuzieyn.html

Py:   os.environ.get("HOME")
来源：http://dali.hfpthk.cn/Article/details/gtqmplywjr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuotcbkcs.html

JS:   process.env.HOME
来源：http://dali.cucudq.cn/Article/details/gtkoxdmfoe.html

TS:   process.env.HOME
来源：http://dali.sysykeji.top/Article/details/gtxhlbcgiy.html

Java: System.getenv("HOME")
来源：http://dali.tanke756.top/Article/details/gtpxfmwxnf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvrbhmmeq.html

Ruby: ENV["HOME"]
来源：http://dali.guowangkeji.top/Article/details/gtlelbpowl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gtzzwgkkri.html

[M03] 执行外部命令
来源：http://dali.nanxinkj.top/Article/details/gturbaszqc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.havefunace.top/Article/details/gthwbslolf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinqigufen.top/Article/details/gtmormefrq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.snrcjt.cn/Article/details/gtgnuzdasg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.9152youxi.cn/Article/details/gtssvxpgzj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yvedp.cn/Article/details/gtfcbefjfs.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.pengpengdd.cyou/Article/details/gtctwytrdj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hywenlv.cn/Article/details/gtqwsgrfvr.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinqigufen.top/Article/details/gtroysilpy.html

[M04] 获取当前工作目录
来源：http://dali.guannengcc.top/Article/details/gtdvnougsn.html

Py:   os.getcwd()
来源：http://dali.ivvv.top/Article/details/gtvjhancue.html

PHP:  getcwd();
来源：http://dali.tianlin.xyz/Article/details/gtvuaxpxpr.html

JS:   process.cwd()
来源：http://dali.shzxlz.cn/Article/details/gtpvfmuhyk.html

TS:   process.cwd()
来源：http://dali.guannengcc.top/Article/details/gtyaktyfwp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.iojbl.cn/Article/details/gtolsxrtud.html

Go:   os.Getwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfxbkjlsa.html

Ruby: Dir.pwd
来源：http://dali.gogol.net.cn/Article/details/gtxvdjeacw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.daria6918.cn/Article/details/gtdfcowsfh.html

[M05] 设置退出码
来源：http://dali.yuanzhike.top/Article/details/gtuczexitw.html

Py:   sys.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gtkyyxmtas.html

PHP:  exit(1);
来源：http://dali.wangshuangyany.cn/Article/details/gtctktgyqu.html

JS:   process.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gtlqtvprem.html

TS:   process.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gtonozmoms.html

Java: System.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtubnatnlv.html

Go:   os.Exit(1)
来源：http://dali.yangfankeji.com/Article/details/gtitcjhqvz.html

Ruby: exit 1
来源：http://dali.zhoulong.xyz/Article/details/gtflyepkds.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xuetiantiany.cn/Article/details/gtvwyzlmko.html

[M06] 向标准错误输出
来源：http://dali.9152youxi.cn/Article/details/gtxqyugqve.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinqigufen.top/Article/details/gtwccvprii.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jianghu66.top/Article/details/gtprvonqcu.html

JS:   console.error("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gtkokjumsz.html

TS:   console.error("err")
来源：http://dali.dianchejie.cn/Article/details/gtxzyhhfbg.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gtxgpulsuq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xylfe.cn/Article/details/gtdjdotcjn.html

Ruby: warn "err"
来源：http://dali.shzxlz.cn/Article/details/gtimwluvno.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sufxvd.cn/Article/details/gtcftfmnub.html

[M07] 判断是否为主入口
来源：http://dali.hfpthk.cn/Article/details/gtfbblauay.html

Py:   if __name__ == "__main__":
来源：http://dali.tianlin.xyz/Article/details/gtivwgraqm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.pycfn.com/Article/details/gtxubqtqnm.html

JS:   require.main === module
来源：http://dali.tian-w.cn/Article/details/gtoqczjfqh.html

TS:   require.main === module
来源：http://dali.iojbl.cn/Article/details/gtbiymbbcj.html

Java: public static void main(String[] args)
来源：http://dali.sysykeji.top/Article/details/gtklslucjz.html

Go:   func main()
来源：http://dali.xylfe.cn/Article/details/gtdqhmlreu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpxdideej.html

C#:   static void Main(string[] args)
来源：http://dali.sufxvd.cn/Article/details/gtsjshjwbx.html

[M08] 获取系统与运行时信息
来源：http://dali.jinghuilouyu.cn/Article/details/gtcvmcwqjk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.haohaochexian.top/Article/details/gtwxpvdike.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.chenzaomai.com/Article/details/gtrdmwrlzg.html

JS:   process.platform;  process.version
来源：http://dali.chenzaomai.com/Article/details/gtftntleja.html

TS:   process.platform;  process.version
来源：http://dali.vqdsnc.cn/Article/details/gtkcrfysvd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xziqi.cn/Article/details/gtatbgnktq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shuidangran.top/Article/details/gtysfwzfcg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yuanzhike.top/Article/details/gtrxghwgdr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tianlin.xyz/Article/details/gtalqhpfhq.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gthlzsruqj.html

N. 数据结构与算法
来源：http://dali.sysykeji.top/Article/details/gtbwczicpl.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtdeepljdp.html

[N01] 二分查找（有序数组）
来源：http://dali.jianghu66.top/Article/details/gtmydhayql.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hammf.cn/Article/details/gttbqcshjq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.haohaochexian.top/Article/details/gtffcdiben.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zdqjudy.top/Article/details/gtfwuidyoo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cucudq.cn/Article/details/gtbmtrijsy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtsdwbulkv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.tanke756.top/Article/details/gtlpglexkm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jlsjyb.cn/Article/details/gtvuinofjs.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtikjlpylh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinqigufen.top/Article/details/gtwvnqyzze.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sweek.top/Article/details/gtkqdmsbbf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.pycfn.com/Article/details/gtgmaxkmmb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.haohaochexian.top/Article/details/gtplzyuemp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuxming.cn/Article/details/gtfjfpwwkk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.fengsongda.top/Article/details/gtpalteqdl.html

Go:   slices.Sort(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtczgcrmap.html

Ruby: arr.sort
来源：http://dali.birdmap.top/Article/details/gtpykelphy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.chenjidiqi.icu/Article/details/gtieqkviwn.html

[N03] 快速排序（分治示例）
来源：http://dali.shangyingyoupin.top/Article/details/gtbrwgctcd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yanxiufei.cn/Article/details/gtmqvsqiwx.html

PHP:  // 递归实现，或用 usort
来源：http://dali.9152youxi.cn/Article/details/gttwehwmwh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jyoumei.cn/Article/details/gtuvvqjzsc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.meibo888.top/Article/details/gtrzwbmics.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shzxlz.cn/Article/details/gtwwqxllcf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yuxming.cn/Article/details/gtvhstmdkh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhixingplan.top/Article/details/gtmaupozho.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gtktpjtxhe.html

[N04] 斐波那契数列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnfgpaecr.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.aizwys.cn/Article/details/gttlihfyep.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.nanxuanxn.top/Article/details/gtadqdkzfg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yonumen.top/Article/details/gtpduezrpq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnqzz.top/Article/details/gtfjtxhcns.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hongshengwenyu.top/Article/details/gtpsdnqugi.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.quarkkingdee.top/Article/details/gtrqgudfbs.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hnqzz.top/Article/details/gtbdripsva.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gtllgbikmx.html

[N05] 最大公约数
来源：http://dali.ydzc1.top/Article/details/gtzjkfqgzf.html

Py:   math.gcd(a, b)
来源：http://dali.haohaochexian.top/Article/details/gtlomcfnls.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gaohongyu789.top/Article/details/gttsrjzpva.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yanxiufei.cn/Article/details/gtwjyalujf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fengsongda.top/Article/details/gtuagevngi.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hnqzz.top/Article/details/gtrttjuoul.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yanxiufei.cn/Article/details/gtkihdvmmq.html

Ruby: a.gcd(b)
来源：http://dali.ivvv.top/Article/details/gtzflsgnlt.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.guowangkeji.top/Article/details/gtuxskbcbp.html

[N06] 判断回文字符串
来源：http://dali.dianchejie.cn/Article/details/gtrkvglcgl.html

Py:   s == s[::-1]
来源：http://dali.yuxming.cn/Article/details/gtsqqkybwp.html

PHP:  $s === strrev($s);
来源：http://dali.vqdsnc.cn/Article/details/gtlcaavltc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gtrfwhkxpc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gtjdvvqijj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shangyingyoupin.top/Article/details/gtvfmceqpt.html

Go:   // 双指针从两端比较
来源：http://dali.feifeiyinyue.top/Article/details/gtcrzjvrfl.html

Ruby: s == s.reverse
来源：http://dali.shzxlz.cn/Article/details/gtqzlvxfdu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.fzhhl.top/Article/details/gteohhxzgu.html

[N07] 两数之和（返回下标）
来源：http://dali.hfpthk.cn/Article/details/gtwkzszyry.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.wangshuangyany.cn/Article/details/gtyomdeyov.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.haohaochexian.top/Article/details/gtwgrjfmab.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.smart0.xyz/Article/details/gtrilbnlek.html

TS:   // 手写 Map<string, number>
来源：http://dali.cheryme.top/Article/details/gtditlhebg.html

Java: // 手写 HashMap
来源：http://dali.jqgfzy.top/Article/details/gtkxtskden.html

Go:   // 手写 map[int]int
来源：http://dali.hnxiangtu.top/Article/details/gtlodwzvyz.html

Ruby: // 手写 Hash
来源：http://dali.wangdashe.top/Article/details/gtceabnxjj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shanyushiyangtech.top/Article/details/gtqcyxgcvq.html

[N08] 生成全排列
来源：http://dali.c1oappe.top/Article/details/gtvthrvlzm.html

Py:   itertools.permutations(arr)
来源：http://dali.9152youxi.cn/Article/details/gtlhzsulfo.html

PHP:  // 手写递归交换
来源：http://dali.c1oappe.top/Article/details/gtymluasfu.html

JS:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gtyrfhdtlw.html

TS:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtixtzlbxm.html

Java: // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gtouvtrhfs.html

Go:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtzhkeqmho.html

Ruby: arr.permutation.to_a
来源：http://dali.zhixingplan.top/Article/details/gtjwztuzhn.html

C#:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gtiiybgloi.html

[N09] 栈与队列
来源：http://dali.316326.xyz/Article/details/gtvothclmf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.fengsongda.top/Article/details/gtbpdieydf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhengqikj.top/Article/details/gthsuhczhv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtujkhetsa.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.iojbl.cn/Article/details/gtyaqrceco.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hfpthk.cn/Article/details/gtkvlopyzo.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.9152youxi.cn/Article/details/gtemnyauxi.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.tian-w.cn/Article/details/gtumseyvui.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hongshengwenyu.top/Article/details/gtitygrvvn.html

[N10] 链表节点定义
来源：http://dali.gogol.net.cn/Article/details/gtydzvudnn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yueranfly.top/Article/details/gtitorwozv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.9152youxi.cn/Article/details/gtfiasqqvt.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cheryme.top/Article/details/gtroeykbnm.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shuidangran.top/Article/details/gtoamiwmac.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gtryrvenas.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.daxiang520.top/Article/details/gtirtrkqlp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shangyingyoupin.top/Article/details/gtqlieoclh.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ehwqpu.com/Article/details/gtxtekjejk.html

[N11] 二叉树中序遍历
来源：http://dali.havefunace.top/Article/details/gtjvfxsiuz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhongyouzk.top/Article/details/gtilshrywn.html

PHP:  // 手写递归函数
来源：http://dali.andypj.xyz/Article/details/gtquczskzl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.9152youxi.cn/Article/details/gtxnkdbogp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgfzy.top/Article/details/gtlhfsxcyr.html

Java: // 手写递归
来源：http://dali.guannengcc.top/Article/details/gtmwhukfku.html

Go:   // 手写递归
来源：http://dali.gogol.net.cn/Article/details/gtvrdgrktc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.nanxinkj.top/Article/details/gtxuppwtjn.html

C#:   // 手写递归
来源：http://dali.yuxming.cn/Article/details/gtfwvjfgur.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jianghu66.top/Article/details/gtmygdpbls.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yuxming.cn/Article/details/gtnrfmkkxt.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yangfankeji.com/Article/details/gtedwpnsnq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ehwqpu.com/Article/details/gtlizbieyt.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.havefunace.top/Article/details/gtnwwzqfrr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gotoacloud.top/Article/details/gtnknaythn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sweek.top/Article/details/gtodhomici.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gaohongyu789.top/Article/details/gtvcudqlbf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yvedp.cn/Article/details/gtjsxhvrwh.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtsdtjzkdz.html

O. 并发与异步
来源：http://dali.gaohongyu789.top/Article/details/gtvgkkfyom.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gttianrvnj.html

[O01] 启动一个线程
来源：http://dali.ydzc1.top/Article/details/gtqyyjifqp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xuanzx.com/Article/details/gtzkhsdwem.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtdeufxvgg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.daxiang520.top/Article/details/gtmpdzvidw.html

TS:   // 同 JS
来源：http://dali.0kj1m.cn/Article/details/gtvxamkzfe.html

Java: new Thread(() -> f()).start()
来源：http://dali.hywenlv.cn/Article/details/gtpcukxmzm.html

Go:   go f()
来源：http://dali.c1oappe.top/Article/details/gtghxuwpij.html

Ruby: Thread.new { f }
来源：http://dali.guannengcc.top/Article/details/gttdnvdyxd.html

C#:   Task.Run(() => F());
来源：http://dali.hywenlv.cn/Article/details/gtykuylavb.html

[O02] 使用线程池
来源：http://dali.chenjidiqi.icu/Article/details/gtgzmairce.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.aizwys.cn/Article/details/gtiimemhjj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.316326.xyz/Article/details/gtoxmiwfer.html

JS:   // worker_threads 线程池
来源：http://dali.ybcxt.top/Article/details/gtbmlkpdkv.html

TS:   // worker_threads 线程池
来源：http://dali.havefunace.top/Article/details/gthrpyllzm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.haohaochexian.top/Article/details/gtgruxhxjw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xuetiantiany.cn/Article/details/gtjeozkzwd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xylfe.cn/Article/details/gtgxfuexcn.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xinyue.icu/Article/details/gtybmaagkf.html

[O03] 加锁保护共享数据
来源：http://dali.zhengqikj.top/Article/details/gteqhihmgo.html

Py:   with lock: shared += 1
来源：http://dali.mhx1999.top/Article/details/gtbddqphgn.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cucudq.cn/Article/details/gtfqtrwdrv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.pengpengdd.cyou/Article/details/gtxalydyrv.html

TS:   // 同 JS
来源：http://dali.hnxiangtu.top/Article/details/gtyynsuuba.html

Java: synchronized (this) { shared++; }
来源：http://dali.nanxinkj.top/Article/details/gtaabbmsdt.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.aibaodan.cn/Article/details/gtgcdmgsqw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hnqzz.top/Article/details/gtacfdvwfp.html

C#:   lock (gate) { shared++; }
来源：http://dali.jlsjyb.cn/Article/details/gthclfxjxl.html

[O04] 定义异步函数并等待
来源：http://dali.yanxiufei.cn/Article/details/gtdmlotclj.html

Py:   async def f():⏎    await g()
来源：http://dali.hnqzz.top/Article/details/gtquhcxovt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.aibaodan.cn/Article/details/gtepmydxgz.html

JS:   async function f() { await g(); }
来源：http://dali.gzhubu.top/Article/details/gtiwxjugpm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.mhx1999.top/Article/details/gtezlhcvpp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.tanke756.top/Article/details/gtdvgppekl.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.chenjidiqi.icu/Article/details/gtmsuesszy.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cdnleiting.top/Article/details/gtcbgmvuck.html

C#:   async Task F() { await G(); }
来源：http://dali.hnxiangtu.top/Article/details/gtoymrfxtl.html

[O05] 并发执行并等待全部完成
来源：http://dali.guannengcc.top/Article/details/gtvzxerxsz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.pycfn.com/Article/details/gtapactkuy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.dashuyun.cn/Article/details/gtdcoxnxot.html

JS:   await Promise.all(tasks)
来源：http://dali.hywenlv.cn/Article/details/gtzpcwuzfh.html

TS:   await Promise.all(tasks)
来源：http://dali.hnqzz.top/Article/details/gtrvznbrnp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.wangdashe.top/Article/details/gtvdcipmhc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gaohongyu789.top/Article/details/gtusitrsof.html

Ruby: threads.map(&:join)
来源：http://dali.yonumen.top/Article/details/gtbrdhfscg.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yvedp.cn/Article/details/gtiddzkaah.html

[O06] 使用进程池
来源：http://dali.haohaochexian.top/Article/details/gtozsvxbap.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sweek.top/Article/details/gtqqhtjfot.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yonumen.top/Article/details/gthlooouhw.html

JS:   // child_process / cluster 模块
来源：http://dali.nanxinkj.top/Article/details/gttfzuirjw.html

TS:   // child_process / cluster 模块
来源：http://dali.tianlin.xyz/Article/details/gtcvruigdp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.nwbrower.top/Article/details/gtfptxeyrx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.haohaochexian.top/Article/details/gthesjhrdl.html

Ruby: // fork 块
来源：http://dali.gotoacloud.top/Article/details/gtlreuhuoh.html

C#:   Parallel.For
来源：http://dali.jiagoushi.top/Article/details/gtjmlefkfp.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtpzuhyzdt.html

P. 常用工具函数
来源：http://dali.jinqigufen.top/Article/details/gtofffssvy.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtzjqpjdgq.html

[P01] 生成 UUID
来源：http://dali.smart0.xyz/Article/details/gtlcstsnzh.html

Py:   str(uuid.uuid4())
来源：http://dali.meibo888.top/Article/details/gtogbhumgb.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.9152youxi.cn/Article/details/gtoucrqyga.html

JS:   crypto.randomUUID()
来源：http://dali.zycfv.cn/Article/details/gtakpcpktf.html

TS:   crypto.randomUUID()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtotufelqp.html

Java: UUID.randomUUID().toString()
来源：http://dali.xinyue.icu/Article/details/gthhwnjxxp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gzhubu.top/Article/details/gtrudcoauh.html

Ruby: SecureRandom.uuid
来源：http://dali.cashguo.top/Article/details/gtnsvgfpcv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.kuanghao11.cn/Article/details/gtwakybbah.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yangfankeji.com/Article/details/gtuutocvpv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xylfe.cn/Article/details/gtfadozajr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.daria6918.cn/Article/details/gtbhfwjksu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfrmcerox.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jyoumei.cn/Article/details/gtgefzsiem.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shangyingyoupin.top/Article/details/gtltfrbvgt.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.birdmap.top/Article/details/gtvkktijuy.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinqigfzy.top/Article/details/gtlxjknxve.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.nanxuanxn.top/Article/details/gttohazjnb.html

[P03] 生成短随机字符串
来源：http://dali.jyoumei.cn/Article/details/gtatbslwpl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xuetiantiany.cn/Article/details/gthvwyqedn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.tianlin.xyz/Article/details/gtlbzjprii.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgufenzy.top/Article/details/gttwkvssqt.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aibaodan.cn/Article/details/gtmdnjnqna.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.chenzaomai.com/Article/details/gtqmabcxwy.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.chenlongwang.top/Article/details/gtnarazntd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hywenlv.cn/Article/details/gtquojjmpt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.daria6918.cn/Article/details/gtfymedwjp.html

[P04] 求长度
来源：http://dali.yanxiufei.cn/Article/details/gtcifwqcfb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cashguo.top/Article/details/gtcunpaczp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gtorrdzgwz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gotoacloud.top/Article/details/gtabublrpx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gogol.net.cn/Article/details/gtwqmntaja.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhongyouzk.top/Article/details/gthmxfkkfn.html

Go:   len(arr);  len(m)
来源：http://dali.dianchejie.cn/Article/details/gtzpfnzddf.html

Ruby: x.length;  x.size
来源：http://dali.yangfankeji.com/Article/details/gtjrzylfvr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.fzhhl.top/Article/details/gtcfnnihyj.html


<!-- 参考信息 -->