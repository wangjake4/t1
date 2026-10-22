代发 wailian999

Ruby: ARGV
来源：http://dali.guannengcc.top/Article/details/gt2xhcdrrlw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhongyouzk.top/Article/details/gt2jhpwcgay.html

[M02] 读取环境变量
来源：http://dali.meibo888.top/Article/details/gt2ysixqzlh.html

Py:   os.environ.get("HOME")
来源：http://dali.9152youxi.cn/Article/details/gt2gzqvsodf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.smart0.xyz/Article/details/gt2cnabfywe.html

JS:   process.env.HOME
来源：http://dali.ybcxt.top/Article/details/gt2nqjqrjxd.html

TS:   process.env.HOME
来源：http://dali.meibo888.top/Article/details/gt2veplnfrq.html

Java: System.getenv("HOME")
来源：http://dali.cheryme.top/Article/details/gt2fvoqltya.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.daria6918.cn/Article/details/gt2qduzjuux.html

Ruby: ENV["HOME"]
来源：http://dali.mhx1999.top/Article/details/gt2cbasfrap.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhengqikj.top/Article/details/gt2ftvqquro.html

[M03] 执行外部命令
来源：http://dali.0kj1m.cn/Article/details/gt2fkvcnkvm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.daxiang520.top/Article/details/gt2hmfbabqk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.chenzaomai.com/Article/details/gt2ojrmaeut.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2brcojmbe.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2undsqbeq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.nanxuanxn.top/Article/details/gt2wrutxagw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tian-w.cn/Article/details/gt2serfofpu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.aibaodan.cn/Article/details/gt2bynrutvc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.chenjidiqi.icu/Article/details/gt2vontohaw.html

[M04] 获取当前工作目录
来源：http://dali.meibo888.top/Article/details/gt2iinjovgt.html

Py:   os.getcwd()
来源：http://dali.jlsjyb.cn/Article/details/gt2frmoenhn.html

PHP:  getcwd();
来源：http://dali.yvedp.cn/Article/details/gt2afoeomqx.html

JS:   process.cwd()
来源：http://dali.cheryme.top/Article/details/gt2harneocg.html

TS:   process.cwd()
来源：http://dali.smart0.xyz/Article/details/gt2rxyxspqo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zdqjudy.top/Article/details/gt2zoyrzxvi.html

Go:   os.Getwd()
来源：http://dali.gaohongyu789.top/Article/details/gt2pypmycdw.html

Ruby: Dir.pwd
来源：http://dali.ppjwa.cn/Article/details/gt2uvpbrnmj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.fengsongda.top/Article/details/gt2tsgczqit.html

[M05] 设置退出码
来源：http://dali.gaohongyu789.top/Article/details/gt2pptzrbkz.html

Py:   sys.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gt2yccnytat.html

PHP:  exit(1);
来源：http://dali.andypj.xyz/Article/details/gt2sawfbmae.html

JS:   process.exit(1)
来源：http://dali.iojbl.cn/Article/details/gt2adoztrci.html

TS:   process.exit(1)
来源：http://dali.andypj.xyz/Article/details/gt2qbkqudci.html

Java: System.exit(1)
来源：http://dali.ivvv.top/Article/details/gt2upktbbdh.html

Go:   os.Exit(1)
来源：http://dali.ppjwa.cn/Article/details/gt2qegburzq.html

Ruby: exit 1
来源：http://dali.chenzaomai.com/Article/details/gt2gsjguelc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xziqi.cn/Article/details/gt2qycmgxgz.html

[M06] 向标准错误输出
来源：http://dali.wangshuangyany.cn/Article/details/gt2avkuzbmg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.birdmap.top/Article/details/gt2oibbrwct.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.fzhhl.top/Article/details/gt2wasncdvn.html

