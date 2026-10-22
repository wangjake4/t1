代发 wailian999

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kxvqoavk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.vqdsnc.cn/Article/details/gt2apxhwryh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.vqdsnc.cn/Article/details/gt2xeyecjwy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhongyouzk.top/Article/details/gt2mdnhfkdz.html

[K06] 解析 URL 查询串
来源：http://dali.0kj1m.cn/Article/details/gt2ufzhbqct.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.wangshuangyany.cn/Article/details/gt2jayvopzv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.aibaodan.cn/Article/details/gt2zknoyoyh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvcbhkev.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenzaomai.com/Article/details/gt2ovvwbjam.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.feifeiyinyue.top/Article/details/gt2efpuuajj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.redwolf501.top/Article/details/gt2keyxbblg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ivvv.top/Article/details/gt2gomejyea.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hammf.cn/Article/details/gt2kpjcfabv.html

[K07] 进制转换
来源：http://dali.cucudq.cn/Article/details/gt2rxkdeusg.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gt2qdaoojxh.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ehwqpu.com/Article/details/gt2bbjivhuh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gt2necerjze.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gt2ftmrwalu.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gt2irdbomif.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nanxinkj.top/Article/details/gt2ofemvprl.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2izpbbigo.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gt2syapltwr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvgataz.html

