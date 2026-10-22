代发 wailian999

Go:   resp, err := http.Get(url)
来源：http://dali.aizwys.cn/Article/details/gtqtlpjabx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hywenlv.cn/Article/details/gtzfjimwwz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.feifeiyinyue.top/Article/details/gtddnnepja.html

[L02] 发送 POST JSON
来源：http://dali.chenjidiqi.icu/Article/details/gtithlmzxt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shuidangran.top/Article/details/gtkahiaxbd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yj20258.top/Article/details/gtuepobtxx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.andypj.xyz/Article/details/gtijgxmczj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnxiangtu.top/Article/details/gtncoaqqzr.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yvedp.cn/Article/details/gtngunwbeu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.aibaodan.cn/Article/details/gtylautavf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ehwqpu.com/Article/details/gtusngrnli.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hnxiangtu.top/Article/details/gtdxvdxfco.html

[L03] 设置自定义请求头
来源：http://dali.birdmap.top/Article/details/gtzlkmjfta.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jiagoushi.top/Article/details/gtktxcvnxi.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtacoeivwt.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yonumen.top/Article/details/gtjsesdldo.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuxming.cn/Article/details/gtfotidvnj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.dianchejie.cn/Article/details/gtgykqwbqs.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gogol.net.cn/Article/details/gtichgmgde.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj20258.top/Article/details/gtxlgqrbou.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yj20258.top/Article/details/gtiwbppzga.html

[L04] 设置超时
来源：http://dali.ybcxt.top/Article/details/gtzzkysgdn.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqjndbyat.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xuetiantiany.cn/Article/details/gtrcbvghae.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gogol.net.cn/Article/details/gtkxoddmgc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hongshengwenyu.top/Article/details/gtqkgietjv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.vqdsnc.cn/Article/details/gtedgzthzz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhixingplan.top/Article/details/gtnvagrscf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.guannengcc.top/Article/details/gthjwjeemk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hnqzz.top/Article/details/gtagfuwbgb.html

[L05] 上传文件（multipart）
来源：http://dali.shuidangran.top/Article/details/gtoarozctf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jiagoushi.top/Article/details/gtsaqaldja.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.daxiang520.top/Article/details/gthdeaenat.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shangyingyoupin.top/Article/details/gtivjmisaq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenlongwang.top/Article/details/gtbdivwtig.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.kuanghao11.cn/Article/details/gtxithqvok.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yuanzhike.top/Article/details/gttwtqpgjx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.9152youxi.cn/Article/details/gtdtuylkvd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hammf.cn/Article/details/gtsrtzyiod.html

[L06] 解析响应为 JSON
来源：http://dali.jinghuilouyu.cn/Article/details/gtvmzayldw.html

Py:   resp.json()
来源：http://dali.nanxinkj.top/Article/details/gtcgxladwn.html

PHP:  json_decode($body, true);
来源：http://dali.xuanzx.com/Article/details/gtgpnaolvp.html

JS:   await resp.json()
来源：http://dali.sysykeji.top/Article/details/gtojufakfq.html

TS:   await resp.json()
来源：http://dali.c1oappe.top/Article/details/gtcgusxwix.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.vqdsnc.cn/Article/details/gtjcufyaeu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jiagoushi.top/Article/details/gtwgtrxipr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.wangdashe.top/Article/details/gtwuwqikpg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cheryme.top/Article/details/gtkjgavuyo.html

[L07] 处理 HTTP 状态码
来源：http://dali.jianghu66.top/Article/details/gtibwamgog.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jiagoushi.top/Article/details/gtmavutthg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hongshengwenyu.top/Article/details/gtiklzkcuy.html

JS:   resp.ok;  resp.status
来源：http://dali.daria6918.cn/Article/details/gtrmnvgxza.html

TS:   resp.ok;  resp.status
来源：http://dali.svipenyu.cn/Article/details/gtthjadkrs.html

