代发 wailian999

Go:   encoding/gob
来源：http://dali.tianlin.xyz/Article/details/gtzrkafkqi.html

Ruby: Marshal.dump(obj)
来源：http://dali.jiagoushi.top/Article/details/gtqnnewuil.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhoulong.xyz/Article/details/gtfvxubdzs.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtzrnppwnw.html

L. 网络请求
来源：http://dali.jinqigufen.top/Article/details/gtvcnveslu.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gthmivddzj.html

[L01] 发送 GET 请求
来源：http://dali.ppjwa.cn/Article/details/gtrrhhkyln.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hammf.cn/Article/details/gtgepmfnae.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.0kj1m.cn/Article/details/gtejwqwctd.html

JS:   await fetch(url)
来源：http://dali.sxryk.cn/Article/details/gthusldhae.html

TS:   await fetch(url)
来源：http://dali.andypj.xyz/Article/details/gtvhycsnem.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shuidangran.top/Article/details/gtoavrezyt.html

Go:   resp, err := http.Get(url)
来源：http://dali.xylfe.cn/Article/details/gtactpyzqk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.meibo888.top/Article/details/gtdjmtrpzt.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nwbrower.top/Article/details/gtkjjaskut.html

[L02] 发送 POST JSON
来源：http://dali.ivvv.top/Article/details/gtlwoudzgn.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.316326.xyz/Article/details/gtazuopdha.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhoulong.xyz/Article/details/gtcofonmev.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fzhhl.top/Article/details/gtwyojozam.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnqzz.top/Article/details/gtbydziqlq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yangfankeji.com/Article/details/gtwlemwgvo.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yvedp.cn/Article/details/gtkoqidvqf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jqgufenzy.top/Article/details/gtnvmnbqwu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hfpthk.cn/Article/details/gtylropeam.html

[L03] 设置自定义请求头
来源：http://dali.yongpay.top/Article/details/gttqesnhmv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.chenzaomai.com/Article/details/gtkwyggrev.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj20258888.top/Article/details/gtweftdsvk.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gtcysyvkos.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yongpay.top/Article/details/gtasjawkux.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtthbdpymv.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yuxming.cn/Article/details/gtfuifxoem.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.haohaochexian.top/Article/details/gtrcohlage.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.wangshuangyany.cn/Article/details/gtfdpadswu.html

[L04] 设置超时
来源：http://dali.chenjidiqi.icu/Article/details/gthvnpkous.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yuanzhike.top/Article/details/gtwehkzdwe.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.daxiang520.top/Article/details/gtgmvghywi.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.redwolf501.top/Article/details/gtfbushyjy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xylfe.cn/Article/details/gtdfiqmrhx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.iojbl.cn/Article/details/gtadpjjyoy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jqgfzy.top/Article/details/gtuwacxvoz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nwbrower.top/Article/details/gtuhrmtrma.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.birdmap.top/Article/details/gtkqnpuect.html

[L05] 上传文件（multipart）
来源：http://dali.ehwqpu.com/Article/details/gtlzmojuib.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ybcxt.top/Article/details/gtgcgrfaav.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gotoacloud.top/Article/details/gteqhzyqhx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gotoacloud.top/Article/details/gtvcwzfyfx.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfciyogrm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shuidangran.top/Article/details/gtkqozxuho.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sxryk.cn/Article/details/gtfeagxqdl.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinghuilouyu.cn/Article/details/gtxkofupyt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.316326.xyz/Article/details/gtwzxsvqbu.html

[L06] 解析响应为 JSON
来源：http://dali.cqqwz.cn/Article/details/gtynqczbpc.html

Py:   resp.json()
来源：http://dali.zhoulong.xyz/Article/details/gtpnbvkpmu.html

PHP:  json_decode($body, true);
来源：http://dali.zhixingplan.top/Article/details/gtikuwutdy.html

JS:   await resp.json()
来源：http://dali.cdnleiting.top/Article/details/gtbhpdnuxw.html

TS:   await resp.json()
来源：http://dali.wangdashe.top/Article/details/gtvojdqnjs.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.fzhhl.top/Article/details/gtqhrnwxiw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yj202588.top/Article/details/gtjrrgpqfz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jiagoushi.top/Article/details/gtutfaqfpb.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhongyouzk.top/Article/details/gtokiqdkpj.html

[L07] 处理 HTTP 状态码
来源：http://dali.jqgfzy.top/Article/details/gtkfkpemwc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hammf.cn/Article/details/gthzbfmniv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yuxming.cn/Article/details/gtayshwgnb.html

