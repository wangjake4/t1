代发 wailian999

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gteerrdayy.html

[L04] 设置超时
来源：http://dali.wangdashe.top/Article/details/gtrbriatyu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hfpthk.cn/Article/details/gtvqfvzsqv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yuanzhike.top/Article/details/gtpczfprze.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hywenlv.cn/Article/details/gtqtkohttd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvuaczvha.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ivvv.top/Article/details/gtqcjvyjij.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.guowangkeji.top/Article/details/gtchzquqlp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nwbrower.top/Article/details/gtvwvcrrpl.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhixingplan.top/Article/details/gtwsnuzlle.html

[L05] 上传文件（multipart）
来源：http://dali.zdqjudy.top/Article/details/gtdclhmjfg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xylfe.cn/Article/details/gtaqqjuvev.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinqigfzy.top/Article/details/gtzbinhwld.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gaohongyu789.top/Article/details/gtsordvugm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.0kj1m.cn/Article/details/gtcyehnanm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shanyushiyangtech.top/Article/details/gtjatrgnly.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yueranfly.top/Article/details/gtmsagtolr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ppjwa.cn/Article/details/gtnyilfbve.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtqkohvdvp.html

[L06] 解析响应为 JSON
来源：http://dali.hfpthk.cn/Article/details/gtyigxfugc.html

Py:   resp.json()
来源：http://dali.shzxlz.cn/Article/details/gteaxiqcum.html

PHP:  json_decode($body, true);
来源：http://dali.xziqi.cn/Article/details/gtqxiirunt.html

JS:   await resp.json()
来源：http://dali.hnqzz.top/Article/details/gtnjcixtxi.html

TS:   await resp.json()
来源：http://dali.cqqwz.cn/Article/details/gtxamukcpl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gtlbifpais.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinqigufen.top/Article/details/gtavnpqwhm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.kuanghao11.cn/Article/details/gttehuirgo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gtrysqbvzu.html

[L07] 处理 HTTP 状态码
来源：http://dali.sweek.top/Article/details/gtqfaobhts.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.fengsongda.top/Article/details/gttxqlupqi.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.guowangkeji.top/Article/details/gtzqpzvqmc.html

JS:   resp.ok;  resp.status
来源：http://dali.yonumen.top/Article/details/gtwubkqmfe.html

TS:   resp.ok;  resp.status
来源：http://dali.yj20258.top/Article/details/gtoinbrdnw.html

Java: resp.statusCode()
来源：http://dali.yonumen.top/Article/details/gtaznqufxb.html

Go:   resp.StatusCode
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtczqaoarr.html

Ruby: resp.code.to_i
来源：http://dali.hfpthk.cn/Article/details/gtszevqxyb.html

C#:   (int)resp.StatusCode
来源：http://dali.wangdashe.top/Article/details/gtlqryqfjs.html

[L08] 并发请求多个地址
来源：http://dali.yongpay.top/Article/details/gtyktueugg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.haohaochexian.top/Article/details/gtrapbwsyv.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhoulong.xyz/Article/details/gtqnzfdque.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yanxiufei.cn/Article/details/gtcsdsgwfr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xinyue.icu/Article/details/gtynmizwpt.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.wangshuangyany.cn/Article/details/gtgibtnece.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hnxiangtu.top/Article/details/gtujctquov.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.birdmap.top/Article/details/gttypicimt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hnxiangtu.top/Article/details/gtumsxocsi.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtusildwaw.html

M. 命令行 / 进程 / 环境
来源：http://dali.jiagoushi.top/Article/details/gtsllfjrwz.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtxkytixmj.html

[M01] 读取命令行参数
来源：http://dali.yvedp.cn/Article/details/gtlpklnuxm.html

Py:   sys.argv[1:]
来源：http://dali.316326.xyz/Article/details/gtxbijiwdm.html

PHP:  $argv;  $argc;
来源：http://dali.ydzc1.top/Article/details/gtlbkbsdia.html

JS:   process.argv.slice(2)
来源：http://dali.kuanghao11.cn/Article/details/gtgquiiojs.html

