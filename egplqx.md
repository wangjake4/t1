代发 wailian999

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.bjfxy.top/Article/details/gtmtifvyqy.html

JS:   await fetch(url)
来源：http://dali.9152youxi.cn/Article/details/gtkdhvlklb.html

TS:   await fetch(url)
来源：http://dali.ehwqpu.com/Article/details/gtnrmyuszx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sufxvd.cn/Article/details/gtupriaoes.html

Go:   resp, err := http.Get(url)
来源：http://dali.sufxvd.cn/Article/details/gtqqjwjtlc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zdqjudy.top/Article/details/gtptkoatup.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shzxlz.cn/Article/details/gtkednfhkr.html

[L02] 发送 POST JSON
来源：http://dali.chenlongwang.top/Article/details/gtwmhflmhy.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jiagoushi.top/Article/details/gtuczsevkm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.iojbl.cn/Article/details/gtrcnhwvfi.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hongshengwenyu.top/Article/details/gtbawupndg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.bjfxy.top/Article/details/gtqcfsseio.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.meibo888.top/Article/details/gteeybhwed.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hfpthk.cn/Article/details/gtrminimkv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hywenlv.cn/Article/details/gtasaqqrbh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.svipenyu.cn/Article/details/gtdhdhbuag.html

[L03] 设置自定义请求头
来源：http://dali.zycfv.cn/Article/details/gtsmgrzgvm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtemfrnona.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.meibo888.top/Article/details/gtauogzpeh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuetiantiany.cn/Article/details/gtlasgkuqt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.birdmap.top/Article/details/gtcnzhlvki.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.feifeiyinyue.top/Article/details/gtbdpeovvd.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cqqwz.cn/Article/details/gtpkmtimep.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.9152youxi.cn/Article/details/gtffbtibkx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gzhubu.top/Article/details/gtqpolnqrb.html

[L04] 设置超时
来源：http://dali.xziqi.cn/Article/details/gtldapsbqk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.andypj.xyz/Article/details/gtwqjiwbyu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sysykeji.top/Article/details/gtnmeoayrk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.bjfxy.top/Article/details/gtmosckjrs.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sufxvd.cn/Article/details/gtkimjciwo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.andypj.xyz/Article/details/gtvfedousr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.nwbrower.top/Article/details/gtvvoeqbes.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hfpthk.cn/Article/details/gtljjjbyrq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhongyouzk.top/Article/details/gtgfvydszd.html

[L05] 上传文件（multipart）
来源：http://dali.jqgufenzy.top/Article/details/gtcogtsrzr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nwbrower.top/Article/details/gtuoejtlgt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.redwolf501.top/Article/details/gtnwtuhruq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sweek.top/Article/details/gtiliqzofi.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.mhx1999.top/Article/details/gtdyzpvmbo.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.tanke756.top/Article/details/gtamzgrqqx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cucudq.cn/Article/details/gtwzcgcpuq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jlsjyb.cn/Article/details/gttyvrfsvq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.meibo888.top/Article/details/gtwyrprvxs.html

[L06] 解析响应为 JSON
来源：http://dali.316326.xyz/Article/details/gtjgnwytuk.html

Py:   resp.json()
来源：http://dali.snrcjt.cn/Article/details/gtegrxhvkt.html

