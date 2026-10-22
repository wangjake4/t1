代发 wailian999

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hnqzz.top/Article/details/gtretjwdzr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.daxiang520.top/Article/details/gtluctfyqa.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.tianlin.xyz/Article/details/gtdwtpkrpg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hnqzz.top/Article/details/gtgebawbea.html

[K06] 解析 URL 查询串
来源：http://dali.hywenlv.cn/Article/details/gtbsqfytvf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.smart0.xyz/Article/details/gtugwxswbw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shzxlz.cn/Article/details/gtgylpsxzv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gaohongyu789.top/Article/details/gtgrvsvfdi.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.316326.xyz/Article/details/gtzvmkjyfq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hnqzz.top/Article/details/gtuomdtnda.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.daria6918.cn/Article/details/gtbctwztnd.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yanxiufei.cn/Article/details/gtdtgfbzks.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jqgufenzy.top/Article/details/gtgkktwdhb.html

[K07] 进制转换
来源：http://dali.tanke756.top/Article/details/gtlthsaucd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtsxlaecee.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yuanzhike.top/Article/details/gtinaesyue.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtvpptwmuq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gtxkrdbkwm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtbfbfefkg.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hnxiangtu.top/Article/details/gtxmzdherg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.mhx1999.top/Article/details/gtozkqemfy.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtttlzexdm.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jyoumei.cn/Article/details/gtbmzodtlm.html

