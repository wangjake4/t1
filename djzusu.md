代发 wailian999

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gt2wgrtswaa.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gt2gqnyesjj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gt2vadnunlj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ehwqpu.com/Article/details/gt2pmgdgxlm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.0kj1m.cn/Article/details/gt2pwpkdimc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj202588.top/Article/details/gt2lescinah.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenjidiqi.icu/Article/details/gt2zjlfqtxo.html

Py:   pickle.dumps(obj)
来源：http://dali.redwolf501.top/Article/details/gt2erhrnfeh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhixingplan.top/Article/details/gt2fjjdbnkb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nwbrower.top/Article/details/gt2lnwzwuyo.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cucudq.cn/Article/details/gt2raztrcmh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xuanzx.com/Article/details/gt2gzkkouod.html

Go:   encoding/gob
来源：http://dali.gaohongyu789.top/Article/details/gt2cbadmaze.html

Ruby: Marshal.dump(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2aeponwkk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ehwqpu.com/Article/details/gt2puyrtmha.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2qnpqqawo.html

L. 网络请求
来源：http://dali.guowangkeji.top/Article/details/gt2zogpigiz.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2gwvxetav.html

[L01] 发送 GET 请求
来源：http://dali.zycfv.cn/Article/details/gt2exfrkbwf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xziqi.cn/Article/details/gt2tjgpyupv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.feifeiyinyue.top/Article/details/gt2fhmspuhn.html

JS:   await fetch(url)
来源：http://dali.zdqjudy.top/Article/details/gt2kmafypjt.html

TS:   await fetch(url)
来源：http://dali.yangfankeji.com/Article/details/gt2mypjqlod.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.tian-w.cn/Article/details/gt2xftghmom.html

Go:   resp, err := http.Get(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kgvjjnio.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ktojlvjz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhengqikj.top/Article/details/gt2dtgtahzj.html

[L02] 发送 POST JSON
来源：http://dali.hfpthk.cn/Article/details/gt2xcbijqpq.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.dashuyun.cn/Article/details/gt2dqicbaiu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xuetiantiany.cn/Article/details/gt2kvsentid.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258888.top/Article/details/gt2ryvuwfcz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuanzx.com/Article/details/gt2pdznxqqf.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.guowangkeji.top/Article/details/gt2lumrvbln.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.chenjidiqi.icu/Article/details/gt2tmvdbjnv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.9152youxi.cn/Article/details/gt2zwuuoyny.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.guowangkeji.top/Article/details/gt2xgfnsfzm.html

[L03] 设置自定义请求头
来源：http://dali.yueranfly.top/Article/details/gt2tggupumz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.havefunace.top/Article/details/gt2ttfjsojk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jiagoushi.top/Article/details/gt2ltxhgswo.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xinyue.icu/Article/details/gt2fepzaryn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yanxiufei.cn/Article/details/gt2wongtafe.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jlsjyb.cn/Article/details/gt2perkcbyt.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ybcxt.top/Article/details/gt2ngvoongn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zycfv.cn/Article/details/gt2cbtslxoc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.havefunace.top/Article/details/gt2jesufqun.html

[L04] 设置超时
来源：http://dali.pengpengdd.cyou/Article/details/gt2rstdrkxo.html

Py:   requests.get(url, timeout=5)
来源：http://dali.nanxinkj.top/Article/details/gt2cqzoclzn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.kuanghao11.cn/Article/details/gt2qedziecf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yvedp.cn/Article/details/gt2fvqrgfov.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangdashe.top/Article/details/gt2fudwdklo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yongpay.top/Article/details/gt2kkbwnmmt.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.9152youxi.cn/Article/details/gt2usjffmwx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yonumen.top/Article/details/gt2aplkropo.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zdqjudy.top/Article/details/gt2zutsafdc.html

[L05] 上传文件（multipart）
来源：http://dali.jlsjyb.cn/Article/details/gt2urgqhdhf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ovtsvjnw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jianghu66.top/Article/details/gt2pzsliocf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.aizwys.cn/Article/details/gt2kegzpybi.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.iojbl.cn/Article/details/gt2drnsprsr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.chenzaomai.com/Article/details/gt2yhfmyvyu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.bjfxy.top/Article/details/gt2akjlgeuj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yueranfly.top/Article/details/gt2kszvbvtp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2rjonywmm.html

[L06] 解析响应为 JSON
来源：http://dali.fengsongda.top/Article/details/gt2oezjmugk.html

Py:   resp.json()
来源：http://dali.zhoulong.xyz/Article/details/gt2lprcsiif.html

PHP:  json_decode($body, true);
来源：http://dali.gaohongyu789.top/Article/details/gt2vxwhyyfg.html

JS:   await resp.json()
来源：http://dali.daxiang520.top/Article/details/gt2hjmfddqo.html

TS:   await resp.json()
来源：http://dali.gotoacloud.top/Article/details/gt2yjziugmt.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ssybxtqc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.wangshuangyany.cn/Article/details/gt2yvlznsod.html

Ruby: JSON.parse(resp.body)
来源：http://dali.snrcjt.cn/Article/details/gt2sunvstyg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jiagoushi.top/Article/details/gt2payidlza.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinqigufen.top/Article/details/gt2phxoamid.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cheryme.top/Article/details/gt2zmptmsbj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yj202588.top/Article/details/gt2flqhyjja.html

JS:   resp.ok;  resp.status
来源：http://dali.tianlin.xyz/Article/details/gt2mbwglpld.html

TS:   resp.ok;  resp.status
来源：http://dali.snrcjt.cn/Article/details/gt2ullaqlkm.html

Java: resp.statusCode()
来源：http://dali.chenzaomai.com/Article/details/gt2ohlftrrt.html

Go:   resp.StatusCode
来源：http://dali.meibo888.top/Article/details/gt2apeipejm.html

Ruby: resp.code.to_i
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fapvpxkd.html

C#:   (int)resp.StatusCode
来源：http://dali.sysykeji.top/Article/details/gt2isyeidwa.html

[L08] 并发请求多个地址
来源：http://dali.gaohongyu789.top/Article/details/gt2zculqsap.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sxryk.cn/Article/details/gt2cmffxrgs.html

PHP:  curl_multi_init() 系列
来源：http://dali.jyoumei.cn/Article/details/gt2xvszxnmg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.bjfxy.top/Article/details/gt2ljuldzxn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgfzy.top/Article/details/gt2slzyingy.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.snrcjt.cn/Article/details/gt2bqfytsov.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sxryk.cn/Article/details/gt2muaabzvz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.svipenyu.cn/Article/details/gt2uyknqwxw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.svipenyu.cn/Article/details/gt2lhkqeykw.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2kgglvscv.html

M. 命令行 / 进程 / 环境
来源：http://dali.jqgufenzy.top/Article/details/gt2acknwlqy.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2dgzotbsv.html

[M01] 读取命令行参数
来源：http://dali.shzxlz.cn/Article/details/gt2joeobepm.html

Py:   sys.argv[1:]
来源：http://dali.jinqigfzy.top/Article/details/gt2ugxxzxzh.html

PHP:  $argv;  $argc;
来源：http://dali.chenjidiqi.icu/Article/details/gt2uommpoqf.html

JS:   process.argv.slice(2)
来源：http://dali.shuidangran.top/Article/details/gt2olnfqakz.html

TS:   process.argv.slice(2)
来源：http://dali.jiagoushi.top/Article/details/gt2nrcygysl.html

Java: args 数组（main 方法参数）
来源：http://dali.kuanghao11.cn/Article/details/gt2nmyumktn.html

Go:   os.Args[1:]
来源：http://dali.wangshuangyany.cn/Article/details/gt2stfgreok.html

Ruby: ARGV
来源：http://dali.wangshuangyany.cn/Article/details/gt2aqzgfteb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zycfv.cn/Article/details/gt2olktypkg.html

[M02] 读取环境变量
来源：http://dali.vqdsnc.cn/Article/details/gt2pyhacqqd.html

Py:   os.environ.get("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gt2nhnzkbhh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sysykeji.top/Article/details/gt2asoqxbzp.html

JS:   process.env.HOME
来源：http://dali.wangdashe.top/Article/details/gt2gfxaymlw.html

TS:   process.env.HOME
来源：http://dali.zdqjudy.top/Article/details/gt2flouoddv.html

Java: System.getenv("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gt2vaqnulju.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gt2vtopcgrh.html

Ruby: ENV["HOME"]
来源：http://dali.pycfn.com/Article/details/gt2bovamfsh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cucudq.cn/Article/details/gt2pumodeoc.html

[M03] 执行外部命令
来源：http://dali.mhx1999.top/Article/details/gt2nqhxsbkh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.daxiang520.top/Article/details/gt2ziiezvfk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.fzhhl.top/Article/details/gt2xayzjbvi.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tanke756.top/Article/details/gt2ziwntfqr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuxming.cn/Article/details/gt2qgajmwqj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ggpbmnxg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nwbrower.top/Article/details/gt2aitucbax.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.aibaodan.cn/Article/details/gt2pmaxjolf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tianlin.xyz/Article/details/gt2yjooqfio.html

[M04] 获取当前工作目录
来源：http://dali.tian-w.cn/Article/details/gt2mjnsvlht.html

Py:   os.getcwd()
来源：http://dali.ydzc1.top/Article/details/gt2pgkxwkej.html

PHP:  getcwd();
来源：http://dali.cashguo.top/Article/details/gt2szshxclf.html

JS:   process.cwd()
来源：http://dali.hnxiangtu.top/Article/details/gt2elvwfmdx.html

TS:   process.cwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sjbdecer.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gzhubu.top/Article/details/gt2dqvmbihc.html

Go:   os.Getwd()
来源：http://dali.tian-w.cn/Article/details/gt2nwvmcppi.html

Ruby: Dir.pwd
来源：http://dali.gotoacloud.top/Article/details/gt2kqnuoedg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.andypj.xyz/Article/details/gt2pudnainm.html

[M05] 设置退出码
来源：http://dali.meibo888.top/Article/details/gt2mvsrhngy.html

Py:   sys.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xdgsfoma.html

PHP:  exit(1);
来源：http://dali.sxryk.cn/Article/details/gt2hfanwzjh.html

JS:   process.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gt2kfmcgjgf.html

TS:   process.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2iiltwxfk.html

Java: System.exit(1)
来源：http://dali.fengsongda.top/Article/details/gt2piwciluf.html

Go:   os.Exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2kiwakbku.html

Ruby: exit 1
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fifllgfd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2skshfiil.html

[M06] 向标准错误输出
来源：http://dali.fzhhl.top/Article/details/gt2birhenfz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gaohongyu789.top/Article/details/gt2gpaipbjr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xylfe.cn/Article/details/gt2nvztxeqa.html

JS:   console.error("err")
来源：http://dali.shangyingyoupin.top/Article/details/gt2dxevlscc.html

TS:   console.error("err")
来源：http://dali.hnqzz.top/Article/details/gt2gxrdyemc.html

Java: System.err.println("err")
来源：http://dali.shangyingyoupin.top/Article/details/gt2eibshhxa.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.haohaochexian.top/Article/details/gt2censokpp.html

Ruby: warn "err"
来源：http://dali.andypj.xyz/Article/details/gt2ltmnvurp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.snrcjt.cn/Article/details/gt2ucumvsjh.html

[M07] 判断是否为主入口
来源：http://dali.shuidangran.top/Article/details/gt2izgduksu.html

Py:   if __name__ == "__main__":
来源：http://dali.jlsjyb.cn/Article/details/gt2modsprtf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.chenlongwang.top/Article/details/gt2gwhsbjvc.html

JS:   require.main === module
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ggxtwedg.html

TS:   require.main === module
来源：http://dali.sxryk.cn/Article/details/gt2ckcgiqap.html

Java: public static void main(String[] args)
来源：http://dali.c1oappe.top/Article/details/gt2zbqzvztw.html

Go:   func main()
来源：http://dali.redwolf501.top/Article/details/gt2unlvaigb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gieyjbzy.html

C#:   static void Main(string[] args)
来源：http://dali.jlsjyb.cn/Article/details/gt2utlbrpsq.html

[M08] 获取系统与运行时信息
来源：http://dali.pengpengdd.cyou/Article/details/gt2rcdqxixc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lqfjzqys.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.tanke756.top/Article/details/gt2dxiijmdt.html

JS:   process.platform;  process.version
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xmrcjndb.html

TS:   process.platform;  process.version
来源：http://dali.tianlin.xyz/Article/details/gt2ihduives.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cheryme.top/Article/details/gt2vbyfiprd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hongshengwenyu.top/Article/details/gt2zbezndrd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yanxiufei.cn/Article/details/gt2uprbbuat.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.feifeiyinyue.top/Article/details/gt2hrsusqps.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2wrracqzu.html

N. 数据结构与算法
来源：http://dali.tianlin.xyz/Article/details/gt2jphrvkrb.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rtqvsrqj.html

[N01] 二分查找（有序数组）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sevffuor.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cucudq.cn/Article/details/gt2uywzfkui.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.chenzaomai.com/Article/details/gt2xvdfgzhn.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fengsongda.top/Article/details/gt2yomkjbaz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxinkj.top/Article/details/gt2vslonlvz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gt2mctqzjjx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gt2uedwcsyy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hongshengwenyu.top/Article/details/gt2lkfhoyrl.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sxryk.cn/Article/details/gt2mxgmsirt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jqgufenzy.top/Article/details/gt2lyxzgdvf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cqqwz.cn/Article/details/gt2zggcbiel.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhongyouzk.top/Article/details/gt2pqtzumfh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ydzc1.top/Article/details/gt2fbgjaneu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yvedp.cn/Article/details/gt2dusawnwx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.quarkkingdee.top/Article/details/gt2ulbjysed.html

Go:   slices.Sort(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oucrkxrg.html

Ruby: arr.sort
来源：http://dali.jyoumei.cn/Article/details/gt2pvblyuxg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vmflvclb.html

[N03] 快速排序（分治示例）
来源：http://dali.zhoulong.xyz/Article/details/gt2ztgpdgcs.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jiagoushi.top/Article/details/gt2iuvqojgl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.haohaochexian.top/Article/details/gt2hhybsgex.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.mhx1999.top/Article/details/gt2zzshijoh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guannengcc.top/Article/details/gt2prneqvsh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.snrcjt.cn/Article/details/gt2pacimnpy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yonumen.top/Article/details/gt2ntiemzcy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xziqi.cn/Article/details/gt2fgolqunj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinqigufen.top/Article/details/gt2auorfoic.html

[N04] 斐波那契数列
来源：http://dali.yvedp.cn/Article/details/gt2skerljrh.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lfxeyypv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.quarkkingdee.top/Article/details/gt2jelivbdk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gt2ziunplst.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gt2xwembqtw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mtoaskll.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cucudq.cn/Article/details/gt2bnfowpmw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yangfankeji.com/Article/details/gt2pluaiexm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinqigufen.top/Article/details/gt2fingdfry.html

[N05] 最大公约数
来源：http://dali.xuetiantiany.cn/Article/details/gt2jgeenjgq.html

Py:   math.gcd(a, b)
来源：http://dali.jianghu66.top/Article/details/gt2rvajjljj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jiagoushi.top/Article/details/gt2ubhucsed.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dashuyun.cn/Article/details/gt2qqwxwaza.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenzaomai.com/Article/details/gt2gtcpclwx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.guowangkeji.top/Article/details/gt2pheofvfv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jqgfzy.top/Article/details/gt2mmzlmvsc.html

Ruby: a.gcd(b)
来源：http://dali.guannengcc.top/Article/details/gt2gwatniyo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2olpkonbh.html

[N06] 判断回文字符串
来源：http://dali.sufxvd.cn/Article/details/gt2wmadwbgz.html

Py:   s == s[::-1]
来源：http://dali.xziqi.cn/Article/details/gt2thyiseyx.html

PHP:  $s === strrev($s);
来源：http://dali.wangdashe.top/Article/details/gt2kkbgtfry.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gt2asdixdfq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gt2vyxtxbcl.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ehwqpu.com/Article/details/gt2vitbaxgs.html

Go:   // 双指针从两端比较
来源：http://dali.zhiwuduotai.top/Article/details/gt2amglzffy.html

Ruby: s == s.reverse
来源：http://dali.sxryk.cn/Article/details/gt2rwrrqooy.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xylfe.cn/Article/details/gt2woxwgoqg.html

[N07] 两数之和（返回下标）
来源：http://dali.9152youxi.cn/Article/details/gt2fttnpmgq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.9152youxi.cn/Article/details/gt2onvbiilh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qtyypcix.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hywenlv.cn/Article/details/gt2neenkkxe.html

TS:   // 手写 Map<string, number>
来源：http://dali.shangyingyoupin.top/Article/details/gt2tdgqaytq.html

Java: // 手写 HashMap
来源：http://dali.meibo888.top/Article/details/gt2redcmbvs.html

Go:   // 手写 map[int]int
来源：http://dali.cdnleiting.top/Article/details/gt2wrlnhnzh.html

Ruby: // 手写 Hash
来源：http://dali.hywenlv.cn/Article/details/gt2fhxvbthi.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzyncuf.html

[N08] 生成全排列
来源：http://dali.kuanghao11.cn/Article/details/gt2tefrjkks.html

Py:   itertools.permutations(arr)
来源：http://dali.yj20258888.top/Article/details/gt2rarvswox.html

PHP:  // 手写递归交换
来源：http://dali.chenzaomai.com/Article/details/gt2sosgtbcw.html

JS:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gt2mvqbadyr.html

TS:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gt2omlajbgo.html

Java: // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gt2arzperon.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdtwqzr.html

Ruby: arr.permutation.to_a
来源：http://dali.316326.xyz/Article/details/gt2fficgyyt.html

C#:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gt2oqqnqimx.html

[N09] 栈与队列
来源：http://dali.jlsjyb.cn/Article/details/gt2mzvsvval.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.meibo888.top/Article/details/gt2bqzpufbs.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jqgfzy.top/Article/details/gt2dstuihhi.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.svipenyu.cn/Article/details/gt2fazljpoq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cheryme.top/Article/details/gt2cdnlojqp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinqigfzy.top/Article/details/gt2eudrcnxf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.tanke756.top/Article/details/gt2ewhhexaf.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shzxlz.cn/Article/details/gt2gouhxems.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.wangdashe.top/Article/details/gt2fxckkkrw.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfbdqqg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.daxiang520.top/Article/details/gt2oiiriapj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.pycfn.com/Article/details/gt2asykfhzz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.pengpengdd.cyou/Article/details/gt2jguzjirh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hnxiangtu.top/Article/details/gt2igldmosx.html

Java: class Node { int v; Node next; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ggtqvhse.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.meibo888.top/Article/details/gt2ntstnnyl.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tian-w.cn/Article/details/gt2ttenwavo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.guannengcc.top/Article/details/gt2tjbqmltl.html

[N11] 二叉树中序遍历
来源：http://dali.jqgfzy.top/Article/details/gt2kkrummwp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yj202588.top/Article/details/gt2qfakprwn.html

PHP:  // 手写递归函数
来源：http://dali.ydzc1.top/Article/details/gt2orlutgjl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hfpthk.cn/Article/details/gt2lnxbleis.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.0kj1m.cn/Article/details/gt2wrfeapux.html

Java: // 手写递归
来源：http://dali.tian-w.cn/Article/details/gt2tpfsjyec.html

Go:   // 手写递归
来源：http://dali.yueranfly.top/Article/details/gt2xtlzzuwp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hammf.cn/Article/details/gt2nybqbplz.html

C#:   // 手写递归
来源：http://dali.ppjwa.cn/Article/details/gt2nblrgnby.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.snrcjt.cn/Article/details/gt2xujdhobs.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hnxiangtu.top/Article/details/gt2mrtniqdp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhiwuduotai.top/Article/details/gt2mlmclpzx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj202588.top/Article/details/gt2srkugeqi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rlobkykp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oxmzqbxn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mjhglaid.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.meibo888.top/Article/details/gt2fgwmqtzk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hongshengwenyu.top/Article/details/gt2tsfpjnwo.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2dmcjykou.html

O. 并发与异步
来源：http://dali.cqqwz.cn/Article/details/gt2yuabdkdk.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2nduujrji.html

[O01] 启动一个线程
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uxzismad.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.aibaodan.cn/Article/details/gt2dxaplgjz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yueranfly.top/Article/details/gt2nbviefbt.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wpapxwzr.html

TS:   // 同 JS
来源：http://dali.birdmap.top/Article/details/gt2gqtruhnm.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2snsltbsr.html

Go:   go f()
来源：http://dali.cheryme.top/Article/details/gt2iicjwcjt.html

Ruby: Thread.new { f }
来源：http://dali.hnqzz.top/Article/details/gt2jcwbnmqr.html

C#:   Task.Run(() => F());
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eusiinuq.html

[O02] 使用线程池
来源：http://dali.hfpthk.cn/Article/details/gt2kpaasixb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hnqzz.top/Article/details/gt2wyhptmvy.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.feifeiyinyue.top/Article/details/gt2jkvfwzfy.html

JS:   // worker_threads 线程池
来源：http://dali.cashguo.top/Article/details/gt2fclgskad.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmwosxq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.tianlin.xyz/Article/details/gt2drnaxnuy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.andypj.xyz/Article/details/gt2zedgzclc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shangyingyoupin.top/Article/details/gt2cmefiggx.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yzgtyytd.html

[O03] 加锁保护共享数据
来源：http://dali.yuxming.cn/Article/details/gt2yzkzijff.html

Py:   with lock: shared += 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zriypnbq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cqqwz.cn/Article/details/gt2noixzksr.html


<!-- 参考信息 -->