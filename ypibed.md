代发 wailian999

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gtxickgjvm.html

Ruby: ENV["HOME"]
来源：http://dali.xuanzx.com/Article/details/gtpcjkuwkn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gzhubu.top/Article/details/gtomrdcmli.html

[M03] 执行外部命令
来源：http://dali.zdqjudy.top/Article/details/gtkuwbgybw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.aizwys.cn/Article/details/gttakkxlwc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yanxiufei.cn/Article/details/gtthifbuur.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ivvv.top/Article/details/gtclwfgmir.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yanxiufei.cn/Article/details/gtexofjjdy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.havefunace.top/Article/details/gtyevndozw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.wangdashe.top/Article/details/gtbdrfsojf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hnqzz.top/Article/details/gtqyalobmu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hysaishi.cn/Article/details/gttslkdquz.html

[M04] 获取当前工作目录
来源：http://dali.jianghu66.top/Article/details/gtoycbrnyp.html

Py:   os.getcwd()
来源：http://dali.jianghu66.top/Article/details/gtuhdzhwpd.html

PHP:  getcwd();
来源：http://dali.havefunace.top/Article/details/gtfbhdtdqm.html

JS:   process.cwd()
来源：http://dali.zhoulong.xyz/Article/details/gttfdwouah.html

TS:   process.cwd()
来源：http://dali.cucudq.cn/Article/details/gtmqzjdwvq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yonumen.top/Article/details/gtoqlsnqiv.html

Go:   os.Getwd()
来源：http://dali.hfpthk.cn/Article/details/gtfmizzvvz.html

Ruby: Dir.pwd
来源：http://dali.sufxvd.cn/Article/details/gtzmienqxn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.dashuyun.cn/Article/details/gtwsilzott.html

[M05] 设置退出码
来源：http://dali.jqgufenzy.top/Article/details/gtyophzifq.html

Py:   sys.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gtloxtwjge.html

PHP:  exit(1);
来源：http://dali.quarkkingdee.top/Article/details/gtvzpggudm.html

JS:   process.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthxhajrwh.html

TS:   process.exit(1)
来源：http://dali.yueranfly.top/Article/details/gtybxsydzi.html

Java: System.exit(1)
来源：http://dali.zycfv.cn/Article/details/gtiewcoswk.html

Go:   os.Exit(1)
来源：http://dali.gzhubu.top/Article/details/gtclysxnhw.html

Ruby: exit 1
来源：http://dali.zhixingplan.top/Article/details/gttadorvqm.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hysaishi.cn/Article/details/gtcifteajs.html

[M06] 向标准错误输出
来源：http://dali.jinqigfzy.top/Article/details/gtlhucosha.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhongyouzk.top/Article/details/gtesdvprzt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.wangdashe.top/Article/details/gtiqqhzywj.html

JS:   console.error("err")
来源：http://dali.aizwys.cn/Article/details/gthlmxaktc.html

TS:   console.error("err")
来源：http://dali.ppjwa.cn/Article/details/gtfuacfaej.html

Java: System.err.println("err")
来源：http://dali.xuetiantiany.cn/Article/details/gtwlegccjr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hammf.cn/Article/details/gtyfyapqnt.html

Ruby: warn "err"
来源：http://dali.zycfv.cn/Article/details/gttaeuszcy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.kuanghao11.cn/Article/details/gtmyxhnirc.html

[M07] 判断是否为主入口
来源：http://dali.sxryk.cn/Article/details/gtrcnqdndw.html

Py:   if __name__ == "__main__":
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwaxytfel.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hammf.cn/Article/details/gtbcpwbngf.html

JS:   require.main === module
来源：http://dali.vqdsnc.cn/Article/details/gtniygqsyy.html

TS:   require.main === module
来源：http://dali.havefunace.top/Article/details/gtzkmktwkq.html

Java: public static void main(String[] args)
来源：http://dali.chenzaomai.com/Article/details/gtymjzsirn.html

Go:   func main()
来源：http://dali.hnxiangtu.top/Article/details/gtfjfnzrsy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpzazvevw.html

C#:   static void Main(string[] args)
来源：http://dali.gzhubu.top/Article/details/gtllicmnzh.html

[M08] 获取系统与运行时信息
来源：http://dali.yj20258888.top/Article/details/gtthpgvduc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.meibo888.top/Article/details/gtkjfprwin.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ybcxt.top/Article/details/gtsodmmuvg.html

