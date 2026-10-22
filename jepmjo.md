代发 wailian999

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gt2adovjsbm.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.meibo888.top/Article/details/gt2xqnloqpb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cheryme.top/Article/details/gt2wyvashgs.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.smart0.xyz/Article/details/gt2xmobbzhx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xylfe.cn/Article/details/gt2bityedwo.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gt2njiqawxi.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yj20258.top/Article/details/gt2gfezyota.html

Py:   pickle.dumps(obj)
来源：http://dali.xinyue.icu/Article/details/gt2fbqefrpq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cashguo.top/Article/details/gt2wbuambtu.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.fengsongda.top/Article/details/gt2exiqyhha.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.birdmap.top/Article/details/gt2pjeibljm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yanxiufei.cn/Article/details/gt2bxwlrcvp.html

Go:   encoding/gob
来源：http://dali.birdmap.top/Article/details/gt2xpcnerlf.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ziqvcbfp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.redwolf501.top/Article/details/gt2bcmsizds.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2lydfkuhr.html

L. 网络请求
来源：http://dali.xuanzx.com/Article/details/gt2rgahqpbg.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2rqdcwbyi.html

[L01] 发送 GET 请求
来源：http://dali.vqdsnc.cn/Article/details/gt2arfagakp.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.smart0.xyz/Article/details/gt2wufedohg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sufxvd.cn/Article/details/gt2bahwlail.html

JS:   await fetch(url)
来源：http://dali.jinqigfzy.top/Article/details/gt2ayucopbc.html

TS:   await fetch(url)
来源：http://dali.yangfankeji.com/Article/details/gt2xvmprgrg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yanxiufei.cn/Article/details/gt2zzdkivmy.html

Go:   resp, err := http.Get(url)
来源：http://dali.nanxinkj.top/Article/details/gt2gupfhkgi.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.chenlongwang.top/Article/details/gt2fuicfmqt.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jlsjyb.cn/Article/details/gt2fukvmwdf.html

[L02] 发送 POST JSON
来源：http://dali.yj202588.top/Article/details/gt2azxjedel.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.nwbrower.top/Article/details/gt2eygvjthg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kizixber.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gzhubu.top/Article/details/gt2zjddqpqc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guannengcc.top/Article/details/gt2pkxyihor.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhiwuduotai.top/Article/details/gt2dvsedwlm.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.0kj1m.cn/Article/details/gt2llyihoty.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.bjfxy.top/Article/details/gt2bcmulhfh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.iojbl.cn/Article/details/gt2vudmhxvz.html

[L03] 设置自定义请求头
来源：http://dali.cucudq.cn/Article/details/gt2zfhztwzf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.meibo888.top/Article/details/gt2oqlkyjnn.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cashguo.top/Article/details/gt2brmkrncp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.bjfxy.top/Article/details/gt2oqjzwavg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xziqi.cn/Article/details/gt2whfqxvgy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhongyouzk.top/Article/details/gt2oifgudgz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.tian-w.cn/Article/details/gt2ttwfpfwk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zycfv.cn/Article/details/gt2ifvgpomm.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.haohaochexian.top/Article/details/gt2rblnyphv.html

[L04] 设置超时
来源：http://dali.fengsongda.top/Article/details/gt2yqaouwsi.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jlsjyb.cn/Article/details/gt2tcvsjdof.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhoulong.xyz/Article/details/gt2eqexfnkh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xinyue.icu/Article/details/gt2yhwtuwcp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zdqjudy.top/Article/details/gt2xolhtyjv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yj202588.top/Article/details/gt2xcznjzcw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qoabsjmg.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zdqjudy.top/Article/details/gt2bbnqfyvr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yuxming.cn/Article/details/gt2popfspil.html

