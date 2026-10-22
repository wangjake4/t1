代发 wailian999

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xziqi.cn/Article/details/gt2ncteeufb.html

[K07] 进制转换
来源：http://dali.guowangkeji.top/Article/details/gt2tbcsbuno.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gt2zkvfigpi.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gogol.net.cn/Article/details/gt2tzteadom.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gt2ouaumbrf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gt2tfleevaz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gt2zxvewdeh.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ppjwa.cn/Article/details/gt2mprsniyy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2frbamqpk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gt2fgaruidy.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shuidangran.top/Article/details/gt2twshkglp.html

Py:   pickle.dumps(obj)
来源：http://dali.yj20258888.top/Article/details/gt2bqfrfwlx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yvedp.cn/Article/details/gt2wsigksus.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.pycfn.com/Article/details/gt2xzixryak.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.wangshuangyany.cn/Article/details/gt2hozsvlyb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hywenlv.cn/Article/details/gt2edppxyyi.html

Go:   encoding/gob
来源：http://dali.bjfxy.top/Article/details/gt2pvfcspdd.html

Ruby: Marshal.dump(obj)
来源：http://dali.yuxming.cn/Article/details/gt2npjxwmrq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nwbrower.top/Article/details/gt2uffdxzzc.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2liegbhoi.html

L. 网络请求
来源：http://dali.yuxming.cn/Article/details/gt2dpumghcy.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2rjxakvis.html

[L01] 发送 GET 请求
来源：http://dali.zhengqikj.top/Article/details/gt2gqhvbfom.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.smart0.xyz/Article/details/gt2hpjybftm.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.316326.xyz/Article/details/gt2ayqjlrxn.html

JS:   await fetch(url)
来源：http://dali.fengsongda.top/Article/details/gt2rrqibxmp.html

TS:   await fetch(url)
来源：http://dali.zhoulong.xyz/Article/details/gt2houqlace.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jlsjyb.cn/Article/details/gt2lmbkkdez.html

Go:   resp, err := http.Get(url)
来源：http://dali.fengsongda.top/Article/details/gt2uogakdft.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hongshengwenyu.top/Article/details/gt2zhlrfhqh.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ychbydbd.html

[L02] 发送 POST JSON
来源：http://dali.ivvv.top/Article/details/gt2lfwzbzwe.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cqqwz.cn/Article/details/gt2evosxhuz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.guannengcc.top/Article/details/gt2aytdvsnf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxuanxn.top/Article/details/gt2xoqqkuop.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxinkj.top/Article/details/gt2pjuxdtcv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jqgfzy.top/Article/details/gt2zltngysq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jlsjyb.cn/Article/details/gt2viclkvxj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ppjwa.cn/Article/details/gt2eivvhxqr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yj20258.top/Article/details/gt2gktarwqh.html

[L03] 设置自定义请求头
来源：http://dali.nanxuanxn.top/Article/details/gt2xtolbqhv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jqgfzy.top/Article/details/gt2zirfmuef.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.guowangkeji.top/Article/details/gt2necrlplc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sweek.top/Article/details/gt2rstpmxhb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangshuangyany.cn/Article/details/gt2wnfmobip.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jianghu66.top/Article/details/gt2tfqzppiu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinqigufen.top/Article/details/gt2jtndgbyp.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.iojbl.cn/Article/details/gt2aufxemqp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2femxxjxc.html

[L04] 设置超时
来源：http://dali.gotoacloud.top/Article/details/gt2dapeyjbe.html

Py:   requests.get(url, timeout=5)
来源：http://dali.smart0.xyz/Article/details/gt2ctlvrrkt.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yonumen.top/Article/details/gt2zyjfyffj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.meibo888.top/Article/details/gt2fjhjguva.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenlongwang.top/Article/details/gt2zjcwitlf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinqigufen.top/Article/details/gt2traftwsq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.redwolf501.top/Article/details/gt2uyjekbek.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.snrcjt.cn/Article/details/gt2jtmfdydk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.tanke756.top/Article/details/gt2kejvhjpg.html

