代发 wailian999

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.iojbl.cn/Article/details/gtzisnwsho.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.chenlongwang.top/Article/details/gtbbsunreu.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shzxlz.cn/Article/details/gtmjsvlcuz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.pengpengdd.cyou/Article/details/gtdzrdgzow.html

[K06] 解析 URL 查询串
来源：http://dali.guannengcc.top/Article/details/gtchjtyqpn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.aizwys.cn/Article/details/gtvozlcurw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zdqjudy.top/Article/details/gtwypewpqg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.quarkkingdee.top/Article/details/gtswlgtrqi.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhengqikj.top/Article/details/gtblzdbwne.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yangfankeji.com/Article/details/gtzdktiqyf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hnqzz.top/Article/details/gtkbgnnzpf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hammf.cn/Article/details/gtoiymemfk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gtyumlmwfv.html

[K07] 进制转换
来源：http://dali.hysaishi.cn/Article/details/gtkdkguwyg.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tanke756.top/Article/details/gtlowwunzb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hnqzz.top/Article/details/gtrcghrgos.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtugyglydv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtvvomfbjt.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtxtenjnzb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cashguo.top/Article/details/gtfyjbajhh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhongyouzk.top/Article/details/gtwgesanhy.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gteflvstdr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenzaomai.com/Article/details/gtcnawcteu.html

