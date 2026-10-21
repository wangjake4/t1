代发 wailian999

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ydzc1.top/Article/details/gtklhlenxc.html

Ruby: ENV["HOME"]
来源：http://dali.redwolf501.top/Article/details/gtftmxpvds.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jiagoushi.top/Article/details/gtkspktniq.html

[M03] 执行外部命令
来源：http://dali.cucudq.cn/Article/details/gtmkjbsidj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhoulong.xyz/Article/details/gthqkfwhzs.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhixingplan.top/Article/details/gthtgtdezo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.bjfxy.top/Article/details/gtcitdbakv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.vqdsnc.cn/Article/details/gtjifytyfr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hnxiangtu.top/Article/details/gtyixwmbrs.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gzhubu.top/Article/details/gtyujblgug.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yj20258888.top/Article/details/gtvhkbauog.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sxryk.cn/Article/details/gtopkcxgon.html

[M04] 获取当前工作目录
来源：http://dali.ivvv.top/Article/details/gteyzucrtx.html

Py:   os.getcwd()
来源：http://dali.hysaishi.cn/Article/details/gtmdmlkjax.html

PHP:  getcwd();
来源：http://dali.nanxinkj.top/Article/details/gterbgeaxn.html

JS:   process.cwd()
来源：http://dali.jinqigfzy.top/Article/details/gticbtbzwh.html

TS:   process.cwd()
来源：http://dali.hnqzz.top/Article/details/gtybrrfoov.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gtrfcibeiw.html

Go:   os.Getwd()
来源：http://dali.guannengcc.top/Article/details/gtlrzopvkt.html

Ruby: Dir.pwd
来源：http://dali.smart0.xyz/Article/details/gtnvkqizzk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jqgfzy.top/Article/details/gtitnjgoft.html

[M05] 设置退出码
来源：http://dali.birdmap.top/Article/details/gtfvsmudrz.html

Py:   sys.exit(1)
来源：http://dali.birdmap.top/Article/details/gtqivoffcr.html

PHP:  exit(1);
来源：http://dali.0kj1m.cn/Article/details/gtwmkniqzs.html

JS:   process.exit(1)
来源：http://dali.cheryme.top/Article/details/gtsijzjkxo.html

TS:   process.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgojbhwqx.html

Java: System.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtkcgfbjnl.html

Go:   os.Exit(1)
来源：http://dali.tanke756.top/Article/details/gtpmofinwh.html

Ruby: exit 1
来源：http://dali.sufxvd.cn/Article/details/gtvbbgaaqr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.svipenyu.cn/Article/details/gtbwitfebh.html

[M06] 向标准错误输出
来源：http://dali.wangdashe.top/Article/details/gtlcjjckig.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ivvv.top/Article/details/gtzdnuesiv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ybcxt.top/Article/details/gtfbxtexkb.html

JS:   console.error("err")
来源：http://dali.jinqigufen.top/Article/details/gtssrxftcq.html

TS:   console.error("err")
来源：http://dali.tian-w.cn/Article/details/gtftkwnybe.html

