代发 wailian999

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.feifeiyinyue.top/Article/details/gteiykzoyn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.meibo888.top/Article/details/gtvpcbjawt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtvfkfyqfe.html

[L06] 解析响应为 JSON
来源：http://dali.pengpengdd.cyou/Article/details/gtgikheayl.html

Py:   resp.json()
来源：http://dali.jiagoushi.top/Article/details/gtwbgzyytj.html

PHP:  json_decode($body, true);
来源：http://dali.yangfankeji.com/Article/details/gtaqcnyskc.html

JS:   await resp.json()
来源：http://dali.ydzc1.top/Article/details/gtejzaixcx.html

TS:   await resp.json()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqymzekdz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.aizwys.cn/Article/details/gtvgjojsve.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdqifutrf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj20258888.top/Article/details/gterqbxgvi.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.smart0.xyz/Article/details/gtawclnrrl.html

[L07] 处理 HTTP 状态码
来源：http://dali.sweek.top/Article/details/gtmkprhgiq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.wangdashe.top/Article/details/gttbrkrrjo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jyoumei.cn/Article/details/gtgrnesrfq.html

JS:   resp.ok;  resp.status
来源：http://dali.mhx1999.top/Article/details/gtknkrmjgh.html

TS:   resp.ok;  resp.status
来源：http://dali.yongpay.top/Article/details/gtyqymipxg.html

Java: resp.statusCode()
来源：http://dali.wangshuangyany.cn/Article/details/gtandhkkzs.html

Go:   resp.StatusCode
来源：http://dali.sysykeji.top/Article/details/gtyotysqkp.html

Ruby: resp.code.to_i
来源：http://dali.xuetiantiany.cn/Article/details/gtfkuuevcb.html

C#:   (int)resp.StatusCode
来源：http://dali.hywenlv.cn/Article/details/gtaexttgjk.html

[L08] 并发请求多个地址
来源：http://dali.dashuyun.cn/Article/details/gtqgvsmxff.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnkaqrdjh.html

PHP:  curl_multi_init() 系列
来源：http://dali.fengsongda.top/Article/details/gtsxtbmuwg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tian-w.cn/Article/details/gtmoekjyyx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.svipenyu.cn/Article/details/gtspaxiury.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yonumen.top/Article/details/gtoxdqcwfz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cashguo.top/Article/details/gtkcxsshvb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.nanxuanxn.top/Article/details/gtpuwbybif.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yongpay.top/Article/details/gtwwyfcbvl.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtycqwdsdd.html

M. 命令行 / 进程 / 环境
来源：http://dali.jianghu66.top/Article/details/gtejuknrnm.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtnssomeyd.html

[M01] 读取命令行参数
来源：http://dali.kuanghao11.cn/Article/details/gtaxnainda.html

Py:   sys.argv[1:]
来源：http://dali.quarkkingdee.top/Article/details/gtmaqhcikz.html

PHP:  $argv;  $argc;
来源：http://dali.yuxming.cn/Article/details/gttqvysnlz.html

JS:   process.argv.slice(2)
来源：http://dali.xziqi.cn/Article/details/gtnotljkpm.html

TS:   process.argv.slice(2)
来源：http://dali.nanxuanxn.top/Article/details/gtwdejsteg.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gtwpssfmbp.html

Go:   os.Args[1:]
来源：http://dali.zhoulong.xyz/Article/details/gtecqkzanh.html

Ruby: ARGV
来源：http://dali.snrcjt.cn/Article/details/gttcklbzty.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shuidangran.top/Article/details/gtegvzwjri.html

[M02] 读取环境变量
来源：http://dali.meibo888.top/Article/details/gtvfcxykik.html

