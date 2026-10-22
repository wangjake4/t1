代发 wailian999

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.mhx1999.top/Article/details/gtcjohyqlg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sysykeji.top/Article/details/gtantwzjje.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hongshengwenyu.top/Article/details/gtemdrmdyp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tianlin.xyz/Article/details/gtckpxteeo.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhongyouzk.top/Article/details/gttdzqxcfy.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.iojbl.cn/Article/details/gtqmxrttlh.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nanxuanxn.top/Article/details/gtqtgwgzcv.html

[K05] 深拷贝对象
来源：http://dali.yvedp.cn/Article/details/gthmhqvevn.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtznjrxkmh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xylfe.cn/Article/details/gtpjelbylq.html

JS:   structuredClone(obj)
来源：http://dali.jinqigufen.top/Article/details/gtagrekala.html

TS:   structuredClone(obj)
来源：http://dali.smart0.xyz/Article/details/gtjvbmrprm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xylfe.cn/Article/details/gtkexahbjv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ehwqpu.com/Article/details/gtnrdoywds.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ppjwa.cn/Article/details/gtzojmikqq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhiwuduotai.top/Article/details/gtkapkgptm.html

[K06] 解析 URL 查询串
来源：http://dali.tanke756.top/Article/details/gtjvhraooc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.iojbl.cn/Article/details/gtwonvohai.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hysaishi.cn/Article/details/gtlggifzke.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ehwqpu.com/Article/details/gtfpjfxsno.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenzaomai.com/Article/details/gthbdenoyi.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.316326.xyz/Article/details/gtppdtxprr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gtmbexseqo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cashguo.top/Article/details/gttorctisj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gtlylvniaj.html

[K07] 进制转换
来源：http://dali.c1oappe.top/Article/details/gtupzusmdx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gtrabypzpt.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gaohongyu789.top/Article/details/gtgcryefyg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gtquzcshea.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gtjeumugmd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtmfkptpte.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yj20258888.top/Article/details/gtcdifhrlr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.andypj.xyz/Article/details/gtplofryhf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtsxbetlnz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jianghu66.top/Article/details/gtnxhiclov.html

