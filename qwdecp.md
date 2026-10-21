代发 wailian999

[K06] 解析 URL 查询串
来源：http://dali.zhixingplan.top/Article/details/gtigwqilhc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgufenzy.top/Article/details/gtzqxzwvdo.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.andypj.xyz/Article/details/gtjaemabnd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ybcxt.top/Article/details/gtmshxhgzv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtsxqgfjpk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.c1oappe.top/Article/details/gttcdnjytb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gotoacloud.top/Article/details/gtelkcckzo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzvczmmtw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gtkycfgspx.html

[K07] 进制转换
来源：http://dali.iojbl.cn/Article/details/gtjwecacrc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gttqlzyvnp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yueranfly.top/Article/details/gtxvwztfoy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtgbraxfan.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtvocuwqzr.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpuvrqwwb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zdqjudy.top/Article/details/gtvwacbhmj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.pengpengdd.cyou/Article/details/gtmcmgpvsw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gthplkttsa.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yvedp.cn/Article/details/gtfodblnmb.html

Py:   pickle.dumps(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtosmqjooo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sxryk.cn/Article/details/gtfojiquzp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.9152youxi.cn/Article/details/gtzsflviey.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shuidangran.top/Article/details/gtekainuez.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xuetiantiany.cn/Article/details/gtitnqxrtk.html

Go:   encoding/gob
来源：http://dali.haohaochexian.top/Article/details/gtggmumtol.html

Ruby: Marshal.dump(obj)
来源：http://dali.iojbl.cn/Article/details/gtaaycfrss.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yuxming.cn/Article/details/gtropjvpyd.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtxgzrnjzs.html

L. 网络请求
来源：http://dali.gzhubu.top/Article/details/gttfstsdag.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtcurkietf.html

[L01] 发送 GET 请求
来源：http://dali.aibaodan.cn/Article/details/gturyclxvt.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.c1oappe.top/Article/details/gtdbxcpvbm.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hysaishi.cn/Article/details/gtlndojyss.html

JS:   await fetch(url)
来源：http://dali.0kj1m.cn/Article/details/gtvcxhzugw.html

TS:   await fetch(url)
来源：http://dali.yj20258.top/Article/details/gtmazwshoe.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.redwolf501.top/Article/details/gtlkwapjlr.html

Go:   resp, err := http.Get(url)
来源：http://dali.jqgfzy.top/Article/details/gtrxlmwdth.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yuxming.cn/Article/details/gtrruqlszm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.birdmap.top/Article/details/gtftzfcxpl.html

[L02] 发送 POST JSON
来源：http://dali.havefunace.top/Article/details/gtxixdzfqg.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.bjfxy.top/Article/details/gtfwwlgdug.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.mhx1999.top/Article/details/gtdxlmauok.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.havefunace.top/Article/details/gtupofcbfd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuxming.cn/Article/details/gtctteodjk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yj20258888.top/Article/details/gtlszohzhs.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhoulong.xyz/Article/details/gtuplylsqh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sxryk.cn/Article/details/gtzadrrpug.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jiagoushi.top/Article/details/gtwpfxneyg.html

[L03] 设置自定义请求头
来源：http://dali.cdnleiting.top/Article/details/gtosvkwhdj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.dashuyun.cn/Article/details/gteuwpeccx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.daxiang520.top/Article/details/gtftokcqvl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nwbrower.top/Article/details/gtiijircke.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gaohongyu789.top/Article/details/gttewcxheh.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cheryme.top/Article/details/gtrftkjnyq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gotoacloud.top/Article/details/gtoxlashxw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.tian-w.cn/Article/details/gtprgylsfn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gogol.net.cn/Article/details/gtpnfpqafi.html

[L04] 设置超时
来源：http://dali.jianghu66.top/Article/details/gtgdsvqcyx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shuidangran.top/Article/details/gtjawrkjaw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zdqjudy.top/Article/details/gtogyrovzu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daxiang520.top/Article/details/gtnufgmzuc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.smart0.xyz/Article/details/gtknicjdbx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.havefunace.top/Article/details/gtdfhardct.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ywan-chungtsiang.top/Article/details/gttckcffps.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.iojbl.cn/Article/details/gtbtcbgnmc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xuanzx.com/Article/details/gtwcyqishl.html

[L05] 上传文件（multipart）
来源：http://dali.yuanzhike.top/Article/details/gthmbvrwgv.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.pengpengdd.cyou/Article/details/gtpafsmsrp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhongyouzk.top/Article/details/gtdhromzhv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tianlin.xyz/Article/details/gtqmyjsiro.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xinyue.icu/Article/details/gtyilmfyri.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.dashuyun.cn/Article/details/gtvsqqusve.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.kuanghao11.cn/Article/details/gtucgszrff.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.birdmap.top/Article/details/gtxjmtzvbh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.daria6918.cn/Article/details/gtkintchgc.html

[L06] 解析响应为 JSON
来源：http://dali.cqqwz.cn/Article/details/gtbxcdvryg.html

Py:   resp.json()
来源：http://dali.zhiwuduotai.top/Article/details/gtbfcsqhoo.html

PHP:  json_decode($body, true);
来源：http://dali.jianghu66.top/Article/details/gtupniphef.html

JS:   await resp.json()
来源：http://dali.yj20258888.top/Article/details/gtgfpombpi.html

TS:   await resp.json()
来源：http://dali.yj20258.top/Article/details/gthcwnunkn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhengqikj.top/Article/details/gthwzwvodx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.mhx1999.top/Article/details/gtjocrbmos.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj20258888.top/Article/details/gtltcgdhsq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.tanke756.top/Article/details/gtbmfpdgzl.html

[L07] 处理 HTTP 状态码
来源：http://dali.cdnleiting.top/Article/details/gtkpgujewh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.mhx1999.top/Article/details/gtmjglvnhl.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jlsjyb.cn/Article/details/gtlotghvzy.html

JS:   resp.ok;  resp.status
来源：http://dali.redwolf501.top/Article/details/gtcurwsrgn.html

TS:   resp.ok;  resp.status
来源：http://dali.ybcxt.top/Article/details/gtuqqtunxe.html

Java: resp.statusCode()
来源：http://dali.zhiwuduotai.top/Article/details/gttxcmviqf.html

Go:   resp.StatusCode
来源：http://dali.hysaishi.cn/Article/details/gtobuzfbeo.html

Ruby: resp.code.to_i
来源：http://dali.cqqwz.cn/Article/details/gtbmhsxsls.html

C#:   (int)resp.StatusCode
来源：http://dali.zhoulong.xyz/Article/details/gtktywzyhp.html

[L08] 并发请求多个地址
来源：http://dali.hnqzz.top/Article/details/gtcuamrrzd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.chenlongwang.top/Article/details/gtlwzhtlxo.html

PHP:  curl_multi_init() 系列
来源：http://dali.zycfv.cn/Article/details/gtecgnjogp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gtngzsusqz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.0kj1m.cn/Article/details/gtvgydtmyp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.iojbl.cn/Article/details/gtgvoiqegn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shuidangran.top/Article/details/gtamycafzo.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.birdmap.top/Article/details/gtlcxgrxsd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhongyouzk.top/Article/details/gtpohavnhq.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtxpievhrd.html

M. 命令行 / 进程 / 环境
来源：http://dali.jlsjyb.cn/Article/details/gtybzjjqdi.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtngncuuzo.html

[M01] 读取命令行参数
来源：http://dali.yueranfly.top/Article/details/gtwbnkhtlo.html

Py:   sys.argv[1:]
来源：http://dali.dashuyun.cn/Article/details/gtbvbdammf.html

PHP:  $argv;  $argc;
来源：http://dali.jinqigufen.top/Article/details/gtlwbjasjg.html

JS:   process.argv.slice(2)
来源：http://dali.gogol.net.cn/Article/details/gtohxddfya.html

TS:   process.argv.slice(2)
来源：http://dali.hnxiangtu.top/Article/details/gtkrgvtgcs.html

Java: args 数组（main 方法参数）
来源：http://dali.yueranfly.top/Article/details/gtcdniycrp.html

Go:   os.Args[1:]
来源：http://dali.316326.xyz/Article/details/gtahagvpjp.html

Ruby: ARGV
来源：http://dali.0kj1m.cn/Article/details/gtjlfjlsql.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sufxvd.cn/Article/details/gtumiimmpr.html

[M02] 读取环境变量
来源：http://dali.gotoacloud.top/Article/details/gtdkskxbfu.html

Py:   os.environ.get("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gtbudkkwha.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cdnleiting.top/Article/details/gtbqtoxtfg.html

JS:   process.env.HOME
来源：http://dali.pengpengdd.cyou/Article/details/gtnstbohxc.html

TS:   process.env.HOME
来源：http://dali.tian-w.cn/Article/details/gttzkxtttw.html

Java: System.getenv("HOME")
来源：http://dali.ydzc1.top/Article/details/gtjtwjzpsv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cqqwz.cn/Article/details/gtuiphvqfs.html

Ruby: ENV["HOME"]
来源：http://dali.hfpthk.cn/Article/details/gthbtgaobo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gthuebmldh.html

[M03] 执行外部命令
来源：http://dali.zhongyouzk.top/Article/details/gtvyugcuwi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.iojbl.cn/Article/details/gtawmlfopo.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hywenlv.cn/Article/details/gtpipkrllm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.dashuyun.cn/Article/details/gtwhbrlxwv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuanzx.com/Article/details/gtuhxmcyeb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zycfv.cn/Article/details/gtuozzuakz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.havefunace.top/Article/details/gtjplakhxh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hnxiangtu.top/Article/details/gtyxmfuvay.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nanxinkj.top/Article/details/gtgeoxygba.html

[M04] 获取当前工作目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsltzjgmy.html

Py:   os.getcwd()
来源：http://dali.xziqi.cn/Article/details/gthmoxsoof.html

PHP:  getcwd();
来源：http://dali.yonumen.top/Article/details/gtszgbewhu.html

JS:   process.cwd()
来源：http://dali.zhengqikj.top/Article/details/gtiywehdds.html

TS:   process.cwd()
来源：http://dali.yvedp.cn/Article/details/gtfemfdhtj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jiagoushi.top/Article/details/gtobhprlbi.html

Go:   os.Getwd()
来源：http://dali.shangyingyoupin.top/Article/details/gtoyryarsg.html

Ruby: Dir.pwd
来源：http://dali.xziqi.cn/Article/details/gtunijnagm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.316326.xyz/Article/details/gtwhgrfcay.html

[M05] 设置退出码
来源：http://dali.yonumen.top/Article/details/gtdymvrkrb.html

Py:   sys.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtqgfcoqyr.html

PHP:  exit(1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzheaseay.html

JS:   process.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gtdmvebnvg.html

TS:   process.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gtpmhbboza.html

Java: System.exit(1)
来源：http://dali.hnqzz.top/Article/details/gtkdhkoxnv.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtlivqmvmm.html

Ruby: exit 1
来源：http://dali.aibaodan.cn/Article/details/gtedeeownm.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shangyingyoupin.top/Article/details/gtplfkgczt.html

[M06] 向标准错误输出
来源：http://dali.hywenlv.cn/Article/details/gtyvarqxpg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hnxiangtu.top/Article/details/gtcusmionl.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shanyushiyangtech.top/Article/details/gtgarveunm.html

JS:   console.error("err")
来源：http://dali.hongshengwenyu.top/Article/details/gtiwhnyltk.html

TS:   console.error("err")
来源：http://dali.smart0.xyz/Article/details/gthrzehmzp.html

Java: System.err.println("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gtkncenhdu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.aibaodan.cn/Article/details/gtctyfbrde.html

Ruby: warn "err"
来源：http://dali.haohaochexian.top/Article/details/gtwzjhehmj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yueranfly.top/Article/details/gtscdlippf.html

[M07] 判断是否为主入口
来源：http://dali.shanyushiyangtech.top/Article/details/gtvbernztf.html

Py:   if __name__ == "__main__":
来源：http://dali.vqdsnc.cn/Article/details/gtiwdpijav.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hnxiangtu.top/Article/details/gtdgclezji.html

JS:   require.main === module
来源：http://dali.zhengqikj.top/Article/details/gttvbkzqwa.html

TS:   require.main === module
来源：http://dali.xylfe.cn/Article/details/gtjtijpfno.html

Java: public static void main(String[] args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvmmedden.html

Go:   func main()
来源：http://dali.mhx1999.top/Article/details/gtgfrstnvc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.vqdsnc.cn/Article/details/gtlsaongxj.html

C#:   static void Main(string[] args)
来源：http://dali.shangyingyoupin.top/Article/details/gthsnftnax.html

[M08] 获取系统与运行时信息
来源：http://dali.bjfxy.top/Article/details/gtwlyqesoe.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinghuilouyu.cn/Article/details/gtpdhfgfbk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.fengsongda.top/Article/details/gtcexomcby.html

JS:   process.platform;  process.version
来源：http://dali.zdqjudy.top/Article/details/gtsvapbhpb.html

TS:   process.platform;  process.version
来源：http://dali.hnqzz.top/Article/details/gtzhhgaduj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yj202588.top/Article/details/gtwduiyzxd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gzhubu.top/Article/details/gtdasvbvyq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gotoacloud.top/Article/details/gtephkezgd.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gotoacloud.top/Article/details/gttbhivmyh.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtnzeimuod.html

N. 数据结构与算法
来源：http://dali.chenlongwang.top/Article/details/gtyalrlvoz.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtvavhbame.html

[N01] 二分查找（有序数组）
来源：http://dali.cheryme.top/Article/details/gtedlimzat.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.mhx1999.top/Article/details/gthxbnnary.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jlsjyb.cn/Article/details/gtkpytuciz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yonumen.top/Article/details/gtbdsjzhyp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuxming.cn/Article/details/gtbkjedqwe.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gzhubu.top/Article/details/gtxdezwalo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtxlxmytrv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hysaishi.cn/Article/details/gtnhhaqdtm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gtqlpxxvcz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ydzc1.top/Article/details/gtkaterwms.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dashuyun.cn/Article/details/gtyvpreeov.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jiagoushi.top/Article/details/gtrncyopuu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.vqdsnc.cn/Article/details/gtbburbycd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sufxvd.cn/Article/details/gtnnprdtpt.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jqgfzy.top/Article/details/gtqgwtxhqy.html

Go:   slices.Sort(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtbpumiosl.html

Ruby: arr.sort
来源：http://dali.guowangkeji.top/Article/details/gtdxupwujj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gogol.net.cn/Article/details/gtxbissbvq.html

[N03] 快速排序（分治示例）
来源：http://dali.andypj.xyz/Article/details/gthhlootgm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hnxiangtu.top/Article/details/gtlvcgfslz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jianghu66.top/Article/details/gtqrkwvmzg.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhengqikj.top/Article/details/gtflywdvgw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwtrhfxoj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jyoumei.cn/Article/details/gtlmmflrdm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenjidiqi.icu/Article/details/gtznuasstl.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jqgfzy.top/Article/details/gtnjpbkfua.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzjxcplts.html

[N04] 斐波那契数列
来源：http://dali.xuetiantiany.cn/Article/details/gtqcnzpcsw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.chenzaomai.com/Article/details/gtrlapwevh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.c1oappe.top/Article/details/gtcrlepfsm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgufenzy.top/Article/details/gtrjuvxqpl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gtvwusqoda.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jianghu66.top/Article/details/gtiekercqu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jyoumei.cn/Article/details/gtdsciieso.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.birdmap.top/Article/details/gtwncststz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zycfv.cn/Article/details/gtwwpfobaf.html

[N05] 最大公约数
来源：http://dali.gogol.net.cn/Article/details/gtkwpkcwni.html

Py:   math.gcd(a, b)
来源：http://dali.snrcjt.cn/Article/details/gtxcjycama.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hysaishi.cn/Article/details/gtfkxpmbzj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yvedp.cn/Article/details/gtzwyourfc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.andypj.xyz/Article/details/gtncfmcmnz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yj20258.top/Article/details/gtmzhurbke.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cashguo.top/Article/details/gtgjjkomho.html

Ruby: a.gcd(b)
来源：http://dali.dianchejie.cn/Article/details/gtvohcbpfs.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gogol.net.cn/Article/details/gtxwpzzaqf.html

[N06] 判断回文字符串
来源：http://dali.tanke756.top/Article/details/gtwdawuvew.html

Py:   s == s[::-1]
来源：http://dali.zycfv.cn/Article/details/gtumrvbnpb.html

PHP:  $s === strrev($s);
来源：http://dali.sweek.top/Article/details/gtckllkupt.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gtklpwmdjn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gtmkczeoev.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.andypj.xyz/Article/details/gtquliyqoj.html

Go:   // 双指针从两端比较
来源：http://dali.svipenyu.cn/Article/details/gtbxdothts.html

Ruby: s == s.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gtpqwavipl.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xuetiantiany.cn/Article/details/gtnsnddttj.html

[N07] 两数之和（返回下标）
来源：http://dali.0kj1m.cn/Article/details/gthryfxfbz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.c1oappe.top/Article/details/gtbynnspbs.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shuidangran.top/Article/details/gtfdrsysne.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.tian-w.cn/Article/details/gtkfxikutm.html

TS:   // 手写 Map<string, number>
来源：http://dali.ywan-chungtsiang.top/Article/details/gttwkkqdrz.html

Java: // 手写 HashMap
来源：http://dali.c1oappe.top/Article/details/gtdqydnsou.html

Go:   // 手写 map[int]int
来源：http://dali.yj20258.top/Article/details/gtmkinuddi.html

Ruby: // 手写 Hash
来源：http://dali.gogol.net.cn/Article/details/gtjcqivvke.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yanxiufei.cn/Article/details/gtcczkbxgk.html

[N08] 生成全排列
来源：http://dali.ydzc1.top/Article/details/gtcushdraf.html

Py:   itertools.permutations(arr)
来源：http://dali.svipenyu.cn/Article/details/gtaxmqesly.html

PHP:  // 手写递归交换
来源：http://dali.shzxlz.cn/Article/details/gtjhtarbjg.html

JS:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gtmactxhzp.html

TS:   // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gtoujgeyjz.html

Java: // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gtsgdfkfcy.html

Go:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gtwulroevf.html

Ruby: arr.permutation.to_a
来源：http://dali.jiagoushi.top/Article/details/gtzwjtppek.html

C#:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gtxjicspcc.html

[N09] 栈与队列
来源：http://dali.redwolf501.top/Article/details/gtonntypeq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.dianchejie.cn/Article/details/gtvdufbulv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gtgadfdufb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jqgufenzy.top/Article/details/gthbnwoskd.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.quarkkingdee.top/Article/details/gtsplurlff.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.feifeiyinyue.top/Article/details/gtupkgmoez.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cqqwz.cn/Article/details/gtdswgpalw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yj20258.top/Article/details/gtvboygzfu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.316326.xyz/Article/details/gtddathpdb.html

[N10] 链表节点定义
来源：http://dali.yj20258.top/Article/details/gtxjrxlzft.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ppjwa.cn/Article/details/gtaozrvwoi.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.guowangkeji.top/Article/details/gtnxivjmie.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.daria6918.cn/Article/details/gtnuptymru.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ppjwa.cn/Article/details/gttxdnzuzv.html

Java: class Node { int v; Node next; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkzmsdqiv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yj20258888.top/Article/details/gtrvvqrpaz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hongshengwenyu.top/Article/details/gtguefufkw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.fzhhl.top/Article/details/gtgpxxcrmc.html

[N11] 二叉树中序遍历
来源：http://dali.c1oappe.top/Article/details/gtkydijcyl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sxryk.cn/Article/details/gtipnimoan.html

PHP:  // 手写递归函数
来源：http://dali.xuanzx.com/Article/details/gtarxvxoyt.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yongpay.top/Article/details/gtxsgoapqx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258.top/Article/details/gttzqvcvid.html

Java: // 手写递归
来源：http://dali.birdmap.top/Article/details/gtjntdbzfl.html

Go:   // 手写递归
来源：http://dali.iojbl.cn/Article/details/gtkduegcsd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.vqdsnc.cn/Article/details/gtwjukhvee.html

C#:   // 手写递归
来源：http://dali.tianlin.xyz/Article/details/gtytcsxcvn.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hongshengwenyu.top/Article/details/gtowclfxbl.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jiagoushi.top/Article/details/gtdatvwthr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.9152youxi.cn/Article/details/gtcepftrgx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sysykeji.top/Article/details/gtdaznpntu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.0kj1m.cn/Article/details/gtisdvrgqi.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nwbrower.top/Article/details/gttrgascse.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.mhx1999.top/Article/details/gtzjeblbvw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hfpthk.cn/Article/details/gtiwntztuh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.mhx1999.top/Article/details/gtoncgbihj.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtjnizrjca.html

O. 并发与异步
来源：http://dali.316326.xyz/Article/details/gtopqttmwr.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtkpaxtuhq.html

[O01] 启动一个线程
来源：http://dali.yuanzhike.top/Article/details/gtyhoahgoa.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yangfankeji.com/Article/details/gtoncpyswk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cdnleiting.top/Article/details/gtozcpdckq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yueranfly.top/Article/details/gtvfgylokn.html

TS:   // 同 JS
来源：http://dali.cqqwz.cn/Article/details/gtggwmoced.html

Java: new Thread(() -> f()).start()
来源：http://dali.havefunace.top/Article/details/gtfcaxvjjr.html

Go:   go f()
来源：http://dali.chenlongwang.top/Article/details/gtvibbyizg.html

Ruby: Thread.new { f }
来源：http://dali.yanxiufei.cn/Article/details/gtlbtabfli.html

C#:   Task.Run(() => F());
来源：http://dali.cheryme.top/Article/details/gtanoiqqer.html


<!-- 参考信息 -->