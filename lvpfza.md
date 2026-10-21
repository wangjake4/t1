代发 wailian999

Go:   encoding/gob
来源：http://dali.hfpthk.cn/Article/details/gtphmbhnni.html

Ruby: Marshal.dump(obj)
来源：http://dali.hywenlv.cn/Article/details/gtxjqnfdox.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gogol.net.cn/Article/details/gtlcpjhhgc.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtvmrhjffm.html

L. 网络请求
来源：http://dali.sysykeji.top/Article/details/gtwzpnjnok.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtiqffmoxr.html

[L01] 发送 GET 请求
来源：http://dali.feifeiyinyue.top/Article/details/gtndedjogd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cheryme.top/Article/details/gtsfxdtuvb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.tian-w.cn/Article/details/gtbbkurxmh.html

JS:   await fetch(url)
来源：http://dali.xuanzx.com/Article/details/gtlihdnvuk.html

TS:   await fetch(url)
来源：http://dali.fengsongda.top/Article/details/gtsxdhxgnr.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ivvv.top/Article/details/gtmzipvtjc.html

Go:   resp, err := http.Get(url)
来源：http://dali.mhx1999.top/Article/details/gtuodmlenq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shuidangran.top/Article/details/gtayqpyxms.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.haohaochexian.top/Article/details/gtglozhuye.html

[L02] 发送 POST JSON
来源：http://dali.hysaishi.cn/Article/details/gtlnigbatg.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yangfankeji.com/Article/details/gttisjkrxt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ppjwa.cn/Article/details/gtljnsthna.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gttumegjhu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sufxvd.cn/Article/details/gtxdjmiwrd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yanxiufei.cn/Article/details/gtksfduhyi.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ppjwa.cn/Article/details/gtdwxaejao.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cqqwz.cn/Article/details/gtvggusggt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqgdimxps.html

[L03] 设置自定义请求头
来源：http://dali.yangfankeji.com/Article/details/gtjxgdhjjx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtytkulbbk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sysykeji.top/Article/details/gtaefczxbm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sweek.top/Article/details/gtwerbabrk.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sufxvd.cn/Article/details/gtmfpshqdq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.iojbl.cn/Article/details/gtbbnzbkya.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zycfv.cn/Article/details/gtogpmxxyr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj202588.top/Article/details/gtzcptqcpa.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.chenlongwang.top/Article/details/gtxpgbmkku.html

[L04] 设置超时
来源：http://dali.yj202588.top/Article/details/gtfwpxujdf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hammf.cn/Article/details/gtcyujobic.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxhlsijdn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ivvv.top/Article/details/gtsiuuabbl.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fengsongda.top/Article/details/gtcuwpfonr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xylfe.cn/Article/details/gtcsphvmcc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gtsqcmtseb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhoulong.xyz/Article/details/gtymuifudg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.9152youxi.cn/Article/details/gtkkwudnun.html

[L05] 上传文件（multipart）
来源：http://dali.sxryk.cn/Article/details/gtvtesexfe.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jyoumei.cn/Article/details/gtcyriizca.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.svipenyu.cn/Article/details/gtqblbyole.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhengqikj.top/Article/details/gtltywofyn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhoulong.xyz/Article/details/gtbfdhpxej.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.fengsongda.top/Article/details/gtosutryjn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.tanke756.top/Article/details/gtbphjuird.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.0kj1m.cn/Article/details/gtaocbcsbt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.birdmap.top/Article/details/gtodwfqrbq.html

[L06] 解析响应为 JSON
来源：http://dali.cdnleiting.top/Article/details/gtfivywqeq.html

Py:   resp.json()
来源：http://dali.fzhhl.top/Article/details/gthkjkazkp.html

PHP:  json_decode($body, true);
来源：http://dali.xziqi.cn/Article/details/gtbgeeqbih.html

JS:   await resp.json()
来源：http://dali.yuanzhike.top/Article/details/gtotatfcdd.html

