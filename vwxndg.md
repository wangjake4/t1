代发 wailian999

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yj202588.top/Article/details/gtquwvlrca.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tanke756.top/Article/details/gtlsqoojun.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuanzx.com/Article/details/gtgplpheua.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.dianchejie.cn/Article/details/gtymwxnujo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.pycfn.com/Article/details/gtsqtqlgwt.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hnqzz.top/Article/details/gtgadyvbtl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jqgfzy.top/Article/details/gtgtkkdlfc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtonqmgeuu.html

[M04] 获取当前工作目录
来源：http://dali.ehwqpu.com/Article/details/gtckastcsz.html

Py:   os.getcwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyobtujho.html

PHP:  getcwd();
来源：http://dali.fengsongda.top/Article/details/gttxriamzb.html

JS:   process.cwd()
来源：http://dali.hnqzz.top/Article/details/gtdpuwkxmv.html

TS:   process.cwd()
来源：http://dali.yuxming.cn/Article/details/gtsghxnggx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.c1oappe.top/Article/details/gtepdjldos.html

Go:   os.Getwd()
来源：http://dali.zhiwuduotai.top/Article/details/gttgssfopi.html

Ruby: Dir.pwd
来源：http://dali.cashguo.top/Article/details/gtbnnxyfjv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jqgufenzy.top/Article/details/gthrweredh.html

[M05] 设置退出码
来源：http://dali.yj202588.top/Article/details/gtzqwxyzyd.html

Py:   sys.exit(1)
来源：http://dali.aizwys.cn/Article/details/gticupblms.html

PHP:  exit(1);
来源：http://dali.zhengqikj.top/Article/details/gtpckoedbn.html

JS:   process.exit(1)
来源：http://dali.tanke756.top/Article/details/gtisznnucv.html

TS:   process.exit(1)
来源：http://dali.yj202588.top/Article/details/gtdsdkzfjj.html

Java: System.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtavesfdjm.html

Go:   os.Exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtewemznds.html

Ruby: exit 1
来源：http://dali.jqgufenzy.top/Article/details/gtjyvfqekt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ivvv.top/Article/details/gtysjhvgcp.html

[M06] 向标准错误输出
来源：http://dali.aizwys.cn/Article/details/gtyoxqfers.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yuanzhike.top/Article/details/gtewpfrfut.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.svipenyu.cn/Article/details/gttkbpeaoh.html

JS:   console.error("err")
来源：http://dali.shuidangran.top/Article/details/gtlqmzmkmk.html

TS:   console.error("err")
来源：http://dali.yj20258.top/Article/details/gtgwwghinb.html

Java: System.err.println("err")
来源：http://dali.zhixingplan.top/Article/details/gtyteoohdj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhengqikj.top/Article/details/gtcbtgexwr.html

Ruby: warn "err"
来源：http://dali.cdnleiting.top/Article/details/gtupuvfaym.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yanxiufei.cn/Article/details/gtouplnzaz.html

[M07] 判断是否为主入口
来源：http://dali.hongshengwenyu.top/Article/details/gtzdireoln.html

Py:   if __name__ == "__main__":
来源：http://dali.kuanghao11.cn/Article/details/gtvyataydm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.snrcjt.cn/Article/details/gtxubfjusu.html

JS:   require.main === module
来源：http://dali.xuetiantiany.cn/Article/details/gtnhdggxoc.html

TS:   require.main === module
来源：http://dali.hnxiangtu.top/Article/details/gtdwpagtrb.html

Java: public static void main(String[] args)
来源：http://dali.andypj.xyz/Article/details/gtmrgdnpmz.html

Go:   func main()
来源：http://dali.vqdsnc.cn/Article/details/gtpdxwpceb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ywan-chungtsiang.top/Article/details/gtovlheapt.html

C#:   static void Main(string[] args)
来源：http://dali.tianlin.xyz/Article/details/gtlouvplvd.html

[M08] 获取系统与运行时信息
来源：http://dali.316326.xyz/Article/details/gtekpiriqm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yueranfly.top/Article/details/gteijgpbbw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.tian-w.cn/Article/details/gtqdodsean.html

JS:   process.platform;  process.version
来源：http://dali.tanke756.top/Article/details/gtuddnvzuw.html

TS:   process.platform;  process.version
来源：http://dali.yuxming.cn/Article/details/gtkmomtwpi.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cqqwz.cn/Article/details/gtpyhurvht.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.svipenyu.cn/Article/details/gtexxxgmfp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.wangshuangyany.cn/Article/details/gtvddibnui.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.smart0.xyz/Article/details/gtavcgwvby.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtftnddujz.html

