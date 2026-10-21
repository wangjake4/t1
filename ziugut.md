代发 wailian999

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ehwqpu.com/Article/details/gtdggwcied.html

Ruby: warn "err"
来源：http://dali.cashguo.top/Article/details/gtqxerpjts.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.snrcjt.cn/Article/details/gtnaxdspmi.html

[M07] 判断是否为主入口
来源：http://dali.yanxiufei.cn/Article/details/gtimfnldhk.html

Py:   if __name__ == "__main__":
来源：http://dali.jinqigfzy.top/Article/details/gtvpyynrga.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinqigufen.top/Article/details/gtfqumgooc.html

JS:   require.main === module
来源：http://dali.hysaishi.cn/Article/details/gtgcnsxoia.html

TS:   require.main === module
来源：http://dali.nanxinkj.top/Article/details/gtvkmcvukl.html

Java: public static void main(String[] args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnaxdnvzw.html

Go:   func main()
来源：http://dali.hongshengwenyu.top/Article/details/gtwvhnmbuk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sysykeji.top/Article/details/gthawfecxq.html

C#:   static void Main(string[] args)
来源：http://dali.yanxiufei.cn/Article/details/gtalvlsilj.html

[M08] 获取系统与运行时信息
来源：http://dali.zdqjudy.top/Article/details/gtwsqhufrl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ybcxt.top/Article/details/gtutmxmdeh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cheryme.top/Article/details/gtmxihxtlv.html

JS:   process.platform;  process.version
来源：http://dali.hnqzz.top/Article/details/gtoturtwmx.html

TS:   process.platform;  process.version
来源：http://dali.jyoumei.cn/Article/details/gtvqdjxzcz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.guowangkeji.top/Article/details/gtvpxkgqzl.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.chenjidiqi.icu/Article/details/gtugbshetf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ywan-chungtsiang.top/Article/details/gteihwzchv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xuetiantiany.cn/Article/details/gtrmotsmgr.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtsiqqprqf.html

N. 数据结构与算法
来源：http://dali.mhx1999.top/Article/details/gtlbwkfdea.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtdwmnniqo.html

[N01] 二分查找（有序数组）
来源：http://dali.hnqzz.top/Article/details/gtkdppbtex.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtwwittvgi.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gogol.net.cn/Article/details/gttujmmafw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhixingplan.top/Article/details/gtjabkkmhj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yongpay.top/Article/details/gtcrxaslbd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yj20258888.top/Article/details/gtbflmsmfk.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtzgeprtbr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj202588.top/Article/details/gtuuukepuu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtcdmetfvm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gzhubu.top/Article/details/gtgclrebxi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hysaishi.cn/Article/details/gtnexqlbvq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.dashuyun.cn/Article/details/gtmhklxymp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuanzhike.top/Article/details/gtpzjerzgg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.birdmap.top/Article/details/gtknlsolmo.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zycfv.cn/Article/details/gtxgfxwiaa.html

Go:   slices.Sort(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtflyueeec.html

Ruby: arr.sort
来源：http://dali.andypj.xyz/Article/details/gthlwakhsm.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yuanzhike.top/Article/details/gtsxjihune.html

[N03] 快速排序（分治示例）
来源：http://dali.gzhubu.top/Article/details/gtkbaszdvt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.mhx1999.top/Article/details/gtpqripydv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ydzc1.top/Article/details/gtqxyimlil.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhengqikj.top/Article/details/gtsuzebjuf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jiagoushi.top/Article/details/gthmvxbfck.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hfpthk.cn/Article/details/gthfwhpxvy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shzxlz.cn/Article/details/gtvtdrbhvp.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hywenlv.cn/Article/details/gtzssqijfs.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xinyue.icu/Article/details/gtbrdlngrp.html

[N04] 斐波那契数列
来源：http://dali.tanke756.top/Article/details/gtzzfxkomv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cucudq.cn/Article/details/gtmmzisyux.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.316326.xyz/Article/details/gtlyqkfoos.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.meibo888.top/Article/details/gtiyjewmze.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaoohovvn.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ehwqpu.com/Article/details/gtpkcerdck.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.316326.xyz/Article/details/gtesrjuksp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.0kj1m.cn/Article/details/gtpeufjsyq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gtgcxlrlen.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gtpsdfdtxi.html

Py:   math.gcd(a, b)
来源：http://dali.yonumen.top/Article/details/gtrcjlyrjx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hysaishi.cn/Article/details/gtjhjjrcwp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.snrcjt.cn/Article/details/gtdksegjkj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.birdmap.top/Article/details/gthcvbccka.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hnqzz.top/Article/details/gttvjqxcpo.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzuljdrat.html

Ruby: a.gcd(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpgoxmaio.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yuxming.cn/Article/details/gtekejuomq.html

[N06] 判断回文字符串
来源：http://dali.chenlongwang.top/Article/details/gtfpzttggm.html

Py:   s == s[::-1]
来源：http://dali.birdmap.top/Article/details/gtwzhyemot.html

PHP:  $s === strrev($s);
来源：http://dali.guowangkeji.top/Article/details/gtoptzrapo.html

JS:   s === [...s].reverse().join("")
来源：http://dali.iojbl.cn/Article/details/gtxvqgxusm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gtpjnxfzpg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jiagoushi.top/Article/details/gtxpzbxwkc.html

Go:   // 双指针从两端比较
来源：http://dali.yj202588.top/Article/details/gtfcfyhxrp.html

Ruby: s == s.reverse
来源：http://dali.guowangkeji.top/Article/details/gtsshkpllc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xinyue.icu/Article/details/gtcbltfxaz.html

[N07] 两数之和（返回下标）
来源：http://dali.sufxvd.cn/Article/details/gtugfjvqbq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yangfankeji.com/Article/details/gteuaivofs.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinghuilouyu.cn/Article/details/gtwfjosvvu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cdnleiting.top/Article/details/gttwwezevh.html

TS:   // 手写 Map<string, number>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjcdhzjz.html

Java: // 手写 HashMap
来源：http://dali.yangfankeji.com/Article/details/gtaprmuakb.html

Go:   // 手写 map[int]int
来源：http://dali.aibaodan.cn/Article/details/gtoifgztvs.html

Ruby: // 手写 Hash
来源：http://dali.jinqigufen.top/Article/details/gtjvqftruo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jiagoushi.top/Article/details/gtyaxlzmmh.html

[N08] 生成全排列
来源：http://dali.jinghuilouyu.cn/Article/details/gtecvjekuz.html

Py:   itertools.permutations(arr)
来源：http://dali.sweek.top/Article/details/gtojwmxuhy.html

PHP:  // 手写递归交换
来源：http://dali.ywan-chungtsiang.top/Article/details/gttnnelbst.html

JS:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gtfkofratn.html

TS:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gtryvvkqwl.html

Java: // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gtgxdgfyut.html

Go:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gthewzocpd.html

Ruby: arr.permutation.to_a
来源：http://dali.yj20258.top/Article/details/gthldtjkpv.html

C#:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtrjgoldal.html

[N09] 栈与队列
来源：http://dali.havefunace.top/Article/details/gtawbglblj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jqgfzy.top/Article/details/gtmefslnfe.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jianghu66.top/Article/details/gtiqiqzpnr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhixingplan.top/Article/details/gtlyzhlypa.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.pengpengdd.cyou/Article/details/gtozanwnkw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ehwqpu.com/Article/details/gtnhdtjqhm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.nanxuanxn.top/Article/details/gtdqucpldb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gtwrxtjvvj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.kuanghao11.cn/Article/details/gtpqpqdmbc.html

[N10] 链表节点定义
来源：http://dali.jqgfzy.top/Article/details/gtwmrzibdk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hongshengwenyu.top/Article/details/gtvwptxino.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jyoumei.cn/Article/details/gtazrswrgt.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jqgufenzy.top/Article/details/gtsevsnyfq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.daxiang520.top/Article/details/gtfsdgalqi.html

Java: class Node { int v; Node next; }
来源：http://dali.jianghu66.top/Article/details/gtmjcrawml.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hysaishi.cn/Article/details/gtbtyiowew.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzrehelpe.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hfpthk.cn/Article/details/gtemekwkif.html

[N11] 二叉树中序遍历
来源：http://dali.shzxlz.cn/Article/details/gtsurplkwm.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsfzahmpt.html

PHP:  // 手写递归函数
来源：http://dali.jyoumei.cn/Article/details/gtrylotvpq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtorukbyao.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tanke756.top/Article/details/gtocqtpslk.html

Java: // 手写递归
来源：http://dali.gogol.net.cn/Article/details/gtvhykamcc.html

Go:   // 手写递归
来源：http://dali.hnqzz.top/Article/details/gtoniotcmx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinghuilouyu.cn/Article/details/gtbzncyzyj.html

C#:   // 手写递归
来源：http://dali.nanxinkj.top/Article/details/gtnxwybghg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yj20258888.top/Article/details/gtesvouypa.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hysaishi.cn/Article/details/gtatnczjwt.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.chenlongwang.top/Article/details/gtcyywiafj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhongyouzk.top/Article/details/gtqffcygwd.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yonumen.top/Article/details/gtwivtvxaa.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sweek.top/Article/details/gtugozekry.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.316326.xyz/Article/details/gtnxzzkajo.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.daria6918.cn/Article/details/gtgxkgjzdv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigufen.top/Article/details/gtwgzmdhee.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtyiautads.html

O. 并发与异步
来源：http://dali.redwolf501.top/Article/details/gtsohsvkvq.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtjxjbwglk.html

[O01] 启动一个线程
来源：http://dali.yongpay.top/Article/details/gtknikokdp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhiwuduotai.top/Article/details/gtvfxvmfhp.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shangyingyoupin.top/Article/details/gtbxrgxfga.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.0kj1m.cn/Article/details/gtzteosglf.html

TS:   // 同 JS
来源：http://dali.hfpthk.cn/Article/details/gtqihkfpwt.html

Java: new Thread(() -> f()).start()
来源：http://dali.zycfv.cn/Article/details/gtzununnpi.html

Go:   go f()
来源：http://dali.wangshuangyany.cn/Article/details/gtpbijaove.html

Ruby: Thread.new { f }
来源：http://dali.gzhubu.top/Article/details/gtzipddqte.html

C#:   Task.Run(() => F());
来源：http://dali.zdqjudy.top/Article/details/gtagnojhdz.html

[O02] 使用线程池
来源：http://dali.chenlongwang.top/Article/details/gttswmwveq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yongpay.top/Article/details/gtdgwbwpgu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hnqzz.top/Article/details/gtzyewzkhw.html

JS:   // worker_threads 线程池
来源：http://dali.xuanzx.com/Article/details/gtjluszkzw.html

TS:   // worker_threads 线程池
来源：http://dali.dianchejie.cn/Article/details/gtmpnypesv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.iojbl.cn/Article/details/gtahtdbaes.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shangyingyoupin.top/Article/details/gtqaxatcmy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hfpthk.cn/Article/details/gtizsxuflt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.daxiang520.top/Article/details/gtlyojundv.html

[O03] 加锁保护共享数据
来源：http://dali.wangdashe.top/Article/details/gtogdvtztm.html

Py:   with lock: shared += 1
来源：http://dali.zhongyouzk.top/Article/details/gtthqvdmbj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.9152youxi.cn/Article/details/gtvadhetwb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhixingplan.top/Article/details/gtozsbayhi.html

TS:   // 同 JS
来源：http://dali.shangyingyoupin.top/Article/details/gtcxmkvfsz.html

Java: synchronized (this) { shared++; }
来源：http://dali.c1oappe.top/Article/details/gtpxktqphw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jinghuilouyu.cn/Article/details/gtgtctkrgn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.vqdsnc.cn/Article/details/gtxvpdkret.html

C#:   lock (gate) { shared++; }
来源：http://dali.yueranfly.top/Article/details/gtprjefbne.html

[O04] 定义异步函数并等待
来源：http://dali.dashuyun.cn/Article/details/gtufvrqxzc.html

Py:   async def f():⏎    await g()
来源：http://dali.daxiang520.top/Article/details/gtpsngbnsn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.316326.xyz/Article/details/gtnqpnhajc.html

JS:   async function f() { await g(); }
来源：http://dali.jianghu66.top/Article/details/gtmwgtikgj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xziqi.cn/Article/details/gtkcxlvwtl.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ehwqpu.com/Article/details/gtncwzatcg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yuxming.cn/Article/details/gtqgaqxrdq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.0kj1m.cn/Article/details/gtjhegldgz.html

C#:   async Task F() { await G(); }
来源：http://dali.dashuyun.cn/Article/details/gtmimaskgo.html

[O05] 并发执行并等待全部完成
来源：http://dali.aibaodan.cn/Article/details/gtmqwskpls.html

Py:   asyncio.gather(*tasks)
来源：http://dali.pycfn.com/Article/details/gtblrwxtaj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ybcxt.top/Article/details/gtleahqwku.html

JS:   await Promise.all(tasks)
来源：http://dali.cheryme.top/Article/details/gtjkxwgfbw.html

TS:   await Promise.all(tasks)
来源：http://dali.c1oappe.top/Article/details/gtoqxzulmh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlktvpiaf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.vqdsnc.cn/Article/details/gtngzlghek.html

Ruby: threads.map(&:join)
来源：http://dali.sysykeji.top/Article/details/gtbkvthpay.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zdqjudy.top/Article/details/gthcdpfcvk.html

[O06] 使用进程池
来源：http://dali.guowangkeji.top/Article/details/gtqpeeumzh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jlsjyb.cn/Article/details/gtgcyghyfe.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnypoeyoe.html

JS:   // child_process / cluster 模块
来源：http://dali.gogol.net.cn/Article/details/gtrbfqsqne.html

TS:   // child_process / cluster 模块
来源：http://dali.bjfxy.top/Article/details/gthpitkkoa.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.vqdsnc.cn/Article/details/gtenpjxrml.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.mhx1999.top/Article/details/gtjkizwskg.html

Ruby: // fork 块
来源：http://dali.aibaodan.cn/Article/details/gtytqofrow.html

C#:   Parallel.For
来源：http://dali.pycfn.com/Article/details/gtyjmiyqnc.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtdizpfutp.html

P. 常用工具函数
来源：http://dali.zhiwuduotai.top/Article/details/gttuhuyggn.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtbqnkycsc.html

[P01] 生成 UUID
来源：http://dali.jinqigufen.top/Article/details/gtqftqaloz.html

Py:   str(uuid.uuid4())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqtfyyxif.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yongpay.top/Article/details/gttqspkhfm.html

JS:   crypto.randomUUID()
来源：http://dali.fzhhl.top/Article/details/gtjffjagzz.html

TS:   crypto.randomUUID()
来源：http://dali.andypj.xyz/Article/details/gtmqggfabq.html

Java: UUID.randomUUID().toString()
来源：http://dali.yj20258.top/Article/details/gtfxlkhouj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gzhubu.top/Article/details/gteyxzsqqt.html

Ruby: SecureRandom.uuid
来源：http://dali.shangyingyoupin.top/Article/details/gtflhgcmjo.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cqqwz.cn/Article/details/gtgmpmlhom.html

[P02] MD5 / SHA256 摘要
来源：http://dali.nwbrower.top/Article/details/gtvolxrcdn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.dianchejie.cn/Article/details/gtyrdypwzr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinqigufen.top/Article/details/gtxkqhhdkt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.fzhhl.top/Article/details/gtbfsxwptg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.quarkkingdee.top/Article/details/gtxauiodob.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.aizwys.cn/Article/details/gtjssyhmml.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyjiqftno.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.pycfn.com/Article/details/gtcealwnbn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinghuilouyu.cn/Article/details/gtmhuscspa.html

[P03] 生成短随机字符串
来源：http://dali.sweek.top/Article/details/gtgwskmype.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yj20258.top/Article/details/gthhrtoqrp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.nanxuanxn.top/Article/details/gtcrkgtzjq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daxiang520.top/Article/details/gthukbwdbb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shzxlz.cn/Article/details/gtgwldikcl.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gthlhdppqa.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.quarkkingdee.top/Article/details/gtcgguszkr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.guowangkeji.top/Article/details/gtzdmdcfep.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jlsjyb.cn/Article/details/gtwkkscqbv.html

[P04] 求长度
来源：http://dali.xylfe.cn/Article/details/gtctpgdtht.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.mhx1999.top/Article/details/gtotphwqip.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gtbjlnnszd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuxming.cn/Article/details/gttzakgwdh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.bjfxy.top/Article/details/gtgowswirg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xziqi.cn/Article/details/gtmjbldoeh.html

Go:   len(arr);  len(m)
来源：http://dali.jqgufenzy.top/Article/details/gtqsfdsmtk.html

Ruby: x.length;  x.size
来源：http://dali.jianghu66.top/Article/details/gtozzpmyyi.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shangyingyoupin.top/Article/details/gttssruuxj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.guowangkeji.top/Article/details/gtsrwiksxa.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hysaishi.cn/Article/details/gtjvigmlwg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cqqwz.cn/Article/details/gtlykgrxgl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xziqi.cn/Article/details/gtnaqutulb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ybcxt.top/Article/details/gtlfnfnlxw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ivvv.top/Article/details/gtoeswurqn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.daxiang520.top/Article/details/gtqnbqsihm.html

Ruby: a == b
来源：http://dali.ybcxt.top/Article/details/gtltyydako.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.chenlongwang.top/Article/details/gttcldrsoe.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.nwbrower.top/Article/details/gtvquxioyh.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.daxiang520.top/Article/details/gtvklwycet.html

PHP:  if (empty($x)) {}
来源：http://dali.snrcjt.cn/Article/details/gtsvqwrnbw.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.iojbl.cn/Article/details/gtgsobncuq.html

TS:   if (x == null) {}
来源：http://dali.cqqwz.cn/Article/details/gthzlkqyig.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtcxtxwnix.html

Go:   if x == nil {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqnudpxxg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yuxming.cn/Article/details/gtxofobsnr.html

C#:   if (x is null) {}
来源：http://dali.xinyue.icu/Article/details/gtesiejkxz.html

[P07] 防抖与节流
来源：http://dali.daria6918.cn/Article/details/gtohcpfcmq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.dashuyun.cn/Article/details/gtmvzfeycg.html

PHP:  // 手写时间戳比较
来源：http://dali.zdqjudy.top/Article/details/gtqjqrycra.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnqzz.top/Article/details/gtcncokfyk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfyqvnkog.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yongpay.top/Article/details/gtwnmhwicb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hywenlv.cn/Article/details/gtkfrfwazj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.daria6918.cn/Article/details/gtltdhkqba.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xziqi.cn/Article/details/gtijpsxtte.html

[P08] 处理浮点精度问题
来源：http://dali.c1oappe.top/Article/details/gtkdprtjrc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.tanke756.top/Article/details/gtfraaytfk.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ybcxt.top/Article/details/gtefpyxqkd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hnqzz.top/Article/details/gtiladhfiu.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yangfankeji.com/Article/details/gtwfdtdyjr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtswfbqkol.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cucudq.cn/Article/details/gtjggafptc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cashguo.top/Article/details/gticvmuaac.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yongpay.top/Article/details/gtdzpelvnf.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtdgjqompo.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.vqdsnc.cn/Article/details/gtpnezmdpt.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtfalmcbyu.html

[Q01] 创建表
来源：http://dali.shzxlz.cn/Article/details/gtikpdpeos.html

CREATE TABLE users (
来源：http://dali.meibo888.top/Article/details/gthafgstrp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gotoacloud.top/Article/details/gthxwfwksi.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ivvv.top/Article/details/gttcfenzyw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shangyingyoupin.top/Article/details/gtjeqyohwa.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ehwqpu.com/Article/details/gtyqlebeuj.html

);
来源：http://dali.jqgfzy.top/Article/details/gtoobksaxi.html

[Q02] 创建带外键的表
来源：http://dali.bjfxy.top/Article/details/gtshwaydnr.html

CREATE TABLE orders (
来源：http://dali.yj20258888.top/Article/details/gtvhfoqskh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hongshengwenyu.top/Article/details/gtezlxkkzs.html

user_id INT NOT NULL,
来源：http://dali.zhongyouzk.top/Article/details/gtpoffatcp.html

amount DECIMAL(10, 2),
来源：http://dali.guowangkeji.top/Article/details/gtqawfosiu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xinyue.icu/Article/details/gtvbqafusl.html

);
来源：http://dali.zhiwuduotai.top/Article/details/gtuhqfthdz.html

[Q03] 增加列
来源：http://dali.jiagoushi.top/Article/details/gtqyzxiiht.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.dashuyun.cn/Article/details/gttnacklgx.html

[Q04] 修改列类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyhhyfmig.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shanyushiyangtech.top/Article/details/gtljyeuesw.html

[Q05] 重命名列
来源：http://dali.hfpthk.cn/Article/details/gtbllckbxl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhiwuduotai.top/Article/details/gtntnchyvo.html

[Q06] 删除列
来源：http://dali.meibo888.top/Article/details/gtqftdqfoa.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttpycbmuz.html

[Q07] 删除表
来源：http://dali.mhx1999.top/Article/details/gtewewqzkj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sxryk.cn/Article/details/gteuuyatsn.html

[Q08] 创建普通索引
来源：http://dali.hfpthk.cn/Article/details/gterflhqlz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jianghu66.top/Article/details/gtfpuaagle.html

[Q09] 创建唯一索引
来源：http://dali.quarkkingdee.top/Article/details/gtduazbqmi.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrrrbtwfu.html

[Q10] 插入单行
来源：http://dali.9152youxi.cn/Article/details/gtjylxqfbb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.dianchejie.cn/Article/details/gtjhmcyiqf.html

[Q11] 一次插入多行
来源：http://dali.gotoacloud.top/Article/details/gtstmdcciy.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.andypj.xyz/Article/details/gthfycjgbi.html

[Q12] 插入后取自增 ID
来源：http://dali.tanke756.top/Article/details/gtmnzrffyg.html


<!-- 参考信息 -->