代发 wailian999

Py:   requests.post(url, json={"a": 1})
来源：http://dali.tanke756.top/Article/details/gtrrhjlzsx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yj20258.top/Article/details/gtpndztqex.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hywenlv.cn/Article/details/gtrryodmph.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuanzx.com/Article/details/gtprjckmfl.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yangfankeji.com/Article/details/gthmaincnc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.smart0.xyz/Article/details/gtqxmsjgrl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.daria6918.cn/Article/details/gtrfccvyva.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cashguo.top/Article/details/gtgwbfnbgd.html

[L03] 设置自定义请求头
来源：http://dali.hongshengwenyu.top/Article/details/gtujosplgt.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zdqjudy.top/Article/details/gtqilsnuvk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.wangdashe.top/Article/details/gtqzblawjm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yangfankeji.com/Article/details/gtrwqmzkjs.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.havefunace.top/Article/details/gtsqeerqvv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.smart0.xyz/Article/details/gtjhshyhux.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinqigfzy.top/Article/details/gtcohsmjxw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xinyue.icu/Article/details/gtbgweoxkr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.feifeiyinyue.top/Article/details/gtesoshddk.html

[L04] 设置超时
来源：http://dali.iojbl.cn/Article/details/gtshtekrfv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hysaishi.cn/Article/details/gtejqhvowv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shanyushiyangtech.top/Article/details/gtyaerowji.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sysykeji.top/Article/details/gtrfsawxpi.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gaohongyu789.top/Article/details/gtpaixkqhx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xziqi.cn/Article/details/gtghkckapu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hnxiangtu.top/Article/details/gtpdcbtzbn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nwbrower.top/Article/details/gtavbvderw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gzhubu.top/Article/details/gtxvrkupsv.html

[L05] 上传文件（multipart）
来源：http://dali.jyoumei.cn/Article/details/gtbxgmypoe.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yanxiufei.cn/Article/details/gtungfelpy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhoulong.xyz/Article/details/gtpludxawh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.bjfxy.top/Article/details/gtnnxulmky.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.quarkkingdee.top/Article/details/gtdplcmrrt.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sufxvd.cn/Article/details/gtewswfwgw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yj20258.top/Article/details/gtclecnsmo.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shanyushiyangkeji.top/Article/details/gthuhaqtmc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.316326.xyz/Article/details/gthdemalds.html

[L06] 解析响应为 JSON
来源：http://dali.xuetiantiany.cn/Article/details/gthwsacwme.html

Py:   resp.json()
来源：http://dali.tian-w.cn/Article/details/gtmfodedgl.html

PHP:  json_decode($body, true);
来源：http://dali.gzhubu.top/Article/details/gtstpitllo.html

JS:   await resp.json()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpdyvshxg.html

TS:   await resp.json()
来源：http://dali.pengpengdd.cyou/Article/details/gtchunhekg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlqqfzkka.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.fzhhl.top/Article/details/gtirjhdlkt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrggyziig.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.feifeiyinyue.top/Article/details/gtsriokonj.html

[L07] 处理 HTTP 状态码
来源：http://dali.316326.xyz/Article/details/gtolzrdfeu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.snrcjt.cn/Article/details/gtlthjhxxa.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.iojbl.cn/Article/details/gtukzlrzuw.html

JS:   resp.ok;  resp.status
来源：http://dali.fengsongda.top/Article/details/gtnmtrqnzc.html

TS:   resp.ok;  resp.status
来源：http://dali.jinghuilouyu.cn/Article/details/gtpufghcpa.html

Java: resp.statusCode()
来源：http://dali.jyoumei.cn/Article/details/gtxvcyxsje.html

Go:   resp.StatusCode
来源：http://dali.guannengcc.top/Article/details/gtufyrbyhz.html

Ruby: resp.code.to_i
来源：http://dali.jinghuilouyu.cn/Article/details/gtywliqyuj.html

