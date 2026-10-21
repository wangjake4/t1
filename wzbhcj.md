代发 wailian999

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.wangdashe.top/Article/details/gtnddjzycp.html

[L04] 设置超时
来源：http://dali.chenzaomai.com/Article/details/gtkcwrcizt.html

Py:   requests.get(url, timeout=5)
来源：http://dali.wangshuangyany.cn/Article/details/gttsapdcct.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gaohongyu789.top/Article/details/gtmmbyuwhn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gtxfmlkpwf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangshuangyany.cn/Article/details/gtsukciyhm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xuetiantiany.cn/Article/details/gtswbtuner.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gzhubu.top/Article/details/gtdxkniqng.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.wangdashe.top/Article/details/gtcyoguoos.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hfpthk.cn/Article/details/gttigjwiew.html

[L05] 上传文件（multipart）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbkunqifx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xylfe.cn/Article/details/gtevpfyehd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj20258.top/Article/details/gtyjgjatmx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuxming.cn/Article/details/gtkclwssfb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.c1oappe.top/Article/details/gtgmgkgtdf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhixingplan.top/Article/details/gtepgllkvl.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinqigufen.top/Article/details/gteyqmkofv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.iojbl.cn/Article/details/gtzqwqtjmp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gogol.net.cn/Article/details/gttvsgrbwp.html

[L06] 解析响应为 JSON
来源：http://dali.havefunace.top/Article/details/gtbxdnxpqw.html

Py:   resp.json()
来源：http://dali.aizwys.cn/Article/details/gtrrcxbszo.html

PHP:  json_decode($body, true);
来源：http://dali.hysaishi.cn/Article/details/gtgksnabkp.html

JS:   await resp.json()
来源：http://dali.yanxiufei.cn/Article/details/gtmtkhfsma.html

TS:   await resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gtlkfrxwxj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.svipenyu.cn/Article/details/gterdojcac.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hfpthk.cn/Article/details/gtakrgcwmd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinqigfzy.top/Article/details/gtumrckiuk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.birdmap.top/Article/details/gthshwysqv.html

[L07] 处理 HTTP 状态码
来源：http://dali.nanxinkj.top/Article/details/gtbtjwhhsd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hongshengwenyu.top/Article/details/gtrjfmfnwa.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yangfankeji.com/Article/details/gtjeyfswih.html

JS:   resp.ok;  resp.status
来源：http://dali.jlsjyb.cn/Article/details/gtgixchodz.html

TS:   resp.ok;  resp.status
来源：http://dali.jlsjyb.cn/Article/details/gtwfgahkhv.html

Java: resp.statusCode()
来源：http://dali.kuanghao11.cn/Article/details/gtnkataixj.html

Go:   resp.StatusCode
来源：http://dali.hywenlv.cn/Article/details/gttwwogfbz.html

Ruby: resp.code.to_i
来源：http://dali.zdqjudy.top/Article/details/gttytobbqv.html

C#:   (int)resp.StatusCode
来源：http://dali.sweek.top/Article/details/gtdokajswb.html

[L08] 并发请求多个地址
来源：http://dali.jiagoushi.top/Article/details/gtpoymmohw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.0kj1m.cn/Article/details/gtenmbmbsf.html

PHP:  curl_multi_init() 系列
来源：http://dali.cucudq.cn/Article/details/gtkrbbfkzr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.havefunace.top/Article/details/gtoykmwlwd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fzhhl.top/Article/details/gtaipstcee.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.wangdashe.top/Article/details/gtpsnraexf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.fengsongda.top/Article/details/gtpkrugrkq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.tian-w.cn/Article/details/gtomyseomw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gtfpteldos.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gttiepzsst.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenlongwang.top/Article/details/gtmabiipmt.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtkoppilgh.html

[M01] 读取命令行参数
来源：http://dali.hysaishi.cn/Article/details/gtoaokrxvh.html

