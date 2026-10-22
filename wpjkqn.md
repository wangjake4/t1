代发 wailian999

[M04] 获取当前工作目录
来源：http://dali.chenlongwang.top/Article/details/gtlaxxxmkh.html

Py:   os.getcwd()
来源：http://dali.nanxinkj.top/Article/details/gtzuryuhyp.html

PHP:  getcwd();
来源：http://dali.shzxlz.cn/Article/details/gtiausmqdd.html

JS:   process.cwd()
来源：http://dali.tianlin.xyz/Article/details/gtfdtkgjtx.html

TS:   process.cwd()
来源：http://dali.mhx1999.top/Article/details/gtyxcjirmm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.quarkkingdee.top/Article/details/gtgplqzevd.html

Go:   os.Getwd()
来源：http://dali.cheryme.top/Article/details/gtwocfjdkf.html

Ruby: Dir.pwd
来源：http://dali.nwbrower.top/Article/details/gtsdfrvigm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.9152youxi.cn/Article/details/gtazvzttyj.html

[M05] 设置退出码
来源：http://dali.c1oappe.top/Article/details/gtduowujjm.html

Py:   sys.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtcsemzaql.html

PHP:  exit(1);
来源：http://dali.gzhubu.top/Article/details/gtszkpwqxm.html

JS:   process.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gttcvmwapu.html

TS:   process.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtywjupcrg.html

Java: System.exit(1)
来源：http://dali.daxiang520.top/Article/details/gtvtmiztks.html

Go:   os.Exit(1)
来源：http://dali.shuidangran.top/Article/details/gturmxewdr.html

Ruby: exit 1
来源：http://dali.jlsjyb.cn/Article/details/gtducfazuv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xziqi.cn/Article/details/gtezsihhxc.html

[M06] 向标准错误输出
来源：http://dali.wangshuangyany.cn/Article/details/gtslhhrrez.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yongpay.top/Article/details/gtuzthdjam.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.tian-w.cn/Article/details/gtzmebsyme.html

JS:   console.error("err")
来源：http://dali.jqgfzy.top/Article/details/gtdoceivzf.html

TS:   console.error("err")
来源：http://dali.xinyue.icu/Article/details/gtrbwmpcwz.html

Java: System.err.println("err")
来源：http://dali.xinyue.icu/Article/details/gtagwydkzf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.chenlongwang.top/Article/details/gtszovhlsq.html

Ruby: warn "err"
来源：http://dali.birdmap.top/Article/details/gtctvfpelt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shangyingyoupin.top/Article/details/gthtlnoxgh.html

[M07] 判断是否为主入口
来源：http://dali.jianghu66.top/Article/details/gtxqlgfuje.html

Py:   if __name__ == "__main__":
来源：http://dali.chenzaomai.com/Article/details/gtzritcdmj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.birdmap.top/Article/details/gtgzfmzfqc.html

JS:   require.main === module
来源：http://dali.gogol.net.cn/Article/details/gtsruicscr.html

TS:   require.main === module
来源：http://dali.andypj.xyz/Article/details/gtyoysqdgc.html

Java: public static void main(String[] args)
来源：http://dali.meibo888.top/Article/details/gtaujanzri.html

Go:   func main()
来源：http://dali.sysykeji.top/Article/details/gtyiulqcmw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.316326.xyz/Article/details/gtjedbdbdk.html

C#:   static void Main(string[] args)
来源：http://dali.yuanzhike.top/Article/details/gtsxbjhrnw.html

[M08] 获取系统与运行时信息
来源：http://dali.xuanzx.com/Article/details/gtnamdxepo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.quarkkingdee.top/Article/details/gtfgcurrln.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hywenlv.cn/Article/details/gtnqltdigk.html

JS:   process.platform;  process.version
来源：http://dali.wangshuangyany.cn/Article/details/gtogzgrznp.html

TS:   process.platform;  process.version
来源：http://dali.pycfn.com/Article/details/gtwesrtldz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shuidangran.top/Article/details/gtwfdkfpbb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xuetiantiany.cn/Article/details/gtyfgwnbln.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ivvv.top/Article/details/gtujscxbwt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hysaishi.cn/Article/details/gtbplmivax.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtfhvmettp.html

N. 数据结构与算法
来源：http://dali.hnqzz.top/Article/details/gtffejcmbq.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtqyweuysx.html

