代发 wailian999

TS:   process.cwd()
来源：http://dali.yanxiufei.cn/Article/details/gt2wjzrmfrd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jlsjyb.cn/Article/details/gt2dqasvoli.html

Go:   os.Getwd()
来源：http://dali.yj20258.top/Article/details/gt2jogxroaa.html

Ruby: Dir.pwd
来源：http://dali.jqgfzy.top/Article/details/gt2pjtrusjm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cheryme.top/Article/details/gt2thbaceov.html

[M05] 设置退出码
来源：http://dali.smart0.xyz/Article/details/gt2hxvffrye.html

Py:   sys.exit(1)
来源：http://dali.guannengcc.top/Article/details/gt2jjvbbipd.html

PHP:  exit(1);
来源：http://dali.svipenyu.cn/Article/details/gt2npqsvqbe.html

JS:   process.exit(1)
来源：http://dali.zycfv.cn/Article/details/gt2gwohikfg.html

TS:   process.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2jbkyqkqt.html

Java: System.exit(1)
来源：http://dali.sysykeji.top/Article/details/gt2jivlvmut.html

Go:   os.Exit(1)
来源：http://dali.svipenyu.cn/Article/details/gt2fujxofis.html

Ruby: exit 1
来源：http://dali.birdmap.top/Article/details/gt2tyodbdcp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.0kj1m.cn/Article/details/gt2jqademng.html

[M06] 向标准错误输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ejxkukiu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.tian-w.cn/Article/details/gt2nvyjhnxh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.quarkkingdee.top/Article/details/gt2czbaqhho.html

JS:   console.error("err")
来源：http://dali.sxryk.cn/Article/details/gt2syxftxyg.html

TS:   console.error("err")
来源：http://dali.gzhubu.top/Article/details/gt2iymfolqo.html

Java: System.err.println("err")
来源：http://dali.yuanzhike.top/Article/details/gt2etdydqca.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.9152youxi.cn/Article/details/gt2gnibjmin.html

Ruby: warn "err"
来源：http://dali.cdnleiting.top/Article/details/gt2jgcjzsar.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinqigfzy.top/Article/details/gt2lzbmozer.html

[M07] 判断是否为主入口
来源：http://dali.dashuyun.cn/Article/details/gt2rlehxllo.html

Py:   if __name__ == "__main__":
来源：http://dali.zhiwuduotai.top/Article/details/gt2kwxoavuq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hammf.cn/Article/details/gt2hyolahfw.html

JS:   require.main === module
来源：http://dali.havefunace.top/Article/details/gt2gvnlqmra.html

TS:   require.main === module
来源：http://dali.hnqzz.top/Article/details/gt2tsaclrom.html

Java: public static void main(String[] args)
来源：http://dali.gotoacloud.top/Article/details/gt2ghsziusp.html

Go:   func main()
来源：http://dali.dianchejie.cn/Article/details/gt2fmljkbef.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.birdmap.top/Article/details/gt2anlbhiig.html

C#:   static void Main(string[] args)
来源：http://dali.cheryme.top/Article/details/gt2mpfdpfty.html

[M08] 获取系统与运行时信息
来源：http://dali.dashuyun.cn/Article/details/gt2vkrwbsuk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.smart0.xyz/Article/details/gt2jyhzyuki.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.kuanghao11.cn/Article/details/gt2qfbjkeos.html

JS:   process.platform;  process.version
来源：http://dali.fzhhl.top/Article/details/gt2hxmysvxe.html

TS:   process.platform;  process.version
来源：http://dali.ivvv.top/Article/details/gt2rlabvddd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yuanzhike.top/Article/details/gt2wdxydkjz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cucudq.cn/Article/details/gt2yipqyoxq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.snrcjt.cn/Article/details/gt2mrzvqpye.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yj202588.top/Article/details/gt2jzuoypch.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2tzpcfziw.html

