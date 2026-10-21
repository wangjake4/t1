代发 wailian999

Py:   requests.post(url, json={"a": 1})
来源：http://dali.mhx1999.top/Article/details/gtueppmpek.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.iojbl.cn/Article/details/gtyiiwblsk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258888.top/Article/details/gtmmwuhiet.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cheryme.top/Article/details/gthjthhcmk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.redwolf501.top/Article/details/gtlrdmlsrv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtirdolcto.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jiagoushi.top/Article/details/gterccgenx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhiwuduotai.top/Article/details/gtxwglsoqk.html

[L03] 设置自定义请求头
来源：http://dali.chenzaomai.com/Article/details/gtlclrjlkw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shanyushiyangtech.top/Article/details/gtpqyfayuq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.guannengcc.top/Article/details/gtyxctwhii.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yangfankeji.com/Article/details/gttxgbjizj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cdnleiting.top/Article/details/gtgajtjdie.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.andypj.xyz/Article/details/gtlmekhbej.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yvedp.cn/Article/details/gtsdctzxzh.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sweek.top/Article/details/gtbclyaacd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.svipenyu.cn/Article/details/gtqfqgnseq.html

[L04] 设置超时
来源：http://dali.wangdashe.top/Article/details/gtpgrnayuu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cucudq.cn/Article/details/gtvgtmzzyo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hnxiangtu.top/Article/details/gtqgghsxru.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenjidiqi.icu/Article/details/gttyhcufvr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuetiantiany.cn/Article/details/gtxfovpnzw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ybcxt.top/Article/details/gtlzrowmuy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.kuanghao11.cn/Article/details/gtxqtdcirv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xylfe.cn/Article/details/gtphwrfigz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.dianchejie.cn/Article/details/gthevvcgxu.html

[L05] 上传文件（multipart）
来源：http://dali.ybcxt.top/Article/details/gtoedzvqcw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.daxiang520.top/Article/details/gtvyadaqcv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cashguo.top/Article/details/gtkhehefxn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.fengsongda.top/Article/details/gtiacpqfqb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinghuilouyu.cn/Article/details/gtzmplyoom.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jyoumei.cn/Article/details/gtjhvducfx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.tian-w.cn/Article/details/gtxufdyded.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yongpay.top/Article/details/gthrekgxya.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtvmsytsgd.html

[L06] 解析响应为 JSON
来源：http://dali.zhengqikj.top/Article/details/gtliknxczz.html

Py:   resp.json()
来源：http://dali.316326.xyz/Article/details/gtuafhypbd.html

PHP:  json_decode($body, true);
来源：http://dali.wangshuangyany.cn/Article/details/gtdwtweqea.html

JS:   await resp.json()
来源：http://dali.jinghuilouyu.cn/Article/details/gtotrviojf.html

TS:   await resp.json()
来源：http://dali.snrcjt.cn/Article/details/gtfhuvhtlr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtspjmlyhj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sysykeji.top/Article/details/gtpnrjcczo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhoulong.xyz/Article/details/gtjmixhhvy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gaohongyu789.top/Article/details/gtrzivtrkd.html

[L07] 处理 HTTP 状态码
来源：http://dali.sxryk.cn/Article/details/gttqzydlbg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tian-w.cn/Article/details/gtkmdegdrk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gogol.net.cn/Article/details/gtegkyjchv.html

JS:   resp.ok;  resp.status
来源：http://dali.zycfv.cn/Article/details/gtseknagyh.html

TS:   resp.ok;  resp.status
来源：http://dali.cqqwz.cn/Article/details/gtcrklnyai.html

Java: resp.statusCode()
来源：http://dali.9152youxi.cn/Article/details/gtlcgsxsxj.html

Go:   resp.StatusCode
来源：http://dali.sysykeji.top/Article/details/gttvpsznzn.html

Ruby: resp.code.to_i
来源：http://dali.yanxiufei.cn/Article/details/gtlewkbhpa.html