Java: System.err.println("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjupzoorp.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.dashuyun.cn/Article/details/gtxycuuetj.html

Ruby: warn "err"
来源：http://dali.jyoumei.cn/Article/details/gtlugdeyio.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xuanzx.com/Article/details/gtjvchfvkp.html

[M07] 判断是否为主入口
来源：http://dali.jiagoushi.top/Article/details/gttshffjiy.html

Py:   if __name__ == "__main__":
来源：http://dali.zdqjudy.top/Article/details/gtsluaeroq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yuxming.cn/Article/details/gtaappszxt.html

JS:   require.main === module
来源：http://dali.gzhubu.top/Article/details/gtiyylfqnw.html

TS:   require.main === module
来源：http://dali.jlsjyb.cn/Article/details/gttgyjplsa.html

Java: public static void main(String[] args)
来源：http://dali.shzxlz.cn/Article/details/gtckrqvqfp.html

Go:   func main()
来源：http://dali.0kj1m.cn/Article/details/gtcfpoqedf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sysykeji.top/Article/details/gtfsxrskew.html

C#:   static void Main(string[] args)
来源：http://dali.yj20258.top/Article/details/gtbjxdejrk.html

[M08] 获取系统与运行时信息
来源：http://dali.tanke756.top/Article/details/gttrtnfmmf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.mhx1999.top/Article/details/gtniezilcs.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.tianlin.xyz/Article/details/gttmcefgud.html

JS:   process.platform;  process.version
来源：http://dali.daxiang520.top/Article/details/gtxxyeltga.html

TS:   process.platform;  process.version
来源：http://dali.shuidangran.top/Article/details/gtxljbehyh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.chenlongwang.top/Article/details/gtrujkmbjr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xuetiantiany.cn/Article/details/gtshvknvyl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinqigufen.top/Article/details/gtmdpsmfym.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cdnleiting.top/Article/details/gtsyphmvxm.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gthcsqkwrx.html

N. 数据结构与算法
来源：http://dali.jlsjyb.cn/Article/details/gtcrdrhafu.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtioikfozi.html

[N01] 二分查找（有序数组）
来源：http://dali.zhongyouzk.top/Article/details/gtuxbbyygj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtcvrjfkrw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jianghu66.top/Article/details/gtbvwqotgi.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zdqjudy.top/Article/details/gtdftgywyv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hywenlv.cn/Article/details/gtlxnpecda.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxacdezpt.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtgzgdqqdx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.316326.xyz/Article/details/gtqbaebfqv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtvhjpalgx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xziqi.cn/Article/details/gthcnibkxc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jianghu66.top/Article/details/gtkxhehuae.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jqgfzy.top/Article/details/gtsvejdanp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.bjfxy.top/Article/details/gtciqrldle.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjejjcsno.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.dianchejie.cn/Article/details/gtceagdkee.html

Go:   slices.Sort(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtsupxlroc.html

Ruby: arr.sort
来源：http://dali.xuetiantiany.cn/Article/details/gthjgfdhbt.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yanxiufei.cn/Article/details/gtvtvhtpuq.html

[N03] 快速排序（分治示例）
来源：http://dali.hysaishi.cn/Article/details/gtrqbqyqyt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yanxiufei.cn/Article/details/gtcehjpvcp.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yongpay.top/Article/details/gtpzvrqzmh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shuidangran.top/Article/details/gtvbvmfhgn.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yonumen.top/Article/details/gtxxrlmjnv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtktboxtlm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xuanzx.com/Article/details/gtksumwnbf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.0kj1m.cn/Article/details/gtlylgjrrq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yj202588.top/Article/details/gtwoldrawr.html

[N04] 斐波那契数列
来源：http://dali.shuidangran.top/Article/details/gtfccbahmd.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cheryme.top/Article/details/gtsmdostvw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gtvixivkqp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gtskyvygxb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gtuwmidpdh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.nanxuanxn.top/Article/details/gtwkvvuhza.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.guannengcc.top/Article/details/gtkbeamxft.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.fzhhl.top/Article/details/gtwlfgabgf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jqgufenzy.top/Article/details/gtgzdiotfi.html

[N05] 最大公约数
来源：http://dali.hnqzz.top/Article/details/gtrhjaiqzx.html

Py:   math.gcd(a, b)
来源：http://dali.gzhubu.top/Article/details/gtczkxbkxj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cashguo.top/Article/details/gthdmfydio.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zdqjudy.top/Article/details/gtfoturmil.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dashuyun.cn/Article/details/gtferyepni.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.316326.xyz/Article/details/gtxgvsvjnk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yj202588.top/Article/details/gtcumwzmih.html

Ruby: a.gcd(b)
来源：http://dali.xuetiantiany.cn/Article/details/gtlevojwfb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtojhdkydx.html

[N06] 判断回文字符串
来源：http://dali.guannengcc.top/Article/details/gtwksgtsso.html

Py:   s == s[::-1]
来源：http://dali.jinqigufen.top/Article/details/gtdflnqnbl.html

PHP:  $s === strrev($s);
来源：http://dali.tianlin.xyz/Article/details/gtkxfiicce.html

JS:   s === [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gtokubaang.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gtoghbtcio.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sweek.top/Article/details/gthqtamizs.html

Go:   // 双指针从两端比较
来源：http://dali.yj20258.top/Article/details/gtdycoiogv.html

Ruby: s == s.reverse
来源：http://dali.feifeiyinyue.top/Article/details/gtxmcoahpt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gotoacloud.top/Article/details/gtopvpttfc.html

[N07] 两数之和（返回下标）
来源：http://dali.daxiang520.top/Article/details/gtlkkwilve.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.bjfxy.top/Article/details/gtaecgfmjh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hywenlv.cn/Article/details/gtbmweysuc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ivvv.top/Article/details/gtwvzwpepe.html

TS:   // 手写 Map<string, number>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmucqdmrx.html

Java: // 手写 HashMap
来源：http://dali.jqgfzy.top/Article/details/gtwzsxfhxj.html

Go:   // 手写 map[int]int
来源：http://dali.sufxvd.cn/Article/details/gtifbgholv.html

Ruby: // 手写 Hash
来源：http://dali.aibaodan.cn/Article/details/gtckjqermd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.nwbrower.top/Article/details/gtcdzevfpc.html

[N08] 生成全排列
来源：http://dali.mhx1999.top/Article/details/gteminnviq.html

Py:   itertools.permutations(arr)
来源：http://dali.guannengcc.top/Article/details/gtgrgsqfso.html

PHP:  // 手写递归交换
来源：http://dali.yj202588.top/Article/details/gtjeodyiax.html

JS:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gtopozpius.html

TS:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gtjjgwslky.html

Java: // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtwkzrvdcp.html

Go:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gtrakpadzw.html

Ruby: arr.permutation.to_a
来源：http://dali.fengsongda.top/Article/details/gtpyljnuuv.html

C#:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gtzsszvukx.html

[N09] 栈与队列
来源：http://dali.yangfankeji.com/Article/details/gtczcceiok.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gtfbylqoug.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sweek.top/Article/details/gtludrrffe.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.tianlin.xyz/Article/details/gtqccworrq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yonumen.top/Article/details/gtvnfkvopk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.nanxuanxn.top/Article/details/gtwospwijh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yvedp.cn/Article/details/gtcsdlzpua.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zdqjudy.top/Article/details/gteyewtccz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xylfe.cn/Article/details/gtmqbazmto.html

[N10] 链表节点定义
来源：http://dali.shuidangran.top/Article/details/gthtbbsucr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.birdmap.top/Article/details/gtedvsxfno.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gogol.net.cn/Article/details/gtuifnhybu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.fzhhl.top/Article/details/gtydtnrkio.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cheryme.top/Article/details/gtevnitmri.html

Java: class Node { int v; Node next; }
来源：http://dali.cqqwz.cn/Article/details/gtqnpvslra.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzolzgxob.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sufxvd.cn/Article/details/gthffrkpiq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.redwolf501.top/Article/details/gtuohwnlfh.html

[N11] 二叉树中序遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlnokihdl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yj202588.top/Article/details/gtwfhjalpm.html

PHP:  // 手写递归函数
来源：http://dali.jianghu66.top/Article/details/gtctxjvoeu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xylfe.cn/Article/details/gtalxplijc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daria6918.cn/Article/details/gtvzgqrghj.html

Java: // 手写递归
来源：http://dali.mhx1999.top/Article/details/gtzecxqkoe.html

Go:   // 手写递归
来源：http://dali.shangyingyoupin.top/Article/details/gtdltgukjc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.nwbrower.top/Article/details/gtmmblmght.html

C#:   // 手写递归
来源：http://dali.svipenyu.cn/Article/details/gttoqtiejo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jiagoushi.top/Article/details/gtqyexvoya.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.tanke756.top/Article/details/gtmpjxbqrg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhengqikj.top/Article/details/gtqgzcenyr.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.bjfxy.top/Article/details/gtxaoipqbx.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenzaomai.com/Article/details/gtaoopemns.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hnxiangtu.top/Article/details/gtfihyisjq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinqigufen.top/Article/details/gttcjcjzlt.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.c1oappe.top/Article/details/gtzzhxsufb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nanxuanxn.top/Article/details/gtfzhjgyrv.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtvucvyiaz.html

O. 并发与异步
来源：http://dali.zhaomingkeji.xyz/Article/details/gtylmbkisj.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtolvaxaqc.html

[O01] 启动一个线程
来源：http://dali.tianlin.xyz/Article/details/gtdtafzyfg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sxryk.cn/Article/details/gtccfqzzja.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yuanzhike.top/Article/details/gtpbyspcig.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.birdmap.top/Article/details/gthjzccfuw.html

TS:   // 同 JS
来源：http://dali.daria6918.cn/Article/details/gtjczbwtaq.html

Java: new Thread(() -> f()).start()
来源：http://dali.yj202588.top/Article/details/gtazxkenvb.html

Go:   go f()
来源：http://dali.hywenlv.cn/Article/details/gtjfdktcko.html

Ruby: Thread.new { f }
来源：http://dali.chenlongwang.top/Article/details/gtnvdcetxo.html

C#:   Task.Run(() => F());
来源：http://dali.yj20258888.top/Article/details/gtmsjyfvmu.html

[O02] 使用线程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdqsasweh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xziqi.cn/Article/details/gtmmrdfncc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gttpgxmchf.html

JS:   // worker_threads 线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gtmeaetmuk.html

TS:   // worker_threads 线程池
来源：http://dali.pengpengdd.cyou/Article/details/gtvauiedza.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xuanzx.com/Article/details/gtqlserwke.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sufxvd.cn/Article/details/gtsxjvwepy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfseopctx.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yangfankeji.com/Article/details/gtxmwsacby.html

[O03] 加锁保护共享数据
来源：http://dali.zdqjudy.top/Article/details/gthzjxwiej.html

Py:   with lock: shared += 1
来源：http://dali.smart0.xyz/Article/details/gtfzpkdyns.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.haohaochexian.top/Article/details/gtdpgzqfpe.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkmqwfhot.html

TS:   // 同 JS
来源：http://dali.shanyushiyangtech.top/Article/details/gtwgsrlrzo.html

Java: synchronized (this) { shared++; }
来源：http://dali.cqqwz.cn/Article/details/gtallgqylh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cqqwz.cn/Article/details/gtomydspxb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zdqjudy.top/Article/details/gtagyqrxox.html

C#:   lock (gate) { shared++; }
来源：http://dali.nwbrower.top/Article/details/gtnaungmvb.html

[O04] 定义异步函数并等待
来源：http://dali.ppjwa.cn/Article/details/gtvzmnoddt.html

Py:   async def f():⏎    await g()
来源：http://dali.9152youxi.cn/Article/details/gtdugytlqt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.c1oappe.top/Article/details/gtbrdylhdb.html

JS:   async function f() { await g(); }
来源：http://dali.yueranfly.top/Article/details/gtgbjicfed.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ivvv.top/Article/details/gtbqcqbmvr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxyvmpfzb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.feifeiyinyue.top/Article/details/gtktachzfg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.quarkkingdee.top/Article/details/gtxpflfrim.html

C#:   async Task F() { await G(); }
来源：http://dali.dashuyun.cn/Article/details/gtpqrbzdtf.html

[O05] 并发执行并等待全部完成
来源：http://dali.hnqzz.top/Article/details/gtixhtwsjs.html

Py:   asyncio.gather(*tasks)
来源：http://dali.sxryk.cn/Article/details/gtimtidbfw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yj202588.top/Article/details/gtedzwwsbv.html

JS:   await Promise.all(tasks)
来源：http://dali.sysykeji.top/Article/details/gtyessiswj.html

TS:   await Promise.all(tasks)
来源：http://dali.hywenlv.cn/Article/details/gtdbrtymaw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ydzc1.top/Article/details/gtimvkozmo.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yj20258.top/Article/details/gtjwvnejbo.html

Ruby: threads.map(&:join)
来源：http://dali.daxiang520.top/Article/details/gtiklsdvmm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.nwbrower.top/Article/details/gtlhtsqvmy.html

[O06] 使用进程池
来源：http://dali.ppjwa.cn/Article/details/gtjogcowno.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtemtbwwsf.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yuanzhike.top/Article/details/gtnacjklad.html

JS:   // child_process / cluster 模块
来源：http://dali.yongpay.top/Article/details/gtzedueevj.html

TS:   // child_process / cluster 模块
来源：http://dali.svipenyu.cn/Article/details/gtqrliqorq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.fengsongda.top/Article/details/gtnvehjtvq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yangfankeji.com/Article/details/gtyftlctsb.html

Ruby: // fork 块
来源：http://dali.zhixingplan.top/Article/details/gtndhykzdk.html

C#:   Parallel.For
来源：http://dali.yonumen.top/Article/details/gtkugaxbgw.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtlshyxcmp.html

P. 常用工具函数
来源：http://dali.yonumen.top/Article/details/gthxruytir.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtwvcninkn.html

[P01] 生成 UUID
来源：http://dali.zhengqikj.top/Article/details/gttyrjmrez.html

Py:   str(uuid.uuid4())
来源：http://dali.jlsjyb.cn/Article/details/gtelkdursq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.fengsongda.top/Article/details/gtuxndcapb.html

JS:   crypto.randomUUID()
来源：http://dali.vqdsnc.cn/Article/details/gtqeemvrsw.html

TS:   crypto.randomUUID()
来源：http://dali.daria6918.cn/Article/details/gtjexznotm.html

Java: UUID.randomUUID().toString()
来源：http://dali.iojbl.cn/Article/details/gtjbztpqos.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gaohongyu789.top/Article/details/gtvtcpfdvj.html

Ruby: SecureRandom.uuid
来源：http://dali.nanxinkj.top/Article/details/gtaxniaemt.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.chenzaomai.com/Article/details/gthzagnzmb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jqgufenzy.top/Article/details/gtgvvmzpyn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hammf.cn/Article/details/gtnyksmawx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cashguo.top/Article/details/gtxjmriqfj.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sysykeji.top/Article/details/gtecfhofsw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jqgufenzy.top/Article/details/gtsdjktjuy.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.daria6918.cn/Article/details/gtcpwwknyx.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yj20258888.top/Article/details/gtwouvyzlh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.bjfxy.top/Article/details/gthgkbwvbi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xinyue.icu/Article/details/gtdqsospdw.html

[P03] 生成短随机字符串
来源：http://dali.hfpthk.cn/Article/details/gtqnstaqqd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.fengsongda.top/Article/details/gthjrwrjco.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zdqjudy.top/Article/details/gtxuvxtyul.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sweek.top/Article/details/gtxgruvnqx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtjarddjlz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtzhdqcfas.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.tanke756.top/Article/details/gtvjlhkzdm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.meibo888.top/Article/details/gtyebmmxxl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gtzohtbole.html

[P04] 求长度
来源：http://dali.chenzaomai.com/Article/details/gtabrpqxhj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jianghu66.top/Article/details/gtpatczcfj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gtoqaxxcjo.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvroukwyi.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ydzc1.top/Article/details/gtutfawfai.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhongyouzk.top/Article/details/gtrqzyzxzo.html

Go:   len(arr);  len(m)
来源：http://dali.vqdsnc.cn/Article/details/gtpojkqtlv.html

Ruby: x.length;  x.size
来源：http://dali.iojbl.cn/Article/details/gtphujpoyi.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.dashuyun.cn/Article/details/gtjibvhcgf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yj20258888.top/Article/details/gtdqjklgou.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yj20258.top/Article/details/gttrheruie.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.daxiang520.top/Article/details/gttbalcjmt.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hfpthk.cn/Article/details/gtqoqyejbx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xylfe.cn/Article/details/gthtkixtxs.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.wangdashe.top/Article/details/gtjzesmtxi.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.tanke756.top/Article/details/gtownztglw.html

Ruby: a == b
来源：http://dali.cashguo.top/Article/details/gtnkitdbqp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ehwqpu.com/Article/details/gtcsevoxqi.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.iojbl.cn/Article/details/gtftleoqsc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.c1oappe.top/Article/details/gtebdsbxsc.html

PHP:  if (empty($x)) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtthycrkfn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.guannengcc.top/Article/details/gtusjkjabj.html

TS:   if (x == null) {}
来源：http://dali.gogol.net.cn/Article/details/gtqynqykyu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.smart0.xyz/Article/details/gtyyrllupd.html

Go:   if x == nil {}
来源：http://dali.sysykeji.top/Article/details/gtdyprdykv.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.nanxuanxn.top/Article/details/gtayuzkzod.html

C#:   if (x is null) {}
来源：http://dali.xuanzx.com/Article/details/gtctuwwjnu.html

[P07] 防抖与节流
来源：http://dali.hnxiangtu.top/Article/details/gtrwwozyav.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jyoumei.cn/Article/details/gtlmvhtxjt.html

PHP:  // 手写时间戳比较
来源：http://dali.jinghuilouyu.cn/Article/details/gtwrzrcxrc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsebzmtri.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gaohongyu789.top/Article/details/gtnktjmjjl.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.iojbl.cn/Article/details/gtkekbvydp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xuanzx.com/Article/details/gtoyhkokyr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.fzhhl.top/Article/details/gtctjekjje.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.guannengcc.top/Article/details/gttnrhioax.html

[P08] 处理浮点精度问题
来源：http://dali.hysaishi.cn/Article/details/gtqlgflsol.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.sysykeji.top/Article/details/gtgvmyrolj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.guowangkeji.top/Article/details/gtzrvndxlb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.fengsongda.top/Article/details/gtpolmuaug.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jqgufenzy.top/Article/details/gtreutzcgc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.chenzaomai.com/Article/details/gtdzcxrxvy.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.dashuyun.cn/Article/details/gtogtthgbc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cdnleiting.top/Article/details/gtpmtyhkpe.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.meibo888.top/Article/details/gtqjrrpsfm.html


<!-- 参考信息 -->