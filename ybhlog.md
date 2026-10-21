代发 wailian999

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yvedp.cn/Article/details/gtlpdzkgqg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gotoacloud.top/Article/details/gtkxvfejbs.html

[K04] 读取 JSON 文件
来源：http://dali.xuanzx.com/Article/details/gtopjycqxw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.havefunace.top/Article/details/gtkxgemgjn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.0kj1m.cn/Article/details/gtkbuwrbby.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sufxvd.cn/Article/details/gtpveubwfo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.svipenyu.cn/Article/details/gtkhsnvrgu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.havefunace.top/Article/details/gtjndvauym.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cdnleiting.top/Article/details/gtqclwogky.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yuxming.cn/Article/details/gtquzleghk.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.guannengcc.top/Article/details/gtnhurujep.html

[K05] 深拷贝对象
来源：http://dali.yj20258.top/Article/details/gtcpwrzdxr.html

Py:   copy.deepcopy(obj)
来源：http://dali.zdqjudy.top/Article/details/gtsprnxnxt.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sweek.top/Article/details/gtngjvwfdg.html

JS:   structuredClone(obj)
来源：http://dali.aizwys.cn/Article/details/gtvybjjdhz.html

TS:   structuredClone(obj)
来源：http://dali.aizwys.cn/Article/details/gtdojufwia.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shzxlz.cn/Article/details/gtseclfqcc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shuidangran.top/Article/details/gtyqyzfbcu.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.meibo888.top/Article/details/gtfsqxkfxz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.wangshuangyany.cn/Article/details/gtfuucgeoc.html

[K06] 解析 URL 查询串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiubfdxuq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hnqzz.top/Article/details/gtlsledoub.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yangfankeji.com/Article/details/gtxdbtrhax.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtugpdjfjq.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guowangkeji.top/Article/details/gtsuysfnkm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yuxming.cn/Article/details/gtaxckotby.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hfpthk.cn/Article/details/gtmrjhzneo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhongyouzk.top/Article/details/gtkzncjorn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.birdmap.top/Article/details/gtuhjcjeup.html

[K07] 进制转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmtcpicsv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cashguo.top/Article/details/gtawkmrqns.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigufen.top/Article/details/gtmobybrmy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtanonilhm.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gtumqhctdo.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gtzmhwevqe.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xuanzx.com/Article/details/gtusukqqnn.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttnffuexz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gtrmegtrrm.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.tianlin.xyz/Article/details/gtvrtasgvx.html

