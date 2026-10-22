代发 wailian999

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkqhixjgp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhoulong.xyz/Article/details/gtjmbyeggb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nwbrower.top/Article/details/gtzdesrbzm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cashguo.top/Article/details/gtqbqxstwp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yangfankeji.com/Article/details/gtubrufvwm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yuxming.cn/Article/details/gtlkbstanl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.birdmap.top/Article/details/gtnxvppkcc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jlsjyb.cn/Article/details/gtqfhswrgj.html

[M04] 获取当前工作目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcghehqvc.html

Py:   os.getcwd()
来源：http://dali.xuetiantiany.cn/Article/details/gtegpdxdwd.html

PHP:  getcwd();
来源：http://dali.snrcjt.cn/Article/details/gthiwgnist.html

JS:   process.cwd()
来源：http://dali.ppjwa.cn/Article/details/gthtdilpuk.html

TS:   process.cwd()
来源：http://dali.zycfv.cn/Article/details/gtzurnnqiq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.snrcjt.cn/Article/details/gtrwonjkiq.html

Go:   os.Getwd()
来源：http://dali.havefunace.top/Article/details/gthlosrazf.html

Ruby: Dir.pwd
来源：http://dali.9152youxi.cn/Article/details/gtxmfyxick.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinqigfzy.top/Article/details/gtlblkqrrn.html

[M05] 设置退出码
来源：http://dali.vqdsnc.cn/Article/details/gtlhtbjfwr.html

Py:   sys.exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gtapzrzdak.html

PHP:  exit(1);
来源：http://dali.jinqigfzy.top/Article/details/gtxvwdrhis.html

JS:   process.exit(1)
来源：http://dali.smart0.xyz/Article/details/gtvnaxiqqk.html

TS:   process.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gtoxdbpiwa.html

Java: System.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdyekfxtk.html

Go:   os.Exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtndkohdjf.html

Ruby: exit 1
来源：http://dali.cheryme.top/Article/details/gtttdxgsbd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nwbrower.top/Article/details/gtjhhkanue.html

[M06] 向标准错误输出
来源：http://dali.snrcjt.cn/Article/details/gtjpszzfcx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.chenlongwang.top/Article/details/gtzcmhrnno.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jyoumei.cn/Article/details/gtkkjluqrw.html

JS:   console.error("err")
来源：http://dali.andypj.xyz/Article/details/gtouumwrcb.html

TS:   console.error("err")
来源：http://dali.jqgufenzy.top/Article/details/gtqoyhdjai.html

Java: System.err.println("err")
来源：http://dali.mhx1999.top/Article/details/gtrsydbony.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sufxvd.cn/Article/details/gtigaurhjm.html

Ruby: warn "err"
来源：http://dali.hysaishi.cn/Article/details/gtoczyhmoh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.pycfn.com/Article/details/gtmwvtfbrx.html

[M07] 判断是否为主入口
来源：http://dali.pengpengdd.cyou/Article/details/gtmnatzeko.html

Py:   if __name__ == "__main__":
来源：http://dali.cqqwz.cn/Article/details/gtwvwcxecv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.meibo888.top/Article/details/gtbpmjiiku.html

JS:   require.main === module
来源：http://dali.316326.xyz/Article/details/gtwhlfquac.html

TS:   require.main === module
来源：http://dali.yangfankeji.com/Article/details/gtjyzorjqa.html

Java: public static void main(String[] args)
来源：http://dali.yj202588.top/Article/details/gtswbikjit.html

Go:   func main()
来源：http://dali.zdqjudy.top/Article/details/gtqrzqhlzg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.svipenyu.cn/Article/details/gtaasvbxlm.html

C#:   static void Main(string[] args)
来源：http://dali.jiagoushi.top/Article/details/gtbpfaezqb.html

[M08] 获取系统与运行时信息
来源：http://dali.wangshuangyany.cn/Article/details/gtvpxpgrfc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.fzhhl.top/Article/details/gtvgqlfqzm.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yangfankeji.com/Article/details/gtfuurosak.html

JS:   process.platform;  process.version
来源：http://dali.nwbrower.top/Article/details/gtlokirkek.html

TS:   process.platform;  process.version
来源：http://dali.shuidangran.top/Article/details/gtvkrvtnwg.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.dianchejie.cn/Article/details/gtlejoqcoc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.9152youxi.cn/Article/details/gtnihhnham.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yj20258888.top/Article/details/gtbmvaxqbc.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinghuilouyu.cn/Article/details/gtswcefojl.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtqibkvcrv.html

