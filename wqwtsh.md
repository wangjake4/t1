代发 wailian999

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gtqmlmtdiy.html

[K07] 进制转换
来源：http://dali.jianghu66.top/Article/details/gtdusahylk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtgzpzxnll.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.chenjidiqi.icu/Article/details/gthhhlytba.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gttifdcbru.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gtoogoewhj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtvsuqvrdw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yongpay.top/Article/details/gtpbcyojtc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.dashuyun.cn/Article/details/gtgxluhjiu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtstiegsjc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.9152youxi.cn/Article/details/gthtyhcnwm.html

Py:   pickle.dumps(obj)
来源：http://dali.0kj1m.cn/Article/details/gtwphtehtf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yuanzhike.top/Article/details/gtgtvocbqq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbmwgremb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.chenzaomai.com/Article/details/gthkgifdcj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.aibaodan.cn/Article/details/gtbdlcbepa.html

Go:   encoding/gob
来源：http://dali.gogol.net.cn/Article/details/gtpcmzpnko.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtypfhfyoq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.9152youxi.cn/Article/details/gteceludki.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtguwbnebg.html

L. 网络请求
来源：http://dali.smart0.xyz/Article/details/gtgmlkkumn.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtdibrgdfb.html

[L01] 发送 GET 请求
来源：http://dali.andypj.xyz/Article/details/gtoqmpytna.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.haohaochexian.top/Article/details/gtyszlxzuz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.fengsongda.top/Article/details/gtjchtunqb.html

JS:   await fetch(url)
来源：http://dali.xinyue.icu/Article/details/gttmujpzpp.html

TS:   await fetch(url)
来源：http://dali.redwolf501.top/Article/details/gtajycpsdu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.haohaochexian.top/Article/details/gtbowqhhrx.html

