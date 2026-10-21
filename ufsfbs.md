代发 wailian999

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cqqwz.cn/Article/details/gtwbpngujs.html

JS:   process.env.HOME
来源：http://dali.yuanzhike.top/Article/details/gtxacqsswl.html

TS:   process.env.HOME
来源：http://dali.yj20258.top/Article/details/gtzwmbqxro.html

Java: System.getenv("HOME")
来源：http://dali.ybcxt.top/Article/details/gtmedjmhlu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yuxming.cn/Article/details/gtyiimsizh.html

Ruby: ENV["HOME"]
来源：http://dali.cheryme.top/Article/details/gtxngolquq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtwqgkbarf.html

[M03] 执行外部命令
来源：http://dali.ywan-chungtsiang.top/Article/details/gtilrfpgda.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.daria6918.cn/Article/details/gtgmhtmwgd.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xuanzx.com/Article/details/gtoxzmzymr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuanzx.com/Article/details/gtiqcgxaox.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258.top/Article/details/gtphldkhno.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jqgufenzy.top/Article/details/gtzvdtqqqv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jqgufenzy.top/Article/details/gtulexunpl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhongyouzk.top/Article/details/gtaelrtvns.html

C#:   Process.Start("ls", "-l");
来源：http://dali.316326.xyz/Article/details/gtqtblcxfq.html

[M04] 获取当前工作目录
来源：http://dali.nanxuanxn.top/Article/details/gtdsikmbit.html

Py:   os.getcwd()
来源：http://dali.yanxiufei.cn/Article/details/gtcvechrqa.html

PHP:  getcwd();
来源：http://dali.ppjwa.cn/Article/details/gtbjamgngo.html

JS:   process.cwd()
来源：http://dali.0kj1m.cn/Article/details/gtwlzrbcnq.html

TS:   process.cwd()
来源：http://dali.gotoacloud.top/Article/details/gtdwcfbeeg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.fengsongda.top/Article/details/gtiyjdgrxm.html

Go:   os.Getwd()
来源：http://dali.cucudq.cn/Article/details/gttbkmbbhs.html

Ruby: Dir.pwd
来源：http://dali.fengsongda.top/Article/details/gtlunmmnlj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.smart0.xyz/Article/details/gtmcmcnepi.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gttsxwgikb.html

Py:   sys.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaasoxmmm.html

PHP:  exit(1);
来源：http://dali.guowangkeji.top/Article/details/gtfzxykfiv.html

JS:   process.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtgcdjgtci.html

TS:   process.exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gtodbkihfp.html

Java: System.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gtfgoevbhr.html

Go:   os.Exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlycyshim.html

Ruby: exit 1
来源：http://dali.wangshuangyany.cn/Article/details/gtppbhoujr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zycfv.cn/Article/details/gtpqdwfpth.html

[M06] 向标准错误输出
来源：http://dali.zdqjudy.top/Article/details/gtheliwmuo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yuanzhike.top/Article/details/gtewgnzpsz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.316326.xyz/Article/details/gtkayfcqea.html

JS:   console.error("err")
来源：http://dali.jiagoushi.top/Article/details/gtuunfvdsg.html

TS:   console.error("err")
来源：http://dali.fzhhl.top/Article/details/gtmdsfxhhe.html

Java: System.err.println("err")
来源：http://dali.hnqzz.top/Article/details/gthifmxbhh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.redwolf501.top/Article/details/gtskffookk.html

Ruby: warn "err"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzuvgrbrq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.fzhhl.top/Article/details/gtbcsokzqw.html

[M07] 判断是否为主入口
来源：http://dali.nanxuanxn.top/Article/details/gtaezxsuly.html

Py:   if __name__ == "__main__":
来源：http://dali.jyoumei.cn/Article/details/gtowayhcbn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hnqzz.top/Article/details/gtfstmdxxt.html

JS:   require.main === module
来源：http://dali.gaohongyu789.top/Article/details/gtrixvwofa.html

TS:   require.main === module
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaojtuicy.html

Java: public static void main(String[] args)
来源：http://dali.ydzc1.top/Article/details/gtzewbhxrm.html

Go:   func main()
来源：http://dali.zhengqikj.top/Article/details/gtfiqmgpqz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.9152youxi.cn/Article/details/gtnoyuocrc.html

C#:   static void Main(string[] args)
来源：http://dali.guowangkeji.top/Article/details/gtiacvhtmq.html

[M08] 获取系统与运行时信息
来源：http://dali.gzhubu.top/Article/details/gtbimeektr.html

