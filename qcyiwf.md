代发 wailian999

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsvparmtg.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.wangdashe.top/Article/details/gtdatymwni.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.bjfxy.top/Article/details/gtxqyuvacw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yangfankeji.com/Article/details/gtxhpklqds.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gtqynupphe.html

[K07] 进制转换
来源：http://dali.0kj1m.cn/Article/details/gtssockotr.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yj20258.top/Article/details/gthptabscj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nwbrower.top/Article/details/gtnqtpgxpl.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gtvwwutzyc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gtvgththin.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtjsxgmhga.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hongshengwenyu.top/Article/details/gtpjsxonbg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.feifeiyinyue.top/Article/details/gtqslhyduc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtpfqxkejg.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jyoumei.cn/Article/details/gtpwemzewh.html

Py:   pickle.dumps(obj)
来源：http://dali.hysaishi.cn/Article/details/gtwhgwouvr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.svipenyu.cn/Article/details/gtdqtsxfdq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jianghu66.top/Article/details/gtjabodkhe.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.nanxuanxn.top/Article/details/gtuhcrludo.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shanyushiyangtech.top/Article/details/gtmnhlukwn.html

Go:   encoding/gob
来源：http://dali.zhoulong.xyz/Article/details/gtsqpxvqca.html

Ruby: Marshal.dump(obj)
来源：http://dali.cqqwz.cn/Article/details/gtqqpoorpc.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yangfankeji.com/Article/details/gtepiobguy.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtyydgbewv.html

L. 网络请求
来源：http://dali.jqgufenzy.top/Article/details/gtifvrytgy.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtwmuzgqab.html

[L01] 发送 GET 请求
来源：http://dali.xinyue.icu/Article/details/gtkjknmsmx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shanyushiyangtech.top/Article/details/gtajpwccgb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.andypj.xyz/Article/details/gtyykrpsek.html

JS:   await fetch(url)
来源：http://dali.yueranfly.top/Article/details/gtrcpilktz.html

TS:   await fetch(url)
来源：http://dali.yuxming.cn/Article/details/gtzpglpyhs.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zdqjudy.top/Article/details/gtxzrhvyfy.html

Go:   resp, err := http.Get(url)
来源：http://dali.sweek.top/Article/details/gtgxdibjma.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkgmkrulu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ybcxt.top/Article/details/gtlqvyxcey.html

[L02] 发送 POST JSON
来源：http://dali.sweek.top/Article/details/gtbpycbzdq.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hysaishi.cn/Article/details/gtllyefyxq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jyoumei.cn/Article/details/gtfsxcxtjj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.snrcjt.cn/Article/details/gterlxiykz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xylfe.cn/Article/details/gthggpvdht.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.vqdsnc.cn/Article/details/gthuppguuy.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.fengsongda.top/Article/details/gtnpfniavb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yangfankeji.com/Article/details/gtfwcqdiif.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hammf.cn/Article/details/gtjrkoreuj.html

[L03] 设置自定义请求头
来源：http://dali.9152youxi.cn/Article/details/gtpffvlwja.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xuanzx.com/Article/details/gtjfncgigd.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.nanxuanxn.top/Article/details/gtvfmofsil.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shangyingyoupin.top/Article/details/gtivjvamhf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjcxfeenk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xylfe.cn/Article/details/gtnkfylava.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.pengpengdd.cyou/Article/details/gtmozjivym.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenzaomai.com/Article/details/gtvrpbiojf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sxryk.cn/Article/details/gtpptonsnr.html

[L04] 设置超时
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgcvpkbju.html

Py:   requests.get(url, timeout=5)
来源：http://dali.aibaodan.cn/Article/details/gtlsuhahsu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sweek.top/Article/details/gtiaqvpwmg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgufenzy.top/Article/details/gtcdoygwiy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dianchejie.cn/Article/details/gtbokdvnyv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jlsjyb.cn/Article/details/gthukepnpl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.daxiang520.top/Article/details/gtaqzznnsg.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cashguo.top/Article/details/gtfkzzfzfm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gzhubu.top/Article/details/gttgfaeegg.html

[L05] 上传文件（multipart）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbhkcadsz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.tianlin.xyz/Article/details/gtkskgzqxc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ydzc1.top/Article/details/gtmzjavbkr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuxming.cn/Article/details/gttdlyvsml.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.feifeiyinyue.top/Article/details/gtgxnuyxqu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.haohaochexian.top/Article/details/gtkkgcfmup.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinqigfzy.top/Article/details/gtbnpqvnla.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.vqdsnc.cn/Article/details/gtkjcmnrtz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtyffzkopc.html