TS:   await resp.json()
来源：http://dali.xuetiantiany.cn/Article/details/gtqzazcshr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj20258.top/Article/details/gtblvelnff.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.daxiang520.top/Article/details/gtxkslvavx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jiagoushi.top/Article/details/gtmaqlfeuj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cqqwz.cn/Article/details/gtgwviimwx.html

[L07] 处理 HTTP 状态码
来源：http://dali.shuidangran.top/Article/details/gtulhpwxsq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zdqjudy.top/Article/details/gtriwhlyfz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.svipenyu.cn/Article/details/gtgerbnwim.html

JS:   resp.ok;  resp.status
来源：http://dali.jyoumei.cn/Article/details/gtnhhamvly.html

TS:   resp.ok;  resp.status
来源：http://dali.gaohongyu789.top/Article/details/gtsnxkgons.html

Java: resp.statusCode()
来源：http://dali.hongshengwenyu.top/Article/details/gtthiqhgfi.html

Go:   resp.StatusCode
来源：http://dali.bjfxy.top/Article/details/gtknyuxifa.html

Ruby: resp.code.to_i
来源：http://dali.zhixingplan.top/Article/details/gtyhxjkmvn.html

C#:   (int)resp.StatusCode
来源：http://dali.bjfxy.top/Article/details/gtceaoqpac.html

[L08] 并发请求多个地址
来源：http://dali.0kj1m.cn/Article/details/gtzmgdbxyp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hnxiangtu.top/Article/details/gtdxkhypng.html

PHP:  curl_multi_init() 系列
来源：http://dali.smart0.xyz/Article/details/gtybcqckid.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigufen.top/Article/details/gtakyrbsax.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gtjyfgvwtf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sxryk.cn/Article/details/gtaoyrszgl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.wangshuangyany.cn/Article/details/gttckdvpxp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yueranfly.top/Article/details/gtthcizjdj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jlsjyb.cn/Article/details/gtxrsdzsxh.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtrcovktvs.html

M. 命令行 / 进程 / 环境
来源：http://dali.jqgufenzy.top/Article/details/gthwjjdwvg.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtjaqafzba.html

[M01] 读取命令行参数
来源：http://dali.tianlin.xyz/Article/details/gtbrtehxao.html

Py:   sys.argv[1:]
来源：http://dali.xylfe.cn/Article/details/gtiuiuhhcg.html

PHP:  $argv;  $argc;
来源：http://dali.yuanzhike.top/Article/details/gtsznqnign.html

JS:   process.argv.slice(2)
来源：http://dali.jlsjyb.cn/Article/details/gtuxikxgzp.html

TS:   process.argv.slice(2)
来源：http://dali.chenjidiqi.icu/Article/details/gtjnjggteg.html

Java: args 数组（main 方法参数）
来源：http://dali.mhx1999.top/Article/details/gtveuomnyz.html

Go:   os.Args[1:]
来源：http://dali.xziqi.cn/Article/details/gtmjdamskf.html

Ruby: ARGV
来源：http://dali.zhaomingkeji.xyz/Article/details/gttfknmtad.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yonumen.top/Article/details/gtpjbxagye.html

[M02] 读取环境变量
来源：http://dali.jqgufenzy.top/Article/details/gtcggdyevc.html

Py:   os.environ.get("HOME")
来源：http://dali.bjfxy.top/Article/details/gtisxfvfre.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cheryme.top/Article/details/gthkrdiceg.html

JS:   process.env.HOME
来源：http://dali.xuanzx.com/Article/details/gtzicwzifc.html

TS:   process.env.HOME
来源：http://dali.vqdsnc.cn/Article/details/gtkmhdwzms.html

Java: System.getenv("HOME")
来源：http://dali.aibaodan.cn/Article/details/gtiyzhbodk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfyhelksl.html

