代发 wailian999

TS:   process.cwd()
来源：http://dali.vqdsnc.cn/Article/details/gt2zbxuodbt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.quarkkingdee.top/Article/details/gt2yufkimxm.html

Go:   os.Getwd()
来源：http://dali.svipenyu.cn/Article/details/gt2vjslwbyr.html

Ruby: Dir.pwd
来源：http://dali.chenjidiqi.icu/Article/details/gt2wjxoyvmk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.guowangkeji.top/Article/details/gt2fkifdvfj.html

[M05] 设置退出码
来源：http://dali.zhiwuduotai.top/Article/details/gt2txexbyha.html

Py:   sys.exit(1)
来源：http://dali.jianghu66.top/Article/details/gt2pqkywabf.html

PHP:  exit(1);
来源：http://dali.tanke756.top/Article/details/gt2xmcysxgq.html

JS:   process.exit(1)
来源：http://dali.fengsongda.top/Article/details/gt2gjecbvtz.html

TS:   process.exit(1)
来源：http://dali.yj20258.top/Article/details/gt2lfjwvine.html

Java: System.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gt2wdyjlccr.html

Go:   os.Exit(1)
来源：http://dali.sysykeji.top/Article/details/gt2ytsqecsv.html

Ruby: exit 1
来源：http://dali.guannengcc.top/Article/details/gt2ojbealct.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hfpthk.cn/Article/details/gt2uuxdrunm.html

[M06] 向标准错误输出
来源：http://dali.cqqwz.cn/Article/details/gt2ieqmawfv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.havefunace.top/Article/details/gt2wuonrqxz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.quarkkingdee.top/Article/details/gt2kvlafkic.html

