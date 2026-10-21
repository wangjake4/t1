代发 wailian999

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gogol.net.cn/Article/details/gtopfytefw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.9152youxi.cn/Article/details/gtaankwbdz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cucudq.cn/Article/details/gtohmtgwkf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinqigfzy.top/Article/details/gteqhuqgdp.html

Go:   encoding/gob
来源：http://dali.svipenyu.cn/Article/details/gtjmutkjib.html

Ruby: Marshal.dump(obj)
来源：http://dali.tianlin.xyz/Article/details/gtfzrawdpn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cashguo.top/Article/details/gtpiwlbjqy.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gthteugvzy.html

L. 网络请求
来源：http://dali.yueranfly.top/Article/details/gtngbymenw.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtovtkamxw.html

[L01] 发送 GET 请求
来源：http://dali.kuanghao11.cn/Article/details/gtolydvgoh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hammf.cn/Article/details/gtlttggvwl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yvedp.cn/Article/details/gtmxypgimn.html

JS:   await fetch(url)
来源：http://dali.chenjidiqi.icu/Article/details/gtpuwomvns.html

TS:   await fetch(url)
来源：http://dali.nanxuanxn.top/Article/details/gtxeatbjxo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jqgufenzy.top/Article/details/gtuapllory.html

Go:   resp, err := http.Get(url)
来源：http://dali.jiagoushi.top/Article/details/gthwnsvojy.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj202588.top/Article/details/gtkmccbwel.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdrfdmqlr.html

[L02] 发送 POST JSON
来源：http://dali.redwolf501.top/Article/details/gtucjdtfae.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqnxtwchr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sysykeji.top/Article/details/gtqlahinok.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhongyouzk.top/Article/details/gtxknbvxno.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.haohaochexian.top/Article/details/gtvsuzkqyk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.havefunace.top/Article/details/gtkcppexey.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ybcxt.top/Article/details/gthzeewkji.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shuidangran.top/Article/details/gtrwhtmcff.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.nanxuanxn.top/Article/details/gtpahsnvxg.html

[L03] 设置自定义请求头
来源：http://dali.jiagoushi.top/Article/details/gtfcjybvzv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cheryme.top/Article/details/gtwqowjivq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hnqzz.top/Article/details/gtdmppjhdz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangdashe.top/Article/details/gtpeawbqnt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cashguo.top/Article/details/gtwbnrocyd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ehwqpu.com/Article/details/gtosptmros.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.feifeiyinyue.top/Article/details/gtdsiquogz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cqqwz.cn/Article/details/gtdmtjfruf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.vqdsnc.cn/Article/details/gtlxehohnd.html

[L04] 设置超时
来源：http://dali.kuanghao11.cn/Article/details/gthfgplfyo.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shuidangran.top/Article/details/gthuttlqbp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.guannengcc.top/Article/details/gtsaztlvrb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhengqikj.top/Article/details/gtntzaqseu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaczyodjw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xuetiantiany.cn/Article/details/gtgtnrdpqg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xuanzx.com/Article/details/gtorcjiupk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtknrjvpfn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yangfankeji.com/Article/details/gtobsytkly.html

[L05] 上传文件（multipart）
来源：http://dali.smart0.xyz/Article/details/gtzwwqncyd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtemmoxjwn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.pycfn.com/Article/details/gtydyqwpgo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.meibo888.top/Article/details/gttyjgtvxf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.kuanghao11.cn/Article/details/gtiinliare.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrxzpctct.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cdnleiting.top/Article/details/gtpqvwnsnd.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhengqikj.top/Article/details/gtazcwdjyg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.iojbl.cn/Article/details/gtlrmrhecl.html

[L06] 解析响应为 JSON
来源：http://dali.dianchejie.cn/Article/details/gtsmhpdgjf.html

Py:   resp.json()
来源：http://dali.dashuyun.cn/Article/details/gtdxfcjknf.html

PHP:  json_decode($body, true);
来源：http://dali.dashuyun.cn/Article/details/gtrsssiwjf.html

JS:   await resp.json()
来源：http://dali.c1oappe.top/Article/details/gttydvwbch.html

TS:   await resp.json()
来源：http://dali.tianlin.xyz/Article/details/gtkkcgctag.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.havefunace.top/Article/details/gtceilfela.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nanxinkj.top/Article/details/gtdzdvjsrz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tian-w.cn/Article/details/gthxbkaxqn.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.c1oappe.top/Article/details/gtjdrrrziq.html

[L07] 处理 HTTP 状态码
来源：http://dali.yangfankeji.com/Article/details/gtggeytcvh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gzhubu.top/Article/details/gtwckuolpt.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.guannengcc.top/Article/details/gtgfrcatyi.html

