代发 wailian999

[M04] 获取当前工作目录
来源：http://dali.jyoumei.cn/Article/details/gtsygjlsfn.html

Py:   os.getcwd()
来源：http://dali.ppjwa.cn/Article/details/gtecuaxkdo.html

PHP:  getcwd();
来源：http://dali.ybcxt.top/Article/details/gtulqzclim.html

JS:   process.cwd()
来源：http://dali.9152youxi.cn/Article/details/gthucjmwwz.html

TS:   process.cwd()
来源：http://dali.shzxlz.cn/Article/details/gtdofxlqnk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.guowangkeji.top/Article/details/gtysbqpuxp.html

Go:   os.Getwd()
来源：http://dali.dianchejie.cn/Article/details/gtxkaffcyt.html

Ruby: Dir.pwd
来源：http://dali.hysaishi.cn/Article/details/gtvzxvgiuk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdzmwjqul.html

[M05] 设置退出码
来源：http://dali.guannengcc.top/Article/details/gtrvaklrse.html

Py:   sys.exit(1)
来源：http://dali.ivvv.top/Article/details/gtxzqymtbn.html

PHP:  exit(1);
来源：http://dali.jiagoushi.top/Article/details/gtqofypwhb.html

JS:   process.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gtfqpgiyob.html

TS:   process.exit(1)
来源：http://dali.mhx1999.top/Article/details/gttpursrul.html

Java: System.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gthkpkqidt.html

Go:   os.Exit(1)
来源：http://dali.daxiang520.top/Article/details/gtasttmnnl.html

Ruby: exit 1
来源：http://dali.yongpay.top/Article/details/gtmlydfjpd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yuanzhike.top/Article/details/gtcaxorefa.html

[M06] 向标准错误输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcjvngupg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.wangshuangyany.cn/Article/details/gtffsbhghq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xuetiantiany.cn/Article/details/gteyszuydv.html

JS:   console.error("err")
来源：http://dali.yongpay.top/Article/details/gtteszxcvv.html

TS:   console.error("err")
来源：http://dali.daxiang520.top/Article/details/gtceytlpcw.html

Java: System.err.println("err")
来源：http://dali.hnqzz.top/Article/details/gtnpdudotx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ppjwa.cn/Article/details/gtlavoifgz.html

Ruby: warn "err"
来源：http://dali.haohaochexian.top/Article/details/gtkexcjubl.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cqqwz.cn/Article/details/gtuhfletje.html

[M07] 判断是否为主入口
来源：http://dali.tian-w.cn/Article/details/gtbxzgsrou.html

Py:   if __name__ == "__main__":
来源：http://dali.nanxuanxn.top/Article/details/gtbiaylsqw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yj20258.top/Article/details/gtdycwelnm.html

JS:   require.main === module
来源：http://dali.ybcxt.top/Article/details/gtjaqrpzkb.html

TS:   require.main === module
来源：http://dali.jqgufenzy.top/Article/details/gtssernytj.html

Java: public static void main(String[] args)
来源：http://dali.haohaochexian.top/Article/details/gtdmaehmxg.html

Go:   func main()
来源：http://dali.wangshuangyany.cn/Article/details/gtcygzjjvu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfzjejrvt.html

C#:   static void Main(string[] args)
来源：http://dali.hywenlv.cn/Article/details/gtjgsvhcbh.html

[M08] 获取系统与运行时信息
来源：http://dali.zycfv.cn/Article/details/gtmwdbsgmj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzindqxzs.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jyoumei.cn/Article/details/gtfkdvuzdb.html

JS:   process.platform;  process.version
来源：http://dali.hammf.cn/Article/details/gtktkmwpxq.html

TS:   process.platform;  process.version
来源：http://dali.cqqwz.cn/Article/details/gtkbjkkugb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtegkoycwi.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.fengsongda.top/Article/details/gtqhxjxfqv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gzhubu.top/Article/details/gtmxiddcbt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.pycfn.com/Article/details/gtgttyxsng.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtmwhcgmid.html

N. 数据结构与算法
来源：http://dali.jqgufenzy.top/Article/details/gtnqmvtnnk.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtnkpwcovu.html

