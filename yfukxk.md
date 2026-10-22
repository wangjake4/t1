代发 wailian999

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.0kj1m.cn/Article/details/gt2zcoyjgwf.html

JS:   process.env.HOME
来源：http://dali.fzhhl.top/Article/details/gt2mksfvgwa.html

TS:   process.env.HOME
来源：http://dali.xuanzx.com/Article/details/gt2exacdfnv.html

Java: System.getenv("HOME")
来源：http://dali.gotoacloud.top/Article/details/gt2zaxsxwmy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sweek.top/Article/details/gt2mnxdvpoj.html

Ruby: ENV["HOME"]
来源：http://dali.iojbl.cn/Article/details/gt2iycuiuhe.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gt2uzxyphpk.html

[M03] 执行外部命令
来源：http://dali.meibo888.top/Article/details/gt2lwhamiqs.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xziqi.cn/Article/details/gt2zieuewda.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhoulong.xyz/Article/details/gt2erizawrh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenlongwang.top/Article/details/gt2viojejke.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhiwuduotai.top/Article/details/gt2unvnabkh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.nwbrower.top/Article/details/gt2dapnrfqk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hongshengwenyu.top/Article/details/gt2xxykrudj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.bjfxy.top/Article/details/gt2hcrlesen.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sysykeji.top/Article/details/gt2suguuaym.html

[M04] 获取当前工作目录
来源：http://dali.shangyingyoupin.top/Article/details/gt2xrykgpiy.html

Py:   os.getcwd()
来源：http://dali.xinyue.icu/Article/details/gt2liuglipi.html

PHP:  getcwd();
来源：http://dali.shzxlz.cn/Article/details/gt2oxkwhssb.html

JS:   process.cwd()
来源：http://dali.nanxinkj.top/Article/details/gt2bzycbjqi.html

TS:   process.cwd()
来源：http://dali.shangyingyoupin.top/Article/details/gt2duyqnmrm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.316326.xyz/Article/details/gt2usouzmlk.html

Go:   os.Getwd()
来源：http://dali.zhiwuduotai.top/Article/details/gt2sqwnfstq.html

Ruby: Dir.pwd
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lqsdjozo.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nanxuanxn.top/Article/details/gt2ydmkggkd.html

[M05] 设置退出码
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ctbwtbly.html

Py:   sys.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gt2ghdgnbed.html

PHP:  exit(1);
来源：http://dali.cheryme.top/Article/details/gt2reumxokj.html

JS:   process.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2yyidnfxh.html

TS:   process.exit(1)
来源：http://dali.sxryk.cn/Article/details/gt2kraznvgw.html

Java: System.exit(1)
来源：http://dali.xuanzx.com/Article/details/gt2ptzdttkb.html

Go:   os.Exit(1)
来源：http://dali.tianlin.xyz/Article/details/gt2bmzgejdp.html

Ruby: exit 1
来源：http://dali.sysykeji.top/Article/details/gt2ahohpebn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xziqi.cn/Article/details/gt2klixgiue.html

[M06] 向标准错误输出
来源：http://dali.wangdashe.top/Article/details/gt2rmmbdsqb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.daxiang520.top/Article/details/gt2aeeqoeru.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jqgfzy.top/Article/details/gt2omjuyukm.html

JS:   console.error("err")
来源：http://dali.shangyingyoupin.top/Article/details/gt2pqojjhoy.html

TS:   console.error("err")
来源：http://dali.hfpthk.cn/Article/details/gt2jskqmrfx.html

Java: System.err.println("err")
来源：http://dali.tian-w.cn/Article/details/gt2kexdlssk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.daria6918.cn/Article/details/gt2jmcztoux.html

Ruby: warn "err"
来源：http://dali.guowangkeji.top/Article/details/gt2mxeiqkpa.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhixingplan.top/Article/details/gt2cnzttuwi.html

[M07] 判断是否为主入口
来源：http://dali.jlsjyb.cn/Article/details/gt2unqmxdpp.html

Py:   if __name__ == "__main__":
来源：http://dali.smart0.xyz/Article/details/gt2exxjmdcw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gotoacloud.top/Article/details/gt2vrmjpnnw.html

JS:   require.main === module
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lfyhmomg.html

TS:   require.main === module
来源：http://dali.ppjwa.cn/Article/details/gt2fdnqstqv.html

Java: public static void main(String[] args)
来源：http://dali.sweek.top/Article/details/gt2gjuescrr.html

Go:   func main()
来源：http://dali.yj202588.top/Article/details/gt2zhgorjtz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.pycfn.com/Article/details/gt2fzixxlbq.html