Py:   sys.argv[1:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuhdiniws.html

PHP:  $argv;  $argc;
来源：http://dali.chenzaomai.com/Article/details/gtfspzcnam.html

JS:   process.argv.slice(2)
来源：http://dali.fzhhl.top/Article/details/gtdtmgxztv.html

TS:   process.argv.slice(2)
来源：http://dali.sweek.top/Article/details/gtuesibqaa.html

Java: args 数组（main 方法参数）
来源：http://dali.yongpay.top/Article/details/gtaeehtxyv.html

Go:   os.Args[1:]
来源：http://dali.quarkkingdee.top/Article/details/gtxhoabycx.html

Ruby: ARGV
来源：http://dali.zhengqikj.top/Article/details/gtragtoehw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cucudq.cn/Article/details/gtfywjvnls.html

[M02] 读取环境变量
来源：http://dali.iojbl.cn/Article/details/gtlamhzutb.html

Py:   os.environ.get("HOME")
来源：http://dali.hammf.cn/Article/details/gteyqgluej.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhengqikj.top/Article/details/gtdctyvpuq.html

JS:   process.env.HOME
来源：http://dali.yongpay.top/Article/details/gtzvnivaho.html

TS:   process.env.HOME
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsfxyllwt.html

Java: System.getenv("HOME")
来源：http://dali.0kj1m.cn/Article/details/gtlccdmnow.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shuidangran.top/Article/details/gtvkkplkuw.html

Ruby: ENV["HOME"]
来源：http://dali.zdqjudy.top/Article/details/gtebtcgykk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gtopjdxbvc.html

[M03] 执行外部命令
来源：http://dali.cucudq.cn/Article/details/gtgrdfmsfn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yangfankeji.com/Article/details/gtyfuwxxmg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sweek.top/Article/details/gtypnesfxq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenlongwang.top/Article/details/gtcewilths.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.meibo888.top/Article/details/gtsykdxour.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.feifeiyinyue.top/Article/details/gtzkilwbbs.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sysykeji.top/Article/details/gtuqvspkdd.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yuxming.cn/Article/details/gtikbdffeu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.fengsongda.top/Article/details/gtfjnjfcsl.html

[M04] 获取当前工作目录
来源：http://dali.nanxinkj.top/Article/details/gtkuvlwygc.html

Py:   os.getcwd()
来源：http://dali.hywenlv.cn/Article/details/gtxmprduvr.html

PHP:  getcwd();
来源：http://dali.redwolf501.top/Article/details/gtiygmdjxk.html

JS:   process.cwd()
来源：http://dali.bjfxy.top/Article/details/gtabnsmrlk.html

TS:   process.cwd()
来源：http://dali.yongpay.top/Article/details/gthciydhay.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.svipenyu.cn/Article/details/gtvdpxmrjp.html

Go:   os.Getwd()
来源：http://dali.gogol.net.cn/Article/details/gtjsxxhhnv.html

Ruby: Dir.pwd
来源：http://dali.jlsjyb.cn/Article/details/gtitfkhdht.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yuxming.cn/Article/details/gttnikefte.html

[M05] 设置退出码
来源：http://dali.chenzaomai.com/Article/details/gtffkwdryy.html

Py:   sys.exit(1)
来源：http://dali.smart0.xyz/Article/details/gtqbbgoytn.html

PHP:  exit(1);
来源：http://dali.jianghu66.top/Article/details/gtgpikopbs.html

JS:   process.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtzqcgllif.html

TS:   process.exit(1)
来源：http://dali.mhx1999.top/Article/details/gtokszhzpn.html

Java: System.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gtnoaxmwef.html

Go:   os.Exit(1)
来源：http://dali.daria6918.cn/Article/details/gtmosczqes.html

Ruby: exit 1
来源：http://dali.smart0.xyz/Article/details/gtrdrefigy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.9152youxi.cn/Article/details/gtzjnitesi.html

[M06] 向标准错误输出
来源：http://dali.dianchejie.cn/Article/details/gtwuzsmame.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cdnleiting.top/Article/details/gtjufqhrwx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.birdmap.top/Article/details/gtqlpruwha.html

JS:   console.error("err")
来源：http://dali.nwbrower.top/Article/details/gtcomokows.html

TS:   console.error("err")
来源：http://dali.hnqzz.top/Article/details/gtiyzcdnmc.html

Java: System.err.println("err")
来源：http://dali.cdnleiting.top/Article/details/gtltnjtted.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jqgfzy.top/Article/details/gtdbixfkvz.html

Ruby: warn "err"
来源：http://dali.shangyingyoupin.top/Article/details/gtrkcedifi.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yj20258888.top/Article/details/gtzbkchmvf.html

[M07] 判断是否为主入口
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmdyaqpyp.html

Py:   if __name__ == "__main__":
来源：http://dali.tianlin.xyz/Article/details/gtryatsxjs.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sweek.top/Article/details/gtuhfnvqfj.html

JS:   require.main === module
来源：http://dali.havefunace.top/Article/details/gtcefiudrt.html

TS:   require.main === module
来源：http://dali.dianchejie.cn/Article/details/gtxhaojiob.html

Java: public static void main(String[] args)
来源：http://dali.tanke756.top/Article/details/gtettnudpq.html

Go:   func main()
来源：http://dali.yvedp.cn/Article/details/gtuoucwlrr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhongyouzk.top/Article/details/gtcphlwhet.html

C#:   static void Main(string[] args)
来源：http://dali.ivvv.top/Article/details/gtqpfggjro.html

[M08] 获取系统与运行时信息
来源：http://dali.hammf.cn/Article/details/gtxrctqhkv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gotoacloud.top/Article/details/gtbkjkdjfv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shuidangran.top/Article/details/gtpdsyxrkf.html

JS:   process.platform;  process.version
来源：http://dali.zhiwuduotai.top/Article/details/gtprvgdhlu.html

TS:   process.platform;  process.version
来源：http://dali.gogol.net.cn/Article/details/gtdicjbbgd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gtpdgztblg.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jyoumei.cn/Article/details/gttgnjwcjf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhongyouzk.top/Article/details/gtpmufyufe.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yangfankeji.com/Article/details/gtszishmby.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gthfdeilnk.html

N. 数据结构与算法
来源：http://dali.kuanghao11.cn/Article/details/gtbdaskuhs.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtzmtpbiaf.html

[N01] 二分查找（有序数组）
来源：http://dali.gotoacloud.top/Article/details/gtermrmnqu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.pycfn.com/Article/details/gtuqndtios.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.redwolf501.top/Article/details/gtzvksydbc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guannengcc.top/Article/details/gtfgekuxra.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdbqhqrwr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtwsutdxoj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.pycfn.com/Article/details/gtbubpykkv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gzhubu.top/Article/details/gtmpmrirqj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.pycfn.com/Article/details/gtucdobjdd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yj202588.top/Article/details/gtnuctklvv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yongpay.top/Article/details/gtqzscayck.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jqgfzy.top/Article/details/gtetnyvrrw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fzhhl.top/Article/details/gtkkysdyeq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cqqwz.cn/Article/details/gtihdkfwrd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.gzhubu.top/Article/details/gtayktkxgl.html

Go:   slices.Sort(arr)
来源：http://dali.dashuyun.cn/Article/details/gtypwzutvc.html

Ruby: arr.sort
来源：http://dali.guannengcc.top/Article/details/gtuewfogty.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xuanzx.com/Article/details/gtynkxlfyg.html

[N03] 快速排序（分治示例）
来源：http://dali.guowangkeji.top/Article/details/gtpzhxzqus.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.316326.xyz/Article/details/gtvvrxekyj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yuanzhike.top/Article/details/gtbtykxmok.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangdashe.top/Article/details/gtvvzdhdfs.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj202588.top/Article/details/gtowknpcco.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xuetiantiany.cn/Article/details/gtzxpvumxk.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yanxiufei.cn/Article/details/gtjlkqkiuu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.pycfn.com/Article/details/gtqxkzsqqk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.nanxinkj.top/Article/details/gtvfufltku.html

[N04] 斐波那契数列
来源：http://dali.xuetiantiany.cn/Article/details/gtciaeezfm.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sweek.top/Article/details/gtkcqrutia.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gtabqezhkd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jianghu66.top/Article/details/gtrchbgqlg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gthmnyqtym.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hysaishi.cn/Article/details/gtuurrsqmv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.tianlin.xyz/Article/details/gtphztvdnt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.birdmap.top/Article/details/gtobpmrugz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gtmorgfdxr.html

[N05] 最大公约数
来源：http://dali.nanxuanxn.top/Article/details/gtxchjomnw.html

Py:   math.gcd(a, b)
来源：http://dali.dashuyun.cn/Article/details/gtjleroiwh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sysykeji.top/Article/details/gtoijrlkfx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cdnleiting.top/Article/details/gtzqyyjifr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.birdmap.top/Article/details/gtjpnddfem.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.aizwys.cn/Article/details/gtsxpjxzxi.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jianghu66.top/Article/details/gtxplszvse.html

Ruby: a.gcd(b)
来源：http://dali.iojbl.cn/Article/details/gtygxarfzh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.nanxinkj.top/Article/details/gtyakviltm.html

[N06] 判断回文字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtmcvydooz.html

Py:   s == s[::-1]
来源：http://dali.yueranfly.top/Article/details/gtujjdyjzq.html

PHP:  $s === strrev($s);
来源：http://dali.snrcjt.cn/Article/details/gtsejvuwgy.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gtpuceezha.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gtckyecvkh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cdnleiting.top/Article/details/gtevbekoaq.html

Go:   // 双指针从两端比较
来源：http://dali.iojbl.cn/Article/details/gtyzxfoivz.html

Ruby: s == s.reverse
来源：http://dali.daria6918.cn/Article/details/gtbszbwgvw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hysaishi.cn/Article/details/gtnsiibxfu.html

[N07] 两数之和（返回下标）
来源：http://dali.316326.xyz/Article/details/gtaplhvupf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.pengpengdd.cyou/Article/details/gtcrbjrczw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.vqdsnc.cn/Article/details/gtqxbgvofd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gotoacloud.top/Article/details/gtebmoloul.html

TS:   // 手写 Map<string, number>
来源：http://dali.tanke756.top/Article/details/gtnjvpygub.html

Java: // 手写 HashMap
来源：http://dali.shangyingyoupin.top/Article/details/gteafxvmnh.html

Go:   // 手写 map[int]int
来源：http://dali.hammf.cn/Article/details/gtzovccyxf.html

Ruby: // 手写 Hash
来源：http://dali.xuetiantiany.cn/Article/details/gtpnolypqu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.iojbl.cn/Article/details/gtjtnyjnzt.html

[N08] 生成全排列
来源：http://dali.yvedp.cn/Article/details/gtvlnqovcr.html

Py:   itertools.permutations(arr)
来源：http://dali.xuanzx.com/Article/details/gtayzdcibg.html

PHP:  // 手写递归交换
来源：http://dali.daria6918.cn/Article/details/gtiabgevew.html

JS:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gttmmowuxo.html

TS:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gtdlzvsgvb.html

Java: // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gtjdvmowwx.html

Go:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gtotsjzpvk.html

Ruby: arr.permutation.to_a
来源：http://dali.hysaishi.cn/Article/details/gtfuepodbt.html

C#:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gtizvymvzp.html

[N09] 栈与队列
来源：http://dali.xziqi.cn/Article/details/gtgqqpfntg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.pengpengdd.cyou/Article/details/gtknwhseph.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcfdktjop.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cucudq.cn/Article/details/gtcwsbsigm.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shangyingyoupin.top/Article/details/gtdsblrwol.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinqigufen.top/Article/details/gtdpdqjsmn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gotoacloud.top/Article/details/gtvzvzacsc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ydzc1.top/Article/details/gtsmeyanvs.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.iojbl.cn/Article/details/gtjdhlmafa.html

[N10] 链表节点定义
来源：http://dali.xuetiantiany.cn/Article/details/gttbnpptfo.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shanyushiyangtech.top/Article/details/gtsunbzhqz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtibwtbhpq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xuanzx.com/Article/details/gtxaqipeon.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hywenlv.cn/Article/details/gthmldyuze.html

Java: class Node { int v; Node next; }
来源：http://dali.hnxiangtu.top/Article/details/gtkqoojvtt.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.svipenyu.cn/Article/details/gtsipdknkg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ehwqpu.com/Article/details/gtcztopaqk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hnxiangtu.top/Article/details/gtavjvoihl.html

[N11] 二叉树中序遍历
来源：http://dali.chenzaomai.com/Article/details/gtrsjzqcbt.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jiagoushi.top/Article/details/gtkyfmueua.html

PHP:  // 手写递归函数
来源：http://dali.tanke756.top/Article/details/gtfwtqomfq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhengqikj.top/Article/details/gtqhtzzllr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.9152youxi.cn/Article/details/gtqywjckzt.html

Java: // 手写递归
来源：http://dali.jiagoushi.top/Article/details/gttptabojn.html

Go:   // 手写递归
来源：http://dali.sufxvd.cn/Article/details/gtybxvylid.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ivvv.top/Article/details/gtigkfnxqr.html

C#:   // 手写递归
来源：http://dali.redwolf501.top/Article/details/gtxgbpdspu.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzxiquvgq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zycfv.cn/Article/details/gtkezucpoa.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.tian-w.cn/Article/details/gtvzltzszk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.0kj1m.cn/Article/details/gtnoiirnsj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sxryk.cn/Article/details/gtisojrbad.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yueranfly.top/Article/details/gtyodoyhfx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cheryme.top/Article/details/gtzoyclekx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.dianchejie.cn/Article/details/gtdlkeabum.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.dashuyun.cn/Article/details/gtxucwhbdh.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtcxvujodi.html

O. 并发与异步
来源：http://dali.chenlongwang.top/Article/details/gtpabarbxk.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtwtgrasiv.html

[O01] 启动一个线程
来源：http://dali.zhengqikj.top/Article/details/gtklnlglzy.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sufxvd.cn/Article/details/gtemowxxpf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhiwuduotai.top/Article/details/gtgvatjuqz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nwbrower.top/Article/details/gtjhbstesz.html

TS:   // 同 JS
来源：http://dali.zhixingplan.top/Article/details/gteyiwiuzf.html

Java: new Thread(() -> f()).start()
来源：http://dali.meibo888.top/Article/details/gteupmknyz.html

Go:   go f()
来源：http://dali.iojbl.cn/Article/details/gtkvwthxsu.html

Ruby: Thread.new { f }
来源：http://dali.quarkkingdee.top/Article/details/gthhubcwmt.html

C#:   Task.Run(() => F());
来源：http://dali.snrcjt.cn/Article/details/gtwsquwtaf.html

[O02] 使用线程池
来源：http://dali.aibaodan.cn/Article/details/gtsfxqymji.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.svipenyu.cn/Article/details/gtoigbnhmj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.quarkkingdee.top/Article/details/gtlsxggitr.html

JS:   // worker_threads 线程池
来源：http://dali.jinghuilouyu.cn/Article/details/gthjrcsais.html

TS:   // worker_threads 线程池
来源：http://dali.yj202588.top/Article/details/gtnynszxgd.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqpkzxuib.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.nanxuanxn.top/Article/details/gtssfthdat.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zdqjudy.top/Article/details/gtkvqwguer.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.dashuyun.cn/Article/details/gtocefgnfx.html

[O03] 加锁保护共享数据
来源：http://dali.cdnleiting.top/Article/details/gtwxvxkots.html

Py:   with lock: shared += 1
来源：http://dali.ivvv.top/Article/details/gtcldizibh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhengqikj.top/Article/details/gtluwdpelg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.nanxinkj.top/Article/details/gtoxyvizwk.html

TS:   // 同 JS
来源：http://dali.yj20258888.top/Article/details/gtjlnepafh.html

Java: synchronized (this) { shared++; }
来源：http://dali.cheryme.top/Article/details/gthocqeeod.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jqgufenzy.top/Article/details/gtghoytihl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.sxryk.cn/Article/details/gtjznxaohf.html

C#:   lock (gate) { shared++; }
来源：http://dali.tianlin.xyz/Article/details/gtatkgqjzl.html

[O04] 定义异步函数并等待
来源：http://dali.zdqjudy.top/Article/details/gtbrtgiemj.html

Py:   async def f():⏎    await g()
来源：http://dali.vqdsnc.cn/Article/details/gtsyflgwfx.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jiagoushi.top/Article/details/gtkhwmspdl.html

JS:   async function f() { await g(); }
来源：http://dali.meibo888.top/Article/details/gtuifbqbkw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.quarkkingdee.top/Article/details/gtcblzdqan.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yuanzhike.top/Article/details/gtnlzfsbcm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shangyingyoupin.top/Article/details/gteiyzvgoo.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.iojbl.cn/Article/details/gtfbirhpxl.html

C#:   async Task F() { await G(); }
来源：http://dali.smart0.xyz/Article/details/gthwxderjp.html

[O05] 并发执行并等待全部完成
来源：http://dali.sufxvd.cn/Article/details/gtxnnosndm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.sysykeji.top/Article/details/gtiyoenqtc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yvedp.cn/Article/details/gtyajqwjpt.html

JS:   await Promise.all(tasks)
来源：http://dali.ydzc1.top/Article/details/gtecdfpqnt.html

TS:   await Promise.all(tasks)
来源：http://dali.yvedp.cn/Article/details/gtdfilupuy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ybcxt.top/Article/details/gtmpfiicgr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tian-w.cn/Article/details/gtchknunqj.html

Ruby: threads.map(&:join)
来源：http://dali.9152youxi.cn/Article/details/gtkvleojba.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinqigfzy.top/Article/details/gtqyzajtxa.html

[O06] 使用进程池
来源：http://dali.chenjidiqi.icu/Article/details/gtdhahdfou.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jinqigufen.top/Article/details/gtqcnsachg.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shzxlz.cn/Article/details/gtbvfykrnm.html

JS:   // child_process / cluster 模块
来源：http://dali.yueranfly.top/Article/details/gtapbpfbee.html

TS:   // child_process / cluster 模块
来源：http://dali.yj202588.top/Article/details/gtxlrekong.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.redwolf501.top/Article/details/gtuskztskb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ivvv.top/Article/details/gtmivzufcb.html

Ruby: // fork 块
来源：http://dali.mhx1999.top/Article/details/gtoabgkcqa.html

C#:   Parallel.For
来源：http://dali.yuxming.cn/Article/details/gtfaaodsru.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtbzbognao.html

P. 常用工具函数
来源：http://dali.pycfn.com/Article/details/gtjjuhldxt.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtransoobf.html

[P01] 生成 UUID
来源：http://dali.daria6918.cn/Article/details/gtqfqrcwvd.html

Py:   str(uuid.uuid4())
来源：http://dali.cqqwz.cn/Article/details/gtryakntbk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yanxiufei.cn/Article/details/gtgvdzysag.html

JS:   crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtawlonzbp.html

TS:   crypto.randomUUID()
来源：http://dali.yuxming.cn/Article/details/gthfrxlney.html

Java: UUID.randomUUID().toString()
来源：http://dali.shzxlz.cn/Article/details/gtrmkfptva.html

Go:   // 用 github.com/google/uuid
来源：http://dali.9152youxi.cn/Article/details/gtawwgstiw.html

Ruby: SecureRandom.uuid
来源：http://dali.316326.xyz/Article/details/gtgcqblsia.html


<!-- 参考信息 -->