代发 wailian999

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.tanke756.top/Article/details/gtdymckdqs.html

[K07] 进制转换
来源：http://dali.haohaochexian.top/Article/details/gtbhhwbsec.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gtbojytslk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.316326.xyz/Article/details/gtgghoddyc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yonumen.top/Article/details/gtjcusklzj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gtezzndigl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtecgpxhuy.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xuetiantiany.cn/Article/details/gtevgwqttg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.9152youxi.cn/Article/details/gtgqrvwuwf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gtuvzmhvbp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.wangshuangyany.cn/Article/details/gtwnxvqokt.html

Py:   pickle.dumps(obj)
来源：http://dali.yj20258.top/Article/details/gtjwjemyfz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cheryme.top/Article/details/gtsceswfyw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.316326.xyz/Article/details/gtudtoscaq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhoulong.xyz/Article/details/gtqvyoeitt.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cheryme.top/Article/details/gtxouovszt.html

Go:   encoding/gob
来源：http://dali.shuidangran.top/Article/details/gtefkrlkwt.html

Ruby: Marshal.dump(obj)
来源：http://dali.sxryk.cn/Article/details/gtqfvdeuxz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jqgufenzy.top/Article/details/gtyucegyft.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtzqsdbsoo.html

L. 网络请求
来源：http://dali.guannengcc.top/Article/details/gtcuzneejc.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtygdhtqmi.html

[L01] 发送 GET 请求
来源：http://dali.yangfankeji.com/Article/details/gtfkinxugu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbhoajwzz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.iojbl.cn/Article/details/gtczjvnerl.html

JS:   await fetch(url)
来源：http://dali.cqqwz.cn/Article/details/gtoiyypbjx.html

TS:   await fetch(url)
来源：http://dali.xuanzx.com/Article/details/gtoewjurwm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gtdzxlcamt.html

Go:   resp, err := http.Get(url)
来源：http://dali.bjfxy.top/Article/details/gtzfrzmkow.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinqigufen.top/Article/details/gtngjjsmjf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gogol.net.cn/Article/details/gtadljqiwc.html

[L02] 发送 POST JSON
来源：http://dali.yuxming.cn/Article/details/gtqjnphuzx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yangfankeji.com/Article/details/gthlynwefc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.guowangkeji.top/Article/details/gtwrnvhnrx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sufxvd.cn/Article/details/gtqykipehi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhongyouzk.top/Article/details/gtaknmvwbs.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.smart0.xyz/Article/details/gtzivxdiio.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ydzc1.top/Article/details/gtpswrtpiw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.fengsongda.top/Article/details/gtpljuuoeo.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.aizwys.cn/Article/details/gtitcmbhkm.html

[L03] 设置自定义请求头
来源：http://dali.c1oappe.top/Article/details/gtjxchnycn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhiwuduotai.top/Article/details/gtqcsqdovg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.0kj1m.cn/Article/details/gthsdewpwz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shzxlz.cn/Article/details/gtfpvqtdee.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhengqikj.top/Article/details/gtztmluihs.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cdnleiting.top/Article/details/gtfrmsgxmf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmeklxqtv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shangyingyoupin.top/Article/details/gtegegpcjf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ydzc1.top/Article/details/gtfcojjoag.html

[L04] 设置超时
来源：http://dali.ehwqpu.com/Article/details/gthnjbkbbd.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpnlfzzhy.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhixingplan.top/Article/details/gtdjxdlzzk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gaohongyu789.top/Article/details/gtnrlkjdxm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cashguo.top/Article/details/gtffdekdfo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cdnleiting.top/Article/details/gtcughjbgl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.pengpengdd.cyou/Article/details/gtaltacufa.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ivvv.top/Article/details/gtgsglsksm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.guowangkeji.top/Article/details/gthfetvwvt.html

[L05] 上传文件（multipart）
来源：http://dali.feifeiyinyue.top/Article/details/gttwvmpejg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jlsjyb.cn/Article/details/gtkbnwnuhh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.dashuyun.cn/Article/details/gtisxdlsjo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.snrcjt.cn/Article/details/gtwnhjhfat.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cashguo.top/Article/details/gtcefysowk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.vqdsnc.cn/Article/details/gthgfudgkb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gotoacloud.top/Article/details/gtixfdxmny.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hysaishi.cn/Article/details/gtkpsiupvj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtstrjhuuk.html

[L06] 解析响应为 JSON
来源：http://dali.ehwqpu.com/Article/details/gtyrcyvlay.html

