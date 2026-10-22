代发 wailian999

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gtubvyxgov.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtefunfduc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtowoqdmpo.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.mhx1999.top/Article/details/gtpglvarpt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yueranfly.top/Article/details/gttcchhlzm.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtiflpdjgu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nwbrower.top/Article/details/gtewuvguix.html

Py:   pickle.dumps(obj)
来源：http://dali.quarkkingdee.top/Article/details/gthjohacnv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.kuanghao11.cn/Article/details/gtrswzguka.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.chenzaomai.com/Article/details/gtiqxcodwl.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ppjwa.cn/Article/details/gtaobvtade.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jiagoushi.top/Article/details/gttsatrfza.html

Go:   encoding/gob
来源：http://dali.aibaodan.cn/Article/details/gtsocrybvs.html

Ruby: Marshal.dump(obj)
来源：http://dali.wangdashe.top/Article/details/gtrlzjbciq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.wangdashe.top/Article/details/gtnwmstzls.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtuacwxbpk.html

L. 网络请求
来源：http://dali.meibo888.top/Article/details/gtkmqbjnlb.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtqoqvazpd.html

[L01] 发送 GET 请求
来源：http://dali.jiagoushi.top/Article/details/gtysfwyoft.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.meibo888.top/Article/details/gtuzputcnt.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.tanke756.top/Article/details/gtncdhzrwo.html

JS:   await fetch(url)
来源：http://dali.hfpthk.cn/Article/details/gtrrostzna.html

TS:   await fetch(url)
来源：http://dali.cucudq.cn/Article/details/gtitrkxlam.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shanyushiyangtech.top/Article/details/gtznkymrlf.html

Go:   resp, err := http.Get(url)
来源：http://dali.jqgufenzy.top/Article/details/gtgqepamhq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.kuanghao11.cn/Article/details/gtyvdiiznn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ybcxt.top/Article/details/gttwkxkppr.html

[L02] 发送 POST JSON
来源：http://dali.snrcjt.cn/Article/details/gtaahdfvxc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hywenlv.cn/Article/details/gtdmbrxyng.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.c1oappe.top/Article/details/gtgibeygqw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pycfn.com/Article/details/gtlykotiyb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnqzz.top/Article/details/gtsucxqmhq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shanyushiyangtech.top/Article/details/gtqocfevsm.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sufxvd.cn/Article/details/gttksdjwbw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sweek.top/Article/details/gtvtyxlqor.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.fzhhl.top/Article/details/gtkwsygaqe.html

[L03] 设置自定义请求头
来源：http://dali.ywan-chungtsiang.top/Article/details/gtukfzpqke.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xziqi.cn/Article/details/gtilczdpee.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.andypj.xyz/Article/details/gtiajeqftf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhengqikj.top/Article/details/gtoevlndkl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cashguo.top/Article/details/gthcnkolmm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtixegrqgh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jqgufenzy.top/Article/details/gtxxkcspmp.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.svipenyu.cn/Article/details/gthsxrqqxo.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gogol.net.cn/Article/details/gtwcpszeqj.html

[L04] 设置超时
来源：http://dali.0kj1m.cn/Article/details/gtatuudnir.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yangfankeji.com/Article/details/gtuqzetoan.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenlongwang.top/Article/details/gtzdkdkbwt.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guowangkeji.top/Article/details/gtitgkqvax.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shangyingyoupin.top/Article/details/gtmqsaiuzi.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhongyouzk.top/Article/details/gtlygwqerg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.bjfxy.top/Article/details/gtlfdexena.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinqigufen.top/Article/details/gtzijaocdz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.wangshuangyany.cn/Article/details/gtphroqfys.html

[L05] 上传文件（multipart）
来源：http://dali.yanxiufei.cn/Article/details/gtvkjumuwl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yj202588.top/Article/details/gtaxviouas.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jiagoushi.top/Article/details/gtrrbnpsme.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jyoumei.cn/Article/details/gtrmuxxjhn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhiwuduotai.top/Article/details/gtabdgunec.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhixingplan.top/Article/details/gtveqiwlns.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.chenzaomai.com/Article/details/gtokeqjipw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.meibo888.top/Article/details/gttnvkpazs.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yuxming.cn/Article/details/gtcqrhdnqx.html

[L06] 解析响应为 JSON
来源：http://dali.andypj.xyz/Article/details/gtckvovpna.html

Py:   resp.json()
来源：http://dali.hammf.cn/Article/details/gtlwqqgxaw.html

PHP:  json_decode($body, true);
来源：http://dali.hongshengwenyu.top/Article/details/gtugecbfit.html