JS:   resp.ok;  resp.status
来源：http://dali.xuetiantiany.cn/Article/details/gtcuitusel.html

TS:   resp.ok;  resp.status
来源：http://dali.andypj.xyz/Article/details/gtijugjslw.html

Java: resp.statusCode()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcsqacrml.html

Go:   resp.StatusCode
来源：http://dali.hywenlv.cn/Article/details/gtwbqvlkyo.html

Ruby: resp.code.to_i
来源：http://dali.fzhhl.top/Article/details/gtjnzpgnvz.html

C#:   (int)resp.StatusCode
来源：http://dali.zhengqikj.top/Article/details/gtvtafuvdg.html

[L08] 并发请求多个地址
来源：http://dali.zdqjudy.top/Article/details/gtyfswoiqh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yongpay.top/Article/details/gthtymjczw.html

PHP:  curl_multi_init() 系列
来源：http://dali.9152youxi.cn/Article/details/gtgpolhjis.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenzaomai.com/Article/details/gtzkxzjnlr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zycfv.cn/Article/details/gtfrydvctd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhaomingkeji.xyz/Article/details/gtudthjuoc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj20258888.top/Article/details/gttzkxbayh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.smart0.xyz/Article/details/gtyskhtbvw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.svipenyu.cn/Article/details/gtztbexpla.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gttddacsdg.html

M. 命令行 / 进程 / 环境
来源：http://dali.nanxinkj.top/Article/details/gtrxqntbpb.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtadvozxtj.html

[M01] 读取命令行参数
来源：http://dali.gzhubu.top/Article/details/gtyuzgrcvp.html

Py:   sys.argv[1:]
来源：http://dali.dianchejie.cn/Article/details/gtprnixxer.html

PHP:  $argv;  $argc;
来源：http://dali.0kj1m.cn/Article/details/gtmcgirihn.html

JS:   process.argv.slice(2)
来源：http://dali.wangshuangyany.cn/Article/details/gtogxwzclr.html

TS:   process.argv.slice(2)
来源：http://dali.xuetiantiany.cn/Article/details/gtzokijkql.html

Java: args 数组（main 方法参数）
来源：http://dali.sxryk.cn/Article/details/gtugaqgcdl.html

Go:   os.Args[1:]
来源：http://dali.xziqi.cn/Article/details/gtkkajpfwb.html

Ruby: ARGV
来源：http://dali.ivvv.top/Article/details/gtgflhijvk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.guowangkeji.top/Article/details/gtowwmxbia.html

[M02] 读取环境变量
来源：http://dali.andypj.xyz/Article/details/gtyhqrwwho.html