Go:   resp, err := http.Get(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuzfuuemm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ivvv.top/Article/details/gtpumqbxzb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkvilmlzj.html

[L02] 发送 POST JSON
来源：http://dali.jlsjyb.cn/Article/details/gthnvlvdbc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.daria6918.cn/Article/details/gtmfbwtwxl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.iojbl.cn/Article/details/gtxhmszzxb.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangtech.top/Article/details/gtxlfpvlos.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenzaomai.com/Article/details/gtulvdbhgl.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.redwolf501.top/Article/details/gtqysxzhcj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.andypj.xyz/Article/details/gtbwqmztmr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.tianlin.xyz/Article/details/gthjxlihys.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jiagoushi.top/Article/details/gtqnyifwqk.html

[L03] 设置自定义请求头
来源：http://dali.tian-w.cn/Article/details/gtlmuczkkb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.mhx1999.top/Article/details/gtgoushxfw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.andypj.xyz/Article/details/gtewwykpgk.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tianlin.xyz/Article/details/gtmirzzqfe.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fzhhl.top/Article/details/gtkrnxqflu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.wangdashe.top/Article/details/gtnuhgvwzw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.bjfxy.top/Article/details/gtiexewqcl.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xinyue.icu/Article/details/gttjkqqxqg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yanxiufei.cn/Article/details/gtqefhvqnz.html

[L04] 设置超时
来源：http://dali.ivvv.top/Article/details/gtybsnwckg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gzhubu.top/Article/details/gtinoarjxo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yuanzhike.top/Article/details/gtntlaaxvp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sufxvd.cn/Article/details/gtypqgbozn.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.kuanghao11.cn/Article/details/gttcfhvifk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yj202588.top/Article/details/gtmpeyxbvn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yj20258.top/Article/details/gtmgnsvzal.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nanxinkj.top/Article/details/gtdnrwkcfe.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shuidangran.top/Article/details/gtxoiwbnvw.html

[L05] 上传文件（multipart）
来源：http://dali.jianghu66.top/Article/details/gtmjsotgdl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenjidiqi.icu/Article/details/gtbcnghpjq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.fengsongda.top/Article/details/gtbfocsomf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.andypj.xyz/Article/details/gtlkticmud.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gotoacloud.top/Article/details/gtwypradit.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.iojbl.cn/Article/details/gthpfjcgnr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhengqikj.top/Article/details/gtracytytf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinyuanbaomall.cn/Article/details/gthgfrswxy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jianghu66.top/Article/details/gtujnpjzzn.html

[L06] 解析响应为 JSON
来源：http://dali.shuidangran.top/Article/details/gtgkufpvtt.html

Py:   resp.json()
来源：http://dali.zhiwuduotai.top/Article/details/gttejqcscc.html

PHP:  json_decode($body, true);
来源：http://dali.iojbl.cn/Article/details/gtlppeehmh.html

JS:   await resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gtnzhsjifr.html

TS:   await resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gtwotxmzdn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zycfv.cn/Article/details/gtlozmhthw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xuetiantiany.cn/Article/details/gtackxdbvh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gzhubu.top/Article/details/gtonaqrsdl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shuidangran.top/Article/details/gtqhiwltpe.html

[L07] 处理 HTTP 状态码
来源：http://dali.guowangkeji.top/Article/details/gtjgcblebl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.kuanghao11.cn/Article/details/gtflafbxmb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sxryk.cn/Article/details/gtknlyhwjt.html

JS:   resp.ok;  resp.status
来源：http://dali.yongpay.top/Article/details/gtwmglpozg.html

TS:   resp.ok;  resp.status
来源：http://dali.cucudq.cn/Article/details/gtjoebkdwi.html

Java: resp.statusCode()
来源：http://dali.yanxiufei.cn/Article/details/gtueudkols.html

Go:   resp.StatusCode
来源：http://dali.xinyue.icu/Article/details/gtwfozjapa.html

Ruby: resp.code.to_i
来源：http://dali.xziqi.cn/Article/details/gtakhhdote.html

C#:   (int)resp.StatusCode
来源：http://dali.zycfv.cn/Article/details/gtdrlcbnvn.html

[L08] 并发请求多个地址
来源：http://dali.jqgfzy.top/Article/details/gtgjjmtwbp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinghuilouyu.cn/Article/details/gtahquqhok.html

PHP:  curl_multi_init() 系列
来源：http://dali.ydzc1.top/Article/details/gtmfileljd.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyhxoqjsx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gttqoqtmtw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.tian-w.cn/Article/details/gtkzwdwakb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.smart0.xyz/Article/details/gtptjybhhu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yj202588.top/Article/details/gttumxcreb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gogol.net.cn/Article/details/gtjbmfxpoo.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtoriggbog.html

M. 命令行 / 进程 / 环境
来源：http://dali.mhx1999.top/Article/details/gtgqguoyhm.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtjtkkojwr.html

[M01] 读取命令行参数
来源：http://dali.yongpay.top/Article/details/gtdtmzoxaa.html

Py:   sys.argv[1:]
来源：http://dali.smart0.xyz/Article/details/gtbhhyxuqk.html

PHP:  $argv;  $argc;
来源：http://dali.yanxiufei.cn/Article/details/gtnuccyior.html

JS:   process.argv.slice(2)
来源：http://dali.yuxming.cn/Article/details/gttrfeigas.html

TS:   process.argv.slice(2)
来源：http://dali.hammf.cn/Article/details/gtynougmtv.html

Java: args 数组（main 方法参数）
来源：http://dali.0kj1m.cn/Article/details/gtpqvnwurg.html

Go:   os.Args[1:]
来源：http://dali.hnxiangtu.top/Article/details/gtrnzrixaq.html

Ruby: ARGV
来源：http://dali.yj20258888.top/Article/details/gtnohoipyf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.wangdashe.top/Article/details/gtojuzqzxo.html

[M02] 读取环境变量
来源：http://dali.gaohongyu789.top/Article/details/gtpqvlxeem.html

Py:   os.environ.get("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gtgcstbfze.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jqgfzy.top/Article/details/gttwxtddwg.html

JS:   process.env.HOME
来源：http://dali.havefunace.top/Article/details/gtpjrfyhhi.html

TS:   process.env.HOME
来源：http://dali.zhoulong.xyz/Article/details/gtaamfsdhr.html

Java: System.getenv("HOME")
来源：http://dali.yuanzhike.top/Article/details/gtppvtpucd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gthdmfgcwm.html

Ruby: ENV["HOME"]
来源：http://dali.cheryme.top/Article/details/gtwiwiooqk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cashguo.top/Article/details/gtdfjmmjsp.html

[M03] 执行外部命令
来源：http://dali.jqgufenzy.top/Article/details/gtvasfpbxk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tian-w.cn/Article/details/gttfsaxqbe.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ppjwa.cn/Article/details/gtwvvkdjxk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.guannengcc.top/Article/details/gtyglnllxo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxinkj.top/Article/details/gtfaqoqvyw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jqgufenzy.top/Article/details/gtbotrszyz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.9152youxi.cn/Article/details/gtfgpbyugz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xylfe.cn/Article/details/gtttnmmezc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ehwqpu.com/Article/details/gtpmbjwhct.html

[M04] 获取当前工作目录
来源：http://dali.ppjwa.cn/Article/details/gtfvwzqner.html

Py:   os.getcwd()
来源：http://dali.redwolf501.top/Article/details/gtvvidiqpo.html

PHP:  getcwd();
来源：http://dali.iojbl.cn/Article/details/gtohtztqtp.html

JS:   process.cwd()
来源：http://dali.jinqigfzy.top/Article/details/gtmeqwqezj.html

TS:   process.cwd()
来源：http://dali.chenjidiqi.icu/Article/details/gtrcoyrmty.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jlsjyb.cn/Article/details/gtwcjmkyyg.html

Go:   os.Getwd()
来源：http://dali.daria6918.cn/Article/details/gtfcgzerzk.html

Ruby: Dir.pwd
来源：http://dali.birdmap.top/Article/details/gtihryuexb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cdnleiting.top/Article/details/gtbpvpqfbu.html

[M05] 设置退出码
来源：http://dali.jinghuilouyu.cn/Article/details/gtwixyubcs.html

Py:   sys.exit(1)
来源：http://dali.havefunace.top/Article/details/gtvfgcttdd.html

PHP:  exit(1);
来源：http://dali.fengsongda.top/Article/details/gtlmqumymq.html

JS:   process.exit(1)
来源：http://dali.daxiang520.top/Article/details/gteathinje.html

TS:   process.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtjpuwqdnl.html

Java: System.exit(1)
来源：http://dali.tanke756.top/Article/details/gthsxghllq.html

Go:   os.Exit(1)
来源：http://dali.snrcjt.cn/Article/details/gtjctoenop.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gtficblwch.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yuanzhike.top/Article/details/gtzfbmtiwp.html

[M06] 向标准错误输出
来源：http://dali.hammf.cn/Article/details/gtpomldpqv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zycfv.cn/Article/details/gtyapmyuem.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.pengpengdd.cyou/Article/details/gtjhlawtla.html

JS:   console.error("err")
来源：http://dali.hysaishi.cn/Article/details/gtbjrblhdd.html

TS:   console.error("err")
来源：http://dali.jianghu66.top/Article/details/gtbnsbeaek.html

Java: System.err.println("err")
来源：http://dali.jiagoushi.top/Article/details/gtgisqhgop.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwiatrccd.html

Ruby: warn "err"
来源：http://dali.yvedp.cn/Article/details/gtxwycponk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sweek.top/Article/details/gtqhhnmqrw.html

[M07] 判断是否为主入口
来源：http://dali.fengsongda.top/Article/details/gtzzbptdnz.html

Py:   if __name__ == "__main__":
来源：http://dali.zycfv.cn/Article/details/gthsmjuwzl.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.wangdashe.top/Article/details/gtrwogwtid.html

JS:   require.main === module
来源：http://dali.quarkkingdee.top/Article/details/gtmksktjxt.html

TS:   require.main === module
来源：http://dali.iojbl.cn/Article/details/gtbpywycfa.html

Java: public static void main(String[] args)
来源：http://dali.shanyushiyangtech.top/Article/details/gtevsrmjlj.html

Go:   func main()
来源：http://dali.svipenyu.cn/Article/details/gtfecfjcvu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.guowangkeji.top/Article/details/gtksoidaca.html

C#:   static void Main(string[] args)
来源：http://dali.gaohongyu789.top/Article/details/gtsmizghrw.html

[M08] 获取系统与运行时信息
来源：http://dali.hnxiangtu.top/Article/details/gtskakzurk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yongpay.top/Article/details/gtqtlqfplq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yueranfly.top/Article/details/gtitpkyxjq.html

JS:   process.platform;  process.version
来源：http://dali.meibo888.top/Article/details/gtpseoqaja.html

TS:   process.platform;  process.version
来源：http://dali.gzhubu.top/Article/details/gtomofkvvz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.9152youxi.cn/Article/details/gtticpkxat.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yongpay.top/Article/details/gtyibscses.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sysykeji.top/Article/details/gtkxazuvpl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.chenjidiqi.icu/Article/details/gtcpqlzioy.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtfdsbbquz.html

N. 数据结构与算法
来源：http://dali.zhongyouzk.top/Article/details/gtcqlqgdeg.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtveqvhkqo.html

[N01] 二分查找（有序数组）
来源：http://dali.316326.xyz/Article/details/gthkwziily.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtkygjnegz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jianghu66.top/Article/details/gtftngdlix.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yonumen.top/Article/details/gtgaxlkfek.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkzjhshdq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gtlqhykzmi.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtboewihxr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.haohaochexian.top/Article/details/gtwvkmoznf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtvxlhfyvl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gtlwpttalb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shangyingyoupin.top/Article/details/gtbloahtqw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ybcxt.top/Article/details/gtufkjwwbz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.c1oappe.top/Article/details/gtjvprabyc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxinkj.top/Article/details/gtqsgyvbzb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.gaohongyu789.top/Article/details/gtnbgvwnet.html

Go:   slices.Sort(arr)
来源：http://dali.ybcxt.top/Article/details/gtgokptrjl.html

Ruby: arr.sort
来源：http://dali.quarkkingdee.top/Article/details/gtfnmmagam.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.snrcjt.cn/Article/details/gtpjmclocw.html

[N03] 快速排序（分治示例）
来源：http://dali.xinyue.icu/Article/details/gtjvwgnyxi.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.pycfn.com/Article/details/gtiwawdniq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tanke756.top/Article/details/gtlahueigv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gtzwcmfpiq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dashuyun.cn/Article/details/gtcooztcze.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shanyushiyangtech.top/Article/details/gtaycwqcsr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.aizwys.cn/Article/details/gtniopkcdr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.chenzaomai.com/Article/details/gtgbudymlf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ydzc1.top/Article/details/gtbhvqckvr.html

[N04] 斐波那契数列
来源：http://dali.hysaishi.cn/Article/details/gtfufqifzf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yangfankeji.com/Article/details/gtwjyrdaja.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.0kj1m.cn/Article/details/gtumgllkfd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gtfcrxmgdb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.redwolf501.top/Article/details/gtnrcrxujy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gtscuxbsfl.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hongshengwenyu.top/Article/details/gtblskybbj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj202588.top/Article/details/gtklyhljsn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.guannengcc.top/Article/details/gtyfvydjjm.html

[N05] 最大公约数
来源：http://dali.tian-w.cn/Article/details/gtjsrttjpo.html

Py:   math.gcd(a, b)
来源：http://dali.xuetiantiany.cn/Article/details/gtekefjfkc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.dianchejie.cn/Article/details/gtoizxjxro.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yonumen.top/Article/details/gtafxijhlx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cucudq.cn/Article/details/gtshuowelg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhongyouzk.top/Article/details/gtwrmumpkg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.meibo888.top/Article/details/gtlxqpgiea.html

Ruby: a.gcd(b)
来源：http://dali.jinqigufen.top/Article/details/gtylumdsso.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.dashuyun.cn/Article/details/gtjrwdrohf.html

[N06] 判断回文字符串
来源：http://dali.bjfxy.top/Article/details/gtbshrkicw.html

Py:   s == s[::-1]
来源：http://dali.ppjwa.cn/Article/details/gtzrwztzoa.html

PHP:  $s === strrev($s);
来源：http://dali.ybcxt.top/Article/details/gthlogwdxw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdhqwxwua.html

TS:   s === [...s].reverse().join("")
来源：http://dali.vqdsnc.cn/Article/details/gtxyexjzxd.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.pengpengdd.cyou/Article/details/gtsiaxerfw.html

Go:   // 双指针从两端比较
来源：http://dali.zhongyouzk.top/Article/details/gtiwuqicvw.html

Ruby: s == s.reverse
来源：http://dali.jianghu66.top/Article/details/gtvxljtpqx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.chenlongwang.top/Article/details/gthcocabee.html

[N07] 两数之和（返回下标）
来源：http://dali.redwolf501.top/Article/details/gtnbiepvku.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinqigufen.top/Article/details/gtbyxuswva.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sysykeji.top/Article/details/gtkwjuspws.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.tianlin.xyz/Article/details/gtuwvnaygg.html

TS:   // 手写 Map<string, number>
来源：http://dali.gogol.net.cn/Article/details/gtmrlnatlo.html

Java: // 手写 HashMap
来源：http://dali.svipenyu.cn/Article/details/gtwdgsslip.html

Go:   // 手写 map[int]int
来源：http://dali.jiagoushi.top/Article/details/gtmvdfjbnn.html

Ruby: // 手写 Hash
来源：http://dali.hongshengwenyu.top/Article/details/gttzctjrgi.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.meibo888.top/Article/details/gtmmsxoibv.html

[N08] 生成全排列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsbszemge.html

Py:   itertools.permutations(arr)
来源：http://dali.jqgfzy.top/Article/details/gtvnsvhahi.html

PHP:  // 手写递归交换
来源：http://dali.jianghu66.top/Article/details/gtzbimcbob.html

JS:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gtxfahlvys.html

TS:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtwftnzbux.html

Java: // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gtqwqdeygx.html

Go:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gtjeqpyuab.html

Ruby: arr.permutation.to_a
来源：http://dali.pycfn.com/Article/details/gtprqposjm.html

C#:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtivoxlkyb.html

[N09] 栈与队列
来源：http://dali.0kj1m.cn/Article/details/gtpbpijnju.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jqgufenzy.top/Article/details/gtzckxeczt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.guowangkeji.top/Article/details/gtymajtwzc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gzhubu.top/Article/details/gtkbjwlwgf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jlsjyb.cn/Article/details/gtjxeypfiw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinqigfzy.top/Article/details/gtmcuofipo.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cdnleiting.top/Article/details/gtncgjibth.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sysykeji.top/Article/details/gtunkpkydr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.tianlin.xyz/Article/details/gthegjoapb.html

[N10] 链表节点定义
来源：http://dali.cucudq.cn/Article/details/gtmfaopsby.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sufxvd.cn/Article/details/gttsovbgtz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhengqikj.top/Article/details/gtsvvedtwb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shzxlz.cn/Article/details/gtfcrwlcrm.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hongshengwenyu.top/Article/details/gtdsewweon.html

Java: class Node { int v; Node next; }
来源：http://dali.zhengqikj.top/Article/details/gtawyacuvs.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.vqdsnc.cn/Article/details/gtdufwdqno.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jqgfzy.top/Article/details/gtpydcrgki.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.svipenyu.cn/Article/details/gtoadusbkm.html

[N11] 二叉树中序遍历
来源：http://dali.jqgfzy.top/Article/details/gtvnsyrkqm.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.aizwys.cn/Article/details/gtzxsklzzi.html

PHP:  // 手写递归函数
来源：http://dali.hnxiangtu.top/Article/details/gtlckrjnev.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xziqi.cn/Article/details/gtcfkrruot.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.snrcjt.cn/Article/details/gtxciooxjt.html

Java: // 手写递归
来源：http://dali.chenjidiqi.icu/Article/details/gtwksdrnza.html

Go:   // 手写递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvsoivtkw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yongpay.top/Article/details/gtgocddtmi.html

C#:   // 手写递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtwrrjzali.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cheryme.top/Article/details/gtzmpyeejp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shzxlz.cn/Article/details/gtslxzlhdh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jqgfzy.top/Article/details/gtkqejtebf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dianchejie.cn/Article/details/gtrdtcsweu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hammf.cn/Article/details/gtptcntzhx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj202588.top/Article/details/gtzkduozld.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.haohaochexian.top/Article/details/gtsmbpsbfa.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shuidangran.top/Article/details/gtswwklcjy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aizwys.cn/Article/details/gtfitdnpzp.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtyaulvatm.html

O. 并发与异步
来源：http://dali.daxiang520.top/Article/details/gtbmwhmbvd.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtajcgynsl.html

[O01] 启动一个线程
来源：http://dali.chenzaomai.com/Article/details/gtylymrevq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jinqigfzy.top/Article/details/gtqwlptsjd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yj20258888.top/Article/details/gtmcqxwknt.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ydzc1.top/Article/details/gttaprtklp.html

TS:   // 同 JS
来源：http://dali.cucudq.cn/Article/details/gtnqxerkye.html

Java: new Thread(() -> f()).start()
来源：http://dali.cdnleiting.top/Article/details/gtlmermmiu.html

Go:   go f()
来源：http://dali.fzhhl.top/Article/details/gtsnukzwwg.html

Ruby: Thread.new { f }
来源：http://dali.cucudq.cn/Article/details/gtkdxufzdw.html

C#:   Task.Run(() => F());
来源：http://dali.birdmap.top/Article/details/gtzzhgkyxa.html

[O02] 使用线程池
来源：http://dali.tanke756.top/Article/details/gthdsjirck.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cucudq.cn/Article/details/gthekigjsb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinqigufen.top/Article/details/gtaoncliag.html

JS:   // worker_threads 线程池
来源：http://dali.ehwqpu.com/Article/details/gtiagqybia.html

TS:   // worker_threads 线程池
来源：http://dali.sxryk.cn/Article/details/gthudvgowc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhiwuduotai.top/Article/details/gtsuvyrtau.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yueranfly.top/Article/details/gttrhrbunh.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhoulong.xyz/Article/details/gtbcxfutuk.html


<!-- 参考信息 -->