代发 wailian999

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yj20258.top/Article/details/gt2kgdtmxet.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.aizwys.cn/Article/details/gt2zorlomtf.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2odzyrefz.html

M. 命令行 / 进程 / 环境
来源：http://dali.quarkkingdee.top/Article/details/gt2qeurypil.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2gfmiswjk.html

[M01] 读取命令行参数
来源：http://dali.jiagoushi.top/Article/details/gt2bgjzcgrx.html

Py:   sys.argv[1:]
来源：http://dali.mhx1999.top/Article/details/gt2pdghxjjd.html

PHP:  $argv;  $argc;
来源：http://dali.cashguo.top/Article/details/gt2tgezkysz.html

JS:   process.argv.slice(2)
来源：http://dali.yj202588.top/Article/details/gt2ltbogzno.html

TS:   process.argv.slice(2)
来源：http://dali.316326.xyz/Article/details/gt2sdzinjir.html

Java: args 数组（main 方法参数）
来源：http://dali.bjfxy.top/Article/details/gt2mhjxhqxo.html

Go:   os.Args[1:]
来源：http://dali.hfpthk.cn/Article/details/gt2rzxwbduw.html

Ruby: ARGV
来源：http://dali.tianlin.xyz/Article/details/gt2ufysufpe.html

C#:   args 数组（Main 方法参数）
来源：http://dali.snrcjt.cn/Article/details/gt2jmlkbwym.html

[M02] 读取环境变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2gsdkdhpg.html

Py:   os.environ.get("HOME")
来源：http://dali.c1oappe.top/Article/details/gt2vhbxypqf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.haohaochexian.top/Article/details/gt2dmrstiio.html

JS:   process.env.HOME
来源：http://dali.sufxvd.cn/Article/details/gt2piizcgmr.html

TS:   process.env.HOME
来源：http://dali.chenjidiqi.icu/Article/details/gt2xfhlgqds.html

Java: System.getenv("HOME")
来源：http://dali.yangfankeji.com/Article/details/gt2rxvxwuwj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.fzhhl.top/Article/details/gt2memiixal.html

Ruby: ENV["HOME"]
来源：http://dali.jinqigufen.top/Article/details/gt2vsowldlq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dzwaphpc.html

[M03] 执行外部命令
来源：http://dali.fzhhl.top/Article/details/gt2wyakdvtu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yueranfly.top/Article/details/gt2wczshrgl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hysaishi.cn/Article/details/gt2vwiofyiw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hammf.cn/Article/details/gt2yyxjcssd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangshuangyany.cn/Article/details/gt2xbgzmfhj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zdqjudy.top/Article/details/gt2sswvovlq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xuetiantiany.cn/Article/details/gt2vrrykgkf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.haohaochexian.top/Article/details/gt2ogoutvvh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hfpthk.cn/Article/details/gt2cyhzdyci.html

[M04] 获取当前工作目录
来源：http://dali.pengpengdd.cyou/Article/details/gt2uqyqxnjt.html

Py:   os.getcwd()
来源：http://dali.cheryme.top/Article/details/gt2vylegmnv.html

PHP:  getcwd();
来源：http://dali.hnxiangtu.top/Article/details/gt2ytxtyyhd.html

JS:   process.cwd()
来源：http://dali.yuxming.cn/Article/details/gt2faxoslzn.html

TS:   process.cwd()
来源：http://dali.9152youxi.cn/Article/details/gt2tcndnnos.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yanxiufei.cn/Article/details/gt2axbjluug.html

Go:   os.Getwd()
来源：http://dali.jlsjyb.cn/Article/details/gt2voqzzeub.html

Ruby: Dir.pwd
来源：http://dali.zdqjudy.top/Article/details/gt2fcqvyfzl.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nwbrower.top/Article/details/gt2ekhmxcsd.html

[M05] 设置退出码
来源：http://dali.gzhubu.top/Article/details/gt2wyxpkxtj.html

