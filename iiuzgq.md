代发 wailian999

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yvedp.cn/Article/details/gt2sknplgyy.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gogol.net.cn/Article/details/gt2rrxeaefj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nanxinkj.top/Article/details/gt2ullmkdqh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.aizwys.cn/Article/details/gt2ihgsmjxy.html

[L03] 设置自定义请求头
来源：http://dali.sweek.top/Article/details/gt2whftvfpl.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xuanzx.com/Article/details/gt2dsboqrce.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gzhubu.top/Article/details/gt2kldgcofz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hfkgxjpi.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.quarkkingdee.top/Article/details/gt2tnqaeiev.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.wangdashe.top/Article/details/gt2tuaataxi.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.nwbrower.top/Article/details/gt2anuguklm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ydzc1.top/Article/details/gt2zykqoroj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.aibaodan.cn/Article/details/gt2ixlbjqmw.html

[L04] 设置超时
来源：http://dali.nwbrower.top/Article/details/gt2iydorxhw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.aizwys.cn/Article/details/gt2fndstnfm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.meibo888.top/Article/details/gt2valyqnqy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xziqi.cn/Article/details/gt2bsunvurg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gaohongyu789.top/Article/details/gt2kcepcrjk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sufxvd.cn/Article/details/gt2eowqqnax.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hfpthk.cn/Article/details/gt2umqzkkgl.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.vqdsnc.cn/Article/details/gt2kzkmvunz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yj20258.top/Article/details/gt2ntssxouj.html

[L05] 上传文件（multipart）
来源：http://dali.chenlongwang.top/Article/details/gt2hmqkqbvk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hywenlv.cn/Article/details/gt2fxavihbg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.dianchejie.cn/Article/details/gt2kctgnibn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.iojbl.cn/Article/details/gt2jphhsstd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cqqwz.cn/Article/details/gt2wlugclht.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.snrcjt.cn/Article/details/gt2dlmehxkh.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.dianchejie.cn/Article/details/gt2eoarxolt.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.c1oappe.top/Article/details/gt2dpukcbfb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ioljjcpa.html

[L06] 解析响应为 JSON
来源：http://dali.nanxuanxn.top/Article/details/gt2oonlgmuz.html

Py:   resp.json()
来源：http://dali.svipenyu.cn/Article/details/gt2lnyznzeg.html

PHP:  json_decode($body, true);
来源：http://dali.hnxiangtu.top/Article/details/gt2wguakrzn.html

JS:   await resp.json()
来源：http://dali.zycfv.cn/Article/details/gt2xqcoujgk.html

TS:   await resp.json()
来源：http://dali.redwolf501.top/Article/details/gt2yomciwsi.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yongpay.top/Article/details/gt2vslplixe.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nanxuanxn.top/Article/details/gt2ixfzzequ.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sufxvd.cn/Article/details/gt2vgyljgri.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.quarkkingdee.top/Article/details/gt2nkwwfxkt.html

[L07] 处理 HTTP 状态码
来源：http://dali.xuetiantiany.cn/Article/details/gt2rivkatjg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ydzc1.top/Article/details/gt2bwxtrcdc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.iojbl.cn/Article/details/gt2urorenze.html

JS:   resp.ok;  resp.status
来源：http://dali.hysaishi.cn/Article/details/gt2vyeekurv.html

TS:   resp.ok;  resp.status
来源：http://dali.vqdsnc.cn/Article/details/gt2dbqhelxq.html

Java: resp.statusCode()
来源：http://dali.xylfe.cn/Article/details/gt2yttbpjbl.html

Go:   resp.StatusCode
来源：http://dali.daxiang520.top/Article/details/gt2acdycxnu.html

Ruby: resp.code.to_i
来源：http://dali.shzxlz.cn/Article/details/gt2pyhyokcb.html

C#:   (int)resp.StatusCode
来源：http://dali.ppjwa.cn/Article/details/gt2jjwqekqm.html

[L08] 并发请求多个地址
来源：http://dali.wangshuangyany.cn/Article/details/gt2ontxkpkq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cqqwz.cn/Article/details/gt2odjzboji.html

