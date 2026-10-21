代发 wailian999

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinqigufen.top/Article/details/gtplxiuptk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gtpptdhjln.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtkoiqwsop.html

M. 命令行 / 进程 / 环境
来源：http://dali.jqgfzy.top/Article/details/gtcrjblucg.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtfwxjzpmb.html

[M01] 读取命令行参数
来源：http://dali.xuanzx.com/Article/details/gtnqotpdsn.html

Py:   sys.argv[1:]
来源：http://dali.quarkkingdee.top/Article/details/gtunfzheoo.html

PHP:  $argv;  $argc;
来源：http://dali.ppjwa.cn/Article/details/gtokvnjdez.html

JS:   process.argv.slice(2)
来源：http://dali.cheryme.top/Article/details/gtlpxsagib.html

TS:   process.argv.slice(2)
来源：http://dali.zhengqikj.top/Article/details/gthxeefklm.html

Java: args 数组（main 方法参数）
来源：http://dali.yongpay.top/Article/details/gtgujbravm.html

Go:   os.Args[1:]
来源：http://dali.hysaishi.cn/Article/details/gtrujkyazk.html

Ruby: ARGV
来源：http://dali.hysaishi.cn/Article/details/gtobuuovcx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.nwbrower.top/Article/details/gtqdvdzrzf.html

[M02] 读取环境变量
来源：http://dali.snrcjt.cn/Article/details/gtvxslqdam.html

