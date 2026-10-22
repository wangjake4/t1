代发 wailian999

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.meibo888.top/Article/details/gt2wdufwkbh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.mhx1999.top/Article/details/gt2viagsest.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhengqikj.top/Article/details/gt2ratsfdlw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ehwqpu.com/Article/details/gt2rhdbubtt.html

Go:   encoding/gob
来源：http://dali.yj202588.top/Article/details/gt2ahtmstza.html

Ruby: Marshal.dump(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2oxtpxyyq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.wangdashe.top/Article/details/gt2sxmedqbt.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2azddsvif.html

L. 网络请求
来源：http://dali.xuetiantiany.cn/Article/details/gt2qnwjxrdy.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2csrvyrqe.html

[L01] 发送 GET 请求
来源：http://dali.jqgfzy.top/Article/details/gt2ooirrhnh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sufxvd.cn/Article/details/gt2odppjjgb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.iojbl.cn/Article/details/gt2dqalcobn.html

JS:   await fetch(url)
来源：http://dali.gaohongyu789.top/Article/details/gt2crlmswtv.html

TS:   await fetch(url)
来源：http://dali.sweek.top/Article/details/gt2tpswwriw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ydzc1.top/Article/details/gt2ybnnisqc.html

Go:   resp, err := http.Get(url)
来源：http://dali.yj202588.top/Article/details/gt2zmfrwrot.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jqgufenzy.top/Article/details/gt2ohwwppxd.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.iojbl.cn/Article/details/gt2vubdxdyc.html

[L02] 发送 POST JSON
来源：http://dali.tianlin.xyz/Article/details/gt2wejgkrmb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gzhubu.top/Article/details/gt2bblkcdyx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.dashuyun.cn/Article/details/gt2gdrzfaat.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenzaomai.com/Article/details/gt2egomllff.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fsvpvovk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.bjfxy.top/Article/details/gt2ppvfldze.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dsujfacp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.meibo888.top/Article/details/gt2xqqwsrhr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jqgufenzy.top/Article/details/gt2kouhiqpt.html

[L03] 设置自定义请求头
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vcrwnbdt.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shangyingyoupin.top/Article/details/gt2xijlttrz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zzkccehx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shangyingyoupin.top/Article/details/gt2medkkffb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aibaodan.cn/Article/details/gt2nuydzhbt.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.bjfxy.top/Article/details/gt2nslbibun.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hammf.cn/Article/details/gt2haqzxgrv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.9152youxi.cn/Article/details/gt2jbcrvsmn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yvedp.cn/Article/details/gt2dolyqhor.html

[L04] 设置超时
来源：http://dali.chenzaomai.com/Article/details/gt2wsykkbjk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xinyue.icu/Article/details/gt2imhhgovd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zycfv.cn/Article/details/gt2mbfmfzoc.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jlsjyb.cn/Article/details/gt2guxoekmp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.vqdsnc.cn/Article/details/gt2acgdogem.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.guowangkeji.top/Article/details/gt2qefmtpwu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.meibo888.top/Article/details/gt2wsqxjjyh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gaohongyu789.top/Article/details/gt2okvjntov.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cucudq.cn/Article/details/gt2aftkggjn.html

[L05] 上传文件（multipart）
来源：http://dali.tanke756.top/Article/details/gt2aauikrmc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cdnleiting.top/Article/details/gt2tzltgpry.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.tanke756.top/Article/details/gt2njsylnkg.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigufen.top/Article/details/gt2oiqihkra.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yongpay.top/Article/details/gt2zeozynlp.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sysykeji.top/Article/details/gt2zzsmvipe.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.chenlongwang.top/Article/details/gt2wlfepgnz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yuanzhike.top/Article/details/gt2orhpjxii.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2aoiaqgjq.html

[L06] 解析响应为 JSON
来源：http://dali.c1oappe.top/Article/details/gt2dquzlhyq.html

Py:   resp.json()
来源：http://dali.dianchejie.cn/Article/details/gt2nfylpkin.html

PHP:  json_decode($body, true);
来源：http://dali.chenzaomai.com/Article/details/gt2yscxwkft.html

JS:   await resp.json()
来源：http://dali.pycfn.com/Article/details/gt2euotvhex.html

TS:   await resp.json()
来源：http://dali.dianchejie.cn/Article/details/gt2anmarfjm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xuanzx.com/Article/details/gt2krehzzug.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.dashuyun.cn/Article/details/gt2hbacplti.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zdqjudy.top/Article/details/gt2bqcgxbjy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.iojbl.cn/Article/details/gt2hsdumlrw.html

[L07] 处理 HTTP 状态码
来源：http://dali.0kj1m.cn/Article/details/gt2iugqxgyz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yueranfly.top/Article/details/gt2ohmmxzfd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.daxiang520.top/Article/details/gt2nmmzmtsk.html

JS:   resp.ok;  resp.status
来源：http://dali.jyoumei.cn/Article/details/gt2vcbmvaty.html

TS:   resp.ok;  resp.status
来源：http://dali.9152youxi.cn/Article/details/gt2rfdhpuqa.html

Java: resp.statusCode()
来源：http://dali.cucudq.cn/Article/details/gt2trajsfaa.html

Go:   resp.StatusCode
来源：http://dali.xinyue.icu/Article/details/gt2unghtxqn.html

Ruby: resp.code.to_i
来源：http://dali.zhongyouzk.top/Article/details/gt2kankdkgm.html

C#:   (int)resp.StatusCode
来源：http://dali.redwolf501.top/Article/details/gt2keykckjf.html

[L08] 并发请求多个地址
来源：http://dali.jiagoushi.top/Article/details/gt2fcyxrbit.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.kuanghao11.cn/Article/details/gt2nvqwrsmo.html

PHP:  curl_multi_init() 系列
来源：http://dali.316326.xyz/Article/details/gt2wwzwbozo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fengsongda.top/Article/details/gt2mjdsodjc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.haohaochexian.top/Article/details/gt2fdddfebk.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sxryk.cn/Article/details/gt2hnufzaoh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.wangshuangyany.cn/Article/details/gt2qxkgwxmn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jiagoushi.top/Article/details/gt2omqhnpil.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xuanzx.com/Article/details/gt2wizpfxfb.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2uquwqrzl.html

M. 命令行 / 进程 / 环境
来源：http://dali.yonumen.top/Article/details/gt2lcvlrzva.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2koixsrlg.html

[M01] 读取命令行参数
来源：http://dali.xuetiantiany.cn/Article/details/gt2jmebfcco.html

Py:   sys.argv[1:]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2allgyhfn.html

PHP:  $argv;  $argc;
来源：http://dali.svipenyu.cn/Article/details/gt2jalgcsmk.html

JS:   process.argv.slice(2)
来源：http://dali.zhoulong.xyz/Article/details/gt2ghxedyyb.html

TS:   process.argv.slice(2)
来源：http://dali.nanxuanxn.top/Article/details/gt2crvtbmel.html

Java: args 数组（main 方法参数）
来源：http://dali.aibaodan.cn/Article/details/gt2njxpncaz.html

Go:   os.Args[1:]
来源：http://dali.xuanzx.com/Article/details/gt2txyeywnx.html

Ruby: ARGV
来源：http://dali.zhongyouzk.top/Article/details/gt2xpebrgky.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zycfv.cn/Article/details/gt2owwhsuxh.html

[M02] 读取环境变量
来源：http://dali.haohaochexian.top/Article/details/gt2qqjzypat.html

Py:   os.environ.get("HOME")
来源：http://dali.yvedp.cn/Article/details/gt2flmqcvzk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.wangshuangyany.cn/Article/details/gt2qgnlgham.html

JS:   process.env.HOME
来源：http://dali.jyoumei.cn/Article/details/gt2pdnszovo.html

TS:   process.env.HOME
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lqmcznhq.html

Java: System.getenv("HOME")
来源：http://dali.hfpthk.cn/Article/details/gt2jnsnqfjl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.nanxinkj.top/Article/details/gt2wzwrweqp.html

Ruby: ENV["HOME"]
来源：http://dali.yuanzhike.top/Article/details/gt2nqzrrppw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jyoumei.cn/Article/details/gt2rpoyihck.html

[M03] 执行外部命令
来源：http://dali.aibaodan.cn/Article/details/gt2ylwfiuuh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tanke756.top/Article/details/gt2yoidybdf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj20258888.top/Article/details/gt2cumzmcwe.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigfzy.top/Article/details/gt2vxjbhakx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gaohongyu789.top/Article/details/gt2ycjqgwel.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.redwolf501.top/Article/details/gt2qzngdslw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sweek.top/Article/details/gt2drrzrigt.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tian-w.cn/Article/details/gt2nndyqcwb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinqigfzy.top/Article/details/gt2bhgelcje.html

[M04] 获取当前工作目录
来源：http://dali.fzhhl.top/Article/details/gt2fvrkqfmx.html

Py:   os.getcwd()
来源：http://dali.guowangkeji.top/Article/details/gt2ihomybav.html

PHP:  getcwd();
来源：http://dali.fengsongda.top/Article/details/gt2siddqnrf.html

JS:   process.cwd()
来源：http://dali.jqgfzy.top/Article/details/gt2gnombhxm.html

TS:   process.cwd()
来源：http://dali.quarkkingdee.top/Article/details/gt2anxbeqzv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.pengpengdd.cyou/Article/details/gt2vfslazkv.html

Go:   os.Getwd()
来源：http://dali.sweek.top/Article/details/gt2epqumsoj.html

Ruby: Dir.pwd
来源：http://dali.yanxiufei.cn/Article/details/gt2oujsvuoh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.vqdsnc.cn/Article/details/gt2koociqhe.html

[M05] 设置退出码
来源：http://dali.gotoacloud.top/Article/details/gt2mhuzlmof.html

Py:   sys.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gt2uhwghael.html

PHP:  exit(1);
来源：http://dali.ehwqpu.com/Article/details/gt2grpwpcsf.html

JS:   process.exit(1)
来源：http://dali.cucudq.cn/Article/details/gt2edyvilvl.html

TS:   process.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gt2dvjiiela.html

Java: System.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rtfwfxen.html

Go:   os.Exit(1)
来源：http://dali.mhx1999.top/Article/details/gt2rxxozvwp.html

Ruby: exit 1
来源：http://dali.haohaochexian.top/Article/details/gt2orbqxocg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.0kj1m.cn/Article/details/gt2bsnilshs.html

[M06] 向标准错误输出
来源：http://dali.jinqigfzy.top/Article/details/gt2cxmfasow.html

Py:   print("err", file=sys.stderr)
来源：http://dali.fengsongda.top/Article/details/gt2rbhtbpwv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yj202588.top/Article/details/gt2kuwcdxib.html

JS:   console.error("err")
来源：http://dali.xinyue.icu/Article/details/gt2dquvixdt.html

TS:   console.error("err")
来源：http://dali.ppjwa.cn/Article/details/gt2aetgxqyh.html

Java: System.err.println("err")
来源：http://dali.mhx1999.top/Article/details/gt2plehqaky.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.redwolf501.top/Article/details/gt2bwsnxqda.html

Ruby: warn "err"
来源：http://dali.jiagoushi.top/Article/details/gt2ayqqehhr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hywenlv.cn/Article/details/gt2gbncxcqc.html

[M07] 判断是否为主入口
来源：http://dali.hammf.cn/Article/details/gt2mdmbvnhz.html

Py:   if __name__ == "__main__":
来源：http://dali.yueranfly.top/Article/details/gt2jnctdiar.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cheryme.top/Article/details/gt2chbnkjda.html

JS:   require.main === module
来源：http://dali.redwolf501.top/Article/details/gt2xkqiwdvk.html

TS:   require.main === module
来源：http://dali.meibo888.top/Article/details/gt2zutlnvsh.html

Java: public static void main(String[] args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2npoloquz.html

Go:   func main()
来源：http://dali.gzhubu.top/Article/details/gt2eebntodr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenzaomai.com/Article/details/gt2gxkqstip.html

C#:   static void Main(string[] args)
来源：http://dali.yvedp.cn/Article/details/gt2tztxgvrb.html

[M08] 获取系统与运行时信息
来源：http://dali.xuanzx.com/Article/details/gt2ipuvdmnl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.vqdsnc.cn/Article/details/gt2rvfrikub.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shuidangran.top/Article/details/gt2vdxeybup.html

JS:   process.platform;  process.version
来源：http://dali.wangdashe.top/Article/details/gt2blumdder.html

TS:   process.platform;  process.version
来源：http://dali.gaohongyu789.top/Article/details/gt2tnhevcyj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aieygrts.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ozsvngrm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jiagoushi.top/Article/details/gt2orimkolb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jqgfzy.top/Article/details/gt2xdjfnmfy.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2vgwghtnn.html

N. 数据结构与算法
来源：http://dali.pycfn.com/Article/details/gt2pnvaijhy.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2btorhfzd.html

[N01] 二分查找（有序数组）
来源：http://dali.wangdashe.top/Article/details/gt2arqxxmlg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gt2gxaqkvzh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jyoumei.cn/Article/details/gt2vxyjyyjv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yangfankeji.com/Article/details/gt2pcdfaxdj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgufenzy.top/Article/details/gt2xkjdbkhn.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cucudq.cn/Article/details/gt2itapoirq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.fengsongda.top/Article/details/gt2splkqbfg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cashguo.top/Article/details/gt2pudqezpm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xylfe.cn/Article/details/gt2ozyhznfl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xziqi.cn/Article/details/gt2mjzhlspq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.andypj.xyz/Article/details/gt2ildfnhwy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jiagoushi.top/Article/details/gt2cmdpvpkc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shzxlz.cn/Article/details/gt2ufqyawos.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.mhx1999.top/Article/details/gt2mzyljwxy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ohtqsdml.html

Go:   slices.Sort(arr)
来源：http://dali.havefunace.top/Article/details/gt2xyybopxw.html

Ruby: arr.sort
来源：http://dali.zhiwuduotai.top/Article/details/gt2xilhlkau.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.sxryk.cn/Article/details/gt2ftvfukoz.html

[N03] 快速排序（分治示例）
来源：http://dali.hnqzz.top/Article/details/gt2iihhtauu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ivvv.top/Article/details/gt2nnvmvnqo.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yueranfly.top/Article/details/gt2brbvvloi.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.birdmap.top/Article/details/gt2rcuobeyg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258888.top/Article/details/gt2nxukipeg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.fzhhl.top/Article/details/gt2hcfbclhz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.bjfxy.top/Article/details/gt2neniisso.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhengqikj.top/Article/details/gt2hdqjgehe.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yanxiufei.cn/Article/details/gt2hltlhdip.html

[N04] 斐波那契数列
来源：http://dali.hnxiangtu.top/Article/details/gt2vmvmnnbm.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2labjbjqf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.daria6918.cn/Article/details/gt2nyfwoiao.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.316326.xyz/Article/details/gt2gudaynen.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangdashe.top/Article/details/gt2asovdqbw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.0kj1m.cn/Article/details/gt2fsblvruv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cucudq.cn/Article/details/gt2czvbdlra.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.nwbrower.top/Article/details/gt2cbhffgkr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.birdmap.top/Article/details/gt2erthxojc.html

[N05] 最大公约数
来源：http://dali.jinqigufen.top/Article/details/gt2neoiqupp.html

Py:   math.gcd(a, b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2waafubso.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsiysane.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.quarkkingdee.top/Article/details/gt2knkxiwzl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cheryme.top/Article/details/gt2wwevgptj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zdqjudy.top/Article/details/gt2zkwyyrfo.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yuanzhike.top/Article/details/gt2hvdotsvs.html

Ruby: a.gcd(b)
来源：http://dali.havefunace.top/Article/details/gt2ccxbocsv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sufxvd.cn/Article/details/gt2dhqyookm.html

[N06] 判断回文字符串
来源：http://dali.gzhubu.top/Article/details/gt2skcqyaqw.html

Py:   s == s[::-1]
来源：http://dali.yvedp.cn/Article/details/gt2cneblpqm.html

PHP:  $s === strrev($s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2mugnxxrl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gt2fmtzmayx.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gt2zvzrlida.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.chenzaomai.com/Article/details/gt2ydvjcmog.html

Go:   // 双指针从两端比较
来源：http://dali.tian-w.cn/Article/details/gt2auakrzqg.html

Ruby: s == s.reverse
来源：http://dali.pycfn.com/Article/details/gt2blwnynze.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jlsjyb.cn/Article/details/gt2mfcomtfa.html

[N07] 两数之和（返回下标）
来源：http://dali.pengpengdd.cyou/Article/details/gt2mreeduvd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.smart0.xyz/Article/details/gt2eqgazjkw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.dashuyun.cn/Article/details/gt2xumzujff.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cdnleiting.top/Article/details/gt2phnjnyls.html

TS:   // 手写 Map<string, number>
来源：http://dali.wangshuangyany.cn/Article/details/gt2dqtacrpj.html

Java: // 手写 HashMap
来源：http://dali.sweek.top/Article/details/gt2sondkgfl.html

Go:   // 手写 map[int]int
来源：http://dali.gzhubu.top/Article/details/gt2aziziidm.html

Ruby: // 手写 Hash
来源：http://dali.hywenlv.cn/Article/details/gt2dexmbggk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ybcxt.top/Article/details/gt2uooerjok.html

[N08] 生成全排列
来源：http://dali.yangfankeji.com/Article/details/gt2zkffjxjk.html

Py:   itertools.permutations(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2dpgmnjxc.html

PHP:  // 手写递归交换
来源：http://dali.yanxiufei.cn/Article/details/gt2bgoljdra.html

JS:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gt2mbibkomm.html

TS:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gt2enhvkypa.html

Java: // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gt2xcrwkhrq.html

Go:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2amtlsisp.html

Ruby: arr.permutation.to_a
来源：http://dali.hongshengwenyu.top/Article/details/gt2lcvwvqnr.html

C#:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gt2rndaqgae.html

[N09] 栈与队列
来源：http://dali.9152youxi.cn/Article/details/gt2gveayktp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gt2qgttwlzj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.tanke756.top/Article/details/gt2gatnakdw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gt2ledkjeym.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.316326.xyz/Article/details/gt2iymztpod.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shuidangran.top/Article/details/gt2rajobeiy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.9152youxi.cn/Article/details/gt2vaetwfzr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cashguo.top/Article/details/gt2lgxivmql.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hywenlv.cn/Article/details/gt2gbmbycvp.html

[N10] 链表节点定义
来源：http://dali.yvedp.cn/Article/details/gt2sddhibyh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cucudq.cn/Article/details/gt2ndqweazg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xziqi.cn/Article/details/gt2wvbolpdo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hywenlv.cn/Article/details/gt2rkhusuko.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jqgufenzy.top/Article/details/gt2bugdxicz.html

Java: class Node { int v; Node next; }
来源：http://dali.gotoacloud.top/Article/details/gt2xilyjshs.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xylfe.cn/Article/details/gt2qvbduzji.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kkimnmfy.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2igxckbgt.html

[N11] 二叉树中序遍历
来源：http://dali.feifeiyinyue.top/Article/details/gt2msxefodh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jiagoushi.top/Article/details/gt2cmkydwjz.html

PHP:  // 手写递归函数
来源：http://dali.daria6918.cn/Article/details/gt2fqrvtppf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ehwqpu.com/Article/details/gt2mjixfcao.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guannengcc.top/Article/details/gt2vfkchiqy.html

Java: // 手写递归
来源：http://dali.vqdsnc.cn/Article/details/gt2heqgnxvw.html

Go:   // 手写递归
来源：http://dali.tanke756.top/Article/details/gt2arxgtgpe.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yj20258.top/Article/details/gt2vitzlqqs.html

C#:   // 手写递归
来源：http://dali.nanxinkj.top/Article/details/gt2ofuqwaok.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yueranfly.top/Article/details/gt2vbugdjbv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ybcxt.top/Article/details/gt2tumpqsrs.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.aibaodan.cn/Article/details/gt2mdznbamy.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sxryk.cn/Article/details/gt2jyurgghy.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.pycfn.com/Article/details/gt2fvuwvrqa.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cucudq.cn/Article/details/gt2glavpjwq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.aibaodan.cn/Article/details/gt2vodfegty.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2guguozqy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hysaishi.cn/Article/details/gt2dmuwapiw.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2wquuoznq.html

O. 并发与异步
来源：http://dali.cashguo.top/Article/details/gt2elxtofwd.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2wtkifmkw.html

[O01] 启动一个线程
来源：http://dali.hysaishi.cn/Article/details/gt2adnbbnbg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ivvv.top/Article/details/gt2yvnvjugp.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yuanzhike.top/Article/details/gt2ftyidttt.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.316326.xyz/Article/details/gt2iryryani.html

TS:   // 同 JS
来源：http://dali.gzhubu.top/Article/details/gt2sufggbzi.html

Java: new Thread(() -> f()).start()
来源：http://dali.hnqzz.top/Article/details/gt2uozcdfqt.html

Go:   go f()
来源：http://dali.shuidangran.top/Article/details/gt2ndgcvstx.html

Ruby: Thread.new { f }
来源：http://dali.316326.xyz/Article/details/gt2ebjigltg.html

C#:   Task.Run(() => F());
来源：http://dali.0kj1m.cn/Article/details/gt2fiquvull.html

[O02] 使用线程池
来源：http://dali.pengpengdd.cyou/Article/details/gt2qelsthfj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.tianlin.xyz/Article/details/gt2szznwxum.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.dianchejie.cn/Article/details/gt2vmdenbqo.html

JS:   // worker_threads 线程池
来源：http://dali.zhoulong.xyz/Article/details/gt2crqojyxf.html

TS:   // worker_threads 线程池
来源：http://dali.zdqjudy.top/Article/details/gt2qszfwsaw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zimzdgzh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cdnleiting.top/Article/details/gt2fhwdybuu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.dashuyun.cn/Article/details/gt2kowqtumv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hfpthk.cn/Article/details/gt2wofrkwep.html

[O03] 加锁保护共享数据
来源：http://dali.haohaochexian.top/Article/details/gt2fwmgilah.html

Py:   with lock: shared += 1
来源：http://dali.iojbl.cn/Article/details/gt2twbvrycp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.guowangkeji.top/Article/details/gt2dedmrplo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.tian-w.cn/Article/details/gt2izpelvpr.html

TS:   // 同 JS
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cosinfyd.html

Java: synchronized (this) { shared++; }
来源：http://dali.jianghu66.top/Article/details/gt2xlucascc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yongpay.top/Article/details/gt2fxkmlctq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.sweek.top/Article/details/gt2sqtlrjxt.html

C#:   lock (gate) { shared++; }
来源：http://dali.yueranfly.top/Article/details/gt2mlgvddze.html

[O04] 定义异步函数并等待
来源：http://dali.jyoumei.cn/Article/details/gt2imcxtxsh.html

Py:   async def f():⏎    await g()
来源：http://dali.jyoumei.cn/Article/details/gt2upwrlxog.html


<!-- 参考信息 -->