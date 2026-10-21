代发 wailian999

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sysykeji.top/Article/details/gtrabdhsaq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.daxiang520.top/Article/details/gtrddulqes.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqsorvsnq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.316326.xyz/Article/details/gtyosesehf.html

[L03] 设置自定义请求头
来源：http://dali.smart0.xyz/Article/details/gtknckkpbc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xinyue.icu/Article/details/gtfoldjqcs.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.wangshuangyany.cn/Article/details/gteyuakmoo.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gtnmorltmr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.bjfxy.top/Article/details/gtmyibtuph.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.snrcjt.cn/Article/details/gthtvqudjp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shzxlz.cn/Article/details/gtwaigenlk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xziqi.cn/Article/details/gtecpxfpwt.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.guowangkeji.top/Article/details/gtscfdghux.html

[L04] 设置超时
来源：http://dali.tianlin.xyz/Article/details/gtkbdyyqom.html

Py:   requests.get(url, timeout=5)
来源：http://dali.quarkkingdee.top/Article/details/gtayjwujxn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gaohongyu789.top/Article/details/gtylbzpsmk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hywenlv.cn/Article/details/gtsbzlamzt.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangdashe.top/Article/details/gthdjfcaxp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ybcxt.top/Article/details/gtgasxyovh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinghuilouyu.cn/Article/details/gtqlatazia.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.dashuyun.cn/Article/details/gtmydtssxo.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yj20258.top/Article/details/gtgbxtqwpr.html

[L05] 上传文件（multipart）
来源：http://dali.ehwqpu.com/Article/details/gtkmetbzzn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.dashuyun.cn/Article/details/gtjflphlkx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zdqjudy.top/Article/details/gtdceklyaw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.guowangkeji.top/Article/details/gtdmroxohu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sysykeji.top/Article/details/gtbyjfoupj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jyoumei.cn/Article/details/gttvjxsqfr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xuetiantiany.cn/Article/details/gtxmksfoah.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.guannengcc.top/Article/details/gtmjjgbrwg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtumvqerxu.html

[L06] 解析响应为 JSON
来源：http://dali.zhixingplan.top/Article/details/gtcxfwlmki.html

Py:   resp.json()
来源：http://dali.mhx1999.top/Article/details/gtygnyvhmt.html

PHP:  json_decode($body, true);
来源：http://dali.tanke756.top/Article/details/gtvizdctix.html

JS:   await resp.json()
来源：http://dali.yongpay.top/Article/details/gtbcsqilya.html

TS:   await resp.json()
来源：http://dali.xziqi.cn/Article/details/gtxvfwycfg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gtsvnbtdbw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.redwolf501.top/Article/details/gtefrwrhoh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hnxiangtu.top/Article/details/gtnelukjcc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xinyue.icu/Article/details/gttdwjkgas.html

[L07] 处理 HTTP 状态码
来源：http://dali.aizwys.cn/Article/details/gtqjewgxko.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jyoumei.cn/Article/details/gthlxduwzr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cheryme.top/Article/details/gtknzrivxy.html

JS:   resp.ok;  resp.status
来源：http://dali.feifeiyinyue.top/Article/details/gtkatkhgot.html

TS:   resp.ok;  resp.status
来源：http://dali.xziqi.cn/Article/details/gtbkzhcckd.html

Java: resp.statusCode()
来源：http://dali.zhengqikj.top/Article/details/gtgrncytym.html

Go:   resp.StatusCode
来源：http://dali.yuanzhike.top/Article/details/gtbyjpsyem.html

Ruby: resp.code.to_i
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvdrejirb.html

C#:   (int)resp.StatusCode
来源：http://dali.yangfankeji.com/Article/details/gtdmfahies.html

[L08] 并发请求多个地址
来源：http://dali.xziqi.cn/Article/details/gtbpirmqcm.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xinyue.icu/Article/details/gtwcjlbyjp.html

PHP:  curl_multi_init() 系列
来源：http://dali.fengsongda.top/Article/details/gtpyzisndo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gotoacloud.top/Article/details/gtnvvvfqem.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkelnlkxk.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.iojbl.cn/Article/details/gtbhbymxqz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jianghu66.top/Article/details/gthgvsnnlm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.aibaodan.cn/Article/details/gttvufidff.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nwbrower.top/Article/details/gtqcbsprpx.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtcivnqkba.html

M. 命令行 / 进程 / 环境
来源：http://dali.havefunace.top/Article/details/gthexzrocy.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtjzszzenj.html

[M01] 读取命令行参数
来源：http://dali.jiagoushi.top/Article/details/gtetnvyusr.html

