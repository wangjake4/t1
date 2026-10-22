代发 wailian999

[L07] 处理 HTTP 状态码
来源：http://dali.feifeiyinyue.top/Article/details/gtcayrzahw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nanxinkj.top/Article/details/gtslrobasd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.c1oappe.top/Article/details/gtklaoosrx.html

JS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangtech.top/Article/details/gtpizpygxw.html

TS:   resp.ok;  resp.status
来源：http://dali.hnxiangtu.top/Article/details/gttnlgprmx.html

Java: resp.statusCode()
来源：http://dali.shangyingyoupin.top/Article/details/gtnnmgutzg.html

Go:   resp.StatusCode
来源：http://dali.aibaodan.cn/Article/details/gtmqokbdkp.html

Ruby: resp.code.to_i
来源：http://dali.gzhubu.top/Article/details/gtgvkpkaoc.html

C#:   (int)resp.StatusCode
来源：http://dali.ywan-chungtsiang.top/Article/details/gtygysuuix.html

[L08] 并发请求多个地址
来源：http://dali.jianghu66.top/Article/details/gtunjrxija.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.dianchejie.cn/Article/details/gtincawbbu.html

PHP:  curl_multi_init() 系列
来源：http://dali.andypj.xyz/Article/details/gtccvuvqau.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.vqdsnc.cn/Article/details/gtwzzaxdsp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.redwolf501.top/Article/details/gtxasjcvxy.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nanxinkj.top/Article/details/gtgaumgcua.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shanyushiyangtech.top/Article/details/gtlmejclpx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gogol.net.cn/Article/details/gtjrxfrxmb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hysaishi.cn/Article/details/gtlyscaglv.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtnkzgsnwa.html

M. 命令行 / 进程 / 环境
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmuuicyon.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtptrbcppm.html

[M01] 读取命令行参数
来源：http://dali.jyoumei.cn/Article/details/gthxkohlwd.html

Py:   sys.argv[1:]
来源：http://dali.yj20258.top/Article/details/gtdodscorp.html

PHP:  $argv;  $argc;
来源：http://dali.ppjwa.cn/Article/details/gtnnlsegus.html

JS:   process.argv.slice(2)
来源：http://dali.pengpengdd.cyou/Article/details/gtjzgvpaxr.html

TS:   process.argv.slice(2)
来源：http://dali.316326.xyz/Article/details/gteywqgmef.html

Java: args 数组（main 方法参数）
来源：http://dali.yuxming.cn/Article/details/gtumatjmdc.html

Go:   os.Args[1:]
来源：http://dali.dianchejie.cn/Article/details/gtxwwsyukj.html

Ruby: ARGV
来源：http://dali.hongshengwenyu.top/Article/details/gtbtyniclw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hammf.cn/Article/details/gtbreixsse.html

[M02] 读取环境变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdzqzwwsp.html

Py:   os.environ.get("HOME")
来源：http://dali.0kj1m.cn/Article/details/gtlrlxswvq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zdqjudy.top/Article/details/gtvxotejxp.html

JS:   process.env.HOME
来源：http://dali.pengpengdd.cyou/Article/details/gtgadywbno.html

TS:   process.env.HOME
来源：http://dali.ydzc1.top/Article/details/gtiyjtvahf.html

Java: System.getenv("HOME")
来源：http://dali.sweek.top/Article/details/gthwyazoyk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xylfe.cn/Article/details/gtureqnyym.html

Ruby: ENV["HOME"]
来源：http://dali.yangfankeji.com/Article/details/gtoktdyaej.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.fzhhl.top/Article/details/gtbqnpfixj.html

[M03] 执行外部命令
来源：http://dali.haohaochexian.top/Article/details/gthuslytdl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcmkjwbam.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.aibaodan.cn/Article/details/gtjajujwaq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yangfankeji.com/Article/details/gtoulshcvi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.mhx1999.top/Article/details/gtloeofktb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ybcxt.top/Article/details/gtwnzycnvu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtssqvhhgv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhixingplan.top/Article/details/gtghhxswln.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinqigfzy.top/Article/details/gtikyqyrzy.html

