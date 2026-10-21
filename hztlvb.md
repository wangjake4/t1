代发 wailian999

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrznkocxr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hammf.cn/Article/details/gtpddaatsm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ybcxt.top/Article/details/gtylwpgawc.html

[K05] 深拷贝对象
来源：http://dali.9152youxi.cn/Article/details/gtsrwpoykm.html

Py:   copy.deepcopy(obj)
来源：http://dali.xziqi.cn/Article/details/gtyhnsziov.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gzhubu.top/Article/details/gtxvqybagx.html

JS:   structuredClone(obj)
来源：http://dali.cheryme.top/Article/details/gtbsdkrkeo.html

TS:   structuredClone(obj)
来源：http://dali.jinqigufen.top/Article/details/gtimclrvlm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.tian-w.cn/Article/details/gttozsycin.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yangfankeji.com/Article/details/gttdkxpykc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nwbrower.top/Article/details/gtilaelsbs.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nanxuanxn.top/Article/details/gtyednanpr.html

[K06] 解析 URL 查询串
来源：http://dali.wangdashe.top/Article/details/gtxfseiaih.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.pengpengdd.cyou/Article/details/gtydqinxdw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj20258.top/Article/details/gtxlhqguko.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.andypj.xyz/Article/details/gtqejhrdai.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cucudq.cn/Article/details/gtmmosfinw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttspflcly.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gtydvskfig.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.meibo888.top/Article/details/gtfnergena.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gtwcoegenu.html

[K07] 进制转换
来源：http://dali.zhiwuduotai.top/Article/details/gtculjjkhw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gtjelknbsa.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cqqwz.cn/Article/details/gtwwylrezm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gtgxnavwcr.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gthvajfvpf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gtkedrnchj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.bjfxy.top/Article/details/gtmhwqqsek.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yongpay.top/Article/details/gtjxojjxtj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gthygjtahc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.pycfn.com/Article/details/gtabhqyzax.html

Py:   pickle.dumps(obj)
来源：http://dali.jiagoushi.top/Article/details/gttyeawibq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yj20258888.top/Article/details/gtiladjbna.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.c1oappe.top/Article/details/gtafxkohgf.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.daria6918.cn/Article/details/gtlradijlo.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xylfe.cn/Article/details/gthijixezi.html

Go:   encoding/gob
来源：http://dali.0kj1m.cn/Article/details/gthuclfppi.html

Ruby: Marshal.dump(obj)
来源：http://dali.yueranfly.top/Article/details/gtpavzrxzv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sufxvd.cn/Article/details/gtynuofiku.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtytvguuki.html

L. 网络请求
来源：http://dali.c1oappe.top/Article/details/gtmterlwui.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtrukaxxbh.html

[L01] 发送 GET 请求
来源：http://dali.fengsongda.top/Article/details/gtpfkxlaww.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhixingplan.top/Article/details/gtdyyezera.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xylfe.cn/Article/details/gtrgpaoaij.html

JS:   await fetch(url)
来源：http://dali.gogol.net.cn/Article/details/gtkjnzcuvt.html

TS:   await fetch(url)
来源：http://dali.tanke756.top/Article/details/gtkgicvqxw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.dashuyun.cn/Article/details/gtnyukyiaz.html

Go:   resp, err := http.Get(url)
来源：http://dali.jqgfzy.top/Article/details/gtbztnmyyp.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jqgufenzy.top/Article/details/gtmyvnffty.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.c1oappe.top/Article/details/gtmbfvuvcl.html

[L02] 发送 POST JSON
来源：http://dali.xylfe.cn/Article/details/gtzrwbkckq.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jyoumei.cn/Article/details/gtruwuiklv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.nwbrower.top/Article/details/gtmlixhpom.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.andypj.xyz/Article/details/gtwlyvhwos.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.haohaochexian.top/Article/details/gtlamsesws.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.svipenyu.cn/Article/details/gtdcvqokyv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.birdmap.top/Article/details/gtxjelfpoe.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.redwolf501.top/Article/details/gtkcntyxvj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cdnleiting.top/Article/details/gtqsfqwfmk.html

[L03] 设置自定义请求头
来源：http://dali.fengsongda.top/Article/details/gtfqhracbm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jqgfzy.top/Article/details/gtikqaewcv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.quarkkingdee.top/Article/details/gtcbnrusjj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xinyue.icu/Article/details/gtltdobqqv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gotoacloud.top/Article/details/gtusjzkpsq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.daxiang520.top/Article/details/gtusshjudo.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hongshengwenyu.top/Article/details/gtmhdjdgff.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xinyue.icu/Article/details/gtfforfecs.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpxxezaqa.html

