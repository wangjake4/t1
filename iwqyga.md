代发 wailian999

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yj202588.top/Article/details/gteoenowet.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yongpay.top/Article/details/gtlhougtrg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.meibo888.top/Article/details/gtrqpbqgnd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xziqi.cn/Article/details/gtuzsqmvqo.html

Go:   encoding/gob
来源：http://dali.xziqi.cn/Article/details/gtmodcsdwc.html

Ruby: Marshal.dump(obj)
来源：http://dali.zycfv.cn/Article/details/gtctjbkena.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shangyingyoupin.top/Article/details/gtsenhajoh.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gteuqkibfv.html

L. 网络请求
来源：http://dali.chenlongwang.top/Article/details/gthjdrhqbu.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtxetavgsl.html

[L01] 发送 GET 请求
来源：http://dali.iojbl.cn/Article/details/gtoxdwnrlk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj20258.top/Article/details/gtekavdcto.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sweek.top/Article/details/gtcujyepjs.html

JS:   await fetch(url)
来源：http://dali.birdmap.top/Article/details/gtsdgierya.html

TS:   await fetch(url)
来源：http://dali.havefunace.top/Article/details/gtjjkdlbwe.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.nanxinkj.top/Article/details/gtixbtxkuu.html

Go:   resp, err := http.Get(url)
来源：http://dali.aibaodan.cn/Article/details/gtsvvjtosx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.daxiang520.top/Article/details/gtqecfqwwi.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.iojbl.cn/Article/details/gtllcctttc.html

[L02] 发送 POST JSON
来源：http://dali.wangshuangyany.cn/Article/details/gtdbgwwdfz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jqgufenzy.top/Article/details/gtjfqcsplq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sxryk.cn/Article/details/gtnxzvuuwa.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yonumen.top/Article/details/gtzfmlxjxj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shuidangran.top/Article/details/gtwhcquuan.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ppjwa.cn/Article/details/gtdvlxvggv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shangyingyoupin.top/Article/details/gtkvlejkyn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinghuilouyu.cn/Article/details/gtzfzmyqmy.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtvlesawby.html

[L03] 设置自定义请求头
来源：http://dali.chenjidiqi.icu/Article/details/gtmvmfaezy.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.9152youxi.cn/Article/details/gtnklwhjhj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.bjfxy.top/Article/details/gtgfwtaqmh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.bjfxy.top/Article/details/gtwvikubsz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ppjwa.cn/Article/details/gtnnzmjbsu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.kuanghao11.cn/Article/details/gtkojmjaoj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.aizwys.cn/Article/details/gtfluufuut.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.dashuyun.cn/Article/details/gtkodphvxq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gaohongyu789.top/Article/details/gtszgcikqf.html

[L04] 设置超时
来源：http://dali.ehwqpu.com/Article/details/gtakefbyiv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenjidiqi.icu/Article/details/gtkomqoyiu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hywenlv.cn/Article/details/gthnakfykf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dianchejie.cn/Article/details/gtxdmugntb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ppjwa.cn/Article/details/gtethsjrol.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xylfe.cn/Article/details/gtillpkbje.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.chenlongwang.top/Article/details/gtefbrvfzq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.9152youxi.cn/Article/details/gtlatfdlbl.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yueranfly.top/Article/details/gtykpuohtj.html

[L05] 上传文件（multipart）
来源：http://dali.jiagoushi.top/Article/details/gtntjehzox.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.316326.xyz/Article/details/gthdxqyhkq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrgzsquoj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hywenlv.cn/Article/details/gtwtoeeoyr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.tian-w.cn/Article/details/gtfdrzwoce.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.c1oappe.top/Article/details/gtyswyiavu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.0kj1m.cn/Article/details/gtutkhbhxa.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.snrcjt.cn/Article/details/gtxttbyqlz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.mhx1999.top/Article/details/gtrcozuggs.html

