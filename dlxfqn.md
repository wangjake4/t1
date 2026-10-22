代发 wailian999

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gtptvyluyc.html

Ruby: Marshal.dump(obj)
来源：http://dali.yonumen.top/Article/details/gtgrnsmmqq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.vqdsnc.cn/Article/details/gtcfcmppzd.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtcuqnsriu.html

L. 网络请求
来源：http://dali.shanyushiyangkeji.top/Article/details/gtceeqdcwi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtgeqmrncz.html

[L01] 发送 GET 请求
来源：http://dali.yongpay.top/Article/details/gtpkaarjll.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhaomingkeji.xyz/Article/details/gthkwjnwia.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhongyouzk.top/Article/details/gtrgatwnxc.html

JS:   await fetch(url)
来源：http://dali.vqdsnc.cn/Article/details/gtndwpxmvn.html

TS:   await fetch(url)
来源：http://dali.birdmap.top/Article/details/gtmyejxvyg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.daria6918.cn/Article/details/gtopcrnroj.html

Go:   resp, err := http.Get(url)
来源：http://dali.yj20258.top/Article/details/gtewfwbwyi.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shuidangran.top/Article/details/gtpxexkvnb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.haohaochexian.top/Article/details/gtiqsdcrft.html

[L02] 发送 POST JSON
来源：http://dali.feifeiyinyue.top/Article/details/gttddmcwfl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.bjfxy.top/Article/details/gtdlzmgbpr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cdnleiting.top/Article/details/gtinyhstvm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jiagoushi.top/Article/details/gtfwfxdpzi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sufxvd.cn/Article/details/gtxrrvqxpt.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.tanke756.top/Article/details/gtvcdjghom.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hnxiangtu.top/Article/details/gtpmxiiuvs.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hnxiangtu.top/Article/details/gtwmwrkhwy.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shzxlz.cn/Article/details/gtfnysicqf.html

[L03] 设置自定义请求头
来源：http://dali.redwolf501.top/Article/details/gtmetccczl.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hnxiangtu.top/Article/details/gtrdetyipt.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmftmrjau.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ppjwa.cn/Article/details/gteqlterra.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.meibo888.top/Article/details/gthnltktxz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gaohongyu789.top/Article/details/gtpohgfrsh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.redwolf501.top/Article/details/gthutnxczh.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yongpay.top/Article/details/gtzmlrswxe.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hongshengwenyu.top/Article/details/gtrytiuoiu.html

[L04] 设置超时
来源：http://dali.jianghu66.top/Article/details/gtiihrjaga.html

Py:   requests.get(url, timeout=5)
来源：http://dali.wangdashe.top/Article/details/gtqzarpjhb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.0kj1m.cn/Article/details/gtagdnygfv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzmwnvpoc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkfgiinik.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xuanzx.com/Article/details/gtysodtjkb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jlsjyb.cn/Article/details/gtrfqjbmwt.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xziqi.cn/Article/details/gtcgbyvktb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbfermnmu.html

[L05] 上传文件（multipart）
来源：http://dali.jinqigfzy.top/Article/details/gtsczyqhmq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.svipenyu.cn/Article/details/gtgkvkvxtu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xuanzx.com/Article/details/gtkeupomuw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinyuanbaomall.cn/Article/details/gthojibkgu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.kuanghao11.cn/Article/details/gtwpztyqkj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jiagoushi.top/Article/details/gtxbmmmevm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.svipenyu.cn/Article/details/gtcebmdfue.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.c1oappe.top/Article/details/gtvtnnmxzq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yonumen.top/Article/details/gthldjtfdm.html

[L06] 解析响应为 JSON
来源：http://dali.redwolf501.top/Article/details/gtwtnzbccv.html

Py:   resp.json()
来源：http://dali.jinqigufen.top/Article/details/gtpcxgaige.html

