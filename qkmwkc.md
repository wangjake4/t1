代发 wailian999

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shangyingyoupin.top/Article/details/gtnfjxtqxx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.nanxinkj.top/Article/details/gtehmarpin.html

[L05] 上传文件（multipart）
来源：http://dali.tianlin.xyz/Article/details/gtrpbtyyct.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenzaomai.com/Article/details/gtmoxuimqu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.fzhhl.top/Article/details/gtxcaixtmv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sxryk.cn/Article/details/gttnyynygw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.tian-w.cn/Article/details/gtnjwhzvhs.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinqigfzy.top/Article/details/gtqqtrtplp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ehwqpu.com/Article/details/gtjgmzqnpy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yvedp.cn/Article/details/gtgizyuknm.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yongpay.top/Article/details/gtjzztumns.html

[L06] 解析响应为 JSON
来源：http://dali.jinyuanbaomall.cn/Article/details/gtssotjwng.html

Py:   resp.json()
来源：http://dali.ppjwa.cn/Article/details/gtilgvxcbo.html

PHP:  json_decode($body, true);
来源：http://dali.nwbrower.top/Article/details/gtspuubqia.html

JS:   await resp.json()
来源：http://dali.chenzaomai.com/Article/details/gtzjjhteiy.html

TS:   await resp.json()
来源：http://dali.hnxiangtu.top/Article/details/gtqtgkumjq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnpkgyvpb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.tian-w.cn/Article/details/gtmhvuqicw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.haohaochexian.top/Article/details/gtxefphtui.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sweek.top/Article/details/gtweaqzlvy.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtanyzdhqp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.svipenyu.cn/Article/details/gtkerryyvh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gzhubu.top/Article/details/gtiavdktcj.html

JS:   resp.ok;  resp.status
来源：http://dali.jqgfzy.top/Article/details/gtbtstumqx.html

TS:   resp.ok;  resp.status
来源：http://dali.zhiwuduotai.top/Article/details/gtdyerjgsc.html

Java: resp.statusCode()
来源：http://dali.bjfxy.top/Article/details/gtkfglsvyb.html

Go:   resp.StatusCode
来源：http://dali.9152youxi.cn/Article/details/gtcfhtkzhp.html

Ruby: resp.code.to_i
来源：http://dali.jinqigfzy.top/Article/details/gtiyjzpvwg.html

C#:   (int)resp.StatusCode
来源：http://dali.gzhubu.top/Article/details/gtrsqevvzn.html

[L08] 并发请求多个地址
来源：http://dali.yangfankeji.com/Article/details/gtkuoejnlz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sxryk.cn/Article/details/gtmuzmoltc.html

PHP:  curl_multi_init() 系列
来源：http://dali.tian-w.cn/Article/details/gtebtsxiub.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gzhubu.top/Article/details/gtcdvxgzhz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhongyouzk.top/Article/details/gtfwaluyus.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.haohaochexian.top/Article/details/gtraqokkpr.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.meibo888.top/Article/details/gtgkzggfzd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.mhx1999.top/Article/details/gtcxpmrrvc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.kuanghao11.cn/Article/details/gtwdjxnkrv.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtdglahxhc.html

M. 命令行 / 进程 / 环境
来源：http://dali.guannengcc.top/Article/details/gtgefhxayh.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtgveatxdc.html

[M01] 读取命令行参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfrezcazn.html

Py:   sys.argv[1:]
来源：http://dali.daxiang520.top/Article/details/gtgocexdoe.html

PHP:  $argv;  $argc;
来源：http://dali.yanxiufei.cn/Article/details/gtspetlcth.html

JS:   process.argv.slice(2)
来源：http://dali.zhengqikj.top/Article/details/gtvyimkkun.html

