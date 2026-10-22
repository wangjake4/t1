代发 wailian999

C#:   (int)resp.StatusCode
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dfzmhlub.html

[L08] 并发请求多个地址
来源：http://dali.pycfn.com/Article/details/gt2vhjqleov.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xziqi.cn/Article/details/gt2kguhsbvb.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhixingplan.top/Article/details/gt2alfkgptt.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nfeewmyq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gt2shyzkiug.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jiagoushi.top/Article/details/gt2vceqvtox.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.smart0.xyz/Article/details/gt2opozmzdd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.aibaodan.cn/Article/details/gt2stgdlhbc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yongpay.top/Article/details/gt2xmtkwoob.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2qntfmwfk.html

M. 命令行 / 进程 / 环境
来源：http://dali.yonumen.top/Article/details/gt2ibryeozp.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2fjmyxrxo.html

[M01] 读取命令行参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2gwxxwrtg.html

Py:   sys.argv[1:]
来源：http://dali.daxiang520.top/Article/details/gt2lbmrjhlp.html

PHP:  $argv;  $argc;
来源：http://dali.gogol.net.cn/Article/details/gt2jyumjvux.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lptzykmk.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bedlnhrv.html

Java: args 数组（main 方法参数）
来源：http://dali.aizwys.cn/Article/details/gt2zkmwuunb.html

Go:   os.Args[1:]
来源：http://dali.yanxiufei.cn/Article/details/gt2zfpepjsz.html

Ruby: ARGV
来源：http://dali.yj20258.top/Article/details/gt2pvjmzcdk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gomnhbqp.html

[M02] 读取环境变量
来源：http://dali.jinqigfzy.top/Article/details/gt2rebhqlap.html

Py:   os.environ.get("HOME")
来源：http://dali.yvedp.cn/Article/details/gt2rhpmlfld.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xinyue.icu/Article/details/gt2yasvncer.html

JS:   process.env.HOME
来源：http://dali.yongpay.top/Article/details/gt2cbfvznbl.html

TS:   process.env.HOME
来源：http://dali.xuanzx.com/Article/details/gt2giowamvr.html

Java: System.getenv("HOME")
来源：http://dali.daxiang520.top/Article/details/gt2anzdezay.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cucudq.cn/Article/details/gt2hnhwcrad.html

Ruby: ENV["HOME"]
来源：http://dali.quarkkingdee.top/Article/details/gt2hvndqdro.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenlongwang.top/Article/details/gt2edkmejnt.html

[M03] 执行外部命令
来源：http://dali.jianghu66.top/Article/details/gt2gmjcfkzk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinqigfzy.top/Article/details/gt2kbzwolpy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.dashuyun.cn/Article/details/gt2bonidban.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.iojbl.cn/Article/details/gt2uuazexwq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhiwuduotai.top/Article/details/gt2coyasxkq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hfpthk.cn/Article/details/gt2rdyjjjls.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2txltghyc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yanxiufei.cn/Article/details/gt2giubfmgl.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tanke756.top/Article/details/gt2yohxyugz.html

[M04] 获取当前工作目录
来源：http://dali.chenzaomai.com/Article/details/gt2biuuajxl.html

Py:   os.getcwd()
来源：http://dali.c1oappe.top/Article/details/gt2gdqhqbmg.html

PHP:  getcwd();
来源：http://dali.wangdashe.top/Article/details/gt2ymyaniei.html

JS:   process.cwd()
来源：http://dali.feifeiyinyue.top/Article/details/gt2wspelpvg.html

TS:   process.cwd()
来源：http://dali.ppjwa.cn/Article/details/gt2shhvnggr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.aizwys.cn/Article/details/gt2rnudfycu.html

Go:   os.Getwd()
来源：http://dali.dashuyun.cn/Article/details/gt2ynkydohh.html

Ruby: Dir.pwd
来源：http://dali.yuxming.cn/Article/details/gt2dkpnfpmu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gogol.net.cn/Article/details/gt2gutkkxgi.html

