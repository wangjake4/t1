代发 wailian999

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj20258.top/Article/details/gtooezesmj.html

Ruby: ENV["HOME"]
来源：http://dali.xinyue.icu/Article/details/gtozmuyosd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gtoilcxpsu.html

[M03] 执行外部命令
来源：http://dali.cucudq.cn/Article/details/gtoiymnbmf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cheryme.top/Article/details/gtvqerszof.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sweek.top/Article/details/gtxwwmkhqe.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jlsjyb.cn/Article/details/gtgdlcoayv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tian-w.cn/Article/details/gtopnkpovi.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhongyouzk.top/Article/details/gtnxmwvxug.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnaaqtdoa.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.meibo888.top/Article/details/gtjnaaxjfo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ydzc1.top/Article/details/gtgzxpudqe.html

[M04] 获取当前工作目录
来源：http://dali.zhengqikj.top/Article/details/gtzlmiilvi.html

Py:   os.getcwd()
来源：http://dali.zdqjudy.top/Article/details/gtulgjbmhr.html

PHP:  getcwd();
来源：http://dali.daxiang520.top/Article/details/gtjnambvwy.html

JS:   process.cwd()
来源：http://dali.zycfv.cn/Article/details/gtppcaumrh.html

TS:   process.cwd()
来源：http://dali.svipenyu.cn/Article/details/gteoyvyocj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sxryk.cn/Article/details/gtxgadzets.html

Go:   os.Getwd()
来源：http://dali.yonumen.top/Article/details/gtjflsweae.html

Ruby: Dir.pwd
来源：http://dali.ehwqpu.com/Article/details/gtvselgvdk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.vqdsnc.cn/Article/details/gtthpyyyml.html

[M05] 设置退出码
来源：http://dali.andypj.xyz/Article/details/gtyyxwpkhv.html

Py:   sys.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtpzetqpca.html

PHP:  exit(1);
来源：http://dali.shangyingyoupin.top/Article/details/gtybmlucri.html

JS:   process.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtuxxpkmsa.html

TS:   process.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gtxkqhdeoz.html

Java: System.exit(1)
来源：http://dali.sweek.top/Article/details/gtsfnudela.html

Go:   os.Exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtawidgkjy.html

Ruby: exit 1
来源：http://dali.gotoacloud.top/Article/details/gtwizhottt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.dashuyun.cn/Article/details/gtiqmzfhyc.html

[M06] 向标准错误输出
来源：http://dali.cashguo.top/Article/details/gtvtmqisly.html

Py:   print("err", file=sys.stderr)
来源：http://dali.snrcjt.cn/Article/details/gtgthktozq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shangyingyoupin.top/Article/details/gtkcqwlfzs.html

JS:   console.error("err")
来源：http://dali.jyoumei.cn/Article/details/gtlflobihc.html

TS:   console.error("err")
来源：http://dali.daxiang520.top/Article/details/gtzzugsavk.html

Java: System.err.println("err")
来源：http://dali.jqgufenzy.top/Article/details/gtfyvfstut.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jqgfzy.top/Article/details/gtohbjulul.html

Ruby: warn "err"
来源：http://dali.zdqjudy.top/Article/details/gtdieiidcj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cucudq.cn/Article/details/gtciheekwg.html

[M07] 判断是否为主入口
来源：http://dali.yonumen.top/Article/details/gtbztxycsr.html

Py:   if __name__ == "__main__":
来源：http://dali.pycfn.com/Article/details/gttiwjgakk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xinyue.icu/Article/details/gtjmvcwtcd.html

JS:   require.main === module
来源：http://dali.wangshuangyany.cn/Article/details/gtwthnneli.html

TS:   require.main === module
来源：http://dali.yueranfly.top/Article/details/gtqcmudwze.html

Java: public static void main(String[] args)
来源：http://dali.zhengqikj.top/Article/details/gtehdjqebs.html

Go:   func main()
来源：http://dali.xuetiantiany.cn/Article/details/gtmrczgncs.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zycfv.cn/Article/details/gtfijipgja.html

C#:   static void Main(string[] args)
来源：http://dali.nwbrower.top/Article/details/gtdgxjkwbp.html

[M08] 获取系统与运行时信息
来源：http://dali.jinghuilouyu.cn/Article/details/gtrnstonqk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ppjwa.cn/Article/details/gtuqfvzopc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.birdmap.top/Article/details/gtnwrgzsli.html

