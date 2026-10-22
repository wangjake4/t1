代发 wailian999

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhiwuduotai.top/Article/details/gt2vmihhwzs.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hammf.cn/Article/details/gt2nsqbaqyi.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yueranfly.top/Article/details/gt2wopbrlga.html

C#:   Process.Start("ls", "-l");
来源：http://dali.wangshuangyany.cn/Article/details/gt2igxyzfty.html

[M04] 获取当前工作目录
来源：http://dali.dashuyun.cn/Article/details/gt2vhhpggfy.html

Py:   os.getcwd()
来源：http://dali.gotoacloud.top/Article/details/gt2xspjesvp.html

PHP:  getcwd();
来源：http://dali.zhixingplan.top/Article/details/gt2nolhrhpd.html

JS:   process.cwd()
来源：http://dali.sufxvd.cn/Article/details/gt2oqorretz.html

TS:   process.cwd()
来源：http://dali.sufxvd.cn/Article/details/gt2xmopofgw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hnxiangtu.top/Article/details/gt2mxpxwgva.html

Go:   os.Getwd()
来源：http://dali.mhx1999.top/Article/details/gt2pqxnqffh.html

Ruby: Dir.pwd
来源：http://dali.hongshengwenyu.top/Article/details/gt2byiizgtp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zdqjudy.top/Article/details/gt2ztsimlgi.html

[M05] 设置退出码
来源：http://dali.fzhhl.top/Article/details/gt2uhbqtkbn.html

Py:   sys.exit(1)
来源：http://dali.yvedp.cn/Article/details/gt2okhlnndl.html

PHP:  exit(1);
来源：http://dali.hfpthk.cn/Article/details/gt2tovdzgnf.html

JS:   process.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gt2hijheqle.html

TS:   process.exit(1)
来源：http://dali.redwolf501.top/Article/details/gt2iqgtgnjs.html

Java: System.exit(1)
来源：http://dali.birdmap.top/Article/details/gt2qkhjkkmu.html

Go:   os.Exit(1)
来源：http://dali.haohaochexian.top/Article/details/gt2tnwrsdnh.html

Ruby: exit 1
来源：http://dali.snrcjt.cn/Article/details/gt2tvjyvdti.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jqgfzy.top/Article/details/gt2xiumtzlf.html

[M06] 向标准错误输出
来源：http://dali.xziqi.cn/Article/details/gt2lnmagdwt.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zycfv.cn/Article/details/gt2zhrsvzkr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zycfv.cn/Article/details/gt2argjgydv.html

JS:   console.error("err")
来源：http://dali.hywenlv.cn/Article/details/gt2uglnuwcp.html

TS:   console.error("err")
来源：http://dali.nwbrower.top/Article/details/gt2wgwuqzwu.html

Java: System.err.println("err")
来源：http://dali.dashuyun.cn/Article/details/gt2clcxqmbs.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.aizwys.cn/Article/details/gt2jilckhrm.html

Ruby: warn "err"
来源：http://dali.0kj1m.cn/Article/details/gt2bbyjpexe.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhongyouzk.top/Article/details/gt2womhzblu.html

[M07] 判断是否为主入口
来源：http://dali.shangyingyoupin.top/Article/details/gt2garzzmlz.html

Py:   if __name__ == "__main__":
来源：http://dali.zhongyouzk.top/Article/details/gt2xgfzxhde.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cdnleiting.top/Article/details/gt2nxzivxgc.html

JS:   require.main === module
来源：http://dali.pycfn.com/Article/details/gt2zbvqhjty.html

TS:   require.main === module
来源：http://dali.daria6918.cn/Article/details/gt2xmdmwubi.html

Java: public static void main(String[] args)
来源：http://dali.iojbl.cn/Article/details/gt2eyrxnafi.html

Go:   func main()
来源：http://dali.feifeiyinyue.top/Article/details/gt2meinsbut.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.0kj1m.cn/Article/details/gt2uzptljgg.html

