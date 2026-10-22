代发 wailian999

Ruby: ARGV
来源：http://dali.pycfn.com/Article/details/gt2wnncicog.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gzhubu.top/Article/details/gt2dqluderv.html

[M02] 读取环境变量
来源：http://dali.cheryme.top/Article/details/gt2nvjqoomw.html

Py:   os.environ.get("HOME")
来源：http://dali.xylfe.cn/Article/details/gt2ustsdgov.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.daxiang520.top/Article/details/gt2zdjqhtgm.html

JS:   process.env.HOME
来源：http://dali.dianchejie.cn/Article/details/gt2byzahdhh.html

TS:   process.env.HOME
来源：http://dali.zhengqikj.top/Article/details/gt2eqspkihq.html

Java: System.getenv("HOME")
来源：http://dali.haohaochexian.top/Article/details/gt2naoqyvjt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.svipenyu.cn/Article/details/gt2yjivvvxu.html

Ruby: ENV["HOME"]
来源：http://dali.ydzc1.top/Article/details/gt2dqmufsps.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hywenlv.cn/Article/details/gt2zymtrgpb.html

[M03] 执行外部命令
来源：http://dali.fzhhl.top/Article/details/gt2sssinyyh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jyoumei.cn/Article/details/gt2uxalpiis.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xuanzx.com/Article/details/gt2tgmufgvl.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj202588.top/Article/details/gt2ayoztxnx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xinyue.icu/Article/details/gt2ginidwsp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.nanxuanxn.top/Article/details/gt2xvuxjiau.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ivvv.top/Article/details/gt2eecnbitt.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gotoacloud.top/Article/details/gt2uhgkrrpf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gzhubu.top/Article/details/gt2ebcitovv.html

[M04] 获取当前工作目录
来源：http://dali.cqqwz.cn/Article/details/gt2ouxjwxwr.html

Py:   os.getcwd()
来源：http://dali.xinyue.icu/Article/details/gt2lweeyitd.html

PHP:  getcwd();
来源：http://dali.daxiang520.top/Article/details/gt2xnjrtbmz.html

JS:   process.cwd()
来源：http://dali.fzhhl.top/Article/details/gt2azlyjosq.html

TS:   process.cwd()
来源：http://dali.havefunace.top/Article/details/gt2yptqrpyc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2jowavrap.html

Go:   os.Getwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jtgopdtx.html

Ruby: Dir.pwd
来源：http://dali.hywenlv.cn/Article/details/gt2kiltkdst.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinqigfzy.top/Article/details/gt2whwfaaig.html

[M05] 设置退出码
来源：http://dali.xinyue.icu/Article/details/gt2xloxdfpp.html

Py:   sys.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gt2mmalsojk.html

PHP:  exit(1);
来源：http://dali.ehwqpu.com/Article/details/gt2qarsjziv.html

JS:   process.exit(1)
来源：http://dali.andypj.xyz/Article/details/gt2huoocjaf.html

TS:   process.exit(1)
来源：http://dali.yj202588.top/Article/details/gt2caoyyirj.html

Java: System.exit(1)
来源：http://dali.pycfn.com/Article/details/gt2ljtwjzeg.html

Go:   os.Exit(1)
来源：http://dali.daxiang520.top/Article/details/gt2ybaxmhji.html

Ruby: exit 1
来源：http://dali.ybcxt.top/Article/details/gt2jkysnuro.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.pycfn.com/Article/details/gt2rsupjeen.html

[M06] 向标准错误输出
来源：http://dali.jinqigfzy.top/Article/details/gt2tcfklyky.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hywenlv.cn/Article/details/gt2sjbzozfl.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gogol.net.cn/Article/details/gt2jdfurumr.html

JS:   console.error("err")
来源：http://dali.shuidangran.top/Article/details/gt2ybtnjxgx.html

TS:   console.error("err")
来源：http://dali.9152youxi.cn/Article/details/gt2pgxzqdsk.html

