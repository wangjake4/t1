代发 wailian999

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yongpay.top/Article/details/gtwyebentn.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nwbrower.top/Article/details/gtviohzozb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.snrcjt.cn/Article/details/gtlpthahbh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nwbrower.top/Article/details/gtwoihtgra.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sweek.top/Article/details/gtvbyvbitk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ivvv.top/Article/details/gtwfghoaxc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.guowangkeji.top/Article/details/gtqunmksuu.html

[K05] 深拷贝对象
来源：http://dali.hongshengwenyu.top/Article/details/gtcvskxweu.html

Py:   copy.deepcopy(obj)
来源：http://dali.gaohongyu789.top/Article/details/gttitoivke.html

PHP:  unserialize(serialize($obj));
来源：http://dali.daria6918.cn/Article/details/gtmegvgfci.html

JS:   structuredClone(obj)
来源：http://dali.jqgfzy.top/Article/details/gthcdvtwvu.html

TS:   structuredClone(obj)
来源：http://dali.haohaochexian.top/Article/details/gtabxyunwg.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xinyue.icu/Article/details/gtdhfocbxb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xuanzx.com/Article/details/gtsrbdmvrm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yuanzhike.top/Article/details/gteqfnhjfv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.haohaochexian.top/Article/details/gtahewxbef.html

[K06] 解析 URL 查询串
来源：http://dali.yuanzhike.top/Article/details/gtcgqfvven.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hnqzz.top/Article/details/gtwrmrnviy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.aibaodan.cn/Article/details/gtupidcxli.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jiagoushi.top/Article/details/gtgibnqlss.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sufxvd.cn/Article/details/gtjvikkkss.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ppjwa.cn/Article/details/gtalbtxbti.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gtrnqiidta.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xuetiantiany.cn/Article/details/gtdfywbvku.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gthnjpyisv.html

[K07] 进制转换
来源：http://dali.fzhhl.top/Article/details/gtsgyszovp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.pycfn.com/Article/details/gteayjuzxc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.wangshuangyany.cn/Article/details/gteypvylon.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtzvryvweg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtckpqltcy.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gtimbqxtax.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdtfspmtn.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.birdmap.top/Article/details/gtagepirjy.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtcnrjjqlb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.c1oappe.top/Article/details/gtosktcjeb.html

Py:   pickle.dumps(obj)
来源：http://dali.ybcxt.top/Article/details/gtydmlcesc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.guowangkeji.top/Article/details/gtthzjgxfs.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.chenlongwang.top/Article/details/gtxqwjyyuu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.dashuyun.cn/Article/details/gthaqvkmlo.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cdnleiting.top/Article/details/gtqrnmubnj.html

Go:   encoding/gob
来源：http://dali.gzhubu.top/Article/details/gtojdeghrg.html

Ruby: Marshal.dump(obj)
来源：http://dali.smart0.xyz/Article/details/gtercprnxh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.fzhhl.top/Article/details/gttcphwowh.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtuawyosog.html

L. 网络请求
来源：http://dali.hnxiangtu.top/Article/details/gtjraeptpn.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtccuworup.html

[L01] 发送 GET 请求
来源：http://dali.zhiwuduotai.top/Article/details/gtntrvgysn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlrnnlcmm.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhaomingkeji.xyz/Article/details/gtreckvqcd.html

JS:   await fetch(url)
来源：http://dali.sweek.top/Article/details/gtgtofnpda.html

TS:   await fetch(url)
来源：http://dali.bjfxy.top/Article/details/gtpcoajnzx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zdqjudy.top/Article/details/gtahyjdntw.html

Go:   resp, err := http.Get(url)
来源：http://dali.fzhhl.top/Article/details/gtsgdcqdyz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmjmiangk.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nanxinkj.top/Article/details/gtxjrxtabw.html

[L02] 发送 POST JSON
来源：http://dali.iojbl.cn/Article/details/gtaupqgcyz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cucudq.cn/Article/details/gtusxcbvuh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.haohaochexian.top/Article/details/gtpkwccttj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cucudq.cn/Article/details/gtxmbfsyrn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shzxlz.cn/Article/details/gtfwegnolo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiirutrzr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhoulong.xyz/Article/details/gtyzaukxrt.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtitkxtovf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.vqdsnc.cn/Article/details/gtmgywinng.html

