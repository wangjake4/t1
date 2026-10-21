代发 wailian999

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.dashuyun.cn/Article/details/gtqkiiwtrr.html

Ruby: ENV["HOME"]
来源：http://dali.jinqigufen.top/Article/details/gtrfcqpoia.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jiagoushi.top/Article/details/gtrichjmhx.html

[M03] 执行外部命令
来源：http://dali.fengsongda.top/Article/details/gtdnckctez.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xuetiantiany.cn/Article/details/gtxflloswc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ppjwa.cn/Article/details/gtkpbayxvk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhoulong.xyz/Article/details/gttdwkyryk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xziqi.cn/Article/details/gtawyivbvf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gtlsrfupmn.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhongyouzk.top/Article/details/gtfnllrxkf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hammf.cn/Article/details/gtpibpbjli.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hnxiangtu.top/Article/details/gtsatypofb.html

[M04] 获取当前工作目录
来源：http://dali.chenzaomai.com/Article/details/gtnvftgrjz.html

Py:   os.getcwd()
来源：http://dali.nanxuanxn.top/Article/details/gtwfasybjk.html

PHP:  getcwd();
来源：http://dali.c1oappe.top/Article/details/gtselphvtt.html

JS:   process.cwd()
来源：http://dali.pycfn.com/Article/details/gthfhlpbxi.html

TS:   process.cwd()
来源：http://dali.316326.xyz/Article/details/gtkmwxubyq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.tianlin.xyz/Article/details/gtijwxpwrp.html

Go:   os.Getwd()
来源：http://dali.zhongyouzk.top/Article/details/gthflytkhx.html

Ruby: Dir.pwd
来源：http://dali.jlsjyb.cn/Article/details/gthfgmepla.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nwbrower.top/Article/details/gtniexhapf.html

[M05] 设置退出码
来源：http://dali.ydzc1.top/Article/details/gtgscpxpbm.html

Py:   sys.exit(1)
来源：http://dali.aizwys.cn/Article/details/gtmkbqqeoi.html

PHP:  exit(1);
来源：http://dali.meibo888.top/Article/details/gtjggpwhhp.html

JS:   process.exit(1)
来源：http://dali.yj20258888.top/Article/details/gtzujzzzzg.html

TS:   process.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtabirlnlr.html

Java: System.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gtgwmyklsf.html

Go:   os.Exit(1)
来源：http://dali.jiagoushi.top/Article/details/gtkarfpobh.html

Ruby: exit 1
来源：http://dali.zdqjudy.top/Article/details/gtjetklbuz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hnxiangtu.top/Article/details/gtlgkafgsq.html

[M06] 向标准错误输出
来源：http://dali.iojbl.cn/Article/details/gtggetwzcb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhongyouzk.top/Article/details/gtifdbiwxw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cashguo.top/Article/details/gtsmwqjhtw.html

JS:   console.error("err")
来源：http://dali.feifeiyinyue.top/Article/details/gtdvjirupt.html

TS:   console.error("err")
来源：http://dali.shangyingyoupin.top/Article/details/gtvebqxrfw.html

Java: System.err.println("err")
来源：http://dali.cashguo.top/Article/details/gtaakooykv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xylfe.cn/Article/details/gtzjxdccvt.html

Ruby: warn "err"
来源：http://dali.ydzc1.top/Article/details/gtgikerckx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.fzhhl.top/Article/details/gtoqzsqtng.html

[M07] 判断是否为主入口
来源：http://dali.haohaochexian.top/Article/details/gtfzcehbxh.html

Py:   if __name__ == "__main__":
来源：http://dali.zhoulong.xyz/Article/details/gtpuuihkpw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.316326.xyz/Article/details/gtbljjohor.html

JS:   require.main === module
来源：http://dali.yongpay.top/Article/details/gtjegsxtlo.html

TS:   require.main === module
来源：http://dali.yangfankeji.com/Article/details/gtxxdanpnw.html

Java: public static void main(String[] args)
来源：http://dali.aibaodan.cn/Article/details/gttwtytdjg.html

Go:   func main()
来源：http://dali.xinyue.icu/Article/details/gtpflpdtan.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jiagoushi.top/Article/details/gthmgoozyf.html

C#:   static void Main(string[] args)
来源：http://dali.cheryme.top/Article/details/gtkmztomfr.html

[M08] 获取系统与运行时信息
来源：http://dali.ybcxt.top/Article/details/gtacpjoigv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.haohaochexian.top/Article/details/gtjednfcxt.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yj202588.top/Article/details/gtmxjtxrvg.html

