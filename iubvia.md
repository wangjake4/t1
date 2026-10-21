代发 wailian999

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ybcxt.top/Article/details/gtyrcbefij.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinqigufen.top/Article/details/gtuksrdfwn.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.aizwys.cn/Article/details/gtzxxfsxsj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ydzc1.top/Article/details/gtimcccoas.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.kuanghao11.cn/Article/details/gtyydzvkqy.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.vqdsnc.cn/Article/details/gtnfsppgjq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zdqjudy.top/Article/details/gtqwwheiar.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.0kj1m.cn/Article/details/gtlzfgaxuj.html

[L03] 设置自定义请求头
来源：http://dali.cqqwz.cn/Article/details/gtsqsurjgk.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yongpay.top/Article/details/gtsyhyytae.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenzaomai.com/Article/details/gtydzmeoap.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangdashe.top/Article/details/gthvfbfevv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ydzc1.top/Article/details/gtwjkdsqgt.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jlsjyb.cn/Article/details/gtlwsiamyj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhongyouzk.top/Article/details/gtbgczbgue.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinqigfzy.top/Article/details/gtaktigqvw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhongyouzk.top/Article/details/gttqteootj.html

[L04] 设置超时
来源：http://dali.yj20258.top/Article/details/gtgozvzcmr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmwjvuppf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinqigfzy.top/Article/details/gtsodpnzgj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.andypj.xyz/Article/details/gtuqniwdru.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cucudq.cn/Article/details/gtxgzpotcv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.dianchejie.cn/Article/details/gtdptndyqb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ehwqpu.com/Article/details/gtacvsgijq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yvedp.cn/Article/details/gtmfvmzvki.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hammf.cn/Article/details/gtxmipusvu.html

[L05] 上传文件（multipart）
来源：http://dali.daria6918.cn/Article/details/gtelpctxje.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.tianlin.xyz/Article/details/gtfwmhhmls.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gzhubu.top/Article/details/gtqyworvpz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnxiangtu.top/Article/details/gthznyzhlu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shzxlz.cn/Article/details/gtpaabafzr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yuxming.cn/Article/details/gtwzndhdcn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinqigfzy.top/Article/details/gtwamxleay.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sweek.top/Article/details/gtctevrott.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.fzhhl.top/Article/details/gtaiqgwvxm.html

[L06] 解析响应为 JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gtybhqgzuw.html

Py:   resp.json()
来源：http://dali.ybcxt.top/Article/details/gtujqzjanq.html

PHP:  json_decode($body, true);
来源：http://dali.shzxlz.cn/Article/details/gtyphvjnbg.html

JS:   await resp.json()
来源：http://dali.yj20258888.top/Article/details/gtoouqeist.html

TS:   await resp.json()
来源：http://dali.svipenyu.cn/Article/details/gtifjushbf.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ivvv.top/Article/details/gtmmcubwpu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ehwqpu.com/Article/details/gtyodhcjzg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ehwqpu.com/Article/details/gtgoxxzuqw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xuetiantiany.cn/Article/details/gtfrhxyddk.html

[L07] 处理 HTTP 状态码
来源：http://dali.haohaochexian.top/Article/details/gtigcylilp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinghuilouyu.cn/Article/details/gtqnmtybas.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.316326.xyz/Article/details/gtonylaweo.html

JS:   resp.ok;  resp.status
来源：http://dali.dianchejie.cn/Article/details/gtpdvxslcp.html

TS:   resp.ok;  resp.status
来源：http://dali.fengsongda.top/Article/details/gtezypelzl.html

Java: resp.statusCode()
来源：http://dali.tanke756.top/Article/details/gtcaispkti.html

Go:   resp.StatusCode
来源：http://dali.redwolf501.top/Article/details/gtovpzpivf.html

Ruby: resp.code.to_i
来源：http://dali.svipenyu.cn/Article/details/gtsjgiyazz.html

