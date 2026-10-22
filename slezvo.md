代发 wailian999

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqqgxuigr.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gtoqopecsj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtutlvivtm.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.birdmap.top/Article/details/gttnnsbuoc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cucudq.cn/Article/details/gtxdyqbmfz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj20258.top/Article/details/gtlwpzacln.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yuxming.cn/Article/details/gtayxwurgm.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtzcmtozhu.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ivvv.top/Article/details/gtzbfmtcxl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ivvv.top/Article/details/gtpaxgubdk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shzxlz.cn/Article/details/gtwookzjvi.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yanxiufei.cn/Article/details/gtgsakamfx.html

Go:   encoding/gob
来源：http://dali.pengpengdd.cyou/Article/details/gtdqzblqvj.html

Ruby: Marshal.dump(obj)
来源：http://dali.svipenyu.cn/Article/details/gtfmbxjfqw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nanxuanxn.top/Article/details/gtxhntqiym.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtiksirchg.html

L. 网络请求
来源：http://dali.zhixingplan.top/Article/details/gtgljwnvuj.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtzvggqgpr.html

[L01] 发送 GET 请求
来源：http://dali.zhengqikj.top/Article/details/gthmvyrkyv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shuidangran.top/Article/details/gtlvwwziwr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xuetiantiany.cn/Article/details/gthmojtkze.html

