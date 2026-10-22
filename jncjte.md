代发 wailian999

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.haohaochexian.top/Article/details/gt2chhpucqy.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jlsjyb.cn/Article/details/gt2rfvwapkt.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.dashuyun.cn/Article/details/gt2oabjaery.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.tianlin.xyz/Article/details/gt2mkgmsmhb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ybcxt.top/Article/details/gt2lriqgrvs.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hnxiangtu.top/Article/details/gt2ohzgaoob.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2vrcgygtq.html

M. 命令行 / 进程 / 环境
来源：http://dali.snrcjt.cn/Article/details/gt2jnzpnwpz.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gehfsplh.html

[M01] 读取命令行参数
来源：http://dali.svipenyu.cn/Article/details/gt2auxejpdk.html

Py:   sys.argv[1:]
来源：http://dali.nanxinkj.top/Article/details/gt2vgpwjynf.html

PHP:  $argv;  $argc;
来源：http://dali.gaohongyu789.top/Article/details/gt2kqosolvj.html

JS:   process.argv.slice(2)
来源：http://dali.xinyue.icu/Article/details/gt2vferysze.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxgruoe.html

Java: args 数组（main 方法参数）
来源：http://dali.gogol.net.cn/Article/details/gt2fecdqtzy.html

Go:   os.Args[1:]
来源：http://dali.yongpay.top/Article/details/gt2pykxegev.html

Ruby: ARGV
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nwioqxha.html

C#:   args 数组（Main 方法参数）
来源：http://dali.dashuyun.cn/Article/details/gt2frhdrvoh.html

[M02] 读取环境变量
来源：http://dali.smart0.xyz/Article/details/gt2jgszqper.html

Py:   os.environ.get("HOME")
来源：http://dali.gogol.net.cn/Article/details/gt2zbxqumwo.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.316326.xyz/Article/details/gt2zpahrnsn.html

JS:   process.env.HOME
来源：http://dali.gotoacloud.top/Article/details/gt2mhxcgmhv.html

TS:   process.env.HOME
来源：http://dali.yj20258.top/Article/details/gt2amybgfep.html

Java: System.getenv("HOME")
来源：http://dali.yj20258.top/Article/details/gt2hxjewqwa.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gt2xpvpqtlm.html

Ruby: ENV["HOME"]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bxwzlcpy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yuxming.cn/Article/details/gt2urqwably.html

[M03] 执行外部命令
来源：http://dali.ppjwa.cn/Article/details/gt2hhkudcne.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.quarkkingdee.top/Article/details/gt2kygsruft.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ydzc1.top/Article/details/gt2tfyxzjag.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.fzhhl.top/Article/details/gt2egihaqrk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jiagoushi.top/Article/details/gt2ishuxnpk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.birdmap.top/Article/details/gt2hjrylrap.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.daria6918.cn/Article/details/gt2vkedudkl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.quarkkingdee.top/Article/details/gt2ljcdyprd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gaohongyu789.top/Article/details/gt2aqwyfixr.html

[M04] 获取当前工作目录
来源：http://dali.guannengcc.top/Article/details/gt2tadgmskd.html

Py:   os.getcwd()
来源：http://dali.cashguo.top/Article/details/gt2mikkwjji.html

PHP:  getcwd();
来源：http://dali.shangyingyoupin.top/Article/details/gt2ldzyocnn.html

JS:   process.cwd()
来源：http://dali.hnxiangtu.top/Article/details/gt2ymkbuxuo.html

TS:   process.cwd()
来源：http://dali.xinyue.icu/Article/details/gt2zbfhjizg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yj20258.top/Article/details/gt2moqroygd.html

Go:   os.Getwd()
来源：http://dali.wangdashe.top/Article/details/gt2lydhutxk.html

Ruby: Dir.pwd
来源：http://dali.yvedp.cn/Article/details/gt2ddsyxlvw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.tian-w.cn/Article/details/gt2xczmwutg.html

