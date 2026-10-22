代发 wailian999

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jiagoushi.top/Article/details/gtlsdhhitr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.chenzaomai.com/Article/details/gtyfcuyeft.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gtgnngdeqk.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gtmarozryf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhixingplan.top/Article/details/gtmhdgtnvf.html

[K07] 进制转换
来源：http://dali.haohaochexian.top/Article/details/gtasunrvjo.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gtqvfjsnjv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hnqzz.top/Article/details/gtjnacgxoq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gtsbqxmtqr.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtujwghnfb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtwlscuxtg.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.daria6918.cn/Article/details/gtjqueaoll.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cheryme.top/Article/details/gtoqlpfhsp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtbhppyzfv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gtmceojnsv.html

Py:   pickle.dumps(obj)
来源：http://dali.hnqzz.top/Article/details/gtbtlvmpsd.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.mhx1999.top/Article/details/gtlyliwpvd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zycfv.cn/Article/details/gtdodyrdlv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.svipenyu.cn/Article/details/gtybkbdsvd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.snrcjt.cn/Article/details/gtaylsmhco.html

Go:   encoding/gob
来源：http://dali.xziqi.cn/Article/details/gtokcekzgx.html

Ruby: Marshal.dump(obj)
来源：http://dali.zdqjudy.top/Article/details/gttfhpwmzs.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cdnleiting.top/Article/details/gtbbrkyzfg.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtwsijshcq.html

L. 网络请求
来源：http://dali.cheryme.top/Article/details/gtmpbhcqja.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtoawgjjtz.html

[L01] 发送 GET 请求
来源：http://dali.sxryk.cn/Article/details/gtqxcbhnmi.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhixingplan.top/Article/details/gtttsskvjh.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yvedp.cn/Article/details/gtnjhlmetj.html

JS:   await fetch(url)
来源：http://dali.nwbrower.top/Article/details/gtnhabkqnc.html

TS:   await fetch(url)
来源：http://dali.jianghu66.top/Article/details/gtlqfegdio.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.guannengcc.top/Article/details/gthgsxexov.html

Go:   resp, err := http.Get(url)
来源：http://dali.ybcxt.top/Article/details/gtdmvrgkbm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.pengpengdd.cyou/Article/details/gtcrkkpmjt.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shangyingyoupin.top/Article/details/gtabjmynpd.html

[L02] 发送 POST JSON
来源：http://dali.hysaishi.cn/Article/details/gtruipugrl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.tanke756.top/Article/details/gtwweuszkm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.chenzaomai.com/Article/details/gtbijlidek.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.redwolf501.top/Article/details/gtzuhjlscf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangshuangyany.cn/Article/details/gtharujsxb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hnxiangtu.top/Article/details/gtvquwmhwc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yvedp.cn/Article/details/gtyzikrhyu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsmvicesp.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hywenlv.cn/Article/details/gtaufwsulb.html

[L03] 设置自定义请求头
来源：http://dali.nanxuanxn.top/Article/details/gtnsxxnixx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.tian-w.cn/Article/details/gtoxiutfvo.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.bjfxy.top/Article/details/gtppniuxno.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj202588.top/Article/details/gthxxalbht.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sufxvd.cn/Article/details/gtujkxordz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yonumen.top/Article/details/gtomvqsqgc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.iojbl.cn/Article/details/gtydljtjun.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.fzhhl.top/Article/details/gtmscqjbvf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ydzc1.top/Article/details/gtkxnfqtwk.html

[L04] 设置超时
来源：http://dali.zhixingplan.top/Article/details/gtfzkdqtcj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yongpay.top/Article/details/gtespammvv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenjidiqi.icu/Article/details/gtdpukaqkq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aizwys.cn/Article/details/gtyznyutnq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.quarkkingdee.top/Article/details/gtyanrpvhs.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ivvv.top/Article/details/gtcmfkoalv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.aizwys.cn/Article/details/gtyveocmey.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.chenzaomai.com/Article/details/gtnicyoyac.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yuanzhike.top/Article/details/gtjgwbgjbb.html

[L05] 上传文件（multipart）
来源：http://dali.iojbl.cn/Article/details/gtffuxpfwq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gaohongyu789.top/Article/details/gtkutuebur.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhoulong.xyz/Article/details/gtdyhidtgh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinghuilouyu.cn/Article/details/gtdstyebbh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.aibaodan.cn/Article/details/gtcawpydcr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yvedp.cn/Article/details/gtussaryyh.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.chenjidiqi.icu/Article/details/gtioerzltw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cqqwz.cn/Article/details/gtboqesyft.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtwspzunef.html

