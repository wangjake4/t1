代发 wailian999

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jyoumei.cn/Article/details/gt2aqohgxys.html

[M05] 设置退出码
来源：http://dali.fzhhl.top/Article/details/gt2jsymjemw.html

Py:   sys.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gt2udmuybfv.html

PHP:  exit(1);
来源：http://dali.316326.xyz/Article/details/gt2rjwaeuaz.html

JS:   process.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kuwpejfv.html

TS:   process.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qhextchi.html

Java: System.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gt2vxrkrcla.html

Go:   os.Exit(1)
来源：http://dali.iojbl.cn/Article/details/gt2knvmlzid.html

Ruby: exit 1
来源：http://dali.redwolf501.top/Article/details/gt2tmviawld.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.316326.xyz/Article/details/gt2otgdeuln.html

[M06] 向标准错误输出
来源：http://dali.yj202588.top/Article/details/gt2ozhfojpb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.c1oappe.top/Article/details/gt2ulcllnkl.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.birdmap.top/Article/details/gt2yjrhuwod.html

JS:   console.error("err")
来源：http://dali.cucudq.cn/Article/details/gt2iicqrwsm.html

TS:   console.error("err")
来源：http://dali.chenjidiqi.icu/Article/details/gt2diofpuzk.html

Java: System.err.println("err")
来源：http://dali.wangdashe.top/Article/details/gt2lbevdfct.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.chenjidiqi.icu/Article/details/gt2minybpdz.html

Ruby: warn "err"
来源：http://dali.hysaishi.cn/Article/details/gt2mbiyyxoq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shzxlz.cn/Article/details/gt2fyomcafv.html

[M07] 判断是否为主入口
来源：http://dali.zhixingplan.top/Article/details/gt2ezrqqaxg.html

Py:   if __name__ == "__main__":
来源：http://dali.jlsjyb.cn/Article/details/gt2icnlfkax.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hywenlv.cn/Article/details/gt2axinweue.html

JS:   require.main === module
来源：http://dali.hnxiangtu.top/Article/details/gt2ungrdsfs.html

TS:   require.main === module
来源：http://dali.daria6918.cn/Article/details/gt2aaglaqdh.html

Java: public static void main(String[] args)
来源：http://dali.dashuyun.cn/Article/details/gt2nenricif.html

Go:   func main()
来源：http://dali.yj20258888.top/Article/details/gt2ofdeemrn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ehwqpu.com/Article/details/gt2erpdglya.html

C#:   static void Main(string[] args)
来源：http://dali.jinqigufen.top/Article/details/gt2zxxaksdv.html

[M08] 获取系统与运行时信息
来源：http://dali.zdqjudy.top/Article/details/gt2qbdovcjy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.wangdashe.top/Article/details/gt2dtihhbyn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhongyouzk.top/Article/details/gt2bappadlw.html

JS:   process.platform;  process.version
来源：http://dali.tian-w.cn/Article/details/gt2gugyrour.html

TS:   process.platform;  process.version
来源：http://dali.xziqi.cn/Article/details/gt2tlqnkmsm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hfpthk.cn/Article/details/gt2bzlxkzyc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zycfv.cn/Article/details/gt2bygveyhi.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.iojbl.cn/Article/details/gt2rftvgyjb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hnxiangtu.top/Article/details/gt2ihhqeztu.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2clvnatlg.html

N. 数据结构与算法
来源：http://dali.fzhhl.top/Article/details/gt2ehkdcblt.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2cporqrrj.html

[N01] 二分查找（有序数组）
来源：http://dali.havefunace.top/Article/details/gt2glgjrxue.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yonumen.top/Article/details/gt2stmnpgqh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.redwolf501.top/Article/details/gt2ukjdthvx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigfzy.top/Article/details/gt2bkhmelqt.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.birdmap.top/Article/details/gt2ednfawek.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gt2zvbhukra.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gt2whyunvaj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.chenzaomai.com/Article/details/gt2lpotjbqr.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cucudq.cn/Article/details/gt2uilkqyqy.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hnqzz.top/Article/details/gt2taoptfmx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tian-w.cn/Article/details/gt2fryealio.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ppjwa.cn/Article/details/gt2hkiotbdl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daria6918.cn/Article/details/gt2vijengac.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cucudq.cn/Article/details/gt2vwrcemtg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.gotoacloud.top/Article/details/gt2ebbabjxo.html

Go:   slices.Sort(arr)
来源：http://dali.zycfv.cn/Article/details/gt2zpeplryd.html

Ruby: arr.sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jgejgxmr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shuidangran.top/Article/details/gt2xqbpwqqm.html