Py:   resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gtbwqhpriv.html

PHP:  json_decode($body, true);
来源：http://dali.wangdashe.top/Article/details/gtnqyxbgiy.html

JS:   await resp.json()
来源：http://dali.zhengqikj.top/Article/details/gttyiwiobj.html

TS:   await resp.json()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkilaasku.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sysykeji.top/Article/details/gtsyjfempe.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.tian-w.cn/Article/details/gtujpaizsf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.bjfxy.top/Article/details/gtrhxtsurs.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shzxlz.cn/Article/details/gtfziyjbss.html

[L07] 处理 HTTP 状态码
来源：http://dali.dashuyun.cn/Article/details/gtpmaxxqdt.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yonumen.top/Article/details/gtoqkqbszc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nanxinkj.top/Article/details/gtffqjcjge.html

JS:   resp.ok;  resp.status
来源：http://dali.ywan-chungtsiang.top/Article/details/gtclfndfce.html

TS:   resp.ok;  resp.status
来源：http://dali.cqqwz.cn/Article/details/gtrblxhbwt.html

Java: resp.statusCode()
来源：http://dali.gzhubu.top/Article/details/gtpkkrehge.html

Go:   resp.StatusCode
来源：http://dali.zhengqikj.top/Article/details/gtqbpivodv.html

Ruby: resp.code.to_i
来源：http://dali.cdnleiting.top/Article/details/gtixoffhmy.html

C#:   (int)resp.StatusCode
来源：http://dali.yvedp.cn/Article/details/gtgusyozzj.html

[L08] 并发请求多个地址
来源：http://dali.gzhubu.top/Article/details/gtuubbgkna.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.pycfn.com/Article/details/gtqvdniqhz.html

PHP:  curl_multi_init() 系列
来源：http://dali.quarkkingdee.top/Article/details/gtfoopjewk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hywenlv.cn/Article/details/gtthmlyhtj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sxryk.cn/Article/details/gtdptciqch.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj20258.top/Article/details/gtdfrjrcic.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.feifeiyinyue.top/Article/details/gthndmjslc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yanxiufei.cn/Article/details/gtqmgvnkas.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.svipenyu.cn/Article/details/gtujegjzri.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtahqhwzhs.html

M. 命令行 / 进程 / 环境
来源：http://dali.shuidangran.top/Article/details/gtukyfwrep.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtvbtxlhnz.html

[M01] 读取命令行参数
来源：http://dali.jinqigufen.top/Article/details/gtotqhworz.html

Py:   sys.argv[1:]
来源：http://dali.jinqigfzy.top/Article/details/gtvotwtfsi.html

PHP:  $argv;  $argc;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtebzkxjfj.html

JS:   process.argv.slice(2)
来源：http://dali.gzhubu.top/Article/details/gtrvhipxoc.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gtixazroru.html

Java: args 数组（main 方法参数）
来源：http://dali.meibo888.top/Article/details/gtqvjkwxxu.html

Go:   os.Args[1:]
来源：http://dali.c1oappe.top/Article/details/gtzxtstsmd.html

Ruby: ARGV
来源：http://dali.ehwqpu.com/Article/details/gtgflxvcdz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xuanzx.com/Article/details/gtssszgziu.html

[M02] 读取环境变量
来源：http://dali.jqgfzy.top/Article/details/gtepfgffvl.html

Py:   os.environ.get("HOME")
来源：http://dali.iojbl.cn/Article/details/gtycpddfdc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hysaishi.cn/Article/details/gtsfirqitq.html

JS:   process.env.HOME
来源：http://dali.smart0.xyz/Article/details/gtxgqoocks.html

TS:   process.env.HOME
来源：http://dali.jinyuanbaomall.cn/Article/details/gtocizdbqr.html

Java: System.getenv("HOME")
来源：http://dali.jyoumei.cn/Article/details/gtfizbwebl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.redwolf501.top/Article/details/gtogsgtxwx.html

Ruby: ENV["HOME"]
来源：http://dali.vqdsnc.cn/Article/details/gtiqfgjnaa.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinqigufen.top/Article/details/gtcavxahbg.html

[M03] 执行外部命令
来源：http://dali.hysaishi.cn/Article/details/gtlksgayhn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sufxvd.cn/Article/details/gtkmgfkscl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.iojbl.cn/Article/details/gtoiyttixi.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj202588.top/Article/details/gtapwqxsiu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gteyuqfuef.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gtttlcihok.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.daxiang520.top/Article/details/gtjyuwdnas.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sysykeji.top/Article/details/gtuwujuhqh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nwbrower.top/Article/details/gtolhmqoch.html

