代发 wailian999

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hnqzz.top/Article/details/gt2fwvnmvkj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.pengpengdd.cyou/Article/details/gt2eyiaaqao.html

[K04] 读取 JSON 文件
来源：http://dali.aibaodan.cn/Article/details/gt2pccvmqrg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.aizwys.cn/Article/details/gt2okymlofx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yonumen.top/Article/details/gt2kjejpbrc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guannengcc.top/Article/details/gt2cymjfpxq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2jjswhihn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hammf.cn/Article/details/gt2gnlknitq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cheryme.top/Article/details/gt2keujsghs.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.dianchejie.cn/Article/details/gt2wdlhvlpo.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yueranfly.top/Article/details/gt2nsppripo.html

[K05] 深拷贝对象
来源：http://dali.vqdsnc.cn/Article/details/gt2exvzshiy.html

Py:   copy.deepcopy(obj)
来源：http://dali.xuanzx.com/Article/details/gt2vdksmogn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xziqi.cn/Article/details/gt2czxwvxhm.html

JS:   structuredClone(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2tpgugsmy.html

TS:   structuredClone(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wiexjlax.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xziqi.cn/Article/details/gt2earprzdp.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hnxiangtu.top/Article/details/gt2bowroflc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhengqikj.top/Article/details/gt2mtbrdkob.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhixingplan.top/Article/details/gt2kfrczquv.html

[K06] 解析 URL 查询串
来源：http://dali.kuanghao11.cn/Article/details/gt2trnywjdw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.9152youxi.cn/Article/details/gt2iuzyolti.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.mhx1999.top/Article/details/gt2nowcsuub.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jiagoushi.top/Article/details/gt2pxofqgeg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.dashuyun.cn/Article/details/gt2xorleugm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fadrvkxg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gt2scidxlyf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2taesdmzk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gt2lpwzngdo.html

[K07] 进制转换
来源：http://dali.sysykeji.top/Article/details/gt2thcaletw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gt2mrafcdjo.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.aibaodan.cn/Article/details/gt2hjgfkdly.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gt2owsbcpjh.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gt2jnoawrih.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gt2kgatjgwq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hywenlv.cn/Article/details/gt2sysxmqcj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.aizwys.cn/Article/details/gt2kcvfllbx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gt2xejlkqmu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ivvv.top/Article/details/gt2bpsntkxf.html

Py:   pickle.dumps(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2nfrnddku.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhongyouzk.top/Article/details/gt2rlgqqonr.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.daria6918.cn/Article/details/gt2cvgjulma.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jyoumei.cn/Article/details/gt2kcwscatv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.andypj.xyz/Article/details/gt2ubokhjro.html

Go:   encoding/gob
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ufqtcytz.html

Ruby: Marshal.dump(obj)
来源：http://dali.xuanzx.com/Article/details/gt2hmtxeqql.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.aizwys.cn/Article/details/gt2wkhkupgk.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2gmtzinxy.html

L. 网络请求
来源：http://dali.ehwqpu.com/Article/details/gt2ybxfmbod.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2vnorbzvw.html

[L01] 发送 GET 请求
来源：http://dali.gzhubu.top/Article/details/gt2jmwdaiaj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.kuanghao11.cn/Article/details/gt2yajdwmir.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shangyingyoupin.top/Article/details/gt2stykejdc.html

JS:   await fetch(url)
来源：http://dali.nwbrower.top/Article/details/gt2ksmvvoor.html

TS:   await fetch(url)
来源：http://dali.xinyue.icu/Article/details/gt2zrrhfgnr.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hammf.cn/Article/details/gt2prmnxulb.html

Go:   resp, err := http.Get(url)
来源：http://dali.haohaochexian.top/Article/details/gt2xdzxfckh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hammf.cn/Article/details/gt2tajhipxt.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.guowangkeji.top/Article/details/gt2vydgzzcq.html

[L02] 发送 POST JSON
来源：http://dali.zhiwuduotai.top/Article/details/gt2dwjojdsn.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yvedp.cn/Article/details/gt2napzqjfx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hywenlv.cn/Article/details/gt2hnkdqnox.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lwknzkon.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qmmgyhvn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.iojbl.cn/Article/details/gt2qhcfprsd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sxryk.cn/Article/details/gt2itbflzfi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yanxiufei.cn/Article/details/gt2ycfjmnng.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sysykeji.top/Article/details/gt2yesupshg.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkyicbx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yj202588.top/Article/details/gt2znrebbkp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sufxvd.cn/Article/details/gt2zxrljzmw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cdnleiting.top/Article/details/gt2hfefpwlt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daxiang520.top/Article/details/gt2gfuaouax.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sufxvd.cn/Article/details/gt2jatiewlr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.pengpengdd.cyou/Article/details/gt2kdtbqfsj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gaohongyu789.top/Article/details/gt2opvztjvr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yangfankeji.com/Article/details/gt2pzgzmtzg.html

[L04] 设置超时
来源：http://dali.hnqzz.top/Article/details/gt2ydfjpuxk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cheryme.top/Article/details/gt2kuaapvqq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.dashuyun.cn/Article/details/gt2czihfsua.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.svipenyu.cn/Article/details/gt2awtoqgqq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pycfn.com/Article/details/gt2hlthtuka.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jltjqgor.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.guowangkeji.top/Article/details/gt2pbymnvsw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sweek.top/Article/details/gt2uyvtomlu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jlsjyb.cn/Article/details/gt2esvbskeh.html

[L05] 上传文件（multipart）
来源：http://dali.zhiwuduotai.top/Article/details/gt2epmaoaoh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nanxinkj.top/Article/details/gt2jcuqnruj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kidzmgvi.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hfpthk.cn/Article/details/gt2polnokbi.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gaohongyu789.top/Article/details/gt2mcobyvye.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hfpthk.cn/Article/details/gt2xtkkhizc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2euzsrvws.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sufxvd.cn/Article/details/gt2eyrhubov.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cqqwz.cn/Article/details/gt2zsobrcqo.html

[L06] 解析响应为 JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ahlukkse.html

Py:   resp.json()
来源：http://dali.jqgfzy.top/Article/details/gt2hatucbta.html

PHP:  json_decode($body, true);
来源：http://dali.mhx1999.top/Article/details/gt2wlmoamqi.html

JS:   await resp.json()
来源：http://dali.cucudq.cn/Article/details/gt2mdnqifhf.html

TS:   await resp.json()
来源：http://dali.hfpthk.cn/Article/details/gt2ohtcdiin.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jlsjyb.cn/Article/details/gt2kdgmohwb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xylfe.cn/Article/details/gt2gukqrbmi.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jlsjyb.cn/Article/details/gt2hzpgmnpq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iidnhkav.html

[L07] 处理 HTTP 状态码
来源：http://dali.9152youxi.cn/Article/details/gt2xdnmxzrj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cdnleiting.top/Article/details/gt2twevdgyk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jqgfzy.top/Article/details/gt2mcyywhpi.html

JS:   resp.ok;  resp.status
来源：http://dali.hywenlv.cn/Article/details/gt2xyhnbokn.html

TS:   resp.ok;  resp.status
来源：http://dali.pengpengdd.cyou/Article/details/gt2zxvuvlss.html

Java: resp.statusCode()
来源：http://dali.xuanzx.com/Article/details/gt2zgkgljjo.html

Go:   resp.StatusCode
来源：http://dali.ppjwa.cn/Article/details/gt2akhmwfbe.html

Ruby: resp.code.to_i
来源：http://dali.yj202588.top/Article/details/gt2octpwwct.html

C#:   (int)resp.StatusCode
来源：http://dali.0kj1m.cn/Article/details/gt2thstuorj.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2akxkjrqc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xuetiantiany.cn/Article/details/gt2pgtcxiuq.html

PHP:  curl_multi_init() 系列
来源：http://dali.cheryme.top/Article/details/gt2spoxfpqg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.havefunace.top/Article/details/gt2gadthgpa.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ilvlfyjq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gogol.net.cn/Article/details/gt2xcouozeq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shangyingyoupin.top/Article/details/gt2vptzphvt.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jianghu66.top/Article/details/gt2khvgwdcr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hnqzz.top/Article/details/gt2kygseeqf.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2ylxkgtoi.html

M. 命令行 / 进程 / 环境
来源：http://dali.yueranfly.top/Article/details/gt2ponuyehh.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2cegsgapb.html

[M01] 读取命令行参数
来源：http://dali.chenzaomai.com/Article/details/gt2czdnyvky.html

Py:   sys.argv[1:]
来源：http://dali.ybcxt.top/Article/details/gt2oysxfzqe.html

PHP:  $argv;  $argc;
来源：http://dali.ivvv.top/Article/details/gt2lgjxktyh.html

JS:   process.argv.slice(2)
来源：http://dali.svipenyu.cn/Article/details/gt2zykxzpjx.html

TS:   process.argv.slice(2)
来源：http://dali.bjfxy.top/Article/details/gt2irjynweo.html

Java: args 数组（main 方法参数）
来源：http://dali.dashuyun.cn/Article/details/gt2dtuvscna.html

Go:   os.Args[1:]
来源：http://dali.9152youxi.cn/Article/details/gt2kdvttvsr.html

Ruby: ARGV
来源：http://dali.xziqi.cn/Article/details/gt2yizqslqn.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ybcxt.top/Article/details/gt2kgxrgwtn.html

[M02] 读取环境变量
来源：http://dali.zhongyouzk.top/Article/details/gt2xxuyubym.html

Py:   os.environ.get("HOME")
来源：http://dali.yvedp.cn/Article/details/gt2pqjdnwlb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sysykeji.top/Article/details/gt2uxsifqwe.html

JS:   process.env.HOME
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nvpbroxu.html

TS:   process.env.HOME
来源：http://dali.yonumen.top/Article/details/gt2ecmandtv.html

Java: System.getenv("HOME")
来源：http://dali.wangdashe.top/Article/details/gt2neltcmhs.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.haohaochexian.top/Article/details/gt2jpodlunu.html

Ruby: ENV["HOME"]
来源：http://dali.nanxuanxn.top/Article/details/gt2gdznggqt.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hywenlv.cn/Article/details/gt2vqhjehwq.html

[M03] 执行外部命令
来源：http://dali.yvedp.cn/Article/details/gt2lgyzrlds.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tianlin.xyz/Article/details/gt2ucjsppfh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.chenlongwang.top/Article/details/gt2fsmlsncw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258.top/Article/details/gt2aauznguu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xziqi.cn/Article/details/gt2udqrtusa.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.redwolf501.top/Article/details/gt2jpthgvbg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sufxvd.cn/Article/details/gt2wumfguan.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.redwolf501.top/Article/details/gt2mfdjzueo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yj20258.top/Article/details/gt2nqjfbbjl.html

[M04] 获取当前工作目录
来源：http://dali.quarkkingdee.top/Article/details/gt2eulwvcnz.html

Py:   os.getcwd()
来源：http://dali.tanke756.top/Article/details/gt2vpkclcts.html

PHP:  getcwd();
来源：http://dali.sweek.top/Article/details/gt2wjtvfarq.html

JS:   process.cwd()
来源：http://dali.yj202588.top/Article/details/gt2penmowlo.html

TS:   process.cwd()
来源：http://dali.svipenyu.cn/Article/details/gt2mxnuennt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cqqwz.cn/Article/details/gt2sxypfzfv.html

Go:   os.Getwd()
来源：http://dali.iojbl.cn/Article/details/gt2ujkbktud.html

Ruby: Dir.pwd
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wkcdsqkd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yuxming.cn/Article/details/gt2wtuofvlm.html

[M05] 设置退出码
来源：http://dali.aizwys.cn/Article/details/gt2uavkjhdj.html

Py:   sys.exit(1)
来源：http://dali.tanke756.top/Article/details/gt2grladkjj.html

PHP:  exit(1);
来源：http://dali.smart0.xyz/Article/details/gt2nqzpsbxk.html

JS:   process.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gt2nzsbbfze.html

TS:   process.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vyxvorey.html

Java: System.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2fufkexao.html

Go:   os.Exit(1)
来源：http://dali.cheryme.top/Article/details/gt2igqouneq.html

Ruby: exit 1
来源：http://dali.jlsjyb.cn/Article/details/gt2uycqguif.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj20258888.top/Article/details/gt2mgjbzujr.html

[M06] 向标准错误输出
来源：http://dali.yvedp.cn/Article/details/gt2vpmhrall.html

Py:   print("err", file=sys.stderr)
来源：http://dali.snrcjt.cn/Article/details/gt2iokvjtsr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhiwuduotai.top/Article/details/gt2kraxiiyr.html

JS:   console.error("err")
来源：http://dali.316326.xyz/Article/details/gt2zgobkukc.html

TS:   console.error("err")
来源：http://dali.cqqwz.cn/Article/details/gt2jvilbsbe.html

Java: System.err.println("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vmlqdccd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.chenzaomai.com/Article/details/gt2jflblalz.html

Ruby: warn "err"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cmksxwin.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.chenzaomai.com/Article/details/gt2aqebraya.html

[M07] 判断是否为主入口
来源：http://dali.tian-w.cn/Article/details/gt2ycssgzsk.html

Py:   if __name__ == "__main__":
来源：http://dali.yueranfly.top/Article/details/gt2rrxnhfov.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yueranfly.top/Article/details/gt2hmixqgcn.html

JS:   require.main === module
来源：http://dali.jlsjyb.cn/Article/details/gt2eiaoojmz.html

TS:   require.main === module
来源：http://dali.cdnleiting.top/Article/details/gt2kxeivnit.html

Java: public static void main(String[] args)
来源：http://dali.hnxiangtu.top/Article/details/gt2kjzodprj.html

Go:   func main()
来源：http://dali.wangdashe.top/Article/details/gt2tpfwbrna.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nxvgoego.html

C#:   static void Main(string[] args)
来源：http://dali.birdmap.top/Article/details/gt2zyfmxyim.html

[M08] 获取系统与运行时信息
来源：http://dali.feifeiyinyue.top/Article/details/gt2ctgtggjr.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yongpay.top/Article/details/gt2cnrtvmko.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xuetiantiany.cn/Article/details/gt2tvjzbady.html

JS:   process.platform;  process.version
来源：http://dali.tanke756.top/Article/details/gt2qcpvhlvv.html

TS:   process.platform;  process.version
来源：http://dali.yuxming.cn/Article/details/gt2kmlseccr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vtweacsf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sweek.top/Article/details/gt2kayigbru.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.guannengcc.top/Article/details/gt2wzbjnzga.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.smart0.xyz/Article/details/gt2vjrmmshp.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2bffzgmvz.html

N. 数据结构与算法
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xkrmgaxe.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2puzryfmw.html

[N01] 二分查找（有序数组）
来源：http://dali.jqgfzy.top/Article/details/gt2pymjmwzy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mafnrpbt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gt2hngusyuu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.andypj.xyz/Article/details/gt2ipflpnlu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.316326.xyz/Article/details/gt2gnooflgt.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sysykeji.top/Article/details/gt2iqghwljo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2aqlnadbm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nanxuanxn.top/Article/details/gt2eettdivx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gt2owczmfaa.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dwcyctnu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigufen.top/Article/details/gt2gmqmnbkr.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.pycfn.com/Article/details/gt2iitmmour.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sufxvd.cn/Article/details/gt2jluzpphy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gotoacloud.top/Article/details/gt2cgntvvfi.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ouksuqkm.html

Go:   slices.Sort(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2quinqvjv.html

Ruby: arr.sort
来源：http://dali.yj20258888.top/Article/details/gt2deujcifn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yj202588.top/Article/details/gt2grgfirfp.html

[N03] 快速排序（分治示例）
来源：http://dali.wangdashe.top/Article/details/gt2hfwxpjgo.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gzhubu.top/Article/details/gt2gwlsengk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinqigufen.top/Article/details/gt2dbowddxl.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sweek.top/Article/details/gt2hdyszkom.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cqqwz.cn/Article/details/gt2vuoqmdcj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yueranfly.top/Article/details/gt2dlyronyf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jlsjyb.cn/Article/details/gt2kmwiztiy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hongshengwenyu.top/Article/details/gt2fqtecqpd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.aizwys.cn/Article/details/gt2vdzdrtjv.html

[N04] 斐波那契数列
来源：http://dali.cheryme.top/Article/details/gt2tpwuecsb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.dashuyun.cn/Article/details/gt2ljamzrgw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.haohaochexian.top/Article/details/gt2mozkkwdd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dianchejie.cn/Article/details/gt2rdexvrtv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenzaomai.com/Article/details/gt2tngmbocx.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cucudq.cn/Article/details/gt2wrvhdvhf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.nanxinkj.top/Article/details/gt2twmtqxxw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgoxlfbm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yuanzhike.top/Article/details/gt2wmnylbpo.html

[N05] 最大公约数
来源：http://dali.nwbrower.top/Article/details/gt2zuhuygap.html

Py:   math.gcd(a, b)
来源：http://dali.jqgfzy.top/Article/details/gt2niwnsqnt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jqgfzy.top/Article/details/gt2ysufmsnp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tianlin.xyz/Article/details/gt2uptyizfk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yanxiufei.cn/Article/details/gt2qmhhliuf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.guannengcc.top/Article/details/gt2cltwuhay.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hwsqeqgg.html

Ruby: a.gcd(b)
来源：http://dali.xziqi.cn/Article/details/gt2yfhbgelh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sysykeji.top/Article/details/gt2rgumheuq.html

[N06] 判断回文字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sinynenq.html

Py:   s == s[::-1]
来源：http://dali.wangshuangyany.cn/Article/details/gt2kbcnyufu.html

PHP:  $s === strrev($s);
来源：http://dali.bjfxy.top/Article/details/gt2zdkikwfp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gt2nmtwruqe.html

TS:   s === [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gt2rcoqedvc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yonumen.top/Article/details/gt2tmdtosih.html

Go:   // 双指针从两端比较
来源：http://dali.cqqwz.cn/Article/details/gt2jkpinder.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2snnaqdrt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.daxiang520.top/Article/details/gt2avpqtcvz.html

[N07] 两数之和（返回下标）
来源：http://dali.smart0.xyz/Article/details/gt2cjzhrvad.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yongpay.top/Article/details/gt2lhshoqzp.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.andypj.xyz/Article/details/gt2vvsouvna.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhiwuduotai.top/Article/details/gt2akxskmfp.html

TS:   // 手写 Map<string, number>
来源：http://dali.nanxinkj.top/Article/details/gt2svicnasg.html

Java: // 手写 HashMap
来源：http://dali.zycfv.cn/Article/details/gt2bkzyvsyq.html

Go:   // 手写 map[int]int
来源：http://dali.jqgufenzy.top/Article/details/gt2vmhlfhgq.html

Ruby: // 手写 Hash
来源：http://dali.zhongyouzk.top/Article/details/gt2ckswpqye.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gogol.net.cn/Article/details/gt2jrndxsjb.html

[N08] 生成全排列
来源：http://dali.meibo888.top/Article/details/gt2rvtoblka.html

Py:   itertools.permutations(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2kiosukfe.html

PHP:  // 手写递归交换
来源：http://dali.jqgfzy.top/Article/details/gt2qhsvoaih.html

JS:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gt2nthzqhnr.html

TS:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gt2fensnihz.html

Java: // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gt2mardpgpc.html

Go:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bbhgulwq.html

Ruby: arr.permutation.to_a
来源：http://dali.yuxming.cn/Article/details/gt2dqedqhtt.html

C#:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cmdqapzw.html

[N09] 栈与队列
来源：http://dali.yanxiufei.cn/Article/details/gt2wieozeiq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ivvv.top/Article/details/gt2stfhctrs.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ivvv.top/Article/details/gt2zhmpapah.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.pengpengdd.cyou/Article/details/gt2khdioekq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.guowangkeji.top/Article/details/gt2cpewkivi.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.gaohongyu789.top/Article/details/gt2makbpcpq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hnqzz.top/Article/details/gt2dtueyrih.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nanxuanxn.top/Article/details/gt2becwqjgx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fdpmtiye.html

[N10] 链表节点定义
来源：http://dali.kuanghao11.cn/Article/details/gt2hxajcoqo.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.snrcjt.cn/Article/details/gt2bfefhupb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.nanxuanxn.top/Article/details/gt2bxpwwuws.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yelzcszy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zycfv.cn/Article/details/gt2ohdsmhnx.html

Java: class Node { int v; Node next; }
来源：http://dali.sufxvd.cn/Article/details/gt2vpkzunfu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.daria6918.cn/Article/details/gt2vcnpfffa.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xuanzx.com/Article/details/gt2fzpivmuk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.daxiang520.top/Article/details/gt2ljznwsag.html

[N11] 二叉树中序遍历
来源：http://dali.cqqwz.cn/Article/details/gt2hzpuuwtw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pmirfczg.html

PHP:  // 手写递归函数
来源：http://dali.aibaodan.cn/Article/details/gt2rsrnzubp.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ivvv.top/Article/details/gt2qjzcmowo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shuidangran.top/Article/details/gt2jdiqqbed.html

Java: // 手写递归
来源：http://dali.zhixingplan.top/Article/details/gt2jykpjdaz.html

Go:   // 手写递归
来源：http://dali.smart0.xyz/Article/details/gt2floiekvj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.nwbrower.top/Article/details/gt2xgpncjjk.html

C#:   // 手写递归
来源：http://dali.316326.xyz/Article/details/gt2hwtslodz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jqgufenzy.top/Article/details/gt2rccdyrxs.html


<!-- 参考信息 -->