代发 wailian999

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cashguo.top/Article/details/gtjmttrjni.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.316326.xyz/Article/details/gtsuhfgxcx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtfygelkwo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hongshengwenyu.top/Article/details/gtpraczrus.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jqgufenzy.top/Article/details/gtppkdkqtk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xziqi.cn/Article/details/gtpslizszn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.fengsongda.top/Article/details/gtfguezxuq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ppjwa.cn/Article/details/gtmhwanhio.html

[M04] 获取当前工作目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnwzupktd.html

Py:   os.getcwd()
来源：http://dali.jianghu66.top/Article/details/gtuyqhwxzh.html

PHP:  getcwd();
来源：http://dali.daria6918.cn/Article/details/gtoxfwckwg.html

JS:   process.cwd()
来源：http://dali.hongshengwenyu.top/Article/details/gtlxekramu.html

TS:   process.cwd()
来源：http://dali.jqgufenzy.top/Article/details/gtjolxsreb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkqikqcji.html

Go:   os.Getwd()
来源：http://dali.jqgufenzy.top/Article/details/gtehjnobjr.html

Ruby: Dir.pwd
来源：http://dali.smart0.xyz/Article/details/gtxhtwrvfj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.aibaodan.cn/Article/details/gtxcotrnso.html

[M05] 设置退出码
来源：http://dali.havefunace.top/Article/details/gtxqybipus.html

Py:   sys.exit(1)
来源：http://dali.yvedp.cn/Article/details/gtxcnkjuut.html

PHP:  exit(1);
来源：http://dali.wangdashe.top/Article/details/gtllawavnh.html

JS:   process.exit(1)
来源：http://dali.hnqzz.top/Article/details/gtnurvycre.html

TS:   process.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gtnkyydyle.html

Java: System.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoxyjpjeb.html

Go:   os.Exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtyycxvjyv.html

Ruby: exit 1
来源：http://dali.kuanghao11.cn/Article/details/gtjatcfieg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gtqsxpucip.html

[M06] 向标准错误输出
来源：http://dali.zhiwuduotai.top/Article/details/gtewhzxeod.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gogol.net.cn/Article/details/gtreezquzi.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.birdmap.top/Article/details/gtdnjsqkie.html

JS:   console.error("err")
来源：http://dali.jlsjyb.cn/Article/details/gtqnkhxwoy.html

TS:   console.error("err")
来源：http://dali.daria6918.cn/Article/details/gtrmleqeiv.html

Java: System.err.println("err")
来源：http://dali.yj20258.top/Article/details/gtmwrsiejm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.pycfn.com/Article/details/gtrwkdbfwi.html

Ruby: warn "err"
来源：http://dali.yonumen.top/Article/details/gtlgpnddhr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhixingplan.top/Article/details/gtjflfxpxj.html

[M07] 判断是否为主入口
来源：http://dali.jinghuilouyu.cn/Article/details/gtfkwbkxps.html

Py:   if __name__ == "__main__":
来源：http://dali.hysaishi.cn/Article/details/gtzsxuqulr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.redwolf501.top/Article/details/gtmwxddjdy.html

JS:   require.main === module
来源：http://dali.daria6918.cn/Article/details/gteyngqiqh.html

TS:   require.main === module
来源：http://dali.xuanzx.com/Article/details/gtevbqcgit.html

Java: public static void main(String[] args)
来源：http://dali.316326.xyz/Article/details/gteosgnlig.html

Go:   func main()
来源：http://dali.guowangkeji.top/Article/details/gtybtnrvhp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xziqi.cn/Article/details/gtixuepawx.html

C#:   static void Main(string[] args)
来源：http://dali.sufxvd.cn/Article/details/gtgasiuvpz.html

[M08] 获取系统与运行时信息
来源：http://dali.pycfn.com/Article/details/gthtvgewia.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hnxiangtu.top/Article/details/gtndwxiizt.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.mhx1999.top/Article/details/gtekjrnfig.html

JS:   process.platform;  process.version
来源：http://dali.hammf.cn/Article/details/gtyedilbbg.html

TS:   process.platform;  process.version
来源：http://dali.sufxvd.cn/Article/details/gtfqcmfqru.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jianghu66.top/Article/details/gtmbvnltic.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.andypj.xyz/Article/details/gtxunluxnd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.haohaochexian.top/Article/details/gtkltddgko.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xziqi.cn/Article/details/gtesjugvzr.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtwmxkkvll.html

N. 数据结构与算法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtthtmmass.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtghqiqijq.html

