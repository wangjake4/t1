代发 wailian999

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigufen.top/Article/details/gtlpuzwghj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yonumen.top/Article/details/gtvzwntlpa.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nanxinkj.top/Article/details/gtdaojnmzs.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cucudq.cn/Article/details/gtupmdbksj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.tanke756.top/Article/details/gtfmufwzds.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xylfe.cn/Article/details/gtbqpgavma.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtiynaymwb.html

M. 命令行 / 进程 / 环境
来源：http://dali.sufxvd.cn/Article/details/gtqkbbbjwv.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtrftnpizi.html

[M01] 读取命令行参数
来源：http://dali.shzxlz.cn/Article/details/gtthplburi.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gteaflqenf.html

PHP:  $argv;  $argc;
来源：http://dali.sufxvd.cn/Article/details/gtrxcpemjm.html

JS:   process.argv.slice(2)
来源：http://dali.9152youxi.cn/Article/details/gtutwryhfw.html

TS:   process.argv.slice(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiubezpqn.html

Java: args 数组（main 方法参数）
来源：http://dali.ppjwa.cn/Article/details/gtfdkqchin.html

Go:   os.Args[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gtwmsipnjm.html

Ruby: ARGV
来源：http://dali.jiagoushi.top/Article/details/gtvbtlwwqu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.smart0.xyz/Article/details/gtvpzycwup.html

[M02] 读取环境变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtwtvksylq.html

Py:   os.environ.get("HOME")
来源：http://dali.svipenyu.cn/Article/details/gtzvvuxmvh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.haohaochexian.top/Article/details/gtxiimflfm.html

JS:   process.env.HOME
来源：http://dali.jlsjyb.cn/Article/details/gtncamhirc.html

TS:   process.env.HOME
来源：http://dali.ydzc1.top/Article/details/gtwgnvqrsc.html

Java: System.getenv("HOME")
来源：http://dali.yvedp.cn/Article/details/gtxeyunmxc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.andypj.xyz/Article/details/gtpggbjhhl.html

Ruby: ENV["HOME"]
来源：http://dali.jianghu66.top/Article/details/gteoxgkiro.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.snrcjt.cn/Article/details/gtiqnbqvve.html

[M03] 执行外部命令
来源：http://dali.aizwys.cn/Article/details/gtqdkufkir.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yonumen.top/Article/details/gtfnunobvu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.bjfxy.top/Article/details/gtucodznlr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.sysykeji.top/Article/details/gttycacdsg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ybcxt.top/Article/details/gtswjjqtoo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinqigfzy.top/Article/details/gtyhorkstj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cheryme.top/Article/details/gtjvpzjopb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gotoacloud.top/Article/details/gtsbspetcs.html

C#:   Process.Start("ls", "-l");
来源：http://dali.pycfn.com/Article/details/gtxyaaxbix.html

[M04] 获取当前工作目录
来源：http://dali.feifeiyinyue.top/Article/details/gtzajcfybv.html

Py:   os.getcwd()
来源：http://dali.snrcjt.cn/Article/details/gthbbpewls.html

PHP:  getcwd();
来源：http://dali.shzxlz.cn/Article/details/gtomxznaqt.html

JS:   process.cwd()
来源：http://dali.hysaishi.cn/Article/details/gtnbnfgkex.html

TS:   process.cwd()
来源：http://dali.ydzc1.top/Article/details/gtwzossdiz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.iojbl.cn/Article/details/gtpujtlgyj.html

Go:   os.Getwd()
来源：http://dali.yvedp.cn/Article/details/gtexygpchl.html

Ruby: Dir.pwd
来源：http://dali.kuanghao11.cn/Article/details/gtjqrzqyrk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xuanzx.com/Article/details/gtamfwwblq.html

[M05] 设置退出码
来源：http://dali.jlsjyb.cn/Article/details/gtcvmjztxg.html

Py:   sys.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtcizmdndp.html

PHP:  exit(1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtglisdcyi.html

JS:   process.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gtbusfvksa.html

TS:   process.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtssxqlndu.html

Java: System.exit(1)
来源：http://dali.cheryme.top/Article/details/gtelolmtlh.html

Go:   os.Exit(1)
来源：http://dali.316326.xyz/Article/details/gtiepgpxnz.html

Ruby: exit 1
来源：http://dali.yueranfly.top/Article/details/gttqfnswqb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sysykeji.top/Article/details/gtuozkmmkv.html

[M06] 向标准错误输出
来源：http://dali.jqgfzy.top/Article/details/gtoidepdfm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.quarkkingdee.top/Article/details/gtztwemkky.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.mhx1999.top/Article/details/gtdeupjfso.html

JS:   console.error("err")
来源：http://dali.tanke756.top/Article/details/gttrqwozgz.html

TS:   console.error("err")
来源：http://dali.svipenyu.cn/Article/details/gtfnkobjny.html

Java: System.err.println("err")
来源：http://dali.gogol.net.cn/Article/details/gtnsmhkajh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yanxiufei.cn/Article/details/gtkzrwiato.html

Ruby: warn "err"
来源：http://dali.aibaodan.cn/Article/details/gtkwlpoiqo.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jlsjyb.cn/Article/details/gtesgtvpkd.html

[M07] 判断是否为主入口
来源：http://dali.sweek.top/Article/details/gtfqbiitvv.html

Py:   if __name__ == "__main__":
来源：http://dali.mhx1999.top/Article/details/gtffeokjuf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.aibaodan.cn/Article/details/gtjotpvzie.html

JS:   require.main === module
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgravntlo.html

TS:   require.main === module
来源：http://dali.xuetiantiany.cn/Article/details/gtgzxlrcgj.html

Java: public static void main(String[] args)
来源：http://dali.cucudq.cn/Article/details/gtpdhxkwjk.html

Go:   func main()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdnksquxt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shanyushiyangtech.top/Article/details/gtsnvmgqkv.html

C#:   static void Main(string[] args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzrxmjonr.html

[M08] 获取系统与运行时信息
来源：http://dali.jlsjyb.cn/Article/details/gttczdauhe.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ehwqpu.com/Article/details/gtmxcrqtye.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.svipenyu.cn/Article/details/gtpwwbnndu.html

JS:   process.platform;  process.version
来源：http://dali.vqdsnc.cn/Article/details/gtgrvpitpu.html

TS:   process.platform;  process.version
来源：http://dali.xuanzx.com/Article/details/gtzyalqmre.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cqqwz.cn/Article/details/gtdlakabnv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.fzhhl.top/Article/details/gtiwyujxoq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jqgufenzy.top/Article/details/gtfmdnyxvv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.daria6918.cn/Article/details/gtttnhhwnx.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtpmvpolgy.html

N. 数据结构与算法
来源：http://dali.yangfankeji.com/Article/details/gthnvcthkd.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtxgxncqyf.html

[N01] 二分查找（有序数组）
来源：http://dali.nanxinkj.top/Article/details/gtrowgnjml.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtazhpuzpc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinghuilouyu.cn/Article/details/gtnjzcbdib.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sxryk.cn/Article/details/gtrqwwjgll.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjicdjjnj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtpyuoagyx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtzruhqjpq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfqplhnen.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtplgyfono.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shuidangran.top/Article/details/gttqdrarzm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwjkikgtc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gteeauyvyc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhixingplan.top/Article/details/gtmbyqdjjr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenjidiqi.icu/Article/details/gtqrlimatx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthogaywlc.html

Go:   slices.Sort(arr)
来源：http://dali.yongpay.top/Article/details/gtplgtrsat.html

Ruby: arr.sort
来源：http://dali.yuxming.cn/Article/details/gtfhivnsox.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yangfankeji.com/Article/details/gtytchcxqa.html

[N03] 快速排序（分治示例）
来源：http://dali.xinyue.icu/Article/details/gtwbxanher.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gzhubu.top/Article/details/gtuhwzzwbi.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xylfe.cn/Article/details/gtadiyvcla.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xylfe.cn/Article/details/gtyoejunlv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258.top/Article/details/gttexuoyzo.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xinyue.icu/Article/details/gtgcmwdtdf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.c1oappe.top/Article/details/gtfqugqyjl.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yj20258.top/Article/details/gtaxdsoukm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.vqdsnc.cn/Article/details/gtgtkzbzsw.html

[N04] 斐波那契数列
来源：http://dali.sxryk.cn/Article/details/gtfnuvlqor.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.smart0.xyz/Article/details/gtzjewrooy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtryvhewnp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhongyouzk.top/Article/details/gtyuozvrgn.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fengsongda.top/Article/details/gtcaelsxtg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shuidangran.top/Article/details/gtnnqigyaf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hfpthk.cn/Article/details/gtvspxwzvx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hysaishi.cn/Article/details/gtesylsgqu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.gotoacloud.top/Article/details/gtduxvgmjc.html

[N05] 最大公约数
来源：http://dali.meibo888.top/Article/details/gtuhstatkw.html

Py:   math.gcd(a, b)
来源：http://dali.fzhhl.top/Article/details/gtkkuvmhvs.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gaohongyu789.top/Article/details/gtedrhirvc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cqqwz.cn/Article/details/gtlxvhlkfe.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnqzz.top/Article/details/gtqvqjpnqa.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.wangshuangyany.cn/Article/details/gtvzlswtoj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.smart0.xyz/Article/details/gtbdxuasne.html

Ruby: a.gcd(b)
来源：http://dali.yj20258.top/Article/details/gtyshvxteh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sweek.top/Article/details/gtbsnyhzxo.html

[N06] 判断回文字符串
来源：http://dali.hammf.cn/Article/details/gtapzzhusn.html

Py:   s == s[::-1]
来源：http://dali.yuxming.cn/Article/details/gtvovhreid.html

PHP:  $s === strrev($s);
来源：http://dali.jiagoushi.top/Article/details/gtelceglmg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gtmrogmbcv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gtohqbqsgw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.wangshuangyany.cn/Article/details/gtzmmwevzt.html

Go:   // 双指针从两端比较
来源：http://dali.ydzc1.top/Article/details/gtgtjtstza.html

Ruby: s == s.reverse
来源：http://dali.jyoumei.cn/Article/details/gthodlsmex.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.bjfxy.top/Article/details/gtvhzxditp.html

[N07] 两数之和（返回下标）
来源：http://dali.daria6918.cn/Article/details/gtjtcecfol.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cqqwz.cn/Article/details/gtbtzjqssw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.316326.xyz/Article/details/gtfemfvavw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.chenzaomai.com/Article/details/gtwdugfcnj.html

TS:   // 手写 Map<string, number>
来源：http://dali.jlsjyb.cn/Article/details/gtsztmtjoc.html

Java: // 手写 HashMap
来源：http://dali.xuanzx.com/Article/details/gtytcvrdha.html

Go:   // 手写 map[int]int
来源：http://dali.iojbl.cn/Article/details/gtndblyawy.html

Ruby: // 手写 Hash
来源：http://dali.fengsongda.top/Article/details/gthaasbkpl.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gogol.net.cn/Article/details/gtbgdrlvyl.html

[N08] 生成全排列
来源：http://dali.zycfv.cn/Article/details/gtiegirzrt.html

Py:   itertools.permutations(arr)
来源：http://dali.zdqjudy.top/Article/details/gtyyzwdwbb.html

PHP:  // 手写递归交换
来源：http://dali.ehwqpu.com/Article/details/gtobtdkper.html

JS:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gtcjtsedtz.html

TS:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtlgrsjjax.html

Java: // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gtzsjonsfu.html

Go:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtforfogst.html

Ruby: arr.permutation.to_a
来源：http://dali.cashguo.top/Article/details/gtpokacsoo.html

C#:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtelybwzuc.html

[N09] 栈与队列
来源：http://dali.zdqjudy.top/Article/details/gtolekonke.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xinyue.icu/Article/details/gtmsfogywk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.meibo888.top/Article/details/gtsvzplqdd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shuidangran.top/Article/details/gtwllobowf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ybcxt.top/Article/details/gtmxwhwpmw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.nanxinkj.top/Article/details/gtjmyqwznn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hnxiangtu.top/Article/details/gtogpxfhor.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.chenlongwang.top/Article/details/gteftlqysa.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.aizwys.cn/Article/details/gttuzszfeq.html

[N10] 链表节点定义
来源：http://dali.ppjwa.cn/Article/details/gtpgluxltv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gogol.net.cn/Article/details/gtyjnlucxf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xinyue.icu/Article/details/gtkvgoszqz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gtkxexytas.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zycfv.cn/Article/details/gtppdlumet.html

Java: class Node { int v; Node next; }
来源：http://dali.cucudq.cn/Article/details/gteikahgtv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.smart0.xyz/Article/details/gtjracekkd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cdnleiting.top/Article/details/gtvizvhowi.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yj20258888.top/Article/details/gtzqxfdqsx.html

[N11] 二叉树中序遍历
来源：http://dali.tianlin.xyz/Article/details/gtuhlhxwic.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhongyouzk.top/Article/details/gtwaqhxzef.html

PHP:  // 手写递归函数
来源：http://dali.zhixingplan.top/Article/details/gtypvsnkqw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gotoacloud.top/Article/details/gtufgnfvab.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ydzc1.top/Article/details/gthwqypxcf.html

Java: // 手写递归
来源：http://dali.jiagoushi.top/Article/details/gttdrxdwzu.html

Go:   // 手写递归
来源：http://dali.tianlin.xyz/Article/details/gtamfjupgy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.svipenyu.cn/Article/details/gtovudtyox.html

C#:   // 手写递归
来源：http://dali.yj20258888.top/Article/details/gtkzgdugnc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jqgufenzy.top/Article/details/gttmrxjbdl.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.meibo888.top/Article/details/gtezfxsndg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.dashuyun.cn/Article/details/gtjvwhcrlz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jiagoushi.top/Article/details/gtheogfvnd.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.316326.xyz/Article/details/gtooezspoh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.birdmap.top/Article/details/gtympgxyvp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.gzhubu.top/Article/details/gtldhiscol.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinghuilouyu.cn/Article/details/gturxohcqk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hnqzz.top/Article/details/gtpvitnuaw.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtiqyuceme.html

O. 并发与异步
来源：http://dali.yvedp.cn/Article/details/gtmdlzhvyn.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtyqvblunj.html

[O01] 启动一个线程
来源：http://dali.meibo888.top/Article/details/gtivxjhuth.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.fengsongda.top/Article/details/gtvjtkgmrq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ybcxt.top/Article/details/gtadkbktms.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xuanzx.com/Article/details/gtzjsyllgd.html

TS:   // 同 JS
来源：http://dali.mhx1999.top/Article/details/gttfwglsjs.html

Java: new Thread(() -> f()).start()
来源：http://dali.vqdsnc.cn/Article/details/gtpoubawtg.html

Go:   go f()
来源：http://dali.gogol.net.cn/Article/details/gthcxibltz.html

Ruby: Thread.new { f }
来源：http://dali.dianchejie.cn/Article/details/gtyrdtxxly.html

C#:   Task.Run(() => F());
来源：http://dali.tanke756.top/Article/details/gtnndfiawe.html

[O02] 使用线程池
来源：http://dali.svipenyu.cn/Article/details/gtroplutpv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gttxdxrapx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.svipenyu.cn/Article/details/gtnrvqblax.html

JS:   // worker_threads 线程池
来源：http://dali.yonumen.top/Article/details/gtwpnjffjl.html

TS:   // worker_threads 线程池
来源：http://dali.jqgufenzy.top/Article/details/gtbsepbqfv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yuxming.cn/Article/details/gtblckqwjo.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hnxiangtu.top/Article/details/gtcteenczm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcbwwbdvx.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.chenjidiqi.icu/Article/details/gtuuxzdkci.html

[O03] 加锁保护共享数据
来源：http://dali.jlsjyb.cn/Article/details/gtabawyjpp.html

Py:   with lock: shared += 1
来源：http://dali.xuetiantiany.cn/Article/details/gtztoewbyb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.9152youxi.cn/Article/details/gtxhmopkvl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xylfe.cn/Article/details/gtkcxquqol.html

TS:   // 同 JS
来源：http://dali.xuanzx.com/Article/details/gtxpovuxis.html

Java: synchronized (this) { shared++; }
来源：http://dali.jlsjyb.cn/Article/details/gtlwnzfpah.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.snrcjt.cn/Article/details/gtldzyxvsq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.aibaodan.cn/Article/details/gtwipaqner.html

C#:   lock (gate) { shared++; }
来源：http://dali.havefunace.top/Article/details/gtqxqsinmh.html

[O04] 定义异步函数并等待
来源：http://dali.yj20258.top/Article/details/gtwgkaqijf.html

Py:   async def f():⏎    await g()
来源：http://dali.hnxiangtu.top/Article/details/gtaivkgxcl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xziqi.cn/Article/details/gtrxgilcdh.html

JS:   async function f() { await g(); }
来源：http://dali.haohaochexian.top/Article/details/gtqsjrgldg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenlongwang.top/Article/details/gtomqjsxqo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinqigufen.top/Article/details/gtsalgpwtv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinyuanbaomall.cn/Article/details/gtduxfywsa.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.feifeiyinyue.top/Article/details/gtekdzjbpk.html

C#:   async Task F() { await G(); }
来源：http://dali.zhongyouzk.top/Article/details/gtbhondlyi.html

[O05] 并发执行并等待全部完成
来源：http://dali.sweek.top/Article/details/gtezikiyzu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.feifeiyinyue.top/Article/details/gtgdpezhpw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hfpthk.cn/Article/details/gtxtkfjgfz.html

JS:   await Promise.all(tasks)
来源：http://dali.yangfankeji.com/Article/details/gtwhnentcl.html

TS:   await Promise.all(tasks)
来源：http://dali.yj20258888.top/Article/details/gtqnsnacja.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xziqi.cn/Article/details/gtoigyzdik.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yonumen.top/Article/details/gtqdecikmt.html

Ruby: threads.map(&:join)
来源：http://dali.nanxuanxn.top/Article/details/gtlpfwypfg.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sufxvd.cn/Article/details/gtencgqtxp.html

[O06] 使用进程池
来源：http://dali.ehwqpu.com/Article/details/gtjnqiagdh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yj202588.top/Article/details/gtndmobcen.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtstdqorre.html

JS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxeqhjuul.html

TS:   // child_process / cluster 模块
来源：http://dali.daria6918.cn/Article/details/gtfcqzucyk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkwmcfkrt.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jqgufenzy.top/Article/details/gthhqlxamy.html

Ruby: // fork 块
来源：http://dali.chenlongwang.top/Article/details/gtvddzwcdl.html

C#:   Parallel.For
来源：http://dali.xuanzx.com/Article/details/gtzkmaqopb.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtdslufdft.html

P. 常用工具函数
来源：http://dali.xziqi.cn/Article/details/gtlxvbbaht.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtmxfeaohz.html

[P01] 生成 UUID
来源：http://dali.fzhhl.top/Article/details/gtnfflxnwy.html

Py:   str(uuid.uuid4())
来源：http://dali.yangfankeji.com/Article/details/gtwsifuiyh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.pycfn.com/Article/details/gtfgbeubid.html

JS:   crypto.randomUUID()
来源：http://dali.kuanghao11.cn/Article/details/gtllquqlol.html

TS:   crypto.randomUUID()
来源：http://dali.hnqzz.top/Article/details/gteprqlaqt.html

Java: UUID.randomUUID().toString()
来源：http://dali.jyoumei.cn/Article/details/gticztnoxn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.9152youxi.cn/Article/details/gtmjxvqpxp.html

Ruby: SecureRandom.uuid
来源：http://dali.feifeiyinyue.top/Article/details/gtslsmoyfq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hnxiangtu.top/Article/details/gtqtyskkjw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jiagoushi.top/Article/details/gtfohljryh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yueranfly.top/Article/details/gtwcnuttub.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.wangdashe.top/Article/details/gtkgezouly.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrcbvjaub.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zdqjudy.top/Article/details/gtbgydyzgs.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvtkeiuux.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuabmvcvq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nanxuanxn.top/Article/details/gtfyjbogww.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhiwuduotai.top/Article/details/gtwprhbyqa.html

[P03] 生成短随机字符串
来源：http://dali.tian-w.cn/Article/details/gtfuxsiahv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.bjfxy.top/Article/details/gtuzxeexbe.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.iojbl.cn/Article/details/gtbkighxfy.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.svipenyu.cn/Article/details/gtcagftkmi.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.mhx1999.top/Article/details/gttuzymmct.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.aibaodan.cn/Article/details/gtphzqewio.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hysaishi.cn/Article/details/gtdvzauyqj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ydzc1.top/Article/details/gtooablylc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.andypj.xyz/Article/details/gtjljuwnuf.html

[P04] 求长度
来源：http://dali.shangyingyoupin.top/Article/details/gtuettfmtb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.kuanghao11.cn/Article/details/gtxvjdslyg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gteglfpdiv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinghuilouyu.cn/Article/details/gtxqxhccmg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xuanzx.com/Article/details/gtwswphvyx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ehwqpu.com/Article/details/gtlhmfkuus.html

Go:   len(arr);  len(m)
来源：http://dali.gzhubu.top/Article/details/gtcytdjuty.html

Ruby: x.length;  x.size
来源：http://dali.wangdashe.top/Article/details/gtxkbgavvl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ybcxt.top/Article/details/gtpkmwbbth.html

[P05] 判断两个对象内容是否相等
来源：http://dali.nanxuanxn.top/Article/details/gtwvmcftdv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gtljffbepj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhoulong.xyz/Article/details/gtbtgrbfgv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjptqirpr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ehwqpu.com/Article/details/gtbeacsvwg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xinyue.icu/Article/details/gtzoqygkvw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jiagoushi.top/Article/details/gtenepqgoq.html

Ruby: a == b
来源：http://dali.yanxiufei.cn/Article/details/gtqyymlmif.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.dashuyun.cn/Article/details/gtzkkjnwqo.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.aizwys.cn/Article/details/gtdirbccym.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.9152youxi.cn/Article/details/gtxkztlcji.html

PHP:  if (empty($x)) {}
来源：http://dali.wangdashe.top/Article/details/gtpflepzmc.html


<!-- 参考信息 -->