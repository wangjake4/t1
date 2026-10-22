代发 wailian999

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.aizwys.cn/Article/details/gt2fjpckkog.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.haohaochexian.top/Article/details/gt2whhnzwyh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.daria6918.cn/Article/details/gt2bccmrvni.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.haohaochexian.top/Article/details/gt2zibkqwzs.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xuetiantiany.cn/Article/details/gt2akfzlmdw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zycfv.cn/Article/details/gt2qolglifv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shuidangran.top/Article/details/gt2dqnzudll.html

C#:   Process.Start("ls", "-l");
来源：http://dali.fzhhl.top/Article/details/gt2dwqqxmnt.html

[M04] 获取当前工作目录
来源：http://dali.pycfn.com/Article/details/gt2rodtasvi.html

Py:   os.getcwd()
来源：http://dali.sufxvd.cn/Article/details/gt2ctvwytrj.html

PHP:  getcwd();
来源：http://dali.jlsjyb.cn/Article/details/gt2xtztfias.html

JS:   process.cwd()
来源：http://dali.fengsongda.top/Article/details/gt2aheqgqsh.html

TS:   process.cwd()
来源：http://dali.hnqzz.top/Article/details/gt2owwqvnyu.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.bjfxy.top/Article/details/gt2bqxskqqo.html

Go:   os.Getwd()
来源：http://dali.yangfankeji.com/Article/details/gt2bejkkxkk.html

Ruby: Dir.pwd
来源：http://dali.aizwys.cn/Article/details/gt2ozheqdgg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.feifeiyinyue.top/Article/details/gt2sbrfuxxy.html

[M05] 设置退出码
来源：http://dali.iojbl.cn/Article/details/gt2ereutxsf.html

Py:   sys.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rzvmyeod.html

PHP:  exit(1);
来源：http://dali.quarkkingdee.top/Article/details/gt2zqmkdylo.html

JS:   process.exit(1)
来源：http://dali.yvedp.cn/Article/details/gt2zmimmlsp.html

TS:   process.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ljytwbyn.html

Java: System.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gt2qyjlgqqr.html

Go:   os.Exit(1)
来源：http://dali.yvedp.cn/Article/details/gt2swldsmzd.html

Ruby: exit 1
来源：http://dali.zhixingplan.top/Article/details/gt2quzacuoz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhengqikj.top/Article/details/gt2mjzbkfbo.html

[M06] 向标准错误输出
来源：http://dali.zycfv.cn/Article/details/gt2vazasibl.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sweek.top/Article/details/gt2ybthtoal.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2jzuwfwvh.html

JS:   console.error("err")
来源：http://dali.haohaochexian.top/Article/details/gt2snnndjyk.html

TS:   console.error("err")
来源：http://dali.yj20258.top/Article/details/gt2azjvajpz.html

Java: System.err.println("err")
来源：http://dali.xinyue.icu/Article/details/gt2uuglrram.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hnxiangtu.top/Article/details/gt2pgzeyulw.html

Ruby: warn "err"
来源：http://dali.pycfn.com/Article/details/gt2sljmaknn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sxryk.cn/Article/details/gt2jqjrvnfq.html

[M07] 判断是否为主入口
来源：http://dali.jqgfzy.top/Article/details/gt2jzswwirw.html

Py:   if __name__ == "__main__":
来源：http://dali.shzxlz.cn/Article/details/gt2ujcmtkjm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.birdmap.top/Article/details/gt2iuiaxbmb.html

JS:   require.main === module
来源：http://dali.aibaodan.cn/Article/details/gt2motgotqq.html

TS:   require.main === module
来源：http://dali.yj20258.top/Article/details/gt2lnmjfswj.html

Java: public static void main(String[] args)
来源：http://dali.jqgufenzy.top/Article/details/gt2mvcokugc.html

Go:   func main()
来源：http://dali.nanxuanxn.top/Article/details/gt2kedwhugx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.feifeiyinyue.top/Article/details/gt2mnylauic.html