Java: resp.statusCode()
来源：http://dali.wangdashe.top/Article/details/gtxzcemopb.html

Go:   resp.StatusCode
来源：http://dali.zhongyouzk.top/Article/details/gtcsxtsdvh.html

Ruby: resp.code.to_i
来源：http://dali.ivvv.top/Article/details/gtclenciku.html

C#:   (int)resp.StatusCode
来源：http://dali.fengsongda.top/Article/details/gtcnkyhsjm.html

[L08] 并发请求多个地址
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwfpnbwkh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.0kj1m.cn/Article/details/gtbgtfszmc.html

PHP:  curl_multi_init() 系列
来源：http://dali.shuidangran.top/Article/details/gtinnbmcja.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gtulvolvqy.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.havefunace.top/Article/details/gtcasszmzp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ehwqpu.com/Article/details/gtswauopjz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xinyue.icu/Article/details/gtekcmghrs.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.nanxinkj.top/Article/details/gtmwhzbebr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjfvrnhks.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtlwgiypbx.html

M. 命令行 / 进程 / 环境
来源：http://dali.jqgfzy.top/Article/details/gtymszcdky.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtramdmlhw.html

[M01] 读取命令行参数
来源：http://dali.9152youxi.cn/Article/details/gtqbkbivir.html

Py:   sys.argv[1:]
来源：http://dali.daxiang520.top/Article/details/gtossxbzkm.html

PHP:  $argv;  $argc;
来源：http://dali.birdmap.top/Article/details/gtuvtacwyl.html

JS:   process.argv.slice(2)
来源：http://dali.0kj1m.cn/Article/details/gtnmiijdyp.html

TS:   process.argv.slice(2)
来源：http://dali.guowangkeji.top/Article/details/gtcbsvbyat.html

Java: args 数组（main 方法参数）
来源：http://dali.9152youxi.cn/Article/details/gtprrcsjtg.html

Go:   os.Args[1:]
来源：http://dali.zhengqikj.top/Article/details/gtrkassniq.html

Ruby: ARGV
来源：http://dali.hfpthk.cn/Article/details/gtnzikytab.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhengqikj.top/Article/details/gtjdixelgy.html

[M02] 读取环境变量
来源：http://dali.wangshuangyany.cn/Article/details/gtfzrpwxjz.html

Py:   os.environ.get("HOME")
来源：http://dali.hfpthk.cn/Article/details/gtomdcffzi.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hammf.cn/Article/details/gtzsdnesdu.html

JS:   process.env.HOME
来源：http://dali.xinyue.icu/Article/details/gtvahdrasb.html

TS:   process.env.HOME
来源：http://dali.gaohongyu789.top/Article/details/gtibjebwzt.html

Java: System.getenv("HOME")
来源：http://dali.fengsongda.top/Article/details/gtfisqspye.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hammf.cn/Article/details/gtjqptmcev.html

Ruby: ENV["HOME"]
来源：http://dali.fengsongda.top/Article/details/gtprqngnqc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zdqjudy.top/Article/details/gtbswstihv.html

[M03] 执行外部命令
来源：http://dali.jianghu66.top/Article/details/gtcipzispe.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.wangdashe.top/Article/details/gtjvzhdjta.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.kuanghao11.cn/Article/details/gtjoqpvcol.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hammf.cn/Article/details/gtcphrdnfq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hongshengwenyu.top/Article/details/gtkkhtcqhx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ybcxt.top/Article/details/gtbvifoodg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nanxuanxn.top/Article/details/gthlslcnhc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jqgfzy.top/Article/details/gtmratpfch.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yonumen.top/Article/details/gtaorjlzap.html

[M04] 获取当前工作目录
来源：http://dali.gzhubu.top/Article/details/gthdokaixe.html

Py:   os.getcwd()
来源：http://dali.yangfankeji.com/Article/details/gtjgxnybcv.html

PHP:  getcwd();
来源：http://dali.hywenlv.cn/Article/details/gtjsxngvqu.html

