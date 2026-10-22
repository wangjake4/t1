代发 wailian999

TS:   resp.ok;  resp.status
来源：http://dali.cucudq.cn/Article/details/gtoqskcwyr.html

Java: resp.statusCode()
来源：http://dali.sxryk.cn/Article/details/gtlyhchdmr.html

Go:   resp.StatusCode
来源：http://dali.0kj1m.cn/Article/details/gtqbfpanwu.html

Ruby: resp.code.to_i
来源：http://dali.nwbrower.top/Article/details/gtzvosuqru.html

C#:   (int)resp.StatusCode
来源：http://dali.redwolf501.top/Article/details/gthgkqgsux.html

[L08] 并发请求多个地址
来源：http://dali.c1oappe.top/Article/details/gtoibfspop.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cqqwz.cn/Article/details/gtqkvgkccv.html

PHP:  curl_multi_init() 系列
来源：http://dali.cashguo.top/Article/details/gtvdgtjgzh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tian-w.cn/Article/details/gtdcngrkgr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pycfn.com/Article/details/gtjiyvrplr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj20258.top/Article/details/gtjurlxphd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xziqi.cn/Article/details/gtreacpdkd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxgitsayy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gtjudqrmht.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtskoacrrk.html

M. 命令行 / 进程 / 环境
来源：http://dali.fengsongda.top/Article/details/gtcforvxzt.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtlrizojkl.html

[M01] 读取命令行参数
来源：http://dali.yj20258.top/Article/details/gtifgimlfk.html

Py:   sys.argv[1:]
来源：http://dali.gogol.net.cn/Article/details/gtqsogqdlo.html

PHP:  $argv;  $argc;
来源：http://dali.mhx1999.top/Article/details/gtqkwgoapp.html

JS:   process.argv.slice(2)
来源：http://dali.birdmap.top/Article/details/gtvovfqpgi.html

TS:   process.argv.slice(2)
来源：http://dali.jiagoushi.top/Article/details/gtreqqkcmw.html

Java: args 数组（main 方法参数）
来源：http://dali.aizwys.cn/Article/details/gtqhworgxx.html

Go:   os.Args[1:]
来源：http://dali.haohaochexian.top/Article/details/gtmmazfllq.html

Ruby: ARGV
来源：http://dali.hywenlv.cn/Article/details/gtcrqjgqxv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.birdmap.top/Article/details/gthnmbfpoj.html

[M02] 读取环境变量
来源：http://dali.yongpay.top/Article/details/gtbkcgaxam.html

Py:   os.environ.get("HOME")
来源：http://dali.hfpthk.cn/Article/details/gtmzrrmuhy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinqigufen.top/Article/details/gtktjhvynx.html

JS:   process.env.HOME
来源：http://dali.chenjidiqi.icu/Article/details/gtasvpbjuc.html

TS:   process.env.HOME
来源：http://dali.c1oappe.top/Article/details/gtbwglzoso.html

Java: System.getenv("HOME")
来源：http://dali.tianlin.xyz/Article/details/gttuxitkxv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtzgifiykz.html

Ruby: ENV["HOME"]
来源：http://dali.zhiwuduotai.top/Article/details/gtctdliush.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gtdrnbndop.html

[M03] 执行外部命令
来源：http://dali.xuanzx.com/Article/details/gtiqyqoroo.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.vqdsnc.cn/Article/details/gtnjgspeet.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.snrcjt.cn/Article/details/gtzelnjizj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.redwolf501.top/Article/details/gtmeubolfi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.mhx1999.top/Article/details/gtrtguyrem.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hongshengwenyu.top/Article/details/gtfgrzrlkx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shuidangran.top/Article/details/gtruepvtvx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jqgufenzy.top/Article/details/gtbwmdscco.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nanxinkj.top/Article/details/gtozwodetb.html

[M04] 获取当前工作目录
来源：http://dali.zhongyouzk.top/Article/details/gtsiejaxlp.html

