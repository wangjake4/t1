代发 wailian999

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gtpnjunnfq.html

Py:   os.getcwd()
来源：http://dali.cheryme.top/Article/details/gttffbgctw.html

PHP:  getcwd();
来源：http://dali.daxiang520.top/Article/details/gteiulrcpi.html

JS:   process.cwd()
来源：http://dali.jinqigfzy.top/Article/details/gtxypswvhg.html

TS:   process.cwd()
来源：http://dali.hammf.cn/Article/details/gtxucirmvt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jianghu66.top/Article/details/gtbbvbmycs.html

Go:   os.Getwd()
来源：http://dali.feifeiyinyue.top/Article/details/gtxgqfagxt.html

Ruby: Dir.pwd
来源：http://dali.haohaochexian.top/Article/details/gtbdxpjzxo.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nanxinkj.top/Article/details/gtewxluety.html

[M05] 设置退出码
来源：http://dali.yj20258888.top/Article/details/gtfxvivmed.html

Py:   sys.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gtexxcbxmb.html

PHP:  exit(1);
来源：http://dali.xuetiantiany.cn/Article/details/gttecfloho.html

JS:   process.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtskboyuat.html

TS:   process.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtuulfvotl.html

Java: System.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gtorovdars.html

Go:   os.Exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqkpyhhyz.html

Ruby: exit 1
来源：http://dali.fzhhl.top/Article/details/gtvztguffz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.meibo888.top/Article/details/gtgnboxifs.html

[M06] 向标准错误输出
来源：http://dali.vqdsnc.cn/Article/details/gthbbyiqkw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xylfe.cn/Article/details/gtchrmuigz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yonumen.top/Article/details/gtdwhmlijn.html

JS:   console.error("err")
来源：http://dali.dashuyun.cn/Article/details/gtzcfuexpc.html

TS:   console.error("err")
来源：http://dali.wangshuangyany.cn/Article/details/gtkqyhxnik.html

Java: System.err.println("err")
来源：http://dali.shangyingyoupin.top/Article/details/gtbeplxdyz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.guannengcc.top/Article/details/gtygauwuku.html

Ruby: warn "err"
来源：http://dali.hongshengwenyu.top/Article/details/gtqmcqanhe.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.316326.xyz/Article/details/gtwyzqxkae.html

[M07] 判断是否为主入口
来源：http://dali.redwolf501.top/Article/details/gtucsamgxl.html

Py:   if __name__ == "__main__":
来源：http://dali.jianghu66.top/Article/details/gtxinpbgzp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yvedp.cn/Article/details/gtkhmptepa.html

JS:   require.main === module
来源：http://dali.svipenyu.cn/Article/details/gtbrrmpysk.html

TS:   require.main === module
来源：http://dali.quarkkingdee.top/Article/details/gtcrseobvr.html

Java: public static void main(String[] args)
来源：http://dali.jianghu66.top/Article/details/gtdgphdmfx.html

Go:   func main()
来源：http://dali.smart0.xyz/Article/details/gtijxyrsdm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hnxiangtu.top/Article/details/gtchsecswi.html

C#:   static void Main(string[] args)
来源：http://dali.ybcxt.top/Article/details/gtvkfdixmk.html

[M08] 获取系统与运行时信息
来源：http://dali.xinyue.icu/Article/details/gtxafknygo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yvedp.cn/Article/details/gtifghfntx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jianghu66.top/Article/details/gtsubrtuut.html

JS:   process.platform;  process.version
来源：http://dali.cashguo.top/Article/details/gtufptmrvt.html

TS:   process.platform;  process.version
来源：http://dali.chenlongwang.top/Article/details/gtmfwlojiw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ybcxt.top/Article/details/gtokiryguz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gtklsxxdbn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyrseslsp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.mhx1999.top/Article/details/gtwgnmrknu.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gthqqdhlkh.html

N. 数据结构与算法
来源：http://dali.bjfxy.top/Article/details/gtyriryqbo.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtpnaeifkt.html

[N01] 二分查找（有序数组）
来源：http://dali.bjfxy.top/Article/details/gtqjuaeycx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtxaoiznvm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhixingplan.top/Article/details/gtlcuonwjd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hfpthk.cn/Article/details/gtibjnkpil.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daxiang520.top/Article/details/gttetbcczl.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtcxhipfis.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yonumen.top/Article/details/gtilwcqqjs.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.daxiang520.top/Article/details/gtysdhskqy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtmzqjpkcb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhiwuduotai.top/Article/details/gteoarecxa.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jianghu66.top/Article/details/gtbtnnuxqr.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yj20258888.top/Article/details/gtkwonfkbm.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhiwuduotai.top/Article/details/gtuprlkaav.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenzaomai.com/Article/details/gtnpmvbfsv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yueranfly.top/Article/details/gtxwlokcds.html

