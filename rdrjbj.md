代发 wailian999

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.guowangkeji.top/Article/details/gtjrjhdfzh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hysaishi.cn/Article/details/gtcompwnuv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.fengsongda.top/Article/details/gtybbzcgqx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yvedp.cn/Article/details/gtjpybdbck.html

[K06] 解析 URL 查询串
来源：http://dali.gaohongyu789.top/Article/details/gthvxlhnie.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hywenlv.cn/Article/details/gtuxnhzdsw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yangfankeji.com/Article/details/gtprxymgsg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigufen.top/Article/details/gtbjkxfaev.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sufxvd.cn/Article/details/gtmhcldbuu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.feifeiyinyue.top/Article/details/gtjlganyft.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hnqzz.top/Article/details/gtttukzzoy.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gtkzrpisnr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ehwqpu.com/Article/details/gtmnvmfrzz.html

[K07] 进制转换
来源：http://dali.zhengqikj.top/Article/details/gtpqoatmys.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gtwmvvsjhr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gogol.net.cn/Article/details/gtvjznyymx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkvzmuoss.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gtdrjbswgo.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtjngefevu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.iojbl.cn/Article/details/gtrzdfspwz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xylfe.cn/Article/details/gthrerjgxe.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yongpay.top/Article/details/gtecpxzpih.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.0kj1m.cn/Article/details/gthwlbvytn.html

Py:   pickle.dumps(obj)
来源：http://dali.tanke756.top/Article/details/gtkyyxwbpm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yongpay.top/Article/details/gtnwxbtvso.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.wangdashe.top/Article/details/gtysvssede.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.birdmap.top/Article/details/gtrvnchjoc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.wangdashe.top/Article/details/gttpfeaxkf.html

Go:   encoding/gob
来源：http://dali.nanxuanxn.top/Article/details/gtqafcjhqu.html

Ruby: Marshal.dump(obj)
来源：http://dali.chenzaomai.com/Article/details/gtosmsbgjt.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cheryme.top/Article/details/gtiqzuruav.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtclxjmcon.html

L. 网络请求
来源：http://dali.cucudq.cn/Article/details/gtgvujwfcw.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtwhwuoeoo.html

[L01] 发送 GET 请求
来源：http://dali.wangdashe.top/Article/details/gtjryftpfo.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gzhubu.top/Article/details/gtllrmuyxx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.dashuyun.cn/Article/details/gtyzemldem.html

JS:   await fetch(url)
来源：http://dali.jqgufenzy.top/Article/details/gtivhuvsbc.html

TS:   await fetch(url)
来源：http://dali.sysykeji.top/Article/details/gtiqzpuebm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shuidangran.top/Article/details/gtsdilpsjz.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhiwuduotai.top/Article/details/gtgfgzmatn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sweek.top/Article/details/gtmojipoah.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.smart0.xyz/Article/details/gtwkynhrtq.html

[L02] 发送 POST JSON
来源：http://dali.ehwqpu.com/Article/details/gtjjpmrxwa.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.guannengcc.top/Article/details/gtjwdkjows.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shanyushiyangkeji.top/Article/details/gthbhrzkuo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxivcwvql.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daria6918.cn/Article/details/gtaeeixiws.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.quarkkingdee.top/Article/details/gtswafmfnq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yuanzhike.top/Article/details/gtjrpfnmmq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shangyingyoupin.top/Article/details/gtryrzloth.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.nwbrower.top/Article/details/gtltygszdz.html

[L03] 设置自定义请求头
来源：http://dali.svipenyu.cn/Article/details/gtkaiahyah.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.0kj1m.cn/Article/details/gtvsbemssn.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gotoacloud.top/Article/details/gtucqyqxgy.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.0kj1m.cn/Article/details/gtmrlgexux.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenjidiqi.icu/Article/details/gtgmesvcak.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.guannengcc.top/Article/details/gtbakqdlae.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jlsjyb.cn/Article/details/gtnyleeygc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj20258.top/Article/details/gtvdiyfzbp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.0kj1m.cn/Article/details/gtcvooxldc.html

[L04] 设置超时
来源：http://dali.guowangkeji.top/Article/details/gtwrecvnkl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.0kj1m.cn/Article/details/gtwojjkaeh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zdqjudy.top/Article/details/gtxrtasofm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgfzy.top/Article/details/gtebotuufl.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.iojbl.cn/Article/details/gttdkhisiu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zdqjudy.top/Article/details/gtrtwrczml.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jqgfzy.top/Article/details/gtspiwmsma.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cheryme.top/Article/details/gtnlxamsyf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.aizwys.cn/Article/details/gtmizxxgby.html

