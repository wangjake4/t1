代发 wailian999

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtewvncmgu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cashguo.top/Article/details/gthvkqddao.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtebenrrsv.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xuanzx.com/Article/details/gtkzbawugg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cheryme.top/Article/details/gthbykbwlq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gtbeurzfwn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yangfankeji.com/Article/details/gtaepedwty.html

Py:   pickle.dumps(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtprrwsxht.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yongpay.top/Article/details/gtobhmwfnp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nanxuanxn.top/Article/details/gthihluuli.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cqqwz.cn/Article/details/gtlonaqaon.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yongpay.top/Article/details/gtzytonmcj.html

Go:   encoding/gob
来源：http://dali.xuetiantiany.cn/Article/details/gtojsjbtlq.html

Ruby: Marshal.dump(obj)
来源：http://dali.smart0.xyz/Article/details/gtznfyxzyt.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gogol.net.cn/Article/details/gtrrerfxjx.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtiqcoidnh.html

L. 网络请求
来源：http://dali.yanxiufei.cn/Article/details/gtqsytonri.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtviumehbk.html

[L01] 发送 GET 请求
来源：http://dali.yj20258.top/Article/details/gtudazyojs.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zdqjudy.top/Article/details/gtzsajljzd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gotoacloud.top/Article/details/gtmlxrtjjc.html

JS:   await fetch(url)
来源：http://dali.vqdsnc.cn/Article/details/gtlzmuoomz.html

TS:   await fetch(url)
来源：http://dali.yonumen.top/Article/details/gtwlvecbez.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.pycfn.com/Article/details/gtuughllzs.html

Go:   resp, err := http.Get(url)
来源：http://dali.aibaodan.cn/Article/details/gtsvvwnlws.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sufxvd.cn/Article/details/gtoxqaudzr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.chenlongwang.top/Article/details/gtpdabalqx.html

[L02] 发送 POST JSON
来源：http://dali.sweek.top/Article/details/gtsjbhtbua.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ybcxt.top/Article/details/gtjxoywmox.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.daria6918.cn/Article/details/gtsuaiccmx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxuanxn.top/Article/details/gtmwhtscjk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.svipenyu.cn/Article/details/gtmqlxsbtx.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.wangshuangyany.cn/Article/details/gtwnlpmxvw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hfpthk.cn/Article/details/gtxidqwkje.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cqqwz.cn/Article/details/gtbauruznx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yuanzhike.top/Article/details/gttszrfxbn.html

[L03] 设置自定义请求头
来源：http://dali.pycfn.com/Article/details/gteqjwmddo.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.svipenyu.cn/Article/details/gtwyvsxdno.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shzxlz.cn/Article/details/gtpbboehps.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yueranfly.top/Article/details/gtpdvzygup.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhoulong.xyz/Article/details/gtbalrrdrn.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hysaishi.cn/Article/details/gtyqvjrkjq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.guowangkeji.top/Article/details/gtwnaoclsp.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.havefunace.top/Article/details/gtelvwxvdw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.aizwys.cn/Article/details/gtwcncxiox.html

[L04] 设置超时
来源：http://dali.smart0.xyz/Article/details/gtxwbcygiq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.feifeiyinyue.top/Article/details/gtbxkdlnki.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj202588.top/Article/details/gtmfrqapcz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.smart0.xyz/Article/details/gtbetdmsyx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ppjwa.cn/Article/details/gtvwzixtdu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cqqwz.cn/Article/details/gtkoxydniv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yvedp.cn/Article/details/gtxmrwnvyf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.daria6918.cn/Article/details/gteykczsjb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hnxiangtu.top/Article/details/gtoprbuyew.html

[L05] 上传文件（multipart）
来源：http://dali.hysaishi.cn/Article/details/gtfxelamsl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.svipenyu.cn/Article/details/gtksfanwwk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.wangshuangyany.cn/Article/details/gtodbpvshe.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.iojbl.cn/Article/details/gtaepjnoeo.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yvedp.cn/Article/details/gtlmixkfkk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ehwqpu.com/Article/details/gtbvqeghgg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.svipenyu.cn/Article/details/gtyjlsthcq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.andypj.xyz/Article/details/gtmgidizmt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtbpjytqzl.html

[L06] 解析响应为 JSON
来源：http://dali.pycfn.com/Article/details/gtwgcvzdpg.html

Py:   resp.json()
来源：http://dali.jqgufenzy.top/Article/details/gtvxvjxchh.html

PHP:  json_decode($body, true);
来源：http://dali.jlsjyb.cn/Article/details/gtmucflfet.html

JS:   await resp.json()
来源：http://dali.zhengqikj.top/Article/details/gthngjlhvt.html

TS:   await resp.json()
来源：http://dali.cheryme.top/Article/details/gtkdrecqhv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.redwolf501.top/Article/details/gtaatkzqzm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxgebbtrw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhiwuduotai.top/Article/details/gtlrkzmuwc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj202588.top/Article/details/gtnnebwstp.html

[L07] 处理 HTTP 状态码
来源：http://dali.bjfxy.top/Article/details/gttxdxozsp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtksvlvhpv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.wangdashe.top/Article/details/gtfjtfnlro.html

JS:   resp.ok;  resp.status
来源：http://dali.yonumen.top/Article/details/gtmvlursyn.html

TS:   resp.ok;  resp.status
来源：http://dali.mhx1999.top/Article/details/gtlsqmdjgp.html

Java: resp.statusCode()
来源：http://dali.yvedp.cn/Article/details/gthpgrqwdf.html

Go:   resp.StatusCode
来源：http://dali.kuanghao11.cn/Article/details/gtwaslkjoh.html

Ruby: resp.code.to_i
来源：http://dali.zhixingplan.top/Article/details/gtcnvptdmq.html

C#:   (int)resp.StatusCode
来源：http://dali.ehwqpu.com/Article/details/gtajnvohfu.html

[L08] 并发请求多个地址
来源：http://dali.xuetiantiany.cn/Article/details/gtidljuisl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sweek.top/Article/details/gtxptaovbw.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinqigfzy.top/Article/details/gtksvxhgre.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yongpay.top/Article/details/gtubzupwcm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aibaodan.cn/Article/details/gtupijjwkz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.dianchejie.cn/Article/details/gtfovnrcbp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hammf.cn/Article/details/gtbsiteril.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hywenlv.cn/Article/details/gtneqjgwvt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj202588.top/Article/details/gtiiqtewng.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gturyfubji.html

M. 命令行 / 进程 / 环境
来源：http://dali.zdqjudy.top/Article/details/gtudykxqyc.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtgisbpsti.html

[M01] 读取命令行参数
来源：http://dali.nwbrower.top/Article/details/gtjrwnkoxp.html

Py:   sys.argv[1:]
来源：http://dali.sufxvd.cn/Article/details/gtmnttoffk.html

PHP:  $argv;  $argc;
来源：http://dali.yuanzhike.top/Article/details/gttfmbktmy.html

JS:   process.argv.slice(2)
来源：http://dali.meibo888.top/Article/details/gtdatkrbwj.html

TS:   process.argv.slice(2)
来源：http://dali.gogol.net.cn/Article/details/gtfgortkjj.html

Java: args 数组（main 方法参数）
来源：http://dali.feifeiyinyue.top/Article/details/gtzhdihwxl.html

Go:   os.Args[1:]
来源：http://dali.cucudq.cn/Article/details/gtnhpuwwnq.html

Ruby: ARGV
来源：http://dali.zhoulong.xyz/Article/details/gtbcsyanom.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yueranfly.top/Article/details/gtnpffmvgs.html

[M02] 读取环境变量
来源：http://dali.jqgufenzy.top/Article/details/gtuhzamkqm.html

Py:   os.environ.get("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfmaiacho.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj20258.top/Article/details/gtkgatjvff.html

JS:   process.env.HOME
来源：http://dali.jinyuanbaomall.cn/Article/details/gteqnioood.html

TS:   process.env.HOME
来源：http://dali.yuanzhike.top/Article/details/gtwiascrap.html

Java: System.getenv("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnjxqjvaz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gtqzkpbgxn.html

Ruby: ENV["HOME"]
来源：http://dali.vqdsnc.cn/Article/details/gtqykmrumy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cucudq.cn/Article/details/gtwbuhdvib.html

[M03] 执行外部命令
来源：http://dali.hnqzz.top/Article/details/gtiolieesc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cheryme.top/Article/details/gtvohsdamk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ppjwa.cn/Article/details/gtsppwatze.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvhlcmymr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gaohongyu789.top/Article/details/gtsvanzjeh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zdqjudy.top/Article/details/gtetrrxetv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ydzc1.top/Article/details/gthmbstgiq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hfpthk.cn/Article/details/gtlhugnxzt.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gogol.net.cn/Article/details/gtnlshjizg.html

[M04] 获取当前工作目录
来源：http://dali.zhixingplan.top/Article/details/gtvpyzyiuv.html

Py:   os.getcwd()
来源：http://dali.hfpthk.cn/Article/details/gtjxrtgbru.html

PHP:  getcwd();
来源：http://dali.cdnleiting.top/Article/details/gtpcnrnypj.html

JS:   process.cwd()
来源：http://dali.cashguo.top/Article/details/gtjwlzwkmr.html

TS:   process.cwd()
来源：http://dali.gaohongyu789.top/Article/details/gtxxfivfdv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenjidiqi.icu/Article/details/gtgpjtsmof.html

Go:   os.Getwd()
来源：http://dali.daxiang520.top/Article/details/gtgfyxgnff.html

Ruby: Dir.pwd
来源：http://dali.sysykeji.top/Article/details/gtaackhgna.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nanxinkj.top/Article/details/gttgquedcw.html

[M05] 设置退出码
来源：http://dali.vqdsnc.cn/Article/details/gtmrcemslm.html

Py:   sys.exit(1)
来源：http://dali.bjfxy.top/Article/details/gtjvafdcvw.html

PHP:  exit(1);
来源：http://dali.hnqzz.top/Article/details/gtktqoccbn.html

JS:   process.exit(1)
来源：http://dali.gzhubu.top/Article/details/gtijgzsels.html

TS:   process.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gtwpgcywis.html

Java: System.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtxjpuebhd.html

Go:   os.Exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gtsjibonwv.html

Ruby: exit 1
来源：http://dali.zhengqikj.top/Article/details/gthantvjsu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shzxlz.cn/Article/details/gtsoysikuo.html

[M06] 向标准错误输出
来源：http://dali.chenzaomai.com/Article/details/gtvnlrjuch.html

Py:   print("err", file=sys.stderr)
来源：http://dali.pengpengdd.cyou/Article/details/gtsthfddof.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.bjfxy.top/Article/details/gtzxvuwwfk.html

JS:   console.error("err")
来源：http://dali.yonumen.top/Article/details/gtxdseppcm.html

TS:   console.error("err")
来源：http://dali.jinqigufen.top/Article/details/gtpccimokt.html

Java: System.err.println("err")
来源：http://dali.zhiwuduotai.top/Article/details/gtokrfgyll.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.tanke756.top/Article/details/gtrxswtyjz.html

Ruby: warn "err"
来源：http://dali.shangyingyoupin.top/Article/details/gtyixrbawv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinqigufen.top/Article/details/gtpktrildj.html

[M07] 判断是否为主入口
来源：http://dali.jinghuilouyu.cn/Article/details/gtgbiljwxe.html

Py:   if __name__ == "__main__":
来源：http://dali.iojbl.cn/Article/details/gtevtokzyi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cashguo.top/Article/details/gtwwpvdexb.html

JS:   require.main === module
来源：http://dali.feifeiyinyue.top/Article/details/gtqibmptya.html

TS:   require.main === module
来源：http://dali.tanke756.top/Article/details/gtkytpokqf.html

Java: public static void main(String[] args)
来源：http://dali.yuxming.cn/Article/details/gtfnyvttup.html

Go:   func main()
来源：http://dali.snrcjt.cn/Article/details/gtqemvhmit.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinyuanbaomall.cn/Article/details/gtokkqcorf.html

C#:   static void Main(string[] args)
来源：http://dali.c1oappe.top/Article/details/gtyvhcnkmc.html

[M08] 获取系统与运行时信息
来源：http://dali.smart0.xyz/Article/details/gtpthqnpof.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hongshengwenyu.top/Article/details/gtpwtstqga.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sysykeji.top/Article/details/gtqzsvpbte.html

JS:   process.platform;  process.version
来源：http://dali.jlsjyb.cn/Article/details/gtksquzbhh.html

TS:   process.platform;  process.version
来源：http://dali.jinyuanbaomall.cn/Article/details/gtakgwfurh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.snrcjt.cn/Article/details/gtoihgmpku.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yuanzhike.top/Article/details/gthpoaojxe.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpotqkqwe.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.andypj.xyz/Article/details/gthfvliosf.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtckkgfcsx.html

N. 数据结构与算法
来源：http://dali.jlsjyb.cn/Article/details/gtxobxahnp.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtnjkabvhe.html

[N01] 二分查找（有序数组）
来源：http://dali.sufxvd.cn/Article/details/gtdpxcutsz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtwzzjjjbv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.havefunace.top/Article/details/gtljispuzf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhongyouzk.top/Article/details/gtqtwrqepd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cqqwz.cn/Article/details/gtahgejzqv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxyssadaz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtdbqgswrz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yangfankeji.com/Article/details/gtnwxmnmnu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtacseczno.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ivvv.top/Article/details/gtqacclxyx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.smart0.xyz/Article/details/gtgbyqajgh.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cheryme.top/Article/details/gtjzpevmxo.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.316326.xyz/Article/details/gtesgvoyta.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sysykeji.top/Article/details/gtgnouaksh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.quarkkingdee.top/Article/details/gtttrxchwz.html

Go:   slices.Sort(arr)
来源：http://dali.jqgfzy.top/Article/details/gtqguvcbed.html

Ruby: arr.sort
来源：http://dali.tianlin.xyz/Article/details/gtzopfxfra.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.smart0.xyz/Article/details/gtztetrpax.html

[N03] 快速排序（分治示例）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtggeojgsj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ybcxt.top/Article/details/gtygbexeps.html

PHP:  // 递归实现，或用 usort
来源：http://dali.haohaochexian.top/Article/details/gtsrpwooed.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.316326.xyz/Article/details/gtvqlqdyuz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangdashe.top/Article/details/gtssvnazii.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zycfv.cn/Article/details/gtvvkjwlif.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.c1oappe.top/Article/details/gttudsyiwr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hongshengwenyu.top/Article/details/gtyeqcrdvl.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhengqikj.top/Article/details/gtuckbzuyd.html

[N04] 斐波那契数列
来源：http://dali.shanyushiyangtech.top/Article/details/gttbbvadvj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gaohongyu789.top/Article/details/gtwpwpolcj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.c1oappe.top/Article/details/gttxhzkypp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cucudq.cn/Article/details/gtqclgqqkw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gtovyyqkmy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.c1oappe.top/Article/details/gtlsdecduf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtryoudjxh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yvedp.cn/Article/details/gtorqcorpk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtsuzpxxsb.html

[N05] 最大公约数
来源：http://dali.daxiang520.top/Article/details/gtdufiimnz.html

Py:   math.gcd(a, b)
来源：http://dali.chenzaomai.com/Article/details/gtnskushua.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.guowangkeji.top/Article/details/gtykkjvdcx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxuanxn.top/Article/details/gtfocewvmh.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtecslgnnf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.redwolf501.top/Article/details/gtmicmdlzj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.mhx1999.top/Article/details/gtfuzigpik.html

Ruby: a.gcd(b)
来源：http://dali.fzhhl.top/Article/details/gtlckjfehe.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ybcxt.top/Article/details/gtycftoldb.html

[N06] 判断回文字符串
来源：http://dali.ehwqpu.com/Article/details/gtqshzbghw.html

Py:   s == s[::-1]
来源：http://dali.gzhubu.top/Article/details/gtsajwghlr.html

PHP:  $s === strrev($s);
来源：http://dali.birdmap.top/Article/details/gtldwwumos.html

JS:   s === [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gtttxeqolg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gtsunslwxn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.aizwys.cn/Article/details/gtdiqpmxix.html

Go:   // 双指针从两端比较
来源：http://dali.hnxiangtu.top/Article/details/gtgcfglmmt.html

Ruby: s == s.reverse
来源：http://dali.ybcxt.top/Article/details/gtjnoixvxe.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shangyingyoupin.top/Article/details/gtqdecwebh.html

[N07] 两数之和（返回下标）
来源：http://dali.shuidangran.top/Article/details/gtggfnirrm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zycfv.cn/Article/details/gtzxisdail.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.tianlin.xyz/Article/details/gtchaudzae.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.tianlin.xyz/Article/details/gtasxlhgbh.html

TS:   // 手写 Map<string, number>
来源：http://dali.fengsongda.top/Article/details/gtvmtujkic.html

Java: // 手写 HashMap
来源：http://dali.snrcjt.cn/Article/details/gtegipwxbx.html

Go:   // 手写 map[int]int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdtfwuqhb.html

Ruby: // 手写 Hash
来源：http://dali.chenlongwang.top/Article/details/gthlsnuvkv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.svipenyu.cn/Article/details/gttdvbxyqh.html

[N08] 生成全排列
来源：http://dali.xuetiantiany.cn/Article/details/gtqreqivqv.html

Py:   itertools.permutations(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtqsztgrxy.html

PHP:  // 手写递归交换
来源：http://dali.cdnleiting.top/Article/details/gtrqrewzvn.html

JS:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtgicrurgf.html

TS:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtfacsaxma.html

Java: // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gtokfxqaph.html

Go:   // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gtlgnzlmsy.html

Ruby: arr.permutation.to_a
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcpkmqrwg.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gtuxglumvr.html

[N09] 栈与队列
来源：http://dali.zdqjudy.top/Article/details/gtjxhqdzkj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gogol.net.cn/Article/details/gtamblgdcp.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gtnqidbmem.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.redwolf501.top/Article/details/gtouxjgzyl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.0kj1m.cn/Article/details/gtknbkgqwy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jiagoushi.top/Article/details/gtmzqeithd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gotoacloud.top/Article/details/gtvgclnwjj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gtmdirzipx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cheryme.top/Article/details/gtyixdglxk.html

[N10] 链表节点定义
来源：http://dali.yj20258888.top/Article/details/gtvypdvuzg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.bjfxy.top/Article/details/gtvjrbjssx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhiwuduotai.top/Article/details/gtizboiaof.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.tianlin.xyz/Article/details/gtnwephekc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.dianchejie.cn/Article/details/gtssarpfip.html

Java: class Node { int v; Node next; }
来源：http://dali.quarkkingdee.top/Article/details/gtadsbsekb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gogol.net.cn/Article/details/gtddkgohtp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cucudq.cn/Article/details/gtppaquxrc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcurjmgdu.html

[N11] 二叉树中序遍历
来源：http://dali.cheryme.top/Article/details/gtrzxwcjqf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cucudq.cn/Article/details/gtoroccybk.html

PHP:  // 手写递归函数
来源：http://dali.yangfankeji.com/Article/details/gtostjtxmm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpotneilo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigufen.top/Article/details/gtoediizhf.html

Java: // 手写递归
来源：http://dali.shzxlz.cn/Article/details/gtqxlgwdwn.html

Go:   // 手写递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwupeputy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jqgufenzy.top/Article/details/gtvwykbbaz.html

C#:   // 手写递归
来源：http://dali.sxryk.cn/Article/details/gtjfggwbjo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhongyouzk.top/Article/details/gtuhvzyobu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gtnyhzvxov.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.birdmap.top/Article/details/gtsnbcmdsq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj202588.top/Article/details/gtznfaezmr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yongpay.top/Article/details/gtzlhibfpe.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.wangdashe.top/Article/details/gtgjlejehl.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jyoumei.cn/Article/details/gtggijvzmj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hysaishi.cn/Article/details/gtudrxsucn.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hywenlv.cn/Article/details/gtpunfuaoc.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtydoaihfu.html

O. 并发与异步
来源：http://dali.shanyushiyangtech.top/Article/details/gtnwdqfjii.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtidupbqie.html

[O01] 启动一个线程
来源：http://dali.cucudq.cn/Article/details/gtqquigzos.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhixingplan.top/Article/details/gtyiqfimay.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.guowangkeji.top/Article/details/gtslyhveqr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhoulong.xyz/Article/details/gtbmhpqwpj.html

TS:   // 同 JS
来源：http://dali.hnxiangtu.top/Article/details/gtsmhhiuqd.html

Java: new Thread(() -> f()).start()
来源：http://dali.sufxvd.cn/Article/details/gtbushxbor.html

Go:   go f()
来源：http://dali.cucudq.cn/Article/details/gtlprbmqud.html

Ruby: Thread.new { f }
来源：http://dali.yj202588.top/Article/details/gtlvkiqsmh.html

C#:   Task.Run(() => F());
来源：http://dali.yj20258.top/Article/details/gtfrnpyoeh.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gtxejoolbk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.nanxinkj.top/Article/details/gtmfheqaeo.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cucudq.cn/Article/details/gtzldafhhz.html

JS:   // worker_threads 线程池
来源：http://dali.shzxlz.cn/Article/details/gtjrswkaex.html

TS:   // worker_threads 线程池
来源：http://dali.shzxlz.cn/Article/details/gtscccujsi.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.chenjidiqi.icu/Article/details/gtimehedmy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvxrodeke.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.havefunace.top/Article/details/gthkodkpci.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yonumen.top/Article/details/gtjxpfvhzq.html

[O03] 加锁保护共享数据
来源：http://dali.zdqjudy.top/Article/details/gtehconull.html

Py:   with lock: shared += 1
来源：http://dali.chenjidiqi.icu/Article/details/gtnemaartg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.guowangkeji.top/Article/details/gtxqxwulfo.html


<!-- 参考信息 -->