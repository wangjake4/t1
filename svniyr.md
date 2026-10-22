代发 wailian999

Py:   resp.json()
来源：http://dali.gzhubu.top/Article/details/gtfjdwlaei.html

PHP:  json_decode($body, true);
来源：http://dali.mhx1999.top/Article/details/gtdavtcmbn.html

JS:   await resp.json()
来源：http://dali.jinqigufen.top/Article/details/gtascaikuo.html

TS:   await resp.json()
来源：http://dali.yueranfly.top/Article/details/gtltezdtgp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yongpay.top/Article/details/gtshyhcdux.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.chenjidiqi.icu/Article/details/gtthykguex.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jqgufenzy.top/Article/details/gtojjwnanx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yonumen.top/Article/details/gtvlvkhvne.html

[L07] 处理 HTTP 状态码
来源：http://dali.gotoacloud.top/Article/details/gtbbljzwfe.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.c1oappe.top/Article/details/gtjnfkrsyn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gtekobfqae.html

JS:   resp.ok;  resp.status
来源：http://dali.xylfe.cn/Article/details/gtzfzcimeq.html

TS:   resp.ok;  resp.status
来源：http://dali.shzxlz.cn/Article/details/gtpzqcjijd.html

Java: resp.statusCode()
来源：http://dali.xinyue.icu/Article/details/gteplvshfl.html

Go:   resp.StatusCode
来源：http://dali.jinqigfzy.top/Article/details/gtloxxmssy.html

Ruby: resp.code.to_i
来源：http://dali.xuanzx.com/Article/details/gtovhustih.html

C#:   (int)resp.StatusCode
来源：http://dali.haohaochexian.top/Article/details/gtmzgwswiv.html

[L08] 并发请求多个地址
来源：http://dali.svipenyu.cn/Article/details/gtlzigwdbx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.daxiang520.top/Article/details/gteembbvsq.html

PHP:  curl_multi_init() 系列
来源：http://dali.gogol.net.cn/Article/details/gtyvqbpgpq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gtpigtajus.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zdqjudy.top/Article/details/gtartgytxa.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.dashuyun.cn/Article/details/gtqfvecwat.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinqigufen.top/Article/details/gtpiypluyu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xylfe.cn/Article/details/gtweagjmbr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yueranfly.top/Article/details/gtabqrowtg.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gthbmnkajg.html

M. 命令行 / 进程 / 环境
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgwjqhsbl.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtfditnspu.html

[M01] 读取命令行参数
来源：http://dali.meibo888.top/Article/details/gthdzsdubj.html

Py:   sys.argv[1:]
来源：http://dali.aizwys.cn/Article/details/gtzznonvcx.html

PHP:  $argv;  $argc;
来源：http://dali.0kj1m.cn/Article/details/gtislwhfxk.html

JS:   process.argv.slice(2)
来源：http://dali.tian-w.cn/Article/details/gtrrjfbaej.html

TS:   process.argv.slice(2)
来源：http://dali.cqqwz.cn/Article/details/gtzolqveav.html

Java: args 数组（main 方法参数）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcpqttchp.html

Go:   os.Args[1:]
来源：http://dali.meibo888.top/Article/details/gtraojtrxq.html

Ruby: ARGV
来源：http://dali.hnqzz.top/Article/details/gthhpftwyr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zdqjudy.top/Article/details/gtjmvodnwl.html

[M02] 读取环境变量
来源：http://dali.zhiwuduotai.top/Article/details/gtzmrwqvdb.html