[L05] 上传文件（multipart）
来源：http://dali.xuanzx.com/Article/details/gt2gvdaomrb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.birdmap.top/Article/details/gt2fssrbqqz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ppjwa.cn/Article/details/gt2jgztolmg.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.bjfxy.top/Article/details/gt2zyburniv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.iojbl.cn/Article/details/gt2ffbxbhxd.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yvedp.cn/Article/details/gt2ikvzrjcx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hywenlv.cn/Article/details/gt2hdgrushq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.haohaochexian.top/Article/details/gt2swgctcyp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nwbrower.top/Article/details/gt2btxwccpn.html

[L06] 解析响应为 JSON
来源：http://dali.jinqigfzy.top/Article/details/gt2iosjexxl.html

Py:   resp.json()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ulxlseio.html

PHP:  json_decode($body, true);
来源：http://dali.feifeiyinyue.top/Article/details/gt2llugyfzl.html

JS:   await resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gt2ygaovouv.html

TS:   await resp.json()
来源：http://dali.cheryme.top/Article/details/gt2bkhbawyb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.9152youxi.cn/Article/details/gt2tiqtukxi.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yonumen.top/Article/details/gt2obhcuidp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xylfe.cn/Article/details/gt2oyacbwyy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.meibo888.top/Article/details/gt2qcumbnbh.html

[L07] 处理 HTTP 状态码
来源：http://dali.birdmap.top/Article/details/gt2dqjpwygs.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhengqikj.top/Article/details/gt2qhzipkhh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.tianlin.xyz/Article/details/gt2euhclgeb.html

JS:   resp.ok;  resp.status
来源：http://dali.sweek.top/Article/details/gt2wxejfsml.html

TS:   resp.ok;  resp.status
来源：http://dali.zdqjudy.top/Article/details/gt2hamlsepf.html

Java: resp.statusCode()
来源：http://dali.iojbl.cn/Article/details/gt2mdaqshgb.html

Go:   resp.StatusCode
来源：http://dali.quarkkingdee.top/Article/details/gt2apdpxnhn.html

Ruby: resp.code.to_i
来源：http://dali.yuanzhike.top/Article/details/gt2mzzqsfuj.html

C#:   (int)resp.StatusCode
来源：http://dali.guowangkeji.top/Article/details/gt2zvwtyznr.html

[L08] 并发请求多个地址
来源：http://dali.jqgfzy.top/Article/details/gt2bjayturp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.wangdashe.top/Article/details/gt2cwmbsorr.html

PHP:  curl_multi_init() 系列
来源：http://dali.daria6918.cn/Article/details/gt2xlfmwgae.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenzaomai.com/Article/details/gt2xftpsgul.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.birdmap.top/Article/details/gt2wytzxkyp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aljvvncf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.vqdsnc.cn/Article/details/gt2rapbafmv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2anixclws.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.aibaodan.cn/Article/details/gt2edcyzdzj.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2ieqcvhze.html

M. 命令行 / 进程 / 环境
来源：http://dali.pycfn.com/Article/details/gt2ozmozksl.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2wlvidlrg.html

[M01] 读取命令行参数
来源：http://dali.xuetiantiany.cn/Article/details/gt2lkhfmrve.html

Py:   sys.argv[1:]
来源：http://dali.gzhubu.top/Article/details/gt2nowmxvex.html

PHP:  $argv;  $argc;
来源：http://dali.gogol.net.cn/Article/details/gt2qsjtpvpj.html

JS:   process.argv.slice(2)
来源：http://dali.shuidangran.top/Article/details/gt2ydtcspbu.html

TS:   process.argv.slice(2)
来源：http://dali.yvedp.cn/Article/details/gt2pbdlfmtv.html