[M05] 设置退出码
来源：http://dali.jiagoushi.top/Article/details/gt2kamvghgj.html

Py:   sys.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gt2qtysnmkk.html

PHP:  exit(1);
来源：http://dali.ivvv.top/Article/details/gt2nxmwxlhw.html

JS:   process.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gt2cekwfazq.html

TS:   process.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gt2ngvtxlsy.html

Java: System.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gt2lbkywpja.html

Go:   os.Exit(1)
来源：http://dali.cucudq.cn/Article/details/gt2oywyjpla.html

Ruby: exit 1
来源：http://dali.ydzc1.top/Article/details/gt2vvdkuofb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.mhx1999.top/Article/details/gt2crobxuma.html

[M06] 向标准错误输出
来源：http://dali.jqgfzy.top/Article/details/gt2lpfymoxg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jlsjyb.cn/Article/details/gt2scdejcie.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.bjfxy.top/Article/details/gt2yalmlijl.html

JS:   console.error("err")
来源：http://dali.c1oappe.top/Article/details/gt2dwszapxj.html

TS:   console.error("err")
来源：http://dali.dashuyun.cn/Article/details/gt2kslnbjsm.html

Java: System.err.println("err")
来源：http://dali.gogol.net.cn/Article/details/gt2dipjvnyz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yongpay.top/Article/details/gt2wiifjops.html

Ruby: warn "err"
来源：http://dali.jinqigufen.top/Article/details/gt2pqajqwys.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hfpthk.cn/Article/details/gt2xhgazbip.html

[M07] 判断是否为主入口
来源：http://dali.smart0.xyz/Article/details/gt2kwaftpcf.html

Py:   if __name__ == "__main__":
来源：http://dali.daria6918.cn/Article/details/gt2zbmvtjwk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zdqjudy.top/Article/details/gt2amxeyznu.html

JS:   require.main === module
来源：http://dali.wangshuangyany.cn/Article/details/gt2mmjkijps.html

TS:   require.main === module
来源：http://dali.xuanzx.com/Article/details/gt2robxsacf.html

Java: public static void main(String[] args)
来源：http://dali.gotoacloud.top/Article/details/gt2nfcovnax.html

Go:   func main()
来源：http://dali.c1oappe.top/Article/details/gt2wvldziaq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xinyue.icu/Article/details/gt2rgmyvkil.html

C#:   static void Main(string[] args)
来源：http://dali.sweek.top/Article/details/gt2yojkjtcu.html

[M08] 获取系统与运行时信息
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hskaeftc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hywenlv.cn/Article/details/gt2tmrrnffl.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.chenzaomai.com/Article/details/gt2atfdtabj.html

JS:   process.platform;  process.version
来源：http://dali.ppjwa.cn/Article/details/gt2omvesaif.html

TS:   process.platform;  process.version
来源：http://dali.shuidangran.top/Article/details/gt2iwwmxlsz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.wangshuangyany.cn/Article/details/gt2xwimbqkn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yongpay.top/Article/details/gt2mjcbamfl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.mhx1999.top/Article/details/gt2jntwundj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.chenzaomai.com/Article/details/gt2skjqssne.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2msllomwg.html

N. 数据结构与算法
来源：http://dali.xuetiantiany.cn/Article/details/gt2aadnlyai.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2mpldwcde.html

[N01] 二分查找（有序数组）
来源：http://dali.fengsongda.top/Article/details/gt2hwutwlpz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tanke756.top/Article/details/gt2dkafpgel.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhixingplan.top/Article/details/gt2dfgionzo.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tianlin.xyz/Article/details/gt2ujokoowd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fzhhl.top/Article/details/gt2gpufeyrq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.smart0.xyz/Article/details/gt2hcvtztuh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hammf.cn/Article/details/gt2cmhmrsin.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nanxinkj.top/Article/details/gt2yiabzfeb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bdeyctuy.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gzhubu.top/Article/details/gt2bdgsrzhb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.iojbl.cn/Article/details/gt2kqqluoqe.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nanxinkj.top/Article/details/gt2dnpyoisw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ufbkvuim.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangdashe.top/Article/details/gt2xnljsgjn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shuidangran.top/Article/details/gt2dirptgmw.html