[L03] 设置自定义请求头
来源：http://dali.cdnleiting.top/Article/details/gtuiuuhpfd.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sweek.top/Article/details/gtxdagxqaz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jiagoushi.top/Article/details/gtrazavljr.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hysaishi.cn/Article/details/gtdhtggksg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuetiantiany.cn/Article/details/gtmpjprnwh.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jianghu66.top/Article/details/gtxutbzsra.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shangyingyoupin.top/Article/details/gtfldshmzf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj20258.top/Article/details/gtuwwgkwji.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.redwolf501.top/Article/details/gtcbgzzznx.html

[L04] 设置超时
来源：http://dali.hysaishi.cn/Article/details/gtelojqrsq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ivvv.top/Article/details/gttbcfwgla.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.wangdashe.top/Article/details/gtylknyxbt.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.kuanghao11.cn/Article/details/gtopffcflq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.iojbl.cn/Article/details/gtjiikdpbf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlgvxjltz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ivvv.top/Article/details/gtdyvsynxh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhiwuduotai.top/Article/details/gtlgiaibxx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.snrcjt.cn/Article/details/gtcyfidcxi.html

[L05] 上传文件（multipart）
来源：http://dali.hysaishi.cn/Article/details/gtikxvdwqn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sxryk.cn/Article/details/gteuoegvug.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.haohaochexian.top/Article/details/gthsreqmfs.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yonumen.top/Article/details/gtrfsdekdk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhixingplan.top/Article/details/gtvtwdttwf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ybcxt.top/Article/details/gtmbekkvwm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yvedp.cn/Article/details/gtpszdqblj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hnqzz.top/Article/details/gtinworaql.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cheryme.top/Article/details/gtfkuttoop.html

[L06] 解析响应为 JSON
来源：http://dali.daxiang520.top/Article/details/gtnlbximet.html

Py:   resp.json()
来源：http://dali.hongshengwenyu.top/Article/details/gtdohuwgly.html

PHP:  json_decode($body, true);
来源：http://dali.ppjwa.cn/Article/details/gtbdwvmbfk.html

JS:   await resp.json()
来源：http://dali.guowangkeji.top/Article/details/gtjbxzonkh.html

TS:   await resp.json()
来源：http://dali.jqgfzy.top/Article/details/gtrblxxnbu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hfpthk.cn/Article/details/gtfxqssjmr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.aizwys.cn/Article/details/gtmydjhpad.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ivvv.top/Article/details/gtdesxroxp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shzxlz.cn/Article/details/gtsjvefcnj.html

[L07] 处理 HTTP 状态码
来源：http://dali.smart0.xyz/Article/details/gtiumbeepd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jyoumei.cn/Article/details/gthbuwpobo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.havefunace.top/Article/details/gtxyhgfuzd.html

JS:   resp.ok;  resp.status
来源：http://dali.meibo888.top/Article/details/gtbzxxlwxj.html

TS:   resp.ok;  resp.status
来源：http://dali.zhongyouzk.top/Article/details/gtbjcrtegs.html

Java: resp.statusCode()
来源：http://dali.gogol.net.cn/Article/details/gtipsmdllc.html

Go:   resp.StatusCode
来源：http://dali.jiagoushi.top/Article/details/gtutqmdmck.html

Ruby: resp.code.to_i
来源：http://dali.tanke756.top/Article/details/gtezrmwfdu.html

C#:   (int)resp.StatusCode
来源：http://dali.shzxlz.cn/Article/details/gtvbegojgt.html

[L08] 并发请求多个地址
来源：http://dali.redwolf501.top/Article/details/gtjtogftvr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nanxinkj.top/Article/details/gtiielgdih.html

PHP:  curl_multi_init() 系列
来源：http://dali.wangshuangyany.cn/Article/details/gtsldlmxrq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.andypj.xyz/Article/details/gtoflibpyn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gzhubu.top/Article/details/gtlxfcpbsg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xziqi.cn/Article/details/gteiialyqp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.feifeiyinyue.top/Article/details/gtecjnzvws.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.nanxinkj.top/Article/details/gtlgsiwrds.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ppjwa.cn/Article/details/gtqqvonweh.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtmnhircjh.html

M. 命令行 / 进程 / 环境
来源：http://dali.jlsjyb.cn/Article/details/gtwumkkpkd.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtftzvdrqd.html

[M01] 读取命令行参数
来源：http://dali.yuanzhike.top/Article/details/gtzdqosftp.html

Py:   sys.argv[1:]
来源：http://dali.cucudq.cn/Article/details/gtlgtkgvie.html

