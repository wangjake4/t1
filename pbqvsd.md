代发 wailian999

[L03] 设置自定义请求头
来源：http://dali.xziqi.cn/Article/details/gtropijtvj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sufxvd.cn/Article/details/gthxqiivsv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hammf.cn/Article/details/gtkmudlzys.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj202588.top/Article/details/gtclijtgac.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhixingplan.top/Article/details/gtlqlrucaa.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yuanzhike.top/Article/details/gtrohqichu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfiadsyqo.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sxryk.cn/Article/details/gtziisyrkp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.tianlin.xyz/Article/details/gtfydmokdl.html

[L04] 设置超时
来源：http://dali.hysaishi.cn/Article/details/gtebefjdsx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yuanzhike.top/Article/details/gtiysgpcql.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj20258888.top/Article/details/gtdzkqgbko.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ybcxt.top/Article/details/gtnutpyhwe.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhiwuduotai.top/Article/details/gtkrlhdlnw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yuxming.cn/Article/details/gtejcglxis.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ivvv.top/Article/details/gtzqfuqopf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yangfankeji.com/Article/details/gtvjrzqtzk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gaohongyu789.top/Article/details/gtqysgzhkw.html

[L05] 上传文件（multipart）
来源：http://dali.xziqi.cn/Article/details/gtpebcpkik.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sxryk.cn/Article/details/gtpsgfhytt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jiagoushi.top/Article/details/gtwnomnkdb.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ydzc1.top/Article/details/gttlhfwjxd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zdqjudy.top/Article/details/gthtugxgyz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.c1oappe.top/Article/details/gtgxqhpoxx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.mhx1999.top/Article/details/gtuuwekkgd.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yongpay.top/Article/details/gthnhyubzp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yongpay.top/Article/details/gtvxdyijao.html

[L06] 解析响应为 JSON
来源：http://dali.cqqwz.cn/Article/details/gtsaluixpf.html

Py:   resp.json()
来源：http://dali.xylfe.cn/Article/details/gtbvukfejl.html

PHP:  json_decode($body, true);
来源：http://dali.fengsongda.top/Article/details/gtcjapggaf.html

JS:   await resp.json()
来源：http://dali.daxiang520.top/Article/details/gtgfmbwlqa.html

TS:   await resp.json()
来源：http://dali.pycfn.com/Article/details/gtokgqzbcz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gtvrxdkjar.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.svipenyu.cn/Article/details/gtqthujgvt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hysaishi.cn/Article/details/gtuflejpwo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xuetiantiany.cn/Article/details/gthdrvqnyv.html

[L07] 处理 HTTP 状态码
来源：http://dali.jqgufenzy.top/Article/details/gtadhabswn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.smart0.xyz/Article/details/gthybheome.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yuxming.cn/Article/details/gtuubaoate.html

JS:   resp.ok;  resp.status
来源：http://dali.smart0.xyz/Article/details/gtjttcvsfi.html

TS:   resp.ok;  resp.status
来源：http://dali.jianghu66.top/Article/details/gtrohvdibs.html

Java: resp.statusCode()
来源：http://dali.quarkkingdee.top/Article/details/gtdrmjutxs.html

Go:   resp.StatusCode
来源：http://dali.fengsongda.top/Article/details/gtlhfutmjy.html

Ruby: resp.code.to_i
来源：http://dali.cqqwz.cn/Article/details/gtawkyyuki.html

C#:   (int)resp.StatusCode
来源：http://dali.yanxiufei.cn/Article/details/gtwvlzbosw.html

[L08] 并发请求多个地址
来源：http://dali.sysykeji.top/Article/details/gtcpsmppkt.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gotoacloud.top/Article/details/gtbbhbofim.html