[N03] 快速排序（分治示例）
来源：http://dali.jinqigufen.top/Article/details/gt2lwobabzo.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.nwbrower.top/Article/details/gt2eysvnxwm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.c1oappe.top/Article/details/gt2ooxcqdfw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sweek.top/Article/details/gt2nnbhheqn.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sufxvd.cn/Article/details/gt2olsbdgve.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cdnleiting.top/Article/details/gt2uyumbamk.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.tianlin.xyz/Article/details/gt2esziqwcd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cdnleiting.top/Article/details/gt2fhbbhxgw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gaohongyu789.top/Article/details/gt2fwitnbis.html

[N04] 斐波那契数列
来源：http://dali.svipenyu.cn/Article/details/gt2bccduksj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.316326.xyz/Article/details/gt2kssrcxus.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.daria6918.cn/Article/details/gt2uoomhrwm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gt2nisumicl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yvedp.cn/Article/details/gt2tkgynrks.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhongyouzk.top/Article/details/gt2ojljmora.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.fzhhl.top/Article/details/gt2bwevwxke.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2mnztdcjn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jqgufenzy.top/Article/details/gt2ipkhtgvv.html

[N05] 最大公约数
来源：http://dali.nanxuanxn.top/Article/details/gt2sgujfxvy.html

Py:   math.gcd(a, b)
来源：http://dali.cdnleiting.top/Article/details/gt2akarweos.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hywenlv.cn/Article/details/gt2sylnqnjp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sweek.top/Article/details/gt2gjjzmnul.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yueranfly.top/Article/details/gt2vvukwfmp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.snrcjt.cn/Article/details/gt2gzxkotga.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.fzhhl.top/Article/details/gt2tmdxznyp.html

Ruby: a.gcd(b)
来源：http://dali.chenlongwang.top/Article/details/gt2otuwontf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2wsyfqyfg.html

[N06] 判断回文字符串
来源：http://dali.cheryme.top/Article/details/gt2mvokizha.html

Py:   s == s[::-1]
来源：http://dali.yj20258.top/Article/details/gt2npoxofty.html

PHP:  $s === strrev($s);
来源：http://dali.yvedp.cn/Article/details/gt2dihjyedj.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hammf.cn/Article/details/gt2uolgjaqy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.bjfxy.top/Article/details/gt2uqcknjlh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.wangdashe.top/Article/details/gt2mfqvuomq.html

Go:   // 双指针从两端比较
来源：http://dali.shangyingyoupin.top/Article/details/gt2odtesxcb.html

Ruby: s == s.reverse
来源：http://dali.yangfankeji.com/Article/details/gt2vhpkjppd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hywenlv.cn/Article/details/gt2ciwtfylm.html

[N07] 两数之和（返回下标）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hjqfleqz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ehwqpu.com/Article/details/gt2unocgjem.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.9152youxi.cn/Article/details/gt2xcsecgdc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yonumen.top/Article/details/gt2lxtbatrz.html

TS:   // 手写 Map<string, number>
来源：http://dali.dianchejie.cn/Article/details/gt2konkdjmy.html

Java: // 手写 HashMap
来源：http://dali.hongshengwenyu.top/Article/details/gt2liqwiabg.html

Go:   // 手写 map[int]int
来源：http://dali.shzxlz.cn/Article/details/gt2qtdbybbe.html

Ruby: // 手写 Hash
来源：http://dali.chenjidiqi.icu/Article/details/gt2ziojcghr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ehwqpu.com/Article/details/gt2gofrkyxe.html

[N08] 生成全排列
来源：http://dali.tian-w.cn/Article/details/gt2kevzzzki.html

Py:   itertools.permutations(arr)
来源：http://dali.meibo888.top/Article/details/gt2hsztlvct.html

PHP:  // 手写递归交换
来源：http://dali.mhx1999.top/Article/details/gt2icgyjfwi.html

JS:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gt2brhurvll.html

TS:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gt2rekpngqh.html

Java: // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gt2tvcgwolg.html

Go:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gt2etxsqfnj.html

Ruby: arr.permutation.to_a
来源：http://dali.nanxuanxn.top/Article/details/gt2tlvkofpa.html

C#:   // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gt2lorwiacn.html

[N09] 栈与队列
来源：http://dali.hongshengwenyu.top/Article/details/gt2fgyybfok.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gt2egblhhhs.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gt2pyoiwxzv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.havefunace.top/Article/details/gt2khyjiehj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.aibaodan.cn/Article/details/gt2ojccmimc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.birdmap.top/Article/details/gt2xocbobkm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.smart0.xyz/Article/details/gt2xbtidmku.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.aizwys.cn/Article/details/gt2gxgussrm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.dashuyun.cn/Article/details/gt2ccawtigs.html

