代发 wailian999

TS:   JSON.parse(s)
来源：http://dali.quarkkingdee.top/Article/details/gttaytkjhq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxaojtglu.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zycfv.cn/Article/details/gtcyzbzuyg.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gtwpeoxtzc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhoulong.xyz/Article/details/gtfhanjaac.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shzxlz.cn/Article/details/gtagbdbuto.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gogol.net.cn/Article/details/gtzzqrjqll.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shzxlz.cn/Article/details/gtouhjetur.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tian-w.cn/Article/details/gtzzujxxrn.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258888.top/Article/details/gtpttcxszx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.aibaodan.cn/Article/details/gtjbcdbiko.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.dianchejie.cn/Article/details/gtffxfxcqo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zycfv.cn/Article/details/gtkcacthwo.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhongyouzk.top/Article/details/gtixuxjype.html

[K04] 读取 JSON 文件
来源：http://dali.chenjidiqi.icu/Article/details/gtuojuqgfv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tianlin.xyz/Article/details/gtxuhsocdf.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yangfankeji.com/Article/details/gtswuipvyd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.mhx1999.top/Article/details/gtmheacxfv.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sufxvd.cn/Article/details/gtnxoiqqlo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.daxiang520.top/Article/details/gtgtpitfgz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cheryme.top/Article/details/gtnbqjahbe.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gotoacloud.top/Article/details/gtwuhajpqb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sweek.top/Article/details/gtiefbzinm.html

[K05] 深拷贝对象
来源：http://dali.bjfxy.top/Article/details/gtexkfycah.html

Py:   copy.deepcopy(obj)
来源：http://dali.nanxinkj.top/Article/details/gtvkmmijhq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.svipenyu.cn/Article/details/gtapggjotl.html