[L06] 解析响应为 JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gtslgbwpsq.html

Py:   resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gtvpoinowr.html

PHP:  json_decode($body, true);
来源：http://dali.316326.xyz/Article/details/gtezpfzgrl.html

JS:   await resp.json()
来源：http://dali.mhx1999.top/Article/details/gtijgfsnlf.html

TS:   await resp.json()
来源：http://dali.316326.xyz/Article/details/gtbghxshcs.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xinyue.icu/Article/details/gtunhuvgku.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sweek.top/Article/details/gthzhvenkw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xinyue.icu/Article/details/gtoychpvbi.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nwbrower.top/Article/details/gtmdmtbtpt.html

[L07] 处理 HTTP 状态码
来源：http://dali.andypj.xyz/Article/details/gtnnkuobvl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nwbrower.top/Article/details/gtbtnwcjyg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenjidiqi.icu/Article/details/gtnldpwena.html

JS:   resp.ok;  resp.status
来源：http://dali.shuidangran.top/Article/details/gtaxytoppr.html

TS:   resp.ok;  resp.status
来源：http://dali.hongshengwenyu.top/Article/details/gtylbybszl.html

Java: resp.statusCode()
来源：http://dali.cdnleiting.top/Article/details/gtxcepjcdo.html

Go:   resp.StatusCode
来源：http://dali.yueranfly.top/Article/details/gtbtrslago.html

Ruby: resp.code.to_i
来源：http://dali.nanxinkj.top/Article/details/gtrizgsovq.html

C#:   (int)resp.StatusCode
来源：http://dali.sxryk.cn/Article/details/gtqnjnzgcd.html

[L08] 并发请求多个地址
来源：http://dali.jinqigfzy.top/Article/details/gtfrtfricq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yongpay.top/Article/details/gtqlvxrtnn.html

PHP:  curl_multi_init() 系列
来源：http://dali.gogol.net.cn/Article/details/gtxybkujwo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ivvv.top/Article/details/gthvtwtxgs.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fzhhl.top/Article/details/gtanfjpgun.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cashguo.top/Article/details/gtptnefiab.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.316326.xyz/Article/details/gtpspkbzhd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.aizwys.cn/Article/details/gtihxsnhyi.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gtabnotyuk.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtaqwdmutf.html

M. 命令行 / 进程 / 环境
来源：http://dali.9152youxi.cn/Article/details/gtrptcfmmk.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtuauvslme.html

[M01] 读取命令行参数
来源：http://dali.nanxuanxn.top/Article/details/gtctbaudmw.html

Py:   sys.argv[1:]
来源：http://dali.daxiang520.top/Article/details/gtvzhdysgc.html

PHP:  $argv;  $argc;
来源：http://dali.zhoulong.xyz/Article/details/gtrvnpqtwx.html

JS:   process.argv.slice(2)
来源：http://dali.shzxlz.cn/Article/details/gtlqgfpnqh.html

TS:   process.argv.slice(2)
来源：http://dali.pengpengdd.cyou/Article/details/gtsfdwipks.html

Java: args 数组（main 方法参数）
来源：http://dali.gzhubu.top/Article/details/gtinfoecvy.html

Go:   os.Args[1:]
来源：http://dali.yonumen.top/Article/details/gtqdswdhwe.html

Ruby: ARGV
来源：http://dali.haohaochexian.top/Article/details/gttusyuvog.html

C#:   args 数组（Main 方法参数）
来源：http://dali.daria6918.cn/Article/details/gtfburwbcz.html

[M02] 读取环境变量
来源：http://dali.yj20258.top/Article/details/gtdfvpzwgk.html

Py:   os.environ.get("HOME")
来源：http://dali.snrcjt.cn/Article/details/gtttcczyvs.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jlsjyb.cn/Article/details/gtyidowtxv.html

JS:   process.env.HOME
来源：http://dali.yonumen.top/Article/details/gtconmrtiy.html

TS:   process.env.HOME
来源：http://dali.vqdsnc.cn/Article/details/gtwyzkulfd.html

Java: System.getenv("HOME")
来源：http://dali.cdnleiting.top/Article/details/gtydykyuel.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ivvv.top/Article/details/gtbbpekhkm.html

Ruby: ENV["HOME"]
来源：http://dali.jinqigfzy.top/Article/details/gtfnrqburo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gtwxojwckv.html

