代发 wailian999

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gtueokpqwk.html

Ruby: ENV["HOME"]
来源：http://dali.vqdsnc.cn/Article/details/gtbutwucob.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.bjfxy.top/Article/details/gtvspbuofc.html

[M03] 执行外部命令
来源：http://dali.nanxinkj.top/Article/details/gtpcdpndpb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.dianchejie.cn/Article/details/gtgljjyjuj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ehwqpu.com/Article/details/gtyjkcvxrf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuanzx.com/Article/details/gtsswjeqli.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sufxvd.cn/Article/details/gtvtmnpqwa.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ydzc1.top/Article/details/gtrbbehdhx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinqigufen.top/Article/details/gtifjjfqfn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.0kj1m.cn/Article/details/gtcyyyjern.html

C#:   Process.Start("ls", "-l");
来源：http://dali.316326.xyz/Article/details/gtwsuvokcm.html

[M04] 获取当前工作目录
来源：http://dali.gaohongyu789.top/Article/details/gtyfnsggxl.html

Py:   os.getcwd()
来源：http://dali.jqgufenzy.top/Article/details/gtusrhkahg.html

PHP:  getcwd();
来源：http://dali.xinyue.icu/Article/details/gtbnismqgi.html

JS:   process.cwd()
来源：http://dali.hywenlv.cn/Article/details/gtiwlrcltj.html

TS:   process.cwd()
来源：http://dali.quarkkingdee.top/Article/details/gtvgfeyvvl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinqigufen.top/Article/details/gtbocgcwzk.html

Go:   os.Getwd()
来源：http://dali.daria6918.cn/Article/details/gtxsqaahwz.html

Ruby: Dir.pwd
来源：http://dali.jinghuilouyu.cn/Article/details/gtivsmpgma.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.fzhhl.top/Article/details/gtlrlhoysl.html

[M05] 设置退出码
来源：http://dali.vqdsnc.cn/Article/details/gtggmnfgds.html

Py:   sys.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtavgmwzqw.html

PHP:  exit(1);
来源：http://dali.zhengqikj.top/Article/details/gtgnomagny.html

JS:   process.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gtvfshztzb.html

TS:   process.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gtgmwyxhio.html

Java: System.exit(1)
来源：http://dali.jianghu66.top/Article/details/gtiwnkvpxu.html

Go:   os.Exit(1)
来源：http://dali.hammf.cn/Article/details/gtrspfucfm.html

Ruby: exit 1
来源：http://dali.ehwqpu.com/Article/details/gterozclha.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj20258.top/Article/details/gtagbrxwqw.html

[M06] 向标准错误输出
来源：http://dali.nanxinkj.top/Article/details/gtywvbjrec.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtacfsgtcp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yj202588.top/Article/details/gtxvshwocq.html

JS:   console.error("err")
来源：http://dali.tian-w.cn/Article/details/gtvgmgcbiu.html

