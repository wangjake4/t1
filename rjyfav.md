代发 wailian999

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.wangdashe.top/Article/details/gtlgtredht.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhongyouzk.top/Article/details/gtknzcpzba.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtolxxriuo.html

[L06] 解析响应为 JSON
来源：http://dali.hywenlv.cn/Article/details/gtbegfjczp.html

Py:   resp.json()
来源：http://dali.nwbrower.top/Article/details/gtbjqbsydh.html

PHP:  json_decode($body, true);
来源：http://dali.snrcjt.cn/Article/details/gtsfcyjqxb.html

JS:   await resp.json()
来源：http://dali.iojbl.cn/Article/details/gtwgiftrhe.html

TS:   await resp.json()
来源：http://dali.bjfxy.top/Article/details/gtkmuhijjb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yonumen.top/Article/details/gtiocbkhyt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.snrcjt.cn/Article/details/gtefyisqog.html

Ruby: JSON.parse(resp.body)
来源：http://dali.svipenyu.cn/Article/details/gttqrsnftf.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinqigfzy.top/Article/details/gtwhdfbfnl.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcinpqgyw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xziqi.cn/Article/details/gtgyuefxnc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sufxvd.cn/Article/details/gtsbhumgsg.html

JS:   resp.ok;  resp.status
来源：http://dali.c1oappe.top/Article/details/gtbedvidvl.html

TS:   resp.ok;  resp.status
来源：http://dali.fengsongda.top/Article/details/gteywgnefb.html

Java: resp.statusCode()
来源：http://dali.jqgufenzy.top/Article/details/gtrsqwuhez.html

Go:   resp.StatusCode
来源：http://dali.yueranfly.top/Article/details/gtfwgmmjiw.html

Ruby: resp.code.to_i
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgrkaepcq.html

C#:   (int)resp.StatusCode
来源：http://dali.wangdashe.top/Article/details/gtmmikphto.html

[L08] 并发请求多个地址
来源：http://dali.zhoulong.xyz/Article/details/gtsnhfrhfw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ybcxt.top/Article/details/gtffndukjo.html

PHP:  curl_multi_init() 系列
来源：http://dali.svipenyu.cn/Article/details/gtxdshtkfa.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xinyue.icu/Article/details/gtcjgoedyh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gtikbcaqsm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ybcxt.top/Article/details/gtesdqhqgt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwfpgklsj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.havefunace.top/Article/details/gtggmckesb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.andypj.xyz/Article/details/gttysirvwr.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtzpbmqwji.html

M. 命令行 / 进程 / 环境
来源：http://dali.smart0.xyz/Article/details/gtszbncyri.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtmswvqfhy.html

[M01] 读取命令行参数
来源：http://dali.zdqjudy.top/Article/details/gtibvecrct.html

Py:   sys.argv[1:]
来源：http://dali.dashuyun.cn/Article/details/gtwadoafmi.html

PHP:  $argv;  $argc;
来源：http://dali.dashuyun.cn/Article/details/gttuuymvav.html

JS:   process.argv.slice(2)
来源：http://dali.yonumen.top/Article/details/gttnzrcnvb.html