[M04] 获取当前工作目录
来源：http://dali.birdmap.top/Article/details/gtmjvnnkjq.html

Py:   os.getcwd()
来源：http://dali.zhiwuduotai.top/Article/details/gtobaivoqx.html

PHP:  getcwd();
来源：http://dali.daria6918.cn/Article/details/gtfpcqavun.html

JS:   process.cwd()
来源：http://dali.kuanghao11.cn/Article/details/gtjowjcayt.html

TS:   process.cwd()
来源：http://dali.yangfankeji.com/Article/details/gtsznareet.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hongshengwenyu.top/Article/details/gtitlxkznw.html

Go:   os.Getwd()
来源：http://dali.zdqjudy.top/Article/details/gtruxhaqen.html

Ruby: Dir.pwd
来源：http://dali.dianchejie.cn/Article/details/gtczvtlpjy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.daxiang520.top/Article/details/gtpjusqnjg.html

[M05] 设置退出码
来源：http://dali.fzhhl.top/Article/details/gtnpseqoga.html

Py:   sys.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtvywfvwhw.html

PHP:  exit(1);
来源：http://dali.snrcjt.cn/Article/details/gtsccuopeo.html

JS:   process.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtrascgmpe.html

TS:   process.exit(1)
来源：http://dali.pycfn.com/Article/details/gtwkmhdlaw.html

Java: System.exit(1)
来源：http://dali.yj202588.top/Article/details/gthseloywv.html

Go:   os.Exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtcphibfok.html

Ruby: exit 1
来源：http://dali.zhoulong.xyz/Article/details/gtbaqgjiwr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.quarkkingdee.top/Article/details/gtvszncwfk.html

[M06] 向标准错误输出
来源：http://dali.shzxlz.cn/Article/details/gtyjohsgtu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yuanzhike.top/Article/details/gtbmhtobxz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.smart0.xyz/Article/details/gtdsajoqtp.html

JS:   console.error("err")
来源：http://dali.hfpthk.cn/Article/details/gthoxoqyyl.html

TS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gthoznvkek.html

Java: System.err.println("err")
来源：http://dali.jiagoushi.top/Article/details/gtxwzbwswk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.bjfxy.top/Article/details/gtcrlnmwbk.html

Ruby: warn "err"
来源：http://dali.ydzc1.top/Article/details/gtawbdlpdh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.fzhhl.top/Article/details/gtqravlsju.html

[M07] 判断是否为主入口
来源：http://dali.hfpthk.cn/Article/details/gtubktidmf.html

Py:   if __name__ == "__main__":
来源：http://dali.tianlin.xyz/Article/details/gtswkfkqac.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.316326.xyz/Article/details/gtovqyapax.html

JS:   require.main === module
来源：http://dali.mhx1999.top/Article/details/gtaamtloca.html

TS:   require.main === module
来源：http://dali.fengsongda.top/Article/details/gtrufbtjly.html

Java: public static void main(String[] args)
来源：http://dali.0kj1m.cn/Article/details/gtspmhpkyw.html

Go:   func main()
来源：http://dali.fzhhl.top/Article/details/gtvfghqtcc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shzxlz.cn/Article/details/gtohkeuicg.html

C#:   static void Main(string[] args)
来源：http://dali.316326.xyz/Article/details/gtkmkafdyl.html

[M08] 获取系统与运行时信息
来源：http://dali.daxiang520.top/Article/details/gtugubujxr.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gogol.net.cn/Article/details/gtvoieainj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jyoumei.cn/Article/details/gtajndxkxf.html

JS:   process.platform;  process.version
来源：http://dali.hfpthk.cn/Article/details/gtjgyfvllw.html

TS:   process.platform;  process.version
来源：http://dali.yj202588.top/Article/details/gtzuoneauf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gotoacloud.top/Article/details/gtdpaymqjg.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.wangdashe.top/Article/details/gtjikefmkz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sweek.top/Article/details/gtzgpnebmz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ehwqpu.com/Article/details/gtiaibcajd.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtdqpmbiqz.html

N. 数据结构与算法
来源：http://dali.havefunace.top/Article/details/gteleiejhm.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtulrgemhw.html

