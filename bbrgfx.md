代发 wailian999

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthirgqwqe.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.snrcjt.cn/Article/details/gtkowqmgkn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yvedp.cn/Article/details/gtudbmillr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.snrcjt.cn/Article/details/gtlyasgpth.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinqigufen.top/Article/details/gtwtuvshwp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.haohaochexian.top/Article/details/gtgvejefcd.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoyeiddbh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ybcxt.top/Article/details/gtqhawxwbg.html

[M04] 获取当前工作目录
来源：http://dali.gotoacloud.top/Article/details/gtyptwjzcs.html

Py:   os.getcwd()
来源：http://dali.xziqi.cn/Article/details/gtcsaupyoy.html

PHP:  getcwd();
来源：http://dali.hysaishi.cn/Article/details/gtcqlogsef.html

JS:   process.cwd()
来源：http://dali.gogol.net.cn/Article/details/gtharticvx.html

TS:   process.cwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtisjuguqi.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.dashuyun.cn/Article/details/gtfadudffh.html

Go:   os.Getwd()
来源：http://dali.vqdsnc.cn/Article/details/gtfkndfdwl.html

Ruby: Dir.pwd
来源：http://dali.aizwys.cn/Article/details/gteozdfzil.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zdqjudy.top/Article/details/gtgtqivjee.html

[M05] 设置退出码
来源：http://dali.tanke756.top/Article/details/gtmemoccnp.html

Py:   sys.exit(1)
来源：http://dali.yueranfly.top/Article/details/gtwitbtxsc.html

PHP:  exit(1);
来源：http://dali.yj202588.top/Article/details/gtxqzkolsz.html

JS:   process.exit(1)
来源：http://dali.sysykeji.top/Article/details/gthixwttws.html

TS:   process.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gtankwxoot.html

Java: System.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtaflzqtpx.html

Go:   os.Exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzrwhjega.html

Ruby: exit 1
来源：http://dali.daria6918.cn/Article/details/gtwexegtkg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhiwuduotai.top/Article/details/gtviqobzus.html

[M06] 向标准错误输出
来源：http://dali.shanyushiyangtech.top/Article/details/gtznncqdup.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cheryme.top/Article/details/gtrulaiuhu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yuxming.cn/Article/details/gtmfvurfsm.html

JS:   console.error("err")
来源：http://dali.wangdashe.top/Article/details/gttaxxlzmo.html

TS:   console.error("err")
来源：http://dali.yueranfly.top/Article/details/gtddhdocti.html

Java: System.err.println("err")
来源：http://dali.cucudq.cn/Article/details/gtgeeqgkge.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cheryme.top/Article/details/gtjidjkyuv.html

Ruby: warn "err"
来源：http://dali.yj20258.top/Article/details/gtgwxopnag.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xuanzx.com/Article/details/gtcmzdphbi.html

[M07] 判断是否为主入口
来源：http://dali.snrcjt.cn/Article/details/gtvrizylzy.html

Py:   if __name__ == "__main__":
来源：http://dali.chenzaomai.com/Article/details/gtdvdmvmpy.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shzxlz.cn/Article/details/gtntejqasm.html

JS:   require.main === module
来源：http://dali.mhx1999.top/Article/details/gthfohmvvd.html

TS:   require.main === module
来源：http://dali.ehwqpu.com/Article/details/gtkzjozfpg.html

Java: public static void main(String[] args)
来源：http://dali.sxryk.cn/Article/details/gtvfovjyud.html

Go:   func main()
来源：http://dali.tian-w.cn/Article/details/gteneytyzz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.daxiang520.top/Article/details/gtvvsrhpcp.html

C#:   static void Main(string[] args)
来源：http://dali.yanxiufei.cn/Article/details/gtldbnbrsf.html

[M08] 获取系统与运行时信息
来源：http://dali.c1oappe.top/Article/details/gtnejxebox.html

Py:   platform.system();  platform.python_version()
来源：http://dali.316326.xyz/Article/details/gtjpypgalv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yangfankeji.com/Article/details/gtcxgmmgas.html

JS:   process.platform;  process.version
来源：http://dali.jinghuilouyu.cn/Article/details/gtueddfhmf.html

TS:   process.platform;  process.version
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlqihwmdh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cheryme.top/Article/details/gtxktbfigq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.dianchejie.cn/Article/details/gttxqnfqbk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yangfankeji.com/Article/details/gtouegotpw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhiwuduotai.top/Article/details/gtytkekffw.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtvcajpyxf.html