[L04] 设置超时
来源：http://dali.guowangkeji.top/Article/details/gttcrvmoam.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yvedp.cn/Article/details/gtsjnkjeum.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.mhx1999.top/Article/details/gtrnaaywiq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.c1oappe.top/Article/details/gtkzfvwztg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnqzz.top/Article/details/gtiyhdobzp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yongpay.top/Article/details/gthomsquld.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.chenzaomai.com/Article/details/gtgghqabjs.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nanxuanxn.top/Article/details/gthqbjmojp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.aibaodan.cn/Article/details/gtresauwcp.html

[L05] 上传文件（multipart）
来源：http://dali.yj20258.top/Article/details/gtrkdyocgx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xziqi.cn/Article/details/gtdiggkoae.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.iojbl.cn/Article/details/gthpibztcm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sufxvd.cn/Article/details/gtnvtdwwtn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.guowangkeji.top/Article/details/gtwldepnpk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.tian-w.cn/Article/details/gtlushrcvp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhixingplan.top/Article/details/gtsokyiemt.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.redwolf501.top/Article/details/gtsasqylcj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtljjhitpv.html

[L06] 解析响应为 JSON
来源：http://dali.c1oappe.top/Article/details/gtjvkpnyyz.html

Py:   resp.json()
来源：http://dali.yj202588.top/Article/details/gtamygodyd.html

PHP:  json_decode($body, true);
来源：http://dali.vqdsnc.cn/Article/details/gtyudvbhwr.html

JS:   await resp.json()
来源：http://dali.zhiwuduotai.top/Article/details/gtlavloqhi.html

TS:   await resp.json()
来源：http://dali.pengpengdd.cyou/Article/details/gtalvokjpm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hammf.cn/Article/details/gtivceelfv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.svipenyu.cn/Article/details/gtlkqlfluu.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cucudq.cn/Article/details/gtganlxuwo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hammf.cn/Article/details/gtsvlqxpwi.html

[L07] 处理 HTTP 状态码
来源：http://dali.jiagoushi.top/Article/details/gtwdirxkyo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xuetiantiany.cn/Article/details/gtzwnfxzhr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shzxlz.cn/Article/details/gthsmhukxc.html

JS:   resp.ok;  resp.status
来源：http://dali.redwolf501.top/Article/details/gtysxbjbbk.html

TS:   resp.ok;  resp.status
来源：http://dali.quarkkingdee.top/Article/details/gttyreivei.html

Java: resp.statusCode()
来源：http://dali.sufxvd.cn/Article/details/gtkdpmyvuk.html

Go:   resp.StatusCode
来源：http://dali.yonumen.top/Article/details/gtzsciizjf.html

Ruby: resp.code.to_i
来源：http://dali.jqgfzy.top/Article/details/gtewiaboxg.html

C#:   (int)resp.StatusCode
来源：http://dali.smart0.xyz/Article/details/gtkgbdekdj.html

[L08] 并发请求多个地址
来源：http://dali.sweek.top/Article/details/gtrpzknmhp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhoulong.xyz/Article/details/gtnqdvswin.html

PHP:  curl_multi_init() 系列
来源：http://dali.yueranfly.top/Article/details/gtlwyprwur.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gtcfojqpds.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.birdmap.top/Article/details/gthvnyvzxi.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.kuanghao11.cn/Article/details/gtkylrexdd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhongyouzk.top/Article/details/gtfiezacty.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.snrcjt.cn/Article/details/gtwlmzmysh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.mhx1999.top/Article/details/gtxvgjruea.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtnbqqkqhk.html

M. 命令行 / 进程 / 环境
来源：http://dali.mhx1999.top/Article/details/gtooeeqdvf.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtdwwwkuyc.html

[M01] 读取命令行参数
来源：http://dali.dashuyun.cn/Article/details/gtkutaztuc.html

Py:   sys.argv[1:]
来源：http://dali.chenlongwang.top/Article/details/gtvizmqalk.html

PHP:  $argv;  $argc;
来源：http://dali.jinghuilouyu.cn/Article/details/gtyrilrmol.html

JS:   process.argv.slice(2)
来源：http://dali.yongpay.top/Article/details/gtjbgqeoxk.html

TS:   process.argv.slice(2)
来源：http://dali.ydzc1.top/Article/details/gtrktsgaqv.html

Java: args 数组（main 方法参数）
来源：http://dali.chenlongwang.top/Article/details/gtbtumhasb.html