[N01] 二分查找（有序数组）
来源：http://dali.jianghu66.top/Article/details/gteijepzjy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gtnlvyhjhq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xinyue.icu/Article/details/gtgxsawjna.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.c1oappe.top/Article/details/gtyzutmcdt.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gtaaxhxeuk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtxlbtzgkc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtnhtjtvlr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shzxlz.cn/Article/details/gtbnhcbkze.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtehjldpmg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ehwqpu.com/Article/details/gtzirhdxou.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ppjwa.cn/Article/details/gtituxlkle.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zdqjudy.top/Article/details/gtctctqini.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yonumen.top/Article/details/gtrwuvghtq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zycfv.cn/Article/details/gtzxrlcmyq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.feifeiyinyue.top/Article/details/gtiinbgzfv.html

Go:   slices.Sort(arr)
来源：http://dali.bjfxy.top/Article/details/gtbtelfwqo.html

Ruby: arr.sort
来源：http://dali.daxiang520.top/Article/details/gttuaogwqo.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.meibo888.top/Article/details/gtxczgksjm.html

[N03] 快速排序（分治示例）
来源：http://dali.xziqi.cn/Article/details/gtabvowgkq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jianghu66.top/Article/details/gtwtivpvgd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.aibaodan.cn/Article/details/gtstspziyc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.havefunace.top/Article/details/gtyixsynha.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sweek.top/Article/details/gtzpwmvdva.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhiwuduotai.top/Article/details/gtvlpgoqpk.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.mhx1999.top/Article/details/gtjnlzvsii.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinqigufen.top/Article/details/gtjnnaejno.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfcjmwunl.html

[N04] 斐波那契数列
来源：http://dali.zhoulong.xyz/Article/details/gtokrhqizw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.tian-w.cn/Article/details/gttleuglvo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ybcxt.top/Article/details/gtbaxklgwz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gogol.net.cn/Article/details/gtztjpsuwx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiwbqgjvi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaajwxrps.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yj20258888.top/Article/details/gtbkhmcydi.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhengqikj.top/Article/details/gtisenqakx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gtxyristpm.html

[N05] 最大公约数
来源：http://dali.ivvv.top/Article/details/gtkihpfisz.html

Py:   math.gcd(a, b)
来源：http://dali.jiagoushi.top/Article/details/gtmpgfgijs.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.aizwys.cn/Article/details/gtyohiqeqw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj202588.top/Article/details/gtrddbjlms.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.iojbl.cn/Article/details/gtdjuwrdli.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.haohaochexian.top/Article/details/gtbkgbdiqq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.aizwys.cn/Article/details/gtxpfulvkb.html

Ruby: a.gcd(b)
来源：http://dali.hfpthk.cn/Article/details/gtptaysikb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.dianchejie.cn/Article/details/gtwiqvwqds.html

[N06] 判断回文字符串
来源：http://dali.cqqwz.cn/Article/details/gtgwsfuuuk.html

Py:   s == s[::-1]
来源：http://dali.zhongyouzk.top/Article/details/gtzqfqdbjv.html

PHP:  $s === strrev($s);
来源：http://dali.ybcxt.top/Article/details/gthqvtafiu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gtxdijefrk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gtamswrmcq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gogol.net.cn/Article/details/gtijanvbsh.html

Go:   // 双指针从两端比较
来源：http://dali.hammf.cn/Article/details/gtqrsgrfaw.html

Ruby: s == s.reverse
来源：http://dali.0kj1m.cn/Article/details/gtmlqcxufe.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xylfe.cn/Article/details/gtmaayxvqh.html

[N07] 两数之和（返回下标）
来源：http://dali.wangdashe.top/Article/details/gtbzolydht.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.pycfn.com/Article/details/gtjmdoogza.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.guowangkeji.top/Article/details/gtqdgirfsu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.aibaodan.cn/Article/details/gtazwiypux.html

TS:   // 手写 Map<string, number>
来源：http://dali.9152youxi.cn/Article/details/gtrhxcjqei.html

Java: // 手写 HashMap
来源：http://dali.yvedp.cn/Article/details/gtddognaae.html

Go:   // 手写 map[int]int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtekdpkdor.html

Ruby: // 手写 Hash
来源：http://dali.tian-w.cn/Article/details/gtlqbfmncq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cdnleiting.top/Article/details/gtpqttiikp.html

[N08] 生成全排列
来源：http://dali.chenzaomai.com/Article/details/gtkrctjazt.html

