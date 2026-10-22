代发 wailian999

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenlongwang.top/Article/details/gt2elnwmyoo.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.tanke756.top/Article/details/gt2czgfelow.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xinyue.icu/Article/details/gt2rfwgkpem.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zdqjudy.top/Article/details/gt2elqjlwqp.html

[L07] 处理 HTTP 状态码
来源：http://dali.jianghu66.top/Article/details/gt2xxalrhan.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.vqdsnc.cn/Article/details/gt2qwpcvbkd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yj20258.top/Article/details/gt2yqqvxwjv.html

JS:   resp.ok;  resp.status
来源：http://dali.316326.xyz/Article/details/gt2ozosaono.html

TS:   resp.ok;  resp.status
来源：http://dali.ybcxt.top/Article/details/gt2hlfbozwe.html

Java: resp.statusCode()
来源：http://dali.sweek.top/Article/details/gt2wajaruli.html

Go:   resp.StatusCode
来源：http://dali.bjfxy.top/Article/details/gt2dgsjsuxk.html

Ruby: resp.code.to_i
来源：http://dali.gogol.net.cn/Article/details/gt2nwrcyeix.html

C#:   (int)resp.StatusCode
来源：http://dali.havefunace.top/Article/details/gt2znnvbfci.html

[L08] 并发请求多个地址
来源：http://dali.jinqigufen.top/Article/details/gt2xhdyadgw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cashguo.top/Article/details/gt2mwkakytm.html

PHP:  curl_multi_init() 系列
来源：http://dali.meibo888.top/Article/details/gt2sflgpqzp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sysykeji.top/Article/details/gt2iculxysg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.smart0.xyz/Article/details/gt2bptcdzqf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shzxlz.cn/Article/details/gt2pzffeqlu.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zdqjudy.top/Article/details/gt2rrasifao.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xinyue.icu/Article/details/gt2vecnncbd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.aizwys.cn/Article/details/gt2fzfrzzmx.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2steybaet.html

M. 命令行 / 进程 / 环境
来源：http://dali.gotoacloud.top/Article/details/gt2jzrxblpc.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fthfedmr.html

[M01] 读取命令行参数
来源：http://dali.dashuyun.cn/Article/details/gt2uuybdefk.html

Py:   sys.argv[1:]
来源：http://dali.wangdashe.top/Article/details/gt2drdzqajo.html

PHP:  $argv;  $argc;
来源：http://dali.guannengcc.top/Article/details/gt2msffyrdb.html

JS:   process.argv.slice(2)
来源：http://dali.yj20258.top/Article/details/gt2bgxulitx.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbxughx.html

Java: args 数组（main 方法参数）
来源：http://dali.snrcjt.cn/Article/details/gt2nhsleowc.html