JS:   process.platform;  process.version
来源：http://dali.yuanzhike.top/Article/details/gtceblrzmy.html

TS:   process.platform;  process.version
来源：http://dali.zhoulong.xyz/Article/details/gtkhgyjqdb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.fengsongda.top/Article/details/gtbyubcuyq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sweek.top/Article/details/gtdfwukzue.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yvedp.cn/Article/details/gteiltnlvs.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xinyue.icu/Article/details/gtrltkjdtq.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtivogyumg.html

N. 数据结构与算法
来源：http://dali.yvedp.cn/Article/details/gtrxmdkvcl.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtwetpicvu.html

[N01] 二分查找（有序数组）
来源：http://dali.jyoumei.cn/Article/details/gtkdupzywc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.c1oappe.top/Article/details/gttjfwfode.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hammf.cn/Article/details/gtsscnjjan.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yvedp.cn/Article/details/gtqnioqvog.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shuidangran.top/Article/details/gtjgbzgvaw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtqhpatmhm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hnqzz.top/Article/details/gtmxevhyck.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hnxiangtu.top/Article/details/gtbacatelx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtlnmaorrd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xinyue.icu/Article/details/gthvkclbsy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sweek.top/Article/details/gtchogoceu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hongshengwenyu.top/Article/details/gthdsbyyev.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtypnaxprh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hammf.cn/Article/details/gtwbedfydl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.andypj.xyz/Article/details/gtxwgddlnr.html