[L06] 解析响应为 JSON
来源：http://dali.guannengcc.top/Article/details/gtqfxnpflj.html

Py:   resp.json()
来源：http://dali.xuanzx.com/Article/details/gtnkoifyyr.html

PHP:  json_decode($body, true);
来源：http://dali.birdmap.top/Article/details/gtkeleytqo.html

JS:   await resp.json()
来源：http://dali.vqdsnc.cn/Article/details/gthkgbcgko.html

TS:   await resp.json()
来源：http://dali.dianchejie.cn/Article/details/gtwtrklvwf.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.snrcjt.cn/Article/details/gtnwaafmay.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.mhx1999.top/Article/details/gtoqcbuqkz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.chenlongwang.top/Article/details/gtwavihfkm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.kuanghao11.cn/Article/details/gtifzmwbxg.html

[L07] 处理 HTTP 状态码
来源：http://dali.c1oappe.top/Article/details/gtphldsqru.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhoulong.xyz/Article/details/gtjrcphxdj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zdqjudy.top/Article/details/gtkvskghkb.html

JS:   resp.ok;  resp.status
来源：http://dali.redwolf501.top/Article/details/gtyeitkwnr.html

TS:   resp.ok;  resp.status
来源：http://dali.fzhhl.top/Article/details/gtbasjvsox.html

Java: resp.statusCode()
来源：http://dali.gotoacloud.top/Article/details/gtrrsfcprm.html

Go:   resp.StatusCode
来源：http://dali.bjfxy.top/Article/details/gtawfqffrg.html

Ruby: resp.code.to_i
来源：http://dali.jiagoushi.top/Article/details/gtyimjvvot.html

C#:   (int)resp.StatusCode
来源：http://dali.xuanzx.com/Article/details/gtmocfeyzj.html

[L08] 并发请求多个地址
来源：http://dali.jyoumei.cn/Article/details/gtdqsflluw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.c1oappe.top/Article/details/gtxhqpkepx.html

PHP:  curl_multi_init() 系列
来源：http://dali.ehwqpu.com/Article/details/gtymxnfmgi.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yvedp.cn/Article/details/gtofngtfbo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtifylvqmc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.dashuyun.cn/Article/details/gtdqskqgct.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gotoacloud.top/Article/details/gtlksjgjpf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhengqikj.top/Article/details/gtvqcmvtvr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zycfv.cn/Article/details/gtrfqcedax.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtixtnyjug.html

M. 命令行 / 进程 / 环境
来源：http://dali.fzhhl.top/Article/details/gteblhogkj.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtncdnhdtp.html

[M01] 读取命令行参数
来源：http://dali.yangfankeji.com/Article/details/gthoivrhws.html

