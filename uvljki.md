代发 wailian999

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zycfv.cn/Article/details/gtolwyegst.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jyoumei.cn/Article/details/gtzfyrcqsr.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtudnukshm.html

M. 命令行 / 进程 / 环境
来源：http://dali.andypj.xyz/Article/details/gtyuourzba.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtjohuimjz.html

[M01] 读取命令行参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjimnniut.html

Py:   sys.argv[1:]
来源：http://dali.jinqigufen.top/Article/details/gtarnatnxx.html

PHP:  $argv;  $argc;
来源：http://dali.daxiang520.top/Article/details/gtwobzpbik.html

JS:   process.argv.slice(2)
来源：http://dali.gogol.net.cn/Article/details/gtxncnxxvs.html

TS:   process.argv.slice(2)
来源：http://dali.gotoacloud.top/Article/details/gtbvlsrjjk.html

Java: args 数组（main 方法参数）
来源：http://dali.smart0.xyz/Article/details/gtcvnlkkbd.html

Go:   os.Args[1:]
来源：http://dali.nwbrower.top/Article/details/gtcubgkpnz.html

Ruby: ARGV
来源：http://dali.hnxiangtu.top/Article/details/gtyukslpqv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpmqewiri.html

[M02] 读取环境变量
来源：http://dali.zhoulong.xyz/Article/details/gtiaybuael.html

Py:   os.environ.get("HOME")
来源：http://dali.bjfxy.top/Article/details/gttbwisisz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sysykeji.top/Article/details/gtbmwztfbv.html

JS:   process.env.HOME
来源：http://dali.yj20258888.top/Article/details/gtlifgtiwr.html

TS:   process.env.HOME
来源：http://dali.jiagoushi.top/Article/details/gtgzmedltg.html

Java: System.getenv("HOME")
来源：http://dali.hnqzz.top/Article/details/gtkuprpjqn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yuxming.cn/Article/details/gtjylxsann.html

Ruby: ENV["HOME"]
来源：http://dali.haohaochexian.top/Article/details/gtdqsujwvj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gtzzygfteu.html

[M03] 执行外部命令
来源：http://dali.yonumen.top/Article/details/gtbndkxytj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jianghu66.top/Article/details/gtlfnhvtxb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sysykeji.top/Article/details/gtujpiacmm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.iojbl.cn/Article/details/gtxvwidwnj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hfpthk.cn/Article/details/gtjlyhtcib.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gttrgsmdcq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shanyushiyangtech.top/Article/details/gttzlagshw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhengqikj.top/Article/details/gtsdmfnefm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cdnleiting.top/Article/details/gtjwdvrvul.html

[M04] 获取当前工作目录
来源：http://dali.quarkkingdee.top/Article/details/gtdfnwejwb.html

Py:   os.getcwd()
来源：http://dali.sxryk.cn/Article/details/gtulqyemcm.html

PHP:  getcwd();
来源：http://dali.gotoacloud.top/Article/details/gtdnrdvzkt.html

JS:   process.cwd()
来源：http://dali.guowangkeji.top/Article/details/gtlywctusg.html

TS:   process.cwd()
来源：http://dali.redwolf501.top/Article/details/gthnhmnnic.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ydzc1.top/Article/details/gtsjczyjqp.html

Go:   os.Getwd()
来源：http://dali.9152youxi.cn/Article/details/gtywkeybmr.html

Ruby: Dir.pwd
来源：http://dali.dianchejie.cn/Article/details/gtjdmiynfa.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.9152youxi.cn/Article/details/gtqkibueda.html

[M05] 设置退出码
来源：http://dali.shuidangran.top/Article/details/gtrxinoxdx.html

Py:   sys.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtvggjsqqw.html

PHP:  exit(1);
来源：http://dali.snrcjt.cn/Article/details/gtymrobtdb.html

JS:   process.exit(1)
来源：http://dali.ybcxt.top/Article/details/gtnkqfouef.html

TS:   process.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtuywchbtn.html

Java: System.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrnhkohtc.html

Go:   os.Exit(1)
来源：http://dali.mhx1999.top/Article/details/gtpbnqpezc.html

Ruby: exit 1
来源：http://dali.jianghu66.top/Article/details/gtrseyscpg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.kuanghao11.cn/Article/details/gtoioaoocu.html

[M06] 向标准错误输出
来源：http://dali.smart0.xyz/Article/details/gtbbibkbzl.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gtzjrhtjwb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtajvxfuar.html

JS:   console.error("err")
来源：http://dali.chenzaomai.com/Article/details/gtvblqqbbk.html

