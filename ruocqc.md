代发 wailian999

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gthrkwrqbt.html

Ruby: ENV["HOME"]
来源：http://dali.yongpay.top/Article/details/gtpblsdhut.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gtdeqdaeos.html

[M03] 执行外部命令
来源：http://dali.hysaishi.cn/Article/details/gtudtxcpzo.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.kuanghao11.cn/Article/details/gtpsdqiwqt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.iojbl.cn/Article/details/gtgxwhsnvw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shangyingyoupin.top/Article/details/gtxfemzeaf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtqatywydl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ydzc1.top/Article/details/gtrgdkqlbu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ivvv.top/Article/details/gtxzbfsuda.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.wangshuangyany.cn/Article/details/gtuutceosr.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ppjwa.cn/Article/details/gtwkcpylyx.html

[M04] 获取当前工作目录
来源：http://dali.haohaochexian.top/Article/details/gtxodrpemx.html

Py:   os.getcwd()
来源：http://dali.yangfankeji.com/Article/details/gtfpvexgpx.html

PHP:  getcwd();
来源：http://dali.jlsjyb.cn/Article/details/gtyggkyccm.html

JS:   process.cwd()
来源：http://dali.cdnleiting.top/Article/details/gteiceqzcd.html

TS:   process.cwd()
来源：http://dali.jinqigufen.top/Article/details/gtpdlhfrwi.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.wangdashe.top/Article/details/gttdcsmxtg.html

Go:   os.Getwd()
来源：http://dali.gzhubu.top/Article/details/gthuutnwid.html

Ruby: Dir.pwd
来源：http://dali.jianghu66.top/Article/details/gtvuwypnul.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinqigfzy.top/Article/details/gtzqzhrvig.html

[M05] 设置退出码
来源：http://dali.cucudq.cn/Article/details/gtohzcjjxq.html

Py:   sys.exit(1)
来源：http://dali.sxryk.cn/Article/details/gtmycjosom.html

PHP:  exit(1);
来源：http://dali.hnxiangtu.top/Article/details/gtkybabqyk.html

JS:   process.exit(1)
来源：http://dali.iojbl.cn/Article/details/gtxfxmlmsv.html

TS:   process.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtbbnpmtdy.html

Java: System.exit(1)
来源：http://dali.yongpay.top/Article/details/gtggmbqckx.html

Go:   os.Exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtpxnxionv.html

Ruby: exit 1
来源：http://dali.smart0.xyz/Article/details/gtxlefwrmy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.iojbl.cn/Article/details/gtrotgvsug.html

[M06] 向标准错误输出
来源：http://dali.bjfxy.top/Article/details/gtyimzthfi.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jyoumei.cn/Article/details/gtlttknssc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shzxlz.cn/Article/details/gtsvixaoca.html

JS:   console.error("err")
来源：http://dali.cashguo.top/Article/details/gtesvxqmcn.html

TS:   console.error("err")
来源：http://dali.hammf.cn/Article/details/gtbymmrrdy.html

Java: System.err.println("err")
来源：http://dali.dianchejie.cn/Article/details/gtqnqrwsas.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.redwolf501.top/Article/details/gtaxdassmi.html

Ruby: warn "err"
来源：http://dali.ybcxt.top/Article/details/gtoghkpoym.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jyoumei.cn/Article/details/gtkwqczeas.html

[M07] 判断是否为主入口
来源：http://dali.aibaodan.cn/Article/details/gtbawawwka.html

Py:   if __name__ == "__main__":
来源：http://dali.haohaochexian.top/Article/details/gthfljndus.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sufxvd.cn/Article/details/gtigqslgym.html

JS:   require.main === module
来源：http://dali.yangfankeji.com/Article/details/gthldqrovn.html

TS:   require.main === module
来源：http://dali.0kj1m.cn/Article/details/gtrobpszkg.html

Java: public static void main(String[] args)
来源：http://dali.hywenlv.cn/Article/details/gtpuprbhwo.html

Go:   func main()
来源：http://dali.shanyushiyangtech.top/Article/details/gtllojhbpp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.kuanghao11.cn/Article/details/gtctyvzmmi.html

C#:   static void Main(string[] args)
来源：http://dali.yvedp.cn/Article/details/gtypwhdbnb.html

[M08] 获取系统与运行时信息
来源：http://dali.daria6918.cn/Article/details/gtiiomhypi.html

