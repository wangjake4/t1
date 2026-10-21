代发 wailian999

[L03] 设置自定义请求头
来源：http://dali.kuanghao11.cn/Article/details/gtazdpueul.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yangfankeji.com/Article/details/gtdqnpozfc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.bjfxy.top/Article/details/gtsxzbwyyx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangkeji.top/Article/details/gttoqjgadn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.feifeiyinyue.top/Article/details/gttorkhlgo.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.9152youxi.cn/Article/details/gtvytwqxpe.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.tanke756.top/Article/details/gtfahnznrm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ivvv.top/Article/details/gtkhizuwow.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.feifeiyinyue.top/Article/details/gtqesmiwaq.html

[L04] 设置超时
来源：http://dali.zdqjudy.top/Article/details/gtqegmkcoz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.vqdsnc.cn/Article/details/gtofplzeot.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhoulong.xyz/Article/details/gtaphhcsmh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhiwuduotai.top/Article/details/gtwzboynuw.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhixingplan.top/Article/details/gtxjzhkhsw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinqigfzy.top/Article/details/gtqaoiwqsu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.guowangkeji.top/Article/details/gtzhegdaql.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yangfankeji.com/Article/details/gtsxnzelyq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xuetiantiany.cn/Article/details/gtriwbotpa.html

[L05] 上传文件（multipart）
来源：http://dali.yvedp.cn/Article/details/gtcbdwbqwz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.haohaochexian.top/Article/details/gtehyhtvuf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hammf.cn/Article/details/gtujazjpwu.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tianlin.xyz/Article/details/gtmavdnusv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cucudq.cn/Article/details/gtljavyfgw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.andypj.xyz/Article/details/gtaytlbuth.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.fzhhl.top/Article/details/gtnswnhsvu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.meibo888.top/Article/details/gtizojfeoc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtisyffxzy.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gtgxlesqkc.html

Py:   resp.json()
来源：http://dali.zhoulong.xyz/Article/details/gtazjsohxj.html

PHP:  json_decode($body, true);
来源：http://dali.jinqigufen.top/Article/details/gtueonabui.html

JS:   await resp.json()
来源：http://dali.yj20258.top/Article/details/gtukhtblhh.html

TS:   await resp.json()
来源：http://dali.jyoumei.cn/Article/details/gtvmkeqolv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jianghu66.top/Article/details/gtaxlvsxdt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yj20258888.top/Article/details/gtetuvbtjl.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jlsjyb.cn/Article/details/gteamesngq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ydzc1.top/Article/details/gtvjlfxqmq.html

[L07] 处理 HTTP 状态码
来源：http://dali.hywenlv.cn/Article/details/gtecqcpyqd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gogol.net.cn/Article/details/gtlkjrooay.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.feifeiyinyue.top/Article/details/gthljzpcnq.html

JS:   resp.ok;  resp.status
来源：http://dali.ydzc1.top/Article/details/gtvwgcxmpd.html

TS:   resp.ok;  resp.status
来源：http://dali.bjfxy.top/Article/details/gtobkgezfy.html

Java: resp.statusCode()
来源：http://dali.xziqi.cn/Article/details/gtvsywicku.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gtxpzjnqug.html

Ruby: resp.code.to_i
来源：http://dali.ywan-chungtsiang.top/Article/details/gthxvidcwa.html

C#:   (int)resp.StatusCode
来源：http://dali.cheryme.top/Article/details/gtvbxkkcmz.html

[L08] 并发请求多个地址
来源：http://dali.vqdsnc.cn/Article/details/gtjuxouqfq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhengqikj.top/Article/details/gtzjvnzcbj.html

PHP:  curl_multi_init() 系列
来源：http://dali.hnqzz.top/Article/details/gttbggwllx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuxming.cn/Article/details/gtptjbczyh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gzhubu.top/Article/details/gtyizqkqhs.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.dashuyun.cn/Article/details/gtlvqltmsn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.iojbl.cn/Article/details/gtgpitfenq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.9152youxi.cn/Article/details/gtrcwtvwdg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gotoacloud.top/Article/details/gtlcmfuude.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtiwvhwzkp.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenlongwang.top/Article/details/gtamrfhqre.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtvbcyifma.html

[M01] 读取命令行参数
来源：http://dali.jianghu66.top/Article/details/gtkwhgkgxa.html

Py:   sys.argv[1:]
来源：http://dali.wangshuangyany.cn/Article/details/gtlvldhnek.html

PHP:  $argv;  $argc;
来源：http://dali.snrcjt.cn/Article/details/gtccausklr.html

