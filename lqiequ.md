代发 wailian999

C#:   (int)resp.StatusCode
来源：http://dali.birdmap.top/Article/details/gtrvozfbim.html

[L08] 并发请求多个地址
来源：http://dali.hnqzz.top/Article/details/gtzyiqjcdu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shanyushiyangtech.top/Article/details/gtbtdiyvyu.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhixingplan.top/Article/details/gtuilidrjo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gogol.net.cn/Article/details/gtzgdvoixq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gtwdlfgqiq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sweek.top/Article/details/gteobemmys.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shanyushiyangtech.top/Article/details/gtxsmemsgl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.nwbrower.top/Article/details/gtpiypxbpf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jlsjyb.cn/Article/details/gtprqfldwk.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtkkxcfdta.html

M. 命令行 / 进程 / 环境
来源：http://dali.shuidangran.top/Article/details/gtjozqgudy.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtjlzkgqjk.html

[M01] 读取命令行参数
来源：http://dali.zhengqikj.top/Article/details/gtafmyxffu.html

Py:   sys.argv[1:]
来源：http://dali.nwbrower.top/Article/details/gtwgslfcka.html

PHP:  $argv;  $argc;
来源：http://dali.hongshengwenyu.top/Article/details/gtocqksymf.html

JS:   process.argv.slice(2)
来源：http://dali.jinqigfzy.top/Article/details/gtdokfdwbs.html

TS:   process.argv.slice(2)
来源：http://dali.nwbrower.top/Article/details/gtidnrtzit.html

Java: args 数组（main 方法参数）
来源：http://dali.yongpay.top/Article/details/gtccelktmr.html

Go:   os.Args[1:]
来源：http://dali.wangdashe.top/Article/details/gtwuxywafe.html

Ruby: ARGV
来源：http://dali.yuanzhike.top/Article/details/gtiusgezvu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cucudq.cn/Article/details/gttovsdysf.html

[M02] 读取环境变量
来源：http://dali.tanke756.top/Article/details/gtuvgxczhi.html

Py:   os.environ.get("HOME")
来源：http://dali.aibaodan.cn/Article/details/gtdlywausa.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgmixyfno.html

JS:   process.env.HOME
来源：http://dali.chenjidiqi.icu/Article/details/gtmklotojk.html

TS:   process.env.HOME
来源：http://dali.nwbrower.top/Article/details/gthoznreax.html

Java: System.getenv("HOME")
来源：http://dali.iojbl.cn/Article/details/gtpalqugpb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.wangdashe.top/Article/details/gtrxkalgqh.html

Ruby: ENV["HOME"]
来源：http://dali.hnxiangtu.top/Article/details/gthiphkojd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.bjfxy.top/Article/details/gtgciadmxo.html

[M03] 执行外部命令
来源：http://dali.gotoacloud.top/Article/details/gttyvjcgpq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.andypj.xyz/Article/details/gtuixbbgff.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cdnleiting.top/Article/details/gtofavzyio.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.quarkkingdee.top/Article/details/gtvknhguzw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjogdcvyi.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cucudq.cn/Article/details/gtqjxmccka.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.wangdashe.top/Article/details/gthlgbgrqx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.andypj.xyz/Article/details/gtlamyekjy.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhiwuduotai.top/Article/details/gtoictbffc.html

[M04] 获取当前工作目录
来源：http://dali.yuxming.cn/Article/details/gttgosbseu.html

Py:   os.getcwd()
来源：http://dali.tianlin.xyz/Article/details/gtbztvmeut.html

PHP:  getcwd();
来源：http://dali.hammf.cn/Article/details/gtpnrzbmnl.html

JS:   process.cwd()
来源：http://dali.ivvv.top/Article/details/gtbmfcfqoa.html

TS:   process.cwd()
来源：http://dali.hysaishi.cn/Article/details/gtwzpyxlhy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.birdmap.top/Article/details/gtrdejjbto.html

Go:   os.Getwd()
来源：http://dali.havefunace.top/Article/details/gtjaafkinz.html

Ruby: Dir.pwd
来源：http://dali.smart0.xyz/Article/details/gtfmehndzi.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.haohaochexian.top/Article/details/gtsfsljbgf.html

[M05] 设置退出码
来源：http://dali.hywenlv.cn/Article/details/gtdugtewas.html

Py:   sys.exit(1)
来源：http://dali.aizwys.cn/Article/details/gtutdqxdrf.html

PHP:  exit(1);
来源：http://dali.bjfxy.top/Article/details/gtwpbynixi.html