JS:   process.platform;  process.version
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgncyjfwb.html

TS:   process.platform;  process.version
来源：http://dali.yongpay.top/Article/details/gtwgkyzdpt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.daxiang520.top/Article/details/gtammfcdlc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sweek.top/Article/details/gtzjmwhpqn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yongpay.top/Article/details/gtpkbditox.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tianlin.xyz/Article/details/gtoybzomml.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtlldnbpnn.html

N. 数据结构与算法
来源：http://dali.c1oappe.top/Article/details/gtklkrrdmd.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtrofzrbsp.html

[N01] 二分查找（有序数组）
来源：http://dali.nanxuanxn.top/Article/details/gtfljuhbef.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gtwskbdqxk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cucudq.cn/Article/details/gtdtqfacwk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.kuanghao11.cn/Article/details/gtzqxapnkj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ppjwa.cn/Article/details/gtmzekhoih.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gtvdrtwzcp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.daria6918.cn/Article/details/gtvuclgzzf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhoulong.xyz/Article/details/gtlqiluhyd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gthduukprw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.birdmap.top/Article/details/gtivflttuz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.wangshuangyany.cn/Article/details/gtshkrzran.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.aibaodan.cn/Article/details/gtevthtkwj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shzxlz.cn/Article/details/gtrkqrgcjf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yonumen.top/Article/details/gtoqyspprv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hongshengwenyu.top/Article/details/gtfbqnhywe.html

Go:   slices.Sort(arr)
来源：http://dali.tanke756.top/Article/details/gtallzuvxt.html

Ruby: arr.sort
来源：http://dali.zhengqikj.top/Article/details/gtvajsabbo.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yueranfly.top/Article/details/gtcuwitjtf.html

[N03] 快速排序（分治示例）
来源：http://dali.feifeiyinyue.top/Article/details/gtnhmaphje.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shanyushiyangkeji.top/Article/details/gtulstyjts.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jlsjyb.cn/Article/details/gtrlxmjxhn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tian-w.cn/Article/details/gtghspiezr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xziqi.cn/Article/details/gtrwxbqvgk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ppjwa.cn/Article/details/gthuivohnz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.havefunace.top/Article/details/gtdgkscfxv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgszgtpyu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hongshengwenyu.top/Article/details/gtnuprruun.html

[N04] 斐波那契数列
来源：http://dali.yonumen.top/Article/details/gtilvjqvtg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jqgufenzy.top/Article/details/gtljkpnxra.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.daxiang520.top/Article/details/gtbkmcypde.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.havefunace.top/Article/details/gtmcpclsjs.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtqabmccdp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmsemiqnl.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhixingplan.top/Article/details/gtdcsemkwx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zdqjudy.top/Article/details/gtllsqookt.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cqqwz.cn/Article/details/gtsnusvmme.html

[N05] 最大公约数
来源：http://dali.hywenlv.cn/Article/details/gtsxafqqzv.html

Py:   math.gcd(a, b)
来源：http://dali.zhoulong.xyz/Article/details/gtdrpvcjly.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.tanke756.top/Article/details/gtavmpeiyx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hongshengwenyu.top/Article/details/gtkvpiljny.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gtwzzctuds.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhongyouzk.top/Article/details/gtwyjgfqhv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.pengpengdd.cyou/Article/details/gtdjfbhmaw.html

Ruby: a.gcd(b)
来源：http://dali.xuanzx.com/Article/details/gtpgpiyomd.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yueranfly.top/Article/details/gtbumrskwq.html

[N06] 判断回文字符串
来源：http://dali.tanke756.top/Article/details/gtmjsigskf.html

Py:   s == s[::-1]
来源：http://dali.jinqigufen.top/Article/details/gtqvlhqdcm.html

