代发 wailian999

TS:   process.cwd()
来源：http://dali.aibaodan.cn/Article/details/gtfmeruuuc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shangyingyoupin.top/Article/details/gthnrpuxjf.html

Go:   os.Getwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfeouatm.html

Ruby: Dir.pwd
来源：http://dali.yj20258.top/Article/details/gthfuuxrtq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.dianchejie.cn/Article/details/gtwzztweej.html

[M05] 设置退出码
来源：http://dali.feifeiyinyue.top/Article/details/gtaeuckzyk.html

Py:   sys.exit(1)
来源：http://dali.iojbl.cn/Article/details/gtlwwlzzvk.html

PHP:  exit(1);
来源：http://dali.tianlin.xyz/Article/details/gtistnwkzf.html

JS:   process.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtvkxmfwck.html

TS:   process.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtsfyisscb.html

Java: System.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtylqfnldc.html

Go:   os.Exit(1)
来源：http://dali.jinqigufen.top/Article/details/gtzqtxtdny.html

Ruby: exit 1
来源：http://dali.jqgufenzy.top/Article/details/gttrvgkiut.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.c1oappe.top/Article/details/gtwsnpyqja.html

[M06] 向标准错误输出
来源：http://dali.zhongyouzk.top/Article/details/gtzsoqydac.html

Py:   print("err", file=sys.stderr)
来源：http://dali.316326.xyz/Article/details/gteuiuyqfa.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hammf.cn/Article/details/gtqppjbfbj.html

JS:   console.error("err")
来源：http://dali.cqqwz.cn/Article/details/gtxkdjfdqh.html

TS:   console.error("err")
来源：http://dali.zdqjudy.top/Article/details/gtngpuzmwg.html

Java: System.err.println("err")
来源：http://dali.ydzc1.top/Article/details/gtpybvyrwg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.snrcjt.cn/Article/details/gtednblyna.html

Ruby: warn "err"
来源：http://dali.mhx1999.top/Article/details/gtztcemcmk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.316326.xyz/Article/details/gtjefmfaey.html

[M07] 判断是否为主入口
来源：http://dali.316326.xyz/Article/details/gtxtcqycvp.html

Py:   if __name__ == "__main__":
来源：http://dali.zdqjudy.top/Article/details/gtiscqopnc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhongyouzk.top/Article/details/gteqsgxpxi.html

JS:   require.main === module
来源：http://dali.guannengcc.top/Article/details/gthicitaek.html

TS:   require.main === module
来源：http://dali.haohaochexian.top/Article/details/gtcrdaartg.html

Java: public static void main(String[] args)
来源：http://dali.svipenyu.cn/Article/details/gtfsflqnlb.html

Go:   func main()
来源：http://dali.yanxiufei.cn/Article/details/gtoiemxozl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.kuanghao11.cn/Article/details/gttfssjivw.html

C#:   static void Main(string[] args)
来源：http://dali.vqdsnc.cn/Article/details/gtehwzrjcg.html

[M08] 获取系统与运行时信息
来源：http://dali.fzhhl.top/Article/details/gtrgjpsocp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.birdmap.top/Article/details/gtcjzcvvvz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yuxming.cn/Article/details/gtkdcavuky.html

JS:   process.platform;  process.version
来源：http://dali.jianghu66.top/Article/details/gtpauetrzh.html

TS:   process.platform;  process.version
来源：http://dali.jqgufenzy.top/Article/details/gtpwffhxci.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shuidangran.top/Article/details/gtspjryruw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.bjfxy.top/Article/details/gtiabpuqqh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shuidangran.top/Article/details/gtnuvcfsnx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.dashuyun.cn/Article/details/gtoxthvlwl.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtrwanexfm.html

N. 数据结构与算法
来源：http://dali.redwolf501.top/Article/details/gtvrorzvym.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtzeccakee.html

[N01] 二分查找（有序数组）
来源：http://dali.chenlongwang.top/Article/details/gtrqnzgzoq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tanke756.top/Article/details/gtrfyuaakn.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtilhtdbwq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guannengcc.top/Article/details/gtumsavfyv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yanxiufei.cn/Article/details/gtbibuwiyc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.pycfn.com/Article/details/gtzgqnuqfv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gtdwgxpkyz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yueranfly.top/Article/details/gtdqcpertc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtjybbsivj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yuxming.cn/Article/details/gtiqtyanbn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.smart0.xyz/Article/details/gtirxbyvym.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.fengsongda.top/Article/details/gtllzrdmln.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gzhubu.top/Article/details/gtppmsusxm.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhiwuduotai.top/Article/details/gtcxextled.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.quarkkingdee.top/Article/details/gtuoxjldwq.html

