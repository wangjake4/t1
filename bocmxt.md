代发 wailian999

[L07] 处理 HTTP 状态码
来源：http://dali.sweek.top/Article/details/gt2aqmgguso.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinqigfzy.top/Article/details/gt2zuyjsbmx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.dianchejie.cn/Article/details/gt2enoocoyd.html

JS:   resp.ok;  resp.status
来源：http://dali.daxiang520.top/Article/details/gt2oqzesvnj.html

TS:   resp.ok;  resp.status
来源：http://dali.pengpengdd.cyou/Article/details/gt2reeaadgx.html

Java: resp.statusCode()
来源：http://dali.iojbl.cn/Article/details/gt2irqywzzl.html

Go:   resp.StatusCode
来源：http://dali.shangyingyoupin.top/Article/details/gt2ciawhagk.html

Ruby: resp.code.to_i
来源：http://dali.cheryme.top/Article/details/gt2xsozqdxt.html

C#:   (int)resp.StatusCode
来源：http://dali.jqgufenzy.top/Article/details/gt2hzwomyvm.html

[L08] 并发请求多个地址
来源：http://dali.yuxming.cn/Article/details/gt2ykikwrnw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.tian-w.cn/Article/details/gt2rfuedmlm.html

PHP:  curl_multi_init() 系列
来源：http://dali.xylfe.cn/Article/details/gt2kklqgcym.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuxming.cn/Article/details/gt2ysnwvzmk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ppjwa.cn/Article/details/gt2tpdakotg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ybcxt.top/Article/details/gt2eqglnylz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jianghu66.top/Article/details/gt2mkjnsunn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.9152youxi.cn/Article/details/gt2jagrqiqo.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.andypj.xyz/Article/details/gt2hbpjopgo.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2paxaubpw.html

M. 命令行 / 进程 / 环境
来源：http://dali.0kj1m.cn/Article/details/gt2tpwnaejj.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2qcrztxpw.html

[M01] 读取命令行参数
来源：http://dali.daria6918.cn/Article/details/gt2xbzpiwlu.html

Py:   sys.argv[1:]
来源：http://dali.hnqzz.top/Article/details/gt2nkgvyfqh.html

PHP:  $argv;  $argc;
来源：http://dali.birdmap.top/Article/details/gt2hezjsbfb.html

JS:   process.argv.slice(2)
来源：http://dali.hfpthk.cn/Article/details/gt2zichimjn.html

TS:   process.argv.slice(2)
来源：http://dali.jqgfzy.top/Article/details/gt2qteniscq.html

Java: args 数组（main 方法参数）
来源：http://dali.vqdsnc.cn/Article/details/gt2zezgrvrt.html

Go:   os.Args[1:]
来源：http://dali.cucudq.cn/Article/details/gt2gymiiuls.html

Ruby: ARGV
来源：http://dali.ivvv.top/Article/details/gt2weeiujtc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinqigufen.top/Article/details/gt2jqleiexk.html

[M02] 读取环境变量
来源：http://dali.andypj.xyz/Article/details/gt2mkfquoqm.html

Py:   os.environ.get("HOME")
来源：http://dali.cdnleiting.top/Article/details/gt2rvttdael.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ppjwa.cn/Article/details/gt2decfcfrs.html

JS:   process.env.HOME
来源：http://dali.c1oappe.top/Article/details/gt2ouubknls.html

TS:   process.env.HOME
来源：http://dali.kuanghao11.cn/Article/details/gt2zssohmce.html

Java: System.getenv("HOME")
来源：http://dali.tian-w.cn/Article/details/gt2pebbunuv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.pycfn.com/Article/details/gt2nizzcvcm.html

Ruby: ENV["HOME"]
来源：http://dali.havefunace.top/Article/details/gt2nculgcqp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shzxlz.cn/Article/details/gt2zchrxwpx.html

