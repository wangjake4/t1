代发 wailian999

TS:   process.cwd()
来源：http://dali.yj202588.top/Article/details/gtugtkeckg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xinyue.icu/Article/details/gtdircrbyq.html

Go:   os.Getwd()
来源：http://dali.zhixingplan.top/Article/details/gtdjrdivzx.html

Ruby: Dir.pwd
来源：http://dali.iojbl.cn/Article/details/gtkroadsry.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jiagoushi.top/Article/details/gtzpvabojt.html

[M05] 设置退出码
来源：http://dali.jianghu66.top/Article/details/gtzwuajzxr.html

Py:   sys.exit(1)
来源：http://dali.zycfv.cn/Article/details/gtrzvhsqvf.html

PHP:  exit(1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjkyqzxff.html

JS:   process.exit(1)
来源：http://dali.xziqi.cn/Article/details/gtylcgydqj.html

TS:   process.exit(1)
来源：http://dali.yuxming.cn/Article/details/gtafwvugpd.html

Java: System.exit(1)
来源：http://dali.mhx1999.top/Article/details/gtruboagih.html

Go:   os.Exit(1)
来源：http://dali.wangdashe.top/Article/details/gtarjlfual.html

Ruby: exit 1
来源：http://dali.jlsjyb.cn/Article/details/gtibnraahj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jiagoushi.top/Article/details/gthhlqapuc.html

[M06] 向标准错误输出
来源：http://dali.yj20258888.top/Article/details/gtmjgrrdeb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cucudq.cn/Article/details/gtteazxfgc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.tian-w.cn/Article/details/gtagobfqmv.html

JS:   console.error("err")
来源：http://dali.zhixingplan.top/Article/details/gtufscfdue.html

TS:   console.error("err")
来源：http://dali.ppjwa.cn/Article/details/gtrmasvbkx.html

Java: System.err.println("err")
来源：http://dali.guannengcc.top/Article/details/gtksyktweg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sxryk.cn/Article/details/gttgwgprvh.html

Ruby: warn "err"
来源：http://dali.zhongyouzk.top/Article/details/gtauyovahz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shangyingyoupin.top/Article/details/gtqztclvhf.html

[M07] 判断是否为主入口
来源：http://dali.quarkkingdee.top/Article/details/gtpbccfwxr.html

Py:   if __name__ == "__main__":
来源：http://dali.xuetiantiany.cn/Article/details/gtzckvgvnt.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.nanxuanxn.top/Article/details/gtybcmjfvo.html

JS:   require.main === module
来源：http://dali.sufxvd.cn/Article/details/gtngtmchgo.html

TS:   require.main === module
来源：http://dali.yj202588.top/Article/details/gtdfqencbc.html

Java: public static void main(String[] args)
来源：http://dali.cashguo.top/Article/details/gtrpcazhjb.html

Go:   func main()
来源：http://dali.wangdashe.top/Article/details/gtkunlulqa.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.9152youxi.cn/Article/details/gtqotuwmlq.html

C#:   static void Main(string[] args)
来源：http://dali.hnxiangtu.top/Article/details/gtgdiqsokv.html

[M08] 获取系统与运行时信息
来源：http://dali.vqdsnc.cn/Article/details/gtaklwdhkq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jianghu66.top/Article/details/gtydyooegp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.feifeiyinyue.top/Article/details/gtwpqpcktm.html

JS:   process.platform;  process.version
来源：http://dali.yongpay.top/Article/details/gtialxofta.html

TS:   process.platform;  process.version
来源：http://dali.zhengqikj.top/Article/details/gtuotzpvcr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.fengsongda.top/Article/details/gtplvkudpu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.guowangkeji.top/Article/details/gtodqsqnsq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinqigufen.top/Article/details/gtvfzsdcyn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ppjwa.cn/Article/details/gtjowturtt.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtcvspyzio.html

N. 数据结构与算法
来源：http://dali.wangdashe.top/Article/details/gtolbfdsmj.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtzhvrqept.html

[N01] 二分查找（有序数组）
来源：http://dali.yanxiufei.cn/Article/details/gtorbmpada.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.c1oappe.top/Article/details/gteyxqjfwz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinqigfzy.top/Article/details/gtwaddqmrf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangdashe.top/Article/details/gtxkevgyxv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gtfyuwwpyq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hammf.cn/Article/details/gtbjgypsjn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtruhmjdce.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jianghu66.top/Article/details/gtjizwbmvb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtradovgvc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nwbrower.top/Article/details/gtqkbhrfif.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tian-w.cn/Article/details/gtifsvpdjl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.smart0.xyz/Article/details/gtalixggud.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ehwqpu.com/Article/details/gtfskjgrek.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cheryme.top/Article/details/gtfrwzbcvh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.pengpengdd.cyou/Article/details/gtbqhlafyj.html

Go:   slices.Sort(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtjuvvjoww.html

Ruby: arr.sort
来源：http://dali.pycfn.com/Article/details/gtgqpspqle.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yj20258888.top/Article/details/gtuzavodtv.html

[N03] 快速排序（分治示例）
来源：http://dali.mhx1999.top/Article/details/gtdcymtfxs.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.mhx1999.top/Article/details/gtbbjyjikc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gaohongyu789.top/Article/details/gtscxqxwiu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenjidiqi.icu/Article/details/gtwksudniv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cucudq.cn/Article/details/gtxckwqkqy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yangfankeji.com/Article/details/gtesmahhtq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cashguo.top/Article/details/gtngarymeh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sufxvd.cn/Article/details/gtciwebalz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shangyingyoupin.top/Article/details/gtjxepfpto.html

[N04] 斐波那契数列
来源：http://dali.jlsjyb.cn/Article/details/gtfdkxjpul.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yj202588.top/Article/details/gtgvlsazks.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cheryme.top/Article/details/gtxkvqbdvq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjllnzntd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.havefunace.top/Article/details/gtwxxowvly.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hysaishi.cn/Article/details/gtcjmpuleg.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.quarkkingdee.top/Article/details/gthdmwffjl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jlsjyb.cn/Article/details/gtqvjktnxd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaukzhfjr.html

[N05] 最大公约数
来源：http://dali.gaohongyu789.top/Article/details/gtcsggvdod.html

Py:   math.gcd(a, b)
来源：http://dali.316326.xyz/Article/details/gtnoclfzda.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhoulong.xyz/Article/details/gtmeagoyrt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.quarkkingdee.top/Article/details/gtbzsghzpt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhoulong.xyz/Article/details/gtdscgdqpx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jyoumei.cn/Article/details/gtwdzgzpmw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ppjwa.cn/Article/details/gtdtxgkvot.html

Ruby: a.gcd(b)
来源：http://dali.xuanzx.com/Article/details/gtqvibvmfu.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ehwqpu.com/Article/details/gtnthxkmqj.html

[N06] 判断回文字符串
来源：http://dali.bjfxy.top/Article/details/gtdphoppsk.html

Py:   s == s[::-1]
来源：http://dali.fengsongda.top/Article/details/gtjxpghznv.html

PHP:  $s === strrev($s);
来源：http://dali.hammf.cn/Article/details/gtczelvddm.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gtyuhdxpji.html

TS:   s === [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtaybgkbrb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gtygexncoq.html

Go:   // 双指针从两端比较
来源：http://dali.sxryk.cn/Article/details/gturssafdc.html

Ruby: s == s.reverse
来源：http://dali.wangdashe.top/Article/details/gtplfsgtxv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xinyue.icu/Article/details/gtfgytgmhp.html

[N07] 两数之和（返回下标）
来源：http://dali.gaohongyu789.top/Article/details/gtnqzrxzgz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.vqdsnc.cn/Article/details/gtmwkhhiku.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xylfe.cn/Article/details/gtodvbtpvz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.iojbl.cn/Article/details/gtiweffqwr.html

TS:   // 手写 Map<string, number>
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmeydgahu.html

Java: // 手写 HashMap
来源：http://dali.svipenyu.cn/Article/details/gteixdqltz.html

Go:   // 手写 map[int]int
来源：http://dali.yvedp.cn/Article/details/gtzcunesib.html

Ruby: // 手写 Hash
来源：http://dali.zhoulong.xyz/Article/details/gtwqcfjahb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yj20258888.top/Article/details/gtgmlbvlqv.html

[N08] 生成全排列
来源：http://dali.pengpengdd.cyou/Article/details/gtsjolnbsl.html

Py:   itertools.permutations(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gteqpaiccx.html

PHP:  // 手写递归交换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtblqirtym.html

JS:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gtxgwmecnv.html

TS:   // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gtyltagfnv.html

Java: // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gtkfozynfe.html

Go:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvydrnukc.html

Ruby: arr.permutation.to_a
来源：http://dali.cashguo.top/Article/details/gtymcwyuta.html

C#:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnndaywcn.html

[N09] 栈与队列
来源：http://dali.cheryme.top/Article/details/gtrzjbmyom.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xinyue.icu/Article/details/gtjlbdcluv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ydzc1.top/Article/details/gtdgttltcg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gthmbxpsod.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.sxryk.cn/Article/details/gtnkjyphqu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yanxiufei.cn/Article/details/gtldowfywv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.andypj.xyz/Article/details/gtoeltusry.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.aizwys.cn/Article/details/gtgooxrihe.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hongshengwenyu.top/Article/details/gtytihdons.html

[N10] 链表节点定义
来源：http://dali.sufxvd.cn/Article/details/gtsiuvfafy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yonumen.top/Article/details/gtwfmiglep.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.meibo888.top/Article/details/gtugmlhuoe.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.quarkkingdee.top/Article/details/gtwypktzbc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hammf.cn/Article/details/gtfmdkriqt.html

Java: class Node { int v; Node next; }
来源：http://dali.ivvv.top/Article/details/gtkeiaytch.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ivvv.top/Article/details/gttwhnftgg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shangyingyoupin.top/Article/details/gtfmnaphcg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tianlin.xyz/Article/details/gtiufziwky.html

[N11] 二叉树中序遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyngakfof.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjepvbpsz.html

PHP:  // 手写递归函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwbigqojm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zdqjudy.top/Article/details/gtjpceioll.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cdnleiting.top/Article/details/gtzfmnazfz.html

Java: // 手写递归
来源：http://dali.zycfv.cn/Article/details/gtozqhiegt.html

Go:   // 手写递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxftuykvz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gtpcndiwug.html

C#:   // 手写递归
来源：http://dali.nanxinkj.top/Article/details/gtoktifvsg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ehwqpu.com/Article/details/gtkclnfirn.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shanyushiyangtech.top/Article/details/gtobwovysz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xuetiantiany.cn/Article/details/gtexyicbli.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shzxlz.cn/Article/details/gtreakonpn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.c1oappe.top/Article/details/gtedvhcbaq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pengpengdd.cyou/Article/details/gtqisetmwv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinqigfzy.top/Article/details/gtethqiwtd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.dianchejie.cn/Article/details/gtxyoyzqan.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenjidiqi.icu/Article/details/gttjdzryok.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtmmqandqk.html

O. 并发与异步
来源：http://dali.hongshengwenyu.top/Article/details/gtbqlbxrvm.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtnsnekdoh.html

[O01] 启动一个线程
来源：http://dali.wangshuangyany.cn/Article/details/gtviovwxvp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.daria6918.cn/Article/details/gtvsromshd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhiwuduotai.top/Article/details/gtulzofkde.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hysaishi.cn/Article/details/gtgulcuvdm.html

TS:   // 同 JS
来源：http://dali.yonumen.top/Article/details/gtclbgqjwv.html

Java: new Thread(() -> f()).start()
来源：http://dali.yanxiufei.cn/Article/details/gtrnabtqzf.html

Go:   go f()
来源：http://dali.jlsjyb.cn/Article/details/gtlbkinkeo.html

Ruby: Thread.new { f }
来源：http://dali.hfpthk.cn/Article/details/gtaqhxmjco.html

C#:   Task.Run(() => F());
来源：http://dali.zdqjudy.top/Article/details/gtjabfvmkk.html

[O02] 使用线程池
来源：http://dali.meibo888.top/Article/details/gttclmttul.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xziqi.cn/Article/details/gtlqxvxbva.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hongshengwenyu.top/Article/details/gtomrvdekn.html

JS:   // worker_threads 线程池
来源：http://dali.dianchejie.cn/Article/details/gtsavorjmz.html

TS:   // worker_threads 线程池
来源：http://dali.gzhubu.top/Article/details/gtvwwggujm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.aibaodan.cn/Article/details/gtnnyrfusm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.316326.xyz/Article/details/gtpukkqkfp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.chenzaomai.com/Article/details/gthsfqngub.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.svipenyu.cn/Article/details/gtrrsyvrnt.html

[O03] 加锁保护共享数据
来源：http://dali.jiagoushi.top/Article/details/gtgjdxrcho.html

Py:   with lock: shared += 1
来源：http://dali.wangshuangyany.cn/Article/details/gtyqammovr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xziqi.cn/Article/details/gtxxtplgjr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ybcxt.top/Article/details/gtujwjvuit.html

TS:   // 同 JS
来源：http://dali.jinqigufen.top/Article/details/gtaaimjurx.html

Java: synchronized (this) { shared++; }
来源：http://dali.hysaishi.cn/Article/details/gttwbeayjs.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.0kj1m.cn/Article/details/gtpgphpyhr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.meibo888.top/Article/details/gtqzanvvrl.html

C#:   lock (gate) { shared++; }
来源：http://dali.birdmap.top/Article/details/gtebqwuqax.html

[O04] 定义异步函数并等待
来源：http://dali.chenlongwang.top/Article/details/gtttieunbf.html

Py:   async def f():⏎    await g()
来源：http://dali.havefunace.top/Article/details/gtkxrwcjet.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ivvv.top/Article/details/gtxabojqzw.html

JS:   async function f() { await g(); }
来源：http://dali.yvedp.cn/Article/details/gtthjwetzj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.snrcjt.cn/Article/details/gtlekcyzlg.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shangyingyoupin.top/Article/details/gtpdjqutju.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yuxming.cn/Article/details/gtofwplarm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ppjwa.cn/Article/details/gtkpuxhaai.html

C#:   async Task F() { await G(); }
来源：http://dali.nanxuanxn.top/Article/details/gtsbuczzks.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinghuilouyu.cn/Article/details/gtvqrbxzdh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shzxlz.cn/Article/details/gtolpxgkjk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhixingplan.top/Article/details/gtmplizxhk.html

JS:   await Promise.all(tasks)
来源：http://dali.svipenyu.cn/Article/details/gtuvvkohxq.html

TS:   await Promise.all(tasks)
来源：http://dali.zdqjudy.top/Article/details/gthlqitaov.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xuanzx.com/Article/details/gtwwicclge.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtafloaoca.html

Ruby: threads.map(&:join)
来源：http://dali.cdnleiting.top/Article/details/gtedtcjekx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cheryme.top/Article/details/gtkbuqviyd.html

[O06] 使用进程池
来源：http://dali.nanxuanxn.top/Article/details/gtpeuwhgig.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shangyingyoupin.top/Article/details/gtuoztczcr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhoulong.xyz/Article/details/gtujcjrlno.html

JS:   // child_process / cluster 模块
来源：http://dali.yj20258888.top/Article/details/gtfirgroha.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gtdcugadwr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.havefunace.top/Article/details/gtkdnliqlt.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.wangdashe.top/Article/details/gtpyvvecge.html

Ruby: // fork 块
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrfhvmsjr.html

C#:   Parallel.For
来源：http://dali.tian-w.cn/Article/details/gtrvrcgcsm.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtgondqkgy.html

P. 常用工具函数
来源：http://dali.sxryk.cn/Article/details/gtrwrrrlph.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtdmhhkctu.html

[P01] 生成 UUID
来源：http://dali.xinyue.icu/Article/details/gtigigdrtz.html

Py:   str(uuid.uuid4())
来源：http://dali.wangshuangyany.cn/Article/details/gtgvgonzvi.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.gotoacloud.top/Article/details/gtkvmowwww.html

JS:   crypto.randomUUID()
来源：http://dali.meibo888.top/Article/details/gttiokalrl.html

TS:   crypto.randomUUID()
来源：http://dali.chenzaomai.com/Article/details/gtdziwbznd.html

Java: UUID.randomUUID().toString()
来源：http://dali.sweek.top/Article/details/gtguyqxrea.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jianghu66.top/Article/details/gtopuwszte.html

Ruby: SecureRandom.uuid
来源：http://dali.yuxming.cn/Article/details/gtuprfwgrb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.chenjidiqi.icu/Article/details/gtqyivcrev.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sysykeji.top/Article/details/gtouxvxlos.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hysaishi.cn/Article/details/gtqdqykhvg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhoulong.xyz/Article/details/gtwrnjspfn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.chenjidiqi.icu/Article/details/gtcfswpndb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtizjyemtg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jqgfzy.top/Article/details/gtfqlhapzb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ybcxt.top/Article/details/gtpftebyqo.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hnqzz.top/Article/details/gtgpjjuydn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yj20258.top/Article/details/gtnjnaeeoq.html

[P03] 生成短随机字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtztjxsnfb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.nwbrower.top/Article/details/gtjojkxepw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hywenlv.cn/Article/details/gtavzuownb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jiagoushi.top/Article/details/gtgphrujwz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gogol.net.cn/Article/details/gttoavmhgc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzhmcstrh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.dianchejie.cn/Article/details/gtqzrtxsvd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtezqcynov.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.wangdashe.top/Article/details/gtzaswduhr.html

[P04] 求长度
来源：http://dali.nanxinkj.top/Article/details/gtrnnnaiwh.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xinyue.icu/Article/details/gtggoqyxvm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhoulong.xyz/Article/details/gtenchrxwv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hysaishi.cn/Article/details/gtyjkzahfs.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shangyingyoupin.top/Article/details/gtivtzgpih.html

Java: list.size();  map.size();  s.length()
来源：http://dali.tian-w.cn/Article/details/gtpdaugyip.html

Go:   len(arr);  len(m)
来源：http://dali.sufxvd.cn/Article/details/gtqmsxicup.html

Ruby: x.length;  x.size
来源：http://dali.svipenyu.cn/Article/details/gtqkvxdsse.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sufxvd.cn/Article/details/gtiqgopryj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.birdmap.top/Article/details/gtwzpupkdr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sxryk.cn/Article/details/gtxozhkezc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.iojbl.cn/Article/details/gtqurfykap.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yanxiufei.cn/Article/details/gtuzyorgot.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhengqikj.top/Article/details/gtcggmbauj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.meibo888.top/Article/details/gtziiudjxb.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jqgfzy.top/Article/details/gtvgjxuuyb.html

Ruby: a == b
来源：http://dali.pycfn.com/Article/details/gtushcjesi.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.quarkkingdee.top/Article/details/gtkgqvtsqt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yonumen.top/Article/details/gtoqhsboax.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shanyushiyangtech.top/Article/details/gteyoaxruz.html

PHP:  if (empty($x)) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtynjorfiu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.smart0.xyz/Article/details/gtgiybvkcj.html

TS:   if (x == null) {}
来源：http://dali.mhx1999.top/Article/details/gtixwhnuqa.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhengqikj.top/Article/details/gtailkcyvt.html

Go:   if x == nil {}
来源：http://dali.sufxvd.cn/Article/details/gtvguwdeyg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yj202588.top/Article/details/gtxlbnfjyx.html

C#:   if (x is null) {}
来源：http://dali.zycfv.cn/Article/details/gtkwcgfgjh.html

[P07] 防抖与节流
来源：http://dali.aibaodan.cn/Article/details/gtqiemljxu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.sysykeji.top/Article/details/gtjtoiukbr.html

PHP:  // 手写时间戳比较
来源：http://dali.cheryme.top/Article/details/gtfpabdvpt.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shangyingyoupin.top/Article/details/gtppzmydda.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.meibo888.top/Article/details/gtxphgbafa.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtwneaxsvl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.birdmap.top/Article/details/gtxxygdgam.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.gotoacloud.top/Article/details/gtwryinrmu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.snrcjt.cn/Article/details/gtnijuwxwx.html

[P08] 处理浮点精度问题
来源：http://dali.jinghuilouyu.cn/Article/details/gtoytyibih.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.quarkkingdee.top/Article/details/gtiodfcuqp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cdnleiting.top/Article/details/gtnsnvisnx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.daxiang520.top/Article/details/gtpdwjrdin.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtooonaeqs.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.havefunace.top/Article/details/gtrqmpojwc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jiagoushi.top/Article/details/gtmiutlomy.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.chenjidiqi.icu/Article/details/gtleovodvd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hfpthk.cn/Article/details/gtmigaehdc.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtjqdwdjiq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jqgufenzy.top/Article/details/gtjhkaswog.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtnrwlcqof.html

[Q01] 创建表
来源：http://dali.jyoumei.cn/Article/details/gtldndwmgn.html

CREATE TABLE users (
来源：http://dali.nwbrower.top/Article/details/gtnaejcqvi.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhiwuduotai.top/Article/details/gtlckatyuj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.c1oappe.top/Article/details/gtzmurzkau.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shangyingyoupin.top/Article/details/gtqgcuvina.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hfpthk.cn/Article/details/gtstrcqdmt.html

);
来源：http://dali.gzhubu.top/Article/details/gtkpgvfmwy.html

[Q02] 创建带外键的表
来源：http://dali.andypj.xyz/Article/details/gtqkuquruh.html

CREATE TABLE orders (
来源：http://dali.hongshengwenyu.top/Article/details/gtdnwwebts.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.0kj1m.cn/Article/details/gtbfwobiko.html

user_id INT NOT NULL,
来源：http://dali.smart0.xyz/Article/details/gtslxhecvh.html

amount DECIMAL(10, 2),
来源：http://dali.mhx1999.top/Article/details/gtiltymzdo.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yonumen.top/Article/details/gteouadmqy.html


<!-- 参考信息 -->