[N10] 链表节点定义
来源：http://dali.snrcjt.cn/Article/details/gt2wixfldhs.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.chenjidiqi.icu/Article/details/gt2skysulyl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jqgfzy.top/Article/details/gt2erikjqdj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jqgfzy.top/Article/details/gt2kaseucwh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.andypj.xyz/Article/details/gt2evwgimha.html

Java: class Node { int v; Node next; }
来源：http://dali.jlsjyb.cn/Article/details/gt2dfevwafm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shangyingyoupin.top/Article/details/gt2jdtmezza.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.snrcjt.cn/Article/details/gt2pelagnvb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2naercxiz.html

[N11] 二叉树中序遍历
来源：http://dali.jinqigfzy.top/Article/details/gt2gharmatx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zdqjudy.top/Article/details/gt2jidfilwu.html

PHP:  // 手写递归函数
来源：http://dali.gzhubu.top/Article/details/gt2ndvygupz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tanke756.top/Article/details/gt2xsrulnlw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tanke756.top/Article/details/gt2xtyjgttq.html

Java: // 手写递归
来源：http://dali.c1oappe.top/Article/details/gt2tjswaawf.html

Go:   // 手写递归
来源：http://dali.9152youxi.cn/Article/details/gt2fdvjerdk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gzhubu.top/Article/details/gt2jfofvysk.html

C#:   // 手写递归
来源：http://dali.ehwqpu.com/Article/details/gt2mjyjtbrf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xziqi.cn/Article/details/gt2ztrtoyds.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xuetiantiany.cn/Article/details/gt2rrvznyun.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.birdmap.top/Article/details/gt2wpnvmlgk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ydzc1.top/Article/details/gt2weiqkikj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tanke756.top/Article/details/gt2mazcrkxb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj202588.top/Article/details/gt2ezewbyru.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.tanke756.top/Article/details/gt2zhebqhcj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.redwolf501.top/Article/details/gt2xpfxywgg.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhiwuduotai.top/Article/details/gt2lhjcbqeh.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2kwxicauu.html

O. 并发与异步
来源：http://dali.xylfe.cn/Article/details/gt2vjekniut.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2elexusqp.html

[O01] 启动一个线程
来源：http://dali.gaohongyu789.top/Article/details/gt2xolawtnp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shuidangran.top/Article/details/gt2ususxjrh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xinyue.icu/Article/details/gt2qfbwfdde.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hammf.cn/Article/details/gt2qmrbsfxe.html

TS:   // 同 JS
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ocarjgoi.html

Java: new Thread(() -> f()).start()
来源：http://dali.shuidangran.top/Article/details/gt2wnvqadol.html

Go:   go f()
来源：http://dali.xinyue.icu/Article/details/gt2jemxdwdr.html

Ruby: Thread.new { f }
来源：http://dali.chenlongwang.top/Article/details/gt2lltezoca.html

C#:   Task.Run(() => F());
来源：http://dali.xuanzx.com/Article/details/gt2pwadmrqd.html

[O02] 使用线程池
来源：http://dali.9152youxi.cn/Article/details/gt2kmlpdffq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.tian-w.cn/Article/details/gt2vfdvedew.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.tianlin.xyz/Article/details/gt2xeozljuf.html

JS:   // worker_threads 线程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fjzrnwcj.html

TS:   // worker_threads 线程池
来源：http://dali.jinqigufen.top/Article/details/gt2gozlpvos.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfsuwium.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shuidangran.top/Article/details/gt2mwripjbc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.feifeiyinyue.top/Article/details/gt2mwvriqhj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hywenlv.cn/Article/details/gt2zfybudhk.html

[O03] 加锁保护共享数据
来源：http://dali.yuxming.cn/Article/details/gt2hylpvvah.html

Py:   with lock: shared += 1
来源：http://dali.hfpthk.cn/Article/details/gt2xmkhdhrn.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.chenzaomai.com/Article/details/gt2nqgkrxmr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhongyouzk.top/Article/details/gt2yswjpwwf.html

TS:   // 同 JS
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2agkolimu.html

Java: synchronized (this) { shared++; }
来源：http://dali.ydzc1.top/Article/details/gt2csbpavef.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.quarkkingdee.top/Article/details/gt2mbfhxwby.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gotoacloud.top/Article/details/gt2cxcjkkdf.html

C#:   lock (gate) { shared++; }
来源：http://dali.xuanzx.com/Article/details/gt2oemctivc.html