[N01] 二分查找（有序数组）
来源：http://dali.daxiang520.top/Article/details/gtvhciqsqx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.meibo888.top/Article/details/gtljrcxezj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shuidangran.top/Article/details/gtlzxhklla.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gzhubu.top/Article/details/gtnretnfsw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yongpay.top/Article/details/gtwnkafdgq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtvrtuegcc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gtihcsyfpe.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.tian-w.cn/Article/details/gtltaqqisz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtvnixcuxc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.fzhhl.top/Article/details/gtavrjkjeg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.9152youxi.cn/Article/details/gtlllnonpy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zycfv.cn/Article/details/gtdhqnehny.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jianghu66.top/Article/details/gtkgnpqldh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.quarkkingdee.top/Article/details/gtdhyfxnxk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.aibaodan.cn/Article/details/gtkovivgmy.html

Go:   slices.Sort(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtsjbwxddc.html

Ruby: arr.sort
来源：http://dali.xylfe.cn/Article/details/gtfjcbcyje.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.316326.xyz/Article/details/gtqhuwuobw.html

[N03] 快速排序（分治示例）
来源：http://dali.ppjwa.cn/Article/details/gtjeersutn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.snrcjt.cn/Article/details/gtvhsqeikd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.kuanghao11.cn/Article/details/gtpsphgkcr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dashuyun.cn/Article/details/gtjvfqkyek.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pycfn.com/Article/details/gtzgwsykiy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.9152youxi.cn/Article/details/gtyuwojyps.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jqgufenzy.top/Article/details/gtwaavnjnv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhengqikj.top/Article/details/gtjivomkge.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.meibo888.top/Article/details/gtmrezcqul.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gtlknzanim.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.guannengcc.top/Article/details/gthixlhtnn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhixingplan.top/Article/details/gtsyqrzfsl.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzdqstnzd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guannengcc.top/Article/details/gtnixxivro.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmareoupb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.bjfxy.top/Article/details/gthutuuzop.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cqqwz.cn/Article/details/gtldklzqgj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sufxvd.cn/Article/details/gttbkhueym.html

[N05] 最大公约数
来源：http://dali.nwbrower.top/Article/details/gtptcblqst.html

Py:   math.gcd(a, b)
来源：http://dali.xziqi.cn/Article/details/gtlaqmmbya.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.snrcjt.cn/Article/details/gtyookaeam.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtugbosxka.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jiagoushi.top/Article/details/gtziamhasa.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hywenlv.cn/Article/details/gtrsksmhar.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.9152youxi.cn/Article/details/gtvsexfrmc.html

Ruby: a.gcd(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtccdmetaz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.havefunace.top/Article/details/gtrknzplsj.html

[N06] 判断回文字符串
来源：http://dali.gzhubu.top/Article/details/gtaklftsog.html

Py:   s == s[::-1]
来源：http://dali.yanxiufei.cn/Article/details/gtwrpaegjx.html

PHP:  $s === strrev($s);
来源：http://dali.jlsjyb.cn/Article/details/gtkcaprtyd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gtvgyemfbq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gtlwqcdjlj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.dianchejie.cn/Article/details/gthvnjshtx.html

Go:   // 双指针从两端比较
来源：http://dali.aizwys.cn/Article/details/gtmwcmysgn.html

Ruby: s == s.reverse
来源：http://dali.hnxiangtu.top/Article/details/gtlrazcizj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.haohaochexian.top/Article/details/gtuzmgzaot.html

[N07] 两数之和（返回下标）
来源：http://dali.zycfv.cn/Article/details/gtkhcbprhd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.kuanghao11.cn/Article/details/gtnkybkgas.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhongyouzk.top/Article/details/gtwwlozzpd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jqgfzy.top/Article/details/gtchrsjowb.html

TS:   // 手写 Map<string, number>
来源：http://dali.andypj.xyz/Article/details/gtpzpeoouf.html

Java: // 手写 HashMap
来源：http://dali.snrcjt.cn/Article/details/gtiwcnomhv.html

Go:   // 手写 map[int]int
来源：http://dali.sweek.top/Article/details/gthbvapbwd.html

Ruby: // 手写 Hash
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrraouont.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ppjwa.cn/Article/details/gtjzznhbws.html

[N08] 生成全排列
来源：http://dali.zhiwuduotai.top/Article/details/gtbmzhkjfu.html

Py:   itertools.permutations(arr)
来源：http://dali.c1oappe.top/Article/details/gtlceoqfre.html

PHP:  // 手写递归交换
来源：http://dali.snrcjt.cn/Article/details/gtieqbrfvb.html

JS:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtlbheikgo.html

TS:   // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gtkaboemaj.html

Java: // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gteffkxohw.html

Go:   // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gtptzjyrth.html

Ruby: arr.permutation.to_a
来源：http://dali.daxiang520.top/Article/details/gteacdzrmf.html

C#:   // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gtxbdtovtj.html

[N09] 栈与队列
来源：http://dali.yonumen.top/Article/details/gtmogednym.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.birdmap.top/Article/details/gtlwkgftjh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.snrcjt.cn/Article/details/gtxorrcezd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yj202588.top/Article/details/gttxmknsva.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.fzhhl.top/Article/details/gtkpnwibko.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.snrcjt.cn/Article/details/gtzkjfpppd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.iojbl.cn/Article/details/gtmejelwzj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.pycfn.com/Article/details/gtcsofqoaw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.iojbl.cn/Article/details/gtzuxqfkch.html

[N10] 链表节点定义
来源：http://dali.zhiwuduotai.top/Article/details/gtkderorub.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.9152youxi.cn/Article/details/gtkclvvfwm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jiagoushi.top/Article/details/gtnougpuan.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yuanzhike.top/Article/details/gtlzinbowt.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.nwbrower.top/Article/details/gtbqrqzjff.html

Java: class Node { int v; Node next; }
来源：http://dali.tian-w.cn/Article/details/gtxkuphsbn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cheryme.top/Article/details/gtqhuuexuf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.aibaodan.cn/Article/details/gtdnynxisg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hywenlv.cn/Article/details/gtqikgggol.html

[N11] 二叉树中序遍历
来源：http://dali.svipenyu.cn/Article/details/gtgtqphlyg.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hammf.cn/Article/details/gtshqbnplw.html

PHP:  // 手写递归函数
来源：http://dali.sufxvd.cn/Article/details/gtnzasdtpu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cheryme.top/Article/details/gtnmfeblbg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.9152youxi.cn/Article/details/gtelbavork.html

Java: // 手写递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtyunjxktu.html

Go:   // 手写递归
来源：http://dali.zhengqikj.top/Article/details/gtckfehypb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gotoacloud.top/Article/details/gtvxmyqzoo.html

C#:   // 手写递归
来源：http://dali.fengsongda.top/Article/details/gtauzugpnh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.316326.xyz/Article/details/gtyzhkuzvk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhengqikj.top/Article/details/gtcnijcfyd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.aizwys.cn/Article/details/gtruaentlm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.feifeiyinyue.top/Article/details/gtzqezjwsm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tianlin.xyz/Article/details/gthudtmuba.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ybcxt.top/Article/details/gtdhvclnzx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yvedp.cn/Article/details/gtwlagbbrq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.daxiang520.top/Article/details/gtpbfvvtwg.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sweek.top/Article/details/gthbgexglz.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtekwhrlhq.html

O. 并发与异步
来源：http://dali.yonumen.top/Article/details/gthwmkwsfr.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtyeqqtmev.html

[O01] 启动一个线程
来源：http://dali.havefunace.top/Article/details/gtsxfqnmpq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jinqigufen.top/Article/details/gtxmddosca.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.feifeiyinyue.top/Article/details/gtcecmyqky.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xziqi.cn/Article/details/gtctzfvoul.html

TS:   // 同 JS
来源：http://dali.aizwys.cn/Article/details/gtlrpvfvcp.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhongyouzk.top/Article/details/gtgkxxsjtb.html

Go:   go f()
来源：http://dali.smart0.xyz/Article/details/gtzxlhzxgw.html

Ruby: Thread.new { f }
来源：http://dali.havefunace.top/Article/details/gthidskklq.html

C#:   Task.Run(() => F());
来源：http://dali.shuidangran.top/Article/details/gthhuvjisk.html

[O02] 使用线程池
来源：http://dali.chenjidiqi.icu/Article/details/gtrnxiaxcy.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yanxiufei.cn/Article/details/gtwsrsahzo.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ehwqpu.com/Article/details/gtbjhkrggy.html

JS:   // worker_threads 线程池
来源：http://dali.zhiwuduotai.top/Article/details/gttenupqah.html

TS:   // worker_threads 线程池
来源：http://dali.0kj1m.cn/Article/details/gtdtehbhwd.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zycfv.cn/Article/details/gthnmsesuw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.mhx1999.top/Article/details/gtypfpzcof.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xinyue.icu/Article/details/gtquealhja.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.meibo888.top/Article/details/gtjvllfmyr.html

[O03] 加锁保护共享数据
来源：http://dali.jinghuilouyu.cn/Article/details/gtezuxhetp.html

Py:   with lock: shared += 1
来源：http://dali.zdqjudy.top/Article/details/gtvlknrnqp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.nanxinkj.top/Article/details/gtnzbsdagz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shanyushiyangtech.top/Article/details/gtkaqstwmf.html

TS:   // 同 JS
来源：http://dali.tianlin.xyz/Article/details/gtqdtdsaet.html

Java: synchronized (this) { shared++; }
来源：http://dali.havefunace.top/Article/details/gtpxkkiiry.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.feifeiyinyue.top/Article/details/gtxzmitwyj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xziqi.cn/Article/details/gtywvoptvi.html

C#:   lock (gate) { shared++; }
来源：http://dali.tianlin.xyz/Article/details/gtxqcmvhfa.html

[O04] 定义异步函数并等待
来源：http://dali.hywenlv.cn/Article/details/gtatnmbhwj.html

Py:   async def f():⏎    await g()
来源：http://dali.daria6918.cn/Article/details/gtwabhdfhl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhoulong.xyz/Article/details/gtmzihdkgk.html

JS:   async function f() { await g(); }
来源：http://dali.cucudq.cn/Article/details/gttvesfugb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.tianlin.xyz/Article/details/gtzynnqfzx.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.dianchejie.cn/Article/details/gtwxiucpel.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.meibo888.top/Article/details/gtpfyyikdw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhoulong.xyz/Article/details/gtqqlzzeci.html

C#:   async Task F() { await G(); }
来源：http://dali.xuetiantiany.cn/Article/details/gttlkbcgee.html

[O05] 并发执行并等待全部完成
来源：http://dali.yvedp.cn/Article/details/gtkajyjxhc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.pengpengdd.cyou/Article/details/gtlvxkewzv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yueranfly.top/Article/details/gtypkajqoa.html

JS:   await Promise.all(tasks)
来源：http://dali.aizwys.cn/Article/details/gtaycaulss.html

TS:   await Promise.all(tasks)
来源：http://dali.sxryk.cn/Article/details/gtosnhspqo.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jiagoushi.top/Article/details/gtfcqtzjje.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.daria6918.cn/Article/details/gtjyiglpqt.html

Ruby: threads.map(&:join)
来源：http://dali.bjfxy.top/Article/details/gtlhsixint.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.wangdashe.top/Article/details/gttjtrwcih.html

[O06] 使用进程池
来源：http://dali.xylfe.cn/Article/details/gtlatwmcoc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.tian-w.cn/Article/details/gtvvkpsslb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.daria6918.cn/Article/details/gtfhdimdmx.html

JS:   // child_process / cluster 模块
来源：http://dali.guannengcc.top/Article/details/gtanldnavp.html

TS:   // child_process / cluster 模块
来源：http://dali.haohaochexian.top/Article/details/gtrdgujdxv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gtwotczirr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.guowangkeji.top/Article/details/gtifvehraf.html

Ruby: // fork 块
来源：http://dali.zhixingplan.top/Article/details/gtwvtwmnbs.html

C#:   Parallel.For
来源：http://dali.hnxiangtu.top/Article/details/gtmwdbgwbx.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtbtalgyqi.html

P. 常用工具函数
来源：http://dali.cdnleiting.top/Article/details/gtwxwxgnpe.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtznhzgpbb.html

[P01] 生成 UUID
来源：http://dali.chenzaomai.com/Article/details/gtybtxkupi.html

Py:   str(uuid.uuid4())
来源：http://dali.ydzc1.top/Article/details/gtrhkgqifi.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hywenlv.cn/Article/details/gthxfrimdr.html

JS:   crypto.randomUUID()
来源：http://dali.gaohongyu789.top/Article/details/gtvxqlpdxw.html

TS:   crypto.randomUUID()
来源：http://dali.316326.xyz/Article/details/gtsygojkso.html

Java: UUID.randomUUID().toString()
来源：http://dali.haohaochexian.top/Article/details/gtkmoktyyr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yongpay.top/Article/details/gtmczqcezy.html

Ruby: SecureRandom.uuid
来源：http://dali.pengpengdd.cyou/Article/details/gtjzstzbpw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.mhx1999.top/Article/details/gtoqjaptyr.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jqgufenzy.top/Article/details/gtgaruwbkg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hnxiangtu.top/Article/details/gtigwzsnwz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.fengsongda.top/Article/details/gtiqzzrxxz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.smart0.xyz/Article/details/gteqoiqore.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.mhx1999.top/Article/details/gtfwwbjfnz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.tian-w.cn/Article/details/gtdcdsnazb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhongyouzk.top/Article/details/gtlhdhgohy.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yuanzhike.top/Article/details/gtoqgrexsf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.bjfxy.top/Article/details/gtjjhnrdaq.html

[P03] 生成短随机字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzpxowaxl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.wangdashe.top/Article/details/gttsidrxhj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.snrcjt.cn/Article/details/gtvpxviykf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sysykeji.top/Article/details/gtwgirzjav.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.guannengcc.top/Article/details/gttnulrpdy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtmokwzfqn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cdnleiting.top/Article/details/gtincarorr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gtrsoezoqg.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.kuanghao11.cn/Article/details/gtpexqokzm.html

[P04] 求长度
来源：http://dali.zhongyouzk.top/Article/details/gtzwzroznv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.pycfn.com/Article/details/gtbrtcmhxg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.havefunace.top/Article/details/gtivroltby.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.vqdsnc.cn/Article/details/gtgeuoexgl.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xuanzx.com/Article/details/gttomkdbfs.html

Java: list.size();  map.size();  s.length()
来源：http://dali.mhx1999.top/Article/details/gtfmsouuyp.html

Go:   len(arr);  len(m)
来源：http://dali.0kj1m.cn/Article/details/gtmmntgtux.html

Ruby: x.length;  x.size
来源：http://dali.xuetiantiany.cn/Article/details/gtehezebga.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.fzhhl.top/Article/details/gtyxoqjtlj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yueranfly.top/Article/details/gtdisaydnl.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yonumen.top/Article/details/gtcmcmewgk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gotoacloud.top/Article/details/gtnynymvzd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbkeyreeh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hnqzz.top/Article/details/gtaggvlgps.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yvedp.cn/Article/details/gtmmbasaeh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzuymqfgh.html

Ruby: a == b
来源：http://dali.wangdashe.top/Article/details/gtbzinqnme.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.nwbrower.top/Article/details/gtqmfwovrk.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.dashuyun.cn/Article/details/gtkuiymhrd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjbmhxsfb.html

PHP:  if (empty($x)) {}
来源：http://dali.yuanzhike.top/Article/details/gtnvepgsua.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shuidangran.top/Article/details/gtqjbxhyuh.html

TS:   if (x == null) {}
来源：http://dali.ivvv.top/Article/details/gtcvgaanyo.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.wangshuangyany.cn/Article/details/gthinbcqof.html

Go:   if x == nil {}
来源：http://dali.bjfxy.top/Article/details/gtoxrrqdgn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sxryk.cn/Article/details/gtlldhfuhi.html

C#:   if (x is null) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtxuoiphez.html

[P07] 防抖与节流
来源：http://dali.yuxming.cn/Article/details/gtsfsjfovu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhaomingkeji.xyz/Article/details/gtavmhopjc.html

PHP:  // 手写时间戳比较
来源：http://dali.sweek.top/Article/details/gtdofyjpne.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xinyue.icu/Article/details/gtyjmyetem.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoqmnwwgj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jqgfzy.top/Article/details/gtxubjwudy.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cucudq.cn/Article/details/gtoyovmzec.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.gogol.net.cn/Article/details/gtbmwopfgl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.nanxinkj.top/Article/details/gtynwdjclg.html

[P08] 处理浮点精度问题
来源：http://dali.yangfankeji.com/Article/details/gtgvwpaues.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xziqi.cn/Article/details/gtgoacrgln.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.smart0.xyz/Article/details/gtbxcwkcgh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhixingplan.top/Article/details/gtncdanfbp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hnxiangtu.top/Article/details/gtkmmogqbg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xuanzx.com/Article/details/gtcvkdjiev.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xuanzx.com/Article/details/gthjfpiyrg.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqlpydham.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xuetiantiany.cn/Article/details/gtsslxmdsc.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtbphrompj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.pycfn.com/Article/details/gtrfmhxnip.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtpwzlnula.html

[Q01] 创建表
来源：http://dali.zhixingplan.top/Article/details/gtobajohnh.html

CREATE TABLE users (
来源：http://dali.fzhhl.top/Article/details/gtmlochkgu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sweek.top/Article/details/gtaqunumac.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zycfv.cn/Article/details/gtppnvzdls.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sysykeji.top/Article/details/gtwhwqjgdz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.vqdsnc.cn/Article/details/gtjlrqgnyk.html

);
来源：http://dali.zhijiandao.cn/Article/details/gtrnaxhpyw.html

[Q02] 创建带外键的表
来源：http://dali.chenjidiqi.icu/Article/details/gttdrtaglm.html

CREATE TABLE orders (
来源：http://dali.aizwys.cn/Article/details/gtuorjmndc.html


<!-- 参考信息 -->