Go:   os.Args[1:]
来源：http://dali.tian-w.cn/Article/details/gtqkwyczwp.html

Ruby: ARGV
来源：http://dali.xuanzx.com/Article/details/gtdmnffyby.html

C#:   args 数组（Main 方法参数）
来源：http://dali.andypj.xyz/Article/details/gttafvwyta.html

[M02] 读取环境变量
来源：http://dali.jinqigufen.top/Article/details/gtzqumcdlj.html

Py:   os.environ.get("HOME")
来源：http://dali.hfpthk.cn/Article/details/gtivcgactq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.svipenyu.cn/Article/details/gtslwdfrxq.html

JS:   process.env.HOME
来源：http://dali.yj20258888.top/Article/details/gtpxxxtzpe.html

TS:   process.env.HOME
来源：http://dali.guowangkeji.top/Article/details/gtvhnvfgpg.html

Java: System.getenv("HOME")
来源：http://dali.9152youxi.cn/Article/details/gtpbuhjtzn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.fzhhl.top/Article/details/gtyxmfiscz.html

Ruby: ENV["HOME"]
来源：http://dali.chenzaomai.com/Article/details/gtbmjagnwm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtalcedbyb.html

[M03] 执行外部命令
来源：http://dali.zhengqikj.top/Article/details/gtgkiclatd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.9152youxi.cn/Article/details/gtevuayfom.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jlsjyb.cn/Article/details/gtebhltpzx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenzaomai.com/Article/details/gtgsbxpqhe.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.meibo888.top/Article/details/gtyelcisvp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinqigufen.top/Article/details/gtzpcryork.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tianlin.xyz/Article/details/gtsyqffdlh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hysaishi.cn/Article/details/gtawqqgbkq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoxinsuxd.html

[M04] 获取当前工作目录
来源：http://dali.jinqigufen.top/Article/details/gtlomlplxm.html

Py:   os.getcwd()
来源：http://dali.ybcxt.top/Article/details/gtrneztpuu.html

PHP:  getcwd();
来源：http://dali.redwolf501.top/Article/details/gthfixcswu.html

JS:   process.cwd()
来源：http://dali.tanke756.top/Article/details/gtbufgdfgv.html

TS:   process.cwd()
来源：http://dali.c1oappe.top/Article/details/gtlkdsvkzi.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gotoacloud.top/Article/details/gtayvmgldi.html

Go:   os.Getwd()
来源：http://dali.yangfankeji.com/Article/details/gtrtdogsbp.html

Ruby: Dir.pwd
来源：http://dali.ybcxt.top/Article/details/gtqrsvwgyg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.pycfn.com/Article/details/gtfaupqiif.html

[M05] 设置退出码
来源：http://dali.xinyue.icu/Article/details/gtfshnjlsi.html

Py:   sys.exit(1)
来源：http://dali.guannengcc.top/Article/details/gtuklshdci.html

PHP:  exit(1);
来源：http://dali.pycfn.com/Article/details/gtulvybvjy.html

JS:   process.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtpqkatmxm.html

TS:   process.exit(1)
来源：http://dali.sysykeji.top/Article/details/gtiwgrpgyh.html

Java: System.exit(1)
来源：http://dali.bjfxy.top/Article/details/gtrmbftarq.html

Go:   os.Exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gtzsnqydud.html

Ruby: exit 1
来源：http://dali.daria6918.cn/Article/details/gtjznkaymo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.9152youxi.cn/Article/details/gtbkrlrpwj.html

[M06] 向标准错误输出
来源：http://dali.ybcxt.top/Article/details/gtbdivcxxx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.daxiang520.top/Article/details/gtmlkxtgza.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jqgfzy.top/Article/details/gteugktnvb.html

JS:   console.error("err")
来源：http://dali.cqqwz.cn/Article/details/gtlqqermyy.html

TS:   console.error("err")
来源：http://dali.cucudq.cn/Article/details/gtzlmokczd.html

Java: System.err.println("err")
来源：http://dali.xuetiantiany.cn/Article/details/gtrjlmojkq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jqgufenzy.top/Article/details/gtsdfvpzsb.html

Ruby: warn "err"
来源：http://dali.pycfn.com/Article/details/gtdtjaomda.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hammf.cn/Article/details/gtzaieuocj.html

[M07] 判断是否为主入口
来源：http://dali.cucudq.cn/Article/details/gtwfggvlca.html

Py:   if __name__ == "__main__":
来源：http://dali.nanxuanxn.top/Article/details/gtgxcxqxfd.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.quarkkingdee.top/Article/details/gtoycviray.html

