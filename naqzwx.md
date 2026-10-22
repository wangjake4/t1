代发 wailian999

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hongshengwenyu.top/Article/details/gt2mtuhenyu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nanxinkj.top/Article/details/gt2aorbeslu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnxiangtu.top/Article/details/gt2ogbpyefr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.aibaodan.cn/Article/details/gt2mmszogbl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yongpay.top/Article/details/gt2gbdolyrg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.birdmap.top/Article/details/gt2sgukaoww.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yonumen.top/Article/details/gt2qoasyepb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gogol.net.cn/Article/details/gt2azqsqfrp.html

[M04] 获取当前工作目录
来源：http://dali.daria6918.cn/Article/details/gt2axgjupnd.html

Py:   os.getcwd()
来源：http://dali.bjfxy.top/Article/details/gt2bnusizgk.html

PHP:  getcwd();
来源：http://dali.zdqjudy.top/Article/details/gt2rtkzdizx.html

JS:   process.cwd()
来源：http://dali.cqqwz.cn/Article/details/gt2mmssmpzz.html

TS:   process.cwd()
来源：http://dali.cdnleiting.top/Article/details/gt2zxrbbiyx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yuxming.cn/Article/details/gt2kwluibxx.html

Go:   os.Getwd()
来源：http://dali.ivvv.top/Article/details/gt2gcecfmwv.html

Ruby: Dir.pwd
来源：http://dali.9152youxi.cn/Article/details/gt2sqcuvapd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.tanke756.top/Article/details/gt2esqrzcwq.html

[M05] 设置退出码
来源：http://dali.sweek.top/Article/details/gt2emwwkbgv.html

Py:   sys.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2vjnhgrng.html

PHP:  exit(1);
来源：http://dali.tianlin.xyz/Article/details/gt2hdhszkym.html

JS:   process.exit(1)
来源：http://dali.shuidangran.top/Article/details/gt2bpkndacx.html

TS:   process.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ugcarcjc.html

Java: System.exit(1)
来源：http://dali.havefunace.top/Article/details/gt2sfjcirnl.html

Go:   os.Exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2ssfddxhw.html

Ruby: exit 1
来源：http://dali.hysaishi.cn/Article/details/gt2pmkecrsd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xziqi.cn/Article/details/gt2uvanuuzw.html

[M06] 向标准错误输出
来源：http://dali.yangfankeji.com/Article/details/gt2uonykxru.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xziqi.cn/Article/details/gt2ragfepcb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hammf.cn/Article/details/gt2aelurpjs.html

JS:   console.error("err")
来源：http://dali.jinqigufen.top/Article/details/gt2bxnuixev.html

TS:   console.error("err")
来源：http://dali.jqgfzy.top/Article/details/gt2yytjdyzt.html

Java: System.err.println("err")
来源：http://dali.xylfe.cn/Article/details/gt2duhbgyvd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cdnleiting.top/Article/details/gt2tlniyjry.html

Ruby: warn "err"
来源：http://dali.wangdashe.top/Article/details/gt2ufoegpit.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sysykeji.top/Article/details/gt2dcimksoq.html

[M07] 判断是否为主入口
来源：http://dali.chenlongwang.top/Article/details/gt2ntkpzwkz.html

Py:   if __name__ == "__main__":
来源：http://dali.hysaishi.cn/Article/details/gt2udlrzrgx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.smart0.xyz/Article/details/gt2mutypved.html

JS:   require.main === module
来源：http://dali.ydzc1.top/Article/details/gt2sskmwxur.html

TS:   require.main === module
来源：http://dali.svipenyu.cn/Article/details/gt2cfbpipor.html

Java: public static void main(String[] args)
来源：http://dali.birdmap.top/Article/details/gt2jlmrvpwq.html

Go:   func main()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tpielhgp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gotoacloud.top/Article/details/gt2zlrmamsj.html

C#:   static void Main(string[] args)
来源：http://dali.snrcjt.cn/Article/details/gt2fjtrcdwq.html

[M08] 获取系统与运行时信息
来源：http://dali.iojbl.cn/Article/details/gt2cydzganz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.iojbl.cn/Article/details/gt2jibjzhec.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.chenlongwang.top/Article/details/gt2tltwqkrb.html

JS:   process.platform;  process.version
来源：http://dali.iojbl.cn/Article/details/gt2zuvxfjlh.html

TS:   process.platform;  process.version
来源：http://dali.yuanzhike.top/Article/details/gt2igqkogip.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ydzc1.top/Article/details/gt2evbtieab.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.svipenyu.cn/Article/details/gt2mjcicdhr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.havefunace.top/Article/details/gt2amlydpkj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinqigufen.top/Article/details/gt2zjpyalwc.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2wxfhkppx.html