PHP:  $s === strrev($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtsqfvlxpi.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gtdoyputsu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gtycgbrcqm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sufxvd.cn/Article/details/gtavzsifje.html

Go:   // 双指针从两端比较
来源：http://dali.hnxiangtu.top/Article/details/gttwcvkxrr.html

Ruby: s == s.reverse
来源：http://dali.sweek.top/Article/details/gttoqsydee.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.iojbl.cn/Article/details/gtrlkvzhat.html

[N07] 两数之和（返回下标）
来源：http://dali.yueranfly.top/Article/details/gtqzpyiady.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkfozltyr.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj20258.top/Article/details/gttmccdigd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.nanxinkj.top/Article/details/gtfqhnujen.html

TS:   // 手写 Map<string, number>
来源：http://dali.tanke756.top/Article/details/gtgmvzmotd.html

Java: // 手写 HashMap
来源：http://dali.hnqzz.top/Article/details/gtwthbcjlx.html

Go:   // 手写 map[int]int
来源：http://dali.pengpengdd.cyou/Article/details/gtknahnhhw.html

Ruby: // 手写 Hash
来源：http://dali.yj202588.top/Article/details/gtzumdvpya.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xinyue.icu/Article/details/gtoisjyjqd.html

[N08] 生成全排列
来源：http://dali.xuetiantiany.cn/Article/details/gtuxuxuber.html

Py:   itertools.permutations(arr)
来源：http://dali.gotoacloud.top/Article/details/gtedfckpmi.html

PHP:  // 手写递归交换
来源：http://dali.pengpengdd.cyou/Article/details/gtadcfsflq.html

JS:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gtcrnopgod.html

TS:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gtnhicltjs.html

Java: // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtyvbytdmv.html

Go:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gtsjhnzvby.html

Ruby: arr.permutation.to_a
来源：http://dali.yueranfly.top/Article/details/gtpcjjqcsi.html

C#:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gtjjmuemys.html

[N09] 栈与队列
来源：http://dali.meibo888.top/Article/details/gtkywfdmdo.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ydzc1.top/Article/details/gtvzdmxltc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hnqzz.top/Article/details/gtcnzooiod.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.guannengcc.top/Article/details/gtujdtrzqv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.fzhhl.top/Article/details/gtzidwwuwn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cashguo.top/Article/details/gtwdfgxlht.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.nwbrower.top/Article/details/gtbmcysqak.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cucudq.cn/Article/details/gtjbcrqyjq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.nanxinkj.top/Article/details/gteedkkfra.html

[N10] 链表节点定义
来源：http://dali.gogol.net.cn/Article/details/gtmrhdhhyo.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfewpcpum.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.smart0.xyz/Article/details/gtqwgmtnrn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.mhx1999.top/Article/details/gtpfmvahlk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zycfv.cn/Article/details/gtpmrpbofe.html

Java: class Node { int v; Node next; }
来源：http://dali.yj20258.top/Article/details/gtndqzuwyc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhoulong.xyz/Article/details/gtgczwzwnj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shangyingyoupin.top/Article/details/gtlhewipcy.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhoulong.xyz/Article/details/gtgskauojb.html

[N11] 二叉树中序遍历
来源：http://dali.dianchejie.cn/Article/details/gteqcmqgdr.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cashguo.top/Article/details/gtapigzhlh.html

PHP:  // 手写递归函数
来源：http://dali.nwbrower.top/Article/details/gtjcfopdyb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgfzy.top/Article/details/gtirnlcbau.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hammf.cn/Article/details/gtvndstind.html

Java: // 手写递归
来源：http://dali.cheryme.top/Article/details/gtipcboyhe.html

Go:   // 手写递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtslxlldbu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhongyouzk.top/Article/details/gthaqzjaks.html

C#:   // 手写递归
来源：http://dali.xuetiantiany.cn/Article/details/gtptujvonh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shzxlz.cn/Article/details/gtjmqxlnmx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yj202588.top/Article/details/gtkfdequgp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhoulong.xyz/Article/details/gtduitrjir.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cashguo.top/Article/details/gtjjbdhgpq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cdnleiting.top/Article/details/gthetslfty.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cheryme.top/Article/details/gtckmpsenb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.fengsongda.top/Article/details/gtwkqqafzi.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.mhx1999.top/Article/details/gtzzaqiuue.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gotoacloud.top/Article/details/gtchaxwbyr.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtymiuvzlr.html

O. 并发与异步
来源：http://dali.zhiwuduotai.top/Article/details/gtantbdmwo.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtllieufzn.html

[O01] 启动一个线程
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwpfjoetr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sxryk.cn/Article/details/gtwzkvfylj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ydzc1.top/Article/details/gtozpajwdw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.fengsongda.top/Article/details/gtzdpvohal.html

TS:   // 同 JS
来源：http://dali.hysaishi.cn/Article/details/gthpotwexg.html

Java: new Thread(() -> f()).start()
来源：http://dali.quarkkingdee.top/Article/details/gttdzfgobn.html

Go:   go f()
来源：http://dali.yuxming.cn/Article/details/gtqkxjxcyl.html

Ruby: Thread.new { f }
来源：http://dali.tian-w.cn/Article/details/gtktjuuavr.html

C#:   Task.Run(() => F());
来源：http://dali.hongshengwenyu.top/Article/details/gtqtevmrag.html

[O02] 使用线程池
来源：http://dali.ivvv.top/Article/details/gtkfxzhlay.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.chenzaomai.com/Article/details/gtyiisvygs.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.chenjidiqi.icu/Article/details/gtnmplxqsx.html

JS:   // worker_threads 线程池
来源：http://dali.aizwys.cn/Article/details/gtajekejkk.html

TS:   // worker_threads 线程池
来源：http://dali.yonumen.top/Article/details/gtngsuojeg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hywenlv.cn/Article/details/gtvveqqsjx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.bjfxy.top/Article/details/gtmkjzwwiq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ppjwa.cn/Article/details/gtzcalfaio.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.kuanghao11.cn/Article/details/gtrynhyovb.html

[O03] 加锁保护共享数据
来源：http://dali.chenlongwang.top/Article/details/gtzqcrpozb.html

Py:   with lock: shared += 1
来源：http://dali.sufxvd.cn/Article/details/gtjtmhsbzy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.dianchejie.cn/Article/details/gtkllkzmab.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.tanke756.top/Article/details/gtmpgwhzop.html

TS:   // 同 JS
来源：http://dali.ppjwa.cn/Article/details/gthfenwqhj.html

Java: synchronized (this) { shared++; }
来源：http://dali.gotoacloud.top/Article/details/gtyqgkslzg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hysaishi.cn/Article/details/gthohvpmxn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuxvsnals.html

C#:   lock (gate) { shared++; }
来源：http://dali.daria6918.cn/Article/details/gtfmnlxclr.html

[O04] 定义异步函数并等待
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlpkcewoo.html

Py:   async def f():⏎    await g()
来源：http://dali.jinqigufen.top/Article/details/gthethksem.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gogol.net.cn/Article/details/gtosdjjzru.html

JS:   async function f() { await g(); }
来源：http://dali.316326.xyz/Article/details/gtrqotqdff.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yangfankeji.com/Article/details/gthwkpbppu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinghuilouyu.cn/Article/details/gtzhgorees.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hnxiangtu.top/Article/details/gtjyobqlbu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.bjfxy.top/Article/details/gtluyoxzym.html

C#:   async Task F() { await G(); }
来源：http://dali.hammf.cn/Article/details/gtcdbxuhgo.html

[O05] 并发执行并等待全部完成
来源：http://dali.316326.xyz/Article/details/gtcbikwyje.html

Py:   asyncio.gather(*tasks)
来源：http://dali.0kj1m.cn/Article/details/gtbtmmrcee.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.vqdsnc.cn/Article/details/gtdtcidmzf.html

JS:   await Promise.all(tasks)
来源：http://dali.cucudq.cn/Article/details/gtocliusxr.html

TS:   await Promise.all(tasks)
来源：http://dali.yuanzhike.top/Article/details/gtedjzrnep.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shzxlz.cn/Article/details/gtpeqzcbhg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xziqi.cn/Article/details/gtsyvkmkjo.html

Ruby: threads.map(&:join)
来源：http://dali.zhiwuduotai.top/Article/details/gtbepnmxxi.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhongyouzk.top/Article/details/gthwnjdrig.html

[O06] 使用进程池
来源：http://dali.nanxinkj.top/Article/details/gtsyyclnrk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.chenjidiqi.icu/Article/details/gtfbttfulh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.tianlin.xyz/Article/details/gtvbyeentp.html

JS:   // child_process / cluster 模块
来源：http://dali.nwbrower.top/Article/details/gtgwhwytpc.html

TS:   // child_process / cluster 模块
来源：http://dali.xylfe.cn/Article/details/gtydyvszin.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yonumen.top/Article/details/gtyzobhski.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.andypj.xyz/Article/details/gtqzfhnnbw.html

Ruby: // fork 块
来源：http://dali.aibaodan.cn/Article/details/gtqylqtazv.html

C#:   Parallel.For
来源：http://dali.fzhhl.top/Article/details/gtzrnvshlt.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gteibkgitr.html

P. 常用工具函数
来源：http://dali.svipenyu.cn/Article/details/gtepfjkuyk.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtdqzkokwh.html

[P01] 生成 UUID
来源：http://dali.hywenlv.cn/Article/details/gtgadcuouy.html

Py:   str(uuid.uuid4())
来源：http://dali.tianlin.xyz/Article/details/gtufkpcxgg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zdqjudy.top/Article/details/gtnnurbexe.html

JS:   crypto.randomUUID()
来源：http://dali.c1oappe.top/Article/details/gtczaabtfj.html

TS:   crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gttfolkmpy.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsnmjqncp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ehwqpu.com/Article/details/gtehxdlgwn.html

Ruby: SecureRandom.uuid
来源：http://dali.jinqigufen.top/Article/details/gtmfdzpqmq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.316326.xyz/Article/details/gtgkxqekvs.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shanyushiyangtech.top/Article/details/gtadcmfiji.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yangfankeji.com/Article/details/gtvckgwvpc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.tanke756.top/Article/details/gtktcavczh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ppjwa.cn/Article/details/gtrnjmhpjo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.9152youxi.cn/Article/details/gtxystjrhv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jiagoushi.top/Article/details/gtunoluqzv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gogol.net.cn/Article/details/gtqatdqqrt.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.tanke756.top/Article/details/gtswpnxlvk.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gttniixysk.html

[P03] 生成短随机字符串
来源：http://dali.guannengcc.top/Article/details/gtojbqkgth.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.andypj.xyz/Article/details/gtbfepjrzd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jinqigfzy.top/Article/details/gtjziqwpbi.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtfqmkdtnb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.haohaochexian.top/Article/details/gtfksvgdnr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.pycfn.com/Article/details/gtsnsmascd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.nanxuanxn.top/Article/details/gtpchbnrxh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.tanke756.top/Article/details/gtdgyxshdt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.andypj.xyz/Article/details/gtuuslphdq.html

[P04] 求长度
来源：http://dali.daria6918.cn/Article/details/gtvyjkreev.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cucudq.cn/Article/details/gtlguurpsz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gtbaljmshh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hysaishi.cn/Article/details/gttnoaaysf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhoulong.xyz/Article/details/gtiubwdetr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xinyue.icu/Article/details/gtotvhnwwd.html

Go:   len(arr);  len(m)
来源：http://dali.nanxuanxn.top/Article/details/gtmfihmgby.html

Ruby: x.length;  x.size
来源：http://dali.aibaodan.cn/Article/details/gtjblywctc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.gaohongyu789.top/Article/details/gtcxxboedv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.smart0.xyz/Article/details/gtcrnmsszm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.redwolf501.top/Article/details/gtdaxzjpce.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhongyouzk.top/Article/details/gtvdiqdggz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.nwbrower.top/Article/details/gtfuaivbvx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sufxvd.cn/Article/details/gtqphsuavl.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkavohyga.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yvedp.cn/Article/details/gtkfftnlje.html

Ruby: a == b
来源：http://dali.feifeiyinyue.top/Article/details/gtbgicjjhw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cashguo.top/Article/details/gtiavrqeof.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yj20258.top/Article/details/gtwyettgcd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xziqi.cn/Article/details/gtcniloijp.html

PHP:  if (empty($x)) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmxoxczbc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.smart0.xyz/Article/details/gtaigmxxuu.html

TS:   if (x == null) {}
来源：http://dali.gaohongyu789.top/Article/details/gtzeaqmwbn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.meibo888.top/Article/details/gtmhvddrso.html

Go:   if x == nil {}
来源：http://dali.xuanzx.com/Article/details/gtgbbdbett.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yvedp.cn/Article/details/gtmhkaihhf.html

C#:   if (x is null) {}
来源：http://dali.c1oappe.top/Article/details/gtrpxjdokg.html

[P07] 防抖与节流
来源：http://dali.shzxlz.cn/Article/details/gtlottnkyo.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.svipenyu.cn/Article/details/gtixigqsoa.html

PHP:  // 手写时间戳比较
来源：http://dali.hywenlv.cn/Article/details/gtrtiidxba.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.svipenyu.cn/Article/details/gtajnhhrum.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zdqjudy.top/Article/details/gtzxqetrtt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yongpay.top/Article/details/gttamlgygk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.0kj1m.cn/Article/details/gtgcvsvrns.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhoulong.xyz/Article/details/gtdytmmgmv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zycfv.cn/Article/details/gtleadlong.html

[P08] 处理浮点精度问题
来源：http://dali.aizwys.cn/Article/details/gtqzivucbr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yongpay.top/Article/details/gtidtmablx.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.haohaochexian.top/Article/details/gtmevpxprf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zdqjudy.top/Article/details/gtnboorcbt.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.haohaochexian.top/Article/details/gtxjrbejqm.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yonumen.top/Article/details/gtouakjnzc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhongyouzk.top/Article/details/gttlimpqgn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cashguo.top/Article/details/gtnqmfexio.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.redwolf501.top/Article/details/gtmzuijchd.html


<!-- 参考信息 -->