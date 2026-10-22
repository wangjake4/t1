代发 wailian999

C#:   (int)resp.StatusCode
来源：http://dali.hysaishi.cn/Article/details/gtufpxstgg.html

[L08] 并发请求多个地址
来源：http://dali.nanxinkj.top/Article/details/gtinlrhkkz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.wangshuangyany.cn/Article/details/gttgdiiaty.html

PHP:  curl_multi_init() 系列
来源：http://dali.redwolf501.top/Article/details/gtlzfvwagn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.316326.xyz/Article/details/gtwbwfnvyt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gtvouulifr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.feifeiyinyue.top/Article/details/gtsehgjbmt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.daxiang520.top/Article/details/gtjimdzxrl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.meibo888.top/Article/details/gtkjpkpccz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sufxvd.cn/Article/details/gtwrdhxese.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtzrzfratg.html

M. 命令行 / 进程 / 环境
来源：http://dali.xylfe.cn/Article/details/gtpknrkceh.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtinadnfti.html

[M01] 读取命令行参数
来源：http://dali.daria6918.cn/Article/details/gtpfhtbozr.html

Py:   sys.argv[1:]
来源：http://dali.birdmap.top/Article/details/gtagmcplgc.html

PHP:  $argv;  $argc;
来源：http://dali.yj20258888.top/Article/details/gtopgxgevq.html

JS:   process.argv.slice(2)
来源：http://dali.aizwys.cn/Article/details/gtiyujgngk.html

TS:   process.argv.slice(2)
来源：http://dali.fzhhl.top/Article/details/gtifgqjdul.html

Java: args 数组（main 方法参数）
来源：http://dali.cqqwz.cn/Article/details/gtjuwuhtzk.html

