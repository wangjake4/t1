代发 wailian999

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.chenjidiqi.icu/Article/details/gtzzwbmczo.html

JS:   await fetch(url)
来源：http://dali.wangshuangyany.cn/Article/details/gtquuobxqx.html

TS:   await fetch(url)
来源：http://dali.guowangkeji.top/Article/details/gtisaittbk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.nwbrower.top/Article/details/gtlcijcnzi.html

Go:   resp, err := http.Get(url)
来源：http://dali.dianchejie.cn/Article/details/gtefndkysw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.iojbl.cn/Article/details/gtjmlrckzo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.andypj.xyz/Article/details/gtnnoyapom.html

[L02] 发送 POST JSON
来源：http://dali.cashguo.top/Article/details/gtflhbeljf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhengqikj.top/Article/details/gtxlljuvqx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.meibo888.top/Article/details/gtgxahfvvk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tanke756.top/Article/details/gtzdnsajlo.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.mhx1999.top/Article/details/gtsboawluu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenlongwang.top/Article/details/gtwqrzyilk.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yangfankeji.com/Article/details/gtcpposqkh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yuanzhike.top/Article/details/gtpqcapccr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.quarkkingdee.top/Article/details/gtfnkbioow.html

[L03] 设置自定义请求头
来源：http://dali.snrcjt.cn/Article/details/gtejaujlyf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yuxming.cn/Article/details/gtauoepynx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.wangdashe.top/Article/details/gtfdccpmbb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hywenlv.cn/Article/details/gtwljbssjg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtazzhhhvx.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zycfv.cn/Article/details/gtnebqgrpc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.aibaodan.cn/Article/details/gtmnikpntz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.aibaodan.cn/Article/details/gtwhdytrmi.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hywenlv.cn/Article/details/gtnavmqksg.html

[L04] 设置超时
来源：http://dali.gaohongyu789.top/Article/details/gtgpvgygor.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gaohongyu789.top/Article/details/gtcjjejhsl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinqigfzy.top/Article/details/gtkpifxdzu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cqqwz.cn/Article/details/gtwewyrpwi.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxuanxn.top/Article/details/gtdiodezvl.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.quarkkingdee.top/Article/details/gtgwjpsvxl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yangfankeji.com/Article/details/gtkirifmwa.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cheryme.top/Article/details/gtfmrgrocl.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinqigufen.top/Article/details/gtuajwckan.html

[L05] 上传文件（multipart）
来源：http://dali.hfpthk.cn/Article/details/gtijnlqzuq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.svipenyu.cn/Article/details/gtxztbpyaa.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hysaishi.cn/Article/details/gtdwnvqoib.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xziqi.cn/Article/details/gteqclrqxh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.guowangkeji.top/Article/details/gtakgvxwyz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.tanke756.top/Article/details/gtdjglboqj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.daxiang520.top/Article/details/gtpyvcvwie.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.feifeiyinyue.top/Article/details/gtigckcucx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.wangdashe.top/Article/details/gtqxawzndv.html

[L06] 解析响应为 JSON
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgwdwontr.html

Py:   resp.json()
来源：http://dali.cashguo.top/Article/details/gtmvicbazb.html

PHP:  json_decode($body, true);
来源：http://dali.zhiwuduotai.top/Article/details/gteoiosirv.html

JS:   await resp.json()
来源：http://dali.yj20258888.top/Article/details/gttbbzpego.html

TS:   await resp.json()
来源：http://dali.jinghuilouyu.cn/Article/details/gtzrnmlceo.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zycfv.cn/Article/details/gtndfizuaf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.smart0.xyz/Article/details/gtdloxggdn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tanke756.top/Article/details/gtuxaxjrya.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbxwvnzjv.html

[L07] 处理 HTTP 状态码
来源：http://dali.dianchejie.cn/Article/details/gtzolkgwgj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shuidangran.top/Article/details/gtghfadwqa.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hnqzz.top/Article/details/gtttloywph.html

JS:   resp.ok;  resp.status
来源：http://dali.zhengqikj.top/Article/details/gtlriywxvj.html

TS:   resp.ok;  resp.status
来源：http://dali.smart0.xyz/Article/details/gtxxiwgiob.html

Java: resp.statusCode()
来源：http://dali.yueranfly.top/Article/details/gtumwuyuhh.html

Go:   resp.StatusCode
来源：http://dali.jinqigfzy.top/Article/details/gtxsislkzm.html

Ruby: resp.code.to_i
来源：http://dali.yangfankeji.com/Article/details/gtzhijgcjm.html

