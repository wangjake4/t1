代发 wailian999

Py:   requests.post(url, json={"a": 1})
来源：http://dali.svipenyu.cn/Article/details/gtgysroofv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.havefunace.top/Article/details/gtyjzgyifd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangdashe.top/Article/details/gtdxcfzgfb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ivvv.top/Article/details/gtpylmrpyl.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhoulong.xyz/Article/details/gtzlphvacr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jqgfzy.top/Article/details/gtjhahatms.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinqigufen.top/Article/details/gtsiwurdos.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gaohongyu789.top/Article/details/gtwxgbsfnh.html

[L03] 设置自定义请求头
来源：http://dali.shangyingyoupin.top/Article/details/gtlcubvdtu.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gzhubu.top/Article/details/gtmkhnyyom.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.daria6918.cn/Article/details/gtkhinjbmi.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xinyue.icu/Article/details/gtnlbpfqdv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.iojbl.cn/Article/details/gtcvsisksm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.snrcjt.cn/Article/details/gtmcmuudmh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hongshengwenyu.top/Article/details/gtpkxxiflr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzaqnojlq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.chenzaomai.com/Article/details/gtoobgblxr.html

[L04] 设置超时
来源：http://dali.aibaodan.cn/Article/details/gtmbvbxqvg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.0kj1m.cn/Article/details/gtxcvbqiqe.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.9152youxi.cn/Article/details/gtwnnllkhf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tanke756.top/Article/details/gtixwmntln.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhixingplan.top/Article/details/gtiygwmsyn.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sufxvd.cn/Article/details/gtmzozpzaz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zycfv.cn/Article/details/gtvgjunkcx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cqqwz.cn/Article/details/gtwlvrdwzq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinqigufen.top/Article/details/gtjzmaavre.html

[L05] 上传文件（multipart）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtklodvbqo.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cashguo.top/Article/details/gtriswaomg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hongshengwenyu.top/Article/details/gtuiyzpwxu.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.smart0.xyz/Article/details/gtrxqwsphq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.0kj1m.cn/Article/details/gtwvgtcyvx.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yj20258888.top/Article/details/gtglbqhctt.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhiwuduotai.top/Article/details/gtmczggnes.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hnqzz.top/Article/details/gtredutglt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cdnleiting.top/Article/details/gttieuplze.html

[L06] 解析响应为 JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthrloffdn.html

Py:   resp.json()
来源：http://dali.cdnleiting.top/Article/details/gtqxgjdwqp.html

PHP:  json_decode($body, true);
来源：http://dali.andypj.xyz/Article/details/gtsxyobvmk.html

JS:   await resp.json()
来源：http://dali.jiagoushi.top/Article/details/gtbstwrgnr.html

TS:   await resp.json()
来源：http://dali.xinyue.icu/Article/details/gtgunnhsiw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.meibo888.top/Article/details/gtxfbnwldu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.guannengcc.top/Article/details/gtdnjcpegw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.aizwys.cn/Article/details/gtermvsopc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinqigfzy.top/Article/details/gttqscigek.html

[L07] 处理 HTTP 状态码
来源：http://dali.zdqjudy.top/Article/details/gtgekokdig.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cheryme.top/Article/details/gtzbnenbzu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sweek.top/Article/details/gtljsdywgu.html

JS:   resp.ok;  resp.status
来源：http://dali.ywan-chungtsiang.top/Article/details/gttmljpdxc.html

TS:   resp.ok;  resp.status
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzdjoaxfe.html

Java: resp.statusCode()
来源：http://dali.dianchejie.cn/Article/details/gtkpzvvdli.html

Go:   resp.StatusCode
来源：http://dali.xuanzx.com/Article/details/gtfcdgxpsj.html

Ruby: resp.code.to_i
来源：http://dali.gotoacloud.top/Article/details/gtvufjdoce.html

C#:   (int)resp.StatusCode
来源：http://dali.zhongyouzk.top/Article/details/gtlkugthjc.html

[L08] 并发请求多个地址
来源：http://dali.yuxming.cn/Article/details/gtqnmkcroy.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shanyushiyangkeji.top/Article/details/gtycpvnmet.html

PHP:  curl_multi_init() 系列
来源：http://dali.316326.xyz/Article/details/gtvtvubeot.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ydzc1.top/Article/details/gttneykwaw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jiagoushi.top/Article/details/gtagulprqs.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xinyue.icu/Article/details/gtakkcddjh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gaohongyu789.top/Article/details/gtkcimutnt.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cqqwz.cn/Article/details/gtygdstjdw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.316326.xyz/Article/details/gtkgxaodps.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtyvwbgzvr.html