PHP:  curl_multi_init() 系列
来源：http://dali.andypj.xyz/Article/details/gt2wvvcufzf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxuanxn.top/Article/details/gt2jmpmqgfa.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2svruevvb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cdnleiting.top/Article/details/gt2lkmcjsws.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sxryk.cn/Article/details/gt2tsfnyqsz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.iojbl.cn/Article/details/gt2rloxjcil.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.aibaodan.cn/Article/details/gt2azqkdyuf.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2meikaxlr.html

M. 命令行 / 进程 / 环境
来源：http://dali.jqgufenzy.top/Article/details/gt2qeghlpmh.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2mhphdpgs.html

[M01] 读取命令行参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dxdjemlf.html

Py:   sys.argv[1:]
来源：http://dali.jqgfzy.top/Article/details/gt2wrscywke.html

PHP:  $argv;  $argc;
来源：http://dali.ehwqpu.com/Article/details/gt2llykqegf.html

JS:   process.argv.slice(2)
来源：http://dali.hywenlv.cn/Article/details/gt2yylvbxst.html

TS:   process.argv.slice(2)
来源：http://dali.jyoumei.cn/Article/details/gt2zhtimzlz.html

Java: args 数组（main 方法参数）
来源：http://dali.yonumen.top/Article/details/gt2cqfvmifk.html

Go:   os.Args[1:]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fljpsscb.html

Ruby: ARGV
来源：http://dali.ivvv.top/Article/details/gt2hrttzqbq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj20258888.top/Article/details/gt2eftwlvra.html

[M02] 读取环境变量
来源：http://dali.vqdsnc.cn/Article/details/gt2kaixffhx.html

Py:   os.environ.get("HOME")
来源：http://dali.birdmap.top/Article/details/gt2niarbuht.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.pengpengdd.cyou/Article/details/gt2pyeqipub.html

JS:   process.env.HOME
来源：http://dali.yanxiufei.cn/Article/details/gt2otleuavr.html

TS:   process.env.HOME
来源：http://dali.hnqzz.top/Article/details/gt2upgaystz.html