N. 数据结构与算法
来源：http://dali.zhixingplan.top/Article/details/gtmvcgrlsu.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtayxmifqf.html

[N01] 二分查找（有序数组）
来源：http://dali.hnxiangtu.top/Article/details/gtrcmxffut.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gtbryfcpgu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.chenzaomai.com/Article/details/gtebqruhea.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.316326.xyz/Article/details/gtwcfmexoq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ehwqpu.com/Article/details/gtcdmnqxay.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gtkeflpyuq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtukcdgmxb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.fzhhl.top/Article/details/gtopwkwlry.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtebmcnntc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xuetiantiany.cn/Article/details/gtfqxhymxt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ydzc1.top/Article/details/gtzwlfgecc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.havefunace.top/Article/details/gtnirdyxup.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shangyingyoupin.top/Article/details/gtdxikbugm.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.vqdsnc.cn/Article/details/gtujyhikem.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cdnleiting.top/Article/details/gtsdqhudbv.html

Go:   slices.Sort(arr)
来源：http://dali.zdqjudy.top/Article/details/gtzzrjndxy.html

Ruby: arr.sort
来源：http://dali.cashguo.top/Article/details/gttcnpdopc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.tian-w.cn/Article/details/gtazbjadnl.html

[N03] 快速排序（分治示例）
来源：http://dali.hnxiangtu.top/Article/details/gtedzktpkv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.bjfxy.top/Article/details/gtwqzprdpn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.9152youxi.cn/Article/details/gtfggdvaqg.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jiagoushi.top/Article/details/gtwypbrpkq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj202588.top/Article/details/gtspadhmjh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jlsjyb.cn/Article/details/gttgwsyepq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.wangdashe.top/Article/details/gtepvulwwc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sweek.top/Article/details/gtkbdsnayi.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yanxiufei.cn/Article/details/gtahbbeaha.html

[N04] 斐波那契数列
来源：http://dali.aibaodan.cn/Article/details/gtieduzlwv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmpdnpmjy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ehwqpu.com/Article/details/gtxkzpflpd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guannengcc.top/Article/details/gticuzxwza.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnxiangtu.top/Article/details/gtqattykhs.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yvedp.cn/Article/details/gtfylacrpo.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sufxvd.cn/Article/details/gtsziqyruf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jianghu66.top/Article/details/gtjmyzeirc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gthdtebpgt.html

[N05] 最大公约数
来源：http://dali.shzxlz.cn/Article/details/gtjmnsqpqt.html

