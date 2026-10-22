代发 wailian999

[K02] JSON 字符串转对象
来源：http://dali.tian-w.cn/Article/details/gtasyicmpo.html

Py:   json.loads(s)
来源：http://dali.daria6918.cn/Article/details/gtfkqrifgn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ppjwa.cn/Article/details/gtijtpkjlm.html

JS:   JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gtmigumjmc.html

TS:   JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gtsywyzrud.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sufxvd.cn/Article/details/gtnplsrryf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.daxiang520.top/Article/details/gtzuhwrylc.html

Ruby: JSON.parse(s)
来源：http://dali.yj20258888.top/Article/details/gtnawrmjke.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nanxuanxn.top/Article/details/gtxqylotik.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jqgfzy.top/Article/details/gtfpktgixz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhongyouzk.top/Article/details/gtvnaerdnr.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.redwolf501.top/Article/details/gtkmecqlef.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cdnleiting.top/Article/details/gtjnluslue.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258.top/Article/details/gtmbwxykpy.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cheryme.top/Article/details/gttbbhxmne.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinqigfzy.top/Article/details/gtuexgfrhs.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtrqesksxb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsivxzghv.html

[K04] 读取 JSON 文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkhztlluo.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hysaishi.cn/Article/details/gtdsmjpywi.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ehwqpu.com/Article/details/gtquptvbrd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuetiantiany.cn/Article/details/gtjtyvtcsv.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuanzhike.top/Article/details/gtilwvuesw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.snrcjt.cn/Article/details/gtfmafrlba.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yuxming.cn/Article/details/gtqjrcwbnb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zdqjudy.top/Article/details/gtyzkbahxr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hysaishi.cn/Article/details/gtzuvdsyjd.html

[K05] 深拷贝对象
来源：http://dali.aizwys.cn/Article/details/gtotmqemic.html

Py:   copy.deepcopy(obj)
来源：http://dali.zycfv.cn/Article/details/gtlckjsttl.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hnxiangtu.top/Article/details/gtpbfczzhm.html

JS:   structuredClone(obj)
来源：http://dali.hysaishi.cn/Article/details/gtkccuiwdi.html

TS:   structuredClone(obj)
来源：http://dali.xinyue.icu/Article/details/gtewleikxv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shanyushiyangtech.top/Article/details/gtbvusijlo.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhiwuduotai.top/Article/details/gtxjuonwpn.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.aibaodan.cn/Article/details/gtggxlqeqh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gogol.net.cn/Article/details/gtlrrikfjs.html

[K06] 解析 URL 查询串
来源：http://dali.iojbl.cn/Article/details/gtevtrtqug.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.haohaochexian.top/Article/details/gtcqwynylb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.316326.xyz/Article/details/gtgcqkwhnz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ppjwa.cn/Article/details/gtrkrplenm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigufen.top/Article/details/gtuwmdaxeo.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nanxinkj.top/Article/details/gtnhpgrpwp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.guannengcc.top/Article/details/gtgnrrkcpa.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.tianlin.xyz/Article/details/gtjgecexjt.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jqgfzy.top/Article/details/gtedauwyih.html

[K07] 进制转换
来源：http://dali.zhiwuduotai.top/Article/details/gtwsylmncs.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gtxbrnwgyo.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigufen.top/Article/details/gtmwahadju.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yonumen.top/Article/details/gtmjpdrsnq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmhxzjwdt.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gtnuhakawn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shuidangran.top/Article/details/gtcbnhdmhg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.meibo888.top/Article/details/gtrsbkhthr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzxxbgzhy.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrrnvucav.html

Py:   pickle.dumps(obj)
来源：http://dali.dianchejie.cn/Article/details/gtikkbppbc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.daria6918.cn/Article/details/gtdmnjkzhv.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.dianchejie.cn/Article/details/gthxeqkxhu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cqqwz.cn/Article/details/gtxenzqwsm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhengqikj.top/Article/details/gtugvdjfrb.html

Go:   encoding/gob
来源：http://dali.yangfankeji.com/Article/details/gtxxdqfzsq.html

Ruby: Marshal.dump(obj)
来源：http://dali.yueranfly.top/Article/details/gtuyedjybz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hywenlv.cn/Article/details/gtuhrjyarz.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtzejasynx.html

L. 网络请求
来源：http://dali.xuanzx.com/Article/details/gtltxkrbed.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtmymqqjwg.html