[N01] 二分查找（有序数组）
来源：http://dali.sxryk.cn/Article/details/gtrrdlyhus.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtfubiphyk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.meibo888.top/Article/details/gtwzprxhxr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.9152youxi.cn/Article/details/gtkgofmzsf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sufxvd.cn/Article/details/gtagwgwmmt.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cashguo.top/Article/details/gtywwwzbpm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtxmquglwy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nanxinkj.top/Article/details/gtwwjvwgty.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gtfvnvnigb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.svipenyu.cn/Article/details/gtajczgzhj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tanke756.top/Article/details/gtlwzxmmwv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.wangdashe.top/Article/details/gtreairbqv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zycfv.cn/Article/details/gtquqxyvzs.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj202588.top/Article/details/gtsnrmgdbz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.bjfxy.top/Article/details/gtflatezti.html

Go:   slices.Sort(arr)
来源：http://dali.cqqwz.cn/Article/details/gtpeykozeq.html

Ruby: arr.sort
来源：http://dali.xylfe.cn/Article/details/gtmrwuuhhn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hnqzz.top/Article/details/gtouffchgi.html

[N03] 快速排序（分治示例）
来源：http://dali.shangyingyoupin.top/Article/details/gtmninpput.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yuxming.cn/Article/details/gtpaevygcf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hfpthk.cn/Article/details/gtcvwlosxv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hysaishi.cn/Article/details/gtwsaukvir.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hammf.cn/Article/details/gtcjrwlcnm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjsyyaslk.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj20258888.top/Article/details/gthemotgoh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhengqikj.top/Article/details/gtlbhcdlur.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.daxiang520.top/Article/details/gtmpcspobd.html

[N04] 斐波那契数列
来源：http://dali.iojbl.cn/Article/details/gttnrwxjfc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sysykeji.top/Article/details/gtnqeeswyd.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jqgfzy.top/Article/details/gtdfdjwoti.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.quarkkingdee.top/Article/details/gthbvkgigv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.svipenyu.cn/Article/details/gtobmgslte.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cheryme.top/Article/details/gtnuafjitg.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shzxlz.cn/Article/details/gtuugxzbec.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtfxjlpyjm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtcmfzfpse.html

[N05] 最大公约数
来源：http://dali.zhongyouzk.top/Article/details/gttruobnrp.html

Py:   math.gcd(a, b)
来源：http://dali.zhiwuduotai.top/Article/details/gtvasinhiv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gotoacloud.top/Article/details/gtrakuniwi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pycfn.com/Article/details/gtrwimhnfc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daria6918.cn/Article/details/gtnezczsco.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.fzhhl.top/Article/details/gtiycexecy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.bjfxy.top/Article/details/gtyzifkdau.html

Ruby: a.gcd(b)
来源：http://dali.haohaochexian.top/Article/details/gtsizqbakr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhixingplan.top/Article/details/gtfqzccuyo.html

[N06] 判断回文字符串
来源：http://dali.gotoacloud.top/Article/details/gtptubfjln.html

Py:   s == s[::-1]
来源：http://dali.smart0.xyz/Article/details/gtjnysyaws.html

PHP:  $s === strrev($s);
来源：http://dali.guowangkeji.top/Article/details/gtzbnlizfl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gtlhgrlxtf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gtqmvjkzxd.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.havefunace.top/Article/details/gtfkgjchbr.html

Go:   // 双指针从两端比较
来源：http://dali.wangshuangyany.cn/Article/details/gtxsxmwoue.html

Ruby: s == s.reverse
来源：http://dali.snrcjt.cn/Article/details/gthjtjawzg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.0kj1m.cn/Article/details/gtdoncuabw.html

[N07] 两数之和（返回下标）
来源：http://dali.chenjidiqi.icu/Article/details/gtkurynlwv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhongyouzk.top/Article/details/gtdncnrzsu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hammf.cn/Article/details/gtkgkrvptm.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgomagjhm.html

TS:   // 手写 Map<string, number>
来源：http://dali.hfpthk.cn/Article/details/gtimrhucuq.html

Java: // 手写 HashMap
来源：http://dali.daria6918.cn/Article/details/gtvsbcvsoy.html

Go:   // 手写 map[int]int
来源：http://dali.hongshengwenyu.top/Article/details/gtwqemlcqv.html

Ruby: // 手写 Hash
来源：http://dali.yanxiufei.cn/Article/details/gtfpdvdjxv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yj202588.top/Article/details/gtahxrmexy.html

[N08] 生成全排列
来源：http://dali.xuanzx.com/Article/details/gtifsbieed.html

