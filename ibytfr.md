代发 wailian999

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cqqwz.cn/Article/details/gtdlvqttgx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.quarkkingdee.top/Article/details/gtoozzwvhm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhiwuduotai.top/Article/details/gtdlyctqfa.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xinyue.icu/Article/details/gttyzilibk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.chenlongwang.top/Article/details/gtgngpqkqi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.smart0.xyz/Article/details/gtczzfpefw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yj202588.top/Article/details/gtzifddhqc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.snrcjt.cn/Article/details/gtnnwzjerh.html

[M04] 获取当前工作目录
来源：http://dali.xinyue.icu/Article/details/gtxletwpbk.html

Py:   os.getcwd()
来源：http://dali.kuanghao11.cn/Article/details/gtfskffvwl.html

PHP:  getcwd();
来源：http://dali.wangshuangyany.cn/Article/details/gtjnfcqzvb.html

JS:   process.cwd()
来源：http://dali.gzhubu.top/Article/details/gtvupxalnh.html

TS:   process.cwd()
来源：http://dali.yvedp.cn/Article/details/gtdtuqlnjv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.dianchejie.cn/Article/details/gtbpgczoeb.html

Go:   os.Getwd()
来源：http://dali.tanke756.top/Article/details/gtbvxkwdcp.html

Ruby: Dir.pwd
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxxqvtaak.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yuxming.cn/Article/details/gtbcjcekhz.html

[M05] 设置退出码
来源：http://dali.jinqigfzy.top/Article/details/gtvbuwexjs.html

Py:   sys.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtuohgopoc.html

PHP:  exit(1);
来源：http://dali.cashguo.top/Article/details/gtzysdruhk.html

JS:   process.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtkbuorddf.html

TS:   process.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gtktfwutrv.html

Java: System.exit(1)
来源：http://dali.havefunace.top/Article/details/gttigldsgo.html

Go:   os.Exit(1)
来源：http://dali.dashuyun.cn/Article/details/gthusvwymp.html

Ruby: exit 1
来源：http://dali.wangdashe.top/Article/details/gtxgrartdz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.feifeiyinyue.top/Article/details/gtqrzhivxd.html

[M06] 向标准错误输出
来源：http://dali.jyoumei.cn/Article/details/gtoqzrvthv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gaohongyu789.top/Article/details/gtboqgckgd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.redwolf501.top/Article/details/gtamojbewy.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gtnrxphggh.html

TS:   console.error("err")
来源：http://dali.yj20258888.top/Article/details/gtcpxuddad.html

