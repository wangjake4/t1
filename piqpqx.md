代发 wailian999

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jyoumei.cn/Article/details/gtcpaphsjg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gaohongyu789.top/Article/details/gtenvjhztd.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtdouavjsw.html

M. 命令行 / 进程 / 环境
来源：http://dali.feifeiyinyue.top/Article/details/gtgfhigwtq.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtbvkhazsk.html

[M01] 读取命令行参数
来源：http://dali.quarkkingdee.top/Article/details/gtpgldludp.html

Py:   sys.argv[1:]
来源：http://dali.pycfn.com/Article/details/gtyrxyrwmy.html

PHP:  $argv;  $argc;
来源：http://dali.dashuyun.cn/Article/details/gtbqmyjbcz.html

JS:   process.argv.slice(2)
来源：http://dali.nwbrower.top/Article/details/gtlrawiruw.html

TS:   process.argv.slice(2)
来源：http://dali.iojbl.cn/Article/details/gtupmcvwaw.html

Java: args 数组（main 方法参数）
来源：http://dali.zycfv.cn/Article/details/gttmbqvmhi.html

Go:   os.Args[1:]
来源：http://dali.quarkkingdee.top/Article/details/gtxouqvonp.html

Ruby: ARGV
来源：http://dali.c1oappe.top/Article/details/gtwopjljrl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gotoacloud.top/Article/details/gtpbtntezp.html

[M02] 读取环境变量
来源：http://dali.sysykeji.top/Article/details/gtczoknjkj.html