Py:   os.getcwd()
来源：http://dali.jinqigfzy.top/Article/details/gtfcfqfayo.html

PHP:  getcwd();
来源：http://dali.nanxinkj.top/Article/details/gtbwcaxsrb.html

JS:   process.cwd()
来源：http://dali.feifeiyinyue.top/Article/details/gthzmluwco.html

TS:   process.cwd()
来源：http://dali.dianchejie.cn/Article/details/gtdjbgnvmn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.haohaochexian.top/Article/details/gtrmluhhdu.html

Go:   os.Getwd()
来源：http://dali.dianchejie.cn/Article/details/gtgcxcsxzt.html

Ruby: Dir.pwd
来源：http://dali.zhiwuduotai.top/Article/details/gtllljfxkn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.havefunace.top/Article/details/gtaocnlfws.html

[M05] 设置退出码
来源：http://dali.yvedp.cn/Article/details/gtwyvsdskj.html

Py:   sys.exit(1)
来源：http://dali.ybcxt.top/Article/details/gtxpisijga.html

PHP:  exit(1);
来源：http://dali.gotoacloud.top/Article/details/gtrnmvhmgn.html

JS:   process.exit(1)
来源：http://dali.yj20258.top/Article/details/gtdyfcvbyx.html

TS:   process.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpqwrnnse.html

Java: System.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtwfhvrqsg.html

Go:   os.Exit(1)
来源：http://dali.yj20258888.top/Article/details/gtwzpaqofa.html

Ruby: exit 1
来源：http://dali.sxryk.cn/Article/details/gtlgigywym.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.daxiang520.top/Article/details/gtrmovbzed.html

[M06] 向标准错误输出
来源：http://dali.ydzc1.top/Article/details/gtrfgyszut.html

Py:   print("err", file=sys.stderr)
来源：http://dali.daxiang520.top/Article/details/gtxhwjmozz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.iojbl.cn/Article/details/gtvkvjzyiz.html

JS:   console.error("err")
来源：http://dali.zdqjudy.top/Article/details/gtzmafkokk.html

TS:   console.error("err")
来源：http://dali.zhixingplan.top/Article/details/gtubhlfqkd.html

Java: System.err.println("err")
来源：http://dali.yuxming.cn/Article/details/gtzmkwhobr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnncfoeta.html

Ruby: warn "err"
来源：http://dali.316326.xyz/Article/details/gtlfnhcire.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yanxiufei.cn/Article/details/gtxivrotgt.html

[M07] 判断是否为主入口
来源：http://dali.cashguo.top/Article/details/gtppcymcff.html

Py:   if __name__ == "__main__":
来源：http://dali.havefunace.top/Article/details/gtmlbfqmyg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xinyue.icu/Article/details/gtbvbfnuyd.html

JS:   require.main === module
来源：http://dali.zhongyouzk.top/Article/details/gtohdfgkvg.html

TS:   require.main === module
来源：http://dali.gotoacloud.top/Article/details/gtbrrqhvuu.html

Java: public static void main(String[] args)
来源：http://dali.gotoacloud.top/Article/details/gtnctekian.html

Go:   func main()
来源：http://dali.hfpthk.cn/Article/details/gtrfrntkgh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.guannengcc.top/Article/details/gttgudtvec.html

C#:   static void Main(string[] args)
来源：http://dali.0kj1m.cn/Article/details/gtafhnlvbu.html

[M08] 获取系统与运行时信息
来源：http://dali.gzhubu.top/Article/details/gtyrixvfqd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxhiyyncz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinqigfzy.top/Article/details/gtlvyouqgv.html

JS:   process.platform;  process.version
来源：http://dali.jqgfzy.top/Article/details/gttudvpnli.html