Java: args 数组（main 方法参数）
来源：http://dali.jianghu66.top/Article/details/gt2lawdztpg.html

Go:   os.Args[1:]
来源：http://dali.gzhubu.top/Article/details/gt2fnvksngb.html

Ruby: ARGV
来源：http://dali.shuidangran.top/Article/details/gt2zxgfeyzj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sysykeji.top/Article/details/gt2fpebmgsz.html

[M02] 读取环境变量
来源：http://dali.quarkkingdee.top/Article/details/gt2shiwefvi.html

Py:   os.environ.get("HOME")
来源：http://dali.cdnleiting.top/Article/details/gt2xqzgyzyd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zycfv.cn/Article/details/gt2hsvxoguj.html

JS:   process.env.HOME
来源：http://dali.zhoulong.xyz/Article/details/gt2iafrntrz.html

TS:   process.env.HOME
来源：http://dali.316326.xyz/Article/details/gt2dfyxzfeo.html

Java: System.getenv("HOME")
来源：http://dali.bjfxy.top/Article/details/gt2olpjuldf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hysaishi.cn/Article/details/gt2egbptcbh.html

Ruby: ENV["HOME"]
来源：http://dali.chenzaomai.com/Article/details/gt2ptoydvzx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zdqjudy.top/Article/details/gt2yzlmmofd.html

[M03] 执行外部命令
来源：http://dali.tian-w.cn/Article/details/gt2omkxgqmy.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.meibo888.top/Article/details/gt2qkfhucxs.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cdnleiting.top/Article/details/gt2kpbcjvco.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ybcxt.top/Article/details/gt2wxiaqqxq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ydzc1.top/Article/details/gt2uyxkoyfp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhixingplan.top/Article/details/gt2eotxizsn.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hammf.cn/Article/details/gt2gqkzzwxu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yuxming.cn/Article/details/gt2hgwifvnc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhiwuduotai.top/Article/details/gt2roakafwx.html

[M04] 获取当前工作目录
来源：http://dali.yanxiufei.cn/Article/details/gt2usmnzoej.html

Py:   os.getcwd()
来源：http://dali.dianchejie.cn/Article/details/gt2ovnretno.html

PHP:  getcwd();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2btvteexy.html

JS:   process.cwd()
来源：http://dali.shuidangran.top/Article/details/gt2wbtkvjxh.html

TS:   process.cwd()
来源：http://dali.daria6918.cn/Article/details/gt2stwysspx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2yfnxvyty.html

Go:   os.Getwd()
来源：http://dali.ydzc1.top/Article/details/gt2qfndlbhi.html

Ruby: Dir.pwd
来源：http://dali.hammf.cn/Article/details/gt2qxpacvpy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2piwicxkn.html

[M05] 设置退出码
来源：http://dali.tanke756.top/Article/details/gt2jzxmeoxn.html

Py:   sys.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gt2njzxcaef.html

PHP:  exit(1);
来源：http://dali.dianchejie.cn/Article/details/gt2rksphhmw.html

JS:   process.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gt2hnrfsuae.html

TS:   process.exit(1)
来源：http://dali.yongpay.top/Article/details/gt2kvjxsdgu.html

Java: System.exit(1)
来源：http://dali.ivvv.top/Article/details/gt2wsyimvji.html

Go:   os.Exit(1)
来源：http://dali.zhixingplan.top/Article/details/gt2elgmbkir.html

Ruby: exit 1
来源：http://dali.xylfe.cn/Article/details/gt2otjkconb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cashguo.top/Article/details/gt2gvoguujt.html

[M06] 向标准错误输出
来源：http://dali.ydzc1.top/Article/details/gt2ddkmkrqy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xinyue.icu/Article/details/gt2rqgvihgj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yueranfly.top/Article/details/gt2ltqxaqin.html

JS:   console.error("err")
来源：http://dali.xinyue.icu/Article/details/gt2byezeqiw.html