N. 数据结构与算法
来源：http://dali.hongshengwenyu.top/Article/details/gtolpikfip.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtntjisbrh.html

[N01] 二分查找（有序数组）
来源：http://dali.wangshuangyany.cn/Article/details/gtgghrxaki.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtohybpdnq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.redwolf501.top/Article/details/gthvpfrhno.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aibaodan.cn/Article/details/gteuwmecxw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuanzhike.top/Article/details/gtfnsawzmm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwwioilrc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtwjzebyzd.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhongyouzk.top/Article/details/gtvspdzmwo.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtfaemuoiy.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yj20258.top/Article/details/gtpoyqwwtm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gogol.net.cn/Article/details/gtxndweepo.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.havefunace.top/Article/details/gthzmaoweu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.0kj1m.cn/Article/details/gtevrjvbuy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hysaishi.cn/Article/details/gtguktlycd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.iojbl.cn/Article/details/gtplwiywuv.html

Go:   slices.Sort(arr)
来源：http://dali.gzhubu.top/Article/details/gtttrackaq.html

Ruby: arr.sort
来源：http://dali.zhongyouzk.top/Article/details/gtaozqzxzw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zycfv.cn/Article/details/gtxevhbcgl.html

[N03] 快速排序（分治示例）
来源：http://dali.wangdashe.top/Article/details/gtzjrtfoed.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.wangshuangyany.cn/Article/details/gttigomwpf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhongyouzk.top/Article/details/gtzgqwciyd.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sufxvd.cn/Article/details/gttlvuxwvo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jiagoushi.top/Article/details/gtvkriojip.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hammf.cn/Article/details/gtbkasprqc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinghuilouyu.cn/Article/details/gtilndrset.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yongpay.top/Article/details/gttxezstqm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gotoacloud.top/Article/details/gtbdhkcjzs.html

[N04] 斐波那契数列
来源：http://dali.guowangkeji.top/Article/details/gtdotiduwq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hnqzz.top/Article/details/gteiwqchbs.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jqgfzy.top/Article/details/gtznqluduj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhixingplan.top/Article/details/gtagduedsx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dashuyun.cn/Article/details/gtigefyjfw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.wangdashe.top/Article/details/gtaudwyaln.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.wangdashe.top/Article/details/gtwzuumvxt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtvbbzrmjz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gtfswpecgk.html

[N05] 最大公约数
来源：http://dali.birdmap.top/Article/details/gtbhdzlfwr.html

Py:   math.gcd(a, b)
来源：http://dali.xuetiantiany.cn/Article/details/gtvhuudwhn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gtlvjfudtr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhengqikj.top/Article/details/gtbrtcdsnf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yueranfly.top/Article/details/gtppwrjzik.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.aibaodan.cn/Article/details/gtfwjwvgga.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hnxiangtu.top/Article/details/gtdxtimaht.html

Ruby: a.gcd(b)
来源：http://dali.yj20258.top/Article/details/gtuuucizqp.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.tanke756.top/Article/details/gtyvgvkfvx.html

[N06] 判断回文字符串
来源：http://dali.daxiang520.top/Article/details/gtgsslakkt.html

Py:   s == s[::-1]
来源：http://dali.gzhubu.top/Article/details/gttwvhiwvl.html

PHP:  $s === strrev($s);
来源：http://dali.jlsjyb.cn/Article/details/gtyncloder.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gtnighdsaf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gtiiccjapv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.guowangkeji.top/Article/details/gtqnvisqqx.html

Go:   // 双指针从两端比较
来源：http://dali.kuanghao11.cn/Article/details/gtulobweuz.html

Ruby: s == s.reverse
来源：http://dali.zhoulong.xyz/Article/details/gtscdsxuur.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yj20258.top/Article/details/gtkhdqxwjf.html

[N07] 两数之和（返回下标）
来源：http://dali.zhoulong.xyz/Article/details/gtgosjdyqf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.feifeiyinyue.top/Article/details/gtrqxdvmwk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jiagoushi.top/Article/details/gtnlmkaojx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jqgfzy.top/Article/details/gtgrpnbvgw.html

TS:   // 手写 Map<string, number>
来源：http://dali.gaohongyu789.top/Article/details/gtwjzxlcst.html

Java: // 手写 HashMap
来源：http://dali.shanyushiyangtech.top/Article/details/gtfsvpglbt.html

Go:   // 手写 map[int]int
来源：http://dali.zhixingplan.top/Article/details/gtjgbbzugz.html

Ruby: // 手写 Hash
来源：http://dali.yongpay.top/Article/details/gtgjfzvcif.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hnxiangtu.top/Article/details/gtdqdhhdqr.html

