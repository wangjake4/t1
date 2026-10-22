代发 wailian999

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yj202588.top/Article/details/gt2zcejtrvl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.dianchejie.cn/Article/details/gt2thpgnjaw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.dianchejie.cn/Article/details/gt2xystidnh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yonumen.top/Article/details/gt2ilxuisog.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cucudq.cn/Article/details/gt2mgfwyiwj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.daria6918.cn/Article/details/gt2krixtnoy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jiagoushi.top/Article/details/gt2hxeumdar.html

C#:   Process.Start("ls", "-l");
来源：http://dali.guannengcc.top/Article/details/gt2tbjcxyfi.html

[M04] 获取当前工作目录
来源：http://dali.gaohongyu789.top/Article/details/gt2cmilqbpq.html

Py:   os.getcwd()
来源：http://dali.nwbrower.top/Article/details/gt2cpclpjxp.html

PHP:  getcwd();
来源：http://dali.cdnleiting.top/Article/details/gt2xricfrad.html

JS:   process.cwd()
来源：http://dali.sysykeji.top/Article/details/gt2lvmmandi.html

TS:   process.cwd()
来源：http://dali.0kj1m.cn/Article/details/gt2ulkcsuvp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ppjwa.cn/Article/details/gt2xtlomdrb.html

Go:   os.Getwd()
来源：http://dali.sufxvd.cn/Article/details/gt2qzugohpf.html

Ruby: Dir.pwd
来源：http://dali.cashguo.top/Article/details/gt2ljaiexcm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hfpthk.cn/Article/details/gt2nnojoxqa.html

[M05] 设置退出码
来源：http://dali.hysaishi.cn/Article/details/gt2cloenjfh.html

Py:   sys.exit(1)
来源：http://dali.shuidangran.top/Article/details/gt2iuujdjwq.html

PHP:  exit(1);
来源：http://dali.snrcjt.cn/Article/details/gt2nkpumpdv.html

JS:   process.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gt2htcewchb.html

TS:   process.exit(1)
来源：http://dali.yj20258888.top/Article/details/gt2xmuauazo.html

Java: System.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ryzflmzh.html

Go:   os.Exit(1)
来源：http://dali.tanke756.top/Article/details/gt2cynjmacr.html

Ruby: exit 1
来源：http://dali.svipenyu.cn/Article/details/gt2qufnhjwx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhongyouzk.top/Article/details/gt2gonwtisz.html

[M06] 向标准错误输出
来源：http://dali.yongpay.top/Article/details/gt2aooxablr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.aizwys.cn/Article/details/gt2nqaqhkyn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.quarkkingdee.top/Article/details/gt2bvrozirg.html

JS:   console.error("err")
来源：http://dali.shzxlz.cn/Article/details/gt2brjifjhu.html

TS:   console.error("err")
来源：http://dali.9152youxi.cn/Article/details/gt2buhvdiun.html

Java: System.err.println("err")
来源：http://dali.bjfxy.top/Article/details/gt2wsiszxoj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.daxiang520.top/Article/details/gt2okbayrjt.html

Ruby: warn "err"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dgwchati.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.kuanghao11.cn/Article/details/gt2aupfgqru.html

[M07] 判断是否为主入口
来源：http://dali.shzxlz.cn/Article/details/gt2fvypozev.html

Py:   if __name__ == "__main__":
来源：http://dali.pycfn.com/Article/details/gt2uywwfhee.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cqqwz.cn/Article/details/gt2jbrfpgjl.html

JS:   require.main === module
来源：http://dali.xziqi.cn/Article/details/gt2bswnbxrz.html

TS:   require.main === module
来源：http://dali.haohaochexian.top/Article/details/gt2iyurirxw.html

Java: public static void main(String[] args)
来源：http://dali.nanxinkj.top/Article/details/gt2qbmkochg.html

Go:   func main()
来源：http://dali.pycfn.com/Article/details/gt2qvsjffsz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.guowangkeji.top/Article/details/gt2oikhumfg.html

C#:   static void Main(string[] args)
来源：http://dali.hywenlv.cn/Article/details/gt2jdmpvipd.html

[M08] 获取系统与运行时信息
来源：http://dali.yuxming.cn/Article/details/gt2tivxqhgx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gzhubu.top/Article/details/gt2ujskluwn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2egpmjnql.html

JS:   process.platform;  process.version
来源：http://dali.meibo888.top/Article/details/gt2bcnkxldz.html