TS:   console.error("err")
来源：http://dali.snrcjt.cn/Article/details/gt2lfnpnidv.html

Java: System.err.println("err")
来源：http://dali.9152youxi.cn/Article/details/gt2gpkzyhgm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hywenlv.cn/Article/details/gt2tjiupwgp.html

Ruby: warn "err"
来源：http://dali.xuetiantiany.cn/Article/details/gt2wjxsbmtj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.haohaochexian.top/Article/details/gt2juatvhua.html

[M07] 判断是否为主入口
来源：http://dali.shuidangran.top/Article/details/gt2qvvouygx.html

Py:   if __name__ == "__main__":
来源：http://dali.sufxvd.cn/Article/details/gt2pwvjghhb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.c1oappe.top/Article/details/gt2rbixcxjh.html

JS:   require.main === module
来源：http://dali.daria6918.cn/Article/details/gt2pppkbzvi.html

TS:   require.main === module
来源：http://dali.xylfe.cn/Article/details/gt2vtwpttxy.html

Java: public static void main(String[] args)
来源：http://dali.nanxuanxn.top/Article/details/gt2xoysurmn.html

Go:   func main()
来源：http://dali.cheryme.top/Article/details/gt2rqqdxatc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sxryk.cn/Article/details/gt2iykolxmt.html

C#:   static void Main(string[] args)
来源：http://dali.jlsjyb.cn/Article/details/gt2qawmmzxa.html

[M08] 获取系统与运行时信息
来源：http://dali.cqqwz.cn/Article/details/gt2vsxyneaq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.vqdsnc.cn/Article/details/gt2jsbatlfc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xuanzx.com/Article/details/gt2qpfircss.html

JS:   process.platform;  process.version
来源：http://dali.tianlin.xyz/Article/details/gt2ywbqeedp.html

TS:   process.platform;  process.version
来源：http://dali.xylfe.cn/Article/details/gt2bpucgtnj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nmspnrvu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shangyingyoupin.top/Article/details/gt2vnsfcqin.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jqgufenzy.top/Article/details/gt2usnssmlf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.smart0.xyz/Article/details/gt2llaqdbcx.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2geyufgry.html

N. 数据结构与算法
来源：http://dali.yj20258.top/Article/details/gt2rubaqjdh.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2hhmbdafk.html

[N01] 二分查找（有序数组）
来源：http://dali.vqdsnc.cn/Article/details/gt2qqzxaiqm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.mhx1999.top/Article/details/gt2ilxwwjtu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.aibaodan.cn/Article/details/gt2lxvvujsa.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ydzc1.top/Article/details/gt2kxgvftxj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sxryk.cn/Article/details/gt2zppoecnq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gt2cdlyzkva.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gt2tpjypvbq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sweek.top/Article/details/gt2arqwomtd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.andypj.xyz/Article/details/gt2meigdatz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yuxming.cn/Article/details/gt2zbsdrtkc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tian-w.cn/Article/details/gt2gskpjmdh.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.birdmap.top/Article/details/gt2nlhmwmwf.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhoulong.xyz/Article/details/gt2zleocwvh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zjcextkb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jqgfzy.top/Article/details/gt2divwqsad.html

