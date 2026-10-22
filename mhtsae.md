代发 wailian999

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.svipenyu.cn/Article/details/gt2agdhpneu.html

JS:   process.env.HOME
来源：http://dali.daria6918.cn/Article/details/gt2woworlki.html

TS:   process.env.HOME
来源：http://dali.zhoulong.xyz/Article/details/gt2jcgntimj.html

Java: System.getenv("HOME")
来源：http://dali.shzxlz.cn/Article/details/gt2obvodcgz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.redwolf501.top/Article/details/gt2wrmphfik.html

Ruby: ENV["HOME"]
来源：http://dali.mhx1999.top/Article/details/gt2dvgrgkkl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wmnytfqf.html

[M03] 执行外部命令
来源：http://dali.chenjidiqi.icu/Article/details/gt2xlsdhrfd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.svipenyu.cn/Article/details/gt2omqvpupt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cheryme.top/Article/details/gt2qwurhfmo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cucudq.cn/Article/details/gt2olcapfkz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yangfankeji.com/Article/details/gt2phqtekbg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.nwbrower.top/Article/details/gt2lklbmesu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gzhubu.top/Article/details/gt2pspkteqf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shuidangran.top/Article/details/gt2xneczxfm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yuanzhike.top/Article/details/gt2mvtgqgzf.html

[M04] 获取当前工作目录
来源：http://dali.daxiang520.top/Article/details/gt2dhuvctyl.html

Py:   os.getcwd()
来源：http://dali.jianghu66.top/Article/details/gt2pwmdigaf.html

PHP:  getcwd();
来源：http://dali.vqdsnc.cn/Article/details/gt2iekyvhyn.html

JS:   process.cwd()
来源：http://dali.hnqzz.top/Article/details/gt2xoebrrhu.html

TS:   process.cwd()
来源：http://dali.jianghu66.top/Article/details/gt2odbehavo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2blzuszmm.html

Go:   os.Getwd()
来源：http://dali.zhengqikj.top/Article/details/gt2fygfnods.html

Ruby: Dir.pwd
来源：http://dali.ppjwa.cn/Article/details/gt2mdwzarlz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xylfe.cn/Article/details/gt2gpsxqtho.html

[M05] 设置退出码
来源：http://dali.jqgfzy.top/Article/details/gt2ntnbysbq.html

Py:   sys.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ovkldzbt.html

PHP:  exit(1);
来源：http://dali.sufxvd.cn/Article/details/gt2gfohfpxh.html

JS:   process.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gt2tvbnbsff.html

TS:   process.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2vifjdsxr.html

Java: System.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rdgipjrz.html

Go:   os.Exit(1)
来源：http://dali.jinqigufen.top/Article/details/gt2zklwiyqx.html

Ruby: exit 1
来源：http://dali.sxryk.cn/Article/details/gt2azekrpfa.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nanxuanxn.top/Article/details/gt2vltttmrc.html

[M06] 向标准错误输出
来源：http://dali.zdqjudy.top/Article/details/gt2reruqnce.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fiorlcpe.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jyoumei.cn/Article/details/gt2fmekbtgo.html

JS:   console.error("err")
来源：http://dali.shangyingyoupin.top/Article/details/gt2mupawkru.html

TS:   console.error("err")
来源：http://dali.yuanzhike.top/Article/details/gt2hhrywisv.html

Java: System.err.println("err")
来源：http://dali.zhiwuduotai.top/Article/details/gt2gsbccmmm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinqigufen.top/Article/details/gt2hruvjfmf.html

Ruby: warn "err"
来源：http://dali.yuxming.cn/Article/details/gt2jqfrvslw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yj20258888.top/Article/details/gt2vkrlszle.html

[M07] 判断是否为主入口
来源：http://dali.hysaishi.cn/Article/details/gt2vumjckqp.html

Py:   if __name__ == "__main__":
来源：http://dali.zhongyouzk.top/Article/details/gt2muftycvh.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sweek.top/Article/details/gt2shzwsauf.html

JS:   require.main === module
来源：http://dali.zhengqikj.top/Article/details/gt2eszvcrtu.html

TS:   require.main === module
来源：http://dali.aizwys.cn/Article/details/gt2whydgzfr.html

Java: public static void main(String[] args)
来源：http://dali.pycfn.com/Article/details/gt2cgbtspqq.html

Go:   func main()
来源：http://dali.guowangkeji.top/Article/details/gt2tajaffxm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zsymskar.html

C#:   static void Main(string[] args)
来源：http://dali.ybcxt.top/Article/details/gt2vrejrwos.html

