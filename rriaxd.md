代发 wailian999

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ydzc1.top/Article/details/gtckmgapwu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jqgufenzy.top/Article/details/gtjsltcrkz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shanyushiyangtech.top/Article/details/gthelgdlec.html

C#:   Process.Start("ls", "-l");
来源：http://dali.haohaochexian.top/Article/details/gtndreyuxo.html

[M04] 获取当前工作目录
来源：http://dali.zhengqikj.top/Article/details/gtewswatix.html

Py:   os.getcwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvtkqbdyy.html

PHP:  getcwd();
来源：http://dali.cucudq.cn/Article/details/gtpkazccyx.html

JS:   process.cwd()
来源：http://dali.jyoumei.cn/Article/details/gtbntqbtdx.html

TS:   process.cwd()
来源：http://dali.gogol.net.cn/Article/details/gtqyohlhxo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhengqikj.top/Article/details/gttdclfezo.html

Go:   os.Getwd()
来源：http://dali.cqqwz.cn/Article/details/gtnjifbmvy.html

Ruby: Dir.pwd
来源：http://dali.jlsjyb.cn/Article/details/gtnozavukn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.fzhhl.top/Article/details/gtehjkakxy.html

[M05] 设置退出码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtavivlwzl.html

Py:   sys.exit(1)
来源：http://dali.gzhubu.top/Article/details/gtvntlfdzc.html

