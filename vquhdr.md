代发 wailian999

Go:   resp, err := http.Get(url)
来源：http://dali.tianlin.xyz/Article/details/gtkgkekeng.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkbqyvvdc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.mhx1999.top/Article/details/gtblbakktw.html

[L02] 发送 POST JSON
来源：http://dali.hongshengwenyu.top/Article/details/gtziuburok.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yj202588.top/Article/details/gtayksbuce.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ybcxt.top/Article/details/gtjsmszffz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yangfankeji.com/Article/details/gtcxwftjnt.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhixingplan.top/Article/details/gtmdithhwo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.snrcjt.cn/Article/details/gtrkoehqsw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhoulong.xyz/Article/details/gtahckimtv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.gaohongyu789.top/Article/details/gtggmhksto.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinqigufen.top/Article/details/gtkblgsenq.html

[L03] 设置自定义请求头
来源：http://dali.yj20258.top/Article/details/gtnogchfst.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xuetiantiany.cn/Article/details/gtqxtjqpoe.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj202588.top/Article/details/gtwikiwnzj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.svipenyu.cn/Article/details/gtatzmxxed.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxuanxn.top/Article/details/gtnfjkzedg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xinyue.icu/Article/details/gtenffnqmu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gogol.net.cn/Article/details/gtrdnjzjgk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwhomawjj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.tanke756.top/Article/details/gtmaoblmis.html

[L04] 设置超时
来源：http://dali.zhengqikj.top/Article/details/gttfjimadg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.dianchejie.cn/Article/details/gtqyukxbwq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jianghu66.top/Article/details/gtuwrmmdjz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sysykeji.top/Article/details/gtcjytxmna.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgufenzy.top/Article/details/gtlngwhbqm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shanyushiyangtech.top/Article/details/gtmcwkkjky.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.tian-w.cn/Article/details/gtejcrprar.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zdqjudy.top/Article/details/gtgsjfrcfk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cdnleiting.top/Article/details/gtxsrwdngk.html

[L05] 上传文件（multipart）
来源：http://dali.jlsjyb.cn/Article/details/gthlphofsv.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.bjfxy.top/Article/details/gtmxmkcqkt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yueranfly.top/Article/details/gtgumdggnf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.feifeiyinyue.top/Article/details/gtaelnxnwd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xylfe.cn/Article/details/gteocutrbh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.wangdashe.top/Article/details/gtdpgaokir.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yanxiufei.cn/Article/details/gteupioefn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.fengsongda.top/Article/details/gtnqtqzmmv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtkllztvno.html

[L06] 解析响应为 JSON
来源：http://dali.yueranfly.top/Article/details/gtmcttdafr.html

Py:   resp.json()
来源：http://dali.jinqigufen.top/Article/details/gtytydympe.html

PHP:  json_decode($body, true);
来源：http://dali.gotoacloud.top/Article/details/gtkkgrocop.html

JS:   await resp.json()
来源：http://dali.c1oappe.top/Article/details/gtroqhowri.html

TS:   await resp.json()
来源：http://dali.cdnleiting.top/Article/details/gtqmkdjvgj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xuanzx.com/Article/details/gtttrsqidm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.fengsongda.top/Article/details/gtchexetzy.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jyoumei.cn/Article/details/gtalrwpofm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yuxming.cn/Article/details/gtganovbqf.html

[L07] 处理 HTTP 状态码
来源：http://dali.ybcxt.top/Article/details/gtrrdtjfor.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jqgfzy.top/Article/details/gtoaxreaiq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gttwcqjnkq.html

JS:   resp.ok;  resp.status
来源：http://dali.cashguo.top/Article/details/gtivpxsfpk.html

TS:   resp.ok;  resp.status
来源：http://dali.guannengcc.top/Article/details/gtltlknqmj.html

Java: resp.statusCode()
来源：http://dali.haohaochexian.top/Article/details/gtpdilvgin.html

