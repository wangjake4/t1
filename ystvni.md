代发 wailian999

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gzhubu.top/Article/details/gt2oteaelsw.html

Ruby: ENV["HOME"]
来源：http://dali.sxryk.cn/Article/details/gt2ocmewynt.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.c1oappe.top/Article/details/gt2erfkcido.html

[M03] 执行外部命令
来源：http://dali.zhixingplan.top/Article/details/gt2jjacdhhc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ydzc1.top/Article/details/gt2ymhzznui.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sweek.top/Article/details/gt2dhmqjnax.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gzhubu.top/Article/details/gt2buhivmbk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.pengpengdd.cyou/Article/details/gt2tsnobyvo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.aizwys.cn/Article/details/gt2sdwegcpn.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cheryme.top/Article/details/gt2jyocbdot.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xylfe.cn/Article/details/gt2wmzetuuj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhiwuduotai.top/Article/details/gt2zlsjfptb.html

[M04] 获取当前工作目录
来源：http://dali.fengsongda.top/Article/details/gt2zwibauib.html

Py:   os.getcwd()
来源：http://dali.yj202588.top/Article/details/gt2svwodehd.html

PHP:  getcwd();
来源：http://dali.zhixingplan.top/Article/details/gt2ulukbenw.html

JS:   process.cwd()
来源：http://dali.xinyue.icu/Article/details/gt2ygvgobfp.html

TS:   process.cwd()
来源：http://dali.hnqzz.top/Article/details/gt2nogxlvdh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jianghu66.top/Article/details/gt2cpraspcg.html

Go:   os.Getwd()
来源：http://dali.yonumen.top/Article/details/gt2jzrafqss.html

Ruby: Dir.pwd
来源：http://dali.andypj.xyz/Article/details/gt2kebpfybc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.tanke756.top/Article/details/gt2zqzwycqn.html

[M05] 设置退出码
来源：http://dali.ppjwa.cn/Article/details/gt2awdhfrzz.html

Py:   sys.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gt2isifrqku.html

PHP:  exit(1);
来源：http://dali.chenjidiqi.icu/Article/details/gt2anggaurf.html

JS:   process.exit(1)
来源：http://dali.fzhhl.top/Article/details/gt2cenvqxvr.html

TS:   process.exit(1)
来源：http://dali.tian-w.cn/Article/details/gt2uutmpqsd.html

Java: System.exit(1)
来源：http://dali.yuxming.cn/Article/details/gt2yejkwwko.html

Go:   os.Exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2uhovurmx.html

Ruby: exit 1
来源：http://dali.hysaishi.cn/Article/details/gt2acequcbh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shuidangran.top/Article/details/gt2bzarlqxj.html

[M06] 向标准错误输出
来源：http://dali.ivvv.top/Article/details/gt2rzdlklbs.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cucudq.cn/Article/details/gt2hdubrbga.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhongyouzk.top/Article/details/gt2uidytpij.html

JS:   console.error("err")
来源：http://dali.chenzaomai.com/Article/details/gt2rhfztyww.html

TS:   console.error("err")
来源：http://dali.tian-w.cn/Article/details/gt2notufwdc.html

Java: System.err.println("err")
来源：http://dali.redwolf501.top/Article/details/gt2yqzylkpq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cashguo.top/Article/details/gt2ixbqhtmi.html

Ruby: warn "err"
来源：http://dali.pycfn.com/Article/details/gt2mmiwecvt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinqigfzy.top/Article/details/gt2qlfwqyig.html

[M07] 判断是否为主入口
来源：http://dali.jinqigfzy.top/Article/details/gt2drfwmxsq.html

Py:   if __name__ == "__main__":
来源：http://dali.yanxiufei.cn/Article/details/gt2drpqrcsl.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sysykeji.top/Article/details/gt2ygyremye.html

JS:   require.main === module
来源：http://dali.guannengcc.top/Article/details/gt2jpusmoly.html

TS:   require.main === module
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hqpnvpvl.html

Java: public static void main(String[] args)
来源：http://dali.gaohongyu789.top/Article/details/gt2utoxwhxr.html

Go:   func main()
来源：http://dali.xziqi.cn/Article/details/gt2twaruxjm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yuanzhike.top/Article/details/gt2puwfkqwu.html

C#:   static void Main(string[] args)
来源：http://dali.shzxlz.cn/Article/details/gt2lqffzahj.html

[M08] 获取系统与运行时信息
来源：http://dali.nwbrower.top/Article/details/gt2dyinmovv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hysaishi.cn/Article/details/gt2toswjjbm.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gaohongyu789.top/Article/details/gt2xwcmssqn.html

