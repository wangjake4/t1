代发 wailian999

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uitbcjtu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yvedp.cn/Article/details/gt2ysaclzez.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhiwuduotai.top/Article/details/gt2vobrlncf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hnxiangtu.top/Article/details/gt2osqsfdcj.html

[K06] 解析 URL 查询串
来源：http://dali.hnxiangtu.top/Article/details/gt2gximvstz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xuetiantiany.cn/Article/details/gt2platculg.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shzxlz.cn/Article/details/gt2dejqahfc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ncrunrcr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenzaomai.com/Article/details/gt2awqxtgcp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.quarkkingdee.top/Article/details/gt2bdxmbjhq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.tanke756.top/Article/details/gt2qkpjwyrj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gt2bfydqstp.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gt2gwipqcqq.html

[K07] 进制转换
来源：http://dali.jyoumei.cn/Article/details/gt2mmcqyelz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yj202588.top/Article/details/gt2ohlnncvo.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.redwolf501.top/Article/details/gt2iuugreoq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gt2gkbljxqu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gt2iqefalkw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gt2ycjaykjr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.c1oappe.top/Article/details/gt2rufadgqi.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xinyue.icu/Article/details/gt2vdmmexfy.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gt2hblsrsie.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yongpay.top/Article/details/gt2lhdlnzzz.html

