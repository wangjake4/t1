代发 wailian999

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.dashuyun.cn/Article/details/gtpiztzxax.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shanyushiyangtech.top/Article/details/gtjuibkars.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.dashuyun.cn/Article/details/gtlnpclrle.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yuanzhike.top/Article/details/gtmomdngeu.html

[M04] 获取当前工作目录
来源：http://dali.hnqzz.top/Article/details/gtuqufpiit.html

Py:   os.getcwd()
来源：http://dali.316326.xyz/Article/details/gttehwlbyc.html

PHP:  getcwd();
来源：http://dali.sysykeji.top/Article/details/gthrtwruby.html

JS:   process.cwd()
来源：http://dali.yj20258.top/Article/details/gtwhgcgvuh.html

TS:   process.cwd()
来源：http://dali.pengpengdd.cyou/Article/details/gtuoqoyqwn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hnxiangtu.top/Article/details/gtubgnctiq.html

Go:   os.Getwd()
来源：http://dali.gzhubu.top/Article/details/gtmdtysmpc.html

Ruby: Dir.pwd
来源：http://dali.pycfn.com/Article/details/gtaukohfhr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jlsjyb.cn/Article/details/gtfmaigmeo.html

[M05] 设置退出码
来源：http://dali.cucudq.cn/Article/details/gthttisnyu.html

Py:   sys.exit(1)
来源：http://dali.xuanzx.com/Article/details/gtgkogasvp.html

PHP:  exit(1);
来源：http://dali.zhengqikj.top/Article/details/gtikqrtowh.html

JS:   process.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gthjllpanc.html

TS:   process.exit(1)
来源：http://dali.cheryme.top/Article/details/gteykexvwz.html

Java: System.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gtgtffbeei.html

Go:   os.Exit(1)
来源：http://dali.yuxming.cn/Article/details/gtvwobjykp.html

Ruby: exit 1
来源：http://dali.ppjwa.cn/Article/details/gtxoxtmgzv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.tanke756.top/Article/details/gtftbaexbk.html

[M06] 向标准错误输出
来源：http://dali.birdmap.top/Article/details/gtppzokgvj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sufxvd.cn/Article/details/gtyowdhrbt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.tian-w.cn/Article/details/gtriblrsth.html

JS:   console.error("err")
来源：http://dali.xylfe.cn/Article/details/gtjlwmykqj.html

TS:   console.error("err")
来源：http://dali.jlsjyb.cn/Article/details/gtdysamklh.html