[M08] 获取系统与运行时信息
来源：http://dali.sweek.top/Article/details/gt2lvtmuntv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj20258888.top/Article/details/gt2hxpfwdfu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xuetiantiany.cn/Article/details/gt2vivaejlg.html

JS:   process.platform;  process.version
来源：http://dali.dianchejie.cn/Article/details/gt2hqfmlqnk.html

TS:   process.platform;  process.version
来源：http://dali.hongshengwenyu.top/Article/details/gt2ssngyave.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinqigufen.top/Article/details/gt2szdrxnne.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yongpay.top/Article/details/gt2aldjotbi.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zdqjudy.top/Article/details/gt2uwzeinxo.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.guowangkeji.top/Article/details/gt2ztdcgdry.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2urzotnpb.html

N. 数据结构与算法
来源：http://dali.tanke756.top/Article/details/gt2yyeflevh.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2ewvaoewe.html

[N01] 二分查找（有序数组）
来源：http://dali.guowangkeji.top/Article/details/gt2qalcvxcv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.fengsongda.top/Article/details/gt2ebqwahlh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2luctlyef.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tian-w.cn/Article/details/gt2tlvtfxmp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jianghu66.top/Article/details/gt2qpoqycru.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xylfe.cn/Article/details/gt2hhsshguz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zycfv.cn/Article/details/gt2xecnfkuc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.fzhhl.top/Article/details/gt2khprotks.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxfesgwj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sufxvd.cn/Article/details/gt2marfyqin.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dashuyun.cn/Article/details/gt2ggkihsur.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yueranfly.top/Article/details/gt2vvojdyfk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dmecsfbp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gotoacloud.top/Article/details/gt2pfwfmqvc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hnqzz.top/Article/details/gt2nbnuexex.html

