代发 wailian999

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gt2fqdkofyx.html

[K07] 进制转换
来源：http://dali.chenlongwang.top/Article/details/gt2nwoszpbs.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gt2imoqriuk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gzhubu.top/Article/details/gt2dvhibygr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ivvv.top/Article/details/gt2erllraca.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gt2wpwpheok.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cashguo.top/Article/details/gt2stjqfqhc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sysykeji.top/Article/details/gt2nchwucpq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.iojbl.cn/Article/details/gt2kczqzteg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.pycfn.com/Article/details/gt2zclmfcnq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.316326.xyz/Article/details/gt2engbqgpa.html

Py:   pickle.dumps(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2izfqsuja.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ymxemyiw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.haohaochexian.top/Article/details/gt2wfidoirx.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cheryme.top/Article/details/gt2opcopgsy.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yuxming.cn/Article/details/gt2vfbchkzj.html

Go:   encoding/gob
来源：http://dali.yonumen.top/Article/details/gt2ffkjpuix.html

Ruby: Marshal.dump(obj)
来源：http://dali.hammf.cn/Article/details/gt2mibnstrg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hysaishi.cn/Article/details/gt2pgnqyaqt.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uypowabh.html

L. 网络请求
来源：http://dali.pycfn.com/Article/details/gt2igcgvprf.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2otpkpzng.html

[L01] 发送 GET 请求
来源：http://dali.chenlongwang.top/Article/details/gt2tsfftnon.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hysaishi.cn/Article/details/gt2pxaxtlww.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hfpthk.cn/Article/details/gt2klsbauef.html

JS:   await fetch(url)
来源：http://dali.dianchejie.cn/Article/details/gt2fzziidnb.html

TS:   await fetch(url)
来源：http://dali.zhoulong.xyz/Article/details/gt2qvoekdnn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jyoumei.cn/Article/details/gt2phrvrdkm.html

Go:   resp, err := http.Get(url)
来源：http://dali.yangfankeji.com/Article/details/gt2cwtkvwdl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zdqjudy.top/Article/details/gt2eslbhqxu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sweek.top/Article/details/gt2kwaqyarp.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vjywxzbq.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yvedp.cn/Article/details/gt2lxgstegw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.andypj.xyz/Article/details/gt2pvvtrkqh.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenlongwang.top/Article/details/gt2wvzfabpv.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fzhhl.top/Article/details/gt2oiuilgds.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yongpay.top/Article/details/gt2andlgbpb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yongpay.top/Article/details/gt2pzotwndy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hysaishi.cn/Article/details/gt2crmxnojb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yuxming.cn/Article/details/gt2koiswuij.html

[L03] 设置自定义请求头
来源：http://dali.hfpthk.cn/Article/details/gt2rtvrowbd.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.snrcjt.cn/Article/details/gt2rhnqsupa.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.nwbrower.top/Article/details/gt2qthcyrge.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ydzc1.top/Article/details/gt2nhqhzokr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.svipenyu.cn/Article/details/gt2wwhhvmym.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zdqjudy.top/Article/details/gt2cgstshwb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cucudq.cn/Article/details/gt2ctgztxbj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gaohongyu789.top/Article/details/gt2tbrpbmov.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinqigufen.top/Article/details/gt2fgzihgfn.html

[L04] 设置超时
来源：http://dali.tanke756.top/Article/details/gt2sqvxtmjf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.c1oappe.top/Article/details/gt2lmvqgjas.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhongyouzk.top/Article/details/gt2pkltbmcv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigufen.top/Article/details/gt2psgelysk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jlsjyb.cn/Article/details/gt2ypdbehpt.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.dianchejie.cn/Article/details/gt2hnyrdosu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.wangdashe.top/Article/details/gt2xviknmvb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sufxvd.cn/Article/details/gt2ovxmdxpf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.0kj1m.cn/Article/details/gt2sadlwnxd.html

[L05] 上传文件（multipart）
来源：http://dali.smart0.xyz/Article/details/gt2zhenzewy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.havefunace.top/Article/details/gt2cyqpkgmz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sufxvd.cn/Article/details/gt2hxvlafeu.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hysaishi.cn/Article/details/gt2ktkqmcnr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenzaomai.com/Article/details/gt2olzhdnto.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hammf.cn/Article/details/gt2ofcfpdii.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yj20258.top/Article/details/gt2rarxvxow.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jyoumei.cn/Article/details/gt2axmajnba.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2mrglnddy.html

[L06] 解析响应为 JSON
来源：http://dali.ehwqpu.com/Article/details/gt2bktbywrz.html

Py:   resp.json()
来源：http://dali.yangfankeji.com/Article/details/gt2vhqijqxl.html

PHP:  json_decode($body, true);
来源：http://dali.zhiwuduotai.top/Article/details/gt2agqpzhnl.html

JS:   await resp.json()
来源：http://dali.aizwys.cn/Article/details/gt2rlfmkrrx.html

TS:   await resp.json()
来源：http://dali.jyoumei.cn/Article/details/gt2sqrfpgko.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jlsjyb.cn/Article/details/gt2cjmomlfx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.guowangkeji.top/Article/details/gt2epgyvfxg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.svipenyu.cn/Article/details/gt2iiyxqrdg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.tianlin.xyz/Article/details/gt2izirufwv.html

[L07] 处理 HTTP 状态码
来源：http://dali.daria6918.cn/Article/details/gt2azbwbkez.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yuanzhike.top/Article/details/gt2udajjsom.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yongpay.top/Article/details/gt2uykakspw.html

JS:   resp.ok;  resp.status
来源：http://dali.aibaodan.cn/Article/details/gt2ritvuflx.html

TS:   resp.ok;  resp.status
来源：http://dali.0kj1m.cn/Article/details/gt2gsbqcwfe.html

Java: resp.statusCode()
来源：http://dali.zdqjudy.top/Article/details/gt2imqlwaqw.html

Go:   resp.StatusCode
来源：http://dali.wangdashe.top/Article/details/gt2eutluxad.html

Ruby: resp.code.to_i
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uxlupnmb.html

C#:   (int)resp.StatusCode
来源：http://dali.yvedp.cn/Article/details/gt2vyqiwvoa.html

[L08] 并发请求多个地址
来源：http://dali.gzhubu.top/Article/details/gt2sswlhcnt.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.dianchejie.cn/Article/details/gt2vtodcwjp.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhixingplan.top/Article/details/gt2ieermyvn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gzhubu.top/Article/details/gt2zolhtjyw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhongyouzk.top/Article/details/gt2xqazzsgw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xylfe.cn/Article/details/gt2pkltjfbs.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.iojbl.cn/Article/details/gt2eqygjljg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zycfv.cn/Article/details/gt2iugobvfe.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj20258.top/Article/details/gt2hpasfvui.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2gcvtmuyz.html

M. 命令行 / 进程 / 环境
来源：http://dali.hnxiangtu.top/Article/details/gt2flfkmmtw.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2xoiedhhq.html

[M01] 读取命令行参数
来源：http://dali.gzhubu.top/Article/details/gt2arabqako.html

Py:   sys.argv[1:]
来源：http://dali.gotoacloud.top/Article/details/gt2gfbdsgso.html

PHP:  $argv;  $argc;
来源：http://dali.cdnleiting.top/Article/details/gt2kzekwusu.html

JS:   process.argv.slice(2)
来源：http://dali.zycfv.cn/Article/details/gt2gqehrgae.html

TS:   process.argv.slice(2)
来源：http://dali.aibaodan.cn/Article/details/gt2tssnrcwm.html

Java: args 数组（main 方法参数）
来源：http://dali.gzhubu.top/Article/details/gt2vbvpkelb.html

Go:   os.Args[1:]
来源：http://dali.wangshuangyany.cn/Article/details/gt2mevuqctk.html

Ruby: ARGV
来源：http://dali.yvedp.cn/Article/details/gt2ykngftpl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.snrcjt.cn/Article/details/gt2fsjfugzm.html

[M02] 读取环境变量
来源：http://dali.yongpay.top/Article/details/gt2xepqtyaf.html

Py:   os.environ.get("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gt2dfexxmnr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.dianchejie.cn/Article/details/gt2jsncsegi.html

JS:   process.env.HOME
来源：http://dali.cqqwz.cn/Article/details/gt2uacmawms.html

TS:   process.env.HOME
来源：http://dali.yangfankeji.com/Article/details/gt2niltkpuv.html

Java: System.getenv("HOME")
来源：http://dali.mhx1999.top/Article/details/gt2lwrxaoqn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gt2enfjtyzu.html

Ruby: ENV["HOME"]
来源：http://dali.ehwqpu.com/Article/details/gt2sgklrouf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhengqikj.top/Article/details/gt2qalcjmjw.html

[M03] 执行外部命令
来源：http://dali.zhongyouzk.top/Article/details/gt2zwoglaib.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ywrlqfpt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yonumen.top/Article/details/gt2auiqmkvn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gzhubu.top/Article/details/gt2fsilubra.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuetiantiany.cn/Article/details/gt2vphhgqvf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.wangdashe.top/Article/details/gt2sdvpdpqa.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yangfankeji.com/Article/details/gt2shnipedb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinqigufen.top/Article/details/gt2rlpkmbst.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gotoacloud.top/Article/details/gt2xcvilerf.html

[M04] 获取当前工作目录
来源：http://dali.yanxiufei.cn/Article/details/gt2qrreolux.html

Py:   os.getcwd()
来源：http://dali.guowangkeji.top/Article/details/gt2vmpiyjoh.html

PHP:  getcwd();
来源：http://dali.feifeiyinyue.top/Article/details/gt2ghbsshhb.html

JS:   process.cwd()
来源：http://dali.ybcxt.top/Article/details/gt2kiyeqvia.html

TS:   process.cwd()
来源：http://dali.hysaishi.cn/Article/details/gt2qnedyctx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cheryme.top/Article/details/gt2dexrepyg.html

Go:   os.Getwd()
来源：http://dali.aizwys.cn/Article/details/gt2jeumshuv.html

Ruby: Dir.pwd
来源：http://dali.yongpay.top/Article/details/gt2kacmegwr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hysaishi.cn/Article/details/gt2okmcenxe.html

[M05] 设置退出码
来源：http://dali.cqqwz.cn/Article/details/gt2cpskpahb.html

Py:   sys.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2dorylbrg.html

PHP:  exit(1);
来源：http://dali.c1oappe.top/Article/details/gt2hbjjkvuu.html

JS:   process.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2znsibeiz.html

TS:   process.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zpzfjpgu.html

Java: System.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kboozday.html

Go:   os.Exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mlxlxjxj.html

Ruby: exit 1
来源：http://dali.svipenyu.cn/Article/details/gt2onirlwku.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nanxinkj.top/Article/details/gt2jtvtrmtw.html

[M06] 向标准错误输出
来源：http://dali.zycfv.cn/Article/details/gt2ndeqxqmr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xnngncxf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hywenlv.cn/Article/details/gt2mxtxchyd.html

JS:   console.error("err")
来源：http://dali.316326.xyz/Article/details/gt2hcyqaump.html

TS:   console.error("err")
来源：http://dali.sysykeji.top/Article/details/gt2ungoqdfo.html

Java: System.err.println("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vapqijvt.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gzhubu.top/Article/details/gt2bwerdffx.html

Ruby: warn "err"
来源：http://dali.0kj1m.cn/Article/details/gt2duqyefru.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sxryk.cn/Article/details/gt2yopdhler.html

[M07] 判断是否为主入口
来源：http://dali.haohaochexian.top/Article/details/gt2ndjipkrt.html

Py:   if __name__ == "__main__":
来源：http://dali.jinqigfzy.top/Article/details/gt2gzilluaz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.redwolf501.top/Article/details/gt2esrboush.html

JS:   require.main === module
来源：http://dali.snrcjt.cn/Article/details/gt2gshyhyqz.html

TS:   require.main === module
来源：http://dali.hammf.cn/Article/details/gt2tbsqoavu.html

Java: public static void main(String[] args)
来源：http://dali.hysaishi.cn/Article/details/gt2scrgmzty.html

Go:   func main()
来源：http://dali.ybcxt.top/Article/details/gt2xfmjwbya.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gwdqaowz.html

C#:   static void Main(string[] args)
来源：http://dali.guannengcc.top/Article/details/gt2tefsnuun.html

[M08] 获取系统与运行时信息
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cukbcpoa.html

Py:   platform.system();  platform.python_version()
来源：http://dali.nanxinkj.top/Article/details/gt2iljvouix.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ydzc1.top/Article/details/gt2hmhpdgje.html

JS:   process.platform;  process.version
来源：http://dali.jlsjyb.cn/Article/details/gt2zagztokd.html

TS:   process.platform;  process.version
来源：http://dali.wangshuangyany.cn/Article/details/gt2qnmwkgsf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.fzhhl.top/Article/details/gt2nxscnbfx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cucudq.cn/Article/details/gt2yblglihc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hywenlv.cn/Article/details/gt2gptopboe.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yanxiufei.cn/Article/details/gt2etwrjhuu.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2wbekvsys.html

N. 数据结构与算法
来源：http://dali.jiagoushi.top/Article/details/gt2wgpibjat.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2cpexbdyg.html

[N01] 二分查找（有序数组）
来源：http://dali.daria6918.cn/Article/details/gt2qpwepbhn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hnqzz.top/Article/details/gt2gllfgptc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yvedp.cn/Article/details/gt2eemztkzb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pycfn.com/Article/details/gt2nkxmjjid.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dashuyun.cn/Article/details/gt2losybtgr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gt2xezzjgsv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vxlwancs.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gotoacloud.top/Article/details/gt2ovmjbcrh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.andypj.xyz/Article/details/gt2yztlimnb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.wangdashe.top/Article/details/gt2dclzvnby.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jiagoushi.top/Article/details/gt2mcbdudfk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.chenzaomai.com/Article/details/gt2jezhhnqe.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ulenbrht.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sufxvd.cn/Article/details/gt2ueiqhmud.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.havefunace.top/Article/details/gt2qjtyrbuf.html

Go:   slices.Sort(arr)
来源：http://dali.zycfv.cn/Article/details/gt2qxuqenqy.html

Ruby: arr.sort
来源：http://dali.zhixingplan.top/Article/details/gt2gkvwwcid.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gzhubu.top/Article/details/gt2mleqfobs.html

[N03] 快速排序（分治示例）
来源：http://dali.0kj1m.cn/Article/details/gt2tihzfgjs.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hnxiangtu.top/Article/details/gt2bmckkkym.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yonumen.top/Article/details/gt2ebqpmakm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.316326.xyz/Article/details/gt2cpqsuzvf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guannengcc.top/Article/details/gt2odxxdbck.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jlsjyb.cn/Article/details/gt2pifshrkk.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.vqdsnc.cn/Article/details/gt2pdrtwxur.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.iojbl.cn/Article/details/gt2hztosqwm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.daria6918.cn/Article/details/gt2sncbrchm.html

[N04] 斐波那契数列
来源：http://dali.ivvv.top/Article/details/gt2anhlsmmq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.wangdashe.top/Article/details/gt2lbtahdfs.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.iojbl.cn/Article/details/gt2sgaoixqt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zycfv.cn/Article/details/gt2dupkrfii.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gt2egukzfhf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zdqjudy.top/Article/details/gt2wgqugymi.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenzaomai.com/Article/details/gt2voqxqmpx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.meibo888.top/Article/details/gt2yqyhpxto.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.chenjidiqi.icu/Article/details/gt2jjpeucif.html

[N05] 最大公约数
来源：http://dali.jlsjyb.cn/Article/details/gt2fcmaiicu.html

Py:   math.gcd(a, b)
来源：http://dali.jiagoushi.top/Article/details/gt2ldwmsjpc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2mvdjhhfa.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2fosmdbci.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hfpthk.cn/Article/details/gt2cszqxjio.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xinyue.icu/Article/details/gt2zocpeyhl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.tian-w.cn/Article/details/gt2qmoejzny.html

Ruby: a.gcd(b)
来源：http://dali.ppjwa.cn/Article/details/gt2zgamugnd.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.svipenyu.cn/Article/details/gt2amfhzivg.html

[N06] 判断回文字符串
来源：http://dali.guannengcc.top/Article/details/gt2jkabbnvp.html

Py:   s == s[::-1]
来源：http://dali.shuidangran.top/Article/details/gt2nmzhnbwr.html

PHP:  $s === strrev($s);
来源：http://dali.9152youxi.cn/Article/details/gt2ultbjqdp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gt2mhthmekl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gt2ktqzreox.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.nwbrower.top/Article/details/gt2iygtdzjb.html

Go:   // 双指针从两端比较
来源：http://dali.zhiwuduotai.top/Article/details/gt2cjafyikm.html

Ruby: s == s.reverse
来源：http://dali.pengpengdd.cyou/Article/details/gt2nwzjdtem.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hongshengwenyu.top/Article/details/gt2odhorzzm.html

[N07] 两数之和（返回下标）
来源：http://dali.jianghu66.top/Article/details/gt2duigfzqq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.daxiang520.top/Article/details/gt2mdhanxpf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj20258888.top/Article/details/gt2kwsltvvu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhongyouzk.top/Article/details/gt2fvnvexsj.html

TS:   // 手写 Map<string, number>
来源：http://dali.hnxiangtu.top/Article/details/gt2mhhlqisa.html

Java: // 手写 HashMap
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xyoopcxn.html

Go:   // 手写 map[int]int
来源：http://dali.chenzaomai.com/Article/details/gt2jybfbekd.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2epwrcqau.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.pengpengdd.cyou/Article/details/gt2umvekzqd.html

[N08] 生成全排列
来源：http://dali.chenlongwang.top/Article/details/gt2zwqnerlc.html

Py:   itertools.permutations(arr)
来源：http://dali.xinyue.icu/Article/details/gt2yhffadxn.html

PHP:  // 手写递归交换
来源：http://dali.316326.xyz/Article/details/gt2vefvnerc.html

JS:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gt2gonkvopw.html

TS:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gt2mhntdgnj.html

Java: // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gt2npzmpznb.html

Go:   // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gt2sxigfeyd.html

Ruby: arr.permutation.to_a
来源：http://dali.zhiwuduotai.top/Article/details/gt2iofmhcne.html

C#:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gt2hivrbogt.html

[N09] 栈与队列
来源：http://dali.zycfv.cn/Article/details/gt2rqwhaqdd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.c1oappe.top/Article/details/gt2djwoypte.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.aibaodan.cn/Article/details/gt2orquaonl.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.0kj1m.cn/Article/details/gt2epqivamf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.tian-w.cn/Article/details/gt2tdohsrwc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xuanzx.com/Article/details/gt2tjjawnof.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shuidangran.top/Article/details/gt2kwwhubcq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yanxiufei.cn/Article/details/gt2wjzswpyk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xuanzx.com/Article/details/gt2tdvsltgx.html

[N10] 链表节点定义
来源：http://dali.yanxiufei.cn/Article/details/gt2kerfwbtv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.fengsongda.top/Article/details/gt2ucpnujke.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.tian-w.cn/Article/details/gt2shrbggxr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hongshengwenyu.top/Article/details/gt2mxhfhhwo.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ehwqpu.com/Article/details/gt2joxriayj.html

Java: class Node { int v; Node next; }
来源：http://dali.yj202588.top/Article/details/gt2bqfyvpvl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zdqjudy.top/Article/details/gt2lvyqvusu.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yj202588.top/Article/details/gt2wurcqjti.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tianlin.xyz/Article/details/gt2rqinbhhp.html

[N11] 二叉树中序遍历
来源：http://dali.sxryk.cn/Article/details/gt2gooblpnc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xylfe.cn/Article/details/gt2qerwvfac.html

PHP:  // 手写递归函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2laegyceg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zycfv.cn/Article/details/gt2sftrqrgo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sxryk.cn/Article/details/gt2vgfktycu.html

Java: // 手写递归
来源：http://dali.pengpengdd.cyou/Article/details/gt2ojltpdux.html

Go:   // 手写递归
来源：http://dali.chenlongwang.top/Article/details/gt2czzjvgdh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yanxiufei.cn/Article/details/gt2qutuvtlq.html

C#:   // 手写递归
来源：http://dali.yj20258.top/Article/details/gt2struocri.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xylfe.cn/Article/details/gt2dycredzf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fttrjkkr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.dianchejie.cn/Article/details/gt2nljrruta.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jiagoushi.top/Article/details/gt2oasirztt.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gotoacloud.top/Article/details/gt2vtavmgde.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xylfe.cn/Article/details/gt2idjsupov.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qrvuhwkx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.svipenyu.cn/Article/details/gt2amswkzfc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.9152youxi.cn/Article/details/gt2fujzzvar.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2bojawyiy.html

O. 并发与异步
来源：http://dali.jlsjyb.cn/Article/details/gt2paagczaf.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2uohrexxh.html

[O01] 启动一个线程
来源：http://dali.hywenlv.cn/Article/details/gt2pgssoobf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2odzlyohj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.havefunace.top/Article/details/gt2uiqeklzf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.sufxvd.cn/Article/details/gt2zwsmuaoh.html

TS:   // 同 JS
来源：http://dali.zhoulong.xyz/Article/details/gt2nkxdkocc.html

Java: new Thread(() -> f()).start()
来源：http://dali.gotoacloud.top/Article/details/gt2krtcgevi.html

Go:   go f()
来源：http://dali.hfpthk.cn/Article/details/gt2hupzshuz.html

Ruby: Thread.new { f }
来源：http://dali.haohaochexian.top/Article/details/gt2rwodnnqe.html

C#:   Task.Run(() => F());
来源：http://dali.birdmap.top/Article/details/gt2kkxmpjos.html

[O02] 使用线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gt2luyrxbrh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.dianchejie.cn/Article/details/gt2tbnxaoad.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sufxvd.cn/Article/details/gt2mtxenmwo.html

JS:   // worker_threads 线程池
来源：http://dali.cdnleiting.top/Article/details/gt2bqvgqazj.html

TS:   // worker_threads 线程池
来源：http://dali.ybcxt.top/Article/details/gt2wlrfbgrw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhiwuduotai.top/Article/details/gt2oesqykoo.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.guannengcc.top/Article/details/gt2qorraydt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.chenzaomai.com/Article/details/gt2pfddefed.html


<!-- 参考信息 -->