Py:   os.environ.get("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrsmnmwuo.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.c1oappe.top/Article/details/gtlbnrnrfa.html

JS:   process.env.HOME
来源：http://dali.cheryme.top/Article/details/gtaagxbuli.html

TS:   process.env.HOME
来源：http://dali.hywenlv.cn/Article/details/gtdcnrcwhn.html

Java: System.getenv("HOME")
来源：http://dali.yj202588.top/Article/details/gtkijwyrqp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.tanke756.top/Article/details/gtcskgvgdr.html

Ruby: ENV["HOME"]
来源：http://dali.hysaishi.cn/Article/details/gthsdxyyea.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.redwolf501.top/Article/details/gtsscvyquk.html

[M03] 执行外部命令
来源：http://dali.xuetiantiany.cn/Article/details/gtewgmufmo.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.andypj.xyz/Article/details/gtdkxedtbc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cucudq.cn/Article/details/gtwzpyabxj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zdqjudy.top/Article/details/gtnxbpfipt.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shangyingyoupin.top/Article/details/gtqjijjvma.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.c1oappe.top/Article/details/gtypsnqwie.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cdnleiting.top/Article/details/gtayymzfcz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yvedp.cn/Article/details/gtepadpeyy.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cdnleiting.top/Article/details/gtjkjrutqk.html

[M04] 获取当前工作目录
来源：http://dali.hnxiangtu.top/Article/details/gtatyhalxw.html

Py:   os.getcwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gttvukgfmf.html

PHP:  getcwd();
来源：http://dali.kuanghao11.cn/Article/details/gtgyhzkolm.html

JS:   process.cwd()
来源：http://dali.gaohongyu789.top/Article/details/gtxhjqiyra.html

TS:   process.cwd()
来源：http://dali.tian-w.cn/Article/details/gtnwtfwsxz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.smart0.xyz/Article/details/gtaddyennq.html

Go:   os.Getwd()
来源：http://dali.dianchejie.cn/Article/details/gtstovoshf.html

Ruby: Dir.pwd
来源：http://dali.gotoacloud.top/Article/details/gthugniqwu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ivvv.top/Article/details/gthdyymyho.html

[M05] 设置退出码
来源：http://dali.yanxiufei.cn/Article/details/gtjnwpgtts.html

Py:   sys.exit(1)
来源：http://dali.mhx1999.top/Article/details/gtblclxbne.html

PHP:  exit(1);
来源：http://dali.aibaodan.cn/Article/details/gtokywcmpt.html

JS:   process.exit(1)
来源：http://dali.cucudq.cn/Article/details/gtasvjwhnu.html

TS:   process.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtovniadbm.html

Java: System.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gtkwrrxkpq.html

Go:   os.Exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gtinpvaazu.html

Ruby: exit 1
来源：http://dali.zhoulong.xyz/Article/details/gtozwlvqks.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ydzc1.top/Article/details/gtflfuttzl.html

[M06] 向标准错误输出
来源：http://dali.cucudq.cn/Article/details/gttxlazuaf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.aibaodan.cn/Article/details/gtcodckujm.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gogol.net.cn/Article/details/gtsbcnpkab.html

JS:   console.error("err")
来源：http://dali.haohaochexian.top/Article/details/gtwthxnoco.html

TS:   console.error("err")
来源：http://dali.snrcjt.cn/Article/details/gtvlqfheof.html

Java: System.err.println("err")
来源：http://dali.birdmap.top/Article/details/gteadwnstp.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjszjawyq.html

Ruby: warn "err"
来源：http://dali.yuxming.cn/Article/details/gtobczzcge.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xuetiantiany.cn/Article/details/gtkxriyisp.html

[M07] 判断是否为主入口
来源：http://dali.zdqjudy.top/Article/details/gtgfdafftz.html

Py:   if __name__ == "__main__":
来源：http://dali.xinyue.icu/Article/details/gtmardscau.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.vqdsnc.cn/Article/details/gtwutlxgzt.html

JS:   require.main === module
来源：http://dali.chenzaomai.com/Article/details/gtqhdonjkv.html

TS:   require.main === module
来源：http://dali.pengpengdd.cyou/Article/details/gtzlpkgfva.html

Java: public static void main(String[] args)
来源：http://dali.fengsongda.top/Article/details/gtipdhzgyt.html

Go:   func main()
来源：http://dali.xuetiantiany.cn/Article/details/gtpcnoagzg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.dashuyun.cn/Article/details/gtuwbnxpcq.html

C#:   static void Main(string[] args)
来源：http://dali.yueranfly.top/Article/details/gtdezxjebk.html

[M08] 获取系统与运行时信息
来源：http://dali.vqdsnc.cn/Article/details/gtfjntefhd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.nwbrower.top/Article/details/gtdpgugmmo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.tianlin.xyz/Article/details/gtflxvwzlf.html

JS:   process.platform;  process.version
来源：http://dali.zycfv.cn/Article/details/gtqrxegqjq.html

TS:   process.platform;  process.version
来源：http://dali.wangdashe.top/Article/details/gteeycphsn.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hongshengwenyu.top/Article/details/gtgcxdtgum.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj202588.top/Article/details/gtxexdannr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yongpay.top/Article/details/gtpgrxzcyq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yj20258888.top/Article/details/gtrvnkaotk.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtsrlgysiy.html

N. 数据结构与算法
来源：http://dali.hammf.cn/Article/details/gthuhzbbil.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtucjzkarn.html

[N01] 二分查找（有序数组）
来源：http://dali.cheryme.top/Article/details/gtjnndwlbn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtnacypowu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yj202588.top/Article/details/gtrjtpajjv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hfpthk.cn/Article/details/gtzfvwjpyv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jianghu66.top/Article/details/gtvpboqsng.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtcfnwnnfs.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yuxming.cn/Article/details/gthiajrood.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gaohongyu789.top/Article/details/gtcnnkccxq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtbvuycfzv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shanyushiyangtech.top/Article/details/gttafadfkh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yonumen.top/Article/details/gtempdhxxu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.haohaochexian.top/Article/details/gtazldtrnb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbfavchzq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fzhhl.top/Article/details/gtcunnoayu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.pycfn.com/Article/details/gtddkkuwsq.html

Go:   slices.Sort(arr)
来源：http://dali.jinqigufen.top/Article/details/gtyevhpdpe.html

Ruby: arr.sort
来源：http://dali.tianlin.xyz/Article/details/gttuehqiqk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrvymvufa.html

[N03] 快速排序（分治示例）
来源：http://dali.gogol.net.cn/Article/details/gtvapbqame.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhixingplan.top/Article/details/gtqrvdsnoi.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jianghu66.top/Article/details/gtjjyqnpsg.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hongshengwenyu.top/Article/details/gtzoyogmyw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daxiang520.top/Article/details/gtflzfqcss.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.mhx1999.top/Article/details/gtfmneffbr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cdnleiting.top/Article/details/gtyuavbjjb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tanke756.top/Article/details/gtkcszlnvv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.aizwys.cn/Article/details/gtkupoteuq.html

[N04] 斐波那契数列
来源：http://dali.jinqigfzy.top/Article/details/gtptyfqaya.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsfyrlryv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shuidangran.top/Article/details/gtpgcqevsm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hammf.cn/Article/details/gtteejavnn.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtxoyubrqn.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yuanzhike.top/Article/details/gtpkhpjbga.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.dashuyun.cn/Article/details/gtddbhaawc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhixingplan.top/Article/details/gthdmqmlio.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinqigufen.top/Article/details/gtrarwqcbt.html

[N05] 最大公约数
来源：http://dali.gogol.net.cn/Article/details/gtrzjlqztu.html

Py:   math.gcd(a, b)
来源：http://dali.yj20258888.top/Article/details/gtrorokfhy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.fzhhl.top/Article/details/gttdvspzim.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhixingplan.top/Article/details/gtypdxaqxp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cheryme.top/Article/details/gtrlutsiqp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzukppxbi.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.tianlin.xyz/Article/details/gtujrynjio.html

Ruby: a.gcd(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkbrilrzo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shzxlz.cn/Article/details/gtvzkvldhm.html

[N06] 判断回文字符串
来源：http://dali.nanxinkj.top/Article/details/gtxbmwzpwr.html

Py:   s == s[::-1]
来源：http://dali.xziqi.cn/Article/details/gtjvuzxrqc.html

PHP:  $s === strrev($s);
来源：http://dali.zdqjudy.top/Article/details/gtxfejkpnm.html

JS:   s === [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gtxbcllebw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoxcenubk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gotoacloud.top/Article/details/gtrqtotzcw.html

Go:   // 双指针从两端比较
来源：http://dali.tian-w.cn/Article/details/gttnqooklm.html

Ruby: s == s.reverse
来源：http://dali.daxiang520.top/Article/details/gtfloeocpc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gotoacloud.top/Article/details/gtcyehfskd.html

[N07] 两数之和（返回下标）
来源：http://dali.cdnleiting.top/Article/details/gtakhzblzo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xziqi.cn/Article/details/gtbyitsxqr.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.vqdsnc.cn/Article/details/gtjnqtheph.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.havefunace.top/Article/details/gtpgvdaezn.html

TS:   // 手写 Map<string, number>
来源：http://dali.guannengcc.top/Article/details/gtsjhhaggd.html

Java: // 手写 HashMap
来源：http://dali.0kj1m.cn/Article/details/gtxilcejlu.html

Go:   // 手写 map[int]int
来源：http://dali.vqdsnc.cn/Article/details/gtjufmxwke.html

Ruby: // 手写 Hash
来源：http://dali.yuanzhike.top/Article/details/gticqxtunt.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jqgfzy.top/Article/details/gtwmgprynp.html

[N08] 生成全排列
来源：http://dali.birdmap.top/Article/details/gtekafdpwm.html

Py:   itertools.permutations(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtnyvtlxmj.html

PHP:  // 手写递归交换
来源：http://dali.aizwys.cn/Article/details/gtjfmfeqgu.html

JS:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gtlcnzwkeu.html

TS:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gtfjiomsuw.html

Java: // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gtljxshmfg.html

Go:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gtrntsvyzy.html

Ruby: arr.permutation.to_a
来源：http://dali.pycfn.com/Article/details/gtbixzaayi.html

C#:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gtftqrpwoc.html

[N09] 栈与队列
来源：http://dali.chenzaomai.com/Article/details/gtfktjmuip.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.birdmap.top/Article/details/gtevaomidc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gotoacloud.top/Article/details/gthqgvczqv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtsjltqhfl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhixingplan.top/Article/details/gthymytzdl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gtgcyqirtt.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhoulong.xyz/Article/details/gtafnzyeyi.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yongpay.top/Article/details/gtfjxhgbmx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhengqikj.top/Article/details/gttoopajar.html

[N10] 链表节点定义
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlsqpkcxx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shanyushiyangtech.top/Article/details/gtsynniyjb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.fzhhl.top/Article/details/gtdeceezde.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.bjfxy.top/Article/details/gtptiilmcn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.pycfn.com/Article/details/gtjoxzlvvv.html

Java: class Node { int v; Node next; }
来源：http://dali.fengsongda.top/Article/details/gtwvcjfuln.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.guowangkeji.top/Article/details/gthfzgpplj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.smart0.xyz/Article/details/gthwxoemlg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.svipenyu.cn/Article/details/gtmuvqixnq.html

[N11] 二叉树中序遍历
来源：http://dali.jinqigufen.top/Article/details/gtoxbpagah.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ybcxt.top/Article/details/gtblozhzzg.html

PHP:  // 手写递归函数
来源：http://dali.xuetiantiany.cn/Article/details/gtslpjhftt.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jianghu66.top/Article/details/gtnxqpftzp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tianlin.xyz/Article/details/gtsepozjpg.html

Java: // 手写递归
来源：http://dali.zhongyouzk.top/Article/details/gtefanmvpd.html

Go:   // 手写递归
来源：http://dali.jqgufenzy.top/Article/details/gtdlemdzpg.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.nwbrower.top/Article/details/gtsqldyitl.html

C#:   // 手写递归
来源：http://dali.cucudq.cn/Article/details/gttldlnftu.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gtkcmteibw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xuetiantiany.cn/Article/details/gtuxpiqqle.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.meibo888.top/Article/details/gtjaclxkvt.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.kuanghao11.cn/Article/details/gtdrlqblrz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.c1oappe.top/Article/details/gtdpscnluc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sweek.top/Article/details/gtbfjcikcn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xuetiantiany.cn/Article/details/gtrxxqnrvf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yonumen.top/Article/details/gtzbyetoym.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ydzc1.top/Article/details/gtyvdcrwyr.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtwjgjjdkq.html

O. 并发与异步
来源：http://dali.bjfxy.top/Article/details/gtwjicever.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtgfnocclf.html

[O01] 启动一个线程
来源：http://dali.yuanzhike.top/Article/details/gtpnclhgqu.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shanyushiyangtech.top/Article/details/gtclucvlrn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.wangdashe.top/Article/details/gtuvvysrne.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yuanzhike.top/Article/details/gthiqgydfy.html

TS:   // 同 JS
来源：http://dali.yonumen.top/Article/details/gtmfabmebv.html

Java: new Thread(() -> f()).start()
来源：http://dali.gotoacloud.top/Article/details/gtfyelzelv.html

Go:   go f()
来源：http://dali.shanyushiyangtech.top/Article/details/gtqsemfvht.html

Ruby: Thread.new { f }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjdsfrhro.html

C#:   Task.Run(() => F());
来源：http://dali.hywenlv.cn/Article/details/gtaqiekihi.html

[O02] 使用线程池
来源：http://dali.yuanzhike.top/Article/details/gtsdobshlh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkdtwhtzx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.aizwys.cn/Article/details/gtimiguopn.html

JS:   // worker_threads 线程池
来源：http://dali.xziqi.cn/Article/details/gtcwexedxs.html

TS:   // worker_threads 线程池
来源：http://dali.gzhubu.top/Article/details/gtcleeswtt.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.mhx1999.top/Article/details/gtjvmztqso.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.redwolf501.top/Article/details/gtigorqhvn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.nwbrower.top/Article/details/gtvsvbsfgb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.wangdashe.top/Article/details/gtlsneffpm.html

[O03] 加锁保护共享数据
来源：http://dali.yangfankeji.com/Article/details/gttdslrovu.html

Py:   with lock: shared += 1
来源：http://dali.9152youxi.cn/Article/details/gtkytubtll.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.fzhhl.top/Article/details/gtfuwffhmd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkvjnxynm.html

TS:   // 同 JS
来源：http://dali.hywenlv.cn/Article/details/gtlfbkdtlx.html

Java: synchronized (this) { shared++; }
来源：http://dali.c1oappe.top/Article/details/gtauapyyfa.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hywenlv.cn/Article/details/gtqwbzgwtw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzrjikdfq.html

C#:   lock (gate) { shared++; }
来源：http://dali.xinyue.icu/Article/details/gtstwwljqq.html

[O04] 定义异步函数并等待
来源：http://dali.kuanghao11.cn/Article/details/gtgovyxobo.html

Py:   async def f():⏎    await g()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkvbxejld.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.meibo888.top/Article/details/gtowvsankt.html

JS:   async function f() { await g(); }
来源：http://dali.9152youxi.cn/Article/details/gtqdrvkmwx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.nanxinkj.top/Article/details/gtgitstlgx.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.wangdashe.top/Article/details/gtmqlsqujn.html


<!-- 参考信息 -->