代发 wailian999

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gt2jfnyiphg.html

Ruby: ENV["HOME"]
来源：http://dali.redwolf501.top/Article/details/gt2jijcggwo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gt2ojtqnzfo.html

[M03] 执行外部命令
来源：http://dali.xuanzx.com/Article/details/gt2xklvmhmc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.redwolf501.top/Article/details/gt2gallpgcj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tianlin.xyz/Article/details/gt2ifirrfph.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yueranfly.top/Article/details/gt2vavvapgo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tanke756.top/Article/details/gt2ncxzzjqb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ydzc1.top/Article/details/gt2wcrdhkwt.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vdnchxtp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cqqwz.cn/Article/details/gt2thunvoep.html

C#:   Process.Start("ls", "-l");
来源：http://dali.andypj.xyz/Article/details/gt2fjsssmvd.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ydswpvor.html

Py:   os.getcwd()
来源：http://dali.wangshuangyany.cn/Article/details/gt2stwvcbdz.html

PHP:  getcwd();
来源：http://dali.iojbl.cn/Article/details/gt2uckpzuuk.html

JS:   process.cwd()
来源：http://dali.jiagoushi.top/Article/details/gt2yizftnbm.html

TS:   process.cwd()
来源：http://dali.zhengqikj.top/Article/details/gt2glymieey.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.pycfn.com/Article/details/gt2kmphgoin.html

Go:   os.Getwd()
来源：http://dali.xylfe.cn/Article/details/gt2grfohufn.html

Ruby: Dir.pwd
来源：http://dali.mhx1999.top/Article/details/gt2ofuzcvqf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.snrcjt.cn/Article/details/gt2iwverqsy.html

[M05] 设置退出码
来源：http://dali.mhx1999.top/Article/details/gt2uiezteuz.html

Py:   sys.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2snyohtwt.html

PHP:  exit(1);
来源：http://dali.0kj1m.cn/Article/details/gt2ueggziur.html

JS:   process.exit(1)
来源：http://dali.ybcxt.top/Article/details/gt2fwenqrvs.html

TS:   process.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gt2zgtxcfph.html

Java: System.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gt2lzzeobom.html

Go:   os.Exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2whkzywiw.html

Ruby: exit 1
来源：http://dali.zycfv.cn/Article/details/gt2obodzahm.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhongyouzk.top/Article/details/gt2hhnckaxa.html

[M06] 向标准错误输出
来源：http://dali.wangshuangyany.cn/Article/details/gt2tsosskof.html

Py:   print("err", file=sys.stderr)
来源：http://dali.wangdashe.top/Article/details/gt2hdacvirg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yongpay.top/Article/details/gt2foskwuro.html

JS:   console.error("err")
来源：http://dali.cqqwz.cn/Article/details/gt2fxkgtlsb.html

TS:   console.error("err")
来源：http://dali.shzxlz.cn/Article/details/gt2htpkdqzb.html

Java: System.err.println("err")
来源：http://dali.yuanzhike.top/Article/details/gt2sohydwxd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xuanzx.com/Article/details/gt2qmrpgouj.html

Ruby: warn "err"
来源：http://dali.ydzc1.top/Article/details/gt2ehprcgkg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xyhzxnmr.html

[M07] 判断是否为主入口
来源：http://dali.jinghuilouyu.cn/Article/details/gt2biggbgtn.html

Py:   if __name__ == "__main__":
来源：http://dali.shzxlz.cn/Article/details/gt2uvoisooi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinqigufen.top/Article/details/gt2wwurkjsm.html

JS:   require.main === module
来源：http://dali.hfpthk.cn/Article/details/gt2vxmlpifi.html

TS:   require.main === module
来源：http://dali.gaohongyu789.top/Article/details/gt2izsdfxsd.html

Java: public static void main(String[] args)
来源：http://dali.hywenlv.cn/Article/details/gt2clbzpjmr.html

Go:   func main()
来源：http://dali.yongpay.top/Article/details/gt2hltzfyjl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jiagoushi.top/Article/details/gt2dxuhsjoy.html

C#:   static void Main(string[] args)
来源：http://dali.jqgfzy.top/Article/details/gt2coqrtsbx.html

[M08] 获取系统与运行时信息
来源：http://dali.snrcjt.cn/Article/details/gt2zarnmsyd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sarmffet.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hywenlv.cn/Article/details/gt2foszohai.html

JS:   process.platform;  process.version
来源：http://dali.hywenlv.cn/Article/details/gt2lhgpvtir.html

