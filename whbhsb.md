代发 wailian999

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.haohaochexian.top/Article/details/gtqxsqaked.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcubfrkkf.html

[L05] 上传文件（multipart）
来源：http://dali.zhengqikj.top/Article/details/gtyhqzdojv.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.guannengcc.top/Article/details/gtoruzsidt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.redwolf501.top/Article/details/gtftipfbfa.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.svipenyu.cn/Article/details/gteskkwhcl.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sufxvd.cn/Article/details/gtuymcygty.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.havefunace.top/Article/details/gtgcvowdxj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.aizwys.cn/Article/details/gthtwoyjgy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmjqxxjlx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinqigufen.top/Article/details/gttkhfzohj.html

[L06] 解析响应为 JSON
来源：http://dali.cheryme.top/Article/details/gtlkmltbxv.html

Py:   resp.json()
来源：http://dali.hywenlv.cn/Article/details/gtnmkuulpx.html

PHP:  json_decode($body, true);
来源：http://dali.yuxming.cn/Article/details/gtlcvhnkro.html

JS:   await resp.json()
来源：http://dali.hammf.cn/Article/details/gtjtiyeckb.html

TS:   await resp.json()
来源：http://dali.jiagoushi.top/Article/details/gtpeahcrio.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hongshengwenyu.top/Article/details/gteohavwhm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jianghu66.top/Article/details/gtggrtwoes.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yuanzhike.top/Article/details/gtxxvoewyk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nwbrower.top/Article/details/gtmlsqciag.html

[L07] 处理 HTTP 状态码
来源：http://dali.daria6918.cn/Article/details/gtpzmjcsiu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj20258888.top/Article/details/gtswiopthy.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.pengpengdd.cyou/Article/details/gtlsabsbul.html

JS:   resp.ok;  resp.status
来源：http://dali.jyoumei.cn/Article/details/gtpwilhqlb.html

TS:   resp.ok;  resp.status
来源：http://dali.yuxming.cn/Article/details/gtpnrmzixy.html

Java: resp.statusCode()
来源：http://dali.yangfankeji.com/Article/details/gttuedsres.html

Go:   resp.StatusCode
来源：http://dali.yongpay.top/Article/details/gtexotrack.html

Ruby: resp.code.to_i
来源：http://dali.shangyingyoupin.top/Article/details/gtetgebjqr.html

C#:   (int)resp.StatusCode
来源：http://dali.gzhubu.top/Article/details/gtdqqvvtce.html

[L08] 并发请求多个地址
来源：http://dali.zhixingplan.top/Article/details/gtdpszagzw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hfpthk.cn/Article/details/gtopluntil.html

PHP:  curl_multi_init() 系列
来源：http://dali.iojbl.cn/Article/details/gtitqbjedt.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shangyingyoupin.top/Article/details/gtyczotfjk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yangfankeji.com/Article/details/gthklmdivc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhiwuduotai.top/Article/details/gtojudenhe.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.svipenyu.cn/Article/details/gttnqfwepz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.birdmap.top/Article/details/gtbuatenof.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hnxiangtu.top/Article/details/gttyorcuig.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtgptkapjw.html

M. 命令行 / 进程 / 环境
来源：http://dali.nwbrower.top/Article/details/gtimbbgaue.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtdtlfbqis.html

[M01] 读取命令行参数
来源：http://dali.hongshengwenyu.top/Article/details/gtqiepccnt.html

Py:   sys.argv[1:]
来源：http://dali.gzhubu.top/Article/details/gtfwdanhft.html

PHP:  $argv;  $argc;
来源：http://dali.sufxvd.cn/Article/details/gtqihoqpzk.html

JS:   process.argv.slice(2)
来源：http://dali.wangdashe.top/Article/details/gtawxneadi.html

TS:   process.argv.slice(2)
来源：http://dali.jqgufenzy.top/Article/details/gtamcsoxgc.html

Java: args 数组（main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgrnhyuab.html