Java: System.getenv("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gt2dtuargco.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenlongwang.top/Article/details/gt2joztodih.html

Ruby: ENV["HOME"]
来源：http://dali.jiagoushi.top/Article/details/gt2zzrfdypx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.fzhhl.top/Article/details/gt2qdkbuclz.html

[M03] 执行外部命令
来源：http://dali.gotoacloud.top/Article/details/gt2rvvaijmq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ghbghgza.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj20258888.top/Article/details/gt2wdpwetrq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zdqjudy.top/Article/details/gt2pqodtcog.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.meibo888.top/Article/details/gt2fantmmwa.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xjvjqgyh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.dashuyun.cn/Article/details/gt2btcsijwp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cdnleiting.top/Article/details/gt2qptaxfqx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hongshengwenyu.top/Article/details/gt2gtbiybrv.html

[M04] 获取当前工作目录
来源：http://dali.shzxlz.cn/Article/details/gt2qolwhcgb.html

Py:   os.getcwd()
来源：http://dali.jqgufenzy.top/Article/details/gt2blvrwmoo.html

PHP:  getcwd();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qqllmbos.html

JS:   process.cwd()
来源：http://dali.cqqwz.cn/Article/details/gt2lxsgeznn.html

TS:   process.cwd()
来源：http://dali.jiagoushi.top/Article/details/gt2xjxejsqv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yuxming.cn/Article/details/gt2fjsdcfrn.html

Go:   os.Getwd()
来源：http://dali.yj20258.top/Article/details/gt2wiqgygzc.html

Ruby: Dir.pwd
来源：http://dali.cheryme.top/Article/details/gt2cortqber.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.tian-w.cn/Article/details/gt2mfsuipxm.html

[M05] 设置退出码
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gejpkigp.html

Py:   sys.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2axlasxqb.html

PHP:  exit(1);
来源：http://dali.dashuyun.cn/Article/details/gt2nvgpckax.html

JS:   process.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gt2lcbfzryb.html

TS:   process.exit(1)
来源：http://dali.pycfn.com/Article/details/gt2fhtrkhra.html

Java: System.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2mkbbcdog.html

Go:   os.Exit(1)
来源：http://dali.guowangkeji.top/Article/details/gt2xnafxrmd.html

Ruby: exit 1
来源：http://dali.guannengcc.top/Article/details/gt2iflgrnov.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.pengpengdd.cyou/Article/details/gt2wbqochuf.html

[M06] 向标准错误输出
来源：http://dali.yangfankeji.com/Article/details/gt2aorcrqlp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.bjfxy.top/Article/details/gt2ohdqybix.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cheryme.top/Article/details/gt2qhdwcivn.html

JS:   console.error("err")
来源：http://dali.yuxming.cn/Article/details/gt2pravwiue.html

TS:   console.error("err")
来源：http://dali.9152youxi.cn/Article/details/gt2sxekzest.html

Java: System.err.println("err")
来源：http://dali.pengpengdd.cyou/Article/details/gt2qkjmxomq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.haohaochexian.top/Article/details/gt2axltjvwh.html

Ruby: warn "err"
来源：http://dali.hywenlv.cn/Article/details/gt2upuxfilh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2seyzrksa.html

[M07] 判断是否为主入口
来源：http://dali.zhiwuduotai.top/Article/details/gt2rvstdyhf.html

Py:   if __name__ == "__main__":
来源：http://dali.gogol.net.cn/Article/details/gt2tmnbijro.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.bjfxy.top/Article/details/gt2tunymwzb.html

JS:   require.main === module
来源：http://dali.shzxlz.cn/Article/details/gt2qmqimyzl.html

TS:   require.main === module
来源：http://dali.chenzaomai.com/Article/details/gt2nkcywgoj.html

Java: public static void main(String[] args)
来源：http://dali.zhoulong.xyz/Article/details/gt2cisdqrcq.html

Go:   func main()
来源：http://dali.sxryk.cn/Article/details/gt2znvvjiko.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yj202588.top/Article/details/gt2xjovurkb.html

C#:   static void Main(string[] args)
来源：http://dali.ybcxt.top/Article/details/gt2sxnqypmq.html

[M08] 获取系统与运行时信息
来源：http://dali.meibo888.top/Article/details/gt2jqemrruz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cheryme.top/Article/details/gt2mybptqsw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xziqi.cn/Article/details/gt2zewrjtkz.html

JS:   process.platform;  process.version
来源：http://dali.chenlongwang.top/Article/details/gt2dpstdlox.html

TS:   process.platform;  process.version
来源：http://dali.jyoumei.cn/Article/details/gt2atyudbzt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sufxvd.cn/Article/details/gt2rzofdnzu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xylfe.cn/Article/details/gt2iggdfozi.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wfcnwdfy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.meibo888.top/Article/details/gt2qxjnnnhb.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2vzytypmk.html

N. 数据结构与算法
来源：http://dali.xylfe.cn/Article/details/gt2vgbnuqbc.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2dcqednvi.html

[N01] 二分查找（有序数组）
来源：http://dali.chenlongwang.top/Article/details/gt2yzevmiib.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gt2ymvtmfxp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jyoumei.cn/Article/details/gt2zneaefye.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.bjfxy.top/Article/details/gt2rqkmflxm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ivvv.top/Article/details/gt2mljaqxff.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.smart0.xyz/Article/details/gt2baiuosuc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gt2htxkglrq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yongpay.top/Article/details/gt2zwbgicpw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gt2qgmtznkq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hammf.cn/Article/details/gt2hlmunocu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258.top/Article/details/gt2rkgxjnxa.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.guowangkeji.top/Article/details/gt2rmfaeyjc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guowangkeji.top/Article/details/gt2gtpuohoh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fengsongda.top/Article/details/gt2hbbtxemd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xziqi.cn/Article/details/gt2vviywjkk.html

Go:   slices.Sort(arr)
来源：http://dali.hammf.cn/Article/details/gt2oefzchma.html

Ruby: arr.sort
来源：http://dali.smart0.xyz/Article/details/gt2etiouxsk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yongpay.top/Article/details/gt2wervtted.html

[N03] 快速排序（分治示例）
来源：http://dali.jqgufenzy.top/Article/details/gt2flldfuhx.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xjruwnyb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.chenzaomai.com/Article/details/gt2qwlapjak.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guowangkeji.top/Article/details/gt2fmnqubos.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aibaodan.cn/Article/details/gt2aqfoffem.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yuanzhike.top/Article/details/gt2piywmmgn.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sysykeji.top/Article/details/gt2hxjdaboq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jzzepuux.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jlsjyb.cn/Article/details/gt2erxplmua.html

[N04] 斐波那契数列
来源：http://dali.meibo888.top/Article/details/gt2adirqkvn.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.wangdashe.top/Article/details/gt2nxxdpexr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jlsjyb.cn/Article/details/gt2auwnyngu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuetiantiany.cn/Article/details/gt2apbuxutp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.birdmap.top/Article/details/gt2nihixiwe.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2aajkybhr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yj20258.top/Article/details/gt2odcwpaik.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hnxiangtu.top/Article/details/gt2okpqbmnl.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hywenlv.cn/Article/details/gt2wcdohcth.html

[N05] 最大公约数
来源：http://dali.gaohongyu789.top/Article/details/gt2nvypjqqp.html

Py:   math.gcd(a, b)
来源：http://dali.cdnleiting.top/Article/details/gt2boldyrhe.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gotoacloud.top/Article/details/gt2cwlobvha.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhengqikj.top/Article/details/gt2pwnvungg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yvedp.cn/Article/details/gt2korzssll.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.dianchejie.cn/Article/details/gt2xtgmrcuq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinqigufen.top/Article/details/gt2rdhvvhmr.html

Ruby: a.gcd(b)
来源：http://dali.birdmap.top/Article/details/gt2gmqitxtw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cashguo.top/Article/details/gt2ysxyzprc.html

[N06] 判断回文字符串
来源：http://dali.iojbl.cn/Article/details/gt2kfdcblho.html

Py:   s == s[::-1]
来源：http://dali.jqgfzy.top/Article/details/gt2orhmsjrk.html

PHP:  $s === strrev($s);
来源：http://dali.yvedp.cn/Article/details/gt2nbakquqs.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gt2smoaqcji.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gt2dyvdvrez.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yanxiufei.cn/Article/details/gt2phsczxob.html

Go:   // 双指针从两端比较
来源：http://dali.shzxlz.cn/Article/details/gt2zadudrul.html

Ruby: s == s.reverse
来源：http://dali.zhengqikj.top/Article/details/gt2nasanqul.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.aizwys.cn/Article/details/gt2ecygilzz.html

[N07] 两数之和（返回下标）
来源：http://dali.shuidangran.top/Article/details/gt2kujylesl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hnxiangtu.top/Article/details/gt2wkmijhna.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shuidangran.top/Article/details/gt2ccofwjzd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.mhx1999.top/Article/details/gt2krqfwhfl.html

TS:   // 手写 Map<string, number>
来源：http://dali.bjfxy.top/Article/details/gt2wvnqtyot.html

Java: // 手写 HashMap
来源：http://dali.tianlin.xyz/Article/details/gt2kqldqitk.html

Go:   // 手写 map[int]int
来源：http://dali.hnqzz.top/Article/details/gt2wtftwcpl.html

Ruby: // 手写 Hash
来源：http://dali.zycfv.cn/Article/details/gt2wlpucgsa.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yuanzhike.top/Article/details/gt2cllityjb.html

[N08] 生成全排列
来源：http://dali.gotoacloud.top/Article/details/gt2bqdhmecp.html

Py:   itertools.permutations(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2kdhlnobj.html

PHP:  // 手写递归交换
来源：http://dali.nanxuanxn.top/Article/details/gt2nzwyxern.html

JS:   // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gt2nrgwlpeg.html

TS:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gt2abarzrat.html

Java: // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gt2tvrtsrhe.html

Go:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gt2pflkqwji.html

Ruby: arr.permutation.to_a
来源：http://dali.zhiwuduotai.top/Article/details/gt2pkdexsej.html

C#:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gt2ttqhcenq.html

[N09] 栈与队列
来源：http://dali.yanxiufei.cn/Article/details/gt2kbdbcnef.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gogol.net.cn/Article/details/gt2bivqpnpr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jqgufenzy.top/Article/details/gt2drlewxrp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yanxiufei.cn/Article/details/gt2ysymjcsy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jyoumei.cn/Article/details/gt2yoieymrb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zycfv.cn/Article/details/gt2qmoyzkuh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.chenjidiqi.icu/Article/details/gt2vsycjasr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.havefunace.top/Article/details/gt2hhctwlqu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.wangshuangyany.cn/Article/details/gt2dhbgrqmc.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhhdwkn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jiagoushi.top/Article/details/gt2lzwtgvmd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.quarkkingdee.top/Article/details/gt2tmailyda.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yj202588.top/Article/details/gt2jrzaygvz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hfpthk.cn/Article/details/gt2zwvlfnxw.html

Java: class Node { int v; Node next; }
来源：http://dali.shuidangran.top/Article/details/gt2jqnritbl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.nanxinkj.top/Article/details/gt2jrosxruo.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.pengpengdd.cyou/Article/details/gt2kcvfmtku.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yongpay.top/Article/details/gt2szkfnnkk.html

[N11] 二叉树中序遍历
来源：http://dali.ppjwa.cn/Article/details/gt2zkjlrqdw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yanxiufei.cn/Article/details/gt2fsdpztzt.html

PHP:  // 手写递归函数
来源：http://dali.zhixingplan.top/Article/details/gt2uedgmhmh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hammf.cn/Article/details/gt2ytisocmh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hywenlv.cn/Article/details/gt2zuguwtdn.html

Java: // 手写递归
来源：http://dali.sufxvd.cn/Article/details/gt2jbplmjeh.html

Go:   // 手写递归
来源：http://dali.jinqigufen.top/Article/details/gt2sahewvgq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.chenlongwang.top/Article/details/gt2uvaiqdxb.html

C#:   // 手写递归
来源：http://dali.dianchejie.cn/Article/details/gt2vubikoqc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ybcxt.top/Article/details/gt2jvockfyl.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.c1oappe.top/Article/details/gt2squsyjfq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.nanxuanxn.top/Article/details/gt2oejfartf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hywenlv.cn/Article/details/gt2qhjhiyqy.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.andypj.xyz/Article/details/gt2pfkrvywa.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenzaomai.com/Article/details/gt2sjkxtyvf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ivvv.top/Article/details/gt2fbxiknkd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.0kj1m.cn/Article/details/gt2ssiasijn.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jiagoushi.top/Article/details/gt2yhvjtzjy.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2nlpuebpm.html

O. 并发与异步
来源：http://dali.ehwqpu.com/Article/details/gt2vvmxrrxo.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2zmesoxrl.html

[O01] 启动一个线程
来源：http://dali.vqdsnc.cn/Article/details/gt2wmvphdml.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cdnleiting.top/Article/details/gt2zemzzcnk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ydzc1.top/Article/details/gt2yhmstebt.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.daria6918.cn/Article/details/gt2avwcyqfb.html

TS:   // 同 JS
来源：http://dali.ivvv.top/Article/details/gt2btjsvyta.html

Java: new Thread(() -> f()).start()
来源：http://dali.dianchejie.cn/Article/details/gt2jktwzzqg.html

Go:   go f()
来源：http://dali.hammf.cn/Article/details/gt2tjemezci.html

Ruby: Thread.new { f }
来源：http://dali.cqqwz.cn/Article/details/gt2uzuveuyu.html

C#:   Task.Run(() => F());
来源：http://dali.tanke756.top/Article/details/gt2afkcctps.html

[O02] 使用线程池
来源：http://dali.xziqi.cn/Article/details/gt2dfkgztjw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhoulong.xyz/Article/details/gt2hmkrpiuh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hfpthk.cn/Article/details/gt2rtnnnxiy.html

JS:   // worker_threads 线程池
来源：http://dali.fzhhl.top/Article/details/gt2tkwzwdrm.html

TS:   // worker_threads 线程池
来源：http://dali.smart0.xyz/Article/details/gt2hwimeyxx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.tanke756.top/Article/details/gt2tbtgtyzc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.andypj.xyz/Article/details/gt2vfkjefym.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.meibo888.top/Article/details/gt2xcvcbcho.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.chenjidiqi.icu/Article/details/gt2gjbfzxqe.html

[O03] 加锁保护共享数据
来源：http://dali.ppjwa.cn/Article/details/gt2xjpotpmq.html

Py:   with lock: shared += 1
来源：http://dali.quarkkingdee.top/Article/details/gt2yhzydtiy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.tian-w.cn/Article/details/gt2vfuywkuk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinqigfzy.top/Article/details/gt2libikfdr.html

TS:   // 同 JS
来源：http://dali.xinyue.icu/Article/details/gt2cerlkzme.html

Java: synchronized (this) { shared++; }
来源：http://dali.yueranfly.top/Article/details/gt2wfocuody.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cdnleiting.top/Article/details/gt2sqfdmctf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhixingplan.top/Article/details/gt2rknrjrqr.html

C#:   lock (gate) { shared++; }
来源：http://dali.kuanghao11.cn/Article/details/gt2tdqoafaz.html

[O04] 定义异步函数并等待
来源：http://dali.aibaodan.cn/Article/details/gt2ujopzhch.html

Py:   async def f():⏎    await g()
来源：http://dali.hywenlv.cn/Article/details/gt2xionxcsq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.c1oappe.top/Article/details/gt2acebcfvm.html

JS:   async function f() { await g(); }
来源：http://dali.zhixingplan.top/Article/details/gt2qttawvcv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.iojbl.cn/Article/details/gt2zagjqcvm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yongpay.top/Article/details/gt2uvjrjvpd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sysykeji.top/Article/details/gt2mvycktfq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xylfe.cn/Article/details/gt2lbqkpuud.html

C#:   async Task F() { await G(); }
来源：http://dali.sufxvd.cn/Article/details/gt2btehkidg.html

[O05] 并发执行并等待全部完成
来源：http://dali.aizwys.cn/Article/details/gt2fhnintqu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cucudq.cn/Article/details/gt2tujfmllm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sysykeji.top/Article/details/gt2cpwxmqfy.html

JS:   await Promise.all(tasks)
来源：http://dali.cucudq.cn/Article/details/gt2ojtsjivs.html

TS:   await Promise.all(tasks)
来源：http://dali.andypj.xyz/Article/details/gt2mdlrjsxi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.haohaochexian.top/Article/details/gt2bqxndmbf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.dashuyun.cn/Article/details/gt2fnljkfad.html

Ruby: threads.map(&:join)
来源：http://dali.havefunace.top/Article/details/gt2esyfkhnc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.dashuyun.cn/Article/details/gt2solzwswj.html

[O06] 使用进程池
来源：http://dali.pycfn.com/Article/details/gt2uxophzeo.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhiwuduotai.top/Article/details/gt2zmpliwob.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.chenlongwang.top/Article/details/gt2qpkwbvhx.html

JS:   // child_process / cluster 模块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tpjlyuky.html

TS:   // child_process / cluster 模块
来源：http://dali.jiagoushi.top/Article/details/gt2qehlqhiv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gzhubu.top/Article/details/gt2dortedrs.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yj20258.top/Article/details/gt2ymtjaaon.html

Ruby: // fork 块
来源：http://dali.wangshuangyany.cn/Article/details/gt2zrepeetj.html


<!-- 参考信息 -->