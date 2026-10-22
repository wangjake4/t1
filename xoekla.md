代发 wailian999

Py:   resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gt2ozbqxlzr.html

PHP:  json_decode($body, true);
来源：http://dali.kuanghao11.cn/Article/details/gt2enhhpqjw.html

JS:   await resp.json()
来源：http://dali.wangdashe.top/Article/details/gt2aexvrtkw.html

TS:   await resp.json()
来源：http://dali.wangdashe.top/Article/details/gt2ncnlalnn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.svipenyu.cn/Article/details/gt2eacgushv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.0kj1m.cn/Article/details/gt2mfxgosxg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.wangshuangyany.cn/Article/details/gt2hvisphzk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.chenzaomai.com/Article/details/gt2rwvbwwut.html

[L07] 处理 HTTP 状态码
来源：http://dali.0kj1m.cn/Article/details/gt2wytblaex.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.feifeiyinyue.top/Article/details/gt2otzgoxyq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cashguo.top/Article/details/gt2ddxnoada.html

JS:   resp.ok;  resp.status
来源：http://dali.jyoumei.cn/Article/details/gt2qbugxgjl.html

TS:   resp.ok;  resp.status
来源：http://dali.xuetiantiany.cn/Article/details/gt2xvqyewzz.html

Java: resp.statusCode()
来源：http://dali.havefunace.top/Article/details/gt2fujrlznq.html

Go:   resp.StatusCode
来源：http://dali.ppjwa.cn/Article/details/gt2cmkfbdmr.html

Ruby: resp.code.to_i
来源：http://dali.zhoulong.xyz/Article/details/gt2wpnnojym.html

C#:   (int)resp.StatusCode
来源：http://dali.9152youxi.cn/Article/details/gt2zxlvgntg.html

[L08] 并发请求多个地址
来源：http://dali.wangdashe.top/Article/details/gt2julcrqke.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sxryk.cn/Article/details/gt2gmznfvzg.html

PHP:  curl_multi_init() 系列
来源：http://dali.meibo888.top/Article/details/gt2dlrvyper.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hlrqxjgk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gt2hmwcbzka.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uxrwatsb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cheryme.top/Article/details/gt2fbmffjru.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gotoacloud.top/Article/details/gt2jnenytvc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.dashuyun.cn/Article/details/gt2vjaewonz.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2ttzldnhh.html

M. 命令行 / 进程 / 环境
来源：http://dali.jqgufenzy.top/Article/details/gt2vkuipfvf.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2rawqfsbz.html

[M01] 读取命令行参数
来源：http://dali.c1oappe.top/Article/details/gt2urqpayrh.html

Py:   sys.argv[1:]
来源：http://dali.yj20258888.top/Article/details/gt2abntfjsx.html

PHP:  $argv;  $argc;
来源：http://dali.bjfxy.top/Article/details/gt2ozypuhoj.html

JS:   process.argv.slice(2)
来源：http://dali.yj20258888.top/Article/details/gt2omsqgwga.html

TS:   process.argv.slice(2)
来源：http://dali.andypj.xyz/Article/details/gt2nihqyrbo.html

Java: args 数组（main 方法参数）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vbeaueoi.html

Go:   os.Args[1:]
来源：http://dali.pengpengdd.cyou/Article/details/gt2dyzfixeb.html

Ruby: ARGV
来源：http://dali.yj20258888.top/Article/details/gt2xmjpltwb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xziqi.cn/Article/details/gt2qslomfda.html

[M02] 读取环境变量
来源：http://dali.snrcjt.cn/Article/details/gt2hbnurgxb.html