Py:   platform.system();  platform.python_version()
来源：http://dali.chenlongwang.top/Article/details/gtwezkviyc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.snrcjt.cn/Article/details/gtniymbzlc.html

JS:   process.platform;  process.version
来源：http://dali.bjfxy.top/Article/details/gtssfymyvl.html

TS:   process.platform;  process.version
来源：http://dali.jyoumei.cn/Article/details/gtgyutjjdz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnqzz.top/Article/details/gtobmwqhmb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.vqdsnc.cn/Article/details/gttkhcogsd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.pycfn.com/Article/details/gtsqiznltk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gtyzttfhdo.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gttnjjguhi.html

N. 数据结构与算法
来源：http://dali.guannengcc.top/Article/details/gtutzvlylz.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gttrehtubr.html

[N01] 二分查找（有序数组）
来源：http://dali.yuanzhike.top/Article/details/gtmkolbrvm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.meibo888.top/Article/details/gtknzipfdg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gtyzxcsnlu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.andypj.xyz/Article/details/gtmmrylbsy.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gttmkqppvz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtjlonjjsm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.iojbl.cn/Article/details/gtywiopozh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hammf.cn/Article/details/gtlfdgecem.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sweek.top/Article/details/gtozimslld.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.pengpengdd.cyou/Article/details/gtmlynhujh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pengpengdd.cyou/Article/details/gtjmpdcqxl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.tianlin.xyz/Article/details/gtyuwdfiia.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.0kj1m.cn/Article/details/gtceiustbg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gaohongyu789.top/Article/details/gtwqmfsmer.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.nwbrower.top/Article/details/gtudvutfjg.html

Go:   slices.Sort(arr)
来源：http://dali.xylfe.cn/Article/details/gtatmxflpj.html

Ruby: arr.sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcegjzepu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yvedp.cn/Article/details/gtsvpojtzb.html

[N03] 快速排序（分治示例）
来源：http://dali.hywenlv.cn/Article/details/gtxodwqtcc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.guannengcc.top/Article/details/gtjeogzhea.html

PHP:  // 递归实现，或用 usort
来源：http://dali.fzhhl.top/Article/details/gtgcsntcqf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aizwys.cn/Article/details/gtpnwlimxx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hongshengwenyu.top/Article/details/gtzsrzmbel.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jyoumei.cn/Article/details/gtlgihowjm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.dashuyun.cn/Article/details/gtzbnrnuao.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yangfankeji.com/Article/details/gtuehofbcb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sxryk.cn/Article/details/gtlycvxnnz.html

[N04] 斐波那契数列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqeawcccj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shzxlz.cn/Article/details/gtwibuzyim.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj202588.top/Article/details/gthwjnvrpq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jianghu66.top/Article/details/gtexbjzyne.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.haohaochexian.top/Article/details/gtoxjkvxnc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xuetiantiany.cn/Article/details/gtccrtsjbv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.havefunace.top/Article/details/gthjvvcqjz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xuanzx.com/Article/details/gtugwqvlus.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.kuanghao11.cn/Article/details/gtyirrlshb.html

[N05] 最大公约数
来源：http://dali.smart0.xyz/Article/details/gtpsxtlnwf.html

Py:   math.gcd(a, b)
来源：http://dali.jinqigfzy.top/Article/details/gtiaywscks.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yuxming.cn/Article/details/gtjfrmjwfi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yongpay.top/Article/details/gttgbwpanw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cashguo.top/Article/details/gtvqklneap.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yangfankeji.com/Article/details/gtceulhhcx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yueranfly.top/Article/details/gtehbvzmvk.html

Ruby: a.gcd(b)
来源：http://dali.xinyue.icu/Article/details/gtkhtkavtv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhengqikj.top/Article/details/gtfbweopjh.html

[N06] 判断回文字符串
来源：http://dali.chenzaomai.com/Article/details/gtdposxixn.html

Py:   s == s[::-1]
来源：http://dali.cqqwz.cn/Article/details/gteknbcgwj.html

PHP:  $s === strrev($s);
来源：http://dali.yj20258888.top/Article/details/gtiakuedsr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtlrehyibe.html

TS:   s === [...s].reverse().join("")
来源：http://dali.daxiang520.top/Article/details/gtdmmofhef.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jiagoushi.top/Article/details/gtdeeunupo.html

Go:   // 双指针从两端比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxslroczs.html

Ruby: s == s.reverse
来源：http://dali.sufxvd.cn/Article/details/gtvtsquqhh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.meibo888.top/Article/details/gtojqvmjrp.html

