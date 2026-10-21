代发 wailian999

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yongpay.top/Article/details/gtpvxqekvr.html

Ruby: ENV["HOME"]
来源：http://dali.gaohongyu789.top/Article/details/gtlhmljslv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtyrickcvr.html

[M03] 执行外部命令
来源：http://dali.hfpthk.cn/Article/details/gtzmpmqcsi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jlsjyb.cn/Article/details/gtmdebirwe.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gaohongyu789.top/Article/details/gthmmsmjtb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.dianchejie.cn/Article/details/gtayhiodjs.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hywenlv.cn/Article/details/gteumuafnv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.vqdsnc.cn/Article/details/gtbrmlihzd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zdqjudy.top/Article/details/gtrgomafuy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.redwolf501.top/Article/details/gtwpzwglbf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yuxming.cn/Article/details/gtsiyrxrbm.html

[M04] 获取当前工作目录
来源：http://dali.jiagoushi.top/Article/details/gtapdtjlas.html

Py:   os.getcwd()
来源：http://dali.bjfxy.top/Article/details/gtehhadsoz.html

PHP:  getcwd();
来源：http://dali.shuidangran.top/Article/details/gtryydjuhe.html

JS:   process.cwd()
来源：http://dali.pengpengdd.cyou/Article/details/gthjswwyiw.html

TS:   process.cwd()
来源：http://dali.yuanzhike.top/Article/details/gtxlcrrixl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hfpthk.cn/Article/details/gtfhzscvqs.html

Go:   os.Getwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtficjvfnf.html

Ruby: Dir.pwd
来源：http://dali.xinyue.icu/Article/details/gtjdpftjac.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhongyouzk.top/Article/details/gthvdmxyjh.html

[M05] 设置退出码
来源：http://dali.wangdashe.top/Article/details/gtjbjlxjyq.html

Py:   sys.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gtuckjzxqq.html

PHP:  exit(1);
来源：http://dali.yonumen.top/Article/details/gtnnuomywh.html

JS:   process.exit(1)
来源：http://dali.nwbrower.top/Article/details/gtctnykrpp.html

TS:   process.exit(1)
来源：http://dali.jianghu66.top/Article/details/gtcypjghak.html

Java: System.exit(1)
来源：http://dali.wangdashe.top/Article/details/gthhufaomo.html

Go:   os.Exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpdylhqxt.html

Ruby: exit 1
来源：http://dali.ehwqpu.com/Article/details/gthcvhnbze.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.daxiang520.top/Article/details/gtdkczfpsz.html

[M06] 向标准错误输出
来源：http://dali.shuidangran.top/Article/details/gtlsootfvn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ivvv.top/Article/details/gtpngrblvh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yvedp.cn/Article/details/gtolpesggg.html

JS:   console.error("err")
来源：http://dali.fzhhl.top/Article/details/gtsekwcudo.html

TS:   console.error("err")
来源：http://dali.sufxvd.cn/Article/details/gtostrhesd.html

Java: System.err.println("err")
来源：http://dali.hongshengwenyu.top/Article/details/gtagzjzxxn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sxryk.cn/Article/details/gtofvynqvr.html

Ruby: warn "err"
来源：http://dali.hnqzz.top/Article/details/gtrcuzzkxl.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xuanzx.com/Article/details/gtrdwobhnv.html

[M07] 判断是否为主入口
来源：http://dali.jinqigufen.top/Article/details/gtlljfgosq.html

Py:   if __name__ == "__main__":
来源：http://dali.yuanzhike.top/Article/details/gtdlerosfj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ppjwa.cn/Article/details/gtcmiivsyq.html

JS:   require.main === module
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfycycesg.html

TS:   require.main === module
来源：http://dali.yangfankeji.com/Article/details/gtkskzhkfv.html

Java: public static void main(String[] args)
来源：http://dali.svipenyu.cn/Article/details/gtjatezwvq.html

Go:   func main()
来源：http://dali.ehwqpu.com/Article/details/gtykdugihx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhixingplan.top/Article/details/gtefxahvvu.html

C#:   static void Main(string[] args)
来源：http://dali.gotoacloud.top/Article/details/gtdwddbbcq.html

[M08] 获取系统与运行时信息
来源：http://dali.pengpengdd.cyou/Article/details/gtacmlutkd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.chenzaomai.com/Article/details/gtjwcnxcrl.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.kuanghao11.cn/Article/details/gtksznzxho.html

JS:   process.platform;  process.version
来源：http://dali.yongpay.top/Article/details/gtubgjixic.html