N. 数据结构与算法
来源：http://dali.jqgufenzy.top/Article/details/gt2hfobkmpl.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2buxqzlrz.html

[N01] 二分查找（有序数组）
来源：http://dali.jinqigfzy.top/Article/details/gt2zbwikyyi.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2odjerftr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2izldlapc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ivvv.top/Article/details/gt2vreeoxtt.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuanzhike.top/Article/details/gt2rvwlaftz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gt2wuvqhtll.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2izxtvmdb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.andypj.xyz/Article/details/gt2ooecycdc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gt2xonryjfh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jiagoushi.top/Article/details/gt2xklplfve.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daxiang520.top/Article/details/gt2iuqcejns.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.vqdsnc.cn/Article/details/gt2crzmpeyl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.c1oappe.top/Article/details/gt2wuypavhd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hammf.cn/Article/details/gt2zckndots.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hnxiangtu.top/Article/details/gt2qcecotfz.html

Go:   slices.Sort(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2ctsjiuiu.html

Ruby: arr.sort
来源：http://dali.jqgufenzy.top/Article/details/gt2zsonvddu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhoulong.xyz/Article/details/gt2ukbhwbdl.html

[N03] 快速排序（分治示例）
来源：http://dali.yanxiufei.cn/Article/details/gt2krgdiokc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj20258888.top/Article/details/gt2jqpwlkip.html

PHP:  // 递归实现，或用 usort
来源：http://dali.dashuyun.cn/Article/details/gt2wfymurzd.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aibaodan.cn/Article/details/gt2fojflmyt.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258.top/Article/details/gt2edigjvdo.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yanxiufei.cn/Article/details/gt2qzcnkecw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yanxiufei.cn/Article/details/gt2fzapepph.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhongyouzk.top/Article/details/gt2olrlawef.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gaohongyu789.top/Article/details/gt2rnvwdwpi.html

[N04] 斐波那契数列
来源：http://dali.hywenlv.cn/Article/details/gt2noswvfut.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.meibo888.top/Article/details/gt2qypbnetd.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gaohongyu789.top/Article/details/gt2onyyynop.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gotoacloud.top/Article/details/gt2ymvlfnti.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ivvv.top/Article/details/gt2hwgcjhtz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xziqi.cn/Article/details/gt2gmsdbsob.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hfpthk.cn/Article/details/gt2choihxxs.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hfpthk.cn/Article/details/gt2bvrcdjdl.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gt2llytbmpo.html

[N05] 最大公约数
来源：http://dali.hongshengwenyu.top/Article/details/gt2thowdkfy.html

Py:   math.gcd(a, b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jhcjsayr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.316326.xyz/Article/details/gt2tpqgamvm.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zycfv.cn/Article/details/gt2eubmmkjg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2awuevalr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.havefunace.top/Article/details/gt2fvgdqnnd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.tianlin.xyz/Article/details/gt2whrulcfp.html

Ruby: a.gcd(b)
来源：http://dali.chenzaomai.com/Article/details/gt2ietgzyee.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yj20258888.top/Article/details/gt2xqrijrvp.html

[N06] 判断回文字符串
来源：http://dali.0kj1m.cn/Article/details/gt2nbbgabhk.html

Py:   s == s[::-1]
来源：http://dali.xinyue.icu/Article/details/gt2xfywvvbw.html

PHP:  $s === strrev($s);
来源：http://dali.iojbl.cn/Article/details/gt2aavgrbvw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ehwqpu.com/Article/details/gt2epkbzxio.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gt2tkbvhabh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xuanzx.com/Article/details/gt2ykfnsqjv.html

Go:   // 双指针从两端比较
来源：http://dali.316326.xyz/Article/details/gt2ztpasqas.html

Ruby: s == s.reverse
来源：http://dali.ybcxt.top/Article/details/gt2bnzkjgmk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hammf.cn/Article/details/gt2hvgamjjj.html

[N07] 两数之和（返回下标）
来源：http://dali.quarkkingdee.top/Article/details/gt2kmbmlcvg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cqqwz.cn/Article/details/gt2jxxdrfso.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cheryme.top/Article/details/gt2hazeurbe.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hgshkuvs.html

TS:   // 手写 Map<string, number>
来源：http://dali.gaohongyu789.top/Article/details/gt2kxejvsur.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkrbkqy.html

Go:   // 手写 map[int]int
来源：http://dali.zhoulong.xyz/Article/details/gt2atnivzsi.html

Ruby: // 手写 Hash
来源：http://dali.andypj.xyz/Article/details/gt2ezvwvajx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mmuapdps.html

[N08] 生成全排列
来源：http://dali.shuidangran.top/Article/details/gt2nbdcxgir.html

Py:   itertools.permutations(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2qcpjseqg.html

PHP:  // 手写递归交换
来源：http://dali.jyoumei.cn/Article/details/gt2gznhwtic.html

JS:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gt2zcwtgpal.html

TS:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gt2cwkhuejh.html

Java: // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gt2edwzsios.html

Go:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gt2bmmuunrz.html

Ruby: arr.permutation.to_a
来源：http://dali.gogol.net.cn/Article/details/gt2khregxhq.html

C#:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gt2rzfydohb.html

[N09] 栈与队列
来源：http://dali.tanke756.top/Article/details/gt2vqyjitts.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yangfankeji.com/Article/details/gt2mnpoosnc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sufxvd.cn/Article/details/gt2ytmrtxhw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.quarkkingdee.top/Article/details/gt2ywuzwfbb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.sufxvd.cn/Article/details/gt2dbvkitfr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.havefunace.top/Article/details/gt2qnahfrsl.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hnqzz.top/Article/details/gt2rorzschy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hammf.cn/Article/details/gt2evkdnufm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zdqjudy.top/Article/details/gt2ktvtekmp.html

[N10] 链表节点定义
来源：http://dali.smart0.xyz/Article/details/gt2fuijzdxf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gotoacloud.top/Article/details/gt2bmwsuijt.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhengqikj.top/Article/details/gt2cgcmqhan.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zycfv.cn/Article/details/gt2tqmbagta.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.316326.xyz/Article/details/gt2tmjrfaak.html

Java: class Node { int v; Node next; }
来源：http://dali.jqgfzy.top/Article/details/gt2xxhwelkc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jianghu66.top/Article/details/gt2jyfrgozi.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shzxlz.cn/Article/details/gt2qdulkqep.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zdqjudy.top/Article/details/gt2tellpbwk.html

[N11] 二叉树中序遍历
来源：http://dali.yonumen.top/Article/details/gt2akqnxtuo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.nwbrower.top/Article/details/gt2xnjtpohs.html

PHP:  // 手写递归函数
来源：http://dali.jqgufenzy.top/Article/details/gt2ckpokdsr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zycfv.cn/Article/details/gt2stxuakao.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258888.top/Article/details/gt2vvgnfjhx.html

Java: // 手写递归
来源：http://dali.guannengcc.top/Article/details/gt2gmtkvvdy.html

Go:   // 手写递归
来源：http://dali.chenlongwang.top/Article/details/gt2ffbayabu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cqqwz.cn/Article/details/gt2ianfdstg.html

C#:   // 手写递归
来源：http://dali.shzxlz.cn/Article/details/gt2stfrwpcs.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.aizwys.cn/Article/details/gt2klkvnidd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.quarkkingdee.top/Article/details/gt2lukcbjfd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.sysykeji.top/Article/details/gt2ofhjgceu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ydzc1.top/Article/details/gt2zaooesbv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sxryk.cn/Article/details/gt2lxsoazqu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigufen.top/Article/details/gt2xgalkacw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2txhhjnng.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sufxvd.cn/Article/details/gt2xmhkphka.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.dianchejie.cn/Article/details/gt2hpufvmvf.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2igibcbid.html

O. 并发与异步
来源：http://dali.jlsjyb.cn/Article/details/gt2idqjkeca.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2ouofmcda.html

[O01] 启动一个线程
来源：http://dali.gzhubu.top/Article/details/gt2gybppshr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jianghu66.top/Article/details/gt2yvfkqdrf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yvedp.cn/Article/details/gt2ieoyxtrk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.dianchejie.cn/Article/details/gt2botwonhu.html

TS:   // 同 JS
来源：http://dali.0kj1m.cn/Article/details/gt2zwdaxdaj.html

Java: new Thread(() -> f()).start()
来源：http://dali.shuidangran.top/Article/details/gt2oeqydnty.html

Go:   go f()
来源：http://dali.zdqjudy.top/Article/details/gt2gxuytxhj.html

Ruby: Thread.new { f }
来源：http://dali.svipenyu.cn/Article/details/gt2pmwrskqt.html

C#:   Task.Run(() => F());
来源：http://dali.gzhubu.top/Article/details/gt2xzgtptwu.html

[O02] 使用线程池
来源：http://dali.fengsongda.top/Article/details/gt2wirpscho.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yj20258888.top/Article/details/gt2pcooyzxv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yuanzhike.top/Article/details/gt2jvdnkbvr.html

JS:   // worker_threads 线程池
来源：http://dali.bjfxy.top/Article/details/gt2wsqvvcqj.html

TS:   // worker_threads 线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pjchpprq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ybcxt.top/Article/details/gt2trhgyxhd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hnxiangtu.top/Article/details/gt2ekrrjsgq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ydzc1.top/Article/details/gt2kfvgezgj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gzhubu.top/Article/details/gt2jynyrnos.html

[O03] 加锁保护共享数据
来源：http://dali.mhx1999.top/Article/details/gt2sfhpgtut.html

Py:   with lock: shared += 1
来源：http://dali.yongpay.top/Article/details/gt2cziherhg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jiagoushi.top/Article/details/gt2xxtpyupk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.iojbl.cn/Article/details/gt2vsqeqxki.html

TS:   // 同 JS
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2capsryvy.html

Java: synchronized (this) { shared++; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2tyndmgts.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.tianlin.xyz/Article/details/gt2azgmfcwd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.0kj1m.cn/Article/details/gt2zedmioma.html

C#:   lock (gate) { shared++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2liuzznya.html

[O04] 定义异步函数并等待
来源：http://dali.yuxming.cn/Article/details/gt2ksribwzu.html

Py:   async def f():⏎    await g()
来源：http://dali.yuxming.cn/Article/details/gt2bsjwzslo.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yuanzhike.top/Article/details/gt2hspnksic.html

JS:   async function f() { await g(); }
来源：http://dali.jinqigufen.top/Article/details/gt2lmzsjqsi.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.daxiang520.top/Article/details/gt2efileixi.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.9152youxi.cn/Article/details/gt2oxuvvvub.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zdqjudy.top/Article/details/gt2girmilfc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ujzvytcm.html

C#:   async Task F() { await G(); }
来源：http://dali.daxiang520.top/Article/details/gt2ecfnbmmg.html

[O05] 并发执行并等待全部完成
来源：http://dali.jqgufenzy.top/Article/details/gt2kpvateuy.html

Py:   asyncio.gather(*tasks)
来源：http://dali.316326.xyz/Article/details/gt2kxqzxgwd.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.wangdashe.top/Article/details/gt2assfnpsc.html

JS:   await Promise.all(tasks)
来源：http://dali.jqgufenzy.top/Article/details/gt2xzelmojs.html

TS:   await Promise.all(tasks)
来源：http://dali.c1oappe.top/Article/details/gt2oigjytwz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.snrcjt.cn/Article/details/gt2onfrsewz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xylfe.cn/Article/details/gt2owtqlcwv.html

Ruby: threads.map(&:join)
来源：http://dali.haohaochexian.top/Article/details/gt2pjwvycsg.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ppjwa.cn/Article/details/gt2vhmyvynq.html

[O06] 使用进程池
来源：http://dali.birdmap.top/Article/details/gt2elaeovgc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.gaohongyu789.top/Article/details/gt2hvxlghik.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yuxming.cn/Article/details/gt2cbkmscsw.html

JS:   // child_process / cluster 模块
来源：http://dali.ppjwa.cn/Article/details/gt2kevqpogz.html

TS:   // child_process / cluster 模块
来源：http://dali.quarkkingdee.top/Article/details/gt2whkqvouj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhixingplan.top/Article/details/gt2nrzmuhnj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.wangdashe.top/Article/details/gt2pyglyibt.html

Ruby: // fork 块
来源：http://dali.shangyingyoupin.top/Article/details/gt2raofeech.html

C#:   Parallel.For
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rfezurxl.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2ywdsxbsc.html

P. 常用工具函数
来源：http://dali.jqgufenzy.top/Article/details/gt2sfvlmlgg.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2afowpsnk.html

[P01] 生成 UUID
来源：http://dali.wangdashe.top/Article/details/gt2medwlray.html

Py:   str(uuid.uuid4())
来源：http://dali.daria6918.cn/Article/details/gt2hwtsekzs.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.redwolf501.top/Article/details/gt2gwiuyepd.html

JS:   crypto.randomUUID()
来源：http://dali.pycfn.com/Article/details/gt2rvuyqenj.html

TS:   crypto.randomUUID()
来源：http://dali.yuxming.cn/Article/details/gt2htbrsfsn.html

Java: UUID.randomUUID().toString()
来源：http://dali.guowangkeji.top/Article/details/gt2lrfqxann.html

Go:   // 用 github.com/google/uuid
来源：http://dali.fzhhl.top/Article/details/gt2mwxykdwr.html

Ruby: SecureRandom.uuid
来源：http://dali.pengpengdd.cyou/Article/details/gt2gdjlnzdf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.snrcjt.cn/Article/details/gt2dbqgqsii.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ehwqpu.com/Article/details/gt2xxdmvjqi.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yuxming.cn/Article/details/gt2gdwdztje.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.bjfxy.top/Article/details/gt2kjrnenay.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhoulong.xyz/Article/details/gt2nxtmnrqu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sufxvd.cn/Article/details/gt2fyqvkyvz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.nanxuanxn.top/Article/details/gt2cjykiuwo.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.quarkkingdee.top/Article/details/gt2krozojsd.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkjcrfi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gogol.net.cn/Article/details/gt2xtqdzzoi.html

[P03] 生成短随机字符串
来源：http://dali.dashuyun.cn/Article/details/gt2dizawtdr.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xylfe.cn/Article/details/gt2bxwbtgwo.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhoulong.xyz/Article/details/gt2bsmamgwa.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgufenzy.top/Article/details/gt2awzzgedg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.vqdsnc.cn/Article/details/gt2twbgmkow.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.chenjidiqi.icu/Article/details/gt2udaxqdcv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jinqigfzy.top/Article/details/gt2lxbpwczs.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qyslndld.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hongshengwenyu.top/Article/details/gt2zywwachs.html

[P04] 求长度
来源：http://dali.gogol.net.cn/Article/details/gt2jhcnxpat.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jianghu66.top/Article/details/gt2isijzlgz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gt2lkghlmos.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgufenzy.top/Article/details/gt2adfwdhyd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mssxrcps.html

Java: list.size();  map.size();  s.length()
来源：http://dali.pengpengdd.cyou/Article/details/gt2jyqupria.html

Go:   len(arr);  len(m)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ybrewwtw.html

Ruby: x.length;  x.size
来源：http://dali.cqqwz.cn/Article/details/gt2fazawxfy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hywenlv.cn/Article/details/gt2ifpuxugc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.9152youxi.cn/Article/details/gt2kebjzgwa.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinqigufen.top/Article/details/gt2emwticzl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.pycfn.com/Article/details/gt2bxzytxab.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.pengpengdd.cyou/Article/details/gt2wokqdhbg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hammf.cn/Article/details/gt2xjbsimrb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jlsjyb.cn/Article/details/gt2ujfhytxc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yj202588.top/Article/details/gt2eifkdxje.html

Ruby: a == b
来源：http://dali.wangdashe.top/Article/details/gt2lzobspkr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xinyue.icu/Article/details/gt2swddzlrv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yvedp.cn/Article/details/gt2jxmpgfij.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tbfwoqfx.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qdfkkcvi.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yuanzhike.top/Article/details/gt2mgkhhnfa.html

TS:   if (x == null) {}
来源：http://dali.ivvv.top/Article/details/gt2qoprotvj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.smart0.xyz/Article/details/gt2xutulxsy.html

Go:   if x == nil {}
来源：http://dali.xuanzx.com/Article/details/gt2lypaagcj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.aibaodan.cn/Article/details/gt2ttepnacb.html

C#:   if (x is null) {}
来源：http://dali.hfpthk.cn/Article/details/gt2qhuumglj.html

[P07] 防抖与节流
来源：http://dali.cheryme.top/Article/details/gt2nfwbkwqp.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.nwbrower.top/Article/details/gt2oredfewe.html

PHP:  // 手写时间戳比较
来源：http://dali.gotoacloud.top/Article/details/gt2kabskxxz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxinkj.top/Article/details/gt2lsrayahq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hammf.cn/Article/details/gt2gxuikdmc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.aibaodan.cn/Article/details/gt2zipjvqxq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yuxming.cn/Article/details/gt2wbrheeuf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.mhx1999.top/Article/details/gt2npjionyj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.birdmap.top/Article/details/gt2dxagyuhw.html

[P08] 处理浮点精度问题
来源：http://dali.daxiang520.top/Article/details/gt2fjpaquvf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.tian-w.cn/Article/details/gt2lzipunhs.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hammf.cn/Article/details/gt2nptpkbsa.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zycfv.cn/Article/details/gt2kwyaydhg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.sweek.top/Article/details/gt2lmlvfivl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shzxlz.cn/Article/details/gt2wsxxwgll.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinqigufen.top/Article/details/gt2pvuupnuc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.meibo888.top/Article/details/gt2pghpmwzn.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jinqigufen.top/Article/details/gt2bhzdkdsb.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2kgetslqg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.wangshuangyany.cn/Article/details/gt2naryhlud.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2bmvcamhc.html

[Q01] 创建表
来源：http://dali.snrcjt.cn/Article/details/gt2rmzwuruo.html

CREATE TABLE users (
来源：http://dali.sxryk.cn/Article/details/gt2pmvqpmin.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shuidangran.top/Article/details/gt2ykcfwubs.html

name VARCHAR(50) NOT NULL,
来源：http://dali.guowangkeji.top/Article/details/gt2bjdwxpxc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eqlptsij.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.snrcjt.cn/Article/details/gt2mhilgkan.html

);
来源：http://dali.birdmap.top/Article/details/gt2zpuubhml.html

[Q02] 创建带外键的表
来源：http://dali.mhx1999.top/Article/details/gt2vlyrqclr.html

CREATE TABLE orders (
来源：http://dali.xziqi.cn/Article/details/gt2hledcnas.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnqzz.top/Article/details/gt2lhnkdios.html

user_id INT NOT NULL,
来源：http://dali.ppjwa.cn/Article/details/gt2aqsuhhhq.html

amount DECIMAL(10, 2),
来源：http://dali.yonumen.top/Article/details/gt2vgmdamwu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ydzc1.top/Article/details/gt2duzpdvhy.html


<!-- 参考信息 -->