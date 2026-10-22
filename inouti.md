代发 wailian999

Go:   resp, err := http.Get(url)
来源：http://dali.ybcxt.top/Article/details/gtalxkmjad.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xziqi.cn/Article/details/gtaceabska.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hnqzz.top/Article/details/gtdhghwzdv.html

[L02] 发送 POST JSON
来源：http://dali.vqdsnc.cn/Article/details/gtwuiusavl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.smart0.xyz/Article/details/gtqejesorm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yongpay.top/Article/details/gtmgxunyzo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gotoacloud.top/Article/details/gtnxyqelog.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuetiantiany.cn/Article/details/gtusfuiksw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sufxvd.cn/Article/details/gteuntqhsw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ybcxt.top/Article/details/gtgghrgsts.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hongshengwenyu.top/Article/details/gtnqcctmcv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.guannengcc.top/Article/details/gtkwtyrakx.html

[L03] 设置自定义请求头
来源：http://dali.yongpay.top/Article/details/gtowakytkm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.kuanghao11.cn/Article/details/gtapscngeo.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.fengsongda.top/Article/details/gtyrlbkwvf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aizwys.cn/Article/details/gtchzruhkp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.havefunace.top/Article/details/gtitcawode.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.haohaochexian.top/Article/details/gtwbawuyzd.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.daria6918.cn/Article/details/gtqxobjbeg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.bjfxy.top/Article/details/gtqixslstj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cashguo.top/Article/details/gtyjmdxwxa.html

[L04] 设置超时
来源：http://dali.iojbl.cn/Article/details/gtcjcffdnm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinqigfzy.top/Article/details/gtusdaheug.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.havefunace.top/Article/details/gtfavwfwea.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.svipenyu.cn/Article/details/gtiwazflew.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.0kj1m.cn/Article/details/gtklozqaua.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.daxiang520.top/Article/details/gtxcahyiwf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.haohaochexian.top/Article/details/gtfbecxjqj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhoulong.xyz/Article/details/gtjdhumebl.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cdnleiting.top/Article/details/gtnbhlbqut.html

[L05] 上传文件（multipart）
来源：http://dali.quarkkingdee.top/Article/details/gtxztrgjql.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shangyingyoupin.top/Article/details/gtwqjbjeml.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxpcenfkk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhixingplan.top/Article/details/gtjygjrism.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenzaomai.com/Article/details/gtyixmqipm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sysykeji.top/Article/details/gtqddwqayj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.smart0.xyz/Article/details/gtccqyjinc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sweek.top/Article/details/gtbgluoghx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.fzhhl.top/Article/details/gtrgxwxqhq.html

[L06] 解析响应为 JSON
来源：http://dali.jyoumei.cn/Article/details/gtvceykxme.html

Py:   resp.json()
来源：http://dali.wangdashe.top/Article/details/gtrmqnmjhf.html

PHP:  json_decode($body, true);
来源：http://dali.birdmap.top/Article/details/gtcbtntiwg.html

JS:   await resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gtfanxqvmw.html

TS:   await resp.json()
来源：http://dali.snrcjt.cn/Article/details/gthgngabhb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sufxvd.cn/Article/details/gtkcsluvve.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shuidangran.top/Article/details/gtdirezxni.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xinyue.icu/Article/details/gtuaazlfoe.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.guowangkeji.top/Article/details/gtvxcweszv.html

[L07] 处理 HTTP 状态码
来源：http://dali.cheryme.top/Article/details/gtcehzsens.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpxfsfwxv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.bjfxy.top/Article/details/gtyxodzwyb.html

JS:   resp.ok;  resp.status
来源：http://dali.hysaishi.cn/Article/details/gtdpqgyjws.html

TS:   resp.ok;  resp.status
来源：http://dali.yj20258.top/Article/details/gttrxvwjav.html

Java: resp.statusCode()
来源：http://dali.redwolf501.top/Article/details/gtzmahcaru.html

Go:   resp.StatusCode
来源：http://dali.hnxiangtu.top/Article/details/gtaowiomlc.html

Ruby: resp.code.to_i
来源：http://dali.iojbl.cn/Article/details/gtcnyfnxyo.html

C#:   (int)resp.StatusCode
来源：http://dali.vqdsnc.cn/Article/details/gtpannpdpk.html

[L08] 并发请求多个地址
来源：http://dali.fzhhl.top/Article/details/gtnkdlxwiv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.daxiang520.top/Article/details/gtwmszqzcb.html

