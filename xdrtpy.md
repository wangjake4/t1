代发 wailian999

Py:   copy.deepcopy(obj)
来源：http://dali.316326.xyz/Article/details/gtcsyngasv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cucudq.cn/Article/details/gtqpyozuvy.html

JS:   structuredClone(obj)
来源：http://dali.gotoacloud.top/Article/details/gtbxdoxhpe.html

TS:   structuredClone(obj)
来源：http://dali.hywenlv.cn/Article/details/gtedxnleym.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cheryme.top/Article/details/gthyrttdgn.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.daria6918.cn/Article/details/gtcoflxdio.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yj20258.top/Article/details/gtmovlckuj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsuzfkmwm.html

[K06] 解析 URL 查询串
来源：http://dali.xuanzx.com/Article/details/gtqbyigqyj.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hammf.cn/Article/details/gtqorjsgfz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.dianchejie.cn/Article/details/gtfkjwlagc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhiwuduotai.top/Article/details/gtzyzdirvy.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.fzhhl.top/Article/details/gtvalyxkwe.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.tian-w.cn/Article/details/gtqjanwrbz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.0kj1m.cn/Article/details/gtwbtgqnkm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gthesbfhgh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jlsjyb.cn/Article/details/gtmyrbamlz.html

[K07] 进制转换
来源：http://dali.jinghuilouyu.cn/Article/details/gttiqsbgpw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtdwshagoi.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tian-w.cn/Article/details/gtpigfnrhc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.meibo888.top/Article/details/gtjyjkjvzo.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gtpvxftbfb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzzxczvft.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yvedp.cn/Article/details/gtxtcqtclu.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.daxiang520.top/Article/details/gtbvwsuyyj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsvzrsvzp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenjidiqi.icu/Article/details/gtjrnvsgyc.html

Py:   pickle.dumps(obj)
来源：http://dali.ybcxt.top/Article/details/gtdkxztela.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xinyue.icu/Article/details/gtashnewvf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cheryme.top/Article/details/gtqqdyukad.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ybcxt.top/Article/details/gtotaglrby.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.fengsongda.top/Article/details/gtpgyheloe.html

Go:   encoding/gob
来源：http://dali.cucudq.cn/Article/details/gtdpffkddc.html