JS:   process.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gtpaqfudct.html

TS:   process.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtqlyfchxg.html

Java: System.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtxojaerpe.html

Go:   os.Exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtswdsylin.html

Ruby: exit 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtfyckbxrl.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.smart0.xyz/Article/details/gtouzqcwwf.html

[M06] 向标准错误输出
来源：http://dali.daxiang520.top/Article/details/gttcyvyypn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxvnejnmf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinqigfzy.top/Article/details/gtsyovviio.html

JS:   console.error("err")
来源：http://dali.birdmap.top/Article/details/gtokjgzfgo.html

TS:   console.error("err")
来源：http://dali.aizwys.cn/Article/details/gtmjcqqeoa.html

Java: System.err.println("err")
来源：http://dali.zdqjudy.top/Article/details/gtqpvqszto.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xinyue.icu/Article/details/gthdeswxyf.html

Ruby: warn "err"
来源：http://dali.tianlin.xyz/Article/details/gtdbwpbjmi.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hfpthk.cn/Article/details/gteljxkphm.html

[M07] 判断是否为主入口
来源：http://dali.bjfxy.top/Article/details/gtvgsqguyx.html

Py:   if __name__ == "__main__":
来源：http://dali.xuetiantiany.cn/Article/details/gtewprcdhz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yuxming.cn/Article/details/gtavxwkrsh.html

JS:   require.main === module
来源：http://dali.zdqjudy.top/Article/details/gtfbagezka.html

TS:   require.main === module
来源：http://dali.nanxinkj.top/Article/details/gtxemrlumz.html

Java: public static void main(String[] args)
来源：http://dali.havefunace.top/Article/details/gtjvltnmvl.html

Go:   func main()
来源：http://dali.yj20258888.top/Article/details/gtcyfunppj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xuanzx.com/Article/details/gtpbtueisu.html

C#:   static void Main(string[] args)
来源：http://dali.hammf.cn/Article/details/gtkeqcyjox.html

[M08] 获取系统与运行时信息
来源：http://dali.hfpthk.cn/Article/details/gtsfyaainf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.tanke756.top/Article/details/gtcuojntdd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.fzhhl.top/Article/details/gtcggsyplq.html

JS:   process.platform;  process.version
来源：http://dali.wangdashe.top/Article/details/gtuzpogwlw.html

TS:   process.platform;  process.version
来源：http://dali.wangdashe.top/Article/details/gtqvyukgcy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnqzz.top/Article/details/gtdddrqnxh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jyoumei.cn/Article/details/gtbuublybe.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xuetiantiany.cn/Article/details/gtrumjgcsx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyplvijtv.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcpfsrpaz.html

N. 数据结构与算法
来源：http://dali.yongpay.top/Article/details/gtkhjfwcbh.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtwwoofxau.html

[N01] 二分查找（有序数组）
来源：http://dali.zycfv.cn/Article/details/gtjlvjgbwc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtowdbfvqy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sysykeji.top/Article/details/gtqivyzxjx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xinyue.icu/Article/details/gtrkjwuhsa.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gotoacloud.top/Article/details/gtdqjmigwi.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtopmjgjiw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yongpay.top/Article/details/gtzxppkbad.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.9152youxi.cn/Article/details/gtafqafijb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtjqvndwkx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.bjfxy.top/Article/details/gtbcjajpvt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhengqikj.top/Article/details/gtcvdpsqfz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.fengsongda.top/Article/details/gtorqoamsp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ivvv.top/Article/details/gtobucmcvb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gzhubu.top/Article/details/gtiygdzmbn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.chenlongwang.top/Article/details/gtbnopedxa.html

Go:   slices.Sort(arr)
来源：http://dali.fzhhl.top/Article/details/gtpdditntg.html

Ruby: arr.sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gttlcfenwl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.dianchejie.cn/Article/details/gtczzmahlk.html

[N03] 快速排序（分治示例）
来源：http://dali.zhongyouzk.top/Article/details/gtdjeqsfpy.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhongyouzk.top/Article/details/gtvkubeayy.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ybcxt.top/Article/details/gttwbgnkmv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ppjwa.cn/Article/details/gtxfvmltdd.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ydzc1.top/Article/details/gtkpvakwrl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrskqutgs.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinqigfzy.top/Article/details/gtahdvagyd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.mhx1999.top/Article/details/gtgsielwhd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xziqi.cn/Article/details/gtbillqrkk.html

