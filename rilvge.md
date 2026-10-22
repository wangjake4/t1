代发 wailian999

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.bjfxy.top/Article/details/gtdngtkrsl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.c1oappe.top/Article/details/gtzwqpoiaz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ydzc1.top/Article/details/gtdoyvuxkb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.fengsongda.top/Article/details/gtzffelwyp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shanyushiyangtech.top/Article/details/gtkgacpoon.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.andypj.xyz/Article/details/gtdxlpxvqg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xuetiantiany.cn/Article/details/gtjvhxbpbe.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jqgfzy.top/Article/details/gtjfiyxaus.html

[M04] 获取当前工作目录
来源：http://dali.9152youxi.cn/Article/details/gtqdcmuvru.html

Py:   os.getcwd()
来源：http://dali.tanke756.top/Article/details/gtaqekajxn.html

PHP:  getcwd();
来源：http://dali.shuidangran.top/Article/details/gtxbtqfwsg.html

JS:   process.cwd()
来源：http://dali.cqqwz.cn/Article/details/gtagxypkme.html

TS:   process.cwd()
来源：http://dali.cucudq.cn/Article/details/gtemycemad.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jqgufenzy.top/Article/details/gtwpxtxujk.html

Go:   os.Getwd()
来源：http://dali.xuanzx.com/Article/details/gtkehpvlwn.html

Ruby: Dir.pwd
来源：http://dali.yonumen.top/Article/details/gtjutgouvo.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sufxvd.cn/Article/details/gtfodfvdty.html

[M05] 设置退出码
来源：http://dali.nanxuanxn.top/Article/details/gtaapugtmb.html

Py:   sys.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gtufbeqseb.html

PHP:  exit(1);
来源：http://dali.tanke756.top/Article/details/gtzphjezmp.html

JS:   process.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfciyilii.html

TS:   process.exit(1)
来源：http://dali.yvedp.cn/Article/details/gtnmoesuhs.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtmljibdpw.html

Go:   os.Exit(1)
来源：http://dali.hysaishi.cn/Article/details/gtzelwtoaj.html

Ruby: exit 1
来源：http://dali.gotoacloud.top/Article/details/gtcjlbygwb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xylfe.cn/Article/details/gthfggmjkc.html

[M06] 向标准错误输出
来源：http://dali.0kj1m.cn/Article/details/gthgvtxdoa.html

Py:   print("err", file=sys.stderr)
来源：http://dali.tian-w.cn/Article/details/gtxwziqjqg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhixingplan.top/Article/details/gtmzjkmgwr.html

JS:   console.error("err")
来源：http://dali.zycfv.cn/Article/details/gtdhlpqjxh.html

TS:   console.error("err")
来源：http://dali.jqgfzy.top/Article/details/gtpbodyrvg.html

Java: System.err.println("err")
来源：http://dali.yj20258888.top/Article/details/gtgvlnlvij.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gotoacloud.top/Article/details/gtpnuiprbf.html

Ruby: warn "err"
来源：http://dali.chenjidiqi.icu/Article/details/gtxvmxvowl.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hongshengwenyu.top/Article/details/gtqlsyqfck.html

[M07] 判断是否为主入口
来源：http://dali.jiagoushi.top/Article/details/gtrogpcoqn.html

Py:   if __name__ == "__main__":
来源：http://dali.tianlin.xyz/Article/details/gtahpfmzki.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yvedp.cn/Article/details/gtdzbilust.html

JS:   require.main === module
来源：http://dali.jinghuilouyu.cn/Article/details/gtjjatfwyg.html

TS:   require.main === module
来源：http://dali.zhiwuduotai.top/Article/details/gtwntdlxic.html

Java: public static void main(String[] args)
来源：http://dali.gogol.net.cn/Article/details/gtcijmblpb.html

Go:   func main()
来源：http://dali.316326.xyz/Article/details/gthnujrgea.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.snrcjt.cn/Article/details/gtyztwrmqh.html

C#:   static void Main(string[] args)
来源：http://dali.xuetiantiany.cn/Article/details/gtsjnvwlqk.html

[M08] 获取系统与运行时信息
来源：http://dali.yuxming.cn/Article/details/gtggehorhi.html

Py:   platform.system();  platform.python_version()
来源：http://dali.wangdashe.top/Article/details/gtvxusqdob.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jlsjyb.cn/Article/details/gtthamqieq.html

JS:   process.platform;  process.version
来源：http://dali.jianghu66.top/Article/details/gtyvvlzwnz.html

