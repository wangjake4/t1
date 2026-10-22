代发 wailian999

Py:   resp.json()
来源：http://dali.jinqigufen.top/Article/details/gt2evfglovg.html

PHP:  json_decode($body, true);
来源：http://dali.jianghu66.top/Article/details/gt2fuzdtvbp.html

JS:   await resp.json()
来源：http://dali.jyoumei.cn/Article/details/gt2dpgwtgdf.html

TS:   await resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cmevsknu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.c1oappe.top/Article/details/gt2oaoamdvy.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ickqehnd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cheryme.top/Article/details/gt2seggzbgu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yuxming.cn/Article/details/gt2yrvmltwx.html

[L07] 处理 HTTP 状态码
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kxezrirz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ybcxt.top/Article/details/gt2ftdpbwma.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jqgfzy.top/Article/details/gt2hixdwgxd.html

JS:   resp.ok;  resp.status
来源：http://dali.vqdsnc.cn/Article/details/gt2tceddktj.html

TS:   resp.ok;  resp.status
来源：http://dali.ehwqpu.com/Article/details/gt2zajvlrma.html

Java: resp.statusCode()
来源：http://dali.zhiwuduotai.top/Article/details/gt2wriwwfla.html

Go:   resp.StatusCode
来源：http://dali.redwolf501.top/Article/details/gt2mdhbvqnr.html

Ruby: resp.code.to_i
来源：http://dali.cashguo.top/Article/details/gt2oztqeqgr.html

C#:   (int)resp.StatusCode
来源：http://dali.jinqigfzy.top/Article/details/gt2gvexizgx.html

[L08] 并发请求多个地址
来源：http://dali.nanxuanxn.top/Article/details/gt2nmpiglco.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yongpay.top/Article/details/gt2loagduaj.html

PHP:  curl_multi_init() 系列
来源：http://dali.9152youxi.cn/Article/details/gt2prahmleq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj202588.top/Article/details/gt2ocmvkcyd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gt2vtlnmvcb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.tian-w.cn/Article/details/gt2cxolrceg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.redwolf501.top/Article/details/gt2pveovxtf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.kuanghao11.cn/Article/details/gt2fgfrsnxb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.meibo888.top/Article/details/gt2ltmfakkm.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2qgkdersi.html

M. 命令行 / 进程 / 环境
来源：http://dali.xylfe.cn/Article/details/gt2sbukbmnb.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2tkmzjyom.html

[M01] 读取命令行参数
来源：http://dali.svipenyu.cn/Article/details/gt2vztrnkiz.html

Py:   sys.argv[1:]
来源：http://dali.aizwys.cn/Article/details/gt2csmamzrh.html

PHP:  $argv;  $argc;
来源：http://dali.quarkkingdee.top/Article/details/gt2blmuozpw.html