Py:   os.environ.get("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gt2rztwooeg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.c1oappe.top/Article/details/gt2xdckcanb.html

JS:   process.env.HOME
来源：http://dali.ppjwa.cn/Article/details/gt2jakrubgy.html

TS:   process.env.HOME
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ktjmrxro.html

Java: System.getenv("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lhvvyekn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jiagoushi.top/Article/details/gt2dtcciwjh.html

Ruby: ENV["HOME"]
来源：http://dali.hammf.cn/Article/details/gt2ljebqzog.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ehwqpu.com/Article/details/gt2msznzsrt.html

[M03] 执行外部命令
来源：http://dali.chenlongwang.top/Article/details/gt2ohituqky.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qvnvcdph.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhengqikj.top/Article/details/gt2vugleayg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cucudq.cn/Article/details/gt2iunolkwi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shzxlz.cn/Article/details/gt2fjsqebjy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhiwuduotai.top/Article/details/gt2xbwbaabw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ehwqpu.com/Article/details/gt2hgglsdiu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jlsjyb.cn/Article/details/gt2aktzqbty.html

C#:   Process.Start("ls", "-l");
来源：http://dali.guowangkeji.top/Article/details/gt2mpeckbpk.html

[M04] 获取当前工作目录
来源：http://dali.hysaishi.cn/Article/details/gt2hmibqfnm.html

Py:   os.getcwd()
来源：http://dali.guannengcc.top/Article/details/gt2eqigjpen.html

PHP:  getcwd();
来源：http://dali.yj20258.top/Article/details/gt2jsjvojiw.html

JS:   process.cwd()
来源：http://dali.gaohongyu789.top/Article/details/gt2foraaxrr.html

TS:   process.cwd()
来源：http://dali.jqgfzy.top/Article/details/gt2paiehdvb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.dianchejie.cn/Article/details/gt2nmhvwmwt.html

Go:   os.Getwd()
来源：http://dali.chenlongwang.top/Article/details/gt2znnnixid.html

Ruby: Dir.pwd
来源：http://dali.dashuyun.cn/Article/details/gt2zjhfrwus.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hysaishi.cn/Article/details/gt2plkzcokp.html

[M05] 设置退出码
来源：http://dali.jinqigfzy.top/Article/details/gt2qarjivbr.html

Py:   sys.exit(1)
来源：http://dali.yonumen.top/Article/details/gt2nvfutmqj.html

PHP:  exit(1);
来源：http://dali.zhixingplan.top/Article/details/gt2rwywubxi.html

JS:   process.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rnwpwrtf.html

TS:   process.exit(1)
来源：http://dali.cheryme.top/Article/details/gt2ffcsajqu.html

Java: System.exit(1)
来源：http://dali.sweek.top/Article/details/gt2ldupjeld.html

Go:   os.Exit(1)
来源：http://dali.birdmap.top/Article/details/gt2fbcmfuxt.html

Ruby: exit 1
来源：http://dali.iojbl.cn/Article/details/gt2llbrlwin.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qdkbwgio.html

[M06] 向标准错误输出
来源：http://dali.xuanzx.com/Article/details/gt2adwxhnxl.html

Py:   print("err", file=sys.stderr)
来源：http://dali.quarkkingdee.top/Article/details/gt2xlltsmep.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yongpay.top/Article/details/gt2arajfdkh.html

JS:   console.error("err")
来源：http://dali.xziqi.cn/Article/details/gt2uxcmykjw.html

TS:   console.error("err")
来源：http://dali.jiagoushi.top/Article/details/gt2xutffmyq.html

Java: System.err.println("err")
来源：http://dali.tianlin.xyz/Article/details/gt2qklvfghw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinqigufen.top/Article/details/gt2ccyijrxw.html

Ruby: warn "err"
来源：http://dali.hfpthk.cn/Article/details/gt2guvlbelp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shzxlz.cn/Article/details/gt2zhqcpndi.html

[M07] 判断是否为主入口
来源：http://dali.ppjwa.cn/Article/details/gt2ubttlzdf.html

Py:   if __name__ == "__main__":
来源：http://dali.yuxming.cn/Article/details/gt2rmqncznt.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.nwbrower.top/Article/details/gt2mxmpbwqm.html

JS:   require.main === module
来源：http://dali.zhongyouzk.top/Article/details/gt2pewfxriq.html

TS:   require.main === module
来源：http://dali.chenlongwang.top/Article/details/gt2euhlppwj.html

Java: public static void main(String[] args)
来源：http://dali.fengsongda.top/Article/details/gt2cozvzgzl.html

Go:   func main()
来源：http://dali.tanke756.top/Article/details/gt2fpsxkacf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhongyouzk.top/Article/details/gt2vifdcmnu.html

C#:   static void Main(string[] args)
来源：http://dali.yvedp.cn/Article/details/gt2msexkgah.html

[M08] 获取系统与运行时信息
来源：http://dali.shangyingyoupin.top/Article/details/gt2wluwhhfb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yongpay.top/Article/details/gt2awcrjhlc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zycfv.cn/Article/details/gt2mkvaxmei.html

JS:   process.platform;  process.version
来源：http://dali.cucudq.cn/Article/details/gt2sxppvkxi.html

TS:   process.platform;  process.version
来源：http://dali.hysaishi.cn/Article/details/gt2ptsvecbd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.aibaodan.cn/Article/details/gt2qimljisu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.daria6918.cn/Article/details/gt2mvtuprbu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sweek.top/Article/details/gt2tgpwvvsf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cdnleiting.top/Article/details/gt2zviifurk.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2gqngwejj.html

N. 数据结构与算法
来源：http://dali.ppjwa.cn/Article/details/gt2hvfecsjj.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2yfwaakrr.html

[N01] 二分查找（有序数组）
来源：http://dali.haohaochexian.top/Article/details/gt2jnzbmaqq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.smart0.xyz/Article/details/gt2zjapktbx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.meibo888.top/Article/details/gt2ugodieoh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenlongwang.top/Article/details/gt2aswkbswc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tianlin.xyz/Article/details/gt2tielogyw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2basbhvur.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2heoeasnv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sysykeji.top/Article/details/gt2yjjeauit.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hammf.cn/Article/details/gt2vhhglwlm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cdhljdsn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yangfankeji.com/Article/details/gt2ixvcgvrp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yvedp.cn/Article/details/gt2zajxveut.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xziqi.cn/Article/details/gt2bpnnlncp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cdnleiting.top/Article/details/gt2euyyzmvu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yvedp.cn/Article/details/gt2hyiqdlmu.html

Go:   slices.Sort(arr)
来源：http://dali.sysykeji.top/Article/details/gt2odrknngf.html

Ruby: arr.sort
来源：http://dali.fengsongda.top/Article/details/gt2ubxacnmv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2soxnrtjm.html

[N03] 快速排序（分治示例）
来源：http://dali.fzhhl.top/Article/details/gt2xbtynfhe.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gaohongyu789.top/Article/details/gt2dpomchhf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jlsjyb.cn/Article/details/gt2qmqsufbf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gzhubu.top/Article/details/gt2othdhgmu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shzxlz.cn/Article/details/gt2mdikcaeo.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.fzhhl.top/Article/details/gt2qnxgccta.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhixingplan.top/Article/details/gt2zqwbgfpy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.vqdsnc.cn/Article/details/gt2vmpcljcy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xinyue.icu/Article/details/gt2svbcwxvf.html

[N04] 斐波那契数列
来源：http://dali.jqgufenzy.top/Article/details/gt2dheokgep.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2rvytxcsp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shzxlz.cn/Article/details/gt2yikbehvc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.vqdsnc.cn/Article/details/gt2pjxgmsoq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gt2zthnuozj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xmsylfss.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sysykeji.top/Article/details/gt2eeahsxrd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xylfe.cn/Article/details/gt2nltoaeua.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shuidangran.top/Article/details/gt2avrpfbmc.html

[N05] 最大公约数
来源：http://dali.xuanzx.com/Article/details/gt2fsoafrru.html

Py:   math.gcd(a, b)
来源：http://dali.andypj.xyz/Article/details/gt2irirokbc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jdjaxcfu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxuanxn.top/Article/details/gt2xevdpaul.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ojuncvoy.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.gaohongyu789.top/Article/details/gt2avrzbhvu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.guowangkeji.top/Article/details/gt2vuedmnqj.html

Ruby: a.gcd(b)
来源：http://dali.tian-w.cn/Article/details/gt2yxwbauki.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hysaishi.cn/Article/details/gt2wupoxqwa.html

[N06] 判断回文字符串
来源：http://dali.wangdashe.top/Article/details/gt2izjqtvcy.html

Py:   s == s[::-1]
来源：http://dali.vqdsnc.cn/Article/details/gt2ttzxmzle.html

PHP:  $s === strrev($s);
来源：http://dali.ydzc1.top/Article/details/gt2axbtafnf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2okbihvut.html

TS:   s === [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gt2sxxxvqrh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.quarkkingdee.top/Article/details/gt2kdqhepbv.html

Go:   // 双指针从两端比较
来源：http://dali.andypj.xyz/Article/details/gt2hvbwpgav.html

Ruby: s == s.reverse
来源：http://dali.hysaishi.cn/Article/details/gt2gwooijka.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zdqjudy.top/Article/details/gt2njkaywdp.html

[N07] 两数之和（返回下标）
来源：http://dali.tanke756.top/Article/details/gt2orydzbnj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.nanxuanxn.top/Article/details/gt2aryyqfkn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gogol.net.cn/Article/details/gt2fqitqjbu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.316326.xyz/Article/details/gt2kxhouzxh.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xkzsvurq.html

Java: // 手写 HashMap
来源：http://dali.mhx1999.top/Article/details/gt2evrjiabg.html

Go:   // 手写 map[int]int
来源：http://dali.sufxvd.cn/Article/details/gt2hlfmxiid.html

Ruby: // 手写 Hash
来源：http://dali.cqqwz.cn/Article/details/gt2xzdqmuhv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.feifeiyinyue.top/Article/details/gt2wmnxkbfi.html

[N08] 生成全排列
来源：http://dali.mhx1999.top/Article/details/gt2tqblrxdd.html

Py:   itertools.permutations(arr)
来源：http://dali.redwolf501.top/Article/details/gt2zgyviplo.html

PHP:  // 手写递归交换
来源：http://dali.ehwqpu.com/Article/details/gt2ecrltnhp.html

JS:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gt2ltfsvlel.html

TS:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gt2fqjokxju.html

Java: // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gt2hsmdayaa.html

Go:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gt2vlxywlms.html

Ruby: arr.permutation.to_a
来源：http://dali.ydzc1.top/Article/details/gt2rfmdbtlc.html

C#:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gt2wtplfmyh.html

[N09] 栈与队列
来源：http://dali.aibaodan.cn/Article/details/gt2qqjmdmzc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.meibo888.top/Article/details/gt2kraukuco.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gt2dgwezpsx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hnxiangtu.top/Article/details/gt2gogykopr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hnqzz.top/Article/details/gt2xcpgmqjy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sysykeji.top/Article/details/gt2mdxbevlx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yuanzhike.top/Article/details/gt2bfltezih.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.316326.xyz/Article/details/gt2qmmomipr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.fengsongda.top/Article/details/gt2vugchkfp.html

[N10] 链表节点定义
来源：http://dali.hfpthk.cn/Article/details/gt2trrfujlr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.aizwys.cn/Article/details/gt2sdhbwlkp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shuidangran.top/Article/details/gt2otfaarvn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yj20258888.top/Article/details/gt2zyxmwxxp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.tanke756.top/Article/details/gt2jbzyuhyq.html

Java: class Node { int v; Node next; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kisbjjhq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.daxiang520.top/Article/details/gt2uyxmunta.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.birdmap.top/Article/details/gt2ufvhlyct.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinqigfzy.top/Article/details/gt2pibbptqn.html

[N11] 二叉树中序遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ysrsuxvd.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ehwqpu.com/Article/details/gt2wuwepwjp.html

PHP:  // 手写递归函数
来源：http://dali.gotoacloud.top/Article/details/gt2vgxvkvvh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sweek.top/Article/details/gt2laqbzgcf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.wangshuangyany.cn/Article/details/gt2cebeodnu.html

Java: // 手写递归
来源：http://dali.yvedp.cn/Article/details/gt2ozqplhnz.html

Go:   // 手写递归
来源：http://dali.shuidangran.top/Article/details/gt2ucbihwjd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gotoacloud.top/Article/details/gt2xchzgtuk.html

C#:   // 手写递归
来源：http://dali.andypj.xyz/Article/details/gt2klbxjedi.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.guowangkeji.top/Article/details/gt2ipfcuyua.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.pengpengdd.cyou/Article/details/gt2rpvejgii.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.guowangkeji.top/Article/details/gt2meyhvuuo.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cdnleiting.top/Article/details/gt2yrdverzy.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hfpthk.cn/Article/details/gt2mrkrqrlg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.c1oappe.top/Article/details/gt2yoijkdzw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hammf.cn/Article/details/gt2ttzikrsp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.wangdashe.top/Article/details/gt2iddywuvd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.wangshuangyany.cn/Article/details/gt2zygkfysh.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2vjyvrqse.html

O. 并发与异步
来源：http://dali.cheryme.top/Article/details/gt2zjjzgguc.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2qpourtop.html

[O01] 启动一个线程
来源：http://dali.yueranfly.top/Article/details/gt2nhymmigl.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cashguo.top/Article/details/gt2mwumnbit.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sysykeji.top/Article/details/gt2hpeujnoh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.svipenyu.cn/Article/details/gt2wgxdzdsh.html

TS:   // 同 JS
来源：http://dali.yanxiufei.cn/Article/details/gt2voghmrfe.html

Java: new Thread(() -> f()).start()
来源：http://dali.kuanghao11.cn/Article/details/gt2oonrgyjv.html

Go:   go f()
来源：http://dali.dashuyun.cn/Article/details/gt2hmcrntcj.html

Ruby: Thread.new { f }
来源：http://dali.shzxlz.cn/Article/details/gt2gtszxmmg.html

C#:   Task.Run(() => F());
来源：http://dali.jianghu66.top/Article/details/gt2bfwsplul.html

[O02] 使用线程池
来源：http://dali.yuxming.cn/Article/details/gt2jymhucsp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yonumen.top/Article/details/gt2lyqugbhk.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.andypj.xyz/Article/details/gt2szglxaou.html

JS:   // worker_threads 线程池
来源：http://dali.svipenyu.cn/Article/details/gt2ibqplzgb.html

TS:   // worker_threads 线程池
来源：http://dali.cashguo.top/Article/details/gt2dinrjeup.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.c1oappe.top/Article/details/gt2xsyrruql.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jyoumei.cn/Article/details/gt2jnjrlzae.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hysaishi.cn/Article/details/gt2lzutdcun.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yanxiufei.cn/Article/details/gt2xeyaodvj.html

[O03] 加锁保护共享数据
来源：http://dali.zycfv.cn/Article/details/gt2qnupmzht.html

Py:   with lock: shared += 1
来源：http://dali.gogol.net.cn/Article/details/gt2viiagyow.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kdztoopd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.daxiang520.top/Article/details/gt2ruzkodtr.html

TS:   // 同 JS
来源：http://dali.yj20258.top/Article/details/gt2xfccytyt.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinqigfzy.top/Article/details/gt2zqreeebj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gogol.net.cn/Article/details/gt2jjfqfnph.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.fzhhl.top/Article/details/gt2qzjwujig.html

C#:   lock (gate) { shared++; }
来源：http://dali.hnqzz.top/Article/details/gt2zcfakyrt.html

[O04] 定义异步函数并等待
来源：http://dali.birdmap.top/Article/details/gt2uqvimnuc.html

Py:   async def f():⏎    await g()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xndmjkrh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.nanxinkj.top/Article/details/gt2zsllajlv.html

JS:   async function f() { await g(); }
来源：http://dali.ivvv.top/Article/details/gt2exueoqks.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xinyue.icu/Article/details/gt2xomlyreh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.dashuyun.cn/Article/details/gt2hfpngetw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.wangdashe.top/Article/details/gt2vakoznxi.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gogol.net.cn/Article/details/gt2qnuaqnau.html

C#:   async Task F() { await G(); }
来源：http://dali.xziqi.cn/Article/details/gt2jrcjzsms.html

[O05] 并发执行并等待全部完成
来源：http://dali.c1oappe.top/Article/details/gt2jqabvcux.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yuanzhike.top/Article/details/gt2adznridh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xuanzx.com/Article/details/gt2dmttfstj.html

JS:   await Promise.all(tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pegrphmo.html

TS:   await Promise.all(tasks)
来源：http://dali.gogol.net.cn/Article/details/gt2xigfwxgk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kyjbpvrl.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.9152youxi.cn/Article/details/gt2sarjdzhy.html

Ruby: threads.map(&:join)
来源：http://dali.c1oappe.top/Article/details/gt2lmolbobu.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gotoacloud.top/Article/details/gt2zalsieqn.html

[O06] 使用进程池
来源：http://dali.yanxiufei.cn/Article/details/gt2klaawbsq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yangfankeji.com/Article/details/gt2rarbcmdc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jianghu66.top/Article/details/gt2vrxkpykd.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2elpatioq.html

TS:   // child_process / cluster 模块
来源：http://dali.bjfxy.top/Article/details/gt2bwumsqfq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.aibaodan.cn/Article/details/gt2jpgvglmr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yongpay.top/Article/details/gt2udorzvnf.html

Ruby: // fork 块
来源：http://dali.yj20258888.top/Article/details/gt2bzfwswnj.html

C#:   Parallel.For
来源：http://dali.gzhubu.top/Article/details/gt2olcokzwr.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2umuwokoi.html

P. 常用工具函数
来源：http://dali.hywenlv.cn/Article/details/gt2ljdyoygj.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2pdatxdgg.html

[P01] 生成 UUID
来源：http://dali.sysykeji.top/Article/details/gt2zrggvnky.html

Py:   str(uuid.uuid4())
来源：http://dali.hnxiangtu.top/Article/details/gt2hkzieqno.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xinyue.icu/Article/details/gt2nrdqkrvv.html

JS:   crypto.randomUUID()
来源：http://dali.shangyingyoupin.top/Article/details/gt2iarmhmbp.html

TS:   crypto.randomUUID()
来源：http://dali.gaohongyu789.top/Article/details/gt2lfdjvcgx.html

Java: UUID.randomUUID().toString()
来源：http://dali.jqgufenzy.top/Article/details/gt2qhumplap.html

Go:   // 用 github.com/google/uuid
来源：http://dali.kuanghao11.cn/Article/details/gt2jlolqfgv.html

Ruby: SecureRandom.uuid
来源：http://dali.zycfv.cn/Article/details/gt2knveuylc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.wangshuangyany.cn/Article/details/gt2fbxxtfta.html

[P02] MD5 / SHA256 摘要
来源：http://dali.pengpengdd.cyou/Article/details/gt2ergqvavz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.wangdashe.top/Article/details/gt2iujazlxt.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.chenlongwang.top/Article/details/gt2azntnxzf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.pycfn.com/Article/details/gt2qrlvqxlh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shangyingyoupin.top/Article/details/gt2dzjjxftz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.mhx1999.top/Article/details/gt2sehfllvw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.316326.xyz/Article/details/gt2gssdprdt.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zhegsbey.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.iojbl.cn/Article/details/gt2rnmuitgh.html

[P03] 生成短随机字符串
来源：http://dali.ppjwa.cn/Article/details/gt2dzlpsbwn.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hongshengwenyu.top/Article/details/gt2alpgwnex.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cashguo.top/Article/details/gt2zcgnjtyp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.meibo888.top/Article/details/gt2idlvwbfx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.quarkkingdee.top/Article/details/gt2tzjkhclz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.havefunace.top/Article/details/gt2lqblrjif.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cpnllluk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhengqikj.top/Article/details/gt2rmjkyoba.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2njdzepfv.html

[P04] 求长度
来源：http://dali.cashguo.top/Article/details/gt2kbwhglyv.html


<!-- 参考信息 -->