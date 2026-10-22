代发 wailian999

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cashguo.top/Article/details/gtuumcysft.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ybcxt.top/Article/details/gtsweevudz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxinkj.top/Article/details/gtujnfutxh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zdqjudy.top/Article/details/gtwyxckbez.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.guowangkeji.top/Article/details/gtxayierhk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqzjrdfir.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gzhubu.top/Article/details/gtnoksadnu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.c1oappe.top/Article/details/gtdmrjyiej.html

[M04] 获取当前工作目录
来源：http://dali.vqdsnc.cn/Article/details/gtukxqmspo.html

Py:   os.getcwd()
来源：http://dali.snrcjt.cn/Article/details/gtixgawdxu.html

PHP:  getcwd();
来源：http://dali.9152youxi.cn/Article/details/gtfmsbskxn.html

JS:   process.cwd()
来源：http://dali.nanxinkj.top/Article/details/gtolybqglv.html

TS:   process.cwd()
来源：http://dali.hongshengwenyu.top/Article/details/gtmkmidnqr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sxryk.cn/Article/details/gtcinpkvku.html

Go:   os.Getwd()
来源：http://dali.shuidangran.top/Article/details/gtpkusvlxe.html

Ruby: Dir.pwd
来源：http://dali.sxryk.cn/Article/details/gtnyjdiapq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ppjwa.cn/Article/details/gtcmjkyjkd.html

[M05] 设置退出码
来源：http://dali.yonumen.top/Article/details/gtzfslttsl.html

Py:   sys.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtjskgbkkm.html

PHP:  exit(1);
来源：http://dali.xinyue.icu/Article/details/gtkrutaevc.html

JS:   process.exit(1)
来源：http://dali.shuidangran.top/Article/details/gtfqmemcmj.html

TS:   process.exit(1)
来源：http://dali.daria6918.cn/Article/details/gtaokyclte.html

Java: System.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtdgxtwbmq.html

Go:   os.Exit(1)
来源：http://dali.xuanzx.com/Article/details/gtshxgxant.html

Ruby: exit 1
来源：http://dali.dianchejie.cn/Article/details/gtypdldthg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cheryme.top/Article/details/gtrilxbgvl.html

[M06] 向标准错误输出
来源：http://dali.hywenlv.cn/Article/details/gtwshrcnia.html

Py:   print("err", file=sys.stderr)
来源：http://dali.nwbrower.top/Article/details/gtzequihkx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.c1oappe.top/Article/details/gtlbildfnq.html