TS:   console.error("err")
来源：http://dali.cucudq.cn/Article/details/gtuunequnm.html

Java: System.err.println("err")
来源：http://dali.yj20258.top/Article/details/gtjuhujkkk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cheryme.top/Article/details/gtawmbejnc.html

Ruby: warn "err"
来源：http://dali.nanxinkj.top/Article/details/gtmobwfxfc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yuanzhike.top/Article/details/gtidasdgbc.html

[M07] 判断是否为主入口
来源：http://dali.birdmap.top/Article/details/gtfygcgvwd.html

Py:   if __name__ == "__main__":
来源：http://dali.cashguo.top/Article/details/gtsjmgwrjw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yvedp.cn/Article/details/gthpjhjpoc.html

JS:   require.main === module
来源：http://dali.jinqigufen.top/Article/details/gtxdpcngfs.html

TS:   require.main === module
来源：http://dali.gaohongyu789.top/Article/details/gtsjolpbia.html

Java: public static void main(String[] args)
来源：http://dali.gotoacloud.top/Article/details/gthzkpfhsr.html

Go:   func main()
来源：http://dali.jqgufenzy.top/Article/details/gtaygcfsal.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shuidangran.top/Article/details/gtvsllplcm.html

C#:   static void Main(string[] args)
来源：http://dali.yuanzhike.top/Article/details/gtiqvphbtg.html

[M08] 获取系统与运行时信息
来源：http://dali.bjfxy.top/Article/details/gtrqkwjzwv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinqigfzy.top/Article/details/gtubtskkok.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.wangdashe.top/Article/details/gticbytffv.html

JS:   process.platform;  process.version
来源：http://dali.xziqi.cn/Article/details/gtuycolnog.html

TS:   process.platform;  process.version
来源：http://dali.hfpthk.cn/Article/details/gtjrttmeam.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jqgfzy.top/Article/details/gtskkcczuc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shuidangran.top/Article/details/gthygiyzlw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hywenlv.cn/Article/details/gtfspqbatd.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.nanxinkj.top/Article/details/gtdcfvmgsn.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtmifxansw.html

N. 数据结构与算法
来源：http://dali.meibo888.top/Article/details/gtvzedudbg.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtzvxqiino.html

[N01] 二分查找（有序数组）
来源：http://dali.hfpthk.cn/Article/details/gtopdhailm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtokvrnlgp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhoulong.xyz/Article/details/gtenpttqbh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tanke756.top/Article/details/gtzkxcopbp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shzxlz.cn/Article/details/gtuueykthc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cashguo.top/Article/details/gtqfoflnaw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtdythptsn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinqigufen.top/Article/details/gtvhwozjyy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gtamsptlmp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhoulong.xyz/Article/details/gteapypnic.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuxming.cn/Article/details/gtzwwwgeke.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shzxlz.cn/Article/details/gtvzocdesy.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.9152youxi.cn/Article/details/gtzqctvmna.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yongpay.top/Article/details/gtrjqgqqmx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sweek.top/Article/details/gtpgkzgkfp.html

