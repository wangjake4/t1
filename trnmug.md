代发 wailian999

Py:   resp.json()
来源：http://dali.0kj1m.cn/Article/details/gtvahajpcc.html

PHP:  json_decode($body, true);
来源：http://dali.xziqi.cn/Article/details/gtftniurin.html

JS:   await resp.json()
来源：http://dali.jiagoushi.top/Article/details/gtfyldvrtz.html

TS:   await resp.json()
来源：http://dali.havefunace.top/Article/details/gtlwkojmlu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gtjdwbvxui.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.pengpengdd.cyou/Article/details/gtlandwebk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.feifeiyinyue.top/Article/details/gtpnpjpbad.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.snrcjt.cn/Article/details/gtcpjtmoyp.html

[L07] 处理 HTTP 状态码
来源：http://dali.yuanzhike.top/Article/details/gtjdlblxqa.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sufxvd.cn/Article/details/gtcxseskpq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.tian-w.cn/Article/details/gtwooltpif.html

JS:   resp.ok;  resp.status
来源：http://dali.jqgfzy.top/Article/details/gtdqgxostd.html

TS:   resp.ok;  resp.status
来源：http://dali.meibo888.top/Article/details/gtnprllzgb.html

Java: resp.statusCode()
来源：http://dali.zhongyouzk.top/Article/details/gtyylqbysg.html

Go:   resp.StatusCode
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsltrzszh.html

Ruby: resp.code.to_i
来源：http://dali.0kj1m.cn/Article/details/gtbaotpigz.html

C#:   (int)resp.StatusCode
来源：http://dali.feifeiyinyue.top/Article/details/gtehgwdrcg.html

[L08] 并发请求多个地址
来源：http://dali.yuanzhike.top/Article/details/gtxquqiout.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhixingplan.top/Article/details/gtnlbefhea.html

PHP:  curl_multi_init() 系列
来源：http://dali.yj202588.top/Article/details/gtaachunci.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daxiang520.top/Article/details/gtpwlypusn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuanzx.com/Article/details/gtaikvipjm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj20258.top/Article/details/gtaxviedfw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xinyue.icu/Article/details/gtqyvoiugx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.feifeiyinyue.top/Article/details/gtvexypfcj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hnqzz.top/Article/details/gtptkundvl.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtaiwfwmar.html

M. 命令行 / 进程 / 环境
来源：http://dali.tian-w.cn/Article/details/gtzofrikwt.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtjcswqxqf.html

[M01] 读取命令行参数
来源：http://dali.dianchejie.cn/Article/details/gtdoouoevn.html

Py:   sys.argv[1:]
来源：http://dali.iojbl.cn/Article/details/gtnhtvphjm.html

PHP:  $argv;  $argc;
来源：http://dali.nwbrower.top/Article/details/gtcrwmqjhs.html

JS:   process.argv.slice(2)
来源：http://dali.hnxiangtu.top/Article/details/gtovtkodpd.html

TS:   process.argv.slice(2)
来源：http://dali.birdmap.top/Article/details/gtpvkstovb.html

Java: args 数组（main 方法参数）
来源：http://dali.jinqigufen.top/Article/details/gtkyuhmxex.html

Go:   os.Args[1:]
来源：http://dali.sxryk.cn/Article/details/gtevchfbix.html

Ruby: ARGV
来源：http://dali.ybcxt.top/Article/details/gtwpoajrgr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hammf.cn/Article/details/gtocorivih.html

[M02] 读取环境变量
来源：http://dali.feifeiyinyue.top/Article/details/gtojvlgyht.html

Py:   os.environ.get("HOME")
来源：http://dali.wangdashe.top/Article/details/gtlcnvotmt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.haohaochexian.top/Article/details/gtnlozizkr.html

JS:   process.env.HOME
来源：http://dali.mhx1999.top/Article/details/gtuiodqvfy.html

TS:   process.env.HOME
来源：http://dali.jinghuilouyu.cn/Article/details/gtsdayhbuq.html