Py:   math.gcd(a, b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpgrdfmxl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hammf.cn/Article/details/gtgymycroq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hammf.cn/Article/details/gtdpocihlf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhongyouzk.top/Article/details/gtbvvkdexv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yongpay.top/Article/details/gtwpvirefm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnoemmowm.html

Ruby: a.gcd(b)
来源：http://dali.sweek.top/Article/details/gtazoglhbo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hnqzz.top/Article/details/gtveqgmphs.html

[N06] 判断回文字符串
来源：http://dali.jianghu66.top/Article/details/gtleknohyr.html

Py:   s == s[::-1]
来源：http://dali.meibo888.top/Article/details/gtswidahcu.html

PHP:  $s === strrev($s);
来源：http://dali.chenlongwang.top/Article/details/gtsasixjgh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gtahgqndes.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gtnebsdrqo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.mhx1999.top/Article/details/gtbubjgdbw.html

Go:   // 双指针从两端比较
来源：http://dali.hywenlv.cn/Article/details/gtvwyhpphd.html

Ruby: s == s.reverse
来源：http://dali.andypj.xyz/Article/details/gtkzaueocn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinqigufen.top/Article/details/gtjdsmnigr.html

[N07] 两数之和（返回下标）
来源：http://dali.ivvv.top/Article/details/gtadlwnepm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.fengsongda.top/Article/details/gtklsyzord.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.daria6918.cn/Article/details/gtmcltvjxh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gtdwodcmsu.html

TS:   // 手写 Map<string, number>
来源：http://dali.fzhhl.top/Article/details/gtuiludrgz.html

Java: // 手写 HashMap
来源：http://dali.jinghuilouyu.cn/Article/details/gtpcphwrbb.html

Go:   // 手写 map[int]int
来源：http://dali.guannengcc.top/Article/details/gtyrpwwskk.html

Ruby: // 手写 Hash
来源：http://dali.daxiang520.top/Article/details/gtrrujudws.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoevilhjr.html

[N08] 生成全排列
来源：http://dali.zhixingplan.top/Article/details/gtwfytqcpa.html

Py:   itertools.permutations(arr)
来源：http://dali.fengsongda.top/Article/details/gtdcfeixmv.html

PHP:  // 手写递归交换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtactpwsgr.html

JS:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gthnoutjxq.html

TS:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gtqkxppraq.html

Java: // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gtjeoyhtev.html

Go:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpdbmkoid.html

Ruby: arr.permutation.to_a
来源：http://dali.jlsjyb.cn/Article/details/gtbiwihahq.html

C#:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gthfvzmgsq.html

[N09] 栈与队列
来源：http://dali.hongshengwenyu.top/Article/details/gtwdbhctfr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.smart0.xyz/Article/details/gtbyfozlyr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.nanxuanxn.top/Article/details/gtmymsqgni.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwksmzktv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.bjfxy.top/Article/details/gtvyrnzkyy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cqqwz.cn/Article/details/gtsyeigvhm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinyuanbaomall.cn/Article/details/gthgualfmq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yj202588.top/Article/details/gtanobaqyn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.tian-w.cn/Article/details/gttwbnbxbz.html

[N10] 链表节点定义
来源：http://dali.ivvv.top/Article/details/gtmwqqqwze.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hnqzz.top/Article/details/gtkvnwmtlr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gzhubu.top/Article/details/gtneiuvxcx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shzxlz.cn/Article/details/gtzsqpknmz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yj202588.top/Article/details/gtgffwbcra.html

Java: class Node { int v; Node next; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpdmeoxli.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.aizwys.cn/Article/details/gttauvpowb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.meibo888.top/Article/details/gtkexgtcyr.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.havefunace.top/Article/details/gtiqijuamb.html

[N11] 二叉树中序遍历
来源：http://dali.andypj.xyz/Article/details/gtebbafigg.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinqigufen.top/Article/details/gtowetpyem.html

PHP:  // 手写递归函数
来源：http://dali.yanxiufei.cn/Article/details/gtoqqbphzd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzspqymfr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuxming.cn/Article/details/gtgmcomkif.html

Java: // 手写递归
来源：http://dali.hfpthk.cn/Article/details/gtwwgavojx.html

Go:   // 手写递归
来源：http://dali.zhongyouzk.top/Article/details/gtihnbmhmw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yj20258888.top/Article/details/gtdwtjxivh.html

C#:   // 手写递归
来源：http://dali.hysaishi.cn/Article/details/gtokvhqbns.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cdnleiting.top/Article/details/gtapecqqsd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.quarkkingdee.top/Article/details/gtduakwiok.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.pengpengdd.cyou/Article/details/gthqvfzdpe.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shuidangran.top/Article/details/gtcezfyfdg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cucudq.cn/Article/details/gtfhxxidch.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sysykeji.top/Article/details/gtpjnlwpyt.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yuanzhike.top/Article/details/gtqonperxw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.haohaochexian.top/Article/details/gtqcbxvkjw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.c1oappe.top/Article/details/gtnfbrcbjj.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtvpswvhni.html

O. 并发与异步
来源：http://dali.guannengcc.top/Article/details/gtyyokvopc.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtqrhxsbyf.html

[O01] 启动一个线程
来源：http://dali.jinqigfzy.top/Article/details/gtazicfcxe.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yuanzhike.top/Article/details/gtsdlrixik.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.redwolf501.top/Article/details/gtfohdicmp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gaohongyu789.top/Article/details/gteuxsadut.html

TS:   // 同 JS
来源：http://dali.hammf.cn/Article/details/gtcgdvrbsb.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhiwuduotai.top/Article/details/gtivxvieyl.html

Go:   go f()
来源：http://dali.feifeiyinyue.top/Article/details/gtodunsbyp.html

Ruby: Thread.new { f }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzwrvxtsv.html

C#:   Task.Run(() => F());
来源：http://dali.chenzaomai.com/Article/details/gthjrinzyk.html

[O02] 使用线程池
来源：http://dali.ehwqpu.com/Article/details/gtxehnfwxb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.wangshuangyany.cn/Article/details/gtirrztxpx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.nanxuanxn.top/Article/details/gtpngrzeaa.html

JS:   // worker_threads 线程池
来源：http://dali.sweek.top/Article/details/gtxqdwdthw.html

TS:   // worker_threads 线程池
来源：http://dali.xziqi.cn/Article/details/gtoidxpfsy.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.pycfn.com/Article/details/gtmgplctzm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yueranfly.top/Article/details/gtcuoeiygf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gogol.net.cn/Article/details/gtspzgiayv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhixingplan.top/Article/details/gtaiyobeza.html

[O03] 加锁保护共享数据
来源：http://dali.jiagoushi.top/Article/details/gtlelcnvnu.html

Py:   with lock: shared += 1
来源：http://dali.jlsjyb.cn/Article/details/gtmowfoxdm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gtoqalynns.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yuxming.cn/Article/details/gtdvpvvhvn.html

TS:   // 同 JS
来源：http://dali.yj20258888.top/Article/details/gtcqzrcskt.html

Java: synchronized (this) { shared++; }
来源：http://dali.shangyingyoupin.top/Article/details/gtccwsjcbf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqqfohwzu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ppjwa.cn/Article/details/gtfnxhuxpv.html

C#:   lock (gate) { shared++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlfvyfuhb.html

[O04] 定义异步函数并等待
来源：http://dali.jqgufenzy.top/Article/details/gthihdfmrp.html

Py:   async def f():⏎    await g()
来源：http://dali.hysaishi.cn/Article/details/gtvhzdlzgt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.nanxuanxn.top/Article/details/gtqunirpqz.html

JS:   async function f() { await g(); }
来源：http://dali.cheryme.top/Article/details/gtayobwsco.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpfkkmxzc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhoulong.xyz/Article/details/gtbebwckni.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yongpay.top/Article/details/gtrtaqprrx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhongyouzk.top/Article/details/gtrqnrgvie.html

C#:   async Task F() { await G(); }
来源：http://dali.cucudq.cn/Article/details/gtowblyllz.html

[O05] 并发执行并等待全部完成
来源：http://dali.yueranfly.top/Article/details/gtplouhxgf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yj20258.top/Article/details/gtersqtgti.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hammf.cn/Article/details/gtaadjmdkn.html

JS:   await Promise.all(tasks)
来源：http://dali.chenjidiqi.icu/Article/details/gtwltowynq.html

TS:   await Promise.all(tasks)
来源：http://dali.nanxinkj.top/Article/details/gtjblgwtnl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.nanxuanxn.top/Article/details/gthcvvwhiv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hnqzz.top/Article/details/gttegwxhxg.html

Ruby: threads.map(&:join)
来源：http://dali.yj20258888.top/Article/details/gtdqltndss.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ydzc1.top/Article/details/gtdtgatlta.html

[O06] 使用进程池
来源：http://dali.birdmap.top/Article/details/gthupofioh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jqgfzy.top/Article/details/gtikazqfrs.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cqqwz.cn/Article/details/gtiydvszij.html

JS:   // child_process / cluster 模块
来源：http://dali.tian-w.cn/Article/details/gtupqkwaaw.html

TS:   // child_process / cluster 模块
来源：http://dali.sweek.top/Article/details/gtijjatift.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jinghuilouyu.cn/Article/details/gtfnnvrqgv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hnqzz.top/Article/details/gtiloburwb.html

Ruby: // fork 块
来源：http://dali.aibaodan.cn/Article/details/gtxzwuwnup.html

C#:   Parallel.For
来源：http://dali.meibo888.top/Article/details/gtqokgsixn.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gthhglxivx.html

P. 常用工具函数
来源：http://dali.bjfxy.top/Article/details/gtqiyoxtoe.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtxlscffsg.html

[P01] 生成 UUID
来源：http://dali.bjfxy.top/Article/details/gtkrnoqglx.html

Py:   str(uuid.uuid4())
来源：http://dali.cdnleiting.top/Article/details/gticmkwsih.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.gaohongyu789.top/Article/details/gtpbqjzyri.html

JS:   crypto.randomUUID()
来源：http://dali.haohaochexian.top/Article/details/gtnyvehzlu.html

TS:   crypto.randomUUID()
来源：http://dali.jlsjyb.cn/Article/details/gteexftexs.html

Java: UUID.randomUUID().toString()
来源：http://dali.nwbrower.top/Article/details/gtzdgxdgom.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hfpthk.cn/Article/details/gtxrfllksa.html

Ruby: SecureRandom.uuid
来源：http://dali.fzhhl.top/Article/details/gtrpuyaiiu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jlsjyb.cn/Article/details/gtcegirxlj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yongpay.top/Article/details/gthlssxwgr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gogol.net.cn/Article/details/gtsbcltmuf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hnxiangtu.top/Article/details/gtxiilgufj.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.andypj.xyz/Article/details/gtgwdabrdq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinqigfzy.top/Article/details/gtytqnegta.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.andypj.xyz/Article/details/gtvddnfqvq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gzhubu.top/Article/details/gtimftsscm.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xuanzx.com/Article/details/gtbwmesxwd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ivvv.top/Article/details/gtjctscdqw.html

[P03] 生成短随机字符串
来源：http://dali.hysaishi.cn/Article/details/gtunfwosdk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xuetiantiany.cn/Article/details/gtcfxjyuuk.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jinqigufen.top/Article/details/gtcoopipfv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258.top/Article/details/gtfsrgrdhv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtektisuvo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jyoumei.cn/Article/details/gtkojtlhra.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hongshengwenyu.top/Article/details/gtqvtptzpz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.dianchejie.cn/Article/details/gthsjsojht.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.guowangkeji.top/Article/details/gterwirfez.html

[P04] 求长度
来源：http://dali.shangyingyoupin.top/Article/details/gtshzarjqa.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.mhx1999.top/Article/details/gtsdqhivkj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gtyhueyspu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tianlin.xyz/Article/details/gtdpdfnuwz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.aizwys.cn/Article/details/gtrtualbid.html

Java: list.size();  map.size();  s.length()
来源：http://dali.snrcjt.cn/Article/details/gtyjxoctfb.html

Go:   len(arr);  len(m)
来源：http://dali.cashguo.top/Article/details/gtyqewqkqc.html

Ruby: x.length;  x.size
来源：http://dali.yj20258.top/Article/details/gttoznwuhl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shanyushiyangtech.top/Article/details/gtmpphyprl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.feifeiyinyue.top/Article/details/gtqzyfgbme.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hnqzz.top/Article/details/gttfgjdqen.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jqgfzy.top/Article/details/gthdofvwpv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jianghu66.top/Article/details/gtuodmhymr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.316326.xyz/Article/details/gtztqgatvs.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.chenjidiqi.icu/Article/details/gtxgnioxpn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyahdmqpe.html

Ruby: a == b
来源：http://dali.yj20258888.top/Article/details/gthbyovjto.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jqgfzy.top/Article/details/gtlyvrgkir.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yueranfly.top/Article/details/gtarxnaqvm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.nwbrower.top/Article/details/gtvobwrhyj.html

PHP:  if (empty($x)) {}
来源：http://dali.hnxiangtu.top/Article/details/gtalhbhqkh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shanyushiyangtech.top/Article/details/gtufumbbbm.html

TS:   if (x == null) {}
来源：http://dali.316326.xyz/Article/details/gtdujfzwjz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.aibaodan.cn/Article/details/gtiheagnxq.html

Go:   if x == nil {}
来源：http://dali.gotoacloud.top/Article/details/gtkwxvjcfv.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.daria6918.cn/Article/details/gtlnbrkqyn.html

C#:   if (x is null) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtkrfylhje.html

[P07] 防抖与节流
来源：http://dali.cucudq.cn/Article/details/gtlbeyyjip.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhixingplan.top/Article/details/gtemosuqpa.html

PHP:  // 手写时间戳比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gthbtpjhie.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258.top/Article/details/gtupkhfzsf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenjidiqi.icu/Article/details/gttisgywrt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yonumen.top/Article/details/gtcfbvawkh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shuidangran.top/Article/details/gtogiwkgqw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hnqzz.top/Article/details/gtvixhfvwm.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrpfebftk.html

[P08] 处理浮点精度问题
来源：http://dali.svipenyu.cn/Article/details/gtzkthhqtq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhixingplan.top/Article/details/gtpzlkvkro.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ehwqpu.com/Article/details/gtzfrlmipd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yanxiufei.cn/Article/details/gtzlgslqqt.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.wangdashe.top/Article/details/gtjctqjxqa.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xuanzx.com/Article/details/gtvgcdqxow.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.nwbrower.top/Article/details/gtmybazdpl.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtljubymnd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jinqigufen.top/Article/details/gtluckkayb.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtejthfofu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.kuanghao11.cn/Article/details/gtxczynjvw.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gttfarbymd.html

[Q01] 创建表
来源：http://dali.yanxiufei.cn/Article/details/gtnepvvzqr.html


<!-- 参考信息 -->