[N08] 生成全排列
来源：http://dali.hfpthk.cn/Article/details/gtaqyeuiej.html

Py:   itertools.permutations(arr)
来源：http://dali.sysykeji.top/Article/details/gtkikirhls.html

PHP:  // 手写递归交换
来源：http://dali.chenjidiqi.icu/Article/details/gtfpzskyvp.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gtdbvheacm.html

TS:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtnokyytgj.html

Java: // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gtfckztdhe.html

Go:   // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gtulqfpowb.html

Ruby: arr.permutation.to_a
来源：http://dali.dianchejie.cn/Article/details/gtnxfpkssy.html

C#:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjyvctnff.html

[N09] 栈与队列
来源：http://dali.c1oappe.top/Article/details/gtomsyxizz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hfpthk.cn/Article/details/gthcerntkc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gogol.net.cn/Article/details/gtcgllzdtq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hnqzz.top/Article/details/gtvtgdqgjn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhongyouzk.top/Article/details/gtnaqwdbhu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.nanxuanxn.top/Article/details/gthtgovoev.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ivvv.top/Article/details/gtucmgslls.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.dianchejie.cn/Article/details/gtvycjurqy.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yanxiufei.cn/Article/details/gtvzfzagsm.html

[N10] 链表节点定义
来源：http://dali.jinghuilouyu.cn/Article/details/gtdyymabuy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.chenzaomai.com/Article/details/gtzomrrkxm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yuxming.cn/Article/details/gtjfqnxyjz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.wangdashe.top/Article/details/gtitwfroab.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hfpthk.cn/Article/details/gttmbguswz.html

Java: class Node { int v; Node next; }
来源：http://dali.wangshuangyany.cn/Article/details/gthfpaxcic.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sweek.top/Article/details/gtxodeiszt.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkpzbmcab.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gzhubu.top/Article/details/gtdmatkakj.html

[N11] 二叉树中序遍历
来源：http://dali.hysaishi.cn/Article/details/gtkgqbuftm.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gzhubu.top/Article/details/gtcgxgzuvo.html

PHP:  // 手写递归函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtprkvtzbf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hongshengwenyu.top/Article/details/gtrjzyimsw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yanxiufei.cn/Article/details/gtcboxllip.html

Java: // 手写递归
来源：http://dali.c1oappe.top/Article/details/gtsmorzzur.html

Go:   // 手写递归
来源：http://dali.ivvv.top/Article/details/gtsdjmwjvp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinyuanbaomall.cn/Article/details/gtezpbpxrp.html

C#:   // 手写递归
来源：http://dali.aibaodan.cn/Article/details/gtomiyighr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yuanzhike.top/Article/details/gtrqtfiflu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.mhx1999.top/Article/details/gttbfybdup.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yj202588.top/Article/details/gtqnvgeekm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.redwolf501.top/Article/details/gtugruomlv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jiagoushi.top/Article/details/gtmcjzxvwi.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aibaodan.cn/Article/details/gtyznpharc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.meibo888.top/Article/details/gtwtyywwte.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.0kj1m.cn/Article/details/gtawnlonhu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sysykeji.top/Article/details/gtcerhcisl.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gticqzzmxz.html

O. 并发与异步
来源：http://dali.hnqzz.top/Article/details/gtlypuqell.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtkinoyttw.html

[O01] 启动一个线程
来源：http://dali.hammf.cn/Article/details/gtjcodynzc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jqgfzy.top/Article/details/gttaxgtfwr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sweek.top/Article/details/gtbavvzcwz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gtrelnmric.html

TS:   // 同 JS
来源：http://dali.shanyushiyangtech.top/Article/details/gtukpsevbu.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gtbdzakrhu.html

Go:   go f()
来源：http://dali.meibo888.top/Article/details/gtrqihulfk.html

Ruby: Thread.new { f }
来源：http://dali.hysaishi.cn/Article/details/gtwdqaiaez.html

C#:   Task.Run(() => F());
来源：http://dali.zhixingplan.top/Article/details/gtmosrxtna.html

[O02] 使用线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gtrqvkfewv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.fzhhl.top/Article/details/gtlkbpdvhx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhongyouzk.top/Article/details/gtiiwyrlsn.html

JS:   // worker_threads 线程池
来源：http://dali.smart0.xyz/Article/details/gtqntcatsi.html

