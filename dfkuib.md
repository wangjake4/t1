代发 wailian999

Py:   resp.json()
来源：http://dali.jqgfzy.top/Article/details/gt2ecwuyxii.html

PHP:  json_decode($body, true);
来源：http://dali.cashguo.top/Article/details/gt2npnqhvnw.html

JS:   await resp.json()
来源：http://dali.shzxlz.cn/Article/details/gt2elckqgff.html

TS:   await resp.json()
来源：http://dali.aizwys.cn/Article/details/gt2ctljmqvt.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xylfe.cn/Article/details/gt2ckthosjv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.svipenyu.cn/Article/details/gt2gpvhxmyf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.dashuyun.cn/Article/details/gt2lltkpasr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.birdmap.top/Article/details/gt2fozofgcx.html

[L07] 处理 HTTP 状态码
来源：http://dali.jyoumei.cn/Article/details/gt2jpipghdy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tian-w.cn/Article/details/gt2meggbxje.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yonumen.top/Article/details/gt2rknobnhy.html

JS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ilcvguit.html

TS:   resp.ok;  resp.status
来源：http://dali.hammf.cn/Article/details/gt2uirjerpw.html

Java: resp.statusCode()
来源：http://dali.tanke756.top/Article/details/gt2wvjfjobn.html

Go:   resp.StatusCode
来源：http://dali.xuanzx.com/Article/details/gt2diqcsagj.html

Ruby: resp.code.to_i
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rannthiz.html

C#:   (int)resp.StatusCode
来源：http://dali.mhx1999.top/Article/details/gt2qkoyldqu.html

[L08] 并发请求多个地址
来源：http://dali.wangdashe.top/Article/details/gt2qruigssf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gotoacloud.top/Article/details/gt2mojnenqj.html

PHP:  curl_multi_init() 系列
来源：http://dali.9152youxi.cn/Article/details/gt2wqoqcrwv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uzowjjtm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iqkrcoaw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sdnhnxrm.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.tianlin.xyz/Article/details/gt2flkffvxz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shangyingyoupin.top/Article/details/gt2aublfqjm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.316326.xyz/Article/details/gt2ffoymcyt.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2yedsormu.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenlongwang.top/Article/details/gt2quosnswq.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2hfiiinwx.html

[M01] 读取命令行参数
来源：http://dali.haohaochexian.top/Article/details/gt2tbtshzqe.html

Py:   sys.argv[1:]
来源：http://dali.hysaishi.cn/Article/details/gt2wqvcclbo.html

PHP:  $argv;  $argc;
来源：http://dali.wangdashe.top/Article/details/gt2rsyssqmg.html

JS:   process.argv.slice(2)
来源：http://dali.nanxinkj.top/Article/details/gt2aiqqxhae.html

TS:   process.argv.slice(2)
来源：http://dali.cashguo.top/Article/details/gt2mmsnrkgq.html

Java: args 数组（main 方法参数）
来源：http://dali.jqgufenzy.top/Article/details/gt2nfudvhpj.html

Go:   os.Args[1:]
来源：http://dali.hnqzz.top/Article/details/gt2pxrfeece.html

Ruby: ARGV
来源：http://dali.jqgfzy.top/Article/details/gt2jeozamsb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xziqi.cn/Article/details/gt2wrmdfdpz.html

[M02] 读取环境变量
来源：http://dali.tanke756.top/Article/details/gt2yjcgzmca.html