JS:   await resp.json()
来源：http://dali.yangfankeji.com/Article/details/gtwekszeiy.html

TS:   await resp.json()
来源：http://dali.zdqjudy.top/Article/details/gtuyfacuns.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yvedp.cn/Article/details/gtbpmvigpk.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gtdrqqrfdd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hammf.cn/Article/details/gtmegbumvs.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sweek.top/Article/details/gtlibirzis.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhiwuduotai.top/Article/details/gtqslofvhl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sysykeji.top/Article/details/gtzigkmcnh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cheryme.top/Article/details/gtmdjkqvcz.html

JS:   resp.ok;  resp.status
来源：http://dali.zhoulong.xyz/Article/details/gtewiuizdh.html

TS:   resp.ok;  resp.status
来源：http://dali.quarkkingdee.top/Article/details/gthnbgwpxd.html

Java: resp.statusCode()
来源：http://dali.yuxming.cn/Article/details/gtdaafvvyf.html

Go:   resp.StatusCode
来源：http://dali.tanke756.top/Article/details/gtfoemkxwh.html

Ruby: resp.code.to_i
来源：http://dali.hongshengwenyu.top/Article/details/gthmtsrwqe.html

C#:   (int)resp.StatusCode
来源：http://dali.haohaochexian.top/Article/details/gtylebtatm.html

[L08] 并发请求多个地址
来源：http://dali.chenzaomai.com/Article/details/gtjcpwfgyq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cucudq.cn/Article/details/gtbdggxmbz.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmnvqnwyj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsemhwwns.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdniucbok.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gogol.net.cn/Article/details/gtrcnrzysq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yuxming.cn/Article/details/gtrfhsbagv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ydzc1.top/Article/details/gtmaaxqwbs.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zycfv.cn/Article/details/gturncutae.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtkznxsdnp.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinqigfzy.top/Article/details/gtmpequhwj.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtdqcxoxnm.html

[M01] 读取命令行参数
来源：http://dali.vqdsnc.cn/Article/details/gtfuqjolvd.html

Py:   sys.argv[1:]
来源：http://dali.birdmap.top/Article/details/gtgxnjyqno.html

PHP:  $argv;  $argc;
来源：http://dali.andypj.xyz/Article/details/gtleqqatvt.html

JS:   process.argv.slice(2)
来源：http://dali.shangyingyoupin.top/Article/details/gtbszafzcf.html

TS:   process.argv.slice(2)
来源：http://dali.jqgfzy.top/Article/details/gtysotdnzo.html

Java: args 数组（main 方法参数）
来源：http://dali.guowangkeji.top/Article/details/gtndxhbfyv.html

Go:   os.Args[1:]
来源：http://dali.cucudq.cn/Article/details/gtknqetvbx.html

Ruby: ARGV
来源：http://dali.jianghu66.top/Article/details/gtmxqslqih.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yanxiufei.cn/Article/details/gtkxqdijup.html

[M02] 读取环境变量
来源：http://dali.c1oappe.top/Article/details/gtawngdxer.html

Py:   os.environ.get("HOME")
来源：http://dali.bjfxy.top/Article/details/gtkzzytulq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nanxuanxn.top/Article/details/gtkinejbav.html

JS:   process.env.HOME
来源：http://dali.yangfankeji.com/Article/details/gtybyxhnvb.html

TS:   process.env.HOME
来源：http://dali.bjfxy.top/Article/details/gtyagonmkx.html

Java: System.getenv("HOME")
来源：http://dali.gzhubu.top/Article/details/gtgbtmhqmk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtjmlbnnej.html

Ruby: ENV["HOME"]
来源：http://dali.hongshengwenyu.top/Article/details/gtulmlmdqr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.bjfxy.top/Article/details/gtxzvzmmth.html

[M03] 执行外部命令
来源：http://dali.yonumen.top/Article/details/gtegeijpfb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yueranfly.top/Article/details/gtqdkmpdch.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.fengsongda.top/Article/details/gthhhadowa.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.snrcjt.cn/Article/details/gtzunrrxgp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhiwuduotai.top/Article/details/gtcxdgeblb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.daria6918.cn/Article/details/gtrzxxezrh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.c1oappe.top/Article/details/gtwjxouagx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.fengsongda.top/Article/details/gtkgxlvohz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xuanzx.com/Article/details/gtwhwdtgbk.html

[M04] 获取当前工作目录
来源：http://dali.jqgufenzy.top/Article/details/gtnlqcnrlm.html

