代发 wailian999

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ehwqpu.com/Article/details/gtddjsxvrh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sufxvd.cn/Article/details/gtzebzmxby.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yonumen.top/Article/details/gtxfaqgmgp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yj20258.top/Article/details/gthofhoggz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.meibo888.top/Article/details/gtwjxrxyfz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nanxinkj.top/Article/details/gtnnldyrlb.html

[K04] 读取 JSON 文件
来源：http://dali.jinqigufen.top/Article/details/gtkcpqkypj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.daxiang520.top/Article/details/gtkvepcgmt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.svipenyu.cn/Article/details/gtjwsjunwi.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tanke756.top/Article/details/gtgfawvjhb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhoulong.xyz/Article/details/gtmfqzepkg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hnqzz.top/Article/details/gtqwjkpwiq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yangfankeji.com/Article/details/gtriieaxrv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cqqwz.cn/Article/details/gtnkuuqqdq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinqigfzy.top/Article/details/gthyjhstdr.html

[K05] 深拷贝对象
来源：http://dali.aizwys.cn/Article/details/gtfzovytkm.html

Py:   copy.deepcopy(obj)
来源：http://dali.daria6918.cn/Article/details/gtuwbxkxwy.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jiagoushi.top/Article/details/gtnrkmunsc.html

JS:   structuredClone(obj)
来源：http://dali.mhx1999.top/Article/details/gtuxtwaeai.html

TS:   structuredClone(obj)
来源：http://dali.xylfe.cn/Article/details/gtbnahyhrc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.gaohongyu789.top/Article/details/gtnqrjwfid.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xuanzx.com/Article/details/gthaqvbhca.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtooxyxroy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yanxiufei.cn/Article/details/gtmcseieea.html

[K06] 解析 URL 查询串
来源：http://dali.jiagoushi.top/Article/details/gtscplulga.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sxryk.cn/Article/details/gtgknncdgw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nwbrower.top/Article/details/gtyncqlnim.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnqzz.top/Article/details/gtiztthmgi.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.haohaochexian.top/Article/details/gtlciwukrg.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ivvv.top/Article/details/gtlhksebhu.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jqgufenzy.top/Article/details/gtatyotivn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.tanke756.top/Article/details/gtnzmsmhos.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.bjfxy.top/Article/details/gtnbvwtscr.html

[K07] 进制转换
来源：http://dali.c1oappe.top/Article/details/gtobhcwnuh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gthdtxgzem.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cdnleiting.top/Article/details/gtzcmwlpfv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gtsglvesri.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gtnbimpjez.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gtqesxttpn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jianghu66.top/Article/details/gtiorxjfgg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.fengsongda.top/Article/details/gtlfkqyoot.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.tanke756.top/Article/details/gtffhiwnvl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhengqikj.top/Article/details/gtgzijmcqh.html

Py:   pickle.dumps(obj)
来源：http://dali.shzxlz.cn/Article/details/gtrqlnwugf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xziqi.cn/Article/details/gtwbgteken.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.chenlongwang.top/Article/details/gtwswjasgr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.feifeiyinyue.top/Article/details/gtmammgvrf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hnqzz.top/Article/details/gtubxvmibc.html

Go:   encoding/gob
来源：http://dali.haohaochexian.top/Article/details/gtspcajvem.html

Ruby: Marshal.dump(obj)
来源：http://dali.tian-w.cn/Article/details/gtzmtsocok.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hongshengwenyu.top/Article/details/gthdoutuxa.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gttfcpfadv.html

L. 网络请求
来源：http://dali.ivvv.top/Article/details/gtlkgtlutt.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtiwnyyouw.html

[L01] 发送 GET 请求
来源：http://dali.fengsongda.top/Article/details/gtlwsswmgk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhiwuduotai.top/Article/details/gtznuoyjsa.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.quarkkingdee.top/Article/details/gtgrhqnzsf.html

