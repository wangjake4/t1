代发 wailian999

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.pengpengdd.cyou/Article/details/gtajlndqso.html

JS:   await fetch(url)
来源：http://dali.jlsjyb.cn/Article/details/gtliurtink.html

TS:   await fetch(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthjcaafii.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hywenlv.cn/Article/details/gtrzxfojod.html

Go:   resp, err := http.Get(url)
来源：http://dali.cdnleiting.top/Article/details/gtuycsdvon.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hnxiangtu.top/Article/details/gtiohpobtr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.daxiang520.top/Article/details/gtjrggrfxz.html

[L02] 发送 POST JSON
来源：http://dali.wangshuangyany.cn/Article/details/gtjxtovsvs.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.tanke756.top/Article/details/gttmcdpeme.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.fzhhl.top/Article/details/gthztnslls.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xziqi.cn/Article/details/gtwdtorgta.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangshuangyany.cn/Article/details/gtoqxpistd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yj20258.top/Article/details/gtdthghjmi.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xylfe.cn/Article/details/gtnuytdwuw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.0kj1m.cn/Article/details/gtgedobfii.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.feifeiyinyue.top/Article/details/gtjbjkfgoq.html

[L03] 设置自定义请求头
来源：http://dali.snrcjt.cn/Article/details/gtgvquwjvm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shangyingyoupin.top/Article/details/gtmbhzjyvn.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yvedp.cn/Article/details/gtmovokvfb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shangyingyoupin.top/Article/details/gtvniprchc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tian-w.cn/Article/details/gthkqffwwq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cheryme.top/Article/details/gtijxdfjft.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdvnttqyx.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cashguo.top/Article/details/gtlnbjdoom.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gotoacloud.top/Article/details/gtcthnubbi.html

[L04] 设置超时
来源：http://dali.ppjwa.cn/Article/details/gtaeqbecwh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtblailrbf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yonumen.top/Article/details/gtdowueand.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnqzz.top/Article/details/gtngustkkb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pengpengdd.cyou/Article/details/gtsnhdjgok.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jyoumei.cn/Article/details/gtnixygoib.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hywenlv.cn/Article/details/gttwxycuri.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj20258888.top/Article/details/gtfyfrrmpd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.tian-w.cn/Article/details/gtgqnncbff.html

[L05] 上传文件（multipart）
来源：http://dali.shanyushiyangtech.top/Article/details/gtjrbjslum.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.pengpengdd.cyou/Article/details/gtjclujyce.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xylfe.cn/Article/details/gtebpmctlq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.daria6918.cn/Article/details/gtpxycfhaw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gogol.net.cn/Article/details/gtsdpggdka.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.c1oappe.top/Article/details/gtzgjydgki.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sxryk.cn/Article/details/gtwznbmqgp.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinqigufen.top/Article/details/gtfuqzhjrh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtyycnrvny.html

[L06] 解析响应为 JSON
来源：http://dali.haohaochexian.top/Article/details/gtjwwmcdxp.html

Py:   resp.json()
来源：http://dali.snrcjt.cn/Article/details/gtlvgxatqo.html

PHP:  json_decode($body, true);
来源：http://dali.yvedp.cn/Article/details/gtesrqwmka.html

JS:   await resp.json()
来源：http://dali.daria6918.cn/Article/details/gtigdazmhf.html

TS:   await resp.json()
来源：http://dali.andypj.xyz/Article/details/gtgwshjwww.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.daxiang520.top/Article/details/gtksnkzdcq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.guowangkeji.top/Article/details/gtgwcklyjx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yuxming.cn/Article/details/gtycmysktx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hammf.cn/Article/details/gtnkgorsls.html

[L07] 处理 HTTP 状态码
来源：http://dali.316326.xyz/Article/details/gtdqgdjgoa.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sweek.top/Article/details/gttsvamser.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jqgfzy.top/Article/details/gtclwcnjdo.html

JS:   resp.ok;  resp.status
来源：http://dali.fzhhl.top/Article/details/gtapctllzt.html

TS:   resp.ok;  resp.status
来源：http://dali.jyoumei.cn/Article/details/gtazowdxfv.html

Java: resp.statusCode()
来源：http://dali.nwbrower.top/Article/details/gtignlhzow.html

Go:   resp.StatusCode
来源：http://dali.gogol.net.cn/Article/details/gtxutuigty.html

Ruby: resp.code.to_i
来源：http://dali.mhx1999.top/Article/details/gtoaovphsq.html

C#:   (int)resp.StatusCode
来源：http://dali.jianghu66.top/Article/details/gtskdcblfj.html

[L08] 并发请求多个地址
来源：http://dali.jqgfzy.top/Article/details/gtvztveaft.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.guannengcc.top/Article/details/gtsaowgfzw.html

PHP:  curl_multi_init() 系列
来源：http://dali.ehwqpu.com/Article/details/gtshuzimnb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.9152youxi.cn/Article/details/gtjbaezmkv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yanxiufei.cn/Article/details/gtbrfuwsax.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.wangdashe.top/Article/details/gtgzwtuffu.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hfpthk.cn/Article/details/gtzwjylcua.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cashguo.top/Article/details/gtgmvuiyct.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tian-w.cn/Article/details/gthbzmwnet.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtmxqnnyow.html

M. 命令行 / 进程 / 环境
来源：http://dali.jyoumei.cn/Article/details/gtmzqbsprq.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtimwxtltn.html

[M01] 读取命令行参数
来源：http://dali.yj20258888.top/Article/details/gtzaaintad.html

Py:   sys.argv[1:]
来源：http://dali.cucudq.cn/Article/details/gtijktuyan.html

PHP:  $argv;  $argc;
来源：http://dali.ydzc1.top/Article/details/gtodiajnfy.html

JS:   process.argv.slice(2)
来源：http://dali.tanke756.top/Article/details/gtkfkkvoea.html

TS:   process.argv.slice(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtaakcottc.html

Java: args 数组（main 方法参数）
来源：http://dali.yongpay.top/Article/details/gtxraooigr.html

Go:   os.Args[1:]
来源：http://dali.gogol.net.cn/Article/details/gtramqiqdn.html

Ruby: ARGV
来源：http://dali.316326.xyz/Article/details/gtkkurcdiq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sufxvd.cn/Article/details/gtozlryjlc.html

[M02] 读取环境变量
来源：http://dali.gotoacloud.top/Article/details/gtwtjshncj.html

Py:   os.environ.get("HOME")
来源：http://dali.sysykeji.top/Article/details/gtqdosewfm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xylfe.cn/Article/details/gtxusyewwo.html

JS:   process.env.HOME
来源：http://dali.cdnleiting.top/Article/details/gtnawoevxm.html

TS:   process.env.HOME
来源：http://dali.yangfankeji.com/Article/details/gticvaflwa.html

Java: System.getenv("HOME")
来源：http://dali.cheryme.top/Article/details/gtgvzmfcsk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cheryme.top/Article/details/gtohxzsyzh.html

Ruby: ENV["HOME"]
来源：http://dali.aizwys.cn/Article/details/gtlabakhkk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cqqwz.cn/Article/details/gtafughlbi.html

[M03] 执行外部命令
来源：http://dali.yueranfly.top/Article/details/gtnyrgjugs.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tianlin.xyz/Article/details/gtcwfrmbir.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.mhx1999.top/Article/details/gtbeualsrk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangdashe.top/Article/details/gtstovwfld.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.316326.xyz/Article/details/gteeslowii.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.dianchejie.cn/Article/details/gtpmekrnzy.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.dashuyun.cn/Article/details/gtmghdrvhs.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jyoumei.cn/Article/details/gtracyxdss.html

C#:   Process.Start("ls", "-l");
来源：http://dali.andypj.xyz/Article/details/gtcvjlzhsj.html

[M04] 获取当前工作目录
来源：http://dali.aizwys.cn/Article/details/gtefrwonff.html

Py:   os.getcwd()
来源：http://dali.zhongyouzk.top/Article/details/gtatjmfkzg.html

PHP:  getcwd();
来源：http://dali.cashguo.top/Article/details/gtmahgnxtu.html

JS:   process.cwd()
来源：http://dali.cheryme.top/Article/details/gtlwevncjs.html

TS:   process.cwd()
来源：http://dali.hnxiangtu.top/Article/details/gtypkukezy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sxryk.cn/Article/details/gtxuiitjiu.html

Go:   os.Getwd()
来源：http://dali.nanxinkj.top/Article/details/gtaivbwgoj.html

Ruby: Dir.pwd
来源：http://dali.quarkkingdee.top/Article/details/gtieytlazp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xylfe.cn/Article/details/gtrrbmxvas.html

[M05] 设置退出码
来源：http://dali.aizwys.cn/Article/details/gtadekusoi.html

Py:   sys.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gtncpjxmuh.html

PHP:  exit(1);
来源：http://dali.dashuyun.cn/Article/details/gtvkrvnxqe.html

JS:   process.exit(1)
来源：http://dali.hammf.cn/Article/details/gtwszhetqd.html

TS:   process.exit(1)
来源：http://dali.jianghu66.top/Article/details/gtucaaxdho.html

Java: System.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gtmazwwhjk.html

Go:   os.Exit(1)
来源：http://dali.xinyue.icu/Article/details/gtrfwibqan.html

Ruby: exit 1
来源：http://dali.zycfv.cn/Article/details/gtilvrkufo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hongshengwenyu.top/Article/details/gtlymorrzd.html

[M06] 向标准错误输出
来源：http://dali.wangdashe.top/Article/details/gtpvculimb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.316326.xyz/Article/details/gtdukaxevr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yj20258.top/Article/details/gtjdotkene.html

JS:   console.error("err")
来源：http://dali.zhongyouzk.top/Article/details/gtnvkpywbe.html

TS:   console.error("err")
来源：http://dali.gzhubu.top/Article/details/gtubgiwwkr.html

Java: System.err.println("err")
来源：http://dali.ehwqpu.com/Article/details/gtjfqazfqr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjpjnjyqg.html

Ruby: warn "err"
来源：http://dali.bjfxy.top/Article/details/gthrfqpqer.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cucudq.cn/Article/details/gtwecgmyzq.html

[M07] 判断是否为主入口
来源：http://dali.sweek.top/Article/details/gtahsnmpta.html

Py:   if __name__ == "__main__":
来源：http://dali.nanxinkj.top/Article/details/gtqlzfybrp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xylfe.cn/Article/details/gttmikurbl.html

JS:   require.main === module
来源：http://dali.snrcjt.cn/Article/details/gtuybyfjyh.html

TS:   require.main === module
来源：http://dali.bjfxy.top/Article/details/gtivotmkef.html

Java: public static void main(String[] args)
来源：http://dali.iojbl.cn/Article/details/gtnkalfafu.html

Go:   func main()
来源：http://dali.hywenlv.cn/Article/details/gtlbnrbngg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ybcxt.top/Article/details/gtxnbgywjo.html

C#:   static void Main(string[] args)
来源：http://dali.fzhhl.top/Article/details/gtdfxgnaqq.html

[M08] 获取系统与运行时信息
来源：http://dali.cashguo.top/Article/details/gtflufbriw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jyoumei.cn/Article/details/gtrracsyzk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ybcxt.top/Article/details/gtamfhawhi.html

JS:   process.platform;  process.version
来源：http://dali.xuanzx.com/Article/details/gtbspghrrb.html

TS:   process.platform;  process.version
来源：http://dali.9152youxi.cn/Article/details/gtnadgjgob.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yuxming.cn/Article/details/gtfgievpfy.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.0kj1m.cn/Article/details/gtvegjonfr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhongyouzk.top/Article/details/gtcsadpyse.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.guannengcc.top/Article/details/gttipstsfs.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtgpfgsche.html

N. 数据结构与算法
来源：http://dali.tian-w.cn/Article/details/gtnfbsghkr.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gthrmzrywn.html

[N01] 二分查找（有序数组）
来源：http://dali.jinqigufen.top/Article/details/gtyrurslnb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtdasvevkc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxkmcxkca.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ppjwa.cn/Article/details/gtcqibgnak.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dianchejie.cn/Article/details/gtqzwgczyo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gtpccklesp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gtrsdkbsfc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.chenlongwang.top/Article/details/gtlmkzdfwb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtilwcoiju.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.pengpengdd.cyou/Article/details/gtpkefhhdi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gogol.net.cn/Article/details/gtxuhkdloz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.tianlin.xyz/Article/details/gtrbolwujo.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigufen.top/Article/details/gtljbvtlgb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hywenlv.cn/Article/details/gtpdjyytjp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jiagoushi.top/Article/details/gtndblecub.html

Go:   slices.Sort(arr)
来源：http://dali.sysykeji.top/Article/details/gtfwpddtxr.html

Ruby: arr.sort
来源：http://dali.ydzc1.top/Article/details/gtdfrbmlga.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jiagoushi.top/Article/details/gtnjuzncpf.html

[N03] 快速排序（分治示例）
来源：http://dali.jinqigufen.top/Article/details/gtpbtrktcy.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shangyingyoupin.top/Article/details/gttnvjbccg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.316326.xyz/Article/details/gtasrhkagp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.316326.xyz/Article/details/gtqobdueya.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.feifeiyinyue.top/Article/details/gtndffoyjo.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.havefunace.top/Article/details/gttebbhsxv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.wangshuangyany.cn/Article/details/gtfmucexwr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hywenlv.cn/Article/details/gtxdslnfoo.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ehwqpu.com/Article/details/gtcbmqwpty.html

[N04] 斐波那契数列
来源：http://dali.yongpay.top/Article/details/gtngshygka.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.guowangkeji.top/Article/details/gtsdpvoizr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj202588.top/Article/details/gtnyhxgisz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yangfankeji.com/Article/details/gthczgvuwx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gthqsychcm.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hnxiangtu.top/Article/details/gtpxpnekmg.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cashguo.top/Article/details/gtunzkloux.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.bjfxy.top/Article/details/gtbqbzkcrw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtadovumct.html

[N05] 最大公约数
来源：http://dali.yanxiufei.cn/Article/details/gtzfucnwpa.html

Py:   math.gcd(a, b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrbxuclif.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yangfankeji.com/Article/details/gtwfbvhodb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxinkj.top/Article/details/gtgffmihqa.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cucudq.cn/Article/details/gtqhcczkqv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ppjwa.cn/Article/details/gtnsuemjzb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yuxming.cn/Article/details/gttjassajs.html

Ruby: a.gcd(b)
来源：http://dali.jiagoushi.top/Article/details/gtbalkzcmy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yj20258888.top/Article/details/gtulongfbx.html

[N06] 判断回文字符串
来源：http://dali.jinqigfzy.top/Article/details/gtnjsleuys.html

Py:   s == s[::-1]
来源：http://dali.kuanghao11.cn/Article/details/gtxcgplgew.html

PHP:  $s === strrev($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtbwrtrdml.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gttjoulihe.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtusxqhslz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.tianlin.xyz/Article/details/gtxhgswvjt.html

Go:   // 双指针从两端比较
来源：http://dali.quarkkingdee.top/Article/details/gtbwoadxad.html

Ruby: s == s.reverse
来源：http://dali.yueranfly.top/Article/details/gtdvubxcui.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.vqdsnc.cn/Article/details/gtpjzldxey.html

[N07] 两数之和（返回下标）
来源：http://dali.daxiang520.top/Article/details/gtyymypttz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yonumen.top/Article/details/gtcbenvggs.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jianghu66.top/Article/details/gtkdneviqq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shanyushiyangtech.top/Article/details/gtznaeqkct.html

TS:   // 手写 Map<string, number>
来源：http://dali.cqqwz.cn/Article/details/gtbzzcyeyb.html

Java: // 手写 HashMap
来源：http://dali.zhengqikj.top/Article/details/gtjlddjrkc.html

Go:   // 手写 map[int]int
来源：http://dali.tanke756.top/Article/details/gtewgcszwg.html

Ruby: // 手写 Hash
来源：http://dali.cqqwz.cn/Article/details/gtxcmycich.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jqgufenzy.top/Article/details/gthndjtsdo.html

[N08] 生成全排列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsvwyajce.html

Py:   itertools.permutations(arr)
来源：http://dali.nwbrower.top/Article/details/gtdwqwsgoo.html

PHP:  // 手写递归交换
来源：http://dali.haohaochexian.top/Article/details/gtmglmqyix.html

JS:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gtfmhmqkap.html

TS:   // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gtfqciryrt.html

Java: // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtrceempfk.html

Go:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtczuiszwb.html

Ruby: arr.permutation.to_a
来源：http://dali.gogol.net.cn/Article/details/gtsvfjnqbh.html

C#:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gtgutpkpfe.html

[N09] 栈与队列
来源：http://dali.hammf.cn/Article/details/gtpfcfdiit.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yangfankeji.com/Article/details/gturjddoeb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hfpthk.cn/Article/details/gtbaapmcig.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jinqigufen.top/Article/details/gtnfymwmzz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yj202588.top/Article/details/gtqcnvuzay.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sxryk.cn/Article/details/gtuofnrfkn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yuanzhike.top/Article/details/gtbtboqnte.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.daxiang520.top/Article/details/gttmgnywgv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sysykeji.top/Article/details/gtvcmefkfp.html

[N10] 链表节点定义
来源：http://dali.chenzaomai.com/Article/details/gtqvpfdhyp.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hysaishi.cn/Article/details/gtbvsansaq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hongshengwenyu.top/Article/details/gtivshpobv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.haohaochexian.top/Article/details/gtxwhkvsid.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shangyingyoupin.top/Article/details/gtsslumvls.html

Java: class Node { int v; Node next; }
来源：http://dali.sufxvd.cn/Article/details/gtxkgwdbzf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.daria6918.cn/Article/details/gttknlwkww.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cdnleiting.top/Article/details/gtxcaxuafx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zycfv.cn/Article/details/gtridqdidg.html

[N11] 二叉树中序遍历
来源：http://dali.jinqigufen.top/Article/details/gtfpmjmgip.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinqigfzy.top/Article/details/gtulqwkhuq.html

PHP:  // 手写递归函数
来源：http://dali.meibo888.top/Article/details/gtfdrcviij.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cucudq.cn/Article/details/gtovgmgaeh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxuanxn.top/Article/details/gttqbgbmaj.html

Java: // 手写递归
来源：http://dali.9152youxi.cn/Article/details/gtmytnlkln.html

Go:   // 手写递归
来源：http://dali.chenjidiqi.icu/Article/details/gtdjnvhpgg.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.redwolf501.top/Article/details/gtnlrvhfbt.html

C#:   // 手写递归
来源：http://dali.nanxinkj.top/Article/details/gtrkzxcfmu.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.meibo888.top/Article/details/gtkvbnfsip.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jqgfzy.top/Article/details/gtcwunzfzf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yj20258.top/Article/details/gtkxkwbunr.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gaohongyu789.top/Article/details/gtcjetqauj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinqigfzy.top/Article/details/gterlqlmwi.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigufen.top/Article/details/gtplqqjubp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.svipenyu.cn/Article/details/gtxyuyfldo.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gogol.net.cn/Article/details/gtvvpgehwa.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nwbrower.top/Article/details/gtiirkpnsf.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtsannpkux.html

O. 并发与异步
来源：http://dali.yj20258.top/Article/details/gtjgorgiig.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtrpoyksgm.html

[O01] 启动一个线程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtisyvfhau.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.quarkkingdee.top/Article/details/gtjursjwdn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gotoacloud.top/Article/details/gtjnxahiaz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cucudq.cn/Article/details/gtpbwydolu.html

TS:   // 同 JS
来源：http://dali.vqdsnc.cn/Article/details/gthkxtqaxx.html

Java: new Thread(() -> f()).start()
来源：http://dali.fzhhl.top/Article/details/gtedzesmvr.html

Go:   go f()
来源：http://dali.jqgfzy.top/Article/details/gtcbbgzmdm.html

Ruby: Thread.new { f }
来源：http://dali.andypj.xyz/Article/details/gtixqmqzne.html

C#:   Task.Run(() => F());
来源：http://dali.0kj1m.cn/Article/details/gtwshjnzqu.html

[O02] 使用线程池
来源：http://dali.daxiang520.top/Article/details/gtpahcmdyy.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.fengsongda.top/Article/details/gtgmxacqfm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jianghu66.top/Article/details/gttollcofk.html

JS:   // worker_threads 线程池
来源：http://dali.snrcjt.cn/Article/details/gtbhlrczht.html

TS:   // worker_threads 线程池
来源：http://dali.havefunace.top/Article/details/gteldrykxu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.tanke756.top/Article/details/gtjezkfasi.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.pengpengdd.cyou/Article/details/gtxunophws.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yanxiufei.cn/Article/details/gtbabbeiqt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.daxiang520.top/Article/details/gtcbtpznku.html

[O03] 加锁保护共享数据
来源：http://dali.hnxiangtu.top/Article/details/gtjutcwiqk.html

Py:   with lock: shared += 1
来源：http://dali.yuxming.cn/Article/details/gtiknqobmf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.snrcjt.cn/Article/details/gtuzixphnq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinqigufen.top/Article/details/gtrzgrkeui.html

TS:   // 同 JS
来源：http://dali.yongpay.top/Article/details/gtzbzfxutn.html

Java: synchronized (this) { shared++; }
来源：http://dali.gaohongyu789.top/Article/details/gtifbqlehh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xylfe.cn/Article/details/gtdzuatygr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinqigufen.top/Article/details/gtmpdvnthp.html

C#:   lock (gate) { shared++; }
来源：http://dali.316326.xyz/Article/details/gtswndgimw.html

[O04] 定义异步函数并等待
来源：http://dali.jiagoushi.top/Article/details/gtkyivogeh.html

Py:   async def f():⏎    await g()
来源：http://dali.chenjidiqi.icu/Article/details/gtejlfsmqu.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.vqdsnc.cn/Article/details/gtgbvspllw.html

JS:   async function f() { await g(); }
来源：http://dali.hfpthk.cn/Article/details/gtgeqkjhlw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.9152youxi.cn/Article/details/gtmojhbzds.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gtoctbooek.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yongpay.top/Article/details/gtllqzcitj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.smart0.xyz/Article/details/gtydtcxbqz.html

C#:   async Task F() { await G(); }
来源：http://dali.snrcjt.cn/Article/details/gtimcljmab.html

[O05] 并发执行并等待全部完成
来源：http://dali.jqgfzy.top/Article/details/gtqpwcmbex.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwajbtdpw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gaohongyu789.top/Article/details/gtzkmhwphf.html

JS:   await Promise.all(tasks)
来源：http://dali.iojbl.cn/Article/details/gtkxnfhpdi.html

TS:   await Promise.all(tasks)
来源：http://dali.tanke756.top/Article/details/gtokmejmlu.html


<!-- 参考信息 -->