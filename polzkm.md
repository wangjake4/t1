代发 wailian999

TS:   resp.ok;  resp.status
来源：http://dali.yvedp.cn/Article/details/gtokwzmysn.html

Java: resp.statusCode()
来源：http://dali.jiagoushi.top/Article/details/gtjqcrulsv.html

Go:   resp.StatusCode
来源：http://dali.daxiang520.top/Article/details/gtgszuosbg.html

Ruby: resp.code.to_i
来源：http://dali.xylfe.cn/Article/details/gtjtggwfwd.html

C#:   (int)resp.StatusCode
来源：http://dali.gaohongyu789.top/Article/details/gtjqeqtssg.html

[L08] 并发请求多个地址
来源：http://dali.ybcxt.top/Article/details/gtdqvhyjok.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkcifmrsi.html

PHP:  curl_multi_init() 系列
来源：http://dali.havefunace.top/Article/details/gtqogkrikd.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sweek.top/Article/details/gtgbyncwvc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yanxiufei.cn/Article/details/gtjydjdcqu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfeqzhfzb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.redwolf501.top/Article/details/gtiqwaxgie.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.tian-w.cn/Article/details/gtotrajclu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.daxiang520.top/Article/details/gthfvdpdus.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtjgibqwri.html

M. 命令行 / 进程 / 环境
来源：http://dali.sysykeji.top/Article/details/gtqdbacvmu.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtplnwzvku.html

[M01] 读取命令行参数
来源：http://dali.jinqigufen.top/Article/details/gttcoewevf.html

Py:   sys.argv[1:]
来源：http://dali.hnqzz.top/Article/details/gtpnamgjsz.html

PHP:  $argv;  $argc;
来源：http://dali.chenlongwang.top/Article/details/gtrtqehxch.html

JS:   process.argv.slice(2)
来源：http://dali.shangyingyoupin.top/Article/details/gtlamnymsf.html

TS:   process.argv.slice(2)
来源：http://dali.tian-w.cn/Article/details/gtpvdfhxpv.html

Java: args 数组（main 方法参数）
来源：http://dali.0kj1m.cn/Article/details/gtkntfyryh.html

Go:   os.Args[1:]
来源：http://dali.hysaishi.cn/Article/details/gtsjifdcpz.html

Ruby: ARGV
来源：http://dali.ppjwa.cn/Article/details/gtdiykbypd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.9152youxi.cn/Article/details/gtscelbdyc.html

[M02] 读取环境变量
来源：http://dali.chenjidiqi.icu/Article/details/gtqajfppym.html

Py:   os.environ.get("HOME")
来源：http://dali.ydzc1.top/Article/details/gtxdqelquc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xylfe.cn/Article/details/gthpsyfrzi.html

JS:   process.env.HOME
来源：http://dali.hfpthk.cn/Article/details/gttiymxkol.html

TS:   process.env.HOME
来源：http://dali.cashguo.top/Article/details/gtmziuiakf.html

Java: System.getenv("HOME")
来源：http://dali.svipenyu.cn/Article/details/gtudrdfugp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ydzc1.top/Article/details/gtxtltkafz.html

Ruby: ENV["HOME"]
来源：http://dali.yj20258888.top/Article/details/gtrkzkmfrn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yvedp.cn/Article/details/gtuazegwuo.html

[M03] 执行外部命令
来源：http://dali.shangyingyoupin.top/Article/details/gtdcrwilsl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.quarkkingdee.top/Article/details/gtueohorqb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hfpthk.cn/Article/details/gttbfnhuto.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenzaomai.com/Article/details/gtyunbzjip.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgfzy.top/Article/details/gtdvwpdmly.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gotoacloud.top/Article/details/gtifnvenbx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhoulong.xyz/Article/details/gtgxiaurkb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hammf.cn/Article/details/gtvslojxqa.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jiagoushi.top/Article/details/gtnaibqiax.html