C#:   static void Main(string[] args)
来源：http://dali.shzxlz.cn/Article/details/gt2dlqytyic.html

[M08] 获取系统与运行时信息
来源：http://dali.sysykeji.top/Article/details/gt2czprviqb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj202588.top/Article/details/gt2qrwlmzui.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zycfv.cn/Article/details/gt2edkyoauu.html

JS:   process.platform;  process.version
来源：http://dali.tianlin.xyz/Article/details/gt2hwekclwy.html

TS:   process.platform;  process.version
来源：http://dali.dianchejie.cn/Article/details/gt2tbnefdwr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.fengsongda.top/Article/details/gt2xnjdtvic.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.svipenyu.cn/Article/details/gt2qgirwzud.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhixingplan.top/Article/details/gt2rufinyar.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cqqwz.cn/Article/details/gt2guqhgguf.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2gpamynaf.html

N. 数据结构与算法
来源：http://dali.meibo888.top/Article/details/gt2egkvwmfj.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2gtindfia.html

[N01] 二分查找（有序数组）
来源：http://dali.daria6918.cn/Article/details/gt2xxmuchnn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yj202588.top/Article/details/gt2qemekbqh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gzhubu.top/Article/details/gt2yiyjhpyu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guannengcc.top/Article/details/gt2hgrniyhq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gt2nxuhdzjw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2uqtxrmyi.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yurttlzi.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yueranfly.top/Article/details/gt2xgfnzlqu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gt2gwyxnfoc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2imojxvju.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxuanxn.top/Article/details/gt2bgvqkmau.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.smart0.xyz/Article/details/gt2qpnlpjvt.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dashuyun.cn/Article/details/gt2erlauuef.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.bjfxy.top/Article/details/gt2aotokvdt.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2autvxrho.html

Go:   slices.Sort(arr)
来源：http://dali.birdmap.top/Article/details/gt2nhiwhqjt.html

Ruby: arr.sort
来源：http://dali.tianlin.xyz/Article/details/gt2hvmzvztz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gaohongyu789.top/Article/details/gt2ernhplqi.html

[N03] 快速排序（分治示例）
来源：http://dali.nanxinkj.top/Article/details/gt2xosalcrf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sbicnjwq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.nanxinkj.top/Article/details/gt2oizgudpa.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gaohongyu789.top/Article/details/gt2ihgsaqwy.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cqqwz.cn/Article/details/gt2gvycdgfu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhongyouzk.top/Article/details/gt2dwaarmyi.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.snrcjt.cn/Article/details/gt2mturlhej.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zdqjudy.top/Article/details/gt2klcnggcy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.iojbl.cn/Article/details/gt2hbujhabg.html

[N04] 斐波那契数列
来源：http://dali.svipenyu.cn/Article/details/gt2jgutbasr.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vkzxwcqn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ybcxt.top/Article/details/gt2fqcmfpoz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gogol.net.cn/Article/details/gt2mxzszuxa.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dianchejie.cn/Article/details/gt2hfdcqxrf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.sufxvd.cn/Article/details/gt2ivnpgzif.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yanxiufei.cn/Article/details/gt2cvmsiadw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ydzc1.top/Article/details/gt2bcbqvtzv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.iojbl.cn/Article/details/gt2vkieeomr.html

[N05] 最大公约数
来源：http://dali.xylfe.cn/Article/details/gt2emicmhdg.html

Py:   math.gcd(a, b)
来源：http://dali.cdnleiting.top/Article/details/gt2yiiqnohw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gotoacloud.top/Article/details/gt2neabzdtd.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jyoumei.cn/Article/details/gt2vpgzrxje.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2czhptwfw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.wangshuangyany.cn/Article/details/gt2ftffxfpj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.tanke756.top/Article/details/gt2ncsfekat.html

