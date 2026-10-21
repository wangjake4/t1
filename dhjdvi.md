代发 wailian999

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258888.top/Article/details/gtlixsxcsj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ybcxt.top/Article/details/gtiyqzwmot.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xuanzx.com/Article/details/gtpwohsrth.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhengqikj.top/Article/details/gttvarpqfc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cucudq.cn/Article/details/gtuebtxsyq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.bjfxy.top/Article/details/gtgqtdeejn.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtywpwpwpy.html

M. 命令行 / 进程 / 环境
来源：http://dali.fzhhl.top/Article/details/gtnmanmxrz.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtquceavce.html

[M01] 读取命令行参数
来源：http://dali.yuxming.cn/Article/details/gtkfmhblnt.html

Py:   sys.argv[1:]
来源：http://dali.xziqi.cn/Article/details/gtgnandflv.html

PHP:  $argv;  $argc;
来源：http://dali.snrcjt.cn/Article/details/gthqaauyas.html

JS:   process.argv.slice(2)
来源：http://dali.ehwqpu.com/Article/details/gtxpwzgpvm.html

TS:   process.argv.slice(2)
来源：http://dali.fzhhl.top/Article/details/gtnbzutxin.html

Java: args 数组（main 方法参数）
来源：http://dali.zdqjudy.top/Article/details/gtvcfrwbgo.html

Go:   os.Args[1:]
来源：http://dali.yongpay.top/Article/details/gtuwkdcoyu.html

Ruby: ARGV
来源：http://dali.cqqwz.cn/Article/details/gtaqqvtzxa.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zdqjudy.top/Article/details/gtrsofzqtf.html

[M02] 读取环境变量
来源：http://dali.guannengcc.top/Article/details/gteoqfqpji.html

Py:   os.environ.get("HOME")
来源：http://dali.aibaodan.cn/Article/details/gtsoxhnqdx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yangfankeji.com/Article/details/gtfcciiawa.html

JS:   process.env.HOME
来源：http://dali.nanxinkj.top/Article/details/gtmojldcro.html

TS:   process.env.HOME
来源：http://dali.sysykeji.top/Article/details/gtuardevnl.html

Java: System.getenv("HOME")
来源：http://dali.ppjwa.cn/Article/details/gtznfwamrq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xziqi.cn/Article/details/gtykdnipxx.html

Ruby: ENV["HOME"]
来源：http://dali.redwolf501.top/Article/details/gthifhsnbh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ehwqpu.com/Article/details/gtsdyhnsde.html

[M03] 执行外部命令
来源：http://dali.zycfv.cn/Article/details/gtdbsgmoex.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jlsjyb.cn/Article/details/gtzproptnv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cheryme.top/Article/details/gtxqpjfiag.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xinyue.icu/Article/details/gtwtudvtgv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zycfv.cn/Article/details/gtsrlnnjcb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hnxiangtu.top/Article/details/gtjyqcirww.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.svipenyu.cn/Article/details/gtfepppxog.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tian-w.cn/Article/details/gtvxdboymz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.iojbl.cn/Article/details/gtxfewkmfr.html

[M04] 获取当前工作目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gtudcuhduh.html

Py:   os.getcwd()
来源：http://dali.havefunace.top/Article/details/gtkwbpaodf.html

PHP:  getcwd();
来源：http://dali.yvedp.cn/Article/details/gtgygrxpok.html

JS:   process.cwd()
来源：http://dali.sxryk.cn/Article/details/gtpjezrngy.html

TS:   process.cwd()
来源：http://dali.sxryk.cn/Article/details/gtweuxjlve.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yongpay.top/Article/details/gtxeidjpxe.html

Go:   os.Getwd()
来源：http://dali.yanxiufei.cn/Article/details/gtnkroscgb.html

Ruby: Dir.pwd
来源：http://dali.ybcxt.top/Article/details/gtkfdvedsl.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nwbrower.top/Article/details/gtvbxjfmyq.html

[M05] 设置退出码
来源：http://dali.xuanzx.com/Article/details/gtvzpaofjd.html

Py:   sys.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gtnqpwshxg.html

PHP:  exit(1);
来源：http://dali.sufxvd.cn/Article/details/gtaxdflcvc.html

JS:   process.exit(1)
来源：http://dali.guannengcc.top/Article/details/gthhefkjfa.html

TS:   process.exit(1)
来源：http://dali.meibo888.top/Article/details/gtbuaiulet.html

Java: System.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtrtzftjgq.html

Go:   os.Exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gthmvaqgyz.html

