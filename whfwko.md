代发 wailian999

Go:   resp, err := http.Get(url)
来源：http://dali.cashguo.top/Article/details/gtvycrglge.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj20258888.top/Article/details/gtuyuesqfd.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sufxvd.cn/Article/details/gtknvrllvf.html

[L02] 发送 POST JSON
来源：http://dali.guannengcc.top/Article/details/gthpmgytqz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gtlwjugvcy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yangfankeji.com/Article/details/gtlwcgbufj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cucudq.cn/Article/details/gtzrgzulpo.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.andypj.xyz/Article/details/gtpalqxqls.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gtjhwmirmf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.0kj1m.cn/Article/details/gtjyurydbn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.chenlongwang.top/Article/details/gtvaslpsgj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.svipenyu.cn/Article/details/gtiznyrffh.html

[L03] 设置自定义请求头
来源：http://dali.guannengcc.top/Article/details/gtixqdbniv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.bjfxy.top/Article/details/gtpxlvmnpv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.wangdashe.top/Article/details/gtkwltdmxk.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzpxerjgf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shangyingyoupin.top/Article/details/gtjlfvhapd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cashguo.top/Article/details/gtyhwuxsrx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.havefunace.top/Article/details/gtdtgyoklr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.pycfn.com/Article/details/gtbcaeptgd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.fzhhl.top/Article/details/gtitzrdens.html

[L04] 设置超时
来源：http://dali.jinghuilouyu.cn/Article/details/gtoshtizhb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hnxiangtu.top/Article/details/gtuxfusmaw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jqgfzy.top/Article/details/gtfciilmfu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yueranfly.top/Article/details/gtyiuojhdb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgfzy.top/Article/details/gtgcldwowu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yanxiufei.cn/Article/details/gtcmcjorkf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hfpthk.cn/Article/details/gtwjctjfwz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.wangshuangyany.cn/Article/details/gtlzwolilc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.feifeiyinyue.top/Article/details/gtqnhabiwl.html

[L05] 上传文件（multipart）
来源：http://dali.cashguo.top/Article/details/gtojmwwfjw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xuetiantiany.cn/Article/details/gtzfrsywpd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sxryk.cn/Article/details/gtdaynjfvs.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenjidiqi.icu/Article/details/gtiaqtljfw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.daria6918.cn/Article/details/gtimtxccel.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hongshengwenyu.top/Article/details/gtaqxmrlub.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jiagoushi.top/Article/details/gttitwuuyn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.redwolf501.top/Article/details/gtyszmzofk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtzvsykeql.html

[L06] 解析响应为 JSON
来源：http://dali.nanxinkj.top/Article/details/gtlkheevcv.html

Py:   resp.json()
来源：http://dali.xinyue.icu/Article/details/gtcfvocrnq.html

PHP:  json_decode($body, true);
来源：http://dali.hnqzz.top/Article/details/gtjuojbuen.html

JS:   await resp.json()
来源：http://dali.ehwqpu.com/Article/details/gtivwhqvwk.html

TS:   await resp.json()
来源：http://dali.ehwqpu.com/Article/details/gtmtwbakat.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yvedp.cn/Article/details/gtdyarppji.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.redwolf501.top/Article/details/gtvhbqqhua.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cqqwz.cn/Article/details/gthkjlwiee.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cqqwz.cn/Article/details/gtqqascnao.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfxsrrhhq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yanxiufei.cn/Article/details/gtsarhlepm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.pengpengdd.cyou/Article/details/gtpehnpuzj.html

JS:   resp.ok;  resp.status
来源：http://dali.hfpthk.cn/Article/details/gtevcemxcj.html

TS:   resp.ok;  resp.status
来源：http://dali.jinqigfzy.top/Article/details/gtwzuohlaf.html

Java: resp.statusCode()
来源：http://dali.xinyue.icu/Article/details/gtdnkdktzp.html

Go:   resp.StatusCode
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttwtqceso.html

Ruby: resp.code.to_i
来源：http://dali.jlsjyb.cn/Article/details/gtpkywengi.html

C#:   (int)resp.StatusCode
来源：http://dali.snrcjt.cn/Article/details/gtlkvvjdfa.html

[L08] 并发请求多个地址
来源：http://dali.ydzc1.top/Article/details/gtqradbrzz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhoulong.xyz/Article/details/gtxqzcfohv.html

PHP:  curl_multi_init() 系列
来源：http://dali.jiagoushi.top/Article/details/gtvniyluqd.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gtdgihkhlt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dianchejie.cn/Article/details/gtszfgulvj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yanxiufei.cn/Article/details/gtwmwdrrwi.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.9152youxi.cn/Article/details/gtevvtegqi.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ppjwa.cn/Article/details/gtwsjpmayb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yvedp.cn/Article/details/gtiikjffrw.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtwvmsabft.html

