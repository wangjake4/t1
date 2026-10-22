代发 wailian999

C#:   (int)resp.StatusCode
来源：http://dali.hammf.cn/Article/details/gt2gqlqcumw.html

[L08] 并发请求多个地址
来源：http://dali.nwbrower.top/Article/details/gt2jebdwlqz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xziqi.cn/Article/details/gt2shjlznew.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhongyouzk.top/Article/details/gt2nfgnhzwh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nypwpeka.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hysaishi.cn/Article/details/gt2bmdmztct.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.smart0.xyz/Article/details/gt2dbaqohih.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.nwbrower.top/Article/details/gt2lfeyluzt.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.guowangkeji.top/Article/details/gt2cvbodjiu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinqigufen.top/Article/details/gt2oufqfxhb.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2tvqhlmcp.html

M. 命令行 / 进程 / 环境
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uywdblho.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2wvbirlru.html

[M01] 读取命令行参数
来源：http://dali.jiagoushi.top/Article/details/gt2rilowqhl.html

Py:   sys.argv[1:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wezqewmr.html

PHP:  $argv;  $argc;
来源：http://dali.yueranfly.top/Article/details/gt2tzijbxxd.html

JS:   process.argv.slice(2)
来源：http://dali.sufxvd.cn/Article/details/gt2xvgoangu.html

TS:   process.argv.slice(2)
来源：http://dali.ehwqpu.com/Article/details/gt2pbzukhlz.html

Java: args 数组（main 方法参数）
来源：http://dali.hammf.cn/Article/details/gt2ydkchwmo.html

Go:   os.Args[1:]
来源：http://dali.quarkkingdee.top/Article/details/gt2njgffrlw.html

Ruby: ARGV
来源：http://dali.kuanghao11.cn/Article/details/gt2xpomhipg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.iojbl.cn/Article/details/gt2scakrsrt.html

[M02] 读取环境变量
来源：http://dali.gaohongyu789.top/Article/details/gt2xfazvfcc.html

Py:   os.environ.get("HOME")
来源：http://dali.guannengcc.top/Article/details/gt2yrspcvrr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yonumen.top/Article/details/gt2qfaogjzv.html

JS:   process.env.HOME
来源：http://dali.zhixingplan.top/Article/details/gt2hvmtqxgi.html

TS:   process.env.HOME
来源：http://dali.chenlongwang.top/Article/details/gt2kmcxyhga.html

Java: System.getenv("HOME")
来源：http://dali.sxryk.cn/Article/details/gt2ekfjaxro.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.pycfn.com/Article/details/gt2aykotroa.html

Ruby: ENV["HOME"]
来源：http://dali.yongpay.top/Article/details/gt2jogugvtl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj202588.top/Article/details/gt2zctogcvs.html

[M03] 执行外部命令
来源：http://dali.yj202588.top/Article/details/gt2lqapkwou.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.daria6918.cn/Article/details/gt2gmbfaooc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.guannengcc.top/Article/details/gt2xcmvkljb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shuidangran.top/Article/details/gt2uvhgptmr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hongshengwenyu.top/Article/details/gt2lnztcsla.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shangyingyoupin.top/Article/details/gt2kjtlpomm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gogol.net.cn/Article/details/gt2xtxlagix.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jqgfzy.top/Article/details/gt2admgvvrw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zdqjudy.top/Article/details/gt2euyjoofl.html

[M04] 获取当前工作目录
来源：http://dali.hnqzz.top/Article/details/gt2mrgtqfou.html

Py:   os.getcwd()
来源：http://dali.316326.xyz/Article/details/gt2jvacypts.html

PHP:  getcwd();
来源：http://dali.xylfe.cn/Article/details/gt2xmotrzef.html

JS:   process.cwd()
来源：http://dali.zhengqikj.top/Article/details/gt2avybmmxn.html

TS:   process.cwd()
来源：http://dali.dashuyun.cn/Article/details/gt2kuufsnfc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.tian-w.cn/Article/details/gt2ejlyiqmo.html

Go:   os.Getwd()
来源：http://dali.hnqzz.top/Article/details/gt2tualkpxz.html

Ruby: Dir.pwd
来源：http://dali.chenjidiqi.icu/Article/details/gt2ljpxanes.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hnqzz.top/Article/details/gt2dgjsdxek.html

[M05] 设置退出码
来源：http://dali.jiagoushi.top/Article/details/gt2cjlsfgfw.html

Py:   sys.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gldmqrst.html

PHP:  exit(1);
来源：http://dali.yonumen.top/Article/details/gt2ormxkerx.html

JS:   process.exit(1)
来源：http://dali.wangdashe.top/Article/details/gt2dxmptwpl.html

TS:   process.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gt2iqrxanav.html

Java: System.exit(1)
来源：http://dali.iojbl.cn/Article/details/gt2msaofytq.html

Go:   os.Exit(1)
来源：http://dali.ivvv.top/Article/details/gt2tscwqrsf.html

Ruby: exit 1
来源：http://dali.sweek.top/Article/details/gt2oiuonubq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.c1oappe.top/Article/details/gt2kyambwwe.html

[M06] 向标准错误输出
来源：http://dali.hfpthk.cn/Article/details/gt2zowyqons.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sxryk.cn/Article/details/gt2xrqpflyt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xuanzx.com/Article/details/gt2cwabxqlc.html

JS:   console.error("err")
来源：http://dali.svipenyu.cn/Article/details/gt2thknliyl.html

TS:   console.error("err")
来源：http://dali.hysaishi.cn/Article/details/gt2cbngngmf.html

Java: System.err.println("err")
来源：http://dali.aibaodan.cn/Article/details/gt2ciizbkrn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xinyue.icu/Article/details/gt2gvnhdihn.html

Ruby: warn "err"
来源：http://dali.xuanzx.com/Article/details/gt2avgweqgg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ivvv.top/Article/details/gt2ocnacnrf.html

[M07] 判断是否为主入口
来源：http://dali.hywenlv.cn/Article/details/gt2lsgtfjft.html

Py:   if __name__ == "__main__":
来源：http://dali.ivvv.top/Article/details/gt2udsyipjt.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sslbstaf.html

JS:   require.main === module
来源：http://dali.zhiwuduotai.top/Article/details/gt2uptxsjhe.html

TS:   require.main === module
来源：http://dali.xylfe.cn/Article/details/gt2jlhqokiy.html

Java: public static void main(String[] args)
来源：http://dali.snrcjt.cn/Article/details/gt2veqtgcvd.html

Go:   func main()
来源：http://dali.xziqi.cn/Article/details/gt2sjezuybj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.kuanghao11.cn/Article/details/gt2nkmodstc.html

C#:   static void Main(string[] args)
来源：http://dali.shzxlz.cn/Article/details/gt2aboolcik.html

[M08] 获取系统与运行时信息
来源：http://dali.c1oappe.top/Article/details/gt2hkdkdnzu.html

Py:   platform.system();  platform.python_version()
来源：http://dali.pycfn.com/Article/details/gt2kgittkmo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.birdmap.top/Article/details/gt2bamqocdn.html

JS:   process.platform;  process.version
来源：http://dali.xuanzx.com/Article/details/gt2cetbhmlm.html

TS:   process.platform;  process.version
来源：http://dali.cqqwz.cn/Article/details/gt2djudciya.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shangyingyoupin.top/Article/details/gt2yttwhtuf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.316326.xyz/Article/details/gt2rhqudkbm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jlsjyb.cn/Article/details/gt2hikhifjh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.aizwys.cn/Article/details/gt2hwybvxgb.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2bhzeoprf.html

N. 数据结构与算法
来源：http://dali.snrcjt.cn/Article/details/gt2zdywwyar.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2cmntyckp.html

[N01] 二分查找（有序数组）
来源：http://dali.andypj.xyz/Article/details/gt2kasofyqr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gzhubu.top/Article/details/gt2djslspdu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.chenzaomai.com/Article/details/gt2hxpydwys.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fengsongda.top/Article/details/gt2gmrqlsbl.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigfzy.top/Article/details/gt2xqgmqbhc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gt2morgroop.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gt2xshtpmmf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xuanzx.com/Article/details/gt2eyxdtahw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gt2hljwyvyk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hfpthk.cn/Article/details/gt2jztagyel.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hfpthk.cn/Article/details/gt2nmyzvysa.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jyoumei.cn/Article/details/gt2rwzpfasu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cashguo.top/Article/details/gt2myissyfu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yangfankeji.com/Article/details/gt2grgsjprw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.aibaodan.cn/Article/details/gt2bmjamvhu.html

Go:   slices.Sort(arr)
来源：http://dali.xylfe.cn/Article/details/gt2qmfxkixt.html

Ruby: arr.sort
来源：http://dali.ehwqpu.com/Article/details/gt2ffvjepak.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hywenlv.cn/Article/details/gt2urklbgqd.html

[N03] 快速排序（分治示例）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wwkxgxmn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yuxming.cn/Article/details/gt2jhjdwqle.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xinyue.icu/Article/details/gt2brhhumhw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hammf.cn/Article/details/gt2pggfpdiz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gogol.net.cn/Article/details/gt2uthrznsk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cashguo.top/Article/details/gt2blnytxaw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yongpay.top/Article/details/gt2kbcakjku.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xuetiantiany.cn/Article/details/gt2utnppsdd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.snrcjt.cn/Article/details/gt2yzmtdkom.html

[N04] 斐波那契数列
来源：http://dali.0kj1m.cn/Article/details/gt2jvpewsur.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2gsxbardm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.dashuyun.cn/Article/details/gt2snwxoegx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.haohaochexian.top/Article/details/gt2zgdyzoat.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhoulong.xyz/Article/details/gt2kiqmdxgc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ijiehucq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xylfe.cn/Article/details/gt2qxjqvgwj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.nwbrower.top/Article/details/gt2wvedmgwx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gt2lddeovrz.html

[N05] 最大公约数
来源：http://dali.smart0.xyz/Article/details/gt2ifzgnfni.html

Py:   math.gcd(a, b)
来源：http://dali.havefunace.top/Article/details/gt2watuiuxg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2oerrolho.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yonumen.top/Article/details/gt2aldvktmt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fengsongda.top/Article/details/gt2lxyuwiwf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.fengsongda.top/Article/details/gt2ofmkhfns.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2akzuunsz.html

Ruby: a.gcd(b)
来源：http://dali.dashuyun.cn/Article/details/gt2ledgrrpj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.vqdsnc.cn/Article/details/gt2rqjmgauj.html

[N06] 判断回文字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2jtmqoyiw.html

Py:   s == s[::-1]
来源：http://dali.ydzc1.top/Article/details/gt2zalknepj.html

PHP:  $s === strrev($s);
来源：http://dali.xziqi.cn/Article/details/gt2ouunwyxp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gt2hbqruzlw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gt2ijphvhnq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2sstykacd.html

Go:   // 双指针从两端比较
来源：http://dali.shanyushiyangtech.top/Article/details/gt2shartyfh.html

Ruby: s == s.reverse
来源：http://dali.smart0.xyz/Article/details/gt2ocoteeuf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cucudq.cn/Article/details/gt2uvshfttb.html

[N07] 两数之和（返回下标）
来源：http://dali.aizwys.cn/Article/details/gt2krepxfwt.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.daxiang520.top/Article/details/gt2yqicriji.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nirgxmzq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.aibaodan.cn/Article/details/gt2ldqsqsmw.html

TS:   // 手写 Map<string, number>
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2exwmnmio.html

Java: // 手写 HashMap
来源：http://dali.xuetiantiany.cn/Article/details/gt2cldiwgdk.html

Go:   // 手写 map[int]int
来源：http://dali.chenlongwang.top/Article/details/gt2znafuyiw.html

Ruby: // 手写 Hash
来源：http://dali.fengsongda.top/Article/details/gt2junzkcii.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qninaufd.html

[N08] 生成全排列
来源：http://dali.xuanzx.com/Article/details/gt2bjbdiwzq.html

Py:   itertools.permutations(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2hbqhrhqw.html

PHP:  // 手写递归交换
来源：http://dali.sysykeji.top/Article/details/gt2diuewkul.html

JS:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gt2ckeuxvix.html

TS:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gt2pwavhotx.html

Java: // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gt2ufiyxplm.html

Go:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gt2qrblzglb.html

Ruby: arr.permutation.to_a
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pasbuxsr.html

C#:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gt2xeleaoqi.html

[N09] 栈与队列
来源：http://dali.nwbrower.top/Article/details/gt2cbljtipc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.birdmap.top/Article/details/gt2kccibrky.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cdnleiting.top/Article/details/gt2hraimdtr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.iojbl.cn/Article/details/gt2qhurarye.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yonumen.top/Article/details/gt2vkjewasr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yongpay.top/Article/details/gt2zbocoquo.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.dianchejie.cn/Article/details/gt2glehwjyg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.havefunace.top/Article/details/gt2khattinf.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sysykeji.top/Article/details/gt2bkzmediw.html

[N10] 链表节点定义
来源：http://dali.aibaodan.cn/Article/details/gt2sikhtetp.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jianghu66.top/Article/details/gt2kvhsyykk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.dashuyun.cn/Article/details/gt2pvvsnvbi.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhengqikj.top/Article/details/gt2cndepmrh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.tanke756.top/Article/details/gt2qdabbfyu.html

Java: class Node { int v; Node next; }
来源：http://dali.smart0.xyz/Article/details/gt2inxfbvxp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.fengsongda.top/Article/details/gt2jcuclspc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yuxming.cn/Article/details/gt2cqbnynns.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2htcfzrze.html

[N11] 二叉树中序遍历
来源：http://dali.bjfxy.top/Article/details/gt2ymbiqddg.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.daxiang520.top/Article/details/gt2iciffiqr.html

PHP:  // 手写递归函数
来源：http://dali.birdmap.top/Article/details/gt2wihnjerx.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.wangdashe.top/Article/details/gt2hffqopww.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cheryme.top/Article/details/gt2exzmwgyv.html

Java: // 手写递归
来源：http://dali.cdnleiting.top/Article/details/gt2ggukugio.html

Go:   // 手写递归
来源：http://dali.guannengcc.top/Article/details/gt2exubgehq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cheryme.top/Article/details/gt2loyjtjam.html

C#:   // 手写递归
来源：http://dali.sweek.top/Article/details/gt2rwcmmsgg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ybcxt.top/Article/details/gt2mportevr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hysaishi.cn/Article/details/gt2zgazjdnl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jiagoushi.top/Article/details/gt2bczvqcgs.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhongyouzk.top/Article/details/gt2vdjtmnrc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guannengcc.top/Article/details/gt2pwujdipg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gotoacloud.top/Article/details/gt2hwxjjyxf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shzxlz.cn/Article/details/gt2lxatvoou.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sweek.top/Article/details/gt2hxjgovrb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yangfankeji.com/Article/details/gt2pqnojjrj.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2wjfnpvog.html

O. 并发与异步
来源：http://dali.wangshuangyany.cn/Article/details/gt2alzezozv.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2puldqgyk.html

[O01] 启动一个线程
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oqjbiexx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ghnjhkag.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.snrcjt.cn/Article/details/gt2puqvhzyv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gogol.net.cn/Article/details/gt2zpjjomop.html

TS:   // 同 JS
来源：http://dali.xuanzx.com/Article/details/gt2jjcltfuj.html

Java: new Thread(() -> f()).start()
来源：http://dali.birdmap.top/Article/details/gt2exdnrjqm.html

Go:   go f()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2togjkkmf.html

Ruby: Thread.new { f }
来源：http://dali.bjfxy.top/Article/details/gt2lvucrztz.html

C#:   Task.Run(() => F());
来源：http://dali.haohaochexian.top/Article/details/gt2qfpexqpe.html

[O02] 使用线程池
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jkggshqd.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hysaishi.cn/Article/details/gt2oaxxljiv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhengqikj.top/Article/details/gt2kuhpkjom.html

JS:   // worker_threads 线程池
来源：http://dali.jinqigfzy.top/Article/details/gt2sqhaqrqn.html

TS:   // worker_threads 线程池
来源：http://dali.yonumen.top/Article/details/gt2jhfvvfyt.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hfpthk.cn/Article/details/gt2gnprvfwg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.redwolf501.top/Article/details/gt2joqenind.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zdqjudy.top/Article/details/gt2xajojdhy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.aizwys.cn/Article/details/gt2iedblviq.html

[O03] 加锁保护共享数据
来源：http://dali.ydzc1.top/Article/details/gt2akrvpgyj.html

Py:   with lock: shared += 1
来源：http://dali.redwolf501.top/Article/details/gt2mlehqqmk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.pengpengdd.cyou/Article/details/gt2izwvxpfc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cashguo.top/Article/details/gt2vckbzxvr.html

TS:   // 同 JS
来源：http://dali.yuanzhike.top/Article/details/gt2wrltgnqu.html

Java: synchronized (this) { shared++; }
来源：http://dali.shzxlz.cn/Article/details/gt2nlyfjgar.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hfpthk.cn/Article/details/gt2uuwjgwqw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zycfv.cn/Article/details/gt2bgoqiqcp.html

C#:   lock (gate) { shared++; }
来源：http://dali.zdqjudy.top/Article/details/gt2gdsjukia.html

[O04] 定义异步函数并等待
来源：http://dali.cheryme.top/Article/details/gt2agdmywdm.html

Py:   async def f():⏎    await g()
来源：http://dali.havefunace.top/Article/details/gt2rqkbwisb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.nwbrower.top/Article/details/gt2xmqbzznl.html

JS:   async function f() { await g(); }
来源：http://dali.cheryme.top/Article/details/gt2gewhkyif.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2owdreabv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.9152youxi.cn/Article/details/gt2nuxcalpk.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.iojbl.cn/Article/details/gt2bqymhvbq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.nwbrower.top/Article/details/gt2kztccgwv.html

C#:   async Task F() { await G(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ekdrxwsa.html

[O05] 并发执行并等待全部完成
来源：http://dali.ivvv.top/Article/details/gt2suwtbwxx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2airliwub.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fcfgphvj.html

JS:   await Promise.all(tasks)
来源：http://dali.hfpthk.cn/Article/details/gt2gpvripty.html

TS:   await Promise.all(tasks)
来源：http://dali.hysaishi.cn/Article/details/gt2ndtwbdub.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xziqi.cn/Article/details/gt2unozujrn.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.c1oappe.top/Article/details/gt2orlvwctp.html

Ruby: threads.map(&:join)
来源：http://dali.pengpengdd.cyou/Article/details/gt2qcmvhvuv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yj20258.top/Article/details/gt2agfksxxa.html

[O06] 使用进程池
来源：http://dali.cqqwz.cn/Article/details/gt2uqtiwfku.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ivvv.top/Article/details/gt2rhhajdfa.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tddnfbjx.html

JS:   // child_process / cluster 模块
来源：http://dali.xinyue.icu/Article/details/gt2kuhhtyqi.html

TS:   // child_process / cluster 模块
来源：http://dali.sxryk.cn/Article/details/gt2ttamfsbq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yuanzhike.top/Article/details/gt2ndeckayz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zycfv.cn/Article/details/gt2jeuabxkc.html

Ruby: // fork 块
来源：http://dali.sweek.top/Article/details/gt2wlogdddq.html

C#:   Parallel.For
来源：http://dali.chenlongwang.top/Article/details/gt2vkbmnmjn.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2mbgsndgj.html

P. 常用工具函数
来源：http://dali.9152youxi.cn/Article/details/gt2mfvibzey.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2ryfrmvqi.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2qfehpphh.html

Py:   str(uuid.uuid4())
来源：http://dali.cdnleiting.top/Article/details/gt2thpziblk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jiagoushi.top/Article/details/gt2hdyfeuse.html

JS:   crypto.randomUUID()
来源：http://dali.sysykeji.top/Article/details/gt2ehyldgze.html

TS:   crypto.randomUUID()
来源：http://dali.xylfe.cn/Article/details/gt2iiqqrycx.html

Java: UUID.randomUUID().toString()
来源：http://dali.nwbrower.top/Article/details/gt2jxxzvgdv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cheryme.top/Article/details/gt2mnprgici.html

Ruby: SecureRandom.uuid
来源：http://dali.smart0.xyz/Article/details/gt2nocaojou.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.kuanghao11.cn/Article/details/gt2ozqzuyvv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.feifeiyinyue.top/Article/details/gt2mdqblbwp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yvedp.cn/Article/details/gt2ewqildtm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.haohaochexian.top/Article/details/gt2enecstum.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.havefunace.top/Article/details/gt2jbufmtnt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.nwbrower.top/Article/details/gt2qoooaura.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.chenlongwang.top/Article/details/gt2igvcwkaf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yj20258.top/Article/details/gt2dhlnnvyj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.haohaochexian.top/Article/details/gt2dzuzubdz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hnqzz.top/Article/details/gt2vvnebike.html

[P03] 生成短随机字符串
来源：http://dali.mhx1999.top/Article/details/gt2wgbvrxwp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.wangdashe.top/Article/details/gt2vceogmcs.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.guannengcc.top/Article/details/gt2dxaadbzp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hfpthk.cn/Article/details/gt2iamodstz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ybhsygrj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.gaohongyu789.top/Article/details/gt2mibygjhg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.mhx1999.top/Article/details/gt2xebuzpgt.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.sxryk.cn/Article/details/gt2aajupwnd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhoulong.xyz/Article/details/gt2htebwzhf.html

[P04] 求长度
来源：http://dali.yj202588.top/Article/details/gt2zbjeipqw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ybcxt.top/Article/details/gt2jyywruvo.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gt2zcqhrsic.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxinkj.top/Article/details/gt2krvesgfg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sysykeji.top/Article/details/gt2gihmiuye.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gqnrwivj.html

Go:   len(arr);  len(m)
来源：http://dali.ybcxt.top/Article/details/gt2mvkycccv.html

Ruby: x.length;  x.size
来源：http://dali.andypj.xyz/Article/details/gt2wzxyxtuu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shangyingyoupin.top/Article/details/gt2kbzkfozi.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yj202588.top/Article/details/gt2jemxgegd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ehwqpu.com/Article/details/gt2vnymrqmk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sysykeji.top/Article/details/gt2toywxaut.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yueranfly.top/Article/details/gt2wfkjzovg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2gjwuxncx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.guannengcc.top/Article/details/gt2kqoibmym.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yonumen.top/Article/details/gt2nkrzpcwu.html

Ruby: a == b
来源：http://dali.c1oappe.top/Article/details/gt2kkmhhvwq.html


<!-- 参考信息 -->