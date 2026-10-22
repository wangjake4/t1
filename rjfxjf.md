代发 wailian999

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cucudq.cn/Article/details/gt2toasetam.html

JS:   process.env.HOME
来源：http://dali.haohaochexian.top/Article/details/gt2wtgegluf.html

TS:   process.env.HOME
来源：http://dali.yj202588.top/Article/details/gt2ttxruayj.html

Java: System.getenv("HOME")
来源：http://dali.cucudq.cn/Article/details/gt2zbmobknk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xinyue.icu/Article/details/gt2sgzhlwgl.html

Ruby: ENV["HOME"]
来源：http://dali.zycfv.cn/Article/details/gt2rbqrxchi.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tanke756.top/Article/details/gt2stoqwwvq.html

[M03] 执行外部命令
来源：http://dali.xinyue.icu/Article/details/gt2wftgthzw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhixingplan.top/Article/details/gt2uqqqktlh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hongshengwenyu.top/Article/details/gt2edvqsupr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.iojbl.cn/Article/details/gt2fthptxpr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258888.top/Article/details/gt2vlbjbois.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.0kj1m.cn/Article/details/gt2sjodkozw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yj20258888.top/Article/details/gt2jazjsqib.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.wangshuangyany.cn/Article/details/gt2spewgrhh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ltwtnnjw.html

[M04] 获取当前工作目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ntzcqzuq.html

Py:   os.getcwd()
来源：http://dali.birdmap.top/Article/details/gt2anxktpym.html

PHP:  getcwd();
来源：http://dali.daria6918.cn/Article/details/gt2olydboow.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2jgeyqlxv.html

TS:   process.cwd()
来源：http://dali.hnqzz.top/Article/details/gt2zlyglijb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xziqi.cn/Article/details/gt2fhjoegdw.html

Go:   os.Getwd()
来源：http://dali.tian-w.cn/Article/details/gt2omrwzjjb.html

Ruby: Dir.pwd
来源：http://dali.tianlin.xyz/Article/details/gt2aezwxjgm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jiagoushi.top/Article/details/gt2cleuzcwv.html

[M05] 设置退出码
来源：http://dali.iojbl.cn/Article/details/gt2xwbcmhtk.html

Py:   sys.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gt2gdzkcgpg.html

PHP:  exit(1);
来源：http://dali.cqqwz.cn/Article/details/gt2fsnujlfj.html

JS:   process.exit(1)
来源：http://dali.nwbrower.top/Article/details/gt2bhwtvuns.html

TS:   process.exit(1)
来源：http://dali.wangdashe.top/Article/details/gt2plezwkcn.html

Java: System.exit(1)
来源：http://dali.zycfv.cn/Article/details/gt2qonqhryi.html

Go:   os.Exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xqxmutzh.html

Ruby: exit 1
来源：http://dali.chenzaomai.com/Article/details/gt2hvdakkkd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cashguo.top/Article/details/gt2kwizgynp.html

[M06] 向标准错误输出
来源：http://dali.xuetiantiany.cn/Article/details/gt2eeflclbx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yangfankeji.com/Article/details/gt2wztaljbe.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hysaishi.cn/Article/details/gt2jjoutguc.html

JS:   console.error("err")
来源：http://dali.svipenyu.cn/Article/details/gt2trdqredi.html

TS:   console.error("err")
来源：http://dali.fzhhl.top/Article/details/gt2fyoavagc.html

