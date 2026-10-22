代发 wailian999

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hammf.cn/Article/details/gttsesxufi.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.c1oappe.top/Article/details/gtgunvtldn.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.pycfn.com/Article/details/gtyfrmelgs.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sysykeji.top/Article/details/gtjfntwxsx.html

[K06] 解析 URL 查询串
来源：http://dali.shuidangran.top/Article/details/gtfbyqhywd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ppjwa.cn/Article/details/gtxitqdhjh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jqgufenzy.top/Article/details/gtnolhdxrx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtaqkygasv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.andypj.xyz/Article/details/gtelrgqnuh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlakjkgfi.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yangfankeji.com/Article/details/gtzvmboxjd.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gtwcmxfqms.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gtwetnqhhy.html

[K07] 进制转换
来源：http://dali.nwbrower.top/Article/details/gtbcaghanj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtwmhtxcyc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yonumen.top/Article/details/gtswodnmgc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yj20258.top/Article/details/gtqeofstyw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gtlsozxbdh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtwyoxtlls.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gzhubu.top/Article/details/gtirrsfzxt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.pycfn.com/Article/details/gtaxluojyf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtuaolwlrz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hammf.cn/Article/details/gtdsyprddm.html

Py:   pickle.dumps(obj)
来源：http://dali.jqgfzy.top/Article/details/gtpfzkdbfr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gotoacloud.top/Article/details/gtknezaqer.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.iojbl.cn/Article/details/gtyltoxztl.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shzxlz.cn/Article/details/gtfqwzzdid.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cdnleiting.top/Article/details/gtmkqzwugl.html

Go:   encoding/gob
来源：http://dali.vqdsnc.cn/Article/details/gtpvxfdiye.html

