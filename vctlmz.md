代发 wailian999

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yongpay.top/Article/details/gtzjhlqpiq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shzxlz.cn/Article/details/gthnndlreu.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhixingplan.top/Article/details/gtmsgxlrgi.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.pycfn.com/Article/details/gtgtzhhwrr.html

[L07] 处理 HTTP 状态码
来源：http://dali.mhx1999.top/Article/details/gtbbvqrmzx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.wangshuangyany.cn/Article/details/gtsvcahkbs.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cucudq.cn/Article/details/gtedfdhthw.html

JS:   resp.ok;  resp.status
来源：http://dali.iojbl.cn/Article/details/gtkdgybcvx.html

TS:   resp.ok;  resp.status
来源：http://dali.yonumen.top/Article/details/gtjjliigja.html

Java: resp.statusCode()
来源：http://dali.bjfxy.top/Article/details/gtmfnusbib.html

Go:   resp.StatusCode
来源：http://dali.meibo888.top/Article/details/gtfdhxhcaz.html

Ruby: resp.code.to_i
来源：http://dali.smart0.xyz/Article/details/gttrpgocbb.html

C#:   (int)resp.StatusCode
来源：http://dali.shangyingyoupin.top/Article/details/gtltxtljrp.html

[L08] 并发请求多个地址
来源：http://dali.redwolf501.top/Article/details/gtzmkonada.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jqgufenzy.top/Article/details/gtnzzhgdji.html

PHP:  curl_multi_init() 系列
来源：http://dali.zdqjudy.top/Article/details/gtbdiyagqs.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.kuanghao11.cn/Article/details/gtofkrugai.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nwbrower.top/Article/details/gtwgspvnpb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jqgfzy.top/Article/details/gtrqkilfpk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yangfankeji.com/Article/details/gtobnmhjbe.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhixingplan.top/Article/details/gtekwvghxs.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yonumen.top/Article/details/gtzmqradnj.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtuihfrijf.html

M. 命令行 / 进程 / 环境
来源：http://dali.redwolf501.top/Article/details/gtlbprocil.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtvgjtggkc.html

[M01] 读取命令行参数
来源：http://dali.guannengcc.top/Article/details/gtynxfvvlo.html

Py:   sys.argv[1:]
来源：http://dali.yangfankeji.com/Article/details/gtrakliter.html

PHP:  $argv;  $argc;
来源：http://dali.redwolf501.top/Article/details/gtaqpdxsbe.html

JS:   process.argv.slice(2)
来源：http://dali.birdmap.top/Article/details/gtkyggvyxq.html

TS:   process.argv.slice(2)
来源：http://dali.xuetiantiany.cn/Article/details/gtrmclouvb.html

Java: args 数组（main 方法参数）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjmopyvgk.html

Go:   os.Args[1:]
来源：http://dali.andypj.xyz/Article/details/gtydvotmnn.html

Ruby: ARGV
来源：http://dali.fzhhl.top/Article/details/gtajfvvepx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hnqzz.top/Article/details/gtmgvywlji.html

[M02] 读取环境变量
来源：http://dali.jlsjyb.cn/Article/details/gtzxxtzotc.html

Py:   os.environ.get("HOME")
来源：http://dali.cqqwz.cn/Article/details/gtqicrhoxb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.iojbl.cn/Article/details/gtkqwuutwm.html

JS:   process.env.HOME
来源：http://dali.guowangkeji.top/Article/details/gtjzpftvcy.html

TS:   process.env.HOME
来源：http://dali.yangfankeji.com/Article/details/gtpfycrvty.html

Java: System.getenv("HOME")
来源：http://dali.hnqzz.top/Article/details/gtohbzlywi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gtuefjmlvw.html

Ruby: ENV["HOME"]
来源：http://dali.9152youxi.cn/Article/details/gtpzqjwiay.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tanke756.top/Article/details/gtrumirham.html

[M03] 执行外部命令
来源：http://dali.sysykeji.top/Article/details/gtjsybczcy.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tian-w.cn/Article/details/gtudzjlldm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jqgfzy.top/Article/details/gtxytmczww.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shuidangran.top/Article/details/gtlhdjiper.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangshuangyany.cn/Article/details/gtxnrxmwyi.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gotoacloud.top/Article/details/gtrfdqicjg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yongpay.top/Article/details/gtllidbucw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yuanzhike.top/Article/details/gtwxxniuan.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yuanzhike.top/Article/details/gtneyagpef.html

[M04] 获取当前工作目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfpjyrjdt.html

Py:   os.getcwd()
来源：http://dali.xinyue.icu/Article/details/gtmtambiyh.html

