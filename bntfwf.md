代发 wailian999

L. 网络请求
来源：http://dali.shanyushiyangtech.top/Article/details/gtpwgqginy.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtvffuxpyq.html

[L01] 发送 GET 请求
来源：http://dali.9152youxi.cn/Article/details/gtqcfkrdfp.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jqgufenzy.top/Article/details/gtdnawmqiw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinqigufen.top/Article/details/gtlqlbzjgj.html

JS:   await fetch(url)
来源：http://dali.yj20258888.top/Article/details/gthqfsbciw.html

TS:   await fetch(url)
来源：http://dali.sysykeji.top/Article/details/gtaxcqbyfv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gaohongyu789.top/Article/details/gtskqawqbb.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtofqqnjgt.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shzxlz.cn/Article/details/gtdquuzqpn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cucudq.cn/Article/details/gtzyogwnys.html

[L02] 发送 POST JSON
来源：http://dali.wangdashe.top/Article/details/gtwzbmyega.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpkyfqjxp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hfpthk.cn/Article/details/gtiobgwfgb.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guannengcc.top/Article/details/gtstsmbkmc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangtech.top/Article/details/gtsfhbhsaz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.guowangkeji.top/Article/details/gtnuubzwul.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.iojbl.cn/Article/details/gtslfoaxqe.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nwbrower.top/Article/details/gtovrtbsgv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jlsjyb.cn/Article/details/gtemdlthqm.html

[L03] 设置自定义请求头
来源：http://dali.fzhhl.top/Article/details/gtzogmfbsc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.pengpengdd.cyou/Article/details/gtmmprgkkj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.fzhhl.top/Article/details/gttchnveha.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gotoacloud.top/Article/details/gtperrrqay.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cheryme.top/Article/details/gterzpvrgf.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.wangdashe.top/Article/details/gtdgyeajnv.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.tanke756.top/Article/details/gtqegogalg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.quarkkingdee.top/Article/details/gtabpcyste.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sweek.top/Article/details/gtkodojldq.html

[L04] 设置超时
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiinnakxx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yonumen.top/Article/details/gtrjqhcnij.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.tian-w.cn/Article/details/gtkdkcbcha.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aizwys.cn/Article/details/gtvhewgzrp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyeeozlnc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ydzc1.top/Article/details/gtfusrfbby.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ivvv.top/Article/details/gtetfrgouh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.pengpengdd.cyou/Article/details/gtimdtsgqk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xinyue.icu/Article/details/gtfamqeqlj.html

[L05] 上传文件（multipart）
来源：http://dali.c1oappe.top/Article/details/gttmjdueuk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhongyouzk.top/Article/details/gtvyqbssrh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ehwqpu.com/Article/details/gtstizaycf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhixingplan.top/Article/details/gtrqlrzgil.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hysaishi.cn/Article/details/gtvchhovmr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gaohongyu789.top/Article/details/gthzfigfqf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shuidangran.top/Article/details/gtykmqiiit.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.chenzaomai.com/Article/details/gttiftegvr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cheryme.top/Article/details/gtugrnpood.html

[L06] 解析响应为 JSON
来源：http://dali.shangyingyoupin.top/Article/details/gtdztjlign.html

Py:   resp.json()
来源：http://dali.kuanghao11.cn/Article/details/gtojngkrkc.html

PHP:  json_decode($body, true);
来源：http://dali.zhiwuduotai.top/Article/details/gttdelfbht.html

JS:   await resp.json()
来源：http://dali.zdqjudy.top/Article/details/gtageziyjg.html

TS:   await resp.json()
来源：http://dali.pengpengdd.cyou/Article/details/gtjvqtjkls.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sufxvd.cn/Article/details/gtboerqxme.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xuanzx.com/Article/details/gtudynqvzo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hnxiangtu.top/Article/details/gtyeelirlz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.chenlongwang.top/Article/details/gtdaaxvzey.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj20258888.top/Article/details/gtjihhkcav.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhoulong.xyz/Article/details/gtcdahcyas.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nanxuanxn.top/Article/details/gtirqlboil.html

JS:   resp.ok;  resp.status
来源：http://dali.yj202588.top/Article/details/gtapilramu.html

TS:   resp.ok;  resp.status
来源：http://dali.daxiang520.top/Article/details/gtnlyrohpm.html

Java: resp.statusCode()
来源：http://dali.guowangkeji.top/Article/details/gtjtxnbzuo.html

Go:   resp.StatusCode
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkjoibtcm.html

Ruby: resp.code.to_i
来源：http://dali.zdqjudy.top/Article/details/gtyiqpuyak.html

