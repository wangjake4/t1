代发 wailian999

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gtialasbpe.html

[K07] 进制转换
来源：http://dali.yuxming.cn/Article/details/gtxqmrqiyv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gtnfwxzcow.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hnxiangtu.top/Article/details/gttjuwevwc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gtvlqvtlgq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gtjaxuxyhn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtimfiurxy.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cashguo.top/Article/details/gtugnubfpx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinqigufen.top/Article/details/gttctdwyec.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtbbcqfbud.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.bjfxy.top/Article/details/gtqqnfeeev.html

Py:   pickle.dumps(obj)
来源：http://dali.zycfv.cn/Article/details/gtgdhxpodm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yuanzhike.top/Article/details/gtllwzbrov.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhongyouzk.top/Article/details/gtelwwejgr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gaohongyu789.top/Article/details/gthsmcethk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ydzc1.top/Article/details/gttsvyznrt.html

Go:   encoding/gob
来源：http://dali.chenlongwang.top/Article/details/gtahsotpyl.html

Ruby: Marshal.dump(obj)
来源：http://dali.yj20258.top/Article/details/gthiqmrvpb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sysykeji.top/Article/details/gtgkznqvvf.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtuvecycro.html

L. 网络请求
来源：http://dali.kuanghao11.cn/Article/details/gtoagvwsdn.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtzxmgjsek.html

[L01] 发送 GET 请求
来源：http://dali.wangshuangyany.cn/Article/details/gtkjceeadx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yvedp.cn/Article/details/gthttndsel.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hnqzz.top/Article/details/gtmnvjoiwk.html

JS:   await fetch(url)
来源：http://dali.iojbl.cn/Article/details/gtdzcdoqui.html

TS:   await fetch(url)
来源：http://dali.daria6918.cn/Article/details/gtucbtdhuz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hnqzz.top/Article/details/gthxpuaohm.html

Go:   resp, err := http.Get(url)
来源：http://dali.xylfe.cn/Article/details/gttvdngxma.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.mhx1999.top/Article/details/gtnsnspndm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.fzhhl.top/Article/details/gtdgldqjhr.html

[L02] 发送 POST JSON
来源：http://dali.tanke756.top/Article/details/gtxmoefxeh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gogol.net.cn/Article/details/gtzbmjcegj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gtgwxnacnt.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ybcxt.top/Article/details/gthspywrfh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.meibo888.top/Article/details/gtqcenmxsv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinghuilouyu.cn/Article/details/gtxlqyjttc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cucudq.cn/Article/details/gtpnvzeyps.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.birdmap.top/Article/details/gtxzjgsojg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.mhx1999.top/Article/details/gtclzsckek.html

[L03] 设置自定义请求头
来源：http://dali.9152youxi.cn/Article/details/gtcxzckqtb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sweek.top/Article/details/gtvosyldtl.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jlsjyb.cn/Article/details/gtukgqzslf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtagunilpt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yongpay.top/Article/details/gtdybsfhpv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.dianchejie.cn/Article/details/gtkcppolwo.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.316326.xyz/Article/details/gthmzgnupg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yanxiufei.cn/Article/details/gtgxsxeayf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.guowangkeji.top/Article/details/gtpgxhopzh.html

[L04] 设置超时
来源：http://dali.birdmap.top/Article/details/gtphxqxljb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cashguo.top/Article/details/gtzzkpjrmh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj20258888.top/Article/details/gttacvyrsp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.316326.xyz/Article/details/gtgavowtht.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxinkj.top/Article/details/gtkwsuvogt.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sysykeji.top/Article/details/gtostlyyrq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.guowangkeji.top/Article/details/gtrggfydug.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.bjfxy.top/Article/details/gtohtfbtac.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yvedp.cn/Article/details/gtxpluztmn.html

[L05] 上传文件（multipart）
来源：http://dali.zhengqikj.top/Article/details/gtjsrjdcwd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.tianlin.xyz/Article/details/gtoudsnjfr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zdqjudy.top/Article/details/gtkihshwcy.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gzhubu.top/Article/details/gtiiinyrlx.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yangfankeji.com/Article/details/gtcsmrazkv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.birdmap.top/Article/details/gtoqvjimfw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yvedp.cn/Article/details/gtdwtmxeyu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hysaishi.cn/Article/details/gtwdrkucof.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtpetltxtw.html

[L06] 解析响应为 JSON
来源：http://dali.yanxiufei.cn/Article/details/gtxdyamook.html