TS:   process.platform;  process.version
来源：http://dali.316326.xyz/Article/details/gt2rpnhokre.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.0kj1m.cn/Article/details/gt2afhqmdya.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jiagoushi.top/Article/details/gt2ftuadymh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yanxiufei.cn/Article/details/gt2jhfunouc.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ppjwa.cn/Article/details/gt2uupwschb.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2teigasdy.html

N. 数据结构与算法
来源：http://dali.svipenyu.cn/Article/details/gt2azbrqjka.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2wrtcifqj.html

[N01] 二分查找（有序数组）
来源：http://dali.dashuyun.cn/Article/details/gt2idciwahk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hnqzz.top/Article/details/gt2icphgpox.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xziqi.cn/Article/details/gt2wfblfnce.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tianlin.xyz/Article/details/gt2beowtwee.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cqqwz.cn/Article/details/gt2uzrutgod.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2aoqkggay.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gt2rwudpfhx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xylfe.cn/Article/details/gt2xysasimm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gt2neylaiqr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.snrcjt.cn/Article/details/gt2ddsahwgs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenlongwang.top/Article/details/gt2kqubccqf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhongyouzk.top/Article/details/gt2mgmdwprd.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gt2eorkelhj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj202588.top/Article/details/gt2uxmhlzgs.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.svipenyu.cn/Article/details/gt2fcuxttak.html

