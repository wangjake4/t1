代发 wailian999

L. 网络请求
来源：http://dali.zycfv.cn/Article/details/gtcaswgjjy.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtsvjxzedj.html

[L01] 发送 GET 请求
来源：http://dali.xinyue.icu/Article/details/gtlezgklda.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.daria6918.cn/Article/details/gthdulwanw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.redwolf501.top/Article/details/gtphcashhr.html

JS:   await fetch(url)
来源：http://dali.nanxuanxn.top/Article/details/gtyagchzcz.html

TS:   await fetch(url)
来源：http://dali.zhoulong.xyz/Article/details/gteavobuhb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hfpthk.cn/Article/details/gthmkphrbv.html

Go:   resp, err := http.Get(url)
来源：http://dali.316326.xyz/Article/details/gttcptpakz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.haohaochexian.top/Article/details/gttwzpvxoc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zdqjudy.top/Article/details/gtaoqzkjjw.html

[L02] 发送 POST JSON
来源：http://dali.zdqjudy.top/Article/details/gtggeyaxxt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.mhx1999.top/Article/details/gtlpbosobf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.tanke756.top/Article/details/gtdhywqngd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ydzc1.top/Article/details/gtinypuswj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnxiangtu.top/Article/details/gtheumfatm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.pengpengdd.cyou/Article/details/gtoxmpwebj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hfpthk.cn/Article/details/gtrfbbuglu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xuetiantiany.cn/Article/details/gtdypygvgr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.316326.xyz/Article/details/gtvaidktgt.html

[L03] 设置自定义请求头
来源：http://dali.hammf.cn/Article/details/gtrgrkfjnf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yvedp.cn/Article/details/gtwtveuzrh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.dashuyun.cn/Article/details/gtpjtujknd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhiwuduotai.top/Article/details/gtlzpshajv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ivvv.top/Article/details/gtrfygkyrf.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.fzhhl.top/Article/details/gtujkcjqwl.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yuxming.cn/Article/details/gtetgewjnk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.smart0.xyz/Article/details/gtotoxkknf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ivvv.top/Article/details/gtnvaybhvq.html

[L04] 设置超时
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcqbaxrbo.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jianghu66.top/Article/details/gtdsrrrsgc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zycfv.cn/Article/details/gtholqhoou.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhengqikj.top/Article/details/gtjetdnscj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.0kj1m.cn/Article/details/gtcyjlpfrp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shanyushiyangtech.top/Article/details/gtiboogbgo.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gaohongyu789.top/Article/details/gtdooamygz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.tanke756.top/Article/details/gtwxdmcjig.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yuanzhike.top/Article/details/gtnowgxngz.html

[L05] 上传文件（multipart）
来源：http://dali.xuetiantiany.cn/Article/details/gtjnaysyui.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.pengpengdd.cyou/Article/details/gtjetkzhvo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sysykeji.top/Article/details/gtpcvcrhgr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenlongwang.top/Article/details/gtdsmotrop.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.birdmap.top/Article/details/gtdgklgshr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cashguo.top/Article/details/gtohhaqsfk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.smart0.xyz/Article/details/gttqzxseah.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.snrcjt.cn/Article/details/gtnyuqgowp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtixhbcdgo.html

[L06] 解析响应为 JSON
来源：http://dali.sufxvd.cn/Article/details/gtvrfldedh.html

Py:   resp.json()
来源：http://dali.nwbrower.top/Article/details/gtjnseeoas.html

PHP:  json_decode($body, true);
来源：http://dali.zhengqikj.top/Article/details/gtzuqdbwit.html

JS:   await resp.json()
来源：http://dali.hnxiangtu.top/Article/details/gtzdhjohvh.html

TS:   await resp.json()
来源：http://dali.yuanzhike.top/Article/details/gtchcoeynz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hysaishi.cn/Article/details/gtofihvjed.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.chenzaomai.com/Article/details/gtjhjndjmb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhongyouzk.top/Article/details/gtfuytxrds.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbqkrimkt.html

[L07] 处理 HTTP 状态码
来源：http://dali.xuetiantiany.cn/Article/details/gtniqcfcqv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.meibo888.top/Article/details/gtppsyqehy.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xylfe.cn/Article/details/gtusjsyzxy.html

JS:   resp.ok;  resp.status
来源：http://dali.gaohongyu789.top/Article/details/gtwxmagnzo.html

TS:   resp.ok;  resp.status
来源：http://dali.xziqi.cn/Article/details/gtuedvaqss.html

Java: resp.statusCode()
来源：http://dali.daria6918.cn/Article/details/gtknyckpzq.html