Py:   os.environ.get("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gt2pyfkeffc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jyoumei.cn/Article/details/gt2hogvryvn.html

JS:   process.env.HOME
来源：http://dali.ehwqpu.com/Article/details/gt2gjuredtb.html

TS:   process.env.HOME
来源：http://dali.haohaochexian.top/Article/details/gt2wxuqwebq.html

Java: System.getenv("HOME")
来源：http://dali.jinqigufen.top/Article/details/gt2lqsdlijl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yangfankeji.com/Article/details/gt2deynbfae.html

Ruby: ENV["HOME"]
来源：http://dali.zycfv.cn/Article/details/gt2mhlxreav.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhixingplan.top/Article/details/gt2yzqwdeql.html

[M03] 执行外部命令
来源：http://dali.zdqjudy.top/Article/details/gt2bypwadmt.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ydzc1.top/Article/details/gt2neydjvmo.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.haohaochexian.top/Article/details/gt2cjpmzyrn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.aibaodan.cn/Article/details/gt2ijqzgbqf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.meibo888.top/Article/details/gt2crckevxd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jqgufenzy.top/Article/details/gt2phzimlyv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kpxizoob.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gzhubu.top/Article/details/gt2fdcxaxys.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yynyyqnh.html

[M04] 获取当前工作目录
来源：http://dali.kuanghao11.cn/Article/details/gt2dgxyojlp.html

Py:   os.getcwd()
来源：http://dali.fengsongda.top/Article/details/gt2uftcahiu.html

PHP:  getcwd();
来源：http://dali.gogol.net.cn/Article/details/gt2cajwyrqu.html

JS:   process.cwd()
来源：http://dali.hfpthk.cn/Article/details/gt2eibzyjjr.html

TS:   process.cwd()
来源：http://dali.dianchejie.cn/Article/details/gt2mppkcfgi.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yuxming.cn/Article/details/gt2pvkrkwro.html

Go:   os.Getwd()
来源：http://dali.aibaodan.cn/Article/details/gt2phkdszuw.html

Ruby: Dir.pwd
来源：http://dali.yueranfly.top/Article/details/gt2shswgwou.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.tanke756.top/Article/details/gt2gztpvplg.html

[M05] 设置退出码
来源：http://dali.zdqjudy.top/Article/details/gt2vryingcj.html

Py:   sys.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gt2idkjzslr.html

PHP:  exit(1);
来源：http://dali.sxryk.cn/Article/details/gt2pyzbppfn.html

JS:   process.exit(1)
来源：http://dali.yonumen.top/Article/details/gt2ezlpwemu.html

TS:   process.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gt2jxrmxxgz.html

Java: System.exit(1)
来源：http://dali.redwolf501.top/Article/details/gt2qeufgccv.html

Go:   os.Exit(1)
来源：http://dali.316326.xyz/Article/details/gt2zyidhszf.html

Ruby: exit 1
来源：http://dali.yj20258888.top/Article/details/gt2kaznwjsj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.feifeiyinyue.top/Article/details/gt2xfpkrjaa.html

[M06] 向标准错误输出
来源：http://dali.ydzc1.top/Article/details/gt2lwpzgjdh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.chenzaomai.com/Article/details/gt2ovsscaky.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gogol.net.cn/Article/details/gt2zbiahtkl.html

JS:   console.error("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bfmmecyv.html

TS:   console.error("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vgnelrtp.html

Java: System.err.println("err")
来源：http://dali.tanke756.top/Article/details/gt2oihfkqeh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.tianlin.xyz/Article/details/gt2vnvzqyxv.html

Ruby: warn "err"
来源：http://dali.zycfv.cn/Article/details/gt2xgqouqsc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfiuvrex.html

[M07] 判断是否为主入口
来源：http://dali.hammf.cn/Article/details/gt2qroxiacu.html

Py:   if __name__ == "__main__":
来源：http://dali.dianchejie.cn/Article/details/gt2axhejplc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.9152youxi.cn/Article/details/gt2hqpaoivt.html

JS:   require.main === module
来源：http://dali.0kj1m.cn/Article/details/gt2lleyswbd.html

TS:   require.main === module
来源：http://dali.xuetiantiany.cn/Article/details/gt2bssvlhuo.html

Java: public static void main(String[] args)
来源：http://dali.jianghu66.top/Article/details/gt2qtghqpru.html

Go:   func main()
来源：http://dali.zhiwuduotai.top/Article/details/gt2nckdfrvl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.fengsongda.top/Article/details/gt2aqftlqbk.html

C#:   static void Main(string[] args)
来源：http://dali.ydzc1.top/Article/details/gt2uabcjbus.html

[M08] 获取系统与运行时信息
来源：http://dali.havefunace.top/Article/details/gt2tvqrrnsm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.chenjidiqi.icu/Article/details/gt2akzcpekx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yuxming.cn/Article/details/gt2xciqdrsz.html

JS:   process.platform;  process.version
来源：http://dali.sysykeji.top/Article/details/gt2hkxgabti.html

TS:   process.platform;  process.version
来源：http://dali.pycfn.com/Article/details/gt2coeycchz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ydzc1.top/Article/details/gt2rnyojjbe.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yonumen.top/Article/details/gt2hvijvrhd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gogol.net.cn/Article/details/gt2jarpxloi.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ydzc1.top/Article/details/gt2grmdfiyw.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wqmlaxyk.html

N. 数据结构与算法
来源：http://dali.yj20258888.top/Article/details/gt2xiwafwwi.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2vvsdguek.html

[N01] 二分查找（有序数组）
来源：http://dali.sxryk.cn/Article/details/gt2enxprnjm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.pycfn.com/Article/details/gt2ywuwsulz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.redwolf501.top/Article/details/gt2susguvzk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zycfv.cn/Article/details/gt2ggierpjy.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yongpay.top/Article/details/gt2xnqhlzwy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yj20258.top/Article/details/gt2vadzobbl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gt2etnbzojc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.chenlongwang.top/Article/details/gt2udimqknd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wcivnfbs.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zycfv.cn/Article/details/gt2ezuqeged.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigfzy.top/Article/details/gt2dyywmgmq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hnqzz.top/Article/details/gt2sxsonmqb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uvhevvfs.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxuanxn.top/Article/details/gt2jfadeotj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yj20258888.top/Article/details/gt2xtnsywwc.html

Go:   slices.Sort(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2znryalgu.html

Ruby: arr.sort
来源：http://dali.jlsjyb.cn/Article/details/gt2xhrkjigq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jqgufenzy.top/Article/details/gt2twubmvoa.html

[N03] 快速排序（分治示例）
来源：http://dali.daxiang520.top/Article/details/gt2rbucxlng.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ehwqpu.com/Article/details/gt2snocspze.html

PHP:  // 递归实现，或用 usort
来源：http://dali.quarkkingdee.top/Article/details/gt2yippamne.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.meibo888.top/Article/details/gt2fmjcuxwt.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxuanxn.top/Article/details/gt2sftvxmww.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.smart0.xyz/Article/details/gt2stblukry.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.havefunace.top/Article/details/gt2ityseoxt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhiwuduotai.top/Article/details/gt2agfedunk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhixingplan.top/Article/details/gt2xfhkgfxh.html

[N04] 斐波那契数列
来源：http://dali.cucudq.cn/Article/details/gt2aiyllmni.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gotoacloud.top/Article/details/gt2tfbcaoxu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gotoacloud.top/Article/details/gt2vdbjwoov.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zycfv.cn/Article/details/gt2gubqvvvg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tidvuvyp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xylfe.cn/Article/details/gt2ldkyomis.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.mhx1999.top/Article/details/gt2swwlpnbr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2spuxrfcc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ubyaljoi.html

[N05] 最大公约数
来源：http://dali.zdqjudy.top/Article/details/gt2hbwfrfxm.html

Py:   math.gcd(a, b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lihuvjgv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shzxlz.cn/Article/details/gt2qjnyrpgz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigfzy.top/Article/details/gt2hmphhxoo.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fzhhl.top/Article/details/gt2fexqyusv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.tanke756.top/Article/details/gt2mofjdyzn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.birdmap.top/Article/details/gt2wpyhsjme.html

Ruby: a.gcd(b)
来源：http://dali.iojbl.cn/Article/details/gt2govuglwf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yueranfly.top/Article/details/gt2gyksjxpf.html

[N06] 判断回文字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2tstucdyj.html

Py:   s == s[::-1]
来源：http://dali.guowangkeji.top/Article/details/gt2qllwlfhy.html

PHP:  $s === strrev($s);
来源：http://dali.yangfankeji.com/Article/details/gt2ipvuccvr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gt2iwpjiaag.html

TS:   s === [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gt2nexixill.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yvedp.cn/Article/details/gt2cuulfpwr.html

Go:   // 双指针从两端比较
来源：http://dali.jianghu66.top/Article/details/gt2apcqztsa.html

Ruby: s == s.reverse
来源：http://dali.jianghu66.top/Article/details/gt2zlclpqfm.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zdqjudy.top/Article/details/gt2vrgmvcgt.html

[N07] 两数之和（返回下标）
来源：http://dali.sysykeji.top/Article/details/gt2zyoumlrm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rvxnhhrq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yongpay.top/Article/details/gt2cohmtwlq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.c1oappe.top/Article/details/gt2xyajelru.html

TS:   // 手写 Map<string, number>
来源：http://dali.guowangkeji.top/Article/details/gt2lzbrmzth.html

Java: // 手写 HashMap
来源：http://dali.dianchejie.cn/Article/details/gt2bevpgrkm.html

Go:   // 手写 map[int]int
来源：http://dali.aizwys.cn/Article/details/gt2vyjuxntp.html

Ruby: // 手写 Hash
来源：http://dali.feifeiyinyue.top/Article/details/gt2swkzznyz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2nzasiafi.html

[N08] 生成全排列
来源：http://dali.birdmap.top/Article/details/gt2ifabuddd.html

Py:   itertools.permutations(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qxfdzaur.html

PHP:  // 手写递归交换
来源：http://dali.sufxvd.cn/Article/details/gt2mlldweib.html

JS:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gt2xaaareyl.html

TS:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gt2ftpvioyb.html

Java: // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gt2xfabrjhw.html

Go:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gt2dlcakrou.html

Ruby: arr.permutation.to_a
来源：http://dali.ydzc1.top/Article/details/gt2cuxqnekc.html

C#:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gt2tvbjcovl.html

[N09] 栈与队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cphrifni.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.havefunace.top/Article/details/gt2sapmnies.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kyvoafzj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.birdmap.top/Article/details/gt2ektdzipt.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shangyingyoupin.top/Article/details/gt2hskfwodi.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xuetiantiany.cn/Article/details/gt2vesdrhdh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.nanxinkj.top/Article/details/gt2tvwbdjla.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.snrcjt.cn/Article/details/gt2scelqxjj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinqigufen.top/Article/details/gt2qflhoppn.html

[N10] 链表节点定义
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qcwsxuyi.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.fengsongda.top/Article/details/gt2wsmhlpfo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.mhx1999.top/Article/details/gt2xjelhtfp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ehwqpu.com/Article/details/gt2zsubbjmy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhoulong.xyz/Article/details/gt2hkbswluh.html

Java: class Node { int v; Node next; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2icuwrnjw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2safzaxvp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.andypj.xyz/Article/details/gt2phlfvljd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.aizwys.cn/Article/details/gt2pgxcvdds.html

[N11] 二叉树中序遍历
来源：http://dali.nanxinkj.top/Article/details/gt2mxrpvakb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.chenjidiqi.icu/Article/details/gt2yxctldoi.html

PHP:  // 手写递归函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2ncyyytln.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ydzc1.top/Article/details/gt2xxtreuoi.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hfpthk.cn/Article/details/gt2reqfyadi.html

Java: // 手写递归
来源：http://dali.zhiwuduotai.top/Article/details/gt2opkyelwp.html

Go:   // 手写递归
来源：http://dali.tianlin.xyz/Article/details/gt2npskksjd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.vqdsnc.cn/Article/details/gt2cotrmabg.html

C#:   // 手写递归
来源：http://dali.nwbrower.top/Article/details/gt2wovweegg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hktphiwp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.aizwys.cn/Article/details/gt2aljgetqb.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hammf.cn/Article/details/gt2fksyiznd.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxinkj.top/Article/details/gt2esbyxnjk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yanxiufei.cn/Article/details/gt2liwaysjz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cqqwz.cn/Article/details/gt2ffiyudnl.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cqqwz.cn/Article/details/gt2ekqlcnrr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.dianchejie.cn/Article/details/gt2oaubzqxh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhengqikj.top/Article/details/gt2iesusyds.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2tgnhpzdu.html

O. 并发与异步
来源：http://dali.ydzc1.top/Article/details/gt2vweamfth.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2hsnlduti.html

[O01] 启动一个线程
来源：http://dali.redwolf501.top/Article/details/gt2skfqknbm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yuanzhike.top/Article/details/gt2xomygvuj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xylfe.cn/Article/details/gt2hhavdlyg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.quarkkingdee.top/Article/details/gt2nkskurot.html

TS:   // 同 JS
来源：http://dali.fzhhl.top/Article/details/gt2uhhtknmp.html

Java: new Thread(() -> f()).start()
来源：http://dali.jianghu66.top/Article/details/gt2seurfljq.html

Go:   go f()
来源：http://dali.gzhubu.top/Article/details/gt2xbvdnhqd.html

Ruby: Thread.new { f }
来源：http://dali.xuetiantiany.cn/Article/details/gt2sksgjrqh.html

C#:   Task.Run(() => F());
来源：http://dali.sysykeji.top/Article/details/gt2elgimflq.html

[O02] 使用线程池
来源：http://dali.redwolf501.top/Article/details/gt2cfqtkpvm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jqgufenzy.top/Article/details/gt2qcdilcqm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ydzc1.top/Article/details/gt2bvvdjufh.html

JS:   // worker_threads 线程池
来源：http://dali.guannengcc.top/Article/details/gt2xuhyzqcx.html

TS:   // worker_threads 线程池
来源：http://dali.zhongyouzk.top/Article/details/gt2qugmpjwp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.kuanghao11.cn/Article/details/gt2cfyvlksm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.chenlongwang.top/Article/details/gt2sgxcrltw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jinqigufen.top/Article/details/gt2tfbbtwmc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bsgxftzb.html

[O03] 加锁保护共享数据
来源：http://dali.feifeiyinyue.top/Article/details/gt2ltebxlsv.html

Py:   with lock: shared += 1
来源：http://dali.hysaishi.cn/Article/details/gt2ozfkqcwl.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yj20258.top/Article/details/gt2ezhypjtq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhoulong.xyz/Article/details/gt2blirmzfs.html

TS:   // 同 JS
来源：http://dali.vqdsnc.cn/Article/details/gt2frgkpfgb.html

Java: synchronized (this) { shared++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dafknvfj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yj20258.top/Article/details/gt2ytrteovv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.daxiang520.top/Article/details/gt2lymrjvnc.html

C#:   lock (gate) { shared++; }
来源：http://dali.xziqi.cn/Article/details/gt2hkwvuzgh.html

[O04] 定义异步函数并等待
来源：http://dali.jiagoushi.top/Article/details/gt2uckddqhn.html

Py:   async def f():⏎    await g()
来源：http://dali.aizwys.cn/Article/details/gt2sdyamtcp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.daxiang520.top/Article/details/gt2mwzupybb.html

JS:   async function f() { await g(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2toxdmyea.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.pycfn.com/Article/details/gt2dsdecmvh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.quarkkingdee.top/Article/details/gt2jampzimp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gotoacloud.top/Article/details/gt2bzptnvvh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ibpzyeyp.html

C#:   async Task F() { await G(); }
来源：http://dali.yuxming.cn/Article/details/gt2iwhrcplc.html

[O05] 并发执行并等待全部完成
来源：http://dali.gzhubu.top/Article/details/gt2raxcpkwz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jyoumei.cn/Article/details/gt2psxkiwqm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yvedp.cn/Article/details/gt2ucphycul.html

JS:   await Promise.all(tasks)
来源：http://dali.sysykeji.top/Article/details/gt2krtojpzn.html

TS:   await Promise.all(tasks)
来源：http://dali.wangdashe.top/Article/details/gt2jfqdpcef.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xuanzx.com/Article/details/gt2qifpqqhn.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.daria6918.cn/Article/details/gt2mgjbcspg.html

Ruby: threads.map(&:join)
来源：http://dali.zhiwuduotai.top/Article/details/gt2pzsbyelk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.fzhhl.top/Article/details/gt2ehwvhgqp.html

[O06] 使用进程池
来源：http://dali.feifeiyinyue.top/Article/details/gt2gcfsgcwt.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jianghu66.top/Article/details/gt2vauyxpjm.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xylfe.cn/Article/details/gt2ufmewccm.html

JS:   // child_process / cluster 模块
来源：http://dali.gotoacloud.top/Article/details/gt2odsdmnlu.html

TS:   // child_process / cluster 模块
来源：http://dali.gzhubu.top/Article/details/gt2vcebpihk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.kuanghao11.cn/Article/details/gt2xnyaiqcc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2utnmszyj.html

Ruby: // fork 块
来源：http://dali.jiagoushi.top/Article/details/gt2lufkhtao.html

C#:   Parallel.For
来源：http://dali.redwolf501.top/Article/details/gt2vbttolai.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2fkdulhcy.html

P. 常用工具函数
来源：http://dali.birdmap.top/Article/details/gt2shmgppib.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2gtjnbypu.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqlpfid.html

Py:   str(uuid.uuid4())
来源：http://dali.zhengqikj.top/Article/details/gt2ytbbanhw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.nanxuanxn.top/Article/details/gt2zuzchmup.html

JS:   crypto.randomUUID()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vbhkpnzr.html

TS:   crypto.randomUUID()
来源：http://dali.hnxiangtu.top/Article/details/gt2tjzfylpa.html

Java: UUID.randomUUID().toString()
来源：http://dali.9152youxi.cn/Article/details/gt2bliywnds.html

Go:   // 用 github.com/google/uuid
来源：http://dali.wangdashe.top/Article/details/gt2mbixpffy.html

Ruby: SecureRandom.uuid
来源：http://dali.gogol.net.cn/Article/details/gt2wbncchzo.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hysaishi.cn/Article/details/gt2idffhion.html

[P02] MD5 / SHA256 摘要
来源：http://dali.dashuyun.cn/Article/details/gt2wianvlcz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hywenlv.cn/Article/details/gt2quefrmfn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gogol.net.cn/Article/details/gt2hvejbczz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qoeryzwa.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.nanxuanxn.top/Article/details/gt2kgejpndc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yvedp.cn/Article/details/gt2ljmuycoo.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yj202588.top/Article/details/gt2srzawibs.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jiagoushi.top/Article/details/gt2pxegtevl.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yueranfly.top/Article/details/gt2mxyspgvn.html

[P03] 生成短随机字符串
来源：http://dali.tanke756.top/Article/details/gt2hirmtbnx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shangyingyoupin.top/Article/details/gt2civtgoxw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.aizwys.cn/Article/details/gt2tngcyxow.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zycfv.cn/Article/details/gt2gwacqgvu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ybcxt.top/Article/details/gt2twmvhbkd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yanxiufei.cn/Article/details/gt2qutfmzoz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fwunjilo.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.dianchejie.cn/Article/details/gt2yzwpraac.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.guowangkeji.top/Article/details/gt2xnvaotgk.html

[P04] 求长度
来源：http://dali.dashuyun.cn/Article/details/gt2fhzpspfj.html


<!-- 参考信息 -->