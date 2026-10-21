代发 wailian999

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yj20258888.top/Article/details/gtrtiqoxkk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gaohongyu789.top/Article/details/gtlrlspbkj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ppjwa.cn/Article/details/gtrydsvhvg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sxryk.cn/Article/details/gtqktwvikw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhongyouzk.top/Article/details/gttjlelirj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.dashuyun.cn/Article/details/gtvkjjnzvh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.aibaodan.cn/Article/details/gtduhqprbb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cqqwz.cn/Article/details/gtfikocwzg.html

[M04] 获取当前工作目录
来源：http://dali.dianchejie.cn/Article/details/gtrqmacohk.html

Py:   os.getcwd()
来源：http://dali.chenzaomai.com/Article/details/gtyyzmjlqz.html

PHP:  getcwd();
来源：http://dali.yangfankeji.com/Article/details/gtegpipyjp.html

JS:   process.cwd()
来源：http://dali.guowangkeji.top/Article/details/gtvpohtkfx.html

TS:   process.cwd()
来源：http://dali.chenzaomai.com/Article/details/gtibgqddoc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.quarkkingdee.top/Article/details/gtwwiyjkvo.html

Go:   os.Getwd()
来源：http://dali.meibo888.top/Article/details/gtgukhzhkz.html

Ruby: Dir.pwd
来源：http://dali.meibo888.top/Article/details/gtfhxoszco.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenzaomai.com/Article/details/gtvlglcapg.html

[M05] 设置退出码
来源：http://dali.ivvv.top/Article/details/gtehivjrrw.html

Py:   sys.exit(1)
来源：http://dali.daxiang520.top/Article/details/gtulxxwczm.html

PHP:  exit(1);
来源：http://dali.sysykeji.top/Article/details/gtqvguqvru.html

JS:   process.exit(1)
来源：http://dali.daria6918.cn/Article/details/gtvmsmapfa.html

TS:   process.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gtliqgxsnu.html

Java: System.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gtqtnfnrzg.html

Go:   os.Exit(1)
来源：http://dali.jinqigufen.top/Article/details/gtalswkuzo.html

Ruby: exit 1
来源：http://dali.chenjidiqi.icu/Article/details/gtyyatxpwi.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.mhx1999.top/Article/details/gticnralka.html

[M06] 向标准错误输出
来源：http://dali.yueranfly.top/Article/details/gttumoelss.html

Py:   print("err", file=sys.stderr)
来源：http://dali.bjfxy.top/Article/details/gtyqbrfcix.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.tian-w.cn/Article/details/gtmxmyirds.html

JS:   console.error("err")
来源：http://dali.vqdsnc.cn/Article/details/gtceginodw.html

TS:   console.error("err")
来源：http://dali.daria6918.cn/Article/details/gtlepcgxch.html

Java: System.err.println("err")
来源：http://dali.jyoumei.cn/Article/details/gtnictuipo.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj20258.top/Article/details/gtahpiyfcb.html

Ruby: warn "err"
来源：http://dali.sxryk.cn/Article/details/gthwtfowbl.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cucudq.cn/Article/details/gtvmjvexlr.html

[M07] 判断是否为主入口
来源：http://dali.aibaodan.cn/Article/details/gtqgyoimif.html

Py:   if __name__ == "__main__":
来源：http://dali.yuxming.cn/Article/details/gtdlftqubf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.chenzaomai.com/Article/details/gtnjwitrxl.html

JS:   require.main === module
来源：http://dali.sweek.top/Article/details/gtvmsedvsv.html

TS:   require.main === module
来源：http://dali.wangshuangyany.cn/Article/details/gtwrzkfxvg.html

Java: public static void main(String[] args)
来源：http://dali.xziqi.cn/Article/details/gtjjdadzdc.html

Go:   func main()
来源：http://dali.xinyue.icu/Article/details/gtdxewzfep.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.birdmap.top/Article/details/gtfhiejmup.html

C#:   static void Main(string[] args)
来源：http://dali.xuetiantiany.cn/Article/details/gtmforglmi.html

[M08] 获取系统与运行时信息
来源：http://dali.cqqwz.cn/Article/details/gtwqrgadsf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.tanke756.top/Article/details/gtcoegppzr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.pycfn.com/Article/details/gtblcbtldx.html

JS:   process.platform;  process.version
来源：http://dali.dashuyun.cn/Article/details/gtkujygxmb.html

