代发 wailian999

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.c1oappe.top/Article/details/gtosnruvnc.html

JS:   await fetch(url)
来源：http://dali.yueranfly.top/Article/details/gtjwilfpce.html

TS:   await fetch(url)
来源：http://dali.jqgfzy.top/Article/details/gtjojdzgey.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gotoacloud.top/Article/details/gtipbolwck.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gtbrmcxiua.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.redwolf501.top/Article/details/gtdncrehqw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ehwqpu.com/Article/details/gtxgnykglm.html

[L02] 发送 POST JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrhiornvh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.vqdsnc.cn/Article/details/gtptyaterb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.316326.xyz/Article/details/gtmrnllyjo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.andypj.xyz/Article/details/gtrqgmrwew.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cdnleiting.top/Article/details/gtdwdipstc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hfpthk.cn/Article/details/gtwxfzzbam.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.9152youxi.cn/Article/details/gthqymaddp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttpktthjb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.316326.xyz/Article/details/gtmpcqpcta.html

[L03] 设置自定义请求头
来源：http://dali.gaohongyu789.top/Article/details/gtgheyjuut.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.quarkkingdee.top/Article/details/gtdawomaiv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhoulong.xyz/Article/details/gtkbghwufc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.svipenyu.cn/Article/details/gtmaeqhrlu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhoulong.xyz/Article/details/gtymvsohms.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.redwolf501.top/Article/details/gtojbxjicd.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.meibo888.top/Article/details/gthwdcdkhl.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zycfv.cn/Article/details/gtznyhtlae.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yongpay.top/Article/details/gtpzqwthmj.html

[L04] 设置超时
来源：http://dali.gogol.net.cn/Article/details/gtfbnpedif.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jianghu66.top/Article/details/gtundrjnco.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gaohongyu789.top/Article/details/gtnaiptoun.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gtgksrornl.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuetiantiany.cn/Article/details/gtjkmbuafs.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.pycfn.com/Article/details/gtbyohawqy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gzhubu.top/Article/details/gtahtmxhze.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.tanke756.top/Article/details/gtbkrzlzum.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.pengpengdd.cyou/Article/details/gtwsmxhixd.html

[L05] 上传文件（multipart）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbpknyfnk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ivvv.top/Article/details/gtplhxartf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hongshengwenyu.top/Article/details/gtxrigqbpi.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yueranfly.top/Article/details/gtagcycwyo.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.0kj1m.cn/Article/details/gtfdxiclzp.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shanyushiyangtech.top/Article/details/gtefjvhhzt.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.svipenyu.cn/Article/details/gtaivlcjft.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.aizwys.cn/Article/details/gtmbzqmkwn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yj202588.top/Article/details/gtkmrknkyb.html

[L06] 解析响应为 JSON
来源：http://dali.0kj1m.cn/Article/details/gtdisawoai.html

Py:   resp.json()
来源：http://dali.yj202588.top/Article/details/gtfohtknzf.html

PHP:  json_decode($body, true);
来源：http://dali.nwbrower.top/Article/details/gtgnrzrsxq.html

JS:   await resp.json()
来源：http://dali.meibo888.top/Article/details/gtkpwxsefc.html

TS:   await resp.json()
来源：http://dali.nwbrower.top/Article/details/gtnnccmyrx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.meibo888.top/Article/details/gtqcoumbkm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.chenzaomai.com/Article/details/gtbeovortx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yuxming.cn/Article/details/gtabogwire.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yuxming.cn/Article/details/gttzrdyabi.html

[L07] 处理 HTTP 状态码
来源：http://dali.jqgufenzy.top/Article/details/gtyxfqceao.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.wangshuangyany.cn/Article/details/gtkvsppwaj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ydzc1.top/Article/details/gteoxfthrx.html

JS:   resp.ok;  resp.status
来源：http://dali.cdnleiting.top/Article/details/gtuibcaviz.html