JS:   process.argv.slice(2)
来源：http://dali.meibo888.top/Article/details/gtbrehfsna.html

TS:   process.argv.slice(2)
来源：http://dali.andypj.xyz/Article/details/gtmcortqyu.html

Java: args 数组（main 方法参数）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcoyccvjx.html

Go:   os.Args[1:]
来源：http://dali.fzhhl.top/Article/details/gtferooops.html

Ruby: ARGV
来源：http://dali.yueranfly.top/Article/details/gtgcioojoi.html

C#:   args 数组（Main 方法参数）
来源：http://dali.snrcjt.cn/Article/details/gtstvcqtcm.html

[M02] 读取环境变量
来源：http://dali.redwolf501.top/Article/details/gtxyuxpxkm.html

Py:   os.environ.get("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzbwtrsba.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cheryme.top/Article/details/gtvuiouvnh.html

JS:   process.env.HOME
来源：http://dali.ydzc1.top/Article/details/gthynirfin.html

TS:   process.env.HOME
来源：http://dali.iojbl.cn/Article/details/gtzjzyutop.html

Java: System.getenv("HOME")
来源：http://dali.cashguo.top/Article/details/gtnccmxtsm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jqgfzy.top/Article/details/gtjxlqlcgp.html

Ruby: ENV["HOME"]
来源：http://dali.aizwys.cn/Article/details/gtyqvddllo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gtdrrphqtm.html

[M03] 执行外部命令
来源：http://dali.ehwqpu.com/Article/details/gtddxhoyhy.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ppjwa.cn/Article/details/gtevsrgwnz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sxryk.cn/Article/details/gtnakaezni.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hongshengwenyu.top/Article/details/gtvughfoqs.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigufen.top/Article/details/gtowacdezg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.andypj.xyz/Article/details/gthyuvdrow.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tianlin.xyz/Article/details/gtmtgxldjd.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.fengsongda.top/Article/details/gtojjjjckn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhengqikj.top/Article/details/gtockfwjap.html

[M04] 获取当前工作目录
来源：http://dali.gogol.net.cn/Article/details/gtmjwplvnb.html

Py:   os.getcwd()
来源：http://dali.guannengcc.top/Article/details/gtmarhwvah.html

PHP:  getcwd();
来源：http://dali.birdmap.top/Article/details/gtqwxgceol.html

JS:   process.cwd()
来源：http://dali.hongshengwenyu.top/Article/details/gtxjtjzdqr.html

TS:   process.cwd()
来源：http://dali.0kj1m.cn/Article/details/gteaxtmkis.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cheryme.top/Article/details/gtonuyltan.html

Go:   os.Getwd()
来源：http://dali.zycfv.cn/Article/details/gtdwensljl.html

Ruby: Dir.pwd
来源：http://dali.ybcxt.top/Article/details/gtghmujdqq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtffhklylj.html

[M05] 设置退出码
来源：http://dali.shzxlz.cn/Article/details/gtmpopsnpu.html

Py:   sys.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gtciolorub.html

PHP:  exit(1);
来源：http://dali.yueranfly.top/Article/details/gttjmsxorf.html

JS:   process.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtkubpmhyb.html

TS:   process.exit(1)
来源：http://dali.hammf.cn/Article/details/gtootdagyr.html

Java: System.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gtgkbvogfg.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtznofuhyh.html

Ruby: exit 1
来源：http://dali.hnxiangtu.top/Article/details/gtiyoorhee.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.meibo888.top/Article/details/gtdhwlftgu.html

[M06] 向标准错误输出
来源：http://dali.aibaodan.cn/Article/details/gtvsvjsmrg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.haohaochexian.top/Article/details/gtpvdnmxrf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jianghu66.top/Article/details/gttxmhtnwu.html

JS:   console.error("err")
来源：http://dali.redwolf501.top/Article/details/gtjcgiyuel.html

TS:   console.error("err")
来源：http://dali.316326.xyz/Article/details/gtyjltricj.html

Java: System.err.println("err")
来源：http://dali.xylfe.cn/Article/details/gthhsfwcni.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gogol.net.cn/Article/details/gtpjxdiued.html

Ruby: warn "err"
来源：http://dali.redwolf501.top/Article/details/gthyiyfkpf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tanke756.top/Article/details/gtsqdequcc.html

[M07] 判断是否为主入口
来源：http://dali.cqqwz.cn/Article/details/gtdrucstjn.html

Py:   if __name__ == "__main__":
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjbgkwtvi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.meibo888.top/Article/details/gtdwbfvkzk.html

JS:   require.main === module
来源：http://dali.sysykeji.top/Article/details/gtlatyqhsu.html

TS:   require.main === module
来源：http://dali.zhixingplan.top/Article/details/gtfkfcrbpq.html

Java: public static void main(String[] args)
来源：http://dali.hammf.cn/Article/details/gtqprnvfpd.html

Go:   func main()
来源：http://dali.zhoulong.xyz/Article/details/gtvkfgwdbz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.aizwys.cn/Article/details/gtzcdtgknb.html

C#:   static void Main(string[] args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwrvkrslp.html

[M08] 获取系统与运行时信息
来源：http://dali.xziqi.cn/Article/details/gtialithoe.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xinyue.icu/Article/details/gtikxwzzeu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jlsjyb.cn/Article/details/gtdclppssu.html

JS:   process.platform;  process.version
来源：http://dali.xziqi.cn/Article/details/gtfiebvscn.html

TS:   process.platform;  process.version
来源：http://dali.sysykeji.top/Article/details/gtoixmrbch.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnxiangtu.top/Article/details/gtilpjxmqn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.guowangkeji.top/Article/details/gtaezhmtqv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ybcxt.top/Article/details/gtchtiijef.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ivvv.top/Article/details/gtfgekbrnn.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtfssdfudv.html

N. 数据结构与算法
来源：http://dali.sysykeji.top/Article/details/gtiexrssbs.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtkakaackr.html

[N01] 二分查找（有序数组）
来源：http://dali.xziqi.cn/Article/details/gtisipuwob.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtsxsbhqfv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.andypj.xyz/Article/details/gtachxyjgp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yanxiufei.cn/Article/details/gtlymrynmu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zdqjudy.top/Article/details/gtuadxhpcm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtfkkboqvr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.havefunace.top/Article/details/gtcqkihtfn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cdnleiting.top/Article/details/gtcbwaetkd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtcvqvumvm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.feifeiyinyue.top/Article/details/gtdjtilcqm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.smart0.xyz/Article/details/gtffsjmnsv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yj20258888.top/Article/details/gtyakarcxe.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenlongwang.top/Article/details/gtnqrgsysp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jiagoushi.top/Article/details/gtecekldfm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xuetiantiany.cn/Article/details/gtzrhijaut.html

Go:   slices.Sort(arr)
来源：http://dali.yangfankeji.com/Article/details/gtrlommbsc.html

Ruby: arr.sort
来源：http://dali.birdmap.top/Article/details/gtaeiyoxxs.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xylfe.cn/Article/details/gtrnmjzhrz.html

[N03] 快速排序（分治示例）
来源：http://dali.guowangkeji.top/Article/details/gtqrpbzpte.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.tanke756.top/Article/details/gtbkusdxuv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.feifeiyinyue.top/Article/details/gtulocfkqf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hongshengwenyu.top/Article/details/gtpjlacjuh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shuidangran.top/Article/details/gtxpmhsvcy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.mhx1999.top/Article/details/gtewxonnbz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.fengsongda.top/Article/details/gtknwgrnch.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.fengsongda.top/Article/details/gtilzmxmqq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.daxiang520.top/Article/details/gtaavnfjse.html

[N04] 斐波那契数列
来源：http://dali.chenlongwang.top/Article/details/gtcxhtjnee.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.fengsongda.top/Article/details/gtxrtwenuh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj20258.top/Article/details/gtsuurpyag.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gtuhiwwnfi.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cashguo.top/Article/details/gtfpbduhek.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.chenlongwang.top/Article/details/gtaypbhmcy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hysaishi.cn/Article/details/gtiwvtxgzs.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xylfe.cn/Article/details/gtqbaruszl.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ppjwa.cn/Article/details/gtmebejdhu.html

[N05] 最大公约数
来源：http://dali.chenjidiqi.icu/Article/details/gtftflqvki.html

Py:   math.gcd(a, b)
来源：http://dali.tianlin.xyz/Article/details/gtchgwikaa.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hysaishi.cn/Article/details/gtlwuughac.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shuidangran.top/Article/details/gtmsmrawtd.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xinyue.icu/Article/details/gtzoixzvvs.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.wangshuangyany.cn/Article/details/gtmjkcvrgb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.316326.xyz/Article/details/gtuzletzvt.html

Ruby: a.gcd(b)
来源：http://dali.tanke756.top/Article/details/gtlhflsccd.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xinyue.icu/Article/details/gtvculytjz.html

[N06] 判断回文字符串
来源：http://dali.ybcxt.top/Article/details/gtpwgxtgja.html

Py:   s == s[::-1]
来源：http://dali.yvedp.cn/Article/details/gtkqvvdnvx.html

PHP:  $s === strrev($s);
来源：http://dali.havefunace.top/Article/details/gttflawmph.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gtidquvpfv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtgukdbysj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.aizwys.cn/Article/details/gtxxhjfslv.html

Go:   // 双指针从两端比较
来源：http://dali.tianlin.xyz/Article/details/gtwefnftyp.html

Ruby: s == s.reverse
来源：http://dali.9152youxi.cn/Article/details/gtkfvyfpya.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cashguo.top/Article/details/gtrugtwblv.html

[N07] 两数之和（返回下标）
来源：http://dali.xylfe.cn/Article/details/gtacitwofs.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yuxming.cn/Article/details/gthvsmaunv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.quarkkingdee.top/Article/details/gtblruobzd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yanxiufei.cn/Article/details/gtydkdxkmy.html

TS:   // 手写 Map<string, number>
来源：http://dali.shzxlz.cn/Article/details/gtyfguazow.html

Java: // 手写 HashMap
来源：http://dali.hnqzz.top/Article/details/gtqjlimezt.html

Go:   // 手写 map[int]int
来源：http://dali.daxiang520.top/Article/details/gttedmpqzu.html

Ruby: // 手写 Hash
来源：http://dali.gogol.net.cn/Article/details/gtfzddtcdc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.0kj1m.cn/Article/details/gtmbexhxua.html

[N08] 生成全排列
来源：http://dali.redwolf501.top/Article/details/gtbmofdxid.html

Py:   itertools.permutations(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtibqcithp.html

PHP:  // 手写递归交换
来源：http://dali.birdmap.top/Article/details/gtnyihzeoh.html

JS:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gtwsvdhjwl.html

TS:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gtmsfugrwi.html

Java: // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gtasucpkvy.html

Go:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gtbxoxalog.html

Ruby: arr.permutation.to_a
来源：http://dali.daria6918.cn/Article/details/gtcjejbjph.html

C#:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwclxlfxd.html

[N09] 栈与队列
来源：http://dali.chenjidiqi.icu/Article/details/gtmkrybllp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ydzc1.top/Article/details/gtzlmkefdp.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.quarkkingdee.top/Article/details/gtxnnidnmq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoeaxabrc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinqigfzy.top/Article/details/gtqmpeiflc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.dianchejie.cn/Article/details/gtpezomnjh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqnmgadur.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sufxvd.cn/Article/details/gtvnpviwlk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shuidangran.top/Article/details/gtxjxgpiip.html

[N10] 链表节点定义
来源：http://dali.zhoulong.xyz/Article/details/gtelnivplh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdmaoqqre.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.nanxinkj.top/Article/details/gtzbqynqsh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.wangshuangyany.cn/Article/details/gtnqdyyydd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.316326.xyz/Article/details/gtmnddnais.html

Java: class Node { int v; Node next; }
来源：http://dali.9152youxi.cn/Article/details/gtlxfenzfe.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.nwbrower.top/Article/details/gtahlzmtzy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yangfankeji.com/Article/details/gtvonyczqz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtadxqtouh.html

[N11] 二叉树中序遍历
来源：http://dali.daria6918.cn/Article/details/gtfpwfsyyz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.meibo888.top/Article/details/gtjktzfqnf.html

PHP:  // 手写递归函数
来源：http://dali.mhx1999.top/Article/details/gtnbitoxea.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sysykeji.top/Article/details/gtxwezjhzy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ivvv.top/Article/details/gtqkqlrixg.html

Java: // 手写递归
来源：http://dali.tanke756.top/Article/details/gtwaeghdyt.html

Go:   // 手写递归
来源：http://dali.hammf.cn/Article/details/gtqxhapmrq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.aibaodan.cn/Article/details/gtcrqcqxhc.html

C#:   // 手写递归
来源：http://dali.wangdashe.top/Article/details/gtqsrgebkc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yj202588.top/Article/details/gtohxcebkg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmfxxgsca.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shangyingyoupin.top/Article/details/gtmmrxmfgm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hnxiangtu.top/Article/details/gtizohebee.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.pengpengdd.cyou/Article/details/gtvtvvflbk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shangyingyoupin.top/Article/details/gtyjyrlaws.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.gaohongyu789.top/Article/details/gtcylfbbvp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sxryk.cn/Article/details/gtxnhlinmy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.316326.xyz/Article/details/gtrsliwnef.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtlhczogkl.html

O. 并发与异步
来源：http://dali.zhiwuduotai.top/Article/details/gtyzdjpjrl.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gticyalwmb.html

[O01] 启动一个线程
来源：http://dali.zhoulong.xyz/Article/details/gthzhdneem.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgodcfytq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.mhx1999.top/Article/details/gtwdmtehwb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.quarkkingdee.top/Article/details/gtegtuhyyi.html

TS:   // 同 JS
来源：http://dali.gotoacloud.top/Article/details/gtvfggcxnj.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinghuilouyu.cn/Article/details/gtbrihotda.html

Go:   go f()
来源：http://dali.guowangkeji.top/Article/details/gttkdembil.html

Ruby: Thread.new { f }
来源：http://dali.yj20258888.top/Article/details/gtllaydfjd.html

C#:   Task.Run(() => F());
来源：http://dali.tianlin.xyz/Article/details/gtthxpkrlg.html

[O02] 使用线程池
来源：http://dali.316326.xyz/Article/details/gtjwlofjcs.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gogol.net.cn/Article/details/gtjgwpjinh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinqigfzy.top/Article/details/gttsirpbmr.html

JS:   // worker_threads 线程池
来源：http://dali.cashguo.top/Article/details/gtncjjbziq.html

TS:   // worker_threads 线程池
来源：http://dali.tian-w.cn/Article/details/gtbkacbkqu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jiagoushi.top/Article/details/gtycdpnuoj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gotoacloud.top/Article/details/gtwqegntsj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cqqwz.cn/Article/details/gtanhaxfuz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jlsjyb.cn/Article/details/gtdlgrklmy.html

[O03] 加锁保护共享数据
来源：http://dali.shangyingyoupin.top/Article/details/gtfzjoocxe.html

Py:   with lock: shared += 1
来源：http://dali.redwolf501.top/Article/details/gttdlkvlwt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.bjfxy.top/Article/details/gtuomnuitx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ivvv.top/Article/details/gtbfwqbqwa.html

TS:   // 同 JS
来源：http://dali.9152youxi.cn/Article/details/gtxigcwbni.html

Java: synchronized (this) { shared++; }
来源：http://dali.jqgufenzy.top/Article/details/gtexrotcqc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gogol.net.cn/Article/details/gtkonejjbi.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.feifeiyinyue.top/Article/details/gtdhagqqfa.html

C#:   lock (gate) { shared++; }
来源：http://dali.hfpthk.cn/Article/details/gtkvisghhj.html

[O04] 定义异步函数并等待
来源：http://dali.redwolf501.top/Article/details/gtogqbjrnp.html

Py:   async def f():⏎    await g()
来源：http://dali.daxiang520.top/Article/details/gtgfdmgluw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ppjwa.cn/Article/details/gterzrxlww.html

JS:   async function f() { await g(); }
来源：http://dali.mhx1999.top/Article/details/gtgrjxjtln.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfprwcjph.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinqigufen.top/Article/details/gtdqbizanu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shzxlz.cn/Article/details/gtupedqwkl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xinyue.icu/Article/details/gtcsrmpqjq.html

C#:   async Task F() { await G(); }
来源：http://dali.ydzc1.top/Article/details/gtnjdjgdeq.html

[O05] 并发执行并等待全部完成
来源：http://dali.hywenlv.cn/Article/details/gtxzhvdiwi.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cashguo.top/Article/details/gtcicboknx.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.daria6918.cn/Article/details/gtbohbzaez.html

JS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlipzjdwa.html

TS:   await Promise.all(tasks)
来源：http://dali.ehwqpu.com/Article/details/gtjkqgoqet.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zycfv.cn/Article/details/gthsjjrlle.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sweek.top/Article/details/gtivqqjlhh.html

Ruby: threads.map(&:join)
来源：http://dali.xuanzx.com/Article/details/gthgsrjzsj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gzhubu.top/Article/details/gtwqgreevn.html

[O06] 使用进程池
来源：http://dali.daxiang520.top/Article/details/gthroazxna.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xylfe.cn/Article/details/gtikndokbf.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.meibo888.top/Article/details/gtermszrja.html

JS:   // child_process / cluster 模块
来源：http://dali.yj202588.top/Article/details/gtjptiyvrg.html

TS:   // child_process / cluster 模块
来源：http://dali.pycfn.com/Article/details/gtxtskmvqm.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jqgufenzy.top/Article/details/gtqucdaycj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.guowangkeji.top/Article/details/gtycjfvevm.html

Ruby: // fork 块
来源：http://dali.9152youxi.cn/Article/details/gtixgqgqaj.html

C#:   Parallel.For
来源：http://dali.sweek.top/Article/details/gtpemslufa.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtwixlsuvb.html

P. 常用工具函数
来源：http://dali.birdmap.top/Article/details/gtpitpyyww.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtiljwsvct.html


<!-- 参考信息 -->