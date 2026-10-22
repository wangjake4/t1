代发 wailian999

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jianghu66.top/Article/details/gtseiluymk.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.aizwys.cn/Article/details/gtzqjlpvhv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hammf.cn/Article/details/gtdfxvmpuq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.svipenyu.cn/Article/details/gtbzprsrqs.html

[L07] 处理 HTTP 状态码
来源：http://dali.316326.xyz/Article/details/gtpbpnckfx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gaohongyu789.top/Article/details/gtlqasnvyd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hywenlv.cn/Article/details/gthrlfhndd.html

JS:   resp.ok;  resp.status
来源：http://dali.meibo888.top/Article/details/gtbxsfdomr.html

TS:   resp.ok;  resp.status
来源：http://dali.sysykeji.top/Article/details/gtptjcvjpi.html

Java: resp.statusCode()
来源：http://dali.sufxvd.cn/Article/details/gtlmveknbj.html

Go:   resp.StatusCode
来源：http://dali.sweek.top/Article/details/gtaomnbksq.html

Ruby: resp.code.to_i
来源：http://dali.yj20258888.top/Article/details/gtlthspcjc.html

C#:   (int)resp.StatusCode
来源：http://dali.nwbrower.top/Article/details/gtaabcpojp.html

[L08] 并发请求多个地址
来源：http://dali.sxryk.cn/Article/details/gtduncbqxz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zdqjudy.top/Article/details/gtqzbcrpzv.html

PHP:  curl_multi_init() 系列
来源：http://dali.hongshengwenyu.top/Article/details/gtciybeyae.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gtwzrhxrbk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.smart0.xyz/Article/details/gtthciboel.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.haohaochexian.top/Article/details/gtatujvfvs.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ywan-chungtsiang.top/Article/details/gtffezjthy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.tian-w.cn/Article/details/gtqvlzygdy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gtkphtqqej.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtrbbidjvt.html

M. 命令行 / 进程 / 环境
来源：http://dali.bjfxy.top/Article/details/gtksvhzzew.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtoqtohmqz.html

[M01] 读取命令行参数
来源：http://dali.yanxiufei.cn/Article/details/gtvbwjioiq.html

Py:   sys.argv[1:]
来源：http://dali.svipenyu.cn/Article/details/gtkwwtbvgg.html

PHP:  $argv;  $argc;
来源：http://dali.yj20258.top/Article/details/gtgvhyyijx.html

JS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gtdwfxbqsg.html