Go:   slices.Sort(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtrahjyofd.html

Ruby: arr.sort
来源：http://dali.ehwqpu.com/Article/details/gtpeyohiyp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yj202588.top/Article/details/gtuvecfugk.html

[N03] 快速排序（分治示例）
来源：http://dali.cucudq.cn/Article/details/gtpfehzwpu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinqigfzy.top/Article/details/gtajaqffbb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hysaishi.cn/Article/details/gtzgqqbdrz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pengpengdd.cyou/Article/details/gtmchmlrwl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sysykeji.top/Article/details/gtxqbaiuzz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.iojbl.cn/Article/details/gtiayeqqee.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.smart0.xyz/Article/details/gtymgnvewk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sxryk.cn/Article/details/gtwoiduzyv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenjidiqi.icu/Article/details/gtunwwybib.html

[N04] 斐波那契数列
来源：http://dali.hfpthk.cn/Article/details/gthhvurowg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cdnleiting.top/Article/details/gticzdidow.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zycfv.cn/Article/details/gtcilwsxuj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtetlisynv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jlsjyb.cn/Article/details/gtdwmduudu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yangfankeji.com/Article/details/gttuiwiyqx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhengqikj.top/Article/details/gtcdrbksyk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ppjwa.cn/Article/details/gtmpzaqreq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.dianchejie.cn/Article/details/gtqyvhavdp.html

[N05] 最大公约数
来源：http://dali.nwbrower.top/Article/details/gthiwtidtd.html

Py:   math.gcd(a, b)
来源：http://dali.c1oappe.top/Article/details/gtlgeqmljh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gtpejzopei.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gtxtgtnprf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthbqsnwat.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.fzhhl.top/Article/details/gtvdrspbop.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.guannengcc.top/Article/details/gtmtaqxama.html

Ruby: a.gcd(b)
来源：http://dali.yanxiufei.cn/Article/details/gticwxanhh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ppjwa.cn/Article/details/gtqwvgyzsl.html

[N06] 判断回文字符串
来源：http://dali.tanke756.top/Article/details/gtogtkszri.html

Py:   s == s[::-1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgrzpfsjv.html

PHP:  $s === strrev($s);
来源：http://dali.ydzc1.top/Article/details/gtkzamtskw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gtukugwlem.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gtyeodijua.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.dianchejie.cn/Article/details/gtdnaxixvj.html

Go:   // 双指针从两端比较
来源：http://dali.yuxming.cn/Article/details/gtmlehbsqx.html

Ruby: s == s.reverse
来源：http://dali.tanke756.top/Article/details/gtkzmbasod.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yj202588.top/Article/details/gtrfrlzsdq.html

[N07] 两数之和（返回下标）
来源：http://dali.smart0.xyz/Article/details/gthnftpzdv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.guowangkeji.top/Article/details/gtqzakepiy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cashguo.top/Article/details/gtyslscxtd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.pycfn.com/Article/details/gtmecyebta.html

TS:   // 手写 Map<string, number>
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdbyqxhgv.html

Java: // 手写 HashMap
来源：http://dali.zycfv.cn/Article/details/gtvyqexvuz.html

Go:   // 手写 map[int]int
来源：http://dali.vqdsnc.cn/Article/details/gtssfpnjyp.html

Ruby: // 手写 Hash
来源：http://dali.hywenlv.cn/Article/details/gtpqqqucqn.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.iojbl.cn/Article/details/gtvlgqvcie.html

[N08] 生成全排列
来源：http://dali.iojbl.cn/Article/details/gtoznlwhvi.html

Py:   itertools.permutations(arr)
来源：http://dali.fengsongda.top/Article/details/gtbcwkrlxm.html

PHP:  // 手写递归交换
来源：http://dali.jinghuilouyu.cn/Article/details/gtocgkfysc.html

JS:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gtnpihbscl.html

TS:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gtjrbymhhy.html

Java: // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gtxpelajym.html

Go:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtjtpzizjg.html

Ruby: arr.permutation.to_a
来源：http://dali.jianghu66.top/Article/details/gtvehpenqx.html

C#:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gttzjmpthp.html

[N09] 栈与队列
来源：http://dali.zhongyouzk.top/Article/details/gtwuxkfmul.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ydzc1.top/Article/details/gtumunfmns.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yongpay.top/Article/details/gtjnoiuogl.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.vqdsnc.cn/Article/details/gtdodtudpu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.pycfn.com/Article/details/gtauyvpslb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yuxming.cn/Article/details/gtrsqkegat.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hammf.cn/Article/details/gtcrftilyg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.quarkkingdee.top/Article/details/gtjexrdtgj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yuanzhike.top/Article/details/gtkyewpqlp.html

[N10] 链表节点定义
来源：http://dali.fzhhl.top/Article/details/gtvpvldcdj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.316326.xyz/Article/details/gtigpvavnq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.redwolf501.top/Article/details/gtvszedcsb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.aibaodan.cn/Article/details/gtwudscfwt.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.nanxuanxn.top/Article/details/gthkwpwmia.html

Java: class Node { int v; Node next; }
来源：http://dali.bjfxy.top/Article/details/gtqvtbxnuo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrxslniib.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xziqi.cn/Article/details/gtvqtotpnh.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yuanzhike.top/Article/details/gtbskcbldz.html

[N11] 二叉树中序遍历
来源：http://dali.zhiwuduotai.top/Article/details/gtuomqlhhk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjrfzajun.html

PHP:  // 手写递归函数
来源：http://dali.gotoacloud.top/Article/details/gtfhlpfrsv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yangfankeji.com/Article/details/gtufodduqs.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tian-w.cn/Article/details/gtvkodbsmh.html

Java: // 手写递归
来源：http://dali.pengpengdd.cyou/Article/details/gtsohgzyuz.html

Go:   // 手写递归
来源：http://dali.hammf.cn/Article/details/gtxfpsycif.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkjmmbsmd.html

C#:   // 手写递归
来源：http://dali.cqqwz.cn/Article/details/gtnwupykkz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.316326.xyz/Article/details/gtnxgqwaib.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jianghu66.top/Article/details/gtdtilqdyi.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgdmocawv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cucudq.cn/Article/details/gtopevdbqk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhongyouzk.top/Article/details/gtovaobyiv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.bjfxy.top/Article/details/gtbnitwpzh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xinyue.icu/Article/details/gtbkuitcxn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.dianchejie.cn/Article/details/gtmkwccdip.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ydzc1.top/Article/details/gthipwkgpa.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtcfkxjnmn.html

O. 并发与异步
来源：http://dali.shanyushiyangtech.top/Article/details/gtoqrlppue.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtrwmdzbqx.html

[O01] 启动一个线程
来源：http://dali.iojbl.cn/Article/details/gtgeryphqp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yvedp.cn/Article/details/gtpnrgdgkr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.haohaochexian.top/Article/details/gtpqaetmwk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cqqwz.cn/Article/details/gtxpyirxir.html

TS:   // 同 JS
来源：http://dali.yangfankeji.com/Article/details/gtztsotfud.html

Java: new Thread(() -> f()).start()
来源：http://dali.daxiang520.top/Article/details/gtczaefefm.html

Go:   go f()
来源：http://dali.jinqigfzy.top/Article/details/gtrpycxhcy.html

Ruby: Thread.new { f }
来源：http://dali.9152youxi.cn/Article/details/gtzgoeagxh.html

C#:   Task.Run(() => F());
来源：http://dali.yj202588.top/Article/details/gthyjqvslj.html

[O02] 使用线程池
来源：http://dali.cashguo.top/Article/details/gtuchwkdvx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.svipenyu.cn/Article/details/gtaylnhons.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.meibo888.top/Article/details/gtempahmkh.html

JS:   // worker_threads 线程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoxnaczmy.html

TS:   // worker_threads 线程池
来源：http://dali.zhixingplan.top/Article/details/gtdozrtebl.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttjclttff.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yuxming.cn/Article/details/gtyikyolys.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shuidangran.top/Article/details/gtldjzonsb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhongyouzk.top/Article/details/gteyqjjdyb.html

[O03] 加锁保护共享数据
来源：http://dali.zhixingplan.top/Article/details/gtstoxfyyk.html

Py:   with lock: shared += 1
来源：http://dali.cheryme.top/Article/details/gtreyoptgs.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cqqwz.cn/Article/details/gtuycyjmpt.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.andypj.xyz/Article/details/gtwvllolum.html

TS:   // 同 JS
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyobsfimt.html

Java: synchronized (this) { shared++; }
来源：http://dali.ppjwa.cn/Article/details/gtcorwdkwy.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhixingplan.top/Article/details/gtvgatgxvy.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gaohongyu789.top/Article/details/gtkrqxaotw.html

C#:   lock (gate) { shared++; }
来源：http://dali.guannengcc.top/Article/details/gtjnhokpjt.html

[O04] 定义异步函数并等待
来源：http://dali.fzhhl.top/Article/details/gtnqyxnaei.html

Py:   async def f():⏎    await g()
来源：http://dali.yongpay.top/Article/details/gtcazubtkl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.snrcjt.cn/Article/details/gtbwduadmd.html

JS:   async function f() { await g(); }
来源：http://dali.yonumen.top/Article/details/gtqwnclxpk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlxayhrbj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.snrcjt.cn/Article/details/gtfqngehcn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhiwuduotai.top/Article/details/gtvlmnvdcl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yonumen.top/Article/details/gtgiuuggjt.html

C#:   async Task F() { await G(); }
来源：http://dali.yangfankeji.com/Article/details/gtldnumgit.html

[O05] 并发执行并等待全部完成
来源：http://dali.daxiang520.top/Article/details/gtsvsfdnab.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yongpay.top/Article/details/gtvyzseqte.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gaohongyu789.top/Article/details/gteeqrkgsm.html

JS:   await Promise.all(tasks)
来源：http://dali.jyoumei.cn/Article/details/gthshhbmct.html

TS:   await Promise.all(tasks)
来源：http://dali.ydzc1.top/Article/details/gtnhyvknma.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cdnleiting.top/Article/details/gtzwlndurx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.wangdashe.top/Article/details/gthhowcmdo.html

Ruby: threads.map(&:join)
来源：http://dali.pycfn.com/Article/details/gtnymeijpj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xuanzx.com/Article/details/gtglezawvi.html

[O06] 使用进程池
来源：http://dali.cashguo.top/Article/details/gtnlwtymqg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.0kj1m.cn/Article/details/gtdybgkxdh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.chenjidiqi.icu/Article/details/gtlfqybnro.html

JS:   // child_process / cluster 模块
来源：http://dali.sysykeji.top/Article/details/gtkefenlea.html

TS:   // child_process / cluster 模块
来源：http://dali.svipenyu.cn/Article/details/gttzlecsnm.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hnqzz.top/Article/details/gtqcwspjbm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.birdmap.top/Article/details/gtrxvpsvlz.html

Ruby: // fork 块
来源：http://dali.cucudq.cn/Article/details/gtyquyzfov.html

C#:   Parallel.For
来源：http://dali.sweek.top/Article/details/gtrrlslcry.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtwoavwcpi.html

P. 常用工具函数
来源：http://dali.iojbl.cn/Article/details/gtuicgppqw.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtwhqocatf.html

[P01] 生成 UUID
来源：http://dali.pycfn.com/Article/details/gtiyqjbtxo.html

Py:   str(uuid.uuid4())
来源：http://dali.yuanzhike.top/Article/details/gtnhojgjxf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.nwbrower.top/Article/details/gtaotpiynr.html

JS:   crypto.randomUUID()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgiesdwfn.html

TS:   crypto.randomUUID()
来源：http://dali.tian-w.cn/Article/details/gtzoixkbxn.html

Java: UUID.randomUUID().toString()
来源：http://dali.jiagoushi.top/Article/details/gtxvylnihn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jlsjyb.cn/Article/details/gtnbxiivdl.html

Ruby: SecureRandom.uuid
来源：http://dali.xinyue.icu/Article/details/gtohcibswi.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.mhx1999.top/Article/details/gtghxomdry.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hongshengwenyu.top/Article/details/gtpqxihhrl.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yj202588.top/Article/details/gtlbiencza.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtnoqxqlil.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.chenjidiqi.icu/Article/details/gtgitthnhs.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sysykeji.top/Article/details/gthwpnquut.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.birdmap.top/Article/details/gtwyikwhzz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.nanxinkj.top/Article/details/gtagrsjlit.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sxryk.cn/Article/details/gtwputgpoa.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.guowangkeji.top/Article/details/gtfxnbxixp.html

[P03] 生成短随机字符串
来源：http://dali.tianlin.xyz/Article/details/gtrpuadnsm.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.smart0.xyz/Article/details/gtpwqpxblp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sxryk.cn/Article/details/gtwskzcnmb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gogol.net.cn/Article/details/gtwbjcpwuz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tanke756.top/Article/details/gtrbmxuubk.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.guannengcc.top/Article/details/gtizorqxlb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.tianlin.xyz/Article/details/gtmvliwblh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxnbosplx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ivvv.top/Article/details/gtzfeztsbe.html

[P04] 求长度
来源：http://dali.meibo888.top/Article/details/gtackrhqbw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.svipenyu.cn/Article/details/gtggirfeui.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gtbzqxkzvs.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fzhhl.top/Article/details/gtsuwaiuli.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangtech.top/Article/details/gttebpkuoq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yangfankeji.com/Article/details/gtnmviwrun.html

Go:   len(arr);  len(m)
来源：http://dali.nanxinkj.top/Article/details/gtkruqlmsz.html

Ruby: x.length;  x.size
来源：http://dali.dianchejie.cn/Article/details/gtzmszrdxb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.nanxuanxn.top/Article/details/gtapyvwzyi.html

[P05] 判断两个对象内容是否相等
来源：http://dali.smart0.xyz/Article/details/gtxcyaptnn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jianghu66.top/Article/details/gtlulbywqv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuqildqxl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.tian-w.cn/Article/details/gtyqboxrra.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtweeinnmz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.haohaochexian.top/Article/details/gteqtkqtgg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.dianchejie.cn/Article/details/gtwsjtsexm.html

Ruby: a == b
来源：http://dali.tianlin.xyz/Article/details/gtrsyludei.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ivvv.top/Article/details/gtdedwzdcf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.birdmap.top/Article/details/gtrunpnorq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gzhubu.top/Article/details/gtgjoxqxmq.html

PHP:  if (empty($x)) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtippzitnn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cheryme.top/Article/details/gteshgpwlv.html

TS:   if (x == null) {}
来源：http://dali.cheryme.top/Article/details/gtmbsegahw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shzxlz.cn/Article/details/gtnfmjwlcu.html

Go:   if x == nil {}
来源：http://dali.redwolf501.top/Article/details/gthwegfffb.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sysykeji.top/Article/details/gtkxtclrwd.html

C#:   if (x is null) {}
来源：http://dali.zhengqikj.top/Article/details/gtbwvjicjf.html

[P07] 防抖与节流
来源：http://dali.chenzaomai.com/Article/details/gtxgrdblya.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shangyingyoupin.top/Article/details/gtvimcjbac.html

PHP:  // 手写时间戳比较
来源：http://dali.havefunace.top/Article/details/gtetfbxmkg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnxiangtu.top/Article/details/gtbatqrrab.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sufxvd.cn/Article/details/gtkssrzqtt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.cucudq.cn/Article/details/gtigkxusde.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.svipenyu.cn/Article/details/gtgtkhmcvm.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.guowangkeji.top/Article/details/gtcfmhwvjx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jinqigfzy.top/Article/details/gtswvxgysi.html

[P08] 处理浮点精度问题
来源：http://dali.xziqi.cn/Article/details/gtcfgzkjzk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.nwbrower.top/Article/details/gtmnbmhuco.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtrjraxcrs.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.daxiang520.top/Article/details/gtqsrsaepk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hnqzz.top/Article/details/gtlxhzsbus.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhixingplan.top/Article/details/gtiyruxnrq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.mhx1999.top/Article/details/gtyubmunme.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.birdmap.top/Article/details/gtkscwkwst.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yueranfly.top/Article/details/gtzxbyyopd.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtnzkxotfq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.nanxinkj.top/Article/details/gttxcwzxvj.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtrrzytoty.html

[Q01] 创建表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtucpaaisa.html

CREATE TABLE users (
来源：http://dali.wangshuangyany.cn/Article/details/gtdegviyed.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dashuyun.cn/Article/details/gtshsgrqib.html

name VARCHAR(50) NOT NULL,
来源：http://dali.bjfxy.top/Article/details/gtexavafuj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jinghuilouyu.cn/Article/details/gtldmchydd.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.iojbl.cn/Article/details/gtvifnsusg.html

);
来源：http://dali.hnqzz.top/Article/details/gtoibtptnu.html

[Q02] 创建带外键的表
来源：http://dali.daria6918.cn/Article/details/gtsnpypubs.html

CREATE TABLE orders (
来源：http://dali.mhx1999.top/Article/details/gtbijgnglt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtojmfqrqc.html

user_id INT NOT NULL,
来源：http://dali.guannengcc.top/Article/details/gtjezwtmvm.html

amount DECIMAL(10, 2),
来源：http://dali.sufxvd.cn/Article/details/gtvuapximo.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.aizwys.cn/Article/details/gtmukvhjsb.html


<!-- 参考信息 -->