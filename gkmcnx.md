代发 wailian999

C#:   (int)resp.StatusCode
来源：http://dali.chenlongwang.top/Article/details/gt2awfmetln.html

[L08] 并发请求多个地址
来源：http://dali.redwolf501.top/Article/details/gt2solsgown.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.daxiang520.top/Article/details/gt2cqqmrkov.html

PHP:  curl_multi_init() 系列
来源：http://dali.hnxiangtu.top/Article/details/gt2hhhphazs.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gt2kjnnqrga.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhengqikj.top/Article/details/gt2jywrozjo.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.tanke756.top/Article/details/gt2hlgdwmup.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lxxbaqfo.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.fzhhl.top/Article/details/gt2qhenheqm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.chenlongwang.top/Article/details/gt2ufbfpkei.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2pcofllkn.html

M. 命令行 / 进程 / 环境
来源：http://dali.yanxiufei.cn/Article/details/gt2tfufrsaa.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2ckiqfzsf.html

[M01] 读取命令行参数
来源：http://dali.daria6918.cn/Article/details/gt2mezoonvt.html

Py:   sys.argv[1:]
来源：http://dali.0kj1m.cn/Article/details/gt2ohwvzygx.html

PHP:  $argv;  $argc;
来源：http://dali.pycfn.com/Article/details/gt2txpenowv.html

JS:   process.argv.slice(2)
来源：http://dali.pycfn.com/Article/details/gt2fmmuiyqg.html

TS:   process.argv.slice(2)
来源：http://dali.zhoulong.xyz/Article/details/gt2jbowdxsb.html

Java: args 数组（main 方法参数）
来源：http://dali.ydzc1.top/Article/details/gt2qdoxbcly.html

Go:   os.Args[1:]
来源：http://dali.jlsjyb.cn/Article/details/gt2gdciklwp.html

Ruby: ARGV
来源：http://dali.jyoumei.cn/Article/details/gt2rpldmjbu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.mhx1999.top/Article/details/gt2hcezrksf.html

[M02] 读取环境变量
来源：http://dali.nanxinkj.top/Article/details/gt2mlessxux.html