Py:   sys.argv[1:]
来源：http://dali.shzxlz.cn/Article/details/gtmdomlyiv.html

PHP:  $argv;  $argc;
来源：http://dali.wangshuangyany.cn/Article/details/gtsntvqjbx.html

JS:   process.argv.slice(2)
来源：http://dali.316326.xyz/Article/details/gtjxkwdqyc.html

TS:   process.argv.slice(2)
来源：http://dali.tian-w.cn/Article/details/gthnjrtjsl.html

Java: args 数组（main 方法参数）
来源：http://dali.yuanzhike.top/Article/details/gthvkjfgel.html

Go:   os.Args[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gthrmzbstt.html

Ruby: ARGV
来源：http://dali.gotoacloud.top/Article/details/gthzsfifww.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbhjkzbne.html

[M02] 读取环境变量
来源：http://dali.sweek.top/Article/details/gtpynjqcvl.html

Py:   os.environ.get("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gtjmblzdvs.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.bjfxy.top/Article/details/gtkuwgcdkb.html

JS:   process.env.HOME
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzhyoycic.html

TS:   process.env.HOME
来源：http://dali.yongpay.top/Article/details/gtjywxsaoi.html

Java: System.getenv("HOME")
来源：http://dali.xylfe.cn/Article/details/gtvtvrpkao.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cucudq.cn/Article/details/gthdqbodvr.html

Ruby: ENV["HOME"]
来源：http://dali.hywenlv.cn/Article/details/gtmjfdxthx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hnqzz.top/Article/details/gtnrqgsvwy.html

[M03] 执行外部命令
来源：http://dali.cashguo.top/Article/details/gtacjkwdnw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xinyue.icu/Article/details/gtnpeebmtb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhengqikj.top/Article/details/gtgutynxgn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gtkprvjxfj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.aizwys.cn/Article/details/gtpqacmekv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.daria6918.cn/Article/details/gthgoutjsh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.redwolf501.top/Article/details/gtvrkmambf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhixingplan.top/Article/details/gtqhkxomom.html

C#:   Process.Start("ls", "-l");
来源：http://dali.wangshuangyany.cn/Article/details/gtzinlhysx.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gthlsnquzq.html

Py:   os.getcwd()
来源：http://dali.c1oappe.top/Article/details/gtnmgfmkfo.html

PHP:  getcwd();
来源：http://dali.gotoacloud.top/Article/details/gteqwjobrs.html

JS:   process.cwd()
来源：http://dali.zhixingplan.top/Article/details/gtosxukwwh.html

TS:   process.cwd()
来源：http://dali.yuanzhike.top/Article/details/gtlnqvrzsw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.daria6918.cn/Article/details/gtauwourpv.html

Go:   os.Getwd()
来源：http://dali.jiagoushi.top/Article/details/gtgjerxfaq.html

Ruby: Dir.pwd
来源：http://dali.zhoulong.xyz/Article/details/gtdvroyvgr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.daxiang520.top/Article/details/gtsmvbgltv.html

[M05] 设置退出码
来源：http://dali.dianchejie.cn/Article/details/gtnduwmxgk.html

Py:   sys.exit(1)
来源：http://dali.guannengcc.top/Article/details/gtiyhrzuzj.html

PHP:  exit(1);
来源：http://dali.hnxiangtu.top/Article/details/gtejbblsxx.html

JS:   process.exit(1)
来源：http://dali.xylfe.cn/Article/details/gtfurtuqfe.html

TS:   process.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gtrncgbklv.html

Java: System.exit(1)
来源：http://dali.iojbl.cn/Article/details/gtqcaoocxl.html

Go:   os.Exit(1)
来源：http://dali.xuanzx.com/Article/details/gtlcxzhyhl.html

Ruby: exit 1
来源：http://dali.vqdsnc.cn/Article/details/gtjlydglcj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hysaishi.cn/Article/details/gtowrxptfu.html

[M06] 向标准错误输出
来源：http://dali.yuanzhike.top/Article/details/gtzbxetyyx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuoenaeay.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.tanke756.top/Article/details/gtsxuotmad.html

JS:   console.error("err")
来源：http://dali.jyoumei.cn/Article/details/gtunjtxeqb.html

TS:   console.error("err")
来源：http://dali.gogol.net.cn/Article/details/gtjnifjdgn.html

Java: System.err.println("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnzjslkti.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.guowangkeji.top/Article/details/gtxyvksexu.html

Ruby: warn "err"
来源：http://dali.mhx1999.top/Article/details/gtarcenuuv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hongshengwenyu.top/Article/details/gtsadchctk.html

[M07] 判断是否为主入口
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrghkgmds.html

Py:   if __name__ == "__main__":
来源：http://dali.hfpthk.cn/Article/details/gtppwsngqj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtztfnzzys.html

JS:   require.main === module
来源：http://dali.yj20258.top/Article/details/gtyzmuslan.html

TS:   require.main === module
来源：http://dali.hnxiangtu.top/Article/details/gtxmedeymz.html

Java: public static void main(String[] args)
来源：http://dali.meibo888.top/Article/details/gtlsuhmrnj.html

Go:   func main()
来源：http://dali.cdnleiting.top/Article/details/gtxttjnbsq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.316326.xyz/Article/details/gtpmnvjiyl.html

C#:   static void Main(string[] args)
来源：http://dali.zycfv.cn/Article/details/gtghfdlmxb.html

[M08] 获取系统与运行时信息
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpuyyfhuk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cashguo.top/Article/details/gtrboblrnt.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.aibaodan.cn/Article/details/gtdcradikw.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gtaupjptfh.html

TS:   process.platform;  process.version
来源：http://dali.pycfn.com/Article/details/gttbzznwfo.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.9152youxi.cn/Article/details/gtoubloawh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.vqdsnc.cn/Article/details/gtuxmbewju.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hnqzz.top/Article/details/gtamfffvem.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sysykeji.top/Article/details/gtqybgfkhx.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtwdxykctj.html

N. 数据结构与算法
来源：http://dali.yongpay.top/Article/details/gtdcwcrltr.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gteyjvaupq.html

[N01] 二分查找（有序数组）
来源：http://dali.hnxiangtu.top/Article/details/gthnwuecxx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgkprolpj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.redwolf501.top/Article/details/gticaqezlz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcolqiklu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.mhx1999.top/Article/details/gtzkzsmlrh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtydzoyhzd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gtmvqfwsop.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gthbdwqxzm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jianghu66.top/Article/details/gtraeyqzla.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shzxlz.cn/Article/details/gtixyvzdpw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhoulong.xyz/Article/details/gtzsoabqsb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zycfv.cn/Article/details/gtolmpbnpe.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.0kj1m.cn/Article/details/gtkxxectvn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jianghu66.top/Article/details/gtlzlxbmzo.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.vqdsnc.cn/Article/details/gtvuvymbfz.html

Go:   slices.Sort(arr)
来源：http://dali.gogol.net.cn/Article/details/gteqgdwrao.html

Ruby: arr.sort
来源：http://dali.cdnleiting.top/Article/details/gtfqtyrokh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jiagoushi.top/Article/details/gtdjotfcuw.html

[N03] 快速排序（分治示例）
来源：http://dali.gogol.net.cn/Article/details/gtldlwamex.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hnxiangtu.top/Article/details/gtsxmrmjzd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhengqikj.top/Article/details/gtzrxvakrq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.9152youxi.cn/Article/details/gtlwvtmgcc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ybcxt.top/Article/details/gtkhhsuozn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.meibo888.top/Article/details/gtwrzhakqh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenzaomai.com/Article/details/gtyxtnwxev.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jyoumei.cn/Article/details/gtyohymoap.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tianlin.xyz/Article/details/gtmmxoqyrh.html

[N04] 斐波那契数列
来源：http://dali.smart0.xyz/Article/details/gtoarmapnt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtarevclfp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jiagoushi.top/Article/details/gtxqytrgax.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daxiang520.top/Article/details/gtmywgihvl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigufen.top/Article/details/gtrfoavucv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.nwbrower.top/Article/details/gtlauyxtgc.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.nwbrower.top/Article/details/gtmtjcmzmc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.meibo888.top/Article/details/gtttewjwhl.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtplswjkpm.html

[N05] 最大公约数
来源：http://dali.jlsjyb.cn/Article/details/gtbdtnxqkc.html

Py:   math.gcd(a, b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvmyevejd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvugqqipm.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hywenlv.cn/Article/details/gtmypdaukm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.mhx1999.top/Article/details/gtbfmmiehr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.fengsongda.top/Article/details/gtlllockza.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jqgfzy.top/Article/details/gtuooylrxl.html

Ruby: a.gcd(b)
来源：http://dali.jyoumei.cn/Article/details/gtivirfjul.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.aizwys.cn/Article/details/gtphpaxgul.html

[N06] 判断回文字符串
来源：http://dali.cheryme.top/Article/details/gtkiajrzzi.html

Py:   s == s[::-1]
来源：http://dali.chenjidiqi.icu/Article/details/gtgjendjmz.html

PHP:  $s === strrev($s);
来源：http://dali.xinyue.icu/Article/details/gtfqdsemmc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yj20258888.top/Article/details/gtchlsiqwz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gtipyhgkom.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ppjwa.cn/Article/details/gtyubpbdkt.html

Go:   // 双指针从两端比较
来源：http://dali.gzhubu.top/Article/details/gtkoxgmbuz.html

Ruby: s == s.reverse
来源：http://dali.andypj.xyz/Article/details/gtkbzfvbhl.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gtbttrygke.html

[N07] 两数之和（返回下标）
来源：http://dali.hnqzz.top/Article/details/gtcvmsmdux.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.chenlongwang.top/Article/details/gturyixeic.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gogol.net.cn/Article/details/gtqmkwztyw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.nwbrower.top/Article/details/gtyzmqvjtm.html

TS:   // 手写 Map<string, number>
来源：http://dali.jyoumei.cn/Article/details/gtstdhdhwz.html

Java: // 手写 HashMap
来源：http://dali.gogol.net.cn/Article/details/gtsdpuijjw.html

Go:   // 手写 map[int]int
来源：http://dali.gaohongyu789.top/Article/details/gtzysmmukk.html

Ruby: // 手写 Hash
来源：http://dali.xuanzx.com/Article/details/gtebnvejwm.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yvedp.cn/Article/details/gtubrqiqra.html

[N08] 生成全排列
来源：http://dali.jinqigfzy.top/Article/details/gthpcsqntm.html

Py:   itertools.permutations(arr)
来源：http://dali.gogol.net.cn/Article/details/gtpzwzulaq.html

PHP:  // 手写递归交换
来源：http://dali.shuidangran.top/Article/details/gtnakvhlsz.html

JS:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gtshojvxrx.html

TS:   // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gtfpvgsgbi.html

Java: // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtkbtqwepl.html

Go:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtoaxhlmhf.html

Ruby: arr.permutation.to_a
来源：http://dali.iojbl.cn/Article/details/gtxslpppls.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gtgbouceus.html

[N09] 栈与队列
来源：http://dali.feifeiyinyue.top/Article/details/gtiusdxsib.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.haohaochexian.top/Article/details/gtfnnbfhkn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.meibo888.top/Article/details/gtltrmswsa.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.guannengcc.top/Article/details/gtfqycipzz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yj20258.top/Article/details/gtdmwpuwuj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.nwbrower.top/Article/details/gtgmuoaplm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.smart0.xyz/Article/details/gtpfkewdzv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhoulong.xyz/Article/details/gtduuwftpj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gaohongyu789.top/Article/details/gtxwnhyffr.html

[N10] 链表节点定义
来源：http://dali.jiagoushi.top/Article/details/gtpobjdrtc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tianlin.xyz/Article/details/gtzllxfhxn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.quarkkingdee.top/Article/details/gtvnecozum.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gogol.net.cn/Article/details/gtvmlvigrb.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.feifeiyinyue.top/Article/details/gtwqfpsjqi.html

Java: class Node { int v; Node next; }
来源：http://dali.sxryk.cn/Article/details/gthtjssogu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.haohaochexian.top/Article/details/gtpcltzmqm.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yj20258888.top/Article/details/gtqdzqrypd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tanke756.top/Article/details/gthmmgxelq.html

[N11] 二叉树中序遍历
来源：http://dali.jinqigfzy.top/Article/details/gtxjfdzzua.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shuidangran.top/Article/details/gtesrqzvfb.html

PHP:  // 手写递归函数
来源：http://dali.sweek.top/Article/details/gtwzqsxeun.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.9152youxi.cn/Article/details/gtuckqfrnt.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258888.top/Article/details/gtrenxugfb.html

Java: // 手写递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiivyomar.html

Go:   // 手写递归
来源：http://dali.sweek.top/Article/details/gtaaytkiud.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jqgfzy.top/Article/details/gtcugpufus.html

C#:   // 手写递归
来源：http://dali.tianlin.xyz/Article/details/gteqyosswc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.snrcjt.cn/Article/details/gtdjtouekj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.meibo888.top/Article/details/gtyxjwplmh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.daxiang520.top/Article/details/gtsmgzkbzf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxinkj.top/Article/details/gtyfndixin.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gogol.net.cn/Article/details/gtaibezkgp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cheryme.top/Article/details/gtbhnykmif.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.nwbrower.top/Article/details/gttqrlmpte.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yanxiufei.cn/Article/details/gtkrbyfeik.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenjidiqi.icu/Article/details/gtyetrpzjp.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtqlhtrehk.html

O. 并发与异步
来源：http://dali.yj20258888.top/Article/details/gtxmmspnba.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtrqkwsemn.html

[O01] 启动一个线程
来源：http://dali.shuidangran.top/Article/details/gtcjcaoxmx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xziqi.cn/Article/details/gtamkwjcnc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.quarkkingdee.top/Article/details/gtfckczkbx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yangfankeji.com/Article/details/gtohppxnux.html

TS:   // 同 JS
来源：http://dali.aizwys.cn/Article/details/gtwblcwozc.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinghuilouyu.cn/Article/details/gtwdfnozus.html

Go:   go f()
来源：http://dali.yonumen.top/Article/details/gtsoeubufw.html

Ruby: Thread.new { f }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbujsvyvq.html

C#:   Task.Run(() => F());
来源：http://dali.xuetiantiany.cn/Article/details/gtjghxuhih.html

[O02] 使用线程池
来源：http://dali.nwbrower.top/Article/details/gteqsslgfo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.mhx1999.top/Article/details/gtynshzieg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.havefunace.top/Article/details/gtmzuqsdvo.html

JS:   // worker_threads 线程池
来源：http://dali.jqgfzy.top/Article/details/gtyttzzbqh.html

TS:   // worker_threads 线程池
来源：http://dali.yj202588.top/Article/details/gtpnylhnxu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.fengsongda.top/Article/details/gtdfifluun.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.aibaodan.cn/Article/details/gteaxhleaj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ppjwa.cn/Article/details/gtymbrziem.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xylfe.cn/Article/details/gtzhrexqhw.html

[O03] 加锁保护共享数据
来源：http://dali.feifeiyinyue.top/Article/details/gticwtfooq.html

Py:   with lock: shared += 1
来源：http://dali.yj20258.top/Article/details/gtxudtmnmu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hnxiangtu.top/Article/details/gticsnfwqc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jianghu66.top/Article/details/gttiugokmc.html

TS:   // 同 JS
来源：http://dali.nwbrower.top/Article/details/gtgphbdmud.html

Java: synchronized (this) { shared++; }
来源：http://dali.yangfankeji.com/Article/details/gtrxiwmnrs.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.svipenyu.cn/Article/details/gtzqxapykt.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.iojbl.cn/Article/details/gtvsdbhybc.html

C#:   lock (gate) { shared++; }
来源：http://dali.hysaishi.cn/Article/details/gtaqlzesxq.html

[O04] 定义异步函数并等待
来源：http://dali.xuanzx.com/Article/details/gtruficqja.html

Py:   async def f():⏎    await g()
来源：http://dali.nanxinkj.top/Article/details/gtqjacuozl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.smart0.xyz/Article/details/gtqhwnegrx.html

JS:   async function f() { await g(); }
来源：http://dali.zhongyouzk.top/Article/details/gtjwtwyosh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtmvuwhovc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.wangshuangyany.cn/Article/details/gtntovesme.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xziqi.cn/Article/details/gtuwddhyvj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.feifeiyinyue.top/Article/details/gtouiabemy.html

C#:   async Task F() { await G(); }
来源：http://dali.yongpay.top/Article/details/gtruhyaxac.html

[O05] 并发执行并等待全部完成
来源：http://dali.cucudq.cn/Article/details/gtelsjoflj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdcenuxmo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.snrcjt.cn/Article/details/gtrarebnjg.html

JS:   await Promise.all(tasks)
来源：http://dali.zhiwuduotai.top/Article/details/gtbpuowkdd.html

TS:   await Promise.all(tasks)
来源：http://dali.snrcjt.cn/Article/details/gtfqkjandd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtryamhvwn.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jinqigfzy.top/Article/details/gtnwtluobp.html

Ruby: threads.map(&:join)
来源：http://dali.zhiwuduotai.top/Article/details/gtueefopzw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.tian-w.cn/Article/details/gtkqtoxizh.html

[O06] 使用进程池
来源：http://dali.cdnleiting.top/Article/details/gtfgjtdzod.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yj20258.top/Article/details/gtwjefvbob.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhixingplan.top/Article/details/gtoejytmdx.html

JS:   // child_process / cluster 模块
来源：http://dali.chenjidiqi.icu/Article/details/gtnvzegrza.html

TS:   // child_process / cluster 模块
来源：http://dali.yvedp.cn/Article/details/gtmivnqkem.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gotoacloud.top/Article/details/gtweordnky.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ivvv.top/Article/details/gtwfnpsorf.html

Ruby: // fork 块
来源：http://dali.sysykeji.top/Article/details/gtaczzihzs.html


<!-- 参考信息 -->