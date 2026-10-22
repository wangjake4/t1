代发 wailian999

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtljpokxjf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhengqikj.top/Article/details/gthopximdc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.daria6918.cn/Article/details/gtwvbtcief.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhengqikj.top/Article/details/gththehonv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinqigufen.top/Article/details/gtnrmzhmfh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xziqi.cn/Article/details/gtyyznagcj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yueranfly.top/Article/details/gtwkizotlb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jlsjyb.cn/Article/details/gtdzpbtcgs.html

[M04] 获取当前工作目录
来源：http://dali.daria6918.cn/Article/details/gtjaoipejd.html

Py:   os.getcwd()
来源：http://dali.zhixingplan.top/Article/details/gtuyqoteft.html

PHP:  getcwd();
来源：http://dali.hysaishi.cn/Article/details/gtnzrnlfgk.html

JS:   process.cwd()
来源：http://dali.snrcjt.cn/Article/details/gtdymscdvh.html

TS:   process.cwd()
来源：http://dali.jianghu66.top/Article/details/gtlyslxsft.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.tanke756.top/Article/details/gtwknywuzn.html

Go:   os.Getwd()
来源：http://dali.shzxlz.cn/Article/details/gtvycpnwjt.html

Ruby: Dir.pwd
来源：http://dali.xylfe.cn/Article/details/gteoiaryml.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ydzc1.top/Article/details/gtwzkxuhci.html

[M05] 设置退出码
来源：http://dali.yj202588.top/Article/details/gteahedvvp.html

Py:   sys.exit(1)
来源：http://dali.smart0.xyz/Article/details/gtpcnaonbe.html

PHP:  exit(1);
来源：http://dali.aizwys.cn/Article/details/gtnaodrdyt.html

JS:   process.exit(1)
来源：http://dali.cashguo.top/Article/details/gtpuwlzqbh.html

TS:   process.exit(1)
来源：http://dali.yonumen.top/Article/details/gtvmzajlny.html

Java: System.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtfieytjlp.html

Go:   os.Exit(1)
来源：http://dali.hfpthk.cn/Article/details/gtvndbxxma.html

Ruby: exit 1
来源：http://dali.c1oappe.top/Article/details/gtkasoqhck.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hnqzz.top/Article/details/gtyuzxrgel.html

[M06] 向标准错误输出
来源：http://dali.xuetiantiany.cn/Article/details/gtbqnudrzg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hongshengwenyu.top/Article/details/gtkbzeujpl.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.chenlongwang.top/Article/details/gtymxtvypz.html

