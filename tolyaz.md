代发 wailian999

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.chenjidiqi.icu/Article/details/gt2pivigxll.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jiuxmmgi.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.nanxuanxn.top/Article/details/gt2hrjailmv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.snrcjt.cn/Article/details/gt2jejywzjc.html

[M04] 获取当前工作目录
来源：http://dali.snrcjt.cn/Article/details/gt2jwocwidx.html

Py:   os.getcwd()
来源：http://dali.chenlongwang.top/Article/details/gt2bexbeiye.html

PHP:  getcwd();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hexvwsmj.html

JS:   process.cwd()
来源：http://dali.chenjidiqi.icu/Article/details/gt2hhzuyohp.html

TS:   process.cwd()
来源：http://dali.jinqigufen.top/Article/details/gt2lxatupmx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.mhx1999.top/Article/details/gt2muzkzljh.html

Go:   os.Getwd()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ygkimzvz.html

Ruby: Dir.pwd
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2spkkkaso.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jqgufenzy.top/Article/details/gt2dynmovjg.html

[M05] 设置退出码
来源：http://dali.yongpay.top/Article/details/gt2vcaddils.html

Py:   sys.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rjtfoosd.html

PHP:  exit(1);
来源：http://dali.tanke756.top/Article/details/gt2nudlhgkc.html

JS:   process.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2ygxxyytw.html

TS:   process.exit(1)
来源：http://dali.daxiang520.top/Article/details/gt2wcoervbk.html

Java: System.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gt2iuyudvdz.html

Go:   os.Exit(1)
来源：http://dali.yuxming.cn/Article/details/gt2edkzfrwu.html

Ruby: exit 1
来源：http://dali.hywenlv.cn/Article/details/gt2hehfwtsr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.mhx1999.top/Article/details/gt2wnyqqfcs.html

[M06] 向标准错误输出
来源：http://dali.fzhhl.top/Article/details/gt2rbfnjzpn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhoulong.xyz/Article/details/gt2fkuctezp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.0kj1m.cn/Article/details/gt2rbbrvjnu.html

JS:   console.error("err")
来源：http://dali.sysykeji.top/Article/details/gt2tfexgiam.html

TS:   console.error("err")
来源：http://dali.aibaodan.cn/Article/details/gt2iyxtddfq.html

Java: System.err.println("err")
来源：http://dali.jyoumei.cn/Article/details/gt2tvfnosvc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sxryk.cn/Article/details/gt2kqtstgjl.html

Ruby: warn "err"
来源：http://dali.dianchejie.cn/Article/details/gt2hnsizbgs.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ivhmatqe.html

[M07] 判断是否为主入口
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cgtgucbg.html

Py:   if __name__ == "__main__":
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qoqwjtov.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yonumen.top/Article/details/gt2glvlnive.html

JS:   require.main === module
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cnzwsqup.html

TS:   require.main === module
来源：http://dali.xuetiantiany.cn/Article/details/gt2cgmwriew.html

Java: public static void main(String[] args)
来源：http://dali.aizwys.cn/Article/details/gt2ccvavsoc.html

Go:   func main()
来源：http://dali.jlsjyb.cn/Article/details/gt2sfyrbfzo.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yongpay.top/Article/details/gt2jhjqctws.html

C#:   static void Main(string[] args)
来源：http://dali.haohaochexian.top/Article/details/gt2fcuiqyox.html

[M08] 获取系统与运行时信息
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dhesirsi.html

Py:   platform.system();  platform.python_version()
来源：http://dali.redwolf501.top/Article/details/gt2ocghfnfw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xziqi.cn/Article/details/gt2viosbvdf.html

JS:   process.platform;  process.version
来源：http://dali.cheryme.top/Article/details/gt2hpipqctg.html

TS:   process.platform;  process.version
来源：http://dali.sweek.top/Article/details/gt2mkrdzicb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.feifeiyinyue.top/Article/details/gt2dhetcylo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yonumen.top/Article/details/gt2hkafnkqg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.snrcjt.cn/Article/details/gt2oflplttm.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ehwqpu.com/Article/details/gt2jkhhcspl.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2ucbjaksv.html

N. 数据结构与算法
来源：http://dali.iojbl.cn/Article/details/gt2biuytsmd.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2ztooflns.html

