代发 wailian999

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjvgjrz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.meibo888.top/Article/details/gt2flrjnlbj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jiagoushi.top/Article/details/gt2uuvwukzt.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhongyouzk.top/Article/details/gt2bahcccdk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.nanxinkj.top/Article/details/gt2eweuffaj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hammf.cn/Article/details/gt2bnpzdgas.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cheryme.top/Article/details/gt2oackzxqo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ppjwa.cn/Article/details/gt2gmztzlir.html

[M04] 获取当前工作目录
来源：http://dali.yvedp.cn/Article/details/gt2jvnypfpm.html

Py:   os.getcwd()
来源：http://dali.iojbl.cn/Article/details/gt2mwzsmrtx.html

PHP:  getcwd();
来源：http://dali.zycfv.cn/Article/details/gt2exkchyrr.html

JS:   process.cwd()
来源：http://dali.daxiang520.top/Article/details/gt2ekufpwuu.html

TS:   process.cwd()
来源：http://dali.havefunace.top/Article/details/gt2nxurvqmd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ghxifjvq.html

Go:   os.Getwd()
来源：http://dali.dianchejie.cn/Article/details/gt2wfdjewdo.html

Ruby: Dir.pwd
来源：http://dali.mhx1999.top/Article/details/gt2tyfbdgip.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ppjwa.cn/Article/details/gt2fbawzkqq.html

[M05] 设置退出码
来源：http://dali.sufxvd.cn/Article/details/gt2zhnkpdfy.html

Py:   sys.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gt2sbqudxah.html

PHP:  exit(1);
来源：http://dali.316326.xyz/Article/details/gt2zhpjcanw.html

JS:   process.exit(1)
来源：http://dali.fzhhl.top/Article/details/gt2txsqszhr.html

TS:   process.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2qeaepufk.html

Java: System.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gt2rqnymwsa.html

Go:   os.Exit(1)
来源：http://dali.gotoacloud.top/Article/details/gt2cvjwwjjo.html

Ruby: exit 1
来源：http://dali.sysykeji.top/Article/details/gt2lxiztaqc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.dashuyun.cn/Article/details/gt2aijvfrne.html

[M06] 向标准错误输出
来源：http://dali.chenjidiqi.icu/Article/details/gt2svoznngl.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yongpay.top/Article/details/gt2ajnlcicb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hnqzz.top/Article/details/gt2zllbader.html

JS:   console.error("err")
来源：http://dali.hongshengwenyu.top/Article/details/gt2fakmbzws.html

TS:   console.error("err")
来源：http://dali.yj202588.top/Article/details/gt2qypakpdw.html

Java: System.err.println("err")
来源：http://dali.xuanzx.com/Article/details/gt2hjiugruq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sxryk.cn/Article/details/gt2vwcfskuw.html

Ruby: warn "err"
来源：http://dali.tianlin.xyz/Article/details/gt2xvckdguv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ivvv.top/Article/details/gt2sqqttvrk.html

[M07] 判断是否为主入口
来源：http://dali.feifeiyinyue.top/Article/details/gt2ghdxbuot.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2izpfbdel.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhongyouzk.top/Article/details/gt2obffcgnn.html

JS:   require.main === module
来源：http://dali.shzxlz.cn/Article/details/gt2ktgyvdkn.html

TS:   require.main === module
来源：http://dali.ydzc1.top/Article/details/gt2rusqqkgy.html

Java: public static void main(String[] args)
来源：http://dali.fzhhl.top/Article/details/gt2ncbsuyoh.html

Go:   func main()
来源：http://dali.meibo888.top/Article/details/gt2wxreepve.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ymusrvsp.html

C#:   static void Main(string[] args)
来源：http://dali.redwolf501.top/Article/details/gt2dqcphduy.html

[M08] 获取系统与运行时信息
来源：http://dali.nanxinkj.top/Article/details/gt2pyberiyi.html

Py:   platform.system();  platform.python_version()
来源：http://dali.chenlongwang.top/Article/details/gt2ximnruej.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhongyouzk.top/Article/details/gt2cthoirtp.html

JS:   process.platform;  process.version
来源：http://dali.zhengqikj.top/Article/details/gt2bmkocvau.html

TS:   process.platform;  process.version
来源：http://dali.snrcjt.cn/Article/details/gt2bdxupocn.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yangfankeji.com/Article/details/gt2vyanutgu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hongshengwenyu.top/Article/details/gt2rnwyaiin.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hnxiangtu.top/Article/details/gt2ftucvgpt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cqqwz.cn/Article/details/gt2ltmowskb.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2wjzqsvdj.html