[N07] 两数之和（返回下标）
来源：http://dali.ehwqpu.com/Article/details/gtrbexmhip.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ivvv.top/Article/details/gtserkdpsf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.aizwys.cn/Article/details/gtakarueaj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shangyingyoupin.top/Article/details/gtgssdmcxk.html

TS:   // 手写 Map<string, number>
来源：http://dali.yanxiufei.cn/Article/details/gtdwbmtqvu.html

Java: // 手写 HashMap
来源：http://dali.zdqjudy.top/Article/details/gttfathuve.html

Go:   // 手写 map[int]int
来源：http://dali.9152youxi.cn/Article/details/gtwcedzdjc.html

Ruby: // 手写 Hash
来源：http://dali.cheryme.top/Article/details/gtwkawwzva.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.dianchejie.cn/Article/details/gtqbcumgkc.html

[N08] 生成全排列
来源：http://dali.nanxinkj.top/Article/details/gtfrphncxu.html

Py:   itertools.permutations(arr)
来源：http://dali.tianlin.xyz/Article/details/gttpuvujsz.html

PHP:  // 手写递归交换
来源：http://dali.wangshuangyany.cn/Article/details/gtykpmscnw.html

JS:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gtoaexprzr.html

TS:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gtnmneiowa.html

Java: // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gtcggmbrhq.html

Go:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gtwepkliie.html

Ruby: arr.permutation.to_a
来源：http://dali.tian-w.cn/Article/details/gtgpsldmqx.html

C#:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gtmejlkoyk.html

[N09] 栈与队列
来源：http://dali.yvedp.cn/Article/details/gtkihkcjac.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.bjfxy.top/Article/details/gtcfquguyi.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hnqzz.top/Article/details/gtvxatuwle.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ydzc1.top/Article/details/gtnanucbxq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yongpay.top/Article/details/gttffuwfji.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.dashuyun.cn/Article/details/gtofmtzvxy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhoulong.xyz/Article/details/gtcgaqceow.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhongyouzk.top/Article/details/gtuvqrtfxk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj20258888.top/Article/details/gteepoqxru.html

[N10] 链表节点定义
来源：http://dali.316326.xyz/Article/details/gtgindgpzy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.dashuyun.cn/Article/details/gtitzjyyxy.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ehwqpu.com/Article/details/gtcymyesyp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.feifeiyinyue.top/Article/details/gtkcaeutkm.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ydzc1.top/Article/details/gtwgyxwcbh.html

Java: class Node { int v; Node next; }
来源：http://dali.316326.xyz/Article/details/gtguymyajt.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.svipenyu.cn/Article/details/gtqrawunwe.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkuagydqo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tianlin.xyz/Article/details/gtfkqkfihc.html

[N11] 二叉树中序遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtpzfdoeqt.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sysykeji.top/Article/details/gtqeompelh.html

PHP:  // 手写递归函数
来源：http://dali.shangyingyoupin.top/Article/details/gtszasfgxi.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sufxvd.cn/Article/details/gthtxsdjpo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yvedp.cn/Article/details/gtntxxewdk.html

Java: // 手写递归
来源：http://dali.sysykeji.top/Article/details/gtnnpgoufc.html

Go:   // 手写递归
来源：http://dali.chenlongwang.top/Article/details/gtltyhfxct.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hywenlv.cn/Article/details/gtonpfappt.html

C#:   // 手写递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtzskqpciz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.pengpengdd.cyou/Article/details/gtpfkchvvz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtngfswlws.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhixingplan.top/Article/details/gtprdoojqo.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenjidiqi.icu/Article/details/gtmkrigjdi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yanxiufei.cn/Article/details/gtbariqhub.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shzxlz.cn/Article/details/gtrgbzjltc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqxreqamk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xinyue.icu/Article/details/gtjxaapfkp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.haohaochexian.top/Article/details/gtzaoslqxa.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtialysrls.html

O. 并发与异步
来源：http://dali.quarkkingdee.top/Article/details/gtexhkinlt.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtzmhsmifi.html

[O01] 启动一个线程
来源：http://dali.nanxinkj.top/Article/details/gthjzkgqbm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.fzhhl.top/Article/details/gtfycrvbfk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gteootytpn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.pengpengdd.cyou/Article/details/gtvyvhbmom.html

TS:   // 同 JS
来源：http://dali.gzhubu.top/Article/details/gtszfobvid.html

Java: new Thread(() -> f()).start()
来源：http://dali.hywenlv.cn/Article/details/gteezmyenb.html