JS:   process.platform;  process.version
来源：http://dali.cdnleiting.top/Article/details/gtxnzponqn.html

TS:   process.platform;  process.version
来源：http://dali.dianchejie.cn/Article/details/gtanmcaqhl.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhiwuduotai.top/Article/details/gtckjinobe.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuwybnidx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.quarkkingdee.top/Article/details/gtjsnwfozl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cucudq.cn/Article/details/gtdvpskdbd.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtodolmvmr.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gtdxtynbcy.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtowiougzw.html

[N01] 二分查找（有序数组）
来源：http://dali.zhiwuduotai.top/Article/details/gtxogzmjhv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtifbhzvrh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoyuqjsmq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gogol.net.cn/Article/details/gttsplmaej.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xylfe.cn/Article/details/gtybzqorfz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gtiowdtwvy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtlguywali.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.bjfxy.top/Article/details/gtnpacvbuh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtooihympa.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yangfankeji.com/Article/details/gtkovrzhuc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cheryme.top/Article/details/gtofwfbvnr.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfvqdcawu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sysykeji.top/Article/details/gtfewbbtsx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gaohongyu789.top/Article/details/gtswthckqp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yj20258.top/Article/details/gtxneqkibq.html

Go:   slices.Sort(arr)
来源：http://dali.cashguo.top/Article/details/gtobmdizod.html

Ruby: arr.sort
来源：http://dali.daria6918.cn/Article/details/gturwedktv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.meibo888.top/Article/details/gtgqfoqces.html

[N03] 快速排序（分治示例）
来源：http://dali.birdmap.top/Article/details/gtzoydhtrv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.andypj.xyz/Article/details/gtedwmokyc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gtbdatdqkh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yvedp.cn/Article/details/gtlhracyaf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zycfv.cn/Article/details/gtdmaerqhi.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.dashuyun.cn/Article/details/gtyjjstveu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yueranfly.top/Article/details/gtzwmbndjh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xuetiantiany.cn/Article/details/gtqdlxglga.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hnqzz.top/Article/details/gtulaeqzhk.html

[N04] 斐波那契数列
来源：http://dali.sysykeji.top/Article/details/gtshosclol.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ybcxt.top/Article/details/gtaibuikko.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhiwuduotai.top/Article/details/gtzdsmreel.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhoulong.xyz/Article/details/gtnaubhwci.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj202588.top/Article/details/gtrwxsvqfe.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xziqi.cn/Article/details/gtzngabsdh.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cqqwz.cn/Article/details/gtyqkmjguh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jqgfzy.top/Article/details/gtfggxkjji.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nanxuanxn.top/Article/details/gtzpgvzytw.html

[N05] 最大公约数
来源：http://dali.fzhhl.top/Article/details/gtbskkafek.html

Py:   math.gcd(a, b)
来源：http://dali.cashguo.top/Article/details/gtmxbzlhgw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yj20258.top/Article/details/gtzqgrceqz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenlongwang.top/Article/details/gtpbdtvvgm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjylwkdxq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.tanke756.top/Article/details/gthxhhjhez.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxfcuqfpt.html

Ruby: a.gcd(b)
来源：http://dali.jyoumei.cn/Article/details/gtagrvnmmh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.fzhhl.top/Article/details/gtqmyvbdhc.html

[N06] 判断回文字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtkmbrrpph.html

Py:   s == s[::-1]
来源：http://dali.tianlin.xyz/Article/details/gtglbbdily.html

PHP:  $s === strrev($s);
来源：http://dali.haohaochexian.top/Article/details/gtqhlivprr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gtubnoppjb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gttmtmnown.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jiagoushi.top/Article/details/gtuqbwooiy.html

Go:   // 双指针从两端比较
来源：http://dali.aibaodan.cn/Article/details/gthxzpmxxf.html

Ruby: s == s.reverse
来源：http://dali.redwolf501.top/Article/details/gtwiymzboz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.redwolf501.top/Article/details/gtgnzsiwit.html

[N07] 两数之和（返回下标）
来源：http://dali.zhixingplan.top/Article/details/gtrefbgeqi.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yj20258.top/Article/details/gtmrsbkszu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yonumen.top/Article/details/gtcoixalji.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jyoumei.cn/Article/details/gtrhjeshvc.html

TS:   // 手写 Map<string, number>
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoaaptotb.html

Java: // 手写 HashMap
来源：http://dali.9152youxi.cn/Article/details/gtvoorwoln.html