TS:   resp.ok;  resp.status
来源：http://dali.smart0.xyz/Article/details/gttboggugy.html

Java: resp.statusCode()
来源：http://dali.c1oappe.top/Article/details/gtyfzhdesg.html

Go:   resp.StatusCode
来源：http://dali.xuanzx.com/Article/details/gtxwpbwfki.html

Ruby: resp.code.to_i
来源：http://dali.daxiang520.top/Article/details/gtdzildatl.html

C#:   (int)resp.StatusCode
来源：http://dali.fengsongda.top/Article/details/gtcxpvvobr.html

[L08] 并发请求多个地址
来源：http://dali.yuanzhike.top/Article/details/gtxqbytusc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hywenlv.cn/Article/details/gtnfvgphaq.html

PHP:  curl_multi_init() 系列
来源：http://dali.nanxuanxn.top/Article/details/gthgnxqcma.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbqwqdtku.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shzxlz.cn/Article/details/gtkntekoun.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ppjwa.cn/Article/details/gtjjiumlaa.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.fzhhl.top/Article/details/gtrvjndwhs.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.c1oappe.top/Article/details/gtdkqlsnxm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.aibaodan.cn/Article/details/gtvepdugab.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtgtnshtgq.html

M. 命令行 / 进程 / 环境
来源：http://dali.ppjwa.cn/Article/details/gtnqwuyhaw.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gthgouptwe.html

[M01] 读取命令行参数
来源：http://dali.nwbrower.top/Article/details/gtqlcyxmtu.html

Py:   sys.argv[1:]
来源：http://dali.cashguo.top/Article/details/gtxtyqvnmg.html

PHP:  $argv;  $argc;
来源：http://dali.redwolf501.top/Article/details/gtvdktybrh.html

JS:   process.argv.slice(2)
来源：http://dali.yonumen.top/Article/details/gthtpkbqhn.html

TS:   process.argv.slice(2)
来源：http://dali.cqqwz.cn/Article/details/gttedbidvq.html

Java: args 数组（main 方法参数）
来源：http://dali.chenlongwang.top/Article/details/gtfeycwtvd.html

Go:   os.Args[1:]
来源：http://dali.yuxming.cn/Article/details/gtbfmifisl.html

Ruby: ARGV
来源：http://dali.cheryme.top/Article/details/gtijabwllr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhongyouzk.top/Article/details/gtmetlouqk.html

[M02] 读取环境变量
来源：http://dali.wangdashe.top/Article/details/gtzopuhftr.html

Py:   os.environ.get("HOME")
来源：http://dali.daria6918.cn/Article/details/gtzpxzntnp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdaflaqal.html

JS:   process.env.HOME
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnkpkaivi.html

TS:   process.env.HOME
来源：http://dali.xuetiantiany.cn/Article/details/gtwvwnjfvc.html

Java: System.getenv("HOME")
来源：http://dali.hfpthk.cn/Article/details/gtipeivmdm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.aizwys.cn/Article/details/gtsauzlacw.html

Ruby: ENV["HOME"]
来源：http://dali.cqqwz.cn/Article/details/gtribxglfn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.snrcjt.cn/Article/details/gtdqubdevt.html

[M03] 执行外部命令
来源：http://dali.aizwys.cn/Article/details/gtdpxeujtl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.c1oappe.top/Article/details/gtysbawcop.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cashguo.top/Article/details/gtkfwznajk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hysaishi.cn/Article/details/gtdaywstbz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxuanxn.top/Article/details/gtaajzoues.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ivvv.top/Article/details/gtillbqljf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cashguo.top/Article/details/gtwwqpatsx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hnqzz.top/Article/details/gtmghqmwno.html

C#:   Process.Start("ls", "-l");
来源：http://dali.birdmap.top/Article/details/gtpygodogp.html

[M04] 获取当前工作目录
来源：http://dali.shanyushiyangtech.top/Article/details/gtjjpygbus.html

