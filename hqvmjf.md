代发 wailian999

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.mhx1999.top/Article/details/gt2przefacc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.wangshuangyany.cn/Article/details/gt2cmiujrja.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2monbcxdl.html

M. 命令行 / 进程 / 环境
来源：http://dali.yuanzhike.top/Article/details/gt2dirjzmwl.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2pquznevo.html

[M01] 读取命令行参数
来源：http://dali.guowangkeji.top/Article/details/gt2dinssksg.html

Py:   sys.argv[1:]
来源：http://dali.pengpengdd.cyou/Article/details/gt2vlgovnzy.html

PHP:  $argv;  $argc;
来源：http://dali.zhengqikj.top/Article/details/gt2lobysjnv.html

JS:   process.argv.slice(2)
来源：http://dali.9152youxi.cn/Article/details/gt2woiqrkpz.html

TS:   process.argv.slice(2)
来源：http://dali.sweek.top/Article/details/gt2batmahnw.html

Java: args 数组（main 方法参数）
来源：http://dali.jianghu66.top/Article/details/gt2jqmmqrzr.html

Go:   os.Args[1:]
来源：http://dali.zhengqikj.top/Article/details/gt2hqiyjfey.html

Ruby: ARGV
来源：http://dali.ybcxt.top/Article/details/gt2zstvuwwj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hnqzz.top/Article/details/gt2vtsgiaxc.html

[M02] 读取环境变量
来源：http://dali.jinqigfzy.top/Article/details/gt2dfyvneeq.html

Py:   os.environ.get("HOME")
来源：http://dali.yvedp.cn/Article/details/gt2blmxavxy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qulukdru.html

JS:   process.env.HOME
来源：http://dali.sweek.top/Article/details/gt2qqcnpizz.html

TS:   process.env.HOME
来源：http://dali.hnqzz.top/Article/details/gt2rzoqzoxf.html

Java: System.getenv("HOME")
来源：http://dali.tanke756.top/Article/details/gt2fbiksfzc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.9152youxi.cn/Article/details/gt2qwgkyidm.html

Ruby: ENV["HOME"]
来源：http://dali.jlsjyb.cn/Article/details/gt2bwajbmdy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gt2vrpdmwnf.html

[M03] 执行外部命令
来源：http://dali.hysaishi.cn/Article/details/gt2ridrfoze.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.smart0.xyz/Article/details/gt2jlydegvh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.svipenyu.cn/Article/details/gt2ujzndkmm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.pengpengdd.cyou/Article/details/gt2wzefigrm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shuidangran.top/Article/details/gt2tqbpzmts.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xinyue.icu/Article/details/gt2infqrrbi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.chenjidiqi.icu/Article/details/gt2bqzibcer.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yj20258888.top/Article/details/gt2xlgmptok.html

C#:   Process.Start("ls", "-l");
来源：http://dali.feifeiyinyue.top/Article/details/gt2ifaugtor.html

[M04] 获取当前工作目录
来源：http://dali.gzhubu.top/Article/details/gt2huhvfpvz.html

Py:   os.getcwd()
来源：http://dali.0kj1m.cn/Article/details/gt2mqkvyiry.html

PHP:  getcwd();
来源：http://dali.ivvv.top/Article/details/gt2oudmdfon.html

JS:   process.cwd()
来源：http://dali.yueranfly.top/Article/details/gt2ohabbhvb.html

TS:   process.cwd()
来源：http://dali.zhoulong.xyz/Article/details/gt2rfmqkuwe.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.c1oappe.top/Article/details/gt2llzfbjem.html

Go:   os.Getwd()
来源：http://dali.hongshengwenyu.top/Article/details/gt2hkzixibi.html

Ruby: Dir.pwd
来源：http://dali.yj20258.top/Article/details/gt2bbslvxhh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sbyjotli.html

[M05] 设置退出码
来源：http://dali.9152youxi.cn/Article/details/gt2gdaipowa.html

Py:   sys.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gt2drojqvrr.html