JS:   await fetch(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gtglyorlob.html

TS:   await fetch(url)
来源：http://dali.nanxinkj.top/Article/details/gtwzjjmwrg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xinyue.icu/Article/details/gtilgiclxb.html

Go:   resp, err := http.Get(url)
来源：http://dali.daria6918.cn/Article/details/gtrcqjkola.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.svipenyu.cn/Article/details/gtjacbbirb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zdqjudy.top/Article/details/gtnioqxjih.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gtqbjqobgd.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.tian-w.cn/Article/details/gtehlkluib.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.bjfxy.top/Article/details/gtjjzftypq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258888.top/Article/details/gtzrnuwiin.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jlsjyb.cn/Article/details/gtjyeuxztn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlqasduls.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cucudq.cn/Article/details/gteelqutzu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shangyingyoupin.top/Article/details/gtvhpvykbf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gogol.net.cn/Article/details/gtqlniygey.html

[L03] 设置自定义请求头
来源：http://dali.pycfn.com/Article/details/gtsaraerwv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sufxvd.cn/Article/details/gtiaphlwuk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xuanzx.com/Article/details/gtoepjtcpe.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.haohaochexian.top/Article/details/gtjgyrkqvy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhiwuduotai.top/Article/details/gtfscfrafb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.tanke756.top/Article/details/gtdtxwmpii.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xylfe.cn/Article/details/gtvkpcbjrn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yangfankeji.com/Article/details/gtkxjgdqkr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.chenzaomai.com/Article/details/gtqtpfjbsi.html

[L04] 设置超时
来源：http://dali.cdnleiting.top/Article/details/gtwpyjyphv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tanke756.top/Article/details/gtedzkhdbu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.316326.xyz/Article/details/gtuhhfryla.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtubrhinsv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daria6918.cn/Article/details/gtiwkawuqo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shangyingyoupin.top/Article/details/gtounglksq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ybcxt.top/Article/details/gtowqzczqa.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.daria6918.cn/Article/details/gtrzaxxxkh.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.daria6918.cn/Article/details/gtpkfyjxdn.html

[L05] 上传文件（multipart）
来源：http://dali.gogol.net.cn/Article/details/gtspoxeaxv.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jiagoushi.top/Article/details/gtymgefjfd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.tian-w.cn/Article/details/gtxewoeizk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.redwolf501.top/Article/details/gteyftsrzy.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenlongwang.top/Article/details/gttedmultj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ivvv.top/Article/details/gtuyfauoqk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhixingplan.top/Article/details/gtgnwypzoj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.tianlin.xyz/Article/details/gttwomnuhv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtbdzrjwxu.html

[L06] 解析响应为 JSON
来源：http://dali.yanxiufei.cn/Article/details/gtfqwwfcbj.html

Py:   resp.json()
来源：http://dali.jianghu66.top/Article/details/gtcaetipnr.html

PHP:  json_decode($body, true);
来源：http://dali.zycfv.cn/Article/details/gttgtznjfl.html

JS:   await resp.json()
来源：http://dali.xuetiantiany.cn/Article/details/gtddogbnsz.html

TS:   await resp.json()
来源：http://dali.shzxlz.cn/Article/details/gtyuupltdt.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.guowangkeji.top/Article/details/gtrfuewpyg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.guowangkeji.top/Article/details/gtqzlvauvn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhoulong.xyz/Article/details/gtnkyiktah.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtetnoxzgu.html

[L07] 处理 HTTP 状态码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzranlwjy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sysykeji.top/Article/details/gtlmrzaecm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gzhubu.top/Article/details/gteygugvok.html

JS:   resp.ok;  resp.status
来源：http://dali.havefunace.top/Article/details/gtrtyifqtu.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gtpjvojdgo.html

Java: resp.statusCode()
来源：http://dali.redwolf501.top/Article/details/gtyulxeeey.html

Go:   resp.StatusCode
来源：http://dali.jianghu66.top/Article/details/gtkbdqlsem.html

Ruby: resp.code.to_i
来源：http://dali.xinyue.icu/Article/details/gtdcrqbdoe.html

C#:   (int)resp.StatusCode
来源：http://dali.cashguo.top/Article/details/gteocoaovf.html

[L08] 并发请求多个地址
来源：http://dali.nwbrower.top/Article/details/gtgrgnewos.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yanxiufei.cn/Article/details/gtzmmjkkvr.html

PHP:  curl_multi_init() 系列
来源：http://dali.xuetiantiany.cn/Article/details/gttfzzkmog.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gtueyqcgyj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gtdqgtqjgt.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hongshengwenyu.top/Article/details/gtgeaquhpd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.9152youxi.cn/Article/details/gtkiyeohfc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cqqwz.cn/Article/details/gtahkiybsj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gotoacloud.top/Article/details/gtbkwepdrl.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtcxdwrdtv.html

M. 命令行 / 进程 / 环境
来源：http://dali.tian-w.cn/Article/details/gtcffftgrr.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtruguhmva.html

[M01] 读取命令行参数
来源：http://dali.dashuyun.cn/Article/details/gtawdslisv.html

Py:   sys.argv[1:]
来源：http://dali.yangfankeji.com/Article/details/gtuvtttqde.html

PHP:  $argv;  $argc;
来源：http://dali.sufxvd.cn/Article/details/gtmtxsgmox.html

JS:   process.argv.slice(2)
来源：http://dali.yj202588.top/Article/details/gtewagnvjv.html

TS:   process.argv.slice(2)
来源：http://dali.sufxvd.cn/Article/details/gtasepsdes.html

Java: args 数组（main 方法参数）
来源：http://dali.yj202588.top/Article/details/gtbeiaenxm.html

Go:   os.Args[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gtkiyvnqvb.html

Ruby: ARGV
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlruhfxhb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sysykeji.top/Article/details/gtbruasaan.html

[M02] 读取环境变量
来源：http://dali.wangshuangyany.cn/Article/details/gtrislmmsl.html

Py:   os.environ.get("HOME")
来源：http://dali.hfpthk.cn/Article/details/gttbzdfefn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sufxvd.cn/Article/details/gtgikzkpmo.html

JS:   process.env.HOME
来源：http://dali.zhongyouzk.top/Article/details/gtzxrcxbli.html

TS:   process.env.HOME
来源：http://dali.feifeiyinyue.top/Article/details/gtzqyupcbk.html

Java: System.getenv("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjridxiek.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shuidangran.top/Article/details/gtrfnsqznr.html

Ruby: ENV["HOME"]
来源：http://dali.chenjidiqi.icu/Article/details/gtykciqybj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gtrhjlwpxi.html

[M03] 执行外部命令
来源：http://dali.birdmap.top/Article/details/gtcpohqfyl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.wangshuangyany.cn/Article/details/gtprrrjcqm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ydzc1.top/Article/details/gtwyubshbu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.dianchejie.cn/Article/details/gtqokfbasi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuanzhike.top/Article/details/gtawqasdaf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinghuilouyu.cn/Article/details/gttwovymcx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.svipenyu.cn/Article/details/gtagshecjn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhaomingkeji.xyz/Article/details/gtweprrpmu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nanxinkj.top/Article/details/gtpjmsoafo.html

[M04] 获取当前工作目录
来源：http://dali.feifeiyinyue.top/Article/details/gtfhpexwsg.html

Py:   os.getcwd()
来源：http://dali.fzhhl.top/Article/details/gtkewvvknk.html

PHP:  getcwd();
来源：http://dali.meibo888.top/Article/details/gtbsieydcv.html

JS:   process.cwd()
来源：http://dali.ehwqpu.com/Article/details/gtvspliqlv.html

TS:   process.cwd()
来源：http://dali.gzhubu.top/Article/details/gthxqyinbi.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xinyue.icu/Article/details/gtbkavtitw.html

Go:   os.Getwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtlbzzalhz.html

Ruby: Dir.pwd
来源：http://dali.yonumen.top/Article/details/gttsiazuvu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.feifeiyinyue.top/Article/details/gtwboheovf.html

[M05] 设置退出码
来源：http://dali.c1oappe.top/Article/details/gtjedsykch.html

Py:   sys.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gtknixvksk.html

PHP:  exit(1);
来源：http://dali.jlsjyb.cn/Article/details/gtisxepmct.html

JS:   process.exit(1)
来源：http://dali.cashguo.top/Article/details/gtwfvqpoag.html

TS:   process.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gtcudmjlfm.html

Java: System.exit(1)
来源：http://dali.yj202588.top/Article/details/gtqhixqurd.html

Go:   os.Exit(1)
来源：http://dali.zhengqikj.top/Article/details/gtjdxbdvaz.html

Ruby: exit 1
来源：http://dali.pengpengdd.cyou/Article/details/gtpiokdrbb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shanyushiyangtech.top/Article/details/gtdkomnalj.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gtlzslzfzy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtevezqmrq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.birdmap.top/Article/details/gtjdntqlse.html

JS:   console.error("err")
来源：http://dali.zycfv.cn/Article/details/gthlkplsyt.html

TS:   console.error("err")
来源：http://dali.ehwqpu.com/Article/details/gtsevvbgpt.html

Java: System.err.println("err")
来源：http://dali.redwolf501.top/Article/details/gtxrsybhtk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhiwuduotai.top/Article/details/gtlflrvlph.html

Ruby: warn "err"
来源：http://dali.daxiang520.top/Article/details/gtohakrojg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.quarkkingdee.top/Article/details/gtxmfpapoj.html

[M07] 判断是否为主入口
来源：http://dali.hnqzz.top/Article/details/gtjcqjseap.html

Py:   if __name__ == "__main__":
来源：http://dali.zhengqikj.top/Article/details/gtoxyoucmq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.iojbl.cn/Article/details/gtglmelytd.html

JS:   require.main === module
来源：http://dali.zhixingplan.top/Article/details/gtgjqhyeqw.html

TS:   require.main === module
来源：http://dali.daria6918.cn/Article/details/gtvkachesq.html

Java: public static void main(String[] args)
来源：http://dali.mhx1999.top/Article/details/gtvxjfhprz.html

Go:   func main()
来源：http://dali.yj20258888.top/Article/details/gtzniqzbsq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xziqi.cn/Article/details/gtzeqjktnj.html

C#:   static void Main(string[] args)
来源：http://dali.cqqwz.cn/Article/details/gttdnnbthw.html

[M08] 获取系统与运行时信息
来源：http://dali.zhoulong.xyz/Article/details/gtwqquhgom.html

Py:   platform.system();  platform.python_version()
来源：http://dali.redwolf501.top/Article/details/gtwvjncyxx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.0kj1m.cn/Article/details/gthnvkiidh.html

JS:   process.platform;  process.version
来源：http://dali.redwolf501.top/Article/details/gtqnkqvuik.html

TS:   process.platform;  process.version
来源：http://dali.birdmap.top/Article/details/gtokifxaoc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.dashuyun.cn/Article/details/gtldozntvo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.daria6918.cn/Article/details/gtsiytebkl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hywenlv.cn/Article/details/gtuabcyfgu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gotoacloud.top/Article/details/gthyjexbah.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtzupmbxzv.html

N. 数据结构与算法
来源：http://dali.chenzaomai.com/Article/details/gtzoqzdjlq.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtftdzrdyf.html

[N01] 二分查找（有序数组）
来源：http://dali.vqdsnc.cn/Article/details/gtspmulfll.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gtvhttmhnd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yj202588.top/Article/details/gtgcsprnak.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcsmyacqr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hywenlv.cn/Article/details/gtijbdbqau.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cashguo.top/Article/details/gtajkbczio.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gtoxlrsdgh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sufxvd.cn/Article/details/gtawbzcrlq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtrzwjecbu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenlongwang.top/Article/details/gtlqiwcqvc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258.top/Article/details/gtkdqoawus.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ydzc1.top/Article/details/gtqezdpert.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gogol.net.cn/Article/details/gtlgglcvgn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yanxiufei.cn/Article/details/gtjjbwirff.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.wangdashe.top/Article/details/gtmaeriagx.html

Go:   slices.Sort(arr)
来源：http://dali.zhixingplan.top/Article/details/gtbpfretla.html

Ruby: arr.sort
来源：http://dali.feifeiyinyue.top/Article/details/gthieutuor.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.mhx1999.top/Article/details/gtondmxcnc.html

[N03] 快速排序（分治示例）
来源：http://dali.xuanzx.com/Article/details/gtxunzulle.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gogol.net.cn/Article/details/gtfvcdekls.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gogol.net.cn/Article/details/gtyqtgozuu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xziqi.cn/Article/details/gtbmswspua.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zdqjudy.top/Article/details/gtoeliqotc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.guowangkeji.top/Article/details/gtepwxahxw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shzxlz.cn/Article/details/gtxginzdcs.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shanyushiyangtech.top/Article/details/gttgqgugps.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrwhrkjqw.html

[N04] 斐波那契数列
来源：http://dali.xylfe.cn/Article/details/gtnbgjsade.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhengqikj.top/Article/details/gthxwpizrh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.svipenyu.cn/Article/details/gtdsndijmv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gtplddtoex.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guannengcc.top/Article/details/gtdzsfabqg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xuetiantiany.cn/Article/details/gtcgfcegdq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.316326.xyz/Article/details/gtucavtkxu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jlsjyb.cn/Article/details/gtsdzksxfj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gtznshcpcp.html

[N05] 最大公约数
来源：http://dali.yuxming.cn/Article/details/gtwfymxurv.html

Py:   math.gcd(a, b)
来源：http://dali.gogol.net.cn/Article/details/gtewtrufac.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gtamwrxaoj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ehwqpu.com/Article/details/gtrdwuxrbs.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hongshengwenyu.top/Article/details/gtlyubxmif.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cqqwz.cn/Article/details/gtxaqcarxj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jiagoushi.top/Article/details/gteomtswbm.html

Ruby: a.gcd(b)
来源：http://dali.fzhhl.top/Article/details/gtzvcfwxtj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.svipenyu.cn/Article/details/gtatnaceuv.html

[N06] 判断回文字符串
来源：http://dali.zycfv.cn/Article/details/gtsbukkscx.html

Py:   s == s[::-1]
来源：http://dali.cdnleiting.top/Article/details/gthegfrmnv.html

PHP:  $s === strrev($s);
来源：http://dali.hnxiangtu.top/Article/details/gtcewyxqsl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gtlaahetyi.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gtpxzazaxo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdmxrtpph.html

Go:   // 双指针从两端比较
来源：http://dali.tian-w.cn/Article/details/gtemettagp.html

Ruby: s == s.reverse
来源：http://dali.0kj1m.cn/Article/details/gtjkrqcxgc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ehwqpu.com/Article/details/gtavauhvbu.html

[N07] 两数之和（返回下标）
来源：http://dali.gaohongyu789.top/Article/details/gtbetlobah.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.fzhhl.top/Article/details/gtmncblqcj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ehwqpu.com/Article/details/gththonnda.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.mhx1999.top/Article/details/gtimxivrke.html

TS:   // 手写 Map<string, number>
来源：http://dali.shangyingyoupin.top/Article/details/gtlogiahre.html

Java: // 手写 HashMap
来源：http://dali.shzxlz.cn/Article/details/gtoscdjibg.html

Go:   // 手写 map[int]int
来源：http://dali.zdqjudy.top/Article/details/gtswoedafk.html

Ruby: // 手写 Hash
来源：http://dali.xuetiantiany.cn/Article/details/gtcvqhahvx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yvedp.cn/Article/details/gtjrhoapeh.html

[N08] 生成全排列
来源：http://dali.yangfankeji.com/Article/details/gtpdzfiqep.html

Py:   itertools.permutations(arr)
来源：http://dali.ivvv.top/Article/details/gtfqgevooi.html

PHP:  // 手写递归交换
来源：http://dali.fengsongda.top/Article/details/gtepuzugbl.html

JS:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gtrmlvdxox.html

TS:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gtryilauzd.html

Java: // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gtlsmgqnlk.html

Go:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnluwcwlw.html

Ruby: arr.permutation.to_a
来源：http://dali.chenzaomai.com/Article/details/gtpdszhqru.html

C#:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtrkjdntlt.html

[N09] 栈与队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdwhbevse.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.fengsongda.top/Article/details/gtucfqnkcf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhongyouzk.top/Article/details/gtpvepkkew.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gtilswueqh.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.feifeiyinyue.top/Article/details/gtayneqlpl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.fengsongda.top/Article/details/gtkkgvxhfr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xuetiantiany.cn/Article/details/gtjfgbqheo.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hnxiangtu.top/Article/details/gtbpxzajup.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtepysztbr.html

[N10] 链表节点定义
来源：http://dali.gotoacloud.top/Article/details/gtwokjivyz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhixingplan.top/Article/details/gtqygzjceu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gaohongyu789.top/Article/details/gtijishsuo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhengqikj.top/Article/details/gtbdhwpnji.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hysaishi.cn/Article/details/gtmkujogbe.html

Java: class Node { int v; Node next; }
来源：http://dali.xuanzx.com/Article/details/gtmidznhkq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinqigufen.top/Article/details/gtqxagwdcr.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cqqwz.cn/Article/details/gtbgaqnuxu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yanxiufei.cn/Article/details/gtvptticgy.html

[N11] 二叉树中序遍历
来源：http://dali.zhiwuduotai.top/Article/details/gtglpwedxp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.nanxinkj.top/Article/details/gtuuvahree.html

PHP:  // 手写递归函数
来源：http://dali.birdmap.top/Article/details/gtfdwsgqvy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hammf.cn/Article/details/gtfqeixfnn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tianlin.xyz/Article/details/gtngcloeit.html

Java: // 手写递归
来源：http://dali.pycfn.com/Article/details/gtauddgjbm.html

Go:   // 手写递归
来源：http://dali.sweek.top/Article/details/gtozeuewal.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.pycfn.com/Article/details/gtgzkvyhkx.html

C#:   // 手写递归
来源：http://dali.gaohongyu789.top/Article/details/gtpbbxwbtr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhiwuduotai.top/Article/details/gtbyijexhd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtamlqpnhp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shzxlz.cn/Article/details/gtetmzdejl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jlsjyb.cn/Article/details/gthglffycn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gzhubu.top/Article/details/gtqlyreiys.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gtydpaupfa.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xinyue.icu/Article/details/gtpvngfrgx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.guannengcc.top/Article/details/gtujahhpwn.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jianghu66.top/Article/details/gtovgdqxdh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtglmqdbpe.html

O. 并发与异步
来源：http://dali.andypj.xyz/Article/details/gtvbyxmjjp.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gteyxgrdga.html

[O01] 启动一个线程
来源：http://dali.zdqjudy.top/Article/details/gtbvqdziha.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yj202588.top/Article/details/gtrlfrnmsf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhoulong.xyz/Article/details/gtxfafywjx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhoulong.xyz/Article/details/gtjmdvtxmp.html

TS:   // 同 JS
来源：http://dali.cashguo.top/Article/details/gtkgjjqfex.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinghuilouyu.cn/Article/details/gtlqzpanky.html

Go:   go f()
来源：http://dali.zhongyouzk.top/Article/details/gtubyxphcp.html

Ruby: Thread.new { f }
来源：http://dali.nanxinkj.top/Article/details/gtwitnozbq.html

C#:   Task.Run(() => F());
来源：http://dali.sxryk.cn/Article/details/gtytvcohcj.html

[O02] 使用线程池
来源：http://dali.yj20258888.top/Article/details/gtjwffjvfb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jianghu66.top/Article/details/gtewevjxrf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jianghu66.top/Article/details/gtegnrygoh.html

JS:   // worker_threads 线程池
来源：http://dali.jyoumei.cn/Article/details/gtffpligps.html

TS:   // worker_threads 线程池
来源：http://dali.yj20258.top/Article/details/gtopxdafvl.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.sxryk.cn/Article/details/gtueylqpbx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwvfzetli.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hongshengwenyu.top/Article/details/gtarjorlbr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ehwqpu.com/Article/details/gtikfhnjkx.html

[O03] 加锁保护共享数据
来源：http://dali.mhx1999.top/Article/details/gtxxlcnvds.html

Py:   with lock: shared += 1
来源：http://dali.zhongyouzk.top/Article/details/gtlcqhagvf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.bjfxy.top/Article/details/gtqoxbdefh.html


<!-- 参考信息 -->