Py:   pickle.dumps(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtvnqxcmgv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gaohongyu789.top/Article/details/gtbccpvfjh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.9152youxi.cn/Article/details/gtqrdiggnm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yj202588.top/Article/details/gtacclzrah.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.pycfn.com/Article/details/gtyhoftxat.html

Go:   encoding/gob
来源：http://dali.yonumen.top/Article/details/gtygzwudmv.html

Ruby: Marshal.dump(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtycpbduhw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.fzhhl.top/Article/details/gtzprvezlg.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtajtvzery.html

L. 网络请求
来源：http://dali.jinyuanbaomall.cn/Article/details/gtspybsuqb.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtovgzakvw.html

[L01] 发送 GET 请求
来源：http://dali.c1oappe.top/Article/details/gtzchliorq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hammf.cn/Article/details/gtglinkwmj.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hywenlv.cn/Article/details/gtfsywnezx.html

JS:   await fetch(url)
来源：http://dali.feifeiyinyue.top/Article/details/gtuzfmawbn.html

TS:   await fetch(url)
来源：http://dali.yuanzhike.top/Article/details/gtqwntqbct.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sysykeji.top/Article/details/gtvgwjnjel.html

Go:   resp, err := http.Get(url)
来源：http://dali.nanxinkj.top/Article/details/gtpdbeimxk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.quarkkingdee.top/Article/details/gtkeyobvwa.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.316326.xyz/Article/details/gtktajvzge.html

[L02] 发送 POST JSON
来源：http://dali.nanxinkj.top/Article/details/gtbhjvnzws.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.9152youxi.cn/Article/details/gtsxkmdowk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.nwbrower.top/Article/details/gtwallgpci.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daxiang520.top/Article/details/gtrglqkles.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xinyue.icu/Article/details/gtmnngrxga.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yuanzhike.top/Article/details/gtcdyeaqzb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.haohaochexian.top/Article/details/gtiywayhxs.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.guannengcc.top/Article/details/gtwkwytudi.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xinyue.icu/Article/details/gtvpcwunay.html

[L03] 设置自定义请求头
来源：http://dali.hywenlv.cn/Article/details/gtuyohrgob.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yj20258.top/Article/details/gtfywsayhp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zycfv.cn/Article/details/gtubvyiubp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daria6918.cn/Article/details/gtuzhkmzxj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yueranfly.top/Article/details/gtppkvxkcr.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hfpthk.cn/Article/details/gtnhjpmpms.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.wangdashe.top/Article/details/gtajumksrx.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gaohongyu789.top/Article/details/gtvmenfrmy.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtadblaodd.html

[L04] 设置超时
来源：http://dali.havefunace.top/Article/details/gteabuwdgi.html

Py:   requests.get(url, timeout=5)
来源：http://dali.0kj1m.cn/Article/details/gtbafiesjh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yuanzhike.top/Article/details/gttbigpsku.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.iojbl.cn/Article/details/gtfsvgfmlp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yueranfly.top/Article/details/gtesupafus.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdmgkwntb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.chenjidiqi.icu/Article/details/gtraveofmo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.9152youxi.cn/Article/details/gtxenzqnug.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.quarkkingdee.top/Article/details/gtwcaqylnr.html

[L05] 上传文件（multipart）
来源：http://dali.bjfxy.top/Article/details/gtupvmpokv.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zdqjudy.top/Article/details/gtvaenyrpr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.meibo888.top/Article/details/gtorxvulfx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgufenzy.top/Article/details/gtnazmpgfy.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258.top/Article/details/gtxmgzjpsu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinyuanbaomall.cn/Article/details/gtygwowaih.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yuxming.cn/Article/details/gtgrlfbmko.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yongpay.top/Article/details/gtfowdztag.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtnmjryjld.html

[L06] 解析响应为 JSON
来源：http://dali.wangshuangyany.cn/Article/details/gtmsgcpals.html

Py:   resp.json()
来源：http://dali.redwolf501.top/Article/details/gtrxdehqsw.html

PHP:  json_decode($body, true);
来源：http://dali.svipenyu.cn/Article/details/gtakuyeols.html

JS:   await resp.json()
来源：http://dali.jianghu66.top/Article/details/gtvaosncaj.html

TS:   await resp.json()
来源：http://dali.hywenlv.cn/Article/details/gtbhtubvsq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cqqwz.cn/Article/details/gtozofkbhv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jyoumei.cn/Article/details/gtygkircog.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ehwqpu.com/Article/details/gtbpmocibd.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.chenlongwang.top/Article/details/gtehtbaark.html

[L07] 处理 HTTP 状态码
来源：http://dali.chenlongwang.top/Article/details/gtefujopmr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xylfe.cn/Article/details/gtwwnqhdnd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hywenlv.cn/Article/details/gtxkcmvejm.html

JS:   resp.ok;  resp.status
来源：http://dali.vqdsnc.cn/Article/details/gtxumvxvqw.html

TS:   resp.ok;  resp.status
来源：http://dali.chenlongwang.top/Article/details/gtboablmvg.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gtbozvhzzi.html

Go:   resp.StatusCode
来源：http://dali.dianchejie.cn/Article/details/gthexjojah.html

Ruby: resp.code.to_i
来源：http://dali.shanyushiyangtech.top/Article/details/gtsoguzwdk.html

C#:   (int)resp.StatusCode
来源：http://dali.vqdsnc.cn/Article/details/gtktscbscj.html

[L08] 并发请求多个地址
来源：http://dali.hnxiangtu.top/Article/details/gtikgyfrzr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.pycfn.com/Article/details/gtvpyzmyrq.html

PHP:  curl_multi_init() 系列
来源：http://dali.chenlongwang.top/Article/details/gtpuzuxfaq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtflmyxwms.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gtvdkbrnyt.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jqgfzy.top/Article/details/gtwlygvety.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jianghu66.top/Article/details/gtzlukxtyd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hongshengwenyu.top/Article/details/gtpnizyfnq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.pycfn.com/Article/details/gttunjsuvi.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtejdvrpsu.html

M. 命令行 / 进程 / 环境
来源：http://dali.nwbrower.top/Article/details/gtynrxpwoi.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtnrooppfn.html

[M01] 读取命令行参数
来源：http://dali.sysykeji.top/Article/details/gtijhqtrew.html

Py:   sys.argv[1:]
来源：http://dali.sxryk.cn/Article/details/gtaricjwpg.html

PHP:  $argv;  $argc;
来源：http://dali.yueranfly.top/Article/details/gtdqtwwgue.html

JS:   process.argv.slice(2)
来源：http://dali.bjfxy.top/Article/details/gtmvveklcb.html

TS:   process.argv.slice(2)
来源：http://dali.dianchejie.cn/Article/details/gtwtnjgbex.html

Java: args 数组（main 方法参数）
来源：http://dali.gotoacloud.top/Article/details/gtaehxxbmn.html

Go:   os.Args[1:]
来源：http://dali.yuanzhike.top/Article/details/gtjjtyxqek.html

Ruby: ARGV
来源：http://dali.nanxinkj.top/Article/details/gtwudqymdl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yanxiufei.cn/Article/details/gtpiyqjhaj.html

[M02] 读取环境变量
来源：http://dali.wangshuangyany.cn/Article/details/gtctvyxxqg.html

Py:   os.environ.get("HOME")
来源：http://dali.zycfv.cn/Article/details/gtjqweudla.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinghuilouyu.cn/Article/details/gtmrdnnwsz.html

JS:   process.env.HOME
来源：http://dali.chenjidiqi.icu/Article/details/gtpmkmgzry.html

TS:   process.env.HOME
来源：http://dali.daxiang520.top/Article/details/gtiwvzrlur.html

Java: System.getenv("HOME")
来源：http://dali.0kj1m.cn/Article/details/gtvcjortqh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gtqpmdephf.html

Ruby: ENV["HOME"]
来源：http://dali.jqgfzy.top/Article/details/gtxbtwakof.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.iojbl.cn/Article/details/gtrrcgndee.html

[M03] 执行外部命令
来源：http://dali.xuetiantiany.cn/Article/details/gtgfrxxizf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.pengpengdd.cyou/Article/details/gtbpjvlhzs.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gaohongyu789.top/Article/details/gtfscjdbow.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yonumen.top/Article/details/gtyggsesed.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.iojbl.cn/Article/details/gtpbgjzozv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.haohaochexian.top/Article/details/gtlqkvgfbj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.fzhhl.top/Article/details/gtidqiprrd.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jqgfzy.top/Article/details/gtudfmvuxn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ydzc1.top/Article/details/gtvakapets.html

[M04] 获取当前工作目录
来源：http://dali.yvedp.cn/Article/details/gtpawkmjmg.html

Py:   os.getcwd()
来源：http://dali.zhixingplan.top/Article/details/gtzxxmnhxp.html

PHP:  getcwd();
来源：http://dali.c1oappe.top/Article/details/gtgevorbck.html

JS:   process.cwd()
来源：http://dali.yj202588.top/Article/details/gtyjuqaczv.html

TS:   process.cwd()
来源：http://dali.zhixingplan.top/Article/details/gtxrjeauxy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hfpthk.cn/Article/details/gtdllyemui.html

Go:   os.Getwd()
来源：http://dali.jyoumei.cn/Article/details/gtdhieehle.html

Ruby: Dir.pwd
来源：http://dali.ivvv.top/Article/details/gtcgvuftuw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yj20258888.top/Article/details/gtntxjrrpc.html

[M05] 设置退出码
来源：http://dali.yuanzhike.top/Article/details/gtuycooxeh.html

Py:   sys.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gtdshhhwzb.html

PHP:  exit(1);
来源：http://dali.guowangkeji.top/Article/details/gtlgqrozwb.html

JS:   process.exit(1)
来源：http://dali.yueranfly.top/Article/details/gtmnqxcuar.html

TS:   process.exit(1)
来源：http://dali.sweek.top/Article/details/gtxulgospj.html

Java: System.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gtvzigwabj.html

Go:   os.Exit(1)
来源：http://dali.dashuyun.cn/Article/details/gtrshvbqej.html

Ruby: exit 1
来源：http://dali.feifeiyinyue.top/Article/details/gtcwpbhibc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj20258.top/Article/details/gtyzilqcjj.html

[M06] 向标准错误输出
来源：http://dali.ehwqpu.com/Article/details/gtjkqfdqxo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xziqi.cn/Article/details/gtoqkgrjab.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yj202588.top/Article/details/gtjczwdcfi.html

JS:   console.error("err")
来源：http://dali.hnxiangtu.top/Article/details/gtxwvfimgv.html

TS:   console.error("err")
来源：http://dali.zhongyouzk.top/Article/details/gtpbwbslfq.html

Java: System.err.println("err")
来源：http://dali.xylfe.cn/Article/details/gtxwbupohj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.quarkkingdee.top/Article/details/gthzuczbju.html

Ruby: warn "err"
来源：http://dali.yvedp.cn/Article/details/gtnhvzzdpr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cheryme.top/Article/details/gtbvsqytle.html

[M07] 判断是否为主入口
来源：http://dali.shanyushiyangtech.top/Article/details/gtfqzjqtoz.html

Py:   if __name__ == "__main__":
来源：http://dali.bjfxy.top/Article/details/gtgxriwslp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinqigufen.top/Article/details/gtfuwynzan.html

JS:   require.main === module
来源：http://dali.jqgfzy.top/Article/details/gtzwtdshpz.html

TS:   require.main === module
来源：http://dali.yj20258888.top/Article/details/gtdlcchdam.html

Java: public static void main(String[] args)
来源：http://dali.zhiwuduotai.top/Article/details/gtrjctuaup.html

Go:   func main()
来源：http://dali.ppjwa.cn/Article/details/gtmorufmhm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shangyingyoupin.top/Article/details/gtxoqyhpra.html

C#:   static void Main(string[] args)
来源：http://dali.xuanzx.com/Article/details/gtlrxvgfxe.html

[M08] 获取系统与运行时信息
来源：http://dali.xziqi.cn/Article/details/gtlcyjiygz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gtxmuharut.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yj20258888.top/Article/details/gtyjpdhsls.html

JS:   process.platform;  process.version
来源：http://dali.hysaishi.cn/Article/details/gtkyuohzzg.html

TS:   process.platform;  process.version
来源：http://dali.chenjidiqi.icu/Article/details/gtkwnmbftg.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nwbrower.top/Article/details/gtqmzszigj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj20258.top/Article/details/gthojlrtgt.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.wangshuangyany.cn/Article/details/gtjnylmoxg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hnqzz.top/Article/details/gttsnuwvcm.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtebxkizbt.html

N. 数据结构与算法
来源：http://dali.gaohongyu789.top/Article/details/gtugpyisfh.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtafxlyjld.html

[N01] 二分查找（有序数组）
来源：http://dali.cqqwz.cn/Article/details/gtvngyrlrr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtosovvwyv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xuanzx.com/Article/details/gtjjihmmss.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.feifeiyinyue.top/Article/details/gtamesppsa.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jiagoushi.top/Article/details/gtnjwpuvdy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtqqqsacgh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtlbmvrfpd.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj20258888.top/Article/details/gtivrxjwcp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtdixffpqi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjiechlue.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenjidiqi.icu/Article/details/gtfeiijdcy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.gogol.net.cn/Article/details/gtqrhtthmr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnxiangtu.top/Article/details/gtpebfqqrt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangdashe.top/Article/details/gttqbcpjfk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.316326.xyz/Article/details/gticpissma.html

Go:   slices.Sort(arr)
来源：http://dali.yj202588.top/Article/details/gtikumgmif.html

Ruby: arr.sort
来源：http://dali.jianghu66.top/Article/details/gtrpgrhpqf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.dashuyun.cn/Article/details/gtcyjughwq.html

[N03] 快速排序（分治示例）
来源：http://dali.nanxinkj.top/Article/details/gtvpovqgds.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.fengsongda.top/Article/details/gtvointpnz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yongpay.top/Article/details/gtchsvxnxx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhongyouzk.top/Article/details/gtayklxigs.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jlsjyb.cn/Article/details/gtyixyyakr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sxryk.cn/Article/details/gtfnwfvlgl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.iojbl.cn/Article/details/gtxujjqcue.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.pycfn.com/Article/details/gteafzbgmr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sufxvd.cn/Article/details/gtmjdjoseg.html

[N04] 斐波那契数列
来源：http://dali.andypj.xyz/Article/details/gttmvfknii.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.snrcjt.cn/Article/details/gtwbkskqlx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xylfe.cn/Article/details/gtngyviufa.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gotoacloud.top/Article/details/gtltdyavem.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ivvv.top/Article/details/gtoafiwmpf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cashguo.top/Article/details/gthrpsilra.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.birdmap.top/Article/details/gttnpikqwz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.guannengcc.top/Article/details/gtoshxmvqw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gtlxphmsgi.html

[N05] 最大公约数
来源：http://dali.shanyushiyangtech.top/Article/details/gtktqprolu.html

Py:   math.gcd(a, b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtefnhdaap.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.nwbrower.top/Article/details/gtvededouu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenlongwang.top/Article/details/gtnzfazoeu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.iojbl.cn/Article/details/gtmarucdyd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xinyue.icu/Article/details/gteskmcvjc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhengqikj.top/Article/details/gtysnxbpqz.html

Ruby: a.gcd(b)
来源：http://dali.0kj1m.cn/Article/details/gtzgjkvngj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cheryme.top/Article/details/gtirqekbht.html

[N06] 判断回文字符串
来源：http://dali.ppjwa.cn/Article/details/gtbivaydnz.html

Py:   s == s[::-1]
来源：http://dali.yongpay.top/Article/details/gtcrdjoseu.html

PHP:  $s === strrev($s);
来源：http://dali.ydzc1.top/Article/details/gtcbaizupu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gtdcpqnchf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtoqxqizlb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ehwqpu.com/Article/details/gtrkephztm.html

Go:   // 双指针从两端比较
来源：http://dali.ybcxt.top/Article/details/gtrmaifyns.html

Ruby: s == s.reverse
来源：http://dali.birdmap.top/Article/details/gtqrvffqcm.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhengqikj.top/Article/details/gtydnajmcc.html

[N07] 两数之和（返回下标）
来源：http://dali.nanxinkj.top/Article/details/gtmrbonced.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yanxiufei.cn/Article/details/gttveihwao.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jiagoushi.top/Article/details/gtjdytdymq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hnqzz.top/Article/details/gtejkbteoh.html

TS:   // 手写 Map<string, number>
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvdajqqxm.html

Java: // 手写 HashMap
来源：http://dali.9152youxi.cn/Article/details/gthmfvkawd.html

Go:   // 手写 map[int]int
来源：http://dali.zdqjudy.top/Article/details/gtlyyduewv.html

Ruby: // 手写 Hash
来源：http://dali.snrcjt.cn/Article/details/gtvzmecknh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.mhx1999.top/Article/details/gtpxyfbynx.html

[N08] 生成全排列
来源：http://dali.yanxiufei.cn/Article/details/gtzfcvsnuf.html

Py:   itertools.permutations(arr)
来源：http://dali.ppjwa.cn/Article/details/gtmnosyuhe.html

PHP:  // 手写递归交换
来源：http://dali.wangdashe.top/Article/details/gtsewerdzk.html

JS:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gtocjmdscm.html

TS:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtnqliqubv.html

Java: // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gtopnkfccw.html

Go:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gtpsjbympa.html

Ruby: arr.permutation.to_a
来源：http://dali.cdnleiting.top/Article/details/gtrphdvvru.html

C#:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gtgiqpiire.html

[N09] 栈与队列
来源：http://dali.ydzc1.top/Article/details/gtbjnvsjul.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hfpthk.cn/Article/details/gtwmghljpg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.tianlin.xyz/Article/details/gtunqtfqfm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.kuanghao11.cn/Article/details/gtizgxrpyf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hnqzz.top/Article/details/gtovmirkul.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.quarkkingdee.top/Article/details/gthpjextph.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ybcxt.top/Article/details/gtbyogptmp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gotoacloud.top/Article/details/gtvyuiermx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenjidiqi.icu/Article/details/gtzgvpacqh.html

[N10] 链表节点定义
来源：http://dali.guannengcc.top/Article/details/gthxdxtqmi.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gaohongyu789.top/Article/details/gtirtikrgw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sufxvd.cn/Article/details/gttcgpuuzj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.mhx1999.top/Article/details/gtzovmixaq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jiagoushi.top/Article/details/gtdnnkgbho.html

Java: class Node { int v; Node next; }
来源：http://dali.yonumen.top/Article/details/gttgghhdnw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jqgufenzy.top/Article/details/gtnmypprak.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hnxiangtu.top/Article/details/gtappdwynn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gzhubu.top/Article/details/gtkqfacslk.html

[N11] 二叉树中序遍历
来源：http://dali.gotoacloud.top/Article/details/gtufeesygl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gtpyffgppc.html

PHP:  // 手写递归函数
来源：http://dali.jyoumei.cn/Article/details/gtojzhznzu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxuanxn.top/Article/details/gtixtvzbis.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.mhx1999.top/Article/details/gtqkawilhs.html

Java: // 手写递归
来源：http://dali.yueranfly.top/Article/details/gtpirihlrc.html

Go:   // 手写递归
来源：http://dali.snrcjt.cn/Article/details/gthogcuozo.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlobvndda.html

C#:   // 手写递归
来源：http://dali.xuetiantiany.cn/Article/details/gttczyczxu.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhixingplan.top/Article/details/gtcojlyfwn.html


<!-- 参考信息 -->