Go:   slices.Sort(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2zskklsgu.html

Ruby: arr.sort
来源：http://dali.jlsjyb.cn/Article/details/gt2ztvicfar.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2cohmoubb.html

[N03] 快速排序（分治示例）
来源：http://dali.xuanzx.com/Article/details/gt2zzhrlwdy.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.haohaochexian.top/Article/details/gt2oypipqri.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bwdlunmi.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lodogosi.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sweek.top/Article/details/gt2gmdzkaih.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cdnleiting.top/Article/details/gt2meitaafk.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yvedp.cn/Article/details/gt2ycvdocvi.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yonumen.top/Article/details/gt2rvoseywq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ybcxt.top/Article/details/gt2oapwjmoy.html

[N04] 斐波那契数列
来源：http://dali.hammf.cn/Article/details/gt2ufxdqpbe.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2mwtnpnmg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yuxming.cn/Article/details/gt2nckqjwdd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dashuyun.cn/Article/details/gt2jbozkigp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigufen.top/Article/details/gt2oqyajuou.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jlsjyb.cn/Article/details/gt2rgxjonec.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yj202588.top/Article/details/gt2zmsfjyjc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.haohaochexian.top/Article/details/gt2eabgxazo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.kuanghao11.cn/Article/details/gt2fiflzvkp.html

[N05] 最大公约数
来源：http://dali.birdmap.top/Article/details/gt2dwbbfocy.html

Py:   math.gcd(a, b)
来源：http://dali.c1oappe.top/Article/details/gt2deeypozu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bcuqvfbq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aizwys.cn/Article/details/gt2nbbgdsxp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gzhubu.top/Article/details/gt2jkvrnlsz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.316326.xyz/Article/details/gt2yrpuaymy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shuidangran.top/Article/details/gt2uvxwcvxz.html

Ruby: a.gcd(b)
来源：http://dali.xinyue.icu/Article/details/gt2qcprspcv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.aibaodan.cn/Article/details/gt2aakjboso.html

[N06] 判断回文字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2xcfkmxcr.html

Py:   s == s[::-1]
来源：http://dali.dashuyun.cn/Article/details/gt2ppcxgwke.html

PHP:  $s === strrev($s);
来源：http://dali.0kj1m.cn/Article/details/gt2bvemplmm.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gt2bcvcfzci.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ydzc1.top/Article/details/gt2omyrxfib.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.pycfn.com/Article/details/gt2bwvjvnbu.html

Go:   // 双指针从两端比较
来源：http://dali.yj202588.top/Article/details/gt2vugpkkvq.html

Ruby: s == s.reverse
来源：http://dali.fzhhl.top/Article/details/gt2rurltrlh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shzxlz.cn/Article/details/gt2cdpwdbjf.html

[N07] 两数之和（返回下标）
来源：http://dali.hongshengwenyu.top/Article/details/gt2cjoxxmit.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhoulong.xyz/Article/details/gt2gaztbsst.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kotsrqsj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.mhx1999.top/Article/details/gt2ezotrwqt.html

TS:   // 手写 Map<string, number>
来源：http://dali.mhx1999.top/Article/details/gt2enadlmwu.html

Java: // 手写 HashMap
来源：http://dali.c1oappe.top/Article/details/gt2eifrrqmk.html

Go:   // 手写 map[int]int
来源：http://dali.gogol.net.cn/Article/details/gt2mflulqdk.html

Ruby: // 手写 Hash
来源：http://dali.sysykeji.top/Article/details/gt2jkvhvbct.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jqgfzy.top/Article/details/gt2bdsztiyu.html

[N08] 生成全排列
来源：http://dali.hywenlv.cn/Article/details/gt2hipwpazf.html

Py:   itertools.permutations(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2faczmmqk.html

PHP:  // 手写递归交换
来源：http://dali.bjfxy.top/Article/details/gt2mmrggxsc.html

JS:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gt2tuismjtp.html

TS:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gt2zasddfhv.html

Java: // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gt2nqunnihn.html

Go:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gt2xpedalql.html

Ruby: arr.permutation.to_a
来源：http://dali.xuanzx.com/Article/details/gt2ziqbjxmo.html

C#:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gt2pcuwflcs.html

[N09] 栈与队列
来源：http://dali.redwolf501.top/Article/details/gt2hajwcvao.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jlsjyb.cn/Article/details/gt2pggspeow.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2guoknppd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hfpthk.cn/Article/details/gt2yzztojax.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.chenjidiqi.icu/Article/details/gt2wakgjdcb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yvedp.cn/Article/details/gt2vacxrlrq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jiagoushi.top/Article/details/gt2gwfkszmd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gt2dqnpkbyx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xziqi.cn/Article/details/gt2wpocmwqa.html

[N10] 链表节点定义
来源：http://dali.havefunace.top/Article/details/gt2swsuxwsm.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhixingplan.top/Article/details/gt2nclpczwo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xuanzx.com/Article/details/gt2vfwugjfj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.havefunace.top/Article/details/gt2fkxjzrmb.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ivvv.top/Article/details/gt2ukziunak.html

Java: class Node { int v; Node next; }
来源：http://dali.sxryk.cn/Article/details/gt2ytlwrrtq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.birdmap.top/Article/details/gt2osujpmup.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.daxiang520.top/Article/details/gt2nhruhsri.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.vqdsnc.cn/Article/details/gt2cxsogrze.html

[N11] 二叉树中序遍历
来源：http://dali.chenlongwang.top/Article/details/gt2jevrerom.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2juatwokq.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjuhhhi.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yonumen.top/Article/details/gt2epbspxap.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhiwuduotai.top/Article/details/gt2cxepbwhj.html

Java: // 手写递归
来源：http://dali.quarkkingdee.top/Article/details/gt2zwameerx.html

Go:   // 手写递归
来源：http://dali.hnxiangtu.top/Article/details/gt2mjbxnoeg.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hammf.cn/Article/details/gt2thcavbhv.html

C#:   // 手写递归
来源：http://dali.aibaodan.cn/Article/details/gt2lwxkicie.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2djtbdgty.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.nanxuanxn.top/Article/details/gt2xohfxsev.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xziqi.cn/Article/details/gt2pcvchtea.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ybcxt.top/Article/details/gt2flekrpgt.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhixingplan.top/Article/details/gt2gtnzidhw.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.smart0.xyz/Article/details/gt2zttrmrer.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xuanzx.com/Article/details/gt2jbtxciap.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.haohaochexian.top/Article/details/gt2mzredcuj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ybcxt.top/Article/details/gt2vwonmoim.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2kjcnxhfd.html

O. 并发与异步
来源：http://dali.jqgufenzy.top/Article/details/gt2pjqhqpez.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ntyhsxvq.html

[O01] 启动一个线程
来源：http://dali.nanxinkj.top/Article/details/gt2sjanwcnu.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ppjwa.cn/Article/details/gt2zarqyycb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hnxiangtu.top/Article/details/gt2cdswjolf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.chenzaomai.com/Article/details/gt2boorufyh.html

TS:   // 同 JS
来源：http://dali.sxryk.cn/Article/details/gt2nyyptkpi.html

Java: new Thread(() -> f()).start()
来源：http://dali.jqgufenzy.top/Article/details/gt2kjehkern.html

Go:   go f()
来源：http://dali.kuanghao11.cn/Article/details/gt2xhqlksqv.html

Ruby: Thread.new { f }
来源：http://dali.xuetiantiany.cn/Article/details/gt2fnmttgzu.html

C#:   Task.Run(() => F());
来源：http://dali.cashguo.top/Article/details/gt2cooxxvmc.html

[O02] 使用线程池
来源：http://dali.nanxinkj.top/Article/details/gt2qxepmdbl.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ydzc1.top/Article/details/gt2kvqsufnz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ivvv.top/Article/details/gt2evdyhpuu.html

JS:   // worker_threads 线程池
来源：http://dali.ppjwa.cn/Article/details/gt2deanmoxo.html

TS:   // worker_threads 线程池
来源：http://dali.wangshuangyany.cn/Article/details/gt2stzfvuyy.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hammf.cn/Article/details/gt2ncmszrff.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cqqwz.cn/Article/details/gt2ekyhjfgr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jinqigfzy.top/Article/details/gt2sljnxpzc.html


<!-- 参考信息 -->