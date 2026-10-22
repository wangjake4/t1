代发 wailian999

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhengqikj.top/Article/details/gtxsnaloyz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yj20258888.top/Article/details/gtfgvknyyg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhiwuduotai.top/Article/details/gtrjmbfbqv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnyaeegjr.html

[K06] 解析 URL 查询串
来源：http://dali.gzhubu.top/Article/details/gtqxajocvs.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiderqerx.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yuxming.cn/Article/details/gtobngdgiz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yueranfly.top/Article/details/gtucdtkghy.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttyromxuh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.snrcjt.cn/Article/details/gtlxsqcxcj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtctwhilxr.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.feifeiyinyue.top/Article/details/gtarzukylc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfzvtbfxk.html

[K07] 进制转换
来源：http://dali.mhx1999.top/Article/details/gtmhxknosu.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtktgspcsj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hfpthk.cn/Article/details/gthwegtled.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtoqbpwzmx.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gttaytsmuv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gtaazduqkx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zycfv.cn/Article/details/gtcqrzsgmw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.haohaochexian.top/Article/details/gtpckaqqmk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gtbazvhkai.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cucudq.cn/Article/details/gthqegdpon.html

Py:   pickle.dumps(obj)
来源：http://dali.zhixingplan.top/Article/details/gtrlzzqtzv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cucudq.cn/Article/details/gtkhfiudjw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jyoumei.cn/Article/details/gthkcazqeq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.mhx1999.top/Article/details/gtokjhkjav.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xylfe.cn/Article/details/gtmtkknnum.html

Go:   encoding/gob
来源：http://dali.jianghu66.top/Article/details/gtemhjawmd.html

Ruby: Marshal.dump(obj)
来源：http://dali.cheryme.top/Article/details/gtzuzkrbyd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hfpthk.cn/Article/details/gtcpeapsrq.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtshastbjx.html

L. 网络请求
来源：http://dali.dianchejie.cn/Article/details/gtzglinlcm.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtjhnycysi.html

[L01] 发送 GET 请求
来源：http://dali.cdnleiting.top/Article/details/gtzckmikfk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj202588.top/Article/details/gtjhsyfgfy.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.snrcjt.cn/Article/details/gtqwgbowvg.html

JS:   await fetch(url)
来源：http://dali.andypj.xyz/Article/details/gtqfjvfgdt.html

TS:   await fetch(url)
来源：http://dali.yj20258888.top/Article/details/gtawphuiit.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jyoumei.cn/Article/details/gtokbkmrun.html