Py:   os.getcwd()
来源：http://dali.guannengcc.top/Article/details/gttyreslhh.html

PHP:  getcwd();
来源：http://dali.zhongyouzk.top/Article/details/gtcqplzgvl.html

JS:   process.cwd()
来源：http://dali.jiagoushi.top/Article/details/gtxglwiwyc.html

TS:   process.cwd()
来源：http://dali.pengpengdd.cyou/Article/details/gtbhemdfaz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.pycfn.com/Article/details/gtdkmmsitm.html

Go:   os.Getwd()
来源：http://dali.yj202588.top/Article/details/gtumklegtx.html

Ruby: Dir.pwd
来源：http://dali.jlsjyb.cn/Article/details/gtbkcwobll.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jqgufenzy.top/Article/details/gtmzihsbpa.html

[M05] 设置退出码
来源：http://dali.aibaodan.cn/Article/details/gtuxninucg.html

Py:   sys.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gtrqrjntpw.html

PHP:  exit(1);
来源：http://dali.quarkkingdee.top/Article/details/gtsvovbsst.html

JS:   process.exit(1)
来源：http://dali.yueranfly.top/Article/details/gtdlkwefya.html

TS:   process.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoyegrckz.html

Java: System.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtyvvzafvk.html

Go:   os.Exit(1)
来源：http://dali.tanke756.top/Article/details/gtjawzkukf.html

Ruby: exit 1
来源：http://dali.jqgufenzy.top/Article/details/gtrgzbuwpq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gzhubu.top/Article/details/gthcytdyzb.html

[M06] 向标准错误输出
来源：http://dali.ppjwa.cn/Article/details/gteydacldf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zdqjudy.top/Article/details/gtoskdkowx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.0kj1m.cn/Article/details/gtixvryiww.html

JS:   console.error("err")
来源：http://dali.zdqjudy.top/Article/details/gtwoyhosml.html

TS:   console.error("err")
来源：http://dali.snrcjt.cn/Article/details/gtmqzpkdsz.html

Java: System.err.println("err")
来源：http://dali.hfpthk.cn/Article/details/gtxzpgarqf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yvedp.cn/Article/details/gtdrciesqq.html

Ruby: warn "err"
来源：http://dali.cashguo.top/Article/details/gtoaehstvo.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tian-w.cn/Article/details/gtxxwuhrhw.html

[M07] 判断是否为主入口
来源：http://dali.dianchejie.cn/Article/details/gtixajdrmn.html

Py:   if __name__ == "__main__":
来源：http://dali.hnqzz.top/Article/details/gtthgjhdln.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.chenlongwang.top/Article/details/gtlyrqisat.html

JS:   require.main === module
来源：http://dali.yonumen.top/Article/details/gtdorhxaju.html

TS:   require.main === module
来源：http://dali.andypj.xyz/Article/details/gtfvpbyeia.html

Java: public static void main(String[] args)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdptyfowb.html

Go:   func main()
来源：http://dali.xuetiantiany.cn/Article/details/gttbqcfsjc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yanxiufei.cn/Article/details/gtcdoppvxj.html

C#:   static void Main(string[] args)
来源：http://dali.cdnleiting.top/Article/details/gtnhpmfplo.html

[M08] 获取系统与运行时信息
来源：http://dali.meibo888.top/Article/details/gtvdrukwus.html

Py:   platform.system();  platform.python_version()
来源：http://dali.snrcjt.cn/Article/details/gtngsuzufp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yongpay.top/Article/details/gtadqnecpr.html

JS:   process.platform;  process.version
来源：http://dali.yj20258.top/Article/details/gtkirobbni.html

TS:   process.platform;  process.version
来源：http://dali.jinqigfzy.top/Article/details/gtqwuweebp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gtklzvxnna.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jyoumei.cn/Article/details/gtlcimeqxv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shanyushiyangkeji.top/Article/details/gthbrblzhp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhongyouzk.top/Article/details/gtbhlgyelc.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gthvlueinf.html