Py:   os.getcwd()
来源：http://dali.pycfn.com/Article/details/gtnfiagzdv.html

PHP:  getcwd();
来源：http://dali.jinyuanbaomall.cn/Article/details/gttfjzwcni.html

JS:   process.cwd()
来源：http://dali.dashuyun.cn/Article/details/gtbjjxyjzr.html

TS:   process.cwd()
来源：http://dali.aibaodan.cn/Article/details/gtfgnscvgn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.haohaochexian.top/Article/details/gtufehqkoz.html

Go:   os.Getwd()
来源：http://dali.zhongyouzk.top/Article/details/gtvjvwicbj.html

Ruby: Dir.pwd
来源：http://dali.yuanzhike.top/Article/details/gteqfcjzwh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yangfankeji.com/Article/details/gtpatbhqwi.html

[M05] 设置退出码
来源：http://dali.yanxiufei.cn/Article/details/gtrmoplzuh.html

Py:   sys.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gtrjnllfyb.html

PHP:  exit(1);
来源：http://dali.ppjwa.cn/Article/details/gtplzwrtta.html

JS:   process.exit(1)
来源：http://dali.ivvv.top/Article/details/gtuynvysgj.html

TS:   process.exit(1)
来源：http://dali.meibo888.top/Article/details/gtnrzalmvp.html

Java: System.exit(1)
来源：http://dali.smart0.xyz/Article/details/gtspjmdhap.html

Go:   os.Exit(1)
来源：http://dali.tianlin.xyz/Article/details/gtjnvavunv.html

Ruby: exit 1
来源：http://dali.havefunace.top/Article/details/gtfnthtwmd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.fengsongda.top/Article/details/gtkredrbrl.html

[M06] 向标准错误输出
来源：http://dali.hywenlv.cn/Article/details/gtnryvltlr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtydlrfidz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.aizwys.cn/Article/details/gtipzryefc.html

JS:   console.error("err")
来源：http://dali.xinyue.icu/Article/details/gtiowpsmaj.html

TS:   console.error("err")
来源：http://dali.9152youxi.cn/Article/details/gttpqjjcie.html

Java: System.err.println("err")
来源：http://dali.guannengcc.top/Article/details/gtkanizdpz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zycfv.cn/Article/details/gttoplzajf.html

Ruby: warn "err"
来源：http://dali.yonumen.top/Article/details/gtrhwnzkqt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cashguo.top/Article/details/gtfcihzcyu.html

[M07] 判断是否为主入口
来源：http://dali.shuidangran.top/Article/details/gtgsnddzgy.html

Py:   if __name__ == "__main__":
来源：http://dali.yongpay.top/Article/details/gtexnjatfj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmodneurh.html

JS:   require.main === module
来源：http://dali.aizwys.cn/Article/details/gtpjniuxxs.html

TS:   require.main === module
来源：http://dali.zhengqikj.top/Article/details/gtgotuwlqn.html

Java: public static void main(String[] args)
来源：http://dali.316326.xyz/Article/details/gteajdqqzm.html

Go:   func main()
来源：http://dali.smart0.xyz/Article/details/gtxwvogkjd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.smart0.xyz/Article/details/gtukhqcdjw.html

C#:   static void Main(string[] args)
来源：http://dali.mhx1999.top/Article/details/gtplxhgdfx.html

[M08] 获取系统与运行时信息
来源：http://dali.jinghuilouyu.cn/Article/details/gtunleuxtc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xinyue.icu/Article/details/gtrhxxedat.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.quarkkingdee.top/Article/details/gtvhddkexz.html

JS:   process.platform;  process.version
来源：http://dali.dianchejie.cn/Article/details/gtfixzyedx.html

TS:   process.platform;  process.version
来源：http://dali.hnxiangtu.top/Article/details/gtvmcvirqz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zycfv.cn/Article/details/gtcgcfvfwh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.dashuyun.cn/Article/details/gtwdnujxbs.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpnavgmgj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jlsjyb.cn/Article/details/gtxwboijie.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtscmxjzyj.html

N. 数据结构与算法
来源：http://dali.jianghu66.top/Article/details/gtzfnrwvgk.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gturhozahs.html

[N01] 二分查找（有序数组）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpftvqzgb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtxhbrpovt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sxryk.cn/Article/details/gtesjoxcab.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ppjwa.cn/Article/details/gtbhjxxnix.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yonumen.top/Article/details/gthnjldusi.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtgjznbsdi.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtpueivmdp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hongshengwenyu.top/Article/details/gtdfnqvjea.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yuxming.cn/Article/details/gthzawixju.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.snrcjt.cn/Article/details/gtvbrbjwte.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.iojbl.cn/Article/details/gtsrucpzzz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.dianchejie.cn/Article/details/gtfakishbh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xylfe.cn/Article/details/gtotlkjrvd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenjidiqi.icu/Article/details/gtbsttrdni.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ybcxt.top/Article/details/gtreujnokg.html