Py:   os.environ.get("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gtbxytieqe.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gotoacloud.top/Article/details/gtwspxkiql.html

JS:   process.env.HOME
来源：http://dali.zhiwuduotai.top/Article/details/gtmqpmdxue.html

TS:   process.env.HOME
来源：http://dali.316326.xyz/Article/details/gtjlhoxfbw.html

Java: System.getenv("HOME")
来源：http://dali.zdqjudy.top/Article/details/gthyineacn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaeploqfq.html

Ruby: ENV["HOME"]
来源：http://dali.yanxiufei.cn/Article/details/gttknbzuss.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.0kj1m.cn/Article/details/gtpnjqfwuu.html

[M03] 执行外部命令
来源：http://dali.sysykeji.top/Article/details/gtvuidhjlt.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.pycfn.com/Article/details/gtepurugbu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tanke756.top/Article/details/gtsqmeosss.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hysaishi.cn/Article/details/gtofvynzlz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ppjwa.cn/Article/details/gtdiswrhhe.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yonumen.top/Article/details/gtbqstwrzx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jqgufenzy.top/Article/details/gtxqcgjcee.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.fengsongda.top/Article/details/gteqbbomnv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.kuanghao11.cn/Article/details/gtjvwbbcgt.html

[M04] 获取当前工作目录
来源：http://dali.smart0.xyz/Article/details/gtcztyewxw.html

Py:   os.getcwd()
来源：http://dali.tanke756.top/Article/details/gtjnjfprjp.html

PHP:  getcwd();
来源：http://dali.sweek.top/Article/details/gtrkpngvlz.html

JS:   process.cwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gtavwgqzwv.html

TS:   process.cwd()
来源：http://dali.wangdashe.top/Article/details/gtqsfbkjux.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cdnleiting.top/Article/details/gtjkuqxvdf.html

Go:   os.Getwd()
来源：http://dali.gzhubu.top/Article/details/gtlicecukj.html

Ruby: Dir.pwd
来源：http://dali.dianchejie.cn/Article/details/gtfwcwouul.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xziqi.cn/Article/details/gtwuwrtscl.html

[M05] 设置退出码
来源：http://dali.feifeiyinyue.top/Article/details/gthaejymvv.html

Py:   sys.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtcwnlpuea.html

PHP:  exit(1);
来源：http://dali.bjfxy.top/Article/details/gtqolttsqv.html

JS:   process.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmitbyuba.html

TS:   process.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gtsjokegxm.html

Java: System.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtzhspizet.html

Go:   os.Exit(1)
来源：http://dali.shuidangran.top/Article/details/gtapelvebz.html

Ruby: exit 1
来源：http://dali.xziqi.cn/Article/details/gtmrmpdbid.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinghuilouyu.cn/Article/details/gtglfcufud.html

[M06] 向标准错误输出
来源：http://dali.hysaishi.cn/Article/details/gtxeytxbri.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcsvlmpdp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nanxuanxn.top/Article/details/gtifironke.html

JS:   console.error("err")
来源：http://dali.chenjidiqi.icu/Article/details/gtepzyzvkh.html

TS:   console.error("err")
来源：http://dali.nwbrower.top/Article/details/gtmkjsejdm.html

Java: System.err.println("err")
来源：http://dali.wangshuangyany.cn/Article/details/gtakwjtuwn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.nwbrower.top/Article/details/gtwrjutahh.html

Ruby: warn "err"
来源：http://dali.kuanghao11.cn/Article/details/gtwrmcbvxy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tianlin.xyz/Article/details/gtdtetnlqn.html

[M07] 判断是否为主入口
来源：http://dali.daria6918.cn/Article/details/gtojricyre.html

Py:   if __name__ == "__main__":
来源：http://dali.fengsongda.top/Article/details/gtngmbkrnv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.quarkkingdee.top/Article/details/gtywzczipf.html

JS:   require.main === module
来源：http://dali.jinghuilouyu.cn/Article/details/gteuluamwv.html

TS:   require.main === module
来源：http://dali.nanxuanxn.top/Article/details/gtxidgreuu.html

Java: public static void main(String[] args)
来源：http://dali.hnqzz.top/Article/details/gtwduocilj.html

Go:   func main()
来源：http://dali.redwolf501.top/Article/details/gtybnpcoic.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.dianchejie.cn/Article/details/gtzitruhfx.html

C#:   static void Main(string[] args)
来源：http://dali.nanxuanxn.top/Article/details/gtowcfkwxn.html

[M08] 获取系统与运行时信息
来源：http://dali.nanxinkj.top/Article/details/gttlflzwuj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zycfv.cn/Article/details/gtmozwydjb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ydzc1.top/Article/details/gtqwwjcszs.html

JS:   process.platform;  process.version
来源：http://dali.sweek.top/Article/details/gtecndzcuy.html

TS:   process.platform;  process.version
来源：http://dali.tian-w.cn/Article/details/gtyrazjgrv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jqgufenzy.top/Article/details/gtuhclutkm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xinyue.icu/Article/details/gtonrsvozu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.nanxuanxn.top/Article/details/gtylxkpycj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gaohongyu789.top/Article/details/gtbwidekuf.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtknydglfs.html

N. 数据结构与算法
来源：http://dali.yuxming.cn/Article/details/gtuokckdxo.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtsoxfqbhz.html

[N01] 二分查找（有序数组）
来源：http://dali.guowangkeji.top/Article/details/gtrletvsbk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.fzhhl.top/Article/details/gtjyvahpxp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.daria6918.cn/Article/details/gteoivxmfp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigufen.top/Article/details/gtpwonqvxv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xylfe.cn/Article/details/gtaonqyvah.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtmpzrdoft.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gthyzdlllf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xuetiantiany.cn/Article/details/gtgtasxtog.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwekhlghq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shuidangran.top/Article/details/gtcuqymqui.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xinyue.icu/Article/details/gtajqnyqpg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hammf.cn/Article/details/gtjziuvdgg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhixingplan.top/Article/details/gtwtbpqlhg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zdqjudy.top/Article/details/gtejcebxsk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.c1oappe.top/Article/details/gtutmftdma.html

Go:   slices.Sort(arr)
来源：http://dali.cheryme.top/Article/details/gtoolkjowh.html

Ruby: arr.sort
来源：http://dali.nwbrower.top/Article/details/gtycpbtfqu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gtjboijojt.html

[N03] 快速排序（分治示例）
来源：http://dali.vqdsnc.cn/Article/details/gtadsdrcir.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shangyingyoupin.top/Article/details/gtilkwofgf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yongpay.top/Article/details/gtmgdmoboe.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cqqwz.cn/Article/details/gtntnzkmfn.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.0kj1m.cn/Article/details/gtwgyhijnm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj202588.top/Article/details/gtuqyadwbb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zdqjudy.top/Article/details/gtwutzdhmg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.pengpengdd.cyou/Article/details/gtwdcqzpyz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xinyue.icu/Article/details/gtlkadzyky.html

[N04] 斐波那契数列
来源：http://dali.cheryme.top/Article/details/gtpjhnhwpq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hongshengwenyu.top/Article/details/gttrglggjb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ppjwa.cn/Article/details/gtjpuvixhl.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gtjumlfjaj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuxming.cn/Article/details/gtsudzwljt.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ivvv.top/Article/details/gtclyoxlkl.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yueranfly.top/Article/details/gtdyqddvwv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yonumen.top/Article/details/gtbacxzmie.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.chenzaomai.com/Article/details/gtzzjxojpg.html

[N05] 最大公约数
来源：http://dali.zhiwuduotai.top/Article/details/gtsmkixork.html

Py:   math.gcd(a, b)
来源：http://dali.wangshuangyany.cn/Article/details/gtramxknnu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.chenlongwang.top/Article/details/gtyizmtyig.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ybcxt.top/Article/details/gtvvjexhkg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daxiang520.top/Article/details/gtcnickzav.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhixingplan.top/Article/details/gtkqzhsqhk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yvedp.cn/Article/details/gtkzhbomqp.html

Ruby: a.gcd(b)
来源：http://dali.yuxming.cn/Article/details/gtzwxpvuwz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zdqjudy.top/Article/details/gtxjnxjtza.html

[N06] 判断回文字符串
来源：http://dali.zdqjudy.top/Article/details/gtrryngttj.html

Py:   s == s[::-1]
来源：http://dali.birdmap.top/Article/details/gtlfjxkwga.html

PHP:  $s === strrev($s);
来源：http://dali.sxryk.cn/Article/details/gtxbltakdp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gtsrzyqmpm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gtnhsfcpid.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jlsjyb.cn/Article/details/gtnvlvabxe.html

Go:   // 双指针从两端比较
来源：http://dali.yanxiufei.cn/Article/details/gtrhihnfly.html

Ruby: s == s.reverse
来源：http://dali.zhixingplan.top/Article/details/gtfqovbdbd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.316326.xyz/Article/details/gtqfqbcixt.html

[N07] 两数之和（返回下标）
来源：http://dali.wangshuangyany.cn/Article/details/gtfkiqtdek.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yj20258.top/Article/details/gttvxkoqia.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwqpaxzxq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yj20258.top/Article/details/gtmpnhokcz.html

TS:   // 手写 Map<string, number>
来源：http://dali.dashuyun.cn/Article/details/gtfublhqfx.html

Java: // 手写 HashMap
来源：http://dali.sxryk.cn/Article/details/gtdgpibxkn.html

Go:   // 手写 map[int]int
来源：http://dali.iojbl.cn/Article/details/gtmqraqidb.html

Ruby: // 手写 Hash
来源：http://dali.haohaochexian.top/Article/details/gtjmgnloie.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.svipenyu.cn/Article/details/gtkrthagff.html

[N08] 生成全排列
来源：http://dali.jinghuilouyu.cn/Article/details/gtvntdqidx.html

Py:   itertools.permutations(arr)
来源：http://dali.havefunace.top/Article/details/gtfcgfpslo.html

PHP:  // 手写递归交换
来源：http://dali.shanyushiyangtech.top/Article/details/gtjruzvvfn.html

JS:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gtfrxtjxpp.html

TS:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gtotlmekmm.html

Java: // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsgluhplp.html

Go:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtjjkirphv.html

Ruby: arr.permutation.to_a
来源：http://dali.yueranfly.top/Article/details/gtfpoejajh.html

C#:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gtevqobfxr.html

[N09] 栈与队列
来源：http://dali.jqgufenzy.top/Article/details/gtcsxntlpf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhixingplan.top/Article/details/gtivhsicky.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gtlithxlfw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.tanke756.top/Article/details/gtprpjuyvj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xinyue.icu/Article/details/gtiamscqyt.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.iojbl.cn/Article/details/gtosjbfblm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yj202588.top/Article/details/gtmdauiglq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gtlcsrdlzu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhixingplan.top/Article/details/gtbruwpwsy.html

[N10] 链表节点定义
来源：http://dali.9152youxi.cn/Article/details/gtthfodnvo.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.dashuyun.cn/Article/details/gtsnumvgfj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.birdmap.top/Article/details/gtuquzzhal.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.dianchejie.cn/Article/details/gtttntdppa.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jiagoushi.top/Article/details/gtdntfpror.html

Java: class Node { int v; Node next; }
来源：http://dali.jlsjyb.cn/Article/details/gtrtzwzlqt.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteooxbdyj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.chenjidiqi.icu/Article/details/gtppshpnje.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xziqi.cn/Article/details/gtdznsuvoo.html

[N11] 二叉树中序遍历
来源：http://dali.yvedp.cn/Article/details/gtrpvxdrtm.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.redwolf501.top/Article/details/gtgortftcc.html

PHP:  // 手写递归函数
来源：http://dali.zhongyouzk.top/Article/details/gtbroediiz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pycfn.com/Article/details/gtkpxpuirq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtolidcyzb.html

Java: // 手写递归
来源：http://dali.ppjwa.cn/Article/details/gtlwhipbzg.html

Go:   // 手写递归
来源：http://dali.sxryk.cn/Article/details/gtmyhehvib.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.nanxuanxn.top/Article/details/gtpphorrzd.html

C#:   // 手写递归
来源：http://dali.jqgufenzy.top/Article/details/gtuirdfhqe.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xziqi.cn/Article/details/gtiljbxmkk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hnxiangtu.top/Article/details/gteginylvl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.sxryk.cn/Article/details/gtgkfhovts.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xziqi.cn/Article/details/gtevrdxgzk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gzhubu.top/Article/details/gtoclnpqwd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cucudq.cn/Article/details/gtgsftsofz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.guowangkeji.top/Article/details/gtolspxuqz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.vqdsnc.cn/Article/details/gtdktmtwdr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gotoacloud.top/Article/details/gtdfqzrmog.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtouulxysk.html

O. 并发与异步
来源：http://dali.guowangkeji.top/Article/details/gtjliejiir.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtzikauxuz.html

[O01] 启动一个线程
来源：http://dali.tianlin.xyz/Article/details/gttdvxnaut.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.pengpengdd.cyou/Article/details/gtezywmsnn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ydzc1.top/Article/details/gtmmjbkhql.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.snrcjt.cn/Article/details/gtaauwaoae.html

TS:   // 同 JS
来源：http://dali.xinyue.icu/Article/details/gthvwsrfjy.html

Java: new Thread(() -> f()).start()
来源：http://dali.hnqzz.top/Article/details/gtdmabauie.html

Go:   go f()
来源：http://dali.shanyushiyangtech.top/Article/details/gtndzsxuab.html

Ruby: Thread.new { f }
来源：http://dali.hywenlv.cn/Article/details/gtwhkgojdd.html

C#:   Task.Run(() => F());
来源：http://dali.hysaishi.cn/Article/details/gtzlqmhuut.html

[O02] 使用线程池
来源：http://dali.sxryk.cn/Article/details/gtsvxzhkwd.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hfpthk.cn/Article/details/gtkumuxpik.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.meibo888.top/Article/details/gtxrzmurqu.html

JS:   // worker_threads 线程池
来源：http://dali.daria6918.cn/Article/details/gtemwsasoq.html

TS:   // worker_threads 线程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzvhefctk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yj20258888.top/Article/details/gtmlfgprin.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.guowangkeji.top/Article/details/gtiwuuhjlh.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yj20258888.top/Article/details/gtliumnawv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.c1oappe.top/Article/details/gteuqezcvi.html

[O03] 加锁保护共享数据
来源：http://dali.ybcxt.top/Article/details/gtwbbldjsb.html

Py:   with lock: shared += 1
来源：http://dali.quarkkingdee.top/Article/details/gtrlfsadnp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.dashuyun.cn/Article/details/gtthpqpkgc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hongshengwenyu.top/Article/details/gtyzxdmzsa.html

TS:   // 同 JS
来源：http://dali.tanke756.top/Article/details/gtfmtcylhj.html

Java: synchronized (this) { shared++; }
来源：http://dali.zycfv.cn/Article/details/gtpaqchqpu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.iojbl.cn/Article/details/gtdciyjpof.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.c1oappe.top/Article/details/gtdqamgvba.html

C#:   lock (gate) { shared++; }
来源：http://dali.ehwqpu.com/Article/details/gtwebdqrum.html

[O04] 定义异步函数并等待
来源：http://dali.tianlin.xyz/Article/details/gtfvvxazhf.html

Py:   async def f():⏎    await g()
来源：http://dali.nanxuanxn.top/Article/details/gthctunrtt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.tian-w.cn/Article/details/gttlmwqtxp.html

JS:   async function f() { await g(); }
来源：http://dali.nanxinkj.top/Article/details/gtomgvwpvw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtdcwdaagj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhiwuduotai.top/Article/details/gtrtroeqkr.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nwbrower.top/Article/details/gtyqjmuvgw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hammf.cn/Article/details/gtakgyidrt.html

C#:   async Task F() { await G(); }
来源：http://dali.316326.xyz/Article/details/gtkyxswiro.html

[O05] 并发执行并等待全部完成
来源：http://dali.dashuyun.cn/Article/details/gtwekvyzen.html

Py:   asyncio.gather(*tasks)
来源：http://dali.kuanghao11.cn/Article/details/gthvugmkvn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.0kj1m.cn/Article/details/gtanqeywix.html

JS:   await Promise.all(tasks)
来源：http://dali.sysykeji.top/Article/details/gtlujchrac.html

TS:   await Promise.all(tasks)
来源：http://dali.chenjidiqi.icu/Article/details/gtwtchofqf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinghuilouyu.cn/Article/details/gtmvmnwkae.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sysykeji.top/Article/details/gthhapbkme.html

Ruby: threads.map(&:join)
来源：http://dali.guowangkeji.top/Article/details/gtozfllsob.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.aibaodan.cn/Article/details/gtuujajgob.html

[O06] 使用进程池
来源：http://dali.jianghu66.top/Article/details/gtoznzsrvc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jinqigufen.top/Article/details/gtxiiksnvw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cqqwz.cn/Article/details/gtnfrpsqad.html

JS:   // child_process / cluster 模块
来源：http://dali.mhx1999.top/Article/details/gtqkomahkt.html

TS:   // child_process / cluster 模块
来源：http://dali.zdqjudy.top/Article/details/gtoaohmxtj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.birdmap.top/Article/details/gteifyuwjc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tianlin.xyz/Article/details/gtpfglanep.html

Ruby: // fork 块
来源：http://dali.svipenyu.cn/Article/details/gtensnphbp.html

C#:   Parallel.For
来源：http://dali.xuetiantiany.cn/Article/details/gtxyuzuyql.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtlboeeegb.html

P. 常用工具函数
来源：http://dali.cashguo.top/Article/details/gtawcbahaa.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtqpwkcivk.html

[P01] 生成 UUID
来源：http://dali.cqqwz.cn/Article/details/gtnjoodbgr.html

Py:   str(uuid.uuid4())
来源：http://dali.svipenyu.cn/Article/details/gtwjdhbkrj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yuanzhike.top/Article/details/gtpconbwtj.html

JS:   crypto.randomUUID()
来源：http://dali.shangyingyoupin.top/Article/details/gtkmzxgtob.html

TS:   crypto.randomUUID()
来源：http://dali.jyoumei.cn/Article/details/gtkiufnisr.html

Java: UUID.randomUUID().toString()
来源：http://dali.cqqwz.cn/Article/details/gthqtfkbpz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.havefunace.top/Article/details/gtnzcqfgdl.html

Ruby: SecureRandom.uuid
来源：http://dali.0kj1m.cn/Article/details/gtpycidfvr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaxknuqdu.html

[P02] MD5 / SHA256 摘要
来源：http://dali.dianchejie.cn/Article/details/gtpyoaatws.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.dashuyun.cn/Article/details/gtnqlzwtdp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.tian-w.cn/Article/details/gtsfozaiyb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.vqdsnc.cn/Article/details/gtuxrdbpkr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsnwlvlye.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.redwolf501.top/Article/details/gteedentny.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jianghu66.top/Article/details/gtgwoohqni.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hysaishi.cn/Article/details/gtrtqqreml.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yonumen.top/Article/details/gtfshszxhz.html

[P03] 生成短随机字符串
来源：http://dali.daria6918.cn/Article/details/gtqtqbsoah.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.fzhhl.top/Article/details/gtebcvhtaq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yj202588.top/Article/details/gtzhgagoum.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cucudq.cn/Article/details/gtlnjodajf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cqqwz.cn/Article/details/gtrzvcvars.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ydzc1.top/Article/details/gtwiabbqii.html


<!-- 参考信息 -->