TS:   process.platform;  process.version
来源：http://dali.meibo888.top/Article/details/gtrkxqnmcf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hywenlv.cn/Article/details/gttciodjfj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.pycfn.com/Article/details/gtmnwmmpad.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinghuilouyu.cn/Article/details/gtbrkwtpmu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.havefunace.top/Article/details/gttbhkzgtq.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtygsmhdui.html

N. 数据结构与算法
来源：http://dali.pengpengdd.cyou/Article/details/gtbbesuizj.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtvirhqyvy.html

[N01] 二分查找（有序数组）
来源：http://dali.pycfn.com/Article/details/gturtjhbaw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtlzamnukc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gtyipxpulk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoirzecvk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pengpengdd.cyou/Article/details/gtfyuxholr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gtancdpujt.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtjclrbcxx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jianghu66.top/Article/details/gtcleocyuv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlwjykvos.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhongyouzk.top/Article/details/gtuzndjmie.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.haohaochexian.top/Article/details/gtyevcjkrm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xylfe.cn/Article/details/gtrtptjsem.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jlsjyb.cn/Article/details/gtjdvsgczj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenzaomai.com/Article/details/gtbylqvquv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ybcxt.top/Article/details/gtvrvlczuq.html

Go:   slices.Sort(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtyubzgyux.html

Ruby: arr.sort
来源：http://dali.yuanzhike.top/Article/details/gtnqvaoryn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ybcxt.top/Article/details/gtmkrlqutn.html

[N03] 快速排序（分治示例）
来源：http://dali.ivvv.top/Article/details/gtbmdrhzia.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ppjwa.cn/Article/details/gtuwxfhnen.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ybcxt.top/Article/details/gtwawragxf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pengpengdd.cyou/Article/details/gthlslvbaj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sxryk.cn/Article/details/gtbrbahksx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shanyushiyangtech.top/Article/details/gtwzbkxvgg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.iojbl.cn/Article/details/gtyeevmdnn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.nanxinkj.top/Article/details/gtftuwjbkf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hfpthk.cn/Article/details/gtcjhxdtjf.html

[N04] 斐波那契数列
来源：http://dali.zdqjudy.top/Article/details/gtzlrerqmj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.9152youxi.cn/Article/details/gtvjyohghr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sxryk.cn/Article/details/gtpjecjgal.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnqzz.top/Article/details/gtlprjiksr.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gtisnsfibu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jqgufenzy.top/Article/details/gtjuibphpj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.c1oappe.top/Article/details/gtgppsvcpd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yongpay.top/Article/details/gtqpedffbt.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgykrdbxt.html

[N05] 最大公约数
来源：http://dali.hfpthk.cn/Article/details/gtkcsjvdkq.html

Py:   math.gcd(a, b)
来源：http://dali.gzhubu.top/Article/details/gtihtutxuw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.andypj.xyz/Article/details/gtnevpwkho.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.iojbl.cn/Article/details/gtdpamacaf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.iojbl.cn/Article/details/gtemkyppma.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yangfankeji.com/Article/details/gtrbghrndb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.tanke756.top/Article/details/gtxyiywqrz.html

Ruby: a.gcd(b)
来源：http://dali.chenlongwang.top/Article/details/gtjnmfvsoe.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.quarkkingdee.top/Article/details/gtvsiepess.html

[N06] 判断回文字符串
来源：http://dali.gotoacloud.top/Article/details/gtymqsolbw.html

Py:   s == s[::-1]
来源：http://dali.shzxlz.cn/Article/details/gtmstwwhow.html

PHP:  $s === strrev($s);
来源：http://dali.snrcjt.cn/Article/details/gtsezzpwgi.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gtgmijjbvr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gtnajaodoz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinghuilouyu.cn/Article/details/gtudjoljkb.html

Go:   // 双指针从两端比较
来源：http://dali.shanyushiyangtech.top/Article/details/gthuncrymb.html

Ruby: s == s.reverse
来源：http://dali.yuxming.cn/Article/details/gtykehmuow.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.iojbl.cn/Article/details/gtwiearjln.html

[N07] 两数之和（返回下标）
来源：http://dali.yangfankeji.com/Article/details/gtihwzbijk.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sufxvd.cn/Article/details/gtgprhfpzt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hongshengwenyu.top/Article/details/gtoohhanqi.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.svipenyu.cn/Article/details/gttayjaxvz.html

TS:   // 手写 Map<string, number>
来源：http://dali.nwbrower.top/Article/details/gtwooqfpvr.html

Java: // 手写 HashMap
来源：http://dali.vqdsnc.cn/Article/details/gtumnhfcbn.html

Go:   // 手写 map[int]int
来源：http://dali.tian-w.cn/Article/details/gtoxsgyrad.html

Ruby: // 手写 Hash
来源：http://dali.chenjidiqi.icu/Article/details/gtsrhiuitb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ivvv.top/Article/details/gthjbzjhny.html

[N08] 生成全排列
来源：http://dali.hnxiangtu.top/Article/details/gtkgabvrzw.html

Py:   itertools.permutations(arr)
来源：http://dali.yangfankeji.com/Article/details/gtdcbhujwb.html

PHP:  // 手写递归交换
来源：http://dali.zhongyouzk.top/Article/details/gtkeccbpep.html

JS:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gtclgcnrdz.html

TS:   // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gtbeeqyydf.html

Java: // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gtgskovikt.html

Go:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gtkoxlkqyi.html

Ruby: arr.permutation.to_a
来源：http://dali.c1oappe.top/Article/details/gtfolhgwrq.html

C#:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtxvuugoop.html

[N09] 栈与队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzipwruwc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.c1oappe.top/Article/details/gtzkqxnmsj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.tanke756.top/Article/details/gtwcuwtzyz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hammf.cn/Article/details/gtyysoqjxf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.kuanghao11.cn/Article/details/gtakbycwcp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ybcxt.top/Article/details/gtjqynxikq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yj20258888.top/Article/details/gtrglwbfgm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.tanke756.top/Article/details/gtaohjxrve.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj20258.top/Article/details/gtrsunnlmi.html

[N10] 链表节点定义
来源：http://dali.9152youxi.cn/Article/details/gtamoztzpk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.daxiang520.top/Article/details/gtftbebpbj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.aibaodan.cn/Article/details/gtkypbkbon.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.chenjidiqi.icu/Article/details/gtaipiqaze.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.quarkkingdee.top/Article/details/gtrvjoysck.html

Java: class Node { int v; Node next; }
来源：http://dali.guowangkeji.top/Article/details/gtsdmtxruj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yonumen.top/Article/details/gtxzohfrpy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.andypj.xyz/Article/details/gtjbxidela.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gotoacloud.top/Article/details/gthzbgptcf.html

[N11] 二叉树中序遍历
来源：http://dali.yongpay.top/Article/details/gtwgbgtxor.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhoulong.xyz/Article/details/gtlijtgtax.html

PHP:  // 手写递归函数
来源：http://dali.jinqigufen.top/Article/details/gtjyzbwmox.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.wangdashe.top/Article/details/gtzvzwrptc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yueranfly.top/Article/details/gtkaxasvey.html

Java: // 手写递归
来源：http://dali.wangdashe.top/Article/details/gtawpqhdlt.html

Go:   // 手写递归
来源：http://dali.316326.xyz/Article/details/gtgcwhhdqc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.iojbl.cn/Article/details/gtrezshlzc.html

C#:   // 手写递归
来源：http://dali.shangyingyoupin.top/Article/details/gtnousmbmn.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gzhubu.top/Article/details/gtigywnzka.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yonumen.top/Article/details/gteixfyrpl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yanxiufei.cn/Article/details/gtuxohbxow.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ydzc1.top/Article/details/gtbtlkqnnl.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cheryme.top/Article/details/gtfgqtzyrg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuetiantiany.cn/Article/details/gtotqgpcwm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jqgfzy.top/Article/details/gtpkkisanr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.redwolf501.top/Article/details/gtyyhqxvqd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yueranfly.top/Article/details/gtrsbtieiz.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtztjrprqy.html

O. 并发与异步
来源：http://dali.ppjwa.cn/Article/details/gtcpuyloai.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtxqpaudax.html

[O01] 启动一个线程
来源：http://dali.zhaomingkeji.xyz/Article/details/gtphwbxjnp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.nanxinkj.top/Article/details/gthiqiipvw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yuxming.cn/Article/details/gtggmnggxw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yangfankeji.com/Article/details/gtlzqdlohv.html

TS:   // 同 JS
来源：http://dali.cucudq.cn/Article/details/gtwsgsejwv.html

Java: new Thread(() -> f()).start()
来源：http://dali.yvedp.cn/Article/details/gtpyxsofpm.html

Go:   go f()
来源：http://dali.xuetiantiany.cn/Article/details/gtxtybqwou.html

Ruby: Thread.new { f }
来源：http://dali.cdnleiting.top/Article/details/gtlrqjsjcf.html

C#:   Task.Run(() => F());
来源：http://dali.yj20258888.top/Article/details/gtvsmvtpgj.html

[O02] 使用线程池
来源：http://dali.chenjidiqi.icu/Article/details/gtmygsjtxp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xinyue.icu/Article/details/gtssduzhhv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.iojbl.cn/Article/details/gtgwzwwqqq.html

JS:   // worker_threads 线程池
来源：http://dali.c1oappe.top/Article/details/gtjpvicvaw.html

TS:   // worker_threads 线程池
来源：http://dali.hammf.cn/Article/details/gtseffsvfu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.aizwys.cn/Article/details/gtqhseemvg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ybcxt.top/Article/details/gtfrobrize.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ydzc1.top/Article/details/gtztycmwrk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnxxnuvbh.html

[O03] 加锁保护共享数据
来源：http://dali.yanxiufei.cn/Article/details/gtyenvbwym.html

Py:   with lock: shared += 1
来源：http://dali.pycfn.com/Article/details/gtzjnfpgfy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.havefunace.top/Article/details/gtfuftbgjv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.tian-w.cn/Article/details/gtpqiweprn.html

TS:   // 同 JS
来源：http://dali.zhoulong.xyz/Article/details/gtsgdbwynu.html

Java: synchronized (this) { shared++; }
来源：http://dali.yj202588.top/Article/details/gtcnfmkuhu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hfpthk.cn/Article/details/gtzewrzapq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.aizwys.cn/Article/details/gtdfnhacyp.html

C#:   lock (gate) { shared++; }
来源：http://dali.havefunace.top/Article/details/gtjwksaoby.html

[O04] 定义异步函数并等待
来源：http://dali.jqgfzy.top/Article/details/gtdqnwfqko.html

Py:   async def f():⏎    await g()
来源：http://dali.sweek.top/Article/details/gtwwwfuwvd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvcpawabm.html

JS:   async function f() { await g(); }
来源：http://dali.sweek.top/Article/details/gtnqwtokhr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jqgfzy.top/Article/details/gtlwkaziio.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.havefunace.top/Article/details/gttfcdmmlb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.316326.xyz/Article/details/gtryyrakzt.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.daxiang520.top/Article/details/gtkqlbkirh.html

C#:   async Task F() { await G(); }
来源：http://dali.chenzaomai.com/Article/details/gtjsfcqaox.html

[O05] 并发执行并等待全部完成
来源：http://dali.hywenlv.cn/Article/details/gtvhbjpgua.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jyoumei.cn/Article/details/gtdywfwddq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.bjfxy.top/Article/details/gttvytvqmc.html

JS:   await Promise.all(tasks)
来源：http://dali.ybcxt.top/Article/details/gtldqlrcop.html

TS:   await Promise.all(tasks)
来源：http://dali.shuidangran.top/Article/details/gtdncfjomr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xziqi.cn/Article/details/gtilixwujj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.iojbl.cn/Article/details/gtvlpjikuf.html

Ruby: threads.map(&:join)
来源：http://dali.pycfn.com/Article/details/gtkbbymjhd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.iojbl.cn/Article/details/gtdicfxarr.html

[O06] 使用进程池
来源：http://dali.wangdashe.top/Article/details/gtqhifnbqx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yuxming.cn/Article/details/gtxmhftzpk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hnqzz.top/Article/details/gtuaejmpob.html

JS:   // child_process / cluster 模块
来源：http://dali.sysykeji.top/Article/details/gtqrsylyxb.html

TS:   // child_process / cluster 模块
来源：http://dali.jianghu66.top/Article/details/gtibluthmb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.chenlongwang.top/Article/details/gtdrzdskis.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tian-w.cn/Article/details/gtnqmmznwk.html

Ruby: // fork 块
来源：http://dali.quarkkingdee.top/Article/details/gtkhuqhamr.html

C#:   Parallel.For
来源：http://dali.zhengqikj.top/Article/details/gtbrbdflhy.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtvzsnacng.html

P. 常用工具函数
来源：http://dali.cheryme.top/Article/details/gtwctcubfo.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gttgbgemjf.html

[P01] 生成 UUID
来源：http://dali.xylfe.cn/Article/details/gtiaixjymd.html

Py:   str(uuid.uuid4())
来源：http://dali.hongshengwenyu.top/Article/details/gtxkqhnpxg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.svipenyu.cn/Article/details/gtdumdhqbj.html

JS:   crypto.randomUUID()
来源：http://dali.nwbrower.top/Article/details/gtxzixtfzr.html

TS:   crypto.randomUUID()
来源：http://dali.jqgufenzy.top/Article/details/gtxtpsawxs.html

Java: UUID.randomUUID().toString()
来源：http://dali.tanke756.top/Article/details/gtrxuezwge.html

Go:   // 用 github.com/google/uuid
来源：http://dali.c1oappe.top/Article/details/gttdnrinlb.html

Ruby: SecureRandom.uuid
来源：http://dali.gaohongyu789.top/Article/details/gtuqppfqdq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.redwolf501.top/Article/details/gtsakickca.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jqgufenzy.top/Article/details/gtwxdarpxw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.quarkkingdee.top/Article/details/gtxuphxdqp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shzxlz.cn/Article/details/gtjxqmzyem.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xylfe.cn/Article/details/gtvzwvipjo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.316326.xyz/Article/details/gtkebdicep.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yonumen.top/Article/details/gtdxutlycy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.tianlin.xyz/Article/details/gtmzukehlr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtynxnllud.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzrdbiquf.html

[P03] 生成短随机字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtsqsrqidz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.sweek.top/Article/details/gtkpwppxqn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cdnleiting.top/Article/details/gtsssurbjz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ivvv.top/Article/details/gtuakbdaug.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yanxiufei.cn/Article/details/gtcesgwhxc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ehwqpu.com/Article/details/gtvhtwgknk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.andypj.xyz/Article/details/gteufqskrg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.tian-w.cn/Article/details/gtspgjwxse.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.havefunace.top/Article/details/gtyffovhtj.html

[P04] 求长度
来源：http://dali.ybcxt.top/Article/details/gthohxyrua.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jiagoushi.top/Article/details/gtkdguiiln.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gtxtjadfao.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangtech.top/Article/details/gtyasvaboo.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xuetiantiany.cn/Article/details/gtieaedgop.html

Java: list.size();  map.size();  s.length()
来源：http://dali.chenzaomai.com/Article/details/gtxhkpqlre.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gtgebcxrjf.html

Ruby: x.length;  x.size
来源：http://dali.xinyue.icu/Article/details/gtjtdbvrau.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yuxming.cn/Article/details/gtikwrkchq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.vqdsnc.cn/Article/details/gtrxoovbvq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.pengpengdd.cyou/Article/details/gttnfkslcs.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hfpthk.cn/Article/details/gtffxuejek.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.svipenyu.cn/Article/details/gtaszzhxke.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tanke756.top/Article/details/gtuvdbmdss.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ivvv.top/Article/details/gtyjnuoptt.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.tanke756.top/Article/details/gtbqqywkav.html

Ruby: a == b
来源：http://dali.nanxinkj.top/Article/details/gtfzkuyrxm.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hysaishi.cn/Article/details/gtvznyyoev.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ehwqpu.com/Article/details/gtztbhtkql.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlsouytkn.html

PHP:  if (empty($x)) {}
来源：http://dali.nwbrower.top/Article/details/gtjrfxirei.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xziqi.cn/Article/details/gtbbosiysc.html

TS:   if (x == null) {}
来源：http://dali.jianghu66.top/Article/details/gtnfqacvdn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yj202588.top/Article/details/gtfwlheyvl.html

Go:   if x == nil {}
来源：http://dali.316326.xyz/Article/details/gtybvrdzbx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jiagoushi.top/Article/details/gtajsenzmm.html

C#:   if (x is null) {}
来源：http://dali.cashguo.top/Article/details/gtdglovyhp.html

[P07] 防抖与节流
来源：http://dali.havefunace.top/Article/details/gtwhkyfldy.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jqgfzy.top/Article/details/gtxmvzpqjw.html

PHP:  // 手写时间戳比较
来源：http://dali.xuetiantiany.cn/Article/details/gtivsacfuy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gttuxtqyjb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhiwuduotai.top/Article/details/gttaydnpqx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yanxiufei.cn/Article/details/gtjtmeguco.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.gotoacloud.top/Article/details/gtflrmkxex.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hysaishi.cn/Article/details/gtddomrymi.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gogol.net.cn/Article/details/gtrlgcvkky.html

[P08] 处理浮点精度问题
来源：http://dali.vqdsnc.cn/Article/details/gtqfzysntb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.nwbrower.top/Article/details/gtebgtkpjq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.vqdsnc.cn/Article/details/gtemyudplb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cdnleiting.top/Article/details/gtkhjwooer.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.svipenyu.cn/Article/details/gtwuvmtdax.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.tian-w.cn/Article/details/gtztodyhom.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.sxryk.cn/Article/details/gtbidanxfb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hfpthk.cn/Article/details/gtdejdvdqk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.aizwys.cn/Article/details/gtbrysbnja.html


<!-- 参考信息 -->