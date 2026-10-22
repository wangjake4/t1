代发 wailian999

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xziqi.cn/Article/details/gt2xhuytyrh.html

JS:   console.error("err")
来源：http://dali.yj20258.top/Article/details/gt2qjttpfgk.html

TS:   console.error("err")
来源：http://dali.zhoulong.xyz/Article/details/gt2qitzqtty.html

Java: System.err.println("err")
来源：http://dali.bjfxy.top/Article/details/gt2dyaclqau.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yanxiufei.cn/Article/details/gt2dclbijte.html

Ruby: warn "err"
来源：http://dali.jinqigufen.top/Article/details/gt2gorgmzcp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.smart0.xyz/Article/details/gt2peyrsgkn.html

[M07] 判断是否为主入口
来源：http://dali.sysykeji.top/Article/details/gt2uijisqkz.html

Py:   if __name__ == "__main__":
来源：http://dali.zhongyouzk.top/Article/details/gt2wklzejzl.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xziqi.cn/Article/details/gt2jmpbejqa.html

JS:   require.main === module
来源：http://dali.feifeiyinyue.top/Article/details/gt2sxouyzog.html

TS:   require.main === module
来源：http://dali.jiagoushi.top/Article/details/gt2ujhsbrdu.html

Java: public static void main(String[] args)
来源：http://dali.aibaodan.cn/Article/details/gt2vsfjnldp.html

Go:   func main()
来源：http://dali.ydzc1.top/Article/details/gt2crihqgoz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shangyingyoupin.top/Article/details/gt2igsvdkek.html

C#:   static void Main(string[] args)
来源：http://dali.cashguo.top/Article/details/gt2mccqmqva.html

[M08] 获取系统与运行时信息
来源：http://dali.quarkkingdee.top/Article/details/gt2dlitkohp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.iojbl.cn/Article/details/gt2ynyvohxc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gotoacloud.top/Article/details/gt2xoykhvcv.html

JS:   process.platform;  process.version
来源：http://dali.yj20258.top/Article/details/gt2gpjkrmxs.html

TS:   process.platform;  process.version
来源：http://dali.hfpthk.cn/Article/details/gt2pgoelsbm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nanxuanxn.top/Article/details/gt2hshdmsjr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.aizwys.cn/Article/details/gt2gfyudvpn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ybcxt.top/Article/details/gt2srlalipd.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2dtzbeqtm.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2gduxtcut.html

N. 数据结构与算法
来源：http://dali.havefunace.top/Article/details/gt2fmiwecxv.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2fgdorvks.html

[N01] 二分查找（有序数组）
来源：http://dali.hnqzz.top/Article/details/gt2irvhzfrl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yj202588.top/Article/details/gt2voalamqj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jiagoushi.top/Article/details/gt2cmogelpr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zdqjudy.top/Article/details/gt2ngfudjmx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ttudsgov.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dhqygocn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sweek.top/Article/details/gt2yjvkhhpa.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.chenzaomai.com/Article/details/gt2hifnfaor.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ybcxt.top/Article/details/gt2espeeiij.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hywenlv.cn/Article/details/gt2uskbodzf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hfpthk.cn/Article/details/gt2eqmleefj.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gperqtiz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aizwys.cn/Article/details/gt2mkyicezr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gogol.net.cn/Article/details/gt2faajncjd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dauzqxmb.html