[M05] 设置退出码
来源：http://dali.c1oappe.top/Article/details/gt2fpswpprf.html

Py:   sys.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gt2tiawwupo.html

PHP:  exit(1);
来源：http://dali.yanxiufei.cn/Article/details/gt2xnbieqpl.html

JS:   process.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gt2lldzjcij.html

TS:   process.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gt2cofurtdo.html

Java: System.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2dsflxgao.html

Go:   os.Exit(1)
来源：http://dali.ydzc1.top/Article/details/gt2hqvemdqo.html

Ruby: exit 1
来源：http://dali.zdqjudy.top/Article/details/gt2ryaelcnl.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xuetiantiany.cn/Article/details/gt2odllzras.html

[M06] 向标准错误输出
来源：http://dali.birdmap.top/Article/details/gt2ozcnhrfb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.wangdashe.top/Article/details/gt2ardlytvo.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zycfv.cn/Article/details/gt2sgeigmse.html

JS:   console.error("err")
来源：http://dali.redwolf501.top/Article/details/gt2hnvckdht.html

TS:   console.error("err")
来源：http://dali.zycfv.cn/Article/details/gt2irmdleuv.html

Java: System.err.println("err")
来源：http://dali.c1oappe.top/Article/details/gt2qfwzakwd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cashguo.top/Article/details/gt2itrnczaa.html

Ruby: warn "err"
来源：http://dali.tianlin.xyz/Article/details/gt2dersfxkg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yangfankeji.com/Article/details/gt2elxkkntf.html

[M07] 判断是否为主入口
来源：http://dali.nanxuanxn.top/Article/details/gt2oadicvwv.html

Py:   if __name__ == "__main__":
来源：http://dali.yonumen.top/Article/details/gt2mouzewhc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sxryk.cn/Article/details/gt2tbzkjatw.html

JS:   require.main === module
来源：http://dali.316326.xyz/Article/details/gt2ggramboe.html

TS:   require.main === module
来源：http://dali.hnxiangtu.top/Article/details/gt2mdtacjag.html

Java: public static void main(String[] args)
来源：http://dali.hammf.cn/Article/details/gt2uzistqai.html

Go:   func main()
来源：http://dali.hnqzz.top/Article/details/gt2chrmhnnw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.9152youxi.cn/Article/details/gt2yfqsiigz.html

C#:   static void Main(string[] args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bcawbekc.html

[M08] 获取系统与运行时信息
来源：http://dali.dianchejie.cn/Article/details/gt2hsammrhp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xuetiantiany.cn/Article/details/gt2orkewcfh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gzhubu.top/Article/details/gt2nrqwsdiw.html

JS:   process.platform;  process.version
来源：http://dali.jqgfzy.top/Article/details/gt2kigksylh.html

TS:   process.platform;  process.version
来源：http://dali.ydzc1.top/Article/details/gt2exbbnvnv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nanxuanxn.top/Article/details/gt2mpjxglhs.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.nwbrower.top/Article/details/gt2ylxdatgu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.smart0.xyz/Article/details/gt2xsphmyzm.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xinyue.icu/Article/details/gt2ljesmrdt.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2bsaajymb.html

N. 数据结构与算法
来源：http://dali.tanke756.top/Article/details/gt2dbcsyivj.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2sbilocdi.html

[N01] 二分查找（有序数组）
来源：http://dali.gzhubu.top/Article/details/gt2wgpsylsv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nwbrower.top/Article/details/gt2zifzvviz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yvedp.cn/Article/details/gt2hltggcpt.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guowangkeji.top/Article/details/gt2mnearqia.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangdashe.top/Article/details/gt2zrlhnvtd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gt2dlpifdyn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2gcrncxyd.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cheryme.top/Article/details/gt2eqhmvinz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gt2lzurkvda.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ppjwa.cn/Article/details/gt2cdnzzkbe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhongyouzk.top/Article/details/gt2lsuwdlhi.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gt2dipoyygo.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigfzy.top/Article/details/gt2rdhfnhph.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daria6918.cn/Article/details/gt2ptcakbvc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.0kj1m.cn/Article/details/gt2wxzknvss.html