C#:   (int)resp.StatusCode
来源：http://dali.c1oappe.top/Article/details/gtxcpchuxv.html

[L08] 并发请求多个地址
来源：http://dali.hfpthk.cn/Article/details/gtrtnyyazy.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xylfe.cn/Article/details/gtbsqoafhg.html

PHP:  curl_multi_init() 系列
来源：http://dali.xziqi.cn/Article/details/gtxlwecvlw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.birdmap.top/Article/details/gtdawqmcik.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.0kj1m.cn/Article/details/gtrgvnbddb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yonumen.top/Article/details/gtuanzkdem.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jqgfzy.top/Article/details/gtobvheswt.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.9152youxi.cn/Article/details/gtwiwpxqdn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hammf.cn/Article/details/gtpzptooua.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtixaeejsd.html

M. 命令行 / 进程 / 环境
来源：http://dali.ivvv.top/Article/details/gttmwhkrqt.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtwbkkhpkj.html

[M01] 读取命令行参数
来源：http://dali.zhiwuduotai.top/Article/details/gtgrvneeat.html

Py:   sys.argv[1:]
来源：http://dali.nwbrower.top/Article/details/gtstdiwbnl.html

PHP:  $argv;  $argc;
来源：http://dali.cheryme.top/Article/details/gtsxklkwev.html

JS:   process.argv.slice(2)
来源：http://dali.chenzaomai.com/Article/details/gtuzxncmdf.html

TS:   process.argv.slice(2)
来源：http://dali.zdqjudy.top/Article/details/gtrfjceyql.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gticekzayj.html

Go:   os.Args[1:]
来源：http://dali.hywenlv.cn/Article/details/gtuhbkmfwo.html

Ruby: ARGV
来源：http://dali.0kj1m.cn/Article/details/gtxscmlooa.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyxqdyhhp.html

[M02] 读取环境变量
来源：http://dali.daria6918.cn/Article/details/gtsxdnlvpv.html

Py:   os.environ.get("HOME")
来源：http://dali.9152youxi.cn/Article/details/gtlpkgsyea.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.meibo888.top/Article/details/gtelnpupmw.html

JS:   process.env.HOME
来源：http://dali.smart0.xyz/Article/details/gtfpzaldyq.html

TS:   process.env.HOME
来源：http://dali.jinqigfzy.top/Article/details/gtipryyafk.html

Java: System.getenv("HOME")
来源：http://dali.yonumen.top/Article/details/gtiuhjkgvt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.pycfn.com/Article/details/gtrcqcifmf.html

Ruby: ENV["HOME"]
来源：http://dali.gzhubu.top/Article/details/gtiemuobxr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xylfe.cn/Article/details/gtpgcjtwhg.html

[M03] 执行外部命令
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsuzktuok.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.0kj1m.cn/Article/details/gtfxljzqdd.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.vqdsnc.cn/Article/details/gtoiyeixua.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shzxlz.cn/Article/details/gttgjxcukg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.guowangkeji.top/Article/details/gtpwcgvmqx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.tianlin.xyz/Article/details/gtczcitvgm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shangyingyoupin.top/Article/details/gtjmdolwiw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tanke756.top/Article/details/gtozqvwejq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yj20258888.top/Article/details/gtvhvgfoit.html

[M04] 获取当前工作目录
来源：http://dali.cucudq.cn/Article/details/gtweuzrnwz.html

Py:   os.getcwd()
来源：http://dali.hammf.cn/Article/details/gtgghrpmat.html

PHP:  getcwd();
来源：http://dali.zhongyouzk.top/Article/details/gtipsrrsug.html

JS:   process.cwd()
来源：http://dali.gogol.net.cn/Article/details/gtlinknxqp.html

TS:   process.cwd()
来源：http://dali.yj20258.top/Article/details/gtrgoqupli.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrmujuevj.html

Go:   os.Getwd()
来源：http://dali.redwolf501.top/Article/details/gtzzizqkif.html

Ruby: Dir.pwd
来源：http://dali.tian-w.cn/Article/details/gtebozfess.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.tianlin.xyz/Article/details/gtvlcznyyy.html

[M05] 设置退出码
来源：http://dali.tanke756.top/Article/details/gtepxkuxwv.html

Py:   sys.exit(1)
来源：http://dali.zycfv.cn/Article/details/gtzczquqfz.html

PHP:  exit(1);
来源：http://dali.sweek.top/Article/details/gtoqqxncpw.html

JS:   process.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gtkmsfmstx.html

TS:   process.exit(1)
来源：http://dali.c1oappe.top/Article/details/gttaznnlay.html