Go:   slices.Sort(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rxfokenx.html

Ruby: arr.sort
来源：http://dali.nanxinkj.top/Article/details/gt2sslchejl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yonumen.top/Article/details/gt2lhcbxvyd.html

[N03] 快速排序（分治示例）
来源：http://dali.aibaodan.cn/Article/details/gt2jtgehysu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ivvv.top/Article/details/gt2straaggd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.birdmap.top/Article/details/gt2qusnqhgk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj202588.top/Article/details/gt2hgktuier.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shuidangran.top/Article/details/gt2tkwnqoim.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2otmndegk.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yanxiufei.cn/Article/details/gt2tynscrey.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zycfv.cn/Article/details/gt2dsafqikh.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jqgfzy.top/Article/details/gt2ktwuffuq.html

[N04] 斐波那契数列
来源：http://dali.jyoumei.cn/Article/details/gt2smvktmac.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.andypj.xyz/Article/details/gt2lkagkytb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ppjwa.cn/Article/details/gt2crddokiy.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gt2mckfzjce.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dcbyeasd.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yj20258.top/Article/details/gt2dxiwlzgy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2myiacnvh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xuanzx.com/Article/details/gt2mxnwnpwy.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gt2evnaahoy.html

[N05] 最大公约数
来源：http://dali.0kj1m.cn/Article/details/gt2orqnmviy.html

Py:   math.gcd(a, b)
来源：http://dali.tanke756.top/Article/details/gt2maixgsja.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.dianchejie.cn/Article/details/gt2smgiesym.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tian-w.cn/Article/details/gt2tstlwjqa.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.vqdsnc.cn/Article/details/gt2qfqulcyv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.mhx1999.top/Article/details/gt2qbfsqrqn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jianghu66.top/Article/details/gt2qukjgezv.html

Ruby: a.gcd(b)
来源：http://dali.yanxiufei.cn/Article/details/gt2neuhhmku.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xziqi.cn/Article/details/gt2vndlpihu.html

[N06] 判断回文字符串
来源：http://dali.cashguo.top/Article/details/gt2zubdwbgw.html

Py:   s == s[::-1]
来源：http://dali.chenlongwang.top/Article/details/gt2cqvaaaat.html

PHP:  $s === strrev($s);
来源：http://dali.havefunace.top/Article/details/gt2frgnkihy.html

JS:   s === [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gt2yjnvugxe.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gt2hqiwlygr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hnxiangtu.top/Article/details/gt2egiwteau.html

Go:   // 双指针从两端比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tjdctemq.html

Ruby: s == s.reverse
来源：http://dali.cucudq.cn/Article/details/gt2uyavatqt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.snrcjt.cn/Article/details/gt2qheoqpti.html

[N07] 两数之和（返回下标）
来源：http://dali.jiagoushi.top/Article/details/gt2medxowxr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yonumen.top/Article/details/gt2ctklcynq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.aibaodan.cn/Article/details/gt2vbohgnwf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lfuyhlha.html

TS:   // 手写 Map<string, number>
来源：http://dali.cqqwz.cn/Article/details/gt2qzczxtzq.html

Java: // 手写 HashMap
来源：http://dali.wangshuangyany.cn/Article/details/gt2dpdoilmg.html

Go:   // 手写 map[int]int
来源：http://dali.kuanghao11.cn/Article/details/gt2yfqhvigl.html

Ruby: // 手写 Hash
来源：http://dali.haohaochexian.top/Article/details/gt2tjkeixuh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.chenjidiqi.icu/Article/details/gt2djnmbjel.html

[N08] 生成全排列
来源：http://dali.jinqigfzy.top/Article/details/gt2mdspzkyr.html

Py:   itertools.permutations(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hudsketq.html

PHP:  // 手写递归交换
来源：http://dali.cashguo.top/Article/details/gt2dntbejhs.html

JS:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gt2dfvgpibb.html

TS:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gt2kizdeitr.html

Java: // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gt2oqabhojr.html

Go:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gt2gpdwkecd.html

Ruby: arr.permutation.to_a
来源：http://dali.vqdsnc.cn/Article/details/gt2pveumbjv.html

C#:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gt2acvtiaub.html

[N09] 栈与队列
来源：http://dali.vqdsnc.cn/Article/details/gt2ahchoslg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.pengpengdd.cyou/Article/details/gt2geqpnhko.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hnqzz.top/Article/details/gt2lnvduokz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.snrcjt.cn/Article/details/gt2vhvuaqhs.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ybcxt.top/Article/details/gt2uoefzvnd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xuetiantiany.cn/Article/details/gt2hrheupxy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jianghu66.top/Article/details/gt2rkrnbkmu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cucudq.cn/Article/details/gt2cotgqahc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cashguo.top/Article/details/gt2ffsqzqgs.html

[N10] 链表节点定义
来源：http://dali.fengsongda.top/Article/details/gt2fptavyko.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.bjfxy.top/Article/details/gt2wbdysvxf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yonumen.top/Article/details/gt2mpnshznm.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ehwqpu.com/Article/details/gt2xxwoqzsp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.quarkkingdee.top/Article/details/gt2xgpqwplm.html

Java: class Node { int v; Node next; }
来源：http://dali.meibo888.top/Article/details/gt2jpfznrar.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.mhx1999.top/Article/details/gt2uoktgopg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yj202588.top/Article/details/gt2tnrxwyfe.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.fzhhl.top/Article/details/gt2mrkpmldf.html

[N11] 二叉树中序遍历
来源：http://dali.fzhhl.top/Article/details/gt2huiarcts.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yuxming.cn/Article/details/gt2bpbsrwur.html

PHP:  // 手写递归函数
来源：http://dali.kuanghao11.cn/Article/details/gt2mqgqfokk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258.top/Article/details/gt2olredefh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.redwolf501.top/Article/details/gt2jzdzzklx.html

Java: // 手写递归
来源：http://dali.meibo888.top/Article/details/gt2egfyepko.html

Go:   // 手写递归
来源：http://dali.gogol.net.cn/Article/details/gt2dadmyowg.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jiagoushi.top/Article/details/gt2plhgniux.html

C#:   // 手写递归
来源：http://dali.pengpengdd.cyou/Article/details/gt2puwjiahn.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sufxvd.cn/Article/details/gt2ijkgfpvm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.guannengcc.top/Article/details/gt2yffcimzf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.daria6918.cn/Article/details/gt2dlebsybm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dashuyun.cn/Article/details/gt2ookltdlm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxinkj.top/Article/details/gt2liyfwuiy.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zycfv.cn/Article/details/gt2smupaana.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.guannengcc.top/Article/details/gt2ososuzcm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.dashuyun.cn/Article/details/gt2hhabafna.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgfzy.top/Article/details/gt2ymdmumrz.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2gnkfgbnh.html

O. 并发与异步
来源：http://dali.ppjwa.cn/Article/details/gt2mxkqkrpr.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2raezwikq.html

[O01] 启动一个线程
来源：http://dali.jinqigufen.top/Article/details/gt2njjiizqz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xuanzx.com/Article/details/gt2hlkqrcth.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.tianlin.xyz/Article/details/gt2nlpoyanb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.quarkkingdee.top/Article/details/gt2hpixecmt.html

TS:   // 同 JS
来源：http://dali.cashguo.top/Article/details/gt2qphvufko.html

Java: new Thread(() -> f()).start()
来源：http://dali.gotoacloud.top/Article/details/gt2jlxxtldh.html

Go:   go f()
来源：http://dali.quarkkingdee.top/Article/details/gt2niqkejdi.html

Ruby: Thread.new { f }
来源：http://dali.redwolf501.top/Article/details/gt2whqayzdk.html

C#:   Task.Run(() => F());
来源：http://dali.chenlongwang.top/Article/details/gt2zaqhmezc.html

[O02] 使用线程池
来源：http://dali.yj20258.top/Article/details/gt2dyrsqawj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.iojbl.cn/Article/details/gt2mtpokpam.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cashguo.top/Article/details/gt2xavsmthu.html

JS:   // worker_threads 线程池
来源：http://dali.nanxuanxn.top/Article/details/gt2uhdhrujr.html

TS:   // worker_threads 线程池
来源：http://dali.yj20258.top/Article/details/gt2hgfnhjhj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.dashuyun.cn/Article/details/gt2eqovzihj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.9152youxi.cn/Article/details/gt2bnbptnxd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jlsjyb.cn/Article/details/gt2atbapwet.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cucudq.cn/Article/details/gt2pzuntzqj.html

[O03] 加锁保护共享数据
来源：http://dali.sxryk.cn/Article/details/gt2jcjbytcu.html

Py:   with lock: shared += 1
来源：http://dali.yvedp.cn/Article/details/gt2rjerqtly.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.tianlin.xyz/Article/details/gt2zwuwpvnq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.haohaochexian.top/Article/details/gt2pajthmqq.html

TS:   // 同 JS
来源：http://dali.tanke756.top/Article/details/gt2vyboshey.html

Java: synchronized (this) { shared++; }
来源：http://dali.aizwys.cn/Article/details/gt2rkzgwyyd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jlsjyb.cn/Article/details/gt2jccygrdn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yuxming.cn/Article/details/gt2feikxecn.html

C#:   lock (gate) { shared++; }
来源：http://dali.9152youxi.cn/Article/details/gt2xmuwwzci.html

[O04] 定义异步函数并等待
来源：http://dali.jinqigufen.top/Article/details/gt2fyllmxbi.html

Py:   async def f():⏎    await g()
来源：http://dali.jyoumei.cn/Article/details/gt2ckfnrfef.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yonumen.top/Article/details/gt2tqdpdteo.html

JS:   async function f() { await g(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2tcvrtnmw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2kstwzejc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ivvv.top/Article/details/gt2zwlmammv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nmkytqaz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.smart0.xyz/Article/details/gt2lruwbopn.html

C#:   async Task F() { await G(); }
来源：http://dali.meibo888.top/Article/details/gt2qxxjilwv.html

[O05] 并发执行并等待全部完成
来源：http://dali.iojbl.cn/Article/details/gt2rhryteva.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shuidangran.top/Article/details/gt2rpxoiatu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hywenlv.cn/Article/details/gt2suiwwstt.html

JS:   await Promise.all(tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2evonauwd.html

TS:   await Promise.all(tasks)
来源：http://dali.zhoulong.xyz/Article/details/gt2wwxdbwdp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.feifeiyinyue.top/Article/details/gt2fjogaxmr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.dashuyun.cn/Article/details/gt2kettfryf.html

Ruby: threads.map(&:join)
来源：http://dali.sysykeji.top/Article/details/gt2qsfuckdr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yanxiufei.cn/Article/details/gt2tmhrwzkl.html

[O06] 使用进程池
来源：http://dali.jqgfzy.top/Article/details/gt2vrogsytr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.mhx1999.top/Article/details/gt2mtkwwyze.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yanxiufei.cn/Article/details/gt2lytqzlkq.html

JS:   // child_process / cluster 模块
来源：http://dali.pycfn.com/Article/details/gt2jydceheu.html

TS:   // child_process / cluster 模块
来源：http://dali.nwbrower.top/Article/details/gt2qifelwuq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.haohaochexian.top/Article/details/gt2mrirhqvq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.aizwys.cn/Article/details/gt2fkxzpptx.html

Ruby: // fork 块
来源：http://dali.yongpay.top/Article/details/gt2ufqlbhir.html

C#:   Parallel.For
来源：http://dali.yj20258888.top/Article/details/gt2wcjrkxte.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2clefjter.html

P. 常用工具函数
来源：http://dali.hywenlv.cn/Article/details/gt2augzpqlq.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2bbcrweps.html

[P01] 生成 UUID
来源：http://dali.yonumen.top/Article/details/gt2wgxutfrc.html

Py:   str(uuid.uuid4())
来源：http://dali.xziqi.cn/Article/details/gt2tzfdncvx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shzxlz.cn/Article/details/gt2tknotekh.html

JS:   crypto.randomUUID()
来源：http://dali.hywenlv.cn/Article/details/gt2nicfaqso.html

TS:   crypto.randomUUID()
来源：http://dali.pycfn.com/Article/details/gt2zexywywm.html

Java: UUID.randomUUID().toString()
来源：http://dali.svipenyu.cn/Article/details/gt2dbzdjqly.html

Go:   // 用 github.com/google/uuid
来源：http://dali.dianchejie.cn/Article/details/gt2qkksboxm.html

Ruby: SecureRandom.uuid
来源：http://dali.jinqigfzy.top/Article/details/gt2gvdgaurt.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.haohaochexian.top/Article/details/gt2kbnguxwq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shuidangran.top/Article/details/gt2orwcuibh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zycfv.cn/Article/details/gt2yeyehowy.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.mhx1999.top/Article/details/gt2tteomddb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qqzbgpet.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.svipenyu.cn/Article/details/gt2pkfcaqem.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.andypj.xyz/Article/details/gt2pcifruxa.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ybcxt.top/Article/details/gt2uibdhjqg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nwbrower.top/Article/details/gt2ytpnoesv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.guannengcc.top/Article/details/gt2vpbbbdpp.html

[P03] 生成短随机字符串
来源：http://dali.fengsongda.top/Article/details/gt2dwobyegy.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.wangdashe.top/Article/details/gt2wsmbaqid.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sweek.top/Article/details/gt2vakscadr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aibaodan.cn/Article/details/gt2cqcxjakg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zycfv.cn/Article/details/gt2wsbgstty.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hnqzz.top/Article/details/gt2urfemkfa.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.tanke756.top/Article/details/gt2cdabllza.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.sweek.top/Article/details/gt2gnqgwjbz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hysaishi.cn/Article/details/gt2tfbynanz.html

[P04] 求长度
来源：http://dali.hnqzz.top/Article/details/gt2jizymlve.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pojnkffz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gt2vppncqvz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tanke756.top/Article/details/gt2fvgxybfr.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ppjwa.cn/Article/details/gt2etapevcr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cqqwz.cn/Article/details/gt2pchpjnau.html

Go:   len(arr);  len(m)
来源：http://dali.yj20258.top/Article/details/gt2tztmysxf.html

Ruby: x.length;  x.size
来源：http://dali.kuanghao11.cn/Article/details/gt2hljqlcvu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.meibo888.top/Article/details/gt2rciysfol.html

[P05] 判断两个对象内容是否相等
来源：http://dali.nwbrower.top/Article/details/gt2hydwgsui.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.fengsongda.top/Article/details/gt2feujsuxi.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.guannengcc.top/Article/details/gt2gxzplfnk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.guannengcc.top/Article/details/gt2puetkika.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vnogfnby.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gaohongyu789.top/Article/details/gt2pdtilpjk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.redwolf501.top/Article/details/gt2brixzjfv.html

Ruby: a == b
来源：http://dali.kuanghao11.cn/Article/details/gt2onudqnfj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.gaohongyu789.top/Article/details/gt2rhledxdj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.0kj1m.cn/Article/details/gt2phqegnno.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.wangshuangyany.cn/Article/details/gt2uucmfogd.html

PHP:  if (empty($x)) {}
来源：http://dali.ppjwa.cn/Article/details/gt2qobxlmjt.html


<!-- 参考信息 -->