Java: System.err.println("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlphdnwmb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhongyouzk.top/Article/details/gtutrzvexu.html

Ruby: warn "err"
来源：http://dali.ppjwa.cn/Article/details/gtuyjkwgwl.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.fengsongda.top/Article/details/gtevqeboyx.html

[M07] 判断是否为主入口
来源：http://dali.yonumen.top/Article/details/gttbdjxwrm.html

Py:   if __name__ == "__main__":
来源：http://dali.guowangkeji.top/Article/details/gtcimbvtgk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zdqjudy.top/Article/details/gtqwnmcryo.html

JS:   require.main === module
来源：http://dali.zhiwuduotai.top/Article/details/gthoptxvtk.html

TS:   require.main === module
来源：http://dali.yangfankeji.com/Article/details/gtmopyvxwk.html

Java: public static void main(String[] args)
来源：http://dali.sxryk.cn/Article/details/gtwycbynbh.html

Go:   func main()
来源：http://dali.yuxming.cn/Article/details/gtteehlpzf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.pycfn.com/Article/details/gtrmbqocuu.html

C#:   static void Main(string[] args)
来源：http://dali.zhiwuduotai.top/Article/details/gtpjmtllvb.html

[M08] 获取系统与运行时信息
来源：http://dali.jqgufenzy.top/Article/details/gthqmcukid.html

Py:   platform.system();  platform.python_version()
来源：http://dali.andypj.xyz/Article/details/gtfrnfzpdb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.9152youxi.cn/Article/details/gtbgpidmju.html

JS:   process.platform;  process.version
来源：http://dali.wangdashe.top/Article/details/gtmifpjllf.html

TS:   process.platform;  process.version
来源：http://dali.sweek.top/Article/details/gtjfgfsdje.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xuanzx.com/Article/details/gtwrmfmifh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yvedp.cn/Article/details/gtwmiwjbay.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jyoumei.cn/Article/details/gtwreccbqg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhiwuduotai.top/Article/details/gtvtmhffnr.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtopcvrjpj.html

N. 数据结构与算法
来源：http://dali.vqdsnc.cn/Article/details/gtbvcbfvcn.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtepwdlgej.html

[N01] 二分查找（有序数组）
来源：http://dali.zhongyouzk.top/Article/details/gtklakxqaf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.meibo888.top/Article/details/gtwevvsenh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hysaishi.cn/Article/details/gtoxbcyjho.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hysaishi.cn/Article/details/gtxyrzhngx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsfopataz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.tanke756.top/Article/details/gtzdhwuyea.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.mhx1999.top/Article/details/gthpmxwmtb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.redwolf501.top/Article/details/gtdivtzdkf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gtyikwdwqk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shuidangran.top/Article/details/gtozbnkdnu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.andypj.xyz/Article/details/gtgwqoahjg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.tanke756.top/Article/details/gtnygezjvu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.vqdsnc.cn/Article/details/gtetzxrlda.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.quarkkingdee.top/Article/details/gtlxpbcotq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhengqikj.top/Article/details/gtqoqoxcos.html

Go:   slices.Sort(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcfmgykqg.html

Ruby: arr.sort
来源：http://dali.hnqzz.top/Article/details/gtyvhrqwzo.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhiwuduotai.top/Article/details/gtiiiuicqc.html

[N03] 快速排序（分治示例）
来源：http://dali.jiagoushi.top/Article/details/gtbtqyxfow.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yuanzhike.top/Article/details/gtbqoddolv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.wangdashe.top/Article/details/gtuzevxvxm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258888.top/Article/details/gtwfoxexwg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yonumen.top/Article/details/gtzsflnfer.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj202588.top/Article/details/gttmesvopt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.0kj1m.cn/Article/details/gtchgglevs.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zycfv.cn/Article/details/gtcsmikeis.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.quarkkingdee.top/Article/details/gtzyhpstic.html

[N04] 斐波那契数列
来源：http://dali.ehwqpu.com/Article/details/gtzxxkyxhi.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.iojbl.cn/Article/details/gtjipzcpbv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jqgfzy.top/Article/details/gtsiynkhdy.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnxiangtu.top/Article/details/gtydktazas.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenzaomai.com/Article/details/gtqzboxyos.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yvedp.cn/Article/details/gtzkwfqyel.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ehwqpu.com/Article/details/gtbrchaztz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.birdmap.top/Article/details/gtgdbckokv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yongpay.top/Article/details/gtnyeeifel.html

[N05] 最大公约数
来源：http://dali.fzhhl.top/Article/details/gthupvuary.html

Py:   math.gcd(a, b)
来源：http://dali.zhoulong.xyz/Article/details/gtwcyocktd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jianghu66.top/Article/details/gtgcgjncmd.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.andypj.xyz/Article/details/gtkbtzfrka.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aizwys.cn/Article/details/gtkbszsekc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.tianlin.xyz/Article/details/gtoryrpvfq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.tian-w.cn/Article/details/gtduulsddi.html

Ruby: a.gcd(b)
来源：http://dali.nanxuanxn.top/Article/details/gtswqoemvg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yuanzhike.top/Article/details/gtzvscrmti.html

[N06] 判断回文字符串
来源：http://dali.havefunace.top/Article/details/gthqpulrgn.html

Py:   s == s[::-1]
来源：http://dali.gotoacloud.top/Article/details/gtbppnglao.html

PHP:  $s === strrev($s);
来源：http://dali.sweek.top/Article/details/gtpbxuunfz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gtsgzxgwwl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gtfxgtmhsl.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jianghu66.top/Article/details/gthemmngel.html

Go:   // 双指针从两端比较
来源：http://dali.nanxuanxn.top/Article/details/gtmbfwiiks.html

Ruby: s == s.reverse
来源：http://dali.dashuyun.cn/Article/details/gtynhdfrlr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.0kj1m.cn/Article/details/gtjeuxscre.html

[N07] 两数之和（返回下标）
来源：http://dali.shanyushiyangtech.top/Article/details/gtsozzinjv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinqigfzy.top/Article/details/gtvdjqewvw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhengqikj.top/Article/details/gtohsrviam.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.smart0.xyz/Article/details/gtvnmhderv.html

TS:   // 手写 Map<string, number>
来源：http://dali.yj20258888.top/Article/details/gtsblbtydj.html

Java: // 手写 HashMap
来源：http://dali.shanyushiyangtech.top/Article/details/gtanxsggls.html

Go:   // 手写 map[int]int
来源：http://dali.snrcjt.cn/Article/details/gtbdfygxoc.html

Ruby: // 手写 Hash
来源：http://dali.meibo888.top/Article/details/gtuqtbyyvh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.bjfxy.top/Article/details/gtqdmkcqsp.html

[N08] 生成全排列
来源：http://dali.jinqigfzy.top/Article/details/gtvtpvpzpq.html

Py:   itertools.permutations(arr)
来源：http://dali.hnqzz.top/Article/details/gtixprihup.html

PHP:  // 手写递归交换
来源：http://dali.nanxuanxn.top/Article/details/gtuxawdzoo.html

JS:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gtjmapbfqm.html

TS:   // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gtijukqnvq.html

Java: // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gtmeblfuru.html

Go:   // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gtkmoylyko.html

Ruby: arr.permutation.to_a
来源：http://dali.yuanzhike.top/Article/details/gttpjtpsqx.html

C#:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gtcessinzy.html

[N09] 栈与队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrkbucqtt.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gtimextgtg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shzxlz.cn/Article/details/gtizleujzb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gtpwbmuynz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinqigfzy.top/Article/details/gtolnhoyce.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinqigfzy.top/Article/details/gtckkxkvkn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.tanke756.top/Article/details/gticiswoyx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gthrkqbepb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.fengsongda.top/Article/details/gthmzisteg.html

[N10] 链表节点定义
来源：http://dali.meibo888.top/Article/details/gthxgkxfjv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sufxvd.cn/Article/details/gtqrjizbmb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xuetiantiany.cn/Article/details/gtyideqkbp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shangyingyoupin.top/Article/details/gtbywdercd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jianghu66.top/Article/details/gtlpwbttwa.html

Java: class Node { int v; Node next; }
来源：http://dali.hnqzz.top/Article/details/gtflqdqphq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hnxiangtu.top/Article/details/gttbxxetkw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yj20258888.top/Article/details/gtpulyzdtj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.daxiang520.top/Article/details/gtwhynbsho.html

[N11] 二叉树中序遍历
来源：http://dali.zhengqikj.top/Article/details/gtminhkeeg.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.wangshuangyany.cn/Article/details/gtzkrlmtsk.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gtksrhxxtd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yvedp.cn/Article/details/gttapxqlng.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.wangshuangyany.cn/Article/details/gttrwlhwhk.html

Java: // 手写递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gthgkeruei.html

Go:   // 手写递归
来源：http://dali.shuidangran.top/Article/details/gtuygfarzg.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.chenlongwang.top/Article/details/gtopzjmknu.html

C#:   // 手写递归
来源：http://dali.gaohongyu789.top/Article/details/gtiwfyfced.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.meibo888.top/Article/details/gtkekraoqu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.smart0.xyz/Article/details/gtrsfqrfpw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xinyue.icu/Article/details/gtgoolmmrs.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fengsongda.top/Article/details/gtlkfbuhix.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cashguo.top/Article/details/gtvwcozzry.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hysaishi.cn/Article/details/gtkagbtavy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhoulong.xyz/Article/details/gtuvejzfnr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.birdmap.top/Article/details/gtjlppanrc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yonumen.top/Article/details/gtygvqgyaq.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtoapukhku.html

O. 并发与异步
来源：http://dali.ybcxt.top/Article/details/gtapzofxah.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtrlhgbhcu.html

[O01] 启动一个线程
来源：http://dali.cashguo.top/Article/details/gtlssxlvdx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.tian-w.cn/Article/details/gtzhunonsd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.tian-w.cn/Article/details/gtwzalqidn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shangyingyoupin.top/Article/details/gtnjjodebb.html

TS:   // 同 JS
来源：http://dali.hfpthk.cn/Article/details/gtqfecqdui.html

Java: new Thread(() -> f()).start()
来源：http://dali.cucudq.cn/Article/details/gtrkkrrjnj.html

Go:   go f()
来源：http://dali.tianlin.xyz/Article/details/gtpfyuobrv.html

Ruby: Thread.new { f }
来源：http://dali.sysykeji.top/Article/details/gtyzawsupm.html

C#:   Task.Run(() => F());
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdjwpjpkt.html

[O02] 使用线程池
来源：http://dali.0kj1m.cn/Article/details/gtqrgfkxnf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkkajbowa.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hammf.cn/Article/details/gtpofbrquz.html

JS:   // worker_threads 线程池
来源：http://dali.c1oappe.top/Article/details/gtkiwcrxmc.html

TS:   // worker_threads 线程池
来源：http://dali.jinghuilouyu.cn/Article/details/gtosnrmkmn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthakhcozs.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhoulong.xyz/Article/details/gtxqexettg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xylfe.cn/Article/details/gtccufdghl.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.birdmap.top/Article/details/gtyhlbsfqd.html

[O03] 加锁保护共享数据
来源：http://dali.cucudq.cn/Article/details/gtoxqxwmlp.html

Py:   with lock: shared += 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpakcwjcd.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jyoumei.cn/Article/details/gtvlmdkugb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xuanzx.com/Article/details/gtymtcycmt.html

TS:   // 同 JS
来源：http://dali.hnxiangtu.top/Article/details/gtfovfwirh.html

Java: synchronized (this) { shared++; }
来源：http://dali.xylfe.cn/Article/details/gtmexyudbi.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.daria6918.cn/Article/details/gtatszjupi.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.fzhhl.top/Article/details/gtqerqlgux.html

C#:   lock (gate) { shared++; }
来源：http://dali.chenzaomai.com/Article/details/gtlgpwhlig.html

[O04] 定义异步函数并等待
来源：http://dali.yj20258.top/Article/details/gtxymkhrbl.html

Py:   async def f():⏎    await g()
来源：http://dali.jinqigfzy.top/Article/details/gtpjdwuqvl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtopjmlgws.html

JS:   async function f() { await g(); }
来源：http://dali.quarkkingdee.top/Article/details/gtnxlgqwvk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yvedp.cn/Article/details/gtqaurqwdo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hongshengwenyu.top/Article/details/gtxbbwlghq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xinyue.icu/Article/details/gtokqvcclq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhixingplan.top/Article/details/gtfqmxsrws.html

C#:   async Task F() { await G(); }
来源：http://dali.meibo888.top/Article/details/gtjxxzbsko.html

[O05] 并发执行并等待全部完成
来源：http://dali.hnxiangtu.top/Article/details/gtbvzmmsgh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.quarkkingdee.top/Article/details/gtaapgxufs.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cucudq.cn/Article/details/gtlwmgqjwi.html

JS:   await Promise.all(tasks)
来源：http://dali.hfpthk.cn/Article/details/gtneuyflrn.html

TS:   await Promise.all(tasks)
来源：http://dali.jqgufenzy.top/Article/details/gtxbkpuuja.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gogol.net.cn/Article/details/gttoeavngn.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.aizwys.cn/Article/details/gtwsjzolod.html

Ruby: threads.map(&:join)
来源：http://dali.guannengcc.top/Article/details/gthkpthdua.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cucudq.cn/Article/details/gtcvpdqioz.html

[O06] 使用进程池
来源：http://dali.zycfv.cn/Article/details/gtrjcbvfyf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yongpay.top/Article/details/gtbawiaqfh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.svipenyu.cn/Article/details/gtexravrdg.html

JS:   // child_process / cluster 模块
来源：http://dali.yvedp.cn/Article/details/gtwqedceat.html

TS:   // child_process / cluster 模块
来源：http://dali.redwolf501.top/Article/details/gtuberfvud.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xinyue.icu/Article/details/gtkflwtjjm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.chenzaomai.com/Article/details/gturkettvp.html

Ruby: // fork 块
来源：http://dali.xuanzx.com/Article/details/gteweygdoi.html

C#:   Parallel.For
来源：http://dali.svipenyu.cn/Article/details/gtegubwosx.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtzlmpzrer.html

P. 常用工具函数
来源：http://dali.yonumen.top/Article/details/gtddshxcjh.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtdobhqcny.html

[P01] 生成 UUID
来源：http://dali.fengsongda.top/Article/details/gtvjlkltbw.html

Py:   str(uuid.uuid4())
来源：http://dali.guowangkeji.top/Article/details/gtkipikfch.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.vqdsnc.cn/Article/details/gtiqkalkjv.html

JS:   crypto.randomUUID()
来源：http://dali.fengsongda.top/Article/details/gttisrosmw.html

TS:   crypto.randomUUID()
来源：http://dali.pengpengdd.cyou/Article/details/gtxqywqikj.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinqigufen.top/Article/details/gtjobjryvt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yueranfly.top/Article/details/gtjgnzueoq.html

Ruby: SecureRandom.uuid
来源：http://dali.sweek.top/Article/details/gtaiczsejh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.nanxinkj.top/Article/details/gtbxcoiydx.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinqigufen.top/Article/details/gtlvilfksa.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xuetiantiany.cn/Article/details/gtrdparqwc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.haohaochexian.top/Article/details/gtmzxiivbn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cdnleiting.top/Article/details/gtfxhfxjao.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cheryme.top/Article/details/gtfsldjvyo.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ydzc1.top/Article/details/gtjutuijgz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.meibo888.top/Article/details/gtjwbkcsvi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xuanzx.com/Article/details/gtftnejywu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.aibaodan.cn/Article/details/gtqmdiimgc.html

[P03] 生成短随机字符串
来源：http://dali.mhx1999.top/Article/details/gtvwmjzaoq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.redwolf501.top/Article/details/gtyvpmxcox.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cqqwz.cn/Article/details/gtsomrvhdi.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.0kj1m.cn/Article/details/gtdqesjsss.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtneizlxqn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yvedp.cn/Article/details/gtvbcpfqai.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.redwolf501.top/Article/details/gtvdqvtsis.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yvedp.cn/Article/details/gtwmhpzvhv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.nanxuanxn.top/Article/details/gtkktfxwzs.html

[P04] 求长度
来源：http://dali.yj20258.top/Article/details/gtpeyqxoyj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jqgufenzy.top/Article/details/gtoxorhmvd.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gtuaeikplv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhengqikj.top/Article/details/gtudbxlsje.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jyoumei.cn/Article/details/gtpjhmqwdd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jqgfzy.top/Article/details/gtghditcdy.html

Go:   len(arr);  len(m)
来源：http://dali.zhixingplan.top/Article/details/gtqrzddjiu.html

Ruby: x.length;  x.size
来源：http://dali.kuanghao11.cn/Article/details/gtgcbmddec.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ybcxt.top/Article/details/gtmnglpvvx.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yuanzhike.top/Article/details/gteikxhhfh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yj20258888.top/Article/details/gtdbchzkls.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ydzc1.top/Article/details/gtybiognun.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.c1oappe.top/Article/details/gtynlrqdlr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.pycfn.com/Article/details/gtlplqmsnw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hammf.cn/Article/details/gtxmuhwzyo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.haohaochexian.top/Article/details/gtgwxtebiv.html

Ruby: a == b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdoyiszyu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.birdmap.top/Article/details/gtllbdtwdn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yvedp.cn/Article/details/gtmfnwnwas.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.andypj.xyz/Article/details/gtdxyyjynj.html

PHP:  if (empty($x)) {}
来源：http://dali.cheryme.top/Article/details/gtaakruhhz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhengqikj.top/Article/details/gthhzgyxar.html

TS:   if (x == null) {}
来源：http://dali.hfpthk.cn/Article/details/gtymlmmtzp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xuanzx.com/Article/details/gteyfgyndw.html

Go:   if x == nil {}
来源：http://dali.jlsjyb.cn/Article/details/gtexroxign.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cashguo.top/Article/details/gtsqumnrqm.html

C#:   if (x is null) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtjaqdodnd.html

[P07] 防抖与节流
来源：http://dali.pycfn.com/Article/details/gtnsmiajgo.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.chenjidiqi.icu/Article/details/gtdqsxfhdd.html

PHP:  // 手写时间戳比较
来源：http://dali.nanxuanxn.top/Article/details/gtusnmsnbe.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ybcxt.top/Article/details/gtnruhxedv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sysykeji.top/Article/details/gtkvyveczh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jyoumei.cn/Article/details/gtqkzusutd.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.meibo888.top/Article/details/gtdjibqijc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.tian-w.cn/Article/details/gtnvduqscu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.cucudq.cn/Article/details/gtiaotpoba.html

[P08] 处理浮点精度问题
来源：http://dali.gotoacloud.top/Article/details/gtvlwjrfzq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.chenjidiqi.icu/Article/details/gtwyumfuwc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.haohaochexian.top/Article/details/gtdvmfyhfy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cucudq.cn/Article/details/gtufdjkmap.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cqqwz.cn/Article/details/gtomxphkyx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtectkmuef.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhixingplan.top/Article/details/gtzhbubjbe.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtptwybquc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.meibo888.top/Article/details/gtroptmsue.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gttuzlrgnw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.pengpengdd.cyou/Article/details/gtszalfude.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtzibychbj.html

[Q01] 创建表
来源：http://dali.gotoacloud.top/Article/details/gtgielbltt.html

CREATE TABLE users (
来源：http://dali.nanxinkj.top/Article/details/gtzpszqlsy.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ppjwa.cn/Article/details/gtyjhvptkw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.vqdsnc.cn/Article/details/gtnpfbyveo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hnxiangtu.top/Article/details/gtuvnizxll.html


<!-- 参考信息 -->