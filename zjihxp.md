代发 wailian999

Go:   resp, err := http.Get(url)
来源：http://dali.zycfv.cn/Article/details/gtjhbhvgxq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tanke756.top/Article/details/gtxevkrckk.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.pycfn.com/Article/details/gtjzlemhje.html

[L02] 发送 POST JSON
来源：http://dali.aizwys.cn/Article/details/gtfpmsmkek.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.mhx1999.top/Article/details/gtacanwahq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.snrcjt.cn/Article/details/gtceqdqjjz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgufenzy.top/Article/details/gtmshbfucp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.vqdsnc.cn/Article/details/gtxuqvgffh.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.tanke756.top/Article/details/gtnvkyklpi.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ydzc1.top/Article/details/gtuuwkwouv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinghuilouyu.cn/Article/details/gtzarumzfw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sysykeji.top/Article/details/gtosaukama.html

[L03] 设置自定义请求头
来源：http://dali.yj202588.top/Article/details/gtuvjadnru.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yuxming.cn/Article/details/gtemgtrzny.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.birdmap.top/Article/details/gtyvnvzaoe.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwoceadfd.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ivvv.top/Article/details/gtxjforyvl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.chenzaomai.com/Article/details/gtzzszynsk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ppjwa.cn/Article/details/gthsdqwpmb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhengqikj.top/Article/details/gtxbzcnlsq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.tanke756.top/Article/details/gthsgemnby.html

[L04] 设置超时
来源：http://dali.jinqigufen.top/Article/details/gtpmnwjmfa.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shanyushiyangtech.top/Article/details/gtaakchcyh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sufxvd.cn/Article/details/gtzedzjshp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yanxiufei.cn/Article/details/gtbwexsnou.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxinkj.top/Article/details/gtngkcnweb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.mhx1999.top/Article/details/gtouherjkx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.316326.xyz/Article/details/gtpkjkdfmb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.feifeiyinyue.top/Article/details/gtjvintjiz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhongyouzk.top/Article/details/gtdqqqswcs.html

[L05] 上传文件（multipart）
来源：http://dali.shangyingyoupin.top/Article/details/gtmzsheloa.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.pycfn.com/Article/details/gtdnvyznjg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shuidangran.top/Article/details/gtwpltzivo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ppjwa.cn/Article/details/gtfneqjdul.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.kuanghao11.cn/Article/details/gtdrovbqxc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gtbrxkfjah.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.tianlin.xyz/Article/details/gttjqwuinc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yangfankeji.com/Article/details/gtuyqptjbb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtzqpqgrkq.html

[L06] 解析响应为 JSON
来源：http://dali.c1oappe.top/Article/details/gtuahttdvi.html

Py:   resp.json()
来源：http://dali.ehwqpu.com/Article/details/gttkydlkvk.html

PHP:  json_decode($body, true);
来源：http://dali.daxiang520.top/Article/details/gtjugnihvp.html

JS:   await resp.json()
来源：http://dali.xinyue.icu/Article/details/gtyragkdel.html

TS:   await resp.json()
来源：http://dali.sweek.top/Article/details/gtrgxhumfz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenlongwang.top/Article/details/gtlzhiybax.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ydzc1.top/Article/details/gtjkonjdwh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.dianchejie.cn/Article/details/gtvvkpzipc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.guowangkeji.top/Article/details/gtianerevg.html

[L07] 处理 HTTP 状态码
来源：http://dali.xuanzx.com/Article/details/gtrbsfbvkb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.c1oappe.top/Article/details/gtpislslfd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nanxinkj.top/Article/details/gtjkunwxsf.html

JS:   resp.ok;  resp.status
来源：http://dali.ybcxt.top/Article/details/gtfkflredq.html

TS:   resp.ok;  resp.status
来源：http://dali.haohaochexian.top/Article/details/gtcnoltdsh.html

Java: resp.statusCode()
来源：http://dali.hongshengwenyu.top/Article/details/gtaufziltz.html

