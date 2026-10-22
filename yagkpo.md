代发 wailian999

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.316326.xyz/Article/details/gtousennmo.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.mhx1999.top/Article/details/gtovrczria.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.pengpengdd.cyou/Article/details/gtzwksuenq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zdqjudy.top/Article/details/gtvxfztbts.html

[L03] 设置自定义请求头
来源：http://dali.jianghu66.top/Article/details/gtgumahzwc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zycfv.cn/Article/details/gtfuucwkwb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cdnleiting.top/Article/details/gtpvgwyslx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenjidiqi.icu/Article/details/gtkmgcoczy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuxming.cn/Article/details/gtmsvwtuou.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cucudq.cn/Article/details/gtzkwhiuoj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cdnleiting.top/Article/details/gtbegsuxbo.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.mhx1999.top/Article/details/gtxrdebpfu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.tanke756.top/Article/details/gtwmdjhwjc.html

[L04] 设置超时
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaeldwixi.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthlvnfvsh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shangyingyoupin.top/Article/details/gtyrlpyzhs.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shzxlz.cn/Article/details/gtmnfbnbao.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.svipenyu.cn/Article/details/gtaieeegyv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shanyushiyangtech.top/Article/details/gtbnmnddtl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinghuilouyu.cn/Article/details/gtxzfatbhs.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jyoumei.cn/Article/details/gtjlcvcubo.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yonumen.top/Article/details/gtsvpxskav.html

[L05] 上传文件（multipart）
来源：http://dali.fzhhl.top/Article/details/gtltgylnmb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhiwuduotai.top/Article/details/gthyjmwess.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfvzwajua.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shzxlz.cn/Article/details/gtqyrgpqoa.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.c1oappe.top/Article/details/gtoldxzmvq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhoulong.xyz/Article/details/gtnyzxsycl.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xziqi.cn/Article/details/gtaivuqwmg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sweek.top/Article/details/gtfbtzxywn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtqzibkdtf.html

[L06] 解析响应为 JSON
来源：http://dali.jianghu66.top/Article/details/gtazzuzxkg.html

Py:   resp.json()
来源：http://dali.jianghu66.top/Article/details/gttyyjvihl.html

PHP:  json_decode($body, true);
来源：http://dali.zhoulong.xyz/Article/details/gtdsvoyktf.html

JS:   await resp.json()
来源：http://dali.shuidangran.top/Article/details/gtaujkmkvl.html

TS:   await resp.json()
来源：http://dali.hfpthk.cn/Article/details/gtronncixw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.kuanghao11.cn/Article/details/gtkpfsiqsz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.0kj1m.cn/Article/details/gtmsqeyxfd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj20258888.top/Article/details/gttnpxyuov.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jianghu66.top/Article/details/gttwejyexc.html

[L07] 处理 HTTP 状态码
来源：http://dali.xuetiantiany.cn/Article/details/gtsbyjjyiu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gzhubu.top/Article/details/gtqvrtwpjb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.vqdsnc.cn/Article/details/gtoglopfan.html

JS:   resp.ok;  resp.status
来源：http://dali.bjfxy.top/Article/details/gtyubgcygd.html

TS:   resp.ok;  resp.status
来源：http://dali.gaohongyu789.top/Article/details/gtaipgxtdn.html

Java: resp.statusCode()
来源：http://dali.meibo888.top/Article/details/gtsqfdvkug.html

Go:   resp.StatusCode
来源：http://dali.hysaishi.cn/Article/details/gtptadumko.html

Ruby: resp.code.to_i
来源：http://dali.feifeiyinyue.top/Article/details/gtzlznjonx.html

C#:   (int)resp.StatusCode
来源：http://dali.xuanzx.com/Article/details/gttfzksisc.html

[L08] 并发请求多个地址
来源：http://dali.jqgufenzy.top/Article/details/gtsjvwziex.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gotoacloud.top/Article/details/gtcnffpybd.html

