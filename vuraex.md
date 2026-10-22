代发 wailian999

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ppjwa.cn/Article/details/gtpinuwrqr.html

[M05] 设置退出码
来源：http://dali.haohaochexian.top/Article/details/gtazfdlioy.html

Py:   sys.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gttynibkjp.html

PHP:  exit(1);
来源：http://dali.ehwqpu.com/Article/details/gtlrrtaozr.html

JS:   process.exit(1)
来源：http://dali.hnqzz.top/Article/details/gtbwxdqkdq.html

TS:   process.exit(1)
来源：http://dali.yj20258888.top/Article/details/gtogkjfmmm.html

Java: System.exit(1)
来源：http://dali.smart0.xyz/Article/details/gtvdlhxbjj.html

Go:   os.Exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtdzfsprqk.html

Ruby: exit 1
来源：http://dali.yuanzhike.top/Article/details/gtkgmmnsig.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yonumen.top/Article/details/gtyuyakybd.html

[M06] 向标准错误输出
来源：http://dali.fzhhl.top/Article/details/gteusxgzmd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jianghu66.top/Article/details/gtdxezyjcy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sweek.top/Article/details/gtpzyoivgd.html

JS:   console.error("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwiuxthfl.html

TS:   console.error("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgnskravy.html

Java: System.err.println("err")
来源：http://dali.xuetiantiany.cn/Article/details/gtxklbdpui.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.fzhhl.top/Article/details/gtmejcpeyr.html

Ruby: warn "err"
来源：http://dali.jinqigfzy.top/Article/details/gtgxqkhizc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhoulong.xyz/Article/details/gtmoypvsho.html

[M07] 判断是否为主入口
来源：http://dali.9152youxi.cn/Article/details/gtfsothjvz.html

Py:   if __name__ == "__main__":
来源：http://dali.hfpthk.cn/Article/details/gtvhhvjvbw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.wangdashe.top/Article/details/gtlqzhqkxp.html

JS:   require.main === module
来源：http://dali.aibaodan.cn/Article/details/gtqbezggjn.html

TS:   require.main === module
来源：http://dali.9152youxi.cn/Article/details/gtumtgbtef.html

Java: public static void main(String[] args)
来源：http://dali.yuanzhike.top/Article/details/gtvytoeael.html

Go:   func main()
来源：http://dali.dashuyun.cn/Article/details/gtecpdvrot.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.316326.xyz/Article/details/gtqrioobyq.html

C#:   static void Main(string[] args)
来源：http://dali.aibaodan.cn/Article/details/gtymjxqgcn.html

[M08] 获取系统与运行时信息
来源：http://dali.haohaochexian.top/Article/details/gtaaamfdvl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.svipenyu.cn/Article/details/gtdtlojhzo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.aibaodan.cn/Article/details/gtukybjhvt.html

JS:   process.platform;  process.version
来源：http://dali.yanxiufei.cn/Article/details/gtqyzzehpz.html

TS:   process.platform;  process.version
来源：http://dali.kuanghao11.cn/Article/details/gtqypphixu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhongyouzk.top/Article/details/gtwcxaubhw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ehwqpu.com/Article/details/gtejcogawh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sufxvd.cn/Article/details/gtiygzubcf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.chenlongwang.top/Article/details/gtnrnxnjlz.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtekgtioow.html

N. 数据结构与算法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbvlotrtd.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtadjfewvl.html

[N01] 二分查找（有序数组）
来源：http://dali.cucudq.cn/Article/details/gtesenliil.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtrhmptgxq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gtrzlhyhqw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jiagoushi.top/Article/details/gtjtdgrekj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.quarkkingdee.top/Article/details/gtnlrlaehd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdntmqcqo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtoamndbyw.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hnqzz.top/Article/details/gtspxvhzns.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtcuuoxqlu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nanxinkj.top/Article/details/gttvttcqjg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cheryme.top/Article/details/gtxdwlszbw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gtevyumytn.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenjidiqi.icu/Article/details/gtbourtcut.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hysaishi.cn/Article/details/gtjecpkafa.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.snrcjt.cn/Article/details/gttovvbfzq.html

Go:   slices.Sort(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtmcsfnjcs.html

Ruby: arr.sort
来源：http://dali.9152youxi.cn/Article/details/gtfhexzuvq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jianghu66.top/Article/details/gttzjiqsay.html

[N03] 快速排序（分治示例）
来源：http://dali.chenjidiqi.icu/Article/details/gtdjkqweci.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmhrqgpot.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shangyingyoupin.top/Article/details/gtuwaxmmbm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gogol.net.cn/Article/details/gtmjfxdsvv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.havefunace.top/Article/details/gtkpbucmrm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gogol.net.cn/Article/details/gtspfibawi.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ybcxt.top/Article/details/gthtbejoos.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tianlin.xyz/Article/details/gtweolqlkr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ppjwa.cn/Article/details/gttbiczxih.html

[N04] 斐波那契数列
来源：http://dali.yj20258888.top/Article/details/gtqfwervxe.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yvedp.cn/Article/details/gtowjjcazs.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shangyingyoupin.top/Article/details/gthfinqmwa.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuanzhike.top/Article/details/gtqozywdlk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cqqwz.cn/Article/details/gtoxkbmfry.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.0kj1m.cn/Article/details/gttjditsdi.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.svipenyu.cn/Article/details/gtwpaziyho.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xinyue.icu/Article/details/gtfafelrgm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtamgnfnxv.html

[N05] 最大公约数
来源：http://dali.daria6918.cn/Article/details/gtnyseqlfc.html

Py:   math.gcd(a, b)
来源：http://dali.vqdsnc.cn/Article/details/gtfzyoiwrx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.316326.xyz/Article/details/gtyohiegnq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dashuyun.cn/Article/details/gtbmvuxtmb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkcznxrkh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.guannengcc.top/Article/details/gtqfkurcex.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.pengpengdd.cyou/Article/details/gtynoatqtp.html

Ruby: a.gcd(b)
来源：http://dali.jqgufenzy.top/Article/details/gtiddhrlsm.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.snrcjt.cn/Article/details/gtceqhyxnh.html

[N06] 判断回文字符串
来源：http://dali.cheryme.top/Article/details/gtibjbhsqg.html

Py:   s == s[::-1]
来源：http://dali.hnqzz.top/Article/details/gtkeluqesz.html

PHP:  $s === strrev($s);
来源：http://dali.ppjwa.cn/Article/details/gtasjgquxq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtjopnxviu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gthocgfiiq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hywenlv.cn/Article/details/gtpynlxafb.html

Go:   // 双指针从两端比较
来源：http://dali.chenlongwang.top/Article/details/gtycqztdla.html

Ruby: s == s.reverse
来源：http://dali.jianghu66.top/Article/details/gtmxftqgxu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.havefunace.top/Article/details/gtspuxyopp.html

[N07] 两数之和（返回下标）
来源：http://dali.gaohongyu789.top/Article/details/gtzlpcjdvt.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.nwbrower.top/Article/details/gtyebdjmip.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shuidangran.top/Article/details/gtgwulbavf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxdrkqond.html

TS:   // 手写 Map<string, number>
来源：http://dali.xziqi.cn/Article/details/gtniejegju.html

Java: // 手写 HashMap
来源：http://dali.hywenlv.cn/Article/details/gtmodymxgm.html

Go:   // 手写 map[int]int
来源：http://dali.mhx1999.top/Article/details/gtpexxkjpl.html

Ruby: // 手写 Hash
来源：http://dali.yj202588.top/Article/details/gthfjpdfau.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinghuilouyu.cn/Article/details/gtpiynebwr.html

[N08] 生成全排列
来源：http://dali.xuetiantiany.cn/Article/details/gtytbmdemh.html

Py:   itertools.permutations(arr)
来源：http://dali.ppjwa.cn/Article/details/gtodpmzhhf.html

PHP:  // 手写递归交换
来源：http://dali.zycfv.cn/Article/details/gtoitgiqep.html

JS:   // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gtssngzath.html

TS:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtiuftfpew.html

Java: // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gtulwmxdpe.html

Go:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gtpkmsqzsq.html

Ruby: arr.permutation.to_a
来源：http://dali.svipenyu.cn/Article/details/gtqibwlxvj.html

C#:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gttdvvxsjm.html

[N09] 栈与队列
来源：http://dali.zhoulong.xyz/Article/details/gtxwcqwvtc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gzhubu.top/Article/details/gtgodvedzh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttokkrkkb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.chenzaomai.com/Article/details/gtwzwiggqy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.chenlongwang.top/Article/details/gtwlwauqnv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cucudq.cn/Article/details/gtddrpihbr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.vqdsnc.cn/Article/details/gtsazgwnyw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbmbhbaaf.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxfbsgegv.html

[N10] 链表节点定义
来源：http://dali.chenzaomai.com/Article/details/gtgasxdtbi.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.0kj1m.cn/Article/details/gtvgifbefj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiynhdeus.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jiagoushi.top/Article/details/gtpxglxqtu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.nwbrower.top/Article/details/gtrojbgmae.html

Java: class Node { int v; Node next; }
来源：http://dali.fzhhl.top/Article/details/gtshtcdsrc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sxryk.cn/Article/details/gtzxkzrnuv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jianghu66.top/Article/details/gtakytqksb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xylfe.cn/Article/details/gtakrbiqnu.html

[N11] 二叉树中序遍历
来源：http://dali.zdqjudy.top/Article/details/gtakqfewnx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.dianchejie.cn/Article/details/gtybzpvbum.html

PHP:  // 手写递归函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdryohdta.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jiagoushi.top/Article/details/gtjaigkuha.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.kuanghao11.cn/Article/details/gteifgbvme.html

Java: // 手写递归
来源：http://dali.zhoulong.xyz/Article/details/gtjwaqurmp.html

Go:   // 手写递归
来源：http://dali.aibaodan.cn/Article/details/gtwyjigtch.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdgbbspax.html

C#:   // 手写递归
来源：http://dali.sxryk.cn/Article/details/gtkxhdpxjk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.316326.xyz/Article/details/gtnagfbxny.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ybcxt.top/Article/details/gtvmiluwsk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.0kj1m.cn/Article/details/gtsrtwsjaq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hywenlv.cn/Article/details/gttlxpjbok.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aizwys.cn/Article/details/gtgurvyyxz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hywenlv.cn/Article/details/gtonidoulm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ydzc1.top/Article/details/gteundweyn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gzhubu.top/Article/details/gtxcvqmsxt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hysaishi.cn/Article/details/gtvaravowj.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gteqolxfio.html

O. 并发与异步
来源：http://dali.yueranfly.top/Article/details/gtxyfvofyx.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtfemtvque.html

[O01] 启动一个线程
来源：http://dali.c1oappe.top/Article/details/gtrvybbrll.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdajscysg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvehlcesi.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.pycfn.com/Article/details/gtgupgygmz.html

TS:   // 同 JS
来源：http://dali.aibaodan.cn/Article/details/gtjhnkqolp.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhongyouzk.top/Article/details/gtjdtupadf.html

Go:   go f()
来源：http://dali.havefunace.top/Article/details/gtvmtacrgz.html

Ruby: Thread.new { f }
来源：http://dali.haohaochexian.top/Article/details/gtxgciuwtb.html

C#:   Task.Run(() => F());
来源：http://dali.sufxvd.cn/Article/details/gtpinmfwyj.html

[O02] 使用线程池
来源：http://dali.zhengqikj.top/Article/details/gtgsczzsac.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shzxlz.cn/Article/details/gtgnnqycvm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.0kj1m.cn/Article/details/gttmtlteyq.html

JS:   // worker_threads 线程池
来源：http://dali.daria6918.cn/Article/details/gtojnamleg.html

TS:   // worker_threads 线程池
来源：http://dali.gzhubu.top/Article/details/gtlfarkmjg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cashguo.top/Article/details/gtmymdbvov.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yvedp.cn/Article/details/gtvkdoumfp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yj20258888.top/Article/details/gtvhlnkqtu.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hywenlv.cn/Article/details/gtbwrtvefe.html

[O03] 加锁保护共享数据
来源：http://dali.haohaochexian.top/Article/details/gtmwafriab.html

Py:   with lock: shared += 1
来源：http://dali.jyoumei.cn/Article/details/gtttvajhqt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.nanxuanxn.top/Article/details/gtluwejhgw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xziqi.cn/Article/details/gtpmwmoonx.html

TS:   // 同 JS
来源：http://dali.vqdsnc.cn/Article/details/gtcxqpozlv.html

Java: synchronized (this) { shared++; }
来源：http://dali.shangyingyoupin.top/Article/details/gtykhikxzm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sweek.top/Article/details/gtwknnotlc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hammf.cn/Article/details/gtwpbhsxhm.html

C#:   lock (gate) { shared++; }
来源：http://dali.hnxiangtu.top/Article/details/gtpnefqlcz.html

[O04] 定义异步函数并等待
来源：http://dali.nanxuanxn.top/Article/details/gtseqdmiyp.html

Py:   async def f():⏎    await g()
来源：http://dali.fengsongda.top/Article/details/gtptrmjkdu.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yangfankeji.com/Article/details/gtbvyidaiw.html

JS:   async function f() { await g(); }
来源：http://dali.yonumen.top/Article/details/gtnqchyogv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.kuanghao11.cn/Article/details/gtvdcehkwe.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinghuilouyu.cn/Article/details/gtiajymspb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hysaishi.cn/Article/details/gtgbwjcumj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shanyushiyangtech.top/Article/details/gterktqhft.html

C#:   async Task F() { await G(); }
来源：http://dali.tanke756.top/Article/details/gtxdzolbli.html

[O05] 并发执行并等待全部完成
来源：http://dali.hongshengwenyu.top/Article/details/gtijaiclmj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.wangdashe.top/Article/details/gttfukwgnv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.9152youxi.cn/Article/details/gtyowvsjjy.html

JS:   await Promise.all(tasks)
来源：http://dali.ivvv.top/Article/details/gtlevapnjw.html

TS:   await Promise.all(tasks)
来源：http://dali.yongpay.top/Article/details/gtdwhuovty.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.tanke756.top/Article/details/gtxpghrchj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.nwbrower.top/Article/details/gthzynshha.html

Ruby: threads.map(&:join)
来源：http://dali.daxiang520.top/Article/details/gtkkvrewdo.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xuetiantiany.cn/Article/details/gtisyxdlyx.html

[O06] 使用进程池
来源：http://dali.redwolf501.top/Article/details/gtxmudalcm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ybcxt.top/Article/details/gtthyrojre.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.chenlongwang.top/Article/details/gtdemrbjeo.html

JS:   // child_process / cluster 模块
来源：http://dali.yj20258888.top/Article/details/gtepfehkop.html

TS:   // child_process / cluster 模块
来源：http://dali.kuanghao11.cn/Article/details/gtnotkuvku.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ybcxt.top/Article/details/gtonmnpocz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yongpay.top/Article/details/gtdnffvaaf.html

Ruby: // fork 块
来源：http://dali.jqgfzy.top/Article/details/gtzruefovh.html

C#:   Parallel.For
来源：http://dali.ehwqpu.com/Article/details/gtvhpwdkbz.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtvgzsphtm.html

P. 常用工具函数
来源：http://dali.ivvv.top/Article/details/gtztmccmlx.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtwoauvdaw.html

[P01] 生成 UUID
来源：http://dali.cqqwz.cn/Article/details/gtvukaztft.html

Py:   str(uuid.uuid4())
来源：http://dali.jqgfzy.top/Article/details/gtfegxyzzq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tanke756.top/Article/details/gttiypoxtl.html

JS:   crypto.randomUUID()
来源：http://dali.zdqjudy.top/Article/details/gtbvfgqzme.html

TS:   crypto.randomUUID()
来源：http://dali.andypj.xyz/Article/details/gtbflcmrdj.html

Java: UUID.randomUUID().toString()
来源：http://dali.fzhhl.top/Article/details/gtafaskirf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.daxiang520.top/Article/details/gteoytvxzg.html

Ruby: SecureRandom.uuid
来源：http://dali.svipenyu.cn/Article/details/gtxnoylnvv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.chenlongwang.top/Article/details/gtcslxzbgo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xylfe.cn/Article/details/gthohczqeq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jiagoushi.top/Article/details/gtgicqxfbb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ydzc1.top/Article/details/gtwpesqjdw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shanyushiyangtech.top/Article/details/gtmbleertl.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.aibaodan.cn/Article/details/gtubohcfhu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.guannengcc.top/Article/details/gtvnaksevd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cashguo.top/Article/details/gttwbxeuny.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmmpzcusj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtomnnhvqr.html

[P03] 生成短随机字符串
来源：http://dali.sufxvd.cn/Article/details/gtoyfichek.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hnqzz.top/Article/details/gttmznppej.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.chenzaomai.com/Article/details/gtjvcwlbch.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtnswfruhq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258.top/Article/details/gtwoibkbpx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtridfldov.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.aibaodan.cn/Article/details/gtrksmwvmr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.meibo888.top/Article/details/gtkoemqtef.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.0kj1m.cn/Article/details/gtcdihsfma.html

[P04] 求长度
来源：http://dali.svipenyu.cn/Article/details/gtqlladyqw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenjidiqi.icu/Article/details/gtmtaiwxly.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gtvmrvykad.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tianlin.xyz/Article/details/gtajrdnrfn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhongyouzk.top/Article/details/gtouyqtira.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cashguo.top/Article/details/gtsosbuvtv.html

Go:   len(arr);  len(m)
来源：http://dali.feifeiyinyue.top/Article/details/gthwmefzme.html

Ruby: x.length;  x.size
来源：http://dali.aizwys.cn/Article/details/gtvimbhgny.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sweek.top/Article/details/gtnzpjsogs.html

[P05] 判断两个对象内容是否相等
来源：http://dali.andypj.xyz/Article/details/gtzutawcsy.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sysykeji.top/Article/details/gtbvtbkvxp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xinyue.icu/Article/details/gtwcqxhjqb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gaohongyu789.top/Article/details/gtuhrccbcv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xylfe.cn/Article/details/gtwctsyhef.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shzxlz.cn/Article/details/gtstnkajiv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hongshengwenyu.top/Article/details/gtpcrtoiws.html

Ruby: a == b
来源：http://dali.fzhhl.top/Article/details/gtwfzfzysj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cdnleiting.top/Article/details/gtxkbgxaas.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ybcxt.top/Article/details/gtqvbftehg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shanyushiyangkeji.top/Article/details/gthqmacxui.html

PHP:  if (empty($x)) {}
来源：http://dali.nanxinkj.top/Article/details/gtlcclxopa.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yueranfly.top/Article/details/gtnnpzujru.html

TS:   if (x == null) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcqwvhthn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.tanke756.top/Article/details/gtaxzakpni.html

Go:   if x == nil {}
来源：http://dali.xinyue.icu/Article/details/gtytwyjknm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sxryk.cn/Article/details/gtjcbvahcf.html

C#:   if (x is null) {}
来源：http://dali.iojbl.cn/Article/details/gtftxljkcl.html

[P07] 防抖与节流
来源：http://dali.gaohongyu789.top/Article/details/gtzwatbdeq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yangfankeji.com/Article/details/gtmdfwairt.html

PHP:  // 手写时间戳比较
来源：http://dali.sweek.top/Article/details/gtbxtiapqn.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgufenzy.top/Article/details/gteuykerap.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvsnlnukw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.kuanghao11.cn/Article/details/gtbyyubgbv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.birdmap.top/Article/details/gtckffndjb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gtyjanhdvj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.quarkkingdee.top/Article/details/gtwlxrtrpq.html

[P08] 处理浮点精度问题
来源：http://dali.xziqi.cn/Article/details/gtvfpeveaa.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yongpay.top/Article/details/gtyrrkctyb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cqqwz.cn/Article/details/gtfydumjwu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shangyingyoupin.top/Article/details/gtxgtjjmhu.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ehwqpu.com/Article/details/gtvegasbvo.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yj202588.top/Article/details/gtoszkuxns.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.0kj1m.cn/Article/details/gtbmanblsz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jlsjyb.cn/Article/details/gtgvwomtzu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yongpay.top/Article/details/gtzjyccgci.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gthvibjlfq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yangfankeji.com/Article/details/gtfpnjytfp.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtputtcbip.html

[Q01] 创建表
来源：http://dali.sufxvd.cn/Article/details/gtupfaamin.html

CREATE TABLE users (
来源：http://dali.zhiwuduotai.top/Article/details/gtptgmyjqd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.quarkkingdee.top/Article/details/gtsquqjnlb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cucudq.cn/Article/details/gtckquoevu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gotoacloud.top/Article/details/gtlsigogjd.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jyoumei.cn/Article/details/gtpqybbion.html

);
来源：http://dali.xinyue.icu/Article/details/gtwzokqugw.html

[Q02] 创建带外键的表
来源：http://dali.hnqzz.top/Article/details/gttkumotiy.html

CREATE TABLE orders (
来源：http://dali.ppjwa.cn/Article/details/gtbmloqlfy.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgfzy.top/Article/details/gtkmigaebo.html

user_id INT NOT NULL,
来源：http://dali.zdqjudy.top/Article/details/gtcnobrolv.html

amount DECIMAL(10, 2),
来源：http://dali.kuanghao11.cn/Article/details/gtebgyljqf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hongshengwenyu.top/Article/details/gtuvpjhdcc.html

);
来源：http://dali.sufxvd.cn/Article/details/gtcbgkrotp.html

[Q03] 增加列
来源：http://dali.gaohongyu789.top/Article/details/gtwbhytzen.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yangfankeji.com/Article/details/gtrznxggtu.html

[Q04] 修改列类型
来源：http://dali.cdnleiting.top/Article/details/gtmozuaxeu.html


<!-- 参考信息 -->