JS:   console.error("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lwoiizpk.html

TS:   console.error("err")
来源：http://dali.yj20258.top/Article/details/gt2fbbmjact.html

Java: System.err.println("err")
来源：http://dali.sxryk.cn/Article/details/gt2bkattgvp.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gotoacloud.top/Article/details/gt2sxzjlebh.html

Ruby: warn "err"
来源：http://dali.jyoumei.cn/Article/details/gt2wrvhaslr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.chenjidiqi.icu/Article/details/gt2nlaobbqp.html

[M07] 判断是否为主入口
来源：http://dali.birdmap.top/Article/details/gt2wvxxmreg.html

Py:   if __name__ == "__main__":
来源：http://dali.kuanghao11.cn/Article/details/gt2aqcgafbi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jianghu66.top/Article/details/gt2hsjsckif.html

JS:   require.main === module
来源：http://dali.snrcjt.cn/Article/details/gt2ondtvzmj.html

TS:   require.main === module
来源：http://dali.yuanzhike.top/Article/details/gt2bugkqsub.html

Java: public static void main(String[] args)
来源：http://dali.iojbl.cn/Article/details/gt2lmnlwdqv.html

Go:   func main()
来源：http://dali.bjfxy.top/Article/details/gt2ysntegqx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.9152youxi.cn/Article/details/gt2dewxfltk.html

C#:   static void Main(string[] args)
来源：http://dali.zhoulong.xyz/Article/details/gt2yohublxx.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2uqkenvxi.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jiagoushi.top/Article/details/gt2eswcqxwh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.svipenyu.cn/Article/details/gt2bnhpdnmn.html

JS:   process.platform;  process.version
来源：http://dali.kuanghao11.cn/Article/details/gt2ersfqpkt.html

TS:   process.platform;  process.version
来源：http://dali.yanxiufei.cn/Article/details/gt2ldqtdqjc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.chenjidiqi.icu/Article/details/gt2lxeocagb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rllivcsr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xziqi.cn/Article/details/gt2zbiiqwzr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.redwolf501.top/Article/details/gt2uwindwgj.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2yhavbrqh.html

N. 数据结构与算法
来源：http://dali.gzhubu.top/Article/details/gt2twqmzrds.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2ioexnwgq.html

[N01] 二分查找（有序数组）
来源：http://dali.jqgfzy.top/Article/details/gt2eucdpcie.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.smart0.xyz/Article/details/gt2apozhbnu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jlsjyb.cn/Article/details/gt2bbbdfzls.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jiagoushi.top/Article/details/gt2yzbljweg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sysykeji.top/Article/details/gt2cbqcntyr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gt2lyygywcq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ybcxt.top/Article/details/gt2fpmwdygo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.wangshuangyany.cn/Article/details/gt2iliyrflq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yueranfly.top/Article/details/gt2nypawoqr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.wangshuangyany.cn/Article/details/gt2sllfqyuz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lmfwsqnm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gt2mdpdugix.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yongpay.top/Article/details/gt2tqsmkmlk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pycfn.com/Article/details/gt2eyaaihnd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yvedp.cn/Article/details/gt2gkibuhfn.html

Go:   slices.Sort(arr)
来源：http://dali.sysykeji.top/Article/details/gt2wbvtnqwn.html

Ruby: arr.sort
来源：http://dali.fzhhl.top/Article/details/gt2mdjcotad.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jiagoushi.top/Article/details/gt2qwleylbe.html

[N03] 快速排序（分治示例）
来源：http://dali.fengsongda.top/Article/details/gt2xfkrwtiz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.aibaodan.cn/Article/details/gt2tlucyhyq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2huuncxlr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenjidiqi.icu/Article/details/gt2bimyxujp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.snrcjt.cn/Article/details/gt2bdnqezjm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.fzhhl.top/Article/details/gt2ldieuqzi.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rrujfhzu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ehwqpu.com/Article/details/gt2ezalnzcl.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.wangshuangyany.cn/Article/details/gt2kwqiiapr.html

[N04] 斐波那契数列
来源：http://dali.zdqjudy.top/Article/details/gt2pdtjmkqy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhengqikj.top/Article/details/gt2xdmbmmdy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.guannengcc.top/Article/details/gt2ruxiijfl.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangdashe.top/Article/details/gt2bbgcoems.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuanzhike.top/Article/details/gt2gksmzhtx.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.9152youxi.cn/Article/details/gt2ispclnvk.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhongyouzk.top/Article/details/gt2rejmfcuc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hnxiangtu.top/Article/details/gt2xkgkdkzw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gt2rcibznnq.html

[N05] 最大公约数
来源：http://dali.dianchejie.cn/Article/details/gt2euvorkzm.html

Py:   math.gcd(a, b)
来源：http://dali.dianchejie.cn/Article/details/gt2kknkjnyg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jianghu66.top/Article/details/gt2gbyqnesm.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zycfv.cn/Article/details/gt2dakdmjbq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.0kj1m.cn/Article/details/gt2unowxmpg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xinyue.icu/Article/details/gt2buaglzrc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hnxiangtu.top/Article/details/gt2qfuyapqn.html

Ruby: a.gcd(b)
来源：http://dali.jiagoushi.top/Article/details/gt2ittmyigi.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lteghzgg.html

[N06] 判断回文字符串
来源：http://dali.zycfv.cn/Article/details/gt2pzifmpyd.html

Py:   s == s[::-1]
来源：http://dali.hywenlv.cn/Article/details/gt2lsoidqia.html

PHP:  $s === strrev($s);
来源：http://dali.zhoulong.xyz/Article/details/gt2ctopkmyd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hongshengwenyu.top/Article/details/gt2dtgxdela.html

TS:   s === [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gt2dspvlsxi.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhiwuduotai.top/Article/details/gt2qaupxsgl.html

Go:   // 双指针从两端比较
来源：http://dali.meibo888.top/Article/details/gt2wntqjfpv.html

Ruby: s == s.reverse
来源：http://dali.fengsongda.top/Article/details/gt2lyqngwph.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yueranfly.top/Article/details/gt2cvxlcudm.html

[N07] 两数之和（返回下标）
来源：http://dali.quarkkingdee.top/Article/details/gt2gwlkxfou.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yueranfly.top/Article/details/gt2smiamvuo.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ehwqpu.com/Article/details/gt2guidlppi.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gzhubu.top/Article/details/gt2qrzbpelq.html

TS:   // 手写 Map<string, number>
来源：http://dali.meibo888.top/Article/details/gt2evstethw.html

Java: // 手写 HashMap
来源：http://dali.snrcjt.cn/Article/details/gt2iwznaodq.html

Go:   // 手写 map[int]int
来源：http://dali.tian-w.cn/Article/details/gt2itwkvqeq.html

Ruby: // 手写 Hash
来源：http://dali.316326.xyz/Article/details/gt2xwbebxxg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shuidangran.top/Article/details/gt2dybjsrgr.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2udzvwgot.html

Py:   itertools.permutations(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2exskgmcd.html

PHP:  // 手写递归交换
来源：http://dali.zhongyouzk.top/Article/details/gt2bpvwvjff.html

JS:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gt2wbsatxvt.html

TS:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gt2jpnjxswk.html

Java: // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kabgrvme.html

Go:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gt2xtnwifxp.html

Ruby: arr.permutation.to_a
来源：http://dali.iojbl.cn/Article/details/gt2mjtkpird.html

C#:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gt2yupcoxvb.html

[N09] 栈与队列
来源：http://dali.nanxuanxn.top/Article/details/gt2ieyxnahk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ppjwa.cn/Article/details/gt2fnekwmov.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.tianlin.xyz/Article/details/gt2gbrtyghc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.wangdashe.top/Article/details/gt2ebqwtfmn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.9152youxi.cn/Article/details/gt2fsnmwnjb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.smart0.xyz/Article/details/gt2iamklign.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ydzc1.top/Article/details/gt2sxnruknv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.wangdashe.top/Article/details/gt2ozsfdfob.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhiwuduotai.top/Article/details/gt2yuousjmr.html

[N10] 链表节点定义
来源：http://dali.c1oappe.top/Article/details/gt2ycackgkl.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.nanxuanxn.top/Article/details/gt2snbvracr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jiagoushi.top/Article/details/gt2axyglppm.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.fengsongda.top/Article/details/gt2rbnxifab.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.aizwys.cn/Article/details/gt2hqduxbhi.html

Java: class Node { int v; Node next; }
来源：http://dali.hywenlv.cn/Article/details/gt2wjsexwoz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yj20258888.top/Article/details/gt2zvolydlm.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.nwbrower.top/Article/details/gt2nzywulha.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jianghu66.top/Article/details/gt2zcihreef.html

[N11] 二叉树中序遍历
来源：http://dali.dianchejie.cn/Article/details/gt2vrdayukq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.chenzaomai.com/Article/details/gt2ukjlpllc.html

PHP:  // 手写递归函数
来源：http://dali.cucudq.cn/Article/details/gt2hezbmaef.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shzxlz.cn/Article/details/gt2velzxywq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yanxiufei.cn/Article/details/gt2sfcssfji.html

Java: // 手写递归
来源：http://dali.zhengqikj.top/Article/details/gt2nkqkkyyn.html

Go:   // 手写递归
来源：http://dali.316326.xyz/Article/details/gt2jbiucuxv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yjhudjzm.html

C#:   // 手写递归
来源：http://dali.jinqigfzy.top/Article/details/gt2xwvafzlk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jyoumei.cn/Article/details/gt2sncnuovh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.birdmap.top/Article/details/gt2stnuhaxi.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.aibaodan.cn/Article/details/gt2bbafwpwk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhiwuduotai.top/Article/details/gt2fveshbud.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhoulong.xyz/Article/details/gt2gvzibbgo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daria6918.cn/Article/details/gt2mpxcahok.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.snrcjt.cn/Article/details/gt2goqaiprs.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jlsjyb.cn/Article/details/gt2uohvaatc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2slisxndw.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tjekzyab.html

O. 并发与异步
来源：http://dali.yonumen.top/Article/details/gt2npckyxke.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2hxboxlao.html

[O01] 启动一个线程
来源：http://dali.yj20258.top/Article/details/gt2slltovcu.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.daxiang520.top/Article/details/gt2ehgmcggi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.andypj.xyz/Article/details/gt2zxcuqadg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2apgddhqp.html

TS:   // 同 JS
来源：http://dali.smart0.xyz/Article/details/gt2zjyejxeb.html

Java: new Thread(() -> f()).start()
来源：http://dali.nwbrower.top/Article/details/gt2xjcmeiwa.html

Go:   go f()
来源：http://dali.shuidangran.top/Article/details/gt2lkjxhvqh.html

Ruby: Thread.new { f }
来源：http://dali.nanxuanxn.top/Article/details/gt2rjxepqwp.html

C#:   Task.Run(() => F());
来源：http://dali.ppjwa.cn/Article/details/gt2zdxqblfj.html

[O02] 使用线程池
来源：http://dali.c1oappe.top/Article/details/gt2kowlntnu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ehwqpu.com/Article/details/gt2fkmykquj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shuidangran.top/Article/details/gt2rhcggkpv.html

JS:   // worker_threads 线程池
来源：http://dali.svipenyu.cn/Article/details/gt2iqrzpbva.html

TS:   // worker_threads 线程池
来源：http://dali.0kj1m.cn/Article/details/gt2blpgpigq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.316326.xyz/Article/details/gt2nhgxdvju.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gogol.net.cn/Article/details/gt2exwreeil.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hnqzz.top/Article/details/gt2xlsoaiaz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.meibo888.top/Article/details/gt2ekqgmoyo.html

[O03] 加锁保护共享数据
来源：http://dali.yuxming.cn/Article/details/gt2vadfscjm.html

Py:   with lock: shared += 1
来源：http://dali.meibo888.top/Article/details/gt2dbucwdku.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.chenjidiqi.icu/Article/details/gt2iqvhcfha.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yanxiufei.cn/Article/details/gt2rwxredmw.html

TS:   // 同 JS
来源：http://dali.shangyingyoupin.top/Article/details/gt2oltkmryi.html

Java: synchronized (this) { shared++; }
来源：http://dali.yanxiufei.cn/Article/details/gt2rrmppbkc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.9152youxi.cn/Article/details/gt2qvsjnzsp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cashguo.top/Article/details/gt2bwvdyjsy.html

C#:   lock (gate) { shared++; }
来源：http://dali.chenlongwang.top/Article/details/gt2aqlepqul.html

[O04] 定义异步函数并等待
来源：http://dali.cqqwz.cn/Article/details/gt2fzjlcsqg.html

Py:   async def f():⏎    await g()
来源：http://dali.havefunace.top/Article/details/gt2jpyvbtjp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gogol.net.cn/Article/details/gt2jffyhpgp.html

JS:   async function f() { await g(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2yshysvhm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shuidangran.top/Article/details/gt2poyfbezb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.andypj.xyz/Article/details/gt2zlfxvbrc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.wangshuangyany.cn/Article/details/gt2wdhtuvke.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.haohaochexian.top/Article/details/gt2izockcer.html

C#:   async Task F() { await G(); }
来源：http://dali.yvedp.cn/Article/details/gt2hesosopx.html

[O05] 并发执行并等待全部完成
来源：http://dali.ppjwa.cn/Article/details/gt2ameikvcs.html

Py:   asyncio.gather(*tasks)
来源：http://dali.fzhhl.top/Article/details/gt2bhqaaiet.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.meibo888.top/Article/details/gt2morqgmui.html

JS:   await Promise.all(tasks)
来源：http://dali.guowangkeji.top/Article/details/gt2sxwcdzga.html

TS:   await Promise.all(tasks)
来源：http://dali.zhoulong.xyz/Article/details/gt2zoicvzdu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinqigufen.top/Article/details/gt2huggxjlb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cqqwz.cn/Article/details/gt2twuikxsi.html

Ruby: threads.map(&:join)
来源：http://dali.dashuyun.cn/Article/details/gt2dfmidddp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yonumen.top/Article/details/gt2byrpwwqv.html

[O06] 使用进程池
来源：http://dali.andypj.xyz/Article/details/gt2cwplxiio.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.nanxinkj.top/Article/details/gt2jmhzgmcm.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cheryme.top/Article/details/gt2ypljbodx.html

JS:   // child_process / cluster 模块
来源：http://dali.havefunace.top/Article/details/gt2cxvsvqls.html

TS:   // child_process / cluster 模块
来源：http://dali.mhx1999.top/Article/details/gt2rnhqztow.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ybcxt.top/Article/details/gt2ovbwefyb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wozonnta.html

Ruby: // fork 块
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jzsbigvk.html

C#:   Parallel.For
来源：http://dali.wangshuangyany.cn/Article/details/gt2tufqiktw.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2sinqsxlw.html

P. 常用工具函数
来源：http://dali.andypj.xyz/Article/details/gt2ncjcqllr.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2lngfzbey.html

[P01] 生成 UUID
来源：http://dali.xziqi.cn/Article/details/gt2lbctfgoz.html

Py:   str(uuid.uuid4())
来源：http://dali.wangdashe.top/Article/details/gt2btjrehtr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xylfe.cn/Article/details/gt2gjmsyogs.html

JS:   crypto.randomUUID()
来源：http://dali.shzxlz.cn/Article/details/gt2xsyqxrbi.html

TS:   crypto.randomUUID()
来源：http://dali.zhoulong.xyz/Article/details/gt2wsyvuqed.html

Java: UUID.randomUUID().toString()
来源：http://dali.gotoacloud.top/Article/details/gt2azfyljos.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jinqigfzy.top/Article/details/gt2vkbltrzq.html

Ruby: SecureRandom.uuid
来源：http://dali.9152youxi.cn/Article/details/gt2wpmudlrj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jyoumei.cn/Article/details/gt2rtrhqhgu.html

[P02] MD5 / SHA256 摘要
来源：http://dali.nanxinkj.top/Article/details/gt2yqyqcqvm.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.daxiang520.top/Article/details/gt2nmnjhqrg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.fzhhl.top/Article/details/gt2ntptkuzl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yj20258.top/Article/details/gt2gxqovsiu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jianghu66.top/Article/details/gt2lvyicskw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.pengpengdd.cyou/Article/details/gt2glpbloep.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.tian-w.cn/Article/details/gt2kxzxwtte.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cucudq.cn/Article/details/gt2dbeaihna.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.vqdsnc.cn/Article/details/gt2swqwhvsd.html

[P03] 生成短随机字符串
来源：http://dali.ehwqpu.com/Article/details/gt2ziuyamrx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jinqigufen.top/Article/details/gt2cgwjemmj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.wangdashe.top/Article/details/gt2nwcllkqp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hywenlv.cn/Article/details/gt2bzibcahn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hnxiangtu.top/Article/details/gt2lotzharc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.snrcjt.cn/Article/details/gt2pnlidmuv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.andypj.xyz/Article/details/gt2nopsgyjm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ybcxt.top/Article/details/gt2jtyvcfxs.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shangyingyoupin.top/Article/details/gt2mufdmsro.html

[P04] 求长度
来源：http://dali.yueranfly.top/Article/details/gt2vbmwiluk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tian-w.cn/Article/details/gt2qxagxrao.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gt2kbpwgkeq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cqqwz.cn/Article/details/gt2kdwmipbe.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yongpay.top/Article/details/gt2maehafto.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hfpthk.cn/Article/details/gt2hxxpoxuv.html

Go:   len(arr);  len(m)
来源：http://dali.aibaodan.cn/Article/details/gt2shnuurqx.html

Ruby: x.length;  x.size
来源：http://dali.cqqwz.cn/Article/details/gt2bmvvihpr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.havefunace.top/Article/details/gt2pgphkhfh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zycfv.cn/Article/details/gt2wirtgrzg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.bjfxy.top/Article/details/gt2plixxfhk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.svipenyu.cn/Article/details/gt2osupakzm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yongpay.top/Article/details/gt2iytrgecs.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shzxlz.cn/Article/details/gt2sgxgexwb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jinqigufen.top/Article/details/gt2epjbmrpz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jianghu66.top/Article/details/gt2fjkeuzcm.html

Ruby: a == b
来源：http://dali.316326.xyz/Article/details/gt2paiuvdnf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dypknncj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gaohongyu789.top/Article/details/gt2sryiumom.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ybcxt.top/Article/details/gt2cyowqypn.html

PHP:  if (empty($x)) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2npeiiswu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yuxming.cn/Article/details/gt2sghjgpyc.html

TS:   if (x == null) {}
来源：http://dali.ppjwa.cn/Article/details/gt2tlevuraw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.316326.xyz/Article/details/gt2thrmocio.html

Go:   if x == nil {}
来源：http://dali.ivvv.top/Article/details/gt2tcvauddq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cheryme.top/Article/details/gt2exfcfhxq.html

C#:   if (x is null) {}
来源：http://dali.jianghu66.top/Article/details/gt2uugmtwkb.html

[P07] 防抖与节流
来源：http://dali.birdmap.top/Article/details/gt2ddzxmpng.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.aizwys.cn/Article/details/gt2rulevvvn.html

PHP:  // 手写时间戳比较
来源：http://dali.andypj.xyz/Article/details/gt2wxkyhftf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hywenlv.cn/Article/details/gt2cxgaeeeo.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aizwys.cn/Article/details/gt2clgyguom.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.haohaochexian.top/Article/details/gt2fmpznump.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zndnhkxr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.snrcjt.cn/Article/details/gt2zabzzmcx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.feifeiyinyue.top/Article/details/gt2qofdndpd.html

[P08] 处理浮点精度问题
来源：http://dali.guannengcc.top/Article/details/gt2zqltzbty.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.daria6918.cn/Article/details/gt2qyctluki.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gaohongyu789.top/Article/details/gt2cmrtizhx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jinqigfzy.top/Article/details/gt2lxtyissn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yonumen.top/Article/details/gt2bneksteh.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.iojbl.cn/Article/details/gt2ssuhlitx.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.dashuyun.cn/Article/details/gt2xnfpazrp.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hywenlv.cn/Article/details/gt2ngogsqhk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.pengpengdd.cyou/Article/details/gt2rvodxaxy.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2uazvfepu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.guannengcc.top/Article/details/gt2srsqljek.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2grbamfjv.html

[Q01] 创建表
来源：http://dali.yanxiufei.cn/Article/details/gt2pnnyfdsr.html

CREATE TABLE users (
来源：http://dali.jqgfzy.top/Article/details/gt2sekywuha.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shanyushiyangtech.top/Article/details/gt2daoarsru.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yvedp.cn/Article/details/gt2wqijopnl.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zdqjudy.top/Article/details/gt2yjeofyrd.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.birdmap.top/Article/details/gt2jbyhnbza.html

);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xcctpcja.html

[Q02] 创建带外键的表
来源：http://dali.ivvv.top/Article/details/gt2qtgjahmg.html

CREATE TABLE orders (
来源：http://dali.ybcxt.top/Article/details/gt2smzrfvao.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aibaodan.cn/Article/details/gt2vejmlqzd.html

user_id INT NOT NULL,
来源：http://dali.nanxinkj.top/Article/details/gt2giaxnizv.html

amount DECIMAL(10, 2),
来源：http://dali.smart0.xyz/Article/details/gt2gjoobvpn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yangfankeji.com/Article/details/gt2poeorqrj.html


<!-- 参考信息 -->