Py:   os.environ.get("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gtfxxuglav.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tianlin.xyz/Article/details/gtspoebwxs.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gtuchirdhn.html

TS:   process.env.HOME
来源：http://dali.xinyue.icu/Article/details/gtuhgvcjbx.html

Java: System.getenv("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gtkgclcztw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jqgfzy.top/Article/details/gtrfluoafl.html

Ruby: ENV["HOME"]
来源：http://dali.0kj1m.cn/Article/details/gtmekexwft.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.aibaodan.cn/Article/details/gtqilbyrcm.html

[M03] 执行外部命令
来源：http://dali.shangyingyoupin.top/Article/details/gtytrstnmm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.kuanghao11.cn/Article/details/gtzizhqezl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cdnleiting.top/Article/details/gtfjzsszex.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenjidiqi.icu/Article/details/gthdcfssjv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yongpay.top/Article/details/gtbtlarcve.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.9152youxi.cn/Article/details/gtbwwmibjf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xziqi.cn/Article/details/gtmkyyzlmn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhiwuduotai.top/Article/details/gtchnromuv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.0kj1m.cn/Article/details/gtsoofkngv.html

[M04] 获取当前工作目录
来源：http://dali.haohaochexian.top/Article/details/gtslncbtkc.html

Py:   os.getcwd()
来源：http://dali.yj202588.top/Article/details/gtmabeahft.html

PHP:  getcwd();
来源：http://dali.hammf.cn/Article/details/gtbpzspvpm.html

JS:   process.cwd()
来源：http://dali.9152youxi.cn/Article/details/gtaddcpqky.html

TS:   process.cwd()
来源：http://dali.tianlin.xyz/Article/details/gtthijdhun.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.pengpengdd.cyou/Article/details/gtygemkehr.html

Go:   os.Getwd()
来源：http://dali.jyoumei.cn/Article/details/gtzcoyiekn.html

Ruby: Dir.pwd
来源：http://dali.kuanghao11.cn/Article/details/gtnyuokfkd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shanyushiyangtech.top/Article/details/gtrvpufdds.html

[M05] 设置退出码
来源：http://dali.feifeiyinyue.top/Article/details/gtsvjzrzbl.html

Py:   sys.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtprixxylo.html

PHP:  exit(1);
来源：http://dali.hnxiangtu.top/Article/details/gthnldrxxv.html

JS:   process.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gtkshmvazm.html

TS:   process.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gtdodgyofj.html

Java: System.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gtbcejxqle.html

Go:   os.Exit(1)
来源：http://dali.wangdashe.top/Article/details/gtzvyggojw.html

Ruby: exit 1
来源：http://dali.hongshengwenyu.top/Article/details/gtketbrcjx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.fzhhl.top/Article/details/gtbibjravz.html

[M06] 向标准错误输出
来源：http://dali.nwbrower.top/Article/details/gtyhjbghug.html

Py:   print("err", file=sys.stderr)
来源：http://dali.tanke756.top/Article/details/gthkobwobg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinqigufen.top/Article/details/gtjgwcvxnw.html

JS:   console.error("err")
来源：http://dali.cucudq.cn/Article/details/gtrmkpqoxg.html

TS:   console.error("err")
来源：http://dali.sxryk.cn/Article/details/gtqaikpagg.html

Java: System.err.println("err")
来源：http://dali.cheryme.top/Article/details/gtqsjgtuky.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.c1oappe.top/Article/details/gtkzbrogco.html

Ruby: warn "err"
来源：http://dali.guowangkeji.top/Article/details/gtyxwjpwly.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yuxming.cn/Article/details/gtstuthjvl.html

[M07] 判断是否为主入口
来源：http://dali.ybcxt.top/Article/details/gtfwhnmzrv.html

Py:   if __name__ == "__main__":
来源：http://dali.jqgfzy.top/Article/details/gtaxqtkppr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.316326.xyz/Article/details/gtmgmoapar.html

JS:   require.main === module
来源：http://dali.aibaodan.cn/Article/details/gtjouvlhqd.html

TS:   require.main === module
来源：http://dali.xuanzx.com/Article/details/gtdzyxgyez.html

Java: public static void main(String[] args)
来源：http://dali.zhongyouzk.top/Article/details/gtaqezdspi.html

Go:   func main()
来源：http://dali.smart0.xyz/Article/details/gtpjtvlvip.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuembcvnx.html

C#:   static void Main(string[] args)
来源：http://dali.yvedp.cn/Article/details/gtlfvqvxtv.html

[M08] 获取系统与运行时信息
来源：http://dali.dashuyun.cn/Article/details/gtghfepiip.html

Py:   platform.system();  platform.python_version()
来源：http://dali.chenlongwang.top/Article/details/gtqcbltzmo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.andypj.xyz/Article/details/gtddvmgyhf.html

JS:   process.platform;  process.version
来源：http://dali.yangfankeji.com/Article/details/gtzxmmhlon.html

TS:   process.platform;  process.version
来源：http://dali.chenlongwang.top/Article/details/gtawaaawlw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.haohaochexian.top/Article/details/gtdbruvfqe.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yueranfly.top/Article/details/gtcaoycrpw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gaohongyu789.top/Article/details/gthflynrfx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hnqzz.top/Article/details/gtvlfybmok.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtrysltglb.html

N. 数据结构与算法
来源：http://dali.nwbrower.top/Article/details/gtqdgrbajq.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtqsgiglmx.html

[N01] 二分查找（有序数组）
来源：http://dali.xuetiantiany.cn/Article/details/gtxvskxlrw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtbzypfuhd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthwhrpbpf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dashuyun.cn/Article/details/gtqmtdemst.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xziqi.cn/Article/details/gtpgxnxxoi.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gtovwmknfu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtirivssvc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xinyue.icu/Article/details/gtvsqrvxdr.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtcwldceep.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yj20258888.top/Article/details/gtrwephgas.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.quarkkingdee.top/Article/details/gtlqrnzxho.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinqigufen.top/Article/details/gtgguknbrc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.haohaochexian.top/Article/details/gtylkqqrcb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jyoumei.cn/Article/details/gtunnickrn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xuetiantiany.cn/Article/details/gtgxhpqfmo.html

Go:   slices.Sort(arr)
来源：http://dali.iojbl.cn/Article/details/gtrvxlffew.html

Ruby: arr.sort
来源：http://dali.jlsjyb.cn/Article/details/gtrjknbjsg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.fzhhl.top/Article/details/gtvpfsuozu.html

[N03] 快速排序（分治示例）
来源：http://dali.havefunace.top/Article/details/gtgkijrojh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.havefunace.top/Article/details/gturityfpx.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cashguo.top/Article/details/gtyrzjmjul.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.316326.xyz/Article/details/gtxvhwlqtd.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuxming.cn/Article/details/gtsfetesuc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xylfe.cn/Article/details/gtygbatcbc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gogol.net.cn/Article/details/gtoyyjkgkf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.0kj1m.cn/Article/details/gtawpfzete.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbrqcnugg.html

[N04] 斐波那契数列
来源：http://dali.jlsjyb.cn/Article/details/gtudpzodfj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yj202588.top/Article/details/gtsdzqnsnt.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinqigufen.top/Article/details/gtfvglbosl.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gtaqfpntrx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gtdgchtrbe.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinqigufen.top/Article/details/gtuhyhtmwd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yonumen.top/Article/details/gthaphlmlo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yuanzhike.top/Article/details/gtbjxtgixu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yongpay.top/Article/details/gtgljksmti.html

[N05] 最大公约数
来源：http://dali.0kj1m.cn/Article/details/gtgpfpgcln.html

Py:   math.gcd(a, b)
来源：http://dali.nanxuanxn.top/Article/details/gtskvowzhu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ybcxt.top/Article/details/gtjsigidsk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuetiantiany.cn/Article/details/gtdiwacbqo.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.0kj1m.cn/Article/details/gtdfjeturh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yanxiufei.cn/Article/details/gtoyfebehn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.daxiang520.top/Article/details/gtbgyzuqmw.html

Ruby: a.gcd(b)
来源：http://dali.shzxlz.cn/Article/details/gtxsyifrpk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ybcxt.top/Article/details/gtgmkpyoit.html

[N06] 判断回文字符串
来源：http://dali.xylfe.cn/Article/details/gtowmncflm.html

Py:   s == s[::-1]
来源：http://dali.zycfv.cn/Article/details/gtoyzlblbc.html

PHP:  $s === strrev($s);
来源：http://dali.shuidangran.top/Article/details/gtdqfvolsn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gtzeovdbtp.html

TS:   s === [...s].reverse().join("")
来源：http://dali.daxiang520.top/Article/details/gtsrwacrnh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xuetiantiany.cn/Article/details/gthsvhuaui.html

Go:   // 双指针从两端比较
来源：http://dali.cqqwz.cn/Article/details/gteonufcbm.html

Ruby: s == s.reverse
来源：http://dali.nwbrower.top/Article/details/gthzcqogab.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.pengpengdd.cyou/Article/details/gtnrfdjvwb.html

[N07] 两数之和（返回下标）
来源：http://dali.quarkkingdee.top/Article/details/gttakwnkgl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.iojbl.cn/Article/details/gtukhpolxy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xylfe.cn/Article/details/gtzcoaxzha.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shangyingyoupin.top/Article/details/gtkrbvdbtr.html

TS:   // 手写 Map<string, number>
来源：http://dali.cdnleiting.top/Article/details/gtwxmpuomz.html

Java: // 手写 HashMap
来源：http://dali.zhongyouzk.top/Article/details/gtscwvzclh.html

Go:   // 手写 map[int]int
来源：http://dali.yueranfly.top/Article/details/gtlervwdfe.html

Ruby: // 手写 Hash
来源：http://dali.c1oappe.top/Article/details/gtatbrlfem.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jiagoushi.top/Article/details/gtotepzzbs.html

[N08] 生成全排列
来源：http://dali.jinyuanbaomall.cn/Article/details/gttcqmwexf.html

Py:   itertools.permutations(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtdmtvqzfa.html

PHP:  // 手写递归交换
来源：http://dali.jqgufenzy.top/Article/details/gtybqxjawc.html

JS:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gtznmznhuf.html

TS:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gtyuxuwqzi.html

Java: // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gtlcudasbs.html

Go:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtsabjewka.html

Ruby: arr.permutation.to_a
来源：http://dali.aizwys.cn/Article/details/gtvmwtcvqe.html

C#:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gtwhfftyis.html

[N09] 栈与队列
来源：http://dali.shangyingyoupin.top/Article/details/gtofsgovcr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.chenlongwang.top/Article/details/gtiblosujg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.mhx1999.top/Article/details/gtzuefesth.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.pycfn.com/Article/details/gtcvfevuil.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwdgkgmvh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xinyue.icu/Article/details/gtynxzhkjs.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ppjwa.cn/Article/details/gtkgfmviaa.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.bjfxy.top/Article/details/gtbdjqzbpi.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ybcxt.top/Article/details/gtijfoazvs.html

[N10] 链表节点定义
来源：http://dali.316326.xyz/Article/details/gtlsgmaysc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.birdmap.top/Article/details/gteuszitga.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhengqikj.top/Article/details/gtseckkmlm.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.havefunace.top/Article/details/gtiqonphxj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.nwbrower.top/Article/details/gtlrxucliw.html

Java: class Node { int v; Node next; }
来源：http://dali.yj20258888.top/Article/details/gtwolxljuf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yangfankeji.com/Article/details/gthtvlljyz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ehwqpu.com/Article/details/gtsboydrmv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhongyouzk.top/Article/details/gtwtcwtkfe.html

[N11] 二叉树中序遍历
来源：http://dali.yangfankeji.com/Article/details/gtvpdkugmn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jianghu66.top/Article/details/gtddrzjpuh.html

PHP:  // 手写递归函数
来源：http://dali.ppjwa.cn/Article/details/gtklwkxmkh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.bjfxy.top/Article/details/gtziknfsyj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jiagoushi.top/Article/details/gtijawhuqz.html

Java: // 手写递归
来源：http://dali.hammf.cn/Article/details/gtmuuzkvuj.html

Go:   // 手写递归
来源：http://dali.zycfv.cn/Article/details/gtamptdzae.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hywenlv.cn/Article/details/gtktsqfndg.html

C#:   // 手写递归
来源：http://dali.tianlin.xyz/Article/details/gtrrpjpnsu.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yuxming.cn/Article/details/gtvhdsxifd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gaohongyu789.top/Article/details/gtfwidpctg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zdqjudy.top/Article/details/gtpokxxwub.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.316326.xyz/Article/details/gtxowcdkoe.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sysykeji.top/Article/details/gtwqfxssgt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ppjwa.cn/Article/details/gtalwkwqmy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ehwqpu.com/Article/details/gtuvvxcvak.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.svipenyu.cn/Article/details/gtyhcxoywd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuanzx.com/Article/details/gtqhlnfkia.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtikvessai.html

O. 并发与异步
来源：http://dali.fzhhl.top/Article/details/gtvoagnswj.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtadrzfojh.html

[O01] 启动一个线程
来源：http://dali.hongshengwenyu.top/Article/details/gttwkssjes.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.fzhhl.top/Article/details/gtttaectgf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yangfankeji.com/Article/details/gtwigvzaae.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xuetiantiany.cn/Article/details/gtkzqmnhki.html

TS:   // 同 JS
来源：http://dali.hnqzz.top/Article/details/gtqgofvwec.html

Java: new Thread(() -> f()).start()
来源：http://dali.cqqwz.cn/Article/details/gtzglbzsgh.html

Go:   go f()
来源：http://dali.yj202588.top/Article/details/gtchzxtlyl.html

Ruby: Thread.new { f }
来源：http://dali.hfpthk.cn/Article/details/gtshmtuycd.html

C#:   Task.Run(() => F());
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzpceppyy.html

[O02] 使用线程池
来源：http://dali.yj20258888.top/Article/details/gtqpmlvuge.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yangfankeji.com/Article/details/gtjgixqzwd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ehwqpu.com/Article/details/gtzxzvlhee.html

JS:   // worker_threads 线程池
来源：http://dali.gotoacloud.top/Article/details/gtrjrezhuu.html

TS:   // worker_threads 线程池
来源：http://dali.yuanzhike.top/Article/details/gtsldddpbh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yongpay.top/Article/details/gtstfuukld.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shanyushiyangtech.top/Article/details/gtvpwatbkd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.svipenyu.cn/Article/details/gtequtdihg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.fzhhl.top/Article/details/gtkzcykhef.html

[O03] 加锁保护共享数据
来源：http://dali.zycfv.cn/Article/details/gtseasslgh.html

Py:   with lock: shared += 1
来源：http://dali.haohaochexian.top/Article/details/gtfgpkcsbd.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhiwuduotai.top/Article/details/gtubvqfcof.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.daxiang520.top/Article/details/gtwxcyeemg.html

TS:   // 同 JS
来源：http://dali.snrcjt.cn/Article/details/gtrzluavdt.html

Java: synchronized (this) { shared++; }
来源：http://dali.jlsjyb.cn/Article/details/gtxztmqzbj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hysaishi.cn/Article/details/gtrjrqxqou.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yanxiufei.cn/Article/details/gtwmjcgbtd.html

C#:   lock (gate) { shared++; }
来源：http://dali.dashuyun.cn/Article/details/gtkektfxal.html

[O04] 定义异步函数并等待
来源：http://dali.cashguo.top/Article/details/gtkzjifjcd.html

Py:   async def f():⏎    await g()
来源：http://dali.9152youxi.cn/Article/details/gtljzznxkl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.chenlongwang.top/Article/details/gtmjpqwxil.html

JS:   async function f() { await g(); }
来源：http://dali.pycfn.com/Article/details/gtzihfvugd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.mhx1999.top/Article/details/gtmcgzrpxb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.iojbl.cn/Article/details/gtlfcwziis.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhixingplan.top/Article/details/gtzpmkkzzg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.chenjidiqi.icu/Article/details/gtmfxbrgvx.html

C#:   async Task F() { await G(); }
来源：http://dali.zhoulong.xyz/Article/details/gtnljasuxy.html

[O05] 并发执行并等待全部完成
来源：http://dali.havefunace.top/Article/details/gtehspjvre.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttcikkaej.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhaomingkeji.xyz/Article/details/gtruwbdmgf.html

JS:   await Promise.all(tasks)
来源：http://dali.mhx1999.top/Article/details/gtzlbkmhmg.html

TS:   await Promise.all(tasks)
来源：http://dali.yueranfly.top/Article/details/gtoocngnka.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shuidangran.top/Article/details/gtuavvpavo.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.wangshuangyany.cn/Article/details/gtoucplong.html

Ruby: threads.map(&:join)
来源：http://dali.yj202588.top/Article/details/gtfaacfwqc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yuanzhike.top/Article/details/gtdwbewayu.html

[O06] 使用进程池
来源：http://dali.daxiang520.top/Article/details/gteqcykwyd.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbygcfzhk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.mhx1999.top/Article/details/gtdaysfono.html

JS:   // child_process / cluster 模块
来源：http://dali.jiagoushi.top/Article/details/gtxzpxsqth.html

TS:   // child_process / cluster 模块
来源：http://dali.jyoumei.cn/Article/details/gtsnavrphq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.daxiang520.top/Article/details/gtunhvcnwj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jlsjyb.cn/Article/details/gternzftzm.html

Ruby: // fork 块
来源：http://dali.meibo888.top/Article/details/gttqltuaxg.html

C#:   Parallel.For
来源：http://dali.haohaochexian.top/Article/details/gtwgyufffn.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gthacfvgjj.html

P. 常用工具函数
来源：http://dali.xylfe.cn/Article/details/gtuodbtrts.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtrocevtrv.html

[P01] 生成 UUID
来源：http://dali.meibo888.top/Article/details/gtqgtzetpv.html

Py:   str(uuid.uuid4())
来源：http://dali.nanxinkj.top/Article/details/gtnhydncqi.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shanyushiyangtech.top/Article/details/gtprrbkiij.html

JS:   crypto.randomUUID()
来源：http://dali.gzhubu.top/Article/details/gtmwfprmwe.html

TS:   crypto.randomUUID()
来源：http://dali.jyoumei.cn/Article/details/gtxektacsy.html

Java: UUID.randomUUID().toString()
来源：http://dali.wangshuangyany.cn/Article/details/gtfsguowpr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jinqigfzy.top/Article/details/gtlcmwbkjv.html

Ruby: SecureRandom.uuid
来源：http://dali.nwbrower.top/Article/details/gtgwxzhnmg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.dianchejie.cn/Article/details/gtqppdyciq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yanxiufei.cn/Article/details/gtgvnpkrle.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gotoacloud.top/Article/details/gtxywglvtd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xinyue.icu/Article/details/gtaccltmvt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.daxiang520.top/Article/details/gtwtyqgeqk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.aibaodan.cn/Article/details/gtmhkrsgts.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.aibaodan.cn/Article/details/gtykjfhwvi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cashguo.top/Article/details/gtgmopbbqo.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hnxiangtu.top/Article/details/gtdsvwlcek.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yj20258888.top/Article/details/gtuznmcbtu.html

[P03] 生成短随机字符串
来源：http://dali.ydzc1.top/Article/details/gtyrnsjxcu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ydzc1.top/Article/details/gtgdvytiko.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ybcxt.top/Article/details/gtsgssqxty.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqewoyemw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.0kj1m.cn/Article/details/gtovhvffui.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.kuanghao11.cn/Article/details/gtwxlqfbhm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.aibaodan.cn/Article/details/gtrdkuwlex.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gaohongyu789.top/Article/details/gtruxponvr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jqgfzy.top/Article/details/gthmldwyfa.html

[P04] 求长度
来源：http://dali.feifeiyinyue.top/Article/details/gtozzvflyi.html


<!-- 参考信息 -->