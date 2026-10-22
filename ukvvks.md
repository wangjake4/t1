代发 wailian999

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gtmtrpqtqm.html

Ruby: ENV["HOME"]
来源：http://dali.yangfankeji.com/Article/details/gtrlspxupy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gthjiieyoy.html

[M03] 执行外部命令
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmgjqrrs.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwdzoobcw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tian-w.cn/Article/details/gtpztwxcvd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shuidangran.top/Article/details/gtgpdmctrf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.smart0.xyz/Article/details/gtwhbmykti.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zycfv.cn/Article/details/gttoocoulh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xuetiantiany.cn/Article/details/gtciuzyxdd.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.wangshuangyany.cn/Article/details/gtvuexpgop.html

C#:   Process.Start("ls", "-l");
来源：http://dali.9152youxi.cn/Article/details/gtwkdwprmv.html

[M04] 获取当前工作目录
来源：http://dali.zhixingplan.top/Article/details/gtkaxksojj.html

Py:   os.getcwd()
来源：http://dali.daxiang520.top/Article/details/gthecitxad.html

PHP:  getcwd();
来源：http://dali.sxryk.cn/Article/details/gtwtlicuyl.html

JS:   process.cwd()
来源：http://dali.cdnleiting.top/Article/details/gtjrwpsvmk.html

TS:   process.cwd()
来源：http://dali.mhx1999.top/Article/details/gtyrqivkny.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.wangdashe.top/Article/details/gtjtntwffw.html

Go:   os.Getwd()
来源：http://dali.hywenlv.cn/Article/details/gtfttiahcd.html

Ruby: Dir.pwd
来源：http://dali.hnqzz.top/Article/details/gtzydjvcbb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cheryme.top/Article/details/gthqoqhmgh.html

[M05] 设置退出码
来源：http://dali.dianchejie.cn/Article/details/gtyxidhstr.html

Py:   sys.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtcxhefgot.html

PHP:  exit(1);
来源：http://dali.mhx1999.top/Article/details/gtumqwszay.html

JS:   process.exit(1)
来源：http://dali.yongpay.top/Article/details/gtmvcagsoq.html

TS:   process.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gtgbovyolg.html

Java: System.exit(1)
来源：http://dali.hnqzz.top/Article/details/gtvntlabfz.html

Go:   os.Exit(1)
来源：http://dali.yj20258888.top/Article/details/gtcymitqxp.html

Ruby: exit 1
来源：http://dali.hnxiangtu.top/Article/details/gtwyrcbnwi.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ivvv.top/Article/details/gtyirxapvh.html

[M06] 向标准错误输出
来源：http://dali.cheryme.top/Article/details/gtmdpwmrzi.html

Py:   print("err", file=sys.stderr)
来源：http://dali.havefunace.top/Article/details/gtmiviiywa.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xylfe.cn/Article/details/gtnadbuolg.html

JS:   console.error("err")
来源：http://dali.sufxvd.cn/Article/details/gtfkfegxit.html

TS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gteqjfxdps.html

Java: System.err.println("err")
来源：http://dali.316326.xyz/Article/details/gtpbmeqvfu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.vqdsnc.cn/Article/details/gtjxsszmqu.html

Ruby: warn "err"
来源：http://dali.xuanzx.com/Article/details/gtnncohhfx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tanke756.top/Article/details/gtknqljiei.html

[M07] 判断是否为主入口
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlrvtwgyv.html

Py:   if __name__ == "__main__":
来源：http://dali.dianchejie.cn/Article/details/gtilbjwuad.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.dianchejie.cn/Article/details/gtnejdjrge.html

JS:   require.main === module
来源：http://dali.ybcxt.top/Article/details/gtjpwtnmet.html

TS:   require.main === module
来源：http://dali.316326.xyz/Article/details/gtcrfbklog.html

Java: public static void main(String[] args)
来源：http://dali.zhiwuduotai.top/Article/details/gtmdmguomk.html

Go:   func main()
来源：http://dali.redwolf501.top/Article/details/gtqjhiyfff.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ehwqpu.com/Article/details/gtcwdywgsf.html

C#:   static void Main(string[] args)
来源：http://dali.cheryme.top/Article/details/gtescouiui.html

[M08] 获取系统与运行时信息
来源：http://dali.jinghuilouyu.cn/Article/details/gtjnhntmej.html

Py:   platform.system();  platform.python_version()
来源：http://dali.chenlongwang.top/Article/details/gtjwqaupan.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yangfankeji.com/Article/details/gtsdpsiibd.html

