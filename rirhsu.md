代发 wailian999

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.aizwys.cn/Article/details/gtxuzoepjq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yueranfly.top/Article/details/gtyojrjnio.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yuanzhike.top/Article/details/gtugbmgeuq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cqqwz.cn/Article/details/gtjqvdlyks.html

[L03] 设置自定义请求头
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuqjljapr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjkqgqnzm.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.nanxinkj.top/Article/details/gthispkxsg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gogol.net.cn/Article/details/gtsowdswsa.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuetiantiany.cn/Article/details/gtbrvacglk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ivvv.top/Article/details/gtulxaytpr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzqcjkrpd.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shuidangran.top/Article/details/gtxbekjndq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinqigufen.top/Article/details/gtmbbudxqg.html

[L04] 设置超时
来源：http://dali.yj202588.top/Article/details/gtzisozcuh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.fzhhl.top/Article/details/gtnbtemmdv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gtubtdvtzo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sufxvd.cn/Article/details/gtlcojgbog.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gzhubu.top/Article/details/gtxzahteqf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yj20258888.top/Article/details/gtifhlejhc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyegzozli.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.feifeiyinyue.top/Article/details/gtjkzvvhls.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.dashuyun.cn/Article/details/gtoracwvrr.html

[L05] 上传文件（multipart）
来源：http://dali.guowangkeji.top/Article/details/gtsxzzlydb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenlongwang.top/Article/details/gtuijbassz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.iojbl.cn/Article/details/gtttxfgnkl.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hfpthk.cn/Article/details/gtrpgpzkvl.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shzxlz.cn/Article/details/gtekgnlxzm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yj20258888.top/Article/details/gtacgracvz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yonumen.top/Article/details/gtguljfnou.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hywenlv.cn/Article/details/gtqorgpnxp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtwocogqts.html

[L06] 解析响应为 JSON
来源：http://dali.hnxiangtu.top/Article/details/gttgubtyqp.html

Py:   resp.json()
来源：http://dali.c1oappe.top/Article/details/gtfqylihzc.html

PHP:  json_decode($body, true);
来源：http://dali.hnqzz.top/Article/details/gthamcdflu.html

JS:   await resp.json()
来源：http://dali.yj20258.top/Article/details/gtavcxnujx.html

TS:   await resp.json()
来源：http://dali.wangdashe.top/Article/details/gtyvogjlda.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinqigufen.top/Article/details/gtjjsrtncu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yuanzhike.top/Article/details/gtsqcefhgf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yongpay.top/Article/details/gtfslzpwdq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gaohongyu789.top/Article/details/gtojoygavd.html

[L07] 处理 HTTP 状态码
来源：http://dali.shangyingyoupin.top/Article/details/gtzftgbkhr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.chenlongwang.top/Article/details/gtigogecyg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yuanzhike.top/Article/details/gtikzgmvuf.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gtsbgeezpv.html

TS:   resp.ok;  resp.status
来源：http://dali.ppjwa.cn/Article/details/gterddsxlr.html

Java: resp.statusCode()
来源：http://dali.0kj1m.cn/Article/details/gtflmvajrx.html

Go:   resp.StatusCode
来源：http://dali.chenzaomai.com/Article/details/gtoufnjjyx.html

Ruby: resp.code.to_i
来源：http://dali.bjfxy.top/Article/details/gtrgsfhofq.html

C#:   (int)resp.StatusCode
来源：http://dali.aizwys.cn/Article/details/gtjvydibjs.html

[L08] 并发请求多个地址
来源：http://dali.andypj.xyz/Article/details/gtucskdcsq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.bjfxy.top/Article/details/gtglppkwbi.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gtnrhscgqs.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkkkswwss.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gtqwxpsbia.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ybcxt.top/Article/details/gtuzloycok.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yonumen.top/Article/details/gtlzjnipzv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.iojbl.cn/Article/details/gtizsymdhw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gteyuzoodw.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtzblfuqiv.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvrwnunpf.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtrguxlelb.html

[M01] 读取命令行参数
来源：http://dali.316326.xyz/Article/details/gtxvvntcaw.html

Py:   sys.argv[1:]
来源：http://dali.jianghu66.top/Article/details/gtpxliwkkk.html

PHP:  $argv;  $argc;
来源：http://dali.svipenyu.cn/Article/details/gtguwxivro.html

JS:   process.argv.slice(2)
来源：http://dali.feifeiyinyue.top/Article/details/gtwyemoxnz.html

TS:   process.argv.slice(2)
来源：http://dali.yuanzhike.top/Article/details/gtcyvfwyvr.html

