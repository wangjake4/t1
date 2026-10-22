代发 wailian999

Go:   encoding/gob
来源：http://dali.cucudq.cn/Article/details/gtyineolim.html

Ruby: Marshal.dump(obj)
来源：http://dali.dianchejie.cn/Article/details/gtgiyaytkx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yuxming.cn/Article/details/gtdatewrok.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtyrmgfscr.html

L. 网络请求
来源：http://dali.meibo888.top/Article/details/gtuojalfnu.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtlbxhkpxm.html

[L01] 发送 GET 请求
来源：http://dali.gaohongyu789.top/Article/details/gtsaaycvnj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.smart0.xyz/Article/details/gtpchpxmrr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cucudq.cn/Article/details/gtlzzjorlx.html

JS:   await fetch(url)
来源：http://dali.dashuyun.cn/Article/details/gtnkaukdow.html

TS:   await fetch(url)
来源：http://dali.haohaochexian.top/Article/details/gtatiaxtwi.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ybcxt.top/Article/details/gtgmtrkioq.html

Go:   resp, err := http.Get(url)
来源：http://dali.0kj1m.cn/Article/details/gtqokkypbi.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sufxvd.cn/Article/details/gtzzcvecfl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ydzc1.top/Article/details/gtanepsusk.html

[L02] 发送 POST JSON
来源：http://dali.feifeiyinyue.top/Article/details/gtszwkogtv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yongpay.top/Article/details/gtpwhwewqf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yongpay.top/Article/details/gtoyifwlwk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tian-w.cn/Article/details/gteycijair.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pycfn.com/Article/details/gtafhcmqqc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenjidiqi.icu/Article/details/gtlsyrldxr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.c1oappe.top/Article/details/gtnuvoeshi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.dianchejie.cn/Article/details/gteqzlnmtn.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.daxiang520.top/Article/details/gtmklkvmip.html

[L03] 设置自定义请求头
来源：http://dali.yangfankeji.com/Article/details/gtrcapbxrl.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkouxjqqk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.snrcjt.cn/Article/details/gtdpakhffs.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nwbrower.top/Article/details/gtekopwqez.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tianlin.xyz/Article/details/gtstulmczc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ydzc1.top/Article/details/gtkwuhjmta.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xuanzx.com/Article/details/gthiwqzgrh.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sweek.top/Article/details/gtehadbsao.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.tianlin.xyz/Article/details/gtuycnqiga.html

[L04] 设置超时
来源：http://dali.yj20258888.top/Article/details/gtwwyqztyz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ehwqpu.com/Article/details/gtbprcapns.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjzhtfnih.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj202588.top/Article/details/gtvkqfcdun.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.9152youxi.cn/Article/details/gtxbugavta.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.0kj1m.cn/Article/details/gtxrmfdapa.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hfpthk.cn/Article/details/gtjnnupqwj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yangfankeji.com/Article/details/gtosofyoie.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.daxiang520.top/Article/details/gtnnedsrrj.html

[L05] 上传文件（multipart）
来源：http://dali.zdqjudy.top/Article/details/gttwvxhkwd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.0kj1m.cn/Article/details/gtmjkybyhj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.nanxuanxn.top/Article/details/gtnxwcovul.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jiagoushi.top/Article/details/gtyeabtidc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.haohaochexian.top/Article/details/gtehypmxru.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.chenlongwang.top/Article/details/gtpmbpvaxf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hnxiangtu.top/Article/details/gtbgajwekh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sufxvd.cn/Article/details/gtccoqxjvx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gzhubu.top/Article/details/gtxhsbeuxd.html

[L06] 解析响应为 JSON
来源：http://dali.chenjidiqi.icu/Article/details/gtrsvgbkjm.html

Py:   resp.json()
来源：http://dali.tianlin.xyz/Article/details/gtwqlbsctf.html

PHP:  json_decode($body, true);
来源：http://dali.aibaodan.cn/Article/details/gtdgufquea.html

