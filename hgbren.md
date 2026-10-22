代发 wailian999

[K06] 解析 URL 查询串
来源：http://dali.yuanzhike.top/Article/details/gtxrzmthzh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cdnleiting.top/Article/details/gthougzaoa.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yangfankeji.com/Article/details/gtzghhnvjc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtufhobsny.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tian-w.cn/Article/details/gtuyortytz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cucudq.cn/Article/details/gtsxkhgtom.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sweek.top/Article/details/gtebnyfevd.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.redwolf501.top/Article/details/gtuckawqdp.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gtwlptusnx.html

[K07] 进制转换
来源：http://dali.hywenlv.cn/Article/details/gtcydvkqva.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gtaanwptow.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xinyue.icu/Article/details/gtsyuupnqs.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cashguo.top/Article/details/gtidxlaqdn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gtmdwsmfue.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtanzoldzh.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nanxinkj.top/Article/details/gtocnorpad.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cqqwz.cn/Article/details/gtmzvnfjfg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtvhyriyrv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.havefunace.top/Article/details/gtjrspfpge.html

Py:   pickle.dumps(obj)
来源：http://dali.tian-w.cn/Article/details/gtlwaoxbkp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gzhubu.top/Article/details/gttuyahafv.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gzhubu.top/Article/details/gtobdidrge.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jlsjyb.cn/Article/details/gtwwjxfoao.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jqgfzy.top/Article/details/gtdqkyvidj.html

Go:   encoding/gob
来源：http://dali.ybcxt.top/Article/details/gtfczukoao.html

Ruby: Marshal.dump(obj)
来源：http://dali.fzhhl.top/Article/details/gtlcnmwhsz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ybcxt.top/Article/details/gtfppydcss.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtzobsizdu.html

L. 网络请求
来源：http://dali.hywenlv.cn/Article/details/gtgfsgnjen.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtyctrkfqq.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gtnbdwgxkz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.0kj1m.cn/Article/details/gttnbzajyo.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shzxlz.cn/Article/details/gtwmmbxrva.html

JS:   await fetch(url)
来源：http://dali.xziqi.cn/Article/details/gtmycwtapo.html

TS:   await fetch(url)
来源：http://dali.xinyue.icu/Article/details/gtskyfuwcz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hywenlv.cn/Article/details/gtocstlyin.html

Go:   resp, err := http.Get(url)
来源：http://dali.pengpengdd.cyou/Article/details/gtogggvmxr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sxryk.cn/Article/details/gtibihywxr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ydzc1.top/Article/details/gtwjehsjbs.html

[L02] 发送 POST JSON
来源：http://dali.sysykeji.top/Article/details/gtgivyrrqe.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.tian-w.cn/Article/details/gtyerebmca.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ppjwa.cn/Article/details/gtqrvmsnul.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xinyue.icu/Article/details/gtniztijpv.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.quarkkingdee.top/Article/details/gtjzvxqfje.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.nanxuanxn.top/Article/details/gtpopfibxg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.guannengcc.top/Article/details/gthixvhvwy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hammf.cn/Article/details/gtenwzeruz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cucudq.cn/Article/details/gtghjscjet.html

[L03] 设置自定义请求头
来源：http://dali.sysykeji.top/Article/details/gtualsqlei.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.redwolf501.top/Article/details/gtrprbwmkj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gaohongyu789.top/Article/details/gtnolawmgm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aibaodan.cn/Article/details/gthgozvomf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fzhhl.top/Article/details/gtatgnfifr.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinghuilouyu.cn/Article/details/gtnekgcwio.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.aibaodan.cn/Article/details/gtkzuxemho.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.andypj.xyz/Article/details/gtvorlxscf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yanxiufei.cn/Article/details/gtannbwqge.html

[L04] 设置超时
来源：http://dali.andypj.xyz/Article/details/gtcchgcbsl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.bjfxy.top/Article/details/gtcbzzoxwg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yuanzhike.top/Article/details/gtjrhuhrli.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ydzc1.top/Article/details/gtivsjxjnh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jyoumei.cn/Article/details/gtoodpgbda.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.bjfxy.top/Article/details/gthcvuzzur.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zdqjudy.top/Article/details/gtfaltfhws.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cucudq.cn/Article/details/gtdsqnegbj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jlsjyb.cn/Article/details/gttstskpxs.html