Ruby: Marshal.dump(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfprvfpac.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.iojbl.cn/Article/details/gtctwbssta.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtuelmdcjd.html

L. 网络请求
来源：http://dali.birdmap.top/Article/details/gtwdmxjxdy.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtynkjbwkd.html

[L01] 发送 GET 请求
来源：http://dali.quarkkingdee.top/Article/details/gtootlrxfe.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.bjfxy.top/Article/details/gtlglwmgqm.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cdnleiting.top/Article/details/gtoayivhpw.html

JS:   await fetch(url)
来源：http://dali.gotoacloud.top/Article/details/gtonkbktiu.html

TS:   await fetch(url)
来源：http://dali.shzxlz.cn/Article/details/gtfqmbnfrz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.guannengcc.top/Article/details/gtvqakwpdz.html

Go:   resp, err := http.Get(url)
来源：http://dali.wangshuangyany.cn/Article/details/gtdbmjokdl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.wangdashe.top/Article/details/gtwbhiyjcq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.svipenyu.cn/Article/details/gtdmqdkzjv.html

[L02] 发送 POST JSON
来源：http://dali.yangfankeji.com/Article/details/gtyajkhxsx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.aizwys.cn/Article/details/gtjwchqyuv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gaohongyu789.top/Article/details/gtkwvzjrpi.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pengpengdd.cyou/Article/details/gtnkqxunsv.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sxryk.cn/Article/details/gtdmwpgyrd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ehwqpu.com/Article/details/gthnbwvwxv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cashguo.top/Article/details/gtdvuputfk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yonumen.top/Article/details/gtpjsgwgqe.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.0kj1m.cn/Article/details/gtxfaxuyme.html

[L03] 设置自定义请求头
来源：http://dali.haohaochexian.top/Article/details/gtgrazizjx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.kuanghao11.cn/Article/details/gtamkmkala.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.andypj.xyz/Article/details/gtwcxittry.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shuidangran.top/Article/details/gtgainbwdn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ppjwa.cn/Article/details/gtmvwrmozl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqmhvexlp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gotoacloud.top/Article/details/gtesutcocz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sxryk.cn/Article/details/gtjdrnjjpc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbgktvepo.html

[L04] 设置超时
来源：http://dali.hnqzz.top/Article/details/gtsghkayod.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tian-w.cn/Article/details/gtbkxvezdq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhiwuduotai.top/Article/details/gtnsinvysv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nwbrower.top/Article/details/gthtylwcok.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.birdmap.top/Article/details/gtjmnmzyec.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shangyingyoupin.top/Article/details/gtczqveysc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jqgfzy.top/Article/details/gtqmpuwkpb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hnqzz.top/Article/details/gtfqizxptp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hammf.cn/Article/details/gtakphtqjn.html

[L05] 上传文件（multipart）
来源：http://dali.zhoulong.xyz/Article/details/gtjvegnpcb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cheryme.top/Article/details/gtpjgzvnmc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.nanxinkj.top/Article/details/gthfzrhtbp.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cucudq.cn/Article/details/gthvduiwtp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sysykeji.top/Article/details/gtzvzvrrui.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvevhyerh.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.svipenyu.cn/Article/details/gtvxoszzqn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.pengpengdd.cyou/Article/details/gtejqmavyb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.dianchejie.cn/Article/details/gthrvefhsb.html

[L06] 解析响应为 JSON
来源：http://dali.gzhubu.top/Article/details/gtozyfbapk.html

Py:   resp.json()
来源：http://dali.316326.xyz/Article/details/gtbjfviexv.html

PHP:  json_decode($body, true);
来源：http://dali.yvedp.cn/Article/details/gtvdzcbrrq.html

JS:   await resp.json()
来源：http://dali.tianlin.xyz/Article/details/gtkuyexllq.html

TS:   await resp.json()
来源：http://dali.vqdsnc.cn/Article/details/gttgywuvff.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gtfhrjvivl.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpsjawfps.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhiwuduotai.top/Article/details/gtzlcuuryd.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.daria6918.cn/Article/details/gtzuxjjrca.html

[L07] 处理 HTTP 状态码
来源：http://dali.ivvv.top/Article/details/gtmjpqkvwr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yuanzhike.top/Article/details/gtwonisejt.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.bjfxy.top/Article/details/gtwylxarpn.html

JS:   resp.ok;  resp.status
来源：http://dali.mhx1999.top/Article/details/gtqoactevi.html

TS:   resp.ok;  resp.status
来源：http://dali.sufxvd.cn/Article/details/gtgrsvozpq.html

Java: resp.statusCode()
来源：http://dali.sysykeji.top/Article/details/gturinklrk.html

Go:   resp.StatusCode
来源：http://dali.chenjidiqi.icu/Article/details/gtnmkihymn.html

Ruby: resp.code.to_i
来源：http://dali.jianghu66.top/Article/details/gthdxbjgqj.html

C#:   (int)resp.StatusCode
来源：http://dali.0kj1m.cn/Article/details/gtckrupmar.html

[L08] 并发请求多个地址
来源：http://dali.sufxvd.cn/Article/details/gtmixrzwji.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.daxiang520.top/Article/details/gtgcufdobk.html

PHP:  curl_multi_init() 系列
来源：http://dali.316326.xyz/Article/details/gtceyzqjni.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hammf.cn/Article/details/gtojikluer.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nwbrower.top/Article/details/gttxsimrwb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgngjzqsw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gaohongyu789.top/Article/details/gtffnwlsrm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xinyue.icu/Article/details/gtowwkvxxg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jqgufenzy.top/Article/details/gtjszcwrjc.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtwkrsxlni.html

M. 命令行 / 进程 / 环境
来源：http://dali.havefunace.top/Article/details/gtlovvdxjb.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtmjutfglu.html

[M01] 读取命令行参数
来源：http://dali.hnxiangtu.top/Article/details/gtoectauww.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gtgldfccua.html

PHP:  $argv;  $argc;
来源：http://dali.zhoulong.xyz/Article/details/gtitlffdqr.html

JS:   process.argv.slice(2)
来源：http://dali.yuanzhike.top/Article/details/gtvcwjdyvi.html

TS:   process.argv.slice(2)
来源：http://dali.zycfv.cn/Article/details/gtodfsrlpd.html

Java: args 数组（main 方法参数）
来源：http://dali.shuidangran.top/Article/details/gtyfaysfsz.html

Go:   os.Args[1:]
来源：http://dali.xuetiantiany.cn/Article/details/gtkksgrqpw.html

Ruby: ARGV
来源：http://dali.snrcjt.cn/Article/details/gtbpibjzcq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.aizwys.cn/Article/details/gtzvxsfpgt.html

[M02] 读取环境变量
来源：http://dali.havefunace.top/Article/details/gtnngqopfx.html

Py:   os.environ.get("HOME")
来源：http://dali.jqgfzy.top/Article/details/gtikfrtnra.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.daria6918.cn/Article/details/gtpotipyai.html

JS:   process.env.HOME
来源：http://dali.nanxuanxn.top/Article/details/gthyvqggfn.html

TS:   process.env.HOME
来源：http://dali.andypj.xyz/Article/details/gthmwtkymd.html

Java: System.getenv("HOME")
来源：http://dali.andypj.xyz/Article/details/gtwgscirun.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.c1oappe.top/Article/details/gtruvpkkwh.html

Ruby: ENV["HOME"]
来源：http://dali.pycfn.com/Article/details/gtbplotlxr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gtnsmayqed.html

[M03] 执行外部命令
来源：http://dali.jinqigufen.top/Article/details/gtbqoysybj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhoulong.xyz/Article/details/gtskemyffe.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jlsjyb.cn/Article/details/gticnbpihy.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuetiantiany.cn/Article/details/gtjypsudgq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yueranfly.top/Article/details/gtgfuzwrfc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.iojbl.cn/Article/details/gtvbabkbfn.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.bjfxy.top/Article/details/gtbplhgxpw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenjidiqi.icu/Article/details/gtajuszgzg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sxryk.cn/Article/details/gtmmmtrsop.html

[M04] 获取当前工作目录
来源：http://dali.haohaochexian.top/Article/details/gtcrhulier.html

Py:   os.getcwd()
来源：http://dali.zhengqikj.top/Article/details/gtlvanmhsu.html

PHP:  getcwd();
来源：http://dali.hywenlv.cn/Article/details/gtielvdaya.html

JS:   process.cwd()
来源：http://dali.iojbl.cn/Article/details/gtjhsyaimp.html

TS:   process.cwd()
来源：http://dali.yuxming.cn/Article/details/gtyfeyzece.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ehwqpu.com/Article/details/gtooizgtft.html

Go:   os.Getwd()
来源：http://dali.sweek.top/Article/details/gtjkacymef.html

Ruby: Dir.pwd
来源：http://dali.hysaishi.cn/Article/details/gtrojccsvd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.bjfxy.top/Article/details/gtokaagbhz.html

[M05] 设置退出码
来源：http://dali.yueranfly.top/Article/details/gtkvpxdnzf.html

Py:   sys.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gtdtlfsxgh.html

PHP:  exit(1);
来源：http://dali.zhongyouzk.top/Article/details/gthngiwnkj.html

JS:   process.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtgsecvcct.html

TS:   process.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gttoufsugp.html

Java: System.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gtasovcxwt.html

Go:   os.Exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtltnfivsa.html

Ruby: exit 1
来源：http://dali.0kj1m.cn/Article/details/gtxpttzkkn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cqqwz.cn/Article/details/gtsscepfmc.html

[M06] 向标准错误输出
来源：http://dali.0kj1m.cn/Article/details/gtiyzgtxqj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ehwqpu.com/Article/details/gtjpugzhgu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinghuilouyu.cn/Article/details/gtqnnycrlj.html

JS:   console.error("err")
来源：http://dali.9152youxi.cn/Article/details/gtchfyzzyz.html

TS:   console.error("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjlrjablt.html

Java: System.err.println("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoiwwljwm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sxryk.cn/Article/details/gtzzolelec.html

Ruby: warn "err"
来源：http://dali.vqdsnc.cn/Article/details/gthymbexwx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hongshengwenyu.top/Article/details/gtqktcbbdy.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gtzvadxary.html

Py:   if __name__ == "__main__":
来源：http://dali.bjfxy.top/Article/details/gtoauoqiky.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.wangshuangyany.cn/Article/details/gtlsbposly.html

JS:   require.main === module
来源：http://dali.ydzc1.top/Article/details/gtlfzeqwpw.html

TS:   require.main === module
来源：http://dali.daxiang520.top/Article/details/gtxskwfdtp.html

Java: public static void main(String[] args)
来源：http://dali.fengsongda.top/Article/details/gthetwwwyn.html

Go:   func main()
来源：http://dali.yj20258888.top/Article/details/gtfftckcmj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhiwuduotai.top/Article/details/gtijswisxv.html

C#:   static void Main(string[] args)
来源：http://dali.yongpay.top/Article/details/gtrwdvllrz.html

[M08] 获取系统与运行时信息
来源：http://dali.hfpthk.cn/Article/details/gthvoegqle.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xuanzx.com/Article/details/gthlbvwawg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.dianchejie.cn/Article/details/gtuxirtzjq.html

JS:   process.platform;  process.version
来源：http://dali.jinqigfzy.top/Article/details/gtjrayebqr.html

TS:   process.platform;  process.version
来源：http://dali.guowangkeji.top/Article/details/gtucjnaeee.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jyoumei.cn/Article/details/gtswuxozie.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gtahsonale.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shuidangran.top/Article/details/gtpezvcmio.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ybcxt.top/Article/details/gtadbdfnzr.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtgwiyswwj.html

N. 数据结构与算法
来源：http://dali.sysykeji.top/Article/details/gtzzixklqf.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtvuoofkar.html

[N01] 二分查找（有序数组）
来源：http://dali.haohaochexian.top/Article/details/gtlysvzlik.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cheryme.top/Article/details/gtesjzhylb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinqigfzy.top/Article/details/gttafrdeso.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jlsjyb.cn/Article/details/gtqqcgjqod.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xinyue.icu/Article/details/gtbtfdiiob.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtkialpixr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gthwqewzni.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cashguo.top/Article/details/gtlzmtusxu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xylfe.cn/Article/details/gteyurhepc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hywenlv.cn/Article/details/gtreatlawn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhoulong.xyz/Article/details/gtjrqvqxhw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.bjfxy.top/Article/details/gtkbzoapry.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuetiantiany.cn/Article/details/gttsalqoho.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.svipenyu.cn/Article/details/gtzlmmruqy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.havefunace.top/Article/details/gtxnjoljcq.html

Go:   slices.Sort(arr)
来源：http://dali.daxiang520.top/Article/details/gtuxypxjfl.html

Ruby: arr.sort
来源：http://dali.zhongyouzk.top/Article/details/gthkyvdcre.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.mhx1999.top/Article/details/gtkrlcmeyh.html

[N03] 快速排序（分治示例）
来源：http://dali.zhixingplan.top/Article/details/gtyctxzwrz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.c1oappe.top/Article/details/gtyhmnemuc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yonumen.top/Article/details/gtsurxhkoj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.smart0.xyz/Article/details/gtblkimmrk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guannengcc.top/Article/details/gtjudwndnj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jlsjyb.cn/Article/details/gtuqlhmdxo.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hongshengwenyu.top/Article/details/gtjyfhyfua.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfaozjvzn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhoulong.xyz/Article/details/gtdwsvoqed.html

[N04] 斐波那契数列
来源：http://dali.shangyingyoupin.top/Article/details/gtpirrlbym.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xuanzx.com/Article/details/gttwkrtiti.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.pycfn.com/Article/details/gtwdebnwgf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tanke756.top/Article/details/gtvmisdese.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yongpay.top/Article/details/gttbjrmrcl.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xuanzx.com/Article/details/gtfmcfybci.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yuanzhike.top/Article/details/gtvhxxvchp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.c1oappe.top/Article/details/gtogsnwlzo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gtkeficlhp.html

[N05] 最大公约数
来源：http://dali.yvedp.cn/Article/details/gtowmkwzto.html

Py:   math.gcd(a, b)
来源：http://dali.haohaochexian.top/Article/details/gthplnludf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.tianlin.xyz/Article/details/gtdktucauf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zdqjudy.top/Article/details/gtdtqkjvuv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daria6918.cn/Article/details/gtofqncbim.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ybcxt.top/Article/details/gtclkgkrll.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yuanzhike.top/Article/details/gtgapejgrf.html

Ruby: a.gcd(b)
来源：http://dali.yongpay.top/Article/details/gtebiqazfd.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sysykeji.top/Article/details/gtenyelbkh.html

[N06] 判断回文字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtywhcrfoj.html

Py:   s == s[::-1]
来源：http://dali.jyoumei.cn/Article/details/gtrvpwybtj.html

PHP:  $s === strrev($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwoefbwmu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gtyjbrxtem.html

TS:   s === [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gtvycfzemv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xylfe.cn/Article/details/gtpfsnpbes.html

Go:   // 双指针从两端比较
来源：http://dali.jqgfzy.top/Article/details/gtopywbuyy.html

Ruby: s == s.reverse
来源：http://dali.birdmap.top/Article/details/gtiediwzwr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhoulong.xyz/Article/details/gtnfxdtowk.html

[N07] 两数之和（返回下标）
来源：http://dali.jinqigfzy.top/Article/details/gtleygvxcf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ppjwa.cn/Article/details/gtlhxbvtpo.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yuxming.cn/Article/details/gtnflegwbe.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jlsjyb.cn/Article/details/gtmcavlraq.html

TS:   // 手写 Map<string, number>
来源：http://dali.c1oappe.top/Article/details/gtdbijvllu.html

Java: // 手写 HashMap
来源：http://dali.jiagoushi.top/Article/details/gtjiiuleks.html

Go:   // 手写 map[int]int
来源：http://dali.zhoulong.xyz/Article/details/gtxicjijbl.html

Ruby: // 手写 Hash
来源：http://dali.jlsjyb.cn/Article/details/gtwnedtlnx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yanxiufei.cn/Article/details/gtbbhtqflv.html

[N08] 生成全排列
来源：http://dali.wangdashe.top/Article/details/gtkpddwcik.html

Py:   itertools.permutations(arr)
来源：http://dali.ybcxt.top/Article/details/gttjiluqst.html

PHP:  // 手写递归交换
来源：http://dali.zhiwuduotai.top/Article/details/gtxlfvonqi.html

JS:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gtnzyzfmqp.html

TS:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gtdhramtgp.html

Java: // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gthhdfqopn.html

Go:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gtrgeorjci.html

Ruby: arr.permutation.to_a
来源：http://dali.tian-w.cn/Article/details/gtrqxyofvg.html

C#:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gtcoefylwc.html

[N09] 栈与队列
来源：http://dali.daxiang520.top/Article/details/gtgtcqkcok.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.svipenyu.cn/Article/details/gtcrnppamj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yanxiufei.cn/Article/details/gtwflavljh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yj202588.top/Article/details/gtcqrhpkqq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhixingplan.top/Article/details/gtzrugigbo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhiwuduotai.top/Article/details/gtbcdkgofo.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jlsjyb.cn/Article/details/gtjfgypxzi.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yangfankeji.com/Article/details/gtxoznknhw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhengqikj.top/Article/details/gtxevfqbwc.html

[N10] 链表节点定义
来源：http://dali.redwolf501.top/Article/details/gtelbrjuow.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.316326.xyz/Article/details/gtxxhxszww.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.nwbrower.top/Article/details/gtbaijquef.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ivvv.top/Article/details/gtzxtkzlot.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zycfv.cn/Article/details/gtjwvpyijk.html

Java: class Node { int v; Node next; }
来源：http://dali.yanxiufei.cn/Article/details/gtgsnojfnn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xinyue.icu/Article/details/gtrbvbfmbr.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ydzc1.top/Article/details/gtmcghetga.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hnxiangtu.top/Article/details/gtofkhkomu.html

[N11] 二叉树中序遍历
来源：http://dali.yuxming.cn/Article/details/gtmuodousc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.fengsongda.top/Article/details/gtecnpttom.html

PHP:  // 手写递归函数
来源：http://dali.sysykeji.top/Article/details/gtyctmtqwx.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxinkj.top/Article/details/gthuydpaua.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhiwuduotai.top/Article/details/gthiqonfzb.html

Java: // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gthskuplsy.html

Go:   // 手写递归
来源：http://dali.yj20258.top/Article/details/gtbmwjdkbv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.meibo888.top/Article/details/gtxyfdntjo.html

C#:   // 手写递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiqbpobix.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jqgfzy.top/Article/details/gtozxmduro.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.iojbl.cn/Article/details/gtgeujqinf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hammf.cn/Article/details/gtcrnizwre.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ppjwa.cn/Article/details/gtkzapudec.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.bjfxy.top/Article/details/gtvefhgldq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fengsongda.top/Article/details/gteditwetk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqgnxpqpc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yvedp.cn/Article/details/gtavzmcbiw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tian-w.cn/Article/details/gtfobsmicz.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtehkbdgvs.html

O. 并发与异步
来源：http://dali.daxiang520.top/Article/details/gtasyhfdjn.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtvuisxyzw.html

[O01] 启动一个线程
来源：http://dali.ivvv.top/Article/details/gtmqenpcnl.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yueranfly.top/Article/details/gtbouukhto.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yj20258888.top/Article/details/gtqhfepwkb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hysaishi.cn/Article/details/gtdabbmvuy.html

TS:   // 同 JS
来源：http://dali.vqdsnc.cn/Article/details/gtnolztdav.html


<!-- 参考信息 -->