C#:   static void Main(string[] args)
来源：http://dali.kuanghao11.cn/Article/details/gt2dryffocn.html

[M08] 获取系统与运行时信息
来源：http://dali.gogol.net.cn/Article/details/gt2xpxprzek.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hywenlv.cn/Article/details/gt2rzcwneot.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ydzc1.top/Article/details/gt2rkyrihja.html

JS:   process.platform;  process.version
来源：http://dali.xziqi.cn/Article/details/gt2lzyefnri.html

TS:   process.platform;  process.version
来源：http://dali.yvedp.cn/Article/details/gt2dvydtiph.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.meibo888.top/Article/details/gt2kuocpqsp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.iojbl.cn/Article/details/gt2hwgwrsng.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinqigfzy.top/Article/details/gt2ugjusyhq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.nanxuanxn.top/Article/details/gt2ebubpbti.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2pxkadkjd.html

N. 数据结构与算法
来源：http://dali.ehwqpu.com/Article/details/gt2hembiauz.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2rhsqyffh.html

[N01] 二分查找（有序数组）
来源：http://dali.yonumen.top/Article/details/gt2oupxshpb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jpkwcfvq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.fengsongda.top/Article/details/gt2fstwkodo.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shangyingyoupin.top/Article/details/gt2rckzupnp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lhaiocnf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gt2pelkxbdm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gt2jigfmcsh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sxryk.cn/Article/details/gt2mgjywjbc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gt2fntvpaem.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sweek.top/Article/details/gt2vgmknpap.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gzhubu.top/Article/details/gt2vymkhtyw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gt2scoueqpi.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2iasqfbkx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2rjjncsrc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cucudq.cn/Article/details/gt2vybaosil.html