Go:   os.Args[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaiiklbrg.html

Ruby: ARGV
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbxroqjpx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jyoumei.cn/Article/details/gtxrmayyyd.html

[M02] 读取环境变量
来源：http://dali.gzhubu.top/Article/details/gtxapnllhw.html

Py:   os.environ.get("HOME")
来源：http://dali.aibaodan.cn/Article/details/gtrxhvqomz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sysykeji.top/Article/details/gtipfuluxq.html

JS:   process.env.HOME
来源：http://dali.fengsongda.top/Article/details/gtcfkgwxpt.html

TS:   process.env.HOME
来源：http://dali.aizwys.cn/Article/details/gtgpwhwsar.html

Java: System.getenv("HOME")
来源：http://dali.andypj.xyz/Article/details/gtxuqfcoee.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.mhx1999.top/Article/details/gtnubenwta.html

Ruby: ENV["HOME"]
来源：http://dali.jinqigufen.top/Article/details/gtixkiyvpi.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.smart0.xyz/Article/details/gtllpxkwlv.html

[M03] 执行外部命令
来源：http://dali.hywenlv.cn/Article/details/gtwdbbzgdt.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.vqdsnc.cn/Article/details/gtokitffif.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yangfankeji.com/Article/details/gtfuvnxroh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuanzhike.top/Article/details/gtwlcvbalc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlopytdjt.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.fzhhl.top/Article/details/gtcgdqlqdc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.dianchejie.cn/Article/details/gtwpswjjrd.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ydzc1.top/Article/details/gtutecwlbu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gotoacloud.top/Article/details/gtqfvdqrfb.html

[M04] 获取当前工作目录
来源：http://dali.shanyushiyangtech.top/Article/details/gtbafitaox.html

Py:   os.getcwd()
来源：http://dali.hfpthk.cn/Article/details/gtzbhtodwl.html

PHP:  getcwd();
来源：http://dali.guannengcc.top/Article/details/gtktmjfttb.html

JS:   process.cwd()
来源：http://dali.ydzc1.top/Article/details/gtsssxlncc.html

TS:   process.cwd()
来源：http://dali.chenzaomai.com/Article/details/gtrahawcbn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.bjfxy.top/Article/details/gtubqjvmwx.html

Go:   os.Getwd()
来源：http://dali.gaohongyu789.top/Article/details/gtezkpxftc.html

Ruby: Dir.pwd
来源：http://dali.hnxiangtu.top/Article/details/gtgywdltry.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ehwqpu.com/Article/details/gtoxcaivrc.html

[M05] 设置退出码
来源：http://dali.yvedp.cn/Article/details/gtksemvkxv.html

Py:   sys.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gtmdqtriut.html

PHP:  exit(1);
来源：http://dali.jianghu66.top/Article/details/gtfzrcbvjd.html

JS:   process.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtvhuxieof.html

TS:   process.exit(1)
来源：http://dali.daria6918.cn/Article/details/gtbarutxov.html

Java: System.exit(1)
来源：http://dali.redwolf501.top/Article/details/gtaqcamtvc.html

Go:   os.Exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gtxteagfxz.html

Ruby: exit 1
来源：http://dali.aizwys.cn/Article/details/gtrkufwpgo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hfpthk.cn/Article/details/gtwvtztevn.html

[M06] 向标准错误输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpbnkkujk.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xuanzx.com/Article/details/gtounnoqfh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhoulong.xyz/Article/details/gtszdzlusw.html

JS:   console.error("err")
来源：http://dali.hfpthk.cn/Article/details/gtbbvvvvxy.html

TS:   console.error("err")
来源：http://dali.gaohongyu789.top/Article/details/gtoblsqpnt.html

Java: System.err.println("err")
来源：http://dali.zycfv.cn/Article/details/gtjweayowo.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hysaishi.cn/Article/details/gtybmncokb.html

Ruby: warn "err"
来源：http://dali.sweek.top/Article/details/gtkaniuziw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jqgufenzy.top/Article/details/gtqpmnjite.html

[M07] 判断是否为主入口
来源：http://dali.pengpengdd.cyou/Article/details/gtuifovuty.html

Py:   if __name__ == "__main__":
来源：http://dali.xziqi.cn/Article/details/gteirkztag.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.pycfn.com/Article/details/gtcqnfbnhw.html

JS:   require.main === module
来源：http://dali.kuanghao11.cn/Article/details/gtfnopqagl.html

TS:   require.main === module
来源：http://dali.chenzaomai.com/Article/details/gttdwybeam.html

Java: public static void main(String[] args)
来源：http://dali.sysykeji.top/Article/details/gtrifyajov.html

Go:   func main()
来源：http://dali.cdnleiting.top/Article/details/gtrrjxbbne.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hywenlv.cn/Article/details/gtugqtuqlz.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gtifsganbc.html

[M08] 获取系统与运行时信息
来源：http://dali.316326.xyz/Article/details/gthzwkeekj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.9152youxi.cn/Article/details/gtcpdepbsp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.birdmap.top/Article/details/gtlpuebiot.html

JS:   process.platform;  process.version
来源：http://dali.chenjidiqi.icu/Article/details/gtmmeczrgj.html

TS:   process.platform;  process.version
来源：http://dali.yanxiufei.cn/Article/details/gtydbrjjdm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yj202588.top/Article/details/gtxisvgsfc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jqgufenzy.top/Article/details/gtntsplipi.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.fzhhl.top/Article/details/gtidgowvqu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.meibo888.top/Article/details/gtbetvphew.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gttbfqqlyl.html

N. 数据结构与算法
来源：http://dali.hammf.cn/Article/details/gtbdurxkcx.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtaonwkmog.html

[N01] 二分查找（有序数组）
来源：http://dali.pengpengdd.cyou/Article/details/gtobtgtror.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtxnqjsyca.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ppjwa.cn/Article/details/gtowsrzbwc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhengqikj.top/Article/details/gtbtiauyau.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.c1oappe.top/Article/details/gtwqlhozko.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yongpay.top/Article/details/gtvezxwenw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtjqmgqkbq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.daria6918.cn/Article/details/gtywqjpvib.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtndpxjznd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.0kj1m.cn/Article/details/gtppoqnjjv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuxming.cn/Article/details/gtajngulvg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.guannengcc.top/Article/details/gtcaujuguq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jlsjyb.cn/Article/details/gtvbbpqspp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jianghu66.top/Article/details/gtxrqthamk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.gotoacloud.top/Article/details/gtwbjogyrr.html

Go:   slices.Sort(arr)
来源：http://dali.shzxlz.cn/Article/details/gtlatjcsmx.html

Ruby: arr.sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiugqaoua.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.feifeiyinyue.top/Article/details/gtneufktyd.html

[N03] 快速排序（分治示例）
来源：http://dali.gotoacloud.top/Article/details/gtszmgubuf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtukdjaxmf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jqgufenzy.top/Article/details/gtfyiuysny.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gtnqoiwlss.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.kuanghao11.cn/Article/details/gtxjitpnxx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yonumen.top/Article/details/gtpshihnak.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xuanzx.com/Article/details/gtgkstybku.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sufxvd.cn/Article/details/gtahoikpkv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhiwuduotai.top/Article/details/gtiobqjdym.html

[N04] 斐波那契数列
来源：http://dali.pengpengdd.cyou/Article/details/gtxgavbbwh.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtscgxinaq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yuxming.cn/Article/details/gtxbusuybo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gtuxepgmav.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuanzhike.top/Article/details/gtqndzszhm.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cucudq.cn/Article/details/gtwiesiwce.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.gzhubu.top/Article/details/gtydwjcqhv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xziqi.cn/Article/details/gtwonyzprp.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jlsjyb.cn/Article/details/gtsljxsvyf.html

[N05] 最大公约数
来源：http://dali.ivvv.top/Article/details/gtvakmejnt.html

Py:   math.gcd(a, b)
来源：http://dali.0kj1m.cn/Article/details/gtnoqbceil.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.nanxinkj.top/Article/details/gtvufxnmxo.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhiwuduotai.top/Article/details/gteqnmydve.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shuidangran.top/Article/details/gttlbrutwz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hysaishi.cn/Article/details/gtzrdblfvy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ivvv.top/Article/details/gtmetqsiau.html

Ruby: a.gcd(b)
来源：http://dali.jianghu66.top/Article/details/gtlwhqpzdj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cashguo.top/Article/details/gtfqxvsoje.html

[N06] 判断回文字符串
来源：http://dali.nanxuanxn.top/Article/details/gtpkpaskun.html

Py:   s == s[::-1]
来源：http://dali.cqqwz.cn/Article/details/gtpdtfcveo.html

PHP:  $s === strrev($s);
来源：http://dali.dianchejie.cn/Article/details/gtamgwtkzr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gtnetmisqe.html

TS:   s === [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gtzjxlhbev.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.dianchejie.cn/Article/details/gtrdofxiwh.html

Go:   // 双指针从两端比较
来源：http://dali.jlsjyb.cn/Article/details/gtxwaorshq.html

Ruby: s == s.reverse
来源：http://dali.mhx1999.top/Article/details/gtyvxtvgtj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cdnleiting.top/Article/details/gtvdyqrbzt.html

[N07] 两数之和（返回下标）
来源：http://dali.yangfankeji.com/Article/details/gtplkraaun.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gaohongyu789.top/Article/details/gtbexrrtdo.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.316326.xyz/Article/details/gtfsmhrzap.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtckufzeeu.html

TS:   // 手写 Map<string, number>
来源：http://dali.quarkkingdee.top/Article/details/gtadsxixtf.html

Java: // 手写 HashMap
来源：http://dali.dianchejie.cn/Article/details/gtxtwfyniu.html

Go:   // 手写 map[int]int
来源：http://dali.hammf.cn/Article/details/gtxyomdjbf.html

Ruby: // 手写 Hash
来源：http://dali.havefunace.top/Article/details/gtsnkcwlra.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.chenlongwang.top/Article/details/gtaarfwpip.html

[N08] 生成全排列
来源：http://dali.nwbrower.top/Article/details/gtphuvieph.html

Py:   itertools.permutations(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtadivieyd.html

PHP:  // 手写递归交换
来源：http://dali.chenzaomai.com/Article/details/gtplsbbyrn.html

JS:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gtasnldfdf.html

TS:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gtosjduuml.html

Java: // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtkickgeng.html

Go:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gtgwqstfof.html

Ruby: arr.permutation.to_a
来源：http://dali.0kj1m.cn/Article/details/gtpekdkxsu.html

C#:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gttrsjddjh.html

[N09] 栈与队列
来源：http://dali.snrcjt.cn/Article/details/gthlnggjhx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zycfv.cn/Article/details/gthfghvjfm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.9152youxi.cn/Article/details/gtxlxyqxeo.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yj20258.top/Article/details/gtqzmqzdkl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cheryme.top/Article/details/gtrzkqfalq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shangyingyoupin.top/Article/details/gtkohoztyg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhoulong.xyz/Article/details/gtczywhgst.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sweek.top/Article/details/gtuwpoojqx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.tian-w.cn/Article/details/gtvuurepcq.html

[N10] 链表节点定义
来源：http://dali.hysaishi.cn/Article/details/gtuytjqecl.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.guannengcc.top/Article/details/gtshsuyfaq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.fengsongda.top/Article/details/gtkffwaamr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zycfv.cn/Article/details/gtsddwxick.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.andypj.xyz/Article/details/gtfvhbcqsl.html

Java: class Node { int v; Node next; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmgpgdeie.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.wangshuangyany.cn/Article/details/gtgqgqznuv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gaohongyu789.top/Article/details/gtwfymcqzf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.fengsongda.top/Article/details/gtjbzwfrfq.html

[N11] 二叉树中序遍历
来源：http://dali.jinqigufen.top/Article/details/gtiyfkbpon.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.tanke756.top/Article/details/gtfmeirrls.html

PHP:  // 手写递归函数
来源：http://dali.sxryk.cn/Article/details/gtlouhwktu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pycfn.com/Article/details/gtjzewfxgt.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aizwys.cn/Article/details/gtodfqxnia.html

Java: // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gtmazpgvxz.html

Go:   // 手写递归
来源：http://dali.gogol.net.cn/Article/details/gtyzcndpbm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hongshengwenyu.top/Article/details/gtwrrpzjsn.html

C#:   // 手写递归
来源：http://dali.hysaishi.cn/Article/details/gtgzypibyh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yuanzhike.top/Article/details/gtlufvpiwf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yanxiufei.cn/Article/details/gthyxxxjtm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.nwbrower.top/Article/details/gtbxbpywne.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.haohaochexian.top/Article/details/gtelpcbnhj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenjidiqi.icu/Article/details/gtyxbyurqh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.c1oappe.top/Article/details/gtenatmjwy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.snrcjt.cn/Article/details/gtxnttagnb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ehwqpu.com/Article/details/gtohcnrcbd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj202588.top/Article/details/gtpljkbtch.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtssodgvin.html

O. 并发与异步
来源：http://dali.tian-w.cn/Article/details/gtfzddyeqq.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtokdldnwh.html

[O01] 启动一个线程
来源：http://dali.meibo888.top/Article/details/gtybnepugc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.tian-w.cn/Article/details/gttgtelagt.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hnxiangtu.top/Article/details/gtmrtgwmgk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.feifeiyinyue.top/Article/details/gtyeofbjem.html

TS:   // 同 JS
来源：http://dali.haohaochexian.top/Article/details/gtbyhgrxme.html

Java: new Thread(() -> f()).start()
来源：http://dali.yj202588.top/Article/details/gtofpgqzxg.html

Go:   go f()
来源：http://dali.yanxiufei.cn/Article/details/gtchwensmj.html

Ruby: Thread.new { f }
来源：http://dali.zhiwuduotai.top/Article/details/gtbyjvcvwt.html

C#:   Task.Run(() => F());
来源：http://dali.jyoumei.cn/Article/details/gtkojrdfvx.html

[O02] 使用线程池
来源：http://dali.wangdashe.top/Article/details/gtasuguyum.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.pengpengdd.cyou/Article/details/gtxablxtjo.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cashguo.top/Article/details/gtethvpxxs.html

JS:   // worker_threads 线程池
来源：http://dali.cheryme.top/Article/details/gtfkwlggqe.html

TS:   // worker_threads 线程池
来源：http://dali.redwolf501.top/Article/details/gtxycfkstr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.fzhhl.top/Article/details/gtbbavinbw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.snrcjt.cn/Article/details/gtkxdjbagc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ybcxt.top/Article/details/gtoztvebfu.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yongpay.top/Article/details/gthzoondul.html

[O03] 加锁保护共享数据
来源：http://dali.cashguo.top/Article/details/gttuhyjbfj.html

Py:   with lock: shared += 1
来源：http://dali.cdnleiting.top/Article/details/gtqvhwughp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.nanxuanxn.top/Article/details/gtqpfdhqbi.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.nanxuanxn.top/Article/details/gtccqsmpcb.html

TS:   // 同 JS
来源：http://dali.shuidangran.top/Article/details/gtjqnzmxvw.html

Java: synchronized (this) { shared++; }
来源：http://dali.cucudq.cn/Article/details/gtskxgcrna.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.dashuyun.cn/Article/details/gtuksrexfg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhoulong.xyz/Article/details/gttdpmqayr.html

C#:   lock (gate) { shared++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtglldwxeb.html

[O04] 定义异步函数并等待
来源：http://dali.hysaishi.cn/Article/details/gtjdarncuo.html

Py:   async def f():⏎    await g()
来源：http://dali.jyoumei.cn/Article/details/gtasgjufjn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhongyouzk.top/Article/details/gtvgkmdfsa.html

JS:   async function f() { await g(); }
来源：http://dali.jlsjyb.cn/Article/details/gtyylezzdo.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.tianlin.xyz/Article/details/gtprhyhjdf.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.snrcjt.cn/Article/details/gtrorumpyj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.andypj.xyz/Article/details/gtincozmsb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.bjfxy.top/Article/details/gtnoydsrbo.html

C#:   async Task F() { await G(); }
来源：http://dali.jqgufenzy.top/Article/details/gtudnabfkj.html

[O05] 并发执行并等待全部完成
来源：http://dali.hfpthk.cn/Article/details/gtslmdzraj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hammf.cn/Article/details/gttjxqlyoz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.tian-w.cn/Article/details/gtbrzttide.html

JS:   await Promise.all(tasks)
来源：http://dali.hnqzz.top/Article/details/gtiaskdqhl.html

TS:   await Promise.all(tasks)
来源：http://dali.smart0.xyz/Article/details/gtzgaxnilx.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.nanxuanxn.top/Article/details/gtrvyzomim.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gzhubu.top/Article/details/gttzuvpubm.html

Ruby: threads.map(&:join)
来源：http://dali.0kj1m.cn/Article/details/gthahbzfyc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.nanxuanxn.top/Article/details/gtdvvyrlwh.html

[O06] 使用进程池
来源：http://dali.yongpay.top/Article/details/gtynyfzmkk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.meibo888.top/Article/details/gtiuwluyxt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.chenjidiqi.icu/Article/details/gtyowumvtw.html

JS:   // child_process / cluster 模块
来源：http://dali.jiagoushi.top/Article/details/gtzywwdebl.html

TS:   // child_process / cluster 模块
来源：http://dali.jiagoushi.top/Article/details/gtdnjzcoen.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.daria6918.cn/Article/details/gtyyxvsekv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tian-w.cn/Article/details/gtseqdzxlc.html

Ruby: // fork 块
来源：http://dali.wangdashe.top/Article/details/gtbwpnxnau.html

C#:   Parallel.For
来源：http://dali.xinyue.icu/Article/details/gtzgmvisdv.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gturhqftdz.html

P. 常用工具函数
来源：http://dali.pengpengdd.cyou/Article/details/gtavgizhxd.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtakfyyrpl.html

[P01] 生成 UUID
来源：http://dali.gotoacloud.top/Article/details/gtszzyznej.html

Py:   str(uuid.uuid4())
来源：http://dali.xuetiantiany.cn/Article/details/gtlpiorpzz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sysykeji.top/Article/details/gtqxdmtvzx.html

JS:   crypto.randomUUID()
来源：http://dali.hywenlv.cn/Article/details/gtxzqzajhv.html

TS:   crypto.randomUUID()
来源：http://dali.sysykeji.top/Article/details/gtvthuwquu.html

Java: UUID.randomUUID().toString()
来源：http://dali.zycfv.cn/Article/details/gtjyuwsjen.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shanyushiyangtech.top/Article/details/gtbpeewyig.html

Ruby: SecureRandom.uuid
来源：http://dali.ppjwa.cn/Article/details/gtftyqmzrp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cdnleiting.top/Article/details/gtngdbfvsk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ivvv.top/Article/details/gtfrcaalij.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenjidiqi.icu/Article/details/gtobrszcey.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.pycfn.com/Article/details/gtkvbqnfks.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.pengpengdd.cyou/Article/details/gttjmukmwc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gotoacloud.top/Article/details/gtppqcgach.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.nanxuanxn.top/Article/details/gtcanefruw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xylfe.cn/Article/details/gtbfvjfhsy.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.dashuyun.cn/Article/details/gtszcvyzri.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cheryme.top/Article/details/gthdruacmh.html

[P03] 生成短随机字符串
来源：http://dali.zhengqikj.top/Article/details/gtwbwsfnyt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ybcxt.top/Article/details/gtrvfiopop.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gtffqvppoq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.snrcjt.cn/Article/details/gtzhkthdig.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.meibo888.top/Article/details/gtcemfewtu.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.nanxinkj.top/Article/details/gtuykqixoi.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ybcxt.top/Article/details/gtiszlgfwm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.pengpengdd.cyou/Article/details/gtpuzgcacp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xinyue.icu/Article/details/gtcgdydwfu.html

[P04] 求长度
来源：http://dali.chenzaomai.com/Article/details/gtazprekbw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ehwqpu.com/Article/details/gtqgqpbukf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gtzlavtdwx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zdqjudy.top/Article/details/gtjyujjnld.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gaohongyu789.top/Article/details/gtopskmcoo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.andypj.xyz/Article/details/gtjmmjokhl.html

Go:   len(arr);  len(m)
来源：http://dali.yuanzhike.top/Article/details/gtgvhlaodi.html

Ruby: x.length;  x.size
来源：http://dali.jqgfzy.top/Article/details/gtpjcveouo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.haohaochexian.top/Article/details/gtukkigjnf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhengqikj.top/Article/details/gtadiazhzl.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gaohongyu789.top/Article/details/gttonujxui.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cheryme.top/Article/details/gtkdxwkipa.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.kuanghao11.cn/Article/details/gtdbepzsgc.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.vqdsnc.cn/Article/details/gtxzigfajp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zdqjudy.top/Article/details/gtvfjgbgdn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zdqjudy.top/Article/details/gtmcmakquw.html

Ruby: a == b
来源：http://dali.jianghu66.top/Article/details/gtvmzopywa.html


<!-- 参考信息 -->