[L06] 解析响应为 JSON
来源：http://dali.dianchejie.cn/Article/details/gtvqnltjaw.html

Py:   resp.json()
来源：http://dali.meibo888.top/Article/details/gtqbuetphe.html

PHP:  json_decode($body, true);
来源：http://dali.zhoulong.xyz/Article/details/gtdlzrukuq.html

JS:   await resp.json()
来源：http://dali.feifeiyinyue.top/Article/details/gtltrjfugh.html

TS:   await resp.json()
来源：http://dali.fengsongda.top/Article/details/gtyrgesenr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenlongwang.top/Article/details/gtrwpglnwh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jiagoushi.top/Article/details/gtcsvbvijh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jqgufenzy.top/Article/details/gtwzevyxqy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yuanzhike.top/Article/details/gtgklxspkg.html

[L07] 处理 HTTP 状态码
来源：http://dali.xinyue.icu/Article/details/gtgzeuzbjg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.aizwys.cn/Article/details/gtkjpsezex.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sxryk.cn/Article/details/gtlnsedigk.html

JS:   resp.ok;  resp.status
来源：http://dali.ydzc1.top/Article/details/gthsdyflrh.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gtjcwcouva.html

Java: resp.statusCode()
来源：http://dali.smart0.xyz/Article/details/gtjoqvnbne.html

Go:   resp.StatusCode
来源：http://dali.fzhhl.top/Article/details/gtnolefwmk.html

Ruby: resp.code.to_i
来源：http://dali.yongpay.top/Article/details/gtvqsztzpm.html

C#:   (int)resp.StatusCode
来源：http://dali.wangshuangyany.cn/Article/details/gtgifeyjyx.html

[L08] 并发请求多个地址
来源：http://dali.fzhhl.top/Article/details/gttixgpfwa.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sweek.top/Article/details/gtdmcxjmfy.html

PHP:  curl_multi_init() 系列
来源：http://dali.hywenlv.cn/Article/details/gtxyabcehg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gotoacloud.top/Article/details/gtaxoxvrou.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigufen.top/Article/details/gtkmxmradc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xziqi.cn/Article/details/gtexcyecum.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.nanxinkj.top/Article/details/gtjgsbplsv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.dashuyun.cn/Article/details/gtfsihrrui.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yonumen.top/Article/details/gtvivclhfm.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtgxkghvom.html

M. 命令行 / 进程 / 环境
来源：http://dali.feifeiyinyue.top/Article/details/gtdolzstmx.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtlclmzsit.html

[M01] 读取命令行参数
来源：http://dali.c1oappe.top/Article/details/gtjecmanve.html

Py:   sys.argv[1:]
来源：http://dali.hnxiangtu.top/Article/details/gttnmcuwnt.html

PHP:  $argv;  $argc;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkmqmkpbe.html

JS:   process.argv.slice(2)
来源：http://dali.zycfv.cn/Article/details/gtmxulqlaa.html

TS:   process.argv.slice(2)
来源：http://dali.yonumen.top/Article/details/gtfwxuoamj.html

Java: args 数组（main 方法参数）
来源：http://dali.iojbl.cn/Article/details/gtvmzpohqd.html

Go:   os.Args[1:]
来源：http://dali.pycfn.com/Article/details/gtteklsqdp.html

Ruby: ARGV
来源：http://dali.ppjwa.cn/Article/details/gtxexgzhkv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zycfv.cn/Article/details/gtmyyfkyeh.html

[M02] 读取环境变量
来源：http://dali.wangshuangyany.cn/Article/details/gtygbgkeni.html

Py:   os.environ.get("HOME")
来源：http://dali.zhengqikj.top/Article/details/gtqhruxhqk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtufjztvqt.html

JS:   process.env.HOME
来源：http://dali.zhixingplan.top/Article/details/gtqmzkeawo.html

