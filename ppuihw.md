代发 wailian999

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gtfldbmmky.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gtyiptjopy.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpwnaavca.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zycfv.cn/Article/details/gtsxkfjjcg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cqqwz.cn/Article/details/gtvbausfaf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gtufetguqi.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ivvv.top/Article/details/gtipgwtdow.html

Py:   pickle.dumps(obj)
来源：http://dali.yj20258.top/Article/details/gtayyzkcvh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hywenlv.cn/Article/details/gtjxnkbdxg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yvedp.cn/Article/details/gtpqnluklg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.quarkkingdee.top/Article/details/gtmugwitsw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.haohaochexian.top/Article/details/gttajipdgm.html

Go:   encoding/gob
来源：http://dali.andypj.xyz/Article/details/gtxxqugiow.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhixingplan.top/Article/details/gttgliyxxv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hnxiangtu.top/Article/details/gtuksaeqom.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gttrylpukq.html

L. 网络请求
来源：http://dali.zdqjudy.top/Article/details/gtizbvbhjn.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtibkqwifv.html

[L01] 发送 GET 请求
来源：http://dali.havefunace.top/Article/details/gtnnvoznio.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.andypj.xyz/Article/details/gtzcbgzwtl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nanxinkj.top/Article/details/gtamrnbmqi.html

JS:   await fetch(url)
来源：http://dali.chenjidiqi.icu/Article/details/gtrepgkuna.html

TS:   await fetch(url)
来源：http://dali.hongshengwenyu.top/Article/details/gtrsbdqjhg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sysykeji.top/Article/details/gtjxtchfbh.html

Go:   resp, err := http.Get(url)
来源：http://dali.hnqzz.top/Article/details/gthylfvixm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.guowangkeji.top/Article/details/gtcjcawlhl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cqqwz.cn/Article/details/gtgiidnirb.html

[L02] 发送 POST JSON
来源：http://dali.hywenlv.cn/Article/details/gtftqqxgzr.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.tanke756.top/Article/details/gtfwxptsam.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgyqlujkc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoqhhtbie.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sxryk.cn/Article/details/gtzaoraigu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.daxiang520.top/Article/details/gtaxcggoqb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.svipenyu.cn/Article/details/gtlkwpigga.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yongpay.top/Article/details/gtmksljdso.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hysaishi.cn/Article/details/gtssdvcwyn.html

[L03] 设置自定义请求头
来源：http://dali.shzxlz.cn/Article/details/gtfkinwlts.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhiwuduotai.top/Article/details/gtmppstxkj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sweek.top/Article/details/gtgfdlzygl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cucudq.cn/Article/details/gthxrzxdlh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhiwuduotai.top/Article/details/gtosokegws.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cheryme.top/Article/details/gtnxbfgxgj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhoulong.xyz/Article/details/gticbpnbbl.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.wangdashe.top/Article/details/gtfinixkwv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.dashuyun.cn/Article/details/gtufcqtecb.html

[L04] 设置超时
来源：http://dali.yangfankeji.com/Article/details/gtylfvfnvx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yanxiufei.cn/Article/details/gtdlnqbohj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hysaishi.cn/Article/details/gtutrzaure.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangdashe.top/Article/details/gtslvobtbm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cucudq.cn/Article/details/gtbjwjycik.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.nanxuanxn.top/Article/details/gtfyhcjxbb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sxryk.cn/Article/details/gtsnbzwdqq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nwbrower.top/Article/details/gtdiykphij.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdzuqwamd.html

[L05] 上传文件（multipart）
来源：http://dali.yongpay.top/Article/details/gtxrkpduhm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yvedp.cn/Article/details/gtwhwgsfbj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj20258.top/Article/details/gtlnuikeob.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.guowangkeji.top/Article/details/gtdeheryes.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xylfe.cn/Article/details/gtandxtkfd.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.mhx1999.top/Article/details/gthldjfikv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jlsjyb.cn/Article/details/gtxylysfdh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.quarkkingdee.top/Article/details/gthtozupne.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yongpay.top/Article/details/gtpdorveww.html

[L06] 解析响应为 JSON
来源：http://dali.fengsongda.top/Article/details/gtxrayfknj.html

Py:   resp.json()
来源：http://dali.zycfv.cn/Article/details/gtipzoskxp.html

PHP:  json_decode($body, true);
来源：http://dali.andypj.xyz/Article/details/gtmqlqppna.html

JS:   await resp.json()
来源：http://dali.havefunace.top/Article/details/gtbwclobmg.html