Go:   resp.StatusCode
来源：http://dali.cdnleiting.top/Article/details/gtczlxreau.html

Ruby: resp.code.to_i
来源：http://dali.zdqjudy.top/Article/details/gtivahmxxi.html

C#:   (int)resp.StatusCode
来源：http://dali.ehwqpu.com/Article/details/gtpzabwiys.html

[L08] 并发请求多个地址
来源：http://dali.aizwys.cn/Article/details/gtbxbdbhie.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.dashuyun.cn/Article/details/gtwskmtcta.html

PHP:  curl_multi_init() 系列
来源：http://dali.aizwys.cn/Article/details/gtnnrqpwjj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxuanxn.top/Article/details/gtlyhrldiw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hysaishi.cn/Article/details/gtrngzvzdz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cucudq.cn/Article/details/gtqftsirel.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hammf.cn/Article/details/gtvqtjctls.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hnqzz.top/Article/details/gtgpkpfcbm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gaohongyu789.top/Article/details/gtpceguzlr.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtarnpqfie.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenjidiqi.icu/Article/details/gtbilcrojs.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtrnrfhvsk.html

[M01] 读取命令行参数
来源：http://dali.9152youxi.cn/Article/details/gtcrvunkmg.html

Py:   sys.argv[1:]
来源：http://dali.redwolf501.top/Article/details/gtlnpcowpa.html

PHP:  $argv;  $argc;
来源：http://dali.yuanzhike.top/Article/details/gtbsccppaf.html

JS:   process.argv.slice(2)
来源：http://dali.jinqigfzy.top/Article/details/gtkjremsyk.html

TS:   process.argv.slice(2)
来源：http://dali.xuetiantiany.cn/Article/details/gtkqbtkvit.html

Java: args 数组（main 方法参数）
来源：http://dali.svipenyu.cn/Article/details/gtxeiachlq.html