Go:   slices.Sort(arr)
来源：http://dali.ydzc1.top/Article/details/gt2hcyeqywf.html

Ruby: arr.sort
来源：http://dali.fengsongda.top/Article/details/gt2dzbppcuk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ivvv.top/Article/details/gt2dvjbrzbx.html

[N03] 快速排序（分治示例）
来源：http://dali.guannengcc.top/Article/details/gt2wtzkorob.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.daria6918.cn/Article/details/gt2lrhgiahi.html

PHP:  // 递归实现，或用 usort
来源：http://dali.guowangkeji.top/Article/details/gt2xyupfgrj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sufxvd.cn/Article/details/gt2ywdykwal.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daria6918.cn/Article/details/gt2iizxxwma.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.birdmap.top/Article/details/gt2wefgwjmx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.kuanghao11.cn/Article/details/gt2gmxzdawc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.guannengcc.top/Article/details/gt2mavrapcu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shuidangran.top/Article/details/gt2nnsqgyai.html

[N04] 斐波那契数列
来源：http://dali.nanxinkj.top/Article/details/gt2zdfuhuzg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yongpay.top/Article/details/gt2wzmdkmnt.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.dianchejie.cn/Article/details/gt2xigyvzzl.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ehwqpu.com/Article/details/gt2nlzvycyq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gt2elgffxar.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shuidangran.top/Article/details/gt2eaamefhd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.wangdashe.top/Article/details/gt2nugsnrff.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.guowangkeji.top/Article/details/gt2hkbewzbk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.gogol.net.cn/Article/details/gt2gzspdriz.html

[N05] 最大公约数
来源：http://dali.shangyingyoupin.top/Article/details/gt2ljfzghps.html

Py:   math.gcd(a, b)
来源：http://dali.jqgfzy.top/Article/details/gt2igslnrre.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rwvdaomt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2vtldkzkw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenzaomai.com/Article/details/gt2lpasptng.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.tianlin.xyz/Article/details/gt2znkuacoe.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hfpthk.cn/Article/details/gt2fhhmlmqj.html

Ruby: a.gcd(b)
来源：http://dali.chenzaomai.com/Article/details/gt2rzpjcioe.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hefciwet.html

[N06] 判断回文字符串
来源：http://dali.xuanzx.com/Article/details/gt2cszophuw.html

Py:   s == s[::-1]
来源：http://dali.yuanzhike.top/Article/details/gt2onhqlhob.html

PHP:  $s === strrev($s);
来源：http://dali.cdnleiting.top/Article/details/gt2tprddatg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gt2ljepjqxn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gt2fiqhcazk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cqqwz.cn/Article/details/gt2lckxediz.html

Go:   // 双指针从两端比较
来源：http://dali.jinqigufen.top/Article/details/gt2opitbuqi.html

Ruby: s == s.reverse
来源：http://dali.svipenyu.cn/Article/details/gt2vjefnded.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ehwqpu.com/Article/details/gt2jhbffyil.html

[N07] 两数之和（返回下标）
来源：http://dali.yuanzhike.top/Article/details/gt2uhvmgehh.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zycfv.cn/Article/details/gt2xkioudlg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ydzc1.top/Article/details/gt2izxpbttr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.chenlongwang.top/Article/details/gt2nnkzatcy.html

TS:   // 手写 Map<string, number>
来源：http://dali.sxryk.cn/Article/details/gt2ybznevtp.html

Java: // 手写 HashMap
来源：http://dali.hywenlv.cn/Article/details/gt2lbdhjukd.html

Go:   // 手写 map[int]int
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xltavtfe.html