Java: System.err.println("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tabteite.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aytcuiqj.html

Ruby: warn "err"
来源：http://dali.dianchejie.cn/Article/details/gt2hpsnskac.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cqqwz.cn/Article/details/gt2ehtskaub.html

[M07] 判断是否为主入口
来源：http://dali.hfpthk.cn/Article/details/gt2cknjezog.html

Py:   if __name__ == "__main__":
来源：http://dali.andypj.xyz/Article/details/gt2xoiareax.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cdnleiting.top/Article/details/gt2htkafxgl.html

JS:   require.main === module
来源：http://dali.fzhhl.top/Article/details/gt2yziomxsx.html

TS:   require.main === module
来源：http://dali.xylfe.cn/Article/details/gt2qnanfdqb.html

Java: public static void main(String[] args)
来源：http://dali.nanxuanxn.top/Article/details/gt2xithyptl.html

Go:   func main()
来源：http://dali.c1oappe.top/Article/details/gt2lrqesyna.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jqgufenzy.top/Article/details/gt2odgkzwip.html

C#:   static void Main(string[] args)
来源：http://dali.tian-w.cn/Article/details/gt2ijywsuit.html

[M08] 获取系统与运行时信息
来源：http://dali.aibaodan.cn/Article/details/gt2esafaqhc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yongpay.top/Article/details/gt2bgcunmlf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yangfankeji.com/Article/details/gt2xtdhegis.html

JS:   process.platform;  process.version
来源：http://dali.havefunace.top/Article/details/gt2lgtmjcio.html

TS:   process.platform;  process.version
来源：http://dali.xuetiantiany.cn/Article/details/gt2ywdqvvsp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinqigufen.top/Article/details/gt2mqbkexni.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xuetiantiany.cn/Article/details/gt2zipflxrn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jqgfzy.top/Article/details/gt2mwzumhhs.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.bjfxy.top/Article/details/gt2ipcrggwj.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2nyfqlocq.html

N. 数据结构与算法
来源：http://dali.dashuyun.cn/Article/details/gt2ecxudvvx.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2jkptfvui.html

[N01] 二分查找（有序数组）
来源：http://dali.vqdsnc.cn/Article/details/gt2lbtkrkhq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bflaguub.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yongpay.top/Article/details/gt2hyemczli.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hammf.cn/Article/details/gt2pzpsoflj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.kuanghao11.cn/Article/details/gt2dmdjqzun.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hnqzz.top/Article/details/gt2fjwvhmgl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xinyue.icu/Article/details/gt2aqwmvpca.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhixingplan.top/Article/details/gt2rqgtydbj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gzhubu.top/Article/details/gt2zqtdmdes.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jiagoushi.top/Article/details/gt2cxmgmwuy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigfzy.top/Article/details/gt2zozpnthf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jlsjyb.cn/Article/details/gt2ijrutddc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj202588.top/Article/details/gt2jbuwswiu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenlongwang.top/Article/details/gt2qmpclaah.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.guowangkeji.top/Article/details/gt2fyhtxhmu.html

Go:   slices.Sort(arr)
来源：http://dali.xziqi.cn/Article/details/gt2omixoaci.html

Ruby: arr.sort
来源：http://dali.chenzaomai.com/Article/details/gt2msfrdokw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mlubqimb.html

[N03] 快速排序（分治示例）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gwnitwsx.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ppjwa.cn/Article/details/gt2svatdhvz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.sysykeji.top/Article/details/gt2mpcihgqu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daxiang520.top/Article/details/gt2vcyjhsgc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxuanxn.top/Article/details/gt2ckxohzdy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhoulong.xyz/Article/details/gt2iysftrmc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hywenlv.cn/Article/details/gt2igvlewve.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yuxming.cn/Article/details/gt2zwpkygfn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.0kj1m.cn/Article/details/gt2jplwjtba.html

[N04] 斐波那契数列
来源：http://dali.zdqjudy.top/Article/details/gt2axnvweia.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qkqyvpxf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.mhx1999.top/Article/details/gt2qzbsesvy.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gt2rfxvtgdm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xdjynood.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhixingplan.top/Article/details/gt2dtfqlbtx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xziqi.cn/Article/details/gt2qktnfisy.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hammf.cn/Article/details/gt2faswzxnd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.iojbl.cn/Article/details/gt2vgsrphmp.html

[N05] 最大公约数
来源：http://dali.chenzaomai.com/Article/details/gt2lpommcwo.html

Py:   math.gcd(a, b)
来源：http://dali.yonumen.top/Article/details/gt2wvvtoodq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xuanzx.com/Article/details/gt2zxzjqhiv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.svipenyu.cn/Article/details/gt2afhpltsc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj202588.top/Article/details/gt2cjdavqso.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.dianchejie.cn/Article/details/gt2goeclgxg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jqgfzy.top/Article/details/gt2hhbfuscf.html

Ruby: a.gcd(b)
来源：http://dali.cheryme.top/Article/details/gt2xwejdnbp.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yvedp.cn/Article/details/gt2yoixtvpa.html

[N06] 判断回文字符串
来源：http://dali.c1oappe.top/Article/details/gt2umzcqdlu.html

Py:   s == s[::-1]
来源：http://dali.andypj.xyz/Article/details/gt2fjtzorlc.html

PHP:  $s === strrev($s);
来源：http://dali.sxryk.cn/Article/details/gt2segdvfrb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gt2ebunilaj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gt2tcbaumzj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2blaarvyt.html

Go:   // 双指针从两端比较
来源：http://dali.yj20258.top/Article/details/gt2lprbkyfw.html

Ruby: s == s.reverse
来源：http://dali.jiagoushi.top/Article/details/gt2gswnafpg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinqigfzy.top/Article/details/gt2jylpjurn.html

[N07] 两数之和（返回下标）
来源：http://dali.bjfxy.top/Article/details/gt2ibwuzfyp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yj202588.top/Article/details/gt2qrmutbgl.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cdnleiting.top/Article/details/gt2kudlyaby.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ehwqpu.com/Article/details/gt2noamueyy.html

TS:   // 手写 Map<string, number>
来源：http://dali.andypj.xyz/Article/details/gt2srkdocew.html

Java: // 手写 HashMap
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hnmkalii.html

Go:   // 手写 map[int]int
来源：http://dali.guannengcc.top/Article/details/gt2zewkarwd.html

Ruby: // 手写 Hash
来源：http://dali.havefunace.top/Article/details/gt2bacywpwu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.snrcjt.cn/Article/details/gt2spvdeiqb.html

[N08] 生成全排列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fmxpbfdp.html

Py:   itertools.permutations(arr)
来源：http://dali.pycfn.com/Article/details/gt2xbavoyeb.html

PHP:  // 手写递归交换
来源：http://dali.zhengqikj.top/Article/details/gt2ivtczamm.html

JS:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gt2ineqwxdk.html

TS:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gt2oasfezit.html

Java: // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gt2egfgkhiw.html

Go:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gt2yvtlttih.html

Ruby: arr.permutation.to_a
来源：http://dali.xuetiantiany.cn/Article/details/gt2nnclmulr.html

C#:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gt2soctrhbb.html

[N09] 栈与队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yfinxkxf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hfpthk.cn/Article/details/gt2tpaddbyx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.daxiang520.top/Article/details/gt2yxnfpqit.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yj20258.top/Article/details/gt2kpckhkes.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.pycfn.com/Article/details/gt2fzymzxtm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hywenlv.cn/Article/details/gt2jtfansza.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinqigfzy.top/Article/details/gt2tstcfivq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gt2dplfqasq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.iojbl.cn/Article/details/gt2mvkcufpk.html

[N10] 链表节点定义
来源：http://dali.svipenyu.cn/Article/details/gt2gtplhjmq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhiwuduotai.top/Article/details/gt2giqkuygq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2vacqqxtj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.fengsongda.top/Article/details/gt2jylnxhus.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.dianchejie.cn/Article/details/gt2clkcdwwa.html

Java: class Node { int v; Node next; }
来源：http://dali.jinqigufen.top/Article/details/gt2jdjmckcj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yj20258888.top/Article/details/gt2crmxgfmq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.wangdashe.top/Article/details/gt2kfzopslq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cqqwz.cn/Article/details/gt2knqhsgci.html

[N11] 二叉树中序遍历
来源：http://dali.jinqigfzy.top/Article/details/gt2wewutexs.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sxryk.cn/Article/details/gt2jalchihv.html

PHP:  // 手写递归函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ztgjlyjo.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.c1oappe.top/Article/details/gt2ieaomywj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.vqdsnc.cn/Article/details/gt2fzqwzcaj.html

Java: // 手写递归
来源：http://dali.cheryme.top/Article/details/gt2wylkjqhw.html

Go:   // 手写递归
来源：http://dali.nwbrower.top/Article/details/gt2kdzirbcm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sufxvd.cn/Article/details/gt2vvooqjel.html

C#:   // 手写递归
来源：http://dali.zhengqikj.top/Article/details/gt2gnysalow.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hysaishi.cn/Article/details/gt2tdtibxab.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zycfv.cn/Article/details/gt2wtxprzag.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.aizwys.cn/Article/details/gt2grsnsddf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gzhubu.top/Article/details/gt2yfipbgjt.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gaohongyu789.top/Article/details/gt2twessrij.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.wangshuangyany.cn/Article/details/gt2dpsfwzcm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sysykeji.top/Article/details/gt2kkexuwae.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.pycfn.com/Article/details/gt2ugikhuxi.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuetiantiany.cn/Article/details/gt2ryjrdxzc.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2qwabaodg.html

O. 并发与异步
来源：http://dali.nanxinkj.top/Article/details/gt2uijeubkw.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2zgcgncrn.html

[O01] 启动一个线程
来源：http://dali.feifeiyinyue.top/Article/details/gt2zjqzpnhp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gaohongyu789.top/Article/details/gt2loonwalh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.0kj1m.cn/Article/details/gt2sqtcrtwa.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhengqikj.top/Article/details/gt2wrdaochp.html

TS:   // 同 JS
来源：http://dali.sufxvd.cn/Article/details/gt2xrxxuxfp.html

Java: new Thread(() -> f()).start()
来源：http://dali.316326.xyz/Article/details/gt2qtpjlpju.html

Go:   go f()
来源：http://dali.jianghu66.top/Article/details/gt2dyawtvby.html

Ruby: Thread.new { f }
来源：http://dali.yongpay.top/Article/details/gt2pfulhiuy.html

C#:   Task.Run(() => F());
来源：http://dali.yj202588.top/Article/details/gt2nuquacqa.html

[O02] 使用线程池
来源：http://dali.gzhubu.top/Article/details/gt2zjjxghya.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hammf.cn/Article/details/gt2mdhkpfml.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.aizwys.cn/Article/details/gt2yakcyviv.html

JS:   // worker_threads 线程池
来源：http://dali.tianlin.xyz/Article/details/gt2pjefyxdp.html

TS:   // worker_threads 线程池
来源：http://dali.pengpengdd.cyou/Article/details/gt2befkpapp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.0kj1m.cn/Article/details/gt2qdikdllu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xuetiantiany.cn/Article/details/gt2sltbxllr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.iojbl.cn/Article/details/gt2bzmkooyx.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.havefunace.top/Article/details/gt2dxmcyqyw.html

[O03] 加锁保护共享数据
来源：http://dali.aibaodan.cn/Article/details/gt2jyjbizup.html

Py:   with lock: shared += 1
来源：http://dali.nanxinkj.top/Article/details/gt2qdjqxsti.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gogol.net.cn/Article/details/gt2kalwnyou.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.guannengcc.top/Article/details/gt2gdmeqeyl.html

TS:   // 同 JS
来源：http://dali.hongshengwenyu.top/Article/details/gt2wethwydl.html

Java: synchronized (this) { shared++; }
来源：http://dali.chenlongwang.top/Article/details/gt2ptrepsaz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gzhubu.top/Article/details/gt2cdvmgwvz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.guowangkeji.top/Article/details/gt2gcgnkfnw.html

C#:   lock (gate) { shared++; }
来源：http://dali.yuxming.cn/Article/details/gt2rgogdzio.html

[O04] 定义异步函数并等待
来源：http://dali.sufxvd.cn/Article/details/gt2mxbuzklq.html

Py:   async def f():⏎    await g()
来源：http://dali.aizwys.cn/Article/details/gt2eqqjhomu.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.chenzaomai.com/Article/details/gt2fbsnqygz.html

JS:   async function f() { await g(); }
来源：http://dali.hfpthk.cn/Article/details/gt2jihhbtbt.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2lqfzhfap.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.feifeiyinyue.top/Article/details/gt2pcwzxttd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eiamtivr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xziqi.cn/Article/details/gt2krkxwaml.html

C#:   async Task F() { await G(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ykvpiamn.html

[O05] 并发执行并等待全部完成
来源：http://dali.hnqzz.top/Article/details/gt2mqctzcym.html

Py:   asyncio.gather(*tasks)
来源：http://dali.9152youxi.cn/Article/details/gt2ijlgrkbf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.c1oappe.top/Article/details/gt2bfqhxcmn.html

JS:   await Promise.all(tasks)
来源：http://dali.daxiang520.top/Article/details/gt2mbyzsvjx.html

TS:   await Promise.all(tasks)
来源：http://dali.hongshengwenyu.top/Article/details/gt2umpgjumb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.svipenyu.cn/Article/details/gt2aehctloz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zdpaohnu.html

Ruby: threads.map(&:join)
来源：http://dali.yj20258888.top/Article/details/gt2mefagahy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhengqikj.top/Article/details/gt2ueahwvmj.html

[O06] 使用进程池
来源：http://dali.cqqwz.cn/Article/details/gt2vohiahxs.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhiwuduotai.top/Article/details/gt2jwfduubi.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xylfe.cn/Article/details/gt2svpxgcwk.html

JS:   // child_process / cluster 模块
来源：http://dali.feifeiyinyue.top/Article/details/gt2egbpwyas.html

TS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ersmkcec.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.pengpengdd.cyou/Article/details/gt2mospoayw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.aizwys.cn/Article/details/gt2xfriyxdv.html

Ruby: // fork 块
来源：http://dali.ybcxt.top/Article/details/gt2vevxhfzb.html

C#:   Parallel.For
来源：http://dali.c1oappe.top/Article/details/gt2jezqgetz.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2wrugmujz.html

P. 常用工具函数
来源：http://dali.hammf.cn/Article/details/gt2vebtlswd.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2geefqbwf.html

[P01] 生成 UUID
来源：http://dali.hnqzz.top/Article/details/gt2wxofvcnc.html

Py:   str(uuid.uuid4())
来源：http://dali.bjfxy.top/Article/details/gt2gxqsqjjx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sweek.top/Article/details/gt2frdxkdpx.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ggbveomq.html

TS:   crypto.randomUUID()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mjvpqjxo.html

Java: UUID.randomUUID().toString()
来源：http://dali.zdqjudy.top/Article/details/gt2hgaaihnf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.meibo888.top/Article/details/gt2okxgwjyy.html

Ruby: SecureRandom.uuid
来源：http://dali.haohaochexian.top/Article/details/gt2pbytqdyt.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jgkltcym.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ydzc1.top/Article/details/gt2mmbmwkmc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.wangshuangyany.cn/Article/details/gt2fkvuezme.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oaqcbwwi.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ydzc1.top/Article/details/gt2vbtzqtrh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hongshengwenyu.top/Article/details/gt2tpotkypb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yangfankeji.com/Article/details/gt2bollffmy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.nanxuanxn.top/Article/details/gt2dklrgzja.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.fzhhl.top/Article/details/gt2czpbjsrw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yj20258888.top/Article/details/gt2unpfwhou.html

[P03] 生成短随机字符串
来源：http://dali.xinyue.icu/Article/details/gt2ildrgteg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.tanke756.top/Article/details/gt2dyeuxmbc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cqqwz.cn/Article/details/gt2qwzmyzlt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yueranfly.top/Article/details/gt2klerwsfo.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuanzx.com/Article/details/gt2ngmfhmyy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jlsjyb.cn/Article/details/gt2xzebsfal.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.9152youxi.cn/Article/details/gt2hysbaabu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zdqjudy.top/Article/details/gt2sudzhysd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jqgufenzy.top/Article/details/gt2zqqhdpza.html

[P04] 求长度
来源：http://dali.hysaishi.cn/Article/details/gt2kufsfhjj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gogol.net.cn/Article/details/gt2ryvimhfs.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gt2krtutfuj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ydzc1.top/Article/details/gt2phljynxf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tian-w.cn/Article/details/gt2hvwemuyn.html

Java: list.size();  map.size();  s.length()
来源：http://dali.316326.xyz/Article/details/gt2basoasfj.html

Go:   len(arr);  len(m)
来源：http://dali.yj202588.top/Article/details/gt2cjkporgq.html

Ruby: x.length;  x.size
来源：http://dali.bjfxy.top/Article/details/gt2fivewcuu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hfpthk.cn/Article/details/gt2pqfcfila.html

[P05] 判断两个对象内容是否相等
来源：http://dali.iojbl.cn/Article/details/gt2dwlnjlqt.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.guannengcc.top/Article/details/gt2xabylskr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhongyouzk.top/Article/details/gt2ldghnfou.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.smart0.xyz/Article/details/gt2dinxtzeo.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jianghu66.top/Article/details/gt2qziemidi.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.316326.xyz/Article/details/gt2xbgyumov.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yonumen.top/Article/details/gt2mfsejwut.html

Ruby: a == b
来源：http://dali.yvedp.cn/Article/details/gt2emgohbmb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.svipenyu.cn/Article/details/gt2ghxepuoz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hnqzz.top/Article/details/gt2uxfgwsrq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yj20258.top/Article/details/gt2bwaolwtj.html

PHP:  if (empty($x)) {}
来源：http://dali.yonumen.top/Article/details/gt2qiutiitl.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.gogol.net.cn/Article/details/gt2bnseyadd.html

TS:   if (x == null) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2iagrswby.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.aizwys.cn/Article/details/gt2siwmfhsw.html

Go:   if x == nil {}
来源：http://dali.nanxinkj.top/Article/details/gt2anjdlpdw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.c1oappe.top/Article/details/gt2karaoryk.html

C#:   if (x is null) {}
来源：http://dali.ehwqpu.com/Article/details/gt2cbkicyam.html

[P07] 防抖与节流
来源：http://dali.zhoulong.xyz/Article/details/gt2xramzfqv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.sysykeji.top/Article/details/gt2jdkydwby.html

PHP:  // 手写时间戳比较
来源：http://dali.yvedp.cn/Article/details/gt2phrdyhnj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258.top/Article/details/gt2gbfudybc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuetiantiany.cn/Article/details/gt2tdejfhac.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yj20258.top/Article/details/gt2ecrhsifo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.fzhhl.top/Article/details/gt2kwitqdtu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yangfankeji.com/Article/details/gt2feskdrdl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shuidangran.top/Article/details/gt2ztmnzsoi.html

[P08] 处理浮点精度问题
来源：http://dali.feifeiyinyue.top/Article/details/gt2xeazydmq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cdnleiting.top/Article/details/gt2qdianubw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gaohongyu789.top/Article/details/gt2djhwphtz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.quarkkingdee.top/Article/details/gt2luomrpus.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.dashuyun.cn/Article/details/gt2enwcwnfk.html


<!-- 参考信息 -->