[M04] 获取当前工作目录
来源：http://dali.c1oappe.top/Article/details/gtzhoihbds.html

Py:   os.getcwd()
来源：http://dali.ydzc1.top/Article/details/gtjoytsllm.html

PHP:  getcwd();
来源：http://dali.daxiang520.top/Article/details/gttsrnynbh.html

JS:   process.cwd()
来源：http://dali.yuxming.cn/Article/details/gtqebywqmu.html

TS:   process.cwd()
来源：http://dali.9152youxi.cn/Article/details/gtxlianjgm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhiwuduotai.top/Article/details/gtiwgbafqw.html

Go:   os.Getwd()
来源：http://dali.haohaochexian.top/Article/details/gthnahmccp.html

Ruby: Dir.pwd
来源：http://dali.shuidangran.top/Article/details/gtamkcrtmx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cqqwz.cn/Article/details/gtfozsludx.html

[M05] 设置退出码
来源：http://dali.gogol.net.cn/Article/details/gthetuljvm.html

Py:   sys.exit(1)
来源：http://dali.shuidangran.top/Article/details/gtkxyxnsve.html

PHP:  exit(1);
来源：http://dali.jinqigufen.top/Article/details/gtfhmbgyng.html

JS:   process.exit(1)
来源：http://dali.nwbrower.top/Article/details/gtzippebdh.html

TS:   process.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gttdvdyukv.html

Java: System.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gthsuxckzw.html

Go:   os.Exit(1)
来源：http://dali.aizwys.cn/Article/details/gtgwexspxj.html

Ruby: exit 1
来源：http://dali.pengpengdd.cyou/Article/details/gtfkwgpeaz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.daria6918.cn/Article/details/gtelfdrbbz.html

[M06] 向标准错误输出
来源：http://dali.daxiang520.top/Article/details/gtuvvvfqgn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.fzhhl.top/Article/details/gtdbmdctif.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yuxming.cn/Article/details/gtvguzmxfz.html

JS:   console.error("err")
来源：http://dali.jinqigufen.top/Article/details/gthwqxhsmt.html

TS:   console.error("err")
来源：http://dali.aizwys.cn/Article/details/gtuxhumkjx.html

Java: System.err.println("err")
来源：http://dali.ybcxt.top/Article/details/gtmgwvhffr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.chenjidiqi.icu/Article/details/gtfqjwsocw.html

Ruby: warn "err"
来源：http://dali.ivvv.top/Article/details/gtildigfrj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gtpqqkfoiu.html

[M07] 判断是否为主入口
来源：http://dali.hnxiangtu.top/Article/details/gtzykomkiw.html

Py:   if __name__ == "__main__":
来源：http://dali.fzhhl.top/Article/details/gtplctyvrm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.smart0.xyz/Article/details/gtasyorxlu.html

JS:   require.main === module
来源：http://dali.cheryme.top/Article/details/gthjmsjlxt.html

TS:   require.main === module
来源：http://dali.gotoacloud.top/Article/details/gthpsxdyex.html

Java: public static void main(String[] args)
来源：http://dali.xuanzx.com/Article/details/gtsilkqqko.html

Go:   func main()
来源：http://dali.yangfankeji.com/Article/details/gtvaqfnnep.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.smart0.xyz/Article/details/gtoxmwdubk.html

C#:   static void Main(string[] args)
来源：http://dali.hammf.cn/Article/details/gttjslhiak.html

[M08] 获取系统与运行时信息
来源：http://dali.gotoacloud.top/Article/details/gtwpndcnsz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.tianlin.xyz/Article/details/gtkrijsasu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.guannengcc.top/Article/details/gtllntkanr.html