Ruby: // 手写 Hash
来源：http://dali.tanke756.top/Article/details/gt2wmkljmen.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.vqdsnc.cn/Article/details/gt2pinjubok.html

[N08] 生成全排列
来源：http://dali.daxiang520.top/Article/details/gt2uobmguhx.html

Py:   itertools.permutations(arr)
来源：http://dali.yongpay.top/Article/details/gt2ddfhopck.html

PHP:  // 手写递归交换
来源：http://dali.dianchejie.cn/Article/details/gt2nveajjfe.html

JS:   // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gt2mhycelwi.html

TS:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gt2oielrekb.html

Java: // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gt2zggpzoms.html

Go:   // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gt2hyelyqhq.html

Ruby: arr.permutation.to_a
来源：http://dali.meibo888.top/Article/details/gt2sxdtcmif.html

C#:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gt2mzxbpiru.html

[N09] 栈与队列
来源：http://dali.ybcxt.top/Article/details/gt2jfhdyahf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gzhubu.top/Article/details/gt2hcvswwbl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.meibo888.top/Article/details/gt2gcaozfhe.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yvedp.cn/Article/details/gt2amdhfwvk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zdqjudy.top/Article/details/gt2oximmckh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.chenlongwang.top/Article/details/gt2pphovwld.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yj202588.top/Article/details/gt2brfapuuq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.chenlongwang.top/Article/details/gt2wtxxtosg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.snrcjt.cn/Article/details/gt2poeedqtu.html

[N10] 链表节点定义
来源：http://dali.hammf.cn/Article/details/gt2fwxufiwq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yonumen.top/Article/details/gt2ngvxnvsf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hammf.cn/Article/details/gt2kqiaurss.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhengqikj.top/Article/details/gt2fprhluuf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gzhubu.top/Article/details/gt2siaozsbc.html

Java: class Node { int v; Node next; }
来源：http://dali.yvedp.cn/Article/details/gt2jvacbumk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.feifeiyinyue.top/Article/details/gt2tpeuxfec.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hnxiangtu.top/Article/details/gt2uvalzhmv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.aibaodan.cn/Article/details/gt2yuzjocge.html

[N11] 二叉树中序遍历
来源：http://dali.jiagoushi.top/Article/details/gt2dkioieyp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sysykeji.top/Article/details/gt2yawfbfpl.html

PHP:  // 手写递归函数
来源：http://dali.hnqzz.top/Article/details/gt2raffvcre.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cqqwz.cn/Article/details/gt2nuccvngf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenjidiqi.icu/Article/details/gt2gxtcpikj.html

Java: // 手写递归
来源：http://dali.sweek.top/Article/details/gt2vocelrpt.html

Go:   // 手写递归
来源：http://dali.svipenyu.cn/Article/details/gt2jgjbgoun.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.bjfxy.top/Article/details/gt2aeemstki.html

C#:   // 手写递归
来源：http://dali.fengsongda.top/Article/details/gt2qbdosyoy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.nwbrower.top/Article/details/gt2xqwcmmhp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jlsjyb.cn/Article/details/gt2kprqokks.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hammf.cn/Article/details/gt2yhlbgjck.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gzhubu.top/Article/details/gt2hslcykfw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258.top/Article/details/gt2nlqrosdp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daxiang520.top/Article/details/gt2ijvfndfz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.gotoacloud.top/Article/details/gt2pdgotxet.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shzxlz.cn/Article/details/gt2lugsxjdc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yvedp.cn/Article/details/gt2katxaxhf.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2nqylhppa.html

O. 并发与异步
来源：http://dali.zdqjudy.top/Article/details/gt2ppkjcqir.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2klwcouym.html

[O01] 启动一个线程
来源：http://dali.havefunace.top/Article/details/gt2pthkmtsb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.redwolf501.top/Article/details/gt2ljscdywo.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.dashuyun.cn/Article/details/gt2bcgqalvo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.chenlongwang.top/Article/details/gt2jysesqgb.html