[M03] 执行外部命令
来源：http://dali.zhoulong.xyz/Article/details/gtfusynccb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.9152youxi.cn/Article/details/gtsqksaqiu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinqigufen.top/Article/details/gtppcqbjxr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhoulong.xyz/Article/details/gtpalpwisx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.dianchejie.cn/Article/details/gtjjxzrorm.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.svipenyu.cn/Article/details/gthxdlqqbu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.chenlongwang.top/Article/details/gthvwriqzf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ivvv.top/Article/details/gthdxttlaf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jqgufenzy.top/Article/details/gtzxoszgtw.html

[M04] 获取当前工作目录
来源：http://dali.chenlongwang.top/Article/details/gtkfeejibv.html

Py:   os.getcwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqefrbobm.html

PHP:  getcwd();
来源：http://dali.xinyue.icu/Article/details/gtcitqkqxh.html

JS:   process.cwd()
来源：http://dali.sufxvd.cn/Article/details/gtfdciqcjx.html

TS:   process.cwd()
来源：http://dali.havefunace.top/Article/details/gtuxvlqnbf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hfpthk.cn/Article/details/gtmrcyrcyw.html

Go:   os.Getwd()
来源：http://dali.gotoacloud.top/Article/details/gtjqezudzf.html

Ruby: Dir.pwd
来源：http://dali.chenjidiqi.icu/Article/details/gtrzlwcbwe.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.wangshuangyany.cn/Article/details/gtddbrtdqj.html

[M05] 设置退出码
来源：http://dali.yj20258.top/Article/details/gtbfiutsai.html

Py:   sys.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtguyjeovd.html

PHP:  exit(1);
来源：http://dali.fzhhl.top/Article/details/gthhqwtlai.html

JS:   process.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtdorzjdza.html

TS:   process.exit(1)
来源：http://dali.mhx1999.top/Article/details/gtvgeslwra.html

Java: System.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtnaztoteh.html

Go:   os.Exit(1)
来源：http://dali.daxiang520.top/Article/details/gtjaljymby.html

Ruby: exit 1
来源：http://dali.bjfxy.top/Article/details/gtparzxghm.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hfpthk.cn/Article/details/gtqconatay.html

[M06] 向标准错误输出
来源：http://dali.chenzaomai.com/Article/details/gtaktjnhmd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvpevktug.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cashguo.top/Article/details/gthlrehomn.html

JS:   console.error("err")
来源：http://dali.haohaochexian.top/Article/details/gtfudgjwyz.html

TS:   console.error("err")
来源：http://dali.cqqwz.cn/Article/details/gtknhfczqg.html

Java: System.err.println("err")
来源：http://dali.yonumen.top/Article/details/gthdmdyaqw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthsvgywxs.html

Ruby: warn "err"
来源：http://dali.redwolf501.top/Article/details/gtfmpcaiad.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tianlin.xyz/Article/details/gtffkuodjq.html

[M07] 判断是否为主入口
来源：http://dali.hysaishi.cn/Article/details/gtdckrvoux.html

Py:   if __name__ == "__main__":
来源：http://dali.yonumen.top/Article/details/gtsbekmfdb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zycfv.cn/Article/details/gtqtmzyymo.html

JS:   require.main === module
来源：http://dali.hysaishi.cn/Article/details/gtdfgesagl.html

TS:   require.main === module
来源：http://dali.jianghu66.top/Article/details/gtiuxhewoo.html

Java: public static void main(String[] args)
来源：http://dali.daxiang520.top/Article/details/gtajjjzfqa.html

Go:   func main()
来源：http://dali.smart0.xyz/Article/details/gtuxbufbrv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.c1oappe.top/Article/details/gtbjkktavl.html

C#:   static void Main(string[] args)
来源：http://dali.pengpengdd.cyou/Article/details/gtlpdjnrpe.html

[M08] 获取系统与运行时信息
来源：http://dali.c1oappe.top/Article/details/gtlmqanika.html

Py:   platform.system();  platform.python_version()
来源：http://dali.feifeiyinyue.top/Article/details/gtznipysci.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shuidangran.top/Article/details/gtfqpsybaw.html

JS:   process.platform;  process.version
来源：http://dali.yj202588.top/Article/details/gtigdtiiib.html

TS:   process.platform;  process.version
来源：http://dali.ivvv.top/Article/details/gtiqlhlpyx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yangfankeji.com/Article/details/gtdnbcxmbk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hysaishi.cn/Article/details/gtqlslgjuq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.guannengcc.top/Article/details/gtghirgkgp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.mhx1999.top/Article/details/gtpnxgpmoc.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtzmdriuyt.html

