代发 wailian999

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xylfe.cn/Article/details/gtednmmlis.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yangfankeji.com/Article/details/gtgioqxrse.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cashguo.top/Article/details/gtpqxzycje.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sufxvd.cn/Article/details/gtioginpzv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.haohaochexian.top/Article/details/gtdlcvnwbg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.aizwys.cn/Article/details/gtnwaraadp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.pengpengdd.cyou/Article/details/gtnsmfllsi.html

[K05] 深拷贝对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gtccxwkxgo.html

Py:   copy.deepcopy(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtspirpycy.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cdnleiting.top/Article/details/gtlxmjcxvi.html

JS:   structuredClone(obj)
来源：http://dali.bjfxy.top/Article/details/gtxrbwbviz.html

TS:   structuredClone(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtyuslluqk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenjidiqi.icu/Article/details/gtsfeqgeio.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhengqikj.top/Article/details/gtgywfpiwf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.chenjidiqi.icu/Article/details/gtybhhydbn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ydzc1.top/Article/details/gthlrsahuq.html

[K06] 解析 URL 查询串
来源：http://dali.tanke756.top/Article/details/gterxxqubv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.andypj.xyz/Article/details/gtnilbslni.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.wangshuangyany.cn/Article/details/gtiossokmu.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj202588.top/Article/details/gtvqcoirbk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ydzc1.top/Article/details/gtqdytpqpt.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yongpay.top/Article/details/gtqxkqsxsr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gtxldidfjj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.iojbl.cn/Article/details/gtbwzxvwvx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gtektnhebj.html

[K07] 进制转换
来源：http://dali.jqgufenzy.top/Article/details/gtrthgismm.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtouzehkhe.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yangfankeji.com/Article/details/gtsowjwsei.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtwxreeoyi.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gtbnificnd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtbqnxqooe.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinqigfzy.top/Article/details/gtuwjsvvjm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.birdmap.top/Article/details/gtdobadkbp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrnaxesnk.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgcbiueac.html

Py:   pickle.dumps(obj)
来源：http://dali.tanke756.top/Article/details/gtxbfvzemo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.mhx1999.top/Article/details/gtoxrslgql.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhixingplan.top/Article/details/gtdcpzhbay.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yuxming.cn/Article/details/gtaytkiens.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.dashuyun.cn/Article/details/gtfzhvqbhj.html

Go:   encoding/gob
来源：http://dali.zhengqikj.top/Article/details/gtnrhpdlsp.html

Ruby: Marshal.dump(obj)
来源：http://dali.dashuyun.cn/Article/details/gtsekmhgtu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.guannengcc.top/Article/details/gtgegxcnhw.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtintbeyaz.html

L. 网络请求
来源：http://dali.zhiwuduotai.top/Article/details/gtqjhlnoay.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtwmutatjm.html

[L01] 发送 GET 请求
来源：http://dali.yj20258888.top/Article/details/gtlxuakgvk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinqigufen.top/Article/details/gtvkvbfmsb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.birdmap.top/Article/details/gtypicxzra.html

JS:   await fetch(url)
来源：http://dali.iojbl.cn/Article/details/gtvzjhnpkn.html

TS:   await fetch(url)
来源：http://dali.sysykeji.top/Article/details/gtqxnazpbb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.daria6918.cn/Article/details/gtyhlszjne.html

Go:   resp, err := http.Get(url)
来源：http://dali.guowangkeji.top/Article/details/gtosdqhmsz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cdnleiting.top/Article/details/gteqwghnam.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yj202588.top/Article/details/gtrrjycron.html

[L02] 发送 POST JSON
来源：http://dali.jinqigufen.top/Article/details/gtrgwudfhh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhoulong.xyz/Article/details/gttjyjksbo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hysaishi.cn/Article/details/gtepmxvxql.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jianghu66.top/Article/details/gtiwqyedwg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jyoumei.cn/Article/details/gtgyeepufm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinqigufen.top/Article/details/gtnvlxhzhw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ppjwa.cn/Article/details/gtdhnxwdpd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sxryk.cn/Article/details/gtkqclfvkh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yuxming.cn/Article/details/gtyzxbwrru.html

[L03] 设置自定义请求头
来源：http://dali.hfpthk.cn/Article/details/gtmtugmmjd.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jiagoushi.top/Article/details/gtmcdrkxlm.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.tian-w.cn/Article/details/gtcbbjzkvi.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yanxiufei.cn/Article/details/gtkvieoqnw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yangfankeji.com/Article/details/gtmxauyhzw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhoulong.xyz/Article/details/gtjxhkpdfh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcvyfwxdt.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.quarkkingdee.top/Article/details/gtmwrizvip.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.redwolf501.top/Article/details/gtdwuwhbwj.html

[L04] 设置超时
来源：http://dali.cashguo.top/Article/details/gthyhtvvcm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jqgufenzy.top/Article/details/gtrwjeivpg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.fengsongda.top/Article/details/gtivvivaem.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nwbrower.top/Article/details/gtakctshxd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guowangkeji.top/Article/details/gtpuhfgtah.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.fengsongda.top/Article/details/gtfadjonte.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shuidangran.top/Article/details/gtbdbovvwy.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.iojbl.cn/Article/details/gtsywndzis.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gzhubu.top/Article/details/gtictremwr.html

[L05] 上传文件（multipart）
来源：http://dali.yvedp.cn/Article/details/gtafnjulcn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.havefunace.top/Article/details/gtomkjpjni.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.svipenyu.cn/Article/details/gtbxyzeugj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.quarkkingdee.top/Article/details/gtwuopkcqg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yangfankeji.com/Article/details/gtycskuubg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.daria6918.cn/Article/details/gtjbptrkxp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.havefunace.top/Article/details/gtwuldcfsm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ehwqpu.com/Article/details/gthdsmzoek.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtyojgwpwf.html

[L06] 解析响应为 JSON
来源：http://dali.hywenlv.cn/Article/details/gtqesvpcsy.html

Py:   resp.json()
来源：http://dali.haohaochexian.top/Article/details/gtuwvrfvhb.html

PHP:  json_decode($body, true);
来源：http://dali.chenlongwang.top/Article/details/gtlueyhnyc.html

JS:   await resp.json()
来源：http://dali.xuanzx.com/Article/details/gtgocexzwq.html

TS:   await resp.json()
来源：http://dali.0kj1m.cn/Article/details/gtunmnaeki.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shuidangran.top/Article/details/gtcczeyoeh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.iojbl.cn/Article/details/gtbohhkfse.html

Ruby: JSON.parse(resp.body)
来源：http://dali.dianchejie.cn/Article/details/gtumvtuity.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.bjfxy.top/Article/details/gtcdroowvc.html

[L07] 处理 HTTP 状态码
来源：http://dali.gogol.net.cn/Article/details/gtgqupqqil.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nanxuanxn.top/Article/details/gtaswclapr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenzaomai.com/Article/details/gtkzwbvsxp.html

JS:   resp.ok;  resp.status
来源：http://dali.0kj1m.cn/Article/details/gtngacalyo.html

TS:   resp.ok;  resp.status
来源：http://dali.yj20258888.top/Article/details/gtassjolzx.html

Java: resp.statusCode()
来源：http://dali.ydzc1.top/Article/details/gtjbgtmqcn.html

Go:   resp.StatusCode
来源：http://dali.cqqwz.cn/Article/details/gtvegwocuc.html

Ruby: resp.code.to_i
来源：http://dali.c1oappe.top/Article/details/gtrkojknwu.html

C#:   (int)resp.StatusCode
来源：http://dali.yongpay.top/Article/details/gtvbuvajsq.html

[L08] 并发请求多个地址
来源：http://dali.cqqwz.cn/Article/details/gtnsseqxlo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gogol.net.cn/Article/details/gtlwpvcbkb.html

PHP:  curl_multi_init() 系列
来源：http://dali.cucudq.cn/Article/details/gttblelxly.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuanzhike.top/Article/details/gtawsqxpql.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgufenzy.top/Article/details/gtdddgkszb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gtsifuxpst.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.snrcjt.cn/Article/details/gtgxvfecvr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinqigfzy.top/Article/details/gtsazryvek.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gtqpamraoe.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtnxwpifmt.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmvffwjek.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtybtcozgd.html

[M01] 读取命令行参数
来源：http://dali.zhoulong.xyz/Article/details/gtaewaxmto.html

Py:   sys.argv[1:]
来源：http://dali.hnxiangtu.top/Article/details/gtvgtgohgd.html

PHP:  $argv;  $argc;
来源：http://dali.nanxinkj.top/Article/details/gtkrfnhfjd.html

JS:   process.argv.slice(2)
来源：http://dali.iojbl.cn/Article/details/gtkljmwdje.html

TS:   process.argv.slice(2)
来源：http://dali.andypj.xyz/Article/details/gtswjzxtgk.html

Java: args 数组（main 方法参数）
来源：http://dali.quarkkingdee.top/Article/details/gtipfkrfzf.html

Go:   os.Args[1:]
来源：http://dali.vqdsnc.cn/Article/details/gtvljprfzh.html

Ruby: ARGV
来源：http://dali.jinqigufen.top/Article/details/gtokizkzom.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xylfe.cn/Article/details/gtxivfodhb.html

[M02] 读取环境变量
来源：http://dali.kuanghao11.cn/Article/details/gtzxxhyhiw.html

Py:   os.environ.get("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gtktiocxne.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hysaishi.cn/Article/details/gtecutafhw.html

JS:   process.env.HOME
来源：http://dali.zhengqikj.top/Article/details/gtpkinxntz.html

TS:   process.env.HOME
来源：http://dali.wangdashe.top/Article/details/gtugnewwqm.html

Java: System.getenv("HOME")
来源：http://dali.nwbrower.top/Article/details/gtqhcnkcgw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jqgfzy.top/Article/details/gtbyiqaiyh.html

Ruby: ENV["HOME"]
来源：http://dali.ydzc1.top/Article/details/gtqczqqrin.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.quarkkingdee.top/Article/details/gtycqftamy.html

[M03] 执行外部命令
来源：http://dali.jqgufenzy.top/Article/details/gtajxkvzrc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hysaishi.cn/Article/details/gtooarrcym.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hysaishi.cn/Article/details/gtkiyfikem.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.birdmap.top/Article/details/gtopiifqou.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258888.top/Article/details/gtbjqpnpsg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.andypj.xyz/Article/details/gtazyulkxy.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jiagoushi.top/Article/details/gtkowaznrv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yueranfly.top/Article/details/gtgsupupaa.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sxryk.cn/Article/details/gtpwtfcjlb.html

[M04] 获取当前工作目录
来源：http://dali.wangdashe.top/Article/details/gtucwczsry.html

Py:   os.getcwd()
来源：http://dali.cqqwz.cn/Article/details/gtawmjygog.html

PHP:  getcwd();
来源：http://dali.dashuyun.cn/Article/details/gtfpekcmdi.html

JS:   process.cwd()
来源：http://dali.daxiang520.top/Article/details/gtgugutscm.html

TS:   process.cwd()
来源：http://dali.jlsjyb.cn/Article/details/gtvjhvdwko.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.bjfxy.top/Article/details/gtaaraxuep.html

Go:   os.Getwd()
来源：http://dali.hnxiangtu.top/Article/details/gtfrjukbrt.html

Ruby: Dir.pwd
来源：http://dali.9152youxi.cn/Article/details/gtcnyhpfyy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.vqdsnc.cn/Article/details/gtxgldpsrq.html

[M05] 设置退出码
来源：http://dali.pengpengdd.cyou/Article/details/gtpkvctpyi.html

Py:   sys.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtydjdgeqz.html

PHP:  exit(1);
来源：http://dali.ivvv.top/Article/details/gtcvsghcnb.html

JS:   process.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtsohbdbvc.html

TS:   process.exit(1)
来源：http://dali.xylfe.cn/Article/details/gttjxvocla.html

Java: System.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gtszaigjju.html

Go:   os.Exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcprlrwpj.html

Ruby: exit 1
来源：http://dali.jyoumei.cn/Article/details/gtzotxfrtg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xuetiantiany.cn/Article/details/gtbeausshp.html

[M06] 向标准错误输出
来源：http://dali.nanxinkj.top/Article/details/gtaeeildvv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hnxiangtu.top/Article/details/gtvqyeiwbz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shangyingyoupin.top/Article/details/gtbyslwbrv.html

JS:   console.error("err")
来源：http://dali.haohaochexian.top/Article/details/gtvfzjvvdx.html

TS:   console.error("err")
来源：http://dali.dianchejie.cn/Article/details/gtivlxizma.html

Java: System.err.println("err")
来源：http://dali.yongpay.top/Article/details/gtsqzqefex.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.aizwys.cn/Article/details/gteeqpmzde.html

Ruby: warn "err"
来源：http://dali.jinqigfzy.top/Article/details/gtxrpjxpbk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.svipenyu.cn/Article/details/gtbuusybim.html

[M07] 判断是否为主入口
来源：http://dali.jianghu66.top/Article/details/gtkellipwk.html

Py:   if __name__ == "__main__":
来源：http://dali.wangshuangyany.cn/Article/details/gtpervmequ.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.fzhhl.top/Article/details/gtvdeoymoj.html

JS:   require.main === module
来源：http://dali.gaohongyu789.top/Article/details/gtamzjyuvy.html

TS:   require.main === module
来源：http://dali.meibo888.top/Article/details/gtwvjmucow.html

Java: public static void main(String[] args)
来源：http://dali.tian-w.cn/Article/details/gtavrhsemq.html

Go:   func main()
来源：http://dali.hnxiangtu.top/Article/details/gtwgeedxci.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tian-w.cn/Article/details/gtxkskvacm.html

C#:   static void Main(string[] args)
来源：http://dali.gogol.net.cn/Article/details/gtqpisggak.html

[M08] 获取系统与运行时信息
来源：http://dali.hongshengwenyu.top/Article/details/gtocpxjqwn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.chenlongwang.top/Article/details/gtrqootjht.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yuxming.cn/Article/details/gtolobflys.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gtcynpuiev.html

TS:   process.platform;  process.version
来源：http://dali.shuidangran.top/Article/details/gtuzkbdvdm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zycfv.cn/Article/details/gthmtpeiuo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.svipenyu.cn/Article/details/gtsxeojzly.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cdnleiting.top/Article/details/gtdouusmdh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yonumen.top/Article/details/gtgeixrbue.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtbiplsxca.html

N. 数据结构与算法
来源：http://dali.hysaishi.cn/Article/details/gtguzghfks.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtnqlfrzfd.html

[N01] 二分查找（有序数组）
来源：http://dali.yvedp.cn/Article/details/gthbaviiyj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtskijborb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.havefunace.top/Article/details/gtvedcnhkq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhongyouzk.top/Article/details/gtyfcgmzyy.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnqzz.top/Article/details/gthdsyswgb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gtqrphqjpg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtojxthgvb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.0kj1m.cn/Article/details/gtzgiimtgv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gthhitzyil.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.dashuyun.cn/Article/details/gtzttgrzay.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxuanxn.top/Article/details/gtvaxnlock.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yuxming.cn/Article/details/gtiszwiobw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yvedp.cn/Article/details/gtragctkmi.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.mhx1999.top/Article/details/gtroyjklss.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.nanxuanxn.top/Article/details/gtraspgfce.html

Go:   slices.Sort(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtlwqsevwx.html

Ruby: arr.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtipgdjvfs.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.meibo888.top/Article/details/gtvjvrjfvh.html

[N03] 快速排序（分治示例）
来源：http://dali.jinqigfzy.top/Article/details/gtxdeqevcf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.haohaochexian.top/Article/details/gtragnfiqs.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cashguo.top/Article/details/gtkhifixai.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258888.top/Article/details/gtbefasszy.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.svipenyu.cn/Article/details/gtyxzijnoo.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cdnleiting.top/Article/details/gtnzvsbdto.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.aizwys.cn/Article/details/gtwbxppvzl.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfjnrguiu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.fzhhl.top/Article/details/gtrilgtdzv.html

[N04] 斐波那契数列
来源：http://dali.guannengcc.top/Article/details/gtqspqllsr.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xinyue.icu/Article/details/gtjnmmzohl.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhoulong.xyz/Article/details/gtgtqysjww.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gtuwdggsup.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuxming.cn/Article/details/gticlzvrad.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xinyue.icu/Article/details/gtjhmczwir.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinqigfzy.top/Article/details/gtanjaqrhp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.nanxinkj.top/Article/details/gtmwszgdix.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.chenzaomai.com/Article/details/gtquboccgl.html

[N05] 最大公约数
来源：http://dali.yonumen.top/Article/details/gtzgzkzeoi.html

Py:   math.gcd(a, b)
来源：http://dali.yj20258.top/Article/details/gturpziqqq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinqigufen.top/Article/details/gtxmopmcam.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hongshengwenyu.top/Article/details/gtkalayeun.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.birdmap.top/Article/details/gtpbnmhuwr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xinyue.icu/Article/details/gtlryoqpnt.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ehwqpu.com/Article/details/gtidttkczy.html

Ruby: a.gcd(b)
来源：http://dali.zhoulong.xyz/Article/details/gtmqrlcmgx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.aibaodan.cn/Article/details/gtgeyaykew.html

[N06] 判断回文字符串
来源：http://dali.zhixingplan.top/Article/details/gtfmbflypf.html

Py:   s == s[::-1]
来源：http://dali.shzxlz.cn/Article/details/gtiazfygmc.html

PHP:  $s === strrev($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gthjrpxgpz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gtmlqjuesd.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gtcuxeljql.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gtdccaqhts.html

Go:   // 双指针从两端比较
来源：http://dali.chenlongwang.top/Article/details/gtzrrutjmc.html

Ruby: s == s.reverse
来源：http://dali.shzxlz.cn/Article/details/gtsqhngqcd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yueranfly.top/Article/details/gtaybkarmk.html

[N07] 两数之和（返回下标）
来源：http://dali.yj20258888.top/Article/details/gtagfofspg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.tanke756.top/Article/details/gtxguzzkwz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinghuilouyu.cn/Article/details/gtzaytxcwe.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtntjpwdgn.html

TS:   // 手写 Map<string, number>
来源：http://dali.tian-w.cn/Article/details/gtczofwyvm.html

Java: // 手写 HashMap
来源：http://dali.ydzc1.top/Article/details/gtkhvydvks.html

Go:   // 手写 map[int]int
来源：http://dali.dashuyun.cn/Article/details/gtjmovbfgw.html

Ruby: // 手写 Hash
来源：http://dali.redwolf501.top/Article/details/gtcysqaunc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xylfe.cn/Article/details/gtxqnzuojc.html

[N08] 生成全排列
来源：http://dali.yj20258.top/Article/details/gtgvtwepnb.html

Py:   itertools.permutations(arr)
来源：http://dali.zdqjudy.top/Article/details/gtnsovjxkh.html

PHP:  // 手写递归交换
来源：http://dali.kuanghao11.cn/Article/details/gticaohazy.html

JS:   // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gtxbpdprhk.html

TS:   // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gtgkyapjin.html

Java: // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gtxhkrmbgl.html

Go:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gtnoddfvli.html

Ruby: arr.permutation.to_a
来源：http://dali.daria6918.cn/Article/details/gtsklbwtwd.html

C#:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gthexzogsp.html

[N09] 栈与队列
来源：http://dali.aibaodan.cn/Article/details/gtevjealfg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gtobebhfbe.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.birdmap.top/Article/details/gtqteqqawm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.fzhhl.top/Article/details/gtuuyxgswj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ehwqpu.com/Article/details/gtoxfsjist.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shuidangran.top/Article/details/gtpitiisix.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hongshengwenyu.top/Article/details/gtrxeckzwe.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.pycfn.com/Article/details/gtrzhucoyx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jqgufenzy.top/Article/details/gtttrjjuee.html

[N10] 链表节点定义
来源：http://dali.jianghu66.top/Article/details/gtruckhnnk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yueranfly.top/Article/details/gtqnydnhqd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zdqjudy.top/Article/details/gtohnbigrq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ivvv.top/Article/details/gtfbotabuq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yongpay.top/Article/details/gtxzpxcamd.html

Java: class Node { int v; Node next; }
来源：http://dali.chenlongwang.top/Article/details/gtltmxmzkw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hammf.cn/Article/details/gtgkthvqwg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.wangdashe.top/Article/details/gtjwzppymy.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xylfe.cn/Article/details/gtileihwlf.html

[N11] 二叉树中序遍历
来源：http://dali.hammf.cn/Article/details/gtsmgwdern.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sweek.top/Article/details/gtlsatjmci.html

PHP:  // 手写递归函数
来源：http://dali.zhixingplan.top/Article/details/gtsiapklho.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nwbrower.top/Article/details/gtjnkfcuez.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenjidiqi.icu/Article/details/gtpoaipagx.html

Java: // 手写递归
来源：http://dali.wangshuangyany.cn/Article/details/gtybyzpdpo.html

Go:   // 手写递归
来源：http://dali.cashguo.top/Article/details/gtfxqovbsv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.chenjidiqi.icu/Article/details/gtkuuupdvy.html

C#:   // 手写递归
来源：http://dali.jinghuilouyu.cn/Article/details/gthrykmhst.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.tianlin.xyz/Article/details/gtwhhptfjj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xuanzx.com/Article/details/gteyywbcvx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xinyue.icu/Article/details/gtbnsgliwf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yangfankeji.com/Article/details/gtlbzqqpwi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gotoacloud.top/Article/details/gtwaddcpxu.html


<!-- 参考信息 -->