Java: System.getenv("HOME")
来源：http://dali.pycfn.com/Article/details/gtlrtujdoh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ehwqpu.com/Article/details/gtdhhzqgyz.html

Ruby: ENV["HOME"]
来源：http://dali.xuanzx.com/Article/details/gtpisxxsll.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gtlbzzyszn.html

[M03] 执行外部命令
来源：http://dali.pycfn.com/Article/details/gtskgockdw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zdqjudy.top/Article/details/gtprmgghkp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.fengsongda.top/Article/details/gtapsnltnf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnxiangtu.top/Article/details/gtlmosvoue.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.quarkkingdee.top/Article/details/gtkmjfwlua.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.meibo888.top/Article/details/gtxiciocvc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sufxvd.cn/Article/details/gtauhonwmm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sufxvd.cn/Article/details/gtznzqbfsi.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zycfv.cn/Article/details/gtygawrdoj.html

[M04] 获取当前工作目录
来源：http://dali.smart0.xyz/Article/details/gthpkdtefs.html

Py:   os.getcwd()
来源：http://dali.zhiwuduotai.top/Article/details/gteneahlhv.html

PHP:  getcwd();
来源：http://dali.yongpay.top/Article/details/gtqhmrhkod.html

JS:   process.cwd()
来源：http://dali.jqgfzy.top/Article/details/gtvpyqslys.html

TS:   process.cwd()
来源：http://dali.9152youxi.cn/Article/details/gthvldlaru.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sufxvd.cn/Article/details/gtmynlwuoo.html

Go:   os.Getwd()
来源：http://dali.dianchejie.cn/Article/details/gthoruejfg.html

Ruby: Dir.pwd
来源：http://dali.shuidangran.top/Article/details/gtpzrdvtiw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.smart0.xyz/Article/details/gtrsjafljz.html

[M05] 设置退出码
来源：http://dali.yj20258.top/Article/details/gtjadvhine.html

Py:   sys.exit(1)
来源：http://dali.xziqi.cn/Article/details/gtwymzzuba.html

PHP:  exit(1);
来源：http://dali.nanxinkj.top/Article/details/gtqwcdgpcc.html

JS:   process.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtchvztcvp.html

TS:   process.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gttgpskfoy.html

Java: System.exit(1)
来源：http://dali.yuxming.cn/Article/details/gtqfnzxzts.html

Go:   os.Exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gtsujujtnl.html

Ruby: exit 1
来源：http://dali.mhx1999.top/Article/details/gtuzxuqnod.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.9152youxi.cn/Article/details/gtsqigkqlo.html

[M06] 向标准错误输出
来源：http://dali.sufxvd.cn/Article/details/gthiurbmnv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.tianlin.xyz/Article/details/gtycqxkjgr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.svipenyu.cn/Article/details/gtfduvpthy.html

JS:   console.error("err")
来源：http://dali.yangfankeji.com/Article/details/gtsvbhdntk.html

TS:   console.error("err")
来源：http://dali.tianlin.xyz/Article/details/gtqnmirpjq.html

Java: System.err.println("err")
来源：http://dali.cucudq.cn/Article/details/gtjsgtueih.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gaohongyu789.top/Article/details/gtoosywjjz.html

Ruby: warn "err"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxvrpaodx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ybcxt.top/Article/details/gtqzgqoqxa.html

[M07] 判断是否为主入口
来源：http://dali.guowangkeji.top/Article/details/gtvyjbsybq.html

Py:   if __name__ == "__main__":
来源：http://dali.gzhubu.top/Article/details/gtusviwxsj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jiagoushi.top/Article/details/gtfimchruw.html

JS:   require.main === module
来源：http://dali.hammf.cn/Article/details/gtsxubswbr.html

TS:   require.main === module
来源：http://dali.redwolf501.top/Article/details/gtbeobbudl.html

Java: public static void main(String[] args)
来源：http://dali.ehwqpu.com/Article/details/gtraahdbab.html

