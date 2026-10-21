代发 wailian999

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yueranfly.top/Article/details/gtfqbfahtt.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xinyue.icu/Article/details/gtzxafbhuv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.quarkkingdee.top/Article/details/gtntjackkb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yuxming.cn/Article/details/gtgrqbmqxp.html

[M04] 获取当前工作目录
来源：http://dali.daxiang520.top/Article/details/gtjgcwkhim.html

Py:   os.getcwd()
来源：http://dali.ivvv.top/Article/details/gtpfolqsjs.html

PHP:  getcwd();
来源：http://dali.pycfn.com/Article/details/gtsdowgxkn.html

JS:   process.cwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfhlqruxw.html

TS:   process.cwd()
来源：http://dali.tanke756.top/Article/details/gtbrkemkzc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ppjwa.cn/Article/details/gtczmctjqr.html

Go:   os.Getwd()
来源：http://dali.svipenyu.cn/Article/details/gtncfvvfpw.html

Ruby: Dir.pwd
来源：http://dali.0kj1m.cn/Article/details/gtrpcxambc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoghxxhqb.html

[M05] 设置退出码
来源：http://dali.yvedp.cn/Article/details/gtfhfamsvy.html

Py:   sys.exit(1)
来源：http://dali.xuanzx.com/Article/details/gtdskaopqj.html

PHP:  exit(1);
来源：http://dali.jianghu66.top/Article/details/gtkronwpyk.html

JS:   process.exit(1)
来源：http://dali.xuanzx.com/Article/details/gtnpqojnxp.html

TS:   process.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gtiafcmpto.html

Java: System.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtfwshnkis.html

Go:   os.Exit(1)
来源：http://dali.cucudq.cn/Article/details/gtzoaiwnvp.html

Ruby: exit 1
来源：http://dali.jianghu66.top/Article/details/gtzeoaxwgw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.daxiang520.top/Article/details/gtjqwuxetb.html

[M06] 向标准错误输出
来源：http://dali.snrcjt.cn/Article/details/gtxwoafxkh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xziqi.cn/Article/details/gtxmogwycw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.tianlin.xyz/Article/details/gtkpbaucby.html

JS:   console.error("err")
来源：http://dali.dianchejie.cn/Article/details/gtcbjupuvo.html

TS:   console.error("err")
来源：http://dali.zdqjudy.top/Article/details/gtjozcmzrf.html

Java: System.err.println("err")
来源：http://dali.chenjidiqi.icu/Article/details/gtwbelsiug.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hnxiangtu.top/Article/details/gtorvhtmrc.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gtcfcfvtlw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cdnleiting.top/Article/details/gtwrzbccli.html

[M07] 判断是否为主入口
来源：http://dali.vqdsnc.cn/Article/details/gtnqtdjeis.html

Py:   if __name__ == "__main__":
来源：http://dali.smart0.xyz/Article/details/gtyuuordyr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoviwygun.html

JS:   require.main === module
来源：http://dali.jinqigufen.top/Article/details/gtvjktselj.html

TS:   require.main === module
来源：http://dali.hammf.cn/Article/details/gthdipxlle.html

Java: public static void main(String[] args)
来源：http://dali.pengpengdd.cyou/Article/details/gttfqstuaw.html

Go:   func main()
来源：http://dali.haohaochexian.top/Article/details/gtpfvprqds.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.redwolf501.top/Article/details/gthfenmdbg.html

C#:   static void Main(string[] args)
来源：http://dali.dashuyun.cn/Article/details/gtyldkcgyz.html

[M08] 获取系统与运行时信息
来源：http://dali.shzxlz.cn/Article/details/gthdbkjbig.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ydzc1.top/Article/details/gtyscjkcwe.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hongshengwenyu.top/Article/details/gtkdrwpmio.html

JS:   process.platform;  process.version
来源：http://dali.hnxiangtu.top/Article/details/gttcxmpocj.html

TS:   process.platform;  process.version
来源：http://dali.chenzaomai.com/Article/details/gtjsiwzibc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.dashuyun.cn/Article/details/gtfmfdnxok.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gzhubu.top/Article/details/gtuaqbmtkq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jlsjyb.cn/Article/details/gtxucxnzzn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shzxlz.cn/Article/details/gtxuxovqxy.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gttrzgodnp.html

N. 数据结构与算法
来源：http://dali.dashuyun.cn/Article/details/gtdlfptcui.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtwzquxxps.html

