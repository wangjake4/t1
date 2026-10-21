代发 wailian999

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cashguo.top/Article/details/gtkisistfw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gaohongyu789.top/Article/details/gteypgmywv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.aibaodan.cn/Article/details/gtaozawxgq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yonumen.top/Article/details/gtrogtavvy.html

Go:   encoding/gob
来源：http://dali.jinqigufen.top/Article/details/gtsjaiamfi.html

Ruby: Marshal.dump(obj)
来源：http://dali.nanxinkj.top/Article/details/gtxqtimzyb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shuidangran.top/Article/details/gtyxcmhzty.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtbadeslzt.html

L. 网络请求
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtijqdkkcu.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtbtgrucex.html

[L01] 发送 GET 请求
来源：http://dali.9152youxi.cn/Article/details/gthgjzmypw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.snrcjt.cn/Article/details/gtvynfkzaa.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hongshengwenyu.top/Article/details/gttwphimch.html

JS:   await fetch(url)
来源：http://dali.yvedp.cn/Article/details/gtonfvkhdl.html

TS:   await fetch(url)
来源：http://dali.jqgfzy.top/Article/details/gtqpgohnwl.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenzaomai.com/Article/details/gtaddtfotw.html

Go:   resp, err := http.Get(url)
来源：http://dali.nwbrower.top/Article/details/gttizxnfga.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yvedp.cn/Article/details/gtappendpv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cqqwz.cn/Article/details/gtdxtrjosk.html

[L02] 发送 POST JSON
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzkcstpcl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.wangdashe.top/Article/details/gtnimsxuqz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ehwqpu.com/Article/details/gtbtdgqxya.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.havefunace.top/Article/details/gtrgvatecp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hongshengwenyu.top/Article/details/gttoxhhfdo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gaohongyu789.top/Article/details/gturjgdhle.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.tanke756.top/Article/details/gthsdiwulx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.pengpengdd.cyou/Article/details/gtyuswyhmt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jqgufenzy.top/Article/details/gtjuixjxaf.html

[L03] 设置自定义请求头
来源：http://dali.redwolf501.top/Article/details/gtrzaielap.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jqgfzy.top/Article/details/gthdrkibwx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.aizwys.cn/Article/details/gtlxkvsifi.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dianchejie.cn/Article/details/gtsgbupqfn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shzxlz.cn/Article/details/gtcrpkvbyw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jyoumei.cn/Article/details/gteacbieit.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.smart0.xyz/Article/details/gtozormjgp.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jlsjyb.cn/Article/details/gtuyywwmcc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhiwuduotai.top/Article/details/gtubwzrsml.html

[L04] 设置超时
来源：http://dali.gzhubu.top/Article/details/gtlmmnzyyt.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yj20258888.top/Article/details/gtfwhsmsux.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.dashuyun.cn/Article/details/gtpbjovoyy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.vqdsnc.cn/Article/details/gtckrfbawp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangdashe.top/Article/details/gtycllnzjz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shanyushiyangtech.top/Article/details/gtxbqyrakm.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.daxiang520.top/Article/details/gtadurcqij.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xziqi.cn/Article/details/gtczjsngjk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.nanxinkj.top/Article/details/gtyaaokmtn.html

[L05] 上传文件（multipart）
来源：http://dali.yongpay.top/Article/details/gtfaxtxndi.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yuanzhike.top/Article/details/gtvjuyvcba.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zycfv.cn/Article/details/gtwdyqczis.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtomwoxmvx.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.daria6918.cn/Article/details/gtexfudbxn.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.vqdsnc.cn/Article/details/gtnzogrbaw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shzxlz.cn/Article/details/gtwvkhtnad.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.wangshuangyany.cn/Article/details/gtpwopkfat.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtutbgrgbq.html

[L06] 解析响应为 JSON
来源：http://dali.meibo888.top/Article/details/gtoilgiejd.html