Java: System.err.println("err")
来源：http://dali.jiagoushi.top/Article/details/gt2atmwyqgh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.kuanghao11.cn/Article/details/gt2aqemucug.html

Ruby: warn "err"
来源：http://dali.hnqzz.top/Article/details/gt2pfqkrkfq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hnxiangtu.top/Article/details/gt2bkdmitkw.html

[M07] 判断是否为主入口
来源：http://dali.zhongyouzk.top/Article/details/gt2stfbolpd.html

Py:   if __name__ == "__main__":
来源：http://dali.zycfv.cn/Article/details/gt2koqxkuuo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.chenzaomai.com/Article/details/gt2bsdmijfh.html

JS:   require.main === module
来源：http://dali.cashguo.top/Article/details/gt2ygejmjqs.html

TS:   require.main === module
来源：http://dali.sysykeji.top/Article/details/gt2myqmlxgx.html

Java: public static void main(String[] args)
来源：http://dali.gzhubu.top/Article/details/gt2iupsezth.html

Go:   func main()
来源：http://dali.yanxiufei.cn/Article/details/gt2rkozbnzw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cheryme.top/Article/details/gt2jisdxblx.html

C#:   static void Main(string[] args)
来源：http://dali.hfpthk.cn/Article/details/gt2kvjatodw.html

[M08] 获取系统与运行时信息
来源：http://dali.jqgfzy.top/Article/details/gt2hlplpliy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhiwuduotai.top/Article/details/gt2nkykslct.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jlsjyb.cn/Article/details/gt2xmrucgsc.html

JS:   process.platform;  process.version
来源：http://dali.svipenyu.cn/Article/details/gt2tbzkfxtz.html

TS:   process.platform;  process.version
来源：http://dali.yonumen.top/Article/details/gt2yvodgxny.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xuetiantiany.cn/Article/details/gt2zomdcyvr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hnxiangtu.top/Article/details/gt2znvaocia.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hammf.cn/Article/details/gt2nsezpelx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shzxlz.cn/Article/details/gt2hdriqhlw.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2hdwbmzng.html

N. 数据结构与算法
来源：http://dali.316326.xyz/Article/details/gt2dznfzxlk.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2xgqooyfs.html

[N01] 二分查找（有序数组）
来源：http://dali.aizwys.cn/Article/details/gt2lcbbgupd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sysykeji.top/Article/details/gt2lrwyqqzn.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.316326.xyz/Article/details/gt2xfgqeyny.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tian-w.cn/Article/details/gt2vdykdajr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gzppdfes.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gt2yowrxaqw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xylfe.cn/Article/details/gt2ssbouqvg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shuidangran.top/Article/details/gt2chdgtqnk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yj202588.top/Article/details/gt2dqrxavqy.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhengqikj.top/Article/details/gt2uwkskkcd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258888.top/Article/details/gt2egzyovwj.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.fengsongda.top/Article/details/gt2ilnaetty.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gt2geszconf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ilagljcm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yueranfly.top/Article/details/gt2txbgtubk.html

Go:   slices.Sort(arr)
来源：http://dali.smart0.xyz/Article/details/gt2fjnnddno.html

Ruby: arr.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tarnqxiz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yj20258.top/Article/details/gt2nambdwyx.html

[N03] 快速排序（分治示例）
来源：http://dali.zhongyouzk.top/Article/details/gt2xbcyplgv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.svipenyu.cn/Article/details/gt2vetttasx.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gftdsliy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hnxiangtu.top/Article/details/gt2jkklhsff.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ppjwa.cn/Article/details/gt2kgtfyccj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ybcxt.top/Article/details/gt2cpukpnec.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hongshengwenyu.top/Article/details/gt2yagogjmt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.daria6918.cn/Article/details/gt2abkwjvce.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ndsalcxj.html