[L05] 上传文件（multipart）
来源：http://dali.zhixingplan.top/Article/details/gt2fgcmsgky.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ybcxt.top/Article/details/gt2jahfpdcq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ehwqpu.com/Article/details/gt2jlknmuxx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuanzhike.top/Article/details/gt2awulrhmf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.andypj.xyz/Article/details/gt2iroozfyv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nanxinkj.top/Article/details/gt2hysqfxfi.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtfrbsa.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cashguo.top/Article/details/gt2ccowcocu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yvedp.cn/Article/details/gt2iasjjhyt.html

[L06] 解析响应为 JSON
来源：http://dali.nwbrower.top/Article/details/gt2zsocirwp.html

Py:   resp.json()
来源：http://dali.yj202588.top/Article/details/gt2ivgfmdgr.html

PHP:  json_decode($body, true);
来源：http://dali.quarkkingdee.top/Article/details/gt2unqotsrx.html

JS:   await resp.json()
来源：http://dali.iojbl.cn/Article/details/gt2vyrzynjz.html

TS:   await resp.json()
来源：http://dali.cdnleiting.top/Article/details/gt2udjxiaeg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yanxiufei.cn/Article/details/gt2kgblleyt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kisppppb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jiagoushi.top/Article/details/gt2ymfstqau.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.dianchejie.cn/Article/details/gt2nyxxzcee.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhengqikj.top/Article/details/gt2zeuoebeh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.316326.xyz/Article/details/gt2amsxfvyz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kqojemzu.html

JS:   resp.ok;  resp.status
来源：http://dali.dashuyun.cn/Article/details/gt2wuxcmgky.html

TS:   resp.ok;  resp.status
来源：http://dali.sweek.top/Article/details/gt2xegvhemi.html

Java: resp.statusCode()
来源：http://dali.guowangkeji.top/Article/details/gt2eqczyjdh.html

Go:   resp.StatusCode
来源：http://dali.daria6918.cn/Article/details/gt2ujnskboq.html

Ruby: resp.code.to_i
来源：http://dali.chenzaomai.com/Article/details/gt2bxncbolf.html

C#:   (int)resp.StatusCode
来源：http://dali.xinyue.icu/Article/details/gt2czgfbnzp.html

[L08] 并发请求多个地址
来源：http://dali.nwbrower.top/Article/details/gt2fknnwpxg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nanxuanxn.top/Article/details/gt2jacxjcyp.html

PHP:  curl_multi_init() 系列
来源：http://dali.fengsongda.top/Article/details/gt2feiorgqx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gt2efpbvuio.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sysykeji.top/Article/details/gt2weldprhl.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.dianchejie.cn/Article/details/gt2aqdenxir.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ybcxt.top/Article/details/gt2xhrwrrtf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.svipenyu.cn/Article/details/gt2ecgyqdfk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fxexoyhz.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2spxfqcic.html

M. 命令行 / 进程 / 环境
来源：http://dali.cucudq.cn/Article/details/gt2etduipar.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2xlnxvabq.html

[M01] 读取命令行参数
来源：http://dali.ehwqpu.com/Article/details/gt2xqvbcpux.html

Py:   sys.argv[1:]
来源：http://dali.jqgufenzy.top/Article/details/gt2vhxwbpcn.html

PHP:  $argv;  $argc;
来源：http://dali.gzhubu.top/Article/details/gt2wqjuigyc.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yncsiojk.html

TS:   process.argv.slice(2)
来源：http://dali.yonumen.top/Article/details/gt2eysirwwm.html

Java: args 数组（main 方法参数）
来源：http://dali.meibo888.top/Article/details/gt2uqigpdzg.html

Go:   os.Args[1:]
来源：http://dali.chenlongwang.top/Article/details/gt2tcuzqqkd.html

Ruby: ARGV
来源：http://dali.feifeiyinyue.top/Article/details/gt2cpqtcxgi.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ojtoxpdv.html

[M02] 读取环境变量
来源：http://dali.wangdashe.top/Article/details/gt2ylkmicfk.html

