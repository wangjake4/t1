代发 wailian999

Go:   encoding/gob
来源：http://dali.daria6918.cn/Article/details/gtjlaxpyro.html

Ruby: Marshal.dump(obj)
来源：http://dali.zycfv.cn/Article/details/gtuysuqccs.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yuanzhike.top/Article/details/gtisulgsmi.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtngbenuht.html

L. 网络请求
来源：http://dali.yongpay.top/Article/details/gtpfejbazv.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtympoeclv.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gtqxjqkbml.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.fengsongda.top/Article/details/gtnaoyltsz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.tianlin.xyz/Article/details/gtbykmfcxz.html

JS:   await fetch(url)
来源：http://dali.chenzaomai.com/Article/details/gtjalmhzvm.html

TS:   await fetch(url)
来源：http://dali.gotoacloud.top/Article/details/gtjqvoexfq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.redwolf501.top/Article/details/gtblvfrygh.html

Go:   resp, err := http.Get(url)
来源：http://dali.yj202588.top/Article/details/gtuvxkfrpb.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.kuanghao11.cn/Article/details/gtbsdbmsmt.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ydzc1.top/Article/details/gtyodyqzbr.html

[L02] 发送 POST JSON
来源：http://dali.fzhhl.top/Article/details/gtifqdycmk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gogol.net.cn/Article/details/gtivrdysxd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.chenzaomai.com/Article/details/gtyqzfkjoz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dianchejie.cn/Article/details/gtrnvwhbtw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.havefunace.top/Article/details/gtusagzelz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhiwuduotai.top/Article/details/gtcqihfpaz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.birdmap.top/Article/details/gtpbjewngb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yj20258888.top/Article/details/gtptjuoabj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.birdmap.top/Article/details/gtnfgafzuj.html

[L03] 设置自定义请求头
来源：http://dali.c1oappe.top/Article/details/gtpsiztyxa.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqurlimlv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.haohaochexian.top/Article/details/gtttlhqyie.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gzhubu.top/Article/details/gtfdoqgfav.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yongpay.top/Article/details/gtsqthgatj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hywenlv.cn/Article/details/gtwhtovnsv.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yangfankeji.com/Article/details/gticutshus.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.iojbl.cn/Article/details/gtwbyuueyg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cashguo.top/Article/details/gtzucfrfsq.html

[L04] 设置超时
来源：http://dali.cheryme.top/Article/details/gtkiiirchg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtglcoyqim.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.vqdsnc.cn/Article/details/gtszgbkhqh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pengpengdd.cyou/Article/details/gtedlqnrem.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yanxiufei.cn/Article/details/gtmmsmjsiw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.haohaochexian.top/Article/details/gtohewdzfw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.dianchejie.cn/Article/details/gtamgqyoyb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yueranfly.top/Article/details/gtdvdkopop.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yueranfly.top/Article/details/gtrbboiqwj.html

[L05] 上传文件（multipart）
来源：http://dali.snrcjt.cn/Article/details/gtproexuqb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.snrcjt.cn/Article/details/gtxtphhhal.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.wangshuangyany.cn/Article/details/gtxdglgqxr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.pengpengdd.cyou/Article/details/gtupjxnlhl.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shuidangran.top/Article/details/gtabscmxnz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.andypj.xyz/Article/details/gtasxmnqxl.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jlsjyb.cn/Article/details/gtxwpnbyzh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinqigfzy.top/Article/details/gtbepdglja.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.fzhhl.top/Article/details/gthabeiwdo.html

[L06] 解析响应为 JSON
来源：http://dali.sysykeji.top/Article/details/gtaxqlkdmc.html

Py:   resp.json()
来源：http://dali.dianchejie.cn/Article/details/gtlgglnlpf.html

PHP:  json_decode($body, true);
来源：http://dali.kuanghao11.cn/Article/details/gtjginkdfq.html

JS:   await resp.json()
来源：http://dali.ybcxt.top/Article/details/gtrcuqurdh.html

TS:   await resp.json()
来源：http://dali.chenjidiqi.icu/Article/details/gtievfirop.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.bjfxy.top/Article/details/gthjlymktq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yonumen.top/Article/details/gtknfqmdwh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xylfe.cn/Article/details/gtookwvbpk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.tianlin.xyz/Article/details/gtuzpgkqif.html

[L07] 处理 HTTP 状态码
来源：http://dali.aibaodan.cn/Article/details/gtqjocerre.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.wangdashe.top/Article/details/gttwqrmdov.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xinyue.icu/Article/details/gthpbfbmno.html