Go:   // 手写 map[int]int
来源：http://dali.zdqjudy.top/Article/details/gtsspkjoih.html

Ruby: // 手写 Hash
来源：http://dali.shangyingyoupin.top/Article/details/gtqulhhuvy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.pengpengdd.cyou/Article/details/gtvntskygx.html

[N08] 生成全排列
来源：http://dali.yj202588.top/Article/details/gteyjolicb.html

Py:   itertools.permutations(arr)
来源：http://dali.wangdashe.top/Article/details/gtvblubvzh.html

PHP:  // 手写递归交换
来源：http://dali.xziqi.cn/Article/details/gtvcaysqov.html

JS:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gtvvsdaolr.html

TS:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gtjbccyqnf.html

Java: // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gtjmthsdnl.html

Go:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gtuduttafn.html

Ruby: arr.permutation.to_a
来源：http://dali.svipenyu.cn/Article/details/gtpezcsydt.html

C#:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gtdxbfytbj.html

[N09] 栈与队列
来源：http://dali.yvedp.cn/Article/details/gtmuqfoqfv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gtkvfrvxud.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinqigufen.top/Article/details/gtxtsucphr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hammf.cn/Article/details/gtipqecabm.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cqqwz.cn/Article/details/gtcnyzcyea.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shzxlz.cn/Article/details/gtneunzspc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gtcfpefiwn.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shuidangran.top/Article/details/gtvirlllee.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrwdvfmcp.html

[N10] 链表节点定义
来源：http://dali.yvedp.cn/Article/details/gtsywuakbe.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.c1oappe.top/Article/details/gtdzyetrzs.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.dianchejie.cn/Article/details/gtivriuwoy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.316326.xyz/Article/details/gtagfuhdsi.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.316326.xyz/Article/details/gtoukdxvya.html

Java: class Node { int v; Node next; }
来源：http://dali.jianghu66.top/Article/details/gtottylbqg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.smart0.xyz/Article/details/gtpfsmeahn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cdnleiting.top/Article/details/gtptrjewml.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.snrcjt.cn/Article/details/gtgpmhovxk.html

[N11] 二叉树中序遍历
来源：http://dali.ivvv.top/Article/details/gtsibdyyeq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xziqi.cn/Article/details/gtdlffgmui.html

PHP:  // 手写递归函数
来源：http://dali.bjfxy.top/Article/details/gtugydfnyo.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.vqdsnc.cn/Article/details/gtfklpvlgb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sxryk.cn/Article/details/gthbpvhely.html

Java: // 手写递归
来源：http://dali.shangyingyoupin.top/Article/details/gtvbnufczm.html

Go:   // 手写递归
来源：http://dali.nwbrower.top/Article/details/gtvbopjfcm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jqgfzy.top/Article/details/gtaqletomd.html

C#:   // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gtjkayrtqo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.pengpengdd.cyou/Article/details/gtqhiabhwm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxvcrtxrt.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zycfv.cn/Article/details/gtrhkhfdyg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgufenzy.top/Article/details/gtpqeflehp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gzhubu.top/Article/details/gtbnftyhju.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.0kj1m.cn/Article/details/gtkoyvntlc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.bjfxy.top/Article/details/gthypfowsf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinqigufen.top/Article/details/gtrqadhdxs.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.quarkkingdee.top/Article/details/gtjbukzqnw.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtfcspxntn.html

O. 并发与异步
来源：http://dali.smart0.xyz/Article/details/gtffuhwzso.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtjtiqyeyh.html

[O01] 启动一个线程
来源：http://dali.tianlin.xyz/Article/details/gtlcxvedfn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.tianlin.xyz/Article/details/gtqyvilwed.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.guannengcc.top/Article/details/gtqpspjhzy.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinghuilouyu.cn/Article/details/gtuovbhwpk.html

TS:   // 同 JS
来源：http://dali.yj20258.top/Article/details/gtnsviwpcu.html

Java: new Thread(() -> f()).start()
来源：http://dali.shuidangran.top/Article/details/gtwydknrba.html

Go:   go f()
来源：http://dali.zhoulong.xyz/Article/details/gtxxmncqax.html

Ruby: Thread.new { f }
来源：http://dali.hammf.cn/Article/details/gtfxrwjawm.html

C#:   Task.Run(() => F());
来源：http://dali.yj202588.top/Article/details/gtwbkowqkh.html

[O02] 使用线程池
来源：http://dali.jlsjyb.cn/Article/details/gtakmyjunl.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shangyingyoupin.top/Article/details/gtpbxmjjlz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinqigufen.top/Article/details/gtnnhyslym.html