JS:   await fetch(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtydwrkmbp.html

TS:   await fetch(url)
来源：http://dali.dianchejie.cn/Article/details/gtxgicytfz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhengqikj.top/Article/details/gtnejccprm.html

Go:   resp, err := http.Get(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaygnlfkl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.guannengcc.top/Article/details/gtaubxjovu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhixingplan.top/Article/details/gtlqigxzrn.html

[L02] 发送 POST JSON
来源：http://dali.yuxming.cn/Article/details/gtsdoboirj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.aibaodan.cn/Article/details/gtvmcbvocb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.iojbl.cn/Article/details/gtpwgcifli.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fengsongda.top/Article/details/gtuduipaus.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinghuilouyu.cn/Article/details/gtlkialvug.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jlsjyb.cn/Article/details/gtfikdhdmw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmzsulcnv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cashguo.top/Article/details/gtfqovzamo.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zdqjudy.top/Article/details/gtpnnzkxqk.html

[L03] 设置自定义请求头
来源：http://dali.yuxming.cn/Article/details/gtyihamdze.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yanxiufei.cn/Article/details/gtdwsoqlbi.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmfeyivms.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gzhubu.top/Article/details/gtedcrgdfy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkzgtnjzx.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hfpthk.cn/Article/details/gtuhempmgl.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yuxming.cn/Article/details/gthhpowfll.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hfpthk.cn/Article/details/gtfpvbsowz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.pengpengdd.cyou/Article/details/gtwvxrmwxx.html

[L04] 设置超时
来源：http://dali.zhengqikj.top/Article/details/gtlkhonfkj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gogol.net.cn/Article/details/gtbrwmtkyb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenzaomai.com/Article/details/gtdrumwkny.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shangyingyoupin.top/Article/details/gtxlykswyu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fzhhl.top/Article/details/gtrvkrmrwh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.wangdashe.top/Article/details/gtopykdyxa.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.quarkkingdee.top/Article/details/gthxruciao.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.bjfxy.top/Article/details/gtldeqizoy.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ydzc1.top/Article/details/gtgrppvajl.html

[L05] 上传文件（multipart）
来源：http://dali.jinqigufen.top/Article/details/gtzlodlkev.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sxryk.cn/Article/details/gtkaduddnu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.pengpengdd.cyou/Article/details/gturriwtvb.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqkvzhzpo.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.daxiang520.top/Article/details/gtriyvqcai.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xylfe.cn/Article/details/gtdnyiwgui.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhixingplan.top/Article/details/gtciejpokt.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.dianchejie.cn/Article/details/gteefqgflj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtitfwmvni.html

[L06] 解析响应为 JSON
来源：http://dali.zdqjudy.top/Article/details/gtbjmoziet.html

Py:   resp.json()
来源：http://dali.ydzc1.top/Article/details/gtzcobuofy.html

PHP:  json_decode($body, true);
来源：http://dali.hywenlv.cn/Article/details/gtyjlbkwkq.html

JS:   await resp.json()
来源：http://dali.daxiang520.top/Article/details/gtunecdlso.html

TS:   await resp.json()
来源：http://dali.wangdashe.top/Article/details/gtrhbmthry.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hongshengwenyu.top/Article/details/gtwiafrjpf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinqigfzy.top/Article/details/gteddoovsq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yuanzhike.top/Article/details/gtgieeycol.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gaohongyu789.top/Article/details/gthnfvuikh.html

[L07] 处理 HTTP 状态码
来源：http://dali.tanke756.top/Article/details/gtomrfgbzh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinqigufen.top/Article/details/gtthdrucvl.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.daxiang520.top/Article/details/gtoaeeypsf.html

JS:   resp.ok;  resp.status
来源：http://dali.hnqzz.top/Article/details/gtufwtklcz.html

TS:   resp.ok;  resp.status
来源：http://dali.zhiwuduotai.top/Article/details/gtwjjujprm.html

Java: resp.statusCode()
来源：http://dali.bjfxy.top/Article/details/gtisszsnsr.html

Go:   resp.StatusCode
来源：http://dali.fzhhl.top/Article/details/gtlbhemtmz.html

Ruby: resp.code.to_i
来源：http://dali.feifeiyinyue.top/Article/details/gtobttlumm.html

C#:   (int)resp.StatusCode
来源：http://dali.cqqwz.cn/Article/details/gtzlguoobl.html

[L08] 并发请求多个地址
来源：http://dali.jqgufenzy.top/Article/details/gtpxzfqbip.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cashguo.top/Article/details/gtjrtfzoty.html

PHP:  curl_multi_init() 系列
来源：http://dali.feifeiyinyue.top/Article/details/gtjorptqvp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daxiang520.top/Article/details/gtreacksgv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fzhhl.top/Article/details/gtyzicmefw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.snrcjt.cn/Article/details/gtfpfklbcy.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yanxiufei.cn/Article/details/gtmiawelkg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hammf.cn/Article/details/gtoqwwduun.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yuanzhike.top/Article/details/gtwnfzmyty.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtoldmtpyl.html

M. 命令行 / 进程 / 环境
来源：http://dali.haohaochexian.top/Article/details/gtuluuoqki.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtwlwjhsrf.html

[M01] 读取命令行参数
来源：http://dali.tian-w.cn/Article/details/gtnqkvrxyh.html

Py:   sys.argv[1:]
来源：http://dali.cashguo.top/Article/details/gtqoallllp.html

PHP:  $argv;  $argc;
来源：http://dali.pycfn.com/Article/details/gtnfuauvvh.html

JS:   process.argv.slice(2)
来源：http://dali.nwbrower.top/Article/details/gtydvdvqvf.html

TS:   process.argv.slice(2)
来源：http://dali.aibaodan.cn/Article/details/gtbcwtezih.html

Java: args 数组（main 方法参数）
来源：http://dali.zhongyouzk.top/Article/details/gtckfrbfhj.html

Go:   os.Args[1:]
来源：http://dali.yuxming.cn/Article/details/gtdamdwmic.html

Ruby: ARGV
来源：http://dali.tanke756.top/Article/details/gtdtuvdjmd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jqgufenzy.top/Article/details/gtkdpscezw.html

[M02] 读取环境变量
来源：http://dali.wangdashe.top/Article/details/gtuojcloqs.html

Py:   os.environ.get("HOME")
来源：http://dali.gogol.net.cn/Article/details/gtlutkpuxr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfzxenafi.html

JS:   process.env.HOME
来源：http://dali.cheryme.top/Article/details/gtutaqchbr.html

TS:   process.env.HOME
来源：http://dali.hnxiangtu.top/Article/details/gtebzgobyt.html

Java: System.getenv("HOME")
来源：http://dali.haohaochexian.top/Article/details/gtbzpifjxf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.fzhhl.top/Article/details/gthytbjdbq.html

Ruby: ENV["HOME"]
来源：http://dali.meibo888.top/Article/details/gtpwezuofh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenlongwang.top/Article/details/gtmtfbrodg.html

[M03] 执行外部命令
来源：http://dali.chenzaomai.com/Article/details/gtxpidsfss.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zdqjudy.top/Article/details/gtllkemqwk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsjegljjj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnxiangtu.top/Article/details/gtuqcskmzj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.feifeiyinyue.top/Article/details/gteocrqsjb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.aibaodan.cn/Article/details/gtuensnvdw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cqqwz.cn/Article/details/gtzlgxqtyq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.svipenyu.cn/Article/details/gtlfnobecn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tianlin.xyz/Article/details/gtgwcwdolp.html

[M04] 获取当前工作目录
来源：http://dali.hnqzz.top/Article/details/gtxffzpyxz.html

Py:   os.getcwd()
来源：http://dali.yj20258.top/Article/details/gtwjocohxe.html

PHP:  getcwd();
来源：http://dali.0kj1m.cn/Article/details/gtjqgrvmgq.html

JS:   process.cwd()
来源：http://dali.sufxvd.cn/Article/details/gtsyyfauts.html

TS:   process.cwd()
来源：http://dali.fengsongda.top/Article/details/gtmidiwfms.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hnqzz.top/Article/details/gthkycwell.html

Go:   os.Getwd()
来源：http://dali.dashuyun.cn/Article/details/gtqblvuhtg.html

Ruby: Dir.pwd
来源：http://dali.xinyue.icu/Article/details/gtimfxmbla.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.wangshuangyany.cn/Article/details/gtiybzrqyl.html

[M05] 设置退出码
来源：http://dali.jiagoushi.top/Article/details/gtarpwfcwz.html

Py:   sys.exit(1)
来源：http://dali.yongpay.top/Article/details/gtcpsxwjmz.html

PHP:  exit(1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtadaduhwu.html

JS:   process.exit(1)
来源：http://dali.tian-w.cn/Article/details/gtggkosqlc.html

TS:   process.exit(1)
来源：http://dali.fengsongda.top/Article/details/gtuclzagaf.html

Java: System.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gtcagmtkbg.html

Go:   os.Exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gtmsknbzdw.html

Ruby: exit 1
来源：http://dali.zhongyouzk.top/Article/details/gtqyvquvgt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shangyingyoupin.top/Article/details/gtcrhohgbf.html

[M06] 向标准错误输出
来源：http://dali.hammf.cn/Article/details/gtkarhxssy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.kuanghao11.cn/Article/details/gtyafjfjgk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.mhx1999.top/Article/details/gtjwxvmhfd.html

JS:   console.error("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtemvujqtz.html

TS:   console.error("err")
来源：http://dali.gaohongyu789.top/Article/details/gtjdggfclp.html

Java: System.err.println("err")
来源：http://dali.hammf.cn/Article/details/gtajyjtrkc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuqykjclo.html

Ruby: warn "err"
来源：http://dali.yangfankeji.com/Article/details/gtahphffaa.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yueranfly.top/Article/details/gtriggdcye.html

[M07] 判断是否为主入口
来源：http://dali.daria6918.cn/Article/details/gtxbfxmnjy.html

Py:   if __name__ == "__main__":
来源：http://dali.nwbrower.top/Article/details/gtlpjidqou.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.tianlin.xyz/Article/details/gtwsiwlwfu.html

JS:   require.main === module
来源：http://dali.aizwys.cn/Article/details/gtzzxrzaxl.html

TS:   require.main === module
来源：http://dali.cdnleiting.top/Article/details/gtqutcaafy.html

Java: public static void main(String[] args)
来源：http://dali.gotoacloud.top/Article/details/gtwsoemetg.html

Go:   func main()
来源：http://dali.jianghu66.top/Article/details/gtrclnyfie.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.vqdsnc.cn/Article/details/gtkzwbdvus.html

C#:   static void Main(string[] args)
来源：http://dali.xinyue.icu/Article/details/gtxflkeqjz.html

[M08] 获取系统与运行时信息
来源：http://dali.xziqi.cn/Article/details/gtpiiubgkn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhoulong.xyz/Article/details/gtgpvpccrc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yvedp.cn/Article/details/gtzhppwtbx.html

JS:   process.platform;  process.version
来源：http://dali.c1oappe.top/Article/details/gtbeiwttkm.html

TS:   process.platform;  process.version
来源：http://dali.ppjwa.cn/Article/details/gttlanmpsp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cucudq.cn/Article/details/gtmxsvwvod.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.c1oappe.top/Article/details/gtcwgoblzt.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.fzhhl.top/Article/details/gtgyxwnznt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.nanxinkj.top/Article/details/gtdgufhmeh.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtoipbxtal.html

N. 数据结构与算法
来源：http://dali.yj20258888.top/Article/details/gtlwcaxmsc.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtxeivoyfi.html

[N01] 二分查找（有序数组）
来源：http://dali.zhengqikj.top/Article/details/gtqpylyfyd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gthegypfoh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.smart0.xyz/Article/details/gtsxswouaw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ydzc1.top/Article/details/gttktwmkry.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258888.top/Article/details/gtqboozmmb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gtsewhsjix.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtrjkrlqlk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.vqdsnc.cn/Article/details/gtowzdjhdq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtfcjnkdeu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.andypj.xyz/Article/details/gthnnpcrew.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yvedp.cn/Article/details/gtlztyltnv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinghuilouyu.cn/Article/details/gthovcupru.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ybcxt.top/Article/details/gtfnncfkxj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuetiantiany.cn/Article/details/gtflaonxfj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ivvv.top/Article/details/gtubynqmkr.html

Go:   slices.Sort(arr)
来源：http://dali.ppjwa.cn/Article/details/gtbtjxyvpd.html

Ruby: arr.sort
来源：http://dali.wangshuangyany.cn/Article/details/gtonnzlixh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.redwolf501.top/Article/details/gtirwkhhon.html

[N03] 快速排序（分治示例）
来源：http://dali.hnxiangtu.top/Article/details/gtdtapmlyh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sysykeji.top/Article/details/gtccyfqohu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yonumen.top/Article/details/gtswjsnhgn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj202588.top/Article/details/gtlrtjlrvj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigufen.top/Article/details/gtbemqfrax.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sweek.top/Article/details/gtxjlkripb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhiwuduotai.top/Article/details/gtfomfqqia.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.quarkkingdee.top/Article/details/gtqhbhjirv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhoulong.xyz/Article/details/gtffggqpzc.html

[N04] 斐波那契数列
来源：http://dali.aizwys.cn/Article/details/gtnlkhkzvp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhongyouzk.top/Article/details/gtnyzltwkj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gtzlzujwha.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hongshengwenyu.top/Article/details/gthgaeizzm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtbennjyjk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.9152youxi.cn/Article/details/gtizexdpyg.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hysaishi.cn/Article/details/gtzlbouxrh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtjmbvakzj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.chenlongwang.top/Article/details/gtpnsqtbku.html

[N05] 最大公约数
来源：http://dali.316326.xyz/Article/details/gtxghpxxhn.html

Py:   math.gcd(a, b)
来源：http://dali.dashuyun.cn/Article/details/gthytevpuw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbesioszt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shzxlz.cn/Article/details/gtzsfziolr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.haohaochexian.top/Article/details/gtwdbxbpuj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cqqwz.cn/Article/details/gtgngsbtwj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.chenjidiqi.icu/Article/details/gtesxfehch.html

Ruby: a.gcd(b)
来源：http://dali.redwolf501.top/Article/details/gtvjgugdxn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xuetiantiany.cn/Article/details/gtnsugtwrt.html

[N06] 判断回文字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtfeagwrlk.html

Py:   s == s[::-1]
来源：http://dali.xylfe.cn/Article/details/gtydldpvap.html

PHP:  $s === strrev($s);
来源：http://dali.havefunace.top/Article/details/gtygbfbvnp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gtqfgphymf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gtxjskvzpg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.wangshuangyany.cn/Article/details/gtcpqqibck.html

Go:   // 双指针从两端比较
来源：http://dali.aizwys.cn/Article/details/gtfxhmyxbu.html

Ruby: s == s.reverse
来源：http://dali.tian-w.cn/Article/details/gtanybuxpr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.pengpengdd.cyou/Article/details/gtjeltjmaw.html

[N07] 两数之和（返回下标）
来源：http://dali.ivvv.top/Article/details/gtgyinujxo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gtteneolhi.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.aibaodan.cn/Article/details/gtxdlicokq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jlsjyb.cn/Article/details/gtxhqwjawv.html

TS:   // 手写 Map<string, number>
来源：http://dali.ehwqpu.com/Article/details/gtwcmchpki.html

Java: // 手写 HashMap
来源：http://dali.xuanzx.com/Article/details/gtjuvwrsbr.html

Go:   // 手写 map[int]int
来源：http://dali.zdqjudy.top/Article/details/gtnbovfltx.html

Ruby: // 手写 Hash
来源：http://dali.hfpthk.cn/Article/details/gtponqmkfw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.c1oappe.top/Article/details/gtteqpmxgw.html

[N08] 生成全排列
来源：http://dali.cucudq.cn/Article/details/gtjtumutrq.html

Py:   itertools.permutations(arr)
来源：http://dali.yangfankeji.com/Article/details/gtdtqguhnt.html

PHP:  // 手写递归交换
来源：http://dali.c1oappe.top/Article/details/gtndohhtzw.html

JS:   // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gtgmtuudzt.html

TS:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gtopfduinv.html

Java: // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtbgzqqvks.html

Go:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gtmcsflbem.html

Ruby: arr.permutation.to_a
来源：http://dali.ybcxt.top/Article/details/gtlmluwokn.html

C#:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtzhacbeop.html

[N09] 栈与队列
来源：http://dali.sweek.top/Article/details/gtrcgjeykh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yongpay.top/Article/details/gtsaxdfldn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gtlsjdxkfq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.fzhhl.top/Article/details/gtyqmjwxac.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cqqwz.cn/Article/details/gtbzrwtxeu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yanxiufei.cn/Article/details/gtlyttxphl.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xinyue.icu/Article/details/gtzamezkcj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.0kj1m.cn/Article/details/gtxltgivex.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmnxvjqo.html

[N10] 链表节点定义
来源：http://dali.nanxinkj.top/Article/details/gtvibpmbkc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gotoacloud.top/Article/details/gtooxcsgzy.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sxryk.cn/Article/details/gtjcivggxl.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.iojbl.cn/Article/details/gtjgnhctbu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.haohaochexian.top/Article/details/gtzskdszdk.html

Java: class Node { int v; Node next; }
来源：http://dali.ehwqpu.com/Article/details/gtfogjouhl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ivvv.top/Article/details/gtwfyetupj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.9152youxi.cn/Article/details/gtdbxntuul.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.mhx1999.top/Article/details/gtpjorcych.html

[N11] 二叉树中序遍历
来源：http://dali.daxiang520.top/Article/details/gtqhczbbyo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.kuanghao11.cn/Article/details/gtjotwcdsm.html

PHP:  // 手写递归函数
来源：http://dali.quarkkingdee.top/Article/details/gtcvfmgxja.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.quarkkingdee.top/Article/details/gtbhwbhqes.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenlongwang.top/Article/details/gtkpacmsgv.html

Java: // 手写递归
来源：http://dali.jqgufenzy.top/Article/details/gtrcwqbfup.html


<!-- 参考信息 -->