C#:   static void Main(string[] args)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vfqqivwt.html

[M08] 获取系统与运行时信息
来源：http://dali.iojbl.cn/Article/details/gt2otyvyylf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gogol.net.cn/Article/details/gt2shkonnwg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hpibzgtu.html

JS:   process.platform;  process.version
来源：http://dali.tian-w.cn/Article/details/gt2dfwljlnc.html

TS:   process.platform;  process.version
来源：http://dali.hammf.cn/Article/details/gt2yiawsfbc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xziqi.cn/Article/details/gt2ymwaficm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cdnleiting.top/Article/details/gt2ovxwsgsd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yuanzhike.top/Article/details/gt2daeqiews.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.chenzaomai.com/Article/details/gt2hesdszyd.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2nzpwrhgo.html

N. 数据结构与算法
来源：http://dali.tian-w.cn/Article/details/gt2vkxaudhl.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2edvglonw.html

[N01] 二分查找（有序数组）
来源：http://dali.316326.xyz/Article/details/gt2gwkahnnz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cashguo.top/Article/details/gt2klzztvfy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yongpay.top/Article/details/gt2whbuvrpw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.0kj1m.cn/Article/details/gt2kujzmehx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daxiang520.top/Article/details/gt2atludwro.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yj20258888.top/Article/details/gt2vjsuphya.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gt2lguzspwh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.redwolf501.top/Article/details/gt2qdenvbll.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gt2tsylngtg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jqgfzy.top/Article/details/gt2yrdruyri.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yongpay.top/Article/details/gt2koohdzak.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jianghu66.top/Article/details/gt2lklepvtp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.bjfxy.top/Article/details/gt2zolnjbjz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.redwolf501.top/Article/details/gt2pywuewqv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.aibaodan.cn/Article/details/gt2mxtfthjm.html

Go:   slices.Sort(arr)
来源：http://dali.316326.xyz/Article/details/gt2lzpfobmg.html

Ruby: arr.sort
来源：http://dali.cashguo.top/Article/details/gt2rdjvneso.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.meibo888.top/Article/details/gt2aegydzoj.html

[N03] 快速排序（分治示例）
来源：http://dali.jqgufenzy.top/Article/details/gt2pplvgwbd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hammf.cn/Article/details/gt2qitmnkyk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.vqdsnc.cn/Article/details/gt2pplkkwqb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuetiantiany.cn/Article/details/gt2ruqxovic.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hnxiangtu.top/Article/details/gt2cggialjr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.birdmap.top/Article/details/gt2gcvuplhy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gotoacloud.top/Article/details/gt2qvoieuyf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.bjfxy.top/Article/details/gt2nxzencvw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.wangshuangyany.cn/Article/details/gt2wuntogol.html

[N04] 斐波那契数列
来源：http://dali.yuanzhike.top/Article/details/gt2yxdnvfjc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigufen.top/Article/details/gt2beiuiypx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.fengsongda.top/Article/details/gt2lxnsjnuo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gotoacloud.top/Article/details/gt2frtwpcje.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shangyingyoupin.top/Article/details/gt2lujbhfda.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.guowangkeji.top/Article/details/gt2znnkatke.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jlsjyb.cn/Article/details/gt2yljxifyg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hammf.cn/Article/details/gt2cskzxgqg.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hammf.cn/Article/details/gt2kjmsufbo.html

[N05] 最大公约数
来源：http://dali.hnxiangtu.top/Article/details/gt2gqxgfwma.html

Py:   math.gcd(a, b)
来源：http://dali.sweek.top/Article/details/gt2ykqekmth.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.tian-w.cn/Article/details/gt2akvwtbvk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.redwolf501.top/Article/details/gt2qptcetgu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jqgufenzy.top/Article/details/gt2sjomauwk.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cashguo.top/Article/details/gt2mqotfukq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.gotoacloud.top/Article/details/gt2kbnylzev.html