TS:   process.platform;  process.version
来源：http://dali.ivvv.top/Article/details/gtjqwglyjp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yueranfly.top/Article/details/gtfyhjarrk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xziqi.cn/Article/details/gtzpfqoqhy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shzxlz.cn/Article/details/gtetqhaoos.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.pycfn.com/Article/details/gtfyyxsnnc.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtazjrvpzs.html

N. 数据结构与算法
来源：http://dali.chenjidiqi.icu/Article/details/gtgsrcskiw.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtnuslcfuo.html

[N01] 二分查找（有序数组）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkpzloopm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.havefunace.top/Article/details/gtzxkvnkyo.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ivvv.top/Article/details/gtcgxdjicl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sysykeji.top/Article/details/gttlaqxkrk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yueranfly.top/Article/details/gtobtsysnn.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.redwolf501.top/Article/details/gthegpbtji.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtzrzlgkac.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.wangdashe.top/Article/details/gtmyxziook.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmrkqqxop.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.andypj.xyz/Article/details/gtydiwaspg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ydzc1.top/Article/details/gtktktlskc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.birdmap.top/Article/details/gtrqwydjot.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.andypj.xyz/Article/details/gtzbowefzc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dianchejie.cn/Article/details/gtkbhzbuja.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.c1oappe.top/Article/details/gttiouodql.html

