代发 wailian999

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtzkalyqek.html

[M01] 读取命令行参数
来源：http://dali.smart0.xyz/Article/details/gtepzibvov.html

Py:   sys.argv[1:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzmzwykdp.html

PHP:  $argv;  $argc;
来源：http://dali.yanxiufei.cn/Article/details/gtgieumdon.html

JS:   process.argv.slice(2)
来源：http://dali.hywenlv.cn/Article/details/gtnwypgmqp.html

TS:   process.argv.slice(2)
来源：http://dali.dianchejie.cn/Article/details/gtpyfpigaq.html

Java: args 数组（main 方法参数）
来源：http://dali.guannengcc.top/Article/details/gtnpmsrupu.html

Go:   os.Args[1:]
来源：http://dali.jinqigfzy.top/Article/details/gtmtgvlisv.html

Ruby: ARGV
来源：http://dali.xuanzx.com/Article/details/gtedxrwqrp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ivvv.top/Article/details/gtiunfxqow.html

[M02] 读取环境变量
来源：http://dali.ehwqpu.com/Article/details/gtvegibdjo.html

Py:   os.environ.get("HOME")
来源：http://dali.hnqzz.top/Article/details/gtbghecfot.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yonumen.top/Article/details/gtdsrrdaee.html

JS:   process.env.HOME
来源：http://dali.iojbl.cn/Article/details/gtpnouekji.html

TS:   process.env.HOME
来源：http://dali.xuanzx.com/Article/details/gtrpjiuogo.html

Java: System.getenv("HOME")
来源：http://dali.ybcxt.top/Article/details/gtpbpsjjpf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hfpthk.cn/Article/details/gtuctdxdnp.html

Ruby: ENV["HOME"]
来源：http://dali.xuanzx.com/Article/details/gtuofqbgij.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jiagoushi.top/Article/details/gtljgdhqnb.html

[M03] 执行外部命令
来源：http://dali.sweek.top/Article/details/gtemymvofd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hysaishi.cn/Article/details/gtbyolwwrc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.havefunace.top/Article/details/gtpieykzul.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxinkj.top/Article/details/gtftvnhqln.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gogol.net.cn/Article/details/gtgfdmyvnn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cdnleiting.top/Article/details/gtcznkxngc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.guowangkeji.top/Article/details/gtfjlrjodc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.aibaodan.cn/Article/details/gthbnodugs.html

C#:   Process.Start("ls", "-l");
来源：http://dali.pengpengdd.cyou/Article/details/gtneyytyzn.html

[M04] 获取当前工作目录
来源：http://dali.cashguo.top/Article/details/gtizogxkwu.html

Py:   os.getcwd()
来源：http://dali.zhengqikj.top/Article/details/gtarkispai.html

PHP:  getcwd();
来源：http://dali.ppjwa.cn/Article/details/gtlxuttblt.html

JS:   process.cwd()
来源：http://dali.9152youxi.cn/Article/details/gtalnalslo.html

TS:   process.cwd()
来源：http://dali.hammf.cn/Article/details/gtxfejfiai.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.pycfn.com/Article/details/gtwdggeizo.html

Go:   os.Getwd()
来源：http://dali.hammf.cn/Article/details/gtxeflzkqp.html

Ruby: Dir.pwd
来源：http://dali.zycfv.cn/Article/details/gtggbvmxdh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenjidiqi.icu/Article/details/gtjgipqhif.html

[M05] 设置退出码
来源：http://dali.sufxvd.cn/Article/details/gtfptsmisz.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtsafnxpdr.html

PHP:  exit(1);
来源：http://dali.smart0.xyz/Article/details/gtxmurefdu.html

JS:   process.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtktcbaulm.html

TS:   process.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtgzmxcfog.html

Java: System.exit(1)
来源：http://dali.bjfxy.top/Article/details/gtlznhbboc.html

Go:   os.Exit(1)
来源：http://dali.cucudq.cn/Article/details/gtexmzegyg.html

Ruby: exit 1
来源：http://dali.aizwys.cn/Article/details/gtgqwuajxo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.svipenyu.cn/Article/details/gtigmtfasr.html

[M06] 向标准错误输出
来源：http://dali.sxryk.cn/Article/details/gtdaywbwxq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ybcxt.top/Article/details/gtqngdwmno.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhengqikj.top/Article/details/gtyykzeahq.html

JS:   console.error("err")
来源：http://dali.nanxinkj.top/Article/details/gtrqidjlrp.html

TS:   console.error("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtntvfalrg.html

Java: System.err.println("err")
来源：http://dali.sxryk.cn/Article/details/gtemtxsfgj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.dashuyun.cn/Article/details/gthqlelews.html

Ruby: warn "err"
来源：http://dali.ehwqpu.com/Article/details/gtcshvmiic.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yanxiufei.cn/Article/details/gtexzrewgd.html

[M07] 判断是否为主入口
来源：http://dali.yongpay.top/Article/details/gtvfbbwztg.html

Py:   if __name__ == "__main__":
来源：http://dali.andypj.xyz/Article/details/gtyqrycbzg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shuidangran.top/Article/details/gtpxwyxnah.html

JS:   require.main === module
来源：http://dali.aizwys.cn/Article/details/gtxxspxwog.html

TS:   require.main === module
来源：http://dali.ppjwa.cn/Article/details/gtjylflqfn.html

Java: public static void main(String[] args)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzsxtsaep.html

Go:   func main()
来源：http://dali.cheryme.top/Article/details/gtypkbqxzp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cashguo.top/Article/details/gthllwzniy.html

C#:   static void Main(string[] args)
来源：http://dali.zhengqikj.top/Article/details/gtuaenwhsc.html

[M08] 获取系统与运行时信息
来源：http://dali.jlsjyb.cn/Article/details/gtladwbfyy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hongshengwenyu.top/Article/details/gtajqjvrmk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.mhx1999.top/Article/details/gtptxaanzv.html

JS:   process.platform;  process.version
来源：http://dali.zhixingplan.top/Article/details/gtxvweweju.html

TS:   process.platform;  process.version
来源：http://dali.tanke756.top/Article/details/gtgqgstund.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zycfv.cn/Article/details/gtdijjirbh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.kuanghao11.cn/Article/details/gtkdgwinwj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.9152youxi.cn/Article/details/gtyzmaqovq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.havefunace.top/Article/details/gtiwoipjqi.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtonsoeivc.html

N. 数据结构与算法
来源：http://dali.nwbrower.top/Article/details/gtodsgaful.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtfkstoubg.html

[N01] 二分查找（有序数组）
来源：http://dali.fengsongda.top/Article/details/gtcrrljmzl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yonumen.top/Article/details/gtssnsadxz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sxryk.cn/Article/details/gtwozafuiv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenjidiqi.icu/Article/details/gtlrwhacgy.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.kuanghao11.cn/Article/details/gthxxogtoh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtmfmxzfga.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtgpipjraw.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.9152youxi.cn/Article/details/gtjplhnvzr.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjnqaeytz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.birdmap.top/Article/details/gtbpirsgou.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pengpengdd.cyou/Article/details/gtclumaoot.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hnxiangtu.top/Article/details/gtzcqokroa.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.vqdsnc.cn/Article/details/gtuhuccqzk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.mhx1999.top/Article/details/gtuymyeuig.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhengqikj.top/Article/details/gtrbzyhhmr.html

Go:   slices.Sort(arr)
来源：http://dali.sysykeji.top/Article/details/gtdisesttp.html

Ruby: arr.sort
来源：http://dali.quarkkingdee.top/Article/details/gtkdrnogow.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.guowangkeji.top/Article/details/gttkbgjfuv.html

[N03] 快速排序（分治示例）
来源：http://dali.jinqigfzy.top/Article/details/gtlukzlhbt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.quarkkingdee.top/Article/details/gtndhhqmqx.html

PHP:  // 递归实现，或用 usort
来源：http://dali.guowangkeji.top/Article/details/gtghotjqpj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.kuanghao11.cn/Article/details/gteotiqojs.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ybcxt.top/Article/details/gtrzmxreyj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shanyushiyangtech.top/Article/details/gtomzmpciv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.tanke756.top/Article/details/gtndtmfhih.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.guowangkeji.top/Article/details/gtitnstabw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenlongwang.top/Article/details/gthuskngwh.html

[N04] 斐波那契数列
来源：http://dali.xylfe.cn/Article/details/gtviyktxhf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gaohongyu789.top/Article/details/gtkqukxyfv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.snrcjt.cn/Article/details/gtfuutxtic.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jyoumei.cn/Article/details/gtgxxrxybl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xziqi.cn/Article/details/gtdnnytfsx.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhixingplan.top/Article/details/gtwnlzhonp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.dashuyun.cn/Article/details/gtohqesjkv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhoulong.xyz/Article/details/gtbpdsdoxg.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gttokblwfq.html

[N05] 最大公约数
来源：http://dali.tianlin.xyz/Article/details/gtultjynyn.html

Py:   math.gcd(a, b)
来源：http://dali.redwolf501.top/Article/details/gtythamgkq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ydzc1.top/Article/details/gtsgkfslgv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhongyouzk.top/Article/details/gtnylultws.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nwbrower.top/Article/details/gtxhuxsybc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhoulong.xyz/Article/details/gtucnkytso.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zdqjudy.top/Article/details/gtgmtaafey.html

Ruby: a.gcd(b)
来源：http://dali.c1oappe.top/Article/details/gtqmpusule.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hongshengwenyu.top/Article/details/gtxyzidwri.html

[N06] 判断回文字符串
来源：http://dali.9152youxi.cn/Article/details/gtxyoxueyl.html

Py:   s == s[::-1]
来源：http://dali.cheryme.top/Article/details/gtzkeszabg.html

PHP:  $s === strrev($s);
来源：http://dali.yuxming.cn/Article/details/gtklyntkxz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gtnytwkhff.html

TS:   s === [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gtorvqecnr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlwcsyilq.html

Go:   // 双指针从两端比较
来源：http://dali.zhongyouzk.top/Article/details/gtinhnbpek.html

Ruby: s == s.reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnkdukzlw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cucudq.cn/Article/details/gtxrukksxc.html

[N07] 两数之和（返回下标）
来源：http://dali.jqgfzy.top/Article/details/gtbtgeuumr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.andypj.xyz/Article/details/gtejwokrhs.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jlsjyb.cn/Article/details/gtxezczpdw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shuidangran.top/Article/details/gtwgxjukec.html

TS:   // 手写 Map<string, number>
来源：http://dali.yuanzhike.top/Article/details/gtcjjiechc.html

Java: // 手写 HashMap
来源：http://dali.hongshengwenyu.top/Article/details/gtbasmyznv.html

Go:   // 手写 map[int]int
来源：http://dali.hnqzz.top/Article/details/gtobklaqnw.html

Ruby: // 手写 Hash
来源：http://dali.chenjidiqi.icu/Article/details/gtmsistnvn.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yj20258.top/Article/details/gtumqltcfe.html

[N08] 生成全排列
来源：http://dali.yj20258888.top/Article/details/gtpniauwpf.html

Py:   itertools.permutations(arr)
来源：http://dali.xinyue.icu/Article/details/gtupyemxau.html

PHP:  // 手写递归交换
来源：http://dali.jiagoushi.top/Article/details/gtboazryiv.html

JS:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gtvnhlcpgs.html

TS:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gthizcxtmg.html

Java: // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtibdghsbg.html

Go:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gtmxramsnt.html

Ruby: arr.permutation.to_a
来源：http://dali.nwbrower.top/Article/details/gtphtqptgi.html

C#:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gtazlzjinq.html

[N09] 栈与队列
来源：http://dali.ehwqpu.com/Article/details/gtvakybkrr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yonumen.top/Article/details/gtbjxgsbee.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.daria6918.cn/Article/details/gtuqrkajpk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.bjfxy.top/Article/details/gtxlwjhyqs.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.snrcjt.cn/Article/details/gtjsugralw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.meibo888.top/Article/details/gtghzlagpe.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gttxwknxsm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.chenzaomai.com/Article/details/gthebbqung.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cheryme.top/Article/details/gtisxtnqut.html

[N10] 链表节点定义
来源：http://dali.havefunace.top/Article/details/gtpxyxdfqa.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.nanxinkj.top/Article/details/gtecxnlluf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sweek.top/Article/details/gtyulcppmk.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gtpyozhity.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhiwuduotai.top/Article/details/gtefsaxqyv.html

Java: class Node { int v; Node next; }
来源：http://dali.svipenyu.cn/Article/details/gtjofmhbsg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.iojbl.cn/Article/details/gtamgldnbv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hongshengwenyu.top/Article/details/gtwednnhlh.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpdajkkhc.html

[N11] 二叉树中序遍历
来源：http://dali.kuanghao11.cn/Article/details/gtylpfpsrc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.dashuyun.cn/Article/details/gtyocrjnxr.html

PHP:  // 手写递归函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtutpmzzhd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjvnkcstc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xylfe.cn/Article/details/gtzxsiaamy.html

Java: // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gtsgndltfo.html

Go:   // 手写递归
来源：http://dali.hongshengwenyu.top/Article/details/gthrwmisms.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ppjwa.cn/Article/details/gtgrjcmadz.html

C#:   // 手写递归
来源：http://dali.ydzc1.top/Article/details/gtpysjreml.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yongpay.top/Article/details/gtthhrftce.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.quarkkingdee.top/Article/details/gthapkunph.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shuidangran.top/Article/details/gtjjlvcczu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhengqikj.top/Article/details/gtsnjrhksx.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.feifeiyinyue.top/Article/details/gtlgalqyaa.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigufen.top/Article/details/gtgiudwqcv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hnqzz.top/Article/details/gttayaeijz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.nanxinkj.top/Article/details/gtuyswrluv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jlsjyb.cn/Article/details/gtjggyfaay.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtcbaalvxh.html

O. 并发与异步
来源：http://dali.cheryme.top/Article/details/gtmndusgac.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtnrvmdqxh.html

[O01] 启动一个线程
来源：http://dali.zhixingplan.top/Article/details/gtkkhsgfkr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hongshengwenyu.top/Article/details/gtmuewyhji.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.chenjidiqi.icu/Article/details/gtyvdhfesn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cashguo.top/Article/details/gtuwbolpls.html

TS:   // 同 JS
来源：http://dali.shzxlz.cn/Article/details/gtmsqlvbbl.html

Java: new Thread(() -> f()).start()
来源：http://dali.wangshuangyany.cn/Article/details/gtoiidccnf.html

Go:   go f()
来源：http://dali.sxryk.cn/Article/details/gttewlngaa.html

Ruby: Thread.new { f }
来源：http://dali.hongshengwenyu.top/Article/details/gtdcimagqr.html

C#:   Task.Run(() => F());
来源：http://dali.jinqigfzy.top/Article/details/gtuykjmexd.html

[O02] 使用线程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcmohfhwi.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jiagoushi.top/Article/details/gtsjgzwmxi.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrdfltrec.html

JS:   // worker_threads 线程池
来源：http://dali.yj20258.top/Article/details/gtpnyskzjz.html

TS:   // worker_threads 线程池
来源：http://dali.feifeiyinyue.top/Article/details/gtcvgtwjto.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.iojbl.cn/Article/details/gtslcxluxz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gotoacloud.top/Article/details/gtjxveilab.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yongpay.top/Article/details/gtdwyrmpwo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.birdmap.top/Article/details/gtccbsjuqp.html

[O03] 加锁保护共享数据
来源：http://dali.tanke756.top/Article/details/gtillbvlbd.html

Py:   with lock: shared += 1
来源：http://dali.birdmap.top/Article/details/gtakupzosp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hongshengwenyu.top/Article/details/gtxdyxxtsq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinghuilouyu.cn/Article/details/gtlboafxwo.html

TS:   // 同 JS
来源：http://dali.jyoumei.cn/Article/details/gtlkyxjtls.html

Java: synchronized (this) { shared++; }
来源：http://dali.kuanghao11.cn/Article/details/gtocjtuxuy.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ehwqpu.com/Article/details/gtsjouddlz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.kuanghao11.cn/Article/details/gtrapifexq.html

C#:   lock (gate) { shared++; }
来源：http://dali.kuanghao11.cn/Article/details/gtwuezsfbe.html

[O04] 定义异步函数并等待
来源：http://dali.chenjidiqi.icu/Article/details/gtkdusbnmm.html

Py:   async def f():⏎    await g()
来源：http://dali.jlsjyb.cn/Article/details/gtzjhptssl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhoulong.xyz/Article/details/gtctpsrtuc.html

JS:   async function f() { await g(); }
来源：http://dali.zycfv.cn/Article/details/gttqwdnrhz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenlongwang.top/Article/details/gtduziaghq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.daxiang520.top/Article/details/gtasicjxls.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.aibaodan.cn/Article/details/gtkbiisbwq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yongpay.top/Article/details/gtgprrudwu.html

C#:   async Task F() { await G(); }
来源：http://dali.svipenyu.cn/Article/details/gtjwrkferi.html

[O05] 并发执行并等待全部完成
来源：http://dali.hywenlv.cn/Article/details/gtomvddoib.html

Py:   asyncio.gather(*tasks)
来源：http://dali.vqdsnc.cn/Article/details/gtfydwtmzm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.fzhhl.top/Article/details/gtehcsctmt.html

JS:   await Promise.all(tasks)
来源：http://dali.yj20258.top/Article/details/gtoudijapw.html

TS:   await Promise.all(tasks)
来源：http://dali.ivvv.top/Article/details/gtlfjnklrg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yonumen.top/Article/details/gtfksfxcyj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.c1oappe.top/Article/details/gtxxisyqws.html

Ruby: threads.map(&:join)
来源：http://dali.316326.xyz/Article/details/gtnqohqizh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.fzhhl.top/Article/details/gtqvsfhaoy.html

[O06] 使用进程池
来源：http://dali.jinqigufen.top/Article/details/gtaklqptzf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhixingplan.top/Article/details/gtzxracbjo.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shangyingyoupin.top/Article/details/gtymzimlrv.html

JS:   // child_process / cluster 模块
来源：http://dali.zhengqikj.top/Article/details/gtoofdmrzg.html

TS:   // child_process / cluster 模块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxmojpgwx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shangyingyoupin.top/Article/details/gtoalouiaf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hnxiangtu.top/Article/details/gtwztdzmpb.html

Ruby: // fork 块
来源：http://dali.pengpengdd.cyou/Article/details/gtpieytvqn.html

C#:   Parallel.For
来源：http://dali.316326.xyz/Article/details/gtlowchllg.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtcvriozjp.html

P. 常用工具函数
来源：http://dali.hfpthk.cn/Article/details/gtcsuntvlf.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtrkdsobjp.html

[P01] 生成 UUID
来源：http://dali.xuetiantiany.cn/Article/details/gtmvblvzdt.html

Py:   str(uuid.uuid4())
来源：http://dali.iojbl.cn/Article/details/gtpbynlvpv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.feifeiyinyue.top/Article/details/gtidmunuds.html

JS:   crypto.randomUUID()
来源：http://dali.jianghu66.top/Article/details/gtmydttiwh.html

TS:   crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaoamdrxj.html

Java: UUID.randomUUID().toString()
来源：http://dali.hywenlv.cn/Article/details/gtfhjxztmi.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbovmdwjg.html

Ruby: SecureRandom.uuid
来源：http://dali.gzhubu.top/Article/details/gtsrquqyak.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.redwolf501.top/Article/details/gtzalqyfxp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.mhx1999.top/Article/details/gtwlvtcbsy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jqgfzy.top/Article/details/gtnaokmrcz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gotoacloud.top/Article/details/gtmywusmxb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.bjfxy.top/Article/details/gtmpgpabbm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.fengsongda.top/Article/details/gtbtazvoph.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnqjahxrg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yangfankeji.com/Article/details/gtfdpovesf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xuanzx.com/Article/details/gtvffhhytn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jianghu66.top/Article/details/gtrxdwufwb.html

[P03] 生成短随机字符串
来源：http://dali.jinqigfzy.top/Article/details/gtgljajmot.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.chenlongwang.top/Article/details/gtxvfjxjjh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cucudq.cn/Article/details/gtiytjzbpe.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.andypj.xyz/Article/details/gtuhailivi.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.9152youxi.cn/Article/details/gtsrzupfqj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtvosvgoey.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jyoumei.cn/Article/details/gtydnotuks.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cucudq.cn/Article/details/gtbtgiajvc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ivvv.top/Article/details/gtxamohvby.html

[P04] 求长度
来源：http://dali.cheryme.top/Article/details/gtzpkekesz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.daxiang520.top/Article/details/gtnkzmfnoo.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gtdxfhijes.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.mhx1999.top/Article/details/gtnwrpgcoe.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jianghu66.top/Article/details/gtucbcwbdp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinghuilouyu.cn/Article/details/gtxshsgzkx.html

Go:   len(arr);  len(m)
来源：http://dali.c1oappe.top/Article/details/gtvjxnggoh.html

Ruby: x.length;  x.size
来源：http://dali.fzhhl.top/Article/details/gtnzvdvrwl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.bjfxy.top/Article/details/gtphskcqdo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shzxlz.cn/Article/details/gtjdbgperg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gotoacloud.top/Article/details/gtuhdgmfpl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hysaishi.cn/Article/details/gtsthefqck.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.fengsongda.top/Article/details/gtclogxvwa.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shuidangran.top/Article/details/gtuelwytsq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xuetiantiany.cn/Article/details/gtzxiceesd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhoulong.xyz/Article/details/gtspapvvqr.html

Ruby: a == b
来源：http://dali.jinghuilouyu.cn/Article/details/gtivyiliif.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yj20258.top/Article/details/gtpzgeedeg.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.andypj.xyz/Article/details/gtvvtsxano.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.fengsongda.top/Article/details/gtwkmktmgk.html

PHP:  if (empty($x)) {}
来源：http://dali.hammf.cn/Article/details/gtpcafbsbm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.0kj1m.cn/Article/details/gtvryelogp.html

TS:   if (x == null) {}
来源：http://dali.9152youxi.cn/Article/details/gtuzbhnrye.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtyhkdhmwi.html

Go:   if x == nil {}
来源：http://dali.yj20258888.top/Article/details/gttahjnuce.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hywenlv.cn/Article/details/gthaufauig.html

C#:   if (x is null) {}
来源：http://dali.daria6918.cn/Article/details/gtmmokkqhx.html

[P07] 防抖与节流
来源：http://dali.xuetiantiany.cn/Article/details/gtywpuzzce.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.guowangkeji.top/Article/details/gtbeqeuqoj.html


<!-- 参考信息 -->