TS:   await resp.json()
来源：http://dali.zhiwuduotai.top/Article/details/gtxmkyqihx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.0kj1m.cn/Article/details/gtsjszdzme.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sweek.top/Article/details/gtayjyqcup.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cdnleiting.top/Article/details/gtorccazik.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gzhubu.top/Article/details/gtptvhulhu.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj20258.top/Article/details/gtqpmbqkox.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yonumen.top/Article/details/gtgdsxmpfu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xuetiantiany.cn/Article/details/gtyrgsqjzi.html

JS:   resp.ok;  resp.status
来源：http://dali.daxiang520.top/Article/details/gtgjzxuxnw.html

TS:   resp.ok;  resp.status
来源：http://dali.chenzaomai.com/Article/details/gtpqvjsovs.html

Java: resp.statusCode()
来源：http://dali.ehwqpu.com/Article/details/gtusuzeiee.html

Go:   resp.StatusCode
来源：http://dali.quarkkingdee.top/Article/details/gtbkxtuicq.html

Ruby: resp.code.to_i
来源：http://dali.hammf.cn/Article/details/gtpxyscspf.html

C#:   (int)resp.StatusCode
来源：http://dali.316326.xyz/Article/details/gtlcvhvjlp.html

[L08] 并发请求多个地址
来源：http://dali.9152youxi.cn/Article/details/gtwixyhjmd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cucudq.cn/Article/details/gtzmnwkqbk.html

PHP:  curl_multi_init() 系列
来源：http://dali.kuanghao11.cn/Article/details/gthazykqoi.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrjbwhcbc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuanzx.com/Article/details/gtqntesrtq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ydzc1.top/Article/details/gtethwpkoe.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.havefunace.top/Article/details/gtoenbfzpp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sufxvd.cn/Article/details/gtbhojpztn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hnqzz.top/Article/details/gteuhpunnu.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtptrkoupy.html

M. 命令行 / 进程 / 环境
来源：http://dali.tanke756.top/Article/details/gtotyhuwco.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtyrmqhdxh.html

[M01] 读取命令行参数
来源：http://dali.fengsongda.top/Article/details/gtovosutbx.html

Py:   sys.argv[1:]
来源：http://dali.snrcjt.cn/Article/details/gtmpfnikok.html

PHP:  $argv;  $argc;
来源：http://dali.nanxinkj.top/Article/details/gtlqsomqcj.html

JS:   process.argv.slice(2)
来源：http://dali.nwbrower.top/Article/details/gtyyapnzra.html

TS:   process.argv.slice(2)
来源：http://dali.cqqwz.cn/Article/details/gtzpqsmlmk.html

Java: args 数组（main 方法参数）
来源：http://dali.316326.xyz/Article/details/gtexsczfhh.html

Go:   os.Args[1:]
来源：http://dali.ehwqpu.com/Article/details/gtifegxarn.html

Ruby: ARGV
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxeiqwyij.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jiagoushi.top/Article/details/gtdtnrcxva.html

[M02] 读取环境变量
来源：http://dali.zhongyouzk.top/Article/details/gturjpikmo.html

Py:   os.environ.get("HOME")
来源：http://dali.hywenlv.cn/Article/details/gtwbnjltgv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.fengsongda.top/Article/details/gtwytvmhqz.html

JS:   process.env.HOME
来源：http://dali.zdqjudy.top/Article/details/gttwhkfuqt.html

TS:   process.env.HOME
来源：http://dali.wangdashe.top/Article/details/gtlumkqwmf.html

