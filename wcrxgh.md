代发 wailian999

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gt2ddmntrkv.html

Ruby: ENV["HOME"]
来源：http://dali.cqqwz.cn/Article/details/gt2ulzoqvwm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.nanxinkj.top/Article/details/gt2bawaehcb.html

[M03] 执行外部命令
来源：http://dali.sufxvd.cn/Article/details/gt2codalsqp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.fzhhl.top/Article/details/gt2lrtykgsl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shzxlz.cn/Article/details/gt2hgiisdhg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuetiantiany.cn/Article/details/gt2tgxahysz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgufenzy.top/Article/details/gt2ujdwnqki.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hongshengwenyu.top/Article/details/gt2gtiobsph.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sweek.top/Article/details/gt2gxwjmwex.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.nwbrower.top/Article/details/gt2pevedgux.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cucudq.cn/Article/details/gt2lrsqyijg.html

[M04] 获取当前工作目录
来源：http://dali.cdnleiting.top/Article/details/gt2rjjzbgve.html

Py:   os.getcwd()
来源：http://dali.mhx1999.top/Article/details/gt2dfrwlrkn.html

PHP:  getcwd();
来源：http://dali.snrcjt.cn/Article/details/gt2pameupgj.html

JS:   process.cwd()
来源：http://dali.snrcjt.cn/Article/details/gt2rfxsbsts.html

TS:   process.cwd()
来源：http://dali.sxryk.cn/Article/details/gt2rihkxffj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jianghu66.top/Article/details/gt2cuimxqup.html

Go:   os.Getwd()
来源：http://dali.yj20258888.top/Article/details/gt2cxhrpijt.html

Ruby: Dir.pwd
来源：http://dali.fzhhl.top/Article/details/gt2jkueciqu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xuanzx.com/Article/details/gt2eyypqigs.html

[M05] 设置退出码
来源：http://dali.xuetiantiany.cn/Article/details/gt2sgidnmfs.html

Py:   sys.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2ogzvvjka.html

PHP:  exit(1);
来源：http://dali.xuanzx.com/Article/details/gt2nhiqfett.html

JS:   process.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2fyuysyuw.html

TS:   process.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gt2ehumnhtf.html

Java: System.exit(1)
来源：http://dali.birdmap.top/Article/details/gt2swrwmfpz.html

Go:   os.Exit(1)
来源：http://dali.jiagoushi.top/Article/details/gt2rwsbercx.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2htknjxmn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yonumen.top/Article/details/gt2uwsxkqig.html

[M06] 向标准错误输出
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ozrqfrrz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.smart0.xyz/Article/details/gt2fbpdvdzh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vzusoldj.html