[O04] 定义异步函数并等待
来源：http://dali.pycfn.com/Article/details/gt2ttbnqofw.html

Py:   async def f():⏎    await g()
来源：http://dali.iojbl.cn/Article/details/gt2eunbnicz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.quarkkingdee.top/Article/details/gt2bgvjrzcy.html

JS:   async function f() { await g(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kigbwoxz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2rvflzqqm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.aibaodan.cn/Article/details/gt2oltmlqyg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinghuilouyu.cn/Article/details/gt2stukazun.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gaohongyu789.top/Article/details/gt2dzwjoxcz.html

C#:   async Task F() { await G(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2iwbnqnja.html

[O05] 并发执行并等待全部完成
来源：http://dali.bjfxy.top/Article/details/gt2ramynozn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yangfankeji.com/Article/details/gt2twznbzhb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yj20258.top/Article/details/gt2igpyzmqr.html

JS:   await Promise.all(tasks)
来源：http://dali.jyoumei.cn/Article/details/gt2iucntyab.html

TS:   await Promise.all(tasks)
来源：http://dali.dianchejie.cn/Article/details/gt2aatgyufr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yonumen.top/Article/details/gt2vfcyocpf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.fzhhl.top/Article/details/gt2yuxabmig.html

Ruby: threads.map(&:join)
来源：http://dali.cheryme.top/Article/details/gt2rpvkjxai.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.9152youxi.cn/Article/details/gt2rbiazbxh.html

[O06] 使用进程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tquizgev.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.havefunace.top/Article/details/gt2kyfxatcw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xylfe.cn/Article/details/gt2bxjoidue.html

JS:   // child_process / cluster 模块
来源：http://dali.zhongyouzk.top/Article/details/gt2womdkbeo.html

TS:   // child_process / cluster 模块
来源：http://dali.cucudq.cn/Article/details/gt2liesllaw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.kuanghao11.cn/Article/details/gt2jaekfpjn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.dianchejie.cn/Article/details/gt2uocaxrjo.html

Ruby: // fork 块
来源：http://dali.haohaochexian.top/Article/details/gt2jtbnnyik.html

C#:   Parallel.For
来源：http://dali.yj20258888.top/Article/details/gt2hoeojgik.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2moptikux.html

P. 常用工具函数
来源：http://dali.nanxinkj.top/Article/details/gt2jtgdkufk.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2obaxkuga.html

[P01] 生成 UUID
来源：http://dali.hammf.cn/Article/details/gt2cyenoaxq.html

Py:   str(uuid.uuid4())
来源：http://dali.wangdashe.top/Article/details/gt2ierdncgh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sxryk.cn/Article/details/gt2hnuhuygc.html

JS:   crypto.randomUUID()
来源：http://dali.316326.xyz/Article/details/gt2jxhzvrfv.html

TS:   crypto.randomUUID()
来源：http://dali.shangyingyoupin.top/Article/details/gt2zretskmx.html

Java: UUID.randomUUID().toString()
来源：http://dali.daxiang520.top/Article/details/gt2isquauge.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xuetiantiany.cn/Article/details/gt2nahwsncn.html

Ruby: SecureRandom.uuid
来源：http://dali.zhongyouzk.top/Article/details/gt2alzlchbi.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yvedp.cn/Article/details/gt2giwmegav.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sysykeji.top/Article/details/gt2uonfyspo.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gogol.net.cn/Article/details/gt2bbrquyxl.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.bjfxy.top/Article/details/gt2rzyzcjdi.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.smart0.xyz/Article/details/gt2zdrlndsw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xuanzx.com/Article/details/gt2hwxxrktf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.havefunace.top/Article/details/gt2auagsxxr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yj20258888.top/Article/details/gt2mqozpema.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lfpabtne.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhiwuduotai.top/Article/details/gt2bomzrnoo.html

[P03] 生成短随机字符串
来源：http://dali.andypj.xyz/Article/details/gt2demoonzn.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.9152youxi.cn/Article/details/gt2iebzxznu.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.dashuyun.cn/Article/details/gt2iulhadqi.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hammf.cn/Article/details/gt2dsbdmfhr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cucudq.cn/Article/details/gt2cebtvibj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.tian-w.cn/Article/details/gt2jvganxou.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.kuanghao11.cn/Article/details/gt2kwvjfbxj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.mhx1999.top/Article/details/gt2fwaaejwy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhongyouzk.top/Article/details/gt2feszkunx.html

[P04] 求长度
来源：http://dali.shangyingyoupin.top/Article/details/gt2utjzelqb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shangyingyoupin.top/Article/details/gt2jdczekvg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aeihiwep.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jiagoushi.top/Article/details/gt2setxhrpz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xinyue.icu/Article/details/gt2yaucfsuk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhoulong.xyz/Article/details/gt2lqhunsss.html

Go:   len(arr);  len(m)
来源：http://dali.c1oappe.top/Article/details/gt2qgavylwr.html

Ruby: x.length;  x.size
来源：http://dali.yj20258.top/Article/details/gt2oczkisjj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xziqi.cn/Article/details/gt2apgspugr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.kuanghao11.cn/Article/details/gt2fbqstvtn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yj20258888.top/Article/details/gt2hyvllcfo.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhengqikj.top/Article/details/gt2ebakheqk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cdnleiting.top/Article/details/gt2ywbyfxek.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenzaomai.com/Article/details/gt2rjpmcapi.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cucudq.cn/Article/details/gt2srfkwvvc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yvedp.cn/Article/details/gt2byridweo.html

Ruby: a == b
来源：http://dali.jyoumei.cn/Article/details/gt2daxtttpj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yangfankeji.com/Article/details/gt2twebwlwo.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.0kj1m.cn/Article/details/gt2kzdbmkxz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhengqikj.top/Article/details/gt2efdapvgc.html

PHP:  if (empty($x)) {}
来源：http://dali.havefunace.top/Article/details/gt2foqfcqvf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.dashuyun.cn/Article/details/gt2woovzqny.html

TS:   if (x == null) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2kqegfjfb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wymrovno.html

Go:   if x == nil {}
来源：http://dali.iojbl.cn/Article/details/gt2sowsstuw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ybcxt.top/Article/details/gt2rrealopl.html

C#:   if (x is null) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2xkqnutju.html

[P07] 防抖与节流
来源：http://dali.jlsjyb.cn/Article/details/gt2tewnkfnu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yiezxann.html

PHP:  // 手写时间戳比较
来源：http://dali.ivvv.top/Article/details/gt2fyrgabbd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sweek.top/Article/details/gt2ajmivfwn.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenjidiqi.icu/Article/details/gt2bbsypxcl.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2mupumdof.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yj202588.top/Article/details/gt2nwhpcnmj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xuanzx.com/Article/details/gt2mffeauri.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yuanzhike.top/Article/details/gt2lpawlmch.html

[P08] 处理浮点精度问题
来源：http://dali.dashuyun.cn/Article/details/gt2iwrmldml.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.c1oappe.top/Article/details/gt2rnjrmbxv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhoulong.xyz/Article/details/gt2dcbftznb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.nanxinkj.top/Article/details/gt2btdxliwn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.316326.xyz/Article/details/gt2ymrdqtfn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aumrmzfo.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2afvishkq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yongpay.top/Article/details/gt2ynqkpicu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jyoumei.cn/Article/details/gt2ptejnthf.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2nswbirbf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hnqzz.top/Article/details/gt2zkwopdfp.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2shbfefty.html

[Q01] 创建表
来源：http://dali.xuetiantiany.cn/Article/details/gt2mubkuvtf.html

CREATE TABLE users (
来源：http://dali.wangshuangyany.cn/Article/details/gt2twkjbpjz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.haohaochexian.top/Article/details/gt2umrqokxv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.nwbrower.top/Article/details/gt2lwxisfhy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yuanzhike.top/Article/details/gt2vinngqgs.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.fzhhl.top/Article/details/gt2glowouhp.html

);
来源：http://dali.feifeiyinyue.top/Article/details/gt2pcbkixwu.html

[Q02] 创建带外键的表
来源：http://dali.bjfxy.top/Article/details/gt2ydivhhfq.html

CREATE TABLE orders (
来源：http://dali.yonumen.top/Article/details/gt2zbbopiaw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gzhubu.top/Article/details/gt2ovlecjzb.html

user_id INT NOT NULL,
来源：http://dali.zhoulong.xyz/Article/details/gt2oeeycfie.html

amount DECIMAL(10, 2),
来源：http://dali.yanxiufei.cn/Article/details/gt2hvjaubif.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.nwbrower.top/Article/details/gt2tcmaglwx.html

);
来源：http://dali.ehwqpu.com/Article/details/gt2rosepqly.html

[Q03] 增加列
来源：http://dali.haohaochexian.top/Article/details/gt2hszhxepu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.9152youxi.cn/Article/details/gt2lvasirxm.html

[Q04] 修改列类型
来源：http://dali.snrcjt.cn/Article/details/gt2iuqdmvhs.html


<!-- 参考信息 -->