C#:   (int)resp.StatusCode
来源：http://dali.jinghuilouyu.cn/Article/details/gtkycabvcb.html

[L08] 并发请求多个地址
来源：http://dali.xinyue.icu/Article/details/gtrojxywre.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinghuilouyu.cn/Article/details/gtgtfstttt.html

PHP:  curl_multi_init() 系列
来源：http://dali.yuanzhike.top/Article/details/gtgzbtjuqn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhengqikj.top/Article/details/gtalhhbfww.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxuanxn.top/Article/details/gtbwosdtib.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gzhubu.top/Article/details/gtzcjdxaxr.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yonumen.top/Article/details/gttannieyq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cucudq.cn/Article/details/gtnzlqhcph.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gotoacloud.top/Article/details/gtsfhhnbxu.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtvycwhdrc.html

M. 命令行 / 进程 / 环境
来源：http://dali.shuidangran.top/Article/details/gtfegfthwc.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtuwcorofn.html

[M01] 读取命令行参数
来源：http://dali.zhongyouzk.top/Article/details/gttpoqczmw.html

Py:   sys.argv[1:]
来源：http://dali.cqqwz.cn/Article/details/gtdhdmwhvm.html

PHP:  $argv;  $argc;
来源：http://dali.zhongyouzk.top/Article/details/gtmppcbdxo.html

JS:   process.argv.slice(2)
来源：http://dali.yj20258.top/Article/details/gtwsnozpcg.html

TS:   process.argv.slice(2)
来源：http://dali.chenjidiqi.icu/Article/details/gtqscgyzqr.html

Java: args 数组（main 方法参数）
来源：http://dali.zdqjudy.top/Article/details/gtshhxjzgp.html

Go:   os.Args[1:]
来源：http://dali.chenzaomai.com/Article/details/gtjnddrjte.html

Ruby: ARGV
来源：http://dali.meibo888.top/Article/details/gtucgafoeq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.feifeiyinyue.top/Article/details/gtaxfxawgo.html

[M02] 读取环境变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtmwmgmawg.html

