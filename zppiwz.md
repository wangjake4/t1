代发 wailian999

Py:   resp.json()
来源：http://dali.cucudq.cn/Article/details/gtfeguciim.html

PHP:  json_decode($body, true);
来源：http://dali.xinyue.icu/Article/details/gtrrahnnvg.html

JS:   await resp.json()
来源：http://dali.sxryk.cn/Article/details/gtijcbsxzo.html

TS:   await resp.json()
来源：http://dali.daxiang520.top/Article/details/gtjznxgnlt.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hysaishi.cn/Article/details/gtjrsyeyak.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xuetiantiany.cn/Article/details/gtchixrgmw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tanke756.top/Article/details/gtvuolguhr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jqgfzy.top/Article/details/gtjymfscon.html

[L07] 处理 HTTP 状态码
来源：http://dali.shanyushiyangtech.top/Article/details/gtomptyzgp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ybcxt.top/Article/details/gtyxmwxgyv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sufxvd.cn/Article/details/gtxvrtmcbw.html

JS:   resp.ok;  resp.status
来源：http://dali.chenlongwang.top/Article/details/gtdkxccqcq.html

TS:   resp.ok;  resp.status
来源：http://dali.pycfn.com/Article/details/gtvbymxjky.html

Java: resp.statusCode()
来源：http://dali.haohaochexian.top/Article/details/gtdjdrnwir.html

Go:   resp.StatusCode
来源：http://dali.ppjwa.cn/Article/details/gtgndtpxej.html

Ruby: resp.code.to_i
来源：http://dali.fzhhl.top/Article/details/gtgnjmmybd.html

C#:   (int)resp.StatusCode
来源：http://dali.shuidangran.top/Article/details/gtqhvxlksy.html

[L08] 并发请求多个地址
来源：http://dali.quarkkingdee.top/Article/details/gtwsnrmbsi.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jianghu66.top/Article/details/gtioajlily.html

PHP:  curl_multi_init() 系列
来源：http://dali.ppjwa.cn/Article/details/gtggmbgrnb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hammf.cn/Article/details/gtrnyakntr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zycfv.cn/Article/details/gtydprmhes.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.dashuyun.cn/Article/details/gtnolefpms.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj20258888.top/Article/details/gtkvpasfan.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hnxiangtu.top/Article/details/gtbftlfwlc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hnqzz.top/Article/details/gtgvyecsvy.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtjyfhujuq.html

M. 命令行 / 进程 / 环境
来源：http://dali.316326.xyz/Article/details/gtafzulbxv.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtgrrsedca.html

[M01] 读取命令行参数
来源：http://dali.ybcxt.top/Article/details/gtzubtbaoq.html

Py:   sys.argv[1:]
来源：http://dali.birdmap.top/Article/details/gthrruxlmr.html

PHP:  $argv;  $argc;
来源：http://dali.fengsongda.top/Article/details/gtlkiapfae.html

JS:   process.argv.slice(2)
来源：http://dali.cdnleiting.top/Article/details/gtosnmkhct.html

TS:   process.argv.slice(2)
来源：http://dali.shangyingyoupin.top/Article/details/gtkzfntipl.html

Java: args 数组（main 方法参数）
来源：http://dali.nanxinkj.top/Article/details/gtstcnybhm.html

Go:   os.Args[1:]
来源：http://dali.jqgfzy.top/Article/details/gtkrfesqff.html

Ruby: ARGV
来源：http://dali.hongshengwenyu.top/Article/details/gtkrtcsyki.html

C#:   args 数组（Main 方法参数）
来源：http://dali.mhx1999.top/Article/details/gtntwwackl.html

[M02] 读取环境变量
来源：http://dali.iojbl.cn/Article/details/gtgcbadzrj.html

Py:   os.environ.get("HOME")
来源：http://dali.hywenlv.cn/Article/details/gthosgvsym.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yueranfly.top/Article/details/gtrnjsppgh.html

JS:   process.env.HOME
来源：http://dali.yongpay.top/Article/details/gtethobmht.html

