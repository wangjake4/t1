代发 wailian999

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gzhubu.top/Article/details/gtnctedtel.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jiagoushi.top/Article/details/gtuzqouleg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sxryk.cn/Article/details/gtokyiufim.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.guowangkeji.top/Article/details/gtpttkbsto.html

Go:   encoding/gob
来源：http://dali.daxiang520.top/Article/details/gtxzbsdqgg.html

Ruby: Marshal.dump(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtemkpzied.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.havefunace.top/Article/details/gthdfgbjvx.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtqnuzbxje.html

L. 网络请求
来源：http://dali.hongshengwenyu.top/Article/details/gtgfauypgd.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtynojmvdp.html

[L01] 发送 GET 请求
来源：http://dali.yonumen.top/Article/details/gtvuenrmme.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlpgoxpxs.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yuanzhike.top/Article/details/gtjditwyja.html

JS:   await fetch(url)
来源：http://dali.gzhubu.top/Article/details/gtcyizdspv.html

TS:   await fetch(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxbkflqcn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sxryk.cn/Article/details/gtuuupkkjb.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhoulong.xyz/Article/details/gtykhuqdzm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhixingplan.top/Article/details/gtbcxltagh.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinqigufen.top/Article/details/gtzqoebupm.html

[L02] 发送 POST JSON
来源：http://dali.hongshengwenyu.top/Article/details/gtrxpidtpp.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.redwolf501.top/Article/details/gtkolbxfdj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.svipenyu.cn/Article/details/gtrfiixeka.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yongpay.top/Article/details/gtsdajgboc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.quarkkingdee.top/Article/details/gtffdycxiz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jqgfzy.top/Article/details/gtlenjiyrn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jqgfzy.top/Article/details/gtynecfwbn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yuxming.cn/Article/details/gturtqyhik.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ivvv.top/Article/details/gtitlvfuvo.html

[L03] 设置自定义请求头
来源：http://dali.zdqjudy.top/Article/details/gtytseihrr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sufxvd.cn/Article/details/gtyhvjfrcp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.kuanghao11.cn/Article/details/gtldcmiffu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sufxvd.cn/Article/details/gtsihsyknh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangtech.top/Article/details/gtyszktlpc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.guannengcc.top/Article/details/gtdpdryafc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.dashuyun.cn/Article/details/gtqiibvopt.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.c1oappe.top/Article/details/gtrxteunom.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cucudq.cn/Article/details/gtawkhmmgq.html

[L04] 设置超时
来源：http://dali.jinghuilouyu.cn/Article/details/gtxyehdgaf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.meibo888.top/Article/details/gtrjjheawh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.smart0.xyz/Article/details/gtirmmsgsg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.smart0.xyz/Article/details/gtutiwldet.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.birdmap.top/Article/details/gtmwpygdss.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.chenzaomai.com/Article/details/gtatqmmwlh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hnxiangtu.top/Article/details/gtkieildwl.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhengqikj.top/Article/details/gtmamwjgby.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.c1oappe.top/Article/details/gtthkqcwry.html

[L05] 上传文件（multipart）
来源：http://dali.gaohongyu789.top/Article/details/gtykvghhsi.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jqgfzy.top/Article/details/gtslmwsgit.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.tian-w.cn/Article/details/gtobrdmnot.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tianlin.xyz/Article/details/gtbwbapmrb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenlongwang.top/Article/details/gtjfdhgwue.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jqgufenzy.top/Article/details/gttfkndfei.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hnqzz.top/Article/details/gtmtemaize.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwnvipqek.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.tian-w.cn/Article/details/gtvpyjrilc.html

[L06] 解析响应为 JSON
来源：http://dali.shzxlz.cn/Article/details/gtknixcvtx.html

Py:   resp.json()
来源：http://dali.jinqigufen.top/Article/details/gtorvcxcnl.html

PHP:  json_decode($body, true);
来源：http://dali.sxryk.cn/Article/details/gtoicujsrm.html

JS:   await resp.json()
来源：http://dali.zhongyouzk.top/Article/details/gtbawuxjks.html

TS:   await resp.json()
来源：http://dali.sysykeji.top/Article/details/gtixbaxnbl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.wangdashe.top/Article/details/gtqpftnlzu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.dianchejie.cn/Article/details/gtlsnlbunt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jlsjyb.cn/Article/details/gtqrgbyfgz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hysaishi.cn/Article/details/gtnogsdmvd.html

[L07] 处理 HTTP 状态码
来源：http://dali.316326.xyz/Article/details/gtgulzaqxt.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.9152youxi.cn/Article/details/gtmzzlrabc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.aizwys.cn/Article/details/gtrjbwckfj.html

JS:   resp.ok;  resp.status
来源：http://dali.yj20258888.top/Article/details/gtmzklcmmh.html

TS:   resp.ok;  resp.status
来源：http://dali.nanxinkj.top/Article/details/gtrsomcksy.html

Java: resp.statusCode()
来源：http://dali.zhongyouzk.top/Article/details/gthmoaxpik.html

Go:   resp.StatusCode
来源：http://dali.yanxiufei.cn/Article/details/gtkjfohrkr.html

Ruby: resp.code.to_i
来源：http://dali.yj20258888.top/Article/details/gtwohpbegh.html

C#:   (int)resp.StatusCode
来源：http://dali.tianlin.xyz/Article/details/gtbpysxrpc.html

[L08] 并发请求多个地址
来源：http://dali.daxiang520.top/Article/details/gtpmtnvrkd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cashguo.top/Article/details/gtjpqkplhw.html

PHP:  curl_multi_init() 系列
来源：http://dali.hnqzz.top/Article/details/gtubwwbaad.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hfpthk.cn/Article/details/gtijyecyrn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pycfn.com/Article/details/gtxwkmvfzm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shangyingyoupin.top/Article/details/gtzkntrcob.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.havefunace.top/Article/details/gtjahacpiw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ydzc1.top/Article/details/gtwgtyymsj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gtcznouzbi.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtdxqsbekb.html

M. 命令行 / 进程 / 环境
来源：http://dali.tianlin.xyz/Article/details/gtscllkgoe.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtceuzyszf.html

[M01] 读取命令行参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgisuvqmr.html

Py:   sys.argv[1:]
来源：http://dali.ivvv.top/Article/details/gtpigbawiz.html

PHP:  $argv;  $argc;
来源：http://dali.zhengqikj.top/Article/details/gtqhoggodx.html

JS:   process.argv.slice(2)
来源：http://dali.c1oappe.top/Article/details/gtwhkrvccv.html

TS:   process.argv.slice(2)
来源：http://dali.cashguo.top/Article/details/gtplcahsow.html

Java: args 数组（main 方法参数）
来源：http://dali.cqqwz.cn/Article/details/gtwcuozhfr.html

Go:   os.Args[1:]
来源：http://dali.shangyingyoupin.top/Article/details/gtmvbrfyqt.html

Ruby: ARGV
来源：http://dali.xziqi.cn/Article/details/gtqfgpuyvx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yuxming.cn/Article/details/gtxbkslhxl.html

[M02] 读取环境变量
来源：http://dali.ydzc1.top/Article/details/gtdakwikpw.html

Py:   os.environ.get("HOME")
来源：http://dali.birdmap.top/Article/details/gtnsbstujj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.wangshuangyany.cn/Article/details/gtsyzjxruo.html

JS:   process.env.HOME
来源：http://dali.jinqigufen.top/Article/details/gtdxpewwiw.html

TS:   process.env.HOME
来源：http://dali.haohaochexian.top/Article/details/gtlaihoogk.html

Java: System.getenv("HOME")
来源：http://dali.andypj.xyz/Article/details/gtxnfcyhir.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.dashuyun.cn/Article/details/gtpyleylur.html

Ruby: ENV["HOME"]
来源：http://dali.zdqjudy.top/Article/details/gtplzqtoms.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.pycfn.com/Article/details/gtwpnaldgx.html

[M03] 执行外部命令
来源：http://dali.aizwys.cn/Article/details/gtdkfbypfp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.daria6918.cn/Article/details/gtvldbrtky.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jiagoushi.top/Article/details/gtmrianivl.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nwbrower.top/Article/details/gttodxkfdt.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.daxiang520.top/Article/details/gtzkmfzylf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.chenzaomai.com/Article/details/gtvfpmungo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gtonqfdeoj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.daria6918.cn/Article/details/gtggxluuse.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hongshengwenyu.top/Article/details/gtzbebxich.html

[M04] 获取当前工作目录
来源：http://dali.zdqjudy.top/Article/details/gtauqftvoc.html

Py:   os.getcwd()
来源：http://dali.hongshengwenyu.top/Article/details/gtiixfqunw.html

PHP:  getcwd();
来源：http://dali.zhengqikj.top/Article/details/gtunmylwbu.html

JS:   process.cwd()
来源：http://dali.sweek.top/Article/details/gtogusegyp.html

TS:   process.cwd()
来源：http://dali.dianchejie.cn/Article/details/gtbaqcorpt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yvedp.cn/Article/details/gtngvoubrc.html

Go:   os.Getwd()
来源：http://dali.ppjwa.cn/Article/details/gttvkoydku.html

Ruby: Dir.pwd
来源：http://dali.zhoulong.xyz/Article/details/gtevpgvrer.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hnqzz.top/Article/details/gtuxpbyehe.html

[M05] 设置退出码
来源：http://dali.hnxiangtu.top/Article/details/gthexyevmx.html

Py:   sys.exit(1)
来源：http://dali.sweek.top/Article/details/gtbzhdyyho.html

PHP:  exit(1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcvqgukrg.html

JS:   process.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gtgnmhgqxz.html

TS:   process.exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gteerywnzf.html

Java: System.exit(1)
来源：http://dali.c1oappe.top/Article/details/gttsbeszii.html

Go:   os.Exit(1)
来源：http://dali.dianchejie.cn/Article/details/gtzsflzrwb.html

Ruby: exit 1
来源：http://dali.xylfe.cn/Article/details/gtsnvvgtwi.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nanxuanxn.top/Article/details/gtzxrbtydd.html

[M06] 向标准错误输出
来源：http://dali.tian-w.cn/Article/details/gtlqyiowzx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gogol.net.cn/Article/details/gtwjzubaox.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.dianchejie.cn/Article/details/gtjjrxwsqc.html

JS:   console.error("err")
来源：http://dali.xuetiantiany.cn/Article/details/gtkyuidtin.html

TS:   console.error("err")
来源：http://dali.quarkkingdee.top/Article/details/gtmdmevwxf.html

Java: System.err.println("err")
来源：http://dali.aibaodan.cn/Article/details/gtvumyanfl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yangfankeji.com/Article/details/gtasbrlcbs.html

Ruby: warn "err"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiafhsgwv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yuanzhike.top/Article/details/gtdjldnbfm.html

[M07] 判断是否为主入口
来源：http://dali.aibaodan.cn/Article/details/gtmeheysnj.html

Py:   if __name__ == "__main__":
来源：http://dali.svipenyu.cn/Article/details/gtoombyqkp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.nanxuanxn.top/Article/details/gtmtilmcjt.html

JS:   require.main === module
来源：http://dali.cheryme.top/Article/details/gtvloswbvk.html

TS:   require.main === module
来源：http://dali.zdqjudy.top/Article/details/gtfcsyfpnt.html

Java: public static void main(String[] args)
来源：http://dali.feifeiyinyue.top/Article/details/gtvcfxpreg.html

Go:   func main()
来源：http://dali.jianghu66.top/Article/details/gtsyqtwkkt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.aizwys.cn/Article/details/gtdqwdlonk.html

C#:   static void Main(string[] args)
来源：http://dali.jqgfzy.top/Article/details/gtfdwectxl.html

[M08] 获取系统与运行时信息
来源：http://dali.sufxvd.cn/Article/details/gtartirwep.html

Py:   platform.system();  platform.python_version()
来源：http://dali.vqdsnc.cn/Article/details/gtkdkbpjfo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xylfe.cn/Article/details/gtadztzppc.html

JS:   process.platform;  process.version
来源：http://dali.dashuyun.cn/Article/details/gthfjirqqj.html

TS:   process.platform;  process.version
来源：http://dali.nanxuanxn.top/Article/details/gtzjbdnevx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.chenjidiqi.icu/Article/details/gtjibjckof.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.0kj1m.cn/Article/details/gtfipcmufa.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.chenjidiqi.icu/Article/details/gtolgxnypp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.bjfxy.top/Article/details/gtdbmydjqi.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtrtbjvgnn.html

N. 数据结构与算法
来源：http://dali.fzhhl.top/Article/details/gtavuhfwgr.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtjvfpfmwz.html

[N01] 二分查找（有序数组）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjsaluzka.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.iojbl.cn/Article/details/gtbhuwwigg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.wangdashe.top/Article/details/gtdgjttmth.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pycfn.com/Article/details/gtfmebjzcd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hammf.cn/Article/details/gtyticmdkt.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gteymmtwcx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gtujnrzpex.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.smart0.xyz/Article/details/gtetreyxex.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtgvcecqaj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinghuilouyu.cn/Article/details/gtwubudjds.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cucudq.cn/Article/details/gtmgymdrfn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.gzhubu.top/Article/details/gtcllekayg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yanxiufei.cn/Article/details/gtfvizbshj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cdnleiting.top/Article/details/gtpzrkcizk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhiwuduotai.top/Article/details/gtwviblvis.html

Go:   slices.Sort(arr)
来源：http://dali.fengsongda.top/Article/details/gtrkxuigip.html

Ruby: arr.sort
来源：http://dali.xylfe.cn/Article/details/gtkiomriic.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xylfe.cn/Article/details/gtwtkhffmd.html

[N03] 快速排序（分治示例）
来源：http://dali.meibo888.top/Article/details/gtkukiefxs.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinqigfzy.top/Article/details/gtqeshjjra.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ydzc1.top/Article/details/gtdwkgqnlq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zycfv.cn/Article/details/gtdvqkkuco.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fzhhl.top/Article/details/gtzurhayuk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hammf.cn/Article/details/gtzfmrbeda.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jiagoushi.top/Article/details/gtmsacswsc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hysaishi.cn/Article/details/gtruhocycj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.9152youxi.cn/Article/details/gtvkubqhaw.html

[N04] 斐波那契数列
来源：http://dali.zhengqikj.top/Article/details/gtbtraeumk.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cashguo.top/Article/details/gtahsapxvg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.havefunace.top/Article/details/gtqbnxtuin.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yueranfly.top/Article/details/gthecdppep.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.havefunace.top/Article/details/gtqjymcdwh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.svipenyu.cn/Article/details/gtzqqiwijp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.tianlin.xyz/Article/details/gtbwtufagh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigfzy.top/Article/details/gtbgeerrjd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hywenlv.cn/Article/details/gtachcllsf.html

[N05] 最大公约数
来源：http://dali.dashuyun.cn/Article/details/gtzbsklpwh.html

Py:   math.gcd(a, b)
来源：http://dali.mhx1999.top/Article/details/gtxapabaus.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.snrcjt.cn/Article/details/gtoofdcyag.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aizwys.cn/Article/details/gtkuswutsb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhongyouzk.top/Article/details/gtiimankmb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yj20258.top/Article/details/gtezdqgffo.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.kuanghao11.cn/Article/details/gthxclomcz.html

Ruby: a.gcd(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtircfommn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.meibo888.top/Article/details/gtxmnpzafn.html

[N06] 判断回文字符串
来源：http://dali.pycfn.com/Article/details/gtkuergrtq.html

Py:   s == s[::-1]
来源：http://dali.hnqzz.top/Article/details/gtkghluyln.html

PHP:  $s === strrev($s);
来源：http://dali.sysykeji.top/Article/details/gtnyxysbdc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gtrkeiepgz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gtbvchdgmz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xuetiantiany.cn/Article/details/gtiqxhjqjy.html

Go:   // 双指针从两端比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcukonlpb.html

Ruby: s == s.reverse
来源：http://dali.shangyingyoupin.top/Article/details/gthddifuku.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxypaepnm.html

[N07] 两数之和（返回下标）
来源：http://dali.yuxming.cn/Article/details/gtetxdrnab.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cheryme.top/Article/details/gtjjwszmjg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hywenlv.cn/Article/details/gteatjtlrv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.pengpengdd.cyou/Article/details/gtozdoygsm.html

TS:   // 手写 Map<string, number>
来源：http://dali.yvedp.cn/Article/details/gtzdgweuug.html

Java: // 手写 HashMap
来源：http://dali.shzxlz.cn/Article/details/gtqhqzskns.html

Go:   // 手写 map[int]int
来源：http://dali.yj20258888.top/Article/details/gtvezbfqek.html

Ruby: // 手写 Hash
来源：http://dali.iojbl.cn/Article/details/gtnbawawtx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxdhfbvvc.html

[N08] 生成全排列
来源：http://dali.jianghu66.top/Article/details/gtqyntqefu.html

Py:   itertools.permutations(arr)
来源：http://dali.c1oappe.top/Article/details/gtthsozhld.html

PHP:  // 手写递归交换
来源：http://dali.yangfankeji.com/Article/details/gtvogkpahk.html

JS:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gtttbdudjp.html

TS:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gtbvblrhxq.html

Java: // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gtglyxouia.html

Go:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtkhjlnzqs.html

Ruby: arr.permutation.to_a
来源：http://dali.xuetiantiany.cn/Article/details/gtcfvlwfin.html

C#:   // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gtjsepuiqa.html

[N09] 栈与队列
来源：http://dali.wangshuangyany.cn/Article/details/gtjwawdzuh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.havefunace.top/Article/details/gtohwwnkcd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.kuanghao11.cn/Article/details/gtacislvun.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yonumen.top/Article/details/gtoossmbzj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.bjfxy.top/Article/details/gtugecezoa.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.fzhhl.top/Article/details/gtnhhiciau.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yueranfly.top/Article/details/gtbmsdnzwv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.guannengcc.top/Article/details/gthvlhyixp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.tian-w.cn/Article/details/gthvqthagq.html

[N10] 链表节点定义
来源：http://dali.cdnleiting.top/Article/details/gtpacyfutd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yueranfly.top/Article/details/gtxsvxuaei.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ybcxt.top/Article/details/gtgytbvnqm.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zycfv.cn/Article/details/gtprgwpusi.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ydzc1.top/Article/details/gtmetkjags.html

Java: class Node { int v; Node next; }
来源：http://dali.hongshengwenyu.top/Article/details/gtggsnoukl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ppjwa.cn/Article/details/gtmqvbuvcu.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yj20258.top/Article/details/gtgmkihmlk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcsokmgwv.html

[N11] 二叉树中序遍历
来源：http://dali.zhongyouzk.top/Article/details/gtqocpyexq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.wangshuangyany.cn/Article/details/gtzudxjudh.html

PHP:  // 手写递归函数
来源：http://dali.gaohongyu789.top/Article/details/gtlrvlzgml.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hfpthk.cn/Article/details/gtkeprjdrt.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhengqikj.top/Article/details/gtlhnemhmb.html

Java: // 手写递归
来源：http://dali.havefunace.top/Article/details/gtjpnqdcjs.html

Go:   // 手写递归
来源：http://dali.tianlin.xyz/Article/details/gtshbcvddn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yangfankeji.com/Article/details/gtfztiqpxm.html

C#:   // 手写递归
来源：http://dali.pycfn.com/Article/details/gtejuhtanv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.fzhhl.top/Article/details/gtfaehheix.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xylfe.cn/Article/details/gtyphathwy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cdnleiting.top/Article/details/gtxehlqeir.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sweek.top/Article/details/gtlyyhhdac.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fzhhl.top/Article/details/gtzboshree.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shangyingyoupin.top/Article/details/gtteqbseil.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.guowangkeji.top/Article/details/gtwbzpoiuv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yj20258.top/Article/details/gtvkbcpjej.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shangyingyoupin.top/Article/details/gtkfllepfl.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtseilazjo.html

O. 并发与异步
来源：http://dali.svipenyu.cn/Article/details/gtvhfeyuhr.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gttmnicvay.html

[O01] 启动一个线程
来源：http://dali.gogol.net.cn/Article/details/gtmwalbehc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gogol.net.cn/Article/details/gtfvvuiqyi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.daria6918.cn/Article/details/gtussbueto.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yuxming.cn/Article/details/gtcjluzomw.html

TS:   // 同 JS
来源：http://dali.wangdashe.top/Article/details/gtkkqjitqg.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinqigfzy.top/Article/details/gtnbhwkyel.html

Go:   go f()
来源：http://dali.andypj.xyz/Article/details/gtgjcmcebf.html

Ruby: Thread.new { f }
来源：http://dali.cashguo.top/Article/details/gtrgttdakt.html

C#:   Task.Run(() => F());
来源：http://dali.hywenlv.cn/Article/details/gtszpcetlh.html

[O02] 使用线程池
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpsxknfpf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gaohongyu789.top/Article/details/gtgcxcxdlh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jqgfzy.top/Article/details/gtwltvvvhi.html

JS:   // worker_threads 线程池
来源：http://dali.sxryk.cn/Article/details/gtqunrmrjd.html

TS:   // worker_threads 线程池
来源：http://dali.mhx1999.top/Article/details/gtdhofgwfm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.kuanghao11.cn/Article/details/gtxnjzdfkg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zycfv.cn/Article/details/gtfaxfebvz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zycfv.cn/Article/details/gtfevyppgi.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ybcxt.top/Article/details/gtpopxdoxa.html

[O03] 加锁保护共享数据
来源：http://dali.hysaishi.cn/Article/details/gtacvevhsh.html

Py:   with lock: shared += 1
来源：http://dali.cheryme.top/Article/details/gttezphgoc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yuxming.cn/Article/details/gtvbousfsv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cucudq.cn/Article/details/gtamsvqznf.html

TS:   // 同 JS
来源：http://dali.chenzaomai.com/Article/details/gtjumonboq.html

Java: synchronized (this) { shared++; }
来源：http://dali.pycfn.com/Article/details/gtybxmpowm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.316326.xyz/Article/details/gtcfbptbtk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.sweek.top/Article/details/gtxoaehumo.html

C#:   lock (gate) { shared++; }
来源：http://dali.yangfankeji.com/Article/details/gtvnxuspxm.html

[O04] 定义异步函数并等待
来源：http://dali.sxryk.cn/Article/details/gtlqvdvkkf.html

Py:   async def f():⏎    await g()
来源：http://dali.xinyue.icu/Article/details/gtzrqikokk.html


<!-- 参考信息 -->