TS:   // worker_threads 线程池
来源：http://dali.shzxlz.cn/Article/details/gteummuqde.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.gogol.net.cn/Article/details/gtxvasoyot.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsqdtxugc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.nanxuanxn.top/Article/details/gtioaswyzv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.tian-w.cn/Article/details/gthjemcjux.html

[O03] 加锁保护共享数据
来源：http://dali.quarkkingdee.top/Article/details/gtwlrwgbug.html

Py:   with lock: shared += 1
来源：http://dali.smart0.xyz/Article/details/gtebsashou.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jqgufenzy.top/Article/details/gtiwqbaono.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cashguo.top/Article/details/gtjgbbuyzs.html

TS:   // 同 JS
来源：http://dali.wangdashe.top/Article/details/gtfwizospp.html

Java: synchronized (this) { shared++; }
来源：http://dali.mhx1999.top/Article/details/gterbkdjti.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zycfv.cn/Article/details/gthdlryheq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.havefunace.top/Article/details/gtbpebcuaa.html

C#:   lock (gate) { shared++; }
来源：http://dali.guowangkeji.top/Article/details/gtgolhsras.html

[O04] 定义异步函数并等待
来源：http://dali.xinyue.icu/Article/details/gtryqjjguo.html

Py:   async def f():⏎    await g()
来源：http://dali.yj20258.top/Article/details/gtubsxvkwg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hysaishi.cn/Article/details/gtdluqmptr.html

JS:   async function f() { await g(); }
来源：http://dali.zycfv.cn/Article/details/gtfvqdjscs.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jlsjyb.cn/Article/details/gtyyajtwpv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yuanzhike.top/Article/details/gtjclfmcfi.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jlsjyb.cn/Article/details/gtxexwmfal.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shuidangran.top/Article/details/gtaldrcohy.html

C#:   async Task F() { await G(); }
来源：http://dali.shzxlz.cn/Article/details/gtbwlgjjcu.html

[O05] 并发执行并等待全部完成
来源：http://dali.cdnleiting.top/Article/details/gtsjgfqoan.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jianghu66.top/Article/details/gtcrvqenom.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jinqigfzy.top/Article/details/gtyquxqyqo.html

JS:   await Promise.all(tasks)
来源：http://dali.hammf.cn/Article/details/gtmhdrgqgv.html

TS:   await Promise.all(tasks)
来源：http://dali.gotoacloud.top/Article/details/gtegdpjbyg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhaomingkeji.xyz/Article/details/gttubeaybz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.c1oappe.top/Article/details/gtiekpzxtg.html

Ruby: threads.map(&:join)
来源：http://dali.sweek.top/Article/details/gtfjhoyjyx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.vqdsnc.cn/Article/details/gtuisttgjh.html

[O06] 使用进程池
来源：http://dali.zdqjudy.top/Article/details/gtbcfzolfi.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ehwqpu.com/Article/details/gtccnquibd.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cashguo.top/Article/details/gtkmlqmood.html

JS:   // child_process / cluster 模块
来源：http://dali.haohaochexian.top/Article/details/gtiurztpne.html

TS:   // child_process / cluster 模块
来源：http://dali.hywenlv.cn/Article/details/gtjhpzciia.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.9152youxi.cn/Article/details/gtnmggnsvp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.quarkkingdee.top/Article/details/gtmrzxfmok.html

Ruby: // fork 块
来源：http://dali.cheryme.top/Article/details/gtofboxnkn.html

C#:   Parallel.For
来源：http://dali.yvedp.cn/Article/details/gtiqvpwxjf.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtoiqpyshz.html

P. 常用工具函数
来源：http://dali.dashuyun.cn/Article/details/gtvokubmgk.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtdnqcjyfv.html

[P01] 生成 UUID
来源：http://dali.sxryk.cn/Article/details/gtyfrpevtf.html

Py:   str(uuid.uuid4())
来源：http://dali.snrcjt.cn/Article/details/gtzibzjmzz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.gogol.net.cn/Article/details/gtxotljzcq.html

JS:   crypto.randomUUID()
来源：http://dali.jianghu66.top/Article/details/gtcblzdfhw.html

TS:   crypto.randomUUID()
来源：http://dali.ivvv.top/Article/details/gtebrfxajw.html

Java: UUID.randomUUID().toString()
来源：http://dali.xinyue.icu/Article/details/gtqipqcbfm.html

Go:   // 用 github.com/google/uuid
来源：http://dali.bjfxy.top/Article/details/gtmezxwjey.html