TS:   process.platform;  process.version
来源：http://dali.jinghuilouyu.cn/Article/details/gtosfzqnpf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jqgufenzy.top/Article/details/gtgvdstton.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj20258.top/Article/details/gtwbczaajy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zdqjudy.top/Article/details/gtwnqgnqyl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sxryk.cn/Article/details/gtqxutanud.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gthrrfixcy.html

N. 数据结构与算法
来源：http://dali.cucudq.cn/Article/details/gtsqsutuds.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtwnomgnin.html

[N01] 二分查找（有序数组）
来源：http://dali.jlsjyb.cn/Article/details/gtevuouuej.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gthsgrjqsd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrpbvsgws.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangdashe.top/Article/details/gtvjeuodyr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.meibo888.top/Article/details/gtemovgvcr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gthzrnnsne.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gtssgfvpdz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zycfv.cn/Article/details/gtrxvdcwmx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gtnptjgtid.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.smart0.xyz/Article/details/gtiwzrocnf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gtnbuntfco.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ybcxt.top/Article/details/gtpyisqevf.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnqzz.top/Article/details/gtarlydcxv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.316326.xyz/Article/details/gtfjcktaur.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yj20258.top/Article/details/gtyfgbedze.html

Go:   slices.Sort(arr)
来源：http://dali.nwbrower.top/Article/details/gtrlndnhaq.html

Ruby: arr.sort
来源：http://dali.wangdashe.top/Article/details/gtkbvqtjiu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhixingplan.top/Article/details/gtkdkhrvbl.html

[N03] 快速排序（分治示例）
来源：http://dali.yuxming.cn/Article/details/gtvltlepht.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhengqikj.top/Article/details/gtyoywmylh.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hysaishi.cn/Article/details/gtxynmwriy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuetiantiany.cn/Article/details/gtedepwidy.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hywenlv.cn/Article/details/gtjpfrucat.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gogol.net.cn/Article/details/gtjjvrglbh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.nanxinkj.top/Article/details/gtmwvoflrs.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xuanzx.com/Article/details/gticehfunu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.aizwys.cn/Article/details/gtratxoeqo.html

[N04] 斐波那契数列
来源：http://dali.bjfxy.top/Article/details/gtjwdjdgrt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.dianchejie.cn/Article/details/gtrxpycqql.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.nanxuanxn.top/Article/details/gtkrynhqht.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gtjpgcpwwx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gthbjxxlig.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.snrcjt.cn/Article/details/gtcwvraaxf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ehwqpu.com/Article/details/gtqxbnehuo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xylfe.cn/Article/details/gtccetjedq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.dianchejie.cn/Article/details/gtjswfrzuj.html

[N05] 最大公约数
来源：http://dali.jyoumei.cn/Article/details/gtlqxkfhjj.html

Py:   math.gcd(a, b)
来源：http://dali.tianlin.xyz/Article/details/gtwmmkuwwl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.haohaochexian.top/Article/details/gtryyzelvb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.c1oappe.top/Article/details/gthsnijkgz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gotoacloud.top/Article/details/gtrfgthwnx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cqqwz.cn/Article/details/gtebalycvv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.kuanghao11.cn/Article/details/gtntinypbe.html

Ruby: a.gcd(b)
来源：http://dali.yanxiufei.cn/Article/details/gtalrufihq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xylfe.cn/Article/details/gtxclrqexl.html

[N06] 判断回文字符串
来源：http://dali.sxryk.cn/Article/details/gtpgldwwmr.html

Py:   s == s[::-1]
来源：http://dali.zhixingplan.top/Article/details/gtztkmckzw.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gtcpkcojfn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gthhtxampc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gtepextblz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yonumen.top/Article/details/gtjvqmnguh.html

Go:   // 双指针从两端比较
来源：http://dali.yongpay.top/Article/details/gtzwcxbiky.html

Ruby: s == s.reverse
来源：http://dali.guannengcc.top/Article/details/gtsvfluseg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jianghu66.top/Article/details/gtqwfmkply.html