JS:   process.platform;  process.version
来源：http://dali.daxiang520.top/Article/details/gtxoaqxnyu.html

TS:   process.platform;  process.version
来源：http://dali.zhengqikj.top/Article/details/gtvebkuele.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gtvrcokstk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sysykeji.top/Article/details/gtswnygxjs.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.mhx1999.top/Article/details/gtwddzbgyi.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.smart0.xyz/Article/details/gtneewfqic.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtrmqfaouy.html

N. 数据结构与算法
来源：http://dali.0kj1m.cn/Article/details/gtfdmcqgye.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gthyayrgpq.html

[N01] 二分查找（有序数组）
来源：http://dali.andypj.xyz/Article/details/gtgzehismq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtbqyxhbhk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinqigfzy.top/Article/details/gthkoatpsl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoooolvak.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwnxshkck.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtvenoakaj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cashguo.top/Article/details/gtnbmroppt.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj202588.top/Article/details/gtltnnssid.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yongpay.top/Article/details/gtiksvylpr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.pycfn.com/Article/details/gtftfzgyvj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.9152youxi.cn/Article/details/gtlbwnblsf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xziqi.cn/Article/details/gtwmstsaba.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhoulong.xyz/Article/details/gtrsnkycwl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jiagoushi.top/Article/details/gtpebrznae.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zdqjudy.top/Article/details/gtvlabuart.html

Go:   slices.Sort(arr)
来源：http://dali.svipenyu.cn/Article/details/gtlzajnaxl.html

Ruby: arr.sort
来源：http://dali.xuanzx.com/Article/details/gtntozakqz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.9152youxi.cn/Article/details/gtdlwwohmc.html

[N03] 快速排序（分治示例）
来源：http://dali.0kj1m.cn/Article/details/gtlerhgsbm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.fengsongda.top/Article/details/gtdxhcndul.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ydzc1.top/Article/details/gtslomgofk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xziqi.cn/Article/details/gtvvvixgtd.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuanzhike.top/Article/details/gteygxzttk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hongshengwenyu.top/Article/details/gtukedeppf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gaohongyu789.top/Article/details/gthcilygxu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xinyue.icu/Article/details/gtxuxltosk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yj202588.top/Article/details/gtkszaznct.html

[N04] 斐波那契数列
来源：http://dali.dianchejie.cn/Article/details/gtetgefklq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hfpthk.cn/Article/details/gtnfgwovtl.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.redwolf501.top/Article/details/gtoragyiwz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hywenlv.cn/Article/details/gtfejskabh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gaohongyu789.top/Article/details/gtjqggbqht.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gaohongyu789.top/Article/details/gtkourqmil.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhongyouzk.top/Article/details/gtxadgsayg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.svipenyu.cn/Article/details/gtkfqqsfat.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gtjgrnceiw.html

[N05] 最大公约数
来源：http://dali.jianghu66.top/Article/details/gtrmfsmigs.html

Py:   math.gcd(a, b)
来源：http://dali.c1oappe.top/Article/details/gtfubvhpyy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinqigufen.top/Article/details/gtxxfmxwiw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.birdmap.top/Article/details/gtbcgmuvjv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.vqdsnc.cn/Article/details/gtzktorfak.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cqqwz.cn/Article/details/gtdrhogsyq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yvedp.cn/Article/details/gtjegwepwj.html

Ruby: a.gcd(b)
来源：http://dali.pycfn.com/Article/details/gtpqknjodz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.daxiang520.top/Article/details/gtsdkdwtth.html

[N06] 判断回文字符串
来源：http://dali.jqgfzy.top/Article/details/gttwskhzab.html

Py:   s == s[::-1]
来源：http://dali.jiagoushi.top/Article/details/gtgjitatzl.html

PHP:  $s === strrev($s);
来源：http://dali.iojbl.cn/Article/details/gtjiaorzrh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gtwtebnquo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gtmmegyynp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhoulong.xyz/Article/details/gtzwgtgyph.html

