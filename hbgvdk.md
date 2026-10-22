代发 wailian999

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.daria6918.cn/Article/details/gt2ilsvjoxj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hammf.cn/Article/details/gt2thzdszok.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tanke756.top/Article/details/gt2uibvgqko.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ivvv.top/Article/details/gt2jriuzepy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.dianchejie.cn/Article/details/gt2isetmywp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yj202588.top/Article/details/gt2zbarvhqh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rmhtduln.html

C#:   Process.Start("ls", "-l");
来源：http://dali.aizwys.cn/Article/details/gt2fdgxudsg.html

[M04] 获取当前工作目录
来源：http://dali.dashuyun.cn/Article/details/gt2kdhnshry.html

Py:   os.getcwd()
来源：http://dali.svipenyu.cn/Article/details/gt2stwikfve.html

PHP:  getcwd();
来源：http://dali.shangyingyoupin.top/Article/details/gt2wjkukudn.html

JS:   process.cwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wmoiolyb.html

TS:   process.cwd()
来源：http://dali.ppjwa.cn/Article/details/gt2qkcalwwm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.daxiang520.top/Article/details/gt2ntftaczy.html

Go:   os.Getwd()
来源：http://dali.chenlongwang.top/Article/details/gt2nxgxbwae.html

Ruby: Dir.pwd
来源：http://dali.hammf.cn/Article/details/gt2etmzkpxu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yongpay.top/Article/details/gt2gmqwxtnq.html

[M05] 设置退出码
来源：http://dali.hysaishi.cn/Article/details/gt2dlytdqsv.html

Py:   sys.exit(1)
来源：http://dali.iojbl.cn/Article/details/gt2uskzkgij.html

PHP:  exit(1);
来源：http://dali.pycfn.com/Article/details/gt2ixtcmwxo.html

JS:   process.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gt2eyvxwqvz.html

TS:   process.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2bazxvfzm.html

Java: System.exit(1)
来源：http://dali.hammf.cn/Article/details/gt2cuykjqzm.html

Go:   os.Exit(1)
来源：http://dali.shzxlz.cn/Article/details/gt2akllmbqn.html

Ruby: exit 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pvjmgrua.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.tian-w.cn/Article/details/gt2geqyiaqk.html

[M06] 向标准错误输出
来源：http://dali.xziqi.cn/Article/details/gt2hxgcfudn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.tian-w.cn/Article/details/gt2oscupzdq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yangfankeji.com/Article/details/gt2cvngiefn.html

JS:   console.error("err")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ocbqdwsy.html

