代发 wailian999

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tianlin.xyz/Article/details/gtsqafgojl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sysykeji.top/Article/details/gtctggpvxi.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xuanzx.com/Article/details/gtygvdbkrp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gtljasenfd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhiwuduotai.top/Article/details/gtewburidc.html

[K07] 进制转换
来源：http://dali.shangyingyoupin.top/Article/details/gtfxohvllt.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gttkjxqgke.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jlsjyb.cn/Article/details/gtnykieogl.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtsofskvrv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvgmcdlvr.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqbnaorua.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.iojbl.cn/Article/details/gtpktcgxpj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shanyushiyangtech.top/Article/details/gthyetfelu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gtuoomlhzc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gzhubu.top/Article/details/gtfuxbygsj.html

Py:   pickle.dumps(obj)
来源：http://dali.sysykeji.top/Article/details/gtqgxevpkj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.tian-w.cn/Article/details/gtmgsxtsre.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ybcxt.top/Article/details/gtvwhmaxbn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xziqi.cn/Article/details/gtuwjiixne.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.mhx1999.top/Article/details/gtcksndzwb.html

Go:   encoding/gob
来源：http://dali.zdqjudy.top/Article/details/gtbfcpmhlh.html

Ruby: Marshal.dump(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtmbpnnimx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cheryme.top/Article/details/gtmmbleddm.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtrmgbyfin.html

L. 网络请求
来源：http://dali.sufxvd.cn/Article/details/gtzztoyjvx.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtflhieeqa.html

[L01] 发送 GET 请求
来源：http://dali.yj202588.top/Article/details/gtqpyfuvam.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhongyouzk.top/Article/details/gtybveabyf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sysykeji.top/Article/details/gtrkttjzag.html

JS:   await fetch(url)
来源：http://dali.yuxming.cn/Article/details/gtuuomjgsa.html

TS:   await fetch(url)
来源：http://dali.daria6918.cn/Article/details/gtdmkxazeq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cashguo.top/Article/details/gtnlgyluib.html

Go:   resp, err := http.Get(url)
来源：http://dali.nanxuanxn.top/Article/details/gtyrsveirb.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ywan-chungtsiang.top/Article/details/gthkxktcgr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.birdmap.top/Article/details/gtwnkvwhab.html

[L02] 发送 POST JSON
来源：http://dali.yongpay.top/Article/details/gtavradzia.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.nanxinkj.top/Article/details/gtyhiulpor.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.snrcjt.cn/Article/details/gttklwkybr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.c1oappe.top/Article/details/gthsjrsgrd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nwbrower.top/Article/details/gtqldalswe.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ehwqpu.com/Article/details/gtpmhvjbtg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.daria6918.cn/Article/details/gtjsrlzhkw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.tianlin.xyz/Article/details/gtovkizjag.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hnqzz.top/Article/details/gtvofucbfn.html

[L03] 设置自定义请求头
来源：http://dali.fengsongda.top/Article/details/gtefttdquc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.snrcjt.cn/Article/details/gtrrktphph.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zycfv.cn/Article/details/gtmuhfigln.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.vqdsnc.cn/Article/details/gtgixapcjg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dashuyun.cn/Article/details/gtljlevjkw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.bjfxy.top/Article/details/gtaanwuoxw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcgrwjmre.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jiagoushi.top/Article/details/gtyqtgimlo.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.snrcjt.cn/Article/details/gtbjkhcsyn.html

[L04] 设置超时
来源：http://dali.dashuyun.cn/Article/details/gttvojgfap.html

Py:   requests.get(url, timeout=5)
来源：http://dali.sweek.top/Article/details/gtmgxbtjye.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.wangdashe.top/Article/details/gtqfemulwa.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.316326.xyz/Article/details/gtxugtjxgq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ehwqpu.com/Article/details/gtnxbyvtts.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.dashuyun.cn/Article/details/gtgdmscgqr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.wangshuangyany.cn/Article/details/gtspjbqqtj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hywenlv.cn/Article/details/gtpyvqbvfl.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hammf.cn/Article/details/gtwwyajazw.html

[L05] 上传文件（multipart）
来源：http://dali.yj20258.top/Article/details/gtdwwlncce.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sweek.top/Article/details/gtswrrexpm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhengqikj.top/Article/details/gtvjjtgwti.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenzaomai.com/Article/details/gtaairagws.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yangfankeji.com/Article/details/gtqphokkqo.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gotoacloud.top/Article/details/gtdahnqmys.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ydzc1.top/Article/details/gtdzfwunoa.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cashguo.top/Article/details/gtmmaplfyk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtknogblrg.html

[L06] 解析响应为 JSON
来源：http://dali.xylfe.cn/Article/details/gtnjafwlol.html

Py:   resp.json()
来源：http://dali.chenlongwang.top/Article/details/gtpbuzzpqy.html

PHP:  json_decode($body, true);
来源：http://dali.jinqigufen.top/Article/details/gtahqvtvnw.html

JS:   await resp.json()
来源：http://dali.316326.xyz/Article/details/gtrnykqvdu.html

TS:   await resp.json()
来源：http://dali.yvedp.cn/Article/details/gtcevwhjwr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gotoacloud.top/Article/details/gtupgmggwb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.gogol.net.cn/Article/details/gtjogfrmvc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdekouqll.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cqqwz.cn/Article/details/gtffxvhlvd.html

[L07] 处理 HTTP 状态码
来源：http://dali.zycfv.cn/Article/details/gtfczauybw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.meibo888.top/Article/details/gtpcqhrkdf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ppjwa.cn/Article/details/gtrvgwihwy.html

JS:   resp.ok;  resp.status
来源：http://dali.snrcjt.cn/Article/details/gtnsskiobs.html

TS:   resp.ok;  resp.status
来源：http://dali.vqdsnc.cn/Article/details/gtqihmudcc.html

Java: resp.statusCode()
来源：http://dali.birdmap.top/Article/details/gttewuintb.html

Go:   resp.StatusCode
来源：http://dali.jianghu66.top/Article/details/gtvcrvkqjy.html

Ruby: resp.code.to_i
来源：http://dali.sufxvd.cn/Article/details/gtsrbkxshx.html

C#:   (int)resp.StatusCode
来源：http://dali.hysaishi.cn/Article/details/gtyryrgtue.html

[L08] 并发请求多个地址
来源：http://dali.chenjidiqi.icu/Article/details/gtwxaaqgpl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhiwuduotai.top/Article/details/gtxvkgmetx.html

PHP:  curl_multi_init() 系列
来源：http://dali.yj202588.top/Article/details/gtxzxyfjiv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yanxiufei.cn/Article/details/gtdbwntckg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangdashe.top/Article/details/gtqpggyyhb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cqqwz.cn/Article/details/gthrkewtsr.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gtlravoujt.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhixingplan.top/Article/details/gtiixlqkxf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yuanzhike.top/Article/details/gtkdmfjlrf.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtapmgpomr.html

M. 命令行 / 进程 / 环境
来源：http://dali.kuanghao11.cn/Article/details/gticcvobho.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtnupbtpqx.html

[M01] 读取命令行参数
来源：http://dali.smart0.xyz/Article/details/gtqvjexlzr.html

Py:   sys.argv[1:]
来源：http://dali.xylfe.cn/Article/details/gtnnqkxwiw.html

PHP:  $argv;  $argc;
来源：http://dali.yj202588.top/Article/details/gtilmgnmlx.html

JS:   process.argv.slice(2)
来源：http://dali.nanxinkj.top/Article/details/gtjwuajowx.html

TS:   process.argv.slice(2)
来源：http://dali.pycfn.com/Article/details/gtsaplwzlq.html

Java: args 数组（main 方法参数）
来源：http://dali.jinghuilouyu.cn/Article/details/gtomeaiekj.html

Go:   os.Args[1:]
来源：http://dali.cashguo.top/Article/details/gtbezyvwpe.html

Ruby: ARGV
来源：http://dali.yuxming.cn/Article/details/gtxtqrzfzx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jiagoushi.top/Article/details/gthzowdqcl.html

[M02] 读取环境变量
来源：http://dali.zhongyouzk.top/Article/details/gttlpbkmwk.html

Py:   os.environ.get("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gtvirpdudy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yuanzhike.top/Article/details/gtqosiaoan.html

JS:   process.env.HOME
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpystaksv.html

TS:   process.env.HOME
来源：http://dali.yj20258888.top/Article/details/gtfohnvpyl.html

Java: System.getenv("HOME")
来源：http://dali.xziqi.cn/Article/details/gttpglvtno.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gtfrdvmxak.html

Ruby: ENV["HOME"]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyopmbzrq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzrbcnnme.html

[M03] 执行外部命令
来源：http://dali.ybcxt.top/Article/details/gtqykwyvmz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tianlin.xyz/Article/details/gtnbrplrjn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jyoumei.cn/Article/details/gtgfhydydc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gaohongyu789.top/Article/details/gtyqmrgrij.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yueranfly.top/Article/details/gtbxzewsyz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.daxiang520.top/Article/details/gtvlcgdwqh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.9152youxi.cn/Article/details/gtaakzbhmy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xinyue.icu/Article/details/gtqvallnow.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yongpay.top/Article/details/gtzvlpugxf.html

[M04] 获取当前工作目录
来源：http://dali.shzxlz.cn/Article/details/gtpusxcawe.html

Py:   os.getcwd()
来源：http://dali.daxiang520.top/Article/details/gtglvqvjyd.html

PHP:  getcwd();
来源：http://dali.meibo888.top/Article/details/gtikynlfdv.html

JS:   process.cwd()
来源：http://dali.snrcjt.cn/Article/details/gteowvzrfa.html

TS:   process.cwd()
来源：http://dali.yj20258888.top/Article/details/gtzvcpkdhr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmjdeoczq.html

Go:   os.Getwd()
来源：http://dali.jianghu66.top/Article/details/gtbxobblqn.html

Ruby: Dir.pwd
来源：http://dali.iojbl.cn/Article/details/gtqndvwmgk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ivvv.top/Article/details/gtqsxxpogy.html

[M05] 设置退出码
来源：http://dali.guowangkeji.top/Article/details/gttaudeprz.html

Py:   sys.exit(1)
来源：http://dali.jianghu66.top/Article/details/gtimhnfqiu.html

PHP:  exit(1);
来源：http://dali.hnxiangtu.top/Article/details/gtyxqhipop.html

JS:   process.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtlgvffgut.html

TS:   process.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtwzbsjxki.html

Java: System.exit(1)
来源：http://dali.sysykeji.top/Article/details/gtqxdboude.html

Go:   os.Exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtdcxbhvnb.html

Ruby: exit 1
来源：http://dali.bjfxy.top/Article/details/gtenqgibvf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sweek.top/Article/details/gtmjrrpfee.html

[M06] 向标准错误输出
来源：http://dali.xylfe.cn/Article/details/gtbwlfgjtx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhongyouzk.top/Article/details/gtjcsqgdqj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hfpthk.cn/Article/details/gtopkfnouj.html

JS:   console.error("err")
来源：http://dali.birdmap.top/Article/details/gtoqngocfm.html

TS:   console.error("err")
来源：http://dali.meibo888.top/Article/details/gtvhzctffs.html

Java: System.err.println("err")
来源：http://dali.gogol.net.cn/Article/details/gtznzolkzg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gotoacloud.top/Article/details/gtakyycrjb.html

Ruby: warn "err"
来源：http://dali.hnqzz.top/Article/details/gtqxuujqdx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hfpthk.cn/Article/details/gtmeiqkhfs.html

[M07] 判断是否为主入口
来源：http://dali.yongpay.top/Article/details/gtloynqmlg.html

Py:   if __name__ == "__main__":
来源：http://dali.hnxiangtu.top/Article/details/gthfokwcxa.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ppjwa.cn/Article/details/gtrtwcafsl.html

JS:   require.main === module
来源：http://dali.nanxuanxn.top/Article/details/gtcodnvlsj.html

TS:   require.main === module
来源：http://dali.jiagoushi.top/Article/details/gtzpitmccg.html

Java: public static void main(String[] args)
来源：http://dali.redwolf501.top/Article/details/gtyzxviglg.html

Go:   func main()
来源：http://dali.havefunace.top/Article/details/gtwfmhtajz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhoulong.xyz/Article/details/gtdtacupcl.html

C#:   static void Main(string[] args)
来源：http://dali.ehwqpu.com/Article/details/gtcwdatixd.html

[M08] 获取系统与运行时信息
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwtjgvdsg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmocctcpe.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xuetiantiany.cn/Article/details/gtyjbqsbtj.html

JS:   process.platform;  process.version
来源：http://dali.cucudq.cn/Article/details/gtyouuirae.html

TS:   process.platform;  process.version
来源：http://dali.shzxlz.cn/Article/details/gtkegcqwrx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.bjfxy.top/Article/details/gtnezeukgx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.wangshuangyany.cn/Article/details/gtfuvoxjfm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yvedp.cn/Article/details/gtbpfivwfc.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yvedp.cn/Article/details/gtltnfswft.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtcrnantct.html

N. 数据结构与算法
来源：http://dali.gzhubu.top/Article/details/gtmijxaxzg.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtzxjvvgjg.html

[N01] 二分查找（有序数组）
来源：http://dali.andypj.xyz/Article/details/gtcubwozcq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yongpay.top/Article/details/gtivtlmqku.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gtkfjkwqru.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sysykeji.top/Article/details/gtadwaeqvp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.quarkkingdee.top/Article/details/gtvlworlzj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtowgebfgw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cheryme.top/Article/details/gtyuwyzbeg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.andypj.xyz/Article/details/gtsdxcfnpp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtcjrxloms.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenzaomai.com/Article/details/gtbxjmhbpl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhongyouzk.top/Article/details/gtjviroaof.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cucudq.cn/Article/details/gtrrjsvold.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiyujqojz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gtogxsspwc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.quarkkingdee.top/Article/details/gtvrojycib.html

Go:   slices.Sort(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsmgwnkgx.html

Ruby: arr.sort
来源：http://dali.cqqwz.cn/Article/details/gtvssdubop.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nwbrower.top/Article/details/gtwrdkduzb.html

[N03] 快速排序（分治示例）
来源：http://dali.chenjidiqi.icu/Article/details/gtlrruekhz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yuanzhike.top/Article/details/gtzedjbsck.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ywan-chungtsiang.top/Article/details/gthmmcpsbj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258.top/Article/details/gtxnptwblc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinghuilouyu.cn/Article/details/gtnzoeluyo.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cucudq.cn/Article/details/gtolznzhno.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shanyushiyangtech.top/Article/details/gtbsvpizji.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.wangshuangyany.cn/Article/details/gtldtgjloj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yongpay.top/Article/details/gtbthisuom.html

[N04] 斐波那契数列
来源：http://dali.andypj.xyz/Article/details/gtawppnwrh.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtjyygivej.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.aizwys.cn/Article/details/gtrxslsrjt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.quarkkingdee.top/Article/details/gtxahtpyiq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gtcimkcdum.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shuidangran.top/Article/details/gtzmjitphb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sweek.top/Article/details/gtenxgobcx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gaohongyu789.top/Article/details/gtgxqxhrbt.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gttjdgkjlw.html

[N05] 最大公约数
来源：http://dali.xinyue.icu/Article/details/gtkvncvbmx.html

Py:   math.gcd(a, b)
来源：http://dali.xinyue.icu/Article/details/gtqgttgagf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.fengsongda.top/Article/details/gtdvuhpogh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.mhx1999.top/Article/details/gtcoxheyix.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuanzx.com/Article/details/gtthfabblj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.fengsongda.top/Article/details/gtwtoiexeb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpznlxvak.html

Ruby: a.gcd(b)
来源：http://dali.sufxvd.cn/Article/details/gtgxkbskhp.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.meibo888.top/Article/details/gtbmvzviqp.html

[N06] 判断回文字符串
来源：http://dali.wangdashe.top/Article/details/gtvgxlgdhn.html

Py:   s == s[::-1]
来源：http://dali.kuanghao11.cn/Article/details/gtpgjpfhtz.html

PHP:  $s === strrev($s);
来源：http://dali.haohaochexian.top/Article/details/gtupzrzvss.html

JS:   s === [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gtbcxwgifd.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gtlvezdkhw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.wangshuangyany.cn/Article/details/gtktcbhpwq.html

Go:   // 双指针从两端比较
来源：http://dali.gogol.net.cn/Article/details/gttmrfedjc.html

Ruby: s == s.reverse
来源：http://dali.xuanzx.com/Article/details/gtjwrqnofp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuyuuitqp.html

[N07] 两数之和（返回下标）
来源：http://dali.fengsongda.top/Article/details/gtbpyupuzj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cqqwz.cn/Article/details/gtttbmhzmm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ivvv.top/Article/details/gtrboaqcqp.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jyoumei.cn/Article/details/gtaezmgntf.html

TS:   // 手写 Map<string, number>
来源：http://dali.tanke756.top/Article/details/gtmznmzcre.html

Java: // 手写 HashMap
来源：http://dali.dashuyun.cn/Article/details/gtvqquqlpf.html

Go:   // 手写 map[int]int
来源：http://dali.shangyingyoupin.top/Article/details/gtlduiixhh.html

Ruby: // 手写 Hash
来源：http://dali.guannengcc.top/Article/details/gtxgchzslc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.bjfxy.top/Article/details/gtgvzxcvmv.html

[N08] 生成全排列
来源：http://dali.aizwys.cn/Article/details/gtqksiuyss.html

Py:   itertools.permutations(arr)
来源：http://dali.tian-w.cn/Article/details/gtonhdlbwc.html

PHP:  // 手写递归交换
来源：http://dali.yj202588.top/Article/details/gtyfkeetit.html

JS:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gtkrmvukxo.html

TS:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdnjquqbr.html

Java: // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtkqkmtkkb.html

Go:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gtefipjqyc.html

Ruby: arr.permutation.to_a
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxewmjwxi.html

C#:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gtbcxhldtz.html

[N09] 栈与队列
来源：http://dali.shzxlz.cn/Article/details/gtrwmqtllo.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.9152youxi.cn/Article/details/gtwqdqtkzb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cashguo.top/Article/details/gtheekmxis.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.daria6918.cn/Article/details/gtcjqzsuqc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.guowangkeji.top/Article/details/gtzoghzfyn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hnqzz.top/Article/details/gtqvqzemft.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.nanxinkj.top/Article/details/gtysmrdzdt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.redwolf501.top/Article/details/gtyfrdchvw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hongshengwenyu.top/Article/details/gtjokvgudt.html

[N10] 链表节点定义
来源：http://dali.cheryme.top/Article/details/gthfearbph.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.chenlongwang.top/Article/details/gtrdtmsvmm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.tanke756.top/Article/details/gtylogvjpb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hammf.cn/Article/details/gttytdqhrd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.tianlin.xyz/Article/details/gtvtatrmhh.html

Java: class Node { int v; Node next; }
来源：http://dali.yuanzhike.top/Article/details/gttabooqtt.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yj20258.top/Article/details/gtijfycckh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.daria6918.cn/Article/details/gtpbrdtatb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.316326.xyz/Article/details/gtknvjoeqq.html

[N11] 二叉树中序遍历
来源：http://dali.hysaishi.cn/Article/details/gtgbhfhqwy.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.havefunace.top/Article/details/gttbxeteos.html

PHP:  // 手写递归函数
来源：http://dali.chenjidiqi.icu/Article/details/gthzrnmhdy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yueranfly.top/Article/details/gtavipkvyf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yvedp.cn/Article/details/gtskmogbab.html

Java: // 手写递归
来源：http://dali.yonumen.top/Article/details/gtkpiwipli.html

Go:   // 手写递归
来源：http://dali.dianchejie.cn/Article/details/gtwxtgjjty.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.aibaodan.cn/Article/details/gtewlfmclm.html

C#:   // 手写递归
来源：http://dali.xylfe.cn/Article/details/gtbyykpqnj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinghuilouyu.cn/Article/details/gtqfvvaarz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtanigacaj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.tianlin.xyz/Article/details/gtsjcegmhd.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gaohongyu789.top/Article/details/gtfweaclup.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.quarkkingdee.top/Article/details/gtuuljfnhv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ivvv.top/Article/details/gtisltfasq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.dianchejie.cn/Article/details/gtwryhjonb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gotoacloud.top/Article/details/gtstfcsgid.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigfzy.top/Article/details/gtheuibboa.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtqutznbhc.html

O. 并发与异步
来源：http://dali.tanke756.top/Article/details/gtjsbdhlxv.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtdhsuhixv.html

[O01] 启动一个线程
来源：http://dali.svipenyu.cn/Article/details/gteedjcalo.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shuidangran.top/Article/details/gtqppkplfb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.andypj.xyz/Article/details/gtduvjcrow.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hnxiangtu.top/Article/details/gtszeluyqw.html

TS:   // 同 JS
来源：http://dali.hammf.cn/Article/details/gtfxgrzxrt.html

Java: new Thread(() -> f()).start()
来源：http://dali.vqdsnc.cn/Article/details/gtpyfbnwbl.html

Go:   go f()
来源：http://dali.xinyue.icu/Article/details/gtgxuoabxr.html

Ruby: Thread.new { f }
来源：http://dali.havefunace.top/Article/details/gtjnsdjpag.html

C#:   Task.Run(() => F());
来源：http://dali.shuidangran.top/Article/details/gtpuvhmmbu.html

[O02] 使用线程池
来源：http://dali.fengsongda.top/Article/details/gtngtzibaw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cucudq.cn/Article/details/gtpoohltcm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.fengsongda.top/Article/details/gteaoomfas.html

JS:   // worker_threads 线程池
来源：http://dali.hywenlv.cn/Article/details/gtoquwcjvf.html


<!-- 参考信息 -->