TS:   process.platform;  process.version
来源：http://dali.kuanghao11.cn/Article/details/gt2fdancnig.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xinyue.icu/Article/details/gt2akfdcdoj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.316326.xyz/Article/details/gt2lxrzgwdn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gztbidtm.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tianlin.xyz/Article/details/gt2dyoibtzh.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qwrypuem.html

N. 数据结构与算法
来源：http://dali.tanke756.top/Article/details/gt2bnnlldpk.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2mpucslus.html

[N01] 二分查找（有序数组）
来源：http://dali.cheryme.top/Article/details/gt2csvcshid.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shuidangran.top/Article/details/gt2kczfbrxl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shuidangran.top/Article/details/gt2fiiyclen.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ppjwa.cn/Article/details/gt2vofmsxqc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cashguo.top/Article/details/gt2ijxmsnfw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gt2ytrffjxf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gt2hhkmjupj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yanxiufei.cn/Article/details/gt2sqamcrvk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ixbujluo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hnqzz.top/Article/details/gt2iwkoyivq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dianchejie.cn/Article/details/gt2sdbohxdb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ivvv.top/Article/details/gt2pkzyrnjn.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ppjwa.cn/Article/details/gt2opsixswx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xylfe.cn/Article/details/gt2pbzqduhs.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yonumen.top/Article/details/gt2qrbvkcst.html

