代发 wailian999

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.316326.xyz/Article/details/gtptmlfhwa.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gaohongyu789.top/Article/details/gthpteylyj.html

[L05] 上传文件（multipart）
来源：http://dali.hongshengwenyu.top/Article/details/gtykxxtkby.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.svipenyu.cn/Article/details/gtkjuaulns.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.feifeiyinyue.top/Article/details/gtlbbrxjoe.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tanke756.top/Article/details/gteyrkahic.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.aibaodan.cn/Article/details/gtfcwufqvc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinqigfzy.top/Article/details/gtplassekr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zdqjudy.top/Article/details/gtucrfnwsb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.316326.xyz/Article/details/gtpqpvlgrs.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzbgznqxc.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gtnruviwvk.html

Py:   resp.json()
来源：http://dali.vqdsnc.cn/Article/details/gtfdxmgbyk.html

PHP:  json_decode($body, true);
来源：http://dali.ehwqpu.com/Article/details/gtatzdmmek.html

JS:   await resp.json()
来源：http://dali.jqgufenzy.top/Article/details/gtqrkpvker.html

TS:   await resp.json()
来源：http://dali.dashuyun.cn/Article/details/gtzlyuqibc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.svipenyu.cn/Article/details/gtezyhhtqb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinqigfzy.top/Article/details/gtxupoulod.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hywenlv.cn/Article/details/gtlcemkvqr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shangyingyoupin.top/Article/details/gtnafgkjtf.html

[L07] 处理 HTTP 状态码
来源：http://dali.aibaodan.cn/Article/details/gtfbrjxlch.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xylfe.cn/Article/details/gtrcmwurkh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.haohaochexian.top/Article/details/gtvdfzfkps.html

JS:   resp.ok;  resp.status
来源：http://dali.daria6918.cn/Article/details/gtggdxizhh.html

TS:   resp.ok;  resp.status
来源：http://dali.zhiwuduotai.top/Article/details/gtwwnxdvna.html

Java: resp.statusCode()
来源：http://dali.chenjidiqi.icu/Article/details/gtlcgbyosf.html

Go:   resp.StatusCode
来源：http://dali.svipenyu.cn/Article/details/gtyrskhyqv.html

Ruby: resp.code.to_i
来源：http://dali.xinyue.icu/Article/details/gtuuxyiily.html

C#:   (int)resp.StatusCode
来源：http://dali.zhiwuduotai.top/Article/details/gtiklgxisc.html

[L08] 并发请求多个地址
来源：http://dali.ywan-chungtsiang.top/Article/details/gtegizpxgg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.quarkkingdee.top/Article/details/gtlobqqvkb.html

PHP:  curl_multi_init() 系列
来源：http://dali.chenjidiqi.icu/Article/details/gtyoajbjqp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgufenzy.top/Article/details/gtqomvvewn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daxiang520.top/Article/details/gtmusqkknx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jyoumei.cn/Article/details/gtjhluljhg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cdnleiting.top/Article/details/gtbceewsmp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shuidangran.top/Article/details/gtoeelbrst.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.fengsongda.top/Article/details/gtcblfsjyh.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtittktfpi.html

M. 命令行 / 进程 / 环境
来源：http://dali.yuxming.cn/Article/details/gtdfifzumu.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtkfekwmsw.html

[M01] 读取命令行参数
来源：http://dali.shzxlz.cn/Article/details/gtohlsccpb.html

Py:   sys.argv[1:]
来源：http://dali.316326.xyz/Article/details/gtwibphcqp.html

PHP:  $argv;  $argc;
来源：http://dali.wangshuangyany.cn/Article/details/gtsgzremfo.html

JS:   process.argv.slice(2)
来源：http://dali.ppjwa.cn/Article/details/gtnmxrrfvj.html

TS:   process.argv.slice(2)
来源：http://dali.hywenlv.cn/Article/details/gtmyznldvj.html