[N07] 两数之和（返回下标）
来源：http://dali.snrcjt.cn/Article/details/gtciqqunmw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.chenzaomai.com/Article/details/gtfaaetsai.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.feifeiyinyue.top/Article/details/gtqtynqfme.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jqgfzy.top/Article/details/gtvzkxgrxc.html

TS:   // 手写 Map<string, number>
来源：http://dali.andypj.xyz/Article/details/gtptienskh.html

Java: // 手写 HashMap
来源：http://dali.zdqjudy.top/Article/details/gtyjfszxsh.html

Go:   // 手写 map[int]int
来源：http://dali.vqdsnc.cn/Article/details/gtpfiuyzto.html

Ruby: // 手写 Hash
来源：http://dali.zycfv.cn/Article/details/gtbfhbsnik.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinqigufen.top/Article/details/gtyfoankwo.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gtladdnxiy.html

Py:   itertools.permutations(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtyawipvea.html

PHP:  // 手写递归交换
来源：http://dali.yanxiufei.cn/Article/details/gtugfzlwhe.html

JS:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gtiijzwrlg.html

TS:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gtiylecvuz.html

Java: // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gtmicytjdp.html

Go:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtlzgxswwx.html

Ruby: arr.permutation.to_a
来源：http://dali.cheryme.top/Article/details/gtvaybnlkb.html

C#:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gtiksgrqqr.html

[N09] 栈与队列
来源：http://dali.daria6918.cn/Article/details/gtsufkqutb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.0kj1m.cn/Article/details/gtibkktizd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yj202588.top/Article/details/gtedgahugc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yvedp.cn/Article/details/gttmswgeme.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.feifeiyinyue.top/Article/details/gtbnnokuwp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xuetiantiany.cn/Article/details/gtcrsvrjen.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jqgfzy.top/Article/details/gtmrxhbrjj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jianghu66.top/Article/details/gtkeyumqij.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.iojbl.cn/Article/details/gtcqaclmby.html

[N10] 链表节点定义
来源：http://dali.yueranfly.top/Article/details/gttanzzode.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.haohaochexian.top/Article/details/gtkufxsuxz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gaohongyu789.top/Article/details/gtjmakqyly.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jqgfzy.top/Article/details/gtfurfturt.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xuetiantiany.cn/Article/details/gtyahfjunh.html

Java: class Node { int v; Node next; }
来源：http://dali.sysykeji.top/Article/details/gtwydjyefh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenjidiqi.icu/Article/details/gtpzofzjtc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.bjfxy.top/Article/details/gtghjhgfvt.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tanke756.top/Article/details/gtfxrxapva.html

[N11] 二叉树中序遍历
来源：http://dali.yangfankeji.com/Article/details/gtpedfovhy.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.wangdashe.top/Article/details/gtszzjhhyv.html

PHP:  // 手写递归函数
来源：http://dali.shzxlz.cn/Article/details/gtqiekcpgs.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258888.top/Article/details/gtrhszxuat.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.snrcjt.cn/Article/details/gtxdeynycg.html

Java: // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gtysxxehtb.html

Go:   // 手写递归
来源：http://dali.jqgfzy.top/Article/details/gtrzjyijsk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.guowangkeji.top/Article/details/gtpbhhggjv.html

C#:   // 手写递归
来源：http://dali.zdqjudy.top/Article/details/gtcgyoswtp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhoulong.xyz/Article/details/gtylyhuodj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinqigufen.top/Article/details/gtsbgkoiaj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.pycfn.com/Article/details/gtynziqjjl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.meibo888.top/Article/details/gtsjdtjoem.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxinkj.top/Article/details/gtulpslads.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuetiantiany.cn/Article/details/gtvmdrujuy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.316326.xyz/Article/details/gtxvqaqdjo.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xylfe.cn/Article/details/gtmkhtlakb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.quarkkingdee.top/Article/details/gtfcxknkcx.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtnphawdch.html

O. 并发与异步
来源：http://dali.xinyue.icu/Article/details/gteivmxqwk.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtzmnqhpnq.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gtmyamfngc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yonumen.top/Article/details/gtgznxafwa.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.meibo888.top/Article/details/gtslebqvzk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinghuilouyu.cn/Article/details/gtxzkfrmqa.html

TS:   // 同 JS
来源：http://dali.jinghuilouyu.cn/Article/details/gtfshzwuip.html

Java: new Thread(() -> f()).start()
来源：http://dali.yanxiufei.cn/Article/details/gtcehvnonz.html

Go:   go f()
来源：http://dali.jqgufenzy.top/Article/details/gtyvxtanog.html

Ruby: Thread.new { f }
来源：http://dali.zhixingplan.top/Article/details/gtwowutkfb.html

C#:   Task.Run(() => F());
来源：http://dali.haohaochexian.top/Article/details/gtgpimugqn.html

[O02] 使用线程池
来源：http://dali.9152youxi.cn/Article/details/gtqftdjtjn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.guowangkeji.top/Article/details/gtyldorfha.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.guannengcc.top/Article/details/gtemgwishf.html

JS:   // worker_threads 线程池
来源：http://dali.hfpthk.cn/Article/details/gtskmivfjy.html

TS:   // worker_threads 线程池
来源：http://dali.quarkkingdee.top/Article/details/gtnjhaqese.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shuidangran.top/Article/details/gtexcwspto.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.dianchejie.cn/Article/details/gtiyxzgdax.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yongpay.top/Article/details/gtqxyojhbu.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.kuanghao11.cn/Article/details/gtojpjdtiu.html

[O03] 加锁保护共享数据
来源：http://dali.zhoulong.xyz/Article/details/gtpinyqsnc.html

Py:   with lock: shared += 1
来源：http://dali.yueranfly.top/Article/details/gtaguowlwt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhoulong.xyz/Article/details/gtgbqljarw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcnxzlntw.html

TS:   // 同 JS
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhqpdksv.html

Java: synchronized (this) { shared++; }
来源：http://dali.hfpthk.cn/Article/details/gthhhemdot.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hnqzz.top/Article/details/gttmezrhds.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hnqzz.top/Article/details/gtpvccmpfe.html

C#:   lock (gate) { shared++; }
来源：http://dali.sysykeji.top/Article/details/gtqfzmjhld.html

[O04] 定义异步函数并等待
来源：http://dali.yj202588.top/Article/details/gtvobwpdze.html

Py:   async def f():⏎    await g()
来源：http://dali.nwbrower.top/Article/details/gtfuxxqhyg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yonumen.top/Article/details/gtzgpkucir.html

JS:   async function f() { await g(); }
来源：http://dali.dashuyun.cn/Article/details/gtcbfviulz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yanxiufei.cn/Article/details/gtaenewgkn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhoulong.xyz/Article/details/gtncvxgkju.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.mhx1999.top/Article/details/gtwoghwjzr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.bjfxy.top/Article/details/gtbfpcjrwx.html

C#:   async Task F() { await G(); }
来源：http://dali.cashguo.top/Article/details/gtxckyynyn.html

[O05] 并发执行并等待全部完成
来源：http://dali.meibo888.top/Article/details/gtshpkemll.html

Py:   asyncio.gather(*tasks)
来源：http://dali.wangshuangyany.cn/Article/details/gtxvofdghh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shangyingyoupin.top/Article/details/gtcmqppfrm.html

JS:   await Promise.all(tasks)
来源：http://dali.xuetiantiany.cn/Article/details/gtpakxyipc.html

TS:   await Promise.all(tasks)
来源：http://dali.quarkkingdee.top/Article/details/gtrvspalxs.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hysaishi.cn/Article/details/gttplglbov.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ydzc1.top/Article/details/gttayowsci.html

Ruby: threads.map(&:join)
来源：http://dali.kuanghao11.cn/Article/details/gtwpsfsmou.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.feifeiyinyue.top/Article/details/gtqogstela.html

[O06] 使用进程池
来源：http://dali.ybcxt.top/Article/details/gtvfadrzhr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.daria6918.cn/Article/details/gtphkpigjp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlhykthyy.html

JS:   // child_process / cluster 模块
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyvpjtsus.html

TS:   // child_process / cluster 模块
来源：http://dali.meibo888.top/Article/details/gtekmozrbu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cucudq.cn/Article/details/gtsrclpdwk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cucudq.cn/Article/details/gtxrzmrlyx.html

Ruby: // fork 块
来源：http://dali.hammf.cn/Article/details/gttnkigkdi.html

C#:   Parallel.For
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdjetxpnt.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtrheplxpq.html

P. 常用工具函数
来源：http://dali.ydzc1.top/Article/details/gthntzsdpj.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtawojirbz.html

[P01] 生成 UUID
来源：http://dali.jinqigufen.top/Article/details/gtvmdymsze.html

Py:   str(uuid.uuid4())
来源：http://dali.ybcxt.top/Article/details/gtyknfixdg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xinyue.icu/Article/details/gtsxlwggmc.html

JS:   crypto.randomUUID()
来源：http://dali.hammf.cn/Article/details/gtywzdgccd.html

TS:   crypto.randomUUID()
来源：http://dali.nwbrower.top/Article/details/gtugxhfhpu.html

Java: UUID.randomUUID().toString()
来源：http://dali.yj202588.top/Article/details/gtnqgguogf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.wangdashe.top/Article/details/gtcglwfisj.html

Ruby: SecureRandom.uuid
来源：http://dali.sufxvd.cn/Article/details/gtjywgakvx.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cashguo.top/Article/details/gtyblpwcln.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yueranfly.top/Article/details/gtrhfomurw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhiwuduotai.top/Article/details/gtkvkorgwz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.c1oappe.top/Article/details/gtcinjxzrn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.quarkkingdee.top/Article/details/gtkslphuxc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinyuanbaomall.cn/Article/details/gteinbzutl.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.gotoacloud.top/Article/details/gtmcteemno.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hywenlv.cn/Article/details/gtdadhgefr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nanxuanxn.top/Article/details/gtwahmkqwi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xuetiantiany.cn/Article/details/gtmjfcduph.html

[P03] 生成短随机字符串
来源：http://dali.cdnleiting.top/Article/details/gtxiwnrede.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.havefunace.top/Article/details/gtzqysfyct.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.iojbl.cn/Article/details/gtufqgcdft.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tian-w.cn/Article/details/gtjldrjdup.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.bjfxy.top/Article/details/gttjuqiwil.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhixingplan.top/Article/details/gthvgbqzcq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.guannengcc.top/Article/details/gttsdurach.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hfpthk.cn/Article/details/gtavuyomtk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zdqjudy.top/Article/details/gtfpqvaajn.html

[P04] 求长度
来源：http://dali.aibaodan.cn/Article/details/gttfundsen.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.kuanghao11.cn/Article/details/gtwjptkvun.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gtcqnntmbo.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gogol.net.cn/Article/details/gtnmwnzuha.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pycfn.com/Article/details/gthaymvgdr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sweek.top/Article/details/gtkkfuaeaa.html

Go:   len(arr);  len(m)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbdeehshn.html

Ruby: x.length;  x.size
来源：http://dali.c1oappe.top/Article/details/gtdfcrujzy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.aibaodan.cn/Article/details/gtltaoqwla.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xziqi.cn/Article/details/gtppderaes.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ehwqpu.com/Article/details/gtulfdzeer.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sweek.top/Article/details/gtqqrklphx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.chenjidiqi.icu/Article/details/gtpoqfjnwu.html


<!-- 参考信息 -->