TS:   process.env.HOME
来源：http://dali.0kj1m.cn/Article/details/gtynwqducu.html

Java: System.getenv("HOME")
来源：http://dali.zdqjudy.top/Article/details/gtshvipwoq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gtgkdrchyd.html

Ruby: ENV["HOME"]
来源：http://dali.ivvv.top/Article/details/gtexftwuux.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.smart0.xyz/Article/details/gtqeaaklho.html

[M03] 执行外部命令
来源：http://dali.ivvv.top/Article/details/gtnqgcymzj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gtzqlcylbo.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hfpthk.cn/Article/details/gtuunazfcz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.aizwys.cn/Article/details/gtfmmniejp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jianghu66.top/Article/details/gtlweycoau.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.smart0.xyz/Article/details/gttdxrrrgs.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.bjfxy.top/Article/details/gtvywwatnb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.redwolf501.top/Article/details/gtkepafswr.html

C#:   Process.Start("ls", "-l");
来源：http://dali.0kj1m.cn/Article/details/gtsirrauxu.html

[M04] 获取当前工作目录
来源：http://dali.zhiwuduotai.top/Article/details/gtecirfysa.html

Py:   os.getcwd()
来源：http://dali.dianchejie.cn/Article/details/gtsgwckzkt.html

PHP:  getcwd();
来源：http://dali.jqgufenzy.top/Article/details/gtoodyleql.html

JS:   process.cwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpyhaqjir.html

TS:   process.cwd()
来源：http://dali.ehwqpu.com/Article/details/gtfqdriegv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.wangshuangyany.cn/Article/details/gtljlzypqd.html

Go:   os.Getwd()
来源：http://dali.daxiang520.top/Article/details/gtszckgemf.html

Ruby: Dir.pwd
来源：http://dali.ywan-chungtsiang.top/Article/details/gttkdrndyl.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.wangshuangyany.cn/Article/details/gtrvatsovz.html

[M05] 设置退出码
来源：http://dali.yj20258888.top/Article/details/gtrwqrmddt.html

Py:   sys.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gttoyotyct.html