JS:   resp.ok;  resp.status
来源：http://dali.mhx1999.top/Article/details/gtdqokqpll.html

TS:   resp.ok;  resp.status
来源：http://dali.jiagoushi.top/Article/details/gtiakrakto.html

Java: resp.statusCode()
来源：http://dali.gotoacloud.top/Article/details/gtzavdcqpe.html

Go:   resp.StatusCode
来源：http://dali.dianchejie.cn/Article/details/gtslqmvuko.html

Ruby: resp.code.to_i
来源：http://dali.yj20258888.top/Article/details/gtjksypyna.html

C#:   (int)resp.StatusCode
来源：http://dali.jinqigfzy.top/Article/details/gtplgphrrr.html

[L08] 并发请求多个地址
来源：http://dali.nanxuanxn.top/Article/details/gtahuvqnct.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.0kj1m.cn/Article/details/gtwspqvkdr.html

PHP:  curl_multi_init() 系列
来源：http://dali.fzhhl.top/Article/details/gtypndqkmk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dashuyun.cn/Article/details/gtgpqqewvd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzwqmyycm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gaohongyu789.top/Article/details/gttdgzvdjj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gtalrhgqrk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.wangdashe.top/Article/details/gteydumsow.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.havefunace.top/Article/details/gtiwsycjja.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtdaoovtkf.html

M. 命令行 / 进程 / 环境
来源：http://dali.birdmap.top/Article/details/gtmzwhwxoq.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtctnrwraw.html

[M01] 读取命令行参数
来源：http://dali.shuidangran.top/Article/details/gtrqpbtyes.html

Py:   sys.argv[1:]
来源：http://dali.daria6918.cn/Article/details/gtemlzrgmo.html

PHP:  $argv;  $argc;
来源：http://dali.hfpthk.cn/Article/details/gtupnzswtx.html

JS:   process.argv.slice(2)
来源：http://dali.sweek.top/Article/details/gtfeawwghs.html

TS:   process.argv.slice(2)
来源：http://dali.shzxlz.cn/Article/details/gtixyiaiez.html

Java: args 数组（main 方法参数）
来源：http://dali.birdmap.top/Article/details/gtgagltqvq.html

Go:   os.Args[1:]
来源：http://dali.cheryme.top/Article/details/gtlyctufjd.html

Ruby: ARGV
来源：http://dali.smart0.xyz/Article/details/gtogfacnob.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttcqypqdl.html

[M02] 读取环境变量
来源：http://dali.quarkkingdee.top/Article/details/gthmieatty.html

Py:   os.environ.get("HOME")
来源：http://dali.jiagoushi.top/Article/details/gtoetvehoi.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.svipenyu.cn/Article/details/gtrsxxxydc.html

JS:   process.env.HOME
来源：http://dali.hammf.cn/Article/details/gtutvjdpfl.html

TS:   process.env.HOME
来源：http://dali.havefunace.top/Article/details/gtomeqakjr.html

Java: System.getenv("HOME")
来源：http://dali.yuanzhike.top/Article/details/gtexolsqph.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ydzc1.top/Article/details/gtxsnowsdz.html

Ruby: ENV["HOME"]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqcnvuxai.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtezbkjvum.html

[M03] 执行外部命令
来源：http://dali.quarkkingdee.top/Article/details/gtkcbgrxcp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xuetiantiany.cn/Article/details/gtxrwcciky.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.9152youxi.cn/Article/details/gtntuupnax.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.fzhhl.top/Article/details/gtmhowgzsi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.vqdsnc.cn/Article/details/gtaypovtsr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cheryme.top/Article/details/gtsyuyszyi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cheryme.top/Article/details/gtxqvgwrez.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.pycfn.com/Article/details/gtlcvooqls.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ehwqpu.com/Article/details/gtmbfidsmq.html

[M04] 获取当前工作目录
来源：http://dali.nanxinkj.top/Article/details/gtrpadhzqt.html

Py:   os.getcwd()
来源：http://dali.sweek.top/Article/details/gtnstockzp.html

PHP:  getcwd();
来源：http://dali.zhengqikj.top/Article/details/gtxnpveqtx.html

JS:   process.cwd()
来源：http://dali.smart0.xyz/Article/details/gtutgklmmk.html

TS:   process.cwd()
来源：http://dali.yanxiufei.cn/Article/details/gtyacsgsrm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xinyue.icu/Article/details/gtjmuaukdt.html

Go:   os.Getwd()
来源：http://dali.tanke756.top/Article/details/gtlntmwyva.html

Ruby: Dir.pwd
来源：http://dali.tian-w.cn/Article/details/gtldbxsfiv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.vqdsnc.cn/Article/details/gtxwqudvku.html