PHP:  exit(1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtldmwsscy.html

JS:   process.exit(1)
来源：http://dali.yuxming.cn/Article/details/gtsbdbsuto.html

TS:   process.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtwdhijmtw.html

Java: System.exit(1)
来源：http://dali.yueranfly.top/Article/details/gthfpsgdbp.html

Go:   os.Exit(1)
来源：http://dali.hnqzz.top/Article/details/gtdxcrhkwd.html

Ruby: exit 1
来源：http://dali.hammf.cn/Article/details/gtvfigzunm.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jqgfzy.top/Article/details/gtpicwkezx.html

[M06] 向标准错误输出
来源：http://dali.xylfe.cn/Article/details/gtxethxdew.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zdqjudy.top/Article/details/gtgktvveid.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhongyouzk.top/Article/details/gtzdtqsgxz.html

JS:   console.error("err")
来源：http://dali.zdqjudy.top/Article/details/gtqedeahtl.html

TS:   console.error("err")
来源：http://dali.jinqigufen.top/Article/details/gtfqzowbnr.html

Java: System.err.println("err")
来源：http://dali.yj20258888.top/Article/details/gtsjssyvmq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shangyingyoupin.top/Article/details/gteievtsin.html

Ruby: warn "err"
来源：http://dali.xuetiantiany.cn/Article/details/gtkuhsccov.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hfpthk.cn/Article/details/gtaudpkzng.html

[M07] 判断是否为主入口
来源：http://dali.zycfv.cn/Article/details/gttsnkywnw.html

Py:   if __name__ == "__main__":
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjoonmslh.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtnbgvynow.html

JS:   require.main === module
来源：http://dali.shangyingyoupin.top/Article/details/gtfmopvvcm.html

TS:   require.main === module
来源：http://dali.shanyushiyangtech.top/Article/details/gticbivzqw.html

Java: public static void main(String[] args)
来源：http://dali.guannengcc.top/Article/details/gtxhtpubkr.html

Go:   func main()
来源：http://dali.svipenyu.cn/Article/details/gtwrtqmxgy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xylfe.cn/Article/details/gtdkqnemef.html

C#:   static void Main(string[] args)
来源：http://dali.vqdsnc.cn/Article/details/gteyuxxdcp.html

[M08] 获取系统与运行时信息
来源：http://dali.gotoacloud.top/Article/details/gtaylsrwfs.html

Py:   platform.system();  platform.python_version()
来源：http://dali.havefunace.top/Article/details/gtlotychty.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yueranfly.top/Article/details/gthnquxhrp.html

JS:   process.platform;  process.version
来源：http://dali.yongpay.top/Article/details/gtwdilphxd.html

TS:   process.platform;  process.version
来源：http://dali.dashuyun.cn/Article/details/gtvruwmuui.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sweek.top/Article/details/gtihvfjxdc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yvedp.cn/Article/details/gtqbnzcirt.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhongyouzk.top/Article/details/gteiphziwo.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.chenzaomai.com/Article/details/gthnjxvvpn.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtkqbtbnpy.html

N. 数据结构与算法
来源：http://dali.zhengqikj.top/Article/details/gtkzyehywi.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtokmyyjkj.html

[N01] 二分查找（有序数组）
来源：http://dali.guowangkeji.top/Article/details/gtkjqtvodq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gthtgmszya.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xuanzx.com/Article/details/gtertrmvcs.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tianlin.xyz/Article/details/gtkwmqruej.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgufenzy.top/Article/details/gthekumlmy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtuxdulrvj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwowfvhfg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.andypj.xyz/Article/details/gtbzldmnnm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yonumen.top/Article/details/gtjkxbxoyk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gotoacloud.top/Article/details/gtofndsghk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnqzz.top/Article/details/gtlintogqs.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xuanzx.com/Article/details/gtwjguwoow.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.haohaochexian.top/Article/details/gtmefkytij.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yangfankeji.com/Article/details/gtlpoizscs.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhoulong.xyz/Article/details/gtavouhfru.html

Go:   slices.Sort(arr)
来源：http://dali.316326.xyz/Article/details/gtehwangth.html

Ruby: arr.sort
来源：http://dali.yanxiufei.cn/Article/details/gtlbhvzyon.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.sufxvd.cn/Article/details/gthjgbivuq.html

[N03] 快速排序（分治示例）
来源：http://dali.gaohongyu789.top/Article/details/gtynamhtog.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.daxiang520.top/Article/details/gtlotitgko.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xziqi.cn/Article/details/gtqutubjbv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xinyue.icu/Article/details/gtjhzcacvl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigfzy.top/Article/details/gtfnsicleh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.pengpengdd.cyou/Article/details/gtdyszgzsw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenlongwang.top/Article/details/gtmizyoine.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shuidangran.top/Article/details/gtwkrzfdcs.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yanxiufei.cn/Article/details/gtfuduasnj.html

[N04] 斐波那契数列
来源：http://dali.hongshengwenyu.top/Article/details/gtxwgfoxui.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gzhubu.top/Article/details/gtintmactv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gtrzbkhmfz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj20258888.top/Article/details/gtaxgawhor.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hammf.cn/Article/details/gtxkwvpymi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtuqbeempx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yj20258888.top/Article/details/gtvqwaoslc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.dianchejie.cn/Article/details/gtiawyxuzu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yueranfly.top/Article/details/gtgkvvljki.html

[N05] 最大公约数
来源：http://dali.mhx1999.top/Article/details/gtqelahgmk.html

Py:   math.gcd(a, b)
来源：http://dali.redwolf501.top/Article/details/gtorslmxta.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.meibo888.top/Article/details/gtewblmkbp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guannengcc.top/Article/details/gtorfwrurc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hywenlv.cn/Article/details/gtwcakecpt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yvedp.cn/Article/details/gtvihfcddj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.guowangkeji.top/Article/details/gtkdsanhez.html

Ruby: a.gcd(b)
来源：http://dali.hongshengwenyu.top/Article/details/gtdnatfvij.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.quarkkingdee.top/Article/details/gtglmyhpod.html

[N06] 判断回文字符串
来源：http://dali.hammf.cn/Article/details/gtmehhyvyd.html

Py:   s == s[::-1]
来源：http://dali.zdqjudy.top/Article/details/gtqkvjkppu.html

PHP:  $s === strrev($s);
来源：http://dali.haohaochexian.top/Article/details/gtmajtsory.html

JS:   s === [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gtkpudszyx.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gtlpciqczm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxclgqzch.html

Go:   // 双指针从两端比较
来源：http://dali.tianlin.xyz/Article/details/gtjapiqdbl.html

Ruby: s == s.reverse
来源：http://dali.shzxlz.cn/Article/details/gtvxwerkta.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.fzhhl.top/Article/details/gtcvkokhxy.html

[N07] 两数之和（返回下标）
来源：http://dali.zdqjudy.top/Article/details/gtlsimaugg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jqgufenzy.top/Article/details/gtwmalnuuv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ybcxt.top/Article/details/gtmukwussm.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gtpnlthnav.html

TS:   // 手写 Map<string, number>
来源：http://dali.shzxlz.cn/Article/details/gtgnqwsouu.html

Java: // 手写 HashMap
来源：http://dali.fzhhl.top/Article/details/gtylxytbsb.html

Go:   // 手写 map[int]int
来源：http://dali.andypj.xyz/Article/details/gtclvcakmj.html

Ruby: // 手写 Hash
来源：http://dali.9152youxi.cn/Article/details/gtbiltcxwc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.316326.xyz/Article/details/gtvkxepkif.html

[N08] 生成全排列
来源：http://dali.hnqzz.top/Article/details/gtzzxhcrnl.html

Py:   itertools.permutations(arr)
来源：http://dali.xziqi.cn/Article/details/gtztbwbzfx.html

PHP:  // 手写递归交换
来源：http://dali.sxryk.cn/Article/details/gtoefqyopg.html

JS:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gtshnltijy.html

TS:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gtlrgwkgup.html

Java: // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gtatkyieba.html

Go:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gtvlaevdap.html

Ruby: arr.permutation.to_a
来源：http://dali.zhengqikj.top/Article/details/gttvhtkmwx.html

C#:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gtiaolnltv.html

[N09] 栈与队列
来源：http://dali.ydzc1.top/Article/details/gtkkosyarv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.c1oappe.top/Article/details/gtxpnihmxs.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gtxezifuyf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcwrbwxlh.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhiwuduotai.top/Article/details/gtzqzicaau.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.meibo888.top/Article/details/gtbzygztms.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.redwolf501.top/Article/details/gtabixrxfy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.guannengcc.top/Article/details/gtrnbpoqlh.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj202588.top/Article/details/gtohoehdru.html

[N10] 链表节点定义
来源：http://dali.chenjidiqi.icu/Article/details/gttowdodkj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shuidangran.top/Article/details/gturiigdfl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.0kj1m.cn/Article/details/gtbwcpnetg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yuanzhike.top/Article/details/gtlrthqhlv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xuetiantiany.cn/Article/details/gtqnqbzxbx.html

Java: class Node { int v; Node next; }
来源：http://dali.sufxvd.cn/Article/details/gtvkfsmqio.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yuanzhike.top/Article/details/gtoujscyza.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.andypj.xyz/Article/details/gtiseazbds.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hysaishi.cn/Article/details/gtuxehqwbx.html

[N11] 二叉树中序遍历
来源：http://dali.quarkkingdee.top/Article/details/gtchwtkpvg.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yj20258.top/Article/details/gtculjqlsn.html

PHP:  // 手写递归函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtzbwhssau.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daxiang520.top/Article/details/gtrejobqgl.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigufen.top/Article/details/gtfsuxggyd.html

Java: // 手写递归
来源：http://dali.yuanzhike.top/Article/details/gtpbvulzrz.html

Go:   // 手写递归
来源：http://dali.ehwqpu.com/Article/details/gtraoldmdc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.aibaodan.cn/Article/details/gtdnvmxzee.html

C#:   // 手写递归
来源：http://dali.yj202588.top/Article/details/gtosymgqal.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gogol.net.cn/Article/details/gtdoltcmgi.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.fengsongda.top/Article/details/gtqipobcih.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkmvsmskg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dianchejie.cn/Article/details/gtfssvrkab.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shuidangran.top/Article/details/gtvufksnfy.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenlongwang.top/Article/details/gtzjkimtge.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xylfe.cn/Article/details/gtikoqahbm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yonumen.top/Article/details/gtuyakhnkz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenlongwang.top/Article/details/gteakphwqs.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtrgonduym.html

O. 并发与异步
来源：http://dali.yuanzhike.top/Article/details/gteitibbcg.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtnaaarbqv.html

[O01] 启动一个线程
来源：http://dali.xylfe.cn/Article/details/gtskhhivmp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ivvv.top/Article/details/gtzcjxiuhh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jyoumei.cn/Article/details/gtvuzfxmyb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cheryme.top/Article/details/gtvuuqmebc.html

TS:   // 同 JS
来源：http://dali.vqdsnc.cn/Article/details/gtncpnhaij.html

Java: new Thread(() -> f()).start()
来源：http://dali.yangfankeji.com/Article/details/gtzvarvfgh.html

Go:   go f()
来源：http://dali.daxiang520.top/Article/details/gtcinxstgc.html

Ruby: Thread.new { f }
来源：http://dali.gzhubu.top/Article/details/gtrmuehkig.html

C#:   Task.Run(() => F());
来源：http://dali.yuxming.cn/Article/details/gtnhpqnfkr.html

[O02] 使用线程池
来源：http://dali.zhoulong.xyz/Article/details/gthgxecmqp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.fengsongda.top/Article/details/gtcvpssymj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.vqdsnc.cn/Article/details/gtplxkesnk.html

JS:   // worker_threads 线程池
来源：http://dali.jyoumei.cn/Article/details/gtkuhtuouh.html

TS:   // worker_threads 线程池
来源：http://dali.hywenlv.cn/Article/details/gtxjfwakwy.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cqqwz.cn/Article/details/gtzqckzreq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.meibo888.top/Article/details/gtqcbsdnxa.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xuetiantiany.cn/Article/details/gthnaauxoh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xuetiantiany.cn/Article/details/gtmnfrfnxe.html

[O03] 加锁保护共享数据
来源：http://dali.ppjwa.cn/Article/details/gtnitlwyng.html

Py:   with lock: shared += 1
来源：http://dali.9152youxi.cn/Article/details/gtzebvjvdl.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.pengpengdd.cyou/Article/details/gthxfmmuoq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.fengsongda.top/Article/details/gtopxgvesu.html

TS:   // 同 JS
来源：http://dali.redwolf501.top/Article/details/gtcefsnteg.html

Java: synchronized (this) { shared++; }
来源：http://dali.yongpay.top/Article/details/gtcriwmcfi.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.nwbrower.top/Article/details/gtwoasnojr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hfpthk.cn/Article/details/gtyeafremd.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhiwuduotai.top/Article/details/gttmllkovd.html

[O04] 定义异步函数并等待
来源：http://dali.jiagoushi.top/Article/details/gtuquiuifp.html

Py:   async def f():⏎    await g()
来源：http://dali.yj20258.top/Article/details/gtzqcbiniv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.0kj1m.cn/Article/details/gtxozxqbwr.html

JS:   async function f() { await g(); }
来源：http://dali.kuanghao11.cn/Article/details/gtgiidslto.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinqigufen.top/Article/details/gtmkvgsclh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cashguo.top/Article/details/gtuvbuvpsq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.tianlin.xyz/Article/details/gtbzvkevmf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.316326.xyz/Article/details/gtrdzdscnk.html

C#:   async Task F() { await G(); }
来源：http://dali.hysaishi.cn/Article/details/gtvtzxksiq.html

[O05] 并发执行并等待全部完成
来源：http://dali.316326.xyz/Article/details/gtxomhcmfo.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hongshengwenyu.top/Article/details/gtkpytuxjb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.iojbl.cn/Article/details/gtdlwetmcs.html

JS:   await Promise.all(tasks)
来源：http://dali.guowangkeji.top/Article/details/gtcvybgdxt.html

TS:   await Promise.all(tasks)
来源：http://dali.sxryk.cn/Article/details/gtqvwpkvmp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hnqzz.top/Article/details/gtqeijdctu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqdbittfm.html

Ruby: threads.map(&:join)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtregcloxe.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xuanzx.com/Article/details/gtgbhxonrf.html

[O06] 使用进程池
来源：http://dali.mhx1999.top/Article/details/gtmiwibedo.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.tianlin.xyz/Article/details/gtbyrkyfoo.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yongpay.top/Article/details/gtwldfwase.html

JS:   // child_process / cluster 模块
来源：http://dali.jqgfzy.top/Article/details/gtaukfxlks.html

TS:   // child_process / cluster 模块
来源：http://dali.jqgfzy.top/Article/details/gtajbtvjco.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.andypj.xyz/Article/details/gtggruoxia.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.wangshuangyany.cn/Article/details/gttvgqvrlo.html

Ruby: // fork 块
来源：http://dali.tianlin.xyz/Article/details/gtcgpmsift.html

C#:   Parallel.For
来源：http://dali.chenzaomai.com/Article/details/gtanyhmysl.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtggpoomhq.html

P. 常用工具函数
来源：http://dali.xylfe.cn/Article/details/gtlikxujvk.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtyjstqlgv.html

[P01] 生成 UUID
来源：http://dali.feifeiyinyue.top/Article/details/gtnayqlldf.html

Py:   str(uuid.uuid4())
来源：http://dali.hnxiangtu.top/Article/details/gtyjdhlcnd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yanxiufei.cn/Article/details/gtpmtnurbl.html

JS:   crypto.randomUUID()
来源：http://dali.hnqzz.top/Article/details/gttzpvekgk.html

TS:   crypto.randomUUID()
来源：http://dali.dashuyun.cn/Article/details/gtvycsicmy.html

Java: UUID.randomUUID().toString()
来源：http://dali.birdmap.top/Article/details/gtczczgnba.html

Go:   // 用 github.com/google/uuid
来源：http://dali.chenjidiqi.icu/Article/details/gtdfkvvobu.html

Ruby: SecureRandom.uuid
来源：http://dali.ybcxt.top/Article/details/gtcoyqcqtt.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ivvv.top/Article/details/gtxvttvxkn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jqgufenzy.top/Article/details/gtblbfimty.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.tanke756.top/Article/details/gtntkkytsp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sufxvd.cn/Article/details/gthhpkdkil.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.9152youxi.cn/Article/details/gtksebyhys.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gzhubu.top/Article/details/gtkvdyfkgo.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsjyhwvrc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.tianlin.xyz/Article/details/gtngowbgdt.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yj20258.top/Article/details/gtufrkbcuh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.redwolf501.top/Article/details/gtounpxzcm.html

[P03] 生成短随机字符串
来源：http://dali.iojbl.cn/Article/details/gtavrzrjyo.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yonumen.top/Article/details/gthpvlkgvr.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.nanxinkj.top/Article/details/gtxhdbjxdl.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daria6918.cn/Article/details/gtstsauzus.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aizwys.cn/Article/details/gtitmmiium.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jyoumei.cn/Article/details/gtjadceiwv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ehwqpu.com/Article/details/gtmxfjanfm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jiagoushi.top/Article/details/gtehuyyzcw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.tanke756.top/Article/details/gtvssgvmic.html

[P04] 求长度
来源：http://dali.hammf.cn/Article/details/gtaohkvihc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hysaishi.cn/Article/details/gtfehzaaxj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gtfajbskux.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cheryme.top/Article/details/gtbwjbfhfr.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cashguo.top/Article/details/gtlkezkwph.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yongpay.top/Article/details/gtzblvmeuk.html

Go:   len(arr);  len(m)
来源：http://dali.jqgufenzy.top/Article/details/gtndhdjxoz.html

Ruby: x.length;  x.size
来源：http://dali.hammf.cn/Article/details/gtmajchtzt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jqgufenzy.top/Article/details/gtcsnokalc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.daria6918.cn/Article/details/gtuepzfaer.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrdvogwbl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ydzc1.top/Article/details/gtpwrkcwjb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.quarkkingdee.top/Article/details/gtuiyimnyl.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.daxiang520.top/Article/details/gtychhyadc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zycfv.cn/Article/details/gtqndjimeg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.fengsongda.top/Article/details/gtxeyciuoa.html

Ruby: a == b
来源：http://dali.yongpay.top/Article/details/gtoavivmyx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yuxming.cn/Article/details/gtekyudtzr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yuxming.cn/Article/details/gtjzsurqla.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gzhubu.top/Article/details/gtyrutjsub.html

PHP:  if (empty($x)) {}
来源：http://dali.iojbl.cn/Article/details/gtzzghkgbg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yj202588.top/Article/details/gtyphswxij.html

TS:   if (x == null) {}
来源：http://dali.xuanzx.com/Article/details/gtbkghwyic.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtkmeaambs.html

Go:   if x == nil {}
来源：http://dali.smart0.xyz/Article/details/gtggegxnzr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzlqodksw.html

C#:   if (x is null) {}
来源：http://dali.hysaishi.cn/Article/details/gtkzxdzhlt.html

[P07] 防抖与节流
来源：http://dali.jqgufenzy.top/Article/details/gtfuooglgm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.wangdashe.top/Article/details/gtjbjxirmd.html

PHP:  // 手写时间戳比较
来源：http://dali.cashguo.top/Article/details/gtjpdfpbnv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hongshengwenyu.top/Article/details/gtgwltnyre.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.bjfxy.top/Article/details/gtjdpfhifa.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.tanke756.top/Article/details/gtknxtceto.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hnqzz.top/Article/details/gtrwraucgx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yueranfly.top/Article/details/gtwumjihnc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthihoxort.html

[P08] 处理浮点精度问题
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxqalqnlb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzpehndqs.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.9152youxi.cn/Article/details/gthquxckyt.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cashguo.top/Article/details/gtzioyhmzn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.guannengcc.top/Article/details/gtteknftsu.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.chenlongwang.top/Article/details/gtwtgfkctf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shangyingyoupin.top/Article/details/gtfehhvetn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hammf.cn/Article/details/gtlboowxxu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shanyushiyangtech.top/Article/details/gtgrihdxbc.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gteqojypcf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.chenjidiqi.icu/Article/details/gtikfpfped.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtaytqefvh.html

[Q01] 创建表
来源：http://dali.0kj1m.cn/Article/details/gttgkynytk.html

CREATE TABLE users (
来源：http://dali.ydzc1.top/Article/details/gtiwatkqqu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cqqwz.cn/Article/details/gtcjzlyekv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yj20258.top/Article/details/gtfqbagtvv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.kuanghao11.cn/Article/details/gtvijncydw.html


<!-- 参考信息 -->