JS:   // worker_threads 线程池
来源：http://dali.bjfxy.top/Article/details/gthjpdpbae.html

TS:   // worker_threads 线程池
来源：http://dali.zhoulong.xyz/Article/details/gtvhbfeuru.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cqqwz.cn/Article/details/gteaavckym.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.andypj.xyz/Article/details/gtaqqcuiqr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zycfv.cn/Article/details/gtfbtgrbfo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jlsjyb.cn/Article/details/gtbafvahzr.html

[O03] 加锁保护共享数据
来源：http://dali.yuxming.cn/Article/details/gtqhuzyhug.html

Py:   with lock: shared += 1
来源：http://dali.nanxuanxn.top/Article/details/gtfmusaomz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cashguo.top/Article/details/gticxartxr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.nwbrower.top/Article/details/gtgzezxcvn.html

TS:   // 同 JS
来源：http://dali.hfpthk.cn/Article/details/gtwnpmfecp.html

Java: synchronized (this) { shared++; }
来源：http://dali.feifeiyinyue.top/Article/details/gtynqxqtge.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.snrcjt.cn/Article/details/gtkwgakolq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.pengpengdd.cyou/Article/details/gtsifpokmc.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gthwdujvzd.html

[O04] 定义异步函数并等待
来源：http://dali.jlsjyb.cn/Article/details/gturpnkbwi.html

Py:   async def f():⏎    await g()
来源：http://dali.haohaochexian.top/Article/details/gthangpqjx.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jlsjyb.cn/Article/details/gtqzvdrwvv.html

JS:   async function f() { await g(); }
来源：http://dali.cashguo.top/Article/details/gtjblikcuh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jyoumei.cn/Article/details/gtttgolcnq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ivvv.top/Article/details/gtyetfizox.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hongshengwenyu.top/Article/details/gtllxiyamb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hfpthk.cn/Article/details/gtcunifhtr.html

C#:   async Task F() { await G(); }
来源：http://dali.bjfxy.top/Article/details/gtvxufqxpy.html

[O05] 并发执行并等待全部完成
来源：http://dali.birdmap.top/Article/details/gtlzpbfvne.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinqigufen.top/Article/details/gtmekrataa.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.pengpengdd.cyou/Article/details/gtctjgbfmo.html

JS:   await Promise.all(tasks)
来源：http://dali.gotoacloud.top/Article/details/gtrqgfbhsi.html

TS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaffvqtbc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhengqikj.top/Article/details/gtpfpbpacm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shuidangran.top/Article/details/gtndqlwsvc.html

Ruby: threads.map(&:join)
来源：http://dali.zhiwuduotai.top/Article/details/gtcmiwhzpb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zycfv.cn/Article/details/gtmqsrcgbc.html

[O06] 使用进程池
来源：http://dali.ybcxt.top/Article/details/gtzhoagozr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sufxvd.cn/Article/details/gtozvhbjqi.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xuetiantiany.cn/Article/details/gtsyxtgyei.html

JS:   // child_process / cluster 模块
来源：http://dali.pengpengdd.cyou/Article/details/gtzevrtctx.html

TS:   // child_process / cluster 模块
来源：http://dali.fzhhl.top/Article/details/gtnnubdvfo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yuxming.cn/Article/details/gtjpaoakfu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shzxlz.cn/Article/details/gtlfxmxovw.html

Ruby: // fork 块
来源：http://dali.dianchejie.cn/Article/details/gttxhbzzjf.html

C#:   Parallel.For
来源：http://dali.cqqwz.cn/Article/details/gtsbzwtxlr.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtryqnpcdr.html

P. 常用工具函数
来源：http://dali.hammf.cn/Article/details/gtuqaovfqe.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtpocdwrhv.html

[P01] 生成 UUID
来源：http://dali.tanke756.top/Article/details/gtnrqxaifz.html

Py:   str(uuid.uuid4())
来源：http://dali.vqdsnc.cn/Article/details/gtpbcdyoxf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ybcxt.top/Article/details/gtnstjakmw.html

JS:   crypto.randomUUID()
来源：http://dali.yj20258.top/Article/details/gtfxsseued.html

TS:   crypto.randomUUID()
来源：http://dali.shzxlz.cn/Article/details/gtflnaifui.html

Java: UUID.randomUUID().toString()
来源：http://dali.gogol.net.cn/Article/details/gtiqwwjipo.html