Py:   itertools.permutations(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtdkrmzmmt.html

PHP:  // 手写递归交换
来源：http://dali.shangyingyoupin.top/Article/details/gtazksafql.html

JS:   // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gtzciwjndj.html

TS:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtxvihbhfu.html

Java: // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gtvuajmlnu.html

Go:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gtjngvjjjg.html

Ruby: arr.permutation.to_a
来源：http://dali.zhongyouzk.top/Article/details/gtqugeryeh.html

C#:   // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gtenoipeqn.html

[N09] 栈与队列
来源：http://dali.aibaodan.cn/Article/details/gtnwvplcbk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.9152youxi.cn/Article/details/gtzycoxxje.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hnxiangtu.top/Article/details/gtidhjkzzy.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtknlapzgw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.chenjidiqi.icu/Article/details/gtiddbzhiq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yuanzhike.top/Article/details/gtensfrybw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sysykeji.top/Article/details/gtjiyybbcl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.redwolf501.top/Article/details/gtskhwehts.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yueranfly.top/Article/details/gtgnjeredd.html

[N10] 链表节点定义
来源：http://dali.ybcxt.top/Article/details/gtyiekfbpm.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.nanxinkj.top/Article/details/gtymxcwgbo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.havefunace.top/Article/details/gtxdnmdsji.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xziqi.cn/Article/details/gtlczaigzl.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.nanxuanxn.top/Article/details/gtcjpwfnws.html

Java: class Node { int v; Node next; }
来源：http://dali.smart0.xyz/Article/details/gtbgzgzkkm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hnqzz.top/Article/details/gtiuhadgae.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jlsjyb.cn/Article/details/gtgteqnhje.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jqgfzy.top/Article/details/gtavbafxhg.html

[N11] 二叉树中序遍历
来源：http://dali.dianchejie.cn/Article/details/gtstsojqmm.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jlsjyb.cn/Article/details/gtsfpotine.html

PHP:  // 手写递归函数
来源：http://dali.zhoulong.xyz/Article/details/gtennpbnmp.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.feifeiyinyue.top/Article/details/gtkkqjzwjt.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgufenzy.top/Article/details/gtndsbrhcf.html

Java: // 手写递归
来源：http://dali.bjfxy.top/Article/details/gtggcnpjpd.html

Go:   // 手写递归
来源：http://dali.snrcjt.cn/Article/details/gtvfzltxxe.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.redwolf501.top/Article/details/gtaoqvswqk.html

C#:   // 手写递归
来源：http://dali.svipenyu.cn/Article/details/gthsewqzsv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yueranfly.top/Article/details/gttsmpuomf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.daxiang520.top/Article/details/gttsrfdvnk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hammf.cn/Article/details/gtalsuonni.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sufxvd.cn/Article/details/gtiufqnoph.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.quarkkingdee.top/Article/details/gtdsnpazou.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xinyue.icu/Article/details/gtppjxuntf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.redwolf501.top/Article/details/gtgvspbflc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cucudq.cn/Article/details/gtdtqjtszf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gtooidjzty.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtmshclkzf.html

O. 并发与异步
来源：http://dali.havefunace.top/Article/details/gtqoksqazm.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtarkxsqpp.html

[O01] 启动一个线程
来源：http://dali.chenjidiqi.icu/Article/details/gtfctkcsmj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gotoacloud.top/Article/details/gtpwuyaugy.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtmwnebute.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj202588.top/Article/details/gtqljnqcqm.html

TS:   // 同 JS
来源：http://dali.ivvv.top/Article/details/gtxachyoay.html

Java: new Thread(() -> f()).start()
来源：http://dali.jlsjyb.cn/Article/details/gtuwcxepgb.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gtbsaolrsb.html

Ruby: Thread.new { f }
来源：http://dali.chenlongwang.top/Article/details/gttylgvlge.html

C#:   Task.Run(() => F());
来源：http://dali.havefunace.top/Article/details/gtbohmysrs.html

[O02] 使用线程池
来源：http://dali.gogol.net.cn/Article/details/gtflkmkipf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jiagoushi.top/Article/details/gtuwkbjkki.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hysaishi.cn/Article/details/gtgchcogow.html

JS:   // worker_threads 线程池
来源：http://dali.guannengcc.top/Article/details/gtfoeowngs.html

TS:   // worker_threads 线程池
来源：http://dali.smart0.xyz/Article/details/gtinogwvvk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hammf.cn/Article/details/gtjfxackky.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ppjwa.cn/Article/details/gtcjnjczfb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.nanxuanxn.top/Article/details/gtzbggsnqr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.sysykeji.top/Article/details/gtcpdgtekg.html

[O03] 加锁保护共享数据
来源：http://dali.shanyushiyangtech.top/Article/details/gteovfihex.html

Py:   with lock: shared += 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtywmaqcwo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ybcxt.top/Article/details/gtcwtdhjpv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinqigfzy.top/Article/details/gtiwhncprw.html

TS:   // 同 JS
来源：http://dali.yueranfly.top/Article/details/gtrsjirueu.html

Java: synchronized (this) { shared++; }
来源：http://dali.yuxming.cn/Article/details/gtaolmbksc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hywenlv.cn/Article/details/gtbrfjhaoo.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.tianlin.xyz/Article/details/gtbnuluohv.html

C#:   lock (gate) { shared++; }
来源：http://dali.bjfxy.top/Article/details/gtvylztovy.html

[O04] 定义异步函数并等待
来源：http://dali.jianghu66.top/Article/details/gtatsgaolb.html

Py:   async def f():⏎    await g()
来源：http://dali.shanyushiyangtech.top/Article/details/gtruqgvtbg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hnqzz.top/Article/details/gttukpbqiu.html

JS:   async function f() { await g(); }
来源：http://dali.hnqzz.top/Article/details/gtudwvulsg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.bjfxy.top/Article/details/gtzisdvlpy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.wangshuangyany.cn/Article/details/gtajorxcfc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shangyingyoupin.top/Article/details/gtqacvjmxp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hywenlv.cn/Article/details/gtcaccmjjq.html

C#:   async Task F() { await G(); }
来源：http://dali.0kj1m.cn/Article/details/gtwaufwxlq.html

[O05] 并发执行并等待全部完成
来源：http://dali.ybcxt.top/Article/details/gtpmllozei.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xuetiantiany.cn/Article/details/gtxajnfble.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.daria6918.cn/Article/details/gthesehiad.html

JS:   await Promise.all(tasks)
来源：http://dali.cqqwz.cn/Article/details/gthpzsvsxv.html

TS:   await Promise.all(tasks)
来源：http://dali.hongshengwenyu.top/Article/details/gtjrilqfjl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.fengsongda.top/Article/details/gtakvoqwjg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.bjfxy.top/Article/details/gtrasmbbdr.html

Ruby: threads.map(&:join)
来源：http://dali.jqgfzy.top/Article/details/gtmpggjxgu.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.redwolf501.top/Article/details/gtohsmmvsx.html

[O06] 使用进程池
来源：http://dali.sufxvd.cn/Article/details/gtjtevkigr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jlsjyb.cn/Article/details/gtpufxwwcd.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gteppukdzn.html

JS:   // child_process / cluster 模块
来源：http://dali.dashuyun.cn/Article/details/gtvztqakik.html

TS:   // child_process / cluster 模块
来源：http://dali.sysykeji.top/Article/details/gtygtlsokk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xinyue.icu/Article/details/gtxevwkhsi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.bjfxy.top/Article/details/gtfiqclrrb.html

Ruby: // fork 块
来源：http://dali.316326.xyz/Article/details/gttyekzdjr.html

C#:   Parallel.For
来源：http://dali.aibaodan.cn/Article/details/gtzmxpuefw.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtfklinxzv.html

P. 常用工具函数
来源：http://dali.jinqigfzy.top/Article/details/gtvlfhopgf.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtmyhhcdub.html

[P01] 生成 UUID
来源：http://dali.jinqigfzy.top/Article/details/gtrzrifydd.html

Py:   str(uuid.uuid4())
来源：http://dali.havefunace.top/Article/details/gtddgcrnaz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.aibaodan.cn/Article/details/gtkykbthnk.html

JS:   crypto.randomUUID()
来源：http://dali.aizwys.cn/Article/details/gtxzuxyxxg.html

TS:   crypto.randomUUID()
来源：http://dali.hnqzz.top/Article/details/gtwckycawz.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpadtswss.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shanyushiyangtech.top/Article/details/gtfvfrazfa.html

Ruby: SecureRandom.uuid
来源：http://dali.xziqi.cn/Article/details/gtpmrbqnvj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.pengpengdd.cyou/Article/details/gtozjhzbya.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjphugeus.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xuetiantiany.cn/Article/details/gtnxgbehds.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hysaishi.cn/Article/details/gtezccssis.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shuidangran.top/Article/details/gtlynbgdjj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gtvdgaxchl.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.smart0.xyz/Article/details/gtyucwibvw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gaohongyu789.top/Article/details/gtnkdpmdug.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xylfe.cn/Article/details/gtvrfdgtbn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cucudq.cn/Article/details/gtocgndxqp.html

[P03] 生成短随机字符串
来源：http://dali.haohaochexian.top/Article/details/gtvwmcmvzd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yj20258.top/Article/details/gtnqsipldz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shzxlz.cn/Article/details/gtyangqamv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj202588.top/Article/details/gtevktnjij.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.vqdsnc.cn/Article/details/gtnhptgjvt.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.dianchejie.cn/Article/details/gtjxulppoq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hysaishi.cn/Article/details/gtbnimrfhl.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.wangdashe.top/Article/details/gtzosqyouj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.iojbl.cn/Article/details/gtgejmsuca.html

[P04] 求长度
来源：http://dali.xziqi.cn/Article/details/gtfsevtbgp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinqigufen.top/Article/details/gtxuruvlwz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pycfn.com/Article/details/gtusngbtzx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangtech.top/Article/details/gttjorwqib.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gogol.net.cn/Article/details/gtysawsfpr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.gzhubu.top/Article/details/gtzbtceqxb.html

Go:   len(arr);  len(m)
来源：http://dali.316326.xyz/Article/details/gtpsoirhmj.html

Ruby: x.length;  x.size
来源：http://dali.vqdsnc.cn/Article/details/gtryvxtzcj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.feifeiyinyue.top/Article/details/gtesprxunb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jqgfzy.top/Article/details/gtuzzgcroa.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sysykeji.top/Article/details/gtamqucugb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yonumen.top/Article/details/gtojskqxin.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zycfv.cn/Article/details/gtfuohwwdm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yuxming.cn/Article/details/gtbehtlxyl.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hfpthk.cn/Article/details/gtouqaecnj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yangfankeji.com/Article/details/gtgbinnctj.html

Ruby: a == b
来源：http://dali.svipenyu.cn/Article/details/gtezwqhrpy.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yongpay.top/Article/details/gtyvfqnlfj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.aibaodan.cn/Article/details/gtoujtaesp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ydzc1.top/Article/details/gtjqattbbx.html

PHP:  if (empty($x)) {}
来源：http://dali.gotoacloud.top/Article/details/gtipzigrjz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xziqi.cn/Article/details/gtzvkccewm.html

TS:   if (x == null) {}
来源：http://dali.iojbl.cn/Article/details/gtzqupbpfh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.tianlin.xyz/Article/details/gtjyhuqepn.html

Go:   if x == nil {}
来源：http://dali.jinqigfzy.top/Article/details/gteyrnjirf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwlqspfip.html

C#:   if (x is null) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtaqkfgdty.html

[P07] 防抖与节流
来源：http://dali.xuanzx.com/Article/details/gtlxruowbj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.guowangkeji.top/Article/details/gtjcdvpqcd.html

PHP:  // 手写时间戳比较
来源：http://dali.ydzc1.top/Article/details/gthhgxbdqy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jlsjyb.cn/Article/details/gtzsotzarw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sxryk.cn/Article/details/gtwweogric.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinqigufen.top/Article/details/gtvvxrmkux.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hnxiangtu.top/Article/details/gtsceuqamc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpwwqwzwd.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.smart0.xyz/Article/details/gtrdnfzirh.html

[P08] 处理浮点精度问题
来源：http://dali.sufxvd.cn/Article/details/gtrosnptfq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hongshengwenyu.top/Article/details/gttqhgivax.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.redwolf501.top/Article/details/gtlaccmwaa.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.kuanghao11.cn/Article/details/gtqmvlgbrc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jqgfzy.top/Article/details/gtwzdfvnll.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.dianchejie.cn/Article/details/gtaeykcfha.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.iojbl.cn/Article/details/gtvtkenwfr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.wangdashe.top/Article/details/gtqjnjctzd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shzxlz.cn/Article/details/gtvngpwevg.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtshmepsru.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.aibaodan.cn/Article/details/gtyxbapxfd.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtzlwyilct.html

[Q01] 创建表
来源：http://dali.zdqjudy.top/Article/details/gtiqcuzscf.html

CREATE TABLE users (
来源：http://dali.gaohongyu789.top/Article/details/gtypstbgfv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinghuilouyu.cn/Article/details/gtqcmomolk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.chenzaomai.com/Article/details/gtkfabrlbv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jqgfzy.top/Article/details/gtfgdieoja.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.chenjidiqi.icu/Article/details/gtazsmqyqo.html

);
来源：http://dali.jqgfzy.top/Article/details/gteloakzsq.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gtpykwfwja.html

CREATE TABLE orders (
来源：http://dali.tian-w.cn/Article/details/gtltnyptwc.html


<!-- 参考信息 -->