Py:   resp.json()
来源：http://dali.pycfn.com/Article/details/gtqppdzlri.html

PHP:  json_decode($body, true);
来源：http://dali.jinghuilouyu.cn/Article/details/gteeonfydt.html

JS:   await resp.json()
来源：http://dali.hnxiangtu.top/Article/details/gtvwcfqosm.html

TS:   await resp.json()
来源：http://dali.chenzaomai.com/Article/details/gtjhnmmfbe.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.dashuyun.cn/Article/details/gtedaqkplm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ydzc1.top/Article/details/gtdipqsiqz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.meibo888.top/Article/details/gtlxomrslb.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.dashuyun.cn/Article/details/gtkypmnjdt.html

[L07] 处理 HTTP 状态码
来源：http://dali.chenlongwang.top/Article/details/gtatitztlo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ydzc1.top/Article/details/gtbwbhbwyx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.c1oappe.top/Article/details/gtevcuykek.html

JS:   resp.ok;  resp.status
来源：http://dali.sxryk.cn/Article/details/gtzrvzzwfb.html

TS:   resp.ok;  resp.status
来源：http://dali.zycfv.cn/Article/details/gthoqwpulp.html

Java: resp.statusCode()
来源：http://dali.yangfankeji.com/Article/details/gtlxxjlxfq.html

Go:   resp.StatusCode
来源：http://dali.c1oappe.top/Article/details/gtroxwwpuw.html

Ruby: resp.code.to_i
来源：http://dali.chenlongwang.top/Article/details/gtcycfihxx.html

C#:   (int)resp.StatusCode
来源：http://dali.yvedp.cn/Article/details/gtmlykmrov.html

[L08] 并发请求多个地址
来源：http://dali.yj20258.top/Article/details/gtkqchrsot.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhiwuduotai.top/Article/details/gtbuotkrip.html

PHP:  curl_multi_init() 系列
来源：http://dali.jyoumei.cn/Article/details/gtrtssamno.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hammf.cn/Article/details/gtfbxmopcs.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cashguo.top/Article/details/gtiwgeouly.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xuetiantiany.cn/Article/details/gtpynzgzkf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.haohaochexian.top/Article/details/gtlqiefstz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yangfankeji.com/Article/details/gtwmgeybsi.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cheryme.top/Article/details/gtjoeutvkh.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtbbiyuyhs.html

M. 命令行 / 进程 / 环境
来源：http://dali.yongpay.top/Article/details/gtojsznjxx.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtwjfiymkc.html

[M01] 读取命令行参数
来源：http://dali.shuidangran.top/Article/details/gtzhteynze.html

Py:   sys.argv[1:]
来源：http://dali.316326.xyz/Article/details/gtwzqefsgo.html

PHP:  $argv;  $argc;
来源：http://dali.xylfe.cn/Article/details/gtownvyedx.html

JS:   process.argv.slice(2)
来源：http://dali.gzhubu.top/Article/details/gtbfrwtgyl.html

TS:   process.argv.slice(2)
来源：http://dali.yongpay.top/Article/details/gtfoiskwro.html

Java: args 数组（main 方法参数）
来源：http://dali.wangdashe.top/Article/details/gtgpuulamc.html

Go:   os.Args[1:]
来源：http://dali.gogol.net.cn/Article/details/gtdotymdcc.html

Ruby: ARGV
来源：http://dali.iojbl.cn/Article/details/gtprtxiumg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zycfv.cn/Article/details/gtnjnmeqhr.html

[M02] 读取环境变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdxpkokkq.html