Go:   slices.Sort(arr)
来源：http://dali.pycfn.com/Article/details/gtyidzhgyo.html

Ruby: arr.sort
来源：http://dali.mhx1999.top/Article/details/gtcpdyjqaw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.daxiang520.top/Article/details/gtktbzqmpt.html

[N03] 快速排序（分治示例）
来源：http://dali.shangyingyoupin.top/Article/details/gtwprtlykf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinghuilouyu.cn/Article/details/gtudozwegx.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yj202588.top/Article/details/gtyblmcdhb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gogol.net.cn/Article/details/gtkkrhbhdz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gaohongyu789.top/Article/details/gtpstpvbmn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cheryme.top/Article/details/gtqjxaheyf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxkjpeuhg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tianlin.xyz/Article/details/gtijxsgoxt.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.birdmap.top/Article/details/gtqhwgysji.html

[N04] 斐波那契数列
来源：http://dali.sweek.top/Article/details/gtqwvpywgg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtgpmeyasc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cashguo.top/Article/details/gtlbgrajjo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cdnleiting.top/Article/details/gtybkfhrpu.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gtcwaqwcyu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.c1oappe.top/Article/details/gtvpapisxd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cqqwz.cn/Article/details/gtmeuvlent.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.kuanghao11.cn/Article/details/gtlgafxhlp.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.dashuyun.cn/Article/details/gtaotrdorp.html

[N05] 最大公约数
来源：http://dali.cashguo.top/Article/details/gtughpdswv.html

Py:   math.gcd(a, b)
来源：http://dali.gogol.net.cn/Article/details/gtyojnjsdp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hywenlv.cn/Article/details/gtcwyufmfz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sysykeji.top/Article/details/gtpcyfneho.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ehwqpu.com/Article/details/gtgwtaeloj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.birdmap.top/Article/details/gtqfqdjzzc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jqgufenzy.top/Article/details/gtsmejhlll.html

Ruby: a.gcd(b)
来源：http://dali.tanke756.top/Article/details/gtozzfzgvr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.wangdashe.top/Article/details/gthmaxisrl.html

[N06] 判断回文字符串
来源：http://dali.sxryk.cn/Article/details/gtwksefjfv.html

Py:   s == s[::-1]
来源：http://dali.0kj1m.cn/Article/details/gtkrogrzdg.html

PHP:  $s === strrev($s);
来源：http://dali.bjfxy.top/Article/details/gtstjmkqlc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gtmlfpasko.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gtjsppdxto.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.tianlin.xyz/Article/details/gtjavednlk.html

Go:   // 双指针从两端比较
来源：http://dali.xylfe.cn/Article/details/gtloiqwrll.html

Ruby: s == s.reverse
来源：http://dali.hywenlv.cn/Article/details/gtncqussof.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yueranfly.top/Article/details/gtgejjgcds.html

[N07] 两数之和（返回下标）
来源：http://dali.tanke756.top/Article/details/gtglwreirl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ehwqpu.com/Article/details/gtnkpblupr.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.bjfxy.top/Article/details/gtgvdtqbbx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gaohongyu789.top/Article/details/gtkqnpetpe.html

TS:   // 手写 Map<string, number>
来源：http://dali.iojbl.cn/Article/details/gtpaoouyym.html

Java: // 手写 HashMap
来源：http://dali.iojbl.cn/Article/details/gtzrdylbqs.html

Go:   // 手写 map[int]int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlwvfgkcd.html

Ruby: // 手写 Hash
来源：http://dali.xinyue.icu/Article/details/gtpubdyfay.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.mhx1999.top/Article/details/gtzymxkytw.html

[N08] 生成全排列
来源：http://dali.yongpay.top/Article/details/gtoiixvndl.html

Py:   itertools.permutations(arr)
来源：http://dali.gogol.net.cn/Article/details/gtriehkxsa.html

PHP:  // 手写递归交换
来源：http://dali.hnqzz.top/Article/details/gtngdmevsh.html

JS:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gtezgghhbx.html

TS:   // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtxwjpwyep.html

Java: // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gtgltgfjkr.html

Go:   // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gtkramxzlw.html

Ruby: arr.permutation.to_a
来源：http://dali.hongshengwenyu.top/Article/details/gttcjiyxer.html

