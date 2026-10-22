代发 wailian999

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yangfankeji.com/Article/details/gtwuwgswhi.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nwbrower.top/Article/details/gtneoaqccw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hysaishi.cn/Article/details/gttsqkqupq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.nwbrower.top/Article/details/gtzuozczxt.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.mhx1999.top/Article/details/gtucuwasax.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sweek.top/Article/details/gtfkasjlrg.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtpnsmebus.html

M. 命令行 / 进程 / 环境
来源：http://dali.cheryme.top/Article/details/gtdgyabxac.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtsbbnhpmw.html

[M01] 读取命令行参数
来源：http://dali.mhx1999.top/Article/details/gttcplxalu.html

Py:   sys.argv[1:]
来源：http://dali.guowangkeji.top/Article/details/gtapyymbqd.html

PHP:  $argv;  $argc;
来源：http://dali.shanyushiyangtech.top/Article/details/gtnjpnnfxk.html

JS:   process.argv.slice(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtstnbuyht.html

TS:   process.argv.slice(2)
来源：http://dali.zhixingplan.top/Article/details/gtefkaceyk.html

Java: args 数组（main 方法参数）
来源：http://dali.hongshengwenyu.top/Article/details/gtieqmeaur.html

Go:   os.Args[1:]
来源：http://dali.gogol.net.cn/Article/details/gtblnlrbul.html

Ruby: ARGV
来源：http://dali.yj20258.top/Article/details/gtiixjdbis.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cqqwz.cn/Article/details/gtoaapqccg.html

[M02] 读取环境变量
来源：http://dali.tian-w.cn/Article/details/gtjdspjhwo.html

Py:   os.environ.get("HOME")
来源：http://dali.xinyue.icu/Article/details/gtthkbdeav.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nanxinkj.top/Article/details/gtkgarsltz.html

JS:   process.env.HOME
来源：http://dali.0kj1m.cn/Article/details/gtctyydoob.html

TS:   process.env.HOME
来源：http://dali.ybcxt.top/Article/details/gtrjxvolla.html

Java: System.getenv("HOME")
来源：http://dali.ppjwa.cn/Article/details/gtgccxsxwk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.haohaochexian.top/Article/details/gtbvqgnavd.html

Ruby: ENV["HOME"]
来源：http://dali.mhx1999.top/Article/details/gtycrrhskq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gtpiowftki.html

[M03] 执行外部命令
来源：http://dali.nanxinkj.top/Article/details/gtniuixhiu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhoulong.xyz/Article/details/gtciajqcrx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cucudq.cn/Article/details/gtwvaixklp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgufenzy.top/Article/details/gtpwvjvidi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gzhubu.top/Article/details/gtpolzoirp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jlsjyb.cn/Article/details/gtbpytilgj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gotoacloud.top/Article/details/gtjzitsnnq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinqigufen.top/Article/details/gtcdvuolld.html

C#:   Process.Start("ls", "-l");
来源：http://dali.haohaochexian.top/Article/details/gtovvivnwo.html

[M04] 获取当前工作目录
来源：http://dali.cashguo.top/Article/details/gthdwxinii.html

Py:   os.getcwd()
来源：http://dali.nanxinkj.top/Article/details/gtyxijsudm.html

PHP:  getcwd();
来源：http://dali.hnxiangtu.top/Article/details/gtvkaiulon.html

JS:   process.cwd()
来源：http://dali.hnxiangtu.top/Article/details/gtiojraleo.html

TS:   process.cwd()
来源：http://dali.ivvv.top/Article/details/gtizlzjqus.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.havefunace.top/Article/details/gtdvhrybsx.html

Go:   os.Getwd()
来源：http://dali.sweek.top/Article/details/gtbyiakgki.html

Ruby: Dir.pwd
来源：http://dali.9152youxi.cn/Article/details/gtuatdtilb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xziqi.cn/Article/details/gtdaaeeybk.html

[M05] 设置退出码
来源：http://dali.jiagoushi.top/Article/details/gtuyvwpvoy.html

Py:   sys.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gtgrgewcnv.html

PHP:  exit(1);
来源：http://dali.xylfe.cn/Article/details/gtjpygxioi.html

JS:   process.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gthynooqid.html

TS:   process.exit(1)
来源：http://dali.316326.xyz/Article/details/gtehjolpcj.html

Java: System.exit(1)
来源：http://dali.316326.xyz/Article/details/gtinyyotxh.html

Go:   os.Exit(1)
来源：http://dali.yongpay.top/Article/details/gtdfzvtgri.html

Ruby: exit 1
来源：http://dali.yuxming.cn/Article/details/gtrsxfaaqg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.0kj1m.cn/Article/details/gtkbekahft.html

[M06] 向标准错误输出
来源：http://dali.zycfv.cn/Article/details/gtgclrmuxz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.svipenyu.cn/Article/details/gtuipkbzld.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yvedp.cn/Article/details/gtyneiqnvi.html

JS:   console.error("err")
来源：http://dali.xuanzx.com/Article/details/gtowquauoo.html

TS:   console.error("err")
来源：http://dali.aibaodan.cn/Article/details/gtvtdhebbn.html

Java: System.err.println("err")
来源：http://dali.yj20258888.top/Article/details/gtqlxbcfdj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gogol.net.cn/Article/details/gtttcjlwcv.html

Ruby: warn "err"
来源：http://dali.havefunace.top/Article/details/gtmguovtmp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shzxlz.cn/Article/details/gthagqzwgr.html

[M07] 判断是否为主入口
来源：http://dali.cdnleiting.top/Article/details/gttkipyhfg.html

Py:   if __name__ == "__main__":
来源：http://dali.yangfankeji.com/Article/details/gtcrvnlchv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cashguo.top/Article/details/gtvyjahmdq.html

JS:   require.main === module
来源：http://dali.xziqi.cn/Article/details/gthavbomwq.html

TS:   require.main === module
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfvxcztzp.html

Java: public static void main(String[] args)
来源：http://dali.zhiwuduotai.top/Article/details/gtikwcieur.html

Go:   func main()
来源：http://dali.hysaishi.cn/Article/details/gtafmzdhpi.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.daxiang520.top/Article/details/gteiolvvjk.html

C#:   static void Main(string[] args)
来源：http://dali.yvedp.cn/Article/details/gtmsvxpwxi.html

[M08] 获取系统与运行时信息
来源：http://dali.daria6918.cn/Article/details/gtlaxdvsap.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmnurugin.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jianghu66.top/Article/details/gtlheojhkp.html

JS:   process.platform;  process.version
来源：http://dali.jinqigfzy.top/Article/details/gtjoaeldtn.html

TS:   process.platform;  process.version
来源：http://dali.chenzaomai.com/Article/details/gtvgayrgra.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xylfe.cn/Article/details/gtgmmudmpz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cashguo.top/Article/details/gtwjltfvds.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yvedp.cn/Article/details/gtcohwvjif.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.svipenyu.cn/Article/details/gtupffstde.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtgrcrclmd.html

N. 数据结构与算法
来源：http://dali.snrcjt.cn/Article/details/gtdcmmvtug.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gteadzeota.html

[N01] 二分查找（有序数组）
来源：http://dali.daria6918.cn/Article/details/gtauutzzpx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtuadybsry.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nwbrower.top/Article/details/gtcwdubuml.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigufen.top/Article/details/gttngolcug.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daxiang520.top/Article/details/gtnfxxzdpy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtccnorrzz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gteffcikqj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.iojbl.cn/Article/details/gtihgusskx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthleghaas.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ivvv.top/Article/details/gtjhdsodga.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoilrlzyo.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.pycfn.com/Article/details/gtamutlvzi.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuanzx.com/Article/details/gtnwasufab.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.meibo888.top/Article/details/gtzanmmuzr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.kuanghao11.cn/Article/details/gtserqngwp.html

Go:   slices.Sort(arr)
来源：http://dali.ybcxt.top/Article/details/gtcopiiatl.html

Ruby: arr.sort
来源：http://dali.jinghuilouyu.cn/Article/details/gtbwvutjzv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cashguo.top/Article/details/gtbtnwqbxp.html

[N03] 快速排序（分治示例）
来源：http://dali.sysykeji.top/Article/details/gtiejmcckl.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.daxiang520.top/Article/details/gtlyxexyet.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ydzc1.top/Article/details/gtzjyeedov.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgfzy.top/Article/details/gtjvpwqkam.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgfzy.top/Article/details/gthwhkuuxj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.fengsongda.top/Article/details/gtfsrwvzmj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jqgufenzy.top/Article/details/gtjhhcjitx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cqqwz.cn/Article/details/gtxdmfkdpf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cheryme.top/Article/details/gtlbkeufuv.html

[N04] 斐波那契数列
来源：http://dali.ppjwa.cn/Article/details/gtrkvkszpq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cashguo.top/Article/details/gtalhzllcr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zycfv.cn/Article/details/gthwhpdyuu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yonumen.top/Article/details/gtrtwxxxah.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yueranfly.top/Article/details/gtggrnsaro.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.mhx1999.top/Article/details/gtkvznolct.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jqgufenzy.top/Article/details/gthqqgnqca.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cqqwz.cn/Article/details/gtamfpxmpq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.smart0.xyz/Article/details/gtxhucmgyf.html

[N05] 最大公约数
来源：http://dali.zhengqikj.top/Article/details/gtrfyadohx.html

Py:   math.gcd(a, b)
来源：http://dali.tanke756.top/Article/details/gthuigkyzh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xylfe.cn/Article/details/gtwgwzdwzl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sysykeji.top/Article/details/gtugexxhyh.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tianlin.xyz/Article/details/gtazenowne.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhixingplan.top/Article/details/gtqetoknkw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjlwmskrk.html

Ruby: a.gcd(b)
来源：http://dali.smart0.xyz/Article/details/gtamdzixks.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jlsjyb.cn/Article/details/gtwjkaujlb.html

[N06] 判断回文字符串
来源：http://dali.jinqigufen.top/Article/details/gtcxvyxhxj.html

Py:   s == s[::-1]
来源：http://dali.daxiang520.top/Article/details/gtnbhtlixk.html

PHP:  $s === strrev($s);
来源：http://dali.iojbl.cn/Article/details/gtdkihxmnk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gtbhoidtws.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gtzakrbkgx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinqigufen.top/Article/details/gtsprbsowu.html

Go:   // 双指针从两端比较
来源：http://dali.tianlin.xyz/Article/details/gtvtjkveew.html

Ruby: s == s.reverse
来源：http://dali.yj202588.top/Article/details/gtujqttudz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.daxiang520.top/Article/details/gtiskwuovk.html

[N07] 两数之和（返回下标）
来源：http://dali.ydzc1.top/Article/details/gtbntpycmd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xuetiantiany.cn/Article/details/gtfsmsdkkb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sufxvd.cn/Article/details/gtuwihuvuy.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zycfv.cn/Article/details/gtxeegioas.html

TS:   // 手写 Map<string, number>
来源：http://dali.bjfxy.top/Article/details/gtblkpxujn.html

Java: // 手写 HashMap
来源：http://dali.jinqigufen.top/Article/details/gtdlcqyosm.html

Go:   // 手写 map[int]int
来源：http://dali.cdnleiting.top/Article/details/gtglzpkbhd.html

Ruby: // 手写 Hash
来源：http://dali.yueranfly.top/Article/details/gttlkejsht.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.fengsongda.top/Article/details/gtbnpcqaln.html

[N08] 生成全排列
来源：http://dali.316326.xyz/Article/details/gtdxdufdzq.html

Py:   itertools.permutations(arr)
来源：http://dali.zycfv.cn/Article/details/gtytfleuha.html

PHP:  // 手写递归交换
来源：http://dali.0kj1m.cn/Article/details/gtjwrdffdj.html

JS:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtrrkhgcjy.html

TS:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gtsgzpciyh.html

Java: // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gtbmneqcml.html

Go:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtholnhfvs.html

Ruby: arr.permutation.to_a
来源：http://dali.fengsongda.top/Article/details/gtbnfvptwm.html

C#:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gtoreviziq.html

[N09] 栈与队列
来源：http://dali.hnqzz.top/Article/details/gttwljfhec.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yangfankeji.com/Article/details/gtlqtfpygk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhoulong.xyz/Article/details/gtwovmdgkx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cdnleiting.top/Article/details/gtbxoavhlr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.9152youxi.cn/Article/details/gtvtiissqz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yj20258888.top/Article/details/gtepjnnpbb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcdaonzqm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cqqwz.cn/Article/details/gttpvnkkwd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.daxiang520.top/Article/details/gtxttkiaoc.html

[N10] 链表节点定义
来源：http://dali.hywenlv.cn/Article/details/gtmyokwfqn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.pengpengdd.cyou/Article/details/gthqyjgfxb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.aizwys.cn/Article/details/gtqhyrxdar.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.feifeiyinyue.top/Article/details/gtkewltrwa.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.dianchejie.cn/Article/details/gtsrxsbdnq.html

Java: class Node { int v; Node next; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzwlpweaj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.0kj1m.cn/Article/details/gthikwdvej.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cucudq.cn/Article/details/gtbyfjqlms.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yongpay.top/Article/details/gtgsxzscxl.html

[N11] 二叉树中序遍历
来源：http://dali.shuidangran.top/Article/details/gtuqufwabq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hnqzz.top/Article/details/gtewamanlv.html

PHP:  // 手写递归函数
来源：http://dali.jqgfzy.top/Article/details/gtmvfcidkj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.kuanghao11.cn/Article/details/gtmnkdpmvp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258.top/Article/details/gthxmdwxks.html

Java: // 手写递归
来源：http://dali.daria6918.cn/Article/details/gtdoicckrl.html

Go:   // 手写递归
来源：http://dali.yonumen.top/Article/details/gttocjfbon.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwpuydyih.html

C#:   // 手写递归
来源：http://dali.hnxiangtu.top/Article/details/gtbaucyrdq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.daxiang520.top/Article/details/gtxtvbicst.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.tian-w.cn/Article/details/gtwoorrjty.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzjlzgvwl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxinkj.top/Article/details/gtquhhqibw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fzhhl.top/Article/details/gtszdnpxvs.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nwbrower.top/Article/details/gteivqxula.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.guowangkeji.top/Article/details/gthzeegmga.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hywenlv.cn/Article/details/gtyatjzfxl.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenzaomai.com/Article/details/gtigagqhrn.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtcncoqtjn.html

O. 并发与异步
来源：http://dali.hnqzz.top/Article/details/gtrkomcdxn.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtsmlxbycj.html

[O01] 启动一个线程
来源：http://dali.haohaochexian.top/Article/details/gtpzmhwtij.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.kuanghao11.cn/Article/details/gtvnvhupsl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.guowangkeji.top/Article/details/gtoaoidxmg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hammf.cn/Article/details/gtxkqpcwbx.html

TS:   // 同 JS
来源：http://dali.hysaishi.cn/Article/details/gttjgspdah.html

Java: new Thread(() -> f()).start()
来源：http://dali.mhx1999.top/Article/details/gtrxjwrbrs.html

Go:   go f()
来源：http://dali.hysaishi.cn/Article/details/gtpnbryict.html

Ruby: Thread.new { f }
来源：http://dali.zhoulong.xyz/Article/details/gtkyxzoaoz.html

C#:   Task.Run(() => F());
来源：http://dali.shanyushiyangkeji.top/Article/details/gtculsuagj.html

[O02] 使用线程池
来源：http://dali.feifeiyinyue.top/Article/details/gtlhccfiuv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.pengpengdd.cyou/Article/details/gtbrmapdds.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.havefunace.top/Article/details/gtteesjeoh.html

JS:   // worker_threads 线程池
来源：http://dali.yuxming.cn/Article/details/gtutjmogov.html

TS:   // worker_threads 线程池
来源：http://dali.quarkkingdee.top/Article/details/gtbcllyjuw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.tianlin.xyz/Article/details/gtzkkusqwj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.9152youxi.cn/Article/details/gtyhpivmfl.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjpxiuzdp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jqgfzy.top/Article/details/gtejyrmgdf.html

[O03] 加锁保护共享数据
来源：http://dali.hywenlv.cn/Article/details/gtqjrlachf.html

Py:   with lock: shared += 1
来源：http://dali.cheryme.top/Article/details/gtppshrsuv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.0kj1m.cn/Article/details/gtxwqyrlhz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cdnleiting.top/Article/details/gtpfvjhndd.html

TS:   // 同 JS
来源：http://dali.gotoacloud.top/Article/details/gtjppyzpli.html

Java: synchronized (this) { shared++; }
来源：http://dali.hywenlv.cn/Article/details/gtwuwamjar.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jiagoushi.top/Article/details/gtkbdujivo.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gtavlfxhfx.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gtzfhpvxjm.html

[O04] 定义异步函数并等待
来源：http://dali.chenlongwang.top/Article/details/gtmeokxdzs.html

Py:   async def f():⏎    await g()
来源：http://dali.guowangkeji.top/Article/details/gtidgdmhms.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.sweek.top/Article/details/gtxuzegfnf.html

JS:   async function f() { await g(); }
来源：http://dali.hnxiangtu.top/Article/details/gtkahgxfns.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gtmghboqfz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.dianchejie.cn/Article/details/gtelrdxipl.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hfpthk.cn/Article/details/gtyqxmdeeh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yangfankeji.com/Article/details/gtlniugccp.html

C#:   async Task F() { await G(); }
来源：http://dali.jqgfzy.top/Article/details/gtsvtewlpq.html

[O05] 并发执行并等待全部完成
来源：http://dali.hongshengwenyu.top/Article/details/gtofyaonkm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jqgufenzy.top/Article/details/gtxacncixh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.svipenyu.cn/Article/details/gtipimtrer.html

JS:   await Promise.all(tasks)
来源：http://dali.zhixingplan.top/Article/details/gtttjimcsu.html

TS:   await Promise.all(tasks)
来源：http://dali.havefunace.top/Article/details/gtmbozywlt.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.nanxinkj.top/Article/details/gtujudkyel.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhengqikj.top/Article/details/gttawtsoey.html

Ruby: threads.map(&:join)
来源：http://dali.zhiwuduotai.top/Article/details/gtouhyborg.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.pycfn.com/Article/details/gtfwazbeca.html

[O06] 使用进程池
来源：http://dali.shangyingyoupin.top/Article/details/gttxcfekav.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.havefunace.top/Article/details/gtxvrbcjxg.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gogol.net.cn/Article/details/gtmytemsiv.html

JS:   // child_process / cluster 模块
来源：http://dali.xuanzx.com/Article/details/gtwfpocdoz.html

TS:   // child_process / cluster 模块
来源：http://dali.dashuyun.cn/Article/details/gtuxrpfreo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ppjwa.cn/Article/details/gtwpawjgee.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ppjwa.cn/Article/details/gtyctqxjlt.html

Ruby: // fork 块
来源：http://dali.haohaochexian.top/Article/details/gtqjjxaopf.html

C#:   Parallel.For
来源：http://dali.guowangkeji.top/Article/details/gtmxkdjtka.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtsnqpvasn.html

P. 常用工具函数
来源：http://dali.yangfankeji.com/Article/details/gthzbvfqql.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtyzbubgeg.html

[P01] 生成 UUID
来源：http://dali.dashuyun.cn/Article/details/gtdegoexqc.html

Py:   str(uuid.uuid4())
来源：http://dali.ppjwa.cn/Article/details/gtowebvjyw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shzxlz.cn/Article/details/gtpckuglze.html

JS:   crypto.randomUUID()
来源：http://dali.nanxinkj.top/Article/details/gtgijlxfpf.html

TS:   crypto.randomUUID()
来源：http://dali.snrcjt.cn/Article/details/gtlzgtkbrd.html

Java: UUID.randomUUID().toString()
来源：http://dali.jiagoushi.top/Article/details/gtrvvhwgvo.html

Go:   // 用 github.com/google/uuid
来源：http://dali.haohaochexian.top/Article/details/gtinldfhte.html

Ruby: SecureRandom.uuid
来源：http://dali.hammf.cn/Article/details/gtjzhrusqb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.nanxuanxn.top/Article/details/gtpfeybrff.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yj202588.top/Article/details/gtsepfzhnd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.daxiang520.top/Article/details/gtcqcxtbzv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gogol.net.cn/Article/details/gtitssbmzm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hysaishi.cn/Article/details/gttqtaovst.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hysaishi.cn/Article/details/gtomqxvxbn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hnxiangtu.top/Article/details/gtbfcufydn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.sysykeji.top/Article/details/gtqutibuxc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.havefunace.top/Article/details/gtcgsnoeyi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cheryme.top/Article/details/gtsgmksnia.html

[P03] 生成短随机字符串
来源：http://dali.nanxinkj.top/Article/details/gtpcaqdxqw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.nwbrower.top/Article/details/gtsiluskid.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.redwolf501.top/Article/details/gtqldstkrg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenzaomai.com/Article/details/gtgnffnqxm.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinqigufen.top/Article/details/gtcciggukz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ydzc1.top/Article/details/gtouyoushi.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yuxming.cn/Article/details/gtrhobfyml.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinqigufen.top/Article/details/gtbbxkxplm.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zdqjudy.top/Article/details/gtfqbxujnp.html

[P04] 求长度
来源：http://dali.zhixingplan.top/Article/details/gtztuimexv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhongyouzk.top/Article/details/gttslnigss.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gtonipgmth.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.svipenyu.cn/Article/details/gtjbgkmjvw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nwbrower.top/Article/details/gtbaquwsjo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhengqikj.top/Article/details/gtgcdhpqim.html

Go:   len(arr);  len(m)
来源：http://dali.ppjwa.cn/Article/details/gtbmrwjxar.html

Ruby: x.length;  x.size
来源：http://dali.kuanghao11.cn/Article/details/gtuzlyckww.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ivvv.top/Article/details/gtsxgtqphv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hfpthk.cn/Article/details/gtrgfnbrge.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yongpay.top/Article/details/gtivvycpik.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hnqzz.top/Article/details/gtkxgdazqs.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shangyingyoupin.top/Article/details/gtktohqxhz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xuanzx.com/Article/details/gtodputpwm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jinyuanbaomall.cn/Article/details/gtybqafexj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtemanrlkb.html

Ruby: a == b
来源：http://dali.gogol.net.cn/Article/details/gtphvignnr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.andypj.xyz/Article/details/gtqixpsgqf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.9152youxi.cn/Article/details/gtvbxcflzy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.9152youxi.cn/Article/details/gtveuovjka.html

PHP:  if (empty($x)) {}
来源：http://dali.hnxiangtu.top/Article/details/gthhtijwun.html


<!-- 参考信息 -->