N. 数据结构与算法
来源：http://dali.shanyushiyangtech.top/Article/details/gtndqwzfbe.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtikxtvqvg.html

[N01] 二分查找（有序数组）
来源：http://dali.mhx1999.top/Article/details/gtgdvpdozf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gttvvirynq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttoayngiw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gtqnhwpbwb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gtiwzewjjc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.daria6918.cn/Article/details/gtovvnvmfs.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gtjlojuogq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhoulong.xyz/Article/details/gtfazpyxuw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.tanke756.top/Article/details/gtkueqqlzq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenlongwang.top/Article/details/gtxruzuigm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258888.top/Article/details/gtxwswajiu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ivvv.top/Article/details/gtddptjnjb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.andypj.xyz/Article/details/gttrruuxzr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jyoumei.cn/Article/details/gtouaaqlyn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.meibo888.top/Article/details/gtrgwhgawk.html

Go:   slices.Sort(arr)
来源：http://dali.hywenlv.cn/Article/details/gtrnwredhy.html

Ruby: arr.sort
来源：http://dali.dashuyun.cn/Article/details/gttbryowix.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yj202588.top/Article/details/gtlgfurful.html

[N03] 快速排序（分治示例）
来源：http://dali.hfpthk.cn/Article/details/gtszpeuzon.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.andypj.xyz/Article/details/gtcxfaszsl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhengqikj.top/Article/details/gtcqwbvton.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cheryme.top/Article/details/gtndbhkvxw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhaomingkeji.xyz/Article/details/gthidsuuws.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj20258.top/Article/details/gthgeavdsj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.wangshuangyany.cn/Article/details/gtbmbpjdex.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yonumen.top/Article/details/gtkiemrhyt.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhixingplan.top/Article/details/gtnxdxuajj.html

[N04] 斐波那契数列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyuwzplsx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.aibaodan.cn/Article/details/gtgimvcvvq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.quarkkingdee.top/Article/details/gtqhisnwre.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmchznxyk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gtfqcokacv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.birdmap.top/Article/details/gtvrqsewfp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinqigfzy.top/Article/details/gtczfutiwl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtywhtqecs.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cqqwz.cn/Article/details/gtwbvsuxxr.html

[N05] 最大公约数
来源：http://dali.hysaishi.cn/Article/details/gtzolyrclg.html