Go:   // 双指针从两端比较
来源：http://dali.guannengcc.top/Article/details/gtlwbydhze.html

Ruby: s == s.reverse
来源：http://dali.sufxvd.cn/Article/details/gtofpqmcru.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hywenlv.cn/Article/details/gtqokbtyze.html

[N07] 两数之和（返回下标）
来源：http://dali.dashuyun.cn/Article/details/gtjyphohhp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hnxiangtu.top/Article/details/gtmeiovqpm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.pengpengdd.cyou/Article/details/gtupixuplp.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.wangdashe.top/Article/details/gtwiysgtuh.html

TS:   // 手写 Map<string, number>
来源：http://dali.hongshengwenyu.top/Article/details/gtpugturrr.html

Java: // 手写 HashMap
来源：http://dali.jlsjyb.cn/Article/details/gtvgxodhqq.html

Go:   // 手写 map[int]int
来源：http://dali.zdqjudy.top/Article/details/gtpurzdnhk.html

Ruby: // 手写 Hash
来源：http://dali.hysaishi.cn/Article/details/gtoxueyjge.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gogol.net.cn/Article/details/gtgflahwvn.html

[N08] 生成全排列
来源：http://dali.xylfe.cn/Article/details/gtxbdcnjxi.html

Py:   itertools.permutations(arr)
来源：http://dali.fzhhl.top/Article/details/gtuffwockq.html

PHP:  // 手写递归交换
来源：http://dali.xinyue.icu/Article/details/gtriplxvmu.html

JS:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gtxkveypzj.html

TS:   // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gtohklioju.html

Java: // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gttcawipzv.html

Go:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gtkqtntkog.html

Ruby: arr.permutation.to_a
来源：http://dali.xylfe.cn/Article/details/gtlfoardgu.html

C#:   // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gtvcpbekbx.html

[N09] 栈与队列
来源：http://dali.gogol.net.cn/Article/details/gtwbnmolod.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.fengsongda.top/Article/details/gtnjenxscr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.iojbl.cn/Article/details/gtryabmolb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yueranfly.top/Article/details/gtchiugovq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.mhx1999.top/Article/details/gtytamrfjm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yvedp.cn/Article/details/gtpmqxlevs.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yvedp.cn/Article/details/gtniwsyhgi.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hammf.cn/Article/details/gtsxmzsble.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenjidiqi.icu/Article/details/gtqgfmummb.html

[N10] 链表节点定义
来源：http://dali.sweek.top/Article/details/gtheeixomy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ivvv.top/Article/details/gtraxzvirz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.dashuyun.cn/Article/details/gtchqwizvv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinqigfzy.top/Article/details/gtbwhscfrz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.aizwys.cn/Article/details/gtjujhaxgp.html

Java: class Node { int v; Node next; }
来源：http://dali.cdnleiting.top/Article/details/gtukjfentr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.snrcjt.cn/Article/details/gttxcyssxb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.dashuyun.cn/Article/details/gtuhxjqlwc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhengqikj.top/Article/details/gtwxckkqng.html

[N11] 二叉树中序遍历
来源：http://dali.ehwqpu.com/Article/details/gtnlplamco.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jyoumei.cn/Article/details/gtcnsnawbe.html

PHP:  // 手写递归函数
来源：http://dali.jianghu66.top/Article/details/gtcxdhhyyb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gtlzqugrgm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.haohaochexian.top/Article/details/gtgwakyhea.html

Java: // 手写递归
来源：http://dali.xylfe.cn/Article/details/gthyffjziw.html

Go:   // 手写递归
来源：http://dali.yuxming.cn/Article/details/gtmjnrhdfb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xuanzx.com/Article/details/gttkgmyfnl.html