Ruby: SecureRandom.uuid
来源：http://dali.ybcxt.top/Article/details/gthnluhqga.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.aizwys.cn/Article/details/gtpnaecugg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yongpay.top/Article/details/gtaacogggj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenjidiqi.icu/Article/details/gtytjnygni.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gotoacloud.top/Article/details/gtcxlspjpn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.meibo888.top/Article/details/gtlpcxeswj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.daxiang520.top/Article/details/gtnhpbzark.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj20258.top/Article/details/gtidyzgqke.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hysaishi.cn/Article/details/gtxhldfpev.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnxdpkvpv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.chenzaomai.com/Article/details/gtaodymxza.html

[P03] 生成短随机字符串
来源：http://dali.sweek.top/Article/details/gtnbckumsg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jqgfzy.top/Article/details/gtkhiyizgt.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.chenlongwang.top/Article/details/gtitxpnksy.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj202588.top/Article/details/gtnfbdjevi.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.guannengcc.top/Article/details/gtpuupblag.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cashguo.top/Article/details/gtslcbnkgo.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.aizwys.cn/Article/details/gtdaqnuvkd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xylfe.cn/Article/details/gtqyypejme.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.quarkkingdee.top/Article/details/gtpoludohr.html

[P04] 求长度
来源：http://dali.xylfe.cn/Article/details/gtpdcmivwf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yonumen.top/Article/details/gtxjhfhpor.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gtbxotlnsr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.0kj1m.cn/Article/details/gtgpdkdhrb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gotoacloud.top/Article/details/gtuiaxhlul.html

Java: list.size();  map.size();  s.length()
来源：http://dali.meibo888.top/Article/details/gtjmbmmmqd.html

Go:   len(arr);  len(m)
来源：http://dali.hongshengwenyu.top/Article/details/gtfusjshdc.html

Ruby: x.length;  x.size
来源：http://dali.daxiang520.top/Article/details/gtgsiyvlok.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yj20258888.top/Article/details/gtrughfutt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.vqdsnc.cn/Article/details/gterwovanw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yj20258888.top/Article/details/gtnbusmeka.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cucudq.cn/Article/details/gtezsagxyg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jqgfzy.top/Article/details/gtazmdxvju.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hongshengwenyu.top/Article/details/gtrtsymghr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.tianlin.xyz/Article/details/gtexbkdfzs.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ybcxt.top/Article/details/gtvwjxgfpu.html

Ruby: a == b
来源：http://dali.nwbrower.top/Article/details/gtjfttjvxy.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.gzhubu.top/Article/details/gtrionsogd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.meibo888.top/Article/details/gtxzpdefnb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ivvv.top/Article/details/gtrwhotdrs.html

PHP:  if (empty($x)) {}
来源：http://dali.guannengcc.top/Article/details/gtnyebgnyj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yongpay.top/Article/details/gtplpnahun.html

TS:   if (x == null) {}
来源：http://dali.cqqwz.cn/Article/details/gtdplbespd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtkmbkiiwv.html

Go:   if x == nil {}
来源：http://dali.hysaishi.cn/Article/details/gtepjtoznt.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinqigfzy.top/Article/details/gtvrjgpdea.html

C#:   if (x is null) {}
来源：http://dali.daxiang520.top/Article/details/gtonmblpag.html

[P07] 防抖与节流
来源：http://dali.jinqigufen.top/Article/details/gtnjpegsum.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.svipenyu.cn/Article/details/gtxtpmzgfx.html

PHP:  // 手写时间戳比较
来源：http://dali.hammf.cn/Article/details/gtqbeumypd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sxryk.cn/Article/details/gtuhktvfjs.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuetiantiany.cn/Article/details/gtksgimdjd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hysaishi.cn/Article/details/gtjyyypkar.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.vqdsnc.cn/Article/details/gtuetbcdbx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cashguo.top/Article/details/gtrgoirhek.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sufxvd.cn/Article/details/gtowployrx.html

[P08] 处理浮点精度问题
来源：http://dali.jyoumei.cn/Article/details/gtdrmewwep.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.daria6918.cn/Article/details/gtluxwanbz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.bjfxy.top/Article/details/gtvzsnyouf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.aizwys.cn/Article/details/gtplydsrdf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbbjxdhpf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shangyingyoupin.top/Article/details/gtingfjycf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.wangshuangyany.cn/Article/details/gtglsjdcbh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.tianlin.xyz/Article/details/gtugocpzwy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhoulong.xyz/Article/details/gtquatmgsl.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtzeffygtc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sweek.top/Article/details/gtvszorecd.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtpnllxhcm.html

[Q01] 创建表
来源：http://dali.smart0.xyz/Article/details/gtoiwkxjih.html


<!-- 参考信息 -->