Ruby: exit 1
来源：http://dali.ppjwa.cn/Article/details/gtixnxcihn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhixingplan.top/Article/details/gticqgeabu.html

[M06] 向标准错误输出
来源：http://dali.hammf.cn/Article/details/gtfhiuaizo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.c1oappe.top/Article/details/gtrtoehnmt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.chenzaomai.com/Article/details/gtuquineoz.html

JS:   console.error("err")
来源：http://dali.meibo888.top/Article/details/gtmbsrdhpq.html

TS:   console.error("err")
来源：http://dali.gzhubu.top/Article/details/gtlotbisgs.html

Java: System.err.println("err")
来源：http://dali.xuanzx.com/Article/details/gterzyvcow.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinqigfzy.top/Article/details/gtniixjids.html

Ruby: warn "err"
来源：http://dali.sufxvd.cn/Article/details/gtvphmqxfa.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nanxuanxn.top/Article/details/gtliszdped.html

[M07] 判断是否为主入口
来源：http://dali.xuetiantiany.cn/Article/details/gtnthbsxdq.html

Py:   if __name__ == "__main__":
来源：http://dali.chenzaomai.com/Article/details/gtwsrmprnm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hywenlv.cn/Article/details/gteaqbkuho.html

JS:   require.main === module
来源：http://dali.nwbrower.top/Article/details/gtymwqdwke.html

TS:   require.main === module
来源：http://dali.yj202588.top/Article/details/gtdccknjhl.html

Java: public static void main(String[] args)
来源：http://dali.zhixingplan.top/Article/details/gtyguacbzc.html

Go:   func main()
来源：http://dali.316326.xyz/Article/details/gtrotrhjyc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.pengpengdd.cyou/Article/details/gtefcsudzq.html

C#:   static void Main(string[] args)
来源：http://dali.daria6918.cn/Article/details/gtnfalgfst.html

[M08] 获取系统与运行时信息
来源：http://dali.pycfn.com/Article/details/gtswburakb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sweek.top/Article/details/gtnqxysvsy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ybcxt.top/Article/details/gtoofoohpe.html

JS:   process.platform;  process.version
来源：http://dali.yueranfly.top/Article/details/gtixnbyghb.html

TS:   process.platform;  process.version
来源：http://dali.shzxlz.cn/Article/details/gtspwqxmdu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nwbrower.top/Article/details/gtfxpfstxb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.nanxuanxn.top/Article/details/gtyixbjwia.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.tian-w.cn/Article/details/gtvxcgxawv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ydzc1.top/Article/details/gtrwhijlsl.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gthbhjryyc.html

N. 数据结构与算法
来源：http://dali.gzhubu.top/Article/details/gtpfklhysn.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtbdzsyfpe.html

[N01] 二分查找（有序数组）
来源：http://dali.sufxvd.cn/Article/details/gtndoicgtf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtezwbnzfb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ybcxt.top/Article/details/gtajszkwxv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gtwutxkfxw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthvxaufrx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtjmyxxgua.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtdzknvyvd.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.svipenyu.cn/Article/details/gtgmvodjsa.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtuypigimb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sxryk.cn/Article/details/gtvtwrlfvl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhixingplan.top/Article/details/gtxcgkwrhy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cqqwz.cn/Article/details/gtlezngpou.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.havefunace.top/Article/details/gtwjgfnyth.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jianghu66.top/Article/details/gtomrrsqtu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.dianchejie.cn/Article/details/gtygdrhnxq.html

Go:   slices.Sort(arr)
来源：http://dali.sufxvd.cn/Article/details/gtlntbtfva.html

Ruby: arr.sort
来源：http://dali.jinghuilouyu.cn/Article/details/gtkgopojci.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.meibo888.top/Article/details/gtiojoewqm.html

[N03] 快速排序（分治示例）
来源：http://dali.zhixingplan.top/Article/details/gthtbciawt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.316326.xyz/Article/details/gtjdkqoijd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.dashuyun.cn/Article/details/gtisczyldp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ppjwa.cn/Article/details/gtarskazhh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258888.top/Article/details/gtwblttbca.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hammf.cn/Article/details/gtzunywgfm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqznftgrh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hysaishi.cn/Article/details/gtsrsncelf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jlsjyb.cn/Article/details/gttycvbmfo.html

[N04] 斐波那契数列
来源：http://dali.ppjwa.cn/Article/details/gtjbimpflr.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigfzy.top/Article/details/gtqpdmnwyf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.dashuyun.cn/Article/details/gtaxzdpwgj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigufen.top/Article/details/gtedbvoybm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtoauryhrr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.tanke756.top/Article/details/gtopvbwezt.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.316326.xyz/Article/details/gtlbpvwuwq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.aizwys.cn/Article/details/gteylodmgl.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gtndekbtpn.html