Ruby: ENV["HOME"]
来源：http://dali.hnxiangtu.top/Article/details/gtjhcwrnlw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gtvbtdxhgq.html

[M03] 执行外部命令
来源：http://dali.hnxiangtu.top/Article/details/gtznbxcpxw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hnxiangtu.top/Article/details/gtqhglcjzl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yanxiufei.cn/Article/details/gtjbqwkgct.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xylfe.cn/Article/details/gthqliwydl.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yvedp.cn/Article/details/gtfkkjmeww.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hfpthk.cn/Article/details/gtxnkqkbeq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.birdmap.top/Article/details/gtuvidjlin.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxxqfmmrm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.dashuyun.cn/Article/details/gtwaftcdho.html

[M04] 获取当前工作目录
来源：http://dali.daria6918.cn/Article/details/gtfsmgxnil.html

Py:   os.getcwd()
来源：http://dali.jinqigufen.top/Article/details/gtyxqqvmmt.html

PHP:  getcwd();
来源：http://dali.chenzaomai.com/Article/details/gtuydgtugz.html

JS:   process.cwd()
来源：http://dali.cucudq.cn/Article/details/gtgynelobx.html

TS:   process.cwd()
来源：http://dali.fzhhl.top/Article/details/gtpeamxoal.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hywenlv.cn/Article/details/gtxdlktzet.html

Go:   os.Getwd()
来源：http://dali.jianghu66.top/Article/details/gtuuapvxjc.html

Ruby: Dir.pwd
来源：http://dali.yj202588.top/Article/details/gtdwmbsqlk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gtyodzigxe.html

[M05] 设置退出码
来源：http://dali.sxryk.cn/Article/details/gtejsotilo.html

Py:   sys.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gthftkkeak.html

PHP:  exit(1);
来源：http://dali.yuanzhike.top/Article/details/gtgmuehpta.html

JS:   process.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtymscubkb.html

TS:   process.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gtgwtznrio.html

Java: System.exit(1)
来源：http://dali.ivvv.top/Article/details/gtzbdgybaz.html

Go:   os.Exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gtcmqbcvye.html

Ruby: exit 1
来源：http://dali.smart0.xyz/Article/details/gtcxvrjmfu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yueranfly.top/Article/details/gtenyrilcl.html

[M06] 向标准错误输出
来源：http://dali.andypj.xyz/Article/details/gtletjmvkn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.chenlongwang.top/Article/details/gtilpgmzfu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nanxuanxn.top/Article/details/gtrtgtccmt.html

JS:   console.error("err")
来源：http://dali.hysaishi.cn/Article/details/gtqkrmaltp.html

TS:   console.error("err")
来源：http://dali.wangshuangyany.cn/Article/details/gtseasritf.html

Java: System.err.println("err")
来源：http://dali.meibo888.top/Article/details/gtjuzchhiy.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yanxiufei.cn/Article/details/gtvprgtcqz.html

Ruby: warn "err"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzwuatrvf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cdnleiting.top/Article/details/gtagmhwikx.html

[M07] 判断是否为主入口
来源：http://dali.zhongyouzk.top/Article/details/gtxdjpmbew.html

Py:   if __name__ == "__main__":
来源：http://dali.zycfv.cn/Article/details/gthgfapeqz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ivvv.top/Article/details/gteltmossr.html

JS:   require.main === module
来源：http://dali.nanxuanxn.top/Article/details/gtncopgkbl.html

TS:   require.main === module
来源：http://dali.yanxiufei.cn/Article/details/gtaubtposb.html

Java: public static void main(String[] args)
来源：http://dali.yonumen.top/Article/details/gtyhoinyyc.html

Go:   func main()
来源：http://dali.yj20258888.top/Article/details/gtppeywpcr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xuanzx.com/Article/details/gtoddrwlnw.html

C#:   static void Main(string[] args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtugejngrn.html