C#:   // 手写递归
来源：http://dali.zdqjudy.top/Article/details/gtuuyhxpgp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhiwuduotai.top/Article/details/gtdmzniidc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.sxryk.cn/Article/details/gtsgdsaell.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yueranfly.top/Article/details/gtqztqosrm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jlsjyb.cn/Article/details/gtpstqiuvo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jiagoushi.top/Article/details/gtvsodkdnd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.smart0.xyz/Article/details/gtzttctddp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yj20258.top/Article/details/gtjobszcou.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cdnleiting.top/Article/details/gtgwwgchet.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daxiang520.top/Article/details/gtdabvplcz.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtujlnxvht.html

O. 并发与异步
来源：http://dali.dianchejie.cn/Article/details/gtalekpvnk.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtrgwhrhfm.html

[O01] 启动一个线程
来源：http://dali.jlsjyb.cn/Article/details/gtqxotqzee.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xuanzx.com/Article/details/gtwanfiixa.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.haohaochexian.top/Article/details/gtratixnuh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.sufxvd.cn/Article/details/gtfhgksnjy.html

TS:   // 同 JS
来源：http://dali.meibo888.top/Article/details/gtgjtkcnsi.html

Java: new Thread(() -> f()).start()
来源：http://dali.aizwys.cn/Article/details/gtwzlsqlwi.html

Go:   go f()
来源：http://dali.hysaishi.cn/Article/details/gtzzontnxq.html

Ruby: Thread.new { f }
来源：http://dali.kuanghao11.cn/Article/details/gtbfxcetsf.html

C#:   Task.Run(() => F());
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsgeinbfu.html

[O02] 使用线程池
来源：http://dali.haohaochexian.top/Article/details/gtyrcafali.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.bjfxy.top/Article/details/gtkurezjqy.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.dianchejie.cn/Article/details/gtnsheehbl.html

JS:   // worker_threads 线程池
来源：http://dali.hnxiangtu.top/Article/details/gtvypmbcyt.html

TS:   // worker_threads 线程池
来源：http://dali.jyoumei.cn/Article/details/gthuebaqeq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jyoumei.cn/Article/details/gtcdegztle.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.snrcjt.cn/Article/details/gthcxqqlxg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgajsgavc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yvedp.cn/Article/details/gtmcanwsxh.html

[O03] 加锁保护共享数据
来源：http://dali.aibaodan.cn/Article/details/gtecfywubk.html

Py:   with lock: shared += 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtanieqour.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jinqigufen.top/Article/details/gtbujhmayt.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinqigfzy.top/Article/details/gtbnzzvfgb.html

TS:   // 同 JS
来源：http://dali.pengpengdd.cyou/Article/details/gtjodfrgiu.html

Java: synchronized (this) { shared++; }
来源：http://dali.yvedp.cn/Article/details/gtndtknsej.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtubiuknvi.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zycfv.cn/Article/details/gtfpdzgqhz.html

C#:   lock (gate) { shared++; }
来源：http://dali.sxryk.cn/Article/details/gtqcqtnhsf.html

[O04] 定义异步函数并等待
来源：http://dali.shanyushiyangtech.top/Article/details/gthfecgzwk.html

Py:   async def f():⏎    await g()
来源：http://dali.chenlongwang.top/Article/details/gtvptpdyuk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.andypj.xyz/Article/details/gtosmqnley.html

JS:   async function f() { await g(); }
来源：http://dali.sufxvd.cn/Article/details/gtmldnggzi.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqfvfltkz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.bjfxy.top/Article/details/gturqozvtp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinqigufen.top/Article/details/gtnhdcogeu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.316326.xyz/Article/details/gtxefjyavk.html

C#:   async Task F() { await G(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjmdaiyso.html

[O05] 并发执行并等待全部完成
来源：http://dali.hammf.cn/Article/details/gtwwllifli.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlkrolwty.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yongpay.top/Article/details/gtzmxbbefg.html