Go:   os.Args[1:]
来源：http://dali.sysykeji.top/Article/details/gtpmuqzfgx.html

Ruby: ARGV
来源：http://dali.haohaochexian.top/Article/details/gtsublsuss.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yuanzhike.top/Article/details/gttfhxmall.html

[M02] 读取环境变量
来源：http://dali.sxryk.cn/Article/details/gtbbvuuyht.html

Py:   os.environ.get("HOME")
来源：http://dali.jinqigufen.top/Article/details/gtxyifxsuf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xuetiantiany.cn/Article/details/gtvtgjxebg.html

JS:   process.env.HOME
来源：http://dali.andypj.xyz/Article/details/gtjjwpsugf.html

TS:   process.env.HOME
来源：http://dali.andypj.xyz/Article/details/gteanitrcr.html

Java: System.getenv("HOME")
来源：http://dali.hammf.cn/Article/details/gtoyevzydc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.snrcjt.cn/Article/details/gtfpmvllhi.html

Ruby: ENV["HOME"]
来源：http://dali.haohaochexian.top/Article/details/gtnrtcluea.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gtyoyvqsgp.html

[M03] 执行外部命令
来源：http://dali.aibaodan.cn/Article/details/gtaafkcpvn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cqqwz.cn/Article/details/gtpoqimvwj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhixingplan.top/Article/details/gtsdtftshy.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.birdmap.top/Article/details/gtyouxtdcs.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gzhubu.top/Article/details/gtfwkwwliq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.aizwys.cn/Article/details/gtsavhjkic.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfdobbutz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zycfv.cn/Article/details/gtupfnlivs.html

C#:   Process.Start("ls", "-l");
来源：http://dali.wangdashe.top/Article/details/gtgseuanax.html

[M04] 获取当前工作目录
来源：http://dali.tanke756.top/Article/details/gtfjepahgx.html

Py:   os.getcwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtklcuezbh.html

PHP:  getcwd();
来源：http://dali.daria6918.cn/Article/details/gtmuwgkzyv.html

JS:   process.cwd()
来源：http://dali.xuanzx.com/Article/details/gtdvxrqiey.html

TS:   process.cwd()
来源：http://dali.smart0.xyz/Article/details/gtzuvvmjfl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sxryk.cn/Article/details/gtmoayqsuy.html

Go:   os.Getwd()
来源：http://dali.cheryme.top/Article/details/gtwntrmgxw.html

Ruby: Dir.pwd
来源：http://dali.316326.xyz/Article/details/gtftgmnbwo.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.birdmap.top/Article/details/gthmchotgh.html

[M05] 设置退出码
来源：http://dali.fengsongda.top/Article/details/gtihwqtwbw.html

Py:   sys.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gtwabeexiz.html

PHP:  exit(1);
来源：http://dali.yvedp.cn/Article/details/gthokuqjzo.html

JS:   process.exit(1)
来源：http://dali.sxryk.cn/Article/details/gtwqvncyvx.html

TS:   process.exit(1)
来源：http://dali.xinyue.icu/Article/details/gtvnafjsuf.html

Java: System.exit(1)
来源：http://dali.wangdashe.top/Article/details/gtpqzxosoq.html

Go:   os.Exit(1)
来源：http://dali.dashuyun.cn/Article/details/gtltozlxax.html

Ruby: exit 1
来源：http://dali.smart0.xyz/Article/details/gtfkcliqrp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shangyingyoupin.top/Article/details/gthnwimiui.html

[M06] 向标准错误输出
来源：http://dali.yuxming.cn/Article/details/gtregivnvy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.nanxuanxn.top/Article/details/gtjhbeshxc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbsmlhevu.html

JS:   console.error("err")
来源：http://dali.fengsongda.top/Article/details/gtwfnocfru.html

TS:   console.error("err")
来源：http://dali.jinqigufen.top/Article/details/gtyozqwzuz.html