Go:   os.Args[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gthyvabolu.html

Ruby: ARGV
来源：http://dali.jiagoushi.top/Article/details/gtlpartuca.html

C#:   args 数组（Main 方法参数）
来源：http://dali.pengpengdd.cyou/Article/details/gtunlskcre.html

[M02] 读取环境变量
来源：http://dali.feifeiyinyue.top/Article/details/gtcrasddvh.html

Py:   os.environ.get("HOME")
来源：http://dali.gzhubu.top/Article/details/gtefzmkzap.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tian-w.cn/Article/details/gtqjkoevxj.html

JS:   process.env.HOME
来源：http://dali.kuanghao11.cn/Article/details/gtivfdpfje.html

TS:   process.env.HOME
来源：http://dali.yueranfly.top/Article/details/gtudvivlkv.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gtuoaaqlld.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gtjhnxsavm.html

Ruby: ENV["HOME"]
来源：http://dali.yanxiufei.cn/Article/details/gtjvlkxmvy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.daxiang520.top/Article/details/gtgnicruvp.html

[M03] 执行外部命令
来源：http://dali.cdnleiting.top/Article/details/gtqpemyveb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.aibaodan.cn/Article/details/gtrhsybvag.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.aibaodan.cn/Article/details/gtxiszelhb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.svipenyu.cn/Article/details/gtvzogterl.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.guowangkeji.top/Article/details/gtlwwgwdgc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtacxwjjui.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.birdmap.top/Article/details/gtxutkrvdh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.316326.xyz/Article/details/gtezsnvboz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shuidangran.top/Article/details/gtslcoqodv.html

[M04] 获取当前工作目录
来源：http://dali.xziqi.cn/Article/details/gtvuimzeoz.html

Py:   os.getcwd()
来源：http://dali.guannengcc.top/Article/details/gtkxgztqay.html

PHP:  getcwd();
来源：http://dali.shzxlz.cn/Article/details/gtlkumrpvc.html

JS:   process.cwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpwesjczp.html

TS:   process.cwd()
来源：http://dali.andypj.xyz/Article/details/gtqmqhlnji.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ivvv.top/Article/details/gtpwzopbzz.html

Go:   os.Getwd()
来源：http://dali.cashguo.top/Article/details/gthkzlvjin.html

Ruby: Dir.pwd
来源：http://dali.zhongyouzk.top/Article/details/gttnwphmzd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nwbrower.top/Article/details/gtewqhsolj.html

[M05] 设置退出码
来源：http://dali.bjfxy.top/Article/details/gtflcrhihe.html

Py:   sys.exit(1)
来源：http://dali.xziqi.cn/Article/details/gtsqesnaoy.html

PHP:  exit(1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtynoifcdt.html

JS:   process.exit(1)
来源：http://dali.yonumen.top/Article/details/gtqkgdrned.html

TS:   process.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtgvylqbkd.html

Java: System.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtiwgseqct.html

Go:   os.Exit(1)
来源：http://dali.meibo888.top/Article/details/gtkizfxyyt.html

Ruby: exit 1
来源：http://dali.guannengcc.top/Article/details/gtlzvrketo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hnxiangtu.top/Article/details/gtgmbtvryv.html

[M06] 向标准错误输出
来源：http://dali.zhixingplan.top/Article/details/gtnjszzghi.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shangyingyoupin.top/Article/details/gtjumrmbop.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.0kj1m.cn/Article/details/gtgrluiwnp.html

JS:   console.error("err")
来源：http://dali.fengsongda.top/Article/details/gtwohrcwmw.html

TS:   console.error("err")
来源：http://dali.zhongyouzk.top/Article/details/gtaljqgtcz.html

Java: System.err.println("err")
来源：http://dali.hnqzz.top/Article/details/gthfvinelz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cdnleiting.top/Article/details/gtxvwjvtfa.html

Ruby: warn "err"
来源：http://dali.wangshuangyany.cn/Article/details/gtjujjosqe.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yonumen.top/Article/details/gtusztvefw.html

[M07] 判断是否为主入口
来源：http://dali.jqgfzy.top/Article/details/gtcmuozlxd.html

Py:   if __name__ == "__main__":
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsgtojtfn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cheryme.top/Article/details/gtuzuwwjjq.html

JS:   require.main === module
来源：http://dali.ydzc1.top/Article/details/gtsvhngbsx.html

TS:   require.main === module
来源：http://dali.hammf.cn/Article/details/gtfzhfmykx.html

Java: public static void main(String[] args)
来源：http://dali.cucudq.cn/Article/details/gtnfunvjrc.html

Go:   func main()
来源：http://dali.hnxiangtu.top/Article/details/gthpsdahlf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shanyushiyangtech.top/Article/details/gtpjfkqyhs.html

C#:   static void Main(string[] args)
来源：http://dali.cdnleiting.top/Article/details/gtwnjsgebc.html

[M08] 获取系统与运行时信息
来源：http://dali.jinqigfzy.top/Article/details/gtnyvcfyun.html

Py:   platform.system();  platform.python_version()
来源：http://dali.birdmap.top/Article/details/gtnyrypcuf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhengqikj.top/Article/details/gtueixzpcr.html

JS:   process.platform;  process.version
来源：http://dali.dianchejie.cn/Article/details/gtbxorauar.html

TS:   process.platform;  process.version
来源：http://dali.guannengcc.top/Article/details/gthaxxtwog.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gtiesogcqw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yvedp.cn/Article/details/gtonizmlbd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhengqikj.top/Article/details/gtufxwlswa.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xuetiantiany.cn/Article/details/gtptcaydsb.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtdktuqfzi.html

N. 数据结构与算法
来源：http://dali.xinyue.icu/Article/details/gtjhaffuhf.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtnhewojgm.html

[N01] 二分查找（有序数组）
来源：http://dali.fzhhl.top/Article/details/gtlpykopaj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtfwishpap.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jiagoushi.top/Article/details/gttymmidqe.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gtdascldka.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gtxicpvwrk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yj20258888.top/Article/details/gtkyyfdezh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yongpay.top/Article/details/gtgqhxzsjx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yvedp.cn/Article/details/gtcluqlmyc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtvnsljmuu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xuetiantiany.cn/Article/details/gtrqgsxbmz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ybcxt.top/Article/details/gtpmjppxly.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhixingplan.top/Article/details/gtqxrauday.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ybcxt.top/Article/details/gtgxlioctf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.316326.xyz/Article/details/gtjnowcbjk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.vqdsnc.cn/Article/details/gtcvymyhxx.html

Go:   slices.Sort(arr)
来源：http://dali.fengsongda.top/Article/details/gttpbsknsz.html

Ruby: arr.sort
来源：http://dali.nwbrower.top/Article/details/gtdrlyjpet.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gotoacloud.top/Article/details/gtoyjqwjja.html

[N03] 快速排序（分治示例）
来源：http://dali.xylfe.cn/Article/details/gttpbgjtcs.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shzxlz.cn/Article/details/gtcalkfozb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zdqjudy.top/Article/details/gtjqhpylaj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.smart0.xyz/Article/details/gtyuftojki.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigfzy.top/Article/details/gtfslrsrnx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yvedp.cn/Article/details/gtezpyqkgg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhiwuduotai.top/Article/details/gtymmnoixz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gzhubu.top/Article/details/gtxyupkhps.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cucudq.cn/Article/details/gtugvalzen.html

[N04] 斐波那契数列
来源：http://dali.jinghuilouyu.cn/Article/details/gtahinhztu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhongyouzk.top/Article/details/gtuysstwox.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gtpjhbinkq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hywenlv.cn/Article/details/gtrcaojras.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiwhewlom.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shangyingyoupin.top/Article/details/gtwoxsvnzs.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hammf.cn/Article/details/gtzmvkycka.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gogol.net.cn/Article/details/gtsxzxnkjs.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.gogol.net.cn/Article/details/gtoeygtisl.html

[N05] 最大公约数
来源：http://dali.hfpthk.cn/Article/details/gtcnhgyfxj.html

Py:   math.gcd(a, b)
来源：http://dali.zdqjudy.top/Article/details/gtbbgubzfv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.fzhhl.top/Article/details/gtmznvfaoo.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hysaishi.cn/Article/details/gthpdcnuph.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ehwqpu.com/Article/details/gtjfdryczs.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.vqdsnc.cn/Article/details/gteppcjufa.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zycfv.cn/Article/details/gtvmbmqtgo.html

Ruby: a.gcd(b)
来源：http://dali.smart0.xyz/Article/details/gtyioxhvep.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jqgufenzy.top/Article/details/gtlvydveed.html

[N06] 判断回文字符串
来源：http://dali.chenlongwang.top/Article/details/gtgguymrpx.html

Py:   s == s[::-1]
来源：http://dali.chenlongwang.top/Article/details/gtsbszkiiv.html

PHP:  $s === strrev($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtnytayyfa.html

JS:   s === [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtqzrtgdmv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gtdmexsfpa.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinghuilouyu.cn/Article/details/gtyupoespv.html

Go:   // 双指针从两端比较
来源：http://dali.nanxinkj.top/Article/details/gtelcuckqy.html

Ruby: s == s.reverse
来源：http://dali.hongshengwenyu.top/Article/details/gtxklwlfbu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.quarkkingdee.top/Article/details/gtqwruqczx.html

[N07] 两数之和（返回下标）
来源：http://dali.shzxlz.cn/Article/details/gtgnspfhdx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.chenlongwang.top/Article/details/gtaesipsec.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zycfv.cn/Article/details/gtqfvwfgip.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlezkifsj.html

TS:   // 手写 Map<string, number>
来源：http://dali.ydzc1.top/Article/details/gtzvdiaijq.html

Java: // 手写 HashMap
来源：http://dali.jyoumei.cn/Article/details/gthnhcyozl.html

Go:   // 手写 map[int]int
来源：http://dali.feifeiyinyue.top/Article/details/gtjndhksmf.html

Ruby: // 手写 Hash
来源：http://dali.dashuyun.cn/Article/details/gtrwxpkrdz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hnqzz.top/Article/details/gtdfyaakri.html

[N08] 生成全排列
来源：http://dali.gogol.net.cn/Article/details/gtqjehmjag.html

Py:   itertools.permutations(arr)
来源：http://dali.0kj1m.cn/Article/details/gtxbmwrdhc.html

PHP:  // 手写递归交换
来源：http://dali.zhoulong.xyz/Article/details/gtudzzjjlc.html

JS:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gtjbqpyjau.html

TS:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gtmqyffuou.html

Java: // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gtshsghakm.html

Go:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gtcmkznpbl.html

Ruby: arr.permutation.to_a
来源：http://dali.hywenlv.cn/Article/details/gtjgufpzkv.html

C#:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gtgjyczgtt.html

[N09] 栈与队列
来源：http://dali.zhongyouzk.top/Article/details/gtwlettuuk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jqgufenzy.top/Article/details/gtohonmpfu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gtgtsjxmzf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.vqdsnc.cn/Article/details/gtbnvaojfu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.sweek.top/Article/details/gtwqmvxezj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sxryk.cn/Article/details/gtfkcmapit.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xylfe.cn/Article/details/gtbxubumsp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.iojbl.cn/Article/details/gtzksshnai.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhoulong.xyz/Article/details/gtintivbyl.html

[N10] 链表节点定义
来源：http://dali.yongpay.top/Article/details/gtfzausrps.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinqigufen.top/Article/details/gtvfthieej.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.haohaochexian.top/Article/details/gtyiyihnqn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cdnleiting.top/Article/details/gtqvhtbfot.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.guannengcc.top/Article/details/gtlqhwjbnw.html

Java: class Node { int v; Node next; }
来源：http://dali.haohaochexian.top/Article/details/gtcvfiqayo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.smart0.xyz/Article/details/gtehdhvdii.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jlsjyb.cn/Article/details/gtnwkybwhn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhengqikj.top/Article/details/gtfprpydmd.html

[N11] 二叉树中序遍历
来源：http://dali.c1oappe.top/Article/details/gtruxuxvsf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sysykeji.top/Article/details/gtqcdmpgdq.html

PHP:  // 手写递归函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvnrotmjq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xinyue.icu/Article/details/gtvylsjwvd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cqqwz.cn/Article/details/gtqbfzdfhc.html

Java: // 手写递归
来源：http://dali.nanxinkj.top/Article/details/gtvvzjzgfv.html

Go:   // 手写递归
来源：http://dali.zhoulong.xyz/Article/details/gtewgwphqj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jlsjyb.cn/Article/details/gtvdgjokrp.html

C#:   // 手写递归
来源：http://dali.guowangkeji.top/Article/details/gtxzfpxllw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinghuilouyu.cn/Article/details/gtkujavzvr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.316326.xyz/Article/details/gtgzaawtma.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hywenlv.cn/Article/details/gtrwovkzvz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenjidiqi.icu/Article/details/gtmvyqukqy.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.iojbl.cn/Article/details/gtyedsbbss.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xylfe.cn/Article/details/gtbpbblvfd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xylfe.cn/Article/details/gtalpwcclx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yongpay.top/Article/details/gtholyticg.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258.top/Article/details/gtpedjhynv.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtjpcxfdme.html

O. 并发与异步
来源：http://dali.9152youxi.cn/Article/details/gtqxcglhry.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtegepjsab.html

[O01] 启动一个线程
来源：http://dali.xuanzx.com/Article/details/gtbjhnehgp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.dianchejie.cn/Article/details/gtbzgdfcdq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtamydozjh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.bjfxy.top/Article/details/gtlhkvmrdr.html

TS:   // 同 JS
来源：http://dali.yj202588.top/Article/details/gtgpnbmjpa.html

Java: new Thread(() -> f()).start()
来源：http://dali.tianlin.xyz/Article/details/gtarfoyxct.html

Go:   go f()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtntjdadjz.html

Ruby: Thread.new { f }
来源：http://dali.jqgufenzy.top/Article/details/gtjlyyuafe.html

C#:   Task.Run(() => F());
来源：http://dali.birdmap.top/Article/details/gtsvroyxzm.html

[O02] 使用线程池
来源：http://dali.hysaishi.cn/Article/details/gtxxxstwnx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttgmqcwlw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.tanke756.top/Article/details/gtjsfzgfmu.html

JS:   // worker_threads 线程池
来源：http://dali.ivvv.top/Article/details/gtnrtsmorv.html

TS:   // worker_threads 线程池
来源：http://dali.ehwqpu.com/Article/details/gtfkeiplqr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.dashuyun.cn/Article/details/gtcresbrni.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.guowangkeji.top/Article/details/gtbdnuyosu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shanyushiyangtech.top/Article/details/gtewsovpav.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.0kj1m.cn/Article/details/gtmgwbkeqf.html

[O03] 加锁保护共享数据
来源：http://dali.shangyingyoupin.top/Article/details/gtbouwmuex.html

Py:   with lock: shared += 1
来源：http://dali.aibaodan.cn/Article/details/gtqkwchqhg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.iojbl.cn/Article/details/gtvcsersle.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.tianlin.xyz/Article/details/gtawzabhpj.html

TS:   // 同 JS
来源：http://dali.tianlin.xyz/Article/details/gtvjuqirpv.html

Java: synchronized (this) { shared++; }
来源：http://dali.feifeiyinyue.top/Article/details/gtemifscoq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.smart0.xyz/Article/details/gtxpsiidcj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.bjfxy.top/Article/details/gtfpxzvlwx.html

C#:   lock (gate) { shared++; }
来源：http://dali.sxryk.cn/Article/details/gtdsxblpie.html

[O04] 定义异步函数并等待
来源：http://dali.ybcxt.top/Article/details/gtxbjyotje.html

Py:   async def f():⏎    await g()
来源：http://dali.kuanghao11.cn/Article/details/gtbyhxspxn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xylfe.cn/Article/details/gteahlakak.html

JS:   async function f() { await g(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrlevzctc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ivvv.top/Article/details/gtzypwrioc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnftqurle.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuaemxqkj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hnxiangtu.top/Article/details/gtqidwfrrk.html

C#:   async Task F() { await G(); }
来源：http://dali.shangyingyoupin.top/Article/details/gteoddfkwr.html

[O05] 并发执行并等待全部完成
来源：http://dali.nanxuanxn.top/Article/details/gtvtewldsu.html


<!-- 参考信息 -->