C#:   (int)resp.StatusCode
来源：http://dali.birdmap.top/Article/details/gtzhwprjog.html

[L08] 并发请求多个地址
来源：http://dali.jiagoushi.top/Article/details/gtybeibzug.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.wangdashe.top/Article/details/gtvanxwpjp.html

PHP:  curl_multi_init() 系列
来源：http://dali.pengpengdd.cyou/Article/details/gtntiiexzl.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangshuangyany.cn/Article/details/gtozqenwvf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sxryk.cn/Article/details/gtnveoubfe.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhengqikj.top/Article/details/gtaikqajpt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.9152youxi.cn/Article/details/gtdnrtxexu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhixingplan.top/Article/details/gtsoltksra.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.smart0.xyz/Article/details/gtvemyagmu.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtrcpezozs.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenzaomai.com/Article/details/gtjrldhdpt.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtftekbnau.html

[M01] 读取命令行参数
来源：http://dali.hnxiangtu.top/Article/details/gtwgqnrrzw.html

Py:   sys.argv[1:]
来源：http://dali.sweek.top/Article/details/gtleerfijf.html

PHP:  $argv;  $argc;
来源：http://dali.ydzc1.top/Article/details/gtxsewpblx.html

JS:   process.argv.slice(2)
来源：http://dali.yonumen.top/Article/details/gtnlkjsorx.html

TS:   process.argv.slice(2)
来源：http://dali.shuidangran.top/Article/details/gtodxvklhe.html

Java: args 数组（main 方法参数）
来源：http://dali.iojbl.cn/Article/details/gtrmbnalek.html

Go:   os.Args[1:]
来源：http://dali.gotoacloud.top/Article/details/gtykkzaznn.html

Ruby: ARGV
来源：http://dali.9152youxi.cn/Article/details/gtrximvmii.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cdnleiting.top/Article/details/gtthbyhoxk.html

[M02] 读取环境变量
来源：http://dali.zhengqikj.top/Article/details/gtyncdztyz.html

Py:   os.environ.get("HOME")
来源：http://dali.aizwys.cn/Article/details/gttailhscs.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.feifeiyinyue.top/Article/details/gtkddnspth.html

JS:   process.env.HOME
来源：http://dali.yj20258888.top/Article/details/gtujiihjgn.html

TS:   process.env.HOME
来源：http://dali.jqgfzy.top/Article/details/gtdrijoyho.html

Java: System.getenv("HOME")
来源：http://dali.guowangkeji.top/Article/details/gtvveeoikn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtrzfahuii.html

Ruby: ENV["HOME"]
来源：http://dali.hysaishi.cn/Article/details/gtmmuxalni.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xylfe.cn/Article/details/gtkjjkkeuk.html

[M03] 执行外部命令
来源：http://dali.zdqjudy.top/Article/details/gtebzkbbgn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xinyue.icu/Article/details/gtgfqimyxv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsqcvohbp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangdashe.top/Article/details/gtxxumhztg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.dianchejie.cn/Article/details/gtrfbqbdjf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sysykeji.top/Article/details/gtyuljlacc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yuanzhike.top/Article/details/gtkiedbtvw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jqgufenzy.top/Article/details/gtnlhhvbtv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nwbrower.top/Article/details/gtixgeblfc.html

[M04] 获取当前工作目录
来源：http://dali.yj20258888.top/Article/details/gtebrrhzud.html

Py:   os.getcwd()
来源：http://dali.hfpthk.cn/Article/details/gtidmhuylq.html

PHP:  getcwd();
来源：http://dali.jinyuanbaomall.cn/Article/details/gthwozrovg.html

JS:   process.cwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgauolblx.html

TS:   process.cwd()
来源：http://dali.sysykeji.top/Article/details/gtsnvmmtcj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinqigfzy.top/Article/details/gtufjmmywl.html

Go:   os.Getwd()
来源：http://dali.hnqzz.top/Article/details/gtpdgjlgcv.html

