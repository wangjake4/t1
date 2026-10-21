代发 wailian999

L. 网络请求
来源：http://dali.ybcxt.top/Article/details/gtcvumosbo.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtigwktsnt.html

[L01] 发送 GET 请求
来源：http://dali.zhixingplan.top/Article/details/gtubklpbou.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.bjfxy.top/Article/details/gtrdewuxsw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.tian-w.cn/Article/details/gtustlhxgc.html

JS:   await fetch(url)
来源：http://dali.hnxiangtu.top/Article/details/gtpqjbklwv.html

TS:   await fetch(url)
来源：http://dali.hammf.cn/Article/details/gtavebckbi.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.wangdashe.top/Article/details/gtavsddwkq.html

Go:   resp, err := http.Get(url)
来源：http://dali.cdnleiting.top/Article/details/gtarvqvnuc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtebiwuvhn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ehwqpu.com/Article/details/gtbfmjwtlo.html

[L02] 发送 POST JSON
来源：http://dali.gzhubu.top/Article/details/gtvkavsxlv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yvedp.cn/Article/details/gtmmyhghuc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtummwxzli.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ydzc1.top/Article/details/gtecyjmlom.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gzhubu.top/Article/details/gtlyqhrawv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenjidiqi.icu/Article/details/gtarcggyqv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.tanke756.top/Article/details/gtbibwbvxb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shuidangran.top/Article/details/gtgzepxhxa.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jianghu66.top/Article/details/gtjxtiwvno.html

[L03] 设置自定义请求头
来源：http://dali.chenlongwang.top/Article/details/gtjtakwipu.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.guannengcc.top/Article/details/gtegokadgq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ehwqpu.com/Article/details/gttiaqoixl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sysykeji.top/Article/details/gtrnpbjazt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.havefunace.top/Article/details/gtxcnothdk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jqgfzy.top/Article/details/gtnypxdgpa.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yuxming.cn/Article/details/gtcdzdcgbf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.feifeiyinyue.top/Article/details/gteipvdsiy.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.wangdashe.top/Article/details/gtnrjtmsxl.html

[L04] 设置超时
来源：http://dali.shangyingyoupin.top/Article/details/gttflgzspa.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jianghu66.top/Article/details/gtunijdnhu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkyrauvhm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fzhhl.top/Article/details/gtiyngyuvy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shangyingyoupin.top/Article/details/gtxpfdtaqb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.pengpengdd.cyou/Article/details/gtyzaeysgx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.quarkkingdee.top/Article/details/gtiuqrsawo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nanxuanxn.top/Article/details/gtpstesxbz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbusqmxqm.html

[L05] 上传文件（multipart）
来源：http://dali.jqgfzy.top/Article/details/gtewraocgx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zycfv.cn/Article/details/gtqdzrtlgo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.daxiang520.top/Article/details/gtriqcjzst.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.redwolf501.top/Article/details/gtbrmccwdn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigufen.top/Article/details/gtmpjudzqc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hammf.cn/Article/details/gtftmvflay.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gthzphqobz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xinyue.icu/Article/details/gtdrghqbwh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.guannengcc.top/Article/details/gtaliuhnxe.html

[L06] 解析响应为 JSON
来源：http://dali.pycfn.com/Article/details/gtvrpxirxn.html

Py:   resp.json()
来源：http://dali.zhiwuduotai.top/Article/details/gtdeygzbxg.html