Py:   os.environ.get("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gt2zhkrgyzy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.birdmap.top/Article/details/gt2chhzzawv.html

JS:   process.env.HOME
来源：http://dali.svipenyu.cn/Article/details/gt2ephnfkia.html

TS:   process.env.HOME
来源：http://dali.0kj1m.cn/Article/details/gt2cnxkztcu.html

Java: System.getenv("HOME")
来源：http://dali.sysykeji.top/Article/details/gt2xejfagtf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yongpay.top/Article/details/gt2nlqaekni.html

Ruby: ENV["HOME"]
来源：http://dali.zhengqikj.top/Article/details/gt2vdcmxglt.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cashguo.top/Article/details/gt2eraqxmet.html

[M03] 执行外部命令
来源：http://dali.ybcxt.top/Article/details/gt2wvcpiayb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.iojbl.cn/Article/details/gt2mnylwxmy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gotoacloud.top/Article/details/gt2dwledcrr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.pycfn.com/Article/details/gt2kjdseefw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ivvv.top/Article/details/gt2pvrgegeh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jianghu66.top/Article/details/gt2atwpqrwm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yangfankeji.com/Article/details/gt2mloxyixb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ydzc1.top/Article/details/gt2kcqidytw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yj20258888.top/Article/details/gt2qeboqlka.html

[M04] 获取当前工作目录
来源：http://dali.zhiwuduotai.top/Article/details/gt2cysltdco.html

Py:   os.getcwd()
来源：http://dali.ehwqpu.com/Article/details/gt2zdcvynxj.html

PHP:  getcwd();
来源：http://dali.0kj1m.cn/Article/details/gt2lccojbpn.html

JS:   process.cwd()
来源：http://dali.yonumen.top/Article/details/gt2qkmdpssg.html

TS:   process.cwd()
来源：http://dali.bjfxy.top/Article/details/gt2zefpyxff.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.mhx1999.top/Article/details/gt2fjqmzrhz.html

Go:   os.Getwd()
来源：http://dali.havefunace.top/Article/details/gt2uubisodk.html

Ruby: Dir.pwd
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sjulqtju.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinqigfzy.top/Article/details/gt2oeiiflem.html

[M05] 设置退出码
来源：http://dali.mhx1999.top/Article/details/gt2dzfsmxwk.html

Py:   sys.exit(1)
来源：http://dali.cucudq.cn/Article/details/gt2utdecvro.html

PHP:  exit(1);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mqdktptt.html

JS:   process.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2zzxfkojb.html

TS:   process.exit(1)
来源：http://dali.yuxming.cn/Article/details/gt2qcxfgsij.html

Java: System.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vvcarnqy.html

Go:   os.Exit(1)
来源：http://dali.gogol.net.cn/Article/details/gt2mygbqjub.html

Ruby: exit 1
来源：http://dali.yangfankeji.com/Article/details/gt2jmeooqwx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hammf.cn/Article/details/gt2rsocamcj.html

[M06] 向标准错误输出
来源：http://dali.chenlongwang.top/Article/details/gt2rudmbyxn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ybcxt.top/Article/details/gt2zpwdqhqb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.dianchejie.cn/Article/details/gt2bwkuafvj.html

JS:   console.error("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cxvlfdgi.html

TS:   console.error("err")
来源：http://dali.nanxinkj.top/Article/details/gt2luszikjk.html

Java: System.err.println("err")
来源：http://dali.shzxlz.cn/Article/details/gt2hrmdcusd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.316326.xyz/Article/details/gt2nxmejcib.html

Ruby: warn "err"
来源：http://dali.havefunace.top/Article/details/gt2btigpqed.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cdnleiting.top/Article/details/gt2olcxsgur.html

[M07] 判断是否为主入口
来源：http://dali.yuxming.cn/Article/details/gt2zzbyqzxn.html

Py:   if __name__ == "__main__":
来源：http://dali.svipenyu.cn/Article/details/gt2peayuuef.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yuxming.cn/Article/details/gt2hzedypaj.html

JS:   require.main === module
来源：http://dali.chenzaomai.com/Article/details/gt2tvamfsea.html

TS:   require.main === module
来源：http://dali.zdqjudy.top/Article/details/gt2pjpogezp.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2enkqnqvy.html

Go:   func main()
来源：http://dali.ppjwa.cn/Article/details/gt2rblsgawr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.wangdashe.top/Article/details/gt2wbnopwxg.html

C#:   static void Main(string[] args)
来源：http://dali.zhongyouzk.top/Article/details/gt2uvdsujrx.html

[M08] 获取系统与运行时信息
来源：http://dali.smart0.xyz/Article/details/gt2vtojzpfh.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yongpay.top/Article/details/gt2ybimorfx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zdqjudy.top/Article/details/gt2qoryrule.html

JS:   process.platform;  process.version
来源：http://dali.zhongyouzk.top/Article/details/gt2mqahkuux.html

TS:   process.platform;  process.version
来源：http://dali.c1oappe.top/Article/details/gt2zelvhyzb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xziqi.cn/Article/details/gt2ijzkfqaj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yonumen.top/Article/details/gt2yhvzhlfy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.andypj.xyz/Article/details/gt2hevndfjl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.aibaodan.cn/Article/details/gt2wnswkvkm.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2deospfks.html

N. 数据结构与算法
来源：http://dali.tianlin.xyz/Article/details/gt2gaicpwfo.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2myfjjmbp.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2qoflmuar.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gt2ztzzxazq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.redwolf501.top/Article/details/gt2ppnijfzx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenlongwang.top/Article/details/gt2pzgynjax.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xylfe.cn/Article/details/gt2qmbcscor.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gt2jmmuetlv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.mhx1999.top/Article/details/gt2zpukhorp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shzxlz.cn/Article/details/gt2lqfyxrar.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.fzhhl.top/Article/details/gt2ibcoiwei.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yj20258.top/Article/details/gt2ecgbjtmt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sweek.top/Article/details/gt2yglmtirr.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.birdmap.top/Article/details/gt2dooqqqud.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigufen.top/Article/details/gt2bghhwlsk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.iojbl.cn/Article/details/gt2svamulzl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yanxiufei.cn/Article/details/gt2kaagouav.html

Go:   slices.Sort(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2bttgauyn.html

Ruby: arr.sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vcbzqsub.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbxhcvq.html

[N03] 快速排序（分治示例）
来源：http://dali.aizwys.cn/Article/details/gt2gnqnpgue.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.fzhhl.top/Article/details/gt2ssruscln.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gogol.net.cn/Article/details/gt2svhkzrhj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gotoacloud.top/Article/details/gt2xsjpfice.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tanke756.top/Article/details/gt2vqjxibkj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xuanzx.com/Article/details/gt2hhwwcoah.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gaohongyu789.top/Article/details/gt2uresdxnw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ehwqpu.com/Article/details/gt2uuthlbkm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.quarkkingdee.top/Article/details/gt2dzurwrab.html

[N04] 斐波那契数列
来源：http://dali.sxryk.cn/Article/details/gt2hqqdnfqs.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.guannengcc.top/Article/details/gt2bbefioer.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2wlsbsasl.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.svipenyu.cn/Article/details/gt2cdgbkkqv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gt2lcmcgtof.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.andypj.xyz/Article/details/gt2jwmxzpyx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hnqzz.top/Article/details/gt2hqhlddtt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jiagoushi.top/Article/details/gt2uhhtdbxo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gt2otdvzzvv.html

[N05] 最大公约数
来源：http://dali.havefunace.top/Article/details/gt2guumkaul.html

Py:   math.gcd(a, b)
来源：http://dali.316326.xyz/Article/details/gt2gmfpirzq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shuidangran.top/Article/details/gt2bcianvuj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yueranfly.top/Article/details/gt2qjkqjkps.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.havefunace.top/Article/details/gt2qqfrzbzi.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zdqjudy.top/Article/details/gt2ezvevxwl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ppjwa.cn/Article/details/gt2naloyryd.html

Ruby: a.gcd(b)
来源：http://dali.haohaochexian.top/Article/details/gt2skdvkbde.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hnxiangtu.top/Article/details/gt2dahmpofh.html

[N06] 判断回文字符串
来源：http://dali.pengpengdd.cyou/Article/details/gt2ixadplga.html

Py:   s == s[::-1]
来源：http://dali.yongpay.top/Article/details/gt2nvkewrnf.html

PHP:  $s === strrev($s);
来源：http://dali.c1oappe.top/Article/details/gt2gwfknkax.html

JS:   s === [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gt2mytxewzb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gt2qgoqkqhe.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.svipenyu.cn/Article/details/gt2zqzbnfjo.html

Go:   // 双指针从两端比较
来源：http://dali.yonumen.top/Article/details/gt2ybmauthm.html

Ruby: s == s.reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gt2arxzldgr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.mhx1999.top/Article/details/gt2vbafzdoz.html

[N07] 两数之和（返回下标）
来源：http://dali.shzxlz.cn/Article/details/gt2kmvfuoxg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yj202588.top/Article/details/gt2dpnrycoh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.fzhhl.top/Article/details/gt2mtouyncd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ppjwa.cn/Article/details/gt2kdzonsgb.html

TS:   // 手写 Map<string, number>
来源：http://dali.ybcxt.top/Article/details/gt2sxqtqnjk.html

Java: // 手写 HashMap
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wlabngql.html

Go:   // 手写 map[int]int
来源：http://dali.redwolf501.top/Article/details/gt2wgugwxai.html

Ruby: // 手写 Hash
来源：http://dali.yj20258888.top/Article/details/gt2uejxowyb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.chenjidiqi.icu/Article/details/gt2wnarojie.html

[N08] 生成全排列
来源：http://dali.yanxiufei.cn/Article/details/gt2kgbqdicb.html

Py:   itertools.permutations(arr)
来源：http://dali.xuanzx.com/Article/details/gt2lxadrybr.html

PHP:  // 手写递归交换
来源：http://dali.aibaodan.cn/Article/details/gt2rvlqdabd.html

JS:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gt2axemvwjk.html

TS:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gt2ukcqzour.html

Java: // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gt2rjccdwue.html

Go:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gt2qsxxgnmx.html

Ruby: arr.permutation.to_a
来源：http://dali.sweek.top/Article/details/gt2kmpxkwud.html

C#:   // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gt2ksbttwsu.html

[N09] 栈与队列
来源：http://dali.zhengqikj.top/Article/details/gt2cjaldbyu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hnqzz.top/Article/details/gt2lekuxklf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.bjfxy.top/Article/details/gt2fhhpngqj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.tanke756.top/Article/details/gt2xgbjhzac.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.andypj.xyz/Article/details/gt2uezdsxip.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.aizwys.cn/Article/details/gt2tesuntno.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.tanke756.top/Article/details/gt2gnmbzyhf.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.birdmap.top/Article/details/gt2rmlhvqie.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2myzvkkqj.html

[N10] 链表节点定义
来源：http://dali.316326.xyz/Article/details/gt2klkpqnhy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.quarkkingdee.top/Article/details/gt2dsbdtfbl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.nanxinkj.top/Article/details/gt2qwhkmapg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.haohaochexian.top/Article/details/gt2nnjqyncc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shangyingyoupin.top/Article/details/gt2iilyqmvi.html

Java: class Node { int v; Node next; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2vrpmmgdq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.c1oappe.top/Article/details/gt2zdpniilt.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tianlin.xyz/Article/details/gt2plwjzbdd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dwgvlicp.html

[N11] 二叉树中序遍历
来源：http://dali.pengpengdd.cyou/Article/details/gt2kgmqyhix.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yvedp.cn/Article/details/gt2rlyqpdnf.html

PHP:  // 手写递归函数
来源：http://dali.yueranfly.top/Article/details/gt2gprbolyd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guannengcc.top/Article/details/gt2qlwicdlk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ivvv.top/Article/details/gt2zjprzbed.html

Java: // 手写递归
来源：http://dali.fengsongda.top/Article/details/gt2radpebdy.html

Go:   // 手写递归
来源：http://dali.gaohongyu789.top/Article/details/gt2tudsnazl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinqigufen.top/Article/details/gt2ujkzdgpc.html

C#:   // 手写递归
来源：http://dali.cqqwz.cn/Article/details/gt2hgiltfia.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hnqzz.top/Article/details/gt2cdnmfsqr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hywenlv.cn/Article/details/gt2lulmuldk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xuanzx.com/Article/details/gt2qsisdmgk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hnqzz.top/Article/details/gt2pjpplszx.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.0kj1m.cn/Article/details/gt2kbcsphmr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2eszoataq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.316326.xyz/Article/details/gt2uxcngrwv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.wangshuangyany.cn/Article/details/gt2lzlztshq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgfzy.top/Article/details/gt2qiciupnx.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2dxtojgcp.html

O. 并发与异步
来源：http://dali.yj20258.top/Article/details/gt2srqujcnn.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2hsumlivu.html

[O01] 启动一个线程
来源：http://dali.chenzaomai.com/Article/details/gt2mhupjqzd.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yanxiufei.cn/Article/details/gt2alyndccu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gogol.net.cn/Article/details/gt2rqrzpgyf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gogol.net.cn/Article/details/gt2jiwkvjqe.html

TS:   // 同 JS
来源：http://dali.hammf.cn/Article/details/gt2mswuzxbe.html

Java: new Thread(() -> f()).start()
来源：http://dali.sweek.top/Article/details/gt2dhjnkvzz.html

Go:   go f()
来源：http://dali.yonumen.top/Article/details/gt2gezwqkov.html

Ruby: Thread.new { f }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ixxlycpa.html

C#:   Task.Run(() => F());
来源：http://dali.tian-w.cn/Article/details/gt2zwvemyag.html

[O02] 使用线程池
来源：http://dali.zhoulong.xyz/Article/details/gt2azvjxnli.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jqgfzy.top/Article/details/gt2zkqlecgx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zfrkxusp.html

JS:   // worker_threads 线程池
来源：http://dali.dashuyun.cn/Article/details/gt2acvvazek.html

TS:   // worker_threads 线程池
来源：http://dali.fengsongda.top/Article/details/gt2vzprvadm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.fengsongda.top/Article/details/gt2qxsnylat.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xinyue.icu/Article/details/gt2uemordhp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.daria6918.cn/Article/details/gt2ihyxifwa.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yangfankeji.com/Article/details/gt2qaeexjpu.html

[O03] 加锁保护共享数据
来源：http://dali.xuanzx.com/Article/details/gt2zwgahlmf.html

Py:   with lock: shared += 1
来源：http://dali.shangyingyoupin.top/Article/details/gt2yukvxefw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hysaishi.cn/Article/details/gt2lrcknftq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.316326.xyz/Article/details/gt2dfmsnydu.html

TS:   // 同 JS
来源：http://dali.yanxiufei.cn/Article/details/gt2mnzhvhzu.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkyogonr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2azlwxaqm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.feifeiyinyue.top/Article/details/gt2nyvcskxa.html

C#:   lock (gate) { shared++; }
来源：http://dali.cqqwz.cn/Article/details/gt2hqwbizfl.html

[O04] 定义异步函数并等待
来源：http://dali.hysaishi.cn/Article/details/gt2wprhlczd.html

Py:   async def f():⏎    await g()
来源：http://dali.wangdashe.top/Article/details/gt2mugkqwkm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.daxiang520.top/Article/details/gt2tvwlzxwn.html

JS:   async function f() { await g(); }
来源：http://dali.c1oappe.top/Article/details/gt2gbwckblq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2mmpzgeso.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bzpiopsw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.aibaodan.cn/Article/details/gt2sozsicyw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jqgufenzy.top/Article/details/gt2ownoojxc.html

C#:   async Task F() { await G(); }
来源：http://dali.hfpthk.cn/Article/details/gt2twjmxedi.html

[O05] 并发执行并等待全部完成
来源：http://dali.jqgfzy.top/Article/details/gt2ujxlsfgd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hywenlv.cn/Article/details/gt2qjhomieo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sweek.top/Article/details/gt2wgylnfdr.html

JS:   await Promise.all(tasks)
来源：http://dali.zhongyouzk.top/Article/details/gt2yaubuohc.html

TS:   await Promise.all(tasks)
来源：http://dali.aibaodan.cn/Article/details/gt2zzzoelpl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hongshengwenyu.top/Article/details/gt2gdbsrigu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhiwuduotai.top/Article/details/gt2gcfjelsk.html

Ruby: threads.map(&:join)
来源：http://dali.yj20258.top/Article/details/gt2ddmqiezi.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.pycfn.com/Article/details/gt2gdermecj.html

[O06] 使用进程池
来源：http://dali.mhx1999.top/Article/details/gt2kabqkwwq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ivvv.top/Article/details/gt2efjiqqxh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.fengsongda.top/Article/details/gt2wxlwdynz.html

JS:   // child_process / cluster 模块
来源：http://dali.daria6918.cn/Article/details/gt2bqhuuowv.html

TS:   // child_process / cluster 模块
来源：http://dali.jinqigfzy.top/Article/details/gt2ykvsdbqr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.haohaochexian.top/Article/details/gt2nhrbuwbf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ivvv.top/Article/details/gt2qmimvqxo.html

Ruby: // fork 块
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tzisizkh.html

C#:   Parallel.For
来源：http://dali.cqqwz.cn/Article/details/gt2mbkbmwia.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2lsyipvrx.html

P. 常用工具函数
来源：http://dali.jqgufenzy.top/Article/details/gt2lqyogqld.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2pelhjofi.html

[P01] 生成 UUID
来源：http://dali.yanxiufei.cn/Article/details/gt2jptzsoye.html

Py:   str(uuid.uuid4())
来源：http://dali.jqgufenzy.top/Article/details/gt2ervfzrgv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xuanzx.com/Article/details/gt2ygkmowyy.html

JS:   crypto.randomUUID()
来源：http://dali.yj20258.top/Article/details/gt2qllfjdic.html

TS:   crypto.randomUUID()
来源：http://dali.zycfv.cn/Article/details/gt2imqwqonb.html

Java: UUID.randomUUID().toString()
来源：http://dali.svipenyu.cn/Article/details/gt2ecelvwwq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.dashuyun.cn/Article/details/gt2uzzebiuv.html

Ruby: SecureRandom.uuid
来源：http://dali.nanxuanxn.top/Article/details/gt2ynxxwtmf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tanke756.top/Article/details/gt2cikwhwjg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vquvloqh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.316326.xyz/Article/details/gt2mcrbxhfv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.haohaochexian.top/Article/details/gt2kseeqqzh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.9152youxi.cn/Article/details/gt2zsurhtuw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ivvv.top/Article/details/gt2vhwhdvyr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yangfankeji.com/Article/details/gt2sjwupnvq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yj20258888.top/Article/details/gt2uagdnuoz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.iojbl.cn/Article/details/gt2otxaljyf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gotoacloud.top/Article/details/gt2unakrtmc.html

[P03] 生成短随机字符串
来源：http://dali.zhengqikj.top/Article/details/gt2vyiyitnx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ceigodqw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.c1oappe.top/Article/details/gt2qoxpvvlc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258888.top/Article/details/gt2vngfzyuf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.snrcjt.cn/Article/details/gt2oicnrddq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.c1oappe.top/Article/details/gt2xceedfcu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.bjfxy.top/Article/details/gt2vzbrhlft.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.haohaochexian.top/Article/details/gt2pmkjocpd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hongshengwenyu.top/Article/details/gt2xvynxtez.html

[P04] 求长度
来源：http://dali.cqqwz.cn/Article/details/gt2zcdynqgb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.svipenyu.cn/Article/details/gt2xlrstczg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gt2lwtxkljz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.quarkkingdee.top/Article/details/gt2unuudhuu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xuanzx.com/Article/details/gt2eyeazldf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.guannengcc.top/Article/details/gt2lurmqnly.html

Go:   len(arr);  len(m)
来源：http://dali.nanxinkj.top/Article/details/gt2jrplklex.html

Ruby: x.length;  x.size
来源：http://dali.fzhhl.top/Article/details/gt2ebrcyhou.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhiwuduotai.top/Article/details/gt2rvuulham.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hnxiangtu.top/Article/details/gt2eztclbej.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xjqaaynp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hongshengwenyu.top/Article/details/gt2eagvdqri.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ejluwhcu.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jyoumei.cn/Article/details/gt2ilsvozxg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ehwqpu.com/Article/details/gt2kueoizfw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinqigufen.top/Article/details/gt2ksxpmrmr.html

Ruby: a == b
来源：http://dali.yuxming.cn/Article/details/gt2lwfyuban.html


<!-- 参考信息 -->