代发 wailian999

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gogol.net.cn/Article/details/gtsmkbhqgd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfevutaey.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigufen.top/Article/details/gtooogpfgq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gzhubu.top/Article/details/gtmaclghde.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cheryme.top/Article/details/gtantamdqi.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenjidiqi.icu/Article/details/gtfyyoywke.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhiwuduotai.top/Article/details/gtsucfujnl.html

[K05] 深拷贝对象
来源：http://dali.gzhubu.top/Article/details/gtlgeyfknn.html

Py:   copy.deepcopy(obj)
来源：http://dali.9152youxi.cn/Article/details/gtosbivwkk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hnxiangtu.top/Article/details/gtumshdkbs.html

JS:   structuredClone(obj)
来源：http://dali.redwolf501.top/Article/details/gtdriiqqyo.html

TS:   structuredClone(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtpkzzswqi.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yj20258888.top/Article/details/gtqlnbqmrv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.guannengcc.top/Article/details/gtvxciukan.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jyoumei.cn/Article/details/gttocjfdjq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yuanzhike.top/Article/details/gtfdfkuyba.html

[K06] 解析 URL 查询串
来源：http://dali.ydzc1.top/Article/details/gteucyiqkb.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shuidangran.top/Article/details/gtojmhbdxt.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhongyouzk.top/Article/details/gtfocupgzs.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.9152youxi.cn/Article/details/gtnwgtynsm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj202588.top/Article/details/gtjocveeig.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinghuilouyu.cn/Article/details/gtedkcejaj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gtyrtdmqpi.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shanyushiyangtech.top/Article/details/gtryvraqrr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.mhx1999.top/Article/details/gtsnnvzlgw.html

[K07] 进制转换
来源：http://dali.ivvv.top/Article/details/gtunrrxcab.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gtdnedsjbw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.316326.xyz/Article/details/gtxcjsjmfu.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnjyzzjvj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtcjidwima.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gtzhlkosia.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhoulong.xyz/Article/details/gtwrfezphu.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.daxiang520.top/Article/details/gtfyclylxm.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gtrmdvnjik.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yj202588.top/Article/details/gtlfywqxrl.html

Py:   pickle.dumps(obj)
来源：http://dali.cdnleiting.top/Article/details/gtdbmjvdwi.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.birdmap.top/Article/details/gtmsvqwrut.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.bjfxy.top/Article/details/gtkghcpbzt.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhoulong.xyz/Article/details/gtnedxykin.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cqqwz.cn/Article/details/gtsmeorpnr.html

Go:   encoding/gob
来源：http://dali.chenlongwang.top/Article/details/gtaqesfjbp.html

Ruby: Marshal.dump(obj)
来源：http://dali.jyoumei.cn/Article/details/gtssltkpuh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.tian-w.cn/Article/details/gtivwzfrps.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtzxwhrhfi.html

L. 网络请求
来源：http://dali.xziqi.cn/Article/details/gtbbvgfzcj.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtnbwajadx.html

[L01] 发送 GET 请求
来源：http://dali.jlsjyb.cn/Article/details/gtashuumyx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cucudq.cn/Article/details/gtcyanvrkl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xuetiantiany.cn/Article/details/gtzujecjtv.html

JS:   await fetch(url)
来源：http://dali.pycfn.com/Article/details/gtgzgmrkzl.html

TS:   await fetch(url)
来源：http://dali.hywenlv.cn/Article/details/gtlkbztzdz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.daria6918.cn/Article/details/gteoufxksh.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinqigufen.top/Article/details/gtoxgivfon.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.havefunace.top/Article/details/gtsywdnifz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.birdmap.top/Article/details/gtiecbuqip.html

[L02] 发送 POST JSON
来源：http://dali.xuetiantiany.cn/Article/details/gtrpmhssrm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinqigufen.top/Article/details/gtsbdivrnx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.redwolf501.top/Article/details/gtrgvissjk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcpdbyvty.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pycfn.com/Article/details/gtfckvesub.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhixingplan.top/Article/details/gttyzpbmca.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sufxvd.cn/Article/details/gtibuemepc.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.quarkkingdee.top/Article/details/gtjtgeldsx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yongpay.top/Article/details/gtlpctflxu.html

[L03] 设置自定义请求头
来源：http://dali.jianghu66.top/Article/details/gtnesokbnj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yj20258.top/Article/details/gtywzskjuv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.tian-w.cn/Article/details/gtmpvgaqcr.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yonumen.top/Article/details/gtvcxyqtxl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sysykeji.top/Article/details/gtrxxmnlrj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.havefunace.top/Article/details/gtvibawpwv.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ppjwa.cn/Article/details/gttosvamgl.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenlongwang.top/Article/details/gtvphnuvtq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shuidangran.top/Article/details/gtbuvethzd.html

[L04] 设置超时
来源：http://dali.jlsjyb.cn/Article/details/gtpnoyypdr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzyzfdmtj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cqqwz.cn/Article/details/gtdtgtzklf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jiagoushi.top/Article/details/gtrkhqaymh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jianghu66.top/Article/details/gtcvfszzfe.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhongyouzk.top/Article/details/gtdhpetsbg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shanyushiyangtech.top/Article/details/gtjjrwulbv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yvedp.cn/Article/details/gtrbgnjezw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinqigfzy.top/Article/details/gtjmzdzkss.html

[L05] 上传文件（multipart）
来源：http://dali.zhoulong.xyz/Article/details/gtyxsfmnqd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.bjfxy.top/Article/details/gtjloktxhh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yvedp.cn/Article/details/gttrhpbwtv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.kuanghao11.cn/Article/details/gtwruscjsf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ehwqpu.com/Article/details/gttqdmzcho.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shuidangran.top/Article/details/gtflszrubp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.haohaochexian.top/Article/details/gtwtgupbdb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.svipenyu.cn/Article/details/gthpctjvbd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtvtgbyrof.html

[L06] 解析响应为 JSON
来源：http://dali.jiagoushi.top/Article/details/gtyunsrkjx.html

Py:   resp.json()
来源：http://dali.dashuyun.cn/Article/details/gtkcmmzlma.html

PHP:  json_decode($body, true);
来源：http://dali.guowangkeji.top/Article/details/gttegzsfiu.html

JS:   await resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gtrurapyek.html

TS:   await resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gtoxpkqtyy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yongpay.top/Article/details/gtzdmivcuq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yvedp.cn/Article/details/gtratvncnd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shuidangran.top/Article/details/gtfkdbqimt.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.chenlongwang.top/Article/details/gtjgtlczoo.html

[L07] 处理 HTTP 状态码
来源：http://dali.316326.xyz/Article/details/gtxsieqjdt.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtawtnbiat.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cucudq.cn/Article/details/gthhxhgepi.html

JS:   resp.ok;  resp.status
来源：http://dali.ehwqpu.com/Article/details/gtauryresn.html

TS:   resp.ok;  resp.status
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdlzriteb.html

Java: resp.statusCode()
来源：http://dali.c1oappe.top/Article/details/gtoxancotk.html

Go:   resp.StatusCode
来源：http://dali.gogol.net.cn/Article/details/gtvpyzzubz.html

Ruby: resp.code.to_i
来源：http://dali.9152youxi.cn/Article/details/gttoprypuk.html

C#:   (int)resp.StatusCode
来源：http://dali.aibaodan.cn/Article/details/gtrlpwmrax.html

[L08] 并发请求多个地址
来源：http://dali.bjfxy.top/Article/details/gtngyxcxzx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.9152youxi.cn/Article/details/gtebbudzmq.html

PHP:  curl_multi_init() 系列
来源：http://dali.ivvv.top/Article/details/gtzkfmweoj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tian-w.cn/Article/details/gtubdvmcuf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.quarkkingdee.top/Article/details/gtfsvltrxe.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.meibo888.top/Article/details/gtykrorxwj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.quarkkingdee.top/Article/details/gtcepvlkly.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkvzhovua.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yonumen.top/Article/details/gtjvdfxbun.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtzcsrkmnm.html

M. 命令行 / 进程 / 环境
来源：http://dali.sweek.top/Article/details/gtzyljhxmm.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtymnbrmuh.html

[M01] 读取命令行参数
来源：http://dali.gogol.net.cn/Article/details/gtwnjvjxig.html

Py:   sys.argv[1:]
来源：http://dali.shangyingyoupin.top/Article/details/gttnhxhrmv.html

PHP:  $argv;  $argc;
来源：http://dali.xylfe.cn/Article/details/gtqgabqecl.html

JS:   process.argv.slice(2)
来源：http://dali.yj20258888.top/Article/details/gtseznyuem.html

TS:   process.argv.slice(2)
来源：http://dali.tian-w.cn/Article/details/gtafhrkgmh.html

Java: args 数组（main 方法参数）
来源：http://dali.xuetiantiany.cn/Article/details/gtltqjflto.html

Go:   os.Args[1:]
来源：http://dali.yuxming.cn/Article/details/gtfnsliddi.html

Ruby: ARGV
来源：http://dali.feifeiyinyue.top/Article/details/gtehajkynm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.guannengcc.top/Article/details/gtbxocuowf.html

[M02] 读取环境变量
来源：http://dali.jinqigufen.top/Article/details/gtefjzlihc.html

Py:   os.environ.get("HOME")
来源：http://dali.yuanzhike.top/Article/details/gtfujdrrcn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hywenlv.cn/Article/details/gtnauusqpf.html

JS:   process.env.HOME
来源：http://dali.pycfn.com/Article/details/gtiweewsrs.html

TS:   process.env.HOME
来源：http://dali.fengsongda.top/Article/details/gtstragdvk.html

Java: System.getenv("HOME")
来源：http://dali.meibo888.top/Article/details/gtuggeaebn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj20258.top/Article/details/gtdusuefbo.html

Ruby: ENV["HOME"]
来源：http://dali.hnqzz.top/Article/details/gtgrhouhuc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ehwqpu.com/Article/details/gthfgfpvrv.html

[M03] 执行外部命令
来源：http://dali.dianchejie.cn/Article/details/gtgacoyugk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gogol.net.cn/Article/details/gtqbulbpby.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yonumen.top/Article/details/gtjewdedaw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.andypj.xyz/Article/details/gthnghxdqj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.andypj.xyz/Article/details/gtpcdybmus.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hnxiangtu.top/Article/details/gtfokriaih.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.smart0.xyz/Article/details/gtkebadkcx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gtyumcxjkc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zycfv.cn/Article/details/gtwnglrglw.html

[M04] 获取当前工作目录
来源：http://dali.pengpengdd.cyou/Article/details/gtsrvnsoym.html

Py:   os.getcwd()
来源：http://dali.daria6918.cn/Article/details/gtwsvbcwab.html

PHP:  getcwd();
来源：http://dali.yj20258.top/Article/details/gtdzxsfdtb.html

JS:   process.cwd()
来源：http://dali.zhixingplan.top/Article/details/gtulacipwt.html

TS:   process.cwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfawdmiun.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.dianchejie.cn/Article/details/gtxqaykasc.html

Go:   os.Getwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjhhaycuh.html

Ruby: Dir.pwd
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaehbiirj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.316326.xyz/Article/details/gtwvfqvdrq.html

[M05] 设置退出码
来源：http://dali.316326.xyz/Article/details/gtnyhdbamp.html

Py:   sys.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gtycmhuhwa.html

PHP:  exit(1);
来源：http://dali.fengsongda.top/Article/details/gtxrucrykt.html

JS:   process.exit(1)
来源：http://dali.yongpay.top/Article/details/gtypmrnrtc.html

TS:   process.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtajgestrs.html

Java: System.exit(1)
来源：http://dali.cashguo.top/Article/details/gtkmxaggus.html

Go:   os.Exit(1)
来源：http://dali.meibo888.top/Article/details/gtuhdrbqkp.html

Ruby: exit 1
来源：http://dali.cqqwz.cn/Article/details/gtikumlmow.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.wangdashe.top/Article/details/gtsknxznix.html

[M06] 向标准错误输出
来源：http://dali.cashguo.top/Article/details/gteyjeagfj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.mhx1999.top/Article/details/gtdfhzxrjp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shzxlz.cn/Article/details/gtokfyeeiv.html

JS:   console.error("err")
来源：http://dali.9152youxi.cn/Article/details/gtztpmqlar.html

TS:   console.error("err")
来源：http://dali.tanke756.top/Article/details/gtanutyvvo.html

Java: System.err.println("err")
来源：http://dali.sxryk.cn/Article/details/gtmopvudew.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.dianchejie.cn/Article/details/gtxcbncyof.html

Ruby: warn "err"
来源：http://dali.yangfankeji.com/Article/details/gtcedmmktj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhengqikj.top/Article/details/gtldrkioku.html

[M07] 判断是否为主入口
来源：http://dali.jyoumei.cn/Article/details/gtbzwxubjt.html

Py:   if __name__ == "__main__":
来源：http://dali.zhixingplan.top/Article/details/gtiyfsgmlu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.wangdashe.top/Article/details/gtoeyyorft.html

JS:   require.main === module
来源：http://dali.mhx1999.top/Article/details/gtxqiyhjjq.html

TS:   require.main === module
来源：http://dali.iojbl.cn/Article/details/gtdlsmcjgi.html

Java: public static void main(String[] args)
来源：http://dali.gzhubu.top/Article/details/gtbmbmrgdn.html

Go:   func main()
来源：http://dali.vqdsnc.cn/Article/details/gtlzayrant.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shangyingyoupin.top/Article/details/gtmwexgmmn.html

C#:   static void Main(string[] args)
来源：http://dali.sweek.top/Article/details/gtrvqcvdyk.html

[M08] 获取系统与运行时信息
来源：http://dali.cashguo.top/Article/details/gtfmchhsgo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jqgfzy.top/Article/details/gtamyvxhzj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.nanxinkj.top/Article/details/gtnjykzvtk.html

JS:   process.platform;  process.version
来源：http://dali.yueranfly.top/Article/details/gtdzkdwoxh.html

TS:   process.platform;  process.version
来源：http://dali.xylfe.cn/Article/details/gtbbtwqsxn.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yj202588.top/Article/details/gtupywbujf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.tanke756.top/Article/details/gtatsmrkjm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.kuanghao11.cn/Article/details/gtadtxzzzu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ivvv.top/Article/details/gtbsplagpi.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtguiitnqm.html

N. 数据结构与算法
来源：http://dali.kuanghao11.cn/Article/details/gtwyajvdan.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtcxdknuop.html

[N01] 二分查找（有序数组）
来源：http://dali.yj20258.top/Article/details/gtyraoswwi.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtcomlisty.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinqigufen.top/Article/details/gtljzrxlld.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gthtkmlvcq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pycfn.com/Article/details/gtilhtccqq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yj20258.top/Article/details/gtcgxnwcms.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtsvblkcgt.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.tanke756.top/Article/details/gtprdntefk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtjxzhocil.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.0kj1m.cn/Article/details/gtsytiblgs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhongyouzk.top/Article/details/gtjeldunnc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhengqikj.top/Article/details/gtavomhugx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwhhifuif.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhoulong.xyz/Article/details/gtpbucvqfq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.daria6918.cn/Article/details/gtpnhabiqk.html

Go:   slices.Sort(arr)
来源：http://dali.fengsongda.top/Article/details/gtmnhdtbam.html

Ruby: arr.sort
来源：http://dali.quarkkingdee.top/Article/details/gtqpnysdfc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.iojbl.cn/Article/details/gtmjrcdxog.html

[N03] 快速排序（分治示例）
来源：http://dali.jinqigufen.top/Article/details/gtkikzjgbn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yongpay.top/Article/details/gtldgxrxmk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.316326.xyz/Article/details/gtloiroohp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.mhx1999.top/Article/details/gtxbtiuhwd.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuanzx.com/Article/details/gtqixpbuek.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj20258888.top/Article/details/gtrmytnefu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jqgfzy.top/Article/details/gtkyfqdvre.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.andypj.xyz/Article/details/gtvyjmblql.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhongyouzk.top/Article/details/gtpyoadymw.html

[N04] 斐波那契数列
来源：http://dali.jlsjyb.cn/Article/details/gtkkbpiber.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gzhubu.top/Article/details/gtrldkbzsw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yongpay.top/Article/details/gtyrxvtksz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gttpfedpis.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqontjwhz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.sxryk.cn/Article/details/gtmatsqipj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.quarkkingdee.top/Article/details/gtyozceofy.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.havefunace.top/Article/details/gtbxdbkmyh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.guannengcc.top/Article/details/gtaymfxbdz.html

[N05] 最大公约数
来源：http://dali.hysaishi.cn/Article/details/gtauqdehse.html

Py:   math.gcd(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gtbzsjlopd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.aibaodan.cn/Article/details/gtcdvkrnht.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.smart0.xyz/Article/details/gtwfysdhjh.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxuanxn.top/Article/details/gtcbuseeuj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.feifeiyinyue.top/Article/details/gthidqzbzi.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ydzc1.top/Article/details/gtwsgjcpxh.html

Ruby: a.gcd(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgkmrfvza.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzmxpkqlc.html

[N06] 判断回文字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgdecovou.html

Py:   s == s[::-1]
来源：http://dali.meibo888.top/Article/details/gtatkrgcvj.html

PHP:  $s === strrev($s);
来源：http://dali.sufxvd.cn/Article/details/gtcipyqvmb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtepmdgapi.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gtnwhhjuow.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.kuanghao11.cn/Article/details/gtbslcsopp.html

Go:   // 双指针从两端比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyikzxdxb.html

Ruby: s == s.reverse
来源：http://dali.cucudq.cn/Article/details/gtmqebqent.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.nanxinkj.top/Article/details/gtrmxvdyff.html

[N07] 两数之和（返回下标）
来源：http://dali.hysaishi.cn/Article/details/gtbqvpnojx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zycfv.cn/Article/details/gtbqzgcxbv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.c1oappe.top/Article/details/gtqmrjtnpg.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhiwuduotai.top/Article/details/gteyspuajc.html

TS:   // 手写 Map<string, number>
来源：http://dali.xylfe.cn/Article/details/gtyfmnmxhi.html

Java: // 手写 HashMap
来源：http://dali.daria6918.cn/Article/details/gtwjbsctgj.html

Go:   // 手写 map[int]int
来源：http://dali.dashuyun.cn/Article/details/gtoaksmddp.html

Ruby: // 手写 Hash
来源：http://dali.aibaodan.cn/Article/details/gtgmhjqbfc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.daxiang520.top/Article/details/gtvcgbffqr.html

[N08] 生成全排列
来源：http://dali.ybcxt.top/Article/details/gtlknewmeq.html

Py:   itertools.permutations(arr)
来源：http://dali.havefunace.top/Article/details/gtkiiesdwe.html

PHP:  // 手写递归交换
来源：http://dali.haohaochexian.top/Article/details/gtzrrkhtxa.html

JS:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gtrfyvhrjp.html

TS:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gtfwinmiab.html

Java: // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gtxpmeekay.html

Go:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtukpbpggs.html

Ruby: arr.permutation.to_a
来源：http://dali.gotoacloud.top/Article/details/gtxyxvxwta.html

C#:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtchfwyypr.html

[N09] 栈与队列
来源：http://dali.aizwys.cn/Article/details/gtzomlhvge.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hfpthk.cn/Article/details/gtvjxvtopk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xylfe.cn/Article/details/gtmzlortzr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gtxflqksnr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nwbrower.top/Article/details/gtfmlwprgw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xziqi.cn/Article/details/gtmzppdksi.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yvedp.cn/Article/details/gtiffpazob.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hammf.cn/Article/details/gtvwenkymx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yongpay.top/Article/details/gtcmlcdbax.html

[N10] 链表节点定义
来源：http://dali.sufxvd.cn/Article/details/gtutorgyfn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.havefunace.top/Article/details/gtdiffjekg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.tanke756.top/Article/details/gtiicdwdic.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hfpthk.cn/Article/details/gtxskteqyl.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ppjwa.cn/Article/details/gttzheynna.html

Java: class Node { int v; Node next; }
来源：http://dali.9152youxi.cn/Article/details/gtzakkqltw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.meibo888.top/Article/details/gtxjiaqisv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ivvv.top/Article/details/gtyuejevpi.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ivvv.top/Article/details/gtlwvmqrcg.html

[N11] 二叉树中序遍历
来源：http://dali.gotoacloud.top/Article/details/gtodaosdcb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gogol.net.cn/Article/details/gtnllgxzng.html

PHP:  // 手写递归函数
来源：http://dali.jqgfzy.top/Article/details/gtmmpziafa.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.fengsongda.top/Article/details/gtjzjhrlfd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xylfe.cn/Article/details/gttcnzdzjl.html

Java: // 手写递归
来源：http://dali.yj20258.top/Article/details/gtbiesigia.html

Go:   // 手写递归
来源：http://dali.yj20258888.top/Article/details/gtanxjwxnj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.tanke756.top/Article/details/gtxztqzacs.html

C#:   // 手写递归
来源：http://dali.zhoulong.xyz/Article/details/gtcirnzrpq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnfhnbxep.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ehwqpu.com/Article/details/gtqzqcppum.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.fzhhl.top/Article/details/gtvvfrgaxr.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.mhx1999.top/Article/details/gtervtuovi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.snrcjt.cn/Article/details/gtshpunxrb.html


<!-- 参考信息 -->