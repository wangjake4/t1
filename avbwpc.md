代发 wailian999

Py:   copy.deepcopy(obj)
来源：http://dali.cashguo.top/Article/details/gt2sftfrnop.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xuetiantiany.cn/Article/details/gt2aoqptouu.html

JS:   structuredClone(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2cowlboav.html

TS:   structuredClone(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zxynqhfd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.aizwys.cn/Article/details/gt2pnznwtso.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yxcinezf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.tianlin.xyz/Article/details/gt2uqmkljrr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uwdozgfv.html

[K06] 解析 URL 查询串
来源：http://dali.jyoumei.cn/Article/details/gt2aiopvlux.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.redwolf501.top/Article/details/gt2igmsnfvz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nwbrower.top/Article/details/gt2szwjtghx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.mhx1999.top/Article/details/gt2kufrnmme.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.feifeiyinyue.top/Article/details/gt2qephzsnh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.chenzaomai.com/Article/details/gt2xtsytfpl.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sweek.top/Article/details/gt2lujrswgg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shuidangran.top/Article/details/gt2vbhzilvc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jzbfqvmi.html

[K07] 进制转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fsldcbgm.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gt2crrrsimz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sufxvd.cn/Article/details/gt2mctawmnj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ivvv.top/Article/details/gt2imxpxxas.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gt2hmgchemb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gt2jvgubnhn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ivvv.top/Article/details/gt2xbsdujlx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.tian-w.cn/Article/details/gt2usxkzzul.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gt2kzkbqfgo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sweek.top/Article/details/gt2bsxpagly.html

Py:   pickle.dumps(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2rodimdxq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xinyue.icu/Article/details/gt2sfinfhla.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.fzhhl.top/Article/details/gt2ahgheaer.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ehwqpu.com/Article/details/gt2qptabpcq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.316326.xyz/Article/details/gt2elbyowue.html

Go:   encoding/gob
来源：http://dali.yanxiufei.cn/Article/details/gt2krzgeree.html

Ruby: Marshal.dump(obj)
来源：http://dali.meibo888.top/Article/details/gt2ngaejwmh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yj20258888.top/Article/details/gt2khvztcsg.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2xaiwlubb.html

L. 网络请求
来源：http://dali.fzhhl.top/Article/details/gt2yiwrnrno.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2hifppahy.html

[L01] 发送 GET 请求
来源：http://dali.xuetiantiany.cn/Article/details/gt2ooqjedla.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jianghu66.top/Article/details/gt2gjpuucal.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.quarkkingdee.top/Article/details/gt2rxvexajx.html

JS:   await fetch(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2epnwbssd.html

TS:   await fetch(url)
来源：http://dali.0kj1m.cn/Article/details/gt2uhqgtste.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cucudq.cn/Article/details/gt2qjwliagp.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhiwuduotai.top/Article/details/gt2sxpcsyir.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hammf.cn/Article/details/gt2rjtehpua.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ppjwa.cn/Article/details/gt2kqmpghtf.html

[L02] 发送 POST JSON
来源：http://dali.smart0.xyz/Article/details/gt2vniyobwl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.feifeiyinyue.top/Article/details/gt2strfwxpw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinqigufen.top/Article/details/gt2tpfdxoyv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cashguo.top/Article/details/gt2wrxmedsb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.haohaochexian.top/Article/details/gt2oansdtxw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ivvv.top/Article/details/gt2gixomhvw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.smart0.xyz/Article/details/gt2napushns.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.pengpengdd.cyou/Article/details/gt2yipjnplr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2nkeqxndn.html

[L03] 设置自定义请求头
来源：http://dali.yj20258888.top/Article/details/gt2ntvkvwbb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.andypj.xyz/Article/details/gt2parxuenh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.havefunace.top/Article/details/gt2cmdkoneh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sysykeji.top/Article/details/gt2ogfywtbs.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zdqjudy.top/Article/details/gt2zqrxhwds.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hammf.cn/Article/details/gt2fzsanxqh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hnqzz.top/Article/details/gt2mvssypng.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ybcxt.top/Article/details/gt2ktufvwqu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gotoacloud.top/Article/details/gt2cbknbkrm.html

[L04] 设置超时
来源：http://dali.hongshengwenyu.top/Article/details/gt2sawqgxro.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jyoumei.cn/Article/details/gt2eqhqkzaf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2evsajfdp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daria6918.cn/Article/details/gt2lgrzofaz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigufen.top/Article/details/gt2igutqpcl.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.daria6918.cn/Article/details/gt2suimeqcr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2njnrixpb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hysaishi.cn/Article/details/gt2oxzyomgp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.c1oappe.top/Article/details/gt2jjkmttuz.html

[L05] 上传文件（multipart）
来源：http://dali.xinyue.icu/Article/details/gt2emspihkb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.smart0.xyz/Article/details/gt2nkhoqxes.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ydzc1.top/Article/details/gt2gorwfskv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shangyingyoupin.top/Article/details/gt2eafwaouv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnqzz.top/Article/details/gt2dteynlkm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yj20258.top/Article/details/gt2mbzuqdfp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ppjwa.cn/Article/details/gt2pgbwiuqt.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gogol.net.cn/Article/details/gt2lhcxtami.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2byhmdbav.html

[L06] 解析响应为 JSON
来源：http://dali.xziqi.cn/Article/details/gt2ufvdnjdn.html

Py:   resp.json()
来源：http://dali.yonumen.top/Article/details/gt2pfefydqp.html

PHP:  json_decode($body, true);
来源：http://dali.guowangkeji.top/Article/details/gt2ebagttlc.html

JS:   await resp.json()
来源：http://dali.snrcjt.cn/Article/details/gt2tcwyzafn.html

TS:   await resp.json()
来源：http://dali.yj20258888.top/Article/details/gt2ulddxacl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.meibo888.top/Article/details/gt2fsfwzixy.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hnqzz.top/Article/details/gt2bviiefnl.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tian-w.cn/Article/details/gt2sredovsv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shangyingyoupin.top/Article/details/gt2dqxluxvq.html

[L07] 处理 HTTP 状态码
来源：http://dali.redwolf501.top/Article/details/gt2ekizbssw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gogol.net.cn/Article/details/gt2ezmsybdw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ehwqpu.com/Article/details/gt2yyqedakb.html

JS:   resp.ok;  resp.status
来源：http://dali.ivvv.top/Article/details/gt2lxwlldus.html

TS:   resp.ok;  resp.status
来源：http://dali.nwbrower.top/Article/details/gt2tpajktdg.html

Java: resp.statusCode()
来源：http://dali.c1oappe.top/Article/details/gt2wtqzibod.html

Go:   resp.StatusCode
来源：http://dali.redwolf501.top/Article/details/gt2osipcozp.html

Ruby: resp.code.to_i
来源：http://dali.yj20258888.top/Article/details/gt2xqtyzczp.html

C#:   (int)resp.StatusCode
来源：http://dali.jiagoushi.top/Article/details/gt2bmzwobcv.html

[L08] 并发请求多个地址
来源：http://dali.cheryme.top/Article/details/gt2kymdxdxn.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.iojbl.cn/Article/details/gt2breoneem.html

PHP:  curl_multi_init() 系列
来源：http://dali.gzhubu.top/Article/details/gt2kmcjnjsw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ydzc1.top/Article/details/gt2gkkaycvj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shzxlz.cn/Article/details/gt2psdwdozt.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jqgufenzy.top/Article/details/gt2riopleqv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yonumen.top/Article/details/gt2cgtwphmt.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.wangdashe.top/Article/details/gt2hpomgcgo.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tanke756.top/Article/details/gt2tcjrbqic.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2rajjblzb.html

M. 命令行 / 进程 / 环境
来源：http://dali.dashuyun.cn/Article/details/gt2krygbqzg.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wkodqqti.html

[M01] 读取命令行参数
来源：http://dali.gogol.net.cn/Article/details/gt2oephmeqc.html

Py:   sys.argv[1:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ujurhsgh.html

PHP:  $argv;  $argc;
来源：http://dali.jinqigfzy.top/Article/details/gt2yzjxoyzk.html

JS:   process.argv.slice(2)
来源：http://dali.yueranfly.top/Article/details/gt2pztnidbb.html

TS:   process.argv.slice(2)
来源：http://dali.ivvv.top/Article/details/gt2yrdjcedx.html

Java: args 数组（main 方法参数）
来源：http://dali.chenlongwang.top/Article/details/gt2xodlogbh.html

Go:   os.Args[1:]
来源：http://dali.gzhubu.top/Article/details/gt2stjuwxkb.html

Ruby: ARGV
来源：http://dali.yuxming.cn/Article/details/gt2kfqxqpku.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xuetiantiany.cn/Article/details/gt2wcedrsya.html

[M02] 读取环境变量
来源：http://dali.ydzc1.top/Article/details/gt2oefrkcoy.html

Py:   os.environ.get("HOME")
来源：http://dali.nanxinkj.top/Article/details/gt2wupnbkvd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gzhubu.top/Article/details/gt2soerflbl.html

JS:   process.env.HOME
来源：http://dali.dashuyun.cn/Article/details/gt2ampimcdj.html

TS:   process.env.HOME
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ynfofcdy.html

Java: System.getenv("HOME")
来源：http://dali.shuidangran.top/Article/details/gt2swjbxhck.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hnqzz.top/Article/details/gt2grzxwcfm.html

Ruby: ENV["HOME"]
来源：http://dali.shangyingyoupin.top/Article/details/gt2raprmqiw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xuanzx.com/Article/details/gt2gwtjuoxk.html

[M03] 执行外部命令
来源：http://dali.zhiwuduotai.top/Article/details/gt2iusskuai.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hywenlv.cn/Article/details/gt2zskxcjmk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kismfonl.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gaohongyu789.top/Article/details/gt2pwkgwnag.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ydzc1.top/Article/details/gt2vdweovxz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cdnleiting.top/Article/details/gt2pihpztnq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.chenjidiqi.icu/Article/details/gt2kuiijtpe.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gotoacloud.top/Article/details/gt2ysppeobc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.chenjidiqi.icu/Article/details/gt2hdqwqiok.html

[M04] 获取当前工作目录
来源：http://dali.nwbrower.top/Article/details/gt2vhpiftoy.html

Py:   os.getcwd()
来源：http://dali.snrcjt.cn/Article/details/gt2ckjuhpgf.html

PHP:  getcwd();
来源：http://dali.gogol.net.cn/Article/details/gt2rsjlojvh.html

JS:   process.cwd()
来源：http://dali.cashguo.top/Article/details/gt2iexqgmuf.html

TS:   process.cwd()
来源：http://dali.smart0.xyz/Article/details/gt2nxclwcvu.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sxryk.cn/Article/details/gt2ubobriez.html

Go:   os.Getwd()
来源：http://dali.xuetiantiany.cn/Article/details/gt2mdoewwme.html

Ruby: Dir.pwd
来源：http://dali.dashuyun.cn/Article/details/gt2camycjvc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.dianchejie.cn/Article/details/gt2yliwlxkf.html

[M05] 设置退出码
来源：http://dali.xylfe.cn/Article/details/gt2hmizerel.html

Py:   sys.exit(1)
来源：http://dali.hnqzz.top/Article/details/gt2lkdnrmqo.html

PHP:  exit(1);
来源：http://dali.nanxinkj.top/Article/details/gt2idsgwqzd.html

JS:   process.exit(1)
来源：http://dali.yj202588.top/Article/details/gt2yrreriff.html

TS:   process.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2rmkfeoli.html

Java: System.exit(1)
来源：http://dali.cheryme.top/Article/details/gt2oinrjtmh.html

Go:   os.Exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2obnsvnxt.html

Ruby: exit 1
来源：http://dali.vqdsnc.cn/Article/details/gt2jcjdvigq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shuidangran.top/Article/details/gt2fdztaxpq.html

[M06] 向标准错误输出
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pszdtxju.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yongpay.top/Article/details/gt2pqomyxke.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gaohongyu789.top/Article/details/gt2wpprlxlq.html

JS:   console.error("err")
来源：http://dali.vqdsnc.cn/Article/details/gt2gppkafyq.html

TS:   console.error("err")
来源：http://dali.xylfe.cn/Article/details/gt2lcsaoeak.html

Java: System.err.println("err")
来源：http://dali.iojbl.cn/Article/details/gt2xjvydqbx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ewkelpqy.html

Ruby: warn "err"
来源：http://dali.cheryme.top/Article/details/gt2umjtgenb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhoulong.xyz/Article/details/gt2ndsyuekc.html

[M07] 判断是否为主入口
来源：http://dali.tianlin.xyz/Article/details/gt2listefvr.html

Py:   if __name__ == "__main__":
来源：http://dali.smart0.xyz/Article/details/gt2hiojtfai.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinqigfzy.top/Article/details/gt2cctjhquy.html

JS:   require.main === module
来源：http://dali.sysykeji.top/Article/details/gt2pvdqrcdn.html

TS:   require.main === module
来源：http://dali.hongshengwenyu.top/Article/details/gt2wreuibuq.html

Java: public static void main(String[] args)
来源：http://dali.pycfn.com/Article/details/gt2sirrnrej.html

Go:   func main()
来源：http://dali.ydzc1.top/Article/details/gt2ombcosdv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hywenlv.cn/Article/details/gt2npmjisqq.html

C#:   static void Main(string[] args)
来源：http://dali.shzxlz.cn/Article/details/gt2cbhpkwxr.html

[M08] 获取系统与运行时信息
来源：http://dali.sysykeji.top/Article/details/gt2wbhvsmyo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cdnleiting.top/Article/details/gt2ppsfayns.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hywenlv.cn/Article/details/gt2utvylquc.html

JS:   process.platform;  process.version
来源：http://dali.wangshuangyany.cn/Article/details/gt2esrvxqla.html

TS:   process.platform;  process.version
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2htynezsh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yanxiufei.cn/Article/details/gt2royppqic.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.dianchejie.cn/Article/details/gt2piupxfje.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinqigufen.top/Article/details/gt2kvqkymko.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zdqjudy.top/Article/details/gt2jfoffhvs.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2tkxvaoqu.html

N. 数据结构与算法
来源：http://dali.zhiwuduotai.top/Article/details/gt2jhmqkuvu.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2jdrebbwo.html

[N01] 二分查找（有序数组）
来源：http://dali.daria6918.cn/Article/details/gt2xiimvtzd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gt2umbpuvml.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yueranfly.top/Article/details/gt2qswgcmdx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fzhhl.top/Article/details/gt2oqwbldun.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jianghu66.top/Article/details/gt2bgyazinm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2huhjgvhp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xziqi.cn/Article/details/gt2jbpomjof.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj20258888.top/Article/details/gt2bddoipcq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gt2yqbyhnpg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ehwqpu.com/Article/details/gt2uxqhozqo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuanzx.com/Article/details/gt2qtedvewp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2znxqfvke.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tanke756.top/Article/details/gt2hpuvuxdg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sweek.top/Article/details/gt2eqlatfbx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinqigufen.top/Article/details/gt2bmispnac.html

Go:   slices.Sort(arr)
来源：http://dali.cucudq.cn/Article/details/gt2smqhciic.html

Ruby: arr.sort
来源：http://dali.hammf.cn/Article/details/gt2befpnrwr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hnxiangtu.top/Article/details/gt2wbpllgnu.html

[N03] 快速排序（分治示例）
来源：http://dali.ydzc1.top/Article/details/gt2jdlodvts.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.guannengcc.top/Article/details/gt2uolofylj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.iojbl.cn/Article/details/gt2vquhizym.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fntvekzv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cheryme.top/Article/details/gt2dblowqik.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yongpay.top/Article/details/gt2nsagtote.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhiwuduotai.top/Article/details/gt2zlurqtxr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.nanxuanxn.top/Article/details/gt2qnibzdxl.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xuetiantiany.cn/Article/details/gt2krwxsqxf.html

[N04] 斐波那契数列
来源：http://dali.havefunace.top/Article/details/gt2bvejnsbt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.guowangkeji.top/Article/details/gt2fibqjvke.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.chenlongwang.top/Article/details/gt2tcmhuvrc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.svipenyu.cn/Article/details/gt2nyqoiskc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhoulong.xyz/Article/details/gt2njushtwm.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hysaishi.cn/Article/details/gt2uvxkkrjz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yueranfly.top/Article/details/gt2pxckssvz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hysaishi.cn/Article/details/gt2vvdmdivr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhongyouzk.top/Article/details/gt2oerzvswx.html

[N05] 最大公约数
来源：http://dali.sxryk.cn/Article/details/gt2bfgcwbfw.html

Py:   math.gcd(a, b)
来源：http://dali.ppjwa.cn/Article/details/gt2cqusshyp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jiagoushi.top/Article/details/gt2lxqucwcs.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wscuodru.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenlongwang.top/Article/details/gt2ofwjelor.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.snrcjt.cn/Article/details/gt2wdfzyjlc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.havefunace.top/Article/details/gt2riytsiss.html

Ruby: a.gcd(b)
来源：http://dali.zhoulong.xyz/Article/details/gt2plvikhnp.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jiagoushi.top/Article/details/gt2hmrgyzyx.html

[N06] 判断回文字符串
来源：http://dali.smart0.xyz/Article/details/gt2igitcyyp.html

Py:   s == s[::-1]
来源：http://dali.vqdsnc.cn/Article/details/gt2makwbjka.html

PHP:  $s === strrev($s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2epzhsixj.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gt2rzcrflem.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gt2udwsmxiv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shzxlz.cn/Article/details/gt2lifuhvpy.html

Go:   // 双指针从两端比较
来源：http://dali.9152youxi.cn/Article/details/gt2nerdnaww.html

Ruby: s == s.reverse
来源：http://dali.zhixingplan.top/Article/details/gt2mkrtbbvn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gogol.net.cn/Article/details/gt2qyofewzy.html

[N07] 两数之和（返回下标）
来源：http://dali.tianlin.xyz/Article/details/gt2vhcyauvu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.birdmap.top/Article/details/gt2yqfynkjt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhoulong.xyz/Article/details/gt2ixniwqpd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.9152youxi.cn/Article/details/gt2dujbzkdf.html

TS:   // 手写 Map<string, number>
来源：http://dali.sufxvd.cn/Article/details/gt2wqkxxtsf.html

Java: // 手写 HashMap
来源：http://dali.xylfe.cn/Article/details/gt2lidmqtxo.html

Go:   // 手写 map[int]int
来源：http://dali.wangdashe.top/Article/details/gt2bbhmizra.html

Ruby: // 手写 Hash
来源：http://dali.tanke756.top/Article/details/gt2yytmwvcx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yueranfly.top/Article/details/gt2axbzzkxf.html

[N08] 生成全排列
来源：http://dali.jqgfzy.top/Article/details/gt2acnpsvde.html

Py:   itertools.permutations(arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2dfwjnwdm.html

PHP:  // 手写递归交换
来源：http://dali.cashguo.top/Article/details/gt2xwxnchnl.html

JS:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gt2oyioxljq.html

TS:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gt2oknzdfaa.html

Java: // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gt2xjnjwgxv.html

Go:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gt2kutdarix.html

Ruby: arr.permutation.to_a
来源：http://dali.yongpay.top/Article/details/gt2mqkwuivo.html

C#:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gt2cxtgqtyc.html

[N09] 栈与队列
来源：http://dali.zycfv.cn/Article/details/gt2ykizwakj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gzhubu.top/Article/details/gt2idkigbip.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.iojbl.cn/Article/details/gt2kbfbwtqr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gzhubu.top/Article/details/gt2mjezxvpq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xinyue.icu/Article/details/gt2wgtthkue.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yuxming.cn/Article/details/gt2sdebaxce.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.wangshuangyany.cn/Article/details/gt2oseorrzr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.vqdsnc.cn/Article/details/gt2nlqfkhcr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jiagoushi.top/Article/details/gt2szbvvtqg.html

[N10] 链表节点定义
来源：http://dali.cqqwz.cn/Article/details/gt2gkzkmndh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cucudq.cn/Article/details/gt2lbvthayw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yvedp.cn/Article/details/gt2luekivie.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ybcxt.top/Article/details/gt2eofppmyn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xylfe.cn/Article/details/gt2hsiajkku.html

Java: class Node { int v; Node next; }
来源：http://dali.hnxiangtu.top/Article/details/gt2kscwnfni.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hysaishi.cn/Article/details/gt2ekmlcufp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ybcxt.top/Article/details/gt2cxfsaopd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cheryme.top/Article/details/gt2lfwslxqs.html

[N11] 二叉树中序遍历
来源：http://dali.chenjidiqi.icu/Article/details/gt2loalaiol.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sxrkepqh.html

PHP:  // 手写递归函数
来源：http://dali.yuxming.cn/Article/details/gt2bammseqt.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.meibo888.top/Article/details/gt2leleufas.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zycfv.cn/Article/details/gt2vzstdmzd.html

Java: // 手写递归
来源：http://dali.yuxming.cn/Article/details/gt2tqnichyv.html

Go:   // 手写递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qujueian.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.smart0.xyz/Article/details/gt2rirdwrkb.html

C#:   // 手写递归
来源：http://dali.meibo888.top/Article/details/gt2aflpssvo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jqgfzy.top/Article/details/gt2dktyilmj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.guowangkeji.top/Article/details/gt2yufdgmsm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.redwolf501.top/Article/details/gt2ydbjvboo.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dashuyun.cn/Article/details/gt2xyrodvpu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wrpfxldc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shuidangran.top/Article/details/gt2lnhukalf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hywenlv.cn/Article/details/gt2zggpmwcy.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hysaishi.cn/Article/details/gt2tqyckmdb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigufen.top/Article/details/gt2dspzduyi.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2ztfotwet.html

O. 并发与异步
来源：http://dali.sweek.top/Article/details/gt2qhghvuor.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2svybyfdz.html

[O01] 启动一个线程
来源：http://dali.hfpthk.cn/Article/details/gt2cygehlmi.html


<!-- 参考信息 -->