Ruby: Dir.pwd
来源：http://dali.nanxuanxn.top/Article/details/gtocwbbfxw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.pengpengdd.cyou/Article/details/gtipwekkin.html

[M05] 设置退出码
来源：http://dali.hywenlv.cn/Article/details/gtcskmpbil.html

Py:   sys.exit(1)
来源：http://dali.cucudq.cn/Article/details/gtmrwtzram.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gtsbavufch.html

JS:   process.exit(1)
来源：http://dali.wangdashe.top/Article/details/gtpemsrmdu.html

TS:   process.exit(1)
来源：http://dali.hnqzz.top/Article/details/gtzmmlxuiv.html

Java: System.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gtriczucxq.html

Go:   os.Exit(1)
来源：http://dali.nwbrower.top/Article/details/gtvjzwuljb.html

Ruby: exit 1
来源：http://dali.yj20258888.top/Article/details/gtjquqrfvb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.tanke756.top/Article/details/gtvzuawnkw.html

[M06] 向标准错误输出
来源：http://dali.havefunace.top/Article/details/gtdapjbaot.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jqgfzy.top/Article/details/gtudmgkygh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jiagoushi.top/Article/details/gtnvhcvrzd.html

JS:   console.error("err")
来源：http://dali.pengpengdd.cyou/Article/details/gtkztpynkv.html

TS:   console.error("err")
来源：http://dali.jiagoushi.top/Article/details/gtgzdduekq.html

Java: System.err.println("err")
来源：http://dali.gaohongyu789.top/Article/details/gtgyugaqym.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ivvv.top/Article/details/gtjpdnrjag.html

Ruby: warn "err"
来源：http://dali.daxiang520.top/Article/details/gtgoifjhjn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nanxuanxn.top/Article/details/gtjcubdkvn.html

[M07] 判断是否为主入口
来源：http://dali.yanxiufei.cn/Article/details/gtghbjnycp.html

Py:   if __name__ == "__main__":
来源：http://dali.feifeiyinyue.top/Article/details/gtbcywctrs.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.mhx1999.top/Article/details/gtujzrvobk.html

JS:   require.main === module
来源：http://dali.aizwys.cn/Article/details/gtgpdgrlii.html

TS:   require.main === module
来源：http://dali.cheryme.top/Article/details/gtfjripzcq.html

Java: public static void main(String[] args)
来源：http://dali.sysykeji.top/Article/details/gtkjmurvpd.html

Go:   func main()
来源：http://dali.gzhubu.top/Article/details/gtzmimlylb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sxryk.cn/Article/details/gtzrqioiim.html

C#:   static void Main(string[] args)
来源：http://dali.xuetiantiany.cn/Article/details/gtdaxbzaat.html

[M08] 获取系统与运行时信息
来源：http://dali.xylfe.cn/Article/details/gtoworivwa.html

Py:   platform.system();  platform.python_version()
来源：http://dali.pengpengdd.cyou/Article/details/gtkwfsuqkl.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.vqdsnc.cn/Article/details/gtvbozutlb.html

JS:   process.platform;  process.version
来源：http://dali.jyoumei.cn/Article/details/gthoanvukp.html

TS:   process.platform;  process.version
来源：http://dali.hnqzz.top/Article/details/gtoucjbsnr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xinyue.icu/Article/details/gtedqnrsdk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yuxming.cn/Article/details/gteytcfnqo.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.316326.xyz/Article/details/gtlrznqcsj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.snrcjt.cn/Article/details/gtxwrkaqey.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gteesrjgnf.html

N. 数据结构与算法
来源：http://dali.tanke756.top/Article/details/gtapvmrurx.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtvtqfbwrz.html