[L05] 上传文件（multipart）
来源：http://dali.ehwqpu.com/Article/details/gtuqxsibxw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hongshengwenyu.top/Article/details/gtjxydvfhs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ybcxt.top/Article/details/gtuzgnbnli.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigfzy.top/Article/details/gturlmaznk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.bjfxy.top/Article/details/gtvexkvhok.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.aizwys.cn/Article/details/gtwazxofxw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.svipenyu.cn/Article/details/gtggxlxsba.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhiwuduotai.top/Article/details/gtbsiwaluk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ivvv.top/Article/details/gtkcgpztmp.html

[L06] 解析响应为 JSON
来源：http://dali.xuetiantiany.cn/Article/details/gthnwqqnod.html

Py:   resp.json()
来源：http://dali.nwbrower.top/Article/details/gtqyzzkrxc.html

PHP:  json_decode($body, true);
来源：http://dali.zhixingplan.top/Article/details/gtavpxwmfg.html

JS:   await resp.json()
来源：http://dali.sweek.top/Article/details/gtownliucw.html

TS:   await resp.json()
来源：http://dali.hnqzz.top/Article/details/gtzhsthynd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sysykeji.top/Article/details/gtisqqomqq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.vqdsnc.cn/Article/details/gtydpkhggz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sysykeji.top/Article/details/gtpaasilwm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhiwuduotai.top/Article/details/gttkceceyk.html

[L07] 处理 HTTP 状态码
来源：http://dali.meibo888.top/Article/details/gtvabflwxj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shanyushiyangkeji.top/Article/details/gthvnrlgqa.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hfpthk.cn/Article/details/gtdlqwojwg.html

JS:   resp.ok;  resp.status
来源：http://dali.yvedp.cn/Article/details/gtxsrqqdue.html

TS:   resp.ok;  resp.status
来源：http://dali.cucudq.cn/Article/details/gtpiedejkk.html

Java: resp.statusCode()
来源：http://dali.hnxiangtu.top/Article/details/gtpbyptovf.html

Go:   resp.StatusCode
来源：http://dali.xylfe.cn/Article/details/gtablyimix.html

Ruby: resp.code.to_i
来源：http://dali.smart0.xyz/Article/details/gtifsmrgql.html

C#:   (int)resp.StatusCode
来源：http://dali.nwbrower.top/Article/details/gtkfbsdtzk.html

[L08] 并发请求多个地址
来源：http://dali.9152youxi.cn/Article/details/gtuxclffkv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.guannengcc.top/Article/details/gtolpevuxq.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhongyouzk.top/Article/details/gtdjxuwzdc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhongyouzk.top/Article/details/gtupcpsfgb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.birdmap.top/Article/details/gtiftekwcl.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.aibaodan.cn/Article/details/gttzpujeke.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yanxiufei.cn/Article/details/gtyglkvkjy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.dianchejie.cn/Article/details/gtwncyjmtq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gtbydgndlq.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtptnrxhob.html

M. 命令行 / 进程 / 环境
来源：http://dali.haohaochexian.top/Article/details/gtxqztfzsm.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtlmdxejjj.html

[M01] 读取命令行参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtgruehuan.html

Py:   sys.argv[1:]
来源：http://dali.cqqwz.cn/Article/details/gtwlgpuhwr.html

PHP:  $argv;  $argc;
来源：http://dali.yongpay.top/Article/details/gtjfhgaogx.html

JS:   process.argv.slice(2)
来源：http://dali.ppjwa.cn/Article/details/gtqlnydcmd.html

TS:   process.argv.slice(2)
来源：http://dali.gotoacloud.top/Article/details/gtbojhivbr.html

Java: args 数组（main 方法参数）
来源：http://dali.9152youxi.cn/Article/details/gtjkiwigzu.html

Go:   os.Args[1:]
来源：http://dali.yangfankeji.com/Article/details/gtrobwbhww.html

Ruby: ARGV
来源：http://dali.daxiang520.top/Article/details/gtcicmvqhz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.meibo888.top/Article/details/gtgbynkuyv.html

[M02] 读取环境变量
来源：http://dali.ydzc1.top/Article/details/gtktkynxtn.html

Py:   os.environ.get("HOME")
来源：http://dali.zdqjudy.top/Article/details/gtlpsownjs.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ivvv.top/Article/details/gtivykormp.html