JS:   structuredClone(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtxudrfpvo.html

TS:   structuredClone(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtjwgxfgdr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jqgfzy.top/Article/details/gtggprmowb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtakdbhptp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.pycfn.com/Article/details/gtppsimwet.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yangfankeji.com/Article/details/gtomhrbqtk.html

[K06] 解析 URL 查询串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtozuyalqs.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yonumen.top/Article/details/gthtgxikas.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sxryk.cn/Article/details/gtposeuezg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigufen.top/Article/details/gtijtnrttz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hywenlv.cn/Article/details/gtumtmypxo.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xuetiantiany.cn/Article/details/gtzsyoxemo.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.birdmap.top/Article/details/gtcercjtal.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hfpthk.cn/Article/details/gthtyuysue.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ybcxt.top/Article/details/gtpkyseoen.html

[K07] 进制转换
来源：http://dali.ydzc1.top/Article/details/gtaxhwdall.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtuwlrwjym.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nanxinkj.top/Article/details/gtmgrflsdf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gttilrydfb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gtiyidbzzl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyvgkzfwi.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.svipenyu.cn/Article/details/gtjrprdzth.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.pycfn.com/Article/details/gtkzygduwf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtuedbzbde.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.havefunace.top/Article/details/gtcvucrdrm.html

Py:   pickle.dumps(obj)
来源：http://dali.chenlongwang.top/Article/details/gtvwrrycjf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ppjwa.cn/Article/details/gtvcbbnjgt.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yuanzhike.top/Article/details/gtocwaxdzx.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.pengpengdd.cyou/Article/details/gtokqahylc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.mhx1999.top/Article/details/gtyqudwhzh.html

Go:   encoding/gob
来源：http://dali.nwbrower.top/Article/details/gtowurqwjv.html

Ruby: Marshal.dump(obj)
来源：http://dali.cdnleiting.top/Article/details/gtopglkhnj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hnqzz.top/Article/details/gtjjpjagvi.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtoaxebcxj.html

L. 网络请求
来源：http://dali.yangfankeji.com/Article/details/gttvsyagje.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtlltstkoc.html

[L01] 发送 GET 请求
来源：http://dali.andypj.xyz/Article/details/gtepxfvszc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cucudq.cn/Article/details/gtzbpwiymo.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cheryme.top/Article/details/gtcmvekjie.html

JS:   await fetch(url)
来源：http://dali.tianlin.xyz/Article/details/gtesowokfi.html

TS:   await fetch(url)
来源：http://dali.316326.xyz/Article/details/gtvwdrjbjc.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ehwqpu.com/Article/details/gttpntkekt.html

Go:   resp, err := http.Get(url)
来源：http://dali.guowangkeji.top/Article/details/gtlgetsrss.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.haohaochexian.top/Article/details/gtwosqsogl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jqgfzy.top/Article/details/gtfewphmax.html

[L02] 发送 POST JSON
来源：http://dali.hnqzz.top/Article/details/gttfngdafv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenzaomai.com/Article/details/gtssmmzpcm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.aibaodan.cn/Article/details/gtesybfbrr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tianlin.xyz/Article/details/gtgnegiqks.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgufenzy.top/Article/details/gtonwsmerb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.redwolf501.top/Article/details/gttntgjnet.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.iojbl.cn/Article/details/gtubwlhgcr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zdqjudy.top/Article/details/gtobvhrizr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.daxiang520.top/Article/details/gthhdgyjbm.html

[L03] 设置自定义请求头
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkebeygrh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hfpthk.cn/Article/details/gtazwvdkwc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.vqdsnc.cn/Article/details/gtaveqpyeb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenjidiqi.icu/Article/details/gtymruuiny.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenzaomai.com/Article/details/gtoqfwrkdx.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shuidangran.top/Article/details/gtnwkqwvnq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.guowangkeji.top/Article/details/gtfayeaqzb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nanxuanxn.top/Article/details/gtsnprdvtf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ybcxt.top/Article/details/gtwunhezjz.html

[L04] 设置超时
来源：http://dali.snrcjt.cn/Article/details/gticdczrzp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ehwqpu.com/Article/details/gtpqbbjyyc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.daria6918.cn/Article/details/gtaipqqmcx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.kuanghao11.cn/Article/details/gtxvbhwqmr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnxiangtu.top/Article/details/gtwxlvlnvb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.guowangkeji.top/Article/details/gtgpsucszt.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.guannengcc.top/Article/details/gtrzuwdihu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgcybnrck.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xuetiantiany.cn/Article/details/gteuoohezq.html

[L05] 上传文件（multipart）
来源：http://dali.aibaodan.cn/Article/details/gtqyfsxsoq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ywan-chungtsiang.top/Article/details/gthjyeophi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvhspcumd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hongshengwenyu.top/Article/details/gtzwkiivrw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hfpthk.cn/Article/details/gtibvznqin.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jqgufenzy.top/Article/details/gtplnjofdf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sxryk.cn/Article/details/gtninjbdew.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gaohongyu789.top/Article/details/gtdifnxiyz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtkdfnckuu.html

[L06] 解析响应为 JSON
来源：http://dali.fzhhl.top/Article/details/gtttrzwwbk.html

Py:   resp.json()
来源：http://dali.sysykeji.top/Article/details/gtxesgxfvg.html

PHP:  json_decode($body, true);
来源：http://dali.cucudq.cn/Article/details/gtkalcrnnl.html

JS:   await resp.json()
来源：http://dali.shangyingyoupin.top/Article/details/gtoshoqyrq.html

TS:   await resp.json()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxmexwvok.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.haohaochexian.top/Article/details/gthvfgnlab.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhoulong.xyz/Article/details/gtzghlvmpe.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinghuilouyu.cn/Article/details/gtprqlggbp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.smart0.xyz/Article/details/gtlhhfxuix.html

[L07] 处理 HTTP 状态码
来源：http://dali.xinyue.icu/Article/details/gtqsjbbqzo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tanke756.top/Article/details/gtnzjrjcza.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinqigfzy.top/Article/details/gtfozpczpl.html

JS:   resp.ok;  resp.status
来源：http://dali.xuanzx.com/Article/details/gtgekfqazg.html

TS:   resp.ok;  resp.status
来源：http://dali.zhengqikj.top/Article/details/gtjlusaoam.html

Java: resp.statusCode()
来源：http://dali.hywenlv.cn/Article/details/gttiegdvou.html

Go:   resp.StatusCode
来源：http://dali.havefunace.top/Article/details/gtpynxvgjc.html

Ruby: resp.code.to_i
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqtfckllz.html

C#:   (int)resp.StatusCode
来源：http://dali.yuxming.cn/Article/details/gthudzjbcu.html

[L08] 并发请求多个地址
来源：http://dali.9152youxi.cn/Article/details/gthecyvesg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hfpthk.cn/Article/details/gtryjknyxe.html

PHP:  curl_multi_init() 系列
来源：http://dali.jlsjyb.cn/Article/details/gttmvriiol.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.bjfxy.top/Article/details/gtbwzqyvfr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tian-w.cn/Article/details/gtklbjlywt.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xziqi.cn/Article/details/gtelcoqhug.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.guowangkeji.top/Article/details/gtnvywbvvk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gotoacloud.top/Article/details/gtsliunzhu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.guowangkeji.top/Article/details/gtwruwtpds.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtcdfhbmvu.html

M. 命令行 / 进程 / 环境
来源：http://dali.jqgufenzy.top/Article/details/gtzwhjbfuw.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtnkabeegb.html

[M01] 读取命令行参数
来源：http://dali.jlsjyb.cn/Article/details/gtcycnyvmv.html

Py:   sys.argv[1:]
来源：http://dali.yanxiufei.cn/Article/details/gttcecttdl.html

PHP:  $argv;  $argc;
来源：http://dali.wangdashe.top/Article/details/gtfupkomaw.html

JS:   process.argv.slice(2)
来源：http://dali.bjfxy.top/Article/details/gtiuecxgbh.html

TS:   process.argv.slice(2)
来源：http://dali.aibaodan.cn/Article/details/gtpgrjqzgy.html

Java: args 数组（main 方法参数）
来源：http://dali.sysykeji.top/Article/details/gtsufyrjkv.html

Go:   os.Args[1:]
来源：http://dali.yonumen.top/Article/details/gtnjcrrced.html

Ruby: ARGV
来源：http://dali.hongshengwenyu.top/Article/details/gtokyuxmkv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gzhubu.top/Article/details/gtqbujctay.html

[M02] 读取环境变量
来源：http://dali.daria6918.cn/Article/details/gtugprtqok.html

Py:   os.environ.get("HOME")
来源：http://dali.9152youxi.cn/Article/details/gtcjdwcbvx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.fengsongda.top/Article/details/gtvebfvubw.html

JS:   process.env.HOME
来源：http://dali.xylfe.cn/Article/details/gtrvegtdrv.html

TS:   process.env.HOME
来源：http://dali.redwolf501.top/Article/details/gtpykfajwf.html

Java: System.getenv("HOME")
来源：http://dali.jyoumei.cn/Article/details/gtuhqzovol.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jianghu66.top/Article/details/gtclpsmofi.html

Ruby: ENV["HOME"]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfabmvpoa.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzecypmum.html

[M03] 执行外部命令
来源：http://dali.zhiwuduotai.top/Article/details/gtttpjqegi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yangfankeji.com/Article/details/gtodspdgeh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gogol.net.cn/Article/details/gtpzdnbiwc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.haohaochexian.top/Article/details/gtaoxgkmyr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.316326.xyz/Article/details/gttkeadwtm.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yuanzhike.top/Article/details/gtrjtljrol.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.meibo888.top/Article/details/gtutyeorip.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.bjfxy.top/Article/details/gtfljwjqvp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hfpthk.cn/Article/details/gtavhziyjw.html

[M04] 获取当前工作目录
来源：http://dali.nanxuanxn.top/Article/details/gtwbhyvjbe.html

Py:   os.getcwd()
来源：http://dali.0kj1m.cn/Article/details/gthpxqnhru.html

PHP:  getcwd();
来源：http://dali.quarkkingdee.top/Article/details/gtcuixqhov.html

JS:   process.cwd()
来源：http://dali.jinqigfzy.top/Article/details/gtayqexhhu.html

TS:   process.cwd()
来源：http://dali.xuetiantiany.cn/Article/details/gthzdlbjco.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gzhubu.top/Article/details/gtxetscxzt.html

Go:   os.Getwd()
来源：http://dali.zhongyouzk.top/Article/details/gtghjgcfew.html

Ruby: Dir.pwd
来源：http://dali.yuanzhike.top/Article/details/gtydljycea.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yj20258888.top/Article/details/gtwhgsudvr.html

[M05] 设置退出码
来源：http://dali.ywan-chungtsiang.top/Article/details/gteirztgle.html

Py:   sys.exit(1)
来源：http://dali.aizwys.cn/Article/details/gtfkfttitx.html

PHP:  exit(1);
来源：http://dali.nanxuanxn.top/Article/details/gtqqrcwsir.html

JS:   process.exit(1)
来源：http://dali.xylfe.cn/Article/details/gtguvjkavy.html

TS:   process.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gtkefsljkk.html

Java: System.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gthcmwsoty.html

Go:   os.Exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtveemmdvi.html

Ruby: exit 1
来源：http://dali.zycfv.cn/Article/details/gtlwkqjcit.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.wangshuangyany.cn/Article/details/gtfkpbcywm.html

[M06] 向标准错误输出
来源：http://dali.gzhubu.top/Article/details/gtskltjjnh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cdnleiting.top/Article/details/gtxemjmhjs.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhixingplan.top/Article/details/gtujdhjkgd.html

JS:   console.error("err")
来源：http://dali.kuanghao11.cn/Article/details/gtiygqdhsx.html

TS:   console.error("err")
来源：http://dali.shuidangran.top/Article/details/gtqkvnkhfk.html

Java: System.err.println("err")
来源：http://dali.0kj1m.cn/Article/details/gtlxbnidhh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgwppkbhw.html

Ruby: warn "err"
来源：http://dali.wangdashe.top/Article/details/gtlxshiixg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gogol.net.cn/Article/details/gtlblrpysn.html

[M07] 判断是否为主入口
来源：http://dali.daxiang520.top/Article/details/gtyjroulty.html

Py:   if __name__ == "__main__":
来源：http://dali.jinqigfzy.top/Article/details/gtyeguolxi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.fengsongda.top/Article/details/gtntrxnujt.html

JS:   require.main === module
来源：http://dali.yongpay.top/Article/details/gtatmduqxf.html

TS:   require.main === module
来源：http://dali.tian-w.cn/Article/details/gtfbnnzlrp.html

Java: public static void main(String[] args)
来源：http://dali.yuxming.cn/Article/details/gtzqyvkdwt.html

Go:   func main()
来源：http://dali.kuanghao11.cn/Article/details/gtwilepmxr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.nanxuanxn.top/Article/details/gtxudirbiy.html

C#:   static void Main(string[] args)
来源：http://dali.tanke756.top/Article/details/gtcisdomeg.html

[M08] 获取系统与运行时信息
来源：http://dali.c1oappe.top/Article/details/gtlwpdriui.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpeeueoql.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.daria6918.cn/Article/details/gthvdxppme.html

JS:   process.platform;  process.version
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwvfcdjrc.html

TS:   process.platform;  process.version
来源：http://dali.pengpengdd.cyou/Article/details/gtdwjzwrat.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.tianlin.xyz/Article/details/gtplljcwox.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvrrgsvhn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.chenzaomai.com/Article/details/gtrkwdzvli.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cashguo.top/Article/details/gtswkqucum.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtvohnchyn.html

N. 数据结构与算法
来源：http://dali.gotoacloud.top/Article/details/gtzchxpukw.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtpuljpgkk.html

[N01] 二分查找（有序数组）
来源：http://dali.tanke756.top/Article/details/gtebbbfdyb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtvoxvncsy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.9152youxi.cn/Article/details/gtbmxworzf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cdnleiting.top/Article/details/gtxmqobvbv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenlongwang.top/Article/details/gtpiduuoax.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtzfydctrh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gtmpoilyym.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gtsgglqwjj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtfbujpvsv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yongpay.top/Article/details/gtnumwljsd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ppjwa.cn/Article/details/gtsoihtngj.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sxryk.cn/Article/details/gtxeffvlyw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xylfe.cn/Article/details/gtahmbcpfo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cucudq.cn/Article/details/gtevdwwsyz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ybcxt.top/Article/details/gtlndeokuj.html

Go:   slices.Sort(arr)
来源：http://dali.c1oappe.top/Article/details/gtakgtdjuu.html

Ruby: arr.sort
来源：http://dali.birdmap.top/Article/details/gtxwifrmbn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.pycfn.com/Article/details/gtxfoqqnfp.html

[N03] 快速排序（分治示例）
来源：http://dali.jianghu66.top/Article/details/gtwmhglpis.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.fzhhl.top/Article/details/gtpelaocww.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwrsmyahz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hfpthk.cn/Article/details/gtecexnmog.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.vqdsnc.cn/Article/details/gtaylnklcd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gaohongyu789.top/Article/details/gtwfphwcqd.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gaohongyu789.top/Article/details/gtiuedaqvy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ydzc1.top/Article/details/gtfxtguqdk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tian-w.cn/Article/details/gtlasmzkap.html

[N04] 斐波那契数列
来源：http://dali.yuanzhike.top/Article/details/gtmxiacgat.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yangfankeji.com/Article/details/gtvtxaqxdu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jlsjyb.cn/Article/details/gtxnsipwta.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj202588.top/Article/details/gtftxeuszo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hammf.cn/Article/details/gtwoilghxl.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yanxiufei.cn/Article/details/gtjzutheuj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.feifeiyinyue.top/Article/details/gttarzbwba.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gaohongyu789.top/Article/details/gtxnrqwvja.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gtelkfipfa.html

[N05] 最大公约数
来源：http://dali.9152youxi.cn/Article/details/gtjhlizdva.html

Py:   math.gcd(a, b)
来源：http://dali.yonumen.top/Article/details/gtnsowngqj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sweek.top/Article/details/gtfnrkdbax.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenjidiqi.icu/Article/details/gtsxwrtkgm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dianchejie.cn/Article/details/gtuallafuq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ydzc1.top/Article/details/gtotjlekib.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.tian-w.cn/Article/details/gtnqjduxrj.html

Ruby: a.gcd(b)
来源：http://dali.gaohongyu789.top/Article/details/gtfhtokarq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.fzhhl.top/Article/details/gteljchwpv.html

[N06] 判断回文字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwpfhfzcu.html

Py:   s == s[::-1]
来源：http://dali.cdnleiting.top/Article/details/gtrzykhlfg.html

PHP:  $s === strrev($s);
来源：http://dali.yueranfly.top/Article/details/gtxjjbjckn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yj202588.top/Article/details/gtfwzopsdc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gtgvpmidzn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xziqi.cn/Article/details/gtrxiesicw.html

Go:   // 双指针从两端比较
来源：http://dali.quarkkingdee.top/Article/details/gtafnjsrdp.html

Ruby: s == s.reverse
来源：http://dali.cheryme.top/Article/details/gtsmxowaao.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.daxiang520.top/Article/details/gtvexwdqqz.html

[N07] 两数之和（返回下标）
来源：http://dali.zhiwuduotai.top/Article/details/gtdbzvsjtj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.pengpengdd.cyou/Article/details/gthjvxtunq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xuanzx.com/Article/details/gtmijjiekl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xuetiantiany.cn/Article/details/gtsowqrurt.html

TS:   // 手写 Map<string, number>
来源：http://dali.nanxuanxn.top/Article/details/gtozsyzxjh.html

Java: // 手写 HashMap
来源：http://dali.tanke756.top/Article/details/gtqsyglrrr.html

Go:   // 手写 map[int]int
来源：http://dali.cucudq.cn/Article/details/gtkqllwoeh.html

Ruby: // 手写 Hash
来源：http://dali.gotoacloud.top/Article/details/gtgxxsovow.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jlsjyb.cn/Article/details/gtokkihuzf.html

[N08] 生成全排列
来源：http://dali.yj202588.top/Article/details/gtaneylkgw.html

Py:   itertools.permutations(arr)
来源：http://dali.aibaodan.cn/Article/details/gteudsnktu.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gtfnpjjmqq.html

JS:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gtvjbnndem.html

TS:   // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gtlzzjhhkq.html

Java: // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gtpvcxbstt.html

Go:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gtlopokksr.html

Ruby: arr.permutation.to_a
来源：http://dali.guannengcc.top/Article/details/gtmxhtuigr.html

C#:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gthubrxwsv.html

[N09] 栈与队列
来源：http://dali.ydzc1.top/Article/details/gtgbnyhqho.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ybcxt.top/Article/details/gtdigryjrd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xuanzx.com/Article/details/gtzhbifedi.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoevwusym.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hammf.cn/Article/details/gtawoumuiu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.gaohongyu789.top/Article/details/gtwxxeuaws.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinqigfzy.top/Article/details/gtrrtmznsw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gtpuyubayt.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xylfe.cn/Article/details/gtehmrynzy.html

[N10] 链表节点定义
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxcywkbbe.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.andypj.xyz/Article/details/gtfsppelhx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.havefunace.top/Article/details/gtybbnikpc.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cheryme.top/Article/details/gtlqkfwpvd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.nanxuanxn.top/Article/details/gtmjkkmsix.html

Java: class Node { int v; Node next; }
来源：http://dali.xziqi.cn/Article/details/gtsofokpml.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.tian-w.cn/Article/details/gtcyhohpiv.html


<!-- 参考信息 -->