[M03] 执行外部命令
来源：http://dali.dianchejie.cn/Article/details/gt2ugooomqm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.haohaochexian.top/Article/details/gt2rbsuewce.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.guowangkeji.top/Article/details/gt2thhsytws.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.9152youxi.cn/Article/details/gt2ckckffxl.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.0kj1m.cn/Article/details/gt2osxrsjhz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ewnarolo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tanke756.top/Article/details/gt2scpppync.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jqgufenzy.top/Article/details/gt2wkwfwezz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sweek.top/Article/details/gt2jsoonuzd.html

[M04] 获取当前工作目录
来源：http://dali.jianghu66.top/Article/details/gt2hgtpjjhj.html

Py:   os.getcwd()
来源：http://dali.9152youxi.cn/Article/details/gt2gzucmwoq.html

PHP:  getcwd();
来源：http://dali.chenzaomai.com/Article/details/gt2pjiurxkz.html

JS:   process.cwd()
来源：http://dali.havefunace.top/Article/details/gt2ulhhjlvt.html

TS:   process.cwd()
来源：http://dali.pycfn.com/Article/details/gt2ytodzarz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shangyingyoupin.top/Article/details/gt2qsuutatm.html

Go:   os.Getwd()
来源：http://dali.yueranfly.top/Article/details/gt2oaysihgy.html

Ruby: Dir.pwd
来源：http://dali.aizwys.cn/Article/details/gt2qkzucewl.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.bjfxy.top/Article/details/gt2kvnlatxa.html

[M05] 设置退出码
来源：http://dali.havefunace.top/Article/details/gt2pfoajqhl.html

Py:   sys.exit(1)
来源：http://dali.sweek.top/Article/details/gt2wedaqhxp.html

PHP:  exit(1);
来源：http://dali.nwbrower.top/Article/details/gt2yqqmqkno.html

JS:   process.exit(1)
来源：http://dali.fzhhl.top/Article/details/gt2tfgizoei.html

TS:   process.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gt2autefluh.html

Java: System.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rpfrgngy.html

Go:   os.Exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2bwemruok.html

Ruby: exit 1
来源：http://dali.snrcjt.cn/Article/details/gt2afikedcc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yonumen.top/Article/details/gt2xjjuggfg.html

[M06] 向标准错误输出
来源：http://dali.yj20258.top/Article/details/gt2fjezzshc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.chenlongwang.top/Article/details/gt2oyrrrlcd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gaohongyu789.top/Article/details/gt2ldqaakvi.html

JS:   console.error("err")
来源：http://dali.meibo888.top/Article/details/gt2tugbfdfu.html

TS:   console.error("err")
来源：http://dali.yj202588.top/Article/details/gt2lbglckie.html

Java: System.err.println("err")
来源：http://dali.fzhhl.top/Article/details/gt2hsdwtkey.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rnxehive.html

Ruby: warn "err"
来源：http://dali.jyoumei.cn/Article/details/gt2tgpiokol.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ybcxt.top/Article/details/gt2cnafjxnu.html

[M07] 判断是否为主入口
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vmwkoxgr.html

Py:   if __name__ == "__main__":
来源：http://dali.hongshengwenyu.top/Article/details/gt2xxcbbqjq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.aibaodan.cn/Article/details/gt2yjwczcdx.html

JS:   require.main === module
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ynpzqvup.html

TS:   require.main === module
来源：http://dali.sysykeji.top/Article/details/gt2uergugtz.html

Java: public static void main(String[] args)
来源：http://dali.vqdsnc.cn/Article/details/gt2ggilrysj.html

Go:   func main()
来源：http://dali.hammf.cn/Article/details/gt2vzcwlpvj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xinyue.icu/Article/details/gt2pfldgpuh.html

C#:   static void Main(string[] args)
来源：http://dali.vqdsnc.cn/Article/details/gt2jltkjykd.html

[M08] 获取系统与运行时信息
来源：http://dali.nanxuanxn.top/Article/details/gt2ycuyjjxp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jyoumei.cn/Article/details/gt2kxwmbhrs.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ppjwa.cn/Article/details/gt2jonlktgk.html