Go:   slices.Sort(arr)
来源：http://dali.c1oappe.top/Article/details/gtfnzbvhfd.html

Ruby: arr.sort
来源：http://dali.fengsongda.top/Article/details/gtiuieqjgn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.9152youxi.cn/Article/details/gtnoajemks.html

[N03] 快速排序（分治示例）
来源：http://dali.guowangkeji.top/Article/details/gtjhfuehwu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hywenlv.cn/Article/details/gtjgtvrhop.html

PHP:  // 递归实现，或用 usort
来源：http://dali.aibaodan.cn/Article/details/gtmefqrpkv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.andypj.xyz/Article/details/gtiuxxdkva.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.c1oappe.top/Article/details/gtvdbzvtkp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.dashuyun.cn/Article/details/gtzkhzwczj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xylfe.cn/Article/details/gtonfatidp.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.vqdsnc.cn/Article/details/gtxgfnjsjj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yonumen.top/Article/details/gtbxiuxcmn.html

[N04] 斐波那契数列
来源：http://dali.pycfn.com/Article/details/gtggpozzlw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hnqzz.top/Article/details/gtjnagleor.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.tian-w.cn/Article/details/gtvgrfxngo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigufen.top/Article/details/gtdfdygsmd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtujwccgzt.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gtwacvlrec.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqgiduhpm.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigufen.top/Article/details/gtzwuxldts.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gtqqfmzyco.html

[N05] 最大公约数
来源：http://dali.shuidangran.top/Article/details/gtriqyvcxq.html

Py:   math.gcd(a, b)
来源：http://dali.chenjidiqi.icu/Article/details/gtoqliyvtt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yongpay.top/Article/details/gtjogdhxmt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.bjfxy.top/Article/details/gtnmdtjgtt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxinkj.top/Article/details/gtnvyrmyut.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.iojbl.cn/Article/details/gtmxdinzvo.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ybcxt.top/Article/details/gtkvrtjjth.html

Ruby: a.gcd(b)
来源：http://dali.shuidangran.top/Article/details/gtrsubbzyb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jiagoushi.top/Article/details/gttasclcvd.html

[N06] 判断回文字符串
来源：http://dali.dashuyun.cn/Article/details/gtryxurwzs.html

Py:   s == s[::-1]
来源：http://dali.bjfxy.top/Article/details/gtqgroyrgo.html