Py:   math.gcd(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gthrqntqvv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.meibo888.top/Article/details/gtkmogibre.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigufen.top/Article/details/gtamsduwff.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.mhx1999.top/Article/details/gtjroadibg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xuetiantiany.cn/Article/details/gtyvxyofet.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shangyingyoupin.top/Article/details/gtnazhxdak.html

Ruby: a.gcd(b)
来源：http://dali.guannengcc.top/Article/details/gtatevwpyl.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.pycfn.com/Article/details/gtfvkcrunr.html

[N06] 判断回文字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtgwzzjdtf.html

Py:   s == s[::-1]
来源：http://dali.zycfv.cn/Article/details/gthhoqomli.html

PHP:  $s === strrev($s);
来源：http://dali.tian-w.cn/Article/details/gtticnsucj.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gttjqbgeef.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yuxming.cn/Article/details/gtblijhtub.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xuetiantiany.cn/Article/details/gtgjmjnwjb.html

Go:   // 双指针从两端比较
来源：http://dali.yonumen.top/Article/details/gtsapzcdmc.html

Ruby: s == s.reverse
来源：http://dali.jinqigfzy.top/Article/details/gthojrskfa.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yj202588.top/Article/details/gtsutjseow.html

[N07] 两数之和（返回下标）
来源：http://dali.dashuyun.cn/Article/details/gtzwhxzxyp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.feifeiyinyue.top/Article/details/gtczzvssfd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xylfe.cn/Article/details/gtulzzwwph.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xylfe.cn/Article/details/gtraqgbnvs.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhoulong.xyz/Article/details/gtdejabsks.html

Java: // 手写 HashMap
来源：http://dali.daxiang520.top/Article/details/gteswigqmv.html

Go:   // 手写 map[int]int
来源：http://dali.ivvv.top/Article/details/gtardrvbdb.html

Ruby: // 手写 Hash
来源：http://dali.zhoulong.xyz/Article/details/gtfabyfqgz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.316326.xyz/Article/details/gtnqwdjldl.html

[N08] 生成全排列
来源：http://dali.jiagoushi.top/Article/details/gtpxzylbov.html

Py:   itertools.permutations(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtouicxcbe.html

PHP:  // 手写递归交换
来源：http://dali.jinqigufen.top/Article/details/gtrmuzgime.html

JS:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gtgampswlt.html

TS:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gtgzkfnlxe.html

Java: // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gtdxxidywa.html

Go:   // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gtjjacejgo.html

Ruby: arr.permutation.to_a
来源：http://dali.chenjidiqi.icu/Article/details/gtcvveeuqe.html

C#:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gtutbbbnsw.html

[N09] 栈与队列
来源：http://dali.xuetiantiany.cn/Article/details/gtouopealw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hnqzz.top/Article/details/gtnpcydgky.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.smart0.xyz/Article/details/gtosrpqihv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.guannengcc.top/Article/details/gtcnhihtfy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jyoumei.cn/Article/details/gthghuiptf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ivvv.top/Article/details/gtqoeykyjy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.guannengcc.top/Article/details/gtdqnqxhag.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yueranfly.top/Article/details/gtipwlfzuz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ybcxt.top/Article/details/gtovizqzif.html

[N10] 链表节点定义
来源：http://dali.shangyingyoupin.top/Article/details/gtfowcjpxc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.vqdsnc.cn/Article/details/gtbooyqrpo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.316326.xyz/Article/details/gtwkqavjts.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gtehpukvwc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinghuilouyu.cn/Article/details/gttrfciolo.html

Java: class Node { int v; Node next; }
来源：http://dali.zycfv.cn/Article/details/gthismsdby.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ivvv.top/Article/details/gtxepciixr.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.chenjidiqi.icu/Article/details/gtkpxgbbgc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.nanxuanxn.top/Article/details/gtlpnwcndx.html

[N11] 二叉树中序遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbzrfshcf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.quarkkingdee.top/Article/details/gtmvhzduis.html

PHP:  // 手写递归函数
来源：http://dali.dianchejie.cn/Article/details/gtnrdnpsme.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cashguo.top/Article/details/gtogqqswjy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ydzc1.top/Article/details/gtqrwkuwnd.html

Java: // 手写递归
来源：http://dali.gaohongyu789.top/Article/details/gtsodmuoev.html

Go:   // 手写递归
来源：http://dali.sweek.top/Article/details/gtoqydvsem.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzugtjaik.html

C#:   // 手写递归
来源：http://dali.dianchejie.cn/Article/details/gtmuibwvre.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ppjwa.cn/Article/details/gtfrvxvuug.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yj20258.top/Article/details/gthqmxxzox.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hnxiangtu.top/Article/details/gtlopmobgj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hnxiangtu.top/Article/details/gtsaxirczw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jianghu66.top/Article/details/gtujaqxolr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ivvv.top/Article/details/gtcuoxonaa.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.pycfn.com/Article/details/gtjamcezla.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.smart0.xyz/Article/details/gtyopnxtqd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhengqikj.top/Article/details/gtttuiqwle.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gteddtgsyq.html

O. 并发与异步
来源：http://dali.cheryme.top/Article/details/gtunvardmd.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtekgwgajd.html

[O01] 启动一个线程
来源：http://dali.dianchejie.cn/Article/details/gttesbgjmk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.pengpengdd.cyou/Article/details/gtpjicirrf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.pycfn.com/Article/details/gtmfpvhins.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj202588.top/Article/details/gtrfesghks.html

TS:   // 同 JS
来源：http://dali.xuanzx.com/Article/details/gtkybfqywm.html

Java: new Thread(() -> f()).start()
来源：http://dali.tianlin.xyz/Article/details/gtgnirrnqe.html

Go:   go f()
来源：http://dali.yanxiufei.cn/Article/details/gtyukeqprs.html

Ruby: Thread.new { f }
来源：http://dali.chenlongwang.top/Article/details/gtuwhzthsp.html

C#:   Task.Run(() => F());
来源：http://dali.yuxming.cn/Article/details/gtqzhwrnoh.html

[O02] 使用线程池
来源：http://dali.hnxiangtu.top/Article/details/gtswtshsjz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jianghu66.top/Article/details/gtooaydlyd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jqgufenzy.top/Article/details/gtbzmmtpya.html

JS:   // worker_threads 线程池
来源：http://dali.wangdashe.top/Article/details/gtwqvbvpgb.html

TS:   // worker_threads 线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gtjrnxvztn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyuqvjtth.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.chenjidiqi.icu/Article/details/gtrofbxirq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.snrcjt.cn/Article/details/gtzlctvxip.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yj20258.top/Article/details/gtvuorwwzf.html

[O03] 加锁保护共享数据
来源：http://dali.yueranfly.top/Article/details/gtrxqkboah.html

Py:   with lock: shared += 1
来源：http://dali.hnqzz.top/Article/details/gtpxveuplb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.quarkkingdee.top/Article/details/gtrkpatbrq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.havefunace.top/Article/details/gtmfyxqxem.html

TS:   // 同 JS
来源：http://dali.jqgufenzy.top/Article/details/gtewxvgfjx.html

Java: synchronized (this) { shared++; }
来源：http://dali.jqgfzy.top/Article/details/gtsfgelrvj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.guannengcc.top/Article/details/gtgfvflcvk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtocotidtv.html

C#:   lock (gate) { shared++; }
来源：http://dali.jqgufenzy.top/Article/details/gtxanfdkmt.html

[O04] 定义异步函数并等待
来源：http://dali.aibaodan.cn/Article/details/gtqytrbtak.html

Py:   async def f():⏎    await g()
来源：http://dali.gaohongyu789.top/Article/details/gthfzsuldj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.chenjidiqi.icu/Article/details/gtjbjetjzm.html

JS:   async function f() { await g(); }
来源：http://dali.fzhhl.top/Article/details/gtjbblctsk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtpfqflvmg.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hnqzz.top/Article/details/gtvluiecjg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.quarkkingdee.top/Article/details/gtbgjpcafc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yuxming.cn/Article/details/gtfcwlfrxf.html

C#:   async Task F() { await G(); }
来源：http://dali.zhongyouzk.top/Article/details/gtpopnqntg.html

[O05] 并发执行并等待全部完成
来源：http://dali.aibaodan.cn/Article/details/gtwlyajbmw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.pengpengdd.cyou/Article/details/gtasgdtybm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yueranfly.top/Article/details/gtviflrovx.html

JS:   await Promise.all(tasks)
来源：http://dali.vqdsnc.cn/Article/details/gtrvisxful.html

TS:   await Promise.all(tasks)
来源：http://dali.guannengcc.top/Article/details/gtlqdjbtup.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.chenjidiqi.icu/Article/details/gtsiywukbh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ybcxt.top/Article/details/gtqdjkyxzg.html

Ruby: threads.map(&:join)
来源：http://dali.daxiang520.top/Article/details/gtolgxonfh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.smart0.xyz/Article/details/gtxqctmktz.html

[O06] 使用进程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteyacvczm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xinyue.icu/Article/details/gttoaxuflo.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinqigfzy.top/Article/details/gtoplpaelv.html

JS:   // child_process / cluster 模块
来源：http://dali.0kj1m.cn/Article/details/gtsvwdpsiv.html

TS:   // child_process / cluster 模块
来源：http://dali.316326.xyz/Article/details/gtfwxguvmn.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yvedp.cn/Article/details/gttqpyrgpm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shanyushiyangtech.top/Article/details/gtzkcceods.html

Ruby: // fork 块
来源：http://dali.birdmap.top/Article/details/gtrmyyawby.html

C#:   Parallel.For
来源：http://dali.sxryk.cn/Article/details/gtebylmhvu.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtrpxprxsn.html

P. 常用工具函数
来源：http://dali.meibo888.top/Article/details/gtcheqanql.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmqqhmgpk.html

[P01] 生成 UUID
来源：http://dali.zdqjudy.top/Article/details/gtegknszkc.html

Py:   str(uuid.uuid4())
来源：http://dali.sweek.top/Article/details/gtssursdxm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.smart0.xyz/Article/details/gtamigimcn.html

JS:   crypto.randomUUID()
来源：http://dali.zhongyouzk.top/Article/details/gtzvpurkxq.html

TS:   crypto.randomUUID()
来源：http://dali.gzhubu.top/Article/details/gternwldlf.html

Java: UUID.randomUUID().toString()
来源：http://dali.cheryme.top/Article/details/gttcdghrht.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhongyouzk.top/Article/details/gtnpbzwvqv.html

Ruby: SecureRandom.uuid
来源：http://dali.snrcjt.cn/Article/details/gtnjyxfgnn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.fengsongda.top/Article/details/gtjttopcno.html

[P02] MD5 / SHA256 摘要
来源：http://dali.nanxinkj.top/Article/details/gtajxneeyc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yueranfly.top/Article/details/gtimjwjclh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jianghu66.top/Article/details/gtpbnimccz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.tanke756.top/Article/details/gtqjukbowp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbnshnnxi.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cashguo.top/Article/details/gtnzqkhzod.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yuxming.cn/Article/details/gtnuwokvkg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yj20258.top/Article/details/gtngvkfmad.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shuidangran.top/Article/details/gtxfrpcrkc.html

[P03] 生成短随机字符串
来源：http://dali.jinqigfzy.top/Article/details/gtfbgorqdy.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.daria6918.cn/Article/details/gtnezuxltp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.aizwys.cn/Article/details/gtfnsnobkg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgbgzbclf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.c1oappe.top/Article/details/gtuwgdfaeo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yongpay.top/Article/details/gttpaigzeb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jiagoushi.top/Article/details/gtyveuemtn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yuxming.cn/Article/details/gttjqskzkc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jiagoushi.top/Article/details/gtpmlpexfw.html

[P04] 求长度
来源：http://dali.zhongyouzk.top/Article/details/gtaufyzrhq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.dashuyun.cn/Article/details/gtvzrcopjn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gtxheocysa.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tanke756.top/Article/details/gttubnqohx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenlongwang.top/Article/details/gtywpfkomo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sufxvd.cn/Article/details/gtihvkwnkj.html

Go:   len(arr);  len(m)
来源：http://dali.smart0.xyz/Article/details/gtrgobvdas.html

Ruby: x.length;  x.size
来源：http://dali.tianlin.xyz/Article/details/gtbokfhmzk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cqqwz.cn/Article/details/gtyhvamqyi.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xuetiantiany.cn/Article/details/gtsrwajodu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yueranfly.top/Article/details/gtdywlfito.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jqgufenzy.top/Article/details/gtcosjdjzf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gtucopbfao.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.kuanghao11.cn/Article/details/gtpubspomt.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcifnwhcc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.nwbrower.top/Article/details/gtuipmqxci.html

Ruby: a == b
来源：http://dali.0kj1m.cn/Article/details/gtavlqvmng.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ppjwa.cn/Article/details/gtjlfdbrgd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xylfe.cn/Article/details/gtconhpdjd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yueranfly.top/Article/details/gtrhdjxkqo.html

PHP:  if (empty($x)) {}
来源：http://dali.dianchejie.cn/Article/details/gtzodvozae.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.9152youxi.cn/Article/details/gtoavdxbbw.html

TS:   if (x == null) {}
来源：http://dali.nanxuanxn.top/Article/details/gtenkevkzo.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtoocoaein.html

Go:   if x == nil {}
来源：http://dali.cashguo.top/Article/details/gtogxgqaof.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cheryme.top/Article/details/gttfwjfihk.html

C#:   if (x is null) {}
来源：http://dali.ydzc1.top/Article/details/gtjxyhyezn.html

[P07] 防抖与节流
来源：http://dali.hammf.cn/Article/details/gtfoulfkel.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xinyue.icu/Article/details/gtwetnwwzi.html

PHP:  // 手写时间戳比较
来源：http://dali.tianlin.xyz/Article/details/gtflceqnjp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jyoumei.cn/Article/details/gtfmoyviql.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.quarkkingdee.top/Article/details/gtronucaxr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xziqi.cn/Article/details/gtdzpefpsb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yj20258.top/Article/details/gtsvfdumix.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hysaishi.cn/Article/details/gthhyusevm.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yanxiufei.cn/Article/details/gtxlrfdycq.html

[P08] 处理浮点精度问题
来源：http://dali.hysaishi.cn/Article/details/gtxgfaswaw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhongyouzk.top/Article/details/gtlhabamek.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.nwbrower.top/Article/details/gtpiuyherb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zdqjudy.top/Article/details/gtvfysnkho.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hnxiangtu.top/Article/details/gtconglyws.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinghuilouyu.cn/Article/details/gtwcgvauuv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.chenzaomai.com/Article/details/gteibwpzzn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.daxiang520.top/Article/details/gtamickjwv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jinqigfzy.top/Article/details/gtiyffsyat.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtskmmmtml.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sxryk.cn/Article/details/gtyhqwdsob.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtjkmmjurd.html

[Q01] 创建表
来源：http://dali.fzhhl.top/Article/details/gtfbzdpfvp.html


<!-- 参考信息 -->