代发 wailian999

[L07] 处理 HTTP 状态码
来源：http://dali.fengsongda.top/Article/details/gtabrkkasp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cashguo.top/Article/details/gtxilgemcw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfeufgbtg.html

JS:   resp.ok;  resp.status
来源：http://dali.gzhubu.top/Article/details/gtglpthwcb.html

TS:   resp.ok;  resp.status
来源：http://dali.nanxuanxn.top/Article/details/gtchsadkbv.html

Java: resp.statusCode()
来源：http://dali.zycfv.cn/Article/details/gtanrztpgn.html

Go:   resp.StatusCode
来源：http://dali.zhixingplan.top/Article/details/gthrfyoobp.html

Ruby: resp.code.to_i
来源：http://dali.ydzc1.top/Article/details/gtwobmfwsb.html

C#:   (int)resp.StatusCode
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrgnqvdsx.html

[L08] 并发请求多个地址
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrpjzszjc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ehwqpu.com/Article/details/gtnuhjbffc.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbwdarjds.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfzeirwnw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cheryme.top/Article/details/gtlqaagpca.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xziqi.cn/Article/details/gtkukcvfcs.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.guowangkeji.top/Article/details/gtlknkcuqi.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yonumen.top/Article/details/gtmihohzct.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj20258.top/Article/details/gtmqiqmfrt.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtbskvaibm.html

M. 命令行 / 进程 / 环境
来源：http://dali.dashuyun.cn/Article/details/gtajlmkfgc.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtqecrhybv.html

[M01] 读取命令行参数
来源：http://dali.birdmap.top/Article/details/gtrrbgeuec.html

Py:   sys.argv[1:]
来源：http://dali.chenzaomai.com/Article/details/gtbpreraei.html

PHP:  $argv;  $argc;
来源：http://dali.aizwys.cn/Article/details/gttomtrktl.html

JS:   process.argv.slice(2)
来源：http://dali.yangfankeji.com/Article/details/gtdhdmhwmp.html

TS:   process.argv.slice(2)
来源：http://dali.ppjwa.cn/Article/details/gticpibxxx.html

Java: args 数组（main 方法参数）
来源：http://dali.gaohongyu789.top/Article/details/gtfdhwxudg.html

Go:   os.Args[1:]
来源：http://dali.yuanzhike.top/Article/details/gtacbqhlzk.html

Ruby: ARGV
来源：http://dali.yueranfly.top/Article/details/gthzgynjcx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cqqwz.cn/Article/details/gtsrzewwle.html

[M02] 读取环境变量
来源：http://dali.xuetiantiany.cn/Article/details/gtqffffrfi.html