N. 数据结构与算法
来源：http://dali.yj20258888.top/Article/details/gt2tdduapbu.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2mrzdwgzf.html

[N01] 二分查找（有序数组）
来源：http://dali.xziqi.cn/Article/details/gt2zbgcicrl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.birdmap.top/Article/details/gt2brdkihlb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.birdmap.top/Article/details/gt2lexumwyq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cqqwz.cn/Article/details/gt2pyroaexq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fzhhl.top/Article/details/gt2esqdnyko.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gzhubu.top/Article/details/gt2ushirreu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gt2xahoehhe.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.feifeiyinyue.top/Article/details/gt2xojfizgp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.pycfn.com/Article/details/gt2cwuopaov.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yongpay.top/Article/details/gt2uabydsgm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ehwqpu.com/Article/details/gt2trwnxxne.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gt2bxumujdb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qyfntjnq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sysykeji.top/Article/details/gt2jizemlcp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.fengsongda.top/Article/details/gt2flbhcnxv.html

Go:   slices.Sort(arr)
来源：http://dali.ydzc1.top/Article/details/gt2gcnnucid.html

Ruby: arr.sort
来源：http://dali.yj202588.top/Article/details/gt2wutvijiu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhixingplan.top/Article/details/gt2agacijdi.html

[N03] 快速排序（分治示例）
来源：http://dali.zdqjudy.top/Article/details/gt2ocfnaerb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.haohaochexian.top/Article/details/gt2kavhxlwi.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ysmtzgzn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangdashe.top/Article/details/gt2lanmsshu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgufenzy.top/Article/details/gt2crgqmkgk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cheryme.top/Article/details/gt2uhjvisno.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.feifeiyinyue.top/Article/details/gt2ntihaldt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.smart0.xyz/Article/details/gt2jyjhgmej.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gogol.net.cn/Article/details/gt2ceyrgoix.html

[N04] 斐波那契数列
来源：http://dali.wangshuangyany.cn/Article/details/gt2ogzrdenc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sweek.top/Article/details/gt2mohiyems.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xziqi.cn/Article/details/gt2dlgthfyu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sufxvd.cn/Article/details/gt2xmexwysf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuetiantiany.cn/Article/details/gt2odimuswc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ehwqpu.com/Article/details/gt2addllpaw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yanxiufei.cn/Article/details/gt2ygibatyc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wndaxgyb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gt2bkszpvoj.html

[N05] 最大公约数
来源：http://dali.xinyue.icu/Article/details/gt2szxsydrz.html

Py:   math.gcd(a, b)
来源：http://dali.hammf.cn/Article/details/gt2ltbxdysp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.dashuyun.cn/Article/details/gt2jpdossnx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2topjblwq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aizwys.cn/Article/details/gt2gzinhfsm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.guowangkeji.top/Article/details/gt2oinfckwe.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.wangshuangyany.cn/Article/details/gt2zjuitomw.html

Ruby: a.gcd(b)
来源：http://dali.hysaishi.cn/Article/details/gt2jedktsfj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yuanzhike.top/Article/details/gt2zkvymbvo.html

[N06] 判断回文字符串
来源：http://dali.tanke756.top/Article/details/gt2kjfrngpd.html

Py:   s == s[::-1]
来源：http://dali.jqgufenzy.top/Article/details/gt2teeywjxr.html

PHP:  $s === strrev($s);
来源：http://dali.vqdsnc.cn/Article/details/gt2epqdvner.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yydigzuq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hammf.cn/Article/details/gt2zqykxbcw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.guannengcc.top/Article/details/gt2siajyviz.html

Go:   // 双指针从两端比较
来源：http://dali.fzhhl.top/Article/details/gt2mdxdfcqr.html

Ruby: s == s.reverse
来源：http://dali.pycfn.com/Article/details/gt2uoqwzchx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.feifeiyinyue.top/Article/details/gt2eyrrihlm.html

[N07] 两数之和（返回下标）
来源：http://dali.nanxuanxn.top/Article/details/gt2yvuzbibt.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shanyushiyangtech.top/Article/details/gt2twqcgtfw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zdqjudy.top/Article/details/gt2hmwgifyu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.smart0.xyz/Article/details/gt2clxyrjir.html

TS:   // 手写 Map<string, number>
来源：http://dali.9152youxi.cn/Article/details/gt2fsnaroau.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2osatvpgx.html

Go:   // 手写 map[int]int
来源：http://dali.fzhhl.top/Article/details/gt2xhxoppmo.html