JS:   process.platform;  process.version
来源：http://dali.jinqigfzy.top/Article/details/gt2vhnpaomh.html

TS:   process.platform;  process.version
来源：http://dali.chenjidiqi.icu/Article/details/gt2sfzhfjcj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sweek.top/Article/details/gt2sfandpdp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.fengsongda.top/Article/details/gt2fukindwo.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yanxiufei.cn/Article/details/gt2jhjrxaiq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.quarkkingdee.top/Article/details/gt2krsxxats.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2wzjnllyk.html

N. 数据结构与算法
来源：http://dali.yuanzhike.top/Article/details/gt2cyefgibx.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2wiqvgxzp.html

[N01] 二分查找（有序数组）
来源：http://dali.xinyue.icu/Article/details/gt2qbrgtdes.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.fzhhl.top/Article/details/gt2usejheco.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.haohaochexian.top/Article/details/gt2oayxpdnx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.9152youxi.cn/Article/details/gt2uepbojwn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pycfn.com/Article/details/gt2gqrszvps.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gt2ctltxfgn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sysykeji.top/Article/details/gt2fyytxbdg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ppjwa.cn/Article/details/gt2ehxyjepa.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gt2hqcvnker.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.andypj.xyz/Article/details/gt2cznjkhyj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.0kj1m.cn/Article/details/gt2yuswfybz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cheryme.top/Article/details/gt2vfexuumw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigufen.top/Article/details/gt2obzmliss.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guannengcc.top/Article/details/gt2rhkrhveg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sxryk.cn/Article/details/gt2pcyxcclc.html

