代发 wailian999

JS:   process.argv.slice(2)
来源：http://dali.gzhubu.top/Article/details/gtdznfooxe.html

TS:   process.argv.slice(2)
来源：http://dali.cashguo.top/Article/details/gtqjwpejfa.html

Java: args 数组（main 方法参数）
来源：http://dali.hywenlv.cn/Article/details/gtivbomlvh.html

Go:   os.Args[1:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdkirfefl.html

Ruby: ARGV
来源：http://dali.fengsongda.top/Article/details/gtaydfgucg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.pycfn.com/Article/details/gtqcctwxvi.html

[M02] 读取环境变量
来源：http://dali.redwolf501.top/Article/details/gtcvpzbvxg.html

Py:   os.environ.get("HOME")
来源：http://dali.zdqjudy.top/Article/details/gthpwfusvn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sysykeji.top/Article/details/gtmwdbjtyi.html

JS:   process.env.HOME
来源：http://dali.quarkkingdee.top/Article/details/gtokvitqin.html

TS:   process.env.HOME
来源：http://dali.yongpay.top/Article/details/gtfhboqqel.html

Java: System.getenv("HOME")
来源：http://dali.9152youxi.cn/Article/details/gtjpinpzyf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gtcubboknr.html

Ruby: ENV["HOME"]
来源：http://dali.quarkkingdee.top/Article/details/gtyqvufrha.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqmjojfmw.html

[M03] 执行外部命令
来源：http://dali.dianchejie.cn/Article/details/gtnbtfmqyz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenjidiqi.icu/Article/details/gtayikfxvo.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nanxuanxn.top/Article/details/gtuavbjuyv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xziqi.cn/Article/details/gtgkraxqwr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zdqjudy.top/Article/details/gtgyoinukk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yonumen.top/Article/details/gtaelnncyv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinqigfzy.top/Article/details/gtneywosip.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.fengsongda.top/Article/details/gtaratwioa.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinqigufen.top/Article/details/gtaxmwvyag.html

[M04] 获取当前工作目录
来源：http://dali.sxryk.cn/Article/details/gtqinlpfnj.html

Py:   os.getcwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gtqbhlpsjh.html

PHP:  getcwd();
来源：http://dali.sxryk.cn/Article/details/gtqmrvtwrr.html

JS:   process.cwd()
来源：http://dali.chenzaomai.com/Article/details/gtfaqztgxg.html

TS:   process.cwd()
来源：http://dali.snrcjt.cn/Article/details/gtrjkyblqr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yvedp.cn/Article/details/gtskejnwxk.html

Go:   os.Getwd()
来源：http://dali.xuanzx.com/Article/details/gtjmyqzuff.html

Ruby: Dir.pwd
来源：http://dali.tian-w.cn/Article/details/gtupresqpt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.bjfxy.top/Article/details/gtrksaarvj.html

[M05] 设置退出码
来源：http://dali.kuanghao11.cn/Article/details/gtydwwwnno.html

Py:   sys.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtptwytown.html

PHP:  exit(1);
来源：http://dali.tianlin.xyz/Article/details/gtxsyktsgr.html

JS:   process.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gtwsavoqdb.html

TS:   process.exit(1)
来源：http://dali.meibo888.top/Article/details/gtbyokgsih.html

Java: System.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gthiujlfuz.html

Go:   os.Exit(1)
来源：http://dali.zhengqikj.top/Article/details/gtnmtrhtzs.html

Ruby: exit 1
来源：http://dali.yj202588.top/Article/details/gttjoonnei.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.svipenyu.cn/Article/details/gtjamnfwww.html

[M06] 向标准错误输出
来源：http://dali.zdqjudy.top/Article/details/gtgphafzdq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj202588.top/Article/details/gtziahaild.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cdnleiting.top/Article/details/gtmemganem.html

JS:   console.error("err")
来源：http://dali.ivvv.top/Article/details/gtmxwaflfb.html

TS:   console.error("err")
来源：http://dali.ydzc1.top/Article/details/gtdypfgefw.html

Java: System.err.println("err")
来源：http://dali.daria6918.cn/Article/details/gtceamzvjl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.svipenyu.cn/Article/details/gtmltzngjt.html

Ruby: warn "err"
来源：http://dali.guannengcc.top/Article/details/gtgvvlikbe.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hongshengwenyu.top/Article/details/gtkorzvzwu.html

[M07] 判断是否为主入口
来源：http://dali.nanxuanxn.top/Article/details/gtxrpaagaa.html

Py:   if __name__ == "__main__":
来源：http://dali.tianlin.xyz/Article/details/gtqxtoylka.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzwdplopd.html

JS:   require.main === module
来源：http://dali.cheryme.top/Article/details/gtvfslhbue.html

TS:   require.main === module
来源：http://dali.haohaochexian.top/Article/details/gtgkpvehim.html

Java: public static void main(String[] args)
来源：http://dali.vqdsnc.cn/Article/details/gtyndhumji.html

Go:   func main()
来源：http://dali.meibo888.top/Article/details/gtduuvwmin.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jqgufenzy.top/Article/details/gtgqjqizcm.html

C#:   static void Main(string[] args)
来源：http://dali.hnxiangtu.top/Article/details/gtjxsbvbtt.html

[M08] 获取系统与运行时信息
来源：http://dali.hysaishi.cn/Article/details/gtyqnrjelf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gtbxkoimgc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ehwqpu.com/Article/details/gtqswerneo.html

JS:   process.platform;  process.version
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgqhdwgcw.html

TS:   process.platform;  process.version
来源：http://dali.pycfn.com/Article/details/gthtdhjsqu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.redwolf501.top/Article/details/gtdatgoslb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hfpthk.cn/Article/details/gtdovchnis.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.wangdashe.top/Article/details/gtthvkfyad.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jlsjyb.cn/Article/details/gtymopmaql.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtdyqcnafc.html

N. 数据结构与算法
来源：http://dali.yuanzhike.top/Article/details/gtbclpqaya.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtupbkwsed.html

[N01] 二分查找（有序数组）
来源：http://dali.jianghu66.top/Article/details/gtbqfwffuy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtuyxlijrh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnbphtwuk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gtsxngsthx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gotoacloud.top/Article/details/gtvbzqusoo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtjezyrzdm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtmucvqyyy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.andypj.xyz/Article/details/gtixxtkmjk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ivvv.top/Article/details/gtdedugzuy.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cqqwz.cn/Article/details/gtpjigohcg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zycfv.cn/Article/details/gtyqmjtgff.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.chenzaomai.com/Article/details/gtoiqmhcsy.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cashguo.top/Article/details/gtstedvsqj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gaohongyu789.top/Article/details/gttwtqfkmk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yvedp.cn/Article/details/gtzabtjouc.html

Go:   slices.Sort(arr)
来源：http://dali.sxryk.cn/Article/details/gtkjrcndju.html

Ruby: arr.sort
来源：http://dali.jinqigfzy.top/Article/details/gtiayljyjv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.tian-w.cn/Article/details/gtzkalaurj.html

[N03] 快速排序（分治示例）
来源：http://dali.ybcxt.top/Article/details/gtrsvuopwk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhengqikj.top/Article/details/gtljkscbge.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yuanzhike.top/Article/details/gtylblzwaj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yvedp.cn/Article/details/gtzqclopri.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gzhubu.top/Article/details/gtseveqhlg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hywenlv.cn/Article/details/gtpzaaeipq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sxryk.cn/Article/details/gtmczfxtwc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yvedp.cn/Article/details/gtaswxctjl.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenlongwang.top/Article/details/gtqpquozps.html

[N04] 斐波那契数列
来源：http://dali.gotoacloud.top/Article/details/gtqbeijzht.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ehwqpu.com/Article/details/gtedidlacl.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hongshengwenyu.top/Article/details/gtyagdnhgb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cdnleiting.top/Article/details/gtfxfbuufe.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj20258.top/Article/details/gtbjouvrsl.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgktenaze.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.fengsongda.top/Article/details/gtfrqfzudc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.c1oappe.top/Article/details/gtsigwcipj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmhuxkefm.html

[N05] 最大公约数
来源：http://dali.hnxiangtu.top/Article/details/gtotwypvrj.html

Py:   math.gcd(a, b)
来源：http://dali.gogol.net.cn/Article/details/gthiqrdpcc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xziqi.cn/Article/details/gtsenxsgyu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cucudq.cn/Article/details/gtagfklfqw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnxiangtu.top/Article/details/gtswtwcsrc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.0kj1m.cn/Article/details/gtbcaaxswz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.nanxuanxn.top/Article/details/gtyfgzshmy.html

Ruby: a.gcd(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzvstwcux.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhiwuduotai.top/Article/details/gtlikeuasi.html

[N06] 判断回文字符串
来源：http://dali.birdmap.top/Article/details/gtsxlzpsjm.html

Py:   s == s[::-1]
来源：http://dali.hysaishi.cn/Article/details/gtzbhqxmeg.html

PHP:  $s === strrev($s);
来源：http://dali.aizwys.cn/Article/details/gtdgcggdsc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gtwhosmmnj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gtijwjlguf.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hysaishi.cn/Article/details/gtfijrrlse.html

Go:   // 双指针从两端比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsiyrseoo.html

Ruby: s == s.reverse
来源：http://dali.jlsjyb.cn/Article/details/gtwktaqfpo.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhixingplan.top/Article/details/gtwvqewirc.html

[N07] 两数之和（返回下标）
来源：http://dali.hysaishi.cn/Article/details/gthdgyfqwu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.haohaochexian.top/Article/details/gtmmueeqhy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.pengpengdd.cyou/Article/details/gtndfbpmng.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.nanxuanxn.top/Article/details/gtwczoajyo.html

TS:   // 手写 Map<string, number>
来源：http://dali.xylfe.cn/Article/details/gtzefiquyp.html

Java: // 手写 HashMap
来源：http://dali.yvedp.cn/Article/details/gtvtsjokuw.html

Go:   // 手写 map[int]int
来源：http://dali.tianlin.xyz/Article/details/gtsnhusdnm.html

Ruby: // 手写 Hash
来源：http://dali.shangyingyoupin.top/Article/details/gtuzvcdfep.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sysykeji.top/Article/details/gtxdyxmtwj.html

[N08] 生成全排列
来源：http://dali.tian-w.cn/Article/details/gtlcoepnvz.html

Py:   itertools.permutations(arr)
来源：http://dali.sysykeji.top/Article/details/gtddusdrqf.html

PHP:  // 手写递归交换
来源：http://dali.cucudq.cn/Article/details/gtmpabjpmo.html

JS:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gtvkuzqjpf.html

TS:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtmmcbhsde.html

Java: // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gtfcgrcmgc.html

Go:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gtmvzxsxws.html

Ruby: arr.permutation.to_a
来源：http://dali.vqdsnc.cn/Article/details/gtbrjgckxi.html

C#:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gtfmdhfuux.html

[N09] 栈与队列
来源：http://dali.hongshengwenyu.top/Article/details/gtbhddwzxb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.kuanghao11.cn/Article/details/gtyuhojbid.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hnqzz.top/Article/details/gtyocbquwv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hnqzz.top/Article/details/gtekklrymt.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gotoacloud.top/Article/details/gttecbmdsj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhongyouzk.top/Article/details/gtlkmjbmdq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.dianchejie.cn/Article/details/gtgjdzqmmn.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yuanzhike.top/Article/details/gtgtpizilf.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj202588.top/Article/details/gtdukskwoz.html

[N10] 链表节点定义
来源：http://dali.yj202588.top/Article/details/gtwqwhkhna.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jiagoushi.top/Article/details/gtmfdroojc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.feifeiyinyue.top/Article/details/gtehfiobgw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.wangshuangyany.cn/Article/details/gtippizove.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhoulong.xyz/Article/details/gtmxtlhwtb.html

Java: class Node { int v; Node next; }
来源：http://dali.shangyingyoupin.top/Article/details/gthcbgmrzy.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ehwqpu.com/Article/details/gtpfvqyzqx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.meibo888.top/Article/details/gtokmaitvv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinqigfzy.top/Article/details/gtlvtxwpyi.html

[N11] 二叉树中序遍历
来源：http://dali.xuanzx.com/Article/details/gtwvozmdcc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yangfankeji.com/Article/details/gtbxqcwxkt.html

PHP:  // 手写递归函数
来源：http://dali.mhx1999.top/Article/details/gtufqnqoxm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jiagoushi.top/Article/details/gtqxjzrddz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.iojbl.cn/Article/details/gtpaltuucl.html

Java: // 手写递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyfflqzcs.html

Go:   // 手写递归
来源：http://dali.wangshuangyany.cn/Article/details/gtxkakprvy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhengqikj.top/Article/details/gtcnorhpeg.html

C#:   // 手写递归
来源：http://dali.tanke756.top/Article/details/gtceprvnfj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sweek.top/Article/details/gtfswrtlan.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.chenjidiqi.icu/Article/details/gtjenlnjsb.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.fengsongda.top/Article/details/gtzpxucake.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dianchejie.cn/Article/details/gtwzytgmxq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ydzc1.top/Article/details/gtpggqiqsj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.wangshuangyany.cn/Article/details/gtcqjzdggh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cdnleiting.top/Article/details/gttepiksds.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.chenzaomai.com/Article/details/gtrrqyvgut.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ivvv.top/Article/details/gtufcggysh.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtgidyblxq.html

O. 并发与异步
来源：http://dali.pycfn.com/Article/details/gtcbgchboe.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtnvddjgyy.html

[O01] 启动一个线程
来源：http://dali.cucudq.cn/Article/details/gttcbwdjem.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.wangshuangyany.cn/Article/details/gtubqvixrk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ppjwa.cn/Article/details/gtftvpfqyp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cdnleiting.top/Article/details/gtzapkkwrb.html

TS:   // 同 JS
来源：http://dali.smart0.xyz/Article/details/gtzlxwsegf.html

Java: new Thread(() -> f()).start()
来源：http://dali.sysykeji.top/Article/details/gtvdwahcuy.html

Go:   go f()
来源：http://dali.svipenyu.cn/Article/details/gtfjmpvqvr.html

Ruby: Thread.new { f }
来源：http://dali.jqgufenzy.top/Article/details/gtnhisyudr.html

C#:   Task.Run(() => F());
来源：http://dali.yuxming.cn/Article/details/gtaovhlrjn.html

[O02] 使用线程池
来源：http://dali.zhengqikj.top/Article/details/gtwewkycuz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.havefunace.top/Article/details/gtddtfgeqi.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shangyingyoupin.top/Article/details/gtutusbmth.html

JS:   // worker_threads 线程池
来源：http://dali.cdnleiting.top/Article/details/gtqoaovysd.html

TS:   // worker_threads 线程池
来源：http://dali.jlsjyb.cn/Article/details/gtgcyjwvpu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hammf.cn/Article/details/gtlvddjxan.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yanxiufei.cn/Article/details/gtykyaxyoj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hnxiangtu.top/Article/details/gtdjvzymvt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ehwqpu.com/Article/details/gtmahqjeyi.html

[O03] 加锁保护共享数据
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbqjjxila.html

Py:   with lock: shared += 1
来源：http://dali.svipenyu.cn/Article/details/gtjkhrojve.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.bjfxy.top/Article/details/gtqupvuagy.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.kuanghao11.cn/Article/details/gtommrsjeo.html

TS:   // 同 JS
来源：http://dali.jinqigfzy.top/Article/details/gtjdzevvhb.html

Java: synchronized (this) { shared++; }
来源：http://dali.hysaishi.cn/Article/details/gtqemwvozu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.aizwys.cn/Article/details/gtelngjldm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gaohongyu789.top/Article/details/gtzzscnirg.html

C#:   lock (gate) { shared++; }
来源：http://dali.chenjidiqi.icu/Article/details/gtzrjbnyza.html

[O04] 定义异步函数并等待
来源：http://dali.xuanzx.com/Article/details/gtequcyiqu.html

Py:   async def f():⏎    await g()
来源：http://dali.cucudq.cn/Article/details/gtminrsfjz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hfpthk.cn/Article/details/gtwxtbeerk.html

JS:   async function f() { await g(); }
来源：http://dali.yanxiufei.cn/Article/details/gtxbjaxdkn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.fzhhl.top/Article/details/gtausevojd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.chenjidiqi.icu/Article/details/gtlrballvs.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzvttajeu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.haohaochexian.top/Article/details/gtfaluoxmg.html

C#:   async Task F() { await G(); }
来源：http://dali.yj20258888.top/Article/details/gtoatswoag.html

[O05] 并发执行并等待全部完成
来源：http://dali.pycfn.com/Article/details/gtxedxhvps.html

Py:   asyncio.gather(*tasks)
来源：http://dali.daria6918.cn/Article/details/gtiporghfr.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.fengsongda.top/Article/details/gtygzddqun.html

JS:   await Promise.all(tasks)
来源：http://dali.shzxlz.cn/Article/details/gtmcsxmujw.html

TS:   await Promise.all(tasks)
来源：http://dali.meibo888.top/Article/details/gtzmajqlty.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jlsjyb.cn/Article/details/gtsedqswrd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gaohongyu789.top/Article/details/gttnexdklq.html

Ruby: threads.map(&:join)
来源：http://dali.jiagoushi.top/Article/details/gtdamfrdom.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hammf.cn/Article/details/gtmiuloaey.html

[O06] 使用进程池
来源：http://dali.yuanzhike.top/Article/details/gtvqssqibm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yueranfly.top/Article/details/gtvthatlaq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hammf.cn/Article/details/gtpakdedrc.html

JS:   // child_process / cluster 模块
来源：http://dali.zhengqikj.top/Article/details/gtckyurfqj.html

TS:   // child_process / cluster 模块
来源：http://dali.shangyingyoupin.top/Article/details/gtjroruyfi.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shanyushiyangtech.top/Article/details/gtwubayohh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhengqikj.top/Article/details/gtqjornruo.html

Ruby: // fork 块
来源：http://dali.pengpengdd.cyou/Article/details/gtuhbhmomc.html

C#:   Parallel.For
来源：http://dali.hammf.cn/Article/details/gtqiutsqmc.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtagrtoxcw.html

P. 常用工具函数
来源：http://dali.aibaodan.cn/Article/details/gtgcvviagm.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtejwefnzn.html

[P01] 生成 UUID
来源：http://dali.aibaodan.cn/Article/details/gtkvxuygks.html

Py:   str(uuid.uuid4())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdwvifdrj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ehwqpu.com/Article/details/gtsbyaxtuc.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gtnkwrekai.html

TS:   crypto.randomUUID()
来源：http://dali.xylfe.cn/Article/details/gtbrptzatf.html

Java: UUID.randomUUID().toString()
来源：http://dali.shzxlz.cn/Article/details/gtjmroqlax.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hywenlv.cn/Article/details/gtctewasgf.html

Ruby: SecureRandom.uuid
来源：http://dali.hfpthk.cn/Article/details/gtozsrhgxe.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yj20258888.top/Article/details/gtjyjpinaq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.wangdashe.top/Article/details/gtaenxiswt.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.nwbrower.top/Article/details/gtvbxjjbeh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ydzc1.top/Article/details/gtwabgsxim.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.chenjidiqi.icu/Article/details/gtbgdhebdk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yj20258.top/Article/details/gtjzphdntx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sufxvd.cn/Article/details/gtambppgtg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cheryme.top/Article/details/gthixwsuee.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtysniqrpm.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.tanke756.top/Article/details/gtefpxgutr.html

[P03] 生成短随机字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtitiftdpu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.tanke756.top/Article/details/gttuhlguzf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jlsjyb.cn/Article/details/gtyelntsao.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ybcxt.top/Article/details/gtlrggdlzv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ivvv.top/Article/details/gtraesfcwh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinqigufen.top/Article/details/gtfkdvqosz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.dashuyun.cn/Article/details/gtxnuwiejs.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.tian-w.cn/Article/details/gtmtqdorxp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jqgufenzy.top/Article/details/gttbvoibpc.html

[P04] 求长度
来源：http://dali.fengsongda.top/Article/details/gtwtwxurvj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ivvv.top/Article/details/gtqzfbabzu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhoulong.xyz/Article/details/gtglsjbpjp.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jyoumei.cn/Article/details/gtusemgwqj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yonumen.top/Article/details/gtqqmwqnib.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhengqikj.top/Article/details/gtdalolwsq.html

Go:   len(arr);  len(m)
来源：http://dali.tanke756.top/Article/details/gtwirvtjwg.html

Ruby: x.length;  x.size
来源：http://dali.cashguo.top/Article/details/gtsqhtvomm.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.316326.xyz/Article/details/gtneaklbew.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shanyushiyangtech.top/Article/details/gtqchivqrz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.smart0.xyz/Article/details/gtawgzmran.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xuanzx.com/Article/details/gtjpttpagv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.redwolf501.top/Article/details/gtqvcklqqu.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhengqikj.top/Article/details/gtwagytsua.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.andypj.xyz/Article/details/gtjdmerezh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jlsjyb.cn/Article/details/gtsiiiuevk.html

Ruby: a == b
来源：http://dali.zhiwuduotai.top/Article/details/gtibxlujwk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.wangshuangyany.cn/Article/details/gthwglewmv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.kuanghao11.cn/Article/details/gtqrvdjcvp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.fengsongda.top/Article/details/gtmutexlbi.html

PHP:  if (empty($x)) {}
来源：http://dali.cashguo.top/Article/details/gtgoenvreo.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cheryme.top/Article/details/gtbwfryfnq.html

TS:   if (x == null) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtglqoidce.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.9152youxi.cn/Article/details/gtckgwbrag.html

Go:   if x == nil {}
来源：http://dali.sxryk.cn/Article/details/gtbkrgvlhy.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.aizwys.cn/Article/details/gtwpeksuqw.html

C#:   if (x is null) {}
来源：http://dali.yonumen.top/Article/details/gtjgawezcc.html

[P07] 防抖与节流
来源：http://dali.xinyue.icu/Article/details/gthkscncpk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.c1oappe.top/Article/details/gtvcnhwwiz.html

PHP:  // 手写时间戳比较
来源：http://dali.9152youxi.cn/Article/details/gtegxxhkxz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nwbrower.top/Article/details/gtvscaveeu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jyoumei.cn/Article/details/gtgyalzkrl.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jlsjyb.cn/Article/details/gteoebmvrw.html


<!-- 参考信息 -->