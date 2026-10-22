代发 wailian999

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xuetiantiany.cn/Article/details/gt2gifuykje.html

Ruby: warn "err"
来源：http://dali.jianghu66.top/Article/details/gt2bpuxbicg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ppjwa.cn/Article/details/gt2pryjyyur.html

[M07] 判断是否为主入口
来源：http://dali.yj202588.top/Article/details/gt2pszhinmk.html

Py:   if __name__ == "__main__":
来源：http://dali.tanke756.top/Article/details/gt2qhzccmzp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yuanzhike.top/Article/details/gt2bckmfzga.html

JS:   require.main === module
来源：http://dali.zhiwuduotai.top/Article/details/gt2ohkorjar.html

TS:   require.main === module
来源：http://dali.sysykeji.top/Article/details/gt2htawzvma.html

Java: public static void main(String[] args)
来源：http://dali.zhiwuduotai.top/Article/details/gt2extbiiym.html

Go:   func main()
来源：http://dali.havefunace.top/Article/details/gt2gjmqsvge.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yueranfly.top/Article/details/gt2foczhrcj.html

C#:   static void Main(string[] args)
来源：http://dali.haohaochexian.top/Article/details/gt2vyvfmmbm.html

[M08] 获取系统与运行时信息
来源：http://dali.hysaishi.cn/Article/details/gt2ynyryqfy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinqigufen.top/Article/details/gt2bwpmqexb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hongshengwenyu.top/Article/details/gt2ftozkxjv.html

JS:   process.platform;  process.version
来源：http://dali.dianchejie.cn/Article/details/gt2nzpnunza.html

TS:   process.platform;  process.version
来源：http://dali.yangfankeji.com/Article/details/gt2gqvufeam.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhoulong.xyz/Article/details/gt2jivtliqx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xuanzx.com/Article/details/gt2mindeacu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xylfe.cn/Article/details/gt2bfviuaul.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cdnleiting.top/Article/details/gt2qajwmpcf.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2gunsjuij.html

N. 数据结构与算法
来源：http://dali.quarkkingdee.top/Article/details/gt2ykwjftpq.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bvbdpixn.html

[N01] 二分查找（有序数组）
来源：http://dali.yj202588.top/Article/details/gt2fkbpkjab.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ydzc1.top/Article/details/gt2yvjcjhrn.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.chenlongwang.top/Article/details/gt2rmrstrav.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jlsjyb.cn/Article/details/gt2wjgdvwur.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxinkj.top/Article/details/gt2ldmlhlvp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cheryme.top/Article/details/gt2lzprrpbl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gt2xqqujcjn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.redwolf501.top/Article/details/gt2qxpoqlwt.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.mhx1999.top/Article/details/gt2qrerqbvo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shuidangran.top/Article/details/gt2inoxhknr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zdqjudy.top/Article/details/gt2orlyvvld.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.fzhhl.top/Article/details/gt2muodujeo.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qycbigpf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258.top/Article/details/gt2fgovchtc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jiagoushi.top/Article/details/gt2kybasclp.html