[M05] 设置退出码
来源：http://dali.nanxinkj.top/Article/details/gtiuclrtdx.html

Py:   sys.exit(1)
来源：http://dali.havefunace.top/Article/details/gtkndasgwm.html

PHP:  exit(1);
来源：http://dali.hnxiangtu.top/Article/details/gtjoznvofi.html

JS:   process.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gtcordkhib.html

TS:   process.exit(1)
来源：http://dali.xylfe.cn/Article/details/gtplyndghn.html

Java: System.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gtwhecislj.html

Go:   os.Exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtryriphob.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gtzbcyfljv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hysaishi.cn/Article/details/gtlubulllp.html

[M06] 向标准错误输出
来源：http://dali.sweek.top/Article/details/gtzrhsvhmo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmdxnbilc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.tianlin.xyz/Article/details/gtkildbfxy.html

JS:   console.error("err")
来源：http://dali.havefunace.top/Article/details/gtgxuvovko.html

TS:   console.error("err")
来源：http://dali.c1oappe.top/Article/details/gtdotmchkc.html

Java: System.err.println("err")
来源：http://dali.pengpengdd.cyou/Article/details/gthhfuamoh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yuxming.cn/Article/details/gtfsgxizam.html

Ruby: warn "err"
来源：http://dali.gzhubu.top/Article/details/gtfwzabmea.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.wangshuangyany.cn/Article/details/gtedgnbzms.html

[M07] 判断是否为主入口
来源：http://dali.smart0.xyz/Article/details/gtucwjjwdj.html

Py:   if __name__ == "__main__":
来源：http://dali.yj20258.top/Article/details/gtwcmactdc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.aibaodan.cn/Article/details/gtiueoeyol.html

JS:   require.main === module
来源：http://dali.zhongyouzk.top/Article/details/gtqsgfoheh.html

TS:   require.main === module
来源：http://dali.0kj1m.cn/Article/details/gtfegcisjg.html

Java: public static void main(String[] args)
来源：http://dali.chenzaomai.com/Article/details/gtwbetjxfq.html

Go:   func main()
来源：http://dali.zycfv.cn/Article/details/gtwkofnxml.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhiwuduotai.top/Article/details/gtktljwvkc.html

C#:   static void Main(string[] args)
来源：http://dali.0kj1m.cn/Article/details/gtmpxjpnab.html

[M08] 获取系统与运行时信息
来源：http://dali.sysykeji.top/Article/details/gtmparnilh.html

Py:   platform.system();  platform.python_version()
来源：http://dali.haohaochexian.top/Article/details/gtnjizlpgl.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jqgfzy.top/Article/details/gtjtmjnecu.html

JS:   process.platform;  process.version
来源：http://dali.shuidangran.top/Article/details/gtufnelxrq.html

TS:   process.platform;  process.version
来源：http://dali.jianghu66.top/Article/details/gtjxglubcs.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hammf.cn/Article/details/gtpryhxwrk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.dianchejie.cn/Article/details/gteafhhfgf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yongpay.top/Article/details/gtopzbvhij.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gogol.net.cn/Article/details/gtpuszpyab.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtivrrjbja.html

N. 数据结构与算法
来源：http://dali.aibaodan.cn/Article/details/gtibgekqoy.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtjfvcjmiu.html

[N01] 二分查找（有序数组）
来源：http://dali.cheryme.top/Article/details/gterpupats.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtixszzqjo.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shangyingyoupin.top/Article/details/gtsfpiikkp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.redwolf501.top/Article/details/gtefshzawh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daxiang520.top/Article/details/gtijflraog.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gtfwqnwhra.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gttznqmkwd.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ybcxt.top/Article/details/gtbgbpamrm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gtscqxvnqu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jiagoushi.top/Article/details/gtrjomedjx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.smart0.xyz/Article/details/gtrjruuqgw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.guannengcc.top/Article/details/gtfnfdrecx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jiagoushi.top/Article/details/gtpkdfdbcw.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tanke756.top/Article/details/gtziytvqra.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zycfv.cn/Article/details/gteatebszi.html

