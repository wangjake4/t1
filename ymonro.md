代发 wailian999

[L03] 设置自定义请求头
来源：http://dali.wangshuangyany.cn/Article/details/gt2bzhdnkpe.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hnqzz.top/Article/details/gt2usyuvtkk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.havefunace.top/Article/details/gt2pnlwxkmk.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxinkj.top/Article/details/gt2lkzoxmqj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenzaomai.com/Article/details/gt2zfzswajc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ydzc1.top/Article/details/gt2jpiretho.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinqigufen.top/Article/details/gt2icdmrgkq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shangyingyoupin.top/Article/details/gt2rxruhpna.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sysykeji.top/Article/details/gt2zyyzqubt.html

[L04] 设置超时
来源：http://dali.gzhubu.top/Article/details/gt2brqpsnlr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yongpay.top/Article/details/gt2bogtxtnt.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.andypj.xyz/Article/details/gt2akdltgdn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shangyingyoupin.top/Article/details/gt2whjahnpf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgfzy.top/Article/details/gt2rqfvzpsj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sweek.top/Article/details/gt2xjgquxny.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gzhubu.top/Article/details/gt2ctmqwckc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj20258.top/Article/details/gt2nylakrvq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jyoumei.cn/Article/details/gt2ibxndiyg.html

[L05] 上传文件（multipart）
来源：http://dali.haohaochexian.top/Article/details/gt2vboiqhcg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hammf.cn/Article/details/gt2othqnjco.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jsfcupxu.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2alrcepki.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.316326.xyz/Article/details/gt2crusaplg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jqgufenzy.top/Article/details/gt2mxmkuhvk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zycfv.cn/Article/details/gt2fyynfhbc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cdnleiting.top/Article/details/gt2vkbhsimq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gt2motylrov.html

[L06] 解析响应为 JSON
来源：http://dali.cheryme.top/Article/details/gt2vupsiodm.html

Py:   resp.json()
来源：http://dali.snrcjt.cn/Article/details/gt2xnrwpxqb.html

PHP:  json_decode($body, true);
来源：http://dali.xziqi.cn/Article/details/gt2zbxqdjzk.html

JS:   await resp.json()
来源：http://dali.wangshuangyany.cn/Article/details/gt2wojeercq.html

TS:   await resp.json()
来源：http://dali.hammf.cn/Article/details/gt2esypimot.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sufxvd.cn/Article/details/gt2kfwazzni.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.fengsongda.top/Article/details/gt2rvxphvtm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hysaishi.cn/Article/details/gt2sgtpuvrx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yanxiufei.cn/Article/details/gt2hgzkeenm.html

[L07] 处理 HTTP 状态码
来源：http://dali.smart0.xyz/Article/details/gt2fzzokcaq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.andypj.xyz/Article/details/gt2ojfgqfkl.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zycfv.cn/Article/details/gt2fxgtatwf.html

JS:   resp.ok;  resp.status
来源：http://dali.jiagoushi.top/Article/details/gt2bfnhqlrj.html

TS:   resp.ok;  resp.status
来源：http://dali.daria6918.cn/Article/details/gt2jxydgzab.html

Java: resp.statusCode()
来源：http://dali.chenlongwang.top/Article/details/gt2rqdfkamo.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2bguazctd.html

Ruby: resp.code.to_i
来源：http://dali.cucudq.cn/Article/details/gt2fnompapg.html

C#:   (int)resp.StatusCode
来源：http://dali.zhoulong.xyz/Article/details/gt2yyqjgtqi.html

[L08] 并发请求多个地址
来源：http://dali.chenzaomai.com/Article/details/gt2exrlkvnw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hfpthk.cn/Article/details/gt2bpcqqbpn.html