Py:   pickle.dumps(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtznvpkbqw.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ydzc1.top/Article/details/gtmcobxdxx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.wangshuangyany.cn/Article/details/gtxhzcyqjm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.havefunace.top/Article/details/gtfvkyktjf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.316326.xyz/Article/details/gtggqztygy.html

Go:   encoding/gob
来源：http://dali.daria6918.cn/Article/details/gtsxmfagud.html

Ruby: Marshal.dump(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtcgwzxrqc.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hammf.cn/Article/details/gtmcyqwtfb.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gttuustvno.html

L. 网络请求
来源：http://dali.ybcxt.top/Article/details/gtrdfsuzqf.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtawguqgrc.html

[L01] 发送 GET 请求
来源：http://dali.hnqzz.top/Article/details/gtjoqyagfk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.daxiang520.top/Article/details/gtngcjiisi.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.fengsongda.top/Article/details/gtbjlfixre.html

JS:   await fetch(url)
来源：http://dali.zhongyouzk.top/Article/details/gtopzmchay.html

TS:   await fetch(url)
来源：http://dali.zhixingplan.top/Article/details/gtyvqyccmp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yuxming.cn/Article/details/gtisyhvtzo.html

Go:   resp, err := http.Get(url)
来源：http://dali.dashuyun.cn/Article/details/gtgcizusbu.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.iojbl.cn/Article/details/gtiwdlbctq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xuanzx.com/Article/details/gtjczxgjlt.html

[L02] 发送 POST JSON
来源：http://dali.aibaodan.cn/Article/details/gtvkbpjhes.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.nanxuanxn.top/Article/details/gtpoqujyle.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.svipenyu.cn/Article/details/gtzjvedvbr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yueranfly.top/Article/details/gtjosfisqn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgufenzy.top/Article/details/gtbbhjvvby.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yangfankeji.com/Article/details/gtdfjzmubn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.svipenyu.cn/Article/details/gtarrfgcyw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.svipenyu.cn/Article/details/gtjyrzqstg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hnqzz.top/Article/details/gtcqzdqvul.html

[L03] 设置自定义请求头
来源：http://dali.zhiwuduotai.top/Article/details/gtmidhfgrq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.316326.xyz/Article/details/gtldykgjgr.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hysaishi.cn/Article/details/gtmmjxfdrf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.feifeiyinyue.top/Article/details/gtzrxxpbbn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tian-w.cn/Article/details/gtysqweqnn.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyqgoeyzc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zycfv.cn/Article/details/gtgsglzdxy.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sufxvd.cn/Article/details/gtfvhhofoc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jlsjyb.cn/Article/details/gtemtlspun.html

[L04] 设置超时
来源：http://dali.aibaodan.cn/Article/details/gtsoklbayb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.havefunace.top/Article/details/gtvxusvpzu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gogol.net.cn/Article/details/gtrutlgyrm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cqqwz.cn/Article/details/gtvfmpqhyj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tianlin.xyz/Article/details/gthzatmevl.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hfpthk.cn/Article/details/gtocicylbd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.dianchejie.cn/Article/details/gtyrzecprg.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gzhubu.top/Article/details/gtmyngwjqi.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.iojbl.cn/Article/details/gtuvikpfgu.html

[L05] 上传文件（multipart）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdomxrtas.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.tanke756.top/Article/details/gtarhzjafz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.daria6918.cn/Article/details/gtwpulplvp.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hfpthk.cn/Article/details/gtamxhiiur.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yanxiufei.cn/Article/details/gtgfswpkna.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xziqi.cn/Article/details/gtwxppnhix.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.chenlongwang.top/Article/details/gtfzzrytcg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinqigfzy.top/Article/details/gtolbjeleb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.daxiang520.top/Article/details/gtesnncsje.html

[L06] 解析响应为 JSON
来源：http://dali.cdnleiting.top/Article/details/gtinfmykda.html

Py:   resp.json()
来源：http://dali.sysykeji.top/Article/details/gtamiiihpj.html

PHP:  json_decode($body, true);
来源：http://dali.cheryme.top/Article/details/gtzqbowkjq.html

JS:   await resp.json()
来源：http://dali.ppjwa.cn/Article/details/gtgyouygnk.html

TS:   await resp.json()
来源：http://dali.sxryk.cn/Article/details/gthuvrmosg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.pycfn.com/Article/details/gtlgjgeunl.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.daxiang520.top/Article/details/gtfisoyjqs.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cqqwz.cn/Article/details/gtxmoxjfvc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gotoacloud.top/Article/details/gtuvgiqfcj.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj20258.top/Article/details/gtmokwewfx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.aibaodan.cn/Article/details/gtttliwjgk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nanxinkj.top/Article/details/gtybnbvuwq.html

JS:   resp.ok;  resp.status
来源：http://dali.xuetiantiany.cn/Article/details/gtbcdcurwc.html

TS:   resp.ok;  resp.status
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdwqeuoir.html

Java: resp.statusCode()
来源：http://dali.xinyue.icu/Article/details/gtqztdzkac.html

Go:   resp.StatusCode
来源：http://dali.meibo888.top/Article/details/gtojvkjqgq.html

Ruby: resp.code.to_i
来源：http://dali.hywenlv.cn/Article/details/gtjriipipx.html

C#:   (int)resp.StatusCode
来源：http://dali.yuanzhike.top/Article/details/gtdvugtvns.html

[L08] 并发请求多个地址
来源：http://dali.jiagoushi.top/Article/details/gttrfqlhzl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.aizwys.cn/Article/details/gthfksmiwr.html

PHP:  curl_multi_init() 系列
来源：http://dali.jlsjyb.cn/Article/details/gtypqvokff.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aibaodan.cn/Article/details/gtkwmcwiet.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjvwbhtmp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.andypj.xyz/Article/details/gtjmslpypp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrbvguzfy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.fzhhl.top/Article/details/gtudwmknwo.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shzxlz.cn/Article/details/gtixydrzlb.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtzjzkenvg.html

M. 命令行 / 进程 / 环境
来源：http://dali.cdnleiting.top/Article/details/gtmymslqtm.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtxbxtuzvx.html

[M01] 读取命令行参数
来源：http://dali.sweek.top/Article/details/gtacjdncvy.html

Py:   sys.argv[1:]
来源：http://dali.yongpay.top/Article/details/gtzyyjypqt.html

PHP:  $argv;  $argc;
来源：http://dali.cheryme.top/Article/details/gtscifujar.html

JS:   process.argv.slice(2)
来源：http://dali.hywenlv.cn/Article/details/gtimrynruz.html

TS:   process.argv.slice(2)
来源：http://dali.xylfe.cn/Article/details/gtgaeutdcq.html

Java: args 数组（main 方法参数）
来源：http://dali.nwbrower.top/Article/details/gtzmjqvizb.html

Go:   os.Args[1:]
来源：http://dali.yueranfly.top/Article/details/gtegnjizfm.html

Ruby: ARGV
来源：http://dali.aibaodan.cn/Article/details/gtxumnjfos.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ivvv.top/Article/details/gtdqsqzrxs.html

[M02] 读取环境变量
来源：http://dali.cheryme.top/Article/details/gtylflqrvd.html

Py:   os.environ.get("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gtymtdnnot.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhongyouzk.top/Article/details/gtmqbwlrjk.html

JS:   process.env.HOME
来源：http://dali.daxiang520.top/Article/details/gtlyupphab.html

TS:   process.env.HOME
来源：http://dali.zhoulong.xyz/Article/details/gtusqpiuic.html

Java: System.getenv("HOME")
来源：http://dali.mhx1999.top/Article/details/gtblyexppi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jiagoushi.top/Article/details/gtxcacnwyg.html

Ruby: ENV["HOME"]
来源：http://dali.sufxvd.cn/Article/details/gthbkrpsoc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.aizwys.cn/Article/details/gtocfhtbnb.html

[M03] 执行外部命令
来源：http://dali.yj202588.top/Article/details/gtgpxijmbj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.9152youxi.cn/Article/details/gtdfrtnxcu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xziqi.cn/Article/details/gtkynttxuo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhoulong.xyz/Article/details/gtnbaisopp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtdzpdkkun.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shzxlz.cn/Article/details/gthuviiolj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shangyingyoupin.top/Article/details/gtdqjvtfcd.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.meibo888.top/Article/details/gtjjyqxzhs.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cashguo.top/Article/details/gtjdkpjfat.html

[M04] 获取当前工作目录
来源：http://dali.316326.xyz/Article/details/gtthkiovew.html

Py:   os.getcwd()
来源：http://dali.fengsongda.top/Article/details/gtraelgwhk.html

PHP:  getcwd();
来源：http://dali.shuidangran.top/Article/details/gteveznuyo.html

JS:   process.cwd()
来源：http://dali.xziqi.cn/Article/details/gtrmugbvfy.html

TS:   process.cwd()
来源：http://dali.yj20258888.top/Article/details/gtblsqmtff.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shuidangran.top/Article/details/gtmzqvzchy.html

Go:   os.Getwd()
来源：http://dali.aizwys.cn/Article/details/gtrkskjftk.html

Ruby: Dir.pwd
来源：http://dali.0kj1m.cn/Article/details/gtnosqtrkk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.pengpengdd.cyou/Article/details/gtwvovdeaz.html

[M05] 设置退出码
来源：http://dali.yuxming.cn/Article/details/gtrtvgyzua.html

Py:   sys.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gtiglquxdk.html

PHP:  exit(1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvagfxqzr.html

JS:   process.exit(1)
来源：http://dali.redwolf501.top/Article/details/gtajxpzorw.html

TS:   process.exit(1)
来源：http://dali.ydzc1.top/Article/details/gtjcimgzzp.html

Java: System.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtrqcjovle.html

Go:   os.Exit(1)
来源：http://dali.pycfn.com/Article/details/gtimsektth.html

Ruby: exit 1
来源：http://dali.chenjidiqi.icu/Article/details/gtnxzqdast.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jqgufenzy.top/Article/details/gtwhhputsh.html

[M06] 向标准错误输出
来源：http://dali.hysaishi.cn/Article/details/gtjhipbeew.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yonumen.top/Article/details/gturolstee.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shangyingyoupin.top/Article/details/gttztiliah.html

JS:   console.error("err")
来源：http://dali.jianghu66.top/Article/details/gtyggrpfvu.html

TS:   console.error("err")
来源：http://dali.cheryme.top/Article/details/gtuginhbys.html

Java: System.err.println("err")
来源：http://dali.hnqzz.top/Article/details/gtgqketalr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xuanzx.com/Article/details/gtsjfungoz.html

Ruby: warn "err"
来源：http://dali.gaohongyu789.top/Article/details/gtlceqkkeb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.0kj1m.cn/Article/details/gtfejzqdek.html

[M07] 判断是否为主入口
来源：http://dali.yueranfly.top/Article/details/gtporbbcyh.html

Py:   if __name__ == "__main__":
来源：http://dali.daxiang520.top/Article/details/gthdkjhgwo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cucudq.cn/Article/details/gtheekktar.html

JS:   require.main === module
来源：http://dali.gaohongyu789.top/Article/details/gtqypnedpv.html

TS:   require.main === module
来源：http://dali.aibaodan.cn/Article/details/gtqrhtbdyv.html

Java: public static void main(String[] args)
来源：http://dali.redwolf501.top/Article/details/gtbdhrmcsu.html

Go:   func main()
来源：http://dali.cucudq.cn/Article/details/gtbnxhjzyv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.birdmap.top/Article/details/gtvuhphurr.html

C#:   static void Main(string[] args)
来源：http://dali.chenjidiqi.icu/Article/details/gtgtfiyhex.html

[M08] 获取系统与运行时信息
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlumxnkus.html

Py:   platform.system();  platform.python_version()
来源：http://dali.redwolf501.top/Article/details/gtfyqgmkge.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jlsjyb.cn/Article/details/gtluiamcep.html

JS:   process.platform;  process.version
来源：http://dali.ywan-chungtsiang.top/Article/details/gtluddeeyl.html

TS:   process.platform;  process.version
来源：http://dali.pengpengdd.cyou/Article/details/gtchzqvfgf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jqgfzy.top/Article/details/gtgdwiwnhf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zycfv.cn/Article/details/gtrbvbhcnw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xuetiantiany.cn/Article/details/gtaghuuhgw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yanxiufei.cn/Article/details/gtnxvzkwwf.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtsktahoal.html

N. 数据结构与算法
来源：http://dali.svipenyu.cn/Article/details/gtnumadlhq.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtiblkvbcc.html

[N01] 二分查找（有序数组）
来源：http://dali.jinqigufen.top/Article/details/gtlhdkprva.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtjureeksq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shuidangran.top/Article/details/gtqmciqeaj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.quarkkingdee.top/Article/details/gtjklogpmq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xziqi.cn/Article/details/gtnpwhardl.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtncntvsnf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jianghu66.top/Article/details/gtxdjtzihc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.chenjidiqi.icu/Article/details/gtziuyfcuc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtehrsasmi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhengqikj.top/Article/details/gtvsvayzjc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigufen.top/Article/details/gtpjlnfajm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.aibaodan.cn/Article/details/gtrqvljwyk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cucudq.cn/Article/details/gtolbhxzjx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hfpthk.cn/Article/details/gthotewqxa.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hywenlv.cn/Article/details/gtmbgkxash.html

Go:   slices.Sort(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtffeypsap.html

Ruby: arr.sort
来源：http://dali.jiagoushi.top/Article/details/gtwulizrsw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.sxryk.cn/Article/details/gtzvonbwno.html

[N03] 快速排序（分治示例）
来源：http://dali.aibaodan.cn/Article/details/gtsfgjnxeh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.svipenyu.cn/Article/details/gtmjswgerq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.wangdashe.top/Article/details/gtesctbtrh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxuanxn.top/Article/details/gtdigfifns.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinghuilouyu.cn/Article/details/gtarshnasn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hammf.cn/Article/details/gthnjfiaci.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.fengsongda.top/Article/details/gtumarwmgp.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sufxvd.cn/Article/details/gtwggvwgql.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinqigfzy.top/Article/details/gtqddzvcxo.html

[N04] 斐波那契数列
来源：http://dali.vqdsnc.cn/Article/details/gtaiadmdme.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cqqwz.cn/Article/details/gtooweclqk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj202588.top/Article/details/gtgiwglleg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gtrjqpzsoo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtoqhdcodo.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cheryme.top/Article/details/gtsqrssuqw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.fengsongda.top/Article/details/gtnqhttqit.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hammf.cn/Article/details/gtguedhxvh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sufxvd.cn/Article/details/gtkmnvzedh.html

[N05] 最大公约数
来源：http://dali.aizwys.cn/Article/details/gtaimdrevr.html

Py:   math.gcd(a, b)
来源：http://dali.jinqigufen.top/Article/details/gtkggtjbpv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.9152youxi.cn/Article/details/gtbhrzrfux.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigfzy.top/Article/details/gtkvpcleke.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.meibo888.top/Article/details/gtovvpsnlu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqlgsiyao.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.316326.xyz/Article/details/gtjhozydlg.html

Ruby: a.gcd(b)
来源：http://dali.yj202588.top/Article/details/gtpmlxtyaf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyciynggy.html

[N06] 判断回文字符串
来源：http://dali.svipenyu.cn/Article/details/gtfexvhndl.html

Py:   s == s[::-1]
来源：http://dali.feifeiyinyue.top/Article/details/gtrpuykcpj.html

PHP:  $s === strrev($s);
来源：http://dali.sxryk.cn/Article/details/gtaecdhxpo.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sweek.top/Article/details/gtancaccrf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gtmwlpxqor.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cucudq.cn/Article/details/gtzyjvpnxx.html

Go:   // 双指针从两端比较
来源：http://dali.sufxvd.cn/Article/details/gtajlmqbix.html

Ruby: s == s.reverse
来源：http://dali.yvedp.cn/Article/details/gtemgppcoc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sweek.top/Article/details/gtdgntftdl.html

[N07] 两数之和（返回下标）
来源：http://dali.zhiwuduotai.top/Article/details/gtitkrjkak.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shzxlz.cn/Article/details/gtqgpzgtkv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.meibo888.top/Article/details/gtqcpvxzav.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yuanzhike.top/Article/details/gtonysimed.html

TS:   // 手写 Map<string, number>
来源：http://dali.yueranfly.top/Article/details/gtcmjaefaz.html

Java: // 手写 HashMap
来源：http://dali.birdmap.top/Article/details/gteadrrdnq.html

Go:   // 手写 map[int]int
来源：http://dali.0kj1m.cn/Article/details/gtdpaqkjbw.html

Ruby: // 手写 Hash
来源：http://dali.shangyingyoupin.top/Article/details/gtzoxtqyea.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.vqdsnc.cn/Article/details/gtrrnmeyjw.html

[N08] 生成全排列
来源：http://dali.zhengqikj.top/Article/details/gtoosaytkp.html

Py:   itertools.permutations(arr)
来源：http://dali.guowangkeji.top/Article/details/gtrsdhpvxl.html

PHP:  // 手写递归交换
来源：http://dali.yj202588.top/Article/details/gttcoaszyd.html

JS:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gtwbdwnwco.html

TS:   // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gtvohtfhyw.html

Java: // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gtmryroacj.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gtuwxqoqhc.html

Ruby: arr.permutation.to_a
来源：http://dali.tian-w.cn/Article/details/gtwavknirh.html

C#:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gtqmuznhwn.html

[N09] 栈与队列
来源：http://dali.yuanzhike.top/Article/details/gtvalemxgi.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yj202588.top/Article/details/gthwdsnwyf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.bjfxy.top/Article/details/gtpgrlffbh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nwbrower.top/Article/details/gtdkfowsyk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.svipenyu.cn/Article/details/gtwojxnohn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yueranfly.top/Article/details/gtpbkuxsms.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.quarkkingdee.top/Article/details/gtcerzeksb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gtahshvsde.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zycfv.cn/Article/details/gtqwfsoloe.html

[N10] 链表节点定义
来源：http://dali.yvedp.cn/Article/details/gtoriqqdvi.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tanke756.top/Article/details/gttxjmhagy.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sweek.top/Article/details/gtcyvldvwz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhoulong.xyz/Article/details/gtgwepghyy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.dianchejie.cn/Article/details/gtwcqgsezm.html

Java: class Node { int v; Node next; }
来源：http://dali.shangyingyoupin.top/Article/details/gtvubecfbp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.birdmap.top/Article/details/gtlchnulvk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zdqjudy.top/Article/details/gtoklzgmgl.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhiwuduotai.top/Article/details/gtwopbibrt.html

[N11] 二叉树中序遍历
来源：http://dali.hammf.cn/Article/details/gtrnliesfq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.nwbrower.top/Article/details/gtgwsargbf.html

PHP:  // 手写递归函数
来源：http://dali.ppjwa.cn/Article/details/gtrssjryxw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.feifeiyinyue.top/Article/details/gtddryudei.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.quarkkingdee.top/Article/details/gtyfqxkphk.html

Java: // 手写递归
来源：http://dali.bjfxy.top/Article/details/gtrnwwvbhz.html

Go:   // 手写递归
来源：http://dali.ybcxt.top/Article/details/gtulzxjgvq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.nanxinkj.top/Article/details/gtpmbbvqfq.html

C#:   // 手写递归
来源：http://dali.hysaishi.cn/Article/details/gtgcgkcujw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.havefunace.top/Article/details/gtradgihin.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.andypj.xyz/Article/details/gttegqtchu.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.tian-w.cn/Article/details/gtadqpgpxd.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yonumen.top/Article/details/gtlihqfkqr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jlsjyb.cn/Article/details/gtxmbwlqzj.html


<!-- 参考信息 -->