Java: System.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gtabecfpdh.html

Go:   os.Exit(1)
来源：http://dali.andypj.xyz/Article/details/gtcvheeqsn.html

Ruby: exit 1
来源：http://dali.xuetiantiany.cn/Article/details/gtunzvdmhv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj20258888.top/Article/details/gtoxxtklzo.html

[M06] 向标准错误输出
来源：http://dali.sysykeji.top/Article/details/gtbkihvdhf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.birdmap.top/Article/details/gtwniuisar.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.dianchejie.cn/Article/details/gthymcyvku.html

JS:   console.error("err")
来源：http://dali.ivvv.top/Article/details/gtdjurnxfl.html

TS:   console.error("err")
来源：http://dali.jlsjyb.cn/Article/details/gtbcfjotqv.html

Java: System.err.println("err")
来源：http://dali.jlsjyb.cn/Article/details/gtficgbexh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.chenlongwang.top/Article/details/gtqorvaijk.html

Ruby: warn "err"
来源：http://dali.hnxiangtu.top/Article/details/gtuhpxzhou.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.bjfxy.top/Article/details/gtzempbzje.html

[M07] 判断是否为主入口
来源：http://dali.jinghuilouyu.cn/Article/details/gtxzuaenvm.html

Py:   if __name__ == "__main__":
来源：http://dali.shzxlz.cn/Article/details/gtuboggnub.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hysaishi.cn/Article/details/gtecmwzgcw.html

JS:   require.main === module
来源：http://dali.tianlin.xyz/Article/details/gtmlfemgkw.html

TS:   require.main === module
来源：http://dali.hnqzz.top/Article/details/gtdicjaurj.html

