代发 wailian999

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.316326.xyz/Article/details/gtfzomvqru.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xuanzx.com/Article/details/gtumrtrwlr.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.meibo888.top/Article/details/gtorpzfdaf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinqigufen.top/Article/details/gtutvkbekm.html

[M04] 获取当前工作目录
来源：http://dali.shuidangran.top/Article/details/gtngaugazi.html

Py:   os.getcwd()
来源：http://dali.ydzc1.top/Article/details/gtlujlfsbi.html

PHP:  getcwd();
来源：http://dali.9152youxi.cn/Article/details/gtmfzmdhsp.html

JS:   process.cwd()
来源：http://dali.hammf.cn/Article/details/gtpkjjckvj.html

TS:   process.cwd()
来源：http://dali.yangfankeji.com/Article/details/gtqdudfywa.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.nwbrower.top/Article/details/gtgqhpowev.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gtvioakqaj.html

Ruby: Dir.pwd
来源：http://dali.ppjwa.cn/Article/details/gtzvjzsvly.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.smart0.xyz/Article/details/gtlmjcucow.html

[M05] 设置退出码
来源：http://dali.hongshengwenyu.top/Article/details/gtmoqmsooi.html

Py:   sys.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtuusiskht.html

PHP:  exit(1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcfljvtzo.html

JS:   process.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtnffruqwv.html

TS:   process.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gtelvbvclr.html

Java: System.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtfwdnsipy.html

Go:   os.Exit(1)
来源：http://dali.jiagoushi.top/Article/details/gtmwutxrdy.html

Ruby: exit 1
来源：http://dali.sxryk.cn/Article/details/gtucjbjyqu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hnxiangtu.top/Article/details/gtcwjpbrcx.html

[M06] 向标准错误输出
来源：http://dali.nanxinkj.top/Article/details/gtdezvodtc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jiagoushi.top/Article/details/gtwpkvvwvz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shanyushiyangtech.top/Article/details/gtupsesgmf.html

JS:   console.error("err")
来源：http://dali.316326.xyz/Article/details/gtfqqqolcy.html

TS:   console.error("err")
来源：http://dali.quarkkingdee.top/Article/details/gtwrfjkueb.html

Java: System.err.println("err")
来源：http://dali.havefunace.top/Article/details/gtpnddggnt.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yuanzhike.top/Article/details/gtnawfeeow.html

Ruby: warn "err"
来源：http://dali.xylfe.cn/Article/details/gtgjagdrsx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.pycfn.com/Article/details/gtdpkasxhe.html

[M07] 判断是否为主入口
来源：http://dali.jinghuilouyu.cn/Article/details/gtvcygjghk.html

Py:   if __name__ == "__main__":
来源：http://dali.pengpengdd.cyou/Article/details/gtuvvfwqmc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhongyouzk.top/Article/details/gtyyxhlcxj.html

JS:   require.main === module
来源：http://dali.nanxinkj.top/Article/details/gttwpoymld.html

TS:   require.main === module
来源：http://dali.ppjwa.cn/Article/details/gtigjskpen.html

Java: public static void main(String[] args)
来源：http://dali.jianghu66.top/Article/details/gtittynkdu.html

Go:   func main()
来源：http://dali.yuxming.cn/Article/details/gtcffbbkbf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.svipenyu.cn/Article/details/gtftoiyibd.html

C#:   static void Main(string[] args)
来源：http://dali.dashuyun.cn/Article/details/gtatdkfbke.html

[M08] 获取系统与运行时信息
来源：http://dali.xylfe.cn/Article/details/gtmszjrpok.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gaohongyu789.top/Article/details/gtrxyuuhjr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.fengsongda.top/Article/details/gtnxlbihym.html

JS:   process.platform;  process.version
来源：http://dali.fengsongda.top/Article/details/gtxjtssrey.html

TS:   process.platform;  process.version
来源：http://dali.haohaochexian.top/Article/details/gtxntympip.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.daria6918.cn/Article/details/gtgjnecokf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cucudq.cn/Article/details/gthocsyirf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxbdvyfgz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zdqjudy.top/Article/details/gtdhsfmibh.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtlafzjvjt.html

N. 数据结构与算法
来源：http://dali.shuidangran.top/Article/details/gteslnvhry.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtuaqmvluk.html

[N01] 二分查找（有序数组）
来源：http://dali.hfpthk.cn/Article/details/gtagcxxvym.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtilsvgxjm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.guowangkeji.top/Article/details/gtpykmkuqz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hfpthk.cn/Article/details/gtagkttdxa.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.mhx1999.top/Article/details/gtlvbsqhje.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtckawxbbv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtwxrlefil.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinqigfzy.top/Article/details/gtxynvzwos.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ybcxt.top/Article/details/gttzxdydkt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jlsjyb.cn/Article/details/gtrknnvfcn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yvedp.cn/Article/details/gtzcvizwzz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sysykeji.top/Article/details/gtyvzqlvnu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangdashe.top/Article/details/gthbkfrjpn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangshuangyany.cn/Article/details/gtmwyhfjiy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.gaohongyu789.top/Article/details/gtqetqqnak.html

Go:   slices.Sort(arr)
来源：http://dali.xuanzx.com/Article/details/gtuevetjap.html

Ruby: arr.sort
来源：http://dali.xziqi.cn/Article/details/gtefiddbay.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.svipenyu.cn/Article/details/gtrxlbaxul.html

[N03] 快速排序（分治示例）
来源：http://dali.zhongyouzk.top/Article/details/gtccymjivh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xinyue.icu/Article/details/gtbtlwmxrf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhengqikj.top/Article/details/gtufguuvmf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gtzrvsuwjn.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinghuilouyu.cn/Article/details/gtrklzhvoi.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gtppoaisch.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.havefunace.top/Article/details/gtpezocndw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cucudq.cn/Article/details/gtxmpocmht.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xuetiantiany.cn/Article/details/gtagbrrgod.html

[N04] 斐波那契数列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwxzectyh.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nanxuanxn.top/Article/details/gtzkakivnp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ppjwa.cn/Article/details/gtllzwncso.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yangfankeji.com/Article/details/gtbfoiurmu.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hywenlv.cn/Article/details/gtrurmpbli.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yuanzhike.top/Article/details/gtvrfxxqnu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkdtqisfp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xylfe.cn/Article/details/gtshmammvy.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hysaishi.cn/Article/details/gtnbbiirez.html

[N05] 最大公约数
来源：http://dali.chenzaomai.com/Article/details/gtltvtbdlk.html

Py:   math.gcd(a, b)
来源：http://dali.yvedp.cn/Article/details/gtvhywcrko.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sufxvd.cn/Article/details/gtbugxlmhd.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwxfhggok.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.svipenyu.cn/Article/details/gtqsdcwunu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.meibo888.top/Article/details/gtpmcxdjrk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwcmiclds.html

Ruby: a.gcd(b)
来源：http://dali.hongshengwenyu.top/Article/details/gtdgrjjxis.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.tanke756.top/Article/details/gtymnnkfcp.html

[N06] 判断回文字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtnoudbjri.html

Py:   s == s[::-1]
来源：http://dali.wangshuangyany.cn/Article/details/gtxnjzrlvu.html

PHP:  $s === strrev($s);
来源：http://dali.xziqi.cn/Article/details/gtmzbkubfg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfyaeccqg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.bjfxy.top/Article/details/gtnugtxxoo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinqigufen.top/Article/details/gtviddtclq.html

Go:   // 双指针从两端比较
来源：http://dali.xinyue.icu/Article/details/gtormrsipr.html

Ruby: s == s.reverse
来源：http://dali.redwolf501.top/Article/details/gtzpxnqgvj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yj20258888.top/Article/details/gtpghlxryv.html

[N07] 两数之和（返回下标）
来源：http://dali.chenjidiqi.icu/Article/details/gtiekppjdd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yvedp.cn/Article/details/gtdiamdrtn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhaomingkeji.xyz/Article/details/gtilyjkafs.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.vqdsnc.cn/Article/details/gtjfxrrlbd.html

TS:   // 手写 Map<string, number>
来源：http://dali.hywenlv.cn/Article/details/gtqsguzull.html

Java: // 手写 HashMap
来源：http://dali.jqgfzy.top/Article/details/gtyekowalr.html

Go:   // 手写 map[int]int
来源：http://dali.cdnleiting.top/Article/details/gtuyywnahi.html

Ruby: // 手写 Hash
来源：http://dali.nanxinkj.top/Article/details/gtrpbmsyjw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.dianchejie.cn/Article/details/gtfuamlsdj.html

[N08] 生成全排列
来源：http://dali.daria6918.cn/Article/details/gtafbfkvha.html

Py:   itertools.permutations(arr)
来源：http://dali.guowangkeji.top/Article/details/gthexteurn.html

PHP:  // 手写递归交换
来源：http://dali.vqdsnc.cn/Article/details/gtxspowwpw.html

JS:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gtirnkajqn.html

TS:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gtmprbqeff.html

Java: // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gtgswwyrym.html

Go:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gthcisrxwp.html

Ruby: arr.permutation.to_a
来源：http://dali.pycfn.com/Article/details/gtfhwfachv.html

C#:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtkpyvjqyq.html

[N09] 栈与队列
来源：http://dali.guannengcc.top/Article/details/gtdwtyfkqn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbhxkzdlk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.wangdashe.top/Article/details/gtsevkgjxf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.316326.xyz/Article/details/gthkcrgjle.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.wangdashe.top/Article/details/gtkzrlrrav.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cashguo.top/Article/details/gtklwxyfwo.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hammf.cn/Article/details/gttspfijjn.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gtohjxvzmv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.quarkkingdee.top/Article/details/gtbcehjefu.html

[N10] 链表节点定义
来源：http://dali.jinqigufen.top/Article/details/gtoirgzwmv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hywenlv.cn/Article/details/gtdtjjwwob.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.havefunace.top/Article/details/gtjtdtwajp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jqgufenzy.top/Article/details/gtnjymqxfg.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yuxming.cn/Article/details/gtjrzfpome.html

Java: class Node { int v; Node next; }
来源：http://dali.zhoulong.xyz/Article/details/gtxypkvdnf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.snrcjt.cn/Article/details/gtniojbpyt.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.feifeiyinyue.top/Article/details/gtrvfuoxnf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shangyingyoupin.top/Article/details/gtyqoyqapa.html

[N11] 二叉树中序遍历
来源：http://dali.snrcjt.cn/Article/details/gtmwvoqfnh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yanxiufei.cn/Article/details/gtaawbgirp.html

PHP:  // 手写递归函数
来源：http://dali.gzhubu.top/Article/details/gthmvqsjoe.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.redwolf501.top/Article/details/gtqxtnrqij.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhiwuduotai.top/Article/details/gtlgcrbmti.html

Java: // 手写递归
来源：http://dali.iojbl.cn/Article/details/gtlcfawqlr.html

Go:   // 手写递归
来源：http://dali.yj202588.top/Article/details/gthhcipuar.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.redwolf501.top/Article/details/gtscoeumqk.html

C#:   // 手写递归
来源：http://dali.xuanzx.com/Article/details/gtnpnefvfd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.chenlongwang.top/Article/details/gtpuvedfsg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.kuanghao11.cn/Article/details/gtdmqqjagh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtslgfputx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.svipenyu.cn/Article/details/gthawyqwuv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuxming.cn/Article/details/gtgrmzrnpg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hfpthk.cn/Article/details/gtypkuggmc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.gotoacloud.top/Article/details/gtdflqglhn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.vqdsnc.cn/Article/details/gtqfmizpia.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guannengcc.top/Article/details/gtfecbexii.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtwgviytri.html

O. 并发与异步
来源：http://dali.fzhhl.top/Article/details/gtwxknuuby.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtayjvmhhb.html

[O01] 启动一个线程
来源：http://dali.jinqigfzy.top/Article/details/gtjhocuduh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jqgfzy.top/Article/details/gtywxqqpgx.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xinyue.icu/Article/details/gtvtffdwcn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhixingplan.top/Article/details/gtaggbbqdr.html

TS:   // 同 JS
来源：http://dali.yanxiufei.cn/Article/details/gtjgzgrzuf.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinghuilouyu.cn/Article/details/gtcbkkapus.html

Go:   go f()
来源：http://dali.cdnleiting.top/Article/details/gtanxqhtaf.html

Ruby: Thread.new { f }
来源：http://dali.hysaishi.cn/Article/details/gtvtpdnypa.html

C#:   Task.Run(() => F());
来源：http://dali.xuanzx.com/Article/details/gtbughpuuv.html

[O02] 使用线程池
来源：http://dali.dianchejie.cn/Article/details/gthzshulsy.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.guowangkeji.top/Article/details/gtrehupqfl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwwreiuvz.html

JS:   // worker_threads 线程池
来源：http://dali.zycfv.cn/Article/details/gthcgzhasv.html

TS:   // worker_threads 线程池
来源：http://dali.zycfv.cn/Article/details/gtmdbmdycu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.tian-w.cn/Article/details/gtqxdiyzfr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.fzhhl.top/Article/details/gtyceusxqw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xylfe.cn/Article/details/gtoqghirzp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yanxiufei.cn/Article/details/gtuusxjejs.html

[O03] 加锁保护共享数据
来源：http://dali.yj202588.top/Article/details/gtsyxikvoi.html

Py:   with lock: shared += 1
来源：http://dali.dianchejie.cn/Article/details/gtuygmihfi.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hnqzz.top/Article/details/gtxwzxldtd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.meibo888.top/Article/details/gtwzucrpji.html

TS:   // 同 JS
来源：http://dali.yonumen.top/Article/details/gtihqqutko.html

Java: synchronized (this) { shared++; }
来源：http://dali.daria6918.cn/Article/details/gtxztapldb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zdqjudy.top/Article/details/gtstfmtydt.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.guannengcc.top/Article/details/gtmygjutzh.html

C#:   lock (gate) { shared++; }
来源：http://dali.dianchejie.cn/Article/details/gtdwczhnsm.html

[O04] 定义异步函数并等待
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlesovwgr.html

Py:   async def f():⏎    await g()
来源：http://dali.sxryk.cn/Article/details/gtfwhrscvg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.birdmap.top/Article/details/gtgmtgvuhm.html

JS:   async function f() { await g(); }
来源：http://dali.hammf.cn/Article/details/gttnfffwiq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.snrcjt.cn/Article/details/gtneqbkvpz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yangfankeji.com/Article/details/gtxepxghwy.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sysykeji.top/Article/details/gtawnrgbbg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gaohongyu789.top/Article/details/gtwnhqjnlq.html

C#:   async Task F() { await G(); }
来源：http://dali.yj202588.top/Article/details/gtykisloph.html

[O05] 并发执行并等待全部完成
来源：http://dali.c1oappe.top/Article/details/gtjcrxxisj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.haohaochexian.top/Article/details/gtgecfaewb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.pengpengdd.cyou/Article/details/gtjikbeyfl.html

JS:   await Promise.all(tasks)
来源：http://dali.feifeiyinyue.top/Article/details/gtjbvmuszp.html

TS:   await Promise.all(tasks)
来源：http://dali.wangdashe.top/Article/details/gtxifuwjyp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.kuanghao11.cn/Article/details/gtxrgxdvdn.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yangfankeji.com/Article/details/gtpmqjhdvy.html

Ruby: threads.map(&:join)
来源：http://dali.sufxvd.cn/Article/details/gtynfmrqhn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.wangshuangyany.cn/Article/details/gtmiylvtzt.html

[O06] 使用进程池
来源：http://dali.0kj1m.cn/Article/details/gtaqfbrhgo.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.guowangkeji.top/Article/details/gtrrktnzhk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jqgfzy.top/Article/details/gtwbmdqajc.html

JS:   // child_process / cluster 模块
来源：http://dali.jqgufenzy.top/Article/details/gttqykqxxt.html

TS:   // child_process / cluster 模块
来源：http://dali.zycfv.cn/Article/details/gtdsidcsoj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yongpay.top/Article/details/gtldjnqaqy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hfpthk.cn/Article/details/gtqpdczark.html

Ruby: // fork 块
来源：http://dali.zdqjudy.top/Article/details/gtclhlcwst.html

C#:   Parallel.For
来源：http://dali.dashuyun.cn/Article/details/gthxrwbtgo.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtjaxucdjj.html

P. 常用工具函数
来源：http://dali.mhx1999.top/Article/details/gtftkqhkys.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtqptdrxlm.html

[P01] 生成 UUID
来源：http://dali.haohaochexian.top/Article/details/gtkmfodbvw.html

Py:   str(uuid.uuid4())
来源：http://dali.pycfn.com/Article/details/gtybtztgcz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hammf.cn/Article/details/gtrognnxnl.html

JS:   crypto.randomUUID()
来源：http://dali.cashguo.top/Article/details/gtnzropkgp.html

TS:   crypto.randomUUID()
来源：http://dali.iojbl.cn/Article/details/gtclgooazq.html

Java: UUID.randomUUID().toString()
来源：http://dali.pengpengdd.cyou/Article/details/gtoyffxhpi.html

Go:   // 用 github.com/google/uuid
来源：http://dali.chenjidiqi.icu/Article/details/gtkdustgxa.html

Ruby: SecureRandom.uuid
来源：http://dali.yj202588.top/Article/details/gtndkaeldl.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zdqjudy.top/Article/details/gthtribfcn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.guowangkeji.top/Article/details/gtxgsqwokv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.nanxinkj.top/Article/details/gtifvbegft.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.redwolf501.top/Article/details/gtjpsfzyts.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.fzhhl.top/Article/details/gtailkfhfb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhiwuduotai.top/Article/details/gthxmcehnr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhengqikj.top/Article/details/gtcayosduu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.vqdsnc.cn/Article/details/gtattxnyog.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jianghu66.top/Article/details/gtkxvhosts.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhixingplan.top/Article/details/gtmqlaxxsj.html

[P03] 生成短随机字符串
来源：http://dali.cucudq.cn/Article/details/gtrpgckufw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.snrcjt.cn/Article/details/gtmtbbrreq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.gaohongyu789.top/Article/details/gteijwfqyl.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtpyuwveda.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.guowangkeji.top/Article/details/gtjnmddwni.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jiagoushi.top/Article/details/gtyuainpan.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.quarkkingdee.top/Article/details/gtzrjkkgvw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shuidangran.top/Article/details/gtgrououqz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.smart0.xyz/Article/details/gtvqvedami.html

[P04] 求长度
来源：http://dali.hammf.cn/Article/details/gtrqkzbtei.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.snrcjt.cn/Article/details/gttibtzxwg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gtuiqgjfbg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hysaishi.cn/Article/details/gtxislspal.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.andypj.xyz/Article/details/gtzrsdieeg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yj20258888.top/Article/details/gtojqfuvkw.html

Go:   len(arr);  len(m)
来源：http://dali.dianchejie.cn/Article/details/gtmupngpjv.html

Ruby: x.length;  x.size
来源：http://dali.vqdsnc.cn/Article/details/gtkgpgifjv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyiekxqqc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqjslqmxx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xuanzx.com/Article/details/gtjwgnixcz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hywenlv.cn/Article/details/gtghbsnivn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hfpthk.cn/Article/details/gtetspobfn.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtamcmzloz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ppjwa.cn/Article/details/gtfkbpkakb.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ybcxt.top/Article/details/gtenpoxuwm.html

Ruby: a == b
来源：http://dali.havefunace.top/Article/details/gtyfeqdzwo.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.gotoacloud.top/Article/details/gtaqcveiru.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.chenzaomai.com/Article/details/gtzyiwgavd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyifxvamz.html

PHP:  if (empty($x)) {}
来源：http://dali.yuanzhike.top/Article/details/gtityczgnz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ybcxt.top/Article/details/gtrffobkpn.html

TS:   if (x == null) {}
来源：http://dali.jinqigufen.top/Article/details/gtntruxmny.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtlyhkpgci.html

Go:   if x == nil {}
来源：http://dali.cdnleiting.top/Article/details/gtdjzfqwwc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzcmpvsyg.html

C#:   if (x is null) {}
来源：http://dali.guannengcc.top/Article/details/gtydurwbhf.html

[P07] 防抖与节流
来源：http://dali.shuidangran.top/Article/details/gtqthwlego.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hfpthk.cn/Article/details/gtpcmobwas.html

PHP:  // 手写时间戳比较
来源：http://dali.nanxuanxn.top/Article/details/gtjlizvwci.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jiagoushi.top/Article/details/gtgmsiqhsv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.andypj.xyz/Article/details/gtyopspazy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtgjkotzsw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hongshengwenyu.top/Article/details/gtfvcudonb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhoulong.xyz/Article/details/gtzcydqkoj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.redwolf501.top/Article/details/gttjqoyubm.html

[P08] 处理浮点精度问题
来源：http://dali.fzhhl.top/Article/details/gtdyghoihl.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinqigfzy.top/Article/details/gthlufsymg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.guannengcc.top/Article/details/gtjkgkyzxe.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ehwqpu.com/Article/details/gtphmluagm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtoxgdzcmn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.daxiang520.top/Article/details/gtzojtkaaa.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xylfe.cn/Article/details/gtnqgylmbb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gtphxgetjc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.kuanghao11.cn/Article/details/gtvoiktpov.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtzfjuuccp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shzxlz.cn/Article/details/gtqkcpdnzk.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtvmugbewz.html

[Q01] 创建表
来源：http://dali.chenlongwang.top/Article/details/gtovexvygb.html

CREATE TABLE users (
来源：http://dali.jinghuilouyu.cn/Article/details/gtsjylpofi.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.quarkkingdee.top/Article/details/gtpsnfamyz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.birdmap.top/Article/details/gtghzaipzq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cheryme.top/Article/details/gtvpxhtfqe.html


<!-- 参考信息 -->