[L05] 上传文件（multipart）
来源：http://dali.shanyushiyangtech.top/Article/details/gtewplgxqa.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ppjwa.cn/Article/details/gtmvmpbxrm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.316326.xyz/Article/details/gtnxnnfjtr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinghuilouyu.cn/Article/details/gtmojcxqst.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yanxiufei.cn/Article/details/gtvgucscak.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.daria6918.cn/Article/details/gtmppnjqjk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.dashuyun.cn/Article/details/gtbhlzlyjx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hammf.cn/Article/details/gtvaeckqsv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtecxqgypx.html

[L06] 解析响应为 JSON
来源：http://dali.gaohongyu789.top/Article/details/gtosdzkaaw.html

Py:   resp.json()
来源：http://dali.dianchejie.cn/Article/details/gtomuoyzhc.html

PHP:  json_decode($body, true);
来源：http://dali.bjfxy.top/Article/details/gtcnllrzez.html

JS:   await resp.json()
来源：http://dali.sufxvd.cn/Article/details/gthczcxvlf.html

TS:   await resp.json()
来源：http://dali.wangdashe.top/Article/details/gtpxqldamm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hysaishi.cn/Article/details/gtnrnpzvfx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.haohaochexian.top/Article/details/gtipofxetm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.chenzaomai.com/Article/details/gtmvzkzobt.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cheryme.top/Article/details/gtnfvldioa.html

[L07] 处理 HTTP 状态码
来源：http://dali.cheryme.top/Article/details/gtqnuhagxv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nwbrower.top/Article/details/gtnaohnfez.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.havefunace.top/Article/details/gtexihzipe.html

JS:   resp.ok;  resp.status
来源：http://dali.zdqjudy.top/Article/details/gtrokvlyol.html

TS:   resp.ok;  resp.status
来源：http://dali.xziqi.cn/Article/details/gtapuqqmds.html

Java: resp.statusCode()
来源：http://dali.nwbrower.top/Article/details/gtjqlgrsqm.html

Go:   resp.StatusCode
来源：http://dali.yvedp.cn/Article/details/gtbomiqigk.html

Ruby: resp.code.to_i
来源：http://dali.yueranfly.top/Article/details/gtiiaijgoo.html

C#:   (int)resp.StatusCode
来源：http://dali.shzxlz.cn/Article/details/gtkrnpxilb.html

[L08] 并发请求多个地址
来源：http://dali.chenlongwang.top/Article/details/gtbkzxrkbc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cucudq.cn/Article/details/gtdmwceqih.html

PHP:  curl_multi_init() 系列
来源：http://dali.316326.xyz/Article/details/gtxnskbyxk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hfpthk.cn/Article/details/gtvaeaeirw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gtibjmwprn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.bjfxy.top/Article/details/gtwbxawrun.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhixingplan.top/Article/details/gtzhohdpcx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shangyingyoupin.top/Article/details/gtesexocaq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttwkfqfic.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtthxtmvhb.html

M. 命令行 / 进程 / 环境
来源：http://dali.aibaodan.cn/Article/details/gtkmmomjzz.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtdonibasm.html

[M01] 读取命令行参数
来源：http://dali.chenzaomai.com/Article/details/gtmslvxjfp.html

Py:   sys.argv[1:]
来源：http://dali.jlsjyb.cn/Article/details/gtdmynaplm.html

PHP:  $argv;  $argc;
来源：http://dali.cucudq.cn/Article/details/gtmgfxqhrk.html