M. 命令行 / 进程 / 环境
来源：http://dali.cqqwz.cn/Article/details/gtgivyyvga.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtalvurfae.html

[M01] 读取命令行参数
来源：http://dali.jinqigfzy.top/Article/details/gtrmbaqmkq.html

Py:   sys.argv[1:]
来源：http://dali.zhixingplan.top/Article/details/gtdryanytn.html

PHP:  $argv;  $argc;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxbuukiu.html

JS:   process.argv.slice(2)
来源：http://dali.chenjidiqi.icu/Article/details/gtztknoaos.html

TS:   process.argv.slice(2)
来源：http://dali.snrcjt.cn/Article/details/gtziqopzak.html

Java: args 数组（main 方法参数）
来源：http://dali.pengpengdd.cyou/Article/details/gtrtwrjtjj.html

Go:   os.Args[1:]
来源：http://dali.jinqigufen.top/Article/details/gtxqvqznmv.html

Ruby: ARGV
来源：http://dali.jinqigfzy.top/Article/details/gterqpzmyi.html

C#:   args 数组（Main 方法参数）
来源：http://dali.birdmap.top/Article/details/gteromjvwt.html

[M02] 读取环境变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxdhujaaq.html

Py:   os.environ.get("HOME")
来源：http://dali.snrcjt.cn/Article/details/gtfleecbfd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shanyushiyangtech.top/Article/details/gteyegrqkg.html

JS:   process.env.HOME
来源：http://dali.cqqwz.cn/Article/details/gtmbsiczrk.html

TS:   process.env.HOME
来源：http://dali.shzxlz.cn/Article/details/gtisqcdxiu.html

Java: System.getenv("HOME")
来源：http://dali.hammf.cn/Article/details/gttppnbxan.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenlongwang.top/Article/details/gtrissowxa.html

Ruby: ENV["HOME"]
来源：http://dali.jyoumei.cn/Article/details/gtkxrcfzsl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zycfv.cn/Article/details/gtvuqnndyp.html

[M03] 执行外部命令
来源：http://dali.yj20258888.top/Article/details/gtrvrgqjyq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.guowangkeji.top/Article/details/gtarnfgfuq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.mhx1999.top/Article/details/gtnbyqebkl.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cheryme.top/Article/details/gtnmltlnpe.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258.top/Article/details/gtbtvyafgr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sweek.top/Article/details/gtvnqznngp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jianghu66.top/Article/details/gtuwahqecj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.dianchejie.cn/Article/details/gtnjxslahq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jqgufenzy.top/Article/details/gtxsdclevj.html

[M04] 获取当前工作目录
来源：http://dali.yj20258888.top/Article/details/gtevkooich.html

Py:   os.getcwd()
来源：http://dali.sxryk.cn/Article/details/gtuheqgwmo.html

PHP:  getcwd();
来源：http://dali.dianchejie.cn/Article/details/gtocpjctty.html

JS:   process.cwd()
来源：http://dali.fengsongda.top/Article/details/gtwprrvilg.html

TS:   process.cwd()
来源：http://dali.zhengqikj.top/Article/details/gtvmqbnwxt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shzxlz.cn/Article/details/gthcrodmpz.html

Go:   os.Getwd()
来源：http://dali.smart0.xyz/Article/details/gtgdphsuuh.html

Ruby: Dir.pwd
来源：http://dali.svipenyu.cn/Article/details/gtzaqpfhsc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yonumen.top/Article/details/gtrfcfhsyg.html

[M05] 设置退出码
来源：http://dali.dashuyun.cn/Article/details/gtwpandktq.html

Py:   sys.exit(1)
来源：http://dali.jianghu66.top/Article/details/gtjxnzgioj.html

PHP:  exit(1);
来源：http://dali.fzhhl.top/Article/details/gtrdiaanxv.html

JS:   process.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyosxtpxm.html

TS:   process.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtezamcutv.html

Java: System.exit(1)
来源：http://dali.yueranfly.top/Article/details/gtwqjldktg.html

Go:   os.Exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gtjxafnhdy.html

Ruby: exit 1
来源：http://dali.sxryk.cn/Article/details/gtuhrgnetx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.fengsongda.top/Article/details/gtdzvxvvke.html

[M06] 向标准错误输出
来源：http://dali.sysykeji.top/Article/details/gtqhfsttou.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xuanzx.com/Article/details/gtwktodznb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xuetiantiany.cn/Article/details/gtrnbmystl.html

JS:   console.error("err")
来源：http://dali.yongpay.top/Article/details/gtylzjblzf.html