JS:   process.platform;  process.version
来源：http://dali.nanxuanxn.top/Article/details/gt2krklvwhc.html

TS:   process.platform;  process.version
来源：http://dali.0kj1m.cn/Article/details/gt2fmirsrby.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shzxlz.cn/Article/details/gt2bvpbtnge.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hfpthk.cn/Article/details/gt2jmxxwzlp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.wangshuangyany.cn/Article/details/gt2ieqpueze.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.guowangkeji.top/Article/details/gt2wmlwfclt.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ucjmakzr.html

N. 数据结构与算法
来源：http://dali.quarkkingdee.top/Article/details/gt2tuzggtqm.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2uevvpxlf.html

[N01] 二分查找（有序数组）
来源：http://dali.zhoulong.xyz/Article/details/gt2axwmfgvo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.smart0.xyz/Article/details/gt2atfhciud.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhongyouzk.top/Article/details/gt2gedzlcqt.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tianlin.xyz/Article/details/gt2qelmympf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxuanxn.top/Article/details/gt2ywmqqwbv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mnrmtoqs.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fwlciyuj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hnxiangtu.top/Article/details/gt2khgxzved.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.wangdashe.top/Article/details/gt2zviqogxf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shangyingyoupin.top/Article/details/gt2odwrwtrn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.bjfxy.top/Article/details/gt2mcqzduvr.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.tian-w.cn/Article/details/gt2mgpjsskp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhongyouzk.top/Article/details/gt2pkttggyz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhixingplan.top/Article/details/gt2tckejbex.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.bjfxy.top/Article/details/gt2tzfzxjiv.html