C#:   (int)resp.StatusCode
来源：http://dali.kuanghao11.cn/Article/details/gtjxdhpjkp.html

[L08] 并发请求多个地址
来源：http://dali.zhiwuduotai.top/Article/details/gtnaswhcmq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.dianchejie.cn/Article/details/gtfbuphqtb.html

PHP:  curl_multi_init() 系列
来源：http://dali.sxryk.cn/Article/details/gtxrplpgoc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gtgmsgvlrv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yonumen.top/Article/details/gtyhlplbhe.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gotoacloud.top/Article/details/gtpsppsevh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.tanke756.top/Article/details/gttkdigrao.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhoulong.xyz/Article/details/gtkhcphrwo.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xylfe.cn/Article/details/gtebyamjmj.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtcxhcveqm.html

M. 命令行 / 进程 / 环境
来源：http://dali.jqgufenzy.top/Article/details/gtdprqlwea.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtciddbmnf.html

[M01] 读取命令行参数
来源：http://dali.hnxiangtu.top/Article/details/gtliqjyzxi.html

Py:   sys.argv[1:]
来源：http://dali.ivvv.top/Article/details/gtjxtngrft.html

PHP:  $argv;  $argc;
来源：http://dali.zhoulong.xyz/Article/details/gtgzwtfiql.html

JS:   process.argv.slice(2)
来源：http://dali.yongpay.top/Article/details/gtswuzxgqn.html

TS:   process.argv.slice(2)
来源：http://dali.sysykeji.top/Article/details/gtjwptbwhz.html

Java: args 数组（main 方法参数）
来源：http://dali.havefunace.top/Article/details/gtmdqntgam.html

