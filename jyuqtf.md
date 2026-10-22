代发 wailian999

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinqigfzy.top/Article/details/gt2wcamltym.html

[M05] 设置退出码
来源：http://dali.mhx1999.top/Article/details/gt2vvyylsru.html

Py:   sys.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gt2owcysgqx.html

PHP:  exit(1);
来源：http://dali.svipenyu.cn/Article/details/gt2csaouuuc.html

JS:   process.exit(1)
来源：http://dali.iojbl.cn/Article/details/gt2pdkbblqg.html

TS:   process.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gt2tgwaxpui.html

Java: System.exit(1)
来源：http://dali.mhx1999.top/Article/details/gt2rcajkpjc.html

Go:   os.Exit(1)
来源：http://dali.yuxming.cn/Article/details/gt2lwueecew.html

Ruby: exit 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fcpfxxea.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.quarkkingdee.top/Article/details/gt2dkejhsdk.html

[M06] 向标准错误输出
来源：http://dali.svipenyu.cn/Article/details/gt2ctpsqccl.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2dcfpuogp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.fzhhl.top/Article/details/gt2xdkfexda.html

JS:   console.error("err")
来源：http://dali.jyoumei.cn/Article/details/gt2ktoxzdgk.html

TS:   console.error("err")
来源：http://dali.tian-w.cn/Article/details/gt2dhqrmcjt.html

Java: System.err.println("err")
来源：http://dali.0kj1m.cn/Article/details/gt2xkxkzchc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pwaamlmb.html

Ruby: warn "err"
来源：http://dali.quarkkingdee.top/Article/details/gt2aiinwtpt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ehwqpu.com/Article/details/gt2ipgjdgvl.html

[M07] 判断是否为主入口
来源：http://dali.nanxinkj.top/Article/details/gt2ypbujura.html

Py:   if __name__ == "__main__":
来源：http://dali.hywenlv.cn/Article/details/gt2iyzmoglr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2enfuekoq.html

JS:   require.main === module
来源：http://dali.cdnleiting.top/Article/details/gt2wftwsrqr.html

TS:   require.main === module
来源：http://dali.tanke756.top/Article/details/gt2iwqxjyvi.html

Java: public static void main(String[] args)
来源：http://dali.tian-w.cn/Article/details/gt2hvbhlrth.html

Go:   func main()
来源：http://dali.aizwys.cn/Article/details/gt2cergzxvw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jlsjyb.cn/Article/details/gt2kgqbaand.html

C#:   static void Main(string[] args)
来源：http://dali.zhengqikj.top/Article/details/gt2syhmfrev.html

[M08] 获取系统与运行时信息
来源：http://dali.tianlin.xyz/Article/details/gt2szotkmxv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jqgfzy.top/Article/details/gt2pqxbclgx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.haohaochexian.top/Article/details/gt2vxxdfiwb.html

JS:   process.platform;  process.version
来源：http://dali.cashguo.top/Article/details/gt2zrcfttwe.html

TS:   process.platform;  process.version
来源：http://dali.bjfxy.top/Article/details/gt2kiqcufmc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hfpthk.cn/Article/details/gt2sjprlxqv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cdnleiting.top/Article/details/gt2vvpdxjua.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.nwbrower.top/Article/details/gt2pxctlpsq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yonumen.top/Article/details/gt2jtfcrokr.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2eqjzxfon.html

N. 数据结构与算法
来源：http://dali.sysykeji.top/Article/details/gt2yuxluczb.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2qctskdhq.html