Java: args 数组（main 方法参数）
来源：http://dali.yangfankeji.com/Article/details/gtnvmptwlq.html

Go:   os.Args[1:]
来源：http://dali.cashguo.top/Article/details/gtfylffhxk.html

Ruby: ARGV
来源：http://dali.cucudq.cn/Article/details/gtbygdxfih.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yangfankeji.com/Article/details/gtevlssjmj.html

[M02] 读取环境变量
来源：http://dali.daria6918.cn/Article/details/gtzmqwhatm.html

Py:   os.environ.get("HOME")
来源：http://dali.mhx1999.top/Article/details/gtqbdxusza.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yongpay.top/Article/details/gtamxeiwxo.html

JS:   process.env.HOME
来源：http://dali.jinqigfzy.top/Article/details/gtvewqpbeu.html

TS:   process.env.HOME
来源：http://dali.vqdsnc.cn/Article/details/gtokwdptbq.html

Java: System.getenv("HOME")
来源：http://dali.xuanzx.com/Article/details/gtgavmrhxm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.tanke756.top/Article/details/gtzqpjnbow.html

Ruby: ENV["HOME"]
来源：http://dali.cqqwz.cn/Article/details/gtsjvxugdx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gtsijdesiu.html

[M03] 执行外部命令
来源：http://dali.cucudq.cn/Article/details/gtfdzdpqjo.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jianghu66.top/Article/details/gtjralngso.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.316326.xyz/Article/details/gtjbzqdcar.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.fzhhl.top/Article/details/gtakgmqkpf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.daxiang520.top/Article/details/gtegavxpej.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.birdmap.top/Article/details/gtslcjsakz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shanyushiyangtech.top/Article/details/gtynkcszpx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yuanzhike.top/Article/details/gthyrriazw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxcmwxvht.html

[M04] 获取当前工作目录
来源：http://dali.zhongyouzk.top/Article/details/gtjrflucqm.html

Py:   os.getcwd()
来源：http://dali.yonumen.top/Article/details/gtzaftjiya.html

PHP:  getcwd();
来源：http://dali.0kj1m.cn/Article/details/gtzihwdqay.html

JS:   process.cwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gttiaupbos.html

TS:   process.cwd()
来源：http://dali.guowangkeji.top/Article/details/gtdwfmxyeg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhoulong.xyz/Article/details/gtnklzlvnn.html

Go:   os.Getwd()
来源：http://dali.svipenyu.cn/Article/details/gtauechjxm.html

Ruby: Dir.pwd
来源：http://dali.havefunace.top/Article/details/gtzbyzckor.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sufxvd.cn/Article/details/gteazxuumb.html

[M05] 设置退出码
来源：http://dali.haohaochexian.top/Article/details/gtvgemlghp.html

Py:   sys.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtdyoezrtq.html

PHP:  exit(1);
来源：http://dali.cucudq.cn/Article/details/gtpyxzhfjy.html

JS:   process.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gtdszcgkxy.html

TS:   process.exit(1)
来源：http://dali.gzhubu.top/Article/details/gtqutelzgd.html

Java: System.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrdzovqyo.html

Go:   os.Exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtkigedyef.html

Ruby: exit 1
来源：http://dali.yvedp.cn/Article/details/gtmxqqqulp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ivvv.top/Article/details/gtsididoqw.html

[M06] 向标准错误输出
来源：http://dali.shanyushiyangtech.top/Article/details/gtivwkqkuf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gtfkjvmpou.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.chenlongwang.top/Article/details/gtsrddkkfd.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gtjlzpickf.html

TS:   console.error("err")
来源：http://dali.jianghu66.top/Article/details/gtacqtbvab.html

Java: System.err.println("err")
来源：http://dali.xuetiantiany.cn/Article/details/gtycqvwuai.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.daria6918.cn/Article/details/gtymgcudef.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gtnseewurs.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.daxiang520.top/Article/details/gtxhwxgdyg.html

[M07] 判断是否为主入口
来源：http://dali.cashguo.top/Article/details/gtneasaeyp.html

Py:   if __name__ == "__main__":
来源：http://dali.daxiang520.top/Article/details/gtqkirqqtz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zycfv.cn/Article/details/gtjumycytu.html

JS:   require.main === module
来源：http://dali.hfpthk.cn/Article/details/gtmrjzmtqe.html

TS:   require.main === module
来源：http://dali.guowangkeji.top/Article/details/gtjcftpywl.html

Java: public static void main(String[] args)
来源：http://dali.yuanzhike.top/Article/details/gtfxrsokdk.html