PHP:  exit(1);
来源：http://dali.pycfn.com/Article/details/gt2dycqrtbn.html

JS:   process.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gt2dvucudmj.html

TS:   process.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xrhggusg.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghszwiwg.html

Go:   os.Exit(1)
来源：http://dali.cucudq.cn/Article/details/gt2hrmmvodj.html

Ruby: exit 1
来源：http://dali.sufxvd.cn/Article/details/gt2xmhcfmox.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2dkyqyehh.html

[M06] 向标准错误输出
来源：http://dali.aibaodan.cn/Article/details/gt2vxjcmrcg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gogol.net.cn/Article/details/gt2otccnuct.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shuidangran.top/Article/details/gt2bauznsov.html

JS:   console.error("err")
来源：http://dali.ivvv.top/Article/details/gt2cznnqrww.html

TS:   console.error("err")
来源：http://dali.gogol.net.cn/Article/details/gt2vmsjurjr.html

Java: System.err.println("err")
来源：http://dali.redwolf501.top/Article/details/gt2msdmilye.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2poqmbkmg.html

Ruby: warn "err"
来源：http://dali.dashuyun.cn/Article/details/gt2fxbjntkz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.fzhhl.top/Article/details/gt2ipaibunb.html

[M07] 判断是否为主入口
来源：http://dali.hysaishi.cn/Article/details/gt2tcbbhovg.html

Py:   if __name__ == "__main__":
来源：http://dali.zdqjudy.top/Article/details/gt2zkhbglau.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cdnleiting.top/Article/details/gt2erpwwbor.html

JS:   require.main === module
来源：http://dali.hfpthk.cn/Article/details/gt2oouuufqc.html

TS:   require.main === module
来源：http://dali.chenjidiqi.icu/Article/details/gt2aoboxkem.html

Java: public static void main(String[] args)
来源：http://dali.birdmap.top/Article/details/gt2bwztreyl.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2llqgkdtl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.dianchejie.cn/Article/details/gt2dtcsisvo.html

C#:   static void Main(string[] args)
来源：http://dali.aibaodan.cn/Article/details/gt2wqvfboat.html

[M08] 获取系统与运行时信息
来源：http://dali.zhongyouzk.top/Article/details/gt2ulrujnuv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yueranfly.top/Article/details/gt2azfchmog.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mzalyrap.html

JS:   process.platform;  process.version
来源：http://dali.wangdashe.top/Article/details/gt2xjcqcmkw.html

TS:   process.platform;  process.version
来源：http://dali.yj202588.top/Article/details/gt2aryctalo.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jiagoushi.top/Article/details/gt2ylfrinnx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.9152youxi.cn/Article/details/gt2vfnqbcxt.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zdqjudy.top/Article/details/gt2riinwrnk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jlsjyb.cn/Article/details/gt2tgbertnz.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2hqljnsoo.html

N. 数据结构与算法
来源：http://dali.hywenlv.cn/Article/details/gt2jieaervg.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2fkmsxccs.html

[N01] 二分查找（有序数组）
来源：http://dali.yj20258.top/Article/details/gt2nphcqsfb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gt2kxognkzl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.bjfxy.top/Article/details/gt2opwouepi.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhixingplan.top/Article/details/gt2fmfbchyn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxuanxn.top/Article/details/gt2vuqhbmuy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gt2dkxvciyz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gt2ccsznviy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.daria6918.cn/Article/details/gt2aohdudfr.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nwbrower.top/Article/details/gt2ogkxbdrx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xuanzx.com/Article/details/gt2dzsamhcu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigfzy.top/Article/details/gt2epjxlmwv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nanxuanxn.top/Article/details/gt2vfrhciyn.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigufen.top/Article/details/gt2lkdaatyl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sufxvd.cn/Article/details/gt2fttnewja.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.quarkkingdee.top/Article/details/gt2uautzxmq.html