Go:   os.Args[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mervwsts.html

Ruby: ARGV
来源：http://dali.pengpengdd.cyou/Article/details/gt2jrdjrtij.html

C#:   args 数组（Main 方法参数）
来源：http://dali.haohaochexian.top/Article/details/gt2ucmvkqnh.html

[M02] 读取环境变量
来源：http://dali.sweek.top/Article/details/gt2gejomdpr.html

Py:   os.environ.get("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gt2cbdxyema.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zdqjudy.top/Article/details/gt2zayxwmgs.html

JS:   process.env.HOME
来源：http://dali.ehwqpu.com/Article/details/gt2zrjdcgrw.html

TS:   process.env.HOME
来源：http://dali.zhiwuduotai.top/Article/details/gt2ddwmoofl.html

Java: System.getenv("HOME")
来源：http://dali.gotoacloud.top/Article/details/gt2rebkeneo.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gt2bqgijhnj.html

Ruby: ENV["HOME"]
来源：http://dali.ehwqpu.com/Article/details/gt2rshbgqok.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.316326.xyz/Article/details/gt2jkjgbxyv.html

[M03] 执行外部命令
来源：http://dali.jqgfzy.top/Article/details/gt2tgujiyit.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jyoumei.cn/Article/details/gt2eceihikd.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jianghu66.top/Article/details/gt2zyxkiuqu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenlongwang.top/Article/details/gt2mucrcdyf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hysaishi.cn/Article/details/gt2vyriohjl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ydzc1.top/Article/details/gt2tdkgdcye.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sysykeji.top/Article/details/gt2maaxqcfh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.snrcjt.cn/Article/details/gt2cnlgbzwp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.meibo888.top/Article/details/gt2iqmkmgro.html

[M04] 获取当前工作目录
来源：http://dali.daxiang520.top/Article/details/gt2rwylzwlw.html

Py:   os.getcwd()
来源：http://dali.pycfn.com/Article/details/gt2ozewwxah.html

PHP:  getcwd();
来源：http://dali.redwolf501.top/Article/details/gt2xahnwhpg.html

JS:   process.cwd()
来源：http://dali.yongpay.top/Article/details/gt2siblvzsx.html

TS:   process.cwd()
来源：http://dali.birdmap.top/Article/details/gt2wsplvzrr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wpypnqhy.html

Go:   os.Getwd()
来源：http://dali.sufxvd.cn/Article/details/gt2teljteye.html

Ruby: Dir.pwd
来源：http://dali.wangdashe.top/Article/details/gt2kxqsvkpl.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yangfankeji.com/Article/details/gt2nlitisvv.html

[M05] 设置退出码
来源：http://dali.daria6918.cn/Article/details/gt2tihozsna.html

Py:   sys.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2qvlzzmqi.html

PHP:  exit(1);
来源：http://dali.svipenyu.cn/Article/details/gt2uagsbffw.html

JS:   process.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2jmsowvba.html

TS:   process.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gt2ijusutov.html

Java: System.exit(1)
来源：http://dali.hnqzz.top/Article/details/gt2zqhksjah.html

Go:   os.Exit(1)
来源：http://dali.chenzaomai.com/Article/details/gt2cqcrugdu.html

Ruby: exit 1
来源：http://dali.yangfankeji.com/Article/details/gt2oevnaryg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhiwuduotai.top/Article/details/gt2zuouvykn.html

[M06] 向标准错误输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lhwkdfdn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sxryk.cn/Article/details/gt2zeczgdzm.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xinyue.icu/Article/details/gt2tuyewidb.html

JS:   console.error("err")
来源：http://dali.sufxvd.cn/Article/details/gt2ewannkbv.html

TS:   console.error("err")
来源：http://dali.shangyingyoupin.top/Article/details/gt2sedpsaag.html

Java: System.err.println("err")
来源：http://dali.feifeiyinyue.top/Article/details/gt2gkrtetpx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.dianchejie.cn/Article/details/gt2sfgvoltk.html

Ruby: warn "err"
来源：http://dali.tanke756.top/Article/details/gt2gqhzeakj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.birdmap.top/Article/details/gt2nufjducw.html

[M07] 判断是否为主入口
来源：http://dali.aizwys.cn/Article/details/gt2eptkqdfo.html

Py:   if __name__ == "__main__":
来源：http://dali.hnxiangtu.top/Article/details/gt2irksyiab.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ivvv.top/Article/details/gt2zikhwzfn.html

JS:   require.main === module
来源：http://dali.hammf.cn/Article/details/gt2wwzcbjpc.html

TS:   require.main === module
来源：http://dali.dashuyun.cn/Article/details/gt2rwnzilut.html

Java: public static void main(String[] args)
来源：http://dali.0kj1m.cn/Article/details/gt2gtwygkvs.html

Go:   func main()
来源：http://dali.shangyingyoupin.top/Article/details/gt2gbpmcoqt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jlsjyb.cn/Article/details/gt2uxugubnt.html

C#:   static void Main(string[] args)
来源：http://dali.sysykeji.top/Article/details/gt2nhznnsyd.html

[M08] 获取系统与运行时信息
来源：http://dali.shuidangran.top/Article/details/gt2melsnkew.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cqqwz.cn/Article/details/gt2bskjrppm.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.svipenyu.cn/Article/details/gt2qxslcnyu.html

JS:   process.platform;  process.version
来源：http://dali.c1oappe.top/Article/details/gt2hzfrgozz.html

TS:   process.platform;  process.version
来源：http://dali.shuidangran.top/Article/details/gt2ofcvtnvm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ybcxt.top/Article/details/gt2khqgxrmk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj202588.top/Article/details/gt2ivhlxevn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhiwuduotai.top/Article/details/gt2igoinwgn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.daxiang520.top/Article/details/gt2uirftcct.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2pkuqlfqz.html

N. 数据结构与算法
来源：http://dali.iojbl.cn/Article/details/gt2uhonxsdv.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2tlftcxvh.html

[N01] 二分查找（有序数组）
来源：http://dali.xuetiantiany.cn/Article/details/gt2xfwgzysy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gt2fvvjhhqk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.c1oappe.top/Article/details/gt2fgkkkuxl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mqfzouiv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhixingplan.top/Article/details/gt2gjhlgjgk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yj20258888.top/Article/details/gt2bxsfcrin.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sweek.top/Article/details/gt2tzpzazel.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhoulong.xyz/Article/details/gt2jhfieqmw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.fzhhl.top/Article/details/gt2krzivmib.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cdnleiting.top/Article/details/gt2nugtaggg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgfzy.top/Article/details/gt2mhpqznkp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.dashuyun.cn/Article/details/gt2ekdmozue.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.quarkkingdee.top/Article/details/gt2dshslwli.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2czjvcwuj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhongyouzk.top/Article/details/gt2iemjjgwu.html

Go:   slices.Sort(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2bbbyldbu.html

Ruby: arr.sort
来源：http://dali.xylfe.cn/Article/details/gt2uxzovcbp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nanxuanxn.top/Article/details/gt2prjviqca.html

[N03] 快速排序（分治示例）
来源：http://dali.chenzaomai.com/Article/details/gt2lamhvtlo.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ybcxt.top/Article/details/gt2dvuofzcg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.svipenyu.cn/Article/details/gt2vddoffzh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fzhhl.top/Article/details/gt2whthkcrw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.iojbl.cn/Article/details/gt2bgjequga.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj20258.top/Article/details/gt2xvcwbxiw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ybcxt.top/Article/details/gt2acsmlqsv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.9152youxi.cn/Article/details/gt2tsttqoij.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sxryk.cn/Article/details/gt2ovrxgtxy.html

[N04] 斐波那契数列
来源：http://dali.wangdashe.top/Article/details/gt2jytgqfps.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.fengsongda.top/Article/details/gt2lksprumj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xinyue.icu/Article/details/gt2ttexlymx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj20258888.top/Article/details/gt2zfxszjau.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ppjwa.cn/Article/details/gt2hlhpemxx.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinqigufen.top/Article/details/gt2pgewmtbm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.snrcjt.cn/Article/details/gt2mwgpnucb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yvedp.cn/Article/details/gt2ivflgkdf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.svipenyu.cn/Article/details/gt2tkgpyegl.html

[N05] 最大公约数
来源：http://dali.0kj1m.cn/Article/details/gt2yumshdqh.html

Py:   math.gcd(a, b)
来源：http://dali.fzhhl.top/Article/details/gt2tvrokejy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2dgpfeyxs.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shuidangran.top/Article/details/gt2vlsqervv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.haohaochexian.top/Article/details/gt2lkbgtkcp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sqeedbee.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.redwolf501.top/Article/details/gt2ecrcmwai.html

Ruby: a.gcd(b)
来源：http://dali.hywenlv.cn/Article/details/gt2iomnlmql.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mthyayer.html

[N06] 判断回文字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2bdekmxox.html

Py:   s == s[::-1]
来源：http://dali.birdmap.top/Article/details/gt2euomvfny.html

PHP:  $s === strrev($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mvlbvhyn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gt2pwgspaoc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sysykeji.top/Article/details/gt2hjywjqwb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jianghu66.top/Article/details/gt2kohepesn.html

Go:   // 双指针从两端比较
来源：http://dali.yj202588.top/Article/details/gt2lexexdqe.html

Ruby: s == s.reverse
来源：http://dali.cucudq.cn/Article/details/gt2yqaibpdy.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.daxiang520.top/Article/details/gt2ojetfgnu.html

[N07] 两数之和（返回下标）
来源：http://dali.andypj.xyz/Article/details/gt2opguxaab.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yangfankeji.com/Article/details/gt2kgmbpxde.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shzxlz.cn/Article/details/gt2ethtohdg.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.guannengcc.top/Article/details/gt2fcfqcisf.html

TS:   // 手写 Map<string, number>
来源：http://dali.gzhubu.top/Article/details/gt2arnalxty.html

Java: // 手写 HashMap
来源：http://dali.sxryk.cn/Article/details/gt2swqryujf.html

Go:   // 手写 map[int]int
来源：http://dali.zhiwuduotai.top/Article/details/gt2waemxcjr.html

Ruby: // 手写 Hash
来源：http://dali.xylfe.cn/Article/details/gt2sldnhqbd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yuanzhike.top/Article/details/gt2idkqoxgd.html

[N08] 生成全排列
来源：http://dali.nanxinkj.top/Article/details/gt2rwmxlczy.html

Py:   itertools.permutations(arr)
来源：http://dali.daria6918.cn/Article/details/gt2zstziwuc.html

PHP:  // 手写递归交换
来源：http://dali.hnqzz.top/Article/details/gt2spvkdceu.html

JS:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gt2vmfyvlcq.html

TS:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gt2nbnbizrt.html

Java: // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gt2zezhsrua.html

Go:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gt2cegphvkc.html

Ruby: arr.permutation.to_a
来源：http://dali.zycfv.cn/Article/details/gt2frbgpegb.html

C#:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tihshvyy.html

[N09] 栈与队列
来源：http://dali.xuetiantiany.cn/Article/details/gt2nqgptssi.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jqgufenzy.top/Article/details/gt2nxnzmbsa.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gogol.net.cn/Article/details/gt2hbonmiwe.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ybcxt.top/Article/details/gt2vtbhzlnc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhengqikj.top/Article/details/gt2tmduagbr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.birdmap.top/Article/details/gt2ffotsabz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.nwbrower.top/Article/details/gt2wjbdhqgp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sufxvd.cn/Article/details/gt2jeroywnf.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yvedp.cn/Article/details/gt2chrofeyg.html

[N10] 链表节点定义
来源：http://dali.9152youxi.cn/Article/details/gt2mzozoktj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ydzc1.top/Article/details/gt2czvaygzn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yj20258.top/Article/details/gt2prgliiqg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.snrcjt.cn/Article/details/gt2qzlvhsjz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sufxvd.cn/Article/details/gt2okmupijl.html

Java: class Node { int v; Node next; }
来源：http://dali.hfpthk.cn/Article/details/gt2hnzmnqkl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.andypj.xyz/Article/details/gt2mrgmrdmz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.dashuyun.cn/Article/details/gt2fmziqfyc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hywenlv.cn/Article/details/gt2pdqoqmpv.html

[N11] 二叉树中序遍历
来源：http://dali.gzhubu.top/Article/details/gt2svwwqxdb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jqgfzy.top/Article/details/gt2vtcwxkse.html

PHP:  // 手写递归函数
来源：http://dali.hysaishi.cn/Article/details/gt2xcnydegv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.quarkkingdee.top/Article/details/gt2vxplyeql.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oxogylth.html

Java: // 手写递归
来源：http://dali.iojbl.cn/Article/details/gt2adqkcily.html

Go:   // 手写递归
来源：http://dali.nanxuanxn.top/Article/details/gt2ukjhjpia.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zecxaolb.html

C#:   // 手写递归
来源：http://dali.zhixingplan.top/Article/details/gt2sjbdelsf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhiwuduotai.top/Article/details/gt2dyojzvtu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.316326.xyz/Article/details/gt2zftgorrm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jyoumei.cn/Article/details/gt2mnpcqtsk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hysaishi.cn/Article/details/gt2gddgcokm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hongshengwenyu.top/Article/details/gt2gpixxuhm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hywenlv.cn/Article/details/gt2pxchtpsw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.quarkkingdee.top/Article/details/gt2vwboewoe.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xuetiantiany.cn/Article/details/gt2dzixsrwj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hfpthk.cn/Article/details/gt2wbulnlsz.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2ncemioba.html

O. 并发与异步
来源：http://dali.xuetiantiany.cn/Article/details/gt2gjfpheak.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2iymvnnxm.html

[O01] 启动一个线程
来源：http://dali.hywenlv.cn/Article/details/gt2hbmizyss.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yvedp.cn/Article/details/gt2mrefpdvv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yj20258888.top/Article/details/gt2ucngwapb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.vqdsnc.cn/Article/details/gt2haznuuwz.html

TS:   // 同 JS
来源：http://dali.ppjwa.cn/Article/details/gt2yjdyhzsu.html

Java: new Thread(() -> f()).start()
来源：http://dali.shangyingyoupin.top/Article/details/gt2xigkvdlk.html

Go:   go f()
来源：http://dali.yonumen.top/Article/details/gt2phcvwarq.html

Ruby: Thread.new { f }
来源：http://dali.yj20258.top/Article/details/gt2jmuqonap.html

C#:   Task.Run(() => F());
来源：http://dali.cdnleiting.top/Article/details/gt2fqwjuqzv.html

[O02] 使用线程池
来源：http://dali.jqgfzy.top/Article/details/gt2nwqgtuek.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.aizwys.cn/Article/details/gt2blzlcfgw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.iojbl.cn/Article/details/gt2atouhrsi.html

JS:   // worker_threads 线程池
来源：http://dali.cucudq.cn/Article/details/gt2anzmzpxe.html

TS:   // worker_threads 线程池
来源：http://dali.xuanzx.com/Article/details/gt2yrwosxrr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hammf.cn/Article/details/gt2bzscigrl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ybcxt.top/Article/details/gt2ekkxuvmf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shzxlz.cn/Article/details/gt2nhotzugz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yangfankeji.com/Article/details/gt2jdyiiiuf.html

[O03] 加锁保护共享数据
来源：http://dali.aibaodan.cn/Article/details/gt2fdfosouu.html

Py:   with lock: shared += 1
来源：http://dali.ivvv.top/Article/details/gt2yoadfuay.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sxryk.cn/Article/details/gt2znhtlwtx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gogol.net.cn/Article/details/gt2taiqcstl.html

TS:   // 同 JS
来源：http://dali.ybcxt.top/Article/details/gt2mchhyoom.html

Java: synchronized (this) { shared++; }
来源：http://dali.cdnleiting.top/Article/details/gt2gxwtdgnd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.chenzaomai.com/Article/details/gt2jsbiohxp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cheryme.top/Article/details/gt2lmxmjojv.html

C#:   lock (gate) { shared++; }
来源：http://dali.yanxiufei.cn/Article/details/gt2rdkfqhcm.html

[O04] 定义异步函数并等待
来源：http://dali.hnxiangtu.top/Article/details/gt2yjczjaju.html

Py:   async def f():⏎    await g()
来源：http://dali.haohaochexian.top/Article/details/gt2dclsbrdn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhixingplan.top/Article/details/gt2jzlqyhyb.html

JS:   async function f() { await g(); }
来源：http://dali.tanke756.top/Article/details/gt2gssgrqyr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jiagoushi.top/Article/details/gt2qghezmap.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zdqjudy.top/Article/details/gt2nidotcbd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.daria6918.cn/Article/details/gt2stsbopbs.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yj202588.top/Article/details/gt2msgocrem.html

C#:   async Task F() { await G(); }
来源：http://dali.bjfxy.top/Article/details/gt2bhmtcmbn.html

[O05] 并发执行并等待全部完成
来源：http://dali.kuanghao11.cn/Article/details/gt2ivwifxkz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hnqzz.top/Article/details/gt2imxvtbbf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cashguo.top/Article/details/gt2xhkfcmxk.html

JS:   await Promise.all(tasks)
来源：http://dali.zhengqikj.top/Article/details/gt2zqraqgmz.html

TS:   await Promise.all(tasks)
来源：http://dali.yj20258.top/Article/details/gt2evodbfwp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.chenjidiqi.icu/Article/details/gt2gqxrwpdj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hywenlv.cn/Article/details/gt2meorzgeu.html

Ruby: threads.map(&:join)
来源：http://dali.ivvv.top/Article/details/gt2onokksig.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinqigfzy.top/Article/details/gt2smpxnnhv.html

[O06] 使用进程池
来源：http://dali.nanxuanxn.top/Article/details/gt2cnsyesnv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.aizwys.cn/Article/details/gt2ayowseqw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.c1oappe.top/Article/details/gt2ctqixooa.html

JS:   // child_process / cluster 模块
来源：http://dali.svipenyu.cn/Article/details/gt2ejmwzvrh.html

TS:   // child_process / cluster 模块
来源：http://dali.aizwys.cn/Article/details/gt2unnazqpo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ppjwa.cn/Article/details/gt2ievsgbhd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sufxvd.cn/Article/details/gt2hnlpcvwi.html

Ruby: // fork 块
来源：http://dali.yvedp.cn/Article/details/gt2nlfpgtzq.html

C#:   Parallel.For
来源：http://dali.vqdsnc.cn/Article/details/gt2qemmhjdz.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2lteyrllx.html

P. 常用工具函数
来源：http://dali.ydzc1.top/Article/details/gt2modplnem.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2whrnmrdc.html

[P01] 生成 UUID
来源：http://dali.chenlongwang.top/Article/details/gt2rmpmqbfz.html

Py:   str(uuid.uuid4())
来源：http://dali.xylfe.cn/Article/details/gt2rzlhskck.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.wangshuangyany.cn/Article/details/gt2grrhqwrb.html

JS:   crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nutmcvzd.html

TS:   crypto.randomUUID()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nuvgzdhi.html

Java: UUID.randomUUID().toString()
来源：http://dali.cqqwz.cn/Article/details/gt2pdrzaymt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.daxiang520.top/Article/details/gt2qurvwbhy.html

Ruby: SecureRandom.uuid
来源：http://dali.jlsjyb.cn/Article/details/gt2miaiviwo.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.andypj.xyz/Article/details/gt2gccxubgl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jyoumei.cn/Article/details/gt2epdrltub.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.tianlin.xyz/Article/details/gt2pagannmc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.tianlin.xyz/Article/details/gt2wqprybgr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yvedp.cn/Article/details/gt2kablqsqd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cashguo.top/Article/details/gt2gmwjciab.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sxryk.cn/Article/details/gt2jbvdhuua.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jqgufenzy.top/Article/details/gt2tiiflkwk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yonumen.top/Article/details/gt2locjwpjw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.svipenyu.cn/Article/details/gt2mehecqvj.html

[P03] 生成短随机字符串
来源：http://dali.jianghu66.top/Article/details/gt2ksnlelvu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.iojbl.cn/Article/details/gt2bznmlqir.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.mhx1999.top/Article/details/gt2hirmiiry.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pengpengdd.cyou/Article/details/gt2izugdwzz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhengqikj.top/Article/details/gt2ffggzbsb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.chenzaomai.com/Article/details/gt2kjitlymo.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ppjwa.cn/Article/details/gt2yscrrziz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.fengsongda.top/Article/details/gt2zihgguop.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zycfv.cn/Article/details/gt2qezkfexo.html

[P04] 求长度
来源：http://dali.cashguo.top/Article/details/gt2qkyhdyyk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.c1oappe.top/Article/details/gt2sdnfrzmu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gt2khvrpfsl.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yanxiufei.cn/Article/details/gt2yeeefevu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dashuyun.cn/Article/details/gt2yqjiaavz.html


<!-- 参考信息 -->