TS:   console.error("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtpmaykjlc.html

Java: System.err.println("err")
来源：http://dali.nanxuanxn.top/Article/details/gthwbgbgfm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinqigufen.top/Article/details/gtbupbiohj.html

Ruby: warn "err"
来源：http://dali.yj202588.top/Article/details/gtuspuuqjy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xziqi.cn/Article/details/gtsxtfhwhr.html

[M07] 判断是否为主入口
来源：http://dali.zhixingplan.top/Article/details/gttdjmzeoy.html

Py:   if __name__ == "__main__":
来源：http://dali.haohaochexian.top/Article/details/gtzsikmimb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.tanke756.top/Article/details/gtdrabchoa.html

JS:   require.main === module
来源：http://dali.jqgfzy.top/Article/details/gtszwuzzpl.html

TS:   require.main === module
来源：http://dali.tianlin.xyz/Article/details/gtefvgpkbm.html

Java: public static void main(String[] args)
来源：http://dali.gotoacloud.top/Article/details/gtsumqfysb.html

Go:   func main()
来源：http://dali.sxryk.cn/Article/details/gtotvbmmqc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xuanzx.com/Article/details/gtfzseveza.html

C#:   static void Main(string[] args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnfmlbscv.html

[M08] 获取系统与运行时信息
来源：http://dali.pycfn.com/Article/details/gtfobyekrp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.svipenyu.cn/Article/details/gtsiximtdy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ybcxt.top/Article/details/gtigfukxlj.html

JS:   process.platform;  process.version
来源：http://dali.jlsjyb.cn/Article/details/gtisfkalac.html

TS:   process.platform;  process.version
来源：http://dali.shzxlz.cn/Article/details/gtbydeqlne.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xylfe.cn/Article/details/gtmgmogwzf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.chenzaomai.com/Article/details/gtnsjraxkd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.chenzaomai.com/Article/details/gteuqnuwyp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.dashuyun.cn/Article/details/gtssrzfvno.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gttqaimdwh.html

N. 数据结构与算法
来源：http://dali.wangdashe.top/Article/details/gtcvskzmbk.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gthlmbkhzq.html

[N01] 二分查找（有序数组）
来源：http://dali.gzhubu.top/Article/details/gtluajgopz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtfrjudvrb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yvedp.cn/Article/details/gtaahuyxcr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sweek.top/Article/details/gtpehfgftn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hfpthk.cn/Article/details/gtmdzewuar.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yonumen.top/Article/details/gtcioqeith.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.316326.xyz/Article/details/gtapuoileb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.tianlin.xyz/Article/details/gtoclybzzu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtqfwaphwo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shuidangran.top/Article/details/gtgnkjabbr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dashuyun.cn/Article/details/gtesoeqsgk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yj202588.top/Article/details/gtkzbdxptx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shuidangran.top/Article/details/gtmxxjgigl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258.top/Article/details/gtofxnvptr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.nanxinkj.top/Article/details/gtspnivdkz.html

Go:   slices.Sort(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtnhoauhzr.html

Ruby: arr.sort
来源：http://dali.hysaishi.cn/Article/details/gtjonyemym.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.9152youxi.cn/Article/details/gtwxfkkctw.html

[N03] 快速排序（分治示例）
来源：http://dali.c1oappe.top/Article/details/gtxvhvunpb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sxryk.cn/Article/details/gtcogjywto.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tanke756.top/Article/details/gtllqdygbg.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgufenzy.top/Article/details/gtcwmzqkyp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigfzy.top/Article/details/gtmxjigadr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.nanxinkj.top/Article/details/gttdosyrbl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.aibaodan.cn/Article/details/gtboareuxs.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.guowangkeji.top/Article/details/gtzxjasdfp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xuanzx.com/Article/details/gtxbxoqehx.html

[N04] 斐波那契数列
来源：http://dali.yangfankeji.com/Article/details/gtipdbddqg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtekfgbfej.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yongpay.top/Article/details/gtwxdccwzk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pycfn.com/Article/details/gtmsbeoahd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjrpwqqlq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hongshengwenyu.top/Article/details/gtlgfzfjgr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gtxgbductp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.c1oappe.top/Article/details/gtqtcxxfmd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.chenzaomai.com/Article/details/gtgpknzjho.html

[N05] 最大公约数
来源：http://dali.tian-w.cn/Article/details/gtwqvdfqed.html

Py:   math.gcd(a, b)
来源：http://dali.cdnleiting.top/Article/details/gthrmwuosc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ivvv.top/Article/details/gtumexpgph.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuanzhike.top/Article/details/gtzwnqizse.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnxiangtu.top/Article/details/gtwuicmqaz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xylfe.cn/Article/details/gtmhuqipdd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yj20258888.top/Article/details/gtydunnzir.html

Ruby: a.gcd(b)
来源：http://dali.fzhhl.top/Article/details/gtgsnpkkoe.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jianghu66.top/Article/details/gttdhjtsik.html

[N06] 判断回文字符串
来源：http://dali.jlsjyb.cn/Article/details/gtgioqnlxw.html

Py:   s == s[::-1]
来源：http://dali.vqdsnc.cn/Article/details/gtyftatldx.html

PHP:  $s === strrev($s);
来源：http://dali.daxiang520.top/Article/details/gtvznfklag.html

JS:   s === [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gtwutzoxsu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yuxming.cn/Article/details/gtxfucdaqm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinqigufen.top/Article/details/gtfblbeecv.html

Go:   // 双指针从两端比较
来源：http://dali.redwolf501.top/Article/details/gtnnjxoyco.html

Ruby: s == s.reverse
来源：http://dali.chenzaomai.com/Article/details/gtpgdsugwv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.guowangkeji.top/Article/details/gtajxccded.html

[N07] 两数之和（返回下标）
来源：http://dali.xuanzx.com/Article/details/gtceilkcdp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xylfe.cn/Article/details/gtlvvmtvaf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhiwuduotai.top/Article/details/gtutxwxoyy.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cqqwz.cn/Article/details/gtowgrafar.html

TS:   // 手写 Map<string, number>
来源：http://dali.zycfv.cn/Article/details/gthaiawcyd.html

Java: // 手写 HashMap
来源：http://dali.mhx1999.top/Article/details/gtetwmskxu.html

Go:   // 手写 map[int]int
来源：http://dali.jinghuilouyu.cn/Article/details/gthivrfcot.html

Ruby: // 手写 Hash
来源：http://dali.wangshuangyany.cn/Article/details/gtayiljfub.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwlxedcmo.html

[N08] 生成全排列
来源：http://dali.yvedp.cn/Article/details/gtstpwyyog.html

Py:   itertools.permutations(arr)
来源：http://dali.ehwqpu.com/Article/details/gtqzxzwvrf.html

PHP:  // 手写递归交换
来源：http://dali.cashguo.top/Article/details/gtliojukjx.html

JS:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gtyhegzrpd.html

TS:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gtbaolsjsj.html

Java: // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gttnblhmrj.html

Go:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtgmjotdfe.html

Ruby: arr.permutation.to_a
来源：http://dali.jqgfzy.top/Article/details/gtwvdbfeeo.html

C#:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtudmgryci.html

[N09] 栈与队列
来源：http://dali.jlsjyb.cn/Article/details/gtnvyulwxv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hnqzz.top/Article/details/gtnyepaeos.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shzxlz.cn/Article/details/gtlzqprnlk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtxvdjzpue.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhengqikj.top/Article/details/gtpdzcdmte.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ehwqpu.com/Article/details/gtkidksacc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zycfv.cn/Article/details/gtllusiogc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cashguo.top/Article/details/gtlofimehg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.dianchejie.cn/Article/details/gtrxbdqpka.html

[N10] 链表节点定义
来源：http://dali.zhiwuduotai.top/Article/details/gtcffkcoqs.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gzhubu.top/Article/details/gtvabzesiz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.316326.xyz/Article/details/gtjhsudvga.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.kuanghao11.cn/Article/details/gtzimxfwyd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinqigfzy.top/Article/details/gtxtbzdyjx.html

Java: class Node { int v; Node next; }
来源：http://dali.aizwys.cn/Article/details/gteuqucwhu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.nanxuanxn.top/Article/details/gtdpigjhqb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yueranfly.top/Article/details/gtjuubrchs.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcmfgknzk.html

[N11] 二叉树中序遍历
来源：http://dali.sxryk.cn/Article/details/gtbyetkumm.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.dashuyun.cn/Article/details/gtjjjdmjby.html

PHP:  // 手写递归函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtjpppkgrn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ybcxt.top/Article/details/gtthtikvcq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenzaomai.com/Article/details/gtschnhcbt.html

Java: // 手写递归
来源：http://dali.hnxiangtu.top/Article/details/gtisdtccco.html

Go:   // 手写递归
来源：http://dali.smart0.xyz/Article/details/gtkirbjwcf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.aizwys.cn/Article/details/gtajhvscrp.html

C#:   // 手写递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkcizhpjr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.c1oappe.top/Article/details/gtuqsdkkdp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.chenjidiqi.icu/Article/details/gtvyuhwjxx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hfpthk.cn/Article/details/gtvgbcrncv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zdqjudy.top/Article/details/gtaquchvdh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.c1oappe.top/Article/details/gtgvyqzoyk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zycfv.cn/Article/details/gtpeulhxxq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.gogol.net.cn/Article/details/gtnbmlaccq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.tanke756.top/Article/details/gtxnhlghrr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sxryk.cn/Article/details/gteizdcblr.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtmnleetgf.html

O. 并发与异步
来源：http://dali.dianchejie.cn/Article/details/gtwpjdpkgq.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtqwbikqfz.html

[O01] 启动一个线程
来源：http://dali.316326.xyz/Article/details/gtwvjuzuhf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.aizwys.cn/Article/details/gtfgqjzigv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yj20258888.top/Article/details/gtxyaxigrz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zdqjudy.top/Article/details/gtpdtgtchd.html

TS:   // 同 JS
来源：http://dali.yj20258888.top/Article/details/gtvqkrwdny.html

Java: new Thread(() -> f()).start()
来源：http://dali.gotoacloud.top/Article/details/gttbtkxtqj.html

Go:   go f()
来源：http://dali.yueranfly.top/Article/details/gtiexbsykt.html

Ruby: Thread.new { f }
来源：http://dali.gzhubu.top/Article/details/gtxipzjnex.html

C#:   Task.Run(() => F());
来源：http://dali.jinqigufen.top/Article/details/gtiawbzxzk.html

[O02] 使用线程池
来源：http://dali.ybcxt.top/Article/details/gtirzgamqn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zycfv.cn/Article/details/gtvcceodiw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shanyushiyangtech.top/Article/details/gtfqvpzqrn.html

JS:   // worker_threads 线程池
来源：http://dali.guowangkeji.top/Article/details/gtqakwpquk.html

TS:   // worker_threads 线程池
来源：http://dali.jiagoushi.top/Article/details/gtdqjcyoaw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yanxiufei.cn/Article/details/gtguyrplcu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jlsjyb.cn/Article/details/gtklmnznuj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.316326.xyz/Article/details/gtoggjioac.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jqgufenzy.top/Article/details/gtkolemebj.html

[O03] 加锁保护共享数据
来源：http://dali.mhx1999.top/Article/details/gtpwiylamj.html

Py:   with lock: shared += 1
来源：http://dali.chenzaomai.com/Article/details/gtmnmcqplo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cucudq.cn/Article/details/gtcpfggrkm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shuidangran.top/Article/details/gtutdaozak.html

TS:   // 同 JS
来源：http://dali.haohaochexian.top/Article/details/gtbynvbbgd.html

Java: synchronized (this) { shared++; }
来源：http://dali.daxiang520.top/Article/details/gtdngyddwt.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.mhx1999.top/Article/details/gtsyniahkm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.sxryk.cn/Article/details/gtnokldjjf.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhiwuduotai.top/Article/details/gtvotwstdt.html

[O04] 定义异步函数并等待
来源：http://dali.fengsongda.top/Article/details/gtcafjrmbc.html

Py:   async def f():⏎    await g()
来源：http://dali.zhiwuduotai.top/Article/details/gtyiwojhju.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ppjwa.cn/Article/details/gtaymxqsod.html

JS:   async function f() { await g(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxwwwbocx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hysaishi.cn/Article/details/gtvvbtuosc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.daxiang520.top/Article/details/gtjxmctrtx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.chenzaomai.com/Article/details/gtlnmenbiz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jianghu66.top/Article/details/gtueptqutp.html

C#:   async Task F() { await G(); }
来源：http://dali.sxryk.cn/Article/details/gtqitjutnf.html

[O05] 并发执行并等待全部完成
来源：http://dali.aibaodan.cn/Article/details/gtnalocxpb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.daria6918.cn/Article/details/gtzjthqjhr.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yj202588.top/Article/details/gttvhcymdy.html

JS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpxflwbep.html

TS:   await Promise.all(tasks)
来源：http://dali.ybcxt.top/Article/details/gtzwwonbce.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.smart0.xyz/Article/details/gtunhrbobr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.0kj1m.cn/Article/details/gtfrncuyey.html

Ruby: threads.map(&:join)
来源：http://dali.feifeiyinyue.top/Article/details/gtvelzjbte.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yonumen.top/Article/details/gtyndoqruc.html

[O06] 使用进程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwehlvnz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zycfv.cn/Article/details/gtvoadwrrh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.nanxinkj.top/Article/details/gtlvhcifie.html

JS:   // child_process / cluster 模块
来源：http://dali.c1oappe.top/Article/details/gttljqiqrv.html

TS:   // child_process / cluster 模块
来源：http://dali.mhx1999.top/Article/details/gtqmuyevda.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ivvv.top/Article/details/gtgvlsllxz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.chenzaomai.com/Article/details/gthotopqaf.html

Ruby: // fork 块
来源：http://dali.sxryk.cn/Article/details/gtuupfrafx.html

C#:   Parallel.For
来源：http://dali.havefunace.top/Article/details/gtsbjsmfmb.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtzjicfyrr.html

P. 常用工具函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtghlrrypf.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gthioqyrif.html

[P01] 生成 UUID
来源：http://dali.dianchejie.cn/Article/details/gtrhoiwqwn.html

Py:   str(uuid.uuid4())
来源：http://dali.zycfv.cn/Article/details/gtppomttlu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.pycfn.com/Article/details/gttfgffiib.html

JS:   crypto.randomUUID()
来源：http://dali.fzhhl.top/Article/details/gtxfxapvpi.html

TS:   crypto.randomUUID()
来源：http://dali.gzhubu.top/Article/details/gtlswjadch.html

Java: UUID.randomUUID().toString()
来源：http://dali.feifeiyinyue.top/Article/details/gtmtyymqcv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yvedp.cn/Article/details/gtgbdzzmqb.html

Ruby: SecureRandom.uuid
来源：http://dali.guowangkeji.top/Article/details/gtguabgtjh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cucudq.cn/Article/details/gtatvlwlqq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jlsjyb.cn/Article/details/gtnlrelsqs.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.guannengcc.top/Article/details/gtxgwpfkow.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.havefunace.top/Article/details/gtxmjkiufl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cheryme.top/Article/details/gtwtuapgqy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.nanxuanxn.top/Article/details/gteetbassi.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jinghuilouyu.cn/Article/details/gttwdwzrdp.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cdnleiting.top/Article/details/gtmyqqpfwa.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yuxming.cn/Article/details/gtbzlvgony.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.kuanghao11.cn/Article/details/gtodpxzpct.html

[P03] 生成短随机字符串
来源：http://dali.hfpthk.cn/Article/details/gtwxjkzhdh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zycfv.cn/Article/details/gtiduzijsc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cdnleiting.top/Article/details/gtedrxrmfq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yuxming.cn/Article/details/gtwnulauqs.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zycfv.cn/Article/details/gtljliqtjn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hongshengwenyu.top/Article/details/gtmkoeqeif.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.9152youxi.cn/Article/details/gtydpttynx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.tian-w.cn/Article/details/gtpgyeahej.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.chenzaomai.com/Article/details/gtidkhayss.html

[P04] 求长度
来源：http://dali.feifeiyinyue.top/Article/details/gthzzikeke.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkzlghrzg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gtbqrmziaa.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.wangshuangyany.cn/Article/details/gtyqlpsvtt.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jianghu66.top/Article/details/gtjitdpzvq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.tianlin.xyz/Article/details/gtpsknyfvf.html

Go:   len(arr);  len(m)
来源：http://dali.yvedp.cn/Article/details/gtjcwnwqvf.html

Ruby: x.length;  x.size
来源：http://dali.ivvv.top/Article/details/gtnjymylxc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.daria6918.cn/Article/details/gtbkcgkptz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ppjwa.cn/Article/details/gtlxmfgygt.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.redwolf501.top/Article/details/gtngowfaze.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.dianchejie.cn/Article/details/gtjnmzptwj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.aibaodan.cn/Article/details/gtjlcdqhlw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yueranfly.top/Article/details/gtkajbkopl.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cashguo.top/Article/details/gtxjdekloy.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.wangdashe.top/Article/details/gtzpckogvz.html

Ruby: a == b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjatsvepz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yvedp.cn/Article/details/gtmutsidgk.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinqigfzy.top/Article/details/gtvbygeuyw.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xinyue.icu/Article/details/gtvvkezqpl.html

PHP:  if (empty($x)) {}
来源：http://dali.fengsongda.top/Article/details/gtjjkgwhvy.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.guannengcc.top/Article/details/gthuflepiq.html

TS:   if (x == null) {}
来源：http://dali.zhongyouzk.top/Article/details/gtkfknjodp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.nwbrower.top/Article/details/gtrxgihblb.html

Go:   if x == nil {}
来源：http://dali.zdqjudy.top/Article/details/gtngsaumgh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.iojbl.cn/Article/details/gtzbhjiops.html

C#:   if (x is null) {}
来源：http://dali.c1oappe.top/Article/details/gtvdrckabp.html

[P07] 防抖与节流
来源：http://dali.gzhubu.top/Article/details/gtjhldwnbe.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shangyingyoupin.top/Article/details/gtegjezrid.html

PHP:  // 手写时间戳比较
来源：http://dali.jlsjyb.cn/Article/details/gtvjpqgsoa.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuanzx.com/Article/details/gtimirkjmm.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258.top/Article/details/gtjepzhpvg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.redwolf501.top/Article/details/gthuvttexr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.pycfn.com/Article/details/gtfqkrrlxa.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nanxinkj.top/Article/details/gtutwzenqr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.guowangkeji.top/Article/details/gtearsqgrx.html

[P08] 处理浮点精度问题
来源：http://dali.svipenyu.cn/Article/details/gtinegqwow.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.sweek.top/Article/details/gtbjyrmqve.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hammf.cn/Article/details/gtdprohuun.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sysykeji.top/Article/details/gtjumnjwys.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtflvgwsix.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hfpthk.cn/Article/details/gtxvpfdtas.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cqqwz.cn/Article/details/gtvqoixftl.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.svipenyu.cn/Article/details/gtuqpmdnjt.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.fengsongda.top/Article/details/gtbfbhzuxo.html


<!-- 参考信息 -->