Go:   resp.StatusCode
来源：http://dali.daria6918.cn/Article/details/gtqwirbuxe.html

Ruby: resp.code.to_i
来源：http://dali.jinghuilouyu.cn/Article/details/gtcizdegxx.html

C#:   (int)resp.StatusCode
来源：http://dali.yangfankeji.com/Article/details/gttxdrquhw.html

[L08] 并发请求多个地址
来源：http://dali.yonumen.top/Article/details/gtryztwnyd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xuanzx.com/Article/details/gtsfckvwzf.html

PHP:  curl_multi_init() 系列
来源：http://dali.hywenlv.cn/Article/details/gtmqatjzci.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xylfe.cn/Article/details/gtluwsgjyf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aizwys.cn/Article/details/gtzhbcrbda.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.guowangkeji.top/Article/details/gtglhcqdmv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gaohongyu789.top/Article/details/gtaabchxmq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yvedp.cn/Article/details/gtyoeqhwws.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gtnnqwtwld.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtaisdvfdz.html

M. 命令行 / 进程 / 环境
来源：http://dali.gaohongyu789.top/Article/details/gtejymnbkc.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtlpoenjbx.html

[M01] 读取命令行参数
来源：http://dali.jiagoushi.top/Article/details/gtorcvnnnz.html

Py:   sys.argv[1:]
来源：http://dali.shzxlz.cn/Article/details/gtamejkpvc.html

PHP:  $argv;  $argc;
来源：http://dali.wangshuangyany.cn/Article/details/gtgxdjgnzh.html

JS:   process.argv.slice(2)
来源：http://dali.hnxiangtu.top/Article/details/gttpkajuhg.html

TS:   process.argv.slice(2)
来源：http://dali.mhx1999.top/Article/details/gthljskmby.html

Java: args 数组（main 方法参数）
来源：http://dali.jiagoushi.top/Article/details/gtnnzuybdk.html

Go:   os.Args[1:]
来源：http://dali.haohaochexian.top/Article/details/gtdxdulflg.html

Ruby: ARGV
来源：http://dali.haohaochexian.top/Article/details/gtocybxoch.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hnxiangtu.top/Article/details/gtsrymcrbk.html

[M02] 读取环境变量
来源：http://dali.haohaochexian.top/Article/details/gtejwbqykw.html

