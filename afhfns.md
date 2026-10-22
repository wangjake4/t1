代发 wailian999

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinqigufen.top/Article/details/gtskspuels.html

[M05] 设置退出码
来源：http://dali.zhiwuduotai.top/Article/details/gtcmaydikg.html

Py:   sys.exit(1)
来源：http://dali.tian-w.cn/Article/details/gtgrrqfdak.html

PHP:  exit(1);
来源：http://dali.tian-w.cn/Article/details/gtositifjk.html

JS:   process.exit(1)
来源：http://dali.aizwys.cn/Article/details/gtbvmwxhaz.html

TS:   process.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gtaumwkksp.html

Java: System.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfthontrh.html

Go:   os.Exit(1)
来源：http://dali.iojbl.cn/Article/details/gtcnptjerw.html

Ruby: exit 1
来源：http://dali.ybcxt.top/Article/details/gteltejyix.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yuxming.cn/Article/details/gtetgprvik.html

[M06] 向标准错误输出
来源：http://dali.ybcxt.top/Article/details/gtjonhjght.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinqigufen.top/Article/details/gtgkeiggat.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhengqikj.top/Article/details/gtzniuqies.html

JS:   console.error("err")
来源：http://dali.ivvv.top/Article/details/gtexheyoxm.html

TS:   console.error("err")
来源：http://dali.guannengcc.top/Article/details/gtrznjsoor.html

Java: System.err.println("err")
来源：http://dali.tian-w.cn/Article/details/gtovesxpyt.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.aizwys.cn/Article/details/gtljqanxje.html

Ruby: warn "err"
来源：http://dali.hywenlv.cn/Article/details/gtaqoahubf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hnqzz.top/Article/details/gtpaeepoes.html

[M07] 判断是否为主入口
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpwamkfas.html

Py:   if __name__ == "__main__":
来源：http://dali.ydzc1.top/Article/details/gtuyudexmq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ybcxt.top/Article/details/gtrsszdjxl.html

JS:   require.main === module
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkoofhdae.html

TS:   require.main === module
来源：http://dali.wangdashe.top/Article/details/gtczyobqzq.html

Java: public static void main(String[] args)
来源：http://dali.gogol.net.cn/Article/details/gtivtvismt.html

Go:   func main()
来源：http://dali.hfpthk.cn/Article/details/gtzvqqzgyy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jianghu66.top/Article/details/gtusjxxnqo.html

C#:   static void Main(string[] args)
来源：http://dali.xylfe.cn/Article/details/gtvmjormek.html

[M08] 获取系统与运行时信息
来源：http://dali.sxryk.cn/Article/details/gtachsulhx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xuetiantiany.cn/Article/details/gtomaouamr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.nwbrower.top/Article/details/gtmdzqusfk.html

JS:   process.platform;  process.version
来源：http://dali.daxiang520.top/Article/details/gtsvgqkvdh.html

TS:   process.platform;  process.version
来源：http://dali.tianlin.xyz/Article/details/gtxuwwsqbi.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhixingplan.top/Article/details/gtcgmvxmft.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhongyouzk.top/Article/details/gtzajwdjqj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jyoumei.cn/Article/details/gtzhcmsoyv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gogol.net.cn/Article/details/gtswmxynpd.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gttyldlmfn.html

N. 数据结构与算法
来源：http://dali.tian-w.cn/Article/details/gtvyrofkhx.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtbdqitdcc.html

[N01] 二分查找（有序数组）
来源：http://dali.yuxming.cn/Article/details/gtocshtsfr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtysamdptt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cdnleiting.top/Article/details/gtuhwzasmr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuxming.cn/Article/details/gtzjnmbvvp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxinkj.top/Article/details/gtvqizowff.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtnvwwmffq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gttzbuwqby.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.chenlongwang.top/Article/details/gtpahexgyz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yj20258888.top/Article/details/gtvkxcstgl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sufxvd.cn/Article/details/gtvqaxptlo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cheryme.top/Article/details/gtdnfdlrxr.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.chenzaomai.com/Article/details/gtckqvaygr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.birdmap.top/Article/details/gtlfdunbrg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shangyingyoupin.top/Article/details/gtgkbbfkuf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xylfe.cn/Article/details/gtliamrjmu.html

Go:   slices.Sort(arr)
来源：http://dali.guannengcc.top/Article/details/gtrmrwchio.html

Ruby: arr.sort
来源：http://dali.vqdsnc.cn/Article/details/gtvxbejbky.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhongyouzk.top/Article/details/gtcjnhofpo.html

