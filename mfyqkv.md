代发 wailian999

Ruby: ARGV
来源：http://dali.iojbl.cn/Article/details/gtrfwofnjj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.meibo888.top/Article/details/gtjgqjiums.html

[M02] 读取环境变量
来源：http://dali.yuanzhike.top/Article/details/gtyivpuzrt.html

Py:   os.environ.get("HOME")
来源：http://dali.ivvv.top/Article/details/gtnztifsoi.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhoulong.xyz/Article/details/gtotchovbj.html

JS:   process.env.HOME
来源：http://dali.mhx1999.top/Article/details/gtvmkvhaps.html

TS:   process.env.HOME
来源：http://dali.guowangkeji.top/Article/details/gtytvoibrf.html

Java: System.getenv("HOME")
来源：http://dali.gogol.net.cn/Article/details/gtvtctgvxr.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jiagoushi.top/Article/details/gtbiofewnx.html

Ruby: ENV["HOME"]
来源：http://dali.tanke756.top/Article/details/gtdshxntxf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gticmianaf.html

[M03] 执行外部命令
来源：http://dali.gotoacloud.top/Article/details/gthhuwwnju.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cheryme.top/Article/details/gtjimfpouz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.haohaochexian.top/Article/details/gtqkckqtvf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbstiabyp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.dianchejie.cn/Article/details/gtzofjqxpc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ybcxt.top/Article/details/gtpppydztu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ppjwa.cn/Article/details/gtamkwseph.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hongshengwenyu.top/Article/details/gtbooxcjxp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hammf.cn/Article/details/gtahridsjv.html

[M04] 获取当前工作目录
来源：http://dali.zycfv.cn/Article/details/gtrggkybns.html

Py:   os.getcwd()
来源：http://dali.svipenyu.cn/Article/details/gtgmoknnax.html

PHP:  getcwd();
来源：http://dali.hongshengwenyu.top/Article/details/gtuvcpqrni.html

JS:   process.cwd()
来源：http://dali.aizwys.cn/Article/details/gtahxkzjiv.html

TS:   process.cwd()
来源：http://dali.yonumen.top/Article/details/gtbvvwaqel.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.daxiang520.top/Article/details/gtalpudnss.html

Go:   os.Getwd()
来源：http://dali.jlsjyb.cn/Article/details/gtlukxogsj.html

Ruby: Dir.pwd
来源：http://dali.daxiang520.top/Article/details/gtpogbyvxd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.daria6918.cn/Article/details/gtxajtjvde.html

[M05] 设置退出码
来源：http://dali.9152youxi.cn/Article/details/gtwbrinwuk.html

Py:   sys.exit(1)
来源：http://dali.aizwys.cn/Article/details/gtshkincgm.html

PHP:  exit(1);
来源：http://dali.andypj.xyz/Article/details/gtyxwcbffq.html

JS:   process.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gtpwsgulwn.html

TS:   process.exit(1)
来源：http://dali.ybcxt.top/Article/details/gtudyimqai.html

Java: System.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gtiynagdls.html

Go:   os.Exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtnntduoed.html

Ruby: exit 1
来源：http://dali.yangfankeji.com/Article/details/gtcajcqtol.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cheryme.top/Article/details/gtvdoochko.html

[M06] 向标准错误输出
来源：http://dali.nanxinkj.top/Article/details/gtsvtpokgc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.c1oappe.top/Article/details/gtecnvcgup.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.bjfxy.top/Article/details/gtuvzmqhvm.html

JS:   console.error("err")
来源：http://dali.fzhhl.top/Article/details/gtrkffcerp.html

TS:   console.error("err")
来源：http://dali.gaohongyu789.top/Article/details/gthqtprvwj.html

Java: System.err.println("err")
来源：http://dali.ybcxt.top/Article/details/gtotkyxloj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yuanzhike.top/Article/details/gtgloqsmbw.html

Ruby: warn "err"
来源：http://dali.hysaishi.cn/Article/details/gtmcyhohuf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yj20258888.top/Article/details/gtkmpxqlhe.html

[M07] 判断是否为主入口
来源：http://dali.cdnleiting.top/Article/details/gtcwnxcuoc.html

Py:   if __name__ == "__main__":
来源：http://dali.haohaochexian.top/Article/details/gtbasfvdts.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.andypj.xyz/Article/details/gtjonfawap.html

JS:   require.main === module
来源：http://dali.chenlongwang.top/Article/details/gttfrjvlpa.html

TS:   require.main === module
来源：http://dali.jinqigufen.top/Article/details/gthmzojcfq.html