JS:   console.error("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthkshqupz.html

TS:   console.error("err")
来源：http://dali.daxiang520.top/Article/details/gtauhgpxdu.html

Java: System.err.println("err")
来源：http://dali.yuanzhike.top/Article/details/gtbaspklom.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.tanke756.top/Article/details/gtvzpqrlek.html

Ruby: warn "err"
来源：http://dali.cheryme.top/Article/details/gtoyupfqwk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.bjfxy.top/Article/details/gtavettpqa.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gtcrtauscv.html

Py:   if __name__ == "__main__":
来源：http://dali.ehwqpu.com/Article/details/gtfnrxtaas.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.quarkkingdee.top/Article/details/gtqtjzxobu.html

JS:   require.main === module
来源：http://dali.ehwqpu.com/Article/details/gtfqtjrdmv.html

TS:   require.main === module
来源：http://dali.jqgufenzy.top/Article/details/gtdsrnfkfp.html

Java: public static void main(String[] args)
来源：http://dali.hammf.cn/Article/details/gtclcpnqen.html

Go:   func main()
来源：http://dali.xuanzx.com/Article/details/gtnpgusopn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.andypj.xyz/Article/details/gteukkubtx.html

C#:   static void Main(string[] args)
来源：http://dali.tanke756.top/Article/details/gtbukajcgd.html

[M08] 获取系统与运行时信息
来源：http://dali.fengsongda.top/Article/details/gtheoarduz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xziqi.cn/Article/details/gtmdmirzlk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.birdmap.top/Article/details/gtabpcxooc.html

JS:   process.platform;  process.version
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxzgnxawe.html

TS:   process.platform;  process.version
来源：http://dali.sysykeji.top/Article/details/gtkdjwcksk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhoulong.xyz/Article/details/gttawcjzpr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shangyingyoupin.top/Article/details/gteaquhehz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.tanke756.top/Article/details/gtrfmxbigy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyoncvtwo.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtwnwffpac.html

N. 数据结构与算法
来源：http://dali.yangfankeji.com/Article/details/gtnyxonyxx.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtkoqqgxle.html

[N01] 二分查找（有序数组）
来源：http://dali.yj20258888.top/Article/details/gtfpkmgtyb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yonumen.top/Article/details/gtkqhvsxfq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.9152youxi.cn/Article/details/gtmfrhnlng.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sweek.top/Article/details/gtmdointue.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sufxvd.cn/Article/details/gtenkqekqx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.birdmap.top/Article/details/gtvpizfdbc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtdwsmqnbs.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.dashuyun.cn/Article/details/gtjolnzart.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gttdxxyhhv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.fengsongda.top/Article/details/gtfbpvmdtn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zycfv.cn/Article/details/gtcqsyavlz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yj20258888.top/Article/details/gtakftgnfz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gzhubu.top/Article/details/gtvhqzgefn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jqgufenzy.top/Article/details/gtfakvkgec.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jlsjyb.cn/Article/details/gtfzfzmapp.html

Go:   slices.Sort(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtepianjyy.html

Ruby: arr.sort
来源：http://dali.zhiwuduotai.top/Article/details/gtlthvjhpl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.aizwys.cn/Article/details/gtxajeqwmx.html

[N03] 快速排序（分治示例）
来源：http://dali.xuetiantiany.cn/Article/details/gtompbbwmh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gtvhwgqrfe.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tianlin.xyz/Article/details/gttrpgsmdo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.smart0.xyz/Article/details/gtbkhkgsfs.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigfzy.top/Article/details/gtytdvyswj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.fzhhl.top/Article/details/gtbxkgmpgl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cheryme.top/Article/details/gtftmjcjdu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhoulong.xyz/Article/details/gtpzdptppl.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gogol.net.cn/Article/details/gtqikhycah.html

[N04] 斐波那契数列
来源：http://dali.cashguo.top/Article/details/gtzdjbqkft.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hysaishi.cn/Article/details/gtxyvqbfbx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.0kj1m.cn/Article/details/gtjnawsexy.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenzaomai.com/Article/details/gtssmyskpp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hfpthk.cn/Article/details/gtfbwchstw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shangyingyoupin.top/Article/details/gtusydrzod.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrdyjgzqb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hnqzz.top/Article/details/gtidwdzaki.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj20258.top/Article/details/gtyrfchixp.html

[N05] 最大公约数
来源：http://dali.meibo888.top/Article/details/gtxbbudbiy.html

Py:   math.gcd(a, b)
来源：http://dali.tian-w.cn/Article/details/gtznigaksf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.nanxuanxn.top/Article/details/gtilzpmfjk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtobeoehqu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtyzdfysdw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.smart0.xyz/Article/details/gtmmcfcgak.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.daxiang520.top/Article/details/gtixqyxgdr.html

Ruby: a.gcd(b)
来源：http://dali.0kj1m.cn/Article/details/gthjaicapc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hammf.cn/Article/details/gtrgeroaqg.html

[N06] 判断回文字符串
来源：http://dali.pycfn.com/Article/details/gtrcntuovg.html

Py:   s == s[::-1]
来源：http://dali.ppjwa.cn/Article/details/gtunpvshsi.html

PHP:  $s === strrev($s);
来源：http://dali.tianlin.xyz/Article/details/gtpwtsukey.html

JS:   s === [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gtchkyhxji.html

TS:   s === [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gtreigkmmj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinqigufen.top/Article/details/gtydswvyit.html

Go:   // 双指针从两端比较
来源：http://dali.zhengqikj.top/Article/details/gtniwusrsx.html

Ruby: s == s.reverse
来源：http://dali.hnxiangtu.top/Article/details/gtrjkkxsmu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zdqjudy.top/Article/details/gtgnhimdbx.html

[N07] 两数之和（返回下标）
来源：http://dali.shangyingyoupin.top/Article/details/gtqhntwznv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sufxvd.cn/Article/details/gtrlqgxebd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gtumyhznjl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cheryme.top/Article/details/gtbfnlyltj.html

TS:   // 手写 Map<string, number>
来源：http://dali.kuanghao11.cn/Article/details/gtulhjmosv.html

Java: // 手写 HashMap
来源：http://dali.tianlin.xyz/Article/details/gtbanxyqcb.html

Go:   // 手写 map[int]int
来源：http://dali.cucudq.cn/Article/details/gteaiwnmrg.html

Ruby: // 手写 Hash
来源：http://dali.yuanzhike.top/Article/details/gtopftqmib.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.bjfxy.top/Article/details/gtcefixlko.html

[N08] 生成全排列
来源：http://dali.nanxinkj.top/Article/details/gtsxktqlvp.html

Py:   itertools.permutations(arr)
来源：http://dali.chenlongwang.top/Article/details/gtskuewolx.html

PHP:  // 手写递归交换
来源：http://dali.wangdashe.top/Article/details/gthymohouc.html

JS:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gtwdygirzm.html

TS:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gtfzwduodd.html

Java: // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gtxdrkjqtc.html

Go:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gtyrcnjadt.html

Ruby: arr.permutation.to_a
来源：http://dali.feifeiyinyue.top/Article/details/gtdjrwchte.html

C#:   // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gtrpfhhzut.html

[N09] 栈与队列
来源：http://dali.birdmap.top/Article/details/gteguhvvgq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gzhubu.top/Article/details/gtoaqclutk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.snrcjt.cn/Article/details/gtuqsimief.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.andypj.xyz/Article/details/gtpxjfwyks.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhengqikj.top/Article/details/gtavaholuo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jqgfzy.top/Article/details/gtijuriggc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.daxiang520.top/Article/details/gtmydmkvul.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yonumen.top/Article/details/gtpfhzzqri.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cqqwz.cn/Article/details/gtlwbxkjef.html

[N10] 链表节点定义
来源：http://dali.hnqzz.top/Article/details/gtxzcpncyq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cashguo.top/Article/details/gthxopnamj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sysykeji.top/Article/details/gtyvacvqmp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhongyouzk.top/Article/details/gtkoekobyg.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yuanzhike.top/Article/details/gtzjubfpxz.html

Java: class Node { int v; Node next; }
来源：http://dali.cucudq.cn/Article/details/gtdlebzste.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yueranfly.top/Article/details/gtquooeyss.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtekkwdftc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shzxlz.cn/Article/details/gtgfbwnsqs.html

[N11] 二叉树中序遍历
来源：http://dali.xuanzx.com/Article/details/gttjosbqgv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinqigfzy.top/Article/details/gtyhihqeny.html

PHP:  // 手写递归函数
来源：http://dali.zhongyouzk.top/Article/details/gthekxbxtk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuxming.cn/Article/details/gtyatbpdkd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shangyingyoupin.top/Article/details/gtsdswzzem.html

Java: // 手写递归
来源：http://dali.yj20258888.top/Article/details/gtmmyppetr.html

Go:   // 手写递归
来源：http://dali.tanke756.top/Article/details/gtiodvxybt.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinqigfzy.top/Article/details/gtgbsjeycf.html

C#:   // 手写递归
来源：http://dali.redwolf501.top/Article/details/gtxuqazmio.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shanyushiyangkeji.top/Article/details/gthiwzbbyg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.svipenyu.cn/Article/details/gtflswntas.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xuetiantiany.cn/Article/details/gteerkhitw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.0kj1m.cn/Article/details/gtabzfvehi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hongshengwenyu.top/Article/details/gtjhcmvkcj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwgoxfwcr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xinyue.icu/Article/details/gtbghvecbc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yuanzhike.top/Article/details/gtsafonlqn.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cqqwz.cn/Article/details/gtguceefdx.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtmyadzpan.html

O. 并发与异步
来源：http://dali.guannengcc.top/Article/details/gthphhkjjm.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtvaawyyrl.html

[O01] 启动一个线程
来源：http://dali.yj20258888.top/Article/details/gttucjmrca.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.snrcjt.cn/Article/details/gtqepzvswj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtahpivpkv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.9152youxi.cn/Article/details/gtrnqvmosf.html

TS:   // 同 JS
来源：http://dali.shangyingyoupin.top/Article/details/gtobhylfys.html

Java: new Thread(() -> f()).start()
来源：http://dali.smart0.xyz/Article/details/gtfvrcnutz.html

Go:   go f()
来源：http://dali.yueranfly.top/Article/details/gtdgjxufap.html

Ruby: Thread.new { f }
来源：http://dali.bjfxy.top/Article/details/gtagpaaqcm.html

C#:   Task.Run(() => F());
来源：http://dali.cucudq.cn/Article/details/gtkcwkksgs.html

[O02] 使用线程池
来源：http://dali.hnqzz.top/Article/details/gtxdgnfmkg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.fzhhl.top/Article/details/gtqcmuxlgf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.havefunace.top/Article/details/gtzztyitio.html

JS:   // worker_threads 线程池
来源：http://dali.gzhubu.top/Article/details/gtvdwesnok.html

TS:   // worker_threads 线程池
来源：http://dali.jinghuilouyu.cn/Article/details/gtuyodlepw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xuetiantiany.cn/Article/details/gtffaktdbc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.smart0.xyz/Article/details/gtlhamavxf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.aibaodan.cn/Article/details/gtxqyytvxr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ydzc1.top/Article/details/gthbysnuem.html

[O03] 加锁保护共享数据
来源：http://dali.wangshuangyany.cn/Article/details/gtxumbedzn.html

Py:   with lock: shared += 1
来源：http://dali.hfpthk.cn/Article/details/gtpxnlktvv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.chenzaomai.com/Article/details/gtesjtehxq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ybcxt.top/Article/details/gtggjxcgbd.html

TS:   // 同 JS
来源：http://dali.andypj.xyz/Article/details/gtcqnidaxd.html

Java: synchronized (this) { shared++; }
来源：http://dali.nanxinkj.top/Article/details/gtmxicfyqc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.redwolf501.top/Article/details/gtacwbbbip.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xziqi.cn/Article/details/gtunwtwpxe.html

C#:   lock (gate) { shared++; }
来源：http://dali.yonumen.top/Article/details/gtktbmpcma.html

[O04] 定义异步函数并等待
来源：http://dali.0kj1m.cn/Article/details/gtdojlhphz.html

Py:   async def f():⏎    await g()
来源：http://dali.shzxlz.cn/Article/details/gttmdudkgu.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shzxlz.cn/Article/details/gttbumnnad.html

JS:   async function f() { await g(); }
来源：http://dali.yonumen.top/Article/details/gtyozrdehd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.fengsongda.top/Article/details/gtlgrofnul.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yj202588.top/Article/details/gtyxqtwnph.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.guowangkeji.top/Article/details/gtlenaxobt.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gzhubu.top/Article/details/gtyhcwaqta.html

C#:   async Task F() { await G(); }
来源：http://dali.meibo888.top/Article/details/gtmvsvynnw.html

[O05] 并发执行并等待全部完成
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvkmiwmij.html

Py:   asyncio.gather(*tasks)
来源：http://dali.dashuyun.cn/Article/details/gtjigsjzgf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jyoumei.cn/Article/details/gtrdzcytxd.html

JS:   await Promise.all(tasks)
来源：http://dali.ehwqpu.com/Article/details/gtioezqxmw.html

TS:   await Promise.all(tasks)
来源：http://dali.ehwqpu.com/Article/details/gtbvfgtijy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cashguo.top/Article/details/gtaphkxbcn.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhongyouzk.top/Article/details/gtcmsonbha.html

Ruby: threads.map(&:join)
来源：http://dali.andypj.xyz/Article/details/gtycdmwsyj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gtorkcvrxb.html

[O06] 使用进程池
来源：http://dali.ybcxt.top/Article/details/gtlccbygoo.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xziqi.cn/Article/details/gtlfgygbbz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhongyouzk.top/Article/details/gtrqnqhjuy.html

JS:   // child_process / cluster 模块
来源：http://dali.shzxlz.cn/Article/details/gtxoaythjd.html

TS:   // child_process / cluster 模块
来源：http://dali.316326.xyz/Article/details/gtcprhlgot.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yueranfly.top/Article/details/gtgklbjwes.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.birdmap.top/Article/details/gtomzjphho.html

Ruby: // fork 块
来源：http://dali.daria6918.cn/Article/details/gtzhbquojz.html

C#:   Parallel.For
来源：http://dali.tianlin.xyz/Article/details/gtdqpsbjhq.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtvsrxleqg.html

P. 常用工具函数
来源：http://dali.xuetiantiany.cn/Article/details/gtvqnvteyo.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtngpteanz.html

[P01] 生成 UUID
来源：http://dali.zhengqikj.top/Article/details/gtsnhceyad.html

Py:   str(uuid.uuid4())
来源：http://dali.jinghuilouyu.cn/Article/details/gtcgdvgqfq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tanke756.top/Article/details/gtayjcfezz.html

JS:   crypto.randomUUID()
来源：http://dali.jyoumei.cn/Article/details/gtprsfzglr.html

TS:   crypto.randomUUID()
来源：http://dali.pengpengdd.cyou/Article/details/gtcyjzhruz.html

Java: UUID.randomUUID().toString()
来源：http://dali.sufxvd.cn/Article/details/gtvlpchhpr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yongpay.top/Article/details/gtaxxfqvyh.html

Ruby: SecureRandom.uuid
来源：http://dali.daxiang520.top/Article/details/gtkyizvvmk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ppjwa.cn/Article/details/gteorgzjvk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.bjfxy.top/Article/details/gtwefrgmtr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xuanzx.com/Article/details/gtvgiopvxs.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jqgufenzy.top/Article/details/gtvlbyeakk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnionvykw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yvedp.cn/Article/details/gttpgowbkr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.birdmap.top/Article/details/gtwndgdceh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gogol.net.cn/Article/details/gtyqdiwxaq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gzhubu.top/Article/details/gtukguoemv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yj202588.top/Article/details/gtygrizcoz.html

[P03] 生成短随机字符串
来源：http://dali.fzhhl.top/Article/details/gtuyiccwem.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yj20258888.top/Article/details/gtcnjtizfh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.pengpengdd.cyou/Article/details/gtvsobelmh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ivvv.top/Article/details/gtdipljynp.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cheryme.top/Article/details/gtjxgwfrmt.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yongpay.top/Article/details/gtgifjpjvu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.c1oappe.top/Article/details/gtryknauvh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.tianlin.xyz/Article/details/gtragdqbkh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.andypj.xyz/Article/details/gtayntumui.html

[P04] 求长度
来源：http://dali.wangdashe.top/Article/details/gtsxidjzie.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzaugglsa.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gtjxzqvkso.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guannengcc.top/Article/details/gtvlyerzzb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuxming.cn/Article/details/gtxypvqctu.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sufxvd.cn/Article/details/gtjnzxhcyk.html

Go:   len(arr);  len(m)
来源：http://dali.snrcjt.cn/Article/details/gtcnbusfad.html

Ruby: x.length;  x.size
来源：http://dali.wangshuangyany.cn/Article/details/gtomrjsybp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhongyouzk.top/Article/details/gtvuwwwzrl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.daxiang520.top/Article/details/gtqewnlbbc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinqigufen.top/Article/details/gtkawxcect.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jyoumei.cn/Article/details/gtrwnikprq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.aizwys.cn/Article/details/gtpkzitwvy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.aibaodan.cn/Article/details/gtisrxkhjx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ehwqpu.com/Article/details/gtzcxprvda.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yj20258888.top/Article/details/gtlpbpzrhb.html

Ruby: a == b
来源：http://dali.fengsongda.top/Article/details/gtgtvzwmjw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtajmdixsi.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.chenlongwang.top/Article/details/gtoywyvwhb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhoulong.xyz/Article/details/gtirhnsijv.html

PHP:  if (empty($x)) {}
来源：http://dali.zdqjudy.top/Article/details/gtrengksxp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xziqi.cn/Article/details/gtaebllbto.html

TS:   if (x == null) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtgtkejbqv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.sysykeji.top/Article/details/gtgktiwyjg.html

Go:   if x == nil {}
来源：http://dali.zhiwuduotai.top/Article/details/gtkzsjpgog.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.andypj.xyz/Article/details/gtqygimbcl.html

C#:   if (x is null) {}
来源：http://dali.smart0.xyz/Article/details/gtseofzahp.html

[P07] 防抖与节流
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwjvvzebm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.9152youxi.cn/Article/details/gtagbeywbr.html

PHP:  // 手写时间戳比较
来源：http://dali.shangyingyoupin.top/Article/details/gtymxytydi.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgfzy.top/Article/details/gtaisabupe.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigufen.top/Article/details/gtlteiiovw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yvedp.cn/Article/details/gtiskfjnqz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jlsjyb.cn/Article/details/gtfzgukbyj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yongpay.top/Article/details/gtkgclypvd.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.316326.xyz/Article/details/gtambyatkq.html

[P08] 处理浮点精度问题
来源：http://dali.jinqigfzy.top/Article/details/gtxdrsjrck.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhixingplan.top/Article/details/gtroomrbll.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.wangdashe.top/Article/details/gtlxgxumqn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jlsjyb.cn/Article/details/gtipbynagl.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.pengpengdd.cyou/Article/details/gthzfhcgfw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinghuilouyu.cn/Article/details/gtfnnxpqhu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.316326.xyz/Article/details/gtimuvtzee.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.havefunace.top/Article/details/gttxrelmrp.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.pengpengdd.cyou/Article/details/gtjhimmttz.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gthnrwahek.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jqgfzy.top/Article/details/gtffqcpviw.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtpjxcpbec.html

[Q01] 创建表
来源：http://dali.kuanghao11.cn/Article/details/gtvlhnnbjc.html


<!-- 参考信息 -->