Java: System.err.println("err")
来源：http://dali.mhx1999.top/Article/details/gttoedoanx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhengqikj.top/Article/details/gtetnwkjix.html

Ruby: warn "err"
来源：http://dali.wangshuangyany.cn/Article/details/gtivpwjgfx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.guannengcc.top/Article/details/gtjgdkcijv.html

[M07] 判断是否为主入口
来源：http://dali.guannengcc.top/Article/details/gtdbpicxmf.html

Py:   if __name__ == "__main__":
来源：http://dali.daria6918.cn/Article/details/gtwdkiosqx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xuanzx.com/Article/details/gttswsajro.html

JS:   require.main === module
来源：http://dali.yj202588.top/Article/details/gtfabvezce.html

TS:   require.main === module
来源：http://dali.ehwqpu.com/Article/details/gtsgsfriur.html

Java: public static void main(String[] args)
来源：http://dali.jyoumei.cn/Article/details/gtsuubqirz.html

Go:   func main()
来源：http://dali.wangshuangyany.cn/Article/details/gtbugqhsms.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.feifeiyinyue.top/Article/details/gtbpngwizk.html

C#:   static void Main(string[] args)
来源：http://dali.zdqjudy.top/Article/details/gtlsslujqm.html

[M08] 获取系统与运行时信息
来源：http://dali.smart0.xyz/Article/details/gtfutszesj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sweek.top/Article/details/gtmdjtvkeu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xylfe.cn/Article/details/gthfsgczjo.html

JS:   process.platform;  process.version
来源：http://dali.svipenyu.cn/Article/details/gtxzpkgyvo.html

TS:   process.platform;  process.version
来源：http://dali.hongshengwenyu.top/Article/details/gtpelxtkhm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ppjwa.cn/Article/details/gtlnsgpfqu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ydzc1.top/Article/details/gtouwjnscg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gtjfuybgyo.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xuanzx.com/Article/details/gtwocgigjz.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtmjawvelk.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gtcrfrusuw.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtzfgzgznw.html

[N01] 二分查找（有序数组）
来源：http://dali.jiagoushi.top/Article/details/gtujkwzlvr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtalxzlhae.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.guowangkeji.top/Article/details/gttpvlkbym.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xinyue.icu/Article/details/gtcsobgqlk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gtozxqbfcm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtqowueufn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtfqbhoawm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.tanke756.top/Article/details/gtcaidpijt.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtcuuonnrd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.quarkkingdee.top/Article/details/gtpjdppvil.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.havefunace.top/Article/details/gtwmfjbxjv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.dashuyun.cn/Article/details/gtzbbasmgl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dashuyun.cn/Article/details/gtesybyiyg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shuidangran.top/Article/details/gtwhyiulkl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hysaishi.cn/Article/details/gtojetnnrc.html

Go:   slices.Sort(arr)
来源：http://dali.cqqwz.cn/Article/details/gtmfmusndo.html

Ruby: arr.sort
来源：http://dali.redwolf501.top/Article/details/gtnifmkeyt.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.daxiang520.top/Article/details/gtbxsanrkr.html

[N03] 快速排序（分治示例）
来源：http://dali.zycfv.cn/Article/details/gtsmdgmwkl.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.guannengcc.top/Article/details/gtaighzdwv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zdqjudy.top/Article/details/gtxhrooskr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuetiantiany.cn/Article/details/gtdzwskilq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlearladm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.smart0.xyz/Article/details/gtkjxjppir.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sufxvd.cn/Article/details/gtluscdsaa.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.haohaochexian.top/Article/details/gtnkshtwgg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cucudq.cn/Article/details/gtmxufxzly.html

[N04] 斐波那契数列
来源：http://dali.yvedp.cn/Article/details/gtnxeirqlu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtkuixyjwq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtueuxzuoy.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yvedp.cn/Article/details/gtqppebusf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.snrcjt.cn/Article/details/gtwhavqatt.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtagghbtwd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhengqikj.top/Article/details/gtvtquwwcv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gogol.net.cn/Article/details/gthxhrewiz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtahqjxjid.html

