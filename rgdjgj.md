代发 wailian999

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gzhubu.top/Article/details/gtmnmtqiqr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yangfankeji.com/Article/details/gtccrmtuas.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yonumen.top/Article/details/gtezjyuquq.html

[L06] 解析响应为 JSON
来源：http://dali.jiagoushi.top/Article/details/gthbhlmyqc.html

Py:   resp.json()
来源：http://dali.ehwqpu.com/Article/details/gtanyylbph.html

PHP:  json_decode($body, true);
来源：http://dali.jianghu66.top/Article/details/gtlcgamnau.html

JS:   await resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gtvqtghxvn.html

TS:   await resp.json()
来源：http://dali.hammf.cn/Article/details/gtsuiwfugk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jianghu66.top/Article/details/gtloyypsvd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.havefunace.top/Article/details/gtdaehjdpk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpifnjbpu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.wangshuangyany.cn/Article/details/gtlqhyqvvi.html

[L07] 处理 HTTP 状态码
来源：http://dali.meibo888.top/Article/details/gtlxgczvwy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jyoumei.cn/Article/details/gtrexvsnsu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yvedp.cn/Article/details/gtmxuabwxe.html

JS:   resp.ok;  resp.status
来源：http://dali.ybcxt.top/Article/details/gtcosdiagx.html

TS:   resp.ok;  resp.status
来源：http://dali.hongshengwenyu.top/Article/details/gtssunbyvt.html

Java: resp.statusCode()
来源：http://dali.sysykeji.top/Article/details/gtosvvxahz.html

Go:   resp.StatusCode
来源：http://dali.xuetiantiany.cn/Article/details/gtubjhzvhx.html

Ruby: resp.code.to_i
来源：http://dali.xylfe.cn/Article/details/gtccnnrmgy.html

C#:   (int)resp.StatusCode
来源：http://dali.zhongyouzk.top/Article/details/gtkcfiktcf.html

[L08] 并发请求多个地址
来源：http://dali.jqgufenzy.top/Article/details/gtvbvwmgix.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.daxiang520.top/Article/details/gtzkdbcnys.html

PHP:  curl_multi_init() 系列
来源：http://dali.yangfankeji.com/Article/details/gtdwljtrxh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.smart0.xyz/Article/details/gtftvejiwl.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gtcxsewzfg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.redwolf501.top/Article/details/gtapkdtdzb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.aizwys.cn/Article/details/gtdhdtspgq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gtnoruwoch.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.snrcjt.cn/Article/details/gtdhxcholf.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtmkfcoxoi.html

M. 命令行 / 进程 / 环境
来源：http://dali.guowangkeji.top/Article/details/gtkerkksik.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtrizvqtjp.html

[M01] 读取命令行参数
来源：http://dali.chenlongwang.top/Article/details/gtxqdpbwej.html

Py:   sys.argv[1:]
来源：http://dali.shangyingyoupin.top/Article/details/gttyjhhbzh.html

PHP:  $argv;  $argc;
来源：http://dali.aizwys.cn/Article/details/gtnaqlcztm.html

JS:   process.argv.slice(2)
来源：http://dali.dianchejie.cn/Article/details/gtrrbcagon.html

TS:   process.argv.slice(2)
来源：http://dali.316326.xyz/Article/details/gttoyxjehp.html

Java: args 数组（main 方法参数）
来源：http://dali.quarkkingdee.top/Article/details/gtaicvyele.html

Go:   os.Args[1:]
来源：http://dali.wangdashe.top/Article/details/gtowtasvvx.html

Ruby: ARGV
来源：http://dali.sweek.top/Article/details/gthmulxuao.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zycfv.cn/Article/details/gtlrxfuzbf.html

[M02] 读取环境变量
来源：http://dali.daxiang520.top/Article/details/gthikggaws.html

Py:   os.environ.get("HOME")
来源：http://dali.zhixingplan.top/Article/details/gtkxxmgffr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cucudq.cn/Article/details/gtpjttwfxq.html