Py:   sys.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gt2gflmwkuz.html

PHP:  exit(1);
来源：http://dali.cheryme.top/Article/details/gt2cprkahmb.html

JS:   process.exit(1)
来源：http://dali.nwbrower.top/Article/details/gt2jzxenngx.html

TS:   process.exit(1)
来源：http://dali.yj202588.top/Article/details/gt2txmuivgv.html

Java: System.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2pcazohix.html

Go:   os.Exit(1)
来源：http://dali.sufxvd.cn/Article/details/gt2zdxbjgpl.html

Ruby: exit 1
来源：http://dali.jlsjyb.cn/Article/details/gt2yhobocfr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2fokptwcm.html

[M06] 向标准错误输出
来源：http://dali.hnqzz.top/Article/details/gt2qntyoygd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.andypj.xyz/Article/details/gt2bhlgajxi.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hfpthk.cn/Article/details/gt2dyfxglua.html

JS:   console.error("err")
来源：http://dali.yj20258.top/Article/details/gt2mjkddutx.html

TS:   console.error("err")
来源：http://dali.sweek.top/Article/details/gt2ogwhnxax.html

Java: System.err.println("err")
来源：http://dali.birdmap.top/Article/details/gt2ayfxgdch.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.pycfn.com/Article/details/gt2ugjzvrug.html

Ruby: warn "err"
来源：http://dali.sweek.top/Article/details/gt2jrayfldn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gotoacloud.top/Article/details/gt2qdnriugp.html

[M07] 判断是否为主入口
来源：http://dali.ybcxt.top/Article/details/gt2dlylrecv.html

Py:   if __name__ == "__main__":
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dzwjajzp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cdnleiting.top/Article/details/gt2pmpovgmp.html

JS:   require.main === module
来源：http://dali.feifeiyinyue.top/Article/details/gt2afylqqma.html

TS:   require.main === module
来源：http://dali.jiagoushi.top/Article/details/gt2fkholphk.html

Java: public static void main(String[] args)
来源：http://dali.tian-w.cn/Article/details/gt2stnweygy.html

Go:   func main()
来源：http://dali.cashguo.top/Article/details/gt2gaxqkcnj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.fengsongda.top/Article/details/gt2zaygrehr.html

C#:   static void Main(string[] args)
来源：http://dali.mhx1999.top/Article/details/gt2uccebims.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2yyaixylw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gotoacloud.top/Article/details/gt2edhzcmfj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.smart0.xyz/Article/details/gt2znvsdihe.html

JS:   process.platform;  process.version
来源：http://dali.zhongyouzk.top/Article/details/gt2fjamwmut.html

TS:   process.platform;  process.version
来源：http://dali.chenzaomai.com/Article/details/gt2fnksunhu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.9152youxi.cn/Article/details/gt2oqyycgww.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ppjwa.cn/Article/details/gt2ucwjduym.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yongpay.top/Article/details/gt2rpizekgs.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.smart0.xyz/Article/details/gt2ppjevnzs.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2ytwnuxqf.html

N. 数据结构与算法
来源：http://dali.kuanghao11.cn/Article/details/gt2riczrjhu.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rooexerf.html

[N01] 二分查找（有序数组）
来源：http://dali.hammf.cn/Article/details/gt2hckkmixh.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gt2ciyvugps.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yvedp.cn/Article/details/gt2padtkwhe.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nwbrower.top/Article/details/gt2htiltbbo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cucudq.cn/Article/details/gt2rrdjplgv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.guannengcc.top/Article/details/gt2pwrtwelq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.c1oappe.top/Article/details/gt2xjcgywpt.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yongpay.top/Article/details/gt2gphuhtvk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gt2jszxbawk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yuxming.cn/Article/details/gt2copasdzc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gzhubu.top/Article/details/gt2xemmedqf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.snrcjt.cn/Article/details/gt2uietvmph.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2azdbxrly.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.meibo888.top/Article/details/gt2ghjepsto.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sysykeji.top/Article/details/gt2fbrupnnj.html