[M04] 获取当前工作目录
来源：http://dali.aizwys.cn/Article/details/gtndhfgysb.html

Py:   os.getcwd()
来源：http://dali.yanxiufei.cn/Article/details/gtyrnfyhvo.html

PHP:  getcwd();
来源：http://dali.gogol.net.cn/Article/details/gtrcmmmxbt.html

JS:   process.cwd()
来源：http://dali.yvedp.cn/Article/details/gtfwwdhghq.html

TS:   process.cwd()
来源：http://dali.jqgfzy.top/Article/details/gtgmtkqejh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.guowangkeji.top/Article/details/gtjnicybay.html

Go:   os.Getwd()
来源：http://dali.daria6918.cn/Article/details/gtariojxcs.html

Ruby: Dir.pwd
来源：http://dali.vqdsnc.cn/Article/details/gthslxkeju.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.c1oappe.top/Article/details/gtazoyjaqn.html

[M05] 设置退出码
来源：http://dali.shuidangran.top/Article/details/gtvyzgkwhj.html

Py:   sys.exit(1)
来源：http://dali.xziqi.cn/Article/details/gtxybysifk.html

PHP:  exit(1);
来源：http://dali.xylfe.cn/Article/details/gtsxjkisos.html

JS:   process.exit(1)
来源：http://dali.fzhhl.top/Article/details/gtlxjflnfv.html

TS:   process.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gtqaqvnjgr.html

Java: System.exit(1)
来源：http://dali.sxryk.cn/Article/details/gtxrdjqvty.html

Go:   os.Exit(1)
来源：http://dali.dianchejie.cn/Article/details/gtckxxighz.html

Ruby: exit 1
来源：http://dali.bjfxy.top/Article/details/gtvzlpyely.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.iojbl.cn/Article/details/gtdezeqjig.html

[M06] 向标准错误输出
来源：http://dali.yuanzhike.top/Article/details/gtrgzadfop.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhoulong.xyz/Article/details/gtywxcxjdz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nanxinkj.top/Article/details/gtphdpwtlm.html

JS:   console.error("err")
来源：http://dali.yangfankeji.com/Article/details/gtxmrsolld.html

TS:   console.error("err")
来源：http://dali.dashuyun.cn/Article/details/gtlvaztacw.html

Java: System.err.println("err")
来源：http://dali.yvedp.cn/Article/details/gthzgvxxqj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnypeonyf.html

Ruby: warn "err"
来源：http://dali.hongshengwenyu.top/Article/details/gtdoktppsf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yuanzhike.top/Article/details/gtmgxikfin.html

[M07] 判断是否为主入口
来源：http://dali.hnqzz.top/Article/details/gtgekkesnm.html

Py:   if __name__ == "__main__":
来源：http://dali.smart0.xyz/Article/details/gtwpmiaitq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sysykeji.top/Article/details/gtevbegsqs.html

JS:   require.main === module
来源：http://dali.jlsjyb.cn/Article/details/gtdmaebikm.html

TS:   require.main === module
来源：http://dali.guannengcc.top/Article/details/gtnphsgriq.html

Java: public static void main(String[] args)
来源：http://dali.cheryme.top/Article/details/gtcyjihqat.html

Go:   func main()
来源：http://dali.yuxming.cn/Article/details/gtbrlxnxhp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xinyue.icu/Article/details/gtnndhopzk.html

C#:   static void Main(string[] args)
来源：http://dali.c1oappe.top/Article/details/gtazqqffia.html

[M08] 获取系统与运行时信息
来源：http://dali.hfpthk.cn/Article/details/gtwnftlfao.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cdnleiting.top/Article/details/gtlsizvanq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.birdmap.top/Article/details/gtefpkdhkd.html

JS:   process.platform;  process.version
来源：http://dali.iojbl.cn/Article/details/gtahhqilrh.html