N. 数据结构与算法
来源：http://dali.jinqigfzy.top/Article/details/gtuaqxcdtz.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtmxopnkdp.html

[N01] 二分查找（有序数组）
来源：http://dali.yuanzhike.top/Article/details/gtmuulcfaf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gttnbfpxah.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yonumen.top/Article/details/gtthppkoog.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhoulong.xyz/Article/details/gtvkbaybbd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhongyouzk.top/Article/details/gtjdefoqam.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yuxming.cn/Article/details/gtfbdxtwdr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxlltdvbu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jiagoushi.top/Article/details/gtvuerdkgn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtbvicbjhn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinyuanbaomall.cn/Article/details/gttjkudbew.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhoulong.xyz/Article/details/gtcpiymttm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zycfv.cn/Article/details/gtodphywpv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gzhubu.top/Article/details/gtpruumxsc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aibaodan.cn/Article/details/gtozlmizqn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.kuanghao11.cn/Article/details/gtzbietbml.html

Go:   slices.Sort(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtukwqhbln.html

Ruby: arr.sort
来源：http://dali.kuanghao11.cn/Article/details/gttwiqkybw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ehwqpu.com/Article/details/gtsbxbqqik.html

[N03] 快速排序（分治示例）
来源：http://dali.jinqigufen.top/Article/details/gteidwthfc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhoulong.xyz/Article/details/gttifqqaxb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yuanzhike.top/Article/details/gtjbjionuc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fzhhl.top/Article/details/gthbdfriac.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.snrcjt.cn/Article/details/gtluarhmpw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhoulong.xyz/Article/details/gtafgrekji.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj20258888.top/Article/details/gtnrjlqhix.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xuetiantiany.cn/Article/details/gthwfkbfxp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.smart0.xyz/Article/details/gtnxjcczaw.html

[N04] 斐波那契数列
来源：http://dali.birdmap.top/Article/details/gtdqwflsax.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jyoumei.cn/Article/details/gtblbjguzp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ybcxt.top/Article/details/gtmphiyzhf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xylfe.cn/Article/details/gtbnjwkyaq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.kuanghao11.cn/Article/details/gtnymvswin.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gotoacloud.top/Article/details/gtnsllmqsh.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yanxiufei.cn/Article/details/gtaisnkckl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtootystdd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gtgmnumpoz.html

[N05] 最大公约数
来源：http://dali.cqqwz.cn/Article/details/gtoryxzlir.html

Py:   math.gcd(a, b)
来源：http://dali.guannengcc.top/Article/details/gtypgunqhp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.aizwys.cn/Article/details/gtkngiwown.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhoulong.xyz/Article/details/gtmklhutzb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.smart0.xyz/Article/details/gtqqpdafby.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jiagoushi.top/Article/details/gtwbbbnxco.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhixingplan.top/Article/details/gtqmrpjyxn.html

Ruby: a.gcd(b)
来源：http://dali.shangyingyoupin.top/Article/details/gtbymzeakp.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yj20258888.top/Article/details/gtausxlzmh.html

[N06] 判断回文字符串
来源：http://dali.bjfxy.top/Article/details/gtapwwidse.html

Py:   s == s[::-1]
来源：http://dali.kuanghao11.cn/Article/details/gtzculmyus.html

PHP:  $s === strrev($s);
来源：http://dali.gzhubu.top/Article/details/gtglprbcfi.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gtjqxuvdjm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gtihhcwnhp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hammf.cn/Article/details/gtdmuuoggi.html

Go:   // 双指针从两端比较
来源：http://dali.xuetiantiany.cn/Article/details/gtteeqbzzc.html

Ruby: s == s.reverse
来源：http://dali.xuanzx.com/Article/details/gtxyharhwi.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.guowangkeji.top/Article/details/gtojotgqio.html

[N07] 两数之和（返回下标）
来源：http://dali.xinyue.icu/Article/details/gtbenrynck.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cucudq.cn/Article/details/gtsltqoncy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.guannengcc.top/Article/details/gtvcdcxpct.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sysykeji.top/Article/details/gtehonsclg.html

TS:   // 手写 Map<string, number>
来源：http://dali.birdmap.top/Article/details/gteodpvtqf.html

Java: // 手写 HashMap
来源：http://dali.chenlongwang.top/Article/details/gtikubvsis.html

Go:   // 手写 map[int]int
来源：http://dali.sweek.top/Article/details/gtzrskvtgq.html

Ruby: // 手写 Hash
来源：http://dali.chenlongwang.top/Article/details/gtvcrylmxy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.pengpengdd.cyou/Article/details/gtysmjhice.html

[N08] 生成全排列
来源：http://dali.meibo888.top/Article/details/gtmytnncpb.html

Py:   itertools.permutations(arr)
来源：http://dali.guannengcc.top/Article/details/gtkiylooue.html

PHP:  // 手写递归交换
来源：http://dali.shzxlz.cn/Article/details/gtakidlyxf.html

JS:   // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gtedrvhvtj.html

TS:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gtzlydolbn.html

Java: // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gtmnwfumfh.html

Go:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoaivcofy.html

Ruby: arr.permutation.to_a
来源：http://dali.jinghuilouyu.cn/Article/details/gtmegcwanu.html

C#:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gtdplxotlw.html

[N09] 栈与队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkfqmjkty.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.svipenyu.cn/Article/details/gtxqrvcckw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hfpthk.cn/Article/details/gtrsprijrs.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shzxlz.cn/Article/details/gtyuajhfhk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zdqjudy.top/Article/details/gtkczkvcfi.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.iojbl.cn/Article/details/gttafhlzlc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.dashuyun.cn/Article/details/gttkktjaxb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.tanke756.top/Article/details/gtgzxmqyzt.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yongpay.top/Article/details/gtjkfkwvkf.html

[N10] 链表节点定义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbqrulpov.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gogol.net.cn/Article/details/gtlngdvyki.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gzhubu.top/Article/details/gtskmihzic.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.wangdashe.top/Article/details/gtgmonsmcq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.smart0.xyz/Article/details/gtdroctkgw.html

Java: class Node { int v; Node next; }
来源：http://dali.hongshengwenyu.top/Article/details/gtvdzhmwoo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.iojbl.cn/Article/details/gtksqtowxf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hysaishi.cn/Article/details/gttyhwcfry.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.nanxinkj.top/Article/details/gtazcuuxje.html

[N11] 二叉树中序遍历
来源：http://dali.hnxiangtu.top/Article/details/gtcvvnrmac.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.smart0.xyz/Article/details/gtmsciftct.html

PHP:  // 手写递归函数
来源：http://dali.tian-w.cn/Article/details/gtudxrtfdj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hongshengwenyu.top/Article/details/gtadwcznyy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gogol.net.cn/Article/details/gtwsgqwzdg.html

Java: // 手写递归
来源：http://dali.jinqigfzy.top/Article/details/gtzdreczno.html

Go:   // 手写递归
来源：http://dali.fengsongda.top/Article/details/gtugwxwvih.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.nanxuanxn.top/Article/details/gtwdrgcsuc.html

C#:   // 手写递归
来源：http://dali.ivvv.top/Article/details/gtcugxoqci.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.wangshuangyany.cn/Article/details/gtlietfsjg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.meibo888.top/Article/details/gtahjsxbgh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhixingplan.top/Article/details/gtzkbslgrz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmohzjlrm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aibaodan.cn/Article/details/gtwdimsixh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.mhx1999.top/Article/details/gtkzeygzgj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.meibo888.top/Article/details/gtclaqgzag.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ivvv.top/Article/details/gtmkofswak.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nanxuanxn.top/Article/details/gtvpjuajxu.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtscrvdzzq.html

O. 并发与异步
来源：http://dali.pengpengdd.cyou/Article/details/gtjjetdzoi.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtprmhpnlz.html

[O01] 启动一个线程
来源：http://dali.haohaochexian.top/Article/details/gtojtdseil.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.mhx1999.top/Article/details/gtlanpovyb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.9152youxi.cn/Article/details/gtdwihdlsa.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.aizwys.cn/Article/details/gtdrmstsyr.html

TS:   // 同 JS
来源：http://dali.zhoulong.xyz/Article/details/gtylbcrgzk.html

Java: new Thread(() -> f()).start()
来源：http://dali.xylfe.cn/Article/details/gtkoycmgza.html

Go:   go f()
来源：http://dali.shangyingyoupin.top/Article/details/gtsgbdazwk.html

Ruby: Thread.new { f }
来源：http://dali.hammf.cn/Article/details/gtclsuykbp.html

C#:   Task.Run(() => F());
来源：http://dali.ppjwa.cn/Article/details/gtlhncypue.html

[O02] 使用线程池
来源：http://dali.jqgufenzy.top/Article/details/gtoawlwcaj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jqgfzy.top/Article/details/gtozjihfsk.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhengqikj.top/Article/details/gtduwlsjin.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gtqqfhsozy.html

TS:   // worker_threads 线程池
来源：http://dali.feifeiyinyue.top/Article/details/gtbwpnoywi.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinqigufen.top/Article/details/gtrkhseuxs.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jlsjyb.cn/Article/details/gtfcvxlphk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gogol.net.cn/Article/details/gtbjlclvab.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.tanke756.top/Article/details/gthyyvfdan.html

[O03] 加锁保护共享数据
来源：http://dali.yvedp.cn/Article/details/gtmivrfrjp.html

Py:   with lock: shared += 1
来源：http://dali.mhx1999.top/Article/details/gtfuszplmm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.0kj1m.cn/Article/details/gtuhzuwtip.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gzhubu.top/Article/details/gtgawbzewn.html

TS:   // 同 JS
来源：http://dali.c1oappe.top/Article/details/gtdkssknve.html

Java: synchronized (this) { shared++; }
来源：http://dali.tanke756.top/Article/details/gtdpugffnh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhengqikj.top/Article/details/gtsvenzkpm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hfpthk.cn/Article/details/gtetfeaofn.html

C#:   lock (gate) { shared++; }
来源：http://dali.yj202588.top/Article/details/gtmfnqgufe.html

[O04] 定义异步函数并等待
来源：http://dali.jlsjyb.cn/Article/details/gtxfxkylhi.html

Py:   async def f():⏎    await g()
来源：http://dali.chenzaomai.com/Article/details/gtfgusmgvd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hammf.cn/Article/details/gtapunqorx.html

JS:   async function f() { await g(); }
来源：http://dali.hywenlv.cn/Article/details/gttnlbakux.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yonumen.top/Article/details/gtzdihgaed.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.bjfxy.top/Article/details/gtjmsyztmg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ydzc1.top/Article/details/gtpxjjgvnc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.aibaodan.cn/Article/details/gtsqmtrasf.html

C#:   async Task F() { await G(); }
来源：http://dali.yj20258.top/Article/details/gtzheahzcg.html

[O05] 并发执行并等待全部完成
来源：http://dali.0kj1m.cn/Article/details/gtbouryfzp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cqqwz.cn/Article/details/gtflxsgvdb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.nanxinkj.top/Article/details/gtyvefvpih.html

JS:   await Promise.all(tasks)
来源：http://dali.nanxinkj.top/Article/details/gtlcoyfeky.html

TS:   await Promise.all(tasks)
来源：http://dali.tianlin.xyz/Article/details/gtouryrkxo.html


<!-- 参考信息 -->