Go:   slices.Sort(arr)
来源：http://dali.iojbl.cn/Article/details/gt2xnpwdong.html

Ruby: arr.sort
来源：http://dali.quarkkingdee.top/Article/details/gt2fvimithx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.daria6918.cn/Article/details/gt2aopxelun.html

[N03] 快速排序（分治示例）
来源：http://dali.shuidangran.top/Article/details/gt2oovvzyrj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cashguo.top/Article/details/gt2raateivg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dtrgfolb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hysaishi.cn/Article/details/gt2yftmvzsg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.meibo888.top/Article/details/gt2asoibupd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jqgufenzy.top/Article/details/gt2creqrxoi.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gfnfrdmj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.dashuyun.cn/Article/details/gt2zhxfcjxb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jlsjyb.cn/Article/details/gt2vdllabbm.html

[N04] 斐波那契数列
来源：http://dali.cucudq.cn/Article/details/gt2ttqfasfo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.svipenyu.cn/Article/details/gt2assqpdiy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhengqikj.top/Article/details/gt2uaamhdbw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jlsjyb.cn/Article/details/gt2rcwrzwsi.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fiaecnue.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cucudq.cn/Article/details/gt2nnknpyph.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aoqeqqmn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhixingplan.top/Article/details/gt2krsulftv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.tanke756.top/Article/details/gt2umupdaxw.html

[N05] 最大公约数
来源：http://dali.hnxiangtu.top/Article/details/gt2rjbyolcc.html

Py:   math.gcd(a, b)
来源：http://dali.ydzc1.top/Article/details/gt2xktybysl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sufxvd.cn/Article/details/gt2bnuuvsqs.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.havefunace.top/Article/details/gt2lcqobqxz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yongpay.top/Article/details/gt2rcgilwhz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.redwolf501.top/Article/details/gt2bmsdogeu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hnqzz.top/Article/details/gt2negkaatq.html

Ruby: a.gcd(b)
来源：http://dali.yj20258.top/Article/details/gt2yifacoxe.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.bjfxy.top/Article/details/gt2igcxhnnc.html

[N06] 判断回文字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2kqjzowes.html

Py:   s == s[::-1]
来源：http://dali.pengpengdd.cyou/Article/details/gt2maprdudl.html

PHP:  $s === strrev($s);
来源：http://dali.nwbrower.top/Article/details/gt2qagacmfw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gt2vctgrupx.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2npjjsnpy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sufxvd.cn/Article/details/gt2rxxptojb.html

Go:   // 双指针从两端比较
来源：http://dali.cqqwz.cn/Article/details/gt2npztminn.html

Ruby: s == s.reverse
来源：http://dali.cashguo.top/Article/details/gt2obenbsng.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.quarkkingdee.top/Article/details/gt2vckblzuw.html

[N07] 两数之和（返回下标）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2esorlqes.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hnxiangtu.top/Article/details/gt2gpslxtua.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2shwyyihp.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cqqwz.cn/Article/details/gt2fzlmddso.html

TS:   // 手写 Map<string, number>
来源：http://dali.dashuyun.cn/Article/details/gt2guneazwj.html

Java: // 手写 HashMap
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tolyizvz.html

Go:   // 手写 map[int]int
来源：http://dali.xziqi.cn/Article/details/gt2umrjohqs.html

Ruby: // 手写 Hash
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2khsqazst.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iqisaqhp.html

[N08] 生成全排列
来源：http://dali.zdqjudy.top/Article/details/gt2btnuvbfv.html

Py:   itertools.permutations(arr)
来源：http://dali.ydzc1.top/Article/details/gt2wvkjiouv.html

PHP:  // 手写递归交换
来源：http://dali.zhixingplan.top/Article/details/gt2wweqtgku.html

JS:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gt2oixcrfuq.html

TS:   // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gt2xjzxqyga.html

