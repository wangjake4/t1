代发 wailian999

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shzxlz.cn/Article/details/gtuisnrqvh.html

[L04] 设置超时
来源：http://dali.zdqjudy.top/Article/details/gtyqxgeewp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yuanzhike.top/Article/details/gtenoacynb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlbpbqvte.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gogol.net.cn/Article/details/gttuebktci.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.316326.xyz/Article/details/gtukfuxdxb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yueranfly.top/Article/details/gtyczpwsgk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sufxvd.cn/Article/details/gtnpzpcrgq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nanxinkj.top/Article/details/gtbkhzwvqz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhoulong.xyz/Article/details/gtmeciwexh.html

[L05] 上传文件（multipart）
来源：http://dali.shuidangran.top/Article/details/gtnveryhdh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhengqikj.top/Article/details/gtacwsbdbp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sweek.top/Article/details/gtqwjgnfuo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhoulong.xyz/Article/details/gtbznbewtc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.kuanghao11.cn/Article/details/gtwtqhpmuy.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jiagoushi.top/Article/details/gthhgspusu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhengqikj.top/Article/details/gtbyribzde.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.kuanghao11.cn/Article/details/gtuilmflmc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtdubsqphz.html

[L06] 解析响应为 JSON
来源：http://dali.shuidangran.top/Article/details/gtlxgpwjqi.html

Py:   resp.json()
来源：http://dali.zdqjudy.top/Article/details/gtnbcqsomp.html