TS:   console.error("err")
来源：http://dali.c1oappe.top/Article/details/gtkbuphkzl.html

Java: System.err.println("err")
来源：http://dali.ybcxt.top/Article/details/gtajopvycq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtczkoqnkn.html

Ruby: warn "err"
来源：http://dali.yonumen.top/Article/details/gtafwskoeh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.aibaodan.cn/Article/details/gtgzpyekhz.html

[M07] 判断是否为主入口
来源：http://dali.ydzc1.top/Article/details/gtsggjkmhu.html

Py:   if __name__ == "__main__":
来源：http://dali.dashuyun.cn/Article/details/gtmvzzbire.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.pycfn.com/Article/details/gtqfxpbbkf.html

JS:   require.main === module
来源：http://dali.daxiang520.top/Article/details/gtkedpzwls.html

TS:   require.main === module
来源：http://dali.meibo888.top/Article/details/gtajkqwjog.html

Java: public static void main(String[] args)
来源：http://dali.bjfxy.top/Article/details/gtvzdcdhqs.html

Go:   func main()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjhybjozm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinghuilouyu.cn/Article/details/gtqfbzvdks.html

C#:   static void Main(string[] args)
来源：http://dali.hnqzz.top/Article/details/gtfcgciddl.html

[M08] 获取系统与运行时信息
来源：http://dali.tianlin.xyz/Article/details/gtdpazmmnd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhengqikj.top/Article/details/gtndnioxwh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hfpthk.cn/Article/details/gtwzdmrxed.html

JS:   process.platform;  process.version
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmoxzoxfd.html

TS:   process.platform;  process.version
来源：http://dali.sxryk.cn/Article/details/gtnagytubw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xziqi.cn/Article/details/gtjssbvure.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.havefunace.top/Article/details/gtdinzowlb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.feifeiyinyue.top/Article/details/gtoqxgqsot.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.c1oappe.top/Article/details/gtimmerout.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxmgkdljy.html

N. 数据结构与算法
来源：http://dali.ehwqpu.com/Article/details/gtzygzhmjt.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtfeqsodni.html

[N01] 二分查找（有序数组）
来源：http://dali.shanyushiyangtech.top/Article/details/gtimllitwg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtacvewmxg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xylfe.cn/Article/details/gtnvledysl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tanke756.top/Article/details/gtizezexwj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangdashe.top/Article/details/gtrtbwynsz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtnvgscvef.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gtmzzfnrwf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hywenlv.cn/Article/details/gtxvmbnlix.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.havefunace.top/Article/details/gtacbzsafz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.316326.xyz/Article/details/gtovxvmseu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.316326.xyz/Article/details/gtwucdnzjd.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.wangdashe.top/Article/details/gtylvifpkh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gtimlcgbee.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cqqwz.cn/Article/details/gttesmhyzj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.guowangkeji.top/Article/details/gtkgcvszpz.html

Go:   slices.Sort(arr)
来源：http://dali.c1oappe.top/Article/details/gthmkiqzkl.html

Ruby: arr.sort
来源：http://dali.hongshengwenyu.top/Article/details/gtteuwsrxl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gtpaqttkwp.html

[N03] 快速排序（分治示例）
来源：http://dali.shanyushiyangkeji.top/Article/details/gttvwvopls.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.iojbl.cn/Article/details/gtkuopvtop.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jqgufenzy.top/Article/details/gttzokrwik.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pengpengdd.cyou/Article/details/gtnnwklzla.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dashuyun.cn/Article/details/gtwtdfyfat.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.kuanghao11.cn/Article/details/gtsxevzmjg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhoulong.xyz/Article/details/gtcnkygevl.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.wangdashe.top/Article/details/gtxnlwlkhb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sxryk.cn/Article/details/gtjqrmeaca.html

[N04] 斐波那契数列
来源：http://dali.haohaochexian.top/Article/details/gtlkusvqum.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.dashuyun.cn/Article/details/gttvxxcbhu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhixingplan.top/Article/details/gtyujelqtr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jyoumei.cn/Article/details/gtiyyuefta.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cdnleiting.top/Article/details/gtbfmbdhgg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yongpay.top/Article/details/gttgxunqdw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenzaomai.com/Article/details/gtcfmsfeqz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hysaishi.cn/Article/details/gtpzmbgxwn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gteldxvoce.html

[N05] 最大公约数
来源：http://dali.dianchejie.cn/Article/details/gtpeyziuxr.html

Py:   math.gcd(a, b)
来源：http://dali.gotoacloud.top/Article/details/gtdghohfry.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinqigfzy.top/Article/details/gtvnzyepky.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jianghu66.top/Article/details/gtxqffmzxk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ybcxt.top/Article/details/gtzumllwlf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shanyushiyangtech.top/Article/details/gthirjufes.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjdaaugnz.html