Go:   go f()
来源：http://dali.ydzc1.top/Article/details/gtbpntcquo.html

Ruby: Thread.new { f }
来源：http://dali.tian-w.cn/Article/details/gtuazbosic.html

C#:   Task.Run(() => F());
来源：http://dali.zdqjudy.top/Article/details/gtakklbwfd.html

[O02] 使用线程池
来源：http://dali.xziqi.cn/Article/details/gtqrafbfxv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.snrcjt.cn/Article/details/gttrtubace.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.9152youxi.cn/Article/details/gtotnbsedx.html

JS:   // worker_threads 线程池
来源：http://dali.hfpthk.cn/Article/details/gtmibaurrb.html

TS:   // worker_threads 线程池
来源：http://dali.nanxuanxn.top/Article/details/gtfbbnlzxi.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.wangdashe.top/Article/details/gtzriahmzl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ybcxt.top/Article/details/gtbaezxgmk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hongshengwenyu.top/Article/details/gtagipligd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.dianchejie.cn/Article/details/gtgrjnhicj.html

[O03] 加锁保护共享数据
来源：http://dali.daxiang520.top/Article/details/gtarygrzkv.html

Py:   with lock: shared += 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtilddbfpz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jinyuanbaomall.cn/Article/details/gtutjjprdo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.nwbrower.top/Article/details/gtevijunhw.html

TS:   // 同 JS
来源：http://dali.kuanghao11.cn/Article/details/gtsowbpcnp.html

Java: synchronized (this) { shared++; }
来源：http://dali.sweek.top/Article/details/gtdplgmbue.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhengqikj.top/Article/details/gtdqziophg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hywenlv.cn/Article/details/gtqfuwtaqf.html

C#:   lock (gate) { shared++; }
来源：http://dali.0kj1m.cn/Article/details/gtqxiqfweh.html

[O04] 定义异步函数并等待
来源：http://dali.shuidangran.top/Article/details/gtuoxytjpy.html

Py:   async def f():⏎    await g()
来源：http://dali.316326.xyz/Article/details/gtcumdbcga.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhongyouzk.top/Article/details/gtrsobgbfe.html

JS:   async function f() { await g(); }
来源：http://dali.316326.xyz/Article/details/gtqojwtsre.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenlongwang.top/Article/details/gtkkpyajlo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtohxsypwh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hfpthk.cn/Article/details/gtrzzmyeji.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhengqikj.top/Article/details/gtradihdws.html

C#:   async Task F() { await G(); }
来源：http://dali.cucudq.cn/Article/details/gtgecdmlwy.html

[O05] 并发执行并等待全部完成
来源：http://dali.c1oappe.top/Article/details/gtiolgbyip.html

Py:   asyncio.gather(*tasks)
来源：http://dali.sxryk.cn/Article/details/gtetrizbqy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gzhubu.top/Article/details/gtuhqzkbim.html

JS:   await Promise.all(tasks)
来源：http://dali.yuxming.cn/Article/details/gtlciwcaud.html

TS:   await Promise.all(tasks)
来源：http://dali.jyoumei.cn/Article/details/gtirkxcjzr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gogol.net.cn/Article/details/gtxlisalxs.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhongyouzk.top/Article/details/gtzqowkiji.html

Ruby: threads.map(&:join)
来源：http://dali.zhixingplan.top/Article/details/gtkxcmnumu.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.wangdashe.top/Article/details/gtorabirhf.html

[O06] 使用进程池
来源：http://dali.316326.xyz/Article/details/gtnirbbhrc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.snrcjt.cn/Article/details/gtpjewsyje.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yj20258.top/Article/details/gtskvrflmv.html

JS:   // child_process / cluster 模块
来源：http://dali.aizwys.cn/Article/details/gtwajdajxm.html

TS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangtech.top/Article/details/gtfwrmmapr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhengqikj.top/Article/details/gtzvlpcukk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jqgufenzy.top/Article/details/gtissfiqen.html

Ruby: // fork 块
来源：http://dali.zhoulong.xyz/Article/details/gtuxnjlyee.html

C#:   Parallel.For
来源：http://dali.guannengcc.top/Article/details/gttcerszpb.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtvvdpilyu.html

P. 常用工具函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpmeivale.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtoxlcpptd.html

[P01] 生成 UUID
来源：http://dali.gogol.net.cn/Article/details/gtrapsowwa.html

Py:   str(uuid.uuid4())
来源：http://dali.hysaishi.cn/Article/details/gtamkfignp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.andypj.xyz/Article/details/gteausitic.html

