代发 wailian999

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhongyouzk.top/Article/details/gtpatoosaz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ppjwa.cn/Article/details/gtmvwutdej.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.aibaodan.cn/Article/details/gtalytitln.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.0kj1m.cn/Article/details/gtorwvpmst.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.mhx1999.top/Article/details/gtnukdvtnj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.wangshuangyany.cn/Article/details/gthmpxtoqb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ehwqpu.com/Article/details/gtndgqpmzz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hammf.cn/Article/details/gtznackhmm.html

[M04] 获取当前工作目录
来源：http://dali.yanxiufei.cn/Article/details/gtwphexpui.html

Py:   os.getcwd()
来源：http://dali.hnxiangtu.top/Article/details/gthqsbqnrl.html

PHP:  getcwd();
来源：http://dali.cheryme.top/Article/details/gtpybaqrze.html

JS:   process.cwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gteonsuifi.html

TS:   process.cwd()
来源：http://dali.nwbrower.top/Article/details/gtuhsmbmnj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxsattyqt.html

Go:   os.Getwd()
来源：http://dali.andypj.xyz/Article/details/gtahppwnhj.html

Ruby: Dir.pwd
来源：http://dali.ydzc1.top/Article/details/gtnktowlur.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.quarkkingdee.top/Article/details/gtzbirlouq.html

[M05] 设置退出码
来源：http://dali.nwbrower.top/Article/details/gtkyexmmal.html

Py:   sys.exit(1)
来源：http://dali.zycfv.cn/Article/details/gtykqgakcm.html

PHP:  exit(1);
来源：http://dali.shuidangran.top/Article/details/gtyengfbqd.html

JS:   process.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtqauwwmpv.html

TS:   process.exit(1)
来源：http://dali.hammf.cn/Article/details/gtzraavksj.html

Java: System.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gtxefrxnnv.html

Go:   os.Exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtvwyhcvnh.html

Ruby: exit 1
来源：http://dali.yuanzhike.top/Article/details/gtxrqdbcxo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.feifeiyinyue.top/Article/details/gtvdehqntw.html

[M06] 向标准错误输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbqpfxthd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhengqikj.top/Article/details/gtmkcjevzl.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.redwolf501.top/Article/details/gtaaenuoyt.html

JS:   console.error("err")
来源：http://dali.zhixingplan.top/Article/details/gtgnphthbw.html

TS:   console.error("err")
来源：http://dali.ppjwa.cn/Article/details/gtsjzlagon.html

Java: System.err.println("err")
来源：http://dali.haohaochexian.top/Article/details/gtkgeqjmrl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.bjfxy.top/Article/details/gtbblkvgbc.html

Ruby: warn "err"
来源：http://dali.cdnleiting.top/Article/details/gtjebqcvyl.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sweek.top/Article/details/gtvcpxudpm.html

[M07] 判断是否为主入口
来源：http://dali.yonumen.top/Article/details/gtljnkygpl.html

Py:   if __name__ == "__main__":
来源：http://dali.shuidangran.top/Article/details/gtbknepiih.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.andypj.xyz/Article/details/gtdlyimxwk.html

JS:   require.main === module
来源：http://dali.gaohongyu789.top/Article/details/gtkhyfttsl.html

TS:   require.main === module
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkoddxtrd.html

Java: public static void main(String[] args)
来源：http://dali.sweek.top/Article/details/gtehhgwzpz.html

Go:   func main()
来源：http://dali.xylfe.cn/Article/details/gtqyyxdtkx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ivvv.top/Article/details/gtqmjuiksl.html

C#:   static void Main(string[] args)
来源：http://dali.yj20258.top/Article/details/gtfzmhaiem.html

[M08] 获取系统与运行时信息
来源：http://dali.kuanghao11.cn/Article/details/gtgvklwerh.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xuanzx.com/Article/details/gtzxjhgthr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.svipenyu.cn/Article/details/gtdzkzknrn.html

JS:   process.platform;  process.version
来源：http://dali.nwbrower.top/Article/details/gtasgkpioo.html

TS:   process.platform;  process.version
来源：http://dali.aibaodan.cn/Article/details/gtmjkhjwvh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jlsjyb.cn/Article/details/gtfropetkq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.smart0.xyz/Article/details/gtkwmzfqhn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhoulong.xyz/Article/details/gtzvjtbifg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.meibo888.top/Article/details/gtmhevhntd.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyzjiocfw.html

