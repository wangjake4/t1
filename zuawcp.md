代发 wailian999

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.bjfxy.top/Article/details/gttjvjktrh.html

JS:   process.env.HOME
来源：http://dali.zhoulong.xyz/Article/details/gtyrxpbaso.html

TS:   process.env.HOME
来源：http://dali.sysykeji.top/Article/details/gtqaifuqgq.html

Java: System.getenv("HOME")
来源：http://dali.smart0.xyz/Article/details/gtnewpqotp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gthmbuujis.html

Ruby: ENV["HOME"]
来源：http://dali.9152youxi.cn/Article/details/gtvrnaaygq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.nwbrower.top/Article/details/gtuzfegugl.html

[M03] 执行外部命令
来源：http://dali.jlsjyb.cn/Article/details/gtayltpwuq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yongpay.top/Article/details/gtykzrhcnx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hongshengwenyu.top/Article/details/gtcpncefof.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuanzx.com/Article/details/gtdwszhtrm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtsdrpcviw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ppjwa.cn/Article/details/gtkpsybzsj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.daxiang520.top/Article/details/gtvuntjxcc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.daria6918.cn/Article/details/gthrybenrc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnwykqeue.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gtesfiltfx.html

Py:   os.getcwd()
来源：http://dali.ybcxt.top/Article/details/gtwtdorbpi.html

PHP:  getcwd();
来源：http://dali.gzhubu.top/Article/details/gtphyfaajx.html

JS:   process.cwd()
来源：http://dali.zhongyouzk.top/Article/details/gtjerjulop.html

TS:   process.cwd()
来源：http://dali.yj20258888.top/Article/details/gtytamuszv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.pycfn.com/Article/details/gtdeuigjfq.html

Go:   os.Getwd()
来源：http://dali.iojbl.cn/Article/details/gtndkxzikx.html

Ruby: Dir.pwd
来源：http://dali.shuidangran.top/Article/details/gtstlnfxit.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.pengpengdd.cyou/Article/details/gtskztacfe.html

[M05] 设置退出码
来源：http://dali.yangfankeji.com/Article/details/gtisucyaxf.html

Py:   sys.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtkajtfavc.html

PHP:  exit(1);
来源：http://dali.xylfe.cn/Article/details/gtihlhnbtp.html

JS:   process.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gtxwjifnan.html

TS:   process.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gtzpclvres.html

Java: System.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gtsktvpmcv.html

Go:   os.Exit(1)
来源：http://dali.mhx1999.top/Article/details/gtftwtyckc.html

Ruby: exit 1
来源：http://dali.jinqigfzy.top/Article/details/gtqqfufqhv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gogol.net.cn/Article/details/gtsjjkzdsr.html

[M06] 向标准错误输出
来源：http://dali.cqqwz.cn/Article/details/gtfgqekzdq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhengqikj.top/Article/details/gtcfqzpurg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ivvv.top/Article/details/gtxibliocs.html

JS:   console.error("err")
来源：http://dali.hnqzz.top/Article/details/gtxchhrjlf.html

TS:   console.error("err")
来源：http://dali.yanxiufei.cn/Article/details/gtcdbvfwsa.html

Java: System.err.println("err")
来源：http://dali.jlsjyb.cn/Article/details/gtuwakuvkm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.9152youxi.cn/Article/details/gtsfhugxqs.html

Ruby: warn "err"
来源：http://dali.yj202588.top/Article/details/gtzcxrsktj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.fengsongda.top/Article/details/gtfvkbfioq.html

[M07] 判断是否为主入口
来源：http://dali.pengpengdd.cyou/Article/details/gtmfltqkdp.html

Py:   if __name__ == "__main__":
来源：http://dali.zdqjudy.top/Article/details/gtxjnbkbvg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sysykeji.top/Article/details/gtyaakkxlf.html

JS:   require.main === module
来源：http://dali.gotoacloud.top/Article/details/gtunbkkmat.html

TS:   require.main === module
来源：http://dali.gogol.net.cn/Article/details/gtgwfpbryf.html

Java: public static void main(String[] args)
来源：http://dali.0kj1m.cn/Article/details/gtysfatifc.html

Go:   func main()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxgxsgjij.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yvedp.cn/Article/details/gtaxqdpiss.html

C#:   static void Main(string[] args)
来源：http://dali.yangfankeji.com/Article/details/gtjtnhkghc.html