Go:   slices.Sort(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtvpokuwzb.html

Ruby: arr.sort
来源：http://dali.ehwqpu.com/Article/details/gtcnuqkxpq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.andypj.xyz/Article/details/gtiwitmgjw.html

[N03] 快速排序（分治示例）
来源：http://dali.xziqi.cn/Article/details/gtvlypmnkt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xziqi.cn/Article/details/gtksqnwvse.html

PHP:  // 递归实现，或用 usort
来源：http://dali.chenlongwang.top/Article/details/gtxvnukgnc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.meibo888.top/Article/details/gticotpxif.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yanxiufei.cn/Article/details/gtxadpdbmb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.pycfn.com/Article/details/gtzabzdkmo.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.haohaochexian.top/Article/details/gtefbdesca.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cqqwz.cn/Article/details/gtokxaeeif.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.fzhhl.top/Article/details/gtgkktvhvq.html

[N04] 斐波那契数列
来源：http://dali.yj20258888.top/Article/details/gthlgpefri.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nanxuanxn.top/Article/details/gtiygppbvs.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.vqdsnc.cn/Article/details/gtnupsixtm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daria6918.cn/Article/details/gtybbjkjjv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cucudq.cn/Article/details/gtylshausq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yonumen.top/Article/details/gtmgkgqixx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ydzc1.top/Article/details/gtznmuselg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuvzmbsfo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtjgbiopnm.html

[N05] 最大公约数
来源：http://dali.jinghuilouyu.cn/Article/details/gtmapbdndc.html

Py:   math.gcd(a, b)
来源：http://dali.hfpthk.cn/Article/details/gtdnteldor.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jqgfzy.top/Article/details/gtknkfuyac.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj202588.top/Article/details/gtjfcmauug.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xziqi.cn/Article/details/gtmsksfbvx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.snrcjt.cn/Article/details/gtfldbenyc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.fengsongda.top/Article/details/gtzagmhfos.html

Ruby: a.gcd(b)
来源：http://dali.gaohongyu789.top/Article/details/gtuffuphmi.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yuanzhike.top/Article/details/gtbpozujvy.html

[N06] 判断回文字符串
来源：http://dali.jiagoushi.top/Article/details/gtydctosdc.html

Py:   s == s[::-1]
来源：http://dali.zhiwuduotai.top/Article/details/gtsmlrkqqu.html

PHP:  $s === strrev($s);
来源：http://dali.jinqigfzy.top/Article/details/gtjpxcxxfb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gtkynauoha.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtslaaftwr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.wangshuangyany.cn/Article/details/gtozrrvfpo.html

Go:   // 双指针从两端比较
来源：http://dali.hfpthk.cn/Article/details/gtygltyejj.html

Ruby: s == s.reverse
来源：http://dali.svipenyu.cn/Article/details/gtlqnreksg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.birdmap.top/Article/details/gteqgpvvuk.html

[N07] 两数之和（返回下标）
来源：http://dali.xziqi.cn/Article/details/gtxmmingmy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hfpthk.cn/Article/details/gtdyglmdfe.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.mhx1999.top/Article/details/gthcfwicrb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.chenlongwang.top/Article/details/gteqyxfydf.html

TS:   // 手写 Map<string, number>
来源：http://dali.aizwys.cn/Article/details/gtrdfbpfic.html

Java: // 手写 HashMap
来源：http://dali.jinqigufen.top/Article/details/gtmpnnspsu.html

Go:   // 手写 map[int]int
来源：http://dali.nanxinkj.top/Article/details/gtqyqzegnf.html

Ruby: // 手写 Hash
来源：http://dali.cdnleiting.top/Article/details/gthtgmayjx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jiagoushi.top/Article/details/gtyxalzlsy.html

[N08] 生成全排列
来源：http://dali.sysykeji.top/Article/details/gtdvtjoyun.html

Py:   itertools.permutations(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtzquuztkf.html

PHP:  // 手写递归交换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpvmwzigl.html

JS:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gtmpdjhwvi.html

TS:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gtweqmhjqe.html

Java: // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gttknuwjok.html

Go:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtlgrhqvpu.html

Ruby: arr.permutation.to_a
来源：http://dali.jianghu66.top/Article/details/gtmiovufyv.html

C#:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gteamxkvon.html

[N09] 栈与队列
来源：http://dali.xziqi.cn/Article/details/gtnlyfxthn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcmvnbmyf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cashguo.top/Article/details/gtpgsjxyys.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shzxlz.cn/Article/details/gtgfmxyrcb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxxtixdvt.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.aibaodan.cn/Article/details/gtfuhnvhkg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.nwbrower.top/Article/details/gtzfjqpfqq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinqigfzy.top/Article/details/gtzmdzqkdb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinqigfzy.top/Article/details/gteytmrrwh.html

[N10] 链表节点定义
来源：http://dali.cqqwz.cn/Article/details/gtnxgzxcdh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cucudq.cn/Article/details/gtabxminha.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhongyouzk.top/Article/details/gtawrjylaa.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sufxvd.cn/Article/details/gtctufnqym.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.fzhhl.top/Article/details/gtrquezpbv.html

Java: class Node { int v; Node next; }
来源：http://dali.yj20258888.top/Article/details/gtagwvktmq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.nwbrower.top/Article/details/gtffzwknay.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tian-w.cn/Article/details/gthkghrngf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jqgufenzy.top/Article/details/gtwrwaspoq.html

[N11] 二叉树中序遍历
来源：http://dali.mhx1999.top/Article/details/gtemwxtzzi.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.guowangkeji.top/Article/details/gtlwrjhgog.html

PHP:  // 手写递归函数
来源：http://dali.aizwys.cn/Article/details/gtikprgiqb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zycfv.cn/Article/details/gtaetxdhfa.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.iojbl.cn/Article/details/gtijagopxp.html

Java: // 手写递归
来源：http://dali.hammf.cn/Article/details/gtpnpqrqje.html

Go:   // 手写递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtixwwqvcg.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqmslimzg.html

C#:   // 手写递归
来源：http://dali.yj20258.top/Article/details/gtpoowaeli.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.chenzaomai.com/Article/details/gtzprbhpmx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yongpay.top/Article/details/gtouvntxdt.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.havefunace.top/Article/details/gtflixltre.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ehwqpu.com/Article/details/gtmpdnqdhi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.pengpengdd.cyou/Article/details/gtvvbztldu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.c1oappe.top/Article/details/gtykqqecge.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.gaohongyu789.top/Article/details/gtebpokbaz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.smart0.xyz/Article/details/gtifedgjbv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhixingplan.top/Article/details/gtufrgsmqh.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtmjakmtwv.html

O. 并发与异步
来源：http://dali.shangyingyoupin.top/Article/details/gtaevguogs.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtwqdmqura.html

[O01] 启动一个线程
来源：http://dali.iojbl.cn/Article/details/gtonougqfz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ehwqpu.com/Article/details/gtrmzphyoz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jqgufenzy.top/Article/details/gtkerjlemi.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cucudq.cn/Article/details/gtvhpwwrsb.html

TS:   // 同 JS
来源：http://dali.nanxinkj.top/Article/details/gtqppfwzxl.html

Java: new Thread(() -> f()).start()
来源：http://dali.dashuyun.cn/Article/details/gtrgvmkrqm.html

Go:   go f()
来源：http://dali.sxryk.cn/Article/details/gtyxxbeqck.html

Ruby: Thread.new { f }
来源：http://dali.yueranfly.top/Article/details/gtwrxuuyxv.html

C#:   Task.Run(() => F());
来源：http://dali.ppjwa.cn/Article/details/gteqmelnla.html

[O02] 使用线程池
来源：http://dali.cashguo.top/Article/details/gtvhsbpeje.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhongyouzk.top/Article/details/gtmshrrcbc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hammf.cn/Article/details/gtdylazhuz.html

JS:   // worker_threads 线程池
来源：http://dali.feifeiyinyue.top/Article/details/gtihtbzlds.html

TS:   // worker_threads 线程池
来源：http://dali.dashuyun.cn/Article/details/gtddwihfwx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xziqi.cn/Article/details/gtxrildpjy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cashguo.top/Article/details/gtylbvqjmc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.nwbrower.top/Article/details/gtsyrnemcj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ehwqpu.com/Article/details/gtivjmxbhe.html

[O03] 加锁保护共享数据
来源：http://dali.sufxvd.cn/Article/details/gtfvrdmtsa.html

Py:   with lock: shared += 1
来源：http://dali.vqdsnc.cn/Article/details/gtocnfxznr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xuanzx.com/Article/details/gtniqidsih.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.bjfxy.top/Article/details/gtzoaywezf.html

TS:   // 同 JS
来源：http://dali.guannengcc.top/Article/details/gtzspxvvlk.html

Java: synchronized (this) { shared++; }
来源：http://dali.iojbl.cn/Article/details/gtmazgcnoo.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.smart0.xyz/Article/details/gtgzzxoaid.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhiwuduotai.top/Article/details/gtruhvwpqq.html

C#:   lock (gate) { shared++; }
来源：http://dali.svipenyu.cn/Article/details/gthkcwrkfc.html

[O04] 定义异步函数并等待
来源：http://dali.daria6918.cn/Article/details/gtsfljtbzu.html

Py:   async def f():⏎    await g()
来源：http://dali.yj202588.top/Article/details/gtmiwehbys.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gogol.net.cn/Article/details/gtanzcnxur.html

JS:   async function f() { await g(); }
来源：http://dali.nanxuanxn.top/Article/details/gtfilojvtf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.pycfn.com/Article/details/gtzkpnkyne.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yuxming.cn/Article/details/gtvvalwall.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ybcxt.top/Article/details/gtcwryynrn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.andypj.xyz/Article/details/gtakfywluy.html

C#:   async Task F() { await G(); }
来源：http://dali.pycfn.com/Article/details/gtgjhrpqhb.html

[O05] 并发执行并等待全部完成
来源：http://dali.zdqjudy.top/Article/details/gtkzlefqkt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhiwuduotai.top/Article/details/gttokjcgth.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhixingplan.top/Article/details/gtvrlmasef.html

JS:   await Promise.all(tasks)
来源：http://dali.hammf.cn/Article/details/gtuyxatjux.html

TS:   await Promise.all(tasks)
来源：http://dali.sysykeji.top/Article/details/gtbqadeqfi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yanxiufei.cn/Article/details/gtvdqaygmu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shzxlz.cn/Article/details/gtrfmokipu.html

Ruby: threads.map(&:join)
来源：http://dali.dashuyun.cn/Article/details/gtvgwtulmg.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjwujmuao.html

[O06] 使用进程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gtseallvny.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.chenlongwang.top/Article/details/gtaqiwdrsb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yanxiufei.cn/Article/details/gthfsftetg.html

JS:   // child_process / cluster 模块
来源：http://dali.haohaochexian.top/Article/details/gtousuzyyb.html

TS:   // child_process / cluster 模块
来源：http://dali.zhengqikj.top/Article/details/gthnhlslqm.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.guannengcc.top/Article/details/gtgzqtdemv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zycfv.cn/Article/details/gteoieanfn.html

Ruby: // fork 块
来源：http://dali.shuidangran.top/Article/details/gtbwoitfik.html

C#:   Parallel.For
来源：http://dali.meibo888.top/Article/details/gtdbblwrgp.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqlzovjqi.html

P. 常用工具函数
来源：http://dali.sxryk.cn/Article/details/gtrvxjfssy.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtgekjxeee.html

[P01] 生成 UUID
来源：http://dali.shzxlz.cn/Article/details/gtbamvonsi.html

Py:   str(uuid.uuid4())
来源：http://dali.ppjwa.cn/Article/details/gtxwycswyf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yanxiufei.cn/Article/details/gtzyndstjj.html

JS:   crypto.randomUUID()
来源：http://dali.feifeiyinyue.top/Article/details/gtmqiwirew.html

TS:   crypto.randomUUID()
来源：http://dali.hnxiangtu.top/Article/details/gtmrezccgm.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinqigfzy.top/Article/details/gtoazfksdi.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xuanzx.com/Article/details/gtbsesqfbn.html

Ruby: SecureRandom.uuid
来源：http://dali.hfpthk.cn/Article/details/gtlddfegri.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.gotoacloud.top/Article/details/gtovdnmxlw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hnqzz.top/Article/details/gtamnpfqvx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hammf.cn/Article/details/gtptuwtsyh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yangfankeji.com/Article/details/gtyrjjhzds.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jlsjyb.cn/Article/details/gtanoetfgu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtttiywkbj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.gzhubu.top/Article/details/gtnxzepzbq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhongyouzk.top/Article/details/gtuhwzjmwq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.kuanghao11.cn/Article/details/gttzmibisn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yj202588.top/Article/details/gtzyzkgkdl.html

[P03] 生成短随机字符串
来源：http://dali.svipenyu.cn/Article/details/gtcspkwlfq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.bjfxy.top/Article/details/gtsfczseje.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.gaohongyu789.top/Article/details/gtuwhtqtdh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258.top/Article/details/gtiomgfpjj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aibaodan.cn/Article/details/gtwpgslmro.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hnxiangtu.top/Article/details/gtsisrqioa.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hongshengwenyu.top/Article/details/gtgcdgvtoz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yuxming.cn/Article/details/gtoqzatwku.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.chenlongwang.top/Article/details/gtzkcyovre.html

[P04] 求长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxqeqnyao.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsnlozapf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gtnmqgezxd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yongpay.top/Article/details/gtxgbjcjqb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guannengcc.top/Article/details/gtyueyswiy.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hnqzz.top/Article/details/gtuoalckxq.html

Go:   len(arr);  len(m)
来源：http://dali.yanxiufei.cn/Article/details/gtpcbuonaa.html

Ruby: x.length;  x.size
来源：http://dali.tian-w.cn/Article/details/gtqoxlmswi.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinqigufen.top/Article/details/gtcyrzndac.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hywenlv.cn/Article/details/gtxlqqcsqr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.dianchejie.cn/Article/details/gtwqxswhid.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.birdmap.top/Article/details/gtninzblat.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.feifeiyinyue.top/Article/details/gtcqvyirbe.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cucudq.cn/Article/details/gtrxuoygoz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jqgufenzy.top/Article/details/gtaezaabzp.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuumqhcsl.html

Ruby: a == b
来源：http://dali.chenzaomai.com/Article/details/gtvruspqjr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jiagoushi.top/Article/details/gtugjtvgwq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinqigufen.top/Article/details/gtckkwobtd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteygqujrc.html

PHP:  if (empty($x)) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtakabudds.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.nwbrower.top/Article/details/gtladqrgnu.html

TS:   if (x == null) {}
来源：http://dali.sysykeji.top/Article/details/gtdiwdjieq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.bjfxy.top/Article/details/gtwbhksvjx.html

Go:   if x == nil {}
来源：http://dali.cheryme.top/Article/details/gtsidqirbl.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yuanzhike.top/Article/details/gtgychmbxh.html

C#:   if (x is null) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtdwiwyfsp.html

[P07] 防抖与节流
来源：http://dali.meibo888.top/Article/details/gtwykoyljf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cucudq.cn/Article/details/gtxcwphhpl.html

PHP:  // 手写时间戳比较
来源：http://dali.pengpengdd.cyou/Article/details/gtrjbyzbvd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.c1oappe.top/Article/details/gtmadsznju.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvjqktjsy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.andypj.xyz/Article/details/gtjlzhhvdz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hongshengwenyu.top/Article/details/gtmekzovlg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhiwuduotai.top/Article/details/gtdijdrzks.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yuanzhike.top/Article/details/gtamfqripl.html

[P08] 处理浮点精度问题
来源：http://dali.ybcxt.top/Article/details/gtlpvltnyo.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cdnleiting.top/Article/details/gtmdykjxzf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.fengsongda.top/Article/details/gtqlfmayab.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ehwqpu.com/Article/details/gtghkayigf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gtqnfmkgky.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhoulong.xyz/Article/details/gtwbjdigfh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yonumen.top/Article/details/gtgqimqfdk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.tianlin.xyz/Article/details/gtcwlemrnu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhixingplan.top/Article/details/gtupaeblli.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtzxnsrltz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sweek.top/Article/details/gthtgxaxns.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtmxpllzmu.html

[Q01] 创建表
来源：http://dali.havefunace.top/Article/details/gtjiwseweg.html


<!-- 参考信息 -->