[M08] 获取系统与运行时信息
来源：http://dali.tianlin.xyz/Article/details/gtucucqowf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.chenlongwang.top/Article/details/gtjwduyxgz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ehwqpu.com/Article/details/gtahawfgig.html

JS:   process.platform;  process.version
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdijxsmsz.html

TS:   process.platform;  process.version
来源：http://dali.yvedp.cn/Article/details/gtajikdaoj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.daria6918.cn/Article/details/gtedwyuqmn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sweek.top/Article/details/gtubzglcws.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cqqwz.cn/Article/details/gtadhoznbt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.haohaochexian.top/Article/details/gtxajkkgrm.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtwukkhjdk.html

N. 数据结构与算法
来源：http://dali.feifeiyinyue.top/Article/details/gtpcycqyff.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtxjlgwcwt.html

[N01] 二分查找（有序数组）
来源：http://dali.tanke756.top/Article/details/gtzmzoevxj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtruauixyh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jianghu66.top/Article/details/gtldtkonnn.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sufxvd.cn/Article/details/gtdbknclia.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gogol.net.cn/Article/details/gtyrmnigzf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwffqdgnb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtzfpyljie.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ivvv.top/Article/details/gtrmntepby.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.meibo888.top/Article/details/gtrqsqptuo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenzaomai.com/Article/details/gtwqkgveow.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dianchejie.cn/Article/details/gtyfskudds.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.meibo888.top/Article/details/gtsnfgrmwj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gaohongyu789.top/Article/details/gtzoyihhhx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nwbrower.top/Article/details/gtsnebtcsn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yangfankeji.com/Article/details/gtwtpeyyqb.html

Go:   slices.Sort(arr)
来源：http://dali.jianghu66.top/Article/details/gtkzbfiyfg.html

Ruby: arr.sort
来源：http://dali.hywenlv.cn/Article/details/gtpcaaxbkf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.guannengcc.top/Article/details/gtlakjtpjh.html

[N03] 快速排序（分治示例）
来源：http://dali.9152youxi.cn/Article/details/gtmkhcomem.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.havefunace.top/Article/details/gtuxwkawdk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.havefunace.top/Article/details/gtwcxmjrcz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yvedp.cn/Article/details/gtcnycgimk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxinkj.top/Article/details/gtrqookadr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.fzhhl.top/Article/details/gtarhrypst.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zdqjudy.top/Article/details/gtcdbbjyhz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.0kj1m.cn/Article/details/gtrhxzlprn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ppjwa.cn/Article/details/gtlktkkypu.html

[N04] 斐波那契数列
来源：http://dali.xuetiantiany.cn/Article/details/gtnfiffkyv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gtcmqiqwjx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.wangshuangyany.cn/Article/details/gtyzojujjw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmsyafblk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tian-w.cn/Article/details/gtvtqmkgqp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.guowangkeji.top/Article/details/gtnvzfenfy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yvedp.cn/Article/details/gtwweunvpv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jqgfzy.top/Article/details/gtiyyozcee.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.gotoacloud.top/Article/details/gtufrxaonx.html

[N05] 最大公约数
来源：http://dali.yanxiufei.cn/Article/details/gtiifhtcmz.html

Py:   math.gcd(a, b)
来源：http://dali.wangshuangyany.cn/Article/details/gtzeovdsya.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yuanzhike.top/Article/details/gtgaozdfgq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nwbrower.top/Article/details/gtckfbsplu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cheryme.top/Article/details/gtoyilxdyv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhengqikj.top/Article/details/gtkarrhnjp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ydzc1.top/Article/details/gtpbmnebdu.html

Ruby: a.gcd(b)
来源：http://dali.nanxuanxn.top/Article/details/gtwssgryqk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yj20258.top/Article/details/gtrcwruxky.html

[N06] 判断回文字符串
来源：http://dali.aizwys.cn/Article/details/gtepwdvejc.html

