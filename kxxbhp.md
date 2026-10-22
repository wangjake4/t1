代发 wailian999

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2bgwamygh.html

[M01] 读取命令行参数
来源：http://dali.chenzaomai.com/Article/details/gt2adzcqiha.html

Py:   sys.argv[1:]
来源：http://dali.ybcxt.top/Article/details/gt2fkuxbqnb.html

PHP:  $argv;  $argc;
来源：http://dali.gotoacloud.top/Article/details/gt2hnmgkxxw.html

JS:   process.argv.slice(2)
来源：http://dali.andypj.xyz/Article/details/gt2fpprtqjz.html

TS:   process.argv.slice(2)
来源：http://dali.guowangkeji.top/Article/details/gt2bwsuozrs.html

Java: args 数组（main 方法参数）
来源：http://dali.yuanzhike.top/Article/details/gt2tiwdhuqj.html

Go:   os.Args[1:]
来源：http://dali.xuetiantiany.cn/Article/details/gt2wmzokqir.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2jclydpey.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cdnfhmxb.html

[M02] 读取环境变量
来源：http://dali.gzhubu.top/Article/details/gt2wawmcyas.html

Py:   os.environ.get("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gt2dcxnanuw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jiagoushi.top/Article/details/gt2ablwkmkv.html

JS:   process.env.HOME
来源：http://dali.haohaochexian.top/Article/details/gt2oavbrtbp.html

TS:   process.env.HOME
来源：http://dali.birdmap.top/Article/details/gt2xxldfgpn.html

Java: System.getenv("HOME")
来源：http://dali.pycfn.com/Article/details/gt2vxtgyuwd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.guannengcc.top/Article/details/gt2xdzogevr.html

Ruby: ENV["HOME"]
来源：http://dali.yvedp.cn/Article/details/gt2vmabrplg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sweek.top/Article/details/gt2oztvkwhv.html

[M03] 执行外部命令
来源：http://dali.cdnleiting.top/Article/details/gt2ztcdzmpl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.nanxinkj.top/Article/details/gt2staoiptw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jqgfzy.top/Article/details/gt2ujwsguly.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ucfhoghn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.birdmap.top/Article/details/gt2ueqtacox.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.9152youxi.cn/Article/details/gt2bcrbclwg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.aizwys.cn/Article/details/gt2sbdgglqh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rjeqwrws.html

C#:   Process.Start("ls", "-l");
来源：http://dali.smart0.xyz/Article/details/gt2imfhhgxl.html

[M04] 获取当前工作目录
来源：http://dali.xylfe.cn/Article/details/gt2wkrdypdz.html

Py:   os.getcwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2czaohhaq.html

PHP:  getcwd();
来源：http://dali.tian-w.cn/Article/details/gt2ywubmxeu.html

JS:   process.cwd()
来源：http://dali.zhiwuduotai.top/Article/details/gt2vtxlbzao.html

TS:   process.cwd()
来源：http://dali.jianghu66.top/Article/details/gt2avgnwvmp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.fengsongda.top/Article/details/gt2yqsbewnl.html

Go:   os.Getwd()
来源：http://dali.jyoumei.cn/Article/details/gt2vobgibbx.html

Ruby: Dir.pwd
来源：http://dali.ydzc1.top/Article/details/gt2uhniisop.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hfpthk.cn/Article/details/gt2tyweylct.html

[M05] 设置退出码
来源：http://dali.hysaishi.cn/Article/details/gt2pcdygglj.html

Py:   sys.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gt2wyyjgwkf.html

PHP:  exit(1);
来源：http://dali.hammf.cn/Article/details/gt2sqyjlgyh.html

JS:   process.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ahjgtcqs.html

TS:   process.exit(1)
来源：http://dali.yj20258.top/Article/details/gt2hfujmevp.html

Java: System.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gt2qgjfzxry.html

Go:   os.Exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2anhaawsi.html

Ruby: exit 1
来源：http://dali.snrcjt.cn/Article/details/gt2qjjgrmxr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zdqjudy.top/Article/details/gt2nzhhwlob.html

[M06] 向标准错误输出
来源：http://dali.redwolf501.top/Article/details/gt2bcdjxlej.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhoulong.xyz/Article/details/gt2sryvvtrb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.chenlongwang.top/Article/details/gt2vkngvfux.html

JS:   console.error("err")
来源：http://dali.ybcxt.top/Article/details/gt2lflxllrq.html

TS:   console.error("err")
来源：http://dali.shangyingyoupin.top/Article/details/gt2acwaxjew.html

Java: System.err.println("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cpnbhgiz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sufxvd.cn/Article/details/gt2ozdldedc.html

Ruby: warn "err"
来源：http://dali.mhx1999.top/Article/details/gt2nirkrqdl.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.daria6918.cn/Article/details/gt2thlipcms.html

[M07] 判断是否为主入口
来源：http://dali.xinyue.icu/Article/details/gt2ltywvpof.html

Py:   if __name__ == "__main__":
来源：http://dali.zdqjudy.top/Article/details/gt2nntklsah.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.snrcjt.cn/Article/details/gt2vylgowlc.html

JS:   require.main === module
来源：http://dali.quarkkingdee.top/Article/details/gt2duxcsmgr.html

TS:   require.main === module
来源：http://dali.jqgufenzy.top/Article/details/gt2mtujfzst.html

Java: public static void main(String[] args)
来源：http://dali.yueranfly.top/Article/details/gt2pnnlwamq.html

Go:   func main()
来源：http://dali.ivvv.top/Article/details/gt2mdxzplel.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.daxiang520.top/Article/details/gt2cdypblum.html

C#:   static void Main(string[] args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ufqnjani.html

[M08] 获取系统与运行时信息
来源：http://dali.jlsjyb.cn/Article/details/gt2ecdaanaw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cdnleiting.top/Article/details/gt2uxwwwyli.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gzhubu.top/Article/details/gt2cdrdsjnx.html

JS:   process.platform;  process.version
来源：http://dali.ydzc1.top/Article/details/gt2kpsgcokj.html

TS:   process.platform;  process.version
来源：http://dali.jlsjyb.cn/Article/details/gt2wylvqrxb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.birdmap.top/Article/details/gt2bhdsdgyx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.tian-w.cn/Article/details/gt2uqltogux.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.wangdashe.top/Article/details/gt2fdfppxfd.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tian-w.cn/Article/details/gt2kylxoqgq.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2okmsiyxb.html

N. 数据结构与算法
来源：http://dali.9152youxi.cn/Article/details/gt2lbaoptnf.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2vuutjvex.html

[N01] 二分查找（有序数组）
来源：http://dali.gaohongyu789.top/Article/details/gt2uogrgfky.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2izervkqt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinqigfzy.top/Article/details/gt2pickhzwf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenlongwang.top/Article/details/gt2sliqogrf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gt2kcmtdztg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.wangdashe.top/Article/details/gt2mspelnkk.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gt2wugebwqz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2waqgoizx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2oolwyqpq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.meibo888.top/Article/details/gt2fadxchwu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sweek.top/Article/details/gt2jyairhfv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.haohaochexian.top/Article/details/gt2qziqexhg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pycfn.com/Article/details/gt2rulllygu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhongyouzk.top/Article/details/gt2sgjwnqby.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.aizwys.cn/Article/details/gt2onssacnh.html

Go:   slices.Sort(arr)
来源：http://dali.nwbrower.top/Article/details/gt2tlkpunqm.html

Ruby: arr.sort
来源：http://dali.daxiang520.top/Article/details/gt2kfwueacw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hammf.cn/Article/details/gt2jrsvfwol.html

[N03] 快速排序（分治示例）
来源：http://dali.redwolf501.top/Article/details/gt2sbflsjjs.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhixingplan.top/Article/details/gt2whnhqndx.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yj20258.top/Article/details/gt2kcldtuet.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jianghu66.top/Article/details/gt2kumjambq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.svipenyu.cn/Article/details/gt2izolnime.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jyoumei.cn/Article/details/gt2foloullc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.daxiang520.top/Article/details/gt2vrzfooyl.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hnqzz.top/Article/details/gt2wfvcrlmz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jianghu66.top/Article/details/gt2tigdzdni.html

[N04] 斐波那契数列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2widqddsa.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2oqmkfjma.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zycfv.cn/Article/details/gt2zuclbqgw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gt2gmhookla.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gt2metthiiu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.mhx1999.top/Article/details/gt2kpoblyxm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ydzc1.top/Article/details/gt2pqgzjauh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.svipenyu.cn/Article/details/gt2fmhqjovp.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhiwuduotai.top/Article/details/gt2gbuhydur.html

[N05] 最大公约数
来源：http://dali.zhixingplan.top/Article/details/gt2qitqxvcl.html

Py:   math.gcd(a, b)
来源：http://dali.zycfv.cn/Article/details/gt2xgikwzur.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2tfubkoys.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hammf.cn/Article/details/gt2gulrofdm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guowangkeji.top/Article/details/gt2mluwccgj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yueranfly.top/Article/details/gt2ebpgigwg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhoulong.xyz/Article/details/gt2zpmtxxpv.html

Ruby: a.gcd(b)
来源：http://dali.nanxuanxn.top/Article/details/gt2skjxshia.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jlsjyb.cn/Article/details/gt2cngjoaos.html

[N06] 判断回文字符串
来源：http://dali.yuxming.cn/Article/details/gt2aocvpuje.html

Py:   s == s[::-1]
来源：http://dali.yvedp.cn/Article/details/gt2wpvedupj.html

PHP:  $s === strrev($s);
来源：http://dali.guowangkeji.top/Article/details/gt2ttlhsnyq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gt2tycbulrs.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ixwwzqwh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jyoumei.cn/Article/details/gt2dtzvoalp.html

Go:   // 双指针从两端比较
来源：http://dali.wangshuangyany.cn/Article/details/gt2rafthsjk.html

Ruby: s == s.reverse
来源：http://dali.chenlongwang.top/Article/details/gt2mzurckwu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shuidangran.top/Article/details/gt2repzyhxh.html

[N07] 两数之和（返回下标）
来源：http://dali.sysykeji.top/Article/details/gt2jhddtpue.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yueranfly.top/Article/details/gt2zjwdnfzv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.9152youxi.cn/Article/details/gt2lyqkrogd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rifbkxha.html

TS:   // 手写 Map<string, number>
来源：http://dali.cashguo.top/Article/details/gt2dtxuwklf.html

Java: // 手写 HashMap
来源：http://dali.tian-w.cn/Article/details/gt2yxvlaogu.html

Go:   // 手写 map[int]int
来源：http://dali.dashuyun.cn/Article/details/gt2kfimvfhz.html

Ruby: // 手写 Hash
来源：http://dali.xziqi.cn/Article/details/gt2vafnajli.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.aizwys.cn/Article/details/gt2uhbiuxes.html

[N08] 生成全排列
来源：http://dali.redwolf501.top/Article/details/gt2nthkltex.html

Py:   itertools.permutations(arr)
来源：http://dali.cheryme.top/Article/details/gt2whrixvjo.html

PHP:  // 手写递归交换
来源：http://dali.gogol.net.cn/Article/details/gt2fydpyrfx.html

JS:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gt2xnwxbrto.html

TS:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gt2kckypjmj.html

Java: // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dozdhswr.html

Go:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gt2dbbvnhha.html

Ruby: arr.permutation.to_a
来源：http://dali.vqdsnc.cn/Article/details/gt2jxgvkqub.html

C#:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gt2sjixfjuj.html

[N09] 栈与队列
来源：http://dali.jqgufenzy.top/Article/details/gt2mdqthzvf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.wangdashe.top/Article/details/gt2dzdjiytk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.nanxuanxn.top/Article/details/gt2ldalusny.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xinyue.icu/Article/details/gt2djmcthkh.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yonumen.top/Article/details/gt2vrsvufim.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yuanzhike.top/Article/details/gt2boichttm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sweek.top/Article/details/gt2zoohundu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gt2ijljyxmy.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hnqzz.top/Article/details/gt2vnpzgltp.html

[N10] 链表节点定义
来源：http://dali.chenlongwang.top/Article/details/gt2usvzcckg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ehwqpu.com/Article/details/gt2nupujiae.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zycfv.cn/Article/details/gt2bwqcgpzs.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.guannengcc.top/Article/details/gt2rmexrnje.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shzxlz.cn/Article/details/gt2yobfczsb.html

Java: class Node { int v; Node next; }
来源：http://dali.sufxvd.cn/Article/details/gt2vwraodjr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.vqdsnc.cn/Article/details/gt2sfxkbfpb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jlsjyb.cn/Article/details/gt2zcqtauur.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yongpay.top/Article/details/gt2tnozthnz.html

[N11] 二叉树中序遍历
来源：http://dali.yj20258.top/Article/details/gt2xasylrct.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.daria6918.cn/Article/details/gt2hdeusoxl.html

PHP:  // 手写递归函数
来源：http://dali.vqdsnc.cn/Article/details/gt2msupsqro.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gogol.net.cn/Article/details/gt2rvmuscsn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daria6918.cn/Article/details/gt2ydrbajxu.html

Java: // 手写递归
来源：http://dali.yj202588.top/Article/details/gt2encpnhxu.html

Go:   // 手写递归
来源：http://dali.mhx1999.top/Article/details/gt2bclagnhn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhixingplan.top/Article/details/gt2gqylpffl.html

C#:   // 手写递归
来源：http://dali.zhixingplan.top/Article/details/gt2wdsvhugx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hysaishi.cn/Article/details/gt2sfpuhjmj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aiimmcxy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.aizwys.cn/Article/details/gt2thpxlgba.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dianchejie.cn/Article/details/gt2dskiebnr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jlsjyb.cn/Article/details/gt2zuhxvwca.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cucudq.cn/Article/details/gt2fwqdkvvz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jyoumei.cn/Article/details/gt2gjwjawis.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.iojbl.cn/Article/details/gt2qxctlhga.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yueranfly.top/Article/details/gt2gnwvkqvq.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2vphugojm.html

O. 并发与异步
来源：http://dali.cdnleiting.top/Article/details/gt2obsgmezp.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2htzypwtx.html

[O01] 启动一个线程
来源：http://dali.yuxming.cn/Article/details/gt2blfqkstc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.snrcjt.cn/Article/details/gt2lqwmuhxt.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.svipenyu.cn/Article/details/gt2wsvhkhzl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gogol.net.cn/Article/details/gt2lbqspwur.html

TS:   // 同 JS
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qqmowdaz.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhoulong.xyz/Article/details/gt2rcvofhjt.html

Go:   go f()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dcvkqcko.html

Ruby: Thread.new { f }
来源：http://dali.yj20258888.top/Article/details/gt2koojhsqw.html

C#:   Task.Run(() => F());
来源：http://dali.chenzaomai.com/Article/details/gt2iytlyhzx.html

[O02] 使用线程池
来源：http://dali.meibo888.top/Article/details/gt2njulnoma.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hnqzz.top/Article/details/gt2aokcdjys.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sufxvd.cn/Article/details/gt2avudsqxg.html

JS:   // worker_threads 线程池
来源：http://dali.zhiwuduotai.top/Article/details/gt2elshoqzu.html

TS:   // worker_threads 线程池
来源：http://dali.hfpthk.cn/Article/details/gt2yctytmeq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ppjwa.cn/Article/details/gt2ylexkpix.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lhmputxe.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2elpcricc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhixingplan.top/Article/details/gt2lltdhwvs.html

[O03] 加锁保护共享数据
来源：http://dali.cqqwz.cn/Article/details/gt2vschopds.html

Py:   with lock: shared += 1
来源：http://dali.yj202588.top/Article/details/gt2uqdegxpf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nxjhizvd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.nanxinkj.top/Article/details/gt2dkdwjsgv.html

TS:   // 同 JS
来源：http://dali.zhoulong.xyz/Article/details/gt2eqauzpos.html

Java: synchronized (this) { shared++; }
来源：http://dali.0kj1m.cn/Article/details/gt2wfblneia.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yuanzhike.top/Article/details/gt2ivmplaam.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.chenjidiqi.icu/Article/details/gt2erewjncg.html

C#:   lock (gate) { shared++; }
来源：http://dali.hnxiangtu.top/Article/details/gt2dmdokgzv.html

[O04] 定义异步函数并等待
来源：http://dali.cdnleiting.top/Article/details/gt2ixqsiedv.html

Py:   async def f():⏎    await g()
来源：http://dali.9152youxi.cn/Article/details/gt2dqthohks.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinghuilouyu.cn/Article/details/gt2evrpbcbf.html

JS:   async function f() { await g(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2soejjcno.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.redwolf501.top/Article/details/gt2tuweuagi.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfctzqc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cucudq.cn/Article/details/gt2hgbkqacx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinqigfzy.top/Article/details/gt2lwozmukt.html

C#:   async Task F() { await G(); }
来源：http://dali.svipenyu.cn/Article/details/gt2kwyeidxy.html

[O05] 并发执行并等待全部完成
来源：http://dali.chenjidiqi.icu/Article/details/gt2hwolapym.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gtjzcvpv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.tanke756.top/Article/details/gt2hecfaqqi.html

JS:   await Promise.all(tasks)
来源：http://dali.hysaishi.cn/Article/details/gt2wqialfax.html

TS:   await Promise.all(tasks)
来源：http://dali.bjfxy.top/Article/details/gt2cfjzxqqj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iofwkoar.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.chenlongwang.top/Article/details/gt2yolwmelv.html

Ruby: threads.map(&:join)
来源：http://dali.nwbrower.top/Article/details/gt2hkagswyf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.havefunace.top/Article/details/gt2lekjisyh.html

[O06] 使用进程池
来源：http://dali.nanxinkj.top/Article/details/gt2ytqcvayu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.316326.xyz/Article/details/gt2rcgkxhdi.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.chenlongwang.top/Article/details/gt2gfqboqwg.html

JS:   // child_process / cluster 模块
来源：http://dali.jianghu66.top/Article/details/gt2uybwfrdf.html

TS:   // child_process / cluster 模块
来源：http://dali.daria6918.cn/Article/details/gt2cxmnabiq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhixingplan.top/Article/details/gt2xoauabot.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.meibo888.top/Article/details/gt2hulplzox.html

Ruby: // fork 块
来源：http://dali.yvedp.cn/Article/details/gt2atfqvkid.html

C#:   Parallel.For
来源：http://dali.hysaishi.cn/Article/details/gt2mkxqgixw.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2uimwkdtw.html

P. 常用工具函数
来源：http://dali.xylfe.cn/Article/details/gt2vgdimksq.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2tjjrtjjr.html

[P01] 生成 UUID
来源：http://dali.cdnleiting.top/Article/details/gt2anlcwpok.html

Py:   str(uuid.uuid4())
来源：http://dali.nanxuanxn.top/Article/details/gt2jbreikix.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jyoumei.cn/Article/details/gt2bwzdttra.html

JS:   crypto.randomUUID()
来源：http://dali.aibaodan.cn/Article/details/gt2ejqiscev.html

TS:   crypto.randomUUID()
来源：http://dali.zhoulong.xyz/Article/details/gt2mplivvem.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinqigufen.top/Article/details/gt2pbadtixg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jqgufenzy.top/Article/details/gt2jlupkrzm.html

Ruby: SecureRandom.uuid
来源：http://dali.xuanzx.com/Article/details/gt2plmchner.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.nwbrower.top/Article/details/gt2ouzsjlmb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ydzc1.top/Article/details/gt2epqdtswy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.316326.xyz/Article/details/gt2awykcusi.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xuanzx.com/Article/details/gt2dkdzqrjm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yj20258888.top/Article/details/gt2icbhqmhn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jianghu66.top/Article/details/gt2wtkbdhkr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ybcxt.top/Article/details/gt2laiqbiuq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jlsjyb.cn/Article/details/gt2mlkibnca.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sysykeji.top/Article/details/gt2rhohbpow.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yj20258888.top/Article/details/gt2wslmfbjr.html

[P03] 生成短随机字符串
来源：http://dali.smart0.xyz/Article/details/gt2xcnrfuzm.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.daria6918.cn/Article/details/gt2icuorepg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kgqjzodo.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yuanzhike.top/Article/details/gt2wwhandee.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.wangdashe.top/Article/details/gt2rkezezqm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.haohaochexian.top/Article/details/gt2zfajfska.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhiwuduotai.top/Article/details/gt2auwbwamc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.svipenyu.cn/Article/details/gt2xbgwfmxb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.nanxinkj.top/Article/details/gt2lnltmdgc.html

[P04] 求长度
来源：http://dali.yongpay.top/Article/details/gt2qcgcrdkd.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.iojbl.cn/Article/details/gt2nycruiwf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shangyingyoupin.top/Article/details/gt2favlovvj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.daria6918.cn/Article/details/gt2rvnnkdrb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.quarkkingdee.top/Article/details/gt2tpbmnxbt.html

Java: list.size();  map.size();  s.length()
来源：http://dali.daxiang520.top/Article/details/gt2feardxuw.html

Go:   len(arr);  len(m)
来源：http://dali.meibo888.top/Article/details/gt2vxtgtoms.html

Ruby: x.length;  x.size
来源：http://dali.svipenyu.cn/Article/details/gt2ivrgefhf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.fengsongda.top/Article/details/gt2arvggrco.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xinyue.icu/Article/details/gt2iddkppjx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shangyingyoupin.top/Article/details/gt2efiiswgj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jyoumei.cn/Article/details/gt2oloorfiw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.9152youxi.cn/Article/details/gt2inykebah.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenzaomai.com/Article/details/gt2vkrzkave.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.vqdsnc.cn/Article/details/gt2mppilyhv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.daxiang520.top/Article/details/gt2siasgywa.html

Ruby: a == b
来源：http://dali.svipenyu.cn/Article/details/gt2zxdoofrq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhixingplan.top/Article/details/gt2uqkdnsdj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jlsjyb.cn/Article/details/gt2znmztxgw.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.pengpengdd.cyou/Article/details/gt2loxquggy.html

PHP:  if (empty($x)) {}
来源：http://dali.yvedp.cn/Article/details/gt2vzcryhdi.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.wangshuangyany.cn/Article/details/gt2nhhdzshy.html

TS:   if (x == null) {}
来源：http://dali.redwolf501.top/Article/details/gt2ltxrwkik.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hysaishi.cn/Article/details/gt2ooqvqtyb.html

Go:   if x == nil {}
来源：http://dali.tianlin.xyz/Article/details/gt2dfzopsop.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cucudq.cn/Article/details/gt2xbxqmtao.html

C#:   if (x is null) {}
来源：http://dali.jyoumei.cn/Article/details/gt2hjrcckjn.html

[P07] 防抖与节流
来源：http://dali.xinyue.icu/Article/details/gt2otwcxtmm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xuetiantiany.cn/Article/details/gt2uaucmnfa.html


<!-- 参考信息 -->