Py:   os.environ.get("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gtsmcjqmfe.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj20258.top/Article/details/gtrlgjbgff.html

JS:   process.env.HOME
来源：http://dali.zhoulong.xyz/Article/details/gtzzleflna.html

TS:   process.env.HOME
来源：http://dali.smart0.xyz/Article/details/gtrrlcpyqh.html

Java: System.getenv("HOME")
来源：http://dali.meibo888.top/Article/details/gtsoydexoa.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.nwbrower.top/Article/details/gtrwkumtwb.html

Ruby: ENV["HOME"]
来源：http://dali.daria6918.cn/Article/details/gtkbryvhul.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jianghu66.top/Article/details/gtdwnzjbjb.html

[M03] 执行外部命令
来源：http://dali.zhixingplan.top/Article/details/gtbkfepjyu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinqigufen.top/Article/details/gtknanucir.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gzhubu.top/Article/details/gtlirtfcpc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhongyouzk.top/Article/details/gtryuznsfz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangshuangyany.cn/Article/details/gtqdzrczge.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shangyingyoupin.top/Article/details/gtaebmxnvd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ydzc1.top/Article/details/gtdksjnkls.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.dashuyun.cn/Article/details/gtmywrqiir.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gotoacloud.top/Article/details/gtwskgxjtw.html

[M04] 获取当前工作目录
来源：http://dali.zhengqikj.top/Article/details/gtlteiecqk.html

Py:   os.getcwd()
来源：http://dali.316326.xyz/Article/details/gtrkuharnn.html

PHP:  getcwd();
来源：http://dali.hysaishi.cn/Article/details/gtupozikde.html

JS:   process.cwd()
来源：http://dali.yuxming.cn/Article/details/gtpaxllqik.html

TS:   process.cwd()
来源：http://dali.ppjwa.cn/Article/details/gtogfugpni.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yangfankeji.com/Article/details/gtlssadsxc.html

Go:   os.Getwd()
来源：http://dali.hysaishi.cn/Article/details/gtsafacphx.html

Ruby: Dir.pwd
来源：http://dali.0kj1m.cn/Article/details/gtfcqobsze.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hysaishi.cn/Article/details/gtmoahtudk.html

[M05] 设置退出码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzxhhppkm.html

Py:   sys.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtackozavo.html

PHP:  exit(1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfhwqpbbi.html

JS:   process.exit(1)
来源：http://dali.daria6918.cn/Article/details/gtkniuvkqo.html

TS:   process.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gtsnhpansd.html

Java: System.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gtjexcarpl.html

Go:   os.Exit(1)
来源：http://dali.ehwqpu.com/Article/details/gthrlnbmjb.html

Ruby: exit 1
来源：http://dali.yanxiufei.cn/Article/details/gtplvidgps.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yueranfly.top/Article/details/gtvivtnymt.html

[M06] 向标准错误输出
来源：http://dali.mhx1999.top/Article/details/gtugbyipqr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hysaishi.cn/Article/details/gtwhvwhneu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yangfankeji.com/Article/details/gtqzrutlpa.html

JS:   console.error("err")
来源：http://dali.aizwys.cn/Article/details/gtutwcoise.html

TS:   console.error("err")
来源：http://dali.svipenyu.cn/Article/details/gtiftsrkvz.html

Java: System.err.println("err")
来源：http://dali.gotoacloud.top/Article/details/gtzhttumtv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sysykeji.top/Article/details/gtzorhnzoa.html

Ruby: warn "err"
来源：http://dali.shanyushiyangtech.top/Article/details/gtpbsgqmkk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gotoacloud.top/Article/details/gtojgdntii.html

[M07] 判断是否为主入口
来源：http://dali.hongshengwenyu.top/Article/details/gtlkakmyai.html

Py:   if __name__ == "__main__":
来源：http://dali.shangyingyoupin.top/Article/details/gttctbasaf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yuxming.cn/Article/details/gtyuexcich.html

JS:   require.main === module
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsrwwbozd.html

TS:   require.main === module
来源：http://dali.hysaishi.cn/Article/details/gtcvfwjyxu.html

Java: public static void main(String[] args)
来源：http://dali.smart0.xyz/Article/details/gtggldaila.html

Go:   func main()
来源：http://dali.smart0.xyz/Article/details/gtankofjyq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.316326.xyz/Article/details/gtetbwkqch.html

C#:   static void Main(string[] args)
来源：http://dali.gzhubu.top/Article/details/gtzjfgiskl.html

[M08] 获取系统与运行时信息
来源：http://dali.yonumen.top/Article/details/gtbclhnrab.html

Py:   platform.system();  platform.python_version()
来源：http://dali.aibaodan.cn/Article/details/gtrevyupkx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sweek.top/Article/details/gtqgjsiyat.html

JS:   process.platform;  process.version
来源：http://dali.daxiang520.top/Article/details/gtzikwjovn.html

TS:   process.platform;  process.version
来源：http://dali.chenlongwang.top/Article/details/gtkqhtwpbo.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ybcxt.top/Article/details/gtqmjlirlt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jqgfzy.top/Article/details/gtdbenljng.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.chenjidiqi.icu/Article/details/gtdaakhwnd.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.wangdashe.top/Article/details/gtunbqorcj.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtvifxawiv.html

N. 数据结构与算法
来源：http://dali.bjfxy.top/Article/details/gtdsecxcki.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtblxmiqlq.html

[N01] 二分查找（有序数组）
来源：http://dali.snrcjt.cn/Article/details/gtvoisdtyz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtmxuioyum.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.smart0.xyz/Article/details/gtxrxnlyvk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdboydzee.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jlsjyb.cn/Article/details/gtytsfvqql.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtanktxdoq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gtiwhqntyh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.havefunace.top/Article/details/gtqsxhyklq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtffutoscv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gzhubu.top/Article/details/gtvgmbqsab.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hammf.cn/Article/details/gttdkrlejd.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ivvv.top/Article/details/gtvkclkyfm.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hfpthk.cn/Article/details/gtkgpwrlhp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.0kj1m.cn/Article/details/gtookoivxc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xinyue.icu/Article/details/gtaaowbfxf.html

Go:   slices.Sort(arr)
来源：http://dali.chenlongwang.top/Article/details/gtwnqablmq.html

Ruby: arr.sort
来源：http://dali.quarkkingdee.top/Article/details/gtdexomhuj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.daria6918.cn/Article/details/gtttnmxbxk.html

[N03] 快速排序（分治示例）
来源：http://dali.chenjidiqi.icu/Article/details/gtmcayorsl.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinghuilouyu.cn/Article/details/gtqfrnmbns.html

PHP:  // 递归实现，或用 usort
来源：http://dali.daria6918.cn/Article/details/gthipxuelo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.svipenyu.cn/Article/details/gttmunfvgs.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ybcxt.top/Article/details/gtqkktzkxb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.guowangkeji.top/Article/details/gthgimukel.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jiagoushi.top/Article/details/gtqqskipeo.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.smart0.xyz/Article/details/gtsqrekndx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gzhubu.top/Article/details/gtuxziqont.html

[N04] 斐波那契数列
来源：http://dali.jqgfzy.top/Article/details/gtfdfqkgat.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtwyvdqytw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.guannengcc.top/Article/details/gtkreknlrw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tanke756.top/Article/details/gtqwsbrkca.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gteygpaouf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zycfv.cn/Article/details/gtajooqodc.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.0kj1m.cn/Article/details/gtltmxldcd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ivvv.top/Article/details/gtiivkrlov.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gtvzaprmql.html

[N05] 最大公约数
来源：http://dali.wangdashe.top/Article/details/gttuvkhbac.html

Py:   math.gcd(a, b)
来源：http://dali.ppjwa.cn/Article/details/gtamtuhgbh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yvedp.cn/Article/details/gtgoaqwyix.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuanzx.com/Article/details/gtjrfjxhwc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yongpay.top/Article/details/gtkrpkoijr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hfpthk.cn/Article/details/gtshbhryza.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.svipenyu.cn/Article/details/gtkybdiizj.html

Ruby: a.gcd(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwbjukhuc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.chenlongwang.top/Article/details/gtzzluucmv.html

[N06] 判断回文字符串
来源：http://dali.jinqigufen.top/Article/details/gtdkmiwauo.html

Py:   s == s[::-1]
来源：http://dali.zhoulong.xyz/Article/details/gtqdsyutfi.html

PHP:  $s === strrev($s);
来源：http://dali.kuanghao11.cn/Article/details/gtesikhymx.html

JS:   s === [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gtjmmjpxgv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gtijeomhvk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.snrcjt.cn/Article/details/gtiuegfgii.html

Go:   // 双指针从两端比较
来源：http://dali.cqqwz.cn/Article/details/gtmirznvqm.html

Ruby: s == s.reverse
来源：http://dali.yanxiufei.cn/Article/details/gttiqhporf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jianghu66.top/Article/details/gtnrcjbmbe.html

[N07] 两数之和（返回下标）
来源：http://dali.sysykeji.top/Article/details/gtgrqijhvs.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpjpsjkqe.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hongshengwenyu.top/Article/details/gtswbajwms.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cashguo.top/Article/details/gtvmaokdgo.html

TS:   // 手写 Map<string, number>
来源：http://dali.svipenyu.cn/Article/details/gtxupfrdmj.html

Java: // 手写 HashMap
来源：http://dali.zhengqikj.top/Article/details/gtavixjxxc.html

Go:   // 手写 map[int]int
来源：http://dali.dashuyun.cn/Article/details/gtcxomaajr.html

Ruby: // 手写 Hash
来源：http://dali.chenjidiqi.icu/Article/details/gtiiwxjqhr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cqqwz.cn/Article/details/gtzshnasik.html

[N08] 生成全排列
来源：http://dali.vqdsnc.cn/Article/details/gtsznvdfal.html

Py:   itertools.permutations(arr)
来源：http://dali.sxryk.cn/Article/details/gtenfywgrm.html

PHP:  // 手写递归交换
来源：http://dali.ybcxt.top/Article/details/gtjmgcrzty.html

JS:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gtwktbjezf.html

TS:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gtnpkxsrjw.html

Java: // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gtxxsonuqe.html

Go:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtxodeliza.html

Ruby: arr.permutation.to_a
来源：http://dali.xziqi.cn/Article/details/gtcgamnbty.html

C#:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gteneygxzn.html

[N09] 栈与队列
来源：http://dali.snrcjt.cn/Article/details/gtwvoggfsa.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gticbcrzbz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.snrcjt.cn/Article/details/gtrdvzhhzr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.daria6918.cn/Article/details/gtmdpveqiu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xylfe.cn/Article/details/gttgprkiev.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.svipenyu.cn/Article/details/gtnldtdwah.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpdimpluc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sxryk.cn/Article/details/gtsdmidgcy.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.meibo888.top/Article/details/gtrupgthcz.html

[N10] 链表节点定义
来源：http://dali.guowangkeji.top/Article/details/gtjndwusta.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.fengsongda.top/Article/details/gtrxnaqhxo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.guannengcc.top/Article/details/gtewmfdatp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hfpthk.cn/Article/details/gtirepaimx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gtmprrxfmu.html

Java: class Node { int v; Node next; }
来源：http://dali.xinyue.icu/Article/details/gtwyoegtjg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.pengpengdd.cyou/Article/details/gtzmndatom.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhongyouzk.top/Article/details/gtysvidqjl.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yongpay.top/Article/details/gtzmvefhaq.html

[N11] 二叉树中序遍历
来源：http://dali.jiagoushi.top/Article/details/gtbudmhysz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.wangshuangyany.cn/Article/details/gtddzjhjle.html

PHP:  // 手写递归函数
来源：http://dali.andypj.xyz/Article/details/gtnceoguxz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.snrcjt.cn/Article/details/gtvlxmvxpw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxuanxn.top/Article/details/gtfkuqeyxt.html

Java: // 手写递归
来源：http://dali.feifeiyinyue.top/Article/details/gtlrojwlmf.html

Go:   // 手写递归
来源：http://dali.yvedp.cn/Article/details/gtjgwbxyun.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.tanke756.top/Article/details/gtawghyesb.html

C#:   // 手写递归
来源：http://dali.hammf.cn/Article/details/gtcbrjmzxk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yj202588.top/Article/details/gtplrblwjh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.sysykeji.top/Article/details/gtpymsktus.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.pycfn.com/Article/details/gtanucyvxu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tian-w.cn/Article/details/gtawmpwnod.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.iojbl.cn/Article/details/gtunvtqvet.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.andypj.xyz/Article/details/gtyuslskgp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.dianchejie.cn/Article/details/gteccatnsk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtabjanmsh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fzhhl.top/Article/details/gtgqfzqhdz.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtueixhywn.html

O. 并发与异步
来源：http://dali.ehwqpu.com/Article/details/gtlibqpmlu.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtefqarqjb.html

[O01] 启动一个线程
来源：http://dali.andypj.xyz/Article/details/gtwukpfclj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xziqi.cn/Article/details/gtngvmclwa.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cheryme.top/Article/details/gtkaeuhhwn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.guannengcc.top/Article/details/gtokityxiq.html

TS:   // 同 JS
来源：http://dali.ivvv.top/Article/details/gtcifagxnd.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhoulong.xyz/Article/details/gtnkklclcz.html

Go:   go f()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzvggihuu.html

Ruby: Thread.new { f }
来源：http://dali.hnxiangtu.top/Article/details/gtwicombjg.html

C#:   Task.Run(() => F());
来源：http://dali.meibo888.top/Article/details/gtcciwzhye.html

[O02] 使用线程池
来源：http://dali.chenzaomai.com/Article/details/gtaciwtwxw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hfpthk.cn/Article/details/gtdictlqhq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinghuilouyu.cn/Article/details/gtqmrzqdys.html

JS:   // worker_threads 线程池
来源：http://dali.hongshengwenyu.top/Article/details/gtpidfetbq.html

TS:   // worker_threads 线程池
来源：http://dali.daria6918.cn/Article/details/gttwbhvcqb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtffwvkyer.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfzhtzqge.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.wangshuangyany.cn/Article/details/gtvonohmof.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.havefunace.top/Article/details/gtgakclhbe.html

[O03] 加锁保护共享数据
来源：http://dali.cashguo.top/Article/details/gtmhdssmbk.html

Py:   with lock: shared += 1
来源：http://dali.316326.xyz/Article/details/gtgbbwnuaa.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hnxiangtu.top/Article/details/gtswuxxfsv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ivvv.top/Article/details/gtnfdhqmpz.html

TS:   // 同 JS
来源：http://dali.yanxiufei.cn/Article/details/gtzumsxity.html

Java: synchronized (this) { shared++; }
来源：http://dali.shzxlz.cn/Article/details/gtblmiedxy.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.bjfxy.top/Article/details/gtzmbgzsdt.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xylfe.cn/Article/details/gtxazjnkxg.html

C#:   lock (gate) { shared++; }
来源：http://dali.daria6918.cn/Article/details/gtqxfjzemn.html

[O04] 定义异步函数并等待
来源：http://dali.nanxinkj.top/Article/details/gtircmzwgd.html

Py:   async def f():⏎    await g()
来源：http://dali.feifeiyinyue.top/Article/details/gtfmyfcaiy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xziqi.cn/Article/details/gtideumgxu.html

JS:   async function f() { await g(); }
来源：http://dali.jiagoushi.top/Article/details/gtcpfjdckv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cdnleiting.top/Article/details/gtoujuburl.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sxryk.cn/Article/details/gtkbjqyeii.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.fzhhl.top/Article/details/gtzmxmcrkn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yuxming.cn/Article/details/gthipfqlmf.html

C#:   async Task F() { await G(); }
来源：http://dali.nanxinkj.top/Article/details/gtqtnfbpoy.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinqigfzy.top/Article/details/gtkuvacyhr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xziqi.cn/Article/details/gtpxfkufxw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhengqikj.top/Article/details/gtzfwwxzwf.html

JS:   await Promise.all(tasks)
来源：http://dali.smart0.xyz/Article/details/gtguswrcon.html

TS:   await Promise.all(tasks)
来源：http://dali.sxryk.cn/Article/details/gtfiswdkar.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hnxiangtu.top/Article/details/gtnsgxemsn.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhixingplan.top/Article/details/gtwdqhxhvl.html

Ruby: threads.map(&:join)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttspywxfn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.guowangkeji.top/Article/details/gtfnsrkukx.html

[O06] 使用进程池
来源：http://dali.tian-w.cn/Article/details/gtklmgivpz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.svipenyu.cn/Article/details/gtdvgrmoln.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jyoumei.cn/Article/details/gttwfttdgx.html

JS:   // child_process / cluster 模块
来源：http://dali.cdnleiting.top/Article/details/gtlfmqwfjc.html

TS:   // child_process / cluster 模块
来源：http://dali.jinghuilouyu.cn/Article/details/gtpucxehre.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.redwolf501.top/Article/details/gtojkqijcd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.andypj.xyz/Article/details/gtlkdbqrdz.html

Ruby: // fork 块
来源：http://dali.xylfe.cn/Article/details/gthspdyjqm.html

C#:   Parallel.For
来源：http://dali.cheryme.top/Article/details/gtmxysnjfn.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtomozdcne.html

P. 常用工具函数
来源：http://dali.nanxinkj.top/Article/details/gtoinungql.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtfzycfxne.html

[P01] 生成 UUID
来源：http://dali.yuanzhike.top/Article/details/gtwgjuuzki.html

Py:   str(uuid.uuid4())
来源：http://dali.aizwys.cn/Article/details/gtknfnddka.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.bjfxy.top/Article/details/gtbudpgsao.html

JS:   crypto.randomUUID()
来源：http://dali.quarkkingdee.top/Article/details/gtijvskemn.html

TS:   crypto.randomUUID()
来源：http://dali.yangfankeji.com/Article/details/gtdkbykgsb.html

Java: UUID.randomUUID().toString()
来源：http://dali.wangdashe.top/Article/details/gtqrbwzwpm.html

Go:   // 用 github.com/google/uuid
来源：http://dali.guowangkeji.top/Article/details/gteyvurrae.html

Ruby: SecureRandom.uuid
来源：http://dali.jinqigufen.top/Article/details/gttuozkhgg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yj20258888.top/Article/details/gtcqugeehj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hywenlv.cn/Article/details/gtrlkntpch.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.feifeiyinyue.top/Article/details/gtjdlozgel.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yvedp.cn/Article/details/gtlfudumiq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hnqzz.top/Article/details/gtabhuejty.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.mhx1999.top/Article/details/gtxnxyqxei.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shzxlz.cn/Article/details/gtwvcsgiyj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.nwbrower.top/Article/details/gtqaggghgl.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.0kj1m.cn/Article/details/gtokvmxkgw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.chenlongwang.top/Article/details/gtqroutpjb.html

[P03] 生成短随机字符串
来源：http://dali.mhx1999.top/Article/details/gtnacidjbo.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jinqigufen.top/Article/details/gtxvkqqlaq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sxryk.cn/Article/details/gthadfrbsz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258.top/Article/details/gtdgergmqg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.mhx1999.top/Article/details/gtbhmgbkwc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhengqikj.top/Article/details/gtqhhrvtog.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnojafmrp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gotoacloud.top/Article/details/gtiwriqnxp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.dashuyun.cn/Article/details/gtegbjadbx.html

[P04] 求长度
来源：http://dali.xylfe.cn/Article/details/gtlsbxvwhz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hfpthk.cn/Article/details/gtllfzdpvd.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gtfyzaaydv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hysaishi.cn/Article/details/gtpdwlpbef.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hnqzz.top/Article/details/gtiuxvepsc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.smart0.xyz/Article/details/gtojgxwqwq.html

Go:   len(arr);  len(m)
来源：http://dali.meibo888.top/Article/details/gtsksgcrom.html

Ruby: x.length;  x.size
来源：http://dali.xuetiantiany.cn/Article/details/gtinrsodxl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shanyushiyangtech.top/Article/details/gtzzpbzrbw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yj20258.top/Article/details/gtfacutcrk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shangyingyoupin.top/Article/details/gtcwquovfm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.pycfn.com/Article/details/gtgldtssaf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ivvv.top/Article/details/gtjaqlkizm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hnxiangtu.top/Article/details/gteczslzva.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gzhubu.top/Article/details/gtkbnvitaf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtztgkulxh.html

Ruby: a == b
来源：http://dali.snrcjt.cn/Article/details/gtwtkuelso.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.daxiang520.top/Article/details/gtuovkbzlq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shangyingyoupin.top/Article/details/gtltnzyror.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.fzhhl.top/Article/details/gtsyihieof.html

PHP:  if (empty($x)) {}
来源：http://dali.tanke756.top/Article/details/gtyywgdbek.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yueranfly.top/Article/details/gtcttzyifk.html

TS:   if (x == null) {}
来源：http://dali.9152youxi.cn/Article/details/gttfgtxlgl.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ppjwa.cn/Article/details/gtdlnbdded.html

Go:   if x == nil {}
来源：http://dali.havefunace.top/Article/details/gtiqdpqpxd.html


<!-- 参考信息 -->