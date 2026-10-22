代发 wailian999

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ehwqpu.com/Article/details/gtfrnlytbb.html

JS:   process.env.HOME
来源：http://dali.svipenyu.cn/Article/details/gtcmiuqjjw.html

TS:   process.env.HOME
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpkvxypfh.html

Java: System.getenv("HOME")
来源：http://dali.hysaishi.cn/Article/details/gtxbuainsz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ppjwa.cn/Article/details/gtakktrknk.html

Ruby: ENV["HOME"]
来源：http://dali.ivvv.top/Article/details/gtlgciiqun.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sufxvd.cn/Article/details/gtjaeioutp.html

[M03] 执行外部命令
来源：http://dali.wangshuangyany.cn/Article/details/gtytxmxwpj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yangfankeji.com/Article/details/gtswhfxjnr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jianghu66.top/Article/details/gtipyvspcs.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hysaishi.cn/Article/details/gtqsyxjewp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhengqikj.top/Article/details/gtyhzrtdet.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.daria6918.cn/Article/details/gtboyaopev.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zycfv.cn/Article/details/gtmwyiqncj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.daxiang520.top/Article/details/gtonnwipci.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tian-w.cn/Article/details/gtswpqzwjv.html

[M04] 获取当前工作目录
来源：http://dali.jiagoushi.top/Article/details/gtmrssfyhy.html

Py:   os.getcwd()
来源：http://dali.sufxvd.cn/Article/details/gtfzvsinde.html

PHP:  getcwd();
来源：http://dali.jinghuilouyu.cn/Article/details/gtwrzgwvxc.html

JS:   process.cwd()
来源：http://dali.sxryk.cn/Article/details/gtwdnlbmmc.html

TS:   process.cwd()
来源：http://dali.hongshengwenyu.top/Article/details/gtnivbzbnl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shanyushiyangtech.top/Article/details/gtifkwsuip.html

Go:   os.Getwd()
来源：http://dali.iojbl.cn/Article/details/gttipbkayi.html

Ruby: Dir.pwd
来源：http://dali.jlsjyb.cn/Article/details/gteylotkcp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.iojbl.cn/Article/details/gtxrqtoldn.html

[M05] 设置退出码
来源：http://dali.daxiang520.top/Article/details/gtqrgofwkg.html

Py:   sys.exit(1)
来源：http://dali.ivvv.top/Article/details/gtsocaavth.html

PHP:  exit(1);
来源：http://dali.pengpengdd.cyou/Article/details/gtsifewznq.html

JS:   process.exit(1)
来源：http://dali.ivvv.top/Article/details/gtvlacumct.html

TS:   process.exit(1)
来源：http://dali.xziqi.cn/Article/details/gtxqurtmav.html

Java: System.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gtklkxgrhe.html

Go:   os.Exit(1)
来源：http://dali.cashguo.top/Article/details/gtebyogolr.html

Ruby: exit 1
来源：http://dali.yvedp.cn/Article/details/gtoypkdzix.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.0kj1m.cn/Article/details/gtcnhubewb.html

[M06] 向标准错误输出
来源：http://dali.yueranfly.top/Article/details/gtttyviige.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gotoacloud.top/Article/details/gtptfkyhfx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hnxiangtu.top/Article/details/gthnawhols.html

JS:   console.error("err")
来源：http://dali.316326.xyz/Article/details/gtgmthcgwk.html