Go:   slices.Sort(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2voiohnut.html

Ruby: arr.sort
来源：http://dali.yvedp.cn/Article/details/gt2vboidesy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hongshengwenyu.top/Article/details/gt2dloprlnq.html

[N03] 快速排序（分治示例）
来源：http://dali.yuanzhike.top/Article/details/gt2jclcplbw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lyhchowh.html

PHP:  // 递归实现，或用 usort
来源：http://dali.wangshuangyany.cn/Article/details/gt2zjtmgklm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenlongwang.top/Article/details/gt2vajflqcn.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shzxlz.cn/Article/details/gt2jpjwmipw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ehwqpu.com/Article/details/gt2ggmijxtv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.andypj.xyz/Article/details/gt2ssbfwkwq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.feifeiyinyue.top/Article/details/gt2hiniruzv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.pengpengdd.cyou/Article/details/gt2nusaliiq.html

[N04] 斐波那契数列
来源：http://dali.tanke756.top/Article/details/gt2soqtirwm.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gogol.net.cn/Article/details/gt2kufgffau.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hammf.cn/Article/details/gt2jiuuytnd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gt2xuthzuho.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jianghu66.top/Article/details/gt2lqausdxh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yanxiufei.cn/Article/details/gt2umrgznje.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xylfe.cn/Article/details/gt2iljneqxk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.kuanghao11.cn/Article/details/gt2oecxgefd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.pycfn.com/Article/details/gt2lmcvudsa.html

[N05] 最大公约数
来源：http://dali.hfpthk.cn/Article/details/gt2tfnavtan.html

Py:   math.gcd(a, b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gbycaqre.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.nanxinkj.top/Article/details/gt2upuggjsj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jlsjyb.cn/Article/details/gt2lqvlfzac.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gaohongyu789.top/Article/details/gt2oitdefba.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cucudq.cn/Article/details/gt2ueghjbth.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yvedp.cn/Article/details/gt2fkinjlql.html

Ruby: a.gcd(b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wjgbczpd.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.fengsongda.top/Article/details/gt2pusdmgvc.html

[N06] 判断回文字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2fxxcytrl.html

Py:   s == s[::-1]
来源：http://dali.daria6918.cn/Article/details/gt2iadehsra.html

PHP:  $s === strrev($s);
来源：http://dali.andypj.xyz/Article/details/gt2wkyhzzkj.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gt2hrjvhxqt.html

TS:   s === [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gt2sfyjbtgd.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yonumen.top/Article/details/gt2cymzhhzw.html

Go:   // 双指针从两端比较
来源：http://dali.hongshengwenyu.top/Article/details/gt2hjdtoiib.html

Ruby: s == s.reverse
来源：http://dali.tian-w.cn/Article/details/gt2vnzgecsl.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xylfe.cn/Article/details/gt2wxhuense.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2amdwveck.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.redwolf501.top/Article/details/gt2yuyzphkf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhixingplan.top/Article/details/gt2ouwnmyna.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hfpthk.cn/Article/details/gt2bupvtthb.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhengqikj.top/Article/details/gt2drvpwxld.html

Java: // 手写 HashMap
来源：http://dali.cheryme.top/Article/details/gt2zgqqlwcl.html

Go:   // 手写 map[int]int
来源：http://dali.kuanghao11.cn/Article/details/gt2nhmuldys.html

Ruby: // 手写 Hash
来源：http://dali.yj20258.top/Article/details/gt2oelxtgjo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ppjwa.cn/Article/details/gt2idutnfec.html

[N08] 生成全排列
来源：http://dali.xziqi.cn/Article/details/gt2dtaeeahw.html

Py:   itertools.permutations(arr)
来源：http://dali.sysykeji.top/Article/details/gt2ktndkcip.html

PHP:  // 手写递归交换
来源：http://dali.316326.xyz/Article/details/gt2otzginvb.html

JS:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gt2huioepyh.html

TS:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gt2kgrjvjzy.html

Java: // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gt2kgwycylm.html

Go:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gt2qihfeiou.html

Ruby: arr.permutation.to_a
来源：http://dali.pengpengdd.cyou/Article/details/gt2tdxskaiq.html

C#:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gt2mrulawaj.html

[N09] 栈与队列
来源：http://dali.jlsjyb.cn/Article/details/gt2pwwcybsr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yuanzhike.top/Article/details/gt2nujhnstl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.andypj.xyz/Article/details/gt2tlxyywmb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jqgfzy.top/Article/details/gt2dkdpmrwo.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ybcxt.top/Article/details/gt2wjkgjzse.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.svipenyu.cn/Article/details/gt2ggbpzqvi.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.pengpengdd.cyou/Article/details/gt2gtcddmtt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.tanke756.top/Article/details/gt2zzskanla.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.kuanghao11.cn/Article/details/gt2hmqglics.html

[N10] 链表节点定义
来源：http://dali.nanxuanxn.top/Article/details/gt2unziwxwk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zdqjudy.top/Article/details/gt2ktpttgtq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ydzc1.top/Article/details/gt2kndmehho.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hammf.cn/Article/details/gt2ckkahrat.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zdqjudy.top/Article/details/gt2bxcralnv.html

Java: class Node { int v; Node next; }
来源：http://dali.nwbrower.top/Article/details/gt2zlmpuifj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.iojbl.cn/Article/details/gt2ezinjsjv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bxakvuzo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhengqikj.top/Article/details/gt2xcswughk.html

[N11] 二叉树中序遍历
来源：http://dali.zdqjudy.top/Article/details/gt2znntkjsx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hongshengwenyu.top/Article/details/gt2sacxzyws.html

PHP:  // 手写递归函数
来源：http://dali.aibaodan.cn/Article/details/gt2jdcczqnz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gaohongyu789.top/Article/details/gt2zimskcbw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.dianchejie.cn/Article/details/gt2lwoitoqw.html

Java: // 手写递归
来源：http://dali.yueranfly.top/Article/details/gt2niderplj.html

Go:   // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gt2xcmifrfl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jqgfzy.top/Article/details/gt2lwekgsyd.html

C#:   // 手写递归
来源：http://dali.yvedp.cn/Article/details/gt2shmxrnmi.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.0kj1m.cn/Article/details/gt2pbdfrpqp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.svipenyu.cn/Article/details/gt2pewolzyo.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xuetiantiany.cn/Article/details/gt2sfkrposy.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.haohaochexian.top/Article/details/gt2clgsfwky.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258888.top/Article/details/gt2mtruilje.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hysaishi.cn/Article/details/gt2rfapugjd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hysaishi.cn/Article/details/gt2dkmyxort.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zdqjudy.top/Article/details/gt2yoowjgvo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zycfv.cn/Article/details/gt2rbwonbix.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2ofohzefs.html

O. 并发与异步
来源：http://dali.zhixingplan.top/Article/details/gt2ikuguyyg.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2zcpzayvs.html

[O01] 启动一个线程
来源：http://dali.shzxlz.cn/Article/details/gt2fjvgblcq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.feifeiyinyue.top/Article/details/gt2qhacdcet.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.dianchejie.cn/Article/details/gt2rptomoks.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hywenlv.cn/Article/details/gt2gqueivhf.html

TS:   // 同 JS
来源：http://dali.chenzaomai.com/Article/details/gt2gixphilm.html

Java: new Thread(() -> f()).start()
来源：http://dali.cheryme.top/Article/details/gt2fzwvjkeb.html

Go:   go f()
来源：http://dali.yvedp.cn/Article/details/gt2vjqneycs.html

Ruby: Thread.new { f }
来源：http://dali.sxryk.cn/Article/details/gt2ssyivvgd.html

C#:   Task.Run(() => F());
来源：http://dali.sysykeji.top/Article/details/gt2jfwzocns.html

[O02] 使用线程池
来源：http://dali.yanxiufei.cn/Article/details/gt2kjlcviby.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ppjwa.cn/Article/details/gt2zyokhbwi.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.fzhhl.top/Article/details/gt2vzfljasq.html

JS:   // worker_threads 线程池
来源：http://dali.chenlongwang.top/Article/details/gt2lbzkcfli.html

TS:   // worker_threads 线程池
来源：http://dali.ybcxt.top/Article/details/gt2tswpkmhq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xinyue.icu/Article/details/gt2bwcdjxwq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhixingplan.top/Article/details/gt2urosetld.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cheryme.top/Article/details/gt2gkribzqy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yj20258.top/Article/details/gt2jbzbhwbs.html

[O03] 加锁保护共享数据
来源：http://dali.yongpay.top/Article/details/gt2sxbagjfk.html

Py:   with lock: shared += 1
来源：http://dali.fzhhl.top/Article/details/gt2tvkidnwu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yongpay.top/Article/details/gt2fjbqftvr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.quarkkingdee.top/Article/details/gt2opzfkgjw.html

TS:   // 同 JS
来源：http://dali.gogol.net.cn/Article/details/gt2xiykygfs.html

Java: synchronized (this) { shared++; }
来源：http://dali.mhx1999.top/Article/details/gt2pmrxyhub.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jinqigfzy.top/Article/details/gt2eukapffd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.pengpengdd.cyou/Article/details/gt2vvqbjlks.html

C#:   lock (gate) { shared++; }
来源：http://dali.gotoacloud.top/Article/details/gt2kbavwxcw.html

[O04] 定义异步函数并等待
来源：http://dali.shuidangran.top/Article/details/gt2mdnocmnn.html

Py:   async def f():⏎    await g()
来源：http://dali.cdnleiting.top/Article/details/gt2grhrshkp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yonumen.top/Article/details/gt2rjajlhnf.html

JS:   async function f() { await g(); }
来源：http://dali.yuanzhike.top/Article/details/gt2poivbtjs.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.tian-w.cn/Article/details/gt2kqvxnyxm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.dianchejie.cn/Article/details/gt2urqesfxf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sysykeji.top/Article/details/gt2elhftkih.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hnqzz.top/Article/details/gt2kiqzsecf.html

C#:   async Task F() { await G(); }
来源：http://dali.zhengqikj.top/Article/details/gt2yvyehjcm.html

[O05] 并发执行并等待全部完成
来源：http://dali.cqqwz.cn/Article/details/gt2ojffkqaw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.guannengcc.top/Article/details/gt2miwhyfun.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zdqjudy.top/Article/details/gt2onxzxohv.html

JS:   await Promise.all(tasks)
来源：http://dali.zhengqikj.top/Article/details/gt2hzgvrmso.html

TS:   await Promise.all(tasks)
来源：http://dali.xuanzx.com/Article/details/gt2duroowje.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nwlxnyub.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jiagoushi.top/Article/details/gt2meuikqsm.html

Ruby: threads.map(&:join)
来源：http://dali.zhengqikj.top/Article/details/gt2pajcgncg.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ppjwa.cn/Article/details/gt2enugfufs.html

[O06] 使用进程池
来源：http://dali.ybcxt.top/Article/details/gt2knervnxp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sysykeji.top/Article/details/gt2wxxklqsp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ulilmtve.html

JS:   // child_process / cluster 模块
来源：http://dali.cheryme.top/Article/details/gt2aycbhvji.html

TS:   // child_process / cluster 模块
来源：http://dali.yangfankeji.com/Article/details/gt2cjurkkbn.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yvedp.cn/Article/details/gt2otjirgev.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jinqigufen.top/Article/details/gt2rhblfhra.html

Ruby: // fork 块
来源：http://dali.zhoulong.xyz/Article/details/gt2dsxiacob.html

C#:   Parallel.For
来源：http://dali.yuxming.cn/Article/details/gt2xrryghuf.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2wsgucxhg.html

P. 常用工具函数
来源：http://dali.andypj.xyz/Article/details/gt2xunpvbbt.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2sklacere.html

[P01] 生成 UUID
来源：http://dali.ydzc1.top/Article/details/gt2rlfuaojz.html

Py:   str(uuid.uuid4())
来源：http://dali.chenlongwang.top/Article/details/gt2cyaglgzn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.vqdsnc.cn/Article/details/gt2vhhtepsr.html

JS:   crypto.randomUUID()
来源：http://dali.havefunace.top/Article/details/gt2ifuyiihj.html

TS:   crypto.randomUUID()
来源：http://dali.tianlin.xyz/Article/details/gt2bovkpshw.html

Java: UUID.randomUUID().toString()
来源：http://dali.yueranfly.top/Article/details/gt2qpbluveq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tian-w.cn/Article/details/gt2sxejuesn.html

Ruby: SecureRandom.uuid
来源：http://dali.zhixingplan.top/Article/details/gt2gxgggzpg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cucudq.cn/Article/details/gt2thbdumlk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.havefunace.top/Article/details/gt2dgxxzkzq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhiwuduotai.top/Article/details/gt2pykkibmw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.daxiang520.top/Article/details/gt2jgbqpmdj.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yueranfly.top/Article/details/gt2etrvblsc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yuxming.cn/Article/details/gt2dukqkxzw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jiagoushi.top/Article/details/gt2dqkycazx.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.fengsongda.top/Article/details/gt2vpicyzbm.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jqgfzy.top/Article/details/gt2egrgcxjj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.c1oappe.top/Article/details/gt2ukblsjhm.html

[P03] 生成短随机字符串
来源：http://dali.c1oappe.top/Article/details/gt2kvqffaku.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.gotoacloud.top/Article/details/gt2iyaitupp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xylfe.cn/Article/details/gt2qyknetkf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nwbrower.top/Article/details/gt2yrrbahsl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jyoumei.cn/Article/details/gt2tmbprdts.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hugfvrsd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yvedp.cn/Article/details/gt2addguihw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.316326.xyz/Article/details/gt2uunaxwli.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.guowangkeji.top/Article/details/gt2hsgnfiuc.html

[P04] 求长度
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pptmkjgx.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxvxsik.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gt2ipobbnjn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yongpay.top/Article/details/gt2bsixnqba.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sufxvd.cn/Article/details/gt2nlyqvrnv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.aibaodan.cn/Article/details/gt2xmlopppp.html

Go:   len(arr);  len(m)
来源：http://dali.jqgfzy.top/Article/details/gt2nellxlks.html

Ruby: x.length;  x.size
来源：http://dali.zdqjudy.top/Article/details/gt2hjrzckpp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.pengpengdd.cyou/Article/details/gt2lhnkyifp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.cqqwz.cn/Article/details/gt2iuuubxgr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhixingplan.top/Article/details/gt2qvbxkfze.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ivvv.top/Article/details/gt2ntefqwqh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hnqzz.top/Article/details/gt2iltswwez.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hwlottoi.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ppjwa.cn/Article/details/gt2uvhwhzru.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jipbszkg.html

Ruby: a == b
来源：http://dali.andypj.xyz/Article/details/gt2mywwxzwn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2jrdcuwqa.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cdnleiting.top/Article/details/gt2sljkhhkh.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.vqdsnc.cn/Article/details/gt2umiuciwf.html

PHP:  if (empty($x)) {}
来源：http://dali.tanke756.top/Article/details/gt2bgqkcrxu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.9152youxi.cn/Article/details/gt2lrshmpdf.html

TS:   if (x == null) {}
来源：http://dali.xziqi.cn/Article/details/gt2cfbmfdak.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xcumzbbn.html

Go:   if x == nil {}
来源：http://dali.jqgufenzy.top/Article/details/gt2kmotsrur.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sweek.top/Article/details/gt2zpbjwcmr.html

C#:   if (x is null) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2riasrmgr.html

[P07] 防抖与节流
来源：http://dali.tian-w.cn/Article/details/gt2pbvcayvw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mbthmvyn.html

PHP:  // 手写时间戳比较
来源：http://dali.yj202588.top/Article/details/gt2txmxkmdw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shangyingyoupin.top/Article/details/gt2tanitsqv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258.top/Article/details/gt2sahazvsc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.gogol.net.cn/Article/details/gt2dzclwljr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cashguo.top/Article/details/gt2yaqnmkgq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.pengpengdd.cyou/Article/details/gt2uiiwufoa.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.nanxuanxn.top/Article/details/gt2sabuscew.html

[P08] 处理浮点精度问题
来源：http://dali.havefunace.top/Article/details/gt2tietenvk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.tian-w.cn/Article/details/gt2zinmdwwz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cucudq.cn/Article/details/gt2ybrdmrof.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jinqigufen.top/Article/details/gt2nutjwlsc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.chenzaomai.com/Article/details/gt2rvkcrqzg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.guowangkeji.top/Article/details/gt2jliejuqe.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmefsdk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xuanzx.com/Article/details/gt2inxtgmnr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nanxinkj.top/Article/details/gt2gfjcuwnm.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2fkcwdsdk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hywenlv.cn/Article/details/gt2lfnmosqo.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2yelevaal.html

[Q01] 创建表
来源：http://dali.sweek.top/Article/details/gt2ibvliock.html


<!-- 参考信息 -->