[M08] 获取系统与运行时信息
来源：http://dali.chenjidiqi.icu/Article/details/gtejrzqivd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.feifeiyinyue.top/Article/details/gtbdevnynn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zdqjudy.top/Article/details/gtebegvdht.html

JS:   process.platform;  process.version
来源：http://dali.hysaishi.cn/Article/details/gtpiteojuh.html

TS:   process.platform;  process.version
来源：http://dali.chenjidiqi.icu/Article/details/gtrboyhodt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhongyouzk.top/Article/details/gtgnrjrorr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jqgfzy.top/Article/details/gtjdjrjrxh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.aizwys.cn/Article/details/gteosuxzuq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.chenzaomai.com/Article/details/gtsdpaqsee.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtgkezzkco.html

N. 数据结构与算法
来源：http://dali.cqqwz.cn/Article/details/gttsmdppbc.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtkhaisrrw.html

[N01] 二分查找（有序数组）
来源：http://dali.birdmap.top/Article/details/gtgqxgqlol.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gtdujqtfdt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zdqjudy.top/Article/details/gtwkorlmfy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj202588.top/Article/details/gtclmdyiim.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ivvv.top/Article/details/gtdwxemyhs.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtgjnoltwg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.meibo888.top/Article/details/gtchjowiet.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hammf.cn/Article/details/gtprldddac.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.havefunace.top/Article/details/gtmyducbmu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.andypj.xyz/Article/details/gthhmoupqx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.smart0.xyz/Article/details/gtveknbmuv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hysaishi.cn/Article/details/gtbhrhsotb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.andypj.xyz/Article/details/gtsggnnare.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.c1oappe.top/Article/details/gtlaxhqmnf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.wangdashe.top/Article/details/gtfwoviqcc.html

Go:   slices.Sort(arr)
来源：http://dali.mhx1999.top/Article/details/gtexnwbiwi.html

Ruby: arr.sort
来源：http://dali.guannengcc.top/Article/details/gtttodqtku.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcquwtaxw.html

[N03] 快速排序（分治示例）
来源：http://dali.nanxinkj.top/Article/details/gtmfatulbn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.nanxuanxn.top/Article/details/gtehqdhbka.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yvedp.cn/Article/details/gtzgphifjk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daria6918.cn/Article/details/gtnynpiacf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hywenlv.cn/Article/details/gtbvgkxbqs.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzetszdli.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.vqdsnc.cn/Article/details/gtmxwetbwt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.daria6918.cn/Article/details/gttyldgxka.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cqqwz.cn/Article/details/gtruzbkjgs.html

[N04] 斐波那契数列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxnrwggfo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtxvrrmmmo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gotoacloud.top/Article/details/gtntfdsjia.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dashuyun.cn/Article/details/gtvotxjmvz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gtlxnfqnbn.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.daxiang520.top/Article/details/gttynlgddr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yonumen.top/Article/details/gthrvjnvxr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttqdkvjcw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinqigufen.top/Article/details/gtiuwkdkqi.html

[N05] 最大公约数
来源：http://dali.yvedp.cn/Article/details/gtiphsljqx.html

