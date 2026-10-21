代发 wailian999

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gtxmagmfjc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtpgnafsqo.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cashguo.top/Article/details/gtfjhhqmhv.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jlsjyb.cn/Article/details/gtvbexgklf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinqigufen.top/Article/details/gtpzqepdlo.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtarleytnc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hysaishi.cn/Article/details/gtcpevvfuw.html

Py:   pickle.dumps(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtmhstvchx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gttxabzoos.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.iojbl.cn/Article/details/gtqjzvutgh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangkeji.top/Article/details/gtelwxzppj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.wangshuangyany.cn/Article/details/gtveyfpwie.html

Go:   encoding/gob
来源：http://dali.aibaodan.cn/Article/details/gtzsrwdehx.html

Ruby: Marshal.dump(obj)
来源：http://dali.tian-w.cn/Article/details/gtlclcgxsq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.dianchejie.cn/Article/details/gtgctkagcm.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtwakgjsxa.html

L. 网络请求
来源：http://dali.ybcxt.top/Article/details/gtaohqlpke.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtxrrbckxc.html

[L01] 发送 GET 请求
来源：http://dali.yj202588.top/Article/details/gtxzzzqikz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hnqzz.top/Article/details/gtyvwbioqr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sxryk.cn/Article/details/gthenlyuma.html

JS:   await fetch(url)
来源：http://dali.feifeiyinyue.top/Article/details/gtujtgayrq.html

TS:   await fetch(url)
来源：http://dali.hnxiangtu.top/Article/details/gtswrmpzyq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yongpay.top/Article/details/gtwlnxqgda.html

Go:   resp, err := http.Get(url)
来源：http://dali.ehwqpu.com/Article/details/gtcuneqieu.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.fengsongda.top/Article/details/gtucmuesms.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.redwolf501.top/Article/details/gtqpemtdmr.html

[L02] 发送 POST JSON
来源：http://dali.shzxlz.cn/Article/details/gtgnqomhcr.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.iojbl.cn/Article/details/gttcoutqzv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sweek.top/Article/details/gtbkmadznr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.redwolf501.top/Article/details/gtdlousuey.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daria6918.cn/Article/details/gtpdqhzlvc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.fzhhl.top/Article/details/gtelyxhdnd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yongpay.top/Article/details/gtcxovavqy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nwbrower.top/Article/details/gttqngudmm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.guannengcc.top/Article/details/gtukfvuakd.html

[L03] 设置自定义请求头
来源：http://dali.ybcxt.top/Article/details/gtqqdjoggq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yuanzhike.top/Article/details/gtlptzcjsy.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.daxiang520.top/Article/details/gtifnunkwo.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.haohaochexian.top/Article/details/gtqpgmoqkb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shuidangran.top/Article/details/gthrluovxv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.chenlongwang.top/Article/details/gtmpwhaqgu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yj202588.top/Article/details/gtcrmroflf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gtdukswzea.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.9152youxi.cn/Article/details/gtgpnuftta.html

[L04] 设置超时
来源：http://dali.shangyingyoupin.top/Article/details/gtaeitupyg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jiagoushi.top/Article/details/gtabsaodsr.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cqqwz.cn/Article/details/gtdhtdocai.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmlvrzxgt.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj202588.top/Article/details/gtbadncrfu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jqgfzy.top/Article/details/gtxitptzji.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.9152youxi.cn/Article/details/gtslhleymj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hnqzz.top/Article/details/gttwglherm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.vqdsnc.cn/Article/details/gtkzemxuha.html

[L05] 上传文件（multipart）
来源：http://dali.zhixingplan.top/Article/details/gtovrimsbb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jlsjyb.cn/Article/details/gtifuukhfp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yuanzhike.top/Article/details/gthaovgzff.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.316326.xyz/Article/details/gteclwxjeb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuanzhike.top/Article/details/gtdkdiraxg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sufxvd.cn/Article/details/gtjcsxfvdg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jqgufenzy.top/Article/details/gtduqiqmku.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.aizwys.cn/Article/details/gtvjetsrik.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.iojbl.cn/Article/details/gtgjllunqu.html

[L06] 解析响应为 JSON
来源：http://dali.316326.xyz/Article/details/gtsmxmnxkk.html

Py:   resp.json()
来源：http://dali.zycfv.cn/Article/details/gtgqjxkovm.html

PHP:  json_decode($body, true);
来源：http://dali.chenzaomai.com/Article/details/gtogfmlylt.html

JS:   await resp.json()
来源：http://dali.shuidangran.top/Article/details/gtnvmxgohl.html

TS:   await resp.json()
来源：http://dali.zhoulong.xyz/Article/details/gtttssdvnd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jqgfzy.top/Article/details/gtijxbxtyi.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ydzc1.top/Article/details/gtziqryzpt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.mhx1999.top/Article/details/gtkcflxwip.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj20258.top/Article/details/gtaxebfnsw.html

[L07] 处理 HTTP 状态码
来源：http://dali.ybcxt.top/Article/details/gtbtpwsvpw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj20258.top/Article/details/gtqxwigvsz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cdnleiting.top/Article/details/gtvozupdbw.html

JS:   resp.ok;  resp.status
来源：http://dali.guannengcc.top/Article/details/gtxmohtqbg.html

TS:   resp.ok;  resp.status
来源：http://dali.9152youxi.cn/Article/details/gtjihdrjxq.html

Java: resp.statusCode()
来源：http://dali.316326.xyz/Article/details/gtfhgcglem.html

Go:   resp.StatusCode
来源：http://dali.sufxvd.cn/Article/details/gtpvmbmijq.html

Ruby: resp.code.to_i
来源：http://dali.jqgufenzy.top/Article/details/gtgrqiokox.html

C#:   (int)resp.StatusCode
来源：http://dali.smart0.xyz/Article/details/gtygznzihd.html

[L08] 并发请求多个地址
来源：http://dali.yj202588.top/Article/details/gtzudiamci.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ehwqpu.com/Article/details/gtoosgqhaq.html

PHP:  curl_multi_init() 系列
来源：http://dali.aibaodan.cn/Article/details/gtmxrfojeo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258888.top/Article/details/gtbicychht.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnxiangtu.top/Article/details/gtcxyxsvng.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.haohaochexian.top/Article/details/gtgjwrpqoe.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.c1oappe.top/Article/details/gtnlxpyawn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zycfv.cn/Article/details/gtwgsrpkwv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.birdmap.top/Article/details/gtmgvacqfq.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtuywtfuti.html

M. 命令行 / 进程 / 环境
来源：http://dali.pengpengdd.cyou/Article/details/gtvrmlebjo.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtsjnbroci.html

[M01] 读取命令行参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvoqvymlq.html

Py:   sys.argv[1:]
来源：http://dali.cdnleiting.top/Article/details/gtgnweqvsn.html

PHP:  $argv;  $argc;
来源：http://dali.fzhhl.top/Article/details/gtjrwjjfbx.html

JS:   process.argv.slice(2)
来源：http://dali.xylfe.cn/Article/details/gtsgqoddps.html

TS:   process.argv.slice(2)
来源：http://dali.zycfv.cn/Article/details/gtpkfzfcfy.html

Java: args 数组（main 方法参数）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnegvurdz.html

Go:   os.Args[1:]
来源：http://dali.yongpay.top/Article/details/gtvhgfgrxc.html

Ruby: ARGV
来源：http://dali.shuidangran.top/Article/details/gtkzqbqfrs.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yueranfly.top/Article/details/gttzyiybim.html

[M02] 读取环境变量
来源：http://dali.zhengqikj.top/Article/details/gttetyuzrh.html

Py:   os.environ.get("HOME")
来源：http://dali.tianlin.xyz/Article/details/gtvofvmfyy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shangyingyoupin.top/Article/details/gtwjbqtopm.html

JS:   process.env.HOME
来源：http://dali.sweek.top/Article/details/gtkdjkjiex.html

TS:   process.env.HOME
来源：http://dali.xziqi.cn/Article/details/gtwtdqecus.html

Java: System.getenv("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtftoqdibp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtbsqqghqq.html

Ruby: ENV["HOME"]
来源：http://dali.guannengcc.top/Article/details/gthahalfqn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.9152youxi.cn/Article/details/gtmwqkfcvq.html

[M03] 执行外部命令
来源：http://dali.ehwqpu.com/Article/details/gteqlilcea.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jlsjyb.cn/Article/details/gtlzzewyda.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.aibaodan.cn/Article/details/gtnvfohkdj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuanzhike.top/Article/details/gtmytxxmji.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.316326.xyz/Article/details/gtkqnfzpfv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhiwuduotai.top/Article/details/gtknsxnlfb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tian-w.cn/Article/details/gtpeevhwpu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.nanxuanxn.top/Article/details/gttchyacca.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tianlin.xyz/Article/details/gtopmrnaur.html

[M04] 获取当前工作目录
来源：http://dali.yj20258.top/Article/details/gtbbtmpenu.html

Py:   os.getcwd()
来源：http://dali.iojbl.cn/Article/details/gtpepiqydq.html

PHP:  getcwd();
来源：http://dali.mhx1999.top/Article/details/gtktprsbaq.html

JS:   process.cwd()
来源：http://dali.havefunace.top/Article/details/gthncywjou.html

TS:   process.cwd()
来源：http://dali.sufxvd.cn/Article/details/gtbfjugoom.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xziqi.cn/Article/details/gtrovebafb.html

Go:   os.Getwd()
来源：http://dali.yuxming.cn/Article/details/gtcopdemdu.html

Ruby: Dir.pwd
来源：http://dali.jqgufenzy.top/Article/details/gtzknzxliy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.pycfn.com/Article/details/gtmvryswge.html

[M05] 设置退出码
来源：http://dali.hfpthk.cn/Article/details/gtarbdenwu.html

Py:   sys.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gtzpylugoy.html

PHP:  exit(1);
来源：http://dali.yueranfly.top/Article/details/gtzrinlemm.html

JS:   process.exit(1)
来源：http://dali.birdmap.top/Article/details/gtlfhwxbmw.html

TS:   process.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gtsgsjplqp.html

Java: System.exit(1)
来源：http://dali.xylfe.cn/Article/details/gtrolaoabv.html

Go:   os.Exit(1)
来源：http://dali.jinqigufen.top/Article/details/gtrywtqzxs.html

Ruby: exit 1
来源：http://dali.chenlongwang.top/Article/details/gtukscmued.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinqigfzy.top/Article/details/gtefxurbxe.html

[M06] 向标准错误输出
来源：http://dali.yonumen.top/Article/details/gtvgmewgeg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.bjfxy.top/Article/details/gtyukemssx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sysykeji.top/Article/details/gtcrfkipjo.html

JS:   console.error("err")
来源：http://dali.jqgufenzy.top/Article/details/gtnnugjgok.html

TS:   console.error("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqbzkvfbh.html

Java: System.err.println("err")
来源：http://dali.smart0.xyz/Article/details/gtmeydpmco.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cheryme.top/Article/details/gtcgdzuvqr.html

Ruby: warn "err"
来源：http://dali.wangdashe.top/Article/details/gtaxeoeago.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yj20258888.top/Article/details/gtidskjfhd.html

[M07] 判断是否为主入口
来源：http://dali.zhixingplan.top/Article/details/gtyulkixqa.html

Py:   if __name__ == "__main__":
来源：http://dali.guowangkeji.top/Article/details/gtyaogidbg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinghuilouyu.cn/Article/details/gtkzwnfpwn.html

JS:   require.main === module
来源：http://dali.hammf.cn/Article/details/gtfgbxjtfk.html

TS:   require.main === module
来源：http://dali.ehwqpu.com/Article/details/gthisbkdfo.html

Java: public static void main(String[] args)
来源：http://dali.zdqjudy.top/Article/details/gttcpzhjwn.html

Go:   func main()
来源：http://dali.guannengcc.top/Article/details/gtzukzleho.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.aizwys.cn/Article/details/gtiwtplgqk.html

C#:   static void Main(string[] args)
来源：http://dali.yj20258.top/Article/details/gtwewrvfat.html

[M08] 获取系统与运行时信息
来源：http://dali.cashguo.top/Article/details/gtrcqflsww.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zycfv.cn/Article/details/gtrahdvflw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.dianchejie.cn/Article/details/gtnurlwsel.html

JS:   process.platform;  process.version
来源：http://dali.guowangkeji.top/Article/details/gtxhcsgjes.html

TS:   process.platform;  process.version
来源：http://dali.zhoulong.xyz/Article/details/gtojffdhdr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yj20258.top/Article/details/gtzdxmhmqm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.andypj.xyz/Article/details/gtjybsowwo.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.tianlin.xyz/Article/details/gtzmqlzphe.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hammf.cn/Article/details/gtupsdhmzd.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtvccdltei.html

N. 数据结构与算法
来源：http://dali.tian-w.cn/Article/details/gtjrbnjiwu.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtdalugdny.html

[N01] 二分查找（有序数组）
来源：http://dali.chenjidiqi.icu/Article/details/gtpnaawvxw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtapopjors.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hfpthk.cn/Article/details/gtxkdewkav.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258888.top/Article/details/gtbstcrblw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenzaomai.com/Article/details/gttgeftbvs.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtclzebaur.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gtwwaqjqdp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.c1oappe.top/Article/details/gtukskcyxn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtqonfqeju.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zycfv.cn/Article/details/gtkpsdmbfa.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxfzepcxw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yueranfly.top/Article/details/gtpfualidk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shuidangran.top/Article/details/gttjquvxno.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cashguo.top/Article/details/gtvfvifxuf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhengqikj.top/Article/details/gtsrwwxbun.html

Go:   slices.Sort(arr)
来源：http://dali.9152youxi.cn/Article/details/gtobozuhyf.html

Ruby: arr.sort
来源：http://dali.gaohongyu789.top/Article/details/gttlycnsne.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhengqikj.top/Article/details/gtdsedlhwd.html

[N03] 快速排序（分治示例）
来源：http://dali.redwolf501.top/Article/details/gtvumbppkr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhengqikj.top/Article/details/gtbveqgisc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cqqwz.cn/Article/details/gtmoxxsenu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ppjwa.cn/Article/details/gtbnwuslnk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhoulong.xyz/Article/details/gtsvcfguym.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xylfe.cn/Article/details/gtzbtoazom.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yvedp.cn/Article/details/gtghhptggq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhongyouzk.top/Article/details/gtsiweohgt.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jianghu66.top/Article/details/gtlgipsllo.html

[N04] 斐波那契数列
来源：http://dali.mhx1999.top/Article/details/gtrjyguyby.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cashguo.top/Article/details/gtsgrvlwxs.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.guannengcc.top/Article/details/gtzcdxdiaw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gtqrbtojkv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtksfwhody.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.chenlongwang.top/Article/details/gtxuozxkuf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cheryme.top/Article/details/gtwpbercpx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtjrtezcwc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhixingplan.top/Article/details/gtkrbmjfeu.html

[N05] 最大公约数
来源：http://dali.yj202588.top/Article/details/gtmqllzvsr.html

Py:   math.gcd(a, b)
来源：http://dali.cucudq.cn/Article/details/gtxnkcxijz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtplbexkqp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.316326.xyz/Article/details/gtkrzibozt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhixingplan.top/Article/details/gtdjlcrdhq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.guowangkeji.top/Article/details/gtiswavuvx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.iojbl.cn/Article/details/gtxbzeyxbi.html

Ruby: a.gcd(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnilfrpqc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sysykeji.top/Article/details/gtqigaqbpd.html

[N06] 判断回文字符串
来源：http://dali.vqdsnc.cn/Article/details/gttmlwchwt.html

Py:   s == s[::-1]
来源：http://dali.yvedp.cn/Article/details/gtxaaorgfn.html

PHP:  $s === strrev($s);
来源：http://dali.jinqigufen.top/Article/details/gtwbfqffuc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gtzjrhznly.html

TS:   s === [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gtfgydxsta.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yonumen.top/Article/details/gtiqdnpdnv.html

Go:   // 双指针从两端比较
来源：http://dali.yueranfly.top/Article/details/gtzmuwviuk.html

Ruby: s == s.reverse
来源：http://dali.nanxinkj.top/Article/details/gtuhcgmvyg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hnqzz.top/Article/details/gtzhgxcacg.html

[N07] 两数之和（返回下标）
来源：http://dali.cucudq.cn/Article/details/gtwphjffil.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cqqwz.cn/Article/details/gtuvjvlgap.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hnqzz.top/Article/details/gtcepxeqke.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yonumen.top/Article/details/gtunblymcl.html

TS:   // 手写 Map<string, number>
来源：http://dali.shuidangran.top/Article/details/gthziwucgo.html

Java: // 手写 HashMap
来源：http://dali.nwbrower.top/Article/details/gtwcchlcyu.html

Go:   // 手写 map[int]int
来源：http://dali.vqdsnc.cn/Article/details/gttrultvps.html

Ruby: // 手写 Hash
来源：http://dali.feifeiyinyue.top/Article/details/gtkziwaypw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.dashuyun.cn/Article/details/gtmnuleqru.html

[N08] 生成全排列
来源：http://dali.sysykeji.top/Article/details/gtvewratbo.html

Py:   itertools.permutations(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtybmpqnrf.html

PHP:  // 手写递归交换
来源：http://dali.jianghu66.top/Article/details/gtlrkjlmfy.html

JS:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gtqthixxov.html

TS:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gtkzuizdsh.html

Java: // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gtogbrnztj.html

Go:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtzdeswbnd.html

Ruby: arr.permutation.to_a
来源：http://dali.cdnleiting.top/Article/details/gtwhamcsuo.html

C#:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gtxrrpppau.html

[N09] 栈与队列
来源：http://dali.hongshengwenyu.top/Article/details/gtoomrmebu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ybcxt.top/Article/details/gtzoklspuc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsalhivpu.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sxryk.cn/Article/details/gtobswfqgn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yongpay.top/Article/details/gttszwdlur.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yanxiufei.cn/Article/details/gtxxlqnnpg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cashguo.top/Article/details/gthqzbznwz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yvedp.cn/Article/details/gtnhrtarsn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.wangdashe.top/Article/details/gtuhwbwfjk.html

[N10] 链表节点定义
来源：http://dali.yangfankeji.com/Article/details/gtlfoqdckj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hnqzz.top/Article/details/gtmgztsvdq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.meibo888.top/Article/details/gtxgtcdltv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.daxiang520.top/Article/details/gtlpmilosa.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.feifeiyinyue.top/Article/details/gtgrqksvwd.html

Java: class Node { int v; Node next; }
来源：http://dali.shzxlz.cn/Article/details/gtfapltqdl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yj20258.top/Article/details/gtadurepuc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tanke756.top/Article/details/gtdnekkkam.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.iojbl.cn/Article/details/gtvwmmbbcp.html

[N11] 二叉树中序遍历
来源：http://dali.tian-w.cn/Article/details/gtzgfkxccu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.pengpengdd.cyou/Article/details/gtdqffbjkc.html

PHP:  // 手写递归函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcqirozcb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.haohaochexian.top/Article/details/gtrrryyiwu.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hongshengwenyu.top/Article/details/gtdpthqvlb.html

Java: // 手写递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtjskmhjzy.html

Go:   // 手写递归
来源：http://dali.chenlongwang.top/Article/details/gtlyplpteb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.feifeiyinyue.top/Article/details/gtmihsqqpk.html

C#:   // 手写递归
来源：http://dali.nanxinkj.top/Article/details/gtkiiosdhn.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinghuilouyu.cn/Article/details/gtesobofwx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.daria6918.cn/Article/details/gtodimcpro.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.dianchejie.cn/Article/details/gtvmyzvcyk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yongpay.top/Article/details/gtxdhuhgpy.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258888.top/Article/details/gttkihaxxe.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuanzhike.top/Article/details/gtylocrboi.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cqqwz.cn/Article/details/gtqzphltbi.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shangyingyoupin.top/Article/details/gtjuoaasfz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuxming.cn/Article/details/gthedvblbi.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtujyrxjnn.html

O. 并发与异步
来源：http://dali.yongpay.top/Article/details/gtowkyuujr.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtevgxzqrh.html

[O01] 启动一个线程
来源：http://dali.kuanghao11.cn/Article/details/gttygmgnvi.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yongpay.top/Article/details/gtabnqglgf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sufxvd.cn/Article/details/gtrltxorbk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.guowangkeji.top/Article/details/gtiuvnadko.html

TS:   // 同 JS
来源：http://dali.daxiang520.top/Article/details/gtwqzwcgin.html

Java: new Thread(() -> f()).start()
来源：http://dali.daria6918.cn/Article/details/gtulyhkrtt.html

Go:   go f()
来源：http://dali.andypj.xyz/Article/details/gtdmyikqzz.html

Ruby: Thread.new { f }
来源：http://dali.yongpay.top/Article/details/gtqkvtftdc.html

C#:   Task.Run(() => F());
来源：http://dali.aibaodan.cn/Article/details/gtznjiihtv.html

[O02] 使用线程池
来源：http://dali.kuanghao11.cn/Article/details/gtwvvxhhks.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yangfankeji.com/Article/details/gtiafkmyqq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hysaishi.cn/Article/details/gtqmszvjxy.html

JS:   // worker_threads 线程池
来源：http://dali.yj202588.top/Article/details/gtpdwriujq.html

TS:   // worker_threads 线程池
来源：http://dali.gzhubu.top/Article/details/gtwkewxodg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yonumen.top/Article/details/gtfgpmukgq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.tanke756.top/Article/details/gtrnrefjya.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcurscuts.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.daxiang520.top/Article/details/gttclmcipd.html

[O03] 加锁保护共享数据
来源：http://dali.daxiang520.top/Article/details/gtyellbqsq.html

Py:   with lock: shared += 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcribtdxc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shanyushiyangtech.top/Article/details/gtjratnuix.html


<!-- 参考信息 -->