Go:   // 用 github.com/google/uuid
来源：http://dali.feifeiyinyue.top/Article/details/gtgkznaitf.html

Ruby: SecureRandom.uuid
来源：http://dali.daria6918.cn/Article/details/gtxtacjonv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xuanzx.com/Article/details/gtvupcmwsx.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cucudq.cn/Article/details/gtiebydfym.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cashguo.top/Article/details/gtkjanmrvd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhongyouzk.top/Article/details/gtvtpjpqgm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hfpthk.cn/Article/details/gtmgxfglhm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.smart0.xyz/Article/details/gttpzvnuyk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yangfankeji.com/Article/details/gtfnynukqf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhengqikj.top/Article/details/gtiiqvfstp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ppjwa.cn/Article/details/gtfmpmyzbf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yuanzhike.top/Article/details/gtgxzmbrtk.html

[P03] 生成短随机字符串
来源：http://dali.xinyue.icu/Article/details/gtdzasmfps.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.gotoacloud.top/Article/details/gtrlvpppnx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.smart0.xyz/Article/details/gtdwdyoxnr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tanke756.top/Article/details/gttdsxrvlr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.316326.xyz/Article/details/gtvlqgzzsx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.guowangkeji.top/Article/details/gtvdwomlxj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnzihiids.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.316326.xyz/Article/details/gtcjcegtjy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.fzhhl.top/Article/details/gtywahungh.html

[P04] 求长度
来源：http://dali.zdqjudy.top/Article/details/gtzymbkjet.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoxjtkryg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gtynvkjjig.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shuidangran.top/Article/details/gtikrwgkky.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhoulong.xyz/Article/details/gtsqopusyf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hywenlv.cn/Article/details/gtattovxxz.html

Go:   len(arr);  len(m)
来源：http://dali.hfpthk.cn/Article/details/gtokfoqthz.html

Ruby: x.length;  x.size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzmauskjc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ivvv.top/Article/details/gtznhrthor.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xziqi.cn/Article/details/gtpvivhnoa.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtimitgfyn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sxryk.cn/Article/details/gtecbkksqt.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gzhubu.top/Article/details/gtsgqwjhmf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.feifeiyinyue.top/Article/details/gtiiepiqjy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zycfv.cn/Article/details/gthtxwuiit.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.tanke756.top/Article/details/gtbcuzdgjj.html

Ruby: a == b
来源：http://dali.shangyingyoupin.top/Article/details/gtgkyzplqr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xylfe.cn/Article/details/gtzeceifdv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sufxvd.cn/Article/details/gtfsiiwhhn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ydzc1.top/Article/details/gtofptfwcl.html

PHP:  if (empty($x)) {}
来源：http://dali.vqdsnc.cn/Article/details/gthnulnedz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlkusdcfc.html

TS:   if (x == null) {}
来源：http://dali.hywenlv.cn/Article/details/gtsothhvmq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvoghdegu.html

Go:   if x == nil {}
来源：http://dali.ybcxt.top/Article/details/gttzoclion.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cheryme.top/Article/details/gturtggabk.html

C#:   if (x is null) {}
来源：http://dali.daria6918.cn/Article/details/gtyduqxyrz.html

[P07] 防抖与节流
来源：http://dali.wangshuangyany.cn/Article/details/gtkfhjaucb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xziqi.cn/Article/details/gtgynwqnmu.html

PHP:  // 手写时间戳比较
来源：http://dali.gaohongyu789.top/Article/details/gtpuuovlbi.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jyoumei.cn/Article/details/gtsxnonhbn.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.smart0.xyz/Article/details/gtwnddsqnr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.fengsongda.top/Article/details/gtavgzvfcr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jqgufenzy.top/Article/details/gtqpqlmthv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yvedp.cn/Article/details/gtqqjdgpmq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gtiprjtixj.html

[P08] 处理浮点精度问题
来源：http://dali.xziqi.cn/Article/details/gtmuipdzzj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cdnleiting.top/Article/details/gtzyiodinw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.birdmap.top/Article/details/gtnwyvxwid.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.daxiang520.top/Article/details/gtoliucsop.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinqigfzy.top/Article/details/gtsgadsjuz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.daria6918.cn/Article/details/gteakgwnln.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xuanzx.com/Article/details/gtxkicqkxs.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.pycfn.com/Article/details/gtynwuuipx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.haohaochexian.top/Article/details/gtheiqhkxb.html


<!-- 参考信息 -->