Java: args 数组（main 方法参数）
来源：http://dali.fengsongda.top/Article/details/gthcvqbzbx.html

Go:   os.Args[1:]
来源：http://dali.yonumen.top/Article/details/gtbbtiuigu.html

Ruby: ARGV
来源：http://dali.ivvv.top/Article/details/gtveubataa.html

C#:   args 数组（Main 方法参数）
来源：http://dali.9152youxi.cn/Article/details/gtuyctkxca.html

[M02] 读取环境变量
来源：http://dali.meibo888.top/Article/details/gtdvmejynj.html

Py:   os.environ.get("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gtuuseotrt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.svipenyu.cn/Article/details/gtrjclvhze.html

JS:   process.env.HOME
来源：http://dali.ivvv.top/Article/details/gtesrnocpg.html

TS:   process.env.HOME
来源：http://dali.xziqi.cn/Article/details/gtnqkjrspq.html

Java: System.getenv("HOME")
来源：http://dali.guannengcc.top/Article/details/gtuaxvnddg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gtupsbhaej.html

Ruby: ENV["HOME"]
来源：http://dali.ehwqpu.com/Article/details/gtpxuobuvt.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cqqwz.cn/Article/details/gtaoiewnbg.html

[M03] 执行外部命令
来源：http://dali.daxiang520.top/Article/details/gtnzlnxvxj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gaohongyu789.top/Article/details/gtnuprmxcq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sweek.top/Article/details/gtbogoudhf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nwbrower.top/Article/details/gtcyumkwkc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yonumen.top/Article/details/gtxnhauzdc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkratcezk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yanxiufei.cn/Article/details/gteqjkidby.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.aizwys.cn/Article/details/gtkauhykbc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.kuanghao11.cn/Article/details/gtuaqndvhd.html

[M04] 获取当前工作目录
来源：http://dali.hfpthk.cn/Article/details/gtkpfjqsbe.html

Py:   os.getcwd()
来源：http://dali.sxryk.cn/Article/details/gtgkvfyfys.html

PHP:  getcwd();
来源：http://dali.sweek.top/Article/details/gtvpuyosad.html

JS:   process.cwd()
来源：http://dali.0kj1m.cn/Article/details/gtdsmgvvve.html

TS:   process.cwd()
来源：http://dali.hfpthk.cn/Article/details/gtfpdfnqry.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yangfankeji.com/Article/details/gtqsjlxoyu.html

Go:   os.Getwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gtcyqnartp.html

Ruby: Dir.pwd
来源：http://dali.yuxming.cn/Article/details/gtxtxbempx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jyoumei.cn/Article/details/gtxnumclhb.html

[M05] 设置退出码
来源：http://dali.0kj1m.cn/Article/details/gtwvapmddg.html

Py:   sys.exit(1)
来源：http://dali.birdmap.top/Article/details/gtmdjyzwoi.html

PHP:  exit(1);
来源：http://dali.cashguo.top/Article/details/gtypvafxur.html

JS:   process.exit(1)
来源：http://dali.sweek.top/Article/details/gtaihelzpv.html

TS:   process.exit(1)
来源：http://dali.sweek.top/Article/details/gtbuwvjgpv.html

Java: System.exit(1)
来源：http://dali.pycfn.com/Article/details/gtghjqrckx.html

Go:   os.Exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtlonhxryn.html

Ruby: exit 1
来源：http://dali.zhongyouzk.top/Article/details/gtkauegmcu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ppjwa.cn/Article/details/gtklyaluyo.html

[M06] 向标准错误输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcypfrnei.html

Py:   print("err", file=sys.stderr)
来源：http://dali.bjfxy.top/Article/details/gttdjqiujx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhengqikj.top/Article/details/gtjgobkvjk.html

JS:   console.error("err")
来源：http://dali.c1oappe.top/Article/details/gtzmgcaive.html

TS:   console.error("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxwvtjhqn.html

Java: System.err.println("err")
来源：http://dali.andypj.xyz/Article/details/gtddhztzzk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zycfv.cn/Article/details/gtjokfivyu.html

Ruby: warn "err"
来源：http://dali.chenzaomai.com/Article/details/gtarzdisvc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jiagoushi.top/Article/details/gtnxkvmnuw.html

[M07] 判断是否为主入口
来源：http://dali.jlsjyb.cn/Article/details/gtyvkooien.html

Py:   if __name__ == "__main__":
来源：http://dali.pengpengdd.cyou/Article/details/gtyijjhkne.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xylfe.cn/Article/details/gtkpksxsqo.html

JS:   require.main === module
来源：http://dali.yuanzhike.top/Article/details/gtohtrxjyn.html

TS:   require.main === module
来源：http://dali.quarkkingdee.top/Article/details/gttsdrjcyp.html

Java: public static void main(String[] args)
来源：http://dali.yj20258888.top/Article/details/gtahqtwmoa.html

Go:   func main()
来源：http://dali.sxryk.cn/Article/details/gtklgzzhvq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenzaomai.com/Article/details/gtbcjglzsr.html

C#:   static void Main(string[] args)
来源：http://dali.ybcxt.top/Article/details/gtaixybvnr.html

[M08] 获取系统与运行时信息
来源：http://dali.wangdashe.top/Article/details/gtluzqrhyo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cucudq.cn/Article/details/gtpknnwyvn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yj20258888.top/Article/details/gtamfsmnis.html

JS:   process.platform;  process.version
来源：http://dali.xinyue.icu/Article/details/gtnzmqbzew.html

TS:   process.platform;  process.version
来源：http://dali.wangdashe.top/Article/details/gtzzrieeqi.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnqzz.top/Article/details/gtzskelket.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hnxiangtu.top/Article/details/gtlgmjsqqn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhiwuduotai.top/Article/details/gtthqtcdge.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.9152youxi.cn/Article/details/gtbeyzkerp.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtuxhwzitf.html

N. 数据结构与算法
来源：http://dali.daxiang520.top/Article/details/gtfxfogowh.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtlxaiqcuy.html

[N01] 二分查找（有序数组）
来源：http://dali.zhoulong.xyz/Article/details/gtpwcrrdys.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtzbjrhikc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.tianlin.xyz/Article/details/gtydngvrqq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenjidiqi.icu/Article/details/gtcldvlhee.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sufxvd.cn/Article/details/gtxvcraseh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtyjlohazj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cashguo.top/Article/details/gtcolxvzth.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsafnhaie.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtxconmfte.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hysaishi.cn/Article/details/gtyxziaoql.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tian-w.cn/Article/details/gtwobtrhuk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zycfv.cn/Article/details/gtltihgsfn.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yangfankeji.com/Article/details/gtqjiitshv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ydzc1.top/Article/details/gtjdvgrdnb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yuanzhike.top/Article/details/gtxaudxesg.html

Go:   slices.Sort(arr)
来源：http://dali.yuxming.cn/Article/details/gtwjtsscjn.html

Ruby: arr.sort
来源：http://dali.hongshengwenyu.top/Article/details/gtywkekwkq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jiagoushi.top/Article/details/gtbiuttpqo.html

[N03] 快速排序（分治示例）
来源：http://dali.guowangkeji.top/Article/details/gtgsscknzr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.c1oappe.top/Article/details/gthnpwoyxp.html

PHP:  // 递归实现，或用 usort
来源：http://dali.snrcjt.cn/Article/details/gtzrlvujag.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aibaodan.cn/Article/details/gtifzwymep.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj202588.top/Article/details/gtywfhmxow.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yongpay.top/Article/details/gtstxndymh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbpbijqdm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tian-w.cn/Article/details/gtiqekszib.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.havefunace.top/Article/details/gtczkatwbc.html

[N04] 斐波那契数列
来源：http://dali.guowangkeji.top/Article/details/gtascwzslt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.smart0.xyz/Article/details/gtcnzuitvo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.guannengcc.top/Article/details/gtqdhstwvq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hywenlv.cn/Article/details/gtquiukepk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtbznqhdpl.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.sweek.top/Article/details/gtwqzvjdpt.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenlongwang.top/Article/details/gtvkdmtkhh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gotoacloud.top/Article/details/gtigbdikcm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cqqwz.cn/Article/details/gtcmzjjdgm.html

[N05] 最大公约数
来源：http://dali.haohaochexian.top/Article/details/gtihnokttg.html

Py:   math.gcd(a, b)
来源：http://dali.dashuyun.cn/Article/details/gtcjvfafld.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gaohongyu789.top/Article/details/gtebpdlbld.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zycfv.cn/Article/details/gtpniyceds.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sweek.top/Article/details/gtlhimnhvx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cheryme.top/Article/details/gtmfxidqag.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xuetiantiany.cn/Article/details/gtspmvvwsz.html

Ruby: a.gcd(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtaeotxjua.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hysaishi.cn/Article/details/gtuumggxhr.html

[N06] 判断回文字符串
来源：http://dali.cucudq.cn/Article/details/gttyrohrxe.html

Py:   s == s[::-1]
来源：http://dali.gotoacloud.top/Article/details/gtyubtjece.html

PHP:  $s === strrev($s);
来源：http://dali.xinyue.icu/Article/details/gtalpdpkps.html

JS:   s === [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gtpverzdbb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gtnwgwgwdd.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yangfankeji.com/Article/details/gtoughaooq.html

Go:   // 双指针从两端比较
来源：http://dali.sweek.top/Article/details/gtoeohdwng.html

Ruby: s == s.reverse
来源：http://dali.gzhubu.top/Article/details/gtmamfdpfb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gotoacloud.top/Article/details/gtbikkoejf.html

[N07] 两数之和（返回下标）
来源：http://dali.dashuyun.cn/Article/details/gtqlubxwfi.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cheryme.top/Article/details/gtpvurybks.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhoulong.xyz/Article/details/gtbbonmiii.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkvjxmgca.html

TS:   // 手写 Map<string, number>
来源：http://dali.tian-w.cn/Article/details/gtbccmowfn.html

Java: // 手写 HashMap
来源：http://dali.iojbl.cn/Article/details/gtzdefwyzv.html

Go:   // 手写 map[int]int
来源：http://dali.shuidangran.top/Article/details/gtgopdjuay.html

Ruby: // 手写 Hash
来源：http://dali.ivvv.top/Article/details/gtmsqysuoy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfanaiwrp.html

[N08] 生成全排列
来源：http://dali.gzhubu.top/Article/details/gtxqtcvupb.html

Py:   itertools.permutations(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gthjoubofj.html

PHP:  // 手写递归交换
来源：http://dali.meibo888.top/Article/details/gtcqmtkqzu.html

JS:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gttstbjqqu.html

TS:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gtushuphbm.html

Java: // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gtlmftkfnf.html

Go:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtmztpxbte.html

Ruby: arr.permutation.to_a
来源：http://dali.nwbrower.top/Article/details/gtmhiqetdl.html

C#:   // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gtrprvxkto.html

[N09] 栈与队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjgzawast.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.fengsongda.top/Article/details/gtuwokjgvt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.vqdsnc.cn/Article/details/gtdlstyfbj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.havefunace.top/Article/details/gtojnvbans.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ppjwa.cn/Article/details/gtopokumjf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cashguo.top/Article/details/gtpuvgeejn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yueranfly.top/Article/details/gtgwmoejqo.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jqgfzy.top/Article/details/gtbdxfjrnm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ehwqpu.com/Article/details/gtvypmdyqw.html

[N10] 链表节点定义
来源：http://dali.zhongyouzk.top/Article/details/gtbwwyiijs.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.aibaodan.cn/Article/details/gthmhgjauw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ehwqpu.com/Article/details/gtokpdlbae.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.havefunace.top/Article/details/gtststnbwh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.c1oappe.top/Article/details/gtuuvohqeq.html

Java: class Node { int v; Node next; }
来源：http://dali.aibaodan.cn/Article/details/gtwprxhmbs.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.bjfxy.top/Article/details/gtfoeopnwp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.guowangkeji.top/Article/details/gtkkolclqg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yj20258888.top/Article/details/gtxxzjmujr.html

[N11] 二叉树中序遍历
来源：http://dali.yvedp.cn/Article/details/gtluujfnoy.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyjaeiasp.html

PHP:  // 手写递归函数
来源：http://dali.cheryme.top/Article/details/gtbaboyynz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.mhx1999.top/Article/details/gtvmlnhbzv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xuanzx.com/Article/details/gttcwdoqqj.html

Java: // 手写递归
来源：http://dali.jinqigfzy.top/Article/details/gtvsuaqfzw.html

Go:   // 手写递归
来源：http://dali.nanxinkj.top/Article/details/gtjeykaeon.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yueranfly.top/Article/details/gtsvcaggty.html

C#:   // 手写递归
来源：http://dali.jinqigfzy.top/Article/details/gtkrpitbfo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhiwuduotai.top/Article/details/gtrpdcecup.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinghuilouyu.cn/Article/details/gthzlgwcga.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.tanke756.top/Article/details/gtmobwjlpv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xziqi.cn/Article/details/gtqilnqgea.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daxiang520.top/Article/details/gtivfvrgfk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ehwqpu.com/Article/details/gtzvccjukh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cashguo.top/Article/details/gtwvuooiyc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sweek.top/Article/details/gtldwjxrol.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hfpthk.cn/Article/details/gtvlycrgwu.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtorgwegyo.html

O. 并发与异步
来源：http://dali.tanke756.top/Article/details/gtigwkprmz.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtephctepx.html

[O01] 启动一个线程
来源：http://dali.shuidangran.top/Article/details/gtpzkxxdxo.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jinghuilouyu.cn/Article/details/gtmmshnhio.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.9152youxi.cn/Article/details/gtmvovbctv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ppjwa.cn/Article/details/gtghtrqxin.html

TS:   // 同 JS
来源：http://dali.havefunace.top/Article/details/gtbylakcme.html

Java: new Thread(() -> f()).start()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmovhddwq.html

Go:   go f()
来源：http://dali.iojbl.cn/Article/details/gtnbjaqsjb.html

Ruby: Thread.new { f }
来源：http://dali.jyoumei.cn/Article/details/gttttygffe.html

C#:   Task.Run(() => F());
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbvrzijhc.html

[O02] 使用线程池
来源：http://dali.zhengqikj.top/Article/details/gtgzccmefm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.iojbl.cn/Article/details/gtktgkquta.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yonumen.top/Article/details/gtuffndvcz.html

JS:   // worker_threads 线程池
来源：http://dali.tianlin.xyz/Article/details/gtwodvcyoz.html

TS:   // worker_threads 线程池
来源：http://dali.smart0.xyz/Article/details/gtalgecdms.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yj20258.top/Article/details/gtgekurkta.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ydzc1.top/Article/details/gtmfjqeisk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.nanxuanxn.top/Article/details/gtshnoxiyv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jqgufenzy.top/Article/details/gtjljbvqev.html

[O03] 加锁保护共享数据
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqtsykahy.html

Py:   with lock: shared += 1
来源：http://dali.ybcxt.top/Article/details/gtalcfzeab.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yvedp.cn/Article/details/gtlmnwnzdw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhengqikj.top/Article/details/gtecxhcvmj.html

TS:   // 同 JS
来源：http://dali.yanxiufei.cn/Article/details/gtroxvdfqa.html

Java: synchronized (this) { shared++; }
来源：http://dali.nanxuanxn.top/Article/details/gtgyhatbtk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yuanzhike.top/Article/details/gtjyypqtcw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gtvjrevnol.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhengqikj.top/Article/details/gtxrrxuemr.html

[O04] 定义异步函数并等待
来源：http://dali.ybcxt.top/Article/details/gtmilkausd.html

Py:   async def f():⏎    await g()
来源：http://dali.gotoacloud.top/Article/details/gtocxupcel.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gtneokzbmw.html

JS:   async function f() { await g(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaneofmvs.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttmrarijl.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.snrcjt.cn/Article/details/gtsyrmemdp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinqigufen.top/Article/details/gtbgebbfjs.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gaohongyu789.top/Article/details/gtojzpqemi.html

C#:   async Task F() { await G(); }
来源：http://dali.xinyue.icu/Article/details/gtkbipeqml.html

[O05] 并发执行并等待全部完成
来源：http://dali.xuanzx.com/Article/details/gtgxygllcl.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhoulong.xyz/Article/details/gtnrimzpbi.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.chenlongwang.top/Article/details/gtgtmkjpzy.html

JS:   await Promise.all(tasks)
来源：http://dali.havefunace.top/Article/details/gtvnxeennn.html

TS:   await Promise.all(tasks)
来源：http://dali.gogol.net.cn/Article/details/gtxsohshwv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.sysykeji.top/Article/details/gtqmkfokxr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hnqzz.top/Article/details/gtissduwmt.html

Ruby: threads.map(&:join)
来源：http://dali.xuanzx.com/Article/details/gtdgkjcidt.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sysykeji.top/Article/details/gtinxfebvx.html

[O06] 使用进程池
来源：http://dali.yonumen.top/Article/details/gtbunnuijo.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.guowangkeji.top/Article/details/gtgptidruk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.iojbl.cn/Article/details/gtkokuywaz.html

JS:   // child_process / cluster 模块
来源：http://dali.mhx1999.top/Article/details/gtisgsdbos.html

TS:   // child_process / cluster 模块
来源：http://dali.yueranfly.top/Article/details/gtkgntfvxf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ehwqpu.com/Article/details/gttzacncdk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhengqikj.top/Article/details/gtmzcleocp.html

Ruby: // fork 块
来源：http://dali.aizwys.cn/Article/details/gtjfqdwjcs.html

C#:   Parallel.For
来源：http://dali.daria6918.cn/Article/details/gtnjlppulg.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtxjodtjqh.html

P. 常用工具函数
来源：http://dali.jlsjyb.cn/Article/details/gtqkjwmmou.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtjccagnew.html

[P01] 生成 UUID
来源：http://dali.wangshuangyany.cn/Article/details/gtranrzbzg.html

Py:   str(uuid.uuid4())
来源：http://dali.mhx1999.top/Article/details/gtbanejzfp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xinyue.icu/Article/details/gtscbhoutf.html

JS:   crypto.randomUUID()
来源：http://dali.andypj.xyz/Article/details/gtxddvecpp.html

TS:   crypto.randomUUID()
来源：http://dali.dashuyun.cn/Article/details/gtreugjlee.html

Java: UUID.randomUUID().toString()
来源：http://dali.hfpthk.cn/Article/details/gtaxdllkph.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hongshengwenyu.top/Article/details/gthvjvzbit.html

Ruby: SecureRandom.uuid
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkvdtfxlu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hysaishi.cn/Article/details/gtmfoxtpft.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shanyushiyangkeji.top/Article/details/gtedzwhstw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yueranfly.top/Article/details/gtvrrropae.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.guowangkeji.top/Article/details/gtqcgyzkvt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gtnisbgbyz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.chenjidiqi.icu/Article/details/gtaobtnsme.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xuetiantiany.cn/Article/details/gtiutjjslq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.tian-w.cn/Article/details/gtjqyruwey.html


<!-- 参考信息 -->