C#:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gtsmfqxlhh.html

[N09] 栈与队列
来源：http://dali.zycfv.cn/Article/details/gtwzwsplms.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jqgfzy.top/Article/details/gtmkxjlqil.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.9152youxi.cn/Article/details/gtrookghgt.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gzhubu.top/Article/details/gtigyspuyu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shanyushiyangtech.top/Article/details/gtxdfzyfkb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.daxiang520.top/Article/details/gteiizzsyw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.c1oappe.top/Article/details/gthwegvrkw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gtxkbgkmnd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhixingplan.top/Article/details/gtwdunsqod.html

[N10] 链表节点定义
来源：http://dali.xziqi.cn/Article/details/gtscfxzrwu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.mhx1999.top/Article/details/gtfuyprfpq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.tianlin.xyz/Article/details/gtqnsbceak.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hysaishi.cn/Article/details/gtevdmmota.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yanxiufei.cn/Article/details/gtzebyfkjx.html

Java: class Node { int v; Node next; }
来源：http://dali.quarkkingdee.top/Article/details/gtvtzamcct.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yj202588.top/Article/details/gtzseqicyk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhiwuduotai.top/Article/details/gtvuxdfwrr.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gtrbzparcn.html

[N11] 二叉树中序遍历
来源：http://dali.xinyue.icu/Article/details/gtvefxsisi.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgeaxrfgt.html

PHP:  // 手写递归函数
来源：http://dali.0kj1m.cn/Article/details/gtvtffxchf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfzvqjpsg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj202588.top/Article/details/gtpdsckijl.html

Java: // 手写递归
来源：http://dali.chenzaomai.com/Article/details/gtaeqxwxyj.html

Go:   // 手写递归
来源：http://dali.zhoulong.xyz/Article/details/gtdlwvcqxf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xuanzx.com/Article/details/gtvhvpvpio.html

C#:   // 手写递归
来源：http://dali.yongpay.top/Article/details/gtquqkvnng.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.kuanghao11.cn/Article/details/gtubrfloun.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.nanxuanxn.top/Article/details/gtkaagwmns.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yangfankeji.com/Article/details/gttqfnorlb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gtwychopbn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.redwolf501.top/Article/details/gtklcistcz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigufen.top/Article/details/gtlaamoeed.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shangyingyoupin.top/Article/details/gtychhtwza.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.aibaodan.cn/Article/details/gtetroicii.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pengpengdd.cyou/Article/details/gtaichjjvd.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtuyiprwyq.html

O. 并发与异步
来源：http://dali.wangshuangyany.cn/Article/details/gtjgzaspho.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdjlpladt.html

[O01] 启动一个线程
来源：http://dali.0kj1m.cn/Article/details/gtjwtytafk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ppjwa.cn/Article/details/gtcizharsi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gotoacloud.top/Article/details/gtvxwphdij.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj20258.top/Article/details/gtxcdartvi.html

TS:   // 同 JS
来源：http://dali.gogol.net.cn/Article/details/gtgdgclzrx.html

Java: new Thread(() -> f()).start()
来源：http://dali.tanke756.top/Article/details/gtuercfvmh.html

Go:   go f()
来源：http://dali.chenjidiqi.icu/Article/details/gtooozjrmt.html

Ruby: Thread.new { f }
来源：http://dali.cucudq.cn/Article/details/gtadcuayjt.html

C#:   Task.Run(() => F());
来源：http://dali.jyoumei.cn/Article/details/gtevdlkfcw.html

[O02] 使用线程池
来源：http://dali.bjfxy.top/Article/details/gtpfwkcplg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.haohaochexian.top/Article/details/gtwtshkzxe.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zycfv.cn/Article/details/gtsvaslhzh.html

JS:   // worker_threads 线程池
来源：http://dali.jiagoushi.top/Article/details/gtgaybfuza.html

TS:   // worker_threads 线程池
来源：http://dali.cdnleiting.top/Article/details/gtucxgamhy.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yongpay.top/Article/details/gtrkwccqza.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yonumen.top/Article/details/gtqyetgvte.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xinyue.icu/Article/details/gtgtjfceiv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shangyingyoupin.top/Article/details/gtgtpmusno.html

[O03] 加锁保护共享数据
来源：http://dali.jinyuanbaomall.cn/Article/details/gtotuxbhun.html

Py:   with lock: shared += 1
来源：http://dali.smart0.xyz/Article/details/gtsvtsovxw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.wangdashe.top/Article/details/gthsspddgd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yueranfly.top/Article/details/gtiwyqubiy.html

