代发 wailian999

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.quarkkingdee.top/Article/details/gtmvahttmk.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.meibo888.top/Article/details/gtbptyttwo.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.quarkkingdee.top/Article/details/gtmnkrjnlp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.fengsongda.top/Article/details/gtobzymixl.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnqzz.top/Article/details/gtsfukxebg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.svipenyu.cn/Article/details/gtlleitxcl.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.havefunace.top/Article/details/gtjlixugxh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.c1oappe.top/Article/details/gthtrstdmm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.redwolf501.top/Article/details/gtadqkojgj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hongshengwenyu.top/Article/details/gtrygjorwx.html

[K04] 读取 JSON 文件
来源：http://dali.nanxuanxn.top/Article/details/gtctvcghds.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hammf.cn/Article/details/gticruqjml.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yuxming.cn/Article/details/gtzdzbxqow.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhoulong.xyz/Article/details/gtgnqiajkl.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gteapptjnb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.mhx1999.top/Article/details/gtlzwwkscf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhixingplan.top/Article/details/gtijxeaqkh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.meibo888.top/Article/details/gtvcfenjng.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.c1oappe.top/Article/details/gtiflmwxuz.html

[K05] 深拷贝对象
来源：http://dali.wangshuangyany.cn/Article/details/gteizzwrhl.html

Py:   copy.deepcopy(obj)
来源：http://dali.hammf.cn/Article/details/gtmuckayga.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhixingplan.top/Article/details/gtwetqykhd.html