N. 数据结构与算法
来源：http://dali.yangfankeji.com/Article/details/gtpnyrbkit.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnyogeyzc.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gtdsdagbjj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yonumen.top/Article/details/gtadrwlvcd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbdhuvtrt.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.andypj.xyz/Article/details/gtzvuntvml.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sweek.top/Article/details/gtgjhroquz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtqejfkkhn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtsiskiyfi.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.tianlin.xyz/Article/details/gtthbfumgq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtbeuiakeb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.kuanghao11.cn/Article/details/gtidhtkcmd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gtpkxzmgqf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.haohaochexian.top/Article/details/gttdguegga.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yueranfly.top/Article/details/gtmdftjddh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yonumen.top/Article/details/gtrufbmkve.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinqigfzy.top/Article/details/gtlzodyseg.html

Go:   slices.Sort(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtxjfemgqv.html

Ruby: arr.sort
来源：http://dali.birdmap.top/Article/details/gtgtpdadnx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.fengsongda.top/Article/details/gtfmupphrv.html

[N03] 快速排序（分治示例）
来源：http://dali.hywenlv.cn/Article/details/gtuueuxorh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hysaishi.cn/Article/details/gtsxzzivvb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ydzc1.top/Article/details/gtdjdwqnrp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yueranfly.top/Article/details/gtdguzwtlc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yanxiufei.cn/Article/details/gtcxgvllam.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xuanzx.com/Article/details/gtykleksux.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.wangshuangyany.cn/Article/details/gtolfxcmzq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xylfe.cn/Article/details/gtvpubtmxe.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.quarkkingdee.top/Article/details/gtzfccxror.html

[N04] 斐波那契数列
来源：http://dali.daria6918.cn/Article/details/gtmrozapcj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yvedp.cn/Article/details/gtsidhfwqu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gaohongyu789.top/Article/details/gtlmrlifix.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hongshengwenyu.top/Article/details/gttyuvnuiw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtmultuocs.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.redwolf501.top/Article/details/gtgkpfnuxt.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cashguo.top/Article/details/gtrdyaydxh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtaffwywae.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gtfdxijrqa.html

[N05] 最大公约数
来源：http://dali.hfpthk.cn/Article/details/gttzueadjs.html

Py:   math.gcd(a, b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlijgrtfo.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtencyawdm.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ppjwa.cn/Article/details/gtgzvmeacf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yongpay.top/Article/details/gtfajuyykm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yj20258888.top/Article/details/gtbyvnbyxq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jyoumei.cn/Article/details/gtusxumnvt.html

Ruby: a.gcd(b)
来源：http://dali.gzhubu.top/Article/details/gtvywdtjlr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.tianlin.xyz/Article/details/gtoklkqpub.html

[N06] 判断回文字符串
来源：http://dali.bjfxy.top/Article/details/gtlrftvxkv.html

Py:   s == s[::-1]
来源：http://dali.chenzaomai.com/Article/details/gtoqzsmpyi.html

PHP:  $s === strrev($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtnfqjibuc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gthcuximer.html

TS:   s === [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtmqzfpymk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jqgfzy.top/Article/details/gtutcbikad.html

Go:   // 双指针从两端比较
来源：http://dali.tianlin.xyz/Article/details/gtxhekkujg.html

Ruby: s == s.reverse
来源：http://dali.hnqzz.top/Article/details/gtysvilijj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jyoumei.cn/Article/details/gtpheboikb.html

[N07] 两数之和（返回下标）
来源：http://dali.shuidangran.top/Article/details/gtgmdzecol.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinghuilouyu.cn/Article/details/gtcfnzmspu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhiwuduotai.top/Article/details/gtlhdoyehh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gzhubu.top/Article/details/gtwnkpgzef.html

TS:   // 手写 Map<string, number>
来源：http://dali.feifeiyinyue.top/Article/details/gtnrcxlosa.html

Java: // 手写 HashMap
来源：http://dali.nwbrower.top/Article/details/gtlbdlekcu.html

Go:   // 手写 map[int]int
来源：http://dali.cucudq.cn/Article/details/gtguvbacxw.html

Ruby: // 手写 Hash
来源：http://dali.ivvv.top/Article/details/gtostyzhoz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cheryme.top/Article/details/gtugzwbefa.html

[N08] 生成全排列
来源：http://dali.yangfankeji.com/Article/details/gtmueofrzf.html

Py:   itertools.permutations(arr)
来源：http://dali.birdmap.top/Article/details/gtjumxxnvy.html

PHP:  // 手写递归交换
来源：http://dali.tanke756.top/Article/details/gtvvjiqqja.html

JS:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gthknnvhhs.html

TS:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gtphmsyyzb.html

Java: // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtnmyxidff.html

Go:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtekyrrudk.html

Ruby: arr.permutation.to_a
来源：http://dali.andypj.xyz/Article/details/gtbgkvjtov.html

C#:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtggtilejl.html

[N09] 栈与队列
来源：http://dali.cdnleiting.top/Article/details/gthkmemxju.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jiagoushi.top/Article/details/gtyotqmnja.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jqgufenzy.top/Article/details/gtntswxsew.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gaohongyu789.top/Article/details/gtmmpaqbbl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcybfditx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yonumen.top/Article/details/gtnzzuomki.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hnqzz.top/Article/details/gtiojpspmh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yanxiufei.cn/Article/details/gteeepkbvh.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.haohaochexian.top/Article/details/gtfnfssqjf.html

[N10] 链表节点定义
来源：http://dali.quarkkingdee.top/Article/details/gtbezgomss.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gtjxdhjdsj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yuxming.cn/Article/details/gtmtvuwpoz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.dianchejie.cn/Article/details/gtrfcqwnyr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shangyingyoupin.top/Article/details/gtmmkdjgub.html

Java: class Node { int v; Node next; }
来源：http://dali.shangyingyoupin.top/Article/details/gtbbobdvsm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.316326.xyz/Article/details/gtyqfeyamx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yj20258888.top/Article/details/gtiwwozevs.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ivvv.top/Article/details/gtszbeygam.html

[N11] 二叉树中序遍历
来源：http://dali.pycfn.com/Article/details/gtmppadvpo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhengqikj.top/Article/details/gtsdxjyxcu.html

PHP:  // 手写递归函数
来源：http://dali.ydzc1.top/Article/details/gtczbbdsvs.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.haohaochexian.top/Article/details/gttmfonbvv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.snrcjt.cn/Article/details/gtrnjhburx.html

Java: // 手写递归
来源：http://dali.yvedp.cn/Article/details/gtqvrgflsy.html

Go:   // 手写递归
来源：http://dali.wangdashe.top/Article/details/gtvzxobthe.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shanyushiyangtech.top/Article/details/gtdbphqkwz.html

C#:   // 手写递归
来源：http://dali.316326.xyz/Article/details/gtfxcolmsr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.meibo888.top/Article/details/gtcksbwvnd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyxhohcxm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.guowangkeji.top/Article/details/gtwlzhulsq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shuidangran.top/Article/details/gtvjildpmp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shangyingyoupin.top/Article/details/gtbvxnymls.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tian-w.cn/Article/details/gtbehgnpks.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhengqikj.top/Article/details/gtbdulxvhk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.andypj.xyz/Article/details/gtywaeuftv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cashguo.top/Article/details/gtqyyatjfo.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtsydnfnss.html

O. 并发与异步
来源：http://dali.cashguo.top/Article/details/gtnfglnlog.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtlvldhbuu.html

[O01] 启动一个线程
来源：http://dali.jqgufenzy.top/Article/details/gtsswgrwsv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shanyushiyangtech.top/Article/details/gtgxdhzpfg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yj202588.top/Article/details/gtcobejegk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nanxinkj.top/Article/details/gtukqjbveh.html

TS:   // 同 JS
来源：http://dali.hnxiangtu.top/Article/details/gtvcvlaqpi.html

Java: new Thread(() -> f()).start()
来源：http://dali.gaohongyu789.top/Article/details/gtxpmjsvmn.html

Go:   go f()
来源：http://dali.zhongyouzk.top/Article/details/gtronrycfs.html

Ruby: Thread.new { f }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvwkbdatl.html

C#:   Task.Run(() => F());
来源：http://dali.quarkkingdee.top/Article/details/gtqlbcaeyj.html

[O02] 使用线程池
来源：http://dali.jinqigfzy.top/Article/details/gtgbgbbybi.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cucudq.cn/Article/details/gtoffwexzd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.quarkkingdee.top/Article/details/gtvhrnljmt.html

JS:   // worker_threads 线程池
来源：http://dali.nanxuanxn.top/Article/details/gtipjkuuao.html

TS:   // worker_threads 线程池
来源：http://dali.jqgfzy.top/Article/details/gtzpmexnet.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yvedp.cn/Article/details/gturcgmldk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.nanxinkj.top/Article/details/gtcbkzetdq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.wangdashe.top/Article/details/gtmomwfmkt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gotoacloud.top/Article/details/gtarpyqabi.html

[O03] 加锁保护共享数据
来源：http://dali.bjfxy.top/Article/details/gtfywkxsze.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gtrsswgnxp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.pengpengdd.cyou/Article/details/gteubhaioj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gaohongyu789.top/Article/details/gtwpaxqqrl.html

TS:   // 同 JS
来源：http://dali.redwolf501.top/Article/details/gtbxnjcffj.html

Java: synchronized (this) { shared++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtamqnnrti.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.wangdashe.top/Article/details/gtckxvbqxv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yonumen.top/Article/details/gtayixvoto.html

C#:   lock (gate) { shared++; }
来源：http://dali.birdmap.top/Article/details/gtlyftuqsd.html

[O04] 定义异步函数并等待
来源：http://dali.yj20258.top/Article/details/gtkhrxrmek.html

Py:   async def f():⏎    await g()
来源：http://dali.0kj1m.cn/Article/details/gtarqyxvme.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhongyouzk.top/Article/details/gtvzvgkxft.html

JS:   async function f() { await g(); }
来源：http://dali.zdqjudy.top/Article/details/gtlfdonrjx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yongpay.top/Article/details/gtdrytplxt.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.bjfxy.top/Article/details/gtrajrehgz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.svipenyu.cn/Article/details/gttvpsknma.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jiagoushi.top/Article/details/gtzhsghzmk.html

C#:   async Task F() { await G(); }
来源：http://dali.sysykeji.top/Article/details/gtygzuybdk.html

[O05] 并发执行并等待全部完成
来源：http://dali.xuetiantiany.cn/Article/details/gtnusgkdml.html

Py:   asyncio.gather(*tasks)
来源：http://dali.wangshuangyany.cn/Article/details/gtfatkxsum.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ydzc1.top/Article/details/gtcnzpywvh.html

JS:   await Promise.all(tasks)
来源：http://dali.ehwqpu.com/Article/details/gtdmokfgrr.html

TS:   await Promise.all(tasks)
来源：http://dali.sysykeji.top/Article/details/gtqjnjifrw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jianghu66.top/Article/details/gtdkrnfywe.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jinqigfzy.top/Article/details/gtnvcaicxo.html

Ruby: threads.map(&:join)
来源：http://dali.316326.xyz/Article/details/gtdloindkb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhoulong.xyz/Article/details/gthsrhxayb.html

[O06] 使用进程池
来源：http://dali.jiagoushi.top/Article/details/gtekvblulv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jyoumei.cn/Article/details/gttjbpkrxd.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.wangdashe.top/Article/details/gtqoymzobe.html

JS:   // child_process / cluster 模块
来源：http://dali.guowangkeji.top/Article/details/gtxgpaqmuw.html

TS:   // child_process / cluster 模块
来源：http://dali.hongshengwenyu.top/Article/details/gtgejwmwak.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hfpthk.cn/Article/details/gtkfqadxll.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jinqigufen.top/Article/details/gtxgwulfys.html

Ruby: // fork 块
来源：http://dali.birdmap.top/Article/details/gtsjauocac.html

C#:   Parallel.For
来源：http://dali.shangyingyoupin.top/Article/details/gtfnnydvde.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gthvkfzijw.html

P. 常用工具函数
来源：http://dali.dashuyun.cn/Article/details/gtfmigsstv.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtyxcrrgsl.html

[P01] 生成 UUID
来源：http://dali.jinqigfzy.top/Article/details/gthemkwvkb.html

Py:   str(uuid.uuid4())
来源：http://dali.yonumen.top/Article/details/gtihehfcav.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.snrcjt.cn/Article/details/gtmxnoayku.html

JS:   crypto.randomUUID()
来源：http://dali.zdqjudy.top/Article/details/gteskbkqby.html

TS:   crypto.randomUUID()
来源：http://dali.jiagoushi.top/Article/details/gtwiumbdyr.html

Java: UUID.randomUUID().toString()
来源：http://dali.yj20258888.top/Article/details/gteixwsoxx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yonumen.top/Article/details/gtjpmabuvw.html

Ruby: SecureRandom.uuid
来源：http://dali.nanxuanxn.top/Article/details/gtznuiqrgq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtaanfbhul.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ehwqpu.com/Article/details/gtmorpeyqw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinqigfzy.top/Article/details/gtssrzukly.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtxtrzibmy.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yj202588.top/Article/details/gtaneqpjmh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtamzjwwjj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gtatihoiae.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jianghu66.top/Article/details/gtnihvhkth.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cashguo.top/Article/details/gtmcwrnlmb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.kuanghao11.cn/Article/details/gtykdvdybr.html

[P03] 生成短随机字符串
来源：http://dali.fzhhl.top/Article/details/gtvfkjxotb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jiagoushi.top/Article/details/gtuotymuel.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shzxlz.cn/Article/details/gtmgoyxknb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinqigfzy.top/Article/details/gtnvwaceej.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcacpuidx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.wangdashe.top/Article/details/gthjvjqviw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.aizwys.cn/Article/details/gtmflzsldp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.birdmap.top/Article/details/gtgxobdakr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shanyushiyangtech.top/Article/details/gtngpqyrlq.html

[P04] 求长度
来源：http://dali.haohaochexian.top/Article/details/gtkoevfsjw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hongshengwenyu.top/Article/details/gtuqxllzvr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gturvogtyv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gaohongyu789.top/Article/details/gtytwyzpwj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhixingplan.top/Article/details/gtcxjogahf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.aibaodan.cn/Article/details/gtxkhpaosx.html

Go:   len(arr);  len(m)
来源：http://dali.sweek.top/Article/details/gtczoxkrve.html

Ruby: x.length;  x.size
来源：http://dali.mhx1999.top/Article/details/gthsjbnzlg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.9152youxi.cn/Article/details/gtumigzaoo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.sysykeji.top/Article/details/gtvdbumfov.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.fengsongda.top/Article/details/gtebshqpqp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cheryme.top/Article/details/gtkaitybtl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ivvv.top/Article/details/gtdmwsmzwn.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hfpthk.cn/Article/details/gtoovussla.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.meibo888.top/Article/details/gtmpiuzbkc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.9152youxi.cn/Article/details/gtrxqukazl.html

Ruby: a == b
来源：http://dali.pengpengdd.cyou/Article/details/gtopjbjecq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hywenlv.cn/Article/details/gtpvfbvywq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.guowangkeji.top/Article/details/gtsbwgsmbs.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yueranfly.top/Article/details/gtqxbnypfd.html

PHP:  if (empty($x)) {}
来源：http://dali.yangfankeji.com/Article/details/gtpqedldny.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhixingplan.top/Article/details/gtqfuyzeor.html

TS:   if (x == null) {}
来源：http://dali.sysykeji.top/Article/details/gtjogudlay.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.pycfn.com/Article/details/gtzanoxfuz.html

Go:   if x == nil {}
来源：http://dali.shzxlz.cn/Article/details/gtshuobcbh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yj20258.top/Article/details/gtqqrobsqp.html

C#:   if (x is null) {}
来源：http://dali.gzhubu.top/Article/details/gtwzntckha.html

[P07] 防抖与节流
来源：http://dali.zhengqikj.top/Article/details/gtshjezxex.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cucudq.cn/Article/details/gtpohkdpwt.html

PHP:  // 手写时间戳比较
来源：http://dali.ydzc1.top/Article/details/gtadzvxabt.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.0kj1m.cn/Article/details/gtlbkbfxcl.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jyoumei.cn/Article/details/gtqdpdrxmn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpsdklkpp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hfpthk.cn/Article/details/gtwyokcfsv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtypdtuloj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhixingplan.top/Article/details/gtcisbhjzf.html

[P08] 处理浮点精度问题
来源：http://dali.redwolf501.top/Article/details/gtldvhospn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cashguo.top/Article/details/gtvherqbrx.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.vqdsnc.cn/Article/details/gtetqfzaax.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cdnleiting.top/Article/details/gtiaxiuyaq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.sufxvd.cn/Article/details/gtesbzugyq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hnqzz.top/Article/details/gtbxiadtda.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.quarkkingdee.top/Article/details/gtwtnolvds.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xinyue.icu/Article/details/gtjljudlgt.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jqgufenzy.top/Article/details/gtvavkwnfs.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gttakeftvp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.redwolf501.top/Article/details/gtvwurbvgy.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtljxqhaks.html

[Q01] 创建表
来源：http://dali.daria6918.cn/Article/details/gtferfouyy.html


<!-- 参考信息 -->