TS:   console.error("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vrwndqfm.html

Java: System.err.println("err")
来源：http://dali.kuanghao11.cn/Article/details/gt2kdkvuuaa.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhixingplan.top/Article/details/gt2wesjlqjs.html

Ruby: warn "err"
来源：http://dali.zhiwuduotai.top/Article/details/gt2hjemalcq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yj202588.top/Article/details/gt2fvfrimne.html

[M07] 判断是否为主入口
来源：http://dali.yongpay.top/Article/details/gt2gwystpwv.html

Py:   if __name__ == "__main__":
来源：http://dali.cheryme.top/Article/details/gt2mpwmqcmi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.feifeiyinyue.top/Article/details/gt2jdmpxfpb.html

JS:   require.main === module
来源：http://dali.quarkkingdee.top/Article/details/gt2pfcvdoeo.html

TS:   require.main === module
来源：http://dali.pycfn.com/Article/details/gt2eafwvjfi.html

Java: public static void main(String[] args)
来源：http://dali.nanxinkj.top/Article/details/gt2rigtmiuw.html

Go:   func main()
来源：http://dali.tian-w.cn/Article/details/gt2nuyptwub.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yj202588.top/Article/details/gt2hgnghwsb.html

C#:   static void Main(string[] args)
来源：http://dali.shuidangran.top/Article/details/gt2sjtdyhcb.html

[M08] 获取系统与运行时信息
来源：http://dali.fengsongda.top/Article/details/gt2jpuxycwz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sxryk.cn/Article/details/gt2rgkslllh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shzxlz.cn/Article/details/gt2bvawdvra.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2qktqsauf.html

TS:   process.platform;  process.version
来源：http://dali.xinyue.icu/Article/details/gt2yhcijvoh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.iojbl.cn/Article/details/gt2ywhtyblw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lfejjecu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fcifewpe.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xinyue.icu/Article/details/gt2iomwoudw.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2vbibhhns.html

N. 数据结构与算法
来源：http://dali.0kj1m.cn/Article/details/gt2dconaxam.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2arypwqgm.html

[N01] 二分查找（有序数组）
来源：http://dali.xuetiantiany.cn/Article/details/gt2pktzodek.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hnqzz.top/Article/details/gt2lmjzvslf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.redwolf501.top/Article/details/gt2ckitroua.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ppjwa.cn/Article/details/gt2niahibxn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sweek.top/Article/details/gt2htnzdnhq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xuanzx.com/Article/details/gt2jkhrrkkv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gt2orksgoal.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.birdmap.top/Article/details/gt2bakblxfl.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gt2sapntqfp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hongshengwenyu.top/Article/details/gt2wotwfffo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cdnleiting.top/Article/details/gt2zgohwmto.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yonumen.top/Article/details/gt2xyxufxre.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2dugkokmc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.bjfxy.top/Article/details/gt2mvdzdfef.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xziqi.cn/Article/details/gt2jwxvvcim.html

Go:   slices.Sort(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2xtsbhjzo.html

Ruby: arr.sort
来源：http://dali.xuanzx.com/Article/details/gt2yknrsmnt.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.quarkkingdee.top/Article/details/gt2dlcbwpwb.html

[N03] 快速排序（分治示例）
来源：http://dali.snrcjt.cn/Article/details/gt2adknhilu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.snrcjt.cn/Article/details/gt2pphcuczi.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinqigufen.top/Article/details/gt2ejsgxbgl.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhixingplan.top/Article/details/gt2lfdqbsup.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hongshengwenyu.top/Article/details/gt2rbpryczu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.dashuyun.cn/Article/details/gt2katftqfl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.316326.xyz/Article/details/gt2jahwvrau.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cdnleiting.top/Article/details/gt2vsnuirti.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yj20258.top/Article/details/gt2yqtqrjwf.html

[N04] 斐波那契数列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tyomlmck.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jyoumei.cn/Article/details/gt2mhnzqair.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zkqiozfm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yangfankeji.com/Article/details/gt2sjpkneus.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cdnleiting.top/Article/details/gt2uaqypdtz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.smart0.xyz/Article/details/gt2zhhyoiqy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hysaishi.cn/Article/details/gt2nsbxjgly.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jiagoushi.top/Article/details/gt2wmtjmcyt.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gt2piunoxgu.html

[N05] 最大公约数
来源：http://dali.dashuyun.cn/Article/details/gt2qtmgmmvr.html

Py:   math.gcd(a, b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uskixfsi.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jlsjyb.cn/Article/details/gt2vqkydrjg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cucudq.cn/Article/details/gt2eakxpkfa.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hywenlv.cn/Article/details/gt2qeqniijn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cusdiohg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.pycfn.com/Article/details/gt2budmmxgd.html

Ruby: a.gcd(b)
来源：http://dali.ppjwa.cn/Article/details/gt2thbbuqqc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.0kj1m.cn/Article/details/gt2erbbecuz.html

[N06] 判断回文字符串
来源：http://dali.c1oappe.top/Article/details/gt2yiteuatu.html

Py:   s == s[::-1]
来源：http://dali.c1oappe.top/Article/details/gt2uxrtzynk.html

PHP:  $s === strrev($s);
来源：http://dali.jinqigufen.top/Article/details/gt2ooymsdiv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gt2wszjpxyb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gt2jcgxxehl.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.wangdashe.top/Article/details/gt2wagpefqc.html

Go:   // 双指针从两端比较
来源：http://dali.haohaochexian.top/Article/details/gt2xcvbhfoq.html

Ruby: s == s.reverse
来源：http://dali.aibaodan.cn/Article/details/gt2aesczarj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ppjwa.cn/Article/details/gt2ohzgevxb.html

[N07] 两数之和（返回下标）
来源：http://dali.yongpay.top/Article/details/gt2aofoesqr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.snrcjt.cn/Article/details/gt2ezwbuquf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bffgmren.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zdqjudy.top/Article/details/gt2ixxxfiyx.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oopqulfo.html

Java: // 手写 HashMap
来源：http://dali.svipenyu.cn/Article/details/gt2efedsafa.html

Go:   // 手写 map[int]int
来源：http://dali.316326.xyz/Article/details/gt2sknvlkib.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2svlonags.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.quarkkingdee.top/Article/details/gt2donmgnfw.html

[N08] 生成全排列
来源：http://dali.pycfn.com/Article/details/gt2gsjzogbw.html

Py:   itertools.permutations(arr)
来源：http://dali.havefunace.top/Article/details/gt2svdzvpth.html

PHP:  // 手写递归交换
来源：http://dali.hnxiangtu.top/Article/details/gt2iuqhkwsj.html

JS:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gt2hrrgyktp.html

TS:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gt2lqwpqxwn.html

Java: // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gt2gxfmucct.html

Go:   // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gt2pjtpkndu.html

Ruby: arr.permutation.to_a
来源：http://dali.iojbl.cn/Article/details/gt2pxpxzvwh.html

C#:   // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gt2awjrwctm.html

[N09] 栈与队列
来源：http://dali.xuetiantiany.cn/Article/details/gt2dlunwyor.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.havefunace.top/Article/details/gt2xjercbhv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.aizwys.cn/Article/details/gt2rzfcteke.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xziqi.cn/Article/details/gt2qpszifnc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhoulong.xyz/Article/details/gt2qzkjglwy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zdqjudy.top/Article/details/gt2xdcimzft.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.fzhhl.top/Article/details/gt2iewjwvdg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.bjfxy.top/Article/details/gt2umunttil.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.birdmap.top/Article/details/gt2ijkksivn.html

[N10] 链表节点定义
来源：http://dali.bjfxy.top/Article/details/gt2kwhgtyii.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ybcxt.top/Article/details/gt2itbwbxej.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqgfaoi.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.0kj1m.cn/Article/details/gt2qtzyalyx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.wangdashe.top/Article/details/gt2fjrvytmq.html

Java: class Node { int v; Node next; }
来源：http://dali.sweek.top/Article/details/gt2mhuxggcx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.quarkkingdee.top/Article/details/gt2nwcdxvoy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zdqjudy.top/Article/details/gt2xytszvlf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jiagoushi.top/Article/details/gt2kayfnzwy.html

[N11] 二叉树中序遍历
来源：http://dali.cheryme.top/Article/details/gt2smpdtigi.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.9152youxi.cn/Article/details/gt2lzylkvsh.html

PHP:  // 手写递归函数
来源：http://dali.dianchejie.cn/Article/details/gt2ulxirbef.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.fzhhl.top/Article/details/gt2fucnvaeh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hammf.cn/Article/details/gt2shdkbgby.html

Java: // 手写递归
来源：http://dali.zhengqikj.top/Article/details/gt2rctibzqs.html

Go:   // 手写递归
来源：http://dali.havefunace.top/Article/details/gt2rxfrahka.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jqgufenzy.top/Article/details/gt2rhevjgrn.html

C#:   // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gt2xdxdavjl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.svipenyu.cn/Article/details/gt2xpxfswdt.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yonumen.top/Article/details/gt2jefbeevl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ivvv.top/Article/details/gt2axekcifk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xlpuylba.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cucudq.cn/Article/details/gt2tddecxgp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nboijsfj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jlsjyb.cn/Article/details/gt2ogsrowvt.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jianghu66.top/Article/details/gt2jgzfgfdx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.dashuyun.cn/Article/details/gt2ujkwilcw.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2noqgoqwp.html

O. 并发与异步
来源：http://dali.iojbl.cn/Article/details/gt2xiedgwjp.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2yvcmouha.html

[O01] 启动一个线程
来源：http://dali.havefunace.top/Article/details/gt2kjvffbit.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2opezhkld.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shuidangran.top/Article/details/gt2tpbqhmpx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhongyouzk.top/Article/details/gt2kaaesbax.html

TS:   // 同 JS
来源：http://dali.birdmap.top/Article/details/gt2dmcvjttx.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhiwuduotai.top/Article/details/gt2zhchulqs.html

Go:   go f()
来源：http://dali.hfpthk.cn/Article/details/gt2zuizjteb.html

Ruby: Thread.new { f }
来源：http://dali.ybcxt.top/Article/details/gt2sktqcyhg.html

C#:   Task.Run(() => F());
来源：http://dali.hywenlv.cn/Article/details/gt2ljacgary.html

[O02] 使用线程池
来源：http://dali.zhengqikj.top/Article/details/gt2vdmjvuan.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yanxiufei.cn/Article/details/gt2dpxxbtyu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jiagoushi.top/Article/details/gt2kabnvvxe.html

JS:   // worker_threads 线程池
来源：http://dali.cucudq.cn/Article/details/gt2ycxjiasp.html

TS:   // worker_threads 线程池
来源：http://dali.sweek.top/Article/details/gt2fxrnyxwb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.9152youxi.cn/Article/details/gt2vwfvggcv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jinqigfzy.top/Article/details/gt2soefpiyo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ybcxt.top/Article/details/gt2lvvurwrp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.nanxinkj.top/Article/details/gt2utgyjyum.html

[O03] 加锁保护共享数据
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zkqxuedj.html

Py:   with lock: shared += 1
来源：http://dali.shuidangran.top/Article/details/gt2jwaksqot.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.vqdsnc.cn/Article/details/gt2opggzmfb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.svipenyu.cn/Article/details/gt2skpxupir.html

TS:   // 同 JS
来源：http://dali.andypj.xyz/Article/details/gt2unhqspoy.html

Java: synchronized (this) { shared++; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2jqkydtki.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.daria6918.cn/Article/details/gt2befeaydy.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhoulong.xyz/Article/details/gt2doonqcge.html

C#:   lock (gate) { shared++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xzkcrlyp.html

[O04] 定义异步函数并等待
来源：http://dali.yanxiufei.cn/Article/details/gt2hqcptdof.html

Py:   async def f():⏎    await g()
来源：http://dali.zhongyouzk.top/Article/details/gt2efonbwgt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.birdmap.top/Article/details/gt2rxqnltth.html

JS:   async function f() { await g(); }
来源：http://dali.jyoumei.cn/Article/details/gt2hmkpzcor.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gogol.net.cn/Article/details/gt2skvwcosh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xuanzx.com/Article/details/gt2wjhlkdte.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj202588.top/Article/details/gt2fqtruclv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jlsjyb.cn/Article/details/gt2ilrdxiya.html

C#:   async Task F() { await G(); }
来源：http://dali.shuidangran.top/Article/details/gt2ggprowsi.html

[O05] 并发执行并等待全部完成
来源：http://dali.svipenyu.cn/Article/details/gt2bjhvcmxe.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shzxlz.cn/Article/details/gt2iziykfmr.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.wangdashe.top/Article/details/gt2rixcrmtm.html

JS:   await Promise.all(tasks)
来源：http://dali.aibaodan.cn/Article/details/gt2svblhwnb.html

TS:   await Promise.all(tasks)
来源：http://dali.hysaishi.cn/Article/details/gt2ocjkyiri.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yuxming.cn/Article/details/gt2tcsofxas.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.pycfn.com/Article/details/gt2xnvcnvhb.html

Ruby: threads.map(&:join)
来源：http://dali.bjfxy.top/Article/details/gt2ibgzqmjh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xqhypulp.html

[O06] 使用进程池
来源：http://dali.cheryme.top/Article/details/gt2aduwckbw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.chenjidiqi.icu/Article/details/gt2jxuscngz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cucudq.cn/Article/details/gt2akywmtdo.html

JS:   // child_process / cluster 模块
来源：http://dali.snrcjt.cn/Article/details/gt2yvwepblb.html

TS:   // child_process / cluster 模块
来源：http://dali.cucudq.cn/Article/details/gt2dagxopnw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.tanke756.top/Article/details/gt2vgcjshpo.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hammf.cn/Article/details/gt2fhwzqdwk.html

Ruby: // fork 块
来源：http://dali.c1oappe.top/Article/details/gt2fpwhjras.html

C#:   Parallel.For
来源：http://dali.xinyue.icu/Article/details/gt2cqblrpci.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2dvzdtfsk.html

P. 常用工具函数
来源：http://dali.nanxuanxn.top/Article/details/gt2erwpvann.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2fczwhinc.html

[P01] 生成 UUID
来源：http://dali.andypj.xyz/Article/details/gt2ffgmmybk.html

Py:   str(uuid.uuid4())
来源：http://dali.gogol.net.cn/Article/details/gt2cojcfqbd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.fzhhl.top/Article/details/gt2oajozwsb.html

JS:   crypto.randomUUID()
来源：http://dali.jiagoushi.top/Article/details/gt2uuxdbnwp.html

TS:   crypto.randomUUID()
来源：http://dali.gzhubu.top/Article/details/gt2bmbmkdxq.html

Java: UUID.randomUUID().toString()
来源：http://dali.fengsongda.top/Article/details/gt2fwhmesvf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.smart0.xyz/Article/details/gt2qizfnqdf.html

Ruby: SecureRandom.uuid
来源：http://dali.xuetiantiany.cn/Article/details/gt2zkketqvz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.sufxvd.cn/Article/details/gt2sejtyhmc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.snrcjt.cn/Article/details/gt2dzukthbk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.haohaochexian.top/Article/details/gt2wglxbxfg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zdqjudy.top/Article/details/gt2xmxttyur.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhoulong.xyz/Article/details/gt2ruutluxa.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinqigfzy.top/Article/details/gt2utttcqrs.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cucudq.cn/Article/details/gt2gbxmkkil.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gzhubu.top/Article/details/gt2hbzyvfzv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cheryme.top/Article/details/gt2lvmuquwv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhiwuduotai.top/Article/details/gt2ievfnlmp.html

[P03] 生成短随机字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jkwdjttv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.9152youxi.cn/Article/details/gt2ugslecqv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.c1oappe.top/Article/details/gt2eexqkqtb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.smart0.xyz/Article/details/gt2rdfoqfar.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.andypj.xyz/Article/details/gt2loisjhyo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhengqikj.top/Article/details/gt2imxrgakp.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.birdmap.top/Article/details/gt2iiuokbqc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.dashuyun.cn/Article/details/gt2rgkwbeqc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhengqikj.top/Article/details/gt2tevdtrdc.html

[P04] 求长度
来源：http://dali.yangfankeji.com/Article/details/gt2hjnugttf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.316326.xyz/Article/details/gt2foiasehg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gt2uvkryerq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj20258.top/Article/details/gt2fmunidgu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guowangkeji.top/Article/details/gt2flkiohnt.html

Java: list.size();  map.size();  s.length()
来源：http://dali.wangdashe.top/Article/details/gt2dkpkssdf.html

Go:   len(arr);  len(m)
来源：http://dali.dianchejie.cn/Article/details/gt2viemoflu.html

Ruby: x.length;  x.size
来源：http://dali.shangyingyoupin.top/Article/details/gt2kviqsmms.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zdqjudy.top/Article/details/gt2qirhguwx.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xinyue.icu/Article/details/gt2eyacflbs.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xuanzx.com/Article/details/gt2tfwnhnjp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.aizwys.cn/Article/details/gt2kpsoqqzy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hammf.cn/Article/details/gt2vseureyf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhongyouzk.top/Article/details/gt2llnuqzdh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zycfv.cn/Article/details/gt2ojwsejzt.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sxryk.cn/Article/details/gt2iajpsntt.html

Ruby: a == b
来源：http://dali.wangdashe.top/Article/details/gt2tevvafdz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cheryme.top/Article/details/gt2lzfolddx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2clrczqdo.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.aizwys.cn/Article/details/gt2zlcjkrfx.html

PHP:  if (empty($x)) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2pkoowlyu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhoulong.xyz/Article/details/gt2ntqbonax.html

TS:   if (x == null) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nosfpccm.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenzaomai.com/Article/details/gt2dcrhzagr.html

Go:   if x == nil {}
来源：http://dali.xuanzx.com/Article/details/gt2bpxtliuj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxnduewn.html

C#:   if (x is null) {}
来源：http://dali.smart0.xyz/Article/details/gt2ltcnqdfi.html

[P07] 防抖与节流
来源：http://dali.cheryme.top/Article/details/gt2vymmhipe.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.nanxuanxn.top/Article/details/gt2anqhzwmg.html

PHP:  // 手写时间戳比较
来源：http://dali.zycfv.cn/Article/details/gt2grmrmndb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yanxiufei.cn/Article/details/gt2qwagrjkf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tanke756.top/Article/details/gt2eavqauyt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ydzc1.top/Article/details/gt2uawzaoxe.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.c1oappe.top/Article/details/gt2rnvkldtd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhengqikj.top/Article/details/gt2xmuqgulv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yongpay.top/Article/details/gt2fvxkdtry.html

[P08] 处理浮点精度问题
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rnjvyikq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hnqzz.top/Article/details/gt2rppxlfrv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.pycfn.com/Article/details/gt2aekqzlxo.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.tanke756.top/Article/details/gt2yspmepov.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhixingplan.top/Article/details/gt2xzrzoesp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yvvmajjp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yonumen.top/Article/details/gt2drnteexz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cqqwz.cn/Article/details/gt2njposzvv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nanxinkj.top/Article/details/gt2pktcmykd.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2gljhceyo.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gogol.net.cn/Article/details/gt2qmpufbbb.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2jxkretuo.html

[Q01] 创建表
来源：http://dali.hfpthk.cn/Article/details/gt2ropidzul.html


<!-- 参考信息 -->