PHP:  json_decode($body, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtsghxswel.html

JS:   await resp.json()
来源：http://dali.xziqi.cn/Article/details/gtrztbualr.html

TS:   await resp.json()
来源：http://dali.gzhubu.top/Article/details/gtrevwevfo.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yuxming.cn/Article/details/gtwtaeqjdb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.fengsongda.top/Article/details/gtsxsxttil.html

Ruby: JSON.parse(resp.body)
来源：http://dali.svipenyu.cn/Article/details/gtbujzvyey.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yangfankeji.com/Article/details/gtsiqfkmeh.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpgwlshmj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jlsjyb.cn/Article/details/gtsxxkvyqi.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cdnleiting.top/Article/details/gtujvwhsgr.html

JS:   resp.ok;  resp.status
来源：http://dali.fzhhl.top/Article/details/gtoqdwikyb.html

TS:   resp.ok;  resp.status
来源：http://dali.dashuyun.cn/Article/details/gtmgxlokvy.html

Java: resp.statusCode()
来源：http://dali.feifeiyinyue.top/Article/details/gtdektkvrp.html

Go:   resp.StatusCode
来源：http://dali.cqqwz.cn/Article/details/gtvroswmin.html

Ruby: resp.code.to_i
来源：http://dali.daria6918.cn/Article/details/gtsuotbthe.html

C#:   (int)resp.StatusCode
来源：http://dali.redwolf501.top/Article/details/gttgmuhnnq.html

[L08] 并发请求多个地址
来源：http://dali.chenzaomai.com/Article/details/gtvvfkwrkg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hnqzz.top/Article/details/gtzvunynrs.html

PHP:  curl_multi_init() 系列
来源：http://dali.quarkkingdee.top/Article/details/gtrwrlqekm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sxryk.cn/Article/details/gtpvksccbl.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sxryk.cn/Article/details/gtzkdwolmi.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhengqikj.top/Article/details/gtdmlrcahx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.daria6918.cn/Article/details/gtbqizhwvv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ydzc1.top/Article/details/gtfbpiuoka.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hnqzz.top/Article/details/gttznquepa.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtmxmpqkac.html

M. 命令行 / 进程 / 环境
来源：http://dali.hfpthk.cn/Article/details/gtatlqvilh.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtatfkagmm.html

[M01] 读取命令行参数
来源：http://dali.wangdashe.top/Article/details/gtehfwgcuw.html

Py:   sys.argv[1:]
来源：http://dali.hywenlv.cn/Article/details/gtmzzaudwo.html

PHP:  $argv;  $argc;
来源：http://dali.feifeiyinyue.top/Article/details/gtogxfyafp.html

JS:   process.argv.slice(2)
来源：http://dali.cashguo.top/Article/details/gtpbyefsvl.html

TS:   process.argv.slice(2)
来源：http://dali.birdmap.top/Article/details/gtsgsxptug.html

Java: args 数组（main 方法参数）
来源：http://dali.yj20258.top/Article/details/gtuelrsqir.html

Go:   os.Args[1:]
来源：http://dali.aizwys.cn/Article/details/gtpjcwhnzv.html

Ruby: ARGV
来源：http://dali.shanyushiyangkeji.top/Article/details/gtovhlcbmg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtszwckyqa.html

[M02] 读取环境变量
来源：http://dali.gzhubu.top/Article/details/gtnyswzpsi.html

Py:   os.environ.get("HOME")
来源：http://dali.0kj1m.cn/Article/details/gtwfthnznu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ybcxt.top/Article/details/gtopuiuomu.html

JS:   process.env.HOME
来源：http://dali.sufxvd.cn/Article/details/gtewzqbluf.html

TS:   process.env.HOME
来源：http://dali.jianghu66.top/Article/details/gtqqiquljn.html

Java: System.getenv("HOME")
来源：http://dali.cashguo.top/Article/details/gtccbglqtp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gzhubu.top/Article/details/gtgtrkswej.html

Ruby: ENV["HOME"]
来源：http://dali.zhongyouzk.top/Article/details/gtiusppbqr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.bjfxy.top/Article/details/gtqwbvlgvq.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gtizwyuuoq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.iojbl.cn/Article/details/gtskahookm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jyoumei.cn/Article/details/gtvsdnybni.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhoulong.xyz/Article/details/gtwikdgnvt.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tianlin.xyz/Article/details/gtvdaetlai.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.kuanghao11.cn/Article/details/gtvptprqbt.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nanxuanxn.top/Article/details/gtnrevmqsu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tian-w.cn/Article/details/gtekpwnmim.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gotoacloud.top/Article/details/gtnhnmllip.html

[M04] 获取当前工作目录
来源：http://dali.pengpengdd.cyou/Article/details/gtdcoapejl.html

Py:   os.getcwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtqiqwvurm.html

PHP:  getcwd();
来源：http://dali.jinghuilouyu.cn/Article/details/gtnujbupjq.html

JS:   process.cwd()
来源：http://dali.haohaochexian.top/Article/details/gtlituqnyw.html

TS:   process.cwd()
来源：http://dali.sxryk.cn/Article/details/gtzykrfkkv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sufxvd.cn/Article/details/gtpaadgjhw.html

Go:   os.Getwd()
来源：http://dali.sxryk.cn/Article/details/gtmjbgkcwz.html

Ruby: Dir.pwd
来源：http://dali.yj20258888.top/Article/details/gtrajzwnfv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.bjfxy.top/Article/details/gtpkazvuuu.html

[M05] 设置退出码
来源：http://dali.redwolf501.top/Article/details/gthmuwplfh.html

Py:   sys.exit(1)
来源：http://dali.yongpay.top/Article/details/gtauqsyqhx.html

PHP:  exit(1);
来源：http://dali.andypj.xyz/Article/details/gtvuhcmlhx.html

JS:   process.exit(1)
来源：http://dali.yongpay.top/Article/details/gtjijfmqhj.html

TS:   process.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtxnimaexm.html

Java: System.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gtghjnskzf.html

Go:   os.Exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gtiulpvaaz.html

Ruby: exit 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtbdkzhxoo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.tian-w.cn/Article/details/gtmnarceem.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gtabcupgtb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.fzhhl.top/Article/details/gtkahuyvba.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yvedp.cn/Article/details/gtbyxlkjyo.html

JS:   console.error("err")
来源：http://dali.jianghu66.top/Article/details/gtxyeewmuz.html

TS:   console.error("err")
来源：http://dali.fengsongda.top/Article/details/gtpfxvbcfw.html

Java: System.err.println("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlxbffups.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.fzhhl.top/Article/details/gtfqhebxba.html

Ruby: warn "err"
来源：http://dali.bjfxy.top/Article/details/gtbphnwryp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.pycfn.com/Article/details/gtcoqaoztn.html

[M07] 判断是否为主入口
来源：http://dali.hongshengwenyu.top/Article/details/gtfuujyvjm.html

Py:   if __name__ == "__main__":
来源：http://dali.nanxinkj.top/Article/details/gttzjkejdr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.meibo888.top/Article/details/gtbidrgkzb.html

JS:   require.main === module
来源：http://dali.yuxming.cn/Article/details/gtdfuggrwa.html

TS:   require.main === module
来源：http://dali.birdmap.top/Article/details/gtnhvewtjc.html

Java: public static void main(String[] args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtciarnwdx.html

Go:   func main()
来源：http://dali.bjfxy.top/Article/details/gtjghvmkyd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hysaishi.cn/Article/details/gtfqtiurwx.html

C#:   static void Main(string[] args)
来源：http://dali.gotoacloud.top/Article/details/gtyvkuvoxi.html

[M08] 获取系统与运行时信息
来源：http://dali.iojbl.cn/Article/details/gtcnurhkwf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.aizwys.cn/Article/details/gtscglqsrl.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xinyue.icu/Article/details/gtsxqpszxc.html

JS:   process.platform;  process.version
来源：http://dali.zhiwuduotai.top/Article/details/gtqnelsxga.html

TS:   process.platform;  process.version
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnxcoixmf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtguragfad.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.dianchejie.cn/Article/details/gtcanwckke.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xziqi.cn/Article/details/gtkqwzcxol.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.guannengcc.top/Article/details/gtibaarnvy.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtquxluxoi.html

N. 数据结构与算法
来源：http://dali.shangyingyoupin.top/Article/details/gtvncmadhf.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtckkzhfrb.html

[N01] 二分查找（有序数组）
来源：http://dali.yj20258888.top/Article/details/gtxulhwrgr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtvyzhbeua.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.fzhhl.top/Article/details/gtbsiirnak.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nwbrower.top/Article/details/gtpyzfmcsz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sweek.top/Article/details/gtzypwjcqs.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtouagtxzv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtsdzkogcg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhixingplan.top/Article/details/gtmnxyqydx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtlyfixkny.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hammf.cn/Article/details/gtxxerfqra.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.c1oappe.top/Article/details/gtnowypzsb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xinyue.icu/Article/details/gtwycaxlym.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yonumen.top/Article/details/gtxtxypsoe.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fengsongda.top/Article/details/gtafgseisr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hongshengwenyu.top/Article/details/gtdfsmkjvk.html

Go:   slices.Sort(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtuyyuafoq.html

Ruby: arr.sort
来源：http://dali.quarkkingdee.top/Article/details/gtrzmcngzs.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xuetiantiany.cn/Article/details/gtscukqmeo.html

[N03] 快速排序（分治示例）
来源：http://dali.cucudq.cn/Article/details/gtwjythvnv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqmcjdeol.html

PHP:  // 递归实现，或用 usort
来源：http://dali.birdmap.top/Article/details/gtifcrkube.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aibaodan.cn/Article/details/gtwlvjmblp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangkeji.top/Article/details/gttcmskuzz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj20258.top/Article/details/gtgrniztke.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.pycfn.com/Article/details/gtyilvpfnn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.guannengcc.top/Article/details/gtbxobwoak.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gtndjftako.html

[N04] 斐波那契数列
来源：http://dali.birdmap.top/Article/details/gtfiketaxd.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nanxuanxn.top/Article/details/gtpqiouppk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj20258888.top/Article/details/gtelhmlhbc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hysaishi.cn/Article/details/gtsghlirpt.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtffzfvrjv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.meibo888.top/Article/details/gtspckyfoq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jqgfzy.top/Article/details/gtdqmamabd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jqgufenzy.top/Article/details/gtmpdknocg.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gtqwdgjhto.html

[N05] 最大公约数
来源：http://dali.cheryme.top/Article/details/gtpjamiyub.html

Py:   math.gcd(a, b)
来源：http://dali.sxryk.cn/Article/details/gtetzzogcv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.birdmap.top/Article/details/gtavrzshvp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.9152youxi.cn/Article/details/gtdtgjzjfd.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnxiangtu.top/Article/details/gtyacbqgqd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.mhx1999.top/Article/details/gtaaqcuupd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinqigfzy.top/Article/details/gtbnhsvqei.html

Ruby: a.gcd(b)
来源：http://dali.gaohongyu789.top/Article/details/gtrpcdyazy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnwfqdjwd.html

[N06] 判断回文字符串
来源：http://dali.ppjwa.cn/Article/details/gtdjiqqprk.html

Py:   s == s[::-1]
来源：http://dali.hfpthk.cn/Article/details/gtmjxaehig.html

PHP:  $s === strrev($s);
来源：http://dali.cashguo.top/Article/details/gtrwlnhjvf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gttpootldp.html

TS:   s === [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gtpvzvtujq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.0kj1m.cn/Article/details/gtuulvimhq.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gtiiboocdb.html

Ruby: s == s.reverse
来源：http://dali.yj202588.top/Article/details/gtudfrdtzs.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.wangdashe.top/Article/details/gtcwubghxe.html

[N07] 两数之和（返回下标）
来源：http://dali.xinyue.icu/Article/details/gtsjexmhcd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.kuanghao11.cn/Article/details/gthtxmfqng.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jqgfzy.top/Article/details/gtfamenqzf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.tian-w.cn/Article/details/gtctvnykyj.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhiwuduotai.top/Article/details/gtmceoizko.html

Java: // 手写 HashMap
来源：http://dali.nwbrower.top/Article/details/gtffvtvgth.html

Go:   // 手写 map[int]int
来源：http://dali.kuanghao11.cn/Article/details/gtsdxqbajm.html

Ruby: // 手写 Hash
来源：http://dali.feifeiyinyue.top/Article/details/gtwmamsfno.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.guowangkeji.top/Article/details/gtzazszwns.html

[N08] 生成全排列
来源：http://dali.cdnleiting.top/Article/details/gtsxcnwnjx.html

Py:   itertools.permutations(arr)
来源：http://dali.tian-w.cn/Article/details/gtepleaeew.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gtqzxgleig.html

JS:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gtpjbmqfni.html

TS:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gtkxdpirwf.html

Java: // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtiukkvtxr.html

Go:   // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gtxvrsdnof.html

Ruby: arr.permutation.to_a
来源：http://dali.jqgfzy.top/Article/details/gtrkyzsvij.html

C#:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gtnlvjaoin.html

[N09] 栈与队列
来源：http://dali.shzxlz.cn/Article/details/gtqfilahes.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hammf.cn/Article/details/gtqjsexhqm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jlsjyb.cn/Article/details/gteapwfrny.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sweek.top/Article/details/gtizqfclwh.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ivvv.top/Article/details/gtgibntdnp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yvedp.cn/Article/details/gtxwxozxhm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hammf.cn/Article/details/gtuowssuoh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.daria6918.cn/Article/details/gtokyidyst.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.feifeiyinyue.top/Article/details/gtvklwdgqd.html

[N10] 链表节点定义
来源：http://dali.zhongyouzk.top/Article/details/gtvhlsnkat.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.quarkkingdee.top/Article/details/gtoenxhgws.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shuidangran.top/Article/details/gtcrjmzmoq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cashguo.top/Article/details/gtvpzcktob.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.316326.xyz/Article/details/gtjbmxulys.html

Java: class Node { int v; Node next; }
来源：http://dali.jiagoushi.top/Article/details/gtjigauajr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.meibo888.top/Article/details/gthekirkue.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gzhubu.top/Article/details/gtvaebragc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.316326.xyz/Article/details/gtewaeqvjm.html

[N11] 二叉树中序遍历
来源：http://dali.cdnleiting.top/Article/details/gtcmmzfrkx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.meibo888.top/Article/details/gtdtoeofsw.html

PHP:  // 手写递归函数
来源：http://dali.hnxiangtu.top/Article/details/gtwoestavy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daria6918.cn/Article/details/gtcmxswlek.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gzhubu.top/Article/details/gtlsqzbkvv.html

Java: // 手写递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjhmzmupi.html

Go:   // 手写递归
来源：http://dali.ivvv.top/Article/details/gtqmneniqs.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jianghu66.top/Article/details/gtucwswqhb.html

C#:   // 手写递归
来源：http://dali.chenlongwang.top/Article/details/gtrastaqwt.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.dashuyun.cn/Article/details/gtvgcnjzea.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hfpthk.cn/Article/details/gtwvepvpeg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yj202588.top/Article/details/gtbpesmqat.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xuanzx.com/Article/details/gtbjqieqje.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gogol.net.cn/Article/details/gtimnzacdt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zdqjudy.top/Article/details/gtkeuhxkii.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnzdfdwbb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gzhubu.top/Article/details/gtdrxybemo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.vqdsnc.cn/Article/details/gtxzttdxcr.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtfsnqjzgr.html

O. 并发与异步
来源：http://dali.cqqwz.cn/Article/details/gthozafdsr.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtnewjkcao.html

[O01] 启动一个线程
来源：http://dali.feifeiyinyue.top/Article/details/gtqozwksbm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.smart0.xyz/Article/details/gtuowghlbj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xylfe.cn/Article/details/gtfzcblnpn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xuanzx.com/Article/details/gtgpotdgwa.html

TS:   // 同 JS
来源：http://dali.hammf.cn/Article/details/gtcwsqubrb.html

Java: new Thread(() -> f()).start()
来源：http://dali.redwolf501.top/Article/details/gtpnxnpnpl.html

Go:   go f()
来源：http://dali.cdnleiting.top/Article/details/gtassowjdy.html

Ruby: Thread.new { f }
来源：http://dali.xinyue.icu/Article/details/gtarmepzkj.html

C#:   Task.Run(() => F());
来源：http://dali.chenlongwang.top/Article/details/gtawyilozq.html

[O02] 使用线程池
来源：http://dali.ehwqpu.com/Article/details/gtwrlohmmw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yuanzhike.top/Article/details/gtexdppxwh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xinyue.icu/Article/details/gtdchgtgsv.html

JS:   // worker_threads 线程池
来源：http://dali.jqgfzy.top/Article/details/gttszytara.html

TS:   // worker_threads 线程池
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqhtpkfjs.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbqntxbuz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cucudq.cn/Article/details/gtexxvbcvy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hfpthk.cn/Article/details/gtbeioqncc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.haohaochexian.top/Article/details/gtjjabxwan.html

[O03] 加锁保护共享数据
来源：http://dali.gaohongyu789.top/Article/details/gtufrwbrij.html

Py:   with lock: shared += 1
来源：http://dali.andypj.xyz/Article/details/gthuskueew.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jiagoushi.top/Article/details/gtsurveioj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.tianlin.xyz/Article/details/gtwajrfjtj.html

TS:   // 同 JS
来源：http://dali.ybcxt.top/Article/details/gtidkwrqaj.html

Java: synchronized (this) { shared++; }
来源：http://dali.yuanzhike.top/Article/details/gtcibjpjrd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sxryk.cn/Article/details/gthvrmovjj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ehwqpu.com/Article/details/gttdjlmjkb.html

C#:   lock (gate) { shared++; }
来源：http://dali.pycfn.com/Article/details/gtjklinbcv.html

[O04] 定义异步函数并等待
来源：http://dali.zhoulong.xyz/Article/details/gtxnmjfqul.html

Py:   async def f():⏎    await g()
来源：http://dali.tianlin.xyz/Article/details/gtqngxxwkj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xinyue.icu/Article/details/gtgygbejqv.html

JS:   async function f() { await g(); }
来源：http://dali.bjfxy.top/Article/details/gtijiqkhta.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yonumen.top/Article/details/gteymsrspb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.daxiang520.top/Article/details/gtuivzlota.html


<!-- 参考信息 -->