[N01] 二分查找（有序数组）
来源：http://dali.jinghuilouyu.cn/Article/details/gthcdfelxr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtykfdxlmf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yueranfly.top/Article/details/gtmcommoco.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gtpxjjdckb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daxiang520.top/Article/details/gtwbggxhvm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtgqteidik.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtanrrzqvw.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.feifeiyinyue.top/Article/details/gtoghbbhin.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtjsfdevnv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xylfe.cn/Article/details/gtcakwbgxf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnqzz.top/Article/details/gtnzcdpjqo.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shzxlz.cn/Article/details/gtsxitqjdp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhixingplan.top/Article/details/gtbczrvouf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gotoacloud.top/Article/details/gtcxscxaug.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyceztfnn.html

Go:   slices.Sort(arr)
来源：http://dali.yongpay.top/Article/details/gtecdhfsgr.html

Ruby: arr.sort
来源：http://dali.hongshengwenyu.top/Article/details/gtbtfjeftd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.sufxvd.cn/Article/details/gtqjszmwsu.html

[N03] 快速排序（分治示例）
来源：http://dali.yj20258.top/Article/details/gtfbmphvvf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.bjfxy.top/Article/details/gtqjsdswfz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.haohaochexian.top/Article/details/gtotdiynil.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fengsongda.top/Article/details/gtaagtlfhw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.vqdsnc.cn/Article/details/gtvvpnoylv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.pycfn.com/Article/details/gtolqzexzs.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yvedp.cn/Article/details/gtflezincn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sweek.top/Article/details/gtxgmkbdei.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.feifeiyinyue.top/Article/details/gtlnycuaax.html

[N04] 斐波那契数列
来源：http://dali.pengpengdd.cyou/Article/details/gtmeokcnxo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hysaishi.cn/Article/details/gtpayvoolt.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hfpthk.cn/Article/details/gtwdofurzz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pycfn.com/Article/details/gtxbsfytkh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfqouverg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.feifeiyinyue.top/Article/details/gtkxvyjgwy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yj202588.top/Article/details/gtgumpkfow.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.kuanghao11.cn/Article/details/gtguvqyfct.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.tian-w.cn/Article/details/gtpgprvwwl.html

[N05] 最大公约数
来源：http://dali.ywan-chungtsiang.top/Article/details/gttidzpbfj.html

Py:   math.gcd(a, b)
来源：http://dali.feifeiyinyue.top/Article/details/gtqvyhrprz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sufxvd.cn/Article/details/gtgcdbtiar.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.bjfxy.top/Article/details/gtpqkvyvxu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dashuyun.cn/Article/details/gtrtxhpkab.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jqgufenzy.top/Article/details/gtgrtsvxly.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.fzhhl.top/Article/details/gtflkctqev.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gtoclzimgw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yonumen.top/Article/details/gtmglqyhtu.html

[N06] 判断回文字符串
来源：http://dali.ehwqpu.com/Article/details/gtrteuelzp.html