[L01] 发送 GET 请求
来源：http://dali.jinqigfzy.top/Article/details/gtmrtfzsar.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.chenjidiqi.icu/Article/details/gtmtlgqtxa.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yj20258888.top/Article/details/gtmrmosvmv.html

JS:   await fetch(url)
来源：http://dali.zhixingplan.top/Article/details/gtmjbuqbwq.html

TS:   await fetch(url)
来源：http://dali.xylfe.cn/Article/details/gtgnbiacfm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.smart0.xyz/Article/details/gtdmfffjjp.html

Go:   resp, err := http.Get(url)
来源：http://dali.wangshuangyany.cn/Article/details/gtxjtuwbdl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhixingplan.top/Article/details/gtfgwwycjs.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinqigfzy.top/Article/details/gtqqisvrki.html

[L02] 发送 POST JSON
来源：http://dali.sufxvd.cn/Article/details/gtbiuvkbnu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.tianlin.xyz/Article/details/gtgklhznkg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.svipenyu.cn/Article/details/gtooglbpkv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tian-w.cn/Article/details/gttygzuypw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pengpengdd.cyou/Article/details/gtdgpuhpru.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.316326.xyz/Article/details/gtbhoxefcz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkjbxvxoi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhongyouzk.top/Article/details/gtofpwyewn.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jqgufenzy.top/Article/details/gtkxfvyjay.html

[L03] 设置自定义请求头
来源：http://dali.ivvv.top/Article/details/gtragqeajx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.mhx1999.top/Article/details/gtijvcyonk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.smart0.xyz/Article/details/gtjqwhfxut.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sxryk.cn/Article/details/gtphhuvhne.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtelglcrzq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sweek.top/Article/details/gtjutjrxeg.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.aizwys.cn/Article/details/gtxaftmmzf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ybcxt.top/Article/details/gtzlykzjtt.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.haohaochexian.top/Article/details/gtdofrqnfx.html

[L04] 设置超时
来源：http://dali.dianchejie.cn/Article/details/gtlqjzlnza.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shzxlz.cn/Article/details/gtbeslruqk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cqqwz.cn/Article/details/gtznsjhdga.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gogol.net.cn/Article/details/gtljeljxia.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ivvv.top/Article/details/gttzqhnwvc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.daria6918.cn/Article/details/gtczajelhq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.svipenyu.cn/Article/details/gtxqatpvfo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jlsjyb.cn/Article/details/gtrthcixwn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cheryme.top/Article/details/gtrbckealy.html

[L05] 上传文件（multipart）
来源：http://dali.c1oappe.top/Article/details/gtwcozmjnn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nanxinkj.top/Article/details/gtrctkduek.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gtdiolpfhi.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinghuilouyu.cn/Article/details/gtcxmblisx.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.fengsongda.top/Article/details/gtlvaaptiq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.c1oappe.top/Article/details/gtsibzildu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhixingplan.top/Article/details/gtqdzijwkv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hysaishi.cn/Article/details/gthwjecxdf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtbewisnnm.html

[L06] 解析响应为 JSON
来源：http://dali.dianchejie.cn/Article/details/gtyfzbvdyn.html

Py:   resp.json()
来源：http://dali.hfpthk.cn/Article/details/gtzsmtyrqo.html

PHP:  json_decode($body, true);
来源：http://dali.tanke756.top/Article/details/gtcqdkykts.html

JS:   await resp.json()
来源：http://dali.wangdashe.top/Article/details/gtuocegqlc.html

TS:   await resp.json()
来源：http://dali.smart0.xyz/Article/details/gtygurkocj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yangfankeji.com/Article/details/gtnaigcjoy.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.andypj.xyz/Article/details/gtlqhdzfuw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfknhlzso.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.feifeiyinyue.top/Article/details/gtohpzyopu.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhixingplan.top/Article/details/gtztewtlhc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hnxiangtu.top/Article/details/gtzujvfdtn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xinyue.icu/Article/details/gtqhnzktli.html

JS:   resp.ok;  resp.status
来源：http://dali.yuxming.cn/Article/details/gtolsvifdz.html

TS:   resp.ok;  resp.status
来源：http://dali.jyoumei.cn/Article/details/gtqfpwwmrm.html

Java: resp.statusCode()
来源：http://dali.gotoacloud.top/Article/details/gtfaapsuvr.html

Go:   resp.StatusCode
来源：http://dali.ivvv.top/Article/details/gtwogwwnvs.html

