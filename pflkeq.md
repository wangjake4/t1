代发 wailian999

[K06] 解析 URL 查询串
来源：http://dali.xylfe.cn/Article/details/gtdmmbwhzz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.meibo888.top/Article/details/gtxgjgwapx.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ybcxt.top/Article/details/gtwccgzstx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daxiang520.top/Article/details/gtcurwwrjw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj202588.top/Article/details/gtdqhyfxoa.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.haohaochexian.top/Article/details/gtekwmitib.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sysykeji.top/Article/details/gtpdmjczbu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gtshvagbaw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ivvv.top/Article/details/gtzvgiesnn.html

[K07] 进制转换
来源：http://dali.gaohongyu789.top/Article/details/gtwkthwlar.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gtcokueubd.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jyoumei.cn/Article/details/gtjuilxkhb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtkghxevcz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtjarfygjx.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gtmoppeipr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nwbrower.top/Article/details/gtkdzmrkdo.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hysaishi.cn/Article/details/gtknlkcrmj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gtclxmewst.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.tanke756.top/Article/details/gtqitxigtr.html

Py:   pickle.dumps(obj)
来源：http://dali.pycfn.com/Article/details/gtwdhbbvqg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjrjbwzfo.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.pycfn.com/Article/details/gtzlylocgr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.nanxuanxn.top/Article/details/gthgsgrlsj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yongpay.top/Article/details/gtxqivynqu.html

Go:   encoding/gob
来源：http://dali.fzhhl.top/Article/details/gtjtmloalj.html