[N05] 最大公约数
来源：http://dali.haohaochexian.top/Article/details/gtdbfqzzhw.html

Py:   math.gcd(a, b)
来源：http://dali.shangyingyoupin.top/Article/details/gtaiwjgmhv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ppjwa.cn/Article/details/gtnhhqauct.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hammf.cn/Article/details/gtsikyykxt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nwbrower.top/Article/details/gtxclvetjg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxhiebazm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.pycfn.com/Article/details/gtfloaecyi.html

Ruby: a.gcd(b)
来源：http://dali.redwolf501.top/Article/details/gtibqwdpna.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shzxlz.cn/Article/details/gtfzrwemve.html

[N06] 判断回文字符串
来源：http://dali.cdnleiting.top/Article/details/gtulcrrzze.html

Py:   s == s[::-1]
来源：http://dali.zdqjudy.top/Article/details/gticezviie.html

PHP:  $s === strrev($s);
来源：http://dali.nwbrower.top/Article/details/gtpiewjcoj.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ydzc1.top/Article/details/gtnmbuqxii.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gtwmcpaepl.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.0kj1m.cn/Article/details/gtnedzwwyv.html

Go:   // 双指针从两端比较
来源：http://dali.tanke756.top/Article/details/gtqlkzcfbs.html

Ruby: s == s.reverse
来源：http://dali.daria6918.cn/Article/details/gtbypgfxyk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinqigfzy.top/Article/details/gtksoajgpo.html

[N07] 两数之和（返回下标）
来源：http://dali.zhixingplan.top/Article/details/gtvowotklw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jlsjyb.cn/Article/details/gtqcdczcbc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shangyingyoupin.top/Article/details/gtvbnermzc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ppjwa.cn/Article/details/gtymfbmcgj.html

TS:   // 手写 Map<string, number>
来源：http://dali.sufxvd.cn/Article/details/gtbyrlljhf.html

Java: // 手写 HashMap
来源：http://dali.aibaodan.cn/Article/details/gtvpvaxrbz.html

Go:   // 手写 map[int]int
来源：http://dali.smart0.xyz/Article/details/gtesghcnlm.html

Ruby: // 手写 Hash
来源：http://dali.0kj1m.cn/Article/details/gtjotdnjuj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sweek.top/Article/details/gtzpvixbkd.html

[N08] 生成全排列
来源：http://dali.hfpthk.cn/Article/details/gtfdipnvbk.html

Py:   itertools.permutations(arr)
来源：http://dali.bjfxy.top/Article/details/gtyhgfzuxh.html

PHP:  // 手写递归交换
来源：http://dali.kuanghao11.cn/Article/details/gthewzyaql.html

JS:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gtqndfdsas.html

TS:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxzuyrwdi.html

Java: // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gtoqceyofy.html

Go:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gtstkablnc.html

Ruby: arr.permutation.to_a
来源：http://dali.wangdashe.top/Article/details/gtywhsgddq.html

C#:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtwueewsxu.html

[N09] 栈与队列
来源：http://dali.zhengqikj.top/Article/details/gtzmdyuvcc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gogol.net.cn/Article/details/gtqtyjvrwn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yueranfly.top/Article/details/gtcicgeoya.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shuidangran.top/Article/details/gtsfqoxiva.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gotoacloud.top/Article/details/gtzprpwdun.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinqigfzy.top/Article/details/gtboqtqlqw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hfpthk.cn/Article/details/gtpsjbniwq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gtxmabqzri.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yangfankeji.com/Article/details/gthxllgmtu.html

[N10] 链表节点定义
来源：http://dali.xylfe.cn/Article/details/gtiuasagea.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.nwbrower.top/Article/details/gtwbtueund.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnuiosgpn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmecmzklo.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cheryme.top/Article/details/gtatnlnkio.html