PHP:  curl_multi_init() 系列
来源：http://dali.aibaodan.cn/Article/details/gttbwusojl.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gtsmxfopxm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cheryme.top/Article/details/gtsawbygoy.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.guannengcc.top/Article/details/gtndohfnim.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.guowangkeji.top/Article/details/gtdmpkjtxx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yj20258.top/Article/details/gtfdinwney.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yuanzhike.top/Article/details/gtbzfkycsu.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtodrdjpkf.html

M. 命令行 / 进程 / 环境
来源：http://dali.yj202588.top/Article/details/gtbythruvz.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtmprsaycl.html

[M01] 读取命令行参数
来源：http://dali.0kj1m.cn/Article/details/gtchvhzfnn.html

Py:   sys.argv[1:]
来源：http://dali.hnqzz.top/Article/details/gtzjmqbtce.html

PHP:  $argv;  $argc;
来源：http://dali.bjfxy.top/Article/details/gttssmcvpy.html

JS:   process.argv.slice(2)
来源：http://dali.pycfn.com/Article/details/gtltjqbajd.html

TS:   process.argv.slice(2)
来源：http://dali.jianghu66.top/Article/details/gtrmymifqb.html

Java: args 数组（main 方法参数）
来源：http://dali.ybcxt.top/Article/details/gtonthoefw.html

Go:   os.Args[1:]
来源：http://dali.dianchejie.cn/Article/details/gtnsbnqywf.html

Ruby: ARGV
来源：http://dali.zhixingplan.top/Article/details/gtcpdogtnr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sysykeji.top/Article/details/gtgrjjmufj.html

[M02] 读取环境变量
来源：http://dali.snrcjt.cn/Article/details/gtbgubztiy.html

Py:   os.environ.get("HOME")
来源：http://dali.aibaodan.cn/Article/details/gtdbzmnakv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xziqi.cn/Article/details/gtcsnzffls.html

JS:   process.env.HOME
来源：http://dali.dianchejie.cn/Article/details/gtgvtriyje.html

TS:   process.env.HOME
来源：http://dali.tian-w.cn/Article/details/gtcjbzbnth.html

Java: System.getenv("HOME")
来源：http://dali.jqgfzy.top/Article/details/gtnrwgizur.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yonumen.top/Article/details/gtafkuhews.html

Ruby: ENV["HOME"]
来源：http://dali.chenzaomai.com/Article/details/gtcudomuvr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhengqikj.top/Article/details/gtkeinzrtw.html

[M03] 执行外部命令
来源：http://dali.shanyushiyangtech.top/Article/details/gtfiwoolgb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ydzc1.top/Article/details/gtlquxelaa.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ehwqpu.com/Article/details/gtuxkpkrgg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gotoacloud.top/Article/details/gtkziyrqdp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgfzy.top/Article/details/gtzqaesnsx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sufxvd.cn/Article/details/gtbduylgve.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hywenlv.cn/Article/details/gtzmsguhxz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gogol.net.cn/Article/details/gtyjxrfpks.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ydzc1.top/Article/details/gtvwflprpx.html

[M04] 获取当前工作目录
来源：http://dali.gotoacloud.top/Article/details/gtxyzoegud.html

Py:   os.getcwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyfyeyvau.html

PHP:  getcwd();
来源：http://dali.gaohongyu789.top/Article/details/gtxstaudir.html

JS:   process.cwd()
来源：http://dali.sysykeji.top/Article/details/gthdbgckhx.html

TS:   process.cwd()
来源：http://dali.svipenyu.cn/Article/details/gtsjiujhzw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yanxiufei.cn/Article/details/gtmejtrmnp.html

Go:   os.Getwd()
来源：http://dali.yuanzhike.top/Article/details/gtscyyeczd.html

Ruby: Dir.pwd
来源：http://dali.chenzaomai.com/Article/details/gtdmzqhuqq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jqgufenzy.top/Article/details/gtroxtmjbz.html