[N01] 二分查找（有序数组）
来源：http://dali.xylfe.cn/Article/details/gt2dzwgwdsh.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sysykeji.top/Article/details/gt2ydzvgzkd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2diridgyc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dianchejie.cn/Article/details/gt2oqibimry.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.kuanghao11.cn/Article/details/gt2nogsarcu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.pycfn.com/Article/details/gt2gxkckpee.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gt2zvjhdito.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.vqdsnc.cn/Article/details/gt2qrhbuzgj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ynggqwib.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.bjfxy.top/Article/details/gt2nbbpagne.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sufxvd.cn/Article/details/gt2xoraoopi.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jqgufenzy.top/Article/details/gt2oisrhhoq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sufxvd.cn/Article/details/gt2lyiwruir.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jyoumei.cn/Article/details/gt2icchuehc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.meibo888.top/Article/details/gt2pckyfoom.html

Go:   slices.Sort(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2oczqlghh.html

Ruby: arr.sort
来源：http://dali.guowangkeji.top/Article/details/gt2qkhghwat.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yj20258888.top/Article/details/gt2ssshywgz.html

[N03] 快速排序（分治示例）
来源：http://dali.wangshuangyany.cn/Article/details/gt2tkxifgwf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhengqikj.top/Article/details/gt2xsrukjvr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tian-w.cn/Article/details/gt2yyjnfitg.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.smart0.xyz/Article/details/gt2soygopwi.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.feifeiyinyue.top/Article/details/gt2gxoapbss.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hammf.cn/Article/details/gt2udjgstfx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sweek.top/Article/details/gt2catnfnfr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tian-w.cn/Article/details/gt2cwbiqkjm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.aizwys.cn/Article/details/gt2dcbfekhl.html

[N04] 斐波那契数列
来源：http://dali.haohaochexian.top/Article/details/gt2ojkbcbjf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sxryk.cn/Article/details/gt2tfkcqldt.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yuanzhike.top/Article/details/gt2plcadpjm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxuanxn.top/Article/details/gt2oogkgmpm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxuanxn.top/Article/details/gt2btkfjqsi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hywenlv.cn/Article/details/gt2blitrlem.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shangyingyoupin.top/Article/details/gt2xaptrfah.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258.top/Article/details/gt2mogrshiv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yuxming.cn/Article/details/gt2nvwlwvpy.html

[N05] 最大公约数
来源：http://dali.nanxuanxn.top/Article/details/gt2zxqoddjc.html

Py:   math.gcd(a, b)
来源：http://dali.fengsongda.top/Article/details/gt2cotcbqru.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.c1oappe.top/Article/details/gt2krotfmww.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xylfe.cn/Article/details/gt2elhvietg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuanzx.com/Article/details/gt2ttfooofs.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.kuanghao11.cn/Article/details/gt2grmtzbfv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wjiaolsq.html

Ruby: a.gcd(b)
来源：http://dali.zdqjudy.top/Article/details/gt2vnjbwlsy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.haohaochexian.top/Article/details/gt2vcuowjtp.html

[N06] 判断回文字符串
来源：http://dali.wangdashe.top/Article/details/gt2oaaubjtg.html

Py:   s == s[::-1]
来源：http://dali.ybcxt.top/Article/details/gt2azijfort.html

PHP:  $s === strrev($s);
来源：http://dali.zhixingplan.top/Article/details/gt2bqxvecvl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gt2omhluync.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gt2kyhikvgk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sxryk.cn/Article/details/gt2pteirlgr.html

Go:   // 双指针从两端比较
来源：http://dali.quarkkingdee.top/Article/details/gt2fjzowohm.html

Ruby: s == s.reverse
来源：http://dali.tanke756.top/Article/details/gt2acvhzleg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.mhx1999.top/Article/details/gt2wfiyvswr.html

[N07] 两数之和（返回下标）
来源：http://dali.hfpthk.cn/Article/details/gt2wehiuicq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.mhx1999.top/Article/details/gt2adttubum.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ydzc1.top/Article/details/gt2gcfhhyuw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xinyue.icu/Article/details/gt2ownhsnsr.html

TS:   // 手写 Map<string, number>
来源：http://dali.jiagoushi.top/Article/details/gt2eiabuvbg.html

Java: // 手写 HashMap
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iutqpfod.html

Go:   // 手写 map[int]int
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qeplgqhq.html

Ruby: // 手写 Hash
来源：http://dali.cdnleiting.top/Article/details/gt2akemocji.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yj20258888.top/Article/details/gt2hnmezqwj.html

[N08] 生成全排列
来源：http://dali.nanxuanxn.top/Article/details/gt2hapokeyo.html

Py:   itertools.permutations(arr)
来源：http://dali.shuidangran.top/Article/details/gt2ukigpdwx.html

PHP:  // 手写递归交换
来源：http://dali.zhengqikj.top/Article/details/gt2qalfckdo.html

JS:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gt2wvylwznk.html

TS:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gt2qaqnrxre.html

Java: // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gt2kssmqkcx.html

Go:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gt2sasmeyet.html

Ruby: arr.permutation.to_a
来源：http://dali.andypj.xyz/Article/details/gt2locjxiss.html

C#:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gt2skidxmcx.html

[N09] 栈与队列
来源：http://dali.fengsongda.top/Article/details/gt2dxvxzkze.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ehwqpu.com/Article/details/gt2vkwcizvw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.316326.xyz/Article/details/gt2logmgmgt.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gzhubu.top/Article/details/gt2yiucbfen.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gzhubu.top/Article/details/gt2ojtbmkok.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.chenlongwang.top/Article/details/gt2xvzjqxxs.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sufxvd.cn/Article/details/gt2tbvisvql.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cdnleiting.top/Article/details/gt2smxbvdzw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hysaishi.cn/Article/details/gt2vtceudxw.html

[N10] 链表节点定义
来源：http://dali.iojbl.cn/Article/details/gt2ctctuggh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hfpthk.cn/Article/details/gt2auhsvqdm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.pycfn.com/Article/details/gt2oaogjdis.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ydzc1.top/Article/details/gt2itvmviej.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinqigufen.top/Article/details/gt2khlxucnt.html

Java: class Node { int v; Node next; }
来源：http://dali.cucudq.cn/Article/details/gt2fgailowo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jqgufenzy.top/Article/details/gt2lgutmwli.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ycvukbnj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hnxiangtu.top/Article/details/gt2xsfsrpjr.html

[N11] 二叉树中序遍历
来源：http://dali.zhiwuduotai.top/Article/details/gt2ikrcqdvk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.aibaodan.cn/Article/details/gt2lopgridf.html

PHP:  // 手写递归函数
来源：http://dali.shuidangran.top/Article/details/gt2cjjohwhy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ppjwa.cn/Article/details/gt2kdxmfghz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tanke756.top/Article/details/gt2nrtaqcom.html

Java: // 手写递归
来源：http://dali.tianlin.xyz/Article/details/gt2onbuinpj.html

Go:   // 手写递归
来源：http://dali.tanke756.top/Article/details/gt2nfamccby.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.c1oappe.top/Article/details/gt2uqqzyqfl.html

C#:   // 手写递归
来源：http://dali.shuidangran.top/Article/details/gt2jijvnysd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.aizwys.cn/Article/details/gt2gyppwycw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gzhubu.top/Article/details/gt2duhwlinu.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.sufxvd.cn/Article/details/gt2ohfvabdx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2senccsao.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ybcxt.top/Article/details/gt2pzoxxkqs.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuetiantiany.cn/Article/details/gt2shpkwwpt.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yj20258.top/Article/details/gt2jxchrpik.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shangyingyoupin.top/Article/details/gt2zihsgbsk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zycfv.cn/Article/details/gt2jwqwdnor.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2jxvaitvc.html

O. 并发与异步
来源：http://dali.xinyue.icu/Article/details/gt2ecjsapox.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2gzugmtof.html

[O01] 启动一个线程
来源：http://dali.aibaodan.cn/Article/details/gt2asefikou.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.svipenyu.cn/Article/details/gt2vsrftvno.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.fzhhl.top/Article/details/gt2hbukcoup.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.guannengcc.top/Article/details/gt2ihftuwom.html

TS:   // 同 JS
来源：http://dali.snrcjt.cn/Article/details/gt2puncssdx.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2odqrvqnj.html

Go:   go f()
来源：http://dali.daria6918.cn/Article/details/gt2dhsywsid.html

Ruby: Thread.new { f }
来源：http://dali.9152youxi.cn/Article/details/gt2rfxjyxso.html

C#:   Task.Run(() => F());
来源：http://dali.andypj.xyz/Article/details/gt2tvqfdzxe.html

[O02] 使用线程池
来源：http://dali.sxryk.cn/Article/details/gt2ucbrvnhw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.pengpengdd.cyou/Article/details/gt2rqgescod.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.aibaodan.cn/Article/details/gt2mdptyrug.html

JS:   // worker_threads 线程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oebtkqrp.html

TS:   // worker_threads 线程池
来源：http://dali.aizwys.cn/Article/details/gt2nhzrsben.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cdnleiting.top/Article/details/gt2eyosuhxd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.0kj1m.cn/Article/details/gt2njyiidnr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.pycfn.com/Article/details/gt2yyohgegg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.nwbrower.top/Article/details/gt2okghahez.html

[O03] 加锁保护共享数据
来源：http://dali.hysaishi.cn/Article/details/gt2ivjvkoem.html

Py:   with lock: shared += 1
来源：http://dali.hnxiangtu.top/Article/details/gt2ppnlmfkf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yonumen.top/Article/details/gt2iovzhoxx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.guowangkeji.top/Article/details/gt2unxocavj.html

TS:   // 同 JS
来源：http://dali.c1oappe.top/Article/details/gt2pvogctxz.html

Java: synchronized (this) { shared++; }
来源：http://dali.yanxiufei.cn/Article/details/gt2bfgaeysm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhixingplan.top/Article/details/gt2qjwnnrlp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.dianchejie.cn/Article/details/gt2slkykxwi.html

C#:   lock (gate) { shared++; }
来源：http://dali.316326.xyz/Article/details/gt2vmhwushq.html

[O04] 定义异步函数并等待
来源：http://dali.ppjwa.cn/Article/details/gt2uwpqywsq.html

Py:   async def f():⏎    await g()
来源：http://dali.gogol.net.cn/Article/details/gt2mbrgdmjc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yj20258888.top/Article/details/gt2ypgbkcti.html

JS:   async function f() { await g(); }
来源：http://dali.yueranfly.top/Article/details/gt2tbiktpfi.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.birdmap.top/Article/details/gt2vapjgnmw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.chenlongwang.top/Article/details/gt2viwjgbcz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zdqjudy.top/Article/details/gt2otzzdjks.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.sxryk.cn/Article/details/gt2uatzujls.html

C#:   async Task F() { await G(); }
来源：http://dali.smart0.xyz/Article/details/gt2rppiizvt.html

[O05] 并发执行并等待全部完成
来源：http://dali.cqqwz.cn/Article/details/gt2viflqqgv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.kuanghao11.cn/Article/details/gt2hlpvogpq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hnqzz.top/Article/details/gt2egowcdbt.html

JS:   await Promise.all(tasks)
来源：http://dali.fzhhl.top/Article/details/gt2wnzfqoch.html

TS:   await Promise.all(tasks)
来源：http://dali.zhiwuduotai.top/Article/details/gt2tqfbklvv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.tian-w.cn/Article/details/gt2ufyfhhfs.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.svipenyu.cn/Article/details/gt2ytmvvwuw.html

Ruby: threads.map(&:join)
来源：http://dali.jlsjyb.cn/Article/details/gt2taxrxejr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sysykeji.top/Article/details/gt2mwrewyvy.html

[O06] 使用进程池
来源：http://dali.gzhubu.top/Article/details/gt2jwlohyqs.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yonumen.top/Article/details/gt2qzyplxzi.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.aibaodan.cn/Article/details/gt2bspgwsdd.html

JS:   // child_process / cluster 模块
来源：http://dali.shzxlz.cn/Article/details/gt2bjncrfbg.html

TS:   // child_process / cluster 模块
来源：http://dali.tanke756.top/Article/details/gt2zvrddwsw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yj202588.top/Article/details/gt2zmctcbxb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shuidangran.top/Article/details/gt2wgkeotjd.html

Ruby: // fork 块
来源：http://dali.sxryk.cn/Article/details/gt2yzybyzxw.html

C#:   Parallel.For
来源：http://dali.shuidangran.top/Article/details/gt2jdhcpsgu.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2skxkurhu.html

P. 常用工具函数
来源：http://dali.sxryk.cn/Article/details/gt2kxjxaond.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2brgbduhd.html

[P01] 生成 UUID
来源：http://dali.guowangkeji.top/Article/details/gt2ryvfdaaw.html

Py:   str(uuid.uuid4())
来源：http://dali.yongpay.top/Article/details/gt2vczzdzue.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.dashuyun.cn/Article/details/gt2wqcbblwr.html

JS:   crypto.randomUUID()
来源：http://dali.shzxlz.cn/Article/details/gt2dmmmfynw.html

TS:   crypto.randomUUID()
来源：http://dali.gogol.net.cn/Article/details/gt2nknesfjk.html

Java: UUID.randomUUID().toString()
来源：http://dali.zdqjudy.top/Article/details/gt2ufqhjmen.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gaohongyu789.top/Article/details/gt2krjfoyit.html

Ruby: SecureRandom.uuid
来源：http://dali.daxiang520.top/Article/details/gt2kuzkjirv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.kuanghao11.cn/Article/details/gt2nllzlwoa.html

[P02] MD5 / SHA256 摘要
来源：http://dali.tanke756.top/Article/details/gt2vclqbyak.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.nwbrower.top/Article/details/gt2hvtwojta.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ipqyyweg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.daxiang520.top/Article/details/gt2ywpubxnh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jqgfzy.top/Article/details/gt2ketizegl.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yanxiufei.cn/Article/details/gt2omyfrzcv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2utaxgwvt.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yongpay.top/Article/details/gt2dikelsas.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.fengsongda.top/Article/details/gt2lbwesoyr.html

[P03] 生成短随机字符串
来源：http://dali.pycfn.com/Article/details/gt2ftlabfcw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yj202588.top/Article/details/gt2obnalpkc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ppjwa.cn/Article/details/gt2fvecvcvn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.wangshuangyany.cn/Article/details/gt2fovwletq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ydzc1.top/Article/details/gt2uaeqaiqa.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xzhubsuz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.tianlin.xyz/Article/details/gt2qfvvhusw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shzxlz.cn/Article/details/gt2qjnfjytn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.9152youxi.cn/Article/details/gt2pufrwaba.html

[P04] 求长度
来源：http://dali.pengpengdd.cyou/Article/details/gt2gcixdkvy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xinyue.icu/Article/details/gt2nknupnvn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yvedp.cn/Article/details/gt2pqnngelr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.mhx1999.top/Article/details/gt2ydzrqvwf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.kuanghao11.cn/Article/details/gt2swjpmzzv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hongshengwenyu.top/Article/details/gt2mvfeosyi.html

Go:   len(arr);  len(m)
来源：http://dali.shuidangran.top/Article/details/gt2zzyrkmqj.html

Ruby: x.length;  x.size
来源：http://dali.sxryk.cn/Article/details/gt2ygdtabya.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.tianlin.xyz/Article/details/gt2ofrjqcai.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xylfe.cn/Article/details/gt2erddesfn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.pycfn.com/Article/details/gt2xpsngueb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.kuanghao11.cn/Article/details/gt2ggasyfnz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yvedp.cn/Article/details/gt2ukeuxyqq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.fzhhl.top/Article/details/gt2ibzziuuc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ppjwa.cn/Article/details/gt2uuylpexz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yuanzhike.top/Article/details/gt2nuisvzmn.html

Ruby: a == b
来源：http://dali.xinyue.icu/Article/details/gt2ughgsbat.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinqigfzy.top/Article/details/gt2jzbtxfuq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ybcxt.top/Article/details/gt2hsoajgyc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jiagoushi.top/Article/details/gt2rdemrvmy.html

PHP:  if (empty($x)) {}
来源：http://dali.jianghu66.top/Article/details/gt2gyxreoua.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ybcxt.top/Article/details/gt2xdnlsujq.html

TS:   if (x == null) {}
来源：http://dali.aizwys.cn/Article/details/gt2qmwpeznb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2hphlikcc.html

Go:   if x == nil {}
来源：http://dali.sufxvd.cn/Article/details/gt2scoqmtwd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.redwolf501.top/Article/details/gt2duicwfux.html

C#:   if (x is null) {}
来源：http://dali.hnqzz.top/Article/details/gt2kwvnbbrx.html

[P07] 防抖与节流
来源：http://dali.cashguo.top/Article/details/gt2gkkxbjow.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.iojbl.cn/Article/details/gt2uqexnxxg.html

PHP:  // 手写时间戳比较
来源：http://dali.jiagoushi.top/Article/details/gt2ygodecoh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hammf.cn/Article/details/gt2tnhzaokl.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ybcxt.top/Article/details/gt2kswvyyth.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hammf.cn/Article/details/gt2brchfvyk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cdnleiting.top/Article/details/gt2zlyggbgm.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nwbrower.top/Article/details/gt2lndmfyvb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhoulong.xyz/Article/details/gt2dglepskj.html

[P08] 处理浮点精度问题
来源：http://dali.xziqi.cn/Article/details/gt2cjyirqev.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.nanxuanxn.top/Article/details/gt2dmcxdkjn.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ixkroyso.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.smart0.xyz/Article/details/gt2nltfasjc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.tianlin.xyz/Article/details/gt2lzrgmcrr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sysykeji.top/Article/details/gt2lqiaabtb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hnqzz.top/Article/details/gt2lwevtzvg.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cdnleiting.top/Article/details/gt2hbfewdzk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hywenlv.cn/Article/details/gt2jydjubtn.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2plmdwtpo.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.bjfxy.top/Article/details/gt2sbvbmecb.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2rtthhagg.html

[Q01] 创建表
来源：http://dali.xuanzx.com/Article/details/gt2otxtnmmg.html

CREATE TABLE users (
来源：http://dali.jqgfzy.top/Article/details/gt2qhdmvevo.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxinkj.top/Article/details/gt2xuwaratd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cashguo.top/Article/details/gt2zxzpifyv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhiwuduotai.top/Article/details/gt2anrogvoh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yangfankeji.com/Article/details/gt2ganqsieq.html

);
来源：http://dali.yueranfly.top/Article/details/gt2qqmapsyy.html

[Q02] 创建带外键的表
来源：http://dali.nanxinkj.top/Article/details/gt2argyvnkl.html

CREATE TABLE orders (
来源：http://dali.kuanghao11.cn/Article/details/gt2mfnhxfbh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sxryk.cn/Article/details/gt2esqzpigh.html

user_id INT NOT NULL,
来源：http://dali.fzhhl.top/Article/details/gt2lrsuduzd.html

amount DECIMAL(10, 2),
来源：http://dali.guowangkeji.top/Article/details/gt2awubsefx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pejamsvz.html

);
来源：http://dali.gaohongyu789.top/Article/details/gt2dgkxuqjr.html

[Q03] 增加列
来源：http://dali.ydzc1.top/Article/details/gt2tnadpkgx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yanxiufei.cn/Article/details/gt2movzcscp.html

[Q04] 修改列类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lrvjnjzr.html


<!-- 参考信息 -->