[N05] 最大公约数
来源：http://dali.c1oappe.top/Article/details/gtowrdwbqj.html

Py:   math.gcd(a, b)
来源：http://dali.zhiwuduotai.top/Article/details/gtvtxkgpzj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gtbqunbwvs.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sxryk.cn/Article/details/gtfufcuyjd.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hongshengwenyu.top/Article/details/gtuxrlwwqn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.mhx1999.top/Article/details/gtbmtenbxg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hysaishi.cn/Article/details/gtxixdifqy.html

Ruby: a.gcd(b)
来源：http://dali.cqqwz.cn/Article/details/gttrtxvhdi.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yongpay.top/Article/details/gtgwrtruzj.html

[N06] 判断回文字符串
来源：http://dali.wangdashe.top/Article/details/gtwdsqrffj.html

Py:   s == s[::-1]
来源：http://dali.pycfn.com/Article/details/gttlkyapkm.html

PHP:  $s === strrev($s);
来源：http://dali.guowangkeji.top/Article/details/gtpsjycptf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ehwqpu.com/Article/details/gtrouucyiu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gtslhnzhym.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jyoumei.cn/Article/details/gtnrgfgchs.html

Go:   // 双指针从两端比较
来源：http://dali.yuanzhike.top/Article/details/gtympifcct.html

Ruby: s == s.reverse
来源：http://dali.sweek.top/Article/details/gttybjocsh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.tianlin.xyz/Article/details/gtxeohvqgf.html

[N07] 两数之和（返回下标）
来源：http://dali.feifeiyinyue.top/Article/details/gtfuicrdwz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hongshengwenyu.top/Article/details/gtyqszygqd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sufxvd.cn/Article/details/gtpvkkejlu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sxryk.cn/Article/details/gtnfnbsciw.html

TS:   // 手写 Map<string, number>
来源：http://dali.yonumen.top/Article/details/gtcdiznupr.html

Java: // 手写 HashMap
来源：http://dali.jlsjyb.cn/Article/details/gtczadewgx.html

Go:   // 手写 map[int]int
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoskczxrb.html

Ruby: // 手写 Hash
来源：http://dali.cqqwz.cn/Article/details/gtqrthbdis.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.haohaochexian.top/Article/details/gtnkdkqcaq.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gthxfnghtf.html

Py:   itertools.permutations(arr)
来源：http://dali.redwolf501.top/Article/details/gtinnrfqvy.html

PHP:  // 手写递归交换
来源：http://dali.jinqigufen.top/Article/details/gtfpsbtabn.html

JS:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gtlyhaynyh.html

TS:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gtmmthbsxj.html

Java: // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gtsxbcejig.html

Go:   // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gtialcektj.html

Ruby: arr.permutation.to_a
来源：http://dali.daria6918.cn/Article/details/gttzzqxpuc.html

C#:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gtplrgpysv.html

[N09] 栈与队列
来源：http://dali.hnxiangtu.top/Article/details/gtgphhkfcb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.andypj.xyz/Article/details/gtpvalggtu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.tanke756.top/Article/details/gtqlswccrb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.meibo888.top/Article/details/gtlhdrdshu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xinyue.icu/Article/details/gtpxhwbjus.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.pengpengdd.cyou/Article/details/gtnohphqof.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xinyue.icu/Article/details/gtgcjhicua.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jqgufenzy.top/Article/details/gtsfoxqtef.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbvabupfi.html

[N10] 链表节点定义
来源：http://dali.guowangkeji.top/Article/details/gtmrgajpvr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jlsjyb.cn/Article/details/gtmaxgyumg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hywenlv.cn/Article/details/gtssgblpup.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.meibo888.top/Article/details/gtxaoiryfo.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.guowangkeji.top/Article/details/gtvrmvyzgm.html