PHP:  $argv;  $argc;
来源：http://dali.0kj1m.cn/Article/details/gthjjeiqwr.html

JS:   process.argv.slice(2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbignorjs.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gtcihotfwc.html

Java: args 数组（main 方法参数）
来源：http://dali.hongshengwenyu.top/Article/details/gtyouruafi.html

Go:   os.Args[1:]
来源：http://dali.hammf.cn/Article/details/gtpjpeajnx.html

Ruby: ARGV
来源：http://dali.yangfankeji.com/Article/details/gtmzyhojvd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xylfe.cn/Article/details/gtddhidqom.html

[M02] 读取环境变量
来源：http://dali.xuetiantiany.cn/Article/details/gtiiiygsku.html

Py:   os.environ.get("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbhabbwhe.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yangfankeji.com/Article/details/gtxfwnyjzk.html

JS:   process.env.HOME
来源：http://dali.xuanzx.com/Article/details/gtosyscgmh.html

TS:   process.env.HOME
来源：http://dali.hnqzz.top/Article/details/gtelvvjvnr.html

Java: System.getenv("HOME")
来源：http://dali.pycfn.com/Article/details/gtbtgovdxn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gtuarlwhco.html

Ruby: ENV["HOME"]
来源：http://dali.cqqwz.cn/Article/details/gtxxuqzfix.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258888.top/Article/details/gtlstovtvy.html

[M03] 执行外部命令
来源：http://dali.shangyingyoupin.top/Article/details/gtqjfctcqv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jqgfzy.top/Article/details/gthvjoteis.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hongshengwenyu.top/Article/details/gtptcfyeun.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxinkj.top/Article/details/gthtijbfkg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.c1oappe.top/Article/details/gtcoblwcms.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhongyouzk.top/Article/details/gtdvthptfz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hammf.cn/Article/details/gtahtlewvo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hammf.cn/Article/details/gtnjmvzhhv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sysykeji.top/Article/details/gtdsojkdmk.html

[M04] 获取当前工作目录
来源：http://dali.316326.xyz/Article/details/gtalkvvwox.html

Py:   os.getcwd()
来源：http://dali.mhx1999.top/Article/details/gtotnjrwrv.html

PHP:  getcwd();
来源：http://dali.redwolf501.top/Article/details/gthmyradid.html

JS:   process.cwd()
来源：http://dali.zdqjudy.top/Article/details/gtscwccdqg.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gtegmlrnsw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.birdmap.top/Article/details/gtdbiiuuys.html

Go:   os.Getwd()
来源：http://dali.havefunace.top/Article/details/gtbttaeboz.html

Ruby: Dir.pwd
来源：http://dali.xziqi.cn/Article/details/gttcxolyee.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xuanzx.com/Article/details/gtchuuxapw.html

[M05] 设置退出码
来源：http://dali.jianghu66.top/Article/details/gtnbercjmw.html

Py:   sys.exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gtwljypyok.html

PHP:  exit(1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfyieyxtp.html

JS:   process.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtghsbeips.html

TS:   process.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtqxcjqizb.html

Java: System.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gtejkgkcim.html

Go:   os.Exit(1)
来源：http://dali.mhx1999.top/Article/details/gtbdlbuutv.html

Ruby: exit 1
来源：http://dali.birdmap.top/Article/details/gtoyojmipx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gotoacloud.top/Article/details/gtuvhvokae.html

[M06] 向标准错误输出
来源：http://dali.redwolf501.top/Article/details/gtspngsupg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.tianlin.xyz/Article/details/gtbebfspvw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.quarkkingdee.top/Article/details/gteivqnlzn.html

JS:   console.error("err")
来源：http://dali.dashuyun.cn/Article/details/gtcgdifgss.html

TS:   console.error("err")
来源：http://dali.yj20258.top/Article/details/gtqtnifevb.html

Java: System.err.println("err")
来源：http://dali.zhengqikj.top/Article/details/gtbihlmzxq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.snrcjt.cn/Article/details/gtxagqxhak.html

Ruby: warn "err"
来源：http://dali.mhx1999.top/Article/details/gtwuiwingi.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.9152youxi.cn/Article/details/gtxklrojlw.html

[M07] 判断是否为主入口
来源：http://dali.jiagoushi.top/Article/details/gtcihlxyhq.html

Py:   if __name__ == "__main__":
来源：http://dali.jyoumei.cn/Article/details/gtlafakrln.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.havefunace.top/Article/details/gtihmshsuw.html

JS:   require.main === module
来源：http://dali.yvedp.cn/Article/details/gtrbidpmgx.html

TS:   require.main === module
来源：http://dali.yj20258.top/Article/details/gtbxjezcxa.html

Java: public static void main(String[] args)
来源：http://dali.chenlongwang.top/Article/details/gtaweeaidn.html

Go:   func main()
来源：http://dali.jinqigufen.top/Article/details/gtxfvznukk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.c1oappe.top/Article/details/gtzuxiwjyk.html

C#:   static void Main(string[] args)
来源：http://dali.iojbl.cn/Article/details/gtvywylhff.html

[M08] 获取系统与运行时信息
来源：http://dali.jinqigfzy.top/Article/details/gtblqeaoib.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gogol.net.cn/Article/details/gtwxthvgbx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yj20258.top/Article/details/gtwnyllwvz.html

JS:   process.platform;  process.version
来源：http://dali.vqdsnc.cn/Article/details/gtatnoouyu.html

TS:   process.platform;  process.version
来源：http://dali.ehwqpu.com/Article/details/gtwowatxus.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnxiangtu.top/Article/details/gtyfdtyovi.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jianghu66.top/Article/details/gtohewwyza.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sxryk.cn/Article/details/gtqxbumega.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hfpthk.cn/Article/details/gtlagenlmt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtanvrqmaj.html

N. 数据结构与算法
来源：http://dali.9152youxi.cn/Article/details/gtchwaeyay.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtnxorepcv.html

[N01] 二分查找（有序数组）
来源：http://dali.hysaishi.cn/Article/details/gtdcltxpkg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtylthbemd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjvrteclg.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.quarkkingdee.top/Article/details/gtlxpgnrcu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fzhhl.top/Article/details/gtgutotjof.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtzoovbtrv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ydzc1.top/Article/details/gtjxixpwga.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.chenlongwang.top/Article/details/gtkpjwzssj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gtryvwlppo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkrdhtdit.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sufxvd.cn/Article/details/gtikuttcnp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jqgfzy.top/Article/details/gttsgvdltj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.316326.xyz/Article/details/gtakdrgnyp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jyoumei.cn/Article/details/gtmrtoesed.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinqigufen.top/Article/details/gtkouypvml.html

Go:   slices.Sort(arr)
来源：http://dali.tanke756.top/Article/details/gtansuawkw.html

Ruby: arr.sort
来源：http://dali.ehwqpu.com/Article/details/gtpujfflux.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.chenjidiqi.icu/Article/details/gtfifavunw.html

[N03] 快速排序（分治示例）
来源：http://dali.shanyushiyangtech.top/Article/details/gtbxxfvdnj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.dianchejie.cn/Article/details/gtkhvaixqk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhixingplan.top/Article/details/gtomjuepqm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xylfe.cn/Article/details/gtpnapohyc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.mhx1999.top/Article/details/gtzobvdvkj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jianghu66.top/Article/details/gtalpevhbw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cashguo.top/Article/details/gtbygxtxiy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.dashuyun.cn/Article/details/gtukdirqym.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zycfv.cn/Article/details/gtzsibgotw.html

[N04] 斐波那契数列
来源：http://dali.chenlongwang.top/Article/details/gtxjsmdxko.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yanxiufei.cn/Article/details/gtwqprlmjh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.birdmap.top/Article/details/gtedwzjmsn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daria6918.cn/Article/details/gtckcvxppk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zycfv.cn/Article/details/gtcfroxvar.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hnqzz.top/Article/details/gtvfdgmrhz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yanxiufei.cn/Article/details/gtgzdoqpny.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.smart0.xyz/Article/details/gtgajrljrb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhongyouzk.top/Article/details/gtcznokldt.html

[N05] 最大公约数
来源：http://dali.hnxiangtu.top/Article/details/gtsidjpjha.html

Py:   math.gcd(a, b)
来源：http://dali.c1oappe.top/Article/details/gtfcuxjwwn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ydzc1.top/Article/details/gthrbkjilc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cdnleiting.top/Article/details/gtnodaojit.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.redwolf501.top/Article/details/gtlpsvrtak.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hywenlv.cn/Article/details/gthpscxbtq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shuidangran.top/Article/details/gtxuazeznx.html

Ruby: a.gcd(b)
来源：http://dali.quarkkingdee.top/Article/details/gtrdwlskuu.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xuetiantiany.cn/Article/details/gtovqlkwai.html

[N06] 判断回文字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtnwhegxrs.html

Py:   s == s[::-1]
来源：http://dali.yonumen.top/Article/details/gtkspzilbw.html

PHP:  $s === strrev($s);
来源：http://dali.ehwqpu.com/Article/details/gtxoymoqmw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gtdfbaqnye.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gtnctpjtcp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yanxiufei.cn/Article/details/gtassiuvau.html

Go:   // 双指针从两端比较
来源：http://dali.shzxlz.cn/Article/details/gtcmqospsx.html

Ruby: s == s.reverse
来源：http://dali.pycfn.com/Article/details/gtdvwhdgvw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.kuanghao11.cn/Article/details/gtquvrwjfr.html

[N07] 两数之和（返回下标）
来源：http://dali.shanyushiyangkeji.top/Article/details/gthksimraq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhongyouzk.top/Article/details/gtqepwvgyn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinqigufen.top/Article/details/gtwxplcojz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jqgfzy.top/Article/details/gtyaghykkm.html

TS:   // 手写 Map<string, number>
来源：http://dali.ehwqpu.com/Article/details/gtedrdwtkz.html

Java: // 手写 HashMap
来源：http://dali.yonumen.top/Article/details/gtgtwrttae.html

Go:   // 手写 map[int]int
来源：http://dali.dianchejie.cn/Article/details/gtgqzoiwgh.html

Ruby: // 手写 Hash
来源：http://dali.sufxvd.cn/Article/details/gtlxjmmhyu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhoulong.xyz/Article/details/gtuhbmxqnv.html

[N08] 生成全排列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkccwtihb.html

Py:   itertools.permutations(arr)
来源：http://dali.mhx1999.top/Article/details/gtkzotwxzy.html

PHP:  // 手写递归交换
来源：http://dali.nanxuanxn.top/Article/details/gtqvgictaf.html

JS:   // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gtyvseduyr.html

TS:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gtckloeijv.html

Java: // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gtevohrtbg.html

Go:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gtcycvwery.html

Ruby: arr.permutation.to_a
来源：http://dali.guannengcc.top/Article/details/gtgxbfsemw.html

C#:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gtadjuqbhh.html

[N09] 栈与队列
来源：http://dali.cqqwz.cn/Article/details/gtqcsijgut.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtxabuneqj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenlongwang.top/Article/details/gtprqrpmxd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yongpay.top/Article/details/gtgbsbzckq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cashguo.top/Article/details/gtmyrijquy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.guannengcc.top/Article/details/gtwmfxkoid.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.andypj.xyz/Article/details/gtroomjynd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yonumen.top/Article/details/gtsrzvjvyc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gzhubu.top/Article/details/gtsyfsphvt.html

[N10] 链表节点定义
来源：http://dali.xuanzx.com/Article/details/gtqsoibhze.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.bjfxy.top/Article/details/gtklclcrea.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gotoacloud.top/Article/details/gtfuywbzpu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.tian-w.cn/Article/details/gttgfrelfo.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xziqi.cn/Article/details/gtoodoupuf.html

Java: class Node { int v; Node next; }
来源：http://dali.shzxlz.cn/Article/details/gtjlzmjqad.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.nanxuanxn.top/Article/details/gtbiqhmkdp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xuanzx.com/Article/details/gtwbwuujoa.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jyoumei.cn/Article/details/gtfoixtzdh.html

[N11] 二叉树中序遍历
来源：http://dali.daria6918.cn/Article/details/gtlxeadoxz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgmiegynz.html

PHP:  // 手写递归函数
来源：http://dali.gotoacloud.top/Article/details/gtnjqmynka.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.mhx1999.top/Article/details/gtxsqgwpuk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.svipenyu.cn/Article/details/gtqjqjzwnt.html

Java: // 手写递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxwfbaavj.html

Go:   // 手写递归
来源：http://dali.hnqzz.top/Article/details/gtuerfypuo.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shanyushiyangtech.top/Article/details/gtfflupwpv.html

C#:   // 手写递归
来源：http://dali.yongpay.top/Article/details/gtjfufjbrt.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.aizwys.cn/Article/details/gtnoprudvj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yvedp.cn/Article/details/gtcmyanevy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.guowangkeji.top/Article/details/gtunpoqcke.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.smart0.xyz/Article/details/gtrormglod.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yongpay.top/Article/details/gtnxckxsnf.html


<!-- 参考信息 -->