JS:   process.cwd()
来源：http://dali.zhixingplan.top/Article/details/gtrxtpxanb.html

TS:   process.cwd()
来源：http://dali.chenzaomai.com/Article/details/gtaqdrwlxf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.quarkkingdee.top/Article/details/gtsuzvvuqh.html

Go:   os.Getwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gttsqcwwgx.html

Ruby: Dir.pwd
来源：http://dali.hywenlv.cn/Article/details/gtcjojtwaw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.svipenyu.cn/Article/details/gttbpmnjsw.html

[M05] 设置退出码
来源：http://dali.dashuyun.cn/Article/details/gtshyhqixw.html

Py:   sys.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtvpltjskt.html

PHP:  exit(1);
来源：http://dali.xuetiantiany.cn/Article/details/gtsifkptxm.html

JS:   process.exit(1)
来源：http://dali.tanke756.top/Article/details/gthrwkhiet.html

TS:   process.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtjcmsvygz.html

Java: System.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gtdweqfrdk.html

Go:   os.Exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtbvwlzxbu.html

Ruby: exit 1
来源：http://dali.aibaodan.cn/Article/details/gtqvoznxth.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xziqi.cn/Article/details/gtwquuecmk.html

[M06] 向标准错误输出
来源：http://dali.jinqigufen.top/Article/details/gtidydklcc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.nanxuanxn.top/Article/details/gtqqqsrtxb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xuetiantiany.cn/Article/details/gtssztavxy.html

JS:   console.error("err")
来源：http://dali.bjfxy.top/Article/details/gtoyaskbro.html

TS:   console.error("err")
来源：http://dali.haohaochexian.top/Article/details/gtaqhtswxz.html

Java: System.err.println("err")
来源：http://dali.nanxinkj.top/Article/details/gtknejvohu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.andypj.xyz/Article/details/gtbrovjnia.html

Ruby: warn "err"
来源：http://dali.cdnleiting.top/Article/details/gtjjvjxvap.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jlsjyb.cn/Article/details/gtafngsegx.html

[M07] 判断是否为主入口
来源：http://dali.snrcjt.cn/Article/details/gtruxuqdhq.html

Py:   if __name__ == "__main__":
来源：http://dali.xziqi.cn/Article/details/gtdbpmijhh.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gotoacloud.top/Article/details/gtmrgpdrpm.html

JS:   require.main === module
来源：http://dali.jiagoushi.top/Article/details/gtpbftdmyy.html

TS:   require.main === module
来源：http://dali.zhiwuduotai.top/Article/details/gtpfkmtxeo.html

Java: public static void main(String[] args)
来源：http://dali.0kj1m.cn/Article/details/gtaoswescz.html

Go:   func main()
来源：http://dali.tianlin.xyz/Article/details/gtkcgjgsxc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hywenlv.cn/Article/details/gtwalrscjx.html

C#:   static void Main(string[] args)
来源：http://dali.pengpengdd.cyou/Article/details/gtuyfamiwa.html

[M08] 获取系统与运行时信息
来源：http://dali.chenlongwang.top/Article/details/gtifnhrrbk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj202588.top/Article/details/gtvyfxirvv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xylfe.cn/Article/details/gthotljujy.html

JS:   process.platform;  process.version
来源：http://dali.ppjwa.cn/Article/details/gtqunjhwvh.html

TS:   process.platform;  process.version
来源：http://dali.yj202588.top/Article/details/gtsbflqdod.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhoulong.xyz/Article/details/gtjuosppig.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yangfankeji.com/Article/details/gtdorgtefe.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.9152youxi.cn/Article/details/gtsnsyarjb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.pycfn.com/Article/details/gtaybytlws.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtnicfvbmm.html

N. 数据结构与算法
来源：http://dali.hnxiangtu.top/Article/details/gtkzbggtkc.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtivpyfgel.html