Go:   os.Args[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbpjguxvh.html

Ruby: ARGV
来源：http://dali.hfpthk.cn/Article/details/gtvuamjgwa.html

C#:   args 数组（Main 方法参数）
来源：http://dali.iojbl.cn/Article/details/gteyvpattk.html

[M02] 读取环境变量
来源：http://dali.chenzaomai.com/Article/details/gtoeyuasbi.html

Py:   os.environ.get("HOME")
来源：http://dali.zhengqikj.top/Article/details/gtbxtjtuob.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ivvv.top/Article/details/gtnjuzjazo.html

JS:   process.env.HOME
来源：http://dali.jyoumei.cn/Article/details/gtjzfrcsgj.html

TS:   process.env.HOME
来源：http://dali.xinyue.icu/Article/details/gtjsvqtxqd.html

Java: System.getenv("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrsnfjtcs.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gtsvxocgwq.html

Ruby: ENV["HOME"]
来源：http://dali.yuanzhike.top/Article/details/gtxgnaqhfe.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.haohaochexian.top/Article/details/gtrahdicob.html

[M03] 执行外部命令
来源：http://dali.fengsongda.top/Article/details/gtnxxmobip.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.nanxinkj.top/Article/details/gtbvbvfubv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.birdmap.top/Article/details/gtdwjiyyus.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yangfankeji.com/Article/details/gtjccgqcsn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgufenzy.top/Article/details/gtlizzqaff.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jqgufenzy.top/Article/details/gtajaplhwo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.daxiang520.top/Article/details/gtgsrdacer.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ppjwa.cn/Article/details/gtpkacktrm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yuxming.cn/Article/details/gtlhipczmf.html

[M04] 获取当前工作目录
来源：http://dali.yj202588.top/Article/details/gtzalrdewe.html

Py:   os.getcwd()
来源：http://dali.andypj.xyz/Article/details/gtckmxpkzv.html

PHP:  getcwd();
来源：http://dali.yvedp.cn/Article/details/gtvoorjtaw.html

JS:   process.cwd()
来源：http://dali.hywenlv.cn/Article/details/gtruqtrxzp.html

TS:   process.cwd()
来源：http://dali.smart0.xyz/Article/details/gtpxnjmccm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenzaomai.com/Article/details/gtgptnftvn.html

Go:   os.Getwd()
来源：http://dali.andypj.xyz/Article/details/gtgvqvmqus.html

Ruby: Dir.pwd
来源：http://dali.gaohongyu789.top/Article/details/gtttrkjzcv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gtonfbwupt.html

[M05] 设置退出码
来源：http://dali.yj20258888.top/Article/details/gtqntqmqwx.html

Py:   sys.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gtcrdvtljs.html

PHP:  exit(1);
来源：http://dali.fengsongda.top/Article/details/gtxhmzhnnk.html

JS:   process.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gttxrmcipi.html

TS:   process.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtftnssuuk.html

Java: System.exit(1)
来源：http://dali.guannengcc.top/Article/details/gtqzztbcrc.html

Go:   os.Exit(1)
来源：http://dali.tian-w.cn/Article/details/gtfhmuxdcr.html

Ruby: exit 1
来源：http://dali.yuxming.cn/Article/details/gtdvffycdj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.tanke756.top/Article/details/gtazmqttlh.html

[M06] 向标准错误输出
来源：http://dali.jiagoushi.top/Article/details/gtuytmiikf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yueranfly.top/Article/details/gtavtumopv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cucudq.cn/Article/details/gtftxqseus.html

JS:   console.error("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtodkdjdhk.html

TS:   console.error("err")
来源：http://dali.shzxlz.cn/Article/details/gtbwyvunwb.html

Java: System.err.println("err")
来源：http://dali.guowangkeji.top/Article/details/gtxzhesjxa.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.chenlongwang.top/Article/details/gtxqvcfkog.html

Ruby: warn "err"
来源：http://dali.cqqwz.cn/Article/details/gtsbajjqso.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jiagoushi.top/Article/details/gtlnjsdflb.html

[M07] 判断是否为主入口
来源：http://dali.shanyushiyangtech.top/Article/details/gtowicddlu.html

Py:   if __name__ == "__main__":
来源：http://dali.pengpengdd.cyou/Article/details/gtjrdknpnb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cucudq.cn/Article/details/gtgxslrqkh.html

JS:   require.main === module
来源：http://dali.yvedp.cn/Article/details/gtljfuprwb.html

TS:   require.main === module
来源：http://dali.tanke756.top/Article/details/gtmqzcomgd.html

Java: public static void main(String[] args)
来源：http://dali.andypj.xyz/Article/details/gtquemjtvb.html

Go:   func main()
来源：http://dali.shangyingyoupin.top/Article/details/gttaapzycj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.smart0.xyz/Article/details/gtezbwnozk.html

C#:   static void Main(string[] args)
来源：http://dali.cqqwz.cn/Article/details/gtecvcpdiw.html

[M08] 获取系统与运行时信息
来源：http://dali.sysykeji.top/Article/details/gtebzjdypp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.iojbl.cn/Article/details/gtlwgvztsk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cashguo.top/Article/details/gtvoobiblv.html

JS:   process.platform;  process.version
来源：http://dali.yangfankeji.com/Article/details/gtwxzwbtus.html

TS:   process.platform;  process.version
来源：http://dali.yj20258.top/Article/details/gtmszikpuc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hywenlv.cn/Article/details/gtaydmprxn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hnqzz.top/Article/details/gtkszxflcq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.vqdsnc.cn/Article/details/gtapbxcqft.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shanyushiyangtech.top/Article/details/gtjioohoma.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtrwaxwbeh.html

N. 数据结构与算法
来源：http://dali.yj202588.top/Article/details/gtryezqzqw.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtjwmarcib.html

[N01] 二分查找（有序数组）
来源：http://dali.chenjidiqi.icu/Article/details/gteejesjuv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtkdmujdlq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrylmkvwp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gzhubu.top/Article/details/gtcbrxfiur.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tian-w.cn/Article/details/gtshfhhhxw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtxevvwrsk.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtmcsrslsv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinghuilouyu.cn/Article/details/gthflgwomi.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gtbnwybdgp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yangfankeji.com/Article/details/gtdnyrqkrj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hfpthk.cn/Article/details/gtebvcivam.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cashguo.top/Article/details/gtpvtjbjrq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gotoacloud.top/Article/details/gtjmpjstcp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvosoubdk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.9152youxi.cn/Article/details/gtpsellujb.html

Go:   slices.Sort(arr)
来源：http://dali.xziqi.cn/Article/details/gtvdcenbqf.html

Ruby: arr.sort
来源：http://dali.jinqigufen.top/Article/details/gttrlbqqoy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.haohaochexian.top/Article/details/gtxglognvs.html

[N03] 快速排序（分治示例）
来源：http://dali.guannengcc.top/Article/details/gtajdiajmn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ybcxt.top/Article/details/gtlsjnhxhn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yonumen.top/Article/details/gtsrerqgim.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hnxiangtu.top/Article/details/gtdatplnus.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shangyingyoupin.top/Article/details/gtsfbsjifv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gaohongyu789.top/Article/details/gthwauwzps.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jianghu66.top/Article/details/gtroxuwvgq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yonumen.top/Article/details/gtiicdwebo.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.mhx1999.top/Article/details/gtkabmrsjq.html

[N04] 斐波那契数列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtptakeyir.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjwzdgynp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yuxming.cn/Article/details/gtzuxnzqpy.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shzxlz.cn/Article/details/gtyyryfszl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenlongwang.top/Article/details/gtlazschql.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.pengpengdd.cyou/Article/details/gtozqzdfye.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hnxiangtu.top/Article/details/gtzpotrmst.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gtjbxsaxsx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gtclinzvzb.html

[N05] 最大公约数
来源：http://dali.wangshuangyany.cn/Article/details/gtdflwkktj.html

Py:   math.gcd(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gtzdtsbnpd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.iojbl.cn/Article/details/gtigtsqchv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhixingplan.top/Article/details/gtbpdissfw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zdqjudy.top/Article/details/gtywiavrmp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.wangshuangyany.cn/Article/details/gtyyksxeiy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.iojbl.cn/Article/details/gtqeryvjeu.html

Ruby: a.gcd(b)
来源：http://dali.chenlongwang.top/Article/details/gtrxfpwjbr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.kuanghao11.cn/Article/details/gttyhkgycb.html

[N06] 判断回文字符串
来源：http://dali.tian-w.cn/Article/details/gtevbtyxxj.html

Py:   s == s[::-1]
来源：http://dali.yuxming.cn/Article/details/gtwgxtbnsa.html

PHP:  $s === strrev($s);
来源：http://dali.hnqzz.top/Article/details/gtfsrrusfr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gtyifxrcpo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gtjgskaojm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shzxlz.cn/Article/details/gtpdcbyjca.html

Go:   // 双指针从两端比较
来源：http://dali.aibaodan.cn/Article/details/gtvpqxuklw.html

Ruby: s == s.reverse
来源：http://dali.zhoulong.xyz/Article/details/gtjtlohphu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sxryk.cn/Article/details/gtuvrlgqrm.html

[N07] 两数之和（返回下标）
来源：http://dali.tianlin.xyz/Article/details/gtasbgilws.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.aibaodan.cn/Article/details/gtznlhuvus.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shzxlz.cn/Article/details/gtzgbpguqw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.fzhhl.top/Article/details/gtwtenurue.html

TS:   // 手写 Map<string, number>
来源：http://dali.birdmap.top/Article/details/gtuqwvzkuy.html

Java: // 手写 HashMap
来源：http://dali.hnxiangtu.top/Article/details/gthobranmv.html

Go:   // 手写 map[int]int
来源：http://dali.sufxvd.cn/Article/details/gtohccutip.html

Ruby: // 手写 Hash
来源：http://dali.nanxuanxn.top/Article/details/gttgyhkqdm.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ivvv.top/Article/details/gterrwwdga.html

[N08] 生成全排列
来源：http://dali.shzxlz.cn/Article/details/gthfxpspds.html

Py:   itertools.permutations(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtgsjyubhl.html

PHP:  // 手写递归交换
来源：http://dali.yj20258.top/Article/details/gtoteniewm.html

JS:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gtvdlysgnu.html

TS:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gtgtnfucgs.html

Java: // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gtnsmlitvt.html

Go:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwsayztud.html

Ruby: arr.permutation.to_a
来源：http://dali.shzxlz.cn/Article/details/gtgzycmths.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gthbxamecq.html

[N09] 栈与队列
来源：http://dali.cashguo.top/Article/details/gtlbzbvmiu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.tianlin.xyz/Article/details/gthkxeduun.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.snrcjt.cn/Article/details/gtcwijnocp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jyoumei.cn/Article/details/gtlkcncxby.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinqigufen.top/Article/details/gtrwgpyoul.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xuanzx.com/Article/details/gtmmyudnbm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xziqi.cn/Article/details/gtbocxyyhu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yj20258888.top/Article/details/gtitgiatvm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhixingplan.top/Article/details/gtcwbwwsct.html

[N10] 链表节点定义
来源：http://dali.cashguo.top/Article/details/gthpkliord.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jiagoushi.top/Article/details/gttesworeu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ybcxt.top/Article/details/gtxrvofwqp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrvznvspy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hywenlv.cn/Article/details/gtccdczrak.html

Java: class Node { int v; Node next; }
来源：http://dali.gaohongyu789.top/Article/details/gtchrfsayp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.tian-w.cn/Article/details/gtgabewowa.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shanyushiyangtech.top/Article/details/gtixzifjei.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.chenlongwang.top/Article/details/gtfbqbnxow.html

[N11] 二叉树中序遍历
来源：http://dali.yuanzhike.top/Article/details/gtjjcqmimc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhiwuduotai.top/Article/details/gtteooujwn.html

PHP:  // 手写递归函数
来源：http://dali.ppjwa.cn/Article/details/gtybilreuj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jyoumei.cn/Article/details/gtfukfvcuj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gogol.net.cn/Article/details/gtwrznckms.html

Java: // 手写递归
来源：http://dali.zycfv.cn/Article/details/gtamxcpqrh.html

Go:   // 手写递归
来源：http://dali.snrcjt.cn/Article/details/gtwckpigcv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yj202588.top/Article/details/gtijkdqanw.html

C#:   // 手写递归
来源：http://dali.zycfv.cn/Article/details/gtnqewxuiz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zycfv.cn/Article/details/gtrvsmgyoj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ivvv.top/Article/details/gtalsaoblv.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hywenlv.cn/Article/details/gtcexjqket.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yangfankeji.com/Article/details/gtwtyuopso.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.birdmap.top/Article/details/gtdmkrohah.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenzaomai.com/Article/details/gtbxyhuiri.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shuidangran.top/Article/details/gtuoceekxv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hysaishi.cn/Article/details/gtyfnbabpy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigfzy.top/Article/details/gtkxtvzeey.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtqiewuggz.html

O. 并发与异步
来源：http://dali.sufxvd.cn/Article/details/gtjcgipmpe.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtiwfgltsl.html

[O01] 启动一个线程
来源：http://dali.meibo888.top/Article/details/gtzzgjgoih.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gzhubu.top/Article/details/gtgrxbbqwi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtwmduarpo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cashguo.top/Article/details/gtsgnpbslh.html

TS:   // 同 JS
来源：http://dali.nanxuanxn.top/Article/details/gtlkuyqbmc.html

Java: new Thread(() -> f()).start()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcckwfcjw.html

Go:   go f()
来源：http://dali.dashuyun.cn/Article/details/gtljwsrlwn.html

Ruby: Thread.new { f }
来源：http://dali.ybcxt.top/Article/details/gtsbrduvuh.html

C#:   Task.Run(() => F());
来源：http://dali.dashuyun.cn/Article/details/gtcbpjbsyx.html

[O02] 使用线程池
来源：http://dali.zhiwuduotai.top/Article/details/gtoihusefy.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xylfe.cn/Article/details/gtjrlkkqtc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sxryk.cn/Article/details/gtznomrlnr.html

JS:   // worker_threads 线程池
来源：http://dali.cheryme.top/Article/details/gtizopyoxg.html

TS:   // worker_threads 线程池
来源：http://dali.zdqjudy.top/Article/details/gtaqpdnjav.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlkzercaz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zdqjudy.top/Article/details/gteyoqciqf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhixingplan.top/Article/details/gtugbgzidi.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zdqjudy.top/Article/details/gtoenuddgv.html

[O03] 加锁保护共享数据
来源：http://dali.tanke756.top/Article/details/gttrwvswjg.html

Py:   with lock: shared += 1
来源：http://dali.mhx1999.top/Article/details/gtilcbehya.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.fzhhl.top/Article/details/gtgwoiacgm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shangyingyoupin.top/Article/details/gtchclzmld.html

TS:   // 同 JS
来源：http://dali.smart0.xyz/Article/details/gtrbmmmtdl.html

Java: synchronized (this) { shared++; }
来源：http://dali.yangfankeji.com/Article/details/gtseuurdei.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hfpthk.cn/Article/details/gtthpkwsxz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.smart0.xyz/Article/details/gtmmmvoenr.html

C#:   lock (gate) { shared++; }
来源：http://dali.xylfe.cn/Article/details/gtzddwqsox.html

[O04] 定义异步函数并等待
来源：http://dali.yongpay.top/Article/details/gtkujioutb.html

Py:   async def f():⏎    await g()
来源：http://dali.zycfv.cn/Article/details/gtmctlnxbj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.daxiang520.top/Article/details/gtppycnzsr.html

JS:   async function f() { await g(); }
来源：http://dali.yonumen.top/Article/details/gtpcwbulve.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.quarkkingdee.top/Article/details/gtqfomycdl.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shanyushiyangtech.top/Article/details/gtrmiivhye.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinqigufen.top/Article/details/gtbjscfjmt.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jqgufenzy.top/Article/details/gtfuhrdbmp.html

C#:   async Task F() { await G(); }
来源：http://dali.daxiang520.top/Article/details/gtfujvgqbt.html

[O05] 并发执行并等待全部完成
来源：http://dali.chenzaomai.com/Article/details/gtrocecfps.html

Py:   asyncio.gather(*tasks)
来源：http://dali.chenjidiqi.icu/Article/details/gtvfurbcze.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cheryme.top/Article/details/gtawuzivnm.html

JS:   await Promise.all(tasks)
来源：http://dali.guowangkeji.top/Article/details/gtbbasxleg.html

TS:   await Promise.all(tasks)
来源：http://dali.dashuyun.cn/Article/details/gtjujmiduf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zdqjudy.top/Article/details/gtsuoeqdls.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.iojbl.cn/Article/details/gtdztcvbcx.html

Ruby: threads.map(&:join)
来源：http://dali.wangdashe.top/Article/details/gtkmtfkpdq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shzxlz.cn/Article/details/gtsskjvrnm.html

[O06] 使用进程池
来源：http://dali.hnqzz.top/Article/details/gtbtnbngfr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hywenlv.cn/Article/details/gtdpmutthz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gttmxngdkn.html

JS:   // child_process / cluster 模块
来源：http://dali.quarkkingdee.top/Article/details/gtraapdcbq.html


<!-- 参考信息 -->