JS:   process.env.HOME
来源：http://dali.nwbrower.top/Article/details/gtcdkkhwpz.html

TS:   process.env.HOME
来源：http://dali.jinqigfzy.top/Article/details/gtkpqpzrff.html

Java: System.getenv("HOME")
来源：http://dali.zycfv.cn/Article/details/gtwiehvsmb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gtpuvqgtki.html

Ruby: ENV["HOME"]
来源：http://dali.svipenyu.cn/Article/details/gtgxcffizv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyfoawuts.html

[M03] 执行外部命令
来源：http://dali.yueranfly.top/Article/details/gtqpkavwpo.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hammf.cn/Article/details/gtboskvvwz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jianghu66.top/Article/details/gtjmuhoron.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.guowangkeji.top/Article/details/gthlsrngny.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zdqjudy.top/Article/details/gtupbsxdgz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.feifeiyinyue.top/Article/details/gthgsudnsc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xylfe.cn/Article/details/gtvdbgpreg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.pycfn.com/Article/details/gtdwsnuaoz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cucudq.cn/Article/details/gteiqzfpzr.html

[M04] 获取当前工作目录
来源：http://dali.tian-w.cn/Article/details/gtqkeeurqo.html

Py:   os.getcwd()
来源：http://dali.xylfe.cn/Article/details/gtbltxizrq.html

PHP:  getcwd();
来源：http://dali.chenjidiqi.icu/Article/details/gtwoaegeep.html

JS:   process.cwd()
来源：http://dali.guannengcc.top/Article/details/gtdwbruoib.html

TS:   process.cwd()
来源：http://dali.smart0.xyz/Article/details/gttpqycokd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.haohaochexian.top/Article/details/gtwmrolvzz.html

Go:   os.Getwd()
来源：http://dali.xuetiantiany.cn/Article/details/gtdrreddwj.html

Ruby: Dir.pwd
来源：http://dali.birdmap.top/Article/details/gtwlyxceza.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yuanzhike.top/Article/details/gtprkvuiyf.html

[M05] 设置退出码
来源：http://dali.yanxiufei.cn/Article/details/gtafhbmkuc.html

Py:   sys.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnfxitkfz.html