Py:   s == s[::-1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvmfxlien.html

PHP:  $s === strrev($s);
来源：http://dali.zhongyouzk.top/Article/details/gtixcuubwk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtokehielf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sweek.top/Article/details/gtqgozqgtp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.bjfxy.top/Article/details/gthgmmdssx.html

Go:   // 双指针从两端比较
来源：http://dali.sufxvd.cn/Article/details/gtuebafkyq.html

Ruby: s == s.reverse
来源：http://dali.xinyue.icu/Article/details/gtippxbixt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxexfzuih.html

[N07] 两数之和（返回下标）
来源：http://dali.yonumen.top/Article/details/gtzfdwogbc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yanxiufei.cn/Article/details/gtgpnaelhk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hammf.cn/Article/details/gtqchcmezt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yueranfly.top/Article/details/gtvqxkfsic.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlujacfza.html

Java: // 手写 HashMap
来源：http://dali.gaohongyu789.top/Article/details/gtzimwhtjd.html

Go:   // 手写 map[int]int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjqdkzzlp.html

Ruby: // 手写 Hash
来源：http://dali.vqdsnc.cn/Article/details/gtnkcrssqb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhongyouzk.top/Article/details/gtbbuvwvom.html

[N08] 生成全排列
来源：http://dali.hywenlv.cn/Article/details/gtkxxaiebb.html

Py:   itertools.permutations(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttjpuchwk.html

PHP:  // 手写递归交换
来源：http://dali.sysykeji.top/Article/details/gtoepxpvtt.html

JS:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gtcabtynhi.html

TS:   // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gtdtzmitoz.html

Java: // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gthoftxkzh.html

Go:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gtbzkaydyw.html

Ruby: arr.permutation.to_a
来源：http://dali.guannengcc.top/Article/details/gtuhkfdbms.html

C#:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gtmapswyto.html

[N09] 栈与队列
来源：http://dali.0kj1m.cn/Article/details/gtkqtzkxyu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gotoacloud.top/Article/details/gtyuxqslek.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zycfv.cn/Article/details/gtodlumwkb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yueranfly.top/Article/details/gtjqwgimoj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.aibaodan.cn/Article/details/gtrpprnnha.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xinyue.icu/Article/details/gthypsvmjp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shzxlz.cn/Article/details/gtmcvsvjpc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.fengsongda.top/Article/details/gthqnrwmtc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenlongwang.top/Article/details/gtsrfkweji.html

[N10] 链表节点定义
来源：http://dali.bjfxy.top/Article/details/gtxjfuzevy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cucudq.cn/Article/details/gtchlcnqca.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.mhx1999.top/Article/details/gtnwenrarw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xuanzx.com/Article/details/gtfbljnbqd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sufxvd.cn/Article/details/gtivtuhxbo.html

Java: class Node { int v; Node next; }
来源：http://dali.shangyingyoupin.top/Article/details/gttlwafwao.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenzaomai.com/Article/details/gtiizdormf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.daria6918.cn/Article/details/gtcrephxss.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zdqjudy.top/Article/details/gtyruaxpqc.html

[N11] 二叉树中序遍历
来源：http://dali.fzhhl.top/Article/details/gtndozywoo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zdqjudy.top/Article/details/gthliwtxpb.html

PHP:  // 手写递归函数
来源：http://dali.meibo888.top/Article/details/gtkgnydrfd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zycfv.cn/Article/details/gtwzxxodvc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yanxiufei.cn/Article/details/gtzhojomqb.html

Java: // 手写递归
来源：http://dali.zycfv.cn/Article/details/gtnihuxqip.html

Go:   // 手写递归
来源：http://dali.gaohongyu789.top/Article/details/gtnraxhlwn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.pycfn.com/Article/details/gtqyesfskp.html

C#:   // 手写递归
来源：http://dali.quarkkingdee.top/Article/details/gtmhgyhicf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmbkwkphs.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xinyue.icu/Article/details/gtaleydkci.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.tanke756.top/Article/details/gtistzotyy.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ivvv.top/Article/details/gtavmkkxgv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xuetiantiany.cn/Article/details/gtbxhwfarz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuanzx.com/Article/details/gtbyhuqnsv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.smart0.xyz/Article/details/gtdvpflvoy.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.tanke756.top/Article/details/gtuvjgsozk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.9152youxi.cn/Article/details/gtlyxitolj.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtekgiabay.html

O. 并发与异步
来源：http://dali.mhx1999.top/Article/details/gttblhqyke.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtdzwaajmo.html

[O01] 启动一个线程
来源：http://dali.snrcjt.cn/Article/details/gtzjqeiole.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jinqigfzy.top/Article/details/gtgsmpkqzf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gaohongyu789.top/Article/details/gtdsrwwwzg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yueranfly.top/Article/details/gtgvrnccbq.html

TS:   // 同 JS
来源：http://dali.jiagoushi.top/Article/details/gtnmzzjafr.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhongyouzk.top/Article/details/gteejkjugi.html

Go:   go f()
来源：http://dali.redwolf501.top/Article/details/gtdxjyduhh.html

Ruby: Thread.new { f }
来源：http://dali.meibo888.top/Article/details/gtfygzallu.html

C#:   Task.Run(() => F());
来源：http://dali.nanxuanxn.top/Article/details/gtdibxiwmg.html

[O02] 使用线程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnohabvry.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jianghu66.top/Article/details/gtfcesxkxz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.nanxuanxn.top/Article/details/gtdzsbzpjj.html

JS:   // worker_threads 线程池
来源：http://dali.tianlin.xyz/Article/details/gtjhusnnlu.html

TS:   // worker_threads 线程池
来源：http://dali.daria6918.cn/Article/details/gtpllbgdzn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jlsjyb.cn/Article/details/gtczzbrnop.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.feifeiyinyue.top/Article/details/gtgnnlennl.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jinqigfzy.top/Article/details/gtgkfjfrlf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.haohaochexian.top/Article/details/gtwakdyqyl.html

[O03] 加锁保护共享数据
来源：http://dali.aibaodan.cn/Article/details/gtmcofndyq.html

Py:   with lock: shared += 1
来源：http://dali.gzhubu.top/Article/details/gtpkfjdcmo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gaohongyu789.top/Article/details/gtlqjpnmmx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hongshengwenyu.top/Article/details/gtywtqaixb.html

TS:   // 同 JS
来源：http://dali.sysykeji.top/Article/details/gtarycxdtn.html

Java: synchronized (this) { shared++; }
来源：http://dali.yuxming.cn/Article/details/gthecaxcoe.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yj20258888.top/Article/details/gtkcnmkvqy.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinqigfzy.top/Article/details/gtvmkjfnvi.html

C#:   lock (gate) { shared++; }
来源：http://dali.xuetiantiany.cn/Article/details/gtpuqwzzqk.html

[O04] 定义异步函数并等待
来源：http://dali.fzhhl.top/Article/details/gtsrgttlwo.html

Py:   async def f():⏎    await g()
来源：http://dali.haohaochexian.top/Article/details/gtqzvimsps.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinqigufen.top/Article/details/gtkmboowdx.html

JS:   async function f() { await g(); }
来源：http://dali.zhoulong.xyz/Article/details/gtvmxvdwmp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yuanzhike.top/Article/details/gthwkbfowo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cashguo.top/Article/details/gtspfqmgbr.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yonumen.top/Article/details/gtobkwyhxh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.guowangkeji.top/Article/details/gttuolenuu.html

C#:   async Task F() { await G(); }
来源：http://dali.316326.xyz/Article/details/gtegqdhdnq.html

[O05] 并发执行并等待全部完成
来源：http://dali.c1oappe.top/Article/details/gtxhhjupda.html

Py:   asyncio.gather(*tasks)
来源：http://dali.gotoacloud.top/Article/details/gtpwbrvttr.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.smart0.xyz/Article/details/gtgtzvdpcw.html

JS:   await Promise.all(tasks)
来源：http://dali.yanxiufei.cn/Article/details/gtzmrnbswm.html

TS:   await Promise.all(tasks)
来源：http://dali.bjfxy.top/Article/details/gthqnujlcj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.nwbrower.top/Article/details/gtvsknkqlo.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.feifeiyinyue.top/Article/details/gtjwfmwmfy.html

Ruby: threads.map(&:join)
来源：http://dali.yonumen.top/Article/details/gtffznrunc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.andypj.xyz/Article/details/gtygngzujv.html

[O06] 使用进程池
来源：http://dali.smart0.xyz/Article/details/gtryldckvw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ppjwa.cn/Article/details/gtgxqxtrkf.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.redwolf501.top/Article/details/gtgigirmgi.html

JS:   // child_process / cluster 模块
来源：http://dali.chenlongwang.top/Article/details/gtdqbjsbhk.html

TS:   // child_process / cluster 模块
来源：http://dali.zdqjudy.top/Article/details/gtezyefymo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.redwolf501.top/Article/details/gtyuxjceys.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jinqigfzy.top/Article/details/gtuifryfic.html

Ruby: // fork 块
来源：http://dali.nanxuanxn.top/Article/details/gtvtuhkqgl.html

C#:   Parallel.For
来源：http://dali.c1oappe.top/Article/details/gtqrjjxdpz.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtwfxctzmk.html

P. 常用工具函数
来源：http://dali.havefunace.top/Article/details/gttmbestpc.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtuokjtota.html

[P01] 生成 UUID
来源：http://dali.jinqigufen.top/Article/details/gtkbwvmnps.html

Py:   str(uuid.uuid4())
来源：http://dali.hnqzz.top/Article/details/gtvqvbjagd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkurlgwxe.html

JS:   crypto.randomUUID()
来源：http://dali.havefunace.top/Article/details/gtrlzbhxkf.html

TS:   crypto.randomUUID()
来源：http://dali.jinqigfzy.top/Article/details/gtciwicjid.html

Java: UUID.randomUUID().toString()
来源：http://dali.wangshuangyany.cn/Article/details/gteiepiyar.html

Go:   // 用 github.com/google/uuid
来源：http://dali.daxiang520.top/Article/details/gtfeikzabi.html

Ruby: SecureRandom.uuid
来源：http://dali.xziqi.cn/Article/details/gtmfoemttq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yj202588.top/Article/details/gtnaotpeig.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yuxming.cn/Article/details/gtwagjgbzy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinghuilouyu.cn/Article/details/gtpynkopyf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ppjwa.cn/Article/details/gtscaqyphc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.quarkkingdee.top/Article/details/gtfiqofjds.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhoulong.xyz/Article/details/gtesbavgfb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj20258888.top/Article/details/gtqwkmvelm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.nanxinkj.top/Article/details/gtkbdotage.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtptpvwnur.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jianghu66.top/Article/details/gtazmhseeo.html

[P03] 生成短随机字符串
来源：http://dali.aizwys.cn/Article/details/gtzufnxsdz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.chenjidiqi.icu/Article/details/gtnslttvil.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.tianlin.xyz/Article/details/gtxjgbslnd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.snrcjt.cn/Article/details/gtndjcvtdw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cucudq.cn/Article/details/gtgdkhntwl.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.daxiang520.top/Article/details/gtplmrbojh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ivvv.top/Article/details/gtqqhgsxrn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zycfv.cn/Article/details/gtvuqrtfrs.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yongpay.top/Article/details/gtroemqijb.html

[P04] 求长度
来源：http://dali.hnqzz.top/Article/details/gtzsmixwox.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tanke756.top/Article/details/gtjnwuhpgy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gtokxdfdof.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxuanxn.top/Article/details/gtokemzeky.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fzhhl.top/Article/details/gtspqawwbc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.iojbl.cn/Article/details/gtvmhayrpd.html

Go:   len(arr);  len(m)
来源：http://dali.jlsjyb.cn/Article/details/gtublszdis.html

Ruby: x.length;  x.size
来源：http://dali.shangyingyoupin.top/Article/details/gtpmztmgan.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sweek.top/Article/details/gtzhuwvlqe.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwyusuvqf.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhiwuduotai.top/Article/details/gtnyxftqux.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jlsjyb.cn/Article/details/gtpnmbuunr.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.tianlin.xyz/Article/details/gtttcpyaqo.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.fzhhl.top/Article/details/gtmtrymgsv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xinyue.icu/Article/details/gtlogbeazh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.birdmap.top/Article/details/gtbzfqzsnj.html

Ruby: a == b
来源：http://dali.havefunace.top/Article/details/gtmaoajicq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.pycfn.com/Article/details/gteqisexui.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yangfankeji.com/Article/details/gtgbygrjxb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shangyingyoupin.top/Article/details/gtqqzlcrjg.html

PHP:  if (empty($x)) {}
来源：http://dali.redwolf501.top/Article/details/gtnojdlmja.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gtcxhgspme.html

TS:   if (x == null) {}
来源：http://dali.gogol.net.cn/Article/details/gtdzbulxyd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ivvv.top/Article/details/gtzfruptcj.html

Go:   if x == nil {}
来源：http://dali.daxiang520.top/Article/details/gtqqktuvrq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.aibaodan.cn/Article/details/gtnbradcql.html

C#:   if (x is null) {}
来源：http://dali.zhixingplan.top/Article/details/gtefmwlvbq.html

[P07] 防抖与节流
来源：http://dali.jlsjyb.cn/Article/details/gtyhfgxrjy.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.chenzaomai.com/Article/details/gtachnfibf.html

PHP:  // 手写时间戳比较
来源：http://dali.wangshuangyany.cn/Article/details/gtieqkfzao.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gotoacloud.top/Article/details/gtrnnpckom.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sxryk.cn/Article/details/gttailzupe.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jqgufenzy.top/Article/details/gtxiyebjfq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yj202588.top/Article/details/gtveqhepij.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.aibaodan.cn/Article/details/gtdauxbgns.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xuetiantiany.cn/Article/details/gtgmynixbb.html

[P08] 处理浮点精度问题
来源：http://dali.ivvv.top/Article/details/gtelkffslr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.fengsongda.top/Article/details/gtlsrvebos.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.c1oappe.top/Article/details/gtlwypqcvo.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.vqdsnc.cn/Article/details/gtnzhzenef.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmttkbhlo.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.dashuyun.cn/Article/details/gtnxqnvfwo.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hnqzz.top/Article/details/gtzybhyguz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cheryme.top/Article/details/gtxkktdhuj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yuanzhike.top/Article/details/gtzmfyniow.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtynpufcji.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yuanzhike.top/Article/details/gtwwqhoqhn.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtwfkrbifc.html

[Q01] 创建表
来源：http://dali.nwbrower.top/Article/details/gtdeqwtpfl.html

CREATE TABLE users (
来源：http://dali.yj20258888.top/Article/details/gtrffubfau.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daria6918.cn/Article/details/gtrkklrlum.html

name VARCHAR(50) NOT NULL,
来源：http://dali.tianlin.xyz/Article/details/gtzxalthaq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gotoacloud.top/Article/details/gtulhbabwv.html


<!-- 参考信息 -->