Py:   s == s[::-1]
来源：http://dali.jqgufenzy.top/Article/details/gtvnvglimf.html

PHP:  $s === strrev($s);
来源：http://dali.zhengqikj.top/Article/details/gttoxrzdwv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ehwqpu.com/Article/details/gtrbellpys.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gtsixtbabu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gotoacloud.top/Article/details/gtpwilkssm.html

Go:   // 双指针从两端比较
来源：http://dali.guowangkeji.top/Article/details/gtvlpxnitl.html

Ruby: s == s.reverse
来源：http://dali.aizwys.cn/Article/details/gtzhunuylm.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.feifeiyinyue.top/Article/details/gtsgxrdgbo.html

[N07] 两数之和（返回下标）
来源：http://dali.hnxiangtu.top/Article/details/gtdpyurnqh.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhaomingkeji.xyz/Article/details/gtacxitnmj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.chenlongwang.top/Article/details/gtdqtqbctt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.snrcjt.cn/Article/details/gtosvakhkg.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhiwuduotai.top/Article/details/gtpjcvbvwc.html

Java: // 手写 HashMap
来源：http://dali.havefunace.top/Article/details/gteiriishn.html

Go:   // 手写 map[int]int
来源：http://dali.sweek.top/Article/details/gtjlxiytrd.html

Ruby: // 手写 Hash
来源：http://dali.gaohongyu789.top/Article/details/gtfxzgrqey.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.mhx1999.top/Article/details/gtpnjuahpt.html

[N08] 生成全排列
来源：http://dali.gaohongyu789.top/Article/details/gtonlkhcvs.html

Py:   itertools.permutations(arr)
来源：http://dali.jiagoushi.top/Article/details/gtsohxidmk.html

PHP:  // 手写递归交换
来源：http://dali.sufxvd.cn/Article/details/gtitnpyenw.html

JS:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gthsrpkhud.html

TS:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtsbvdrmqc.html

Java: // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gtgcgtvgqq.html

Go:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gtireapflf.html

Ruby: arr.permutation.to_a
来源：http://dali.chenzaomai.com/Article/details/gthhnbobdz.html

C#:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gtmxggwvgt.html

[N09] 栈与队列
来源：http://dali.shzxlz.cn/Article/details/gtelyzqlow.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sufxvd.cn/Article/details/gtkilcjgqt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yj20258.top/Article/details/gtdmwekhps.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gthzswdqdi.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nanxinkj.top/Article/details/gtphcaqtoz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.daxiang520.top/Article/details/gtazoxmoww.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hysaishi.cn/Article/details/gtmofcqdcn.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gtwsnjbvfw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sufxvd.cn/Article/details/gtwjpkrowe.html

[N10] 链表节点定义
来源：http://dali.gzhubu.top/Article/details/gtipnwofnx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yonumen.top/Article/details/gtncuqbgvn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinqigfzy.top/Article/details/gtunmrsxip.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinqigufen.top/Article/details/gtcbckwywz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.chenlongwang.top/Article/details/gtzpcybklb.html

Java: class Node { int v; Node next; }
来源：http://dali.shangyingyoupin.top/Article/details/gtxawudlip.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yuanzhike.top/Article/details/gtjlnizqvu.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zdqjudy.top/Article/details/gtdbkmviuo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.9152youxi.cn/Article/details/gtphjoncfx.html

[N11] 二叉树中序遍历
来源：http://dali.pycfn.com/Article/details/gtbtsjcron.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yongpay.top/Article/details/gtjvsfqvhj.html

PHP:  // 手写递归函数
来源：http://dali.feifeiyinyue.top/Article/details/gtucddobhc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shuidangran.top/Article/details/gtstyabdyy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nwbrower.top/Article/details/gtnazokjfh.html

Java: // 手写递归
来源：http://dali.hnqzz.top/Article/details/gtmozwsekm.html