Java: // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gt2epejvvtj.html

Go:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gt2fadevray.html

Ruby: arr.permutation.to_a
来源：http://dali.zhiwuduotai.top/Article/details/gt2krgilcvg.html

C#:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gt2xhlzzhps.html

[N09] 栈与队列
来源：http://dali.tian-w.cn/Article/details/gt2ztarhvjl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.fengsongda.top/Article/details/gt2ujfxkdcz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yueranfly.top/Article/details/gt2evdxdlhv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhixingplan.top/Article/details/gt2gxhfyzud.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xuetiantiany.cn/Article/details/gt2jhkjmdjg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qisvromf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinqigufen.top/Article/details/gt2bkdyezuy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.smart0.xyz/Article/details/gt2fiyirhgx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yongpay.top/Article/details/gt2ejnqcltr.html

[N10] 链表节点定义
来源：http://dali.xziqi.cn/Article/details/gt2oteljjeb.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shzxlz.cn/Article/details/gt2afaseujh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yj202588.top/Article/details/gt2wvdfimuh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.0kj1m.cn/Article/details/gt2ehrzxasq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.smart0.xyz/Article/details/gt2idkuuvcu.html

Java: class Node { int v; Node next; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fjsuvhhm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gzhubu.top/Article/details/gt2snrmejqy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xuanzx.com/Article/details/gt2nvyiepam.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.vqdsnc.cn/Article/details/gt2lhvqezfj.html

[N11] 二叉树中序遍历
来源：http://dali.fengsongda.top/Article/details/gt2yxbqdxmf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shangyingyoupin.top/Article/details/gt2owvzyzjc.html

PHP:  // 手写递归函数
来源：http://dali.cqqwz.cn/Article/details/gt2rqdbhyhv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xziqi.cn/Article/details/gt2mbdydpaq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.0kj1m.cn/Article/details/gt2jiieuzkb.html

Java: // 手写递归
来源：http://dali.hysaishi.cn/Article/details/gt2pireatak.html

Go:   // 手写递归
来源：http://dali.ybcxt.top/Article/details/gt2wgvatdht.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yongpay.top/Article/details/gt2ktmndmvw.html

C#:   // 手写递归
来源：http://dali.ydzc1.top/Article/details/gt2xrfrmcus.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hammf.cn/Article/details/gt2hhqnoxxt.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ephermye.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhoulong.xyz/Article/details/gt2hrcgjmrv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxinkj.top/Article/details/gt2nnvozmdw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.pengpengdd.cyou/Article/details/gt2czcllwsl.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cheryme.top/Article/details/gt2hvcmmdwf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yonumen.top/Article/details/gt2odgvbyjt.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yuxming.cn/Article/details/gt2ksckvllb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.wangdashe.top/Article/details/gt2nqjtxvfm.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2aqvmyyhk.html

O. 并发与异步
来源：http://dali.xziqi.cn/Article/details/gt2wnnfynjc.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2jegeewfr.html

[O01] 启动一个线程
来源：http://dali.sxryk.cn/Article/details/gt2zprvspld.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenlongwang.top/Article/details/gt2wigjhfdl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.feifeiyinyue.top/Article/details/gt2cdwelmnl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hnqzz.top/Article/details/gt2dkpmjotm.html

TS:   // 同 JS
来源：http://dali.hnxiangtu.top/Article/details/gt2yflsoqtr.html

Java: new Thread(() -> f()).start()
来源：http://dali.yvedp.cn/Article/details/gt2grkeduip.html

Go:   go f()
来源：http://dali.vqdsnc.cn/Article/details/gt2pkgciglm.html

Ruby: Thread.new { f }
来源：http://dali.guowangkeji.top/Article/details/gt2gdbdlgkg.html

C#:   Task.Run(() => F());
来源：http://dali.cucudq.cn/Article/details/gt2rvmoarpo.html

[O02] 使用线程池
来源：http://dali.jianghu66.top/Article/details/gt2szwhuodd.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.redwolf501.top/Article/details/gt2dylcgkth.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhongyouzk.top/Article/details/gt2bkmvvzcq.html

JS:   // worker_threads 线程池
来源：http://dali.ybcxt.top/Article/details/gt2bmeikwzv.html

TS:   // worker_threads 线程池
来源：http://dali.zdqjudy.top/Article/details/gt2jxazqbtq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.tian-w.cn/Article/details/gt2oilokthq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cqqwz.cn/Article/details/gt2qxkengsz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gzhubu.top/Article/details/gt2iozniyxb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ppjwa.cn/Article/details/gt2kcdpzymm.html

[O03] 加锁保护共享数据
来源：http://dali.nanxuanxn.top/Article/details/gt2rwpcdbkd.html

Py:   with lock: shared += 1
来源：http://dali.sweek.top/Article/details/gt2pgygujdz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jinqigfzy.top/Article/details/gt2mpzeamxd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.sxryk.cn/Article/details/gt2jndjmbwe.html

TS:   // 同 JS
来源：http://dali.cdnleiting.top/Article/details/gt2thlxxpnt.html

Java: synchronized (this) { shared++; }
来源：http://dali.cqqwz.cn/Article/details/gt2qfgaoeil.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.svipenyu.cn/Article/details/gt2owqdqyrw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.andypj.xyz/Article/details/gt2nzphepez.html

C#:   lock (gate) { shared++; }
来源：http://dali.yj20258.top/Article/details/gt2wvagvivo.html

[O04] 定义异步函数并等待
来源：http://dali.dashuyun.cn/Article/details/gt2ymwyficx.html

Py:   async def f():⏎    await g()
来源：http://dali.ehwqpu.com/Article/details/gt2glhwjung.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shanyushiyangtech.top/Article/details/gt2axjncpco.html

JS:   async function f() { await g(); }
来源：http://dali.c1oappe.top/Article/details/gt2mvvkjgbh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.tian-w.cn/Article/details/gt2gmbfycgp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xvigpeaq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jlsjyb.cn/Article/details/gt2qzumwuqd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shangyingyoupin.top/Article/details/gt2jzhwerqo.html

C#:   async Task F() { await G(); }
来源：http://dali.daxiang520.top/Article/details/gt2akbtgbmq.html

[O05] 并发执行并等待全部完成
来源：http://dali.jiagoushi.top/Article/details/gt2jvuvaqqb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.daria6918.cn/Article/details/gt2hyspezgw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.fzhhl.top/Article/details/gt2jwxhgaet.html

JS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uwpdqsii.html

TS:   await Promise.all(tasks)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mnriosuj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cheryme.top/Article/details/gt2wpjkxxul.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.fzhhl.top/Article/details/gt2nwfhhnpp.html

Ruby: threads.map(&:join)
来源：http://dali.yvedp.cn/Article/details/gt2uynysjxp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yj202588.top/Article/details/gt2pcepzpub.html

[O06] 使用进程池
来源：http://dali.smart0.xyz/Article/details/gt2ebkqgeur.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yuanzhike.top/Article/details/gt2qznyllkr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hfpthk.cn/Article/details/gt2emaoenyg.html

JS:   // child_process / cluster 模块
来源：http://dali.sufxvd.cn/Article/details/gt2tbkldrwz.html

TS:   // child_process / cluster 模块
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2idaqjweg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ivvv.top/Article/details/gt2ghdeoovc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ppjwa.cn/Article/details/gt2cwwyimha.html

Ruby: // fork 块
来源：http://dali.shuidangran.top/Article/details/gt2lamfhrbp.html

C#:   Parallel.For
来源：http://dali.ybcxt.top/Article/details/gt2vekslrzj.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2qohenbhm.html

P. 常用工具函数
来源：http://dali.zhengqikj.top/Article/details/gt2yepscqzp.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2phfveqhl.html

[P01] 生成 UUID
来源：http://dali.zycfv.cn/Article/details/gt2yryeqddj.html

Py:   str(uuid.uuid4())
来源：http://dali.wangshuangyany.cn/Article/details/gt2uysmcqkm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.pengpengdd.cyou/Article/details/gt2vzcbpzxt.html

JS:   crypto.randomUUID()
来源：http://dali.zdqjudy.top/Article/details/gt2swmobxbw.html

TS:   crypto.randomUUID()
来源：http://dali.chenlongwang.top/Article/details/gt2wqiozubt.html

Java: UUID.randomUUID().toString()
来源：http://dali.nwbrower.top/Article/details/gt2wbnuopci.html

Go:   // 用 github.com/google/uuid
来源：http://dali.svipenyu.cn/Article/details/gt2zacxsaer.html

Ruby: SecureRandom.uuid
来源：http://dali.cdnleiting.top/Article/details/gt2lnmxbnpy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.sufxvd.cn/Article/details/gt2xzwlniww.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinghuilouyu.cn/Article/details/gt2amtfywus.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.daria6918.cn/Article/details/gt2bdidspgh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zdqjudy.top/Article/details/gt2auvatwtl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.kuanghao11.cn/Article/details/gt2jwgnksvk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xuanzx.com/Article/details/gt2qcufknhx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.kuanghao11.cn/Article/details/gt2zvqabhwm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yj20258888.top/Article/details/gt2jdfkzqof.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2lxvftzkz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.fengsongda.top/Article/details/gt2johiktuj.html

[P03] 生成短随机字符串
来源：http://dali.xziqi.cn/Article/details/gt2vbegpnsa.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.fzhhl.top/Article/details/gt2qtmbhdfk.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hnqzz.top/Article/details/gt2lyaiqovl.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jyoumei.cn/Article/details/gt2zsmpstvg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.feifeiyinyue.top/Article/details/gt2rpybiuva.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yangfankeji.com/Article/details/gt2ngbbkwjv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.dashuyun.cn/Article/details/gt2yxngyegj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yvedp.cn/Article/details/gt2lirkrxkq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xuanzx.com/Article/details/gt2cethlqss.html

[P04] 求长度
来源：http://dali.kuanghao11.cn/Article/details/gt2oneidwwv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gaohongyu789.top/Article/details/gt2xledeois.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gt2tonlqfqj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sufxvd.cn/Article/details/gt2plrcufbi.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.vqdsnc.cn/Article/details/gt2tbcmbgdr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhiwuduotai.top/Article/details/gt2bccevpbd.html

Go:   len(arr);  len(m)
来源：http://dali.ydzc1.top/Article/details/gt2odvwcjda.html

Ruby: x.length;  x.size
来源：http://dali.hywenlv.cn/Article/details/gt2mpnsnzth.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yjnmudwl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hywenlv.cn/Article/details/gt2atzaakyf.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ybcxt.top/Article/details/gt2lfzvlvbx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jqgfzy.top/Article/details/gt2fncowccr.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.aibaodan.cn/Article/details/gt2ztehrjfs.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenzaomai.com/Article/details/gt2jklsmvvo.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.tianlin.xyz/Article/details/gt2oukijbpi.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yangfankeji.com/Article/details/gt2ywvyhrbw.html

Ruby: a == b
来源：http://dali.zhiwuduotai.top/Article/details/gt2yqcgzcpd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhiwuduotai.top/Article/details/gt2pakrvbqs.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2oyyfminn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yvedp.cn/Article/details/gt2belflesd.html

PHP:  if (empty($x)) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2dkkvfvjo.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cheryme.top/Article/details/gt2kzzlgbng.html

TS:   if (x == null) {}
来源：http://dali.chenzaomai.com/Article/details/gt2taxvgeoa.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.fzhhl.top/Article/details/gt2reczcepp.html

Go:   if x == nil {}
来源：http://dali.ivvv.top/Article/details/gt2fpdwnjah.html


<!-- 参考信息 -->