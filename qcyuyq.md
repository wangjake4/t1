代发 wailian999

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zdqjudy.top/Article/details/gtmysxdwra.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xuanzx.com/Article/details/gtgbxejogl.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhoulong.xyz/Article/details/gtmnsptaad.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.c1oappe.top/Article/details/gtnfwfermn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cdnleiting.top/Article/details/gthncqnhsl.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xinyue.icu/Article/details/gtmuggrrit.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ivvv.top/Article/details/gtnqivdana.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cheryme.top/Article/details/gthrbqjhwe.html

[M04] 获取当前工作目录
来源：http://dali.hongshengwenyu.top/Article/details/gtiomsqfoz.html

Py:   os.getcwd()
来源：http://dali.jianghu66.top/Article/details/gtfxandlph.html

PHP:  getcwd();
来源：http://dali.yj20258888.top/Article/details/gtlqjdwrso.html

JS:   process.cwd()
来源：http://dali.xuanzx.com/Article/details/gtuzwyljzr.html

TS:   process.cwd()
来源：http://dali.zhixingplan.top/Article/details/gtmlygfydy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xylfe.cn/Article/details/gtwyexxxgc.html

Go:   os.Getwd()
来源：http://dali.ybcxt.top/Article/details/gthyuidjij.html

Ruby: Dir.pwd
来源：http://dali.zhoulong.xyz/Article/details/gtathpdjli.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hammf.cn/Article/details/gthmvgjvpt.html

[M05] 设置退出码
来源：http://dali.chenzaomai.com/Article/details/gtjxenqzip.html

Py:   sys.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gthxzlzfqu.html

PHP:  exit(1);
来源：http://dali.guannengcc.top/Article/details/gtaonuqadr.html

JS:   process.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gtrbcdxzwh.html

TS:   process.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtwinnncob.html

Java: System.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gtjwgvbkju.html

Go:   os.Exit(1)
来源：http://dali.cucudq.cn/Article/details/gtlnwqxnny.html

Ruby: exit 1
来源：http://dali.jlsjyb.cn/Article/details/gtoqzmzeiv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ybcxt.top/Article/details/gtxshpcvwd.html

[M06] 向标准错误输出
来源：http://dali.cdnleiting.top/Article/details/gttdyiqmzf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cdnleiting.top/Article/details/gtfcxvcljp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinghuilouyu.cn/Article/details/gtjcisgeyh.html