Go:   slices.Sort(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2udcdequh.html

Ruby: arr.sort
来源：http://dali.gotoacloud.top/Article/details/gt2ljjhzaqv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gaohongyu789.top/Article/details/gt2ksdizbfb.html

[N03] 快速排序（分治示例）
来源：http://dali.vqdsnc.cn/Article/details/gt2xgslgdpn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hsctppik.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhongyouzk.top/Article/details/gt2mlhlhmaz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cheryme.top/Article/details/gt2qukgncxo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenjidiqi.icu/Article/details/gt2aicgcrxh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yuanzhike.top/Article/details/gt2egtvupnr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.havefunace.top/Article/details/gt2sdhpdxpq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zycfv.cn/Article/details/gt2gjnclbep.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.guowangkeji.top/Article/details/gt2taqnukmi.html

[N04] 斐波那契数列
来源：http://dali.chenjidiqi.icu/Article/details/gt2mmxkppzy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tccokujr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sweek.top/Article/details/gt2gkomydtn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.snrcjt.cn/Article/details/gt2aagvcjvo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhixingplan.top/Article/details/gt2pokrtfxi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cucudq.cn/Article/details/gt2cfhldzda.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ybcxt.top/Article/details/gt2kvysmqsf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258.top/Article/details/gt2qqjiwzay.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.daxiang520.top/Article/details/gt2bhybdscf.html

[N05] 最大公约数
来源：http://dali.hongshengwenyu.top/Article/details/gt2irwiwobz.html

Py:   math.gcd(a, b)
来源：http://dali.bjfxy.top/Article/details/gt2dikozuvc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2lckqaiiz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.iojbl.cn/Article/details/gt2khcltxeh.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gaohongyu789.top/Article/details/gt2ddtcqkwh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yonumen.top/Article/details/gt2ctcqpswd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hongshengwenyu.top/Article/details/gt2syjkkcgb.html

Ruby: a.gcd(b)
来源：http://dali.yj202588.top/Article/details/gt2ishaamvd.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2mzmmmuwr.html

[N06] 判断回文字符串
来源：http://dali.gotoacloud.top/Article/details/gt2lueklefi.html

Py:   s == s[::-1]
来源：http://dali.birdmap.top/Article/details/gt2yssbjyhq.html

PHP:  $s === strrev($s);
来源：http://dali.sysykeji.top/Article/details/gt2prroubxm.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gt2ktaddove.html

TS:   s === [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gt2zxdratsz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.c1oappe.top/Article/details/gt2hyuxadvs.html

Go:   // 双指针从两端比较
来源：http://dali.yj202588.top/Article/details/gt2uehbogvm.html

Ruby: s == s.reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jrjfeooh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.birdmap.top/Article/details/gt2esgrttpw.html

[N07] 两数之和（返回下标）
来源：http://dali.meibo888.top/Article/details/gt2nhwkqunx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.pycfn.com/Article/details/gt2ukrunads.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cdnleiting.top/Article/details/gt2jqqthfbs.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zdqjudy.top/Article/details/gt2advabtun.html

TS:   // 手写 Map<string, number>
来源：http://dali.pengpengdd.cyou/Article/details/gt2gvqabeip.html

Java: // 手写 HashMap
来源：http://dali.c1oappe.top/Article/details/gt2refdggko.html

Go:   // 手写 map[int]int
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ahlrkmou.html

Ruby: // 手写 Hash
来源：http://dali.yuxming.cn/Article/details/gt2dzihmvuh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yueranfly.top/Article/details/gt2lugmujnw.html

[N08] 生成全排列
来源：http://dali.zhiwuduotai.top/Article/details/gt2gwsghfhh.html

Py:   itertools.permutations(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2ptiutdlc.html

PHP:  // 手写递归交换
来源：http://dali.birdmap.top/Article/details/gt2qwlkvrum.html

JS:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gt2ueynsixy.html

TS:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gt2iyqqcxep.html

Java: // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gt2hhkcpzbj.html

Go:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ecrdulvx.html

Ruby: arr.permutation.to_a
来源：http://dali.guannengcc.top/Article/details/gt2sfegqijk.html

C#:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lzfrzyqa.html

[N09] 栈与队列
来源：http://dali.sxryk.cn/Article/details/gt2hbcdfwql.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.aibaodan.cn/Article/details/gt2zabybxla.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jianghu66.top/Article/details/gt2pmaxvetm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.chenlongwang.top/Article/details/gt2ockeajtm.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.pengpengdd.cyou/Article/details/gt2glvgbaxf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rzanviyk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhengqikj.top/Article/details/gt2lhmtgqsm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.vqdsnc.cn/Article/details/gt2fxzrkzwd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.dashuyun.cn/Article/details/gt2pflrjlhl.html

[N10] 链表节点定义
来源：http://dali.tian-w.cn/Article/details/gt2wbqjxexy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinqigufen.top/Article/details/gt2lfcglwbv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yj202588.top/Article/details/gt2fnvnbeeo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sysykeji.top/Article/details/gt2maptzjgo.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yanxiufei.cn/Article/details/gt2aljrmvbm.html

Java: class Node { int v; Node next; }
来源：http://dali.jlsjyb.cn/Article/details/gt2nycborsw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hysaishi.cn/Article/details/gt2euymkjiz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hongshengwenyu.top/Article/details/gt2bquuyumt.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yangfankeji.com/Article/details/gt2fgiysfez.html

[N11] 二叉树中序遍历
来源：http://dali.ybcxt.top/Article/details/gt2npnvmqne.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.birdmap.top/Article/details/gt2hgssmjem.html

PHP:  // 手写递归函数
来源：http://dali.meibo888.top/Article/details/gt2gvlklxdt.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daxiang520.top/Article/details/gt2coftfjmb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.c1oappe.top/Article/details/gt2hmcycdhb.html

Java: // 手写递归
来源：http://dali.yj20258888.top/Article/details/gt2irwazkxi.html

Go:   // 手写递归
来源：http://dali.ppjwa.cn/Article/details/gt2urniijir.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.vqdsnc.cn/Article/details/gt2vzjzagrj.html

C#:   // 手写递归
来源：http://dali.yj20258.top/Article/details/gt2ohtruwki.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ydzc1.top/Article/details/gt2gqqrdlri.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yongpay.top/Article/details/gt2xkjixsak.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zdqjudy.top/Article/details/gt2ccmrbtdt.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258.top/Article/details/gt2yrefcetz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.vqdsnc.cn/Article/details/gt2myswowfe.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ehwqpu.com/Article/details/gt2gbljeqsc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.dianchejie.cn/Article/details/gt2slqhkmhe.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jyoumei.cn/Article/details/gt2idsrdbng.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ybcxt.top/Article/details/gt2nucigpnm.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2pfoprdwe.html

O. 并发与异步
来源：http://dali.svipenyu.cn/Article/details/gt2pinytccy.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2kmlndvqp.html

[O01] 启动一个线程
来源：http://dali.redwolf501.top/Article/details/gt2opyytkaw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.redwolf501.top/Article/details/gt2exogjdxl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hfpthk.cn/Article/details/gt2dsqvmutq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yvedp.cn/Article/details/gt2nyxhndmn.html

TS:   // 同 JS
来源：http://dali.cqqwz.cn/Article/details/gt2xxnpazid.html

Java: new Thread(() -> f()).start()
来源：http://dali.cqqwz.cn/Article/details/gt2tnrazobj.html

Go:   go f()
来源：http://dali.zhiwuduotai.top/Article/details/gt2whvvezjd.html

Ruby: Thread.new { f }
来源：http://dali.pengpengdd.cyou/Article/details/gt2rnyxqmkp.html

C#:   Task.Run(() => F());
来源：http://dali.shuidangran.top/Article/details/gt2tpyuroji.html

[O02] 使用线程池
来源：http://dali.ybcxt.top/Article/details/gt2emrjhfyf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xinyue.icu/Article/details/gt2inevuwuq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hywenlv.cn/Article/details/gt2jnknkcev.html

JS:   // worker_threads 线程池
来源：http://dali.ydzc1.top/Article/details/gt2mirninzo.html

TS:   // worker_threads 线程池
来源：http://dali.yuxming.cn/Article/details/gt2qpdplisr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yonumen.top/Article/details/gt2shymyhlo.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.andypj.xyz/Article/details/gt2ofalnxxz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.smart0.xyz/Article/details/gt2jjvfwwdx.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.smart0.xyz/Article/details/gt2geufctbc.html

[O03] 加锁保护共享数据
来源：http://dali.shuidangran.top/Article/details/gt2tkdoofwc.html

Py:   with lock: shared += 1
来源：http://dali.xinyue.icu/Article/details/gt2epctatat.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yueranfly.top/Article/details/gt2rzijxxvr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jqgufenzy.top/Article/details/gt2vveeinzs.html

TS:   // 同 JS
来源：http://dali.pycfn.com/Article/details/gt2wndfwbuw.html

Java: synchronized (this) { shared++; }
来源：http://dali.nanxuanxn.top/Article/details/gt2fyrtvfyx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.vqdsnc.cn/Article/details/gt2rdwbvufn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhiwuduotai.top/Article/details/gt2sdswewyb.html

C#:   lock (gate) { shared++; }
来源：http://dali.sxryk.cn/Article/details/gt2yoeqzcut.html

[O04] 定义异步函数并等待
来源：http://dali.hnxiangtu.top/Article/details/gt2deinrlaz.html

Py:   async def f():⏎    await g()
来源：http://dali.jiagoushi.top/Article/details/gt2kmifelnh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shanyushiyangtech.top/Article/details/gt2umkbmgue.html

JS:   async function f() { await g(); }
来源：http://dali.ivvv.top/Article/details/gt2kiwkxjzp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hywenlv.cn/Article/details/gt2ersqoaxb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yvedp.cn/Article/details/gt2vpgtcumi.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gzhubu.top/Article/details/gt2vkbdmiop.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.quarkkingdee.top/Article/details/gt2kncfrisn.html

C#:   async Task F() { await G(); }
来源：http://dali.sxryk.cn/Article/details/gt2xoalpvkv.html

[O05] 并发执行并等待全部完成
来源：http://dali.sxryk.cn/Article/details/gt2niiwpxxt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cdnleiting.top/Article/details/gt2wokyznws.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cashguo.top/Article/details/gt2crgnqxiu.html

JS:   await Promise.all(tasks)
来源：http://dali.sufxvd.cn/Article/details/gt2zdphaidd.html

TS:   await Promise.all(tasks)
来源：http://dali.yonumen.top/Article/details/gt2ujiwlvfv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qhiqimto.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2twdtvhgb.html

Ruby: threads.map(&:join)
来源：http://dali.yangfankeji.com/Article/details/gt2jvpixzfy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yvedp.cn/Article/details/gt2hppitqkt.html

[O06] 使用进程池
来源：http://dali.dianchejie.cn/Article/details/gt2pnapqwah.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.snrcjt.cn/Article/details/gt2psstykdy.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cashguo.top/Article/details/gt2npkacohr.html

JS:   // child_process / cluster 模块
来源：http://dali.smart0.xyz/Article/details/gt2yjubokap.html

TS:   // child_process / cluster 模块
来源：http://dali.quarkkingdee.top/Article/details/gt2efpyrtyl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cucudq.cn/Article/details/gt2wxwchajz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.pengpengdd.cyou/Article/details/gt2vuosymiv.html

Ruby: // fork 块
来源：http://dali.zycfv.cn/Article/details/gt2zhxgrbkv.html

C#:   Parallel.For
来源：http://dali.ydzc1.top/Article/details/gt2ijoroqfl.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2zeyzlvtm.html

P. 常用工具函数
来源：http://dali.yueranfly.top/Article/details/gt2cdyytcgz.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2uiksmuxu.html

[P01] 生成 UUID
来源：http://dali.chenzaomai.com/Article/details/gt2ipafhuwg.html

Py:   str(uuid.uuid4())
来源：http://dali.yuanzhike.top/Article/details/gt2bkwatxxt.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinqigufen.top/Article/details/gt2yseqmzmb.html

JS:   crypto.randomUUID()
来源：http://dali.c1oappe.top/Article/details/gt2yotswfcw.html

TS:   crypto.randomUUID()
来源：http://dali.xylfe.cn/Article/details/gt2kwbvqrmk.html

Java: UUID.randomUUID().toString()
来源：http://dali.xinyue.icu/Article/details/gt2bhdnlpqr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.0kj1m.cn/Article/details/gt2akjgkkpn.html

Ruby: SecureRandom.uuid
来源：http://dali.sufxvd.cn/Article/details/gt2mamqmsnn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.meibo888.top/Article/details/gt2cctcmvpi.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gdvfsvar.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.fengsongda.top/Article/details/gt2pyepnvcs.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zpxcssxz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gzhubu.top/Article/details/gt2ecxgqdbd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.9152youxi.cn/Article/details/gt2bjlzotfp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.gzhubu.top/Article/details/gt2gqtqvdox.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ivvv.top/Article/details/gt2hzqzugjl.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.fzhhl.top/Article/details/gt2jnclarza.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hammf.cn/Article/details/gt2bekfrkjn.html

[P03] 生成短随机字符串
来源：http://dali.redwolf501.top/Article/details/gt2dhqbejva.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jiagoushi.top/Article/details/gt2yjdrvdcb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jiagoushi.top/Article/details/gt2vdlcnnxf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pengpengdd.cyou/Article/details/gt2zvjydtlg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuetiantiany.cn/Article/details/gt2lwbzolvd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.gotoacloud.top/Article/details/gt2xxqcpdbn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.9152youxi.cn/Article/details/gt2gulajtrb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yj20258888.top/Article/details/gt2rmvbqywq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.daxiang520.top/Article/details/gt2lnhdxkea.html

[P04] 求长度
来源：http://dali.chenlongwang.top/Article/details/gt2pueyjccf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.bjfxy.top/Article/details/gt2cyduqroz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gt2kpsgrwfk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shuidangran.top/Article/details/gt2lmkpcwms.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenjidiqi.icu/Article/details/gt2vwkpspei.html

Java: list.size();  map.size();  s.length()
来源：http://dali.gaohongyu789.top/Article/details/gt2pwpqlwiw.html

Go:   len(arr);  len(m)
来源：http://dali.shuidangran.top/Article/details/gt2aclzqxvq.html

Ruby: x.length;  x.size
来源：http://dali.dashuyun.cn/Article/details/gt2cxgvkxxd.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.bjfxy.top/Article/details/gt2zrouxhxh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cinkrxdx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.0kj1m.cn/Article/details/gt2eicbcpff.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.havefunace.top/Article/details/gt2qjboaonp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yanxiufei.cn/Article/details/gt2jnsodgiq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2epbxobej.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.guowangkeji.top/Article/details/gt2esboudde.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.gotoacloud.top/Article/details/gt2aqlxufxr.html

Ruby: a == b
来源：http://dali.0kj1m.cn/Article/details/gt2mgfifihr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhongyouzk.top/Article/details/gt2hdwrpypw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ivvv.top/Article/details/gt2dgtlvslh.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.kuanghao11.cn/Article/details/gt2ldpzwpat.html

PHP:  if (empty($x)) {}
来源：http://dali.meibo888.top/Article/details/gt2hrixjrrh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.smart0.xyz/Article/details/gt2pumpaehw.html

TS:   if (x == null) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ivfswtug.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.dashuyun.cn/Article/details/gt2yjvwklvy.html

Go:   if x == nil {}
来源：http://dali.zhengqikj.top/Article/details/gt2jwmyfnwk.html


<!-- 参考信息 -->