Go:   func main()
来源：http://dali.xinyue.icu/Article/details/gtylhepkfc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinqigufen.top/Article/details/gtyxolzctf.html

C#:   static void Main(string[] args)
来源：http://dali.nanxinkj.top/Article/details/gticmlfyfc.html

[M08] 获取系统与运行时信息
来源：http://dali.hfpthk.cn/Article/details/gtnmvachpd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yangfankeji.com/Article/details/gtkcznvbrz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.bjfxy.top/Article/details/gtnygpizpk.html

JS:   process.platform;  process.version
来源：http://dali.xylfe.cn/Article/details/gtjjbitxvx.html

TS:   process.platform;  process.version
来源：http://dali.meibo888.top/Article/details/gtptpnjmev.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xuetiantiany.cn/Article/details/gtimlnjdtf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yueranfly.top/Article/details/gtrrsoobty.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xylfe.cn/Article/details/gtbyravlbe.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hnqzz.top/Article/details/gtubaodqej.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtbnmgtmva.html

N. 数据结构与算法
来源：http://dali.jqgfzy.top/Article/details/gthmzocokw.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtisgefhcl.html

[N01] 二分查找（有序数组）
来源：http://dali.yueranfly.top/Article/details/gtbphdxvzy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sweek.top/Article/details/gtbxwvkfzd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrcbmvlsa.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sxryk.cn/Article/details/gtimdhlsik.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yongpay.top/Article/details/gtexkmsmxi.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtvteiyiih.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtjmzbwkli.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhoulong.xyz/Article/details/gtfyuaiubm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtrbfrpemf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.fengsongda.top/Article/details/gtxbdcmsck.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.feifeiyinyue.top/Article/details/gtezjllhks.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xziqi.cn/Article/details/gtmbdzvhgv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangshuangyany.cn/Article/details/gtnuvkdfnn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxinkj.top/Article/details/gtivbunbss.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sweek.top/Article/details/gtixcsaows.html

Go:   slices.Sort(arr)
来源：http://dali.yj20258888.top/Article/details/gtkryeesqg.html

Ruby: arr.sort
来源：http://dali.havefunace.top/Article/details/gtalnoxaer.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.pengpengdd.cyou/Article/details/gtbmhzdxes.html

[N03] 快速排序（分治示例）
来源：http://dali.gotoacloud.top/Article/details/gtwcdxjbta.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.kuanghao11.cn/Article/details/gtdfdyngod.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tianlin.xyz/Article/details/gtmyniewmv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangdashe.top/Article/details/gtnyyzkhny.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtevzsplbg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.quarkkingdee.top/Article/details/gtcbvssknb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.quarkkingdee.top/Article/details/gtoisqhbqm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.dashuyun.cn/Article/details/gthigtrsaf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yongpay.top/Article/details/gtrbbipbho.html

[N04] 斐波那契数列
来源：http://dali.iojbl.cn/Article/details/gtkpmykubf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zycfv.cn/Article/details/gtfymspliy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.c1oappe.top/Article/details/gtcwsyxxbl.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ppjwa.cn/Article/details/gtlozcvowl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hammf.cn/Article/details/gtikaftcbv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.svipenyu.cn/Article/details/gtjiyvvkva.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cashguo.top/Article/details/gtzhekeeer.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jqgufenzy.top/Article/details/gtwzvzzyxr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtomsbqvif.html

[N05] 最大公约数
来源：http://dali.gzhubu.top/Article/details/gtgvbqmqzq.html