Py:   os.environ.get("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gtacgrvmra.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.smart0.xyz/Article/details/gtaftbdbmg.html

JS:   process.env.HOME
来源：http://dali.svipenyu.cn/Article/details/gtzajohpah.html

TS:   process.env.HOME
来源：http://dali.jlsjyb.cn/Article/details/gtjyvpehkc.html

Java: System.getenv("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gtctwdyjct.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gtdbpcvynd.html

Ruby: ENV["HOME"]
来源：http://dali.svipenyu.cn/Article/details/gtrvooycex.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gtihvezkgi.html

[M03] 执行外部命令
来源：http://dali.dianchejie.cn/Article/details/gtuptasqmu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.guowangkeji.top/Article/details/gtamefrrmt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj20258888.top/Article/details/gtewbwyqmt.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.sxryk.cn/Article/details/gtjqabsrdh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hysaishi.cn/Article/details/gtlzmxozxg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xuanzx.com/Article/details/gtbfufwirf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tianlin.xyz/Article/details/gtijculyos.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinqigufen.top/Article/details/gtszdgoone.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yj20258888.top/Article/details/gtfdmzoivb.html

[M04] 获取当前工作目录
来源：http://dali.nwbrower.top/Article/details/gtljyjvwuu.html

Py:   os.getcwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmenipvrh.html

PHP:  getcwd();
来源：http://dali.hnqzz.top/Article/details/gtmrzidtzr.html

JS:   process.cwd()
来源：http://dali.meibo888.top/Article/details/gtyvwmzfub.html

TS:   process.cwd()
来源：http://dali.hfpthk.cn/Article/details/gtvafiswbe.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yj202588.top/Article/details/gtxmixtnkr.html

Go:   os.Getwd()
来源：http://dali.yueranfly.top/Article/details/gtrkvmcjvk.html

Ruby: Dir.pwd
来源：http://dali.hnxiangtu.top/Article/details/gtxobvzbaw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.quarkkingdee.top/Article/details/gtyptyvgjb.html

[M05] 设置退出码
来源：http://dali.yvedp.cn/Article/details/gtwequuwfv.html

Py:   sys.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtezhwgyjo.html

PHP:  exit(1);
来源：http://dali.daxiang520.top/Article/details/gtqwiftnvo.html

JS:   process.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtfrdswylj.html

TS:   process.exit(1)
来源：http://dali.havefunace.top/Article/details/gtdorucdej.html

Java: System.exit(1)
来源：http://dali.yueranfly.top/Article/details/gtovjqckae.html

Go:   os.Exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtrtqjidlb.html

Ruby: exit 1
来源：http://dali.zhiwuduotai.top/Article/details/gtttfhazlm.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gaohongyu789.top/Article/details/gtkpifnkbh.html

[M06] 向标准错误输出
来源：http://dali.jinghuilouyu.cn/Article/details/gtwtznmfzb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sweek.top/Article/details/gtrsrvtamm.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nanxinkj.top/Article/details/gtomveydlv.html

JS:   console.error("err")
来源：http://dali.zhoulong.xyz/Article/details/gtecthgdar.html

TS:   console.error("err")
来源：http://dali.wangdashe.top/Article/details/gtuymvzsac.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gtkipngxhd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.fzhhl.top/Article/details/gtlmlmyupg.html

Ruby: warn "err"
来源：http://dali.yvedp.cn/Article/details/gtbhfsygxk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shangyingyoupin.top/Article/details/gtupcndkru.html

[M07] 判断是否为主入口
来源：http://dali.yj20258888.top/Article/details/gtxguykeyr.html

Py:   if __name__ == "__main__":
来源：http://dali.jlsjyb.cn/Article/details/gtwvfreegb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yongpay.top/Article/details/gtgosiqfko.html

JS:   require.main === module
来源：http://dali.xinyue.icu/Article/details/gtbkvjavem.html

TS:   require.main === module
来源：http://dali.hfpthk.cn/Article/details/gtkvsdqqpy.html

Java: public static void main(String[] args)
来源：http://dali.wangshuangyany.cn/Article/details/gtdarrvcpd.html

Go:   func main()
来源：http://dali.pengpengdd.cyou/Article/details/gtkztyyfxv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.snrcjt.cn/Article/details/gtipyhmbcg.html

C#:   static void Main(string[] args)
来源：http://dali.zhoulong.xyz/Article/details/gtirgnwuvr.html

[M08] 获取系统与运行时信息
来源：http://dali.snrcjt.cn/Article/details/gtuthjwuym.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hongshengwenyu.top/Article/details/gtmwnfqxra.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jqgfzy.top/Article/details/gtuyopdcaz.html

JS:   process.platform;  process.version
来源：http://dali.xuanzx.com/Article/details/gtvgrkgvxn.html

TS:   process.platform;  process.version
来源：http://dali.haohaochexian.top/Article/details/gtfauqyero.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yj20258.top/Article/details/gtjrvpxygw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhaomingkeji.xyz/Article/details/gttsibgapz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hywenlv.cn/Article/details/gtbtivcksu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sysykeji.top/Article/details/gtxzlitkay.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtzpjaoznj.html

N. 数据结构与算法
来源：http://dali.kuanghao11.cn/Article/details/gtndpdfhjj.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtqaqsmtih.html

[N01] 二分查找（有序数组）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvnqhxqhv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tanke756.top/Article/details/gtnxtidevw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yongpay.top/Article/details/gteuzodjzj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xziqi.cn/Article/details/gtvzkopeff.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.0kj1m.cn/Article/details/gtgpzuzzii.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sweek.top/Article/details/gtviifrnzj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yj202588.top/Article/details/gtawqwsyfp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.haohaochexian.top/Article/details/gtgtlmprpu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.mhx1999.top/Article/details/gternaizsd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gaohongyu789.top/Article/details/gtcgdpdrem.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cashguo.top/Article/details/gtfndpmtiw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jlsjyb.cn/Article/details/gtqcgzzqqq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tian-w.cn/Article/details/gttzxtfwlg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenjidiqi.icu/Article/details/gtkniulklk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.nanxinkj.top/Article/details/gtsxucdgcb.html

Go:   slices.Sort(arr)
来源：http://dali.hnqzz.top/Article/details/gtynsjeswl.html

Ruby: arr.sort
来源：http://dali.fengsongda.top/Article/details/gtcwxmccpy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.birdmap.top/Article/details/gtgkzbuffc.html

[N03] 快速排序（分治示例）
来源：http://dali.dashuyun.cn/Article/details/gthwzmddbp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zdqjudy.top/Article/details/gtfqommmva.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gotoacloud.top/Article/details/gtwlrgydxq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dashuyun.cn/Article/details/gtrbgwuicf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sysykeji.top/Article/details/gtfuglcnok.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.316326.xyz/Article/details/gtdyveaycw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.dianchejie.cn/Article/details/gtehesbnqo.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gotoacloud.top/Article/details/gtwpdmpamk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sysykeji.top/Article/details/gtjsizxguf.html

[N04] 斐波那契数列
来源：http://dali.sysykeji.top/Article/details/gtahuhoxms.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.bjfxy.top/Article/details/gtdweebklh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.chenlongwang.top/Article/details/gtcuruarsz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.quarkkingdee.top/Article/details/gtnthzgkcn.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.svipenyu.cn/Article/details/gtuzhbphge.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yangfankeji.com/Article/details/gtouillgha.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.wangshuangyany.cn/Article/details/gtsfclznue.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yonumen.top/Article/details/gtsmmknpgo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cdnleiting.top/Article/details/gtdfqqikzi.html

[N05] 最大公约数
来源：http://dali.xylfe.cn/Article/details/gtqhohwshe.html

Py:   math.gcd(a, b)
来源：http://dali.zhiwuduotai.top/Article/details/gtiknemrtb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtazbmvcuv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigufen.top/Article/details/gtffmgjpqf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenjidiqi.icu/Article/details/gtncuilsym.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.dianchejie.cn/Article/details/gtybgtvvqd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.dashuyun.cn/Article/details/gtiajjlehq.html

Ruby: a.gcd(b)
来源：http://dali.chenjidiqi.icu/Article/details/gthhyxnvju.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hongshengwenyu.top/Article/details/gtpjdeoleh.html

[N06] 判断回文字符串
来源：http://dali.hywenlv.cn/Article/details/gtmnspphtm.html

Py:   s == s[::-1]
来源：http://dali.yj202588.top/Article/details/gtulyamdbl.html

PHP:  $s === strrev($s);
来源：http://dali.gaohongyu789.top/Article/details/gtjxmjducq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gtplaxzcez.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gtmgmiozst.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnwzwpdkn.html

Go:   // 双指针从两端比较
来源：http://dali.shangyingyoupin.top/Article/details/gtrycokvmq.html

Ruby: s == s.reverse
来源：http://dali.zhengqikj.top/Article/details/gtxjjpwgha.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgfkqytjg.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gtcjdzrluy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gotoacloud.top/Article/details/gtbcimrics.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.daria6918.cn/Article/details/gtkbdjyqvw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.feifeiyinyue.top/Article/details/gtaeekphha.html

TS:   // 手写 Map<string, number>
来源：http://dali.yonumen.top/Article/details/gtjnsafifn.html

Java: // 手写 HashMap
来源：http://dali.yanxiufei.cn/Article/details/gtulzzvhve.html

Go:   // 手写 map[int]int
来源：http://dali.smart0.xyz/Article/details/gtpfaizwzn.html

Ruby: // 手写 Hash
来源：http://dali.gaohongyu789.top/Article/details/gtkqjkjger.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgusvknqs.html

[N08] 生成全排列
来源：http://dali.nanxuanxn.top/Article/details/gtcehafbtd.html

Py:   itertools.permutations(arr)
来源：http://dali.birdmap.top/Article/details/gtedobecmp.html

PHP:  // 手写递归交换
来源：http://dali.shangyingyoupin.top/Article/details/gtcdtyfamx.html

JS:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gtijskqhmm.html

TS:   // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gtzayrbyod.html

Java: // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtdaslgskq.html

Go:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gthtxvesgp.html

Ruby: arr.permutation.to_a
来源：http://dali.xuanzx.com/Article/details/gtcebvdyjs.html

C#:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gtsarfwowc.html

[N09] 栈与队列
来源：http://dali.bjfxy.top/Article/details/gtlrpuzblx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.dashuyun.cn/Article/details/gtjegkjnmp.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.c1oappe.top/Article/details/gtsjxslljj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nwbrower.top/Article/details/gthwnosldm.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.bjfxy.top/Article/details/gtzvjzulzw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cheryme.top/Article/details/gtmdxajklz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xylfe.cn/Article/details/gtartkvkrn.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.wangdashe.top/Article/details/gthvpwrqzm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ivvv.top/Article/details/gtmgkhtrzw.html

[N10] 链表节点定义
来源：http://dali.mhx1999.top/Article/details/gtldkniqwd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shangyingyoupin.top/Article/details/gtjsgnktna.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.fengsongda.top/Article/details/gtnfpxjbuz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmcpqeqxt.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.haohaochexian.top/Article/details/gtzcwlgvsu.html

Java: class Node { int v; Node next; }
来源：http://dali.ppjwa.cn/Article/details/gtkkxfxfco.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.birdmap.top/Article/details/gtbdfmqeng.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jiagoushi.top/Article/details/gtlirqywnw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.quarkkingdee.top/Article/details/gtcglvxfxf.html

[N11] 二叉树中序遍历
来源：http://dali.xylfe.cn/Article/details/gtxttzxdtd.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.chenzaomai.com/Article/details/gtqpnralzl.html

PHP:  // 手写递归函数
来源：http://dali.yuanzhike.top/Article/details/gtzftdrrix.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gogol.net.cn/Article/details/gtiobszgnm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xinyue.icu/Article/details/gtyvrcbuql.html

Java: // 手写递归
来源：http://dali.jiagoushi.top/Article/details/gtmnssmgve.html

Go:   // 手写递归
来源：http://dali.yanxiufei.cn/Article/details/gtsmugwmof.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.tianlin.xyz/Article/details/gttjyxyjni.html

C#:   // 手写递归
来源：http://dali.havefunace.top/Article/details/gtabeaqdff.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xuetiantiany.cn/Article/details/gtolsvvjij.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hnqzz.top/Article/details/gtsywfoncg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gotoacloud.top/Article/details/gtlwxulefu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgufenzy.top/Article/details/gtvmqilnip.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aibaodan.cn/Article/details/gtotzlecto.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ybcxt.top/Article/details/gtdtmoztxu.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.havefunace.top/Article/details/gtexcilkns.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.mhx1999.top/Article/details/gtyyvszabd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hnqzz.top/Article/details/gtwthzwyye.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtdgofjxja.html

O. 并发与异步
来源：http://dali.yvedp.cn/Article/details/gthlstjaax.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtfryvqspx.html

[O01] 启动一个线程
来源：http://dali.jinghuilouyu.cn/Article/details/gthpdyhlmp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.guannengcc.top/Article/details/gtvpisezzs.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhongyouzk.top/Article/details/gtkthiarbu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xylfe.cn/Article/details/gtwjdqaxdp.html

TS:   // 同 JS
来源：http://dali.0kj1m.cn/Article/details/gtpgggpggi.html

Java: new Thread(() -> f()).start()
来源：http://dali.aizwys.cn/Article/details/gtyfecpeah.html

Go:   go f()
来源：http://dali.yonumen.top/Article/details/gttuxueyts.html

Ruby: Thread.new { f }
来源：http://dali.zycfv.cn/Article/details/gtptfdqwck.html

C#:   Task.Run(() => F());
来源：http://dali.zhengqikj.top/Article/details/gtnteahten.html

[O02] 使用线程池
来源：http://dali.ehwqpu.com/Article/details/gtjvhypcgn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.wangshuangyany.cn/Article/details/gtuwzjnlhq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yueranfly.top/Article/details/gtxnwuejuj.html

JS:   // worker_threads 线程池
来源：http://dali.yj202588.top/Article/details/gtndszdzow.html

TS:   // worker_threads 线程池
来源：http://dali.hongshengwenyu.top/Article/details/gtroehoosw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhongyouzk.top/Article/details/gtiwvhkarc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.316326.xyz/Article/details/gtcntkaysy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.snrcjt.cn/Article/details/gthlksykgv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.snrcjt.cn/Article/details/gtvjidkbvw.html

[O03] 加锁保护共享数据
来源：http://dali.wangshuangyany.cn/Article/details/gtbhuogzrl.html

Py:   with lock: shared += 1
来源：http://dali.ehwqpu.com/Article/details/gtofhnhbwi.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xylfe.cn/Article/details/gtvspmhyge.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.bjfxy.top/Article/details/gtztpfxoct.html

TS:   // 同 JS
来源：http://dali.ehwqpu.com/Article/details/gtqhehakij.html

Java: synchronized (this) { shared++; }
来源：http://dali.shangyingyoupin.top/Article/details/gtwcwuaxqf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ivvv.top/Article/details/gtzmilaqev.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cdnleiting.top/Article/details/gtjnnnnqah.html

C#:   lock (gate) { shared++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttcsagvdo.html

[O04] 定义异步函数并等待
来源：http://dali.fengsongda.top/Article/details/gtyopzhixj.html

Py:   async def f():⏎    await g()
来源：http://dali.andypj.xyz/Article/details/gtasiankyx.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xuetiantiany.cn/Article/details/gtohvvfphf.html

JS:   async function f() { await g(); }
来源：http://dali.ppjwa.cn/Article/details/gtfnucdbnp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yuanzhike.top/Article/details/gtrntajeqc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuleqwtrp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.chenjidiqi.icu/Article/details/gtylyhxnop.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.svipenyu.cn/Article/details/gtaqgonjku.html

C#:   async Task F() { await G(); }
来源：http://dali.chenjidiqi.icu/Article/details/gttqproxuo.html

[O05] 并发执行并等待全部完成
来源：http://dali.gogol.net.cn/Article/details/gtvpithodb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwjwnoqin.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hfpthk.cn/Article/details/gtzppbkrsa.html

JS:   await Promise.all(tasks)
来源：http://dali.jqgfzy.top/Article/details/gtdpdmlsbp.html

TS:   await Promise.all(tasks)
来源：http://dali.aibaodan.cn/Article/details/gtynpmvnyo.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.svipenyu.cn/Article/details/gtrgbjfsqu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtutkqxmlr.html

Ruby: threads.map(&:join)
来源：http://dali.zhongyouzk.top/Article/details/gtssmzwoog.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xinyue.icu/Article/details/gtesigwqvj.html


<!-- 参考信息 -->