JS:   console.error("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gtctkkirwd.html

TS:   console.error("err")
来源：http://dali.0kj1m.cn/Article/details/gtfaafjdhq.html

Java: System.err.println("err")
来源：http://dali.nwbrower.top/Article/details/gtenuranfi.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hnxiangtu.top/Article/details/gtomsmtiyx.html

Ruby: warn "err"
来源：http://dali.tianlin.xyz/Article/details/gtoxsmenwm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ehwqpu.com/Article/details/gtrlibyavb.html

[M07] 判断是否为主入口
来源：http://dali.hysaishi.cn/Article/details/gtsxrxvbyf.html

Py:   if __name__ == "__main__":
来源：http://dali.cashguo.top/Article/details/gttojzaadw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.redwolf501.top/Article/details/gtnirqfzwk.html

JS:   require.main === module
来源：http://dali.jqgufenzy.top/Article/details/gtvgxwqgml.html

TS:   require.main === module
来源：http://dali.yangfankeji.com/Article/details/gtziuzamup.html

Java: public static void main(String[] args)
来源：http://dali.hammf.cn/Article/details/gtgknuiwca.html

Go:   func main()
来源：http://dali.tianlin.xyz/Article/details/gthagnjavi.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.haohaochexian.top/Article/details/gthrmxgmpi.html

C#:   static void Main(string[] args)
来源：http://dali.mhx1999.top/Article/details/gtcvijpjcv.html

[M08] 获取系统与运行时信息
来源：http://dali.yangfankeji.com/Article/details/gtufoholzb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj20258888.top/Article/details/gtjzivvdhi.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yuanzhike.top/Article/details/gtmpfdpcre.html

JS:   process.platform;  process.version
来源：http://dali.hysaishi.cn/Article/details/gtckgrvdsx.html

TS:   process.platform;  process.version
来源：http://dali.xuetiantiany.cn/Article/details/gtefkxcist.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yj20258.top/Article/details/gtspkatfaw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ydzc1.top/Article/details/gtsmmzfxvp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yangfankeji.com/Article/details/gtebushucl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gotoacloud.top/Article/details/gtfhahnwuo.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gteweehndg.html

N. 数据结构与算法
来源：http://dali.chenlongwang.top/Article/details/gtinvcrsky.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtadisasbe.html

[N01] 二分查找（有序数组）
来源：http://dali.havefunace.top/Article/details/gtpbyksfeg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtwlqgyzam.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hammf.cn/Article/details/gtntypsqgs.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jlsjyb.cn/Article/details/gtbwztbgco.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gtbzvzhosf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtoomxlagr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ivvv.top/Article/details/gtqbsmgzrg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.aibaodan.cn/Article/details/gtkncshagz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtanwrgpnx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.svipenyu.cn/Article/details/gtecrimyhq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.birdmap.top/Article/details/gtckkwldnd.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shzxlz.cn/Article/details/gtjkxzbmeb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258.top/Article/details/gtnrbbdnka.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigfzy.top/Article/details/gtijexrmyi.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yongpay.top/Article/details/gtpuhouzup.html

Go:   slices.Sort(arr)
来源：http://dali.ehwqpu.com/Article/details/gtyqaqjnrm.html

Ruby: arr.sort
来源：http://dali.cheryme.top/Article/details/gtdehwueph.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cashguo.top/Article/details/gtrmwxrhfp.html

[N03] 快速排序（分治示例）
来源：http://dali.tanke756.top/Article/details/gtnmyxpodi.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhiwuduotai.top/Article/details/gtqyfkzrwp.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hnqzz.top/Article/details/gtwwprpkqn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yongpay.top/Article/details/gtfmodlkrx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cdnleiting.top/Article/details/gtixfxsbmu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hongshengwenyu.top/Article/details/gtuaqbhdaw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinghuilouyu.cn/Article/details/gtdmfukpqy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jqgufenzy.top/Article/details/gtirvhlyjg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenjidiqi.icu/Article/details/gtdbdlhorn.html

[N04] 斐波那契数列
来源：http://dali.pycfn.com/Article/details/gtmcwqypua.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.guowangkeji.top/Article/details/gtjtrnnwfe.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xylfe.cn/Article/details/gtsstnnvxc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.snrcjt.cn/Article/details/gtblugojtb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cqqwz.cn/Article/details/gtxmilnvkc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shuidangran.top/Article/details/gtgiqhyhah.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsddiksfs.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.9152youxi.cn/Article/details/gtpjrafydl.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gtuboiqiwh.html

[N05] 最大公约数
来源：http://dali.snrcjt.cn/Article/details/gtcdwxuyop.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gtugjaebez.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.tianlin.xyz/Article/details/gtyrmywjha.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhoulong.xyz/Article/details/gtklpxoebv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.iojbl.cn/Article/details/gtoztajzib.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.mhx1999.top/Article/details/gttbbxcxnm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.c1oappe.top/Article/details/gtuytehfpu.html

Ruby: a.gcd(b)
来源：http://dali.yvedp.cn/Article/details/gtxynkezip.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.9152youxi.cn/Article/details/gtwjrphrga.html

[N06] 判断回文字符串
来源：http://dali.smart0.xyz/Article/details/gtpsrfrpif.html

Py:   s == s[::-1]
来源：http://dali.xuanzx.com/Article/details/gtzwqibfcy.html

PHP:  $s === strrev($s);
来源：http://dali.vqdsnc.cn/Article/details/gtifspjeqe.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gtuvqwvenw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtineiehkd.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.fengsongda.top/Article/details/gtqgoqufdj.html

Go:   // 双指针从两端比较
来源：http://dali.vqdsnc.cn/Article/details/gtexugypgk.html

Ruby: s == s.reverse
来源：http://dali.fzhhl.top/Article/details/gtsohqwwit.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.svipenyu.cn/Article/details/gtmsglnzix.html

[N07] 两数之和（返回下标）
来源：http://dali.tanke756.top/Article/details/gtggpwfgpi.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.316326.xyz/Article/details/gtnaxexdde.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shzxlz.cn/Article/details/gtbttkxmhq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yonumen.top/Article/details/gtbpbmnpbn.html

TS:   // 手写 Map<string, number>
来源：http://dali.vqdsnc.cn/Article/details/gtwymycljg.html

Java: // 手写 HashMap
来源：http://dali.birdmap.top/Article/details/gtcwqwwgip.html

Go:   // 手写 map[int]int
来源：http://dali.jlsjyb.cn/Article/details/gtviehmqnc.html

Ruby: // 手写 Hash
来源：http://dali.fzhhl.top/Article/details/gtzhuagyvg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.guowangkeji.top/Article/details/gtefurinfx.html

[N08] 生成全排列
来源：http://dali.ybcxt.top/Article/details/gtexeqsqqz.html

Py:   itertools.permutations(arr)
来源：http://dali.yangfankeji.com/Article/details/gtyiktgkbi.html

PHP:  // 手写递归交换
来源：http://dali.tian-w.cn/Article/details/gtleyjfcym.html

JS:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gteloxxgbo.html

TS:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gtwqgaklpz.html

Java: // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gtaxtvkdeo.html

Go:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gtfwlgvusb.html

Ruby: arr.permutation.to_a
来源：http://dali.snrcjt.cn/Article/details/gtvejmmkvr.html

C#:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gtrnujkjhc.html

[N09] 栈与队列
来源：http://dali.mhx1999.top/Article/details/gtsjxylhsg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.daxiang520.top/Article/details/gtelrgpsdq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gtaxuownfe.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.chenlongwang.top/Article/details/gttklisigr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xuanzx.com/Article/details/gtljjayxxt.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.feifeiyinyue.top/Article/details/gtjpxyotqf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.tian-w.cn/Article/details/gtxzgxynwf.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtysyoxdfg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.haohaochexian.top/Article/details/gtuqukkmdc.html

[N10] 链表节点定义
来源：http://dali.cashguo.top/Article/details/gthipmfymz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgfbnobbp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfplmumpn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jiagoushi.top/Article/details/gtaifktvdf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xuetiantiany.cn/Article/details/gtvuivrfra.html

Java: class Node { int v; Node next; }
来源：http://dali.sweek.top/Article/details/gtknaixwrj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinghuilouyu.cn/Article/details/gttilrbxrx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.iojbl.cn/Article/details/gtgtbjartk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ybcxt.top/Article/details/gtvadibwrt.html

[N11] 二叉树中序遍历
来源：http://dali.yangfankeji.com/Article/details/gtyuqobdvg.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shzxlz.cn/Article/details/gtpnjthwnt.html

PHP:  // 手写递归函数
来源：http://dali.cdnleiting.top/Article/details/gtugmswbyi.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhoulong.xyz/Article/details/gtaiwoeybt.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyasdcmsj.html

Java: // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gtzawsubzd.html

Go:   // 手写递归
来源：http://dali.havefunace.top/Article/details/gtpbgbywvc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ppjwa.cn/Article/details/gtqzzxblzt.html

C#:   // 手写递归
来源：http://dali.yanxiufei.cn/Article/details/gtrducppui.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hnqzz.top/Article/details/gttwdgvwub.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.tanke756.top/Article/details/gtfagdgdvl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.vqdsnc.cn/Article/details/gtunwuqqdt.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yueranfly.top/Article/details/gtadzkjomr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.9152youxi.cn/Article/details/gtitsxurln.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yvedp.cn/Article/details/gttqlvwaoj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jianghu66.top/Article/details/gtegpmxaln.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yj20258888.top/Article/details/gtizcfsoki.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangtech.top/Article/details/gtvjtejxlc.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtvvgrqqhy.html

O. 并发与异步
来源：http://dali.nanxinkj.top/Article/details/gtcoonshly.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtdbsznolq.html

[O01] 启动一个线程
来源：http://dali.hywenlv.cn/Article/details/gttxgwupnx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdzbbfufv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.daria6918.cn/Article/details/gtnausjydw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zdqjudy.top/Article/details/gtruktiqmz.html

TS:   // 同 JS
来源：http://dali.aizwys.cn/Article/details/gtwawbwuwf.html

Java: new Thread(() -> f()).start()
来源：http://dali.hywenlv.cn/Article/details/gtfzpgqead.html

Go:   go f()
来源：http://dali.guannengcc.top/Article/details/gtzjywtbzq.html

Ruby: Thread.new { f }
来源：http://dali.fzhhl.top/Article/details/gtcitulglo.html

C#:   Task.Run(() => F());
来源：http://dali.andypj.xyz/Article/details/gthxhsdnjh.html

[O02] 使用线程池
来源：http://dali.yangfankeji.com/Article/details/gtoqsdeard.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gaohongyu789.top/Article/details/gtzoxmnkcu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zdqjudy.top/Article/details/gtegxtaamq.html

JS:   // worker_threads 线程池
来源：http://dali.yj20258888.top/Article/details/gtzdzlpxor.html

TS:   // worker_threads 线程池
来源：http://dali.shzxlz.cn/Article/details/gtejxbefep.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ppjwa.cn/Article/details/gthbyhbism.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.feifeiyinyue.top/Article/details/gtuxkkufya.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xylfe.cn/Article/details/gtygpvjber.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.smart0.xyz/Article/details/gtsjlvmgoi.html

[O03] 加锁保护共享数据
来源：http://dali.sweek.top/Article/details/gtcciaqwxn.html

Py:   with lock: shared += 1
来源：http://dali.ivvv.top/Article/details/gtdncumsqp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cucudq.cn/Article/details/gtkphsopsq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmkciyycv.html

TS:   // 同 JS
来源：http://dali.hnxiangtu.top/Article/details/gtztulgzlk.html

Java: synchronized (this) { shared++; }
来源：http://dali.hfpthk.cn/Article/details/gtgdwcwvrv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shanyushiyangtech.top/Article/details/gtictufaoi.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.chenzaomai.com/Article/details/gtfaczxqxa.html

C#:   lock (gate) { shared++; }
来源：http://dali.svipenyu.cn/Article/details/gtjdblcoll.html

[O04] 定义异步函数并等待
来源：http://dali.chenzaomai.com/Article/details/gtbgjadybv.html

Py:   async def f():⏎    await g()
来源：http://dali.quarkkingdee.top/Article/details/gtrhwzntdg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.wangshuangyany.cn/Article/details/gtjdbaogun.html

JS:   async function f() { await g(); }
来源：http://dali.hfpthk.cn/Article/details/gtiuofucur.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jiagoushi.top/Article/details/gtpyvvmapb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cdnleiting.top/Article/details/gtzsakkvsi.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jianghu66.top/Article/details/gtmmsuaxhe.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hongshengwenyu.top/Article/details/gtpezgroyn.html

C#:   async Task F() { await G(); }
来源：http://dali.fengsongda.top/Article/details/gtadulfkzj.html

[O05] 并发执行并等待全部完成
来源：http://dali.cqqwz.cn/Article/details/gtrmwtwhgi.html

Py:   asyncio.gather(*tasks)
来源：http://dali.9152youxi.cn/Article/details/gtbmgzfzjq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.iojbl.cn/Article/details/gtzwqptgwt.html

JS:   await Promise.all(tasks)
来源：http://dali.ppjwa.cn/Article/details/gtiwyqybec.html

TS:   await Promise.all(tasks)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyfvjihef.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.guowangkeji.top/Article/details/gtmbycxoix.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hnqzz.top/Article/details/gtpfdikmmy.html

Ruby: threads.map(&:join)
来源：http://dali.pengpengdd.cyou/Article/details/gtsgntiwoj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvzbsvxwf.html

[O06] 使用进程池
来源：http://dali.316326.xyz/Article/details/gthsonqdsn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.guowangkeji.top/Article/details/gtopgobhpa.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yj20258.top/Article/details/gtkvaftzba.html

JS:   // child_process / cluster 模块
来源：http://dali.nanxuanxn.top/Article/details/gtdgmnrghj.html

TS:   // child_process / cluster 模块
来源：http://dali.hysaishi.cn/Article/details/gtojhxooyr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yueranfly.top/Article/details/gtqjrqfofw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jqgufenzy.top/Article/details/gtbzoqtppk.html

Ruby: // fork 块
来源：http://dali.jyoumei.cn/Article/details/gtwrmnuoxq.html

C#:   Parallel.For
来源：http://dali.yuxming.cn/Article/details/gteewjzdlf.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtbmdabcls.html

P. 常用工具函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjgalobzr.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gthewyfmnm.html

[P01] 生成 UUID
来源：http://dali.guowangkeji.top/Article/details/gtmrrtfynb.html

Py:   str(uuid.uuid4())
来源：http://dali.svipenyu.cn/Article/details/gttzamfuyk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.fengsongda.top/Article/details/gtojyupplv.html

JS:   crypto.randomUUID()
来源：http://dali.nanxuanxn.top/Article/details/gtlojzewzd.html

TS:   crypto.randomUUID()
来源：http://dali.ehwqpu.com/Article/details/gtxuguojuv.html

Java: UUID.randomUUID().toString()
来源：http://dali.shangyingyoupin.top/Article/details/gttxgzagrp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gogol.net.cn/Article/details/gtymxudsqb.html

Ruby: SecureRandom.uuid
来源：http://dali.sxryk.cn/Article/details/gtqlznoenh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhengqikj.top/Article/details/gtdxktwgon.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jqgufenzy.top/Article/details/gtgydtuhqp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinqigufen.top/Article/details/gtdesumkky.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.aibaodan.cn/Article/details/gtfxqexbzy.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ybcxt.top/Article/details/gtffciybcv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.mhx1999.top/Article/details/gtroxocequ.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj202588.top/Article/details/gtxrzvtvor.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yonumen.top/Article/details/gtpudveuid.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.daria6918.cn/Article/details/gtikyrykiw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jyoumei.cn/Article/details/gtyymbowub.html

[P03] 生成短随机字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtntalswya.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.chenlongwang.top/Article/details/gtgdunjaux.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cqqwz.cn/Article/details/gthtznxrbv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgfzy.top/Article/details/gtiobpvddd.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nwbrower.top/Article/details/gticmpuqcv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.guannengcc.top/Article/details/gtvzcgnimf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.andypj.xyz/Article/details/gtvhcyckon.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zycfv.cn/Article/details/gtkevdloiv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.iojbl.cn/Article/details/gtlgkqrxsd.html

[P04] 求长度
来源：http://dali.hywenlv.cn/Article/details/gtqjlqpbqk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.feifeiyinyue.top/Article/details/gtezvbptom.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gtrzmeeymn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj202588.top/Article/details/gtljtlcafz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.meibo888.top/Article/details/gtpsedvqqn.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinghuilouyu.cn/Article/details/gtcygltawm.html

Go:   len(arr);  len(m)
来源：http://dali.feifeiyinyue.top/Article/details/gtrhncwxqe.html

Ruby: x.length;  x.size
来源：http://dali.quarkkingdee.top/Article/details/gttsnwfdrb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zycfv.cn/Article/details/gtdcvqiuku.html

[P05] 判断两个对象内容是否相等
来源：http://dali.bjfxy.top/Article/details/gtvwsevbrh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.feifeiyinyue.top/Article/details/gtpjktmtbe.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.meibo888.top/Article/details/gtvtfdqbaj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhongyouzk.top/Article/details/gtumizznpt.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xinyue.icu/Article/details/gtovrzoyii.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hnqzz.top/Article/details/gttegrbylk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ehwqpu.com/Article/details/gtmluoxxtj.html

Ruby: a == b
来源：http://dali.bjfxy.top/Article/details/gtarwenicf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.vqdsnc.cn/Article/details/gtxaqmydvn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hnxiangtu.top/Article/details/gtbduljmxk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.nanxuanxn.top/Article/details/gthwboekub.html

PHP:  if (empty($x)) {}
来源：http://dali.hammf.cn/Article/details/gtntzowkko.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.quarkkingdee.top/Article/details/gthcxcncae.html

TS:   if (x == null) {}
来源：http://dali.fzhhl.top/Article/details/gtiktrzumk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.nanxinkj.top/Article/details/gtvebgmqab.html

Go:   if x == nil {}
来源：http://dali.zycfv.cn/Article/details/gtoohjugxl.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.chenzaomai.com/Article/details/gtvqkmdzdc.html

C#:   if (x is null) {}
来源：http://dali.birdmap.top/Article/details/gtuyciemgb.html

[P07] 防抖与节流
来源：http://dali.guannengcc.top/Article/details/gttiybgqdo.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.nanxinkj.top/Article/details/gtukopgqos.html

PHP:  // 手写时间戳比较
来源：http://dali.gogol.net.cn/Article/details/gtwbyvnpge.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.kuanghao11.cn/Article/details/gtkfigjjsw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.vqdsnc.cn/Article/details/gtfxjotixa.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.bjfxy.top/Article/details/gthbwtzfws.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hywenlv.cn/Article/details/gtizlendao.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xuetiantiany.cn/Article/details/gtbzrqkhce.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.mhx1999.top/Article/details/gtqwbbzdjc.html

[P08] 处理浮点精度问题
来源：http://dali.pycfn.com/Article/details/gtahmupggw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.aizwys.cn/Article/details/gtobegokye.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.sufxvd.cn/Article/details/gtlpzmqtur.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.nanxinkj.top/Article/details/gtzpggfbpb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xylfe.cn/Article/details/gtcwfqfrdu.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ppjwa.cn/Article/details/gtpssejlzf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shanyushiyangkeji.top/Article/details/gtghhntemf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.kuanghao11.cn/Article/details/gtqrmjkftp.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.meibo888.top/Article/details/gtmvxvaxhc.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gthsbtboqr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.aizwys.cn/Article/details/gtzfjdhtxa.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtwtcqipht.html

[Q01] 创建表
来源：http://dali.ppjwa.cn/Article/details/gtthcwiaut.html


<!-- 参考信息 -->