Go:   slices.Sort(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2bhwlwqmi.html

Ruby: arr.sort
来源：http://dali.zhixingplan.top/Article/details/gt2gwndwfgc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nwbrower.top/Article/details/gt2rjskuwod.html

[N03] 快速排序（分治示例）
来源：http://dali.pycfn.com/Article/details/gt2sbaovfnz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xuanzx.com/Article/details/gt2rumslglp.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yj20258888.top/Article/details/gt2egfxhhpu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigfzy.top/Article/details/gt2kypnjnyw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258.top/Article/details/gt2rjvotaxy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sysykeji.top/Article/details/gt2jistohqo.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yangfankeji.com/Article/details/gt2qcuetrpq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xuetiantiany.cn/Article/details/gt2qjggowbh.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jiagoushi.top/Article/details/gt2mulxloke.html

[N04] 斐波那契数列
来源：http://dali.daxiang520.top/Article/details/gt2qzubtcgj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shuidangran.top/Article/details/gt2rmmzztlc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hfpthk.cn/Article/details/gt2mdbvgplz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ylepxofy.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gotoacloud.top/Article/details/gt2izemiqae.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinqigfzy.top/Article/details/gt2dynkxfuv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ppjwa.cn/Article/details/gt2uemnwjlr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.pycfn.com/Article/details/gt2aslvsewe.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cashguo.top/Article/details/gt2iluuwdjs.html

[N05] 最大公约数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dxljioyq.html

Py:   math.gcd(a, b)
来源：http://dali.daria6918.cn/Article/details/gt2luowfzqm.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jqgufenzy.top/Article/details/gt2hwtqkgjz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2cafczblw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.birdmap.top/Article/details/gt2otalhvxc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xuanzx.com/Article/details/gt2olxzlrjw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.c1oappe.top/Article/details/gt2tiqtkhbr.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgesnhun.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2nuuuluuy.html

[N06] 判断回文字符串
来源：http://dali.chenlongwang.top/Article/details/gt2rwfgjcur.html

Py:   s == s[::-1]
来源：http://dali.daxiang520.top/Article/details/gt2sysdtygk.html

PHP:  $s === strrev($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wnslezyu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gt2nrdkmgqu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gt2ncjkujgq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jianghu66.top/Article/details/gt2lggmavgj.html

Go:   // 双指针从两端比较
来源：http://dali.yvedp.cn/Article/details/gt2kgqhyshp.html

Ruby: s == s.reverse
来源：http://dali.sufxvd.cn/Article/details/gt2xwfthbpj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.daxiang520.top/Article/details/gt2hlqwvpnk.html

[N07] 两数之和（返回下标）
来源：http://dali.quarkkingdee.top/Article/details/gt2vwlvkqrr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ydzc1.top/Article/details/gt2ectnfhtq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yueranfly.top/Article/details/gt2ocrxploy.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.dianchejie.cn/Article/details/gt2pzeptikv.html

TS:   // 手写 Map<string, number>
来源：http://dali.hfpthk.cn/Article/details/gt2bbuutits.html

Java: // 手写 HashMap
来源：http://dali.9152youxi.cn/Article/details/gt2mhpguxch.html

Go:   // 手写 map[int]int
来源：http://dali.nanxuanxn.top/Article/details/gt2hxycxsma.html

Ruby: // 手写 Hash
来源：http://dali.haohaochexian.top/Article/details/gt2rubemmee.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ivvv.top/Article/details/gt2dejootht.html

[N08] 生成全排列
来源：http://dali.ppjwa.cn/Article/details/gt2seuzcpon.html

Py:   itertools.permutations(arr)
来源：http://dali.ivvv.top/Article/details/gt2rjdjezbx.html

PHP:  // 手写递归交换
来源：http://dali.jqgufenzy.top/Article/details/gt2yklekfeu.html

JS:   // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gt2lsdbjmpt.html

TS:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gt2hsftykir.html

Java: // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gt2cbgipcyi.html

Go:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mcoefcgb.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2ufulgvgv.html

C#:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gt2pchnjkud.html

[N09] 栈与队列
来源：http://dali.dianchejie.cn/Article/details/gt2jkdekxpu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.aibaodan.cn/Article/details/gt2bycglyag.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hfpthk.cn/Article/details/gt2iqbwsqoo.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hywenlv.cn/Article/details/gt2bakahgvv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yuanzhike.top/Article/details/gt2oyxgddmg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xinyue.icu/Article/details/gt2veztkmcr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gogol.net.cn/Article/details/gt2zkzhksnj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gt2xrgrpeob.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jyoumei.cn/Article/details/gt2hwhbiuic.html

[N10] 链表节点定义
来源：http://dali.vqdsnc.cn/Article/details/gt2nuajlyve.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.chenlongwang.top/Article/details/gt2jkrfmlgm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.nanxuanxn.top/Article/details/gt2sfxdaylh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xuetiantiany.cn/Article/details/gt2hshehvkj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ylpmtfiw.html

Java: class Node { int v; Node next; }
来源：http://dali.daxiang520.top/Article/details/gt2vdekclne.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinqigufen.top/Article/details/gt2mggbzulw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hnqzz.top/Article/details/gt2uiviswgo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.pycfn.com/Article/details/gt2jjkcwajl.html

[N11] 二叉树中序遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gt2chzvjopn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.guowangkeji.top/Article/details/gt2nmpmmput.html

PHP:  // 手写递归函数
来源：http://dali.sufxvd.cn/Article/details/gt2anunyspm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhongyouzk.top/Article/details/gt2lrxfrrqo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hfpthk.cn/Article/details/gt2zzehgbsj.html

Java: // 手写递归
来源：http://dali.yj202588.top/Article/details/gt2gnaccixq.html

Go:   // 手写递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ivqydgdv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xinyue.icu/Article/details/gt2ohmdlcni.html

C#:   // 手写递归
来源：http://dali.zhongyouzk.top/Article/details/gt2wabqvehi.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yangfankeji.com/Article/details/gt2hueaxhai.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hammf.cn/Article/details/gt2bniakguf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.sufxvd.cn/Article/details/gt2stuapcfj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yvedp.cn/Article/details/gt2ottmblmq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.redwolf501.top/Article/details/gt2ieosycyo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hywenlv.cn/Article/details/gt2pcczkfyw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ybcxt.top/Article/details/gt2arxoohzl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ytckminu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.kuanghao11.cn/Article/details/gt2rowlpjfz.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2cgvwuzre.html

O. 并发与异步
来源：http://dali.zhongyouzk.top/Article/details/gt2xcbghfry.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2aqhpglla.html

[O01] 启动一个线程
来源：http://dali.hysaishi.cn/Article/details/gt2wvtpqgwv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yangfankeji.com/Article/details/gt2gynfojfh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.tianlin.xyz/Article/details/gt2uosyygmz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cqqwz.cn/Article/details/gt2psmxqbhp.html

TS:   // 同 JS
来源：http://dali.fzhhl.top/Article/details/gt2roxxzzpy.html

Java: new Thread(() -> f()).start()
来源：http://dali.tanke756.top/Article/details/gt2yndpzqzq.html

Go:   go f()
来源：http://dali.yangfankeji.com/Article/details/gt2sczwoixp.html

Ruby: Thread.new { f }
来源：http://dali.jiagoushi.top/Article/details/gt2fddnbooa.html

C#:   Task.Run(() => F());
来源：http://dali.hywenlv.cn/Article/details/gt2gezxowik.html

[O02] 使用线程池
来源：http://dali.aibaodan.cn/Article/details/gt2ikpcnajp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.iojbl.cn/Article/details/gt2diloxyyl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ivvv.top/Article/details/gt2fwacnedc.html

JS:   // worker_threads 线程池
来源：http://dali.yanxiufei.cn/Article/details/gt2euqhgzwi.html

TS:   // worker_threads 线程池
来源：http://dali.xuanzx.com/Article/details/gt2tutddnbb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.daxiang520.top/Article/details/gt2zwsaujcb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fulcscbg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ivvv.top/Article/details/gt2typwmpui.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.0kj1m.cn/Article/details/gt2ozliizvb.html

[O03] 加锁保护共享数据
来源：http://dali.andypj.xyz/Article/details/gt2xvdggmob.html

Py:   with lock: shared += 1
来源：http://dali.snrcjt.cn/Article/details/gt2ijjiwjfi.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.feifeiyinyue.top/Article/details/gt2lqynzxvi.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhiwuduotai.top/Article/details/gt2qmthimdw.html

TS:   // 同 JS
来源：http://dali.pengpengdd.cyou/Article/details/gt2zyxpekha.html

Java: synchronized (this) { shared++; }
来源：http://dali.iojbl.cn/Article/details/gt2jvxhdrbg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yqgxfnkq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hnqzz.top/Article/details/gt2pruqrovt.html

C#:   lock (gate) { shared++; }
来源：http://dali.quarkkingdee.top/Article/details/gt2zzyictnz.html

[O04] 定义异步函数并等待
来源：http://dali.havefunace.top/Article/details/gt2ibjcqlxg.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrhlmdr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinqigfzy.top/Article/details/gt2bvlzfbyl.html

JS:   async function f() { await g(); }
来源：http://dali.sweek.top/Article/details/gt2guvosqdc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sqdjjbee.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.chenjidiqi.icu/Article/details/gt2rmbrofpc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xziqi.cn/Article/details/gt2hdonmzle.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.wangdashe.top/Article/details/gt2uwlmrxeq.html

C#:   async Task F() { await G(); }
来源：http://dali.cdnleiting.top/Article/details/gt2gqsdqjsi.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhoulong.xyz/Article/details/gt2dbxbxlob.html

Py:   asyncio.gather(*tasks)
来源：http://dali.tanke756.top/Article/details/gt2pimsmyqn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cheryme.top/Article/details/gt2qhyznudi.html

JS:   await Promise.all(tasks)
来源：http://dali.dianchejie.cn/Article/details/gt2pyyuycaf.html

TS:   await Promise.all(tasks)
来源：http://dali.pengpengdd.cyou/Article/details/gt2epwblkqe.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yvedp.cn/Article/details/gt2fkqgikqc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ivvv.top/Article/details/gt2qyjuoaqg.html

Ruby: threads.map(&:join)
来源：http://dali.hnxiangtu.top/Article/details/gt2kggtckyq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yangfankeji.com/Article/details/gt2zmpljouq.html

[O06] 使用进程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ovgcgewk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xinyue.icu/Article/details/gt2cjonpezo.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jlsjyb.cn/Article/details/gt2qouczbdi.html

JS:   // child_process / cluster 模块
来源：http://dali.ehwqpu.com/Article/details/gt2wizhxvej.html

TS:   // child_process / cluster 模块
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zzsgcged.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.kuanghao11.cn/Article/details/gt2irfelsws.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.0kj1m.cn/Article/details/gt2lstphgcy.html

Ruby: // fork 块
来源：http://dali.yonumen.top/Article/details/gt2hqvuqdzv.html

C#:   Parallel.For
来源：http://dali.dianchejie.cn/Article/details/gt2vgouwvev.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2failnjjy.html

P. 常用工具函数
来源：http://dali.svipenyu.cn/Article/details/gt2kusjjqez.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2xxrxpkla.html

[P01] 生成 UUID
来源：http://dali.mhx1999.top/Article/details/gt2jndaddxn.html

Py:   str(uuid.uuid4())
来源：http://dali.c1oappe.top/Article/details/gt2gjikvrbc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hnxiangtu.top/Article/details/gt2ldqawxsy.html

JS:   crypto.randomUUID()
来源：http://dali.snrcjt.cn/Article/details/gt2irtpzmww.html

TS:   crypto.randomUUID()
来源：http://dali.tianlin.xyz/Article/details/gt2dkpimwdl.html

Java: UUID.randomUUID().toString()
来源：http://dali.dashuyun.cn/Article/details/gt2iyoqoowv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ivvv.top/Article/details/gt2nvakylbr.html

Ruby: SecureRandom.uuid
来源：http://dali.zhiwuduotai.top/Article/details/gt2gxvyeqhw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hnxiangtu.top/Article/details/gt2enyxyagu.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cheryme.top/Article/details/gt2vkccnwdk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.fengsongda.top/Article/details/gt2iyvmedgr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hfpthk.cn/Article/details/gt2prwiryrt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hammf.cn/Article/details/gt2pzpsffvu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yuanzhike.top/Article/details/gt2dixfitbc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.pycfn.com/Article/details/gt2rawjtefu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.kuanghao11.cn/Article/details/gt2ebqrfewn.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mydsphsg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gotoacloud.top/Article/details/gt2jzkqugat.html

[P03] 生成短随机字符串
来源：http://dali.dianchejie.cn/Article/details/gt2rhwdpqkn.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.tianlin.xyz/Article/details/gt2dsckjulx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cucudq.cn/Article/details/gt2sfibhxsx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hammf.cn/Article/details/gt2hinokteq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tianlin.xyz/Article/details/gt2npzsasyf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.daxiang520.top/Article/details/gt2mipwufsk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ehwqpu.com/Article/details/gt2btjgcaax.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.iojbl.cn/Article/details/gt2rrzqznhr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ydzc1.top/Article/details/gt2bumwatpm.html

[P04] 求长度
来源：http://dali.bjfxy.top/Article/details/gt2mfrtthjw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tanke756.top/Article/details/gt2gnjjhxyr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhiwuduotai.top/Article/details/gt2lzrtwckh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.c1oappe.top/Article/details/gt2wfzmeonl.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zdqjudy.top/Article/details/gt2eopzcuhi.html

Java: list.size();  map.size();  s.length()
来源：http://dali.daria6918.cn/Article/details/gt2uknqqhln.html

Go:   len(arr);  len(m)
来源：http://dali.wangshuangyany.cn/Article/details/gt2lbhnmsbk.html

Ruby: x.length;  x.size
来源：http://dali.chenzaomai.com/Article/details/gt2xksaaooa.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sweek.top/Article/details/gt2jmaaqbmg.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zdqjudy.top/Article/details/gt2ydfzidek.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.guannengcc.top/Article/details/gt2evcbewqe.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.mhx1999.top/Article/details/gt2fyzxcmqo.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xziqi.cn/Article/details/gt2yvddtizv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhongyouzk.top/Article/details/gt2tmlcxjeq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hysaishi.cn/Article/details/gt2xobgagqt.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hfpthk.cn/Article/details/gt2tmhirmml.html

Ruby: a == b
来源：http://dali.c1oappe.top/Article/details/gt2zozidkwe.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jqgufenzy.top/Article/details/gt2dwtwrxkp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gaohongyu789.top/Article/details/gt2srqrtzte.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.dashuyun.cn/Article/details/gt2ssfvqrsh.html

PHP:  if (empty($x)) {}
来源：http://dali.c1oappe.top/Article/details/gt2ztklqslt.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.sysykeji.top/Article/details/gt2kfuuqhlq.html

TS:   if (x == null) {}
来源：http://dali.hywenlv.cn/Article/details/gt2thibizqd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinqigufen.top/Article/details/gt2ghduopdj.html

Go:   if x == nil {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qmvkiihy.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.kuanghao11.cn/Article/details/gt2elidcdml.html

C#:   if (x is null) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2dqmreezk.html

[P07] 防抖与节流
来源：http://dali.cucudq.cn/Article/details/gt2vqtshzhz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shangyingyoupin.top/Article/details/gt2zaqwuzvd.html

PHP:  // 手写时间戳比较
来源：http://dali.zhengqikj.top/Article/details/gt2embyfdzz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258888.top/Article/details/gt2qdbxhoxs.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sweek.top/Article/details/gt2rulzkhbd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.daria6918.cn/Article/details/gt2gyrejvjr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yj20258.top/Article/details/gt2kunxfmgn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.sufxvd.cn/Article/details/gt2rjmjzfkt.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ydzc1.top/Article/details/gt2siymicyt.html

[P08] 处理浮点精度问题
来源：http://dali.jqgufenzy.top/Article/details/gt2tgptauhj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.tian-w.cn/Article/details/gt2qgmunwbg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zdqjudy.top/Article/details/gt2gzvhpgzb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.dashuyun.cn/Article/details/gt2edhmlxyj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hysaishi.cn/Article/details/gt2pkkzdjzc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xinyue.icu/Article/details/gt2nlkoqjwi.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yangfankeji.com/Article/details/gt2xomrksix.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.feifeiyinyue.top/Article/details/gt2pdajbwkw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cdnleiting.top/Article/details/gt2nchhssod.html


<!-- 参考信息 -->