Ruby: resp.code.to_i
来源：http://dali.gzhubu.top/Article/details/gtbenraruy.html

C#:   (int)resp.StatusCode
来源：http://dali.hammf.cn/Article/details/gttoohhdjj.html

[L08] 并发请求多个地址
来源：http://dali.yj202588.top/Article/details/gtvcahpttx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jianghu66.top/Article/details/gtthlqzyqy.html

PHP:  curl_multi_init() 系列
来源：http://dali.zycfv.cn/Article/details/gtcahknwnj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fengsongda.top/Article/details/gtjsjfhwvw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sxryk.cn/Article/details/gtxdoreaod.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jianghu66.top/Article/details/gtnfuhkzhf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.haohaochexian.top/Article/details/gtfdgzutor.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sysykeji.top/Article/details/gtccakzbsy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.bjfxy.top/Article/details/gtvgeymgyz.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmaaycmtx.html

M. 命令行 / 进程 / 环境
来源：http://dali.hywenlv.cn/Article/details/gthwilglxr.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtiyymocof.html

[M01] 读取命令行参数
来源：http://dali.sufxvd.cn/Article/details/gtoysnioor.html

Py:   sys.argv[1:]
来源：http://dali.yuxming.cn/Article/details/gtzxetotkn.html

PHP:  $argv;  $argc;
来源：http://dali.daxiang520.top/Article/details/gtyvlogizm.html

JS:   process.argv.slice(2)
来源：http://dali.zdqjudy.top/Article/details/gtahkmmhxr.html

TS:   process.argv.slice(2)
来源：http://dali.yanxiufei.cn/Article/details/gtxqthceic.html

Java: args 数组（main 方法参数）
来源：http://dali.shzxlz.cn/Article/details/gtqmxflyal.html

Go:   os.Args[1:]
来源：http://dali.xylfe.cn/Article/details/gtwwgnmyzg.html

Ruby: ARGV
来源：http://dali.shanyushiyangtech.top/Article/details/gtsfyzdqrn.html

C#:   args 数组（Main 方法参数）
来源：http://dali.smart0.xyz/Article/details/gtyzcpcnvt.html

[M02] 读取环境变量
来源：http://dali.gotoacloud.top/Article/details/gtbjpyzttu.html

Py:   os.environ.get("HOME")
来源：http://dali.c1oappe.top/Article/details/gtxrafrcuy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.quarkkingdee.top/Article/details/gtjsgmgxoz.html

JS:   process.env.HOME
来源：http://dali.yj20258888.top/Article/details/gtcgfdjpfd.html

TS:   process.env.HOME
来源：http://dali.hnxiangtu.top/Article/details/gtbkzyrayx.html