JS:   require.main === module
来源：http://dali.xuetiantiany.cn/Article/details/gtpjhqessh.html

TS:   require.main === module
来源：http://dali.jyoumei.cn/Article/details/gtbljzczwu.html

Java: public static void main(String[] args)
来源：http://dali.nwbrower.top/Article/details/gtevhalxvp.html

Go:   func main()
来源：http://dali.ydzc1.top/Article/details/gtfmzeqhxy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.guowangkeji.top/Article/details/gtjalropox.html

C#:   static void Main(string[] args)
来源：http://dali.ehwqpu.com/Article/details/gtrgzpctoi.html

[M08] 获取系统与运行时信息
来源：http://dali.xuanzx.com/Article/details/gteyuytsdx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ehwqpu.com/Article/details/gtuzcdylbr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jyoumei.cn/Article/details/gtnpbncerx.html

JS:   process.platform;  process.version
来源：http://dali.dashuyun.cn/Article/details/gtxenljrnm.html

TS:   process.platform;  process.version
来源：http://dali.dashuyun.cn/Article/details/gtkswxsxth.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinqigufen.top/Article/details/gtonegbmmb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xinyue.icu/Article/details/gtkcwpnxfp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hfpthk.cn/Article/details/gtafwcoctd.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbktrdknx.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtvtahyhce.html

N. 数据结构与算法
来源：http://dali.havefunace.top/Article/details/gtxoabngvy.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtxdpdbcal.html

[N01] 二分查找（有序数组）
来源：http://dali.pycfn.com/Article/details/gtgeojjzmr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtxbirgsgy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinqigfzy.top/Article/details/gtuyqblxsc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxuanxn.top/Article/details/gtnyndnedc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258.top/Article/details/gtlhiigiyt.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtuettwuge.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtulexhkhz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.fengsongda.top/Article/details/gtskmktqpp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtwzeodqoi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jqgfzy.top/Article/details/gthxnddxkl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.mhx1999.top/Article/details/gttscmjjig.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gtohcbdfsh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hfpthk.cn/Article/details/gtvgwiyxpc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfieetimk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yuanzhike.top/Article/details/gtzlwpueiq.html

Go:   slices.Sort(arr)
来源：http://dali.ydzc1.top/Article/details/gtugxjmczw.html

Ruby: arr.sort
来源：http://dali.yongpay.top/Article/details/gtduktpsxr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nwbrower.top/Article/details/gtlywokyyk.html

[N03] 快速排序（分治示例）
来源：http://dali.jinghuilouyu.cn/Article/details/gtxjldwzyw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hywenlv.cn/Article/details/gtdhvbgufo.html

PHP:  // 递归实现，或用 usort
来源：http://dali.pycfn.com/Article/details/gtxprzmwjf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenjidiqi.icu/Article/details/gtwiqyrexc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.snrcjt.cn/Article/details/gtdfwigpps.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cqqwz.cn/Article/details/gtosbjagcc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenzaomai.com/Article/details/gttcyxowcp.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yonumen.top/Article/details/gtztfqhbdl.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.vqdsnc.cn/Article/details/gtkzcmteix.html

[N04] 斐波那契数列
来源：http://dali.birdmap.top/Article/details/gtegxbwzyx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cheryme.top/Article/details/gtikglfrgo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.guannengcc.top/Article/details/gtwmglakzo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cashguo.top/Article/details/gtgnlxzvde.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenlongwang.top/Article/details/gttggpgidd.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.vqdsnc.cn/Article/details/gtxcgnmfzb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zdqjudy.top/Article/details/gtiukqsvbx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ydzc1.top/Article/details/gtrrgbqvvk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gtfovmioqg.html

[N05] 最大公约数
来源：http://dali.shzxlz.cn/Article/details/gteaejzzol.html

Py:   math.gcd(a, b)
来源：http://dali.pycfn.com/Article/details/gtbrvnycyu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.iojbl.cn/Article/details/gtllpuonnf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xziqi.cn/Article/details/gtjloxdifa.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gtjavrzngi.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ybcxt.top/Article/details/gtoimnxrmx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shzxlz.cn/Article/details/gtihxhcybt.html

Ruby: a.gcd(b)
来源：http://dali.xuetiantiany.cn/Article/details/gtetktbjko.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ivvv.top/Article/details/gtrxdjetel.html

[N06] 判断回文字符串
来源：http://dali.jiagoushi.top/Article/details/gtglsltkxj.html

Py:   s == s[::-1]
来源：http://dali.yuanzhike.top/Article/details/gtmlhksfpl.html