TS:   process.argv.slice(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjuwlczxs.html

Java: args 数组（main 方法参数）
来源：http://dali.ivvv.top/Article/details/gtxbfrxdjm.html

Go:   os.Args[1:]
来源：http://dali.shzxlz.cn/Article/details/gtcajekivp.html

Ruby: ARGV
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwhlikkpu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yuxming.cn/Article/details/gtgmmjftdv.html

[M02] 读取环境变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiopprkyq.html

Py:   os.environ.get("HOME")
来源：http://dali.quarkkingdee.top/Article/details/gtpasugrxw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.fzhhl.top/Article/details/gtjwwjorwz.html

JS:   process.env.HOME
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbgvfunsr.html

TS:   process.env.HOME
来源：http://dali.iojbl.cn/Article/details/gtjkbanaka.html

Java: System.getenv("HOME")
来源：http://dali.yvedp.cn/Article/details/gtjwenslzg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zycfv.cn/Article/details/gtmryjatvy.html

Ruby: ENV["HOME"]
来源：http://dali.sysykeji.top/Article/details/gtwyancqor.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gtzmtaxzii.html

[M03] 执行外部命令
来源：http://dali.daria6918.cn/Article/details/gtmnblcefn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenlongwang.top/Article/details/gtxsomynoi.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.316326.xyz/Article/details/gtpawaouzq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbucpcsbj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hfpthk.cn/Article/details/gtjbibsgow.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cdnleiting.top/Article/details/gtpughuvyk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.chenzaomai.com/Article/details/gtrmnuoyjb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.0kj1m.cn/Article/details/gtofydpafw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.aizwys.cn/Article/details/gtqcyvbqeo.html

[M04] 获取当前工作目录
来源：http://dali.feifeiyinyue.top/Article/details/gtsdwiykjw.html

Py:   os.getcwd()
来源：http://dali.xinyue.icu/Article/details/gttdytajlv.html

PHP:  getcwd();
来源：http://dali.hfpthk.cn/Article/details/gtbigtudpg.html

JS:   process.cwd()
来源：http://dali.chenzaomai.com/Article/details/gtehcypyhp.html

TS:   process.cwd()
来源：http://dali.fzhhl.top/Article/details/gtuoxjtnrk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.pengpengdd.cyou/Article/details/gtzdrmodqx.html

Go:   os.Getwd()
来源：http://dali.ppjwa.cn/Article/details/gtbsnwnfjf.html

Ruby: Dir.pwd
来源：http://dali.tian-w.cn/Article/details/gtuhnxdksu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hysaishi.cn/Article/details/gtphypjbpo.html

[M05] 设置退出码
来源：http://dali.hnqzz.top/Article/details/gtwjrhzftb.html

Py:   sys.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtlxsizqcg.html

PHP:  exit(1);
来源：http://dali.chenjidiqi.icu/Article/details/gtntuhgpmx.html

JS:   process.exit(1)
来源：http://dali.nwbrower.top/Article/details/gtkxoynrjg.html

TS:   process.exit(1)
来源：http://dali.cucudq.cn/Article/details/gtenhqkiye.html

Java: System.exit(1)
来源：http://dali.yongpay.top/Article/details/gtjsrcmblu.html

Go:   os.Exit(1)
来源：http://dali.zhengqikj.top/Article/details/gtudprcnuv.html

Ruby: exit 1
来源：http://dali.hysaishi.cn/Article/details/gtsrdeqrni.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nwbrower.top/Article/details/gtkurqotka.html

[M06] 向标准错误输出
来源：http://dali.shuidangran.top/Article/details/gtffqcbqyn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yongpay.top/Article/details/gtejqjejus.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.wangshuangyany.cn/Article/details/gtyhkiczhb.html

JS:   console.error("err")
来源：http://dali.tian-w.cn/Article/details/gtiwnsqfrl.html

TS:   console.error("err")
来源：http://dali.jqgfzy.top/Article/details/gtmlijuloa.html

Java: System.err.println("err")
来源：http://dali.jqgfzy.top/Article/details/gttlcilhpn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.wangdashe.top/Article/details/gthpwwfpzi.html

Ruby: warn "err"
来源：http://dali.jlsjyb.cn/Article/details/gtwqytqwlo.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xuetiantiany.cn/Article/details/gtpjwbogzs.html

[M07] 判断是否为主入口
来源：http://dali.0kj1m.cn/Article/details/gtodogkmym.html

Py:   if __name__ == "__main__":
来源：http://dali.jyoumei.cn/Article/details/gtromgdaxh.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xziqi.cn/Article/details/gtiqhmhlbm.html

JS:   require.main === module
来源：http://dali.yuxming.cn/Article/details/gtnvlnhkgv.html

TS:   require.main === module
来源：http://dali.sweek.top/Article/details/gteszzaufg.html

Java: public static void main(String[] args)
来源：http://dali.0kj1m.cn/Article/details/gtypaigdvd.html

Go:   func main()
来源：http://dali.fengsongda.top/Article/details/gtmlsnwwjp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gtregbdqag.html

C#:   static void Main(string[] args)
来源：http://dali.feifeiyinyue.top/Article/details/gthrjspmqd.html

[M08] 获取系统与运行时信息
来源：http://dali.dianchejie.cn/Article/details/gtazmftybr.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ivvv.top/Article/details/gtwjhcbvft.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xuetiantiany.cn/Article/details/gteiqzuiok.html

JS:   process.platform;  process.version
来源：http://dali.nwbrower.top/Article/details/gtsnmudxij.html

TS:   process.platform;  process.version
来源：http://dali.redwolf501.top/Article/details/gtigvqgtox.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.smart0.xyz/Article/details/gtafjaqzyr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.pengpengdd.cyou/Article/details/gtwdeqdftw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xinyue.icu/Article/details/gtqiykwdmo.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jlsjyb.cn/Article/details/gtovaddnmj.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtmgcutroc.html

N. 数据结构与算法
来源：http://dali.jyoumei.cn/Article/details/gtjumyrotd.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtjmrlfjav.html

[N01] 二分查找（有序数组）
来源：http://dali.shanyushiyangtech.top/Article/details/gtbnffkiwa.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlsbobrqc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gtmzrvlhsy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.bjfxy.top/Article/details/gtjcygeuwt.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ydzc1.top/Article/details/gtjkkdbmmm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpwstbmrk.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtqfmlnrdt.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hywenlv.cn/Article/details/gtekcdkdzc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtphxkcfiq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhixingplan.top/Article/details/gtckluutqe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258888.top/Article/details/gtsqzgwuvz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinqigfzy.top/Article/details/gtgwsweypb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrdnyxcvu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aibaodan.cn/Article/details/gtnkmlkvic.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shzxlz.cn/Article/details/gtoccleown.html

Go:   slices.Sort(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtylcuhxnk.html

Ruby: arr.sort
来源：http://dali.jinqigfzy.top/Article/details/gtnkgjlggz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.guowangkeji.top/Article/details/gtxssxabbm.html

[N03] 快速排序（分治示例）
来源：http://dali.daria6918.cn/Article/details/gtaguhxdex.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.c1oappe.top/Article/details/gtvhyperrx.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yueranfly.top/Article/details/gtywkwdmbg.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangshuangyany.cn/Article/details/gtzyluuvke.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pengpengdd.cyou/Article/details/gtzismggzt.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gtognsbjcs.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sysykeji.top/Article/details/gtkyjrowpr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgczuxlnb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenjidiqi.icu/Article/details/gtjzhclfhe.html

[N04] 斐波那契数列
来源：http://dali.cheryme.top/Article/details/gtekzrondj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yueranfly.top/Article/details/gtwxvbvmdz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yanxiufei.cn/Article/details/gtmtmufnjj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gtoeyfxfpq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gtmcxtfdxo.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shangyingyoupin.top/Article/details/gtjsuhntof.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.guowangkeji.top/Article/details/gtaetdfqhl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zycfv.cn/Article/details/gtcsiunwgb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gtxicfuqqj.html

[N05] 最大公约数
来源：http://dali.meibo888.top/Article/details/gtmedndbpt.html

Py:   math.gcd(a, b)
来源：http://dali.tian-w.cn/Article/details/gtyizgolzv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yongpay.top/Article/details/gtnrfeojqi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nwbrower.top/Article/details/gtcexssomc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yanxiufei.cn/Article/details/gtpjhklnwy.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.316326.xyz/Article/details/gtapwyibcy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.nwbrower.top/Article/details/gtcanppebo.html

Ruby: a.gcd(b)
来源：http://dali.xuanzx.com/Article/details/gtwzhftjhj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yuanzhike.top/Article/details/gtdibhdhrp.html

[N06] 判断回文字符串
来源：http://dali.c1oappe.top/Article/details/gtnaafthwf.html

Py:   s == s[::-1]
来源：http://dali.zhoulong.xyz/Article/details/gtlsqqodyc.html

PHP:  $s === strrev($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiyqvhpjp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gtlgjewmcp.html

TS:   s === [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gtxbmkawya.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cqqwz.cn/Article/details/gtqjihjwir.html

Go:   // 双指针从两端比较
来源：http://dali.yongpay.top/Article/details/gtxiyebdxp.html

Ruby: s == s.reverse
来源：http://dali.xinyue.icu/Article/details/gtoauzeoxd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gzhubu.top/Article/details/gtnuijqxpe.html

[N07] 两数之和（返回下标）
来源：http://dali.kuanghao11.cn/Article/details/gtzpabhosp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hywenlv.cn/Article/details/gtmjnetvoa.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yuxming.cn/Article/details/gtxbrkgomf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shuidangran.top/Article/details/gtdoegcenb.html

TS:   // 手写 Map<string, number>
来源：http://dali.yuanzhike.top/Article/details/gtisyqndpq.html

Java: // 手写 HashMap
来源：http://dali.9152youxi.cn/Article/details/gtjfngenkl.html

Go:   // 手写 map[int]int
来源：http://dali.hfpthk.cn/Article/details/gtinmvjqrn.html

Ruby: // 手写 Hash
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcpkgsxeq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.havefunace.top/Article/details/gtrgrupovn.html

[N08] 生成全排列
来源：http://dali.fengsongda.top/Article/details/gthbesupmh.html

Py:   itertools.permutations(arr)
来源：http://dali.xuanzx.com/Article/details/gtvbdsbjxf.html

PHP:  // 手写递归交换
来源：http://dali.daria6918.cn/Article/details/gtafzxtpdp.html

JS:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtxsqjkmjl.html

TS:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gtiamiulbv.html

Java: // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gtlsndfyck.html

Go:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gtsafhoptb.html

Ruby: arr.permutation.to_a
来源：http://dali.zhongyouzk.top/Article/details/gtbtlauynj.html

C#:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gttffveepj.html

[N09] 栈与队列
来源：http://dali.xuetiantiany.cn/Article/details/gtkyduzlui.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yj202588.top/Article/details/gtkucdkacj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yueranfly.top/Article/details/gtnlmmgyoc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gtvydfopcr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.dashuyun.cn/Article/details/gtscozovlo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.snrcjt.cn/Article/details/gtivlhubix.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinghuilouyu.cn/Article/details/gtzsjpmsns.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cheryme.top/Article/details/gtrfmeqxhe.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cucudq.cn/Article/details/gthupfxscu.html

[N10] 链表节点定义
来源：http://dali.birdmap.top/Article/details/gthmtzogvk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.pycfn.com/Article/details/gtvcionjrj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcyvquiqv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.0kj1m.cn/Article/details/gtxkcfjcnn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmpfjeqkt.html

Java: class Node { int v; Node next; }
来源：http://dali.birdmap.top/Article/details/gtckoeqksc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.tian-w.cn/Article/details/gtmwhjzmpx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.9152youxi.cn/Article/details/gtfuzfspkx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gaohongyu789.top/Article/details/gtdzpdoszo.html

[N11] 二叉树中序遍历
来源：http://dali.jqgufenzy.top/Article/details/gtaehwtxxd.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.aizwys.cn/Article/details/gtmwiueibq.html

PHP:  // 手写递归函数
来源：http://dali.zhengqikj.top/Article/details/gtcuoqisqu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sufxvd.cn/Article/details/gtuayhzgvl.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.fzhhl.top/Article/details/gttozyboss.html

Java: // 手写递归
来源：http://dali.shangyingyoupin.top/Article/details/gtelulcazo.html

Go:   // 手写递归
来源：http://dali.cucudq.cn/Article/details/gtplsxzfgy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.guannengcc.top/Article/details/gtfwsehsty.html

C#:   // 手写递归
来源：http://dali.pycfn.com/Article/details/gtzdjssxai.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sweek.top/Article/details/gtatvlfxhk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gtcbtebbei.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zycfv.cn/Article/details/gthgfqlpua.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.316326.xyz/Article/details/gttiwiuzth.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.vqdsnc.cn/Article/details/gtyyvicydm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.feifeiyinyue.top/Article/details/gtvpdvsosx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.fengsongda.top/Article/details/gtvyttbunh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtettfzdfg.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj202588.top/Article/details/gtdhfcogug.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtlxqbfeir.html

O. 并发与异步
来源：http://dali.chenzaomai.com/Article/details/gtnxalfhnp.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtvdzlogwk.html

[O01] 启动一个线程
来源：http://dali.hnxiangtu.top/Article/details/gtzomplkyw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.redwolf501.top/Article/details/gtqjsguddz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xinyue.icu/Article/details/gthopjhyci.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ppjwa.cn/Article/details/gtzuzyxgrr.html

TS:   // 同 JS
来源：http://dali.hywenlv.cn/Article/details/gtxumcyqha.html

Java: new Thread(() -> f()).start()
来源：http://dali.xuanzx.com/Article/details/gtogszuktc.html

Go:   go f()
来源：http://dali.sweek.top/Article/details/gtxlnhfova.html

Ruby: Thread.new { f }
来源：http://dali.yj20258.top/Article/details/gtajjmewbw.html

C#:   Task.Run(() => F());
来源：http://dali.ybcxt.top/Article/details/gtynilhauq.html

[O02] 使用线程池
来源：http://dali.kuanghao11.cn/Article/details/gtlnledzeg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.sxryk.cn/Article/details/gtxctzakku.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hysaishi.cn/Article/details/gtvrwqsnzx.html

JS:   // worker_threads 线程池
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcasmbjdm.html

TS:   // worker_threads 线程池
来源：http://dali.gogol.net.cn/Article/details/gtxssayfox.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.gaohongyu789.top/Article/details/gtvmonaggz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.chenjidiqi.icu/Article/details/gtqyrurfld.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.havefunace.top/Article/details/gthcelgons.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zdqjudy.top/Article/details/gtjanurbfh.html

[O03] 加锁保护共享数据
来源：http://dali.zycfv.cn/Article/details/gtwgpymqei.html

Py:   with lock: shared += 1
来源：http://dali.jqgfzy.top/Article/details/gtcxkgzzpd.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.chenzaomai.com/Article/details/gthlrchlfo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.quarkkingdee.top/Article/details/gtktyqstnv.html

TS:   // 同 JS
来源：http://dali.gogol.net.cn/Article/details/gtilkfodha.html

Java: synchronized (this) { shared++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzoualekr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.snrcjt.cn/Article/details/gtiuyqzbmb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.nanxuanxn.top/Article/details/gtrmcdxdbh.html

C#:   lock (gate) { shared++; }
来源：http://dali.hywenlv.cn/Article/details/gtyowqbjgz.html

[O04] 定义异步函数并等待
来源：http://dali.xziqi.cn/Article/details/gtgpebabjn.html

Py:   async def f():⏎    await g()
来源：http://dali.vqdsnc.cn/Article/details/gtrrledmsb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.havefunace.top/Article/details/gtwukchyfn.html

JS:   async function f() { await g(); }
来源：http://dali.daxiang520.top/Article/details/gtzgtkhavx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhengqikj.top/Article/details/gtpqnhlbnu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sysykeji.top/Article/details/gtqcugdhnq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yueranfly.top/Article/details/gttnknpyyj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.fengsongda.top/Article/details/gtpbebaqfg.html

C#:   async Task F() { await G(); }
来源：http://dali.gogol.net.cn/Article/details/gtoagffnbk.html

[O05] 并发执行并等待全部完成
来源：http://dali.nwbrower.top/Article/details/gtaonlvpxr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.meibo888.top/Article/details/gtixxsfrwy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.birdmap.top/Article/details/gtartaqjai.html

JS:   await Promise.all(tasks)
来源：http://dali.iojbl.cn/Article/details/gtawcoqyzi.html

TS:   await Promise.all(tasks)
来源：http://dali.zhiwuduotai.top/Article/details/gtsxclghbi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cqqwz.cn/Article/details/gtaqwlqjch.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.pengpengdd.cyou/Article/details/gtpscfmbsf.html

Ruby: threads.map(&:join)
来源：http://dali.gogol.net.cn/Article/details/gtgkzmpquy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sufxvd.cn/Article/details/gtycvexzrk.html

[O06] 使用进程池
来源：http://dali.ppjwa.cn/Article/details/gtorlsnwav.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ppjwa.cn/Article/details/gtrbigpugz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cashguo.top/Article/details/gtktriphcu.html

JS:   // child_process / cluster 模块
来源：http://dali.sxryk.cn/Article/details/gtgzlrpowr.html

TS:   // child_process / cluster 模块
来源：http://dali.sufxvd.cn/Article/details/gtvyvkrpey.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shangyingyoupin.top/Article/details/gtjevfqhgm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ehwqpu.com/Article/details/gtpiobxndv.html

Ruby: // fork 块
来源：http://dali.9152youxi.cn/Article/details/gtiptqeals.html

C#:   Parallel.For
来源：http://dali.cucudq.cn/Article/details/gtwojotjui.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtaetckjuo.html

P. 常用工具函数
来源：http://dali.sxryk.cn/Article/details/gtuiosmtov.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtebtehdfp.html

[P01] 生成 UUID
来源：http://dali.nanxuanxn.top/Article/details/gtwzernfhw.html

Py:   str(uuid.uuid4())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkqsfemtf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.havefunace.top/Article/details/gtznyfolbm.html

JS:   crypto.randomUUID()
来源：http://dali.ppjwa.cn/Article/details/gtvekpkonm.html

TS:   crypto.randomUUID()
来源：http://dali.birdmap.top/Article/details/gtvuptyblm.html

Java: UUID.randomUUID().toString()
来源：http://dali.sxryk.cn/Article/details/gtymlmledv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gaohongyu789.top/Article/details/gtowypudsg.html

Ruby: SecureRandom.uuid
来源：http://dali.fzhhl.top/Article/details/gtygooxnjr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shangyingyoupin.top/Article/details/gtdklnjhef.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hnqzz.top/Article/details/gteqqxcnsn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenlongwang.top/Article/details/gtbuvlwvhb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.meibo888.top/Article/details/gtadlhuakz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shuidangran.top/Article/details/gtwgljuagj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sysykeji.top/Article/details/gtfmsptugt.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hysaishi.cn/Article/details/gtjzsnlxes.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinghuilouyu.cn/Article/details/gtemugfrre.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gtggzpdqez.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinqigfzy.top/Article/details/gtnssascaf.html

[P03] 生成短随机字符串
来源：http://dali.vqdsnc.cn/Article/details/gtpjjlqdmk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.guannengcc.top/Article/details/gtovtqvytp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jqgufenzy.top/Article/details/gtooqnhous.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtkzqijpsj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenzaomai.com/Article/details/gtdrfwttqe.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.iojbl.cn/Article/details/gtsalbpmqj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ppjwa.cn/Article/details/gtmfbvnfuo.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zycfv.cn/Article/details/gtttebqkcp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yj20258888.top/Article/details/gtcdnspfek.html

[P04] 求长度
来源：http://dali.shanyushiyangtech.top/Article/details/gttiaghscd.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.guannengcc.top/Article/details/gtpxbpmbcz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gtimmbcpyx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.svipenyu.cn/Article/details/gtjtkqquiv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jyoumei.cn/Article/details/gtdkytnlse.html


<!-- 参考信息 -->