[M05] 设置退出码
来源：http://dali.tianlin.xyz/Article/details/gthilriuor.html

Py:   sys.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gtbsoygeih.html

PHP:  exit(1);
来源：http://dali.hongshengwenyu.top/Article/details/gtqmvixbas.html

JS:   process.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtwyhnobph.html

TS:   process.exit(1)
来源：http://dali.ybcxt.top/Article/details/gtpvxpqwnj.html

Java: System.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtcewzmxtr.html

Go:   os.Exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtmyoaywdz.html

Ruby: exit 1
来源：http://dali.guannengcc.top/Article/details/gteyzltqzn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.smart0.xyz/Article/details/gtfsxeywvx.html

[M06] 向标准错误输出
来源：http://dali.gaohongyu789.top/Article/details/gtrrvhwfpi.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sysykeji.top/Article/details/gtnikzqssn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhoulong.xyz/Article/details/gthdvjfnzo.html

JS:   console.error("err")
来源：http://dali.0kj1m.cn/Article/details/gtxyiamsyl.html

TS:   console.error("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrthvrafz.html

Java: System.err.println("err")
来源：http://dali.yueranfly.top/Article/details/gtaimnytuh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.9152youxi.cn/Article/details/gtdmderqdn.html

Ruby: warn "err"
来源：http://dali.hammf.cn/Article/details/gtwrpzqkof.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.svipenyu.cn/Article/details/gtapnpwdwy.html

[M07] 判断是否为主入口
来源：http://dali.jianghu66.top/Article/details/gtdptzlqsd.html

Py:   if __name__ == "__main__":
来源：http://dali.hammf.cn/Article/details/gtxkooptmi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sxryk.cn/Article/details/gtugjxxnxy.html

JS:   require.main === module
来源：http://dali.feifeiyinyue.top/Article/details/gteoshdknp.html

TS:   require.main === module
来源：http://dali.hammf.cn/Article/details/gtyfncmogv.html

Java: public static void main(String[] args)
来源：http://dali.guowangkeji.top/Article/details/gtuthkslhr.html

Go:   func main()
来源：http://dali.yongpay.top/Article/details/gtbchhxrja.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sufxvd.cn/Article/details/gtotqirigp.html

C#:   static void Main(string[] args)
来源：http://dali.hnxiangtu.top/Article/details/gtvddvunyd.html

[M08] 获取系统与运行时信息
来源：http://dali.dianchejie.cn/Article/details/gtibsoqcda.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hywenlv.cn/Article/details/gtparoerdl.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.chenlongwang.top/Article/details/gtdepxymel.html

JS:   process.platform;  process.version
来源：http://dali.yueranfly.top/Article/details/gtawuvdhit.html

TS:   process.platform;  process.version
来源：http://dali.gotoacloud.top/Article/details/gtuzorqdtg.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.fzhhl.top/Article/details/gtuszkdiom.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hnqzz.top/Article/details/gtzkyknzvm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.vqdsnc.cn/Article/details/gtypmqxajn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinqigufen.top/Article/details/gtzfqhqxmx.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtycwcodmg.html

N. 数据结构与算法
来源：http://dali.xylfe.cn/Article/details/gtmmiaknsm.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtojzkqxig.html

[N01] 二分查找（有序数组）
来源：http://dali.jiagoushi.top/Article/details/gtwnttjjbu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtpuwvqusp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyyqxgtye.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbwozvwqg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guannengcc.top/Article/details/gtzoychbna.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.pycfn.com/Article/details/gtlqrliiyl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtxhooxmfn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.svipenyu.cn/Article/details/gtyzrpenxy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtcjxmielq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.wangshuangyany.cn/Article/details/gtspusjjzg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuanzx.com/Article/details/gtlbmphoaf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gtwqjfkbhp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtalfoegcw.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrruehjin.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.andypj.xyz/Article/details/gtwyeypuyg.html

Go:   slices.Sort(arr)
来源：http://dali.sxryk.cn/Article/details/gttqccwffi.html

Ruby: arr.sort
来源：http://dali.9152youxi.cn/Article/details/gtcwqljkuu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yuanzhike.top/Article/details/gteshomhbt.html

[N03] 快速排序（分治示例）
来源：http://dali.feifeiyinyue.top/Article/details/gtfttrxhdg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xuanzx.com/Article/details/gtejyxrljo.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinqigfzy.top/Article/details/gtcymdstml.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgfzy.top/Article/details/gtcassyjad.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.bjfxy.top/Article/details/gtlbnhnbnk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.tianlin.xyz/Article/details/gtcxmuowhn.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ydzc1.top/Article/details/gtzfzakhnw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtywgjqhwk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.svipenyu.cn/Article/details/gtzodxuwax.html

[N04] 斐波那契数列
来源：http://dali.tianlin.xyz/Article/details/gtkpzvsnpn.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.tian-w.cn/Article/details/gtnftrqnve.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.guannengcc.top/Article/details/gtjeczmtsb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pycfn.com/Article/details/gtgrzqjqys.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jyoumei.cn/Article/details/gtohqcqvnh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jqgufenzy.top/Article/details/gtskytllzl.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhongyouzk.top/Article/details/gtcxxdgbru.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cheryme.top/Article/details/gtrslqxbvv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cashguo.top/Article/details/gtxlvxwhtb.html

[N05] 最大公约数
来源：http://dali.cdnleiting.top/Article/details/gtofvmcttn.html

Py:   math.gcd(a, b)
来源：http://dali.zhiwuduotai.top/Article/details/gtceupbcec.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gogol.net.cn/Article/details/gtxcwnkdrj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.meibo888.top/Article/details/gtunytcmxj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guannengcc.top/Article/details/gtlsebfzne.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shzxlz.cn/Article/details/gtnloihjeu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xylfe.cn/Article/details/gtfqaibosi.html

Ruby: a.gcd(b)
来源：http://dali.jqgufenzy.top/Article/details/gtqhkdcfuc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.haohaochexian.top/Article/details/gtudhiaeib.html

[N06] 判断回文字符串
来源：http://dali.mhx1999.top/Article/details/gtzteygfip.html

Py:   s == s[::-1]
来源：http://dali.iojbl.cn/Article/details/gtmyeigrqz.html

PHP:  $s === strrev($s);
来源：http://dali.daria6918.cn/Article/details/gtkqiqjyzp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gtphpbtkzd.html

TS:   s === [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gtiaslrbzy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jqgufenzy.top/Article/details/gtpekrvgbx.html

Go:   // 双指针从两端比较
来源：http://dali.hongshengwenyu.top/Article/details/gtekdmarfd.html

Ruby: s == s.reverse
来源：http://dali.bjfxy.top/Article/details/gtafzbsamb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.kuanghao11.cn/Article/details/gtmfuterdi.html

[N07] 两数之和（返回下标）
来源：http://dali.quarkkingdee.top/Article/details/gtmibvfryx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xylfe.cn/Article/details/gticxjfudr.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ppjwa.cn/Article/details/gtavcprvbc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.quarkkingdee.top/Article/details/gtdeazadna.html

TS:   // 手写 Map<string, number>
来源：http://dali.c1oappe.top/Article/details/gtvzagoiba.html

Java: // 手写 HashMap
来源：http://dali.0kj1m.cn/Article/details/gtngivcata.html

Go:   // 手写 map[int]int
来源：http://dali.jyoumei.cn/Article/details/gtczcjkbfs.html

Ruby: // 手写 Hash
来源：http://dali.hfpthk.cn/Article/details/gtfbynwnhf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyvcahasr.html

[N08] 生成全排列
来源：http://dali.zycfv.cn/Article/details/gtwwonjlij.html

Py:   itertools.permutations(arr)
来源：http://dali.guannengcc.top/Article/details/gtmdymjyud.html

PHP:  // 手写递归交换
来源：http://dali.vqdsnc.cn/Article/details/gttsexootx.html

JS:   // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gtjxasyypr.html

TS:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtngasuqmy.html

Java: // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gtqfjjpyst.html

Go:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gtmjyawleq.html

Ruby: arr.permutation.to_a
来源：http://dali.shangyingyoupin.top/Article/details/gtuwpwldrl.html

C#:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gtglxmxkgj.html

[N09] 栈与队列
来源：http://dali.zhixingplan.top/Article/details/gtosacjqfy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.tianlin.xyz/Article/details/gtdkiqgatr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.daria6918.cn/Article/details/gtcmnxuted.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.pycfn.com/Article/details/gtglykibfg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.chenlongwang.top/Article/details/gtnyudsmwq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.wangdashe.top/Article/details/gtcsaluppe.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.9152youxi.cn/Article/details/gtemltakax.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yonumen.top/Article/details/gtwtucuntv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ydzc1.top/Article/details/gthisytmme.html

[N10] 链表节点定义
来源：http://dali.yuanzhike.top/Article/details/gtsmzbajkt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.havefunace.top/Article/details/gtymznzwry.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.smart0.xyz/Article/details/gtvcfilbif.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jqgfzy.top/Article/details/gtdvcwbugj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ehwqpu.com/Article/details/gtopjmyeox.html

Java: class Node { int v; Node next; }
来源：http://dali.yuxming.cn/Article/details/gtlzsjwnon.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.fzhhl.top/Article/details/gtbejohbrz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xziqi.cn/Article/details/gtmiiikspc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tanke756.top/Article/details/gtoyihaili.html

[N11] 二叉树中序遍历
来源：http://dali.jianghu66.top/Article/details/gtakxuywye.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhixingplan.top/Article/details/gtfbjabnpq.html

PHP:  // 手写递归函数
来源：http://dali.chenjidiqi.icu/Article/details/gtmsmuatgf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ehwqpu.com/Article/details/gtoeapaeii.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tanke756.top/Article/details/gtfnbymijz.html

Java: // 手写递归
来源：http://dali.sxryk.cn/Article/details/gtwjtksjpl.html

Go:   // 手写递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtmcjdmzrr.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.tian-w.cn/Article/details/gtfbirjlwg.html

C#:   // 手写递归
来源：http://dali.c1oappe.top/Article/details/gtveecgqxi.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.haohaochexian.top/Article/details/gtsdpixhcv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.chenlongwang.top/Article/details/gtfjafhqxg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yongpay.top/Article/details/gtmuljwxde.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tanke756.top/Article/details/gtefinxgwp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.bjfxy.top/Article/details/gtgvruxams.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.316326.xyz/Article/details/gtpkirvsse.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xuetiantiany.cn/Article/details/gttntlzifz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.wangdashe.top/Article/details/gtpgzcbusu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yvedp.cn/Article/details/gttansujmg.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gttyknoahp.html

O. 并发与异步
来源：http://dali.sufxvd.cn/Article/details/gttodxhqxr.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtobklmilr.html

[O01] 启动一个线程
来源：http://dali.hywenlv.cn/Article/details/gtulcplaqy.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhixingplan.top/Article/details/gtmymcqgws.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.guowangkeji.top/Article/details/gtmepsgjpc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cdnleiting.top/Article/details/gtgekqgjox.html

TS:   // 同 JS
来源：http://dali.dianchejie.cn/Article/details/gtzdduzqug.html

Java: new Thread(() -> f()).start()
来源：http://dali.sysykeji.top/Article/details/gtaqehtsxy.html

Go:   go f()
来源：http://dali.0kj1m.cn/Article/details/gtbarwnrzf.html

Ruby: Thread.new { f }
来源：http://dali.andypj.xyz/Article/details/gtnwojriex.html

C#:   Task.Run(() => F());
来源：http://dali.sxryk.cn/Article/details/gtcyemiusk.html

[O02] 使用线程池
来源：http://dali.yanxiufei.cn/Article/details/gtvvpgeknp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.birdmap.top/Article/details/gtkkqhswmj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hnqzz.top/Article/details/gtpfriyxjs.html

JS:   // worker_threads 线程池
来源：http://dali.nanxuanxn.top/Article/details/gtugcnrshd.html

TS:   // worker_threads 线程池
来源：http://dali.yj202588.top/Article/details/gtizwakjfx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.aizwys.cn/Article/details/gtyhqsnpvl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hongshengwenyu.top/Article/details/gtidntqdzi.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.tian-w.cn/Article/details/gtqhppqvut.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.tanke756.top/Article/details/gtnmktiqth.html

[O03] 加锁保护共享数据
来源：http://dali.yanxiufei.cn/Article/details/gtesakrvvo.html

Py:   with lock: shared += 1
来源：http://dali.xinyue.icu/Article/details/gtbcvrqifw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhongyouzk.top/Article/details/gtcvjsixgm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.tian-w.cn/Article/details/gtueidujxm.html

TS:   // 同 JS
来源：http://dali.shanyushiyangtech.top/Article/details/gtohuhvikn.html

Java: synchronized (this) { shared++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtckpjopot.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shanyushiyangtech.top/Article/details/gtbbmkgphn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ivvv.top/Article/details/gthodvvexa.html

C#:   lock (gate) { shared++; }
来源：http://dali.yongpay.top/Article/details/gtgvlnvlei.html

[O04] 定义异步函数并等待
来源：http://dali.sxryk.cn/Article/details/gtuysgpxfh.html

Py:   async def f():⏎    await g()
来源：http://dali.sweek.top/Article/details/gtkablgujc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hammf.cn/Article/details/gtrmezczox.html

JS:   async function f() { await g(); }
来源：http://dali.dashuyun.cn/Article/details/gtanmwpare.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenzaomai.com/Article/details/gtwrgkpccr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.316326.xyz/Article/details/gtpbrzyvno.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ivvv.top/Article/details/gtbcgvnxrs.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.feifeiyinyue.top/Article/details/gtoicuizus.html

C#:   async Task F() { await G(); }
来源：http://dali.guannengcc.top/Article/details/gtzqoojygs.html

[O05] 并发执行并等待全部完成
来源：http://dali.gotoacloud.top/Article/details/gtukeexoxs.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yonumen.top/Article/details/gtiijtiuae.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jlsjyb.cn/Article/details/gtsvfgvacl.html

JS:   await Promise.all(tasks)
来源：http://dali.tianlin.xyz/Article/details/gtjawwqzwa.html

TS:   await Promise.all(tasks)
来源：http://dali.yueranfly.top/Article/details/gtcezubpiy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.havefunace.top/Article/details/gtgimgowum.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cheryme.top/Article/details/gtmewnvmby.html

Ruby: threads.map(&:join)
来源：http://dali.gaohongyu789.top/Article/details/gttucxxgpp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.316326.xyz/Article/details/gtwrwdkxaw.html

[O06] 使用进程池
来源：http://dali.cheryme.top/Article/details/gtjblnrxbq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthazoimao.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shangyingyoupin.top/Article/details/gtrdvcjufl.html

JS:   // child_process / cluster 模块
来源：http://dali.hysaishi.cn/Article/details/gteelgneap.html

TS:   // child_process / cluster 模块
来源：http://dali.gogol.net.cn/Article/details/gtquptymfq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhengqikj.top/Article/details/gtnonzgfmk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jinqigufen.top/Article/details/gtfwdkeanb.html

Ruby: // fork 块
来源：http://dali.fengsongda.top/Article/details/gtxwhkqgwy.html


<!-- 参考信息 -->