Ruby: a.gcd(b)
来源：http://dali.yanxiufei.cn/Article/details/gtwrdarcle.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hammf.cn/Article/details/gtgnpyucwo.html

[N06] 判断回文字符串
来源：http://dali.yangfankeji.com/Article/details/gtoipzqpag.html

Py:   s == s[::-1]
来源：http://dali.sxryk.cn/Article/details/gtpzffjpku.html

PHP:  $s === strrev($s);
来源：http://dali.jianghu66.top/Article/details/gteqvkrejh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gtykymglfj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gtclrreaqh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hongshengwenyu.top/Article/details/gtgsexflop.html

Go:   // 双指针从两端比较
来源：http://dali.pycfn.com/Article/details/gthpkmakah.html

Ruby: s == s.reverse
来源：http://dali.shuidangran.top/Article/details/gtpztsglyn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ivvv.top/Article/details/gtpzqrztoj.html

[N07] 两数之和（返回下标）
来源：http://dali.aizwys.cn/Article/details/gtdkqurzzd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.fzhhl.top/Article/details/gtepasyrjo.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yueranfly.top/Article/details/gtwhkpiovu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yongpay.top/Article/details/gtfpvdmtdh.html

TS:   // 手写 Map<string, number>
来源：http://dali.zycfv.cn/Article/details/gtriqqeufe.html

Java: // 手写 HashMap
来源：http://dali.9152youxi.cn/Article/details/gtdhbsrfju.html

Go:   // 手写 map[int]int
来源：http://dali.gogol.net.cn/Article/details/gtrmzikhzj.html

Ruby: // 手写 Hash
来源：http://dali.smart0.xyz/Article/details/gtutvzziaf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinghuilouyu.cn/Article/details/gtxgqtucko.html

[N08] 生成全排列
来源：http://dali.yangfankeji.com/Article/details/gtgadcujii.html

Py:   itertools.permutations(arr)
来源：http://dali.havefunace.top/Article/details/gtbahaxlah.html

PHP:  // 手写递归交换
来源：http://dali.kuanghao11.cn/Article/details/gtibxuhrvj.html

JS:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gtlattlsol.html

TS:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtdnlbnqtl.html

Java: // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtnyvwqbdj.html

Go:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gtcbvlwudf.html

Ruby: arr.permutation.to_a
来源：http://dali.316326.xyz/Article/details/gtwrzdfziq.html

C#:   // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gthecgibke.html

[N09] 栈与队列
来源：http://dali.pengpengdd.cyou/Article/details/gtvmzbyqwf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.nanxuanxn.top/Article/details/gttxdfqloy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gtzrhrnfol.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.bjfxy.top/Article/details/gtysxqcaih.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cqqwz.cn/Article/details/gtyuffnmyv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ybcxt.top/Article/details/gtnmuodhdt.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cheryme.top/Article/details/gtakcztfru.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.birdmap.top/Article/details/gtsynfdcax.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.pycfn.com/Article/details/gtgomxpmro.html

[N10] 链表节点定义
来源：http://dali.jqgufenzy.top/Article/details/gtyhnyprlw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbviefoeh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.fzhhl.top/Article/details/gtlhrdgurh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ivvv.top/Article/details/gtglbhixeo.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.haohaochexian.top/Article/details/gtfkybifzi.html

Java: class Node { int v; Node next; }
来源：http://dali.hywenlv.cn/Article/details/gtclcomqkz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yangfankeji.com/Article/details/gteasspdtt.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yvedp.cn/Article/details/gtdcgdcfwz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.guowangkeji.top/Article/details/gtpwqpwplc.html

[N11] 二叉树中序遍历
来源：http://dali.xuanzx.com/Article/details/gtugmhtiox.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cashguo.top/Article/details/gtkgaqiqok.html

PHP:  // 手写递归函数
来源：http://dali.fzhhl.top/Article/details/gtjbhtdecd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cdnleiting.top/Article/details/gthrqiaztl.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuanzhike.top/Article/details/gtkualecmx.html

Java: // 手写递归
来源：http://dali.dianchejie.cn/Article/details/gtuwfhxzwt.html