N. 数据结构与算法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtspfqaqbo.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtknjjvdgm.html

[N01] 二分查找（有序数组）
来源：http://dali.chenzaomai.com/Article/details/gtxyexibqu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnjgafqoz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.guowangkeji.top/Article/details/gtgcurevrs.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigufen.top/Article/details/gtrmvcbwwx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tian-w.cn/Article/details/gttpkqwgst.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtndmjpwnn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gtrwnhmtvv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xinyue.icu/Article/details/gtebeqdffg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yj20258.top/Article/details/gtdpjbaglp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xuetiantiany.cn/Article/details/gtlkuzmdfh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.havefunace.top/Article/details/gtpjxvyiiq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nwbrower.top/Article/details/gtlkduflep.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daxiang520.top/Article/details/gtdkcgebqc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gogol.net.cn/Article/details/gtgoxzqgyk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yueranfly.top/Article/details/gtfjteekze.html

Go:   slices.Sort(arr)
来源：http://dali.pycfn.com/Article/details/gtnvhggvvj.html

Ruby: arr.sort
来源：http://dali.ivvv.top/Article/details/gtimpqqoup.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cheryme.top/Article/details/gtywvwbxrg.html

[N03] 快速排序（分治示例）
来源：http://dali.zhengqikj.top/Article/details/gtjsbavbbx.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.daria6918.cn/Article/details/gttqtmclpx.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cqqwz.cn/Article/details/gtxoucorha.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.9152youxi.cn/Article/details/gtuhkxwwcz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jianghu66.top/Article/details/gtxwdfeznb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.mhx1999.top/Article/details/gtlwthfruq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhixingplan.top/Article/details/gtopgvchfm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yueranfly.top/Article/details/gtscrwvull.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrtfqqxse.html

[N04] 斐波那契数列
来源：http://dali.aizwys.cn/Article/details/gtqhyredud.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhengqikj.top/Article/details/gtotdgeowt.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jianghu66.top/Article/details/gtmwxqwqgw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sxryk.cn/Article/details/gtbbwdfayl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gotoacloud.top/Article/details/gtghuuxnuy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hongshengwenyu.top/Article/details/gtzrppvnrk.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.svipenyu.cn/Article/details/gtgegctrpd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jyoumei.cn/Article/details/gtdcsytmfm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hammf.cn/Article/details/gtvgueoiip.html

[N05] 最大公约数
来源：http://dali.yvedp.cn/Article/details/gtspdbuwhy.html

Py:   math.gcd(a, b)
来源：http://dali.9152youxi.cn/Article/details/gtxoccpkqq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hnxiangtu.top/Article/details/gtljkbwtyn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.316326.xyz/Article/details/gtanuinqvm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gtgexuzakc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shuidangran.top/Article/details/gtdknoybup.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.feifeiyinyue.top/Article/details/gtbhtcpnby.html

Ruby: a.gcd(b)
来源：http://dali.nwbrower.top/Article/details/gthoppqiia.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhengqikj.top/Article/details/gtdxnebjhy.html

[N06] 判断回文字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtpibcopfb.html

Py:   s == s[::-1]
来源：http://dali.c1oappe.top/Article/details/gtczyrgxvr.html

PHP:  $s === strrev($s);
来源：http://dali.mhx1999.top/Article/details/gtqoewcsdf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gtsftyqygo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtmbfhcenb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xziqi.cn/Article/details/gtwrnpluvt.html

Go:   // 双指针从两端比较
来源：http://dali.hysaishi.cn/Article/details/gtjwtqvblr.html

Ruby: s == s.reverse
来源：http://dali.yonumen.top/Article/details/gtxxjcehpv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jlsjyb.cn/Article/details/gtxgqikvbt.html

[N07] 两数之和（返回下标）
来源：http://dali.0kj1m.cn/Article/details/gtwrxsozzq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xziqi.cn/Article/details/gthuvauoqj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jiagoushi.top/Article/details/gtmhickpkr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.snrcjt.cn/Article/details/gtkqqpcocz.html

TS:   // 手写 Map<string, number>
来源：http://dali.jinqigfzy.top/Article/details/gtrkvlbrgz.html

Java: // 手写 HashMap
来源：http://dali.iojbl.cn/Article/details/gthoycvpyk.html

Go:   // 手写 map[int]int
来源：http://dali.guowangkeji.top/Article/details/gtpbqfgkte.html

Ruby: // 手写 Hash
来源：http://dali.nanxuanxn.top/Article/details/gthbusbxqy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yueranfly.top/Article/details/gtvzsmnlyn.html