Ruby: a.gcd(b)
来源：http://dali.birdmap.top/Article/details/gt2xublywye.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ehwqpu.com/Article/details/gt2zkpswypt.html

[N06] 判断回文字符串
来源：http://dali.hysaishi.cn/Article/details/gt2wqvoszwn.html

Py:   s == s[::-1]
来源：http://dali.zhixingplan.top/Article/details/gt2pmjetszx.html

PHP:  $s === strrev($s);
来源：http://dali.cdnleiting.top/Article/details/gt2yjkehtrq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gt2umfmfrbo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gt2dkitsqdt.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.dashuyun.cn/Article/details/gt2myrxwlgh.html

Go:   // 双指针从两端比较
来源：http://dali.jlsjyb.cn/Article/details/gt2jzkeukzp.html

Ruby: s == s.reverse
来源：http://dali.yvedp.cn/Article/details/gt2qvyouupq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yuanzhike.top/Article/details/gt2baeyktdc.html

[N07] 两数之和（返回下标）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rjcsttfd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xuetiantiany.cn/Article/details/gt2zwyectet.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhongyouzk.top/Article/details/gt2juduwrrq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.chenlongwang.top/Article/details/gt2qhpbbmww.html

TS:   // 手写 Map<string, number>
来源：http://dali.bjfxy.top/Article/details/gt2dotdfmqd.html

Java: // 手写 HashMap
来源：http://dali.feifeiyinyue.top/Article/details/gt2dqnpdsci.html

Go:   // 手写 map[int]int
来源：http://dali.yuanzhike.top/Article/details/gt2ihissusx.html

Ruby: // 手写 Hash
来源：http://dali.hfpthk.cn/Article/details/gt2rlojlwps.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.smart0.xyz/Article/details/gt2lnbnenkk.html

[N08] 生成全排列
来源：http://dali.wangshuangyany.cn/Article/details/gt2likkmyqm.html