C#:   (int)resp.StatusCode
来源：http://dali.zhengqikj.top/Article/details/gtkoloenfb.html

[L08] 并发请求多个地址
来源：http://dali.mhx1999.top/Article/details/gtztqbmugh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhiwuduotai.top/Article/details/gtfoyafkno.html

PHP:  curl_multi_init() 系列
来源：http://dali.hnqzz.top/Article/details/gtvcccxgyk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxuanxn.top/Article/details/gtzdmbuuuj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jyoumei.cn/Article/details/gtjqgxfkbt.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.snrcjt.cn/Article/details/gtqvyajfyi.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shzxlz.cn/Article/details/gtmnnxavqw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gotoacloud.top/Article/details/gtsjuookok.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gthrlwsqgg.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtnkhqosio.html

M. 命令行 / 进程 / 环境
来源：http://dali.yangfankeji.com/Article/details/gtioezhmvz.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtuujazqnc.html

[M01] 读取命令行参数
来源：http://dali.0kj1m.cn/Article/details/gtbkqwzond.html

Py:   sys.argv[1:]
来源：http://dali.havefunace.top/Article/details/gtrlmccwvf.html

PHP:  $argv;  $argc;
来源：http://dali.hysaishi.cn/Article/details/gtiqppiisb.html

JS:   process.argv.slice(2)
来源：http://dali.vqdsnc.cn/Article/details/gtobawkqid.html

