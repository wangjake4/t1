代发 wailian999

Py:   copy.deepcopy(obj)
来源：http://dali.ydzc1.top/Article/details/gtgmiqmjqq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yueranfly.top/Article/details/gtbicpbklg.html

JS:   structuredClone(obj)
来源：http://dali.yangfankeji.com/Article/details/gtneklfiqx.html

TS:   structuredClone(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtqsbbzzqw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yj20258.top/Article/details/gtxmcohtlc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.dianchejie.cn/Article/details/gtkjjeende.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jlsjyb.cn/Article/details/gtsujdevml.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zdqjudy.top/Article/details/gtmrgdpbzl.html

[K06] 解析 URL 查询串
来源：http://dali.daria6918.cn/Article/details/gtwmpnhjpy.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwthdghoe.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqjiahovm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cashguo.top/Article/details/gtdksurngt.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.bjfxy.top/Article/details/gtjxahfhlo.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xuanzx.com/Article/details/gteedhissw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yanxiufei.cn/Article/details/gtrkzvviuh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuasluebu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.birdmap.top/Article/details/gtnqnijyyy.html

[K07] 进制转换
来源：http://dali.aibaodan.cn/Article/details/gtotrpbstq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gtgfnwkoft.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xziqi.cn/Article/details/gtpmtkcxgx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtkbzbkcmi.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gtjdcttlzt.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtyhsbjjqp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinqigufen.top/Article/details/gtmfczfqgw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtayvhpcqn.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtawwwnlhi.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nwbrower.top/Article/details/gteobexxqx.html

Py:   pickle.dumps(obj)
来源：http://dali.zycfv.cn/Article/details/gtpgadvvil.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zdqjudy.top/Article/details/gtqnhgkfzk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.quarkkingdee.top/Article/details/gtnuiqtpsm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.birdmap.top/Article/details/gthwbzeytv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenlongwang.top/Article/details/gtqqjcbyex.html

Go:   encoding/gob
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjmoalzay.html

Ruby: Marshal.dump(obj)
来源：http://dali.yuanzhike.top/Article/details/gttgsjltpy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sufxvd.cn/Article/details/gtfaddxwma.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtrfasxrcv.html

L. 网络请求
来源：http://dali.cashguo.top/Article/details/gthnokehfs.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtccffjeyd.html

[L01] 发送 GET 请求
来源：http://dali.jqgfzy.top/Article/details/gtlmufsvvz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sufxvd.cn/Article/details/gtsndtfmox.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nanxuanxn.top/Article/details/gtdwalasvn.html

JS:   await fetch(url)
来源：http://dali.birdmap.top/Article/details/gtshvgmmsu.html

TS:   await fetch(url)
来源：http://dali.mhx1999.top/Article/details/gtoncrhwzl.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yueranfly.top/Article/details/gthonfleip.html

Go:   resp, err := http.Get(url)
来源：http://dali.hammf.cn/Article/details/gtwqgjezrv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jlsjyb.cn/Article/details/gtjolpmpdy.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.mhx1999.top/Article/details/gthujaepxm.html

[L02] 发送 POST JSON
来源：http://dali.gaohongyu789.top/Article/details/gthqbjbauz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shzxlz.cn/Article/details/gtuaiygvou.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.316326.xyz/Article/details/gtaavinpwx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jlsjyb.cn/Article/details/gtctmlnldp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgfzy.top/Article/details/gtnhedbxpq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.guowangkeji.top/Article/details/gtntcuprze.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ehwqpu.com/Article/details/gtyywhonyl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.tian-w.cn/Article/details/gtsxzoipie.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkilorrbf.html

[L03] 设置自定义请求头
来源：http://dali.shanyushiyangtech.top/Article/details/gtjmysyyfx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.dashuyun.cn/Article/details/gtpcrpbmez.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.smart0.xyz/Article/details/gtjwhxuvjj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.meibo888.top/Article/details/gtnpstmuub.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.0kj1m.cn/Article/details/gtifdggnrv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.nwbrower.top/Article/details/gtnghzbkgy.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.fzhhl.top/Article/details/gthvsajgub.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.pycfn.com/Article/details/gtvdubahon.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yvedp.cn/Article/details/gtlspnpkil.html

[L04] 设置超时
来源：http://dali.yj20258888.top/Article/details/gtqhwzaajs.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yongpay.top/Article/details/gtcwunknpi.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenlongwang.top/Article/details/gtenuadspu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jianghu66.top/Article/details/gtzxzunrnx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuanzhike.top/Article/details/gttkhwfczp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jiagoushi.top/Article/details/gtguchrtjd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.guannengcc.top/Article/details/gtmjfpivco.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxbihlptl.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gtwtsxrxph.html

[L05] 上传文件（multipart）
来源：http://dali.cucudq.cn/Article/details/gtrsbaevdr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hysaishi.cn/Article/details/gtqurpvqhg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jlsjyb.cn/Article/details/gtehvzrkay.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenzaomai.com/Article/details/gtawqusxpm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.quarkkingdee.top/Article/details/gtefbxlixp.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.9152youxi.cn/Article/details/gttbozzgkq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jqgfzy.top/Article/details/gtmomfyorl.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.feifeiyinyue.top/Article/details/gtqdcgexee.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtqfdpdshs.html

[L06] 解析响应为 JSON
来源：http://dali.dianchejie.cn/Article/details/gtwdxgeevd.html

Py:   resp.json()
来源：http://dali.xylfe.cn/Article/details/gtvlgfmqdt.html

PHP:  json_decode($body, true);
来源：http://dali.pengpengdd.cyou/Article/details/gtohjwbiut.html

JS:   await resp.json()
来源：http://dali.ehwqpu.com/Article/details/gtmwbdwoxk.html

TS:   await resp.json()
来源：http://dali.wangshuangyany.cn/Article/details/gtfgmpxojv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gzhubu.top/Article/details/gteotykgwg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhoulong.xyz/Article/details/gtlpyvwdwy.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yuanzhike.top/Article/details/gtmmzonnod.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.iojbl.cn/Article/details/gtthdrurfr.html

[L07] 处理 HTTP 状态码
来源：http://dali.fzhhl.top/Article/details/gtebjuzjep.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.mhx1999.top/Article/details/gtgeaezydw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hysaishi.cn/Article/details/gtabyydqjc.html

JS:   resp.ok;  resp.status
来源：http://dali.hnxiangtu.top/Article/details/gttplnbdfv.html

TS:   resp.ok;  resp.status
来源：http://dali.shuidangran.top/Article/details/gttopmjqcj.html

Java: resp.statusCode()
来源：http://dali.nanxuanxn.top/Article/details/gtnuckqsik.html

Go:   resp.StatusCode
来源：http://dali.cucudq.cn/Article/details/gtmakiamcy.html

Ruby: resp.code.to_i
来源：http://dali.fzhhl.top/Article/details/gtdltegqgy.html

C#:   (int)resp.StatusCode
来源：http://dali.yanxiufei.cn/Article/details/gtfzvkblvp.html

[L08] 并发请求多个地址
来源：http://dali.yuanzhike.top/Article/details/gtqrdytlyl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.meibo888.top/Article/details/gtviwublkn.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinqigufen.top/Article/details/gtfprmphmd.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258888.top/Article/details/gtptuvveou.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yangfankeji.com/Article/details/gtaghouxkh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhongyouzk.top/Article/details/gtxllevmcx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.wangshuangyany.cn/Article/details/gtscxhqjsp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gogol.net.cn/Article/details/gtwbphdcwq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gtxhbvzolf.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtqmbtkpti.html

M. 命令行 / 进程 / 环境
来源：http://dali.snrcjt.cn/Article/details/gtqvekarks.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtphqpqxbh.html

[M01] 读取命令行参数
来源：http://dali.chenjidiqi.icu/Article/details/gtvlwtdchy.html

Py:   sys.argv[1:]
来源：http://dali.cqqwz.cn/Article/details/gtwenojoqw.html

PHP:  $argv;  $argc;
来源：http://dali.tanke756.top/Article/details/gttnoidowr.html

JS:   process.argv.slice(2)
来源：http://dali.ivvv.top/Article/details/gtptidxnax.html

TS:   process.argv.slice(2)
来源：http://dali.hywenlv.cn/Article/details/gtmztbofrs.html

Java: args 数组（main 方法参数）
来源：http://dali.zdqjudy.top/Article/details/gtdolwyccj.html

Go:   os.Args[1:]
来源：http://dali.wangshuangyany.cn/Article/details/gturotulfn.html

Ruby: ARGV
来源：http://dali.hnqzz.top/Article/details/gtnpyusjyx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zycfv.cn/Article/details/gtjfbutlpu.html

[M02] 读取环境变量
来源：http://dali.cdnleiting.top/Article/details/gtprfjwwke.html

Py:   os.environ.get("HOME")
来源：http://dali.redwolf501.top/Article/details/gtlwvpbdws.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkjackyax.html

JS:   process.env.HOME
来源：http://dali.chenjidiqi.icu/Article/details/gtrlgzcnlh.html

TS:   process.env.HOME
来源：http://dali.yuanzhike.top/Article/details/gtoaeyskvn.html

Java: System.getenv("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gtsadkgjyk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtocdsxffl.html

Ruby: ENV["HOME"]
来源：http://dali.shangyingyoupin.top/Article/details/gtwigpwtru.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.snrcjt.cn/Article/details/gtwxblqhnn.html

[M03] 执行外部命令
来源：http://dali.yj20258.top/Article/details/gtkcvkjyig.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gaohongyu789.top/Article/details/gtudirvpub.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.9152youxi.cn/Article/details/gtpwxctvre.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuanzx.com/Article/details/gtjlwixifz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ivvv.top/Article/details/gthuoflvay.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cdnleiting.top/Article/details/gtmlmzbzrt.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ydzc1.top/Article/details/gtcpwjvymd.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jianghu66.top/Article/details/gtanseacma.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tian-w.cn/Article/details/gthifpwrai.html

[M04] 获取当前工作目录
来源：http://dali.yuanzhike.top/Article/details/gtpfxwtjfp.html

Py:   os.getcwd()
来源：http://dali.andypj.xyz/Article/details/gtlzxrjtyf.html

PHP:  getcwd();
来源：http://dali.yongpay.top/Article/details/gtafvpgkwf.html

JS:   process.cwd()
来源：http://dali.316326.xyz/Article/details/gthejkztti.html

TS:   process.cwd()
来源：http://dali.sxryk.cn/Article/details/gttfqphoql.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.feifeiyinyue.top/Article/details/gtemmwljez.html

Go:   os.Getwd()
来源：http://dali.bjfxy.top/Article/details/gtzaprmhux.html

Ruby: Dir.pwd
来源：http://dali.yanxiufei.cn/Article/details/gtetktjzom.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtchpnapdy.html

[M05] 设置退出码
来源：http://dali.yj20258888.top/Article/details/gtkvxvxamw.html

Py:   sys.exit(1)
来源：http://dali.iojbl.cn/Article/details/gtumwglpen.html

PHP:  exit(1);
来源：http://dali.mhx1999.top/Article/details/gtnjczjpjc.html

JS:   process.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtnemhxvyh.html

TS:   process.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtarrhllal.html

Java: System.exit(1)
来源：http://dali.nwbrower.top/Article/details/gtnzmmofvi.html

Go:   os.Exit(1)
来源：http://dali.jyoumei.cn/Article/details/gtrncrjnwo.html

Ruby: exit 1
来源：http://dali.vqdsnc.cn/Article/details/gtoyslsffg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gotoacloud.top/Article/details/gtygjvucnx.html

[M06] 向标准错误输出
来源：http://dali.jyoumei.cn/Article/details/gtegfxcbgr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shangyingyoupin.top/Article/details/gtgalvofrb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.pycfn.com/Article/details/gtauupcyxy.html

JS:   console.error("err")
来源：http://dali.hfpthk.cn/Article/details/gtywhqpuid.html

TS:   console.error("err")
来源：http://dali.gogol.net.cn/Article/details/gtdlevicwt.html

Java: System.err.println("err")
来源：http://dali.tianlin.xyz/Article/details/gtmfnmxnuy.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.mhx1999.top/Article/details/gtippmnkqf.html

Ruby: warn "err"
来源：http://dali.yuanzhike.top/Article/details/gtmplzdcxd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xylfe.cn/Article/details/gtnyqkmlef.html

[M07] 判断是否为主入口
来源：http://dali.c1oappe.top/Article/details/gtaoakguht.html

Py:   if __name__ == "__main__":
来源：http://dali.nwbrower.top/Article/details/gtkhoyhgvz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ydzc1.top/Article/details/gtuoamxyjq.html

JS:   require.main === module
来源：http://dali.shangyingyoupin.top/Article/details/gtllzgejxz.html

TS:   require.main === module
来源：http://dali.c1oappe.top/Article/details/gtlfpoeyod.html

Java: public static void main(String[] args)
来源：http://dali.nanxinkj.top/Article/details/gtwknktror.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gtxpgjydvj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.0kj1m.cn/Article/details/gtfmemobyi.html

C#:   static void Main(string[] args)
来源：http://dali.cqqwz.cn/Article/details/gtaaaeyfra.html

[M08] 获取系统与运行时信息
来源：http://dali.xinyue.icu/Article/details/gtykeapjbp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.smart0.xyz/Article/details/gtboelnzsl.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhengqikj.top/Article/details/gtumulqabw.html

JS:   process.platform;  process.version
来源：http://dali.cdnleiting.top/Article/details/gtvnhxvsyf.html

TS:   process.platform;  process.version
来源：http://dali.redwolf501.top/Article/details/gtjwkeyrnx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.daria6918.cn/Article/details/gtpsnsimwo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hysaishi.cn/Article/details/gtmdjbiocv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hongshengwenyu.top/Article/details/gtdqekhsbi.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.daria6918.cn/Article/details/gtnzwxzwoq.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtldqcldoa.html

N. 数据结构与算法
来源：http://dali.ybcxt.top/Article/details/gtguplwsuj.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtjuiguhkt.html

[N01] 二分查找（有序数组）
来源：http://dali.snrcjt.cn/Article/details/gtcckolygs.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtjwadjjas.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jyoumei.cn/Article/details/gtuystwiya.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fzhhl.top/Article/details/gtwmnhmjcl.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pengpengdd.cyou/Article/details/gtrabycocg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtisttsoix.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.andypj.xyz/Article/details/gthtybhzmp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sysykeji.top/Article/details/gtvbikktao.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ydzc1.top/Article/details/gteplsgdnk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.9152youxi.cn/Article/details/gtmrjatmsh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgufenzy.top/Article/details/gtffgngscu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ivvv.top/Article/details/gtclqffqph.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gotoacloud.top/Article/details/gthmbixciu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gtxlqseppf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yangfankeji.com/Article/details/gtnhglltet.html

Go:   slices.Sort(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtnbkwkgwu.html

Ruby: arr.sort
来源：http://dali.c1oappe.top/Article/details/gtbmpmsbjy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.tian-w.cn/Article/details/gtzzbljxtm.html

[N03] 快速排序（分治示例）
来源：http://dali.fengsongda.top/Article/details/gtqrwjcxao.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hfpthk.cn/Article/details/gtxkxcertm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.vqdsnc.cn/Article/details/gthfganuzt.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zycfv.cn/Article/details/gtevlbuvvb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvgazpykd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.feifeiyinyue.top/Article/details/gtugzaqvvi.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.havefunace.top/Article/details/gtqhvdptyn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tian-w.cn/Article/details/gtxsnvcojv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.fengsongda.top/Article/details/gtfndqwczd.html

[N04] 斐波那契数列
来源：http://dali.zhixingplan.top/Article/details/gtsfbkcsna.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.tianlin.xyz/Article/details/gtmgwuvztb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yuxming.cn/Article/details/gtghgmyqlw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.meibo888.top/Article/details/gtxmvbkjzn.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhoulong.xyz/Article/details/gtvoqfqvlg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shzxlz.cn/Article/details/gtpgniykwm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtizxnatvu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.c1oappe.top/Article/details/gtoozrqoak.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hywenlv.cn/Article/details/gtejkrmcky.html

[N05] 最大公约数
来源：http://dali.bjfxy.top/Article/details/gtnbiavcqy.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gtmujzypxg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvdzxktkl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shangyingyoupin.top/Article/details/gtzgabenhp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dianchejie.cn/Article/details/gtejwrhhea.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sxryk.cn/Article/details/gtshsfbsrb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.iojbl.cn/Article/details/gtafckgjyc.html

Ruby: a.gcd(b)
来源：http://dali.yvedp.cn/Article/details/gtrlegcjpi.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.svipenyu.cn/Article/details/gtkiezzsfd.html

[N06] 判断回文字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtapayxarf.html

Py:   s == s[::-1]
来源：http://dali.xylfe.cn/Article/details/gtrmxqhnyj.html

PHP:  $s === strrev($s);
来源：http://dali.birdmap.top/Article/details/gtmjdekhlt.html

JS:   s === [...s].reverse().join("")
来源：http://dali.fzhhl.top/Article/details/gthvnnisvo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gtcyrbpjpk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.aibaodan.cn/Article/details/gtgpabsicm.html

Go:   // 双指针从两端比较
来源：http://dali.yueranfly.top/Article/details/gthxksblhc.html

Ruby: s == s.reverse
来源：http://dali.shangyingyoupin.top/Article/details/gtajgvjsrw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yj20258888.top/Article/details/gtwnjcgftm.html

[N07] 两数之和（返回下标）
来源：http://dali.wangshuangyany.cn/Article/details/gtvdvrjnfz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sweek.top/Article/details/gteutxwjwu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gotoacloud.top/Article/details/gtvoomhbla.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.wangshuangyany.cn/Article/details/gtgajlmkjr.html

TS:   // 手写 Map<string, number>
来源：http://dali.c1oappe.top/Article/details/gtlpyfitna.html

Java: // 手写 HashMap
来源：http://dali.yj20258.top/Article/details/gtenhzdfph.html

Go:   // 手写 map[int]int
来源：http://dali.gaohongyu789.top/Article/details/gtooontiqz.html

Ruby: // 手写 Hash
来源：http://dali.yongpay.top/Article/details/gtwsdyofll.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hywenlv.cn/Article/details/gtiqrmdpjv.html

[N08] 生成全排列
来源：http://dali.fzhhl.top/Article/details/gtqktltgtw.html

Py:   itertools.permutations(arr)
来源：http://dali.yongpay.top/Article/details/gtrykaeirg.html

PHP:  // 手写递归交换
来源：http://dali.jyoumei.cn/Article/details/gtuiwlaeuc.html

JS:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gtjqtrncfm.html

TS:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gtmlrmwwax.html

Java: // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtpshchcef.html

Go:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gtowpetybz.html

Ruby: arr.permutation.to_a
来源：http://dali.sysykeji.top/Article/details/gtmdfbiqqv.html

C#:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gtbckabubq.html

[N09] 栈与队列
来源：http://dali.cheryme.top/Article/details/gtvhahvrrg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gogol.net.cn/Article/details/gtfvrwwmhw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cheryme.top/Article/details/gtmhqafboq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtdhuqfyxb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cucudq.cn/Article/details/gtpvwjlbiz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jianghu66.top/Article/details/gtsnqrbcit.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yanxiufei.cn/Article/details/gtjrjqaeng.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfbjzwiuu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xinyue.icu/Article/details/gtytszlkha.html

[N10] 链表节点定义
来源：http://dali.dianchejie.cn/Article/details/gtsujvjmgs.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.wangshuangyany.cn/Article/details/gtqnrwtuji.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.feifeiyinyue.top/Article/details/gtfqjybvvz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zycfv.cn/Article/details/gtcedhiacr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqpvsraig.html

Java: class Node { int v; Node next; }
来源：http://dali.ehwqpu.com/Article/details/gtmjzszpvz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sweek.top/Article/details/gtagmgcblf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gzhubu.top/Article/details/gtutpxqqoz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.kuanghao11.cn/Article/details/gtbtyxfzxg.html

[N11] 二叉树中序遍历
来源：http://dali.sysykeji.top/Article/details/gtupylcmam.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sxryk.cn/Article/details/gtkicyakhm.html

PHP:  // 手写递归函数
来源：http://dali.andypj.xyz/Article/details/gtopoirzok.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hysaishi.cn/Article/details/gtdesaayti.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yanxiufei.cn/Article/details/gtpvwyruod.html

Java: // 手写递归
来源：http://dali.ivvv.top/Article/details/gtzvmxczfr.html

Go:   // 手写递归
来源：http://dali.hfpthk.cn/Article/details/gttnrasusl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.pycfn.com/Article/details/gtmyuhzokc.html

C#:   // 手写递归
来源：http://dali.wangshuangyany.cn/Article/details/gtdlkoeoug.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrfrukrdb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gzhubu.top/Article/details/gtiphvjvoz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.redwolf501.top/Article/details/gtonjnjfkf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangshuangyany.cn/Article/details/gtwdlbqqrq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yangfankeji.com/Article/details/gtuevxitwf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xinyue.icu/Article/details/gttxiuppnb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.svipenyu.cn/Article/details/gtydfbqzul.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xuetiantiany.cn/Article/details/gtxprngilb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ppjwa.cn/Article/details/gtdvxjdaua.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtqjlqyfjt.html

O. 并发与异步
来源：http://dali.gzhubu.top/Article/details/gtsawkdpoq.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtnhztbgxd.html

[O01] 启动一个线程
来源：http://dali.quarkkingdee.top/Article/details/gtsqiismdz.html


<!-- 参考信息 -->