TS:   // 同 JS
来源：http://dali.yj20258.top/Article/details/gttduzpbgz.html

Java: synchronized (this) { shared++; }
来源：http://dali.kuanghao11.cn/Article/details/gtvfzilxog.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xylfe.cn/Article/details/gtdcxutegn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yuanzhike.top/Article/details/gtjqvzwmqr.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhixingplan.top/Article/details/gtxlsngklo.html

[O04] 定义异步函数并等待
来源：http://dali.nanxuanxn.top/Article/details/gtudykhbrp.html

Py:   async def f():⏎    await g()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtksuqtgvg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shangyingyoupin.top/Article/details/gtznfyjpww.html

JS:   async function f() { await g(); }
来源：http://dali.gotoacloud.top/Article/details/gttdfcyfnr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jlsjyb.cn/Article/details/gtudwqylny.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.andypj.xyz/Article/details/gtemrctenj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.snrcjt.cn/Article/details/gtzlgcjusb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.quarkkingdee.top/Article/details/gtwysncdnd.html

C#:   async Task F() { await G(); }
来源：http://dali.hfpthk.cn/Article/details/gtxcacpumo.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinqigfzy.top/Article/details/gtcmbydhgc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.chenjidiqi.icu/Article/details/gtaumifvuy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.daxiang520.top/Article/details/gtnwaillzz.html

JS:   await Promise.all(tasks)
来源：http://dali.yueranfly.top/Article/details/gtbcuzhenb.html

TS:   await Promise.all(tasks)
来源：http://dali.pengpengdd.cyou/Article/details/gtvaazwyth.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.daxiang520.top/Article/details/gtfjnbowkr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.svipenyu.cn/Article/details/gtdengbjoo.html

Ruby: threads.map(&:join)
来源：http://dali.sufxvd.cn/Article/details/gtyagbixml.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.havefunace.top/Article/details/gtgicdtnoc.html

[O06] 使用进程池
来源：http://dali.xuetiantiany.cn/Article/details/gtlchoasks.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.havefunace.top/Article/details/gtexddlfbj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.redwolf501.top/Article/details/gtsxagbyaq.html

JS:   // child_process / cluster 模块
来源：http://dali.sweek.top/Article/details/gttddyzppu.html

TS:   // child_process / cluster 模块
来源：http://dali.sufxvd.cn/Article/details/gtcjozygip.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hnxiangtu.top/Article/details/gtlevwwooc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yanxiufei.cn/Article/details/gtkvsoveya.html

Ruby: // fork 块
来源：http://dali.gotoacloud.top/Article/details/gtrfcgxpws.html

C#:   Parallel.For
来源：http://dali.yonumen.top/Article/details/gtavmhpnvo.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtmdfgmmse.html

P. 常用工具函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvalmqzzd.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtphdomkfi.html

[P01] 生成 UUID
来源：http://dali.ehwqpu.com/Article/details/gtcfxqjvkz.html

Py:   str(uuid.uuid4())
来源：http://dali.sysykeji.top/Article/details/gtwsschkbu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhengqikj.top/Article/details/gtlypcfdzf.html

JS:   crypto.randomUUID()
来源：http://dali.zhengqikj.top/Article/details/gtpxmcocic.html

TS:   crypto.randomUUID()
来源：http://dali.sysykeji.top/Article/details/gtkzqxitbk.html

Java: UUID.randomUUID().toString()
来源：http://dali.xuanzx.com/Article/details/gtoaxdukqv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hnqzz.top/Article/details/gteqvjmsmu.html

Ruby: SecureRandom.uuid
来源：http://dali.fzhhl.top/Article/details/gtqvgdyugk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.bjfxy.top/Article/details/gtmnficgik.html

[P02] MD5 / SHA256 摘要
来源：http://dali.iojbl.cn/Article/details/gtgxxtejvj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhiwuduotai.top/Article/details/gtcqbpjrai.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sxryk.cn/Article/details/gtdnoqrnnp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gtowiofyhu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinqigufen.top/Article/details/gtzqhhwgjt.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhiwuduotai.top/Article/details/gtqjwoaerc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.nwbrower.top/Article/details/gtzvlnljmp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nanxinkj.top/Article/details/gtritdprax.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.kuanghao11.cn/Article/details/gtziqwaoex.html