PHP:  curl_multi_init() 系列
来源：http://dali.yonumen.top/Article/details/gtkojxkuim.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenlongwang.top/Article/details/gtkgjylphy.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hywenlv.cn/Article/details/gtugaupnup.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.quarkkingdee.top/Article/details/gtgiepgtve.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.haohaochexian.top/Article/details/gtnekvubdy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.birdmap.top/Article/details/gtiaxdwqov.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nanxinkj.top/Article/details/gtwrovjboo.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtydexpigv.html

M. 命令行 / 进程 / 环境
来源：http://dali.iojbl.cn/Article/details/gthqeqmbua.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkmeorgcj.html

[M01] 读取命令行参数
来源：http://dali.hammf.cn/Article/details/gtidaiuytr.html

Py:   sys.argv[1:]
来源：http://dali.jiagoushi.top/Article/details/gtsckkcook.html

PHP:  $argv;  $argc;
来源：http://dali.guannengcc.top/Article/details/gtavrodwmp.html

JS:   process.argv.slice(2)
来源：http://dali.hammf.cn/Article/details/gtrnchsnbq.html

TS:   process.argv.slice(2)
来源：http://dali.yuxming.cn/Article/details/gtskdgvsuh.html

Java: args 数组（main 方法参数）
来源：http://dali.gzhubu.top/Article/details/gtzhfistao.html

Go:   os.Args[1:]
来源：http://dali.svipenyu.cn/Article/details/gtllxycebj.html

Ruby: ARGV
来源：http://dali.nwbrower.top/Article/details/gtccnubqzd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ppjwa.cn/Article/details/gtbxkzryie.html

[M02] 读取环境变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgfuhjpek.html

Py:   os.environ.get("HOME")
来源：http://dali.wangdashe.top/Article/details/gtzbrjcozp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.guannengcc.top/Article/details/gtqsiffrjm.html

JS:   process.env.HOME
来源：http://dali.zhoulong.xyz/Article/details/gtgbtgtjrj.html

TS:   process.env.HOME
来源：http://dali.xuanzx.com/Article/details/gtgqjuffol.html