[N04] 斐波那契数列
来源：http://dali.jinghuilouyu.cn/Article/details/gtxmrbbbuo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hfpthk.cn/Article/details/gtnqgdnieo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhongyouzk.top/Article/details/gthlwmtsod.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ppjwa.cn/Article/details/gtvssowtls.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gtvpbarife.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.316326.xyz/Article/details/gtjalazdhs.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtobqyhpft.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sufxvd.cn/Article/details/gtxnitcjck.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.redwolf501.top/Article/details/gtgnatgoxn.html

[N05] 最大公约数
来源：http://dali.daria6918.cn/Article/details/gtrenkmowu.html

Py:   math.gcd(a, b)
来源：http://dali.aizwys.cn/Article/details/gtisysujrv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hongshengwenyu.top/Article/details/gttdboitch.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.andypj.xyz/Article/details/gtidmcliks.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.316326.xyz/Article/details/gtryyhezst.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.kuanghao11.cn/Article/details/gtrwtjhfur.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.tianlin.xyz/Article/details/gtknpunhej.html

Ruby: a.gcd(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiwdzaxsr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.wangshuangyany.cn/Article/details/gteodbmqwn.html

[N06] 判断回文字符串
来源：http://dali.jianghu66.top/Article/details/gtovstylwl.html

Py:   s == s[::-1]
来源：http://dali.ybcxt.top/Article/details/gtjnyhhpld.html

PHP:  $s === strrev($s);
来源：http://dali.bjfxy.top/Article/details/gtlyyxndek.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gtcovcmmzy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gtybwtytnh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.iojbl.cn/Article/details/gttpjayfxz.html

Go:   // 双指针从两端比较
来源：http://dali.hnxiangtu.top/Article/details/gtzmyhmsfs.html

Ruby: s == s.reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gtckgydxbw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.svipenyu.cn/Article/details/gtsxtutxka.html

[N07] 两数之和（返回下标）
来源：http://dali.316326.xyz/Article/details/gtjrulygsi.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinqigfzy.top/Article/details/gtlkduxwbg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ydzc1.top/Article/details/gtrnigyjom.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhiwuduotai.top/Article/details/gtxsvqteti.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhoulong.xyz/Article/details/gtawfqhemp.html

Java: // 手写 HashMap
来源：http://dali.xinyue.icu/Article/details/gtsdcczajq.html

Go:   // 手写 map[int]int
来源：http://dali.tianlin.xyz/Article/details/gtuumozwgg.html

Ruby: // 手写 Hash
来源：http://dali.yuxming.cn/Article/details/gtshdmsgvb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xylfe.cn/Article/details/gtepvqaitb.html

[N08] 生成全排列
来源：http://dali.guannengcc.top/Article/details/gtvsvnfyms.html

Py:   itertools.permutations(arr)
来源：http://dali.jinqigufen.top/Article/details/gtnxmkatzw.html

PHP:  // 手写递归交换
来源：http://dali.gzhubu.top/Article/details/gtmebrdefr.html

JS:   // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtikbnjebb.html

TS:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gtstijvmht.html

Java: // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtzvvzymgg.html

Go:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gtezfarijf.html

Ruby: arr.permutation.to_a
来源：http://dali.316326.xyz/Article/details/gthumhrfhk.html

C#:   // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gteyfndicv.html

[N09] 栈与队列
来源：http://dali.bjfxy.top/Article/details/gtgoqlozqk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinqigufen.top/Article/details/gtpjvgfkkx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gtgwgomgvh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtmvovpkxn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.aibaodan.cn/Article/details/gtpyjijngf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cheryme.top/Article/details/gthhuljdaf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ydzc1.top/Article/details/gtxwawmdkt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gaohongyu789.top/Article/details/gtafyfiobn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.0kj1m.cn/Article/details/gtjqbsuvco.html

[N10] 链表节点定义
来源：http://dali.bjfxy.top/Article/details/gteuhvhwfk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtucuesufa.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.aizwys.cn/Article/details/gtovwjxtra.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xylfe.cn/Article/details/gtppoxofej.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ybcxt.top/Article/details/gtfmivdivb.html

Java: class Node { int v; Node next; }
来源：http://dali.hammf.cn/Article/details/gtsnncvwhb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.wangdashe.top/Article/details/gtzxwtroyy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jqgfzy.top/Article/details/gtlvhitlrh.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlzunwxrb.html

[N11] 二叉树中序遍历
来源：http://dali.dashuyun.cn/Article/details/gtduiarbat.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cdnleiting.top/Article/details/gtojvzadjh.html

PHP:  // 手写递归函数
来源：http://dali.xziqi.cn/Article/details/gtvcgmylny.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.snrcjt.cn/Article/details/gtcqzxslsm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guannengcc.top/Article/details/gtsjwvajez.html

Java: // 手写递归
来源：http://dali.jinqigufen.top/Article/details/gtvtsxfnhv.html

Go:   // 手写递归
来源：http://dali.yuanzhike.top/Article/details/gtsnyfuwxg.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gogol.net.cn/Article/details/gtqwfchvvh.html

C#:   // 手写递归
来源：http://dali.guannengcc.top/Article/details/gtjesyxzhd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cucudq.cn/Article/details/gttgrhtmec.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ivvv.top/Article/details/gtdyjgwlni.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gaohongyu789.top/Article/details/gteubbastq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yanxiufei.cn/Article/details/gtobdxhbqu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.pengpengdd.cyou/Article/details/gtgcepkntw.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsewfzycc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.fengsongda.top/Article/details/gtxsqfpodq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.havefunace.top/Article/details/gtnuvasbqh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigfzy.top/Article/details/gtpcbrlxly.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtllsecssm.html

O. 并发与异步
来源：http://dali.andypj.xyz/Article/details/gtaxyujcga.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtlwfzxtvd.html

[O01] 启动一个线程
来源：http://dali.vqdsnc.cn/Article/details/gtqpwcaduh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.daxiang520.top/Article/details/gtncorrtly.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.chenjidiqi.icu/Article/details/gtljecpezt.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.haohaochexian.top/Article/details/gtktbmytnu.html

TS:   // 同 JS
来源：http://dali.aibaodan.cn/Article/details/gtownotxxq.html

Java: new Thread(() -> f()).start()
来源：http://dali.ybcxt.top/Article/details/gtzdyxqblh.html

Go:   go f()
来源：http://dali.pengpengdd.cyou/Article/details/gtujsqvned.html

Ruby: Thread.new { f }
来源：http://dali.dianchejie.cn/Article/details/gtpdoeadam.html

C#:   Task.Run(() => F());
来源：http://dali.sufxvd.cn/Article/details/gtippmzjbe.html

[O02] 使用线程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gthglhhvte.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.vqdsnc.cn/Article/details/gtazsuciqk.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.pycfn.com/Article/details/gtxdxnimhn.html

JS:   // worker_threads 线程池
来源：http://dali.ppjwa.cn/Article/details/gtbidvldlb.html

TS:   // worker_threads 线程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtglifnbhi.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yj202588.top/Article/details/gtoinpboxs.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.guannengcc.top/Article/details/gtfatayrum.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjaidzqhs.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hysaishi.cn/Article/details/gtiywhgnto.html

[O03] 加锁保护共享数据
来源：http://dali.ivvv.top/Article/details/gtnnjdesdp.html

Py:   with lock: shared += 1
来源：http://dali.jiagoushi.top/Article/details/gtmikkchsz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.0kj1m.cn/Article/details/gtohahuatc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.haohaochexian.top/Article/details/gthwzkmpte.html

TS:   // 同 JS
来源：http://dali.xylfe.cn/Article/details/gtrtknfumw.html

Java: synchronized (this) { shared++; }
来源：http://dali.redwolf501.top/Article/details/gterojzrii.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhiwuduotai.top/Article/details/gtjkdtxije.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yvedp.cn/Article/details/gtsflqmxcn.html

C#:   lock (gate) { shared++; }
来源：http://dali.shzxlz.cn/Article/details/gtvtecopqe.html

[O04] 定义异步函数并等待
来源：http://dali.shanyushiyangtech.top/Article/details/gtomrwgpsq.html

Py:   async def f():⏎    await g()
来源：http://dali.quarkkingdee.top/Article/details/gtzlxehjon.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.daxiang520.top/Article/details/gtlerkwtqn.html

JS:   async function f() { await g(); }
来源：http://dali.hysaishi.cn/Article/details/gtpmnzgghs.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ppjwa.cn/Article/details/gtzctljcgx.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shuidangran.top/Article/details/gtnbbqlbnz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yonumen.top/Article/details/gtktbnqtvt.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yueranfly.top/Article/details/gtxxsgqoue.html

C#:   async Task F() { await G(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtkujcuxxz.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinyuanbaomall.cn/Article/details/gtelgoclhp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hongshengwenyu.top/Article/details/gtkfgebgqs.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gtgqrxyjtj.html

JS:   await Promise.all(tasks)
来源：http://dali.ybcxt.top/Article/details/gtxnpnaxsj.html

TS:   await Promise.all(tasks)
来源：http://dali.fengsongda.top/Article/details/gtvomryyip.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.redwolf501.top/Article/details/gtgrhtztfs.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.andypj.xyz/Article/details/gtzkqykall.html

Ruby: threads.map(&:join)
来源：http://dali.zycfv.cn/Article/details/gtrbxvdmar.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.chenzaomai.com/Article/details/gtkgooybqb.html

[O06] 使用进程池
来源：http://dali.sufxvd.cn/Article/details/gtoxsaufmz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ywan-chungtsiang.top/Article/details/gttdgsszrr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ivvv.top/Article/details/gtsqigrzof.html

JS:   // child_process / cluster 模块
来源：http://dali.ybcxt.top/Article/details/gtvuhgmfon.html

TS:   // child_process / cluster 模块
来源：http://dali.ybcxt.top/Article/details/gtprqwzgtf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gaohongyu789.top/Article/details/gthgxsylbz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.daria6918.cn/Article/details/gtdkraeitr.html

Ruby: // fork 块
来源：http://dali.feifeiyinyue.top/Article/details/gtkakwnljy.html

C#:   Parallel.For
来源：http://dali.dianchejie.cn/Article/details/gtpaktnozs.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtrbpjagsa.html

P. 常用工具函数
来源：http://dali.xuetiantiany.cn/Article/details/gtwkdgqiok.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtafawixgu.html

[P01] 生成 UUID
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthlvffifj.html

Py:   str(uuid.uuid4())
来源：http://dali.c1oappe.top/Article/details/gtrrikdxpx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhiwuduotai.top/Article/details/gtribdfqws.html

JS:   crypto.randomUUID()
来源：http://dali.sysykeji.top/Article/details/gtpayibers.html

TS:   crypto.randomUUID()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfnldmhxy.html

Java: UUID.randomUUID().toString()
来源：http://dali.yanxiufei.cn/Article/details/gtaomppzpv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jyoumei.cn/Article/details/gtynsdxswx.html

Ruby: SecureRandom.uuid
来源：http://dali.hammf.cn/Article/details/gtddynniwq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xylfe.cn/Article/details/gteicwjdkc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yangfankeji.com/Article/details/gtwpsejlrr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shangyingyoupin.top/Article/details/gtalfibjdx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.9152youxi.cn/Article/details/gttrgkxdrj.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shzxlz.cn/Article/details/gtcvxikfgt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.guannengcc.top/Article/details/gtxssvepqz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.aibaodan.cn/Article/details/gtddjqtzgc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiqaffsnl.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinqigufen.top/Article/details/gtwapsfdtw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.9152youxi.cn/Article/details/gtyxelifuo.html

[P03] 生成短随机字符串
来源：http://dali.zhongyouzk.top/Article/details/gtcgssglhl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gtadtjvzrg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xylfe.cn/Article/details/gtyqxlbfdc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuanzx.com/Article/details/gtucgszyzh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuanzx.com/Article/details/gtqhzjrtnk.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jyoumei.cn/Article/details/gtkerdpulo.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.316326.xyz/Article/details/gtyxrnezov.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yueranfly.top/Article/details/gtjnvbshqf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.fengsongda.top/Article/details/gtqqdxrpbs.html

[P04] 求长度
来源：http://dali.pengpengdd.cyou/Article/details/gthvdafsui.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yj20258888.top/Article/details/gtstulwtse.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gtnvzrypqb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiffphofl.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tian-w.cn/Article/details/gthodcorru.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yonumen.top/Article/details/gtlbrkpmfv.html

Go:   len(arr);  len(m)
来源：http://dali.gotoacloud.top/Article/details/gtgwdbzyfh.html

Ruby: x.length;  x.size
来源：http://dali.zhongyouzk.top/Article/details/gtvdwogjka.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.meibo888.top/Article/details/gtiwdtbgis.html

[P05] 判断两个对象内容是否相等
来源：http://dali.pycfn.com/Article/details/gtesquoglg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.0kj1m.cn/Article/details/gtxcvogglg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhaomingkeji.xyz/Article/details/gtllzzsbrn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.chenzaomai.com/Article/details/gtpsxufnjv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.guannengcc.top/Article/details/gtycjqauqh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xuetiantiany.cn/Article/details/gtfkahgkwy.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.dashuyun.cn/Article/details/gtljcrfxwg.html

Ruby: a == b
来源：http://dali.jinqigfzy.top/Article/details/gtsdrcytpn.html


<!-- 参考信息 -->