Go:   slices.Sort(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xajwgqre.html

Ruby: arr.sort
来源：http://dali.ehwqpu.com/Article/details/gt2dcneozkj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.c1oappe.top/Article/details/gt2slzdbvyw.html

[N03] 快速排序（分治示例）
来源：http://dali.andypj.xyz/Article/details/gt2soalnxpx.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.nwbrower.top/Article/details/gt2eueacybh.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zdqjudy.top/Article/details/gt2luurrhzu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuanzx.com/Article/details/gt2hofecuwk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhixingplan.top/Article/details/gt2phklgyqw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.pengpengdd.cyou/Article/details/gt2mbmzrunz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.kuanghao11.cn/Article/details/gt2itdxsjtg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.havefunace.top/Article/details/gt2ubcrjiyn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tanke756.top/Article/details/gt2ifyqognc.html

[N04] 斐波那契数列
来源：http://dali.sweek.top/Article/details/gt2deebahjb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ivvv.top/Article/details/gt2vcakwkyr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj20258888.top/Article/details/gt2kscfemuv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hfpthk.cn/Article/details/gt2uepkwrvb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cdnleiting.top/Article/details/gt2rkzgbkpx.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cdnleiting.top/Article/details/gt2sewnogqj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yj20258.top/Article/details/gt2qdwjwapi.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.c1oappe.top/Article/details/gt2jrybdhee.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sxryk.cn/Article/details/gt2unmgkkry.html

[N05] 最大公约数
来源：http://dali.mhx1999.top/Article/details/gt2uumaujui.html

Py:   math.gcd(a, b)
来源：http://dali.zycfv.cn/Article/details/gt2yqgitjbl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jlsjyb.cn/Article/details/gt2bcmbjysk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ydzc1.top/Article/details/gt2zdcrbrbt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zsosflok.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.pengpengdd.cyou/Article/details/gt2ppqghwsh.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hnxiangtu.top/Article/details/gt2cszemdcd.html

Ruby: a.gcd(b)
来源：http://dali.cucudq.cn/Article/details/gt2uupbxxtj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.pycfn.com/Article/details/gt2heyryqva.html

[N06] 判断回文字符串
来源：http://dali.daxiang520.top/Article/details/gt2mzdkzntb.html

Py:   s == s[::-1]
来源：http://dali.hammf.cn/Article/details/gt2eaoirtqd.html

PHP:  $s === strrev($s);
来源：http://dali.dianchejie.cn/Article/details/gt2xtvfxdkl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gt2ftkluyur.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gt2sdtsyrtr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.tian-w.cn/Article/details/gt2xcbawnqa.html

Go:   // 双指针从两端比较
来源：http://dali.svipenyu.cn/Article/details/gt2uuxekmqp.html

Ruby: s == s.reverse
来源：http://dali.zhengqikj.top/Article/details/gt2uonhqtky.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinqigfzy.top/Article/details/gt2whasiefb.html

[N07] 两数之和（返回下标）
来源：http://dali.yj20258.top/Article/details/gt2olysijuo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.havefunace.top/Article/details/gt2mszjpiml.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hbuxcmel.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yonumen.top/Article/details/gt2qojwzdbb.html

TS:   // 手写 Map<string, number>
来源：http://dali.tanke756.top/Article/details/gt2ffmguqiw.html

Java: // 手写 HashMap
来源：http://dali.nanxuanxn.top/Article/details/gt2vhbudapd.html

Go:   // 手写 map[int]int
来源：http://dali.dianchejie.cn/Article/details/gt2olomsqao.html

Ruby: // 手写 Hash
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qmjudqpa.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gotoacloud.top/Article/details/gt2plzonqnk.html

[N08] 生成全排列
来源：http://dali.tianlin.xyz/Article/details/gt2clqvfbyq.html

Py:   itertools.permutations(arr)
来源：http://dali.ivvv.top/Article/details/gt2mfosrrpz.html

PHP:  // 手写递归交换
来源：http://dali.9152youxi.cn/Article/details/gt2tecdasiv.html

JS:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gt2sacuqkwk.html

TS:   // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gt2rwcigxip.html

Java: // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gt2iuafanoj.html

Go:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gt2wxpssdqz.html

Ruby: arr.permutation.to_a
来源：http://dali.andypj.xyz/Article/details/gt2jrzqatah.html

C#:   // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gt2ezjraiuo.html

[N09] 栈与队列
来源：http://dali.chenjidiqi.icu/Article/details/gt2efomjdzf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gt2xxsctrxd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhoulong.xyz/Article/details/gt2xxrugjel.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.9152youxi.cn/Article/details/gt2jaxclmbw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uccdhccv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yangfankeji.com/Article/details/gt2oxtmvsuy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.316326.xyz/Article/details/gt2glrqmspl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gt2juscwwzd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenzaomai.com/Article/details/gt2nxrsukaz.html

[N10] 链表节点定义
来源：http://dali.daria6918.cn/Article/details/gt2gaqeoshp.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ybcxt.top/Article/details/gt2lpkdlyog.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhongyouzk.top/Article/details/gt2nizkaayz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zrlayzmd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.pycfn.com/Article/details/gt2jrpjmcrj.html

Java: class Node { int v; Node next; }
来源：http://dali.pycfn.com/Article/details/gt2dykucbkn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hnxiangtu.top/Article/details/gt2bqdjfyra.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hnqzz.top/Article/details/gt2ovkgnjgm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jlsjyb.cn/Article/details/gt2uxtbcvoa.html

[N11] 二叉树中序遍历
来源：http://dali.nwbrower.top/Article/details/gt2prtxukqv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.andypj.xyz/Article/details/gt2cqagkwch.html

PHP:  // 手写递归函数
来源：http://dali.svipenyu.cn/Article/details/gt2dsjzqkbu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.kuanghao11.cn/Article/details/gt2noputdoo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.feifeiyinyue.top/Article/details/gt2palxjgpf.html

Java: // 手写递归
来源：http://dali.ppjwa.cn/Article/details/gt2nekbbrul.html

Go:   // 手写递归
来源：http://dali.cqqwz.cn/Article/details/gt2tsacaawa.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yj20258.top/Article/details/gt2bjuglduv.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmweluv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jqgfzy.top/Article/details/gt2mbwhlqbr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.quarkkingdee.top/Article/details/gt2zqsghsph.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shangyingyoupin.top/Article/details/gt2maezpllj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shangyingyoupin.top/Article/details/gt2qhslelaw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.birdmap.top/Article/details/gt2bpydwirs.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258.top/Article/details/gt2ggnkmpmx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.gzhubu.top/Article/details/gt2vsqgjtpw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yanxiufei.cn/Article/details/gt2xaxujwhg.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.snrcjt.cn/Article/details/gt2qqbjixdw.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2kynibfsv.html

O. 并发与异步
来源：http://dali.0kj1m.cn/Article/details/gt2rihrbewn.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2adjuyzac.html

[O01] 启动一个线程
来源：http://dali.9152youxi.cn/Article/details/gt2pzvjuaqc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.9152youxi.cn/Article/details/gt2sdxmfbhb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.guowangkeji.top/Article/details/gt2wehebpuw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jiagoushi.top/Article/details/gt2xuujrjvh.html

TS:   // 同 JS
来源：http://dali.nanxuanxn.top/Article/details/gt2qqluiqro.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinqigfzy.top/Article/details/gt2szmuvcck.html

Go:   go f()
来源：http://dali.yangfankeji.com/Article/details/gt2lrmnylyx.html

Ruby: Thread.new { f }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ckesymuv.html

C#:   Task.Run(() => F());
来源：http://dali.9152youxi.cn/Article/details/gt2ivurtijc.html

[O02] 使用线程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rrsyycvk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.chenlongwang.top/Article/details/gt2aedotdvf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinqigufen.top/Article/details/gt2txrcmiqi.html

JS:   // worker_threads 线程池
来源：http://dali.yj202588.top/Article/details/gt2vxgcupqj.html

TS:   // worker_threads 线程池
来源：http://dali.quarkkingdee.top/Article/details/gt2bfnnpips.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2thgsqufl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yj20258.top/Article/details/gt2uwcepvle.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tuokvaiy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cheryme.top/Article/details/gt2fellbkwh.html

[O03] 加锁保护共享数据
来源：http://dali.cdnleiting.top/Article/details/gt2xpqmqfpc.html

Py:   with lock: shared += 1
来源：http://dali.sufxvd.cn/Article/details/gt2qdvvpesc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.tian-w.cn/Article/details/gt2lupvrdho.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hfpthk.cn/Article/details/gt2ropqkeeg.html

TS:   // 同 JS
来源：http://dali.zdqjudy.top/Article/details/gt2mkrexzso.html

Java: synchronized (this) { shared++; }
来源：http://dali.jiagoushi.top/Article/details/gt2prtvflay.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.guowangkeji.top/Article/details/gt2rlyrnevh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhongyouzk.top/Article/details/gt2dstxpmos.html

C#:   lock (gate) { shared++; }
来源：http://dali.dashuyun.cn/Article/details/gt2crbvicve.html

[O04] 定义异步函数并等待
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sdnafsbf.html

Py:   async def f():⏎    await g()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2joahrrqp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.tanke756.top/Article/details/gt2sggdzgfp.html

JS:   async function f() { await g(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2mxlnxcfz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.redwolf501.top/Article/details/gt2rorjeobo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.dianchejie.cn/Article/details/gt2klpononp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xuetiantiany.cn/Article/details/gt2zbywzibq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yvedp.cn/Article/details/gt2jjnymval.html

C#:   async Task F() { await G(); }
来源：http://dali.jyoumei.cn/Article/details/gt2zifqjkmy.html

[O05] 并发执行并等待全部完成
来源：http://dali.pycfn.com/Article/details/gt2igudiant.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ecfjsyow.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hywenlv.cn/Article/details/gt2enyveruo.html

JS:   await Promise.all(tasks)
来源：http://dali.zhongyouzk.top/Article/details/gt2qxjfxwsz.html

TS:   await Promise.all(tasks)
来源：http://dali.nanxuanxn.top/Article/details/gt2ocungokn.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.pengpengdd.cyou/Article/details/gt2aoykragk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xuanzx.com/Article/details/gt2gdjeqppu.html

Ruby: threads.map(&:join)
来源：http://dali.mhx1999.top/Article/details/gt2aagxkpfp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.vqdsnc.cn/Article/details/gt2jwrhvxqi.html

[O06] 使用进程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nvjbmeqj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yuanzhike.top/Article/details/gt2mhjqvwix.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.redwolf501.top/Article/details/gt2hmqgkmdx.html

JS:   // child_process / cluster 模块
来源：http://dali.shuidangran.top/Article/details/gt2zesqxnly.html

TS:   // child_process / cluster 模块
来源：http://dali.mhx1999.top/Article/details/gt2pnxqnvfv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.9152youxi.cn/Article/details/gt2omophvys.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tian-w.cn/Article/details/gt2nrcffxvr.html

Ruby: // fork 块
来源：http://dali.xziqi.cn/Article/details/gt2rjvxntaj.html

C#:   Parallel.For
来源：http://dali.ydzc1.top/Article/details/gt2twzejclk.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rfyzxegh.html

P. 常用工具函数
来源：http://dali.0kj1m.cn/Article/details/gt2drizsaqk.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2dwmjldur.html

[P01] 生成 UUID
来源：http://dali.nwbrower.top/Article/details/gt2zoziihri.html

Py:   str(uuid.uuid4())
来源：http://dali.birdmap.top/Article/details/gt2rdjmrair.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jlsjyb.cn/Article/details/gt2ycrcjutg.html

JS:   crypto.randomUUID()
来源：http://dali.ppjwa.cn/Article/details/gt2hospdhhe.html

TS:   crypto.randomUUID()
来源：http://dali.xziqi.cn/Article/details/gt2awnvvnzn.html

Java: UUID.randomUUID().toString()
来源：http://dali.cdnleiting.top/Article/details/gt2oljefdtt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.quarkkingdee.top/Article/details/gt2fezqkqrp.html

Ruby: SecureRandom.uuid
来源：http://dali.nanxinkj.top/Article/details/gt2ahtiuiqv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.dashuyun.cn/Article/details/gt2zafxpwtp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.daxiang520.top/Article/details/gt2gqjahvlc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hammf.cn/Article/details/gt2ixkzlnrg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.havefunace.top/Article/details/gt2jixomwer.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hnqzz.top/Article/details/gt2vsrlrrfv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jianghu66.top/Article/details/gt2hfeodjyu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.meibo888.top/Article/details/gt2trdtmsww.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.tian-w.cn/Article/details/gt2hliwhbzy.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2pxjpbuwa.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zdqjudy.top/Article/details/gt2bpmlheze.html

[P03] 生成短随机字符串
来源：http://dali.jinqigufen.top/Article/details/gt2mprneroy.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.pengpengdd.cyou/Article/details/gt2dhcntqgp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.meibo888.top/Article/details/gt2lernzmxw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ojmpyxle.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.9152youxi.cn/Article/details/gt2tvulnvgt.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sxryk.cn/Article/details/gt2ygeepbkz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jlsjyb.cn/Article/details/gt2yhpwvqjs.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.tian-w.cn/Article/details/gt2jpseenrt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhongyouzk.top/Article/details/gt2vkxveovi.html

[P04] 求长度
来源：http://dali.quarkkingdee.top/Article/details/gt2fkytfsmt.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shuidangran.top/Article/details/gt2ftulkuxv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gt2xpdudpxa.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tianlin.xyz/Article/details/gt2rjptdksq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yueranfly.top/Article/details/gt2zsnbjbqv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yanxiufei.cn/Article/details/gt2yiqhmfhv.html

Go:   len(arr);  len(m)
来源：http://dali.jiagoushi.top/Article/details/gt2yyjodffo.html

Ruby: x.length;  x.size
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dvvvjxkh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.tanke756.top/Article/details/gt2riihmpue.html


<!-- 参考信息 -->