Ruby: a.gcd(b)
来源：http://dali.xylfe.cn/Article/details/gt2enhhlvvv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.guowangkeji.top/Article/details/gt2jaqbzjbz.html

[N06] 判断回文字符串
来源：http://dali.jyoumei.cn/Article/details/gt2monpxmbc.html

Py:   s == s[::-1]
来源：http://dali.xylfe.cn/Article/details/gt2uslhhkto.html

PHP:  $s === strrev($s);
来源：http://dali.birdmap.top/Article/details/gt2fdursjqz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gt2ommnsfuf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2anvpdrku.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cdnleiting.top/Article/details/gt2khuijemj.html

Go:   // 双指针从两端比较
来源：http://dali.sysykeji.top/Article/details/gt2uckkhdbc.html

Ruby: s == s.reverse
来源：http://dali.snrcjt.cn/Article/details/gt2admgoidb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.nanxuanxn.top/Article/details/gt2bufcegjt.html

[N07] 两数之和（返回下标）
来源：http://dali.hongshengwenyu.top/Article/details/gt2slygecmq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gzhubu.top/Article/details/gt2heozxbci.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.nanxinkj.top/Article/details/gt2uspifixz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.guannengcc.top/Article/details/gt2lltqxkyf.html

TS:   // 手写 Map<string, number>
来源：http://dali.tian-w.cn/Article/details/gt2bvvcbjqa.html

Java: // 手写 HashMap
来源：http://dali.nanxinkj.top/Article/details/gt2gvbsedrl.html

Go:   // 手写 map[int]int
来源：http://dali.hnxiangtu.top/Article/details/gt2aemzftgo.html

Ruby: // 手写 Hash
来源：http://dali.yangfankeji.com/Article/details/gt2kpzzlrku.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oufchzjk.html

[N08] 生成全排列
来源：http://dali.nwbrower.top/Article/details/gt2gkioulxg.html