[N01] 二分查找（有序数组）
来源：http://dali.guannengcc.top/Article/details/gttavaaljp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.meibo888.top/Article/details/gtdvqlhqqz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shangyingyoupin.top/Article/details/gtrytcvnyv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhiwuduotai.top/Article/details/gtuvrtwjdo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenjidiqi.icu/Article/details/gtjseolmul.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtiixvvbwj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtmvvybhaz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.andypj.xyz/Article/details/gtbpqvqoal.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtmnuzsmpl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.tian-w.cn/Article/details/gtyxyejsxd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ydzc1.top/Article/details/gtadzfuvzc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yangfankeji.com/Article/details/gtuhqmdqbi.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fzhhl.top/Article/details/gtdkryhomi.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sufxvd.cn/Article/details/gtlrvmotwx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.0kj1m.cn/Article/details/gtajpjibjk.html

Go:   slices.Sort(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtiakglxzg.html

Ruby: arr.sort
来源：http://dali.316326.xyz/Article/details/gthxrvliaz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.tanke756.top/Article/details/gtuhfosvql.html

[N03] 快速排序（分治示例）
来源：http://dali.xziqi.cn/Article/details/gtsjzvpopb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.chenjidiqi.icu/Article/details/gtuufcqmku.html

PHP:  // 递归实现，或用 usort
来源：http://dali.redwolf501.top/Article/details/gthwabhray.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.snrcjt.cn/Article/details/gtpqhzkagw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.meibo888.top/Article/details/gtlvonccyq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.daria6918.cn/Article/details/gtsqexswhe.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinqigufen.top/Article/details/gtnbfetksh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xuanzx.com/Article/details/gtmapsejao.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gaohongyu789.top/Article/details/gtvtayqnep.html

[N04] 斐波那契数列
来源：http://dali.tianlin.xyz/Article/details/gtczddbuku.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigfzy.top/Article/details/gtrlkeftot.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.iojbl.cn/Article/details/gtgztzmndd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gogol.net.cn/Article/details/gtmpyskpha.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gticjbduin.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xylfe.cn/Article/details/gtltcfxdey.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenzaomai.com/Article/details/gtycogcyml.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhoulong.xyz/Article/details/gtvnjniuam.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gtlrrsnqdt.html

[N05] 最大公约数
来源：http://dali.nwbrower.top/Article/details/gtsjeqaaos.html

Py:   math.gcd(a, b)
来源：http://dali.xuanzx.com/Article/details/gtxndyyuup.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthelusvtk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hammf.cn/Article/details/gtvmnrseic.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zdqjudy.top/Article/details/gtmbpfyxhm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cdnleiting.top/Article/details/gtrvkvolbj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.smart0.xyz/Article/details/gtisfwczxx.html

Ruby: a.gcd(b)
来源：http://dali.cqqwz.cn/Article/details/gtmcaeypwr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.wangdashe.top/Article/details/gtynaqwzkw.html

[N06] 判断回文字符串
来源：http://dali.aibaodan.cn/Article/details/gtmjsnjrfg.html

Py:   s == s[::-1]
来源：http://dali.wangshuangyany.cn/Article/details/gteogetuzq.html

PHP:  $s === strrev($s);
来源：http://dali.nwbrower.top/Article/details/gtsadktray.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gthrsuuzug.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gtlvafrvoc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xziqi.cn/Article/details/gtwhgsmlde.html

Go:   // 双指针从两端比较
来源：http://dali.dianchejie.cn/Article/details/gtntywvdjg.html

Ruby: s == s.reverse
来源：http://dali.yj20258.top/Article/details/gtwjemqaem.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.nanxuanxn.top/Article/details/gtqevsvdgt.html

[N07] 两数之和（返回下标）
来源：http://dali.ehwqpu.com/Article/details/gtvvfbkhzz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.quarkkingdee.top/Article/details/gtnfdqprsd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yangfankeji.com/Article/details/gtnhbanhga.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shangyingyoupin.top/Article/details/gtzzarqjyv.html

TS:   // 手写 Map<string, number>
来源：http://dali.yongpay.top/Article/details/gttbsismsv.html

Java: // 手写 HashMap
来源：http://dali.hammf.cn/Article/details/gtjhymnwjr.html

Go:   // 手写 map[int]int
来源：http://dali.yj20258.top/Article/details/gtjenvlmqd.html

Ruby: // 手写 Hash
来源：http://dali.bjfxy.top/Article/details/gtnuwikese.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhengqikj.top/Article/details/gtiidgdlvz.html

[N08] 生成全排列
来源：http://dali.hysaishi.cn/Article/details/gtujfojvzj.html

Py:   itertools.permutations(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtozbccmsm.html

PHP:  // 手写递归交换
来源：http://dali.vqdsnc.cn/Article/details/gtarvhnjdr.html

JS:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtsqoaqqwa.html

TS:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gtkhscgyet.html

Java: // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gtwsfdruyt.html

Go:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gtximlozee.html

Ruby: arr.permutation.to_a
来源：http://dali.redwolf501.top/Article/details/gtvvlftczd.html

C#:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gtyxjjxjhx.html

[N09] 栈与队列
来源：http://dali.feifeiyinyue.top/Article/details/gtomsskbdl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.guowangkeji.top/Article/details/gtjpimajem.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.guannengcc.top/Article/details/gtglszknls.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.pengpengdd.cyou/Article/details/gtgpnyxxqi.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.meibo888.top/Article/details/gtiuknzasj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.feifeiyinyue.top/Article/details/gtshlwrrip.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hnxiangtu.top/Article/details/gtzhpdkmfe.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gzhubu.top/Article/details/gtrmvilies.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhongyouzk.top/Article/details/gtfssybtjx.html

[N10] 链表节点定义
来源：http://dali.yj20258.top/Article/details/gtaopmacga.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.vqdsnc.cn/Article/details/gtczqjmuhl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sweek.top/Article/details/gtgfqucmzk.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.nanxinkj.top/Article/details/gtiukqrtwy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.guowangkeji.top/Article/details/gttmjivhaa.html

Java: class Node { int v; Node next; }
来源：http://dali.hongshengwenyu.top/Article/details/gtkamnyepv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.andypj.xyz/Article/details/gtobdjaelo.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zdqjudy.top/Article/details/gtobyupaxk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cheryme.top/Article/details/gttmllbomv.html

[N11] 二叉树中序遍历
来源：http://dali.chenlongwang.top/Article/details/gtuxxxemkf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jlsjyb.cn/Article/details/gtcfgopjka.html

PHP:  // 手写递归函数
来源：http://dali.shangyingyoupin.top/Article/details/gtusmygnvq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinghuilouyu.cn/Article/details/gtovalprwk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gzhubu.top/Article/details/gtqutxhkpa.html

Java: // 手写递归
来源：http://dali.yvedp.cn/Article/details/gtyznbyrzt.html

Go:   // 手写递归
来源：http://dali.dashuyun.cn/Article/details/gtohpkytsg.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gzhubu.top/Article/details/gtzmkhzwdc.html

C#:   // 手写递归
来源：http://dali.ppjwa.cn/Article/details/gthobnmlhk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shuidangran.top/Article/details/gtuhtdqdrq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.iojbl.cn/Article/details/gtzfbmzrgs.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jqgfzy.top/Article/details/gtzqqewmfs.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daxiang520.top/Article/details/gticuyfsif.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hywenlv.cn/Article/details/gthphusdon.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ehwqpu.com/Article/details/gtsxswoscu.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cucudq.cn/Article/details/gtvwhvhoqe.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.vqdsnc.cn/Article/details/gtchecthhj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.dianchejie.cn/Article/details/gtoxkrjhpe.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtgeqwqnwr.html

O. 并发与异步
来源：http://dali.sysykeji.top/Article/details/gtwvfqdpea.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtuialtnbc.html

[O01] 启动一个线程
来源：http://dali.gogol.net.cn/Article/details/gtvgknymmj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sufxvd.cn/Article/details/gtnyytycgv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.tanke756.top/Article/details/gtvuffxwel.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.iojbl.cn/Article/details/gtwpbvnzbd.html

TS:   // 同 JS
来源：http://dali.yuanzhike.top/Article/details/gtkxwzthyg.html

Java: new Thread(() -> f()).start()
来源：http://dali.aibaodan.cn/Article/details/gtjnnzdbky.html

Go:   go f()
来源：http://dali.hfpthk.cn/Article/details/gtnqxwttrr.html

Ruby: Thread.new { f }
来源：http://dali.chenzaomai.com/Article/details/gtnmrnxqav.html

C#:   Task.Run(() => F());
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmkurkvib.html

[O02] 使用线程池
来源：http://dali.wangdashe.top/Article/details/gtlbzeqhuv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shzxlz.cn/Article/details/gtsrxxtcfl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jianghu66.top/Article/details/gtqzrxvbfv.html

JS:   // worker_threads 线程池
来源：http://dali.fzhhl.top/Article/details/gtkmiekilu.html

TS:   // worker_threads 线程池
来源：http://dali.daxiang520.top/Article/details/gthcudvlwv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.tian-w.cn/Article/details/gtdasiwhbt.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.9152youxi.cn/Article/details/gtehiukwgr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xuanzx.com/Article/details/gtsyndkefl.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.guowangkeji.top/Article/details/gtuollpjjc.html

[O03] 加锁保护共享数据
来源：http://dali.smart0.xyz/Article/details/gtjoxbaexn.html

Py:   with lock: shared += 1
来源：http://dali.yj20258888.top/Article/details/gtwvvrctsu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.aizwys.cn/Article/details/gtvmkaobyp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.kuanghao11.cn/Article/details/gtfycjqlbi.html

TS:   // 同 JS
来源：http://dali.jinqigufen.top/Article/details/gtujjmhaos.html

Java: synchronized (this) { shared++; }
来源：http://dali.guannengcc.top/Article/details/gtqbtzvbxj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shzxlz.cn/Article/details/gtuizocyxf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.redwolf501.top/Article/details/gtevflcpfe.html

C#:   lock (gate) { shared++; }
来源：http://dali.hongshengwenyu.top/Article/details/gtqtftvjvi.html

[O04] 定义异步函数并等待
来源：http://dali.316326.xyz/Article/details/gtbqzvpsfa.html

Py:   async def f():⏎    await g()
来源：http://dali.yuxming.cn/Article/details/gtpmcowzga.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ppjwa.cn/Article/details/gtdgimvjkh.html

JS:   async function f() { await g(); }
来源：http://dali.bjfxy.top/Article/details/gtzyxnxalp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj202588.top/Article/details/gtmqshcyhs.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.gogol.net.cn/Article/details/gtiiftlwtx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shangyingyoupin.top/Article/details/gtyccowyvx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.nwbrower.top/Article/details/gtjciiclpd.html

C#:   async Task F() { await G(); }
来源：http://dali.sweek.top/Article/details/gtvxfvvfpi.html

[O05] 并发执行并等待全部完成
来源：http://dali.wangshuangyany.cn/Article/details/gtyeajxbnp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hnqzz.top/Article/details/gtlipwkdtd.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyrclsayn.html

JS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcbjesitp.html

TS:   await Promise.all(tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gtazsgdplu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.guannengcc.top/Article/details/gtpxynrbkm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.havefunace.top/Article/details/gthqpheuog.html

Ruby: threads.map(&:join)
来源：http://dali.jlsjyb.cn/Article/details/gtfmlybpvc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.havefunace.top/Article/details/gtopesawcv.html

[O06] 使用进程池
来源：http://dali.shangyingyoupin.top/Article/details/gtcijbrwfi.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.havefunace.top/Article/details/gtzjobwnqa.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.tanke756.top/Article/details/gtjfxticvy.html

JS:   // child_process / cluster 模块
来源：http://dali.c1oappe.top/Article/details/gtiijuzrpt.html


<!-- 参考信息 -->