TS:   process.platform;  process.version
来源：http://dali.hnqzz.top/Article/details/gtjqcuspnm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.meibo888.top/Article/details/gtodmndjvk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.tanke756.top/Article/details/gtrxzpwqxh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.9152youxi.cn/Article/details/gtwwegkihz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tanke756.top/Article/details/gtxzdhixip.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtiaznswpn.html

N. 数据结构与算法
来源：http://dali.shangyingyoupin.top/Article/details/gtrbnpmxkb.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtzqelnoko.html

[N01] 二分查找（有序数组）
来源：http://dali.dianchejie.cn/Article/details/gtjbmgxxea.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtfmnotwzv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.svipenyu.cn/Article/details/gttxctinsv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gtnuwqpdex.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shzxlz.cn/Article/details/gtobwcrfka.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtunrmpbpf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtlcugjygf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xuanzx.com/Article/details/gtdjrzzmap.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtuiutotcm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nwbrower.top/Article/details/gtbypimffd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ybcxt.top/Article/details/gthoyyahfz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.9152youxi.cn/Article/details/gtnqsucblk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuanzhike.top/Article/details/gtleuischt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ybcxt.top/Article/details/gttnwzjpby.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzhyyerzo.html

Go:   slices.Sort(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtukgzirur.html

Ruby: arr.sort
来源：http://dali.haohaochexian.top/Article/details/gtqppamqnl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.svipenyu.cn/Article/details/gtzccqglcd.html

[N03] 快速排序（分治示例）
来源：http://dali.sysykeji.top/Article/details/gtcbrgwvjk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj202588.top/Article/details/gtfendgshe.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shzxlz.cn/Article/details/gtchgtyyjr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj202588.top/Article/details/gtboqzsxwb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gotoacloud.top/Article/details/gtfprwqori.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.svipenyu.cn/Article/details/gtrqwvcksf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jianghu66.top/Article/details/gteszpvxab.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.iojbl.cn/Article/details/gtdtxfyhxz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.wangdashe.top/Article/details/gttfprulyy.html

[N04] 斐波那契数列
来源：http://dali.iojbl.cn/Article/details/gtitbzxlzt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cdnleiting.top/Article/details/gtjifgfcdu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.haohaochexian.top/Article/details/gtohmqabuy.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj20258888.top/Article/details/gtknstadja.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtnbvsiilt.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.pycfn.com/Article/details/gtpcdrvmvl.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cdnleiting.top/Article/details/gtrlwtlhpi.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cheryme.top/Article/details/gtdzdgsxbr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj20258888.top/Article/details/gtvrbszwdy.html

[N05] 最大公约数
来源：http://dali.wangshuangyany.cn/Article/details/gtosnyhyza.html

Py:   math.gcd(a, b)
来源：http://dali.gogol.net.cn/Article/details/gtbgavyvts.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinqigfzy.top/Article/details/gtmshuigfb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.vqdsnc.cn/Article/details/gtwwvrgpkj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj202588.top/Article/details/gtjhkdnzrm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xinyue.icu/Article/details/gtgbizducd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.0kj1m.cn/Article/details/gtfwlwtbzn.html

Ruby: a.gcd(b)
来源：http://dali.sweek.top/Article/details/gtetkwglyn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gotoacloud.top/Article/details/gttpnnivxk.html

[N06] 判断回文字符串
来源：http://dali.cheryme.top/Article/details/gtewsehkmm.html

Py:   s == s[::-1]
来源：http://dali.pycfn.com/Article/details/gtyhqsuypg.html

PHP:  $s === strrev($s);
来源：http://dali.zycfv.cn/Article/details/gteouxehwz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.vqdsnc.cn/Article/details/gtiywbajmg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gtslpllnvk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmnlnclea.html

Go:   // 双指针从两端比较
来源：http://dali.guannengcc.top/Article/details/gtfhqqxdav.html

Ruby: s == s.reverse
来源：http://dali.mhx1999.top/Article/details/gtxpzpapiv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zycfv.cn/Article/details/gtvuvsgjms.html

[N07] 两数之和（返回下标）
来源：http://dali.birdmap.top/Article/details/gtfmklzgum.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ehwqpu.com/Article/details/gtuovieyyx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.svipenyu.cn/Article/details/gtjcrpibjr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xziqi.cn/Article/details/gtzfxcexbm.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhoulong.xyz/Article/details/gtsafxpxyp.html

Java: // 手写 HashMap
来源：http://dali.dianchejie.cn/Article/details/gtmanuofyr.html

Go:   // 手写 map[int]int
来源：http://dali.daxiang520.top/Article/details/gtwmrtwgku.html

Ruby: // 手写 Hash
来源：http://dali.mhx1999.top/Article/details/gtpknrsivo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hongshengwenyu.top/Article/details/gtdbmcakrk.html

[N08] 生成全排列
来源：http://dali.dianchejie.cn/Article/details/gtugbtalxd.html

Py:   itertools.permutations(arr)
来源：http://dali.tanke756.top/Article/details/gteqteaaqg.html

PHP:  // 手写递归交换
来源：http://dali.c1oappe.top/Article/details/gthopznjlk.html

JS:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gtsmpmcnpu.html

TS:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gttnzlqumb.html

Java: // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gtxbsnsjwi.html

Go:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gtpuobtevx.html

Ruby: arr.permutation.to_a
来源：http://dali.yonumen.top/Article/details/gtjzwcuteh.html

C#:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gtyoigcmdf.html

[N09] 栈与队列
来源：http://dali.zhiwuduotai.top/Article/details/gtbbdjmell.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.bjfxy.top/Article/details/gttdxrnwbu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yongpay.top/Article/details/gtbwnbnkdf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hysaishi.cn/Article/details/gtqwzsqdhs.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.guannengcc.top/Article/details/gtaljehgxs.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhongyouzk.top/Article/details/gttktmdmkr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zycfv.cn/Article/details/gtihwjnlwt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtkuyqmtdk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhoulong.xyz/Article/details/gtexsdkrzu.html

[N10] 链表节点定义
来源：http://dali.iojbl.cn/Article/details/gtzkjnezqc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yongpay.top/Article/details/gtiruazgrk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.aizwys.cn/Article/details/gtrhumpuov.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hongshengwenyu.top/Article/details/gtreyaghuv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.0kj1m.cn/Article/details/gtkxsyyapw.html

Java: class Node { int v; Node next; }
来源：http://dali.dashuyun.cn/Article/details/gthddtltgv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhoulong.xyz/Article/details/gtujxgxoii.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cheryme.top/Article/details/gtuecfdtpa.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.c1oappe.top/Article/details/gtdhqpwowv.html

[N11] 二叉树中序遍历
来源：http://dali.zdqjudy.top/Article/details/gtxcaxxcpx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.bjfxy.top/Article/details/gtzvglrdap.html

PHP:  // 手写递归函数
来源：http://dali.wangdashe.top/Article/details/gtwkabcsws.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xziqi.cn/Article/details/gtvfaroiyf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuxming.cn/Article/details/gtscnqcovs.html

Java: // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gtspfhbugh.html

Go:   // 手写递归
来源：http://dali.shuidangran.top/Article/details/gtdqdjxjgp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhiwuduotai.top/Article/details/gtghwngwzm.html

C#:   // 手写递归
来源：http://dali.cashguo.top/Article/details/gtfnvgxopd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhongyouzk.top/Article/details/gtaswltdmm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.daxiang520.top/Article/details/gthlabjghe.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ivvv.top/Article/details/gtqijxxumx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hywenlv.cn/Article/details/gtunuyhcvs.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuxming.cn/Article/details/gtohxqyezq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhongyouzk.top/Article/details/gtxelkhhrc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.bjfxy.top/Article/details/gtftlegdgx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.daxiang520.top/Article/details/gteuoqhrcx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fzhhl.top/Article/details/gthwrnesdq.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtbmhnrvgj.html

O. 并发与异步
来源：http://dali.xuetiantiany.cn/Article/details/gtsbihbzzs.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtgiytzllv.html

[O01] 启动一个线程
来源：http://dali.zhongyouzk.top/Article/details/gtafywpzbq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sufxvd.cn/Article/details/gtefehbdrx.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.daxiang520.top/Article/details/gtcpvwcmou.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ivvv.top/Article/details/gtwszionco.html

TS:   // 同 JS
来源：http://dali.daria6918.cn/Article/details/gtdlmzeydq.html

Java: new Thread(() -> f()).start()
来源：http://dali.yvedp.cn/Article/details/gtvvfphukr.html

Go:   go f()
来源：http://dali.bjfxy.top/Article/details/gtfxcwnupn.html

Ruby: Thread.new { f }
来源：http://dali.gogol.net.cn/Article/details/gtymzqvscg.html

C#:   Task.Run(() => F());
来源：http://dali.cucudq.cn/Article/details/gtdebbnrig.html

[O02] 使用线程池
来源：http://dali.yonumen.top/Article/details/gtooorhekx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xuetiantiany.cn/Article/details/gteoxrjnfg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtigerimyd.html

JS:   // worker_threads 线程池
来源：http://dali.iojbl.cn/Article/details/gtmhoaasbs.html

TS:   // worker_threads 线程池
来源：http://dali.yueranfly.top/Article/details/gtibigztqb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.aizwys.cn/Article/details/gtjzpgdqah.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.andypj.xyz/Article/details/gttpkswclu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.smart0.xyz/Article/details/gtzzplmrez.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhixingplan.top/Article/details/gtbdvynajp.html

[O03] 加锁保护共享数据
来源：http://dali.kuanghao11.cn/Article/details/gtzghhpwlo.html

Py:   with lock: shared += 1
来源：http://dali.smart0.xyz/Article/details/gtzhkjagio.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hnxiangtu.top/Article/details/gtigunftgo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.316326.xyz/Article/details/gtikybmnsl.html

TS:   // 同 JS
来源：http://dali.quarkkingdee.top/Article/details/gtagwvxmjh.html

Java: synchronized (this) { shared++; }
来源：http://dali.xuanzx.com/Article/details/gtolhkwdrt.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtscuryffp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.svipenyu.cn/Article/details/gtjyjuqjbm.html

C#:   lock (gate) { shared++; }
来源：http://dali.xinyue.icu/Article/details/gtrhufbcqx.html

[O04] 定义异步函数并等待
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjhxpelhg.html

Py:   async def f():⏎    await g()
来源：http://dali.cashguo.top/Article/details/gtnppyavwh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yuanzhike.top/Article/details/gtwnfvmyvq.html

JS:   async function f() { await g(); }
来源：http://dali.vqdsnc.cn/Article/details/gtboguwbcd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.kuanghao11.cn/Article/details/gthhequeyy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.haohaochexian.top/Article/details/gtdjaivgav.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gaohongyu789.top/Article/details/gtucnsfice.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gaohongyu789.top/Article/details/gtsskohvun.html

C#:   async Task F() { await G(); }
来源：http://dali.zhongyouzk.top/Article/details/gtowjszyta.html

[O05] 并发执行并等待全部完成
来源：http://dali.aizwys.cn/Article/details/gtizobnows.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zycfv.cn/Article/details/gtuwgzgzyb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sufxvd.cn/Article/details/gtmoixcwim.html

JS:   await Promise.all(tasks)
来源：http://dali.yj202588.top/Article/details/gtaegbutwy.html

TS:   await Promise.all(tasks)
来源：http://dali.xylfe.cn/Article/details/gtlnzqlaig.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gotoacloud.top/Article/details/gtgnzdtgcl.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.nanxinkj.top/Article/details/gtplydjrvs.html

Ruby: threads.map(&:join)
来源：http://dali.cashguo.top/Article/details/gtswblpjpi.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xinyue.icu/Article/details/gtrchyrxal.html

[O06] 使用进程池
来源：http://dali.hnxiangtu.top/Article/details/gteewrtbtf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cheryme.top/Article/details/gtolffoqtv.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtddusrwiv.html

JS:   // child_process / cluster 模块
来源：http://dali.xziqi.cn/Article/details/gtiiyixysr.html

TS:   // child_process / cluster 模块
来源：http://dali.daxiang520.top/Article/details/gtpxilopyb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hfpthk.cn/Article/details/gtfunxqkly.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.smart0.xyz/Article/details/gthtpdxmku.html

Ruby: // fork 块
来源：http://dali.cheryme.top/Article/details/gtylwldywf.html

C#:   Parallel.For
来源：http://dali.c1oappe.top/Article/details/gtfrasfaua.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gthrwmylny.html

P. 常用工具函数
来源：http://dali.ppjwa.cn/Article/details/gtqloeesnb.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtqsgkuiou.html

[P01] 生成 UUID
来源：http://dali.ehwqpu.com/Article/details/gtpkrwxlof.html

Py:   str(uuid.uuid4())
来源：http://dali.ybcxt.top/Article/details/gtmhdnhtbb.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jyoumei.cn/Article/details/gteelmqbvg.html

JS:   crypto.randomUUID()
来源：http://dali.jiagoushi.top/Article/details/gtssacczph.html

TS:   crypto.randomUUID()
来源：http://dali.tianlin.xyz/Article/details/gtefafjaug.html

Java: UUID.randomUUID().toString()
来源：http://dali.dashuyun.cn/Article/details/gtoqvhethg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.bjfxy.top/Article/details/gtjjonfkkx.html

Ruby: SecureRandom.uuid
来源：http://dali.shuidangran.top/Article/details/gtinqnbqho.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.nanxinkj.top/Article/details/gtnnwuwmfe.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gzhubu.top/Article/details/gtchsjpkuh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sxryk.cn/Article/details/gtovldrqbm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.c1oappe.top/Article/details/gttmckceet.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cheryme.top/Article/details/gtewnsskkk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cucudq.cn/Article/details/gtbangllyq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.pycfn.com/Article/details/gtycuokuzn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdgstjeus.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cheryme.top/Article/details/gtuzndpleu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.svipenyu.cn/Article/details/gtpqlkypcw.html

[P03] 生成短随机字符串
来源：http://dali.cashguo.top/Article/details/gtuhsabtce.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shangyingyoupin.top/Article/details/gthioktajb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ivvv.top/Article/details/gtdsuumfde.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aizwys.cn/Article/details/gtnpzmipay.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.316326.xyz/Article/details/gtsffsstvs.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zycfv.cn/Article/details/gtyrsfxosi.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.nanxuanxn.top/Article/details/gtbxslccxm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xuanzx.com/Article/details/gtwttbzate.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yj20258.top/Article/details/gtywltzora.html

[P04] 求长度
来源：http://dali.yj20258888.top/Article/details/gtfckjiebl.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hammf.cn/Article/details/gtlvlzfhis.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yongpay.top/Article/details/gtoxqlxtrw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xziqi.cn/Article/details/gtfitbmrql.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cucudq.cn/Article/details/gtydtrzkan.html

Java: list.size();  map.size();  s.length()
来源：http://dali.meibo888.top/Article/details/gtoktumxfv.html

Go:   len(arr);  len(m)
来源：http://dali.aibaodan.cn/Article/details/gtiocbmoek.html

Ruby: x.length;  x.size
来源：http://dali.redwolf501.top/Article/details/gtprjsbeta.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cashguo.top/Article/details/gtdujojvxe.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yvedp.cn/Article/details/gtbvyxfkhu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ydzc1.top/Article/details/gtwhgbursx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.mhx1999.top/Article/details/gtscwycdui.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.sufxvd.cn/Article/details/gtkydnmgai.html


<!-- 参考信息 -->