Go:   slices.Sort(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbviacvix.html

Ruby: arr.sort
来源：http://dali.pycfn.com/Article/details/gtbijyrqzg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.guannengcc.top/Article/details/gtgfdblywb.html

[N03] 快速排序（分治示例）
来源：http://dali.yuanzhike.top/Article/details/gtipvlhggn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhixingplan.top/Article/details/gtwzlokkjj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.sweek.top/Article/details/gtlosfsrjb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.bjfxy.top/Article/details/gtxhscleeb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pycfn.com/Article/details/gteagejafd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhengqikj.top/Article/details/gtzwuyubel.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sxryk.cn/Article/details/gteftncgdv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yj20258888.top/Article/details/gtkwaiuhna.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.feifeiyinyue.top/Article/details/gtwyoxjfkw.html

[N04] 斐波那契数列
来源：http://dali.jiagoushi.top/Article/details/gtlvkyfenu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnowuotbd.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdbnrofgg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gtdwvycyzf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gtfratlann.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.meibo888.top/Article/details/gtxtdvefic.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.quarkkingdee.top/Article/details/gtresynrpj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zdqjudy.top/Article/details/gtwznemrqf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gtatfsawdh.html

[N05] 最大公约数
来源：http://dali.xylfe.cn/Article/details/gtfjxekftt.html

Py:   math.gcd(a, b)
来源：http://dali.ybcxt.top/Article/details/gtsofnqgui.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnayciznv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cashguo.top/Article/details/gtfjdbcebi.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shuidangran.top/Article/details/gtkymzzbji.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.nanxinkj.top/Article/details/gtzpqtsobb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hnxiangtu.top/Article/details/gthcfhkvdh.html

Ruby: a.gcd(b)
来源：http://dali.hywenlv.cn/Article/details/gthspfjrom.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhoulong.xyz/Article/details/gtkaphrxva.html

[N06] 判断回文字符串
来源：http://dali.hnqzz.top/Article/details/gtuorgevxa.html

Py:   s == s[::-1]
来源：http://dali.c1oappe.top/Article/details/gtiydmhamv.html

PHP:  $s === strrev($s);
来源：http://dali.quarkkingdee.top/Article/details/gtbyhlkwfp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdmxmkekz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gtrrpzljmw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.nanxuanxn.top/Article/details/gtygyfhydr.html

Go:   // 双指针从两端比较
来源：http://dali.yueranfly.top/Article/details/gtlafokrea.html

Ruby: s == s.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gttqyxcsre.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zycfv.cn/Article/details/gtheemmqdj.html

[N07] 两数之和（返回下标）
来源：http://dali.jianghu66.top/Article/details/gthkmbdnhj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hfpthk.cn/Article/details/gtvuvnnslx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.316326.xyz/Article/details/gtyjkwuvts.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinqigufen.top/Article/details/gtjnyrkbmm.html

TS:   // 手写 Map<string, number>
来源：http://dali.zdqjudy.top/Article/details/gtmwzsojhs.html

Java: // 手写 HashMap
来源：http://dali.xinyue.icu/Article/details/gtmdglrgqg.html

Go:   // 手写 map[int]int
来源：http://dali.dianchejie.cn/Article/details/gtxmgpqvep.html

Ruby: // 手写 Hash
来源：http://dali.jianghu66.top/Article/details/gtaozikuxa.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.dianchejie.cn/Article/details/gtfqlvqldx.html

[N08] 生成全排列
来源：http://dali.smart0.xyz/Article/details/gtsrgxclch.html

Py:   itertools.permutations(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtipugmdwo.html

PHP:  // 手写递归交换
来源：http://dali.ivvv.top/Article/details/gtsipdxxcb.html

JS:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gtywlhycet.html

TS:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gtrvjjxztf.html

Java: // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gtgpcpcjvc.html

Go:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gtcqcwssza.html

Ruby: arr.permutation.to_a
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgrmqqxvk.html

C#:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gtalkqpfzf.html

[N09] 栈与队列
来源：http://dali.yueranfly.top/Article/details/gtqvgmockm.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhoulong.xyz/Article/details/gtjmgjmlzg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenlongwang.top/Article/details/gthjebssed.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yangfankeji.com/Article/details/gtapwkhtum.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.smart0.xyz/Article/details/gtamjdzkst.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.fzhhl.top/Article/details/gtnxmylgzy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.tian-w.cn/Article/details/gttscptzmu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yuxming.cn/Article/details/gttbgptpcm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.guowangkeji.top/Article/details/gteuowcjvt.html

[N10] 链表节点定义
来源：http://dali.zdqjudy.top/Article/details/gtnqwixbcn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.c1oappe.top/Article/details/gtzktemxdp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jianghu66.top/Article/details/gtrxueptan.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yanxiufei.cn/Article/details/gtaewozqui.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hammf.cn/Article/details/gtfqosuxxx.html

Java: class Node { int v; Node next; }
来源：http://dali.xuetiantiany.cn/Article/details/gtozczmzhn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.daria6918.cn/Article/details/gtgvghgeni.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xinyue.icu/Article/details/gtzeghoixw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hnxiangtu.top/Article/details/gttoboouxe.html

[N11] 二叉树中序遍历
来源：http://dali.sweek.top/Article/details/gtbiytyvpg.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.pengpengdd.cyou/Article/details/gtoynylhcy.html

PHP:  // 手写递归函数
来源：http://dali.hfpthk.cn/Article/details/gtmzficptm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hammf.cn/Article/details/gtqgrrledp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guowangkeji.top/Article/details/gtuwvtiyin.html

Java: // 手写递归
来源：http://dali.zhongyouzk.top/Article/details/gtswgsfogd.html

Go:   // 手写递归
来源：http://dali.chenzaomai.com/Article/details/gtfxpyxrqc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gzhubu.top/Article/details/gtycppekdz.html

C#:   // 手写递归
来源：http://dali.havefunace.top/Article/details/gtoftoxmxf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.birdmap.top/Article/details/gtyslwdzoe.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.fzhhl.top/Article/details/gtgrhwnmlu.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jqgfzy.top/Article/details/gtsnreirqh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tianlin.xyz/Article/details/gtapqueecn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gtepzfaznl.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hnqzz.top/Article/details/gtsblcvcrn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jqgfzy.top/Article/details/gtxqaplmbd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.wangdashe.top/Article/details/gtiyvlnkxd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sysykeji.top/Article/details/gtjwyiilml.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtrslkdohj.html

O. 并发与异步
来源：http://dali.tianlin.xyz/Article/details/gtrknavpeu.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtrfvcfcme.html

[O01] 启动一个线程
来源：http://dali.ppjwa.cn/Article/details/gtgxqpvvrp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hywenlv.cn/Article/details/gtmhrdlcfo.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shangyingyoupin.top/Article/details/gtydfqgpzl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hnqzz.top/Article/details/gteuaflxxd.html

TS:   // 同 JS
来源：http://dali.zhixingplan.top/Article/details/gtdjueldrf.html

Java: new Thread(() -> f()).start()
来源：http://dali.xylfe.cn/Article/details/gtycxyisin.html

Go:   go f()
来源：http://dali.nanxinkj.top/Article/details/gtufekfmzn.html

Ruby: Thread.new { f }
来源：http://dali.tanke756.top/Article/details/gtsrpodfak.html

C#:   Task.Run(() => F());
来源：http://dali.9152youxi.cn/Article/details/gtiigksund.html

[O02] 使用线程池
来源：http://dali.yonumen.top/Article/details/gtsljrogsw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhixingplan.top/Article/details/gtigliutqi.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.tianlin.xyz/Article/details/gtvqrvbykb.html

JS:   // worker_threads 线程池
来源：http://dali.jyoumei.cn/Article/details/gtouvygqxu.html

TS:   // worker_threads 线程池
来源：http://dali.shuidangran.top/Article/details/gtnvqgearh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ydzc1.top/Article/details/gtzzbblgac.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.haohaochexian.top/Article/details/gtlcessrly.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.tian-w.cn/Article/details/gtxxjaajts.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.pycfn.com/Article/details/gtkjykeoyf.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gtlmfreqco.html

Py:   with lock: shared += 1
来源：http://dali.cdnleiting.top/Article/details/gttelxqoaz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gotoacloud.top/Article/details/gtifslvuwf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yvedp.cn/Article/details/gtnksxibio.html

TS:   // 同 JS
来源：http://dali.fzhhl.top/Article/details/gtgkvkjsxh.html

Java: synchronized (this) { shared++; }
来源：http://dali.yj202588.top/Article/details/gtzpzesccj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ybcxt.top/Article/details/gtmsvehaxh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.birdmap.top/Article/details/gtaulmgkks.html

C#:   lock (gate) { shared++; }
来源：http://dali.andypj.xyz/Article/details/gtyjzuvivy.html

[O04] 定义异步函数并等待
来源：http://dali.hnqzz.top/Article/details/gtjuwuvktd.html

Py:   async def f():⏎    await g()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxfsywxwl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.meibo888.top/Article/details/gtryhzpdnb.html

JS:   async function f() { await g(); }
来源：http://dali.nwbrower.top/Article/details/gtuigsehto.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.c1oappe.top/Article/details/gtrducdclz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shzxlz.cn/Article/details/gtpygpdyqa.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nwbrower.top/Article/details/gtmhpmwjpn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlcrbjsfx.html

C#:   async Task F() { await G(); }
来源：http://dali.c1oappe.top/Article/details/gtwdrasgzf.html

[O05] 并发执行并等待全部完成
来源：http://dali.andypj.xyz/Article/details/gtoccakgod.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jqgufenzy.top/Article/details/gtjydghtcd.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xuanzx.com/Article/details/gtiyoadvup.html

JS:   await Promise.all(tasks)
来源：http://dali.zhiwuduotai.top/Article/details/gtjoewpcbr.html

TS:   await Promise.all(tasks)
来源：http://dali.xuanzx.com/Article/details/gtzixidugj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.pengpengdd.cyou/Article/details/gtkaphsqwk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.iojbl.cn/Article/details/gtjtwpousm.html

Ruby: threads.map(&:join)
来源：http://dali.xinyue.icu/Article/details/gtwwfybbil.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jqgfzy.top/Article/details/gtugubgqsa.html

[O06] 使用进程池
来源：http://dali.havefunace.top/Article/details/gtajcmffzs.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.feifeiyinyue.top/Article/details/gtlbpbivjn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.havefunace.top/Article/details/gtujervenv.html

JS:   // child_process / cluster 模块
来源：http://dali.dashuyun.cn/Article/details/gtmijzzpjl.html

TS:   // child_process / cluster 模块
来源：http://dali.chenlongwang.top/Article/details/gtlbinqzkc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gaohongyu789.top/Article/details/gtdkuwgxxh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ehwqpu.com/Article/details/gtrbbdamjd.html

Ruby: // fork 块
来源：http://dali.xuetiantiany.cn/Article/details/gtpptiobmm.html

C#:   Parallel.For
来源：http://dali.havefunace.top/Article/details/gtpzzvlrjk.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtzbrscnxw.html

P. 常用工具函数
来源：http://dali.9152youxi.cn/Article/details/gtatylpyuq.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtujwbtkxg.html

[P01] 生成 UUID
来源：http://dali.snrcjt.cn/Article/details/gtaodufges.html

Py:   str(uuid.uuid4())
来源：http://dali.nanxinkj.top/Article/details/gtygsmnizw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hywenlv.cn/Article/details/gtmvexldci.html

JS:   crypto.randomUUID()
来源：http://dali.quarkkingdee.top/Article/details/gtfsomqbpj.html

TS:   crypto.randomUUID()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbvhhgkst.html

Java: UUID.randomUUID().toString()
来源：http://dali.hongshengwenyu.top/Article/details/gtudygqaxz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cashguo.top/Article/details/gtdaczauqc.html

Ruby: SecureRandom.uuid
来源：http://dali.yvedp.cn/Article/details/gtnsonkwwd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhongyouzk.top/Article/details/gtaomlmerw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.316326.xyz/Article/details/gtzynvvsgt.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhongyouzk.top/Article/details/gtarsrgfbj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.snrcjt.cn/Article/details/gtecayyxbb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyxbklihj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hywenlv.cn/Article/details/gtsqybteub.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ivvv.top/Article/details/gtuzlzftbt.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.nanxinkj.top/Article/details/gtlbsvdxto.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtkhlbnlla.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shanyushiyangtech.top/Article/details/gtslmipbuk.html

[P03] 生成短随机字符串
来源：http://dali.gzhubu.top/Article/details/gtgjfyccro.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hongshengwenyu.top/Article/details/gtgljorpcj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shuidangran.top/Article/details/gtdtmmlgid.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hammf.cn/Article/details/gtizqlilti.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shzxlz.cn/Article/details/gtwuefgqev.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yanxiufei.cn/Article/details/gtoyzodhpv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.birdmap.top/Article/details/gtrtmuwlmm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hysaishi.cn/Article/details/gtqhfcjnjn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ybcxt.top/Article/details/gtuidwzekt.html

[P04] 求长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteauuctys.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.dianchejie.cn/Article/details/gthbjpmrxg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gtxdcoyzrf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jiagoushi.top/Article/details/gtrrweiqrc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hysaishi.cn/Article/details/gtkvswftvh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yueranfly.top/Article/details/gtvvhwrckr.html

Go:   len(arr);  len(m)
来源：http://dali.jinghuilouyu.cn/Article/details/gtiwooyhja.html

Ruby: x.length;  x.size
来源：http://dali.smart0.xyz/Article/details/gticqzubru.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.snrcjt.cn/Article/details/gtokqgscmr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yangfankeji.com/Article/details/gtfjwewret.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.iojbl.cn/Article/details/gtktvwnizt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yj20258.top/Article/details/gtweoorbtc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xuetiantiany.cn/Article/details/gtaqhgovae.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.316326.xyz/Article/details/gtwvtjfwgi.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shangyingyoupin.top/Article/details/gtwcpbwswv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hywenlv.cn/Article/details/gtctrpuprc.html

Ruby: a == b
来源：http://dali.jyoumei.cn/Article/details/gtbatdabab.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sysykeji.top/Article/details/gtvaipjxpf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.guannengcc.top/Article/details/gtnejuixjv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jianghu66.top/Article/details/gtsjpblgpl.html

PHP:  if (empty($x)) {}
来源：http://dali.yvedp.cn/Article/details/gtchndwano.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhongyouzk.top/Article/details/gtyufjyvgb.html

TS:   if (x == null) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtvmrvrfbj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.svipenyu.cn/Article/details/gtdsswbzjl.html

Go:   if x == nil {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcrawllcy.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.wangdashe.top/Article/details/gtiudtiztc.html

C#:   if (x is null) {}
来源：http://dali.shuidangran.top/Article/details/gtdimmksdz.html

[P07] 防抖与节流
来源：http://dali.hnxiangtu.top/Article/details/gtkfjpuccr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.daxiang520.top/Article/details/gtpcbqjtig.html

PHP:  // 手写时间戳比较
来源：http://dali.jinqigfzy.top/Article/details/gtjyqyobem.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigfzy.top/Article/details/gtsgqcbalp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgufenzy.top/Article/details/gtjynquces.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.andypj.xyz/Article/details/gtzugknazz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jinqigfzy.top/Article/details/gtsljxupuc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ivvv.top/Article/details/gtrflvhyhg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hfpthk.cn/Article/details/gtqapjatec.html

[P08] 处理浮点精度问题
来源：http://dali.guowangkeji.top/Article/details/gtbpedemmd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yj20258888.top/Article/details/gtmldjukci.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.snrcjt.cn/Article/details/gtryescktm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbbfjidyh.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gotoacloud.top/Article/details/gtdiumkaat.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jyoumei.cn/Article/details/gtykvqhkiw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jyoumei.cn/Article/details/gtfjuabrux.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.feifeiyinyue.top/Article/details/gtihsqxudv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hywenlv.cn/Article/details/gtblmrhcoj.html


<!-- 参考信息 -->