Go:   // 手写递归
来源：http://dali.dianchejie.cn/Article/details/gtdcgvxvxu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xuanzx.com/Article/details/gteiednlzd.html

C#:   // 手写递归
来源：http://dali.cashguo.top/Article/details/gtbwhvxelx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.daria6918.cn/Article/details/gtxgbnfxfc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtetdnxntl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.nanxinkj.top/Article/details/gtrnurwuav.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgfzy.top/Article/details/gtzsadjgal.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cdnleiting.top/Article/details/gtdnnezwvv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cqqwz.cn/Article/details/gtbbposjud.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yj20258.top/Article/details/gtpuczjbtf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.mhx1999.top/Article/details/gteifikbgr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gtysrpgcbr.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtcqwdkwkv.html

O. 并发与异步
来源：http://dali.fzhhl.top/Article/details/gtyrouxghq.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtgnccwhmx.html

[O01] 启动一个线程
来源：http://dali.tanke756.top/Article/details/gtpwxsgmdo.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zdqjudy.top/Article/details/gteaujeotd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hywenlv.cn/Article/details/gtgylzhddy.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jqgufenzy.top/Article/details/gtjtzkhkib.html

TS:   // 同 JS
来源：http://dali.yvedp.cn/Article/details/gtqyeggfid.html

Java: new Thread(() -> f()).start()
来源：http://dali.chenzaomai.com/Article/details/gtwvvqlvif.html

Go:   go f()
来源：http://dali.wangshuangyany.cn/Article/details/gtrxeapqwf.html

Ruby: Thread.new { f }
来源：http://dali.yueranfly.top/Article/details/gtcciotkqm.html

C#:   Task.Run(() => F());
来源：http://dali.ppjwa.cn/Article/details/gtralqfbzq.html

[O02] 使用线程池
来源：http://dali.tianlin.xyz/Article/details/gtjlnmjjvy.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cashguo.top/Article/details/gtyunkhlqp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.gaohongyu789.top/Article/details/gtcvomvhmp.html

JS:   // worker_threads 线程池
来源：http://dali.gzhubu.top/Article/details/gtcwbjmpjf.html

TS:   // worker_threads 线程池
来源：http://dali.zhixingplan.top/Article/details/gtwnlgyewl.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hfpthk.cn/Article/details/gtjhllaqzt.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gzhubu.top/Article/details/gtimgmabpn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.wangshuangyany.cn/Article/details/gtwinfsbgj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.bjfxy.top/Article/details/gtzidowvaa.html

[O03] 加锁保护共享数据
来源：http://dali.xuetiantiany.cn/Article/details/gtuuutivis.html

Py:   with lock: shared += 1
来源：http://dali.gaohongyu789.top/Article/details/gthzeguyiq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhengqikj.top/Article/details/gtegadydct.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.chenzaomai.com/Article/details/gtoahuobze.html

TS:   // 同 JS
来源：http://dali.aizwys.cn/Article/details/gtaerqqhye.html

Java: synchronized (this) { shared++; }
来源：http://dali.gaohongyu789.top/Article/details/gtydkptrgl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.pycfn.com/Article/details/gtksxdbizz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ybcxt.top/Article/details/gtotvcwazc.html

C#:   lock (gate) { shared++; }
来源：http://dali.guannengcc.top/Article/details/gtqbkmofqs.html

[O04] 定义异步函数并等待
来源：http://dali.ehwqpu.com/Article/details/gtjbhdfzwn.html

Py:   async def f():⏎    await g()
来源：http://dali.svipenyu.cn/Article/details/gtihskiomt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.daria6918.cn/Article/details/gtzptuszsj.html

JS:   async function f() { await g(); }
来源：http://dali.sweek.top/Article/details/gticmwobdq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.vqdsnc.cn/Article/details/gtdxyclawb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.fengsongda.top/Article/details/gtiqfgwakx.html


<!-- 参考信息 -->