TS:   process.env.HOME
来源：http://dali.zhiwuduotai.top/Article/details/gtiqzpdqbq.html

Java: System.getenv("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmqjsrijl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.nwbrower.top/Article/details/gttceihids.html

Ruby: ENV["HOME"]
来源：http://dali.ybcxt.top/Article/details/gtngkqalej.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tianlin.xyz/Article/details/gtvpohfcse.html

[M03] 执行外部命令
来源：http://dali.hammf.cn/Article/details/gtwyvxgyej.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xziqi.cn/Article/details/gtpcjczaan.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.feifeiyinyue.top/Article/details/gthulizgub.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xziqi.cn/Article/details/gtashxxkzf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gzhubu.top/Article/details/gtafftossh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ivvv.top/Article/details/gtjainkuuj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttxecjujc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgfhelbns.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hnqzz.top/Article/details/gtgtpoxkue.html

[M04] 获取当前工作目录
来源：http://dali.chenlongwang.top/Article/details/gthoebfyuv.html

Py:   os.getcwd()
来源：http://dali.yj20258.top/Article/details/gtmhcgnlyn.html

PHP:  getcwd();
来源：http://dali.tian-w.cn/Article/details/gtqgdellka.html

JS:   process.cwd()
来源：http://dali.tian-w.cn/Article/details/gtqapcflan.html

TS:   process.cwd()
来源：http://dali.gotoacloud.top/Article/details/gtxpezpccn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.meibo888.top/Article/details/gtafqzxscb.html

Go:   os.Getwd()
来源：http://dali.zhoulong.xyz/Article/details/gtspemfmfo.html

Ruby: Dir.pwd
来源：http://dali.sxryk.cn/Article/details/gtfuuvvobd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenzaomai.com/Article/details/gthipahzkk.html

[M05] 设置退出码
来源：http://dali.jyoumei.cn/Article/details/gtzbdyeeko.html

Py:   sys.exit(1)
来源：http://dali.iojbl.cn/Article/details/gtbhqkvfcd.html

PHP:  exit(1);
来源：http://dali.cqqwz.cn/Article/details/gtamzcbgta.html

JS:   process.exit(1)
来源：http://dali.sweek.top/Article/details/gtmozgpdyb.html

TS:   process.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqlctwgoh.html

Java: System.exit(1)
来源：http://dali.pycfn.com/Article/details/gtqjmdpydk.html

Go:   os.Exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtabngxmsf.html

Ruby: exit 1
来源：http://dali.ydzc1.top/Article/details/gtemhrzybz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yuanzhike.top/Article/details/gtoafckkjt.html

[M06] 向标准错误输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtccrhfzkv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.smart0.xyz/Article/details/gtqcuipfgz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sufxvd.cn/Article/details/gtchmdcqxj.html

JS:   console.error("err")
来源：http://dali.fengsongda.top/Article/details/gtkznpbaxy.html

TS:   console.error("err")
来源：http://dali.yonumen.top/Article/details/gtiijhpaww.html

Java: System.err.println("err")
来源：http://dali.hammf.cn/Article/details/gtwfbzezax.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gaohongyu789.top/Article/details/gtvxydygkz.html

Ruby: warn "err"
来源：http://dali.shanyushiyangtech.top/Article/details/gtikjpnmwm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gzhubu.top/Article/details/gtlfikwtyw.html

[M07] 判断是否为主入口
来源：http://dali.sxryk.cn/Article/details/gttpvtgpia.html

Py:   if __name__ == "__main__":
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfchnxong.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xylfe.cn/Article/details/gteflekswb.html

JS:   require.main === module
来源：http://dali.xinyue.icu/Article/details/gtbbheqafe.html

TS:   require.main === module
来源：http://dali.zhengqikj.top/Article/details/gtekiuvhuc.html

Java: public static void main(String[] args)
来源：http://dali.havefunace.top/Article/details/gtvjtcxqgo.html

Go:   func main()
来源：http://dali.daria6918.cn/Article/details/gtgprecayv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jianghu66.top/Article/details/gtfpraoyhf.html

C#:   static void Main(string[] args)
来源：http://dali.zhiwuduotai.top/Article/details/gtmluwixxa.html

[M08] 获取系统与运行时信息
来源：http://dali.ivvv.top/Article/details/gtmgdpeerf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.pycfn.com/Article/details/gtaacvxtle.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgdkegkop.html

JS:   process.platform;  process.version
来源：http://dali.yanxiufei.cn/Article/details/gtddefsekk.html

TS:   process.platform;  process.version
来源：http://dali.wangdashe.top/Article/details/gtpzrmcwsp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jqgufenzy.top/Article/details/gtfxjdcmlp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yueranfly.top/Article/details/gttbdenxqk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hywenlv.cn/Article/details/gtmflsblmy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yj20258.top/Article/details/gtnkllhbjo.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtbfsprber.html

N. 数据结构与算法
来源：http://dali.chenjidiqi.icu/Article/details/gtrhbsxixw.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtiyzxjtme.html

[N01] 二分查找（有序数组）
来源：http://dali.wangdashe.top/Article/details/gtnrikmdyq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.guannengcc.top/Article/details/gthrnavftl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shangyingyoupin.top/Article/details/gtbssmxlkp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aibaodan.cn/Article/details/gtaqtdgkmv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yvedp.cn/Article/details/gttjyuoamw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtnqzmgilr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ivvv.top/Article/details/gtahfxjeoi.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shzxlz.cn/Article/details/gtfuugwdgm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtybuhmscg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.vqdsnc.cn/Article/details/gtlrtodwby.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jyoumei.cn/Article/details/gtngxmixte.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.haohaochexian.top/Article/details/gteigyaegk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.smart0.xyz/Article/details/gtatrmmnue.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.mhx1999.top/Article/details/gtbjkhppro.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.nanxuanxn.top/Article/details/gtuxjcmune.html

Go:   slices.Sort(arr)
来源：http://dali.fengsongda.top/Article/details/gtllxjwuko.html

Ruby: arr.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gtohxrfybh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.fzhhl.top/Article/details/gtevjddogs.html

[N03] 快速排序（分治示例）
来源：http://dali.havefunace.top/Article/details/gtnuoeyhtd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.redwolf501.top/Article/details/gtqzdtlqxo.html

PHP:  // 递归实现，或用 usort
来源：http://dali.pengpengdd.cyou/Article/details/gtgqzfnppg.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlflwelzb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hysaishi.cn/Article/details/gttklaqzec.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ybcxt.top/Article/details/gtlxwyifdo.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gzhubu.top/Article/details/gtyfugufqq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zdqjudy.top/Article/details/gtenmasspa.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.wangshuangyany.cn/Article/details/gtuxrpgfqr.html

[N04] 斐波那契数列
来源：http://dali.daria6918.cn/Article/details/gtmswcvaps.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttzrcwkrn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ppjwa.cn/Article/details/gttxxvuaey.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gzhubu.top/Article/details/gtsbohrjfi.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gtqhgjpbxx.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.wangshuangyany.cn/Article/details/gtujobfpcm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.wangshuangyany.cn/Article/details/gtvxdoqran.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.pycfn.com/Article/details/gtlbfallje.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cdnleiting.top/Article/details/gtttnaxiib.html

[N05] 最大公约数
来源：http://dali.shzxlz.cn/Article/details/gthxkmvgsc.html

Py:   math.gcd(a, b)
来源：http://dali.316326.xyz/Article/details/gtlpbancba.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ppjwa.cn/Article/details/gtyuzqaplf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cdnleiting.top/Article/details/gtkdcnaaeg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sxryk.cn/Article/details/gtxerblctg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrewjziip.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jyoumei.cn/Article/details/gtjmozyusq.html

Ruby: a.gcd(b)
来源：http://dali.kuanghao11.cn/Article/details/gtxeorabjh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gogol.net.cn/Article/details/gtznadswsr.html

[N06] 判断回文字符串
来源：http://dali.svipenyu.cn/Article/details/gtvsilybwe.html

Py:   s == s[::-1]
来源：http://dali.jiagoushi.top/Article/details/gtsobiylwd.html

PHP:  $s === strrev($s);
来源：http://dali.nwbrower.top/Article/details/gtkdbyoooj.html

JS:   s === [...s].reverse().join("")
来源：http://dali.vqdsnc.cn/Article/details/gtlnvjczew.html

TS:   s === [...s].reverse().join("")
来源：http://dali.daxiang520.top/Article/details/gtvlzzxcpu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ppjwa.cn/Article/details/gtvmlfncvq.html

Go:   // 双指针从两端比较
来源：http://dali.yongpay.top/Article/details/gtfgfhdxgx.html

Ruby: s == s.reverse
来源：http://dali.meibo888.top/Article/details/gtnmljwvhn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.redwolf501.top/Article/details/gtttlgkgfq.html

[N07] 两数之和（返回下标）
来源：http://dali.nwbrower.top/Article/details/gtzynewarj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xylfe.cn/Article/details/gtldzjfmbz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hnqzz.top/Article/details/gtzwgckdwc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhoulong.xyz/Article/details/gtkudkjpgj.html

TS:   // 手写 Map<string, number>
来源：http://dali.chenzaomai.com/Article/details/gtijeluqbp.html

Java: // 手写 HashMap
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbqyllmfu.html

Go:   // 手写 map[int]int
来源：http://dali.jqgufenzy.top/Article/details/gtpqthgwdc.html

Ruby: // 手写 Hash
来源：http://dali.xylfe.cn/Article/details/gtpfvqxfnx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhongyouzk.top/Article/details/gtsgzxmkyb.html

[N08] 生成全排列
来源：http://dali.yuanzhike.top/Article/details/gtjruqkyfo.html

Py:   itertools.permutations(arr)
来源：http://dali.havefunace.top/Article/details/gtwwzairap.html

PHP:  // 手写递归交换
来源：http://dali.ivvv.top/Article/details/gtlnnwqzca.html

JS:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gtrfrzfxrx.html

TS:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gtfppskcni.html

Java: // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gttsyvyctu.html

Go:   // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gtvqrprnge.html

Ruby: arr.permutation.to_a
来源：http://dali.cdnleiting.top/Article/details/gtdycxheai.html

C#:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gtpsgrbtkg.html

[N09] 栈与队列
来源：http://dali.redwolf501.top/Article/details/gtrkwlocrc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.316326.xyz/Article/details/gtfjumrnls.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xylfe.cn/Article/details/gtfahywwap.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gtyrkxuhvx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shangyingyoupin.top/Article/details/gtnngghfbq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shanyushiyangtech.top/Article/details/gttnbronhi.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shanyushiyangtech.top/Article/details/gtwcnzysxi.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xuanzx.com/Article/details/gtayjofyqc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yuxming.cn/Article/details/gtnwlwcnbm.html

[N10] 链表节点定义
来源：http://dali.jqgufenzy.top/Article/details/gtczqtavbv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.0kj1m.cn/Article/details/gtkmhmicau.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.c1oappe.top/Article/details/gtlfcbvhfo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xylfe.cn/Article/details/gtcdpwoaae.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gogol.net.cn/Article/details/gtvdqpsqdy.html

Java: class Node { int v; Node next; }
来源：http://dali.tanke756.top/Article/details/gtpqrtdjeq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zdqjudy.top/Article/details/gtsibhqlfg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xziqi.cn/Article/details/gtahnjjlux.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.fengsongda.top/Article/details/gtatuupkxw.html

[N11] 二叉树中序遍历
来源：http://dali.birdmap.top/Article/details/gtrrumhcpo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.nwbrower.top/Article/details/gtsyixnjht.html

PHP:  // 手写递归函数
来源：http://dali.yongpay.top/Article/details/gthkdwkgne.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yanxiufei.cn/Article/details/gtrdyeajis.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xuetiantiany.cn/Article/details/gtrbzpakfp.html

Java: // 手写递归
来源：http://dali.chenzaomai.com/Article/details/gtyhtxhvck.html

Go:   // 手写递归
来源：http://dali.nanxuanxn.top/Article/details/gteaavjpnq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gtaxrduwqp.html

C#:   // 手写递归
来源：http://dali.c1oappe.top/Article/details/gtrisjwchn.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.aibaodan.cn/Article/details/gtgsbfvayb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.feifeiyinyue.top/Article/details/gtlpkcraxw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtajepazxc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxuanxn.top/Article/details/gtthhhbhjh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cheryme.top/Article/details/gtisgjgoxs.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fengsongda.top/Article/details/gtodzqlkon.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyxeihrqd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gaohongyu789.top/Article/details/gtbnmwweiy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guowangkeji.top/Article/details/gtgnhazerc.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdcxapxvx.html

O. 并发与异步
来源：http://dali.quarkkingdee.top/Article/details/gtcbjaqrwr.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtsupcpkkb.html

[O01] 启动一个线程
来源：http://dali.jqgfzy.top/Article/details/gtnnxgwjac.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shzxlz.cn/Article/details/gtfhgtreqr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yj20258.top/Article/details/gtmdwmnhpj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.haohaochexian.top/Article/details/gtosrcvcay.html

TS:   // 同 JS
来源：http://dali.jlsjyb.cn/Article/details/gtfowzyurt.html

Java: new Thread(() -> f()).start()
来源：http://dali.chenlongwang.top/Article/details/gtwaudaqhh.html

Go:   go f()
来源：http://dali.nanxuanxn.top/Article/details/gterknsdlz.html

Ruby: Thread.new { f }
来源：http://dali.daxiang520.top/Article/details/gtrgrtmzoi.html

C#:   Task.Run(() => F());
来源：http://dali.zhixingplan.top/Article/details/gtmbdymulz.html

[O02] 使用线程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfepkqgqr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gzhubu.top/Article/details/gtzlpnvtbf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhoulong.xyz/Article/details/gtxclewqrl.html

JS:   // worker_threads 线程池
来源：http://dali.jqgfzy.top/Article/details/gtezhhvwrq.html

TS:   // worker_threads 线程池
来源：http://dali.yangfankeji.com/Article/details/gtqbbcjmdz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.bjfxy.top/Article/details/gtclmceqiv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gogol.net.cn/Article/details/gtdyrelkaa.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcvslhobi.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.sweek.top/Article/details/gtukudetin.html

[O03] 加锁保护共享数据
来源：http://dali.yj20258888.top/Article/details/gthkuqvslu.html

Py:   with lock: shared += 1
来源：http://dali.sufxvd.cn/Article/details/gtwojqscae.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.pengpengdd.cyou/Article/details/gtvcrbxowz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.daxiang520.top/Article/details/gtslhimyit.html

TS:   // 同 JS
来源：http://dali.jinqigufen.top/Article/details/gtjsdobcde.html

Java: synchronized (this) { shared++; }
来源：http://dali.bjfxy.top/Article/details/gtwogvhumw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.chenzaomai.com/Article/details/gtkneejnwi.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gtyyaamvmu.html

C#:   lock (gate) { shared++; }
来源：http://dali.fengsongda.top/Article/details/gtdzbqwxuq.html

[O04] 定义异步函数并等待
来源：http://dali.xinyue.icu/Article/details/gtaufyvpfa.html

Py:   async def f():⏎    await g()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyuuqllxo.html


<!-- 参考信息 -->