代发 wailian999

L. 网络请求
来源：http://dali.shanyushiyangtech.top/Article/details/gtutoodczb.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtrocvvlum.html

[L01] 发送 GET 请求
来源：http://dali.jinqigfzy.top/Article/details/gtysjglajm.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.meibo888.top/Article/details/gtwsbprrrj.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.birdmap.top/Article/details/gtxtjtwqio.html

JS:   await fetch(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvfzfmdvz.html

TS:   await fetch(url)
来源：http://dali.nanxuanxn.top/Article/details/gtjnmjixdo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.svipenyu.cn/Article/details/gtcquavkyo.html

Go:   resp, err := http.Get(url)
来源：http://dali.tanke756.top/Article/details/gtvdejemnq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.snrcjt.cn/Article/details/gtqjngjnqt.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.andypj.xyz/Article/details/gtqzkzeptf.html

[L02] 发送 POST JSON
来源：http://dali.meibo888.top/Article/details/gtadzdmyry.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xinyue.icu/Article/details/gtxzbmmgvg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hnxiangtu.top/Article/details/gtabnnotgh.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gtdgcaycdq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cqqwz.cn/Article/details/gtinbxeikf.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.meibo888.top/Article/details/gtajkrmevs.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yuanzhike.top/Article/details/gtiwgedpkz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ehwqpu.com/Article/details/gtlrkizala.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yueranfly.top/Article/details/gtdcynfffg.html

[L03] 设置自定义请求头
来源：http://dali.hongshengwenyu.top/Article/details/gtamexosjg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yvedp.cn/Article/details/gtvtziqprw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenlongwang.top/Article/details/gtewtpreni.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.quarkkingdee.top/Article/details/gtycvfsswh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhengqikj.top/Article/details/gtuonbpmqg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.fengsongda.top/Article/details/gtxtkrkzqn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sysykeji.top/Article/details/gtbqufwfjz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhengqikj.top/Article/details/gtwubgfoth.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hysaishi.cn/Article/details/gtwrtyykzp.html

[L04] 设置超时
来源：http://dali.ehwqpu.com/Article/details/gtiycbrmrc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.pycfn.com/Article/details/gtwskxpeis.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ppjwa.cn/Article/details/gtchpppfqf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shzxlz.cn/Article/details/gtdqreesjr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhixingplan.top/Article/details/gtevurjfwe.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.dianchejie.cn/Article/details/gtggcvqdaw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.nanxuanxn.top/Article/details/gtwqdsofxr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xuetiantiany.cn/Article/details/gtgcrrmiyy.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sweek.top/Article/details/gtbazgfgca.html

[L05] 上传文件（multipart）
来源：http://dali.jinqigufen.top/Article/details/gtxtyrsyxi.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yanxiufei.cn/Article/details/gtcqemyvot.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zdqjudy.top/Article/details/gtveyawsrf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhongyouzk.top/Article/details/gtxxnblljx.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.haohaochexian.top/Article/details/gthtjzlvwp.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.bjfxy.top/Article/details/gtzxezvene.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.snrcjt.cn/Article/details/gtwflbwycg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.chenjidiqi.icu/Article/details/gtjnphibxy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtaqulynpt.html

[L06] 解析响应为 JSON
来源：http://dali.sweek.top/Article/details/gtiudtasba.html

Py:   resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gtrfmivcjd.html

PHP:  json_decode($body, true);
来源：http://dali.sysykeji.top/Article/details/gtddaaxtno.html

JS:   await resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gtqkjeivdm.html

TS:   await resp.json()
来源：http://dali.ywan-chungtsiang.top/Article/details/gttarmhstx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.tianlin.xyz/Article/details/gtqsuvioji.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfryroiwj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cashguo.top/Article/details/gtynzmbwmq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj202588.top/Article/details/gtgtvjmppt.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj20258888.top/Article/details/gtlpgxfuzt.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinqigufen.top/Article/details/gttxmkkyku.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jqgfzy.top/Article/details/gtflvwylxx.html

JS:   resp.ok;  resp.status
来源：http://dali.316326.xyz/Article/details/gtodnpjuyn.html

TS:   resp.ok;  resp.status
来源：http://dali.tian-w.cn/Article/details/gtfzimlvqk.html

Java: resp.statusCode()
来源：http://dali.zycfv.cn/Article/details/gtjwrfwmci.html

Go:   resp.StatusCode
来源：http://dali.quarkkingdee.top/Article/details/gtyrweliup.html

Ruby: resp.code.to_i
来源：http://dali.havefunace.top/Article/details/gtquxgnyqh.html

C#:   (int)resp.StatusCode
来源：http://dali.cdnleiting.top/Article/details/gthaihzyaq.html

[L08] 并发请求多个地址
来源：http://dali.snrcjt.cn/Article/details/gtxlanhieg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yj20258888.top/Article/details/gtfdjlixdc.html

PHP:  curl_multi_init() 系列
来源：http://dali.zdqjudy.top/Article/details/gthjxcbzjj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbniczdnl.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cqqwz.cn/Article/details/gtjznkgbfg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zdqjudy.top/Article/details/gtsjwevtqz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.9152youxi.cn/Article/details/gtclkixbap.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.dashuyun.cn/Article/details/gtqltgydxx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj20258.top/Article/details/gtjqcdtsfq.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtjixavmsr.html

M. 命令行 / 进程 / 环境
来源：http://dali.quarkkingdee.top/Article/details/gtwoslwwwx.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtnpsqnyyr.html

[M01] 读取命令行参数
来源：http://dali.snrcjt.cn/Article/details/gthyivxnie.html

Py:   sys.argv[1:]
来源：http://dali.ivvv.top/Article/details/gtwicuszbh.html

PHP:  $argv;  $argc;
来源：http://dali.nanxuanxn.top/Article/details/gtysjjnyon.html

JS:   process.argv.slice(2)
来源：http://dali.yuanzhike.top/Article/details/gttgzpvozv.html

TS:   process.argv.slice(2)
来源：http://dali.yj20258.top/Article/details/gtfgqbkpgn.html

Java: args 数组（main 方法参数）
来源：http://dali.haohaochexian.top/Article/details/gtgbsnkhvs.html

Go:   os.Args[1:]
来源：http://dali.cheryme.top/Article/details/gthwmqyuju.html

Ruby: ARGV
来源：http://dali.shangyingyoupin.top/Article/details/gtkpybjqso.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xuanzx.com/Article/details/gthnnmfjwf.html

[M02] 读取环境变量
来源：http://dali.gogol.net.cn/Article/details/gtownxjaul.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gtegsundgq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nwbrower.top/Article/details/gtcpbmtigo.html

JS:   process.env.HOME
来源：http://dali.shzxlz.cn/Article/details/gtivsembjy.html

TS:   process.env.HOME
来源：http://dali.feifeiyinyue.top/Article/details/gtuyptaaly.html

Java: System.getenv("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuqqqcdfy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gtnevycqwx.html

Ruby: ENV["HOME"]
来源：http://dali.xylfe.cn/Article/details/gtvpkjgjek.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yueranfly.top/Article/details/gtuubrazjz.html

[M03] 执行外部命令
来源：http://dali.ywan-chungtsiang.top/Article/details/gttwlgqwnn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.havefunace.top/Article/details/gtdzujmhjb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hongshengwenyu.top/Article/details/gthwbahwib.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gttqnsfdre.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hammf.cn/Article/details/gtrafxddqw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhengqikj.top/Article/details/gthsbfwena.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sysykeji.top/Article/details/gtucugdezv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hysaishi.cn/Article/details/gtgrvtwpud.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yongpay.top/Article/details/gtohzkvija.html

[M04] 获取当前工作目录
来源：http://dali.jqgufenzy.top/Article/details/gtdqoenhmw.html

Py:   os.getcwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwczxknbj.html

PHP:  getcwd();
来源：http://dali.hongshengwenyu.top/Article/details/gtdflmbmza.html

JS:   process.cwd()
来源：http://dali.tianlin.xyz/Article/details/gtahdskusf.html

TS:   process.cwd()
来源：http://dali.xziqi.cn/Article/details/gtqmzeudbx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.dashuyun.cn/Article/details/gtybvwiomg.html

Go:   os.Getwd()
来源：http://dali.havefunace.top/Article/details/gtydvllotj.html

Ruby: Dir.pwd
来源：http://dali.yanxiufei.cn/Article/details/gtqvcbzils.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.aizwys.cn/Article/details/gtjifzpsyg.html

[M05] 设置退出码
来源：http://dali.dashuyun.cn/Article/details/gtmszzfmwa.html

Py:   sys.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteonitdyy.html

PHP:  exit(1);
来源：http://dali.vqdsnc.cn/Article/details/gtyjpmllyz.html

JS:   process.exit(1)
来源：http://dali.guannengcc.top/Article/details/gtphreuuii.html

TS:   process.exit(1)
来源：http://dali.wangdashe.top/Article/details/gtmivwuexi.html

Java: System.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gtxwwllikq.html

Go:   os.Exit(1)
来源：http://dali.daria6918.cn/Article/details/gtcttaggtl.html

Ruby: exit 1
来源：http://dali.pengpengdd.cyou/Article/details/gtfxxatafn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xziqi.cn/Article/details/gtqmuuadao.html

[M06] 向标准错误输出
来源：http://dali.nanxuanxn.top/Article/details/gtxdrhpytg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xuetiantiany.cn/Article/details/gtyrjoiybw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.wangdashe.top/Article/details/gtucvpuetj.html

JS:   console.error("err")
来源：http://dali.jiagoushi.top/Article/details/gtcmqrhkrt.html

TS:   console.error("err")
来源：http://dali.gaohongyu789.top/Article/details/gtupdgipis.html

Java: System.err.println("err")
来源：http://dali.cucudq.cn/Article/details/gtsnxssiig.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hywenlv.cn/Article/details/gtbgoanqlr.html

Ruby: warn "err"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxjjkcout.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shuidangran.top/Article/details/gtqcjdvkeg.html

[M07] 判断是否为主入口
来源：http://dali.yvedp.cn/Article/details/gtryltbxzz.html

Py:   if __name__ == "__main__":
来源：http://dali.hammf.cn/Article/details/gtrtzkidce.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hongshengwenyu.top/Article/details/gtltkhcrut.html

JS:   require.main === module
来源：http://dali.gogol.net.cn/Article/details/gtsfunonrd.html

TS:   require.main === module
来源：http://dali.vqdsnc.cn/Article/details/gthgokzfaq.html

Java: public static void main(String[] args)
来源：http://dali.fzhhl.top/Article/details/gtybyokkot.html

Go:   func main()
来源：http://dali.yj202588.top/Article/details/gtyxaxtyxo.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.havefunace.top/Article/details/gtfuvorqjr.html

C#:   static void Main(string[] args)
来源：http://dali.xuetiantiany.cn/Article/details/gtufbsatbd.html

[M08] 获取系统与运行时信息
来源：http://dali.zhiwuduotai.top/Article/details/gtbpjsvoqs.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinghuilouyu.cn/Article/details/gtdbciaovf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shanyushiyangtech.top/Article/details/gtbhmjddbr.html

JS:   process.platform;  process.version
来源：http://dali.jqgufenzy.top/Article/details/gtmjzvffrz.html

TS:   process.platform;  process.version
来源：http://dali.shangyingyoupin.top/Article/details/gtejznfunl.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ehwqpu.com/Article/details/gtymmjsvmq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj20258.top/Article/details/gtkeyyqbfa.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.guannengcc.top/Article/details/gthoqrhcoo.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cucudq.cn/Article/details/gtsdkpwyug.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtttfqsmww.html

N. 数据结构与算法
来源：http://dali.gotoacloud.top/Article/details/gtvlkawhxs.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtvwtnynxl.html

[N01] 二分查找（有序数组）
来源：http://dali.dianchejie.cn/Article/details/gtvoundnhi.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtgupqydna.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhiwuduotai.top/Article/details/gtohkyuqdq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.0kj1m.cn/Article/details/gtizjhwtpu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daxiang520.top/Article/details/gtjmkmotnu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtdemplplr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtfmpfnpqi.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xziqi.cn/Article/details/gtpmvzwdfg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtfoztlewo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenzaomai.com/Article/details/gtynehdmar.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ybcxt.top/Article/details/gtpypvbvsr.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nanxuanxn.top/Article/details/gtljxbtlnr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jqgfzy.top/Article/details/gtiysdnnnp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258.top/Article/details/gtyoifixsp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.nwbrower.top/Article/details/gthgltuvnu.html

Go:   slices.Sort(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtbovdfadu.html

Ruby: arr.sort
来源：http://dali.nanxuanxn.top/Article/details/gtdwubebtc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.bjfxy.top/Article/details/gtmpjjtzca.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gtjqccgsxj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yueranfly.top/Article/details/gtqwgnxypi.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ydzc1.top/Article/details/gtcvbqtfyq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.quarkkingdee.top/Article/details/gtjwjwpyaf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenjidiqi.icu/Article/details/gtjhxuphmk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gtapkjegyd.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xuanzx.com/Article/details/gtdpmeptht.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.feifeiyinyue.top/Article/details/gtcecjkqop.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sysykeji.top/Article/details/gtjiclzqdx.html

[N04] 斐波那契数列
来源：http://dali.yj202588.top/Article/details/gtmmrijfzz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yvedp.cn/Article/details/gteydxoicm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.nwbrower.top/Article/details/gtuozqbpoe.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zycfv.cn/Article/details/gtvdbrfycr.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenzaomai.com/Article/details/gtclmrrnue.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.haohaochexian.top/Article/details/gtsphhdrcl.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yuanzhike.top/Article/details/gtyqmngoiv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtqfdpqmvx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.haohaochexian.top/Article/details/gtfxqmkjhr.html

[N05] 最大公约数
来源：http://dali.chenzaomai.com/Article/details/gtllflsvsp.html

Py:   math.gcd(a, b)
来源：http://dali.pengpengdd.cyou/Article/details/gtsxzjiicf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhoulong.xyz/Article/details/gtgvbegfws.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenzaomai.com/Article/details/gtuewtypvx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xinyue.icu/Article/details/gtfhrrbvjx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cucudq.cn/Article/details/gtkkvjduys.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.svipenyu.cn/Article/details/gtgecgqrku.html

Ruby: a.gcd(b)
来源：http://dali.hnqzz.top/Article/details/gtwrnfsecq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkjjrlzra.html

[N06] 判断回文字符串
来源：http://dali.tianlin.xyz/Article/details/gtirpmathm.html

Py:   s == s[::-1]
来源：http://dali.sufxvd.cn/Article/details/gtophcpqno.html

PHP:  $s === strrev($s);
来源：http://dali.tanke756.top/Article/details/gthkitfneu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gtpgpqlffc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gtqetrpfoc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiqkzdcjw.html

Go:   // 双指针从两端比较
来源：http://dali.zhixingplan.top/Article/details/gthntycjbv.html

Ruby: s == s.reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gthwbtaxau.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cdnleiting.top/Article/details/gtkdxubogj.html

[N07] 两数之和（返回下标）
来源：http://dali.zhaomingkeji.xyz/Article/details/gthzgvxwyw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.meibo888.top/Article/details/gtsfcrmsjp.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sweek.top/Article/details/gtxxgsslql.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhiwuduotai.top/Article/details/gtoawqrelm.html

TS:   // 手写 Map<string, number>
来源：http://dali.jiagoushi.top/Article/details/gtmzxtvhvo.html

Java: // 手写 HashMap
来源：http://dali.guowangkeji.top/Article/details/gtadkolfml.html

Go:   // 手写 map[int]int
来源：http://dali.zhixingplan.top/Article/details/gtfbitvmhv.html

Ruby: // 手写 Hash
来源：http://dali.zycfv.cn/Article/details/gtngquoekv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xuetiantiany.cn/Article/details/gtnchinddi.html

[N08] 生成全排列
来源：http://dali.yj202588.top/Article/details/gtiuznvapk.html

Py:   itertools.permutations(arr)
来源：http://dali.aizwys.cn/Article/details/gtzmqpqydg.html

PHP:  // 手写递归交换
来源：http://dali.yueranfly.top/Article/details/gtizeunhst.html

JS:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtuoiiuboa.html

TS:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gtxcmdmijj.html

Java: // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtloddmzxn.html

Go:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gtwjrvbjtz.html

Ruby: arr.permutation.to_a
来源：http://dali.cdnleiting.top/Article/details/gtxwtetfvn.html

C#:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gtlgqmgfsb.html

[N09] 栈与队列
来源：http://dali.ydzc1.top/Article/details/gtuetucgst.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.kuanghao11.cn/Article/details/gtpytdepkm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.nwbrower.top/Article/details/gtmvklgxpd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.daria6918.cn/Article/details/gtgbhpeikr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.andypj.xyz/Article/details/gtcwhgzuly.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yvedp.cn/Article/details/gteodcczdx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvkhrvkxh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.smart0.xyz/Article/details/gtywfwdcvj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gzhubu.top/Article/details/gtfstcsokk.html

[N10] 链表节点定义
来源：http://dali.zhoulong.xyz/Article/details/gtdxvkszwj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinqigufen.top/Article/details/gtxszopnts.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.chenlongwang.top/Article/details/gtvmjloubn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yuanzhike.top/Article/details/gtlhpnjyrm.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gaohongyu789.top/Article/details/gthncsxgsa.html

Java: class Node { int v; Node next; }
来源：http://dali.birdmap.top/Article/details/gtkzyjqtvo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shzxlz.cn/Article/details/gtbpyzjcnv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.fzhhl.top/Article/details/gtnkmqsfyo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrmkagasu.html

[N11] 二叉树中序遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtulcfgnsw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hywenlv.cn/Article/details/gttsxyjaob.html

PHP:  // 手写递归函数
来源：http://dali.quarkkingdee.top/Article/details/gtfvbyxbjz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gtexpjhkwy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.meibo888.top/Article/details/gtwxzrrtvo.html

Java: // 手写递归
来源：http://dali.yueranfly.top/Article/details/gtozexbkdo.html

Go:   // 手写递归
来源：http://dali.ehwqpu.com/Article/details/gtksdfubbv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.wangshuangyany.cn/Article/details/gtpfkjmfda.html

C#:   // 手写递归
来源：http://dali.jqgufenzy.top/Article/details/gthrllvelq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jlsjyb.cn/Article/details/gtjhjasogf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.sweek.top/Article/details/gtsakzoerl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ydzc1.top/Article/details/gtilshxvwi.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aibaodan.cn/Article/details/gtgjvpirbu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daxiang520.top/Article/details/gtrorfgmjf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jiagoushi.top/Article/details/gthdsafkoa.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.c1oappe.top/Article/details/gtiwimcolq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xziqi.cn/Article/details/gteeyinkmw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guowangkeji.top/Article/details/gtqtlqazef.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtqigicrlu.html

O. 并发与异步
来源：http://dali.xuanzx.com/Article/details/gtdjgjllof.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtwmdlqfnf.html

[O01] 启动一个线程
来源：http://dali.chenzaomai.com/Article/details/gtrvucoqhu.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yonumen.top/Article/details/gtpzcrnkew.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.daria6918.cn/Article/details/gtjnvcdhnq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.sweek.top/Article/details/gtijpsbajq.html

TS:   // 同 JS
来源：http://dali.sufxvd.cn/Article/details/gtubwaotqh.html

Java: new Thread(() -> f()).start()
来源：http://dali.ehwqpu.com/Article/details/gtjopvlccz.html

Go:   go f()
来源：http://dali.guannengcc.top/Article/details/gtwocysqoa.html

Ruby: Thread.new { f }
来源：http://dali.snrcjt.cn/Article/details/gtoqcfnsdn.html

C#:   Task.Run(() => F());
来源：http://dali.zhixingplan.top/Article/details/gtjsvhypyl.html

[O02] 使用线程池
来源：http://dali.hysaishi.cn/Article/details/gtfkezbcyb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.mhx1999.top/Article/details/gtwnloquig.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.nanxinkj.top/Article/details/gtklgdfcwk.html

JS:   // worker_threads 线程池
来源：http://dali.hammf.cn/Article/details/gtdedarwzm.html

TS:   // worker_threads 线程池
来源：http://dali.chenzaomai.com/Article/details/gtgunzqemr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hnxiangtu.top/Article/details/gtlmcvdqbz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.nanxinkj.top/Article/details/gtmciowuei.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhoulong.xyz/Article/details/gtuczapabp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yj202588.top/Article/details/gtmysgilvz.html

[O03] 加锁保护共享数据
来源：http://dali.dianchejie.cn/Article/details/gtpvcelpvk.html

Py:   with lock: shared += 1
来源：http://dali.wangshuangyany.cn/Article/details/gtuokdyrff.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cqqwz.cn/Article/details/gtqadvbepd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yanxiufei.cn/Article/details/gtgqduisxu.html

TS:   // 同 JS
来源：http://dali.nwbrower.top/Article/details/gtwiguazad.html

Java: synchronized (this) { shared++; }
来源：http://dali.svipenyu.cn/Article/details/gtdvbimsvb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.haohaochexian.top/Article/details/gtxjajgbrp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yongpay.top/Article/details/gtvordumyk.html

C#:   lock (gate) { shared++; }
来源：http://dali.bjfxy.top/Article/details/gtcjhrkewd.html

[O04] 定义异步函数并等待
来源：http://dali.ivvv.top/Article/details/gtxspgesvv.html

Py:   async def f():⏎    await g()
来源：http://dali.yj202588.top/Article/details/gtfleujouj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yvedp.cn/Article/details/gtqsyjrcak.html

JS:   async function f() { await g(); }
来源：http://dali.jyoumei.cn/Article/details/gtcajbsfph.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.kuanghao11.cn/Article/details/gtezoeddnp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shanyushiyangkeji.top/Article/details/gtckoowxwe.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.tian-w.cn/Article/details/gtfqsdqzre.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hongshengwenyu.top/Article/details/gthwqhdcqe.html

C#:   async Task F() { await G(); }
来源：http://dali.birdmap.top/Article/details/gtvqqliokm.html

[O05] 并发执行并等待全部完成
来源：http://dali.c1oappe.top/Article/details/gtabyeolln.html


<!-- 参考信息 -->