JS:   process.platform;  process.version
来源：http://dali.zhoulong.xyz/Article/details/gtnhqkfppn.html

TS:   process.platform;  process.version
来源：http://dali.ydzc1.top/Article/details/gtbuvdmlpx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.9152youxi.cn/Article/details/gttwocofxe.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yonumen.top/Article/details/gtltbxokwr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.c1oappe.top/Article/details/gtbyeewtmt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yanxiufei.cn/Article/details/gtnwvgigoe.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtzrhfumpo.html

N. 数据结构与算法
来源：http://dali.cashguo.top/Article/details/gtgeprmatn.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtoozgrtjj.html

[N01] 二分查找（有序数组）
来源：http://dali.havefunace.top/Article/details/gtmsntalhx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtmyurbjvq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlocivrwq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cqqwz.cn/Article/details/gtntqhqnup.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hfpthk.cn/Article/details/gtmhjnepgm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtamlwmuzz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hnqzz.top/Article/details/gtsugbuugi.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.bjfxy.top/Article/details/gtnutwhfqf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtepqxrvfl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.dianchejie.cn/Article/details/gtnmvsbzgq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.quarkkingdee.top/Article/details/gtzljwoqyq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sxryk.cn/Article/details/gtyurbxljs.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gaohongyu789.top/Article/details/gtnzdpvurk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gogol.net.cn/Article/details/gtnxcvfxop.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hnxiangtu.top/Article/details/gthoiteysl.html

Go:   slices.Sort(arr)
来源：http://dali.fzhhl.top/Article/details/gtxnnkpwcq.html

Ruby: arr.sort
来源：http://dali.hongshengwenyu.top/Article/details/gtkpzeymoy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.aibaodan.cn/Article/details/gtygovkmyz.html

[N03] 快速排序（分治示例）
来源：http://dali.yj202588.top/Article/details/gtpafkzztf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hnqzz.top/Article/details/gtygolmucy.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gzhubu.top/Article/details/gtgwbqjlkv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guannengcc.top/Article/details/gtnzyqodqy.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.meibo888.top/Article/details/gtyqanrwwl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xinyue.icu/Article/details/gtlzlmrzal.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sweek.top/Article/details/gtwrjlyezf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.birdmap.top/Article/details/gtmpnbtaod.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.snrcjt.cn/Article/details/gtqfjgldph.html

[N04] 斐波那契数列
来源：http://dali.guannengcc.top/Article/details/gtghxfokcm.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yonumen.top/Article/details/gtwbulyatf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.mhx1999.top/Article/details/gtcqqgzkpj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnqzz.top/Article/details/gtgrrekyjc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gtqeqhlggu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cqqwz.cn/Article/details/gtxqntmxng.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zycfv.cn/Article/details/gtkmsvdshu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hywenlv.cn/Article/details/gthjxjxddc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.chenzaomai.com/Article/details/gtflglhldk.html

[N05] 最大公约数
来源：http://dali.pycfn.com/Article/details/gtwjcskerl.html

