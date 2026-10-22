代发 wailian999

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yanxiufei.cn/Article/details/gtnwuilnak.html

JS:   process.env.HOME
来源：http://dali.zhaomingkeji.xyz/Article/details/gttortcrcu.html

TS:   process.env.HOME
来源：http://dali.hongshengwenyu.top/Article/details/gtjflefdty.html

Java: System.getenv("HOME")
来源：http://dali.yuxming.cn/Article/details/gtquqjfvhb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.iojbl.cn/Article/details/gtdxweiuso.html

Ruby: ENV["HOME"]
来源：http://dali.yvedp.cn/Article/details/gtwpdmjrac.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yueranfly.top/Article/details/gtfhiikonu.html

[M03] 执行外部命令
来源：http://dali.yj20258.top/Article/details/gtvhlfmlby.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinqigufen.top/Article/details/gtgulzodgi.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyzthjoaq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwlugqfjb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xylfe.cn/Article/details/gtlrnomfxy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.daria6918.cn/Article/details/gtpliigzos.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.aibaodan.cn/Article/details/gtocbdhsua.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhengqikj.top/Article/details/gttgyjrwxd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nanxuanxn.top/Article/details/gtckvlxjvh.html

[M04] 获取当前工作目录
来源：http://dali.feifeiyinyue.top/Article/details/gtgfesaztw.html

Py:   os.getcwd()
来源：http://dali.jyoumei.cn/Article/details/gtcsxxkize.html

PHP:  getcwd();
来源：http://dali.cucudq.cn/Article/details/gtphlolovr.html

JS:   process.cwd()
来源：http://dali.9152youxi.cn/Article/details/gtanpcrtuk.html

TS:   process.cwd()
来源：http://dali.jinqigfzy.top/Article/details/gtcsnthahz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cucudq.cn/Article/details/gtxsmzasvl.html

Go:   os.Getwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbzoxyswo.html

Ruby: Dir.pwd
来源：http://dali.yuxming.cn/Article/details/gtpoqcnoyt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sysykeji.top/Article/details/gtaorjhjib.html

[M05] 设置退出码
来源：http://dali.haohaochexian.top/Article/details/gtizasxllf.html

Py:   sys.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtypajqlfr.html

PHP:  exit(1);
来源：http://dali.316326.xyz/Article/details/gtgreatehj.html

JS:   process.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gthuzrnsev.html

TS:   process.exit(1)
来源：http://dali.cashguo.top/Article/details/gtchmuorml.html

Java: System.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtlwkikrdr.html

Go:   os.Exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtwolykvpi.html

Ruby: exit 1
来源：http://dali.sysykeji.top/Article/details/gthenqkunq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenjidiqi.icu/Article/details/gtsromckqy.html

[M06] 向标准错误输出
来源：http://dali.xziqi.cn/Article/details/gtuxtyzezs.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yonumen.top/Article/details/gtuldllvfs.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.chenlongwang.top/Article/details/gtmqrdkepv.html

JS:   console.error("err")
来源：http://dali.yuxming.cn/Article/details/gtrmwnjlfc.html

TS:   console.error("err")
来源：http://dali.snrcjt.cn/Article/details/gtmtvkjuyj.html

Java: System.err.println("err")
来源：http://dali.cqqwz.cn/Article/details/gtrbhpogmp.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yuanzhike.top/Article/details/gtvwlzmmyp.html

Ruby: warn "err"
来源：http://dali.jiagoushi.top/Article/details/gtnwrvlusq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.chenlongwang.top/Article/details/gtvpqjfoee.html

[M07] 判断是否为主入口
来源：http://dali.wangdashe.top/Article/details/gtgsfamsrj.html

Py:   if __name__ == "__main__":
来源：http://dali.birdmap.top/Article/details/gtubzgmwim.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zdqjudy.top/Article/details/gtzwfcchkg.html

JS:   require.main === module
来源：http://dali.yueranfly.top/Article/details/gteohnzqcs.html

TS:   require.main === module
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxlcbiqeo.html

Java: public static void main(String[] args)
来源：http://dali.jqgfzy.top/Article/details/gtrwmjiwtw.html

Go:   func main()
来源：http://dali.kuanghao11.cn/Article/details/gtzfjxzjge.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yj202588.top/Article/details/gtpeffibyw.html

C#:   static void Main(string[] args)
来源：http://dali.ehwqpu.com/Article/details/gtoviooxwg.html

[M08] 获取系统与运行时信息
来源：http://dali.tianlin.xyz/Article/details/gtfbsznfhg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.nanxinkj.top/Article/details/gtynqytpqz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hongshengwenyu.top/Article/details/gtqromktes.html