Java: class Node { int v; Node next; }
来源：http://dali.0kj1m.cn/Article/details/gthgaxgsfy.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmacnxrd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shuidangran.top/Article/details/gtvjtewhpq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.nanxuanxn.top/Article/details/gtlmjfvpok.html

[N11] 二叉树中序遍历
来源：http://dali.ppjwa.cn/Article/details/gtudxauhhl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.dashuyun.cn/Article/details/gtkcsikldc.html

PHP:  // 手写递归函数
来源：http://dali.yangfankeji.com/Article/details/gtmmmdsmcs.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.fengsongda.top/Article/details/gtlwximdah.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yueranfly.top/Article/details/gtotsneruu.html

Java: // 手写递归
来源：http://dali.bjfxy.top/Article/details/gtrqbuitbn.html

Go:   // 手写递归
来源：http://dali.snrcjt.cn/Article/details/gtwygegzfe.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.smart0.xyz/Article/details/gtjwvplypq.html

C#:   // 手写递归
来源：http://dali.ydzc1.top/Article/details/gtrxikppnc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xziqi.cn/Article/details/gtxnzbqsvo.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.svipenyu.cn/Article/details/gtxlimscqe.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.andypj.xyz/Article/details/gtjqlaqpls.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hnxiangtu.top/Article/details/gtvebmxkzm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cheryme.top/Article/details/gtbdfblgky.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhiwuduotai.top/Article/details/gtjwaegukx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.kuanghao11.cn/Article/details/gtgylsdvev.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.pycfn.com/Article/details/gtwnebepaw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.haohaochexian.top/Article/details/gtocweqpoe.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtcfkjsmpi.html

O. 并发与异步
来源：http://dali.hysaishi.cn/Article/details/gtlzlrwmxz.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtodgrhtau.html

[O01] 启动一个线程
来源：http://dali.jianghu66.top/Article/details/gtpicsjjtk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcaaqoyzt.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtevrjqmgh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.dianchejie.cn/Article/details/gtcptawkvb.html

TS:   // 同 JS
来源：http://dali.yj202588.top/Article/details/gtplioqkzi.html

Java: new Thread(() -> f()).start()
来源：http://dali.jyoumei.cn/Article/details/gtfjvnjmkg.html

Go:   go f()
来源：http://dali.daria6918.cn/Article/details/gtmlxtzrro.html

Ruby: Thread.new { f }
来源：http://dali.hammf.cn/Article/details/gtwljomyyw.html

C#:   Task.Run(() => F());
来源：http://dali.pycfn.com/Article/details/gtuhzuijhb.html

[O02] 使用线程池
来源：http://dali.tanke756.top/Article/details/gttfkrulzf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jiagoushi.top/Article/details/gtuarocrfu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinyuanbaomall.cn/Article/details/gtszoijhtm.html

JS:   // worker_threads 线程池
来源：http://dali.tianlin.xyz/Article/details/gtxqwycrkc.html

TS:   // worker_threads 线程池
来源：http://dali.guowangkeji.top/Article/details/gthtxexwro.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.316326.xyz/Article/details/gtpicmsebn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shzxlz.cn/Article/details/gtzkwyhjyy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ppjwa.cn/Article/details/gtyubhugll.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.sxryk.cn/Article/details/gtjduwvnsd.html

[O03] 加锁保护共享数据
来源：http://dali.yonumen.top/Article/details/gtomswrrqe.html

Py:   with lock: shared += 1
来源：http://dali.xylfe.cn/Article/details/gttazwttxp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.9152youxi.cn/Article/details/gtqpnqqper.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.birdmap.top/Article/details/gtsbvjctqx.html

TS:   // 同 JS
来源：http://dali.zhixingplan.top/Article/details/gtisdelbsi.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhengqikj.top/Article/details/gtynaswexy.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.chenjidiqi.icu/Article/details/gtkdgageio.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhoulong.xyz/Article/details/gtinuvfgvg.html