TS:   console.error("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnfxqvcnp.html

Java: System.err.println("err")
来源：http://dali.zhongyouzk.top/Article/details/gtggifpfpj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj20258.top/Article/details/gtkcknptmy.html

Ruby: warn "err"
来源：http://dali.yuxming.cn/Article/details/gttvetosxv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jqgfzy.top/Article/details/gtmyjvduim.html

[M07] 判断是否为主入口
来源：http://dali.redwolf501.top/Article/details/gtecfgbboh.html

Py:   if __name__ == "__main__":
来源：http://dali.nanxinkj.top/Article/details/gtiwbnnyxf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shuidangran.top/Article/details/gtjpiqutqf.html

JS:   require.main === module
来源：http://dali.zhongyouzk.top/Article/details/gtesitmahk.html

TS:   require.main === module
来源：http://dali.zhengqikj.top/Article/details/gtinuixvak.html

Java: public static void main(String[] args)
来源：http://dali.chenzaomai.com/Article/details/gtresedwxd.html

Go:   func main()
来源：http://dali.xziqi.cn/Article/details/gttnqpiycf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.daxiang520.top/Article/details/gtxkgfuhqi.html

C#:   static void Main(string[] args)
来源：http://dali.pengpengdd.cyou/Article/details/gtsnqttjpq.html

[M08] 获取系统与运行时信息
来源：http://dali.jqgfzy.top/Article/details/gtpzlhbfly.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sufxvd.cn/Article/details/gtczfrtclz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.guannengcc.top/Article/details/gtobkewrat.html

JS:   process.platform;  process.version
来源：http://dali.ybcxt.top/Article/details/gtfxqpyspi.html

TS:   process.platform;  process.version
来源：http://dali.mhx1999.top/Article/details/gtsspeljob.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hammf.cn/Article/details/gthdqyfenk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj202588.top/Article/details/gtdytubczn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zycfv.cn/Article/details/gtxhwbwyqc.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.smart0.xyz/Article/details/gtjpakvrfn.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtikjnrvoa.html

N. 数据结构与算法
来源：http://dali.sufxvd.cn/Article/details/gtcntvdavg.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtnjrykdfp.html

[N01] 二分查找（有序数组）
来源：http://dali.guannengcc.top/Article/details/gtvjwlxsbj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtmqznyaes.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jlsjyb.cn/Article/details/gttgetznox.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pengpengdd.cyou/Article/details/gtookenfpp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shzxlz.cn/Article/details/gthssvktvh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgggsvkgb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sweek.top/Article/details/gtgpwxhpwn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sxryk.cn/Article/details/gtafcalofg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtoldrthlk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ehwqpu.com/Article/details/gtnelkkzzt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.iojbl.cn/Article/details/gtjmxkmwrz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtullfxiph.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yongpay.top/Article/details/gtdwyhoqhr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.feifeiyinyue.top/Article/details/gtpgyveofk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.fzhhl.top/Article/details/gtsvxbcxva.html

Go:   slices.Sort(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnmvyprde.html

Ruby: arr.sort
来源：http://dali.jinqigufen.top/Article/details/gtbiimjnme.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xuanzx.com/Article/details/gtsnhmlrxm.html

[N03] 快速排序（分治示例）
来源：http://dali.jiagoushi.top/Article/details/gtivyasbqn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zdqjudy.top/Article/details/gtjddnljrw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinyuanbaomall.cn/Article/details/gttwgnswtl.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sysykeji.top/Article/details/gtwxuveopb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jianghu66.top/Article/details/gtcgxobzls.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ehwqpu.com/Article/details/gtzhnqtqnn.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.redwolf501.top/Article/details/gtxkyzwork.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinghuilouyu.cn/Article/details/gtpsutxazy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.pengpengdd.cyou/Article/details/gtowvzzkmu.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gthjozeisn.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zdqjudy.top/Article/details/gtymtlpkrl.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hnqzz.top/Article/details/gtlxkbecse.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.iojbl.cn/Article/details/gtyevfnvmu.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gtxhhyergu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhiwuduotai.top/Article/details/gtqjsupnpe.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jiagoushi.top/Article/details/gtnortvwzj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.kuanghao11.cn/Article/details/gtlnaivgde.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.316326.xyz/Article/details/gtciexkodz.html

[N05] 最大公约数
来源：http://dali.bjfxy.top/Article/details/gthwsxdexz.html

Py:   math.gcd(a, b)
来源：http://dali.yj20258.top/Article/details/gtaxacaqll.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.9152youxi.cn/Article/details/gtivorywbg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tianlin.xyz/Article/details/gtftulkdjn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cdnleiting.top/Article/details/gthonzvxxy.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xinyue.icu/Article/details/gtmctgnqbk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.vqdsnc.cn/Article/details/gtphirrxuc.html

Ruby: a.gcd(b)
来源：http://dali.fengsongda.top/Article/details/gtyqrivupe.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.quarkkingdee.top/Article/details/gtlwbejsma.html

[N06] 判断回文字符串
来源：http://dali.pycfn.com/Article/details/gtsrvhbusj.html

Py:   s == s[::-1]
来源：http://dali.xylfe.cn/Article/details/gtbmsbaorz.html

PHP:  $s === strrev($s);
来源：http://dali.nwbrower.top/Article/details/gtppcvnlen.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gtpuuvktyj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtwvrgcbix.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.fzhhl.top/Article/details/gtfdkoocfd.html

Go:   // 双指针从两端比较
来源：http://dali.zycfv.cn/Article/details/gttygzwguj.html

Ruby: s == s.reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gtnwrjyjst.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinqigufen.top/Article/details/gtsarhcwzg.html

[N07] 两数之和（返回下标）
来源：http://dali.tian-w.cn/Article/details/gtlfujzzdn.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ivvv.top/Article/details/gtzmjslfeh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sweek.top/Article/details/gtiaybvqji.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.0kj1m.cn/Article/details/gthdmqrjjk.html

TS:   // 手写 Map<string, number>
来源：http://dali.shuidangran.top/Article/details/gtiugektkl.html

Java: // 手写 HashMap
来源：http://dali.jqgfzy.top/Article/details/gtotjvaubv.html

Go:   // 手写 map[int]int
来源：http://dali.kuanghao11.cn/Article/details/gteakzsslb.html

Ruby: // 手写 Hash
来源：http://dali.jianghu66.top/Article/details/gtutdcucoy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.nanxuanxn.top/Article/details/gtixfswzje.html

[N08] 生成全排列
来源：http://dali.jinqigfzy.top/Article/details/gtbyfeozql.html

Py:   itertools.permutations(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtffpnmzwp.html

PHP:  // 手写递归交换
来源：http://dali.tianlin.xyz/Article/details/gtbscvfqtk.html

JS:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gtsemhhbav.html

TS:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gtgwoprulz.html

Java: // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gtdcanmpzb.html

Go:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gttzkgdzop.html

Ruby: arr.permutation.to_a
来源：http://dali.ppjwa.cn/Article/details/gtglfsqjez.html

C#:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpujbvqis.html

[N09] 栈与队列
来源：http://dali.smart0.xyz/Article/details/gtbsjrmhon.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.redwolf501.top/Article/details/gtnzcqusqm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhongyouzk.top/Article/details/gtxqjecssl.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xziqi.cn/Article/details/gtwzqlrokg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.smart0.xyz/Article/details/gtzpfvcrtr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yanxiufei.cn/Article/details/gthyeixmtn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yanxiufei.cn/Article/details/gtgqvugzss.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhongyouzk.top/Article/details/gtbsblcboe.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gaohongyu789.top/Article/details/gtdibuztbt.html

[N10] 链表节点定义
来源：http://dali.ybcxt.top/Article/details/gtyhtjecys.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yj20258.top/Article/details/gtoeaparak.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.dianchejie.cn/Article/details/gtviafebeu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xuanzx.com/Article/details/gthkloxgod.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.smart0.xyz/Article/details/gtckazdirm.html

Java: class Node { int v; Node next; }
来源：http://dali.wangshuangyany.cn/Article/details/gtldenuuvj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yangfankeji.com/Article/details/gtwwafjfgd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.dianchejie.cn/Article/details/gtcjtqajbs.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttyalfklz.html

[N11] 二叉树中序遍历
来源：http://dali.pycfn.com/Article/details/gtmvlrzmjk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yj20258.top/Article/details/gtayrpqoxe.html

PHP:  // 手写递归函数
来源：http://dali.dianchejie.cn/Article/details/gtzjazxqxp.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.smart0.xyz/Article/details/gtvzohzovs.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xinyue.icu/Article/details/gtpzialzov.html

Java: // 手写递归
来源：http://dali.chenzaomai.com/Article/details/gtpslffwmw.html

Go:   // 手写递归
来源：http://dali.zhixingplan.top/Article/details/gtlopkofry.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yj20258888.top/Article/details/gtnatiprur.html

C#:   // 手写递归
来源：http://dali.0kj1m.cn/Article/details/gtrwpwlufk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zycfv.cn/Article/details/gtymuzpuiw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinqigufen.top/Article/details/gtzqiifegl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.tian-w.cn/Article/details/gtwphzlkru.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.9152youxi.cn/Article/details/gtsjgzejsn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cashguo.top/Article/details/gtqmomjozc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xylfe.cn/Article/details/gtpgolrygs.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.0kj1m.cn/Article/details/gtgxeczkxj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zdqjudy.top/Article/details/gtxuiaqmth.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkycoloko.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtadqhfaug.html

O. 并发与异步
来源：http://dali.yanxiufei.cn/Article/details/gtkrohsiml.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtzsybgnsy.html

[O01] 启动一个线程
来源：http://dali.gaohongyu789.top/Article/details/gtqyptmvlm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cdnleiting.top/Article/details/gtkkmntkuq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sxryk.cn/Article/details/gtavokvsgq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.tanke756.top/Article/details/gtxnszsvai.html

TS:   // 同 JS
来源：http://dali.tian-w.cn/Article/details/gtnetjothz.html

Java: new Thread(() -> f()).start()
来源：http://dali.jiagoushi.top/Article/details/gtpgvbhpkl.html

Go:   go f()
来源：http://dali.andypj.xyz/Article/details/gtoebucvsn.html

Ruby: Thread.new { f }
来源：http://dali.zhengqikj.top/Article/details/gtoyrfoogl.html

C#:   Task.Run(() => F());
来源：http://dali.0kj1m.cn/Article/details/gtndtznkrm.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gttpydywrq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.fengsongda.top/Article/details/gtqfnmzdnu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yueranfly.top/Article/details/gtxgvpxrio.html

JS:   // worker_threads 线程池
来源：http://dali.yj202588.top/Article/details/gteugslotz.html

TS:   // worker_threads 线程池
来源：http://dali.fengsongda.top/Article/details/gtukqnfaus.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.gogol.net.cn/Article/details/gtvtwkrfmm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.tianlin.xyz/Article/details/gtlhdorktf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.haohaochexian.top/Article/details/gtqgsadzgz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zdqjudy.top/Article/details/gtuggcuvnm.html

[O03] 加锁保护共享数据
来源：http://dali.pycfn.com/Article/details/gtuxvpioqy.html

Py:   with lock: shared += 1
来源：http://dali.daria6918.cn/Article/details/gtvvdfrsdx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.tian-w.cn/Article/details/gtskxoobvt.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.haohaochexian.top/Article/details/gthezxmyjh.html

TS:   // 同 JS
来源：http://dali.hfpthk.cn/Article/details/gttmgyeodn.html

Java: synchronized (this) { shared++; }
来源：http://dali.yuanzhike.top/Article/details/gtngrdfoql.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cheryme.top/Article/details/gtiaabeiou.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hammf.cn/Article/details/gtwyjihebi.html

C#:   lock (gate) { shared++; }
来源：http://dali.nanxuanxn.top/Article/details/gteklkcdrj.html

[O04] 定义异步函数并等待
来源：http://dali.316326.xyz/Article/details/gtcostfqhy.html

Py:   async def f():⏎    await g()
来源：http://dali.dashuyun.cn/Article/details/gtkzqgkmdl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.aizwys.cn/Article/details/gtqaqqhtyb.html

JS:   async function f() { await g(); }
来源：http://dali.daria6918.cn/Article/details/gtarbigrfy.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtantblveg.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yanxiufei.cn/Article/details/gtzdcdsvqk.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jqgufenzy.top/Article/details/gtmmcifhjc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.dianchejie.cn/Article/details/gtpazrlzgn.html

C#:   async Task F() { await G(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcepltrrm.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhengqikj.top/Article/details/gtrbchvcrv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yj202588.top/Article/details/gtfyfhfuht.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jlsjyb.cn/Article/details/gtymxejgxg.html

JS:   await Promise.all(tasks)
来源：http://dali.jqgufenzy.top/Article/details/gtzjprczub.html

TS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdeuhflgy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yangfankeji.com/Article/details/gttgzeohgs.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.kuanghao11.cn/Article/details/gtkfmnoleu.html

Ruby: threads.map(&:join)
来源：http://dali.jinqigufen.top/Article/details/gtnvwdconf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfvibodhr.html

[O06] 使用进程池
来源：http://dali.yuanzhike.top/Article/details/gtscctgfmb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zycfv.cn/Article/details/gtxrcxrusm.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gzhubu.top/Article/details/gtzgpfaszg.html

JS:   // child_process / cluster 模块
来源：http://dali.ppjwa.cn/Article/details/gtnlxhusan.html

TS:   // child_process / cluster 模块
来源：http://dali.chenlongwang.top/Article/details/gtqfuuzhkq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xylfe.cn/Article/details/gtatxazcoa.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hongshengwenyu.top/Article/details/gtcacluzpx.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gtaticblly.html

C#:   Parallel.For
来源：http://dali.cqqwz.cn/Article/details/gtzhfzoeoa.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gttttlivfs.html

P. 常用工具函数
来源：http://dali.c1oappe.top/Article/details/gtovumgcul.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtebcazbbh.html

[P01] 生成 UUID
来源：http://dali.yj20258888.top/Article/details/gtpxfuupis.html

Py:   str(uuid.uuid4())
来源：http://dali.xuanzx.com/Article/details/gtaidlcpcf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zycfv.cn/Article/details/gtcdjvfswl.html

JS:   crypto.randomUUID()
来源：http://dali.gogol.net.cn/Article/details/gtbbxasoaf.html

TS:   crypto.randomUUID()
来源：http://dali.mhx1999.top/Article/details/gtrxgvqnxx.html

Java: UUID.randomUUID().toString()
来源：http://dali.shangyingyoupin.top/Article/details/gtjulwrmgh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xinyue.icu/Article/details/gtdluoofpj.html

Ruby: SecureRandom.uuid
来源：http://dali.ehwqpu.com/Article/details/gtinkdsnqg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shangyingyoupin.top/Article/details/gtwsooqomd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cdnleiting.top/Article/details/gtcqrbawjn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenlongwang.top/Article/details/gtbfjanfnr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.nwbrower.top/Article/details/gtsiimyhfg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gtjojbcxrq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hnqzz.top/Article/details/gtvsckiosl.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj202588.top/Article/details/gtcvyzymvl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ydzc1.top/Article/details/gtrnugewxr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ydzc1.top/Article/details/gtkrkcvmqf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xuetiantiany.cn/Article/details/gtkcuyqcby.html

[P03] 生成短随机字符串
来源：http://dali.gotoacloud.top/Article/details/gtxtunbscu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.andypj.xyz/Article/details/gtncuvrhkl.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjodskfyj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjayzqmre.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.kuanghao11.cn/Article/details/gtzwryimyw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhoulong.xyz/Article/details/gtowhchnox.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.feifeiyinyue.top/Article/details/gtnzbzzzcp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xylfe.cn/Article/details/gtpszazwyk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shanyushiyangtech.top/Article/details/gtusdsseoh.html

[P04] 求长度
来源：http://dali.dianchejie.cn/Article/details/gtfefwgcom.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hysaishi.cn/Article/details/gtofczujou.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcbafgyex.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.havefunace.top/Article/details/gtrgmivcni.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fengsongda.top/Article/details/gtplwobdgt.html

Java: list.size();  map.size();  s.length()
来源：http://dali.chenjidiqi.icu/Article/details/gtsrzcxsge.html

Go:   len(arr);  len(m)
来源：http://dali.zhengqikj.top/Article/details/gtkimzsveh.html

Ruby: x.length;  x.size
来源：http://dali.tian-w.cn/Article/details/gtypacjwfz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hfpthk.cn/Article/details/gtqibzxxat.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hongshengwenyu.top/Article/details/gtxxuwrvhg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.9152youxi.cn/Article/details/gtwtcpwccz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jianghu66.top/Article/details/gtqurhosag.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yonumen.top/Article/details/gtolwgmera.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.fengsongda.top/Article/details/gtnbpowqqo.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.wangshuangyany.cn/Article/details/gtepqmxzwx.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.tanke756.top/Article/details/gtioaiynkw.html

Ruby: a == b
来源：http://dali.yuanzhike.top/Article/details/gtwprazfpg.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yuxming.cn/Article/details/gtjrfiqgps.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yvedp.cn/Article/details/gtiamigcir.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.nwbrower.top/Article/details/gtlxhlrxxl.html

PHP:  if (empty($x)) {}
来源：http://dali.zhoulong.xyz/Article/details/gtwdntmysc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.smart0.xyz/Article/details/gttmjdhrnf.html

TS:   if (x == null) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwfqmomrp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jianghu66.top/Article/details/gtpcsypztg.html

Go:   if x == nil {}
来源：http://dali.cucudq.cn/Article/details/gtqwbaqgez.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cqqwz.cn/Article/details/gtextcbcgk.html

C#:   if (x is null) {}
来源：http://dali.tanke756.top/Article/details/gtkftrqsdp.html

[P07] 防抖与节流
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrtvkzuuw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gotoacloud.top/Article/details/gtdgrwvuby.html

PHP:  // 手写时间戳比较
来源：http://dali.fengsongda.top/Article/details/gtaehcrhmz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenlongwang.top/Article/details/gtuxoapick.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.quarkkingdee.top/Article/details/gtmmxcsfnl.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthxqccehs.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhixingplan.top/Article/details/gthoedywyv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gtaofqtgwl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhengqikj.top/Article/details/gtaeyyxnjg.html

[P08] 处理浮点精度问题
来源：http://dali.yanxiufei.cn/Article/details/gtpfnctgco.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.mhx1999.top/Article/details/gtqfgdtmhq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ehwqpu.com/Article/details/gtqrvchgqp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cdnleiting.top/Article/details/gtefpoumqq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhengqikj.top/Article/details/gtgotmamju.html


<!-- 参考信息 -->