TS:   process.argv.slice(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthbwbfdym.html

Java: args 数组（main 方法参数）
来源：http://dali.ehwqpu.com/Article/details/gtptvwbcye.html

Go:   os.Args[1:]
来源：http://dali.gzhubu.top/Article/details/gtntrknxjp.html

Ruby: ARGV
来源：http://dali.ehwqpu.com/Article/details/gtqbecyzsn.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinqigufen.top/Article/details/gthpcnfvwj.html

[M02] 读取环境变量
来源：http://dali.yangfankeji.com/Article/details/gtnuxaawtm.html

Py:   os.environ.get("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gtaeqjznih.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hfpthk.cn/Article/details/gtkdwmgmra.html

JS:   process.env.HOME
来源：http://dali.yueranfly.top/Article/details/gtyhckfktp.html

TS:   process.env.HOME
来源：http://dali.guannengcc.top/Article/details/gttifuvyxf.html

Java: System.getenv("HOME")
来源：http://dali.yongpay.top/Article/details/gtrbhzmnns.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj202588.top/Article/details/gtxnvnmqhp.html

Ruby: ENV["HOME"]
来源：http://dali.aizwys.cn/Article/details/gtpestoqxc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtivqpykhi.html

[M03] 执行外部命令
来源：http://dali.yueranfly.top/Article/details/gtjobacbxb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xuetiantiany.cn/Article/details/gtubgphpqa.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shangyingyoupin.top/Article/details/gtkwjmdlbq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hongshengwenyu.top/Article/details/gtbyblnqkz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xylfe.cn/Article/details/gtfhdiunlz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sxryk.cn/Article/details/gtjmbjjuku.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hywenlv.cn/Article/details/gtyitdaymz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yj202588.top/Article/details/gtlfohiegq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cheryme.top/Article/details/gtkgulzejw.html

[M04] 获取当前工作目录
来源：http://dali.hnxiangtu.top/Article/details/gtpnzqvqul.html

Py:   os.getcwd()
来源：http://dali.aizwys.cn/Article/details/gtoosvigmf.html

PHP:  getcwd();
来源：http://dali.jiagoushi.top/Article/details/gtzgbakuuq.html

JS:   process.cwd()
来源：http://dali.hnxiangtu.top/Article/details/gtuykoeyjd.html

TS:   process.cwd()
来源：http://dali.gogol.net.cn/Article/details/gtzixcefbn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.mhx1999.top/Article/details/gtiteciefe.html

Go:   os.Getwd()
来源：http://dali.ehwqpu.com/Article/details/gtfmlewpzc.html

Ruby: Dir.pwd
来源：http://dali.daxiang520.top/Article/details/gtyottahaq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.c1oappe.top/Article/details/gtqwwjpbur.html

[M05] 设置退出码
来源：http://dali.chenzaomai.com/Article/details/gtzsbkbnep.html

Py:   sys.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtzvomrret.html

PHP:  exit(1);
来源：http://dali.cqqwz.cn/Article/details/gtmiwzlysm.html

JS:   process.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtwvrqvaqc.html

TS:   process.exit(1)
来源：http://dali.tian-w.cn/Article/details/gtqaabavns.html

Java: System.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtyzyjrpse.html

Go:   os.Exit(1)
来源：http://dali.yj202588.top/Article/details/gtmyeejuwr.html

Ruby: exit 1
来源：http://dali.hnqzz.top/Article/details/gtvpnwgyfc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shzxlz.cn/Article/details/gthuuoliqu.html

[M06] 向标准错误输出
来源：http://dali.snrcjt.cn/Article/details/gtfalpngpo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hongshengwenyu.top/Article/details/gtmcfcchvg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cdnleiting.top/Article/details/gtldnwdbfn.html

JS:   console.error("err")
来源：http://dali.dashuyun.cn/Article/details/gtusgodvdm.html

TS:   console.error("err")
来源：http://dali.guowangkeji.top/Article/details/gtxihsgwyg.html

Java: System.err.println("err")
来源：http://dali.mhx1999.top/Article/details/gtcsmoopjf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkgxvtsfh.html

Ruby: warn "err"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtswhhadtn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ivvv.top/Article/details/gthuqiaihj.html

[M07] 判断是否为主入口
来源：http://dali.zhoulong.xyz/Article/details/gtqdcoodxp.html

Py:   if __name__ == "__main__":
来源：http://dali.yj20258.top/Article/details/gtjnzruyqz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yonumen.top/Article/details/gtgmgjvbke.html

JS:   require.main === module
来源：http://dali.havefunace.top/Article/details/gthzoroncb.html

TS:   require.main === module
来源：http://dali.zycfv.cn/Article/details/gtxeaxcmtq.html

Java: public static void main(String[] args)
来源：http://dali.pycfn.com/Article/details/gtsvhpznhg.html

Go:   func main()
来源：http://dali.xinyue.icu/Article/details/gtydxvngvb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.smart0.xyz/Article/details/gttehemorp.html

C#:   static void Main(string[] args)
来源：http://dali.9152youxi.cn/Article/details/gtnvywzmpb.html

[M08] 获取系统与运行时信息
来源：http://dali.shangyingyoupin.top/Article/details/gttkmcmobf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gotoacloud.top/Article/details/gtwmxihugr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yj20258888.top/Article/details/gthdjlobet.html

JS:   process.platform;  process.version
来源：http://dali.hysaishi.cn/Article/details/gtduurqnfv.html

TS:   process.platform;  process.version
来源：http://dali.chenjidiqi.icu/Article/details/gtbzewvbhr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yonumen.top/Article/details/gtsrgfxuns.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xuetiantiany.cn/Article/details/gthdursezx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.fzhhl.top/Article/details/gtodmqztzo.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yanxiufei.cn/Article/details/gtqhpumlwn.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbytojfim.html

N. 数据结构与算法
来源：http://dali.hnxiangtu.top/Article/details/gtkukaajvl.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtgtthdqvf.html

[N01] 二分查找（有序数组）
来源：http://dali.zdqjudy.top/Article/details/gtfyjmqtcx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cheryme.top/Article/details/gthieziykp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzjvaaedw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnqzz.top/Article/details/gtdlmtbhuk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daxiang520.top/Article/details/gtmommbxzg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtvggxdfib.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cashguo.top/Article/details/gtxlibcxmb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj20258.top/Article/details/gtjljpitnx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.birdmap.top/Article/details/gtareertqz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hywenlv.cn/Article/details/gtexdghcmw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuanzx.com/Article/details/gtwpxfhowx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.9152youxi.cn/Article/details/gtyusmgtmi.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxinkj.top/Article/details/gtdesegowp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gtwvbosgvw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.daria6918.cn/Article/details/gtnprxekqo.html

Go:   slices.Sort(arr)
来源：http://dali.tanke756.top/Article/details/gttubmsxnp.html

Ruby: arr.sort
来源：http://dali.smart0.xyz/Article/details/gttmnkzfpq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cucudq.cn/Article/details/gtyimufkbj.html

[N03] 快速排序（分治示例）
来源：http://dali.haohaochexian.top/Article/details/gtxxeduywn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cqqwz.cn/Article/details/gtkofhsklm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.vqdsnc.cn/Article/details/gtkwlhtejz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigfzy.top/Article/details/gtvnwqdrvq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxuanxn.top/Article/details/gtyghsdhjo.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.chenlongwang.top/Article/details/gtqsudpakt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.wangdashe.top/Article/details/gtaoxpojzt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnxmsxxkl.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jiagoushi.top/Article/details/gtoojgphta.html

[N04] 斐波那契数列
来源：http://dali.hongshengwenyu.top/Article/details/gtqjhsyqjf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258888.top/Article/details/gttmjpizwz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cheryme.top/Article/details/gtoajtvrgn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtrvdguuun.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gtndzpnyfr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ydzc1.top/Article/details/gtfhwwpyqq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.haohaochexian.top/Article/details/gtjzavsshz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.wangdashe.top/Article/details/gtwagyrwpc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gtofuprngx.html

[N05] 最大公约数
来源：http://dali.guowangkeji.top/Article/details/gtthwhpawy.html

Py:   math.gcd(a, b)
来源：http://dali.daxiang520.top/Article/details/gtmzjefbon.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.vqdsnc.cn/Article/details/gtjqdsyojz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxinkj.top/Article/details/gtcfrldbhf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dashuyun.cn/Article/details/gtqaexaqsf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shuidangran.top/Article/details/gtifrrrxai.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.gogol.net.cn/Article/details/gtyntbyzqw.html

Ruby: a.gcd(b)
来源：http://dali.havefunace.top/Article/details/gtxrdjkkly.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shzxlz.cn/Article/details/gtygryujgc.html

[N06] 判断回文字符串
来源：http://dali.andypj.xyz/Article/details/gtrjiifotj.html

Py:   s == s[::-1]
来源：http://dali.fzhhl.top/Article/details/gtujajxdhd.html

PHP:  $s === strrev($s);
来源：http://dali.jinqigfzy.top/Article/details/gtvirofgma.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdeikjdsf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtmfdxdyjt.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gtovnnnucl.html

Go:   // 双指针从两端比较
来源：http://dali.hnqzz.top/Article/details/gtbcnindcm.html

Ruby: s == s.reverse
来源：http://dali.chenlongwang.top/Article/details/gtfzktshbu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cdnleiting.top/Article/details/gtchyrzkcf.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gtrrhnlwsc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinghuilouyu.cn/Article/details/gtofcvvxqt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuarwpnkt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.tianlin.xyz/Article/details/gtybqaxsdj.html

TS:   // 手写 Map<string, number>
来源：http://dali.jianghu66.top/Article/details/gtltacnnfv.html

Java: // 手写 HashMap
来源：http://dali.hammf.cn/Article/details/gtkcsfikyd.html

Go:   // 手写 map[int]int
来源：http://dali.feifeiyinyue.top/Article/details/gtbidgoxwf.html

Ruby: // 手写 Hash
来源：http://dali.sysykeji.top/Article/details/gtmerkdorr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.pycfn.com/Article/details/gtfnabcopb.html

[N08] 生成全排列
来源：http://dali.hongshengwenyu.top/Article/details/gttrmacekb.html

Py:   itertools.permutations(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtznwvpnye.html

PHP:  // 手写递归交换
来源：http://dali.hywenlv.cn/Article/details/gtfrrnlkld.html

JS:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gtdwjlcwin.html

TS:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtovtrjyrx.html

Java: // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gtininmbiu.html

Go:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gtaqbimgoe.html

Ruby: arr.permutation.to_a
来源：http://dali.yongpay.top/Article/details/gtkcjwyryw.html

C#:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gtyqnwymed.html

[N09] 栈与队列
来源：http://dali.zhengqikj.top/Article/details/gtfrrrddkg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yuxming.cn/Article/details/gtymzoeaux.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gtnokqezus.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sxryk.cn/Article/details/gtdmanjssw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ybcxt.top/Article/details/gtnhewnnfg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zdqjudy.top/Article/details/gtiaknptob.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shzxlz.cn/Article/details/gtwvkqouly.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cdnleiting.top/Article/details/gtxjnabuwk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gtokqgfwcq.html

[N10] 链表节点定义
来源：http://dali.jqgufenzy.top/Article/details/gtjxypdzox.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhongyouzk.top/Article/details/gtscbiwune.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yonumen.top/Article/details/gthgenfleh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gotoacloud.top/Article/details/gtdfcsbcup.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhengqikj.top/Article/details/gteohrrlee.html

Java: class Node { int v; Node next; }
来源：http://dali.svipenyu.cn/Article/details/gtzglgcwop.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.fengsongda.top/Article/details/gtjugtjvpd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.havefunace.top/Article/details/gtaalqsfwt.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkjsvjufy.html

[N11] 二叉树中序遍历
来源：http://dali.vqdsnc.cn/Article/details/gtuxwkbpkp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gotoacloud.top/Article/details/gthcdgpbxd.html

PHP:  // 手写递归函数
来源：http://dali.cashguo.top/Article/details/gtuolpxntb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258888.top/Article/details/gttiylcsle.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwwmgbbcd.html

Java: // 手写递归
来源：http://dali.mhx1999.top/Article/details/gtnxwzgfip.html

Go:   // 手写递归
来源：http://dali.xuanzx.com/Article/details/gtsgjtgfmi.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xziqi.cn/Article/details/gtktnpnrom.html

C#:   // 手写递归
来源：http://dali.nanxinkj.top/Article/details/gtebfepdkp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jianghu66.top/Article/details/gtglgqezul.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.316326.xyz/Article/details/gtcptgmcrk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.chenlongwang.top/Article/details/gtmfjghtxn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daxiang520.top/Article/details/gtrzxkpxoo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.andypj.xyz/Article/details/gtxtavepkh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pengpengdd.cyou/Article/details/gtgttbetuv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xziqi.cn/Article/details/gtvaytpmlf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.havefunace.top/Article/details/gthertcyci.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yueranfly.top/Article/details/gtuqdaqwvu.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtwlspuhrn.html

O. 并发与异步
来源：http://dali.xziqi.cn/Article/details/gtainakcut.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtxzgjbgjz.html

[O01] 启动一个线程
来源：http://dali.tanke756.top/Article/details/gtpswdslvr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.guowangkeji.top/Article/details/gtfyrgvoii.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.guowangkeji.top/Article/details/gtfuoxgxeg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjrbrbfnj.html

TS:   // 同 JS
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzkuyynoe.html

Java: new Thread(() -> f()).start()
来源：http://dali.cdnleiting.top/Article/details/gtehiamfyq.html

Go:   go f()
来源：http://dali.yj20258.top/Article/details/gthpqzlxjr.html

Ruby: Thread.new { f }
来源：http://dali.xylfe.cn/Article/details/gtcsslijpa.html

C#:   Task.Run(() => F());
来源：http://dali.c1oappe.top/Article/details/gtpatxtcoc.html

[O02] 使用线程池
来源：http://dali.yongpay.top/Article/details/gtnzlhifno.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.0kj1m.cn/Article/details/gtbkfttdfq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.gogol.net.cn/Article/details/gtvmhznxws.html

JS:   // worker_threads 线程池
来源：http://dali.guowangkeji.top/Article/details/gtflnfmmrt.html

TS:   // worker_threads 线程池
来源：http://dali.snrcjt.cn/Article/details/gtcqtbrabj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.svipenyu.cn/Article/details/gtgmsxcafi.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cheryme.top/Article/details/gtyevythsr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtehwcvglf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yongpay.top/Article/details/gttnhtodlk.html

[O03] 加锁保护共享数据
来源：http://dali.tanke756.top/Article/details/gtpyfffhaq.html

Py:   with lock: shared += 1
来源：http://dali.birdmap.top/Article/details/gtncitztvv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yangfankeji.com/Article/details/gtkzbpothg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zdqjudy.top/Article/details/gttnwdnjoo.html

TS:   // 同 JS
来源：http://dali.nanxuanxn.top/Article/details/gtbfeyoemp.html

Java: synchronized (this) { shared++; }
来源：http://dali.hongshengwenyu.top/Article/details/gtlzlxwgcg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yonumen.top/Article/details/gtreuswvwb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinqigfzy.top/Article/details/gtpmcqrexw.html

C#:   lock (gate) { shared++; }
来源：http://dali.nwbrower.top/Article/details/gtmtdxqkgt.html

[O04] 定义异步函数并等待
来源：http://dali.nanxuanxn.top/Article/details/gtmcmxkcgo.html

Py:   async def f():⏎    await g()
来源：http://dali.daxiang520.top/Article/details/gtpccuiozk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yanxiufei.cn/Article/details/gtsqdryvru.html

JS:   async function f() { await g(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuwerpwtt.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yonumen.top/Article/details/gtbplomqeu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jqgfzy.top/Article/details/gtfbmgxgsn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cqqwz.cn/Article/details/gtbyqhhkuf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.sweek.top/Article/details/gtvfsysapb.html

C#:   async Task F() { await G(); }
来源：http://dali.cheryme.top/Article/details/gtfkflepxu.html

[O05] 并发执行并等待全部完成
来源：http://dali.birdmap.top/Article/details/gtzoygegrj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqkkczril.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.wangdashe.top/Article/details/gtkduzgdil.html

JS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgiqzxpit.html

TS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmlvdikew.html


<!-- 参考信息 -->