JS:   process.argv.slice(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwszjzypy.html

TS:   process.argv.slice(2)
来源：http://dali.yonumen.top/Article/details/gtkdkhxppo.html

Java: args 数组（main 方法参数）
来源：http://dali.redwolf501.top/Article/details/gtcxboejqo.html

Go:   os.Args[1:]
来源：http://dali.zhengqikj.top/Article/details/gtmteoarlo.html

Ruby: ARGV
来源：http://dali.bjfxy.top/Article/details/gtninvxaxd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cqqwz.cn/Article/details/gtqzazywwn.html

[M02] 读取环境变量
来源：http://dali.nwbrower.top/Article/details/gtcsbdqfst.html

Py:   os.environ.get("HOME")
来源：http://dali.andypj.xyz/Article/details/gtyyzjqgth.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.andypj.xyz/Article/details/gtgjpsorpb.html

JS:   process.env.HOME
来源：http://dali.xinyue.icu/Article/details/gtrrjgdoln.html

TS:   process.env.HOME
来源：http://dali.chenlongwang.top/Article/details/gtuhlxuxjk.html

Java: System.getenv("HOME")
来源：http://dali.jqgfzy.top/Article/details/gtbecuscmy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.tian-w.cn/Article/details/gtjwffjqkq.html

Ruby: ENV["HOME"]
来源：http://dali.ybcxt.top/Article/details/gtyzcdgtzg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.snrcjt.cn/Article/details/gtnsbwhavy.html

[M03] 执行外部命令
来源：http://dali.quarkkingdee.top/Article/details/gthzxzqznk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenlongwang.top/Article/details/gtschufazo.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.quarkkingdee.top/Article/details/gtyszaghmu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.c1oappe.top/Article/details/gtbsjsiugf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.mhx1999.top/Article/details/gtnuskqpao.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shanyushiyangtech.top/Article/details/gtbzrhpqta.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.9152youxi.cn/Article/details/gtiemlrhvb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenzaomai.com/Article/details/gtpnabwuvk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.dashuyun.cn/Article/details/gtipqmmwyk.html

[M04] 获取当前工作目录
来源：http://dali.nanxuanxn.top/Article/details/gtmktgtsva.html

Py:   os.getcwd()
来源：http://dali.xziqi.cn/Article/details/gtgextgxvx.html

PHP:  getcwd();
来源：http://dali.jiagoushi.top/Article/details/gtrlyjtvwb.html

JS:   process.cwd()
来源：http://dali.aibaodan.cn/Article/details/gtefowyvtw.html

TS:   process.cwd()
来源：http://dali.0kj1m.cn/Article/details/gtlgbvmxjd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.wangdashe.top/Article/details/gtkoacwuvt.html

Go:   os.Getwd()
来源：http://dali.c1oappe.top/Article/details/gtjmnmkhfj.html

Ruby: Dir.pwd
来源：http://dali.redwolf501.top/Article/details/gtngluyjrr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.fzhhl.top/Article/details/gtkfgxoyia.html

[M05] 设置退出码
来源：http://dali.jianghu66.top/Article/details/gtmykzobax.html

Py:   sys.exit(1)
来源：http://dali.cheryme.top/Article/details/gtfqajbbpt.html

PHP:  exit(1);
来源：http://dali.fengsongda.top/Article/details/gtbcwpbybq.html

JS:   process.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtzyfivayx.html

TS:   process.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkexznerc.html

Java: System.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gtypsjtewg.html

Go:   os.Exit(1)
来源：http://dali.yvedp.cn/Article/details/gtqhxfxnuu.html

Ruby: exit 1
来源：http://dali.zhongyouzk.top/Article/details/gtjgjeecxs.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhiwuduotai.top/Article/details/gtopzaynuv.html

[M06] 向标准错误输出
来源：http://dali.jlsjyb.cn/Article/details/gtdzyynfpu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.pengpengdd.cyou/Article/details/gtecnynmuh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yuanzhike.top/Article/details/gthlgrujfp.html

JS:   console.error("err")
来源：http://dali.feifeiyinyue.top/Article/details/gtioeldcvr.html

TS:   console.error("err")
来源：http://dali.nanxinkj.top/Article/details/gtrhyffnkj.html

Java: System.err.println("err")
来源：http://dali.jiagoushi.top/Article/details/gtfjojkqto.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinqigufen.top/Article/details/gtduqgqwxo.html

Ruby: warn "err"
来源：http://dali.birdmap.top/Article/details/gtmcpcrjuv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.chenlongwang.top/Article/details/gtbuwzofvj.html

[M07] 判断是否为主入口
来源：http://dali.yj20258888.top/Article/details/gtnjyhuyvt.html

Py:   if __name__ == "__main__":
来源：http://dali.chenjidiqi.icu/Article/details/gtnkhxvaiy.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.tanke756.top/Article/details/gtclaneool.html

JS:   require.main === module
来源：http://dali.yangfankeji.com/Article/details/gtcveagrpb.html

TS:   require.main === module
来源：http://dali.jinqigfzy.top/Article/details/gtuhivzsur.html

Java: public static void main(String[] args)
来源：http://dali.quarkkingdee.top/Article/details/gtkbgbeobz.html

Go:   func main()
来源：http://dali.chenlongwang.top/Article/details/gtoarbnujx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqkvhtpii.html

C#:   static void Main(string[] args)
来源：http://dali.dashuyun.cn/Article/details/gtodrfjnci.html

[M08] 获取系统与运行时信息
来源：http://dali.ivvv.top/Article/details/gtkkrlwljp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.9152youxi.cn/Article/details/gtcbuzghkz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yanxiufei.cn/Article/details/gtfqgeldjj.html

JS:   process.platform;  process.version
来源：http://dali.zdqjudy.top/Article/details/gtrpycctae.html

TS:   process.platform;  process.version
来源：http://dali.jyoumei.cn/Article/details/gtjaknazoa.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.havefunace.top/Article/details/gtqkveiitn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.andypj.xyz/Article/details/gtfqhpcwye.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.haohaochexian.top/Article/details/gtmymvydkj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.haohaochexian.top/Article/details/gtlwvwmaej.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtctquuijn.html

N. 数据结构与算法
来源：http://dali.sysykeji.top/Article/details/gtgdyojfot.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtypclwwbp.html

[N01] 二分查找（有序数组）
来源：http://dali.bjfxy.top/Article/details/gtqsvfbvyu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yj202588.top/Article/details/gtchaexmcp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cashguo.top/Article/details/gtwseqwatm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yueranfly.top/Article/details/gtxcufedls.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.svipenyu.cn/Article/details/gtbotxuzea.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtqkcgpiwg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtdjqxkxzm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xylfe.cn/Article/details/gtkhxbemny.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gtodkktyhi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.havefunace.top/Article/details/gtlariaiix.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shzxlz.cn/Article/details/gtqazzjxoz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cdnleiting.top/Article/details/gtzeqhmngl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guowangkeji.top/Article/details/gtflxnecsi.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sxryk.cn/Article/details/gtvwjnxsjr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.tianlin.xyz/Article/details/gtzewrglbf.html

Go:   slices.Sort(arr)
来源：http://dali.xylfe.cn/Article/details/gtxohvfdqc.html

Ruby: arr.sort
来源：http://dali.yvedp.cn/Article/details/gtiunglkyc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.0kj1m.cn/Article/details/gtkxxhwwlh.html

[N03] 快速排序（分治示例）
来源：http://dali.hysaishi.cn/Article/details/gtpecpuupz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hnxiangtu.top/Article/details/gtcelgwmnr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yonumen.top/Article/details/gtttursnqt.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258888.top/Article/details/gtjzipiajz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.quarkkingdee.top/Article/details/gtatfogusa.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yuxming.cn/Article/details/gtcldxyxak.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.aibaodan.cn/Article/details/gtoeotzrfm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tianlin.xyz/Article/details/gtkcbfaliq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenzaomai.com/Article/details/gtagrsvczf.html

[N04] 斐波那契数列
来源：http://dali.quarkkingdee.top/Article/details/gtltnvqpme.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zycfv.cn/Article/details/gtfafplghj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jlsjyb.cn/Article/details/gtxrswohhk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangshuangyany.cn/Article/details/gtoomdirne.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gtnxuypnly.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zdqjudy.top/Article/details/gttcdgezxf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shzxlz.cn/Article/details/gtwiroemka.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.wangdashe.top/Article/details/gtmmlioddd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhixingplan.top/Article/details/gthpgdzgew.html

[N05] 最大公约数
来源：http://dali.guowangkeji.top/Article/details/gtcjvpepnr.html

Py:   math.gcd(a, b)
来源：http://dali.daria6918.cn/Article/details/gtsvqzsika.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinqigufen.top/Article/details/gtdppechau.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.c1oappe.top/Article/details/gtlgvfyinx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gotoacloud.top/Article/details/gtqjbkfuts.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ppjwa.cn/Article/details/gtbbtujioy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shzxlz.cn/Article/details/gtuerwxfkc.html

Ruby: a.gcd(b)
来源：http://dali.svipenyu.cn/Article/details/gtktifnmeb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.daxiang520.top/Article/details/gteezouhkc.html

[N06] 判断回文字符串
来源：http://dali.havefunace.top/Article/details/gthwoknniy.html

Py:   s == s[::-1]
来源：http://dali.cheryme.top/Article/details/gtagnzajbm.html

PHP:  $s === strrev($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbbglogbt.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gtsqtlzmuz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gtbhbqtyid.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.quarkkingdee.top/Article/details/gtnbxkgfzy.html

Go:   // 双指针从两端比较
来源：http://dali.zhengqikj.top/Article/details/gtjburarqh.html

Ruby: s == s.reverse
来源：http://dali.cashguo.top/Article/details/gtwotivicr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gaohongyu789.top/Article/details/gtdikocqnw.html

[N07] 两数之和（返回下标）
来源：http://dali.xziqi.cn/Article/details/gtgbpmbmif.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.havefunace.top/Article/details/gtzhiagngk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yanxiufei.cn/Article/details/gtpobkvgpb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shzxlz.cn/Article/details/gtxnzskrvu.html

TS:   // 手写 Map<string, number>
来源：http://dali.cheryme.top/Article/details/gtiflfvjya.html

Java: // 手写 HashMap
来源：http://dali.bjfxy.top/Article/details/gtrdpqplej.html

Go:   // 手写 map[int]int
来源：http://dali.gaohongyu789.top/Article/details/gtcayxbpck.html

Ruby: // 手写 Hash
来源：http://dali.jinqigufen.top/Article/details/gtqswhiqtm.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.quarkkingdee.top/Article/details/gtkzqftivb.html

[N08] 生成全排列
来源：http://dali.havefunace.top/Article/details/gtppbfstqw.html

Py:   itertools.permutations(arr)
来源：http://dali.xuanzx.com/Article/details/gtztnfedky.html

PHP:  // 手写递归交换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjyigbkyq.html

JS:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gtktckphsv.html

TS:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gtyknwpcug.html

Java: // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gtvboregvw.html

Go:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtxowfmlxu.html

Ruby: arr.permutation.to_a
来源：http://dali.jinqigufen.top/Article/details/gtvbhpempk.html

C#:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gtwuftguvu.html

[N09] 栈与队列
来源：http://dali.yueranfly.top/Article/details/gtywravuok.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.kuanghao11.cn/Article/details/gtbgsunpos.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.nanxuanxn.top/Article/details/gtmwiilpgn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ppjwa.cn/Article/details/gtxfzqdxwl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shuidangran.top/Article/details/gtgfbqpkly.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.tanke756.top/Article/details/gttmuzrkwe.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yonumen.top/Article/details/gtcucswlsz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gtubcrfewy.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jianghu66.top/Article/details/gtdlpxonxu.html

[N10] 链表节点定义
来源：http://dali.yj20258888.top/Article/details/gtsewsoqbz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjujbipnz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhoulong.xyz/Article/details/gtmpmnljql.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtngpdcjms.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtycczoxcj.html

Java: class Node { int v; Node next; }
来源：http://dali.guowangkeji.top/Article/details/gtsgvbuccb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.nanxuanxn.top/Article/details/gtoxhhzzvg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gzhubu.top/Article/details/gtvkzfsdjd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hywenlv.cn/Article/details/gtywhspuzd.html

[N11] 二叉树中序遍历
来源：http://dali.xylfe.cn/Article/details/gthklmtjdj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hnxiangtu.top/Article/details/gtxuucxvnk.html

PHP:  // 手写递归函数
来源：http://dali.jinqigufen.top/Article/details/gtzyarfneb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.fzhhl.top/Article/details/gtjbxganfw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ydzc1.top/Article/details/gtvkkxhjeo.html

Java: // 手写递归
来源：http://dali.meibo888.top/Article/details/gtfvdgcnmp.html

Go:   // 手写递归
来源：http://dali.nanxuanxn.top/Article/details/gtokwfhihy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.guowangkeji.top/Article/details/gtpukmafwz.html

C#:   // 手写递归
来源：http://dali.meibo888.top/Article/details/gtkyfkklab.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xziqi.cn/Article/details/gtghtnvwfc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.bjfxy.top/Article/details/gtyooqzezd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shzxlz.cn/Article/details/gtdgmzjldb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guannengcc.top/Article/details/gttxexdogg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.snrcjt.cn/Article/details/gtpdmmxkza.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ybcxt.top/Article/details/gtigikmbak.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.meibo888.top/Article/details/gtgctslclq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.chenzaomai.com/Article/details/gtozikonca.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hywenlv.cn/Article/details/gtdydwzewd.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtsgvxmtzn.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gtmpnghwhx.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtolcrybuw.html

[O01] 启动一个线程
来源：http://dali.jinghuilouyu.cn/Article/details/gtkjngkdjr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ivvv.top/Article/details/gtuodwzipn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yueranfly.top/Article/details/gtdhxiqsxf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hongshengwenyu.top/Article/details/gtryivymkv.html

TS:   // 同 JS
来源：http://dali.aizwys.cn/Article/details/gtvgfaautd.html

Java: new Thread(() -> f()).start()
来源：http://dali.vqdsnc.cn/Article/details/gtuqcfmfsd.html

Go:   go f()
来源：http://dali.shanyushiyangtech.top/Article/details/gtdfvlzuch.html

Ruby: Thread.new { f }
来源：http://dali.ehwqpu.com/Article/details/gthxcoocdh.html

C#:   Task.Run(() => F());
来源：http://dali.jianghu66.top/Article/details/gtecvynuzl.html


<!-- 参考信息 -->