N. 数据结构与算法
来源：http://dali.snrcjt.cn/Article/details/gt2ynqgyigv.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2vzqkzdio.html

[N01] 二分查找（有序数组）
来源：http://dali.sweek.top/Article/details/gt2hkelspow.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tanke756.top/Article/details/gt2qzxhnmxl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhengqikj.top/Article/details/gt2xzyzvymp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dashuyun.cn/Article/details/gt2mlqqders.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tianlin.xyz/Article/details/gt2jefzfooc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gt2yhljpgow.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.fengsongda.top/Article/details/gt2ndmvyiuh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gzhubu.top/Article/details/gt2tahhozkx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cucudq.cn/Article/details/gt2cdlpddvy.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.quarkkingdee.top/Article/details/gt2hgfrnpki.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yangfankeji.com/Article/details/gt2tfgioowj.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sysykeji.top/Article/details/gt2ucnbszly.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dianchejie.cn/Article/details/gt2odfaxppe.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ehwqpu.com/Article/details/gt2sljvcqju.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.smart0.xyz/Article/details/gt2qtiuuaaf.html

Go:   slices.Sort(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2yxhzvvta.html

Ruby: arr.sort
来源：http://dali.zhongyouzk.top/Article/details/gt2mdbobtmb.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yj202588.top/Article/details/gt2aghstczr.html

[N03] 快速排序（分治示例）
来源：http://dali.gogol.net.cn/Article/details/gt2agafgukr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.svipenyu.cn/Article/details/gt2oflrvzji.html

PHP:  // 递归实现，或用 usort
来源：http://dali.snrcjt.cn/Article/details/gt2emdtvclf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhoulong.xyz/Article/details/gt2tlrqzgdf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shuidangran.top/Article/details/gt2izkwrjty.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gzhubu.top/Article/details/gt2dnxrquka.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.smart0.xyz/Article/details/gt2ijigowwh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.fzhhl.top/Article/details/gt2hxizztuy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hywenlv.cn/Article/details/gt2epbmoqrw.html

[N04] 斐波那契数列
来源：http://dali.daxiang520.top/Article/details/gt2sdrigvap.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.fengsongda.top/Article/details/gt2zddfjicy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.nanxuanxn.top/Article/details/gt2idxphmyj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zycfv.cn/Article/details/gt2odrdstjm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yongpay.top/Article/details/gt2paakysho.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2qaspyyot.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.guowangkeji.top/Article/details/gt2sryymcoo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yuxming.cn/Article/details/gt2bwiqwqji.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gt2kkwpjnxo.html

[N05] 最大公约数
来源：http://dali.sweek.top/Article/details/gt2cmhnhcpq.html

Py:   math.gcd(a, b)
来源：http://dali.shuidangran.top/Article/details/gt2mlxskyjq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.redwolf501.top/Article/details/gt2qmxtsjpc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cashguo.top/Article/details/gt2vamfmrak.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xinyue.icu/Article/details/gt2mlsmrxtg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.haohaochexian.top/Article/details/gt2gnpmiprd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hammf.cn/Article/details/gt2pratwles.html

Ruby: a.gcd(b)
来源：http://dali.bjfxy.top/Article/details/gt2ndfwczlf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ydzc1.top/Article/details/gt2obvhotgf.html

[N06] 判断回文字符串
来源：http://dali.zdqjudy.top/Article/details/gt2jteahdjt.html

Py:   s == s[::-1]
来源：http://dali.yj20258888.top/Article/details/gt2cjpmjgvd.html

PHP:  $s === strrev($s);
来源：http://dali.andypj.xyz/Article/details/gt2wwthlhzt.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sysykeji.top/Article/details/gt2ohctgdcl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ehwqpu.com/Article/details/gt2qrksqlea.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shuidangran.top/Article/details/gt2ggsyxckc.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2phrefkas.html

Ruby: s == s.reverse
来源：http://dali.hfpthk.cn/Article/details/gt2kimqoxdm.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cqqwz.cn/Article/details/gt2yjqvikhr.html

[N07] 两数之和（返回下标）
来源：http://dali.ydzc1.top/Article/details/gt2mhqsaamx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yongpay.top/Article/details/gt2fclpdxlt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ybcxt.top/Article/details/gt2lnwmbrfu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhoulong.xyz/Article/details/gt2ttjwsixh.html

TS:   // 手写 Map<string, number>
来源：http://dali.wangshuangyany.cn/Article/details/gt2pmlkrdyb.html

Java: // 手写 HashMap
来源：http://dali.zycfv.cn/Article/details/gt2rkdvlkjr.html

Go:   // 手写 map[int]int
来源：http://dali.cashguo.top/Article/details/gt2diyrogvk.html

Ruby: // 手写 Hash
来源：http://dali.xuanzx.com/Article/details/gt2rgindwhf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.guannengcc.top/Article/details/gt2jzxzdiey.html

[N08] 生成全排列
来源：http://dali.shangyingyoupin.top/Article/details/gt2rjdiamkb.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2beteocxh.html

PHP:  // 手写递归交换
来源：http://dali.jinqigufen.top/Article/details/gt2yqmesujy.html

JS:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gt2okuynjec.html

TS:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gt2lnkahstk.html

Java: // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nkyzhgyd.html

Go:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vbnbnmnp.html

Ruby: arr.permutation.to_a
来源：http://dali.ppjwa.cn/Article/details/gt2gzzzovzz.html

C#:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gt2fhqefzsh.html

[N09] 栈与队列
来源：http://dali.xziqi.cn/Article/details/gt2ekldaqks.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.9152youxi.cn/Article/details/gt2kowvimpv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cheryme.top/Article/details/gt2elhaqoup.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jqgfzy.top/Article/details/gt2rvcqbcto.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.c1oappe.top/Article/details/gt2kvgalmcd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jlsjyb.cn/Article/details/gt2jhfcprqy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gotoacloud.top/Article/details/gt2rheobvse.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cqqwz.cn/Article/details/gt2jqjasslm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.svipenyu.cn/Article/details/gt2iyvrutrr.html

[N10] 链表节点定义
来源：http://dali.cdnleiting.top/Article/details/gt2daotrnue.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gzhubu.top/Article/details/gt2jmgozjpy.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xinyue.icu/Article/details/gt2dnlzpvxm.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.tianlin.xyz/Article/details/gt2rmntvwsr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yj20258.top/Article/details/gt2zfwckorc.html

Java: class Node { int v; Node next; }
来源：http://dali.zhengqikj.top/Article/details/gt2svmczvyf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.pycfn.com/Article/details/gt2nvprohqi.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhengqikj.top/Article/details/gt2udnjnkcx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhongyouzk.top/Article/details/gt2bzywunkp.html

[N11] 二叉树中序遍历
来源：http://dali.0kj1m.cn/Article/details/gt2oygdqaqd.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hywenlv.cn/Article/details/gt2uukjneum.html

PHP:  // 手写递归函数
来源：http://dali.kuanghao11.cn/Article/details/gt2gnnzhimt.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnqzz.top/Article/details/gt2cngbfqxx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.0kj1m.cn/Article/details/gt2mxlywqmu.html

Java: // 手写递归
来源：http://dali.ybcxt.top/Article/details/gt2melcrknp.html

Go:   // 手写递归
来源：http://dali.yvedp.cn/Article/details/gt2sozwbyre.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhixingplan.top/Article/details/gt2ligakjvr.html

C#:   // 手写递归
来源：http://dali.nanxinkj.top/Article/details/gt2ecfwyovi.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ppjwa.cn/Article/details/gt2emmigtiy.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinqigufen.top/Article/details/gt2etbiopwb.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yj20258.top/Article/details/gt2gvhdmbij.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhongyouzk.top/Article/details/gt2pfjslowe.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vozhotsa.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guowangkeji.top/Article/details/gt2aajllypn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.chenjidiqi.icu/Article/details/gt2iqmgriev.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yuanzhike.top/Article/details/gt2bdgidpxu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.c1oappe.top/Article/details/gt2coeyxfjr.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2zjrvinnq.html

O. 并发与异步
来源：http://dali.jinqigfzy.top/Article/details/gt2dwdobhuk.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2zwewrstg.html

[O01] 启动一个线程
来源：http://dali.ehwqpu.com/Article/details/gt2vjoqlckb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ydzc1.top/Article/details/gt2ezrokcve.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sufxvd.cn/Article/details/gt2lystpwii.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.svipenyu.cn/Article/details/gt2arjuebar.html

TS:   // 同 JS
来源：http://dali.xylfe.cn/Article/details/gt2ovevpian.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhengqikj.top/Article/details/gt2rusvfvct.html

Go:   go f()
来源：http://dali.jqgfzy.top/Article/details/gt2tvwkqigp.html

Ruby: Thread.new { f }
来源：http://dali.hnqzz.top/Article/details/gt2tshjnvqd.html

C#:   Task.Run(() => F());
来源：http://dali.hywenlv.cn/Article/details/gt2bhuszeiv.html

[O02] 使用线程池
来源：http://dali.andypj.xyz/Article/details/gt2jtmpaegv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cheryme.top/Article/details/gt2tajfrtxq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zdqjudy.top/Article/details/gt2lgszlydc.html

JS:   // worker_threads 线程池
来源：http://dali.birdmap.top/Article/details/gt2kfvznzsm.html

TS:   // worker_threads 线程池
来源：http://dali.chenzaomai.com/Article/details/gt2jkvobsmh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.birdmap.top/Article/details/gt2tqboujlf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cucudq.cn/Article/details/gt2xzhdbunu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.guowangkeji.top/Article/details/gt2iolmjqsl.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.aibaodan.cn/Article/details/gt2otelawxh.html

[O03] 加锁保护共享数据
来源：http://dali.zhongyouzk.top/Article/details/gt2xdkinrcq.html

Py:   with lock: shared += 1
来源：http://dali.quarkkingdee.top/Article/details/gt2jgelfpti.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhoulong.xyz/Article/details/gt2lruaxnwe.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yanxiufei.cn/Article/details/gt2wdltscvz.html

TS:   // 同 JS
来源：http://dali.yueranfly.top/Article/details/gt2fkqvjcwc.html

Java: synchronized (this) { shared++; }
来源：http://dali.yj20258888.top/Article/details/gt2hinxdzde.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hammf.cn/Article/details/gt2bcgwiqkk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.0kj1m.cn/Article/details/gt2zohnrkpv.html

C#:   lock (gate) { shared++; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2asiejgpm.html

[O04] 定义异步函数并等待
来源：http://dali.gotoacloud.top/Article/details/gt2ypxxljqg.html

Py:   async def f():⏎    await g()
来源：http://dali.vqdsnc.cn/Article/details/gt2xuruqokq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shanyushiyangtech.top/Article/details/gt2znsdwmdw.html

JS:   async function f() { await g(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2swrocpco.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rodtawut.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hongshengwenyu.top/Article/details/gt2mobylnfz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj20258888.top/Article/details/gt2gmmzpcck.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.kuanghao11.cn/Article/details/gt2xgmaorqd.html

C#:   async Task F() { await G(); }
来源：http://dali.ybcxt.top/Article/details/gt2bsggjdga.html

[O05] 并发执行并等待全部完成
来源：http://dali.dashuyun.cn/Article/details/gt2gjtgiuov.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cheryme.top/Article/details/gt2ylfvgmwk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hnqzz.top/Article/details/gt2mptchupv.html

JS:   await Promise.all(tasks)
来源：http://dali.havefunace.top/Article/details/gt2jfscqjlb.html

TS:   await Promise.all(tasks)
来源：http://dali.xuanzx.com/Article/details/gt2cvhhkctw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hnqzz.top/Article/details/gt2skxraxwx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tanke756.top/Article/details/gt2fqteezhm.html

Ruby: threads.map(&:join)
来源：http://dali.yangfankeji.com/Article/details/gt2vkpscpyd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.tianlin.xyz/Article/details/gt2rwomtntw.html

[O06] 使用进程池
来源：http://dali.cqqwz.cn/Article/details/gt2scznyfvv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.gaohongyu789.top/Article/details/gt2yzttfqnn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.tianlin.xyz/Article/details/gt2lgpajdfz.html

JS:   // child_process / cluster 模块
来源：http://dali.iojbl.cn/Article/details/gt2kwdpgjhr.html

TS:   // child_process / cluster 模块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rukrhbzz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.feifeiyinyue.top/Article/details/gt2hndsvbnu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.nanxuanxn.top/Article/details/gt2paddbzxv.html

Ruby: // fork 块
来源：http://dali.chenjidiqi.icu/Article/details/gt2qydwpkrj.html

C#:   Parallel.For
来源：http://dali.fengsongda.top/Article/details/gt2jgzuacsg.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2wulagbbq.html

P. 常用工具函数
来源：http://dali.ivvv.top/Article/details/gt2zrtjuqyz.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2wtychwaa.html

[P01] 生成 UUID
来源：http://dali.jqgfzy.top/Article/details/gt2dndiopul.html

Py:   str(uuid.uuid4())
来源：http://dali.cqqwz.cn/Article/details/gt2ldebunuw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tianlin.xyz/Article/details/gt2lauopntq.html

JS:   crypto.randomUUID()
来源：http://dali.zhoulong.xyz/Article/details/gt2wpowhrdw.html

TS:   crypto.randomUUID()
来源：http://dali.guowangkeji.top/Article/details/gt2joioyrop.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhongyouzk.top/Article/details/gt2diugxgpv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tanke756.top/Article/details/gt2txgeojqg.html

Ruby: SecureRandom.uuid
来源：http://dali.xziqi.cn/Article/details/gt2tjoiyjdw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yj20258.top/Article/details/gt2afklkyaj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.chenzaomai.com/Article/details/gt2rcpzgcrp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.mhx1999.top/Article/details/gt2appdimam.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rmndazce.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.tanke756.top/Article/details/gt2syhcfwgt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pbyrkckq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yvedp.cn/Article/details/gt2ycttwhqw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shzxlz.cn/Article/details/gt2mwokyhlv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2hdumcdby.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.0kj1m.cn/Article/details/gt2bcrdaugi.html

[P03] 生成短随机字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2jqvvynyc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hnxiangtu.top/Article/details/gt2mwxvecnv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhtmtwtl.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.wangshuangyany.cn/Article/details/gt2osblbdie.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.haohaochexian.top/Article/details/gt2nrwtceai.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yueranfly.top/Article/details/gt2jtbbjokk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xuanzx.com/Article/details/gt2bvgitrxh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eamxhogj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.quarkkingdee.top/Article/details/gt2ubinhfbw.html

[P04] 求长度
来源：http://dali.daria6918.cn/Article/details/gt2tfibciri.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hysaishi.cn/Article/details/gt2vardrpzr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gt2mlowddxn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.smart0.xyz/Article/details/gt2vcpmiwdo.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhiwuduotai.top/Article/details/gt2lhqlyrdk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinqigufen.top/Article/details/gt2qfllnfgh.html

Go:   len(arr);  len(m)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ksqdkkti.html

Ruby: x.length;  x.size
来源：http://dali.jqgfzy.top/Article/details/gt2ywpndjuq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hysaishi.cn/Article/details/gt2pbwlsrdm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xziqi.cn/Article/details/gt2eyfvqdtl.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhengqikj.top/Article/details/gt2ycurpmwz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinqigfzy.top/Article/details/gt2amrddqpj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhixingplan.top/Article/details/gt2hguvwzdx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxinkj.top/Article/details/gt2gwjykuja.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jiagoushi.top/Article/details/gt2thtjptdq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jiagoushi.top/Article/details/gt2urgbfubq.html

Ruby: a == b
来源：http://dali.pengpengdd.cyou/Article/details/gt2ddcjeuty.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkmanll.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.0kj1m.cn/Article/details/gt2vtllsdcc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.nanxuanxn.top/Article/details/gt2idhaljti.html

PHP:  if (empty($x)) {}
来源：http://dali.sysykeji.top/Article/details/gt2cnxhrrti.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yangfankeji.com/Article/details/gt2eivhoesv.html

TS:   if (x == null) {}
来源：http://dali.aibaodan.cn/Article/details/gt2qzyawsgb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2utnqzyyn.html

Go:   if x == nil {}
来源：http://dali.redwolf501.top/Article/details/gt2wlgmbqvt.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ppjwa.cn/Article/details/gt2ovdmdajy.html

C#:   if (x is null) {}
来源：http://dali.hywenlv.cn/Article/details/gt2ywbstylb.html

[P07] 防抖与节流
来源：http://dali.yuanzhike.top/Article/details/gt2aebyimdi.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yonumen.top/Article/details/gt2dzocfeix.html

PHP:  // 手写时间戳比较
来源：http://dali.feifeiyinyue.top/Article/details/gt2pqijmwji.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ullkutkh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cqqwz.cn/Article/details/gt2vqgjgbwi.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ppjwa.cn/Article/details/gt2trievpdq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.meibo888.top/Article/details/gt2neaohuug.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ybcxt.top/Article/details/gt2uitbjroi.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.havefunace.top/Article/details/gt2hzmayqck.html

[P08] 处理浮点精度问题
来源：http://dali.vqdsnc.cn/Article/details/gt2mlxioqlb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yvedp.cn/Article/details/gt2exfgwajm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yj20258888.top/Article/details/gt2khgoxjwk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fuawojws.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinqigfzy.top/Article/details/gt2wjjwqtnp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gotoacloud.top/Article/details/gt2eieyusxf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.sweek.top/Article/details/gt2viguueix.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zdqjudy.top/Article/details/gt2lkttewoy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jqgfzy.top/Article/details/gt2emedtzob.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2ufiiqidx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yj202588.top/Article/details/gt2wnhcihcl.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2oldwcfzq.html

[Q01] 创建表
来源：http://dali.kuanghao11.cn/Article/details/gt2zhbnyjjq.html


<!-- 参考信息 -->