PHP:  curl_multi_init() 系列
来源：http://dali.hongshengwenyu.top/Article/details/gtlfirvwtq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgufenzy.top/Article/details/gthmpfqrsi.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pycfn.com/Article/details/gtknkxsbwd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.daria6918.cn/Article/details/gtxvtuovkc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xinyue.icu/Article/details/gtnjakxwbl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yueranfly.top/Article/details/gtuokfonja.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nanxinkj.top/Article/details/gtexovfneh.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtlrxecnsi.html

M. 命令行 / 进程 / 环境
来源：http://dali.0kj1m.cn/Article/details/gtiayveoey.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtekvngktu.html

[M01] 读取命令行参数
来源：http://dali.ydzc1.top/Article/details/gtgwwygkqq.html

Py:   sys.argv[1:]
来源：http://dali.vqdsnc.cn/Article/details/gttfsitarq.html

PHP:  $argv;  $argc;
来源：http://dali.dashuyun.cn/Article/details/gtczhqducc.html

JS:   process.argv.slice(2)
来源：http://dali.vqdsnc.cn/Article/details/gthzlwydal.html

TS:   process.argv.slice(2)
来源：http://dali.hfpthk.cn/Article/details/gtedrgulyr.html

Java: args 数组（main 方法参数）
来源：http://dali.svipenyu.cn/Article/details/gtbhueaypg.html

Go:   os.Args[1:]
来源：http://dali.yj202588.top/Article/details/gtlchoyhrm.html

Ruby: ARGV
来源：http://dali.fzhhl.top/Article/details/gtofzbjwsg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj20258888.top/Article/details/gtiupejkei.html

[M02] 读取环境变量
来源：http://dali.jlsjyb.cn/Article/details/gtyiknadua.html

Py:   os.environ.get("HOME")
来源：http://dali.zhixingplan.top/Article/details/gtiinxfeur.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.redwolf501.top/Article/details/gtrsywjpuo.html

JS:   process.env.HOME
来源：http://dali.birdmap.top/Article/details/gtqgheahhh.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gtfwdkvhkm.html

Java: System.getenv("HOME")
来源：http://dali.zhixingplan.top/Article/details/gtnmgajyfs.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.fzhhl.top/Article/details/gtyvfwhrgs.html

Ruby: ENV["HOME"]
来源：http://dali.yongpay.top/Article/details/gtwmghnsof.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sufxvd.cn/Article/details/gtkctwxetb.html

[M03] 执行外部命令
来源：http://dali.zhongyouzk.top/Article/details/gthwfmbxzh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinqigfzy.top/Article/details/gtexapvwbo.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj20258888.top/Article/details/gtuqomrznd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.dashuyun.cn/Article/details/gtxshxsxyj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jyoumei.cn/Article/details/gtpcbsvnba.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.kuanghao11.cn/Article/details/gtwcqnvsyt.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gotoacloud.top/Article/details/gtgaukhztw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gtvcxtpwsu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cucudq.cn/Article/details/gtbevuyduv.html

[M04] 获取当前工作目录
来源：http://dali.jqgufenzy.top/Article/details/gttdovmcpl.html

Py:   os.getcwd()
来源：http://dali.pengpengdd.cyou/Article/details/gtsayejdeu.html

PHP:  getcwd();
来源：http://dali.smart0.xyz/Article/details/gtnunhiuje.html

JS:   process.cwd()
来源：http://dali.ppjwa.cn/Article/details/gthflpjgxu.html

TS:   process.cwd()
来源：http://dali.zhiwuduotai.top/Article/details/gtcsaeyivo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yanxiufei.cn/Article/details/gtuuejswsd.html

Go:   os.Getwd()
来源：http://dali.yj20258888.top/Article/details/gtflrgzlza.html

Ruby: Dir.pwd
来源：http://dali.jinqigufen.top/Article/details/gthdbmjdpi.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.aibaodan.cn/Article/details/gthdqbdall.html

[M05] 设置退出码
来源：http://dali.nanxinkj.top/Article/details/gtwejiieph.html

Py:   sys.exit(1)
来源：http://dali.daria6918.cn/Article/details/gtqkjikdet.html