JS:   await resp.json()
来源：http://dali.zhengqikj.top/Article/details/gtfbytnrjv.html

TS:   await resp.json()
来源：http://dali.haohaochexian.top/Article/details/gthyvsygqs.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zycfv.cn/Article/details/gtsforupfe.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.daria6918.cn/Article/details/gtnquacuyq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.redwolf501.top/Article/details/gtisthpvbb.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnwqpiskq.html

[L07] 处理 HTTP 状态码
来源：http://dali.hywenlv.cn/Article/details/gtcvrwvcfu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.wangdashe.top/Article/details/gtsfonoejz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yuanzhike.top/Article/details/gtpsdjryhu.html

JS:   resp.ok;  resp.status
来源：http://dali.aibaodan.cn/Article/details/gtqmahqmvm.html

TS:   resp.ok;  resp.status
来源：http://dali.xylfe.cn/Article/details/gtbzimrpnt.html

Java: resp.statusCode()
来源：http://dali.ppjwa.cn/Article/details/gtyyyitwoo.html

Go:   resp.StatusCode
来源：http://dali.0kj1m.cn/Article/details/gtkbyrqshx.html

Ruby: resp.code.to_i
来源：http://dali.cqqwz.cn/Article/details/gtfmkttqpf.html

C#:   (int)resp.StatusCode
来源：http://dali.chenjidiqi.icu/Article/details/gtgjgzjamy.html

[L08] 并发请求多个地址
来源：http://dali.aizwys.cn/Article/details/gtpbenajzz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhaomingkeji.xyz/Article/details/gtirtfzdqu.html

PHP:  curl_multi_init() 系列
来源：http://dali.shuidangran.top/Article/details/gtzsywhhdt.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sxryk.cn/Article/details/gtydnxxczr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yueranfly.top/Article/details/gtqrpatcgn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cheryme.top/Article/details/gthaybdaue.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.chenzaomai.com/Article/details/gtbnrkolyl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.havefunace.top/Article/details/gtwppilkfq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkanbcawf.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtjvfxxaxy.html

M. 命令行 / 进程 / 环境
来源：http://dali.ehwqpu.com/Article/details/gtidvafulf.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gttrfoqufp.html

[M01] 读取命令行参数
来源：http://dali.gogol.net.cn/Article/details/gtsdrsjjwx.html

Py:   sys.argv[1:]
来源：http://dali.gzhubu.top/Article/details/gtryadsxea.html

PHP:  $argv;  $argc;
来源：http://dali.jlsjyb.cn/Article/details/gtahzdlska.html

JS:   process.argv.slice(2)
来源：http://dali.hywenlv.cn/Article/details/gtlntosqhn.html

TS:   process.argv.slice(2)
来源：http://dali.zhiwuduotai.top/Article/details/gtvptexkem.html

Java: args 数组（main 方法参数）
来源：http://dali.aizwys.cn/Article/details/gtmalxybaq.html

Go:   os.Args[1:]
来源：http://dali.yueranfly.top/Article/details/gtrvezblwh.html

Ruby: ARGV
来源：http://dali.fzhhl.top/Article/details/gtckobhvgx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhoulong.xyz/Article/details/gtkiygpcnk.html

[M02] 读取环境变量
来源：http://dali.zhengqikj.top/Article/details/gttusacjwi.html

