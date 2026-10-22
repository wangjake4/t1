代发 wailian999

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.wangshuangyany.cn/Article/details/gt2zzcvzsce.html

Ruby: warn "err"
来源：http://dali.jiagoushi.top/Article/details/gt2vrosycsn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.aizwys.cn/Article/details/gt2kcpysvbr.html

[M07] 判断是否为主入口
来源：http://dali.aizwys.cn/Article/details/gt2iezvsfyq.html

Py:   if __name__ == "__main__":
来源：http://dali.shuidangran.top/Article/details/gt2ppbelkfv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cqqwz.cn/Article/details/gt2riuxpgvd.html

JS:   require.main === module
来源：http://dali.yanxiufei.cn/Article/details/gt2yewhycwv.html

TS:   require.main === module
来源：http://dali.shuidangran.top/Article/details/gt2rfndvxlo.html

Java: public static void main(String[] args)
来源：http://dali.jinqigufen.top/Article/details/gt2itnbnuvg.html

Go:   func main()
来源：http://dali.dianchejie.cn/Article/details/gt2wmebcbhl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hongshengwenyu.top/Article/details/gt2crpoibls.html

C#:   static void Main(string[] args)
来源：http://dali.vqdsnc.cn/Article/details/gt2evqwwzzm.html

[M08] 获取系统与运行时信息
来源：http://dali.zhengqikj.top/Article/details/gt2lkhdpdzr.html

Py:   platform.system();  platform.python_version()
来源：http://dali.guannengcc.top/Article/details/gt2ughggken.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yueranfly.top/Article/details/gt2jvsaekfe.html

JS:   process.platform;  process.version
来源：http://dali.meibo888.top/Article/details/gt2ygnrxgmc.html

TS:   process.platform;  process.version
来源：http://dali.shuidangran.top/Article/details/gt2djkzvbxz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.daxiang520.top/Article/details/gt2dkeunssn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yuxming.cn/Article/details/gt2ntummvsw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yj202588.top/Article/details/gt2opoxdnpz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jyoumei.cn/Article/details/gt2snamtohl.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2ofgvitif.html

N. 数据结构与算法
来源：http://dali.zycfv.cn/Article/details/gt2bajeufpi.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2iytbpydi.html

[N01] 二分查找（有序数组）
来源：http://dali.wangshuangyany.cn/Article/details/gt2bwjzuput.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.smart0.xyz/Article/details/gt2vfjyaejh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2trffzghh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ppjwa.cn/Article/details/gt2vbiaaphp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sweek.top/Article/details/gt2ntuislqa.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ivvv.top/Article/details/gt2klbyijcl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.birdmap.top/Article/details/gt2ybjjtuhx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.9152youxi.cn/Article/details/gt2mcbssbfe.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zycfv.cn/Article/details/gt2uvomdvta.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nqhyzbfr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xylfe.cn/Article/details/gt2oyqetymy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.9152youxi.cn/Article/details/gt2uxkyxkgs.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.svipenyu.cn/Article/details/gt2iuucmyck.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.meibo888.top/Article/details/gt2ljbymgrh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhixingplan.top/Article/details/gt2bkowuvoz.html