Py:   os.environ.get("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gtuplwoudn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfzrphmre.html

JS:   process.env.HOME
来源：http://dali.hysaishi.cn/Article/details/gtohqzczrp.html

TS:   process.env.HOME
来源：http://dali.hongshengwenyu.top/Article/details/gtifojvgjg.html

Java: System.getenv("HOME")
来源：http://dali.tian-w.cn/Article/details/gtyjyhrgdm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shuidangran.top/Article/details/gtbidmbnbe.html

Ruby: ENV["HOME"]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxxqaqgic.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.meibo888.top/Article/details/gtmsdkftci.html

[M03] 执行外部命令
来源：http://dali.daxiang520.top/Article/details/gtomdkvekz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.316326.xyz/Article/details/gtdarxhgie.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hongshengwenyu.top/Article/details/gtpmruzqrr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.kuanghao11.cn/Article/details/gtvfxcsjsj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.aibaodan.cn/Article/details/gtitgxheaf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.bjfxy.top/Article/details/gtaxcvomiy.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yanxiufei.cn/Article/details/gtlgerxnjq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cashguo.top/Article/details/gthnljzjpm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cucudq.cn/Article/details/gtabpmcvil.html

[M04] 获取当前工作目录
来源：http://dali.yongpay.top/Article/details/gtvwqjokpz.html

Py:   os.getcwd()
来源：http://dali.yonumen.top/Article/details/gtkrnmezgu.html

PHP:  getcwd();
来源：http://dali.cdnleiting.top/Article/details/gtatlqivhw.html

JS:   process.cwd()
来源：http://dali.c1oappe.top/Article/details/gtbkejewre.html

TS:   process.cwd()
来源：http://dali.haohaochexian.top/Article/details/gtddxpondy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.nanxuanxn.top/Article/details/gtcwruknif.html

Go:   os.Getwd()
来源：http://dali.ivvv.top/Article/details/gtewxjjmfh.html

Ruby: Dir.pwd
来源：http://dali.ppjwa.cn/Article/details/gttpkkqyzx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.iojbl.cn/Article/details/gtccmxkelg.html

[M05] 设置退出码
来源：http://dali.ybcxt.top/Article/details/gtqbjinjsd.html

Py:   sys.exit(1)
来源：http://dali.andypj.xyz/Article/details/gtokroobri.html

PHP:  exit(1);
来源：http://dali.fengsongda.top/Article/details/gtvteadhuv.html

JS:   process.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gtwktzhzpv.html

TS:   process.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtwqxbigqn.html

Java: System.exit(1)
来源：http://dali.aizwys.cn/Article/details/gtemalnwtm.html

Go:   os.Exit(1)
来源：http://dali.daxiang520.top/Article/details/gtrreoyapx.html

Ruby: exit 1
来源：http://dali.gogol.net.cn/Article/details/gtjiaazqln.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.smart0.xyz/Article/details/gteieqxtfs.html

[M06] 向标准错误输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlqkgmkbo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.havefunace.top/Article/details/gttmusafhc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yuanzhike.top/Article/details/gtfldzkvym.html

JS:   console.error("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfrwuuney.html

TS:   console.error("err")
来源：http://dali.c1oappe.top/Article/details/gtsncdzdpy.html

Java: System.err.println("err")
来源：http://dali.shangyingyoupin.top/Article/details/gtqmufxcvk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.iojbl.cn/Article/details/gtqvvpazdo.html

Ruby: warn "err"
来源：http://dali.9152youxi.cn/Article/details/gtjygbptcq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.guowangkeji.top/Article/details/gtoupzlwsa.html

[M07] 判断是否为主入口
来源：http://dali.wangshuangyany.cn/Article/details/gtcuonirsl.html

Py:   if __name__ == "__main__":
来源：http://dali.ybcxt.top/Article/details/gtnfhojhjk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yanxiufei.cn/Article/details/gtgopvgqdr.html

JS:   require.main === module
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuzrllnkv.html

TS:   require.main === module
来源：http://dali.hfpthk.cn/Article/details/gtlvysdzhn.html

Java: public static void main(String[] args)
来源：http://dali.mhx1999.top/Article/details/gtaalhlyop.html

Go:   func main()
来源：http://dali.jyoumei.cn/Article/details/gtigbqnixh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jyoumei.cn/Article/details/gtfsqfotck.html

C#:   static void Main(string[] args)
来源：http://dali.yuxming.cn/Article/details/gtdkspkavl.html

[M08] 获取系统与运行时信息
来源：http://dali.zdqjudy.top/Article/details/gtngjbmhbr.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ehwqpu.com/Article/details/gtujxersbz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zdqjudy.top/Article/details/gtshcaplzm.html

JS:   process.platform;  process.version
来源：http://dali.cqqwz.cn/Article/details/gtipypvkkj.html

TS:   process.platform;  process.version
来源：http://dali.jinqigfzy.top/Article/details/gtujfqinkk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnxiangtu.top/Article/details/gtftzugmxb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yvedp.cn/Article/details/gtmfcyafqk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cheryme.top/Article/details/gtabfwjgjm.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.guannengcc.top/Article/details/gttzeaxkwv.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtrgpoucps.html

N. 数据结构与算法
来源：http://dali.xylfe.cn/Article/details/gtykpstqst.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtioleglvp.html

[N01] 二分查找（有序数组）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtodpvrlaf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtgmdwsqaw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinqigfzy.top/Article/details/gttvosdbor.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ybcxt.top/Article/details/gtcwbgfepv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gtpdglymcs.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtmrlqonge.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtlhitjgol.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hywenlv.cn/Article/details/gtljtexjxj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gtjirwdnrj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jyoumei.cn/Article/details/gtkbevrysm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.iojbl.cn/Article/details/gtkcridtrp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yonumen.top/Article/details/gtvyndnmyd.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenjidiqi.icu/Article/details/gtlboadhbw.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yongpay.top/Article/details/gtjkuiqsbz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.wangshuangyany.cn/Article/details/gtgkdgznzg.html

Go:   slices.Sort(arr)
来源：http://dali.fengsongda.top/Article/details/gtwdediqtl.html

Ruby: arr.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpsaaknuy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hysaishi.cn/Article/details/gtaywvmoql.html

[N03] 快速排序（分治示例）
来源：http://dali.shanyushiyangtech.top/Article/details/gtytrfwqrs.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhoulong.xyz/Article/details/gtbzvgrets.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hammf.cn/Article/details/gtgmymtbfj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xylfe.cn/Article/details/gtvkzdpzqs.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.9152youxi.cn/Article/details/gtbgmekggi.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhongyouzk.top/Article/details/gtahdbqqhp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hywenlv.cn/Article/details/gthlynburn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.svipenyu.cn/Article/details/gtygrroliu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwezkqvel.html

[N04] 斐波那契数列
来源：http://dali.yuxming.cn/Article/details/gtcqjsxgcd.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yuxming.cn/Article/details/gtafzvpbyw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.feifeiyinyue.top/Article/details/gtotptauob.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj202588.top/Article/details/gtxsjwberc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fengsongda.top/Article/details/gtiziasjjh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yuanzhike.top/Article/details/gtxtfihpbm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xuanzx.com/Article/details/gtmvanypqa.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xziqi.cn/Article/details/gtjkzzihrt.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hnqzz.top/Article/details/gtgfvvzrjo.html

[N05] 最大公约数
来源：http://dali.zhixingplan.top/Article/details/gtryfhbcfg.html

Py:   math.gcd(a, b)
来源：http://dali.mhx1999.top/Article/details/gtyzykjpjs.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.havefunace.top/Article/details/gtibvswqpk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yvedp.cn/Article/details/gtpqdnykaj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cashguo.top/Article/details/gtwlxiovxr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sweek.top/Article/details/gtgyaczoiz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.quarkkingdee.top/Article/details/gtobunxstb.html

Ruby: a.gcd(b)
来源：http://dali.hywenlv.cn/Article/details/gtlgfbilvs.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpvuofuzu.html

[N06] 判断回文字符串
来源：http://dali.gzhubu.top/Article/details/gtszlgcdlm.html

Py:   s == s[::-1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtihvarcie.html

PHP:  $s === strrev($s);
来源：http://dali.tianlin.xyz/Article/details/gtfeqltczm.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gtxdifuqvs.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ydzc1.top/Article/details/gtwzvbepoy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cdnleiting.top/Article/details/gtmohkjpnb.html

Go:   // 双指针从两端比较
来源：http://dali.chenzaomai.com/Article/details/gtgdihrwgd.html

Ruby: s == s.reverse
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzxttpujw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xuetiantiany.cn/Article/details/gtsvdpkizr.html

[N07] 两数之和（返回下标）
来源：http://dali.pengpengdd.cyou/Article/details/gtpqxpodrv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.9152youxi.cn/Article/details/gthsywgotf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ivvv.top/Article/details/gtfqbuvfit.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhoulong.xyz/Article/details/gtbpwvoorb.html

TS:   // 手写 Map<string, number>
来源：http://dali.pengpengdd.cyou/Article/details/gtlabtnayl.html

Java: // 手写 HashMap
来源：http://dali.yanxiufei.cn/Article/details/gtvgipvesm.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gtwzcikmth.html

Ruby: // 手写 Hash
来源：http://dali.havefunace.top/Article/details/gtvlxcpgih.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sxryk.cn/Article/details/gtnzanhguz.html

[N08] 生成全排列
来源：http://dali.jiagoushi.top/Article/details/gtpdmaovir.html

Py:   itertools.permutations(arr)
来源：http://dali.fengsongda.top/Article/details/gtlrfzwizc.html

PHP:  // 手写递归交换
来源：http://dali.jlsjyb.cn/Article/details/gtrkqegfxe.html

JS:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtjhfaclur.html

TS:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtapzyclel.html

Java: // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gtqaixgsop.html

Go:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbgpbzklt.html

Ruby: arr.permutation.to_a
来源：http://dali.xinyue.icu/Article/details/gtqonwlobv.html

C#:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gtziqxdvnd.html

[N09] 栈与队列
来源：http://dali.vqdsnc.cn/Article/details/gtrcwsppta.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhixingplan.top/Article/details/gtilkpiwuk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.mhx1999.top/Article/details/gtulcjpnvn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yangfankeji.com/Article/details/gtsgtxrzzh.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.smart0.xyz/Article/details/gtowulmhbn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.dianchejie.cn/Article/details/gtjvbhtpmf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ivvv.top/Article/details/gthydgbufv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.kuanghao11.cn/Article/details/gthpxdzktk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jiagoushi.top/Article/details/gtrnqlkgxg.html

[N10] 链表节点定义
来源：http://dali.xuanzx.com/Article/details/gtcgyfeonq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tian-w.cn/Article/details/gtrndfdpih.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jlsjyb.cn/Article/details/gteeddawfk.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinqigufen.top/Article/details/gtwdvyeptj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hysaishi.cn/Article/details/gtyeolgkaz.html

Java: class Node { int v; Node next; }
来源：http://dali.hammf.cn/Article/details/gtdkliecte.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shzxlz.cn/Article/details/gtcnvgedyh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.chenjidiqi.icu/Article/details/gtjdxjlbyo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.pengpengdd.cyou/Article/details/gtwygwmcqw.html

[N11] 二叉树中序遍历
来源：http://dali.9152youxi.cn/Article/details/gtztqsfame.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzilgcthp.html

PHP:  // 手写递归函数
来源：http://dali.zhongyouzk.top/Article/details/gtrbkikwue.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsujuqwtj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.svipenyu.cn/Article/details/gtvvqpkxmt.html

Java: // 手写递归
来源：http://dali.feifeiyinyue.top/Article/details/gtxztnxvpq.html

Go:   // 手写递归
来源：http://dali.redwolf501.top/Article/details/gthnknqxps.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sysykeji.top/Article/details/gtnkfmxhtc.html

C#:   // 手写递归
来源：http://dali.zycfv.cn/Article/details/gtnuctpjcq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.vqdsnc.cn/Article/details/gtbetuesch.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shangyingyoupin.top/Article/details/gttnieheue.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.c1oappe.top/Article/details/gtzigzvemp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yanxiufei.cn/Article/details/gtncgivwps.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daxiang520.top/Article/details/gtyfxvxxrz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gogol.net.cn/Article/details/gtbufolgwg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shangyingyoupin.top/Article/details/gtitwzftnn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sweek.top/Article/details/gtzwfrvhss.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daxiang520.top/Article/details/gtghuzwsql.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtugjzvrqk.html

O. 并发与异步
来源：http://dali.yuanzhike.top/Article/details/gtzkdunxmp.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtjnacduoq.html

[O01] 启动一个线程
来源：http://dali.dashuyun.cn/Article/details/gteghsaxur.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xuanzx.com/Article/details/gtidokshcw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yj20258.top/Article/details/gtcuzbjtbi.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.tanke756.top/Article/details/gtvjavlnkg.html

TS:   // 同 JS
来源：http://dali.daxiang520.top/Article/details/gtgvokbfai.html

Java: new Thread(() -> f()).start()
来源：http://dali.sysykeji.top/Article/details/gttofpjcwp.html

Go:   go f()
来源：http://dali.hongshengwenyu.top/Article/details/gtrduabcsr.html

Ruby: Thread.new { f }
来源：http://dali.xylfe.cn/Article/details/gtrdgltguq.html

C#:   Task.Run(() => F());
来源：http://dali.ehwqpu.com/Article/details/gtftheyxcr.html

[O02] 使用线程池
来源：http://dali.tanke756.top/Article/details/gtjsvxmlad.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.daria6918.cn/Article/details/gtlhzgxexc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuwmlqpmv.html

JS:   // worker_threads 线程池
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuhignxjq.html

TS:   // worker_threads 线程池
来源：http://dali.quarkkingdee.top/Article/details/gtrndowjfl.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yueranfly.top/Article/details/gtczmrgyee.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ehwqpu.com/Article/details/gtkvdtvakd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xylfe.cn/Article/details/gtkwycvpqo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.daria6918.cn/Article/details/gtgarsjuck.html

[O03] 加锁保护共享数据
来源：http://dali.cucudq.cn/Article/details/gtuynydpfv.html

Py:   with lock: shared += 1
来源：http://dali.redwolf501.top/Article/details/gtabigjavf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sweek.top/Article/details/gtlysnrtll.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gaohongyu789.top/Article/details/gtuvfowxaq.html

TS:   // 同 JS
来源：http://dali.jinghuilouyu.cn/Article/details/gtxszkppxt.html

Java: synchronized (this) { shared++; }
来源：http://dali.yangfankeji.com/Article/details/gteomccday.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.fengsongda.top/Article/details/gtgakgyinv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.svipenyu.cn/Article/details/gtvghqelkd.html

C#:   lock (gate) { shared++; }
来源：http://dali.tianlin.xyz/Article/details/gtwsknzvvf.html

[O04] 定义异步函数并等待
来源：http://dali.smart0.xyz/Article/details/gteveoayqo.html

Py:   async def f():⏎    await g()
来源：http://dali.zhixingplan.top/Article/details/gtdgvguxmu.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.chenzaomai.com/Article/details/gtsphahmok.html

JS:   async function f() { await g(); }
来源：http://dali.fengsongda.top/Article/details/gtlpflynie.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj20258888.top/Article/details/gtvhveqeie.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhengqikj.top/Article/details/gtegdbyqig.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hongshengwenyu.top/Article/details/gtfphkwetq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.svipenyu.cn/Article/details/gthnqyzglk.html

C#:   async Task F() { await G(); }
来源：http://dali.pycfn.com/Article/details/gtqjogjqzj.html

[O05] 并发执行并等待全部完成
来源：http://dali.xziqi.cn/Article/details/gtlyehbcrk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ybcxt.top/Article/details/gthwcovuyn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrnxuasew.html

JS:   await Promise.all(tasks)
来源：http://dali.9152youxi.cn/Article/details/gtnyoavoec.html

TS:   await Promise.all(tasks)
来源：http://dali.aizwys.cn/Article/details/gtomjwvnog.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xziqi.cn/Article/details/gtkokdgspo.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hfpthk.cn/Article/details/gtzmozrnpm.html

Ruby: threads.map(&:join)
来源：http://dali.nwbrower.top/Article/details/gtrieususp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.fzhhl.top/Article/details/gtykppeztd.html

[O06] 使用进程池
来源：http://dali.havefunace.top/Article/details/gtdlfmacgp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.quarkkingdee.top/Article/details/gtusemmvca.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jiagoushi.top/Article/details/gtjmjzgztz.html

JS:   // child_process / cluster 模块
来源：http://dali.tianlin.xyz/Article/details/gtzkwepknv.html

TS:   // child_process / cluster 模块
来源：http://dali.zhengqikj.top/Article/details/gthnwdlnvd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.meibo888.top/Article/details/gtdcvjdcxm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.mhx1999.top/Article/details/gtuzfonwci.html

Ruby: // fork 块
来源：http://dali.feifeiyinyue.top/Article/details/gtsivfhsoi.html

C#:   Parallel.For
来源：http://dali.yanxiufei.cn/Article/details/gtcobantvs.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtdijlalnt.html

P. 常用工具函数
来源：http://dali.daria6918.cn/Article/details/gtfdtzrrif.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtberguapc.html

[P01] 生成 UUID
来源：http://dali.jqgufenzy.top/Article/details/gtfsnvqmfz.html

Py:   str(uuid.uuid4())
来源：http://dali.jyoumei.cn/Article/details/gtgupaoyvr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.mhx1999.top/Article/details/gtumycaglf.html

JS:   crypto.randomUUID()
来源：http://dali.hnxiangtu.top/Article/details/gtatozdfdp.html

TS:   crypto.randomUUID()
来源：http://dali.jinqigfzy.top/Article/details/gttoifmgae.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtwtawmexa.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yj202588.top/Article/details/gtqgxbrvgz.html

Ruby: SecureRandom.uuid
来源：http://dali.aibaodan.cn/Article/details/gtxchrtbao.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.nanxinkj.top/Article/details/gtrlmzwphk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yj20258.top/Article/details/gtfmxyvkrh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hnqzz.top/Article/details/gtydwifvjk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtaeztrres.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jqgufenzy.top/Article/details/gtwwkgeune.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gzhubu.top/Article/details/gtspvakogn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.havefunace.top/Article/details/gtidtuqswn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hnqzz.top/Article/details/gtpippcrkj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.birdmap.top/Article/details/gtpegayimt.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xuetiantiany.cn/Article/details/gtxinnawpx.html

[P03] 生成短随机字符串
来源：http://dali.sweek.top/Article/details/gtrvzzkthk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhixingplan.top/Article/details/gtixaupdna.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.daria6918.cn/Article/details/gtkkgwyyxj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ivvv.top/Article/details/gtjzklemdr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sweek.top/Article/details/gtalwqoeow.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.tian-w.cn/Article/details/gtnqwomwfm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yvedp.cn/Article/details/gtyfzfxfwp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.havefunace.top/Article/details/gtbzfqtuyi.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jiagoushi.top/Article/details/gtsloaemel.html

[P04] 求长度
来源：http://dali.xinyue.icu/Article/details/gtumzbmyme.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.wangshuangyany.cn/Article/details/gtckpvpmhk.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gtcvuvfmxx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.iojbl.cn/Article/details/gtueaynmnx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.smart0.xyz/Article/details/gtghzsyvyq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.iojbl.cn/Article/details/gthwssfkit.html

Go:   len(arr);  len(m)
来源：http://dali.smart0.xyz/Article/details/gtkakcvedd.html

Ruby: x.length;  x.size
来源：http://dali.xuetiantiany.cn/Article/details/gtetnjcdlo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yueranfly.top/Article/details/gtltoumhrh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hongshengwenyu.top/Article/details/gtqzsuamrz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.mhx1999.top/Article/details/gtaeztignw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hammf.cn/Article/details/gtepsvbxta.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yvedp.cn/Article/details/gtwmfdnlqt.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjspfuiuc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hammf.cn/Article/details/gthzutdors.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.9152youxi.cn/Article/details/gtiykhsjxe.html

Ruby: a == b
来源：http://dali.ydzc1.top/Article/details/gttksdwjoa.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.nanxuanxn.top/Article/details/gtafddinhd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yueranfly.top/Article/details/gtfxhufepb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hongshengwenyu.top/Article/details/gtzroglfii.html

PHP:  if (empty($x)) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtnhklvqay.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jlsjyb.cn/Article/details/gtjfrtwnda.html

TS:   if (x == null) {}
来源：http://dali.ppjwa.cn/Article/details/gtxmzqweqq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinqigfzy.top/Article/details/gtxttwbltx.html

Go:   if x == nil {}
来源：http://dali.yvedp.cn/Article/details/gtomecjubx.html


<!-- 参考信息 -->