Py:   pickle.dumps(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2kpzxvoyo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2usospobh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.kuanghao11.cn/Article/details/gt2zfqdjizo.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cashguo.top/Article/details/gt2flilvjta.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.nanxinkj.top/Article/details/gt2avmqekmz.html

Go:   encoding/gob
来源：http://dali.guowangkeji.top/Article/details/gt2kscmahdf.html

Ruby: Marshal.dump(obj)
来源：http://dali.bjfxy.top/Article/details/gt2imulzgzr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gzhubu.top/Article/details/gt2qxuyelsg.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2tcfgxpky.html

L. 网络请求
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dhiczsdi.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2ptjsalul.html

[L01] 发送 GET 请求
来源：http://dali.daxiang520.top/Article/details/gt2nzqrobei.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jlsjyb.cn/Article/details/gt2ludvekft.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zawqlpzy.html

JS:   await fetch(url)
来源：http://dali.zhixingplan.top/Article/details/gt2bmctpzuo.html

TS:   await fetch(url)
来源：http://dali.hnxiangtu.top/Article/details/gt2rwcjjgka.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.feifeiyinyue.top/Article/details/gt2nalmtlvl.html

Go:   resp, err := http.Get(url)
来源：http://dali.jlsjyb.cn/Article/details/gt2apqxxfej.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cucudq.cn/Article/details/gt2smiminhn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nwbrower.top/Article/details/gt2lxvzfkhs.html

[L02] 发送 POST JSON
来源：http://dali.ppjwa.cn/Article/details/gt2iogixgrj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.guannengcc.top/Article/details/gt2hlbajgmk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.aibaodan.cn/Article/details/gt2ntyiohfx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuxming.cn/Article/details/gt2supiqabi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.birdmap.top/Article/details/gt2khwzqepn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hongshengwenyu.top/Article/details/gt2vghdeety.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ivvv.top/Article/details/gt2gdgjnbtz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nanxuanxn.top/Article/details/gt2ugmpbjdc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.c1oappe.top/Article/details/gt2erqxlyqi.html

[L03] 设置自定义请求头
来源：http://dali.jlsjyb.cn/Article/details/gt2cslhsrvz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.vqdsnc.cn/Article/details/gt2ziaagfkh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zlewandh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.meibo888.top/Article/details/gt2tqnycqcx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhiwuduotai.top/Article/details/gt2myexltmy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shangyingyoupin.top/Article/details/gt2xirjbrpf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sxryk.cn/Article/details/gt2mewbpxbq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.guannengcc.top/Article/details/gt2rngmtiny.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.9152youxi.cn/Article/details/gt2nbjjcoef.html

[L04] 设置超时
来源：http://dali.redwolf501.top/Article/details/gt2sthqtadg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2phbvjzcc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.fengsongda.top/Article/details/gt2lerriwnz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shzxlz.cn/Article/details/gt2lbrqupes.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tianlin.xyz/Article/details/gt2onndnhho.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hywenlv.cn/Article/details/gt2ndzylgwb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gzhubu.top/Article/details/gt2eaxiwwep.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhixingplan.top/Article/details/gt2dclgvsik.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tspwvnow.html

[L05] 上传文件（multipart）
来源：http://dali.feifeiyinyue.top/Article/details/gt2kseyrkvf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinghuilouyu.cn/Article/details/gt2celqydzc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.pycfn.com/Article/details/gt2yelrsyof.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.snrcjt.cn/Article/details/gt2rghvqqeo.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenjidiqi.icu/Article/details/gt2xymvfstc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jlsjyb.cn/Article/details/gt2vvjfhqme.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.aibaodan.cn/Article/details/gt2nkzamlpf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jiagoushi.top/Article/details/gt2cwueniew.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2vfuqxdlk.html

[L06] 解析响应为 JSON
来源：http://dali.fengsongda.top/Article/details/gt2ktfjtjbi.html

Py:   resp.json()
来源：http://dali.yj20258888.top/Article/details/gt2armjntug.html

PHP:  json_decode($body, true);
来源：http://dali.pengpengdd.cyou/Article/details/gt2uwzkytbu.html

JS:   await resp.json()
来源：http://dali.yueranfly.top/Article/details/gt2mmjbxqgz.html

TS:   await resp.json()
来源：http://dali.redwolf501.top/Article/details/gt2mjczsqet.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.tanke756.top/Article/details/gt2pkvfgyaj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hfpthk.cn/Article/details/gt2olfvacfm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.aibaodan.cn/Article/details/gt2qddjjego.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sysykeji.top/Article/details/gt2ycvzxtcu.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fsocvrtu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tianlin.xyz/Article/details/gt2ilglcjtq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.smart0.xyz/Article/details/gt2tsyufslu.html

JS:   resp.ok;  resp.status
来源：http://dali.havefunace.top/Article/details/gt2pdbxkyrl.html

TS:   resp.ok;  resp.status
来源：http://dali.fzhhl.top/Article/details/gt2bzkqudbc.html

Java: resp.statusCode()
来源：http://dali.aizwys.cn/Article/details/gt2nnkoujaa.html

Go:   resp.StatusCode
来源：http://dali.ppjwa.cn/Article/details/gt2prxjbtnz.html

Ruby: resp.code.to_i
来源：http://dali.hnqzz.top/Article/details/gt2xiivfzyw.html

C#:   (int)resp.StatusCode
来源：http://dali.cucudq.cn/Article/details/gt2xcbbwshk.html

[L08] 并发请求多个地址
来源：http://dali.yongpay.top/Article/details/gt2fodkujfi.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinqigufen.top/Article/details/gt2stdrfbtf.html

PHP:  curl_multi_init() 系列
来源：http://dali.0kj1m.cn/Article/details/gt2huucmydw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shuidangran.top/Article/details/gt2qxmspyfv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xylfe.cn/Article/details/gt2amcakpnx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hammf.cn/Article/details/gt2fyuoegtl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gotoacloud.top/Article/details/gt2nqkprebf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gogol.net.cn/Article/details/gt2bpmccaxj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhongyouzk.top/Article/details/gt2tkecmzqc.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2osxzhpcs.html

M. 命令行 / 进程 / 环境
来源：http://dali.cqqwz.cn/Article/details/gt2irwlkyhq.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2bngdmepd.html

[M01] 读取命令行参数
来源：http://dali.yuxming.cn/Article/details/gt2owzugoqp.html

Py:   sys.argv[1:]
来源：http://dali.0kj1m.cn/Article/details/gt2bzvwvqhq.html

PHP:  $argv;  $argc;
来源：http://dali.316326.xyz/Article/details/gt2blsgpcaa.html

JS:   process.argv.slice(2)
来源：http://dali.tianlin.xyz/Article/details/gt2ptdiilzm.html

TS:   process.argv.slice(2)
来源：http://dali.zhengqikj.top/Article/details/gt2zoqyqjao.html

Java: args 数组（main 方法参数）
来源：http://dali.jinqigfzy.top/Article/details/gt2pgizjhsv.html

Go:   os.Args[1:]
来源：http://dali.chenlongwang.top/Article/details/gt2zwseurze.html

Ruby: ARGV
来源：http://dali.hysaishi.cn/Article/details/gt2kxtswxtp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.kuanghao11.cn/Article/details/gt2ehmgsngx.html

[M02] 读取环境变量
来源：http://dali.yanxiufei.cn/Article/details/gt2eopmnudn.html

Py:   os.environ.get("HOME")
来源：http://dali.tian-w.cn/Article/details/gt2swvwnynt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nanxuanxn.top/Article/details/gt2iljahrde.html

JS:   process.env.HOME
来源：http://dali.cucudq.cn/Article/details/gt2zwcrcfcn.html

TS:   process.env.HOME
来源：http://dali.nanxinkj.top/Article/details/gt2lbnegsva.html

Java: System.getenv("HOME")
来源：http://dali.ivvv.top/Article/details/gt2prcnzucs.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.guannengcc.top/Article/details/gt2rbdmgcpt.html

Ruby: ENV["HOME"]
来源：http://dali.shuidangran.top/Article/details/gt2urdblkmx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.dianchejie.cn/Article/details/gt2rzjnolbs.html

[M03] 执行外部命令
来源：http://dali.jlsjyb.cn/Article/details/gt2gnowglig.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hongshengwenyu.top/Article/details/gt2npcdjwfi.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jqgfzy.top/Article/details/gt2pwawjxab.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cqqwz.cn/Article/details/gt2etktgybf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zycfv.cn/Article/details/gt2hbrzoumh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.chenlongwang.top/Article/details/gt2urvzqgjx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinqigufen.top/Article/details/gt2koltteab.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jqgufenzy.top/Article/details/gt2vyqeusbg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shuidangran.top/Article/details/gt2giogmiox.html

[M04] 获取当前工作目录
来源：http://dali.nanxuanxn.top/Article/details/gt2azupglnb.html

Py:   os.getcwd()
来源：http://dali.ybcxt.top/Article/details/gt2vuiokxmh.html

PHP:  getcwd();
来源：http://dali.yuxming.cn/Article/details/gt2fpuxvmmo.html

JS:   process.cwd()
来源：http://dali.xylfe.cn/Article/details/gt2hfmwqqry.html

TS:   process.cwd()
来源：http://dali.sufxvd.cn/Article/details/gt2uyrrpwls.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.0kj1m.cn/Article/details/gt2lmjdypok.html

Go:   os.Getwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mwrsxxei.html

Ruby: Dir.pwd
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lkgnrymy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dwrhnfub.html

[M05] 设置退出码
来源：http://dali.meibo888.top/Article/details/gt2ifvigsdx.html

Py:   sys.exit(1)
来源：http://dali.xinyue.icu/Article/details/gt2btnxfqym.html

PHP:  exit(1);
来源：http://dali.yuanzhike.top/Article/details/gt2kadocnio.html

JS:   process.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gt2ckunpric.html

TS:   process.exit(1)
来源：http://dali.sysykeji.top/Article/details/gt2qhxwhyaq.html

Java: System.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gt2etiruqbh.html

Go:   os.Exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qycqjeuq.html

Ruby: exit 1
来源：http://dali.316326.xyz/Article/details/gt2sumevzal.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.9152youxi.cn/Article/details/gt2bneifrpw.html

[M06] 向标准错误输出
来源：http://dali.snrcjt.cn/Article/details/gt2erbocfyx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.c1oappe.top/Article/details/gt2voikfufz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iyoqflvu.html

JS:   console.error("err")
来源：http://dali.xuetiantiany.cn/Article/details/gt2wonpzomo.html

TS:   console.error("err")
来源：http://dali.shuidangran.top/Article/details/gt2ylrflkix.html

Java: System.err.println("err")
来源：http://dali.xinyue.icu/Article/details/gt2qkygxddt.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.mhx1999.top/Article/details/gt2yliqofnp.html

Ruby: warn "err"
来源：http://dali.snrcjt.cn/Article/details/gt2cpewmiui.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nwbrower.top/Article/details/gt2flkkhian.html

[M07] 判断是否为主入口
来源：http://dali.fengsongda.top/Article/details/gt2ydsinyof.html

Py:   if __name__ == "__main__":
来源：http://dali.xylfe.cn/Article/details/gt2ilcczpcw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.kuanghao11.cn/Article/details/gt2jgpxvxbn.html

JS:   require.main === module
来源：http://dali.yangfankeji.com/Article/details/gt2lejorqlm.html

TS:   require.main === module
来源：http://dali.birdmap.top/Article/details/gt2akiyybml.html

Java: public static void main(String[] args)
来源：http://dali.ivvv.top/Article/details/gt2qsdhujqs.html

Go:   func main()
来源：http://dali.tianlin.xyz/Article/details/gt2ckivhawn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hammf.cn/Article/details/gt2ydskcgzk.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2twnsawel.html

[M08] 获取系统与运行时信息
来源：http://dali.zycfv.cn/Article/details/gt2xoajfjgm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hnxiangtu.top/Article/details/gt2irlfcdjv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yuanzhike.top/Article/details/gt2vweunuxd.html

JS:   process.platform;  process.version
来源：http://dali.shuidangran.top/Article/details/gt2btqetoyl.html

TS:   process.platform;  process.version
来源：http://dali.zycfv.cn/Article/details/gt2jchwrwik.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cashguo.top/Article/details/gt2uowodmdz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.birdmap.top/Article/details/gt2icuuesat.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jlsjyb.cn/Article/details/gt2vsotaxtc.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinqigufen.top/Article/details/gt2fgeqjkbt.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2bqktwfvf.html

N. 数据结构与算法
来源：http://dali.tian-w.cn/Article/details/gt2dqwtalbx.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2kcbwwvlz.html

[N01] 二分查找（有序数组）
来源：http://dali.jiagoushi.top/Article/details/gt2dgqjoarw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sxryk.cn/Article/details/gt2ezyvzime.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ybcxt.top/Article/details/gt2izokelbc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sxryk.cn/Article/details/gt2nddqeafz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhixingplan.top/Article/details/gt2kpjjfizf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ujsvzqlf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gt2vspydhaz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.wangshuangyany.cn/Article/details/gt2mimprvfe.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.wangdashe.top/Article/details/gt2cajrcwby.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sweek.top/Article/details/gt2eidtkdsp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenjidiqi.icu/Article/details/gt2djsyazkw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.daxiang520.top/Article/details/gt2zhgagrus.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhixingplan.top/Article/details/gt2iajafyfc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ivvv.top/Article/details/gt2ywpqjzrm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.tanke756.top/Article/details/gt2chqctvkt.html

Go:   slices.Sort(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2qtbukiag.html

Ruby: arr.sort
来源：http://dali.zdqjudy.top/Article/details/gt2uvlwiutn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xkuzciga.html

[N03] 快速排序（分治示例）
来源：http://dali.sxryk.cn/Article/details/gt2mxslqyfg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.wangdashe.top/Article/details/gt2nrvrxtts.html

PHP:  // 递归实现，或用 usort
来源：http://dali.chenzaomai.com/Article/details/gt2icjfuwmr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhengqikj.top/Article/details/gt2wkfyvawe.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lbvcejwd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yuanzhike.top/Article/details/gt2dkjberff.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.smart0.xyz/Article/details/gt2nqawdnyx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.wangdashe.top/Article/details/gt2jcszcwrd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.daxiang520.top/Article/details/gt2igcxmwyr.html

[N04] 斐波那契数列
来源：http://dali.zhiwuduotai.top/Article/details/gt2jwugwbmb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sweek.top/Article/details/gt2gxxazghi.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.birdmap.top/Article/details/gt2anbibkbp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cashguo.top/Article/details/gt2xxhyavyl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gt2riubmqup.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.0kj1m.cn/Article/details/gt2hfbqqvqr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.daxiang520.top/Article/details/gt2mofmbccu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258.top/Article/details/gt2btgdbklb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ivvv.top/Article/details/gt2ausvavei.html

[N05] 最大公约数
来源：http://dali.zhengqikj.top/Article/details/gt2ttpgkahj.html

Py:   math.gcd(a, b)
来源：http://dali.9152youxi.cn/Article/details/gt2risxmism.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.tanke756.top/Article/details/gt2ipveffpq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aizwys.cn/Article/details/gt2perkcgay.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yonumen.top/Article/details/gt2kfsmsjia.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zycfv.cn/Article/details/gt2nmufwehj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2osozzycg.html

Ruby: a.gcd(b)
来源：http://dali.kuanghao11.cn/Article/details/gt2trmffuns.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yj20258888.top/Article/details/gt2xpudqdlz.html

[N06] 判断回文字符串
来源：http://dali.yj202588.top/Article/details/gt2awbdqszg.html

Py:   s == s[::-1]
来源：http://dali.cdnleiting.top/Article/details/gt2aopffxga.html

PHP:  $s === strrev($s);
来源：http://dali.9152youxi.cn/Article/details/gt2tydihovb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gt2ulwrnoel.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gt2ofdijfrc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ppjwa.cn/Article/details/gt2qgomtxdu.html

Go:   // 双指针从两端比较
来源：http://dali.gotoacloud.top/Article/details/gt2hzhxanis.html

Ruby: s == s.reverse
来源：http://dali.yj20258888.top/Article/details/gt2viuhonhp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.feifeiyinyue.top/Article/details/gt2ujhicaav.html

[N07] 两数之和（返回下标）
来源：http://dali.jianghu66.top/Article/details/gt2uhfcnjyz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ldpsacjx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.nanxuanxn.top/Article/details/gt2jppffyfr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hongshengwenyu.top/Article/details/gt2iqtarfem.html

TS:   // 手写 Map<string, number>
来源：http://dali.zycfv.cn/Article/details/gt2hjsejshk.html

Java: // 手写 HashMap
来源：http://dali.dashuyun.cn/Article/details/gt2ydyqfyff.html

Go:   // 手写 map[int]int
来源：http://dali.dashuyun.cn/Article/details/gt2xjaiifly.html

Ruby: // 手写 Hash
来源：http://dali.yvedp.cn/Article/details/gt2hvkrlgka.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.dashuyun.cn/Article/details/gt2nklylddw.html

[N08] 生成全排列
来源：http://dali.vqdsnc.cn/Article/details/gt2qnmoscvy.html

Py:   itertools.permutations(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ukdzbubf.html

PHP:  // 手写递归交换
来源：http://dali.yueranfly.top/Article/details/gt2wlaiwger.html

JS:   // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gt2iblhxwoj.html

TS:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gt2nbybzsvk.html

Java: // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gt2vvjxerfc.html

Go:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gt2ixyyrfac.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2guldmkph.html

C#:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gt2lhyluzet.html

[N09] 栈与队列
来源：http://dali.jianghu66.top/Article/details/gt2ilsbnvdz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhrrbvj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.9152youxi.cn/Article/details/gt2gioivbtb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yangfankeji.com/Article/details/gt2olbctghl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.daxiang520.top/Article/details/gt2cjttznjm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lavasazc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cashguo.top/Article/details/gt2zdppbepe.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yuanzhike.top/Article/details/gt2yifmptlm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.mhx1999.top/Article/details/gt2ndzgnwhl.html

[N10] 链表节点定义
来源：http://dali.tian-w.cn/Article/details/gt2crbityvv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ivvv.top/Article/details/gt2bwasgwfn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jqgfzy.top/Article/details/gt2wnjbkusj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bvkchzpj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.nwbrower.top/Article/details/gt2ibeoynil.html

Java: class Node { int v; Node next; }
来源：http://dali.cashguo.top/Article/details/gt2vplhjlui.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hammf.cn/Article/details/gt2djbagrxz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.wangdashe.top/Article/details/gt2zjzrozab.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.sufxvd.cn/Article/details/gt2gtfkycrk.html

[N11] 二叉树中序遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cwivxymu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinqigufen.top/Article/details/gt2etnuhvme.html

PHP:  // 手写递归函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rbqbgdmx.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sxryk.cn/Article/details/gt2emoitoma.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgfzy.top/Article/details/gt2trnqjowu.html

Java: // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gt2qdtxnvdr.html

Go:   // 手写递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ylpuysze.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yonumen.top/Article/details/gt2otufajoq.html

C#:   // 手写递归
来源：http://dali.ivvv.top/Article/details/gt2cxslymqv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zdqjudy.top/Article/details/gt2ezgenxvv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jqgufenzy.top/Article/details/gt2rlowqxjr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.aibaodan.cn/Article/details/gt2yqybfstm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.redwolf501.top/Article/details/gt2vzvrccml.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgfzy.top/Article/details/gt2neylvxme.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yangfankeji.com/Article/details/gt2oxsdhawl.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xinyue.icu/Article/details/gt2aovuffht.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gaohongyu789.top/Article/details/gt2qhjxbpyv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuxming.cn/Article/details/gt2qjwdenjf.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2svceyesm.html

O. 并发与异步
来源：http://dali.sxryk.cn/Article/details/gt2bgslrlta.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2akdtmbgp.html

[O01] 启动一个线程
来源：http://dali.tianlin.xyz/Article/details/gt2fxtzpsye.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sweek.top/Article/details/gt2amkepjvc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.fzhhl.top/Article/details/gt2vbcvqrcc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.andypj.xyz/Article/details/gt2cimshsef.html

TS:   // 同 JS
来源：http://dali.shuidangran.top/Article/details/gt2aunyfmxa.html


<!-- 参考信息 -->