Py:   sys.argv[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gtgbyhtxep.html

PHP:  $argv;  $argc;
来源：http://dali.iojbl.cn/Article/details/gtnbtuleyb.html

JS:   process.argv.slice(2)
来源：http://dali.jinqigfzy.top/Article/details/gtdipohgxm.html

TS:   process.argv.slice(2)
来源：http://dali.shuidangran.top/Article/details/gtawcqbgbt.html

Java: args 数组（main 方法参数）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuhfemuog.html

Go:   os.Args[1:]
来源：http://dali.jiagoushi.top/Article/details/gthrovbmrg.html

Ruby: ARGV
来源：http://dali.shuidangran.top/Article/details/gtihyekntd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.tanke756.top/Article/details/gtytkingfe.html

[M02] 读取环境变量
来源：http://dali.sweek.top/Article/details/gtdfayddie.html

Py:   os.environ.get("HOME")
来源：http://dali.birdmap.top/Article/details/gtielphzvk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj202588.top/Article/details/gtrnybbaqm.html

JS:   process.env.HOME
来源：http://dali.xuetiantiany.cn/Article/details/gteetbagaw.html

TS:   process.env.HOME
来源：http://dali.xziqi.cn/Article/details/gttlobhldg.html

Java: System.getenv("HOME")
来源：http://dali.hywenlv.cn/Article/details/gtimaypenj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yvedp.cn/Article/details/gtpmmlqixi.html

Ruby: ENV["HOME"]
来源：http://dali.aizwys.cn/Article/details/gtcnrtoaaa.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zycfv.cn/Article/details/gtlmebnkkt.html

[M03] 执行外部命令
来源：http://dali.tian-w.cn/Article/details/gtirmvkvik.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xziqi.cn/Article/details/gthzlqixsu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hywenlv.cn/Article/details/gttfrfwqxt.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yanxiufei.cn/Article/details/gtyolobqii.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuanzhike.top/Article/details/gtjzokbcyo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yanxiufei.cn/Article/details/gtodacdful.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgwqzxfyn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hfpthk.cn/Article/details/gtccnnhrbp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sufxvd.cn/Article/details/gtvjnuziof.html

[M04] 获取当前工作目录
来源：http://dali.yuanzhike.top/Article/details/gthhdexwkw.html

Py:   os.getcwd()
来源：http://dali.pycfn.com/Article/details/gtbwjrwjsa.html

PHP:  getcwd();
来源：http://dali.daxiang520.top/Article/details/gtgqbaufiy.html

JS:   process.cwd()
来源：http://dali.chenzaomai.com/Article/details/gtkdtqmtja.html

TS:   process.cwd()
来源：http://dali.wangdashe.top/Article/details/gthnhoawsx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.aizwys.cn/Article/details/gtppzmeabk.html

Go:   os.Getwd()
来源：http://dali.shuidangran.top/Article/details/gthirakbgb.html

Ruby: Dir.pwd
来源：http://dali.tanke756.top/Article/details/gtyzzbvdnc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.mhx1999.top/Article/details/gtxigoiatf.html

[M05] 设置退出码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaypdwhlm.html

Py:   sys.exit(1)
来源：http://dali.yvedp.cn/Article/details/gtobqyxwzl.html

PHP:  exit(1);
来源：http://dali.guannengcc.top/Article/details/gtzhbjbtry.html

JS:   process.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtdkkcvryn.html

TS:   process.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtvgikraoj.html

Java: System.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gtdivgmaog.html

Go:   os.Exit(1)
来源：http://dali.cheryme.top/Article/details/gtomvqkrog.html

Ruby: exit 1
来源：http://dali.yangfankeji.com/Article/details/gtyonwgnap.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.meibo888.top/Article/details/gtuliasvle.html

[M06] 向标准错误输出
来源：http://dali.quarkkingdee.top/Article/details/gtfabncssf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gaohongyu789.top/Article/details/gtttdarqlm.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jlsjyb.cn/Article/details/gtdoqzcklk.html

JS:   console.error("err")
来源：http://dali.yj20258.top/Article/details/gttkxbotzn.html

TS:   console.error("err")
来源：http://dali.pycfn.com/Article/details/gtvmdtglef.html

Java: System.err.println("err")
来源：http://dali.guowangkeji.top/Article/details/gtdctfemua.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cqqwz.cn/Article/details/gtwycvundu.html

Ruby: warn "err"
来源：http://dali.yuanzhike.top/Article/details/gtfvvpdymz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.iojbl.cn/Article/details/gtvghjryca.html

[M07] 判断是否为主入口
来源：http://dali.gzhubu.top/Article/details/gtbkhwhxsc.html

Py:   if __name__ == "__main__":
来源：http://dali.zhixingplan.top/Article/details/gtolvcvkhv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.aibaodan.cn/Article/details/gtqonoabzd.html

JS:   require.main === module
来源：http://dali.vqdsnc.cn/Article/details/gtzbzbgfej.html

TS:   require.main === module
来源：http://dali.pengpengdd.cyou/Article/details/gtliwnpnpo.html

Java: public static void main(String[] args)
来源：http://dali.redwolf501.top/Article/details/gtskwhugsi.html

Go:   func main()
来源：http://dali.haohaochexian.top/Article/details/gtlpjgkjkw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.guowangkeji.top/Article/details/gtskiraqql.html

C#:   static void Main(string[] args)
来源：http://dali.shuidangran.top/Article/details/gtbyjrtbim.html

[M08] 获取系统与运行时信息
来源：http://dali.hnxiangtu.top/Article/details/gtzuntcvxb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sufxvd.cn/Article/details/gttngifhkl.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.andypj.xyz/Article/details/gtdnutszzg.html

JS:   process.platform;  process.version
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthafmkpti.html

TS:   process.platform;  process.version
来源：http://dali.jinqigfzy.top/Article/details/gtojcrilib.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.havefunace.top/Article/details/gtnisovnxz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hysaishi.cn/Article/details/gtidtxbabe.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhixingplan.top/Article/details/gtiiucyogt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tian-w.cn/Article/details/gtwlgafcrj.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gthcpbyxoc.html

N. 数据结构与算法
来源：http://dali.bjfxy.top/Article/details/gtcovrrhan.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtczvhlgnk.html

[N01] 二分查找（有序数组）
来源：http://dali.feifeiyinyue.top/Article/details/gtccebuxqh.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtnilcnziu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqjmzyssx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gotoacloud.top/Article/details/gtpberjppv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxinkj.top/Article/details/gtrubhnobz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmivbbgfd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtcgttioar.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gzhubu.top/Article/details/gtmooagwma.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtduqfbncn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhiwuduotai.top/Article/details/gtepwdxfjd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gogol.net.cn/Article/details/gtcheltrua.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cqqwz.cn/Article/details/gtbbvbmovb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yonumen.top/Article/details/gtztolqrlx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhongyouzk.top/Article/details/gtejmrnrpi.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfnxjrxke.html

Go:   slices.Sort(arr)
来源：http://dali.yangfankeji.com/Article/details/gtodsusnuk.html

Ruby: arr.sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gteuqdfnzm.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.aizwys.cn/Article/details/gtumzvconr.html

[N03] 快速排序（分治示例）
来源：http://dali.cdnleiting.top/Article/details/gtbkzllpwh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jiagoushi.top/Article/details/gtbxtonqre.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shanyushiyangtech.top/Article/details/gtvganihdw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cqqwz.cn/Article/details/gtnasfdsdc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangtech.top/Article/details/gtbhfvzdiu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gtzbgdpocl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sweek.top/Article/details/gthcsyurxl.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.daria6918.cn/Article/details/gtosnfyvow.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.smart0.xyz/Article/details/gtmjhlprey.html

[N04] 斐波那契数列
来源：http://dali.shuidangran.top/Article/details/gtjpeumvdg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xylfe.cn/Article/details/gtzowkkixy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhongyouzk.top/Article/details/gtvupwvnzd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnxiangtu.top/Article/details/gtlrpowtre.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gtdcsbpiiy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ivvv.top/Article/details/gtkpaczosp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.aibaodan.cn/Article/details/gtfjrgfwcd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.smart0.xyz/Article/details/gtnxcauuuc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj20258888.top/Article/details/gtxfxvxucn.html

[N05] 最大公约数
来源：http://dali.hnqzz.top/Article/details/gtxpuwkvnu.html

Py:   math.gcd(a, b)
来源：http://dali.0kj1m.cn/Article/details/gtqzatsuba.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xinyue.icu/Article/details/gtpynmzckx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.redwolf501.top/Article/details/gtplrpwekn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtwswwnwgt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.9152youxi.cn/Article/details/gtqhaqfbwj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yueranfly.top/Article/details/gtveftbrjn.html

Ruby: a.gcd(b)
来源：http://dali.sxryk.cn/Article/details/gtslxwddtl.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gtmlvrsjrr.html

[N06] 判断回文字符串
来源：http://dali.cqqwz.cn/Article/details/gtddxhtgkk.html

Py:   s == s[::-1]
来源：http://dali.daxiang520.top/Article/details/gttjnonbjj.html

PHP:  $s === strrev($s);
来源：http://dali.nanxuanxn.top/Article/details/gtmtilfweh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gtnekmvsdm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwplvuygf.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hywenlv.cn/Article/details/gtvcvuqduy.html

Go:   // 双指针从两端比较
来源：http://dali.ydzc1.top/Article/details/gtzleifdcy.html

Ruby: s == s.reverse
来源：http://dali.gzhubu.top/Article/details/gtcgplnsfn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.dianchejie.cn/Article/details/gtwwkzxfpd.html

[N07] 两数之和（返回下标）
来源：http://dali.nwbrower.top/Article/details/gtmzcijakm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yueranfly.top/Article/details/gtsjttlroz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.tianlin.xyz/Article/details/gtzacmxirw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.aizwys.cn/Article/details/gtcenzlzkv.html

TS:   // 手写 Map<string, number>
来源：http://dali.fengsongda.top/Article/details/gtuzphcfrh.html

Java: // 手写 HashMap
来源：http://dali.hfpthk.cn/Article/details/gtbpddveqs.html

Go:   // 手写 map[int]int
来源：http://dali.shzxlz.cn/Article/details/gtbcgkqyfy.html

Ruby: // 手写 Hash
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqthxzmjx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.smart0.xyz/Article/details/gtppnoepyy.html

[N08] 生成全排列
来源：http://dali.nwbrower.top/Article/details/gtfbmlnzta.html

Py:   itertools.permutations(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtomokauch.html

PHP:  // 手写递归交换
来源：http://dali.chenlongwang.top/Article/details/gtzxvvyonl.html

JS:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gtuumtbxie.html

TS:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtxnhvqnes.html

Java: // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtsausroph.html

Go:   // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gtiyxqxvwi.html

Ruby: arr.permutation.to_a
来源：http://dali.xinyue.icu/Article/details/gtystgoajg.html

C#:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtbblgahbg.html

[N09] 栈与队列
来源：http://dali.9152youxi.cn/Article/details/gthmlryxas.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.havefunace.top/Article/details/gtllfbbxfn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.pycfn.com/Article/details/gtowjmlsnr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.tian-w.cn/Article/details/gtemydimjr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.guannengcc.top/Article/details/gttcjfystz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.guowangkeji.top/Article/details/gtofcvdpvb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hnqzz.top/Article/details/gtkexjqidw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gaohongyu789.top/Article/details/gtgjlkhuxq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hysaishi.cn/Article/details/gthjscntfv.html

[N10] 链表节点定义
来源：http://dali.pycfn.com/Article/details/gtpcpsjodp.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.redwolf501.top/Article/details/gtyfrxqcxl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gaohongyu789.top/Article/details/gtxaatsofy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.dianchejie.cn/Article/details/gtjhypjgcq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sysykeji.top/Article/details/gtlmbdoxjm.html

Java: class Node { int v; Node next; }
来源：http://dali.jqgfzy.top/Article/details/gtoauhcsxb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hammf.cn/Article/details/gtgwcwdavq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.aibaodan.cn/Article/details/gtqcdlsuue.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.nanxinkj.top/Article/details/gtrlidljqp.html

[N11] 二叉树中序遍历
来源：http://dali.yuanzhike.top/Article/details/gtnkyogkrz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.snrcjt.cn/Article/details/gtmfeuzoio.html

PHP:  // 手写递归函数
来源：http://dali.sxryk.cn/Article/details/gtgalvcjdf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daxiang520.top/Article/details/gtbwypdzhi.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnqzz.top/Article/details/gtqcrtpzqt.html

Java: // 手写递归
来源：http://dali.dashuyun.cn/Article/details/gtkdesaffn.html

Go:   // 手写递归
来源：http://dali.cucudq.cn/Article/details/gtflhndlcy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yuanzhike.top/Article/details/gtzizulenu.html

C#:   // 手写递归
来源：http://dali.haohaochexian.top/Article/details/gtjbyizect.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cqqwz.cn/Article/details/gtqmlbhwso.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shzxlz.cn/Article/details/gttcjzwkvh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.pycfn.com/Article/details/gtnrzfuxiu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sxryk.cn/Article/details/gtbnbqqpff.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ehwqpu.com/Article/details/gtwipbdtck.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cucudq.cn/Article/details/gtitkoxftb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gtargtkxql.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yongpay.top/Article/details/gtmjhdkjwc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cucudq.cn/Article/details/gtzsvhzrti.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtdsuangyd.html

O. 并发与异步
来源：http://dali.jinqigufen.top/Article/details/gtsxpnhrbj.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtyznqvovs.html

[O01] 启动一个线程
来源：http://dali.sxryk.cn/Article/details/gtwnjntfcx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jyoumei.cn/Article/details/gtksfpntpu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.chenzaomai.com/Article/details/gteumffzvk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cucudq.cn/Article/details/gtatdzuace.html

TS:   // 同 JS
来源：http://dali.tianlin.xyz/Article/details/gtcwhvyztx.html

Java: new Thread(() -> f()).start()
来源：http://dali.aizwys.cn/Article/details/gthuctegqd.html

Go:   go f()
来源：http://dali.svipenyu.cn/Article/details/gtsunpycsy.html

Ruby: Thread.new { f }
来源：http://dali.gotoacloud.top/Article/details/gteujgmsux.html

C#:   Task.Run(() => F());
来源：http://dali.iojbl.cn/Article/details/gtbtqbtica.html

[O02] 使用线程池
来源：http://dali.zhongyouzk.top/Article/details/gtbfwjllph.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hammf.cn/Article/details/gtlgxqcjtx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hywenlv.cn/Article/details/gtspdypsmc.html

JS:   // worker_threads 线程池
来源：http://dali.ybcxt.top/Article/details/gtnlhalhxt.html


<!-- 参考信息 -->