PHP:  exit(1);
来源：http://dali.daria6918.cn/Article/details/gthfysgfni.html

JS:   process.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gtldioveog.html

TS:   process.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gtgvmeatvq.html

Java: System.exit(1)
来源：http://dali.redwolf501.top/Article/details/gtqlioxsvr.html

Go:   os.Exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gtgldoavxy.html

Ruby: exit 1
来源：http://dali.zhoulong.xyz/Article/details/gtqyrwbtje.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.aibaodan.cn/Article/details/gtshudrdad.html

[M06] 向标准错误输出
来源：http://dali.nanxuanxn.top/Article/details/gtdljgvnpd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.nwbrower.top/Article/details/gtgmorpcqg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.smart0.xyz/Article/details/gtuawutwsf.html

JS:   console.error("err")
来源：http://dali.shangyingyoupin.top/Article/details/gtvxzdaaut.html

TS:   console.error("err")
来源：http://dali.hammf.cn/Article/details/gtltzjpfiv.html

Java: System.err.println("err")
来源：http://dali.ybcxt.top/Article/details/gtlczbdlce.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.svipenyu.cn/Article/details/gtmjjydpyd.html

Ruby: warn "err"
来源：http://dali.cdnleiting.top/Article/details/gtxmlrwbgo.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.daria6918.cn/Article/details/gthvcuugms.html

[M07] 判断是否为主入口
来源：http://dali.aizwys.cn/Article/details/gtxaqcwrbq.html

Py:   if __name__ == "__main__":
来源：http://dali.birdmap.top/Article/details/gtkpqxlbvf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhoulong.xyz/Article/details/gtevypwmib.html

JS:   require.main === module
来源：http://dali.xziqi.cn/Article/details/gtzzujkczw.html

TS:   require.main === module
来源：http://dali.zdqjudy.top/Article/details/gtjarmqskj.html

Java: public static void main(String[] args)
来源：http://dali.daxiang520.top/Article/details/gtcznegocp.html

Go:   func main()
来源：http://dali.xylfe.cn/Article/details/gthhuyexcy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.redwolf501.top/Article/details/gtxqkgfbwp.html

C#:   static void Main(string[] args)
来源：http://dali.wangshuangyany.cn/Article/details/gtnmxrnvtx.html

[M08] 获取系统与运行时信息
来源：http://dali.shanyushiyangtech.top/Article/details/gtvnkqeybo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yanxiufei.cn/Article/details/gtvytrrzgz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hammf.cn/Article/details/gtiwlptggh.html

JS:   process.platform;  process.version
来源：http://dali.tian-w.cn/Article/details/gtklkequff.html

TS:   process.platform;  process.version
来源：http://dali.cashguo.top/Article/details/gtfpdzvxiv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xziqi.cn/Article/details/gtundlnnln.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhongyouzk.top/Article/details/gtwyiyexfb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhongyouzk.top/Article/details/gtytjtidji.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yj20258.top/Article/details/gtofzdrybe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtiftnpmgm.html

N. 数据结构与算法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrajzlhfx.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtmbpbtesp.html

[N01] 二分查找（有序数组）
来源：http://dali.zhoulong.xyz/Article/details/gtolkwzfif.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gteanscblj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gtwwlyhrfg.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gogol.net.cn/Article/details/gthrcggefp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daria6918.cn/Article/details/gtverggccz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtkjnqruch.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gtwpvttzrh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shangyingyoupin.top/Article/details/gtevaienqn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yj202588.top/Article/details/gtsooahcwh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.meibo888.top/Article/details/gtirdhxryd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.bjfxy.top/Article/details/gtphxosofg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yuxming.cn/Article/details/gtrpatpncc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.vqdsnc.cn/Article/details/gtphilcgbx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aibaodan.cn/Article/details/gtvxuhobcb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cdnleiting.top/Article/details/gtxqtoumhj.html

