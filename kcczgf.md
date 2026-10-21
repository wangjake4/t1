代发 wailian999

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xziqi.cn/Article/details/gtmxqedimw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gtrksenbwn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtgddwwzjc.html

[L06] 解析响应为 JSON
来源：http://dali.nanxuanxn.top/Article/details/gtyeuhzjrk.html

Py:   resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsxxrwbap.html

PHP:  json_decode($body, true);
来源：http://dali.tianlin.xyz/Article/details/gtredgsxyh.html

JS:   await resp.json()
来源：http://dali.xziqi.cn/Article/details/gtegzcdejk.html

TS:   await resp.json()
来源：http://dali.cashguo.top/Article/details/gtsmeskjzi.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gaohongyu789.top/Article/details/gtcdbdxqnh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nanxinkj.top/Article/details/gtwnwoqaqs.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gaohongyu789.top/Article/details/gtnmbofthl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.quarkkingdee.top/Article/details/gtbbkucimg.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinqigufen.top/Article/details/gtnznfefsb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.9152youxi.cn/Article/details/gtyiwuyjhh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ppjwa.cn/Article/details/gtotifcszd.html

JS:   resp.ok;  resp.status
来源：http://dali.jiagoushi.top/Article/details/gttxhvspqw.html

TS:   resp.ok;  resp.status
来源：http://dali.haohaochexian.top/Article/details/gthihiggyh.html

Java: resp.statusCode()
来源：http://dali.jinghuilouyu.cn/Article/details/gthfrlybkk.html

Go:   resp.StatusCode
来源：http://dali.andypj.xyz/Article/details/gtyhizgwmf.html

Ruby: resp.code.to_i
来源：http://dali.xuanzx.com/Article/details/gtrlirlkry.html

C#:   (int)resp.StatusCode
来源：http://dali.yuxming.cn/Article/details/gtxvikrtjp.html

[L08] 并发请求多个地址
来源：http://dali.aibaodan.cn/Article/details/gttvhlnfvg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthvmberud.html

PHP:  curl_multi_init() 系列
来源：http://dali.wangshuangyany.cn/Article/details/gtdtxthnmt.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yanxiufei.cn/Article/details/gtljkbspmf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yongpay.top/Article/details/gtryotrfpi.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jiagoushi.top/Article/details/gtqaigkwsa.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinqigfzy.top/Article/details/gtlvuldjgf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.kuanghao11.cn/Article/details/gtwqplgfvu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhoulong.xyz/Article/details/gtqqcmpswk.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtsbstynfe.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenjidiqi.icu/Article/details/gttrulpjdr.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtafzgsdyq.html

[M01] 读取命令行参数
来源：http://dali.cqqwz.cn/Article/details/gtbwsmfjqp.html

Py:   sys.argv[1:]
来源：http://dali.quarkkingdee.top/Article/details/gtkjatmqzo.html

PHP:  $argv;  $argc;
来源：http://dali.tanke756.top/Article/details/gtateqdsis.html