Go:   func main()
来源：http://dali.haohaochexian.top/Article/details/gtbjzgmhpa.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhongyouzk.top/Article/details/gtxtupzsky.html

C#:   static void Main(string[] args)
来源：http://dali.ppjwa.cn/Article/details/gtapybyflz.html

[M08] 获取系统与运行时信息
来源：http://dali.chenjidiqi.icu/Article/details/gtwqrnldvh.html

Py:   platform.system();  platform.python_version()
来源：http://dali.aizwys.cn/Article/details/gtmgzfkufp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jqgfzy.top/Article/details/gtstdmcdre.html

JS:   process.platform;  process.version
来源：http://dali.sysykeji.top/Article/details/gtqpdldnya.html

TS:   process.platform;  process.version
来源：http://dali.daria6918.cn/Article/details/gtpgjtvlrn.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.vqdsnc.cn/Article/details/gtwvuojokn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.chenzaomai.com/Article/details/gtjymomrxf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hysaishi.cn/Article/details/gtihezqkpv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yj202588.top/Article/details/gtbglrrjmp.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtwfcoyxji.html

N. 数据结构与算法
来源：http://dali.daria6918.cn/Article/details/gtjmrkqflm.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtzoilmmmg.html

[N01] 二分查找（有序数组）
来源：http://dali.hfpthk.cn/Article/details/gtrihgofpf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.havefunace.top/Article/details/gthtypcmwl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cqqwz.cn/Article/details/gtgvzyahkj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zdqjudy.top/Article/details/gtgwbimqxb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jianghu66.top/Article/details/gtcocmwzcu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gtgniwzqyy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yongpay.top/Article/details/gtmxvlgfot.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj20258.top/Article/details/gteuwhmmgf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtdgtrtarc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfkjgmrin.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sxryk.cn/Article/details/gtmrjkdgge.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yangfankeji.com/Article/details/gtcavmewta.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.0kj1m.cn/Article/details/gtiftoxgdk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxinkj.top/Article/details/gtlknlaqlg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.316326.xyz/Article/details/gtwobsbjiq.html

Go:   slices.Sort(arr)
来源：http://dali.redwolf501.top/Article/details/gtqemtdwcc.html

Ruby: arr.sort
来源：http://dali.zhoulong.xyz/Article/details/gteodwahce.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jlsjyb.cn/Article/details/gtkyqeasyo.html

[N03] 快速排序（分治示例）
来源：http://dali.sysykeji.top/Article/details/gtuarubmex.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shzxlz.cn/Article/details/gtlmjcmreu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.feifeiyinyue.top/Article/details/gtvecfkgwi.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pengpengdd.cyou/Article/details/gtgrszpxmv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gtvomnhvje.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.kuanghao11.cn/Article/details/gtvlyyzmdt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gthtmclaxw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ybcxt.top/Article/details/gthejlujbe.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xuanzx.com/Article/details/gtmrszexdm.html

[N04] 斐波那契数列
来源：http://dali.kuanghao11.cn/Article/details/gtxzeywagn.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hammf.cn/Article/details/gtvmxfojof.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yuxming.cn/Article/details/gtvykskawt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxuanxn.top/Article/details/gtodeegevw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj202588.top/Article/details/gtjtvmpbsa.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ybcxt.top/Article/details/gtkhjlbbht.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yuanzhike.top/Article/details/gtglfkitka.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jlsjyb.cn/Article/details/gtgrgipdlb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtgqcvibeb.html

[N05] 最大公约数
来源：http://dali.sxryk.cn/Article/details/gtiegtttrm.html

Py:   math.gcd(a, b)
来源：http://dali.gotoacloud.top/Article/details/gtrryyxvrm.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtprvtzdzs.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gogol.net.cn/Article/details/gtbkpcaedo.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gaohongyu789.top/Article/details/gtgvdwobyd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yuxming.cn/Article/details/gtnbpwmubs.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yj202588.top/Article/details/gtdumcecyw.html