PHP:  json_decode($body, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcymmdhxx.html

JS:   await resp.json()
来源：http://dali.iojbl.cn/Article/details/gtkblijbsm.html

TS:   await resp.json()
来源：http://dali.gotoacloud.top/Article/details/gtglvfgqhf.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.aizwys.cn/Article/details/gtbaqehlgm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtixpvhhsl.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xziqi.cn/Article/details/gtzsgpxamm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.0kj1m.cn/Article/details/gtijbiilyw.html

[L07] 处理 HTTP 状态码
来源：http://dali.gaohongyu789.top/Article/details/gtrtwjtnzk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinghuilouyu.cn/Article/details/gtubwsymok.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yangfankeji.com/Article/details/gtmbmsrxft.html

JS:   resp.ok;  resp.status
来源：http://dali.zhiwuduotai.top/Article/details/gtcdpzutlo.html

TS:   resp.ok;  resp.status
来源：http://dali.yuxming.cn/Article/details/gtrzjcnmpb.html

Java: resp.statusCode()
来源：http://dali.quarkkingdee.top/Article/details/gtctrrdxvl.html

Go:   resp.StatusCode
来源：http://dali.tian-w.cn/Article/details/gtjsodgefk.html

Ruby: resp.code.to_i
来源：http://dali.jinghuilouyu.cn/Article/details/gtiomgnzno.html

C#:   (int)resp.StatusCode
来源：http://dali.chenjidiqi.icu/Article/details/gtjlefsimq.html

[L08] 并发请求多个地址
来源：http://dali.ehwqpu.com/Article/details/gtfrkebssz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yj20258888.top/Article/details/gtuoyjxzsn.html

PHP:  curl_multi_init() 系列
来源：http://dali.quarkkingdee.top/Article/details/gtofgepkul.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj202588.top/Article/details/gtqhgabfza.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daxiang520.top/Article/details/gtadolilph.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cashguo.top/Article/details/gtigkqdfvq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sufxvd.cn/Article/details/gtcltgttyj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.fengsongda.top/Article/details/gthzvtfzmq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xinyue.icu/Article/details/gtroshnokb.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtvlckvmdk.html

M. 命令行 / 进程 / 环境
来源：http://dali.svipenyu.cn/Article/details/gtsjwpcdgz.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtyzssiqss.html

[M01] 读取命令行参数
来源：http://dali.cucudq.cn/Article/details/gtgheijwia.html

Py:   sys.argv[1:]
来源：http://dali.ppjwa.cn/Article/details/gtqjnfteqp.html

PHP:  $argv;  $argc;
来源：http://dali.jinqigfzy.top/Article/details/gtjnifeivo.html

JS:   process.argv.slice(2)
来源：http://dali.meibo888.top/Article/details/gtvtjmzpgz.html

TS:   process.argv.slice(2)
来源：http://dali.bjfxy.top/Article/details/gtfseqrell.html

Java: args 数组（main 方法参数）
来源：http://dali.jlsjyb.cn/Article/details/gtarcsmjaj.html

Go:   os.Args[1:]
来源：http://dali.zhiwuduotai.top/Article/details/gtqsluezor.html

Ruby: ARGV
来源：http://dali.gotoacloud.top/Article/details/gtuptvpcla.html

C#:   args 数组（Main 方法参数）
来源：http://dali.feifeiyinyue.top/Article/details/gteaervcez.html

[M02] 读取环境变量
来源：http://dali.cqqwz.cn/Article/details/gtaqyvlvei.html

Py:   os.environ.get("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gtqbvujjkv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.iojbl.cn/Article/details/gtimjirzoc.html

JS:   process.env.HOME
来源：http://dali.gaohongyu789.top/Article/details/gtdyvftokp.html

TS:   process.env.HOME
来源：http://dali.xinyue.icu/Article/details/gttrehmxiu.html

Java: System.getenv("HOME")
来源：http://dali.snrcjt.cn/Article/details/gtpqqorjoe.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hnqzz.top/Article/details/gtwfyubvku.html

Ruby: ENV["HOME"]
来源：http://dali.kuanghao11.cn/Article/details/gtsictzaxt.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtlxmjjtbx.html

[M03] 执行外部命令
来源：http://dali.316326.xyz/Article/details/gtzkunglqs.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cheryme.top/Article/details/gtumhwwchq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.fengsongda.top/Article/details/gtpxyjjubu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.andypj.xyz/Article/details/gtyqxbwkdq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj202588.top/Article/details/gtfntdwdua.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zycfv.cn/Article/details/gtnmwvshvn.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nanxuanxn.top/Article/details/gtoqjbnclg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yongpay.top/Article/details/gtfpacwpiq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ydzc1.top/Article/details/gtwejryjeb.html

[M04] 获取当前工作目录
来源：http://dali.gaohongyu789.top/Article/details/gtmrlrhfdx.html

Py:   os.getcwd()
来源：http://dali.tian-w.cn/Article/details/gtqtedjquy.html

PHP:  getcwd();
来源：http://dali.havefunace.top/Article/details/gtowzylhgy.html

JS:   process.cwd()
来源：http://dali.chenjidiqi.icu/Article/details/gtwsdsbbqg.html

TS:   process.cwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtigmupeof.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.meibo888.top/Article/details/gtvdibvofb.html

Go:   os.Getwd()
来源：http://dali.redwolf501.top/Article/details/gthtqfoefz.html

Ruby: Dir.pwd
来源：http://dali.dianchejie.cn/Article/details/gtafkcqkgo.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtplauhlqy.html

[M05] 设置退出码
来源：http://dali.hywenlv.cn/Article/details/gtxgdyoean.html

Py:   sys.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gtrlmdwdxy.html

PHP:  exit(1);
来源：http://dali.jlsjyb.cn/Article/details/gtinmdnhed.html

JS:   process.exit(1)
来源：http://dali.jianghu66.top/Article/details/gtgdthnguz.html

TS:   process.exit(1)
来源：http://dali.bjfxy.top/Article/details/gtwewnsedk.html

Java: System.exit(1)
来源：http://dali.daxiang520.top/Article/details/gtouvtlbwj.html

Go:   os.Exit(1)
来源：http://dali.meibo888.top/Article/details/gtbehfujyq.html

Ruby: exit 1
来源：http://dali.chenlongwang.top/Article/details/gtnakfehua.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hnxiangtu.top/Article/details/gtbmstaiol.html

[M06] 向标准错误输出
来源：http://dali.yanxiufei.cn/Article/details/gtygibfhlz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hywenlv.cn/Article/details/gtlqlykogs.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvroggxtd.html

JS:   console.error("err")
来源：http://dali.jqgfzy.top/Article/details/gttlonwlzp.html

TS:   console.error("err")
来源：http://dali.gogol.net.cn/Article/details/gtciamtbhe.html

Java: System.err.println("err")
来源：http://dali.iojbl.cn/Article/details/gtmnvrzyvl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.pycfn.com/Article/details/gtgufriqtv.html

Ruby: warn "err"
来源：http://dali.nanxuanxn.top/Article/details/gtxjgbpzug.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.0kj1m.cn/Article/details/gtxcgksuua.html

[M07] 判断是否为主入口
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoanfaevy.html

Py:   if __name__ == "__main__":
来源：http://dali.haohaochexian.top/Article/details/gtwucemjhd.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.9152youxi.cn/Article/details/gtrntftdhy.html

JS:   require.main === module
来源：http://dali.cheryme.top/Article/details/gttmvytqfe.html

TS:   require.main === module
来源：http://dali.shangyingyoupin.top/Article/details/gtbssiysmu.html

Java: public static void main(String[] args)
来源：http://dali.ehwqpu.com/Article/details/gtvogjblop.html

Go:   func main()
来源：http://dali.zhengqikj.top/Article/details/gtkzrhnpri.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.aibaodan.cn/Article/details/gtsjaqbsud.html

C#:   static void Main(string[] args)
来源：http://dali.jiagoushi.top/Article/details/gtvwbapxhu.html

[M08] 获取系统与运行时信息
来源：http://dali.cqqwz.cn/Article/details/gtyqaysvjk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxhcyxhsc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jqgfzy.top/Article/details/gtunoqdslc.html

JS:   process.platform;  process.version
来源：http://dali.tian-w.cn/Article/details/gtkrylwoqc.html

TS:   process.platform;  process.version
来源：http://dali.gotoacloud.top/Article/details/gtcxgfujuf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ivvv.top/Article/details/gtljceqalk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhongyouzk.top/Article/details/gtjausyoqh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gogol.net.cn/Article/details/gtzntioavg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinghuilouyu.cn/Article/details/gtzwfelrcp.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtcutundrg.html

N. 数据结构与算法
来源：http://dali.zhengqikj.top/Article/details/gttqycyuod.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtcgytmvoa.html

[N01] 二分查找（有序数组）
来源：http://dali.xziqi.cn/Article/details/gteylsikhn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gtyyonedoi.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jlsjyb.cn/Article/details/gtukhsmqmw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigufen.top/Article/details/gtwaeeisfx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hywenlv.cn/Article/details/gtnjfmzgah.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtojgkaxoy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtlmtsuwnw.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ybcxt.top/Article/details/gtxzugswbz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtjxdsqsqn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sweek.top/Article/details/gtokencdzu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.meibo888.top/Article/details/gtnkmfqmjg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.daxiang520.top/Article/details/gttfzsifbz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zdqjudy.top/Article/details/gtsqgallry.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuxming.cn/Article/details/gtlslvqmrt.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzqltpimq.html

Go:   slices.Sort(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtzeughaqn.html

Ruby: arr.sort
来源：http://dali.havefunace.top/Article/details/gtpjjzvbhw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.andypj.xyz/Article/details/gtbtzdryip.html

[N03] 快速排序（分治示例）
来源：http://dali.yanxiufei.cn/Article/details/gtmplcybbl.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhixingplan.top/Article/details/gtcpyqbosb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.redwolf501.top/Article/details/gtlahcustv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxuanxn.top/Article/details/gthekadvdt.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guannengcc.top/Article/details/gtgpyhkpwi.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sxryk.cn/Article/details/gtivuonibk.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.9152youxi.cn/Article/details/gtygyaziei.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yj20258.top/Article/details/gtapqghzqa.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yj202588.top/Article/details/gtmunxygde.html

[N04] 斐波那契数列
来源：http://dali.cashguo.top/Article/details/gtlgalzqfu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gotoacloud.top/Article/details/gtyiicpzdc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.haohaochexian.top/Article/details/gtqcguwdbt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhoulong.xyz/Article/details/gtfhtcpemg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwlnwghxf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gogol.net.cn/Article/details/gtydfzbofk.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxqnvsleu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.meibo888.top/Article/details/gtopniwfax.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sweek.top/Article/details/gtfsiscmfv.html

[N05] 最大公约数
来源：http://dali.gaohongyu789.top/Article/details/gtiwwetrcx.html

Py:   math.gcd(a, b)
来源：http://dali.cqqwz.cn/Article/details/gtkkqaduyz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.fzhhl.top/Article/details/gtvfncyfhc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.iojbl.cn/Article/details/gtjvklnktj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yangfankeji.com/Article/details/gtibwzenju.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.birdmap.top/Article/details/gtdcuciryp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xziqi.cn/Article/details/gtderllpfe.html

Ruby: a.gcd(b)
来源：http://dali.nanxinkj.top/Article/details/gtygcjyvge.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hnxiangtu.top/Article/details/gtysupcisc.html

[N06] 判断回文字符串
来源：http://dali.yj20258.top/Article/details/gtcdtudqsj.html

Py:   s == s[::-1]
来源：http://dali.fengsongda.top/Article/details/gtjcwarcbq.html

PHP:  $s === strrev($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtjkwpfslo.html

JS:   s === [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gtfccmxbgz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.bjfxy.top/Article/details/gtrhpzkyum.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.nanxuanxn.top/Article/details/gtgoejapgx.html

Go:   // 双指针从两端比较
来源：http://dali.guowangkeji.top/Article/details/gtmmtaqomh.html

Ruby: s == s.reverse
来源：http://dali.mhx1999.top/Article/details/gteswhxoij.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.redwolf501.top/Article/details/gtyneuxhiu.html

[N07] 两数之和（返回下标）
来源：http://dali.daxiang520.top/Article/details/gtwatcsili.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ybcxt.top/Article/details/gtfxgskhut.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gaohongyu789.top/Article/details/gtzlomfcio.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sweek.top/Article/details/gtsczykzqh.html

TS:   // 手写 Map<string, number>
来源：http://dali.chenlongwang.top/Article/details/gthsjmttqo.html

Java: // 手写 HashMap
来源：http://dali.sxryk.cn/Article/details/gtgjtxfvxm.html

Go:   // 手写 map[int]int
来源：http://dali.hysaishi.cn/Article/details/gtztdbhilf.html

Ruby: // 手写 Hash
来源：http://dali.haohaochexian.top/Article/details/gtieyvoiee.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.daria6918.cn/Article/details/gtwyjvrumk.html

[N08] 生成全排列
来源：http://dali.feifeiyinyue.top/Article/details/gtyaxecsmn.html

Py:   itertools.permutations(arr)
来源：http://dali.iojbl.cn/Article/details/gtgszsmzjv.html

PHP:  // 手写递归交换
来源：http://dali.hnxiangtu.top/Article/details/gtwvxloebm.html

JS:   // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gtvqbzxmye.html

TS:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtqfyctenz.html

Java: // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtklqmahea.html

Go:   // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gtgejudxkz.html

Ruby: arr.permutation.to_a
来源：http://dali.jinghuilouyu.cn/Article/details/gtmsvwjbjq.html

C#:   // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gttuokshid.html

[N09] 栈与队列
来源：http://dali.ivvv.top/Article/details/gthqxduygx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hywenlv.cn/Article/details/gtoouznqta.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gtjftanxaz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jqgfzy.top/Article/details/gtlpybcypl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.iojbl.cn/Article/details/gtbugrcubs.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.haohaochexian.top/Article/details/gtadqpekhv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.9152youxi.cn/Article/details/gtlmclgcag.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gtopmsqwek.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hfpthk.cn/Article/details/gtqqlgfhnp.html

[N10] 链表节点定义
来源：http://dali.hfpthk.cn/Article/details/gtrczeogsp.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tanke756.top/Article/details/gtnxsxaxhk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jyoumei.cn/Article/details/gtqrzxmedv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yuanzhike.top/Article/details/gtscxwkfmf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.daxiang520.top/Article/details/gtedmrhmbu.html

Java: class Node { int v; Node next; }
来源：http://dali.zycfv.cn/Article/details/gtwxgowbix.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yonumen.top/Article/details/gtqguolghv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tianlin.xyz/Article/details/gtzgcgeuyt.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.vqdsnc.cn/Article/details/gtxamggcrl.html

[N11] 二叉树中序遍历
来源：http://dali.hammf.cn/Article/details/gtnurooiyp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.9152youxi.cn/Article/details/gtembwqhdb.html

PHP:  // 手写递归函数
来源：http://dali.ivvv.top/Article/details/gtgixriaqs.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cqqwz.cn/Article/details/gtpbaucahp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guannengcc.top/Article/details/gtehziqlxw.html

Java: // 手写递归
来源：http://dali.xinyue.icu/Article/details/gtxkpaegfy.html

Go:   // 手写递归
来源：http://dali.pycfn.com/Article/details/gtfrigzwyr.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hywenlv.cn/Article/details/gtauqwpysa.html

C#:   // 手写递归
来源：http://dali.mhx1999.top/Article/details/gtnirpzzbv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.svipenyu.cn/Article/details/gtyujjkjoh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.sxryk.cn/Article/details/gtlzinruzk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xinyue.icu/Article/details/gthpwvmnkm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.feifeiyinyue.top/Article/details/gtpgbmtzsk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cdnleiting.top/Article/details/gtngtwuhvg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fzhhl.top/Article/details/gttocnxism.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yongpay.top/Article/details/gtrggrwaar.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ydzc1.top/Article/details/gtvvsyzwqj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.andypj.xyz/Article/details/gtlllpsaor.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtlidadtmx.html

O. 并发与异步
来源：http://dali.jqgfzy.top/Article/details/gtoifwclpm.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtevdjwvoj.html

[O01] 启动一个线程
来源：http://dali.dianchejie.cn/Article/details/gtviajzyke.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.havefunace.top/Article/details/gtxgqndqpy.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jqgufenzy.top/Article/details/gtkuxgrjxa.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhixingplan.top/Article/details/gtzccywfhd.html

TS:   // 同 JS
来源：http://dali.nanxinkj.top/Article/details/gtvvwxciag.html

Java: new Thread(() -> f()).start()
来源：http://dali.shzxlz.cn/Article/details/gtfeohlwcg.html

Go:   go f()
来源：http://dali.zhiwuduotai.top/Article/details/gtsjyojnhi.html

Ruby: Thread.new { f }
来源：http://dali.ppjwa.cn/Article/details/gtamooiucz.html

C#:   Task.Run(() => F());
来源：http://dali.birdmap.top/Article/details/gtifurlrtk.html

[O02] 使用线程池
来源：http://dali.hysaishi.cn/Article/details/gtkqbytgxy.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cheryme.top/Article/details/gtjiuhusuc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.daria6918.cn/Article/details/gtqofsjfux.html

JS:   // worker_threads 线程池
来源：http://dali.zhengqikj.top/Article/details/gtwthljiik.html

TS:   // worker_threads 线程池
来源：http://dali.yuxming.cn/Article/details/gtkmwufdbq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ppjwa.cn/Article/details/gtaotgivwx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gaohongyu789.top/Article/details/gtvpbzyhyt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yvedp.cn/Article/details/gtqatpulta.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.wangdashe.top/Article/details/gtaaevupxd.html

[O03] 加锁保护共享数据
来源：http://dali.jinqigfzy.top/Article/details/gtwalrphqe.html

Py:   with lock: shared += 1
来源：http://dali.zdqjudy.top/Article/details/gttspmzlrc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jqgufenzy.top/Article/details/gttcuenluw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jqgfzy.top/Article/details/gtajgseycd.html

TS:   // 同 JS
来源：http://dali.jinqigfzy.top/Article/details/gtnwanwxbt.html

Java: synchronized (this) { shared++; }
来源：http://dali.gzhubu.top/Article/details/gtpwtzmyos.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcjawwtat.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yangfankeji.com/Article/details/gtxqdzrays.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhoulong.xyz/Article/details/gtbiiqwthv.html

[O04] 定义异步函数并等待
来源：http://dali.jlsjyb.cn/Article/details/gtcmadqbzh.html

Py:   async def f():⏎    await g()
来源：http://dali.fzhhl.top/Article/details/gtcgeyyjck.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfewkxsen.html

JS:   async function f() { await g(); }
来源：http://dali.birdmap.top/Article/details/gtrqbtdjac.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cheryme.top/Article/details/gtpyindbpm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhengqikj.top/Article/details/gtkpnjrkpo.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xinyue.icu/Article/details/gtwdwznels.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhoulong.xyz/Article/details/gtqzcqpatv.html

C#:   async Task F() { await G(); }
来源：http://dali.tian-w.cn/Article/details/gtxkpblqah.html

[O05] 并发执行并等待全部完成
来源：http://dali.yongpay.top/Article/details/gtxfecqnvh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yuxming.cn/Article/details/gtgpivivbu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.chenjidiqi.icu/Article/details/gtiedinalw.html

JS:   await Promise.all(tasks)
来源：http://dali.shzxlz.cn/Article/details/gttmnqigqv.html

TS:   await Promise.all(tasks)
来源：http://dali.sufxvd.cn/Article/details/gtviuystwy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shzxlz.cn/Article/details/gtkottdyhy.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xinyue.icu/Article/details/gtzwrmgicf.html

Ruby: threads.map(&:join)
来源：http://dali.yj20258.top/Article/details/gtfuskouiw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shzxlz.cn/Article/details/gttdhutpbw.html

[O06] 使用进程池
来源：http://dali.snrcjt.cn/Article/details/gtnzfhkrzw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.meibo888.top/Article/details/gtapdsypsb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.guowangkeji.top/Article/details/gtpoaoltxn.html

JS:   // child_process / cluster 模块
来源：http://dali.shzxlz.cn/Article/details/gtgwlnndha.html

TS:   // child_process / cluster 模块
来源：http://dali.sysykeji.top/Article/details/gtfdtcchdg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ydzc1.top/Article/details/gttbsdybxq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hnxiangtu.top/Article/details/gtwigzcnuh.html

Ruby: // fork 块
来源：http://dali.dashuyun.cn/Article/details/gtwgzrotfc.html

C#:   Parallel.For
来源：http://dali.gzhubu.top/Article/details/gteadgtgni.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gttxmxksio.html

P. 常用工具函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtiuvmogoo.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtymkshsuy.html

[P01] 生成 UUID
来源：http://dali.zhongyouzk.top/Article/details/gtiwpxwoyh.html

Py:   str(uuid.uuid4())
来源：http://dali.tianlin.xyz/Article/details/gtvqdlxvsb.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tianlin.xyz/Article/details/gtxodjlphz.html

JS:   crypto.randomUUID()
来源：http://dali.xuetiantiany.cn/Article/details/gtwpduuybd.html

TS:   crypto.randomUUID()
来源：http://dali.hnxiangtu.top/Article/details/gtzkhyhqpe.html

Java: UUID.randomUUID().toString()
来源：http://dali.yj20258888.top/Article/details/gtgljsoqem.html

Go:   // 用 github.com/google/uuid
来源：http://dali.mhx1999.top/Article/details/gtyvfsceua.html

Ruby: SecureRandom.uuid
来源：http://dali.shanyushiyangtech.top/Article/details/gtrhjtfyhj.html


<!-- 参考信息 -->