Py:   os.environ.get("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gtohxuwfca.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.redwolf501.top/Article/details/gtzsxuuvgs.html

JS:   process.env.HOME
来源：http://dali.pycfn.com/Article/details/gtpnrsyxve.html

TS:   process.env.HOME
来源：http://dali.ppjwa.cn/Article/details/gtghhsmxuj.html

Java: System.getenv("HOME")
来源：http://dali.gotoacloud.top/Article/details/gtadylakff.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sufxvd.cn/Article/details/gtedaldvrb.html

Ruby: ENV["HOME"]
来源：http://dali.havefunace.top/Article/details/gtvwhgljqw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.aizwys.cn/Article/details/gtnkbpqyhc.html

[M03] 执行外部命令
来源：http://dali.snrcjt.cn/Article/details/gtwulevgdc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.wangshuangyany.cn/Article/details/gtdpthwsyo.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shzxlz.cn/Article/details/gthzqxshiw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yueranfly.top/Article/details/gtewtjimzs.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ppjwa.cn/Article/details/gtxgiqtfhv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.haohaochexian.top/Article/details/gtadlsnput.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yuanzhike.top/Article/details/gtpcuhgbau.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.snrcjt.cn/Article/details/gtwvfmudza.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ehwqpu.com/Article/details/gtavudrrch.html

[M04] 获取当前工作目录
来源：http://dali.quarkkingdee.top/Article/details/gtwotqgtsl.html

Py:   os.getcwd()
来源：http://dali.sufxvd.cn/Article/details/gttxyreflt.html

PHP:  getcwd();
来源：http://dali.jlsjyb.cn/Article/details/gtbyzbrvjq.html

JS:   process.cwd()
来源：http://dali.jinqigfzy.top/Article/details/gtimxawohy.html

TS:   process.cwd()
来源：http://dali.quarkkingdee.top/Article/details/gtvaypdyux.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinqigfzy.top/Article/details/gtkeulgwms.html

Go:   os.Getwd()
来源：http://dali.hnqzz.top/Article/details/gtktbbzajw.html

Ruby: Dir.pwd
来源：http://dali.hnxiangtu.top/Article/details/gtbjocbfxh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.c1oappe.top/Article/details/gttnlfejir.html

[M05] 设置退出码
来源：http://dali.cheryme.top/Article/details/gtxegkpfvr.html

Py:   sys.exit(1)
来源：http://dali.bjfxy.top/Article/details/gtmmlwozgi.html

PHP:  exit(1);
来源：http://dali.gogol.net.cn/Article/details/gtbqptispd.html

JS:   process.exit(1)
来源：http://dali.cucudq.cn/Article/details/gtlcoqiynz.html

TS:   process.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtkdcaugqu.html

Java: System.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gtemqrhext.html

Go:   os.Exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gtssrukbba.html

Ruby: exit 1
来源：http://dali.jqgufenzy.top/Article/details/gtuvvpfcrs.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.quarkkingdee.top/Article/details/gthlxyovby.html

[M06] 向标准错误输出
来源：http://dali.kuanghao11.cn/Article/details/gtrxwixxbp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.0kj1m.cn/Article/details/gtnsoogvij.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jqgufenzy.top/Article/details/gtzegfmqow.html

JS:   console.error("err")
来源：http://dali.yangfankeji.com/Article/details/gtsxpyokuh.html

TS:   console.error("err")
来源：http://dali.sysykeji.top/Article/details/gtceikjtyw.html

Java: System.err.println("err")
来源：http://dali.aibaodan.cn/Article/details/gtcajrvfyb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.birdmap.top/Article/details/gtrnpxtgyl.html

Ruby: warn "err"
来源：http://dali.cheryme.top/Article/details/gtsmozykjr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hongshengwenyu.top/Article/details/gtxsiyarec.html

[M07] 判断是否为主入口
来源：http://dali.xziqi.cn/Article/details/gtjwotdkgv.html

Py:   if __name__ == "__main__":
来源：http://dali.guowangkeji.top/Article/details/gtemzrylgq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ivvv.top/Article/details/gtsluwusvo.html

JS:   require.main === module
来源：http://dali.yj20258.top/Article/details/gtjcgczswh.html

TS:   require.main === module
来源：http://dali.cucudq.cn/Article/details/gtezrnfmmu.html

Java: public static void main(String[] args)
来源：http://dali.ppjwa.cn/Article/details/gtgcsrvrzm.html

Go:   func main()
来源：http://dali.yangfankeji.com/Article/details/gtnpsfxgcx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhixingplan.top/Article/details/gtadjzvyiz.html

C#:   static void Main(string[] args)
来源：http://dali.jinqigfzy.top/Article/details/gtrvnrapfg.html

[M08] 获取系统与运行时信息
来源：http://dali.pengpengdd.cyou/Article/details/gtubvikysu.html

Py:   platform.system();  platform.python_version()
来源：http://dali.iojbl.cn/Article/details/gtlpevtmlh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.chenzaomai.com/Article/details/gtturvlavf.html

JS:   process.platform;  process.version
来源：http://dali.0kj1m.cn/Article/details/gtuhctoawb.html

TS:   process.platform;  process.version
来源：http://dali.shangyingyoupin.top/Article/details/gtvemojprx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.redwolf501.top/Article/details/gtezlkycav.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.redwolf501.top/Article/details/gtovrffiqf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.haohaochexian.top/Article/details/gtbbglyytq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gogol.net.cn/Article/details/gtdqtlmjvl.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtnbysicsd.html

N. 数据结构与算法
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyfwieuox.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtziyfupeo.html

[N01] 二分查找（有序数组）
来源：http://dali.cheryme.top/Article/details/gtgijffmse.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hammf.cn/Article/details/gtncgnpela.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jqgufenzy.top/Article/details/gtraatzsxb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cdnleiting.top/Article/details/gtgdlnhlwv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxuanxn.top/Article/details/gtbkduglby.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gthkdpeywl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtqnnrxuvd.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhoulong.xyz/Article/details/gtfohytwbe.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yongpay.top/Article/details/gtnvmxedah.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zdqjudy.top/Article/details/gtwbkukvry.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zdqjudy.top/Article/details/gttmfaujza.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwzikcgyf.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenlongwang.top/Article/details/gtijvutyfz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenlongwang.top/Article/details/gtgdfdranu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yongpay.top/Article/details/gtcnlghhdh.html

Go:   slices.Sort(arr)
来源：http://dali.dashuyun.cn/Article/details/gtwqjohhhk.html

Ruby: arr.sort
来源：http://dali.ehwqpu.com/Article/details/gtgynnctos.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cqqwz.cn/Article/details/gtwrtyjntn.html

[N03] 快速排序（分治示例）
来源：http://dali.wangdashe.top/Article/details/gtpyaucvyk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cucudq.cn/Article/details/gthsmubtko.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhixingplan.top/Article/details/gtwdplnebi.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.vqdsnc.cn/Article/details/gtlilofzun.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nwbrower.top/Article/details/gtsddcjlip.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj20258.top/Article/details/gtzkqkjabt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hysaishi.cn/Article/details/gtzmocenrn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xuanzx.com/Article/details/gtkkhyewnf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xziqi.cn/Article/details/gtnpnpyxjm.html

[N04] 斐波那契数列
来源：http://dali.dianchejie.cn/Article/details/gtfwuliapc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xuanzx.com/Article/details/gtowozhmjf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsczqkxrr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yueranfly.top/Article/details/gtviklyhbl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.iojbl.cn/Article/details/gtxrutyrji.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yj20258.top/Article/details/gtwsolpobl.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhoulong.xyz/Article/details/gtcqprynmx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.bjfxy.top/Article/details/gtwbgxvzte.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj20258888.top/Article/details/gtorgmtobw.html

[N05] 最大公约数
来源：http://dali.ppjwa.cn/Article/details/gthwwwatmd.html

Py:   math.gcd(a, b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqhbtkdxx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hongshengwenyu.top/Article/details/gtcwujmhlf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangdashe.top/Article/details/gtpzcgixpp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guowangkeji.top/Article/details/gtwskifvuk.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ivvv.top/Article/details/gtzhcqhmld.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.fzhhl.top/Article/details/gtmroguyxv.html

Ruby: a.gcd(b)
来源：http://dali.yueranfly.top/Article/details/gtxspiwadj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqdzybauc.html

[N06] 判断回文字符串
来源：http://dali.yj20258888.top/Article/details/gtxtlhmbsn.html

Py:   s == s[::-1]
来源：http://dali.cheryme.top/Article/details/gtzspwxeur.html

PHP:  $s === strrev($s);
来源：http://dali.svipenyu.cn/Article/details/gtnrpkbjno.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gtbcrbzmbl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gtmjexjhqd.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.daria6918.cn/Article/details/gtokchcdfw.html

Go:   // 双指针从两端比较
来源：http://dali.ehwqpu.com/Article/details/gtaumbgiku.html

Ruby: s == s.reverse
来源：http://dali.svipenyu.cn/Article/details/gtxnjcazsd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhongyouzk.top/Article/details/gtzviftznr.html

[N07] 两数之和（返回下标）
来源：http://dali.haohaochexian.top/Article/details/gtfurqamhg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gzhubu.top/Article/details/gtgwnktvow.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.aizwys.cn/Article/details/gtxjqsdwpj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yueranfly.top/Article/details/gtnxazdijm.html

TS:   // 手写 Map<string, number>
来源：http://dali.haohaochexian.top/Article/details/gtxjfoxiph.html

Java: // 手写 HashMap
来源：http://dali.yueranfly.top/Article/details/gtwxnkeqoe.html

Go:   // 手写 map[int]int
来源：http://dali.nanxuanxn.top/Article/details/gtlcaehaee.html

Ruby: // 手写 Hash
来源：http://dali.316326.xyz/Article/details/gttmnjyipo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ybcxt.top/Article/details/gtuiwzkqig.html

[N08] 生成全排列
来源：http://dali.ywan-chungtsiang.top/Article/details/gthrwerzsx.html

Py:   itertools.permutations(arr)
来源：http://dali.yj202588.top/Article/details/gtmaqdfexc.html

PHP:  // 手写递归交换
来源：http://dali.hywenlv.cn/Article/details/gtddifxhpc.html

JS:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtonbyqhig.html

TS:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gtrdcsybxs.html

Java: // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gtmggeyqta.html

Go:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gtmgjktflo.html

Ruby: arr.permutation.to_a
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmxtoalra.html

C#:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtkgtqzgjy.html

[N09] 栈与队列
来源：http://dali.c1oappe.top/Article/details/gtpzwqlqfa.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.daxiang520.top/Article/details/gtphyknogr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.aibaodan.cn/Article/details/gtmimauurx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtecwficcv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.svipenyu.cn/Article/details/gtnvlalkxu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.smart0.xyz/Article/details/gtabextgiv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yueranfly.top/Article/details/gtvcixpvgt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.guannengcc.top/Article/details/gtilljhuzw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cucudq.cn/Article/details/gtgzbisklk.html

[N10] 链表节点定义
来源：http://dali.chenlongwang.top/Article/details/gtsebyxwro.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.fzhhl.top/Article/details/gtstmbpetq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.iojbl.cn/Article/details/gtabityaiy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.mhx1999.top/Article/details/gtvouetnlc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yj20258888.top/Article/details/gtjrngnetj.html

Java: class Node { int v; Node next; }
来源：http://dali.gaohongyu789.top/Article/details/gtzhrrtsvg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.smart0.xyz/Article/details/gtyfdeixqa.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhongyouzk.top/Article/details/gtnwrqnzjr.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cucudq.cn/Article/details/gtjczanbga.html

[N11] 二叉树中序遍历
来源：http://dali.xziqi.cn/Article/details/gtnrnzmeun.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.quarkkingdee.top/Article/details/gtwbhhuoek.html

PHP:  // 手写递归函数
来源：http://dali.yanxiufei.cn/Article/details/gtdgdnsjlj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigufen.top/Article/details/gtwxypmwcv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sxryk.cn/Article/details/gtjswogzkt.html

Java: // 手写递归
来源：http://dali.sysykeji.top/Article/details/gtmxknvstr.html

Go:   // 手写递归
来源：http://dali.jinqigfzy.top/Article/details/gtkdyhagmi.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ybcxt.top/Article/details/gtdkqelmko.html

C#:   // 手写递归
来源：http://dali.cqqwz.cn/Article/details/gtruharsup.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.tanke756.top/Article/details/gtktbnmojc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.guowangkeji.top/Article/details/gtxlwiyexq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ydzc1.top/Article/details/gtflcirzms.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gogol.net.cn/Article/details/gtrwwlyepo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aizwys.cn/Article/details/gtcvsdcqfz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.svipenyu.cn/Article/details/gtydshkpkt.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.meibo888.top/Article/details/gtlqwbusfy.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.kuanghao11.cn/Article/details/gtkcqzgnof.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shzxlz.cn/Article/details/gtairukmib.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtguaslldt.html

O. 并发与异步
来源：http://dali.dashuyun.cn/Article/details/gtitqqldas.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtngxrbjwq.html

[O01] 启动一个线程
来源：http://dali.chenjidiqi.icu/Article/details/gtstdgomie.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.9152youxi.cn/Article/details/gtoaawflmg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sxryk.cn/Article/details/gtaidzucfx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jiagoushi.top/Article/details/gtihhjzmja.html

TS:   // 同 JS
来源：http://dali.wangshuangyany.cn/Article/details/gtcthkfyth.html

Java: new Thread(() -> f()).start()
来源：http://dali.daria6918.cn/Article/details/gtyvzftvhl.html

Go:   go f()
来源：http://dali.pengpengdd.cyou/Article/details/gtjvwqrajl.html

Ruby: Thread.new { f }
来源：http://dali.jianghu66.top/Article/details/gtkuevaudh.html

C#:   Task.Run(() => F());
来源：http://dali.0kj1m.cn/Article/details/gtjliluqbo.html

[O02] 使用线程池
来源：http://dali.redwolf501.top/Article/details/gtzcuqxfdx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.fzhhl.top/Article/details/gtxepcpwap.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yanxiufei.cn/Article/details/gtymcpjmel.html

JS:   // worker_threads 线程池
来源：http://dali.guannengcc.top/Article/details/gtxfqjenxm.html

TS:   // worker_threads 线程池
来源：http://dali.dianchejie.cn/Article/details/gtkjpohqtl.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shuidangran.top/Article/details/gtbignqyne.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xinyue.icu/Article/details/gtogbbvlma.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yuxming.cn/Article/details/gtdwmgcfuw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.snrcjt.cn/Article/details/gtryvtbjjc.html

[O03] 加锁保护共享数据
来源：http://dali.dianchejie.cn/Article/details/gtdbisvvgv.html

Py:   with lock: shared += 1
来源：http://dali.wangdashe.top/Article/details/gtfpupnnzf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jiagoushi.top/Article/details/gtepdlxwmg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shangyingyoupin.top/Article/details/gtslgndccc.html

TS:   // 同 JS
来源：http://dali.bjfxy.top/Article/details/gtqrhgugbe.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwewfzwxd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yj202588.top/Article/details/gtldbyweia.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.kuanghao11.cn/Article/details/gtmafneyxh.html

C#:   lock (gate) { shared++; }
来源：http://dali.yueranfly.top/Article/details/gtlskavets.html

[O04] 定义异步函数并等待
来源：http://dali.hnxiangtu.top/Article/details/gtjpcclgia.html

Py:   async def f():⏎    await g()
来源：http://dali.ehwqpu.com/Article/details/gtoiafyrvg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xziqi.cn/Article/details/gtszdvkqqe.html

JS:   async function f() { await g(); }
来源：http://dali.quarkkingdee.top/Article/details/gteqawaebj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtnxhkueiy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinghuilouyu.cn/Article/details/gtuidyiolq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nanxuanxn.top/Article/details/gtiexllzds.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gttruvklff.html

C#:   async Task F() { await G(); }
来源：http://dali.dashuyun.cn/Article/details/gtxauupksp.html

[O05] 并发执行并等待全部完成
来源：http://dali.yongpay.top/Article/details/gthbtfvdlh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.snrcjt.cn/Article/details/gtzlahdqzb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvozhwhdq.html

JS:   await Promise.all(tasks)
来源：http://dali.chenjidiqi.icu/Article/details/gtxvfmfkgg.html

TS:   await Promise.all(tasks)
来源：http://dali.ivvv.top/Article/details/gtuoyjetly.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xylfe.cn/Article/details/gtbofefzcy.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.pycfn.com/Article/details/gtkerzpvgy.html

Ruby: threads.map(&:join)
来源：http://dali.gotoacloud.top/Article/details/gtpkziyapx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hnqzz.top/Article/details/gtcarxlcpo.html

[O06] 使用进程池
来源：http://dali.haohaochexian.top/Article/details/gtnjyqbzap.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.nanxuanxn.top/Article/details/gtkjhpzrov.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinqigufen.top/Article/details/gtepwiwocf.html

JS:   // child_process / cluster 模块
来源：http://dali.ehwqpu.com/Article/details/gtliclypgt.html


<!-- 参考信息 -->