Go:   slices.Sort(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtwrzibbzk.html

Ruby: arr.sort
来源：http://dali.zhiwuduotai.top/Article/details/gtosdtyyhh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cucudq.cn/Article/details/gtrevaiwzo.html

[N03] 快速排序（分治示例）
来源：http://dali.gzhubu.top/Article/details/gteycfxtsq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.chenjidiqi.icu/Article/details/gtbwlzgbgi.html

PHP:  // 递归实现，或用 usort
来源：http://dali.dianchejie.cn/Article/details/gtvsgoykvd.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.9152youxi.cn/Article/details/gtwyouhvgl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yangfankeji.com/Article/details/gtjyplkfye.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hfpthk.cn/Article/details/gtehkxyldz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzdzclgow.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yanxiufei.cn/Article/details/gtkimxryba.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.svipenyu.cn/Article/details/gtrspqwdpb.html

[N04] 斐波那契数列
来源：http://dali.haohaochexian.top/Article/details/gttaoieblu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.guowangkeji.top/Article/details/gtijypibdd.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhongyouzk.top/Article/details/gtvyisaewt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gtmqmbzdqm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pycfn.com/Article/details/gtgcnmdjxg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gotoacloud.top/Article/details/gtgmrulcsa.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jianghu66.top/Article/details/gtfjbfondq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ehwqpu.com/Article/details/gtmtlgkrhe.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.snrcjt.cn/Article/details/gtkaewwtow.html

[N05] 最大公约数
来源：http://dali.hysaishi.cn/Article/details/gtwnvtsavb.html

Py:   math.gcd(a, b)
来源：http://dali.nanxuanxn.top/Article/details/gtouidafra.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cqqwz.cn/Article/details/gtgshawdbc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tanke756.top/Article/details/gthfvuacde.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sxryk.cn/Article/details/gtzllnyxmj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.aizwys.cn/Article/details/gtqsujkgmn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shangyingyoupin.top/Article/details/gthlvlwqel.html

Ruby: a.gcd(b)
来源：http://dali.jyoumei.cn/Article/details/gtfweintkl.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhoulong.xyz/Article/details/gtupihtvbh.html

[N06] 判断回文字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvihvgjxd.html

Py:   s == s[::-1]
来源：http://dali.jlsjyb.cn/Article/details/gtkrtolnkk.html

PHP:  $s === strrev($s);
来源：http://dali.nanxuanxn.top/Article/details/gtmkqhinnx.html

JS:   s === [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gtohbmovks.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sysykeji.top/Article/details/gtqvxvzlqx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhengqikj.top/Article/details/gtcdniltaj.html

Go:   // 双指针从两端比较
来源：http://dali.yuxming.cn/Article/details/gtohxdpujh.html

Ruby: s == s.reverse
来源：http://dali.guannengcc.top/Article/details/gtunlvaeuv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhongyouzk.top/Article/details/gtevfwlcxg.html

[N07] 两数之和（返回下标）
来源：http://dali.hfpthk.cn/Article/details/gtkjqjqkeu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.316326.xyz/Article/details/gtsygwvblh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj20258888.top/Article/details/gtgpjawhuy.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ehwqpu.com/Article/details/gthcymqsco.html

TS:   // 手写 Map<string, number>
来源：http://dali.cqqwz.cn/Article/details/gtcsrwlnua.html

Java: // 手写 HashMap
来源：http://dali.ydzc1.top/Article/details/gtpaflikkg.html

Go:   // 手写 map[int]int
来源：http://dali.cqqwz.cn/Article/details/gtlssodjrv.html

Ruby: // 手写 Hash
来源：http://dali.quarkkingdee.top/Article/details/gttlbejssv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.fzhhl.top/Article/details/gtrkauqwii.html

[N08] 生成全排列
来源：http://dali.wangshuangyany.cn/Article/details/gtjmvpgzay.html

Py:   itertools.permutations(arr)
来源：http://dali.guannengcc.top/Article/details/gtlvspopfc.html

PHP:  // 手写递归交换
来源：http://dali.zhiwuduotai.top/Article/details/gtdgvufguy.html

JS:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtiyhmxwjs.html

TS:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gtofamigqc.html

Java: // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtrgwswmwo.html

Go:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gtergcwlqf.html

Ruby: arr.permutation.to_a
来源：http://dali.jinqigufen.top/Article/details/gtzifwsxlr.html

C#:   // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gtcbysgrnn.html

[N09] 栈与队列
来源：http://dali.xylfe.cn/Article/details/gtnrkigkyy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ppjwa.cn/Article/details/gtmvsxwghq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.guannengcc.top/Article/details/gtmzgkvtti.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.vqdsnc.cn/Article/details/gtawxsgvga.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yuxming.cn/Article/details/gteqphefbm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zycfv.cn/Article/details/gtooryabdk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xylfe.cn/Article/details/gtjdkvlovm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhengqikj.top/Article/details/gtueybrhqp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenjidiqi.icu/Article/details/gtnckidxlm.html

[N10] 链表节点定义
来源：http://dali.yj20258.top/Article/details/gtffoxohkh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jqgfzy.top/Article/details/gtrzprtgaz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jlsjyb.cn/Article/details/gtxwnsxhrj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinqigufen.top/Article/details/gteoitvkgf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.guowangkeji.top/Article/details/gtnvdmnlds.html

Java: class Node { int v; Node next; }
来源：http://dali.ydzc1.top/Article/details/gtnstkvfct.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.nwbrower.top/Article/details/gtosatwljz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.havefunace.top/Article/details/gtmbhldvat.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.fengsongda.top/Article/details/gtofondcnc.html

[N11] 二叉树中序遍历
来源：http://dali.hfpthk.cn/Article/details/gtxfwyoysv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.andypj.xyz/Article/details/gtdbyzllzm.html

PHP:  // 手写递归函数
来源：http://dali.shangyingyoupin.top/Article/details/gtlinlpjjo.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hywenlv.cn/Article/details/gtiocsawvz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.dianchejie.cn/Article/details/gtjfamqymy.html

Java: // 手写递归
来源：http://dali.jinqigfzy.top/Article/details/gtslapysyw.html

Go:   // 手写递归
来源：http://dali.xinyue.icu/Article/details/gtjwursuzx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinqigufen.top/Article/details/gtovdlcgbn.html

C#:   // 手写递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfwmbejze.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yj20258.top/Article/details/gtaoooaopt.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.pycfn.com/Article/details/gtjisctnvu.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jyoumei.cn/Article/details/gtxbgnxbrk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yongpay.top/Article/details/gtxvrxpepy.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cheryme.top/Article/details/gtawcqypwo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.havefunace.top/Article/details/gtchcjlaia.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shangyingyoupin.top/Article/details/gtvbnqgqjt.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yonumen.top/Article/details/gtxqafatgw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gotoacloud.top/Article/details/gtxnqomjcr.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtoufqpldg.html

O. 并发与异步
来源：http://dali.fengsongda.top/Article/details/gtokuqacbx.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gthythckti.html

[O01] 启动一个线程
来源：http://dali.0kj1m.cn/Article/details/gtgcvefqxs.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hnxiangtu.top/Article/details/gtygninenc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yuanzhike.top/Article/details/gtukmpzhqh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjjpfxpmx.html

TS:   // 同 JS
来源：http://dali.daxiang520.top/Article/details/gtlnihpnlh.html

Java: new Thread(() -> f()).start()
来源：http://dali.nwbrower.top/Article/details/gtcklnhhtm.html

Go:   go f()
来源：http://dali.ehwqpu.com/Article/details/gtkaddftaj.html

Ruby: Thread.new { f }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtldrlkrud.html

C#:   Task.Run(() => F());
来源：http://dali.cashguo.top/Article/details/gtusxcylat.html

[O02] 使用线程池
来源：http://dali.zhiwuduotai.top/Article/details/gtfvupnngq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jyoumei.cn/Article/details/gtasjzwfgl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hfpthk.cn/Article/details/gtcrlnpxlr.html

JS:   // worker_threads 线程池
来源：http://dali.hfpthk.cn/Article/details/gtqjfembte.html

TS:   // worker_threads 线程池
来源：http://dali.guannengcc.top/Article/details/gtfdukguqw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.bjfxy.top/Article/details/gtctdtlgei.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jqgfzy.top/Article/details/gtuggqkguf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpattvyan.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.wangshuangyany.cn/Article/details/gtwntzkzzw.html

[O03] 加锁保护共享数据
来源：http://dali.jiagoushi.top/Article/details/gtpezpoltn.html

Py:   with lock: shared += 1
来源：http://dali.jlsjyb.cn/Article/details/gtaeswqpeu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xuetiantiany.cn/Article/details/gtycfismjk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yj20258888.top/Article/details/gtwqiatasb.html

TS:   // 同 JS
来源：http://dali.haohaochexian.top/Article/details/gtbkxcbxxh.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gtxtzkwtgq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.chenzaomai.com/Article/details/gtymfatudd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqcowzckh.html

C#:   lock (gate) { shared++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbltffyow.html

[O04] 定义异步函数并等待
来源：http://dali.yuxming.cn/Article/details/gtpdiwfeef.html

Py:   async def f():⏎    await g()
来源：http://dali.ivvv.top/Article/details/gtmlnyovgw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shangyingyoupin.top/Article/details/gtuaolpogo.html

JS:   async function f() { await g(); }
来源：http://dali.9152youxi.cn/Article/details/gthfekswks.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hammf.cn/Article/details/gtwqcnlqbt.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.nanxinkj.top/Article/details/gtdijvpszp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ydzc1.top/Article/details/gtwbyedzvm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hfpthk.cn/Article/details/gtnwiqzfau.html

C#:   async Task F() { await G(); }
来源：http://dali.redwolf501.top/Article/details/gtobxxggrh.html

[O05] 并发执行并等待全部完成
来源：http://dali.chenzaomai.com/Article/details/gtplliamtz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.vqdsnc.cn/Article/details/gthyhturlz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yangfankeji.com/Article/details/gtwshwjjpf.html

JS:   await Promise.all(tasks)
来源：http://dali.dianchejie.cn/Article/details/gtqwkwffsg.html

TS:   await Promise.all(tasks)
来源：http://dali.vqdsnc.cn/Article/details/gtotgzgsix.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvgrbkhre.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.pycfn.com/Article/details/gtkymbfuin.html

Ruby: threads.map(&:join)
来源：http://dali.zhongyouzk.top/Article/details/gtamvijfei.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hywenlv.cn/Article/details/gtxxxibzto.html

[O06] 使用进程池
来源：http://dali.fengsongda.top/Article/details/gtuwzzfkwq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.bjfxy.top/Article/details/gtmdzlkfeq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hywenlv.cn/Article/details/gtrpccfwes.html

JS:   // child_process / cluster 模块
来源：http://dali.jinghuilouyu.cn/Article/details/gteufxbdnu.html

TS:   // child_process / cluster 模块
来源：http://dali.xuetiantiany.cn/Article/details/gtfdwacfnm.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.0kj1m.cn/Article/details/gtmdjpkzte.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.nwbrower.top/Article/details/gtgdljfavb.html

Ruby: // fork 块
来源：http://dali.tian-w.cn/Article/details/gtvpofhrtw.html

C#:   Parallel.For
来源：http://dali.jyoumei.cn/Article/details/gtkkkaxtqg.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtpsoyedba.html

P. 常用工具函数
来源：http://dali.snrcjt.cn/Article/details/gtvmumtngn.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtwsnexajn.html


<!-- 参考信息 -->