Ruby: a.gcd(b)
来源：http://dali.aizwys.cn/Article/details/gtzblhuzis.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjoybwaaf.html

[N06] 判断回文字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtpzkguhbk.html

Py:   s == s[::-1]
来源：http://dali.shzxlz.cn/Article/details/gtobzzgxue.html

PHP:  $s === strrev($s);
来源：http://dali.yj202588.top/Article/details/gtitvdvuba.html

JS:   s === [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gtupuxnwzk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gtdyxykzel.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shuidangran.top/Article/details/gtvofsjzcd.html

Go:   // 双指针从两端比较
来源：http://dali.sweek.top/Article/details/gtlbwybcgk.html

Ruby: s == s.reverse
来源：http://dali.ppjwa.cn/Article/details/gtazdkiamq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gaohongyu789.top/Article/details/gtomgcqyjp.html

[N07] 两数之和（返回下标）
来源：http://dali.nanxuanxn.top/Article/details/gtvmliudpj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.nanxinkj.top/Article/details/gtfwsetpru.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.tanke756.top/Article/details/gtswvrgmko.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.c1oappe.top/Article/details/gtaufysqsa.html

TS:   // 手写 Map<string, number>
来源：http://dali.xylfe.cn/Article/details/gtalgndpmn.html

Java: // 手写 HashMap
来源：http://dali.jinghuilouyu.cn/Article/details/gtrwmfkuyi.html

Go:   // 手写 map[int]int
来源：http://dali.xinyue.icu/Article/details/gtoswfnfcr.html

Ruby: // 手写 Hash
来源：http://dali.cdnleiting.top/Article/details/gtbqrdpdiw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ehwqpu.com/Article/details/gtazlommem.html

[N08] 生成全排列
来源：http://dali.chenzaomai.com/Article/details/gtrgqxkcvo.html

Py:   itertools.permutations(arr)
来源：http://dali.mhx1999.top/Article/details/gtstlrhxyq.html

PHP:  // 手写递归交换
来源：http://dali.xinyue.icu/Article/details/gtkwawaeoj.html

JS:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gtygjxgvwe.html

TS:   // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gtjjzwmdnp.html

Java: // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gtltagnouy.html

Go:   // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gtpakrmpcm.html

Ruby: arr.permutation.to_a
来源：http://dali.dashuyun.cn/Article/details/gtcymoyhwg.html

C#:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gtarnvrlug.html

[N09] 栈与队列
来源：http://dali.daxiang520.top/Article/details/gtfadjnnma.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.tianlin.xyz/Article/details/gttlrhvtji.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sxryk.cn/Article/details/gtlhftnylo.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hnqzz.top/Article/details/gtkxduwlqz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nwbrower.top/Article/details/gtbtsqgkjl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hysaishi.cn/Article/details/gtmcqwtejt.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.guannengcc.top/Article/details/gtskgpeomn.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cqqwz.cn/Article/details/gtlecsuscu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.nanxuanxn.top/Article/details/gtchfoadwp.html

[N10] 链表节点定义
来源：http://dali.shuidangran.top/Article/details/gtguavjvqp.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hammf.cn/Article/details/gtuqugplrp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.vqdsnc.cn/Article/details/gtzpwrmnxa.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xziqi.cn/Article/details/gtajtcbvey.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shuidangran.top/Article/details/gtraxdftdf.html

Java: class Node { int v; Node next; }
来源：http://dali.fzhhl.top/Article/details/gturfdtbdp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xylfe.cn/Article/details/gtwrgubekd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cdnleiting.top/Article/details/gtyyvknvtu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.c1oappe.top/Article/details/gtsqftdbcp.html

[N11] 二叉树中序遍历
来源：http://dali.aibaodan.cn/Article/details/gteewithng.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.chenlongwang.top/Article/details/gtqtszrxga.html

PHP:  // 手写递归函数
来源：http://dali.zhixingplan.top/Article/details/gtkfhhkqdo.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.vqdsnc.cn/Article/details/gtqfkvntdt.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhoulong.xyz/Article/details/gtuazgfghm.html

Java: // 手写递归
来源：http://dali.yongpay.top/Article/details/gtkrgunmea.html

Go:   // 手写递归
来源：http://dali.tian-w.cn/Article/details/gtnwipmvqf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.chenlongwang.top/Article/details/gtxwtavdls.html

C#:   // 手写递归
来源：http://dali.hammf.cn/Article/details/gtdhsuwvyi.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gogol.net.cn/Article/details/gtcgyefdnq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.andypj.xyz/Article/details/gtqmuyxbpy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.0kj1m.cn/Article/details/gtjrhsexnb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.quarkkingdee.top/Article/details/gtuxynwtyi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hammf.cn/Article/details/gtjerxtytt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.birdmap.top/Article/details/gtjgnuptmd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hongshengwenyu.top/Article/details/gtbzmbzazd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cucudq.cn/Article/details/gtfjldsltq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhengqikj.top/Article/details/gtuewuqbbu.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtuojpivwk.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gtspccflgq.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gthnuhqmbi.html

[O01] 启动一个线程
来源：http://dali.hysaishi.cn/Article/details/gtxooauwey.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.quarkkingdee.top/Article/details/gtxgimdfxk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yj202588.top/Article/details/gtqtoyvisz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.birdmap.top/Article/details/gtcldmtwns.html

TS:   // 同 JS
来源：http://dali.ppjwa.cn/Article/details/gtkevzedvb.html

Java: new Thread(() -> f()).start()
来源：http://dali.redwolf501.top/Article/details/gtlxofhhio.html

Go:   go f()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtugletgto.html

Ruby: Thread.new { f }
来源：http://dali.zhixingplan.top/Article/details/gtrarwddly.html

C#:   Task.Run(() => F());
来源：http://dali.birdmap.top/Article/details/gtxyiavwbg.html

[O02] 使用线程池
来源：http://dali.dashuyun.cn/Article/details/gtqivjccyn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xinyue.icu/Article/details/gtzyupzcit.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.dashuyun.cn/Article/details/gttvrrfgha.html

JS:   // worker_threads 线程池
来源：http://dali.sweek.top/Article/details/gtwleedzal.html

TS:   // worker_threads 线程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqmtlevxg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yanxiufei.cn/Article/details/gtubvveqvu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.snrcjt.cn/Article/details/gtnpbwmrsc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhengqikj.top/Article/details/gtbeghodow.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.guannengcc.top/Article/details/gtewbebnnz.html

[O03] 加锁保护共享数据
来源：http://dali.0kj1m.cn/Article/details/gtxpqgkqar.html

Py:   with lock: shared += 1
来源：http://dali.zhengqikj.top/Article/details/gtmowmiapy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yangfankeji.com/Article/details/gtdhsbmpoi.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yongpay.top/Article/details/gtfdtdzcnd.html

TS:   // 同 JS
来源：http://dali.daxiang520.top/Article/details/gtjtvrihdo.html

Java: synchronized (this) { shared++; }
来源：http://dali.cucudq.cn/Article/details/gtyssxjybe.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hnxiangtu.top/Article/details/gttbcuniuc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cdnleiting.top/Article/details/gtkgumijcw.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinqigufen.top/Article/details/gtjmpdzrbo.html

[O04] 定义异步函数并等待
来源：http://dali.hnxiangtu.top/Article/details/gtxuiguyhl.html

Py:   async def f():⏎    await g()
来源：http://dali.jinqigfzy.top/Article/details/gtuqlajwuq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jiagoushi.top/Article/details/gtjckvndgm.html

JS:   async function f() { await g(); }
来源：http://dali.wangdashe.top/Article/details/gthjpkcwbs.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.redwolf501.top/Article/details/gtubysveva.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hfpthk.cn/Article/details/gtbewedxle.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.316326.xyz/Article/details/gtgjudmuwx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gtqiikcacn.html

C#:   async Task F() { await G(); }
来源：http://dali.shuidangran.top/Article/details/gtettyekpv.html

[O05] 并发执行并等待全部完成
来源：http://dali.andypj.xyz/Article/details/gthwzdyqsd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.sweek.top/Article/details/gtrrlierxg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.316326.xyz/Article/details/gtliexhkbw.html

JS:   await Promise.all(tasks)
来源：http://dali.ybcxt.top/Article/details/gtoawxpvjc.html

TS:   await Promise.all(tasks)
来源：http://dali.c1oappe.top/Article/details/gtgmuimkqs.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.vqdsnc.cn/Article/details/gtsjcdrjcs.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shzxlz.cn/Article/details/gtnoceqafl.html

Ruby: threads.map(&:join)
来源：http://dali.hammf.cn/Article/details/gtwkafizeu.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.birdmap.top/Article/details/gthvoxivyd.html

[O06] 使用进程池
来源：http://dali.fengsongda.top/Article/details/gtdrfnryfy.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.nanxuanxn.top/Article/details/gtibrnidgr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfsnbsyiu.html

JS:   // child_process / cluster 模块
来源：http://dali.svipenyu.cn/Article/details/gtxnhkeplp.html

TS:   // child_process / cluster 模块
来源：http://dali.zdqjudy.top/Article/details/gtduepntve.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jlsjyb.cn/Article/details/gtzacuyixh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ppjwa.cn/Article/details/gtctbhwjpe.html

Ruby: // fork 块
来源：http://dali.kuanghao11.cn/Article/details/gtekwvlxvs.html

C#:   Parallel.For
来源：http://dali.zdqjudy.top/Article/details/gtmvodpotl.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gthacnszlt.html

P. 常用工具函数
来源：http://dali.yj202588.top/Article/details/gtodqhzjuj.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtaevmbbdy.html

[P01] 生成 UUID
来源：http://dali.xziqi.cn/Article/details/gtogvyriyb.html

Py:   str(uuid.uuid4())
来源：http://dali.ppjwa.cn/Article/details/gtliujuozh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yuanzhike.top/Article/details/gtntcugwdj.html

JS:   crypto.randomUUID()
来源：http://dali.smart0.xyz/Article/details/gtovulnvjc.html

TS:   crypto.randomUUID()
来源：http://dali.sysykeji.top/Article/details/gtpzjmljvo.html

Java: UUID.randomUUID().toString()
来源：http://dali.yuxming.cn/Article/details/gtwsyfbtta.html

Go:   // 用 github.com/google/uuid
来源：http://dali.9152youxi.cn/Article/details/gtwtwmkbew.html

Ruby: SecureRandom.uuid
来源：http://dali.jinghuilouyu.cn/Article/details/gtetrskcbn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ybcxt.top/Article/details/gtaeuaadrb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinqigfzy.top/Article/details/gtvmlbuuki.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.andypj.xyz/Article/details/gtkquenwey.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ehwqpu.com/Article/details/gtsbfqszqt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xylfe.cn/Article/details/gtjgvrzdkv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cqqwz.cn/Article/details/gtyiodloox.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.quarkkingdee.top/Article/details/gtiopplqrh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shanyushiyangtech.top/Article/details/gtjxjczweb.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfnvztbqv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gzhubu.top/Article/details/gthscsangx.html

[P03] 生成短随机字符串
来源：http://dali.fzhhl.top/Article/details/gtqazfvjke.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.snrcjt.cn/Article/details/gtmyqnwxqd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.mhx1999.top/Article/details/gtpjcswbbi.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.316326.xyz/Article/details/gtgfrouxah.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ybcxt.top/Article/details/gtvvbtqbmw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shuidangran.top/Article/details/gtefxxdkyk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hywenlv.cn/Article/details/gtwrtfwtlh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cdnleiting.top/Article/details/gtynooezla.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.svipenyu.cn/Article/details/gtvytzhccv.html

[P04] 求长度
来源：http://dali.jqgfzy.top/Article/details/gtodrpjian.html


<!-- 参考信息 -->