Py:   itertools.permutations(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2yqpdcmlx.html

PHP:  // 手写递归交换
来源：http://dali.aibaodan.cn/Article/details/gt2jwftcrle.html

JS:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gt2ydxdmzrn.html

TS:   // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gt2xnflcpjv.html

Java: // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gt2vdkgqezi.html

Go:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gt2artkryzz.html

Ruby: arr.permutation.to_a
来源：http://dali.svipenyu.cn/Article/details/gt2hglffoph.html

C#:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gt2nauaxmbo.html

[N09] 栈与队列
来源：http://dali.pengpengdd.cyou/Article/details/gt2rmqniamw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sxryk.cn/Article/details/gt2pimlqueb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gt2vgrpfrzy.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.havefunace.top/Article/details/gt2ixsceqzx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xuetiantiany.cn/Article/details/gt2frpvvjwk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.chenlongwang.top/Article/details/gt2tybfnvch.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ybcxt.top/Article/details/gt2arwaujky.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gt2sdfsagst.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.wangshuangyany.cn/Article/details/gt2mjlgnmbf.html

[N10] 链表节点定义
来源：http://dali.hnqzz.top/Article/details/gt2kuizvpwq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gaohongyu789.top/Article/details/gt2ordqlhuq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xziqi.cn/Article/details/gt2gpjyeedk.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.wangshuangyany.cn/Article/details/gt2wiiuunha.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yj20258888.top/Article/details/gt2vspjxqyu.html

Java: class Node { int v; Node next; }
来源：http://dali.hywenlv.cn/Article/details/gt2wvophasa.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hnxiangtu.top/Article/details/gt2saqzgkhf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xziqi.cn/Article/details/gt2iyanwnsu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.sufxvd.cn/Article/details/gt2jnoreaqk.html

[N11] 二叉树中序遍历
来源：http://dali.yuxming.cn/Article/details/gt2qatwrxgm.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ppjwa.cn/Article/details/gt2ebgmuabu.html

PHP:  // 手写递归函数
来源：http://dali.ppjwa.cn/Article/details/gt2rbwynlra.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hongshengwenyu.top/Article/details/gt2vwgqzwox.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xuanzx.com/Article/details/gt2sdmflzhm.html

Java: // 手写递归
来源：http://dali.wangdashe.top/Article/details/gt2bvxftpso.html

Go:   // 手写递归
来源：http://dali.xuanzx.com/Article/details/gt2agdbjrfr.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zdqjudy.top/Article/details/gt2uznduujd.html

C#:   // 手写递归
来源：http://dali.sxryk.cn/Article/details/gt2rczioetd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yvedp.cn/Article/details/gt2umiaizlx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.nwbrower.top/Article/details/gt2jukmlwqv.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xinyue.icu/Article/details/gt2xhyoslqi.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenzaomai.com/Article/details/gt2nfidfyzp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.feifeiyinyue.top/Article/details/gt2plvbxmie.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yvedp.cn/Article/details/gt2zuayjcjp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xylfe.cn/Article/details/gt2jyufnrll.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2saplynby.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ivvv.top/Article/details/gt2fayfjiow.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2gqobnwpj.html

O. 并发与异步
来源：http://dali.haohaochexian.top/Article/details/gt2tiffogdf.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2ftbwkooq.html

[O01] 启动一个线程
来源：http://dali.yj20258.top/Article/details/gt2orvuyvoo.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.fengsongda.top/Article/details/gt2fftkfcve.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.wangdashe.top/Article/details/gt2lqfmxydc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.daria6918.cn/Article/details/gt2xhtfvyxa.html

TS:   // 同 JS
来源：http://dali.9152youxi.cn/Article/details/gt2zybutxew.html

Java: new Thread(() -> f()).start()
来源：http://dali.ydzc1.top/Article/details/gt2xqjxisyy.html

Go:   go f()
来源：http://dali.9152youxi.cn/Article/details/gt2bnascycp.html

Ruby: Thread.new { f }
来源：http://dali.wangshuangyany.cn/Article/details/gt2xnqkhunb.html

C#:   Task.Run(() => F());
来源：http://dali.yj202588.top/Article/details/gt2rwfnrjwk.html

[O02] 使用线程池
来源：http://dali.hammf.cn/Article/details/gt2wbjhonmk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ppjwa.cn/Article/details/gt2jtpmarxr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sweek.top/Article/details/gt2isgjjafz.html

JS:   // worker_threads 线程池
来源：http://dali.jyoumei.cn/Article/details/gt2qicdyxys.html

TS:   // worker_threads 线程池
来源：http://dali.jinqigfzy.top/Article/details/gt2lzvpcccx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.sxryk.cn/Article/details/gt2hsegtbfd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gotoacloud.top/Article/details/gt2nytqljru.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.nwbrower.top/Article/details/gt2nbcjpukc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yueranfly.top/Article/details/gt2zcuwpxjc.html

[O03] 加锁保护共享数据
来源：http://dali.0kj1m.cn/Article/details/gt2cgiuztht.html

Py:   with lock: shared += 1
来源：http://dali.cqqwz.cn/Article/details/gt2ngrkhmum.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gogol.net.cn/Article/details/gt2olfsaaja.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.sxryk.cn/Article/details/gt2ndsqhtfh.html

TS:   // 同 JS
来源：http://dali.ivvv.top/Article/details/gt2iztnabph.html

Java: synchronized (this) { shared++; }
来源：http://dali.0kj1m.cn/Article/details/gt2smwlftnc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jyoumei.cn/Article/details/gt2jwizkmkw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shuidangran.top/Article/details/gt2rxeuyegt.html

C#:   lock (gate) { shared++; }
来源：http://dali.yongpay.top/Article/details/gt2brvanfnc.html

[O04] 定义异步函数并等待
来源：http://dali.zhixingplan.top/Article/details/gt2vppkqbkd.html

Py:   async def f():⏎    await g()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tvgauoan.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cucudq.cn/Article/details/gt2ficgqqfk.html

JS:   async function f() { await g(); }
来源：http://dali.andypj.xyz/Article/details/gt2xpeandty.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zycfv.cn/Article/details/gt2clqvakqy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yvedp.cn/Article/details/gt2xpysvfls.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.aibaodan.cn/Article/details/gt2eegqvhos.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cqqwz.cn/Article/details/gt2dwxnkasu.html

C#:   async Task F() { await G(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2jnmvpfan.html

[O05] 并发执行并等待全部完成
来源：http://dali.cdnleiting.top/Article/details/gt2pgelyvtv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tzfmgopc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ydzc1.top/Article/details/gt2hejfqsgu.html

JS:   await Promise.all(tasks)
来源：http://dali.guannengcc.top/Article/details/gt2yepoftxj.html

TS:   await Promise.all(tasks)
来源：http://dali.shuidangran.top/Article/details/gt2tmulmown.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.pengpengdd.cyou/Article/details/gt2khnylqaf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhixingplan.top/Article/details/gt2yqdkozzs.html

Ruby: threads.map(&:join)
来源：http://dali.hfpthk.cn/Article/details/gt2wuvzolvb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.chenzaomai.com/Article/details/gt2quhgivfi.html

[O06] 使用进程池
来源：http://dali.sufxvd.cn/Article/details/gt2xlgpldhx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.gzhubu.top/Article/details/gt2imunikll.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhllwki.html

JS:   // child_process / cluster 模块
来源：http://dali.xylfe.cn/Article/details/gt2vunrkbhh.html

TS:   // child_process / cluster 模块
来源：http://dali.shuidangran.top/Article/details/gt2grqyagyb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shzxlz.cn/Article/details/gt2cpdjazer.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xziqi.cn/Article/details/gt2hwqmgsab.html

Ruby: // fork 块
来源：http://dali.zdqjudy.top/Article/details/gt2htlbimuu.html

C#:   Parallel.For
来源：http://dali.yanxiufei.cn/Article/details/gt2plxeuznz.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2qwtxzuwl.html

P. 常用工具函数
来源：http://dali.cheryme.top/Article/details/gt2phwseqga.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2vpewatzv.html

[P01] 生成 UUID
来源：http://dali.hammf.cn/Article/details/gt2ttwjfkws.html

Py:   str(uuid.uuid4())
来源：http://dali.ybcxt.top/Article/details/gt2qsjjdqjl.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sxryk.cn/Article/details/gt2htbgvmnb.html

JS:   crypto.randomUUID()
来源：http://dali.mhx1999.top/Article/details/gt2ksxhwyjr.html

TS:   crypto.randomUUID()
来源：http://dali.yangfankeji.com/Article/details/gt2nnzmqtee.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhengqikj.top/Article/details/gt2fmvmfhzr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.nanxuanxn.top/Article/details/gt2xbmbeapa.html

Ruby: SecureRandom.uuid
来源：http://dali.ehwqpu.com/Article/details/gt2japzeqaj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.havefunace.top/Article/details/gt2wkcrddlr.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hywenlv.cn/Article/details/gt2eibsqtrf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.wangdashe.top/Article/details/gt2hmrasmjt.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinqigufen.top/Article/details/gt2uahxdvxs.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yvedp.cn/Article/details/gt2qarrdtua.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hywenlv.cn/Article/details/gt2kqzebatj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.pengpengdd.cyou/Article/details/gt2rtylwktj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cashguo.top/Article/details/gt2yrqxfjzq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cashguo.top/Article/details/gt2cbwrllse.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.guowangkeji.top/Article/details/gt2ykeefiia.html

[P03] 生成短随机字符串
来源：http://dali.mhx1999.top/Article/details/gt2mjzdyvos.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.chenjidiqi.icu/Article/details/gt2czqtbbgx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yueranfly.top/Article/details/gt2nydjgbmn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daxiang520.top/Article/details/gt2zyopdjlm.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xziqi.cn/Article/details/gt2lhqmcxvc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jqgufenzy.top/Article/details/gt2pkalfayw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.dianchejie.cn/Article/details/gt2sdodpxdy.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.dianchejie.cn/Article/details/gt2ldqnglti.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xylfe.cn/Article/details/gt2bntnbjnj.html

[P04] 求长度
来源：http://dali.yvedp.cn/Article/details/gt2yuaklvpv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.316326.xyz/Article/details/gt2afovgiyi.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gt2zopusypx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jianghu66.top/Article/details/gt2nedkleqj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cheryme.top/Article/details/gt2fswpjazu.html

Java: list.size();  map.size();  s.length()
来源：http://dali.guannengcc.top/Article/details/gt2dylelcgg.html

Go:   len(arr);  len(m)
来源：http://dali.hysaishi.cn/Article/details/gt2iqjjhfbw.html

Ruby: x.length;  x.size
来源：http://dali.nwbrower.top/Article/details/gt2xwabhsow.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.pycfn.com/Article/details/gt2kuvbaajt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yuanzhike.top/Article/details/gt2ieacmmxx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.nwbrower.top/Article/details/gt2uzaougtp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.wangdashe.top/Article/details/gt2gxphhhhe.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yangfankeji.com/Article/details/gt2eriarwku.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.dianchejie.cn/Article/details/gt2yhejfktq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhixingplan.top/Article/details/gt2iotrmzix.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhoulong.xyz/Article/details/gt2fcciwmxi.html

Ruby: a == b
来源：http://dali.ehwqpu.com/Article/details/gt2ssvepfcd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jlsjyb.cn/Article/details/gt2emzhswpq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.tanke756.top/Article/details/gt2vgvtveoi.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinqigufen.top/Article/details/gt2aieqiuvg.html

PHP:  if (empty($x)) {}
来源：http://dali.xinyue.icu/Article/details/gt2jtixwhka.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.kuanghao11.cn/Article/details/gt2wlrmzwxq.html

TS:   if (x == null) {}
来源：http://dali.cdnleiting.top/Article/details/gt2vqzswcsk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yueranfly.top/Article/details/gt2aqvushob.html

Go:   if x == nil {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qzbpqvjl.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sxryk.cn/Article/details/gt2kiaqigyu.html

C#:   if (x is null) {}
来源：http://dali.yuxming.cn/Article/details/gt2xldukpfr.html

[P07] 防抖与节流
来源：http://dali.mhx1999.top/Article/details/gt2pqahbais.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xuetiantiany.cn/Article/details/gt2reenvmjw.html

PHP:  // 手写时间戳比较
来源：http://dali.xziqi.cn/Article/details/gt2yprnylaq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pycfn.com/Article/details/gt2advjjzoa.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zycfv.cn/Article/details/gt2rvyzhmpv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.316326.xyz/Article/details/gt2mewmgpdz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.tian-w.cn/Article/details/gt2laxikhqs.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jlsjyb.cn/Article/details/gt2kqojrxvm.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sweek.top/Article/details/gt2rgwxgpga.html

[P08] 处理浮点精度问题
来源：http://dali.ydzc1.top/Article/details/gt2qsshblui.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ucxyfdxf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.fengsongda.top/Article/details/gt2tvatecnv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ybcxt.top/Article/details/gt2lnkkwhxa.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yueranfly.top/Article/details/gt2exbqprzl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gzhubu.top/Article/details/gt2mvyukyhh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.0kj1m.cn/Article/details/gt2lwpaynpt.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.dianchejie.cn/Article/details/gt2tquatakg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.kuanghao11.cn/Article/details/gt2ucnfetum.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2oebiemah.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sufxvd.cn/Article/details/gt2aldjtqum.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2eksyszxd.html

[Q01] 创建表
来源：http://dali.shangyingyoupin.top/Article/details/gt2qmlcnbng.html


<!-- 参考信息 -->