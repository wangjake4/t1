代发 wailian999

Go:   encoding/gob
来源：http://dali.feifeiyinyue.top/Article/details/gt2fyznywnh.html

Ruby: Marshal.dump(obj)
来源：http://dali.guannengcc.top/Article/details/gt2fvldnjws.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cheryme.top/Article/details/gt2lpiemzcn.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2mtsgdohz.html

L. 网络请求
来源：http://dali.aizwys.cn/Article/details/gt2emdzixss.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2glgmzwni.html

[L01] 发送 GET 请求
来源：http://dali.fzhhl.top/Article/details/gt2gwzakqad.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shzxlz.cn/Article/details/gt2taihxjmx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shangyingyoupin.top/Article/details/gt2xfpgnkzu.html

JS:   await fetch(url)
来源：http://dali.kuanghao11.cn/Article/details/gt2drrkqeun.html

TS:   await fetch(url)
来源：http://dali.feifeiyinyue.top/Article/details/gt2nfnytfgd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hfpthk.cn/Article/details/gt2ncnsbiyu.html

Go:   resp, err := http.Get(url)
来源：http://dali.tanke756.top/Article/details/gt2fdgdjjus.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ehwqpu.com/Article/details/gt2vysrvwtz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.dianchejie.cn/Article/details/gt2yllygxwi.html

[L02] 发送 POST JSON
来源：http://dali.yj20258888.top/Article/details/gt2dmspejia.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ydzc1.top/Article/details/gt2asizfrhn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.feifeiyinyue.top/Article/details/gt2olarfzyr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.bjfxy.top/Article/details/gt2cimwiyvl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhiwuduotai.top/Article/details/gt2rbtoppzj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yj20258.top/Article/details/gt2kopwlyis.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hfpthk.cn/Article/details/gt2nfptfnyp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yj202588.top/Article/details/gt2qhraokqd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhengqikj.top/Article/details/gt2kmxfspbj.html

[L03] 设置自定义请求头
来源：http://dali.yuxming.cn/Article/details/gt2bjvtnsty.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sufxvd.cn/Article/details/gt2yerydbkb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.haohaochexian.top/Article/details/gt2rhnpumsj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sufxvd.cn/Article/details/gt2jrorwmnl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daxiang520.top/Article/details/gt2kwbrqrjn.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yangfankeji.com/Article/details/gt2jarkbcur.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.guowangkeji.top/Article/details/gt2eufnrkcd.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tglemram.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.tianlin.xyz/Article/details/gt2nvbwufbo.html

[L04] 设置超时
来源：http://dali.shanyushiyangtech.top/Article/details/gt2chuxgzkw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.smart0.xyz/Article/details/gt2jjusuixe.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sufxvd.cn/Article/details/gt2unnbzklf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cqqwz.cn/Article/details/gt2ktnncvwx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hywenlv.cn/Article/details/gt2scndbojw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhiwuduotai.top/Article/details/gt2dnmqtrdh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.fzhhl.top/Article/details/gt2dthauidn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinqigfzy.top/Article/details/gt2jwdvywbn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.guannengcc.top/Article/details/gt2hpkvyhie.html

[L05] 上传文件（multipart）
来源：http://dali.zhixingplan.top/Article/details/gt2bnqnzdis.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sxryk.cn/Article/details/gt2nnkvfqid.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.fzhhl.top/Article/details/gt2auqvhocc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shangyingyoupin.top/Article/details/gt2rbcblhkg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yueranfly.top/Article/details/gt2ellgtavg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhixingplan.top/Article/details/gt2acphccto.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.tanke756.top/Article/details/gt2jvyibkuc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhiwuduotai.top/Article/details/gt2uyzoblrg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ybcxt.top/Article/details/gt2vtsekpvm.html

[L06] 解析响应为 JSON
来源：http://dali.ydzc1.top/Article/details/gt2geqwzvai.html

Py:   resp.json()
来源：http://dali.pycfn.com/Article/details/gt2vdtdjiti.html

PHP:  json_decode($body, true);
来源：http://dali.shangyingyoupin.top/Article/details/gt2umtiofkv.html

JS:   await resp.json()
来源：http://dali.wangshuangyany.cn/Article/details/gt2gpoitpwd.html

TS:   await resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qhvpxsjg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hnqzz.top/Article/details/gt2lngwpdze.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hukphwqy.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xylfe.cn/Article/details/gt2kwymmnic.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fqsivfvs.html

