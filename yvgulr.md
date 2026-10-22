代发 wailian999

[K06] 解析 URL 查询串
来源：http://dali.fzhhl.top/Article/details/gt2xsweetce.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.wangdashe.top/Article/details/gt2meakpxqz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jianghu66.top/Article/details/gt2txftqhaq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgfzy.top/Article/details/gt2fvybtrbv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuetiantiany.cn/Article/details/gt2qukxppcd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jyoumei.cn/Article/details/gt2ekdfmufr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.havefunace.top/Article/details/gt2eylawhtz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yanxiufei.cn/Article/details/gt2xavoeoun.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yueranfly.top/Article/details/gt2cehnqggd.html

[K07] 进制转换
来源：http://dali.fengsongda.top/Article/details/gt2uyqjftdv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gt2hahguchl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigufen.top/Article/details/gt2sgfroltm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pgklmzyu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gt2dzxizals.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gt2hkxhjkky.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ydzc1.top/Article/details/gt2conujbag.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.guowangkeji.top/Article/details/gt2ydjkmiye.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gt2epuwgfrf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sufxvd.cn/Article/details/gt2mhcbkzmd.html

Py:   pickle.dumps(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2mckrmczt.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gogol.net.cn/Article/details/gt2cjoilswd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yanxiufei.cn/Article/details/gt2xrdsepkg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sweek.top/Article/details/gt2tluwqnnd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj20258888.top/Article/details/gt2cfzserjr.html

Go:   encoding/gob
来源：http://dali.cucudq.cn/Article/details/gt2zhuecmtm.html

Ruby: Marshal.dump(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2jgleashl.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yueranfly.top/Article/details/gt2dbjguvhh.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2qlolpwdx.html

L. 网络请求
来源：http://dali.tanke756.top/Article/details/gt2mvavgiyi.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2ngaacpto.html

[L01] 发送 GET 请求
来源：http://dali.wangdashe.top/Article/details/gt2kduveyhm.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.tian-w.cn/Article/details/gt2samsrxfh.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.svipenyu.cn/Article/details/gt2eowxscaf.html

JS:   await fetch(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2twonlqlg.html

TS:   await fetch(url)
来源：http://dali.jiagoushi.top/Article/details/gt2dxjkaqib.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhongyouzk.top/Article/details/gt2sbpdstce.html

Go:   resp, err := http.Get(url)
来源：http://dali.xylfe.cn/Article/details/gt2azdmakwb.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.birdmap.top/Article/details/gt2pfhhuppw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xziqi.cn/Article/details/gt2njtzmqgv.html

[L02] 发送 POST JSON
来源：http://dali.ppjwa.cn/Article/details/gt2lqybuapj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.mhx1999.top/Article/details/gt2hktixowj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cqqwz.cn/Article/details/gt2zarvhgui.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dianchejie.cn/Article/details/gt2hffnnorb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shangyingyoupin.top/Article/details/gt2vchrqkhe.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.c1oappe.top/Article/details/gt2lwbxzqlc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhoulong.xyz/Article/details/gt2echptiad.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nwbrower.top/Article/details/gt2wrcmzmtu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yangfankeji.com/Article/details/gt2qhqcrlmb.html

[L03] 设置自定义请求头
来源：http://dali.cdnleiting.top/Article/details/gt2rkemqlpu.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gotoacloud.top/Article/details/gt2bmckbncp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xziqi.cn/Article/details/gt2rtomalwn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.birdmap.top/Article/details/gt2xcosmyig.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2kjxnbdue.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.vqdsnc.cn/Article/details/gt2sjfzmdyc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.svipenyu.cn/Article/details/gt2rbxrxitc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.aizwys.cn/Article/details/gt2sjqhozvs.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yanxiufei.cn/Article/details/gt2jkuazmio.html

[L04] 设置超时
来源：http://dali.mhx1999.top/Article/details/gt2lbykmjhr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.9152youxi.cn/Article/details/gt2mzlzldwl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yueranfly.top/Article/details/gt2qxeqyqow.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.kuanghao11.cn/Article/details/gt2mwidhbzd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangshuangyany.cn/Article/details/gt2fcdfrffl.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.feifeiyinyue.top/Article/details/gt2lexdyicx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oyguzchh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.tian-w.cn/Article/details/gt2xwptnfyl.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hfpthk.cn/Article/details/gt2hjzgljln.html

[L05] 上传文件（multipart）
来源：http://dali.shzxlz.cn/Article/details/gt2qqywwaoq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nanxinkj.top/Article/details/gt2aaxozxre.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.snrcjt.cn/Article/details/gt2lazjptst.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhoulong.xyz/Article/details/gt2wdzfaxva.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.pycfn.com/Article/details/gt2ptzxzmcq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sufxvd.cn/Article/details/gt2drbkbhzn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gogol.net.cn/Article/details/gt2jolsfcph.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ujhdnjtt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gt2kmbfdprg.html

[L06] 解析响应为 JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tmmprlrz.html

Py:   resp.json()
来源：http://dali.ppjwa.cn/Article/details/gt2ejbjrqrh.html

PHP:  json_decode($body, true);
来源：http://dali.guannengcc.top/Article/details/gt2xzeiunqb.html

JS:   await resp.json()
来源：http://dali.snrcjt.cn/Article/details/gt2awzngtkk.html

TS:   await resp.json()
来源：http://dali.zhongyouzk.top/Article/details/gt2aivdnmyx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenzaomai.com/Article/details/gt2qahxuaic.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwrrfrur.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tian-w.cn/Article/details/gt2fbdgeqjl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ohijmkua.html

[L07] 处理 HTTP 状态码
来源：http://dali.dianchejie.cn/Article/details/gt2tuocnovk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.redwolf501.top/Article/details/gt2vdpzcsiz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.haohaochexian.top/Article/details/gt2aeamksec.html

JS:   resp.ok;  resp.status
来源：http://dali.0kj1m.cn/Article/details/gt2lmdurxjf.html

TS:   resp.ok;  resp.status
来源：http://dali.wangdashe.top/Article/details/gt2wmdnmcni.html

Java: resp.statusCode()
来源：http://dali.sufxvd.cn/Article/details/gt2zrwnbtco.html

Go:   resp.StatusCode
来源：http://dali.jqgfzy.top/Article/details/gt2qrrfqedy.html

Ruby: resp.code.to_i
来源：http://dali.cqqwz.cn/Article/details/gt2jphkgdlr.html

C#:   (int)resp.StatusCode
来源：http://dali.316326.xyz/Article/details/gt2kkmehapc.html

[L08] 并发请求多个地址
来源：http://dali.svipenyu.cn/Article/details/gt2afbbpwii.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhixingplan.top/Article/details/gt2pozjmxqh.html

PHP:  curl_multi_init() 系列
来源：http://dali.ybcxt.top/Article/details/gt2seonmcgl.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cywyuhjz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cucudq.cn/Article/details/gt2fbxyzdre.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jlsjyb.cn/Article/details/gt2ibyykotr.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.wangdashe.top/Article/details/gt2manqcgre.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.wangdashe.top/Article/details/gt2uxqmzmjf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jqgfzy.top/Article/details/gt2jzwjsoju.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2thfnupoi.html

M. 命令行 / 进程 / 环境
来源：http://dali.jyoumei.cn/Article/details/gt2hdjyzpzq.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2sdpoghpe.html

[M01] 读取命令行参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2pkzettot.html

Py:   sys.argv[1:]
来源：http://dali.chenlongwang.top/Article/details/gt2skdlosdg.html

PHP:  $argv;  $argc;
来源：http://dali.9152youxi.cn/Article/details/gt2ixkulxff.html

JS:   process.argv.slice(2)
来源：http://dali.sxryk.cn/Article/details/gt2purgvgqt.html

TS:   process.argv.slice(2)
来源：http://dali.ppjwa.cn/Article/details/gt2afqdvbvw.html

Java: args 数组（main 方法参数）
来源：http://dali.bjfxy.top/Article/details/gt2zmijyrmp.html

Go:   os.Args[1:]
来源：http://dali.svipenyu.cn/Article/details/gt2emgqskyi.html

Ruby: ARGV
来源：http://dali.sweek.top/Article/details/gt2azwaqcyw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jyoumei.cn/Article/details/gt2etkrkiut.html

[M02] 读取环境变量
来源：http://dali.sxryk.cn/Article/details/gt2xfhxvpyk.html

Py:   os.environ.get("HOME")
来源：http://dali.ppjwa.cn/Article/details/gt2tqaoohno.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ximwdvje.html

JS:   process.env.HOME
来源：http://dali.mhx1999.top/Article/details/gt2jamqcxqk.html

TS:   process.env.HOME
来源：http://dali.hywenlv.cn/Article/details/gt2fiqteaaf.html

Java: System.getenv("HOME")
来源：http://dali.yongpay.top/Article/details/gt2avyjnwmo.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ehwqpu.com/Article/details/gt2udavpxjw.html

Ruby: ENV["HOME"]
来源：http://dali.chenjidiqi.icu/Article/details/gt2clhpqyov.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yuanzhike.top/Article/details/gt2ftoajpvr.html

[M03] 执行外部命令
来源：http://dali.yueranfly.top/Article/details/gt2cecczwoz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ybcxt.top/Article/details/gt2nckzpdui.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nanxinkj.top/Article/details/gt2grdknbbt.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ppjwa.cn/Article/details/gt2jjlkuzlu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yvedp.cn/Article/details/gt2ywxmzzhc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2mutkepum.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ehwqpu.com/Article/details/gt2vojflibd.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.wangshuangyany.cn/Article/details/gt2xpaxvzib.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gogol.net.cn/Article/details/gt2blfnnjvk.html

[M04] 获取当前工作目录
来源：http://dali.meibo888.top/Article/details/gt2evlvndgn.html

Py:   os.getcwd()
来源：http://dali.shuidangran.top/Article/details/gt2anpzquqs.html

PHP:  getcwd();
来源：http://dali.guannengcc.top/Article/details/gt2kgilbxxu.html

JS:   process.cwd()
来源：http://dali.bjfxy.top/Article/details/gt2tzorspjp.html

TS:   process.cwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zjeietcl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhixingplan.top/Article/details/gt2thzqovpt.html

Go:   os.Getwd()
来源：http://dali.cdnleiting.top/Article/details/gt2nweoeofx.html

Ruby: Dir.pwd
来源：http://dali.xuetiantiany.cn/Article/details/gt2ubvenczd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.9152youxi.cn/Article/details/gt2kqafcice.html

[M05] 设置退出码
来源：http://dali.cdnleiting.top/Article/details/gt2eacgvprv.html

Py:   sys.exit(1)
来源：http://dali.aizwys.cn/Article/details/gt2wuedohrk.html

PHP:  exit(1);
来源：http://dali.jianghu66.top/Article/details/gt2dkwvjwfq.html

JS:   process.exit(1)
来源：http://dali.pycfn.com/Article/details/gt2quhtiujs.html

TS:   process.exit(1)
来源：http://dali.daxiang520.top/Article/details/gt2tdsefhpi.html

Java: System.exit(1)
来源：http://dali.ivvv.top/Article/details/gt2djghohyt.html

Go:   os.Exit(1)
来源：http://dali.hfpthk.cn/Article/details/gt2ovppohaj.html

Ruby: exit 1
来源：http://dali.vqdsnc.cn/Article/details/gt2fkbktsgd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nanxuanxn.top/Article/details/gt2mduyuxxx.html

[M06] 向标准错误输出
来源：http://dali.yvedp.cn/Article/details/gt2acjmwkdh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xgmnzqio.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.dianchejie.cn/Article/details/gt2bdnhbzrl.html

JS:   console.error("err")
来源：http://dali.jiagoushi.top/Article/details/gt2dlrnjotf.html

TS:   console.error("err")
来源：http://dali.pycfn.com/Article/details/gt2ymumbrjz.html

Java: System.err.println("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kfugthio.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shuidangran.top/Article/details/gt2mlsqfdlv.html

Ruby: warn "err"
来源：http://dali.zycfv.cn/Article/details/gt2dxzcvxuu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.snrcjt.cn/Article/details/gt2yyekjoia.html

[M07] 判断是否为主入口
来源：http://dali.ydzc1.top/Article/details/gt2buchhpmd.html

Py:   if __name__ == "__main__":
来源：http://dali.dashuyun.cn/Article/details/gt2jjdivcly.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ydzc1.top/Article/details/gt2rgeywacx.html

JS:   require.main === module
来源：http://dali.cucudq.cn/Article/details/gt2otzvxjmy.html

TS:   require.main === module
来源：http://dali.jyoumei.cn/Article/details/gt2xnhjqhne.html

Java: public static void main(String[] args)
来源：http://dali.xziqi.cn/Article/details/gt2tvcffvsz.html

Go:   func main()
来源：http://dali.pycfn.com/Article/details/gt2rnbiizih.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shzxlz.cn/Article/details/gt2jaulttel.html

C#:   static void Main(string[] args)
来源：http://dali.andypj.xyz/Article/details/gt2qclobjtb.html

[M08] 获取系统与运行时信息
来源：http://dali.yvedp.cn/Article/details/gt2idzikerx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sysykeji.top/Article/details/gt2pjhmpgzb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.pycfn.com/Article/details/gt2dggwkjjn.html

JS:   process.platform;  process.version
来源：http://dali.shanyushiyangtech.top/Article/details/gt2smjoqvne.html

TS:   process.platform;  process.version
来源：http://dali.jqgfzy.top/Article/details/gt2szscfvmr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.c1oappe.top/Article/details/gt2binqapkf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinqigfzy.top/Article/details/gt2vtcciwad.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.andypj.xyz/Article/details/gt2arilmmfg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.redwolf501.top/Article/details/gt2pqkwwhks.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2xwqtxaev.html

N. 数据结构与算法
来源：http://dali.andypj.xyz/Article/details/gt2ojgrhhlh.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2oyjbkahs.html

[N01] 二分查找（有序数组）
来源：http://dali.zhiwuduotai.top/Article/details/gt2stynujvy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yuxming.cn/Article/details/gt2vjtkqpps.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.kuanghao11.cn/Article/details/gt2dtjjttyn.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cucudq.cn/Article/details/gt2vmsfhmkc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daxiang520.top/Article/details/gt2ggxjzrfw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.fzhhl.top/Article/details/gt2eczztdfm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yj20258888.top/Article/details/gt2zziwxhrj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.316326.xyz/Article/details/gt2eahuewzk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.tanke756.top/Article/details/gt2ojdnpvuk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hfpthk.cn/Article/details/gt2ymrpalde.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.kuanghao11.cn/Article/details/gt2kcfsbisp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yvedp.cn/Article/details/gt2gxopugzu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aibaodan.cn/Article/details/gt2xizedgnh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.havefunace.top/Article/details/gt2czyqlaor.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sxryk.cn/Article/details/gt2roczkcvd.html

Go:   slices.Sort(arr)
来源：http://dali.sxryk.cn/Article/details/gt2ydkztbmn.html

Ruby: arr.sort
来源：http://dali.yueranfly.top/Article/details/gt2fajchejz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhengqikj.top/Article/details/gt2uzepnoth.html

[N03] 快速排序（分治示例）
来源：http://dali.wangdashe.top/Article/details/gt2vstmdsif.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.smart0.xyz/Article/details/gt2ghrcwjpg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yuanzhike.top/Article/details/gt2vnhjbzlb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.iojbl.cn/Article/details/gt2dcbnwwwe.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj202588.top/Article/details/gt2ldpxehbz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gzhubu.top/Article/details/gt2oianuvmg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.andypj.xyz/Article/details/gt2hqwxqdsw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xylfe.cn/Article/details/gt2eqspaubz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xuanzx.com/Article/details/gt2mdthefww.html

[N04] 斐波那契数列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zqaffkmr.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sysykeji.top/Article/details/gt2zfwujizy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sysykeji.top/Article/details/gt2rwdnoilk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ybcxt.top/Article/details/gt2mcdlyppf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tian-w.cn/Article/details/gt2qevirght.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xziqi.cn/Article/details/gt2ynkmupdg.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hpsuehmq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hhwxceul.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.meibo888.top/Article/details/gt2ejalxsij.html

[N05] 最大公约数
来源：http://dali.andypj.xyz/Article/details/gt2kyndursw.html

Py:   math.gcd(a, b)
来源：http://dali.jinqigfzy.top/Article/details/gt2tuihtgvo.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ydzc1.top/Article/details/gt2iapshkyw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhongyouzk.top/Article/details/gt2wjysszoj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wugtjnbs.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yj20258888.top/Article/details/gt2idscsspu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.meibo888.top/Article/details/gt2fritvvpt.html

Ruby: a.gcd(b)
来源：http://dali.mhx1999.top/Article/details/gt2ngsryzsx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2mwsnuqgs.html

[N06] 判断回文字符串
来源：http://dali.gotoacloud.top/Article/details/gt2kyvdmlje.html

Py:   s == s[::-1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zhgwtaqy.html

PHP:  $s === strrev($s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2mbxafvle.html

JS:   s === [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gt2gzxkqhmx.html

TS:   s === [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gt2qhkzwxin.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.kuanghao11.cn/Article/details/gt2tlindelj.html

Go:   // 双指针从两端比较
来源：http://dali.zycfv.cn/Article/details/gt2bmwefuxq.html

Ruby: s == s.reverse
来源：http://dali.gogol.net.cn/Article/details/gt2wgteexut.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gogol.net.cn/Article/details/gt2oyjtlfeu.html

[N07] 两数之和（返回下标）
来源：http://dali.tian-w.cn/Article/details/gt2osfwynax.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhongyouzk.top/Article/details/gt2jhbtqckc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinqigfzy.top/Article/details/gt2jyaeunts.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.bjfxy.top/Article/details/gt2hrefrgzk.html

TS:   // 手写 Map<string, number>
来源：http://dali.xuanzx.com/Article/details/gt2uoilpzmx.html

Java: // 手写 HashMap
来源：http://dali.9152youxi.cn/Article/details/gt2swuuoypz.html

Go:   // 手写 map[int]int
来源：http://dali.zhoulong.xyz/Article/details/gt2ickjkpfd.html

Ruby: // 手写 Hash
来源：http://dali.smart0.xyz/Article/details/gt2dnynjzzf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.quarkkingdee.top/Article/details/gt2yhfawnuf.html

[N08] 生成全排列
来源：http://dali.andypj.xyz/Article/details/gt2watiezep.html

Py:   itertools.permutations(arr)
来源：http://dali.shuidangran.top/Article/details/gt2uwdynxwb.html

PHP:  // 手写递归交换
来源：http://dali.redwolf501.top/Article/details/gt2iijtijpt.html

JS:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gt2pmejfbih.html

TS:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gt2spweylra.html

Java: // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gt2nibwcihh.html

Go:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gt2uhguprqp.html

Ruby: arr.permutation.to_a
来源：http://dali.c1oappe.top/Article/details/gt2mrofxenk.html

C#:   // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gt2kywafswc.html

[N09] 栈与队列
来源：http://dali.daria6918.cn/Article/details/gt2sasujndp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mcubtrek.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gzhubu.top/Article/details/gt2pjufigrq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.mhx1999.top/Article/details/gt2luqdkbcx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jyoumei.cn/Article/details/gt2phlimmju.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yuanzhike.top/Article/details/gt2wrnynhcz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.aibaodan.cn/Article/details/gt2jgtavyqv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yj20258.top/Article/details/gt2tqnqshwd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.meibo888.top/Article/details/gt2unizrmkx.html

[N10] 链表节点定义
来源：http://dali.xinyue.icu/Article/details/gt2ehfullnv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.daria6918.cn/Article/details/gt2vgxltdnb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jiagoushi.top/Article/details/gt2nvvaayvr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xuanzx.com/Article/details/gt2jlbedrvu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.dianchejie.cn/Article/details/gt2mnhprija.html

Java: class Node { int v; Node next; }
来源：http://dali.yj202588.top/Article/details/gt2zewwmrpv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sufxvd.cn/Article/details/gt2zjobtjyj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.316326.xyz/Article/details/gt2hzqnjnlv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.nanxinkj.top/Article/details/gt2pwiixpod.html

[N11] 二叉树中序遍历
来源：http://dali.iojbl.cn/Article/details/gt2llxqhjug.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.chenlongwang.top/Article/details/gt2olzhrytc.html

PHP:  // 手写递归函数
来源：http://dali.meibo888.top/Article/details/gt2qtaeuidf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jyoumei.cn/Article/details/gt2cvcbaioq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ceuhwwba.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqjbbim.html

Go:   // 手写递归
来源：http://dali.yuanzhike.top/Article/details/gt2zxcqgzhw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhiwuduotai.top/Article/details/gt2nazpltyp.html

C#:   // 手写递归
来源：http://dali.jianghu66.top/Article/details/gt2pfzjljeq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jiagoushi.top/Article/details/gt2zwnqdpgh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.fengsongda.top/Article/details/gt2lfwqscmf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.chenjidiqi.icu/Article/details/gt2yeywoygs.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tanke756.top/Article/details/gt2xmxkmorq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zycfv.cn/Article/details/gt2jzyktkux.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hongshengwenyu.top/Article/details/gt2nsigntpv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yj202588.top/Article/details/gt2moshtnng.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hnxiangtu.top/Article/details/gt2arkungxi.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.dianchejie.cn/Article/details/gt2mdgiqfou.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2pgoefrle.html

O. 并发与异步
来源：http://dali.zycfv.cn/Article/details/gt2nooacjih.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2lomlsezf.html

[O01] 启动一个线程
来源：http://dali.dashuyun.cn/Article/details/gt2kpfuihjp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xuetiantiany.cn/Article/details/gt2jcrzcmog.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2biljieoa.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hywenlv.cn/Article/details/gt2zgheeckp.html

TS:   // 同 JS
来源：http://dali.gotoacloud.top/Article/details/gt2ibrjxfcn.html

Java: new Thread(() -> f()).start()
来源：http://dali.316326.xyz/Article/details/gt2wucdpekr.html

Go:   go f()
来源：http://dali.zhoulong.xyz/Article/details/gt2fhtxodoz.html

Ruby: Thread.new { f }
来源：http://dali.jlsjyb.cn/Article/details/gt2ofmepdwi.html

C#:   Task.Run(() => F());
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ketcesuq.html


<!-- 参考信息 -->