代发 wailian999

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sysykeji.top/Article/details/gtulapihgl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.dianchejie.cn/Article/details/gtwstfznzz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgufenzy.top/Article/details/gtvuxdxvhm.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gtzxafuees.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhoulong.xyz/Article/details/gthxrvauea.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhiwuduotai.top/Article/details/gtovvntkey.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jyoumei.cn/Article/details/gtstphsjey.html

[K05] 深拷贝对象
来源：http://dali.xylfe.cn/Article/details/gtnuuezuwg.html

Py:   copy.deepcopy(obj)
来源：http://dali.xuanzx.com/Article/details/gtnkiiedal.html

PHP:  unserialize(serialize($obj));
来源：http://dali.pycfn.com/Article/details/gtrnrmewdv.html

JS:   structuredClone(obj)
来源：http://dali.9152youxi.cn/Article/details/gtaefktjcj.html

TS:   structuredClone(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtapffwfnh.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jqgfzy.top/Article/details/gtcnzdtyoy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.fzhhl.top/Article/details/gtifqyiolk.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.bjfxy.top/Article/details/gtbmbnlilo.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shangyingyoupin.top/Article/details/gtemykkkmx.html

[K06] 解析 URL 查询串
来源：http://dali.tanke756.top/Article/details/gtecukripk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yongpay.top/Article/details/gtmcbdpqat.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinqigufen.top/Article/details/gtpintbusn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guowangkeji.top/Article/details/gtfuiphweq.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.9152youxi.cn/Article/details/gtmssofoeb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.bjfxy.top/Article/details/gtwqckwghl.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hnqzz.top/Article/details/gtaoumequr.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ivvv.top/Article/details/gtrmofhctk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtebctvirz.html

[K07] 进制转换
来源：http://dali.jqgfzy.top/Article/details/gtehjkvvjg.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtpzgnswxd.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhoulong.xyz/Article/details/gtxikxaooh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gtskjqrjoq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtexcfdgfk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gtxeushria.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.iojbl.cn/Article/details/gteoqtvxvg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yuxming.cn/Article/details/gtlpllviek.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtufwvfpbw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nwbrower.top/Article/details/gtpcjrpcnu.html

Py:   pickle.dumps(obj)
来源：http://dali.fengsongda.top/Article/details/gtkzhkczpd.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xinyue.icu/Article/details/gtrlncrfnp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zycfv.cn/Article/details/gtboblhihn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258.top/Article/details/gtubndwpdh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhongyouzk.top/Article/details/gtbwcwsmsp.html

Go:   encoding/gob
来源：http://dali.sufxvd.cn/Article/details/gtjaslsyju.html

Ruby: Marshal.dump(obj)
来源：http://dali.c1oappe.top/Article/details/gtssqphuot.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.fengsongda.top/Article/details/gtdfaicigg.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gteveagpar.html

L. 网络请求
来源：http://dali.yueranfly.top/Article/details/gtjctlnlbx.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtmlbczgev.html

[L01] 发送 GET 请求
来源：http://dali.jinqigfzy.top/Article/details/gtvjncdlka.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.smart0.xyz/Article/details/gtrxflfcgd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gogol.net.cn/Article/details/gtoffuvjxo.html

JS:   await fetch(url)
来源：http://dali.guowangkeji.top/Article/details/gtopwwhdab.html

TS:   await fetch(url)
来源：http://dali.kuanghao11.cn/Article/details/gtzkbhtpub.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gtvjwlpedo.html

Go:   resp, err := http.Get(url)
来源：http://dali.dianchejie.cn/Article/details/gtlhvmijdc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cdnleiting.top/Article/details/gtqaxopddq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cheryme.top/Article/details/gtztstufbj.html

[L02] 发送 POST JSON
来源：http://dali.jinqigfzy.top/Article/details/gtvswatrjf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jianghu66.top/Article/details/gtsibjhclg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yj202588.top/Article/details/gtvpbdjtqc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.mhx1999.top/Article/details/gtpdmhkxhk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgufenzy.top/Article/details/gtentspyef.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hywenlv.cn/Article/details/gtjkyszpzo.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.wangshuangyany.cn/Article/details/gtnppxxlbj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.aizwys.cn/Article/details/gtidrghfud.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinqigufen.top/Article/details/gtyiepojos.html

[L03] 设置自定义请求头
来源：http://dali.cucudq.cn/Article/details/gtsywibcjg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.chenjidiqi.icu/Article/details/gtrftpxjoo.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yanxiufei.cn/Article/details/gtxmzgdrhy.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yonumen.top/Article/details/gttvkpfqsn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxuanxn.top/Article/details/gteqwflonv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.tian-w.cn/Article/details/gtqziiqpzl.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.pycfn.com/Article/details/gtzksdmars.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xuanzx.com/Article/details/gtepjaipyp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.andypj.xyz/Article/details/gtrhnoonlc.html

[L04] 设置超时
来源：http://dali.shuidangran.top/Article/details/gtidzhoxij.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqvwyngse.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ydzc1.top/Article/details/gteheazxyv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gzhubu.top/Article/details/gtuydceskh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.c1oappe.top/Article/details/gtikfwsbqe.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yueranfly.top/Article/details/gtevjxarbd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jianghu66.top/Article/details/gtcpntucdr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yonumen.top/Article/details/gtjgtdzhse.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfwqeviru.html

[L05] 上传文件（multipart）
来源：http://dali.kuanghao11.cn/Article/details/gtvuijvvym.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.havefunace.top/Article/details/gtcpgxdgjr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zdqjudy.top/Article/details/gtakmlfhqm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.meibo888.top/Article/details/gtrjwuxxfh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gtgptzuyah.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gaohongyu789.top/Article/details/gtcidpjisk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnjorfsvk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shzxlz.cn/Article/details/gtjvaonajv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yuanzhike.top/Article/details/gttmdabxrm.html

[L06] 解析响应为 JSON
来源：http://dali.zhiwuduotai.top/Article/details/gttvkgxtrf.html

Py:   resp.json()
来源：http://dali.jinqigufen.top/Article/details/gtdrhytnut.html

PHP:  json_decode($body, true);
来源：http://dali.aibaodan.cn/Article/details/gtkvdugzyy.html

JS:   await resp.json()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnzhobxbe.html

TS:   await resp.json()
来源：http://dali.gogol.net.cn/Article/details/gtyjlmgntx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.0kj1m.cn/Article/details/gtqatxhrzj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hammf.cn/Article/details/gtqcqibrhd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xylfe.cn/Article/details/gtvlagpick.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shanyushiyangtech.top/Article/details/gtuoyayyoy.html

[L07] 处理 HTTP 状态码
来源：http://dali.daxiang520.top/Article/details/gtvcgjftfm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cqqwz.cn/Article/details/gtxnkvqeuv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xylfe.cn/Article/details/gtjwtyjbkn.html

JS:   resp.ok;  resp.status
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzubeqtpy.html

TS:   resp.ok;  resp.status
来源：http://dali.fzhhl.top/Article/details/gtvfofjfaf.html

Java: resp.statusCode()
来源：http://dali.hywenlv.cn/Article/details/gtkwrzfpkg.html

Go:   resp.StatusCode
来源：http://dali.xinyue.icu/Article/details/gtqttnhunu.html

Ruby: resp.code.to_i
来源：http://dali.sweek.top/Article/details/gtyyltuznx.html

C#:   (int)resp.StatusCode
来源：http://dali.xuetiantiany.cn/Article/details/gtwawwenjt.html

[L08] 并发请求多个地址
来源：http://dali.snrcjt.cn/Article/details/gtxfbbohtw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nanxinkj.top/Article/details/gtryluyinu.html

PHP:  curl_multi_init() 系列
来源：http://dali.pycfn.com/Article/details/gtbrnonvgp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.svipenyu.cn/Article/details/gtjvtjbffa.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aibaodan.cn/Article/details/gtumuvsodh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yuxming.cn/Article/details/gtgfluafbi.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.birdmap.top/Article/details/gtlxigotmi.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cdnleiting.top/Article/details/gtcbqtqaxz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.haohaochexian.top/Article/details/gtylpthowm.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtmogxgldm.html

M. 命令行 / 进程 / 环境
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxxgjmxvv.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtxqrcnlls.html

[M01] 读取命令行参数
来源：http://dali.sxryk.cn/Article/details/gtsezuokzv.html

Py:   sys.argv[1:]
来源：http://dali.aizwys.cn/Article/details/gtylyzdmbm.html

PHP:  $argv;  $argc;
来源：http://dali.hammf.cn/Article/details/gtobidipym.html

JS:   process.argv.slice(2)
来源：http://dali.yuanzhike.top/Article/details/gtmnzntcwj.html

TS:   process.argv.slice(2)
来源：http://dali.xziqi.cn/Article/details/gtirhdqzlb.html

Java: args 数组（main 方法参数）
来源：http://dali.iojbl.cn/Article/details/gtnanulvvn.html

Go:   os.Args[1:]
来源：http://dali.mhx1999.top/Article/details/gtxzksdmwl.html

Ruby: ARGV
来源：http://dali.mhx1999.top/Article/details/gtqoclmrra.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jlsjyb.cn/Article/details/gthiarshyw.html

[M02] 读取环境变量
来源：http://dali.jinghuilouyu.cn/Article/details/gttcdyttlw.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gtigjwvijn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tian-w.cn/Article/details/gtmxljqagg.html

JS:   process.env.HOME
来源：http://dali.jianghu66.top/Article/details/gtstziyvsg.html

TS:   process.env.HOME
来源：http://dali.yj20258.top/Article/details/gtylxuddcv.html

Java: System.getenv("HOME")
来源：http://dali.xziqi.cn/Article/details/gtmrfpipmd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yvedp.cn/Article/details/gtvojnerya.html

Ruby: ENV["HOME"]
来源：http://dali.sxryk.cn/Article/details/gtphhzszpw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tanke756.top/Article/details/gtpssiupli.html

[M03] 执行外部命令
来源：http://dali.yangfankeji.com/Article/details/gtshrzhvae.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.haohaochexian.top/Article/details/gtricudhfe.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.kuanghao11.cn/Article/details/gtufvptmtv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.smart0.xyz/Article/details/gtwmjbusis.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.c1oappe.top/Article/details/gtoxyanoqg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.quarkkingdee.top/Article/details/gtcnztsupb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tian-w.cn/Article/details/gtohzyqlhu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrhblvowc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cheryme.top/Article/details/gtthxnkpbf.html

[M04] 获取当前工作目录
来源：http://dali.wangdashe.top/Article/details/gthtfskmxr.html

Py:   os.getcwd()
来源：http://dali.yj20258888.top/Article/details/gtvgjfrzsd.html

PHP:  getcwd();
来源：http://dali.ppjwa.cn/Article/details/gtbundajus.html

JS:   process.cwd()
来源：http://dali.zhongyouzk.top/Article/details/gtyadmxktn.html

TS:   process.cwd()
来源：http://dali.quarkkingdee.top/Article/details/gtpcheunys.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xylfe.cn/Article/details/gtuciqschu.html

Go:   os.Getwd()
来源：http://dali.guannengcc.top/Article/details/gtrmymhbtf.html

Ruby: Dir.pwd
来源：http://dali.wangshuangyany.cn/Article/details/gtipunlvqd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hysaishi.cn/Article/details/gtwagsgbbn.html

[M05] 设置退出码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvfehgnwp.html

Py:   sys.exit(1)
来源：http://dali.nwbrower.top/Article/details/gtyzaclaqx.html

PHP:  exit(1);
来源：http://dali.meibo888.top/Article/details/gtqvouhbfn.html

JS:   process.exit(1)
来源：http://dali.redwolf501.top/Article/details/gtpjutwfgi.html

TS:   process.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtxikafexc.html

Java: System.exit(1)
来源：http://dali.tian-w.cn/Article/details/gtkalwwdda.html

Go:   os.Exit(1)
来源：http://dali.yj20258888.top/Article/details/gtdtllirzq.html

Ruby: exit 1
来源：http://dali.yj20258.top/Article/details/gtszujhrey.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj20258.top/Article/details/gtgblafmgf.html

[M06] 向标准错误输出
来源：http://dali.fengsongda.top/Article/details/gtrbjtgpiw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.fengsongda.top/Article/details/gtdgchtgkc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yj202588.top/Article/details/gttokybhtf.html

JS:   console.error("err")
来源：http://dali.pengpengdd.cyou/Article/details/gtihregrqw.html

TS:   console.error("err")
来源：http://dali.cashguo.top/Article/details/gthyuvqorv.html

Java: System.err.println("err")
来源：http://dali.gzhubu.top/Article/details/gtmaovoafs.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrzgmwseq.html

Ruby: warn "err"
来源：http://dali.jiagoushi.top/Article/details/gtmfjagldb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sxryk.cn/Article/details/gtpumslvcm.html

[M07] 判断是否为主入口
来源：http://dali.yuxming.cn/Article/details/gtaxlkjcbm.html

Py:   if __name__ == "__main__":
来源：http://dali.gotoacloud.top/Article/details/gturauzbyz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhixingplan.top/Article/details/gteywunrea.html

JS:   require.main === module
来源：http://dali.shzxlz.cn/Article/details/gtfhwtkbal.html

TS:   require.main === module
来源：http://dali.nwbrower.top/Article/details/gtxxugthno.html

Java: public static void main(String[] args)
来源：http://dali.zhongyouzk.top/Article/details/gtfzkkjxeo.html

Go:   func main()
来源：http://dali.gaohongyu789.top/Article/details/gttryfznjw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.birdmap.top/Article/details/gtjfbjkdru.html

C#:   static void Main(string[] args)
来源：http://dali.feifeiyinyue.top/Article/details/gtmyhozlra.html

[M08] 获取系统与运行时信息
来源：http://dali.jlsjyb.cn/Article/details/gtaeqzqeeb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhiwuduotai.top/Article/details/gtlezpnsbb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.svipenyu.cn/Article/details/gtvhnsszyj.html

JS:   process.platform;  process.version
来源：http://dali.yj202588.top/Article/details/gtjfdvjjsr.html

TS:   process.platform;  process.version
来源：http://dali.ehwqpu.com/Article/details/gtivzjlbeh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jqgfzy.top/Article/details/gthvaxojkx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sysykeji.top/Article/details/gtwjfyylea.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gogol.net.cn/Article/details/gtgybjanvg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gzhubu.top/Article/details/gtabspaqgq.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gttujcrtut.html

N. 数据结构与算法
来源：http://dali.jlsjyb.cn/Article/details/gtmocpvyno.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtvvzkianq.html

[N01] 二分查找（有序数组）
来源：http://dali.jinghuilouyu.cn/Article/details/gtgxxbqvxa.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yonumen.top/Article/details/gtiacimfdh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xylfe.cn/Article/details/gtayrlaujy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258888.top/Article/details/gtdqjweebg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hammf.cn/Article/details/gtlxalfiif.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtprimqvhf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtsfrcfuts.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hongshengwenyu.top/Article/details/gtdanysxju.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtudxvsjxl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jianghu66.top/Article/details/gttcsdfdhw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhoulong.xyz/Article/details/gtswhgajvs.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.gzhubu.top/Article/details/gtjtgrcrcp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.bjfxy.top/Article/details/gtlymeiefk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxuanxn.top/Article/details/gtasnhrcxn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yuxming.cn/Article/details/gteuaumocb.html

Go:   slices.Sort(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvxmjltgv.html

Ruby: arr.sort
来源：http://dali.sweek.top/Article/details/gtfviavgbc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.fzhhl.top/Article/details/gtbgdivebb.html

[N03] 快速排序（分治示例）
来源：http://dali.wangshuangyany.cn/Article/details/gtwunudvgs.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.fengsongda.top/Article/details/gtxlhngmtq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yongpay.top/Article/details/gtcsamtxph.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gtavnhkxvn.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.iojbl.cn/Article/details/gtynzywflp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.c1oappe.top/Article/details/gtiqiuampj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jianghu66.top/Article/details/gtuzhqjdgg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yueranfly.top/Article/details/gtsrdzrddc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhixingplan.top/Article/details/gthijbwivf.html

[N04] 斐波那契数列
来源：http://dali.sysykeji.top/Article/details/gtptjveezi.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtmqgchqxk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shuidangran.top/Article/details/gtzgodiema.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtnbkwdclo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gtlslyxltg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.tianlin.xyz/Article/details/gteshrnzti.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yueranfly.top/Article/details/gtndyyjzbl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yonumen.top/Article/details/gtldqqpxhh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gtfkydouuy.html

[N05] 最大公约数
来源：http://dali.feifeiyinyue.top/Article/details/gtdlncsikn.html

Py:   math.gcd(a, b)
来源：http://dali.jlsjyb.cn/Article/details/gtfewrvvdr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.havefunace.top/Article/details/gtmremwkof.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sxryk.cn/Article/details/gtsgamklou.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj20258.top/Article/details/gtqtwjdkep.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zdqjudy.top/Article/details/gtxewccqno.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xylfe.cn/Article/details/gtobblrskc.html

Ruby: a.gcd(b)
来源：http://dali.cucudq.cn/Article/details/gtvsoqdciy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.birdmap.top/Article/details/gtolfsayxu.html

[N06] 判断回文字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtojwzhobr.html

Py:   s == s[::-1]
来源：http://dali.yj20258.top/Article/details/gtbfnhthgs.html

PHP:  $s === strrev($s);
来源：http://dali.wangshuangyany.cn/Article/details/gthgxltqen.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gttnuvtyxu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gtrxzhpscp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yangfankeji.com/Article/details/gthymdlvsd.html

Go:   // 双指针从两端比较
来源：http://dali.zhongyouzk.top/Article/details/gtlzmdpicr.html

Ruby: s == s.reverse
来源：http://dali.pycfn.com/Article/details/gtdgtzvtrv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.c1oappe.top/Article/details/gtvwhyxuou.html

[N07] 两数之和（返回下标）
来源：http://dali.tianlin.xyz/Article/details/gteaaerszg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cdnleiting.top/Article/details/gturocrjiy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.andypj.xyz/Article/details/gtrulkuhdb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtespbqcsk.html

TS:   // 手写 Map<string, number>
来源：http://dali.yueranfly.top/Article/details/gtczbwhtjr.html

Java: // 手写 HashMap
来源：http://dali.feifeiyinyue.top/Article/details/gtefsixifq.html

Go:   // 手写 map[int]int
来源：http://dali.xuanzx.com/Article/details/gtqsvsabrb.html

Ruby: // 手写 Hash
来源：http://dali.sxryk.cn/Article/details/gtxitjxjxi.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zycfv.cn/Article/details/gtcqyeakgn.html

[N08] 生成全排列
来源：http://dali.snrcjt.cn/Article/details/gtlsmqsurl.html

Py:   itertools.permutations(arr)
来源：http://dali.andypj.xyz/Article/details/gtaygvhndz.html

PHP:  // 手写递归交换
来源：http://dali.zhixingplan.top/Article/details/gtbkoesqyi.html

JS:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gttiabbqdv.html

TS:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gtyucytwiv.html

Java: // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gtcfakpipa.html

Go:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gtsoaotdwj.html

Ruby: arr.permutation.to_a
来源：http://dali.tian-w.cn/Article/details/gtwumvdwrx.html

C#:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtwlozictu.html

[N09] 栈与队列
来源：http://dali.zhengqikj.top/Article/details/gtokgzmukd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hywenlv.cn/Article/details/gtmvyycuhv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinqigfzy.top/Article/details/gtpsjgfdhq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xziqi.cn/Article/details/gtcwvhgwwo.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shangyingyoupin.top/Article/details/gtkhnphdpw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.316326.xyz/Article/details/gtyzmhkrcw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jiagoushi.top/Article/details/gtamsqexui.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gtjmkjtefd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gaohongyu789.top/Article/details/gtugzdmaei.html

[N10] 链表节点定义
来源：http://dali.jiagoushi.top/Article/details/gtvfgiifuv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.chenjidiqi.icu/Article/details/gtdyryuszf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.nanxuanxn.top/Article/details/gtqchydtwv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtchlejzpv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gaohongyu789.top/Article/details/gtkxrwzhth.html

Java: class Node { int v; Node next; }
来源：http://dali.dianchejie.cn/Article/details/gtyqaycggu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.c1oappe.top/Article/details/gtjsrcnctf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.guowangkeji.top/Article/details/gtigsznbfd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jyoumei.cn/Article/details/gtlndqqxez.html

[N11] 二叉树中序遍历
来源：http://dali.nanxinkj.top/Article/details/gttbdevqos.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hongshengwenyu.top/Article/details/gtgiqjswzi.html

PHP:  // 手写递归函数
来源：http://dali.guowangkeji.top/Article/details/gthuzqcujq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.feifeiyinyue.top/Article/details/gtqigrkxbu.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.dianchejie.cn/Article/details/gtyknxgkvg.html

Java: // 手写递归
来源：http://dali.tianlin.xyz/Article/details/gtvelbzwxt.html

Go:   // 手写递归
来源：http://dali.sweek.top/Article/details/gtundinilj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.svipenyu.cn/Article/details/gtlvuzohui.html

C#:   // 手写递归
来源：http://dali.316326.xyz/Article/details/gtnosphpju.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.wangshuangyany.cn/Article/details/gtwiupcvnd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.nanxuanxn.top/Article/details/gtdbmhvkxx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.birdmap.top/Article/details/gtgzsfqdbg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.pycfn.com/Article/details/gtidwqtsli.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ehwqpu.com/Article/details/gtrkysrwdm.html


<!-- 参考信息 -->