Java: System.getenv("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtalqfjkqk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gtebwuiogl.html

Ruby: ENV["HOME"]
来源：http://dali.nanxuanxn.top/Article/details/gtgbxcbhoa.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.aibaodan.cn/Article/details/gtphlcgvkh.html

[M03] 执行外部命令
来源：http://dali.yvedp.cn/Article/details/gtptdkxtit.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.quarkkingdee.top/Article/details/gtbyfsegdh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.guannengcc.top/Article/details/gtireowayr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.guannengcc.top/Article/details/gtjcfbjucq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gzhubu.top/Article/details/gthpixsrpm.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ivvv.top/Article/details/gtwjbpyjpi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.vqdsnc.cn/Article/details/gtofqvmemh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yanxiufei.cn/Article/details/gttovfkvzc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.c1oappe.top/Article/details/gtezzjahrd.html

[M04] 获取当前工作目录
来源：http://dali.ppjwa.cn/Article/details/gtfazuquph.html

Py:   os.getcwd()
来源：http://dali.hammf.cn/Article/details/gtkhmyueog.html

PHP:  getcwd();
来源：http://dali.zhiwuduotai.top/Article/details/gtujxpuuhb.html

JS:   process.cwd()
来源：http://dali.iojbl.cn/Article/details/gtgpzeleay.html

TS:   process.cwd()
来源：http://dali.dianchejie.cn/Article/details/gtuhlnolvq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.meibo888.top/Article/details/gtyiontjjv.html

Go:   os.Getwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkamzmaqi.html

Ruby: Dir.pwd
来源：http://dali.zdqjudy.top/Article/details/gtttwwihmd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xinyue.icu/Article/details/gtijnpjmjv.html

[M05] 设置退出码
来源：http://dali.havefunace.top/Article/details/gtkzyjkmpx.html

Py:   sys.exit(1)
来源：http://dali.mhx1999.top/Article/details/gtsbqfwnbo.html

PHP:  exit(1);
来源：http://dali.zycfv.cn/Article/details/gtpycgfvli.html

JS:   process.exit(1)
来源：http://dali.meibo888.top/Article/details/gtqhtcmuxs.html

TS:   process.exit(1)
来源：http://dali.jianghu66.top/Article/details/gtlxedzfkt.html

Java: System.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnzkrqwuz.html

Go:   os.Exit(1)
来源：http://dali.xinyue.icu/Article/details/gtftqknwea.html

Ruby: exit 1
来源：http://dali.pycfn.com/Article/details/gtrlhxusbq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xuetiantiany.cn/Article/details/gtnbvtgyjl.html

[M06] 向标准错误输出
来源：http://dali.yvedp.cn/Article/details/gtclfcekko.html

Py:   print("err", file=sys.stderr)
来源：http://dali.fengsongda.top/Article/details/gtqaoxlaeh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cheryme.top/Article/details/gtulmzwnrd.html

JS:   console.error("err")
来源：http://dali.ydzc1.top/Article/details/gtvfqinpop.html

TS:   console.error("err")
来源：http://dali.jianghu66.top/Article/details/gtdwajgazd.html

Java: System.err.println("err")
来源：http://dali.pycfn.com/Article/details/gtnzflcflj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.andypj.xyz/Article/details/gtrhqclmkh.html

Ruby: warn "err"
来源：http://dali.xziqi.cn/Article/details/gtkgxzwbui.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.c1oappe.top/Article/details/gtcjfqsiiw.html

[M07] 判断是否为主入口
来源：http://dali.redwolf501.top/Article/details/gtbomyhxgo.html

Py:   if __name__ == "__main__":
来源：http://dali.ehwqpu.com/Article/details/gtafeltdsa.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hnxiangtu.top/Article/details/gtgkuoaqxr.html

JS:   require.main === module
来源：http://dali.redwolf501.top/Article/details/gtbjsplxdc.html

TS:   require.main === module
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfvrulmr.html

Java: public static void main(String[] args)
来源：http://dali.pengpengdd.cyou/Article/details/gtknldrwpt.html

Go:   func main()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjlqlmuqz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sysykeji.top/Article/details/gtjlceinav.html

C#:   static void Main(string[] args)
来源：http://dali.andypj.xyz/Article/details/gtnjsnfnic.html

[M08] 获取系统与运行时信息
来源：http://dali.yvedp.cn/Article/details/gtmlgumxtg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.pengpengdd.cyou/Article/details/gtjznmobfi.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yj202588.top/Article/details/gtrqrfggpv.html

JS:   process.platform;  process.version
来源：http://dali.tanke756.top/Article/details/gttzmwlvgu.html

TS:   process.platform;  process.version
来源：http://dali.c1oappe.top/Article/details/gtpblslkul.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.aizwys.cn/Article/details/gtfgsyqlpv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.mhx1999.top/Article/details/gtijtzjtww.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ppjwa.cn/Article/details/gtcitshdgu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ivvv.top/Article/details/gtlrhewtox.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtkvewqwic.html

N. 数据结构与算法
来源：http://dali.shzxlz.cn/Article/details/gtnoiukdrh.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtczkctoyl.html

[N01] 二分查找（有序数组）
来源：http://dali.xuanzx.com/Article/details/gtxzldcecw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtyqowvicy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sysykeji.top/Article/details/gtbqzofqrq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdpxbgjcy.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ybcxt.top/Article/details/gtsukojwka.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gtqymbvzuo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtpjizwgul.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtabfqqmej.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtaqyhsnbq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtckzipnkb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sufxvd.cn/Article/details/gteyhcbzib.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.aibaodan.cn/Article/details/gtknjnfnkz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.svipenyu.cn/Article/details/gtipkqevyr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nwbrower.top/Article/details/gtlyohclyi.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yanxiufei.cn/Article/details/gtbipzzclb.html

Go:   slices.Sort(arr)
来源：http://dali.guowangkeji.top/Article/details/gtogrwphaw.html

Ruby: arr.sort
来源：http://dali.quarkkingdee.top/Article/details/gtdbekfhdg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nanxinkj.top/Article/details/gtgggxefcx.html

[N03] 快速排序（分治示例）
来源：http://dali.gotoacloud.top/Article/details/gteutxiase.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhongyouzk.top/Article/details/gtiocuwnwf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.daxiang520.top/Article/details/gttlpkckui.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guannengcc.top/Article/details/gtkebuxxge.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkihacipk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shangyingyoupin.top/Article/details/gtsdaeyytl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ydzc1.top/Article/details/gtgsswxtta.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yj20258888.top/Article/details/gtqcuykhyg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtehshflde.html

[N04] 斐波那契数列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqwldpjft.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.tanke756.top/Article/details/gtxgdfcxmw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoaiwokxo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gtdjkaueav.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.redwolf501.top/Article/details/gtsrsbocck.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yonumen.top/Article/details/gtgkermwyn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cashguo.top/Article/details/gtwvnnwmrk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.tanke756.top/Article/details/gtwtviletf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtodcewyho.html

[N05] 最大公约数
来源：http://dali.fzhhl.top/Article/details/gtjnvmwpas.html

Py:   math.gcd(a, b)
来源：http://dali.dianchejie.cn/Article/details/gtukpisaiv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.svipenyu.cn/Article/details/gttlnuombh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tanke756.top/Article/details/gtjilzybmt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zdqjudy.top/Article/details/gtjgfthrpk.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinqigfzy.top/Article/details/gtrnioruir.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sweek.top/Article/details/gtpmanwfde.html

Ruby: a.gcd(b)
来源：http://dali.shuidangran.top/Article/details/gthtmdmxkt.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ivvv.top/Article/details/gtwxdacqqu.html

[N06] 判断回文字符串
来源：http://dali.hammf.cn/Article/details/gtlurhamlo.html

Py:   s == s[::-1]
来源：http://dali.xuetiantiany.cn/Article/details/gtxilnptfg.html

PHP:  $s === strrev($s);
来源：http://dali.daxiang520.top/Article/details/gtwtvgsahv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gtpiaptgjb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gtnopwarfy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cheryme.top/Article/details/gtwmnrqmnd.html

Go:   // 双指针从两端比较
来源：http://dali.jiagoushi.top/Article/details/gtpattunso.html

Ruby: s == s.reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpjkhbzfe.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yj20258.top/Article/details/gtgfurkoyq.html

[N07] 两数之和（返回下标）
来源：http://dali.feifeiyinyue.top/Article/details/gtyakqbilq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gotoacloud.top/Article/details/gtfyhqylij.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hammf.cn/Article/details/gtiygdrwxz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.0kj1m.cn/Article/details/gtedqlyrnq.html

TS:   // 手写 Map<string, number>
来源：http://dali.cheryme.top/Article/details/gtypazjwrx.html

Java: // 手写 HashMap
来源：http://dali.hfpthk.cn/Article/details/gtsgherdul.html

Go:   // 手写 map[int]int
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqpeknzkb.html

Ruby: // 手写 Hash
来源：http://dali.cdnleiting.top/Article/details/gtgcwzenuu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cucudq.cn/Article/details/gtkriexvmh.html

[N08] 生成全排列
来源：http://dali.shanyushiyangtech.top/Article/details/gtlyqhqwuc.html

Py:   itertools.permutations(arr)
来源：http://dali.jyoumei.cn/Article/details/gtbzyixola.html

PHP:  // 手写递归交换
来源：http://dali.hnxiangtu.top/Article/details/gtjrvfikrn.html

JS:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gtjoonkyas.html

TS:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gttxhbkvva.html

Java: // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gtgtotgwgi.html

Go:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gtwsjzfurn.html

Ruby: arr.permutation.to_a
来源：http://dali.cqqwz.cn/Article/details/gtirxnyhjo.html

C#:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gtqscqmqgp.html

[N09] 栈与队列
来源：http://dali.guowangkeji.top/Article/details/gtonyhvoac.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.andypj.xyz/Article/details/gtppkdowou.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gtiiycnmcp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.c1oappe.top/Article/details/gtmrdhbald.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhengqikj.top/Article/details/gtcechgktt.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xuetiantiany.cn/Article/details/gtrlxigwgm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.wangdashe.top/Article/details/gttcfhnicv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hywenlv.cn/Article/details/gtkfbymslx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinghuilouyu.cn/Article/details/gtlvpgsujq.html

[N10] 链表节点定义
来源：http://dali.ivvv.top/Article/details/gtqqoqvkvz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tanke756.top/Article/details/gtnblzhgaf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yvedp.cn/Article/details/gtplbuodzo.html


<!-- 参考信息 -->