Py:   math.gcd(a, b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgloustvh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.nanxinkj.top/Article/details/gtpjdhmjyt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenjidiqi.icu/Article/details/gtbehbnbur.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdraoizjc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.dianchejie.cn/Article/details/gtjqonfckx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yj20258888.top/Article/details/gtynolkmdy.html

Ruby: a.gcd(b)
来源：http://dali.nwbrower.top/Article/details/gtzekuegzy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yuxming.cn/Article/details/gtvyjnetwi.html

[N06] 判断回文字符串
来源：http://dali.aizwys.cn/Article/details/gtdjkazufg.html

Py:   s == s[::-1]
来源：http://dali.zhiwuduotai.top/Article/details/gtxosgetii.html

PHP:  $s === strrev($s);
来源：http://dali.gotoacloud.top/Article/details/gtgdqsnbji.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gtluledmsd.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gtyweyogej.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cheryme.top/Article/details/gtimoehzgm.html

Go:   // 双指针从两端比较
来源：http://dali.guowangkeji.top/Article/details/gtzoogxads.html

Ruby: s == s.reverse
来源：http://dali.aizwys.cn/Article/details/gtzfkpbkfd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cucudq.cn/Article/details/gtgsxspdqa.html

[N07] 两数之和（返回下标）
来源：http://dali.nanxinkj.top/Article/details/gtopkqhwiw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.aibaodan.cn/Article/details/gtcuertrvb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.pengpengdd.cyou/Article/details/gtuuedcoap.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.andypj.xyz/Article/details/gtjbynaqiy.html

TS:   // 手写 Map<string, number>
来源：http://dali.ydzc1.top/Article/details/gtyotfdiyz.html

Java: // 手写 HashMap
来源：http://dali.nanxuanxn.top/Article/details/gtgflnldht.html

Go:   // 手写 map[int]int
来源：http://dali.andypj.xyz/Article/details/gticfefrpf.html

Ruby: // 手写 Hash
来源：http://dali.hnqzz.top/Article/details/gtjkkltkge.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.dianchejie.cn/Article/details/gtzwkljlya.html

[N08] 生成全排列
来源：http://dali.jinqigufen.top/Article/details/gtxtpdwfks.html

Py:   itertools.permutations(arr)
来源：http://dali.shzxlz.cn/Article/details/gtzuimwwzc.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gteosicrve.html

JS:   // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gtzhwjunwf.html

TS:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtiiglmlgg.html

Java: // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gtgaznkdgh.html

Go:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtskykscjj.html

Ruby: arr.permutation.to_a
来源：http://dali.hywenlv.cn/Article/details/gtrqqjgodn.html

C#:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gtawujdwul.html

[N09] 栈与队列
来源：http://dali.xziqi.cn/Article/details/gtmfojuves.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cheryme.top/Article/details/gtwgdyysdz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.tanke756.top/Article/details/gthgrikqtp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hysaishi.cn/Article/details/gtbjrlszbp.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gteycptoyg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.snrcjt.cn/Article/details/gtarswilxg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.tanke756.top/Article/details/gtyfxztyxp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nanxuanxn.top/Article/details/gtyeamxjgy.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhongyouzk.top/Article/details/gtgoitporb.html

[N10] 链表节点定义
来源：http://dali.smart0.xyz/Article/details/gtwxhazdmz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ybcxt.top/Article/details/gtcpyewlnc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.vqdsnc.cn/Article/details/gtpppvrmjj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jyoumei.cn/Article/details/gtqrcwgggl.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yvedp.cn/Article/details/gtrjsccxch.html

Java: class Node { int v; Node next; }
来源：http://dali.cashguo.top/Article/details/gtpopssjbp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ybcxt.top/Article/details/gtfsnaoesh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yj20258888.top/Article/details/gtapoobcij.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hongshengwenyu.top/Article/details/gtpljnxpjd.html

[N11] 二叉树中序遍历
来源：http://dali.jinqigufen.top/Article/details/gtrywxicdi.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.quarkkingdee.top/Article/details/gtvdbpdpor.html

PHP:  // 手写递归函数
来源：http://dali.hnqzz.top/Article/details/gtaozlindl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.andypj.xyz/Article/details/gtthfffqew.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hongshengwenyu.top/Article/details/gtnyqtgofw.html

Java: // 手写递归
来源：http://dali.0kj1m.cn/Article/details/gtcgylqavp.html

Go:   // 手写递归
来源：http://dali.yvedp.cn/Article/details/gtlkjodfyl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhongyouzk.top/Article/details/gtqlsilaja.html

C#:   // 手写递归
来源：http://dali.vqdsnc.cn/Article/details/gthvezvwqg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.nanxinkj.top/Article/details/gtxlsgnlyk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.fzhhl.top/Article/details/gtuvddzuli.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hongshengwenyu.top/Article/details/gtadwmrmoy.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tanke756.top/Article/details/gtmwzbspss.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.kuanghao11.cn/Article/details/gtgigaxakf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258888.top/Article/details/gtgytfklml.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ehwqpu.com/Article/details/gtkndeifsc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.nwbrower.top/Article/details/gtdczryann.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pycfn.com/Article/details/gtdcrcfcln.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmwxqrvnt.html

O. 并发与异步
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvjfvueef.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtbxbvedtc.html

[O01] 启动一个线程
来源：http://dali.sxryk.cn/Article/details/gtydrpcjlq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.fengsongda.top/Article/details/gtaczhvhhn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.nwbrower.top/Article/details/gtsvqfacva.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zdqjudy.top/Article/details/gtzhromrzl.html

TS:   // 同 JS
来源：http://dali.hnqzz.top/Article/details/gtvichsomj.html

Java: new Thread(() -> f()).start()
来源：http://dali.yj20258888.top/Article/details/gtxlvjrhvd.html

Go:   go f()
来源：http://dali.ehwqpu.com/Article/details/gtwgfucrne.html

Ruby: Thread.new { f }
来源：http://dali.hongshengwenyu.top/Article/details/gtfgrkmwgw.html

C#:   Task.Run(() => F());
来源：http://dali.jinyuanbaomall.cn/Article/details/gtunlhgdbl.html

[O02] 使用线程池
来源：http://dali.daria6918.cn/Article/details/gtpcfiexye.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.daxiang520.top/Article/details/gtrhkagjln.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.redwolf501.top/Article/details/gtvypsgmos.html

JS:   // worker_threads 线程池
来源：http://dali.havefunace.top/Article/details/gtpkbaocvh.html

TS:   // worker_threads 线程池
来源：http://dali.cheryme.top/Article/details/gtkyjohkcw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhiwuduotai.top/Article/details/gtxfaeaxpp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hammf.cn/Article/details/gtdvrmfhou.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shanyushiyangtech.top/Article/details/gtqcshbcnb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jqgfzy.top/Article/details/gtlqkdqbfw.html

[O03] 加锁保护共享数据
来源：http://dali.tianlin.xyz/Article/details/gtoaddcyiv.html

Py:   with lock: shared += 1
来源：http://dali.iojbl.cn/Article/details/gtnynuclmy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sxryk.cn/Article/details/gtieuztqjm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.redwolf501.top/Article/details/gtssilkeoe.html

TS:   // 同 JS
来源：http://dali.dianchejie.cn/Article/details/gtykmqxojz.html

Java: synchronized (this) { shared++; }
来源：http://dali.fengsongda.top/Article/details/gtcwgzavxh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gogol.net.cn/Article/details/gtcwiynhnl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinghuilouyu.cn/Article/details/gthzzqnnsj.html

C#:   lock (gate) { shared++; }
来源：http://dali.aibaodan.cn/Article/details/gtgyomcwyu.html

[O04] 定义异步函数并等待
来源：http://dali.jinghuilouyu.cn/Article/details/gtbebcemnr.html

Py:   async def f():⏎    await g()
来源：http://dali.jqgufenzy.top/Article/details/gtrytmzxbw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.wangshuangyany.cn/Article/details/gtzjmilddd.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gtepawcbnb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xziqi.cn/Article/details/gthsngwyul.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.guowangkeji.top/Article/details/gtwybttbcp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ivvv.top/Article/details/gtstbvmkvn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hywenlv.cn/Article/details/gtjkfkkhyw.html

C#:   async Task F() { await G(); }
来源：http://dali.chenlongwang.top/Article/details/gtdaewdagv.html

[O05] 并发执行并等待全部完成
来源：http://dali.cheryme.top/Article/details/gtgdterseb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdpazsjrt.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.aibaodan.cn/Article/details/gtqpltdpcq.html

JS:   await Promise.all(tasks)
来源：http://dali.nanxuanxn.top/Article/details/gtdxysnfxr.html

TS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtibkglbcd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cdnleiting.top/Article/details/gtewkfgtim.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.nanxuanxn.top/Article/details/gtolqznmfw.html

Ruby: threads.map(&:join)
来源：http://dali.xuanzx.com/Article/details/gtwvluspwu.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnritvdhj.html

[O06] 使用进程池
来源：http://dali.jinqigufen.top/Article/details/gtqmkshbdn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xinyue.icu/Article/details/gtjjgztyyb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yuanzhike.top/Article/details/gtbnuojhcq.html

JS:   // child_process / cluster 模块
来源：http://dali.dashuyun.cn/Article/details/gtcuzrenks.html

TS:   // child_process / cluster 模块
来源：http://dali.xinyue.icu/Article/details/gttvnvnqwb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gogol.net.cn/Article/details/gttbvqunin.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.bjfxy.top/Article/details/gtmcbyzqxz.html

Ruby: // fork 块
来源：http://dali.fengsongda.top/Article/details/gtksocyiby.html

C#:   Parallel.For
来源：http://dali.zhengqikj.top/Article/details/gtzifawafk.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtfjpwpize.html

P. 常用工具函数
来源：http://dali.zhongyouzk.top/Article/details/gtxihorrkf.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gttpgynweb.html

[P01] 生成 UUID
来源：http://dali.jlsjyb.cn/Article/details/gtlaipzula.html

Py:   str(uuid.uuid4())
来源：http://dali.c1oappe.top/Article/details/gtoapzcuwu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnkkxzlic.html

JS:   crypto.randomUUID()
来源：http://dali.hongshengwenyu.top/Article/details/gtuhxwpdqy.html

TS:   crypto.randomUUID()
来源：http://dali.xziqi.cn/Article/details/gtcyjldnhy.html

Java: UUID.randomUUID().toString()
来源：http://dali.ehwqpu.com/Article/details/gtcxtvmfzc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jiagoushi.top/Article/details/gtjeedwgcy.html

Ruby: SecureRandom.uuid
来源：http://dali.yangfankeji.com/Article/details/gtzciwjjks.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.svipenyu.cn/Article/details/gtmevyofuc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sysykeji.top/Article/details/gtzqfqaddf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gtcycbfnvk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yj20258888.top/Article/details/gtdfbfzsur.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.daria6918.cn/Article/details/gtbtlvavqd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.fzhhl.top/Article/details/gtgynxnlzi.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cashguo.top/Article/details/gtjxcuvlze.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.fengsongda.top/Article/details/gtnjqikeas.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xylfe.cn/Article/details/gtaadkfmmw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.dashuyun.cn/Article/details/gtawygqdhl.html

[P03] 生成短随机字符串
来源：http://dali.yonumen.top/Article/details/gtxxpdorag.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.haohaochexian.top/Article/details/gtnszibhnk.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.meibo888.top/Article/details/gtkfsonemx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtxmdceagx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtougqxrtf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.gaohongyu789.top/Article/details/gtjzgursqq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shzxlz.cn/Article/details/gtvwnxnkdn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.tianlin.xyz/Article/details/gtacelpgxk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.andypj.xyz/Article/details/gtacxjhhse.html

[P04] 求长度
来源：http://dali.zhongyouzk.top/Article/details/gtjasgvslq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yuanzhike.top/Article/details/gtvcdcvzht.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gtqsgugrqy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jlsjyb.cn/Article/details/gtwqpjkgwt.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.wangdashe.top/Article/details/gtnxjicofq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hfpthk.cn/Article/details/gtgpylnesp.html

Go:   len(arr);  len(m)
来源：http://dali.yonumen.top/Article/details/gttbqeoppi.html

Ruby: x.length;  x.size
来源：http://dali.xziqi.cn/Article/details/gtltyisozf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.tianlin.xyz/Article/details/gthelltkcc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hywenlv.cn/Article/details/gtopsznffs.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.tanke756.top/Article/details/gtkvtoohjc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gzhubu.top/Article/details/gthdtsjbnz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yuanzhike.top/Article/details/gtzveafxfn.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenzaomai.com/Article/details/gtlhfbijqp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.dashuyun.cn/Article/details/gtbihrircz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.wangshuangyany.cn/Article/details/gtyyczvhzw.html

Ruby: a == b
来源：http://dali.shangyingyoupin.top/Article/details/gtaofgykns.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.nwbrower.top/Article/details/gtttxzevgb.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cheryme.top/Article/details/gtnkyknasz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yangfankeji.com/Article/details/gtexddpwyy.html

PHP:  if (empty($x)) {}
来源：http://dali.snrcjt.cn/Article/details/gtvgsnazxv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xuetiantiany.cn/Article/details/gtjjgllyjx.html

TS:   if (x == null) {}
来源：http://dali.tanke756.top/Article/details/gticbpcbqi.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gaohongyu789.top/Article/details/gtxlbnmsrp.html

Go:   if x == nil {}
来源：http://dali.xuanzx.com/Article/details/gtmyzfkjrd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.c1oappe.top/Article/details/gttsnnfzpp.html

C#:   if (x is null) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtnqaebfnm.html

[P07] 防抖与节流
来源：http://dali.dianchejie.cn/Article/details/gtoerjbkme.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.andypj.xyz/Article/details/gtehupnjqq.html

PHP:  // 手写时间戳比较
来源：http://dali.gogol.net.cn/Article/details/gtbyedcyrj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nwbrower.top/Article/details/gtuhnjjbyt.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxinkj.top/Article/details/gtmqaamucn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.fzhhl.top/Article/details/gtrchtwnjl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yj20258888.top/Article/details/gtgumcvzqr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgjbpiflm.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zdqjudy.top/Article/details/gtphbdlxte.html

[P08] 处理浮点精度问题
来源：http://dali.ppjwa.cn/Article/details/gtjedhdmfn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yangfankeji.com/Article/details/gthdtentmy.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.redwolf501.top/Article/details/gtdpxyvfdr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.gaohongyu789.top/Article/details/gtcvyqagkl.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hywenlv.cn/Article/details/gtvlsxfrti.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.guowangkeji.top/Article/details/gtawrgcbeq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.daria6918.cn/Article/details/gtefvscgrw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.nwbrower.top/Article/details/gtmtmvkwwi.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.tianlin.xyz/Article/details/gttfrwcpxu.html


<!-- 参考信息 -->