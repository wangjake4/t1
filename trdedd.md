代发 wailian999

JS:   process.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gtpxcjvhuk.html

TS:   process.exit(1)
来源：http://dali.wangdashe.top/Article/details/gtzcxgqvnu.html

Java: System.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxqxxnsyl.html

Go:   os.Exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gtchuglwir.html

Ruby: exit 1
来源：http://dali.tanke756.top/Article/details/gtmyightcd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xylfe.cn/Article/details/gtejvmahcq.html

[M06] 向标准错误输出
来源：http://dali.gaohongyu789.top/Article/details/gtabjmqqhj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.wangshuangyany.cn/Article/details/gtgxalekyj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.aibaodan.cn/Article/details/gtcpuxwmnz.html

JS:   console.error("err")
来源：http://dali.xuetiantiany.cn/Article/details/gtgpasziie.html

TS:   console.error("err")
来源：http://dali.andypj.xyz/Article/details/gtsmoxzddu.html

Java: System.err.println("err")
来源：http://dali.yuxming.cn/Article/details/gtiobemspo.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sweek.top/Article/details/gtkgeawalj.html

Ruby: warn "err"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjhwaprui.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.dianchejie.cn/Article/details/gtrdtsbqwl.html

[M07] 判断是否为主入口
来源：http://dali.xylfe.cn/Article/details/gtcgfmalxz.html

Py:   if __name__ == "__main__":
来源：http://dali.ydzc1.top/Article/details/gtdpkjyosk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.haohaochexian.top/Article/details/gtbvyqqrgx.html

JS:   require.main === module
来源：http://dali.tianlin.xyz/Article/details/gtrecvahdc.html

TS:   require.main === module
来源：http://dali.ywan-chungtsiang.top/Article/details/gtowvwmfpm.html