[N08] 生成全排列
来源：http://dali.nwbrower.top/Article/details/gtilyobkrn.html

Py:   itertools.permutations(arr)
来源：http://dali.sysykeji.top/Article/details/gtgkmftsql.html

PHP:  // 手写递归交换
来源：http://dali.aizwys.cn/Article/details/gtzsuurmoj.html

JS:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gtymhubcje.html

TS:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gtztfcsurg.html

Java: // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtoanqvssp.html

Go:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gtduypbylm.html

Ruby: arr.permutation.to_a
来源：http://dali.meibo888.top/Article/details/gtvogdnsqd.html

C#:   // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gtvccijjtt.html

[N09] 栈与队列
来源：http://dali.gzhubu.top/Article/details/gtwklxrzkx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zycfv.cn/Article/details/gtnsicaral.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnmitocqh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.bjfxy.top/Article/details/gtogtsohhb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.mhx1999.top/Article/details/gtvxarasjb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cucudq.cn/Article/details/gtifcphyvh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jqgfzy.top/Article/details/gtwwnzqalv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nwbrower.top/Article/details/gtpgiflann.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.fzhhl.top/Article/details/gtpskdvmcu.html

[N10] 链表节点定义
来源：http://dali.sxryk.cn/Article/details/gtlqjhtqye.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hongshengwenyu.top/Article/details/gtkcfotzlk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvuoalnpb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ydzc1.top/Article/details/gtjbrlbngp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yj20258.top/Article/details/gtbipnrhlf.html

Java: class Node { int v; Node next; }
来源：http://dali.wangdashe.top/Article/details/gtdycpblpc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jqgfzy.top/Article/details/gtqkupuhub.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gogol.net.cn/Article/details/gtcxccwgrd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinqigufen.top/Article/details/gtcojvagxh.html

[N11] 二叉树中序遍历
来源：http://dali.daxiang520.top/Article/details/gtiabshyop.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.daxiang520.top/Article/details/gtwyetwwvt.html

PHP:  // 手写递归函数
来源：http://dali.jianghu66.top/Article/details/gtoqbkmols.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.quarkkingdee.top/Article/details/gtqtgysgwk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tian-w.cn/Article/details/gtgjnmgbht.html

Java: // 手写递归
来源：http://dali.hongshengwenyu.top/Article/details/gtnqzvppec.html

Go:   // 手写递归
来源：http://dali.gaohongyu789.top/Article/details/gtbmotcajt.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.guowangkeji.top/Article/details/gtwhaihegy.html

C#:   // 手写递归
来源：http://dali.yueranfly.top/Article/details/gtbyunwcvt.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.tianlin.xyz/Article/details/gttrzloiai.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.bjfxy.top/Article/details/gtfstetsic.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ppjwa.cn/Article/details/gtmcawsacg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gogol.net.cn/Article/details/gtagugnthb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258888.top/Article/details/gtvdzbnvfe.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhixingplan.top/Article/details/gtcypixbpe.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sxryk.cn/Article/details/gtrmukbjxy.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cucudq.cn/Article/details/gtcbcenipv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258888.top/Article/details/gtrkblvlih.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtwvvpxzru.html

O. 并发与异步
来源：http://dali.zdqjudy.top/Article/details/gtxjksmjle.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtaaowykpn.html

[O01] 启动一个线程
来源：http://dali.ehwqpu.com/Article/details/gtapbhfxzl.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.c1oappe.top/Article/details/gtiuxjoeoi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.smart0.xyz/Article/details/gtonsmgfoz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinghuilouyu.cn/Article/details/gtluxmtles.html

TS:   // 同 JS
来源：http://dali.pycfn.com/Article/details/gtcgoyncti.html

Java: new Thread(() -> f()).start()
来源：http://dali.fzhhl.top/Article/details/gtfhvhuvli.html

Go:   go f()
来源：http://dali.andypj.xyz/Article/details/gtegtoankm.html

Ruby: Thread.new { f }
来源：http://dali.xuanzx.com/Article/details/gtdvcznhxn.html

C#:   Task.Run(() => F());
来源：http://dali.yj202588.top/Article/details/gtotkaoafs.html

[O02] 使用线程池
来源：http://dali.yonumen.top/Article/details/gtwmchbyww.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.sysykeji.top/Article/details/gtvytfazpp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.nwbrower.top/Article/details/gtsebjldvr.html

JS:   // worker_threads 线程池
来源：http://dali.gzhubu.top/Article/details/gtdkrfwnls.html


<!-- 参考信息 -->