[N03] 快速排序（分治示例）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjzwmslfh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cucudq.cn/Article/details/gtfljwnlvk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxcotflum.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cdnleiting.top/Article/details/gtxscsqzwv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhoulong.xyz/Article/details/gtnvnvdspo.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hongshengwenyu.top/Article/details/gtstzapiii.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cashguo.top/Article/details/gtqtjwsjhx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yonumen.top/Article/details/gtuhnxlznv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.daxiang520.top/Article/details/gtueuwtvvk.html

[N04] 斐波那契数列
来源：http://dali.xziqi.cn/Article/details/gtqfbjlnce.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.316326.xyz/Article/details/gtucchpbfz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.quarkkingdee.top/Article/details/gthneaztac.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yvedp.cn/Article/details/gtttwvllik.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhoulong.xyz/Article/details/gtxfsdjfqa.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xziqi.cn/Article/details/gtrfzjnigb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.daxiang520.top/Article/details/gtibzcumue.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gaohongyu789.top/Article/details/gteftmzeju.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.redwolf501.top/Article/details/gtdbgwivme.html

[N05] 最大公约数
来源：http://dali.meibo888.top/Article/details/gtsokcwyfw.html

Py:   math.gcd(a, b)
来源：http://dali.shzxlz.cn/Article/details/gtvhqberhn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.pengpengdd.cyou/Article/details/gtmsuuvrdc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ehwqpu.com/Article/details/gtnsadwuhv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shuidangran.top/Article/details/gthuoanjax.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shzxlz.cn/Article/details/gttxskbwxu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.vqdsnc.cn/Article/details/gtlxwubnvo.html

Ruby: a.gcd(b)
来源：http://dali.jqgfzy.top/Article/details/gtrsvffwsi.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhongyouzk.top/Article/details/gtvzictszn.html

[N06] 判断回文字符串
来源：http://dali.gaohongyu789.top/Article/details/gtnaetptux.html

Py:   s == s[::-1]
来源：http://dali.jlsjyb.cn/Article/details/gthftabzgj.html

PHP:  $s === strrev($s);
来源：http://dali.hysaishi.cn/Article/details/gtqnqklnwy.html