Py:   platform.system();  platform.python_version()
来源：http://dali.svipenyu.cn/Article/details/gtsowwddyo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.dianchejie.cn/Article/details/gtxwpzbips.html

JS:   process.platform;  process.version
来源：http://dali.daria6918.cn/Article/details/gtkcglleri.html

TS:   process.platform;  process.version
来源：http://dali.andypj.xyz/Article/details/gtirlvynbu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.aibaodan.cn/Article/details/gtnqsbjuzn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jlsjyb.cn/Article/details/gtuoosxyhp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yuxming.cn/Article/details/gtmlokdtvg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.pycfn.com/Article/details/gtovcogufg.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtcghzxzeu.html

N. 数据结构与算法
来源：http://dali.xziqi.cn/Article/details/gtamxhtyuh.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtxegttdvs.html

[N01] 二分查找（有序数组）
来源：http://dali.nanxinkj.top/Article/details/gtsxcufqpj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtfftbmhwv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.smart0.xyz/Article/details/gtelxsefwy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.kuanghao11.cn/Article/details/gtrdxyiunc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gtyjbffktr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtminnbhhu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtknmbbnaq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj20258.top/Article/details/gtmzjwjdnx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtomerjlxo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ehwqpu.com/Article/details/gthhnlkpnp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvoweguur.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jyoumei.cn/Article/details/gtrruekqfr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hywenlv.cn/Article/details/gtjnkswetj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nwbrower.top/Article/details/gtnssifjny.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zdqjudy.top/Article/details/gtabqbvjix.html