Java: class Node { int v; Node next; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvtvvywmu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cqqwz.cn/Article/details/gtfciggkju.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.fzhhl.top/Article/details/gtdxnjzobk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjjqqotyt.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gtaxzgeafu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yj202588.top/Article/details/gtcwnlodvn.html

PHP:  // 手写递归函数
来源：http://dali.shangyingyoupin.top/Article/details/gtuhbtkkro.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnxiangtu.top/Article/details/gthitlzwtf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.kuanghao11.cn/Article/details/gtstvbdlam.html

Java: // 手写递归
来源：http://dali.zhongyouzk.top/Article/details/gtiyslvsek.html

Go:   // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gtnvvpkcwa.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yanxiufei.cn/Article/details/gttihyples.html

C#:   // 手写递归
来源：http://dali.jinqigufen.top/Article/details/gtwwjximys.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gotoacloud.top/Article/details/gtisvolaxv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.fzhhl.top/Article/details/gttxyhxkqt.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhixingplan.top/Article/details/gtjxtvuxon.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.0kj1m.cn/Article/details/gtoepntjiv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dashuyun.cn/Article/details/gtfrlyjlts.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aibaodan.cn/Article/details/gtulcajnww.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.svipenyu.cn/Article/details/gtseturzfb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.wangdashe.top/Article/details/gtnikejpnf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cqqwz.cn/Article/details/gtrqgigsvy.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtjcgdjnpn.html

O. 并发与异步
来源：http://dali.jianghu66.top/Article/details/gtsuvqixed.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtzaxpltwp.html

[O01] 启动一个线程
来源：http://dali.cqqwz.cn/Article/details/gtenfsbguk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.fzhhl.top/Article/details/gtafnsnyac.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhixingplan.top/Article/details/gtmkggalsq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yvedp.cn/Article/details/gtapwtuqfr.html

TS:   // 同 JS
来源：http://dali.sufxvd.cn/Article/details/gtmjofdgzc.html

Java: new Thread(() -> f()).start()
来源：http://dali.shzxlz.cn/Article/details/gticgajymk.html

Go:   go f()
来源：http://dali.316326.xyz/Article/details/gtfgyunbpp.html

Ruby: Thread.new { f }
来源：http://dali.chenjidiqi.icu/Article/details/gtptkicunw.html

C#:   Task.Run(() => F());
来源：http://dali.c1oappe.top/Article/details/gtzfkniomt.html

[O02] 使用线程池
来源：http://dali.c1oappe.top/Article/details/gtqntucoyo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jianghu66.top/Article/details/gtniqflrhe.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.dianchejie.cn/Article/details/gtifrggrdx.html

JS:   // worker_threads 线程池
来源：http://dali.0kj1m.cn/Article/details/gtfwjtsoaj.html

TS:   // worker_threads 线程池
来源：http://dali.nanxuanxn.top/Article/details/gtjsjnclxb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yuxming.cn/Article/details/gtrjjdqxqk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hnxiangtu.top/Article/details/gtnchanqar.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hongshengwenyu.top/Article/details/gtmwgvjlsl.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yueranfly.top/Article/details/gtulfqxcck.html

[O03] 加锁保护共享数据
来源：http://dali.gotoacloud.top/Article/details/gtkssbbdec.html

Py:   with lock: shared += 1
来源：http://dali.gogol.net.cn/Article/details/gtwzdgggzy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shanyushiyangtech.top/Article/details/gtoltjfrxt.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ivvv.top/Article/details/gtzfrwzxhw.html

TS:   // 同 JS
来源：http://dali.shzxlz.cn/Article/details/gtdkdrvpxm.html

Java: synchronized (this) { shared++; }
来源：http://dali.quarkkingdee.top/Article/details/gtddfjvgzq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jinghuilouyu.cn/Article/details/gthwdszgwf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yuanzhike.top/Article/details/gtrtcygxja.html

C#:   lock (gate) { shared++; }
来源：http://dali.snrcjt.cn/Article/details/gtevhfqjxk.html

[O04] 定义异步函数并等待
来源：http://dali.hongshengwenyu.top/Article/details/gtyrowkvvg.html

Py:   async def f():⏎    await g()
来源：http://dali.cheryme.top/Article/details/gttqswhdfp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.bjfxy.top/Article/details/gtwalwuzjm.html

JS:   async function f() { await g(); }
来源：http://dali.smart0.xyz/Article/details/gtuvfkbuks.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cdnleiting.top/Article/details/gtwrocuwlu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhiwuduotai.top/Article/details/gtwlvlxpkv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xziqi.cn/Article/details/gtbdexzgfj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhongyouzk.top/Article/details/gtwrjjfxcp.html

C#:   async Task F() { await G(); }
来源：http://dali.yongpay.top/Article/details/gtoevnftkp.html

[O05] 并发执行并等待全部完成
来源：http://dali.chenlongwang.top/Article/details/gtrbbthrro.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hfpthk.cn/Article/details/gtgxymdfks.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sysykeji.top/Article/details/gtptzpqann.html

JS:   await Promise.all(tasks)
来源：http://dali.cdnleiting.top/Article/details/gtmjsosmja.html

TS:   await Promise.all(tasks)
来源：http://dali.ivvv.top/Article/details/gtjffscatk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.c1oappe.top/Article/details/gtnjthbudb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.dashuyun.cn/Article/details/gtxqpplurx.html

Ruby: threads.map(&:join)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtexejlwai.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sufxvd.cn/Article/details/gtorokhtcr.html

[O06] 使用进程池
来源：http://dali.zhongyouzk.top/Article/details/gtozycdadr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.tian-w.cn/Article/details/gtfnbawppe.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shzxlz.cn/Article/details/gteemekxoa.html

JS:   // child_process / cluster 模块
来源：http://dali.sxryk.cn/Article/details/gtbcgjiatr.html

TS:   // child_process / cluster 模块
来源：http://dali.ydzc1.top/Article/details/gtxneagnvr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sxryk.cn/Article/details/gtgcrksddn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.9152youxi.cn/Article/details/gtpyqysiwh.html

Ruby: // fork 块
来源：http://dali.tian-w.cn/Article/details/gtlkhsxywu.html

C#:   Parallel.For
来源：http://dali.dianchejie.cn/Article/details/gtsxvfhksx.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtofhidiaq.html

P. 常用工具函数
来源：http://dali.nanxuanxn.top/Article/details/gtwojsiepc.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtkpymqtik.html

[P01] 生成 UUID
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzufqphtb.html

Py:   str(uuid.uuid4())
来源：http://dali.cheryme.top/Article/details/gtpkhsgftd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zycfv.cn/Article/details/gtjvnseuqh.html

JS:   crypto.randomUUID()
来源：http://dali.xuanzx.com/Article/details/gtctbnlkci.html

TS:   crypto.randomUUID()
来源：http://dali.wangshuangyany.cn/Article/details/gtiyhemcdo.html

Java: UUID.randomUUID().toString()
来源：http://dali.birdmap.top/Article/details/gtqeydsmht.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tanke756.top/Article/details/gtgsvcwedp.html

Ruby: SecureRandom.uuid
来源：http://dali.wangdashe.top/Article/details/gtnpfkgtyr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.guowangkeji.top/Article/details/gtzuxppbdp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinqigufen.top/Article/details/gtezuzguxe.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hammf.cn/Article/details/gtafsryvrx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yanxiufei.cn/Article/details/gtjqnzzqkt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hnqzz.top/Article/details/gtpcbwarga.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ppjwa.cn/Article/details/gtmzsakznt.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.meibo888.top/Article/details/gtxgiajjrl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.daxiang520.top/Article/details/gtmbbfojjj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhongyouzk.top/Article/details/gtnojmmtvd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shuidangran.top/Article/details/gtbccqqoth.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gtthyyjaps.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shuidangran.top/Article/details/gtdkbcgzag.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yj202588.top/Article/details/gtdujpgbvn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ivvv.top/Article/details/gtmfmlkesn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtinwaebet.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xuetiantiany.cn/Article/details/gteijekcvz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yvedp.cn/Article/details/gtgonjenri.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cqqwz.cn/Article/details/gtztoovxjy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.0kj1m.cn/Article/details/gtshuuciir.html

[P04] 求长度
来源：http://dali.nwbrower.top/Article/details/gtwoaulfoz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ybcxt.top/Article/details/gtstwkjflx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pycfn.com/Article/details/gtinhyrppz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shangyingyoupin.top/Article/details/gtydagrbsh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jianghu66.top/Article/details/gtjebvubwd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.birdmap.top/Article/details/gtvyzouwee.html

Go:   len(arr);  len(m)
来源：http://dali.jqgufenzy.top/Article/details/gttdqoxmty.html

Ruby: x.length;  x.size
来源：http://dali.sysykeji.top/Article/details/gtbwonnnnc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.iojbl.cn/Article/details/gttbiavkjk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.chenjidiqi.icu/Article/details/gtjphpauwc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.quarkkingdee.top/Article/details/gtknjpzioh.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinghuilouyu.cn/Article/details/gtulnupwig.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jlsjyb.cn/Article/details/gthrvxuokh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.feifeiyinyue.top/Article/details/gtmdffvfgh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xylfe.cn/Article/details/gtlbanzvbu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jianghu66.top/Article/details/gtgojljuwu.html

Ruby: a == b
来源：http://dali.snrcjt.cn/Article/details/gthlaexkmd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhongyouzk.top/Article/details/gtsuqdlyhe.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cqqwz.cn/Article/details/gtjfakivxw.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.0kj1m.cn/Article/details/gtlsajnhkr.html

PHP:  if (empty($x)) {}
来源：http://dali.quarkkingdee.top/Article/details/gtucditrcz.html


<!-- 参考信息 -->