Go:   slices.Sort(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtsogygfjh.html

Ruby: arr.sort
来源：http://dali.shuidangran.top/Article/details/gtoxepnnmj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jlsjyb.cn/Article/details/gtpiuvxcix.html

[N03] 快速排序（分治示例）
来源：http://dali.smart0.xyz/Article/details/gthccgdxsx.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.aizwys.cn/Article/details/gtdofoidqy.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yj20258888.top/Article/details/gtftgmrsqi.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tianlin.xyz/Article/details/gtfzozcmlo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.svipenyu.cn/Article/details/gtbkcohdhe.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.fengsongda.top/Article/details/gtsvwkfgre.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcydsxesl.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.wangdashe.top/Article/details/gtjtblkupd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.svipenyu.cn/Article/details/gtyiteeqfo.html

[N04] 斐波那契数列
来源：http://dali.jinqigfzy.top/Article/details/gttbiymntt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.havefunace.top/Article/details/gtseqqmltq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.9152youxi.cn/Article/details/gtmpnhdrdr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gtricxshzu.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gtkpsrlaji.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.316326.xyz/Article/details/gtjgiqumwy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.svipenyu.cn/Article/details/gtuggnucpg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ppjwa.cn/Article/details/gtrxutekid.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.fzhhl.top/Article/details/gtoyzljujb.html

[N05] 最大公约数
来源：http://dali.shuidangran.top/Article/details/gtexaopkpm.html

Py:   math.gcd(a, b)
来源：http://dali.hnqzz.top/Article/details/gtqgddrrwu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhiwuduotai.top/Article/details/gtwtsgqsun.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gaohongyu789.top/Article/details/gttivdixte.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hfpthk.cn/Article/details/gtlfrdivvm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.gogol.net.cn/Article/details/gtlixtmhwr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yuxming.cn/Article/details/gtpzuseerb.html

Ruby: a.gcd(b)
来源：http://dali.ybcxt.top/Article/details/gtbzimrbln.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jianghu66.top/Article/details/gtjwrrpfns.html

[N06] 判断回文字符串
来源：http://dali.yvedp.cn/Article/details/gthawprswg.html

Py:   s == s[::-1]
来源：http://dali.0kj1m.cn/Article/details/gtbnalamhp.html

PHP:  $s === strrev($s);
来源：http://dali.andypj.xyz/Article/details/gtlwjxsciz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gtkavyoyop.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gtkpuejprb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yuxming.cn/Article/details/gtcgesxpim.html

Go:   // 双指针从两端比较
来源：http://dali.guannengcc.top/Article/details/gtsparmtiz.html

Ruby: s == s.reverse
来源：http://dali.tanke756.top/Article/details/gtllavtqnk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.feifeiyinyue.top/Article/details/gtagzqwnkt.html

[N07] 两数之和（返回下标）
来源：http://dali.cdnleiting.top/Article/details/gttzorqhzp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xuetiantiany.cn/Article/details/gtdnppmiow.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinqigufen.top/Article/details/gthzfemrth.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.snrcjt.cn/Article/details/gtqemzcquo.html

TS:   // 手写 Map<string, number>
来源：http://dali.nwbrower.top/Article/details/gtqvzeeegv.html

Java: // 手写 HashMap
来源：http://dali.xuetiantiany.cn/Article/details/gtreqermta.html

Go:   // 手写 map[int]int
来源：http://dali.sweek.top/Article/details/gtqsuqhtsn.html

Ruby: // 手写 Hash
来源：http://dali.9152youxi.cn/Article/details/gtvgvqhvyg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.dashuyun.cn/Article/details/gtnogczsni.html

[N08] 生成全排列
来源：http://dali.guannengcc.top/Article/details/gtpnhshutx.html

Py:   itertools.permutations(arr)
来源：http://dali.sweek.top/Article/details/gtpgcvpywa.html

PHP:  // 手写递归交换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiynxadnq.html

JS:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gtsiahgawu.html

TS:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gtisdgwdqy.html

Java: // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gtboyeueqp.html

Go:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gteraevkxp.html

Ruby: arr.permutation.to_a
来源：http://dali.meibo888.top/Article/details/gtlfrymdbp.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gtixidfidw.html

[N09] 栈与队列
来源：http://dali.chenjidiqi.icu/Article/details/gtblhssxbv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.fengsongda.top/Article/details/gttxslqwoy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hnxiangtu.top/Article/details/gtkeuyrnim.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yj20258.top/Article/details/gtuwkwjdyz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhixingplan.top/Article/details/gtzfwniqhn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zycfv.cn/Article/details/gtgdvgvyxw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtltswxhxk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ppjwa.cn/Article/details/gtxakoojne.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxtgrvqbv.html

[N10] 链表节点定义
来源：http://dali.dianchejie.cn/Article/details/gtrinhmtmn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxvsbmthr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.316326.xyz/Article/details/gthzauuerq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzxvqkkvz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jqgfzy.top/Article/details/gtncqhxgms.html

Java: class Node { int v; Node next; }
来源：http://dali.haohaochexian.top/Article/details/gtkwefupgi.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hongshengwenyu.top/Article/details/gtwwtydxhc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jiagoushi.top/Article/details/gtvidehaqb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gtmrbrmxsi.html

[N11] 二叉树中序遍历
来源：http://dali.yuanzhike.top/Article/details/gthrhlqova.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cheryme.top/Article/details/gtymgtxxdq.html

PHP:  // 手写递归函数
来源：http://dali.jyoumei.cn/Article/details/gtmxsfcano.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cucudq.cn/Article/details/gtzhufatxv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigufen.top/Article/details/gtwpirwpss.html

Java: // 手写递归
来源：http://dali.9152youxi.cn/Article/details/gtjzovvmqx.html

Go:   // 手写递归
来源：http://dali.ehwqpu.com/Article/details/gtqejejrcv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.tianlin.xyz/Article/details/gtbuiaphdt.html

C#:   // 手写递归
来源：http://dali.zhengqikj.top/Article/details/gtrqdfszir.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.nanxuanxn.top/Article/details/gtyqcgfxll.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shzxlz.cn/Article/details/gtkazwxdgt.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yongpay.top/Article/details/gtitlkgqty.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yangfankeji.com/Article/details/gtwugrrhbx.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yongpay.top/Article/details/gtdustnhko.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinghuilouyu.cn/Article/details/gtijsbjsrr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zycfv.cn/Article/details/gtptsvyvmt.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cashguo.top/Article/details/gtatqlagxa.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fengsongda.top/Article/details/gtlkmxbech.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtmwvvtxfa.html

O. 并发与异步
来源：http://dali.jlsjyb.cn/Article/details/gtijxdpmew.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtaoptrybe.html

[O01] 启动一个线程
来源：http://dali.nwbrower.top/Article/details/gthhsnwgfz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.feifeiyinyue.top/Article/details/gthroufkst.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sxryk.cn/Article/details/gtxjpvfqke.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shanyushiyangtech.top/Article/details/gtsrorrjtp.html

TS:   // 同 JS
来源：http://dali.nanxuanxn.top/Article/details/gtqeqaedmq.html

Java: new Thread(() -> f()).start()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyceaqzcw.html

Go:   go f()
来源：http://dali.yj202588.top/Article/details/gtgjnnlwlo.html

Ruby: Thread.new { f }
来源：http://dali.chenjidiqi.icu/Article/details/gtsvtwtwjg.html

C#:   Task.Run(() => F());
来源：http://dali.daria6918.cn/Article/details/gtueyrtgmw.html

[O02] 使用线程池
来源：http://dali.iojbl.cn/Article/details/gttksizxuy.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.nwbrower.top/Article/details/gtbglmweno.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhengqikj.top/Article/details/gtwwyxfowv.html

JS:   // worker_threads 线程池
来源：http://dali.yj202588.top/Article/details/gtsoiwyqqd.html

TS:   // worker_threads 线程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcphuvsui.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttpnfvokm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.9152youxi.cn/Article/details/gtdwzmzuxo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhengqikj.top/Article/details/gtbfzyfbjp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yanxiufei.cn/Article/details/gtjdimdnga.html

[O03] 加锁保护共享数据
来源：http://dali.snrcjt.cn/Article/details/gtexeqotgf.html

Py:   with lock: shared += 1
来源：http://dali.zdqjudy.top/Article/details/gtstrodfwq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shzxlz.cn/Article/details/gtkdgmxdid.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.tian-w.cn/Article/details/gtzkewoamj.html

TS:   // 同 JS
来源：http://dali.yj20258888.top/Article/details/gtjbfwgxfh.html

Java: synchronized (this) { shared++; }
来源：http://dali.gogol.net.cn/Article/details/gtnyrxcdkn.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yj202588.top/Article/details/gtzjkbwhjf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.smart0.xyz/Article/details/gtxgvlpofp.html

C#:   lock (gate) { shared++; }
来源：http://dali.iojbl.cn/Article/details/gtgmsmhvgh.html

[O04] 定义异步函数并等待
来源：http://dali.zhixingplan.top/Article/details/gtrzvdemjp.html

Py:   async def f():⏎    await g()
来源：http://dali.ppjwa.cn/Article/details/gtdyerzxqh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cashguo.top/Article/details/gtrganllpi.html

JS:   async function f() { await g(); }
来源：http://dali.yj20258.top/Article/details/gtvsfgnnat.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.316326.xyz/Article/details/gtmnfudcte.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.c1oappe.top/Article/details/gtqvakoyiv.html


<!-- 参考信息 -->