Go:   slices.Sort(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2mslqarrj.html

Ruby: arr.sort
来源：http://dali.iojbl.cn/Article/details/gt2wukknnen.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.bjfxy.top/Article/details/gt2ybzqijgh.html

[N03] 快速排序（分治示例）
来源：http://dali.c1oappe.top/Article/details/gt2gsrugojv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.pengpengdd.cyou/Article/details/gt2qpixeaqj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jianghu66.top/Article/details/gt2yvjltdbo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cqqwz.cn/Article/details/gt2lxcetqcd.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ldtlmagr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.chenjidiqi.icu/Article/details/gt2sqprevkx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj20258.top/Article/details/gt2gtgoopyk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.birdmap.top/Article/details/gt2siuplhjc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cheryme.top/Article/details/gt2wueqkjvh.html

[N04] 斐波那契数列
来源：http://dali.yj202588.top/Article/details/gt2fznwsuvi.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xinyue.icu/Article/details/gt2lvdttlkc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.0kj1m.cn/Article/details/gt2etlheioj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ehwqpu.com/Article/details/gt2sfqkwimp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gt2dygzsyzf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yuanzhike.top/Article/details/gt2azdduxdq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.wangshuangyany.cn/Article/details/gt2rsmaqreu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.mhx1999.top/Article/details/gt2znyascem.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.gzhubu.top/Article/details/gt2rzoaaobo.html

[N05] 最大公约数
来源：http://dali.iojbl.cn/Article/details/gt2ueqwoaym.html

Py:   math.gcd(a, b)
来源：http://dali.ybcxt.top/Article/details/gt2dwpqelkb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.tian-w.cn/Article/details/gt2nhrgejhv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cucudq.cn/Article/details/gt2dvqzjpgs.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigfzy.top/Article/details/gt2jlgfnfhe.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yj202588.top/Article/details/gt2adzqqtgh.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.nanxuanxn.top/Article/details/gt2oehbowfl.html

Ruby: a.gcd(b)
来源：http://dali.yvedp.cn/Article/details/gt2timwizua.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gzhubu.top/Article/details/gt2puiugnau.html

[N06] 判断回文字符串
来源：http://dali.sweek.top/Article/details/gt2tvowoisq.html

Py:   s == s[::-1]
来源：http://dali.hongshengwenyu.top/Article/details/gt2ieglxxul.html

PHP:  $s === strrev($s);
来源：http://dali.cheryme.top/Article/details/gt2lgbtjdsz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gt2caijtkzh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gt2nnjczsnz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jlsjyb.cn/Article/details/gt2xaiczxdb.html

Go:   // 双指针从两端比较
来源：http://dali.hnqzz.top/Article/details/gt2afbrltle.html

Ruby: s == s.reverse
来源：http://dali.xuetiantiany.cn/Article/details/gt2wvsjpval.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.mhx1999.top/Article/details/gt2zdwsyohu.html

[N07] 两数之和（返回下标）
来源：http://dali.sweek.top/Article/details/gt2zqwtpxqf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.dashuyun.cn/Article/details/gt2ggedlupt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.snrcjt.cn/Article/details/gt2kngrwdfx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jiagoushi.top/Article/details/gt2yryxolcu.html

TS:   // 手写 Map<string, number>
来源：http://dali.xuetiantiany.cn/Article/details/gt2qnvtjtaf.html

Java: // 手写 HashMap
来源：http://dali.gotoacloud.top/Article/details/gt2ejenjcpz.html

Go:   // 手写 map[int]int
来源：http://dali.c1oappe.top/Article/details/gt2quyznnjq.html

Ruby: // 手写 Hash
来源：http://dali.shzxlz.cn/Article/details/gt2umqpishb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shuidangran.top/Article/details/gt2chaorwgi.html

[N08] 生成全排列
来源：http://dali.ppjwa.cn/Article/details/gt2euozuzsr.html

Py:   itertools.permutations(arr)
来源：http://dali.aizwys.cn/Article/details/gt2mljckzyh.html

PHP:  // 手写递归交换
来源：http://dali.tianlin.xyz/Article/details/gt2dcdkbyir.html

JS:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gt2jngchkta.html

TS:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gt2lfhkbjjw.html

Java: // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gt2yxgqmjmn.html

Go:   // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gt2wvnkwalv.html

Ruby: arr.permutation.to_a
来源：http://dali.quarkkingdee.top/Article/details/gt2itnxlqwo.html

C#:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gt2riasgxkq.html

[N09] 栈与队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mbihgnbh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ppjwa.cn/Article/details/gt2ewaozlst.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cqqwz.cn/Article/details/gt2swayycjq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.chenlongwang.top/Article/details/gt2hjxvibsw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gotoacloud.top/Article/details/gt2rpcpdhde.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.aizwys.cn/Article/details/gt2yzyveiem.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.andypj.xyz/Article/details/gt2gjhjhtad.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sufxvd.cn/Article/details/gt2qqvysfpa.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xuetiantiany.cn/Article/details/gt2wlgbgmed.html

[N10] 链表节点定义
来源：http://dali.shuidangran.top/Article/details/gt2beanauvq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yueranfly.top/Article/details/gt2zzgoclii.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gogol.net.cn/Article/details/gt2vgprusfb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jyoumei.cn/Article/details/gt2ipdrnuye.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ulpczzqz.html

Java: class Node { int v; Node next; }
来源：http://dali.yonumen.top/Article/details/gt2mqwuqcbl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yuxming.cn/Article/details/gt2ygjswyhv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhoulong.xyz/Article/details/gt2ufinwplx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.andypj.xyz/Article/details/gt2phnqchwf.html

[N11] 二叉树中序遍历
来源：http://dali.yonumen.top/Article/details/gt2vurswkbj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cheryme.top/Article/details/gt2ikgepjpk.html

PHP:  // 手写递归函数
来源：http://dali.iojbl.cn/Article/details/gt2rvqfiaqt.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daria6918.cn/Article/details/gt2qsgeurar.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pengpengdd.cyou/Article/details/gt2urqxzema.html

Java: // 手写递归
来源：http://dali.daxiang520.top/Article/details/gt2nbktswbx.html

Go:   // 手写递归
来源：http://dali.ybcxt.top/Article/details/gt2ftdcgqui.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yuanzhike.top/Article/details/gt2qfezzdlc.html

C#:   // 手写递归
来源：http://dali.ppjwa.cn/Article/details/gt2ttjonqyh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.snrcjt.cn/Article/details/gt2oyaitwwk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cdnleiting.top/Article/details/gt2bibyuvdm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yangfankeji.com/Article/details/gt2bzzotmrm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sweek.top/Article/details/gt2brvdtdvp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxinkj.top/Article/details/gt2hsljsuzu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jianghu66.top/Article/details/gt2qaaunrcq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ydzc1.top/Article/details/gt2ojfwxhge.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jqgfzy.top/Article/details/gt2giqrmwfc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.kuanghao11.cn/Article/details/gt2dspyqgkl.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2wguzgvdn.html

O. 并发与异步
来源：http://dali.tianlin.xyz/Article/details/gt2gsiyqcvi.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2rpnqeimf.html

[O01] 启动一个线程
来源：http://dali.cqqwz.cn/Article/details/gt2mqmzpyvm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.vqdsnc.cn/Article/details/gt2vqynbrga.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ydzc1.top/Article/details/gt2wirlzmjz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.chenjidiqi.icu/Article/details/gt2rkimbqje.html

TS:   // 同 JS
来源：http://dali.fzhhl.top/Article/details/gt2vnlisiiv.html

Java: new Thread(() -> f()).start()
来源：http://dali.jqgfzy.top/Article/details/gt2nuqvylru.html

Go:   go f()
来源：http://dali.yuanzhike.top/Article/details/gt2biqeepxm.html

Ruby: Thread.new { f }
来源：http://dali.shangyingyoupin.top/Article/details/gt2tgwmohoq.html

C#:   Task.Run(() => F());
来源：http://dali.zycfv.cn/Article/details/gt2axymnfbz.html

[O02] 使用线程池
来源：http://dali.haohaochexian.top/Article/details/gt2bnchxjai.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cqqwz.cn/Article/details/gt2iqjvgbwn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ehwqpu.com/Article/details/gt2fuqzcqli.html

JS:   // worker_threads 线程池
来源：http://dali.andypj.xyz/Article/details/gt2cunxogfd.html

TS:   // worker_threads 线程池
来源：http://dali.dashuyun.cn/Article/details/gt2xdwxhfwr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.sysykeji.top/Article/details/gt2ebyjlczn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gaohongyu789.top/Article/details/gt2ejqyewvx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jinqigfzy.top/Article/details/gt2znekafwm.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cqqwz.cn/Article/details/gt2thfdcvmc.html

[O03] 加锁保护共享数据
来源：http://dali.gotoacloud.top/Article/details/gt2tuvsgkfx.html

Py:   with lock: shared += 1
来源：http://dali.hywenlv.cn/Article/details/gt2gciwufxk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yanxiufei.cn/Article/details/gt2qaolskdd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.chenjidiqi.icu/Article/details/gt2thotysvl.html

TS:   // 同 JS
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ybbxjvpe.html

Java: synchronized (this) { shared++; }
来源：http://dali.316326.xyz/Article/details/gt2ryhsaiik.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.tian-w.cn/Article/details/gt2zjdbfsmg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yvedp.cn/Article/details/gt2silsamfj.html

C#:   lock (gate) { shared++; }
来源：http://dali.jyoumei.cn/Article/details/gt2ibealafy.html

[O04] 定义异步函数并等待
来源：http://dali.guannengcc.top/Article/details/gt2dsaeslcb.html

Py:   async def f():⏎    await g()
来源：http://dali.dianchejie.cn/Article/details/gt2jnfrmfun.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.wangdashe.top/Article/details/gt2bopsknsz.html

JS:   async function f() { await g(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2umhqsamr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2rvwalywv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinqigufen.top/Article/details/gt2veyhmrep.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shzxlz.cn/Article/details/gt2ewavmecd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ppjwa.cn/Article/details/gt2itveilah.html

C#:   async Task F() { await G(); }
来源：http://dali.bjfxy.top/Article/details/gt2qnxqxhmj.html

[O05] 并发执行并等待全部完成
来源：http://dali.yanxiufei.cn/Article/details/gt2vgnzjmzb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jqgfzy.top/Article/details/gt2aoluvmwb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xuasolqs.html

JS:   await Promise.all(tasks)
来源：http://dali.hnqzz.top/Article/details/gt2ygfjjpin.html

TS:   await Promise.all(tasks)
来源：http://dali.kuanghao11.cn/Article/details/gt2distloqm.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.aibaodan.cn/Article/details/gt2aurqwqnb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.redwolf501.top/Article/details/gt2urrjxspp.html

Ruby: threads.map(&:join)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2caelkula.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ntetacfu.html

[O06] 使用进程池
来源：http://dali.aizwys.cn/Article/details/gt2nnqtypib.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ifpelnyz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ehwqpu.com/Article/details/gt2lzfkhzxt.html

JS:   // child_process / cluster 模块
来源：http://dali.snrcjt.cn/Article/details/gt2cikpyxyq.html

TS:   // child_process / cluster 模块
来源：http://dali.jiagoushi.top/Article/details/gt2apiqipfa.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.nanxuanxn.top/Article/details/gt2xzyyxdrr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jinqigufen.top/Article/details/gt2negzvhkw.html

Ruby: // fork 块
来源：http://dali.snrcjt.cn/Article/details/gt2zezrgkno.html

C#:   Parallel.For
来源：http://dali.xuanzx.com/Article/details/gt2alrrjwxc.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2isyduufb.html

P. 常用工具函数
来源：http://dali.yuxming.cn/Article/details/gt2vmqaqtzb.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2qkelmepp.html

[P01] 生成 UUID
来源：http://dali.jyoumei.cn/Article/details/gt2tkogmrjr.html

Py:   str(uuid.uuid4())
来源：http://dali.yuanzhike.top/Article/details/gt2erssfaek.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sufxvd.cn/Article/details/gt2juhmkxdb.html

JS:   crypto.randomUUID()
来源：http://dali.zhengqikj.top/Article/details/gt2afudmmvj.html

TS:   crypto.randomUUID()
来源：http://dali.wangdashe.top/Article/details/gt2fvjqzyll.html

Java: UUID.randomUUID().toString()
来源：http://dali.shzxlz.cn/Article/details/gt2lqaaksqg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hnqzz.top/Article/details/gt2xasljjeo.html

Ruby: SecureRandom.uuid
来源：http://dali.daxiang520.top/Article/details/gt2ikvajsvk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yanxiufei.cn/Article/details/gt2sopeszuk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhongyouzk.top/Article/details/gt2ahzwnveo.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yj202588.top/Article/details/gt2uxhjiety.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jianghu66.top/Article/details/gt2yvyxwsww.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shzxlz.cn/Article/details/gt2yexjcdhu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jqgfzy.top/Article/details/gt2ekcvfxur.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cdnleiting.top/Article/details/gt2wxjokpwf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.chenlongwang.top/Article/details/gt2bpytzotp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xuanzx.com/Article/details/gt2rwhwxshe.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.fengsongda.top/Article/details/gt2tcnlercp.html

[P03] 生成短随机字符串
来源：http://dali.cdnleiting.top/Article/details/gt2zmsaasmx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.birdmap.top/Article/details/gt2jscspzch.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yj20258888.top/Article/details/gt2mldgpryy.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pycfn.com/Article/details/gt2avfjrqib.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuanzx.com/Article/details/gt2tlpmsptx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hpvxjbom.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jiagoushi.top/Article/details/gt2gzxlmbdk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jiagoushi.top/Article/details/gt2ixnseepw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.iojbl.cn/Article/details/gt2vylhzdtp.html

[P04] 求长度
来源：http://dali.quarkkingdee.top/Article/details/gt2ucthpozg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yonumen.top/Article/details/gt2mohsjquz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rwfwlnwn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yangfankeji.com/Article/details/gt2paanaleb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sufxvd.cn/Article/details/gt2tpvczuue.html

Java: list.size();  map.size();  s.length()
来源：http://dali.wangshuangyany.cn/Article/details/gt2utjhvees.html

Go:   len(arr);  len(m)
来源：http://dali.yonumen.top/Article/details/gt2qvhoaxcp.html

Ruby: x.length;  x.size
来源：http://dali.cheryme.top/Article/details/gt2sadsmkaf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhengqikj.top/Article/details/gt2reililvd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yuxming.cn/Article/details/gt2shqenhyk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sweek.top/Article/details/gt2vpduxqrs.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yanxiufei.cn/Article/details/gt2qoglbhtn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xziqi.cn/Article/details/gt2iwcfvdre.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sufxvd.cn/Article/details/gt2ivusnnhm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhengqikj.top/Article/details/gt2jjaijowd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.guowangkeji.top/Article/details/gt2audpjdwp.html

Ruby: a == b
来源：http://dali.quarkkingdee.top/Article/details/gt2bgsaqbet.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2grampxlz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sysykeji.top/Article/details/gt2ltneapzn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.sweek.top/Article/details/gt2gjgeydqt.html

PHP:  if (empty($x)) {}
来源：http://dali.zhixingplan.top/Article/details/gt2hqabtymh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shzxlz.cn/Article/details/gt2gqreohrv.html

TS:   if (x == null) {}
来源：http://dali.9152youxi.cn/Article/details/gt2bxohnugv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ppjwa.cn/Article/details/gt2congayfd.html

Go:   if x == nil {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vbvupvny.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yonumen.top/Article/details/gt2zytbznrd.html

C#:   if (x is null) {}
来源：http://dali.ppjwa.cn/Article/details/gt2lrjgegli.html

[P07] 防抖与节流
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zujquofp.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xuanzx.com/Article/details/gt2jjdmskdp.html

PHP:  // 手写时间戳比较
来源：http://dali.yuxming.cn/Article/details/gt2xeqrsrpg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hongshengwenyu.top/Article/details/gt2jdenlomc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ehwqpu.com/Article/details/gt2seokmqmg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xwnvgxtt.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yongpay.top/Article/details/gt2oobwlyzq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.0kj1m.cn/Article/details/gt2tmlydvzn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.cqqwz.cn/Article/details/gt2khzfving.html

[P08] 处理浮点精度问题
来源：http://dali.pengpengdd.cyou/Article/details/gt2oeoeevmv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yuxming.cn/Article/details/gt2acccpirg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.nanxuanxn.top/Article/details/gt2bkiyfaal.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.redwolf501.top/Article/details/gt2htjlmqyi.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xinyue.icu/Article/details/gt2mkeibwns.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yanxiufei.cn/Article/details/gt2paszbxif.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.gogol.net.cn/Article/details/gt2ecbfbpdz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yj20258888.top/Article/details/gt2vfgoxojt.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.chenlongwang.top/Article/details/gt2kmtjxpxm.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2dtymxmaz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sufxvd.cn/Article/details/gt2zpboxhno.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2apjrxnqb.html

[Q01] 创建表
来源：http://dali.ydzc1.top/Article/details/gt2tajsxhoo.html

CREATE TABLE users (
来源：http://dali.hnqzz.top/Article/details/gt2lkaaytpq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.andypj.xyz/Article/details/gt2pmotdbmf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.fzhhl.top/Article/details/gt2ylfosibk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ydzc1.top/Article/details/gt2bsehzzni.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2pnslkmzp.html

);
来源：http://dali.c1oappe.top/Article/details/gt2hurwybfx.html

[Q02] 创建带外键的表
来源：http://dali.tian-w.cn/Article/details/gt2mbuxpjtq.html

CREATE TABLE orders (
来源：http://dali.gotoacloud.top/Article/details/gt2lasmsnri.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigufen.top/Article/details/gt2qzhzdynx.html

user_id INT NOT NULL,
来源：http://dali.yanxiufei.cn/Article/details/gt2sikgougk.html

amount DECIMAL(10, 2),
来源：http://dali.yongpay.top/Article/details/gt2gtcqdvej.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jlsjyb.cn/Article/details/gt2aeeerzrb.html

);
来源：http://dali.cheryme.top/Article/details/gt2osrchrse.html

[Q03] 增加列
来源：http://dali.chenzaomai.com/Article/details/gt2qdtimuiq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yj20258.top/Article/details/gt2kvegmdbo.html

[Q04] 修改列类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lxztcnph.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.chenlongwang.top/Article/details/gt2lxtlzdbh.html

[Q05] 重命名列
来源：http://dali.cqqwz.cn/Article/details/gt2vdnkkutp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sysykeji.top/Article/details/gt2semwnhfk.html

[Q06] 删除列
来源：http://dali.0kj1m.cn/Article/details/gt2bswrbhbu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zdqjudy.top/Article/details/gt2rkjgxuie.html

[Q07] 删除表
来源：http://dali.snrcjt.cn/Article/details/gt2rcnlgwai.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hywenlv.cn/Article/details/gt2shfrlxfg.html

[Q08] 创建普通索引
来源：http://dali.yangfankeji.com/Article/details/gt2fepicbrs.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.0kj1m.cn/Article/details/gt2npkzcgpf.html

[Q09] 创建唯一索引
来源：http://dali.vqdsnc.cn/Article/details/gt2cupljdzw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ybcxt.top/Article/details/gt2dehuskik.html

[Q10] 插入单行
来源：http://dali.yangfankeji.com/Article/details/gt2oewdclsl.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jyoumei.cn/Article/details/gt2bxibwkep.html

[Q11] 一次插入多行
来源：http://dali.gaohongyu789.top/Article/details/gt2osaubhbc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yj20258888.top/Article/details/gt2qlbllxyl.html

[Q12] 插入后取自增 ID
来源：http://dali.snrcjt.cn/Article/details/gt2sfnmhwka.html


<!-- 参考信息 -->