Go:   slices.Sort(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2bkaeetyo.html

Ruby: arr.sort
来源：http://dali.haohaochexian.top/Article/details/gt2dzqijdmo.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ydzc1.top/Article/details/gt2gwjwuoup.html

[N03] 快速排序（分治示例）
来源：http://dali.shangyingyoupin.top/Article/details/gt2rlphanna.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jyoumei.cn/Article/details/gt2kjqttqjh.html

PHP:  // 递归实现，或用 usort
来源：http://dali.wangshuangyany.cn/Article/details/gt2wnwhjduk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sysykeji.top/Article/details/gt2cfiofttv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.havefunace.top/Article/details/gt2qtuorxxp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sxryk.cn/Article/details/gt2iaonznmh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.tian-w.cn/Article/details/gt2acbuhoyc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2moihjvdd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.daxiang520.top/Article/details/gt2muxoflxz.html

[N04] 斐波那契数列
来源：http://dali.shuidangran.top/Article/details/gt2wlrbxftj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yuxming.cn/Article/details/gt2vamdbmkh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhengqikj.top/Article/details/gt2lyzpjeox.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daria6918.cn/Article/details/gt2dlqroamo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yongpay.top/Article/details/gt2rklijsyt.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xlmlpxtx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.aibaodan.cn/Article/details/gt2mgruipmc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jianghu66.top/Article/details/gt2cvszacnt.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gt2ufqbsvmi.html

[N05] 最大公约数
来源：http://dali.jlsjyb.cn/Article/details/gt2vftzvzmk.html

Py:   math.gcd(a, b)
来源：http://dali.xylfe.cn/Article/details/gt2jtcmgcby.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yangfankeji.com/Article/details/gt2csdrwoeo.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qizvbezx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gogol.net.cn/Article/details/gt2uycwtxre.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yonumen.top/Article/details/gt2jkyasfcf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.vqdsnc.cn/Article/details/gt2bphchyjn.html

Ruby: a.gcd(b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qdohgrfx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yueranfly.top/Article/details/gt2foqqssyi.html

[N06] 判断回文字符串
来源：http://dali.yvedp.cn/Article/details/gt2hvnoycno.html

Py:   s == s[::-1]
来源：http://dali.quarkkingdee.top/Article/details/gt2elpboawq.html

PHP:  $s === strrev($s);
来源：http://dali.hysaishi.cn/Article/details/gt2tdldcnut.html

JS:   s === [...s].reverse().join("")
来源：http://dali.vqdsnc.cn/Article/details/gt2hjkvwesx.html

TS:   s === [...s].reverse().join("")
来源：http://dali.fzhhl.top/Article/details/gt2tuwopxmw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.nanxinkj.top/Article/details/gt2akokezxp.html

Go:   // 双指针从两端比较
来源：http://dali.wangshuangyany.cn/Article/details/gt2hvwzbgss.html

Ruby: s == s.reverse
来源：http://dali.sxryk.cn/Article/details/gt2lacehigm.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yvedp.cn/Article/details/gt2rfsrrfwz.html

[N07] 两数之和（返回下标）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2scwfcqif.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.316326.xyz/Article/details/gt2yowsrufi.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cashguo.top/Article/details/gt2qpwmudes.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinqigufen.top/Article/details/gt2jqbjprng.html

TS:   // 手写 Map<string, number>
来源：http://dali.gaohongyu789.top/Article/details/gt2rkrpzrce.html

Java: // 手写 HashMap
来源：http://dali.jinqigufen.top/Article/details/gt2bnwdkymm.html

Go:   // 手写 map[int]int
来源：http://dali.guannengcc.top/Article/details/gt2mmzlcfry.html

Ruby: // 手写 Hash
来源：http://dali.ppjwa.cn/Article/details/gt2akmfhujt.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.daxiang520.top/Article/details/gt2yfduvfwa.html

[N08] 生成全排列
来源：http://dali.tanke756.top/Article/details/gt2xltrbgum.html

Py:   itertools.permutations(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2cqoqhith.html

PHP:  // 手写递归交换
来源：http://dali.zdqjudy.top/Article/details/gt2artbcfjy.html

JS:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gt2gmrspkcu.html

TS:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gt2baaekidz.html

Java: // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gt2krangkpj.html

Go:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gt2fvaskhzr.html

Ruby: arr.permutation.to_a
来源：http://dali.pengpengdd.cyou/Article/details/gt2gaaferzn.html

C#:   // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gt2cswoumao.html

[N09] 栈与队列
来源：http://dali.yvedp.cn/Article/details/gt2measpwds.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yuxming.cn/Article/details/gt2drcyxxtx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gaohongyu789.top/Article/details/gt2kqvbksch.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hwfpqljs.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ydzc1.top/Article/details/gt2gdztkgqi.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.chenzaomai.com/Article/details/gt2wmyxzarh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xuetiantiany.cn/Article/details/gt2lrgohows.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gt2xrhydycu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.tianlin.xyz/Article/details/gt2hyetwfgs.html

[N10] 链表节点定义
来源：http://dali.gotoacloud.top/Article/details/gt2zxdtclot.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ehwqpu.com/Article/details/gt2mtuiraes.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.birdmap.top/Article/details/gt2omrckzyc.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.nanxuanxn.top/Article/details/gt2xzpwampn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cucudq.cn/Article/details/gt2ojzkmfcu.html

Java: class Node { int v; Node next; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wruonaxd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.snrcjt.cn/Article/details/gt2uopnpura.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.snrcjt.cn/Article/details/gt2uozyvycn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.bjfxy.top/Article/details/gt2oibweaje.html

[N11] 二叉树中序遍历
来源：http://dali.yongpay.top/Article/details/gt2lalkgkyh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shuidangran.top/Article/details/gt2bkaieyuh.html

PHP:  // 手写递归函数
来源：http://dali.jinqigfzy.top/Article/details/gt2eczcnjlj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pengpengdd.cyou/Article/details/gt2ambkclup.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tianlin.xyz/Article/details/gt2orlplgmp.html

Java: // 手写递归
来源：http://dali.ehwqpu.com/Article/details/gt2tozeaaxt.html

Go:   // 手写递归
来源：http://dali.tanke756.top/Article/details/gt2sjgepocz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yvedp.cn/Article/details/gt2ohkykdtx.html

C#:   // 手写递归
来源：http://dali.hnqzz.top/Article/details/gt2uqhzixzf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.aibaodan.cn/Article/details/gt2usaszozs.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jqgufenzy.top/Article/details/gt2pordvyzx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xuanzx.com/Article/details/gt2nsfijdop.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangshuangyany.cn/Article/details/gt2soehofca.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shangyingyoupin.top/Article/details/gt2bpeqdhvy.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hammf.cn/Article/details/gt2kjbkmdlr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hnxiangtu.top/Article/details/gt2qbfyyjer.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.redwolf501.top/Article/details/gt2tydqisbv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yongpay.top/Article/details/gt2swfptqdm.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2ykrjtgpj.html

O. 并发与异步
来源：http://dali.ydzc1.top/Article/details/gt2hjvnmimc.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2cyjjwgnd.html

[O01] 启动一个线程
来源：http://dali.sysykeji.top/Article/details/gt2crkenguu.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ubmlplnq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zycfv.cn/Article/details/gt2adnmqeac.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lgizdwim.html

TS:   // 同 JS
来源：http://dali.snrcjt.cn/Article/details/gt2pndrjzft.html

Java: new Thread(() -> f()).start()
来源：http://dali.birdmap.top/Article/details/gt2hqmifcex.html

Go:   go f()
来源：http://dali.aizwys.cn/Article/details/gt2ofxrzjub.html

Ruby: Thread.new { f }
来源：http://dali.bjfxy.top/Article/details/gt2fndgypji.html

C#:   Task.Run(() => F());
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2trphxtaa.html

[O02] 使用线程池
来源：http://dali.iojbl.cn/Article/details/gt2luukontl.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yanxiufei.cn/Article/details/gt2ufqjgijj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hongshengwenyu.top/Article/details/gt2nnbudkcr.html

JS:   // worker_threads 线程池
来源：http://dali.shzxlz.cn/Article/details/gt2ccpjfgub.html

TS:   // worker_threads 线程池
来源：http://dali.c1oappe.top/Article/details/gt2fwvkbpkx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yangfankeji.com/Article/details/gt2zaolsswr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yj202588.top/Article/details/gt2enjrhecv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gotoacloud.top/Article/details/gt2syhcpjco.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.nwbrower.top/Article/details/gt2atrtyjju.html

[O03] 加锁保护共享数据
来源：http://dali.jiagoushi.top/Article/details/gt2exnucyzq.html

Py:   with lock: shared += 1
来源：http://dali.ybcxt.top/Article/details/gt2hvknpwxs.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.chenjidiqi.icu/Article/details/gt2sobyhhmj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.snrcjt.cn/Article/details/gt2mxhaqmuw.html

TS:   // 同 JS
来源：http://dali.feifeiyinyue.top/Article/details/gt2nctcrcvo.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2abilxgrz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yj20258888.top/Article/details/gt2zmyktvsu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yueranfly.top/Article/details/gt2dqdrtupw.html

C#:   lock (gate) { shared++; }
来源：http://dali.daria6918.cn/Article/details/gt2bexonlqn.html

[O04] 定义异步函数并等待
来源：http://dali.sweek.top/Article/details/gt2majbwacu.html

Py:   async def f():⏎    await g()
来源：http://dali.tanke756.top/Article/details/gt2cdizxwzr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinqigufen.top/Article/details/gt2bvttcfdn.html

JS:   async function f() { await g(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2txcvryla.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenlongwang.top/Article/details/gt2ttdkogle.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cheryme.top/Article/details/gt2itqylwdt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yuxming.cn/Article/details/gt2jyfhhqje.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.fzhhl.top/Article/details/gt2mhmwfraa.html

C#:   async Task F() { await G(); }
来源：http://dali.iojbl.cn/Article/details/gt2ymfnquyf.html

[O05] 并发执行并等待全部完成
来源：http://dali.chenjidiqi.icu/Article/details/gt2yydsyfaq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zdqjudy.top/Article/details/gt2uinblehy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gzhubu.top/Article/details/gt2terdxyuo.html

JS:   await Promise.all(tasks)
来源：http://dali.sxryk.cn/Article/details/gt2tlnrqjqi.html

TS:   await Promise.all(tasks)
来源：http://dali.chenzaomai.com/Article/details/gt2cvbbgjqq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jyoumei.cn/Article/details/gt2fwfmmrdj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.chenlongwang.top/Article/details/gt2mmherxuw.html

Ruby: threads.map(&:join)
来源：http://dali.ehwqpu.com/Article/details/gt2llywqesh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2pxozdack.html

[O06] 使用进程池
来源：http://dali.jinqigfzy.top/Article/details/gt2slwtwnvb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yxqglavi.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xziqi.cn/Article/details/gt2ncqargyx.html

JS:   // child_process / cluster 模块
来源：http://dali.daxiang520.top/Article/details/gt2bxfmegiv.html

TS:   // child_process / cluster 模块
来源：http://dali.chenzaomai.com/Article/details/gt2ivipkibp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.chenlongwang.top/Article/details/gt2gajhyrol.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhoulong.xyz/Article/details/gt2dhdtlzhl.html

Ruby: // fork 块
来源：http://dali.chenzaomai.com/Article/details/gt2fozldvbp.html

C#:   Parallel.For
来源：http://dali.zhiwuduotai.top/Article/details/gt2yapepzzr.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2fjnzbpst.html

P. 常用工具函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gycfndzm.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2mtxbfiin.html

[P01] 生成 UUID
来源：http://dali.daxiang520.top/Article/details/gt2lfcrgfoz.html

Py:   str(uuid.uuid4())
来源：http://dali.jianghu66.top/Article/details/gt2rcculavy.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xinyue.icu/Article/details/gt2lmfzgaax.html

JS:   crypto.randomUUID()
来源：http://dali.ppjwa.cn/Article/details/gt2ungntupb.html

TS:   crypto.randomUUID()
来源：http://dali.hnxiangtu.top/Article/details/gt2iollcdrb.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhiwuduotai.top/Article/details/gt2hmxndqgw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tian-w.cn/Article/details/gt2icnceiiu.html

Ruby: SecureRandom.uuid
来源：http://dali.yuanzhike.top/Article/details/gt2qstfatch.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tanke756.top/Article/details/gt2tewrekph.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhixingplan.top/Article/details/gt2dumyhmvm.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xziqi.cn/Article/details/gt2trqkpplk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sufxvd.cn/Article/details/gt2cukaqdof.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sweek.top/Article/details/gt2jujvlywd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.9152youxi.cn/Article/details/gt2mfxhqbng.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.birdmap.top/Article/details/gt2gpgrxdku.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xuanzx.com/Article/details/gt2ierhblzo.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.haohaochexian.top/Article/details/gt2eqhggxmt.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jyoumei.cn/Article/details/gt2cbemkign.html

[P03] 生成短随机字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2dhhqwoov.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jiagoushi.top/Article/details/gt2dhmwdyrp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hammf.cn/Article/details/gt2mbuhxixt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aizwys.cn/Article/details/gt2qovlvenx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.vqdsnc.cn/Article/details/gt2baapvqcx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yuxming.cn/Article/details/gt2rvhvfbjj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jianghu66.top/Article/details/gt2rxhhlfwv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zycfv.cn/Article/details/gt2srknunjb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shuidangran.top/Article/details/gt2zbnwdwwt.html

[P04] 求长度
来源：http://dali.daxiang520.top/Article/details/gt2qdtjjcue.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hwlzuqjm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hyylvpih.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.kuanghao11.cn/Article/details/gt2ljozbsxo.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tianlin.xyz/Article/details/gt2ufymcsvo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.aizwys.cn/Article/details/gt2nmvuwstt.html

Go:   len(arr);  len(m)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jkarjtno.html

Ruby: x.length;  x.size
来源：http://dali.jinghuilouyu.cn/Article/details/gt2picsnisp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.gzhubu.top/Article/details/gt2njavynhh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gotoacloud.top/Article/details/gt2dmjieqgl.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhongyouzk.top/Article/details/gt2gqrqelnw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jiagoushi.top/Article/details/gt2itumnsqc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xuetiantiany.cn/Article/details/gt2uhazmnfy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zdqjudy.top/Article/details/gt2yhbszneu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yangfankeji.com/Article/details/gt2fwnnivwt.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.tanke756.top/Article/details/gt2yxpqvxmr.html

Ruby: a == b
来源：http://dali.aibaodan.cn/Article/details/gt2mponbiva.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hywenlv.cn/Article/details/gt2tdzmlryb.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.smart0.xyz/Article/details/gt2lcvrkusa.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gogol.net.cn/Article/details/gt2phczctil.html

PHP:  if (empty($x)) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2jrybptor.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.daria6918.cn/Article/details/gt2pwilddey.html

TS:   if (x == null) {}
来源：http://dali.sysykeji.top/Article/details/gt2udpzbjoz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yongpay.top/Article/details/gt2otswzzxx.html

Go:   if x == nil {}
来源：http://dali.cheryme.top/Article/details/gt2ajqgcsrj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kwnpxlhi.html

C#:   if (x is null) {}
来源：http://dali.aibaodan.cn/Article/details/gt2fspcneyk.html

[P07] 防抖与节流
来源：http://dali.yuxming.cn/Article/details/gt2czyqiocw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2bwnbpzqo.html

PHP:  // 手写时间戳比较
来源：http://dali.chenlongwang.top/Article/details/gt2navorcmk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jiagoushi.top/Article/details/gt2tgyandiv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenjidiqi.icu/Article/details/gt2dezzcpsk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.dianchejie.cn/Article/details/gt2naftplak.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.iojbl.cn/Article/details/gt2yarletpv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.wangdashe.top/Article/details/gt2rltscplw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.cucudq.cn/Article/details/gt2uujyjniq.html

[P08] 处理浮点精度问题
来源：http://dali.havefunace.top/Article/details/gt2tkyzlwla.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.birdmap.top/Article/details/gt2tpriomkb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hnxiangtu.top/Article/details/gt2ajxaqozq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.chenlongwang.top/Article/details/gt2ysoagwrj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yongpay.top/Article/details/gt2sdonmmfs.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.chenjidiqi.icu/Article/details/gt2tdaetyjt.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xrhbenxz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinqigufen.top/Article/details/gt2utvgykgd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cdnleiting.top/Article/details/gt2weynifmh.html


<!-- 参考信息 -->