Go:   slices.Sort(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2tbzntvki.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbssfcu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hongshengwenyu.top/Article/details/gt2nxqusrjr.html

[N03] 快速排序（分治示例）
来源：http://dali.yanxiufei.cn/Article/details/gt2snpiitth.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.quarkkingdee.top/Article/details/gt2ioxppvwr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yonumen.top/Article/details/gt2fmcchprm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.c1oappe.top/Article/details/gt2qoymuoux.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gotoacloud.top/Article/details/gt2fnlfinvr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.meibo888.top/Article/details/gt2fqlqwrzz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yuxming.cn/Article/details/gt2cprodxzs.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.nwbrower.top/Article/details/gt2yixrfvcd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.smart0.xyz/Article/details/gt2gajtyzaw.html

[N04] 斐波那契数列
来源：http://dali.gogol.net.cn/Article/details/gt2nqevphns.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.dianchejie.cn/Article/details/gt2xjayduwp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.redwolf501.top/Article/details/gt2gyiooqmq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwcayec.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.316326.xyz/Article/details/gt2xakrvxnk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.daxiang520.top/Article/details/gt2exlrcfaf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shuidangran.top/Article/details/gt2ncbfkqyz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2qtcljgwu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jianghu66.top/Article/details/gt2dcltgkch.html

[N05] 最大公约数
来源：http://dali.smart0.xyz/Article/details/gt2fstxtqga.html

Py:   math.gcd(a, b)
来源：http://dali.yj20258.top/Article/details/gt2sxfnfzim.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cdnleiting.top/Article/details/gt2pxcgqzjr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rrcqqswi.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guowangkeji.top/Article/details/gt2bpmsijok.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jiagoushi.top/Article/details/gt2axtimrla.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jyoumei.cn/Article/details/gt2efqcdxph.html

Ruby: a.gcd(b)
来源：http://dali.yj20258888.top/Article/details/gt2qwvvjsiy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xuanzx.com/Article/details/gt2jbpjeans.html

[N06] 判断回文字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vetbxzzz.html

Py:   s == s[::-1]
来源：http://dali.sufxvd.cn/Article/details/gt2trfgmigw.html

PHP:  $s === strrev($s);
来源：http://dali.sxryk.cn/Article/details/gt2vtrufzcg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2wegzbpzr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gt2fhshrqut.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gzhubu.top/Article/details/gt2cbdnegde.html

Go:   // 双指针从两端比较
来源：http://dali.shuidangran.top/Article/details/gt2xijstvou.html

Ruby: s == s.reverse
来源：http://dali.tian-w.cn/Article/details/gt2luxctsib.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yanxiufei.cn/Article/details/gt2houkxded.html

[N07] 两数之和（返回下标）
来源：http://dali.tianlin.xyz/Article/details/gt2iqslsyyv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sweek.top/Article/details/gt2jxghiytz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.9152youxi.cn/Article/details/gt2qwoqkdur.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yuanzhike.top/Article/details/gt2mjhuubox.html

TS:   // 手写 Map<string, number>
来源：http://dali.birdmap.top/Article/details/gt2sgrattkx.html

Java: // 手写 HashMap
来源：http://dali.ppjwa.cn/Article/details/gt2ucuytynk.html

Go:   // 手写 map[int]int
来源：http://dali.hywenlv.cn/Article/details/gt2qcoubzyd.html

Ruby: // 手写 Hash
来源：http://dali.316326.xyz/Article/details/gt2vfzuchmf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hysaishi.cn/Article/details/gt2bvxqfpft.html

[N08] 生成全排列
来源：http://dali.gotoacloud.top/Article/details/gt2vdxqfstz.html

Py:   itertools.permutations(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2jlfmtjvn.html

PHP:  // 手写递归交换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pazivgkp.html

JS:   // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gt2lvwuoxyf.html

TS:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gt2lqsvnebv.html

Java: // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gt2cqmtomrh.html

Go:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gt2dnzkftzu.html

Ruby: arr.permutation.to_a
来源：http://dali.cheryme.top/Article/details/gt2bmnjltim.html

C#:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gt2hfiggpeq.html

[N09] 栈与队列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2itmckqqh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jianghu66.top/Article/details/gt2xywifusn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.quarkkingdee.top/Article/details/gt2ixjhgxkx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.9152youxi.cn/Article/details/gt2ifjccszy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xuanzx.com/Article/details/gt2zxevbcxb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sufxvd.cn/Article/details/gt2thxbheic.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.chenzaomai.com/Article/details/gt2roliuwub.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hnxiangtu.top/Article/details/gt2vynqxurr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.smart0.xyz/Article/details/gt2jyddaqdz.html

[N10] 链表节点定义
来源：http://dali.yonumen.top/Article/details/gt2crkpsftt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.chenlongwang.top/Article/details/gt2nqmpxlre.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yj20258888.top/Article/details/gt2izonettt.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.wangdashe.top/Article/details/gt2fyploitx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shuidangran.top/Article/details/gt2chnqspxf.html

Java: class Node { int v; Node next; }
来源：http://dali.yangfankeji.com/Article/details/gt2knbgszpv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sysykeji.top/Article/details/gt2ecempzwh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2prsaitdg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yanxiufei.cn/Article/details/gt2cemtyxht.html

[N11] 二叉树中序遍历
来源：http://dali.kuanghao11.cn/Article/details/gt2nvskbkmb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gaohongyu789.top/Article/details/gt2jpehndyn.html

PHP:  // 手写递归函数
来源：http://dali.tianlin.xyz/Article/details/gt2lncvequw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.andypj.xyz/Article/details/gt2tdbbjvon.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shangyingyoupin.top/Article/details/gt2ugrjrcap.html

Java: // 手写递归
来源：http://dali.0kj1m.cn/Article/details/gt2tfbdsdxa.html

Go:   // 手写递归
来源：http://dali.jqgfzy.top/Article/details/gt2awakaqtk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gzhubu.top/Article/details/gt2ijyygnqr.html

C#:   // 手写递归
来源：http://dali.yuanzhike.top/Article/details/gt2uavxmmkc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhixingplan.top/Article/details/gt2rlbuzqrj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shzxlz.cn/Article/details/gt2qggesrom.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gzhubu.top/Article/details/gt2dwifpyzi.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sweek.top/Article/details/gt2tmcgycqu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.316326.xyz/Article/details/gt2hiszgzmo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.mhx1999.top/Article/details/gt2zwoqaaeo.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.gotoacloud.top/Article/details/gt2cgyqavao.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhengqikj.top/Article/details/gt2lflwcwmp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hysaishi.cn/Article/details/gt2qjejtcai.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2quljlsip.html

O. 并发与异步
来源：http://dali.xylfe.cn/Article/details/gt2fonmwxkt.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2wiknbiwf.html

[O01] 启动一个线程
来源：http://dali.ybcxt.top/Article/details/gt2zaiwcezd.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cucudq.cn/Article/details/gt2niafrdwb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.redwolf501.top/Article/details/gt2mmhuuapf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.pengpengdd.cyou/Article/details/gt2qxyvdapa.html

TS:   // 同 JS
来源：http://dali.yj20258888.top/Article/details/gt2gqwckgcp.html

Java: new Thread(() -> f()).start()
来源：http://dali.yuanzhike.top/Article/details/gt2etpbaepr.html

Go:   go f()
来源：http://dali.316326.xyz/Article/details/gt2mmxwdecv.html

Ruby: Thread.new { f }
来源：http://dali.dashuyun.cn/Article/details/gt2dqxndrlg.html

C#:   Task.Run(() => F());
来源：http://dali.ybcxt.top/Article/details/gt2wgiqrefg.html

[O02] 使用线程池
来源：http://dali.guowangkeji.top/Article/details/gt2htxwpsyk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cucudq.cn/Article/details/gt2wtdzgfgl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jqgfzy.top/Article/details/gt2behqjtxn.html

JS:   // worker_threads 线程池
来源：http://dali.shuidangran.top/Article/details/gt2lkjsqvyy.html

TS:   // worker_threads 线程池
来源：http://dali.jiagoushi.top/Article/details/gt2mzolnkap.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.chenjidiqi.icu/Article/details/gt2gwzayqya.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gotoacloud.top/Article/details/gt2okxdjbjk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.bjfxy.top/Article/details/gt2uidicjwg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinqigfzy.top/Article/details/gt2rdydabzl.html

[O03] 加锁保护共享数据
来源：http://dali.xuetiantiany.cn/Article/details/gt2pnlwslnv.html

Py:   with lock: shared += 1
来源：http://dali.hnqzz.top/Article/details/gt2nvqlozqb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shangyingyoupin.top/Article/details/gt2dehdcjdx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cucudq.cn/Article/details/gt2ihiptbtv.html

TS:   // 同 JS
来源：http://dali.zhiwuduotai.top/Article/details/gt2qmvwkqvv.html

Java: synchronized (this) { shared++; }
来源：http://dali.hywenlv.cn/Article/details/gt2gzoyvpow.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhixingplan.top/Article/details/gt2nomdwsye.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zdqjudy.top/Article/details/gt2tnfyuibn.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hspvkroa.html

[O04] 定义异步函数并等待
来源：http://dali.yvedp.cn/Article/details/gt2xyyrkzhw.html

Py:   async def f():⏎    await g()
来源：http://dali.cashguo.top/Article/details/gt2dxjhvmtt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hongshengwenyu.top/Article/details/gt2buzbayxm.html

JS:   async function f() { await g(); }
来源：http://dali.zhixingplan.top/Article/details/gt2skjqrpne.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2cfvzrxss.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xuanzx.com/Article/details/gt2oshuvucu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.0kj1m.cn/Article/details/gt2thpkexaj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.c1oappe.top/Article/details/gt2sligbcxa.html

C#:   async Task F() { await G(); }
来源：http://dali.svipenyu.cn/Article/details/gt2obrtkzfs.html

[O05] 并发执行并等待全部完成
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qihbvact.html

Py:   asyncio.gather(*tasks)
来源：http://dali.kuanghao11.cn/Article/details/gt2aevnarfc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xylfe.cn/Article/details/gt2srhhjfmz.html

JS:   await Promise.all(tasks)
来源：http://dali.guannengcc.top/Article/details/gt2axajwmld.html

TS:   await Promise.all(tasks)
来源：http://dali.hysaishi.cn/Article/details/gt2fqvymhfz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shangyingyoupin.top/Article/details/gt2lxkvovoc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.daria6918.cn/Article/details/gt2lpzhurdi.html

Ruby: threads.map(&:join)
来源：http://dali.cashguo.top/Article/details/gt2gwqjvhnq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.quarkkingdee.top/Article/details/gt2exsdnhsf.html

[O06] 使用进程池
来源：http://dali.svipenyu.cn/Article/details/gt2ahfiubae.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2itgyteal.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yuxming.cn/Article/details/gt2spxpnefj.html

JS:   // child_process / cluster 模块
来源：http://dali.aibaodan.cn/Article/details/gt2gqnjdsvb.html

TS:   // child_process / cluster 模块
来源：http://dali.shangyingyoupin.top/Article/details/gt2qmkcynpg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yuxming.cn/Article/details/gt2geqcrkbo.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.svipenyu.cn/Article/details/gt2whtmctzv.html

Ruby: // fork 块
来源：http://dali.jqgfzy.top/Article/details/gt2uapaiazq.html

C#:   Parallel.For
来源：http://dali.andypj.xyz/Article/details/gt2sqtnmvjf.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2ykxdtagw.html

P. 常用工具函数
来源：http://dali.shuidangran.top/Article/details/gt2rwhlcyht.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2xdrnmlne.html

[P01] 生成 UUID
来源：http://dali.chenlongwang.top/Article/details/gt2laybrunr.html

Py:   str(uuid.uuid4())
来源：http://dali.kuanghao11.cn/Article/details/gt2tpzpmegs.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pfufmfmt.html

JS:   crypto.randomUUID()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dlhzghro.html

TS:   crypto.randomUUID()
来源：http://dali.sxryk.cn/Article/details/gt2pbvorlno.html

Java: UUID.randomUUID().toString()
来源：http://dali.yangfankeji.com/Article/details/gt2mrekktpn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shuidangran.top/Article/details/gt2xbbwldbx.html

Ruby: SecureRandom.uuid
来源：http://dali.hongshengwenyu.top/Article/details/gt2qpiflyan.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ivvv.top/Article/details/gt2ebhgwuji.html

[P02] MD5 / SHA256 摘要
来源：http://dali.aibaodan.cn/Article/details/gt2cvollqwc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.quarkkingdee.top/Article/details/gt2awcgqfnh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2feyvxqni.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhiwuduotai.top/Article/details/gt2urvlfgzp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yanxiufei.cn/Article/details/gt2celhtvjv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.wangshuangyany.cn/Article/details/gt2agrorufx.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yonumen.top/Article/details/gt2qqdfidqs.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jiagoushi.top/Article/details/gt2emqytigb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.tanke756.top/Article/details/gt2dmufegfw.html

[P03] 生成短随机字符串
来源：http://dali.chenlongwang.top/Article/details/gt2hhhowvyc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jlsjyb.cn/Article/details/gt2yjtgpzkc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shangyingyoupin.top/Article/details/gt2wrimtaaj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shzxlz.cn/Article/details/gt2icvwofju.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.fzhhl.top/Article/details/gt2ubjszgha.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yangfankeji.com/Article/details/gt2bopigayp.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.quarkkingdee.top/Article/details/gt2lgjlnfve.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jlsjyb.cn/Article/details/gt2syfzkhzx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yj20258888.top/Article/details/gt2nbfgthqg.html

[P04] 求长度
来源：http://dali.wangshuangyany.cn/Article/details/gt2piijxwju.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jqgufenzy.top/Article/details/gt2xonpycwq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fnnjqwrl.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgfzy.top/Article/details/gt2jwxaaxfv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shzxlz.cn/Article/details/gt2frjucobe.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhixingplan.top/Article/details/gt2qsjfpsyn.html

Go:   len(arr);  len(m)
来源：http://dali.xylfe.cn/Article/details/gt2ijhchaza.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2eflyevao.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.redwolf501.top/Article/details/gt2ohkromgy.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhengqikj.top/Article/details/gt2ogpozghm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shuidangran.top/Article/details/gt2dnshldjz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hnxiangtu.top/Article/details/gt2vobfuhlo.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.havefunace.top/Article/details/gt2etjmzxkx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.bjfxy.top/Article/details/gt2filoszzo.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ybcxt.top/Article/details/gt2crnxjnqu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.fzhhl.top/Article/details/gt2psurohbb.html

Ruby: a == b
来源：http://dali.xziqi.cn/Article/details/gt2rvyybpds.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.quarkkingdee.top/Article/details/gt2upmvgdfc.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gzhubu.top/Article/details/gt2calexclb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.wangshuangyany.cn/Article/details/gt2rvzuaxky.html

PHP:  if (empty($x)) {}
来源：http://dali.zhengqikj.top/Article/details/gt2kiqeqtfv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xuanzx.com/Article/details/gt2iathpbat.html

TS:   if (x == null) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2ntapsvhu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xylfe.cn/Article/details/gt2geffswtf.html

Go:   if x == nil {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rtthismj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jlsjyb.cn/Article/details/gt2zuxmzkxv.html

C#:   if (x is null) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2kmaomiwe.html

[P07] 防抖与节流
来源：http://dali.dashuyun.cn/Article/details/gt2dtoxlvcw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cheryme.top/Article/details/gt2oniwzuza.html

PHP:  // 手写时间戳比较
来源：http://dali.gaohongyu789.top/Article/details/gt2cjercnct.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sweek.top/Article/details/gt2kqyspomo.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.andypj.xyz/Article/details/gt2hqdvwgjw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lnnadwyp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jyoumei.cn/Article/details/gt2izrqisoe.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.tanke756.top/Article/details/gt2pwohkycl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ydzc1.top/Article/details/gt2qequhqkm.html

[P08] 处理浮点精度问题
来源：http://dali.jinqigfzy.top/Article/details/gt2tgaorijt.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shzxlz.cn/Article/details/gt2zlnyhbgz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hywenlv.cn/Article/details/gt2ywbejwlr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.havefunace.top/Article/details/gt2msmifknl.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.bjfxy.top/Article/details/gt2gkzsmwig.html


<!-- 参考信息 -->