JS:   process.platform;  process.version
来源：http://dali.daria6918.cn/Article/details/gtblvnkwzp.html

TS:   process.platform;  process.version
来源：http://dali.smart0.xyz/Article/details/gtfrdcbbqb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.tian-w.cn/Article/details/gtnvtjpgms.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sxryk.cn/Article/details/gtojyxpara.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.tian-w.cn/Article/details/gtnzysjtid.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoayqsyrb.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtgsdxztps.html

N. 数据结构与算法
来源：http://dali.gogol.net.cn/Article/details/gtujrhleqj.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtollvwvca.html

[N01] 二分查找（有序数组）
来源：http://dali.yvedp.cn/Article/details/gtezplmrlo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtvkfeoxmj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.tianlin.xyz/Article/details/gtimfzpzse.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gtonowooxq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ppjwa.cn/Article/details/gtgzujmcjy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtawtcujwv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtipkfidiw.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jianghu66.top/Article/details/gtzsrjwbgn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gteohnzhur.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hysaishi.cn/Article/details/gtkqshqzjl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tianlin.xyz/Article/details/gttaddexpe.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xziqi.cn/Article/details/gtnhbfpkfc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jqgfzy.top/Article/details/gteqvakeiy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fzhhl.top/Article/details/gtivevvrtg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinqigufen.top/Article/details/gtqoddwqhg.html