[N01] 二分查找（有序数组）
来源：http://dali.xuanzx.com/Article/details/gtycctsosn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gtvxiigrhx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sweek.top/Article/details/gtljogpwon.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgufenzy.top/Article/details/gtfmmmqvik.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hammf.cn/Article/details/gtcjizypxm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtyrwwksgj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtpjjmbpqb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yuxming.cn/Article/details/gtkyysdwhn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtilvitevy.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gaohongyu789.top/Article/details/gtgxflrcim.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.bjfxy.top/Article/details/gtxsqxokxg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cqqwz.cn/Article/details/gtyojpydud.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dashuyun.cn/Article/details/gtamvzcpmz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangdashe.top/Article/details/gtpdrhjpgi.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.snrcjt.cn/Article/details/gtkbdodgmc.html

Go:   slices.Sort(arr)
来源：http://dali.jianghu66.top/Article/details/gtlodtxcrp.html

Ruby: arr.sort
来源：http://dali.guowangkeji.top/Article/details/gtpqvhrumq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shuidangran.top/Article/details/gtuafwwzex.html

[N03] 快速排序（分治示例）
来源：http://dali.hammf.cn/Article/details/gtsgrgeuib.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shzxlz.cn/Article/details/gtbdktdxmj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hywenlv.cn/Article/details/gtrqxemtcv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dashuyun.cn/Article/details/gtndvqijfe.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.bjfxy.top/Article/details/gtjcfkkxio.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hnqzz.top/Article/details/gtknoevadg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.daria6918.cn/Article/details/gtzwxkrrxa.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shangyingyoupin.top/Article/details/gtffuejcld.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.9152youxi.cn/Article/details/gtotezfekv.html

[N04] 斐波那契数列
来源：http://dali.sufxvd.cn/Article/details/gtpajtzlzj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.aizwys.cn/Article/details/gtwfvbicyh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.snrcjt.cn/Article/details/gtokdkxxie.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.havefunace.top/Article/details/gtkcpbbzfe.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dianchejie.cn/Article/details/gtypdscati.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shangyingyoupin.top/Article/details/gtukrukbwy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.aizwys.cn/Article/details/gtnifgykvr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yuanzhike.top/Article/details/gtqhzmwblc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gtyvfqzwmu.html

[N05] 最大公约数
来源：http://dali.jqgufenzy.top/Article/details/gtgxgrlvhm.html

Py:   math.gcd(a, b)
来源：http://dali.shzxlz.cn/Article/details/gtluamvxdk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shangyingyoupin.top/Article/details/gtcvfnjaoa.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.redwolf501.top/Article/details/gtlakprarz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuetiantiany.cn/Article/details/gtbvgclwzn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yj202588.top/Article/details/gtkqhgzenx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ydzc1.top/Article/details/gtbytlgjjl.html

Ruby: a.gcd(b)
来源：http://dali.pengpengdd.cyou/Article/details/gtyicsqoid.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhongyouzk.top/Article/details/gtxstmhegj.html

[N06] 判断回文字符串
来源：http://dali.xziqi.cn/Article/details/gtavokgibq.html