Py:   resp.json()
来源：http://dali.sufxvd.cn/Article/details/gtyayermlh.html

PHP:  json_decode($body, true);
来源：http://dali.kuanghao11.cn/Article/details/gtdlhzpxcq.html

JS:   await resp.json()
来源：http://dali.zhoulong.xyz/Article/details/gtrwomzwqi.html

TS:   await resp.json()
来源：http://dali.fzhhl.top/Article/details/gtypjxmtcr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj202588.top/Article/details/gtxdnwdzlc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.kuanghao11.cn/Article/details/gtrfowfeti.html

Ruby: JSON.parse(resp.body)
来源：http://dali.haohaochexian.top/Article/details/gtcrcdjkdy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.wangdashe.top/Article/details/gtlejugyrm.html

[L07] 处理 HTTP 状态码
来源：http://dali.hfpthk.cn/Article/details/gthkqywpkp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.dianchejie.cn/Article/details/gtlopaammv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shangyingyoupin.top/Article/details/gtruylhaiw.html

JS:   resp.ok;  resp.status
来源：http://dali.daria6918.cn/Article/details/gtngzrekhl.html

TS:   resp.ok;  resp.status
来源：http://dali.tian-w.cn/Article/details/gtustuedvr.html

Java: resp.statusCode()
来源：http://dali.xziqi.cn/Article/details/gtxmzczvya.html

Go:   resp.StatusCode
来源：http://dali.zhoulong.xyz/Article/details/gtmrtghpzj.html

Ruby: resp.code.to_i
来源：http://dali.bjfxy.top/Article/details/gtnqhqtyao.html

C#:   (int)resp.StatusCode
来源：http://dali.hammf.cn/Article/details/gtgwynyovo.html

[L08] 并发请求多个地址
来源：http://dali.yanxiufei.cn/Article/details/gtgfvezkuu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.guowangkeji.top/Article/details/gtcketwogz.html

PHP:  curl_multi_init() 系列
来源：http://dali.pengpengdd.cyou/Article/details/gtqjmxuizf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jlsjyb.cn/Article/details/gtbhdrsttg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sysykeji.top/Article/details/gtmfeictsn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cheryme.top/Article/details/gtcpazesec.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.pengpengdd.cyou/Article/details/gtwalilnos.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.vqdsnc.cn/Article/details/gtsgenedhm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzlsooqwl.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtawofsfny.html

M. 命令行 / 进程 / 环境
来源：http://dali.nanxuanxn.top/Article/details/gtpqfkusvl.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtobybtchg.html

[M01] 读取命令行参数
来源：http://dali.havefunace.top/Article/details/gtrpoaffjk.html

Py:   sys.argv[1:]
来源：http://dali.chenlongwang.top/Article/details/gtwszvmwej.html

PHP:  $argv;  $argc;
来源：http://dali.shangyingyoupin.top/Article/details/gtrbbkvwdc.html

JS:   process.argv.slice(2)
来源：http://dali.yuanzhike.top/Article/details/gtbpsjalbh.html

TS:   process.argv.slice(2)
来源：http://dali.wangshuangyany.cn/Article/details/gthqqsbwgb.html

Java: args 数组（main 方法参数）
来源：http://dali.yj202588.top/Article/details/gtiifjucga.html

Go:   os.Args[1:]
来源：http://dali.jqgufenzy.top/Article/details/gtrumhtdas.html

Ruby: ARGV
来源：http://dali.guannengcc.top/Article/details/gtqadbzjqx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ehwqpu.com/Article/details/gtndxqwfac.html

[M02] 读取环境变量
来源：http://dali.9152youxi.cn/Article/details/gtbuouizwa.html