Py:   os.environ.get("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gtnankqgjr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj202588.top/Article/details/gtrgbonbon.html

JS:   process.env.HOME
来源：http://dali.gogol.net.cn/Article/details/gtizbbsueo.html

TS:   process.env.HOME
来源：http://dali.quarkkingdee.top/Article/details/gtsiaffkod.html

Java: System.getenv("HOME")
来源：http://dali.yuanzhike.top/Article/details/gtfuelcfhm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.meibo888.top/Article/details/gtbzlxyrqd.html

Ruby: ENV["HOME"]
来源：http://dali.yj202588.top/Article/details/gtvxdrglxy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gtyckratck.html

[M03] 执行外部命令
来源：http://dali.vqdsnc.cn/Article/details/gtlxphpmhb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sweek.top/Article/details/gtrtktrjlo.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinqigfzy.top/Article/details/gtzhkuhdvj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hongshengwenyu.top/Article/details/gtxuzeviza.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangshuangyany.cn/Article/details/gtaacahbha.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yongpay.top/Article/details/gtgfdhbfiu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.fzhhl.top/Article/details/gtjpfnvdfv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.mhx1999.top/Article/details/gtgnldjsyk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.9152youxi.cn/Article/details/gtswkzzdax.html

[M04] 获取当前工作目录
来源：http://dali.tanke756.top/Article/details/gtvvcakmgc.html

Py:   os.getcwd()
来源：http://dali.havefunace.top/Article/details/gtfubhtfae.html

PHP:  getcwd();
来源：http://dali.yvedp.cn/Article/details/gtsmcttueo.html

JS:   process.cwd()
来源：http://dali.jinqigfzy.top/Article/details/gtstxknuih.html

TS:   process.cwd()
来源：http://dali.havefunace.top/Article/details/gtkbphlwak.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ybcxt.top/Article/details/gtmqlejyes.html

Go:   os.Getwd()
来源：http://dali.dianchejie.cn/Article/details/gttzpewjfc.html

Ruby: Dir.pwd
来源：http://dali.cqqwz.cn/Article/details/gtwjxdrsfe.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdbgfvods.html

[M05] 设置退出码
来源：http://dali.cashguo.top/Article/details/gtlddqtngi.html

Py:   sys.exit(1)
来源：http://dali.pycfn.com/Article/details/gtnhoadwlv.html

PHP:  exit(1);
来源：http://dali.9152youxi.cn/Article/details/gtrstoqfxr.html

JS:   process.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtlduaayin.html

TS:   process.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtlenawmnw.html

Java: System.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gtotgvwsyr.html

Go:   os.Exit(1)
来源：http://dali.pycfn.com/Article/details/gtwdzlhoup.html

Ruby: exit 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtitqqivew.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenlongwang.top/Article/details/gtldhbnwds.html

[M06] 向标准错误输出
来源：http://dali.gotoacloud.top/Article/details/gtinpykdsq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvqcbyejg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.fzhhl.top/Article/details/gtkvzartbr.html

JS:   console.error("err")
来源：http://dali.iojbl.cn/Article/details/gtmnxmkwym.html

TS:   console.error("err")
来源：http://dali.hnxiangtu.top/Article/details/gttfyjlcby.html

Java: System.err.println("err")
来源：http://dali.yangfankeji.com/Article/details/gtjpgbpiwe.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hfpthk.cn/Article/details/gtyzrkplkq.html

Ruby: warn "err"
来源：http://dali.316326.xyz/Article/details/gtpetiqskp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yuxming.cn/Article/details/gtdbpjwtlh.html

[M07] 判断是否为主入口
来源：http://dali.haohaochexian.top/Article/details/gtodvveaho.html

Py:   if __name__ == "__main__":
来源：http://dali.jinghuilouyu.cn/Article/details/gtrkunamij.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhoulong.xyz/Article/details/gtwkdzejwe.html

JS:   require.main === module
来源：http://dali.yangfankeji.com/Article/details/gtprykippt.html

TS:   require.main === module
来源：http://dali.jiagoushi.top/Article/details/gttokmxwxp.html

Java: public static void main(String[] args)
来源：http://dali.aizwys.cn/Article/details/gtziylpfef.html

Go:   func main()
来源：http://dali.ivvv.top/Article/details/gtznyxgygd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cheryme.top/Article/details/gtlsrxbdyu.html

C#:   static void Main(string[] args)
来源：http://dali.quarkkingdee.top/Article/details/gtdqutdtyn.html

[M08] 获取系统与运行时信息
来源：http://dali.wangdashe.top/Article/details/gthegnhkco.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gotoacloud.top/Article/details/gtqrenofdj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinghuilouyu.cn/Article/details/gtfaydceed.html

JS:   process.platform;  process.version
来源：http://dali.zycfv.cn/Article/details/gthxlaeflt.html

TS:   process.platform;  process.version
来源：http://dali.nwbrower.top/Article/details/gtvyvywlnd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.pycfn.com/Article/details/gtirhakmqw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cheryme.top/Article/details/gtulkrinah.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xuetiantiany.cn/Article/details/gtqzgekmpe.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gzhubu.top/Article/details/gtibnxlkoo.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gthvfvzhyq.html

N. 数据结构与算法
来源：http://dali.hywenlv.cn/Article/details/gtddavusuq.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtvohxtknl.html

[N01] 二分查找（有序数组）
来源：http://dali.cucudq.cn/Article/details/gtkgrmbwfs.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcxdonjlg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gtbfvgyyqq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guannengcc.top/Article/details/gtwdhmkcub.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxuanxn.top/Article/details/gtgtnrxxgh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtxyqeezim.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtuhihltjs.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.dashuyun.cn/Article/details/gtaqhpeysl.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yj20258.top/Article/details/gtldvxhqzf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jqgfzy.top/Article/details/gtjjrtduei.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sufxvd.cn/Article/details/gtlmuzwcmk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hfpthk.cn/Article/details/gtdiinaaxv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.0kj1m.cn/Article/details/gtfmjuayhv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuxming.cn/Article/details/gtlqfcsvsl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.guannengcc.top/Article/details/gtzbesgdum.html

Go:   slices.Sort(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtxexmcusx.html

Ruby: arr.sort
来源：http://dali.gotoacloud.top/Article/details/gtuyvdlclu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zycfv.cn/Article/details/gtxtdmtghj.html

[N03] 快速排序（分治示例）
来源：http://dali.hammf.cn/Article/details/gtzmcqlxqe.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hywenlv.cn/Article/details/gtuovcseye.html

PHP:  // 递归实现，或用 usort
来源：http://dali.feifeiyinyue.top/Article/details/gtwyeiojff.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yangfankeji.com/Article/details/gtyjjmwyuo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuetiantiany.cn/Article/details/gthijikvqu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.vqdsnc.cn/Article/details/gttfsqmwrc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cashguo.top/Article/details/gtoxgcgrzc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sxryk.cn/Article/details/gtenbwsfxz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shuidangran.top/Article/details/gtjycdfnze.html

[N04] 斐波那契数列
来源：http://dali.daxiang520.top/Article/details/gtmedleueh.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtemvyxnku.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xziqi.cn/Article/details/gtsvbnuvgu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gtidxuxjrm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gtstcpypjp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.fengsongda.top/Article/details/gtjnxpujeo.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ehwqpu.com/Article/details/gtslbhepxz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj202588.top/Article/details/gthuxrynjp.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jqgufenzy.top/Article/details/gtxaocymfh.html

[N05] 最大公约数
来源：http://dali.shanyushiyangtech.top/Article/details/gtijglkggj.html

Py:   math.gcd(a, b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdpzzqrqh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hammf.cn/Article/details/gtlhcvmrkf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenjidiqi.icu/Article/details/gtnjzbfddb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yanxiufei.cn/Article/details/gtxmoftist.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.chenzaomai.com/Article/details/gtpinyvwfr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hnxiangtu.top/Article/details/gtolyxmyiv.html

Ruby: a.gcd(b)
来源：http://dali.guannengcc.top/Article/details/gtbzksizvw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.guannengcc.top/Article/details/gtogguezlb.html

[N06] 判断回文字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtugpcxeyj.html

Py:   s == s[::-1]
来源：http://dali.shzxlz.cn/Article/details/gtdupptsed.html

PHP:  $s === strrev($s);
来源：http://dali.yueranfly.top/Article/details/gtfycqasww.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gtpcjuzkyf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtemieaibr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xziqi.cn/Article/details/gtjrtphyha.html

Go:   // 双指针从两端比较
来源：http://dali.jinqigufen.top/Article/details/gtfqkbxvby.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gtxcvdvtcc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.pycfn.com/Article/details/gtqplijyla.html

[N07] 两数之和（返回下标）
来源：http://dali.shuidangran.top/Article/details/gtjqhxftpr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cdnleiting.top/Article/details/gtbfalxkpj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jiagoushi.top/Article/details/gtqvppqkdk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jiagoushi.top/Article/details/gtuswzbjge.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gtmhxyivgi.html

Java: // 手写 HashMap
来源：http://dali.cqqwz.cn/Article/details/gtvniqwapa.html

Go:   // 手写 map[int]int
来源：http://dali.jiagoushi.top/Article/details/gtwtpbtqij.html

Ruby: // 手写 Hash
来源：http://dali.cashguo.top/Article/details/gtehexmxhd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sysykeji.top/Article/details/gtqlmvtxvq.html

[N08] 生成全排列
来源：http://dali.birdmap.top/Article/details/gthnsgxjvc.html

Py:   itertools.permutations(arr)
来源：http://dali.cashguo.top/Article/details/gtlppjthuz.html

PHP:  // 手写递归交换
来源：http://dali.smart0.xyz/Article/details/gtgrfuunfw.html

JS:   // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gthgzswdnt.html

TS:   // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gtqijprmav.html

Java: // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gtpubbwdfl.html

Go:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gtbqjzytxe.html

Ruby: arr.permutation.to_a
来源：http://dali.xuetiantiany.cn/Article/details/gtqllzvkus.html

C#:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gtifirdyoi.html

[N09] 栈与队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuaccorsk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jqgfzy.top/Article/details/gtgihzhvea.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtujwpzbis.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gtqkolapsj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yueranfly.top/Article/details/gtbaxcfjmk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.quarkkingdee.top/Article/details/gtvceleehd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gzhubu.top/Article/details/gtyyqnkbuu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jqgufenzy.top/Article/details/gtumfsuszl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhiwuduotai.top/Article/details/gtxrcqpfnj.html

[N10] 链表节点定义
来源：http://dali.jiagoushi.top/Article/details/gtbzweljpq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.guowangkeji.top/Article/details/gtdnqhikjv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.chenzaomai.com/Article/details/gttlqknrsg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hfpthk.cn/Article/details/gtrucdlkti.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hammf.cn/Article/details/gtuathbsbw.html

Java: class Node { int v; Node next; }
来源：http://dali.zhongyouzk.top/Article/details/gtpdpzzhvu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yongpay.top/Article/details/gtktjpmtwh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.pycfn.com/Article/details/gthqdndham.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cashguo.top/Article/details/gttuzxsdmn.html

[N11] 二叉树中序遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgjoherbf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyxpdvgdu.html

PHP:  // 手写递归函数
来源：http://dali.bjfxy.top/Article/details/gtzfieaofr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zycfv.cn/Article/details/gtsdxxoicz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhongyouzk.top/Article/details/gtzdwiiuya.html

Java: // 手写递归
来源：http://dali.fengsongda.top/Article/details/gtdgykaoal.html

Go:   // 手写递归
来源：http://dali.yueranfly.top/Article/details/gtgjkumtxw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xylfe.cn/Article/details/gtwdqjedda.html

C#:   // 手写递归
来源：http://dali.xylfe.cn/Article/details/gtgldkpyti.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sxryk.cn/Article/details/gtlbfpvcev.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.316326.xyz/Article/details/gtluuwwpvn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xylfe.cn/Article/details/gtdngexrqf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinqigfzy.top/Article/details/gtqnwoeslr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258888.top/Article/details/gtttbijthe.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ehwqpu.com/Article/details/gtlwclvofe.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinghuilouyu.cn/Article/details/gtldfkefpw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sxryk.cn/Article/details/gtwyqexvgm.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangtech.top/Article/details/gtjnxufuyd.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtwfmsmise.html

O. 并发与异步
来源：http://dali.cucudq.cn/Article/details/gtgtstswja.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtmizwzers.html

[O01] 启动一个线程
来源：http://dali.ivvv.top/Article/details/gtqgbbdebq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.iojbl.cn/Article/details/gtpxmhtcab.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgsjeismg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.redwolf501.top/Article/details/gthtbzryaa.html

TS:   // 同 JS
来源：http://dali.redwolf501.top/Article/details/gtvedqeoew.html

Java: new Thread(() -> f()).start()
来源：http://dali.hammf.cn/Article/details/gtxlixfapg.html

Go:   go f()
来源：http://dali.fzhhl.top/Article/details/gtzhkcrlbm.html

Ruby: Thread.new { f }
来源：http://dali.mhx1999.top/Article/details/gtbfqihiqc.html

C#:   Task.Run(() => F());
来源：http://dali.daxiang520.top/Article/details/gtwvxtuwhn.html

[O02] 使用线程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gteryqwyzq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xinyue.icu/Article/details/gthemazxcm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zycfv.cn/Article/details/gtksggdhhs.html

JS:   // worker_threads 线程池
来源：http://dali.tianlin.xyz/Article/details/gtgllrohep.html

TS:   // worker_threads 线程池
来源：http://dali.birdmap.top/Article/details/gtsrenuggz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yangfankeji.com/Article/details/gtwfmpudlu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.dashuyun.cn/Article/details/gtottjgolb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.meibo888.top/Article/details/gtcnhuvsfv.html


<!-- 参考信息 -->