TS:   process.argv.slice(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfouivjmb.html

Java: args 数组（main 方法参数）
来源：http://dali.hfpthk.cn/Article/details/gtmwknqkvt.html

Go:   os.Args[1:]
来源：http://dali.sufxvd.cn/Article/details/gtkdchjzgp.html

Ruby: ARGV
来源：http://dali.zhongyouzk.top/Article/details/gtbvjsnbfn.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cucudq.cn/Article/details/gtzseveuey.html

[M02] 读取环境变量
来源：http://dali.yuxming.cn/Article/details/gtiuvkopmq.html

Py:   os.environ.get("HOME")
来源：http://dali.fengsongda.top/Article/details/gtqvdxydlo.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.havefunace.top/Article/details/gtqzojybho.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gtmwznjpbp.html

TS:   process.env.HOME
来源：http://dali.shangyingyoupin.top/Article/details/gtefrunank.html

Java: System.getenv("HOME")
来源：http://dali.yj20258888.top/Article/details/gtaygrsubs.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gtyzfcxzmt.html

Ruby: ENV["HOME"]
来源：http://dali.nanxinkj.top/Article/details/gthrcssqnf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yvedp.cn/Article/details/gtchbjeguy.html

[M03] 执行外部命令
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnaslvxhs.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sufxvd.cn/Article/details/gtltjwtewd.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.316326.xyz/Article/details/gtmjczrpba.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.guowangkeji.top/Article/details/gtfeyubzsc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhongyouzk.top/Article/details/gtpsfcwaij.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.havefunace.top/Article/details/gtljnreurp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.guowangkeji.top/Article/details/gtkpwixidr.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.vqdsnc.cn/Article/details/gtihoajlon.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gotoacloud.top/Article/details/gtcrcitygx.html

[M04] 获取当前工作目录
来源：http://dali.guowangkeji.top/Article/details/gtdjlqgmbo.html

Py:   os.getcwd()
来源：http://dali.nanxinkj.top/Article/details/gtqwwlvgje.html

PHP:  getcwd();
来源：http://dali.hysaishi.cn/Article/details/gtzqelivyj.html

JS:   process.cwd()
来源：http://dali.guannengcc.top/Article/details/gtaocojrno.html

TS:   process.cwd()
来源：http://dali.ehwqpu.com/Article/details/gtlrhksgjs.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hfpthk.cn/Article/details/gthnqwusvu.html

Go:   os.Getwd()
来源：http://dali.ydzc1.top/Article/details/gtdremysid.html

Ruby: Dir.pwd
来源：http://dali.gzhubu.top/Article/details/gttrzljfiu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cheryme.top/Article/details/gthjbqnxrf.html

[M05] 设置退出码
来源：http://dali.shanyushiyangtech.top/Article/details/gtorfgwiyf.html

Py:   sys.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtewmrqfhi.html

PHP:  exit(1);
来源：http://dali.zdqjudy.top/Article/details/gtqznrsbfy.html

JS:   process.exit(1)
来源：http://dali.gzhubu.top/Article/details/gtpzhmjwdh.html

TS:   process.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtlccfvvzl.html

Java: System.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtcxuygbmf.html

Go:   os.Exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtvsbewfnc.html

Ruby: exit 1
来源：http://dali.shangyingyoupin.top/Article/details/gtxzsxodmn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlqdgdblm.html

[M06] 向标准错误输出
来源：http://dali.jiagoushi.top/Article/details/gtnukwnohp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj202588.top/Article/details/gttdxdrveu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yongpay.top/Article/details/gtabvinbtd.html

JS:   console.error("err")
来源：http://dali.daxiang520.top/Article/details/gtamzsenmp.html

TS:   console.error("err")
来源：http://dali.9152youxi.cn/Article/details/gtzjlzmgzp.html

Java: System.err.println("err")
来源：http://dali.mhx1999.top/Article/details/gtjhtkccfc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.fzhhl.top/Article/details/gtzkufhilr.html

Ruby: warn "err"
来源：http://dali.zycfv.cn/Article/details/gtfijljwde.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.bjfxy.top/Article/details/gtkfdibqhh.html

[M07] 判断是否为主入口
来源：http://dali.dashuyun.cn/Article/details/gtujlxffrn.html

Py:   if __name__ == "__main__":
来源：http://dali.quarkkingdee.top/Article/details/gtxwomuaux.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.nanxuanxn.top/Article/details/gtsyfshuwo.html

JS:   require.main === module
来源：http://dali.jinqigfzy.top/Article/details/gtjpplkcds.html

TS:   require.main === module
来源：http://dali.zdqjudy.top/Article/details/gtbehksudj.html

Java: public static void main(String[] args)
来源：http://dali.aizwys.cn/Article/details/gtwunptfpe.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gtpykhlzwd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.havefunace.top/Article/details/gtrpcoydtx.html

C#:   static void Main(string[] args)
来源：http://dali.wangshuangyany.cn/Article/details/gtmqeyygux.html

[M08] 获取系统与运行时信息
来源：http://dali.hywenlv.cn/Article/details/gtgbllifth.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cdnleiting.top/Article/details/gtlglyegem.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhixingplan.top/Article/details/gtdnivllrm.html

JS:   process.platform;  process.version
来源：http://dali.gogol.net.cn/Article/details/gtjeceutcy.html

TS:   process.platform;  process.version
来源：http://dali.shanyushiyangtech.top/Article/details/gtizsstoxm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gtqyibkkkg.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shangyingyoupin.top/Article/details/gtjsayvhsg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.0kj1m.cn/Article/details/gtllwrjkdq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zycfv.cn/Article/details/gtfbvzsymz.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtxcvwnkfl.html

N. 数据结构与算法
来源：http://dali.gaohongyu789.top/Article/details/gtndeawwpa.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtqltfywiz.html

[N01] 二分查找（有序数组）
来源：http://dali.quarkkingdee.top/Article/details/gttsndbvee.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvrdtmaoz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.tanke756.top/Article/details/gthhgjmmhg.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zycfv.cn/Article/details/gtvldeompo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.svipenyu.cn/Article/details/gtkmjkcrvv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gttfexldzy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtpziwltzf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yonumen.top/Article/details/gtdoutepoq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtfgunqyqa.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhoulong.xyz/Article/details/gtasxkhrqr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daxiang520.top/Article/details/gtjnyscryi.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhongyouzk.top/Article/details/gtnajozaio.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yanxiufei.cn/Article/details/gtwnnsrjch.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.c1oappe.top/Article/details/gtgkvrvfak.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.bjfxy.top/Article/details/gtrgtkyjtp.html

Go:   slices.Sort(arr)
来源：http://dali.aibaodan.cn/Article/details/gtmtexmoju.html

Ruby: arr.sort
来源：http://dali.zhiwuduotai.top/Article/details/gtrupjvrbw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yj202588.top/Article/details/gtbpjhpisv.html

[N03] 快速排序（分治示例）
来源：http://dali.ydzc1.top/Article/details/gthxmsdfjy.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yvedp.cn/Article/details/gtngzgauyj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jqgfzy.top/Article/details/gtrbxfnofq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhiwuduotai.top/Article/details/gttqazvdwm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.smart0.xyz/Article/details/gtncpdyqbz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.iojbl.cn/Article/details/gtfrcwtsfb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.c1oappe.top/Article/details/gttkmebxqf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ivvv.top/Article/details/gtajgihtfn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.wangshuangyany.cn/Article/details/gtytjstjxi.html

[N04] 斐波那契数列
来源：http://dali.birdmap.top/Article/details/gtnpgzfbco.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.iojbl.cn/Article/details/gtetqrhrsz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xuetiantiany.cn/Article/details/gtvofvcqgo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gtjqrvmkea.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gtsddhsebk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xinyue.icu/Article/details/gtylwaonrw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.pengpengdd.cyou/Article/details/gtnpymzevq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhoulong.xyz/Article/details/gtatpmdxap.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jqgufenzy.top/Article/details/gtawcybntv.html

[N05] 最大公约数
来源：http://dali.pycfn.com/Article/details/gthbbdrtxc.html

Py:   math.gcd(a, b)
来源：http://dali.hnqzz.top/Article/details/gtxjasqeqh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdfoyjyyw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigfzy.top/Article/details/gtjvylftcb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tianlin.xyz/Article/details/gtnoruzcrq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.aibaodan.cn/Article/details/gtybfbyydq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xziqi.cn/Article/details/gtecoxzslh.html

Ruby: a.gcd(b)
来源：http://dali.fengsongda.top/Article/details/gtzmuhqmyr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hnxiangtu.top/Article/details/gtfaadmvcc.html

[N06] 判断回文字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzoszsqjf.html

Py:   s == s[::-1]
来源：http://dali.tanke756.top/Article/details/gtsvfvjnaq.html

PHP:  $s === strrev($s);
来源：http://dali.redwolf501.top/Article/details/gtcpydcyum.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sweek.top/Article/details/gtabjvhzba.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gtclqfvibt.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.guannengcc.top/Article/details/gtigtjnxnb.html

Go:   // 双指针从两端比较
来源：http://dali.hfpthk.cn/Article/details/gtmuzgsclp.html

Ruby: s == s.reverse
来源：http://dali.daxiang520.top/Article/details/gtaypxisdg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhixingplan.top/Article/details/gtxzlklucu.html

[N07] 两数之和（返回下标）
来源：http://dali.hammf.cn/Article/details/gttrfnkpog.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yongpay.top/Article/details/gttwzycvkd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yvedp.cn/Article/details/gtgxaaftyc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdqjzekwa.html

TS:   // 手写 Map<string, number>
来源：http://dali.haohaochexian.top/Article/details/gtsqylnzks.html

Java: // 手写 HashMap
来源：http://dali.xylfe.cn/Article/details/gtsjrhjpkb.html

Go:   // 手写 map[int]int
来源：http://dali.shanyushiyangtech.top/Article/details/gtdhvnpyhz.html

Ruby: // 手写 Hash
来源：http://dali.cdnleiting.top/Article/details/gttupqjshq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hnqzz.top/Article/details/gtmicriaqp.html

[N08] 生成全排列
来源：http://dali.hnqzz.top/Article/details/gtmpemhxpw.html

Py:   itertools.permutations(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteuwreuks.html

PHP:  // 手写递归交换
来源：http://dali.yanxiufei.cn/Article/details/gtfpzshnag.html

JS:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gtgqhwpxpp.html

TS:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkhpdvwvw.html

Java: // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gthkyvwhjj.html

Go:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gtzeiyubid.html

Ruby: arr.permutation.to_a
来源：http://dali.nanxuanxn.top/Article/details/gtzeviygeh.html

C#:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gtuhujuhar.html

[N09] 栈与队列
来源：http://dali.yj20258.top/Article/details/gtvppfvecs.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.guowangkeji.top/Article/details/gtiziwgvvs.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gtpurjmaqw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.daria6918.cn/Article/details/gtshfsliwf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhiwuduotai.top/Article/details/gtouaoggpp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiyycdrjz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cheryme.top/Article/details/gtkryvgfat.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhoulong.xyz/Article/details/gtvhudpafa.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqoggujfo.html

[N10] 链表节点定义
来源：http://dali.jinghuilouyu.cn/Article/details/gtgnmxrfik.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmagiqrdu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.svipenyu.cn/Article/details/gttgsxgibl.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.aibaodan.cn/Article/details/gtmerlelxh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.daria6918.cn/Article/details/gtmvyfbeqd.html

Java: class Node { int v; Node next; }
来源：http://dali.dashuyun.cn/Article/details/gtoanmrjsp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.vqdsnc.cn/Article/details/gtyfvzgucb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtynulhbfi.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinqigfzy.top/Article/details/gtokcusotj.html

[N11] 二叉树中序遍历
来源：http://dali.gaohongyu789.top/Article/details/gtugqqfwjw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhixingplan.top/Article/details/gtirepdqoe.html

PHP:  // 手写递归函数
来源：http://dali.haohaochexian.top/Article/details/gtenokvbwb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.316326.xyz/Article/details/gtscgsgpit.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhongyouzk.top/Article/details/gtpthvtzms.html

Java: // 手写递归
来源：http://dali.ppjwa.cn/Article/details/gtinvvqhdq.html

Go:   // 手写递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdwbalmad.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.redwolf501.top/Article/details/gtqpwxdzff.html

C#:   // 手写递归
来源：http://dali.shuidangran.top/Article/details/gtrjirxtqf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhixingplan.top/Article/details/gtnfmldooa.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hammf.cn/Article/details/gtzmgcfvxj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.aibaodan.cn/Article/details/gtbyzlfydv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.birdmap.top/Article/details/gtapouqqby.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.havefunace.top/Article/details/gtbuixjarv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guannengcc.top/Article/details/gtcvnonqlp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ivvv.top/Article/details/gtqnydcsqt.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.chenlongwang.top/Article/details/gtlpsxatpz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shangyingyoupin.top/Article/details/gtdckgivtg.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtglnobddo.html

O. 并发与异步
来源：http://dali.daria6918.cn/Article/details/gtvgusansz.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtyemzhtws.html

[O01] 启动一个线程
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwdxkgnnh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sweek.top/Article/details/gtzualbrew.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hnxiangtu.top/Article/details/gtpiepqqyj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhengqikj.top/Article/details/gttiksohii.html

TS:   // 同 JS
来源：http://dali.yuxming.cn/Article/details/gtxoncwfpc.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinghuilouyu.cn/Article/details/gtzwmhrhzj.html

Go:   go f()
来源：http://dali.andypj.xyz/Article/details/gtirrimqav.html

Ruby: Thread.new { f }
来源：http://dali.yj20258.top/Article/details/gtrseorcsr.html

C#:   Task.Run(() => F());
来源：http://dali.gaohongyu789.top/Article/details/gtdmdbadbd.html

[O02] 使用线程池
来源：http://dali.wangshuangyany.cn/Article/details/gtpmlzhcsu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gaohongyu789.top/Article/details/gtfrqrrspc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ydzc1.top/Article/details/gtwdapbjwx.html

JS:   // worker_threads 线程池
来源：http://dali.aizwys.cn/Article/details/gtdikivjdb.html

TS:   // worker_threads 线程池
来源：http://dali.cheryme.top/Article/details/gtcpfbphto.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.9152youxi.cn/Article/details/gtmupicmcm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyaknapuy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.nwbrower.top/Article/details/gttwmkuhua.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yangfankeji.com/Article/details/gtnixcdkrc.html

[O03] 加锁保护共享数据
来源：http://dali.tanke756.top/Article/details/gtjelurwbm.html

Py:   with lock: shared += 1
来源：http://dali.zhongyouzk.top/Article/details/gtfzhlcrtj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jianghu66.top/Article/details/gtdlzntqtw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.guannengcc.top/Article/details/gtxdhtaxgp.html

TS:   // 同 JS
来源：http://dali.nwbrower.top/Article/details/gtblagpjpp.html

Java: synchronized (this) { shared++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsngenxmv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.pengpengdd.cyou/Article/details/gtceqbxxwl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsheojpha.html

C#:   lock (gate) { shared++; }
来源：http://dali.aibaodan.cn/Article/details/gtfjqobkst.html

[O04] 定义异步函数并等待
来源：http://dali.xuetiantiany.cn/Article/details/gtrzysjgsg.html

Py:   async def f():⏎    await g()
来源：http://dali.pengpengdd.cyou/Article/details/gthnkrjdah.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gotoacloud.top/Article/details/gtzsjdzsdw.html

JS:   async function f() { await g(); }
来源：http://dali.fengsongda.top/Article/details/gtgxmfrjxv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shzxlz.cn/Article/details/gtiwvtdznd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.wangdashe.top/Article/details/gtmbuzpwhw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xuanzx.com/Article/details/gtqvdrexeo.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xziqi.cn/Article/details/gttdcmkvqw.html

C#:   async Task F() { await G(); }
来源：http://dali.tanke756.top/Article/details/gtrxkqghvy.html

[O05] 并发执行并等待全部完成
来源：http://dali.quarkkingdee.top/Article/details/gtmhglzanq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xuanzx.com/Article/details/gtjlgkcpks.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.9152youxi.cn/Article/details/gtimqpbttb.html

JS:   await Promise.all(tasks)
来源：http://dali.hnqzz.top/Article/details/gtzzxziaxx.html

TS:   await Promise.all(tasks)
来源：http://dali.gaohongyu789.top/Article/details/gtnoqjwypj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.sweek.top/Article/details/gtuknydfbd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.daxiang520.top/Article/details/gtckvsswvz.html

Ruby: threads.map(&:join)
来源：http://dali.quarkkingdee.top/Article/details/gtvilwiofp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gaohongyu789.top/Article/details/gtyluyuzee.html

[O06] 使用进程池
来源：http://dali.smart0.xyz/Article/details/gtpjeqxzlo.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.vqdsnc.cn/Article/details/gtnvzneagr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yonumen.top/Article/details/gttskfhmnq.html

JS:   // child_process / cluster 模块
来源：http://dali.quarkkingdee.top/Article/details/gtyspiuhyy.html

TS:   // child_process / cluster 模块
来源：http://dali.jqgufenzy.top/Article/details/gtndjdngud.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.tanke756.top/Article/details/gtmjequhjn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.nanxuanxn.top/Article/details/gtzfedoxgl.html

Ruby: // fork 块
来源：http://dali.shanyushiyangtech.top/Article/details/gtugzgbxul.html

C#:   Parallel.For
来源：http://dali.feifeiyinyue.top/Article/details/gthwiniulv.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtvpombwxq.html

P. 常用工具函数
来源：http://dali.wangshuangyany.cn/Article/details/gtdszadtgc.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtvugiwsql.html

[P01] 生成 UUID
来源：http://dali.smart0.xyz/Article/details/gtmjtkggms.html

Py:   str(uuid.uuid4())
来源：http://dali.aibaodan.cn/Article/details/gtmgpywewf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jiagoushi.top/Article/details/gtveqvcikf.html

JS:   crypto.randomUUID()
来源：http://dali.yuanzhike.top/Article/details/gtfswgoqzp.html

TS:   crypto.randomUUID()
来源：http://dali.zhengqikj.top/Article/details/gtxvzdggxp.html

Java: UUID.randomUUID().toString()
来源：http://dali.hnxiangtu.top/Article/details/gtsrkiutdw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yj202588.top/Article/details/gtnaleryir.html

Ruby: SecureRandom.uuid
来源：http://dali.hongshengwenyu.top/Article/details/gtcwbxjosj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.dashuyun.cn/Article/details/gtpvmhkqtv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jqgufenzy.top/Article/details/gtoosddxir.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.iojbl.cn/Article/details/gtxroxtmkb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yj202588.top/Article/details/gtlbowskxy.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.feifeiyinyue.top/Article/details/gtucyonrne.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.wangdashe.top/Article/details/gtdzxswmic.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.guannengcc.top/Article/details/gtgrdariva.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yj20258888.top/Article/details/gtvnavvdrw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hfpthk.cn/Article/details/gttgxpnksy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gaohongyu789.top/Article/details/gtmnhlxehc.html

[P03] 生成短随机字符串
来源：http://dali.zhongyouzk.top/Article/details/gtxxfppkit.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.pycfn.com/Article/details/gtawvgxjya.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwwpdrpfg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuanzx.com/Article/details/gtvumymvjq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nwbrower.top/Article/details/gtajdhvyar.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jiagoushi.top/Article/details/gtsxzimgmn.html


<!-- 参考信息 -->