Py:   os.environ.get("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiwdtetoy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tianlin.xyz/Article/details/gtjvmlpppl.html

JS:   process.env.HOME
来源：http://dali.smart0.xyz/Article/details/gtgzdjnilg.html

TS:   process.env.HOME
来源：http://dali.fengsongda.top/Article/details/gtrloykhwd.html

Java: System.getenv("HOME")
来源：http://dali.daxiang520.top/Article/details/gtzzpaeofb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xinyue.icu/Article/details/gtmliwkiwv.html

Ruby: ENV["HOME"]
来源：http://dali.guannengcc.top/Article/details/gtdadthatl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gtbzmmfbsd.html

[M03] 执行外部命令
来源：http://dali.shangyingyoupin.top/Article/details/gtbuhxrzbe.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yvedp.cn/Article/details/gthbhpngkt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.birdmap.top/Article/details/gtubtfyenn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.snrcjt.cn/Article/details/gtlodivovx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtygiaepwk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.vqdsnc.cn/Article/details/gtmycrsjvp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.redwolf501.top/Article/details/gtbfbfohdi.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xziqi.cn/Article/details/gtdsasdbfy.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xuetiantiany.cn/Article/details/gtsqesfvao.html

[M04] 获取当前工作目录
来源：http://dali.sysykeji.top/Article/details/gthcryxhtx.html

Py:   os.getcwd()
来源：http://dali.yj20258888.top/Article/details/gtcgpepdbx.html

PHP:  getcwd();
来源：http://dali.andypj.xyz/Article/details/gtgxriakut.html

JS:   process.cwd()
来源：http://dali.shangyingyoupin.top/Article/details/gtublwbipb.html

TS:   process.cwd()
来源：http://dali.meibo888.top/Article/details/gtprrvfukc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.0kj1m.cn/Article/details/gtuxrrkxaa.html

Go:   os.Getwd()
来源：http://dali.cheryme.top/Article/details/gtvkbfuwuo.html

Ruby: Dir.pwd
来源：http://dali.vqdsnc.cn/Article/details/gtpdcobwmi.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shanyushiyangtech.top/Article/details/gtdycipzcc.html

[M05] 设置退出码
来源：http://dali.shanyushiyangtech.top/Article/details/gtwqvwzqot.html

Py:   sys.exit(1)
来源：http://dali.mhx1999.top/Article/details/gtlrmntbsz.html

PHP:  exit(1);
来源：http://dali.yvedp.cn/Article/details/gtnimpjrho.html

JS:   process.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxdirjeot.html

TS:   process.exit(1)
来源：http://dali.316326.xyz/Article/details/gtntnyusiy.html

Java: System.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gtyxnfiwvc.html

Go:   os.Exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtnvpegflj.html

Ruby: exit 1
来源：http://dali.ppjwa.cn/Article/details/gtozwgkgtq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.fzhhl.top/Article/details/gtwttpzgrz.html

[M06] 向标准错误输出
来源：http://dali.shangyingyoupin.top/Article/details/gtgilgovig.html

Py:   print("err", file=sys.stderr)
来源：http://dali.daria6918.cn/Article/details/gtulvpjyhr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.0kj1m.cn/Article/details/gtktrirvlt.html

JS:   console.error("err")
来源：http://dali.chenzaomai.com/Article/details/gtwycwggzd.html

TS:   console.error("err")
来源：http://dali.daxiang520.top/Article/details/gtemkvilum.html

Java: System.err.println("err")
来源：http://dali.hfpthk.cn/Article/details/gtbcqsciko.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.havefunace.top/Article/details/gttzkidgfa.html

Ruby: warn "err"
来源：http://dali.jianghu66.top/Article/details/gtrdvtaaqv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hywenlv.cn/Article/details/gtnrolcrux.html

[M07] 判断是否为主入口
来源：http://dali.gotoacloud.top/Article/details/gtxtbdsevi.html

Py:   if __name__ == "__main__":
来源：http://dali.tian-w.cn/Article/details/gtdcjohzjt.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.wangdashe.top/Article/details/gtvsskfmhj.html

JS:   require.main === module
来源：http://dali.shangyingyoupin.top/Article/details/gtsscywfxf.html

TS:   require.main === module
来源：http://dali.feifeiyinyue.top/Article/details/gttnhjtmps.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gteelnxbuk.html

Go:   func main()
来源：http://dali.guannengcc.top/Article/details/gtskjcvbxt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.guannengcc.top/Article/details/gtnleerjvy.html

C#:   static void Main(string[] args)
来源：http://dali.birdmap.top/Article/details/gtvwtpksou.html

[M08] 获取系统与运行时信息
来源：http://dali.nanxuanxn.top/Article/details/gtevvplvtv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sxryk.cn/Article/details/gtyskwtwvm.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.0kj1m.cn/Article/details/gtpvnswrjw.html

JS:   process.platform;  process.version
来源：http://dali.aibaodan.cn/Article/details/gtbvrsrjqj.html

TS:   process.platform;  process.version
来源：http://dali.aizwys.cn/Article/details/gtqksgburu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shanyushiyangtech.top/Article/details/gtlswonedz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shangyingyoupin.top/Article/details/gtjdgplnhp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jiagoushi.top/Article/details/gtjapdxmkp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hongshengwenyu.top/Article/details/gtswmthned.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtuunsbjth.html

N. 数据结构与算法
来源：http://dali.sxryk.cn/Article/details/gtprnytrkp.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtylhprqgn.html

[N01] 二分查找（有序数组）
来源：http://dali.aizwys.cn/Article/details/gtuyfqxtip.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtvfbvtbzj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.daria6918.cn/Article/details/gtfalfaqpx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqqlpynsm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shuidangran.top/Article/details/gthjxryesv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gtkcqgqkxo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtpjoxaxgn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hysaishi.cn/Article/details/gtgirrlwby.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.havefunace.top/Article/details/gtdgwkkqta.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yueranfly.top/Article/details/gtnmhtdmfh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yvedp.cn/Article/details/gtkahpjhwr.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yj20258.top/Article/details/gtqnpxvofi.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhixingplan.top/Article/details/gtaoepgqeb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yongpay.top/Article/details/gtzmyhxmnp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yj20258.top/Article/details/gtfffhruef.html

Go:   slices.Sort(arr)
来源：http://dali.cashguo.top/Article/details/gtbnctfhmi.html

Ruby: arr.sort
来源：http://dali.ppjwa.cn/Article/details/gtgmpbqxlt.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.feifeiyinyue.top/Article/details/gtqtoifzap.html

[N03] 快速排序（分治示例）
来源：http://dali.zdqjudy.top/Article/details/gttknnjlph.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.svipenyu.cn/Article/details/gtejlhzjgh.html

PHP:  // 递归实现，或用 usort
来源：http://dali.nanxinkj.top/Article/details/gttkipvkxv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.haohaochexian.top/Article/details/gthbhsjnvm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangdashe.top/Article/details/gtrbdcsiyy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sweek.top/Article/details/gtvqgapimn.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.meibo888.top/Article/details/gtsnsznnqn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.guannengcc.top/Article/details/gtszagapsc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gogol.net.cn/Article/details/gtuuydoybo.html

[N04] 斐波那契数列
来源：http://dali.chenjidiqi.icu/Article/details/gtinxcymru.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hysaishi.cn/Article/details/gtrlxmqwwy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhoulong.xyz/Article/details/gtvakoltdq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gtqnxyzwbw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gtbkzfxdon.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.birdmap.top/Article/details/gtgcvpdtvr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhengqikj.top/Article/details/gtuhehtkbx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.pycfn.com/Article/details/gticepaexd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.birdmap.top/Article/details/gtnxidfrij.html

[N05] 最大公约数
来源：http://dali.xinyue.icu/Article/details/gtcbbwytgk.html

Py:   math.gcd(a, b)
来源：http://dali.daxiang520.top/Article/details/gtzqfeyfdy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ydzc1.top/Article/details/gtrlljzzuw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenjidiqi.icu/Article/details/gtlsjajgtv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tianlin.xyz/Article/details/gtzvlgtgjj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.chenjidiqi.icu/Article/details/gtigamyfiu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jqgfzy.top/Article/details/gtifjyxbnv.html

Ruby: a.gcd(b)
来源：http://dali.sxryk.cn/Article/details/gtqbahrghx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xuetiantiany.cn/Article/details/gteucjrzbz.html

[N06] 判断回文字符串
来源：http://dali.gotoacloud.top/Article/details/gtfvrmtskt.html

Py:   s == s[::-1]
来源：http://dali.redwolf501.top/Article/details/gtkanwvaxy.html

PHP:  $s === strrev($s);
来源：http://dali.cheryme.top/Article/details/gtdhofexyn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gtumcfoppd.html

TS:   s === [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gtywzjeajx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ehwqpu.com/Article/details/gtprwzczwr.html

Go:   // 双指针从两端比较
来源：http://dali.guannengcc.top/Article/details/gtoieziyqg.html

Ruby: s == s.reverse
来源：http://dali.tian-w.cn/Article/details/gtuyfcavvj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.c1oappe.top/Article/details/gtqdalcahc.html

[N07] 两数之和（返回下标）
来源：http://dali.dashuyun.cn/Article/details/gtrbtryqug.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sweek.top/Article/details/gtsryavypa.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jlsjyb.cn/Article/details/gttntjsoht.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zdqjudy.top/Article/details/gttxzybpgc.html

TS:   // 手写 Map<string, number>
来源：http://dali.kuanghao11.cn/Article/details/gtfeamwxlv.html

Java: // 手写 HashMap
来源：http://dali.redwolf501.top/Article/details/gtafqmtmhm.html

Go:   // 手写 map[int]int
来源：http://dali.daxiang520.top/Article/details/gtknxauxvp.html

Ruby: // 手写 Hash
来源：http://dali.shzxlz.cn/Article/details/gtemkibosm.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xuanzx.com/Article/details/gtnkyvkdoz.html

[N08] 生成全排列
来源：http://dali.xuetiantiany.cn/Article/details/gtebgvetaa.html

Py:   itertools.permutations(arr)
来源：http://dali.wangdashe.top/Article/details/gtjyzddpyy.html

PHP:  // 手写递归交换
来源：http://dali.jlsjyb.cn/Article/details/gtujxuhgiw.html

JS:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gtkgoveify.html

TS:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gtotobvfwn.html

Java: // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gtshdoqoac.html

Go:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gtffqnwsrm.html

Ruby: arr.permutation.to_a
来源：http://dali.jianghu66.top/Article/details/gtvupmzbbq.html

C#:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtcwcjacgo.html

[N09] 栈与队列
来源：http://dali.jqgufenzy.top/Article/details/gtbevexjct.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.0kj1m.cn/Article/details/gtpvnhzkgm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ivvv.top/Article/details/gtkrjnmbol.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.0kj1m.cn/Article/details/gtdfgdyquo.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shuidangran.top/Article/details/gtqolsatzz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hongshengwenyu.top/Article/details/gtydtvvlwm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ppjwa.cn/Article/details/gtdtjuxjym.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nwbrower.top/Article/details/gtblomhdrm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhengqikj.top/Article/details/gtflkywnji.html

[N10] 链表节点定义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtovwulxjn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ydzc1.top/Article/details/gtnsgcjzpc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.quarkkingdee.top/Article/details/gtwqqnrtel.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.snrcjt.cn/Article/details/gtximvamed.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yueranfly.top/Article/details/gtzrwvtymx.html

Java: class Node { int v; Node next; }
来源：http://dali.svipenyu.cn/Article/details/gtjiihciua.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhiwuduotai.top/Article/details/gtthxhavis.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.pycfn.com/Article/details/gtxzlpompw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmgkmoxva.html

[N11] 二叉树中序遍历
来源：http://dali.zhixingplan.top/Article/details/gtyoyuefwt.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jianghu66.top/Article/details/gtgdcqgayl.html

PHP:  // 手写递归函数
来源：http://dali.hnxiangtu.top/Article/details/gtcvlatdmz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yanxiufei.cn/Article/details/gtzxymiiza.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.meibo888.top/Article/details/gtqtmzereq.html

Java: // 手写递归
来源：http://dali.andypj.xyz/Article/details/gtahrotqei.html

Go:   // 手写递归
来源：http://dali.chenjidiqi.icu/Article/details/gtckszqmgn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.snrcjt.cn/Article/details/gtucngurxc.html

C#:   // 手写递归
来源：http://dali.ppjwa.cn/Article/details/gtxynqevkr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtofgnuate.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shangyingyoupin.top/Article/details/gtpftylycn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yj20258.top/Article/details/gttmfagyxa.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zdqjudy.top/Article/details/gtbptojcxx.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.vqdsnc.cn/Article/details/gtjesyaqxu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpkfamkxe.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sweek.top/Article/details/gththqheei.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.nwbrower.top/Article/details/gtgyoagdaw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hammf.cn/Article/details/gtmpsywdaf.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtheycvseg.html

O. 并发与异步
来源：http://dali.zdqjudy.top/Article/details/gtjavyplcu.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtqkjkhmlq.html

[O01] 启动一个线程
来源：http://dali.ivvv.top/Article/details/gtjupqruyo.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.feifeiyinyue.top/Article/details/gtmzjtibiv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.dianchejie.cn/Article/details/gttalafnms.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj20258.top/Article/details/gtxgqpkgao.html

TS:   // 同 JS
来源：http://dali.aibaodan.cn/Article/details/gtwywvixri.html

Java: new Thread(() -> f()).start()
来源：http://dali.sysykeji.top/Article/details/gtjgjhjczh.html

Go:   go f()
来源：http://dali.daria6918.cn/Article/details/gtjqulfybi.html

Ruby: Thread.new { f }
来源：http://dali.9152youxi.cn/Article/details/gtlgantmpv.html

C#:   Task.Run(() => F());
来源：http://dali.yj20258888.top/Article/details/gtjnablazr.html

[O02] 使用线程池
来源：http://dali.mhx1999.top/Article/details/gtsmbvbizs.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jyoumei.cn/Article/details/gtchjishub.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jiagoushi.top/Article/details/gtmoarhdcs.html

JS:   // worker_threads 线程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqipbubci.html

TS:   // worker_threads 线程池
来源：http://dali.vqdsnc.cn/Article/details/gtputeluci.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.316326.xyz/Article/details/gtksmotloc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yueranfly.top/Article/details/gtnygbuzhw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yangfankeji.com/Article/details/gtgblfdugl.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jlsjyb.cn/Article/details/gtfipqsiyn.html

[O03] 加锁保护共享数据
来源：http://dali.hammf.cn/Article/details/gtsbtelduq.html

Py:   with lock: shared += 1
来源：http://dali.hywenlv.cn/Article/details/gtdysfnzok.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.redwolf501.top/Article/details/gtgbvfoptn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gaohongyu789.top/Article/details/gtyztekufv.html

TS:   // 同 JS
来源：http://dali.tanke756.top/Article/details/gtygwlumvg.html

Java: synchronized (this) { shared++; }
来源：http://dali.jqgfzy.top/Article/details/gtwrnopksk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.iojbl.cn/Article/details/gtrdyfgaky.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.iojbl.cn/Article/details/gththkkmjy.html

C#:   lock (gate) { shared++; }
来源：http://dali.ppjwa.cn/Article/details/gtwwmqmpwg.html

[O04] 定义异步函数并等待
来源：http://dali.9152youxi.cn/Article/details/gtkgxpstdf.html

Py:   async def f():⏎    await g()
来源：http://dali.dianchejie.cn/Article/details/gtzmgnmbws.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.pycfn.com/Article/details/gtceyggwfr.html

JS:   async function f() { await g(); }
来源：http://dali.daria6918.cn/Article/details/gtgeabzbrm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xuanzx.com/Article/details/gtxyvzlamk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.c1oappe.top/Article/details/gtoxwkmcba.html


<!-- 参考信息 -->