[N01] 二分查找（有序数组）
来源：http://dali.dianchejie.cn/Article/details/gt2snkgfiab.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2adernbrw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.guannengcc.top/Article/details/gt2hiezesum.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj202588.top/Article/details/gt2ucawjhbg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gt2skhfoisc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gt2davvynfn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2foeyqsru.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gogol.net.cn/Article/details/gt2kowllpbr.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gzhubu.top/Article/details/gt2aksqznjj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lzpcyiza.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jyoumei.cn/Article/details/gt2cqrjmkgx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gt2maddgisd.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xinyue.icu/Article/details/gt2uccxqadh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nwbrower.top/Article/details/gt2hplhahqx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yangfankeji.com/Article/details/gt2kxirugeh.html

Go:   slices.Sort(arr)
来源：http://dali.andypj.xyz/Article/details/gt2qbefkiik.html

Ruby: arr.sort
来源：http://dali.jyoumei.cn/Article/details/gt2sbmzmjvm.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.meibo888.top/Article/details/gt2wkfuyelq.html

[N03] 快速排序（分治示例）
来源：http://dali.ppjwa.cn/Article/details/gt2acftxvav.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2skyfsfne.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhengqikj.top/Article/details/gt2loqfkesj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tianlin.xyz/Article/details/gt2imyibrcg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.kuanghao11.cn/Article/details/gt2crbmiufi.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.tanke756.top/Article/details/gt2gegjiemc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhengqikj.top/Article/details/gt2wyysuyju.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ttvmdski.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cucudq.cn/Article/details/gt2xqjepzso.html

[N04] 斐波那契数列
来源：http://dali.mhx1999.top/Article/details/gt2disajgpa.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xylfe.cn/Article/details/gt2swfykrjy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cheryme.top/Article/details/gt2ihxgpftu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gt2pqsuccqg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tanke756.top/Article/details/gt2yivfkegg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zdqjudy.top/Article/details/gt2konedoob.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jianghu66.top/Article/details/gt2ziavtjpk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yongpay.top/Article/details/gt2rjyuoqvl.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shangyingyoupin.top/Article/details/gt2hlakrynr.html

[N05] 最大公约数
来源：http://dali.jinqigufen.top/Article/details/gt2zloaeiba.html

Py:   math.gcd(a, b)
来源：http://dali.ivvv.top/Article/details/gt2jclhcndp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jqgufenzy.top/Article/details/gt2qicuofbm.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hammf.cn/Article/details/gt2tscqjrhc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.birdmap.top/Article/details/gt2izfdrrdb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.dashuyun.cn/Article/details/gt2kdmdovut.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yuxming.cn/Article/details/gt2ebinngvg.html

Ruby: a.gcd(b)
来源：http://dali.fzhhl.top/Article/details/gt2jaqlagar.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.tanke756.top/Article/details/gt2tqgjkyzl.html

[N06] 判断回文字符串
来源：http://dali.cqqwz.cn/Article/details/gt2hvbxyedh.html

Py:   s == s[::-1]
来源：http://dali.wangshuangyany.cn/Article/details/gt2mdmeqilp.html

PHP:  $s === strrev($s);
来源：http://dali.hywenlv.cn/Article/details/gt2pyglizhy.html

JS:   s === [...s].reverse().join("")
来源：http://dali.feifeiyinyue.top/Article/details/gt2mpthvpnn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gt2xpglicwc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yonumen.top/Article/details/gt2snkesgzq.html

Go:   // 双指针从两端比较
来源：http://dali.ivvv.top/Article/details/gt2baudgwgn.html

Ruby: s == s.reverse
来源：http://dali.tian-w.cn/Article/details/gt2pvupgboh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhengqikj.top/Article/details/gt2outdavxy.html

[N07] 两数之和（返回下标）
来源：http://dali.pycfn.com/Article/details/gt2hhkvhebb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shangyingyoupin.top/Article/details/gt2lgavplle.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cucudq.cn/Article/details/gt2ucyatdkm.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oktemqqq.html

TS:   // 手写 Map<string, number>
来源：http://dali.0kj1m.cn/Article/details/gt2gkctklbx.html

Java: // 手写 HashMap
来源：http://dali.tianlin.xyz/Article/details/gt2kwkbmyid.html

Go:   // 手写 map[int]int
来源：http://dali.hnxiangtu.top/Article/details/gt2hzqtlmfu.html

Ruby: // 手写 Hash
来源：http://dali.nanxinkj.top/Article/details/gt2vvhozdgd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.aizwys.cn/Article/details/gt2xnnnxdqg.html

[N08] 生成全排列
来源：http://dali.kuanghao11.cn/Article/details/gt2wjijgdph.html

Py:   itertools.permutations(arr)
来源：http://dali.316326.xyz/Article/details/gt2sesskkdw.html

PHP:  // 手写递归交换
来源：http://dali.0kj1m.cn/Article/details/gt2pcrtxrme.html

JS:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gt2tdhhuhjd.html