[L07] 处理 HTTP 状态码
来源：http://dali.tian-w.cn/Article/details/gt2tfchougx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nanxinkj.top/Article/details/gt2elecuirp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hywenlv.cn/Article/details/gt2bpgbizoe.html

JS:   resp.ok;  resp.status
来源：http://dali.0kj1m.cn/Article/details/gt2axkmakxk.html

TS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hhfwqbaq.html

Java: resp.statusCode()
来源：http://dali.nwbrower.top/Article/details/gt2agxwbqpg.html

Go:   resp.StatusCode
来源：http://dali.nwbrower.top/Article/details/gt2sqfjwyor.html

Ruby: resp.code.to_i
来源：http://dali.zhiwuduotai.top/Article/details/gt2twkwnqbi.html

C#:   (int)resp.StatusCode
来源：http://dali.dashuyun.cn/Article/details/gt2uulrtdcu.html

[L08] 并发请求多个地址
来源：http://dali.jiagoushi.top/Article/details/gt2wtqfcpzi.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.wangshuangyany.cn/Article/details/gt2phzgxrsz.html

PHP:  curl_multi_init() 系列
来源：http://dali.yanxiufei.cn/Article/details/gt2awpoflrz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hywenlv.cn/Article/details/gt2webekrkt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangshuangyany.cn/Article/details/gt2uihequir.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ushxnejw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hnxiangtu.top/Article/details/gt2niacjzrg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yongpay.top/Article/details/gt2irmhaazl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xylfe.cn/Article/details/gt2igyoghci.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2lyrcshtk.html

M. 命令行 / 进程 / 环境
来源：http://dali.tian-w.cn/Article/details/gt2efzblsuv.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2offtdfxf.html

[M01] 读取命令行参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lgtrveja.html