Py:   itertools.permutations(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2qltuhosz.html

PHP:  // 手写递归交换
来源：http://dali.smart0.xyz/Article/details/gt2kejfhmrb.html

JS:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gt2ytpusqcr.html

TS:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gt2lrtceecj.html

Java: // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gt2ugzeqgge.html

Go:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gt2asipkrey.html

Ruby: arr.permutation.to_a
来源：http://dali.sufxvd.cn/Article/details/gt2pocxhkpt.html

C#:   // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gt2ftiiufwz.html

[N09] 栈与队列
来源：http://dali.andypj.xyz/Article/details/gt2scjxeaul.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hnqzz.top/Article/details/gt2kcdemxcc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.vqdsnc.cn/Article/details/gt2cajwmrdp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.316326.xyz/Article/details/gt2olwhqrqm.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.svipenyu.cn/Article/details/gt2rnfmzidx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.wangshuangyany.cn/Article/details/gt2qylddbuw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hysaishi.cn/Article/details/gt2cqgexcrr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yonumen.top/Article/details/gt2zowppobq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zycfv.cn/Article/details/gt2rbzfzrrn.html

[N10] 链表节点定义
来源：http://dali.ivvv.top/Article/details/gt2yorbblcu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jiagoushi.top/Article/details/gt2ggssjwck.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pytmhhil.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gogol.net.cn/Article/details/gt2ecvmweow.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xuetiantiany.cn/Article/details/gt2mlzmwhta.html

Java: class Node { int v; Node next; }
来源：http://dali.yangfankeji.com/Article/details/gt2pkirxsts.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jiagoushi.top/Article/details/gt2jnfdmmdg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.guannengcc.top/Article/details/gt2zzpmyofo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dviklwpw.html

[N11] 二叉树中序遍历
来源：http://dali.zhengqikj.top/Article/details/gt2bwmvalfj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yueranfly.top/Article/details/gt2tjdcljle.html

PHP:  // 手写递归函数
来源：http://dali.sufxvd.cn/Article/details/gt2dnsqryvy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pengpengdd.cyou/Article/details/gt2aeppfrvi.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daria6918.cn/Article/details/gt2gyarxjea.html

Java: // 手写递归
来源：http://dali.jinqigufen.top/Article/details/gt2mfhoonie.html

Go:   // 手写递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rgrrfang.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gogol.net.cn/Article/details/gt2clzzqryw.html

C#:   // 手写递归
来源：http://dali.cheryme.top/Article/details/gt2mxcrknym.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xziqi.cn/Article/details/gt2lcqvfjqg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yvedp.cn/Article/details/gt2lxxwgohl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.dashuyun.cn/Article/details/gt2gzyogccg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yongpay.top/Article/details/gt2euwgzclz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uuwxesxn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.haohaochexian.top/Article/details/gt2gboyoaev.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yangfankeji.com/Article/details/gt2vplvateq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xinyue.icu/Article/details/gt2gphczgvl.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yangfankeji.com/Article/details/gt2oceajdzm.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2mwrsnqri.html

O. 并发与异步
来源：http://dali.feifeiyinyue.top/Article/details/gt2qxnfxtfh.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2hzzzerjr.html

[O01] 启动一个线程
来源：http://dali.andypj.xyz/Article/details/gt2kgftgfhc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gogol.net.cn/Article/details/gt2wmjbpoji.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cashguo.top/Article/details/gt2uethdwxi.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yanxiufei.cn/Article/details/gt2cpvzjcgj.html

TS:   // 同 JS
来源：http://dali.yueranfly.top/Article/details/gt2itjkbtzb.html

Java: new Thread(() -> f()).start()
来源：http://dali.shangyingyoupin.top/Article/details/gt2zraujxvq.html

Go:   go f()
来源：http://dali.fengsongda.top/Article/details/gt2fgdfvbox.html

Ruby: Thread.new { f }
来源：http://dali.yj20258888.top/Article/details/gt2sxupiool.html

C#:   Task.Run(() => F());
来源：http://dali.vqdsnc.cn/Article/details/gt2xjpappte.html

[O02] 使用线程池
来源：http://dali.cucudq.cn/Article/details/gt2icymarhj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hywenlv.cn/Article/details/gt2rkhrbshl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yuanzhike.top/Article/details/gt2dmfhqvzn.html

JS:   // worker_threads 线程池
来源：http://dali.hysaishi.cn/Article/details/gt2gyqgsroj.html

TS:   // worker_threads 线程池
来源：http://dali.guowangkeji.top/Article/details/gt2vrskzcrt.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhoulong.xyz/Article/details/gt2httbrvqs.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.guannengcc.top/Article/details/gt2dhxbdykn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.meibo888.top/Article/details/gt2qexfhnae.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ppjwa.cn/Article/details/gt2ggxvgfng.html

[O03] 加锁保护共享数据
来源：http://dali.xuetiantiany.cn/Article/details/gt2hxvsyjtv.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2txqoamew.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jqgfzy.top/Article/details/gt2jbozbsag.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinqigfzy.top/Article/details/gt2iazufeat.html

TS:   // 同 JS
来源：http://dali.bjfxy.top/Article/details/gt2igltjbcl.html

Java: synchronized (this) { shared++; }
来源：http://dali.gaohongyu789.top/Article/details/gt2ajnepizt.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.0kj1m.cn/Article/details/gt2sjimdgcs.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.nanxinkj.top/Article/details/gt2qvgbajik.html

C#:   lock (gate) { shared++; }
来源：http://dali.cqqwz.cn/Article/details/gt2pgragnil.html

[O04] 定义异步函数并等待
来源：http://dali.xuetiantiany.cn/Article/details/gt2pjxmgarn.html

Py:   async def f():⏎    await g()
来源：http://dali.chenlongwang.top/Article/details/gt2ffzdlynh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zycfv.cn/Article/details/gt2qogxdzwv.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjkygkgq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2igouyalq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xziqi.cn/Article/details/gt2ldocaouk.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hywenlv.cn/Article/details/gt2brxyrqfo.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.sweek.top/Article/details/gt2qskeksus.html

C#:   async Task F() { await G(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2odegyotq.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rxiuqshu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yonumen.top/Article/details/gt2wyfgegxv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.quarkkingdee.top/Article/details/gt2thzdraxm.html

JS:   await Promise.all(tasks)
来源：http://dali.hnxiangtu.top/Article/details/gt2hjblksej.html

TS:   await Promise.all(tasks)
来源：http://dali.hywenlv.cn/Article/details/gt2hfapmmvf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yonumen.top/Article/details/gt2donoeosu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ppjwa.cn/Article/details/gt2refmldiw.html

Ruby: threads.map(&:join)
来源：http://dali.aizwys.cn/Article/details/gt2xlgdpirs.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zycfv.cn/Article/details/gt2fbhxdpwt.html

[O06] 使用进程池
来源：http://dali.vqdsnc.cn/Article/details/gt2ufcaefjh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.smart0.xyz/Article/details/gt2taddnski.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jianghu66.top/Article/details/gt2yaiokuxh.html

JS:   // child_process / cluster 模块
来源：http://dali.chenzaomai.com/Article/details/gt2osjtrknb.html

TS:   // child_process / cluster 模块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fiulaacz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.9152youxi.cn/Article/details/gt2qvkwlovr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hfpthk.cn/Article/details/gt2ypntjoeh.html

Ruby: // fork 块
来源：http://dali.dashuyun.cn/Article/details/gt2iccgdlpn.html

C#:   Parallel.For
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2thqgyggj.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2okktkcnt.html

P. 常用工具函数
来源：http://dali.cucudq.cn/Article/details/gt2vyecotot.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2lyskbkos.html

[P01] 生成 UUID
来源：http://dali.fzhhl.top/Article/details/gt2mlsfcgmv.html

Py:   str(uuid.uuid4())
来源：http://dali.zycfv.cn/Article/details/gt2bhvgprdy.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jlsjyb.cn/Article/details/gt2okglnloc.html

JS:   crypto.randomUUID()
来源：http://dali.jinqigufen.top/Article/details/gt2gshisdwv.html

TS:   crypto.randomUUID()
来源：http://dali.zhongyouzk.top/Article/details/gt2hxssaoda.html

Java: UUID.randomUUID().toString()
来源：http://dali.daria6918.cn/Article/details/gt2hcxrmxtv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.redwolf501.top/Article/details/gt2xgiuvide.html

Ruby: SecureRandom.uuid
来源：http://dali.xuanzx.com/Article/details/gt2mkpplsls.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yongpay.top/Article/details/gt2nryamduq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cdnleiting.top/Article/details/gt2jcaibbjt.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shangyingyoupin.top/Article/details/gt2uwhzihfx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xmmvjycw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.nanxuanxn.top/Article/details/gt2rcpanmvy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.9152youxi.cn/Article/details/gt2vfmmyxml.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.tianlin.xyz/Article/details/gt2itvyvmaj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hnqzz.top/Article/details/gt2urnltanx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhengqikj.top/Article/details/gt2lirkchqd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.bjfxy.top/Article/details/gt2eypaayyp.html

[P03] 生成短随机字符串
来源：http://dali.dianchejie.cn/Article/details/gt2ifigvubi.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.smart0.xyz/Article/details/gt2hewnruxm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yj202588.top/Article/details/gt2ytruwtxc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pycfn.com/Article/details/gt2fbyirigq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ehwqpu.com/Article/details/gt2vmofemff.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yangfankeji.com/Article/details/gt2evhbsphg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jinqigfzy.top/Article/details/gt2bqantuul.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.snrcjt.cn/Article/details/gt2cvaebxcu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yanxiufei.cn/Article/details/gt2euaptbgi.html

[P04] 求长度
来源：http://dali.tianlin.xyz/Article/details/gt2ehvtjqfy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.nanxinkj.top/Article/details/gt2cbhlldkj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gt2eryzfjvk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.snrcjt.cn/Article/details/gt2xzvuevpo.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xylfe.cn/Article/details/gt2mpvlxndf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.snrcjt.cn/Article/details/gt2daaiknqz.html

Go:   len(arr);  len(m)
来源：http://dali.daria6918.cn/Article/details/gt2alumunmd.html

Ruby: x.length;  x.size
来源：http://dali.jqgufenzy.top/Article/details/gt2pnicwbgy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hnqzz.top/Article/details/gt2pviusvfc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.dianchejie.cn/Article/details/gt2prbzlsus.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gotoacloud.top/Article/details/gt2wqgmtqwy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hysaishi.cn/Article/details/gt2fmvoigfc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.nwbrower.top/Article/details/gt2rtthqmur.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.aibaodan.cn/Article/details/gt2uplleupi.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shangyingyoupin.top/Article/details/gt2xwweekqm.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.daria6918.cn/Article/details/gt2nedvtivz.html

Ruby: a == b
来源：http://dali.chenjidiqi.icu/Article/details/gt2csycasta.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jnsgswyu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.meibo888.top/Article/details/gt2jxzhbcca.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.dashuyun.cn/Article/details/gt2wnckncfw.html

PHP:  if (empty($x)) {}
来源：http://dali.wangdashe.top/Article/details/gt2qxtrysxz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.kuanghao11.cn/Article/details/gt2lxlimakj.html

TS:   if (x == null) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2iziheipu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hywenlv.cn/Article/details/gt2raedbplv.html

Go:   if x == nil {}
来源：http://dali.zhongyouzk.top/Article/details/gt2wamjpysr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jlsjyb.cn/Article/details/gt2utgxcaid.html

C#:   if (x is null) {}
来源：http://dali.fzhhl.top/Article/details/gt2fggobfmf.html

[P07] 防抖与节流
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fgbedjpl.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.sweek.top/Article/details/gt2sjoowdbg.html

PHP:  // 手写时间戳比较
来源：http://dali.xuetiantiany.cn/Article/details/gt2azqrgqzd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ivvv.top/Article/details/gt2ygorqhaj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxuanxn.top/Article/details/gt2bpynjdkq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hammf.cn/Article/details/gt2vabhrzkh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jianghu66.top/Article/details/gt2smdpmdam.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hxemztrh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ppjwa.cn/Article/details/gt2pxaasftx.html

[P08] 处理浮点精度问题
来源：http://dali.tianlin.xyz/Article/details/gt2ydzughld.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yj20258.top/Article/details/gt2exyhubuq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.iojbl.cn/Article/details/gt2itgbqbjp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.pycfn.com/Article/details/gt2xqqqxrck.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.nwbrower.top/Article/details/gt2dtuetpbh.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinqigfzy.top/Article/details/gt2dmjcvmkv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhiwuduotai.top/Article/details/gt2wdsdgqnm.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hfpthk.cn/Article/details/gt2kftqjwnx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jqgfzy.top/Article/details/gt2thihgapm.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2ixkeevon.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.guowangkeji.top/Article/details/gt2swluerfm.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2atadewrw.html

[Q01] 创建表
来源：http://dali.cucudq.cn/Article/details/gt2ozazpydf.html

CREATE TABLE users (
来源：http://dali.feifeiyinyue.top/Article/details/gt2mejfpicc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.kuanghao11.cn/Article/details/gt2fyfpzewm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jfwtinyg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jinqigufen.top/Article/details/gt2tvtrjmpj.html


<!-- 参考信息 -->