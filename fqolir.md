代发 wailian999

Py:   copy.deepcopy(obj)
来源：http://dali.cucudq.cn/Article/details/gt2hnysapfe.html

PHP:  unserialize(serialize($obj));
来源：http://dali.tianlin.xyz/Article/details/gt2uiwvxprq.html

JS:   structuredClone(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lgqlghyr.html

TS:   structuredClone(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2bcvvaeac.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yj20258888.top/Article/details/gt2phrqvwxg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.vqdsnc.cn/Article/details/gt2dzdpeuqk.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvtfyad.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.svipenyu.cn/Article/details/gt2ifquisgn.html

[K06] 解析 URL 查询串
来源：http://dali.yj20258.top/Article/details/gt2aaksraey.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.aizwys.cn/Article/details/gt2lribjdby.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ppjwa.cn/Article/details/gt2bfnnbmxr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.mhx1999.top/Article/details/gt2pvjjfsxr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shuidangran.top/Article/details/gt2wmawcnck.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yonumen.top/Article/details/gt2etuuyiuw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.mhx1999.top/Article/details/gt2ppgkvdeg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gt2fmxcfwrr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gaohongyu789.top/Article/details/gt2jpgopekg.html

[K07] 进制转换
来源：http://dali.zycfv.cn/Article/details/gt2ifdxxugn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lasfhask.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.0kj1m.cn/Article/details/gt2fedhbjxz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gt2svisixgz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gt2tkzkbcwr.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gt2yeuuygan.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.iojbl.cn/Article/details/gt2tqkmxxgg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cdnleiting.top/Article/details/gt2petpejoq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gt2xeibsmhn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sufxvd.cn/Article/details/gt2zvhzlcfx.html

Py:   pickle.dumps(obj)
来源：http://dali.xziqi.cn/Article/details/gt2uwytuxvk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yongpay.top/Article/details/gt2ogkjzqgh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.kuanghao11.cn/Article/details/gt2pgvafqwk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.wangshuangyany.cn/Article/details/gt2pxurbdcs.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cashguo.top/Article/details/gt2sysetext.html

Go:   encoding/gob
来源：http://dali.dianchejie.cn/Article/details/gt2slkoshvk.html

Ruby: Marshal.dump(obj)
来源：http://dali.zycfv.cn/Article/details/gt2xhqhjciv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinqigufen.top/Article/details/gt2qmodgeqi.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2ozkklxvi.html

L. 网络请求
来源：http://dali.hywenlv.cn/Article/details/gt2lvcbwfqx.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2isosgemg.html

[L01] 发送 GET 请求
来源：http://dali.sufxvd.cn/Article/details/gt2snywylzq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zmgunjav.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pamceauw.html

JS:   await fetch(url)
来源：http://dali.xylfe.cn/Article/details/gt2vytwlkkc.html

TS:   await fetch(url)
来源：http://dali.chenzaomai.com/Article/details/gt2aigtnpec.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.wangshuangyany.cn/Article/details/gt2fayadwrk.html

Go:   resp, err := http.Get(url)
来源：http://dali.yanxiufei.cn/Article/details/gt2qxkdpuss.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ybcxt.top/Article/details/gt2cjzjzygn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ehwqpu.com/Article/details/gt2hmxbjrjm.html

[L02] 发送 POST JSON
来源：http://dali.jlsjyb.cn/Article/details/gt2ujkcpxeo.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hnqzz.top/Article/details/gt2hejzcyqy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.pycfn.com/Article/details/gt2rkrngjsf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhoulong.xyz/Article/details/gt2lmpgsfjk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.snrcjt.cn/Article/details/gt2ryxyvjzx.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.smart0.xyz/Article/details/gt2ujtdjbdk.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yvedp.cn/Article/details/gt2cfutckko.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.meibo888.top/Article/details/gt2ypikyhyg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zqotvefy.html

[L03] 设置自定义请求头
来源：http://dali.zhongyouzk.top/Article/details/gt2ysoanxnz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2pdsifgdw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xylfe.cn/Article/details/gt2pnjqfcxa.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zdqjudy.top/Article/details/gt2gxutbdqq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xinyue.icu/Article/details/gt2rfcjsvtz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhoulong.xyz/Article/details/gt2fhpxuzph.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yonumen.top/Article/details/gt2wkesnlnc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cucudq.cn/Article/details/gt2kftotsdx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.havefunace.top/Article/details/gt2wyuqjkeh.html

[L04] 设置超时
来源：http://dali.svipenyu.cn/Article/details/gt2zfblwecs.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wfexovsc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lbwwvwuv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hywenlv.cn/Article/details/gt2mzvrgwre.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gotoacloud.top/Article/details/gt2pemnbquu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hnqzz.top/Article/details/gt2gsgwayhk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.guannengcc.top/Article/details/gt2jvwspfby.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yvedp.cn/Article/details/gt2eeyznuzq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.pengpengdd.cyou/Article/details/gt2mcvjiqmp.html

[L05] 上传文件（multipart）
来源：http://dali.tianlin.xyz/Article/details/gt2zxzizhaw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shangyingyoupin.top/Article/details/gt2feofkumo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.nanxuanxn.top/Article/details/gt2ohhfhnec.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.snrcjt.cn/Article/details/gt2xqfbrmel.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuanzhike.top/Article/details/gt2nrrtkgph.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yj20258888.top/Article/details/gt2gnhtpudp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sxryk.cn/Article/details/gt2fnltufjp.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hongshengwenyu.top/Article/details/gt2gbkimevs.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.9152youxi.cn/Article/details/gt2irzfurla.html

[L06] 解析响应为 JSON
来源：http://dali.zhiwuduotai.top/Article/details/gt2jwhaicpn.html

Py:   resp.json()
来源：http://dali.zhiwuduotai.top/Article/details/gt2mgbjccbc.html

PHP:  json_decode($body, true);
来源：http://dali.gzhubu.top/Article/details/gt2xjusekui.html

JS:   await resp.json()
来源：http://dali.daria6918.cn/Article/details/gt2eincbsgc.html

TS:   await resp.json()
来源：http://dali.quarkkingdee.top/Article/details/gt2idipuruo.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhiwuduotai.top/Article/details/gt2plcnhexz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.birdmap.top/Article/details/gt2qyjgztya.html

Ruby: JSON.parse(resp.body)
来源：http://dali.wangdashe.top/Article/details/gt2yzhygqxn.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2axcoclfh.html

[L07] 处理 HTTP 状态码
来源：http://dali.mhx1999.top/Article/details/gt2jzgvgxgq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yklfapdp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ppjwa.cn/Article/details/gt2zbwtdand.html

JS:   resp.ok;  resp.status
来源：http://dali.zhoulong.xyz/Article/details/gt2admwdahp.html

TS:   resp.ok;  resp.status
来源：http://dali.ppjwa.cn/Article/details/gt2zgtvnccn.html

Java: resp.statusCode()
来源：http://dali.hnqzz.top/Article/details/gt2iazaennk.html

Go:   resp.StatusCode
来源：http://dali.yuanzhike.top/Article/details/gt2zmymchny.html

Ruby: resp.code.to_i
来源：http://dali.gzhubu.top/Article/details/gt2jvfpczle.html

C#:   (int)resp.StatusCode
来源：http://dali.yuanzhike.top/Article/details/gt2zkamgaso.html

[L08] 并发请求多个地址
来源：http://dali.wangdashe.top/Article/details/gt2delidbne.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ydzc1.top/Article/details/gt2epbftthv.html

PHP:  curl_multi_init() 系列
来源：http://dali.xuetiantiany.cn/Article/details/gt2ilztvlbq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gogol.net.cn/Article/details/gt2xbbilcvv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ydzc1.top/Article/details/gt2rxrlmlid.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jiagoushi.top/Article/details/gt2jyqtpxze.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.birdmap.top/Article/details/gt2wmpxdagn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.chenzaomai.com/Article/details/gt2teixmret.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zycfv.cn/Article/details/gt2alskxteo.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2eoaghruh.html

M. 命令行 / 进程 / 环境
来源：http://dali.c1oappe.top/Article/details/gt2zdshobug.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2kwrmxgwb.html

[M01] 读取命令行参数
来源：http://dali.cheryme.top/Article/details/gt2pilpmmuk.html

Py:   sys.argv[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vwjolruq.html

PHP:  $argv;  $argc;
来源：http://dali.bjfxy.top/Article/details/gt2dmlqrtyd.html

JS:   process.argv.slice(2)
来源：http://dali.hnxiangtu.top/Article/details/gt2qassraxs.html

TS:   process.argv.slice(2)
来源：http://dali.cheryme.top/Article/details/gt2pvbpflay.html

Java: args 数组（main 方法参数）
来源：http://dali.meibo888.top/Article/details/gt2azqgbgir.html

Go:   os.Args[1:]
来源：http://dali.vqdsnc.cn/Article/details/gt2pjwwgaqq.html

Ruby: ARGV
来源：http://dali.sxryk.cn/Article/details/gt2dsnsdzsn.html

C#:   args 数组（Main 方法参数）
来源：http://dali.havefunace.top/Article/details/gt2dfrppzkc.html

[M02] 读取环境变量
来源：http://dali.chenlongwang.top/Article/details/gt2beyuxprd.html

Py:   os.environ.get("HOME")
来源：http://dali.mhx1999.top/Article/details/gt2vslouonp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.birdmap.top/Article/details/gt2bjgkkcqb.html

JS:   process.env.HOME
来源：http://dali.birdmap.top/Article/details/gt2cufvoknb.html

TS:   process.env.HOME
来源：http://dali.gaohongyu789.top/Article/details/gt2ddhekrek.html

Java: System.getenv("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2velhztdi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gt2egkfkjkj.html

Ruby: ENV["HOME"]
来源：http://dali.zycfv.cn/Article/details/gt2vnxxzpfw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gzhubu.top/Article/details/gt2hlaivyvz.html

[M03] 执行外部命令
来源：http://dali.tianlin.xyz/Article/details/gt2kjthrhta.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.andypj.xyz/Article/details/gt2loagdcht.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xinyue.icu/Article/details/gt2cyparcnj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.snrcjt.cn/Article/details/gt2vtokukvh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tian-w.cn/Article/details/gt2lhtfffjl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cucudq.cn/Article/details/gt2tlecckhp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhixingplan.top/Article/details/gt2fdfysvss.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ivvv.top/Article/details/gt2dlpocyyo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yj202588.top/Article/details/gt2jweplqof.html

[M04] 获取当前工作目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rxescxbe.html

Py:   os.getcwd()
来源：http://dali.feifeiyinyue.top/Article/details/gt2skqzgbxk.html

PHP:  getcwd();
来源：http://dali.gaohongyu789.top/Article/details/gt2pedrbbar.html

JS:   process.cwd()
来源：http://dali.xziqi.cn/Article/details/gt2qpfndsqi.html

TS:   process.cwd()
来源：http://dali.fzhhl.top/Article/details/gt2mfxodtof.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yongpay.top/Article/details/gt2pdimdatv.html

Go:   os.Getwd()
来源：http://dali.chenjidiqi.icu/Article/details/gt2vktxdsii.html

Ruby: Dir.pwd
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cxcjwfqm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinqigfzy.top/Article/details/gt2jghxhbtx.html

[M05] 设置退出码
来源：http://dali.xuetiantiany.cn/Article/details/gt2vcpyotnt.html

Py:   sys.exit(1)
来源：http://dali.ybcxt.top/Article/details/gt2dqnshysq.html

PHP:  exit(1);
来源：http://dali.0kj1m.cn/Article/details/gt2xzzrwpva.html

JS:   process.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gt2mqwcxhxg.html

TS:   process.exit(1)
来源：http://dali.aizwys.cn/Article/details/gt2mbqojotb.html

Java: System.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gt2qqyccnvi.html

Go:   os.Exit(1)
来源：http://dali.guowangkeji.top/Article/details/gt2brbgvkii.html

Ruby: exit 1
来源：http://dali.wangdashe.top/Article/details/gt2picqkjyd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.kuanghao11.cn/Article/details/gt2yvohnusg.html

[M06] 向标准错误输出
来源：http://dali.xuanzx.com/Article/details/gt2yyvxpoms.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jiagoushi.top/Article/details/gt2fgxoxqob.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.guowangkeji.top/Article/details/gt2beutusqz.html

JS:   console.error("err")
来源：http://dali.jiagoushi.top/Article/details/gt2ltrkxjvj.html

TS:   console.error("err")
来源：http://dali.aizwys.cn/Article/details/gt2tifzeott.html

Java: System.err.println("err")
来源：http://dali.yj20258.top/Article/details/gt2jcuwhouy.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2msdpcszi.html

Ruby: warn "err"
来源：http://dali.cdnleiting.top/Article/details/gt2tawdwxvi.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.c1oappe.top/Article/details/gt2lcmgnhop.html

[M07] 判断是否为主入口
来源：http://dali.xuetiantiany.cn/Article/details/gt2xhctchii.html

Py:   if __name__ == "__main__":
来源：http://dali.jlsjyb.cn/Article/details/gt2fmnycmwy.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xziqi.cn/Article/details/gt2qnlmerds.html

JS:   require.main === module
来源：http://dali.guannengcc.top/Article/details/gt2nliyiole.html

TS:   require.main === module
来源：http://dali.aizwys.cn/Article/details/gt2pwnibaeq.html

Java: public static void main(String[] args)
来源：http://dali.yj202588.top/Article/details/gt2dckebnax.html

Go:   func main()
来源：http://dali.dashuyun.cn/Article/details/gt2aitafnay.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hnqzz.top/Article/details/gt2bxjnlfhc.html

C#:   static void Main(string[] args)
来源：http://dali.gotoacloud.top/Article/details/gt2rtempsfb.html

[M08] 获取系统与运行时信息
来源：http://dali.0kj1m.cn/Article/details/gt2utkrgjxa.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sufxvd.cn/Article/details/gt2eunmraol.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jddehmeu.html

JS:   process.platform;  process.version
来源：http://dali.xuetiantiany.cn/Article/details/gt2erhfwyqb.html

TS:   process.platform;  process.version
来源：http://dali.sysykeji.top/Article/details/gt2ombghfei.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hywenlv.cn/Article/details/gt2xzwiqfvb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.fzhhl.top/Article/details/gt2yxosyqjf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gotoacloud.top/Article/details/gt2yylqnxsz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hammf.cn/Article/details/gt2vaxneets.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2zwywzdra.html

N. 数据结构与算法
来源：http://dali.zhiwuduotai.top/Article/details/gt2jideguku.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2yjjrsthi.html

[N01] 二分查找（有序数组）
来源：http://dali.hnqzz.top/Article/details/gt2qwumfpix.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gt2oepvdfjh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yj202588.top/Article/details/gt2ehvcxzaj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ehwqpu.com/Article/details/gt2ljoqfsju.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangdashe.top/Article/details/gt2mvixqeev.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gt2mqyvhwub.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yj202588.top/Article/details/gt2lxzqqgru.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kmenftep.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.pycfn.com/Article/details/gt2hqyyzzhl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yj20258.top/Article/details/gt2zobuuegq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pqiwdrej.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.kuanghao11.cn/Article/details/gt2eqjxzvnh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnxiangtu.top/Article/details/gt2iqykfnmd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cqqwz.cn/Article/details/gt2fpsppyte.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xylfe.cn/Article/details/gt2mrdslhzh.html

Go:   slices.Sort(arr)
来源：http://dali.sysykeji.top/Article/details/gt2cdccvzxk.html

Ruby: arr.sort
来源：http://dali.yj20258.top/Article/details/gt2vebskptl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.c1oappe.top/Article/details/gt2iwuigivl.html

[N03] 快速排序（分治示例）
来源：http://dali.tianlin.xyz/Article/details/gt2rscxavjk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.nanxinkj.top/Article/details/gt2jtavrnvu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.aizwys.cn/Article/details/gt2delgvfjk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.kuanghao11.cn/Article/details/gt2udjbwhvv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.vqdsnc.cn/Article/details/gt2viuxdzsr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yongpay.top/Article/details/gt2tszheoqn.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sxryk.cn/Article/details/gt2oerggvwk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yuanzhike.top/Article/details/gt2ykbusxcf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mqkhzqtn.html

[N04] 斐波那契数列
来源：http://dali.yonumen.top/Article/details/gt2ypzkogpb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.snrcjt.cn/Article/details/gt2pwkwcqrh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gogol.net.cn/Article/details/gt2kjdnyahy.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuxming.cn/Article/details/gt2cxcgxrwy.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.redwolf501.top/Article/details/gt2objwrfog.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.sweek.top/Article/details/gt2tihlzflg.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.dashuyun.cn/Article/details/gt2qwqxqdpg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.aibaodan.cn/Article/details/gt2vsfyoeox.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gt2flhidvob.html

[N05] 最大公约数
来源：http://dali.sweek.top/Article/details/gt2jzdgcevd.html

Py:   math.gcd(a, b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2kgzfczsn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.snrcjt.cn/Article/details/gt2hblhkorx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jianghu66.top/Article/details/gt2uoioodqd.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.quarkkingdee.top/Article/details/gt2tuolxafd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.daria6918.cn/Article/details/gt2sjyqefca.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sxryk.cn/Article/details/gt2rabclklr.html

Ruby: a.gcd(b)
来源：http://dali.hysaishi.cn/Article/details/gt2pcxzjmkm.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.bjfxy.top/Article/details/gt2sinyrifs.html

[N06] 判断回文字符串
来源：http://dali.smart0.xyz/Article/details/gt2dzxummif.html

Py:   s == s[::-1]
来源：http://dali.hysaishi.cn/Article/details/gt2oibtakrv.html

PHP:  $s === strrev($s);
来源：http://dali.gaohongyu789.top/Article/details/gt2cxeagevi.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hammf.cn/Article/details/gt2uwdaweba.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2opvvtecc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gotoacloud.top/Article/details/gt2pbwggalc.html

Go:   // 双指针从两端比较
来源：http://dali.fzhhl.top/Article/details/gt2khwiykkd.html

Ruby: s == s.reverse
来源：http://dali.jqgufenzy.top/Article/details/gt2itaugqwi.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hammf.cn/Article/details/gt2qsrwwmww.html

[N07] 两数之和（返回下标）
来源：http://dali.tianlin.xyz/Article/details/gt2qmlkibzv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.aibaodan.cn/Article/details/gt2ebqaglrx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.tian-w.cn/Article/details/gt2kqdpvyao.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.haohaochexian.top/Article/details/gt2biumjukz.html

TS:   // 手写 Map<string, number>
来源：http://dali.hnxiangtu.top/Article/details/gt2svnuvyqo.html

Java: // 手写 HashMap
来源：http://dali.jinqigufen.top/Article/details/gt2itnpuguv.html

Go:   // 手写 map[int]int
来源：http://dali.hysaishi.cn/Article/details/gt2bijwzqzy.html

Ruby: // 手写 Hash
来源：http://dali.sysykeji.top/Article/details/gt2dgwxnolu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.svipenyu.cn/Article/details/gt2jjeisbxf.html

[N08] 生成全排列
来源：http://dali.shuidangran.top/Article/details/gt2emfalxdy.html

Py:   itertools.permutations(arr)
来源：http://dali.meibo888.top/Article/details/gt2vvhurwaq.html

PHP:  // 手写递归交换
来源：http://dali.tianlin.xyz/Article/details/gt2samnhqbb.html

JS:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gt2ygdqmbqh.html

TS:   // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gt2nyxmspqf.html

Java: // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gt2jrwzgckb.html

Go:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gt2kqswmfgl.html

Ruby: arr.permutation.to_a
来源：http://dali.dianchejie.cn/Article/details/gt2qxhceezq.html

C#:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gt2yfsavrod.html

[N09] 栈与队列
来源：http://dali.chenjidiqi.icu/Article/details/gt2ifafrqms.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.snrcjt.cn/Article/details/gt2cipuzrsl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.pengpengdd.cyou/Article/details/gt2mzgjvlnv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nwbrower.top/Article/details/gt2awcmpqrg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xylfe.cn/Article/details/gt2purapjyz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sufxvd.cn/Article/details/gt2zqgcwnxd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hysaishi.cn/Article/details/gt2nhqjctoa.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2azfbkmbh.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.svipenyu.cn/Article/details/gt2anjdmbuq.html

[N10] 链表节点定义
来源：http://dali.xylfe.cn/Article/details/gt2tiibfonl.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.pycfn.com/Article/details/gt2cujvyyyn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yueranfly.top/Article/details/gt2haugteos.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yuxming.cn/Article/details/gt2kiufmdpl.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cashguo.top/Article/details/gt2dtunmyjn.html

Java: class Node { int v; Node next; }
来源：http://dali.zhengqikj.top/Article/details/gt2ovmjpjwv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shzxlz.cn/Article/details/gt2clsjxlkb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jqgufenzy.top/Article/details/gt2wbuyafkp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.havefunace.top/Article/details/gt2pspxuwzw.html

[N11] 二叉树中序遍历
来源：http://dali.pycfn.com/Article/details/gt2dtegwkaz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shangyingyoupin.top/Article/details/gt2jrotlibi.html

PHP:  // 手写递归函数
来源：http://dali.iojbl.cn/Article/details/gt2jnhuuijj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cdnleiting.top/Article/details/gt2ovaxtexa.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sxryk.cn/Article/details/gt2opndtngq.html

Java: // 手写递归
来源：http://dali.cqqwz.cn/Article/details/gt2daesulgn.html

Go:   // 手写递归
来源：http://dali.jyoumei.cn/Article/details/gt2ydjchmwf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvtktxj.html

C#:   // 手写递归
来源：http://dali.hammf.cn/Article/details/gt2krvwnkvz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinqigfzy.top/Article/details/gt2zmicxpqd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cqqwz.cn/Article/details/gt2djguizlt.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wqagjirh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yanxiufei.cn/Article/details/gt2bkifbvgw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nwbrower.top/Article/details/gt2huxgbinf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hyayvejw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.nanxuanxn.top/Article/details/gt2gaosxxbb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.iojbl.cn/Article/details/gt2dxjectvx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenjidiqi.icu/Article/details/gt2aiewihuv.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2juevmabs.html

O. 并发与异步
来源：http://dali.nanxinkj.top/Article/details/gt2jywgraxm.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2qypttnjg.html

[O01] 启动一个线程
来源：http://dali.tianlin.xyz/Article/details/gt2bqyhdckq.html


<!-- 参考信息 -->