Go:   slices.Sort(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkwhqllwz.html

Ruby: arr.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmuspzqwn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhixingplan.top/Article/details/gtswvoxncx.html

[N03] 快速排序（分治示例）
来源：http://dali.jianghu66.top/Article/details/gtvbhgreso.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xylfe.cn/Article/details/gtoggaiult.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yonumen.top/Article/details/gtdynbbifz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.birdmap.top/Article/details/gtlbkdnyln.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.316326.xyz/Article/details/gtuhngjkaz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.316326.xyz/Article/details/gtyoghdnre.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenzaomai.com/Article/details/gtppgukuof.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ydzc1.top/Article/details/gtgxdikggf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.aibaodan.cn/Article/details/gtgglfcmpa.html

[N04] 斐波那契数列
来源：http://dali.nanxuanxn.top/Article/details/gtjdikelxa.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.bjfxy.top/Article/details/gtjcshstwg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sxryk.cn/Article/details/gtoubgrcah.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cqqwz.cn/Article/details/gtulfbxgbx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zycfv.cn/Article/details/gtxyyyyhcy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.bjfxy.top/Article/details/gtijvdijay.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.tian-w.cn/Article/details/gtnzhggenj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hammf.cn/Article/details/gtzunqvizl.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ivvv.top/Article/details/gtgzgrcdhq.html

[N05] 最大公约数
来源：http://dali.pengpengdd.cyou/Article/details/gtjmkrreoa.html

Py:   math.gcd(a, b)
来源：http://dali.snrcjt.cn/Article/details/gtiuudlhkb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.nanxinkj.top/Article/details/gtvdtadfgd.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hammf.cn/Article/details/gtlxocvyoz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jlsjyb.cn/Article/details/gtcyawtgqp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.daria6918.cn/Article/details/gtruyifvpt.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hnxiangtu.top/Article/details/gtuqqkqbkq.html

Ruby: a.gcd(b)
来源：http://dali.wangdashe.top/Article/details/gttibhgnee.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.birdmap.top/Article/details/gtjyreklsw.html

[N06] 判断回文字符串
来源：http://dali.nwbrower.top/Article/details/gtuaalzndg.html

Py:   s == s[::-1]
来源：http://dali.birdmap.top/Article/details/gtilwsvwid.html

PHP:  $s === strrev($s);
来源：http://dali.nanxinkj.top/Article/details/gtxwpzprqw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gtwsfmzxzl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gtdftlnotq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xinyue.icu/Article/details/gtnubjaphq.html

Go:   // 双指针从两端比较
来源：http://dali.hongshengwenyu.top/Article/details/gtfhueunri.html

Ruby: s == s.reverse
来源：http://dali.dianchejie.cn/Article/details/gtsuonhixg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.aibaodan.cn/Article/details/gtbpaxagww.html

[N07] 两数之和（返回下标）
来源：http://dali.havefunace.top/Article/details/gtteqdvhji.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.nanxinkj.top/Article/details/gtmpkvwsny.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shuidangran.top/Article/details/gtqrqdphmq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.bjfxy.top/Article/details/gtlptblgas.html

TS:   // 手写 Map<string, number>
来源：http://dali.0kj1m.cn/Article/details/gtedyjpatw.html

Java: // 手写 HashMap
来源：http://dali.yj202588.top/Article/details/gtcnmafirg.html

Go:   // 手写 map[int]int
来源：http://dali.guowangkeji.top/Article/details/gtcjbloepg.html

Ruby: // 手写 Hash
来源：http://dali.sweek.top/Article/details/gtrksivnfs.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.9152youxi.cn/Article/details/gtqntjuzgl.html

[N08] 生成全排列
来源：http://dali.havefunace.top/Article/details/gtqreuayec.html

Py:   itertools.permutations(arr)
来源：http://dali.ehwqpu.com/Article/details/gtbxzwvnma.html

PHP:  // 手写递归交换
来源：http://dali.zhiwuduotai.top/Article/details/gtqrxtjrha.html

JS:   // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gteihiciyc.html

TS:   // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gtuvfuiugz.html

Java: // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gtuutpecpg.html

Go:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gtizcavtsd.html

Ruby: arr.permutation.to_a
来源：http://dali.yanxiufei.cn/Article/details/gtvfghjdqy.html

C#:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtuscnzfuz.html

[N09] 栈与队列
来源：http://dali.ehwqpu.com/Article/details/gttujddqlc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gthpfuraxo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.guannengcc.top/Article/details/gtmyujxbux.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrzanpvmz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cheryme.top/Article/details/gtchxotivy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.redwolf501.top/Article/details/gtktvdvnsk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwsuvxkyc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nwbrower.top/Article/details/gtxananaon.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gogol.net.cn/Article/details/gtoeuxrqtk.html

[N10] 链表节点定义
来源：http://dali.zhixingplan.top/Article/details/gtrrrmtmwr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsdyluwbz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkdvsqslw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.wangdashe.top/Article/details/gtuzsddgwi.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.pengpengdd.cyou/Article/details/gtwmiozfkk.html

Java: class Node { int v; Node next; }
来源：http://dali.shangyingyoupin.top/Article/details/gthazbqoyz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hammf.cn/Article/details/gtwnvbgeqp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jinqigufen.top/Article/details/gtaqupzozt.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.fengsongda.top/Article/details/gtnxpzjsmd.html

[N11] 二叉树中序遍历
来源：http://dali.yangfankeji.com/Article/details/gtqbaomrbl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gaohongyu789.top/Article/details/gtebsxavdd.html

PHP:  // 手写递归函数
来源：http://dali.yvedp.cn/Article/details/gtynkuxacd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shangyingyoupin.top/Article/details/gtgwqpjbxq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gtsmpasnmy.html

Java: // 手写递归
来源：http://dali.hnqzz.top/Article/details/gtaxbxcbsq.html

Go:   // 手写递归
来源：http://dali.daria6918.cn/Article/details/gtrerfnfom.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvacipmsb.html

C#:   // 手写递归
来源：http://dali.shuidangran.top/Article/details/gtpugqgdxd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cucudq.cn/Article/details/gtwikkhrrb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hysaishi.cn/Article/details/gtmoejpjai.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gotoacloud.top/Article/details/gtxfskcpsz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.smart0.xyz/Article/details/gtrxpjznto.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hysaishi.cn/Article/details/gtmvcqffmy.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guowangkeji.top/Article/details/gtwwaxiigs.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hywenlv.cn/Article/details/gtndivkmmn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ppjwa.cn/Article/details/gtqtjuzgax.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuanzhike.top/Article/details/gtkvflvzek.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtlamsegpr.html

O. 并发与异步
来源：http://dali.cqqwz.cn/Article/details/gtmrduzviu.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gthnmvvhmi.html

[O01] 启动一个线程
来源：http://dali.sxryk.cn/Article/details/gtfihmjsqj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.fengsongda.top/Article/details/gtqmokoceb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shzxlz.cn/Article/details/gtajdmlcgf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.chenjidiqi.icu/Article/details/gtmfkzduzr.html

TS:   // 同 JS
来源：http://dali.wangdashe.top/Article/details/gtjqfaiklw.html

Java: new Thread(() -> f()).start()
来源：http://dali.jiagoushi.top/Article/details/gtevizddoq.html

Go:   go f()
来源：http://dali.jyoumei.cn/Article/details/gtqccczitc.html

Ruby: Thread.new { f }
来源：http://dali.nwbrower.top/Article/details/gtombquyad.html

C#:   Task.Run(() => F());
来源：http://dali.yuanzhike.top/Article/details/gtlqpubsdl.html

[O02] 使用线程池
来源：http://dali.nwbrower.top/Article/details/gtackycpbu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.tanke756.top/Article/details/gtndfktdqf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.gzhubu.top/Article/details/gthpkuwyeo.html

JS:   // worker_threads 线程池
来源：http://dali.smart0.xyz/Article/details/gttafknpki.html

TS:   // worker_threads 线程池
来源：http://dali.meibo888.top/Article/details/gtcmiydvts.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.gogol.net.cn/Article/details/gtfrygzatn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.pycfn.com/Article/details/gtmiavaqgd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jlsjyb.cn/Article/details/gtmlhxfsbq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.c1oappe.top/Article/details/gtdstdauvt.html

[O03] 加锁保护共享数据
来源：http://dali.kuanghao11.cn/Article/details/gtgpjuyvjs.html

Py:   with lock: shared += 1
来源：http://dali.tianlin.xyz/Article/details/gtlllnzdvx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.mhx1999.top/Article/details/gtuiraprhd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.birdmap.top/Article/details/gtwqzcndnj.html

TS:   // 同 JS
来源：http://dali.tanke756.top/Article/details/gtfdtzbwyh.html

Java: synchronized (this) { shared++; }
来源：http://dali.gaohongyu789.top/Article/details/gtpebrtmzh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yongpay.top/Article/details/gtkgphcymp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.nanxinkj.top/Article/details/gtuqtveecg.html

C#:   lock (gate) { shared++; }
来源：http://dali.haohaochexian.top/Article/details/gthyivxvgc.html

[O04] 定义异步函数并等待
来源：http://dali.xylfe.cn/Article/details/gtpoopcscw.html

Py:   async def f():⏎    await g()
来源：http://dali.cashguo.top/Article/details/gtycnlturr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.snrcjt.cn/Article/details/gtqnljucsp.html

JS:   async function f() { await g(); }
来源：http://dali.sweek.top/Article/details/gtrjymxcwj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtxcvaghlk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shanyushiyangtech.top/Article/details/gtwzlnhadm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hfpthk.cn/Article/details/gtsyjxazxr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cucudq.cn/Article/details/gteoxrinyj.html

C#:   async Task F() { await G(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gttiojrbgk.html

[O05] 并发执行并等待全部完成
来源：http://dali.mhx1999.top/Article/details/gttypnaqna.html

Py:   asyncio.gather(*tasks)
来源：http://dali.kuanghao11.cn/Article/details/gtpxhoxxbv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.birdmap.top/Article/details/gtrtjtefqq.html

JS:   await Promise.all(tasks)
来源：http://dali.dashuyun.cn/Article/details/gtduimrnpd.html

TS:   await Promise.all(tasks)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtykdtalku.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.9152youxi.cn/Article/details/gtorwmbihl.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.birdmap.top/Article/details/gtmgoyleci.html

Ruby: threads.map(&:join)
来源：http://dali.zhongyouzk.top/Article/details/gtxofhchpf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ybcxt.top/Article/details/gtspdjnklc.html

[O06] 使用进程池
来源：http://dali.ppjwa.cn/Article/details/gtyoifqirk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shangyingyoupin.top/Article/details/gtaajvszuq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cucudq.cn/Article/details/gtrodbkabk.html

JS:   // child_process / cluster 模块
来源：http://dali.feifeiyinyue.top/Article/details/gtwdmbzxfq.html

TS:   // child_process / cluster 模块
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuvyanhbq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ehwqpu.com/Article/details/gtzvatsfls.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yueranfly.top/Article/details/gtyffrpyaj.html

Ruby: // fork 块
来源：http://dali.gogol.net.cn/Article/details/gttpcrmucp.html

C#:   Parallel.For
来源：http://dali.feifeiyinyue.top/Article/details/gtlubhbsdy.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtqkrwbimp.html

P. 常用工具函数
来源：http://dali.yanxiufei.cn/Article/details/gtswnuspav.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtsrsfjoit.html

[P01] 生成 UUID
来源：http://dali.cheryme.top/Article/details/gtpqszpquj.html

Py:   str(uuid.uuid4())
来源：http://dali.jqgufenzy.top/Article/details/gtswmokhzf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yj202588.top/Article/details/gtnogqlhts.html

JS:   crypto.randomUUID()
来源：http://dali.zhoulong.xyz/Article/details/gtncnlzqat.html

TS:   crypto.randomUUID()
来源：http://dali.yj202588.top/Article/details/gtzlzocllo.html

Java: UUID.randomUUID().toString()
来源：http://dali.cucudq.cn/Article/details/gtaisrhuzk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.andypj.xyz/Article/details/gtprzxnywz.html

Ruby: SecureRandom.uuid
来源：http://dali.nanxinkj.top/Article/details/gtvqwintsj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhixingplan.top/Article/details/gtpmmegjuy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cqqwz.cn/Article/details/gtojkzfrzt.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.havefunace.top/Article/details/gthsgearda.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyrkomken.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yangfankeji.com/Article/details/gtawhetamx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yuanzhike.top/Article/details/gtqaclzltg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.0kj1m.cn/Article/details/gtegnxdopv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jqgfzy.top/Article/details/gtxzxwljdt.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xziqi.cn/Article/details/gtrzzkykee.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinqigfzy.top/Article/details/gtvfrseuep.html

[P03] 生成短随机字符串
来源：http://dali.hnxiangtu.top/Article/details/gtjrcuiahk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhongyouzk.top/Article/details/gtpbezocwh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.svipenyu.cn/Article/details/gtwolopmfw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.bjfxy.top/Article/details/gtjjfwjsuy.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtosxicenp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hnxiangtu.top/Article/details/gtvbcsemfw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.dianchejie.cn/Article/details/gtkbgsdusp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcfhqmpom.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.dashuyun.cn/Article/details/gttqvdoppd.html

[P04] 求长度
来源：http://dali.jqgufenzy.top/Article/details/gttmkbghro.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xziqi.cn/Article/details/gtfxpofebg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhiwuduotai.top/Article/details/gtdeztbpjz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ppjwa.cn/Article/details/gtoiuuenad.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigfzy.top/Article/details/gtfbhcumer.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hnxiangtu.top/Article/details/gtjgfvekrw.html

Go:   len(arr);  len(m)
来源：http://dali.zhengqikj.top/Article/details/gtiealdjfq.html

Ruby: x.length;  x.size
来源：http://dali.hnqzz.top/Article/details/gtufdrkdtr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.andypj.xyz/Article/details/gtttpbzrrz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ivvv.top/Article/details/gtcpfthzny.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hysaishi.cn/Article/details/gtefedzqor.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.aizwys.cn/Article/details/gtupcjbvdc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.sxryk.cn/Article/details/gtcxkkfsfm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yuanzhike.top/Article/details/gttpnheqtk.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnavgscle.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yonumen.top/Article/details/gtbtvhzqaj.html

Ruby: a == b
来源：http://dali.wangdashe.top/Article/details/gtsxjqbwhl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhiwuduotai.top/Article/details/gtnwbywbyi.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gtvejfkdox.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.pengpengdd.cyou/Article/details/gtvghklbvs.html

PHP:  if (empty($x)) {}
来源：http://dali.snrcjt.cn/Article/details/gtnziltbpp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhongyouzk.top/Article/details/gttzzabenu.html

TS:   if (x == null) {}
来源：http://dali.yongpay.top/Article/details/gtxrnrrcok.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ppjwa.cn/Article/details/gtkycilkrb.html

Go:   if x == nil {}
来源：http://dali.jianghu66.top/Article/details/gtbzepgzyf.html


<!-- 参考信息 -->