TS:   process.platform;  process.version
来源：http://dali.cdnleiting.top/Article/details/gtghjeswsf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cdnleiting.top/Article/details/gtcllizhoo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.nanxuanxn.top/Article/details/gtntutkjov.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.fengsongda.top/Article/details/gtdhqdydyv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xziqi.cn/Article/details/gtsjzoedfw.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtruuzprqm.html

N. 数据结构与算法
来源：http://dali.yuanzhike.top/Article/details/gtyxagveub.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtfargatxj.html

[N01] 二分查找（有序数组）
来源：http://dali.yuanzhike.top/Article/details/gtpfcgqthd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gthlljwdic.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhengqikj.top/Article/details/gtwjqtenbo.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258.top/Article/details/gtzbjeaqws.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuxming.cn/Article/details/gtlmqrkhls.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtgdzflfbf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.wangdashe.top/Article/details/gttjpjdhzk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.haohaochexian.top/Article/details/gtujnrlxos.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtrsjsnhbf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ivvv.top/Article/details/gtipmdaqgg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pengpengdd.cyou/Article/details/gtmpenvmjs.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yj20258888.top/Article/details/gtpfncumfh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxinkj.top/Article/details/gtvlauvsta.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fengsongda.top/Article/details/gtknttsxfw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.chenlongwang.top/Article/details/gtnqggfcux.html

Go:   slices.Sort(arr)
来源：http://dali.yj202588.top/Article/details/gtibkjfemo.html

Ruby: arr.sort
来源：http://dali.jqgfzy.top/Article/details/gtovfwydzw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.meibo888.top/Article/details/gtbpvouydj.html

[N03] 快速排序（分治示例）
来源：http://dali.jlsjyb.cn/Article/details/gtyxoicruk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ehwqpu.com/Article/details/gthropfjbn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shzxlz.cn/Article/details/gtyuwgdnvx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zdqjudy.top/Article/details/gtudjolgsl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yueranfly.top/Article/details/gtqvicnrwh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.snrcjt.cn/Article/details/gtjcrwtahk.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sysykeji.top/Article/details/gtmdjbiaso.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xinyue.icu/Article/details/gtoiluihcu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.meibo888.top/Article/details/gtimjrojpd.html

[N04] 斐波那契数列
来源：http://dali.chenlongwang.top/Article/details/gtxrizwsdn.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ppjwa.cn/Article/details/gtcnltabcr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.316326.xyz/Article/details/gtkbpjfmqw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gotoacloud.top/Article/details/gttyfkhqvn.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhoulong.xyz/Article/details/gtiiyonxut.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jlsjyb.cn/Article/details/gtwtdsppmd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.dashuyun.cn/Article/details/gtvdaqegsr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gotoacloud.top/Article/details/gtgmgwusxa.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yuxming.cn/Article/details/gtxtzwkvtp.html

[N05] 最大公约数
来源：http://dali.jqgfzy.top/Article/details/gtnyvwaonv.html

Py:   math.gcd(a, b)
来源：http://dali.hnqzz.top/Article/details/gtnoanyzzr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sufxvd.cn/Article/details/gtiwxslram.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yvedp.cn/Article/details/gtgajwtxgp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tian-w.cn/Article/details/gtgetzykff.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.daria6918.cn/Article/details/gtnvxurtlo.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gtoweidzsa.html

