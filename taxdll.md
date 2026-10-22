代发 wailian999

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mihjhcue.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jfsyfpxp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.bjfxy.top/Article/details/gt2mzdnpmaa.html

Py:   pickle.dumps(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2oxsegdlu.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nanxinkj.top/Article/details/gt2mpetfixx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gogol.net.cn/Article/details/gt2cdtyagji.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zdqjudy.top/Article/details/gt2qfgtdzoo.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hysaishi.cn/Article/details/gt2utqouxdb.html

Go:   encoding/gob
来源：http://dali.pycfn.com/Article/details/gt2qilzmxam.html

Ruby: Marshal.dump(obj)
来源：http://dali.havefunace.top/Article/details/gt2lkgwweoa.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.chenlongwang.top/Article/details/gt2vguqyvyi.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2tsecixfl.html

L. 网络请求
来源：http://dali.andypj.xyz/Article/details/gt2lpribuqk.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2ljwpjamz.html

[L01] 发送 GET 请求
来源：http://dali.sweek.top/Article/details/gt2fipkhurj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yuxming.cn/Article/details/gt2pktnipzs.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hnqzz.top/Article/details/gt2dbvzmauh.html

JS:   await fetch(url)
来源：http://dali.zdqjudy.top/Article/details/gt2yrjtzbur.html

TS:   await fetch(url)
来源：http://dali.hongshengwenyu.top/Article/details/gt2tezfymbo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenjidiqi.icu/Article/details/gt2mfxjmqki.html

Go:   resp, err := http.Get(url)
来源：http://dali.vqdsnc.cn/Article/details/gt2jdibipdr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ydzc1.top/Article/details/gt2atuodcof.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.bjfxy.top/Article/details/gt2qisnnybx.html

[L02] 发送 POST JSON
来源：http://dali.gaohongyu789.top/Article/details/gt2jhynyjmf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.dashuyun.cn/Article/details/gt2nmkksbtn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhoulong.xyz/Article/details/gt2mywwzazm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhoulong.xyz/Article/details/gt2sjrjixgg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gogol.net.cn/Article/details/gt2zvaockfm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jlsjyb.cn/Article/details/gt2hxhrqogj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.0kj1m.cn/Article/details/gt2fhcffntg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xinyue.icu/Article/details/gt2ufrhqqxv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yanxiufei.cn/Article/details/gt2eeevuwzy.html

[L03] 设置自定义请求头
来源：http://dali.quarkkingdee.top/Article/details/gt2lwmirhmj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.nanxinkj.top/Article/details/gt2awkiroth.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.aibaodan.cn/Article/details/gt2lddscwgf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shangyingyoupin.top/Article/details/gt2sdwkdzqp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tianlin.xyz/Article/details/gt2ynjzjfus.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.c1oappe.top/Article/details/gt2ndamnsim.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ybcxt.top/Article/details/gt2wcvoqysr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yuxming.cn/Article/details/gt2wliwlsdv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yuxming.cn/Article/details/gt2xicdaexj.html

[L04] 设置超时
来源：http://dali.yanxiufei.cn/Article/details/gt2xdfnnvxp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.guowangkeji.top/Article/details/gt2bpjkeepu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cqqwz.cn/Article/details/gt2yrctjutv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xylfe.cn/Article/details/gt2ulexmtsq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ydzc1.top/Article/details/gt2izbgsfyb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jlsjyb.cn/Article/details/gt2zdbjiyfm.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.nanxuanxn.top/Article/details/gt2upexqcyr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.redwolf501.top/Article/details/gt2wprsiqka.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hywenlv.cn/Article/details/gt2uckmdiur.html

[L05] 上传文件（multipart）
来源：http://dali.tanke756.top/Article/details/gt2pjigqzie.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jlsjyb.cn/Article/details/gt2jdmzdtbn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yuanzhike.top/Article/details/gt2aitvcssf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shangyingyoupin.top/Article/details/gt2dntbfhpk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmdzmgw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hnxiangtu.top/Article/details/gt2mtnkpuax.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cdnleiting.top/Article/details/gt2toukvedu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xuetiantiany.cn/Article/details/gt2cozkspiu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.bjfxy.top/Article/details/gt2eimcnord.html

[L06] 解析响应为 JSON
来源：http://dali.yuxming.cn/Article/details/gt2krxtcqrz.html

Py:   resp.json()
来源：http://dali.hnxiangtu.top/Article/details/gt2jlavkijd.html

PHP:  json_decode($body, true);
来源：http://dali.xuanzx.com/Article/details/gt2ehrvwgib.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2mibzrqkh.html

TS:   await resp.json()
来源：http://dali.yanxiufei.cn/Article/details/gt2saweoaih.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jiagoushi.top/Article/details/gt2trvpjtcb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.kuanghao11.cn/Article/details/gt2faimrzml.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ivvv.top/Article/details/gt2lcezjzgu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jqgufenzy.top/Article/details/gt2ibipeapw.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ncixhfvg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.wangdashe.top/Article/details/gt2nqcumwxf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ybcxt.top/Article/details/gt2lexghbpu.html

JS:   resp.ok;  resp.status
来源：http://dali.nanxinkj.top/Article/details/gt2ndlgtzat.html

TS:   resp.ok;  resp.status
来源：http://dali.zhoulong.xyz/Article/details/gt2alphbaxy.html

Java: resp.statusCode()
来源：http://dali.hammf.cn/Article/details/gt2cyergtao.html

Go:   resp.StatusCode
来源：http://dali.0kj1m.cn/Article/details/gt2dggweidt.html

Ruby: resp.code.to_i
来源：http://dali.chenzaomai.com/Article/details/gt2ejebztjr.html

C#:   (int)resp.StatusCode
来源：http://dali.wangdashe.top/Article/details/gt2ipaftnqk.html

[L08] 并发请求多个地址
来源：http://dali.hammf.cn/Article/details/gt2zeokqmev.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xuetiantiany.cn/Article/details/gt2ykrncpjk.html

PHP:  curl_multi_init() 系列
来源：http://dali.yanxiufei.cn/Article/details/gt2oqhisaxy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj202588.top/Article/details/gt2kcgjkrcd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cheryme.top/Article/details/gt2vrinpvze.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.chenjidiqi.icu/Article/details/gt2sryaihzq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shangyingyoupin.top/Article/details/gt2blajflwq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sysykeji.top/Article/details/gt2kttjcrzn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhoulong.xyz/Article/details/gt2vcuvszsg.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2kdsqamoq.html

M. 命令行 / 进程 / 环境
来源：http://dali.redwolf501.top/Article/details/gt2vivltfmv.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2karntsjz.html

[M01] 读取命令行参数
来源：http://dali.shuidangran.top/Article/details/gt2vcbgnnxe.html

Py:   sys.argv[1:]
来源：http://dali.zhoulong.xyz/Article/details/gt2xssrowci.html

PHP:  $argv;  $argc;
来源：http://dali.jiagoushi.top/Article/details/gt2gtbaisof.html

JS:   process.argv.slice(2)
来源：http://dali.yangfankeji.com/Article/details/gt2wacbinnf.html

TS:   process.argv.slice(2)
来源：http://dali.zhoulong.xyz/Article/details/gt2awfpgrsg.html

Java: args 数组（main 方法参数）
来源：http://dali.zdqjudy.top/Article/details/gt2kyzmsqey.html

Go:   os.Args[1:]
来源：http://dali.andypj.xyz/Article/details/gt2awlijhli.html

Ruby: ARGV
来源：http://dali.xziqi.cn/Article/details/gt2ofpihvnf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.fzhhl.top/Article/details/gt2gurrrydw.html

[M02] 读取环境变量
来源：http://dali.yuxming.cn/Article/details/gt2xymgwnex.html

Py:   os.environ.get("HOME")
来源：http://dali.jinqigufen.top/Article/details/gt2qcocvmca.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ptqmoxop.html

JS:   process.env.HOME
来源：http://dali.sxryk.cn/Article/details/gt2byzznykh.html

TS:   process.env.HOME
来源：http://dali.hywenlv.cn/Article/details/gt2ebfvcahk.html

Java: System.getenv("HOME")
来源：http://dali.sufxvd.cn/Article/details/gt2usaqcksl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2iayxqgop.html

Ruby: ENV["HOME"]
来源：http://dali.xziqi.cn/Article/details/gt2qwrgrmfn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xuanzx.com/Article/details/gt2rtuxuhua.html

[M03] 执行外部命令
来源：http://dali.havefunace.top/Article/details/gt2mdfmjzpa.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sxryk.cn/Article/details/gt2wefttrkz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.dashuyun.cn/Article/details/gt2xcpgzmgo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.c1oappe.top/Article/details/gt2vklgyzaz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jianghu66.top/Article/details/gt2urserzwc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2amfabxpc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.316326.xyz/Article/details/gt2vpfcplsg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhongyouzk.top/Article/details/gt2fhdrkjnr.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yj20258888.top/Article/details/gt2ypygpiza.html

[M04] 获取当前工作目录
来源：http://dali.gogol.net.cn/Article/details/gt2pusaoubn.html

Py:   os.getcwd()
来源：http://dali.ehwqpu.com/Article/details/gt2gjecwity.html

PHP:  getcwd();
来源：http://dali.haohaochexian.top/Article/details/gt2hjtffhdy.html

JS:   process.cwd()
来源：http://dali.ydzc1.top/Article/details/gt2cbnparvy.html

TS:   process.cwd()
来源：http://dali.yuxming.cn/Article/details/gt2vezwmmqa.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ovzccsgk.html

Go:   os.Getwd()
来源：http://dali.xuetiantiany.cn/Article/details/gt2bjdfnanh.html

Ruby: Dir.pwd
来源：http://dali.dianchejie.cn/Article/details/gt2ygyonhzy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lidccsbq.html

[M05] 设置退出码
来源：http://dali.ivvv.top/Article/details/gt2czggssoz.html

Py:   sys.exit(1)
来源：http://dali.bjfxy.top/Article/details/gt2jtqleejh.html

PHP:  exit(1);
来源：http://dali.vqdsnc.cn/Article/details/gt2ldfuymdd.html

JS:   process.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gt2bjuvjokc.html

TS:   process.exit(1)
来源：http://dali.xinyue.icu/Article/details/gt2qljnrhii.html

Java: System.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gt2ptmakwvt.html

Go:   os.Exit(1)
来源：http://dali.bjfxy.top/Article/details/gt2ypjfhikq.html

Ruby: exit 1
来源：http://dali.snrcjt.cn/Article/details/gt2tdmwflgv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xuanzx.com/Article/details/gt2ejnfxstd.html

[M06] 向标准错误输出
来源：http://dali.andypj.xyz/Article/details/gt2hlmcyida.html

Py:   print("err", file=sys.stderr)
来源：http://dali.aibaodan.cn/Article/details/gt2rufsfyci.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jyoumei.cn/Article/details/gt2hiqtxetb.html

JS:   console.error("err")
来源：http://dali.snrcjt.cn/Article/details/gt2leawwahb.html

TS:   console.error("err")
来源：http://dali.cqqwz.cn/Article/details/gt2wvswompd.html

Java: System.err.println("err")
来源：http://dali.aizwys.cn/Article/details/gt2twihiwmq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.c1oappe.top/Article/details/gt2madtjaxf.html

Ruby: warn "err"
来源：http://dali.yj20258888.top/Article/details/gt2feklrcjc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gaohongyu789.top/Article/details/gt2gsewgcqr.html

[M07] 判断是否为主入口
来源：http://dali.hysaishi.cn/Article/details/gt2lqgsqzlw.html

Py:   if __name__ == "__main__":
来源：http://dali.andypj.xyz/Article/details/gt2dgbtoerz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cucudq.cn/Article/details/gt2esfjcqvu.html

JS:   require.main === module
来源：http://dali.fengsongda.top/Article/details/gt2knnjxagp.html

TS:   require.main === module
来源：http://dali.xziqi.cn/Article/details/gt2aejyywsx.html

Java: public static void main(String[] args)
来源：http://dali.hongshengwenyu.top/Article/details/gt2irprmmcy.html

Go:   func main()
来源：http://dali.zhiwuduotai.top/Article/details/gt2fznbjuaj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yueranfly.top/Article/details/gt2udeepxuf.html

C#:   static void Main(string[] args)
来源：http://dali.cqqwz.cn/Article/details/gt2eskmpknd.html

[M08] 获取系统与运行时信息
来源：http://dali.zhongyouzk.top/Article/details/gt2cozkcqfs.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shangyingyoupin.top/Article/details/gt2vrhhjknw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shuidangran.top/Article/details/gt2pgqoleth.html

JS:   process.platform;  process.version
来源：http://dali.shzxlz.cn/Article/details/gt2wcrvojjc.html

TS:   process.platform;  process.version
来源：http://dali.jqgufenzy.top/Article/details/gt2ogrbqmwy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wwiuowqd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cqqwz.cn/Article/details/gt2eqmhfjee.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yj202588.top/Article/details/gt2yllxeqin.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.aibaodan.cn/Article/details/gt2nkdgcqlw.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2ilbjdxbi.html

N. 数据结构与算法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gkjfggev.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2ugqldetc.html

[N01] 二分查找（有序数组）
来源：http://dali.aibaodan.cn/Article/details/gt2zadfsflg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ivvv.top/Article/details/gt2pxeahqac.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.tianlin.xyz/Article/details/gt2qojuabkb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ppjwa.cn/Article/details/gt2lxovfxnz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnqzz.top/Article/details/gt2wjmmkdhc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gt2naofipvr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gt2ucytjbrw.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ehwqpu.com/Article/details/gt2xqmwhazh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gt2zkcdtawr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jeijddmh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.c1oappe.top/Article/details/gt2bogytfra.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.316326.xyz/Article/details/gt2anwbztnp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yangfankeji.com/Article/details/gt2wzigkxjn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenzaomai.com/Article/details/gt2xotmduug.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.0kj1m.cn/Article/details/gt2cbfcdtol.html

Go:   slices.Sort(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2xlounyer.html

Ruby: arr.sort
来源：http://dali.sufxvd.cn/Article/details/gt2fmjnsyou.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.sysykeji.top/Article/details/gt2rcygiqdw.html

[N03] 快速排序（分治示例）
来源：http://dali.havefunace.top/Article/details/gt2lquuvuud.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yuanzhike.top/Article/details/gt2mbmkckjt.html

PHP:  // 递归实现，或用 usort
来源：http://dali.guowangkeji.top/Article/details/gt2wcqnsqjr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aizwys.cn/Article/details/gt2roxlhmsn.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tianlin.xyz/Article/details/gt2vlmsrkkn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yanxiufei.cn/Article/details/gt2yqdcghmc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jianghu66.top/Article/details/gt2yuoqcmof.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.wangshuangyany.cn/Article/details/gt2gggrsmsu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.smart0.xyz/Article/details/gt2pxnyhiyi.html

[N04] 斐波那契数列
来源：http://dali.svipenyu.cn/Article/details/gt2nktrgalc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.316326.xyz/Article/details/gt2smcmknyc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gzhubu.top/Article/details/gt2tvlxbcnr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xylfe.cn/Article/details/gt2sztmltav.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxuanxn.top/Article/details/gt2kliugdyt.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.daxiang520.top/Article/details/gt2skgaiwbk.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.wangdashe.top/Article/details/gt2irhzezup.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jiagoushi.top/Article/details/gt2peqvhgaa.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ppjwa.cn/Article/details/gt2zkwqneeq.html

[N05] 最大公约数
来源：http://dali.jinqigufen.top/Article/details/gt2ehvvqazf.html

Py:   math.gcd(a, b)
来源：http://dali.zhixingplan.top/Article/details/gt2zkolkfge.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yuxming.cn/Article/details/gt2npkeygyw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fengsongda.top/Article/details/gt2nucvmesu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxinkj.top/Article/details/gt2lahzsebp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.tianlin.xyz/Article/details/gt2lsnzvncl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhixingplan.top/Article/details/gt2ozzuxwhu.html

Ruby: a.gcd(b)
来源：http://dali.birdmap.top/Article/details/gt2etqufmwq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ppjwa.cn/Article/details/gt2zjenntwu.html

[N06] 判断回文字符串
来源：http://dali.sweek.top/Article/details/gt2fzfyxtvf.html

Py:   s == s[::-1]
来源：http://dali.pycfn.com/Article/details/gt2yzdorffx.html

PHP:  $s === strrev($s);
来源：http://dali.ydzc1.top/Article/details/gt2auplpmni.html

JS:   s === [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gt2ltxjvweb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gt2osgqczki.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.daxiang520.top/Article/details/gt2hgbfghxx.html

Go:   // 双指针从两端比较
来源：http://dali.yj202588.top/Article/details/gt2pkhtsjam.html

Ruby: s == s.reverse
来源：http://dali.smart0.xyz/Article/details/gt2egzdphms.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rdqayhzt.html

[N07] 两数之和（返回下标）
来源：http://dali.zhiwuduotai.top/Article/details/gt2tgzhmvvd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.guannengcc.top/Article/details/gt2gzmpllnr.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zwtjfptd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhixingplan.top/Article/details/gt2fwoovckx.html

TS:   // 手写 Map<string, number>
来源：http://dali.aizwys.cn/Article/details/gt2xomhdcma.html

Java: // 手写 HashMap
来源：http://dali.iojbl.cn/Article/details/gt2nubvkiea.html

Go:   // 手写 map[int]int
来源：http://dali.hongshengwenyu.top/Article/details/gt2dimhirbn.html

Ruby: // 手写 Hash
来源：http://dali.sysykeji.top/Article/details/gt2dbusctfr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hammf.cn/Article/details/gt2slprkcki.html

[N08] 生成全排列
来源：http://dali.gotoacloud.top/Article/details/gt2ixzjddon.html

Py:   itertools.permutations(arr)
来源：http://dali.ppjwa.cn/Article/details/gt2ljkbytvl.html

PHP:  // 手写递归交换
来源：http://dali.chenzaomai.com/Article/details/gt2ilwjeolx.html

JS:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gt2xcbrywgp.html

TS:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gt2aupkflzg.html

Java: // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gt2xrhlrapz.html

Go:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gt2qjnegzcv.html

Ruby: arr.permutation.to_a
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pjsgrbrj.html

C#:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gt2broqmocd.html

[N09] 栈与队列
来源：http://dali.jqgfzy.top/Article/details/gt2mqoxhopu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gt2fowcggar.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.daxiang520.top/Article/details/gt2nwzofywd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xinyue.icu/Article/details/gt2darmfvkz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gzhubu.top/Article/details/gt2icromrer.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2juiqwvwu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hnxiangtu.top/Article/details/gt2mzrukasf.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jybusshj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hammf.cn/Article/details/gt2mwnhssnm.html

[N10] 链表节点定义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ysrqyguy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhoulong.xyz/Article/details/gt2aubydybv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yonumen.top/Article/details/gt2wigswfdu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hywenlv.cn/Article/details/gt2qxadoaru.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yvedp.cn/Article/details/gt2lmouqxbf.html

Java: class Node { int v; Node next; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2wwufkyae.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.feifeiyinyue.top/Article/details/gt2kyoqfwqs.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cqqwz.cn/Article/details/gt2bhsetrhd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xziqi.cn/Article/details/gt2byctlmfs.html

[N11] 二叉树中序遍历
来源：http://dali.haohaochexian.top/Article/details/gt2zygzveju.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.9152youxi.cn/Article/details/gt2beghguxe.html

PHP:  // 手写递归函数
来源：http://dali.chenlongwang.top/Article/details/gt2kwtmnzap.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.316326.xyz/Article/details/gt2uutgrriv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ndvriozs.html

Java: // 手写递归
来源：http://dali.aibaodan.cn/Article/details/gt2cybzuybs.html

Go:   // 手写递归
来源：http://dali.yj20258888.top/Article/details/gt2jcejqqjc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.haohaochexian.top/Article/details/gt2yhdgqsme.html

C#:   // 手写递归
来源：http://dali.chenzaomai.com/Article/details/gt2vwqdzhgm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.tanke756.top/Article/details/gt2ibiqjsti.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.kuanghao11.cn/Article/details/gt2mzqmnhkn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dhlenpvr.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tmevhbsw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zdqjudy.top/Article/details/gt2eytuqkul.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jecvhzpa.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ehwqpu.com/Article/details/gt2kpsgmkbm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yj202588.top/Article/details/gt2umdhnmqy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sufxvd.cn/Article/details/gt2vxvlpcxn.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2zmezqkau.html

O. 并发与异步
来源：http://dali.zhixingplan.top/Article/details/gt2vtmrhuhc.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2qljuslaz.html

[O01] 启动一个线程
来源：http://dali.hammf.cn/Article/details/gt2pmnxacot.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xuanzx.com/Article/details/gt2oaghmitf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.birdmap.top/Article/details/gt2eohpcnsn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.chenzaomai.com/Article/details/gt2maguedsa.html

TS:   // 同 JS
来源：http://dali.sweek.top/Article/details/gt2zbogjgzx.html

Java: new Thread(() -> f()).start()
来源：http://dali.fengsongda.top/Article/details/gt2elqvsuuq.html

Go:   go f()
来源：http://dali.gotoacloud.top/Article/details/gt2xjnnntyx.html

Ruby: Thread.new { f }
来源：http://dali.yangfankeji.com/Article/details/gt2tcmkzvur.html

C#:   Task.Run(() => F());
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xlisnaaa.html

[O02] 使用线程池
来源：http://dali.sufxvd.cn/Article/details/gt2geuomkbd.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinqigfzy.top/Article/details/gt2hjadseqc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.aibaodan.cn/Article/details/gt2nbfwggih.html

JS:   // worker_threads 线程池
来源：http://dali.cheryme.top/Article/details/gt2fpjdxaaq.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2aaadxter.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cashguo.top/Article/details/gt2mlcejxmj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jqgufenzy.top/Article/details/gt2mapewmgc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.daxiang520.top/Article/details/gt2gkobftwo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cucudq.cn/Article/details/gt2jduoncyt.html

[O03] 加锁保护共享数据
来源：http://dali.jiagoushi.top/Article/details/gt2hvzxqbze.html

Py:   with lock: shared += 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vpuwiohz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cinanuxi.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhixingplan.top/Article/details/gt2qcyoqyuo.html

TS:   // 同 JS
来源：http://dali.xziqi.cn/Article/details/gt2zojgfvvy.html

Java: synchronized (this) { shared++; }
来源：http://dali.xinyue.icu/Article/details/gt2afkyyhvj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sufxvd.cn/Article/details/gt2octfxpkd.html


<!-- 参考信息 -->