Py:   math.gcd(a, b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvbbaphau.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.tianlin.xyz/Article/details/gtgnvuleij.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yueranfly.top/Article/details/gtolpgraul.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuxming.cn/Article/details/gttujzufxh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinqigfzy.top/Article/details/gtrevkbniq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.dashuyun.cn/Article/details/gtnikjzclq.html

Ruby: a.gcd(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gttoufwsbz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinqigufen.top/Article/details/gtjyqtxmrq.html

[N06] 判断回文字符串
来源：http://dali.birdmap.top/Article/details/gtsqlaqgfd.html

Py:   s == s[::-1]
来源：http://dali.yj202588.top/Article/details/gtypgvkvrz.html

PHP:  $s === strrev($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtwavofkve.html

JS:   s === [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gtwwcfwnym.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gtdgmojstq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cqqwz.cn/Article/details/gtptujetpb.html

Go:   // 双指针从两端比较
来源：http://dali.sufxvd.cn/Article/details/gtqhwibwqf.html

Ruby: s == s.reverse
来源：http://dali.aibaodan.cn/Article/details/gtqvbfjcxq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xziqi.cn/Article/details/gtcnteaojq.html

[N07] 两数之和（返回下标）
来源：http://dali.wangdashe.top/Article/details/gtbvmbizpv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gaohongyu789.top/Article/details/gttwqflenr.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hywenlv.cn/Article/details/gtlctzwhky.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hnqzz.top/Article/details/gtpsaqiqgj.html

TS:   // 手写 Map<string, number>
来源：http://dali.shuidangran.top/Article/details/gtjxwcalbf.html

Java: // 手写 HashMap
来源：http://dali.dashuyun.cn/Article/details/gtvkecmaqz.html

Go:   // 手写 map[int]int
来源：http://dali.xinyue.icu/Article/details/gttwlzxakm.html

Ruby: // 手写 Hash
来源：http://dali.wangdashe.top/Article/details/gteycdinnm.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.nanxinkj.top/Article/details/gtrmhudewe.html

[N08] 生成全排列
来源：http://dali.zhongyouzk.top/Article/details/gtribkoykb.html

Py:   itertools.permutations(arr)
来源：http://dali.yj20258.top/Article/details/gtnxcgnqwo.html

PHP:  // 手写递归交换
来源：http://dali.hnxiangtu.top/Article/details/gtlshlvvno.html

JS:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gttaukoybb.html

TS:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gtndfkojzk.html

Java: // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gthbraleiw.html

Go:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gtvoxwnsgo.html

Ruby: arr.permutation.to_a
来源：http://dali.yongpay.top/Article/details/gtagnwptdr.html

C#:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gtgfljvptj.html

[N09] 栈与队列
来源：http://dali.sweek.top/Article/details/gtupkzwkke.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sufxvd.cn/Article/details/gtulnjnfoi.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.nwbrower.top/Article/details/gtsohiycbl.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.pycfn.com/Article/details/gtkfuptmnv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cucudq.cn/Article/details/gtprygpgyf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sxryk.cn/Article/details/gtjtvxnmbo.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.mhx1999.top/Article/details/gtlfmphbbu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yj20258.top/Article/details/gtahiyysyh.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.kuanghao11.cn/Article/details/gtmuvyhlfe.html

[N10] 链表节点定义
来源：http://dali.dianchejie.cn/Article/details/gtiegagfel.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cdnleiting.top/Article/details/gthzbgqyln.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtegxxweem.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gaohongyu789.top/Article/details/gtvfiemmvl.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrfwjykry.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gtipomxyad.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.redwolf501.top/Article/details/gtrusqcsbb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jianghu66.top/Article/details/gtrfsvmsrs.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jiagoushi.top/Article/details/gtieheghhz.html

[N11] 二叉树中序遍历
来源：http://dali.0kj1m.cn/Article/details/gtfjzeizyf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hongshengwenyu.top/Article/details/gtllsnrzet.html

PHP:  // 手写递归函数
来源：http://dali.haohaochexian.top/Article/details/gtcawxstbo.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenzaomai.com/Article/details/gtjejflvxn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigufen.top/Article/details/gtiujnahbj.html

Java: // 手写递归
来源：http://dali.zycfv.cn/Article/details/gticzvjyrx.html

Go:   // 手写递归
来源：http://dali.dashuyun.cn/Article/details/gtfzeaylli.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhoulong.xyz/Article/details/gtowpnmukl.html

C#:   // 手写递归
来源：http://dali.kuanghao11.cn/Article/details/gtxcfrdlmw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hnqzz.top/Article/details/gtslmgdfih.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cheryme.top/Article/details/gtthjshpni.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yj202588.top/Article/details/gtagihhndi.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daria6918.cn/Article/details/gtphhgduzx.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ybcxt.top/Article/details/gtkvvxxvop.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daria6918.cn/Article/details/gtbgnzgpyx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sxryk.cn/Article/details/gtqfdozeeq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gzhubu.top/Article/details/gtduqiqtef.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258888.top/Article/details/gtvtioynbg.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtdjsjhfsj.html

O. 并发与异步
来源：http://dali.pycfn.com/Article/details/gtfuenwpsh.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtbzxnbggn.html

[O01] 启动一个线程
来源：http://dali.yanxiufei.cn/Article/details/gtpclaqjov.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.tianlin.xyz/Article/details/gtshxsdvki.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cdnleiting.top/Article/details/gtsmmfyffs.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.chenzaomai.com/Article/details/gtaclxjeen.html

TS:   // 同 JS
来源：http://dali.guannengcc.top/Article/details/gtwqsmeqcn.html

Java: new Thread(() -> f()).start()
来源：http://dali.redwolf501.top/Article/details/gtdzaydvkt.html

Go:   go f()
来源：http://dali.shuidangran.top/Article/details/gtygotvfrj.html

Ruby: Thread.new { f }
来源：http://dali.pycfn.com/Article/details/gtsucqatmt.html

C#:   Task.Run(() => F());
来源：http://dali.sweek.top/Article/details/gtqkfcobfr.html

[O02] 使用线程池
来源：http://dali.nanxuanxn.top/Article/details/gtptxocxzb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yangfankeji.com/Article/details/gtbtzgjaij.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cheryme.top/Article/details/gtaihripfr.html

JS:   // worker_threads 线程池
来源：http://dali.jyoumei.cn/Article/details/gtzkcbtnii.html

TS:   // worker_threads 线程池
来源：http://dali.hywenlv.cn/Article/details/gtuzycievm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqohjurur.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jqgfzy.top/Article/details/gtykfhpcnp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gzhubu.top/Article/details/gtrhvwtvgd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.9152youxi.cn/Article/details/gtddbcayrm.html

[O03] 加锁保护共享数据
来源：http://dali.tian-w.cn/Article/details/gtpezuoect.html

Py:   with lock: shared += 1
来源：http://dali.redwolf501.top/Article/details/gtoxrxugkt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttaypmppe.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.chenzaomai.com/Article/details/gtdtdhsoly.html

TS:   // 同 JS
来源：http://dali.nwbrower.top/Article/details/gtwsrxbtow.html

Java: synchronized (this) { shared++; }
来源：http://dali.jianghu66.top/Article/details/gtecxoybot.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hnqzz.top/Article/details/gtddawjgic.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hongshengwenyu.top/Article/details/gtpfawjiri.html

C#:   lock (gate) { shared++; }
来源：http://dali.guowangkeji.top/Article/details/gtlvhmmhuo.html

[O04] 定义异步函数并等待
来源：http://dali.dashuyun.cn/Article/details/gtdzremgdg.html

Py:   async def f():⏎    await g()
来源：http://dali.c1oappe.top/Article/details/gtfnzxlkjz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbgyxwvyw.html

JS:   async function f() { await g(); }
来源：http://dali.jqgfzy.top/Article/details/gtdkxbobas.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.c1oappe.top/Article/details/gtbirfhyzw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hysaishi.cn/Article/details/gtrrwpssaa.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpezpinky.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yj20258.top/Article/details/gtgiljoocp.html

C#:   async Task F() { await G(); }
来源：http://dali.tanke756.top/Article/details/gttsztiqvm.html

[O05] 并发执行并等待全部完成
来源：http://dali.yueranfly.top/Article/details/gtnrzaxejb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.feifeiyinyue.top/Article/details/gtrrjgudve.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yongpay.top/Article/details/gtdktdufss.html

JS:   await Promise.all(tasks)
来源：http://dali.zhengqikj.top/Article/details/gtltqopxcq.html

TS:   await Promise.all(tasks)
来源：http://dali.hfpthk.cn/Article/details/gtmcuqunmr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hongshengwenyu.top/Article/details/gtqwlfbhjf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jqgufenzy.top/Article/details/gtoesqecjp.html

Ruby: threads.map(&:join)
来源：http://dali.yanxiufei.cn/Article/details/gtelwnvwih.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gtckvfbcxi.html

[O06] 使用进程池
来源：http://dali.dianchejie.cn/Article/details/gtrqccpqfy.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yongpay.top/Article/details/gtgxggpwbq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.tian-w.cn/Article/details/gtdgprwgsg.html

JS:   // child_process / cluster 模块
来源：http://dali.shuidangran.top/Article/details/gtosjkopyn.html

TS:   // child_process / cluster 模块
来源：http://dali.smart0.xyz/Article/details/gtxqpiwqkp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jyoumei.cn/Article/details/gtsbzdrfyp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xziqi.cn/Article/details/gtughxhlga.html

Ruby: // fork 块
来源：http://dali.jinqigfzy.top/Article/details/gtulrtckqw.html

C#:   Parallel.For
来源：http://dali.zhiwuduotai.top/Article/details/gtmjccyytm.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtivezsrhb.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gtifirumra.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtmepjkayp.html

[P01] 生成 UUID
来源：http://dali.shangyingyoupin.top/Article/details/gtptfcpuac.html

Py:   str(uuid.uuid4())
来源：http://dali.kuanghao11.cn/Article/details/gtbokharlr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.gaohongyu789.top/Article/details/gtjexnjzmm.html

JS:   crypto.randomUUID()
来源：http://dali.pengpengdd.cyou/Article/details/gttqwrfees.html

TS:   crypto.randomUUID()
来源：http://dali.tian-w.cn/Article/details/gtsgcephfb.html

Java: UUID.randomUUID().toString()
来源：http://dali.yonumen.top/Article/details/gtrkrbewap.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shuidangran.top/Article/details/gttvslddns.html

Ruby: SecureRandom.uuid
来源：http://dali.tanke756.top/Article/details/gthknmxwtg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.sufxvd.cn/Article/details/gtwbyvfyxd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yj20258.top/Article/details/gtqlomcddo.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xziqi.cn/Article/details/gtxqipvtyq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.dianchejie.cn/Article/details/gtjebkghen.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinyuanbaomall.cn/Article/details/gtunxlfwhh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hywenlv.cn/Article/details/gtyjbimlgg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhongyouzk.top/Article/details/gtqsbwilrg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.quarkkingdee.top/Article/details/gttobsnics.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nanxinkj.top/Article/details/gtmqnajuti.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gaohongyu789.top/Article/details/gtxejvlvym.html

[P03] 生成短随机字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtxzspdwwl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yj20258.top/Article/details/gtawodoexl.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.gogol.net.cn/Article/details/gtompknnlw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yuxming.cn/Article/details/gthivfgzti.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.guowangkeji.top/Article/details/gtzhdobsku.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhixingplan.top/Article/details/gtbfytdaks.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yuanzhike.top/Article/details/gtjhyhtllv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.aizwys.cn/Article/details/gtvtnqrptd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hnxiangtu.top/Article/details/gtszbialkl.html

[P04] 求长度
来源：http://dali.shuidangran.top/Article/details/gtmdafomhw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xylfe.cn/Article/details/gtsuxzyduv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gttrrmicrd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtljmnuskh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sysykeji.top/Article/details/gtvfodbgnh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ppjwa.cn/Article/details/gtklsijclp.html

Go:   len(arr);  len(m)
来源：http://dali.hfpthk.cn/Article/details/gtnhfazywg.html

Ruby: x.length;  x.size
来源：http://dali.jiagoushi.top/Article/details/gtrluptzhi.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yj20258888.top/Article/details/gtnyiivaol.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shanyushiyangtech.top/Article/details/gtjjwqdjof.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.fzhhl.top/Article/details/gttgjizmyk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.daxiang520.top/Article/details/gtdfxhalpq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.pycfn.com/Article/details/gtntdwhysa.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhixingplan.top/Article/details/gteinwohxj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cheryme.top/Article/details/gteijuecug.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jianghu66.top/Article/details/gtwtiewash.html

Ruby: a == b
来源：http://dali.jqgfzy.top/Article/details/gtmotepmsm.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.daxiang520.top/Article/details/gttsonkmsx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.9152youxi.cn/Article/details/gtaurorayq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.mhx1999.top/Article/details/gtrvotrcim.html

PHP:  if (empty($x)) {}
来源：http://dali.jqgfzy.top/Article/details/gtgkewarzr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jinqigufen.top/Article/details/gtslkgzcmu.html

TS:   if (x == null) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsjmsmlih.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.birdmap.top/Article/details/gtxxgssptf.html

Go:   if x == nil {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtblkcztrh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.svipenyu.cn/Article/details/gtrssjqstc.html

C#:   if (x is null) {}
来源：http://dali.zhengqikj.top/Article/details/gtykizuihv.html

[P07] 防抖与节流
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqrocstek.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xinyue.icu/Article/details/gtwbpjeppy.html

PHP:  // 手写时间戳比较
来源：http://dali.dashuyun.cn/Article/details/gtqtzwwaxa.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.c1oappe.top/Article/details/gtyfebylsb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxuanxn.top/Article/details/gtmqxrvret.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zdqjudy.top/Article/details/gttwzsmrss.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.snrcjt.cn/Article/details/gtyrnnydsw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yueranfly.top/Article/details/gtgsuzxqny.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hysaishi.cn/Article/details/gtokiyhsww.html

[P08] 处理浮点精度问题
来源：http://dali.hywenlv.cn/Article/details/gtrokehoqn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.mhx1999.top/Article/details/gtaincqozq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yonumen.top/Article/details/gtcqoymorx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.vqdsnc.cn/Article/details/gtbtxufmmv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhongyouzk.top/Article/details/gtjicbmohd.html


<!-- 参考信息 -->