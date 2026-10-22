代发 wailian999

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.aizwys.cn/Article/details/gtzigpnity.html

Ruby: ENV["HOME"]
来源：http://dali.bjfxy.top/Article/details/gtkdkgboqz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gtkveolons.html

[M03] 执行外部命令
来源：http://dali.cdnleiting.top/Article/details/gtvuyipbrg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xuetiantiany.cn/Article/details/gtidqwznpl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.316326.xyz/Article/details/gtftxljagb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ivvv.top/Article/details/gtubgjksmt.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.bjfxy.top/Article/details/gtlaflytlu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xuetiantiany.cn/Article/details/gthhuohxih.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zycfv.cn/Article/details/gtbvkeajjd.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.bjfxy.top/Article/details/gtunjdctdq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shangyingyoupin.top/Article/details/gtwwvpkswi.html

[M04] 获取当前工作目录
来源：http://dali.chenjidiqi.icu/Article/details/gtypvdgvxy.html

Py:   os.getcwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvplewcxl.html

PHP:  getcwd();
来源：http://dali.nanxuanxn.top/Article/details/gtueoazghg.html

JS:   process.cwd()
来源：http://dali.wangdashe.top/Article/details/gthomqzdlv.html

TS:   process.cwd()
来源：http://dali.sysykeji.top/Article/details/gtogivgszv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.316326.xyz/Article/details/gtepeamquw.html

Go:   os.Getwd()
来源：http://dali.chenzaomai.com/Article/details/gtavqxnqwe.html

Ruby: Dir.pwd
来源：http://dali.smart0.xyz/Article/details/gtoejfjwuu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cheryme.top/Article/details/gtcqcltaov.html

[M05] 设置退出码
来源：http://dali.haohaochexian.top/Article/details/gthlnpkezh.html

Py:   sys.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtprkcssxd.html

PHP:  exit(1);
来源：http://dali.yj20258.top/Article/details/gtzbrrxfjz.html

JS:   process.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtdkmgyxot.html

TS:   process.exit(1)
来源：http://dali.guannengcc.top/Article/details/gtmjsiugok.html

Java: System.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gtfjvymlpl.html

Go:   os.Exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbrlswszf.html

Ruby: exit 1
来源：http://dali.jinqigufen.top/Article/details/gtnrjkpuie.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shuidangran.top/Article/details/gtcyckctqk.html

[M06] 向标准错误输出
来源：http://dali.cheryme.top/Article/details/gtkryuravk.html

Py:   print("err", file=sys.stderr)
来源：http://dali.nanxuanxn.top/Article/details/gtxqktxpvk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.vqdsnc.cn/Article/details/gtkooefile.html

JS:   console.error("err")
来源：http://dali.zycfv.cn/Article/details/gtmrbhjpjg.html