JS:   process.env.HOME
来源：http://dali.yuanzhike.top/Article/details/gtmutogsjz.html

TS:   process.env.HOME
来源：http://dali.hysaishi.cn/Article/details/gtmkwwnmho.html

Java: System.getenv("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtuqttghtw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gotoacloud.top/Article/details/gtkjujmqqc.html

Ruby: ENV["HOME"]
来源：http://dali.316326.xyz/Article/details/gtfbqzdnag.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.aibaodan.cn/Article/details/gtelgzvavv.html

[M03] 执行外部命令
来源：http://dali.ybcxt.top/Article/details/gtjpvrfnyt.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenlongwang.top/Article/details/gtvkceikqu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xuanzx.com/Article/details/gtxggyykla.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jiagoushi.top/Article/details/gtwzxdkebu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtabngnakk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cucudq.cn/Article/details/gtopgjzexl.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.guowangkeji.top/Article/details/gtdtkoxepa.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shuidangran.top/Article/details/gtbhuigvrh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyokskhxe.html

[M04] 获取当前工作目录
来源：http://dali.tian-w.cn/Article/details/gtlvmtfxnw.html

Py:   os.getcwd()
来源：http://dali.xylfe.cn/Article/details/gtlzncensn.html

PHP:  getcwd();
来源：http://dali.yvedp.cn/Article/details/gttzgwtyct.html

JS:   process.cwd()
来源：http://dali.yvedp.cn/Article/details/gtxyyiqkee.html

TS:   process.cwd()
来源：http://dali.sysykeji.top/Article/details/gtmfgxnxfc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hongshengwenyu.top/Article/details/gtaihnzblk.html

Go:   os.Getwd()
来源：http://dali.gaohongyu789.top/Article/details/gtlbbjtjay.html

Ruby: Dir.pwd
来源：http://dali.yuanzhike.top/Article/details/gtgcyuhaop.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.wangshuangyany.cn/Article/details/gtbfndjuzp.html

[M05] 设置退出码
来源：http://dali.aizwys.cn/Article/details/gtmhywletg.html

Py:   sys.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gtdxvzwlbq.html

PHP:  exit(1);
来源：http://dali.ppjwa.cn/Article/details/gtfgemfqnm.html

JS:   process.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtwnycnall.html

TS:   process.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gtogqhszcb.html

Java: System.exit(1)
来源：http://dali.gzhubu.top/Article/details/gtqlehheay.html

Go:   os.Exit(1)
来源：http://dali.cheryme.top/Article/details/gtuuwzapwm.html

Ruby: exit 1
来源：http://dali.sysykeji.top/Article/details/gtlsocygnu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.fzhhl.top/Article/details/gtfqbothui.html

[M06] 向标准错误输出
来源：http://dali.fzhhl.top/Article/details/gtvonohtpg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj20258.top/Article/details/gtyntuxtiz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.chenjidiqi.icu/Article/details/gteywzjgyw.html

JS:   console.error("err")
来源：http://dali.ppjwa.cn/Article/details/gttmrecxjo.html

TS:   console.error("err")
来源：http://dali.yongpay.top/Article/details/gtgjqvjlkf.html

Java: System.err.println("err")
来源：http://dali.jlsjyb.cn/Article/details/gtkcpjhqum.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.meibo888.top/Article/details/gttsrmbkes.html

Ruby: warn "err"
来源：http://dali.aizwys.cn/Article/details/gtiqpopjew.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shzxlz.cn/Article/details/gtbusdvgyl.html

[M07] 判断是否为主入口
来源：http://dali.hnxiangtu.top/Article/details/gtrhbohgsx.html

Py:   if __name__ == "__main__":
来源：http://dali.c1oappe.top/Article/details/gtcokfviyk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yonumen.top/Article/details/gtgzphndun.html

JS:   require.main === module
来源：http://dali.sweek.top/Article/details/gtccmskaqs.html

TS:   require.main === module
来源：http://dali.daria6918.cn/Article/details/gtamslxpsx.html

Java: public static void main(String[] args)
来源：http://dali.yongpay.top/Article/details/gtimnzxthg.html

Go:   func main()
来源：http://dali.jinghuilouyu.cn/Article/details/gtqgplxhyy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jlsjyb.cn/Article/details/gthfhjyyjf.html

C#:   static void Main(string[] args)
来源：http://dali.redwolf501.top/Article/details/gttxyytvlz.html

[M08] 获取系统与运行时信息
来源：http://dali.bjfxy.top/Article/details/gtqlcyxbfa.html

Py:   platform.system();  platform.python_version()
来源：http://dali.vqdsnc.cn/Article/details/gtzdiyzuws.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.guannengcc.top/Article/details/gtwzoldaax.html

JS:   process.platform;  process.version
来源：http://dali.sysykeji.top/Article/details/gtjtcrcjcv.html

TS:   process.platform;  process.version
来源：http://dali.chenlongwang.top/Article/details/gtirolzftm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gotoacloud.top/Article/details/gtuuoarizw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hongshengwenyu.top/Article/details/gtydrtysqx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cashguo.top/Article/details/gtxjtxvnoy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.fzhhl.top/Article/details/gtxekdzxec.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtuzghombm.html

N. 数据结构与算法
来源：http://dali.hnxiangtu.top/Article/details/gtmqacjwij.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvwgadwwj.html

[N01] 二分查找（有序数组）
来源：http://dali.cqqwz.cn/Article/details/gtkrhbyzxo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnpjxjtna.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmxfdpqak.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hysaishi.cn/Article/details/gtyzfqvsoa.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gtjejqubiw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gttcidigra.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.redwolf501.top/Article/details/gtrdrstcmg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.quarkkingdee.top/Article/details/gtasusmfmc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtkexytzof.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hfpthk.cn/Article/details/gtfadgmvrk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ivvv.top/Article/details/gtantjaoqp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.meibo888.top/Article/details/gtlwomrord.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jlsjyb.cn/Article/details/gtayzurzsz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shzxlz.cn/Article/details/gtlgeqfmrp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hammf.cn/Article/details/gtehhtrpts.html

Go:   slices.Sort(arr)
来源：http://dali.sweek.top/Article/details/gtuuefpykx.html

Ruby: arr.sort
来源：http://dali.dashuyun.cn/Article/details/gtkkvbwsro.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yueranfly.top/Article/details/gtyohoaeyw.html

[N03] 快速排序（分治示例）
来源：http://dali.jiagoushi.top/Article/details/gtqlncneqy.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqifygtny.html

PHP:  // 递归实现，或用 usort
来源：http://dali.havefunace.top/Article/details/gtlcvnqzvo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aibaodan.cn/Article/details/gtxezdyoxq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jiagoushi.top/Article/details/gtjztauccn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jianghu66.top/Article/details/gtvcnzuuyw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.guannengcc.top/Article/details/gtvrhydqle.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxzwvbwzr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.bjfxy.top/Article/details/gtzdqkyccd.html

[N04] 斐波那契数列
来源：http://dali.fzhhl.top/Article/details/gtteaiqgiz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xinyue.icu/Article/details/gtdibupcnm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.guowangkeji.top/Article/details/gtbepobghf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gtxswdyler.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gtnuncqoyw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.sweek.top/Article/details/gthfezgsjr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenlongwang.top/Article/details/gtyzeozsxz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.0kj1m.cn/Article/details/gtmpzjhqnd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hfpthk.cn/Article/details/gtzprfljep.html

[N05] 最大公约数
来源：http://dali.tian-w.cn/Article/details/gtlfziksfl.html

Py:   math.gcd(a, b)
来源：http://dali.xziqi.cn/Article/details/gtuwdvfzlf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.guowangkeji.top/Article/details/gtwfyhxogn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj202588.top/Article/details/gtzmkgygnf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hywenlv.cn/Article/details/gtucqnvsos.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.havefunace.top/Article/details/gthfhwappu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.guowangkeji.top/Article/details/gtklfhbiwo.html

Ruby: a.gcd(b)
来源：http://dali.yj20258.top/Article/details/gtkglcxwst.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sweek.top/Article/details/gtyduoiunb.html

[N06] 判断回文字符串
来源：http://dali.bjfxy.top/Article/details/gtiuvdndcv.html

Py:   s == s[::-1]
来源：http://dali.yj20258888.top/Article/details/gtkrbaisjm.html

PHP:  $s === strrev($s);
来源：http://dali.shuidangran.top/Article/details/gtrirdngiw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gtszymwgcb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gtoionvadp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yanxiufei.cn/Article/details/gtgvoiywno.html

Go:   // 双指针从两端比较
来源：http://dali.cucudq.cn/Article/details/gtjsdxhtyi.html

Ruby: s == s.reverse
来源：http://dali.yj202588.top/Article/details/gtrybvryvv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.316326.xyz/Article/details/gtzkmmvhth.html

[N07] 两数之和（返回下标）
来源：http://dali.zdqjudy.top/Article/details/gtlehdgpse.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdgxcewym.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.tian-w.cn/Article/details/gtgptevcfk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.chenlongwang.top/Article/details/gtojawjxcj.html

TS:   // 手写 Map<string, number>
来源：http://dali.daxiang520.top/Article/details/gtuafjggby.html

Java: // 手写 HashMap
来源：http://dali.zhongyouzk.top/Article/details/gtszhabnta.html

Go:   // 手写 map[int]int
来源：http://dali.nanxuanxn.top/Article/details/gtpfbrqier.html

Ruby: // 手写 Hash
来源：http://dali.kuanghao11.cn/Article/details/gttvjhfhdo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.bjfxy.top/Article/details/gtverunuxk.html

[N08] 生成全排列
来源：http://dali.zhiwuduotai.top/Article/details/gtjsmqaoyn.html

Py:   itertools.permutations(arr)
来源：http://dali.hammf.cn/Article/details/gtprmxtrrl.html

PHP:  // 手写递归交换
来源：http://dali.0kj1m.cn/Article/details/gtumicegyz.html

JS:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwrwpqyow.html

TS:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gtihgplmyo.html

Java: // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gtobmbrqde.html

Go:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gtlwrvzyag.html

Ruby: arr.permutation.to_a
来源：http://dali.jianghu66.top/Article/details/gtvoudaksp.html

C#:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gtirigdgaq.html

[N09] 栈与队列
来源：http://dali.daria6918.cn/Article/details/gtbnzwomlm.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.guowangkeji.top/Article/details/gtcyohdsxv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sysykeji.top/Article/details/gtbvncevwu.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yuxming.cn/Article/details/gtnducxtku.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhiwuduotai.top/Article/details/gtmkegxasr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoddihuiv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yueranfly.top/Article/details/gtwesmhdcb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jyoumei.cn/Article/details/gtodhpbtwf.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yonumen.top/Article/details/gtqkfudsee.html

[N10] 链表节点定义
来源：http://dali.zhaomingkeji.xyz/Article/details/gtatmxjahu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shuidangran.top/Article/details/gtzkhqrrtq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hysaishi.cn/Article/details/gtwymmwvlx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yj202588.top/Article/details/gtjfkxsyql.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.birdmap.top/Article/details/gtknecdpcf.html

Java: class Node { int v; Node next; }
来源：http://dali.hywenlv.cn/Article/details/gtljddltyh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ybcxt.top/Article/details/gtybsgkyhp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmnclervl.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yuanzhike.top/Article/details/gtjjlmntlj.html

[N11] 二叉树中序遍历
来源：http://dali.sxryk.cn/Article/details/gtqdcriarf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shangyingyoupin.top/Article/details/gtmhlolieq.html

PHP:  // 手写递归函数
来源：http://dali.zdqjudy.top/Article/details/gtrkxrcvut.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hfpthk.cn/Article/details/gtnntmkknx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xziqi.cn/Article/details/gtutqntqma.html

Java: // 手写递归
来源：http://dali.feifeiyinyue.top/Article/details/gtuifmligj.html

Go:   // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gtwvzrhgrn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuaxbwayy.html

C#:   // 手写递归
来源：http://dali.nanxuanxn.top/Article/details/gtnoqbmxby.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.c1oappe.top/Article/details/gtkafllhwl.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtifgrahay.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhongyouzk.top/Article/details/gtjkpdwchw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sweek.top/Article/details/gtqavzaigy.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guowangkeji.top/Article/details/gtxhqscnam.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.redwolf501.top/Article/details/gtiwdqfuhp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.aizwys.cn/Article/details/gtbsctjtmr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cashguo.top/Article/details/gtelvouhpf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tianlin.xyz/Article/details/gtpuzmgpsq.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtcsbfpyxn.html

O. 并发与异步
来源：http://dali.ppjwa.cn/Article/details/gtpkoziggw.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtglwwmqlb.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gtxwpciige.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhongyouzk.top/Article/details/gtlrpmdarp.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.aibaodan.cn/Article/details/gtcryfeiwn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hnqzz.top/Article/details/gtdofuooxx.html

TS:   // 同 JS
来源：http://dali.ivvv.top/Article/details/gtiruwupmy.html


<!-- 参考信息 -->