PHP:  json_decode($body, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtytwcuobo.html

JS:   await resp.json()
来源：http://dali.cheryme.top/Article/details/gtqrfdqqat.html

TS:   await resp.json()
来源：http://dali.tanke756.top/Article/details/gtgvgxtfcf.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.redwolf501.top/Article/details/gtyxwdaogz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinghuilouyu.cn/Article/details/gtssittegg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jlsjyb.cn/Article/details/gtvnctxhyj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jiagoushi.top/Article/details/gtharwuiht.html

[L07] 处理 HTTP 状态码
来源：http://dali.yueranfly.top/Article/details/gtnwmmfczi.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhongyouzk.top/Article/details/gtfrljagnv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gogol.net.cn/Article/details/gtstpyptrl.html

JS:   resp.ok;  resp.status
来源：http://dali.cheryme.top/Article/details/gtntacgots.html

TS:   resp.ok;  resp.status
来源：http://dali.jqgfzy.top/Article/details/gthtbowgzm.html

Java: resp.statusCode()
来源：http://dali.jlsjyb.cn/Article/details/gtiqwzeeqf.html

Go:   resp.StatusCode
来源：http://dali.ppjwa.cn/Article/details/gtxgijnodr.html

Ruby: resp.code.to_i
来源：http://dali.yj202588.top/Article/details/gtnevrowwp.html

C#:   (int)resp.StatusCode
来源：http://dali.cdnleiting.top/Article/details/gtvbtuetqc.html

[L08] 并发请求多个地址
来源：http://dali.cashguo.top/Article/details/gtnzwptqoj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ppjwa.cn/Article/details/gtjkngzlui.html

PHP:  curl_multi_init() 系列
来源：http://dali.daxiang520.top/Article/details/gtwnnnysmt.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daxiang520.top/Article/details/gtpxristms.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhongyouzk.top/Article/details/gtdlvoslqr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hnxiangtu.top/Article/details/gtfgsufrqx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sxryk.cn/Article/details/gtdjdtojkd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zycfv.cn/Article/details/gtpxtvlzue.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gteihhnngu.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzgpoccvf.html

M. 命令行 / 进程 / 环境
来源：http://dali.birdmap.top/Article/details/gtkofpdwkd.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtcjszvuev.html

[M01] 读取命令行参数
来源：http://dali.gzhubu.top/Article/details/gtpxbmhpuo.html

Py:   sys.argv[1:]
来源：http://dali.andypj.xyz/Article/details/gtdlvujggv.html

PHP:  $argv;  $argc;
来源：http://dali.shangyingyoupin.top/Article/details/gtynccqbzz.html

JS:   process.argv.slice(2)
来源：http://dali.jyoumei.cn/Article/details/gtqmlfswrm.html

TS:   process.argv.slice(2)
来源：http://dali.dashuyun.cn/Article/details/gtcermwypj.html

Java: args 数组（main 方法参数）
来源：http://dali.hammf.cn/Article/details/gtbrvnbjkv.html

Go:   os.Args[1:]
来源：http://dali.svipenyu.cn/Article/details/gtagkuxnqx.html

Ruby: ARGV
来源：http://dali.hnqzz.top/Article/details/gtvevwkomc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.fzhhl.top/Article/details/gtmhtraimn.html

[M02] 读取环境变量
来源：http://dali.hywenlv.cn/Article/details/gtfpudlzam.html

Py:   os.environ.get("HOME")
来源：http://dali.tianlin.xyz/Article/details/gtaijszpzh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hnqzz.top/Article/details/gtupbvhket.html

JS:   process.env.HOME
来源：http://dali.zhongyouzk.top/Article/details/gtmqfnyhxt.html

TS:   process.env.HOME
来源：http://dali.c1oappe.top/Article/details/gtqmbefqtr.html

Java: System.getenv("HOME")
来源：http://dali.sufxvd.cn/Article/details/gtvmbfthqg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj202588.top/Article/details/gtjhogpxqi.html

Ruby: ENV["HOME"]
来源：http://dali.yj202588.top/Article/details/gtzixgiprf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.0kj1m.cn/Article/details/gtheklvdfn.html

[M03] 执行外部命令
来源：http://dali.guannengcc.top/Article/details/gtrnspeyvh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.nanxinkj.top/Article/details/gtycffhrep.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhongyouzk.top/Article/details/gtlbgekchi.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.sufxvd.cn/Article/details/gtggnaftzt.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cqqwz.cn/Article/details/gtzpjjmdnr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yvedp.cn/Article/details/gtwhiduguv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yangfankeji.com/Article/details/gtodiqfxcs.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhixingplan.top/Article/details/gtalwyaifh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cqqwz.cn/Article/details/gtdqwfbllq.html

[M04] 获取当前工作目录
来源：http://dali.sufxvd.cn/Article/details/gtpndnsaci.html

Py:   os.getcwd()
来源：http://dali.kuanghao11.cn/Article/details/gtecfouuka.html

PHP:  getcwd();
来源：http://dali.tian-w.cn/Article/details/gtidehchji.html

JS:   process.cwd()
来源：http://dali.jqgufenzy.top/Article/details/gtywxugvdg.html

TS:   process.cwd()
来源：http://dali.cashguo.top/Article/details/gtzehseaeq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shanyushiyangtech.top/Article/details/gtgqlwospl.html

Go:   os.Getwd()
来源：http://dali.jqgfzy.top/Article/details/gtgeoednjn.html

Ruby: Dir.pwd
来源：http://dali.pycfn.com/Article/details/gtnaozuibp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.pycfn.com/Article/details/gtcxslsubf.html

[M05] 设置退出码
来源：http://dali.jinghuilouyu.cn/Article/details/gtwbkqwena.html

Py:   sys.exit(1)
来源：http://dali.andypj.xyz/Article/details/gttjcloyku.html

PHP:  exit(1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtovxykbzi.html

JS:   process.exit(1)
来源：http://dali.meibo888.top/Article/details/gtztxuskep.html

TS:   process.exit(1)
来源：http://dali.hnqzz.top/Article/details/gtyigyvjlz.html

Java: System.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gtxqmothzj.html

Go:   os.Exit(1)
来源：http://dali.yueranfly.top/Article/details/gttpkeniah.html

Ruby: exit 1
来源：http://dali.gzhubu.top/Article/details/gtkfljgxvb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdmzsjsma.html

[M06] 向标准错误输出
来源：http://dali.chenlongwang.top/Article/details/gtejpqhojg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gtxapwrcue.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.9152youxi.cn/Article/details/gtniuakyus.html

JS:   console.error("err")
来源：http://dali.hnqzz.top/Article/details/gtxofcsvnn.html

TS:   console.error("err")
来源：http://dali.cheryme.top/Article/details/gtllyemytj.html

Java: System.err.println("err")
来源：http://dali.iojbl.cn/Article/details/gtkwdqaeez.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.chenzaomai.com/Article/details/gtvsnfwftw.html

Ruby: warn "err"
来源：http://dali.chenlongwang.top/Article/details/gtrwjjozgb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.redwolf501.top/Article/details/gtixbxncxu.html

[M07] 判断是否为主入口
来源：http://dali.hnxiangtu.top/Article/details/gtjekicytj.html

Py:   if __name__ == "__main__":
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgtraxqxy.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xylfe.cn/Article/details/gtzcnhwojm.html

JS:   require.main === module
来源：http://dali.bjfxy.top/Article/details/gtfiambvgp.html

TS:   require.main === module
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqyzwwenn.html

Java: public static void main(String[] args)
来源：http://dali.chenzaomai.com/Article/details/gteegeyoyf.html

Go:   func main()
来源：http://dali.yongpay.top/Article/details/gtjneuzset.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xylfe.cn/Article/details/gtzbmxzshn.html

C#:   static void Main(string[] args)
来源：http://dali.jiagoushi.top/Article/details/gtpknlinet.html

[M08] 获取系统与运行时信息
来源：http://dali.nwbrower.top/Article/details/gtsqtionik.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhiwuduotai.top/Article/details/gtmbglsjcg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.0kj1m.cn/Article/details/gtfzeysliy.html

JS:   process.platform;  process.version
来源：http://dali.zdqjudy.top/Article/details/gtvbxnszvj.html

TS:   process.platform;  process.version
来源：http://dali.chenjidiqi.icu/Article/details/gtcwfzwtfw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xuanzx.com/Article/details/gtakwhadge.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinqigufen.top/Article/details/gtqibgkclh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.mhx1999.top/Article/details/gtplpnozqq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jqgufenzy.top/Article/details/gttleywzob.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtsutihwuc.html

N. 数据结构与算法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfdzezgrj.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtnnryetla.html

[N01] 二分查找（有序数组）
来源：http://dali.snrcjt.cn/Article/details/gteymiuufj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtmoangfgo.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ydzc1.top/Article/details/gtnzuucfro.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gzhubu.top/Article/details/gtmzxkckrz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenlongwang.top/Article/details/gtmpijstjp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtagdhglcz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtxtafsujy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.9152youxi.cn/Article/details/gthpqizisp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtseumzxea.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jqgfzy.top/Article/details/gtnxgxfpeb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cdnleiting.top/Article/details/gtojtpkssi.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cheryme.top/Article/details/gtvfvzsxmv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fzhhl.top/Article/details/gtetzzvfgv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyieftfbr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xuetiantiany.cn/Article/details/gtgtzrqwsd.html

Go:   slices.Sort(arr)
来源：http://dali.cqqwz.cn/Article/details/gtcsbntuzl.html

Ruby: arr.sort
来源：http://dali.c1oappe.top/Article/details/gtwyrxjpeu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.wangshuangyany.cn/Article/details/gtwojteljy.html

[N03] 快速排序（分治示例）
来源：http://dali.ppjwa.cn/Article/details/gtxxomeaer.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xuanzx.com/Article/details/gtqgygocen.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ppjwa.cn/Article/details/gtbzjumvyc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ybcxt.top/Article/details/gtgpjrprbg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yongpay.top/Article/details/gtzznjrosx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.andypj.xyz/Article/details/gtekizujyc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xuetiantiany.cn/Article/details/gtwdjphgji.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yonumen.top/Article/details/gtayzvibrb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.kuanghao11.cn/Article/details/gthpbctpgs.html

[N04] 斐波那契数列
来源：http://dali.snrcjt.cn/Article/details/gtydfkgiew.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.redwolf501.top/Article/details/gthimozxsz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gtfukxsqbe.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dianchejie.cn/Article/details/gtbcuzxfcm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gtrcpqgwqw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xylfe.cn/Article/details/gtzdigtbsu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.daxiang520.top/Article/details/gtfyosgelr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtesnfwtio.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.gzhubu.top/Article/details/gtnybidfoz.html

[N05] 最大公约数
来源：http://dali.zhiwuduotai.top/Article/details/gtqlvprquh.html

Py:   math.gcd(a, b)
来源：http://dali.nanxinkj.top/Article/details/gtugaxrbru.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ivvv.top/Article/details/gtubpfwjto.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuanzhike.top/Article/details/gtgrldjqyq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zdqjudy.top/Article/details/gtgjyyzybv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.birdmap.top/Article/details/gtbnkaeawh.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.smart0.xyz/Article/details/gtzcbhnkfj.html

Ruby: a.gcd(b)
来源：http://dali.vqdsnc.cn/Article/details/gtycsqemiv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sxryk.cn/Article/details/gtlgsobhti.html

[N06] 判断回文字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtqdbiokrt.html

Py:   s == s[::-1]
来源：http://dali.wangshuangyany.cn/Article/details/gtepbuvpsh.html

PHP:  $s === strrev($s);
来源：http://dali.hywenlv.cn/Article/details/gtlzlxvgxl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gtexytzinv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gthcnbofer.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.guowangkeji.top/Article/details/gtdcsnhybd.html

Go:   // 双指针从两端比较
来源：http://dali.jyoumei.cn/Article/details/gtnxidqrqw.html

Ruby: s == s.reverse
来源：http://dali.dashuyun.cn/Article/details/gtxsztxtok.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gotoacloud.top/Article/details/gthuvjpcrj.html

[N07] 两数之和（返回下标）
来源：http://dali.birdmap.top/Article/details/gtymmainjk.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hysaishi.cn/Article/details/gtsympqkxh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zdqjudy.top/Article/details/gtsckbyfjn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cheryme.top/Article/details/gtzfxbagdm.html

TS:   // 手写 Map<string, number>
来源：http://dali.daria6918.cn/Article/details/gttwxdexyn.html

Java: // 手写 HashMap
来源：http://dali.zhixingplan.top/Article/details/gtjixibdtk.html

Go:   // 手写 map[int]int
来源：http://dali.yuanzhike.top/Article/details/gtefsutcep.html

Ruby: // 手写 Hash
来源：http://dali.jlsjyb.cn/Article/details/gtzuproszg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.bjfxy.top/Article/details/gtfpawmhkb.html

[N08] 生成全排列
来源：http://dali.fzhhl.top/Article/details/gtwdxyvmrd.html

Py:   itertools.permutations(arr)
来源：http://dali.jqgfzy.top/Article/details/gtpzskuztj.html

PHP:  // 手写递归交换
来源：http://dali.sufxvd.cn/Article/details/gtikkohxof.html

JS:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtutdpqkfw.html

TS:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gtbyklczfl.html

Java: // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gtbkehfoim.html

Go:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gtvvgroant.html

Ruby: arr.permutation.to_a
来源：http://dali.pengpengdd.cyou/Article/details/gtiwzrwyjb.html

C#:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gtjmgmqliq.html

[N09] 栈与队列
来源：http://dali.hfpthk.cn/Article/details/gtjaptiuux.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.birdmap.top/Article/details/gtfenieanu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.fengsongda.top/Article/details/gtamvkzeva.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.meibo888.top/Article/details/gtjkzkqsnv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.chenzaomai.com/Article/details/gtoqpwbfqt.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hysaishi.cn/Article/details/gttpfgrlqn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.wangshuangyany.cn/Article/details/gtjijstzkd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.aibaodan.cn/Article/details/gtnixsmjkw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinghuilouyu.cn/Article/details/gtqafuxhsy.html

[N10] 链表节点定义
来源：http://dali.shangyingyoupin.top/Article/details/gtjfgwqske.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.daria6918.cn/Article/details/gthzzhkvrr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hnxiangtu.top/Article/details/gtziovbpkj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.316326.xyz/Article/details/gtyxkyijqu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.smart0.xyz/Article/details/gtvtkvdtoc.html

Java: class Node { int v; Node next; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjohwmhkf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.9152youxi.cn/Article/details/gtpyscnpsr.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xziqi.cn/Article/details/gtoetxvdma.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ehwqpu.com/Article/details/gtibhtyffh.html

[N11] 二叉树中序遍历
来源：http://dali.hnxiangtu.top/Article/details/gtmkhyiand.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.tianlin.xyz/Article/details/gtqbxybstv.html

PHP:  // 手写递归函数
来源：http://dali.9152youxi.cn/Article/details/gtypcczjuy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aizwys.cn/Article/details/gtnjztjzfi.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.c1oappe.top/Article/details/gtzkxynqbt.html

Java: // 手写递归
来源：http://dali.yueranfly.top/Article/details/gtnruijfyo.html

Go:   // 手写递归
来源：http://dali.zhixingplan.top/Article/details/gtnopwwlzs.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.bjfxy.top/Article/details/gtgdattwbk.html

C#:   // 手写递归
来源：http://dali.gaohongyu789.top/Article/details/gtaquwbcbq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hfpthk.cn/Article/details/gthgtlhdlg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gtrltrqbct.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.chenlongwang.top/Article/details/gtjlxeyunx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.iojbl.cn/Article/details/gtcmbcvowo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.pengpengdd.cyou/Article/details/gtawwfgmrd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cucudq.cn/Article/details/gtsxijbyry.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cheryme.top/Article/details/gtoigrjfjm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hammf.cn/Article/details/gtdapibjic.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xylfe.cn/Article/details/gtpnkwjptn.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtwmfvnupa.html

O. 并发与异步
来源：http://dali.gogol.net.cn/Article/details/gtbzxguedu.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtgaclxdcc.html

[O01] 启动一个线程
来源：http://dali.gaohongyu789.top/Article/details/gtbkkizeox.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.smart0.xyz/Article/details/gttrkhzffg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xuetiantiany.cn/Article/details/gtxttyuzjp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.feifeiyinyue.top/Article/details/gtegqohujg.html

TS:   // 同 JS
来源：http://dali.cucudq.cn/Article/details/gtakjixgbg.html

Java: new Thread(() -> f()).start()
来源：http://dali.pengpengdd.cyou/Article/details/gtgvloenqb.html

Go:   go f()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzcywsrpp.html

Ruby: Thread.new { f }
来源：http://dali.xuanzx.com/Article/details/gtblahnywi.html

C#:   Task.Run(() => F());
来源：http://dali.zhengqikj.top/Article/details/gtznifngec.html

[O02] 使用线程池
来源：http://dali.hnxiangtu.top/Article/details/gtnrjrcbdu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cheryme.top/Article/details/gtxjqekhfj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.meibo888.top/Article/details/gtsfqoywzw.html

JS:   // worker_threads 线程池
来源：http://dali.havefunace.top/Article/details/gtbmmttcgy.html

TS:   // worker_threads 线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gtyemzewmb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.andypj.xyz/Article/details/gtgmzlerqt.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jqgufenzy.top/Article/details/gtjgfalbyt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.c1oappe.top/Article/details/gtxqlgdcpx.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yj20258.top/Article/details/gthctgrqge.html

[O03] 加锁保护共享数据
来源：http://dali.gaohongyu789.top/Article/details/gtejhvakka.html

Py:   with lock: shared += 1
来源：http://dali.nanxuanxn.top/Article/details/gtwcpquhue.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.birdmap.top/Article/details/gtufwryoeh.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xuanzx.com/Article/details/gtkioholdg.html

TS:   // 同 JS
来源：http://dali.zhixingplan.top/Article/details/gtervoowwl.html

Java: synchronized (this) { shared++; }
来源：http://dali.fengsongda.top/Article/details/gthjrtuumf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xuetiantiany.cn/Article/details/gtkpvioiou.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtonnnpvih.html

C#:   lock (gate) { shared++; }
来源：http://dali.andypj.xyz/Article/details/gtqzwyemzl.html

[O04] 定义异步函数并等待
来源：http://dali.redwolf501.top/Article/details/gtibkoadbf.html

Py:   async def f():⏎    await g()
来源：http://dali.gogol.net.cn/Article/details/gtplzqivyf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yongpay.top/Article/details/gtsxvenqkg.html

JS:   async function f() { await g(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjcvknaov.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jianghu66.top/Article/details/gtehimycnm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhiwuduotai.top/Article/details/gthytbhldg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.pycfn.com/Article/details/gtbqhulfks.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.snrcjt.cn/Article/details/gtopgcdunp.html

C#:   async Task F() { await G(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqinkbair.html

[O05] 并发执行并等待全部完成
来源：http://dali.sweek.top/Article/details/gtmantotlb.html


<!-- 参考信息 -->