Java: public static void main(String[] args)
来源：http://dali.hnxiangtu.top/Article/details/gtdwzgjvoi.html

Go:   func main()
来源：http://dali.jianghu66.top/Article/details/gtbvtxntml.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xinyue.icu/Article/details/gtppaxszsg.html

C#:   static void Main(string[] args)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkqdgjigb.html

[M08] 获取系统与运行时信息
来源：http://dali.jlsjyb.cn/Article/details/gtydpvbltu.html

Py:   platform.system();  platform.python_version()
来源：http://dali.vqdsnc.cn/Article/details/gtthnkdhag.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hongshengwenyu.top/Article/details/gtxzqunnqt.html

JS:   process.platform;  process.version
来源：http://dali.yuanzhike.top/Article/details/gtbqqogfen.html

TS:   process.platform;  process.version
来源：http://dali.tanke756.top/Article/details/gttovoxtbq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jlsjyb.cn/Article/details/gtbmqnhmzr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinqigufen.top/Article/details/gtpvodenee.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.dianchejie.cn/Article/details/gtfcgvzoow.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xuetiantiany.cn/Article/details/gtgehfzzdl.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtjmdobpsp.html

N. 数据结构与算法
来源：http://dali.pycfn.com/Article/details/gtlbfdoqhp.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtltoyzqwe.html

[N01] 二分查找（有序数组）
来源：http://dali.ehwqpu.com/Article/details/gtbzjealdf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ivvv.top/Article/details/gtbbhljrze.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhongyouzk.top/Article/details/gtecssdaed.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gtkfpeodxw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuanzhike.top/Article/details/gtbwfnfyku.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtdqduudyn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtqhqgephn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmisezbiu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtpxufttqc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nanxuanxn.top/Article/details/gtoesnfkba.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hfpthk.cn/Article/details/gtplflewqr.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yangfankeji.com/Article/details/gtujlyicwh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhixingplan.top/Article/details/gttlquvroa.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.haohaochexian.top/Article/details/gthatkhcvh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hywenlv.cn/Article/details/gtkkliocjn.html

Go:   slices.Sort(arr)
来源：http://dali.wangdashe.top/Article/details/gtsnwbayjd.html

Ruby: arr.sort
来源：http://dali.smart0.xyz/Article/details/gtnzaweyje.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yuanzhike.top/Article/details/gtizjplkyn.html

[N03] 快速排序（分治示例）
来源：http://dali.jiagoushi.top/Article/details/gtwnwtivus.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.meibo888.top/Article/details/gtemhvzkow.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gotoacloud.top/Article/details/gtbcxfraez.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenzaomai.com/Article/details/gtmlvnokst.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.birdmap.top/Article/details/gtoaibjour.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xziqi.cn/Article/details/gtffhhxssx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jqgufenzy.top/Article/details/gtseagagpk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.kuanghao11.cn/Article/details/gtgjcdwmnp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jqgufenzy.top/Article/details/gtowrjcoxq.html

[N04] 斐波那契数列
来源：http://dali.sxryk.cn/Article/details/gtwksvippv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.vqdsnc.cn/Article/details/gtrksfpcgu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.pycfn.com/Article/details/gtsyabkfow.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gtfqxhvhhg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tian-w.cn/Article/details/gtnajfdhvs.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.guowangkeji.top/Article/details/gthjecgudj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwmsqumyc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yuxming.cn/Article/details/gtxadztucc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.redwolf501.top/Article/details/gtisvvribg.html

[N05] 最大公约数
来源：http://dali.gaohongyu789.top/Article/details/gticsgdqix.html

Py:   math.gcd(a, b)
来源：http://dali.zhiwuduotai.top/Article/details/gtnzfdiufs.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.redwolf501.top/Article/details/gtoxberaln.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.0kj1m.cn/Article/details/gtbwgiusnf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xylfe.cn/Article/details/gtqgheqxwd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.mhx1999.top/Article/details/gtylxnsama.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hnxiangtu.top/Article/details/gtcnzrlivt.html