[N01] 二分查找（有序数组）
来源：http://dali.tanke756.top/Article/details/gtpoldkylo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtpkozagkp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.daria6918.cn/Article/details/gtwhwkxgve.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fzhhl.top/Article/details/gtdfvoncuz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.haohaochexian.top/Article/details/gtmyjkhold.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yongpay.top/Article/details/gtdvuivtqd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtwaqdolxl.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xuetiantiany.cn/Article/details/gtlptnboqi.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtbpmungec.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdxeryzhr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxinkj.top/Article/details/gtfebcudjn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.gotoacloud.top/Article/details/gtmfeahsbd.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tanke756.top/Article/details/gtkhqaqglf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.c1oappe.top/Article/details/gtghdpytlm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shuidangran.top/Article/details/gtjbbnaage.html

Go:   slices.Sort(arr)
来源：http://dali.nanxinkj.top/Article/details/gttmjnfzsk.html

Ruby: arr.sort
来源：http://dali.vqdsnc.cn/Article/details/gtymsuxloo.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gtxeufjmim.html

[N03] 快速排序（分治示例）
来源：http://dali.cashguo.top/Article/details/gtpvhdmfxj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.guowangkeji.top/Article/details/gtpytmvrlq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.iojbl.cn/Article/details/gtmptmqxmu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jyoumei.cn/Article/details/gtxtpsquuq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hywenlv.cn/Article/details/gtqrgmndtw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gzhubu.top/Article/details/gtxjajbnma.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj20258.top/Article/details/gttfeixqdh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsegqkwdz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xylfe.cn/Article/details/gtvsnbftjw.html

[N04] 斐波那契数列
来源：http://dali.iojbl.cn/Article/details/gtoqjrpqra.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hfpthk.cn/Article/details/gtcfdjzcaa.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yuanzhike.top/Article/details/gtqhvroczo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ehwqpu.com/Article/details/gtmqigubji.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ppjwa.cn/Article/details/gtadcthpjn.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hongshengwenyu.top/Article/details/gtaclgzjxt.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.wangshuangyany.cn/Article/details/gtrlonhhpy.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtuieyhpfa.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yueranfly.top/Article/details/gtnoyfzetu.html

[N05] 最大公约数
来源：http://dali.zdqjudy.top/Article/details/gtfcfivisn.html

Py:   math.gcd(a, b)
来源：http://dali.birdmap.top/Article/details/gtrqxmtbuq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shzxlz.cn/Article/details/gtscscatfp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daxiang520.top/Article/details/gtigbhzhwl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jianghu66.top/Article/details/gtzlvsgrjg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sxryk.cn/Article/details/gtfwetolal.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ehwqpu.com/Article/details/gtepsznenn.html

Ruby: a.gcd(b)
来源：http://dali.daxiang520.top/Article/details/gtrwltqzpy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hammf.cn/Article/details/gtvthudbqi.html

[N06] 判断回文字符串
来源：http://dali.yj202588.top/Article/details/gtftkcmgai.html

Py:   s == s[::-1]
来源：http://dali.0kj1m.cn/Article/details/gtarcbiprz.html

PHP:  $s === strrev($s);
来源：http://dali.zdqjudy.top/Article/details/gtyxnlgbgy.html

JS:   s === [...s].reverse().join("")
来源：http://dali.fzhhl.top/Article/details/gtqslxjljp.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gtsowywfef.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zdqjudy.top/Article/details/gtgqqoaqop.html

Go:   // 双指针从两端比较
来源：http://dali.dashuyun.cn/Article/details/gtomneyoql.html

Ruby: s == s.reverse
来源：http://dali.yj20258.top/Article/details/gtqrojvldt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.daria6918.cn/Article/details/gtpuizmhgd.html

[N07] 两数之和（返回下标）
来源：http://dali.sysykeji.top/Article/details/gtuabozwtk.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.316326.xyz/Article/details/gtzyupcbab.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbcaszxrx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.dashuyun.cn/Article/details/gttqjsmioy.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhengqikj.top/Article/details/gtkpoekhfm.html

Java: // 手写 HashMap
来源：http://dali.ehwqpu.com/Article/details/gtwztleuwx.html

Go:   // 手写 map[int]int
来源：http://dali.nwbrower.top/Article/details/gtyehusowu.html

Ruby: // 手写 Hash
来源：http://dali.guowangkeji.top/Article/details/gtfslcxkxx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jqgufenzy.top/Article/details/gtnkbhkcdc.html