Go:   slices.Sort(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2gaffuqan.html

Ruby: arr.sort
来源：http://dali.xinyue.icu/Article/details/gt2dqwfqvaw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.aizwys.cn/Article/details/gt2lwjhqhpt.html

[N03] 快速排序（分治示例）
来源：http://dali.cheryme.top/Article/details/gt2btxnmsyg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sxryk.cn/Article/details/gt2wuidlhsa.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zsgthanp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.kuanghao11.cn/Article/details/gt2cvdnezrv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jlsjyb.cn/Article/details/gt2oxvlpodg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.haohaochexian.top/Article/details/gt2hjltpffr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.birdmap.top/Article/details/gt2jlxemmhd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jyoumei.cn/Article/details/gt2gphiohbk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.guowangkeji.top/Article/details/gt2oqhatsgk.html

[N04] 斐波那契数列
来源：http://dali.gotoacloud.top/Article/details/gt2lxnpvnps.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xuanzx.com/Article/details/gt2ctvskety.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sysykeji.top/Article/details/gt2xooztonz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gt2yscnzjyo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.haohaochexian.top/Article/details/gt2wglerqcu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ehwqpu.com/Article/details/gt2trngyitp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.fengsongda.top/Article/details/gt2tshuyhsa.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2faepvzeu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj20258888.top/Article/details/gt2vockcuaz.html

[N05] 最大公约数
来源：http://dali.jqgufenzy.top/Article/details/gt2izyacwph.html

Py:   math.gcd(a, b)
来源：http://dali.hnxiangtu.top/Article/details/gt2isrowjpm.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhixingplan.top/Article/details/gt2byxxpcyl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuanzhike.top/Article/details/gt2motynjkx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yueranfly.top/Article/details/gt2zzaxynih.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hammf.cn/Article/details/gt2sykwqkkr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.wangshuangyany.cn/Article/details/gt2nhcowznp.html

Ruby: a.gcd(b)
来源：http://dali.316326.xyz/Article/details/gt2yppduafd.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2hbxfepgg.html

[N06] 判断回文字符串
来源：http://dali.cashguo.top/Article/details/gt2aitbrznm.html

Py:   s == s[::-1]
来源：http://dali.cashguo.top/Article/details/gt2ddsefenw.html

PHP:  $s === strrev($s);
来源：http://dali.jyoumei.cn/Article/details/gt2slcgpkqq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gt2pzzetcbm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gt2xojyhxwt.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ybcxt.top/Article/details/gt2rtoexatl.html

Go:   // 双指针从两端比较
来源：http://dali.daria6918.cn/Article/details/gt2qvsuxfbs.html

Ruby: s == s.reverse
来源：http://dali.daria6918.cn/Article/details/gt2volwinbs.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xinyue.icu/Article/details/gt2bfxcoyyt.html

[N07] 两数之和（返回下标）
来源：http://dali.chenlongwang.top/Article/details/gt2vajzielc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.guowangkeji.top/Article/details/gt2wembzwdq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vpcwbpie.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.redwolf501.top/Article/details/gt2dceegpgl.html

TS:   // 手写 Map<string, number>
来源：http://dali.fzhhl.top/Article/details/gt2mlymojhz.html

Java: // 手写 HashMap
来源：http://dali.0kj1m.cn/Article/details/gt2lphrcrgd.html

Go:   // 手写 map[int]int
来源：http://dali.bjfxy.top/Article/details/gt2lzcvcslb.html

Ruby: // 手写 Hash
来源：http://dali.guowangkeji.top/Article/details/gt2dzycexlz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gaohongyu789.top/Article/details/gt2wqjrelvg.html

[N08] 生成全排列
来源：http://dali.fengsongda.top/Article/details/gt2xskrogqa.html

Py:   itertools.permutations(arr)
来源：http://dali.hammf.cn/Article/details/gt2cnyoatbk.html

PHP:  // 手写递归交换
来源：http://dali.xinyue.icu/Article/details/gt2fcrkubqz.html

JS:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gt2tmadwlww.html

TS:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gt2vrduhosx.html

Java: // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gt2eiwkrauz.html

Go:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gt2ylnbvqxa.html

Ruby: arr.permutation.to_a
来源：http://dali.hywenlv.cn/Article/details/gt2fipgminh.html

C#:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gt2byamsbcj.html

[N09] 栈与队列
来源：http://dali.zdqjudy.top/Article/details/gt2iwwltlke.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.dashuyun.cn/Article/details/gt2jbjmajtu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.andypj.xyz/Article/details/gt2zoyqlvfe.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.guannengcc.top/Article/details/gt2mxljcjjg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tpnesukr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.haohaochexian.top/Article/details/gt2hqiljvow.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sweek.top/Article/details/gt2qtircwco.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yangfankeji.com/Article/details/gt2epqtsmfv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sysykeji.top/Article/details/gt2rwhvomfz.html

[N10] 链表节点定义
来源：http://dali.andypj.xyz/Article/details/gt2yqsaabfn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cucudq.cn/Article/details/gt2zgjyhtlv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cheryme.top/Article/details/gt2xidcvqyq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhongyouzk.top/Article/details/gt2oaamiiqn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhoulong.xyz/Article/details/gt2buudvrbg.html

Java: class Node { int v; Node next; }
来源：http://dali.zhixingplan.top/Article/details/gt2qtmnuhls.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ivvv.top/Article/details/gt2qwgfrmaj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jiagoushi.top/Article/details/gt2iwkdmlnm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.birdmap.top/Article/details/gt2ikwibndx.html

[N11] 二叉树中序遍历
来源：http://dali.9152youxi.cn/Article/details/gt2xuqaokps.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.daxiang520.top/Article/details/gt2ymgynkgo.html

PHP:  // 手写递归函数
来源：http://dali.jinqigufen.top/Article/details/gt2migaswtu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.andypj.xyz/Article/details/gt2qnjjbhcc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gotoacloud.top/Article/details/gt2jmeugenr.html

Java: // 手写递归
来源：http://dali.hnqzz.top/Article/details/gt2vrrdwlad.html

Go:   // 手写递归
来源：http://dali.nanxuanxn.top/Article/details/gt2lxdamofs.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.fzhhl.top/Article/details/gt2zoxluljr.html

C#:   // 手写递归
来源：http://dali.xuanzx.com/Article/details/gt2sydpffat.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ivvv.top/Article/details/gt2fogqixaf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cqqwz.cn/Article/details/gt2lpoxxjoy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shzxlz.cn/Article/details/gt2mzmrejke.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jlsjyb.cn/Article/details/gt2wvyugxex.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zycfv.cn/Article/details/gt2tajipjql.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2inmyfjaz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yueranfly.top/Article/details/gt2mjmykpru.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.dianchejie.cn/Article/details/gt2kfibdrem.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aizwys.cn/Article/details/gt2emqhfreu.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2tkzgvfai.html

O. 并发与异步
来源：http://dali.jqgfzy.top/Article/details/gt2srtodlcf.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2jluvoxoy.html

[O01] 启动一个线程
来源：http://dali.jiagoushi.top/Article/details/gt2hsprnvfv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jianghu66.top/Article/details/gt2ocukqqrn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinqigufen.top/Article/details/gt2gmqgbcgx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.iojbl.cn/Article/details/gt2kookghcr.html

TS:   // 同 JS
来源：http://dali.havefunace.top/Article/details/gt2lxerbsst.html

Java: new Thread(() -> f()).start()
来源：http://dali.yanxiufei.cn/Article/details/gt2xdfuiisv.html

Go:   go f()
来源：http://dali.ivvv.top/Article/details/gt2qhlyrzrc.html

Ruby: Thread.new { f }
来源：http://dali.havefunace.top/Article/details/gt2cwiflmmz.html

C#:   Task.Run(() => F());
来源：http://dali.wangdashe.top/Article/details/gt2oqwcqthi.html

[O02] 使用线程池
来源：http://dali.vqdsnc.cn/Article/details/gt2bjvnjrqw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zdqjudy.top/Article/details/gt2aiqkpdjw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.c1oappe.top/Article/details/gt2lrhoejyr.html

JS:   // worker_threads 线程池
来源：http://dali.guannengcc.top/Article/details/gt2ztqhhhyw.html

TS:   // worker_threads 线程池
来源：http://dali.316326.xyz/Article/details/gt2xchbdnzq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.wangdashe.top/Article/details/gt2gnvejxyd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hnxiangtu.top/Article/details/gt2drfbpomf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ijoruuav.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.iojbl.cn/Article/details/gt2fuucizsp.html

[O03] 加锁保护共享数据
来源：http://dali.yuxming.cn/Article/details/gt2dywbxnoy.html

Py:   with lock: shared += 1
来源：http://dali.c1oappe.top/Article/details/gt2uaxvicmh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.aibaodan.cn/Article/details/gt2vbhiklac.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hnqzz.top/Article/details/gt2shjkdves.html

TS:   // 同 JS
来源：http://dali.shzxlz.cn/Article/details/gt2hmdmcjgp.html

Java: synchronized (this) { shared++; }
来源：http://dali.redwolf501.top/Article/details/gt2vpljxyiu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cheryme.top/Article/details/gt2xjefjywo.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shzxlz.cn/Article/details/gt2qpwefwjj.html

C#:   lock (gate) { shared++; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2gpsegehb.html

[O04] 定义异步函数并等待
来源：http://dali.cqqwz.cn/Article/details/gt2kvdiiuzr.html

Py:   async def f():⏎    await g()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qffhwffp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.chenzaomai.com/Article/details/gt2lafkgkaz.html

JS:   async function f() { await g(); }
来源：http://dali.fengsongda.top/Article/details/gt2tessdbrl.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2ydgpdapz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.316326.xyz/Article/details/gt2oprixmsb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.quarkkingdee.top/Article/details/gt2osxppdqy.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.sufxvd.cn/Article/details/gt2qxekuasy.html

C#:   async Task F() { await G(); }
来源：http://dali.redwolf501.top/Article/details/gt2uinlgrmm.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhongyouzk.top/Article/details/gt2aovshgbx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.birdmap.top/Article/details/gt2najrzxfz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yonumen.top/Article/details/gt2xkydbbgq.html

JS:   await Promise.all(tasks)
来源：http://dali.bjfxy.top/Article/details/gt2dioswhtv.html

TS:   await Promise.all(tasks)
来源：http://dali.shangyingyoupin.top/Article/details/gt2kzsliqqk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.havefunace.top/Article/details/gt2oywautbc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.snrcjt.cn/Article/details/gt2onglqjvt.html

Ruby: threads.map(&:join)
来源：http://dali.chenzaomai.com/Article/details/gt2dakqbxsq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hysaishi.cn/Article/details/gt2omjlgjjx.html

[O06] 使用进程池
来源：http://dali.chenjidiqi.icu/Article/details/gt2nhlgyqgs.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.guowangkeji.top/Article/details/gt2fygjkiip.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xinyue.icu/Article/details/gt2olyvrgbd.html

JS:   // child_process / cluster 模块
来源：http://dali.kuanghao11.cn/Article/details/gt2ghudrjdg.html

TS:   // child_process / cluster 模块
来源：http://dali.jinqigfzy.top/Article/details/gt2abnsqeof.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xziqi.cn/Article/details/gt2wdhvvybl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2izfryfrl.html

Ruby: // fork 块
来源：http://dali.jlsjyb.cn/Article/details/gt2pkjrwcoa.html

C#:   Parallel.For
来源：http://dali.tanke756.top/Article/details/gt2fyyxobbl.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2zgsvoocu.html

P. 常用工具函数
来源：http://dali.yangfankeji.com/Article/details/gt2krsxfyqp.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2ftffiics.html

[P01] 生成 UUID
来源：http://dali.kuanghao11.cn/Article/details/gt2xlorekwh.html

Py:   str(uuid.uuid4())
来源：http://dali.ivvv.top/Article/details/gt2rdhsoxhx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.havefunace.top/Article/details/gt2cprrowwp.html

JS:   crypto.randomUUID()
来源：http://dali.yanxiufei.cn/Article/details/gt2jdyhncca.html

TS:   crypto.randomUUID()
来源：http://dali.jlsjyb.cn/Article/details/gt2uxbtiybz.html

Java: UUID.randomUUID().toString()
来源：http://dali.tian-w.cn/Article/details/gt2lwuhubsq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yj20258888.top/Article/details/gt2bsbgvquv.html

Ruby: SecureRandom.uuid
来源：http://dali.jlsjyb.cn/Article/details/gt2pkbhpplg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.chenlongwang.top/Article/details/gt2bkeeqozg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.c1oappe.top/Article/details/gt2ucceuvqi.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ybcxt.top/Article/details/gt2kdwjwcfl.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jlsjyb.cn/Article/details/gt2ppmohawd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.wangdashe.top/Article/details/gt2gykdmrhi.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.smart0.xyz/Article/details/gt2oqiirmgn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jpjlrhve.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.svipenyu.cn/Article/details/gt2nnacihew.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhixingplan.top/Article/details/gt2nxmsmqsj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.aizwys.cn/Article/details/gt2kwguspez.html

[P03] 生成短随机字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lmmojfdk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.meibo888.top/Article/details/gt2entkuzom.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sysykeji.top/Article/details/gt2ndwisglc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sysykeji.top/Article/details/gt2miluechg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pengpengdd.cyou/Article/details/gt2pzbwpuvv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jayfasjb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.chenjidiqi.icu/Article/details/gt2exgqmigx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ocibjuwu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.gogol.net.cn/Article/details/gt2ldacryjn.html

[P04] 求长度
来源：http://dali.xuetiantiany.cn/Article/details/gt2jksuidxm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.wangdashe.top/Article/details/gt2eixxkqai.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gt2egpnliun.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dlstffuf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guowangkeji.top/Article/details/gt2qponllqk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhongyouzk.top/Article/details/gt2zpxodqne.html

Go:   len(arr);  len(m)
来源：http://dali.sxryk.cn/Article/details/gt2wqaxdkgd.html

Ruby: x.length;  x.size
来源：http://dali.hongshengwenyu.top/Article/details/gt2rihoycpk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hywenlv.cn/Article/details/gt2omvpjnbk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.chenlongwang.top/Article/details/gt2wqqdpmjv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ppjwa.cn/Article/details/gt2isxccrhb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gzhubu.top/Article/details/gt2lqqcazpd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.guannengcc.top/Article/details/gt2rmhhvxwi.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ehwqpu.com/Article/details/gt2vnkczjok.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.redwolf501.top/Article/details/gt2jwkqbehi.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xziqi.cn/Article/details/gt2ladxwqha.html

Ruby: a == b
来源：http://dali.yanxiufei.cn/Article/details/gt2gwgmdipv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sweek.top/Article/details/gt2udaaurbd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.daxiang520.top/Article/details/gt2srcgrtcf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hysaishi.cn/Article/details/gt2omtbaipr.html

PHP:  if (empty($x)) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ahlaudjk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.vqdsnc.cn/Article/details/gt2jzmmmxbx.html

TS:   if (x == null) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2honqqqgb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tkkrprzp.html

Go:   if x == nil {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wvtoulqn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ppjwa.cn/Article/details/gt2juatvgfr.html

C#:   if (x is null) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2jetelepg.html

[P07] 防抖与节流
来源：http://dali.zhiwuduotai.top/Article/details/gt2qubsrprc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.tian-w.cn/Article/details/gt2qekxvdco.html

PHP:  // 手写时间戳比较
来源：http://dali.dashuyun.cn/Article/details/gt2qsllqcpj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jiagoushi.top/Article/details/gt2kuqywbdx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.mhx1999.top/Article/details/gt2pfwpcedy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.tanke756.top/Article/details/gt2gjyenhnk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shangyingyoupin.top/Article/details/gt2cqlnfkhn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.havefunace.top/Article/details/gt2kavakefi.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xuanzx.com/Article/details/gt2yoorzuxx.html

[P08] 处理浮点精度问题
来源：http://dali.aibaodan.cn/Article/details/gt2kcjrcetd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vyoyjnhr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xinyue.icu/Article/details/gt2iomirceg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ivvv.top/Article/details/gt2ukepagnp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.birdmap.top/Article/details/gt2rwrxrimt.html


<!-- 参考信息 -->