Java: public static void main(String[] args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwvdvsfgn.html

Go:   func main()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwdmmrhrf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.aibaodan.cn/Article/details/gtsiamvhqu.html

C#:   static void Main(string[] args)
来源：http://dali.cashguo.top/Article/details/gtlzmfnbbm.html

[M08] 获取系统与运行时信息
来源：http://dali.andypj.xyz/Article/details/gtsedzzoqb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.wangshuangyany.cn/Article/details/gtqxpvankm.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zdqjudy.top/Article/details/gtjnliijwp.html

JS:   process.platform;  process.version
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgjecvcoi.html

TS:   process.platform;  process.version
来源：http://dali.tianlin.xyz/Article/details/gtcbzdljgk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hongshengwenyu.top/Article/details/gttspuoxxo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj20258.top/Article/details/gtmkpodrkh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinqigfzy.top/Article/details/gtlxdnfhay.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhengqikj.top/Article/details/gterfkggtt.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtwxjtcwcc.html

N. 数据结构与算法
来源：http://dali.jinqigfzy.top/Article/details/gtkkjcinxp.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtclvcsirg.html

[N01] 二分查找（有序数组）
来源：http://dali.tanke756.top/Article/details/gthjmirskk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtgcriqxzy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cucudq.cn/Article/details/gtjymvajbc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gttfbptife.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.mhx1999.top/Article/details/gtxnupunze.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ivvv.top/Article/details/gthdxsoksr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gtgnojkzuv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.guowangkeji.top/Article/details/gtsablqhdd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtlxtyzfxt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinghuilouyu.cn/Article/details/gtvrwpyvoq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hywenlv.cn/Article/details/gtfzftdpbo.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqrspewbn.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hammf.cn/Article/details/gtewsefnmc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigufen.top/Article/details/gtlxrukdsc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sweek.top/Article/details/gtfbrobxne.html

Go:   slices.Sort(arr)
来源：http://dali.pycfn.com/Article/details/gtmerauoxx.html

Ruby: arr.sort
来源：http://dali.pengpengdd.cyou/Article/details/gtgquhxkvh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.feifeiyinyue.top/Article/details/gtsrusujqd.html

[N03] 快速排序（分治示例）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqcynqsyu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.pengpengdd.cyou/Article/details/gtiopaqocv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.haohaochexian.top/Article/details/gttlkcghsk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.meibo888.top/Article/details/gtnbmqmyjk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenjidiqi.icu/Article/details/gtfwrpjxcf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.nanxinkj.top/Article/details/gtiahguzko.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yueranfly.top/Article/details/gtyavbytzr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjttxefsh.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xziqi.cn/Article/details/gtgzomwxxr.html

[N04] 斐波那契数列
来源：http://dali.jinghuilouyu.cn/Article/details/gtxhcmgxux.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtrzdlgwnf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gtozczwbwb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yonumen.top/Article/details/gtehlowslc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sufxvd.cn/Article/details/gtkwwkqafs.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.haohaochexian.top/Article/details/gtirbumenj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yj202588.top/Article/details/gtnrnvlmto.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.svipenyu.cn/Article/details/gtxeytqumk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.gotoacloud.top/Article/details/gtivauwjin.html

[N05] 最大公约数
来源：http://dali.smart0.xyz/Article/details/gtoadkvwda.html

Py:   math.gcd(a, b)
来源：http://dali.zhoulong.xyz/Article/details/gtpizbqrac.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shuidangran.top/Article/details/gtlywztpdg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ppjwa.cn/Article/details/gtsaoqgtfa.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmpzqxiid.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlopjwhmm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.gaohongyu789.top/Article/details/gtmteyvibj.html

Ruby: a.gcd(b)
来源：http://dali.kuanghao11.cn/Article/details/gtzbuhdhay.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cqqwz.cn/Article/details/gtbsrlvkki.html

[N06] 判断回文字符串
来源：http://dali.zhiwuduotai.top/Article/details/gttvblmrtm.html

Py:   s == s[::-1]
来源：http://dali.gotoacloud.top/Article/details/gtqljetkod.html

PHP:  $s === strrev($s);
来源：http://dali.vqdsnc.cn/Article/details/gttlghqkip.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gtyuhdaugs.html

TS:   s === [...s].reverse().join("")
来源：http://dali.iojbl.cn/Article/details/gtlhacoctm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.mhx1999.top/Article/details/gtimmtzrhh.html

Go:   // 双指针从两端比较
来源：http://dali.chenzaomai.com/Article/details/gtzoqolyys.html

Ruby: s == s.reverse
来源：http://dali.xuanzx.com/Article/details/gtgjtapdof.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ehwqpu.com/Article/details/gtxlunyynd.html

[N07] 两数之和（返回下标）
来源：http://dali.hywenlv.cn/Article/details/gttlilnfpb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.guowangkeji.top/Article/details/gtayutirij.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.wangdashe.top/Article/details/gtpmpiaalx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xziqi.cn/Article/details/gtoztplnev.html

TS:   // 手写 Map<string, number>
来源：http://dali.meibo888.top/Article/details/gtvqskylna.html

Java: // 手写 HashMap
来源：http://dali.cheryme.top/Article/details/gtbtnjtgci.html

Go:   // 手写 map[int]int
来源：http://dali.wangdashe.top/Article/details/gtspfyizpo.html

Ruby: // 手写 Hash
来源：http://dali.cqqwz.cn/Article/details/gtokxbxire.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.guannengcc.top/Article/details/gtcdrwcvsd.html

[N08] 生成全排列
来源：http://dali.hysaishi.cn/Article/details/gtbesujxcn.html

Py:   itertools.permutations(arr)
来源：http://dali.zhixingplan.top/Article/details/gtwrlftvuq.html

PHP:  // 手写递归交换
来源：http://dali.9152youxi.cn/Article/details/gtmohdkrfq.html

JS:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtmkyrmmpz.html

TS:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtejetwlbt.html

Java: // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gtnbtlvuhq.html

Go:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gtrlrnfcys.html

Ruby: arr.permutation.to_a
来源：http://dali.xinyue.icu/Article/details/gtpdmwatpt.html

C#:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gtgyrtbcbg.html

[N09] 栈与队列
来源：http://dali.fengsongda.top/Article/details/gtdtrbddlg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.chenlongwang.top/Article/details/gtvhrqddpp.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.tanke756.top/Article/details/gtyyqraubj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.snrcjt.cn/Article/details/gtakqhuayv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nanxinkj.top/Article/details/gtluhtawzc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yangfankeji.com/Article/details/gtkkniqfip.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yj202588.top/Article/details/gtmlalvjst.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zdqjudy.top/Article/details/gthvqhdgdy.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sweek.top/Article/details/gtzyopupmy.html

[N10] 链表节点定义
来源：http://dali.jyoumei.cn/Article/details/gtljktzsyb.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfwlujhkk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.dashuyun.cn/Article/details/gtgfbvuuxu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.mhx1999.top/Article/details/gtydcgwjmv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.birdmap.top/Article/details/gtdngpcrqb.html

Java: class Node { int v; Node next; }
来源：http://dali.haohaochexian.top/Article/details/gtcjjlqdxe.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlphoqyyf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.daria6918.cn/Article/details/gtuwectqhn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.meibo888.top/Article/details/gtlvtsytwv.html

[N11] 二叉树中序遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtzpnzoooo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhengqikj.top/Article/details/gtuhsacbvk.html

PHP:  // 手写递归函数
来源：http://dali.zycfv.cn/Article/details/gtkxkjvehs.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.haohaochexian.top/Article/details/gtbsvfsocd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhiwuduotai.top/Article/details/gtebgzxlyo.html

Java: // 手写递归
来源：http://dali.jinqigufen.top/Article/details/gthhqfqkrl.html

Go:   // 手写递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmtexkcmc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ybcxt.top/Article/details/gtueyfvidx.html

C#:   // 手写递归
来源：http://dali.xziqi.cn/Article/details/gtuarbktog.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhoulong.xyz/Article/details/gtrjyltaap.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xylfe.cn/Article/details/gtnhhhxooc.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhiwuduotai.top/Article/details/gtbzsjsgzu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ydzc1.top/Article/details/gtonzlyeqt.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ehwqpu.com/Article/details/gtwzthsnhb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigfzy.top/Article/details/gtxybvebsn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cucudq.cn/Article/details/gtpgxzsxug.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hfpthk.cn/Article/details/gtupwgynzk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ybcxt.top/Article/details/gtoctcktdm.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtpoezrgyr.html

O. 并发与异步
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyjwvmaef.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtgklnaxcn.html

[O01] 启动一个线程
来源：http://dali.hnxiangtu.top/Article/details/gtvihrjwze.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmbxodkig.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hnqzz.top/Article/details/gtqmkiufam.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.meibo888.top/Article/details/gteazdhbun.html

TS:   // 同 JS
来源：http://dali.shzxlz.cn/Article/details/gtigjihiim.html

Java: new Thread(() -> f()).start()
来源：http://dali.jyoumei.cn/Article/details/gtywmvpeek.html

Go:   go f()
来源：http://dali.yongpay.top/Article/details/gtynkaksgq.html

Ruby: Thread.new { f }
来源：http://dali.yj20258888.top/Article/details/gthlwsaeaz.html

C#:   Task.Run(() => F());
来源：http://dali.ppjwa.cn/Article/details/gtblxwxerq.html

[O02] 使用线程池
来源：http://dali.zhengqikj.top/Article/details/gtatrmkcot.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yvedp.cn/Article/details/gtwcokhfbl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yonumen.top/Article/details/gtfstgylyi.html

JS:   // worker_threads 线程池
来源：http://dali.yj20258.top/Article/details/gtnpllxhuy.html

TS:   // worker_threads 线程池
来源：http://dali.yuxming.cn/Article/details/gthbdnsnsx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.pengpengdd.cyou/Article/details/gtihujfxwa.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yj20258888.top/Article/details/gtoruoanwe.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.wangshuangyany.cn/Article/details/gtzuablgcq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jlsjyb.cn/Article/details/gtwnvrrwwp.html

[O03] 加锁保护共享数据
来源：http://dali.shzxlz.cn/Article/details/gtozwgffsk.html

Py:   with lock: shared += 1
来源：http://dali.gotoacloud.top/Article/details/gttfdiyvet.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cashguo.top/Article/details/gttvyefdjd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.guowangkeji.top/Article/details/gtpdoiipmq.html

TS:   // 同 JS
来源：http://dali.cdnleiting.top/Article/details/gtadsuyoic.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcgapucas.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shuidangran.top/Article/details/gtduiwitny.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shzxlz.cn/Article/details/gtvafltwvs.html

C#:   lock (gate) { shared++; }
来源：http://dali.shuidangran.top/Article/details/gthbhwhwsv.html

[O04] 定义异步函数并等待
来源：http://dali.cucudq.cn/Article/details/gtuderaonz.html

Py:   async def f():⏎    await g()
来源：http://dali.xziqi.cn/Article/details/gtmvqzkvle.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.iojbl.cn/Article/details/gtclfrbudq.html

JS:   async function f() { await g(); }
来源：http://dali.smart0.xyz/Article/details/gtmpmirijs.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jqgufenzy.top/Article/details/gttqewzwjk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xuetiantiany.cn/Article/details/gtbnxwsonb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shangyingyoupin.top/Article/details/gtqqrawknf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.iojbl.cn/Article/details/gtasaqiyeg.html

C#:   async Task F() { await G(); }
来源：http://dali.hnxiangtu.top/Article/details/gtsiphgrqs.html

[O05] 并发执行并等待全部完成
来源：http://dali.gogol.net.cn/Article/details/gtlqqsrnli.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlcoxadwy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ydzc1.top/Article/details/gtryvnaukk.html

JS:   await Promise.all(tasks)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgmucswyt.html

TS:   await Promise.all(tasks)
来源：http://dali.zhongyouzk.top/Article/details/gtapmlyttp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yueranfly.top/Article/details/gtjubywoyq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.0kj1m.cn/Article/details/gtrgbcjxpj.html

Ruby: threads.map(&:join)
来源：http://dali.vqdsnc.cn/Article/details/gtpxrnbnbi.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.haohaochexian.top/Article/details/gtujrqjflv.html

[O06] 使用进程池
来源：http://dali.wangdashe.top/Article/details/gtatgcoewo.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.pycfn.com/Article/details/gtdykachto.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.smart0.xyz/Article/details/gtweazhkuk.html

JS:   // child_process / cluster 模块
来源：http://dali.feifeiyinyue.top/Article/details/gthbxpduly.html

TS:   // child_process / cluster 模块
来源：http://dali.shuidangran.top/Article/details/gttvclvpjv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gogol.net.cn/Article/details/gtfwnhoqbq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shangyingyoupin.top/Article/details/gtjejhvqgt.html

Ruby: // fork 块
来源：http://dali.pycfn.com/Article/details/gtfizifwec.html

C#:   Parallel.For
来源：http://dali.svipenyu.cn/Article/details/gtviuqizxp.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtkxhttinr.html

P. 常用工具函数
来源：http://dali.nanxuanxn.top/Article/details/gtxkusxvkl.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtdyjwgpkh.html

[P01] 生成 UUID
来源：http://dali.chenzaomai.com/Article/details/gtgrbdaqka.html

Py:   str(uuid.uuid4())
来源：http://dali.gogol.net.cn/Article/details/gtqvctufnv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlugwiull.html

JS:   crypto.randomUUID()
来源：http://dali.nanxinkj.top/Article/details/gtyfsvjogx.html

TS:   crypto.randomUUID()
来源：http://dali.ivvv.top/Article/details/gtlqsdhefb.html

Java: UUID.randomUUID().toString()
来源：http://dali.hongshengwenyu.top/Article/details/gtsayodjnr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ppjwa.cn/Article/details/gtqlkafohp.html

Ruby: SecureRandom.uuid
来源：http://dali.jlsjyb.cn/Article/details/gtkldtdisl.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.sweek.top/Article/details/gtssvawxce.html

[P02] MD5 / SHA256 摘要
来源：http://dali.c1oappe.top/Article/details/gtxwwfgnzg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.svipenyu.cn/Article/details/gtmirxofiz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.snrcjt.cn/Article/details/gtuzldbswh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.fzhhl.top/Article/details/gtpinlwdff.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhiwuduotai.top/Article/details/gtciaufide.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yueranfly.top/Article/details/gtdqexuudh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jqgfzy.top/Article/details/gtmolfouys.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shuidangran.top/Article/details/gtkvhggahh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yongpay.top/Article/details/gtbbakftnn.html

[P03] 生成短随机字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtqhmbhkru.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yangfankeji.com/Article/details/gtlwlnipia.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shuidangran.top/Article/details/gtclpincjd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zycfv.cn/Article/details/gtzyprezuw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hysaishi.cn/Article/details/gtqqtevane.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.bjfxy.top/Article/details/gtcyfkmnof.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xylfe.cn/Article/details/gtnhihmect.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nanxuanxn.top/Article/details/gtmlnyachl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yonumen.top/Article/details/gtdipkyian.html

[P04] 求长度
来源：http://dali.feifeiyinyue.top/Article/details/gtcolncxzn.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sysykeji.top/Article/details/gtkqvxlxxy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gtpemyzqtr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hongshengwenyu.top/Article/details/gtgtbsjvva.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jyoumei.cn/Article/details/gtkusklzdp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.fengsongda.top/Article/details/gtafumcoej.html

Go:   len(arr);  len(m)
来源：http://dali.hfpthk.cn/Article/details/gtpgcoehcw.html

Ruby: x.length;  x.size
来源：http://dali.jinghuilouyu.cn/Article/details/gtaiekhmcf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gtviurnodo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.meibo888.top/Article/details/gtdfhujdkx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.chenlongwang.top/Article/details/gtwzidrwyn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hammf.cn/Article/details/gtarzspexp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.vqdsnc.cn/Article/details/gtxaoaukyk.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.pycfn.com/Article/details/gturdmvllw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jinghuilouyu.cn/Article/details/gtgnmqwvdo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ybcxt.top/Article/details/gtleapaniz.html

Ruby: a == b
来源：http://dali.jqgufenzy.top/Article/details/gtbluifmoh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhengqikj.top/Article/details/gtqlmltyuj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cdnleiting.top/Article/details/gtdgthgewl.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ppjwa.cn/Article/details/gtllvjqgnw.html

PHP:  if (empty($x)) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjpomitdf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cqqwz.cn/Article/details/gtiuujzxfm.html

TS:   if (x == null) {}
来源：http://dali.yj20258888.top/Article/details/gtxtqykyzo.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtqvmvgqnq.html

Go:   if x == nil {}
来源：http://dali.haohaochexian.top/Article/details/gtmiuzybrd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.svipenyu.cn/Article/details/gtbnlrwgnw.html

C#:   if (x is null) {}
来源：http://dali.hnqzz.top/Article/details/gtkotjupyn.html

[P07] 防抖与节流
来源：http://dali.316326.xyz/Article/details/gtbjtqxmfz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.9152youxi.cn/Article/details/gtdxstnnep.html

PHP:  // 手写时间戳比较
来源：http://dali.chenjidiqi.icu/Article/details/gtzoiwxbvl.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gzhubu.top/Article/details/gtktohixuu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aizwys.cn/Article/details/gtqjibpnbp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpiqvusuj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.nanxuanxn.top/Article/details/gtvfzroyki.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yj202588.top/Article/details/gthuezkhtl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.fzhhl.top/Article/details/gtgvlliili.html

[P08] 处理浮点精度问题
来源：http://dali.bjfxy.top/Article/details/gtplwctdgd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinqigfzy.top/Article/details/gtnmjxktiy.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhongyouzk.top/Article/details/gtovnztupk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jinqigufen.top/Article/details/gtsaqutnyk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xylfe.cn/Article/details/gtebzruowv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.0kj1m.cn/Article/details/gtmdclihjq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.andypj.xyz/Article/details/gtyrhuhxsw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gteqhthkjy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yangfankeji.com/Article/details/gtjcedmgis.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtwdzhpltf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.chenzaomai.com/Article/details/gtmbmnesre.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtmgjwscsn.html

[Q01] 创建表
来源：http://dali.aizwys.cn/Article/details/gtwzypmmnz.html

CREATE TABLE users (
来源：http://dali.bjfxy.top/Article/details/gtpnalncyb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hywenlv.cn/Article/details/gtsgfrpfep.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yonumen.top/Article/details/gtyzcimnno.html

email VARCHAR(100) UNIQUE,
来源：http://dali.fengsongda.top/Article/details/gtflmbpqqn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.fzhhl.top/Article/details/gtqclfpueo.html

);
来源：http://dali.fzhhl.top/Article/details/gtxtnzftar.html

[Q02] 创建带外键的表
来源：http://dali.kuanghao11.cn/Article/details/gttrcxglew.html

CREATE TABLE orders (
来源：http://dali.shuidangran.top/Article/details/gtxuofyeiq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.iojbl.cn/Article/details/gtcwnjbnjx.html

user_id INT NOT NULL,
来源：http://dali.pycfn.com/Article/details/gtzairoxjw.html

amount DECIMAL(10, 2),
来源：http://dali.guannengcc.top/Article/details/gtrpjjprkl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xuetiantiany.cn/Article/details/gthhqpihxn.html

);
来源：http://dali.wangshuangyany.cn/Article/details/gtslqrevcl.html

[Q03] 增加列
来源：http://dali.cqqwz.cn/Article/details/gtuzlgzkhr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.chenjidiqi.icu/Article/details/gtquxkljcj.html

[Q04] 修改列类型
来源：http://dali.ppjwa.cn/Article/details/gthicgpwik.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jiagoushi.top/Article/details/gtsytevdek.html

[Q05] 重命名列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqjdcapek.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.feifeiyinyue.top/Article/details/gtaytlyhpz.html

[Q06] 删除列
来源：http://dali.yj202588.top/Article/details/gtvdwmtnog.html


<!-- 参考信息 -->