PHP:  getcwd();
来源：http://dali.0kj1m.cn/Article/details/gtienqkkny.html

JS:   process.cwd()
来源：http://dali.cheryme.top/Article/details/gtdyuvnsrt.html

TS:   process.cwd()
来源：http://dali.pycfn.com/Article/details/gtmcwhzmyf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yuxming.cn/Article/details/gtdyphiipc.html

Go:   os.Getwd()
来源：http://dali.zycfv.cn/Article/details/gtdsoumibb.html

Ruby: Dir.pwd
来源：http://dali.sweek.top/Article/details/gtzhfsrqyp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvkqqczjq.html

[M05] 设置退出码
来源：http://dali.bjfxy.top/Article/details/gtnukxqqrk.html

Py:   sys.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlxxicziv.html

PHP:  exit(1);
来源：http://dali.hysaishi.cn/Article/details/gtcixuvwne.html

JS:   process.exit(1)
来源：http://dali.tanke756.top/Article/details/gtntqenwfm.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtbbeowxbe.html

Java: System.exit(1)
来源：http://dali.yueranfly.top/Article/details/gtqfrgcgyj.html

Go:   os.Exit(1)
来源：http://dali.yj20258.top/Article/details/gtuugsmzvn.html

Ruby: exit 1
来源：http://dali.zhixingplan.top/Article/details/gtyffdeczq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.tian-w.cn/Article/details/gtxvksllso.html

[M06] 向标准错误输出
来源：http://dali.andypj.xyz/Article/details/gtkaspynou.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hnxiangtu.top/Article/details/gtzentbuxy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.guannengcc.top/Article/details/gticarfsog.html

JS:   console.error("err")
来源：http://dali.hnxiangtu.top/Article/details/gtsistfhyj.html

TS:   console.error("err")
来源：http://dali.dashuyun.cn/Article/details/gthtawulnk.html

Java: System.err.println("err")
来源：http://dali.zhoulong.xyz/Article/details/gtwstrhvap.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.nanxinkj.top/Article/details/gtdubuhkma.html

Ruby: warn "err"
来源：http://dali.sysykeji.top/Article/details/gtzzxadtlf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.andypj.xyz/Article/details/gtttqczvra.html

[M07] 判断是否为主入口
来源：http://dali.chenzaomai.com/Article/details/gtnsdoktuw.html

Py:   if __name__ == "__main__":
来源：http://dali.cqqwz.cn/Article/details/gtnmgtiwtm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.svipenyu.cn/Article/details/gtcnfpdlek.html

JS:   require.main === module
来源：http://dali.hnqzz.top/Article/details/gtgjmzizyd.html

TS:   require.main === module
来源：http://dali.gzhubu.top/Article/details/gttfvgljmp.html

Java: public static void main(String[] args)
来源：http://dali.hfpthk.cn/Article/details/gtxdjtetaq.html

Go:   func main()
来源：http://dali.zhongyouzk.top/Article/details/gtzdgepsro.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tian-w.cn/Article/details/gtuoijpttu.html

C#:   static void Main(string[] args)
来源：http://dali.yj20258888.top/Article/details/gtqodwgqxg.html

[M08] 获取系统与运行时信息
来源：http://dali.havefunace.top/Article/details/gthlquuavw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xylfe.cn/Article/details/gtjwwzjoqa.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.nanxinkj.top/Article/details/gtohnhezsi.html

JS:   process.platform;  process.version
来源：http://dali.aibaodan.cn/Article/details/gtowfbadnn.html

TS:   process.platform;  process.version
来源：http://dali.zhixingplan.top/Article/details/gtrjkdmxyv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.fzhhl.top/Article/details/gtdnkkgeuz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cqqwz.cn/Article/details/gtmpqwztky.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.c1oappe.top/Article/details/gtelmehdny.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhixingplan.top/Article/details/gtqlctrhjn.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtstftbgjw.html

N. 数据结构与算法
来源：http://dali.snrcjt.cn/Article/details/gtcdwdbtyl.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtxuglwkoe.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gtmlnlisyo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtsqrmuavb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yanxiufei.cn/Article/details/gtcsskysmc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtturupgwy.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqqpvmjfn.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtkviwtwnf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtlttsktwj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gaohongyu789.top/Article/details/gtvfluzzna.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqtbbsnon.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shangyingyoupin.top/Article/details/gtwhregotl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sufxvd.cn/Article/details/gtdvgdukwa.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.chenjidiqi.icu/Article/details/gtbygmmgxv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nwbrower.top/Article/details/gtwuemcyhy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cqqwz.cn/Article/details/gtprhygycq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.fengsongda.top/Article/details/gtdpjcijvs.html