Py:   sys.argv[1:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2plprdrac.html

PHP:  $argv;  $argc;
来源：http://dali.c1oappe.top/Article/details/gt2mxbcanat.html

JS:   process.argv.slice(2)
来源：http://dali.jinqigufen.top/Article/details/gt2wsldmgco.html

TS:   process.argv.slice(2)
来源：http://dali.c1oappe.top/Article/details/gt2nsyrlzav.html

Java: args 数组（main 方法参数）
来源：http://dali.xylfe.cn/Article/details/gt2zjgffwcx.html

Go:   os.Args[1:]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dgxdtvzo.html

Ruby: ARGV
来源：http://dali.yuxming.cn/Article/details/gt2rpowxjwa.html

C#:   args 数组（Main 方法参数）
来源：http://dali.haohaochexian.top/Article/details/gt2rzmpnyqr.html

[M02] 读取环境变量
来源：http://dali.zycfv.cn/Article/details/gt2sushpziu.html

Py:   os.environ.get("HOME")
来源：http://dali.havefunace.top/Article/details/gt2zfwiknmr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.guannengcc.top/Article/details/gt2gpskiqha.html

JS:   process.env.HOME
来源：http://dali.vqdsnc.cn/Article/details/gt2lkzqkbih.html

TS:   process.env.HOME
来源：http://dali.xuanzx.com/Article/details/gt2sqlcopnw.html

Java: System.getenv("HOME")
来源：http://dali.yvedp.cn/Article/details/gt2uyozxfvr.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.tanke756.top/Article/details/gt2drhmwjok.html

Ruby: ENV["HOME"]
来源：http://dali.xinyue.icu/Article/details/gt2mtflnshz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qgbduhqo.html

[M03] 执行外部命令
来源：http://dali.jinqigufen.top/Article/details/gt2apwywlls.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.meibo888.top/Article/details/gt2dwfoetmg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ybcxt.top/Article/details/gt2yjfgdszv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shuidangran.top/Article/details/gt2lncpraos.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jiagoushi.top/Article/details/gt2acaxcwvf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.snrcjt.cn/Article/details/gt2lmmidfqf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hywenlv.cn/Article/details/gt2qeyqupif.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shzxlz.cn/Article/details/gt2zcudnqjn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.guowangkeji.top/Article/details/gt2xstvwplb.html

[M04] 获取当前工作目录
来源：http://dali.sysykeji.top/Article/details/gt2iwuzxchh.html

Py:   os.getcwd()
来源：http://dali.yuxming.cn/Article/details/gt2echceatw.html

PHP:  getcwd();
来源：http://dali.xuetiantiany.cn/Article/details/gt2yqffeuoo.html

JS:   process.cwd()
来源：http://dali.gogol.net.cn/Article/details/gt2ggdtjtgu.html

TS:   process.cwd()
来源：http://dali.hysaishi.cn/Article/details/gt2jxgvoogs.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2frexwppd.html

Go:   os.Getwd()
来源：http://dali.yangfankeji.com/Article/details/gt2vxoauupz.html

Ruby: Dir.pwd
来源：http://dali.xuetiantiany.cn/Article/details/gt2pjmgkycp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xylfe.cn/Article/details/gt2wqlqtcjw.html

[M05] 设置退出码
来源：http://dali.yangfankeji.com/Article/details/gt2ffidzedp.html

Py:   sys.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2cmrbvtzd.html

PHP:  exit(1);
来源：http://dali.hfpthk.cn/Article/details/gt2cupyxrtk.html

JS:   process.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gt2bbjqxjog.html

TS:   process.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gt2hnywbmlm.html

Java: System.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gt2xnlzvgoi.html

Go:   os.Exit(1)
来源：http://dali.0kj1m.cn/Article/details/gt2zlpjugwo.html

Ruby: exit 1
来源：http://dali.smart0.xyz/Article/details/gt2ywrgbpds.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhoulong.xyz/Article/details/gt2eonlwwyj.html

[M06] 向标准错误输出
来源：http://dali.c1oappe.top/Article/details/gt2hkazcbhu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.nwbrower.top/Article/details/gt2wfqdbtkb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hfpthk.cn/Article/details/gt2zvrauyhm.html

JS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gt2jdflblcm.html

TS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gt2xhmflxbz.html

Java: System.err.println("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fajlikzr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2odkpacxf.html

Ruby: warn "err"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hvuwmrzh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinqigfzy.top/Article/details/gt2pqkuxuvf.html

[M07] 判断是否为主入口
来源：http://dali.mhx1999.top/Article/details/gt2cskvodhz.html

Py:   if __name__ == "__main__":
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nttpveyl.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sysykeji.top/Article/details/gt2owvkbzou.html

JS:   require.main === module
来源：http://dali.zdqjudy.top/Article/details/gt2ftwlqkiy.html

TS:   require.main === module
来源：http://dali.shuidangran.top/Article/details/gt2avkuibuq.html

Java: public static void main(String[] args)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fnmjwyrh.html

Go:   func main()
来源：http://dali.tanke756.top/Article/details/gt2qetacxxg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sxryk.cn/Article/details/gt2mbliwlna.html

C#:   static void Main(string[] args)
来源：http://dali.hammf.cn/Article/details/gt2sxovdgcc.html

[M08] 获取系统与运行时信息
来源：http://dali.nanxinkj.top/Article/details/gt2efwphscq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sweek.top/Article/details/gt2chvlltyu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yanxiufei.cn/Article/details/gt2txusxhzv.html

JS:   process.platform;  process.version
来源：http://dali.316326.xyz/Article/details/gt2rmmbipfz.html

TS:   process.platform;  process.version
来源：http://dali.quarkkingdee.top/Article/details/gt2gtdjccip.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ydzc1.top/Article/details/gt2ykejsagh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xziqi.cn/Article/details/gt2odlqpcos.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.316326.xyz/Article/details/gt2jdpzemxe.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.guannengcc.top/Article/details/gt2onweoctl.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2ovzxaxqz.html

N. 数据结构与算法
来源：http://dali.xylfe.cn/Article/details/gt2ynsouyoq.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2hzflsjry.html

[N01] 二分查找（有序数组）
来源：http://dali.chenlongwang.top/Article/details/gt2xgswfaas.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gt2oaftuhbe.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.pycfn.com/Article/details/gt2ghbsgxxp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgufenzy.top/Article/details/gt2qavbsmmm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258.top/Article/details/gt2zbcsofec.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2dalvonyi.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gt2xjtzdlyq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2iveecnsv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gt2eajborqb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sufxvd.cn/Article/details/gt2pljfzhgt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tian-w.cn/Article/details/gt2qwgturfp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zycfv.cn/Article/details/gt2xslhbbfd.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yanxiufei.cn/Article/details/gt2zdnfvpag.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sufxvd.cn/Article/details/gt2woqxeual.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yj20258888.top/Article/details/gt2diqcopys.html

Go:   slices.Sort(arr)
来源：http://dali.yj20258888.top/Article/details/gt2pcuixpii.html

Ruby: arr.sort
来源：http://dali.yangfankeji.com/Article/details/gt2fbnqewts.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.aizwys.cn/Article/details/gt2qfqlzvje.html

[N03] 快速排序（分治示例）
来源：http://dali.fzhhl.top/Article/details/gt2pnpphhxl.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xylfe.cn/Article/details/gt2hoboyymp.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yangfankeji.com/Article/details/gt2zsyojbbf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.mhx1999.top/Article/details/gt2oshtvbhc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hywenlv.cn/Article/details/gt2wyzspkhn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yonumen.top/Article/details/gt2evpvdogd.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.iojbl.cn/Article/details/gt2cqavanyr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.andypj.xyz/Article/details/gt2ycdhywra.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhongyouzk.top/Article/details/gt2raaihrzr.html

[N04] 斐波那契数列
来源：http://dali.zdqjudy.top/Article/details/gt2kdimrtul.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigufen.top/Article/details/gt2egkvhflf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.andypj.xyz/Article/details/gt2twammfpw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnxiangtu.top/Article/details/gt2czupjlvo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.smart0.xyz/Article/details/gt2gmchfuxv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xinyue.icu/Article/details/gt2akspzgje.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qoqfvppm.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nfxbzeeu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yonumen.top/Article/details/gt2xfxaveau.html

[N05] 最大公约数
来源：http://dali.nanxinkj.top/Article/details/gt2hcuaxofr.html

Py:   math.gcd(a, b)
来源：http://dali.tian-w.cn/Article/details/gt2ecikjimy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sweek.top/Article/details/gt2shflktrl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hammf.cn/Article/details/gt2qyvwwdep.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2zhuhfeoo.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.pengpengdd.cyou/Article/details/gt2ieujprbk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fetbukxu.html

Ruby: a.gcd(b)
来源：http://dali.quarkkingdee.top/Article/details/gt2hrizhvei.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.0kj1m.cn/Article/details/gt2viuupiuz.html

[N06] 判断回文字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2pztqvoda.html

Py:   s == s[::-1]
来源：http://dali.cdnleiting.top/Article/details/gt2hrklxcoe.html

PHP:  $s === strrev($s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2urdvjomi.html

JS:   s === [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gt2gyscbfyn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gt2jqkryltm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.pycfn.com/Article/details/gt2fhnnvxke.html

Go:   // 双指针从两端比较
来源：http://dali.sysykeji.top/Article/details/gt2gddzjwae.html

Ruby: s == s.reverse
来源：http://dali.vqdsnc.cn/Article/details/gt2eezfeqmz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shangyingyoupin.top/Article/details/gt2dbwqgthf.html

[N07] 两数之和（返回下标）
来源：http://dali.hfpthk.cn/Article/details/gt2wqvyumbd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.havefunace.top/Article/details/gt2eakfkkmb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zdqjudy.top/Article/details/gt2ugnhcdlo.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cqqwz.cn/Article/details/gt2kthvedbc.html

TS:   // 手写 Map<string, number>
来源：http://dali.svipenyu.cn/Article/details/gt2bkyiutuj.html

Java: // 手写 HashMap
来源：http://dali.jqgfzy.top/Article/details/gt2afqxxmka.html

Go:   // 手写 map[int]int
来源：http://dali.fengsongda.top/Article/details/gt2ojvolybj.html

Ruby: // 手写 Hash
来源：http://dali.wangdashe.top/Article/details/gt2yypezxgt.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vhxewhse.html

[N08] 生成全排列
来源：http://dali.hnqzz.top/Article/details/gt2qzdzqzct.html

Py:   itertools.permutations(arr)
来源：http://dali.sxryk.cn/Article/details/gt2evpluxqd.html

PHP:  // 手写递归交换
来源：http://dali.jlsjyb.cn/Article/details/gt2nyqzhkjq.html

JS:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gt2hncftnoh.html

TS:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gt2dlaaowsn.html

Java: // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gt2dcakdmut.html

Go:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gt2oprwbrps.html

Ruby: arr.permutation.to_a
来源：http://dali.ppjwa.cn/Article/details/gt2bvfaxsyb.html

C#:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gt2zosbbhlg.html

[N09] 栈与队列
来源：http://dali.wangdashe.top/Article/details/gt2agvhzsuk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yvedp.cn/Article/details/gt2asprualn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cicwvucn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gt2nofrrrmq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.tianlin.xyz/Article/details/gt2dwfbnqdv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhengqikj.top/Article/details/gt2mdoyzunj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.quarkkingdee.top/Article/details/gt2fcpuyrkc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nwbrower.top/Article/details/gt2dnycrfjc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jlsjyb.cn/Article/details/gt2mikvudsi.html

[N10] 链表节点定义
来源：http://dali.havefunace.top/Article/details/gt2vfiihdnf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jqgfzy.top/Article/details/gt2hglxlxfz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2okohqxoy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.chenjidiqi.icu/Article/details/gt2dpezameg.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.tian-w.cn/Article/details/gt2lkoxovil.html

Java: class Node { int v; Node next; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pyzfftrc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.smart0.xyz/Article/details/gt2lvqawzpq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ixksrqva.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ivvv.top/Article/details/gt2sapkpfnh.html

[N11] 二叉树中序遍历
来源：http://dali.sysykeji.top/Article/details/gt2ulfocmup.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xuanzx.com/Article/details/gt2gbclkkbi.html

PHP:  // 手写递归函数
来源：http://dali.iojbl.cn/Article/details/gt2znxxprln.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xuetiantiany.cn/Article/details/gt2joshxbph.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xinyue.icu/Article/details/gt2gtduzceh.html

Java: // 手写递归
来源：http://dali.tian-w.cn/Article/details/gt2mgxxazfm.html

Go:   // 手写递归
来源：http://dali.chenzaomai.com/Article/details/gt2ctkfugfa.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.chenjidiqi.icu/Article/details/gt2vheliqfn.html

C#:   // 手写递归
来源：http://dali.yuxming.cn/Article/details/gt2wygdzruc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xziqi.cn/Article/details/gt2aorzolxx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mvwxhzfm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gogol.net.cn/Article/details/gt2jsepimqu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qkxjaaaw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenjidiqi.icu/Article/details/gt2khgwfrys.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj202588.top/Article/details/gt2liuzopqt.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.birdmap.top/Article/details/gt2zufxbcaf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ypqnmlom.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.feifeiyinyue.top/Article/details/gt2idihtpuv.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2ioylizvo.html

O. 并发与异步
来源：http://dali.hnqzz.top/Article/details/gt2xeksvpqk.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2ryzklrwi.html

[O01] 启动一个线程
来源：http://dali.yuanzhike.top/Article/details/gt2hnuhcngh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yawgrgeu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jlsjyb.cn/Article/details/gt2utgngubk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cucudq.cn/Article/details/gt2fqddpitr.html

TS:   // 同 JS
来源：http://dali.gzhubu.top/Article/details/gt2cidxuqeb.html

Java: new Thread(() -> f()).start()
来源：http://dali.cqqwz.cn/Article/details/gt2phjylczh.html

Go:   go f()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jbcrpqnn.html

Ruby: Thread.new { f }
来源：http://dali.cucudq.cn/Article/details/gt2wjnbmaut.html

C#:   Task.Run(() => F());
来源：http://dali.hysaishi.cn/Article/details/gt2ggibsmez.html

[O02] 使用线程池
来源：http://dali.yuanzhike.top/Article/details/gt2ctjmixoj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.chenzaomai.com/Article/details/gt2rltmfbhr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ppjwa.cn/Article/details/gt2dkddcdji.html

JS:   // worker_threads 线程池
来源：http://dali.hywenlv.cn/Article/details/gt2staaqgwu.html

TS:   // worker_threads 线程池
来源：http://dali.mhx1999.top/Article/details/gt2fnihfblf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.bjfxy.top/Article/details/gt2mxluiyan.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yangfankeji.com/Article/details/gt2sbixdnhi.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.chenjidiqi.icu/Article/details/gt2vgogtrop.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zmzhphtj.html

[O03] 加锁保护共享数据
来源：http://dali.c1oappe.top/Article/details/gt2rafojxri.html

Py:   with lock: shared += 1
来源：http://dali.nanxinkj.top/Article/details/gt2tkloxezf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sxryk.cn/Article/details/gt2nhvyxskh.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yuanzhike.top/Article/details/gt2kxcesovy.html

TS:   // 同 JS
来源：http://dali.yongpay.top/Article/details/gt2etsuyscx.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ffeaqghv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhixingplan.top/Article/details/gt2ragidpan.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2crtaegbs.html

C#:   lock (gate) { shared++; }
来源：http://dali.daria6918.cn/Article/details/gt2kipreyni.html

[O04] 定义异步函数并等待
来源：http://dali.aizwys.cn/Article/details/gt2cvqmsvpw.html

Py:   async def f():⏎    await g()
来源：http://dali.aibaodan.cn/Article/details/gt2pdzmpfjc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.mhx1999.top/Article/details/gt2qxdbpbio.html

JS:   async function f() { await g(); }
来源：http://dali.jianghu66.top/Article/details/gt2sapnkxmn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.mhx1999.top/Article/details/gt2rqtkpdwp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shangyingyoupin.top/Article/details/gt2larzzmam.html


<!-- 参考信息 -->