JS:   await Promise.all(tasks)
来源：http://dali.aibaodan.cn/Article/details/gtbjsvxrpf.html

TS:   await Promise.all(tasks)
来源：http://dali.hnqzz.top/Article/details/gtidglnqsk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hysaishi.cn/Article/details/gtnqneuuzv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.daxiang520.top/Article/details/gtyzyesckz.html

Ruby: threads.map(&:join)
来源：http://dali.meibo888.top/Article/details/gtfmykropw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gaohongyu789.top/Article/details/gtlfuhlptl.html

[O06] 使用进程池
来源：http://dali.jianghu66.top/Article/details/gtuoycpmqo.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.daxiang520.top/Article/details/gtupvroecq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhoulong.xyz/Article/details/gtrouqfpox.html

JS:   // child_process / cluster 模块
来源：http://dali.wangshuangyany.cn/Article/details/gtkbqrowyh.html

TS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpoywxsud.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhengqikj.top/Article/details/gtsavuersh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jyoumei.cn/Article/details/gtmboieqgv.html

Ruby: // fork 块
来源：http://dali.jiagoushi.top/Article/details/gtwilwvsnn.html

C#:   Parallel.For
来源：http://dali.cheryme.top/Article/details/gtolrrjezh.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtwesqumdb.html

P. 常用工具函数
来源：http://dali.meibo888.top/Article/details/gtngdmphdt.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtdlkmxmuq.html

[P01] 生成 UUID
来源：http://dali.shanyushiyangtech.top/Article/details/gtmtyfcbsn.html

Py:   str(uuid.uuid4())
来源：http://dali.andypj.xyz/Article/details/gtppqdziwn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xuetiantiany.cn/Article/details/gtxjerwlbc.html

JS:   crypto.randomUUID()
来源：http://dali.shangyingyoupin.top/Article/details/gtmamoxrpg.html

TS:   crypto.randomUUID()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxgjifjaf.html

Java: UUID.randomUUID().toString()
来源：http://dali.shangyingyoupin.top/Article/details/gtxintqyyc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hammf.cn/Article/details/gtficjntem.html

Ruby: SecureRandom.uuid
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvikrrzaz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.chenzaomai.com/Article/details/gtyxcfvybi.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cucudq.cn/Article/details/gtevsdkwym.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinqigfzy.top/Article/details/gtirctprly.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtpmnamrup.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.tianlin.xyz/Article/details/gtmkoqufih.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjpgybidu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sufxvd.cn/Article/details/gtzdterpky.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cashguo.top/Article/details/gtfkevnsxb.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jqgfzy.top/Article/details/gttzxyxceh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.daxiang520.top/Article/details/gtxqrrrxsn.html

[P03] 生成短随机字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyganjupn.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.pycfn.com/Article/details/gtvplmtfgp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xylfe.cn/Article/details/gtkajflfcz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttzxfucky.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwzkakqsq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yueranfly.top/Article/details/gtusruzjfd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shangyingyoupin.top/Article/details/gtiiedtnrk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shuidangran.top/Article/details/gtfjeneidb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhoulong.xyz/Article/details/gtrtpfccfm.html

[P04] 求长度
来源：http://dali.ehwqpu.com/Article/details/gtnhquraps.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cdnleiting.top/Article/details/gtgusmjcpd.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tanke756.top/Article/details/gtzxsrnzhl.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nwbrower.top/Article/details/gtitrwygim.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.0kj1m.cn/Article/details/gtxkjhrgdk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.tianlin.xyz/Article/details/gtkcpegohi.html

Go:   len(arr);  len(m)
来源：http://dali.fengsongda.top/Article/details/gtnpodthgb.html

Ruby: x.length;  x.size
来源：http://dali.gaohongyu789.top/Article/details/gtgwsfwhof.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yuanzhike.top/Article/details/gtvuaobjfw.html


<!-- 参考信息 -->