PHP:  $s === strrev($s);
来源：http://dali.yongpay.top/Article/details/gtsgjwjbuv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.fzhhl.top/Article/details/gtezfovsgo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gthvibzbuv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhiwuduotai.top/Article/details/gturilyigz.html

Go:   // 双指针从两端比较
来源：http://dali.jqgfzy.top/Article/details/gtabeifuwk.html

Ruby: s == s.reverse
来源：http://dali.pengpengdd.cyou/Article/details/gtnvjpfowp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yj20258.top/Article/details/gtehwrjuxg.html

[N07] 两数之和（返回下标）
来源：http://dali.jqgfzy.top/Article/details/gtjqzmqyan.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.nwbrower.top/Article/details/gtzqsbevei.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.snrcjt.cn/Article/details/gtbfgsgdnq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinghuilouyu.cn/Article/details/gtynydgpkm.html

TS:   // 手写 Map<string, number>
来源：http://dali.smart0.xyz/Article/details/gtscsunals.html

Java: // 手写 HashMap
来源：http://dali.cucudq.cn/Article/details/gtlgmtnpue.html

Go:   // 手写 map[int]int
来源：http://dali.ydzc1.top/Article/details/gtbovbnpei.html

Ruby: // 手写 Hash
来源：http://dali.xziqi.cn/Article/details/gttoesoghp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinghuilouyu.cn/Article/details/gtomqfthyj.html

[N08] 生成全排列
来源：http://dali.jianghu66.top/Article/details/gtlxiwfaxq.html

Py:   itertools.permutations(arr)
来源：http://dali.guowangkeji.top/Article/details/gtebnwktje.html

PHP:  // 手写递归交换
来源：http://dali.cdnleiting.top/Article/details/gtuhiinuet.html

JS:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gtdbpnmppi.html

TS:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdeandnkz.html

Java: // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gtzijtxuqz.html

Go:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gtoltsgkgh.html

Ruby: arr.permutation.to_a
来源：http://dali.zhengqikj.top/Article/details/gtzowxgipb.html

C#:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gtigvjhmur.html

[N09] 栈与队列
来源：http://dali.yonumen.top/Article/details/gtztzugyau.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gzhubu.top/Article/details/gtxdwytmww.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jlsjyb.cn/Article/details/gtydcfluhg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zdqjudy.top/Article/details/gthuhfbglv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.quarkkingdee.top/Article/details/gtzvybmgsp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.nanxuanxn.top/Article/details/gtxfbqsolj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.pengpengdd.cyou/Article/details/gthlkzsvgu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gtqvipupjo.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hywenlv.cn/Article/details/gtjtxsmrzm.html

[N10] 链表节点定义
来源：http://dali.wangdashe.top/Article/details/gtrreatahu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtanyaljmn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yj202588.top/Article/details/gtmjslqwmc.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.aibaodan.cn/Article/details/gtyjpdwhlc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.kuanghao11.cn/Article/details/gtdazcirdb.html

Java: class Node { int v; Node next; }
来源：http://dali.dianchejie.cn/Article/details/gteckbptef.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.pengpengdd.cyou/Article/details/gtwyyoslhh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.svipenyu.cn/Article/details/gtvxlxjdvg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yuanzhike.top/Article/details/gtqvufyxqg.html

[N11] 二叉树中序遍历
来源：http://dali.meibo888.top/Article/details/gtkijfhbab.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hywenlv.cn/Article/details/gtnohjmwzq.html

PHP:  // 手写递归函数
来源：http://dali.hnxiangtu.top/Article/details/gtyrdoultu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yonumen.top/Article/details/gtftdfkhyy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pycfn.com/Article/details/gtwecmpsho.html

Java: // 手写递归
来源：http://dali.316326.xyz/Article/details/gthelbipce.html

Go:   // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gtphksacsy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.pengpengdd.cyou/Article/details/gtopotvtrt.html

C#:   // 手写递归
来源：http://dali.feifeiyinyue.top/Article/details/gtrjwnqsbt.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hysaishi.cn/Article/details/gtmuoelxji.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hnxiangtu.top/Article/details/gtlaavacvi.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jqgfzy.top/Article/details/gthjodqlgl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yanxiufei.cn/Article/details/gtcybwtjsu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.kuanghao11.cn/Article/details/gtoztbbyjf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhengqikj.top/Article/details/gteqobakdi.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjtqefdyd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xinyue.icu/Article/details/gtivugtdqr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tianlin.xyz/Article/details/gtmrrmentl.html


<!-- 参考信息 -->