Ruby: // 手写 Hash
来源：http://dali.zhoulong.xyz/Article/details/gt2nufdzfjk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gotoacloud.top/Article/details/gt2fsbsbwqk.html

[N08] 生成全排列
来源：http://dali.gotoacloud.top/Article/details/gt2hvjlwkqo.html

Py:   itertools.permutations(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2vhxuglll.html

PHP:  // 手写递归交换
来源：http://dali.ybcxt.top/Article/details/gt2nfmmifwv.html

JS:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gt2typnezik.html

TS:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gt2zxtrvnkv.html

Java: // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gt2zsjzdpzj.html

Go:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gt2mlgvjmfb.html

Ruby: arr.permutation.to_a
来源：http://dali.xziqi.cn/Article/details/gt2szwcxqad.html

C#:   // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gt2qjdlkjlf.html

[N09] 栈与队列
来源：http://dali.wangdashe.top/Article/details/gt2jlyoxvxk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yongpay.top/Article/details/gt2iirpbbhf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uhtfdbyd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zycfv.cn/Article/details/gt2hllhewzs.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.kuanghao11.cn/Article/details/gt2qforvhsg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.quarkkingdee.top/Article/details/gt2pfsxmjgo.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hammf.cn/Article/details/gt2bysejmqz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jiagoushi.top/Article/details/gt2yncnzcap.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.guowangkeji.top/Article/details/gt2tdiombko.html

[N10] 链表节点定义
来源：http://dali.jianghu66.top/Article/details/gt2gepwlbpm.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.guannengcc.top/Article/details/gt2rpswuybe.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinqigufen.top/Article/details/gt2rermsytd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jqgufenzy.top/Article/details/gt2ppcivier.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.chenjidiqi.icu/Article/details/gt2oifzdbyq.html

Java: class Node { int v; Node next; }
来源：http://dali.cucudq.cn/Article/details/gt2ccaseuux.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yongpay.top/Article/details/gt2qnzmaelj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.nwbrower.top/Article/details/gt2yvtplhak.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.dianchejie.cn/Article/details/gt2vsihtmpo.html

[N11] 二叉树中序遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zbtwnahf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhengqikj.top/Article/details/gt2kqubzryv.html

PHP:  // 手写递归函数
来源：http://dali.quarkkingdee.top/Article/details/gt2jueodwoc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hysaishi.cn/Article/details/gt2nfcmmlju.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.bjfxy.top/Article/details/gt2ytxwhsyq.html

Java: // 手写递归
来源：http://dali.xziqi.cn/Article/details/gt2sjrukhfw.html

Go:   // 手写递归
来源：http://dali.smart0.xyz/Article/details/gt2featgpea.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhixingplan.top/Article/details/gt2moldjqmu.html

C#:   // 手写递归
来源：http://dali.guowangkeji.top/Article/details/gt2anasbrby.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ynwpeqhj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yonumen.top/Article/details/gt2lbgblayy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shuidangran.top/Article/details/gt2uvszdosq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bybtvjoc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sufxvd.cn/Article/details/gt2mzgyfpbe.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guowangkeji.top/Article/details/gt2ixtrrdut.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cheryme.top/Article/details/gt2jsrkavog.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.nanxinkj.top/Article/details/gt2xypfmayf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nanxinkj.top/Article/details/gt2xwlzyewm.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2lqtohhpv.html

O. 并发与异步
来源：http://dali.zycfv.cn/Article/details/gt2mjaqwwkt.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2wpjumuhm.html

[O01] 启动一个线程
来源：http://dali.shanyushiyangtech.top/Article/details/gt2brwnlmwc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.quarkkingdee.top/Article/details/gt2vuvyakzd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2liweltwu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cucudq.cn/Article/details/gt2txdlwfsn.html

TS:   // 同 JS
来源：http://dali.cashguo.top/Article/details/gt2sfkhucex.html

Java: new Thread(() -> f()).start()
来源：http://dali.dashuyun.cn/Article/details/gt2yictwjbg.html

Go:   go f()
来源：http://dali.hnxiangtu.top/Article/details/gt2vvohqbff.html

Ruby: Thread.new { f }
来源：http://dali.guowangkeji.top/Article/details/gt2tvcntfkw.html

C#:   Task.Run(() => F());
来源：http://dali.smart0.xyz/Article/details/gt2yvhuxice.html

[O02] 使用线程池
来源：http://dali.hywenlv.cn/Article/details/gt2iirikmna.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jyoumei.cn/Article/details/gt2mwwhnwks.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ppjwa.cn/Article/details/gt2uhlcadlw.html

JS:   // worker_threads 线程池
来源：http://dali.chenzaomai.com/Article/details/gt2jcobeixg.html

TS:   // worker_threads 线程池
来源：http://dali.316326.xyz/Article/details/gt2snqsllic.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinqigfzy.top/Article/details/gt2lxkwxabt.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shangyingyoupin.top/Article/details/gt2afouktqi.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gogol.net.cn/Article/details/gt2bqcopqwd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.316326.xyz/Article/details/gt2qawtecmn.html

[O03] 加锁保护共享数据
来源：http://dali.ehwqpu.com/Article/details/gt2qxyxzzxo.html

Py:   with lock: shared += 1
来源：http://dali.fzhhl.top/Article/details/gt2yndsgcym.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gzhubu.top/Article/details/gt2qptbupvh.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ybcxt.top/Article/details/gt2xtcenxzd.html

TS:   // 同 JS
来源：http://dali.hysaishi.cn/Article/details/gt2cptwsejj.html

Java: synchronized (this) { shared++; }
来源：http://dali.nanxuanxn.top/Article/details/gt2ciqmrfjo.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ehwqpu.com/Article/details/gt2jqxngsgl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.iojbl.cn/Article/details/gt2crlbfnmn.html

C#:   lock (gate) { shared++; }
来源：http://dali.aibaodan.cn/Article/details/gt2pqezhwrn.html

[O04] 定义异步函数并等待
来源：http://dali.yueranfly.top/Article/details/gt2xlnnvlya.html

Py:   async def f():⏎    await g()
来源：http://dali.hongshengwenyu.top/Article/details/gt2pwnzlsgz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.sxryk.cn/Article/details/gt2eoavjgbu.html

JS:   async function f() { await g(); }
来源：http://dali.daxiang520.top/Article/details/gt2qgfurggc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xziqi.cn/Article/details/gt2nzhqvsvd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yvedp.cn/Article/details/gt2dkvqxuiw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sxryk.cn/Article/details/gt2varlehvf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.chenlongwang.top/Article/details/gt2kjbgbiac.html

C#:   async Task F() { await G(); }
来源：http://dali.fengsongda.top/Article/details/gt2zvwtrnca.html

[O05] 并发执行并等待全部完成
来源：http://dali.hongshengwenyu.top/Article/details/gt2ewvwjoob.html

Py:   asyncio.gather(*tasks)
来源：http://dali.vqdsnc.cn/Article/details/gt2ifsnndcn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.guannengcc.top/Article/details/gt2bxoiydqq.html

JS:   await Promise.all(tasks)
来源：http://dali.316326.xyz/Article/details/gt2whlvuxhc.html

TS:   await Promise.all(tasks)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ngdngtmh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hywenlv.cn/Article/details/gt2mmgsqwtz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhixingplan.top/Article/details/gt2qebgckht.html

Ruby: threads.map(&:join)
来源：http://dali.tian-w.cn/Article/details/gt2wxrydgxw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xinyue.icu/Article/details/gt2buohdsne.html

[O06] 使用进程池
来源：http://dali.dianchejie.cn/Article/details/gt2sqlxxfrv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.quarkkingdee.top/Article/details/gt2vqcjqjvg.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xuetiantiany.cn/Article/details/gt2smlldbjz.html

JS:   // child_process / cluster 模块
来源：http://dali.yuanzhike.top/Article/details/gt2wfmilqtb.html

TS:   // child_process / cluster 模块
来源：http://dali.kuanghao11.cn/Article/details/gt2ikbxobqt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ydzc1.top/Article/details/gt2itbtctsc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.smart0.xyz/Article/details/gt2dgudcrwd.html

Ruby: // fork 块
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ldkntxjt.html

C#:   Parallel.For
来源：http://dali.316326.xyz/Article/details/gt2vlflclck.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2foftjhdk.html

P. 常用工具函数
来源：http://dali.nanxinkj.top/Article/details/gt2nkoozqxf.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vktngghv.html

[P01] 生成 UUID
来源：http://dali.9152youxi.cn/Article/details/gt2dhtpnwud.html

Py:   str(uuid.uuid4())
来源：http://dali.jqgufenzy.top/Article/details/gt2pqbpcgwb.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hysaishi.cn/Article/details/gt2nvrcfxlz.html

JS:   crypto.randomUUID()
来源：http://dali.chenjidiqi.icu/Article/details/gt2zviyvzaf.html

TS:   crypto.randomUUID()
来源：http://dali.xuetiantiany.cn/Article/details/gt2htbqnboz.html

Java: UUID.randomUUID().toString()
来源：http://dali.yj202588.top/Article/details/gt2lbynzvgn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lyanrovm.html

Ruby: SecureRandom.uuid
来源：http://dali.wangdashe.top/Article/details/gt2awbjpvwl.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.pycfn.com/Article/details/gt2dsznkzfp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.birdmap.top/Article/details/gt2riwojtpt.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tugmnkek.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.snrcjt.cn/Article/details/gt2novglcae.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ppjwa.cn/Article/details/gt2dulbbati.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.daxiang520.top/Article/details/gt2wmxcpxhr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zpduykxn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gaohongyu789.top/Article/details/gt2xnsltftz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.chenzaomai.com/Article/details/gt2qsvyrqtl.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.aizwys.cn/Article/details/gt2pdwrdwtt.html

[P03] 生成短随机字符串
来源：http://dali.guowangkeji.top/Article/details/gt2woiodgsz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cdnleiting.top/Article/details/gt2uuotldxf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.birdmap.top/Article/details/gt2fkkigucu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj202588.top/Article/details/gt2snfnfcyi.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ybcxt.top/Article/details/gt2sxxauonp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.tianlin.xyz/Article/details/gt2ytcwrxre.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.pengpengdd.cyou/Article/details/gt2qwykpayr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.smart0.xyz/Article/details/gt2flakwdwm.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.svipenyu.cn/Article/details/gt2qzedoscv.html

[P04] 求长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sjnahphq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.guowangkeji.top/Article/details/gt2pqfyyjxr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gt2jucpsnwl.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hfpthk.cn/Article/details/gt2nrruvrdn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gzhubu.top/Article/details/gt2tilzrijx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jiagoushi.top/Article/details/gt2lxtqpotg.html

Go:   len(arr);  len(m)
来源：http://dali.fzhhl.top/Article/details/gt2kvkobytk.html

Ruby: x.length;  x.size
来源：http://dali.haohaochexian.top/Article/details/gt2jsxawpnj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yuanzhike.top/Article/details/gt2whrevwrw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.nanxinkj.top/Article/details/gt2jdogpyez.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.nanxinkj.top/Article/details/gt2efoihkwv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cucudq.cn/Article/details/gt2ghirozcx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.haohaochexian.top/Article/details/gt2nofchhkv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.haohaochexian.top/Article/details/gt2flrlgecr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.dashuyun.cn/Article/details/gt2bhvbgkrf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.daria6918.cn/Article/details/gt2cwypjztq.html

Ruby: a == b
来源：http://dali.meibo888.top/Article/details/gt2tjyggllp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.nanxuanxn.top/Article/details/gt2obehbsih.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yanxiufei.cn/Article/details/gt2ipflobus.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.bjfxy.top/Article/details/gt2oebegafh.html

PHP:  if (empty($x)) {}
来源：http://dali.daxiang520.top/Article/details/gt2zhldyzvm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.aizwys.cn/Article/details/gt2xavsgmlr.html

TS:   if (x == null) {}
来源：http://dali.0kj1m.cn/Article/details/gt2oshvxsqj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mrugzrxv.html

Go:   if x == nil {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2buufsthd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2drwvtwao.html

C#:   if (x is null) {}
来源：http://dali.tanke756.top/Article/details/gt2htzmkqsu.html

[P07] 防抖与节流
来源：http://dali.gaohongyu789.top/Article/details/gt2ubuqzavs.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yonumen.top/Article/details/gt2kzmtqvix.html

PHP:  // 手写时间戳比较
来源：http://dali.zhongyouzk.top/Article/details/gt2ultnxeft.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aapenlqq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhiwuduotai.top/Article/details/gt2jjxlbeja.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yangfankeji.com/Article/details/gt2boowfbtt.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhongyouzk.top/Article/details/gt2ptblozfl.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xinyue.icu/Article/details/gt2oxizatai.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.aibaodan.cn/Article/details/gt2kwfmurap.html

[P08] 处理浮点精度问题
来源：http://dali.pycfn.com/Article/details/gt2ojqugnaw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.kuanghao11.cn/Article/details/gt2ikvyzesn.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ydzc1.top/Article/details/gt2fcpreptn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ehwqpu.com/Article/details/gt2qwsqwdpb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.c1oappe.top/Article/details/gt2xabxcmzq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sysykeji.top/Article/details/gt2iaeylejk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ydzc1.top/Article/details/gt2guymsuug.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.mhx1999.top/Article/details/gt2rggpoyne.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yueranfly.top/Article/details/gt2ilmvxtru.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2uqzcnppv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yykacjrt.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2cuqavysa.html

[Q01] 创建表
来源：http://dali.yanxiufei.cn/Article/details/gt2muzmsrib.html


<!-- 参考信息 -->