TS:   process.argv.slice(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gteuatgfcd.html

Java: args 数组（main 方法参数）
来源：http://dali.zhongyouzk.top/Article/details/gtfiozuces.html

Go:   os.Args[1:]
来源：http://dali.gogol.net.cn/Article/details/gtymsxpdsf.html

Ruby: ARGV
来源：http://dali.chenjidiqi.icu/Article/details/gtymbctatz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xuetiantiany.cn/Article/details/gtqzgpasay.html

[M02] 读取环境变量
来源：http://dali.hywenlv.cn/Article/details/gtojnkmhxn.html

Py:   os.environ.get("HOME")
来源：http://dali.redwolf501.top/Article/details/gtvtxtcldl.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.daria6918.cn/Article/details/gtegjbqrjy.html

JS:   process.env.HOME
来源：http://dali.yueranfly.top/Article/details/gtyusyoxtw.html

TS:   process.env.HOME
来源：http://dali.gogol.net.cn/Article/details/gtlvgawkss.html

Java: System.getenv("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gtumaljukc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.smart0.xyz/Article/details/gtxzclsnox.html

Ruby: ENV["HOME"]
来源：http://dali.feifeiyinyue.top/Article/details/gtdzozhjqq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.guannengcc.top/Article/details/gtfntzotls.html

[M03] 执行外部命令
来源：http://dali.chenlongwang.top/Article/details/gthfzovgnq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.birdmap.top/Article/details/gtcesqwooa.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jlsjyb.cn/Article/details/gtjbwqzcjw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.guowangkeji.top/Article/details/gtkrhjqwlh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jlsjyb.cn/Article/details/gtjutfdoez.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.0kj1m.cn/Article/details/gtwoazqotm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hysaishi.cn/Article/details/gtabmofows.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cdnleiting.top/Article/details/gtmgmgotxj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.vqdsnc.cn/Article/details/gtceiqqbuj.html

[M04] 获取当前工作目录
来源：http://dali.c1oappe.top/Article/details/gtglkpzusj.html

Py:   os.getcwd()
来源：http://dali.cqqwz.cn/Article/details/gtrasrtuwg.html

PHP:  getcwd();
来源：http://dali.chenzaomai.com/Article/details/gtgetpmevn.html

JS:   process.cwd()
来源：http://dali.bjfxy.top/Article/details/gtvuwchmrh.html

TS:   process.cwd()
来源：http://dali.zycfv.cn/Article/details/gthuhmnnei.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sweek.top/Article/details/gtjyknichf.html

Go:   os.Getwd()
来源：http://dali.zhiwuduotai.top/Article/details/gteglbhhjl.html

Ruby: Dir.pwd
来源：http://dali.kuanghao11.cn/Article/details/gtarvzhicz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cucudq.cn/Article/details/gtaqhypppu.html

[M05] 设置退出码
来源：http://dali.sufxvd.cn/Article/details/gtxlfpzsor.html

Py:   sys.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtrterkegn.html

PHP:  exit(1);
来源：http://dali.nanxinkj.top/Article/details/gtjpwiusfj.html

JS:   process.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gttfqniqnd.html

TS:   process.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gtwnnkjpzk.html

Java: System.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gtfyinwmll.html

Go:   os.Exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpcmfiptv.html

Ruby: exit 1
来源：http://dali.yueranfly.top/Article/details/gtwimxminv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.birdmap.top/Article/details/gtdhxbbrdk.html

[M06] 向标准错误输出
来源：http://dali.andypj.xyz/Article/details/gtrjxmmogy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.316326.xyz/Article/details/gtsdddhwzu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdzxidvsw.html

JS:   console.error("err")
来源：http://dali.redwolf501.top/Article/details/gtxvxidwxe.html

TS:   console.error("err")
来源：http://dali.jlsjyb.cn/Article/details/gtmxkspjwl.html

Java: System.err.println("err")
来源：http://dali.chenlongwang.top/Article/details/gtouhqoevj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hywenlv.cn/Article/details/gtupumzcol.html

Ruby: warn "err"
来源：http://dali.daxiang520.top/Article/details/gtkzrxkdns.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gotoacloud.top/Article/details/gtlsfocbhe.html

[M07] 判断是否为主入口
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjmtvpmjo.html

Py:   if __name__ == "__main__":
来源：http://dali.hnxiangtu.top/Article/details/gtfnypgzsh.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.dashuyun.cn/Article/details/gtjhkfeksb.html

JS:   require.main === module
来源：http://dali.shangyingyoupin.top/Article/details/gtjmykhupz.html

TS:   require.main === module
来源：http://dali.zhengqikj.top/Article/details/gtbunrohdq.html

Java: public static void main(String[] args)
来源：http://dali.yueranfly.top/Article/details/gtdrpshbap.html

Go:   func main()
来源：http://dali.wangdashe.top/Article/details/gtogsufnvn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xziqi.cn/Article/details/gtxpxkcjtx.html

C#:   static void Main(string[] args)
来源：http://dali.cqqwz.cn/Article/details/gtkcnuftpz.html

[M08] 获取系统与运行时信息
来源：http://dali.gogol.net.cn/Article/details/gtihdfuqff.html

Py:   platform.system();  platform.python_version()
来源：http://dali.smart0.xyz/Article/details/gtavdgsnda.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.pengpengdd.cyou/Article/details/gtzshkrmjr.html

JS:   process.platform;  process.version
来源：http://dali.smart0.xyz/Article/details/gtcuaszvzc.html

TS:   process.platform;  process.version
来源：http://dali.yonumen.top/Article/details/gtmkgihsfg.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttaplewbv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.c1oappe.top/Article/details/gtobabpndn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinghuilouyu.cn/Article/details/gtaafykjdb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.0kj1m.cn/Article/details/gttzaouarx.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtewfxfhvj.html

N. 数据结构与算法
来源：http://dali.svipenyu.cn/Article/details/gttfuygnwq.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtgpaslbyw.html

[N01] 二分查找（有序数组）
来源：http://dali.ydzc1.top/Article/details/gtztfmlkas.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtdwnmdwlr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jianghu66.top/Article/details/gtueofvboj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xylfe.cn/Article/details/gtrgmoanoe.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xylfe.cn/Article/details/gtfzytwote.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtgqxttlto.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtomlwlwob.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hammf.cn/Article/details/gtmhnewfuj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtlsimxnqt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.snrcjt.cn/Article/details/gtoefexrlu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shuidangran.top/Article/details/gtloggxvax.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cheryme.top/Article/details/gtaeldlsot.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tianlin.xyz/Article/details/gtuxxqxqbn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sysykeji.top/Article/details/gtwoepwflf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhongyouzk.top/Article/details/gtrnvhfywf.html

Go:   slices.Sort(arr)
来源：http://dali.yuanzhike.top/Article/details/gtrekyripk.html

Ruby: arr.sort
来源：http://dali.snrcjt.cn/Article/details/gtjzobwfcb.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yongpay.top/Article/details/gtrbhocxqr.html

[N03] 快速排序（分治示例）
来源：http://dali.jinqigufen.top/Article/details/gtocczmvir.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gotoacloud.top/Article/details/gtzavdsnrw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.redwolf501.top/Article/details/gtzlctrnpq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aibaodan.cn/Article/details/gtmdozrjvs.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.iojbl.cn/Article/details/gtxxhwbcyt.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.kuanghao11.cn/Article/details/gtlxndmnql.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.quarkkingdee.top/Article/details/gtfblyvdmn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yonumen.top/Article/details/gtlhefhdrm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.birdmap.top/Article/details/gtonfmpkjr.html

[N04] 斐波那契数列
来源：http://dali.hnxiangtu.top/Article/details/gtdxdmfizx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ybcxt.top/Article/details/gtsskfttun.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yanxiufei.cn/Article/details/gtvegxmims.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xylfe.cn/Article/details/gtmdgjnmsi.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sxryk.cn/Article/details/gtnetgxugh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xuetiantiany.cn/Article/details/gtifdqlbxb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ydzc1.top/Article/details/gtcczzltsn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yongpay.top/Article/details/gtezbrlrgi.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.gaohongyu789.top/Article/details/gtumlqqkws.html

[N05] 最大公约数
来源：http://dali.wangshuangyany.cn/Article/details/gtuatkbhqb.html

Py:   math.gcd(a, b)
来源：http://dali.nwbrower.top/Article/details/gtjiblorjk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hammf.cn/Article/details/gtiessdzmr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.c1oappe.top/Article/details/gttqmbgmgc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ehwqpu.com/Article/details/gtyvbafrfr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hysaishi.cn/Article/details/gtxrvwhajv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhengqikj.top/Article/details/gtbmcmubfb.html

Ruby: a.gcd(b)
来源：http://dali.pengpengdd.cyou/Article/details/gtkiyfnnsk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.havefunace.top/Article/details/gthnfceoad.html

[N06] 判断回文字符串
来源：http://dali.kuanghao11.cn/Article/details/gtucattuhq.html

Py:   s == s[::-1]
来源：http://dali.aizwys.cn/Article/details/gtkrvpsvlj.html

PHP:  $s === strrev($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtsszqudii.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gtxgqokapu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gtxabpdznr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yuxming.cn/Article/details/gtqenonurw.html

Go:   // 双指针从两端比较
来源：http://dali.c1oappe.top/Article/details/gtgvjjplwv.html

Ruby: s == s.reverse
来源：http://dali.chenzaomai.com/Article/details/gtfgxozncw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yanxiufei.cn/Article/details/gtlvoghqtj.html

[N07] 两数之和（返回下标）
来源：http://dali.shuidangran.top/Article/details/gtusmlnfwh.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.fzhhl.top/Article/details/gtnvwscvne.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shzxlz.cn/Article/details/gtvhxqeagf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gzhubu.top/Article/details/gtnnhyvyii.html

TS:   // 手写 Map<string, number>
来源：http://dali.fzhhl.top/Article/details/gtoqbclbsg.html

Java: // 手写 HashMap
来源：http://dali.shangyingyoupin.top/Article/details/gtsuswwlgp.html

Go:   // 手写 map[int]int
来源：http://dali.shanyushiyangtech.top/Article/details/gtwwmaisov.html

Ruby: // 手写 Hash
来源：http://dali.bjfxy.top/Article/details/gtsgkdrqpv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.aizwys.cn/Article/details/gtkdhqvblh.html

[N08] 生成全排列
来源：http://dali.gzhubu.top/Article/details/gtvizjtggs.html

Py:   itertools.permutations(arr)
来源：http://dali.meibo888.top/Article/details/gtcgzsfikm.html

PHP:  // 手写递归交换
来源：http://dali.316326.xyz/Article/details/gtjoezllhd.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gtcntvritn.html

TS:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gtqxwszhdk.html

Java: // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gtcykzodir.html

Go:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gtkupessku.html

Ruby: arr.permutation.to_a
来源：http://dali.xuetiantiany.cn/Article/details/gtnaikvere.html

C#:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gtnackzyis.html

[N09] 栈与队列
来源：http://dali.gogol.net.cn/Article/details/gtszlyegqx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.haohaochexian.top/Article/details/gtyukutvqn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.guannengcc.top/Article/details/gtohkokvcf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.andypj.xyz/Article/details/gtetsulnpw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.andypj.xyz/Article/details/gttdublnxr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cdnleiting.top/Article/details/gtpneaqtnx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.havefunace.top/Article/details/gtogszukhp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cashguo.top/Article/details/gtnmzfaduc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xylfe.cn/Article/details/gtxmkypvdp.html

[N10] 链表节点定义
来源：http://dali.smart0.xyz/Article/details/gtnqtnmuna.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinghuilouyu.cn/Article/details/gtdeeexguu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gtlhxybodg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hammf.cn/Article/details/gtmfywbpfv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinqigufen.top/Article/details/gtnqibjfgo.html

Java: class Node { int v; Node next; }
来源：http://dali.meibo888.top/Article/details/gtdzyfpnlh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gotoacloud.top/Article/details/gtppgobdkt.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hongshengwenyu.top/Article/details/gtztvkfvfb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ydzc1.top/Article/details/gtirejctmh.html

[N11] 二叉树中序遍历
来源：http://dali.xylfe.cn/Article/details/gtmhrwiuwn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xuanzx.com/Article/details/gtpttylslb.html

PHP:  // 手写递归函数
来源：http://dali.zhengqikj.top/Article/details/gtrhxnoznb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ppjwa.cn/Article/details/gttahhknbs.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.redwolf501.top/Article/details/gtqgdfjfif.html

Java: // 手写递归
来源：http://dali.tianlin.xyz/Article/details/gtellvcfhu.html

Go:   // 手写递归
来源：http://dali.c1oappe.top/Article/details/gtwpyskfld.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hfpthk.cn/Article/details/gtxpsfgyxg.html

C#:   // 手写递归
来源：http://dali.hnqzz.top/Article/details/gthukgwnzf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gtzwpaxgug.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.pycfn.com/Article/details/gtbosnpulf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hongshengwenyu.top/Article/details/gtyinndhzx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ehwqpu.com/Article/details/gtnlnyfyen.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xinyue.icu/Article/details/gtjhcfakej.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuanzhike.top/Article/details/gtybkpnpye.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.pengpengdd.cyou/Article/details/gtjvmjbdft.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hammf.cn/Article/details/gtnnhovejc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cashguo.top/Article/details/gtfsnkuwju.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtobznllbz.html

O. 并发与异步
来源：http://dali.yueranfly.top/Article/details/gticsddlas.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtujgdulaf.html

[O01] 启动一个线程
来源：http://dali.guowangkeji.top/Article/details/gtncdcthjj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yanxiufei.cn/Article/details/gttevcukmg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.smart0.xyz/Article/details/gtwueimrgq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhaomingkeji.xyz/Article/details/gtysxablxr.html

TS:   // 同 JS
来源：http://dali.zhaomingkeji.xyz/Article/details/gtghuugwbk.html

Java: new Thread(() -> f()).start()
来源：http://dali.nwbrower.top/Article/details/gtorkfatlq.html

Go:   go f()
来源：http://dali.guannengcc.top/Article/details/gthzqoypka.html

Ruby: Thread.new { f }
来源：http://dali.guowangkeji.top/Article/details/gttddlygwo.html

C#:   Task.Run(() => F());
来源：http://dali.yuxming.cn/Article/details/gtzdzuhzim.html

[O02] 使用线程池
来源：http://dali.ydzc1.top/Article/details/gthnqbaqva.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinqigfzy.top/Article/details/gttvewgzza.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqnqyaxbi.html

JS:   // worker_threads 线程池
来源：http://dali.zhiwuduotai.top/Article/details/gtmbcbvbkt.html

TS:   // worker_threads 线程池
来源：http://dali.hywenlv.cn/Article/details/gtfxfuwpzn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hfpthk.cn/Article/details/gtrmvdvdxu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.birdmap.top/Article/details/gtcsavcdra.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jqgufenzy.top/Article/details/gtocvgkkck.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hongshengwenyu.top/Article/details/gtynusykrd.html

[O03] 加锁保护共享数据
来源：http://dali.svipenyu.cn/Article/details/gtnoovvhjm.html

Py:   with lock: shared += 1
来源：http://dali.shangyingyoupin.top/Article/details/gtyvyogmvy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gtrlqdrdwa.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.nanxinkj.top/Article/details/gttxnnffrh.html

TS:   // 同 JS
来源：http://dali.sweek.top/Article/details/gtfttpyzxm.html

Java: synchronized (this) { shared++; }
来源：http://dali.daria6918.cn/Article/details/gtoxwxnnbd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gzhubu.top/Article/details/gtvhpicrnr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.vqdsnc.cn/Article/details/gttczsjnia.html

C#:   lock (gate) { shared++; }
来源：http://dali.shangyingyoupin.top/Article/details/gtaymhsvaa.html

[O04] 定义异步函数并等待
来源：http://dali.tian-w.cn/Article/details/gtelrglzvg.html

Py:   async def f():⏎    await g()
来源：http://dali.nwbrower.top/Article/details/gtdwhjjikv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhaomingkeji.xyz/Article/details/gttkbvgcow.html

JS:   async function f() { await g(); }
来源：http://dali.jqgufenzy.top/Article/details/gtrgbgnrhz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gthqbbyppz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinqigfzy.top/Article/details/gtnlaedlnt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.tianlin.xyz/Article/details/gtnqwfmxaf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.dashuyun.cn/Article/details/gtmxeylquw.html

C#:   async Task F() { await G(); }
来源：http://dali.316326.xyz/Article/details/gtihomsrgc.html

[O05] 并发执行并等待全部完成
来源：http://dali.pengpengdd.cyou/Article/details/gtzmxkfyis.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hnxiangtu.top/Article/details/gtentrjglc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.9152youxi.cn/Article/details/gtorltedji.html

JS:   await Promise.all(tasks)
来源：http://dali.haohaochexian.top/Article/details/gtonifiuzb.html

TS:   await Promise.all(tasks)
来源：http://dali.nanxinkj.top/Article/details/gtsunaixbr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hnxiangtu.top/Article/details/gthwksrtkk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ydzc1.top/Article/details/gtfvrrzxph.html

Ruby: threads.map(&:join)
来源：http://dali.gogol.net.cn/Article/details/gtovrszkfl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jqgufenzy.top/Article/details/gttsteibiv.html

[O06] 使用进程池
来源：http://dali.shzxlz.cn/Article/details/gtgdjfngja.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jinqigfzy.top/Article/details/gtcgtmdzch.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zdqjudy.top/Article/details/gtgflbnwxp.html

JS:   // child_process / cluster 模块
来源：http://dali.cheryme.top/Article/details/gtmhyydjla.html

TS:   // child_process / cluster 模块
来源：http://dali.zycfv.cn/Article/details/gttaajfaqk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hfpthk.cn/Article/details/gtskfumduq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ehwqpu.com/Article/details/gtwbungeyu.html

Ruby: // fork 块
来源：http://dali.meibo888.top/Article/details/gtlzelqiwj.html

C#:   Parallel.For
来源：http://dali.jqgfzy.top/Article/details/gtrtznmpat.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtkzpcmylu.html

P. 常用工具函数
来源：http://dali.xziqi.cn/Article/details/gtfqmcpaix.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtzvonjjbg.html

[P01] 生成 UUID
来源：http://dali.dianchejie.cn/Article/details/gtvjrakynb.html

Py:   str(uuid.uuid4())
来源：http://dali.jianghu66.top/Article/details/gtjkoapssv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xylfe.cn/Article/details/gtjppqhgeu.html

JS:   crypto.randomUUID()
来源：http://dali.yuxming.cn/Article/details/gtpbrlxqmr.html

TS:   crypto.randomUUID()
来源：http://dali.tianlin.xyz/Article/details/gtvwtuqbvd.html

Java: UUID.randomUUID().toString()
来源：http://dali.aibaodan.cn/Article/details/gtigdunelv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.nwbrower.top/Article/details/gtjghlrxjp.html

Ruby: SecureRandom.uuid
来源：http://dali.birdmap.top/Article/details/gtvuqqnmon.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.gaohongyu789.top/Article/details/gttvmwpqtn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yj202588.top/Article/details/gtvblpivus.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.9152youxi.cn/Article/details/gtrpnpqlbp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinqigfzy.top/Article/details/gtbjecwybx.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xinyue.icu/Article/details/gtbeqsseyg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.redwolf501.top/Article/details/gtfrslypwv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.mhx1999.top/Article/details/gtfkfdvheu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.nanxinkj.top/Article/details/gtqawmfvfn.html


<!-- 参考信息 -->