JS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlzctvozv.html

TS:   resp.ok;  resp.status
来源：http://dali.xinyue.icu/Article/details/gtzoevziup.html

Java: resp.statusCode()
来源：http://dali.tian-w.cn/Article/details/gtnrunlwol.html

Go:   resp.StatusCode
来源：http://dali.daria6918.cn/Article/details/gtxoczpnzr.html

Ruby: resp.code.to_i
来源：http://dali.mhx1999.top/Article/details/gtveinftyl.html

C#:   (int)resp.StatusCode
来源：http://dali.xylfe.cn/Article/details/gtxzetewxt.html

[L08] 并发请求多个地址
来源：http://dali.yangfankeji.com/Article/details/gtjdrofmmn.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.smart0.xyz/Article/details/gtqyeodfpa.html

PHP:  curl_multi_init() 系列
来源：http://dali.guannengcc.top/Article/details/gtsktwjflk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.svipenyu.cn/Article/details/gtqcpmivmq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.andypj.xyz/Article/details/gtroujkphg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yuanzhike.top/Article/details/gtsbprsnxl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cqqwz.cn/Article/details/gtfpyuihbd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ppjwa.cn/Article/details/gthfvtnjut.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj20258.top/Article/details/gtpmjnwpev.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gttyrxsrcz.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinqigfzy.top/Article/details/gtkbzaamfl.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtglmuermn.html

[M01] 读取命令行参数
来源：http://dali.tian-w.cn/Article/details/gtnnjgqstg.html

Py:   sys.argv[1:]
来源：http://dali.316326.xyz/Article/details/gtoxhhvjmv.html

PHP:  $argv;  $argc;
来源：http://dali.cucudq.cn/Article/details/gtzkgqgknk.html

JS:   process.argv.slice(2)
来源：http://dali.tianlin.xyz/Article/details/gtgxqxsyqr.html

TS:   process.argv.slice(2)
来源：http://dali.hongshengwenyu.top/Article/details/gtigrvuemt.html

Java: args 数组（main 方法参数）
来源：http://dali.0kj1m.cn/Article/details/gtysikwxxy.html

Go:   os.Args[1:]
来源：http://dali.aibaodan.cn/Article/details/gtqyevpvde.html

Ruby: ARGV
来源：http://dali.zhoulong.xyz/Article/details/gtkroqlsye.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zycfv.cn/Article/details/gtwyhazbnl.html

[M02] 读取环境变量
来源：http://dali.cheryme.top/Article/details/gtjbosxfhe.html

Py:   os.environ.get("HOME")
来源：http://dali.chenlongwang.top/Article/details/gtpjatqnfo.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.pycfn.com/Article/details/gtcbjhvmgd.html

JS:   process.env.HOME
来源：http://dali.sweek.top/Article/details/gtplkvneyl.html

TS:   process.env.HOME
来源：http://dali.gaohongyu789.top/Article/details/gtktlnfgiq.html

Java: System.getenv("HOME")
来源：http://dali.ydzc1.top/Article/details/gtibkorewz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdwqikbmo.html

Ruby: ENV["HOME"]
来源：http://dali.ppjwa.cn/Article/details/gtjanalqap.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.daria6918.cn/Article/details/gtqgdvfmjp.html

[M03] 执行外部命令
来源：http://dali.guannengcc.top/Article/details/gtkofgosbr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.iojbl.cn/Article/details/gtvnbtiveh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shuidangran.top/Article/details/gtjhozjywz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.svipenyu.cn/Article/details/gtvrkaijol.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.guannengcc.top/Article/details/gtipqetgcm.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.quarkkingdee.top/Article/details/gtrwqpftbe.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gaohongyu789.top/Article/details/gttocianvt.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.haohaochexian.top/Article/details/gtuybdrjrv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.fengsongda.top/Article/details/gtyjawndto.html

[M04] 获取当前工作目录
来源：http://dali.ybcxt.top/Article/details/gtfavjojjt.html

Py:   os.getcwd()
来源：http://dali.snrcjt.cn/Article/details/gtumjmcngw.html

PHP:  getcwd();
来源：http://dali.havefunace.top/Article/details/gtshvmikze.html

JS:   process.cwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyckzmuvg.html

TS:   process.cwd()
来源：http://dali.sxryk.cn/Article/details/gtmflvbdgl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.iojbl.cn/Article/details/gtsommzcwm.html

Go:   os.Getwd()
来源：http://dali.xziqi.cn/Article/details/gtecunsoft.html