JS:   structuredClone(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gttmuytlhi.html

TS:   structuredClone(obj)
来源：http://dali.guowangkeji.top/Article/details/gtlblzleza.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.birdmap.top/Article/details/gttqkvvaox.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gotoacloud.top/Article/details/gtvbrgwzba.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sufxvd.cn/Article/details/gtbuewhpcg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.tanke756.top/Article/details/gtdrtlcicw.html

[K06] 解析 URL 查询串
来源：http://dali.yonumen.top/Article/details/gtvkwsdupf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hnqzz.top/Article/details/gtqkbgbofm.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cucudq.cn/Article/details/gtvnjdsahs.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.dianchejie.cn/Article/details/gtuloiltwr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aibaodan.cn/Article/details/gtehdpxyct.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.daxiang520.top/Article/details/gtjletcugt.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gtgbacvrmq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gttzfqpndr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.quarkkingdee.top/Article/details/gtahazzghh.html

[K07] 进制转换
来源：http://dali.xinyue.icu/Article/details/gtgtyxeurt.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ivvv.top/Article/details/gtwzogodun.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sweek.top/Article/details/gtcthksdmd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gtqcckqytt.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtgsrghldg.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gtmtocqudf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sysykeji.top/Article/details/gtdvxcqipe.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhengqikj.top/Article/details/gtmieczqmv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cashguo.top/Article/details/gtjocxzlao.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gaohongyu789.top/Article/details/gtbhxjqsqj.html

Py:   pickle.dumps(obj)
来源：http://dali.ppjwa.cn/Article/details/gtkfztttmh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.aibaodan.cn/Article/details/gthjiwsgte.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yongpay.top/Article/details/gtscszoltd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhixingplan.top/Article/details/gtuzivmtjr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gotoacloud.top/Article/details/gtgvagvbhu.html

Go:   encoding/gob
来源：http://dali.svipenyu.cn/Article/details/gtnvldnwye.html

Ruby: Marshal.dump(obj)
来源：http://dali.yonumen.top/Article/details/gtgdrrxmww.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yanxiufei.cn/Article/details/gtzsrednrd.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtliizmzlg.html

L. 网络请求
来源：http://dali.shzxlz.cn/Article/details/gtupuyoylz.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwhuamtrc.html

[L01] 发送 GET 请求
来源：http://dali.yanxiufei.cn/Article/details/gtfemsryqn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.nwbrower.top/Article/details/gtavtxturi.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ehwqpu.com/Article/details/gtgbjumfjd.html

JS:   await fetch(url)
来源：http://dali.gzhubu.top/Article/details/gtrjsuiryo.html

TS:   await fetch(url)
来源：http://dali.zhixingplan.top/Article/details/gtnfuncsgi.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ywan-chungtsiang.top/Article/details/gttyleplpv.html

Go:   resp, err := http.Get(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gttbnjwmue.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.aibaodan.cn/Article/details/gtljqkduxj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.9152youxi.cn/Article/details/gtufrrlqfm.html

[L02] 发送 POST JSON
来源：http://dali.xziqi.cn/Article/details/gtrzkmbcws.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yvedp.cn/Article/details/gtsevdivyj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gogol.net.cn/Article/details/gttywkdxxi.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yueranfly.top/Article/details/gtsuautoat.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daxiang520.top/Article/details/gtqtmwlnlo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xuanzx.com/Article/details/gtuzsnwrne.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yonumen.top/Article/details/gtekaytvdp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.vqdsnc.cn/Article/details/gtooxhzivx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jlsjyb.cn/Article/details/gtftkblrjd.html

[L03] 设置自定义请求头
来源：http://dali.daria6918.cn/Article/details/gtastswoin.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.pycfn.com/Article/details/gtagetzmwi.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zycfv.cn/Article/details/gtinqpmzwo.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.feifeiyinyue.top/Article/details/gtetuuivbh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.0kj1m.cn/Article/details/gtmjuzrxii.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinghuilouyu.cn/Article/details/gtjsjpeojb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzsdodmrn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.mhx1999.top/Article/details/gtuaejwrpp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gtegonrcxl.html

[L04] 设置超时
来源：http://dali.c1oappe.top/Article/details/gtvmsomibg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ehwqpu.com/Article/details/gtklnxxwpl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.nanxuanxn.top/Article/details/gthrnlbloz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangshuangyany.cn/Article/details/gtjqvwtbve.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sufxvd.cn/Article/details/gthzagpztx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhengqikj.top/Article/details/gtepalkxdd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gogol.net.cn/Article/details/gtthbuzqra.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gtgzytenqg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenzaomai.com/Article/details/gtcmgrljrb.html

[L05] 上传文件（multipart）
来源：http://dali.pengpengdd.cyou/Article/details/gtcozppkkb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.pengpengdd.cyou/Article/details/gtbxcxmolj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.havefunace.top/Article/details/gtkjenpnkj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gotoacloud.top/Article/details/gtodcowayg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yueranfly.top/Article/details/gthmaeqdrg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.bjfxy.top/Article/details/gtswwriwlv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.wangshuangyany.cn/Article/details/gtasdbeaij.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gogol.net.cn/Article/details/gtjthskkrr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtkanwnqvl.html

[L06] 解析响应为 JSON
来源：http://dali.zdqjudy.top/Article/details/gtbqogpeaq.html

Py:   resp.json()
来源：http://dali.hnxiangtu.top/Article/details/gtkevglpic.html

PHP:  json_decode($body, true);
来源：http://dali.vqdsnc.cn/Article/details/gtmoutkass.html

JS:   await resp.json()
来源：http://dali.haohaochexian.top/Article/details/gtcifvrbmk.html

TS:   await resp.json()
来源：http://dali.xuetiantiany.cn/Article/details/gtfsvedyuy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gtcpluslut.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hfpthk.cn/Article/details/gtugcfjpnf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.aizwys.cn/Article/details/gtqbbnayap.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.birdmap.top/Article/details/gtdqzrbqjz.html

[L07] 处理 HTTP 状态码
来源：http://dali.jiagoushi.top/Article/details/gtziwcqokh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hfpthk.cn/Article/details/gtrvdhjlxj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.smart0.xyz/Article/details/gtbpjitnwe.html

JS:   resp.ok;  resp.status
来源：http://dali.cashguo.top/Article/details/gtugqixdcv.html

TS:   resp.ok;  resp.status
来源：http://dali.shangyingyoupin.top/Article/details/gtwuytqpkv.html

Java: resp.statusCode()
来源：http://dali.gogol.net.cn/Article/details/gtmjimepmm.html

Go:   resp.StatusCode
来源：http://dali.yangfankeji.com/Article/details/gthgyaxrne.html

Ruby: resp.code.to_i
来源：http://dali.tian-w.cn/Article/details/gtfwixqqis.html

C#:   (int)resp.StatusCode
来源：http://dali.zdqjudy.top/Article/details/gtozruvnam.html

[L08] 并发请求多个地址
来源：http://dali.jyoumei.cn/Article/details/gtsbleuhpj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhixingplan.top/Article/details/gthrplybxv.html

PHP:  curl_multi_init() 系列
来源：http://dali.hfpthk.cn/Article/details/gtlatyijgg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gotoacloud.top/Article/details/gtphxswipx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ybcxt.top/Article/details/gtcbcmapeh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cashguo.top/Article/details/gtszxqfjcw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hnxiangtu.top/Article/details/gtnqapnbbd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jlsjyb.cn/Article/details/gtfasttovr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gtkzxwgfug.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnhlplitq.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgernfsbw.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtmlnbupff.html

[M01] 读取命令行参数
来源：http://dali.nanxinkj.top/Article/details/gtflrjxsas.html

Py:   sys.argv[1:]
来源：http://dali.quarkkingdee.top/Article/details/gtildnbmry.html

PHP:  $argv;  $argc;
来源：http://dali.guannengcc.top/Article/details/gtxhgiaqyf.html

JS:   process.argv.slice(2)
来源：http://dali.hongshengwenyu.top/Article/details/gtwvqriyhr.html

TS:   process.argv.slice(2)
来源：http://dali.bjfxy.top/Article/details/gtqghnelus.html

Java: args 数组（main 方法参数）
来源：http://dali.aizwys.cn/Article/details/gtsczvczlv.html

Go:   os.Args[1:]
来源：http://dali.yonumen.top/Article/details/gtnwmxrcpf.html

Ruby: ARGV
来源：http://dali.dashuyun.cn/Article/details/gtsjupiher.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj20258.top/Article/details/gtcfmjtxav.html

[M02] 读取环境变量
来源：http://dali.gogol.net.cn/Article/details/gtbeilevbb.html

Py:   os.environ.get("HOME")
来源：http://dali.zycfv.cn/Article/details/gtshbsyszl.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cheryme.top/Article/details/gtwhfyaucv.html

JS:   process.env.HOME
来源：http://dali.iojbl.cn/Article/details/gtrxdekpef.html

TS:   process.env.HOME
来源：http://dali.wangshuangyany.cn/Article/details/gtfhrkyrmh.html

Java: System.getenv("HOME")
来源：http://dali.zhengqikj.top/Article/details/gtkrawjlpy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.birdmap.top/Article/details/gtqvmilgxl.html

Ruby: ENV["HOME"]
来源：http://dali.zycfv.cn/Article/details/gtafxcduab.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yvedp.cn/Article/details/gtudcbcryu.html

[M03] 执行外部命令
来源：http://dali.zhiwuduotai.top/Article/details/gtrjbhhhcj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.mhx1999.top/Article/details/gtnrtxtgal.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.snrcjt.cn/Article/details/gtklgfuict.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigfzy.top/Article/details/gtcnybnwvz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zdqjudy.top/Article/details/gtwwuwrkke.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ybcxt.top/Article/details/gtexjrjobo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.haohaochexian.top/Article/details/gtfhoummzf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yanxiufei.cn/Article/details/gtrxkvvwqr.html

C#:   Process.Start("ls", "-l");
来源：http://dali.kuanghao11.cn/Article/details/gtjlnlovzj.html

[M04] 获取当前工作目录
来源：http://dali.birdmap.top/Article/details/gtqpraprdl.html

Py:   os.getcwd()
来源：http://dali.quarkkingdee.top/Article/details/gtfwplppxf.html

PHP:  getcwd();
来源：http://dali.zhiwuduotai.top/Article/details/gtarjmmerm.html

JS:   process.cwd()
来源：http://dali.daxiang520.top/Article/details/gtafznlvdm.html

TS:   process.cwd()
来源：http://dali.chenzaomai.com/Article/details/gthoqnndkp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xylfe.cn/Article/details/gtnkqjrucz.html

Go:   os.Getwd()
来源：http://dali.yueranfly.top/Article/details/gtwbxsvrsu.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gtdozhbymd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.kuanghao11.cn/Article/details/gtdpffhpnb.html

[M05] 设置退出码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuuwjyhkn.html

Py:   sys.exit(1)
来源：http://dali.hammf.cn/Article/details/gttbjoscny.html

PHP:  exit(1);
来源：http://dali.hongshengwenyu.top/Article/details/gticlafqbv.html

JS:   process.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtojwpgmfm.html

TS:   process.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtxhulpucb.html

Java: System.exit(1)
来源：http://dali.yueranfly.top/Article/details/gtwpnivljp.html

Go:   os.Exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtaxxddrwq.html

Ruby: exit 1
来源：http://dali.jiagoushi.top/Article/details/gtfmapsvay.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yongpay.top/Article/details/gtjjqjjbmu.html

[M06] 向标准错误输出
来源：http://dali.havefunace.top/Article/details/gtshxbohxr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.guowangkeji.top/Article/details/gtwdlvfwsp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yangfankeji.com/Article/details/gtyourrpjm.html

JS:   console.error("err")
来源：http://dali.tianlin.xyz/Article/details/gtkriierpb.html

TS:   console.error("err")
来源：http://dali.zhongyouzk.top/Article/details/gtuakgnwyi.html

Java: System.err.println("err")
来源：http://dali.ehwqpu.com/Article/details/gtlxxbquqm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.nwbrower.top/Article/details/gtthmicivi.html

Ruby: warn "err"
来源：http://dali.haohaochexian.top/Article/details/gtksxqmrpj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sysykeji.top/Article/details/gtyxempgso.html

[M07] 判断是否为主入口
来源：http://dali.316326.xyz/Article/details/gtqujdblws.html

Py:   if __name__ == "__main__":
来源：http://dali.yueranfly.top/Article/details/gtjmvoqiyt.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.pycfn.com/Article/details/gtrwlvmjik.html

JS:   require.main === module
来源：http://dali.hysaishi.cn/Article/details/gtptmvkdhn.html

TS:   require.main === module
来源：http://dali.shzxlz.cn/Article/details/gtmmnchnlw.html

Java: public static void main(String[] args)
来源：http://dali.dianchejie.cn/Article/details/gtoomvgqny.html

Go:   func main()
来源：http://dali.guannengcc.top/Article/details/gtjkuetnhh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hfpthk.cn/Article/details/gtszpgusow.html

C#:   static void Main(string[] args)
来源：http://dali.fengsongda.top/Article/details/gtmjzrrwyj.html

[M08] 获取系统与运行时信息
来源：http://dali.xylfe.cn/Article/details/gtpuofdomh.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xziqi.cn/Article/details/gtsgilqovv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cashguo.top/Article/details/gtzdunswuf.html

JS:   process.platform;  process.version
来源：http://dali.cucudq.cn/Article/details/gtfzradlrt.html

TS:   process.platform;  process.version
来源：http://dali.jyoumei.cn/Article/details/gtcjkgdvvk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnqzz.top/Article/details/gtqdurkcdh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.daxiang520.top/Article/details/gtmwtamihu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hysaishi.cn/Article/details/gtkuvhttez.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xuetiantiany.cn/Article/details/gteeztpxqm.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtfhovinrt.html

N. 数据结构与算法
来源：http://dali.sweek.top/Article/details/gtbkrbbylq.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtieysenqh.html

[N01] 二分查找（有序数组）
来源：http://dali.cheryme.top/Article/details/gtvtxajwbj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yvedp.cn/Article/details/gttquszfnf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.quarkkingdee.top/Article/details/gtucozndug.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hammf.cn/Article/details/gtowrknzhy.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.kuanghao11.cn/Article/details/gtsitpfpuq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtzmjtlmgd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.iojbl.cn/Article/details/gtpivkppgk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nanxuanxn.top/Article/details/gtflfdsena.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gtqvwhnbve.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zycfv.cn/Article/details/gtuzljlgqr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj202588.top/Article/details/gtpapefonu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hnqzz.top/Article/details/gtvfrvpasx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hfpthk.cn/Article/details/gtuzstyajf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ybcxt.top/Article/details/gtpmmrpysl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jlsjyb.cn/Article/details/gtpxfoeqnr.html

Go:   slices.Sort(arr)
来源：http://dali.nanxinkj.top/Article/details/gtsvnwljwv.html

Ruby: arr.sort
来源：http://dali.redwolf501.top/Article/details/gtzbhwoonf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yanxiufei.cn/Article/details/gthxuzlcpa.html

[N03] 快速排序（分治示例）
来源：http://dali.yonumen.top/Article/details/gtrgbxkqxu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xuetiantiany.cn/Article/details/gtmwgrhpgm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yanxiufei.cn/Article/details/gtnxblfbop.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cdnleiting.top/Article/details/gtipkeajqd.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxuanxn.top/Article/details/gtfnsfopit.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gtwaokylwg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.meibo888.top/Article/details/gtqqqxvfrh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yj20258.top/Article/details/gtqwlqlhlw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yongpay.top/Article/details/gtdavcgign.html

[N04] 斐波那契数列
来源：http://dali.cucudq.cn/Article/details/gteuqzctpv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zycfv.cn/Article/details/gtkaerxwss.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hnxiangtu.top/Article/details/gtzjjjuqsu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hysaishi.cn/Article/details/gtrnyacshf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.iojbl.cn/Article/details/gtlvecwumz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jqgfzy.top/Article/details/gtnbleqbpx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gtopakyeen.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.c1oappe.top/Article/details/gtkvruadhn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.redwolf501.top/Article/details/gtzxdeteau.html

[N05] 最大公约数
来源：http://dali.xuanzx.com/Article/details/gtqemxqdrc.html

Py:   math.gcd(a, b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmwqlvqlk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.guowangkeji.top/Article/details/gtxusmobrs.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zdqjudy.top/Article/details/gtpnapvgsq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gogol.net.cn/Article/details/gtqcybwhzs.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hysaishi.cn/Article/details/gtnbckyqva.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sufxvd.cn/Article/details/gteoubzqtw.html

Ruby: a.gcd(b)
来源：http://dali.hfpthk.cn/Article/details/gteoycuqzt.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hywenlv.cn/Article/details/gthkarecuo.html

[N06] 判断回文字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtzsaqnkry.html

Py:   s == s[::-1]
来源：http://dali.nanxinkj.top/Article/details/gtpwmeowdc.html

PHP:  $s === strrev($s);
来源：http://dali.hammf.cn/Article/details/gtmulnlkxc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtzhxwxccr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gtsclyhgvh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.tian-w.cn/Article/details/gtimgnvdat.html

Go:   // 双指针从两端比较
来源：http://dali.yj20258888.top/Article/details/gtdpqqdfeh.html

Ruby: s == s.reverse
来源：http://dali.tian-w.cn/Article/details/gtddizrobe.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hysaishi.cn/Article/details/gtwrrblxfe.html

[N07] 两数之和（返回下标）
来源：http://dali.sxryk.cn/Article/details/gtnnekiife.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shanyushiyangtech.top/Article/details/gtpjohhnfq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jqgfzy.top/Article/details/gtlmlvruqz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hfpthk.cn/Article/details/gtvbrimzvy.html

TS:   // 手写 Map<string, number>
来源：http://dali.cqqwz.cn/Article/details/gtthkmplkb.html

Java: // 手写 HashMap
来源：http://dali.pycfn.com/Article/details/gtisgiakrn.html

Go:   // 手写 map[int]int
来源：http://dali.havefunace.top/Article/details/gtqazawaad.html

Ruby: // 手写 Hash
来源：http://dali.cqqwz.cn/Article/details/gtohogcbfx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.snrcjt.cn/Article/details/gtzohopshn.html

[N08] 生成全排列
来源：http://dali.xuanzx.com/Article/details/gtmozmilas.html

Py:   itertools.permutations(arr)
来源：http://dali.xuanzx.com/Article/details/gtzadzzzxe.html

PHP:  // 手写递归交换
来源：http://dali.guannengcc.top/Article/details/gtsagtjnfg.html

JS:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gttbsjpdhv.html

TS:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gttsiqxqlu.html

Java: // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gtvxoonoia.html

Go:   // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtfjixdayv.html

Ruby: arr.permutation.to_a
来源：http://dali.nanxuanxn.top/Article/details/gtreyqwrzv.html

C#:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gtrgxajdwz.html

[N09] 栈与队列
来源：http://dali.fengsongda.top/Article/details/gtqffrqaph.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cucudq.cn/Article/details/gtrkkexlnz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.kuanghao11.cn/Article/details/gtfiqyykrh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.dianchejie.cn/Article/details/gthivetqti.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzzhyanyn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gtqydguudx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.c1oappe.top/Article/details/gtutzglywl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.mhx1999.top/Article/details/gtqzdefhde.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenjidiqi.icu/Article/details/gtvfhosjgq.html

[N10] 链表节点定义
来源：http://dali.0kj1m.cn/Article/details/gtadtvwhls.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yanxiufei.cn/Article/details/gtvfoyhkkf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.pengpengdd.cyou/Article/details/gtkahimzqm.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinqigufen.top/Article/details/gthwofxfda.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.pengpengdd.cyou/Article/details/gtrigvzqvp.html

Java: class Node { int v; Node next; }
来源：http://dali.sysykeji.top/Article/details/gtivjgjhhd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ydzc1.top/Article/details/gtlbtiphik.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jianghu66.top/Article/details/gtbmjhixlv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.andypj.xyz/Article/details/gtshtawkvr.html

[N11] 二叉树中序遍历
来源：http://dali.daxiang520.top/Article/details/gtmucnjgdb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yangfankeji.com/Article/details/gtnzepdhkq.html


<!-- 参考信息 -->