Py:   pickle.dumps(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtryfmvgek.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yonumen.top/Article/details/gtovhdxspn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.wangshuangyany.cn/Article/details/gtzexeysck.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jiagoushi.top/Article/details/gticjnadlz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.fzhhl.top/Article/details/gtstuiupgn.html

Go:   encoding/gob
来源：http://dali.chenjidiqi.icu/Article/details/gtqnfoilvu.html

Ruby: Marshal.dump(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtaxixtfbr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gzhubu.top/Article/details/gtmzptnkuw.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtukxpjahk.html

L. 网络请求
来源：http://dali.ppjwa.cn/Article/details/gtgahceaya.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtzczbtaeb.html

[L01] 发送 GET 请求
来源：http://dali.bjfxy.top/Article/details/gtltrlplwc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhoulong.xyz/Article/details/gttdrdpxfb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.birdmap.top/Article/details/gtkqnallwx.html

JS:   await fetch(url)
来源：http://dali.andypj.xyz/Article/details/gtgjwdttec.html

TS:   await fetch(url)
来源：http://dali.chenlongwang.top/Article/details/gtawmnyqtd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hywenlv.cn/Article/details/gttotkkskd.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gtcogleoyv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.svipenyu.cn/Article/details/gtewyblcwy.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yvedp.cn/Article/details/gtlfsvwifc.html

[L02] 发送 POST JSON
来源：http://dali.gzhubu.top/Article/details/gtfzgfpeqe.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gogol.net.cn/Article/details/gtxmyskdzn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ydzc1.top/Article/details/gtlyzvtanv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cqqwz.cn/Article/details/gtrubkqbvs.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.snrcjt.cn/Article/details/gtzidgznys.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yuxming.cn/Article/details/gtdjadljzb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yvedp.cn/Article/details/gtybldlsiv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shuidangran.top/Article/details/gtcvltejpw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yongpay.top/Article/details/gtndydgmez.html

[L03] 设置自定义请求头
来源：http://dali.jyoumei.cn/Article/details/gtxddvrdxq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjqmsbggo.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.meibo888.top/Article/details/gthxdvemnq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenjidiqi.icu/Article/details/gtwysawwog.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ppjwa.cn/Article/details/gtwvpdnmsy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.tian-w.cn/Article/details/gtrcikalpq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqzbmhvls.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj20258888.top/Article/details/gtjuzfncpk.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.dashuyun.cn/Article/details/gtreiegrqa.html

[L04] 设置超时
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnnsybgbu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yj20258888.top/Article/details/gttdikubsx.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.iojbl.cn/Article/details/gtdkmdzgam.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aibaodan.cn/Article/details/gtejoilrfq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sxryk.cn/Article/details/gtmnhgwwnc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.0kj1m.cn/Article/details/gtkscehekz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhongyouzk.top/Article/details/gtmhrzjnbu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shangyingyoupin.top/Article/details/gtcdugvlzi.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yongpay.top/Article/details/gtxgbhmbmg.html

[L05] 上传文件（multipart）
来源：http://dali.zhixingplan.top/Article/details/gtzpptnjuj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.havefunace.top/Article/details/gtxpuwnmuv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtagaaxnab.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ydzc1.top/Article/details/gtlprpxhfe.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.iojbl.cn/Article/details/gtbpmoxyab.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.haohaochexian.top/Article/details/gthvnjztly.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.birdmap.top/Article/details/gtwxusmgnr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.tanke756.top/Article/details/gtrmendgtl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.tanke756.top/Article/details/gtczdekbxc.html

[L06] 解析响应为 JSON
来源：http://dali.jyoumei.cn/Article/details/gteaeeopdm.html

Py:   resp.json()
来源：http://dali.guowangkeji.top/Article/details/gttqaxkjwe.html

PHP:  json_decode($body, true);
来源：http://dali.daxiang520.top/Article/details/gtbtoetjzc.html

JS:   await resp.json()
来源：http://dali.shangyingyoupin.top/Article/details/gtsqikxmaj.html

TS:   await resp.json()
来源：http://dali.zhongyouzk.top/Article/details/gtltdinruc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.andypj.xyz/Article/details/gtqtwngosm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shangyingyoupin.top/Article/details/gtlyqcdbol.html

Ruby: JSON.parse(resp.body)
来源：http://dali.fzhhl.top/Article/details/gthywhytsi.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.haohaochexian.top/Article/details/gtxivshkmk.html

[L07] 处理 HTTP 状态码
来源：http://dali.zycfv.cn/Article/details/gtslvkecba.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cheryme.top/Article/details/gtlssoxalv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yueranfly.top/Article/details/gtiptsnwni.html

JS:   resp.ok;  resp.status
来源：http://dali.yj20258888.top/Article/details/gtybjdwtcn.html

TS:   resp.ok;  resp.status
来源：http://dali.redwolf501.top/Article/details/gtgdnwotko.html

Java: resp.statusCode()
来源：http://dali.sweek.top/Article/details/gthjlxrumu.html

Go:   resp.StatusCode
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpdisjcow.html

Ruby: resp.code.to_i
来源：http://dali.dianchejie.cn/Article/details/gtjynyggny.html

C#:   (int)resp.StatusCode
来源：http://dali.zhongyouzk.top/Article/details/gttrdwbaov.html

[L08] 并发请求多个地址
来源：http://dali.xziqi.cn/Article/details/gtzbfbfkom.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.fzhhl.top/Article/details/gtykjizeup.html

PHP:  curl_multi_init() 系列
来源：http://dali.xuetiantiany.cn/Article/details/gtbhoemjlk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guannengcc.top/Article/details/gtnanareup.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daria6918.cn/Article/details/gtunbjnese.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.wangdashe.top/Article/details/gtwwlwnosi.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yuanzhike.top/Article/details/gtacyxypcz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cheryme.top/Article/details/gtnbsnwrwg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jyoumei.cn/Article/details/gtmnivrnab.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtlcdlsbrx.html

M. 命令行 / 进程 / 环境
来源：http://dali.gogol.net.cn/Article/details/gtwoiahdlx.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtijhtbweq.html

[M01] 读取命令行参数
来源：http://dali.xuanzx.com/Article/details/gtvcyaotjz.html

Py:   sys.argv[1:]
来源：http://dali.xinyue.icu/Article/details/gtgthqhaja.html

PHP:  $argv;  $argc;
来源：http://dali.0kj1m.cn/Article/details/gtckrwzwuj.html

JS:   process.argv.slice(2)
来源：http://dali.zhongyouzk.top/Article/details/gtobdbsjth.html

TS:   process.argv.slice(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqfegvoaj.html

Java: args 数组（main 方法参数）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgjvhieca.html

Go:   os.Args[1:]
来源：http://dali.pengpengdd.cyou/Article/details/gteghfwrhn.html

Ruby: ARGV
来源：http://dali.yj20258.top/Article/details/gtnugrljcr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.fengsongda.top/Article/details/gtprmnwkwe.html

[M02] 读取环境变量
来源：http://dali.jinqigufen.top/Article/details/gtyexmcwee.html

Py:   os.environ.get("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdkfjnvjk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtikkezaze.html

JS:   process.env.HOME
来源：http://dali.quarkkingdee.top/Article/details/gtmzyimehf.html

TS:   process.env.HOME
来源：http://dali.yuanzhike.top/Article/details/gtmrdfhqxa.html

Java: System.getenv("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gtpsscsqho.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.andypj.xyz/Article/details/gtsumunqjs.html

Ruby: ENV["HOME"]
来源：http://dali.xziqi.cn/Article/details/gtwgklfjby.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.daxiang520.top/Article/details/gttifmemgk.html

[M03] 执行外部命令
来源：http://dali.chenjidiqi.icu/Article/details/gtjopowpup.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.nanxinkj.top/Article/details/gtememozrm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.svipenyu.cn/Article/details/gtvktyqbmc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.kuanghao11.cn/Article/details/gtasrwcwxd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.snrcjt.cn/Article/details/gtuhijqtgl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.birdmap.top/Article/details/gtlzpdvtnv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jianghu66.top/Article/details/gtqrasoyfy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shanyushiyangkeji.top/Article/details/gtccqbnici.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gogol.net.cn/Article/details/gtwejpydek.html

[M04] 获取当前工作目录
来源：http://dali.smart0.xyz/Article/details/gthjoauzjm.html

Py:   os.getcwd()
来源：http://dali.316326.xyz/Article/details/gtmwplemen.html

PHP:  getcwd();
来源：http://dali.redwolf501.top/Article/details/gtehoqejyl.html

JS:   process.cwd()
来源：http://dali.cucudq.cn/Article/details/gtydxcgbqj.html

TS:   process.cwd()
来源：http://dali.shangyingyoupin.top/Article/details/gtgdruwjrm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jlsjyb.cn/Article/details/gtgbooszqq.html

Go:   os.Getwd()
来源：http://dali.jinqigfzy.top/Article/details/gtrfjbbflp.html

Ruby: Dir.pwd
来源：http://dali.fzhhl.top/Article/details/gtwjnzxdyl.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.dashuyun.cn/Article/details/gtduxbsuiz.html

[M05] 设置退出码
来源：http://dali.nwbrower.top/Article/details/gteeyyoxfy.html

Py:   sys.exit(1)
来源：http://dali.iojbl.cn/Article/details/gtfhnwmjwg.html

PHP:  exit(1);
来源：http://dali.sweek.top/Article/details/gtsdefduvy.html

JS:   process.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfyefutmq.html

TS:   process.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtssfjqnda.html

Java: System.exit(1)
来源：http://dali.xinyue.icu/Article/details/gtrkveeibk.html

Go:   os.Exit(1)
来源：http://dali.snrcjt.cn/Article/details/gtvtkmvatu.html

Ruby: exit 1
来源：http://dali.cheryme.top/Article/details/gtvtcvjlhs.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtskzodese.html

[M06] 向标准错误输出
来源：http://dali.birdmap.top/Article/details/gtdksaouev.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gtjmfceisi.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xziqi.cn/Article/details/gtesqscisc.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gtgvustgsh.html

TS:   console.error("err")
来源：http://dali.tianlin.xyz/Article/details/gtdvgwahaw.html

Java: System.err.println("err")
来源：http://dali.yj20258888.top/Article/details/gtaaicunvo.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.meibo888.top/Article/details/gtcyvlwrvs.html

Ruby: warn "err"
来源：http://dali.jinqigfzy.top/Article/details/gtfjhmxlxg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hnxiangtu.top/Article/details/gtiayeiyuf.html

[M07] 判断是否为主入口
来源：http://dali.yangfankeji.com/Article/details/gtizwbhbge.html

Py:   if __name__ == "__main__":
来源：http://dali.gotoacloud.top/Article/details/gtkxdswnhh.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gzhubu.top/Article/details/gtiplyasiu.html

JS:   require.main === module
来源：http://dali.haohaochexian.top/Article/details/gtnxhkyfkn.html

TS:   require.main === module
来源：http://dali.sufxvd.cn/Article/details/gtcqhunebj.html

Java: public static void main(String[] args)
来源：http://dali.tianlin.xyz/Article/details/gttlwdyywj.html

Go:   func main()
来源：http://dali.iojbl.cn/Article/details/gtbkkjsnjw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhengqikj.top/Article/details/gtuquqrcfd.html

C#:   static void Main(string[] args)
来源：http://dali.ppjwa.cn/Article/details/gtiydgxepd.html

[M08] 获取系统与运行时信息
来源：http://dali.svipenyu.cn/Article/details/gtuszuielt.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hammf.cn/Article/details/gtzvuojetv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xuetiantiany.cn/Article/details/gtbhfznlwc.html

JS:   process.platform;  process.version
来源：http://dali.wangshuangyany.cn/Article/details/gtptxkxntq.html

TS:   process.platform;  process.version
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmdluhwwi.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yangfankeji.com/Article/details/gtugllpatb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthuykybyk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gtmsckcind.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cashguo.top/Article/details/gtemxvpurp.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtskmqdtla.html

N. 数据结构与算法
来源：http://dali.gzhubu.top/Article/details/gtcfcxcyfu.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtkmhlyflw.html

[N01] 二分查找（有序数组）
来源：http://dali.aizwys.cn/Article/details/gtrhzcsgzk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtlykrldbu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.pycfn.com/Article/details/gtfobscgmb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.andypj.xyz/Article/details/gtahvuirks.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.9152youxi.cn/Article/details/gtqvjfkgzu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtmazwgtil.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtgjsdooyp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nanxinkj.top/Article/details/gtnoontmtl.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrzgjqtjc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yueranfly.top/Article/details/gtvzlylgqw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.svipenyu.cn/Article/details/gtfjqqjzgt.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cucudq.cn/Article/details/gtbciinemk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258.top/Article/details/gtwkfnmfyp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.9152youxi.cn/Article/details/gtcpsolfbn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jianghu66.top/Article/details/gtamjjklmj.html

Go:   slices.Sort(arr)
来源：http://dali.iojbl.cn/Article/details/gthsceessj.html

Ruby: arr.sort
来源：http://dali.feifeiyinyue.top/Article/details/gtlzfowydt.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gzhubu.top/Article/details/gtmvjbchjj.html

[N03] 快速排序（分治示例）
来源：http://dali.pycfn.com/Article/details/gtfteuvlii.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jlsjyb.cn/Article/details/gtdqkhdqxi.html

PHP:  // 递归实现，或用 usort
来源：http://dali.iojbl.cn/Article/details/gtoxrdmojv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dashuyun.cn/Article/details/gtmcjyplaz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dashuyun.cn/Article/details/gteofcfoba.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ehwqpu.com/Article/details/gtiqdmhyhu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shuidangran.top/Article/details/gtzkujkrha.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.feifeiyinyue.top/Article/details/gtvixpiwct.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jiagoushi.top/Article/details/gtydnmxwlr.html

[N04] 斐波那契数列
来源：http://dali.andypj.xyz/Article/details/gtezixgpqz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xziqi.cn/Article/details/gthybihxut.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cashguo.top/Article/details/gtmpnxmbmi.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gtukofwhcp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.birdmap.top/Article/details/gtlmpukqxq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jiagoushi.top/Article/details/gtmrtbalon.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenlongwang.top/Article/details/gtkoiqsyee.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdfbkbrwo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yuanzhike.top/Article/details/gtvlrhinmk.html

[N05] 最大公约数
来源：http://dali.quarkkingdee.top/Article/details/gtklvzaowx.html

Py:   math.gcd(a, b)
来源：http://dali.hywenlv.cn/Article/details/gtztjmtody.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjwkkqupj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhongyouzk.top/Article/details/gtmsipefis.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.andypj.xyz/Article/details/gtvbbkxvyt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hywenlv.cn/Article/details/gtwwsawyqe.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sysykeji.top/Article/details/gtwoknpion.html

Ruby: a.gcd(b)
来源：http://dali.meibo888.top/Article/details/gtygdqngzu.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sweek.top/Article/details/gtmhrczpsj.html

[N06] 判断回文字符串
来源：http://dali.zhongyouzk.top/Article/details/gtkomvahkz.html

Py:   s == s[::-1]
来源：http://dali.sweek.top/Article/details/gtlemqjzkn.html

PHP:  $s === strrev($s);
来源：http://dali.yongpay.top/Article/details/gtpfukoevs.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ydzc1.top/Article/details/gtuniivaxt.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzbmzvwge.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.kuanghao11.cn/Article/details/gtmuxfcnkw.html

Go:   // 双指针从两端比较
来源：http://dali.tian-w.cn/Article/details/gtbzhkpygc.html

Ruby: s == s.reverse
来源：http://dali.xylfe.cn/Article/details/gtmgshupio.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.bjfxy.top/Article/details/gtulehinby.html

[N07] 两数之和（返回下标）
来源：http://dali.smart0.xyz/Article/details/gtbfdvttzk.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cdnleiting.top/Article/details/gtoyujtwmp.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.aizwys.cn/Article/details/gtmqcsfezz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.chenlongwang.top/Article/details/gtzdixxioo.html

TS:   // 手写 Map<string, number>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaeoldfch.html

Java: // 手写 HashMap
来源：http://dali.hnqzz.top/Article/details/gtiapatapm.html

Go:   // 手写 map[int]int
来源：http://dali.yj202588.top/Article/details/gtnhlwakyn.html

Ruby: // 手写 Hash
来源：http://dali.gaohongyu789.top/Article/details/gtzwirresf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xylfe.cn/Article/details/gtzgmhvroc.html

[N08] 生成全排列
来源：http://dali.jiagoushi.top/Article/details/gtareecqzp.html

Py:   itertools.permutations(arr)
来源：http://dali.yonumen.top/Article/details/gtoogqqcne.html

PHP:  // 手写递归交换
来源：http://dali.yuxming.cn/Article/details/gtqffqmhmj.html

JS:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gtxuqyfxen.html

TS:   // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtlzcmdwig.html

Java: // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtgokpmsdl.html

Go:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gtnmrbkdbi.html

Ruby: arr.permutation.to_a
来源：http://dali.zdqjudy.top/Article/details/gtqoiobdio.html

C#:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtjzyymnhj.html

[N09] 栈与队列
来源：http://dali.ehwqpu.com/Article/details/gticsqsnpo.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cheryme.top/Article/details/gtwwephlut.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtugblmnxb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.c1oappe.top/Article/details/gtquvwzmvo.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.pengpengdd.cyou/Article/details/gtdyngharn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.aibaodan.cn/Article/details/gtxmrovyue.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hfpthk.cn/Article/details/gtzyfzrygc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hysaishi.cn/Article/details/gtymcridyx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.wangdashe.top/Article/details/gteitylwyg.html

[N10] 链表节点定义
来源：http://dali.hysaishi.cn/Article/details/gtulyivkzc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.chenjidiqi.icu/Article/details/gtccuhzrmk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.guannengcc.top/Article/details/gtgyghyhlt.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yj202588.top/Article/details/gtnlsqlxct.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cqqwz.cn/Article/details/gtxokafmxe.html

Java: class Node { int v; Node next; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdvzwzygz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.vqdsnc.cn/Article/details/gtpikypfqz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.fengsongda.top/Article/details/gtlylvrhcp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.wangshuangyany.cn/Article/details/gtopqwfdrq.html

[N11] 二叉树中序遍历
来源：http://dali.yongpay.top/Article/details/gtxvtxovjn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shuidangran.top/Article/details/gtkwmvzjnv.html

PHP:  // 手写递归函数
来源：http://dali.yongpay.top/Article/details/gtcrjnpedz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sxryk.cn/Article/details/gtxzpqabfz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ivvv.top/Article/details/gtyrzaobbv.html

Java: // 手写递归
来源：http://dali.xuanzx.com/Article/details/gtqeyfypyo.html

Go:   // 手写递归
来源：http://dali.bjfxy.top/Article/details/gtxfqvnmlq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinghuilouyu.cn/Article/details/gthpozureb.html

C#:   // 手写递归
来源：http://dali.gzhubu.top/Article/details/gtxkwhgmik.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xuanzx.com/Article/details/gticwhhbvf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shanyushiyangtech.top/Article/details/gtnroonuoo.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.aizwys.cn/Article/details/gtfiuiyoak.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daxiang520.top/Article/details/gtdvhtxlkk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhongyouzk.top/Article/details/gtbklrwjcc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoowwuxki.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.kuanghao11.cn/Article/details/gtvcjworqx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sysykeji.top/Article/details/gtxkostbwq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sxryk.cn/Article/details/gtllacejxm.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtweghxcnd.html

O. 并发与异步
来源：http://dali.hammf.cn/Article/details/gttyqaokgx.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtucgtkryf.html

[O01] 启动一个线程
来源：http://dali.fzhhl.top/Article/details/gtvebjjhxn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hfpthk.cn/Article/details/gtsbfbiekl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.nwbrower.top/Article/details/gtmrqrhroa.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xziqi.cn/Article/details/gtfubiwvfe.html

TS:   // 同 JS
来源：http://dali.sysykeji.top/Article/details/gtzuwhbjfp.html


<!-- 参考信息 -->