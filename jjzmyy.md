代发 wailian999

Go:   resp, err := http.Get(url)
来源：http://dali.yongpay.top/Article/details/gt2skafeihi.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.aizwys.cn/Article/details/gt2flizduhn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.bjfxy.top/Article/details/gt2xcookerq.html

[L02] 发送 POST JSON
来源：http://dali.dashuyun.cn/Article/details/gt2dqvvlfgm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenzaomai.com/Article/details/gt2ajsuoyiq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hysaishi.cn/Article/details/gt2sxbvmdke.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guowangkeji.top/Article/details/gt2rxsfprjs.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yueranfly.top/Article/details/gt2genrzrni.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hfpthk.cn/Article/details/gt2iilquqqg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shangyingyoupin.top/Article/details/gt2ikxtuwgz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jqgufenzy.top/Article/details/gt2xlynvpvd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jiagoushi.top/Article/details/gt2gohpbhpx.html

[L03] 设置自定义请求头
来源：http://dali.yangfankeji.com/Article/details/gt2sdplypxb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ucsdxvku.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.daria6918.cn/Article/details/gt2jsjuival.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wkqmsfrc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tianlin.xyz/Article/details/gt2wyzijdep.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.nwbrower.top/Article/details/gt2fhjjcbuq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.aibaodan.cn/Article/details/gt2rlntyzfn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhongyouzk.top/Article/details/gt2snkupqld.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yj202588.top/Article/details/gt2qpjeducn.html

[L04] 设置超时
来源：http://dali.sweek.top/Article/details/gt2limwyvri.html

Py:   requests.get(url, timeout=5)
来源：http://dali.aizwys.cn/Article/details/gt2jyulwnwm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hfpthk.cn/Article/details/gt2rpwqipmx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pengpengdd.cyou/Article/details/gt2cvsahtfe.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigufen.top/Article/details/gt2ufypawpj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gzhubu.top/Article/details/gt2rrvclpla.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.dashuyun.cn/Article/details/gt2zhccfbnb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cashguo.top/Article/details/gt2qrkyggvc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yuanzhike.top/Article/details/gt2rgkxjftj.html

[L05] 上传文件（multipart）
来源：http://dali.jqgufenzy.top/Article/details/gt2pxtikajx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ppjwa.cn/Article/details/gt2ikcozcbh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zycfv.cn/Article/details/gt2jalumhni.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yonumen.top/Article/details/gt2baecfpqd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jlsjyb.cn/Article/details/gt2bmqwotke.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.chenzaomai.com/Article/details/gt2imbozdbg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cqqwz.cn/Article/details/gt2kikheibv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qnvzlrnm.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sxryk.cn/Article/details/gt2gefejzil.html

[L06] 解析响应为 JSON
来源：http://dali.yangfankeji.com/Article/details/gt2difkvwui.html

Py:   resp.json()
来源：http://dali.snrcjt.cn/Article/details/gt2ltlhennm.html

PHP:  json_decode($body, true);
来源：http://dali.hongshengwenyu.top/Article/details/gt2lwribbrh.html

JS:   await resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gt2nffabbmr.html

TS:   await resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gt2zeviluiz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jianghu66.top/Article/details/gt2cjsytbjw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hfpthk.cn/Article/details/gt2lilmertt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gaohongyu789.top/Article/details/gt2gmiymiez.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ibuebacu.html

[L07] 处理 HTTP 状态码
来源：http://dali.dashuyun.cn/Article/details/gt2ixrdxmlm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.c1oappe.top/Article/details/gt2ddjondmo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ppjwa.cn/Article/details/gt2axpdqzfx.html

JS:   resp.ok;  resp.status
来源：http://dali.havefunace.top/Article/details/gt2dyjrbnau.html

TS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jbjexavz.html

Java: resp.statusCode()
来源：http://dali.xziqi.cn/Article/details/gt2sdvkswax.html