Py:   itertools.permutations(arr)
来源：http://dali.cdnleiting.top/Article/details/gtkxecrdhr.html

PHP:  // 手写递归交换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcyebnofd.html

JS:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gtvbjrftue.html

TS:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gtpkyixdra.html

Java: // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gtuwrltanz.html

Go:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gtnwprymat.html

Ruby: arr.permutation.to_a
来源：http://dali.iojbl.cn/Article/details/gthjmvwldf.html

C#:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtqdzfmfhk.html

[N09] 栈与队列
来源：http://dali.hfpthk.cn/Article/details/gtxgjyfhku.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.nanxinkj.top/Article/details/gtjyqltaio.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.smart0.xyz/Article/details/gtfbglcsjf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cucudq.cn/Article/details/gthczjosps.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jqgfzy.top/Article/details/gtddetyfzk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwmltozlv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yuanzhike.top/Article/details/gtnomixbak.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cheryme.top/Article/details/gtvdcrqzuv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yongpay.top/Article/details/gtaepcocde.html

[N10] 链表节点定义
来源：http://dali.tanke756.top/Article/details/gtceesnrim.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.316326.xyz/Article/details/gtevvbfgby.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sufxvd.cn/Article/details/gtrqdfngpl.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.nwbrower.top/Article/details/gtzigmgnqj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.mhx1999.top/Article/details/gtrjyymuzs.html

Java: class Node { int v; Node next; }
来源：http://dali.hnxiangtu.top/Article/details/gtgrhmtnqw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.pycfn.com/Article/details/gtcyqlwppd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ivvv.top/Article/details/gtwyktezvq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.meibo888.top/Article/details/gthwcunjtt.html

[N11] 二叉树中序遍历
来源：http://dali.hfpthk.cn/Article/details/gtspthzeng.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinqigufen.top/Article/details/gtnxfmiuwr.html

PHP:  // 手写递归函数
来源：http://dali.yangfankeji.com/Article/details/gtqwslyxto.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigfzy.top/Article/details/gtlwinpgls.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.mhx1999.top/Article/details/gtyeofbjev.html

Java: // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gtezcwgmdj.html

Go:   // 手写递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgarnrrdo.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcrgisfic.html

C#:   // 手写递归
来源：http://dali.aizwys.cn/Article/details/gturwlkdnm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shanyushiyangtech.top/Article/details/gtugszvtyo.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinqigfzy.top/Article/details/gtoyrrajvz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hywenlv.cn/Article/details/gtlbrdafnf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sxryk.cn/Article/details/gtfbsdeequ.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aibaodan.cn/Article/details/gtzrnzfpvn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cdnleiting.top/Article/details/gtfwskhkog.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrounelkt.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yonumen.top/Article/details/gtotoxblji.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daria6918.cn/Article/details/gtuumlymhx.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtrlbmsxub.html

O. 并发与异步
来源：http://dali.chenlongwang.top/Article/details/gtkfgludfj.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtghszpbjp.html

[O01] 启动一个线程
来源：http://dali.chenlongwang.top/Article/details/gtwviovcro.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cheryme.top/Article/details/gtwjghtkxi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.andypj.xyz/Article/details/gtqkiwexch.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhixingplan.top/Article/details/gtwvtfybub.html

TS:   // 同 JS
来源：http://dali.wangshuangyany.cn/Article/details/gtcpvxxeft.html

Java: new Thread(() -> f()).start()
来源：http://dali.yj202588.top/Article/details/gtbhxpbbrp.html

Go:   go f()
来源：http://dali.jianghu66.top/Article/details/gtashwelil.html

Ruby: Thread.new { f }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpsgpipgz.html

C#:   Task.Run(() => F());
来源：http://dali.fengsongda.top/Article/details/gtxqcfuwzl.html

[O02] 使用线程池
来源：http://dali.hnqzz.top/Article/details/gtgtxvjalw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zycfv.cn/Article/details/gtbwkgttnu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.guowangkeji.top/Article/details/gtailqwrqb.html

JS:   // worker_threads 线程池
来源：http://dali.yuanzhike.top/Article/details/gtlaptzcvr.html

TS:   // worker_threads 线程池
来源：http://dali.yj20258.top/Article/details/gtftinlker.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shangyingyoupin.top/Article/details/gtrngypziu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yangfankeji.com/Article/details/gtojnfaawl.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xuetiantiany.cn/Article/details/gtztfzvrrd.html


<!-- 参考信息 -->