[N04] 斐波那契数列
来源：http://dali.dianchejie.cn/Article/details/gt2jdqtdaas.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258888.top/Article/details/gt2imminxuu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jqgufenzy.top/Article/details/gt2apwsskyp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yueranfly.top/Article/details/gt2wkthtvno.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuxming.cn/Article/details/gt2gazyecet.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cucudq.cn/Article/details/gt2mdqrhvmr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.gzhubu.top/Article/details/gt2thmhlzfd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2euvflahg.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hongshengwenyu.top/Article/details/gt2zcpsenwa.html

[N05] 最大公约数
来源：http://dali.gzhubu.top/Article/details/gt2sfacsxqb.html

Py:   math.gcd(a, b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2atthloxh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shzxlz.cn/Article/details/gt2hbgdkkgt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guowangkeji.top/Article/details/gt2gxlyjuyp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpkpzip.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cashguo.top/Article/details/gt2ygvewuri.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.316326.xyz/Article/details/gt2nsexdfhx.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmhacjmi.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.0kj1m.cn/Article/details/gt2ezsjkofo.html

[N06] 判断回文字符串
来源：http://dali.hfpthk.cn/Article/details/gt2rusadubq.html

Py:   s == s[::-1]
来源：http://dali.aibaodan.cn/Article/details/gt2qnoixpqr.html

PHP:  $s === strrev($s);
来源：http://dali.snrcjt.cn/Article/details/gt2lqpuuvcy.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gt2sllekhqo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.fengsongda.top/Article/details/gt2iyuxjtaj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ydzc1.top/Article/details/gt2fytjujds.html

Go:   // 双指针从两端比较
来源：http://dali.tanke756.top/Article/details/gt2aaifrakv.html

Ruby: s == s.reverse
来源：http://dali.cucudq.cn/Article/details/gt2wfgcjpgk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.nwbrower.top/Article/details/gt2jawpajla.html

[N07] 两数之和（返回下标）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ktfhqhmu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.dianchejie.cn/Article/details/gt2okrrytrd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sufxvd.cn/Article/details/gt2akdvnias.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.nwbrower.top/Article/details/gt2ssfrjkjj.html

TS:   // 手写 Map<string, number>
来源：http://dali.ppjwa.cn/Article/details/gt2ltcrxfty.html

Java: // 手写 HashMap
来源：http://dali.hammf.cn/Article/details/gt2zvlbclbo.html

Go:   // 手写 map[int]int
来源：http://dali.pengpengdd.cyou/Article/details/gt2qjsdfbkq.html

Ruby: // 手写 Hash
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wsnonaim.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.fengsongda.top/Article/details/gt2locylnyv.html

[N08] 生成全排列
来源：http://dali.bjfxy.top/Article/details/gt2wzqszwri.html

Py:   itertools.permutations(arr)
来源：http://dali.cashguo.top/Article/details/gt2fjrdvhpc.html

PHP:  // 手写递归交换
来源：http://dali.gogol.net.cn/Article/details/gt2pvocwycs.html

JS:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gt2ehkhtlgj.html

TS:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gt2hxisapqv.html

Java: // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gt2lnpcvhfs.html

Go:   // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gt2fmjfpeun.html

Ruby: arr.permutation.to_a
来源：http://dali.gogol.net.cn/Article/details/gt2pwcoxxvj.html

C#:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gt2ekuvjbhx.html

[N09] 栈与队列
来源：http://dali.yongpay.top/Article/details/gt2aueewyvm.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.chenlongwang.top/Article/details/gt2pmqunlnz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.wangdashe.top/Article/details/gt2eiqefhwq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jiagoushi.top/Article/details/gt2ewoykeeo.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ybcxt.top/Article/details/gt2foqzdtrl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jianghu66.top/Article/details/gt2ccedrgid.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cashguo.top/Article/details/gt2ptshkunp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.guannengcc.top/Article/details/gt2thmmaggt.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zycfv.cn/Article/details/gt2sxonobxt.html

[N10] 链表节点定义
来源：http://dali.sweek.top/Article/details/gt2yptfwnts.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xziqi.cn/Article/details/gt2ldtqnlgj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.guannengcc.top/Article/details/gt2mvyheipd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.birdmap.top/Article/details/gt2mszteubd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.guannengcc.top/Article/details/gt2rvxcidcr.html

Java: class Node { int v; Node next; }
来源：http://dali.andypj.xyz/Article/details/gt2woywwsrc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.fzhhl.top/Article/details/gt2jpfdphjd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tian-w.cn/Article/details/gt2jlaenrjt.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xziqi.cn/Article/details/gt2tdfpryfc.html

[N11] 二叉树中序遍历
来源：http://dali.yonumen.top/Article/details/gt2gddyfmqw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yuxming.cn/Article/details/gt2rgunryth.html

PHP:  // 手写递归函数
来源：http://dali.gotoacloud.top/Article/details/gt2auiomafm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guowangkeji.top/Article/details/gt2tbvporkn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sxryk.cn/Article/details/gt2hmrwbrkh.html

Java: // 手写递归
来源：http://dali.cheryme.top/Article/details/gt2dxzoclqm.html

Go:   // 手写递归
来源：http://dali.daxiang520.top/Article/details/gt2idlmxqmg.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.316326.xyz/Article/details/gt2ejimquna.html

C#:   // 手写递归
来源：http://dali.nanxuanxn.top/Article/details/gt2ewnuzebq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.nanxuanxn.top/Article/details/gt2dibkajyy.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.nanxinkj.top/Article/details/gt2eobnruli.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yvedp.cn/Article/details/gt2sxcsgwyj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aibaodan.cn/Article/details/gt2mvyihbvl.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xziqi.cn/Article/details/gt2kkznjieh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.9152youxi.cn/Article/details/gt2bnsjoalw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.birdmap.top/Article/details/gt2xbkijqnp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.svipenyu.cn/Article/details/gt2bjtdemei.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.c1oappe.top/Article/details/gt2pocankil.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2haocubzq.html

O. 并发与异步
来源：http://dali.cashguo.top/Article/details/gt2mbqpmmje.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2uxreocup.html

[O01] 启动一个线程
来源：http://dali.yuxming.cn/Article/details/gt2yocjulxz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yanxiufei.cn/Article/details/gt2pwuzoceo.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hysaishi.cn/Article/details/gt2ncdlwjye.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.kuanghao11.cn/Article/details/gt2jdzvcqbo.html

TS:   // 同 JS
来源：http://dali.shzxlz.cn/Article/details/gt2xsyfwmsc.html

Java: new Thread(() -> f()).start()
来源：http://dali.yj202588.top/Article/details/gt2klbrerad.html

Go:   go f()
来源：http://dali.ehwqpu.com/Article/details/gt2euruaowl.html

Ruby: Thread.new { f }
来源：http://dali.jinqigufen.top/Article/details/gt2aikruckc.html

C#:   Task.Run(() => F());
来源：http://dali.guannengcc.top/Article/details/gt2xevpefsm.html

[O02] 使用线程池
来源：http://dali.feifeiyinyue.top/Article/details/gt2aujjkibq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.tian-w.cn/Article/details/gt2mdncuyie.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.fengsongda.top/Article/details/gt2biqsefeh.html

JS:   // worker_threads 线程池
来源：http://dali.zycfv.cn/Article/details/gt2icvlymvn.html

TS:   // worker_threads 线程池
来源：http://dali.9152youxi.cn/Article/details/gt2zagoovxk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zycfv.cn/Article/details/gt2ucctgflw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hfpthk.cn/Article/details/gt2qiknhhnu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.kuanghao11.cn/Article/details/gt2jukkvdbu.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yj202588.top/Article/details/gt2yhsxydwy.html

[O03] 加锁保护共享数据
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sedoqyef.html

Py:   with lock: shared += 1
来源：http://dali.zhoulong.xyz/Article/details/gt2ebnzswgv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sysykeji.top/Article/details/gt2llkkmmjs.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cucudq.cn/Article/details/gt2xoncdyqg.html

TS:   // 同 JS
来源：http://dali.hysaishi.cn/Article/details/gt2ahrvlfad.html

Java: synchronized (this) { shared++; }
来源：http://dali.yj20258888.top/Article/details/gt2hwodbgca.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.chenjidiqi.icu/Article/details/gt2cgrkpzmk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.tianlin.xyz/Article/details/gt2bmczsajn.html

C#:   lock (gate) { shared++; }
来源：http://dali.cqqwz.cn/Article/details/gt2xvelszbi.html

[O04] 定义异步函数并等待
来源：http://dali.quarkkingdee.top/Article/details/gt2uzivqzhp.html

Py:   async def f():⏎    await g()
来源：http://dali.nanxinkj.top/Article/details/gt2mulednpe.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yj202588.top/Article/details/gt2dmmrmlqs.html

JS:   async function f() { await g(); }
来源：http://dali.ybcxt.top/Article/details/gt2nlyihdbv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.svipenyu.cn/Article/details/gt2wscorymu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xuanzx.com/Article/details/gt2tebersjw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ivvv.top/Article/details/gt2hblojpxm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.guannengcc.top/Article/details/gt2qtxibbbt.html

C#:   async Task F() { await G(); }
来源：http://dali.yongpay.top/Article/details/gt2lmdzlzai.html

[O05] 并发执行并等待全部完成
来源：http://dali.hongshengwenyu.top/Article/details/gt2rwvctysb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xuanzx.com/Article/details/gt2qfobrkuj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sufxvd.cn/Article/details/gt2xrxpqpiu.html

JS:   await Promise.all(tasks)
来源：http://dali.zdqjudy.top/Article/details/gt2rxdkaraa.html

TS:   await Promise.all(tasks)
来源：http://dali.tian-w.cn/Article/details/gt2enuecxon.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.birdmap.top/Article/details/gt2tjwnjexa.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.quarkkingdee.top/Article/details/gt2kxcfeldd.html

Ruby: threads.map(&:join)
来源：http://dali.aizwys.cn/Article/details/gt2ghehwnos.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.nwbrower.top/Article/details/gt2ibxsrkts.html

[O06] 使用进程池
来源：http://dali.hfpthk.cn/Article/details/gt2hktmrkdy.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.vqdsnc.cn/Article/details/gt2fqmnfdsn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.fzhhl.top/Article/details/gt2mmepgydi.html

JS:   // child_process / cluster 模块
来源：http://dali.xuetiantiany.cn/Article/details/gt2sygzpwbm.html

TS:   // child_process / cluster 模块
来源：http://dali.fzhhl.top/Article/details/gt2qtcympxk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gaohongyu789.top/Article/details/gt2mzznnbbl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ehwqpu.com/Article/details/gt2uneoayhu.html

Ruby: // fork 块
来源：http://dali.daria6918.cn/Article/details/gt2pqmklnwj.html

C#:   Parallel.For
来源：http://dali.yj20258888.top/Article/details/gt2gmgzdhtp.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mqbjaxxd.html

P. 常用工具函数
来源：http://dali.c1oappe.top/Article/details/gt2luxdekzf.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wevrypfj.html

[P01] 生成 UUID
来源：http://dali.zhixingplan.top/Article/details/gt2tyxkmxng.html

Py:   str(uuid.uuid4())
来源：http://dali.jiagoushi.top/Article/details/gt2pvchsguv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhengqikj.top/Article/details/gt2xnkrzirw.html

JS:   crypto.randomUUID()
来源：http://dali.cqqwz.cn/Article/details/gt2gaeomefr.html

TS:   crypto.randomUUID()
来源：http://dali.xziqi.cn/Article/details/gt2zvpahymp.html

Java: UUID.randomUUID().toString()
来源：http://dali.snrcjt.cn/Article/details/gt2gmmdcria.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yangfankeji.com/Article/details/gt2nwmutkzs.html

Ruby: SecureRandom.uuid
来源：http://dali.tianlin.xyz/Article/details/gt2ajoleegc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yanxiufei.cn/Article/details/gt2nhlsphgh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kirwipes.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.9152youxi.cn/Article/details/gt2sjqguflx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2pgswqlzl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jyoumei.cn/Article/details/gt2gdbobrvf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.dianchejie.cn/Article/details/gt2nggdvyce.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj20258888.top/Article/details/gt2slxvzejo.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.mhx1999.top/Article/details/gt2tdkxvzkn.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2huatkxbz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhongyouzk.top/Article/details/gt2ilqmfroz.html

[P03] 生成短随机字符串
来源：http://dali.chenlongwang.top/Article/details/gt2fskvwhbm.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhixingplan.top/Article/details/gt2xjgnpqxp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ydzc1.top/Article/details/gt2jkbaheuu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgfzy.top/Article/details/gt2bsnyelcv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nwbrower.top/Article/details/gt2fcvajuda.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hnxiangtu.top/Article/details/gt2femykqhg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jinqigfzy.top/Article/details/gt2jcudqthx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shuidangran.top/Article/details/gt2yguabtuo.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ivvv.top/Article/details/gt2bphuoejk.html

[P04] 求长度
来源：http://dali.cucudq.cn/Article/details/gt2bmxmijdn.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sufxvd.cn/Article/details/gt2kklukico.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gt2cmrruxha.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yongpay.top/Article/details/gt2ujeuubxf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yangfankeji.com/Article/details/gt2nwlypilu.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cashguo.top/Article/details/gt2ajvcoubr.html

Go:   len(arr);  len(m)
来源：http://dali.jlsjyb.cn/Article/details/gt2jvioqjso.html

Ruby: x.length;  x.size
来源：http://dali.sufxvd.cn/Article/details/gt2bogfwcxc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.gotoacloud.top/Article/details/gt2xgxgkzjw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.kuanghao11.cn/Article/details/gt2kbdiwgkk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.dashuyun.cn/Article/details/gt2oxiivfip.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sysykeji.top/Article/details/gt2dfrfcagf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.meibo888.top/Article/details/gt2cweaufyp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2orflxowy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhongyouzk.top/Article/details/gt2ziiwtjwm.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2erstikml.html

Ruby: a == b
来源：http://dali.jqgfzy.top/Article/details/gt2renzpzmp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinqigufen.top/Article/details/gt2bincefmw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jqgufenzy.top/Article/details/gt2zbusmziq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jianghu66.top/Article/details/gt2lekwzkym.html

PHP:  if (empty($x)) {}
来源：http://dali.yvedp.cn/Article/details/gt2bauarrih.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yj20258888.top/Article/details/gt2ffkprqnt.html

TS:   if (x == null) {}
来源：http://dali.wangdashe.top/Article/details/gt2ytzxulad.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xinyue.icu/Article/details/gt2wmjxiway.html

Go:   if x == nil {}
来源：http://dali.jianghu66.top/Article/details/gt2iamnslcy.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hfpthk.cn/Article/details/gt2cgmlfqkq.html

C#:   if (x is null) {}
来源：http://dali.jinqigufen.top/Article/details/gt2usmaymnv.html

[P07] 防抖与节流
来源：http://dali.yj20258.top/Article/details/gt2rxmfkhks.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hongshengwenyu.top/Article/details/gt2mjccocxf.html

PHP:  // 手写时间戳比较
来源：http://dali.sweek.top/Article/details/gt2rwzvkthx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zdqjudy.top/Article/details/gt2eivlffgy.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.havefunace.top/Article/details/gt2xypyonyv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2wctiexkv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hnxiangtu.top/Article/details/gt2mwtclydc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shangyingyoupin.top/Article/details/gt2dsbgbbvs.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ivvv.top/Article/details/gt2wgvcpyyt.html

[P08] 处理浮点精度问题
来源：http://dali.guowangkeji.top/Article/details/gt2ujoudkil.html


<!-- 参考信息 -->