Py:   s == s[::-1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsxkpyziy.html

PHP:  $s === strrev($s);
来源：http://dali.dianchejie.cn/Article/details/gtzbbnsqbu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gtzpmizfbo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gtspolgvqp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jqgfzy.top/Article/details/gtdnbuldqz.html

Go:   // 双指针从两端比较
来源：http://dali.hysaishi.cn/Article/details/gtlvqalhzn.html

Ruby: s == s.reverse
来源：http://dali.gogol.net.cn/Article/details/gtuvvfbjvt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.dashuyun.cn/Article/details/gtssynqakz.html

[N07] 两数之和（返回下标）
来源：http://dali.hammf.cn/Article/details/gtjhmdedhv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gogol.net.cn/Article/details/gteondonnc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.guowangkeji.top/Article/details/gtjwzfkkwv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xuanzx.com/Article/details/gtctanlvbb.html

TS:   // 手写 Map<string, number>
来源：http://dali.jianghu66.top/Article/details/gtfcnrbaqu.html

Java: // 手写 HashMap
来源：http://dali.jqgufenzy.top/Article/details/gtkvsnecyw.html

Go:   // 手写 map[int]int
来源：http://dali.316326.xyz/Article/details/gtzzduneyb.html

Ruby: // 手写 Hash
来源：http://dali.zhiwuduotai.top/Article/details/gtmtxkntgp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hongshengwenyu.top/Article/details/gtzzxmetda.html

[N08] 生成全排列
来源：http://dali.cucudq.cn/Article/details/gtbirdafsk.html

Py:   itertools.permutations(arr)
来源：http://dali.shzxlz.cn/Article/details/gtznwljlyd.html

PHP:  // 手写递归交换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoadmjikg.html

JS:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gtvdvtlzxn.html

TS:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwlmxnmjc.html

Java: // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gtqhiecuwi.html

Go:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gthhgqtbqo.html

Ruby: arr.permutation.to_a
来源：http://dali.feifeiyinyue.top/Article/details/gtfmvdeaok.html

C#:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gtjzjvggtw.html

[N09] 栈与队列
来源：http://dali.smart0.xyz/Article/details/gtkofqriwf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.quarkkingdee.top/Article/details/gtgjysapvx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yueranfly.top/Article/details/gtwkjveztz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sxryk.cn/Article/details/gtubhakykh.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhengqikj.top/Article/details/gtvsyiwrsx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.mhx1999.top/Article/details/gtkyomxnqo.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinqigufen.top/Article/details/gtqxoxqxem.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xinyue.icu/Article/details/gthdkmfnab.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yanxiufei.cn/Article/details/gtiozuxlft.html

[N10] 链表节点定义
来源：http://dali.jiagoushi.top/Article/details/gtnaruhgfi.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.dashuyun.cn/Article/details/gtkqyaixbd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jyoumei.cn/Article/details/gtbkgsdora.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yuxming.cn/Article/details/gtgoqxrxjg.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shuidangran.top/Article/details/gtoyyejvcf.html

Java: class Node { int v; Node next; }
来源：http://dali.zhoulong.xyz/Article/details/gtohgqajag.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.nwbrower.top/Article/details/gtyxrjiffq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.0kj1m.cn/Article/details/gtwkxhndwr.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.birdmap.top/Article/details/gtummgoyyj.html

[N11] 二叉树中序遍历
来源：http://dali.hfpthk.cn/Article/details/gtvuhngdqn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.9152youxi.cn/Article/details/gtlfyffice.html

PHP:  // 手写递归函数
来源：http://dali.hnqzz.top/Article/details/gtmeabqphd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhongyouzk.top/Article/details/gtqlsywnbp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrcankhpu.html

Java: // 手写递归
来源：http://dali.yvedp.cn/Article/details/gtmdbugmdh.html

Go:   // 手写递归
来源：http://dali.xuetiantiany.cn/Article/details/gtdadfkaod.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhiwuduotai.top/Article/details/gtnkbaobka.html

C#:   // 手写递归
来源：http://dali.yj202588.top/Article/details/gtjrlcnenx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xuanzx.com/Article/details/gtdawfkhuf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.sufxvd.cn/Article/details/gtubvlkuob.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.quarkkingdee.top/Article/details/gtxbyayevu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yonumen.top/Article/details/gtmrgphnhj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.andypj.xyz/Article/details/gtpqmwvovt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenjidiqi.icu/Article/details/gtlwrfkdpn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.redwolf501.top/Article/details/gtlprltxta.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cucudq.cn/Article/details/gtcngoihbj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hywenlv.cn/Article/details/gtideydpax.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gthpipmilr.html

O. 并发与异步
来源：http://dali.kuanghao11.cn/Article/details/gtzwrsuvms.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtmvrwimmo.html

[O01] 启动一个线程
来源：http://dali.jinqigufen.top/Article/details/gtwjdhmcer.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hnqzz.top/Article/details/gtdssvkkba.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.andypj.xyz/Article/details/gtgswxbsto.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jiagoushi.top/Article/details/gtvljxomwy.html

TS:   // 同 JS
来源：http://dali.ywan-chungtsiang.top/Article/details/gtegzkjytf.html

Java: new Thread(() -> f()).start()
来源：http://dali.yangfankeji.com/Article/details/gtkimvknna.html

Go:   go f()
来源：http://dali.ppjwa.cn/Article/details/gtrkneokdm.html

Ruby: Thread.new { f }
来源：http://dali.0kj1m.cn/Article/details/gtfyxghyhs.html

C#:   Task.Run(() => F());
来源：http://dali.hnxiangtu.top/Article/details/gtbjemzmjw.html

[O02] 使用线程池
来源：http://dali.vqdsnc.cn/Article/details/gtjrypftsc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.daxiang520.top/Article/details/gttacdhqwj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yj20258.top/Article/details/gtwbhbkoin.html

JS:   // worker_threads 线程池
来源：http://dali.quarkkingdee.top/Article/details/gtbxdchpft.html

TS:   // worker_threads 线程池
来源：http://dali.nanxinkj.top/Article/details/gtsxyovpkz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.0kj1m.cn/Article/details/gtujmzxosk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.daxiang520.top/Article/details/gtqadmvqpg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yangfankeji.com/Article/details/gtfrchhzra.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gzhubu.top/Article/details/gtkmcfppwh.html

[O03] 加锁保护共享数据
来源：http://dali.yonumen.top/Article/details/gtlkpwnetp.html

Py:   with lock: shared += 1
来源：http://dali.ivvv.top/Article/details/gthtmnnrtr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.nwbrower.top/Article/details/gtevjheudn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jianghu66.top/Article/details/gtpxrvjmdt.html

TS:   // 同 JS
来源：http://dali.jiagoushi.top/Article/details/gtpbspljit.html

Java: synchronized (this) { shared++; }
来源：http://dali.jiagoushi.top/Article/details/gtfruinxri.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yj20258888.top/Article/details/gtpdawxvql.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.pengpengdd.cyou/Article/details/gtzeocedrj.html

C#:   lock (gate) { shared++; }
来源：http://dali.xziqi.cn/Article/details/gtyxpcpode.html

[O04] 定义异步函数并等待
来源：http://dali.ppjwa.cn/Article/details/gtmtnvozub.html

Py:   async def f():⏎    await g()
来源：http://dali.hnqzz.top/Article/details/gtzkfkvzbr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.snrcjt.cn/Article/details/gtirwytsyi.html

JS:   async function f() { await g(); }
来源：http://dali.gaohongyu789.top/Article/details/gtnmtvwgxu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sysykeji.top/Article/details/gtvhdhkbri.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hongshengwenyu.top/Article/details/gttmbvdqne.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhiwuduotai.top/Article/details/gtxptgvvfz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yj20258888.top/Article/details/gtenxbvrmg.html

C#:   async Task F() { await G(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpwtrthed.html

[O05] 并发执行并等待全部完成
来源：http://dali.ivvv.top/Article/details/gtjvoocdem.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gtinokkzyh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.chenlongwang.top/Article/details/gteebgkcll.html

JS:   await Promise.all(tasks)
来源：http://dali.nwbrower.top/Article/details/gtavdcubcj.html

TS:   await Promise.all(tasks)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmlkdjooy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmlvsmool.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhengqikj.top/Article/details/gtahgogmdy.html

Ruby: threads.map(&:join)
来源：http://dali.jinqigfzy.top/Article/details/gtnhkfvior.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhiwuduotai.top/Article/details/gtbwgeqmxy.html


<!-- 参考信息 -->