JS:   console.error("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2idofzsju.html

TS:   console.error("err")
来源：http://dali.fzhhl.top/Article/details/gt2fezrjklt.html

Java: System.err.println("err")
来源：http://dali.yueranfly.top/Article/details/gt2pmkxumou.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinqigfzy.top/Article/details/gt2dhbjpymd.html

Ruby: warn "err"
来源：http://dali.cheryme.top/Article/details/gt2lertatkv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.havefunace.top/Article/details/gt2fndsnron.html

[M07] 判断是否为主入口
来源：http://dali.zhixingplan.top/Article/details/gt2mfnibulu.html

Py:   if __name__ == "__main__":
来源：http://dali.ppjwa.cn/Article/details/gt2lytrjzug.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yonumen.top/Article/details/gt2qgxdkste.html

JS:   require.main === module
来源：http://dali.yongpay.top/Article/details/gt2iwxzscla.html

TS:   require.main === module
来源：http://dali.feifeiyinyue.top/Article/details/gt2abtxllpu.html

Java: public static void main(String[] args)
来源：http://dali.chenlongwang.top/Article/details/gt2ppgtvyzf.html

Go:   func main()
来源：http://dali.xuanzx.com/Article/details/gt2qxxzighw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hysaishi.cn/Article/details/gt2cjgptrcp.html

C#:   static void Main(string[] args)
来源：http://dali.xuanzx.com/Article/details/gt2rikuhtdz.html

[M08] 获取系统与运行时信息
来源：http://dali.yvedp.cn/Article/details/gt2xzllthxf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.feifeiyinyue.top/Article/details/gt2euvdtxgb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ppjwa.cn/Article/details/gt2odjaqyxp.html

JS:   process.platform;  process.version
来源：http://dali.chenjidiqi.icu/Article/details/gt2unkkveiu.html

TS:   process.platform;  process.version
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cxmduiyr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.svipenyu.cn/Article/details/gt2qyldlkpb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yangfankeji.com/Article/details/gt2iuyprykg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gotoacloud.top/Article/details/gt2xwxdboia.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.316326.xyz/Article/details/gt2yzmaroxd.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2hcotmvjk.html

N. 数据结构与算法
来源：http://dali.yonumen.top/Article/details/gt2neyjcafz.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2zmsxrfqa.html

[N01] 二分查找（有序数组）
来源：http://dali.tianlin.xyz/Article/details/gt2guxdkdva.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cashguo.top/Article/details/gt2zpuejqjx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yj20258888.top/Article/details/gt2ajtgujag.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.9152youxi.cn/Article/details/gt2qkoaeooa.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigfzy.top/Article/details/gt2vdwuxrdw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qopgpszm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gt2ukmdukjo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.iojbl.cn/Article/details/gt2nkmhbmxa.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2zfhylspy.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qtcxmjri.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dashuyun.cn/Article/details/gt2ubmeoorv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.havefunace.top/Article/details/gt2sfpyfrkq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daria6918.cn/Article/details/gt2cwbegbmw.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jlsjyb.cn/Article/details/gt2lagftqrp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.fengsongda.top/Article/details/gt2zmghcrcm.html

Go:   slices.Sort(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2rvlrhwuf.html

Ruby: arr.sort
来源：http://dali.hysaishi.cn/Article/details/gt2ftqhdxwh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.dashuyun.cn/Article/details/gt2kfphzptq.html

[N03] 快速排序（分治示例）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wvbqgoey.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.haohaochexian.top/Article/details/gt2oewqumpt.html

PHP:  // 递归实现，或用 usort
来源：http://dali.c1oappe.top/Article/details/gt2epzlumrm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pycfn.com/Article/details/gt2kkwyuayo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenzaomai.com/Article/details/gt2zglpxwtr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yanxiufei.cn/Article/details/gt2jlyiotpw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yuanzhike.top/Article/details/gt2peiffezu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yonumen.top/Article/details/gt2muhslhbl.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.0kj1m.cn/Article/details/gt2ozqnnhqm.html

[N04] 斐波那契数列
来源：http://dali.dashuyun.cn/Article/details/gt2jfcptckl.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gotoacloud.top/Article/details/gt2jbqgbths.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.daxiang520.top/Article/details/gt2iuokqtor.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuxming.cn/Article/details/gt2gznyxzqi.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hywenlv.cn/Article/details/gt2bewzbvdc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yqhlhxlp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.redwolf501.top/Article/details/gt2qopiuztx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sufxvd.cn/Article/details/gt2kfpjahga.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.dashuyun.cn/Article/details/gt2bjybsrzi.html

[N05] 最大公约数
来源：http://dali.aizwys.cn/Article/details/gt2smvnzkmw.html

Py:   math.gcd(a, b)
来源：http://dali.svipenyu.cn/Article/details/gt2eywjkuyp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gotoacloud.top/Article/details/gt2nspkfgmy.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aizwys.cn/Article/details/gt2crpkogfa.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.meibo888.top/Article/details/gt2kxtwtcqy.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cashguo.top/Article/details/gt2kasfaoai.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sweek.top/Article/details/gt2zfggsmev.html

Ruby: a.gcd(b)
来源：http://dali.gaohongyu789.top/Article/details/gt2bcurgdcg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.andypj.xyz/Article/details/gt2dkumfxjh.html

[N06] 判断回文字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2gqroscpf.html

Py:   s == s[::-1]
来源：http://dali.zhongyouzk.top/Article/details/gt2tpeljdet.html

PHP:  $s === strrev($s);
来源：http://dali.9152youxi.cn/Article/details/gt2ivfhqhnu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.vqdsnc.cn/Article/details/gt2yweciuxg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gt2tnknetkn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mntumgde.html

Go:   // 双指针从两端比较
来源：http://dali.guowangkeji.top/Article/details/gt2xvrofryr.html

Ruby: s == s.reverse
来源：http://dali.cheryme.top/Article/details/gt2ipoipdwz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.daxiang520.top/Article/details/gt2nuuvepuc.html

[N07] 两数之和（返回下标）
来源：http://dali.yuanzhike.top/Article/details/gt2shoahukx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xuetiantiany.cn/Article/details/gt2ujjtzxvv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yonumen.top/Article/details/gt2fzgnxrcg.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ppjwa.cn/Article/details/gt2snyiysvq.html

TS:   // 手写 Map<string, number>
来源：http://dali.xuetiantiany.cn/Article/details/gt2ziuhejsd.html

Java: // 手写 HashMap
来源：http://dali.redwolf501.top/Article/details/gt2ehbnbntq.html

Go:   // 手写 map[int]int
来源：http://dali.hywenlv.cn/Article/details/gt2nrvmbonz.html

Ruby: // 手写 Hash
来源：http://dali.zdqjudy.top/Article/details/gt2gtbalqqq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.c1oappe.top/Article/details/gt2rnxghizs.html

[N08] 生成全排列
来源：http://dali.jinqigfzy.top/Article/details/gt2waibskfk.html

Py:   itertools.permutations(arr)
来源：http://dali.jianghu66.top/Article/details/gt2wgmvwxsj.html

PHP:  // 手写递归交换
来源：http://dali.fengsongda.top/Article/details/gt2szdyrttv.html

JS:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gt2tfwifvlu.html

TS:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gt2tbvjjmhg.html

Java: // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gt2llgldaui.html

Go:   // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gt2tjwpnoyc.html

Ruby: arr.permutation.to_a
来源：http://dali.xylfe.cn/Article/details/gt2spsvpego.html

C#:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gt2epznjywz.html

[N09] 栈与队列
来源：http://dali.ydzc1.top/Article/details/gt2rioxhdvt.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gt2tcsxomvo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinqigfzy.top/Article/details/gt2tclpocom.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.guowangkeji.top/Article/details/gt2aeupnjzd.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nanxinkj.top/Article/details/gt2ejtaciqy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.c1oappe.top/Article/details/gt2lqqlxavj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhongyouzk.top/Article/details/gt2romiglkq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.kuanghao11.cn/Article/details/gt2cwwblvvu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2opsdxzgi.html

[N10] 链表节点定义
来源：http://dali.c1oappe.top/Article/details/gt2qvvvjesn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.c1oappe.top/Article/details/gt2ondrehnz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cucudq.cn/Article/details/gt2qhqtjkiu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yuxming.cn/Article/details/gt2twitgpro.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2oeroloyw.html

Java: class Node { int v; Node next; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2gwyriahg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jlsjyb.cn/Article/details/gt2ovpvjcmb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hammf.cn/Article/details/gt2cfekmrva.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2doxyemve.html

[N11] 二叉树中序遍历
来源：http://dali.sufxvd.cn/Article/details/gt2tqqcdtyw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shangyingyoupin.top/Article/details/gt2aekagwea.html

PHP:  // 手写递归函数
来源：http://dali.yongpay.top/Article/details/gt2tntrexoh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ydzc1.top/Article/details/gt2nwkakmss.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigfzy.top/Article/details/gt2karuphff.html

Java: // 手写递归
来源：http://dali.pengpengdd.cyou/Article/details/gt2izhsquhn.html

Go:   // 手写递归
来源：http://dali.snrcjt.cn/Article/details/gt2ocdekllo.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhiwuduotai.top/Article/details/gt2fkmvwjdz.html

C#:   // 手写递归
来源：http://dali.chenlongwang.top/Article/details/gt2juwkpeco.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.c1oappe.top/Article/details/gt2ofikdzgp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.birdmap.top/Article/details/gt2ndtxgwod.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhongyouzk.top/Article/details/gt2orixxpib.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gotoacloud.top/Article/details/gt2kkttzuye.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jyoumei.cn/Article/details/gt2ffczwauf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ivvv.top/Article/details/gt2cvhgpoag.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bioqzhsj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cheryme.top/Article/details/gt2phlfgrdz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daxiang520.top/Article/details/gt2edclrbbu.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2gpmhyisq.html

O. 并发与异步
来源：http://dali.fengsongda.top/Article/details/gt2eipcsouq.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2ifwndlqk.html

[O01] 启动一个线程
来源：http://dali.aibaodan.cn/Article/details/gt2oyktaulr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yvedp.cn/Article/details/gt2zlorsrjr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.bjfxy.top/Article/details/gt2clikvcwv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cqqwz.cn/Article/details/gt2mdfzepik.html

TS:   // 同 JS
来源：http://dali.zhongyouzk.top/Article/details/gt2ymlpylxx.html

Java: new Thread(() -> f()).start()
来源：http://dali.yuxming.cn/Article/details/gt2fouzeqwb.html

Go:   go f()
来源：http://dali.jianghu66.top/Article/details/gt2holtpjtb.html

Ruby: Thread.new { f }
来源：http://dali.zhoulong.xyz/Article/details/gt2qmwfeeks.html

C#:   Task.Run(() => F());
来源：http://dali.jqgfzy.top/Article/details/gt2ontskdxk.html

[O02] 使用线程池
来源：http://dali.guowangkeji.top/Article/details/gt2bndcnhrq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.quarkkingdee.top/Article/details/gt2neentrry.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sweek.top/Article/details/gt2lqngermp.html

JS:   // worker_threads 线程池
来源：http://dali.hfpthk.cn/Article/details/gt2hjzphura.html

TS:   // worker_threads 线程池
来源：http://dali.yvedp.cn/Article/details/gt2idhfcuza.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.wangdashe.top/Article/details/gt2pfvesswz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xylfe.cn/Article/details/gt2pbmapcwm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sufxvd.cn/Article/details/gt2yxfiygoj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.bjfxy.top/Article/details/gt2oncatrwj.html

[O03] 加锁保护共享数据
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mbqslxsr.html

Py:   with lock: shared += 1
来源：http://dali.hywenlv.cn/Article/details/gt2jtlalbsy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shzxlz.cn/Article/details/gt2tiltjdpv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yj202588.top/Article/details/gt2wylqveyx.html

TS:   // 同 JS
来源：http://dali.zhengqikj.top/Article/details/gt2ubbqfryg.html

Java: synchronized (this) { shared++; }
来源：http://dali.jqgufenzy.top/Article/details/gt2ussztily.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ivvv.top/Article/details/gt2ywccxgju.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yanxiufei.cn/Article/details/gt2lfmszezu.html

C#:   lock (gate) { shared++; }
来源：http://dali.yangfankeji.com/Article/details/gt2mwjrxwky.html

[O04] 定义异步函数并等待
来源：http://dali.sufxvd.cn/Article/details/gt2jdoawxqd.html

Py:   async def f():⏎    await g()
来源：http://dali.yj202588.top/Article/details/gt2bmwaaxon.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zdqjudy.top/Article/details/gt2tahfjosg.html

JS:   async function f() { await g(); }
来源：http://dali.sweek.top/Article/details/gt2iwuihnoc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dllpacbo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xziqi.cn/Article/details/gt2pahpapet.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sweek.top/Article/details/gt2lohzhpxp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.feifeiyinyue.top/Article/details/gt2skbknlcg.html

C#:   async Task F() { await G(); }
来源：http://dali.sxryk.cn/Article/details/gt2tqmbmtom.html

[O05] 并发执行并等待全部完成
来源：http://dali.wangshuangyany.cn/Article/details/gt2qgxqvglk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aztgdcuu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhongyouzk.top/Article/details/gt2unjliqoh.html

JS:   await Promise.all(tasks)
来源：http://dali.cheryme.top/Article/details/gt2gaiufnlm.html

TS:   await Promise.all(tasks)
来源：http://dali.316326.xyz/Article/details/gt2ksfjaqzk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gotoacloud.top/Article/details/gt2dnurdruw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jiagoushi.top/Article/details/gt2kysqanip.html

Ruby: threads.map(&:join)
来源：http://dali.nanxinkj.top/Article/details/gt2jtxwxczq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ydzc1.top/Article/details/gt2axuwodcz.html

[O06] 使用进程池
来源：http://dali.guowangkeji.top/Article/details/gt2hteydyhc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yuxming.cn/Article/details/gt2btwytyrz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.tanke756.top/Article/details/gt2gjtyeizm.html

JS:   // child_process / cluster 模块
来源：http://dali.hywenlv.cn/Article/details/gt2iibbftez.html

TS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iosbaqpz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jqgufenzy.top/Article/details/gt2kwmcdgge.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.daria6918.cn/Article/details/gt2nbkwanjr.html

Ruby: // fork 块
来源：http://dali.smart0.xyz/Article/details/gt2eronwiux.html

C#:   Parallel.For
来源：http://dali.iojbl.cn/Article/details/gt2zkkqojtf.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2gflxdnuc.html

P. 常用工具函数
来源：http://dali.yj20258.top/Article/details/gt2sjebcnwe.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2jilqopre.html

[P01] 生成 UUID
来源：http://dali.jqgufenzy.top/Article/details/gt2vnqhfvwt.html

Py:   str(uuid.uuid4())
来源：http://dali.redwolf501.top/Article/details/gt2lgrkuiyn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yanxiufei.cn/Article/details/gt2bnintdqj.html

JS:   crypto.randomUUID()
来源：http://dali.yangfankeji.com/Article/details/gt2hmxdtexq.html

TS:   crypto.randomUUID()
来源：http://dali.yuxming.cn/Article/details/gt2vvuanhvu.html

Java: UUID.randomUUID().toString()
来源：http://dali.tian-w.cn/Article/details/gt2qrodepjq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.birdmap.top/Article/details/gt2fjtrpgfg.html

Ruby: SecureRandom.uuid
来源：http://dali.gaohongyu789.top/Article/details/gt2hfskvxrv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.wangdashe.top/Article/details/gt2aahfnupi.html

[P02] MD5 / SHA256 摘要
来源：http://dali.redwolf501.top/Article/details/gt2fpekvlfc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenlongwang.top/Article/details/gt2ubtlglil.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xziqi.cn/Article/details/gt2wziklwmr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hnxiangtu.top/Article/details/gt2mshvooyt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2czmesqig.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zycfv.cn/Article/details/gt2qqxlzwqj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.smart0.xyz/Article/details/gt2sszlbefm.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.wangdashe.top/Article/details/gt2xunwblsw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hfpthk.cn/Article/details/gt2ukpurqtg.html

[P03] 生成短随机字符串
来源：http://dali.daria6918.cn/Article/details/gt2fseyqgtx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.nanxinkj.top/Article/details/gt2xfunhtwf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cqqwz.cn/Article/details/gt2jegmlcbr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.andypj.xyz/Article/details/gt2tcxnyyzr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.feifeiyinyue.top/Article/details/gt2pymzdnzg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.dashuyun.cn/Article/details/gt2xwuddrxa.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ybcxt.top/Article/details/gt2xtspzrdc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jlsjyb.cn/Article/details/gt2ciezqioj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.dianchejie.cn/Article/details/gt2ztjwwttj.html

[P04] 求长度
来源：http://dali.nanxuanxn.top/Article/details/gt2tkrsyqfq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhongyouzk.top/Article/details/gt2wygnbwqc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yvedp.cn/Article/details/gt2zeciunph.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guannengcc.top/Article/details/gt2ldjhfubv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jyoumei.cn/Article/details/gt2ffarubaf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cheryme.top/Article/details/gt2jdtjhooc.html

Go:   len(arr);  len(m)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bcixwblj.html

Ruby: x.length;  x.size
来源：http://dali.shangyingyoupin.top/Article/details/gt2lpdpwtcm.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yanxiufei.cn/Article/details/gt2gcallfme.html

[P05] 判断两个对象内容是否相等
来源：http://dali.guannengcc.top/Article/details/gt2bmldnljr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gzhubu.top/Article/details/gt2hzukihbj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.guannengcc.top/Article/details/gt2aszndmmk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cheryme.top/Article/details/gt2mvvdnfii.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yongpay.top/Article/details/gt2emuzwhtr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yuanzhike.top/Article/details/gt2gcutaaaz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yj202588.top/Article/details/gt2bifsgysm.html

Ruby: a == b
来源：http://dali.c1oappe.top/Article/details/gt2dbgnbukk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.guannengcc.top/Article/details/gt2eptjdrrg.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gzhubu.top/Article/details/gt2axhjcekl.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhengqikj.top/Article/details/gt2seregouz.html

PHP:  if (empty($x)) {}
来源：http://dali.0kj1m.cn/Article/details/gt2qfblmeac.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.snrcjt.cn/Article/details/gt2ytsaesiz.html

TS:   if (x == null) {}
来源：http://dali.jqgfzy.top/Article/details/gt2gyvlyfai.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yj20258888.top/Article/details/gt2iqpzirbn.html

Go:   if x == nil {}
来源：http://dali.fengsongda.top/Article/details/gt2mtcrjweb.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gogol.net.cn/Article/details/gt2fymskfqh.html

C#:   if (x is null) {}
来源：http://dali.mhx1999.top/Article/details/gt2xwxqhsem.html

[P07] 防抖与节流
来源：http://dali.yangfankeji.com/Article/details/gt2akudopnt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hongshengwenyu.top/Article/details/gt2qqazwqjb.html

PHP:  // 手写时间戳比较
来源：http://dali.nanxuanxn.top/Article/details/gt2vylyjskq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guannengcc.top/Article/details/gt2xawsdnlh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnxiangtu.top/Article/details/gt2dmjzufie.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhengqikj.top/Article/details/gt2hdncatjw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jinqigufen.top/Article/details/gt2kubuoouj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.aizwys.cn/Article/details/gt2vuhppubr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gotoacloud.top/Article/details/gt2smloknum.html

[P08] 处理浮点精度问题
来源：http://dali.haohaochexian.top/Article/details/gt2bdrymsgt.html


<!-- 参考信息 -->