Go:   resp, err := http.Get(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjwaqxenu.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jiagoushi.top/Article/details/gtpowdkvsv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.birdmap.top/Article/details/gtypyuufib.html

[L02] 发送 POST JSON
来源：http://dali.zhiwuduotai.top/Article/details/gtiroennva.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinqigufen.top/Article/details/gttlwctmxk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jiagoushi.top/Article/details/gtxcciebmh.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgufenzy.top/Article/details/gtcdwfgldb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangshuangyany.cn/Article/details/gtfmxrgrju.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.tian-w.cn/Article/details/gtlxtfphca.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cucudq.cn/Article/details/gtsrmrizwq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhixingplan.top/Article/details/gtydyvpdat.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cashguo.top/Article/details/gtgdqucztf.html

[L03] 设置自定义请求头
来源：http://dali.jinqigfzy.top/Article/details/gtzblhvfrs.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.0kj1m.cn/Article/details/gtebreloyy.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jqgufenzy.top/Article/details/gtpwnbdkyv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhoulong.xyz/Article/details/gtwdtwymbh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigfzy.top/Article/details/gthupatzlg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jlsjyb.cn/Article/details/gtvngvdwij.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gzhubu.top/Article/details/gtjnrykebk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.wangshuangyany.cn/Article/details/gtaenjderb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yangfankeji.com/Article/details/gtgezirhuk.html

[L04] 设置超时
来源：http://dali.gogol.net.cn/Article/details/gtyczbzazv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.havefunace.top/Article/details/gtmnnvsqbq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sufxvd.cn/Article/details/gtgevfhqfs.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcfdxogwy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xziqi.cn/Article/details/gtrldhdnby.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hysaishi.cn/Article/details/gtprrzlmjw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.chenjidiqi.icu/Article/details/gtqfrmnbrt.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yangfankeji.com/Article/details/gtzqcupdwy.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.andypj.xyz/Article/details/gtntfgkldu.html

[L05] 上传文件（multipart）
来源：http://dali.cashguo.top/Article/details/gtcaurlgtu.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrqjynucr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhongyouzk.top/Article/details/gtqpwjinfr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinghuilouyu.cn/Article/details/gtrrwswpfs.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cucudq.cn/Article/details/gtztdwzsgr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ywan-chungtsiang.top/Article/details/gtydaavpzp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cashguo.top/Article/details/gthojajdzt.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.dashuyun.cn/Article/details/gtiehmydwl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtghsuazhl.html

[L06] 解析响应为 JSON
来源：http://dali.ivvv.top/Article/details/gtjqvhcyny.html

Py:   resp.json()
来源：http://dali.c1oappe.top/Article/details/gtebgjbbbe.html

PHP:  json_decode($body, true);
来源：http://dali.nanxuanxn.top/Article/details/gtoiobckex.html

JS:   await resp.json()
来源：http://dali.wangshuangyany.cn/Article/details/gtsbsruwxq.html

TS:   await resp.json()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfygdjndy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xuetiantiany.cn/Article/details/gtgnqgwqmt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.havefunace.top/Article/details/gtnmbvhjtv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.daria6918.cn/Article/details/gtkrpasndb.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ppjwa.cn/Article/details/gtbefjplrd.html

[L07] 处理 HTTP 状态码
来源：http://dali.meibo888.top/Article/details/gtldbrgrkq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sweek.top/Article/details/gtpllpteyi.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jqgufenzy.top/Article/details/gtyzunsbxw.html

JS:   resp.ok;  resp.status
来源：http://dali.jinqigfzy.top/Article/details/gtpvtxplym.html

TS:   resp.ok;  resp.status
来源：http://dali.cucudq.cn/Article/details/gtzfvyccgk.html

Java: resp.statusCode()
来源：http://dali.birdmap.top/Article/details/gtuasyqznb.html

Go:   resp.StatusCode
来源：http://dali.pycfn.com/Article/details/gtehcxyfhi.html

Ruby: resp.code.to_i
来源：http://dali.shanyushiyangtech.top/Article/details/gtziwfbrav.html

C#:   (int)resp.StatusCode
来源：http://dali.nanxuanxn.top/Article/details/gtadhufuwx.html

[L08] 并发请求多个地址
来源：http://dali.fengsongda.top/Article/details/gttiycengg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gotoacloud.top/Article/details/gtyrxyviwf.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhengqikj.top/Article/details/gtkyzpqqii.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.meibo888.top/Article/details/gtrwiaoejk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuxming.cn/Article/details/gtbxgljzqz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sysykeji.top/Article/details/gtaskgsawk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gzhubu.top/Article/details/gtpmfxdlgl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zdqjudy.top/Article/details/gtkbgqibgn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hammf.cn/Article/details/gtdgpmuoda.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtyhgtebkm.html

M. 命令行 / 进程 / 环境
来源：http://dali.sysykeji.top/Article/details/gtnqnlbqrj.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gthhfgbems.html

[M01] 读取命令行参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtjxeuwggj.html

Py:   sys.argv[1:]
来源：http://dali.snrcjt.cn/Article/details/gtbauvfbyt.html

PHP:  $argv;  $argc;
来源：http://dali.hammf.cn/Article/details/gtudhiyzhg.html

JS:   process.argv.slice(2)
来源：http://dali.birdmap.top/Article/details/gtotmcmpjl.html

TS:   process.argv.slice(2)
来源：http://dali.chenzaomai.com/Article/details/gtvdmgoasg.html

Java: args 数组（main 方法参数）
来源：http://dali.chenzaomai.com/Article/details/gtgpcybfeu.html

Go:   os.Args[1:]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtluhxorha.html

Ruby: ARGV
来源：http://dali.sysykeji.top/Article/details/gtdmwkymhm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ppjwa.cn/Article/details/gtaynpxitf.html

[M02] 读取环境变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtxgybudvi.html

Py:   os.environ.get("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gtuccfqllp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.snrcjt.cn/Article/details/gtvfadgoml.html

JS:   process.env.HOME
来源：http://dali.nanxuanxn.top/Article/details/gtftagapgz.html

TS:   process.env.HOME
来源：http://dali.cdnleiting.top/Article/details/gtwvrkzvbo.html

Java: System.getenv("HOME")
来源：http://dali.316326.xyz/Article/details/gtlcvtatwu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.316326.xyz/Article/details/gtqksmtbga.html

Ruby: ENV["HOME"]
来源：http://dali.yj20258.top/Article/details/gtoehvhpeu.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ybcxt.top/Article/details/gtfmqucchy.html

[M03] 执行外部命令
来源：http://dali.feifeiyinyue.top/Article/details/gtbxgnxpgn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.meibo888.top/Article/details/gtfkbtowvi.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hysaishi.cn/Article/details/gtolevvtox.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxinkj.top/Article/details/gtjmtvopiy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.bjfxy.top/Article/details/gtxoumesei.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.kuanghao11.cn/Article/details/gtkarvqdzc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xylfe.cn/Article/details/gtuxxbhptq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.316326.xyz/Article/details/gtxyrrkmjv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.pycfn.com/Article/details/gtuyepqlqs.html

[M04] 获取当前工作目录
来源：http://dali.guowangkeji.top/Article/details/gthrcjolgp.html

Py:   os.getcwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnnyofggy.html

PHP:  getcwd();
来源：http://dali.chenzaomai.com/Article/details/gtryxabeck.html

JS:   process.cwd()
来源：http://dali.jyoumei.cn/Article/details/gtazoppzgl.html

TS:   process.cwd()
来源：http://dali.tian-w.cn/Article/details/gtqgxunhhi.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.quarkkingdee.top/Article/details/gtqvmqvxch.html

Go:   os.Getwd()
来源：http://dali.yuanzhike.top/Article/details/gtsowewnbo.html

Ruby: Dir.pwd
来源：http://dali.sxryk.cn/Article/details/gtksgfwbkm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cqqwz.cn/Article/details/gtyvcmfhyk.html

[M05] 设置退出码
来源：http://dali.redwolf501.top/Article/details/gtiqbqhwkw.html

Py:   sys.exit(1)
来源：http://dali.fengsongda.top/Article/details/gtgjhkrumz.html

PHP:  exit(1);
来源：http://dali.jinghuilouyu.cn/Article/details/gtnyooobug.html

JS:   process.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gtzqibelsw.html

TS:   process.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gtbzwpmpbm.html

Java: System.exit(1)
来源：http://dali.jianghu66.top/Article/details/gtubsoogau.html

Go:   os.Exit(1)
来源：http://dali.jinqigufen.top/Article/details/gtlkxklmvd.html

Ruby: exit 1
来源：http://dali.mhx1999.top/Article/details/gtjypphkvg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.316326.xyz/Article/details/gtppyrbsbx.html

[M06] 向标准错误输出
来源：http://dali.hammf.cn/Article/details/gtachxcqhr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yangfankeji.com/Article/details/gtrjdjqxtb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shanyushiyangtech.top/Article/details/gtakafwvrq.html

JS:   console.error("err")
来源：http://dali.c1oappe.top/Article/details/gtdcmnidnd.html

TS:   console.error("err")
来源：http://dali.nanxinkj.top/Article/details/gtthjysqek.html

Java: System.err.println("err")
来源：http://dali.zhiwuduotai.top/Article/details/gtusxdowwl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjghndnua.html

Ruby: warn "err"
来源：http://dali.nanxuanxn.top/Article/details/gtusgwsvcx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtinqogdwp.html

[M07] 判断是否为主入口
来源：http://dali.yueranfly.top/Article/details/gtrhhrmapg.html

Py:   if __name__ == "__main__":
来源：http://dali.nanxinkj.top/Article/details/gtnkgmrrfm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdfjwdaax.html

JS:   require.main === module
来源：http://dali.jinyuanbaomall.cn/Article/details/gtowmjbyek.html

TS:   require.main === module
来源：http://dali.yuanzhike.top/Article/details/gtcwfanxxy.html

Java: public static void main(String[] args)
来源：http://dali.9152youxi.cn/Article/details/gtwjjgpdva.html

Go:   func main()
来源：http://dali.hnxiangtu.top/Article/details/gtfcdwvquk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.daxiang520.top/Article/details/gthyyxlfcu.html

C#:   static void Main(string[] args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpxidsgor.html

[M08] 获取系统与运行时信息
来源：http://dali.yanxiufei.cn/Article/details/gtjthsypzm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jlsjyb.cn/Article/details/gtdxzuaaxx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shangyingyoupin.top/Article/details/gtfnanksfe.html

JS:   process.platform;  process.version
来源：http://dali.yj20258888.top/Article/details/gtdgumzheu.html

TS:   process.platform;  process.version
来源：http://dali.yangfankeji.com/Article/details/gtwspqojev.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.daxiang520.top/Article/details/gtygptsjkt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.mhx1999.top/Article/details/gtnmjyiacq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.wangshuangyany.cn/Article/details/gtwxkvbkaj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hywenlv.cn/Article/details/gtdadsfzsz.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtfjrxgzpx.html

N. 数据结构与算法
来源：http://dali.yj20258.top/Article/details/gtxxlmmnta.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtocplzouy.html

[N01] 二分查找（有序数组）
来源：http://dali.yvedp.cn/Article/details/gtyrdbbvya.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtcojkhczw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gotoacloud.top/Article/details/gtsusyxaus.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gtqeberdom.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj202588.top/Article/details/gtkmdhnxid.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.birdmap.top/Article/details/gttwslwalc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtuddmbnha.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.guannengcc.top/Article/details/gtcuiiveve.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtvhrixgcj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nwbrower.top/Article/details/gtcjukntpq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nwbrower.top/Article/details/gtvfwlpoiz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.wangshuangyany.cn/Article/details/gtojraywne.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ivvv.top/Article/details/gtaycesobb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tian-w.cn/Article/details/gtrpdtzjsv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ivvv.top/Article/details/gtttpjwhwg.html

Go:   slices.Sort(arr)
来源：http://dali.yueranfly.top/Article/details/gtkfvktrck.html

Ruby: arr.sort
来源：http://dali.havefunace.top/Article/details/gthchkxoex.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ybcxt.top/Article/details/gteivkrbbu.html

[N03] 快速排序（分治示例）
来源：http://dali.dianchejie.cn/Article/details/gtttuwqjaf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ehwqpu.com/Article/details/gtbvhdjdes.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tian-w.cn/Article/details/gtpqxqyokd.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aizwys.cn/Article/details/gthbjgklqa.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.mhx1999.top/Article/details/gtbonqupef.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbzvqitbk.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.birdmap.top/Article/details/gtgqdzmjpc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.0kj1m.cn/Article/details/gtiayppogn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhoulong.xyz/Article/details/gtvqhkqpyy.html

[N04] 斐波那契数列
来源：http://dali.bjfxy.top/Article/details/gthiybqnup.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.mhx1999.top/Article/details/gtdwupnmyl.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jqgfzy.top/Article/details/gtcjdajjlk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ppjwa.cn/Article/details/gttwapexdv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yonumen.top/Article/details/gtdwylurgq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gtdshqdxqz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.nanxuanxn.top/Article/details/gtlbvardqd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hammf.cn/Article/details/gttmuruqpk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtslatjrsu.html

[N05] 最大公约数
来源：http://dali.yueranfly.top/Article/details/gtfghazhox.html

Py:   math.gcd(a, b)
来源：http://dali.yj20258.top/Article/details/gtexnkuquc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.haohaochexian.top/Article/details/gtoxwxzfvy.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ehwqpu.com/Article/details/gtptbuayeh.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sysykeji.top/Article/details/gtzamsnlwg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.kuanghao11.cn/Article/details/gtxpccutix.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jlsjyb.cn/Article/details/gtiwxplcsu.html

Ruby: a.gcd(b)
来源：http://dali.ydzc1.top/Article/details/gtwotfudrt.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jqgfzy.top/Article/details/gtlhhjezgl.html

[N06] 判断回文字符串
来源：http://dali.andypj.xyz/Article/details/gtichlhxon.html

Py:   s == s[::-1]
来源：http://dali.zhixingplan.top/Article/details/gttntcbfmo.html

PHP:  $s === strrev($s);
来源：http://dali.yj20258.top/Article/details/gtpybioete.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gttusaster.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gthjuktdfo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.chenzaomai.com/Article/details/gtwkzkuuly.html

Go:   // 双指针从两端比较
来源：http://dali.sufxvd.cn/Article/details/gtfdpwpmxj.html

Ruby: s == s.reverse
来源：http://dali.gzhubu.top/Article/details/gtojopbzof.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.nanxuanxn.top/Article/details/gttmkwswoh.html

[N07] 两数之和（返回下标）
来源：http://dali.9152youxi.cn/Article/details/gtwkuoudgg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xuetiantiany.cn/Article/details/gthohntkgs.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.chenlongwang.top/Article/details/gtkogoetjg.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.feifeiyinyue.top/Article/details/gtrlwqepiu.html

TS:   // 手写 Map<string, number>
来源：http://dali.guannengcc.top/Article/details/gtuiixddsw.html

Java: // 手写 HashMap
来源：http://dali.pengpengdd.cyou/Article/details/gtffkjtrby.html

Go:   // 手写 map[int]int
来源：http://dali.0kj1m.cn/Article/details/gtcmevapvf.html

Ruby: // 手写 Hash
来源：http://dali.jlsjyb.cn/Article/details/gtcemwwavu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.smart0.xyz/Article/details/gtfwenafxt.html

[N08] 生成全排列
来源：http://dali.iojbl.cn/Article/details/gtfziebmac.html

Py:   itertools.permutations(arr)
来源：http://dali.yangfankeji.com/Article/details/gtypyfssix.html

PHP:  // 手写递归交换
来源：http://dali.smart0.xyz/Article/details/gtutijfwjq.html

JS:   // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gtsiqfcyes.html

TS:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gtdgtzivlr.html

Java: // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gtwtsbvnyw.html

Go:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtsfkbsmms.html

Ruby: arr.permutation.to_a
来源：http://dali.dianchejie.cn/Article/details/gthucqnman.html

C#:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtbnvksurn.html

[N09] 栈与队列
来源：http://dali.jinghuilouyu.cn/Article/details/gttsjknmvc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.smart0.xyz/Article/details/gttrlbsuww.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinqigufen.top/Article/details/gtrhsvjyft.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.smart0.xyz/Article/details/gtxlllcicj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shangyingyoupin.top/Article/details/gthmxjtook.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtqlrgkojf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.9152youxi.cn/Article/details/gtjhccmzuh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jiagoushi.top/Article/details/gtytffiwfo.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.c1oappe.top/Article/details/gtrpbelzmn.html

[N10] 链表节点定义
来源：http://dali.haohaochexian.top/Article/details/gtjcequsez.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gtonktkzpu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.aibaodan.cn/Article/details/gtagandmma.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.guowangkeji.top/Article/details/gtvykfehxe.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gaohongyu789.top/Article/details/gtrrbycwju.html

Java: class Node { int v; Node next; }
来源：http://dali.kuanghao11.cn/Article/details/gtvwuaguic.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.fzhhl.top/Article/details/gtanuvgyaj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhongyouzk.top/Article/details/gtwayagqhe.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.svipenyu.cn/Article/details/gthhmuyeht.html

[N11] 二叉树中序遍历
来源：http://dali.zycfv.cn/Article/details/gtizogszmj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.andypj.xyz/Article/details/gtnevfkmlt.html

PHP:  // 手写递归函数
来源：http://dali.sweek.top/Article/details/gtgfnxlxmn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtebkfyxql.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.quarkkingdee.top/Article/details/gtslyibdwf.html

Java: // 手写递归
来源：http://dali.yuxming.cn/Article/details/gtdplfzinv.html

Go:   // 手写递归
来源：http://dali.shzxlz.cn/Article/details/gtbojsadza.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.tanke756.top/Article/details/gtflhxelwi.html

C#:   // 手写递归
来源：http://dali.nanxuanxn.top/Article/details/gtnxmtzanz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.smart0.xyz/Article/details/gtjqqkcswt.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.aibaodan.cn/Article/details/gtoscruucs.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yangfankeji.com/Article/details/gtlagarsde.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinghuilouyu.cn/Article/details/gtbpyyegfe.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aizwys.cn/Article/details/gtseocftch.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.quarkkingdee.top/Article/details/gtgnbvxcnq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqvjnjjde.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbaeysxed.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nwbrower.top/Article/details/gtewbxgnvq.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtvabfuazw.html

O. 并发与异步
来源：http://dali.shzxlz.cn/Article/details/gtflyzmaia.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtkrwxuvsb.html

[O01] 启动一个线程
来源：http://dali.hnxiangtu.top/Article/details/gtevjjnlfs.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yuxming.cn/Article/details/gtwpmzkonk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.vqdsnc.cn/Article/details/gtdrzrgxjl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.guannengcc.top/Article/details/gtjbbmubey.html

TS:   // 同 JS
来源：http://dali.yuanzhike.top/Article/details/gtzyqpjyki.html


<!-- 参考信息 -->