PHP:  curl_multi_init() 系列
来源：http://dali.hammf.cn/Article/details/gt2pqictjam.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xinyue.icu/Article/details/gt2oslfdgrm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigufen.top/Article/details/gt2ypioowxp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.haohaochexian.top/Article/details/gt2vcinpkzb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yueranfly.top/Article/details/gt2macsmmrb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jyoumei.cn/Article/details/gt2qrqzgzza.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xziqi.cn/Article/details/gt2vxxkxamq.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2yrjrztod.html

M. 命令行 / 进程 / 环境
来源：http://dali.hywenlv.cn/Article/details/gt2rblmizyu.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2ecxdoedw.html

[M01] 读取命令行参数
来源：http://dali.yj202588.top/Article/details/gt2vitrvoov.html

Py:   sys.argv[1:]
来源：http://dali.gogol.net.cn/Article/details/gt2uscyzogz.html

PHP:  $argv;  $argc;
来源：http://dali.xuanzx.com/Article/details/gt2yrstbskc.html

JS:   process.argv.slice(2)
来源：http://dali.nwbrower.top/Article/details/gt2lwdxmuia.html

TS:   process.argv.slice(2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tyublheg.html

Java: args 数组（main 方法参数）
来源：http://dali.smart0.xyz/Article/details/gt2irmscolv.html

Go:   os.Args[1:]
来源：http://dali.kuanghao11.cn/Article/details/gt2hhjdusnl.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2evgcfcei.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shuidangran.top/Article/details/gt2qhmhiokf.html

[M02] 读取环境变量
来源：http://dali.xuetiantiany.cn/Article/details/gt2jfmwncql.html

Py:   os.environ.get("HOME")
来源：http://dali.ehwqpu.com/Article/details/gt2flrzzsly.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hammf.cn/Article/details/gt2sohdqndj.html

JS:   process.env.HOME
来源：http://dali.tianlin.xyz/Article/details/gt2jmkogwqy.html

TS:   process.env.HOME
来源：http://dali.gzhubu.top/Article/details/gt2vechebqa.html

Java: System.getenv("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gt2zpjcieeo.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gogol.net.cn/Article/details/gt2uwhfqgls.html

Ruby: ENV["HOME"]
来源：http://dali.yuxming.cn/Article/details/gt2bskdidtm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gt2pkahxaze.html

[M03] 执行外部命令
来源：http://dali.zycfv.cn/Article/details/gt2ofarzmhn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zycfv.cn/Article/details/gt2rrybwtbo.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tian-w.cn/Article/details/gt2lhtzvrua.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ovjfojfi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuxming.cn/Article/details/gt2amsqwrer.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.mhx1999.top/Article/details/gt2kxefrzbx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.havefunace.top/Article/details/gt2iftuwsdh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.guowangkeji.top/Article/details/gt2ezzqamnc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cucudq.cn/Article/details/gt2qutmcqzw.html

[M04] 获取当前工作目录
来源：http://dali.daria6918.cn/Article/details/gt2ycfacijs.html

Py:   os.getcwd()
来源：http://dali.yanxiufei.cn/Article/details/gt2cikmivip.html

PHP:  getcwd();
来源：http://dali.andypj.xyz/Article/details/gt2ukdluiio.html

JS:   process.cwd()
来源：http://dali.ehwqpu.com/Article/details/gt2vimisyes.html

TS:   process.cwd()
来源：http://dali.pengpengdd.cyou/Article/details/gt2auhdeygf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jianghu66.top/Article/details/gt2pfjtlmyx.html

Go:   os.Getwd()
来源：http://dali.hywenlv.cn/Article/details/gt2ahkalejg.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2zplxmfui.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.guannengcc.top/Article/details/gt2cwwdpdsi.html

[M05] 设置退出码
来源：http://dali.iojbl.cn/Article/details/gt2zzfgczsc.html

Py:   sys.exit(1)
来源：http://dali.tian-w.cn/Article/details/gt2fzdfwvje.html

PHP:  exit(1);
来源：http://dali.yueranfly.top/Article/details/gt2fdoulqim.html

JS:   process.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gt2fyrgudga.html

TS:   process.exit(1)
来源：http://dali.bjfxy.top/Article/details/gt2gvsoahul.html

Java: System.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wtnxeekr.html

Go:   os.Exit(1)
来源：http://dali.chenzaomai.com/Article/details/gt2kcjrtmar.html

Ruby: exit 1
来源：http://dali.fengsongda.top/Article/details/gt2pwebqaob.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.redwolf501.top/Article/details/gt2rjxqsxon.html

[M06] 向标准错误输出
来源：http://dali.guowangkeji.top/Article/details/gt2ovgqauxv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.0kj1m.cn/Article/details/gt2grucmszh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yvedp.cn/Article/details/gt2imtagrny.html

JS:   console.error("err")
来源：http://dali.jinqigfzy.top/Article/details/gt2dcnkdntg.html

TS:   console.error("err")
来源：http://dali.zdqjudy.top/Article/details/gt2ztolbbbu.html

Java: System.err.println("err")
来源：http://dali.andypj.xyz/Article/details/gt2qpcwaucz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xuanzx.com/Article/details/gt2dzhomkls.html

Ruby: warn "err"
来源：http://dali.chenzaomai.com/Article/details/gt2tewiogdu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hfpthk.cn/Article/details/gt2yyczlgnj.html

[M07] 判断是否为主入口
来源：http://dali.shzxlz.cn/Article/details/gt2clmsmdlx.html

Py:   if __name__ == "__main__":
来源：http://dali.wangdashe.top/Article/details/gt2etknyael.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.iojbl.cn/Article/details/gt2wuawvipl.html

JS:   require.main === module
来源：http://dali.wangdashe.top/Article/details/gt2oxozhrvk.html

TS:   require.main === module
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cfljfoux.html

Java: public static void main(String[] args)
来源：http://dali.haohaochexian.top/Article/details/gt2sivxjklm.html

Go:   func main()
来源：http://dali.hywenlv.cn/Article/details/gt2fsgadepv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hywenlv.cn/Article/details/gt2qkeqaoiv.html

C#:   static void Main(string[] args)
来源：http://dali.9152youxi.cn/Article/details/gt2ixifxzkk.html

[M08] 获取系统与运行时信息
来源：http://dali.zdqjudy.top/Article/details/gt2lrfljuag.html

Py:   platform.system();  platform.python_version()
来源：http://dali.birdmap.top/Article/details/gt2ajkjnask.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.feifeiyinyue.top/Article/details/gt2jcrmxmji.html

JS:   process.platform;  process.version
来源：http://dali.yj20258888.top/Article/details/gt2qmxxbhah.html

TS:   process.platform;  process.version
来源：http://dali.vqdsnc.cn/Article/details/gt2iilgzbbd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxfebvfm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.316326.xyz/Article/details/gt2aoxjuftc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.aibaodan.cn/Article/details/gt2ntkhxsai.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhoulong.xyz/Article/details/gt2lozyitin.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2hwncydox.html

N. 数据结构与算法
来源：http://dali.yueranfly.top/Article/details/gt2fomurill.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2waukyfzi.html

[N01] 二分查找（有序数组）
来源：http://dali.aibaodan.cn/Article/details/gt2minquhry.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ygorzcas.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ydzc1.top/Article/details/gt2bqngcawk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.mhx1999.top/Article/details/gt2gylabcdw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.quarkkingdee.top/Article/details/gt2szjueamw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gt2pkesfegw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gt2tbxrzcgt.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shzxlz.cn/Article/details/gt2mlwkjcsv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gt2utxtdfbz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.c1oappe.top/Article/details/gt2dewsovmu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shangyingyoupin.top/Article/details/gt2velzbwas.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pacnntkb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jqgufenzy.top/Article/details/gt2cocduasb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gotoacloud.top/Article/details/gt2eondclvs.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cqqwz.cn/Article/details/gt2mxhglibp.html

Go:   slices.Sort(arr)
来源：http://dali.redwolf501.top/Article/details/gt2heogzmfc.html

Ruby: arr.sort
来源：http://dali.mhx1999.top/Article/details/gt2ppaxrkcc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gzhubu.top/Article/details/gt2smqjmedw.html

[N03] 快速排序（分治示例）
来源：http://dali.zhoulong.xyz/Article/details/gt2wyhfvtlm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.0kj1m.cn/Article/details/gt2uvtbnlgn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinqigufen.top/Article/details/gt2gkqefujv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yvedp.cn/Article/details/gt2jcpcussq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shangyingyoupin.top/Article/details/gt2rnddimjc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.chenjidiqi.icu/Article/details/gt2ckljuymm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yanxiufei.cn/Article/details/gt2erngdsjd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.pengpengdd.cyou/Article/details/gt2rxwgohgj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jlsjyb.cn/Article/details/gt2wtlyqryp.html

[N04] 斐波那契数列
来源：http://dali.9152youxi.cn/Article/details/gt2gajxhsqj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yuanzhike.top/Article/details/gt2ncebboff.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.redwolf501.top/Article/details/gt2zhglffye.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gt2myojwrem.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yonumen.top/Article/details/gt2etmzeczd.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.havefunace.top/Article/details/gt2liwmcumi.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hywenlv.cn/Article/details/gt2pczxjmyh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ybcxt.top/Article/details/gt2wqtluzdx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.guannengcc.top/Article/details/gt2sbfolzjh.html

[N05] 最大公约数
来源：http://dali.ydzc1.top/Article/details/gt2pgqespxm.html

Py:   math.gcd(a, b)
来源：http://dali.nanxuanxn.top/Article/details/gt2bdwtfysf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2vbynhxuu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dashuyun.cn/Article/details/gt2mzwiauxc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj202588.top/Article/details/gt2fqhxkyil.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zusamxyp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.iojbl.cn/Article/details/gt2vbbithwv.html

Ruby: a.gcd(b)
来源：http://dali.chenzaomai.com/Article/details/gt2xbxvhrzc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gyfnkvts.html

[N06] 判断回文字符串
来源：http://dali.gzhubu.top/Article/details/gt2lpuyuwaq.html

Py:   s == s[::-1]
来源：http://dali.haohaochexian.top/Article/details/gt2xcgfmpsr.html

PHP:  $s === strrev($s);
来源：http://dali.hfpthk.cn/Article/details/gt2mcnayhdc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gt2hpczqzxt.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gt2iygdukiw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jqgufenzy.top/Article/details/gt2nitkvraw.html

Go:   // 双指针从两端比较
来源：http://dali.shuidangran.top/Article/details/gt2mkfxcore.html

Ruby: s == s.reverse
来源：http://dali.yueranfly.top/Article/details/gt2kfimobsk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yonumen.top/Article/details/gt2vkqchuhd.html

[N07] 两数之和（返回下标）
来源：http://dali.9152youxi.cn/Article/details/gt2rljspitb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.chenjidiqi.icu/Article/details/gt2nkakkhwg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ytrwkjxo.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2doefmyqh.html

TS:   // 手写 Map<string, number>
来源：http://dali.sysykeji.top/Article/details/gt2tdtqeidf.html

Java: // 手写 HashMap
来源：http://dali.yj20258888.top/Article/details/gt2buxodblg.html

Go:   // 手写 map[int]int
来源：http://dali.iojbl.cn/Article/details/gt2mhhsfmuh.html

Ruby: // 手写 Hash
来源：http://dali.daxiang520.top/Article/details/gt2qkdadwpj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.guowangkeji.top/Article/details/gt2qnzqdkmd.html

[N08] 生成全排列
来源：http://dali.kuanghao11.cn/Article/details/gt2dvkfzthd.html

Py:   itertools.permutations(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zbqyargd.html

PHP:  // 手写递归交换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ojyhrrde.html

JS:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gt2iwymfrtq.html

TS:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gt2lgcijhyq.html

Java: // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gt2wlxamiup.html

Go:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gt2zhhqowcs.html

Ruby: arr.permutation.to_a
来源：http://dali.shangyingyoupin.top/Article/details/gt2fkjbgaza.html

C#:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gt2wfjtafgk.html

[N09] 栈与队列
来源：http://dali.sweek.top/Article/details/gt2snxqknfn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.meibo888.top/Article/details/gt2kjuvdudx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhixingplan.top/Article/details/gt2viyfnjsy.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.vqdsnc.cn/Article/details/gt2kajuoyfe.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.tianlin.xyz/Article/details/gt2qezmfeww.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yongpay.top/Article/details/gt2bhzlntoq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sxryk.cn/Article/details/gt2utmlivlm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.birdmap.top/Article/details/gt2olythiva.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yongpay.top/Article/details/gt2uluxczwo.html

[N10] 链表节点定义
来源：http://dali.guowangkeji.top/Article/details/gt2ijcifioo.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.snrcjt.cn/Article/details/gt2tfrsnxzs.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yueranfly.top/Article/details/gt2rvijvgzg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.redwolf501.top/Article/details/gt2bfitzoca.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.wangdashe.top/Article/details/gt2neggdbyc.html

Java: class Node { int v; Node next; }
来源：http://dali.redwolf501.top/Article/details/gt2zusgiudo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ybcxt.top/Article/details/gt2owwmvybo.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shuidangran.top/Article/details/gt2vcybselt.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ivvv.top/Article/details/gt2tnlgoovs.html

[N11] 二叉树中序遍历
来源：http://dali.sweek.top/Article/details/gt2yvbmybof.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ehwqpu.com/Article/details/gt2yxhfpdrq.html

PHP:  // 手写递归函数
来源：http://dali.dianchejie.cn/Article/details/gt2nxbyewtn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yangfankeji.com/Article/details/gt2eewgpuem.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.fengsongda.top/Article/details/gt2ljakemqv.html

Java: // 手写递归
来源：http://dali.gaohongyu789.top/Article/details/gt2wxsouupz.html

Go:   // 手写递归
来源：http://dali.fengsongda.top/Article/details/gt2zxprgvpj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.haohaochexian.top/Article/details/gt2vlgbdtvi.html

C#:   // 手写递归
来源：http://dali.guannengcc.top/Article/details/gt2fwhcgkju.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.haohaochexian.top/Article/details/gt2rjxwkuxe.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.0kj1m.cn/Article/details/gt2lpdrcazr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.nanxuanxn.top/Article/details/gt2ivkoeihj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cucudq.cn/Article/details/gt2rllxeqrb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dianchejie.cn/Article/details/gt2vmdwdcgo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shzxlz.cn/Article/details/gt2qyvoamhv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hysaishi.cn/Article/details/gt2semepzph.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.pengpengdd.cyou/Article/details/gt2msarcmnp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenzaomai.com/Article/details/gt2mrjtbuoz.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2fkvnmqyo.html

O. 并发与异步
来源：http://dali.wangdashe.top/Article/details/gt2ftmrqfnk.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2ktefumjj.html

[O01] 启动一个线程
来源：http://dali.yuanzhike.top/Article/details/gt2yrhexweo.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2yjxnrzfw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yanxiufei.cn/Article/details/gt2tqslkyzm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.tian-w.cn/Article/details/gt2xijvteqs.html

TS:   // 同 JS
来源：http://dali.cdnleiting.top/Article/details/gt2jiftgyre.html

Java: new Thread(() -> f()).start()
来源：http://dali.wangdashe.top/Article/details/gt2qjbnvslk.html

Go:   go f()
来源：http://dali.hfpthk.cn/Article/details/gt2pcalqtsz.html

Ruby: Thread.new { f }
来源：http://dali.yonumen.top/Article/details/gt2udkjdqxz.html

C#:   Task.Run(() => F());
来源：http://dali.gogol.net.cn/Article/details/gt2vjkjpmic.html

[O02] 使用线程池
来源：http://dali.nanxuanxn.top/Article/details/gt2hmzlptan.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.meibo888.top/Article/details/gt2nftwsaln.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.vqdsnc.cn/Article/details/gt2erodvhid.html

JS:   // worker_threads 线程池
来源：http://dali.dianchejie.cn/Article/details/gt2eykazxag.html

TS:   // worker_threads 线程池
来源：http://dali.sufxvd.cn/Article/details/gt2nyopmtzl.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shzxlz.cn/Article/details/gt2rqnuxerq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cashguo.top/Article/details/gt2saicraxa.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jiagoushi.top/Article/details/gt2tktkxpqk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ivvv.top/Article/details/gt2cfhgjcva.html

[O03] 加锁保护共享数据
来源：http://dali.cqqwz.cn/Article/details/gt2eflownci.html

Py:   with lock: shared += 1
来源：http://dali.zhoulong.xyz/Article/details/gt2oqgsytxj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.bjfxy.top/Article/details/gt2tbwcxzlz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvwssgc.html

TS:   // 同 JS
来源：http://dali.yueranfly.top/Article/details/gt2tbhxirea.html

Java: synchronized (this) { shared++; }
来源：http://dali.havefunace.top/Article/details/gt2ieaywjig.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ptwdtkmg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xinyue.icu/Article/details/gt2fvxkqiby.html

C#:   lock (gate) { shared++; }
来源：http://dali.fengsongda.top/Article/details/gt2viietpeu.html

[O04] 定义异步函数并等待
来源：http://dali.snrcjt.cn/Article/details/gt2lmpuakwx.html

Py:   async def f():⏎    await g()
来源：http://dali.pycfn.com/Article/details/gt2ijzrocov.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.snrcjt.cn/Article/details/gt2mdscghfi.html

JS:   async function f() { await g(); }
来源：http://dali.yj20258.top/Article/details/gt2njhfxynr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.0kj1m.cn/Article/details/gt2noydokxx.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.0kj1m.cn/Article/details/gt2fbphsxzi.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.aibaodan.cn/Article/details/gt2wcqevwjc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.dianchejie.cn/Article/details/gt2ontickts.html

C#:   async Task F() { await G(); }
来源：http://dali.smart0.xyz/Article/details/gt2lnacgqfp.html

[O05] 并发执行并等待全部完成
来源：http://dali.chenzaomai.com/Article/details/gt2ytstatba.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhixingplan.top/Article/details/gt2jsuvecrh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ggxubcgl.html

JS:   await Promise.all(tasks)
来源：http://dali.cdnleiting.top/Article/details/gt2nohojoor.html

TS:   await Promise.all(tasks)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vencffgd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.9152youxi.cn/Article/details/gt2lhjiixbu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yuxming.cn/Article/details/gt2sjwraqqw.html

Ruby: threads.map(&:join)
来源：http://dali.jinqigufen.top/Article/details/gt2sradtzox.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yvedp.cn/Article/details/gt2rljqinsq.html

[O06] 使用进程池
来源：http://dali.hfpthk.cn/Article/details/gt2mmfwxbrv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hammf.cn/Article/details/gt2wyqngswv.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yongpay.top/Article/details/gt2nqetttyx.html

JS:   // child_process / cluster 模块
来源：http://dali.yangfankeji.com/Article/details/gt2zemzblxd.html

TS:   // child_process / cluster 模块
来源：http://dali.cucudq.cn/Article/details/gt2zfldtolu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2spjgdlmg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tian-w.cn/Article/details/gt2exofwebg.html

Ruby: // fork 块
来源：http://dali.0kj1m.cn/Article/details/gt2yifpcolp.html

C#:   Parallel.For
来源：http://dali.yj202588.top/Article/details/gt2zflgjiwd.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2rqwryuxg.html

P. 常用工具函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ggcfkxyu.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2ipmkrpsq.html


<!-- 参考信息 -->