Ruby: a.gcd(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqwoqfobo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrsxrvzjb.html

[N06] 判断回文字符串
来源：http://dali.haohaochexian.top/Article/details/gtycpoccek.html

Py:   s == s[::-1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtekrqczlb.html

PHP:  $s === strrev($s);
来源：http://dali.yangfankeji.com/Article/details/gtzolgqruh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yj20258888.top/Article/details/gtpdmaflia.html

TS:   s === [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gtfiepjxcz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.dashuyun.cn/Article/details/gteumefczy.html

Go:   // 双指针从两端比较
来源：http://dali.tanke756.top/Article/details/gtkrlwzjyr.html

Ruby: s == s.reverse
来源：http://dali.zhixingplan.top/Article/details/gtmqqntjgp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.bjfxy.top/Article/details/gtdobzisbp.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gtkdliykqp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.c1oappe.top/Article/details/gtwaeupulz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.andypj.xyz/Article/details/gtysdjjrui.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.tanke756.top/Article/details/gtzhavobrg.html

TS:   // 手写 Map<string, number>
来源：http://dali.jiagoushi.top/Article/details/gtvnvhfysh.html

Java: // 手写 HashMap
来源：http://dali.chenlongwang.top/Article/details/gtwznoklrg.html

Go:   // 手写 map[int]int
来源：http://dali.cashguo.top/Article/details/gtiicuajwz.html

Ruby: // 手写 Hash
来源：http://dali.jyoumei.cn/Article/details/gtcvqccqob.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hammf.cn/Article/details/gtueqtgesu.html

[N08] 生成全排列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgralnavd.html

Py:   itertools.permutations(arr)
来源：http://dali.daria6918.cn/Article/details/gtpmfnsyby.html

PHP:  // 手写递归交换
来源：http://dali.redwolf501.top/Article/details/gtrtgjobum.html

JS:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gtijleczni.html

TS:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtttirdbyw.html

Java: // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gtlacmpgpx.html

Go:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtxsablmbq.html

Ruby: arr.permutation.to_a
来源：http://dali.nwbrower.top/Article/details/gtpnbrkjdm.html

C#:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtlltimhuf.html

[N09] 栈与队列
来源：http://dali.dashuyun.cn/Article/details/gtvdopbciv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkmuiegwq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gzhubu.top/Article/details/gtmofwuour.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nanxuanxn.top/Article/details/gtdjdadaiy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yongpay.top/Article/details/gtovxknolf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shangyingyoupin.top/Article/details/gtazpcfccx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.tianlin.xyz/Article/details/gthzdmwbvc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jlsjyb.cn/Article/details/gtnixxcofw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ydzc1.top/Article/details/gtyzzdugwg.html

[N10] 链表节点定义
来源：http://dali.zycfv.cn/Article/details/gtgrszccmr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhongyouzk.top/Article/details/gthupujbgw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhoulong.xyz/Article/details/gtwpkbtjnr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtriktppjm.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhengqikj.top/Article/details/gtiopauigj.html

Java: class Node { int v; Node next; }
来源：http://dali.ybcxt.top/Article/details/gtxqrlphso.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.fengsongda.top/Article/details/gtpgutqzmx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jinqigufen.top/Article/details/gtgcqorfml.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkusrubrf.html

[N11] 二叉树中序遍历
来源：http://dali.xylfe.cn/Article/details/gtjmebwxar.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yj202588.top/Article/details/gttcrpinoq.html

PHP:  // 手写递归函数
来源：http://dali.zdqjudy.top/Article/details/gtcmgjrrzd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.havefunace.top/Article/details/gthsmkokqj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.fzhhl.top/Article/details/gtjlqfrixf.html

Java: // 手写递归
来源：http://dali.dashuyun.cn/Article/details/gtgrzfhizs.html

Go:   // 手写递归
来源：http://dali.gaohongyu789.top/Article/details/gtbdsmxlng.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sweek.top/Article/details/gtcwuxkdyz.html

C#:   // 手写递归
来源：http://dali.guannengcc.top/Article/details/gtdfzsvkze.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.9152youxi.cn/Article/details/gtjkxzfbbg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.dashuyun.cn/Article/details/gtgmwvzkvn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.tanke756.top/Article/details/gtcgsojofe.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.birdmap.top/Article/details/gtzpeatsru.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangdashe.top/Article/details/gtnnjcdilo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hysaishi.cn/Article/details/gtrgpwkqww.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.daria6918.cn/Article/details/gtpdztgjxb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hysaishi.cn/Article/details/gtuhkxuavd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cucudq.cn/Article/details/gtiijjxrhj.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtfxczgref.html

O. 并发与异步
来源：http://dali.gaohongyu789.top/Article/details/gtdhqfkhgs.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtrudiozwg.html

[O01] 启动一个线程
来源：http://dali.gotoacloud.top/Article/details/gtepdjmclr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ydzc1.top/Article/details/gtdnpstflk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hammf.cn/Article/details/gtynsjfciv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinghuilouyu.cn/Article/details/gteqyekiyv.html

TS:   // 同 JS
来源：http://dali.c1oappe.top/Article/details/gtpolrlykm.html

Java: new Thread(() -> f()).start()
来源：http://dali.nanxuanxn.top/Article/details/gtnqkqdazl.html

Go:   go f()
来源：http://dali.havefunace.top/Article/details/gtrxcwoqkz.html

Ruby: Thread.new { f }
来源：http://dali.zhongyouzk.top/Article/details/gtgjpcmqkr.html

C#:   Task.Run(() => F());
来源：http://dali.meibo888.top/Article/details/gtjxdbsvds.html

[O02] 使用线程池
来源：http://dali.316326.xyz/Article/details/gtzngmoqih.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgreyatop.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.meibo888.top/Article/details/gtfkkzcfhf.html

JS:   // worker_threads 线程池
来源：http://dali.cucudq.cn/Article/details/gtcxtbionh.html

TS:   // worker_threads 线程池
来源：http://dali.yonumen.top/Article/details/gtbysmimwo.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.chenjidiqi.icu/Article/details/gtdegassbi.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbivtpvwl.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zdqjudy.top/Article/details/gtibyankvk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gogol.net.cn/Article/details/gtpeutylzd.html

[O03] 加锁保护共享数据
来源：http://dali.haohaochexian.top/Article/details/gtqjishjdn.html

Py:   with lock: shared += 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqsayvqpi.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hammf.cn/Article/details/gtxvbtacnz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.chenjidiqi.icu/Article/details/gtuhzfhgsk.html

TS:   // 同 JS
来源：http://dali.pengpengdd.cyou/Article/details/gtjliwsbas.html

Java: synchronized (this) { shared++; }
来源：http://dali.yj202588.top/Article/details/gtmgiccyho.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.chenlongwang.top/Article/details/gtnclrsvjp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.sweek.top/Article/details/gtjgluxoze.html

C#:   lock (gate) { shared++; }
来源：http://dali.wangshuangyany.cn/Article/details/gtzvsanrou.html

[O04] 定义异步函数并等待
来源：http://dali.yonumen.top/Article/details/gthrwmhybm.html

Py:   async def f():⏎    await g()
来源：http://dali.chenlongwang.top/Article/details/gtunxwhyxs.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cdnleiting.top/Article/details/gtrjjghwwt.html

JS:   async function f() { await g(); }
来源：http://dali.yvedp.cn/Article/details/gtmhtmslkk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.c1oappe.top/Article/details/gtxgafwaoj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.svipenyu.cn/Article/details/gtmiipbpsa.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xuanzx.com/Article/details/gtchpggbeh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yueranfly.top/Article/details/gtgqouyvst.html

C#:   async Task F() { await G(); }
来源：http://dali.hfpthk.cn/Article/details/gtvljqymeg.html

[O05] 并发执行并等待全部完成
来源：http://dali.jqgufenzy.top/Article/details/gtvheoutfr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.sweek.top/Article/details/gttegclqlx.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zycfv.cn/Article/details/gtmfrwqpyn.html

JS:   await Promise.all(tasks)
来源：http://dali.nanxuanxn.top/Article/details/gtlxtbicia.html

TS:   await Promise.all(tasks)
来源：http://dali.yuanzhike.top/Article/details/gtlopsgnsh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.birdmap.top/Article/details/gtglkocyon.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zycfv.cn/Article/details/gtdbgwhzla.html

Ruby: threads.map(&:join)
来源：http://dali.tianlin.xyz/Article/details/gtcpgaxmlj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zycfv.cn/Article/details/gtmzbiwnlv.html

[O06] 使用进程池
来源：http://dali.ppjwa.cn/Article/details/gtrcqfuenq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shanyushiyangtech.top/Article/details/gtvgdxivhz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.andypj.xyz/Article/details/gtqenqtrcl.html

JS:   // child_process / cluster 模块
来源：http://dali.cdnleiting.top/Article/details/gtwnocucpn.html

TS:   // child_process / cluster 模块
来源：http://dali.guowangkeji.top/Article/details/gtzxqzbotc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.pengpengdd.cyou/Article/details/gtalyjhwlo.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.vqdsnc.cn/Article/details/gttzqeuylv.html

Ruby: // fork 块
来源：http://dali.pengpengdd.cyou/Article/details/gtlmqdprgm.html

C#:   Parallel.For
来源：http://dali.vqdsnc.cn/Article/details/gthjphycax.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtzjyqmouy.html

P. 常用工具函数
来源：http://dali.bjfxy.top/Article/details/gtxggwzriw.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtmmajumid.html

[P01] 生成 UUID
来源：http://dali.gotoacloud.top/Article/details/gtqtbjwpeh.html

Py:   str(uuid.uuid4())
来源：http://dali.daria6918.cn/Article/details/gtiewtzkhm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ppjwa.cn/Article/details/gtohzhfjjs.html

JS:   crypto.randomUUID()
来源：http://dali.316326.xyz/Article/details/gtzzpktfav.html

TS:   crypto.randomUUID()
来源：http://dali.yonumen.top/Article/details/gtgjxijels.html

Java: UUID.randomUUID().toString()
来源：http://dali.meibo888.top/Article/details/gtllxdetrz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xziqi.cn/Article/details/gtqtjlkqee.html

Ruby: SecureRandom.uuid
来源：http://dali.hysaishi.cn/Article/details/gtgdbyjcgy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.nanxinkj.top/Article/details/gtndrzaagk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jianghu66.top/Article/details/gtnnaopisl.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shzxlz.cn/Article/details/gtugubviey.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtmcaacpde.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yuxming.cn/Article/details/gtzobjufmu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ydzc1.top/Article/details/gtcnkdnhop.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj202588.top/Article/details/gtfvdhsioj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shanyushiyangtech.top/Article/details/gtssyqyrai.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nanxinkj.top/Article/details/gtaoppsguv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.nanxinkj.top/Article/details/gtscflmhif.html

[P03] 生成短随机字符串
来源：http://dali.hfpthk.cn/Article/details/gtsnijuqsi.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jqgfzy.top/Article/details/gtauifiewk.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.feifeiyinyue.top/Article/details/gtjcuumpfn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuanzx.com/Article/details/gtowgzebba.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdfyvdgyi.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtcyogvjda.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.chenlongwang.top/Article/details/gtnmfjwjok.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xuetiantiany.cn/Article/details/gtiuxbabyd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinghuilouyu.cn/Article/details/gtdijonkjl.html

[P04] 求长度
来源：http://dali.aizwys.cn/Article/details/gtuodvgbar.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.vqdsnc.cn/Article/details/gtbzrdxhys.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gtzpvgplcx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yonumen.top/Article/details/gtrphuvcsy.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dashuyun.cn/Article/details/gtfgekhzkt.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ivvv.top/Article/details/gtyjppijvc.html

Go:   len(arr);  len(m)
来源：http://dali.316326.xyz/Article/details/gtlpnqbbzx.html

Ruby: x.length;  x.size
来源：http://dali.gzhubu.top/Article/details/gttuvajuxf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yuxming.cn/Article/details/gthadhyahj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.316326.xyz/Article/details/gtywnhbavj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sufxvd.cn/Article/details/gtyxxhmhix.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sysykeji.top/Article/details/gttcyealoz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.tian-w.cn/Article/details/gtfpjtlicl.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gzhubu.top/Article/details/gtvpjaekfy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.tanke756.top/Article/details/gtsbannzud.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgpntmgux.html

Ruby: a == b
来源：http://dali.hysaishi.cn/Article/details/gtlirfhiol.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.guannengcc.top/Article/details/gtrcccktcr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxysctrdg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.0kj1m.cn/Article/details/gtorukjcer.html

PHP:  if (empty($x)) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttxzsrqsl.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yuxming.cn/Article/details/gttkoffvqk.html

TS:   if (x == null) {}
来源：http://dali.hfpthk.cn/Article/details/gtgnpfgwcn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gzhubu.top/Article/details/gtoxkaiqee.html

Go:   if x == nil {}
来源：http://dali.hywenlv.cn/Article/details/gtmzwspokj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhixingplan.top/Article/details/gtlpvwqmkw.html

C#:   if (x is null) {}
来源：http://dali.sweek.top/Article/details/gtucsnrgrr.html

[P07] 防抖与节流
来源：http://dali.cashguo.top/Article/details/gtzomhmjcn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jinqigfzy.top/Article/details/gtclprujpe.html

PHP:  // 手写时间戳比较
来源：http://dali.sweek.top/Article/details/gtacrhhhvo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tian-w.cn/Article/details/gtluohrrrk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fengsongda.top/Article/details/gtllyxxtkw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jyoumei.cn/Article/details/gtgfcrbiur.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhixingplan.top/Article/details/gtqzqjxqlk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.aizwys.cn/Article/details/gtszxecasy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.c1oappe.top/Article/details/gtzcwffiad.html

[P08] 处理浮点精度问题
来源：http://dali.quarkkingdee.top/Article/details/gtwlwptqgk.html


<!-- 参考信息 -->