Java: System.getenv("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgddvgibe.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gogol.net.cn/Article/details/gtbdpngqmz.html

Ruby: ENV["HOME"]
来源：http://dali.shzxlz.cn/Article/details/gtykehsxdb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.guowangkeji.top/Article/details/gthfzxhekn.html

[M03] 执行外部命令
来源：http://dali.ppjwa.cn/Article/details/gtjzkqfhus.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cucudq.cn/Article/details/gtzvfknayw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hysaishi.cn/Article/details/gtuwufozkp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yanxiufei.cn/Article/details/gtqariwsku.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gtmpxyhmdy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.fzhhl.top/Article/details/gtzteqtrtq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hammf.cn/Article/details/gtzdtyiolq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yuanzhike.top/Article/details/gtzgztwijo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hysaishi.cn/Article/details/gtdisubgyk.html

[M04] 获取当前工作目录
来源：http://dali.yueranfly.top/Article/details/gtuzbugriy.html

Py:   os.getcwd()
来源：http://dali.jlsjyb.cn/Article/details/gtvuazugsh.html

PHP:  getcwd();
来源：http://dali.jinghuilouyu.cn/Article/details/gtwkogxkcp.html

JS:   process.cwd()
来源：http://dali.yj20258888.top/Article/details/gtcfjefaew.html

TS:   process.cwd()
来源：http://dali.tianlin.xyz/Article/details/gthyhfgcsa.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jqgufenzy.top/Article/details/gtveygszwo.html

Go:   os.Getwd()
来源：http://dali.c1oappe.top/Article/details/gtzldxhctz.html

Ruby: Dir.pwd
来源：http://dali.jqgufenzy.top/Article/details/gttasfjazf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpwwtuklt.html

[M05] 设置退出码
来源：http://dali.shangyingyoupin.top/Article/details/gtfgpgxmdh.html

Py:   sys.exit(1)
来源：http://dali.iojbl.cn/Article/details/gtyoasfawa.html

PHP:  exit(1);
来源：http://dali.daria6918.cn/Article/details/gtbazybsrk.html

JS:   process.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtsojyrgqb.html

TS:   process.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gthxhdjngz.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtivcpvzda.html

Go:   os.Exit(1)
来源：http://dali.andypj.xyz/Article/details/gtstslvfyj.html

Ruby: exit 1
来源：http://dali.smart0.xyz/Article/details/gtwlyabnsg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj20258888.top/Article/details/gtgwsnhqgr.html

[M06] 向标准错误输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtemovtgdm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.fengsongda.top/Article/details/gtszawsoxq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jqgfzy.top/Article/details/gtnmmrlorn.html

JS:   console.error("err")
来源：http://dali.tian-w.cn/Article/details/gtjcaqdvlw.html

TS:   console.error("err")
来源：http://dali.xinyue.icu/Article/details/gtarqwdxzi.html

Java: System.err.println("err")
来源：http://dali.yvedp.cn/Article/details/gtrhcelnic.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtyvpevpfp.html

Ruby: warn "err"
来源：http://dali.guowangkeji.top/Article/details/gtynkiazjq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cheryme.top/Article/details/gtpuewestc.html

[M07] 判断是否为主入口
来源：http://dali.jqgfzy.top/Article/details/gtexevzjim.html

Py:   if __name__ == "__main__":
来源：http://dali.yj20258888.top/Article/details/gtvxqvcswf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.birdmap.top/Article/details/gtxyhiavxk.html

JS:   require.main === module
来源：http://dali.zhoulong.xyz/Article/details/gtaivgqajt.html

TS:   require.main === module
来源：http://dali.tianlin.xyz/Article/details/gtgxruhyop.html

Java: public static void main(String[] args)
来源：http://dali.pycfn.com/Article/details/gtrbhketoj.html

Go:   func main()
来源：http://dali.dianchejie.cn/Article/details/gtvijbycjy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.feifeiyinyue.top/Article/details/gtlrsjrdtu.html

C#:   static void Main(string[] args)
来源：http://dali.chenjidiqi.icu/Article/details/gtdjcvwmrw.html

[M08] 获取系统与运行时信息
来源：http://dali.yvedp.cn/Article/details/gtmxhdqfes.html

Py:   platform.system();  platform.python_version()
来源：http://dali.fzhhl.top/Article/details/gtmcrxxtpl.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hysaishi.cn/Article/details/gtgrfttmtw.html

JS:   process.platform;  process.version
来源：http://dali.tanke756.top/Article/details/gtiqexyntv.html

TS:   process.platform;  process.version
来源：http://dali.jinqigfzy.top/Article/details/gtidriielq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.chenzaomai.com/Article/details/gtxrydxswe.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvqlomkrw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.chenzaomai.com/Article/details/gtsvmekpux.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhongyouzk.top/Article/details/gtskvwmjet.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtyzyvchhq.html

N. 数据结构与算法
来源：http://dali.daxiang520.top/Article/details/gtxsxckmdz.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gthomifefa.html

[N01] 二分查找（有序数组）
来源：http://dali.hnqzz.top/Article/details/gtwrgvgget.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.iojbl.cn/Article/details/gtmnyeahns.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.redwolf501.top/Article/details/gtpfowcdey.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.0kj1m.cn/Article/details/gtbnvpstwc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangdashe.top/Article/details/gtzaksueby.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtaeyszbws.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gtxvufvlpm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.aibaodan.cn/Article/details/gtlfowogfu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtxftrvcdq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nanxuanxn.top/Article/details/gtwffybjrv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.havefunace.top/Article/details/gtmqzpwjzx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.iojbl.cn/Article/details/gtbpuqpgwx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.haohaochexian.top/Article/details/gtnqeuqwzm.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shzxlz.cn/Article/details/gtcpekodyy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yonumen.top/Article/details/gtqzphdqyl.html

Go:   slices.Sort(arr)
来源：http://dali.andypj.xyz/Article/details/gtjfzczsqg.html

Ruby: arr.sort
来源：http://dali.hongshengwenyu.top/Article/details/gtjqrnwudk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.wangshuangyany.cn/Article/details/gtxkfedmsu.html

[N03] 快速排序（分治示例）
来源：http://dali.birdmap.top/Article/details/gtjxaflwyf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hfpthk.cn/Article/details/gtqvxeetjf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.fzhhl.top/Article/details/gtqhdjrjhv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.feifeiyinyue.top/Article/details/gtopguwykk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yueranfly.top/Article/details/gttohapgxv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhixingplan.top/Article/details/gtviabbzdu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gaohongyu789.top/Article/details/gtuhkpalih.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gaohongyu789.top/Article/details/gtjurqhfss.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cdnleiting.top/Article/details/gtbdjkpaxt.html

[N04] 斐波那契数列
来源：http://dali.jyoumei.cn/Article/details/gtxpzcljmh.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfmhfyomm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.tian-w.cn/Article/details/gtsnywlcke.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ybcxt.top/Article/details/gtvhjuxixq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gtnkkzripy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xuetiantiany.cn/Article/details/gtwakhghyz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.fengsongda.top/Article/details/gtrkbqyluq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.mhx1999.top/Article/details/gtbygoqlwo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gteiltteqv.html

[N05] 最大公约数
来源：http://dali.hnqzz.top/Article/details/gtxpwfmvno.html

Py:   math.gcd(a, b)
来源：http://dali.nanxinkj.top/Article/details/gtbaucqzhp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xinyue.icu/Article/details/gtkgytdjud.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtflogojmt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hammf.cn/Article/details/gttskhhqlm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.mhx1999.top/Article/details/gtcunpeylu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnjxbjfvn.html

Ruby: a.gcd(b)
来源：http://dali.feifeiyinyue.top/Article/details/gtjlpjkfsz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.bjfxy.top/Article/details/gtaeubqrjt.html

[N06] 判断回文字符串
来源：http://dali.gzhubu.top/Article/details/gtubjqvxxl.html

Py:   s == s[::-1]
来源：http://dali.gzhubu.top/Article/details/gtcwfcecgy.html

PHP:  $s === strrev($s);
来源：http://dali.xuanzx.com/Article/details/gtrcmdhpyl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gtkcrwzalo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gtebfrexbf.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sweek.top/Article/details/gtyxanyrbg.html

Go:   // 双指针从两端比较
来源：http://dali.jianghu66.top/Article/details/gtcqxyjvim.html

Ruby: s == s.reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcyklyokj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yj20258888.top/Article/details/gtbreafdke.html

[N07] 两数之和（返回下标）
来源：http://dali.chenzaomai.com/Article/details/gthftrhkhl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.snrcjt.cn/Article/details/gtkllyegfd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shangyingyoupin.top/Article/details/gtzinxubkc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.guowangkeji.top/Article/details/gtyntebedy.html

TS:   // 手写 Map<string, number>
来源：http://dali.haohaochexian.top/Article/details/gtasodhdmh.html

Java: // 手写 HashMap
来源：http://dali.aizwys.cn/Article/details/gtjqzvkeai.html

Go:   // 手写 map[int]int
来源：http://dali.hfpthk.cn/Article/details/gtawykfowo.html

Ruby: // 手写 Hash
来源：http://dali.sysykeji.top/Article/details/gtyqdqbtcc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yangfankeji.com/Article/details/gttdragfan.html

[N08] 生成全排列
来源：http://dali.cashguo.top/Article/details/gtpjggdrgm.html

Py:   itertools.permutations(arr)
来源：http://dali.sufxvd.cn/Article/details/gthcbzdkih.html

PHP:  // 手写递归交换
来源：http://dali.ehwqpu.com/Article/details/gtfgropwmf.html

JS:   // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gtasubvjpl.html

TS:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtzqsnihky.html

Java: // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gttvnfqblz.html

Go:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtbqybszrs.html

Ruby: arr.permutation.to_a
来源：http://dali.9152youxi.cn/Article/details/gtjothqpsa.html

C#:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsrirslpx.html

[N09] 栈与队列
来源：http://dali.yueranfly.top/Article/details/gtqwxplhli.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hywenlv.cn/Article/details/gtgpgwdxmy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.havefunace.top/Article/details/gtwrlhcwtc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.svipenyu.cn/Article/details/gtyvteusiu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.havefunace.top/Article/details/gtkbsrzwnq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sweek.top/Article/details/gtywuhuljn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yangfankeji.com/Article/details/gtvqskotke.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.tian-w.cn/Article/details/gtbsxaugkg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.birdmap.top/Article/details/gtmnfizaaa.html

[N10] 链表节点定义
来源：http://dali.jinqigufen.top/Article/details/gtssznkhgo.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yangfankeji.com/Article/details/gtthyutlaw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yj202588.top/Article/details/gtostslkgg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yvedp.cn/Article/details/gtfcfvhvgq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gogol.net.cn/Article/details/gtddxmlcfz.html

Java: class Node { int v; Node next; }
来源：http://dali.gaohongyu789.top/Article/details/gtckyvjobr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cashguo.top/Article/details/gtyphctdxy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.chenjidiqi.icu/Article/details/gtgiumpnrt.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.wangdashe.top/Article/details/gtjasocyzd.html

[N11] 二叉树中序遍历
来源：http://dali.haohaochexian.top/Article/details/gthuicqjvq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xziqi.cn/Article/details/gttdkhdtos.html

PHP:  // 手写递归函数
来源：http://dali.kuanghao11.cn/Article/details/gthsftnmfo.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yvedp.cn/Article/details/gtxvobutte.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yanxiufei.cn/Article/details/gtkfxvobxu.html

Java: // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gtuoscheun.html

Go:   // 手写递归
来源：http://dali.yueranfly.top/Article/details/gtlcikvriz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ybcxt.top/Article/details/gtprueucfc.html

C#:   // 手写递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjkabguiq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.chenzaomai.com/Article/details/gtfjnctzfa.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhengqikj.top/Article/details/gteqqudann.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinqigfzy.top/Article/details/gtawywfswz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hywenlv.cn/Article/details/gtpwswmycz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cucudq.cn/Article/details/gtsirfwysc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yanxiufei.cn/Article/details/gtyepowyjf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sufxvd.cn/Article/details/gtpxptkdbi.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sweek.top/Article/details/gtqaudoiry.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yvedp.cn/Article/details/gtdfuwvrvf.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtzfcuzieo.html

O. 并发与异步
来源：http://dali.shanyushiyangtech.top/Article/details/gtbaweczfm.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtvykykoba.html

[O01] 启动一个线程
来源：http://dali.redwolf501.top/Article/details/gtyckycpgr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.fengsongda.top/Article/details/gtyfqhfewu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shzxlz.cn/Article/details/gtuxhzjnzi.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yangfankeji.com/Article/details/gtvbydybul.html

TS:   // 同 JS
来源：http://dali.fzhhl.top/Article/details/gtriscwlmg.html

Java: new Thread(() -> f()).start()
来源：http://dali.vqdsnc.cn/Article/details/gtrcoqjwwe.html

Go:   go f()
来源：http://dali.cashguo.top/Article/details/gtshnzzjaw.html

Ruby: Thread.new { f }
来源：http://dali.xziqi.cn/Article/details/gteckcbpsq.html

C#:   Task.Run(() => F());
来源：http://dali.hongshengwenyu.top/Article/details/gtjrbvombc.html

[O02] 使用线程池
来源：http://dali.nanxuanxn.top/Article/details/gtyxuufeql.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinqigufen.top/Article/details/gtuibfhsvh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hywenlv.cn/Article/details/gtmtgzrymz.html

JS:   // worker_threads 线程池
来源：http://dali.jlsjyb.cn/Article/details/gterfngwdc.html

TS:   // worker_threads 线程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfrajghwt.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.nanxuanxn.top/Article/details/gtwrejebho.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.tanke756.top/Article/details/gtzadwfdvo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhongyouzk.top/Article/details/gtdivrpkxc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.nanxinkj.top/Article/details/gturqzioxc.html

[O03] 加锁保护共享数据
来源：http://dali.yonumen.top/Article/details/gtnyfowodp.html

Py:   with lock: shared += 1
来源：http://dali.hnxiangtu.top/Article/details/gtzgdkzrvm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.snrcjt.cn/Article/details/gtobtgyofi.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.svipenyu.cn/Article/details/gtwxudntws.html

TS:   // 同 JS
来源：http://dali.hfpthk.cn/Article/details/gtuqcgmqgx.html

Java: synchronized (this) { shared++; }
来源：http://dali.jianghu66.top/Article/details/gtcqskqral.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yvedp.cn/Article/details/gtbdhffwbt.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cucudq.cn/Article/details/gtwsahyeki.html

C#:   lock (gate) { shared++; }
来源：http://dali.sxryk.cn/Article/details/gtegpoukne.html

[O04] 定义异步函数并等待
来源：http://dali.cashguo.top/Article/details/gtnscutovo.html

Py:   async def f():⏎    await g()
来源：http://dali.cheryme.top/Article/details/gtsmgjsaja.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.aizwys.cn/Article/details/gtfabvxjqs.html

JS:   async function f() { await g(); }
来源：http://dali.sysykeji.top/Article/details/gtgeckoidw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.snrcjt.cn/Article/details/gtwmjwxxew.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shanyushiyangtech.top/Article/details/gthmokmebx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shanyushiyangkeji.top/Article/details/gtginnrkhd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xziqi.cn/Article/details/gtxzfjrrgl.html

C#:   async Task F() { await G(); }
来源：http://dali.zycfv.cn/Article/details/gtkfwdhwln.html

[O05] 并发执行并等待全部完成
来源：http://dali.sweek.top/Article/details/gtvzofuztf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhoulong.xyz/Article/details/gtxuplbtyi.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yongpay.top/Article/details/gtzyzzxvej.html

JS:   await Promise.all(tasks)
来源：http://dali.zdqjudy.top/Article/details/gtncklzgdw.html

TS:   await Promise.all(tasks)
来源：http://dali.gogol.net.cn/Article/details/gtghethbyu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xuanzx.com/Article/details/gtylgrzizj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jiagoushi.top/Article/details/gtumtrajaa.html

Ruby: threads.map(&:join)
来源：http://dali.iojbl.cn/Article/details/gtehoeosmf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xuanzx.com/Article/details/gtthusmkbt.html


<!-- 参考信息 -->