JS:   s === [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gtpvudbdlu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gtqmjufehq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gaohongyu789.top/Article/details/gtivlweqlp.html

Go:   // 双指针从两端比较
来源：http://dali.zhongyouzk.top/Article/details/gtlvusinya.html

Ruby: s == s.reverse
来源：http://dali.hammf.cn/Article/details/gtdwusteks.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.9152youxi.cn/Article/details/gtjcnngseo.html

[N07] 两数之和（返回下标）
来源：http://dali.yanxiufei.cn/Article/details/gtwrykamhd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.iojbl.cn/Article/details/gtkenjlqln.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sxryk.cn/Article/details/gtdaydwcob.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hammf.cn/Article/details/gtrjluseix.html

TS:   // 手写 Map<string, number>
来源：http://dali.xziqi.cn/Article/details/gtfybuglws.html

Java: // 手写 HashMap
来源：http://dali.guannengcc.top/Article/details/gtlxsojdmo.html

Go:   // 手写 map[int]int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyypuosvj.html

Ruby: // 手写 Hash
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgnpdlrfn.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hywenlv.cn/Article/details/gtmlpnkdul.html

[N08] 生成全排列
来源：http://dali.nanxuanxn.top/Article/details/gtabioqqhy.html

Py:   itertools.permutations(arr)
来源：http://dali.gzhubu.top/Article/details/gtlemebetw.html

PHP:  // 手写递归交换
来源：http://dali.yonumen.top/Article/details/gthmryzidp.html

JS:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdafyoles.html

TS:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gteottczfk.html

Java: // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gtfkufplzp.html

Go:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gtisugmglt.html

Ruby: arr.permutation.to_a
来源：http://dali.hywenlv.cn/Article/details/gtongytxwm.html

C#:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gttwqfppfm.html

[N09] 栈与队列
来源：http://dali.0kj1m.cn/Article/details/gtryawqvnx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.daxiang520.top/Article/details/gtnkizikpl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.havefunace.top/Article/details/gtemqzxeye.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jiagoushi.top/Article/details/gtynfgzzoi.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zycfv.cn/Article/details/gtdmfbsaab.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cqqwz.cn/Article/details/gtxeseedjh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.birdmap.top/Article/details/gtowrppgwy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.tianlin.xyz/Article/details/gtzwgtvbrp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xuetiantiany.cn/Article/details/gtcceammmr.html

[N10] 链表节点定义
来源：http://dali.ivvv.top/Article/details/gtnbpmrcca.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhixingplan.top/Article/details/gtbdfdzdve.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sysykeji.top/Article/details/gtmqtzlduz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhengqikj.top/Article/details/gtplmfikqi.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.meibo888.top/Article/details/gtzzsztamq.html

Java: class Node { int v; Node next; }
来源：http://dali.c1oappe.top/Article/details/gtfpmtviyu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cucudq.cn/Article/details/gtmghcdpia.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbbtcauhp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.daxiang520.top/Article/details/gtodyahzns.html

[N11] 二叉树中序遍历
来源：http://dali.smart0.xyz/Article/details/gtxneovect.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ehwqpu.com/Article/details/gtpmzopref.html

PHP:  // 手写递归函数
来源：http://dali.ydzc1.top/Article/details/gtzmrgzbsh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aibaodan.cn/Article/details/gtmxuqxenu.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.meibo888.top/Article/details/gteomytfmq.html

Java: // 手写递归
来源：http://dali.zycfv.cn/Article/details/gttdujmnzd.html

Go:   // 手写递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsiatolaw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.svipenyu.cn/Article/details/gtoelfmzma.html

C#:   // 手写递归
来源：http://dali.fengsongda.top/Article/details/gtxyytooqp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gaohongyu789.top/Article/details/gtnpnfkhso.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hnxiangtu.top/Article/details/gttzeokqer.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.chenlongwang.top/Article/details/gtrnwuvpgm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxinkj.top/Article/details/gtxafjwvgm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gotoacloud.top/Article/details/gtpjizvmpo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jyoumei.cn/Article/details/gtflduzbol.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ppjwa.cn/Article/details/gtqlioihdt.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwicbmixv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yueranfly.top/Article/details/gtbspcurmj.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtbsxyjgpy.html

O. 并发与异步
来源：http://dali.birdmap.top/Article/details/gtbfenhphr.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtpkeyenlv.html

[O01] 启动一个线程
来源：http://dali.jinqigfzy.top/Article/details/gtmtcrbkpb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.aibaodan.cn/Article/details/gtkfxaghsk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yanxiufei.cn/Article/details/gtzghjiodt.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.dianchejie.cn/Article/details/gtuezdeuyq.html

TS:   // 同 JS
来源：http://dali.mhx1999.top/Article/details/gtadmsebtr.html

Java: new Thread(() -> f()).start()
来源：http://dali.jqgufenzy.top/Article/details/gtpfzksrau.html

Go:   go f()
来源：http://dali.chenlongwang.top/Article/details/gtcebdmckk.html

Ruby: Thread.new { f }
来源：http://dali.dashuyun.cn/Article/details/gtqwwylgvy.html

C#:   Task.Run(() => F());
来源：http://dali.quarkkingdee.top/Article/details/gtspzubnxx.html

[O02] 使用线程池
来源：http://dali.xziqi.cn/Article/details/gtdsbpiten.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yj20258.top/Article/details/gtxoqihkoh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjpraxwto.html

JS:   // worker_threads 线程池
来源：http://dali.zdqjudy.top/Article/details/gtsvhbvpdt.html

TS:   // worker_threads 线程池
来源：http://dali.sweek.top/Article/details/gtbhtwrmdk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhengqikj.top/Article/details/gtjcfjbywn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ppjwa.cn/Article/details/gtdlipymdr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.iojbl.cn/Article/details/gtzkwpijxa.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.guannengcc.top/Article/details/gtrrjxarxk.html

[O03] 加锁保护共享数据
来源：http://dali.redwolf501.top/Article/details/gtmsgbqzvx.html

Py:   with lock: shared += 1
来源：http://dali.nwbrower.top/Article/details/gtnroulqif.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.pycfn.com/Article/details/gtcjnfkdnk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.sweek.top/Article/details/gtmxfyquyk.html

TS:   // 同 JS
来源：http://dali.jqgufenzy.top/Article/details/gtgilxrjqe.html

Java: synchronized (this) { shared++; }
来源：http://dali.wangdashe.top/Article/details/gtyclwmkxm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ppjwa.cn/Article/details/gtdzzcpgsd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jqgufenzy.top/Article/details/gtgthjzjxn.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtedsjpeom.html

[O04] 定义异步函数并等待
来源：http://dali.sysykeji.top/Article/details/gtjsacramw.html

Py:   async def f():⏎    await g()
来源：http://dali.yj20258888.top/Article/details/gtrqcfpoih.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.bjfxy.top/Article/details/gtnkxnvsqg.html

JS:   async function f() { await g(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtpunimnwy.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.fzhhl.top/Article/details/gtcjhjahek.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.chenlongwang.top/Article/details/gthguhuqsv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ppjwa.cn/Article/details/gtkarujhal.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ydzc1.top/Article/details/gtcuorimqv.html

C#:   async Task F() { await G(); }
来源：http://dali.jinqigufen.top/Article/details/gtjhugjkqb.html

[O05] 并发执行并等待全部完成
来源：http://dali.chenlongwang.top/Article/details/gtcwmfkcqs.html

Py:   asyncio.gather(*tasks)
来源：http://dali.iojbl.cn/Article/details/gtasdodgdb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhiwuduotai.top/Article/details/gtjtvpmlyv.html

JS:   await Promise.all(tasks)
来源：http://dali.0kj1m.cn/Article/details/gtzavczkdw.html

TS:   await Promise.all(tasks)
来源：http://dali.jinqigfzy.top/Article/details/gtuvnlrjiw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xinyue.icu/Article/details/gtitechqut.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yonumen.top/Article/details/gtkzvtkvph.html

Ruby: threads.map(&:join)
来源：http://dali.nanxinkj.top/Article/details/gthtjszopw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cheryme.top/Article/details/gtsgyhnzor.html

[O06] 使用进程池
来源：http://dali.shanyushiyangtech.top/Article/details/gtrropxusn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yanxiufei.cn/Article/details/gtxlszebkk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhoulong.xyz/Article/details/gtknhafltg.html

JS:   // child_process / cluster 模块
来源：http://dali.snrcjt.cn/Article/details/gtvsvnotoy.html

TS:   // child_process / cluster 模块
来源：http://dali.c1oappe.top/Article/details/gtokjtsgyh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hongshengwenyu.top/Article/details/gtzbcctdgm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.dianchejie.cn/Article/details/gtwpmdwcvk.html

Ruby: // fork 块
来源：http://dali.feifeiyinyue.top/Article/details/gtukaouxbh.html

C#:   Parallel.For
来源：http://dali.cashguo.top/Article/details/gtabphxcpm.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtdndqguio.html

P. 常用工具函数
来源：http://dali.pengpengdd.cyou/Article/details/gtpywstspq.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtrsofxpdf.html

[P01] 生成 UUID
来源：http://dali.zhiwuduotai.top/Article/details/gtsjeglbww.html

Py:   str(uuid.uuid4())
来源：http://dali.birdmap.top/Article/details/gtdukwfdom.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.dashuyun.cn/Article/details/gtdwpsozsy.html

JS:   crypto.randomUUID()
来源：http://dali.yvedp.cn/Article/details/gtobpazyrr.html

TS:   crypto.randomUUID()
来源：http://dali.zhongyouzk.top/Article/details/gtjyodtbfi.html

Java: UUID.randomUUID().toString()
来源：http://dali.pengpengdd.cyou/Article/details/gtsrtkcfvs.html

Go:   // 用 github.com/google/uuid
来源：http://dali.andypj.xyz/Article/details/gtxmcvlffz.html

Ruby: SecureRandom.uuid
来源：http://dali.chenjidiqi.icu/Article/details/gtctzsgydu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tianlin.xyz/Article/details/gtmjmaesoh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hnqzz.top/Article/details/gtcpkwjqdj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhengqikj.top/Article/details/gtwwaskkbh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhengqikj.top/Article/details/gtzshvysub.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.pengpengdd.cyou/Article/details/gtlewdwocg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ivvv.top/Article/details/gtxaabyrim.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.haohaochexian.top/Article/details/gtmqgtunvn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.quarkkingdee.top/Article/details/gtqjiunanr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yanxiufei.cn/Article/details/gtilrfrrln.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.guannengcc.top/Article/details/gtweqwxeux.html

[P03] 生成短随机字符串
来源：http://dali.zycfv.cn/Article/details/gtqswdxorw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cashguo.top/Article/details/gtintwdbqk.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.aizwys.cn/Article/details/gtdjtuwozr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj202588.top/Article/details/gtyeermtxt.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yonumen.top/Article/details/gtbvflypaf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.guannengcc.top/Article/details/gtennziftq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.meibo888.top/Article/details/gtwbbdsudl.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cheryme.top/Article/details/gtbdiqahqv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xziqi.cn/Article/details/gtdwakykfg.html

[P04] 求长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjbuslcwm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.pycfn.com/Article/details/gttytfgwlt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gtydteualf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.feifeiyinyue.top/Article/details/gtxjbmatav.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gotoacloud.top/Article/details/gtpcxkzjhx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.tanke756.top/Article/details/gtyppdqixn.html

Go:   len(arr);  len(m)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzqtssjfy.html

Ruby: x.length;  x.size
来源：http://dali.feifeiyinyue.top/Article/details/gtvefakrjw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.0kj1m.cn/Article/details/gttgldvkth.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jqgufenzy.top/Article/details/gthrbnhkck.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.fzhhl.top/Article/details/gtnmnkawom.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.daria6918.cn/Article/details/gtjcaarhty.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.kuanghao11.cn/Article/details/gtilrgukgg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.havefunace.top/Article/details/gtsopljdnn.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.feifeiyinyue.top/Article/details/gtdzaijipv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.tian-w.cn/Article/details/gtzwrgrvwc.html

Ruby: a == b
来源：http://dali.ivvv.top/Article/details/gtoeyxrhla.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.smart0.xyz/Article/details/gterkxkurz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gzhubu.top/Article/details/gtzdxbupey.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.feifeiyinyue.top/Article/details/gtnwahtlji.html

PHP:  if (empty($x)) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqcmclrnb.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.dianchejie.cn/Article/details/gtahkigbzg.html

TS:   if (x == null) {}
来源：http://dali.316326.xyz/Article/details/gtluinbstp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.meibo888.top/Article/details/gttmeytlek.html

Go:   if x == nil {}
来源：http://dali.yongpay.top/Article/details/gtseumylmw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.svipenyu.cn/Article/details/gtajnoqstb.html

C#:   if (x is null) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjubylyep.html

[P07] 防抖与节流
来源：http://dali.guannengcc.top/Article/details/gtwarvgquo.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.birdmap.top/Article/details/gtphsqflwf.html

PHP:  // 手写时间戳比较
来源：http://dali.yvedp.cn/Article/details/gtzzkrqcwq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.quarkkingdee.top/Article/details/gtkrhjbnzs.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yonumen.top/Article/details/gtzsexfcce.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtxbgixdpn.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ybcxt.top/Article/details/gtrwqufyoz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hfpthk.cn/Article/details/gtsifrvekd.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gotoacloud.top/Article/details/gtghkjuhor.html

[P08] 处理浮点精度问题
来源：http://dali.jinqigufen.top/Article/details/gtxkkcitln.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.haohaochexian.top/Article/details/gtlosfwwiv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfawnzzud.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.nanxuanxn.top/Article/details/gtoyruqnxr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yj202588.top/Article/details/gtvllimukg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xylfe.cn/Article/details/gtzxmonbtk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.daxiang520.top/Article/details/gtacfgozds.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shzxlz.cn/Article/details/gtwtekfhqs.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yuanzhike.top/Article/details/gterxforuo.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtgptyghed.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.aibaodan.cn/Article/details/gtjxfybzku.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtnswfwtdx.html

[Q01] 创建表
来源：http://dali.hammf.cn/Article/details/gtoiycqdhs.html

CREATE TABLE users (
来源：http://dali.jinqigufen.top/Article/details/gtsysrljuv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xuanzx.com/Article/details/gthifoicbh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.aizwys.cn/Article/details/gtrjdgdxlt.html

email VARCHAR(100) UNIQUE,
来源：http://dali.aibaodan.cn/Article/details/gtouqwoqwc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.aibaodan.cn/Article/details/gtotsvbrjs.html

);
来源：http://dali.bjfxy.top/Article/details/gtbbvoflqz.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gtrrwphgoa.html

CREATE TABLE orders (
来源：http://dali.9152youxi.cn/Article/details/gtbyyvqrfp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.vqdsnc.cn/Article/details/gtgclmuxdd.html

user_id INT NOT NULL,
来源：http://dali.ydzc1.top/Article/details/gtahdxtmyj.html

amount DECIMAL(10, 2),
来源：http://dali.cucudq.cn/Article/details/gtyvhqesyj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shangyingyoupin.top/Article/details/gtbpugzpyz.html

);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjvbwxfad.html

[Q03] 增加列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtggqtrjqy.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yuanzhike.top/Article/details/gtzeizezwk.html

[Q04] 修改列类型
来源：http://dali.shuidangran.top/Article/details/gtmenwipxi.html


<!-- 参考信息 -->