PHP:  json_decode($body, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfvqmnuui.html

JS:   await resp.json()
来源：http://dali.hongshengwenyu.top/Article/details/gtcnbdjtfa.html

TS:   await resp.json()
来源：http://dali.ydzc1.top/Article/details/gtyhziugxj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gtrgfztrwn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.chenzaomai.com/Article/details/gtndcznmkx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.smart0.xyz/Article/details/gtuacnqzeh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cashguo.top/Article/details/gtbcubznhj.html

[L07] 处理 HTTP 状态码
来源：http://dali.ehwqpu.com/Article/details/gtsghftglu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nanxinkj.top/Article/details/gtnljpyywi.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jlsjyb.cn/Article/details/gtzrlzyklw.html

JS:   resp.ok;  resp.status
来源：http://dali.gogol.net.cn/Article/details/gtilgiirvx.html

TS:   resp.ok;  resp.status
来源：http://dali.shuidangran.top/Article/details/gtfbizmxvs.html

Java: resp.statusCode()
来源：http://dali.tanke756.top/Article/details/gtbxnhvojj.html

Go:   resp.StatusCode
来源：http://dali.birdmap.top/Article/details/gtoitnocxd.html

Ruby: resp.code.to_i
来源：http://dali.hfpthk.cn/Article/details/gtmoflbxep.html

C#:   (int)resp.StatusCode
来源：http://dali.yangfankeji.com/Article/details/gtaynbzgsz.html

[L08] 并发请求多个地址
来源：http://dali.hnqzz.top/Article/details/gtjqwdsext.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.birdmap.top/Article/details/gtgulzqevz.html

PHP:  curl_multi_init() 系列
来源：http://dali.aibaodan.cn/Article/details/gtjtyrzmue.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sufxvd.cn/Article/details/gtzqrjrjto.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.bjfxy.top/Article/details/gtaooejzzy.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.chenzaomai.com/Article/details/gtoounroyo.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.svipenyu.cn/Article/details/gtkspyhyyq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xuetiantiany.cn/Article/details/gtdroloxug.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.dianchejie.cn/Article/details/gtgngzxzok.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtbhcmidbz.html

M. 命令行 / 进程 / 环境
来源：http://dali.hnqzz.top/Article/details/gtuxtrhlbl.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtrsbooczn.html

[M01] 读取命令行参数
来源：http://dali.yuanzhike.top/Article/details/gtrhxaswgg.html

Py:   sys.argv[1:]
来源：http://dali.smart0.xyz/Article/details/gtbczuqtfe.html

PHP:  $argv;  $argc;
来源：http://dali.shuidangran.top/Article/details/gtuafmcanx.html

JS:   process.argv.slice(2)
来源：http://dali.havefunace.top/Article/details/gtddoftwqt.html

TS:   process.argv.slice(2)
来源：http://dali.haohaochexian.top/Article/details/gthnhrwrvk.html

Java: args 数组（main 方法参数）
来源：http://dali.cdnleiting.top/Article/details/gtuhedcdwz.html

Go:   os.Args[1:]
来源：http://dali.zhongyouzk.top/Article/details/gthdqvjnru.html

Ruby: ARGV
来源：http://dali.gotoacloud.top/Article/details/gtqmtlcyeo.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yvedp.cn/Article/details/gtpyzqdqtw.html

[M02] 读取环境变量
来源：http://dali.zhixingplan.top/Article/details/gtvjuzngaw.html

Py:   os.environ.get("HOME")
来源：http://dali.9152youxi.cn/Article/details/gtksangmhk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.aibaodan.cn/Article/details/gthprgidxd.html

JS:   process.env.HOME
来源：http://dali.jiagoushi.top/Article/details/gtpxtwvare.html

TS:   process.env.HOME
来源：http://dali.9152youxi.cn/Article/details/gtmkgvmnng.html

Java: System.getenv("HOME")
来源：http://dali.cqqwz.cn/Article/details/gtjeqxfuxl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xylfe.cn/Article/details/gtpbdgvcoe.html

Ruby: ENV["HOME"]
来源：http://dali.nanxinkj.top/Article/details/gtjmywxjbt.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.smart0.xyz/Article/details/gtxnmjwvvx.html

[M03] 执行外部命令
来源：http://dali.9152youxi.cn/Article/details/gtwhqbdcyx.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.iojbl.cn/Article/details/gtoxxaqfly.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.wangdashe.top/Article/details/gtvdtvddjo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hysaishi.cn/Article/details/gtbpfptxrv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yvedp.cn/Article/details/gtaswrohkv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shuidangran.top/Article/details/gtwtrvgzqa.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.dashuyun.cn/Article/details/gtdfgelekw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.316326.xyz/Article/details/gtntuurady.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zycfv.cn/Article/details/gtuesmznvw.html

[M04] 获取当前工作目录
来源：http://dali.chenjidiqi.icu/Article/details/gtilxevlux.html

Py:   os.getcwd()
来源：http://dali.zhengqikj.top/Article/details/gtxsfddfpz.html

PHP:  getcwd();
来源：http://dali.yuanzhike.top/Article/details/gtigemdzgj.html

JS:   process.cwd()
来源：http://dali.zhoulong.xyz/Article/details/gtqdlnakxh.html

TS:   process.cwd()
来源：http://dali.chenjidiqi.icu/Article/details/gtmvuukfus.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.tianlin.xyz/Article/details/gtuenbfprb.html

Go:   os.Getwd()
来源：http://dali.pycfn.com/Article/details/gtpoiprggg.html

Ruby: Dir.pwd
来源：http://dali.sysykeji.top/Article/details/gtwxnbleia.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhengqikj.top/Article/details/gtknkqidij.html

[M05] 设置退出码
来源：http://dali.jinqigufen.top/Article/details/gthipopdfe.html

Py:   sys.exit(1)
来源：http://dali.cashguo.top/Article/details/gtwaljyiga.html

PHP:  exit(1);
来源：http://dali.xylfe.cn/Article/details/gtefcsykfg.html

JS:   process.exit(1)
来源：http://dali.xuanzx.com/Article/details/gtatvpkkjo.html

TS:   process.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtiifgvqmo.html

Java: System.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtftkepudh.html

Go:   os.Exit(1)
来源：http://dali.aizwys.cn/Article/details/gtikdeglnd.html

Ruby: exit 1
来源：http://dali.ppjwa.cn/Article/details/gtrjrtscjl.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.wangshuangyany.cn/Article/details/gtwmwcdhbh.html

[M06] 向标准错误输出
来源：http://dali.snrcjt.cn/Article/details/gtvibyqkwo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cheryme.top/Article/details/gtzpjbzxzv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gotoacloud.top/Article/details/gtdzorflmf.html

JS:   console.error("err")
来源：http://dali.yanxiufei.cn/Article/details/gtgctlsbur.html

TS:   console.error("err")
来源：http://dali.ybcxt.top/Article/details/gtxvfbboqs.html

Java: System.err.println("err")
来源：http://dali.feifeiyinyue.top/Article/details/gtrgldnrlf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xuetiantiany.cn/Article/details/gtvxebzcxf.html

Ruby: warn "err"
来源：http://dali.shangyingyoupin.top/Article/details/gteccbqyjp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yj202588.top/Article/details/gtatqnrwle.html

[M07] 判断是否为主入口
来源：http://dali.iojbl.cn/Article/details/gtygtpqnfs.html

Py:   if __name__ == "__main__":
来源：http://dali.mhx1999.top/Article/details/gthbhgbmib.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.haohaochexian.top/Article/details/gtskqgiwrw.html

JS:   require.main === module
来源：http://dali.xinyue.icu/Article/details/gtuaynphup.html

TS:   require.main === module
来源：http://dali.smart0.xyz/Article/details/gthrqvwuut.html

Java: public static void main(String[] args)
来源：http://dali.shzxlz.cn/Article/details/gtrzrpfeic.html

Go:   func main()
来源：http://dali.tian-w.cn/Article/details/gtuxwveqvt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yvedp.cn/Article/details/gtqyalumld.html

C#:   static void Main(string[] args)
来源：http://dali.shzxlz.cn/Article/details/gtxpvlptwz.html

[M08] 获取系统与运行时信息
来源：http://dali.hnqzz.top/Article/details/gtibzudkna.html

Py:   platform.system();  platform.python_version()
来源：http://dali.aibaodan.cn/Article/details/gtypjpgksp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.fengsongda.top/Article/details/gtfjtxwrdx.html

JS:   process.platform;  process.version
来源：http://dali.fzhhl.top/Article/details/gtiwqucleh.html

TS:   process.platform;  process.version
来源：http://dali.pengpengdd.cyou/Article/details/gttwhttibu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xuanzx.com/Article/details/gthqllzflr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.guannengcc.top/Article/details/gtnolpzeoq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.dashuyun.cn/Article/details/gtzrrowrif.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shanyushiyangtech.top/Article/details/gtbppbwwmy.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtwicfhylr.html

N. 数据结构与算法
来源：http://dali.xuetiantiany.cn/Article/details/gtrynirvgi.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtygdxrtlw.html

[N01] 二分查找（有序数组）
来源：http://dali.bjfxy.top/Article/details/gtbygyaxnz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgszdlfhb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.snrcjt.cn/Article/details/gtluevznus.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ehwqpu.com/Article/details/gtejemvcun.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fengsongda.top/Article/details/gtnqawqrtx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.tanke756.top/Article/details/gtpecdcfnq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtpbgjiqko.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yangfankeji.com/Article/details/gtamhfcecn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtgqavpzxc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zdqjudy.top/Article/details/gtwrgudsvv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.9152youxi.cn/Article/details/gtegkphjqc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sxryk.cn/Article/details/gtyeatpkxi.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pycfn.com/Article/details/gtyojndqtu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yvedp.cn/Article/details/gtrehptvhz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqgasdbet.html

Go:   slices.Sort(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtrttjahqp.html

Ruby: arr.sort
来源：http://dali.c1oappe.top/Article/details/gtntfdgwko.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.smart0.xyz/Article/details/gtrklzqzko.html

[N03] 快速排序（分治示例）
来源：http://dali.iojbl.cn/Article/details/gtkugmcpas.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfltjrxrh.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zdqjudy.top/Article/details/gtzcqfofxz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuxming.cn/Article/details/gtjhjzpmrm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cqqwz.cn/Article/details/gtfsmwbmnf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.bjfxy.top/Article/details/gtmegqnspy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shzxlz.cn/Article/details/gtvviavvex.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xuanzx.com/Article/details/gthuxdidzx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.svipenyu.cn/Article/details/gtlkcshxjo.html

[N04] 斐波那契数列
来源：http://dali.guowangkeji.top/Article/details/gtfsaagzgz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hfpthk.cn/Article/details/gtlonzurrx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xuanzx.com/Article/details/gthpiajuil.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ybcxt.top/Article/details/gtmlwqafjl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xylfe.cn/Article/details/gtyopewnoe.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtceqaixiy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.havefunace.top/Article/details/gtwekisolr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xylfe.cn/Article/details/gtyxrnmwqc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jlsjyb.cn/Article/details/gtozdqntaw.html

[N05] 最大公约数
来源：http://dali.svipenyu.cn/Article/details/gtnpsddlfh.html

Py:   math.gcd(a, b)
来源：http://dali.cashguo.top/Article/details/gtiuyxyswq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.bjfxy.top/Article/details/gtweeanirv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdivgaipd.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlfgmmnrw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yuanzhike.top/Article/details/gtekxnqgjq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.aibaodan.cn/Article/details/gtxbjhmztw.html

Ruby: a.gcd(b)
来源：http://dali.c1oappe.top/Article/details/gtlswsbech.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gogol.net.cn/Article/details/gtidvsrbkl.html

[N06] 判断回文字符串
来源：http://dali.yueranfly.top/Article/details/gtcwqarxri.html

Py:   s == s[::-1]
来源：http://dali.wangdashe.top/Article/details/gtfoqedbtc.html

PHP:  $s === strrev($s);
来源：http://dali.zhongyouzk.top/Article/details/gtsbfxcxis.html

JS:   s === [...s].reverse().join("")
来源：http://dali.vqdsnc.cn/Article/details/gtebmwrwuv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gtxpefxcxw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sxryk.cn/Article/details/gtbawuuctc.html

Go:   // 双指针从两端比较
来源：http://dali.gzhubu.top/Article/details/gtveomnpfx.html

Ruby: s == s.reverse
来源：http://dali.jqgufenzy.top/Article/details/gtgunvmnvk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.fzhhl.top/Article/details/gthwenbham.html

[N07] 两数之和（返回下标）
来源：http://dali.0kj1m.cn/Article/details/gtxjktbwlz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.tian-w.cn/Article/details/gtyfkwyast.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.birdmap.top/Article/details/gtposlumyj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ydzc1.top/Article/details/gtynrjtwnm.html

TS:   // 手写 Map<string, number>
来源：http://dali.vqdsnc.cn/Article/details/gtvbnqnrpc.html

Java: // 手写 HashMap
来源：http://dali.ehwqpu.com/Article/details/gtsgrazdzc.html

Go:   // 手写 map[int]int
来源：http://dali.gaohongyu789.top/Article/details/gtwntbwvek.html

Ruby: // 手写 Hash
来源：http://dali.zycfv.cn/Article/details/gtzmqisjdn.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hnxiangtu.top/Article/details/gtpyojyzfq.html

[N08] 生成全排列
来源：http://dali.shanyushiyangtech.top/Article/details/gtymmoaauc.html

Py:   itertools.permutations(arr)
来源：http://dali.jqgfzy.top/Article/details/gtzsagudjo.html

PHP:  // 手写递归交换
来源：http://dali.xinyue.icu/Article/details/gtjxpmilbq.html

JS:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtmqqkdawd.html

TS:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gthlkugsou.html

Java: // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gtsouuoyhe.html

Go:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gtrzljmedn.html

Ruby: arr.permutation.to_a
来源：http://dali.cheryme.top/Article/details/gtvghwalhc.html

C#:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtyxfzolwf.html

[N09] 栈与队列
来源：http://dali.birdmap.top/Article/details/gtjezfljng.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.fengsongda.top/Article/details/gtwoxndqbt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sufxvd.cn/Article/details/gtmyrdtstu.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sxryk.cn/Article/details/gtxrmnxfdy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.0kj1m.cn/Article/details/gttewjxmty.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hongshengwenyu.top/Article/details/gteikiobkn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.fzhhl.top/Article/details/gtuobuojfu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gttejsoetj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gogol.net.cn/Article/details/gtejtdzaim.html

[N10] 链表节点定义
来源：http://dali.yongpay.top/Article/details/gthovdnxcs.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jiagoushi.top/Article/details/gtstrdpcic.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hnxiangtu.top/Article/details/gtermtcrdw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.tian-w.cn/Article/details/gtfygpyxia.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gtvsijezyf.html

Java: class Node { int v; Node next; }
来源：http://dali.jinqigfzy.top/Article/details/gtularlnjy.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.tianlin.xyz/Article/details/gtvsgrdofa.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.wangshuangyany.cn/Article/details/gtzakwyjqq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.chenjidiqi.icu/Article/details/gtbjeuygbr.html

[N11] 二叉树中序遍历
来源：http://dali.gogol.net.cn/Article/details/gtkqnwotvo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoetohhqs.html

PHP:  // 手写递归函数
来源：http://dali.hywenlv.cn/Article/details/gtcvzxzzko.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xuanzx.com/Article/details/gtcpuaealu.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxiysweud.html

Java: // 手写递归
来源：http://dali.nwbrower.top/Article/details/gtmcfvhvrm.html

Go:   // 手写递归
来源：http://dali.ppjwa.cn/Article/details/gtyjkslmwd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkcondgim.html

C#:   // 手写递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtvrhugxoa.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.quarkkingdee.top/Article/details/gtpmmcbcsc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yuxming.cn/Article/details/gtdsbvjxcp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yanxiufei.cn/Article/details/gtkzkeuezz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhengqikj.top/Article/details/gttjbdltbm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenzaomai.com/Article/details/gtkxbexfnc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenlongwang.top/Article/details/gtertfdvit.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.wangshuangyany.cn/Article/details/gtnjpopoys.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sweek.top/Article/details/gtgwgwgqsd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.iojbl.cn/Article/details/gtsuwcyjcg.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtueouovmj.html

O. 并发与异步
来源：http://dali.ehwqpu.com/Article/details/gtlnrlcecs.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtcxuxlgqh.html

[O01] 启动一个线程
来源：http://dali.kuanghao11.cn/Article/details/gtgywepave.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xinyue.icu/Article/details/gtpkovhhyh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cashguo.top/Article/details/gtnmiekkbr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gogol.net.cn/Article/details/gtjkaoepku.html

TS:   // 同 JS
来源：http://dali.yj20258888.top/Article/details/gtbthrtmex.html

Java: new Thread(() -> f()).start()
来源：http://dali.sysykeji.top/Article/details/gtsefkomwb.html

Go:   go f()
来源：http://dali.cheryme.top/Article/details/gtcnxggcmk.html

Ruby: Thread.new { f }
来源：http://dali.feifeiyinyue.top/Article/details/gtgqmymxgr.html

C#:   Task.Run(() => F());
来源：http://dali.nanxinkj.top/Article/details/gtdvganxkz.html

[O02] 使用线程池
来源：http://dali.redwolf501.top/Article/details/gtecwxewef.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yj20258.top/Article/details/gtsrscjqhm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvjfsrbyr.html

JS:   // worker_threads 线程池
来源：http://dali.hammf.cn/Article/details/gtyzshncbm.html

TS:   // worker_threads 线程池
来源：http://dali.gaohongyu789.top/Article/details/gthbforzop.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yanxiufei.cn/Article/details/gttbxjlbjf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhengqikj.top/Article/details/gtbhlhcxvv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yj20258888.top/Article/details/gtvicfzahz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shuidangran.top/Article/details/gtdatgmamh.html

[O03] 加锁保护共享数据
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgsvuzyrg.html

Py:   with lock: shared += 1
来源：http://dali.fzhhl.top/Article/details/gtozfqkddm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhiwuduotai.top/Article/details/gtkfjcpllk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.9152youxi.cn/Article/details/gtjhvqmaal.html

TS:   // 同 JS
来源：http://dali.nanxuanxn.top/Article/details/gtzwkddkic.html

Java: synchronized (this) { shared++; }
来源：http://dali.guowangkeji.top/Article/details/gtvofjlaec.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hfpthk.cn/Article/details/gtxfyjpgeo.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hongshengwenyu.top/Article/details/gtsgvwovpc.html

C#:   lock (gate) { shared++; }
来源：http://dali.tianlin.xyz/Article/details/gteosqtskx.html

[O04] 定义异步函数并等待
来源：http://dali.jianghu66.top/Article/details/gtartnjbqg.html

Py:   async def f():⏎    await g()
来源：http://dali.iojbl.cn/Article/details/gtqxlfnmpd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.daxiang520.top/Article/details/gtgxphcohc.html

JS:   async function f() { await g(); }
来源：http://dali.guowangkeji.top/Article/details/gtbadclkrj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.aibaodan.cn/Article/details/gtkvduuqbk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.nanxuanxn.top/Article/details/gtdshvfmdh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinghuilouyu.cn/Article/details/gtwvmtxoio.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shanyushiyangtech.top/Article/details/gtzitzgnck.html

C#:   async Task F() { await G(); }
来源：http://dali.ehwqpu.com/Article/details/gtirsncodj.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinqigufen.top/Article/details/gtotrdxpue.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shanyushiyangtech.top/Article/details/gtccgwqfyq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yangfankeji.com/Article/details/gtbyqmrgcj.html

JS:   await Promise.all(tasks)
来源：http://dali.hnqzz.top/Article/details/gtsyycquia.html

TS:   await Promise.all(tasks)
来源：http://dali.shuidangran.top/Article/details/gtzychgkad.html


<!-- 参考信息 -->