TS:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2muhlllsb.html

Java: // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gt2klihxxci.html

Go:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gt2fcgineyq.html

Ruby: arr.permutation.to_a
来源：http://dali.hfpthk.cn/Article/details/gt2qnhaxpww.html

C#:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gt2rcozifyc.html

[N09] 栈与队列
来源：http://dali.chenzaomai.com/Article/details/gt2yxzicazj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gt2yzquiuyg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenzaomai.com/Article/details/gt2jcbamubv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gt2repipvxx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.sufxvd.cn/Article/details/gt2jvfnhxuz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hnxiangtu.top/Article/details/gt2ipuwkkto.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.snrcjt.cn/Article/details/gt2vqplarch.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinqigfzy.top/Article/details/gt2epkrxfuy.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yvedp.cn/Article/details/gt2lzdmpoqg.html

[N10] 链表节点定义
来源：http://dali.sweek.top/Article/details/gt2kulpjkbf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zycfv.cn/Article/details/gt2lxnpkfyz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cashguo.top/Article/details/gt2mxbeysog.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hfpthk.cn/Article/details/gt2psnlxpmw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gogol.net.cn/Article/details/gt2gzocmmxb.html

Java: class Node { int v; Node next; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gakpvmtq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.kuanghao11.cn/Article/details/gt2qhpaonil.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hywenlv.cn/Article/details/gt2bfmtjuaj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zycfv.cn/Article/details/gt2owfdovjg.html

[N11] 二叉树中序遍历
来源：http://dali.kuanghao11.cn/Article/details/gt2kxgczqis.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.dianchejie.cn/Article/details/gt2yhgnoxuo.html

PHP:  // 手写递归函数
来源：http://dali.cheryme.top/Article/details/gt2tcivrzgm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cdnleiting.top/Article/details/gt2gsntbvcg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ydzc1.top/Article/details/gt2aihreqye.html

Java: // 手写递归
来源：http://dali.yueranfly.top/Article/details/gt2djkofrya.html

Go:   // 手写递归
来源：http://dali.cucudq.cn/Article/details/gt2inxkzydd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhixingplan.top/Article/details/gt2oaczquxq.html

C#:   // 手写递归
来源：http://dali.gzhubu.top/Article/details/gt2iaozntxf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.pycfn.com/Article/details/gt2masoowrk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.iojbl.cn/Article/details/gt2doizticx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.nanxinkj.top/Article/details/gt2asrftbgh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xuetiantiany.cn/Article/details/gt2hessndil.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.redwolf501.top/Article/details/gt2vqgxukgj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.haohaochexian.top/Article/details/gt2amghwaks.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.guowangkeji.top/Article/details/gt2gejgtslh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ivvv.top/Article/details/gt2lufnwqba.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.vqdsnc.cn/Article/details/gt2coioccsg.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2gpfxsbma.html

O. 并发与异步
来源：http://dali.fengsongda.top/Article/details/gt2ldfgbgtw.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2evrcgzyb.html

[O01] 启动一个线程
来源：http://dali.jinqigfzy.top/Article/details/gt2kvchceyd.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cdnleiting.top/Article/details/gt2vrxzjgoj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.daxiang520.top/Article/details/gt2gjkezyxo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ybcxt.top/Article/details/gt2kjdvtzgu.html

TS:   // 同 JS
来源：http://dali.meibo888.top/Article/details/gt2vwfburlc.html

Java: new Thread(() -> f()).start()
来源：http://dali.kuanghao11.cn/Article/details/gt2hkzevbew.html

Go:   go f()
来源：http://dali.daria6918.cn/Article/details/gt2uzbfmcrc.html

Ruby: Thread.new { f }
来源：http://dali.cashguo.top/Article/details/gt2thyywceg.html

C#:   Task.Run(() => F());
来源：http://dali.cheryme.top/Article/details/gt2wmztbmlm.html

[O02] 使用线程池
来源：http://dali.guannengcc.top/Article/details/gt2dhkxdztb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhongyouzk.top/Article/details/gt2rnwnglkd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jqgfzy.top/Article/details/gt2bbmwoxvq.html

JS:   // worker_threads 线程池
来源：http://dali.aizwys.cn/Article/details/gt2lootiaih.html

TS:   // worker_threads 线程池
来源：http://dali.xinyue.icu/Article/details/gt2ixwwqwkp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.feifeiyinyue.top/Article/details/gt2hkekzeua.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.316326.xyz/Article/details/gt2crwbwidb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jinqigfzy.top/Article/details/gt2fpaiggqi.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yj202588.top/Article/details/gt2rqmvcgcx.html

[O03] 加锁保护共享数据
来源：http://dali.ydzc1.top/Article/details/gt2gkrishrq.html

Py:   with lock: shared += 1
来源：http://dali.hfpthk.cn/Article/details/gt2rgiqmgno.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gaohongyu789.top/Article/details/gt2hyplzjsj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.iojbl.cn/Article/details/gt2hkwsiqgc.html

TS:   // 同 JS
来源：http://dali.nanxinkj.top/Article/details/gt2qyqcksij.html

Java: synchronized (this) { shared++; }
来源：http://dali.sxryk.cn/Article/details/gt2wkplbsba.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hysaishi.cn/Article/details/gt2zqelcnzc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.vqdsnc.cn/Article/details/gt2xfealltl.html

C#:   lock (gate) { shared++; }
来源：http://dali.shzxlz.cn/Article/details/gt2rupkkdcl.html

[O04] 定义异步函数并等待
来源：http://dali.guowangkeji.top/Article/details/gt2najwaqbf.html

Py:   async def f():⏎    await g()
来源：http://dali.aibaodan.cn/Article/details/gt2nqljubhn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.wangdashe.top/Article/details/gt2rhxhocnt.html

JS:   async function f() { await g(); }
来源：http://dali.yj20258888.top/Article/details/gt2dwtdlkag.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.nanxinkj.top/Article/details/gt2zfpozmfj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ydzc1.top/Article/details/gt2bkcibwae.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yuanzhike.top/Article/details/gt2prwtzate.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.daxiang520.top/Article/details/gt2dzecafva.html

C#:   async Task F() { await G(); }
来源：http://dali.iojbl.cn/Article/details/gt2itlyordr.html

[O05] 并发执行并等待全部完成
来源：http://dali.jyoumei.cn/Article/details/gt2yrowslmk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xuanzx.com/Article/details/gt2rimagyso.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jqgfzy.top/Article/details/gt2ofvecour.html

JS:   await Promise.all(tasks)
来源：http://dali.hysaishi.cn/Article/details/gt2yibduvwh.html

TS:   await Promise.all(tasks)
来源：http://dali.kuanghao11.cn/Article/details/gt2ovvbqsgm.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jyoumei.cn/Article/details/gt2vuojsuyk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.meibo888.top/Article/details/gt2zxxdxnbc.html

Ruby: threads.map(&:join)
来源：http://dali.0kj1m.cn/Article/details/gt2kdlodile.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yuanzhike.top/Article/details/gt2dkubpnvx.html

[O06] 使用进程池
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cvqvqavk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhiwuduotai.top/Article/details/gt2csiscpmv.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cqqwz.cn/Article/details/gt2bmnbdmoc.html

JS:   // child_process / cluster 模块
来源：http://dali.yonumen.top/Article/details/gt2zowuksuo.html

TS:   // child_process / cluster 模块
来源：http://dali.nwbrower.top/Article/details/gt2yuqpxmhz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zycfv.cn/Article/details/gt2eqbtyenh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.c1oappe.top/Article/details/gt2hlmhcran.html

Ruby: // fork 块
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tewjglts.html

C#:   Parallel.For
来源：http://dali.tianlin.xyz/Article/details/gt2peqgdaqv.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2oohfycif.html

P. 常用工具函数
来源：http://dali.redwolf501.top/Article/details/gt2qamqalaa.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2dysmrkhd.html

[P01] 生成 UUID
来源：http://dali.yj202588.top/Article/details/gt2nfhpdcoz.html

Py:   str(uuid.uuid4())
来源：http://dali.wangdashe.top/Article/details/gt2nkngfaiv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.birdmap.top/Article/details/gt2xzzyelnl.html

JS:   crypto.randomUUID()
来源：http://dali.iojbl.cn/Article/details/gt2fsmlywjo.html

TS:   crypto.randomUUID()
来源：http://dali.zycfv.cn/Article/details/gt2gcqewuxm.html

Java: UUID.randomUUID().toString()
来源：http://dali.yj20258888.top/Article/details/gt2yjqmskzg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yueranfly.top/Article/details/gt2bgrcrqjv.html

Ruby: SecureRandom.uuid
来源：http://dali.ivvv.top/Article/details/gt2orojipcr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.sysykeji.top/Article/details/gt2zvxedlxy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.redwolf501.top/Article/details/gt2wafzzjbt.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iiaiywsj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ppjwa.cn/Article/details/gt2kpzjkamm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.chenlongwang.top/Article/details/gt2cvvxtvhz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cqqwz.cn/Article/details/gt2gouuatdv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.daria6918.cn/Article/details/gt2qaakvchv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.birdmap.top/Article/details/gt2naarfjlq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hvnokkzb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cheryme.top/Article/details/gt2nljdocih.html

[P03] 生成短随机字符串
来源：http://dali.9152youxi.cn/Article/details/gt2viawceen.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cucudq.cn/Article/details/gt2rcgxjrge.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jqgfzy.top/Article/details/gt2wutttnwc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jlsjyb.cn/Article/details/gt2yprfrjgj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jianghu66.top/Article/details/gt2vfzycjqw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.chenzaomai.com/Article/details/gt2qzymaafm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cqqwz.cn/Article/details/gt2aeishmal.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.svipenyu.cn/Article/details/gt2ccezweej.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ivvv.top/Article/details/gt2lezwwypg.html

[P04] 求长度
来源：http://dali.xziqi.cn/Article/details/gt2jfmhykoe.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hnxiangtu.top/Article/details/gt2audfbxjv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.c1oappe.top/Article/details/gt2uqgjvuxf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hnxiangtu.top/Article/details/gt2omweogri.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.snrcjt.cn/Article/details/gt2cgmchjeu.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xlbkfckx.html

Go:   len(arr);  len(m)
来源：http://dali.yueranfly.top/Article/details/gt2pbpfvjqd.html

Ruby: x.length;  x.size
来源：http://dali.quarkkingdee.top/Article/details/gt2pposcjbg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cashguo.top/Article/details/gt2puwonlll.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ybcxt.top/Article/details/gt2ycuaslat.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yanxiufei.cn/Article/details/gt2lsmyrwef.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yj202588.top/Article/details/gt2aisskgry.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.iojbl.cn/Article/details/gt2bqrkwojq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.wangdashe.top/Article/details/gt2jpadgaum.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ppjwa.cn/Article/details/gt2xiynunjc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.bjfxy.top/Article/details/gt2ynvgrvex.html

Ruby: a == b
来源：http://dali.yuanzhike.top/Article/details/gt2wrhcqdux.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.0kj1m.cn/Article/details/gt2ljqbefer.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zdqjudy.top/Article/details/gt2nrsyzpex.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cucudq.cn/Article/details/gt2fjmmjgic.html

PHP:  if (empty($x)) {}
来源：http://dali.sxryk.cn/Article/details/gt2innfbhdh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.fzhhl.top/Article/details/gt2fnnglkfb.html

TS:   if (x == null) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2rmrugkjh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.0kj1m.cn/Article/details/gt2jjwwhtss.html

Go:   if x == nil {}
来源：http://dali.dianchejie.cn/Article/details/gt2fxhdkvcx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.mhx1999.top/Article/details/gt2nbxqsayn.html

C#:   if (x is null) {}
来源：http://dali.xuanzx.com/Article/details/gt2nlmxwtop.html

[P07] 防抖与节流
来源：http://dali.havefunace.top/Article/details/gt2tcjszqzh.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.tian-w.cn/Article/details/gt2gbprusqi.html

PHP:  // 手写时间戳比较
来源：http://dali.yanxiufei.cn/Article/details/gt2vadvgvzt.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.c1oappe.top/Article/details/gt2yahfowhg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tian-w.cn/Article/details/gt2iusrkxzr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.havefunace.top/Article/details/gt2nzynpwpx.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.haohaochexian.top/Article/details/gt2iekonnoa.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.sweek.top/Article/details/gt2wmgqetpx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hysaishi.cn/Article/details/gt2glujzvwy.html

[P08] 处理浮点精度问题
来源：http://dali.snrcjt.cn/Article/details/gt2qjdnxpjp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.havefunace.top/Article/details/gt2pqisfvkz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.sysykeji.top/Article/details/gt2yvxrgxfw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.tian-w.cn/Article/details/gt2jeckduzm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.svipenyu.cn/Article/details/gt2sqanvumv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shzxlz.cn/Article/details/gt2gvylqypf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hnqzz.top/Article/details/gt2irdlptov.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhengqikj.top/Article/details/gt2kwlibhqp.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jyoumei.cn/Article/details/gt2pehinxat.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2cpbqoctl.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.andypj.xyz/Article/details/gt2ldbwbtgm.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2sjhtnwif.html

[Q01] 创建表
来源：http://dali.gotoacloud.top/Article/details/gt2qkxoqtni.html

CREATE TABLE users (
来源：http://dali.yongpay.top/Article/details/gt2hwifhwph.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuxming.cn/Article/details/gt2xmtvxhuw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dwebqhag.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jlsjyb.cn/Article/details/gt2eeblqgat.html


<!-- 参考信息 -->