Go:   slices.Sort(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2laaxrajr.html

Ruby: arr.sort
来源：http://dali.svipenyu.cn/Article/details/gt2kyywplna.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ehwqpu.com/Article/details/gt2lsvspalh.html

[N03] 快速排序（分治示例）
来源：http://dali.yuxming.cn/Article/details/gt2nhrbdfyb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj202588.top/Article/details/gt2nmkyseox.html

PHP:  // 递归实现，或用 usort
来源：http://dali.vqdsnc.cn/Article/details/gt2fmtrvgjo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuxming.cn/Article/details/gt2fzpgekya.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jiagoushi.top/Article/details/gt2movtbsbn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shzxlz.cn/Article/details/gt2jovzlttb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sxryk.cn/Article/details/gt2qbjyulsi.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jqgufenzy.top/Article/details/gt2eicnydgb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cqqwz.cn/Article/details/gt2fuxjpmar.html

[N04] 斐波那契数列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iytczuoi.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tkijhbie.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gzhubu.top/Article/details/gt2eeubqdic.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gt2djerwrxz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fengsongda.top/Article/details/gt2didqfygm.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gogol.net.cn/Article/details/gt2dmizrgzk.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hongshengwenyu.top/Article/details/gt2vmfsazhh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.bjfxy.top/Article/details/gt2nkvxxmxp.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yangfankeji.com/Article/details/gt2ieknysei.html

[N05] 最大公约数
来源：http://dali.tanke756.top/Article/details/gt2wktspppq.html

Py:   math.gcd(a, b)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ttozsmyu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jiagoushi.top/Article/details/gt2dxnvurjs.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ivvv.top/Article/details/gt2pmwruxmc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuanzx.com/Article/details/gt2phawdngj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cpxabtmx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.nanxuanxn.top/Article/details/gt2tlgbqmya.html

Ruby: a.gcd(b)
来源：http://dali.jinqigfzy.top/Article/details/gt2rlrhnyfx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.chenlongwang.top/Article/details/gt2ssqoxdmw.html

[N06] 判断回文字符串
来源：http://dali.xuanzx.com/Article/details/gt2nvlistqa.html

Py:   s == s[::-1]
来源：http://dali.zhixingplan.top/Article/details/gt2vgijeblr.html

PHP:  $s === strrev($s);
来源：http://dali.ehwqpu.com/Article/details/gt2ljompdqz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gt2yafplmvu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gt2sovjjppy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gotoacloud.top/Article/details/gt2mvfgbrao.html

Go:   // 双指针从两端比较
来源：http://dali.jqgufenzy.top/Article/details/gt2riwsmmjv.html

Ruby: s == s.reverse
来源：http://dali.hysaishi.cn/Article/details/gt2jxcddxlr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.chenjidiqi.icu/Article/details/gt2bmgfcefr.html

[N07] 两数之和（返回下标）
来源：http://dali.cqqwz.cn/Article/details/gt2vhlmiwjx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sweek.top/Article/details/gt2cdwujtpo.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sufxvd.cn/Article/details/gt2nyjayvwu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.c1oappe.top/Article/details/gt2mrayycir.html

TS:   // 手写 Map<string, number>
来源：http://dali.xinyue.icu/Article/details/gt2bmqyrbmw.html

Java: // 手写 HashMap
来源：http://dali.ydzc1.top/Article/details/gt2mwoyycyn.html

Go:   // 手写 map[int]int
来源：http://dali.nwbrower.top/Article/details/gt2atylswey.html

Ruby: // 手写 Hash
来源：http://dali.sufxvd.cn/Article/details/gt2eppkdoec.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jlsjyb.cn/Article/details/gt2wlefvabo.html

[N08] 生成全排列
来源：http://dali.nwbrower.top/Article/details/gt2yddlaqce.html

Py:   itertools.permutations(arr)
来源：http://dali.ydzc1.top/Article/details/gt2wnddmvbe.html

PHP:  // 手写递归交换
来源：http://dali.ydzc1.top/Article/details/gt2efqqagwt.html

JS:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gt2foqjnani.html

TS:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gt2bfwoctif.html

Java: // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gt2tnsybcju.html

Go:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gt2frwggfkh.html

Ruby: arr.permutation.to_a
来源：http://dali.aizwys.cn/Article/details/gt2fwrsimpx.html

C#:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gt2qrovursa.html

[N09] 栈与队列
来源：http://dali.daria6918.cn/Article/details/gt2quyqvjut.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.smart0.xyz/Article/details/gt2djxwuska.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gotoacloud.top/Article/details/gt2apcekigz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yonumen.top/Article/details/gt2morsljcw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jyoumei.cn/Article/details/gt2gouwsquq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.pycfn.com/Article/details/gt2thxgxftp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.snrcjt.cn/Article/details/gt2hyjfcjjl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.fzhhl.top/Article/details/gt2zmalcypx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.vqdsnc.cn/Article/details/gt2afjunrvs.html

[N10] 链表节点定义
来源：http://dali.gaohongyu789.top/Article/details/gt2dukpoxcv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.fzhhl.top/Article/details/gt2ivqampbi.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yvedp.cn/Article/details/gt2oupzbeoh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gotoacloud.top/Article/details/gt2bhuqrcvp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jyoumei.cn/Article/details/gt2gburyamy.html

Java: class Node { int v; Node next; }
来源：http://dali.haohaochexian.top/Article/details/gt2zmkqrbzz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.fzhhl.top/Article/details/gt2iwefbrbg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2igziysti.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cucudq.cn/Article/details/gt2cvzayapu.html

[N11] 二叉树中序遍历
来源：http://dali.gotoacloud.top/Article/details/gt2vumanclc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sweek.top/Article/details/gt2xsnfuhpq.html

PHP:  // 手写递归函数
来源：http://dali.sxryk.cn/Article/details/gt2fvcnhkny.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ikebmsmg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhengqikj.top/Article/details/gt2kvwfzgvh.html

Java: // 手写递归
来源：http://dali.wangshuangyany.cn/Article/details/gt2jwelukas.html

Go:   // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gt2hngvgrnt.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.meibo888.top/Article/details/gt2udsrkowh.html

C#:   // 手写递归
来源：http://dali.iojbl.cn/Article/details/gt2nidbzjrj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.dianchejie.cn/Article/details/gt2bygxwhfd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.snrcjt.cn/Article/details/gt2fgsjytok.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.chenjidiqi.icu/Article/details/gt2bdxuixue.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jbfogpuw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ackfhleg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cheryme.top/Article/details/gt2viljernk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zdqjudy.top/Article/details/gt2cqmoowna.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shzxlz.cn/Article/details/gt2bayetuki.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.wangdashe.top/Article/details/gt2kzyufwwo.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2ahxeqfhm.html

O. 并发与异步
来源：http://dali.jlsjyb.cn/Article/details/gt2houkqlxy.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2pcniflxj.html

[O01] 启动一个线程
来源：http://dali.jinqigufen.top/Article/details/gt2ugdmhtib.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jianghu66.top/Article/details/gt2eaztxvlk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.9152youxi.cn/Article/details/gt2jhntgflp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.andypj.xyz/Article/details/gt2yqfutxrq.html

TS:   // 同 JS
来源：http://dali.chenlongwang.top/Article/details/gt2lsqvwgiz.html

Java: new Thread(() -> f()).start()
来源：http://dali.nanxinkj.top/Article/details/gt2junympwp.html

Go:   go f()
来源：http://dali.quarkkingdee.top/Article/details/gt2ifoqxqfv.html

Ruby: Thread.new { f }
来源：http://dali.ppjwa.cn/Article/details/gt2xmghwwsa.html

C#:   Task.Run(() => F());
来源：http://dali.yvedp.cn/Article/details/gt2uwvlfqgq.html

[O02] 使用线程池
来源：http://dali.andypj.xyz/Article/details/gt2uvyqalez.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.iojbl.cn/Article/details/gt2ymaoeajq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wjdgqrvi.html

JS:   // worker_threads 线程池
来源：http://dali.fengsongda.top/Article/details/gt2weximyou.html

TS:   // worker_threads 线程池
来源：http://dali.wangshuangyany.cn/Article/details/gt2ddkczekk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yj20258888.top/Article/details/gt2sqihttls.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhixingplan.top/Article/details/gt2cxlftqfm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xziqi.cn/Article/details/gt2umwmmwik.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yanxiufei.cn/Article/details/gt2gxmfjios.html

[O03] 加锁保护共享数据
来源：http://dali.jyoumei.cn/Article/details/gt2xevakaad.html

Py:   with lock: shared += 1
来源：http://dali.xuanzx.com/Article/details/gt2ooytmxsp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.wangdashe.top/Article/details/gt2ntavktyd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cheryme.top/Article/details/gt2ohisvnyq.html

TS:   // 同 JS
来源：http://dali.shuidangran.top/Article/details/gt2azbnxgtf.html

Java: synchronized (this) { shared++; }
来源：http://dali.zdqjudy.top/Article/details/gt2bbbhljqv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.mhx1999.top/Article/details/gt2cpefswcx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yonumen.top/Article/details/gt2lrvxvxew.html

C#:   lock (gate) { shared++; }
来源：http://dali.jiagoushi.top/Article/details/gt2bngtbigr.html

[O04] 定义异步函数并等待
来源：http://dali.cdnleiting.top/Article/details/gt2alpszpkc.html

Py:   async def f():⏎    await g()
来源：http://dali.xuetiantiany.cn/Article/details/gt2mohwanvh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.feifeiyinyue.top/Article/details/gt2fwuucpyt.html

JS:   async function f() { await g(); }
来源：http://dali.sweek.top/Article/details/gt2mueklune.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2ryxlbpvp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yueranfly.top/Article/details/gt2olnbjlsq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gogol.net.cn/Article/details/gt2hfmxfejq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yonumen.top/Article/details/gt2ejpmrjth.html

C#:   async Task F() { await G(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2jdjlfmmq.html

[O05] 并发执行并等待全部完成
来源：http://dali.yanxiufei.cn/Article/details/gt2uhnqzrjd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.nanxinkj.top/Article/details/gt2kfafhbui.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yvedp.cn/Article/details/gt2uqeiycen.html

JS:   await Promise.all(tasks)
来源：http://dali.shangyingyoupin.top/Article/details/gt2uetznoff.html

TS:   await Promise.all(tasks)
来源：http://dali.jqgufenzy.top/Article/details/gt2yogjfesi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.iojbl.cn/Article/details/gt2rercibcb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.mhx1999.top/Article/details/gt2rxunzxph.html

Ruby: threads.map(&:join)
来源：http://dali.nanxinkj.top/Article/details/gt2nlmufqif.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.quarkkingdee.top/Article/details/gt2mroprqjr.html

[O06] 使用进程池
来源：http://dali.jinqigfzy.top/Article/details/gt2duicende.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yanxiufei.cn/Article/details/gt2pcpisqio.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.nanxuanxn.top/Article/details/gt2mdwutzqx.html

JS:   // child_process / cluster 模块
来源：http://dali.316326.xyz/Article/details/gt2uuiqzpvx.html

TS:   // child_process / cluster 模块
来源：http://dali.jqgfzy.top/Article/details/gt2uzdnmvhl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hkxydihc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.haohaochexian.top/Article/details/gt2ufvkexas.html

Ruby: // fork 块
来源：http://dali.jianghu66.top/Article/details/gt2qmmvwrcz.html

C#:   Parallel.For
来源：http://dali.zdqjudy.top/Article/details/gt2mrriplph.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2bdytfhtz.html

P. 常用工具函数
来源：http://dali.pycfn.com/Article/details/gt2ytuzidrj.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2nuxfzrso.html

[P01] 生成 UUID
来源：http://dali.shzxlz.cn/Article/details/gt2qyzhqkwg.html

Py:   str(uuid.uuid4())
来源：http://dali.yangfankeji.com/Article/details/gt2aaxbjinf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yongpay.top/Article/details/gt2uysscgfo.html

JS:   crypto.randomUUID()
来源：http://dali.gotoacloud.top/Article/details/gt2tyiicdmz.html

TS:   crypto.randomUUID()
来源：http://dali.gzhubu.top/Article/details/gt2hfawbdal.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhengqikj.top/Article/details/gt2nilpdtxa.html

Go:   // 用 github.com/google/uuid
来源：http://dali.wangdashe.top/Article/details/gt2rlobivpw.html

Ruby: SecureRandom.uuid
来源：http://dali.xuetiantiany.cn/Article/details/gt2pzipsfzg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.wangshuangyany.cn/Article/details/gt2bnfqhjmk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhoulong.xyz/Article/details/gt2fittttlj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jqgfzy.top/Article/details/gt2ujjtwobz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jqgfzy.top/Article/details/gt2kmnowcsx.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jqgfzy.top/Article/details/gt2wzuofaty.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yangfankeji.com/Article/details/gt2npsemafg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hammf.cn/Article/details/gt2tcsfthiz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hywenlv.cn/Article/details/gt2usycvcwd.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.c1oappe.top/Article/details/gt2hevukbwu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yonumen.top/Article/details/gt2mluckgum.html

[P03] 生成短随机字符串
来源：http://dali.ybcxt.top/Article/details/gt2toxullde.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.gaohongyu789.top/Article/details/gt2mrmgfjak.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.bjfxy.top/Article/details/gt2yfszdklm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhongyouzk.top/Article/details/gt2aacvivio.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jlsjyb.cn/Article/details/gt2ctywaorr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.316326.xyz/Article/details/gt2pdzjlovl.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhengqikj.top/Article/details/gt2cvaxnncr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhoulong.xyz/Article/details/gt2axfmhrlc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ehwqpu.com/Article/details/gt2zrtedxsv.html

[P04] 求长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iopxaxry.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yuxming.cn/Article/details/gt2wxlbdxvv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gt2lranppyc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yfgidjfu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cugrsohs.html

Java: list.size();  map.size();  s.length()
来源：http://dali.guowangkeji.top/Article/details/gt2mbyyuopc.html

Go:   len(arr);  len(m)
来源：http://dali.iojbl.cn/Article/details/gt2hcsaditz.html

Ruby: x.length;  x.size
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wfexxqsb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqebkce.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yvedp.cn/Article/details/gt2xfxngwox.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.guannengcc.top/Article/details/gt2nzxewrzd.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cpxptlqi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.0kj1m.cn/Article/details/gt2maevjirc.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xziqi.cn/Article/details/gt2ygqqlhkg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xylfe.cn/Article/details/gt2peqjzfsn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ehwqpu.com/Article/details/gt2qhjkutix.html

Ruby: a == b
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vbivpoaj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.daxiang520.top/Article/details/gt2jdjkxlhd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.snrcjt.cn/Article/details/gt2xrfmyqow.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yj20258888.top/Article/details/gt2rzgbflen.html

PHP:  if (empty($x)) {}
来源：http://dali.9152youxi.cn/Article/details/gt2kuabkstg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.fzhhl.top/Article/details/gt2cevwtocf.html

TS:   if (x == null) {}
来源：http://dali.316326.xyz/Article/details/gt2cofofonh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.dianchejie.cn/Article/details/gt2bvovacxr.html

Go:   if x == nil {}
来源：http://dali.guannengcc.top/Article/details/gt2muqzavpu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rzkaboii.html

C#:   if (x is null) {}
来源：http://dali.xuanzx.com/Article/details/gt2wpqidgfd.html

[P07] 防抖与节流
来源：http://dali.wangshuangyany.cn/Article/details/gt2ezxdlvat.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.havefunace.top/Article/details/gt2wtqheqxu.html

PHP:  // 手写时间戳比较
来源：http://dali.yanxiufei.cn/Article/details/gt2zlasuwir.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cqqwz.cn/Article/details/gt2cevpthtj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xziqi.cn/Article/details/gt2zaizubbi.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kiakrzvg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.pycfn.com/Article/details/gt2oshztswl.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhiwuduotai.top/Article/details/gt2jszmbxdd.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shangyingyoupin.top/Article/details/gt2nmqriuhl.html

[P08] 处理浮点精度问题
来源：http://dali.svipenyu.cn/Article/details/gt2qwmjkhqe.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.tian-w.cn/Article/details/gt2dvreejrr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhoulong.xyz/Article/details/gt2xyofqljb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhoulong.xyz/Article/details/gt2nkjlwjmw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uorhzfuf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yanxiufei.cn/Article/details/gt2hyrbcabb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yuanzhike.top/Article/details/gt2ysedrzkb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shuidangran.top/Article/details/gt2bukttstz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.havefunace.top/Article/details/gt2trwwdhvd.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2vzbjbiup.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.guowangkeji.top/Article/details/gt2xfbmojny.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2rgoqlfvq.html

[Q01] 创建表
来源：http://dali.dianchejie.cn/Article/details/gt2xwpjzurk.html

CREATE TABLE users (
来源：http://dali.sxryk.cn/Article/details/gt2iufvluqh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shzxlz.cn/Article/details/gt2tyxgbqcn.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yj202588.top/Article/details/gt2qrebgyfg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.fengsongda.top/Article/details/gt2cplabkiz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ydzc1.top/Article/details/gt2koaqqoln.html

);
来源：http://dali.kuanghao11.cn/Article/details/gt2orlatqjm.html

[Q02] 创建带外键的表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mxwwcogt.html

CREATE TABLE orders (
来源：http://dali.c1oappe.top/Article/details/gt2zzscgwjg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhiwuduotai.top/Article/details/gt2wbbqfpbi.html

user_id INT NOT NULL,
来源：http://dali.chenzaomai.com/Article/details/gt2untznthv.html

amount DECIMAL(10, 2),
来源：http://dali.chenlongwang.top/Article/details/gt2hxpebyul.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.gzhubu.top/Article/details/gt2gupmnlvp.html

);
来源：http://dali.ydzc1.top/Article/details/gt2hoairqjd.html

[Q03] 增加列
来源：http://dali.zycfv.cn/Article/details/gt2bjxqaiod.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.birdmap.top/Article/details/gt2jhpixyet.html

[Q04] 修改列类型
来源：http://dali.shangyingyoupin.top/Article/details/gt2btmqivtv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gogol.net.cn/Article/details/gt2vlagxhcd.html

[Q05] 重命名列
来源：http://dali.zycfv.cn/Article/details/gt2puxhabzf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yvedp.cn/Article/details/gt2cybdmdhl.html

[Q06] 删除列
来源：http://dali.aizwys.cn/Article/details/gt2xxkdfgbh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.tianlin.xyz/Article/details/gt2qlrsyehq.html

[Q07] 删除表
来源：http://dali.ivvv.top/Article/details/gt2vtkoersk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.feifeiyinyue.top/Article/details/gt2iblghsir.html

[Q08] 创建普通索引
来源：http://dali.gogol.net.cn/Article/details/gt2jhsdxgiz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jiagoushi.top/Article/details/gt2jixzqkht.html

[Q09] 创建唯一索引
来源：http://dali.hammf.cn/Article/details/gt2ojskaart.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhoulong.xyz/Article/details/gt2yntvwjzy.html

[Q10] 插入单行
来源：http://dali.gotoacloud.top/Article/details/gt2zfzavpfc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yj20258.top/Article/details/gt2ezidnziu.html

[Q11] 一次插入多行
来源：http://dali.fzhhl.top/Article/details/gt2ggaivugi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.quarkkingdee.top/Article/details/gt2xnnumnnu.html

[Q12] 插入后取自增 ID
来源：http://dali.hnxiangtu.top/Article/details/gt2pyyobnfd.html


<!-- 参考信息 -->