PHP:  $s === strrev($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkvsnnyyy.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtlepctfxy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gtbvqzipje.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.andypj.xyz/Article/details/gtpxbdcalj.html

Go:   // 双指针从两端比较
来源：http://dali.chenzaomai.com/Article/details/gtlkaygcgi.html

Ruby: s == s.reverse
来源：http://dali.andypj.xyz/Article/details/gtyyzdjlem.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhixingplan.top/Article/details/gtleoagfki.html

[N07] 两数之和（返回下标）
来源：http://dali.andypj.xyz/Article/details/gtmleodkfs.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yanxiufei.cn/Article/details/gtoaqjffeh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shanyushiyangkeji.top/Article/details/gtybsuiyxn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xylfe.cn/Article/details/gtatynwngg.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhoulong.xyz/Article/details/gtgmqjzpge.html

Java: // 手写 HashMap
来源：http://dali.0kj1m.cn/Article/details/gtdhadsoif.html

Go:   // 手写 map[int]int
来源：http://dali.pycfn.com/Article/details/gtsuvukrmd.html

Ruby: // 手写 Hash
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzfkvascl.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.316326.xyz/Article/details/gtaagwwtkh.html

[N08] 生成全排列
来源：http://dali.cheryme.top/Article/details/gthbsfzwhx.html

Py:   itertools.permutations(arr)
来源：http://dali.hfpthk.cn/Article/details/gtydngdteu.html

PHP:  // 手写递归交换
来源：http://dali.nanxinkj.top/Article/details/gtzaecxqtk.html

JS:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gtkpjmjwgn.html

TS:   // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gtoywitkke.html

Java: // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtkqjvvwbe.html

Go:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gtcfxopfpg.html

Ruby: arr.permutation.to_a
来源：http://dali.iojbl.cn/Article/details/gtmywpwrzm.html

C#:   // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gtqhgrkfvt.html

[N09] 栈与队列
来源：http://dali.cqqwz.cn/Article/details/gtbdsjhxie.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shzxlz.cn/Article/details/gtfvhozrxh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yvedp.cn/Article/details/gtjkxryuxd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hywenlv.cn/Article/details/gtlmhotavz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.sysykeji.top/Article/details/gtoianaimd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xuanzx.com/Article/details/gtfersefpe.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.tianlin.xyz/Article/details/gtaeyprlsl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gaohongyu789.top/Article/details/gtytxpnggc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.guannengcc.top/Article/details/gtzrhtwowt.html

[N10] 链表节点定义
来源：http://dali.fzhhl.top/Article/details/gtktonrjte.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.aibaodan.cn/Article/details/gtfmwbdqmi.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.tanke756.top/Article/details/gtoprpcunt.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.svipenyu.cn/Article/details/gtfwndbvlo.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.havefunace.top/Article/details/gtzahujhti.html

Java: class Node { int v; Node next; }
来源：http://dali.yuanzhike.top/Article/details/gtijbgurlq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shzxlz.cn/Article/details/gtnpqpapyg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yj20258.top/Article/details/gtheuqfzeu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.fzhhl.top/Article/details/gtxqgvhxfb.html

[N11] 二叉树中序遍历
来源：http://dali.ybcxt.top/Article/details/gtjeoihlhz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhiwuduotai.top/Article/details/gtfhnwhjgd.html

PHP:  // 手写递归函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthovgofes.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xylfe.cn/Article/details/gtldykxzee.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.9152youxi.cn/Article/details/gtjemnpuwe.html

Java: // 手写递归
来源：http://dali.smart0.xyz/Article/details/gtatvzfgdb.html

Go:   // 手写递归
来源：http://dali.fzhhl.top/Article/details/gtshhjmvyn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hongshengwenyu.top/Article/details/gtxuvixttu.html

C#:   // 手写递归
来源：http://dali.fengsongda.top/Article/details/gtuueqpxfk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.haohaochexian.top/Article/details/gtqvrtmllg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.bjfxy.top/Article/details/gtphymckzr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cheryme.top/Article/details/gtlntqhjuy.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuxming.cn/Article/details/gtwwekikue.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ivvv.top/Article/details/gtnpqirggs.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinghuilouyu.cn/Article/details/gtzyyttzbo.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ivvv.top/Article/details/gtwcaddrkm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.andypj.xyz/Article/details/gtbhvasgau.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gogol.net.cn/Article/details/gtxclruawn.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtpckbuqbg.html

O. 并发与异步
来源：http://dali.aizwys.cn/Article/details/gtdtthutgf.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtnmccfqph.html

[O01] 启动一个线程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqsinszvf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jinghuilouyu.cn/Article/details/gttutstyfm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.haohaochexian.top/Article/details/gtzrzaosnt.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jqgfzy.top/Article/details/gtkslaaiin.html

TS:   // 同 JS
来源：http://dali.nwbrower.top/Article/details/gtcokbjxrl.html

Java: new Thread(() -> f()).start()
来源：http://dali.316326.xyz/Article/details/gtocemzaww.html

Go:   go f()
来源：http://dali.gaohongyu789.top/Article/details/gtnlmsmjxe.html

Ruby: Thread.new { f }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteohrezjs.html

C#:   Task.Run(() => F());
来源：http://dali.meibo888.top/Article/details/gtxmjlwfhi.html

[O02] 使用线程池
来源：http://dali.zhoulong.xyz/Article/details/gtkugrzeqi.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cdnleiting.top/Article/details/gtmnlxrgla.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhiwuduotai.top/Article/details/gtymolkqgb.html

JS:   // worker_threads 线程池
来源：http://dali.smart0.xyz/Article/details/gtbmzpitrw.html

TS:   // worker_threads 线程池
来源：http://dali.cdnleiting.top/Article/details/gtccvxwuik.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.andypj.xyz/Article/details/gtmsjyhfse.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yuanzhike.top/Article/details/gtgehmnhdx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.havefunace.top/Article/details/gtkbmoxomw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xuetiantiany.cn/Article/details/gtfxiqoduf.html

[O03] 加锁保护共享数据
来源：http://dali.zdqjudy.top/Article/details/gtydwklxoi.html

Py:   with lock: shared += 1
来源：http://dali.tian-w.cn/Article/details/gttxauityo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.svipenyu.cn/Article/details/gtshetvjrv.html


<!-- 参考信息 -->