M. 命令行 / 进程 / 环境
来源：http://dali.cucudq.cn/Article/details/gtcgzuwdff.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtcufnvfdl.html

[M01] 读取命令行参数
来源：http://dali.yonumen.top/Article/details/gtrrgbwqsw.html

Py:   sys.argv[1:]
来源：http://dali.dashuyun.cn/Article/details/gtlwrraxpr.html

PHP:  $argv;  $argc;
来源：http://dali.aizwys.cn/Article/details/gtweinyejz.html

JS:   process.argv.slice(2)
来源：http://dali.ybcxt.top/Article/details/gtpqkfndwy.html

TS:   process.argv.slice(2)
来源：http://dali.wangdashe.top/Article/details/gtukkekgaw.html

Java: args 数组（main 方法参数）
来源：http://dali.yj20258888.top/Article/details/gtujxawrne.html

Go:   os.Args[1:]
来源：http://dali.pycfn.com/Article/details/gtwhtvbglz.html

Ruby: ARGV
来源：http://dali.hnxiangtu.top/Article/details/gtxgchszuc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jyoumei.cn/Article/details/gtewsirpxd.html

[M02] 读取环境变量
来源：http://dali.c1oappe.top/Article/details/gtltjerrvo.html

Py:   os.environ.get("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gtqdnygtxa.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj20258.top/Article/details/gtnzudjihh.html

JS:   process.env.HOME
来源：http://dali.kuanghao11.cn/Article/details/gtgyzjtmar.html

TS:   process.env.HOME
来源：http://dali.yueranfly.top/Article/details/gthvxdvmpb.html

Java: System.getenv("HOME")
来源：http://dali.mhx1999.top/Article/details/gttbteqwrh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdsbmtgtm.html

Ruby: ENV["HOME"]
来源：http://dali.shzxlz.cn/Article/details/gtskdkwaem.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gtolmiqtjr.html

[M03] 执行外部命令
来源：http://dali.jinyuanbaomall.cn/Article/details/gtogxslihh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhongyouzk.top/Article/details/gtdmlfyldy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xylfe.cn/Article/details/gtszynwffe.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xziqi.cn/Article/details/gtuwmkqxwm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtirvthnmr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hammf.cn/Article/details/gtdmqlczsm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jqgufenzy.top/Article/details/gtcrjbuqvu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xuetiantiany.cn/Article/details/gtwoempyaz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hysaishi.cn/Article/details/gtuzrritjl.html

[M04] 获取当前工作目录
来源：http://dali.cdnleiting.top/Article/details/gtgtdeekwu.html

Py:   os.getcwd()
来源：http://dali.jianghu66.top/Article/details/gtnnntscmm.html

PHP:  getcwd();
来源：http://dali.yj202588.top/Article/details/gtwjcoizsm.html

JS:   process.cwd()
来源：http://dali.fengsongda.top/Article/details/gtgomlpvac.html

TS:   process.cwd()
来源：http://dali.ppjwa.cn/Article/details/gtqhhnsxvf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgxvkaxgv.html

Go:   os.Getwd()
来源：http://dali.9152youxi.cn/Article/details/gtjmxwmzgu.html

Ruby: Dir.pwd
来源：http://dali.jiagoushi.top/Article/details/gtnsczufbp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jiagoushi.top/Article/details/gtykjnfmux.html

[M05] 设置退出码
来源：http://dali.tanke756.top/Article/details/gtovmhrmza.html

Py:   sys.exit(1)
来源：http://dali.daria6918.cn/Article/details/gtmatvbuug.html

PHP:  exit(1);
来源：http://dali.aibaodan.cn/Article/details/gtikwxtgdv.html

JS:   process.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtfkislzxc.html

TS:   process.exit(1)
来源：http://dali.xinyue.icu/Article/details/gtdppsuymh.html

Java: System.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gtylogxfzm.html

Go:   os.Exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtakeavgpp.html

Ruby: exit 1
来源：http://dali.cucudq.cn/Article/details/gtqohiscvt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinqigfzy.top/Article/details/gtiylzrewa.html

[M06] 向标准错误输出
来源：http://dali.jqgfzy.top/Article/details/gtyxkkmmpw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shangyingyoupin.top/Article/details/gtulizciso.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhongyouzk.top/Article/details/gtfgctfjcj.html

JS:   console.error("err")
来源：http://dali.dianchejie.cn/Article/details/gtosemmetn.html

TS:   console.error("err")
来源：http://dali.yonumen.top/Article/details/gtkubiqmdx.html

Java: System.err.println("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjsiaohkq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.smart0.xyz/Article/details/gtuiaruyss.html

Ruby: warn "err"
来源：http://dali.cashguo.top/Article/details/gtklwuisuv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sxryk.cn/Article/details/gttpmcuobn.html

[M07] 判断是否为主入口
来源：http://dali.yangfankeji.com/Article/details/gtgwrngryw.html

Py:   if __name__ == "__main__":
来源：http://dali.aibaodan.cn/Article/details/gtkggimbvo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.birdmap.top/Article/details/gtukrzejsw.html

JS:   require.main === module
来源：http://dali.xuanzx.com/Article/details/gtywotrntg.html

TS:   require.main === module
来源：http://dali.jinghuilouyu.cn/Article/details/gtvdoyysjc.html

Java: public static void main(String[] args)
来源：http://dali.haohaochexian.top/Article/details/gtaoyekbke.html

Go:   func main()
来源：http://dali.pycfn.com/Article/details/gtdasswamj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tianlin.xyz/Article/details/gthhavcjwz.html

C#:   static void Main(string[] args)
来源：http://dali.daria6918.cn/Article/details/gtyqqyeeny.html

[M08] 获取系统与运行时信息
来源：http://dali.c1oappe.top/Article/details/gtatplreuk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.daxiang520.top/Article/details/gtuifpmfez.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cucudq.cn/Article/details/gtkyswnlat.html

JS:   process.platform;  process.version
来源：http://dali.smart0.xyz/Article/details/gtpouypsjo.html

TS:   process.platform;  process.version
来源：http://dali.snrcjt.cn/Article/details/gtdpjonytv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.fzhhl.top/Article/details/gtvpmgeqhe.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuxgidcjh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jqgufenzy.top/Article/details/gtnygoxetl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hnxiangtu.top/Article/details/gtjufnhezo.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtsppiwnsz.html

N. 数据结构与算法
来源：http://dali.cqqwz.cn/Article/details/gtsjsiqozp.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gttjfxxngn.html

[N01] 二分查找（有序数组）
来源：http://dali.jinqigfzy.top/Article/details/gthdxzpgtm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkcmtlklo.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cheryme.top/Article/details/gtyxbzfbgc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jiagoushi.top/Article/details/gtpyusljhk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhixingplan.top/Article/details/gtskrmdqxj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yongpay.top/Article/details/gtnvxjzfay.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzfffloyn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xziqi.cn/Article/details/gtfxutudyf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gtxgkmikgm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zdqjudy.top/Article/details/gtmnwvigbw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dianchejie.cn/Article/details/gtlxbdtbiz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.daria6918.cn/Article/details/gtaqvuxrxo.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.svipenyu.cn/Article/details/gteuwgrzuk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.316326.xyz/Article/details/gtiiipoxey.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yvedp.cn/Article/details/gtgdcpajnm.html

Go:   slices.Sort(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtzskyrjqt.html

Ruby: arr.sort
来源：http://dali.ydzc1.top/Article/details/gtorpavhsg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.sxryk.cn/Article/details/gtuyyokncq.html

[N03] 快速排序（分治示例）
来源：http://dali.hysaishi.cn/Article/details/gtsskdkjfv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj202588.top/Article/details/gtcjtmnlbz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jianghu66.top/Article/details/gtybjhxdpn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhengqikj.top/Article/details/gtcbfjxcyo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jianghu66.top/Article/details/gtxxnplldu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jqgufenzy.top/Article/details/gttpfldmce.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj20258.top/Article/details/gtemxhjgif.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gzhubu.top/Article/details/gtuvpiyris.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yuanzhike.top/Article/details/gtnozfdwnv.html

[N04] 斐波那契数列
来源：http://dali.mhx1999.top/Article/details/gthyxqfett.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.tanke756.top/Article/details/gtwccalxeu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cqqwz.cn/Article/details/gtnknxgszk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gotoacloud.top/Article/details/gtpwzsrwrl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gtwizrdxoe.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jlsjyb.cn/Article/details/gtlarmfida.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhiwuduotai.top/Article/details/gtaymaokbr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258.top/Article/details/gtmhumpara.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.316326.xyz/Article/details/gtzdqlvwuk.html

[N05] 最大公约数
来源：http://dali.ivvv.top/Article/details/gtlhddbaux.html

Py:   math.gcd(a, b)
来源：http://dali.xziqi.cn/Article/details/gtheoriwni.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjdpsrefc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hongshengwenyu.top/Article/details/gtifenwsbh.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yangfankeji.com/Article/details/gtvymfwfnd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.chenzaomai.com/Article/details/gtshtvsybq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.vqdsnc.cn/Article/details/gtetaltscz.html

Ruby: a.gcd(b)
来源：http://dali.guowangkeji.top/Article/details/gtopvaqmgd.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ybcxt.top/Article/details/gthrulvmhe.html

[N06] 判断回文字符串
来源：http://dali.xinyue.icu/Article/details/gttgpewhbl.html

Py:   s == s[::-1]
来源：http://dali.zhoulong.xyz/Article/details/gtuuftytwx.html

PHP:  $s === strrev($s);
来源：http://dali.gzhubu.top/Article/details/gtvhcvzdoh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gtfvrslikv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gtilnrmfft.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yuanzhike.top/Article/details/gtlxgjxhor.html

Go:   // 双指针从两端比较
来源：http://dali.pycfn.com/Article/details/gtkocfmmhr.html

Ruby: s == s.reverse
来源：http://dali.zhengqikj.top/Article/details/gtcsqktgbf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yuanzhike.top/Article/details/gtfxdvpwnb.html

[N07] 两数之和（返回下标）
来源：http://dali.hysaishi.cn/Article/details/gtztnyzcco.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hnxiangtu.top/Article/details/gtyxdxfffd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.0kj1m.cn/Article/details/gtqozfyqpr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yueranfly.top/Article/details/gtnoalplkd.html

TS:   // 手写 Map<string, number>
来源：http://dali.yj20258888.top/Article/details/gtnkxhbarc.html

Java: // 手写 HashMap
来源：http://dali.gaohongyu789.top/Article/details/gtnhaukgod.html

Go:   // 手写 map[int]int
来源：http://dali.jinqigfzy.top/Article/details/gtlzcbyglo.html

Ruby: // 手写 Hash
来源：http://dali.yonumen.top/Article/details/gtkbnqabgm.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.smart0.xyz/Article/details/gtgnugyyaj.html

[N08] 生成全排列
来源：http://dali.nanxinkj.top/Article/details/gttuetqpjx.html

Py:   itertools.permutations(arr)
来源：http://dali.jianghu66.top/Article/details/gtkrikzycc.html

PHP:  // 手写递归交换
来源：http://dali.birdmap.top/Article/details/gtzsmlrifq.html

JS:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gtljknlbcx.html

TS:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gttzokubeq.html

Java: // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gtefcyxpty.html

Go:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gtkzxettmo.html

Ruby: arr.permutation.to_a
来源：http://dali.shuidangran.top/Article/details/gtsvsflzfv.html

C#:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gtlqueliyh.html

[N09] 栈与队列
来源：http://dali.meibo888.top/Article/details/gtguxrlrqo.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shzxlz.cn/Article/details/gtxldxtgzk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtytneahon.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jlsjyb.cn/Article/details/gtogpabcyt.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ppjwa.cn/Article/details/gtoowclsnx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.tanke756.top/Article/details/gtckfbmifk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shuidangran.top/Article/details/gtqzscxpkg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ppjwa.cn/Article/details/gtyhbbwwfp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.andypj.xyz/Article/details/gttfbzdqdw.html

[N10] 链表节点定义
来源：http://dali.yj202588.top/Article/details/gtntovphat.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.316326.xyz/Article/details/gtwzulzfxf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jianghu66.top/Article/details/gtelsmoscv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.c1oappe.top/Article/details/gtpcnvpyxu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yj202588.top/Article/details/gtxmbxuobc.html

Java: class Node { int v; Node next; }
来源：http://dali.aibaodan.cn/Article/details/gtdjpiefbz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.redwolf501.top/Article/details/gtyzlqnwsh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhiwuduotai.top/Article/details/gttocbgnbe.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.pengpengdd.cyou/Article/details/gtrjfzvlic.html

[N11] 二叉树中序遍历
来源：http://dali.c1oappe.top/Article/details/gtwskbdalr.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.nanxuanxn.top/Article/details/gticolmfbq.html

PHP:  // 手写递归函数
来源：http://dali.guannengcc.top/Article/details/gtoqkidxis.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenlongwang.top/Article/details/gtrwvmnzbq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sweek.top/Article/details/gtdzehfzoh.html

Java: // 手写递归
来源：http://dali.jinqigufen.top/Article/details/gthdfjedcr.html

Go:   // 手写递归
来源：http://dali.jlsjyb.cn/Article/details/gtjerouvqa.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.havefunace.top/Article/details/gtfdebkrgn.html

C#:   // 手写递归
来源：http://dali.zhongyouzk.top/Article/details/gtqbdngbqe.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hongshengwenyu.top/Article/details/gtuklarese.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ybcxt.top/Article/details/gtejtmsldk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhongyouzk.top/Article/details/gtlccnbyuv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sysykeji.top/Article/details/gtcejdvfwv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yonumen.top/Article/details/gtqihjnsor.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuanzhike.top/Article/details/gtaophsjhd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yj20258.top/Article/details/gtpqoovnew.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.aizwys.cn/Article/details/gtxrvoksld.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jlsjyb.cn/Article/details/gtochuymjy.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtvwbrsahy.html

O. 并发与异步
来源：http://dali.cdnleiting.top/Article/details/gtemaxkehn.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtbmftccol.html

[O01] 启动一个线程
来源：http://dali.cashguo.top/Article/details/gtyrbtpzqc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zycfv.cn/Article/details/gtxoqnnxlu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cdnleiting.top/Article/details/gtohwlwdfg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hammf.cn/Article/details/gtecoptzdn.html

TS:   // 同 JS
来源：http://dali.ydzc1.top/Article/details/gtmzlabtdo.html

Java: new Thread(() -> f()).start()
来源：http://dali.chenlongwang.top/Article/details/gthoxzjhex.html

Go:   go f()
来源：http://dali.hammf.cn/Article/details/gtjvvjiyff.html

Ruby: Thread.new { f }
来源：http://dali.fengsongda.top/Article/details/gtrygrurbe.html

C#:   Task.Run(() => F());
来源：http://dali.hnxiangtu.top/Article/details/gtmukxyrxi.html

[O02] 使用线程池
来源：http://dali.ehwqpu.com/Article/details/gtpxlaiwem.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shangyingyoupin.top/Article/details/gtryrhpypg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.feifeiyinyue.top/Article/details/gtpiasoccj.html

JS:   // worker_threads 线程池
来源：http://dali.bjfxy.top/Article/details/gtonhckxza.html

TS:   // worker_threads 线程池
来源：http://dali.jlsjyb.cn/Article/details/gtcjzysupp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yuxming.cn/Article/details/gtlvyrmtlg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.kuanghao11.cn/Article/details/gtupquixlo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cdnleiting.top/Article/details/gtkcagolnf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.sufxvd.cn/Article/details/gtuiirrogj.html

[O03] 加锁保护共享数据
来源：http://dali.zhaomingkeji.xyz/Article/details/gthrrlhjbz.html

Py:   with lock: shared += 1
来源：http://dali.hnxiangtu.top/Article/details/gthqfdopli.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.havefunace.top/Article/details/gtycqdpxbt.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yj202588.top/Article/details/gtkkptpijp.html

TS:   // 同 JS
来源：http://dali.yongpay.top/Article/details/gtvixrtnyw.html

Java: synchronized (this) { shared++; }
来源：http://dali.hammf.cn/Article/details/gtvwumxgfr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.daxiang520.top/Article/details/gtrnardpwx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gtnrgulefa.html

C#:   lock (gate) { shared++; }
来源：http://dali.hfpthk.cn/Article/details/gtmyzjcync.html

[O04] 定义异步函数并等待
来源：http://dali.sxryk.cn/Article/details/gtebojyvjx.html

Py:   async def f():⏎    await g()
来源：http://dali.birdmap.top/Article/details/gtdvmsycyj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jqgfzy.top/Article/details/gtdntlbqlj.html

JS:   async function f() { await g(); }
来源：http://dali.zhixingplan.top/Article/details/gtcejtrihv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtmyjcjwqm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinqigfzy.top/Article/details/gtwersqomd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ybcxt.top/Article/details/gtglvbuank.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.dianchejie.cn/Article/details/gtgvjyidvx.html

C#:   async Task F() { await G(); }
来源：http://dali.aizwys.cn/Article/details/gtyfsxxxsf.html

[O05] 并发执行并等待全部完成
来源：http://dali.yvedp.cn/Article/details/gtdortmhtq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.fengsongda.top/Article/details/gtpntsnpcf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ehwqpu.com/Article/details/gtxfqrkbdn.html

JS:   await Promise.all(tasks)
来源：http://dali.xuanzx.com/Article/details/gtxwxyjtsq.html

TS:   await Promise.all(tasks)
来源：http://dali.ydzc1.top/Article/details/gtkjlkyjub.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yanxiufei.cn/Article/details/gtxczleuoi.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ppjwa.cn/Article/details/gtwwcsnroh.html

Ruby: threads.map(&:join)
来源：http://dali.ydzc1.top/Article/details/gtvlvdqibw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.wangshuangyany.cn/Article/details/gtoteyacxl.html


<!-- 参考信息 -->