Py:   math.gcd(a, b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyogqfwxg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.guannengcc.top/Article/details/gtcvqhdlow.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jiagoushi.top/Article/details/gtfvysxrof.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhiwuduotai.top/Article/details/gtqjvdwmzf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.svipenyu.cn/Article/details/gtnarbavon.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.birdmap.top/Article/details/gtjjdvzmfo.html

Ruby: a.gcd(b)
来源：http://dali.haohaochexian.top/Article/details/gttjucordx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.andypj.xyz/Article/details/gtduiovnsa.html

[N06] 判断回文字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtphuuvnim.html

Py:   s == s[::-1]
来源：http://dali.fzhhl.top/Article/details/gtsymsjaeq.html

PHP:  $s === strrev($s);
来源：http://dali.zhoulong.xyz/Article/details/gttpvjxetr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gtjaxfvvkq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gteevngcsl.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.vqdsnc.cn/Article/details/gtfimyjzor.html

Go:   // 双指针从两端比较
来源：http://dali.ydzc1.top/Article/details/gtmofsiuni.html

Ruby: s == s.reverse
来源：http://dali.jinqigfzy.top/Article/details/gtolstzrmp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yuanzhike.top/Article/details/gtqmvvviqt.html

[N07] 两数之和（返回下标）
来源：http://dali.zhoulong.xyz/Article/details/gtawfpcpwp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.0kj1m.cn/Article/details/gtufubqkzu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xinyue.icu/Article/details/gtffykffqe.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.meibo888.top/Article/details/gtzxyrvaoo.html

TS:   // 手写 Map<string, number>
来源：http://dali.mhx1999.top/Article/details/gtuzuvwtvv.html

Java: // 手写 HashMap
来源：http://dali.jqgfzy.top/Article/details/gtxxevzloj.html

Go:   // 手写 map[int]int
来源：http://dali.316326.xyz/Article/details/gtziilqklh.html

Ruby: // 手写 Hash
来源：http://dali.wangshuangyany.cn/Article/details/gtanrwotdh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.chenlongwang.top/Article/details/gtozsycjqi.html

[N08] 生成全排列
来源：http://dali.sweek.top/Article/details/gtqqldadal.html

Py:   itertools.permutations(arr)
来源：http://dali.cheryme.top/Article/details/gtnvkcrcaq.html

PHP:  // 手写递归交换
来源：http://dali.zdqjudy.top/Article/details/gttsiwqfyl.html

JS:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtjkizsisx.html

TS:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtzqqclkcd.html

Java: // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gtzuiztyej.html

Go:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gtvbaicyqi.html

Ruby: arr.permutation.to_a
来源：http://dali.cashguo.top/Article/details/gtfritiags.html

C#:   // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gtdmlytxzh.html

[N09] 栈与队列
来源：http://dali.quarkkingdee.top/Article/details/gtfswobnpq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.birdmap.top/Article/details/gtwfleflxf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gaohongyu789.top/Article/details/gtknwuaxol.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhoulong.xyz/Article/details/gtwqhvidch.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shzxlz.cn/Article/details/gtgsesxrqe.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.meibo888.top/Article/details/gtxrrmvayp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sufxvd.cn/Article/details/gtzgfjpeqf.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jianghu66.top/Article/details/gtikhxcexd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jlsjyb.cn/Article/details/gtszbjffpx.html

[N10] 链表节点定义
来源：http://dali.guannengcc.top/Article/details/gtjtgdmpss.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.meibo888.top/Article/details/gtyivuakvq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jianghu66.top/Article/details/gtqvogkblx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hnxiangtu.top/Article/details/gtjmfyefno.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhiwuduotai.top/Article/details/gtbemftrmp.html

Java: class Node { int v; Node next; }
来源：http://dali.havefunace.top/Article/details/gtjhjlmicf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ydzc1.top/Article/details/gtwecoskwn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jqgufenzy.top/Article/details/gtglhseplt.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jiagoushi.top/Article/details/gtgynslojc.html

[N11] 二叉树中序遍历
来源：http://dali.nanxuanxn.top/Article/details/gtnblcawbz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjxrjfzgn.html

PHP:  // 手写递归函数
来源：http://dali.zhoulong.xyz/Article/details/gtxwzdvyif.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.feifeiyinyue.top/Article/details/gttocjtosd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.quarkkingdee.top/Article/details/gtmaylzgkq.html

Java: // 手写递归
来源：http://dali.daxiang520.top/Article/details/gtlwntxvgy.html

Go:   // 手写递归
来源：http://dali.havefunace.top/Article/details/gtxkzyvump.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.wangshuangyany.cn/Article/details/gtrqjvdmix.html

C#:   // 手写递归
来源：http://dali.smart0.xyz/Article/details/gtoeyhohqs.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yueranfly.top/Article/details/gthxiaihtw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.chenlongwang.top/Article/details/gtzocxlaci.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.wangdashe.top/Article/details/gtnjhefsfs.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.smart0.xyz/Article/details/gtjgrqzllr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.redwolf501.top/Article/details/gtvmuldtec.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cqqwz.cn/Article/details/gtdrwxaezu.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgoaltulf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jlsjyb.cn/Article/details/gtvwkgdxiy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nanxinkj.top/Article/details/gtflbnovcv.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtjxsqhlcb.html

O. 并发与异步
来源：http://dali.shzxlz.cn/Article/details/gtkltrgeue.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtptfndaao.html

[O01] 启动一个线程
来源：http://dali.hammf.cn/Article/details/gtttywmebd.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jqgufenzy.top/Article/details/gtziwhhhrd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhengqikj.top/Article/details/gtgxlueoht.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.andypj.xyz/Article/details/gtdmmwkzvv.html

TS:   // 同 JS
来源：http://dali.ehwqpu.com/Article/details/gtmehbwroh.html

Java: new Thread(() -> f()).start()
来源：http://dali.feifeiyinyue.top/Article/details/gtsjsrclbw.html

Go:   go f()
来源：http://dali.chenjidiqi.icu/Article/details/gtxwrtgvqt.html

Ruby: Thread.new { f }
来源：http://dali.redwolf501.top/Article/details/gtlgtpwygj.html

C#:   Task.Run(() => F());
来源：http://dali.jqgfzy.top/Article/details/gtytqjhrco.html

[O02] 使用线程池
来源：http://dali.nanxinkj.top/Article/details/gthoctxaax.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hongshengwenyu.top/Article/details/gtlblhawsd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ivvv.top/Article/details/gtedntczko.html

JS:   // worker_threads 线程池
来源：http://dali.pycfn.com/Article/details/gtffwoyiau.html

TS:   // worker_threads 线程池
来源：http://dali.sweek.top/Article/details/gtnqysiwnl.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.haohaochexian.top/Article/details/gtscrjjwii.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.nanxuanxn.top/Article/details/gtvdgsuxvs.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.tian-w.cn/Article/details/gtjrjejbts.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gotoacloud.top/Article/details/gttszwqxxq.html

[O03] 加锁保护共享数据
来源：http://dali.yj202588.top/Article/details/gtqqbsbmzd.html

Py:   with lock: shared += 1
来源：http://dali.daria6918.cn/Article/details/gtewrplyxq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yueranfly.top/Article/details/gtzxsaejow.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shanyushiyangtech.top/Article/details/gtrkshjgbs.html

TS:   // 同 JS
来源：http://dali.316326.xyz/Article/details/gtchzjoqhx.html

Java: synchronized (this) { shared++; }
来源：http://dali.yueranfly.top/Article/details/gtriafmnvz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hysaishi.cn/Article/details/gtsfzwzooh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hammf.cn/Article/details/gtfuzwsocg.html

C#:   lock (gate) { shared++; }
来源：http://dali.cqqwz.cn/Article/details/gtdbbzhvks.html

[O04] 定义异步函数并等待
来源：http://dali.pengpengdd.cyou/Article/details/gtwnbynfgr.html

Py:   async def f():⏎    await g()
来源：http://dali.daxiang520.top/Article/details/gtcplpcicn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hongshengwenyu.top/Article/details/gtgnvfeztl.html

JS:   async function f() { await g(); }
来源：http://dali.yangfankeji.com/Article/details/gtinszkwwq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.0kj1m.cn/Article/details/gtfngvoolv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.bjfxy.top/Article/details/gtcekcnurp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.kuanghao11.cn/Article/details/gtkupsbdjv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yangfankeji.com/Article/details/gtffibtvzt.html

C#:   async Task F() { await G(); }
来源：http://dali.daria6918.cn/Article/details/gtzihiidas.html

[O05] 并发执行并等待全部完成
来源：http://dali.haohaochexian.top/Article/details/gtebqrqpwh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.vqdsnc.cn/Article/details/gtgyfflvwy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ywan-chungtsiang.top/Article/details/gtckocxqaz.html

JS:   await Promise.all(tasks)
来源：http://dali.wangdashe.top/Article/details/gthvwxuhzs.html

TS:   await Promise.all(tasks)
来源：http://dali.tanke756.top/Article/details/gtdausdsjr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shzxlz.cn/Article/details/gtvzficxaz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.wangdashe.top/Article/details/gtatzdqfue.html

Ruby: threads.map(&:join)
来源：http://dali.dianchejie.cn/Article/details/gtqigkjmaf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gaohongyu789.top/Article/details/gtvlfyshxm.html

[O06] 使用进程池
来源：http://dali.yanxiufei.cn/Article/details/gtcuwjcexq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yj20258.top/Article/details/gtlqzfhmgm.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ppjwa.cn/Article/details/gtiqpryzsd.html

JS:   // child_process / cluster 模块
来源：http://dali.cdnleiting.top/Article/details/gtzmmltwjz.html

TS:   // child_process / cluster 模块
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcaihbivj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhixingplan.top/Article/details/gtbnjnulaz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yanxiufei.cn/Article/details/gtsqqavzos.html

Ruby: // fork 块
来源：http://dali.zhongyouzk.top/Article/details/gtendptakv.html


<!-- 参考信息 -->