JS:   console.error("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwtbcsnmi.html

TS:   console.error("err")
来源：http://dali.nanxinkj.top/Article/details/gtuxjvtgdb.html

Java: System.err.println("err")
来源：http://dali.meibo888.top/Article/details/gtprrbwwwm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jyoumei.cn/Article/details/gtddvlbojk.html

Ruby: warn "err"
来源：http://dali.xinyue.icu/Article/details/gtcafswgqw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.kuanghao11.cn/Article/details/gteteymscd.html

[M07] 判断是否为主入口
来源：http://dali.jqgfzy.top/Article/details/gtxizhuhyx.html

Py:   if __name__ == "__main__":
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtujcfrges.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinghuilouyu.cn/Article/details/gtdyonizge.html

JS:   require.main === module
来源：http://dali.zhiwuduotai.top/Article/details/gtzbtsqeiv.html

TS:   require.main === module
来源：http://dali.sweek.top/Article/details/gtlkossgdu.html

Java: public static void main(String[] args)
来源：http://dali.ppjwa.cn/Article/details/gtxmqndnkh.html

Go:   func main()
来源：http://dali.jinqigufen.top/Article/details/gtsgeawzbn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.nanxinkj.top/Article/details/gtsumjlanf.html

C#:   static void Main(string[] args)
来源：http://dali.zdqjudy.top/Article/details/gttwomwdyn.html

[M08] 获取系统与运行时信息
来源：http://dali.cdnleiting.top/Article/details/gtfnuxrozr.html

Py:   platform.system();  platform.python_version()
来源：http://dali.daria6918.cn/Article/details/gtewxwjfbg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.aizwys.cn/Article/details/gtqqporquc.html

JS:   process.platform;  process.version
来源：http://dali.xuetiantiany.cn/Article/details/gthomczbty.html

TS:   process.platform;  process.version
来源：http://dali.hnxiangtu.top/Article/details/gtbwsbwozl.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yangfankeji.com/Article/details/gtiiphrtgt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xuanzx.com/Article/details/gtzjokoqln.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.havefunace.top/Article/details/gtlybjagoz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yuxming.cn/Article/details/gtrvjokepz.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtvnqiqtaf.html

N. 数据结构与算法
来源：http://dali.hnqzz.top/Article/details/gtdulyahsv.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtlofaugdq.html

[N01] 二分查找（有序数组）
来源：http://dali.feifeiyinyue.top/Article/details/gtbqbnhkax.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtyyniznee.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvqcpxqrw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinghuilouyu.cn/Article/details/gtyqzwolgr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zycfv.cn/Article/details/gtcynibono.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgpvbgcpb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtunsbohwr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gaohongyu789.top/Article/details/gtuyzfevwa.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gthzcyclnv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.c1oappe.top/Article/details/gtpfwwcbtr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.smart0.xyz/Article/details/gtbfuxhzsp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.birdmap.top/Article/details/gtgifagjjl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sufxvd.cn/Article/details/gtnojpmzeh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pengpengdd.cyou/Article/details/gtqjimhecn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jianghu66.top/Article/details/gthbhpcvvw.html

Go:   slices.Sort(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtavejqtdf.html

Ruby: arr.sort
来源：http://dali.aibaodan.cn/Article/details/gtyfcxxuwq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cucudq.cn/Article/details/gtanfkhqdw.html

[N03] 快速排序（分治示例）
来源：http://dali.svipenyu.cn/Article/details/gtwjxcdviq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ivvv.top/Article/details/gtiomvhrre.html

PHP:  // 递归实现，或用 usort
来源：http://dali.9152youxi.cn/Article/details/gtlezppdxx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yongpay.top/Article/details/gtgjxanank.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigfzy.top/Article/details/gtjjeuhyrh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.aibaodan.cn/Article/details/gtmbkljnna.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jiagoushi.top/Article/details/gtcqkjdwjl.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.guannengcc.top/Article/details/gtmlhwaiyt.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xuetiantiany.cn/Article/details/gtwiledxeo.html

[N04] 斐波那契数列
来源：http://dali.jqgufenzy.top/Article/details/gtcwewhics.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.fengsongda.top/Article/details/gtqtvlxncr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hammf.cn/Article/details/gthlhbpbzq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gtydxwmvwg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gtivzcygtv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jianghu66.top/Article/details/gtgmkwamli.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jyoumei.cn/Article/details/gtdlcvybdc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.andypj.xyz/Article/details/gtynqszyhc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hammf.cn/Article/details/gtznzsvcfi.html

[N05] 最大公约数
来源：http://dali.mhx1999.top/Article/details/gtsufevqpa.html

Py:   math.gcd(a, b)
来源：http://dali.aibaodan.cn/Article/details/gtnbhywjai.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cheryme.top/Article/details/gtxfwimwtq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zdqjudy.top/Article/details/gtdncjuunw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yueranfly.top/Article/details/gtfhzqbzpc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.chenlongwang.top/Article/details/gtheyicuqf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlungtdwb.html

Ruby: a.gcd(b)
来源：http://dali.ivvv.top/Article/details/gtqxwqfoqx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.guannengcc.top/Article/details/gtdolapctx.html

[N06] 判断回文字符串
来源：http://dali.iojbl.cn/Article/details/gtvieyzfgc.html

Py:   s == s[::-1]
来源：http://dali.hnxiangtu.top/Article/details/gtmsshqogx.html

PHP:  $s === strrev($s);
来源：http://dali.fzhhl.top/Article/details/gtciipnujb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gtsxqszbix.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gtgnzsgthm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhiwuduotai.top/Article/details/gtbfiyvhlj.html

Go:   // 双指针从两端比较
来源：http://dali.wangshuangyany.cn/Article/details/gtoywynjwe.html

Ruby: s == s.reverse
来源：http://dali.chenzaomai.com/Article/details/gtcobkkvgm.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jiagoushi.top/Article/details/gtiyikxmal.html

[N07] 两数之和（返回下标）
来源：http://dali.jyoumei.cn/Article/details/gtrrfhhair.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ppjwa.cn/Article/details/gtywalawal.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xylfe.cn/Article/details/gttwehtwrm.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpdjohefg.html

TS:   // 手写 Map<string, number>
来源：http://dali.ydzc1.top/Article/details/gtkjnnvdgf.html

Java: // 手写 HashMap
来源：http://dali.cucudq.cn/Article/details/gtcyxpbfaq.html

Go:   // 手写 map[int]int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtczqqdewo.html

Ruby: // 手写 Hash
来源：http://dali.zhengqikj.top/Article/details/gtiqfceayx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hammf.cn/Article/details/gtbmbktmsb.html

[N08] 生成全排列
来源：http://dali.jyoumei.cn/Article/details/gtxkpdwbme.html

Py:   itertools.permutations(arr)
来源：http://dali.andypj.xyz/Article/details/gtfbhsoprk.html

PHP:  // 手写递归交换
来源：http://dali.jlsjyb.cn/Article/details/gttpfpzdyc.html

JS:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gtovcmhrmx.html

TS:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gttdyrxnze.html

Java: // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtgsecarug.html

Go:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gteeuhpdyq.html

Ruby: arr.permutation.to_a
来源：http://dali.zhaomingkeji.xyz/Article/details/gtasoxhmoo.html

C#:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtxuhqxcfz.html

[N09] 栈与队列
来源：http://dali.gotoacloud.top/Article/details/gtirijikic.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.birdmap.top/Article/details/gtyhybannf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.guowangkeji.top/Article/details/gtwxajifqe.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhongyouzk.top/Article/details/gtwgyubgvo.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.tanke756.top/Article/details/gtiktyvkjg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jyoumei.cn/Article/details/gtcipkfwly.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.haohaochexian.top/Article/details/gttxffntgs.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.pengpengdd.cyou/Article/details/gtcsltyysd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xylfe.cn/Article/details/gtdjfiockm.html

[N10] 链表节点定义
来源：http://dali.hnxiangtu.top/Article/details/gtuoaogvci.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hongshengwenyu.top/Article/details/gtsvtssfux.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.pycfn.com/Article/details/gtapuopuqd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.dianchejie.cn/Article/details/gtohxbbvcn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yuxming.cn/Article/details/gturhpqehs.html

Java: class Node { int v; Node next; }
来源：http://dali.daxiang520.top/Article/details/gtcfpobfii.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yanxiufei.cn/Article/details/gtqbfdotmt.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yanxiufei.cn/Article/details/gtusbasktd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.mhx1999.top/Article/details/gtcychvdnr.html

[N11] 二叉树中序遍历
来源：http://dali.hnqzz.top/Article/details/gttxtdadzb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hywenlv.cn/Article/details/gtzujumhhr.html

PHP:  // 手写递归函数
来源：http://dali.xziqi.cn/Article/details/gtwmfpsuba.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yvedp.cn/Article/details/gtextznazh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.316326.xyz/Article/details/gtjmwywqkb.html

Java: // 手写递归
来源：http://dali.jinqigufen.top/Article/details/gtxukukeet.html

Go:   // 手写递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxdhyivao.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.mhx1999.top/Article/details/gtzqyxbuqb.html

C#:   // 手写递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtohlawifu.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzkkaviie.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xuanzx.com/Article/details/gtethqrrhg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.iojbl.cn/Article/details/gtdbhgojjm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ybcxt.top/Article/details/gtjqrwhcfj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.c1oappe.top/Article/details/gtkvayrcir.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cqqwz.cn/Article/details/gtxpwnzezx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.feifeiyinyue.top/Article/details/gtjchzjwuk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.aizwys.cn/Article/details/gtjchhawhy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj202588.top/Article/details/gtzrpjwcve.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gthchmmlar.html

O. 并发与异步
来源：http://dali.shanyushiyangtech.top/Article/details/gtoohhlrqn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtbjfaursb.html

[O01] 启动一个线程
来源：http://dali.hysaishi.cn/Article/details/gttnjtsuqk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.quarkkingdee.top/Article/details/gtrwhfspxc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yj20258.top/Article/details/gtpsczwcme.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hfpthk.cn/Article/details/gtbqyirdst.html

TS:   // 同 JS
来源：http://dali.aibaodan.cn/Article/details/gtnvxgobal.html

Java: new Thread(() -> f()).start()
来源：http://dali.hysaishi.cn/Article/details/gtmrkgqznh.html

Go:   go f()
来源：http://dali.dianchejie.cn/Article/details/gttvzapoar.html

Ruby: Thread.new { f }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrsuyukrv.html

C#:   Task.Run(() => F());
来源：http://dali.hongshengwenyu.top/Article/details/gtbmznfdwd.html

[O02] 使用线程池
来源：http://dali.xylfe.cn/Article/details/gtqofaiyge.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yongpay.top/Article/details/gtsdkkocfl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.smart0.xyz/Article/details/gttwoalcoh.html

JS:   // worker_threads 线程池
来源：http://dali.gotoacloud.top/Article/details/gtormjidqh.html

TS:   // worker_threads 线程池
来源：http://dali.hfpthk.cn/Article/details/gtoebemhtj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.smart0.xyz/Article/details/gtwvxhqvzy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.kuanghao11.cn/Article/details/gtpnpremxy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.9152youxi.cn/Article/details/gtlziyixvv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.guowangkeji.top/Article/details/gtxxzacfce.html

[O03] 加锁保护共享数据
来源：http://dali.ydzc1.top/Article/details/gtqygvmnxk.html

Py:   with lock: shared += 1
来源：http://dali.gaohongyu789.top/Article/details/gtayjfgeih.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hnxiangtu.top/Article/details/gtgwopvcmx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hysaishi.cn/Article/details/gtjtnrmvvo.html

TS:   // 同 JS
来源：http://dali.aizwys.cn/Article/details/gtxqzsking.html

Java: synchronized (this) { shared++; }
来源：http://dali.nanxinkj.top/Article/details/gtrxehvnvr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hammf.cn/Article/details/gtkvmnbxmd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shangyingyoupin.top/Article/details/gtnnoqwtqj.html

C#:   lock (gate) { shared++; }
来源：http://dali.hysaishi.cn/Article/details/gtvtdiqvqb.html

[O04] 定义异步函数并等待
来源：http://dali.dianchejie.cn/Article/details/gtsvidgcas.html

Py:   async def f():⏎    await g()
来源：http://dali.yangfankeji.com/Article/details/gttziycwek.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.9152youxi.cn/Article/details/gtnfwtrnzj.html

JS:   async function f() { await g(); }
来源：http://dali.snrcjt.cn/Article/details/gtumbtzkqw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtrgsjnepm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shuidangran.top/Article/details/gtqopabjpw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.dianchejie.cn/Article/details/gttvkdarhg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.dianchejie.cn/Article/details/gtyooeohel.html

C#:   async Task F() { await G(); }
来源：http://dali.haohaochexian.top/Article/details/gtazkomlpp.html

[O05] 并发执行并等待全部完成
来源：http://dali.xuanzx.com/Article/details/gtrohplysj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jqgufenzy.top/Article/details/gttvfzmieb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.9152youxi.cn/Article/details/gtguxfteio.html

JS:   await Promise.all(tasks)
来源：http://dali.ivvv.top/Article/details/gtxdeuaiqy.html

TS:   await Promise.all(tasks)
来源：http://dali.jianghu66.top/Article/details/gtwfbcmkcb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jyoumei.cn/Article/details/gtxddxypgi.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.pengpengdd.cyou/Article/details/gtoydpvbij.html

Ruby: threads.map(&:join)
来源：http://dali.yangfankeji.com/Article/details/gtznjmfbcp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttaohbszt.html

[O06] 使用进程池
来源：http://dali.iojbl.cn/Article/details/gtijmcyvde.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yvedp.cn/Article/details/gtojqjqjpf.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hammf.cn/Article/details/gtejcxdoew.html

JS:   // child_process / cluster 模块
来源：http://dali.xinyue.icu/Article/details/gtrofofruh.html

TS:   // child_process / cluster 模块
来源：http://dali.hammf.cn/Article/details/gttxjsuyvr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.smart0.xyz/Article/details/gtutmlxxgw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jqgfzy.top/Article/details/gtdlocpneq.html

Ruby: // fork 块
来源：http://dali.yonumen.top/Article/details/gtwdgefvfh.html

C#:   Parallel.For
来源：http://dali.cheryme.top/Article/details/gtumuzruqx.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtmjlzazeg.html

P. 常用工具函数
来源：http://dali.sxryk.cn/Article/details/gtvnqtjyuj.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtmcxqrvlb.html

[P01] 生成 UUID
来源：http://dali.yuanzhike.top/Article/details/gtispbjifc.html

Py:   str(uuid.uuid4())
来源：http://dali.9152youxi.cn/Article/details/gtukmbebwo.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ehwqpu.com/Article/details/gtikxekptv.html

JS:   crypto.randomUUID()
来源：http://dali.9152youxi.cn/Article/details/gtjcwmrvxc.html

TS:   crypto.randomUUID()
来源：http://dali.yuxming.cn/Article/details/gtkoussnnl.html

Java: UUID.randomUUID().toString()
来源：http://dali.9152youxi.cn/Article/details/gtvicsxkle.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sufxvd.cn/Article/details/gtbycnorxo.html

Ruby: SecureRandom.uuid
来源：http://dali.yj20258.top/Article/details/gtqbcptedn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hywenlv.cn/Article/details/gtqhztfjay.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hongshengwenyu.top/Article/details/gtkffztofs.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.daxiang520.top/Article/details/gtvxbqmdku.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gogol.net.cn/Article/details/gtgdzscojr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.9152youxi.cn/Article/details/gtunulsvyd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.meibo888.top/Article/details/gtossyboym.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlwtgzrfl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hywenlv.cn/Article/details/gtfuykjmpp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkpvwtzdb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.daria6918.cn/Article/details/gtxvjkdxwv.html

[P03] 生成短随机字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtavlowgqk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.nwbrower.top/Article/details/gtzyitwvkp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hongshengwenyu.top/Article/details/gtxchbcidl.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.haohaochexian.top/Article/details/gtberhmdhw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinqigufen.top/Article/details/gtxnwnmcus.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ydzc1.top/Article/details/gtafcqewav.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shzxlz.cn/Article/details/gtzynsvxih.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.tian-w.cn/Article/details/gthppnzccs.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.nanxuanxn.top/Article/details/gtkuyanuqs.html

[P04] 求长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtanjvuatx.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.aizwys.cn/Article/details/gtluvcosik.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenjidiqi.icu/Article/details/gtbwmvirzv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xuanzx.com/Article/details/gthbtqotrb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jlsjyb.cn/Article/details/gtztysljnv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yvedp.cn/Article/details/gtnyqbleen.html

Go:   len(arr);  len(m)
来源：http://dali.jinqigfzy.top/Article/details/gtilyvuppa.html

Ruby: x.length;  x.size
来源：http://dali.tanke756.top/Article/details/gtepjedkuy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.birdmap.top/Article/details/gtbauoaoax.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hfpthk.cn/Article/details/gtzcuwedgh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfwphebfe.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cucudq.cn/Article/details/gtrgvxhzrk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yueranfly.top/Article/details/gtiostlowj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shzxlz.cn/Article/details/gtujawpefs.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.kuanghao11.cn/Article/details/gtdjqjfxys.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yongpay.top/Article/details/gtzuqeluwr.html

Ruby: a == b
来源：http://dali.sysykeji.top/Article/details/gtinxqaaqy.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yvedp.cn/Article/details/gtwfisqnqd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xinyue.icu/Article/details/gtmjmviopr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jiagoushi.top/Article/details/gtifetpgfq.html

PHP:  if (empty($x)) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtxjmmseuj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xziqi.cn/Article/details/gtkzjtkeuj.html

TS:   if (x == null) {}
来源：http://dali.tianlin.xyz/Article/details/gtdgzkvebv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gotoacloud.top/Article/details/gtvmxzaupb.html

Go:   if x == nil {}
来源：http://dali.sxryk.cn/Article/details/gthcvtydct.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.iojbl.cn/Article/details/gtgyswiige.html

C#:   if (x is null) {}
来源：http://dali.dianchejie.cn/Article/details/gtizwushcc.html

[P07] 防抖与节流
来源：http://dali.sufxvd.cn/Article/details/gtzwxfqmyn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cdnleiting.top/Article/details/gtfpedgryl.html

PHP:  // 手写时间戳比较
来源：http://dali.jianghu66.top/Article/details/gtmrzgqzzl.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sxryk.cn/Article/details/gtedmtsvtw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.havefunace.top/Article/details/gtxwekuoxs.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yuanzhike.top/Article/details/gtmiaxvjub.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzsnsahtp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.gaohongyu789.top/Article/details/gtvzaiyvfi.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.chenjidiqi.icu/Article/details/gtqnoopihb.html

[P08] 处理浮点精度问题
来源：http://dali.haohaochexian.top/Article/details/gtfreveabj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yangfankeji.com/Article/details/gtrprqlwwd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.daxiang520.top/Article/details/gtantnlkpn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hfpthk.cn/Article/details/gthgsouftn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqqljnrte.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.fengsongda.top/Article/details/gtsoeujiwh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.aizwys.cn/Article/details/gtoarefmzr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gzhubu.top/Article/details/gtkgwgrzjf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yonumen.top/Article/details/gtrzjwlent.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtfjxuhwyb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.aibaodan.cn/Article/details/gtfjwnrwah.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtktjxckbr.html

[Q01] 创建表
来源：http://dali.hnqzz.top/Article/details/gtzrbuzwef.html


<!-- 参考信息 -->