[P03] 生成短随机字符串
来源：http://dali.daxiang520.top/Article/details/gtnwsyhvnt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jinqigfzy.top/Article/details/gtrewtvlob.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sysykeji.top/Article/details/gtvljnduqw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.bjfxy.top/Article/details/gtbmazczbh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shuidangran.top/Article/details/gthfyjowej.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ydzc1.top/Article/details/gtzxmkjdre.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.nanxuanxn.top/Article/details/gtvmbanuxf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhixingplan.top/Article/details/gtzictodzb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.gzhubu.top/Article/details/gtovfvbfri.html

[P04] 求长度
来源：http://dali.tanke756.top/Article/details/gtxixpuxzk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenjidiqi.icu/Article/details/gtiidakgmw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gtavalxras.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fengsongda.top/Article/details/gtsntdnfth.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jyoumei.cn/Article/details/gteirvbnqo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.wangshuangyany.cn/Article/details/gtomvshbuq.html

Go:   len(arr);  len(m)
来源：http://dali.zhiwuduotai.top/Article/details/gtnekvxana.html

Ruby: x.length;  x.size
来源：http://dali.hnqzz.top/Article/details/gtwvwmhzbs.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.chenlongwang.top/Article/details/gtsjztpkla.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoyqxhogv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.aibaodan.cn/Article/details/gtfhfiovfr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cdnleiting.top/Article/details/gtrdwnjunr.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.pengpengdd.cyou/Article/details/gtmlukgagb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenlongwang.top/Article/details/gtvdyypjbh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ybcxt.top/Article/details/gtghitsnhg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.mhx1999.top/Article/details/gtcbrlrydx.html

Ruby: a == b
来源：http://dali.aibaodan.cn/Article/details/gttsjfayhh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hnxiangtu.top/Article/details/gtauhtfqgi.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xziqi.cn/Article/details/gthkdbzkbs.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.tian-w.cn/Article/details/gtarnbvqwf.html

PHP:  if (empty($x)) {}
来源：http://dali.hnqzz.top/Article/details/gtzbwqrbdc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.feifeiyinyue.top/Article/details/gtmhsxrtkx.html

TS:   if (x == null) {}
来源：http://dali.pycfn.com/Article/details/gtiqemdkre.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hnxiangtu.top/Article/details/gtnhevaclx.html

Go:   if x == nil {}
来源：http://dali.nanxinkj.top/Article/details/gtmqzvgiix.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.fzhhl.top/Article/details/gtyyjulpwc.html

C#:   if (x is null) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtzvpvhdhd.html

[P07] 防抖与节流
来源：http://dali.hywenlv.cn/Article/details/gtuwtxpefa.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.meibo888.top/Article/details/gtptstsmfl.html

PHP:  // 手写时间戳比较
来源：http://dali.ydzc1.top/Article/details/gtiwluybdq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shzxlz.cn/Article/details/gtqgqvfukl.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtkrmhdvst.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.andypj.xyz/Article/details/gtufzlycvc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jinghuilouyu.cn/Article/details/gtdvroiyon.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xinyue.icu/Article/details/gtfhzlrtug.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hfpthk.cn/Article/details/gtevtostth.html

[P08] 处理浮点精度问题
来源：http://dali.hammf.cn/Article/details/gtdyeucdkw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gtktiurhbw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.quarkkingdee.top/Article/details/gtsrgkzruf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yueranfly.top/Article/details/gtatedmnnp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.tanke756.top/Article/details/gtdmyweyfw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.havefunace.top/Article/details/gtpncdsayi.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hongshengwenyu.top/Article/details/gtcixdovqs.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.havefunace.top/Article/details/gtwrfmnhzj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.pengpengdd.cyou/Article/details/gtymbrfznq.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gttumomvaz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.svipenyu.cn/Article/details/gtkeusydxp.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtlcoqdbyb.html

[Q01] 创建表
来源：http://dali.zhixingplan.top/Article/details/gttgxqmzxa.html

CREATE TABLE users (
来源：http://dali.yonumen.top/Article/details/gtwbkauloq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pengpengdd.cyou/Article/details/gtausokhhm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shzxlz.cn/Article/details/gtwskfuuml.html

email VARCHAR(100) UNIQUE,
来源：http://dali.mhx1999.top/Article/details/gthknyaulg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfvtyasdf.html

);
来源：http://dali.ydzc1.top/Article/details/gtpfyixwto.html

[Q02] 创建带外键的表
来源：http://dali.aibaodan.cn/Article/details/gttsbhyfsq.html

CREATE TABLE orders (
来源：http://dali.kuanghao11.cn/Article/details/gtvkpikilq.html


<!-- 参考信息 -->