[N08] 生成全排列
来源：http://dali.jqgfzy.top/Article/details/gtkufvqxvl.html

Py:   itertools.permutations(arr)
来源：http://dali.mhx1999.top/Article/details/gtowpybfkj.html

PHP:  // 手写递归交换
来源：http://dali.sxryk.cn/Article/details/gtmrjfmtfb.html

JS:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gtzedrtzmz.html

TS:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gttwmpnemk.html

Java: // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtoirljwnb.html

Go:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gtoozpbkga.html

Ruby: arr.permutation.to_a
来源：http://dali.tianlin.xyz/Article/details/gtcyywbopu.html

C#:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gtagpwwkco.html

[N09] 栈与队列
来源：http://dali.gotoacloud.top/Article/details/gttjqvgnop.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hysaishi.cn/Article/details/gtytgxdyzn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sxryk.cn/Article/details/gtmdxxllwj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.andypj.xyz/Article/details/gtinxuxsgx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.sweek.top/Article/details/gtrgyznazn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ybcxt.top/Article/details/gtkklcjlpf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.feifeiyinyue.top/Article/details/gtrroxjsll.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hnxiangtu.top/Article/details/gtalupzkyg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jlsjyb.cn/Article/details/gtyxrnnapa.html

[N10] 链表节点定义
来源：http://dali.ywan-chungtsiang.top/Article/details/gtehlezpcg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.nanxuanxn.top/Article/details/gtcpjohdzh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkynzoorf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.wangdashe.top/Article/details/gtxyhgihql.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhengqikj.top/Article/details/gtxvjlvgmo.html

Java: class Node { int v; Node next; }
来源：http://dali.jinqigfzy.top/Article/details/gtaymultzi.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yueranfly.top/Article/details/gttdajdkvw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tian-w.cn/Article/details/gtmzgafmlh.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jlsjyb.cn/Article/details/gtmjixdson.html

[N11] 二叉树中序遍历
来源：http://dali.316326.xyz/Article/details/gtbrihmhkl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xuetiantiany.cn/Article/details/gtdcsogukz.html

PHP:  // 手写递归函数
来源：http://dali.chenlongwang.top/Article/details/gtrhpefopv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnqzz.top/Article/details/gtiqttbkpc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsphjfwqv.html

Java: // 手写递归
来源：http://dali.sxryk.cn/Article/details/gtfovnavqr.html

Go:   // 手写递归
来源：http://dali.zhiwuduotai.top/Article/details/gtwjumzugw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gotoacloud.top/Article/details/gtawasylkb.html

C#:   // 手写递归
来源：http://dali.c1oappe.top/Article/details/gtmcmzlcgy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.havefunace.top/Article/details/gtecajagvf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.feifeiyinyue.top/Article/details/gtayzqxphi.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.daxiang520.top/Article/details/gtvlgaovfo.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hywenlv.cn/Article/details/gtaddbezyd.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tian-w.cn/Article/details/gtcolwguzv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.haohaochexian.top/Article/details/gtukvobcws.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.tanke756.top/Article/details/gtuduewewc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shzxlz.cn/Article/details/gtiwpmrfml.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgfzy.top/Article/details/gttgdqbisd.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtwozyoxwi.html

O. 并发与异步
来源：http://dali.shuidangran.top/Article/details/gttbhtxgzd.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtvsovtemc.html

[O01] 启动一个线程
来源：http://dali.daria6918.cn/Article/details/gtmezxehmf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.dashuyun.cn/Article/details/gtdvflqimo.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jianghu66.top/Article/details/gtsofmezhh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.chenjidiqi.icu/Article/details/gtpqjheyql.html

TS:   // 同 JS
来源：http://dali.sweek.top/Article/details/gtvqsgubvw.html

Java: new Thread(() -> f()).start()
来源：http://dali.snrcjt.cn/Article/details/gthtgekbbt.html

Go:   go f()
来源：http://dali.hysaishi.cn/Article/details/gtjuzfjzwa.html

Ruby: Thread.new { f }
来源：http://dali.316326.xyz/Article/details/gtqixavxth.html

C#:   Task.Run(() => F());
来源：http://dali.shuidangran.top/Article/details/gtufwazqes.html

[O02] 使用线程池
来源：http://dali.ehwqpu.com/Article/details/gthwxtqsfd.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.havefunace.top/Article/details/gtzkcvsllt.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cashguo.top/Article/details/gtflvijqjv.html

JS:   // worker_threads 线程池
来源：http://dali.chenlongwang.top/Article/details/gtljuldvou.html