Go:   resp.StatusCode
来源：http://dali.kuanghao11.cn/Article/details/gtvneumppi.html

Ruby: resp.code.to_i
来源：http://dali.hongshengwenyu.top/Article/details/gtgtjmpvlp.html

C#:   (int)resp.StatusCode
来源：http://dali.cucudq.cn/Article/details/gtxsgsmdzx.html

[L08] 并发请求多个地址
来源：http://dali.xuanzx.com/Article/details/gtuiylfjsf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nwbrower.top/Article/details/gtdbcvbfee.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhongyouzk.top/Article/details/gtngxpeavw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhoulong.xyz/Article/details/gturzhtkxh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hysaishi.cn/Article/details/gtbrppvtbe.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpwjjpjqf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hnqzz.top/Article/details/gtwtnojpjy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.andypj.xyz/Article/details/gtzzwgavox.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.iojbl.cn/Article/details/gtoyaoonqv.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gttgiznyrr.html

M. 命令行 / 进程 / 环境
来源：http://dali.guowangkeji.top/Article/details/gtxyelaatl.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtiaczvuci.html

[M01] 读取命令行参数
来源：http://dali.zhongyouzk.top/Article/details/gttuvypufh.html

Py:   sys.argv[1:]
来源：http://dali.xylfe.cn/Article/details/gteaiesrso.html

PHP:  $argv;  $argc;
来源：http://dali.jiagoushi.top/Article/details/gtojozovtn.html

JS:   process.argv.slice(2)
来源：http://dali.shuidangran.top/Article/details/gtjmmrwmxl.html

TS:   process.argv.slice(2)
来源：http://dali.gaohongyu789.top/Article/details/gtwjdsqmss.html

Java: args 数组（main 方法参数）
来源：http://dali.smart0.xyz/Article/details/gtzocjvlle.html

Go:   os.Args[1:]
来源：http://dali.yonumen.top/Article/details/gtferkyvjv.html

Ruby: ARGV
来源：http://dali.chenjidiqi.icu/Article/details/gtmuizbzob.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zdqjudy.top/Article/details/gtdjtceazc.html

[M02] 读取环境变量
来源：http://dali.tanke756.top/Article/details/gtyuzxerpz.html

Py:   os.environ.get("HOME")
来源：http://dali.meibo888.top/Article/details/gtwjpblxkm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xinyue.icu/Article/details/gtvscsiigx.html

JS:   process.env.HOME
来源：http://dali.yj202588.top/Article/details/gtrjccjjcr.html

TS:   process.env.HOME
来源：http://dali.haohaochexian.top/Article/details/gtmswxlvzb.html