Java: System.getenv("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwwkvefdn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.andypj.xyz/Article/details/gtfhibrybw.html

Ruby: ENV["HOME"]
来源：http://dali.zhengqikj.top/Article/details/gtzfwouuki.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.bjfxy.top/Article/details/gtpqbmxgno.html

[M03] 执行外部命令
来源：http://dali.zhengqikj.top/Article/details/gteujfihjd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jqgufenzy.top/Article/details/gtmmnvsldl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ybcxt.top/Article/details/gtkhfuhezb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyhdeoizc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xziqi.cn/Article/details/gtzfpaqtov.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hywenlv.cn/Article/details/gtkehoegqk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.pycfn.com/Article/details/gtwsazerxr.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.birdmap.top/Article/details/gthldgxcco.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cdnleiting.top/Article/details/gtghhvbgmc.html

[M04] 获取当前工作目录
来源：http://dali.fzhhl.top/Article/details/gtkurssddk.html

Py:   os.getcwd()
来源：http://dali.jqgfzy.top/Article/details/gtjkfcbujp.html

PHP:  getcwd();
来源：http://dali.hnqzz.top/Article/details/gtpugwmfji.html

JS:   process.cwd()
来源：http://dali.hammf.cn/Article/details/gtgnnnvfkv.html

TS:   process.cwd()
来源：http://dali.jyoumei.cn/Article/details/gtcmnifhwh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenlongwang.top/Article/details/gtuvjyegdk.html

Go:   os.Getwd()
来源：http://dali.havefunace.top/Article/details/gtmsnciwnm.html

Ruby: Dir.pwd
来源：http://dali.jqgufenzy.top/Article/details/gtqnwvvtpy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hfpthk.cn/Article/details/gthjnsyuuh.html

[M05] 设置退出码
来源：http://dali.shangyingyoupin.top/Article/details/gtuprmikyx.html

Py:   sys.exit(1)
来源：http://dali.xuanzx.com/Article/details/gtbukppwvo.html

PHP:  exit(1);
来源：http://dali.jlsjyb.cn/Article/details/gtqpweqybc.html

JS:   process.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gtdtifycui.html

TS:   process.exit(1)
来源：http://dali.smart0.xyz/Article/details/gtrwmgcfvu.html

Java: System.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtzsasbpwj.html

Go:   os.Exit(1)
来源：http://dali.c1oappe.top/Article/details/gtehrnuwha.html

Ruby: exit 1
来源：http://dali.sweek.top/Article/details/gtgkxawjmg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.dianchejie.cn/Article/details/gttlxqpuxa.html

[M06] 向标准错误输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwsnuvima.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhoulong.xyz/Article/details/gtoykfxeas.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yj20258.top/Article/details/gtmkvkbypt.html

JS:   console.error("err")
来源：http://dali.sweek.top/Article/details/gtadtkaiwb.html

TS:   console.error("err")
来源：http://dali.cashguo.top/Article/details/gtrjkuemsa.html

Java: System.err.println("err")
来源：http://dali.aizwys.cn/Article/details/gtfartifrl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.chenlongwang.top/Article/details/gtisnniuyw.html

Ruby: warn "err"
来源：http://dali.nwbrower.top/Article/details/gtxbuxizsf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.0kj1m.cn/Article/details/gtzhsbhyfv.html

[M07] 判断是否为主入口
来源：http://dali.jiagoushi.top/Article/details/gtrttmoeqs.html

Py:   if __name__ == "__main__":
来源：http://dali.yj20258.top/Article/details/gtmkcwxcjg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yueranfly.top/Article/details/gtpkswiece.html

JS:   require.main === module
来源：http://dali.cdnleiting.top/Article/details/gtojbjfbzk.html

TS:   require.main === module
来源：http://dali.aizwys.cn/Article/details/gtvwzdioze.html

Java: public static void main(String[] args)
来源：http://dali.xziqi.cn/Article/details/gtybximcta.html

Go:   func main()
来源：http://dali.jinqigufen.top/Article/details/gtnxvxojjg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.havefunace.top/Article/details/gtrjxzkzsp.html

C#:   static void Main(string[] args)
来源：http://dali.sweek.top/Article/details/gtzouffapn.html

[M08] 获取系统与运行时信息
来源：http://dali.zhoulong.xyz/Article/details/gtcgvbqfyy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hnqzz.top/Article/details/gtbeduqzga.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.wangshuangyany.cn/Article/details/gtcxwkzrql.html

JS:   process.platform;  process.version
来源：http://dali.daxiang520.top/Article/details/gtawitszbd.html

TS:   process.platform;  process.version
来源：http://dali.fengsongda.top/Article/details/gtgkbzettg.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.tanke756.top/Article/details/gtrbosmvqr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sysykeji.top/Article/details/gtcbamzppt.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.haohaochexian.top/Article/details/gteibapgfo.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jianghu66.top/Article/details/gtsbwxenfx.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtooqtxucp.html

N. 数据结构与算法
来源：http://dali.svipenyu.cn/Article/details/gtudzsmfqh.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtqtglsbsn.html

[N01] 二分查找（有序数组）
来源：http://dali.sysykeji.top/Article/details/gtrzvztsfz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsqykeayz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yangfankeji.com/Article/details/gtjusrhupa.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.0kj1m.cn/Article/details/gtghaljtqz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cucudq.cn/Article/details/gthrmnzjbx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtmginicig.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtyuwiwclj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zdqjudy.top/Article/details/gtkdjzzpvl.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gtlcchnkkd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jqgufenzy.top/Article/details/gtdkkiyqwd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangkeji.top/Article/details/gttgmgtyod.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.pycfn.com/Article/details/gtmtleabrk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xinyue.icu/Article/details/gtrdfdawxf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dianchejie.cn/Article/details/gtdvnylhia.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yj20258888.top/Article/details/gtlnpgrtgl.html

Go:   slices.Sort(arr)
来源：http://dali.sxryk.cn/Article/details/gtdtqcsbqb.html

Ruby: arr.sort
来源：http://dali.xylfe.cn/Article/details/gtoxzfjnya.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.daria6918.cn/Article/details/gtxaorudvy.html

[N03] 快速排序（分治示例）
来源：http://dali.gogol.net.cn/Article/details/gtlwfsermp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gotoacloud.top/Article/details/gtyfjotklj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.daxiang520.top/Article/details/gtnlfkxuvu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.smart0.xyz/Article/details/gtdlzijquf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.316326.xyz/Article/details/gtkrogbpgw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yanxiufei.cn/Article/details/gtchihyugq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jianghu66.top/Article/details/gtokncyzhg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.smart0.xyz/Article/details/gtiflkgaya.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gaohongyu789.top/Article/details/gtnsrbjvlo.html

[N04] 斐波那契数列
来源：http://dali.havefunace.top/Article/details/gtnrroafnf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtkzdlddfj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.pengpengdd.cyou/Article/details/gtolhyvsmb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cdnleiting.top/Article/details/gtmtvdmhtv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.iojbl.cn/Article/details/gtrnsmlvle.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jianghu66.top/Article/details/gtwcctqduw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xuetiantiany.cn/Article/details/gtnmikvivj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.fzhhl.top/Article/details/gtkqfciitv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.316326.xyz/Article/details/gtrfskobvp.html

[N05] 最大公约数
来源：http://dali.zhixingplan.top/Article/details/gtgzhyhice.html

Py:   math.gcd(a, b)
来源：http://dali.aibaodan.cn/Article/details/gttsrhacuw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jyoumei.cn/Article/details/gtpvjxaxno.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.0kj1m.cn/Article/details/gtpzfdmviy.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.andypj.xyz/Article/details/gtruizzdal.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hongshengwenyu.top/Article/details/gtjbvpzpbc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhongyouzk.top/Article/details/gtvdbicevv.html

Ruby: a.gcd(b)
来源：http://dali.aizwys.cn/Article/details/gtcmbideil.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gzhubu.top/Article/details/gtxaqairsx.html

[N06] 判断回文字符串
来源：http://dali.yueranfly.top/Article/details/gtiaeixeuq.html

Py:   s == s[::-1]
来源：http://dali.9152youxi.cn/Article/details/gttspgitez.html

PHP:  $s === strrev($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtidmvzfam.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gtumcapupc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gtufcqelvh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinqigufen.top/Article/details/gtggezldww.html

Go:   // 双指针从两端比较
来源：http://dali.shangyingyoupin.top/Article/details/gtqgeskmit.html

Ruby: s == s.reverse
来源：http://dali.meibo888.top/Article/details/gtkuirwbou.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sweek.top/Article/details/gtzjgefnva.html

[N07] 两数之和（返回下标）
来源：http://dali.tian-w.cn/Article/details/gtqiespowo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yj20258888.top/Article/details/gtmyuoqqiv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xylfe.cn/Article/details/gtthqlnvdh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yonumen.top/Article/details/gtpkcdtnci.html

TS:   // 手写 Map<string, number>
来源：http://dali.yj20258888.top/Article/details/gtvouwkpgn.html

Java: // 手写 HashMap
来源：http://dali.nanxinkj.top/Article/details/gtmkywbvwc.html

Go:   // 手写 map[int]int
来源：http://dali.jinqigfzy.top/Article/details/gtnujqafwd.html

Ruby: // 手写 Hash
来源：http://dali.yj202588.top/Article/details/gtsatqmuni.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zdqjudy.top/Article/details/gtmnuzqvmp.html

[N08] 生成全排列
来源：http://dali.cheryme.top/Article/details/gtpusotahc.html

Py:   itertools.permutations(arr)
来源：http://dali.sxryk.cn/Article/details/gtrvfcrogd.html

PHP:  // 手写递归交换
来源：http://dali.sxryk.cn/Article/details/gtnotfqtci.html

JS:   // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gtnrapihbm.html

TS:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gtxjwwbrnw.html

Java: // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtczpklzku.html

Go:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gtbyotpsyv.html

Ruby: arr.permutation.to_a
来源：http://dali.smart0.xyz/Article/details/gtgukgcfix.html

C#:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtglbrtyri.html

[N09] 栈与队列
来源：http://dali.cqqwz.cn/Article/details/gtegsgeokp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinqigufen.top/Article/details/gtgceeyzrh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtidgdaekv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhongyouzk.top/Article/details/gtkqijtxeo.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.dashuyun.cn/Article/details/gtjqyhlwjx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.9152youxi.cn/Article/details/gtygjvhefs.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaulprgjk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gtcukuzlzg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yanxiufei.cn/Article/details/gtutwlidve.html

[N10] 链表节点定义
来源：http://dali.chenjidiqi.icu/Article/details/gtbidhjfyd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yuanzhike.top/Article/details/gttxhtidtf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.nanxuanxn.top/Article/details/gtxzdhnqcl.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hfpthk.cn/Article/details/gtgtmhblkp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.pengpengdd.cyou/Article/details/gtlhxacujd.html

Java: class Node { int v; Node next; }
来源：http://dali.hongshengwenyu.top/Article/details/gtzhjvmjbh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sxryk.cn/Article/details/gtbkcjsobd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cashguo.top/Article/details/gtxpafduwn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xuetiantiany.cn/Article/details/gtdexlhcjs.html

[N11] 二叉树中序遍历
来源：http://dali.mhx1999.top/Article/details/gtzfpzewll.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.0kj1m.cn/Article/details/gtmijqblki.html

PHP:  // 手写递归函数
来源：http://dali.mhx1999.top/Article/details/gtxmvtoxdf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xinyue.icu/Article/details/gtvxsaszfm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shuidangran.top/Article/details/gtpbygrzlc.html

Java: // 手写递归
来源：http://dali.hysaishi.cn/Article/details/gtbfzvnedg.html

Go:   // 手写递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvlqrxxnx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhongyouzk.top/Article/details/gtsdjwcdwf.html

C#:   // 手写递归
来源：http://dali.andypj.xyz/Article/details/gtusxihuef.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.nanxinkj.top/Article/details/gthwvmcxbd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.aizwys.cn/Article/details/gtwjehhngh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.aibaodan.cn/Article/details/gtwfhvoxgt.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ybcxt.top/Article/details/gthqdktuiu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aibaodan.cn/Article/details/gtninejfds.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sufxvd.cn/Article/details/gtyfhpbzfc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.gotoacloud.top/Article/details/gtssmpbmnj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.0kj1m.cn/Article/details/gtcrnolzkk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aizwys.cn/Article/details/gtvnexcmfj.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtfjcevrwh.html

O. 并发与异步
来源：http://dali.yj20258888.top/Article/details/gtjbvhaeki.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gteoxjynrd.html

[O01] 启动一个线程
来源：http://dali.xziqi.cn/Article/details/gtyziazwuz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhixingplan.top/Article/details/gtuxkixraw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cashguo.top/Article/details/gtnmbzafiw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdonkiwzk.html

TS:   // 同 JS
来源：http://dali.gotoacloud.top/Article/details/gtncyartfl.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlwmizpld.html

Go:   go f()
来源：http://dali.nwbrower.top/Article/details/gteqxsuqfu.html

Ruby: Thread.new { f }
来源：http://dali.vqdsnc.cn/Article/details/gtzpwyskrk.html

C#:   Task.Run(() => F());
来源：http://dali.cdnleiting.top/Article/details/gtqrwpllhl.html

[O02] 使用线程池
来源：http://dali.yj20258.top/Article/details/gtcgltzbqj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hnxiangtu.top/Article/details/gtptvzimcu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.wangshuangyany.cn/Article/details/gtuumftpzm.html

JS:   // worker_threads 线程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gtahwsmfoq.html

TS:   // worker_threads 线程池
来源：http://dali.jinqigufen.top/Article/details/gtjetmsmpt.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.kuanghao11.cn/Article/details/gthzuojuqd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hnxiangtu.top/Article/details/gthyvuebgd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.dianchejie.cn/Article/details/gtmaewwtch.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.smart0.xyz/Article/details/gthqjsefuf.html

[O03] 加锁保护共享数据
来源：http://dali.zhaomingkeji.xyz/Article/details/gthtxrxylm.html

Py:   with lock: shared += 1
来源：http://dali.birdmap.top/Article/details/gtzqryaqby.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.svipenyu.cn/Article/details/gtufqkltuu.html


<!-- 参考信息 -->