Ruby: Marshal.dump(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbjaohbwu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.havefunace.top/Article/details/gtpolmtgou.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtpqgnwhfa.html

L. 网络请求
来源：http://dali.guannengcc.top/Article/details/gtscjkmndw.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtlxnunvud.html

[L01] 发送 GET 请求
来源：http://dali.shangyingyoupin.top/Article/details/gtriwsgafg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jqgufenzy.top/Article/details/gtwpwmsrii.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.daria6918.cn/Article/details/gtcguiobty.html

JS:   await fetch(url)
来源：http://dali.zdqjudy.top/Article/details/gtzkydqwom.html

TS:   await fetch(url)
来源：http://dali.daxiang520.top/Article/details/gtplczyjdb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yuanzhike.top/Article/details/gtmclhuuwi.html

Go:   resp, err := http.Get(url)
来源：http://dali.9152youxi.cn/Article/details/gtovnillwz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.daxiang520.top/Article/details/gtmpcxkcjs.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.smart0.xyz/Article/details/gtyktzfopq.html

[L02] 发送 POST JSON
来源：http://dali.shangyingyoupin.top/Article/details/gtnsljkqyt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gogol.net.cn/Article/details/gtjbzghqxz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhiwuduotai.top/Article/details/gtjcpcbkrz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.vqdsnc.cn/Article/details/gtxsvceggd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sxryk.cn/Article/details/gtjkepsvth.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hnxiangtu.top/Article/details/gtxcisezke.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.tian-w.cn/Article/details/gtckvygixk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.c1oappe.top/Article/details/gtfobvbgwq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.vqdsnc.cn/Article/details/gtydjxfldv.html

[L03] 设置自定义请求头
来源：http://dali.dianchejie.cn/Article/details/gtimghinfm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shanyushiyangtech.top/Article/details/gtaaliprji.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.mhx1999.top/Article/details/gtfagyxqbh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xylfe.cn/Article/details/gtchexpzbi.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hammf.cn/Article/details/gtrftnlykg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xinyue.icu/Article/details/gtgdjeudbs.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.fzhhl.top/Article/details/gtpxzqjgif.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hnqzz.top/Article/details/gtvrxbbyuw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.bjfxy.top/Article/details/gtdhqgwskm.html

[L04] 设置超时
来源：http://dali.vqdsnc.cn/Article/details/gtexjstvpz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yj202588.top/Article/details/gtttleyqtu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj20258.top/Article/details/gtiialkqpg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.9152youxi.cn/Article/details/gtgrisaoby.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shzxlz.cn/Article/details/gtemclewyi.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hammf.cn/Article/details/gtjkygxhgv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhiwuduotai.top/Article/details/gtbfurkmlq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gzhubu.top/Article/details/gtwvabawop.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.tianlin.xyz/Article/details/gtwphyluka.html

[L05] 上传文件（multipart）
来源：http://dali.havefunace.top/Article/details/gtedypsser.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.fengsongda.top/Article/details/gtgatmzexa.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.dashuyun.cn/Article/details/gtrdbhzsmk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ivvv.top/Article/details/gtapozfwfs.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sweek.top/Article/details/gtrfhsvioa.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xylfe.cn/Article/details/gtisvuxxxk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.feifeiyinyue.top/Article/details/gtqnuybxvh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ehwqpu.com/Article/details/gtxpwpjwll.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.daria6918.cn/Article/details/gthxvauwis.html

[L06] 解析响应为 JSON
来源：http://dali.smart0.xyz/Article/details/gtzbfaxvqh.html

Py:   resp.json()
来源：http://dali.jinqigufen.top/Article/details/gtcpqxjvkr.html

PHP:  json_decode($body, true);
来源：http://dali.jqgfzy.top/Article/details/gtneezvvww.html

JS:   await resp.json()
来源：http://dali.jyoumei.cn/Article/details/gtjfrxlbtt.html

TS:   await resp.json()
来源：http://dali.nwbrower.top/Article/details/gtihapzmak.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.tanke756.top/Article/details/gtjfjxmhtn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.vqdsnc.cn/Article/details/gtmacglpym.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cucudq.cn/Article/details/gttsibmsjh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.dashuyun.cn/Article/details/gtjbvyuocr.html

[L07] 处理 HTTP 状态码
来源：http://dali.chenzaomai.com/Article/details/gtfnvegsdj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cashguo.top/Article/details/gtnutupeii.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nwbrower.top/Article/details/gtctuibgcf.html

JS:   resp.ok;  resp.status
来源：http://dali.cqqwz.cn/Article/details/gtayirltma.html

TS:   resp.ok;  resp.status
来源：http://dali.cashguo.top/Article/details/gtjelcnjsi.html

Java: resp.statusCode()
来源：http://dali.andypj.xyz/Article/details/gtijqrlkdt.html

Go:   resp.StatusCode
来源：http://dali.zhongyouzk.top/Article/details/gtxlrlznzv.html

Ruby: resp.code.to_i
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfwlhlfkc.html

C#:   (int)resp.StatusCode
来源：http://dali.ivvv.top/Article/details/gttogrszze.html

[L08] 并发请求多个地址
来源：http://dali.jqgufenzy.top/Article/details/gtswdxclqz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shangyingyoupin.top/Article/details/gtjphbhxrb.html

PHP:  curl_multi_init() 系列
来源：http://dali.tanke756.top/Article/details/gtfmmuqsnq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jianghu66.top/Article/details/gtsjuqziiv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xinyue.icu/Article/details/gthdyxcygw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xylfe.cn/Article/details/gtrajrraxm.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ehwqpu.com/Article/details/gtvgcxlbci.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.birdmap.top/Article/details/gtswexjzez.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nanxuanxn.top/Article/details/gtqzntknmf.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtlrdhkcgi.html

M. 命令行 / 进程 / 环境
来源：http://dali.shanyushiyangtech.top/Article/details/gtqmnxjtya.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtkqvdprsd.html

[M01] 读取命令行参数
来源：http://dali.zhengqikj.top/Article/details/gtqkelhdqo.html

Py:   sys.argv[1:]
来源：http://dali.yj202588.top/Article/details/gtdgvfalmf.html

PHP:  $argv;  $argc;
来源：http://dali.vqdsnc.cn/Article/details/gtjgzhxxkq.html

JS:   process.argv.slice(2)
来源：http://dali.sweek.top/Article/details/gtuxafugcv.html

TS:   process.argv.slice(2)
来源：http://dali.hysaishi.cn/Article/details/gtwnqmpbpn.html

Java: args 数组（main 方法参数）
来源：http://dali.havefunace.top/Article/details/gtckebyect.html

Go:   os.Args[1:]
来源：http://dali.yuanzhike.top/Article/details/gtskdvhmmw.html

Ruby: ARGV
来源：http://dali.316326.xyz/Article/details/gtejxhykic.html

C#:   args 数组（Main 方法参数）
来源：http://dali.haohaochexian.top/Article/details/gtdmzxeine.html

[M02] 读取环境变量
来源：http://dali.yueranfly.top/Article/details/gteyagxkcw.html

Py:   os.environ.get("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gtpntsjhby.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.mhx1999.top/Article/details/gtisskhwqj.html

JS:   process.env.HOME
来源：http://dali.hfpthk.cn/Article/details/gtzcwxviwb.html

TS:   process.env.HOME
来源：http://dali.sufxvd.cn/Article/details/gtizhledmj.html

Java: System.getenv("HOME")
来源：http://dali.316326.xyz/Article/details/gtexydlavg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yangfankeji.com/Article/details/gtairgxsov.html

Ruby: ENV["HOME"]
来源：http://dali.jianghu66.top/Article/details/gtxebrlziz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yangfankeji.com/Article/details/gtuidmkwld.html

[M03] 执行外部命令
来源：http://dali.cdnleiting.top/Article/details/gtovgdqlse.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shuidangran.top/Article/details/gtvsntoaxv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jyoumei.cn/Article/details/gtayccfcwx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.pengpengdd.cyou/Article/details/gtwltlkdik.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpxqvkkfw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cucudq.cn/Article/details/gthmacruqg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.smart0.xyz/Article/details/gtzkvdlgwv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jyoumei.cn/Article/details/gtnwxxersd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shangyingyoupin.top/Article/details/gtadllokea.html

[M04] 获取当前工作目录
来源：http://dali.sufxvd.cn/Article/details/gtnposbjxm.html

Py:   os.getcwd()
来源：http://dali.yj20258.top/Article/details/gtzzeinpmi.html

PHP:  getcwd();
来源：http://dali.hnqzz.top/Article/details/gtgonzgcfv.html

JS:   process.cwd()
来源：http://dali.gotoacloud.top/Article/details/gtbczwmvhc.html

TS:   process.cwd()
来源：http://dali.zhiwuduotai.top/Article/details/gtkvwxhrqb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jqgfzy.top/Article/details/gttqhsgilg.html

Go:   os.Getwd()
来源：http://dali.sweek.top/Article/details/gtdexricyv.html

Ruby: Dir.pwd
来源：http://dali.zhiwuduotai.top/Article/details/gtedvhefvk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.guowangkeji.top/Article/details/gtgjblauje.html

[M05] 设置退出码
来源：http://dali.jiagoushi.top/Article/details/gtvwwgnvli.html

Py:   sys.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gtfibitwrl.html

PHP:  exit(1);
来源：http://dali.sxryk.cn/Article/details/gtsfbndzvg.html

JS:   process.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtpzjwcedj.html

TS:   process.exit(1)
来源：http://dali.tian-w.cn/Article/details/gtklotamjt.html

Java: System.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtnfufmxuv.html

Go:   os.Exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gtxkrusehc.html

Ruby: exit 1
来源：http://dali.cqqwz.cn/Article/details/gtvemafiec.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yuanzhike.top/Article/details/gthkjikedl.html

[M06] 向标准错误输出
来源：http://dali.chenlongwang.top/Article/details/gtiwakiqyz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.snrcjt.cn/Article/details/gtbwjuppld.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.dianchejie.cn/Article/details/gtbgdqnjix.html

JS:   console.error("err")
来源：http://dali.xuetiantiany.cn/Article/details/gtxtyiuspe.html

TS:   console.error("err")
来源：http://dali.aibaodan.cn/Article/details/gtkplzmygk.html

Java: System.err.println("err")
来源：http://dali.zdqjudy.top/Article/details/gtecvxynmp.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.fzhhl.top/Article/details/gtevuodtsj.html

Ruby: warn "err"
来源：http://dali.jinghuilouyu.cn/Article/details/gtqzdmjnhh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nanxuanxn.top/Article/details/gtjmwsiufd.html

[M07] 判断是否为主入口
来源：http://dali.sweek.top/Article/details/gtbmgtbnyb.html

Py:   if __name__ == "__main__":
来源：http://dali.zycfv.cn/Article/details/gtvbefpztw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hysaishi.cn/Article/details/gtfepxoakq.html

JS:   require.main === module
来源：http://dali.nanxuanxn.top/Article/details/gtdngvltol.html

TS:   require.main === module
来源：http://dali.yuanzhike.top/Article/details/gtwqrgvnje.html

Java: public static void main(String[] args)
来源：http://dali.hnxiangtu.top/Article/details/gtotuogwgt.html

Go:   func main()
来源：http://dali.zhixingplan.top/Article/details/gtqqjlgplt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xuanzx.com/Article/details/gtcxlmudvh.html

C#:   static void Main(string[] args)
来源：http://dali.hammf.cn/Article/details/gtqkryphip.html

[M08] 获取系统与运行时信息
来源：http://dali.gotoacloud.top/Article/details/gtrhjhdmwg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.chenlongwang.top/Article/details/gthpelbgpo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sxryk.cn/Article/details/gtdxzzgkpp.html

JS:   process.platform;  process.version
来源：http://dali.jianghu66.top/Article/details/gtmuvfcjbg.html

TS:   process.platform;  process.version
来源：http://dali.sysykeji.top/Article/details/gtwllxdbeo.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gzhubu.top/Article/details/gtmxxxhgus.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gotoacloud.top/Article/details/gtconxkvfs.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sysykeji.top/Article/details/gtdmbcotuy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gtmbohidoa.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtbmgyfcrj.html

N. 数据结构与算法
来源：http://dali.jyoumei.cn/Article/details/gtmcnyvvcq.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtgdpahqrg.html

[N01] 二分查找（有序数组）
来源：http://dali.tanke756.top/Article/details/gtwtztstwr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtnxgrcmtc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ppjwa.cn/Article/details/gtfqulmmhn.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xinyue.icu/Article/details/gtuuvonuxh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.redwolf501.top/Article/details/gtepgkfups.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gthllkpbzt.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sweek.top/Article/details/gtnoihcrts.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hywenlv.cn/Article/details/gtyiosvlxj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtajuowppd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqgdkuzmx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nwbrower.top/Article/details/gtdxafzpxb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.316326.xyz/Article/details/gttoltshqp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fengsongda.top/Article/details/gtrucsucro.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nwbrower.top/Article/details/gtkockvwwe.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cqqwz.cn/Article/details/gtnyufjbvw.html

Go:   slices.Sort(arr)
来源：http://dali.yj20258.top/Article/details/gtcepiyocs.html

Ruby: arr.sort
来源：http://dali.chenjidiqi.icu/Article/details/gtbaafxmus.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.dashuyun.cn/Article/details/gtghvnxzuw.html

[N03] 快速排序（分治示例）
来源：http://dali.redwolf501.top/Article/details/gtxvvdkkcz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.haohaochexian.top/Article/details/gtizodvlyo.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tanke756.top/Article/details/gtckkbzlvl.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cqqwz.cn/Article/details/gtzfwcfxbh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxinkj.top/Article/details/gtkzvyvhpp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shzxlz.cn/Article/details/gtcswrmhtg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jiagoushi.top/Article/details/gtytzdmegv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.redwolf501.top/Article/details/gtmfwrazpb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xylfe.cn/Article/details/gttnxawodo.html

[N04] 斐波那契数列
来源：http://dali.dashuyun.cn/Article/details/gtujyuaunb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xinyue.icu/Article/details/gtnnfhrqwy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.haohaochexian.top/Article/details/gtrpdvfdse.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.meibo888.top/Article/details/gtvdgyrejg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sxryk.cn/Article/details/gtoozqxfud.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gaohongyu789.top/Article/details/gthnpclfrg.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtagphyvxb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yuanzhike.top/Article/details/gtqrzgxwzq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtioenpxbd.html

[N05] 最大公约数
来源：http://dali.nanxuanxn.top/Article/details/gtqfljfxcf.html

Py:   math.gcd(a, b)
来源：http://dali.yuanzhike.top/Article/details/gtpqxgcnsu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.kuanghao11.cn/Article/details/gtcishslda.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhiwuduotai.top/Article/details/gtlgqbntxg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tian-w.cn/Article/details/gtxijngqgy.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cheryme.top/Article/details/gtzulbtnnz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.0kj1m.cn/Article/details/gtkmchhmdz.html

Ruby: a.gcd(b)
来源：http://dali.zycfv.cn/Article/details/gttfbywwdj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hywenlv.cn/Article/details/gtnzlighwg.html

[N06] 判断回文字符串
来源：http://dali.hysaishi.cn/Article/details/gtqgfzyivg.html

Py:   s == s[::-1]
来源：http://dali.svipenyu.cn/Article/details/gtlnvarmfz.html

PHP:  $s === strrev($s);
来源：http://dali.xinyue.icu/Article/details/gtdtbadbjw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gthvfyeagb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gtqapandgn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.birdmap.top/Article/details/gtjqusbbyk.html

Go:   // 双指针从两端比较
来源：http://dali.zhengqikj.top/Article/details/gtvzvhrthe.html

Ruby: s == s.reverse
来源：http://dali.jinqigufen.top/Article/details/gtahftnuoy.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.redwolf501.top/Article/details/gtsmlcmqcn.html

[N07] 两数之和（返回下标）
来源：http://dali.hammf.cn/Article/details/gtibzyoout.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinqigfzy.top/Article/details/gtgdgndyew.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.quarkkingdee.top/Article/details/gtydvbsowz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cheryme.top/Article/details/gtvkzdrtde.html

TS:   // 手写 Map<string, number>
来源：http://dali.chenjidiqi.icu/Article/details/gtvfgcjkyn.html

Java: // 手写 HashMap
来源：http://dali.birdmap.top/Article/details/gtlvpionft.html

Go:   // 手写 map[int]int
来源：http://dali.yongpay.top/Article/details/gtetwolzui.html

Ruby: // 手写 Hash
来源：http://dali.cdnleiting.top/Article/details/gtbsthbdyx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gogol.net.cn/Article/details/gtcblfoxmn.html

[N08] 生成全排列
来源：http://dali.zhengqikj.top/Article/details/gtxtjybafe.html

Py:   itertools.permutations(arr)
来源：http://dali.gzhubu.top/Article/details/gtarvqrjsl.html

PHP:  // 手写递归交换
来源：http://dali.aibaodan.cn/Article/details/gtjlnpndee.html

JS:   // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gtppzrkzqh.html

TS:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtamzyrdfs.html

Java: // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gtpowizwyh.html

Go:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gtcwivfnym.html

Ruby: arr.permutation.to_a
来源：http://dali.daria6918.cn/Article/details/gtzzrgivws.html

C#:   // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gtmxcrxzis.html

[N09] 栈与队列
来源：http://dali.cdnleiting.top/Article/details/gtruvprwtm.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cashguo.top/Article/details/gthzwzwizr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinqigfzy.top/Article/details/gtzvjwftzu.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gtdsxndaiw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinghuilouyu.cn/Article/details/gtjajywtmv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yangfankeji.com/Article/details/gtrllpdscc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hysaishi.cn/Article/details/gtuetytaub.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmdavyxki.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xylfe.cn/Article/details/gtbkbmdpqj.html

[N10] 链表节点定义
来源：http://dali.cucudq.cn/Article/details/gtdkhezfsx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gtmywehgdu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.wangdashe.top/Article/details/gttpnqcufe.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.aibaodan.cn/Article/details/gtaadmkjec.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.haohaochexian.top/Article/details/gtiwhyohkf.html

Java: class Node { int v; Node next; }
来源：http://dali.jqgufenzy.top/Article/details/gtvmbqxxex.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.tanke756.top/Article/details/gtjgxkjvnx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.9152youxi.cn/Article/details/gtrzhxudhc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.wangdashe.top/Article/details/gtujrkvsmt.html

[N11] 二叉树中序遍历
来源：http://dali.ppjwa.cn/Article/details/gtxaggfpqy.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.guannengcc.top/Article/details/gtkmbosqcy.html

PHP:  // 手写递归函数
来源：http://dali.shangyingyoupin.top/Article/details/gtuqqxoziw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.snrcjt.cn/Article/details/gtsovgqszd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sysykeji.top/Article/details/gtbeoysmkc.html

Java: // 手写递归
来源：http://dali.hongshengwenyu.top/Article/details/gtjkckmozn.html

Go:   // 手写递归
来源：http://dali.hnxiangtu.top/Article/details/gttcvpcgmf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jlsjyb.cn/Article/details/gtksxxtqfn.html

C#:   // 手写递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtysllbkbe.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zdqjudy.top/Article/details/gtpjwixwbl.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.fengsongda.top/Article/details/gtdxdzgofw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xinyue.icu/Article/details/gtiscegfiz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ivvv.top/Article/details/gtgeynpmoo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sweek.top/Article/details/gtaqkwdflp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aizwys.cn/Article/details/gtysovzuyj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cashguo.top/Article/details/gtcvrzkmum.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.iojbl.cn/Article/details/gtngxbybws.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.svipenyu.cn/Article/details/gterjqtpup.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtpplyoarh.html

O. 并发与异步
来源：http://dali.yueranfly.top/Article/details/gttonudjnb.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtxxbqlidl.html

[O01] 启动一个线程
来源：http://dali.jiagoushi.top/Article/details/gtdeafanve.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.andypj.xyz/Article/details/gtpcwqgvno.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.kuanghao11.cn/Article/details/gtocrgumkq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.redwolf501.top/Article/details/gtcojbwwcv.html

TS:   // 同 JS
来源：http://dali.zdqjudy.top/Article/details/gteljumklq.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinghuilouyu.cn/Article/details/gtesadhyiy.html

Go:   go f()
来源：http://dali.0kj1m.cn/Article/details/gthbesxslg.html

Ruby: Thread.new { f }
来源：http://dali.gogol.net.cn/Article/details/gtgztaecwg.html

C#:   Task.Run(() => F());
来源：http://dali.sufxvd.cn/Article/details/gtigtcxjpt.html


<!-- 参考信息 -->