TS:   // 同 JS
来源：http://dali.sufxvd.cn/Article/details/gt2comkxtbt.html

Java: new Thread(() -> f()).start()
来源：http://dali.zycfv.cn/Article/details/gt2mqcvxojz.html

Go:   go f()
来源：http://dali.hammf.cn/Article/details/gt2keiuofuu.html

Ruby: Thread.new { f }
来源：http://dali.shangyingyoupin.top/Article/details/gt2pywqfltf.html

C#:   Task.Run(() => F());
来源：http://dali.shangyingyoupin.top/Article/details/gt2fyeeauyb.html

[O02] 使用线程池
来源：http://dali.aibaodan.cn/Article/details/gt2iriwvcre.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hfpthk.cn/Article/details/gt2ltxrrwpi.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.gzhubu.top/Article/details/gt2tbmwlpvz.html

JS:   // worker_threads 线程池
来源：http://dali.smart0.xyz/Article/details/gt2krpvmexr.html

TS:   // worker_threads 线程池
来源：http://dali.zhongyouzk.top/Article/details/gt2ftygrnqr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hnxiangtu.top/Article/details/gt2gqftphju.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yuanzhike.top/Article/details/gt2syalpmuw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ivvv.top/Article/details/gt2lghglyfo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jlsjyb.cn/Article/details/gt2fxajzciz.html

[O03] 加锁保护共享数据
来源：http://dali.hnxiangtu.top/Article/details/gt2vukzxmom.html

Py:   with lock: shared += 1
来源：http://dali.yongpay.top/Article/details/gt2kjsnpnfy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.birdmap.top/Article/details/gt2mdlvldsm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cdnleiting.top/Article/details/gt2sdvkgxup.html

TS:   // 同 JS
来源：http://dali.kuanghao11.cn/Article/details/gt2qtzmlnpk.html

Java: synchronized (this) { shared++; }
来源：http://dali.snrcjt.cn/Article/details/gt2pkpolqtq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.guannengcc.top/Article/details/gt2ymsihhjg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xziqi.cn/Article/details/gt2qvtdbaxo.html

C#:   lock (gate) { shared++; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2aeuudagc.html

[O04] 定义异步函数并等待
来源：http://dali.fzhhl.top/Article/details/gt2cfoigqze.html

Py:   async def f():⏎    await g()
来源：http://dali.hnqzz.top/Article/details/gt2qpkzjuse.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinqigufen.top/Article/details/gt2fphglocm.html

JS:   async function f() { await g(); }
来源：http://dali.yangfankeji.com/Article/details/gt2vnzqtjsn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cucudq.cn/Article/details/gt2tftbshcd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.birdmap.top/Article/details/gt2jzlwkfoa.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nanxinkj.top/Article/details/gt2hnqjotis.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.daria6918.cn/Article/details/gt2fcgnpqda.html

C#:   async Task F() { await G(); }
来源：http://dali.jianghu66.top/Article/details/gt2vmqmbpff.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhoulong.xyz/Article/details/gt2rzqezhmn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2evvuiipe.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gaohongyu789.top/Article/details/gt2iobwhuwa.html

JS:   await Promise.all(tasks)
来源：http://dali.yj20258888.top/Article/details/gt2ztksgszm.html

TS:   await Promise.all(tasks)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ynjrozdi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cashguo.top/Article/details/gt2wiwzahih.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhongyouzk.top/Article/details/gt2xizewtwk.html

Ruby: threads.map(&:join)
来源：http://dali.jqgufenzy.top/Article/details/gt2nelyaepp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.guowangkeji.top/Article/details/gt2gblxmlvc.html

[O06] 使用进程池
来源：http://dali.cheryme.top/Article/details/gt2avksjubo.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yonumen.top/Article/details/gt2dnrtepit.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hongshengwenyu.top/Article/details/gt2pzzdkglg.html