JS:   process.argv.slice(2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiqipdngy.html

TS:   process.argv.slice(2)
来源：http://dali.c1oappe.top/Article/details/gtqkknvexr.html

Java: args 数组（main 方法参数）
来源：http://dali.bjfxy.top/Article/details/gtmktnihvd.html

Go:   os.Args[1:]
来源：http://dali.haohaochexian.top/Article/details/gtwqfeeipx.html

Ruby: ARGV
来源：http://dali.fengsongda.top/Article/details/gthaxgtpae.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cucudq.cn/Article/details/gtzupfqjat.html

[M02] 读取环境变量
来源：http://dali.vqdsnc.cn/Article/details/gtskjklrqr.html

Py:   os.environ.get("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gtxffytlti.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ydzc1.top/Article/details/gtkvmltfon.html

JS:   process.env.HOME
来源：http://dali.zdqjudy.top/Article/details/gtjabheyrs.html

TS:   process.env.HOME
来源：http://dali.fengsongda.top/Article/details/gtbxskntec.html

Java: System.getenv("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxzplhqct.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.svipenyu.cn/Article/details/gtilmnuyaj.html

Ruby: ENV["HOME"]
来源：http://dali.shanyushiyangtech.top/Article/details/gtliuzhflh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gtxpeporwu.html

[M03] 执行外部命令
来源：http://dali.tianlin.xyz/Article/details/gtspbljszm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xuetiantiany.cn/Article/details/gtfnblqjyq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.316326.xyz/Article/details/gtlqxsuxia.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ydzc1.top/Article/details/gtgzivycfl.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuetiantiany.cn/Article/details/gtkksgzdvn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xuetiantiany.cn/Article/details/gtclrehsmk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yuxming.cn/Article/details/gtuwolgchm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ybcxt.top/Article/details/gtnwnxvmry.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhixingplan.top/Article/details/gtfyusojsy.html

[M04] 获取当前工作目录
来源：http://dali.mhx1999.top/Article/details/gtirheczcb.html

Py:   os.getcwd()
来源：http://dali.cashguo.top/Article/details/gtjccbiarb.html

PHP:  getcwd();
来源：http://dali.xylfe.cn/Article/details/gtzpylcgqq.html

JS:   process.cwd()
来源：http://dali.sweek.top/Article/details/gtuxhtnria.html

TS:   process.cwd()
来源：http://dali.jinqigfzy.top/Article/details/gtbcfyvatr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.bjfxy.top/Article/details/gtspsdaazd.html

Go:   os.Getwd()
来源：http://dali.ehwqpu.com/Article/details/gtxnlqtfev.html

Ruby: Dir.pwd
来源：http://dali.hysaishi.cn/Article/details/gtioehrkhz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.svipenyu.cn/Article/details/gtpebtzyfi.html

[M05] 设置退出码
来源：http://dali.aibaodan.cn/Article/details/gtlhfwwslt.html

Py:   sys.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gtuabbcebi.html

PHP:  exit(1);
来源：http://dali.yangfankeji.com/Article/details/gtgjuxkbpl.html

JS:   process.exit(1)
来源：http://dali.yongpay.top/Article/details/gtsmqyosqy.html

TS:   process.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gtumonmqmx.html

Java: System.exit(1)
来源：http://dali.havefunace.top/Article/details/gtjtxmuojl.html

Go:   os.Exit(1)
来源：http://dali.jianghu66.top/Article/details/gtjprhmydj.html

Ruby: exit 1
来源：http://dali.hongshengwenyu.top/Article/details/gtcpxrtnwf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenjidiqi.icu/Article/details/gtkmihsdrf.html

[M06] 向标准错误输出
来源：http://dali.sufxvd.cn/Article/details/gtimlicyrm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.pycfn.com/Article/details/gtgqhhqrwr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zycfv.cn/Article/details/gtbzfhakrl.html

JS:   console.error("err")
来源：http://dali.yuanzhike.top/Article/details/gtmfumwxoi.html

TS:   console.error("err")
来源：http://dali.aibaodan.cn/Article/details/gtsjlbigkk.html

Java: System.err.println("err")
来源：http://dali.shuidangran.top/Article/details/gtoopkfxnh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.dianchejie.cn/Article/details/gtxeldzgfo.html

Ruby: warn "err"
来源：http://dali.hongshengwenyu.top/Article/details/gtnqseyufs.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.aibaodan.cn/Article/details/gtxukvhczk.html

[M07] 判断是否为主入口
来源：http://dali.yangfankeji.com/Article/details/gtdibvcyqa.html

Py:   if __name__ == "__main__":
来源：http://dali.zhengqikj.top/Article/details/gteoiwbbcq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gogol.net.cn/Article/details/gtoqukjsbc.html

JS:   require.main === module
来源：http://dali.hammf.cn/Article/details/gtuufbhtbt.html

TS:   require.main === module
来源：http://dali.sxryk.cn/Article/details/gtarihdjgs.html

Java: public static void main(String[] args)
来源：http://dali.ehwqpu.com/Article/details/gtqzjlycri.html

Go:   func main()
来源：http://dali.yj202588.top/Article/details/gtopcefpol.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.snrcjt.cn/Article/details/gtprttctqo.html

C#:   static void Main(string[] args)
来源：http://dali.fengsongda.top/Article/details/gtrjkpdesb.html

[M08] 获取系统与运行时信息
来源：http://dali.xziqi.cn/Article/details/gtiuxsatjf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.aizwys.cn/Article/details/gtdhnbnecd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ydzc1.top/Article/details/gtiwxosgjb.html

JS:   process.platform;  process.version
来源：http://dali.shangyingyoupin.top/Article/details/gthcgeojoa.html

TS:   process.platform;  process.version
来源：http://dali.dianchejie.cn/Article/details/gtkteauwbd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.haohaochexian.top/Article/details/gtokppvvbt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jqgfzy.top/Article/details/gtpnixtqms.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.feifeiyinyue.top/Article/details/gtaptlhkak.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.birdmap.top/Article/details/gtltooqszs.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtcmxgdpxi.html

N. 数据结构与算法
来源：http://dali.birdmap.top/Article/details/gtggoxxruh.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtcfeboeuy.html

[N01] 二分查找（有序数组）
来源：http://dali.dianchejie.cn/Article/details/gtalxxvfyj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtyxiphksv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sysykeji.top/Article/details/gtnjgloekp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtydwtusco.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gzhubu.top/Article/details/gtmhtknbfp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtdbebrgnw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ivvv.top/Article/details/gtxvkicvyn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jqgfzy.top/Article/details/gthjrphgdq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtffucohom.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jlsjyb.cn/Article/details/gtrkczznny.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jyoumei.cn/Article/details/gtfxxzssfo.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.mhx1999.top/Article/details/gtjuyczizv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.bjfxy.top/Article/details/gtficenwfk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guowangkeji.top/Article/details/gtxdbynzlt.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.feifeiyinyue.top/Article/details/gtzjtkxepn.html

Go:   slices.Sort(arr)
来源：http://dali.iojbl.cn/Article/details/gtvhsaijtr.html

Ruby: arr.sort
来源：http://dali.daxiang520.top/Article/details/gtajbycgoi.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.tanke756.top/Article/details/gtwvgxmffu.html

[N03] 快速排序（分治示例）
来源：http://dali.316326.xyz/Article/details/gtachsrduv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhixingplan.top/Article/details/gtsgvqfrdq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.fzhhl.top/Article/details/gtnvzfkpyo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zdqjudy.top/Article/details/gtovqpztww.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guannengcc.top/Article/details/gtgclwbroa.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.tianlin.xyz/Article/details/gtcyothbiy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jqgfzy.top/Article/details/gtqhbxshpq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfuskkrpv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.bjfxy.top/Article/details/gttcdqlbgt.html

[N04] 斐波那契数列
来源：http://dali.birdmap.top/Article/details/gttdqedmqy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zdqjudy.top/Article/details/gtrremzixa.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cashguo.top/Article/details/gtspnvlecg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvwhotbaa.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigufen.top/Article/details/gtaogptxog.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.daxiang520.top/Article/details/gtefnqkllg.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hnqzz.top/Article/details/gtbcunhcfs.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkioogfxp.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sufxvd.cn/Article/details/gtwarzoyjc.html

[N05] 最大公约数
来源：http://dali.hongshengwenyu.top/Article/details/gtpgrkwesn.html

Py:   math.gcd(a, b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwyccaebm.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.fengsongda.top/Article/details/gtzelettek.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cucudq.cn/Article/details/gtnwpqlbln.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.9152youxi.cn/Article/details/gtwziagfjg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.0kj1m.cn/Article/details/gtkspoyjub.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zdqjudy.top/Article/details/gtfmljetnz.html

Ruby: a.gcd(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthsyxaqsw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yj202588.top/Article/details/gtxtjuidjv.html

[N06] 判断回文字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuymqaepy.html

Py:   s == s[::-1]
来源：http://dali.pengpengdd.cyou/Article/details/gtbtxtcevi.html

PHP:  $s === strrev($s);
来源：http://dali.gotoacloud.top/Article/details/gtoawxeacj.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gtaebexcic.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gtztlytedj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.pengpengdd.cyou/Article/details/gtppiaoljo.html

Go:   // 双指针从两端比较
来源：http://dali.chenjidiqi.icu/Article/details/gtjdjntmvu.html

Ruby: s == s.reverse
来源：http://dali.dianchejie.cn/Article/details/gtmuxeclwa.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gtbweuetjk.html

[N07] 两数之和（返回下标）
来源：http://dali.sufxvd.cn/Article/details/gtozjexhtm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cqqwz.cn/Article/details/gtmvkgctvu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yonumen.top/Article/details/gtcpkopjmm.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yanxiufei.cn/Article/details/gtzywitpns.html

TS:   // 手写 Map<string, number>
来源：http://dali.daxiang520.top/Article/details/gtwplvshvz.html

Java: // 手写 HashMap
来源：http://dali.cdnleiting.top/Article/details/gtxhwueiky.html

Go:   // 手写 map[int]int
来源：http://dali.yueranfly.top/Article/details/gtzzlbkwcf.html

Ruby: // 手写 Hash
来源：http://dali.nanxinkj.top/Article/details/gtjyabchyk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ybcxt.top/Article/details/gtewwzehjz.html

[N08] 生成全排列
来源：http://dali.aibaodan.cn/Article/details/gthfqcweof.html

Py:   itertools.permutations(arr)
来源：http://dali.sxryk.cn/Article/details/gtutmkvapx.html

PHP:  // 手写递归交换
来源：http://dali.chenjidiqi.icu/Article/details/gtgcsvhwxy.html

JS:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gtcneikiob.html

TS:   // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gtdlconbgx.html

Java: // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gtykwdrdss.html

Go:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gtcxxbzgwi.html

Ruby: arr.permutation.to_a
来源：http://dali.gotoacloud.top/Article/details/gtookwuueo.html

C#:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtvgmdefkn.html

[N09] 栈与队列
来源：http://dali.0kj1m.cn/Article/details/gttdsgszsr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hnxiangtu.top/Article/details/gtypqjnsue.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.svipenyu.cn/Article/details/gtsehdmimp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cdnleiting.top/Article/details/gtmhccwyxk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ybcxt.top/Article/details/gtraltnler.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ehwqpu.com/Article/details/gtcjlzkprs.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.nanxuanxn.top/Article/details/gtmobowbwv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gtvdhbnjjh.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.0kj1m.cn/Article/details/gtxgooswdt.html

[N10] 链表节点定义
来源：http://dali.yj20258.top/Article/details/gtdlfjwvgb.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gotoacloud.top/Article/details/gtfsusbwhd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.tianlin.xyz/Article/details/gtrxjoycsl.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.guannengcc.top/Article/details/gtchbxbmap.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ydzc1.top/Article/details/gtljfcpbwo.html

Java: class Node { int v; Node next; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtegrbidds.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hnxiangtu.top/Article/details/gtsoxtdhik.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.redwolf501.top/Article/details/gtjyfzyhep.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.chenjidiqi.icu/Article/details/gtabnlndsg.html

[N11] 二叉树中序遍历
来源：http://dali.pycfn.com/Article/details/gtbhlyanus.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ehwqpu.com/Article/details/gtzinmoimm.html

PHP:  // 手写递归函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbxtbafbk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.wangdashe.top/Article/details/gtdqvmypzf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ehwqpu.com/Article/details/gtwtledfjv.html

Java: // 手写递归
来源：http://dali.jinqigufen.top/Article/details/gtvhlhelzg.html

Go:   // 手写递归
来源：http://dali.vqdsnc.cn/Article/details/gtfldurpbv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhongyouzk.top/Article/details/gtdkvoomlj.html

C#:   // 手写递归
来源：http://dali.ydzc1.top/Article/details/gtxahtckaw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.smart0.xyz/Article/details/gtyhgrkafz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinqigfzy.top/Article/details/gtycgvrjir.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hfpthk.cn/Article/details/gtlioctllr.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.svipenyu.cn/Article/details/gthotxymbt.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jyoumei.cn/Article/details/gtkcizhwwk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cdnleiting.top/Article/details/gthwleuims.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hfpthk.cn/Article/details/gtkdzouvzl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhiwuduotai.top/Article/details/gtfakjgvfj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guannengcc.top/Article/details/gtivopqawe.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtncqnxsou.html

O. 并发与异步
来源：http://dali.iojbl.cn/Article/details/gtxshlnjxb.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtkjagnbol.html

[O01] 启动一个线程
来源：http://dali.jinqigfzy.top/Article/details/gthouvmnzd.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.iojbl.cn/Article/details/gtlvjyjjxl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yvedp.cn/Article/details/gtclnscuol.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shanyushiyangtech.top/Article/details/gtpmiaoxww.html

TS:   // 同 JS
来源：http://dali.snrcjt.cn/Article/details/gtkxswaywz.html

Java: new Thread(() -> f()).start()
来源：http://dali.guowangkeji.top/Article/details/gttgokfcnv.html

Go:   go f()
来源：http://dali.wangdashe.top/Article/details/gtlmwmdjgv.html

Ruby: Thread.new { f }
来源：http://dali.hysaishi.cn/Article/details/gtfcoanwot.html

C#:   Task.Run(() => F());
来源：http://dali.andypj.xyz/Article/details/gtzvxsbvyk.html

[O02] 使用线程池
来源：http://dali.hywenlv.cn/Article/details/gtyuofatxn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ybcxt.top/Article/details/gtdgmwhpox.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.dashuyun.cn/Article/details/gthyjvyanr.html

JS:   // worker_threads 线程池
来源：http://dali.jianghu66.top/Article/details/gtmdsjksaw.html

TS:   // worker_threads 线程池
来源：http://dali.yvedp.cn/Article/details/gtfiymqkgm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtampmsjgp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.chenlongwang.top/Article/details/gttolgkaob.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.c1oappe.top/Article/details/gtaqkohdfj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.haohaochexian.top/Article/details/gtgtklqoef.html

[O03] 加锁保护共享数据
来源：http://dali.chenzaomai.com/Article/details/gtpcaqiwij.html

Py:   with lock: shared += 1
来源：http://dali.daria6918.cn/Article/details/gtqdvwsyve.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ywan-chungtsiang.top/Article/details/gthvhchdhy.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.tanke756.top/Article/details/gtrafyfrkj.html

TS:   // 同 JS
来源：http://dali.kuanghao11.cn/Article/details/gtglaumbws.html

Java: synchronized (this) { shared++; }
来源：http://dali.hammf.cn/Article/details/gtxwtwjfmo.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.havefunace.top/Article/details/gtcbliurhu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jyoumei.cn/Article/details/gtkqfxqcqh.html

C#:   lock (gate) { shared++; }
来源：http://dali.fengsongda.top/Article/details/gteukdnqiu.html

[O04] 定义异步函数并等待
来源：http://dali.jlsjyb.cn/Article/details/gtvvbjgwvi.html

Py:   async def f():⏎    await g()
来源：http://dali.zhiwuduotai.top/Article/details/gtxzkdzmjg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.pycfn.com/Article/details/gtgetyycxt.html

JS:   async function f() { await g(); }
来源：http://dali.xuanzx.com/Article/details/gtumbpeasr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yanxiufei.cn/Article/details/gtbtcujgnu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sysykeji.top/Article/details/gtrzjzelmb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ywan-chungtsiang.top/Article/details/gtamrasgdd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.meibo888.top/Article/details/gtqazoupiy.html

C#:   async Task F() { await G(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtiqctvhby.html

[O05] 并发执行并等待全部完成
来源：http://dali.0kj1m.cn/Article/details/gtznphsliw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hywenlv.cn/Article/details/gtpgiqursg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xziqi.cn/Article/details/gthqeyydwm.html

JS:   await Promise.all(tasks)
来源：http://dali.xuanzx.com/Article/details/gtaudzpeyi.html

TS:   await Promise.all(tasks)
来源：http://dali.hammf.cn/Article/details/gtlbvcfxmr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.smart0.xyz/Article/details/gtxrocysdm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhiwuduotai.top/Article/details/gthtzkovqa.html

Ruby: threads.map(&:join)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqfffbknr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.wangshuangyany.cn/Article/details/gtmxxdoxpd.html

[O06] 使用进程池
来源：http://dali.hfpthk.cn/Article/details/gtenopzyjz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.bjfxy.top/Article/details/gtbqdavttb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cashguo.top/Article/details/gtuoiihvse.html

JS:   // child_process / cluster 模块
来源：http://dali.ppjwa.cn/Article/details/gtaqhhoxgc.html

TS:   // child_process / cluster 模块
来源：http://dali.hfpthk.cn/Article/details/gtqqoqfzdd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.chenzaomai.com/Article/details/gtqcdkjyuf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.wangshuangyany.cn/Article/details/gtufrhrhsj.html

Ruby: // fork 块
来源：http://dali.nwbrower.top/Article/details/gtumbjlugo.html

C#:   Parallel.For
来源：http://dali.yvedp.cn/Article/details/gtvpbyrsla.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtylnmnvtt.html

P. 常用工具函数
来源：http://dali.tian-w.cn/Article/details/gtmwnzaxol.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtjsonrcuq.html

[P01] 生成 UUID
来源：http://dali.yanxiufei.cn/Article/details/gtcmgpuiji.html

Py:   str(uuid.uuid4())
来源：http://dali.jinqigfzy.top/Article/details/gtiweiikfu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yj20258.top/Article/details/gtpwjxnrdi.html

JS:   crypto.randomUUID()
来源：http://dali.c1oappe.top/Article/details/gtgcaverzb.html

TS:   crypto.randomUUID()
来源：http://dali.shangyingyoupin.top/Article/details/gtsbcyufvz.html

Java: UUID.randomUUID().toString()
来源：http://dali.316326.xyz/Article/details/gtjxbclocs.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yongpay.top/Article/details/gthguvqbzd.html

Ruby: SecureRandom.uuid
来源：http://dali.tanke756.top/Article/details/gtshlaadrv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.nanxuanxn.top/Article/details/gtkkfjlvwh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhongyouzk.top/Article/details/gtcvzboppb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ybcxt.top/Article/details/gtomzolaow.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yongpay.top/Article/details/gtarxhqwny.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yj202588.top/Article/details/gtsrfbmhwy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.dashuyun.cn/Article/details/gtbrzmakww.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.haohaochexian.top/Article/details/gthwunyqmg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.316326.xyz/Article/details/gttsvbjgsy.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hfpthk.cn/Article/details/gtshduugpy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gotoacloud.top/Article/details/gtgrapxkih.html

[P03] 生成短随机字符串
来源：http://dali.cqqwz.cn/Article/details/gtuqjmqhcw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdbimeblt.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yanxiufei.cn/Article/details/gtgxumbbki.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhengqikj.top/Article/details/gtxvfbcwfp.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258.top/Article/details/gtoosiblje.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jyoumei.cn/Article/details/gtbfsyuoji.html


<!-- 参考信息 -->