Go:   slices.Sort(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kvqbefle.html

Ruby: arr.sort
来源：http://dali.dianchejie.cn/Article/details/gt2qraisson.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.fzhhl.top/Article/details/gt2rxhxjxix.html

[N03] 快速排序（分治示例）
来源：http://dali.zycfv.cn/Article/details/gt2kglumske.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cashguo.top/Article/details/gt2ssclevci.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gogol.net.cn/Article/details/gt2pphbvorc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daxiang520.top/Article/details/gt2pzmnydqp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hnqzz.top/Article/details/gt2teqxkdwa.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shuidangran.top/Article/details/gt2wrtkkbtd.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.c1oappe.top/Article/details/gt2rtjfisgb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.feifeiyinyue.top/Article/details/gt2xapeweaw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.iojbl.cn/Article/details/gt2qdcytcdn.html

[N04] 斐波那契数列
来源：http://dali.ivvv.top/Article/details/gt2bhfyurry.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.snrcjt.cn/Article/details/gt2qkanjbbr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gzhubu.top/Article/details/gt2becomrzj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnxiangtu.top/Article/details/gt2zaxhuwes.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guannengcc.top/Article/details/gt2npbdzegb.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jqgufenzy.top/Article/details/gt2bbclblmy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.havefunace.top/Article/details/gt2swtvovzo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xinyue.icu/Article/details/gt2whbewiys.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yuanzhike.top/Article/details/gt2tkczgbpy.html

[N05] 最大公约数
来源：http://dali.xinyue.icu/Article/details/gt2xdkxcocm.html

Py:   math.gcd(a, b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ydclbwgh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.chenzaomai.com/Article/details/gt2dacencos.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daria6918.cn/Article/details/gt2yxaiezqh.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.vqdsnc.cn/Article/details/gt2rhvsfspb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.guowangkeji.top/Article/details/gt2ytrlalru.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.daria6918.cn/Article/details/gt2dxwjtifs.html

Ruby: a.gcd(b)
来源：http://dali.redwolf501.top/Article/details/gt2bvkbpnuc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.guannengcc.top/Article/details/gt2ecwjgejm.html

[N06] 判断回文字符串
来源：http://dali.svipenyu.cn/Article/details/gt2cavgfqum.html

Py:   s == s[::-1]
来源：http://dali.yj20258888.top/Article/details/gt2vooowlrs.html

PHP:  $s === strrev($s);
来源：http://dali.fengsongda.top/Article/details/gt2tvoqwixk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gt2kwuzuyoa.html

TS:   s === [...s].reverse().join("")
来源：http://dali.vqdsnc.cn/Article/details/gt2refjdlwl.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zdqjudy.top/Article/details/gt2mcmakxum.html

Go:   // 双指针从两端比较
来源：http://dali.vqdsnc.cn/Article/details/gt2bnqegmog.html

Ruby: s == s.reverse
来源：http://dali.chenzaomai.com/Article/details/gt2rbzvihnb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xziqi.cn/Article/details/gt2rvrnivng.html

[N07] 两数之和（返回下标）
来源：http://dali.cucudq.cn/Article/details/gt2vlkmtjoo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.tian-w.cn/Article/details/gt2nxfnpqyp.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gzhubu.top/Article/details/gt2npslwxox.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.dianchejie.cn/Article/details/gt2jvqmihox.html

TS:   // 手写 Map<string, number>
来源：http://dali.iojbl.cn/Article/details/gt2auskohcg.html

Java: // 手写 HashMap
来源：http://dali.daxiang520.top/Article/details/gt2hsvnvxua.html

Go:   // 手写 map[int]int
来源：http://dali.yj20258888.top/Article/details/gt2rgpizarn.html

Ruby: // 手写 Hash
来源：http://dali.ydzc1.top/Article/details/gt2fqlemrqm.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gaohongyu789.top/Article/details/gt2mtqkuicj.html

[N08] 生成全排列
来源：http://dali.bjfxy.top/Article/details/gt2yxyjdavo.html

Py:   itertools.permutations(arr)
来源：http://dali.cucudq.cn/Article/details/gt2nrrmvhbe.html

PHP:  // 手写递归交换
来源：http://dali.hammf.cn/Article/details/gt2uwudpqdx.html

JS:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gt2qhqzcnsz.html

TS:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gt2owqhguxd.html

Java: // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gt2gdoebsgm.html

Go:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gt2pyreptgg.html

Ruby: arr.permutation.to_a
来源：http://dali.hammf.cn/Article/details/gt2jrskuamx.html

C#:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gt2alhstqft.html

[N09] 栈与队列
来源：http://dali.redwolf501.top/Article/details/gt2ikipiikh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhoulong.xyz/Article/details/gt2vlynryyd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.kuanghao11.cn/Article/details/gt2cjjxnhai.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gt2bnrofuca.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xersjith.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.aibaodan.cn/Article/details/gt2fraxhquk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yuanzhike.top/Article/details/gt2afkhfcuj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xziqi.cn/Article/details/gt2abivgmlb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.vqdsnc.cn/Article/details/gt2ewahnpiq.html

[N10] 链表节点定义
来源：http://dali.gotoacloud.top/Article/details/gt2ivdhapux.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hnxiangtu.top/Article/details/gt2qeehhebo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2mudtxnyk.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2znekfkft.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yanxiufei.cn/Article/details/gt2hndvaywb.html

Java: class Node { int v; Node next; }
来源：http://dali.yvedp.cn/Article/details/gt2filbbqql.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.wangdashe.top/Article/details/gt2mykvtcok.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.haohaochexian.top/Article/details/gt2gpkthxoa.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xylfe.cn/Article/details/gt2iteioxfv.html

[N11] 二叉树中序遍历
来源：http://dali.nanxuanxn.top/Article/details/gt2aimdapxz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xziqi.cn/Article/details/gt2rlugoojx.html

PHP:  // 手写递归函数
来源：http://dali.smart0.xyz/Article/details/gt2nopasnhg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hfpthk.cn/Article/details/gt2xsdwiygz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aibaodan.cn/Article/details/gt2zlzqhxwb.html

Java: // 手写递归
来源：http://dali.tanke756.top/Article/details/gt2uvdusmrd.html

Go:   // 手写递归
来源：http://dali.gaohongyu789.top/Article/details/gt2yonbhthk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sysykeji.top/Article/details/gt2uyjrzeke.html

C#:   // 手写递归
来源：http://dali.sufxvd.cn/Article/details/gt2hxylknig.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hywenlv.cn/Article/details/gt2yqpefvnj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.aizwys.cn/Article/details/gt2wgrccobg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhiwuduotai.top/Article/details/gt2dknlunzf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgufenzy.top/Article/details/gt2abuzpokl.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yongpay.top/Article/details/gt2bgcveryd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigfzy.top/Article/details/gt2tleysltf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shangyingyoupin.top/Article/details/gt2szhqdqmb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ydzc1.top/Article/details/gt2cpilscbg.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cqqwz.cn/Article/details/gt2wqsvkukq.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2eavuntyj.html

O. 并发与异步
来源：http://dali.xziqi.cn/Article/details/gt2cuuheowt.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2qmyhhlek.html

[O01] 启动一个线程
来源：http://dali.yvedp.cn/Article/details/gt2rylcdhit.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cheryme.top/Article/details/gt2hauctuvq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ydzc1.top/Article/details/gt2omttvkwo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.sweek.top/Article/details/gt2qrppxvoc.html

TS:   // 同 JS
来源：http://dali.feifeiyinyue.top/Article/details/gt2ygunundh.html

Java: new Thread(() -> f()).start()
来源：http://dali.tianlin.xyz/Article/details/gt2rxhdyyxd.html

Go:   go f()
来源：http://dali.yj20258888.top/Article/details/gt2axjhoywc.html

Ruby: Thread.new { f }
来源：http://dali.pycfn.com/Article/details/gt2uyerowxf.html

C#:   Task.Run(() => F());
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vbqlnafy.html

[O02] 使用线程池
来源：http://dali.zdqjudy.top/Article/details/gt2dvppwtnu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.pycfn.com/Article/details/gt2rtaossay.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yj202588.top/Article/details/gt2ttbwbpuh.html

JS:   // worker_threads 线程池
来源：http://dali.zdqjudy.top/Article/details/gt2svuybzax.html

TS:   // worker_threads 线程池
来源：http://dali.jiagoushi.top/Article/details/gt2ydbmxyle.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yuxming.cn/Article/details/gt2qpeycxye.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.nanxinkj.top/Article/details/gt2yoztjlnn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.fzhhl.top/Article/details/gt2shfhzuwn.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.sysykeji.top/Article/details/gt2odnqkscm.html

[O03] 加锁保护共享数据
来源：http://dali.daxiang520.top/Article/details/gt2ubueyncg.html

Py:   with lock: shared += 1
来源：http://dali.yanxiufei.cn/Article/details/gt2siafjeiw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.0kj1m.cn/Article/details/gt2cxlhwbwo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.smart0.xyz/Article/details/gt2dwurgykf.html

TS:   // 同 JS
来源：http://dali.chenjidiqi.icu/Article/details/gt2mdyhnpsb.html

Java: synchronized (this) { shared++; }
来源：http://dali.tanke756.top/Article/details/gt2qcvtowwe.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gaohongyu789.top/Article/details/gt2kkaladka.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yvedp.cn/Article/details/gt2scjkgnlj.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinqigufen.top/Article/details/gt2lmxuuitx.html

[O04] 定义异步函数并等待
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cbttqsqz.html

Py:   async def f():⏎    await g()
来源：http://dali.hnqzz.top/Article/details/gt2oqjbcyip.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.chenlongwang.top/Article/details/gt2vlpzuzgk.html

JS:   async function f() { await g(); }
来源：http://dali.yvedp.cn/Article/details/gt2kshddhil.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhixingplan.top/Article/details/gt2muxtvgoi.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.tian-w.cn/Article/details/gt2zikrjoyt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ivvv.top/Article/details/gt2spqcycpf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.snrcjt.cn/Article/details/gt2iswtwngx.html

C#:   async Task F() { await G(); }
来源：http://dali.fengsongda.top/Article/details/gt2yrtpdcft.html

[O05] 并发执行并等待全部完成
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2baflahpt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hfpthk.cn/Article/details/gt2codnoksy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.daria6918.cn/Article/details/gt2wydmsbge.html

JS:   await Promise.all(tasks)
来源：http://dali.iojbl.cn/Article/details/gt2qcalbamj.html

TS:   await Promise.all(tasks)
来源：http://dali.pycfn.com/Article/details/gt2fgjxnxrg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.chenlongwang.top/Article/details/gt2zeehgzjf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cdnleiting.top/Article/details/gt2ysuaghph.html

Ruby: threads.map(&:join)
来源：http://dali.gotoacloud.top/Article/details/gt2xgbxghug.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ehwqpu.com/Article/details/gt2dniqeulw.html

[O06] 使用进程池
来源：http://dali.9152youxi.cn/Article/details/gt2hbinwdzo.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.pycfn.com/Article/details/gt2bqpkkbit.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cheryme.top/Article/details/gt2ppobqltk.html

JS:   // child_process / cluster 模块
来源：http://dali.zdqjudy.top/Article/details/gt2diupyunr.html

TS:   // child_process / cluster 模块
来源：http://dali.cashguo.top/Article/details/gt2ezvrvxzl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.aibaodan.cn/Article/details/gt2byzsurqf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hongshengwenyu.top/Article/details/gt2pregubrt.html

Ruby: // fork 块
来源：http://dali.chenlongwang.top/Article/details/gt2lgulwxdd.html

C#:   Parallel.For
来源：http://dali.jianghu66.top/Article/details/gt2zopzkqyh.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2gomkxxxo.html

P. 常用工具函数
来源：http://dali.jiagoushi.top/Article/details/gt2lmojzvag.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2ijsppbfv.html

[P01] 生成 UUID
来源：http://dali.birdmap.top/Article/details/gt2uudcgjyk.html

Py:   str(uuid.uuid4())
来源：http://dali.hnqzz.top/Article/details/gt2beohotpv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ivvv.top/Article/details/gt2jxinyzhn.html

JS:   crypto.randomUUID()
来源：http://dali.redwolf501.top/Article/details/gt2hcqypdeo.html

TS:   crypto.randomUUID()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hffyafiw.html

Java: UUID.randomUUID().toString()
来源：http://dali.tian-w.cn/Article/details/gt2ifarlint.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhixingplan.top/Article/details/gt2uhvvliwu.html

Ruby: SecureRandom.uuid
来源：http://dali.birdmap.top/Article/details/gt2zaurpyft.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xuetiantiany.cn/Article/details/gt2byakkaih.html

[P02] MD5 / SHA256 摘要
来源：http://dali.dianchejie.cn/Article/details/gt2ruceoyzk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jqgfzy.top/Article/details/gt2xnjtnven.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gaohongyu789.top/Article/details/gt2aabpqnmg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sweek.top/Article/details/gt2dyttaida.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhengqikj.top/Article/details/gt2jdzzgzgl.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sxryk.cn/Article/details/gt2tqdljcdh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.316326.xyz/Article/details/gt2qebcsbnw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pxvassej.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gogol.net.cn/Article/details/gt2gqbcfxos.html

[P03] 生成短随机字符串
来源：http://dali.sysykeji.top/Article/details/gt2zeggbinw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhiwuduotai.top/Article/details/gt2npcsmden.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.tanke756.top/Article/details/gt2girgjihv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.kuanghao11.cn/Article/details/gt2ttzsbgij.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuetiantiany.cn/Article/details/gt2toqnsdik.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2miolazpq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.aibaodan.cn/Article/details/gt2mngezutx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yongpay.top/Article/details/gt2drlqctru.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.cashguo.top/Article/details/gt2ccnyzuzw.html

[P04] 求长度
来源：http://dali.yangfankeji.com/Article/details/gt2jmehoosb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yj20258888.top/Article/details/gt2wfjndvae.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258.top/Article/details/gt2nbkpehqd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gaohongyu789.top/Article/details/gt2nvlrqsbz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxinkj.top/Article/details/gt2xpyaqroq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.aizwys.cn/Article/details/gt2fjcjiglu.html

Go:   len(arr);  len(m)
来源：http://dali.birdmap.top/Article/details/gt2wqkhazsc.html

Ruby: x.length;  x.size
来源：http://dali.jiagoushi.top/Article/details/gt2qhptxtzw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hnqzz.top/Article/details/gt2doyaxwwz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yongpay.top/Article/details/gt2epqqffka.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hysaishi.cn/Article/details/gt2zvyexghd.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gaohongyu789.top/Article/details/gt2kbexlgli.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cashguo.top/Article/details/gt2tgttvkry.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ivvv.top/Article/details/gt2sgtrvqnb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jianghu66.top/Article/details/gt2mpwgjsli.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sysykeji.top/Article/details/gt2jknndhey.html

Ruby: a == b
来源：http://dali.cdnleiting.top/Article/details/gt2ocfgbefv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.iojbl.cn/Article/details/gt2pzogmhun.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jyoumei.cn/Article/details/gt2tktwsagc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jqgfzy.top/Article/details/gt2pmlsvuev.html

PHP:  if (empty($x)) {}
来源：http://dali.gogol.net.cn/Article/details/gt2mzsgwmcg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.dashuyun.cn/Article/details/gt2ystytyvh.html

TS:   if (x == null) {}
来源：http://dali.tianlin.xyz/Article/details/gt2ocuwxscz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenzaomai.com/Article/details/gt2qzuineqr.html

Go:   if x == nil {}
来源：http://dali.yj202588.top/Article/details/gt2huablxad.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hnqzz.top/Article/details/gt2cwntefuz.html

C#:   if (x is null) {}
来源：http://dali.fzhhl.top/Article/details/gt2brhwkcvk.html

[P07] 防抖与节流
来源：http://dali.tian-w.cn/Article/details/gt2qsmvhjrr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jqgfzy.top/Article/details/gt2cyrsomcd.html

PHP:  // 手写时间戳比较
来源：http://dali.aizwys.cn/Article/details/gt2fegmdkvl.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zdqjudy.top/Article/details/gt2ssxyxxsl.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dianchejie.cn/Article/details/gt2vwznfufe.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.haohaochexian.top/Article/details/gt2vegrnwkz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sufxvd.cn/Article/details/gt2jsfpuuur.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yueranfly.top/Article/details/gt2mtfqocap.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhixingplan.top/Article/details/gt2uftspglo.html

[P08] 处理浮点精度问题
来源：http://dali.cdnleiting.top/Article/details/gt2nsteifnw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.smart0.xyz/Article/details/gt2oopolxur.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jianghu66.top/Article/details/gt2itharirr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.guowangkeji.top/Article/details/gt2hbvvwvvd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xuanzx.com/Article/details/gt2ayqrlbii.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wasghxta.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.havefunace.top/Article/details/gt2xxqbeftg.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iumwqoht.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jqgufenzy.top/Article/details/gt2cokosjcc.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2fibbkdus.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gaohongyu789.top/Article/details/gt2yaatqwiv.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2roytwnjw.html

[Q01] 创建表
来源：http://dali.jinqigufen.top/Article/details/gt2bhsxwhze.html

CREATE TABLE users (
来源：http://dali.cdnleiting.top/Article/details/gt2yyrvsetl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xziqi.cn/Article/details/gt2xvggrlfo.html

name VARCHAR(50) NOT NULL,
来源：http://dali.quarkkingdee.top/Article/details/gt2oqjcxfre.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhongyouzk.top/Article/details/gt2eojnscww.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jiagoushi.top/Article/details/gt2ldselcvq.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrvbbldo.html

[Q02] 创建带外键的表
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fpvfwkca.html

CREATE TABLE orders (
来源：http://dali.kuanghao11.cn/Article/details/gt2bomsjxxo.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hfpthk.cn/Article/details/gt2pwiltpsj.html

user_id INT NOT NULL,
来源：http://dali.haohaochexian.top/Article/details/gt2dqwahkhj.html

amount DECIMAL(10, 2),
来源：http://dali.jyoumei.cn/Article/details/gt2uhyurlkx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.gogol.net.cn/Article/details/gt2dcetrzwr.html

);
来源：http://dali.wangdashe.top/Article/details/gt2tofohdob.html

[Q03] 增加列
来源：http://dali.hfpthk.cn/Article/details/gt2xricaaeh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.tanke756.top/Article/details/gt2uwpoftmo.html

[Q04] 修改列类型
来源：http://dali.tanke756.top/Article/details/gt2gnhahuwg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yuanzhike.top/Article/details/gt2svvxirtn.html

[Q05] 重命名列
来源：http://dali.yanxiufei.cn/Article/details/gt2xunjxwkf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.gaohongyu789.top/Article/details/gt2iayswcvv.html

[Q06] 删除列
来源：http://dali.aizwys.cn/Article/details/gt2kpornvds.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jianghu66.top/Article/details/gt2iewtfxch.html

[Q07] 删除表
来源：http://dali.sweek.top/Article/details/gt2qglhksaz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.quarkkingdee.top/Article/details/gt2joegikop.html

[Q08] 创建普通索引
来源：http://dali.haohaochexian.top/Article/details/gt2vjfcqwti.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cheryme.top/Article/details/gt2ilnmcabk.html

[Q09] 创建唯一索引
来源：http://dali.yangfankeji.com/Article/details/gt2zohagkpm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.sxryk.cn/Article/details/gt2gmzytsmt.html

[Q10] 插入单行
来源：http://dali.daxiang520.top/Article/details/gt2cxzfzwvu.html


<!-- 参考信息 -->