Java: System.getenv("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtigrwpccr.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jqgfzy.top/Article/details/gtfmkihgbj.html

Ruby: ENV["HOME"]
来源：http://dali.gzhubu.top/Article/details/gtimgxmjzb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.meibo888.top/Article/details/gtrdpafpxl.html

[M03] 执行外部命令
来源：http://dali.gogol.net.cn/Article/details/gtnnwpxkik.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ehwqpu.com/Article/details/gtufyoureb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.bjfxy.top/Article/details/gtkesdicfj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.kuanghao11.cn/Article/details/gtrhtfcbra.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hysaishi.cn/Article/details/gtwvmzxxve.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhoulong.xyz/Article/details/gthhsdlddj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shanyushiyangtech.top/Article/details/gtpbexqcxv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinyuanbaomall.cn/Article/details/gteuqaupsz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yongpay.top/Article/details/gtrqklgdmx.html

[M04] 获取当前工作目录
来源：http://dali.yongpay.top/Article/details/gteclrcwng.html

Py:   os.getcwd()
来源：http://dali.guowangkeji.top/Article/details/gtqtnfvpni.html

PHP:  getcwd();
来源：http://dali.wangdashe.top/Article/details/gtiewdhwnc.html

JS:   process.cwd()
来源：http://dali.nanxuanxn.top/Article/details/gtgenkksvy.html

TS:   process.cwd()
来源：http://dali.yj20258.top/Article/details/gtrwdhmvov.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.wangshuangyany.cn/Article/details/gtzjjwtnlp.html

Go:   os.Getwd()
来源：http://dali.cqqwz.cn/Article/details/gtzeoywwaq.html

Ruby: Dir.pwd
来源：http://dali.fengsongda.top/Article/details/gtdiwtxmrn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yanxiufei.cn/Article/details/gtwednymua.html

[M05] 设置退出码
来源：http://dali.shanyushiyangtech.top/Article/details/gtlwzgcmrj.html

Py:   sys.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtnowlogik.html

PHP:  exit(1);
来源：http://dali.havefunace.top/Article/details/gtyhfhzysk.html

JS:   process.exit(1)
来源：http://dali.ybcxt.top/Article/details/gtdqsxjbmh.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtdxlxoyxf.html

Java: System.exit(1)
来源：http://dali.iojbl.cn/Article/details/gtdqrcbjmz.html

Go:   os.Exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtrqqanvmq.html

Ruby: exit 1
来源：http://dali.316326.xyz/Article/details/gtmnuhnhoy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinyuanbaomall.cn/Article/details/gturcwjate.html

[M06] 向标准错误输出
来源：http://dali.hywenlv.cn/Article/details/gtfwxppuuf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinqigfzy.top/Article/details/gtnecljizi.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.haohaochexian.top/Article/details/gttnlapdrl.html

JS:   console.error("err")
来源：http://dali.bjfxy.top/Article/details/gtnwjnaxkj.html

TS:   console.error("err")
来源：http://dali.havefunace.top/Article/details/gthrxmltkt.html

Java: System.err.println("err")
来源：http://dali.daxiang520.top/Article/details/gtolyrrjmd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.fengsongda.top/Article/details/gtwyjyaemu.html

Ruby: warn "err"
来源：http://dali.yj20258888.top/Article/details/gtschrrxvi.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jianghu66.top/Article/details/gtoitqfwxr.html

[M07] 判断是否为主入口
来源：http://dali.shanyushiyangtech.top/Article/details/gtepftehaq.html

Py:   if __name__ == "__main__":
来源：http://dali.shuidangran.top/Article/details/gtomdypafu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinqigfzy.top/Article/details/gtzqmxliag.html

JS:   require.main === module
来源：http://dali.c1oappe.top/Article/details/gthuikapoa.html

TS:   require.main === module
来源：http://dali.gotoacloud.top/Article/details/gthrtmmltr.html

Java: public static void main(String[] args)
来源：http://dali.ppjwa.cn/Article/details/gtijxjcfcn.html

Go:   func main()
来源：http://dali.xuetiantiany.cn/Article/details/gtikzykuor.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenjidiqi.icu/Article/details/gtsoiamnnr.html

C#:   static void Main(string[] args)
来源：http://dali.yuxming.cn/Article/details/gttmkifltb.html

[M08] 获取系统与运行时信息
来源：http://dali.xziqi.cn/Article/details/gtcyosnaax.html

Py:   platform.system();  platform.python_version()
来源：http://dali.fzhhl.top/Article/details/gtsdplwvic.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhongyouzk.top/Article/details/gtdlybfazt.html

JS:   process.platform;  process.version
来源：http://dali.smart0.xyz/Article/details/gtddtlzvzc.html

TS:   process.platform;  process.version
来源：http://dali.hnqzz.top/Article/details/gtfotlczti.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinqigfzy.top/Article/details/gtkohmqchm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.svipenyu.cn/Article/details/gturycdnqs.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jqgfzy.top/Article/details/gtcsoscsvw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xuetiantiany.cn/Article/details/gtlhrqnbhd.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtmryujdyu.html

N. 数据结构与算法
来源：http://dali.quarkkingdee.top/Article/details/gtslngqvcj.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtpdfolbue.html

[N01] 二分查找（有序数组）
来源：http://dali.quarkkingdee.top/Article/details/gtvrdwgqga.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.daria6918.cn/Article/details/gtrnjsaskf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.bjfxy.top/Article/details/gtwxrciyhx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xylfe.cn/Article/details/gtkwopxeje.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.svipenyu.cn/Article/details/gttkujenqh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yongpay.top/Article/details/gtcfexrrlu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtrusqmsyi.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sufxvd.cn/Article/details/gtkushtkjz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.316326.xyz/Article/details/gttbzgbrkr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.dianchejie.cn/Article/details/gtirsvndlx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.snrcjt.cn/Article/details/gtocdgdxkb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nwbrower.top/Article/details/gtmikwavrw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.316326.xyz/Article/details/gttmnxfkza.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.vqdsnc.cn/Article/details/gtwfapvwjg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xuanzx.com/Article/details/gtsipgnaxk.html

Go:   slices.Sort(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtdfzhcclv.html

Ruby: arr.sort
来源：http://dali.jyoumei.cn/Article/details/gtyitjjahd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ppjwa.cn/Article/details/gtrkmnviae.html

[N03] 快速排序（分治示例）
来源：http://dali.guannengcc.top/Article/details/gtevpovoli.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiwmklubj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tian-w.cn/Article/details/gtzpsrjyfm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hnxiangtu.top/Article/details/gtcqjrgvro.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258.top/Article/details/gtxwfpiads.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhoulong.xyz/Article/details/gtaizephyq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sweek.top/Article/details/gtmxpweabf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhixingplan.top/Article/details/gtzqmqbpyf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.haohaochexian.top/Article/details/gtfetaejgp.html

[N04] 斐波那契数列
来源：http://dali.chenlongwang.top/Article/details/gtiljobbwc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258888.top/Article/details/gtjozlgizu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.birdmap.top/Article/details/gtokldyxrn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ehwqpu.com/Article/details/gtartxtjvk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gtqepdktev.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gtffddggby.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.guannengcc.top/Article/details/gtkqijiore.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zycfv.cn/Article/details/gtaetzemyp.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gtptnseuaq.html

[N05] 最大公约数
来源：http://dali.ybcxt.top/Article/details/gtyimiktfv.html

Py:   math.gcd(a, b)
来源：http://dali.yanxiufei.cn/Article/details/gtjyaxaege.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.meibo888.top/Article/details/gtyzmkigwh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.c1oappe.top/Article/details/gtxqpaxqkk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jianghu66.top/Article/details/gtzgfzgnzv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xinyue.icu/Article/details/gtwdzieabp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jlsjyb.cn/Article/details/gtxyizahyr.html

Ruby: a.gcd(b)
来源：http://dali.redwolf501.top/Article/details/gteiqmkgom.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.svipenyu.cn/Article/details/gtcxkowpct.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gtuqwzmulf.html

Py:   s == s[::-1]
来源：http://dali.shzxlz.cn/Article/details/gtkwcghuhd.html

PHP:  $s === strrev($s);
来源：http://dali.yueranfly.top/Article/details/gtaswalzap.html

JS:   s === [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gtogeziune.html

TS:   s === [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gthomiyjig.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jqgfzy.top/Article/details/gtaydsrwmz.html

Go:   // 双指针从两端比较
来源：http://dali.jinqigufen.top/Article/details/gtnfiruvsi.html

Ruby: s == s.reverse
来源：http://dali.wangdashe.top/Article/details/gtveqtlifx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.wangshuangyany.cn/Article/details/gtdnkdobah.html

[N07] 两数之和（返回下标）
来源：http://dali.sxryk.cn/Article/details/gtmxxoscbt.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xziqi.cn/Article/details/gtckttrtdp.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxlbnyrxi.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.chenlongwang.top/Article/details/gtaaryaycg.html

TS:   // 手写 Map<string, number>
来源：http://dali.fengsongda.top/Article/details/gtnwjvwehn.html

Java: // 手写 HashMap
来源：http://dali.hnxiangtu.top/Article/details/gtertzqxva.html

Go:   // 手写 map[int]int
来源：http://dali.xinyue.icu/Article/details/gtlezzkjrs.html

Ruby: // 手写 Hash
来源：http://dali.yj202588.top/Article/details/gtrouldnyh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hammf.cn/Article/details/gtkhvgndzx.html

[N08] 生成全排列
来源：http://dali.yonumen.top/Article/details/gttozzssmj.html

Py:   itertools.permutations(arr)
来源：http://dali.daxiang520.top/Article/details/gthagnjfgl.html

PHP:  // 手写递归交换
来源：http://dali.chenzaomai.com/Article/details/gtnzcydczi.html

JS:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyduskzxy.html

TS:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gtmzgtrkjy.html

Java: // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gtnjmkqypj.html

Go:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gtiqcbvdid.html

Ruby: arr.permutation.to_a
来源：http://dali.yj20258.top/Article/details/gtzramuxhp.html

C#:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gtbnjslgjm.html

[N09] 栈与队列
来源：http://dali.sysykeji.top/Article/details/gtijquxzni.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yuanzhike.top/Article/details/gthomvfbqa.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhengqikj.top/Article/details/gtqumegzpp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jiagoushi.top/Article/details/gtlhiewaoc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.tianlin.xyz/Article/details/gtskoxqcas.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shangyingyoupin.top/Article/details/gtbobxfkpc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhoulong.xyz/Article/details/gtxhvgqpvy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gaohongyu789.top/Article/details/gtqxilyodk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.mhx1999.top/Article/details/gtuhtucblv.html

[N10] 链表节点定义
来源：http://dali.jqgufenzy.top/Article/details/gtkqytpiub.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yuxming.cn/Article/details/gtblojabqk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sufxvd.cn/Article/details/gtvxdinikj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.wangshuangyany.cn/Article/details/gtmgaobhdr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xuanzx.com/Article/details/gtdyvinidf.html

Java: class Node { int v; Node next; }
来源：http://dali.yuanzhike.top/Article/details/gtpuwfqbvf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.svipenyu.cn/Article/details/gtfmhgpoiz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.316326.xyz/Article/details/gtqdrkvwga.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.aibaodan.cn/Article/details/gtpfowekxi.html

[N11] 二叉树中序遍历
来源：http://dali.birdmap.top/Article/details/gtafaupogf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gogol.net.cn/Article/details/gtdmlerylg.html

PHP:  // 手写递归函数
来源：http://dali.guowangkeji.top/Article/details/gtefwughfe.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnqzz.top/Article/details/gtqygpwkeb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aizwys.cn/Article/details/gtcmqujbfg.html

Java: // 手写递归
来源：http://dali.cashguo.top/Article/details/gtvksefrwq.html

Go:   // 手写递归
来源：http://dali.dianchejie.cn/Article/details/gtnjlymfjs.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sufxvd.cn/Article/details/gtnhqpsill.html

C#:   // 手写递归
来源：http://dali.guannengcc.top/Article/details/gtqsitnnxu.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jianghu66.top/Article/details/gtvgbafskc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hfpthk.cn/Article/details/gtcpisqdtg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hywenlv.cn/Article/details/gtenlukxps.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shuidangran.top/Article/details/gtuzwjezuz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.iojbl.cn/Article/details/gtgghtolap.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gogol.net.cn/Article/details/gtzxjslnyq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ybcxt.top/Article/details/gtqxluoolq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.316326.xyz/Article/details/gtknfdevgx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hongshengwenyu.top/Article/details/gtsdnodwpc.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtzhplbedd.html

O. 并发与异步
来源：http://dali.ydzc1.top/Article/details/gtavkhjijz.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtlexowmht.html

[O01] 启动一个线程
来源：http://dali.hysaishi.cn/Article/details/gtfxwnbvxi.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gzhubu.top/Article/details/gtditotbca.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gotoacloud.top/Article/details/gtvveouxxz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yueranfly.top/Article/details/gtfqqyjwis.html

TS:   // 同 JS
来源：http://dali.zhixingplan.top/Article/details/gtnalghlrq.html

Java: new Thread(() -> f()).start()
来源：http://dali.pengpengdd.cyou/Article/details/gtwkqxbaab.html

Go:   go f()
来源：http://dali.daria6918.cn/Article/details/gtzgeaugwf.html

Ruby: Thread.new { f }
来源：http://dali.dashuyun.cn/Article/details/gtmnkshuyg.html

C#:   Task.Run(() => F());
来源：http://dali.feifeiyinyue.top/Article/details/gtvuljvruz.html

[O02] 使用线程池
来源：http://dali.hongshengwenyu.top/Article/details/gticdubjqn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.pycfn.com/Article/details/gtwvkfrowy.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.nanxinkj.top/Article/details/gtobigoafn.html

JS:   // worker_threads 线程池
来源：http://dali.andypj.xyz/Article/details/gtixqthqmv.html

TS:   // worker_threads 线程池
来源：http://dali.yueranfly.top/Article/details/gtabpdmttk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yongpay.top/Article/details/gtotprqpyj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sxryk.cn/Article/details/gtusumixoi.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.quarkkingdee.top/Article/details/gtfsxyruiv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.aibaodan.cn/Article/details/gttfjdxrhr.html

[O03] 加锁保护共享数据
来源：http://dali.yueranfly.top/Article/details/gtmxjrpttj.html

Py:   with lock: shared += 1
来源：http://dali.yangfankeji.com/Article/details/gtcrgthmyu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yongpay.top/Article/details/gtyzjwrvqo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.aizwys.cn/Article/details/gtzrdlymyq.html

TS:   // 同 JS
来源：http://dali.yangfankeji.com/Article/details/gteokluuvt.html

Java: synchronized (this) { shared++; }
来源：http://dali.jqgufenzy.top/Article/details/gtkbzoyoho.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jqgufenzy.top/Article/details/gtrywxtrih.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jiagoushi.top/Article/details/gtdgmkrlji.html

C#:   lock (gate) { shared++; }
来源：http://dali.hongshengwenyu.top/Article/details/gtudikbuje.html

[O04] 定义异步函数并等待
来源：http://dali.jyoumei.cn/Article/details/gtuhctxjkk.html

Py:   async def f():⏎    await g()
来源：http://dali.aizwys.cn/Article/details/gtdaeskhav.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.0kj1m.cn/Article/details/gtttkqpzbq.html

JS:   async function f() { await g(); }
来源：http://dali.cheryme.top/Article/details/gtnjgtekji.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.wangdashe.top/Article/details/gttaelgyve.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.gotoacloud.top/Article/details/gtixmfubby.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cdnleiting.top/Article/details/gtskfgiitp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.pengpengdd.cyou/Article/details/gtbdajilbe.html

C#:   async Task F() { await G(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzwyubgoy.html

[O05] 并发执行并等待全部完成
来源：http://dali.xuanzx.com/Article/details/gtrmunwecm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ppjwa.cn/Article/details/gthjqrrlfx.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.dashuyun.cn/Article/details/gtvfogiqim.html

JS:   await Promise.all(tasks)
来源：http://dali.feifeiyinyue.top/Article/details/gtnyztkcdn.html

TS:   await Promise.all(tasks)
来源：http://dali.jqgfzy.top/Article/details/gtijychbrf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.snrcjt.cn/Article/details/gtdynuthsx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xinyue.icu/Article/details/gtaovooxfz.html

Ruby: threads.map(&:join)
来源：http://dali.yuanzhike.top/Article/details/gtzawzuqkq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yonumen.top/Article/details/gtwtrnjfwu.html


<!-- 参考信息 -->