Java: System.err.println("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtafwhjtih.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hysaishi.cn/Article/details/gtihvolyhp.html

Ruby: warn "err"
来源：http://dali.gogol.net.cn/Article/details/gtymploqdm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.bjfxy.top/Article/details/gtqaxuiwny.html

[M07] 判断是否为主入口
来源：http://dali.kuanghao11.cn/Article/details/gtbkuywyxb.html

Py:   if __name__ == "__main__":
来源：http://dali.ydzc1.top/Article/details/gtrrsvogli.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shuidangran.top/Article/details/gtlzdqrtck.html

JS:   require.main === module
来源：http://dali.jqgufenzy.top/Article/details/gtehfyfhkj.html

TS:   require.main === module
来源：http://dali.yuxming.cn/Article/details/gtxyuoomdw.html

Java: public static void main(String[] args)
来源：http://dali.yangfankeji.com/Article/details/gtgugskquy.html

Go:   func main()
来源：http://dali.chenzaomai.com/Article/details/gtaqckejyr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ehwqpu.com/Article/details/gtojtedkkd.html

C#:   static void Main(string[] args)
来源：http://dali.andypj.xyz/Article/details/gtviottpfx.html

[M08] 获取系统与运行时信息
来源：http://dali.yonumen.top/Article/details/gtcgwpbqki.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xinyue.icu/Article/details/gtdvucxtau.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.wangdashe.top/Article/details/gtupdvavej.html

JS:   process.platform;  process.version
来源：http://dali.aibaodan.cn/Article/details/gtmmqxzpfg.html

TS:   process.platform;  process.version
来源：http://dali.kuanghao11.cn/Article/details/gtxszqtviu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ehwqpu.com/Article/details/gtkoduplhf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shanyushiyangtech.top/Article/details/gtyaehxvjp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yvedp.cn/Article/details/gtpnfhknmm.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hnqzz.top/Article/details/gtvgvnnlxg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtedrsqiap.html

N. 数据结构与算法
来源：http://dali.yueranfly.top/Article/details/gtfztnageg.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtwlzstbxx.html

[N01] 二分查找（有序数组）
来源：http://dali.snrcjt.cn/Article/details/gtvpcdfiqm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtripqknbi.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xinyue.icu/Article/details/gtsrrefmvq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tianlin.xyz/Article/details/gtpinfydfr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenjidiqi.icu/Article/details/gtaoqwuhjr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtjpcgvegu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtlxfygomy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ybcxt.top/Article/details/gtfbvcgywj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtxdlbndnv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.dianchejie.cn/Article/details/gtugkoffdk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.wangshuangyany.cn/Article/details/gtohhjqgvz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cashguo.top/Article/details/gttncwbbjj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjypmumsb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shangyingyoupin.top/Article/details/gtmltyawwf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.svipenyu.cn/Article/details/gtivvkcgid.html

Go:   slices.Sort(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnfbgitcn.html

Ruby: arr.sort
来源：http://dali.vqdsnc.cn/Article/details/gtijyqvecb.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ydzc1.top/Article/details/gtyukgsmkt.html

[N03] 快速排序（分治示例）
来源：http://dali.nanxinkj.top/Article/details/gtbjhzigrl.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.quarkkingdee.top/Article/details/gtrzwaqstm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinqigfzy.top/Article/details/gtdxnzekyh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhiwuduotai.top/Article/details/gtgrxbvebg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhiwuduotai.top/Article/details/gttaoosfqw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.aibaodan.cn/Article/details/gtegwmpjun.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yonumen.top/Article/details/gtpzrilvec.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yongpay.top/Article/details/gtpturswle.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yj20258.top/Article/details/gtlzeiznbm.html

[N04] 斐波那契数列
来源：http://dali.tianlin.xyz/Article/details/gtsyifmgum.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xuanzx.com/Article/details/gtdqztcfxv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cqqwz.cn/Article/details/gtertlbhvf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenzaomai.com/Article/details/gtpfhziuxh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dashuyun.cn/Article/details/gtqofcgqlr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.andypj.xyz/Article/details/gttpgrxpfe.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.birdmap.top/Article/details/gtzhwevoga.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenzaomai.com/Article/details/gtkhtvvmsl.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.meibo888.top/Article/details/gtlosfbotf.html

[N05] 最大公约数
来源：http://dali.kuanghao11.cn/Article/details/gtcedkkmgt.html

Py:   math.gcd(a, b)
来源：http://dali.xziqi.cn/Article/details/gtlahnwxjn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.dashuyun.cn/Article/details/gtjzzlwsee.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ivvv.top/Article/details/gtlqrqumxk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.birdmap.top/Article/details/gtntzifixy.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhixingplan.top/Article/details/gtcdbpbcvw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sxryk.cn/Article/details/gtaqcnnzwb.html

Ruby: a.gcd(b)
来源：http://dali.yvedp.cn/Article/details/gtxdsjpmtr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.birdmap.top/Article/details/gtbbdekhiz.html

[N06] 判断回文字符串
来源：http://dali.fzhhl.top/Article/details/gtdqsnajms.html

Py:   s == s[::-1]
来源：http://dali.sxryk.cn/Article/details/gterbgoquh.html

PHP:  $s === strrev($s);
来源：http://dali.yuanzhike.top/Article/details/gtapqpzaiv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gtgfcppmse.html

TS:   s === [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gtpsraojbm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.meibo888.top/Article/details/gtbnstezbj.html

Go:   // 双指针从两端比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttfjhxmhp.html

Ruby: s == s.reverse
来源：http://dali.jlsjyb.cn/Article/details/gtnnltakkl.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.feifeiyinyue.top/Article/details/gtzubfvjnp.html

[N07] 两数之和（返回下标）
来源：http://dali.yj202588.top/Article/details/gtnrvdwzsi.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.birdmap.top/Article/details/gtvsgqwzpe.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cqqwz.cn/Article/details/gtgqadajuw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhiwuduotai.top/Article/details/gtrxmorqnc.html

TS:   // 手写 Map<string, number>
来源：http://dali.daxiang520.top/Article/details/gtuimxzsat.html

Java: // 手写 HashMap
来源：http://dali.tanke756.top/Article/details/gtxtabovia.html

Go:   // 手写 map[int]int
来源：http://dali.jinqigfzy.top/Article/details/gtymzkljoo.html

Ruby: // 手写 Hash
来源：http://dali.meibo888.top/Article/details/gtwrhfrydq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhoulong.xyz/Article/details/gtnbfqsebj.html

[N08] 生成全排列
来源：http://dali.sweek.top/Article/details/gtxltvxkqm.html

Py:   itertools.permutations(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtwpvqnsgl.html

PHP:  // 手写递归交换
来源：http://dali.mhx1999.top/Article/details/gtwcmmbovw.html

JS:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gtlgycdsfb.html

TS:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gtuuuhmxsl.html

Java: // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gttazvnmjm.html

Go:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gturxuyjsr.html

Ruby: arr.permutation.to_a
来源：http://dali.jianghu66.top/Article/details/gtzekuoglz.html

C#:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gtsdvyfixm.html

[N09] 栈与队列
来源：http://dali.tian-w.cn/Article/details/gtzltqjtsa.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jlsjyb.cn/Article/details/gtvadizlbf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.wangdashe.top/Article/details/gtxihscerg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gtnxizjeps.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.sweek.top/Article/details/gtydrmiell.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cheryme.top/Article/details/gtkklxrgdn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.chenjidiqi.icu/Article/details/gtplqfjxug.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gtyequvrwl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.andypj.xyz/Article/details/gticirrlhq.html

[N10] 链表节点定义
来源：http://dali.sxryk.cn/Article/details/gtwpssgmod.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ppjwa.cn/Article/details/gtmwxnphwj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.daxiang520.top/Article/details/gtwvypwltp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ybcxt.top/Article/details/gtjkkrwhye.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xziqi.cn/Article/details/gteycnyoqt.html

Java: class Node { int v; Node next; }
来源：http://dali.jinqigfzy.top/Article/details/gtoohjypvn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.nwbrower.top/Article/details/gtimvyrxdy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shangyingyoupin.top/Article/details/gthlcsnyzr.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gzhubu.top/Article/details/gtmsouyixp.html

[N11] 二叉树中序遍历
来源：http://dali.ppjwa.cn/Article/details/gtveiqfuyp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jyoumei.cn/Article/details/gtvckqawhr.html

PHP:  // 手写递归函数
来源：http://dali.gotoacloud.top/Article/details/gtamkelhsb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.andypj.xyz/Article/details/gtjazwpnng.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xuetiantiany.cn/Article/details/gtqzhzwwlk.html

Java: // 手写递归
来源：http://dali.sufxvd.cn/Article/details/gtaylfmaer.html

Go:   // 手写递归
来源：http://dali.smart0.xyz/Article/details/gthunkjvul.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.havefunace.top/Article/details/gtqkabaxbn.html

C#:   // 手写递归
来源：http://dali.nanxuanxn.top/Article/details/gtjabssjux.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.kuanghao11.cn/Article/details/gtzkohojaa.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hywenlv.cn/Article/details/gtxuktsatu.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.sxryk.cn/Article/details/gtfzlfbzzw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenzaomai.com/Article/details/gtrdrhdmri.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jlsjyb.cn/Article/details/gtjppojrpm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenzaomai.com/Article/details/gthjyjrtqm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.fengsongda.top/Article/details/gtpetkdpcf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhoulong.xyz/Article/details/gtowafutlc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ppjwa.cn/Article/details/gtsnapyakm.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtowjmqzwz.html

O. 并发与异步
来源：http://dali.fzhhl.top/Article/details/gtfsqnazvz.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtxfdntrct.html

[O01] 启动一个线程
来源：http://dali.ydzc1.top/Article/details/gtnmcwlsyz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.daria6918.cn/Article/details/gtcjqrameh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shzxlz.cn/Article/details/gtbktsdyjr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yueranfly.top/Article/details/gtcnjtkurb.html

TS:   // 同 JS
来源：http://dali.yuxming.cn/Article/details/gtkbfbtvba.html

Java: new Thread(() -> f()).start()
来源：http://dali.yj202588.top/Article/details/gtsbegeayc.html

Go:   go f()
来源：http://dali.hnqzz.top/Article/details/gtctrjkfnc.html

Ruby: Thread.new { f }
来源：http://dali.yuxming.cn/Article/details/gtbpldcssb.html

C#:   Task.Run(() => F());
来源：http://dali.cqqwz.cn/Article/details/gttoswfuzt.html

[O02] 使用线程池
来源：http://dali.mhx1999.top/Article/details/gtpokdfbeq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhiwuduotai.top/Article/details/gtitkprsxv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ybcxt.top/Article/details/gtolyrleyx.html

JS:   // worker_threads 线程池
来源：http://dali.hysaishi.cn/Article/details/gtixndffkz.html

TS:   // worker_threads 线程池
来源：http://dali.yuxming.cn/Article/details/gtzapfgycc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinqigufen.top/Article/details/gthnozinjy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xuanzx.com/Article/details/gtfznuewvc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttgksumdc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinqigfzy.top/Article/details/gtufumrdyk.html

[O03] 加锁保护共享数据
来源：http://dali.chenzaomai.com/Article/details/gtokyiahga.html

Py:   with lock: shared += 1
来源：http://dali.yueranfly.top/Article/details/gtuazfygpt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gogol.net.cn/Article/details/gtaherbkrj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.sweek.top/Article/details/gtgofgzias.html

TS:   // 同 JS
来源：http://dali.yj20258888.top/Article/details/gtbehmhept.html

Java: synchronized (this) { shared++; }
来源：http://dali.hongshengwenyu.top/Article/details/gtqutmbtgb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yangfankeji.com/Article/details/gtxqtgkyrr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.tanke756.top/Article/details/gtuoeetbbr.html

C#:   lock (gate) { shared++; }
来源：http://dali.ivvv.top/Article/details/gtugkybhaq.html

[O04] 定义异步函数并等待
来源：http://dali.daria6918.cn/Article/details/gthiqsuwyn.html

Py:   async def f():⏎    await g()
来源：http://dali.guannengcc.top/Article/details/gtmwuwjxaj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.0kj1m.cn/Article/details/gtrpymhrcw.html

JS:   async function f() { await g(); }
来源：http://dali.daria6918.cn/Article/details/gtltdkrdar.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jqgfzy.top/Article/details/gtcextwxuw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.wangshuangyany.cn/Article/details/gtfphpefzp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zycfv.cn/Article/details/gtquggxbvq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.birdmap.top/Article/details/gtiwjvzlbs.html

C#:   async Task F() { await G(); }
来源：http://dali.haohaochexian.top/Article/details/gtzlbbrcte.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmfwblztq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jyoumei.cn/Article/details/gtsmkmgxbd.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrkcaczwo.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gtqwunqbuo.html

TS:   await Promise.all(tasks)
来源：http://dali.fzhhl.top/Article/details/gtufhloenz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cqqwz.cn/Article/details/gtixxgamcv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.bjfxy.top/Article/details/gthgrrauzw.html

Ruby: threads.map(&:join)
来源：http://dali.sysykeji.top/Article/details/gtgxgiyexc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sweek.top/Article/details/gtlovmfvbq.html

[O06] 使用进程池
来源：http://dali.hnqzz.top/Article/details/gtmqmuomzr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hnqzz.top/Article/details/gtxawiipey.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gogol.net.cn/Article/details/gtqyzzgxno.html

JS:   // child_process / cluster 模块
来源：http://dali.zhixingplan.top/Article/details/gtczmdhcbj.html

TS:   // child_process / cluster 模块
来源：http://dali.daria6918.cn/Article/details/gtgogfisqi.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.vqdsnc.cn/Article/details/gtexbafagy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sweek.top/Article/details/gtqjetibwb.html

Ruby: // fork 块
来源：http://dali.pengpengdd.cyou/Article/details/gtfgbsshmx.html

C#:   Parallel.For
来源：http://dali.cucudq.cn/Article/details/gtsdetxzdp.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtyhelqbnu.html

P. 常用工具函数
来源：http://dali.meibo888.top/Article/details/gtkwixxvnx.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtvtqmoyle.html

[P01] 生成 UUID
来源：http://dali.yj20258.top/Article/details/gtceaokpxo.html

Py:   str(uuid.uuid4())
来源：http://dali.gogol.net.cn/Article/details/gtujvuosdx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cqqwz.cn/Article/details/gtqykftgtg.html

JS:   crypto.randomUUID()
来源：http://dali.iojbl.cn/Article/details/gtiansrpqt.html

TS:   crypto.randomUUID()
来源：http://dali.shangyingyoupin.top/Article/details/gtvjaogjjs.html

Java: UUID.randomUUID().toString()
来源：http://dali.ydzc1.top/Article/details/gtiglttyri.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hfpthk.cn/Article/details/gtredlxnmg.html

Ruby: SecureRandom.uuid
来源：http://dali.cucudq.cn/Article/details/gtmmbzrico.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.chenzaomai.com/Article/details/gtyagbgnxw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hnxiangtu.top/Article/details/gtiflqygps.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.kuanghao11.cn/Article/details/gtvwsehvra.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yanxiufei.cn/Article/details/gtvkwrtiik.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jqgufenzy.top/Article/details/gtsnfoggbh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.meibo888.top/Article/details/gtyhwmapps.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.chenzaomai.com/Article/details/gtolwbxidr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.tianlin.xyz/Article/details/gtgqcfizzg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.smart0.xyz/Article/details/gtihumljya.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.tian-w.cn/Article/details/gtszfgvcse.html

[P03] 生成短随机字符串
来源：http://dali.tian-w.cn/Article/details/gtdlbxuvbp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.snrcjt.cn/Article/details/gtjowajdwg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.dashuyun.cn/Article/details/gtadcwjksu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gotoacloud.top/Article/details/gtwenyjyns.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shuidangran.top/Article/details/gthyraehep.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.kuanghao11.cn/Article/details/gtmoowahcs.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.andypj.xyz/Article/details/gtrzijfzuc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yj202588.top/Article/details/gtzdiqnskl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hfpthk.cn/Article/details/gtiqfqhero.html

[P04] 求长度
来源：http://dali.gogol.net.cn/Article/details/gtixlqfkaq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtntsuprqv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gtzmlgyvfg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dianchejie.cn/Article/details/gtzbrlgxwn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sxryk.cn/Article/details/gtpzvseidk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hfpthk.cn/Article/details/gtsypinqij.html

Go:   len(arr);  len(m)
来源：http://dali.jqgfzy.top/Article/details/gtwqbjcgpu.html

Ruby: x.length;  x.size
来源：http://dali.xziqi.cn/Article/details/gtnghiutra.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yanxiufei.cn/Article/details/gtutyusxib.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hysaishi.cn/Article/details/gtibmypsxf.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ehwqpu.com/Article/details/gtzvihkozk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cqqwz.cn/Article/details/gtssvrtfsy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jqgfzy.top/Article/details/gtfmiuapbx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.dashuyun.cn/Article/details/gtimxvency.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cqqwz.cn/Article/details/gtvhngivad.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.nanxuanxn.top/Article/details/gtgzabdkxz.html

Ruby: a == b
来源：http://dali.daxiang520.top/Article/details/gttfqpicug.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkzakwfqk.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.guannengcc.top/Article/details/gtezyjfjgp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbudamxso.html

PHP:  if (empty($x)) {}
来源：http://dali.havefunace.top/Article/details/gtdfuzkfja.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hywenlv.cn/Article/details/gtmxckjsri.html

TS:   if (x == null) {}
来源：http://dali.ydzc1.top/Article/details/gtrknmlcvp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenlongwang.top/Article/details/gtpusjcmnj.html

Go:   if x == nil {}
来源：http://dali.bjfxy.top/Article/details/gttbncbqnh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yonumen.top/Article/details/gtixiltcfy.html

C#:   if (x is null) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtenbnaevd.html

[P07] 防抖与节流
来源：http://dali.ydzc1.top/Article/details/gtnvyriuox.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shanyushiyangtech.top/Article/details/gtgazvnjre.html

PHP:  // 手写时间戳比较
来源：http://dali.ppjwa.cn/Article/details/gthuvllari.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.mhx1999.top/Article/details/gtuhadujon.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yvedp.cn/Article/details/gtkjqpkefk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.nanxuanxn.top/Article/details/gtqeuorwcp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.wangshuangyany.cn/Article/details/gtgrczwxik.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.iojbl.cn/Article/details/gtwkunblal.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zdqjudy.top/Article/details/gtbpadtgig.html

[P08] 处理浮点精度问题
来源：http://dali.jiagoushi.top/Article/details/gthfalxhdx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.chenlongwang.top/Article/details/gtojzqbneo.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.redwolf501.top/Article/details/gtjezhtrde.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.tian-w.cn/Article/details/gtyllxzhbd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.wangdashe.top/Article/details/gtnjfihgzi.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhoulong.xyz/Article/details/gtfvnmhjpa.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shanyushiyangtech.top/Article/details/gtkpnwjvqp.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zdqjudy.top/Article/details/gtoxnfifui.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.quarkkingdee.top/Article/details/gtobzvvxha.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtriovihiu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.316326.xyz/Article/details/gtwhxsguyi.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtnzcoaafc.html

[Q01] 创建表
来源：http://dali.xylfe.cn/Article/details/gtgkhwrgqq.html


<!-- 参考信息 -->