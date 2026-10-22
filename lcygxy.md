代发 wailian999

Ruby: ARGV
来源：http://dali.yj20258.top/Article/details/gt2cxgqffai.html

C#:   args 数组（Main 方法参数）
来源：http://dali.316326.xyz/Article/details/gt2wcuivcrk.html

[M02] 读取环境变量
来源：http://dali.andypj.xyz/Article/details/gt2enntjjee.html

Py:   os.environ.get("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gt2yphqcavw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.redwolf501.top/Article/details/gt2vrkipxem.html

JS:   process.env.HOME
来源：http://dali.shuidangran.top/Article/details/gt2oevtyqjm.html

TS:   process.env.HOME
来源：http://dali.sweek.top/Article/details/gt2uqruwact.html

Java: System.getenv("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gzrqpntb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cucudq.cn/Article/details/gt2auaihtao.html

Ruby: ENV["HOME"]
来源：http://dali.yonumen.top/Article/details/gt2qkwjpgxc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cucudq.cn/Article/details/gt2ajxqnnmy.html

[M03] 执行外部命令
来源：http://dali.hfpthk.cn/Article/details/gt2lhdmcger.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lmhfdcvi.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.wangshuangyany.cn/Article/details/gt2tmfmzgym.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ydzc1.top/Article/details/gt2pwakimjt.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2buvratzv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aiefjezh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.pengpengdd.cyou/Article/details/gt2mfmfnqnf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jqgufenzy.top/Article/details/gt2ypfymkjg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hfpthk.cn/Article/details/gt2yvzzoixg.html

[M04] 获取当前工作目录
来源：http://dali.birdmap.top/Article/details/gt2qzlixdxh.html

Py:   os.getcwd()
来源：http://dali.iojbl.cn/Article/details/gt2krenwfhu.html

PHP:  getcwd();
来源：http://dali.gotoacloud.top/Article/details/gt2kjwhtuib.html

JS:   process.cwd()
来源：http://dali.chenlongwang.top/Article/details/gt2tesgqqyg.html

TS:   process.cwd()
来源：http://dali.cashguo.top/Article/details/gt2lamddwei.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.bjfxy.top/Article/details/gt2jhmwtjxn.html

Go:   os.Getwd()
来源：http://dali.mhx1999.top/Article/details/gt2yxnthjzf.html

Ruby: Dir.pwd
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hvhclqlu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinqigfzy.top/Article/details/gt2pejzeajd.html

[M05] 设置退出码
来源：http://dali.ivvv.top/Article/details/gt2boxadclk.html

Py:   sys.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2svomzlus.html

PHP:  exit(1);
来源：http://dali.jlsjyb.cn/Article/details/gt2kxgdcjen.html

JS:   process.exit(1)
来源：http://dali.shuidangran.top/Article/details/gt2xwwapixi.html

TS:   process.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gt2zqdvlpvy.html

Java: System.exit(1)
来源：http://dali.cucudq.cn/Article/details/gt2xozsqowc.html

Go:   os.Exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2yotohzch.html

Ruby: exit 1
来源：http://dali.havefunace.top/Article/details/gt2gngulpxe.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenzaomai.com/Article/details/gt2uzmxppdd.html

[M06] 向标准错误输出
来源：http://dali.daxiang520.top/Article/details/gt2wecqqxjf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj20258.top/Article/details/gt2nsdzmztl.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.pengpengdd.cyou/Article/details/gt2btcykedt.html

JS:   console.error("err")
来源：http://dali.jinqigufen.top/Article/details/gt2glaqopfl.html

TS:   console.error("err")
来源：http://dali.xuanzx.com/Article/details/gt2lgrdtsaz.html

Java: System.err.println("err")
来源：http://dali.cheryme.top/Article/details/gt2mwllscjf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hywenlv.cn/Article/details/gt2dvmdnwsu.html

Ruby: warn "err"
来源：http://dali.bjfxy.top/Article/details/gt2ohpdcttv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ivvv.top/Article/details/gt2cqoijvjz.html

[M07] 判断是否为主入口
来源：http://dali.hongshengwenyu.top/Article/details/gt2wpjbokxc.html

Py:   if __name__ == "__main__":
来源：http://dali.xinyue.icu/Article/details/gt2ilbgdpjw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cheryme.top/Article/details/gt2cfhbabpu.html

JS:   require.main === module
来源：http://dali.c1oappe.top/Article/details/gt2ooyechrt.html

TS:   require.main === module
来源：http://dali.chenjidiqi.icu/Article/details/gt2wvuxhqzk.html

Java: public static void main(String[] args)
来源：http://dali.hongshengwenyu.top/Article/details/gt2gomgxqul.html

Go:   func main()
来源：http://dali.hysaishi.cn/Article/details/gt2rgbbtecu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ppjwa.cn/Article/details/gt2pexrovwg.html

C#:   static void Main(string[] args)
来源：http://dali.gzhubu.top/Article/details/gt2qvpkkfiy.html

[M08] 获取系统与运行时信息
来源：http://dali.havefunace.top/Article/details/gt2lvikkpuk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sufxvd.cn/Article/details/gt2qhhjbuas.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shangyingyoupin.top/Article/details/gt2uqlxcyex.html

JS:   process.platform;  process.version
来源：http://dali.snrcjt.cn/Article/details/gt2wzodagga.html

TS:   process.platform;  process.version
来源：http://dali.jiagoushi.top/Article/details/gt2urytoyqk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nanxuanxn.top/Article/details/gt2hdqbezcs.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yongpay.top/Article/details/gt2ffjwtwnn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.daxiang520.top/Article/details/gt2kgzvjddi.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.meibo888.top/Article/details/gt2hyorrcgz.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2vrrfzdpv.html

N. 数据结构与算法
来源：http://dali.jlsjyb.cn/Article/details/gt2ifikhnbe.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2aztwwbtf.html

[N01] 二分查找（有序数组）
来源：http://dali.hysaishi.cn/Article/details/gt2xnwfiegb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gt2ctebukuo.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.bjfxy.top/Article/details/gt2osyravex.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuanzx.com/Article/details/gt2xmnfnjdp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cucudq.cn/Article/details/gt2zxfdhzdh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gphzhnxt.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yuxming.cn/Article/details/gt2kjoaejlo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.c1oappe.top/Article/details/gt2saroghcz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gt2syrksupf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenjidiqi.icu/Article/details/gt2riprnqtl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.iojbl.cn/Article/details/gt2nagxohmp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ehwqpu.com/Article/details/gt2cvrzwold.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guowangkeji.top/Article/details/gt2wqqhzhok.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2kxmfyasg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ppjwa.cn/Article/details/gt2aqcslnxa.html

Go:   slices.Sort(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2vgtvdspo.html

Ruby: arr.sort
来源：http://dali.meibo888.top/Article/details/gt2ylkakbql.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cqfontsm.html

[N03] 快速排序（分治示例）
来源：http://dali.dashuyun.cn/Article/details/gt2vulkhurj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jqgufenzy.top/Article/details/gt2nbmqefux.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xinyue.icu/Article/details/gt2ekymyyco.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigufen.top/Article/details/gt2zonbifqp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xziqi.cn/Article/details/gt2zibodpkv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.nanxuanxn.top/Article/details/gt2xyduzybt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jiagoushi.top/Article/details/gt2gwkvikwj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhongyouzk.top/Article/details/gt2gznrzvuu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hnqzz.top/Article/details/gt2ajmagydr.html

[N04] 斐波那契数列
来源：http://dali.pengpengdd.cyou/Article/details/gt2jnrcaaxf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sxryk.cn/Article/details/gt2fvzoapqb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cetmgnhr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gt2eljsiswt.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenjidiqi.icu/Article/details/gt2icpwzuch.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yangfankeji.com/Article/details/gt2shuksmsc.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hammf.cn/Article/details/gt2fslkbpes.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2wgzzxfip.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.kuanghao11.cn/Article/details/gt2hefpjsje.html

[N05] 最大公约数
来源：http://dali.cashguo.top/Article/details/gt2vhaedbwr.html

Py:   math.gcd(a, b)
来源：http://dali.ybcxt.top/Article/details/gt2yehnktjt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2zvgpqurp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.c1oappe.top/Article/details/gt2anvsynph.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pycfn.com/Article/details/gt2hdotecvy.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jlsjyb.cn/Article/details/gt2gvryaqtd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zdqjudy.top/Article/details/gt2sznohjfk.html

Ruby: a.gcd(b)
来源：http://dali.ppjwa.cn/Article/details/gt2uyrifzcf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xylfe.cn/Article/details/gt2ixrtczke.html

[N06] 判断回文字符串
来源：http://dali.cheryme.top/Article/details/gt2iubinnfg.html

Py:   s == s[::-1]
来源：http://dali.tianlin.xyz/Article/details/gt2heaywymq.html

PHP:  $s === strrev($s);
来源：http://dali.0kj1m.cn/Article/details/gt2fampuyhx.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gt2uhuoeljx.html

TS:   s === [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gt2rkwoktwr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.andypj.xyz/Article/details/gt2upxscxic.html

Go:   // 双指针从两端比较
来源：http://dali.aibaodan.cn/Article/details/gt2zohrbseh.html

Ruby: s == s.reverse
来源：http://dali.bjfxy.top/Article/details/gt2eswyudqh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jiagoushi.top/Article/details/gt2fnldrnhm.html

[N07] 两数之和（返回下标）
来源：http://dali.aizwys.cn/Article/details/gt2svrrwdxb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yangfankeji.com/Article/details/gt2uqdvdduj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yuxming.cn/Article/details/gt2qcqwssci.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xylfe.cn/Article/details/gt2qggtoizm.html

TS:   // 手写 Map<string, number>
来源：http://dali.tanke756.top/Article/details/gt2aeicswvy.html

Java: // 手写 HashMap
来源：http://dali.pycfn.com/Article/details/gt2qkwgsyrq.html

Go:   // 手写 map[int]int
来源：http://dali.0kj1m.cn/Article/details/gt2nvmhbkms.html

Ruby: // 手写 Hash
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yihwhqba.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2frvjilub.html

[N08] 生成全排列
来源：http://dali.shuidangran.top/Article/details/gt2xmkgifai.html

Py:   itertools.permutations(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2bmwjhorq.html

PHP:  // 手写递归交换
来源：http://dali.yangfankeji.com/Article/details/gt2vrmyxzoe.html

JS:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gt2nsytiqnm.html

TS:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gt2mibzldzq.html

Java: // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gt2lsfnaagi.html

Go:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gt2acohosij.html

Ruby: arr.permutation.to_a
来源：http://dali.ybcxt.top/Article/details/gt2rkuwvkhu.html

C#:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gt2bmolgedb.html

[N09] 栈与队列
来源：http://dali.cheryme.top/Article/details/gt2bqvfkwwn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gt2qiafqgts.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.iojbl.cn/Article/details/gt2sxumsltx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qvtwwykt.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.chenlongwang.top/Article/details/gt2adbptguz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yonumen.top/Article/details/gt2xyfvichq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.meibo888.top/Article/details/gt2ggmjbzls.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.c1oappe.top/Article/details/gt2mxqyvyhb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ansngjeu.html

[N10] 链表节点定义
来源：http://dali.aizwys.cn/Article/details/gt2fcvtbwrf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xziqi.cn/Article/details/gt2utliekde.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2feeqjyth.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.quarkkingdee.top/Article/details/gt2ssjcvsje.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ydzc1.top/Article/details/gt2ptjlcjvq.html

Java: class Node { int v; Node next; }
来源：http://dali.jianghu66.top/Article/details/gt2vtrmmmsu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hammf.cn/Article/details/gt2vwxbwyki.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yuxming.cn/Article/details/gt2eosutdjg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.iojbl.cn/Article/details/gt2huohjtey.html

[N11] 二叉树中序遍历
来源：http://dali.yuanzhike.top/Article/details/gt2xbptrttv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinqigfzy.top/Article/details/gt2exjvwelw.html

PHP:  // 手写递归函数
来源：http://dali.yj20258888.top/Article/details/gt2pgnkpecr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuanzhike.top/Article/details/gt2phbgslop.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ydzc1.top/Article/details/gt2gqkqjpvi.html

Java: // 手写递归
来源：http://dali.yj202588.top/Article/details/gt2oslfojjx.html

Go:   // 手写递归
来源：http://dali.xziqi.cn/Article/details/gt2toavqkkj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sxryk.cn/Article/details/gt2icmfijqb.html

C#:   // 手写递归
来源：http://dali.jlsjyb.cn/Article/details/gt2eqvulzjx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hnxiangtu.top/Article/details/gt2einyxoha.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.snrcjt.cn/Article/details/gt2timteemk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lylfvuzf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.kuanghao11.cn/Article/details/gt2ssuzzlaw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yvedp.cn/Article/details/gt2qfkvtojt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tianlin.xyz/Article/details/gt2fcomcrht.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.c1oappe.top/Article/details/gt2gnvkyvpj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzlcyen.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ylarmnxu.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tkurzbqc.html

O. 并发与异步
来源：http://dali.pycfn.com/Article/details/gt2iudwzkao.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2zhodkynm.html

[O01] 启动一个线程
来源：http://dali.ppjwa.cn/Article/details/gt2uigpfblo.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.wangdashe.top/Article/details/gt2ibdndmzy.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.pycfn.com/Article/details/gt2xirpojwb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.tanke756.top/Article/details/gt2fjqeoqll.html

TS:   // 同 JS
来源：http://dali.guannengcc.top/Article/details/gt2lvltrnfu.html

Java: new Thread(() -> f()).start()
来源：http://dali.sufxvd.cn/Article/details/gt2wlpqzkmb.html

Go:   go f()
来源：http://dali.haohaochexian.top/Article/details/gt2jkiwscrq.html

Ruby: Thread.new { f }
来源：http://dali.kuanghao11.cn/Article/details/gt2xyypluue.html

C#:   Task.Run(() => F());
来源：http://dali.yuanzhike.top/Article/details/gt2aidygrix.html

[O02] 使用线程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kllrcydh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.haohaochexian.top/Article/details/gt2svzeiiou.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cqqwz.cn/Article/details/gt2tkldfaon.html

JS:   // worker_threads 线程池
来源：http://dali.tanke756.top/Article/details/gt2gxbkaygc.html

TS:   // worker_threads 线程池
来源：http://dali.quarkkingdee.top/Article/details/gt2bnjabwzs.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cqqwz.cn/Article/details/gt2uwrfchrd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sweek.top/Article/details/gt2vwnqfzxg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.haohaochexian.top/Article/details/gt2jzdnhgdf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zdqjudy.top/Article/details/gt2iqouxqyb.html

[O03] 加锁保护共享数据
来源：http://dali.zhoulong.xyz/Article/details/gt2omqmreov.html

Py:   with lock: shared += 1
来源：http://dali.gogol.net.cn/Article/details/gt2zbyufybi.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.iojbl.cn/Article/details/gt2cpsvldhp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqakygo.html

TS:   // 同 JS
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hefkrueh.html

Java: synchronized (this) { shared++; }
来源：http://dali.vqdsnc.cn/Article/details/gt2tdqeqmlf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xylfe.cn/Article/details/gt2iibqocjt.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.sufxvd.cn/Article/details/gt2pbmhndge.html

C#:   lock (gate) { shared++; }
来源：http://dali.ybcxt.top/Article/details/gt2blcegvjw.html

[O04] 定义异步函数并等待
来源：http://dali.zhiwuduotai.top/Article/details/gt2lavqxjms.html

Py:   async def f():⏎    await g()
来源：http://dali.chenjidiqi.icu/Article/details/gt2bzbhscjw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.bjfxy.top/Article/details/gt2tfcklpfs.html

JS:   async function f() { await g(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2pxotcvnm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.guannengcc.top/Article/details/gt2aagjspvm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.feifeiyinyue.top/Article/details/gt2inctorhw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.wangshuangyany.cn/Article/details/gt2eeegkonf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.tian-w.cn/Article/details/gt2bnkbgwrr.html

C#:   async Task F() { await G(); }
来源：http://dali.chenlongwang.top/Article/details/gt2dwkhwrsl.html

[O05] 并发执行并等待全部完成
来源：http://dali.cheryme.top/Article/details/gt2npjrovqz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hammf.cn/Article/details/gt2bdgdratp.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yangfankeji.com/Article/details/gt2sajtmpjq.html

JS:   await Promise.all(tasks)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gdpsppcy.html

TS:   await Promise.all(tasks)
来源：http://dali.chenjidiqi.icu/Article/details/gt2eewxkpki.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.wangshuangyany.cn/Article/details/gt2vuxfxqbl.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tianlin.xyz/Article/details/gt2takmohuw.html

Ruby: threads.map(&:join)
来源：http://dali.chenzaomai.com/Article/details/gt2hexziqgl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ncqacblb.html

[O06] 使用进程池
来源：http://dali.ybcxt.top/Article/details/gt2riqygmnr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eanmfqie.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.redwolf501.top/Article/details/gt2jbxkugtr.html

JS:   // child_process / cluster 模块
来源：http://dali.fzhhl.top/Article/details/gt2hbpoqgsy.html

TS:   // child_process / cluster 模块
来源：http://dali.yanxiufei.cn/Article/details/gt2gpsdlcpe.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yj20258888.top/Article/details/gt2rdtbmdrr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.nwbrower.top/Article/details/gt2ozpaecxi.html

Ruby: // fork 块
来源：http://dali.shangyingyoupin.top/Article/details/gt2bytuqdcv.html

C#:   Parallel.For
来源：http://dali.hywenlv.cn/Article/details/gt2huokirxk.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2frvwkypq.html

P. 常用工具函数
来源：http://dali.yangfankeji.com/Article/details/gt2ehojmpid.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2lvzstmbx.html

[P01] 生成 UUID
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xabsgiva.html

Py:   str(uuid.uuid4())
来源：http://dali.haohaochexian.top/Article/details/gt2xnewjfab.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinqigfzy.top/Article/details/gt2ngvqxlba.html

JS:   crypto.randomUUID()
来源：http://dali.ivvv.top/Article/details/gt2gnggfwur.html

TS:   crypto.randomUUID()
来源：http://dali.nanxinkj.top/Article/details/gt2gpnwkkkq.html

Java: UUID.randomUUID().toString()
来源：http://dali.tanke756.top/Article/details/gt2xtxyxkeo.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jiagoushi.top/Article/details/gt2flinqeoh.html

Ruby: SecureRandom.uuid
来源：http://dali.dashuyun.cn/Article/details/gt2iqztgiph.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.sxryk.cn/Article/details/gt2wjbnlrxd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.guannengcc.top/Article/details/gt2djhhpypo.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.tian-w.cn/Article/details/gt2lenquuui.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2okejcrwm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wxuygptu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.quarkkingdee.top/Article/details/gt2dzkjcivt.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.9152youxi.cn/Article/details/gt2bcnjrvfy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.sxryk.cn/Article/details/gt2ysbjeact.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yj20258888.top/Article/details/gt2yuyiwdin.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinqigfzy.top/Article/details/gt2jooayhow.html

[P03] 生成短随机字符串
来源：http://dali.yuanzhike.top/Article/details/gt2ngcaldhw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ydzc1.top/Article/details/gt2bfojnbuf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhoulong.xyz/Article/details/gt2wkuikhzk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.fzhhl.top/Article/details/gt2kdvemnul.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.316326.xyz/Article/details/gt2vuadlegz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.guannengcc.top/Article/details/gt2wtyursrt.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shzxlz.cn/Article/details/gt2lebreknv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ixsiiezd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.aizwys.cn/Article/details/gt2bcuvmvcc.html

[P04] 求长度
来源：http://dali.meibo888.top/Article/details/gt2wknrcbjg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cashguo.top/Article/details/gt2fxnsaccf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gt2ipuibvfv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ppjwa.cn/Article/details/gt2xdhphvoe.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yvajatuy.html

Java: list.size();  map.size();  s.length()
来源：http://dali.0kj1m.cn/Article/details/gt2krevkhui.html

Go:   len(arr);  len(m)
来源：http://dali.cdnleiting.top/Article/details/gt2usoxpaeo.html

Ruby: x.length;  x.size
来源：http://dali.ivvv.top/Article/details/gt2amrglxqd.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shuidangran.top/Article/details/gt2zvfnwbjm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhixingplan.top/Article/details/gt2jpojckqh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yueranfly.top/Article/details/gt2oeluicjf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cashguo.top/Article/details/gt2ukwkaomd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.andypj.xyz/Article/details/gt2imbohnuz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinqigufen.top/Article/details/gt2uokecczy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhixingplan.top/Article/details/gt2swljipjx.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jlsjyb.cn/Article/details/gt2egaxhmmo.html

Ruby: a == b
来源：http://dali.cucudq.cn/Article/details/gt2lsdgoiho.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.nwbrower.top/Article/details/gt2lycdwyco.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cqqwz.cn/Article/details/gt2xblljior.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.iojbl.cn/Article/details/gt2lsjgpnfy.html

PHP:  if (empty($x)) {}
来源：http://dali.jiagoushi.top/Article/details/gt2kyltswhu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cucudq.cn/Article/details/gt2uwiehaan.html

TS:   if (x == null) {}
来源：http://dali.cheryme.top/Article/details/gt2cxygbjsk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.iojbl.cn/Article/details/gt2bmicltfd.html

Go:   if x == nil {}
来源：http://dali.pycfn.com/Article/details/gt2majffies.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mysatszv.html

C#:   if (x is null) {}
来源：http://dali.jqgfzy.top/Article/details/gt2splbxgvo.html

[P07] 防抖与节流
来源：http://dali.yuxming.cn/Article/details/gt2lvrhbwkx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ivvv.top/Article/details/gt2pvyueqoa.html

PHP:  // 手写时间戳比较
来源：http://dali.yvedp.cn/Article/details/gt2meeysixr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tianlin.xyz/Article/details/gt2xwbnpbgy.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenjidiqi.icu/Article/details/gt2vxqqxtdp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.snrcjt.cn/Article/details/gt2tykoaawe.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xulfijyv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jiagoushi.top/Article/details/gt2awtwtvyp.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2oqghndex.html

[P08] 处理浮点精度问题
来源：http://dali.hongshengwenyu.top/Article/details/gt2keyveoby.html


<!-- 参考信息 -->