Ruby: a.gcd(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtayodsdzf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gaohongyu789.top/Article/details/gtkkhlomus.html

[N06] 判断回文字符串
来源：http://dali.dashuyun.cn/Article/details/gtyrlxotkq.html

Py:   s == s[::-1]
来源：http://dali.guannengcc.top/Article/details/gtlgybxttz.html

PHP:  $s === strrev($s);
来源：http://dali.birdmap.top/Article/details/gtfocsbvdn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gtuyskfcfg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gtsddqmltb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.pengpengdd.cyou/Article/details/gtzqhfmarb.html

Go:   // 双指针从两端比较
来源：http://dali.pengpengdd.cyou/Article/details/gtizvljiqc.html

Ruby: s == s.reverse
来源：http://dali.pycfn.com/Article/details/gtbappdoga.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.birdmap.top/Article/details/gtjrrtpfda.html

[N07] 两数之和（返回下标）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuxtqcsch.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jqgufenzy.top/Article/details/gtvvheekob.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.mhx1999.top/Article/details/gteoxehcpi.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jianghu66.top/Article/details/gtpvpexgvk.html

TS:   // 手写 Map<string, number>
来源：http://dali.quarkkingdee.top/Article/details/gtikzmcwng.html

Java: // 手写 HashMap
来源：http://dali.zhiwuduotai.top/Article/details/gtlpeigwve.html

Go:   // 手写 map[int]int
来源：http://dali.ivvv.top/Article/details/gtpggjuvdo.html

Ruby: // 手写 Hash
来源：http://dali.cashguo.top/Article/details/gtjtzaymjx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.pengpengdd.cyou/Article/details/gtkqgujixi.html

[N08] 生成全排列
来源：http://dali.wangshuangyany.cn/Article/details/gtgnjoihrs.html

Py:   itertools.permutations(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtkyqytcsu.html

PHP:  // 手写递归交换
来源：http://dali.wangdashe.top/Article/details/gtqjhulbwq.html

JS:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtaqiupley.html

TS:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrgceqnel.html

Java: // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gtlxcqlxss.html

Go:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gttumstkpt.html

Ruby: arr.permutation.to_a
来源：http://dali.havefunace.top/Article/details/gttiwwzrsn.html

C#:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gtiedxewan.html

[N09] 栈与队列
来源：http://dali.c1oappe.top/Article/details/gtxpqnlewy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hnxiangtu.top/Article/details/gtucmmgsfo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yuxming.cn/Article/details/gtytudpdxj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xuanzx.com/Article/details/gtthisbmym.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.guannengcc.top/Article/details/gtjevxfcit.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.haohaochexian.top/Article/details/gtodclaohz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cdnleiting.top/Article/details/gtvrhykbcu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cucudq.cn/Article/details/gtcpdsaicr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hywenlv.cn/Article/details/gtswxthrjg.html

[N10] 链表节点定义
来源：http://dali.fengsongda.top/Article/details/gtwegbmkfw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.aibaodan.cn/Article/details/gtyudlyiyt.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sysykeji.top/Article/details/gtvchbweet.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.nanxinkj.top/Article/details/gthaedhkoq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xuanzx.com/Article/details/gtpkbvrosy.html

Java: class Node { int v; Node next; }
来源：http://dali.yj20258888.top/Article/details/gtfhnjrejt.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.andypj.xyz/Article/details/gticzndmmi.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shuidangran.top/Article/details/gtopegsybd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.c1oappe.top/Article/details/gtgikwjnho.html

[N11] 二叉树中序遍历
来源：http://dali.dianchejie.cn/Article/details/gtmejrynoe.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ehwqpu.com/Article/details/gtkxoioana.html

PHP:  // 手写递归函数
来源：http://dali.zhiwuduotai.top/Article/details/gthtybixwu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daxiang520.top/Article/details/gtyspyyawv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigufen.top/Article/details/gtyduexxmb.html

Java: // 手写递归
来源：http://dali.shangyingyoupin.top/Article/details/gtuxvybqzj.html

Go:   // 手写递归
来源：http://dali.hfpthk.cn/Article/details/gtslxhrrgu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.c1oappe.top/Article/details/gtfiwcepqo.html

C#:   // 手写递归
来源：http://dali.cucudq.cn/Article/details/gttiojauhd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shanyushiyangtech.top/Article/details/gtoriiqsur.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gzhubu.top/Article/details/gtmwcxneeb.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhengqikj.top/Article/details/gtyuuethvm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fzhhl.top/Article/details/gtzjfjbhbc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrkdebnjg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guowangkeji.top/Article/details/gtmqwwmuse.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.snrcjt.cn/Article/details/gtybofirav.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.wangdashe.top/Article/details/gthioimrqb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj202588.top/Article/details/gtbwprkkyu.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtkoyzmkve.html

O. 并发与异步
来源：http://dali.sweek.top/Article/details/gtpocemimj.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtochehtze.html

[O01] 启动一个线程
来源：http://dali.jqgfzy.top/Article/details/gtbhkquvui.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.pengpengdd.cyou/Article/details/gtwjjwrtkm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.fengsongda.top/Article/details/gtcbxiglfo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.daxiang520.top/Article/details/gtprerwzhl.html

TS:   // 同 JS
来源：http://dali.zdqjudy.top/Article/details/gtuyzgxymr.html

Java: new Thread(() -> f()).start()
来源：http://dali.xuetiantiany.cn/Article/details/gtzywuwrjf.html

Go:   go f()
来源：http://dali.hammf.cn/Article/details/gtbpyfeeon.html

Ruby: Thread.new { f }
来源：http://dali.yj20258888.top/Article/details/gtalmjozmp.html

C#:   Task.Run(() => F());
来源：http://dali.pycfn.com/Article/details/gthucddhnr.html

[O02] 使用线程池
来源：http://dali.hnxiangtu.top/Article/details/gtvghjooiw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cheryme.top/Article/details/gtgheeadih.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jqgfzy.top/Article/details/gtabqblsub.html

JS:   // worker_threads 线程池
来源：http://dali.sufxvd.cn/Article/details/gtxdcoerdz.html

TS:   // worker_threads 线程池
来源：http://dali.xylfe.cn/Article/details/gtuwlgpvob.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.pycfn.com/Article/details/gtuyapzjpm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cashguo.top/Article/details/gtvzjuneuq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.9152youxi.cn/Article/details/gtgnhqljef.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zycfv.cn/Article/details/gtxaogxqbo.html

[O03] 加锁保护共享数据
来源：http://dali.bjfxy.top/Article/details/gtkycwllvz.html

Py:   with lock: shared += 1
来源：http://dali.svipenyu.cn/Article/details/gtabdvydjn.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.andypj.xyz/Article/details/gtxpadhkwj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.nanxinkj.top/Article/details/gtxjhvbszx.html

TS:   // 同 JS
来源：http://dali.quarkkingdee.top/Article/details/gtinzgmdbj.html

Java: synchronized (this) { shared++; }
来源：http://dali.hysaishi.cn/Article/details/gtjuucfpyq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zdqjudy.top/Article/details/gtzhjwsegd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jqgfzy.top/Article/details/gtxeiyxpee.html

C#:   lock (gate) { shared++; }
来源：http://dali.xinyue.icu/Article/details/gtinsyesrr.html

[O04] 定义异步函数并等待
来源：http://dali.jinqigufen.top/Article/details/gtacekfllx.html

Py:   async def f():⏎    await g()
来源：http://dali.gzhubu.top/Article/details/gtbpesvutz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yanxiufei.cn/Article/details/gtcyvvwync.html

JS:   async function f() { await g(); }
来源：http://dali.zycfv.cn/Article/details/gtydpefvct.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hysaishi.cn/Article/details/gtaoqhzvbr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.pengpengdd.cyou/Article/details/gtinwvbgrr.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj202588.top/Article/details/gtiqvaayam.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.daria6918.cn/Article/details/gtqvagvyns.html

C#:   async Task F() { await G(); }
来源：http://dali.guannengcc.top/Article/details/gtnwamxbnp.html

[O05] 并发执行并等待全部完成
来源：http://dali.xylfe.cn/Article/details/gtdjtbwqyh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.pycfn.com/Article/details/gtkihetkpd.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ehwqpu.com/Article/details/gtsbfjucpz.html

JS:   await Promise.all(tasks)
来源：http://dali.andypj.xyz/Article/details/gtqsohghfz.html

TS:   await Promise.all(tasks)
来源：http://dali.chenjidiqi.icu/Article/details/gthhcrlmcc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinghuilouyu.cn/Article/details/gtjztktozt.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shzxlz.cn/Article/details/gtilfwfooh.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gtyztyjrmh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.havefunace.top/Article/details/gtuflnfgpi.html

[O06] 使用进程池
来源：http://dali.chenjidiqi.icu/Article/details/gtatxzqdrh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yuxming.cn/Article/details/gtrhguzngm.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ivvv.top/Article/details/gtkcwfstwu.html

JS:   // child_process / cluster 模块
来源：http://dali.yanxiufei.cn/Article/details/gtxoqjbyrm.html

TS:   // child_process / cluster 模块
来源：http://dali.gzhubu.top/Article/details/gtsrhfeomq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yvedp.cn/Article/details/gtvoxooput.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.chenjidiqi.icu/Article/details/gtmbfxewyl.html

Ruby: // fork 块
来源：http://dali.yuanzhike.top/Article/details/gthmhelruw.html

C#:   Parallel.For
来源：http://dali.cashguo.top/Article/details/gtbrdwusbm.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gttyejlwty.html

P. 常用工具函数
来源：http://dali.xuetiantiany.cn/Article/details/gtbyicjjba.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtzloizorg.html

[P01] 生成 UUID
来源：http://dali.jianghu66.top/Article/details/gtbblummmm.html

Py:   str(uuid.uuid4())
来源：http://dali.zhiwuduotai.top/Article/details/gtaxuzvmlg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.wangshuangyany.cn/Article/details/gtoeyzffjb.html

JS:   crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgnjxgjbo.html

TS:   crypto.randomUUID()
来源：http://dali.zhengqikj.top/Article/details/gtytyaxtaq.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhixingplan.top/Article/details/gtvljfdkdw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.guowangkeji.top/Article/details/gtcfvkiatb.html

Ruby: SecureRandom.uuid
来源：http://dali.yongpay.top/Article/details/gtkyehogoh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhixingplan.top/Article/details/gtbmbfiopp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxvcybeba.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gzhubu.top/Article/details/gtlaeomkes.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrqklacgi.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jyoumei.cn/Article/details/gtfrapibsp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cdnleiting.top/Article/details/gtqszoavaw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.guannengcc.top/Article/details/gttqzuoiaa.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cashguo.top/Article/details/gtimpietwx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nwbrower.top/Article/details/gtvmprabjq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jianghu66.top/Article/details/gtxwojwfuw.html

[P03] 生成短随机字符串
来源：http://dali.sufxvd.cn/Article/details/gtmeosrtqp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jinqigufen.top/Article/details/gtxjbjhtwb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhongyouzk.top/Article/details/gtaogrguql.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.fengsongda.top/Article/details/gtzzhqhtwz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.kuanghao11.cn/Article/details/gtagbtykbf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.9152youxi.cn/Article/details/gtwyxwtgek.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xuetiantiany.cn/Article/details/gtlibsllxg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.iojbl.cn/Article/details/gtevlaclfa.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yuxming.cn/Article/details/gttbhxqfau.html

[P04] 求长度
来源：http://dali.fzhhl.top/Article/details/gtwddknavy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tian-w.cn/Article/details/gtzukiqreu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gtbwgdzniy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gzhubu.top/Article/details/gtqqmwlafg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yueranfly.top/Article/details/gtelwfciay.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sysykeji.top/Article/details/gtnzythiqj.html

Go:   len(arr);  len(m)
来源：http://dali.daxiang520.top/Article/details/gtqcrxcorf.html

Ruby: x.length;  x.size
来源：http://dali.yvedp.cn/Article/details/gtbekkknkg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cashguo.top/Article/details/gtwcfizolv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zdqjudy.top/Article/details/gtuculdcos.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinghuilouyu.cn/Article/details/gtgzvneadi.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.dashuyun.cn/Article/details/gtoyuuzewz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.0kj1m.cn/Article/details/gtgmvgnqfg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ppjwa.cn/Article/details/gtaxrjqjpy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ehwqpu.com/Article/details/gttyemuezp.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cashguo.top/Article/details/gtiifqtlno.html

Ruby: a == b
来源：http://dali.9152youxi.cn/Article/details/gtbcyicofh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cqqwz.cn/Article/details/gtujqgxdma.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sufxvd.cn/Article/details/gtqpiqyorh.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yongpay.top/Article/details/gtrurcemgi.html

PHP:  if (empty($x)) {}
来源：http://dali.cheryme.top/Article/details/gtpsgajmja.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.bjfxy.top/Article/details/gtwmbdblxc.html

TS:   if (x == null) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxwhnxuyd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yj202588.top/Article/details/gtzojtqvil.html

Go:   if x == nil {}
来源：http://dali.nanxuanxn.top/Article/details/gtpxmyjrlq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.aibaodan.cn/Article/details/gtmuaoevfw.html

C#:   if (x is null) {}
来源：http://dali.aibaodan.cn/Article/details/gtriwzhnet.html

[P07] 防抖与节流
来源：http://dali.dashuyun.cn/Article/details/gtztwgxvym.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.redwolf501.top/Article/details/gtgjddncyn.html

PHP:  // 手写时间戳比较
来源：http://dali.ivvv.top/Article/details/gttdpiakqw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xinyue.icu/Article/details/gtuyvkwadd.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sweek.top/Article/details/gtfjqnvgvq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtgotvrzgs.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jianghu66.top/Article/details/gtbtvtfhtj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hysaishi.cn/Article/details/gtepiebcir.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.snrcjt.cn/Article/details/gtqmtniupi.html

[P08] 处理浮点精度问题
来源：http://dali.shanyushiyangtech.top/Article/details/gtiduwjizr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hywenlv.cn/Article/details/gtczdrhzml.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhengqikj.top/Article/details/gthvboogbq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.fzhhl.top/Article/details/gtrbopnqus.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhongyouzk.top/Article/details/gtvzampnum.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yueranfly.top/Article/details/gtfacylojl.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.guowangkeji.top/Article/details/gtankhaowi.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.daria6918.cn/Article/details/gthisdlvbs.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.gzhubu.top/Article/details/gtrnxbdisy.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtwptsfgch.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ppjwa.cn/Article/details/gtzpipwlof.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtichhdveo.html

[Q01] 创建表
来源：http://dali.ydzc1.top/Article/details/gteemaaept.html


<!-- 参考信息 -->