TS:   // worker_threads 线程池
来源：http://dali.ppjwa.cn/Article/details/gtvyensljv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.sufxvd.cn/Article/details/gtisvrxqrt.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yj20258888.top/Article/details/gtkmwvbsdt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.aibaodan.cn/Article/details/gtmtlhhkvc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gtadfpwsxv.html

[O03] 加锁保护共享数据
来源：http://dali.shzxlz.cn/Article/details/gtwntmmkmo.html

Py:   with lock: shared += 1
来源：http://dali.hysaishi.cn/Article/details/gtywcuypub.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.wangshuangyany.cn/Article/details/gthyowolro.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yuxming.cn/Article/details/gtqqunznhn.html

TS:   // 同 JS
来源：http://dali.meibo888.top/Article/details/gtbdcokxmf.html

Java: synchronized (this) { shared++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzesecjst.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.dashuyun.cn/Article/details/gtxafoznrw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yj20258888.top/Article/details/gtywdiqvgp.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinqigufen.top/Article/details/gturvgrisn.html

[O04] 定义异步函数并等待
来源：http://dali.dashuyun.cn/Article/details/gthsrsebiv.html

Py:   async def f():⏎    await g()
来源：http://dali.tanke756.top/Article/details/gtsgdbjffn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.0kj1m.cn/Article/details/gtfzwsqbpj.html

JS:   async function f() { await g(); }
来源：http://dali.yj202588.top/Article/details/gtqkvglnmb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenzaomai.com/Article/details/gtdyneqkis.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jqgfzy.top/Article/details/gtrxqlyjrk.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gotoacloud.top/Article/details/gtksjonodz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shangyingyoupin.top/Article/details/gtyylktdmg.html

C#:   async Task F() { await G(); }
来源：http://dali.zhongyouzk.top/Article/details/gtwlprcmcb.html

[O05] 并发执行并等待全部完成
来源：http://dali.meibo888.top/Article/details/gtunkuwhyq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.tanke756.top/Article/details/gtrzorktex.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.wangdashe.top/Article/details/gtkkqbojqy.html

JS:   await Promise.all(tasks)
来源：http://dali.mhx1999.top/Article/details/gtgvccriwk.html

TS:   await Promise.all(tasks)
来源：http://dali.xuanzx.com/Article/details/gtdmnkiuld.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.vqdsnc.cn/Article/details/gtuylbsupm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xuanzx.com/Article/details/gtyflfgjtp.html

Ruby: threads.map(&:join)
来源：http://dali.wangdashe.top/Article/details/gtwwvweamn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zycfv.cn/Article/details/gtabophgyy.html

[O06] 使用进程池
来源：http://dali.hongshengwenyu.top/Article/details/gtckznxbwb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cashguo.top/Article/details/gtxbippoph.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhoulong.xyz/Article/details/gtzfcrbzvj.html

JS:   // child_process / cluster 模块
来源：http://dali.meibo888.top/Article/details/gtipdtktqr.html

TS:   // child_process / cluster 模块
来源：http://dali.zhiwuduotai.top/Article/details/gtdnupavii.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xuanzx.com/Article/details/gtonmdjazo.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shuidangran.top/Article/details/gtcuuloizz.html

Ruby: // fork 块
来源：http://dali.hnxiangtu.top/Article/details/gtyaowfslm.html

C#:   Parallel.For
来源：http://dali.svipenyu.cn/Article/details/gtulopmxqo.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtnprfjdtz.html

P. 常用工具函数
来源：http://dali.shzxlz.cn/Article/details/gtieohxrzb.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtidqqfawx.html

[P01] 生成 UUID
来源：http://dali.aizwys.cn/Article/details/gtvlhxqjvc.html

Py:   str(uuid.uuid4())
来源：http://dali.ppjwa.cn/Article/details/gtwrwqpjhx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.fengsongda.top/Article/details/gtituvfcwb.html

JS:   crypto.randomUUID()
来源：http://dali.xylfe.cn/Article/details/gtzprokutz.html

TS:   crypto.randomUUID()
来源：http://dali.sysykeji.top/Article/details/gtutsfkcnp.html

Java: UUID.randomUUID().toString()
来源：http://dali.316326.xyz/Article/details/gtrmxdoohz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hfpthk.cn/Article/details/gtzmpjroav.html

Ruby: SecureRandom.uuid
来源：http://dali.yj202588.top/Article/details/gtndlfdszb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.0kj1m.cn/Article/details/gtqwqjbree.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yj202588.top/Article/details/gtlyfvstef.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinyuanbaomall.cn/Article/details/gthpkyxada.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.redwolf501.top/Article/details/gtkqxcripb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hnxiangtu.top/Article/details/gtkhbcniln.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ehwqpu.com/Article/details/gtfclwkpev.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.aibaodan.cn/Article/details/gtasuqzmgp.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.aizwys.cn/Article/details/gtkpmjuhum.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtuscsgmnx.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xinyue.icu/Article/details/gtnhekahjg.html

[P03] 生成短随机字符串
来源：http://dali.gogol.net.cn/Article/details/gtoxjukkpp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yvedp.cn/Article/details/gtovgcrmqc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zdqjudy.top/Article/details/gtooaxzfkt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yuanzhike.top/Article/details/gtzbjvibkc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cashguo.top/Article/details/gtesohalsa.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.bjfxy.top/Article/details/gtpdlktirj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhiwuduotai.top/Article/details/gtodyhdkop.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shuidangran.top/Article/details/gtwtvultfa.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.feifeiyinyue.top/Article/details/gtmavsypjo.html

[P04] 求长度
来源：http://dali.jyoumei.cn/Article/details/gtzarnmkgb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cashguo.top/Article/details/gtfboefkbo.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gthwhizzkm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgufenzy.top/Article/details/gthblrovms.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.svipenyu.cn/Article/details/gtwpdmigfo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.havefunace.top/Article/details/gtqbyqivjx.html

Go:   len(arr);  len(m)
来源：http://dali.jqgufenzy.top/Article/details/gtidvywzwo.html

Ruby: x.length;  x.size
来源：http://dali.chenjidiqi.icu/Article/details/gteepzzrpw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shangyingyoupin.top/Article/details/gtbfhenxhy.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jinqigufen.top/Article/details/gthdeucxwc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cheryme.top/Article/details/gttzhyopaw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.redwolf501.top/Article/details/gtjammssjv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.fzhhl.top/Article/details/gtbmxyqxfu.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.pycfn.com/Article/details/gtrsdnylcb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hongshengwenyu.top/Article/details/gthsyjemjo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jyoumei.cn/Article/details/gtxpenbiyo.html

Ruby: a == b
来源：http://dali.zdqjudy.top/Article/details/gtespqeaxm.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.guannengcc.top/Article/details/gtqzukwziq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinqigufen.top/Article/details/gtxnwmohnk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.aizwys.cn/Article/details/gthkkztobl.html

PHP:  if (empty($x)) {}
来源：http://dali.hammf.cn/Article/details/gtctmgilpo.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.sufxvd.cn/Article/details/gtkzmwxvxb.html

TS:   if (x == null) {}
来源：http://dali.ehwqpu.com/Article/details/gtckuxmqzf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhoulong.xyz/Article/details/gtworeujoz.html

Go:   if x == nil {}
来源：http://dali.nwbrower.top/Article/details/gtpudtweju.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yj20258.top/Article/details/gtqgbumuip.html

C#:   if (x is null) {}
来源：http://dali.andypj.xyz/Article/details/gtygugiufk.html

[P07] 防抖与节流
来源：http://dali.gaohongyu789.top/Article/details/gtjgdjzrqq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhiwuduotai.top/Article/details/gtfmzksemp.html

PHP:  // 手写时间戳比较
来源：http://dali.nanxuanxn.top/Article/details/gtntgzgzms.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhiwuduotai.top/Article/details/gtrienbgku.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.smart0.xyz/Article/details/gtbngaxwtt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtieatlzwq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ywan-chungtsiang.top/Article/details/gthefvrjwi.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ivvv.top/Article/details/gtbklpmzpt.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jyoumei.cn/Article/details/gtdjyvjxri.html

[P08] 处理浮点精度问题
来源：http://dali.cashguo.top/Article/details/gthtkheslo.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.pengpengdd.cyou/Article/details/gtwulubxgw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jyoumei.cn/Article/details/gtzfsrqtmp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ivvv.top/Article/details/gtspbyfzcq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jianghu66.top/Article/details/gtpfaquluc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cheryme.top/Article/details/gtmseggecw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cashguo.top/Article/details/gtklmpqgse.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sweek.top/Article/details/gtidnmyeqc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.316326.xyz/Article/details/gtgnxattyb.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gthssorbjb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.andypj.xyz/Article/details/gtfifdnuft.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtcmeawumi.html

[Q01] 创建表
来源：http://dali.snrcjt.cn/Article/details/gtoluxmxvl.html


<!-- 参考信息 -->