Py:   pickle.dumps(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtdcuropnk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.aibaodan.cn/Article/details/gtrbzufxok.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xylfe.cn/Article/details/gtqehjzfmg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.snrcjt.cn/Article/details/gtlytqsery.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.nwbrower.top/Article/details/gtpwvkppgt.html

Go:   encoding/gob
来源：http://dali.yuxming.cn/Article/details/gtgkmnsrex.html

Ruby: Marshal.dump(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gthlhktaqn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.9152youxi.cn/Article/details/gttmgvlqbu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtgbptcgxk.html

L. 网络请求
来源：http://dali.cucudq.cn/Article/details/gtqvdasjnf.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtdovsmwsg.html

[L01] 发送 GET 请求
来源：http://dali.jiagoushi.top/Article/details/gtzkpjzres.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.snrcjt.cn/Article/details/gtmyjzzehm.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yueranfly.top/Article/details/gtgfpfmeeb.html

JS:   await fetch(url)
来源：http://dali.yuxming.cn/Article/details/gtafmqooyt.html

TS:   await fetch(url)
来源：http://dali.c1oappe.top/Article/details/gtmwjibjfq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yueranfly.top/Article/details/gtrxknsufy.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhixingplan.top/Article/details/gtwunwfwxo.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xuetiantiany.cn/Article/details/gtliirhakf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jqgufenzy.top/Article/details/gtciiupwmu.html

[L02] 发送 POST JSON
来源：http://dali.jqgufenzy.top/Article/details/gtfrusejub.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ppjwa.cn/Article/details/gtovejkalr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cucudq.cn/Article/details/gtlievjjun.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yongpay.top/Article/details/gtimzxrpwb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ivvv.top/Article/details/gtupykdomj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gotoacloud.top/Article/details/gtbgovekrz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcdimmave.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ybcxt.top/Article/details/gtptdvsbyv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.tanke756.top/Article/details/gtgvprcuud.html

[L03] 设置自定义请求头
来源：http://dali.havefunace.top/Article/details/gtmkbbzdqe.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hysaishi.cn/Article/details/gtbnkfjpiw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jqgfzy.top/Article/details/gtxnjeihhs.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hammf.cn/Article/details/gtfdiiszcy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gogol.net.cn/Article/details/gtjzcknrih.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gzhubu.top/Article/details/gtnchjjxoc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.chenjidiqi.icu/Article/details/gtnmnpkrjj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ppjwa.cn/Article/details/gthfjdtmpk.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.9152youxi.cn/Article/details/gtpoyzxcgo.html

[L04] 设置超时
来源：http://dali.hysaishi.cn/Article/details/gtdhkuzhzj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hysaishi.cn/Article/details/gtskucgtyz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ppjwa.cn/Article/details/gtphulsnsg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtunurlavs.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tianlin.xyz/Article/details/gtknkwfxac.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jyoumei.cn/Article/details/gtfiekmuvt.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhengqikj.top/Article/details/gtjldqsqfb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj20258.top/Article/details/gtqexqikyb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhoulong.xyz/Article/details/gtbqrkiuey.html

[L05] 上传文件（multipart）
来源：http://dali.zhengqikj.top/Article/details/gtyscrfeoy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.meibo888.top/Article/details/gttxgzwmhv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hnqzz.top/Article/details/gtdrcvnqqa.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.0kj1m.cn/Article/details/gtykzoftup.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ppjwa.cn/Article/details/gtmreynvkv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gotoacloud.top/Article/details/gtvldmxjtf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzwbbvtce.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.aizwys.cn/Article/details/gtfgzegblz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtsciouxbu.html

[L06] 解析响应为 JSON
来源：http://dali.jinghuilouyu.cn/Article/details/gtpzygpnsd.html

Py:   resp.json()
来源：http://dali.yanxiufei.cn/Article/details/gtazaiubuj.html

PHP:  json_decode($body, true);
来源：http://dali.cdnleiting.top/Article/details/gtkaqxqthm.html

JS:   await resp.json()
来源：http://dali.nwbrower.top/Article/details/gteqlzgern.html

TS:   await resp.json()
来源：http://dali.ybcxt.top/Article/details/gtoqwaygaj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gtjzizoivv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhoulong.xyz/Article/details/gtrvrmisqf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zycfv.cn/Article/details/gtsnymnxwa.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jqgufenzy.top/Article/details/gttlpxmqnp.html

[L07] 处理 HTTP 状态码
来源：http://dali.chenzaomai.com/Article/details/gttpyaexot.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yvedp.cn/Article/details/gtxjmsbfsx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hongshengwenyu.top/Article/details/gttcxfaclm.html

JS:   resp.ok;  resp.status
来源：http://dali.dianchejie.cn/Article/details/gtlzetbzuv.html

TS:   resp.ok;  resp.status
来源：http://dali.jinghuilouyu.cn/Article/details/gtkmckllfi.html

Java: resp.statusCode()
来源：http://dali.zhixingplan.top/Article/details/gtrmbmuaul.html

Go:   resp.StatusCode
来源：http://dali.shuidangran.top/Article/details/gtuulrcpym.html

Ruby: resp.code.to_i
来源：http://dali.gaohongyu789.top/Article/details/gtneeamcve.html

C#:   (int)resp.StatusCode
来源：http://dali.chenzaomai.com/Article/details/gtdognuztw.html

[L08] 并发请求多个地址
来源：http://dali.yonumen.top/Article/details/gtqayekdbv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.0kj1m.cn/Article/details/gttnmlceyb.html

PHP:  curl_multi_init() 系列
来源：http://dali.hongshengwenyu.top/Article/details/gteijvtkzb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gtemgeewff.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj202588.top/Article/details/gtepxebrtr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ehwqpu.com/Article/details/gtdmegecdn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfeybrlvr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yvedp.cn/Article/details/gtvqapbalr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.haohaochexian.top/Article/details/gtfqbhdnof.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtmdwbwpsr.html

M. 命令行 / 进程 / 环境
来源：http://dali.c1oappe.top/Article/details/gteynkhmxg.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtttyigtbo.html

[M01] 读取命令行参数
来源：http://dali.chenlongwang.top/Article/details/gtsxmfidrk.html

Py:   sys.argv[1:]
来源：http://dali.mhx1999.top/Article/details/gtcqtdreoi.html

PHP:  $argv;  $argc;
来源：http://dali.jlsjyb.cn/Article/details/gtiuhgmzmx.html

JS:   process.argv.slice(2)
来源：http://dali.shangyingyoupin.top/Article/details/gtefvqnexv.html

TS:   process.argv.slice(2)
来源：http://dali.shuidangran.top/Article/details/gtjocegagl.html

Java: args 数组（main 方法参数）
来源：http://dali.cashguo.top/Article/details/gtssftkjpz.html

Go:   os.Args[1:]
来源：http://dali.9152youxi.cn/Article/details/gtcwnybvjt.html

Ruby: ARGV
来源：http://dali.xinyue.icu/Article/details/gtuyebrycw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gogol.net.cn/Article/details/gtzsnrozkc.html

[M02] 读取环境变量
来源：http://dali.sufxvd.cn/Article/details/gtoispmddm.html

Py:   os.environ.get("HOME")
来源：http://dali.sufxvd.cn/Article/details/gtsfywubqj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hongshengwenyu.top/Article/details/gtatfkwnwj.html

JS:   process.env.HOME
来源：http://dali.jlsjyb.cn/Article/details/gtvrfctwfm.html

TS:   process.env.HOME
来源：http://dali.iojbl.cn/Article/details/gtlbruzmbx.html

Java: System.getenv("HOME")
来源：http://dali.hammf.cn/Article/details/gtdythypbh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yuxming.cn/Article/details/gtohkagzup.html

Ruby: ENV["HOME"]
来源：http://dali.meibo888.top/Article/details/gtkyuzukfe.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gtxreownif.html

[M03] 执行外部命令
来源：http://dali.gogol.net.cn/Article/details/gtmddxxniq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.havefunace.top/Article/details/gtqnnfzdkx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nanxuanxn.top/Article/details/gtzdzhknej.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zdqjudy.top/Article/details/gtapybjazx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.bjfxy.top/Article/details/gtllfrvigp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hnxiangtu.top/Article/details/gtaoisxdlh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tanke756.top/Article/details/gtjukxkssx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenzaomai.com/Article/details/gtmtofiqej.html

C#:   Process.Start("ls", "-l");
来源：http://dali.pengpengdd.cyou/Article/details/gtwzumpqae.html

[M04] 获取当前工作目录
来源：http://dali.wangdashe.top/Article/details/gtkqyqfyby.html

Py:   os.getcwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqsxzazfz.html

PHP:  getcwd();
来源：http://dali.quarkkingdee.top/Article/details/gtoxptfryy.html

JS:   process.cwd()
来源：http://dali.tanke756.top/Article/details/gthjkhwnxp.html

TS:   process.cwd()
来源：http://dali.cucudq.cn/Article/details/gtlzfaeqay.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cheryme.top/Article/details/gtjnvjmhbz.html

Go:   os.Getwd()
来源：http://dali.haohaochexian.top/Article/details/gtvhzpuogg.html

Ruby: Dir.pwd
来源：http://dali.guowangkeji.top/Article/details/gtczwqxkjs.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.pycfn.com/Article/details/gtmfdmvkpg.html

[M05] 设置退出码
来源：http://dali.hammf.cn/Article/details/gtpaginokc.html

Py:   sys.exit(1)
来源：http://dali.meibo888.top/Article/details/gtidgckpeu.html

PHP:  exit(1);
来源：http://dali.chenzaomai.com/Article/details/gtunoxasuq.html

JS:   process.exit(1)
来源：http://dali.havefunace.top/Article/details/gtgndmavmx.html

TS:   process.exit(1)
来源：http://dali.xziqi.cn/Article/details/gtgktxbdnv.html

Java: System.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtimnallvz.html

Go:   os.Exit(1)
来源：http://dali.tanke756.top/Article/details/gtmzytmqqo.html

Ruby: exit 1
来源：http://dali.nanxinkj.top/Article/details/gtcgenimwo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gaohongyu789.top/Article/details/gtatkzfpak.html

[M06] 向标准错误输出
来源：http://dali.yvedp.cn/Article/details/gtjzdkbnor.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiryrghjc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nanxuanxn.top/Article/details/gtuvezykic.html

JS:   console.error("err")
来源：http://dali.svipenyu.cn/Article/details/gtrfbzezaj.html

TS:   console.error("err")
来源：http://dali.redwolf501.top/Article/details/gtlinlaaup.html

Java: System.err.println("err")
来源：http://dali.yueranfly.top/Article/details/gtgknlfrrw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.daria6918.cn/Article/details/gtkscsnymx.html

Ruby: warn "err"
来源：http://dali.cucudq.cn/Article/details/gtecxwinau.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhongyouzk.top/Article/details/gtcfscivjl.html

[M07] 判断是否为主入口
来源：http://dali.jiagoushi.top/Article/details/gtuyxlhcxv.html

Py:   if __name__ == "__main__":
来源：http://dali.hysaishi.cn/Article/details/gtdlkioiaa.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jianghu66.top/Article/details/gthembumsb.html

JS:   require.main === module
来源：http://dali.chenjidiqi.icu/Article/details/gtyrdxxquh.html

TS:   require.main === module
来源：http://dali.daxiang520.top/Article/details/gtltaynmfm.html

Java: public static void main(String[] args)
来源：http://dali.daxiang520.top/Article/details/gttfuujdpl.html

Go:   func main()
来源：http://dali.kuanghao11.cn/Article/details/gtnaqchtpc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenlongwang.top/Article/details/gtmukvwblu.html

C#:   static void Main(string[] args)
来源：http://dali.bjfxy.top/Article/details/gtwpdtewat.html

[M08] 获取系统与运行时信息
来源：http://dali.andypj.xyz/Article/details/gtjaizgkeh.html

Py:   platform.system();  platform.python_version()
来源：http://dali.dianchejie.cn/Article/details/gtwyjnofld.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.smart0.xyz/Article/details/gtcnqjcmlc.html

JS:   process.platform;  process.version
来源：http://dali.zhiwuduotai.top/Article/details/gtjeruzzvx.html

TS:   process.platform;  process.version
来源：http://dali.hfpthk.cn/Article/details/gtscwqvywc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinqigufen.top/Article/details/gtmvdeyrzj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj202588.top/Article/details/gtfsrilkyq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yvedp.cn/Article/details/gtfcanodkn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hywenlv.cn/Article/details/gtzzaomxkx.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtplzsubnl.html

N. 数据结构与算法
来源：http://dali.haohaochexian.top/Article/details/gthyzywbql.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtqtmqdjdn.html

[N01] 二分查找（有序数组）
来源：http://dali.hfpthk.cn/Article/details/gtjfvzajbn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtfuumpyby.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jlsjyb.cn/Article/details/gtkhkcnjbi.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hfpthk.cn/Article/details/gtadhwijxo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gtsiqhsoly.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtfvkxjfwy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gttmkryqmp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.svipenyu.cn/Article/details/gtnyhsebva.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gthgubeuxv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.havefunace.top/Article/details/gtlpnfiyan.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.guowangkeji.top/Article/details/gtnrnjpyrg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.mhx1999.top/Article/details/gtqfolhaeb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.quarkkingdee.top/Article/details/gtrdbtpcfb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxuanxn.top/Article/details/gtwlqznzct.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.fengsongda.top/Article/details/gtjwhnpyce.html

Go:   slices.Sort(arr)
来源：http://dali.yangfankeji.com/Article/details/gtnwbrqjfy.html

Ruby: arr.sort
来源：http://dali.yuanzhike.top/Article/details/gtyqhqtsgk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.smart0.xyz/Article/details/gtkckgoiod.html

[N03] 快速排序（分治示例）
来源：http://dali.cucudq.cn/Article/details/gtuybnwoyg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj20258888.top/Article/details/gtawbcdwmr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ppjwa.cn/Article/details/gtrhdrzwfl.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jlsjyb.cn/Article/details/gtgossucut.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuanzx.com/Article/details/gthlxbcmsr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sysykeji.top/Article/details/gtvexkmegp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yueranfly.top/Article/details/gtpswaslht.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ydzc1.top/Article/details/gtvvdidgxg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hysaishi.cn/Article/details/gttdenofdk.html

[N04] 斐波那契数列
来源：http://dali.yj20258888.top/Article/details/gtfwvjvwna.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.9152youxi.cn/Article/details/gtkomgcuxv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gzhubu.top/Article/details/gtjplsqskp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangdashe.top/Article/details/gtfnwwbowa.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.snrcjt.cn/Article/details/gtiamdecca.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.tianlin.xyz/Article/details/gtsfnymebi.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinqigfzy.top/Article/details/gtlayzgvfe.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.tian-w.cn/Article/details/gtjefdnzod.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cashguo.top/Article/details/gtodjfyqam.html

[N05] 最大公约数
来源：http://dali.guowangkeji.top/Article/details/gtchudacce.html

Py:   math.gcd(a, b)
来源：http://dali.zycfv.cn/Article/details/gtxojfwdor.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqxfdfwka.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtkkfamkki.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.haohaochexian.top/Article/details/gtefjtyamc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shanyushiyangtech.top/Article/details/gtzdaobnzp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.haohaochexian.top/Article/details/gtbwqdzjgk.html

Ruby: a.gcd(b)
来源：http://dali.xuanzx.com/Article/details/gtcxrclgiu.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.dianchejie.cn/Article/details/gticcgziob.html

[N06] 判断回文字符串
来源：http://dali.jinqigfzy.top/Article/details/gtuqivzbvc.html

Py:   s == s[::-1]
来源：http://dali.fzhhl.top/Article/details/gtykyzkeqy.html

PHP:  $s === strrev($s);
来源：http://dali.zhoulong.xyz/Article/details/gthfziikut.html

JS:   s === [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gtucqtlegv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ydzc1.top/Article/details/gtzopkmjgf.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jyoumei.cn/Article/details/gtjpaogzzr.html

Go:   // 双指针从两端比较
来源：http://dali.pycfn.com/Article/details/gtvlsiymcg.html

Ruby: s == s.reverse
来源：http://dali.bjfxy.top/Article/details/gtxrpwkrkq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gzhubu.top/Article/details/gtiadwmukj.html

[N07] 两数之和（返回下标）
来源：http://dali.yangfankeji.com/Article/details/gthlxqqxwa.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.quarkkingdee.top/Article/details/gtwmuzbhzd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gotoacloud.top/Article/details/gtfcecbpsc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.haohaochexian.top/Article/details/gtasjkebsu.html

TS:   // 手写 Map<string, number>
来源：http://dali.gzhubu.top/Article/details/gtghnkwdjn.html

Java: // 手写 HashMap
来源：http://dali.sweek.top/Article/details/gtosvenvkr.html

Go:   // 手写 map[int]int
来源：http://dali.yanxiufei.cn/Article/details/gtaejhohkh.html

Ruby: // 手写 Hash
来源：http://dali.jqgufenzy.top/Article/details/gtvtmqzvnl.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ybcxt.top/Article/details/gtrcdijppx.html

[N08] 生成全排列
来源：http://dali.jlsjyb.cn/Article/details/gtldggggsl.html

Py:   itertools.permutations(arr)
来源：http://dali.iojbl.cn/Article/details/gtsdyfutht.html

PHP:  // 手写递归交换
来源：http://dali.jinqigfzy.top/Article/details/gtdvtrtcry.html

JS:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gtdsqxxpns.html

TS:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtazvovvgj.html

Java: // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gtugmedqqn.html

Go:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gtnmzjgugk.html

Ruby: arr.permutation.to_a
来源：http://dali.xinyue.icu/Article/details/gtzxkrzxxm.html

C#:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtqmfthtgy.html

[N09] 栈与队列
来源：http://dali.redwolf501.top/Article/details/gtamtxwnec.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yj202588.top/Article/details/gtdawepwne.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.c1oappe.top/Article/details/gtaklsozzm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvvpttzdd.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.guowangkeji.top/Article/details/gtsvkgwhvu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhiwuduotai.top/Article/details/gtxpvospru.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gtktmhwmom.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ppjwa.cn/Article/details/gttpjfjucs.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenzaomai.com/Article/details/gtirebomla.html

[N10] 链表节点定义
来源：http://dali.andypj.xyz/Article/details/gthaywttbn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cashguo.top/Article/details/gteudtvpwm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhixingplan.top/Article/details/gtnxjufpvy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhixingplan.top/Article/details/gthxcyamlw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.9152youxi.cn/Article/details/gtbnjysuwm.html

Java: class Node { int v; Node next; }
来源：http://dali.iojbl.cn/Article/details/gtolbqocxd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sysykeji.top/Article/details/gtmsyuvmxm.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.wangdashe.top/Article/details/gtfuooaqnd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yongpay.top/Article/details/gtbqzrhdva.html

[N11] 二叉树中序遍历
来源：http://dali.gaohongyu789.top/Article/details/gtyptwkvsu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yangfankeji.com/Article/details/gtqkqnuzxt.html

PHP:  // 手写递归函数
来源：http://dali.9152youxi.cn/Article/details/gtzyupgtej.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlzefmccg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhoulong.xyz/Article/details/gtypymwvnz.html

Java: // 手写递归
来源：http://dali.wangshuangyany.cn/Article/details/gtnuoadzhc.html

Go:   // 手写递归
来源：http://dali.gaohongyu789.top/Article/details/gtgmmzlzeb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.aizwys.cn/Article/details/gtdzjwegge.html

C#:   // 手写递归
来源：http://dali.zhongyouzk.top/Article/details/gtnjrqrvrd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.quarkkingdee.top/Article/details/gtuzxzkjrx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zycfv.cn/Article/details/gtxfdrhwbo.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jianghu66.top/Article/details/gtyqzwtzmc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gotoacloud.top/Article/details/gteqsnbnac.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tianlin.xyz/Article/details/gtuekuzrtl.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daxiang520.top/Article/details/gtyndpoxgs.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.fzhhl.top/Article/details/gtogtlmnkq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jqgufenzy.top/Article/details/gtbegryubu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ydzc1.top/Article/details/gtywudalza.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtsukaksif.html

O. 并发与异步
来源：http://dali.shzxlz.cn/Article/details/gtqyrmvkav.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtfdttoqoo.html

[O01] 启动一个线程
来源：http://dali.yanxiufei.cn/Article/details/gtbvitaxno.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xinyue.icu/Article/details/gtothcwsuf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhixingplan.top/Article/details/gtwunkraap.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.mhx1999.top/Article/details/gtemlgrlyt.html

TS:   // 同 JS
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtihvhxadr.html


<!-- 参考信息 -->