Py:   os.environ.get("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gt2fbapszuv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.smart0.xyz/Article/details/gt2ouuuljqw.html

JS:   process.env.HOME
来源：http://dali.gotoacloud.top/Article/details/gt2warageud.html

TS:   process.env.HOME
来源：http://dali.daxiang520.top/Article/details/gt2bkabqufn.html

Java: System.getenv("HOME")
来源：http://dali.c1oappe.top/Article/details/gt2hpffrzpe.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.316326.xyz/Article/details/gt2xefbpynl.html

Ruby: ENV["HOME"]
来源：http://dali.shzxlz.cn/Article/details/gt2zywafwwr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gotoacloud.top/Article/details/gt2wwkapvhr.html

[M03] 执行外部命令
来源：http://dali.cashguo.top/Article/details/gt2lbvlkglk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rijrwxjt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.316326.xyz/Article/details/gt2mefbgjvp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.vqdsnc.cn/Article/details/gt2foacyopn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuetiantiany.cn/Article/details/gt2yxqripro.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yuxming.cn/Article/details/gt2czenzqlb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hongshengwenyu.top/Article/details/gt2liuthtob.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhengqikj.top/Article/details/gt2rsyumeao.html

C#:   Process.Start("ls", "-l");
来源：http://dali.birdmap.top/Article/details/gt2tawdabuy.html

[M04] 获取当前工作目录
来源：http://dali.hywenlv.cn/Article/details/gt2yaoarjbt.html

Py:   os.getcwd()
来源：http://dali.nwbrower.top/Article/details/gt2sqszahyo.html

PHP:  getcwd();
来源：http://dali.jlsjyb.cn/Article/details/gt2ankqnrqa.html

JS:   process.cwd()
来源：http://dali.guannengcc.top/Article/details/gt2qgxwtktd.html

TS:   process.cwd()
来源：http://dali.zhixingplan.top/Article/details/gt2xgpbuehb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhixingplan.top/Article/details/gt2xcyunxgb.html

Go:   os.Getwd()
来源：http://dali.chenzaomai.com/Article/details/gt2yfdylsyq.html

Ruby: Dir.pwd
来源：http://dali.sysykeji.top/Article/details/gt2cbkjfnwa.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.aizwys.cn/Article/details/gt2wtvfluue.html

[M05] 设置退出码
来源：http://dali.zdqjudy.top/Article/details/gt2zwhwymwd.html

Py:   sys.exit(1)
来源：http://dali.gzhubu.top/Article/details/gt2mgdpjpds.html

PHP:  exit(1);
来源：http://dali.gaohongyu789.top/Article/details/gt2dbwmqukf.html

JS:   process.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gt2rqaogogj.html

TS:   process.exit(1)
来源：http://dali.xylfe.cn/Article/details/gt2ilfuntvu.html

Java: System.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gt2moejzfsj.html

Go:   os.Exit(1)
来源：http://dali.yj202588.top/Article/details/gt2nuojxrgj.html

Ruby: exit 1
来源：http://dali.zhiwuduotai.top/Article/details/gt2vhktpksv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj20258888.top/Article/details/gt2kjhjfujv.html

[M06] 向标准错误输出
来源：http://dali.ppjwa.cn/Article/details/gt2ihhnbayo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinqigufen.top/Article/details/gt2tmgzlvjc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.chenjidiqi.icu/Article/details/gt2ahfretye.html

JS:   console.error("err")
来源：http://dali.yonumen.top/Article/details/gt2eaelctat.html

TS:   console.error("err")
来源：http://dali.cashguo.top/Article/details/gt2sonyubrd.html

Java: System.err.println("err")
来源：http://dali.xuetiantiany.cn/Article/details/gt2louatdrl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xuetiantiany.cn/Article/details/gt2txoxcntn.html

Ruby: warn "err"
来源：http://dali.yj20258888.top/Article/details/gt2jyjlvjgp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhoulong.xyz/Article/details/gt2fsafcgln.html

[M07] 判断是否为主入口
来源：http://dali.redwolf501.top/Article/details/gt2azhizfec.html

Py:   if __name__ == "__main__":
来源：http://dali.chenjidiqi.icu/Article/details/gt2sltbdaxi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.birdmap.top/Article/details/gt2mebztmfd.html

JS:   require.main === module
来源：http://dali.hywenlv.cn/Article/details/gt2nderplvr.html

TS:   require.main === module
来源：http://dali.aibaodan.cn/Article/details/gt2topxsjxw.html

Java: public static void main(String[] args)
来源：http://dali.birdmap.top/Article/details/gt2gmphkowo.html

Go:   func main()
来源：http://dali.shangyingyoupin.top/Article/details/gt2qbbrqkun.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cashguo.top/Article/details/gt2fhnyuwxq.html

C#:   static void Main(string[] args)
来源：http://dali.guowangkeji.top/Article/details/gt2hfgiomjm.html

[M08] 获取系统与运行时信息
来源：http://dali.zhongyouzk.top/Article/details/gt2qyzqfbiz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.wangdashe.top/Article/details/gt2jwjenqgp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cucudq.cn/Article/details/gt2ngusakns.html

JS:   process.platform;  process.version
来源：http://dali.yvedp.cn/Article/details/gt2eclvfdmy.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2akjrdfys.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.c1oappe.top/Article/details/gt2jlwknsfx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shangyingyoupin.top/Article/details/gt2oqbnwjcy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.meibo888.top/Article/details/gt2ulklaimn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.haohaochexian.top/Article/details/gt2ssqyplaj.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2xxgyjtwo.html

N. 数据结构与算法
来源：http://dali.cqqwz.cn/Article/details/gt2nzihdrds.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2nawiossb.html

[N01] 二分查找（有序数组）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2euwxcdzp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xylfe.cn/Article/details/gt2qkvuhvui.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.aizwys.cn/Article/details/gt2sdjlrfte.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenjidiqi.icu/Article/details/gt2atloqzck.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.kuanghao11.cn/Article/details/gt2lnlopwju.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gt2nybqlcul.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.tian-w.cn/Article/details/gt2xctbafdq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sysykeji.top/Article/details/gt2wgctwehe.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.birdmap.top/Article/details/gt2ptdqffqj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yj20258.top/Article/details/gt2ojuirhmy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yvedp.cn/Article/details/gt2fifxgcad.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.andypj.xyz/Article/details/gt2awufokhg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shzxlz.cn/Article/details/gt2kzabohkg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jyoumei.cn/Article/details/gt2omtjvfpz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.smart0.xyz/Article/details/gt2gfzsyfas.html

Go:   slices.Sort(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hntajnyi.html

Ruby: arr.sort
来源：http://dali.zhengqikj.top/Article/details/gt2hgoptjsf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xuetiantiany.cn/Article/details/gt2riaiieal.html

[N03] 快速排序（分治示例）
来源：http://dali.zhengqikj.top/Article/details/gt2kfczrjpv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ydzc1.top/Article/details/gt2azuslxbp.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hongshengwenyu.top/Article/details/gt2hurrfnva.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tanke756.top/Article/details/gt2gxgoeqbm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aizwys.cn/Article/details/gt2flghwqbl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.pengpengdd.cyou/Article/details/gt2ackzmwfe.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sxryk.cn/Article/details/gt2whgaxsuq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.c1oappe.top/Article/details/gt2pquwkqyb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yonumen.top/Article/details/gt2sqeozige.html

[N04] 斐波那契数列
来源：http://dali.dashuyun.cn/Article/details/gt2jzjwwwva.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.iojbl.cn/Article/details/gt2jvexmyoy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.daxiang520.top/Article/details/gt2flzolyjx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cashguo.top/Article/details/gt2bcapngwo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shangyingyoupin.top/Article/details/gt2vakwwdnj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.andypj.xyz/Article/details/gt2rqhlwxjs.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cucudq.cn/Article/details/gt2smllkomg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hnxiangtu.top/Article/details/gt2zbzcqqtc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hysaishi.cn/Article/details/gt2lxnfpinq.html

[N05] 最大公约数
来源：http://dali.pycfn.com/Article/details/gt2csknkhki.html

Py:   math.gcd(a, b)
来源：http://dali.tanke756.top/Article/details/gt2bhhkxdbx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.daxiang520.top/Article/details/gt2pfwbbbge.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daria6918.cn/Article/details/gt2sewldikl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dianchejie.cn/Article/details/gt2gjoqdwfe.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.pycfn.com/Article/details/gt2boqxyhhv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yuxming.cn/Article/details/gt2msgreshc.html

Ruby: a.gcd(b)
来源：http://dali.ybcxt.top/Article/details/gt2xkiuemje.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2auhxvtud.html

[N06] 判断回文字符串
来源：http://dali.gzhubu.top/Article/details/gt2guoactoh.html

Py:   s == s[::-1]
来源：http://dali.zhoulong.xyz/Article/details/gt2qmcvgpnn.html

PHP:  $s === strrev($s);
来源：http://dali.jianghu66.top/Article/details/gt2hnosxpia.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shangyingyoupin.top/Article/details/gt2urrormtx.html

TS:   s === [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gt2iaxbrlya.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yanxiufei.cn/Article/details/gt2bohfgzvj.html

Go:   // 双指针从两端比较
来源：http://dali.yueranfly.top/Article/details/gt2tondyhar.html

Ruby: s == s.reverse
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iubsczof.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jianghu66.top/Article/details/gt2xoaxhgdo.html

[N07] 两数之和（返回下标）
来源：http://dali.quarkkingdee.top/Article/details/gt2qidujcbs.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.dianchejie.cn/Article/details/gt2kwprwdqg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yanxiufei.cn/Article/details/gt2iokvyheg.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2crcchxee.html

TS:   // 手写 Map<string, number>
来源：http://dali.snrcjt.cn/Article/details/gt2drkdqrge.html

Java: // 手写 HashMap
来源：http://dali.9152youxi.cn/Article/details/gt2itkjpkhl.html

Go:   // 手写 map[int]int
来源：http://dali.jqgufenzy.top/Article/details/gt2oaiesuse.html

Ruby: // 手写 Hash
来源：http://dali.tian-w.cn/Article/details/gt2ibyhfwvu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.vqdsnc.cn/Article/details/gt2ufnzrqag.html

[N08] 生成全排列
来源：http://dali.shuidangran.top/Article/details/gt2dewsshzs.html

Py:   itertools.permutations(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2yzppxpll.html

PHP:  // 手写递归交换
来源：http://dali.sweek.top/Article/details/gt2tpqwoidv.html

JS:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gt2qoscydib.html

TS:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gt2yqertglf.html

Java: // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gt2omlqexed.html

Go:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gt2zbiwcptj.html

Ruby: arr.permutation.to_a
来源：http://dali.chenlongwang.top/Article/details/gt2esagfspg.html

C#:   // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gt2hniqdldm.html

[N09] 栈与队列
来源：http://dali.xziqi.cn/Article/details/gt2izxkbhnf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.mhx1999.top/Article/details/gt2xtdsccxg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenlongwang.top/Article/details/gt2mjiyaebh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sxryk.cn/Article/details/gt2lalfwiuq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.tanke756.top/Article/details/gt2hadteodu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xinyue.icu/Article/details/gt2byslcril.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hammf.cn/Article/details/gt2clmcbbfw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.meibo888.top/Article/details/gt2nyhssxay.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sysykeji.top/Article/details/gt2hpdqxwre.html

[N10] 链表节点定义
来源：http://dali.haohaochexian.top/Article/details/gt2bkgklgkc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.nanxuanxn.top/Article/details/gt2jnxkvlic.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.guannengcc.top/Article/details/gt2zbblzyxe.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.guowangkeji.top/Article/details/gt2joestswq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.chenlongwang.top/Article/details/gt2bzmeaevw.html

Java: class Node { int v; Node next; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ncnautaf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yj202588.top/Article/details/gt2hourufkn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.feifeiyinyue.top/Article/details/gt2katnhgtq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.wangdashe.top/Article/details/gt2ngwzpvlm.html

[N11] 二叉树中序遍历
来源：http://dali.shangyingyoupin.top/Article/details/gt2lhyuynmp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.iojbl.cn/Article/details/gt2ookzxrlk.html

PHP:  // 手写递归函数
来源：http://dali.sufxvd.cn/Article/details/gt2gaviozyk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258888.top/Article/details/gt2cuavapgo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gaohongyu789.top/Article/details/gt2kyriltmn.html

Java: // 手写递归
来源：http://dali.cdnleiting.top/Article/details/gt2xxtjhsgy.html

Go:   // 手写递归
来源：http://dali.ybcxt.top/Article/details/gt2kozabxdo.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shangyingyoupin.top/Article/details/gt2oqqoegqf.html

C#:   // 手写递归
来源：http://dali.zhixingplan.top/Article/details/gt2ztrlfgeh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hysaishi.cn/Article/details/gt2pummdwle.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cashguo.top/Article/details/gt2euctugoz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hywenlv.cn/Article/details/gt2yutpplbi.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hnqzz.top/Article/details/gt2gfafbbav.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aizwys.cn/Article/details/gt2lrjfihbt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shangyingyoupin.top/Article/details/gt2qwlszyof.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yvedp.cn/Article/details/gt2hhsyonni.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hnqzz.top/Article/details/gt2lderwmyv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gaohongyu789.top/Article/details/gt2kulgmjui.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2vrkkoxmo.html

O. 并发与异步
来源：http://dali.zdqjudy.top/Article/details/gt2uxswjeoo.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2yubhtalp.html

[O01] 启动一个线程
来源：http://dali.vqdsnc.cn/Article/details/gt2pdtggmrr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.aizwys.cn/Article/details/gt2xzdibjhl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.bjfxy.top/Article/details/gt2vqphpnjx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinqigufen.top/Article/details/gt2aihwskhb.html

TS:   // 同 JS
来源：http://dali.svipenyu.cn/Article/details/gt2wemwgwjl.html

Java: new Thread(() -> f()).start()
来源：http://dali.jqgufenzy.top/Article/details/gt2xbmjarwt.html

Go:   go f()
来源：http://dali.kuanghao11.cn/Article/details/gt2hfjuvysv.html

Ruby: Thread.new { f }
来源：http://dali.pycfn.com/Article/details/gt2gpcydkfa.html

C#:   Task.Run(() => F());
来源：http://dali.hnqzz.top/Article/details/gt2hgdwrigw.html

[O02] 使用线程池
来源：http://dali.yj202588.top/Article/details/gt2bmeybkev.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2evyhxyrd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.9152youxi.cn/Article/details/gt2rusjrlck.html

JS:   // worker_threads 线程池
来源：http://dali.guowangkeji.top/Article/details/gt2itoublyf.html

TS:   // worker_threads 线程池
来源：http://dali.hfpthk.cn/Article/details/gt2wnsdnwzz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zdqjudy.top/Article/details/gt2vkpmrvae.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.andypj.xyz/Article/details/gt2wvrkeyqe.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cqqwz.cn/Article/details/gt2mhuolmtc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ppjwa.cn/Article/details/gt2skkxazhb.html

[O03] 加锁保护共享数据
来源：http://dali.nanxinkj.top/Article/details/gt2dchvuxge.html

Py:   with lock: shared += 1
来源：http://dali.havefunace.top/Article/details/gt2fqqfdjoz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhoulong.xyz/Article/details/gt2oyaxfjbp.html


<!-- 参考信息 -->