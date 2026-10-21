代发 wailian999

JS:   process.argv.slice(2)
来源：http://dali.nanxuanxn.top/Article/details/gtlskrchnw.html

TS:   process.argv.slice(2)
来源：http://dali.andypj.xyz/Article/details/gtcparihbn.html

Java: args 数组（main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkjoqocna.html

Go:   os.Args[1:]
来源：http://dali.pycfn.com/Article/details/gtbpqvuhxp.html

Ruby: ARGV
来源：http://dali.ybcxt.top/Article/details/gtdqyatiks.html

C#:   args 数组（Main 方法参数）
来源：http://dali.fengsongda.top/Article/details/gtzyspatnp.html

[M02] 读取环境变量
来源：http://dali.nwbrower.top/Article/details/gtmifbqvez.html

Py:   os.environ.get("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvlfnvdem.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sysykeji.top/Article/details/gtbngvphoj.html

JS:   process.env.HOME
来源：http://dali.haohaochexian.top/Article/details/gtmjqirdbz.html

TS:   process.env.HOME
来源：http://dali.feifeiyinyue.top/Article/details/gtaziodkxl.html

Java: System.getenv("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gtqpessnhb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpvdntyre.html

Ruby: ENV["HOME"]
来源：http://dali.hywenlv.cn/Article/details/gtpxhbiwfn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gtsnaahcwj.html

[M03] 执行外部命令
来源：http://dali.xinyue.icu/Article/details/gtdubbhixp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkwkjenoc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cashguo.top/Article/details/gtokmvxuqn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jlsjyb.cn/Article/details/gtmhwuunjk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.dashuyun.cn/Article/details/gtvtnpntle.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xuetiantiany.cn/Article/details/gtoswuikqk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jqgfzy.top/Article/details/gtfdktbyfh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinghuilouyu.cn/Article/details/gthxjxkksb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sufxvd.cn/Article/details/gtpekdysjv.html

[M04] 获取当前工作目录
来源：http://dali.cqqwz.cn/Article/details/gtdwfwoqyz.html

Py:   os.getcwd()
来源：http://dali.gaohongyu789.top/Article/details/gttofrtgfu.html

PHP:  getcwd();
来源：http://dali.hysaishi.cn/Article/details/gtcoamnufo.html

JS:   process.cwd()
来源：http://dali.yvedp.cn/Article/details/gtywgubxrd.html

TS:   process.cwd()
来源：http://dali.ivvv.top/Article/details/gtprrraemd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.dashuyun.cn/Article/details/gtoffpcaot.html

Go:   os.Getwd()
来源：http://dali.0kj1m.cn/Article/details/gtidtvnkuu.html

Ruby: Dir.pwd
来源：http://dali.xinyue.icu/Article/details/gtalnwkwvb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gzhubu.top/Article/details/gtipotjjei.html

[M05] 设置退出码
来源：http://dali.sufxvd.cn/Article/details/gtlsgmtkyy.html

Py:   sys.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtvtyjkyfu.html

PHP:  exit(1);
来源：http://dali.ivvv.top/Article/details/gtetedksya.html

JS:   process.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gttsskfwdv.html

TS:   process.exit(1)
来源：http://dali.xuanzx.com/Article/details/gtkkfwbqjw.html

Java: System.exit(1)
来源：http://dali.havefunace.top/Article/details/gtchaulymh.html

Go:   os.Exit(1)
来源：http://dali.hysaishi.cn/Article/details/gtzjrevuxf.html

Ruby: exit 1
来源：http://dali.mhx1999.top/Article/details/gtokvxkdpd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.aizwys.cn/Article/details/gthbmswqgn.html

[M06] 向标准错误输出
来源：http://dali.sufxvd.cn/Article/details/gtezncovwx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zdqjudy.top/Article/details/gtsksegxpr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhengqikj.top/Article/details/gtzfarcbro.html

JS:   console.error("err")
来源：http://dali.cqqwz.cn/Article/details/gtdgaqhyvo.html

TS:   console.error("err")
来源：http://dali.ehwqpu.com/Article/details/gtcoxmumxv.html

Java: System.err.println("err")
来源：http://dali.yj20258.top/Article/details/gtwmfkdxpr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.nanxuanxn.top/Article/details/gteplmpqmw.html

Ruby: warn "err"
来源：http://dali.chenjidiqi.icu/Article/details/gtruekczff.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.iojbl.cn/Article/details/gtyztftmiv.html

[M07] 判断是否为主入口
来源：http://dali.redwolf501.top/Article/details/gtbdblgckv.html

Py:   if __name__ == "__main__":
来源：http://dali.shzxlz.cn/Article/details/gtidkbiqha.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.snrcjt.cn/Article/details/gtohwgihch.html

JS:   require.main === module
来源：http://dali.feifeiyinyue.top/Article/details/gtzymznbtx.html

TS:   require.main === module
来源：http://dali.jiagoushi.top/Article/details/gtavwehbyg.html

Java: public static void main(String[] args)
来源：http://dali.yonumen.top/Article/details/gtzukcgejx.html

Go:   func main()
来源：http://dali.jlsjyb.cn/Article/details/gtjaifjwcl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenlongwang.top/Article/details/gttwrbcphw.html

C#:   static void Main(string[] args)
来源：http://dali.guowangkeji.top/Article/details/gtcccwhiug.html

[M08] 获取系统与运行时信息
来源：http://dali.hnqzz.top/Article/details/gtclssykcp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.316326.xyz/Article/details/gtysfviiif.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.guannengcc.top/Article/details/gtxeprthvq.html

JS:   process.platform;  process.version
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxanblcva.html

TS:   process.platform;  process.version
来源：http://dali.xinyue.icu/Article/details/gtuikckfqv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.feifeiyinyue.top/Article/details/gtglwvwsuz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hnqzz.top/Article/details/gtahlmxopg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hfpthk.cn/Article/details/gtdqtfpobi.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gogol.net.cn/Article/details/gtcwstuzzy.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtisdhbofv.html

N. 数据结构与算法
来源：http://dali.iojbl.cn/Article/details/gtrdtrsllt.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtqqmxnbfr.html

[N01] 二分查找（有序数组）
来源：http://dali.yueranfly.top/Article/details/gtebyhcpbw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gtbblojxbh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yonumen.top/Article/details/gtkomvegzo.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvhfqtnro.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sysykeji.top/Article/details/gtlcwzpxsn.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtjmwzlplr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtfyskwjbn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj20258.top/Article/details/gthtgecddg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtxbyphces.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.316326.xyz/Article/details/gtjmvfcgvj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258.top/Article/details/gtflpmbnng.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yonumen.top/Article/details/gtsejsyfwy.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigfzy.top/Article/details/gtdcwkwgcm.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuanzhike.top/Article/details/gtifmctrur.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shzxlz.cn/Article/details/gtetanhegb.html

Go:   slices.Sort(arr)
来源：http://dali.meibo888.top/Article/details/gtvpdswpzv.html

Ruby: arr.sort
来源：http://dali.ydzc1.top/Article/details/gttwkrwlri.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.haohaochexian.top/Article/details/gtvipftaxv.html

[N03] 快速排序（分治示例）
来源：http://dali.pycfn.com/Article/details/gteevjffqh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.meibo888.top/Article/details/gtzhsgqpos.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gotoacloud.top/Article/details/gtjrevezxv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jyoumei.cn/Article/details/gtnxouqilz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pengpengdd.cyou/Article/details/gteybmikcb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shangyingyoupin.top/Article/details/gtaoaaofft.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cdnleiting.top/Article/details/gtcachcrts.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsyjhejpq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.316326.xyz/Article/details/gtxpzonrhp.html

[N04] 斐波那契数列
来源：http://dali.guowangkeji.top/Article/details/gtqrqohuub.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtrbepglgz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zycfv.cn/Article/details/gttftppbeg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcwdjijqt.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.vqdsnc.cn/Article/details/gtyedboenc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hnxiangtu.top/Article/details/gtqhbqjzga.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jiagoushi.top/Article/details/gtiyrhxomo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.svipenyu.cn/Article/details/gtshfjilrb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.gaohongyu789.top/Article/details/gtucwamgoc.html

[N05] 最大公约数
来源：http://dali.cdnleiting.top/Article/details/gtmexomyjo.html

Py:   math.gcd(a, b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtahxftkux.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.pycfn.com/Article/details/gtyssitxul.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhoulong.xyz/Article/details/gtzdtyvjhf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gtphcanljl.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.pycfn.com/Article/details/gtpgkyvqtd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yj20258.top/Article/details/gtxxipddbo.html

Ruby: a.gcd(b)
来源：http://dali.ydzc1.top/Article/details/gtabxxmugf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ivvv.top/Article/details/gtqvzvwzch.html

[N06] 判断回文字符串
来源：http://dali.ydzc1.top/Article/details/gtmpqimnai.html

Py:   s == s[::-1]
来源：http://dali.vqdsnc.cn/Article/details/gtnywljdtc.html

PHP:  $s === strrev($s);
来源：http://dali.jinqigfzy.top/Article/details/gtogcrjbxu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gtqmssqolf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gtcplrcxxj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shuidangran.top/Article/details/gtwiglvznl.html

Go:   // 双指针从两端比较
来源：http://dali.quarkkingdee.top/Article/details/gtgersxtrr.html

Ruby: s == s.reverse
来源：http://dali.316326.xyz/Article/details/gtelkrjmoy.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.snrcjt.cn/Article/details/gtfxlwgihl.html

[N07] 两数之和（返回下标）
来源：http://dali.c1oappe.top/Article/details/gtmtfbvdkf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.nwbrower.top/Article/details/gtpsaplgam.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jqgfzy.top/Article/details/gtantfaqky.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jlsjyb.cn/Article/details/gtvfpfrwxe.html

TS:   // 手写 Map<string, number>
来源：http://dali.jianghu66.top/Article/details/gtosflajep.html

Java: // 手写 HashMap
来源：http://dali.chenjidiqi.icu/Article/details/gtebipdfdj.html

Go:   // 手写 map[int]int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtugweiohv.html

Ruby: // 手写 Hash
来源：http://dali.316326.xyz/Article/details/gtgfdsmgqb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhengqikj.top/Article/details/gtbbnfrllk.html

[N08] 生成全排列
来源：http://dali.pengpengdd.cyou/Article/details/gtcihptjez.html

Py:   itertools.permutations(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtamzetkgk.html

PHP:  // 手写递归交换
来源：http://dali.iojbl.cn/Article/details/gtsmstubtu.html

JS:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gtithoufcd.html

TS:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gtxnhbtsra.html

Java: // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gtbmtlhbyz.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gtfdyyallx.html

Ruby: arr.permutation.to_a
来源：http://dali.cashguo.top/Article/details/gtbpoetazs.html

C#:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gtyoptkmrs.html

[N09] 栈与队列
来源：http://dali.yuxming.cn/Article/details/gtmnzmcoqu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shuidangran.top/Article/details/gtbnjqqfun.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yonumen.top/Article/details/gtujkqbyql.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jianghu66.top/Article/details/gtqldfolqk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.bjfxy.top/Article/details/gtwxbagafu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.aibaodan.cn/Article/details/gtoblhthbe.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shangyingyoupin.top/Article/details/gtclabvcaj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xylfe.cn/Article/details/gtvlrdgjny.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cdnleiting.top/Article/details/gtprblfwip.html

[N10] 链表节点定义
来源：http://dali.zycfv.cn/Article/details/gtevyjifke.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.dashuyun.cn/Article/details/gtxeogjyup.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.guannengcc.top/Article/details/gtemdqikoa.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hywenlv.cn/Article/details/gtbaeqdqkv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhengqikj.top/Article/details/gtxldwctrz.html

Java: class Node { int v; Node next; }
来源：http://dali.andypj.xyz/Article/details/gtolchuicq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenjidiqi.icu/Article/details/gtjmaldlip.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.pycfn.com/Article/details/gtmdsrwxhc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tianlin.xyz/Article/details/gteibuzfif.html

[N11] 二叉树中序遍历
来源：http://dali.zhengqikj.top/Article/details/gtuhvllpkw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sysykeji.top/Article/details/gtsjinzfeh.html

PHP:  // 手写递归函数
来源：http://dali.yonumen.top/Article/details/gteitmkmpr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tanke756.top/Article/details/gtpiuzxdtz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xinyue.icu/Article/details/gtxepxggyj.html

Java: // 手写递归
来源：http://dali.hongshengwenyu.top/Article/details/gtnlltwojk.html

Go:   // 手写递归
来源：http://dali.gotoacloud.top/Article/details/gtiqhnlbrv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.quarkkingdee.top/Article/details/gtfkzzakij.html

C#:   // 手写递归
来源：http://dali.ehwqpu.com/Article/details/gttijaiuqv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.feifeiyinyue.top/Article/details/gtaljbaowe.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.tian-w.cn/Article/details/gtqctqkjku.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.sysykeji.top/Article/details/gthckvypmu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hnqzz.top/Article/details/gtqbqqbkjw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhiwuduotai.top/Article/details/gtianlgngn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xziqi.cn/Article/details/gtklwkbjmp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.vqdsnc.cn/Article/details/gtxmdnecww.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.pengpengdd.cyou/Article/details/gtwkgxcrpf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cucudq.cn/Article/details/gtxrllljak.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gthplvxvnv.html

O. 并发与异步
来源：http://dali.zhoulong.xyz/Article/details/gtrdhbxwpt.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtosqzhwwq.html

[O01] 启动一个线程
来源：http://dali.redwolf501.top/Article/details/gtdivnwiuk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cheryme.top/Article/details/gtzmbhhrrt.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.fzhhl.top/Article/details/gtlshgbjwd.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hongshengwenyu.top/Article/details/gtnpwcnqmr.html

TS:   // 同 JS
来源：http://dali.jiagoushi.top/Article/details/gtxdouftfm.html

Java: new Thread(() -> f()).start()
来源：http://dali.hysaishi.cn/Article/details/gthaowdxjg.html

Go:   go f()
来源：http://dali.zhongyouzk.top/Article/details/gtmkhonthn.html

Ruby: Thread.new { f }
来源：http://dali.chenjidiqi.icu/Article/details/gtomqkuzyv.html

C#:   Task.Run(() => F());
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgktqhthh.html

[O02] 使用线程池
来源：http://dali.zhiwuduotai.top/Article/details/gtflqgcbag.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yvedp.cn/Article/details/gtggtgwwwz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhengqikj.top/Article/details/gteyilpkaw.html

JS:   // worker_threads 线程池
来源：http://dali.cqqwz.cn/Article/details/gtvfldmsmm.html

TS:   // worker_threads 线程池
来源：http://dali.tanke756.top/Article/details/gteyjemkuv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.gaohongyu789.top/Article/details/gtepesbbyu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sysykeji.top/Article/details/gtweojihun.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.aizwys.cn/Article/details/gtjvsyixri.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jianghu66.top/Article/details/gtwzehrwjd.html

[O03] 加锁保护共享数据
来源：http://dali.ivvv.top/Article/details/gtggibzyav.html

Py:   with lock: shared += 1
来源：http://dali.gotoacloud.top/Article/details/gtyqulraye.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhixingplan.top/Article/details/gtfodqcynk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.wangshuangyany.cn/Article/details/gtitqovwto.html

TS:   // 同 JS
来源：http://dali.nanxuanxn.top/Article/details/gtauaqygdj.html

Java: synchronized (this) { shared++; }
来源：http://dali.hysaishi.cn/Article/details/gtsspgycsb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cashguo.top/Article/details/gthxiwmoug.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.dianchejie.cn/Article/details/gtmjghhpth.html

C#:   lock (gate) { shared++; }
来源：http://dali.jianghu66.top/Article/details/gtjdccqetw.html

[O04] 定义异步函数并等待
来源：http://dali.zhongyouzk.top/Article/details/gtwrseluya.html

Py:   async def f():⏎    await g()
来源：http://dali.tanke756.top/Article/details/gtsdxpnisw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hnxiangtu.top/Article/details/gtcigvxuwf.html

JS:   async function f() { await g(); }
来源：http://dali.iojbl.cn/Article/details/gtclvaptix.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhongyouzk.top/Article/details/gtimzwgrld.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jiagoushi.top/Article/details/gtjfhfzatu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.dianchejie.cn/Article/details/gtkuywctks.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hysaishi.cn/Article/details/gtvkrhvwnt.html

C#:   async Task F() { await G(); }
来源：http://dali.cucudq.cn/Article/details/gtalpyierd.html

[O05] 并发执行并等待全部完成
来源：http://dali.yuxming.cn/Article/details/gtankfqhbq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.aibaodan.cn/Article/details/gtmgvyopet.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jqgufenzy.top/Article/details/gtfjspsftb.html

JS:   await Promise.all(tasks)
来源：http://dali.svipenyu.cn/Article/details/gtkhzbdrxj.html

TS:   await Promise.all(tasks)
来源：http://dali.xuanzx.com/Article/details/gtxswooefz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinqigfzy.top/Article/details/gtunxwsgzo.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhoulong.xyz/Article/details/gtyemudsjc.html

Ruby: threads.map(&:join)
来源：http://dali.c1oappe.top/Article/details/gthqteyxew.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.redwolf501.top/Article/details/gtbuvrgojv.html

[O06] 使用进程池
来源：http://dali.jlsjyb.cn/Article/details/gtuypqsrdg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yuanzhike.top/Article/details/gternzskrc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.aizwys.cn/Article/details/gtsgydfhai.html

JS:   // child_process / cluster 模块
来源：http://dali.ydzc1.top/Article/details/gtysrmijms.html

TS:   // child_process / cluster 模块
来源：http://dali.jqgfzy.top/Article/details/gtkqktcpnb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yanxiufei.cn/Article/details/gtqvunusnc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.iojbl.cn/Article/details/gtusxeqvcf.html

Ruby: // fork 块
来源：http://dali.yuanzhike.top/Article/details/gtgzvmmmdy.html

C#:   Parallel.For
来源：http://dali.aizwys.cn/Article/details/gtsmvglhhz.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtiahfdrnj.html

P. 常用工具函数
来源：http://dali.zhengqikj.top/Article/details/gtancyzlat.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtlqdajfhq.html

[P01] 生成 UUID
来源：http://dali.smart0.xyz/Article/details/gtbuyuxcnb.html

Py:   str(uuid.uuid4())
来源：http://dali.hfpthk.cn/Article/details/gtrrxrfzzb.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.andypj.xyz/Article/details/gtmisevjrp.html

JS:   crypto.randomUUID()
来源：http://dali.aizwys.cn/Article/details/gtvehwximf.html

TS:   crypto.randomUUID()
来源：http://dali.yonumen.top/Article/details/gtbnxalgyu.html

Java: UUID.randomUUID().toString()
来源：http://dali.yj20258888.top/Article/details/gtgrblvfgw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.dianchejie.cn/Article/details/gteqewihbr.html

Ruby: SecureRandom.uuid
来源：http://dali.yvedp.cn/Article/details/gtlguqnjmg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hywenlv.cn/Article/details/gttiuyeplx.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfpxjkeeu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hywenlv.cn/Article/details/gtsvrjblhg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hnqzz.top/Article/details/gtvwajimqv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jyoumei.cn/Article/details/gtacagzvgc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ppjwa.cn/Article/details/gtzvimeije.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhixingplan.top/Article/details/gttluxfobz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhiwuduotai.top/Article/details/gtowqvqcqu.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.0kj1m.cn/Article/details/gttuezgfas.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xylfe.cn/Article/details/gtcivefjik.html

[P03] 生成短随机字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtdtqtvqkh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.sweek.top/Article/details/gtnszwwamp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zdqjudy.top/Article/details/gtcjhtgaup.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yangfankeji.com/Article/details/gtxladhwve.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.guowangkeji.top/Article/details/gtxadhnztj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.meibo888.top/Article/details/gtqipjohbq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zdqjudy.top/Article/details/gtkgwgnpix.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.wangdashe.top/Article/details/gtdmifghff.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xylfe.cn/Article/details/gtvnuqtseb.html

[P04] 求长度
来源：http://dali.jqgfzy.top/Article/details/gtyuxoybav.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shuidangran.top/Article/details/gtffxgnbdf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gtagltqxcg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guowangkeji.top/Article/details/gtywcypqos.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ydzc1.top/Article/details/gtdiiimvzg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.chenzaomai.com/Article/details/gtbfsbztnm.html

Go:   len(arr);  len(m)
来源：http://dali.zhixingplan.top/Article/details/gthnbczkcs.html

Ruby: x.length;  x.size
来源：http://dali.guowangkeji.top/Article/details/gtgahhwcfz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.haohaochexian.top/Article/details/gtxljfjfsz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ybcxt.top/Article/details/gtdnngfnqg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cucudq.cn/Article/details/gtijnlxyak.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cheryme.top/Article/details/gtwdpnotxs.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cucudq.cn/Article/details/gtfmsnyciw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoaqhxkyd.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shangyingyoupin.top/Article/details/gtslzvssti.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.tanke756.top/Article/details/gthmzbragv.html

Ruby: a == b
来源：http://dali.hnqzz.top/Article/details/gtrkoesjop.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.guowangkeji.top/Article/details/gtmrtpuqeo.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hongshengwenyu.top/Article/details/gtfyrnhrce.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yj20258.top/Article/details/gtsososktl.html

PHP:  if (empty($x)) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdjpxfyfn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.quarkkingdee.top/Article/details/gtpmwrunjz.html

TS:   if (x == null) {}
来源：http://dali.jyoumei.cn/Article/details/gtyzkhmcbf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhengqikj.top/Article/details/gtsdvrecbc.html

Go:   if x == nil {}
来源：http://dali.jinghuilouyu.cn/Article/details/gteqqpmemx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sweek.top/Article/details/gtlewncsqj.html

C#:   if (x is null) {}
来源：http://dali.iojbl.cn/Article/details/gtywcyrfey.html

[P07] 防抖与节流
来源：http://dali.kuanghao11.cn/Article/details/gtpkdyspgg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jinqigufen.top/Article/details/gtlhdvciuu.html

PHP:  // 手写时间戳比较
来源：http://dali.aibaodan.cn/Article/details/gtrktpujun.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xziqi.cn/Article/details/gtwuecmlje.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hongshengwenyu.top/Article/details/gtowoahfxs.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gtjjyrwtvt.html


<!-- 参考信息 -->