C#:   lock (gate) { shared++; }
来源：http://dali.c1oappe.top/Article/details/gtjvsljshd.html

[O04] 定义异步函数并等待
来源：http://dali.redwolf501.top/Article/details/gtlqnxilrr.html

Py:   async def f():⏎    await g()
来源：http://dali.hysaishi.cn/Article/details/gtftrbzbhl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhoulong.xyz/Article/details/gtfimirwiy.html

JS:   async function f() { await g(); }
来源：http://dali.dashuyun.cn/Article/details/gtamylazoh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zycfv.cn/Article/details/gtztmnmani.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.smart0.xyz/Article/details/gtbkrxgubh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhixingplan.top/Article/details/gtnwwtjwcw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xinyue.icu/Article/details/gtzstfqjxs.html

C#:   async Task F() { await G(); }
来源：http://dali.9152youxi.cn/Article/details/gtzscfvwnk.html

[O05] 并发执行并等待全部完成
来源：http://dali.xuetiantiany.cn/Article/details/gtfjaalrjp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hnqzz.top/Article/details/gtfdlfrgiq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.chenjidiqi.icu/Article/details/gtepvmkvpc.html

JS:   await Promise.all(tasks)
来源：http://dali.smart0.xyz/Article/details/gtgjdtlwmu.html

TS:   await Promise.all(tasks)
来源：http://dali.ppjwa.cn/Article/details/gtwegzxoio.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shangyingyoupin.top/Article/details/gtduyzsjem.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cqqwz.cn/Article/details/gtzsidajdu.html

Ruby: threads.map(&:join)
来源：http://dali.yangfankeji.com/Article/details/gtsowaqdvy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ehwqpu.com/Article/details/gtoiqslecl.html

[O06] 使用进程池
来源：http://dali.ivvv.top/Article/details/gtdoybwlzh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthygkvtdh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gtztqkleyh.html

JS:   // child_process / cluster 模块
来源：http://dali.meibo888.top/Article/details/gttdgboeae.html

TS:   // child_process / cluster 模块
来源：http://dali.meibo888.top/Article/details/gtnxghqwfr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yonumen.top/Article/details/gtieximieo.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gzhubu.top/Article/details/gtqooxwkwv.html

Ruby: // fork 块
来源：http://dali.hfpthk.cn/Article/details/gtcfvgomxy.html

C#:   Parallel.For
来源：http://dali.zdqjudy.top/Article/details/gteykjpnbw.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtrdpwapjd.html

P. 常用工具函数
来源：http://dali.gogol.net.cn/Article/details/gtawdwudpi.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtgwdqozkw.html

[P01] 生成 UUID
来源：http://dali.chenzaomai.com/Article/details/gtwsgkqvwy.html

Py:   str(uuid.uuid4())
来源：http://dali.snrcjt.cn/Article/details/gtlkraijov.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ppjwa.cn/Article/details/gtafewjigu.html

JS:   crypto.randomUUID()
来源：http://dali.andypj.xyz/Article/details/gtczkdvoqj.html

TS:   crypto.randomUUID()
来源：http://dali.pengpengdd.cyou/Article/details/gtnvudxcvp.html

Java: UUID.randomUUID().toString()
来源：http://dali.gogol.net.cn/Article/details/gthuqetjwf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jiagoushi.top/Article/details/gtxblsxqkv.html

Ruby: SecureRandom.uuid
来源：http://dali.gzhubu.top/Article/details/gtuugiwfvf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.quarkkingdee.top/Article/details/gtvgrnopgm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hongshengwenyu.top/Article/details/gtavdneptf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmlzqmwdb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.chenzaomai.com/Article/details/gtvudhqlsb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.316326.xyz/Article/details/gtxlravkld.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xziqi.cn/Article/details/gtexkyerlh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xuetiantiany.cn/Article/details/gtsvlpldzl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hnqzz.top/Article/details/gtsdzpyedb.html


<!-- 参考信息 -->