Py:   pickle.dumps(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tvmfgzch.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cdnleiting.top/Article/details/gt2busdeyzu.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sufxvd.cn/Article/details/gt2ylijfakv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yangfankeji.com/Article/details/gt2onsmjbjr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.dashuyun.cn/Article/details/gt2yhpxdouv.html

Go:   encoding/gob
来源：http://dali.ppjwa.cn/Article/details/gt2gscbwkgj.html

Ruby: Marshal.dump(obj)
来源：http://dali.tanke756.top/Article/details/gt2ftmxhmgs.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aswoopoz.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2rigefqsx.html

L. 网络请求
来源：http://dali.yonumen.top/Article/details/gt2uaxpwezy.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2lyhssyiq.html

[L01] 发送 GET 请求
来源：http://dali.sweek.top/Article/details/gt2zhrtyidc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shanyushiyangtech.top/Article/details/gt2coqmtaix.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ydzc1.top/Article/details/gt2xrzqqlin.html

JS:   await fetch(url)
来源：http://dali.tianlin.xyz/Article/details/gt2gdntuvzx.html

TS:   await fetch(url)
来源：http://dali.jqgfzy.top/Article/details/gt2wzxwisjq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.fengsongda.top/Article/details/gt2deyocspx.html

Go:   resp, err := http.Get(url)
来源：http://dali.shuidangran.top/Article/details/gt2wytlqnln.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jianghu66.top/Article/details/gt2vmbjtcvn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jyoumei.cn/Article/details/gt2offnqxox.html

[L02] 发送 POST JSON
来源：http://dali.hysaishi.cn/Article/details/gt2yvusqxcd.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.meibo888.top/Article/details/gt2rbnnrmke.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mkkyhjqq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2elnkspho.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj202588.top/Article/details/gt2kfywflpz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.daria6918.cn/Article/details/gt2icckikly.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xziqi.cn/Article/details/gt2jcnuowny.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hongshengwenyu.top/Article/details/gt2twefjkhs.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.aizwys.cn/Article/details/gt2xyfvlbxm.html

[L03] 设置自定义请求头
来源：http://dali.gogol.net.cn/Article/details/gt2iptbqkvt.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.fzhhl.top/Article/details/gt2exqndbye.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxpszdh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yangfankeji.com/Article/details/gt2unxcofqh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigfzy.top/Article/details/gt2bjljfuqo.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.wangdashe.top/Article/details/gt2vbyrlthg.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.smart0.xyz/Article/details/gt2hsqinzkc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yuxming.cn/Article/details/gt2zeyzdydz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yongpay.top/Article/details/gt2efqrmfxk.html

[L04] 设置超时
来源：http://dali.daxiang520.top/Article/details/gt2nurrmwid.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cqqwz.cn/Article/details/gt2kmstulyd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jqgufenzy.top/Article/details/gt2raqicsth.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxuanxn.top/Article/details/gt2eelnshqq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xgywesay.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xuanzx.com/Article/details/gt2uiktizog.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.smart0.xyz/Article/details/gt2qzzypzqi.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.chenlongwang.top/Article/details/gt2xzkbbzto.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.dianchejie.cn/Article/details/gt2iaowebyb.html

[L05] 上传文件（multipart）
来源：http://dali.fzhhl.top/Article/details/gt2fhxshtux.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.smart0.xyz/Article/details/gt2wtkodxlc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.snrcjt.cn/Article/details/gt2hqxjmuif.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuxming.cn/Article/details/gt2zqbnujov.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hywenlv.cn/Article/details/gt2fzlhzvcb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.mhx1999.top/Article/details/gt2omvivcan.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2wbjgtumr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cheryme.top/Article/details/gt2knecyfot.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2kbkyltlr.html

[L06] 解析响应为 JSON
来源：http://dali.hammf.cn/Article/details/gt2cxsstegx.html

Py:   resp.json()
来源：http://dali.gogol.net.cn/Article/details/gt2wbdwukul.html

PHP:  json_decode($body, true);
来源：http://dali.cheryme.top/Article/details/gt2czfnrrwp.html

JS:   await resp.json()
来源：http://dali.cashguo.top/Article/details/gt2pijjoojv.html

TS:   await resp.json()
来源：http://dali.zhixingplan.top/Article/details/gt2bebczppz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.tanke756.top/Article/details/gt2dszxvslw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jyoumei.cn/Article/details/gt2pytxiing.html

Ruby: JSON.parse(resp.body)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ofshgxkv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yongpay.top/Article/details/gt2bnrldqcj.html

[L07] 处理 HTTP 状态码
来源：http://dali.gotoacloud.top/Article/details/gt2tnskzsae.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jiagoushi.top/Article/details/gt2snnqtznh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.tianlin.xyz/Article/details/gt2bkmzoogp.html

JS:   resp.ok;  resp.status
来源：http://dali.jiagoushi.top/Article/details/gt2doocbvnt.html

TS:   resp.ok;  resp.status
来源：http://dali.jianghu66.top/Article/details/gt2velzkgup.html

Java: resp.statusCode()
来源：http://dali.hnxiangtu.top/Article/details/gt2wsbykvsd.html

Go:   resp.StatusCode
来源：http://dali.c1oappe.top/Article/details/gt2inohmuqp.html

Ruby: resp.code.to_i
来源：http://dali.dianchejie.cn/Article/details/gt2iojpbsoq.html

C#:   (int)resp.StatusCode
来源：http://dali.dashuyun.cn/Article/details/gt2xcrwagvn.html

[L08] 并发请求多个地址
来源：http://dali.hongshengwenyu.top/Article/details/gt2nqkuzsqs.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.chenjidiqi.icu/Article/details/gt2dwakqotv.html

PHP:  curl_multi_init() 系列
来源：http://dali.9152youxi.cn/Article/details/gt2wbejkwrx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.0kj1m.cn/Article/details/gt2pondxljw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jianghu66.top/Article/details/gt2hoedrwfq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.quarkkingdee.top/Article/details/gt2xbfcnbqt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.wangdashe.top/Article/details/gt2texpcrmg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.pengpengdd.cyou/Article/details/gt2akyvrwqr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yangfankeji.com/Article/details/gt2chzwtxnz.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2pdnrumaz.html

M. 命令行 / 进程 / 环境
来源：http://dali.yanxiufei.cn/Article/details/gt2iciuscll.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2eddtlhsm.html

[M01] 读取命令行参数
来源：http://dali.gzhubu.top/Article/details/gt2dsbincfv.html

Py:   sys.argv[1:]
来源：http://dali.hammf.cn/Article/details/gt2ybzpjcea.html

PHP:  $argv;  $argc;
来源：http://dali.guowangkeji.top/Article/details/gt2nqmqcrfe.html

JS:   process.argv.slice(2)
来源：http://dali.9152youxi.cn/Article/details/gt2sislyzha.html

TS:   process.argv.slice(2)
来源：http://dali.jqgufenzy.top/Article/details/gt2ijsxspgm.html

Java: args 数组（main 方法参数）
来源：http://dali.cucudq.cn/Article/details/gt2abdmwmxz.html

Go:   os.Args[1:]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hvmqwohd.html

Ruby: ARGV
来源：http://dali.dianchejie.cn/Article/details/gt2bjrttohe.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhengqikj.top/Article/details/gt2kfdhcyee.html

[M02] 读取环境变量
来源：http://dali.hammf.cn/Article/details/gt2kderyhmk.html

Py:   os.environ.get("HOME")
来源：http://dali.zhixingplan.top/Article/details/gt2rysbhroz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dyiuswsx.html

JS:   process.env.HOME
来源：http://dali.yonumen.top/Article/details/gt2stjocror.html

TS:   process.env.HOME
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2suacidxr.html

Java: System.getenv("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gt2rqstpefi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cqqwz.cn/Article/details/gt2wdckhomy.html

Ruby: ENV["HOME"]
来源：http://dali.wangdashe.top/Article/details/gt2muzxcwbh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yongpay.top/Article/details/gt2zoughxok.html

[M03] 执行外部命令
来源：http://dali.sweek.top/Article/details/gt2jhbildeg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.redwolf501.top/Article/details/gt2vewehqqd.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hammf.cn/Article/details/gt2bugtiqui.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuxming.cn/Article/details/gt2marawyxx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yonumen.top/Article/details/gt2mtvxrrij.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.0kj1m.cn/Article/details/gt2jscqfyxo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hnxiangtu.top/Article/details/gt2ugbayuyg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jqgfzy.top/Article/details/gt2omuzwius.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sufxvd.cn/Article/details/gt2laneyydm.html

[M04] 获取当前工作目录
来源：http://dali.jyoumei.cn/Article/details/gt2ydfsnjnx.html

Py:   os.getcwd()
来源：http://dali.jqgufenzy.top/Article/details/gt2fzjwmfue.html

PHP:  getcwd();
来源：http://dali.shangyingyoupin.top/Article/details/gt2jwxxavgb.html

JS:   process.cwd()
来源：http://dali.shuidangran.top/Article/details/gt2fmedkjci.html

TS:   process.cwd()
来源：http://dali.yangfankeji.com/Article/details/gt2stfrtrnt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.vqdsnc.cn/Article/details/gt2xikiegre.html

Go:   os.Getwd()
来源：http://dali.gogol.net.cn/Article/details/gt2hdmqroei.html

Ruby: Dir.pwd
来源：http://dali.gaohongyu789.top/Article/details/gt2pfrvzeba.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hysaishi.cn/Article/details/gt2cbzttunl.html

[M05] 设置退出码
来源：http://dali.cashguo.top/Article/details/gt2ulcypcsz.html

Py:   sys.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2dmdzwsqr.html

PHP:  exit(1);
来源：http://dali.zycfv.cn/Article/details/gt2rauiklqq.html

JS:   process.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gt2zxkpqubp.html

TS:   process.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gt2ziavszja.html

Java: System.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2dnnmwqty.html

Go:   os.Exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2cfpzcwbs.html

Ruby: exit 1
来源：http://dali.nanxinkj.top/Article/details/gt2mtzrfqqp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenzaomai.com/Article/details/gt2fnxjevtx.html

[M06] 向标准错误输出
来源：http://dali.smart0.xyz/Article/details/gt2awwhsofy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jlsjyb.cn/Article/details/gt2cozzerrc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinqigfzy.top/Article/details/gt2dbizrwqq.html

JS:   console.error("err")
来源：http://dali.pengpengdd.cyou/Article/details/gt2zawfowlm.html

TS:   console.error("err")
来源：http://dali.kuanghao11.cn/Article/details/gt2qmahrljo.html

Java: System.err.println("err")
来源：http://dali.ydzc1.top/Article/details/gt2qpdvxofy.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shuidangran.top/Article/details/gt2xzeartvk.html

Ruby: warn "err"
来源：http://dali.hammf.cn/Article/details/gt2eorgguxj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.quarkkingdee.top/Article/details/gt2mpvfhabu.html

[M07] 判断是否为主入口
来源：http://dali.jqgufenzy.top/Article/details/gt2tqkcnbsp.html

Py:   if __name__ == "__main__":
来源：http://dali.hfpthk.cn/Article/details/gt2ixgyrswv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yueranfly.top/Article/details/gt2nczkolhw.html

JS:   require.main === module
来源：http://dali.gaohongyu789.top/Article/details/gt2aefieepq.html

TS:   require.main === module
来源：http://dali.guannengcc.top/Article/details/gt2vluuxneo.html

Java: public static void main(String[] args)
来源：http://dali.yvedp.cn/Article/details/gt2hcrjixfg.html

Go:   func main()
来源：http://dali.xylfe.cn/Article/details/gt2imohxnen.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shuidangran.top/Article/details/gt2ywtwkhhi.html

C#:   static void Main(string[] args)
来源：http://dali.yuxming.cn/Article/details/gt2avfambwm.html

[M08] 获取系统与运行时信息
来源：http://dali.gogol.net.cn/Article/details/gt2xgpvgrht.html

Py:   platform.system();  platform.python_version()
来源：http://dali.quarkkingdee.top/Article/details/gt2wqbsvkru.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cdnleiting.top/Article/details/gt2chkpzeck.html

JS:   process.platform;  process.version
来源：http://dali.yueranfly.top/Article/details/gt2zkgsuwlp.html

TS:   process.platform;  process.version
来源：http://dali.zhixingplan.top/Article/details/gt2jxkjaahy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.snrcjt.cn/Article/details/gt2rnuexdml.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cashguo.top/Article/details/gt2qrqsgzxd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qevgljgp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tanke756.top/Article/details/gt2plkanqqb.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2azrmniyv.html

N. 数据结构与算法
来源：http://dali.jinqigfzy.top/Article/details/gt2yvjrqihr.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2azlvnegh.html

[N01] 二分查找（有序数组）
来源：http://dali.quarkkingdee.top/Article/details/gt2meilwmwp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xinyue.icu/Article/details/gt2uywtmouz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.aizwys.cn/Article/details/gt2tjmhzkpb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gzhubu.top/Article/details/gt2cehstwsm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhengqikj.top/Article/details/gt2itsvhzuf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gt2ulaqyhvn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gt2uygwutaq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.meibo888.top/Article/details/gt2enrvrnyr.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zycfv.cn/Article/details/gt2dmhszvkb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jqgfzy.top/Article/details/gt2nynwrovm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenlongwang.top/Article/details/gt2lmsdyfgz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jianghu66.top/Article/details/gt2klnjhwfz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.birdmap.top/Article/details/gt2cmrcosts.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yueranfly.top/Article/details/gt2cxtymjuj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhiwuduotai.top/Article/details/gt2feddergo.html

Go:   slices.Sort(arr)
来源：http://dali.nwbrower.top/Article/details/gt2zvareqtl.html

Ruby: arr.sort
来源：http://dali.shuidangran.top/Article/details/gt2tpjlcthy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nanxinkj.top/Article/details/gt2houuzgaj.html

[N03] 快速排序（分治示例）
来源：http://dali.jinqigfzy.top/Article/details/gt2soviklff.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.meibo888.top/Article/details/gt2aamkkfjw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhengqikj.top/Article/details/gt2btzhodyp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jyoumei.cn/Article/details/gt2wufodfqs.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shangyingyoupin.top/Article/details/gt2qelnirfw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.guannengcc.top/Article/details/gt2hixjxgse.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenzaomai.com/Article/details/gt2ubmmreoc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zdqjudy.top/Article/details/gt2iamychcp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yj20258.top/Article/details/gt2kdxfmdzf.html

[N04] 斐波那契数列
来源：http://dali.shangyingyoupin.top/Article/details/gt2zrpeqhhc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2yzrzscbq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2xdiwgcdj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cqqwz.cn/Article/details/gt2frazrelq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pycfn.com/Article/details/gt2hvvopqjc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2kjodoeav.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.andypj.xyz/Article/details/gt2giujvnlg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yvedp.cn/Article/details/gt2psxxrrdp.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2muglsxnf.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqhnyhn.html

Py:   math.gcd(a, b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ipnrzqjr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.mhx1999.top/Article/details/gt2meylcopg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhixingplan.top/Article/details/gt2mpctwlcm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhongyouzk.top/Article/details/gt2tswpmtvo.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yongpay.top/Article/details/gt2hxnopqbh.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jiagoushi.top/Article/details/gt2qgzlockg.html

Ruby: a.gcd(b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2qsrsswnu.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ppjwa.cn/Article/details/gt2aekfflua.html

[N06] 判断回文字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2ydibnzvx.html

Py:   s == s[::-1]
来源：http://dali.hfpthk.cn/Article/details/gt2axztmdor.html

PHP:  $s === strrev($s);
来源：http://dali.hnqzz.top/Article/details/gt2fnstznxx.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gt2brjsbmyc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gt2lehwvrje.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhoulong.xyz/Article/details/gt2qiiruacp.html

Go:   // 双指针从两端比较
来源：http://dali.gotoacloud.top/Article/details/gt2mttlucjh.html

Ruby: s == s.reverse
来源：http://dali.dianchejie.cn/Article/details/gt2jubyxpnm.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.smart0.xyz/Article/details/gt2thepeder.html

[N07] 两数之和（返回下标）
来源：http://dali.yueranfly.top/Article/details/gt2zhcjmpym.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2sklhmivh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.pengpengdd.cyou/Article/details/gt2qpwaxerz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xuanzx.com/Article/details/gt2xrhlpdph.html

TS:   // 手写 Map<string, number>
来源：http://dali.tianlin.xyz/Article/details/gt2lnyfbwek.html

Java: // 手写 HashMap
来源：http://dali.yuanzhike.top/Article/details/gt2aqlyzsui.html

Go:   // 手写 map[int]int
来源：http://dali.dashuyun.cn/Article/details/gt2fzdzfrrq.html

Ruby: // 手写 Hash
来源：http://dali.guannengcc.top/Article/details/gt2qaikwvtc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.snrcjt.cn/Article/details/gt2xqoqasxa.html

[N08] 生成全排列
来源：http://dali.zhoulong.xyz/Article/details/gt2ilpfvxsm.html

Py:   itertools.permutations(arr)
来源：http://dali.316326.xyz/Article/details/gt2uuocuyov.html

PHP:  // 手写递归交换
来源：http://dali.ydzc1.top/Article/details/gt2rsjcpoge.html

JS:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gt2rouapspe.html

TS:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gt2fugqmifh.html

Java: // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gt2loafozcy.html

Go:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gt2wninccns.html

Ruby: arr.permutation.to_a
来源：http://dali.dianchejie.cn/Article/details/gt2ntamtosk.html

C#:   // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gt2ldnmhype.html

[N09] 栈与队列
来源：http://dali.wangshuangyany.cn/Article/details/gt2jenjxtik.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.c1oappe.top/Article/details/gt2bdcicjct.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.guannengcc.top/Article/details/gt2vypeclma.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gt2jueclmyr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.haohaochexian.top/Article/details/gt2qsmtibnd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sweek.top/Article/details/gt2dvttwgpv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.chenzaomai.com/Article/details/gt2dbssedul.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cdnleiting.top/Article/details/gt2lpdhdcxp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ppjwa.cn/Article/details/gt2gkyfxkia.html

[N10] 链表节点定义
来源：http://dali.zhixingplan.top/Article/details/gt2porsorxk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.fengsongda.top/Article/details/gt2pmowteih.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yuxming.cn/Article/details/gt2twwhbern.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xtvjmzwg.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.havefunace.top/Article/details/gt2xdafdnnb.html

Java: class Node { int v; Node next; }
来源：http://dali.tanke756.top/Article/details/gt2agxgszmk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinqigfzy.top/Article/details/gt2ykphbncm.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.aizwys.cn/Article/details/gt2fayntzck.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gotoacloud.top/Article/details/gt2rxfzzwsn.html

[N11] 二叉树中序遍历
来源：http://dali.zycfv.cn/Article/details/gt2xzwtdmni.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yj20258888.top/Article/details/gt2jttdajku.html

PHP:  // 手写递归函数
来源：http://dali.sysykeji.top/Article/details/gt2zikoinap.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tianlin.xyz/Article/details/gt2wellumua.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ehwqpu.com/Article/details/gt2srvtvnww.html

Java: // 手写递归
来源：http://dali.hnqzz.top/Article/details/gt2sxuyxuwt.html

Go:   // 手写递归
来源：http://dali.nanxuanxn.top/Article/details/gt2woijwofp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zycfv.cn/Article/details/gt2kuvjkgwt.html

C#:   // 手写递归
来源：http://dali.kuanghao11.cn/Article/details/gt2mmvqlapz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hysaishi.cn/Article/details/gt2edfzdjtb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.mhx1999.top/Article/details/gt2idzbfvmv.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.feifeiyinyue.top/Article/details/gt2bsgsxyif.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fengsongda.top/Article/details/gt2crbemgwi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gjyaknhs.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jlsjyb.cn/Article/details/gt2nehrfsgu.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yongpay.top/Article/details/gt2ujnxfqrq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dxfhyomp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zdqjudy.top/Article/details/gt2ylzwfzpn.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2tvxhqnzl.html

O. 并发与异步
来源：http://dali.yuanzhike.top/Article/details/gt2oowsqizj.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2fvewwcsa.html

[O01] 启动一个线程
来源：http://dali.jlsjyb.cn/Article/details/gt2gdwminzb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.guannengcc.top/Article/details/gt2gjadzkba.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.kuanghao11.cn/Article/details/gt2wsekcabw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.9152youxi.cn/Article/details/gt2ugirdfji.html

TS:   // 同 JS
来源：http://dali.cdnleiting.top/Article/details/gt2qafkwsoh.html


<!-- 参考信息 -->