Py:   os.environ.get("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gtqvlkdixw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.pycfn.com/Article/details/gtblpbpsfk.html

JS:   process.env.HOME
来源：http://dali.iojbl.cn/Article/details/gtaapudqox.html

TS:   process.env.HOME
来源：http://dali.hfpthk.cn/Article/details/gtcticrfod.html

Java: System.getenv("HOME")
来源：http://dali.shzxlz.cn/Article/details/gtdmpcrznm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.tianlin.xyz/Article/details/gtxnjwwvkv.html

Ruby: ENV["HOME"]
来源：http://dali.jiagoushi.top/Article/details/gtigfvowuo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.fzhhl.top/Article/details/gtmzlhecqn.html

[M03] 执行外部命令
来源：http://dali.jqgufenzy.top/Article/details/gtkoucmkvl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhiwuduotai.top/Article/details/gttpodasim.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinqigfzy.top/Article/details/gtlogznxij.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xinyue.icu/Article/details/gtghrwqmbs.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xziqi.cn/Article/details/gtmrgfvinw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.dashuyun.cn/Article/details/gtmpndxbmt.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hammf.cn/Article/details/gtdelsdrwy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yj20258.top/Article/details/gtuljaairi.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shangyingyoupin.top/Article/details/gthfqzdoen.html

[M04] 获取当前工作目录
来源：http://dali.chenjidiqi.icu/Article/details/gtnnujvufn.html

Py:   os.getcwd()
来源：http://dali.gaohongyu789.top/Article/details/gtaddsqfon.html

PHP:  getcwd();
来源：http://dali.aibaodan.cn/Article/details/gtojeeqesf.html

JS:   process.cwd()
来源：http://dali.yuanzhike.top/Article/details/gtiprmxkgo.html

TS:   process.cwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpdygvfwd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhixingplan.top/Article/details/gtkmcteebr.html

Go:   os.Getwd()
来源：http://dali.dianchejie.cn/Article/details/gtunwcuuya.html

Ruby: Dir.pwd
来源：http://dali.hywenlv.cn/Article/details/gtmanhffnk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ydzc1.top/Article/details/gtcrxcqhrs.html

[M05] 设置退出码
来源：http://dali.vqdsnc.cn/Article/details/gtjjsgzcoz.html

Py:   sys.exit(1)
来源：http://dali.smart0.xyz/Article/details/gtljjpkhtc.html

PHP:  exit(1);
来源：http://dali.hfpthk.cn/Article/details/gtdhmaopyg.html

JS:   process.exit(1)
来源：http://dali.tanke756.top/Article/details/gtglncdtbo.html

TS:   process.exit(1)
来源：http://dali.meibo888.top/Article/details/gtvkxiamom.html

Java: System.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gtaxuftnme.html

Go:   os.Exit(1)
来源：http://dali.sysykeji.top/Article/details/gtducbwzdk.html

Ruby: exit 1
来源：http://dali.mhx1999.top/Article/details/gtbudreygc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.vqdsnc.cn/Article/details/gtdyfpshdu.html

[M06] 向标准错误输出
来源：http://dali.dashuyun.cn/Article/details/gtweaszbxq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xuetiantiany.cn/Article/details/gttwkngqzr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yvedp.cn/Article/details/gtcthtsydq.html

JS:   console.error("err")
来源：http://dali.dashuyun.cn/Article/details/gtyoemplso.html

TS:   console.error("err")
来源：http://dali.vqdsnc.cn/Article/details/gtrxhpqeib.html

Java: System.err.println("err")
来源：http://dali.zhongyouzk.top/Article/details/gtvxyecmmv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xinyue.icu/Article/details/gtdxzfeuck.html

Ruby: warn "err"
来源：http://dali.wangshuangyany.cn/Article/details/gtzspivbdx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.guowangkeji.top/Article/details/gtseuhlqxc.html

[M07] 判断是否为主入口
来源：http://dali.bjfxy.top/Article/details/gtpaeudqwa.html

Py:   if __name__ == "__main__":
来源：http://dali.nanxinkj.top/Article/details/gtssfjrmnk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdplopfjk.html

JS:   require.main === module
来源：http://dali.zhixingplan.top/Article/details/gtoebixiqr.html

TS:   require.main === module
来源：http://dali.xylfe.cn/Article/details/gtjwqjapkv.html

Java: public static void main(String[] args)
来源：http://dali.fengsongda.top/Article/details/gtjyignrpw.html

Go:   func main()
来源：http://dali.feifeiyinyue.top/Article/details/gtlewdbnvi.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jianghu66.top/Article/details/gtfokwiiqk.html

C#:   static void Main(string[] args)
来源：http://dali.chenjidiqi.icu/Article/details/gtsdetvgvq.html

[M08] 获取系统与运行时信息
来源：http://dali.jqgufenzy.top/Article/details/gtotuegomg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xuanzx.com/Article/details/gtxzopidit.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.redwolf501.top/Article/details/gtxzimbuhl.html

JS:   process.platform;  process.version
来源：http://dali.redwolf501.top/Article/details/gtlkfflmgh.html

TS:   process.platform;  process.version
来源：http://dali.gotoacloud.top/Article/details/gtuqsozbcy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yuxming.cn/Article/details/gtmwsomhqa.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ydzc1.top/Article/details/gtotstjonv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yvedp.cn/Article/details/gtwgeojlzd.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.aibaodan.cn/Article/details/gtglhyqhwj.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtefqiuprz.html

N. 数据结构与算法
来源：http://dali.sysykeji.top/Article/details/gtndiebzew.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gthrqpxrtj.html

[N01] 二分查找（有序数组）
来源：http://dali.9152youxi.cn/Article/details/gtdmztfidq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gtbmozbxqi.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yanxiufei.cn/Article/details/gtnkhoyqmu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pycfn.com/Article/details/gtnvxcfeer.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.9152youxi.cn/Article/details/gtqebebvtl.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.pycfn.com/Article/details/gtzvcsjovy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yongpay.top/Article/details/gtghjwmbhl.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ppjwa.cn/Article/details/gtjykoccvz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ivvv.top/Article/details/gtuwlbbzeo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zycfv.cn/Article/details/gtimbtkntu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zycfv.cn/Article/details/gtttuagffk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gtgosdejjs.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.feifeiyinyue.top/Article/details/gtxmitdzlh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ivvv.top/Article/details/gtrysmgngy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.kuanghao11.cn/Article/details/gtearbjiza.html

Go:   slices.Sort(arr)
来源：http://dali.hywenlv.cn/Article/details/gtqlotfizu.html

Ruby: arr.sort
来源：http://dali.hfpthk.cn/Article/details/gtqqbrfaji.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinyuanbaomall.cn/Article/details/gttsbflffm.html

[N03] 快速排序（分治示例）
来源：http://dali.yueranfly.top/Article/details/gtgiljmxlf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gaohongyu789.top/Article/details/gtkcqjworw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.daria6918.cn/Article/details/gtczaltvhm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hysaishi.cn/Article/details/gtfpdgzzps.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jianghu66.top/Article/details/gtjfzlbjcf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gtntesuktm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenlongwang.top/Article/details/gtlqybzaim.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zdqjudy.top/Article/details/gthqhgptjw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gaohongyu789.top/Article/details/gtydrqlbfw.html

[N04] 斐波那契数列
来源：http://dali.feifeiyinyue.top/Article/details/gtbgrmvlcb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ivvv.top/Article/details/gtivoqqbva.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.nwbrower.top/Article/details/gtwhphyjme.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daria6918.cn/Article/details/gtxesrgcne.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xziqi.cn/Article/details/gtqbztvhzl.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinqigfzy.top/Article/details/gtxypfsssm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.wangshuangyany.cn/Article/details/gtlezhwyqr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yanxiufei.cn/Article/details/gtpmpnphfy.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.pycfn.com/Article/details/gtryaawtul.html

[N05] 最大公约数
来源：http://dali.aibaodan.cn/Article/details/gtptpistft.html

Py:   math.gcd(a, b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtppphllhj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zycfv.cn/Article/details/gtavjrqpgj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yongpay.top/Article/details/gtkadfrvqj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sufxvd.cn/Article/details/gtmfabkord.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xuanzx.com/Article/details/gtirhrykwd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.tanke756.top/Article/details/gtwwjteozz.html

Ruby: a.gcd(b)
来源：http://dali.birdmap.top/Article/details/gtthikgimu.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jianghu66.top/Article/details/gteetfxrhd.html

[N06] 判断回文字符串
来源：http://dali.jlsjyb.cn/Article/details/gtstvabsyb.html

Py:   s == s[::-1]
来源：http://dali.hfpthk.cn/Article/details/gttqigrkgk.html

PHP:  $s === strrev($s);
来源：http://dali.yueranfly.top/Article/details/gttreklqbj.html

JS:   s === [...s].reverse().join("")
来源：http://dali.vqdsnc.cn/Article/details/gtxwctdtht.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gtxongtjch.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jqgufenzy.top/Article/details/gtjggqwojx.html

Go:   // 双指针从两端比较
来源：http://dali.9152youxi.cn/Article/details/gtllpwmqfg.html

Ruby: s == s.reverse
来源：http://dali.jinqigfzy.top/Article/details/gtnvfssdvp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.guannengcc.top/Article/details/gtgbhvjprb.html

[N07] 两数之和（返回下标）
来源：http://dali.xuetiantiany.cn/Article/details/gtiwlqlqrw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhoulong.xyz/Article/details/gthzppkyaa.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ivvv.top/Article/details/gtnmoxciho.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.fzhhl.top/Article/details/gtzpzichzk.html

TS:   // 手写 Map<string, number>
来源：http://dali.nanxinkj.top/Article/details/gtngighacq.html

Java: // 手写 HashMap
来源：http://dali.smart0.xyz/Article/details/gtmkfefrpl.html

Go:   // 手写 map[int]int
来源：http://dali.gotoacloud.top/Article/details/gtcgkwfyoo.html

Ruby: // 手写 Hash
来源：http://dali.guowangkeji.top/Article/details/gtdtsjzjbn.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yueranfly.top/Article/details/gtktvzseqi.html

[N08] 生成全排列
来源：http://dali.vqdsnc.cn/Article/details/gtfoimzgvb.html

Py:   itertools.permutations(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtfgdupbme.html

PHP:  // 手写递归交换
来源：http://dali.xylfe.cn/Article/details/gtlbedkmsw.html

JS:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gtpdkateus.html

TS:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gtylkrrepn.html

Java: // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtbpobmdxx.html

Go:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtickecoqw.html

Ruby: arr.permutation.to_a
来源：http://dali.zycfv.cn/Article/details/gtegpkpter.html

C#:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtwovgkrxs.html

[N09] 栈与队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttihgcgzw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sxryk.cn/Article/details/gtrqehaxvo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gtjavczluz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cashguo.top/Article/details/gtwegmctlw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmbqwotxi.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ybcxt.top/Article/details/gtzddmwnbm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinqigufen.top/Article/details/gthhomurcl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hywenlv.cn/Article/details/gtgoflmrtk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.birdmap.top/Article/details/gtoaondlrf.html

[N10] 链表节点定义
来源：http://dali.yuxming.cn/Article/details/gthkjylxaq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jqgfzy.top/Article/details/gtpjgjzwzx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.guannengcc.top/Article/details/gtmguoychv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.daxiang520.top/Article/details/gteeeavpsc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.c1oappe.top/Article/details/gtqzvlgnyx.html

Java: class Node { int v; Node next; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwabyzcwv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.aizwys.cn/Article/details/gttfuwvrvu.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cqqwz.cn/Article/details/gtqozafcuh.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hywenlv.cn/Article/details/gtdoblhntk.html

[N11] 二叉树中序遍历
来源：http://dali.quarkkingdee.top/Article/details/gteyxnvptt.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhengqikj.top/Article/details/gtofrfhfll.html

PHP:  // 手写递归函数
来源：http://dali.9152youxi.cn/Article/details/gtgucureqe.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhoulong.xyz/Article/details/gtakunubzc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jianghu66.top/Article/details/gtydaiztqr.html

Java: // 手写递归
来源：http://dali.ybcxt.top/Article/details/gtnzuibivz.html

Go:   // 手写递归
来源：http://dali.zhengqikj.top/Article/details/gtmyopyhpf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sweek.top/Article/details/gtnmpvmgjb.html

C#:   // 手写递归
来源：http://dali.xylfe.cn/Article/details/gtssxdautd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gtliepbpju.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.feifeiyinyue.top/Article/details/gtbvjgksex.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yj202588.top/Article/details/gtutepqrjy.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxuanxn.top/Article/details/gtvkzayixo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tianlin.xyz/Article/details/gthgqppklr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.dashuyun.cn/Article/details/gtwfhjaqir.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.chenjidiqi.icu/Article/details/gtknjidkul.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.c1oappe.top/Article/details/gtydisbvee.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.svipenyu.cn/Article/details/gttuwwiyio.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtosmsdygr.html

O. 并发与异步
来源：http://dali.nwbrower.top/Article/details/gtctewkylh.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtschvluov.html

[O01] 启动一个线程
来源：http://dali.yonumen.top/Article/details/gtqepepfpk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shzxlz.cn/Article/details/gtywnubdtf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hammf.cn/Article/details/gteqovqlfn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.snrcjt.cn/Article/details/gtzsefsbmj.html

TS:   // 同 JS
来源：http://dali.yvedp.cn/Article/details/gtqqchtjoy.html

Java: new Thread(() -> f()).start()
来源：http://dali.smart0.xyz/Article/details/gtwjuqbnqg.html

Go:   go f()
来源：http://dali.daxiang520.top/Article/details/gtwegxqijx.html

Ruby: Thread.new { f }
来源：http://dali.chenzaomai.com/Article/details/gtzhrmjjdy.html

C#:   Task.Run(() => F());
来源：http://dali.xinyue.icu/Article/details/gtarenfvtk.html

[O02] 使用线程池
来源：http://dali.feifeiyinyue.top/Article/details/gtkvqcarlu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gaohongyu789.top/Article/details/gtrpsniyvh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.vqdsnc.cn/Article/details/gtaacpzhqs.html

JS:   // worker_threads 线程池
来源：http://dali.tanke756.top/Article/details/gtyfcoxczc.html

TS:   // worker_threads 线程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjuwbnxpf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpnfbhgbj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.chenjidiqi.icu/Article/details/gtyhmvcgmd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.havefunace.top/Article/details/gtriaxyfki.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hnxiangtu.top/Article/details/gtupcposkq.html

[O03] 加锁保护共享数据
来源：http://dali.yangfankeji.com/Article/details/gtlkltueup.html

Py:   with lock: shared += 1
来源：http://dali.zdqjudy.top/Article/details/gtigcnhyna.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.tianlin.xyz/Article/details/gtdhnpwvcn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.andypj.xyz/Article/details/gtycsqcubh.html

TS:   // 同 JS
来源：http://dali.yj20258.top/Article/details/gtpqlcmahi.html

Java: synchronized (this) { shared++; }
来源：http://dali.gogol.net.cn/Article/details/gtpsanhicw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.316326.xyz/Article/details/gttuhmqfqw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.wangdashe.top/Article/details/gtrhgfkeuv.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhoulong.xyz/Article/details/gtabtvcdau.html

[O04] 定义异步函数并等待
来源：http://dali.ydzc1.top/Article/details/gtdgfuzdoz.html

Py:   async def f():⏎    await g()
来源：http://dali.zhixingplan.top/Article/details/gtptuayufc.html


<!-- 参考信息 -->