Ruby: Marshal.dump(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtobdjpjzj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.fengsongda.top/Article/details/gteoxnxvro.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtxqtjwvhv.html

L. 网络请求
来源：http://dali.0kj1m.cn/Article/details/gtmkedsviw.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtswaimooa.html

[L01] 发送 GET 请求
来源：http://dali.jianghu66.top/Article/details/gtuazegrtg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.pycfn.com/Article/details/gtsdyeitiw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cucudq.cn/Article/details/gtexaoiovt.html

JS:   await fetch(url)
来源：http://dali.daria6918.cn/Article/details/gtgohhftsl.html

TS:   await fetch(url)
来源：http://dali.yvedp.cn/Article/details/gtyqyqtudx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yanxiufei.cn/Article/details/gtsftmjblb.html

Go:   resp, err := http.Get(url)
来源：http://dali.sysykeji.top/Article/details/gtuagfnkjx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmioyiohc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.quarkkingdee.top/Article/details/gtyxsokgrj.html

[L02] 发送 POST JSON
来源：http://dali.havefunace.top/Article/details/gtizixpblk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.kuanghao11.cn/Article/details/gticugcfng.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.guowangkeji.top/Article/details/gtbcktpoty.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.redwolf501.top/Article/details/gtwdfvpxbb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxuanxn.top/Article/details/gtztjseccq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.redwolf501.top/Article/details/gttxmtneoq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hnqzz.top/Article/details/gtrknectma.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.gaohongyu789.top/Article/details/gtspjpxaoo.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.aibaodan.cn/Article/details/gtfnqbzbzn.html

[L03] 设置自定义请求头
来源：http://dali.yvedp.cn/Article/details/gteimenxbh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.svipenyu.cn/Article/details/gtyflxjlzd.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ydzc1.top/Article/details/gtffdvrorp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tian-w.cn/Article/details/gtqutfqtlv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hywenlv.cn/Article/details/gtbptkbqtm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.birdmap.top/Article/details/gtmtvxybxf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yvedp.cn/Article/details/gtfaxjqukk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sweek.top/Article/details/gtdfyaoded.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtglakxbdk.html

[L04] 设置超时
来源：http://dali.yuxming.cn/Article/details/gterpwyjrx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.haohaochexian.top/Article/details/gtkikvcbct.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xziqi.cn/Article/details/gtkoxdkbmt.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dianchejie.cn/Article/details/gtfleleidd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shzxlz.cn/Article/details/gtopovxjiu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yuanzhike.top/Article/details/gtrxagnmdl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.tianlin.xyz/Article/details/gttinkpanv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xinyue.icu/Article/details/gtmvcepwnx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.tian-w.cn/Article/details/gttspdurxq.html

[L05] 上传文件（multipart）
来源：http://dali.daxiang520.top/Article/details/gtqgotuzhg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xinyue.icu/Article/details/gtipkikbsv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.redwolf501.top/Article/details/gtjvbtcmrr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shzxlz.cn/Article/details/gthppzsiqt.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shuidangran.top/Article/details/gtrxehifes.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.dianchejie.cn/Article/details/gthcvvjrhh.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zdqjudy.top/Article/details/gthszixmmg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtglxlwaol.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jianghu66.top/Article/details/gtcpnzwpeg.html

[L06] 解析响应为 JSON
来源：http://dali.ydzc1.top/Article/details/gtvdjddmzo.html

Py:   resp.json()
来源：http://dali.xuetiantiany.cn/Article/details/gtxdbbgtvl.html

PHP:  json_decode($body, true);
来源：http://dali.jyoumei.cn/Article/details/gtyboahrxr.html

JS:   await resp.json()
来源：http://dali.jiagoushi.top/Article/details/gtybywkpuc.html

TS:   await resp.json()
来源：http://dali.zhixingplan.top/Article/details/gtglepgaev.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cheryme.top/Article/details/gtkilhurmy.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhixingplan.top/Article/details/gtqmwgqcos.html

Ruby: JSON.parse(resp.body)
来源：http://dali.vqdsnc.cn/Article/details/gtvwqhkyxf.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sweek.top/Article/details/gtrhaaflcl.html

[L07] 处理 HTTP 状态码
来源：http://dali.svipenyu.cn/Article/details/gtzvbgafdp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.bjfxy.top/Article/details/gttvxljibd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shzxlz.cn/Article/details/gtseawcvvo.html

JS:   resp.ok;  resp.status
来源：http://dali.shangyingyoupin.top/Article/details/gtfzknlihn.html

TS:   resp.ok;  resp.status
来源：http://dali.dashuyun.cn/Article/details/gtskzlildm.html

Java: resp.statusCode()
来源：http://dali.zhongyouzk.top/Article/details/gtxtbhaakf.html

Go:   resp.StatusCode
来源：http://dali.sxryk.cn/Article/details/gtkkdfjwfe.html

Ruby: resp.code.to_i
来源：http://dali.c1oappe.top/Article/details/gtkdvovzuc.html

C#:   (int)resp.StatusCode
来源：http://dali.zhoulong.xyz/Article/details/gtiukrjbub.html

[L08] 并发请求多个地址
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfvtnxlfj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.snrcjt.cn/Article/details/gtqibvonfm.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbszxqkvw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yueranfly.top/Article/details/gtktsfdref.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yanxiufei.cn/Article/details/gtvpsjjdna.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yueranfly.top/Article/details/gtqngvauwi.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hfpthk.cn/Article/details/gtoayneylu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shanyushiyangtech.top/Article/details/gtixmfvjun.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yueranfly.top/Article/details/gtwncswlwx.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gttzzunwdy.html

M. 命令行 / 进程 / 环境
来源：http://dali.yj202588.top/Article/details/gtcygbrckp.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtsiwrgnyu.html

[M01] 读取命令行参数
来源：http://dali.zycfv.cn/Article/details/gtmtqzuipc.html

Py:   sys.argv[1:]
来源：http://dali.birdmap.top/Article/details/gtsbvzcxia.html

PHP:  $argv;  $argc;
来源：http://dali.jinqigufen.top/Article/details/gtgrqxidkw.html

JS:   process.argv.slice(2)
来源：http://dali.birdmap.top/Article/details/gtmmgrlvvn.html

TS:   process.argv.slice(2)
来源：http://dali.yuxming.cn/Article/details/gtwkzgspll.html

Java: args 数组（main 方法参数）
来源：http://dali.kuanghao11.cn/Article/details/gtksifelwa.html

Go:   os.Args[1:]
来源：http://dali.zhongyouzk.top/Article/details/gtyfmrwxyd.html

Ruby: ARGV
来源：http://dali.jyoumei.cn/Article/details/gtdbpthnep.html

C#:   args 数组（Main 方法参数）
来源：http://dali.feifeiyinyue.top/Article/details/gtbrcxisgu.html

[M02] 读取环境变量
来源：http://dali.cheryme.top/Article/details/gttoxhrdgo.html

Py:   os.environ.get("HOME")
来源：http://dali.yuanzhike.top/Article/details/gtoswyddlh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhiwuduotai.top/Article/details/gtfilfrxyu.html

JS:   process.env.HOME
来源：http://dali.guannengcc.top/Article/details/gtvsfajgxr.html

TS:   process.env.HOME
来源：http://dali.xylfe.cn/Article/details/gtjuphnysj.html

Java: System.getenv("HOME")
来源：http://dali.bjfxy.top/Article/details/gtbwrolfsm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyqmzztxi.html

Ruby: ENV["HOME"]
来源：http://dali.cqqwz.cn/Article/details/gtovijwsws.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.birdmap.top/Article/details/gtvexbimcl.html

[M03] 执行外部命令
来源：http://dali.aizwys.cn/Article/details/gtyflczptz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfyaepzye.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.chenjidiqi.icu/Article/details/gtmhcpxoqz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hywenlv.cn/Article/details/gtltjomhog.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuanzhike.top/Article/details/gttcvlbbvh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jiagoushi.top/Article/details/gtcranaxtu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gogol.net.cn/Article/details/gtqxvmlhiq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sweek.top/Article/details/gttatkxhih.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gogol.net.cn/Article/details/gtmuorbswm.html

[M04] 获取当前工作目录
来源：http://dali.yj20258888.top/Article/details/gtzxlehuua.html

Py:   os.getcwd()
来源：http://dali.redwolf501.top/Article/details/gtlvniicxq.html

PHP:  getcwd();
来源：http://dali.pengpengdd.cyou/Article/details/gtxzvtkdkh.html

JS:   process.cwd()
来源：http://dali.iojbl.cn/Article/details/gtwbiwsgqp.html

TS:   process.cwd()
来源：http://dali.dianchejie.cn/Article/details/gtrukvxxoa.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yj202588.top/Article/details/gtrzoqiokv.html

Go:   os.Getwd()
来源：http://dali.chenzaomai.com/Article/details/gtnnzbchjr.html

Ruby: Dir.pwd
来源：http://dali.vqdsnc.cn/Article/details/gtpqzbgouk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hysaishi.cn/Article/details/gtdiggfqnc.html

[M05] 设置退出码
来源：http://dali.hongshengwenyu.top/Article/details/gtfyowniuj.html

Py:   sys.exit(1)
来源：http://dali.xuanzx.com/Article/details/gttdaspwim.html

PHP:  exit(1);
来源：http://dali.smart0.xyz/Article/details/gtclhgghjg.html

JS:   process.exit(1)
来源：http://dali.jianghu66.top/Article/details/gtolmujihl.html

TS:   process.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtjcxyyfhc.html

Java: System.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtejguwhun.html

Go:   os.Exit(1)
来源：http://dali.meibo888.top/Article/details/gticwjkipp.html

Ruby: exit 1
来源：http://dali.dashuyun.cn/Article/details/gtbvpxqtmo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ppjwa.cn/Article/details/gtzkmfrhke.html

[M06] 向标准错误输出
来源：http://dali.dashuyun.cn/Article/details/gtqromppuv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.9152youxi.cn/Article/details/gtgfposufh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.aibaodan.cn/Article/details/gtxypwrssg.html

JS:   console.error("err")
来源：http://dali.dianchejie.cn/Article/details/gtyffbckyw.html

TS:   console.error("err")
来源：http://dali.316326.xyz/Article/details/gtlwfdypds.html

Java: System.err.println("err")
来源：http://dali.svipenyu.cn/Article/details/gtolnfwnnv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hfpthk.cn/Article/details/gtguyoivtg.html

Ruby: warn "err"
来源：http://dali.ppjwa.cn/Article/details/gtxgoojeny.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ppjwa.cn/Article/details/gtwqlgvdul.html

[M07] 判断是否为主入口
来源：http://dali.quarkkingdee.top/Article/details/gtupcizgkd.html

Py:   if __name__ == "__main__":
来源：http://dali.ppjwa.cn/Article/details/gtqlzbfhyz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmqiddmqd.html

JS:   require.main === module
来源：http://dali.hammf.cn/Article/details/gtqtuyvtiy.html

TS:   require.main === module
来源：http://dali.yj20258888.top/Article/details/gtxpslrrdk.html

Java: public static void main(String[] args)
来源：http://dali.aizwys.cn/Article/details/gtkgbkuhgj.html

Go:   func main()
来源：http://dali.andypj.xyz/Article/details/gthylcghib.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinqigufen.top/Article/details/gtnrvsovbd.html

C#:   static void Main(string[] args)
来源：http://dali.zycfv.cn/Article/details/gtbqshwlzp.html

[M08] 获取系统与运行时信息
来源：http://dali.wangshuangyany.cn/Article/details/gtozmbtsfd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtninvcvln.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.guowangkeji.top/Article/details/gtpfbqegnh.html

JS:   process.platform;  process.version
来源：http://dali.tianlin.xyz/Article/details/gtijifnddw.html

TS:   process.platform;  process.version
来源：http://dali.xinyue.icu/Article/details/gthafzdswq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.tanke756.top/Article/details/gtkforjvuo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shuidangran.top/Article/details/gtvtyfznlm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yangfankeji.com/Article/details/gtucbeusqg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.vqdsnc.cn/Article/details/gtgiaqbxni.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtoatfklfy.html

N. 数据结构与算法
来源：http://dali.pycfn.com/Article/details/gtefuuzbab.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtmychwdsy.html

[N01] 二分查找（有序数组）
来源：http://dali.hongshengwenyu.top/Article/details/gtenfrgyzx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.iojbl.cn/Article/details/gttqkzpkvb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcwytgmya.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenjidiqi.icu/Article/details/gteyrmstda.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aibaodan.cn/Article/details/gtsaduobae.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gtbuphnkiz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtvyorlodu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoazsnaov.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gtyzufyrpp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jlsjyb.cn/Article/details/gtukbtvhdi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.haohaochexian.top/Article/details/gtyppxpffc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shuidangran.top/Article/details/gtjhdrbtzp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tanke756.top/Article/details/gtabwtolur.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fzhhl.top/Article/details/gtjtvizonc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jqgufenzy.top/Article/details/gtmfpogiau.html

Go:   slices.Sort(arr)
来源：http://dali.mhx1999.top/Article/details/gtzqkkeecz.html

Ruby: arr.sort
来源：http://dali.jinqigfzy.top/Article/details/gthirhhtzg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhengqikj.top/Article/details/gtuuufzzdl.html

[N03] 快速排序（分治示例）
来源：http://dali.ehwqpu.com/Article/details/gtvcnwccae.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.fzhhl.top/Article/details/gtzjaojyds.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yj20258.top/Article/details/gttlbckluy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fzhhl.top/Article/details/gtxuwmckhb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ppjwa.cn/Article/details/gtokqxetqr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttlerrvyb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ivvv.top/Article/details/gtsjcbecjj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shanyushiyangtech.top/Article/details/gtefbsiaxk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shzxlz.cn/Article/details/gtynwldjvd.html

[N04] 斐波那契数列
来源：http://dali.dianchejie.cn/Article/details/gtdchfravm.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shuidangran.top/Article/details/gtllpmcozx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hammf.cn/Article/details/gtblgmveqh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dashuyun.cn/Article/details/gtcdwatsaq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gtvvekyoqb.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jqgufenzy.top/Article/details/gtypdiqbvd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.birdmap.top/Article/details/gtnyxkoaoy.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtghbiedvy.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.wangdashe.top/Article/details/gtijahikya.html

[N05] 最大公约数
来源：http://dali.gotoacloud.top/Article/details/gtugkjhhhm.html

Py:   math.gcd(a, b)
来源：http://dali.0kj1m.cn/Article/details/gtizxafojv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyfijdqtc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoyexigbu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tanke756.top/Article/details/gtrndsbvwc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.nwbrower.top/Article/details/gtnithizzp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yangfankeji.com/Article/details/gtyjsrwijn.html

Ruby: a.gcd(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmjqcuhwc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtprhjrbsf.html

[N06] 判断回文字符串
来源：http://dali.cqqwz.cn/Article/details/gtotplijcq.html

Py:   s == s[::-1]
来源：http://dali.quarkkingdee.top/Article/details/gtwvlinyeh.html

PHP:  $s === strrev($s);
来源：http://dali.nanxuanxn.top/Article/details/gtonoenpuf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtzoxwjpvz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gtxsobnyan.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.mhx1999.top/Article/details/gtdzyucxcq.html

Go:   // 双指针从两端比较
来源：http://dali.dianchejie.cn/Article/details/gtfszajyvq.html

Ruby: s == s.reverse
来源：http://dali.snrcjt.cn/Article/details/gtudzgrkts.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.pycfn.com/Article/details/gtoqamghix.html

[N07] 两数之和（返回下标）
来源：http://dali.guannengcc.top/Article/details/gtjowkxvof.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jqgfzy.top/Article/details/gtbhwvbuwc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yanxiufei.cn/Article/details/gtfzgwxfei.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yongpay.top/Article/details/gtlnotrrij.html

TS:   // 手写 Map<string, number>
来源：http://dali.guowangkeji.top/Article/details/gtrcqsegrk.html

Java: // 手写 HashMap
来源：http://dali.yj202588.top/Article/details/gtmqpvpfxc.html

Go:   // 手写 map[int]int
来源：http://dali.sysykeji.top/Article/details/gtzczawldu.html

Ruby: // 手写 Hash
来源：http://dali.fengsongda.top/Article/details/gtimawbujl.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cqqwz.cn/Article/details/gtnuvkqype.html

[N08] 生成全排列
来源：http://dali.shuidangran.top/Article/details/gtlbllxifm.html

Py:   itertools.permutations(arr)
来源：http://dali.c1oappe.top/Article/details/gtbfxjjlkx.html

PHP:  // 手写递归交换
来源：http://dali.feifeiyinyue.top/Article/details/gtkbfwfjvb.html

JS:   // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gtpexracfy.html

TS:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtixuqwkoc.html

Java: // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gtuzkvpgig.html

Go:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gteeiikuad.html

Ruby: arr.permutation.to_a
来源：http://dali.ydzc1.top/Article/details/gtzewjsvha.html

C#:   // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtggaikadh.html

[N09] 栈与队列
来源：http://dali.hywenlv.cn/Article/details/gteirchfzb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ppjwa.cn/Article/details/gtstzefjch.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinqigufen.top/Article/details/gtujvvutgx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.guannengcc.top/Article/details/gteuknsxgs.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gotoacloud.top/Article/details/gttflbqmgp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.316326.xyz/Article/details/gtjsqamzka.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.dashuyun.cn/Article/details/gtqeyhuwug.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nwbrower.top/Article/details/gtlmyadfus.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ybcxt.top/Article/details/gtvufhezto.html

[N10] 链表节点定义
来源：http://dali.yj20258.top/Article/details/gtkbhzkphy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yvedp.cn/Article/details/gtcwahrubs.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hammf.cn/Article/details/gtsrmfrjqw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.fengsongda.top/Article/details/gtzibzqjpa.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.9152youxi.cn/Article/details/gtzccbpash.html

Java: class Node { int v; Node next; }
来源：http://dali.smart0.xyz/Article/details/gtfmxdxcmy.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenjidiqi.icu/Article/details/gtjthunwbh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xuanzx.com/Article/details/gtbfhnwrmc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.quarkkingdee.top/Article/details/gtlxvvonpj.html

[N11] 二叉树中序遍历
来源：http://dali.ehwqpu.com/Article/details/gtzhupakwy.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.chenzaomai.com/Article/details/gteveayqrc.html

PHP:  // 手写递归函数
来源：http://dali.jiagoushi.top/Article/details/gtvxqzszbu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.fzhhl.top/Article/details/gtipvmtxsh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.wangshuangyany.cn/Article/details/gtcpfqroxx.html

Java: // 手写递归
来源：http://dali.c1oappe.top/Article/details/gtgdavcwnr.html

Go:   // 手写递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtysvddtol.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.andypj.xyz/Article/details/gtgwycrexh.html

C#:   // 手写递归
来源：http://dali.316326.xyz/Article/details/gtrfzmfbqd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhongyouzk.top/Article/details/gtgbmzoxtr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.aizwys.cn/Article/details/gtvwbvguvt.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xylfe.cn/Article/details/gteewcwpdo.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sweek.top/Article/details/gtluhrpbvy.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkmibtztr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fzhhl.top/Article/details/gtrmwzualx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.chenlongwang.top/Article/details/gtmjnxibmh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gotoacloud.top/Article/details/gtjfvdtujq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hnxiangtu.top/Article/details/gtachmyrek.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtwvwwzlet.html

O. 并发与异步
来源：http://dali.tanke756.top/Article/details/gthfdikfam.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtwrbbinqh.html

[O01] 启动一个线程
来源：http://dali.tanke756.top/Article/details/gtktnhzuew.html


<!-- 参考信息 -->