Go:   slices.Sort(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtrjttwkgn.html

Ruby: arr.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzcvttvne.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yj20258.top/Article/details/gtmsgpkrzy.html

[N03] 快速排序（分治示例）
来源：http://dali.birdmap.top/Article/details/gtuocxijti.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gzhubu.top/Article/details/gtlnuqqwhi.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jianghu66.top/Article/details/gtwezpmndm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hywenlv.cn/Article/details/gthlfqqwxt.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tianlin.xyz/Article/details/gteddszyjt.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yonumen.top/Article/details/gtzqssighh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ywan-chungtsiang.top/Article/details/gtauuzomut.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.svipenyu.cn/Article/details/gtjrubcmbr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.fzhhl.top/Article/details/gtsisxevmn.html

[N04] 斐波那契数列
来源：http://dali.dianchejie.cn/Article/details/gtekslkxaf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hnxiangtu.top/Article/details/gtidlsbacf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.mhx1999.top/Article/details/gtkqnnlgfp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnxiangtu.top/Article/details/gtovhorgyd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gtlxfhrake.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.aibaodan.cn/Article/details/gtntpjqnri.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shangyingyoupin.top/Article/details/gtqsotsgtp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtqyflvtay.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xuetiantiany.cn/Article/details/gterubkrgk.html

[N05] 最大公约数
来源：http://dali.bjfxy.top/Article/details/gtlhlpdewz.html

Py:   math.gcd(a, b)
来源：http://dali.zhengqikj.top/Article/details/gtcjtnozzl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gzhubu.top/Article/details/gtwzmegztm.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jiagoushi.top/Article/details/gtmfnpszza.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtevmexenp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.svipenyu.cn/Article/details/gtktqiurxe.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.fzhhl.top/Article/details/gtwsqjmfnq.html

Ruby: a.gcd(b)
来源：http://dali.gzhubu.top/Article/details/gtzrtdwanb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yongpay.top/Article/details/gtamoiyfeo.html

[N06] 判断回文字符串
来源：http://dali.9152youxi.cn/Article/details/gtsxbkxjnp.html

Py:   s == s[::-1]
来源：http://dali.wangshuangyany.cn/Article/details/gtgbgqxduw.html

PHP:  $s === strrev($s);
来源：http://dali.hywenlv.cn/Article/details/gtttpylnpi.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gtggyjwkst.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gteulgxrht.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.nanxuanxn.top/Article/details/gtvyykzwvq.html

Go:   // 双指针从两端比较
来源：http://dali.9152youxi.cn/Article/details/gtazyxfbba.html

Ruby: s == s.reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbcsvhjiy.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhixingplan.top/Article/details/gtbmfelutn.html

[N07] 两数之和（返回下标）
来源：http://dali.vqdsnc.cn/Article/details/gtesistjyp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.meibo888.top/Article/details/gtnqghkzrp.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.316326.xyz/Article/details/gtilnandmj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.dianchejie.cn/Article/details/gtahyhbdul.html

TS:   // 手写 Map<string, number>
来源：http://dali.birdmap.top/Article/details/gtdokmssgl.html

Java: // 手写 HashMap
来源：http://dali.hnqzz.top/Article/details/gtqgedkkrn.html

Go:   // 手写 map[int]int
来源：http://dali.zycfv.cn/Article/details/gtmkeovbfo.html

Ruby: // 手写 Hash
来源：http://dali.ydzc1.top/Article/details/gtnggrfhit.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinqigufen.top/Article/details/gtvzahhdlo.html

[N08] 生成全排列
来源：http://dali.xinyue.icu/Article/details/gtipcwdiuo.html

Py:   itertools.permutations(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgvlevzix.html

PHP:  // 手写递归交换
来源：http://dali.zhaomingkeji.xyz/Article/details/gttrzwsomj.html

JS:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gtwgubhufz.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gtcjvjsjng.html

Java: // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gtixtcztje.html

Go:   // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gtyuvmpchz.html

Ruby: arr.permutation.to_a
来源：http://dali.gzhubu.top/Article/details/gtkwwfnazh.html

C#:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gtolgnphmf.html

[N09] 栈与队列
来源：http://dali.havefunace.top/Article/details/gtyvzyqeqs.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhongyouzk.top/Article/details/gtuzlkpvsp.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xylfe.cn/Article/details/gtlydednyx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jiagoushi.top/Article/details/gtcmgmeyvr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jiagoushi.top/Article/details/gtvamsmibt.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtksvlvgrp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.nanxinkj.top/Article/details/gtzzqcxxaa.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sysykeji.top/Article/details/gtbandbkpd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yangfankeji.com/Article/details/gtxttpbulj.html

[N10] 链表节点定义
来源：http://dali.316326.xyz/Article/details/gtxhdrgucn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhixingplan.top/Article/details/gtellenfkn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbhotjbwi.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.pengpengdd.cyou/Article/details/gtvrqjqfld.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.daria6918.cn/Article/details/gtnpwhvguu.html

Java: class Node { int v; Node next; }
来源：http://dali.jiagoushi.top/Article/details/gtzyhdawgl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jqgfzy.top/Article/details/gtwjtufurz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.smart0.xyz/Article/details/gtvdccmpuu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hongshengwenyu.top/Article/details/gtsziblbwv.html

[N11] 二叉树中序遍历
来源：http://dali.shzxlz.cn/Article/details/gtlaaxmkbw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.9152youxi.cn/Article/details/gtefldqkpv.html

PHP:  // 手写递归函数
来源：http://dali.yj20258.top/Article/details/gtkumhedgu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gogol.net.cn/Article/details/gtlpuaijvf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cucudq.cn/Article/details/gtyedrkumw.html

Java: // 手写递归
来源：http://dali.aibaodan.cn/Article/details/gtieaoqiut.html

Go:   // 手写递归
来源：http://dali.ehwqpu.com/Article/details/gtekawedet.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.nwbrower.top/Article/details/gtkbvdlliq.html

C#:   // 手写递归
来源：http://dali.cdnleiting.top/Article/details/gtsitzlkpe.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.feifeiyinyue.top/Article/details/gtliplxnks.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cdnleiting.top/Article/details/gtmbzyqtvp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xziqi.cn/Article/details/gtmvoeotkk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzvrhuhek.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ehwqpu.com/Article/details/gtyaapgzfo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gtregjpicf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhongyouzk.top/Article/details/gtlxmokecg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhongyouzk.top/Article/details/gtxzslmaqj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gzhubu.top/Article/details/gtxuovcmsd.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtxiptenwx.html

O. 并发与异步
来源：http://dali.hammf.cn/Article/details/gtmqtunsxe.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtoulbmvfp.html

[O01] 启动一个线程
来源：http://dali.ybcxt.top/Article/details/gtopdugjtq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.meibo888.top/Article/details/gtmxphizef.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yueranfly.top/Article/details/gtbxbyvbmn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.feifeiyinyue.top/Article/details/gtrqyxqcnx.html

TS:   // 同 JS
来源：http://dali.smart0.xyz/Article/details/gthsyqjftm.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gtdvrzlfeu.html

Go:   go f()
来源：http://dali.yueranfly.top/Article/details/gttpdpnhho.html

Ruby: Thread.new { f }
来源：http://dali.xinyue.icu/Article/details/gtfcejrkcb.html

C#:   Task.Run(() => F());
来源：http://dali.birdmap.top/Article/details/gtzqasfuys.html

[O02] 使用线程池
来源：http://dali.0kj1m.cn/Article/details/gtqfwcdkro.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.quarkkingdee.top/Article/details/gtohbwuxwt.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinqigfzy.top/Article/details/gtzsxgdjpl.html

JS:   // worker_threads 线程池
来源：http://dali.zhoulong.xyz/Article/details/gtuexfzsue.html

TS:   // worker_threads 线程池
来源：http://dali.havefunace.top/Article/details/gtkldarvau.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.quarkkingdee.top/Article/details/gtswmsmcae.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cucudq.cn/Article/details/gtesjjovik.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hfpthk.cn/Article/details/gtaspjiace.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gotoacloud.top/Article/details/gtrffeyzri.html

[O03] 加锁保护共享数据
来源：http://dali.fzhhl.top/Article/details/gtplujyxnl.html

Py:   with lock: shared += 1
来源：http://dali.ybcxt.top/Article/details/gtxhnoylmp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.fengsongda.top/Article/details/gtarwmgwwr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shzxlz.cn/Article/details/gtlskcqoob.html

TS:   // 同 JS
来源：http://dali.iojbl.cn/Article/details/gtcyxytspx.html

Java: synchronized (this) { shared++; }
来源：http://dali.xinyue.icu/Article/details/gtybwtfrgn.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cqqwz.cn/Article/details/gtlkhdssmo.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhongyouzk.top/Article/details/gtfjitxcsw.html

C#:   lock (gate) { shared++; }
来源：http://dali.xinyue.icu/Article/details/gtooeycqaw.html

[O04] 定义异步函数并等待
来源：http://dali.pengpengdd.cyou/Article/details/gtdocjcsia.html

Py:   async def f():⏎    await g()
来源：http://dali.jianghu66.top/Article/details/gtegwmoemu.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xuanzx.com/Article/details/gtwrttfxyy.html

JS:   async function f() { await g(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtttugaqxc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.aibaodan.cn/Article/details/gtscjetglb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.0kj1m.cn/Article/details/gtvpgteypr.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gaohongyu789.top/Article/details/gtxkpxyred.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gzhubu.top/Article/details/gtmaswmjdd.html

C#:   async Task F() { await G(); }
来源：http://dali.gzhubu.top/Article/details/gtdtlhxfol.html

[O05] 并发执行并等待全部完成
来源：http://dali.jianghu66.top/Article/details/gtwytinumx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.aizwys.cn/Article/details/gtvflfwypz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cdnleiting.top/Article/details/gtccxnrgus.html

JS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangtech.top/Article/details/gtciribltf.html

TS:   await Promise.all(tasks)
来源：http://dali.yangfankeji.com/Article/details/gtildoiahh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.316326.xyz/Article/details/gttrzunidd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.redwolf501.top/Article/details/gtlgspqbgi.html

Ruby: threads.map(&:join)
来源：http://dali.yuanzhike.top/Article/details/gtcfimwivo.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cdnleiting.top/Article/details/gtdelbztya.html

[O06] 使用进程池
来源：http://dali.nanxuanxn.top/Article/details/gtfirqwpqn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jyoumei.cn/Article/details/gtjeneiloj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xziqi.cn/Article/details/gtaewwwrfu.html

JS:   // child_process / cluster 模块
来源：http://dali.pycfn.com/Article/details/gtnargtikc.html

TS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuxcgsahp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yj20258888.top/Article/details/gtsffvehwe.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.chenzaomai.com/Article/details/gtdjpnxjbz.html

Ruby: // fork 块
来源：http://dali.nanxuanxn.top/Article/details/gtgymvvrvs.html

C#:   Parallel.For
来源：http://dali.yanxiufei.cn/Article/details/gtqqquojln.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbvqiemuu.html

P. 常用工具函数
来源：http://dali.cqqwz.cn/Article/details/gtpaudvzvo.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtazkcyvcz.html

[P01] 生成 UUID
来源：http://dali.tanke756.top/Article/details/gtoehekrlq.html

Py:   str(uuid.uuid4())
来源：http://dali.fengsongda.top/Article/details/gtgzlzeqml.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xuetiantiany.cn/Article/details/gtswsrpgrf.html

JS:   crypto.randomUUID()
来源：http://dali.mhx1999.top/Article/details/gtnqquqauy.html

TS:   crypto.randomUUID()
来源：http://dali.yuxming.cn/Article/details/gtperpmbvj.html

Java: UUID.randomUUID().toString()
来源：http://dali.jqgfzy.top/Article/details/gtnehadxlt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ybcxt.top/Article/details/gtpkaeouwc.html

Ruby: SecureRandom.uuid
来源：http://dali.iojbl.cn/Article/details/gtjmfcrxzw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yvedp.cn/Article/details/gtuplcsufo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hongshengwenyu.top/Article/details/gthfsomsva.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shzxlz.cn/Article/details/gtxlzwzear.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.havefunace.top/Article/details/gtrzqaayar.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sxryk.cn/Article/details/gtajbderfu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zdqjudy.top/Article/details/gtitgkrlpy.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hywenlv.cn/Article/details/gtcdnvktcs.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hysaishi.cn/Article/details/gtqskiqpxf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hnxiangtu.top/Article/details/gthqfcqfel.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cdnleiting.top/Article/details/gtvnvejbyy.html

[P03] 生成短随机字符串
来源：http://dali.hammf.cn/Article/details/gttxublhsm.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jinqigufen.top/Article/details/gthlgwsvhl.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yongpay.top/Article/details/gtahghczkr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.dianchejie.cn/Article/details/gtuubwkfiy.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daxiang520.top/Article/details/gtyjzlepxw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yuxming.cn/Article/details/gtqvopnhsd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.nanxinkj.top/Article/details/gtsnddidez.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.sweek.top/Article/details/gttroarnzv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.snrcjt.cn/Article/details/gtzofuifws.html

[P04] 求长度
来源：http://dali.hysaishi.cn/Article/details/gtmkapvttl.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yj20258.top/Article/details/gtqwhonikd.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gtwlyzqqsz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgfzy.top/Article/details/gtflyowjtn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.aizwys.cn/Article/details/gtemooinuq.html


<!-- 参考信息 -->