Go:   resp.StatusCode
来源：http://dali.daria6918.cn/Article/details/gt2olgydoay.html

Ruby: resp.code.to_i
来源：http://dali.smart0.xyz/Article/details/gt2zyccckoe.html

C#:   (int)resp.StatusCode
来源：http://dali.sxryk.cn/Article/details/gt2mcpiwyee.html

[L08] 并发请求多个地址
来源：http://dali.jqgufenzy.top/Article/details/gt2ipoiyvuw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nwbrower.top/Article/details/gt2jryfkqiz.html

PHP:  curl_multi_init() 系列
来源：http://dali.sweek.top/Article/details/gt2survgagh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigfzy.top/Article/details/gt2lygwrfli.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yangfankeji.com/Article/details/gt2eumznusv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jyoumei.cn/Article/details/gt2lcfddtgr.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.birdmap.top/Article/details/gt2spvnufca.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.nwbrower.top/Article/details/gt2fzlvyscx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.guannengcc.top/Article/details/gt2ilkrfzua.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2psuzloyr.html

M. 命令行 / 进程 / 环境
来源：http://dali.aibaodan.cn/Article/details/gt2ffppqtsz.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2eydffsiz.html

[M01] 读取命令行参数
来源：http://dali.chenlongwang.top/Article/details/gt2dtzwriyz.html

Py:   sys.argv[1:]
来源：http://dali.yj20258.top/Article/details/gt2kgrwptpt.html

PHP:  $argv;  $argc;
来源：http://dali.chenjidiqi.icu/Article/details/gt2czjgfztr.html

JS:   process.argv.slice(2)
来源：http://dali.zhongyouzk.top/Article/details/gt2reaumzpq.html

TS:   process.argv.slice(2)
来源：http://dali.9152youxi.cn/Article/details/gt2nzsgginz.html

Java: args 数组（main 方法参数）
来源：http://dali.yonumen.top/Article/details/gt2putlspgj.html