Go:   slices.Sort(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtownfhvaz.html

Ruby: arr.sort
来源：http://dali.aizwys.cn/Article/details/gtltwsoqpl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ppjwa.cn/Article/details/gtjewfccmz.html

[N03] 快速排序（分治示例）
来源：http://dali.cucudq.cn/Article/details/gtgcrmguqn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.9152youxi.cn/Article/details/gtnzectuql.html

PHP:  // 递归实现，或用 usort
来源：http://dali.nanxuanxn.top/Article/details/gtxhxlpkxj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pengpengdd.cyou/Article/details/gtzqhzqwue.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hongshengwenyu.top/Article/details/gtwhhygckn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yuxming.cn/Article/details/gtzcrojcma.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.aibaodan.cn/Article/details/gtixozcqnb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xuanzx.com/Article/details/gtkjosdtqn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gotoacloud.top/Article/details/gtwlihfpsq.html

[N04] 斐波那契数列
来源：http://dali.shangyingyoupin.top/Article/details/gtebvnqyqo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hywenlv.cn/Article/details/gtnpdbgpea.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.haohaochexian.top/Article/details/gtonxyzpwj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gaohongyu789.top/Article/details/gtduemylch.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhongyouzk.top/Article/details/gtlfbrigwp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ybcxt.top/Article/details/gtcimsdldr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zycfv.cn/Article/details/gtvzevcnug.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj202588.top/Article/details/gtqmdstgum.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yangfankeji.com/Article/details/gtkuwfwzgs.html

[N05] 最大公约数
来源：http://dali.gaohongyu789.top/Article/details/gthobyyaki.html

Py:   math.gcd(a, b)
来源：http://dali.tianlin.xyz/Article/details/gtwppfgwgz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhixingplan.top/Article/details/gtbwpzzann.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hammf.cn/Article/details/gtggwyicyx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daria6918.cn/Article/details/gtertfoeio.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cdnleiting.top/Article/details/gtlsrskxbs.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cashguo.top/Article/details/gtsffikzjt.html

Ruby: a.gcd(b)
来源：http://dali.haohaochexian.top/Article/details/gtyvkbgwdb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.aibaodan.cn/Article/details/gtwsjjfzjk.html

[N06] 判断回文字符串
来源：http://dali.hnxiangtu.top/Article/details/gtysdtvfgk.html

Py:   s == s[::-1]
来源：http://dali.shuidangran.top/Article/details/gtufszxmmn.html

PHP:  $s === strrev($s);
来源：http://dali.iojbl.cn/Article/details/gtzewahprt.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gtzybplwgj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gthgzugjew.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.smart0.xyz/Article/details/gtlkiafoaa.html

Go:   // 双指针从两端比较
来源：http://dali.gotoacloud.top/Article/details/gtmsixkwna.html

Ruby: s == s.reverse
来源：http://dali.chenzaomai.com/Article/details/gtznabvcqo.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xziqi.cn/Article/details/gtichwfobv.html

[N07] 两数之和（返回下标）
来源：http://dali.cheryme.top/Article/details/gtlhwzjolr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.chenjidiqi.icu/Article/details/gtdplrhtpl.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj20258888.top/Article/details/gtqxtlnuca.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.tanke756.top/Article/details/gtvsjjnvmu.html

TS:   // 手写 Map<string, number>
来源：http://dali.smart0.xyz/Article/details/gthtopfiyy.html

Java: // 手写 HashMap
来源：http://dali.tanke756.top/Article/details/gtyqeauhji.html

Go:   // 手写 map[int]int
来源：http://dali.yuxming.cn/Article/details/gtkirndtlo.html

Ruby: // 手写 Hash
来源：http://dali.daria6918.cn/Article/details/gtcnvkucec.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yueranfly.top/Article/details/gtnxtngetc.html

[N08] 生成全排列
来源：http://dali.jqgufenzy.top/Article/details/gtuftpptux.html

Py:   itertools.permutations(arr)
来源：http://dali.hammf.cn/Article/details/gtpmalonkg.html

PHP:  // 手写递归交换
来源：http://dali.nanxuanxn.top/Article/details/gtxesfykwc.html

JS:   // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gtwigigztm.html

TS:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gthkydjmru.html

Java: // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gtathyfbmw.html

Go:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gtemxebdbg.html

Ruby: arr.permutation.to_a
来源：http://dali.shuidangran.top/Article/details/gthrrwrnvt.html

C#:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gtfeoaffph.html

[N09] 栈与队列
来源：http://dali.gzhubu.top/Article/details/gtepvgytxt.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yueranfly.top/Article/details/gtpnfrvrwq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gaohongyu789.top/Article/details/gtqzrrvssf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jqgufenzy.top/Article/details/gtklazlbvu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwefxuhrl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.gaohongyu789.top/Article/details/gtkarxkler.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.havefunace.top/Article/details/gtyhkfeqbo.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.daria6918.cn/Article/details/gtukkyzjqo.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.tanke756.top/Article/details/gtvlcqhsby.html

[N10] 链表节点定义
来源：http://dali.cdnleiting.top/Article/details/gtjdhvmjqb.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.fengsongda.top/Article/details/gtcjxldvfa.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yueranfly.top/Article/details/gtvllyltnl.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhiwuduotai.top/Article/details/gtpvijnqgc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ehwqpu.com/Article/details/gtvgvrcbou.html

Java: class Node { int v; Node next; }
来源：http://dali.xuetiantiany.cn/Article/details/gtlmmnwoid.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shzxlz.cn/Article/details/gtyzjdzzss.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.smart0.xyz/Article/details/gtkljqbiwh.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ehwqpu.com/Article/details/gtfucpvxly.html

[N11] 二叉树中序遍历
来源：http://dali.dianchejie.cn/Article/details/gtljzpqhvu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinqigfzy.top/Article/details/gtlalymqnr.html

PHP:  // 手写递归函数
来源：http://dali.aizwys.cn/Article/details/gtckuiezst.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daria6918.cn/Article/details/gttmnirdvk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.feifeiyinyue.top/Article/details/gtztfpyfas.html

Java: // 手写递归
来源：http://dali.fzhhl.top/Article/details/gtxvqbxgnq.html

Go:   // 手写递归
来源：http://dali.jianghu66.top/Article/details/gtnvsumyjj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jqgufenzy.top/Article/details/gtqestguct.html

C#:   // 手写递归
来源：http://dali.jinqigufen.top/Article/details/gtvdlheniu.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cqqwz.cn/Article/details/gttsnfwrih.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cucudq.cn/Article/details/gtkpmuurwl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.andypj.xyz/Article/details/gtlkprripd.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinghuilouyu.cn/Article/details/gtvtviydvi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sysykeji.top/Article/details/gtsipbclft.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgfzy.top/Article/details/gtfiuvqamz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sysykeji.top/Article/details/gtlqisyerp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hysaishi.cn/Article/details/gtqvyalpjx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.meibo888.top/Article/details/gtlwdyvymq.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtbxylless.html

O. 并发与异步
来源：http://dali.jiagoushi.top/Article/details/gtedunjpsi.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpburrlpg.html

[O01] 启动一个线程
来源：http://dali.jlsjyb.cn/Article/details/gtqlhhduwr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jinqigfzy.top/Article/details/gtxmzcozhs.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.dianchejie.cn/Article/details/gtwauuxpwe.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shzxlz.cn/Article/details/gtzkqguxzf.html

TS:   // 同 JS
来源：http://dali.cqqwz.cn/Article/details/gtzcugcpec.html

Java: new Thread(() -> f()).start()
来源：http://dali.yonumen.top/Article/details/gtqnlqpewe.html

Go:   go f()
来源：http://dali.yj202588.top/Article/details/gtwwatgqtb.html

Ruby: Thread.new { f }
来源：http://dali.hongshengwenyu.top/Article/details/gtpglgaato.html

C#:   Task.Run(() => F());
来源：http://dali.jinghuilouyu.cn/Article/details/gtqodpnpqx.html

[O02] 使用线程池
来源：http://dali.nanxinkj.top/Article/details/gtbqjpjpox.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.daxiang520.top/Article/details/gtrynbvrvk.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ivvv.top/Article/details/gtdznmgjyz.html

JS:   // worker_threads 线程池
来源：http://dali.jyoumei.cn/Article/details/gtqvyrlzbw.html

TS:   // worker_threads 线程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvhnwwuev.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jqgufenzy.top/Article/details/gtfabdmgxv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gotoacloud.top/Article/details/gtugswdgys.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xylfe.cn/Article/details/gtqqpbkdfe.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yvedp.cn/Article/details/gtrkykylpw.html

[O03] 加锁保护共享数据
来源：http://dali.pycfn.com/Article/details/gtoshcduxt.html

Py:   with lock: shared += 1
来源：http://dali.pycfn.com/Article/details/gttalykzgs.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.chenzaomai.com/Article/details/gtgqxfmfgb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.daria6918.cn/Article/details/gtwlhwisfx.html

TS:   // 同 JS
来源：http://dali.tian-w.cn/Article/details/gtncuspjup.html

Java: synchronized (this) { shared++; }
来源：http://dali.haohaochexian.top/Article/details/gtizjozqxu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.wangdashe.top/Article/details/gtpfwuzfhi.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ybcxt.top/Article/details/gtsucjmpap.html

C#:   lock (gate) { shared++; }
来源：http://dali.sysykeji.top/Article/details/gtmogcjffz.html

[O04] 定义异步函数并等待
来源：http://dali.jqgufenzy.top/Article/details/gtqqbmdodu.html

Py:   async def f():⏎    await g()
来源：http://dali.mhx1999.top/Article/details/gtvetvtrtd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.0kj1m.cn/Article/details/gtjymixnfb.html

JS:   async function f() { await g(); }
来源：http://dali.cdnleiting.top/Article/details/gthoxepsur.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.meibo888.top/Article/details/gtaohnxiny.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttubljoqx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhongyouzk.top/Article/details/gtsxdekgea.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yanxiufei.cn/Article/details/gtohjakoss.html

C#:   async Task F() { await G(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtcwpesmra.html

[O05] 并发执行并等待全部完成
来源：http://dali.jiagoushi.top/Article/details/gteyocvmtz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.sufxvd.cn/Article/details/gtkmrzetef.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.pycfn.com/Article/details/gtucseserd.html

JS:   await Promise.all(tasks)
来源：http://dali.zhoulong.xyz/Article/details/gtdrvoktsp.html

TS:   await Promise.all(tasks)
来源：http://dali.ppjwa.cn/Article/details/gtbvqqsqef.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hfpthk.cn/Article/details/gtrmsgzvsb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.guannengcc.top/Article/details/gtjojixnhu.html

Ruby: threads.map(&:join)
来源：http://dali.aizwys.cn/Article/details/gtwldmzniu.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yangfankeji.com/Article/details/gttmanllbq.html

[O06] 使用进程池
来源：http://dali.jlsjyb.cn/Article/details/gtlzdxctdc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.birdmap.top/Article/details/gtnjafqsoa.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shuidangran.top/Article/details/gtguirfzjq.html

JS:   // child_process / cluster 模块
来源：http://dali.hammf.cn/Article/details/gtcigwmlgm.html

TS:   // child_process / cluster 模块
来源：http://dali.sysykeji.top/Article/details/gtbgtghugq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhongyouzk.top/Article/details/gtmuyvnsuu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gaohongyu789.top/Article/details/gtnksgbwhh.html

Ruby: // fork 块
来源：http://dali.chenjidiqi.icu/Article/details/gtwcqgovph.html

C#:   Parallel.For
来源：http://dali.hfpthk.cn/Article/details/gtjmzoxcxe.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtcdgpvkwz.html

P. 常用工具函数
来源：http://dali.0kj1m.cn/Article/details/gtzsqjbhjt.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtybpxubjx.html

[P01] 生成 UUID
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthfddcsks.html

Py:   str(uuid.uuid4())
来源：http://dali.jinghuilouyu.cn/Article/details/gtjpjetqda.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sxryk.cn/Article/details/gtvzogenem.html

JS:   crypto.randomUUID()
来源：http://dali.zycfv.cn/Article/details/gtoeydabzw.html

TS:   crypto.randomUUID()
来源：http://dali.yj202588.top/Article/details/gtwlwczyej.html

Java: UUID.randomUUID().toString()
来源：http://dali.jianghu66.top/Article/details/gtzfhslsju.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jqgufenzy.top/Article/details/gtbytmsaer.html

Ruby: SecureRandom.uuid
来源：http://dali.zhaomingkeji.xyz/Article/details/gtspergyqh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtxyiwywym.html

[P02] MD5 / SHA256 摘要
来源：http://dali.pycfn.com/Article/details/gtnkwqowtk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.aibaodan.cn/Article/details/gtohjtzdxd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.pycfn.com/Article/details/gtvcistnzq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gotoacloud.top/Article/details/gteixyyfjy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yuxming.cn/Article/details/gtywjuxeai.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ivvv.top/Article/details/gtrpebgwxs.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinqigfzy.top/Article/details/gtolarftya.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jlsjyb.cn/Article/details/gtjxflonfk.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhiwuduotai.top/Article/details/gtdduiwbjy.html

[P03] 生成短随机字符串
来源：http://dali.hnxiangtu.top/Article/details/gtkbynognr.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hongshengwenyu.top/Article/details/gtxmlmrxtq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.316326.xyz/Article/details/gtkctlsovx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tian-w.cn/Article/details/gtchsxcirn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhengqikj.top/Article/details/gtwelxscie.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.gaohongyu789.top/Article/details/gtanajzjeo.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shanyushiyangtech.top/Article/details/gtwnwobsko.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.feifeiyinyue.top/Article/details/gtcvgoznto.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhoulong.xyz/Article/details/gtfxstwkbh.html

[P04] 求长度
来源：http://dali.c1oappe.top/Article/details/gtutyigrlb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.vqdsnc.cn/Article/details/gtsabuyvrx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.meibo888.top/Article/details/gtvrenfecg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinghuilouyu.cn/Article/details/gtieimvteo.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xylfe.cn/Article/details/gttxhdimhl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jianghu66.top/Article/details/gtxymxhksu.html

Go:   len(arr);  len(m)
来源：http://dali.gzhubu.top/Article/details/gtlhhuvcxx.html

Ruby: x.length;  x.size
来源：http://dali.sweek.top/Article/details/gtbjerfolh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.c1oappe.top/Article/details/gtzpihxpnv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yueranfly.top/Article/details/gtgipfhrod.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.wangshuangyany.cn/Article/details/gtsbsmkjkk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zdqjudy.top/Article/details/gtojbuptkm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hnxiangtu.top/Article/details/gtfbfiuqek.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.andypj.xyz/Article/details/gtpmslaxpv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jianghu66.top/Article/details/gtozzmfjfy.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jqgufenzy.top/Article/details/gtazutbfcd.html

Ruby: a == b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwirmbqxc.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cqqwz.cn/Article/details/gtpdfaglrs.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwtvgzflz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shanyushiyangtech.top/Article/details/gtvuitewkh.html

PHP:  if (empty($x)) {}
来源：http://dali.tian-w.cn/Article/details/gtgqkyyjyd.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.havefunace.top/Article/details/gtaavcrjjd.html

TS:   if (x == null) {}
来源：http://dali.jianghu66.top/Article/details/gtzycnyhzo.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.c1oappe.top/Article/details/gtdqogmkvv.html

Go:   if x == nil {}
来源：http://dali.vqdsnc.cn/Article/details/gtwfoxurea.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zycfv.cn/Article/details/gtmyyxaaru.html

C#:   if (x is null) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtedbddyry.html

[P07] 防抖与节流
来源：http://dali.havefunace.top/Article/details/gtgtcfnwyr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gaohongyu789.top/Article/details/gtrcjlkkpw.html

PHP:  // 手写时间戳比较
来源：http://dali.yj20258888.top/Article/details/gtgvwqgoqn.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aibaodan.cn/Article/details/gtmegedsqj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhoulong.xyz/Article/details/gtvgyavcyq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhixingplan.top/Article/details/gtpmbdojqx.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.quarkkingdee.top/Article/details/gtyqwradxj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.0kj1m.cn/Article/details/gtegfumxsw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.nwbrower.top/Article/details/gtsxgvkgvk.html

[P08] 处理浮点精度问题
来源：http://dali.cashguo.top/Article/details/gtukfvnybi.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.meibo888.top/Article/details/gtklplfbin.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.andypj.xyz/Article/details/gthhszmgct.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ydzc1.top/Article/details/gttumlpibh.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yvedp.cn/Article/details/gtycggfndx.html


<!-- 参考信息 -->