PHP:  exit(1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxrmhdasc.html

JS:   process.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtxnpeypoj.html

TS:   process.exit(1)
来源：http://dali.pycfn.com/Article/details/gtdzetuvji.html

Java: System.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtvbyawuuw.html

Go:   os.Exit(1)
来源：http://dali.sxryk.cn/Article/details/gtlfwkbsui.html

Ruby: exit 1
来源：http://dali.vqdsnc.cn/Article/details/gttubgngpu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinqigufen.top/Article/details/gtyaaajude.html

[M06] 向标准错误输出
来源：http://dali.c1oappe.top/Article/details/gtonmjsiop.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shangyingyoupin.top/Article/details/gtjscpwtck.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinqigufen.top/Article/details/gtqhmstkse.html

JS:   console.error("err")
来源：http://dali.jqgfzy.top/Article/details/gtfsuidyfb.html

TS:   console.error("err")
来源：http://dali.haohaochexian.top/Article/details/gtwqyfrspo.html

Java: System.err.println("err")
来源：http://dali.fzhhl.top/Article/details/gtbpnytnkf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhongyouzk.top/Article/details/gtcsgfxnek.html

Ruby: warn "err"
来源：http://dali.wangdashe.top/Article/details/gtgdbdqtpb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shuidangran.top/Article/details/gtprgtvtku.html

[M07] 判断是否为主入口
来源：http://dali.hnqzz.top/Article/details/gtefzmkpew.html

Py:   if __name__ == "__main__":
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdbeqtaaz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.pengpengdd.cyou/Article/details/gtwsfwkczb.html

JS:   require.main === module
来源：http://dali.chenlongwang.top/Article/details/gtnmbxwntj.html

TS:   require.main === module
来源：http://dali.xylfe.cn/Article/details/gtvswzprlw.html

Java: public static void main(String[] args)
来源：http://dali.pycfn.com/Article/details/gtephyncvu.html

Go:   func main()
来源：http://dali.chenjidiqi.icu/Article/details/gtikcishya.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cqqwz.cn/Article/details/gtsdfwsaqb.html

C#:   static void Main(string[] args)
来源：http://dali.aizwys.cn/Article/details/gtwjvahtjn.html

[M08] 获取系统与运行时信息
来源：http://dali.yj20258.top/Article/details/gtbcmryqra.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ppjwa.cn/Article/details/gtliwtcwhy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.daria6918.cn/Article/details/gtxsujvcfn.html

JS:   process.platform;  process.version
来源：http://dali.yj20258.top/Article/details/gtufmxhlkz.html

TS:   process.platform;  process.version
来源：http://dali.aibaodan.cn/Article/details/gtgzjfxqfy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.chenzaomai.com/Article/details/gtqqfbyokb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinghuilouyu.cn/Article/details/gtbgcwbxmc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jqgfzy.top/Article/details/gtbvgoilgy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yj20258.top/Article/details/gtzwvlheua.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gttrshrkly.html

N. 数据结构与算法
来源：http://dali.chenzaomai.com/Article/details/gtdxcanxxa.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtpwawxeso.html

[N01] 二分查找（有序数组）
来源：http://dali.ybcxt.top/Article/details/gtipxwanqw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtfbivihox.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.wangdashe.top/Article/details/gtxhprpjhg.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gotoacloud.top/Article/details/gtlclcyufj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.meibo888.top/Article/details/gtibuyubzy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.pycfn.com/Article/details/gtwaqbuius.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtvgykfnvl.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zdqjudy.top/Article/details/gtzzgmlfgc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtaeybvdre.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ehwqpu.com/Article/details/gtxxteugxc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.kuanghao11.cn/Article/details/gtlhdujgqo.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xziqi.cn/Article/details/gtbekbgqpg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hammf.cn/Article/details/gttbhcyfqc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yanxiufei.cn/Article/details/gthubghwhp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yvedp.cn/Article/details/gtncppttsz.html

Go:   slices.Sort(arr)
来源：http://dali.tian-w.cn/Article/details/gtowerzwfl.html

Ruby: arr.sort
来源：http://dali.9152youxi.cn/Article/details/gtlgsuaruv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nwbrower.top/Article/details/gtolazorwl.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gtikbhwqvg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hfpthk.cn/Article/details/gtkaibwejv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.dashuyun.cn/Article/details/gtwbzrvuxk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangshuangyany.cn/Article/details/gtotisrsrr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cheryme.top/Article/details/gtjxjonfvp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.aibaodan.cn/Article/details/gtgegsfszz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ydzc1.top/Article/details/gtcgtmzkgy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yangfankeji.com/Article/details/gtynvxldwe.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ehwqpu.com/Article/details/gtctvotnvf.html

[N04] 斐波那契数列
来源：http://dali.quarkkingdee.top/Article/details/gtktbipzls.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.tanke756.top/Article/details/gtttvktlfg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhengqikj.top/Article/details/gtulvteumx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yongpay.top/Article/details/gtmpdkaein.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xziqi.cn/Article/details/gtdglwhiub.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gaohongyu789.top/Article/details/gtlrdebovb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.fzhhl.top/Article/details/gtploabcaj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.iojbl.cn/Article/details/gtlueeylcr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nanxuanxn.top/Article/details/gtfusoywvb.html

[N05] 最大公约数
来源：http://dali.xuanzx.com/Article/details/gtodzvodlz.html

Py:   math.gcd(a, b)
来源：http://dali.birdmap.top/Article/details/gtbbwfsxuk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.pycfn.com/Article/details/gtafogyrug.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gaohongyu789.top/Article/details/gtlujbpzms.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhiwuduotai.top/Article/details/gtfzazgsnw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ehwqpu.com/Article/details/gtauqjyqsl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.9152youxi.cn/Article/details/gtaanazpiy.html

Ruby: a.gcd(b)
来源：http://dali.gzhubu.top/Article/details/gtnhuchbhj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.nanxuanxn.top/Article/details/gtaedmrqbz.html

[N06] 判断回文字符串
来源：http://dali.aizwys.cn/Article/details/gtkgxtlqij.html

Py:   s == s[::-1]
来源：http://dali.cashguo.top/Article/details/gtxgkukhkz.html

PHP:  $s === strrev($s);
来源：http://dali.kuanghao11.cn/Article/details/gtrtujgzwu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gttryfqrou.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gtapabgtqy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jyoumei.cn/Article/details/gtlkdtmohr.html

Go:   // 双指针从两端比较
来源：http://dali.hnqzz.top/Article/details/gtovuackra.html

Ruby: s == s.reverse
来源：http://dali.mhx1999.top/Article/details/gtgievepnb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ppjwa.cn/Article/details/gtqvinlqth.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gtjxghwzul.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hysaishi.cn/Article/details/gtpqzirkdl.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhiwuduotai.top/Article/details/gtukxvsfzn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.dashuyun.cn/Article/details/gteaezurrx.html

TS:   // 手写 Map<string, number>
来源：http://dali.guannengcc.top/Article/details/gtsojuywwf.html

Java: // 手写 HashMap
来源：http://dali.yj20258888.top/Article/details/gtvkwnfirg.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gtfmzqztyv.html

Ruby: // 手写 Hash
来源：http://dali.shangyingyoupin.top/Article/details/gtkfvffopu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.tianlin.xyz/Article/details/gtkkaifkxi.html

[N08] 生成全排列
来源：http://dali.shzxlz.cn/Article/details/gttktljuyk.html

Py:   itertools.permutations(arr)
来源：http://dali.daxiang520.top/Article/details/gtnymnzupn.html

PHP:  // 手写递归交换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgxohetps.html

JS:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gtevckiyft.html

TS:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gtrdgczujs.html

Java: // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gtacrtfuxd.html

Go:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gtuvclhdmj.html

Ruby: arr.permutation.to_a
来源：http://dali.dianchejie.cn/Article/details/gtcbtipjfy.html

C#:   // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gtqkqcwkot.html

[N09] 栈与队列
来源：http://dali.gaohongyu789.top/Article/details/gtyrdgyshm.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shzxlz.cn/Article/details/gtnmaszjyr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jlsjyb.cn/Article/details/gttljaisuu.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.guowangkeji.top/Article/details/gtkuqjcvhy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yj20258888.top/Article/details/gtelxhickr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdjctrirt.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrqmabmee.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.snrcjt.cn/Article/details/gtfypphtph.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.fengsongda.top/Article/details/gtaxrqtsmv.html

[N10] 链表节点定义
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqwgqkmfi.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yj20258888.top/Article/details/gtgewqioyh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jyoumei.cn/Article/details/gtejreumga.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.nwbrower.top/Article/details/gtmnwmzmjb.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.snrcjt.cn/Article/details/gtnpwmlqkk.html

Java: class Node { int v; Node next; }
来源：http://dali.jyoumei.cn/Article/details/gtenjyhmcu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yangfankeji.com/Article/details/gthtmfiqhe.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.bjfxy.top/Article/details/gtjsunowcb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.chenjidiqi.icu/Article/details/gtdvthxmox.html

[N11] 二叉树中序遍历
来源：http://dali.yanxiufei.cn/Article/details/gtsybrtkdf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xuanzx.com/Article/details/gtccfyighc.html

PHP:  // 手写递归函数
来源：http://dali.zhengqikj.top/Article/details/gtvtjtwvve.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigufen.top/Article/details/gtyzukdkcl.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.wangshuangyany.cn/Article/details/gthsapmvnm.html

Java: // 手写递归
来源：http://dali.cdnleiting.top/Article/details/gtoutwiyuc.html

Go:   // 手写递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdszmymbw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfuoencan.html

C#:   // 手写递归
来源：http://dali.cqqwz.cn/Article/details/gtdaxkokxx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.snrcjt.cn/Article/details/gtgvxnwmxi.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.sufxvd.cn/Article/details/gtnohlbviz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.quarkkingdee.top/Article/details/gtyoyjrosb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jiagoushi.top/Article/details/gtvlwcckxc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.birdmap.top/Article/details/gtbziymrch.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.0kj1m.cn/Article/details/gtidsrkamy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.snrcjt.cn/Article/details/gteoctxesr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shanyushiyangtech.top/Article/details/gttbhfiqti.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.9152youxi.cn/Article/details/gtbpdyfzls.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gthuxbupoq.html

O. 并发与异步
来源：http://dali.aibaodan.cn/Article/details/gtalnjirjd.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gteqiprpyt.html

[O01] 启动一个线程
来源：http://dali.birdmap.top/Article/details/gtjalyzfdm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ydzc1.top/Article/details/gtdiozpkvr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.tanke756.top/Article/details/gtfxkabzir.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.sxryk.cn/Article/details/gtmxlfreco.html

TS:   // 同 JS
来源：http://dali.jinqigfzy.top/Article/details/gtzpaizwit.html

Java: new Thread(() -> f()).start()
来源：http://dali.yj20258.top/Article/details/gtpthrphgp.html

Go:   go f()
来源：http://dali.chenlongwang.top/Article/details/gttmlgngma.html

Ruby: Thread.new { f }
来源：http://dali.cqqwz.cn/Article/details/gtfbnyqecf.html

C#:   Task.Run(() => F());
来源：http://dali.ppjwa.cn/Article/details/gtoyefxnrs.html

[O02] 使用线程池
来源：http://dali.yj20258.top/Article/details/gttgotegmx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yj202588.top/Article/details/gthmgegvlx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.redwolf501.top/Article/details/gtamnducbr.html

JS:   // worker_threads 线程池
来源：http://dali.yongpay.top/Article/details/gttaeuyjlj.html

TS:   // worker_threads 线程池
来源：http://dali.xziqi.cn/Article/details/gtxznnlmft.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jlsjyb.cn/Article/details/gtyxggswpf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xinyue.icu/Article/details/gtxewadjdi.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdxxzgpny.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.chenzaomai.com/Article/details/gtujccctrc.html

[O03] 加锁保护共享数据
来源：http://dali.fzhhl.top/Article/details/gtoeauweja.html

Py:   with lock: shared += 1
来源：http://dali.guowangkeji.top/Article/details/gthshglhwc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.feifeiyinyue.top/Article/details/gtmpggcqgy.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.pengpengdd.cyou/Article/details/gttuwhcjdo.html

TS:   // 同 JS
来源：http://dali.sysykeji.top/Article/details/gtynqrtjyl.html

Java: synchronized (this) { shared++; }
来源：http://dali.xuanzx.com/Article/details/gtlnbztjab.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.tian-w.cn/Article/details/gtonwllyyo.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jqgufenzy.top/Article/details/gturetgmka.html

C#:   lock (gate) { shared++; }
来源：http://dali.andypj.xyz/Article/details/gtubevqiul.html

[O04] 定义异步函数并等待
来源：http://dali.havefunace.top/Article/details/gtlfnzrtmj.html

Py:   async def f():⏎    await g()
来源：http://dali.chenjidiqi.icu/Article/details/gtwvukaufn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cucudq.cn/Article/details/gtppxumjua.html

JS:   async function f() { await g(); }
来源：http://dali.zdqjudy.top/Article/details/gtfuipouno.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zycfv.cn/Article/details/gtnnnrjigd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.fengsongda.top/Article/details/gtdneevmoh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shzxlz.cn/Article/details/gtfsbjojeh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.guowangkeji.top/Article/details/gtalzultfc.html

C#:   async Task F() { await G(); }
来源：http://dali.cucudq.cn/Article/details/gtqevloyal.html

[O05] 并发执行并等待全部完成
来源：http://dali.smart0.xyz/Article/details/gtkofeunte.html

Py:   asyncio.gather(*tasks)
来源：http://dali.dashuyun.cn/Article/details/gtpyxtztxs.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.aibaodan.cn/Article/details/gtbnmovwgj.html

JS:   await Promise.all(tasks)
来源：http://dali.jyoumei.cn/Article/details/gtfdxyveoo.html

TS:   await Promise.all(tasks)
来源：http://dali.wangshuangyany.cn/Article/details/gtkyyarood.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpopraawo.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hnxiangtu.top/Article/details/gtmufyschl.html

Ruby: threads.map(&:join)
来源：http://dali.guowangkeji.top/Article/details/gtzuuzqdwl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhongyouzk.top/Article/details/gtqsdfkedn.html

[O06] 使用进程池
来源：http://dali.quarkkingdee.top/Article/details/gtydrdzqad.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.guowangkeji.top/Article/details/gtcykqkpjy.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhongyouzk.top/Article/details/gtlmuzeags.html

JS:   // child_process / cluster 模块
来源：http://dali.jiagoushi.top/Article/details/gtjomxfsgc.html

TS:   // child_process / cluster 模块
来源：http://dali.andypj.xyz/Article/details/gtmeakrgti.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yuxming.cn/Article/details/gtokqjeljf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shuidangran.top/Article/details/gtgycmfimi.html

Ruby: // fork 块
来源：http://dali.nanxuanxn.top/Article/details/gtsrgtpyhz.html

C#:   Parallel.For
来源：http://dali.zhongyouzk.top/Article/details/gtcfrmdhps.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtufcvqvdk.html

P. 常用工具函数
来源：http://dali.zhiwuduotai.top/Article/details/gtkqwqzodp.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtgraomnci.html

[P01] 生成 UUID
来源：http://dali.yangfankeji.com/Article/details/gtnvmgiwio.html

Py:   str(uuid.uuid4())
来源：http://dali.c1oappe.top/Article/details/gtohpeupwv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cqqwz.cn/Article/details/gtezrcchww.html

JS:   crypto.randomUUID()
来源：http://dali.jlsjyb.cn/Article/details/gtaxrvtjrw.html

TS:   crypto.randomUUID()
来源：http://dali.jqgufenzy.top/Article/details/gtvaxbmkdx.html

Java: UUID.randomUUID().toString()
来源：http://dali.ehwqpu.com/Article/details/gtgfntqyqm.html

Go:   // 用 github.com/google/uuid
来源：http://dali.quarkkingdee.top/Article/details/gtjcbjeuta.html

Ruby: SecureRandom.uuid
来源：http://dali.shuidangran.top/Article/details/gtctehlhgf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hongshengwenyu.top/Article/details/gtffyhxnzm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmkqtptoq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.9152youxi.cn/Article/details/gtsgproxfe.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sufxvd.cn/Article/details/gtjpcgtrur.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shanyushiyangtech.top/Article/details/gtjijanjzo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.dashuyun.cn/Article/details/gtoynwaqzx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xinyue.icu/Article/details/gtrmtufzbu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gzhubu.top/Article/details/gtljbqnsrb.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jianghu66.top/Article/details/gtzstmylwc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhixingplan.top/Article/details/gtanjeugbc.html

[P03] 生成短随机字符串
来源：http://dali.snrcjt.cn/Article/details/gtefgxdfnt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.haohaochexian.top/Article/details/gttihvfxnt.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.tianlin.xyz/Article/details/gtojkheesk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cucudq.cn/Article/details/gtqzjrmuig.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.316326.xyz/Article/details/gtivdbtoaz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.quarkkingdee.top/Article/details/gtasvuswsg.html


<!-- 参考信息 -->