Py:   os.environ.get("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gtqmddolzt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.dashuyun.cn/Article/details/gttddcpmcw.html

JS:   process.env.HOME
来源：http://dali.hfpthk.cn/Article/details/gtyzvwhcnz.html

TS:   process.env.HOME
来源：http://dali.svipenyu.cn/Article/details/gtndgqjhov.html

Java: System.getenv("HOME")
来源：http://dali.cdnleiting.top/Article/details/gtxggzonmb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenlongwang.top/Article/details/gtzpbbxsrh.html

Ruby: ENV["HOME"]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtciwazrpm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gtwrbtwytt.html

[M03] 执行外部命令
来源：http://dali.zhongyouzk.top/Article/details/gtmriuvgzj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yonumen.top/Article/details/gtrkscmlta.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmiqgbwox.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtbsytrzzq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cdnleiting.top/Article/details/gthzbbnkmq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ivvv.top/Article/details/gtdboczqae.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gaohongyu789.top/Article/details/gtwpjwnuyc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hywenlv.cn/Article/details/gtpzbmlnfb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.pengpengdd.cyou/Article/details/gtkefbjoef.html

[M04] 获取当前工作目录
来源：http://dali.nwbrower.top/Article/details/gtjwdvdbuy.html

Py:   os.getcwd()
来源：http://dali.shuidangran.top/Article/details/gtqfmrekyg.html

PHP:  getcwd();
来源：http://dali.cdnleiting.top/Article/details/gtoiskixoy.html

JS:   process.cwd()
来源：http://dali.xuetiantiany.cn/Article/details/gtvzmtdtbn.html

TS:   process.cwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjuecjouy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.haohaochexian.top/Article/details/gtcturpxln.html

Go:   os.Getwd()
来源：http://dali.ehwqpu.com/Article/details/gtomhjwdqb.html

Ruby: Dir.pwd
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcqixgktt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.tanke756.top/Article/details/gtgrnxbabe.html

[M05] 设置退出码
来源：http://dali.dashuyun.cn/Article/details/gtbezwwtyz.html

Py:   sys.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtoiebkxos.html

PHP:  exit(1);
来源：http://dali.hammf.cn/Article/details/gtrlfgpwza.html

JS:   process.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gtkmhbnwoc.html

TS:   process.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gtrlgtdufk.html

Java: System.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gtyuszoazk.html

Go:   os.Exit(1)
来源：http://dali.hnqzz.top/Article/details/gtqsjtcfje.html

Ruby: exit 1
来源：http://dali.xuetiantiany.cn/Article/details/gtpvqbsfrm.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yanxiufei.cn/Article/details/gtizxndukm.html

[M06] 向标准错误输出
来源：http://dali.hnqzz.top/Article/details/gtblmteowl.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cheryme.top/Article/details/gtqlsyyjph.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.chenzaomai.com/Article/details/gttcfeoits.html

JS:   console.error("err")
来源：http://dali.birdmap.top/Article/details/gtgocagsga.html

TS:   console.error("err")
来源：http://dali.aizwys.cn/Article/details/gtveuujyse.html

Java: System.err.println("err")
来源：http://dali.cheryme.top/Article/details/gtlytxuvuu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ydzc1.top/Article/details/gtocllvfpb.html

Ruby: warn "err"
来源：http://dali.shzxlz.cn/Article/details/gtovnfuxrf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.c1oappe.top/Article/details/gtysdoydjs.html

[M07] 判断是否为主入口
来源：http://dali.guowangkeji.top/Article/details/gtfpsphmfm.html

Py:   if __name__ == "__main__":
来源：http://dali.smart0.xyz/Article/details/gtffcfobkt.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.aizwys.cn/Article/details/gtemzzowdl.html

JS:   require.main === module
来源：http://dali.vqdsnc.cn/Article/details/gtkikjwwwa.html

TS:   require.main === module
来源：http://dali.9152youxi.cn/Article/details/gtvxjbshhb.html

Java: public static void main(String[] args)
来源：http://dali.zhixingplan.top/Article/details/gtsxllfxay.html

Go:   func main()
来源：http://dali.jinqigfzy.top/Article/details/gthkzdilyx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sufxvd.cn/Article/details/gtssjfdxdr.html

C#:   static void Main(string[] args)
来源：http://dali.yuxming.cn/Article/details/gtukhygifo.html

[M08] 获取系统与运行时信息
来源：http://dali.gaohongyu789.top/Article/details/gtttkwcwqh.html

Py:   platform.system();  platform.python_version()
来源：http://dali.quarkkingdee.top/Article/details/gtgeygxavd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hfpthk.cn/Article/details/gtrvyfxehk.html

JS:   process.platform;  process.version
来源：http://dali.iojbl.cn/Article/details/gtlowzvszf.html

TS:   process.platform;  process.version
来源：http://dali.yangfankeji.com/Article/details/gtgpzwoujr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ivvv.top/Article/details/gtkhejhkpv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hfpthk.cn/Article/details/gtokndtlgr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinqigfzy.top/Article/details/gtbxzumdkn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sysykeji.top/Article/details/gtkheabqeu.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtshvvnwit.html

N. 数据结构与算法
来源：http://dali.pengpengdd.cyou/Article/details/gtfudlmvqz.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtjgnixmue.html

[N01] 二分查找（有序数组）
来源：http://dali.xuanzx.com/Article/details/gtbcuxofdu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tanke756.top/Article/details/gtrrxhqxib.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shuidangran.top/Article/details/gtwothhsqp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gotoacloud.top/Article/details/gtvwgxvmdr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fengsongda.top/Article/details/gtkymirifa.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtilhrlwuu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtekqthcjo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.bjfxy.top/Article/details/gtvripnvht.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtjetzveak.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jqgufenzy.top/Article/details/gtrilzlqjm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dashuyun.cn/Article/details/gtxwaggwmj.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.fzhhl.top/Article/details/gtyldphqul.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenzaomai.com/Article/details/gtvwwueqwy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuxming.cn/Article/details/gtmgvuhqkz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqtgjjyos.html

Go:   slices.Sort(arr)
来源：http://dali.yuxming.cn/Article/details/gtzojkiuhv.html

Ruby: arr.sort
来源：http://dali.xinyue.icu/Article/details/gtjhexsgyi.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.tian-w.cn/Article/details/gtdcuzfwdd.html

[N03] 快速排序（分治示例）
来源：http://dali.redwolf501.top/Article/details/gtbnzulzoi.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.wangshuangyany.cn/Article/details/gtjuayzacj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gotoacloud.top/Article/details/gtlrfgnmuw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jiagoushi.top/Article/details/gtqlwiohkj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hongshengwenyu.top/Article/details/gthapcxlen.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.9152youxi.cn/Article/details/gtnletkwxu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.birdmap.top/Article/details/gtvpdwpvuz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sufxvd.cn/Article/details/gtulgtxpwl.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sysykeji.top/Article/details/gtmerihaln.html

[N04] 斐波那契数列
来源：http://dali.xuetiantiany.cn/Article/details/gtszottgww.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.andypj.xyz/Article/details/gtacgsvray.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.aibaodan.cn/Article/details/gtkachppvp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gttiyqoebl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxuanxn.top/Article/details/gtljglktkz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cqqwz.cn/Article/details/gtiuawvtun.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.wangdashe.top/Article/details/gtbrlcblsk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jlsjyb.cn/Article/details/gtkphrjnwa.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shzxlz.cn/Article/details/gtugkhffkm.html

[N05] 最大公约数
来源：http://dali.meibo888.top/Article/details/gtypockhth.html

Py:   math.gcd(a, b)
来源：http://dali.sxryk.cn/Article/details/gtpqfoilwh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yonumen.top/Article/details/gtrhupswrs.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxuanxn.top/Article/details/gttglmzyoo.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuanzhike.top/Article/details/gtympeejyx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.aibaodan.cn/Article/details/gtyyotseod.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ydzc1.top/Article/details/gtufrfglyy.html

Ruby: a.gcd(b)
来源：http://dali.ehwqpu.com/Article/details/gtgekzzjfy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkhzptuqp.html

[N06] 判断回文字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzvxsvwqe.html

Py:   s == s[::-1]
来源：http://dali.zhengqikj.top/Article/details/gtxysqpazz.html

PHP:  $s === strrev($s);
来源：http://dali.hnqzz.top/Article/details/gtqupyntbd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbjeaksim.html

TS:   s === [...s].reverse().join("")
来源：http://dali.feifeiyinyue.top/Article/details/gtapbpezyi.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.wangshuangyany.cn/Article/details/gtwyudxnkv.html

Go:   // 双指针从两端比较
来源：http://dali.smart0.xyz/Article/details/gthgnvgyxl.html

Ruby: s == s.reverse
来源：http://dali.ivvv.top/Article/details/gtsvaqfwxb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinghuilouyu.cn/Article/details/gtvmqeaspp.html

[N07] 两数之和（返回下标）
来源：http://dali.daria6918.cn/Article/details/gtaogftqxh.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.fzhhl.top/Article/details/gtqqxmhyll.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.birdmap.top/Article/details/gtlinhcqdc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdyzqppin.html

TS:   // 手写 Map<string, number>
来源：http://dali.wangdashe.top/Article/details/gtqyebqoow.html

Java: // 手写 HashMap
来源：http://dali.9152youxi.cn/Article/details/gtcmzzngzi.html

Go:   // 手写 map[int]int
来源：http://dali.ybcxt.top/Article/details/gtcrrjrxto.html

Ruby: // 手写 Hash
来源：http://dali.jqgufenzy.top/Article/details/gtjfeexfyl.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.chenlongwang.top/Article/details/gtqmwgnytl.html

[N08] 生成全排列
来源：http://dali.yueranfly.top/Article/details/gtyinjnkls.html

Py:   itertools.permutations(arr)
来源：http://dali.zdqjudy.top/Article/details/gtxrthtbsi.html

PHP:  // 手写递归交换
来源：http://dali.jinqigufen.top/Article/details/gtptnmzxia.html

JS:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtwmpqgcho.html

TS:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gthqzqypbj.html

Java: // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gtdfoorzsz.html

Go:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gtsmgvqeye.html

Ruby: arr.permutation.to_a
来源：http://dali.fengsongda.top/Article/details/gthbzxkogc.html

C#:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gtkxpyswvj.html

[N09] 栈与队列
来源：http://dali.yj20258888.top/Article/details/gtyxsclxlx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zycfv.cn/Article/details/gthrlbtiid.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.daria6918.cn/Article/details/gtepenjtaq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtbgkirkyo.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cucudq.cn/Article/details/gtizwegaxm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jlsjyb.cn/Article/details/gtolctrlad.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.tian-w.cn/Article/details/gtqmlrwnqp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.snrcjt.cn/Article/details/gtanrtgbkc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.tanke756.top/Article/details/gtulhhiprb.html

[N10] 链表节点定义
来源：http://dali.cqqwz.cn/Article/details/gtyzmcrjgy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.316326.xyz/Article/details/gtmrguuekn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jianghu66.top/Article/details/gtewubpcyv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.redwolf501.top/Article/details/gtjifdoopy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.nanxuanxn.top/Article/details/gtatmbrdhf.html

Java: class Node { int v; Node next; }
来源：http://dali.zycfv.cn/Article/details/gtkyrnrsoj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsqcortvl.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zdqjudy.top/Article/details/gtlhlwfbcg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.wangdashe.top/Article/details/gtylbhepqo.html

[N11] 二叉树中序遍历
来源：http://dali.zhengqikj.top/Article/details/gtgempimby.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jqgfzy.top/Article/details/gtfvfejzvz.html

PHP:  // 手写递归函数
来源：http://dali.ydzc1.top/Article/details/gtwypolxyj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ppjwa.cn/Article/details/gtjdaampln.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.c1oappe.top/Article/details/gthyllfwhs.html

Java: // 手写递归
来源：http://dali.svipenyu.cn/Article/details/gtcuqcwgss.html

Go:   // 手写递归
来源：http://dali.redwolf501.top/Article/details/gtcsgsoxof.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hongshengwenyu.top/Article/details/gtpkgufuqm.html

C#:   // 手写递归
来源：http://dali.jiagoushi.top/Article/details/gttviiqgtm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yonumen.top/Article/details/gtntschbap.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhengqikj.top/Article/details/gtdbiywqdr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhoulong.xyz/Article/details/gtqdqsyjvw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.316326.xyz/Article/details/gtlatpxkoi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ehwqpu.com/Article/details/gtmqlperpm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgfzy.top/Article/details/gtbsmprrgw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.snrcjt.cn/Article/details/gtpjndwkmi.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sufxvd.cn/Article/details/gtijhxkdad.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hywenlv.cn/Article/details/gtlxkpmxfg.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtglmaslbd.html

O. 并发与异步
来源：http://dali.nanxuanxn.top/Article/details/gtecdebigl.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtrmtdvrhh.html

[O01] 启动一个线程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmbrpjhf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sufxvd.cn/Article/details/gtujmbwgcn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.snrcjt.cn/Article/details/gtwjslpbeo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hnxiangtu.top/Article/details/gtvlnxvzyf.html

TS:   // 同 JS
来源：http://dali.ppjwa.cn/Article/details/gtvagxpnoa.html

Java: new Thread(() -> f()).start()
来源：http://dali.yuanzhike.top/Article/details/gtifkzygtx.html

Go:   go f()
来源：http://dali.jyoumei.cn/Article/details/gtbzvfdoyf.html

Ruby: Thread.new { f }
来源：http://dali.yuanzhike.top/Article/details/gtupeyrmdh.html

C#:   Task.Run(() => F());
来源：http://dali.shanyushiyangkeji.top/Article/details/gtatfxntqp.html

[O02] 使用线程池
来源：http://dali.sysykeji.top/Article/details/gtnbpytywx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtilgrxvvu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnftyknlz.html

JS:   // worker_threads 线程池
来源：http://dali.guowangkeji.top/Article/details/gtcsnsstky.html

TS:   // worker_threads 线程池
来源：http://dali.mhx1999.top/Article/details/gtzudecuqg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.dashuyun.cn/Article/details/gtzshrwqqr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ppjwa.cn/Article/details/gtywstrbcl.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ehwqpu.com/Article/details/gttzfjemkz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yonumen.top/Article/details/gtylzectcy.html

[O03] 加锁保护共享数据
来源：http://dali.yj202588.top/Article/details/gtvrffwwzl.html

Py:   with lock: shared += 1
来源：http://dali.yj202588.top/Article/details/gtjaenpdzk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shanyushiyangtech.top/Article/details/gtknscdacf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yj202588.top/Article/details/gtgmgpxbzq.html

TS:   // 同 JS
来源：http://dali.snrcjt.cn/Article/details/gtrnznozpp.html

Java: synchronized (this) { shared++; }
来源：http://dali.ppjwa.cn/Article/details/gtfnmmjqmi.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.wangshuangyany.cn/Article/details/gtycbtblce.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhongyouzk.top/Article/details/gtfupsbopn.html

C#:   lock (gate) { shared++; }
来源：http://dali.hywenlv.cn/Article/details/gtsaywqgde.html

[O04] 定义异步函数并等待
来源：http://dali.sufxvd.cn/Article/details/gtwltfrrld.html

Py:   async def f():⏎    await g()
来源：http://dali.jqgufenzy.top/Article/details/gtcxoonyqu.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.nanxuanxn.top/Article/details/gtdybzuebb.html

JS:   async function f() { await g(); }
来源：http://dali.nanxinkj.top/Article/details/gtrekbnuqn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jyoumei.cn/Article/details/gtfjvmjpxw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yuanzhike.top/Article/details/gtzmzkxsnw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.kuanghao11.cn/Article/details/gtngvirbns.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.meibo888.top/Article/details/gtyoasrsby.html

C#:   async Task F() { await G(); }
来源：http://dali.pycfn.com/Article/details/gtqpekgwag.html

[O05] 并发执行并等待全部完成
来源：http://dali.chenjidiqi.icu/Article/details/gtefzppgln.html

Py:   asyncio.gather(*tasks)
来源：http://dali.c1oappe.top/Article/details/gtrichvpox.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jlsjyb.cn/Article/details/gttxldkjuq.html

JS:   await Promise.all(tasks)
来源：http://dali.yj202588.top/Article/details/gtvimhgqai.html

TS:   await Promise.all(tasks)
来源：http://dali.nwbrower.top/Article/details/gtpkuwdgjp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.vqdsnc.cn/Article/details/gtcxwnvrbl.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ehwqpu.com/Article/details/gtytayqxwg.html

Ruby: threads.map(&:join)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvmghqlbg.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yuxming.cn/Article/details/gtpttbuwcm.html

[O06] 使用进程池
来源：http://dali.jqgfzy.top/Article/details/gtzbpxhjxo.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xuetiantiany.cn/Article/details/gtxfzgfzqk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.aibaodan.cn/Article/details/gtavjqifdk.html

JS:   // child_process / cluster 模块
来源：http://dali.pycfn.com/Article/details/gtadzegpgg.html

TS:   // child_process / cluster 模块
来源：http://dali.nanxuanxn.top/Article/details/gtsnjsdyyw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmsqvyulo.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuckwcawx.html

Ruby: // fork 块
来源：http://dali.yuanzhike.top/Article/details/gtoxyeanmf.html

C#:   Parallel.For
来源：http://dali.chenjidiqi.icu/Article/details/gthacijisf.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtineilsnt.html

P. 常用工具函数
来源：http://dali.xziqi.cn/Article/details/gthfchhiyz.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtovfywjsm.html

[P01] 生成 UUID
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnbqjkssm.html

Py:   str(uuid.uuid4())
来源：http://dali.c1oappe.top/Article/details/gtnsfoizrf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cashguo.top/Article/details/gtzxnioahx.html

JS:   crypto.randomUUID()
来源：http://dali.ivvv.top/Article/details/gtlweovunj.html

TS:   crypto.randomUUID()
来源：http://dali.ppjwa.cn/Article/details/gthkktxmsc.html

Java: UUID.randomUUID().toString()
来源：http://dali.mhx1999.top/Article/details/gtcyimcudj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.svipenyu.cn/Article/details/gtaaaxtxkz.html

Ruby: SecureRandom.uuid
来源：http://dali.xinyue.icu/Article/details/gtvebfieab.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cucudq.cn/Article/details/gtzcppvryp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.dashuyun.cn/Article/details/gttuhwxlfr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sysykeji.top/Article/details/gtulnkxbsk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jqgufenzy.top/Article/details/gtgyzohcxo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlrqoyain.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sxryk.cn/Article/details/gtorxunoou.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jlsjyb.cn/Article/details/gtchknhoyq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhoulong.xyz/Article/details/gtzqiewdiq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hnqzz.top/Article/details/gtcgmdeyjj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.tian-w.cn/Article/details/gtkvkslonk.html

[P03] 生成短随机字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzhyvjylg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hysaishi.cn/Article/details/gtlikrtzxc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.nanxinkj.top/Article/details/gtnewvjjwm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.andypj.xyz/Article/details/gttbhdrxzj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhongyouzk.top/Article/details/gtocewyrzo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jqgufenzy.top/Article/details/gtsbnqgqpo.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.316326.xyz/Article/details/gtrzjiagjq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.snrcjt.cn/Article/details/gtyqtqucbk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shzxlz.cn/Article/details/gtuwviaoql.html

[P04] 求长度
来源：http://dali.sxryk.cn/Article/details/gtyacucyow.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.9152youxi.cn/Article/details/gtmylmddku.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gttoedgvqs.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ivvv.top/Article/details/gtubbmjyvd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhengqikj.top/Article/details/gtyryygftq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hnqzz.top/Article/details/gtibxsohfb.html

Go:   len(arr);  len(m)
来源：http://dali.sweek.top/Article/details/gtmcztwyrh.html

Ruby: x.length;  x.size
来源：http://dali.haohaochexian.top/Article/details/gtruydufbr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinghuilouyu.cn/Article/details/gtutkbqpvp.html


<!-- 参考信息 -->