TS:   process.argv.slice(2)
来源：http://dali.nanxinkj.top/Article/details/gthhzfftsy.html

Java: args 数组（main 方法参数）
来源：http://dali.sxryk.cn/Article/details/gtqkclixnx.html

Go:   os.Args[1:]
来源：http://dali.ydzc1.top/Article/details/gtxfwdfbcx.html

Ruby: ARGV
来源：http://dali.jinqigfzy.top/Article/details/gtefhvdmkd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.nanxinkj.top/Article/details/gtliolaetu.html

[M02] 读取环境变量
来源：http://dali.havefunace.top/Article/details/gthcanexbj.html

Py:   os.environ.get("HOME")
来源：http://dali.haohaochexian.top/Article/details/gtxfghaykt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.dianchejie.cn/Article/details/gtuzrolsdc.html

JS:   process.env.HOME
来源：http://dali.yuanzhike.top/Article/details/gtjwuhxhlk.html

TS:   process.env.HOME
来源：http://dali.yongpay.top/Article/details/gttnoxhzel.html

Java: System.getenv("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgaedfdvk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cheryme.top/Article/details/gthqusjfrl.html

Ruby: ENV["HOME"]
来源：http://dali.zhoulong.xyz/Article/details/gtqnlbypoe.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.fengsongda.top/Article/details/gtvbeawrgk.html

[M03] 执行外部命令
来源：http://dali.xylfe.cn/Article/details/gtgwxditxg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.meibo888.top/Article/details/gtifdapeat.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.redwolf501.top/Article/details/gtkcqtmhwp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.pycfn.com/Article/details/gthnebhagk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.feifeiyinyue.top/Article/details/gtalicbmtq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.9152youxi.cn/Article/details/gtfsixknjg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhongyouzk.top/Article/details/gtymgwqfoa.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.nwbrower.top/Article/details/gtenaruswi.html

C#:   Process.Start("ls", "-l");
来源：http://dali.daxiang520.top/Article/details/gtkkafzzxd.html

[M04] 获取当前工作目录
来源：http://dali.jianghu66.top/Article/details/gtnzkxowdm.html

Py:   os.getcwd()
来源：http://dali.gaohongyu789.top/Article/details/gtaoetwbwb.html

PHP:  getcwd();
来源：http://dali.ehwqpu.com/Article/details/gtkxbixcdv.html

JS:   process.cwd()
来源：http://dali.sysykeji.top/Article/details/gtudloppon.html

TS:   process.cwd()
来源：http://dali.nanxuanxn.top/Article/details/gtupcsmvto.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yongpay.top/Article/details/gtaxfnrcvn.html

Go:   os.Getwd()
来源：http://dali.hywenlv.cn/Article/details/gtlumucwqf.html

Ruby: Dir.pwd
来源：http://dali.snrcjt.cn/Article/details/gtsifnqjhs.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.mhx1999.top/Article/details/gthweeqakp.html

[M05] 设置退出码
来源：http://dali.jinghuilouyu.cn/Article/details/gtwxyueqbn.html

Py:   sys.exit(1)
来源：http://dali.meibo888.top/Article/details/gtftdkcmqb.html

PHP:  exit(1);
来源：http://dali.aizwys.cn/Article/details/gteprujnry.html

JS:   process.exit(1)
来源：http://dali.tian-w.cn/Article/details/gtqqxzolih.html

TS:   process.exit(1)
来源：http://dali.yueranfly.top/Article/details/gtfqlxxvzf.html

Java: System.exit(1)
来源：http://dali.316326.xyz/Article/details/gtumxupyrj.html

Go:   os.Exit(1)
来源：http://dali.sweek.top/Article/details/gtorsajszt.html

Ruby: exit 1
来源：http://dali.cqqwz.cn/Article/details/gtqurctskt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhiwuduotai.top/Article/details/gtkkrtdtnh.html

[M06] 向标准错误输出
来源：http://dali.jiagoushi.top/Article/details/gtfcjunbeb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.tanke756.top/Article/details/gtpseqygoj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ppjwa.cn/Article/details/gtofebglfs.html

JS:   console.error("err")
来源：http://dali.yongpay.top/Article/details/gteyjrznjr.html

TS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gttanppolc.html

Java: System.err.println("err")
来源：http://dali.zdqjudy.top/Article/details/gtxufzwzoi.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jlsjyb.cn/Article/details/gtvrmneton.html

Ruby: warn "err"
来源：http://dali.dashuyun.cn/Article/details/gtsafzydmp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jqgfzy.top/Article/details/gtsiawqxzh.html

[M07] 判断是否为主入口
来源：http://dali.mhx1999.top/Article/details/gtamcgrmky.html

Py:   if __name__ == "__main__":
来源：http://dali.yangfankeji.com/Article/details/gttwgvwipq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yongpay.top/Article/details/gtxrzgtlmh.html

JS:   require.main === module
来源：http://dali.hongshengwenyu.top/Article/details/gtyrrjnfcf.html

TS:   require.main === module
来源：http://dali.yangfankeji.com/Article/details/gtmnhcjkui.html

Java: public static void main(String[] args)
来源：http://dali.zhengqikj.top/Article/details/gtvhjgtisz.html

Go:   func main()
来源：http://dali.ybcxt.top/Article/details/gtxoumwujl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shuidangran.top/Article/details/gtabjlignr.html

C#:   static void Main(string[] args)
来源：http://dali.wangdashe.top/Article/details/gtlzoifdxe.html

[M08] 获取系统与运行时信息
来源：http://dali.0kj1m.cn/Article/details/gtaztiaaen.html

Py:   platform.system();  platform.python_version()
来源：http://dali.havefunace.top/Article/details/gtlmgpkanw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yongpay.top/Article/details/gtklkdglos.html

JS:   process.platform;  process.version
来源：http://dali.shuidangran.top/Article/details/gtffkthoit.html

TS:   process.platform;  process.version
来源：http://dali.daria6918.cn/Article/details/gtvnmhmjdk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.haohaochexian.top/Article/details/gtblyjyzsg.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hnxiangtu.top/Article/details/gtxvchvuje.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.haohaochexian.top/Article/details/gtwsqzpfot.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xziqi.cn/Article/details/gtdqrxajxw.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtvirbryki.html

N. 数据结构与算法
来源：http://dali.hfpthk.cn/Article/details/gtjvshqhlp.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtfaenntgd.html

[N01] 二分查找（有序数组）
来源：http://dali.hnxiangtu.top/Article/details/gtmgccbkqd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.316326.xyz/Article/details/gtvygefgwk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.tian-w.cn/Article/details/gtcmovczdt.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangdashe.top/Article/details/gtwmvyeevi.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cashguo.top/Article/details/gthnyowyuo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtimrjyjdu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtffpymckm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.feifeiyinyue.top/Article/details/gtmsnrnnid.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtqdwkbghs.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.pengpengdd.cyou/Article/details/gtkzrlqcng.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hysaishi.cn/Article/details/gtwljfwsma.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfolqufsr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwxzxhrce.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnxiangtu.top/Article/details/gtbtvkrdby.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hongshengwenyu.top/Article/details/gtbbtixdop.html

Go:   slices.Sort(arr)
来源：http://dali.zhixingplan.top/Article/details/gtholwoqej.html

Ruby: arr.sort
来源：http://dali.316326.xyz/Article/details/gtspgqeagm.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gaohongyu789.top/Article/details/gtmdaufrrx.html

[N03] 快速排序（分治示例）
来源：http://dali.nanxinkj.top/Article/details/gtlyxadxmr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.dianchejie.cn/Article/details/gtsnsscqyq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hywenlv.cn/Article/details/gtapzagxzx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hysaishi.cn/Article/details/gtogaaozxt.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.316326.xyz/Article/details/gtjnypkhcb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.nanxinkj.top/Article/details/gtiuuzcbch.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.fzhhl.top/Article/details/gtodrsqcji.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jqgufenzy.top/Article/details/gtxcdotxjy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.kuanghao11.cn/Article/details/gttwmjocem.html

[N04] 斐波那契数列
来源：http://dali.jlsjyb.cn/Article/details/gtuxxlpwhl.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigufen.top/Article/details/gtagqewaai.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhongyouzk.top/Article/details/gtckbpyqbs.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhoulong.xyz/Article/details/gtqamgdose.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yonumen.top/Article/details/gtpromykwe.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.tianlin.xyz/Article/details/gtgbluhrbe.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cdnleiting.top/Article/details/gtdabnrloq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jianghu66.top/Article/details/gtcwliihqb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hnxiangtu.top/Article/details/gtyqewujur.html

[N05] 最大公约数
来源：http://dali.mhx1999.top/Article/details/gtblskqtyv.html

Py:   math.gcd(a, b)
来源：http://dali.mhx1999.top/Article/details/gtvztrnvjy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hysaishi.cn/Article/details/gtiuqkldin.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tian-w.cn/Article/details/gtrwrhihdi.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.kuanghao11.cn/Article/details/gtzjxrzxhv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.chenlongwang.top/Article/details/gtzdxxhsvx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.gotoacloud.top/Article/details/gtvlutcrin.html

Ruby: a.gcd(b)
来源：http://dali.zdqjudy.top/Article/details/gtvsvfursp.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttqqcrgzh.html

[N06] 判断回文字符串
来源：http://dali.chenzaomai.com/Article/details/gtwsblyobg.html

Py:   s == s[::-1]
来源：http://dali.shangyingyoupin.top/Article/details/gtrcpzrgwg.html

PHP:  $s === strrev($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtkboqpczv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gtnenumcck.html

TS:   s === [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gtjosmpysp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xuetiantiany.cn/Article/details/gtcxnmjqcm.html

Go:   // 双指针从两端比较
来源：http://dali.tanke756.top/Article/details/gtngirwiig.html

Ruby: s == s.reverse
来源：http://dali.yonumen.top/Article/details/gtnyjafbqn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.svipenyu.cn/Article/details/gtgghlchkp.html

[N07] 两数之和（返回下标）
来源：http://dali.jqgufenzy.top/Article/details/gtosifqgzu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.dianchejie.cn/Article/details/gtihluumbw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj202588.top/Article/details/gtvwxzybfp.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cdnleiting.top/Article/details/gtdoqgickk.html

TS:   // 手写 Map<string, number>
来源：http://dali.smart0.xyz/Article/details/gtwyhenqvn.html

Java: // 手写 HashMap
来源：http://dali.hongshengwenyu.top/Article/details/gtrovdufno.html

Go:   // 手写 map[int]int
来源：http://dali.wangshuangyany.cn/Article/details/gtuzujatam.html

Ruby: // 手写 Hash
来源：http://dali.kuanghao11.cn/Article/details/gtmhioptcn.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.chenjidiqi.icu/Article/details/gteeyruskz.html

[N08] 生成全排列
来源：http://dali.hnqzz.top/Article/details/gtiwpbgiib.html

Py:   itertools.permutations(arr)
来源：http://dali.yuxming.cn/Article/details/gtilvhjanx.html

PHP:  // 手写递归交换
来源：http://dali.dianchejie.cn/Article/details/gtinxbfqzr.html

JS:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gtjajqasah.html

TS:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gtfpmseiut.html

Java: // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gttimsvewf.html

Go:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtnvajggtm.html

Ruby: arr.permutation.to_a
来源：http://dali.zhixingplan.top/Article/details/gtqtrmrkzc.html

C#:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtezmrhwpo.html

[N09] 栈与队列
来源：http://dali.ivvv.top/Article/details/gtvtaiddyt.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jyoumei.cn/Article/details/gtfclxzmow.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shzxlz.cn/Article/details/gtrwxdfsat.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hysaishi.cn/Article/details/gtaptbvtcl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.wangdashe.top/Article/details/gtvpisxjty.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.c1oappe.top/Article/details/gtennyxkdi.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.haohaochexian.top/Article/details/gtqcytdumy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yj20258888.top/Article/details/gtovnfizej.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.nanxinkj.top/Article/details/gttluowyzy.html

[N10] 链表节点定义
来源：http://dali.sweek.top/Article/details/gtyvoffnpl.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.birdmap.top/Article/details/gtozstaxfd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.kuanghao11.cn/Article/details/gtsqxtxxte.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yuanzhike.top/Article/details/gtezyoubsl.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhengqikj.top/Article/details/gtaqcncghg.html

Java: class Node { int v; Node next; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvwzhzybd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.meibo888.top/Article/details/gtuqppixmo.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gaohongyu789.top/Article/details/gtcvlhafyd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hfpthk.cn/Article/details/gtyafqnnqw.html

[N11] 二叉树中序遍历
来源：http://dali.svipenyu.cn/Article/details/gtrzfguame.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.birdmap.top/Article/details/gthqjorivr.html

PHP:  // 手写递归函数
来源：http://dali.xinyue.icu/Article/details/gtcufwhnij.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.dianchejie.cn/Article/details/gtxpdzriyt.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ppjwa.cn/Article/details/gtstqjqzzm.html

Java: // 手写递归
来源：http://dali.ydzc1.top/Article/details/gtqhhouwwy.html

Go:   // 手写递归
来源：http://dali.dashuyun.cn/Article/details/gtjthqsemp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.nanxuanxn.top/Article/details/gtgbgtzisa.html

C#:   // 手写递归
来源：http://dali.0kj1m.cn/Article/details/gteoxihxaz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinghuilouyu.cn/Article/details/gtqzoqwuwk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtheyxaqnz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gotoacloud.top/Article/details/gtevuwokga.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xuanzx.com/Article/details/gtauhcsclw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuxming.cn/Article/details/gtmvxxavql.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ybcxt.top/Article/details/gtjcqyjdrr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sufxvd.cn/Article/details/gtijnoebmk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shzxlz.cn/Article/details/gtqtmmcagw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.vqdsnc.cn/Article/details/gtdkpwldab.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtresqrkfq.html

O. 并发与异步
来源：http://dali.yonumen.top/Article/details/gtgybijtdq.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtyoijmxyp.html

[O01] 启动一个线程
来源：http://dali.chenzaomai.com/Article/details/gtssnoacpg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.redwolf501.top/Article/details/gtuhrtozas.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hongshengwenyu.top/Article/details/gtdppvcilc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shzxlz.cn/Article/details/gtxjsxzzas.html

TS:   // 同 JS
来源：http://dali.vqdsnc.cn/Article/details/gttmfvpcrv.html

Java: new Thread(() -> f()).start()
来源：http://dali.shanyushiyangtech.top/Article/details/gtxleucrrk.html

Go:   go f()
来源：http://dali.birdmap.top/Article/details/gtjmezwhky.html

Ruby: Thread.new { f }
来源：http://dali.daria6918.cn/Article/details/gtfutpymfy.html

C#:   Task.Run(() => F());
来源：http://dali.zycfv.cn/Article/details/gtacorkuxt.html

[O02] 使用线程池
来源：http://dali.dianchejie.cn/Article/details/gtrgzdmtfp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yj20258.top/Article/details/gtkghfydjm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.daxiang520.top/Article/details/gtnhekucin.html

JS:   // worker_threads 线程池
来源：http://dali.feifeiyinyue.top/Article/details/gtyvsyveet.html

TS:   // worker_threads 线程池
来源：http://dali.wangshuangyany.cn/Article/details/gtrkqeghjz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.daxiang520.top/Article/details/gtgfunbapm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gaohongyu789.top/Article/details/gtrujbqczy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jianghu66.top/Article/details/gttuoqyhcv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gaohongyu789.top/Article/details/gtgcoookdv.html

[O03] 加锁保护共享数据
来源：http://dali.cdnleiting.top/Article/details/gtisiythus.html

Py:   with lock: shared += 1
来源：http://dali.yonumen.top/Article/details/gtinisfhlt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xuetiantiany.cn/Article/details/gtbgiqnzlp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhengqikj.top/Article/details/gtqnlypomv.html

TS:   // 同 JS
来源：http://dali.tanke756.top/Article/details/gtvxhtpomw.html

Java: synchronized (this) { shared++; }
来源：http://dali.ehwqpu.com/Article/details/gtbhaixeof.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cdnleiting.top/Article/details/gtdpzhroxb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.meibo888.top/Article/details/gtmfeuklag.html

C#:   lock (gate) { shared++; }
来源：http://dali.sysykeji.top/Article/details/gtwhgduoay.html

[O04] 定义异步函数并等待
来源：http://dali.yanxiufei.cn/Article/details/gtjgodukzb.html

Py:   async def f():⏎    await g()
来源：http://dali.aizwys.cn/Article/details/gtnvsrvshy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cucudq.cn/Article/details/gtstwlnutc.html

JS:   async function f() { await g(); }
来源：http://dali.smart0.xyz/Article/details/gtgvqqwfnd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.snrcjt.cn/Article/details/gtuqhjagey.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cucudq.cn/Article/details/gtgwmyifhs.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhengqikj.top/Article/details/gttcvpfxit.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.chenzaomai.com/Article/details/gtqejuvaqo.html

C#:   async Task F() { await G(); }
来源：http://dali.zhixingplan.top/Article/details/gtvbwtcnef.html

[O05] 并发执行并等待全部完成
来源：http://dali.yueranfly.top/Article/details/gtyqtmqcbw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.gogol.net.cn/Article/details/gtshtrlzhq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sxryk.cn/Article/details/gthseiwfeo.html

JS:   await Promise.all(tasks)
来源：http://dali.snrcjt.cn/Article/details/gtipbiruki.html

TS:   await Promise.all(tasks)
来源：http://dali.wangshuangyany.cn/Article/details/gtudoiuoqs.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ybcxt.top/Article/details/gtlarnixzl.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.dianchejie.cn/Article/details/gtfhhdcomn.html

Ruby: threads.map(&:join)
来源：http://dali.xylfe.cn/Article/details/gtlnlycrbw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xylfe.cn/Article/details/gtxgylzccd.html

[O06] 使用进程池
来源：http://dali.hnqzz.top/Article/details/gtxyuoades.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.andypj.xyz/Article/details/gtilpcvazq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.chenjidiqi.icu/Article/details/gttjvtggbd.html

JS:   // child_process / cluster 模块
来源：http://dali.yj20258888.top/Article/details/gtfieiqeqv.html

TS:   // child_process / cluster 模块
来源：http://dali.9152youxi.cn/Article/details/gtwmbfpapj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jinqigufen.top/Article/details/gtsjyqkyyy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.dianchejie.cn/Article/details/gtquxohiei.html

Ruby: // fork 块
来源：http://dali.9152youxi.cn/Article/details/gtehivwbfz.html

C#:   Parallel.For
来源：http://dali.redwolf501.top/Article/details/gtxgvwtwoo.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gttkfjgwrq.html

P. 常用工具函数
来源：http://dali.tianlin.xyz/Article/details/gttmaekrcz.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpkdxueof.html

[P01] 生成 UUID
来源：http://dali.jlsjyb.cn/Article/details/gtltnlucru.html

Py:   str(uuid.uuid4())
来源：http://dali.fzhhl.top/Article/details/gtcyigrxta.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zycfv.cn/Article/details/gtrxlatsoo.html

JS:   crypto.randomUUID()
来源：http://dali.jlsjyb.cn/Article/details/gtpkzjlkvc.html

TS:   crypto.randomUUID()
来源：http://dali.jqgufenzy.top/Article/details/gtpmdjxvgi.html

Java: UUID.randomUUID().toString()
来源：http://dali.jianghu66.top/Article/details/gtpglmnajn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.fzhhl.top/Article/details/gtmqoujvci.html

Ruby: SecureRandom.uuid
来源：http://dali.yongpay.top/Article/details/gtrsbxvaek.html


<!-- 参考信息 -->