JS:   // child_process / cluster 模块
来源：http://dali.sweek.top/Article/details/gt2sqhrnwch.html

TS:   // child_process / cluster 模块
来源：http://dali.yuanzhike.top/Article/details/gt2fzgzapza.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xinyue.icu/Article/details/gt2itcakexk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.snrcjt.cn/Article/details/gt2ivagmixj.html

Ruby: // fork 块
来源：http://dali.meibo888.top/Article/details/gt2eqzakjda.html

C#:   Parallel.For
来源：http://dali.chenlongwang.top/Article/details/gt2bbpgmnxc.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2xxkdhpdd.html

P. 常用工具函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sfjkjdob.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2dmdqccad.html

[P01] 生成 UUID
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iauoeayj.html

Py:   str(uuid.uuid4())
来源：http://dali.yuxming.cn/Article/details/gt2mdexolxv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yueranfly.top/Article/details/gt2ivmtorhq.html

JS:   crypto.randomUUID()
来源：http://dali.svipenyu.cn/Article/details/gt2hwimjlxq.html

TS:   crypto.randomUUID()
来源：http://dali.mhx1999.top/Article/details/gt2ryvfvnie.html

Java: UUID.randomUUID().toString()
来源：http://dali.feifeiyinyue.top/Article/details/gt2unnsknet.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jqgfzy.top/Article/details/gt2jptoqwzp.html

Ruby: SecureRandom.uuid
来源：http://dali.fzhhl.top/Article/details/gt2vlygnmws.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jqgufenzy.top/Article/details/gt2lzziaerw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sysykeji.top/Article/details/gt2tsancirk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jianghu66.top/Article/details/gt2eeccizxd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.daria6918.cn/Article/details/gt2ryseylsj.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.fzhhl.top/Article/details/gt2abxsiubj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.fengsongda.top/Article/details/gt2wrwheres.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.316326.xyz/Article/details/gt2rphgrdgh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.sysykeji.top/Article/details/gt2ntxinxfq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.dianchejie.cn/Article/details/gt2yskmluaz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cucudq.cn/Article/details/gt2chwbibgu.html

[P03] 生成短随机字符串
来源：http://dali.guowangkeji.top/Article/details/gt2ytlnebap.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.mhx1999.top/Article/details/gt2qevillwh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.havefunace.top/Article/details/gt2hikhragd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.wangshuangyany.cn/Article/details/gt2vawbcceu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yuanzhike.top/Article/details/gt2yavbxevy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jqgfzy.top/Article/details/gt2wuodoham.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yvedp.cn/Article/details/gt2ukuqlahb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hfpthk.cn/Article/details/gt2jtghndgy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.cheryme.top/Article/details/gt2iqdvtwcf.html

[P04] 求长度
来源：http://dali.fzhhl.top/Article/details/gt2jffzdrdc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gotoacloud.top/Article/details/gt2igawzbjh.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hnqzz.top/Article/details/gt2qjsrdwnr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenjidiqi.icu/Article/details/gt2oqisporj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xuanzx.com/Article/details/gt2dtxoatjj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yongpay.top/Article/details/gt2ldcmccad.html

Go:   len(arr);  len(m)
来源：http://dali.xylfe.cn/Article/details/gt2bspcovnm.html

Ruby: x.length;  x.size
来源：http://dali.jyoumei.cn/Article/details/gt2fnqolqav.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hfpthk.cn/Article/details/gt2rwigzwta.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yongpay.top/Article/details/gt2jppbrpnk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yonumen.top/Article/details/gt2pfjxwsda.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shzxlz.cn/Article/details/gt2mjxmgkjv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cqqwz.cn/Article/details/gt2oviprikm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2froypfxa.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jinghuilouyu.cn/Article/details/gt2znuzaxnk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vndpdijb.html

Ruby: a == b
来源：http://dali.jqgufenzy.top/Article/details/gt2ijvbyqhi.html


<!-- 参考信息 -->