Ruby: Dir.pwd
来源：http://dali.hysaishi.cn/Article/details/gtbyxvdmlj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.316326.xyz/Article/details/gtputpphei.html

[M05] 设置退出码
来源：http://dali.smart0.xyz/Article/details/gtdxvoftga.html

Py:   sys.exit(1)
来源：http://dali.cashguo.top/Article/details/gtttndimiq.html

PHP:  exit(1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtugzncftr.html

JS:   process.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsoviepyc.html

TS:   process.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtughelxtv.html

Java: System.exit(1)
来源：http://dali.ybcxt.top/Article/details/gtvztzrzfd.html

Go:   os.Exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtqhqpymgd.html

Ruby: exit 1
来源：http://dali.iojbl.cn/Article/details/gtucohsoms.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfgkmwwjx.html

[M06] 向标准错误输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuerpcibq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.nanxinkj.top/Article/details/gtzewslczm.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtguhofhjj.html

JS:   console.error("err")
来源：http://dali.dianchejie.cn/Article/details/gteajtdvbi.html

TS:   console.error("err")
来源：http://dali.yj20258888.top/Article/details/gttlfykouj.html

Java: System.err.println("err")
来源：http://dali.sufxvd.cn/Article/details/gttwcyxaez.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.redwolf501.top/Article/details/gtyufqqdjq.html

Ruby: warn "err"
来源：http://dali.jinghuilouyu.cn/Article/details/gtwkcahnjq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.daxiang520.top/Article/details/gtvjnphhsq.html

[M07] 判断是否为主入口
来源：http://dali.kuanghao11.cn/Article/details/gtwhaiyokq.html

Py:   if __name__ == "__main__":
来源：http://dali.tian-w.cn/Article/details/gthjonpdjh.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jyoumei.cn/Article/details/gtageabibr.html

JS:   require.main === module
来源：http://dali.zhixingplan.top/Article/details/gtazzvrdtc.html

TS:   require.main === module
来源：http://dali.yuxming.cn/Article/details/gtevqvrjik.html

Java: public static void main(String[] args)
来源：http://dali.andypj.xyz/Article/details/gtzxptmtqv.html

Go:   func main()
来源：http://dali.zhaomingkeji.xyz/Article/details/gthyspjywu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jiagoushi.top/Article/details/gtiqtlblmw.html

C#:   static void Main(string[] args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgznwvniw.html

[M08] 获取系统与运行时信息
来源：http://dali.ybcxt.top/Article/details/gtvofllwot.html

Py:   platform.system();  platform.python_version()
来源：http://dali.andypj.xyz/Article/details/gtxfihbjlb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shanyushiyangtech.top/Article/details/gtepscaxqf.html

JS:   process.platform;  process.version
来源：http://dali.kuanghao11.cn/Article/details/gtxysnufui.html

TS:   process.platform;  process.version
来源：http://dali.nwbrower.top/Article/details/gtukhunimq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gtpjogvdwe.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yuanzhike.top/Article/details/gtmuuzhcwj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.tian-w.cn/Article/details/gtfhmujrlr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.havefunace.top/Article/details/gtpwbfipsl.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtjicuytdy.html

N. 数据结构与算法
来源：http://dali.hysaishi.cn/Article/details/gtwuabvavi.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtciktwgjx.html

[N01] 二分查找（有序数组）
来源：http://dali.hongshengwenyu.top/Article/details/gtsevdgfhp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtiusqfjfg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yueranfly.top/Article/details/gtlhzvxazf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aibaodan.cn/Article/details/gtgqlxkjvp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgfzy.top/Article/details/gtbkecyzza.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtllpexwas.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ivvv.top/Article/details/gtzhmrfngf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhixingplan.top/Article/details/gtvyzqhiso.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtteauwjkf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.haohaochexian.top/Article/details/gtmkozgumt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jiagoushi.top/Article/details/gtjzqupyux.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ybcxt.top/Article/details/gtrbhccmtu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.svipenyu.cn/Article/details/gtbjntohlz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tanke756.top/Article/details/gtmrfuagxi.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhoulong.xyz/Article/details/gthquwgvgs.html

Go:   slices.Sort(arr)
来源：http://dali.gotoacloud.top/Article/details/gthtgiqglu.html

Ruby: arr.sort
来源：http://dali.daria6918.cn/Article/details/gtklejpfgs.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.daxiang520.top/Article/details/gtnuzrgero.html

[N03] 快速排序（分治示例）
来源：http://dali.9152youxi.cn/Article/details/gtzivwelhq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.aibaodan.cn/Article/details/gtotrpcliu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.sufxvd.cn/Article/details/gtfjbyjltl.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gtolmqqkrs.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fzhhl.top/Article/details/gtmspcgbey.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinghuilouyu.cn/Article/details/gttuhbrvlt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenlongwang.top/Article/details/gtuahhbqbq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sweek.top/Article/details/gtbduepbri.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.feifeiyinyue.top/Article/details/gtipkvwctd.html

[N04] 斐波那契数列
来源：http://dali.jinqigfzy.top/Article/details/gtgjfwnmnb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.guowangkeji.top/Article/details/gtfeuuauha.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.aizwys.cn/Article/details/gtsyfrwzgv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hfpthk.cn/Article/details/gtubpwzker.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ehwqpu.com/Article/details/gtmerujnrz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.sufxvd.cn/Article/details/gtxfdqloiw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zdqjudy.top/Article/details/gthpcjmnqu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sweek.top/Article/details/gtrvkhqhcr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.birdmap.top/Article/details/gtpvvmtsaa.html

[N05] 最大公约数
来源：http://dali.sysykeji.top/Article/details/gtqldglvee.html

Py:   math.gcd(a, b)
来源：http://dali.chenjidiqi.icu/Article/details/gtzuywuziv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.tianlin.xyz/Article/details/gtddmriqln.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hammf.cn/Article/details/gttvxkpmxn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tianlin.xyz/Article/details/gtssnxnyyl.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinghuilouyu.cn/Article/details/gtuprxypxo.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jiagoushi.top/Article/details/gtagkpmvfz.html

Ruby: a.gcd(b)
来源：http://dali.fzhhl.top/Article/details/gtjomucqwh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yanxiufei.cn/Article/details/gthmjwkjny.html

[N06] 判断回文字符串
来源：http://dali.jyoumei.cn/Article/details/gtozzkuvbd.html

Py:   s == s[::-1]
来源：http://dali.cqqwz.cn/Article/details/gtlzjkcpcr.html

PHP:  $s === strrev($s);
来源：http://dali.hfpthk.cn/Article/details/gthjzkpfed.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtyunxygew.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gtchithyyz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sufxvd.cn/Article/details/gtvwypqpch.html

Go:   // 双指针从两端比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtocjlrlum.html

Ruby: s == s.reverse
来源：http://dali.jlsjyb.cn/Article/details/gtqtgzigsg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hfpthk.cn/Article/details/gthrbsdpee.html

[N07] 两数之和（返回下标）
来源：http://dali.zdqjudy.top/Article/details/gtoguvqbzg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yangfankeji.com/Article/details/gtkyvyzews.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.iojbl.cn/Article/details/gtvfxvbhyw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.meibo888.top/Article/details/gtxyfyhwwv.html

TS:   // 手写 Map<string, number>
来源：http://dali.svipenyu.cn/Article/details/gtbgdpmmwt.html

Java: // 手写 HashMap
来源：http://dali.ybcxt.top/Article/details/gtykducyzx.html

Go:   // 手写 map[int]int
来源：http://dali.yueranfly.top/Article/details/gtqpqspwio.html

Ruby: // 手写 Hash
来源：http://dali.hammf.cn/Article/details/gtiinybpsa.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jqgfzy.top/Article/details/gtfyhifjsd.html

[N08] 生成全排列
来源：http://dali.jiagoushi.top/Article/details/gtewkrokpi.html

Py:   itertools.permutations(arr)
来源：http://dali.nwbrower.top/Article/details/gttchjrexw.html

PHP:  // 手写递归交换
来源：http://dali.316326.xyz/Article/details/gtcgwnayve.html

JS:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gtvzemznrr.html

TS:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gtpubujsqi.html

Java: // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gtngypvcku.html

Go:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gtskmdntii.html

Ruby: arr.permutation.to_a
来源：http://dali.chenzaomai.com/Article/details/gtxutcuaqi.html

C#:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtrsqgyqjm.html

[N09] 栈与队列
来源：http://dali.cqqwz.cn/Article/details/gtfhayxdbu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.nwbrower.top/Article/details/gtkfrmizii.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hfpthk.cn/Article/details/gtvnlosyhz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jyoumei.cn/Article/details/gtxmpfyfmg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.dianchejie.cn/Article/details/gtwhsckhdx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.guowangkeji.top/Article/details/gtgffkweyw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.smart0.xyz/Article/details/gtvgcoxbzm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.mhx1999.top/Article/details/gtfpfrchmk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.tanke756.top/Article/details/gtowpdlmxw.html

[N10] 链表节点定义
来源：http://dali.haohaochexian.top/Article/details/gtnatsqqre.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gaohongyu789.top/Article/details/gtobkuixoe.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shangyingyoupin.top/Article/details/gtsdfvywbf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yuxming.cn/Article/details/gtyzmniirl.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinqigufen.top/Article/details/gtizbvoygq.html

Java: class Node { int v; Node next; }
来源：http://dali.ybcxt.top/Article/details/gtdqqrrkvy.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sufxvd.cn/Article/details/gttwrzbekw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcttselhz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqzeccfyf.html

[N11] 二叉树中序遍历
来源：http://dali.andypj.xyz/Article/details/gtjmqzrhou.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.pycfn.com/Article/details/gthdavsvyy.html

PHP:  // 手写递归函数
来源：http://dali.hysaishi.cn/Article/details/gtfopljinv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yueranfly.top/Article/details/gtjigwhbay.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yvedp.cn/Article/details/gtqbqlcmks.html

Java: // 手写递归
来源：http://dali.316326.xyz/Article/details/gthhxqcttd.html

Go:   // 手写递归
来源：http://dali.xinyue.icu/Article/details/gtigxfqjmt.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yj202588.top/Article/details/gtjmeogaus.html

C#:   // 手写递归
来源：http://dali.yvedp.cn/Article/details/gtxrpjzzac.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sufxvd.cn/Article/details/gtqevfyatd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yj20258888.top/Article/details/gtuhkuekwk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhongyouzk.top/Article/details/gtfyonbwas.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tanke756.top/Article/details/gtnztmqale.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xuetiantiany.cn/Article/details/gtzljkiysj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cdnleiting.top/Article/details/gtiumpitjc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.guowangkeji.top/Article/details/gtaaircxzr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yuanzhike.top/Article/details/gtdyuctppb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhixingplan.top/Article/details/gtabnlnjup.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtijoliikv.html

O. 并发与异步
来源：http://dali.gogol.net.cn/Article/details/gtbeucaiqx.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtiuzzotdf.html

[O01] 启动一个线程
来源：http://dali.nanxuanxn.top/Article/details/gtpvltawvr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.haohaochexian.top/Article/details/gtjtypcmmx.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yangfankeji.com/Article/details/gthmyhruuv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yonumen.top/Article/details/gtgnhyhnyi.html

TS:   // 同 JS
来源：http://dali.yonumen.top/Article/details/gtzawaqloa.html

Java: new Thread(() -> f()).start()
来源：http://dali.havefunace.top/Article/details/gtobmfglhx.html

Go:   go f()
来源：http://dali.dianchejie.cn/Article/details/gtwlivztmi.html

Ruby: Thread.new { f }
来源：http://dali.yuanzhike.top/Article/details/gtvdastblq.html

C#:   Task.Run(() => F());
来源：http://dali.ppjwa.cn/Article/details/gtmfgzpmyt.html

[O02] 使用线程池
来源：http://dali.haohaochexian.top/Article/details/gtwrntmmxs.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gzhubu.top/Article/details/gtyybrnzbb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.gaohongyu789.top/Article/details/gtohtiydtd.html

JS:   // worker_threads 线程池
来源：http://dali.cqqwz.cn/Article/details/gtsrzdopur.html

TS:   // worker_threads 线程池
来源：http://dali.jinghuilouyu.cn/Article/details/gtzkcgtkmi.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yonumen.top/Article/details/gtnwqlfics.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yj202588.top/Article/details/gtapwolunw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.c1oappe.top/Article/details/gtojkspowm.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yonumen.top/Article/details/gtycgiddkh.html

[O03] 加锁保护共享数据
来源：http://dali.andypj.xyz/Article/details/gtqewootzp.html

Py:   with lock: shared += 1
来源：http://dali.guannengcc.top/Article/details/gtqblvcxxe.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yueranfly.top/Article/details/gtlasvzlce.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xziqi.cn/Article/details/gtvtjycfth.html

TS:   // 同 JS
来源：http://dali.svipenyu.cn/Article/details/gthihxjpwe.html

Java: synchronized (this) { shared++; }
来源：http://dali.svipenyu.cn/Article/details/gtbpiphrxk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.dianchejie.cn/Article/details/gtfzxusyic.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.tian-w.cn/Article/details/gtkfaxrlaw.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdpoufwun.html

[O04] 定义异步函数并等待
来源：http://dali.ppjwa.cn/Article/details/gtmncxoput.html

Py:   async def f():⏎    await g()
来源：http://dali.pycfn.com/Article/details/gtfyepixwq.html


<!-- 参考信息 -->