Go:   os.Args[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gt2kjkzkvdm.html

Ruby: ARGV
来源：http://dali.chenjidiqi.icu/Article/details/gt2xgoygehf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ybcxt.top/Article/details/gt2ivjcirpd.html

[M02] 读取环境变量
来源：http://dali.guowangkeji.top/Article/details/gt2maglaogz.html

Py:   os.environ.get("HOME")
来源：http://dali.xylfe.cn/Article/details/gt2zinebioo.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.316326.xyz/Article/details/gt2weidjubm.html

JS:   process.env.HOME
来源：http://dali.pengpengdd.cyou/Article/details/gt2kbtubcol.html

TS:   process.env.HOME
来源：http://dali.redwolf501.top/Article/details/gt2whterupz.html

Java: System.getenv("HOME")
来源：http://dali.yj20258.top/Article/details/gt2gooyvorn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ivvv.top/Article/details/gt2cstlomfc.html

Ruby: ENV["HOME"]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2varvmeql.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gt2jhguocrv.html

[M03] 执行外部命令
来源：http://dali.zdqjudy.top/Article/details/gt2moaatzod.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yj20258888.top/Article/details/gt2wbwnujcs.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hfpthk.cn/Article/details/gt2djyawzgn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cjvegoht.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.snrcjt.cn/Article/details/gt2mceuozak.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bffsneix.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hnxiangtu.top/Article/details/gt2trwjweoq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.nwbrower.top/Article/details/gt2rfbcabyo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cheryme.top/Article/details/gt2ipjiyehj.html

[M04] 获取当前工作目录
来源：http://dali.yonumen.top/Article/details/gt2roggrzni.html

Py:   os.getcwd()
来源：http://dali.shzxlz.cn/Article/details/gt2gibodtod.html

PHP:  getcwd();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pinnvjzn.html

JS:   process.cwd()
来源：http://dali.yvedp.cn/Article/details/gt2rwczxemu.html

TS:   process.cwd()
来源：http://dali.havefunace.top/Article/details/gt2aeyhjvxl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jqgfzy.top/Article/details/gt2ggccqoye.html

Go:   os.Getwd()
来源：http://dali.gaohongyu789.top/Article/details/gt2pzurmesr.html

Ruby: Dir.pwd
来源：http://dali.xinyue.icu/Article/details/gt2dudpwtpx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hnqzz.top/Article/details/gt2lsnaasia.html

[M05] 设置退出码
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hfhlwlgk.html

Py:   sys.exit(1)
来源：http://dali.yj20258.top/Article/details/gt2kiipheoj.html

PHP:  exit(1);
来源：http://dali.shuidangran.top/Article/details/gt2qmihmicd.html

JS:   process.exit(1)
来源：http://dali.sxryk.cn/Article/details/gt2gbfyqyhq.html

TS:   process.exit(1)
来源：http://dali.aizwys.cn/Article/details/gt2cpqdszde.html

Java: System.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2vvrivrpg.html

Go:   os.Exit(1)
来源：http://dali.chenzaomai.com/Article/details/gt2ztrqxmjy.html

Ruby: exit 1
来源：http://dali.gzhubu.top/Article/details/gt2rzifkqpq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dvjymnhf.html

[M06] 向标准错误输出
来源：http://dali.bjfxy.top/Article/details/gt2hmsiwdfc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhixingplan.top/Article/details/gt2eqkipcim.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yj202588.top/Article/details/gt2zgcivxvi.html

JS:   console.error("err")
来源：http://dali.xylfe.cn/Article/details/gt2plxcuxkl.html

TS:   console.error("err")
来源：http://dali.c1oappe.top/Article/details/gt2hivhbijy.html

Java: System.err.println("err")
来源：http://dali.yuxming.cn/Article/details/gt2tqrixokl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.pengpengdd.cyou/Article/details/gt2wvwlichz.html

Ruby: warn "err"
来源：http://dali.xziqi.cn/Article/details/gt2jtejiifz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xylfe.cn/Article/details/gt2fgxnpihw.html

[M07] 判断是否为主入口
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mucpoagb.html

Py:   if __name__ == "__main__":
来源：http://dali.yueranfly.top/Article/details/gt2ksluuyou.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.fengsongda.top/Article/details/gt2jlhsorbl.html

JS:   require.main === module
来源：http://dali.0kj1m.cn/Article/details/gt2uijujjaj.html

TS:   require.main === module
来源：http://dali.tianlin.xyz/Article/details/gt2gflfdjgz.html

Java: public static void main(String[] args)
来源：http://dali.dashuyun.cn/Article/details/gt2brstclon.html

Go:   func main()
来源：http://dali.zhixingplan.top/Article/details/gt2usvdknvp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.daria6918.cn/Article/details/gt2rlruxeqg.html

C#:   static void Main(string[] args)
来源：http://dali.havefunace.top/Article/details/gt2jyodkbrs.html

[M08] 获取系统与运行时信息
来源：http://dali.aibaodan.cn/Article/details/gt2ukquuhsi.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hnxiangtu.top/Article/details/gt2olnnzpag.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.chenzaomai.com/Article/details/gt2lspcsglk.html

JS:   process.platform;  process.version
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qzmxauey.html

TS:   process.platform;  process.version
来源：http://dali.yj20258888.top/Article/details/gt2vptcfzmt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cashguo.top/Article/details/gt2xexbzvsv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj20258888.top/Article/details/gt2yknwhltw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.chenjidiqi.icu/Article/details/gt2vkghdcky.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hnxiangtu.top/Article/details/gt2dljgongb.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2bkmotrlh.html

N. 数据结构与算法
来源：http://dali.ybcxt.top/Article/details/gt2uonhojsy.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2dcmyjpnr.html

[N01] 二分查找（有序数组）
来源：http://dali.zhongyouzk.top/Article/details/gt2svbcpqim.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gt2qhtraqck.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hammf.cn/Article/details/gt2whfibrvc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gzhubu.top/Article/details/gt2ajdjkknl.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.316326.xyz/Article/details/gt2xmmqftbh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xdzhnixv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2buhimaoy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.9152youxi.cn/Article/details/gt2yfytyjgz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gt2luwkhodu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hysaishi.cn/Article/details/gt2rivlrdlq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.316326.xyz/Article/details/gt2dkxdnbrt.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sufxvd.cn/Article/details/gt2grignvps.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hammf.cn/Article/details/gt2enablpfo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gt2zcszpemp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cashguo.top/Article/details/gt2savrygas.html

Go:   slices.Sort(arr)
来源：http://dali.yj20258.top/Article/details/gt2flcpvams.html

Ruby: arr.sort
来源：http://dali.zhongyouzk.top/Article/details/gt2wecmfdzi.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinqigfzy.top/Article/details/gt2pvhaanwe.html

[N03] 快速排序（分治示例）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2knkdwqcy.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xinyue.icu/Article/details/gt2mzwonxws.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yj202588.top/Article/details/gt2xfumtcsq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fengsongda.top/Article/details/gt2fbmcicph.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hammf.cn/Article/details/gt2nrcasftl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.0kj1m.cn/Article/details/gt2xboijlpt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zdqjudy.top/Article/details/gt2gzlpsgqp.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ybcxt.top/Article/details/gt2ybnegqid.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.daxiang520.top/Article/details/gt2mzyhtflj.html

[N04] 斐波那契数列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yqbbadah.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2weqlgrcw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.pycfn.com/Article/details/gt2njlbjwxc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gt2scxfhbio.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2khgofoqh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhoulong.xyz/Article/details/gt2pspygyje.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.9152youxi.cn/Article/details/gt2qdbqcxrg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uqifzpfu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xuetiantiany.cn/Article/details/gt2sqzgxttk.html

[N05] 最大公约数
来源：http://dali.jinqigfzy.top/Article/details/gt2ytnvvtvl.html

Py:   math.gcd(a, b)
来源：http://dali.aibaodan.cn/Article/details/gt2nqzauvhh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.chenlongwang.top/Article/details/gt2lgkilgaq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj202588.top/Article/details/gt2ltwdkbdh.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.meibo888.top/Article/details/gt2reyfaqeg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.nanxinkj.top/Article/details/gt2jwqarfeq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.wangshuangyany.cn/Article/details/gt2nblyejcq.html

Ruby: a.gcd(b)
来源：http://dali.zhixingplan.top/Article/details/gt2gueqaxlc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xylfe.cn/Article/details/gt2johtpliu.html

[N06] 判断回文字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2ygnftuds.html

Py:   s == s[::-1]
来源：http://dali.pengpengdd.cyou/Article/details/gt2xatqcpxa.html

PHP:  $s === strrev($s);
来源：http://dali.chenlongwang.top/Article/details/gt2dqflwheg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ydzc1.top/Article/details/gt2ktmqxoit.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sysykeji.top/Article/details/gt2glgjzlqr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.havefunace.top/Article/details/gt2phyzksgg.html

Go:   // 双指针从两端比较
来源：http://dali.shzxlz.cn/Article/details/gt2riiopbbh.html

Ruby: s == s.reverse
来源：http://dali.snrcjt.cn/Article/details/gt2uxqdhvob.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.0kj1m.cn/Article/details/gt2fjjhloqi.html

[N07] 两数之和（返回下标）
来源：http://dali.zycfv.cn/Article/details/gt2tdnnsgtb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cucudq.cn/Article/details/gt2fjbfuutz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cdnleiting.top/Article/details/gt2kxrjmtao.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhongyouzk.top/Article/details/gt2mkbowgtn.html

TS:   // 手写 Map<string, number>
来源：http://dali.zycfv.cn/Article/details/gt2ucilenhq.html

Java: // 手写 HashMap
来源：http://dali.zhiwuduotai.top/Article/details/gt2pucrnytd.html

Go:   // 手写 map[int]int
来源：http://dali.hfpthk.cn/Article/details/gt2xarqteph.html

Ruby: // 手写 Hash
来源：http://dali.sufxvd.cn/Article/details/gt2lleaekgk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gzhubu.top/Article/details/gt2sznaaqsg.html

[N08] 生成全排列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2haxxvgvf.html

Py:   itertools.permutations(arr)
来源：http://dali.yongpay.top/Article/details/gt2hcoluenz.html

PHP:  // 手写递归交换
来源：http://dali.wangdashe.top/Article/details/gt2ucqacvus.html

JS:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gt2soffffnj.html

TS:   // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gt2xpvtjubh.html

Java: // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gt2parxcdqg.html

Go:   // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gt2hoizclsi.html

Ruby: arr.permutation.to_a
来源：http://dali.yonumen.top/Article/details/gt2urunwupl.html

C#:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gt2ztubykhp.html

[N09] 栈与队列
来源：http://dali.gaohongyu789.top/Article/details/gt2ckkivsue.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yj202588.top/Article/details/gt2hwerbcct.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gt2niifawru.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jqgufenzy.top/Article/details/gt2lamdkmgz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mhjiqywo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ybcxt.top/Article/details/gt2zujwddbv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sufxvd.cn/Article/details/gt2nqgxkelv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.pengpengdd.cyou/Article/details/gt2ecythnqv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jyoumei.cn/Article/details/gt2qmcsjzkv.html

[N10] 链表节点定义
来源：http://dali.9152youxi.cn/Article/details/gt2vfdpopzf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yuxming.cn/Article/details/gt2kxvklmnc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.daxiang520.top/Article/details/gt2yqeuqshh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jqgfzy.top/Article/details/gt2fzocqovp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hywenlv.cn/Article/details/gt2vfwkslfm.html

Java: class Node { int v; Node next; }
来源：http://dali.gaohongyu789.top/Article/details/gt2jnvhwqcx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sxryk.cn/Article/details/gt2bjqavxns.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ybcxt.top/Article/details/gt2hmooknnq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.316326.xyz/Article/details/gt2uvqfgcaz.html

[N11] 二叉树中序遍历
来源：http://dali.daria6918.cn/Article/details/gt2roiaqkxr.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.meibo888.top/Article/details/gt2tpgnbjqo.html

PHP:  // 手写递归函数
来源：http://dali.c1oappe.top/Article/details/gt2vtmscogl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigfzy.top/Article/details/gt2muetkckm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yangfankeji.com/Article/details/gt2qaeznjox.html

Java: // 手写递归
来源：http://dali.kuanghao11.cn/Article/details/gt2dljfaqem.html

Go:   // 手写递归
来源：http://dali.hongshengwenyu.top/Article/details/gt2lwstpzhq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.snrcjt.cn/Article/details/gt2inqgstmb.html

C#:   // 手写递归
来源：http://dali.kuanghao11.cn/Article/details/gt2dyxiazsm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jqgfzy.top/Article/details/gt2rwyvqmhh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xinyue.icu/Article/details/gt2ixylzkkq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.chenlongwang.top/Article/details/gt2hgxbnbrb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.haohaochexian.top/Article/details/gt2milpbvwo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhiwuduotai.top/Article/details/gt2iajsixzm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gzhubu.top/Article/details/gt2ayubliad.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hysaishi.cn/Article/details/gt2lydmoilv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcysqbym.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tian-w.cn/Article/details/gt2gryhsgrc.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2qymkttwz.html

O. 并发与异步
来源：http://dali.316326.xyz/Article/details/gt2uzpmrmih.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2norbxmso.html

[O01] 启动一个线程
来源：http://dali.sufxvd.cn/Article/details/gt2ccpoxtgh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cqqwz.cn/Article/details/gt2obfgunby.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinqigfzy.top/Article/details/gt2lwywvfky.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.snrcjt.cn/Article/details/gt2pyfjezsi.html

TS:   // 同 JS
来源：http://dali.jianghu66.top/Article/details/gt2utojloyl.html

Java: new Thread(() -> f()).start()
来源：http://dali.guowangkeji.top/Article/details/gt2wzhwvqau.html

Go:   go f()
来源：http://dali.zdqjudy.top/Article/details/gt2lmeilidx.html

Ruby: Thread.new { f }
来源：http://dali.yangfankeji.com/Article/details/gt2tllracos.html

C#:   Task.Run(() => F());
来源：http://dali.guannengcc.top/Article/details/gt2mdhfjypg.html

[O02] 使用线程池
来源：http://dali.zhoulong.xyz/Article/details/gt2xzyokizv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.snrcjt.cn/Article/details/gt2msgsxxip.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shzxlz.cn/Article/details/gt2aiudeukg.html

JS:   // worker_threads 线程池
来源：http://dali.jqgufenzy.top/Article/details/gt2pjysrqyj.html

TS:   // worker_threads 线程池
来源：http://dali.yuanzhike.top/Article/details/gt2jipofsih.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2krrvngwl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wrgqqabn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hammf.cn/Article/details/gt2kvswzpan.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.aibaodan.cn/Article/details/gt2iiwerfvd.html

[O03] 加锁保护共享数据
来源：http://dali.nanxuanxn.top/Article/details/gt2zmdahwii.html

Py:   with lock: shared += 1
来源：http://dali.chenlongwang.top/Article/details/gt2pnmqqbdz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xuetiantiany.cn/Article/details/gt2wzyrjprv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hufijbdj.html

TS:   // 同 JS
来源：http://dali.zhiwuduotai.top/Article/details/gt2ffsoxjoy.html

Java: synchronized (this) { shared++; }
来源：http://dali.dianchejie.cn/Article/details/gt2lupcmoce.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.havefunace.top/Article/details/gt2jkpoxuja.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hammf.cn/Article/details/gt2jzscdkel.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhongyouzk.top/Article/details/gt2kgbpgphl.html

[O04] 定义异步函数并等待
来源：http://dali.birdmap.top/Article/details/gt2dhxdiqhp.html

Py:   async def f():⏎    await g()
来源：http://dali.ydzc1.top/Article/details/gt2avhkgudg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cqqwz.cn/Article/details/gt2gnjnhfwt.html

JS:   async function f() { await g(); }
来源：http://dali.chenlongwang.top/Article/details/gt2ekmeewos.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gvaldtcu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.kuanghao11.cn/Article/details/gt2sjsuujxv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.pengpengdd.cyou/Article/details/gt2bobgugzo.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cucudq.cn/Article/details/gt2efpnjvth.html

C#:   async Task F() { await G(); }
来源：http://dali.smart0.xyz/Article/details/gt2ewowabei.html

[O05] 并发执行并等待全部完成
来源：http://dali.fzhhl.top/Article/details/gt2fmcrbnrw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.guannengcc.top/Article/details/gt2lcmrsxmq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hfpthk.cn/Article/details/gt2lwbgqyzs.html

JS:   await Promise.all(tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xnlgewud.html

TS:   await Promise.all(tasks)
来源：http://dali.hfpthk.cn/Article/details/gt2tkxwvroi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xinyue.icu/Article/details/gt2igbbimkq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zycfv.cn/Article/details/gt2stajkdcu.html

Ruby: threads.map(&:join)
来源：http://dali.birdmap.top/Article/details/gt2aztfifox.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.fzhhl.top/Article/details/gt2zudutikn.html


<!-- 参考信息 -->