JS:   console.error("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cxslvbyv.html

TS:   console.error("err")
来源：http://dali.pycfn.com/Article/details/gt2vatnlrwh.html

Java: System.err.println("err")
来源：http://dali.shzxlz.cn/Article/details/gt2hpquyinj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.wangshuangyany.cn/Article/details/gt2xeqeuztu.html

Ruby: warn "err"
来源：http://dali.yj20258.top/Article/details/gt2sqkemumy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hnxiangtu.top/Article/details/gt2qbhesooc.html

[M07] 判断是否为主入口
来源：http://dali.birdmap.top/Article/details/gt2ppswmnko.html

Py:   if __name__ == "__main__":
来源：http://dali.fzhhl.top/Article/details/gt2oceablsj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ehwqpu.com/Article/details/gt2khvyrtpp.html

JS:   require.main === module
来源：http://dali.mhx1999.top/Article/details/gt2ejlyqxoj.html

TS:   require.main === module
来源：http://dali.dianchejie.cn/Article/details/gt2kstpanij.html

Java: public static void main(String[] args)
来源：http://dali.cdnleiting.top/Article/details/gt2xcltcrvn.html

Go:   func main()
来源：http://dali.cucudq.cn/Article/details/gt2wkpsqcpv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cdnleiting.top/Article/details/gt2emkmcxmh.html

C#:   static void Main(string[] args)
来源：http://dali.ybcxt.top/Article/details/gt2ktdlivrx.html

[M08] 获取系统与运行时信息
来源：http://dali.smart0.xyz/Article/details/gt2kuoqdwib.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yonumen.top/Article/details/gt2xrmofwly.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.haohaochexian.top/Article/details/gt2qmfknvhh.html

JS:   process.platform;  process.version
来源：http://dali.chenjidiqi.icu/Article/details/gt2uedkwyws.html

TS:   process.platform;  process.version
来源：http://dali.shangyingyoupin.top/Article/details/gt2hxstmjft.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hysaishi.cn/Article/details/gt2axdllvsg.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hnxiangtu.top/Article/details/gt2gxyfiqud.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.chenlongwang.top/Article/details/gt2qwvgdpxt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hongshengwenyu.top/Article/details/gt2kariafmv.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2quiqzhlu.html

N. 数据结构与算法
来源：http://dali.guowangkeji.top/Article/details/gt2kgzgvoyq.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2oetoybnn.html

[N01] 二分查找（有序数组）
来源：http://dali.zhiwuduotai.top/Article/details/gt2qcvahrjw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gt2fikoqteu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.smart0.xyz/Article/details/gt2euzdfcyz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.meibo888.top/Article/details/gt2uvgwpbrk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenzaomai.com/Article/details/gt2cbtbrjqz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gt2udpocwco.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yj20258.top/Article/details/gt2phtvvcqb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jyoumei.cn/Article/details/gt2acfylhlv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.daria6918.cn/Article/details/gt2yhbeblhi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xuanzx.com/Article/details/gt2wyehpuva.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.guowangkeji.top/Article/details/gt2ylgwgpvf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.tianlin.xyz/Article/details/gt2pextljlm.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tian-w.cn/Article/details/gt2vrpoxrih.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.316326.xyz/Article/details/gt2iapcdgpj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.fzhhl.top/Article/details/gt2fzotihlg.html

Go:   slices.Sort(arr)
来源：http://dali.yj20258888.top/Article/details/gt2toymegzn.html

Ruby: arr.sort
来源：http://dali.pycfn.com/Article/details/gt2typasjkp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ehwqpu.com/Article/details/gt2gtjdotlz.html

[N03] 快速排序（分治示例）
来源：http://dali.gogol.net.cn/Article/details/gt2vnhulxwc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yangfankeji.com/Article/details/gt2suztpciv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ydzc1.top/Article/details/gt2cylfmuxt.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fzhhl.top/Article/details/gt2jcywictb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guannengcc.top/Article/details/gt2jjzqyhqd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinqigufen.top/Article/details/gt2fwekzhrk.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.smart0.xyz/Article/details/gt2tjnvbnah.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.c1oappe.top/Article/details/gt2nblvfjlb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhoulong.xyz/Article/details/gt2wmmfggqq.html

[N04] 斐波那契数列
来源：http://dali.xinyue.icu/Article/details/gt2udzxpuui.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wagzyxhm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.daria6918.cn/Article/details/gt2sipfvrgu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cucudq.cn/Article/details/gt2qlekftex.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sokdigxq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.0kj1m.cn/Article/details/gt2xtpvdqiw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yvedp.cn/Article/details/gt2ajbsdpjc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cashguo.top/Article/details/gt2roskould.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gt2ocnuulrk.html

[N05] 最大公约数
来源：http://dali.ivvv.top/Article/details/gt2qhndcycc.html

Py:   math.gcd(a, b)
来源：http://dali.wangdashe.top/Article/details/gt2uwnqguvl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ehwqpu.com/Article/details/gt2yauhcztx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2disslspg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ftncjwps.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yj20258888.top/Article/details/gt2vmlfkhfn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinqigfzy.top/Article/details/gt2avprjort.html

Ruby: a.gcd(b)
来源：http://dali.daxiang520.top/Article/details/gt2fxdgnrep.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jyoumei.cn/Article/details/gt2anopjiwj.html

[N06] 判断回文字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2vjspoaji.html

Py:   s == s[::-1]
来源：http://dali.yj202588.top/Article/details/gt2dtqmybdg.html

PHP:  $s === strrev($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vofwfohe.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gt2pcbnutgu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ahzcyfco.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlvqkev.html

Go:   // 双指针从两端比较
来源：http://dali.0kj1m.cn/Article/details/gt2prqdapur.html

Ruby: s == s.reverse
来源：http://dali.yongpay.top/Article/details/gt2fsplfure.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hammf.cn/Article/details/gt2hjbthmgq.html

[N07] 两数之和（返回下标）
来源：http://dali.zhongyouzk.top/Article/details/gt2rmntkjcj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hywenlv.cn/Article/details/gt2srjkzhdu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jlsjyb.cn/Article/details/gt2hxemukpj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhwkqdz.html

TS:   // 手写 Map<string, number>
来源：http://dali.yongpay.top/Article/details/gt2jpvlizel.html

Java: // 手写 HashMap
来源：http://dali.hnqzz.top/Article/details/gt2vgvikbzx.html

Go:   // 手写 map[int]int
来源：http://dali.hongshengwenyu.top/Article/details/gt2ojfhqrmo.html

Ruby: // 手写 Hash
来源：http://dali.tianlin.xyz/Article/details/gt2qewxuyqy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.9152youxi.cn/Article/details/gt2qibeimqm.html

[N08] 生成全排列
来源：http://dali.gzhubu.top/Article/details/gt2ebdhkfng.html

Py:   itertools.permutations(arr)
来源：http://dali.yongpay.top/Article/details/gt2iyacwnes.html

PHP:  // 手写递归交换
来源：http://dali.hywenlv.cn/Article/details/gt2ymrvljaa.html

JS:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gt2zaxclovw.html

TS:   // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gt2cwcuytwk.html

Java: // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aruzndoj.html

Go:   // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qyanyqcp.html

Ruby: arr.permutation.to_a
来源：http://dali.redwolf501.top/Article/details/gt2uuknwjqa.html

C#:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gt2rxtzzwfo.html

[N09] 栈与队列
来源：http://dali.gotoacloud.top/Article/details/gt2enhbvwvp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.birdmap.top/Article/details/gt2kcerszru.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gt2opyhjowc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nanxuanxn.top/Article/details/gt2urjhysai.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.c1oappe.top/Article/details/gt2kfrdfiyy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.chenlongwang.top/Article/details/gt2iupsijsl.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.wangshuangyany.cn/Article/details/gt2pnwtwqvt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.0kj1m.cn/Article/details/gt2sqdpsszo.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ybcxt.top/Article/details/gt2vzipkayi.html

[N10] 链表节点定义
来源：http://dali.snrcjt.cn/Article/details/gt2sunerwvi.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jqgfzy.top/Article/details/gt2nzgjvlzw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.kuanghao11.cn/Article/details/gt2wltltcey.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xuanzx.com/Article/details/gt2oseigqza.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.tianlin.xyz/Article/details/gt2wdqftgac.html

Java: class Node { int v; Node next; }
来源：http://dali.gaohongyu789.top/Article/details/gt2bbzsimix.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ckswsyqv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.andypj.xyz/Article/details/gt2muiaiaot.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xziqi.cn/Article/details/gt2ulfgclqn.html

[N11] 二叉树中序遍历
来源：http://dali.yonumen.top/Article/details/gt2yovgcznm.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hfpthk.cn/Article/details/gt2rawelkcv.html

PHP:  // 手写递归函数
来源：http://dali.yuanzhike.top/Article/details/gt2qnbnpoki.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guowangkeji.top/Article/details/gt2kioswwwc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zycfv.cn/Article/details/gt2rvnmusto.html

Java: // 手写递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2widplrvv.html

Go:   // 手写递归
来源：http://dali.sufxvd.cn/Article/details/gt2fcqhyqmx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cdnleiting.top/Article/details/gt2pejzlpal.html

C#:   // 手写递归
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lgpzxdrf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhongyouzk.top/Article/details/gt2ykalifwj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hywenlv.cn/Article/details/gt2lbfhfzel.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.mhx1999.top/Article/details/gt2glvjxrlk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.c1oappe.top/Article/details/gt2dfcqgfoc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tzegmbaz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nwbrower.top/Article/details/gt2bvzqsuif.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jianghu66.top/Article/details/gt2sngkfufb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xuetiantiany.cn/Article/details/gt2bddarzsn.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guannengcc.top/Article/details/gt2zdwuqzkl.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2pbxmypoh.html

O. 并发与异步
来源：http://dali.haohaochexian.top/Article/details/gt2gduinayr.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2tlylgszn.html

[O01] 启动一个线程
来源：http://dali.daxiang520.top/Article/details/gt2cwwpjhqi.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.havefunace.top/Article/details/gt2ajeyxjqv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yonumen.top/Article/details/gt2pyssomjb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nbbeqnnm.html

TS:   // 同 JS
来源：http://dali.cheryme.top/Article/details/gt2mufkrbso.html

Java: new Thread(() -> f()).start()
来源：http://dali.yvedp.cn/Article/details/gt2liyhvyea.html

Go:   go f()
来源：http://dali.tanke756.top/Article/details/gt2wqubcxpx.html

Ruby: Thread.new { f }
来源：http://dali.smart0.xyz/Article/details/gt2daxvkguc.html

C#:   Task.Run(() => F());
来源：http://dali.jinqigufen.top/Article/details/gt2safsytdv.html

[O02] 使用线程池
来源：http://dali.ydzc1.top/Article/details/gt2veyejhdp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.sxryk.cn/Article/details/gt2lhdgrevx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.chenlongwang.top/Article/details/gt2eeavyuye.html

JS:   // worker_threads 线程池
来源：http://dali.guowangkeji.top/Article/details/gt2rfdzhllj.html

TS:   // worker_threads 线程池
来源：http://dali.xuanzx.com/Article/details/gt2ywykuxgb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhiwuduotai.top/Article/details/gt2fiozxvrs.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cucudq.cn/Article/details/gt2cphmdsqk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.vqdsnc.cn/Article/details/gt2bezxxidt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jqgfzy.top/Article/details/gt2jbidwgsi.html

[O03] 加锁保护共享数据
来源：http://dali.zhengqikj.top/Article/details/gt2uuavtggk.html

Py:   with lock: shared += 1
来源：http://dali.hywenlv.cn/Article/details/gt2grunyiby.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hammf.cn/Article/details/gt2gfkbeepd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.wangdashe.top/Article/details/gt2aueshhsa.html

TS:   // 同 JS
来源：http://dali.ppjwa.cn/Article/details/gt2flmmdfrj.html

Java: synchronized (this) { shared++; }
来源：http://dali.sxryk.cn/Article/details/gt2iozxppdh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.aibaodan.cn/Article/details/gt2turschbg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gotoacloud.top/Article/details/gt2bnoxrfol.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhongyouzk.top/Article/details/gt2tdlmlynw.html

[O04] 定义异步函数并等待
来源：http://dali.yonumen.top/Article/details/gt2fooxnbjs.html

Py:   async def f():⏎    await g()
来源：http://dali.daxiang520.top/Article/details/gt2dnvecgoj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.mhx1999.top/Article/details/gt2weedcdpk.html

JS:   async function f() { await g(); }
来源：http://dali.cdnleiting.top/Article/details/gt2kpkgaqsn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2dzzuyxhu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eopyngnb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gzhubu.top/Article/details/gt2hiyvtnor.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.iojbl.cn/Article/details/gt2zarvtpkh.html

C#:   async Task F() { await G(); }
来源：http://dali.jianghu66.top/Article/details/gt2uahdehvv.html

[O05] 并发执行并等待全部完成
来源：http://dali.jqgfzy.top/Article/details/gt2yewwwtxu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hnqzz.top/Article/details/gt2rpompnoi.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hysaishi.cn/Article/details/gt2rwjwoori.html

JS:   await Promise.all(tasks)
来源：http://dali.gotoacloud.top/Article/details/gt2ekhgeokl.html

TS:   await Promise.all(tasks)
来源：http://dali.316326.xyz/Article/details/gt2gwporflt.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.redwolf501.top/Article/details/gt2zflnvyqd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tian-w.cn/Article/details/gt2hzchcpht.html

Ruby: threads.map(&:join)
来源：http://dali.316326.xyz/Article/details/gt2nvelgrjx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.smart0.xyz/Article/details/gt2legcoqpg.html

[O06] 使用进程池
来源：http://dali.cucudq.cn/Article/details/gt2cizowawa.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.9152youxi.cn/Article/details/gt2neuwomza.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.fengsongda.top/Article/details/gt2qytciinz.html

JS:   // child_process / cluster 模块
来源：http://dali.yvedp.cn/Article/details/gt2frqxrlbc.html

TS:   // child_process / cluster 模块
来源：http://dali.tanke756.top/Article/details/gt2jgmxnzvm.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.aibaodan.cn/Article/details/gt2ytvtdgef.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jianghu66.top/Article/details/gt2lzoumnbh.html

Ruby: // fork 块
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uxduwplx.html

C#:   Parallel.For
来源：http://dali.pycfn.com/Article/details/gt2rgezllth.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2bmimuvin.html

P. 常用工具函数
来源：http://dali.tanke756.top/Article/details/gt2bgpgfuhr.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2cwspviuo.html

[P01] 生成 UUID
来源：http://dali.iojbl.cn/Article/details/gt2wjxqzwlr.html

Py:   str(uuid.uuid4())
来源：http://dali.fzhhl.top/Article/details/gt2fjhoklkd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhongyouzk.top/Article/details/gt2nxeovngx.html

JS:   crypto.randomUUID()
来源：http://dali.nanxuanxn.top/Article/details/gt2ggdumrzk.html

TS:   crypto.randomUUID()
来源：http://dali.hnqzz.top/Article/details/gt2hkdawuim.html

Java: UUID.randomUUID().toString()
来源：http://dali.jyoumei.cn/Article/details/gt2lgmdoxqm.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xziqi.cn/Article/details/gt2yoifdnak.html

Ruby: SecureRandom.uuid
来源：http://dali.yueranfly.top/Article/details/gt2xuffqein.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hnxiangtu.top/Article/details/gt2zscyqhsn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yj202588.top/Article/details/gt2uqinlryx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.meibo888.top/Article/details/gt2ojsbystk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xuanzx.com/Article/details/gt2ktxzrrev.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zdqjudy.top/Article/details/gt2qosaqzcd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tian-w.cn/Article/details/gt2ncnpjglr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2upldzsnq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cucudq.cn/Article/details/gt2hzbfzflq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ytponfqu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.guowangkeji.top/Article/details/gt2hfledkgp.html

[P03] 生成短随机字符串
来源：http://dali.cashguo.top/Article/details/gt2ovtqpbxp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.pycfn.com/Article/details/gt2eadtikwy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.nanxinkj.top/Article/details/gt2pzyhknna.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shuidangran.top/Article/details/gt2sdwfkzbt.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yangfankeji.com/Article/details/gt2vexwccct.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinqigfzy.top/Article/details/gt2snmumimm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvldxgb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.wangshuangyany.cn/Article/details/gt2kwtkbnuo.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.aizwys.cn/Article/details/gt2fcutnbgx.html

[P04] 求长度
来源：http://dali.snrcjt.cn/Article/details/gt2pjdzpjta.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenzaomai.com/Article/details/gt2ukcnlhzm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gt2pkkkvmte.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yonumen.top/Article/details/gt2yzxzmckd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.kuanghao11.cn/Article/details/gt2rqoipvxx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hammf.cn/Article/details/gt2paprkcpd.html

Go:   len(arr);  len(m)
来源：http://dali.cheryme.top/Article/details/gt2bwqalqrl.html

Ruby: x.length;  x.size
来源：http://dali.jinqigufen.top/Article/details/gt2fgxgoaxj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.havefunace.top/Article/details/gt2erfwcgxg.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zdqjudy.top/Article/details/gt2zpwffwdo.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhoulong.xyz/Article/details/gt2yvbvdgtv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.daria6918.cn/Article/details/gt2gylacjdk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.meibo888.top/Article/details/gt2atphjwfb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zdqjudy.top/Article/details/gt2szgrpddq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gaohongyu789.top/Article/details/gt2qehbeism.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cashguo.top/Article/details/gt2jrfrcmnd.html

Ruby: a == b
来源：http://dali.cheryme.top/Article/details/gt2pbaminlp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xuetiantiany.cn/Article/details/gt2rvorxoim.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.fzhhl.top/Article/details/gt2spllkzgl.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.sweek.top/Article/details/gt2qkvnanlh.html

PHP:  if (empty($x)) {}
来源：http://dali.guowangkeji.top/Article/details/gt2iyoenvcm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.guannengcc.top/Article/details/gt2kdhnjzkb.html

TS:   if (x == null) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2zixlakiv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2bgaqihol.html

Go:   if x == nil {}
来源：http://dali.xziqi.cn/Article/details/gt2tjjqdqjh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xylfe.cn/Article/details/gt2qnijzdvn.html

C#:   if (x is null) {}
来源：http://dali.dashuyun.cn/Article/details/gt2emnppjsd.html

[P07] 防抖与节流
来源：http://dali.nwbrower.top/Article/details/gt2xkgfgbis.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.havefunace.top/Article/details/gt2wxcaalzc.html

PHP:  // 手写时间戳比较
来源：http://dali.xuanzx.com/Article/details/gt2jxaimopv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxuanxn.top/Article/details/gt2warainje.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jianghu66.top/Article/details/gt2tfgefwbi.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2zsgeaqxn.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ehwqpu.com/Article/details/gt2xpgsvfdl.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.bjfxy.top/Article/details/gt2tthlehni.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.aizwys.cn/Article/details/gt2uadlnhft.html

[P08] 处理浮点精度问题
来源：http://dali.gogol.net.cn/Article/details/gt2bkflnbva.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.smart0.xyz/Article/details/gt2gkkbhxct.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ehwqpu.com/Article/details/gt2ewkqdvxm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ppjwa.cn/Article/details/gt2yqletgey.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.sweek.top/Article/details/gt2yfkjglzx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yj202588.top/Article/details/gt2olblurre.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cdnleiting.top/Article/details/gt2qmwmybgp.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.snrcjt.cn/Article/details/gt2vycjialw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cdnleiting.top/Article/details/gt2swsxgcgh.html


<!-- 参考信息 -->