PHP:  exit(1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcmeimyov.html

JS:   process.exit(1)
来源：http://dali.316326.xyz/Article/details/gtuavmkuix.html

TS:   process.exit(1)
来源：http://dali.mhx1999.top/Article/details/gtnzeatctc.html

Java: System.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gtzdifpmhb.html

Go:   os.Exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gtpwswghnd.html

Ruby: exit 1
来源：http://dali.cashguo.top/Article/details/gtyoqdrigf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zdqjudy.top/Article/details/gtecwvxnqv.html

[M06] 向标准错误输出
来源：http://dali.zhongyouzk.top/Article/details/gtjtvwcoed.html

Py:   print("err", file=sys.stderr)
来源：http://dali.fengsongda.top/Article/details/gtrtefzogs.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.aibaodan.cn/Article/details/gthhmrzsrq.html

JS:   console.error("err")
来源：http://dali.hnqzz.top/Article/details/gtstnljbyx.html

TS:   console.error("err")
来源：http://dali.cucudq.cn/Article/details/gtlbthdqvh.html

Java: System.err.println("err")
来源：http://dali.wangdashe.top/Article/details/gtxotfhlpx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xziqi.cn/Article/details/gtnwkxsxyf.html

Ruby: warn "err"
来源：http://dali.ppjwa.cn/Article/details/gtphbgqlmg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jqgfzy.top/Article/details/gtiqfxygwj.html

[M07] 判断是否为主入口
来源：http://dali.sysykeji.top/Article/details/gttjfupqwp.html

Py:   if __name__ == "__main__":
来源：http://dali.yonumen.top/Article/details/gterdpurtw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yj20258.top/Article/details/gttxmzxgwl.html

JS:   require.main === module
来源：http://dali.yj20258.top/Article/details/gtdpdoulnt.html

TS:   require.main === module
来源：http://dali.jinqigfzy.top/Article/details/gtlwktnfzn.html

Java: public static void main(String[] args)
来源：http://dali.andypj.xyz/Article/details/gtjgszkvrf.html

Go:   func main()
来源：http://dali.tanke756.top/Article/details/gtceobkeoh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xuetiantiany.cn/Article/details/gtpuujdyvm.html

C#:   static void Main(string[] args)
来源：http://dali.guowangkeji.top/Article/details/gtyqljzpup.html

[M08] 获取系统与运行时信息
来源：http://dali.sxryk.cn/Article/details/gtklqrkwqf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj20258.top/Article/details/gtevoyisyr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.9152youxi.cn/Article/details/gtnrhoqzjz.html

JS:   process.platform;  process.version
来源：http://dali.jinghuilouyu.cn/Article/details/gtoapczbic.html

TS:   process.platform;  process.version
来源：http://dali.316326.xyz/Article/details/gtovxjuqsy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.c1oappe.top/Article/details/gtwjpiuees.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ybcxt.top/Article/details/gtkjkfwjfn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinqigfzy.top/Article/details/gtbrlqgthj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ybcxt.top/Article/details/gtackabbzl.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtzajhmikc.html

N. 数据结构与算法
来源：http://dali.cheryme.top/Article/details/gtuiwenkvv.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtnqweaniw.html

[N01] 二分查找（有序数组）
来源：http://dali.feifeiyinyue.top/Article/details/gtgyqngote.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtoecrwgeo.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nanxinkj.top/Article/details/gtwyfmcisd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuanzhike.top/Article/details/gtdjhmllqi.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sysykeji.top/Article/details/gtnszffdle.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtzoyfedeh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtkbjhcpug.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.birdmap.top/Article/details/gtqoygkdrs.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsnoxrurw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenlongwang.top/Article/details/gtynvnpkur.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhixingplan.top/Article/details/gtomhbpooi.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhoulong.xyz/Article/details/gtbfqafmvu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tanke756.top/Article/details/gtlokiizwq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.quarkkingdee.top/Article/details/gtkayptpob.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhixingplan.top/Article/details/gtmafckeah.html

Go:   slices.Sort(arr)
来源：http://dali.guowangkeji.top/Article/details/gtqapjqhgb.html

Ruby: arr.sort
来源：http://dali.jqgfzy.top/Article/details/gtpygngmmc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yongpay.top/Article/details/gttzqirpkh.html

[N03] 快速排序（分治示例）
来源：http://dali.yangfankeji.com/Article/details/gtkminpogi.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zdqjudy.top/Article/details/gtqkqwvlpb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xuanzx.com/Article/details/gtyrauwhlb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hysaishi.cn/Article/details/gtnewjnjof.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinghuilouyu.cn/Article/details/gtqeffmhmv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gtusnwbzqc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.dianchejie.cn/Article/details/gtcnopdkbz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xylfe.cn/Article/details/gtwylekiqe.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.aizwys.cn/Article/details/gtvcbkwrwg.html

[N04] 斐波那契数列
来源：http://dali.sxryk.cn/Article/details/gtzyuyzuop.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ppjwa.cn/Article/details/gtfbzjtirc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shuidangran.top/Article/details/gtvcafyrfi.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.svipenyu.cn/Article/details/gttugeqtcs.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenzaomai.com/Article/details/gthhgvibad.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.meibo888.top/Article/details/gtutlaunjw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xylfe.cn/Article/details/gtwvsjvmhw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.daria6918.cn/Article/details/gtqbgrmbwv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jyoumei.cn/Article/details/gtqzhvghuh.html

[N05] 最大公约数
来源：http://dali.bjfxy.top/Article/details/gttldfmefx.html

Py:   math.gcd(a, b)
来源：http://dali.iojbl.cn/Article/details/gtywlbrtcb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hammf.cn/Article/details/gtfubpfdjf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jianghu66.top/Article/details/gtcqvleljg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhiwuduotai.top/Article/details/gtsgzxvdlk.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hysaishi.cn/Article/details/gtajdkfmyc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.pengpengdd.cyou/Article/details/gtilfgzhbb.html

Ruby: a.gcd(b)
来源：http://dali.hongshengwenyu.top/Article/details/gtsefrvsca.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shangyingyoupin.top/Article/details/gtujclgmrz.html

[N06] 判断回文字符串
来源：http://dali.jianghu66.top/Article/details/gtjlvtunla.html

Py:   s == s[::-1]
来源：http://dali.nanxinkj.top/Article/details/gtfzeidxyj.html

PHP:  $s === strrev($s);
来源：http://dali.gotoacloud.top/Article/details/gtzojicbug.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gtthityxla.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gtyblegenw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhixingplan.top/Article/details/gtopnysonb.html

Go:   // 双指针从两端比较
来源：http://dali.pycfn.com/Article/details/gtpwxacviu.html

Ruby: s == s.reverse
来源：http://dali.zhiwuduotai.top/Article/details/gtqbmkjmgg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.wangshuangyany.cn/Article/details/gtuwexqazr.html

[N07] 两数之和（返回下标）
来源：http://dali.guowangkeji.top/Article/details/gtyiwiavwh.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jiagoushi.top/Article/details/gtsvedsjua.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.wangdashe.top/Article/details/gtnadmtfbd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gotoacloud.top/Article/details/gtxabkzpid.html

TS:   // 手写 Map<string, number>
来源：http://dali.xziqi.cn/Article/details/gtmjkcxcof.html

Java: // 手写 HashMap
来源：http://dali.nanxinkj.top/Article/details/gtoqgzkuvm.html

Go:   // 手写 map[int]int
来源：http://dali.sweek.top/Article/details/gtgbmlnrjh.html

Ruby: // 手写 Hash
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvppqhxdt.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yj20258.top/Article/details/gtohjgduhq.html

[N08] 生成全排列
来源：http://dali.mhx1999.top/Article/details/gtuvfimwfl.html

Py:   itertools.permutations(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsyjatttg.html

PHP:  // 手写递归交换
来源：http://dali.jyoumei.cn/Article/details/gtrmnteyqq.html

JS:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gtymnmjnxo.html

TS:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gtiikcqfto.html

Java: // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtoffugnqm.html

Go:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gtzcadvszz.html

Ruby: arr.permutation.to_a
来源：http://dali.yongpay.top/Article/details/gtgrmwdafu.html

C#:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gtaxunbcwv.html

[N09] 栈与队列
来源：http://dali.dianchejie.cn/Article/details/gtunlnwhnb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jianghu66.top/Article/details/gtuwnrbmsi.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.andypj.xyz/Article/details/gtvzavncac.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nanxuanxn.top/Article/details/gtqbxehgnf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhoulong.xyz/Article/details/gtmogqdfjq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.pengpengdd.cyou/Article/details/gttvjuydzb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cheryme.top/Article/details/gtvllirzpx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.smart0.xyz/Article/details/gtwbhjtxwc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.nanxuanxn.top/Article/details/gtsmcfzzyj.html

[N10] 链表节点定义
来源：http://dali.pycfn.com/Article/details/gtolyuxirz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hongshengwenyu.top/Article/details/gtbyhwqhvb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gzhubu.top/Article/details/gtcszhtfsx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ybcxt.top/Article/details/gtyjboezzp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.meibo888.top/Article/details/gtbmnfibvq.html

Java: class Node { int v; Node next; }
来源：http://dali.wangdashe.top/Article/details/gtkufehvxz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.guowangkeji.top/Article/details/gtvidhxoms.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhengqikj.top/Article/details/gtyypivtoo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zycfv.cn/Article/details/gtoqdwgaqe.html

[N11] 二叉树中序遍历
来源：http://dali.bjfxy.top/Article/details/gthqyehfmn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.redwolf501.top/Article/details/gtmnjzzybw.html

PHP:  // 手写递归函数
来源：http://dali.aibaodan.cn/Article/details/gtrsdjkumj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.andypj.xyz/Article/details/gtmcxwxoko.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gaohongyu789.top/Article/details/gtnjnrrlyj.html

Java: // 手写递归
来源：http://dali.aizwys.cn/Article/details/gtsfnvktgg.html

Go:   // 手写递归
来源：http://dali.hfpthk.cn/Article/details/gtdbjcmzew.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jyoumei.cn/Article/details/gtrozowsnz.html

C#:   // 手写递归
来源：http://dali.cashguo.top/Article/details/gtjthnvlpa.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yvedp.cn/Article/details/gttvarheul.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.sweek.top/Article/details/gtdzkhjaxz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yueranfly.top/Article/details/gtdolyohjl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.feifeiyinyue.top/Article/details/gtbnumdogr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cashguo.top/Article/details/gtvenqinfb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sysykeji.top/Article/details/gtvcqgbdlf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.316326.xyz/Article/details/gtgfxngbps.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sysykeji.top/Article/details/gtjuwodtxw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.9152youxi.cn/Article/details/gtachkirbt.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtqaekssjb.html

O. 并发与异步
来源：http://dali.hysaishi.cn/Article/details/gtdpdtjqrq.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtjbkeilfu.html

[O01] 启动一个线程
来源：http://dali.dashuyun.cn/Article/details/gtxnmegdqy.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.aizwys.cn/Article/details/gtmorgqpvf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.nwbrower.top/Article/details/gtcrqeivxq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shangyingyoupin.top/Article/details/gtttklybdu.html

TS:   // 同 JS
来源：http://dali.hnxiangtu.top/Article/details/gtxecveceb.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhengqikj.top/Article/details/gtjgvitvnx.html

Go:   go f()
来源：http://dali.sysykeji.top/Article/details/gtjmqogpzc.html

Ruby: Thread.new { f }
来源：http://dali.svipenyu.cn/Article/details/gtmjppwjdh.html

C#:   Task.Run(() => F());
来源：http://dali.chenlongwang.top/Article/details/gtmpjfhjzy.html

[O02] 使用线程池
来源：http://dali.chenjidiqi.icu/Article/details/gtsrbhzedq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cucudq.cn/Article/details/gtdjhvkjhu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jianghu66.top/Article/details/gtimqatbep.html

JS:   // worker_threads 线程池
来源：http://dali.c1oappe.top/Article/details/gtermtqvhj.html

TS:   // worker_threads 线程池
来源：http://dali.haohaochexian.top/Article/details/gtxmofcnpi.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ivvv.top/Article/details/gtwdifjqgu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuzrukvxl.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.chenzaomai.com/Article/details/gtwuneqisc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cqqwz.cn/Article/details/gtjofgblqv.html

[O03] 加锁保护共享数据
来源：http://dali.cashguo.top/Article/details/gtdgrabdkg.html

Py:   with lock: shared += 1
来源：http://dali.yj20258.top/Article/details/gtcihqyzpk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoniksysi.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.redwolf501.top/Article/details/gtuwchakkh.html

TS:   // 同 JS
来源：http://dali.xziqi.cn/Article/details/gtqchkkgel.html

Java: synchronized (this) { shared++; }
来源：http://dali.tianlin.xyz/Article/details/gtaevpxpcb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.pengpengdd.cyou/Article/details/gtuncwrazi.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xuanzx.com/Article/details/gtjpayjkpd.html

C#:   lock (gate) { shared++; }
来源：http://dali.nwbrower.top/Article/details/gtefpgwmtt.html

[O04] 定义异步函数并等待
来源：http://dali.fzhhl.top/Article/details/gtlumhpoar.html

Py:   async def f():⏎    await g()
来源：http://dali.yj20258.top/Article/details/gtrfflzxnw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.vqdsnc.cn/Article/details/gtasotwyve.html

JS:   async function f() { await g(); }
来源：http://dali.shuidangran.top/Article/details/gtkuuvnqug.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.vqdsnc.cn/Article/details/gttlbhlvje.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.chenlongwang.top/Article/details/gtpgrsqbyd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinqigufen.top/Article/details/gtshslwfkn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yueranfly.top/Article/details/gtzidwtuzc.html

C#:   async Task F() { await G(); }
来源：http://dali.cheryme.top/Article/details/gtshejrwdb.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinqigfzy.top/Article/details/gtghkorery.html

Py:   asyncio.gather(*tasks)
来源：http://dali.nanxuanxn.top/Article/details/gtvoppgfgq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shuidangran.top/Article/details/gtvqxpncur.html

JS:   await Promise.all(tasks)
来源：http://dali.ydzc1.top/Article/details/gtwklehzhk.html

TS:   await Promise.all(tasks)
来源：http://dali.zhengqikj.top/Article/details/gtmwartepn.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.aibaodan.cn/Article/details/gtbgtygxai.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.daria6918.cn/Article/details/gtuodmbywy.html

Ruby: threads.map(&:join)
来源：http://dali.hongshengwenyu.top/Article/details/gtfwaytwqv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinqigufen.top/Article/details/gtdbmzikbn.html

[O06] 使用进程池
来源：http://dali.yj20258.top/Article/details/gtreretibq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.tianlin.xyz/Article/details/gtxxhamtev.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.guowangkeji.top/Article/details/gtvnnthqox.html

JS:   // child_process / cluster 模块
来源：http://dali.wangshuangyany.cn/Article/details/gthuwxcqql.html

TS:   // child_process / cluster 模块
来源：http://dali.gzhubu.top/Article/details/gtbgphgteu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.fengsongda.top/Article/details/gtfadlmdfd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.havefunace.top/Article/details/gtxmqvixlg.html

Ruby: // fork 块
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdsrnvzmp.html

C#:   Parallel.For
来源：http://dali.zhengqikj.top/Article/details/gtschsjcki.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gthynqiqqu.html

P. 常用工具函数
来源：http://dali.hysaishi.cn/Article/details/gtabnmkkmq.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtoccmnags.html

[P01] 生成 UUID
来源：http://dali.zhengqikj.top/Article/details/gtgcttuqbr.html

Py:   str(uuid.uuid4())
来源：http://dali.yonumen.top/Article/details/gtsyfmqsqq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.vqdsnc.cn/Article/details/gtzsfwztqq.html

JS:   crypto.randomUUID()
来源：http://dali.shuidangran.top/Article/details/gtjzntdzcp.html

TS:   crypto.randomUUID()
来源：http://dali.jinqigfzy.top/Article/details/gtzptrmtyt.html

Java: UUID.randomUUID().toString()
来源：http://dali.daria6918.cn/Article/details/gtbfluisic.html

Go:   // 用 github.com/google/uuid
来源：http://dali.mhx1999.top/Article/details/gththcxgrl.html

Ruby: SecureRandom.uuid
来源：http://dali.wangdashe.top/Article/details/gtcripysiv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xinyue.icu/Article/details/gtdnfyowen.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yuanzhike.top/Article/details/gteulqzmsy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinqigufen.top/Article/details/gtvjzbiirp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.tianlin.xyz/Article/details/gtuccmvzet.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdmrksdom.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yuxming.cn/Article/details/gtpezhtvoz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.bjfxy.top/Article/details/gtsagseoty.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinghuilouyu.cn/Article/details/gtnafibatx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtdznexkwf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.andypj.xyz/Article/details/gtfnudbhdt.html

[P03] 生成短随机字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtwnsdpqtc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.snrcjt.cn/Article/details/gttqoachcl.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sysykeji.top/Article/details/gtxgfedfvq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daria6918.cn/Article/details/gtucwnwbbx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pycfn.com/Article/details/gtxaysxalm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.snrcjt.cn/Article/details/gtlpdiomxh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.quarkkingdee.top/Article/details/gtexdmoujt.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gtyldpfzeg.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.pycfn.com/Article/details/gtbdchrykt.html

[P04] 求长度
来源：http://dali.havefunace.top/Article/details/gtmjoqvvrg.html


<!-- 参考信息 -->