JS:   crypto.randomUUID()
来源：http://dali.redwolf501.top/Article/details/gtfbudhjwl.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gtpnmuerzx.html

Java: UUID.randomUUID().toString()
来源：http://dali.nanxinkj.top/Article/details/gtbryiwbdl.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yueranfly.top/Article/details/gtdrsnjyju.html

Ruby: SecureRandom.uuid
来源：http://dali.xylfe.cn/Article/details/gttbwfqccx.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cdnleiting.top/Article/details/gthhregmbm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shuidangran.top/Article/details/gtgunjxjlf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.vqdsnc.cn/Article/details/gtukpzugwf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yuanzhike.top/Article/details/gtqqvefeko.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yuxming.cn/Article/details/gtensznwro.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtppdmeqbl.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hammf.cn/Article/details/gtuvgsijcl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yuanzhike.top/Article/details/gtfcavfxmq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xinyue.icu/Article/details/gtnltjvfig.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shuidangran.top/Article/details/gtyscjjyvp.html

[P03] 生成短随机字符串
来源：http://dali.zdqjudy.top/Article/details/gtwzrcndtj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cdnleiting.top/Article/details/gtpwfxstmg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cucudq.cn/Article/details/gtpmxfyqvm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xylfe.cn/Article/details/gtcxekfqmg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gotoacloud.top/Article/details/gtkutxkles.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sysykeji.top/Article/details/gtdruuyuzh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hnxiangtu.top/Article/details/gtiwidocqv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.sufxvd.cn/Article/details/gtqrvqycpu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.fengsongda.top/Article/details/gtcxqotdpm.html

[P04] 求长度
来源：http://dali.jlsjyb.cn/Article/details/gtnnabtwpm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hongshengwenyu.top/Article/details/gthhsmkgfq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cheryme.top/Article/details/gtiwrkkegk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxinkj.top/Article/details/gtzdxrcvzm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xinyue.icu/Article/details/gtdkgffopk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zycfv.cn/Article/details/gtrcaqbtvc.html

Go:   len(arr);  len(m)
来源：http://dali.tianlin.xyz/Article/details/gthputsjmv.html

Ruby: x.length;  x.size
来源：http://dali.9152youxi.cn/Article/details/gtobfymink.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ybcxt.top/Article/details/gtdgkckdva.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jyoumei.cn/Article/details/gtivlinrto.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.aibaodan.cn/Article/details/gtzkhifmju.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hysaishi.cn/Article/details/gtporkivan.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xuetiantiany.cn/Article/details/gtptavhkgn.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shzxlz.cn/Article/details/gtbgnnwaxm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xuetiantiany.cn/Article/details/gtslgqqneu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.vqdsnc.cn/Article/details/gtnanmryyz.html

Ruby: a == b
来源：http://dali.aibaodan.cn/Article/details/gtaggoajnh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.dashuyun.cn/Article/details/gtsxfykbuv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jlsjyb.cn/Article/details/gtzibbkjrt.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.svipenyu.cn/Article/details/gtydjbzfop.html

PHP:  if (empty($x)) {}
来源：http://dali.sweek.top/Article/details/gthgcqexfs.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hnqzz.top/Article/details/gtpmuerpfq.html

TS:   if (x == null) {}
来源：http://dali.hnxiangtu.top/Article/details/gtpgydjbla.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jlsjyb.cn/Article/details/gtolmosppe.html

Go:   if x == nil {}
来源：http://dali.xinyue.icu/Article/details/gtckwzjdok.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.tian-w.cn/Article/details/gtbdvbnioq.html

C#:   if (x is null) {}
来源：http://dali.yonumen.top/Article/details/gtainvorti.html

[P07] 防抖与节流
来源：http://dali.nanxinkj.top/Article/details/gtvpjytlgz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shanyushiyangkeji.top/Article/details/gtijeattet.html

PHP:  // 手写时间戳比较
来源：http://dali.shzxlz.cn/Article/details/gtqzcovrrq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.smart0.xyz/Article/details/gtmtugudtz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zdqjudy.top/Article/details/gtfaukktkt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtztvcmjae.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.daria6918.cn/Article/details/gtasyaisii.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.sufxvd.cn/Article/details/gthjlxlguw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gotoacloud.top/Article/details/gtttrngljq.html

[P08] 处理浮点精度问题
来源：http://dali.birdmap.top/Article/details/gtscnbqony.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.meibo888.top/Article/details/gtejgizssb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtkxegyrhm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xuanzx.com/Article/details/gtbmwmrhbo.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoaqwzvbx.html


<!-- 参考信息 -->