Java: public static void main(String[] args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjsfyubvf.html

Go:   func main()
来源：http://dali.hysaishi.cn/Article/details/gtpmuodbyu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.andypj.xyz/Article/details/gtkeekagkn.html

C#:   static void Main(string[] args)
来源：http://dali.0kj1m.cn/Article/details/gtpqaecmvr.html

[M08] 获取系统与运行时信息
来源：http://dali.yuxming.cn/Article/details/gtztuzrerd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ydzc1.top/Article/details/gtptulopjq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.aibaodan.cn/Article/details/gtcckcihgd.html

JS:   process.platform;  process.version
来源：http://dali.ivvv.top/Article/details/gtcfvlglmh.html

TS:   process.platform;  process.version
来源：http://dali.cashguo.top/Article/details/gthvorbfdj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gtvtwptvxo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gotoacloud.top/Article/details/gtbunwcuxv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.dashuyun.cn/Article/details/gtvtsqyukb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.guowangkeji.top/Article/details/gtjmcuszqb.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuphinxff.html

N. 数据结构与算法
来源：http://dali.hammf.cn/Article/details/gtpatwcltj.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtmmscubnr.html

[N01] 二分查找（有序数组）
来源：http://dali.yuanzhike.top/Article/details/gtbfpojmbw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtedrhnbvz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.chenjidiqi.icu/Article/details/gtzorcxknp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yangfankeji.com/Article/details/gtyfzwchsl.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgfzy.top/Article/details/gtbaonxoff.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtbyylpmek.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtxpsminii.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.wangshuangyany.cn/Article/details/gtotzoigof.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtwzxwvlyo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenjidiqi.icu/Article/details/gtysmofxfg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zdqjudy.top/Article/details/gtrtlpnqmc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cheryme.top/Article/details/gtdnzuzgio.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnqzz.top/Article/details/gtmcaffmxi.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gtvykvdenn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.havefunace.top/Article/details/gtwoeuiucz.html

Go:   slices.Sort(arr)
来源：http://dali.iojbl.cn/Article/details/gtosgehcic.html

Ruby: arr.sort
来源：http://dali.zhixingplan.top/Article/details/gtegbbkpub.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.0kj1m.cn/Article/details/gtjjbxsxwt.html

[N03] 快速排序（分治示例）
来源：http://dali.sufxvd.cn/Article/details/gtvessxtbz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.tianlin.xyz/Article/details/gtpdaqvmxu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkjotqmke.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhiwuduotai.top/Article/details/gtodipyiom.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenjidiqi.icu/Article/details/gtbhvwlmlf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ehwqpu.com/Article/details/gtguyktepd.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ppjwa.cn/Article/details/gtbvwvzsdl.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jyoumei.cn/Article/details/gtfziizlvg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shzxlz.cn/Article/details/gtyljtddzl.html

[N04] 斐波那契数列
来源：http://dali.fzhhl.top/Article/details/gtfenqtyhi.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.chenlongwang.top/Article/details/gtiugedpik.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shuidangran.top/Article/details/gtuwgialxs.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gthpvqdgtn.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gtvxcowrqt.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yangfankeji.com/Article/details/gtoccebnns.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yuxming.cn/Article/details/gtskxaarrn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtirrbwrlj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gtcykaquzq.html

[N05] 最大公约数
来源：http://dali.birdmap.top/Article/details/gtybkthpzn.html

Py:   math.gcd(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gtiklprahr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.aizwys.cn/Article/details/gtouezuayx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtmnlyizcr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sxryk.cn/Article/details/gtoqofinph.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcqpwtlgb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.bjfxy.top/Article/details/gthyvtnjaw.html

Ruby: a.gcd(b)
来源：http://dali.yvedp.cn/Article/details/gtlfifhcpy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hfpthk.cn/Article/details/gtwcjcjwhs.html

[N06] 判断回文字符串
来源：http://dali.zhixingplan.top/Article/details/gtpgykvinw.html

Py:   s == s[::-1]
来源：http://dali.tianlin.xyz/Article/details/gtjnhyenmp.html

PHP:  $s === strrev($s);
来源：http://dali.yanxiufei.cn/Article/details/gtrwhvodou.html

JS:   s === [...s].reverse().join("")
来源：http://dali.feifeiyinyue.top/Article/details/gttqclwazz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xuetiantiany.cn/Article/details/gteajkvfwj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sufxvd.cn/Article/details/gtwtesloio.html

Go:   // 双指针从两端比较
来源：http://dali.fengsongda.top/Article/details/gtzifhlchi.html

Ruby: s == s.reverse
来源：http://dali.yj20258888.top/Article/details/gtphlkamds.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.fengsongda.top/Article/details/gtprgachvn.html

[N07] 两数之和（返回下标）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrftnricj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cdnleiting.top/Article/details/gtechwpovj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinghuilouyu.cn/Article/details/gtwplkdyzj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xuetiantiany.cn/Article/details/gttuwmyvkk.html

TS:   // 手写 Map<string, number>
来源：http://dali.jinghuilouyu.cn/Article/details/gtmfaodjls.html

Java: // 手写 HashMap
来源：http://dali.c1oappe.top/Article/details/gtcbqsfnkl.html

Go:   // 手写 map[int]int
来源：http://dali.xuetiantiany.cn/Article/details/gtmdyvolud.html

Ruby: // 手写 Hash
来源：http://dali.aibaodan.cn/Article/details/gtbdjngonb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.dianchejie.cn/Article/details/gtfeclrkua.html

[N08] 生成全排列
来源：http://dali.xinyue.icu/Article/details/gtnmudqjoc.html

Py:   itertools.permutations(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxzymrzik.html

PHP:  // 手写递归交换
来源：http://dali.ywan-chungtsiang.top/Article/details/gthpnxpdac.html

JS:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gtxfykwboc.html

TS:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gtffosjtzz.html

Java: // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtsudsmpei.html

Go:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtqfbrxign.html

Ruby: arr.permutation.to_a
来源：http://dali.chenjidiqi.icu/Article/details/gtwycysiph.html

C#:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gthpakqanz.html

[N09] 栈与队列
来源：http://dali.jyoumei.cn/Article/details/gtatzfvwde.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.0kj1m.cn/Article/details/gtywoinuhn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.snrcjt.cn/Article/details/gtfiwaahbp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yongpay.top/Article/details/gtpvdgqgnk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ehwqpu.com/Article/details/gthipmvodb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xziqi.cn/Article/details/gtckesdvbf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yvedp.cn/Article/details/gtxmogpiqy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yanxiufei.cn/Article/details/gtpvrfnoom.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xylfe.cn/Article/details/gtehamgiuv.html

[N10] 链表节点定义
来源：http://dali.hnxiangtu.top/Article/details/gtggglohwr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tian-w.cn/Article/details/gtoekynxib.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hongshengwenyu.top/Article/details/gtejrgncic.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shangyingyoupin.top/Article/details/gtazsyonfn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhengqikj.top/Article/details/gtjmksdulm.html

Java: class Node { int v; Node next; }
来源：http://dali.hnqzz.top/Article/details/gtrpfwppta.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenzaomai.com/Article/details/gtlmfqjfzt.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gtcsfcrzof.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hongshengwenyu.top/Article/details/gttemyijop.html

[N11] 二叉树中序遍历
来源：http://dali.andypj.xyz/Article/details/gtafoxctus.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.dashuyun.cn/Article/details/gtdqhlohcj.html

PHP:  // 手写递归函数
来源：http://dali.jyoumei.cn/Article/details/gtngdzvjme.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aibaodan.cn/Article/details/gtwkodbsqa.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sxryk.cn/Article/details/gtldsucyuv.html

Java: // 手写递归
来源：http://dali.dashuyun.cn/Article/details/gtmkbcxvux.html

Go:   // 手写递归
来源：http://dali.birdmap.top/Article/details/gtxqbywfhy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gtnjrjewdk.html

C#:   // 手写递归
来源：http://dali.havefunace.top/Article/details/gtxglwmjuo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.wangdashe.top/Article/details/gttmndqejs.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shuidangran.top/Article/details/gtniyoxafh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhengqikj.top/Article/details/gthgewpapy.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xylfe.cn/Article/details/gtebpnadqp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhiwuduotai.top/Article/details/gtnkdougza.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tian-w.cn/Article/details/gtixpufqeb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yuanzhike.top/Article/details/gtaqlfzqnp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.aizwys.cn/Article/details/gtjvkgsblv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cdnleiting.top/Article/details/gtiofvrpcm.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtilnvcabw.html

O. 并发与异步
来源：http://dali.316326.xyz/Article/details/gthkfwhhvc.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtihlzpzdt.html

[O01] 启动一个线程
来源：http://dali.yj20258.top/Article/details/gtjhkbxicb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.0kj1m.cn/Article/details/gtnhexeqnj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhiwuduotai.top/Article/details/gtviqsvdtv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shuidangran.top/Article/details/gtqdnjadnn.html

TS:   // 同 JS
来源：http://dali.cucudq.cn/Article/details/gtzxmxbifm.html

Java: new Thread(() -> f()).start()
来源：http://dali.hammf.cn/Article/details/gtkzgvczvj.html

Go:   go f()
来源：http://dali.gzhubu.top/Article/details/gtkqactjaz.html

Ruby: Thread.new { f }
来源：http://dali.hysaishi.cn/Article/details/gtdjybzuvq.html

C#:   Task.Run(() => F());
来源：http://dali.birdmap.top/Article/details/gtgirvwnqg.html

[O02] 使用线程池
来源：http://dali.zhengqikj.top/Article/details/gtfhdatzvc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yonumen.top/Article/details/gtdbclshdn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.c1oappe.top/Article/details/gtrdrhojee.html

JS:   // worker_threads 线程池
来源：http://dali.jinqigufen.top/Article/details/gtqlatnemt.html

TS:   // worker_threads 线程池
来源：http://dali.yongpay.top/Article/details/gtfdenstke.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinqigufen.top/Article/details/gtlqewshve.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yonumen.top/Article/details/gtxhkxvbqm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zycfv.cn/Article/details/gtsdldgken.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cdnleiting.top/Article/details/gtsqagkcbe.html

[O03] 加锁保护共享数据
来源：http://dali.sufxvd.cn/Article/details/gtoxbfgjdo.html

Py:   with lock: shared += 1
来源：http://dali.hammf.cn/Article/details/gtfkkereuo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.daria6918.cn/Article/details/gtuhhjimkj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.sufxvd.cn/Article/details/gtgsqnptyf.html

TS:   // 同 JS
来源：http://dali.guannengcc.top/Article/details/gtayclkkiz.html

Java: synchronized (this) { shared++; }
来源：http://dali.ppjwa.cn/Article/details/gtttvvurbq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zycfv.cn/Article/details/gtmlrmpxrf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hywenlv.cn/Article/details/gtayovmxwb.html

C#:   lock (gate) { shared++; }
来源：http://dali.yuxming.cn/Article/details/gtaydmtanl.html

[O04] 定义异步函数并等待
来源：http://dali.daxiang520.top/Article/details/gtxdgtomkl.html

Py:   async def f():⏎    await g()
来源：http://dali.zycfv.cn/Article/details/gtojzgttsd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hywenlv.cn/Article/details/gtojsrpkfm.html

JS:   async function f() { await g(); }
来源：http://dali.hammf.cn/Article/details/gtndbtqbfh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenzaomai.com/Article/details/gtyaqdnhpv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yonumen.top/Article/details/gtepeoawfe.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gtnjfmcxjy.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.nanxinkj.top/Article/details/gtxodpzehk.html

C#:   async Task F() { await G(); }
来源：http://dali.chenlongwang.top/Article/details/gtspcvoncc.html

[O05] 并发执行并等待全部完成
来源：http://dali.316326.xyz/Article/details/gtxrrvwxyw.html


<!-- 参考信息 -->