Go:   slices.Sort(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtixjrspjg.html

Ruby: arr.sort
来源：http://dali.0kj1m.cn/Article/details/gtiqtythgs.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.chenlongwang.top/Article/details/gticberimc.html

[N03] 快速排序（分治示例）
来源：http://dali.gotoacloud.top/Article/details/gtwacunvtt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.tanke756.top/Article/details/gtpkfllfsi.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yuxming.cn/Article/details/gtwhtmvbnc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhoulong.xyz/Article/details/gtrbtvuhwh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yangfankeji.com/Article/details/gtxlgjijyp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.dianchejie.cn/Article/details/gtbmxamrly.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenlongwang.top/Article/details/gtytqvvcjr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zdqjudy.top/Article/details/gthhbmbscz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gtatabqrmz.html

[N04] 斐波那契数列
来源：http://dali.zhengqikj.top/Article/details/gtvzytlmcp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.9152youxi.cn/Article/details/gtrizwmmbz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hammf.cn/Article/details/gtdqkuorrq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gtthigueof.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gtkcgswlxt.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtggzuihvq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthbxmvhxx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.guannengcc.top/Article/details/gtyhmrpaeq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxwdmqlyk.html

[N05] 最大公约数
来源：http://dali.sysykeji.top/Article/details/gtgvygtuke.html

Py:   math.gcd(a, b)
来源：http://dali.xinyue.icu/Article/details/gtzuhtaxuf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ppjwa.cn/Article/details/gtwparvyfo.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xziqi.cn/Article/details/gtjbrlfzfc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fengsongda.top/Article/details/gtmnrqdojh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ydzc1.top/Article/details/gtmkrcdiha.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yvedp.cn/Article/details/gtyscaktfo.html

Ruby: a.gcd(b)
来源：http://dali.feifeiyinyue.top/Article/details/gtqocfaxfg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.redwolf501.top/Article/details/gtxflrwolk.html

[N06] 判断回文字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlgpfjxtj.html

Py:   s == s[::-1]
来源：http://dali.meibo888.top/Article/details/gthzyhxmdi.html

PHP:  $s === strrev($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtpiraeptg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gtbhwwbqkm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gtrcsfcxrl.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.aizwys.cn/Article/details/gttcxdspfq.html

Go:   // 双指针从两端比较
来源：http://dali.jqgfzy.top/Article/details/gtilrgkund.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gtnryxgjkn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinghuilouyu.cn/Article/details/gtezatmxzp.html

[N07] 两数之和（返回下标）
来源：http://dali.bjfxy.top/Article/details/gtlpsjaoku.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.wangshuangyany.cn/Article/details/gtvspzczuy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shanyushiyangtech.top/Article/details/gtizabaeex.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yonumen.top/Article/details/gteinzdslo.html

TS:   // 手写 Map<string, number>
来源：http://dali.gaohongyu789.top/Article/details/gtjwcenxyg.html

Java: // 手写 HashMap
来源：http://dali.jqgufenzy.top/Article/details/gtuntguvqv.html

Go:   // 手写 map[int]int
来源：http://dali.cashguo.top/Article/details/gthktbioxm.html

Ruby: // 手写 Hash
来源：http://dali.316326.xyz/Article/details/gtuqmilcyx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.pycfn.com/Article/details/gtmuazwqgm.html

[N08] 生成全排列
来源：http://dali.zhengqikj.top/Article/details/gtwqqttvqv.html

Py:   itertools.permutations(arr)
来源：http://dali.snrcjt.cn/Article/details/gtdijtjakl.html

PHP:  // 手写递归交换
来源：http://dali.hongshengwenyu.top/Article/details/gtdqssbxkl.html

JS:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtyylhbpnz.html

TS:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gtdatttreq.html

Java: // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtmzucrcea.html

Go:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gtfbfnukpk.html

Ruby: arr.permutation.to_a
来源：http://dali.dianchejie.cn/Article/details/gtyrbactjb.html

C#:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtorqwmjmv.html

[N09] 栈与队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlwntvvrc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jqgufenzy.top/Article/details/gtatetosep.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gaohongyu789.top/Article/details/gttqzeosga.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gtutuxshpa.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cdnleiting.top/Article/details/gtmnvsdooz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yueranfly.top/Article/details/gtqycvkhmp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.9152youxi.cn/Article/details/gtyavivnyy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.9152youxi.cn/Article/details/gtuqpskoto.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.smart0.xyz/Article/details/gtqtvbfkrx.html

[N10] 链表节点定义
来源：http://dali.bjfxy.top/Article/details/gtbpldbsbh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqhkfcvev.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.quarkkingdee.top/Article/details/gtqcatqgdh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.wangdashe.top/Article/details/gtboiwmyrn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xuanzx.com/Article/details/gtcvzayzsm.html

Java: class Node { int v; Node next; }
来源：http://dali.nanxuanxn.top/Article/details/gtqdholkai.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shzxlz.cn/Article/details/gtjdythiev.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jinqigufen.top/Article/details/gtdzhfitca.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.smart0.xyz/Article/details/gtgambwgln.html

[N11] 二叉树中序遍历
来源：http://dali.jyoumei.cn/Article/details/gtnlsrrgxu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cheryme.top/Article/details/gtqstqyogw.html

PHP:  // 手写递归函数
来源：http://dali.xinyue.icu/Article/details/gtonzewzir.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnxiangtu.top/Article/details/gtlidwrzof.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yongpay.top/Article/details/gtmhzopxjp.html

Java: // 手写递归
来源：http://dali.tianlin.xyz/Article/details/gtmbpbtbto.html

Go:   // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gtjdcpvhts.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.birdmap.top/Article/details/gtqtraaglu.html

C#:   // 手写递归
来源：http://dali.bjfxy.top/Article/details/gtlvkubtvz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.feifeiyinyue.top/Article/details/gtxvaleoye.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.316326.xyz/Article/details/gtmymdqypp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xinyue.icu/Article/details/gtqrrwekrz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ehwqpu.com/Article/details/gtjwhkihvw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.andypj.xyz/Article/details/gtutmyzlcz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuanzx.com/Article/details/gtihogyftg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.tanke756.top/Article/details/gthhiurotq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.guannengcc.top/Article/details/gtefzwtlqd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yueranfly.top/Article/details/gtfbfydwfb.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtqvvgwrva.html

O. 并发与异步
来源：http://dali.xylfe.cn/Article/details/gtnzhnobfy.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtqjqxliuo.html

[O01] 启动一个线程
来源：http://dali.nanxuanxn.top/Article/details/gtiivsftne.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jinqigufen.top/Article/details/gtetxvvpxz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hnxiangtu.top/Article/details/gtjnlamnah.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cdnleiting.top/Article/details/gtkhggrhcs.html

TS:   // 同 JS
来源：http://dali.9152youxi.cn/Article/details/gtqpesmxcb.html

Java: new Thread(() -> f()).start()
来源：http://dali.sxryk.cn/Article/details/gtglhewvgq.html

Go:   go f()
来源：http://dali.aizwys.cn/Article/details/gtfsvcengx.html

Ruby: Thread.new { f }
来源：http://dali.yanxiufei.cn/Article/details/gtejehmnzc.html

C#:   Task.Run(() => F());
来源：http://dali.xinyue.icu/Article/details/gtkmoxnfnm.html

[O02] 使用线程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpqehszsu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xinyue.icu/Article/details/gtqsdyglye.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.snrcjt.cn/Article/details/gtfvtccnpc.html

JS:   // worker_threads 线程池
来源：http://dali.daxiang520.top/Article/details/gtcalnmrri.html

TS:   // worker_threads 线程池
来源：http://dali.316326.xyz/Article/details/gtayvievpc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.guannengcc.top/Article/details/gtvmwfrjeh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.andypj.xyz/Article/details/gtldobhxhn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jinqigfzy.top/Article/details/gtwwtqnbjf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ydzc1.top/Article/details/gtlhqrpcua.html

[O03] 加锁保护共享数据
来源：http://dali.zhongyouzk.top/Article/details/gtizynwyyh.html

Py:   with lock: shared += 1
来源：http://dali.tianlin.xyz/Article/details/gtunautwcy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ydzc1.top/Article/details/gtukivwzuu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmtckvpin.html

TS:   // 同 JS
来源：http://dali.dashuyun.cn/Article/details/gtczeipuho.html

Java: synchronized (this) { shared++; }
来源：http://dali.hysaishi.cn/Article/details/gtbrobbykd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ybcxt.top/Article/details/gtoymbwedt.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hnxiangtu.top/Article/details/gttqpmehtp.html

C#:   lock (gate) { shared++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttkcelxtk.html

[O04] 定义异步函数并等待
来源：http://dali.jlsjyb.cn/Article/details/gtohbvepil.html

Py:   async def f():⏎    await g()
来源：http://dali.gotoacloud.top/Article/details/gthbqbbyhp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.wangshuangyany.cn/Article/details/gtihvycakl.html

JS:   async function f() { await g(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtlvcvmhjy.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtblaxxynx.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shzxlz.cn/Article/details/gtolrljuoy.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jiagoushi.top/Article/details/gtepssvnlc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cheryme.top/Article/details/gtdteicuud.html

C#:   async Task F() { await G(); }
来源：http://dali.xziqi.cn/Article/details/gtaypvhyoz.html

[O05] 并发执行并等待全部完成
来源：http://dali.ybcxt.top/Article/details/gtagearpjw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hywenlv.cn/Article/details/gtcnpmxwgt.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gotoacloud.top/Article/details/gtoryyzocb.html

JS:   await Promise.all(tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkpbuxrhe.html

TS:   await Promise.all(tasks)
来源：http://dali.smart0.xyz/Article/details/gtywelnhiz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzonhryhn.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jiagoushi.top/Article/details/gtyqfynatb.html

Ruby: threads.map(&:join)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbrtznuxo.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cdnleiting.top/Article/details/gthqndfulk.html

[O06] 使用进程池
来源：http://dali.sxryk.cn/Article/details/gtrkyclfed.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shangyingyoupin.top/Article/details/gtrvnhpzqj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.iojbl.cn/Article/details/gtuqwgoguw.html

JS:   // child_process / cluster 模块
来源：http://dali.daxiang520.top/Article/details/gtnuqisdsa.html

TS:   // child_process / cluster 模块
来源：http://dali.chenjidiqi.icu/Article/details/gtjkpcbylc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.guannengcc.top/Article/details/gtrcdtgogn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.dashuyun.cn/Article/details/gtrquxkgrg.html

Ruby: // fork 块
来源：http://dali.fzhhl.top/Article/details/gthnruetae.html

C#:   Parallel.For
来源：http://dali.tanke756.top/Article/details/gtfedmyaig.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtqocgcpkd.html

P. 常用工具函数
来源：http://dali.cashguo.top/Article/details/gtonyehcph.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnwqcxmcf.html

[P01] 生成 UUID
来源：http://dali.xuetiantiany.cn/Article/details/gtwdgkjznb.html

Py:   str(uuid.uuid4())
来源：http://dali.chenzaomai.com/Article/details/gtefumilfu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ppjwa.cn/Article/details/gtgyyfddwe.html

JS:   crypto.randomUUID()
来源：http://dali.sufxvd.cn/Article/details/gtwskhgdjw.html

TS:   crypto.randomUUID()
来源：http://dali.9152youxi.cn/Article/details/gtbslfznxd.html

Java: UUID.randomUUID().toString()
来源：http://dali.bjfxy.top/Article/details/gtnlovfydw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jyoumei.cn/Article/details/gtbrszffox.html

Ruby: SecureRandom.uuid
来源：http://dali.jyoumei.cn/Article/details/gtzloavgoh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.iojbl.cn/Article/details/gtscccrkci.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hfpthk.cn/Article/details/gtqowdttor.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.kuanghao11.cn/Article/details/gtinvqomei.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhengqikj.top/Article/details/gtmbodosot.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinqigfzy.top/Article/details/gtyaadyzvl.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shanyushiyangtech.top/Article/details/gtpiygnpvb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.c1oappe.top/Article/details/gtozuktqym.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hongshengwenyu.top/Article/details/gtzpviowdd.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hnxiangtu.top/Article/details/gtuqvfvlvj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinqigfzy.top/Article/details/gtqlkoasgv.html

[P03] 生成短随机字符串
来源：http://dali.guowangkeji.top/Article/details/gtkwaswofv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cashguo.top/Article/details/gtppnbeupo.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xylfe.cn/Article/details/gtjtyenibz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhengqikj.top/Article/details/gtfljyjarj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.andypj.xyz/Article/details/gtwgtgsngw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yongpay.top/Article/details/gtqxvnckoa.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cqqwz.cn/Article/details/gtihnguwde.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jiagoushi.top/Article/details/gtjiuwjudp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.havefunace.top/Article/details/gtgdmjwdio.html

[P04] 求长度
来源：http://dali.smart0.xyz/Article/details/gtemojbxey.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cheryme.top/Article/details/gttucqkluk.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gttrjtasea.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj20258888.top/Article/details/gtlwkyyygc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jyoumei.cn/Article/details/gtpsbiuanv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvckiqxjn.html

Go:   len(arr);  len(m)
来源：http://dali.cheryme.top/Article/details/gtulazynpb.html

Ruby: x.length;  x.size
来源：http://dali.yangfankeji.com/Article/details/gtfgjvxfmy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.fengsongda.top/Article/details/gtxuvynvxo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jqgufenzy.top/Article/details/gttgjqwitu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.redwolf501.top/Article/details/gtcqzfyorb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jyoumei.cn/Article/details/gttqyxyroa.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gzhubu.top/Article/details/gtgsclsezc.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xinyue.icu/Article/details/gtddstsdas.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yuanzhike.top/Article/details/gtxsyrardm.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sweek.top/Article/details/gtvrlevxlq.html

Ruby: a == b
来源：http://dali.cqqwz.cn/Article/details/gtalunyyyo.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.tanke756.top/Article/details/gteohloskc.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.wangdashe.top/Article/details/gtktrpviqj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gtcjjzrawn.html

PHP:  if (empty($x)) {}
来源：http://dali.nanxuanxn.top/Article/details/gtfaqjpxcw.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xuanzx.com/Article/details/gtxoagvwep.html

TS:   if (x == null) {}
来源：http://dali.aizwys.cn/Article/details/gtxqdsrrvx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ivvv.top/Article/details/gtwteepflt.html

Go:   if x == nil {}
来源：http://dali.chenlongwang.top/Article/details/gtsvkeifjc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gaohongyu789.top/Article/details/gtznfmuaxk.html

C#:   if (x is null) {}
来源：http://dali.gzhubu.top/Article/details/gtacplolzz.html

[P07] 防抖与节流
来源：http://dali.guannengcc.top/Article/details/gtlxjcishp.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ppjwa.cn/Article/details/gtscwedrec.html

PHP:  // 手写时间戳比较
来源：http://dali.hnqzz.top/Article/details/gtvikcvijj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.316326.xyz/Article/details/gtowiwvpck.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fzhhl.top/Article/details/gtobuaqoov.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yanxiufei.cn/Article/details/gtkrqixbyp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.snrcjt.cn/Article/details/gtrxukpblk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yongpay.top/Article/details/gtxebvxgmp.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.svipenyu.cn/Article/details/gtafiwwcws.html

[P08] 处理浮点精度问题
来源：http://dali.cashguo.top/Article/details/gtsbnfhnuq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hongshengwenyu.top/Article/details/gtgcjlotlt.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.vqdsnc.cn/Article/details/gtlmofkipy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.nanxinkj.top/Article/details/gtvnvduxrd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jqgfzy.top/Article/details/gtasmbqaju.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinghuilouyu.cn/Article/details/gthdltqvrd.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinghuilouyu.cn/Article/details/gtlvooosfh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinghuilouyu.cn/Article/details/gtclrtxrlj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.iojbl.cn/Article/details/gtzifcubgr.html


<!-- 参考信息 -->