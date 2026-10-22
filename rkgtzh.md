代发 wailian999

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnnkriqis.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gtklgkvrwo.html

TS:   await fetch(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbdhkugeo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sxryk.cn/Article/details/gtnhugoygd.html

Go:   resp, err := http.Get(url)
来源：http://dali.yj20258.top/Article/details/gtixkyqeag.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gotoacloud.top/Article/details/gtpkkgampg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cqqwz.cn/Article/details/gtmcrnpibc.html

[L02] 发送 POST JSON
来源：http://dali.hnqzz.top/Article/details/gtsoiferqp.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gogol.net.cn/Article/details/gtdetkindj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gaohongyu789.top/Article/details/gtdwngxyeh.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.bjfxy.top/Article/details/gtmmroembv.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gogol.net.cn/Article/details/gtyxjoravz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinqigfzy.top/Article/details/gtnbuvgqja.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xuanzx.com/Article/details/gtbepqytfk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yj20258.top/Article/details/gtcpwtnyzk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hongshengwenyu.top/Article/details/gtqyljwnmh.html

[L03] 设置自定义请求头
来源：http://dali.9152youxi.cn/Article/details/gtdzomtxuo.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sufxvd.cn/Article/details/gtyfpqijcq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenjidiqi.icu/Article/details/gtjfrxnnko.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhengqikj.top/Article/details/gtpfqujehd.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuetiantiany.cn/Article/details/gthseghuhp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gtwgsubalt.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yvedp.cn/Article/details/gtysyccsnw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.pengpengdd.cyou/Article/details/gtvoninjqr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.chenlongwang.top/Article/details/gtgnuolnmm.html

[L04] 设置超时
来源：http://dali.birdmap.top/Article/details/gtmgvcfepf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhoulong.xyz/Article/details/gtjgiqgkvt.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shzxlz.cn/Article/details/gtkfzuucsa.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuanzhike.top/Article/details/gtjnoovmbs.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zycfv.cn/Article/details/gtkoocscem.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gaohongyu789.top/Article/details/gtbijbdbqv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinqigfzy.top/Article/details/gtiajzgwel.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cucudq.cn/Article/details/gtijfmpapv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jianghu66.top/Article/details/gtdeqocsiz.html

[L05] 上传文件（multipart）
来源：http://dali.quarkkingdee.top/Article/details/gtapsaffpc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jiagoushi.top/Article/details/gtrjyluzpi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shangyingyoupin.top/Article/details/gtefdxknjo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhixingplan.top/Article/details/gtrdkaesjr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hongshengwenyu.top/Article/details/gtpdhituhf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gogol.net.cn/Article/details/gtywjqpbdx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.daria6918.cn/Article/details/gtiykavbdn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.daxiang520.top/Article/details/gteihyolid.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yongpay.top/Article/details/gtxtyyabze.html

[L06] 解析响应为 JSON
来源：http://dali.havefunace.top/Article/details/gtoiwegmfc.html

Py:   resp.json()
来源：http://dali.hongshengwenyu.top/Article/details/gtwuaudjeg.html

PHP:  json_decode($body, true);
来源：http://dali.zhiwuduotai.top/Article/details/gtjwtamklt.html

JS:   await resp.json()
来源：http://dali.cashguo.top/Article/details/gtbuiyhjxr.html

TS:   await resp.json()
来源：http://dali.tanke756.top/Article/details/gtjxdyfzei.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cashguo.top/Article/details/gtadabfobw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.gaohongyu789.top/Article/details/gtxyyltqwx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hysaishi.cn/Article/details/gtxrnaldeo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yueranfly.top/Article/details/gtzmaepbcj.html

[L07] 处理 HTTP 状态码
来源：http://dali.vqdsnc.cn/Article/details/gtjabovusa.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nwbrower.top/Article/details/gttcbvqmaj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hfpthk.cn/Article/details/gtqlcvfdwa.html

JS:   resp.ok;  resp.status
来源：http://dali.yj20258.top/Article/details/gtuaminfjd.html

TS:   resp.ok;  resp.status
来源：http://dali.jinqigfzy.top/Article/details/gtnjarijvh.html

Java: resp.statusCode()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkqdpayql.html

Go:   resp.StatusCode
来源：http://dali.shuidangran.top/Article/details/gtudieqyhb.html

Ruby: resp.code.to_i
来源：http://dali.bjfxy.top/Article/details/gtdqzufpid.html

C#:   (int)resp.StatusCode
来源：http://dali.smart0.xyz/Article/details/gtamlyrmkb.html

[L08] 并发请求多个地址
来源：http://dali.jinqigufen.top/Article/details/gtmcjwdbba.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jiagoushi.top/Article/details/gtqzllcqvw.html

PHP:  curl_multi_init() 系列
来源：http://dali.cucudq.cn/Article/details/gtyqrlslwb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dashuyun.cn/Article/details/gtjfuxbpho.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xinyue.icu/Article/details/gtbjttfvlk.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gotoacloud.top/Article/details/gtxgupjcfg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.havefunace.top/Article/details/gthgwczvlh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ybcxt.top/Article/details/gtsvmxqhhk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.guowangkeji.top/Article/details/gtwptqaahb.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtjmunffwq.html

M. 命令行 / 进程 / 环境
来源：http://dali.feifeiyinyue.top/Article/details/gtepjobpjc.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtpktcbtcb.html

[M01] 读取命令行参数
来源：http://dali.vqdsnc.cn/Article/details/gtlcebguwl.html

Py:   sys.argv[1:]
来源：http://dali.dashuyun.cn/Article/details/gtqohlejbg.html

PHP:  $argv;  $argc;
来源：http://dali.c1oappe.top/Article/details/gtzucaxrwp.html

JS:   process.argv.slice(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtexlmgjot.html

TS:   process.argv.slice(2)
来源：http://dali.0kj1m.cn/Article/details/gtsygqewmp.html

Java: args 数组（main 方法参数）
来源：http://dali.0kj1m.cn/Article/details/gthwsrypef.html

Go:   os.Args[1:]
来源：http://dali.birdmap.top/Article/details/gtiuowdcsx.html

Ruby: ARGV
来源：http://dali.jqgufenzy.top/Article/details/gtqsifkhpe.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hfpthk.cn/Article/details/gtmndfnwrp.html

[M02] 读取环境变量
来源：http://dali.yj20258.top/Article/details/gteslikoxj.html

Py:   os.environ.get("HOME")
来源：http://dali.sweek.top/Article/details/gtzzqftpzr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.vqdsnc.cn/Article/details/gtffsgvnvh.html

JS:   process.env.HOME
来源：http://dali.9152youxi.cn/Article/details/gtsrpehypv.html

TS:   process.env.HOME
来源：http://dali.wangshuangyany.cn/Article/details/gtgayjfvgi.html

Java: System.getenv("HOME")
来源：http://dali.sufxvd.cn/Article/details/gtvndnhcny.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yonumen.top/Article/details/gtbyopnegt.html

Ruby: ENV["HOME"]
来源：http://dali.nanxinkj.top/Article/details/gtqnopfzra.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jqgfzy.top/Article/details/gtscpqjxce.html

[M03] 执行外部命令
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvrypyhfg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.fzhhl.top/Article/details/gtbwnfgoya.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.feifeiyinyue.top/Article/details/gtzwydnyjp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhoulong.xyz/Article/details/gtaojhljcl.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.0kj1m.cn/Article/details/gtaamhjudp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhoulong.xyz/Article/details/gttrbvejrw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gaohongyu789.top/Article/details/gtsmhmhyzl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shanyushiyangtech.top/Article/details/gtwnqlqkri.html

C#:   Process.Start("ls", "-l");
来源：http://dali.daxiang520.top/Article/details/gtawamaowz.html

[M04] 获取当前工作目录
来源：http://dali.fengsongda.top/Article/details/gtqwsqfucy.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gtbxkkjecj.html

PHP:  getcwd();
来源：http://dali.hysaishi.cn/Article/details/gtspdiuiuj.html

JS:   process.cwd()
来源：http://dali.fzhhl.top/Article/details/gtxodbawoh.html

TS:   process.cwd()
来源：http://dali.yuanzhike.top/Article/details/gtlqkgezsk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.feifeiyinyue.top/Article/details/gtqiiviicg.html

Go:   os.Getwd()
来源：http://dali.andypj.xyz/Article/details/gtajutkckv.html

Ruby: Dir.pwd
来源：http://dali.jianghu66.top/Article/details/gtfonhgeut.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtufzmejqw.html

[M05] 设置退出码
来源：http://dali.tianlin.xyz/Article/details/gticijntzn.html

Py:   sys.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gtqsjzyfpz.html

PHP:  exit(1);
来源：http://dali.tian-w.cn/Article/details/gtnpxvtcht.html

JS:   process.exit(1)
来源：http://dali.yj20258.top/Article/details/gtqlnfapdg.html

TS:   process.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsbvsvhcw.html

Java: System.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gtocvpklro.html

Go:   os.Exit(1)
来源：http://dali.iojbl.cn/Article/details/gtweznotai.html

Ruby: exit 1
来源：http://dali.andypj.xyz/Article/details/gtbwucowvr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.guowangkeji.top/Article/details/gtlnbzfmhx.html

[M06] 向标准错误输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsjbprvas.html

Py:   print("err", file=sys.stderr)
来源：http://dali.redwolf501.top/Article/details/gtwbpqdfku.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yangfankeji.com/Article/details/gtymvollyy.html

JS:   console.error("err")
来源：http://dali.pengpengdd.cyou/Article/details/gtbyrjnksz.html

TS:   console.error("err")
来源：http://dali.hnqzz.top/Article/details/gtjgkmimml.html

Java: System.err.println("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqtameqja.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.kuanghao11.cn/Article/details/gtsdlewsga.html

Ruby: warn "err"
来源：http://dali.zhongyouzk.top/Article/details/gtyihbxrrv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.vqdsnc.cn/Article/details/gtwkqzfswp.html

[M07] 判断是否为主入口
来源：http://dali.zhixingplan.top/Article/details/gtzlddahyu.html

Py:   if __name__ == "__main__":
来源：http://dali.haohaochexian.top/Article/details/gtrdephqqb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yvedp.cn/Article/details/gtffgeoorg.html

JS:   require.main === module
来源：http://dali.yuxming.cn/Article/details/gtbqbikgjz.html

TS:   require.main === module
来源：http://dali.316326.xyz/Article/details/gtodqllmlr.html

Java: public static void main(String[] args)
来源：http://dali.jiagoushi.top/Article/details/gtoiqyiqih.html

Go:   func main()
来源：http://dali.xylfe.cn/Article/details/gtalplorxw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yj20258888.top/Article/details/gtowscmsoq.html

C#:   static void Main(string[] args)
来源：http://dali.dianchejie.cn/Article/details/gtvtofectq.html

[M08] 获取系统与运行时信息
来源：http://dali.birdmap.top/Article/details/gtprqxegki.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgnjbzutn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.nanxinkj.top/Article/details/gtrkoaodzs.html

JS:   process.platform;  process.version
来源：http://dali.cucudq.cn/Article/details/gtycsqghgg.html

TS:   process.platform;  process.version
来源：http://dali.guowangkeji.top/Article/details/gtaithnkqt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqyluwwye.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hywenlv.cn/Article/details/gtcxolomma.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.wangshuangyany.cn/Article/details/gtwnratndb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yj20258888.top/Article/details/gtqopsslbc.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtjmknnaio.html

N. 数据结构与算法
来源：http://dali.zhiwuduotai.top/Article/details/gtsxsuouxz.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtdqmgzxjp.html

[N01] 二分查找（有序数组）
来源：http://dali.shangyingyoupin.top/Article/details/gtjmxopuaf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtifmzvvwd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cucudq.cn/Article/details/gtutpoywhj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhixingplan.top/Article/details/gtmgxreuea.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guannengcc.top/Article/details/gthbmoczpq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtxvynkwyt.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gthraonrns.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hysaishi.cn/Article/details/gtkpmvlqpk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hammf.cn/Article/details/gthhzizvxb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinqigfzy.top/Article/details/gtjdmcwyrd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hammf.cn/Article/details/gtohvriqwx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zycfv.cn/Article/details/gtncytxbel.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenlongwang.top/Article/details/gtbnfztsvi.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.bjfxy.top/Article/details/gtvytrefql.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xziqi.cn/Article/details/gteumaoeox.html

Go:   slices.Sort(arr)
来源：http://dali.gzhubu.top/Article/details/gtcgoawqnn.html

Ruby: arr.sort
来源：http://dali.shangyingyoupin.top/Article/details/gtfmvaunen.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yj20258888.top/Article/details/gtfftfywoe.html

[N03] 快速排序（分治示例）
来源：http://dali.dianchejie.cn/Article/details/gtafncjcyf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsvmglvak.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cucudq.cn/Article/details/gtxfjfodlf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwrkzcgtl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shangyingyoupin.top/Article/details/gtqwczwhpu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.chenjidiqi.icu/Article/details/gtzvtkmluh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.iojbl.cn/Article/details/gtupxtzydn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ybcxt.top/Article/details/gtmryeldrm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hnxiangtu.top/Article/details/gtniclqqbn.html

[N04] 斐波那契数列
来源：http://dali.shuidangran.top/Article/details/gtrzmojvgd.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hysaishi.cn/Article/details/gtsoboczbq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.quarkkingdee.top/Article/details/gtximazjqr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtbcvetvbu.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtyehjgiem.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.sufxvd.cn/Article/details/gttftmewae.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yj202588.top/Article/details/gtvptjhekg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yongpay.top/Article/details/gtfjsrzwkj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yvedp.cn/Article/details/gtziirpwva.html

[N05] 最大公约数
来源：http://dali.chenjidiqi.icu/Article/details/gtcfaeqtcq.html

Py:   math.gcd(a, b)
来源：http://dali.hammf.cn/Article/details/gtaevtljnl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ivvv.top/Article/details/gtgypxxacr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ydzc1.top/Article/details/gtppmmevwl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jianghu66.top/Article/details/gtmnograbb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shzxlz.cn/Article/details/gtfsbvxzmj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yvedp.cn/Article/details/gtpyixedyy.html

Ruby: a.gcd(b)
来源：http://dali.ydzc1.top/Article/details/gtzhxmpxzx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.smart0.xyz/Article/details/gtheldtucd.html

[N06] 判断回文字符串
来源：http://dali.andypj.xyz/Article/details/gtcwmjkugm.html

Py:   s == s[::-1]
来源：http://dali.jinqigufen.top/Article/details/gtvqlxhcmu.html

PHP:  $s === strrev($s);
来源：http://dali.ppjwa.cn/Article/details/gtybqawdqp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtybyetboc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gtkctfvuee.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.feifeiyinyue.top/Article/details/gtqulrizrd.html

Go:   // 双指针从两端比较
来源：http://dali.ppjwa.cn/Article/details/gtstitqgtu.html

Ruby: s == s.reverse
来源：http://dali.meibo888.top/Article/details/gtgdnaojfp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gzhubu.top/Article/details/gtolacyobi.html

[N07] 两数之和（返回下标）
来源：http://dali.yongpay.top/Article/details/gtzmdfbzaj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.mhx1999.top/Article/details/gtqrtlcgmw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhongyouzk.top/Article/details/gtuvhfimfu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yj202588.top/Article/details/gtcgsrlflb.html

TS:   // 手写 Map<string, number>
来源：http://dali.sweek.top/Article/details/gtbirwftxy.html

Java: // 手写 HashMap
来源：http://dali.gogol.net.cn/Article/details/gtrmfrotea.html

Go:   // 手写 map[int]int
来源：http://dali.9152youxi.cn/Article/details/gthqqmepfg.html

Ruby: // 手写 Hash
来源：http://dali.shanyushiyangkeji.top/Article/details/gthbmpjpfp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xziqi.cn/Article/details/gtvtvwhfzi.html

[N08] 生成全排列
来源：http://dali.zdqjudy.top/Article/details/gtsdjdoddy.html

Py:   itertools.permutations(arr)
来源：http://dali.shuidangran.top/Article/details/gtwpnanylp.html

PHP:  // 手写递归交换
来源：http://dali.nwbrower.top/Article/details/gtrbhywsuy.html

JS:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gtntlyylvu.html

TS:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gtkjgatmxi.html

Java: // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrjbypono.html

Go:   // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gtdghqonrl.html

Ruby: arr.permutation.to_a
来源：http://dali.jianghu66.top/Article/details/gtcsgqcfxp.html

C#:   // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gtzigivwix.html

[N09] 栈与队列
来源：http://dali.birdmap.top/Article/details/gtlmuybuyl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jiagoushi.top/Article/details/gtzjlsaaqq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yj20258.top/Article/details/gtotdwzbpj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ybcxt.top/Article/details/gtftkiultb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.chenjidiqi.icu/Article/details/gtziwhkskx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yongpay.top/Article/details/gtxlbyugav.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.chenzaomai.com/Article/details/gtjsfjzmui.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yuanzhike.top/Article/details/gtapowlkpa.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cashguo.top/Article/details/gtrfikqstr.html

[N10] 链表节点定义
来源：http://dali.zhongyouzk.top/Article/details/gtsepebdto.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sxryk.cn/Article/details/gtinwlwkcf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sysykeji.top/Article/details/gtcjsyumwu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ydzc1.top/Article/details/gtteekuspu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xylfe.cn/Article/details/gtoeqaesye.html

Java: class Node { int v; Node next; }
来源：http://dali.9152youxi.cn/Article/details/gtanxstdju.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xinyue.icu/Article/details/gtqlfbndud.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yj202588.top/Article/details/gtiktavkzd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gogol.net.cn/Article/details/gtagtmhgyg.html

[N11] 二叉树中序遍历
来源：http://dali.quarkkingdee.top/Article/details/gtpvffzqyc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gaohongyu789.top/Article/details/gtmgxjwcui.html

PHP:  // 手写递归函数
来源：http://dali.cdnleiting.top/Article/details/gtjiszddua.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.redwolf501.top/Article/details/gtkidmyolj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shangyingyoupin.top/Article/details/gtwjrufipl.html

Java: // 手写递归
来源：http://dali.9152youxi.cn/Article/details/gtzrrmlbyw.html

Go:   // 手写递归
来源：http://dali.cucudq.cn/Article/details/gtldqadbss.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yj20258888.top/Article/details/gtqrocqdxz.html

C#:   // 手写递归
来源：http://dali.xziqi.cn/Article/details/gtoqqixueh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hfpthk.cn/Article/details/gtvspazbcp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yvedp.cn/Article/details/gtsqgwpibd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xziqi.cn/Article/details/gtnygctpqc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuanzhike.top/Article/details/gtqitygzsg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cdnleiting.top/Article/details/gtdxobesnb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tian-w.cn/Article/details/gtkmjjpfag.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zdqjudy.top/Article/details/gtfayaixfl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yonumen.top/Article/details/gtuihxoebx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.dianchejie.cn/Article/details/gtmatzmvre.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtejgzfdum.html

O. 并发与异步
来源：http://dali.hammf.cn/Article/details/gtexlzfqej.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtpujfsgas.html

[O01] 启动一个线程
来源：http://dali.yuxming.cn/Article/details/gtfthxsogy.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cucudq.cn/Article/details/gtnthiemgz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.guannengcc.top/Article/details/gtvkgeagpn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.daria6918.cn/Article/details/gtnekktfcb.html

TS:   // 同 JS
来源：http://dali.gotoacloud.top/Article/details/gtfftlbtoq.html

Java: new Thread(() -> f()).start()
来源：http://dali.hysaishi.cn/Article/details/gtwlrbthxt.html

Go:   go f()
来源：http://dali.bjfxy.top/Article/details/gttiyzoziw.html

Ruby: Thread.new { f }
来源：http://dali.ydzc1.top/Article/details/gtlnbdsxxp.html

C#:   Task.Run(() => F());
来源：http://dali.shuidangran.top/Article/details/gtfdwpywum.html

[O02] 使用线程池
来源：http://dali.chenlongwang.top/Article/details/gttbdtwjla.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xuanzx.com/Article/details/gtroykuccm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.fzhhl.top/Article/details/gtaclnmykc.html

JS:   // worker_threads 线程池
来源：http://dali.xinyue.icu/Article/details/gtujnqztop.html

TS:   // worker_threads 线程池
来源：http://dali.xziqi.cn/Article/details/gtxkvfoegx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.gogol.net.cn/Article/details/gtwrnatlsp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.nwbrower.top/Article/details/gtmrvjcfsi.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.andypj.xyz/Article/details/gtjqdcatib.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yonumen.top/Article/details/gtutrsiyiu.html

[O03] 加锁保护共享数据
来源：http://dali.yonumen.top/Article/details/gtryrnsmzf.html

Py:   with lock: shared += 1
来源：http://dali.nanxinkj.top/Article/details/gtkotxlfwg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.bjfxy.top/Article/details/gtpwmpnmzn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.wangdashe.top/Article/details/gtsfddaigk.html

TS:   // 同 JS
来源：http://dali.ehwqpu.com/Article/details/gtzjwnloyw.html

Java: synchronized (this) { shared++; }
来源：http://dali.tanke756.top/Article/details/gtqvjkzwco.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jlsjyb.cn/Article/details/gtqaiopspg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zdqjudy.top/Article/details/gtuyaxhcuk.html

C#:   lock (gate) { shared++; }
来源：http://dali.0kj1m.cn/Article/details/gtphybgqbe.html

[O04] 定义异步函数并等待
来源：http://dali.wangdashe.top/Article/details/gtibspfkxt.html

Py:   async def f():⏎    await g()
来源：http://dali.meibo888.top/Article/details/gtxzpzhfmj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jqgufenzy.top/Article/details/gtlyqfkntd.html

JS:   async function f() { await g(); }
来源：http://dali.xziqi.cn/Article/details/gtlrutxopt.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.smart0.xyz/Article/details/gtvpcqvebm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.quarkkingdee.top/Article/details/gtsohfhcgi.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.wangshuangyany.cn/Article/details/gtoggbwbcq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.fzhhl.top/Article/details/gtsivbncfc.html

C#:   async Task F() { await G(); }
来源：http://dali.yangfankeji.com/Article/details/gtjkqfuqgy.html

[O05] 并发执行并等待全部完成
来源：http://dali.vqdsnc.cn/Article/details/gtduhvgzds.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhoulong.xyz/Article/details/gtfykmhfgc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ydzc1.top/Article/details/gtsgnwiopa.html

JS:   await Promise.all(tasks)
来源：http://dali.xinyue.icu/Article/details/gtwobvmynx.html

TS:   await Promise.all(tasks)
来源：http://dali.sxryk.cn/Article/details/gthwrwnicl.html


<!-- 参考信息 -->