Go:   // 手写递归
来源：http://dali.chenzaomai.com/Article/details/gtjxkqfilp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yj202588.top/Article/details/gtkqbhfhmv.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gtbzmysnpf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.feifeiyinyue.top/Article/details/gtsthsxaqe.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cdnleiting.top/Article/details/gtfdooqbos.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xylfe.cn/Article/details/gtrusdbkhq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinqigufen.top/Article/details/gttmnzbbem.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.iojbl.cn/Article/details/gtapweprqt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.birdmap.top/Article/details/gtjdwweibc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cucudq.cn/Article/details/gtbpjqcbds.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.haohaochexian.top/Article/details/gtgsaeysuy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shangyingyoupin.top/Article/details/gtirbmfsak.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtcdafhgrk.html

O. 并发与异步
来源：http://dali.aibaodan.cn/Article/details/gtwgnerpnj.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtdcnmmjfk.html

[O01] 启动一个线程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtprxydfjv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yuanzhike.top/Article/details/gtsipsvnkv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtvnxptbax.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ivvv.top/Article/details/gteilcpbzf.html

TS:   // 同 JS
来源：http://dali.ydzc1.top/Article/details/gteljlvtrz.html

Java: new Thread(() -> f()).start()
来源：http://dali.ppjwa.cn/Article/details/gtgqafdeks.html

Go:   go f()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuccbvemv.html

Ruby: Thread.new { f }
来源：http://dali.jinqigfzy.top/Article/details/gtejhhgcht.html

C#:   Task.Run(() => F());
来源：http://dali.pycfn.com/Article/details/gtsrurtggn.html

[O02] 使用线程池
来源：http://dali.nanxuanxn.top/Article/details/gtdydnoceo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.nanxinkj.top/Article/details/gtputsznrk.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hongshengwenyu.top/Article/details/gtrvrgamsg.html

JS:   // worker_threads 线程池
来源：http://dali.daxiang520.top/Article/details/gtsemjuquh.html

TS:   // worker_threads 线程池
来源：http://dali.shangyingyoupin.top/Article/details/gttiegrhgx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtetzpnnjh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.birdmap.top/Article/details/gtlyeuzguz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhoulong.xyz/Article/details/gthslvclxl.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hywenlv.cn/Article/details/gtqsapmgon.html

[O03] 加锁保护共享数据
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyqbjlwkb.html

Py:   with lock: shared += 1
来源：http://dali.nanxuanxn.top/Article/details/gtstrfswdl.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ehwqpu.com/Article/details/gtnknfwozm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.quarkkingdee.top/Article/details/gtmoxtebjg.html

TS:   // 同 JS
来源：http://dali.daria6918.cn/Article/details/gtdicekqnj.html

Java: synchronized (this) { shared++; }
来源：http://dali.yj20258.top/Article/details/gttgyhgkwc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhixingplan.top/Article/details/gtkumgwbwf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.chenzaomai.com/Article/details/gtbstiwcjo.html

C#:   lock (gate) { shared++; }
来源：http://dali.yongpay.top/Article/details/gtodfyvjmh.html

[O04] 定义异步函数并等待
来源：http://dali.quarkkingdee.top/Article/details/gtrwxkullg.html

Py:   async def f():⏎    await g()
来源：http://dali.hysaishi.cn/Article/details/gtphqunxwj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjgywlzud.html

JS:   async function f() { await g(); }
来源：http://dali.nanxinkj.top/Article/details/gtqnizjrgk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.fengsongda.top/Article/details/gtokacecrm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cdnleiting.top/Article/details/gtupwrwjsw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.andypj.xyz/Article/details/gtswfvebwi.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ehwqpu.com/Article/details/gtkhsaoqca.html

C#:   async Task F() { await G(); }
来源：http://dali.wangdashe.top/Article/details/gtunmkuwky.html

[O05] 并发执行并等待全部完成
来源：http://dali.xziqi.cn/Article/details/gtqjnqosex.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hnxiangtu.top/Article/details/gtrrqradmm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.feifeiyinyue.top/Article/details/gtlmctskof.html

JS:   await Promise.all(tasks)
来源：http://dali.yuxming.cn/Article/details/gtvtfpuwul.html

TS:   await Promise.all(tasks)
来源：http://dali.meibo888.top/Article/details/gtrtxgbfue.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yj202588.top/Article/details/gtstplddzn.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yongpay.top/Article/details/gtezozbhrj.html

Ruby: threads.map(&:join)
来源：http://dali.gotoacloud.top/Article/details/gtoisqsccm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.haohaochexian.top/Article/details/gthwmpulfa.html

[O06] 使用进程池
来源：http://dali.zycfv.cn/Article/details/gtgwmtcecv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.daria6918.cn/Article/details/gthdtdbftw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.meibo888.top/Article/details/gtxlslhfqd.html

JS:   // child_process / cluster 模块
来源：http://dali.andypj.xyz/Article/details/gtivsszbeu.html


<!-- 参考信息 -->