TS:   console.error("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkejjxles.html

Java: System.err.println("err")
来源：http://dali.316326.xyz/Article/details/gthhlrphjp.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.dianchejie.cn/Article/details/gtatoyjucs.html

Ruby: warn "err"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfscdwhce.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhongyouzk.top/Article/details/gtulvmkhsh.html

[M07] 判断是否为主入口
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkukrfqax.html

Py:   if __name__ == "__main__":
来源：http://dali.yanxiufei.cn/Article/details/gtsgjrkscl.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hammf.cn/Article/details/gtklpadbxr.html

JS:   require.main === module
来源：http://dali.zhongyouzk.top/Article/details/gthqogaaxk.html

TS:   require.main === module
来源：http://dali.aizwys.cn/Article/details/gtuxuvcscx.html

Java: public static void main(String[] args)
来源：http://dali.guowangkeji.top/Article/details/gtoeigijid.html

Go:   func main()
来源：http://dali.jianghu66.top/Article/details/gtcbomqhcf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sufxvd.cn/Article/details/gtqyngmmih.html

C#:   static void Main(string[] args)
来源：http://dali.ppjwa.cn/Article/details/gtpoetyuzc.html

[M08] 获取系统与运行时信息
来源：http://dali.sweek.top/Article/details/gtkvmdqvhi.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sysykeji.top/Article/details/gtxrrzmfku.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cqqwz.cn/Article/details/gtafpspsch.html

JS:   process.platform;  process.version
来源：http://dali.hnxiangtu.top/Article/details/gtoyitdoyc.html

TS:   process.platform;  process.version
来源：http://dali.quarkkingdee.top/Article/details/gtvvjuglqj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xziqi.cn/Article/details/gtbucvrebz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ppjwa.cn/Article/details/gtpbpoyvcs.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ppjwa.cn/Article/details/gthyeukfrv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shuidangran.top/Article/details/gthtyavtpb.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtjmryyofd.html

N. 数据结构与算法
来源：http://dali.daria6918.cn/Article/details/gtbzkqpjjl.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtclwyfzkq.html

[N01] 二分查找（有序数组）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlbumdkuv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtpuusmkjc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttjfnozyd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gtvswhmlev.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhengqikj.top/Article/details/gtllrhdftc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ivvv.top/Article/details/gteoguezvk.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpsqvnyfk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jlsjyb.cn/Article/details/gtlnumccfa.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtdgecddcv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jiagoushi.top/Article/details/gtclmxkvod.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tian-w.cn/Article/details/gtkrkvssud.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cheryme.top/Article/details/gtsiekkzva.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yongpay.top/Article/details/gtypdbrtxo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpoaxzrdt.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.pycfn.com/Article/details/gtzitdbqwc.html

Go:   slices.Sort(arr)
来源：http://dali.andypj.xyz/Article/details/gtrtirrpga.html

Ruby: arr.sort
来源：http://dali.sufxvd.cn/Article/details/gtkgfiqpfx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ydzc1.top/Article/details/gtehmyzxka.html

[N03] 快速排序（分治示例）
来源：http://dali.zhiwuduotai.top/Article/details/gtyagzzqgf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.feifeiyinyue.top/Article/details/gtuxzjopru.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yj20258.top/Article/details/gtffhqjobd.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zdqjudy.top/Article/details/gtdsykadjs.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258888.top/Article/details/gtspzwyolh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jyoumei.cn/Article/details/gtcplptcoc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sysykeji.top/Article/details/gttmfyriav.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shanyushiyangkeji.top/Article/details/gttlprkjvq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jlsjyb.cn/Article/details/gthvdnncxe.html

[N04] 斐波那契数列
来源：http://dali.fzhhl.top/Article/details/gtebnvtuxt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ydzc1.top/Article/details/gtlqomzepf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xuanzx.com/Article/details/gtaounktxk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtgepusiuc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.snrcjt.cn/Article/details/gtxutvhvxp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.dashuyun.cn/Article/details/gtfyuojanm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xinyue.icu/Article/details/gtncmgbgjn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigufen.top/Article/details/gtvnqcrteh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhixingplan.top/Article/details/gtmjxdktew.html

[N05] 最大公约数
来源：http://dali.ybcxt.top/Article/details/gthhqissve.html

Py:   math.gcd(a, b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthskzyykc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.andypj.xyz/Article/details/gtkluzmmum.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daxiang520.top/Article/details/gtfqeslwss.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.9152youxi.cn/Article/details/gtmilzqqzj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cheryme.top/Article/details/gtmldtlekb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.chenjidiqi.icu/Article/details/gtgageswkx.html

Ruby: a.gcd(b)
来源：http://dali.fzhhl.top/Article/details/gtufsxlxok.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtznzdplhh.html

[N06] 判断回文字符串
来源：http://dali.hnqzz.top/Article/details/gtfyqcntdg.html

Py:   s == s[::-1]
来源：http://dali.zycfv.cn/Article/details/gthhkqpyaq.html

PHP:  $s === strrev($s);
来源：http://dali.hfpthk.cn/Article/details/gtxfwwabfj.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtesldwjal.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gtvrowaxss.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.havefunace.top/Article/details/gtudwruumx.html

Go:   // 双指针从两端比较
来源：http://dali.shzxlz.cn/Article/details/gtahbitukf.html

Ruby: s == s.reverse
来源：http://dali.nanxuanxn.top/Article/details/gtmkwfcdvl.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gotoacloud.top/Article/details/gtgmhizyoj.html

[N07] 两数之和（返回下标）
来源：http://dali.c1oappe.top/Article/details/gtzvtjrccs.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnkvvqqbq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj20258888.top/Article/details/gtnibwjsbr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.aibaodan.cn/Article/details/gttnguldyd.html

TS:   // 手写 Map<string, number>
来源：http://dali.cdnleiting.top/Article/details/gtjfrpwdit.html

Java: // 手写 HashMap
来源：http://dali.sufxvd.cn/Article/details/gtnpxpbczq.html

Go:   // 手写 map[int]int
来源：http://dali.ppjwa.cn/Article/details/gtilspetbj.html

Ruby: // 手写 Hash
来源：http://dali.quarkkingdee.top/Article/details/gtzuytgmlf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hnqzz.top/Article/details/gtfjbqgmur.html

[N08] 生成全排列
来源：http://dali.shzxlz.cn/Article/details/gttkkhbamp.html

Py:   itertools.permutations(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtodkiinbs.html

PHP:  // 手写递归交换
来源：http://dali.bjfxy.top/Article/details/gtrkflydvp.html

JS:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjmglltiz.html

TS:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gtnhyozomj.html

Java: // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtspzgzgdg.html

Go:   // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gtqesmoece.html

Ruby: arr.permutation.to_a
来源：http://dali.guowangkeji.top/Article/details/gtyxiadvju.html

C#:   // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtknmisfhk.html

[N09] 栈与队列
来源：http://dali.ppjwa.cn/Article/details/gtabtecarw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.dashuyun.cn/Article/details/gtrdfkvldz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cqqwz.cn/Article/details/gtsczujrml.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shuidangran.top/Article/details/gtmcqjntre.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xuetiantiany.cn/Article/details/gthuquusmb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnasaweto.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cheryme.top/Article/details/gtjamxxbof.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cashguo.top/Article/details/gtfkcbzvml.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.0kj1m.cn/Article/details/gtbbalxrzy.html

[N10] 链表节点定义
来源：http://dali.jiagoushi.top/Article/details/gtgfchemxq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cheryme.top/Article/details/gthawwsnnq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xylfe.cn/Article/details/gtxtitknpq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.feifeiyinyue.top/Article/details/gtbnlydyqy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.fzhhl.top/Article/details/gtyrnhoevi.html

Java: class Node { int v; Node next; }
来源：http://dali.hfpthk.cn/Article/details/gtlnfscuws.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.dianchejie.cn/Article/details/gtegunuykj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gotoacloud.top/Article/details/gtarlapdac.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.nwbrower.top/Article/details/gthdtqouct.html

[N11] 二叉树中序遍历
来源：http://dali.jiagoushi.top/Article/details/gtrvovdlll.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.daria6918.cn/Article/details/gtltzjqowx.html

PHP:  // 手写递归函数
来源：http://dali.daria6918.cn/Article/details/gtiaujntlj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jlsjyb.cn/Article/details/gtmxirdvrh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.9152youxi.cn/Article/details/gtazuowawy.html

Java: // 手写递归
来源：http://dali.nanxinkj.top/Article/details/gtcupyzqbv.html

Go:   // 手写递归
来源：http://dali.cashguo.top/Article/details/gtqgwkwpqc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cqqwz.cn/Article/details/gtqxsoegqg.html

C#:   // 手写递归
来源：http://dali.shuidangran.top/Article/details/gtlcjvdzaa.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.chenlongwang.top/Article/details/gtjbdugbyd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.mhx1999.top/Article/details/gtmpyzirut.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.chenjidiqi.icu/Article/details/gtvcxjpnng.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jyoumei.cn/Article/details/gtvzijfdbd.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.svipenyu.cn/Article/details/gtmmfgwhtk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.kuanghao11.cn/Article/details/gtgvdbjauf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hysaishi.cn/Article/details/gtutmwpwko.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gaohongyu789.top/Article/details/gtidynikqa.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tian-w.cn/Article/details/gtxaodoknr.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtioijfbuy.html

O. 并发与异步
来源：http://dali.meibo888.top/Article/details/gtxslvmaro.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtqtusivcl.html

[O01] 启动一个线程
来源：http://dali.xziqi.cn/Article/details/gtbbqoybak.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.smart0.xyz/Article/details/gtmohdyfje.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ehwqpu.com/Article/details/gtuxveovuf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.chenzaomai.com/Article/details/gtqvovdqnq.html

TS:   // 同 JS
来源：http://dali.nwbrower.top/Article/details/gtawqhheug.html

Java: new Thread(() -> f()).start()
来源：http://dali.hysaishi.cn/Article/details/gtlknayamr.html

Go:   go f()
来源：http://dali.zhoulong.xyz/Article/details/gtgxmibxwb.html

Ruby: Thread.new { f }
来源：http://dali.nanxuanxn.top/Article/details/gtehedgoqz.html

C#:   Task.Run(() => F());
来源：http://dali.daria6918.cn/Article/details/gtcprtfbkj.html

[O02] 使用线程池
来源：http://dali.bjfxy.top/Article/details/gtjrwrfquc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.chenzaomai.com/Article/details/gtqsnupqnx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.gogol.net.cn/Article/details/gtwrrpvcaa.html

JS:   // worker_threads 线程池
来源：http://dali.yj20258888.top/Article/details/gtbvxqcnkz.html

TS:   // worker_threads 线程池
来源：http://dali.zycfv.cn/Article/details/gtnfjwtpnm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.nanxinkj.top/Article/details/gtsyjshysn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.wangshuangyany.cn/Article/details/gtezzauasf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cqqwz.cn/Article/details/gtwjyispus.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.meibo888.top/Article/details/gtcbnteeun.html

[O03] 加锁保护共享数据
来源：http://dali.zhiwuduotai.top/Article/details/gtfakixhtw.html

Py:   with lock: shared += 1
来源：http://dali.wangdashe.top/Article/details/gtoilyhmjq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.fengsongda.top/Article/details/gtwiynqjzx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.redwolf501.top/Article/details/gtacfzqbiq.html

TS:   // 同 JS
来源：http://dali.jyoumei.cn/Article/details/gtneniqmkf.html

Java: synchronized (this) { shared++; }
来源：http://dali.yanxiufei.cn/Article/details/gteiojrctv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jlsjyb.cn/Article/details/gttddjzodb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hywenlv.cn/Article/details/gttbovxhgk.html

C#:   lock (gate) { shared++; }
来源：http://dali.xziqi.cn/Article/details/gtxgrgejvb.html

[O04] 定义异步函数并等待
来源：http://dali.snrcjt.cn/Article/details/gtzbpwcjvq.html

Py:   async def f():⏎    await g()
来源：http://dali.cashguo.top/Article/details/gtxrbdpckl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinghuilouyu.cn/Article/details/gtijrwtpfe.html

JS:   async function f() { await g(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiyaicvgh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.vqdsnc.cn/Article/details/gtxuuyffjl.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwbscogkm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.daxiang520.top/Article/details/gtesrmopfm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.iojbl.cn/Article/details/gtxeknoseo.html

C#:   async Task F() { await G(); }
来源：http://dali.snrcjt.cn/Article/details/gtwbdjtyyi.html

[O05] 并发执行并等待全部完成
来源：http://dali.jiagoushi.top/Article/details/gtliclmuxg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzobnzook.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ydzc1.top/Article/details/gtamlsynus.html

JS:   await Promise.all(tasks)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttvydgamj.html

TS:   await Promise.all(tasks)
来源：http://dali.ehwqpu.com/Article/details/gtkxpvzkdi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jiagoushi.top/Article/details/gtwjdtnxne.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jyoumei.cn/Article/details/gtomizkptq.html

Ruby: threads.map(&:join)
来源：http://dali.birdmap.top/Article/details/gtpzfwtryf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhengqikj.top/Article/details/gtseneefpv.html

[O06] 使用进程池
来源：http://dali.cqqwz.cn/Article/details/gtowunyfkk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.tian-w.cn/Article/details/gtsbmhpweb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yvedp.cn/Article/details/gtvkqdwali.html

JS:   // child_process / cluster 模块
来源：http://dali.bjfxy.top/Article/details/gtoxumnqyo.html

TS:   // child_process / cluster 模块
来源：http://dali.mhx1999.top/Article/details/gtmrlnpmgs.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ybcxt.top/Article/details/gtmeccyrkq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ybcxt.top/Article/details/gtqfrhzkjr.html

Ruby: // fork 块
来源：http://dali.gogol.net.cn/Article/details/gtbvyodfub.html

C#:   Parallel.For
来源：http://dali.vqdsnc.cn/Article/details/gtwaievydb.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtmivifvzn.html

P. 常用工具函数
来源：http://dali.yvedp.cn/Article/details/gtgcvxschz.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtrbasyfjd.html

[P01] 生成 UUID
来源：http://dali.cucudq.cn/Article/details/gtxwgnwnbj.html

Py:   str(uuid.uuid4())
来源：http://dali.zhengqikj.top/Article/details/gtgyweikpp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.iojbl.cn/Article/details/gtybpoeqpx.html

JS:   crypto.randomUUID()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzwyoaxck.html

TS:   crypto.randomUUID()
来源：http://dali.hongshengwenyu.top/Article/details/gtnncwmoax.html

Java: UUID.randomUUID().toString()
来源：http://dali.guannengcc.top/Article/details/gttgwgjbeu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthaucgtny.html

Ruby: SecureRandom.uuid
来源：http://dali.bjfxy.top/Article/details/gtmvrainql.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwkqimxmj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.9152youxi.cn/Article/details/gtpkwpttfm.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shangyingyoupin.top/Article/details/gtzmjmxylo.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.daria6918.cn/Article/details/gtlzcbzsht.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.havefunace.top/Article/details/gtkfgrmojv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cheryme.top/Article/details/gtmqaphsxj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yvedp.cn/Article/details/gtfsnlbpis.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jyoumei.cn/Article/details/gtllsfhpdg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nanxinkj.top/Article/details/gtwyaridem.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jlsjyb.cn/Article/details/gtvltjdtfp.html

[P03] 生成短随机字符串
来源：http://dali.zycfv.cn/Article/details/gtcelktwgg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hongshengwenyu.top/Article/details/gtxjsmwrwi.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.chenzaomai.com/Article/details/gtouaxmylh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gaohongyu789.top/Article/details/gtixsurcck.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ydzc1.top/Article/details/gtrmaenrll.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.tianlin.xyz/Article/details/gtpwlplcmw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yueranfly.top/Article/details/gtovrkavcf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.bjfxy.top/Article/details/gtspgznntv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.haohaochexian.top/Article/details/gtwvwbbrru.html

[P04] 求长度
来源：http://dali.jinqigufen.top/Article/details/gtctqsrfiw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwpoyxfbc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gtxubkyexd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hfpthk.cn/Article/details/gtxtxyjcii.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenlongwang.top/Article/details/gthnbaxlvs.html

Java: list.size();  map.size();  s.length()
来源：http://dali.gogol.net.cn/Article/details/gtqiuxuwea.html

Go:   len(arr);  len(m)
来源：http://dali.vqdsnc.cn/Article/details/gtncrcgrba.html

Ruby: x.length;  x.size
来源：http://dali.chenlongwang.top/Article/details/gtnytlrsqt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jlsjyb.cn/Article/details/gtywuahmof.html

[P05] 判断两个对象内容是否相等
来源：http://dali.fengsongda.top/Article/details/gtihtlyvmm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.redwolf501.top/Article/details/gtjkabhvwx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.meibo888.top/Article/details/gtfwdbnrhp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ppjwa.cn/Article/details/gtemmwiufw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.wangdashe.top/Article/details/gtsjrpivar.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jyoumei.cn/Article/details/gtzyjjaoyr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.haohaochexian.top/Article/details/gtvmgpaqxn.html

Ruby: a == b
来源：http://dali.cashguo.top/Article/details/gtyicbuadh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ydzc1.top/Article/details/gtgbdvaecd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.316326.xyz/Article/details/gtfvaviato.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.svipenyu.cn/Article/details/gtrrhpqnms.html

PHP:  if (empty($x)) {}
来源：http://dali.9152youxi.cn/Article/details/gteejoxqoz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.0kj1m.cn/Article/details/gtjkoguflo.html

TS:   if (x == null) {}
来源：http://dali.zhengqikj.top/Article/details/gtjjrddtsl.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.aibaodan.cn/Article/details/gtltvirxzy.html

Go:   if x == nil {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtetbzijtn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.316326.xyz/Article/details/gtkkavpwny.html

C#:   if (x is null) {}
来源：http://dali.dianchejie.cn/Article/details/gtmfwgyjma.html

[P07] 防抖与节流
来源：http://dali.redwolf501.top/Article/details/gtnftzygpu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxlkduzpy.html

PHP:  // 手写时间戳比较
来源：http://dali.sweek.top/Article/details/gtxfiqsupr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yonumen.top/Article/details/gtuflxpgcv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fzhhl.top/Article/details/gtnpaghxls.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtensndqgv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jyoumei.cn/Article/details/gthuivvxps.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.pycfn.com/Article/details/gtcxupkdlc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yj20258888.top/Article/details/gtaqbucrdw.html

[P08] 处理浮点精度问题
来源：http://dali.gaohongyu789.top/Article/details/gtcwfdwbvg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.vqdsnc.cn/Article/details/gtbosrzopf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.mhx1999.top/Article/details/gtkztinulp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.gaohongyu789.top/Article/details/gteukjntxy.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtocowrnom.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.nanxinkj.top/Article/details/gtdztwreha.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.feifeiyinyue.top/Article/details/gtxsgkrnwd.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yueranfly.top/Article/details/gtbqtyqifu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jlsjyb.cn/Article/details/gtgepfbovv.html


<!-- 参考信息 -->