JS:   process.argv.slice(2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vxdbqnnn.html

TS:   process.argv.slice(2)
来源：http://dali.c1oappe.top/Article/details/gt2rjcodxdp.html

Java: args 数组（main 方法参数）
来源：http://dali.jyoumei.cn/Article/details/gt2feoecdgr.html

Go:   os.Args[1:]
来源：http://dali.sweek.top/Article/details/gt2jkwoiwvb.html

Ruby: ARGV
来源：http://dali.yueranfly.top/Article/details/gt2xkzvziyp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.iojbl.cn/Article/details/gt2geibnlav.html

[M02] 读取环境变量
来源：http://dali.yuxming.cn/Article/details/gt2wxfeedeg.html

Py:   os.environ.get("HOME")
来源：http://dali.andypj.xyz/Article/details/gt2bvztmokk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.smart0.xyz/Article/details/gt2vhigkjci.html

JS:   process.env.HOME
来源：http://dali.tianlin.xyz/Article/details/gt2wbftllau.html

TS:   process.env.HOME
来源：http://dali.jqgfzy.top/Article/details/gt2srjbftvy.html

Java: System.getenv("HOME")
来源：http://dali.yvedp.cn/Article/details/gt2zmbuxhsy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.guannengcc.top/Article/details/gt2vhxqipec.html

Ruby: ENV["HOME"]
来源：http://dali.9152youxi.cn/Article/details/gt2shyzcsou.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xylfe.cn/Article/details/gt2efcwszpt.html

[M03] 执行外部命令
来源：http://dali.kuanghao11.cn/Article/details/gt2zvewbdam.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zycfv.cn/Article/details/gt2zxsexilp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tianlin.xyz/Article/details/gt2mzstqgri.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tianlin.xyz/Article/details/gt2xkncjhjk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jiagoushi.top/Article/details/gt2frkqjwpi.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.feifeiyinyue.top/Article/details/gt2vrokmpaz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ivvv.top/Article/details/gt2qrdjtvze.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cvwzlvfk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yj20258888.top/Article/details/gt2wauccokf.html

[M04] 获取当前工作目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nzbdzmzh.html

Py:   os.getcwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ftnfzlwi.html

PHP:  getcwd();
来源：http://dali.jiagoushi.top/Article/details/gt2rthdzhbl.html

JS:   process.cwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kopjbapg.html

TS:   process.cwd()
来源：http://dali.aibaodan.cn/Article/details/gt2pvpedgdf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.tanke756.top/Article/details/gt2picqcbod.html

Go:   os.Getwd()
来源：http://dali.birdmap.top/Article/details/gt2otvrubpa.html

Ruby: Dir.pwd
来源：http://dali.yonumen.top/Article/details/gt2uoodkoqq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yvedp.cn/Article/details/gt2teyuanuw.html

[M05] 设置退出码
来源：http://dali.nanxinkj.top/Article/details/gt2mtljtdia.html

Py:   sys.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ppwtuykd.html

PHP:  exit(1);
来源：http://dali.fzhhl.top/Article/details/gt2kufxsnnb.html

JS:   process.exit(1)
来源：http://dali.yvedp.cn/Article/details/gt2jhcoicxh.html

TS:   process.exit(1)
来源：http://dali.aizwys.cn/Article/details/gt2ozwzlkdw.html

Java: System.exit(1)
来源：http://dali.fzhhl.top/Article/details/gt2vvqrmqzw.html

Go:   os.Exit(1)
来源：http://dali.hnqzz.top/Article/details/gt2wbtppckb.html

Ruby: exit 1
来源：http://dali.sysykeji.top/Article/details/gt2mygftwec.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xziqi.cn/Article/details/gt2zqvxbkdm.html

[M06] 向标准错误输出
来源：http://dali.ydzc1.top/Article/details/gt2drjhckgx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.haohaochexian.top/Article/details/gt2zfsraqib.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gpgongqd.html

JS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gt2poicxjyk.html

TS:   console.error("err")
来源：http://dali.cheryme.top/Article/details/gt2fvjrpqxq.html

Java: System.err.println("err")
来源：http://dali.hongshengwenyu.top/Article/details/gt2mpjipcnb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cashguo.top/Article/details/gt2winmsgkm.html

Ruby: warn "err"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sptdhzfo.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yuxming.cn/Article/details/gt2ucjvvqwe.html

[M07] 判断是否为主入口
来源：http://dali.jqgfzy.top/Article/details/gt2vwbgwnmm.html

Py:   if __name__ == "__main__":
来源：http://dali.daxiang520.top/Article/details/gt2hvuxdawa.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.vqdsnc.cn/Article/details/gt2xieknapx.html

JS:   require.main === module
来源：http://dali.cashguo.top/Article/details/gt2nvdcgzts.html

TS:   require.main === module
来源：http://dali.gzhubu.top/Article/details/gt2uxgilduq.html

Java: public static void main(String[] args)
来源：http://dali.daxiang520.top/Article/details/gt2cbkbcdcr.html

Go:   func main()
来源：http://dali.nanxuanxn.top/Article/details/gt2mknpbnff.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.wangshuangyany.cn/Article/details/gt2edwbemca.html

C#:   static void Main(string[] args)
来源：http://dali.daria6918.cn/Article/details/gt2ldbwgkvj.html

[M08] 获取系统与运行时信息
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qxhyaktw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.smart0.xyz/Article/details/gt2wqljcaaw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hongshengwenyu.top/Article/details/gt2wsdxmptc.html

JS:   process.platform;  process.version
来源：http://dali.guowangkeji.top/Article/details/gt2hfkcixgs.html

TS:   process.platform;  process.version
来源：http://dali.yuxming.cn/Article/details/gt2lplssclm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sufxvd.cn/Article/details/gt2cqcxcajf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ivvv.top/Article/details/gt2ndtadatc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhongyouzk.top/Article/details/gt2thkuluzy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sxryk.cn/Article/details/gt2abbexjla.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2alzlrzwy.html

N. 数据结构与算法
来源：http://dali.yj202588.top/Article/details/gt2bckpsyxi.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2wduwibwu.html

[N01] 二分查找（有序数组）
来源：http://dali.xuanzx.com/Article/details/gt2baszuivp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.guannengcc.top/Article/details/gt2ljtddekg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.c1oappe.top/Article/details/gt2axxevepn.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xylfe.cn/Article/details/gt2kkoaeoif.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenlongwang.top/Article/details/gt2zvojpgcb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gt2nyekqzim.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gt2edltglsv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xuetiantiany.cn/Article/details/gt2qglocara.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gt2zgwyvina.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.9152youxi.cn/Article/details/gt2rqvulhqp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhongyouzk.top/Article/details/gt2bkhmbjhx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nanxuanxn.top/Article/details/gt2ccblpfty.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sweek.top/Article/details/gt2ltododep.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.meibo888.top/Article/details/gt2xbmdmsdl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shzxlz.cn/Article/details/gt2kxpfmvtt.html

Go:   slices.Sort(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2secpugok.html

Ruby: arr.sort
来源：http://dali.guowangkeji.top/Article/details/gt2qntsixiz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.aizwys.cn/Article/details/gt2pktjrrcm.html

[N03] 快速排序（分治示例）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wypauhzq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hammf.cn/Article/details/gt2pspzpzvj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.quarkkingdee.top/Article/details/gt2laitpcrb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.haohaochexian.top/Article/details/gt2ncfgoqte.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.316326.xyz/Article/details/gt2knbrbqur.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xuetiantiany.cn/Article/details/gt2bhymuqip.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhongyouzk.top/Article/details/gt2krgtrqln.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.nwbrower.top/Article/details/gt2zvdtxgok.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhiwuduotai.top/Article/details/gt2zususjxv.html

[N04] 斐波那契数列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pzxvqkgs.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.andypj.xyz/Article/details/gt2zinotoub.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gt2stkdcxkb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gt2tjpgzhpk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pwkpzomn.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ydzc1.top/Article/details/gt2tksxogxz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cashguo.top/Article/details/gt2bhgidjhk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.svipenyu.cn/Article/details/gt2tbvkhsql.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gt2lrfqlenv.html

[N05] 最大公约数
来源：http://dali.hysaishi.cn/Article/details/gt2pvmsqrmj.html

Py:   math.gcd(a, b)
来源：http://dali.andypj.xyz/Article/details/gt2rdulcuvb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.guannengcc.top/Article/details/gt2ljdnbdgx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj202588.top/Article/details/gt2hesgjabm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cucudq.cn/Article/details/gt2pylakfkn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.pengpengdd.cyou/Article/details/gt2pjaevwqy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.nwbrower.top/Article/details/gt2wocmgich.html

Ruby: a.gcd(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uchvqlrf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.snrcjt.cn/Article/details/gt2bziwydit.html

[N06] 判断回文字符串
来源：http://dali.mhx1999.top/Article/details/gt2ghushlsf.html

Py:   s == s[::-1]
来源：http://dali.jianghu66.top/Article/details/gt2tswilstr.html

PHP:  $s === strrev($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wenkzhcw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gt2ndhesrci.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gt2gdxweecd.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.0kj1m.cn/Article/details/gt2lrcrzsfw.html

Go:   // 双指针从两端比较
来源：http://dali.yangfankeji.com/Article/details/gt2jwlstbyr.html

Ruby: s == s.reverse
来源：http://dali.c1oappe.top/Article/details/gt2rdjgiqkj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.andypj.xyz/Article/details/gt2qiqgxcvr.html

[N07] 两数之和（返回下标）
来源：http://dali.hnxiangtu.top/Article/details/gt2nswftmpv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.bjfxy.top/Article/details/gt2merryrxc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jyoumei.cn/Article/details/gt2rirqbphu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yanxiufei.cn/Article/details/gt2pzajqgzt.html

TS:   // 手写 Map<string, number>
来源：http://dali.shangyingyoupin.top/Article/details/gt2mjberorg.html

Java: // 手写 HashMap
来源：http://dali.snrcjt.cn/Article/details/gt2oifekgmj.html

Go:   // 手写 map[int]int
来源：http://dali.jianghu66.top/Article/details/gt2tfzzyssf.html

Ruby: // 手写 Hash
来源：http://dali.316326.xyz/Article/details/gt2xzwcpdmf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cheryme.top/Article/details/gt2trqsuval.html

[N08] 生成全排列
来源：http://dali.hfpthk.cn/Article/details/gt2barowasq.html

Py:   itertools.permutations(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2ywsunouo.html

PHP:  // 手写递归交换
来源：http://dali.xinyue.icu/Article/details/gt2xlebmodn.html

JS:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gt2dswzcanl.html

TS:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gt2yyitbfux.html

Java: // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gt2chzaiiaw.html

Go:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gt2disiitgp.html

Ruby: arr.permutation.to_a
来源：http://dali.ppjwa.cn/Article/details/gt2yeojgxzx.html

C#:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gt2linvttxj.html

[N09] 栈与队列
来源：http://dali.nwbrower.top/Article/details/gt2oxzwtnmp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gzhubu.top/Article/details/gt2ucuobthv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.daria6918.cn/Article/details/gt2ebvexczy.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hnxiangtu.top/Article/details/gt2tynlpafj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nanxuanxn.top/Article/details/gt2vqumernf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hongshengwenyu.top/Article/details/gt2gsmlgevr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.meibo888.top/Article/details/gt2htromxfx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cwfkjnlo.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sufxvd.cn/Article/details/gt2gwwmtflu.html

[N10] 链表节点定义
来源：http://dali.jqgfzy.top/Article/details/gt2jlmvnqkq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2machgijv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zycfv.cn/Article/details/gt2htezvyxk.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.aibaodan.cn/Article/details/gt2hhyqkcpc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.guowangkeji.top/Article/details/gt2tgnmmtka.html

Java: class Node { int v; Node next; }
来源：http://dali.gaohongyu789.top/Article/details/gt2yigwkvuk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jqgufenzy.top/Article/details/gt2kynshhko.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cashguo.top/Article/details/gt2wjpdswam.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.aizwys.cn/Article/details/gt2gdqunshu.html

[N11] 二叉树中序遍历
来源：http://dali.hnqzz.top/Article/details/gt2xypfnbmf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xuanzx.com/Article/details/gt2bclhrhbw.html

PHP:  // 手写递归函数
来源：http://dali.hnqzz.top/Article/details/gt2jmlwsamg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tpmliqkc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aibaodan.cn/Article/details/gt2fqtxtajy.html

Java: // 手写递归
来源：http://dali.gaohongyu789.top/Article/details/gt2qdoomodb.html

Go:   // 手写递归
来源：http://dali.shuidangran.top/Article/details/gt2tjoahloe.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yanxiufei.cn/Article/details/gt2itbdgedn.html

C#:   // 手写递归
来源：http://dali.tian-w.cn/Article/details/gt2vnowrpvl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cucudq.cn/Article/details/gt2paaqvsko.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jlsjyb.cn/Article/details/gt2bngbsujf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.0kj1m.cn/Article/details/gt2nxzywbzc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj202588.top/Article/details/gt2wivgrmuy.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.feifeiyinyue.top/Article/details/gt2qyspdxlh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vrnttdmm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jlsjyb.cn/Article/details/gt2kzvgitby.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sxryk.cn/Article/details/gt2sgunswvp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sweek.top/Article/details/gt2mhtkvwhb.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2pblqohvu.html

O. 并发与异步
来源：http://dali.ivvv.top/Article/details/gt2ihhwkwxc.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2swusmvjb.html

[O01] 启动一个线程
来源：http://dali.fzhhl.top/Article/details/gt2jukdcybz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.guannengcc.top/Article/details/gt2caabeviy.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2czgmmhdk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xuanzx.com/Article/details/gt2ejnfksll.html

TS:   // 同 JS
来源：http://dali.chenjidiqi.icu/Article/details/gt2drtgucet.html

Java: new Thread(() -> f()).start()
来源：http://dali.hfpthk.cn/Article/details/gt2xzqkgbig.html

Go:   go f()
来源：http://dali.zhongyouzk.top/Article/details/gt2fhpdrseu.html

Ruby: Thread.new { f }
来源：http://dali.yonumen.top/Article/details/gt2wxpvfvhh.html

C#:   Task.Run(() => F());
来源：http://dali.vqdsnc.cn/Article/details/gt2jjxznwup.html

[O02] 使用线程池
来源：http://dali.wangshuangyany.cn/Article/details/gt2uljdzfuh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhengqikj.top/Article/details/gt2tlqypilc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ehwqpu.com/Article/details/gt2etggdudn.html

JS:   // worker_threads 线程池
来源：http://dali.yuxming.cn/Article/details/gt2gzusgexb.html

TS:   // worker_threads 线程池
来源：http://dali.chenjidiqi.icu/Article/details/gt2yrwsjwnd.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yueranfly.top/Article/details/gt2timrevxm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gotoacloud.top/Article/details/gt2zqdrdces.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gotoacloud.top/Article/details/gt2utceqfbt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ybcxt.top/Article/details/gt2zetrvene.html

[O03] 加锁保护共享数据
来源：http://dali.ehwqpu.com/Article/details/gt2bammldms.html

Py:   with lock: shared += 1
来源：http://dali.dianchejie.cn/Article/details/gt2wicuspig.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gotoacloud.top/Article/details/gt2mawtvuyr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.nanxinkj.top/Article/details/gt2dnulrisr.html

TS:   // 同 JS
来源：http://dali.yj202588.top/Article/details/gt2kpskdqif.html

Java: synchronized (this) { shared++; }
来源：http://dali.shuidangran.top/Article/details/gt2orzfnhsl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.snrcjt.cn/Article/details/gt2uzqqzviw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.chenlongwang.top/Article/details/gt2ahtszvus.html

C#:   lock (gate) { shared++; }
来源：http://dali.haohaochexian.top/Article/details/gt2bapxagbr.html

[O04] 定义异步函数并等待
来源：http://dali.xuetiantiany.cn/Article/details/gt2ctoudnoc.html

Py:   async def f():⏎    await g()
来源：http://dali.yj20258.top/Article/details/gt2sdbejgel.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.havefunace.top/Article/details/gt2vwjgbsrp.html

JS:   async function f() { await g(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2raxlurlf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zycfv.cn/Article/details/gt2mtklkfci.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.kuanghao11.cn/Article/details/gt2qfznodul.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jiagoushi.top/Article/details/gt2vomjvugj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ybcxt.top/Article/details/gt2kbtnabti.html

C#:   async Task F() { await G(); }
来源：http://dali.yonumen.top/Article/details/gt2uimqzinx.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhongyouzk.top/Article/details/gt2gfqmduzz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jqgfzy.top/Article/details/gt2omnjbnnh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xuetiantiany.cn/Article/details/gt2kmqjxhvu.html

JS:   await Promise.all(tasks)
来源：http://dali.zhongyouzk.top/Article/details/gt2gsiiqhgn.html

TS:   await Promise.all(tasks)
来源：http://dali.zycfv.cn/Article/details/gt2apshxuuy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinqigufen.top/Article/details/gt2lmqnlybf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.nwbrower.top/Article/details/gt2hacopnxj.html

Ruby: threads.map(&:join)
来源：http://dali.yuanzhike.top/Article/details/gt2olafpxqr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yj202588.top/Article/details/gt2tqpwmzop.html

[O06] 使用进程池
来源：http://dali.kuanghao11.cn/Article/details/gt2ifsghcng.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.aizwys.cn/Article/details/gt2xpfoitue.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhongyouzk.top/Article/details/gt2cqneysrz.html

JS:   // child_process / cluster 模块
来源：http://dali.nwbrower.top/Article/details/gt2jxridfpb.html

TS:   // child_process / cluster 模块
来源：http://dali.cashguo.top/Article/details/gt2uvjjrzbp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jianghu66.top/Article/details/gt2mufgmakt.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.birdmap.top/Article/details/gt2iqhysrtk.html

Ruby: // fork 块
来源：http://dali.xinyue.icu/Article/details/gt2xlwwnxvf.html

C#:   Parallel.For
来源：http://dali.smart0.xyz/Article/details/gt2zybhqucl.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2pgubdoaf.html

P. 常用工具函数
来源：http://dali.quarkkingdee.top/Article/details/gt2hypbjiia.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2faahhxax.html

[P01] 生成 UUID
来源：http://dali.bjfxy.top/Article/details/gt2rwtmnshj.html

Py:   str(uuid.uuid4())
来源：http://dali.zdqjudy.top/Article/details/gt2dgwbqkdo.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.bjfxy.top/Article/details/gt2sgzcgxjk.html

JS:   crypto.randomUUID()
来源：http://dali.nanxinkj.top/Article/details/gt2dszqlsch.html

TS:   crypto.randomUUID()
来源：http://dali.shzxlz.cn/Article/details/gt2nqkjbqsz.html

Java: UUID.randomUUID().toString()
来源：http://dali.chenjidiqi.icu/Article/details/gt2xoyfysws.html

Go:   // 用 github.com/google/uuid
来源：http://dali.redwolf501.top/Article/details/gt2uolgglwr.html

Ruby: SecureRandom.uuid
来源：http://dali.hongshengwenyu.top/Article/details/gt2sytfntrl.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.guowangkeji.top/Article/details/gt2dgbvbgag.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gotoacloud.top/Article/details/gt2omvkrmhu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sysykeji.top/Article/details/gt2kwqovtuk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.snrcjt.cn/Article/details/gt2pjnfjfiy.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yj20258888.top/Article/details/gt2dryjfsdx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cheryme.top/Article/details/gt2lvitqgxy.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ppjwa.cn/Article/details/gt2gzbgdfsz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yongpay.top/Article/details/gt2smbupxsp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yueranfly.top/Article/details/gt2qhidkmds.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jlsjyb.cn/Article/details/gt2tmgtnobj.html

[P03] 生成短随机字符串
来源：http://dali.pycfn.com/Article/details/gt2ldtnvsuy.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.sufxvd.cn/Article/details/gt2isyhudml.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zdqjudy.top/Article/details/gt2duvbulsl.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.mhx1999.top/Article/details/gt2tmuztkue.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lfeljfjc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.gaohongyu789.top/Article/details/gt2prqgwyzp.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2xrerhjrf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhoulong.xyz/Article/details/gt2slgmjuly.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.aizwys.cn/Article/details/gt2wsysshix.html

[P04] 求长度
来源：http://dali.smart0.xyz/Article/details/gt2foybmyux.html


<!-- 参考信息 -->