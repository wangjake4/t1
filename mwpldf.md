代发 wailian999

TS:   JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gt2kobvsnxc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zdqjudy.top/Article/details/gt2lcyfviqz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jqgufenzy.top/Article/details/gt2thmwjzqf.html

Ruby: JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gt2wxrhmygj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.tian-w.cn/Article/details/gt2mynqluix.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xkdtsvfl.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.pycfn.com/Article/details/gt2sztxnrqf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iudnyhvo.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2kupiagrn.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ttrpjqer.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.daria6918.cn/Article/details/gt2ykyusqxr.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.tianlin.xyz/Article/details/gt2rjhupoez.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ydzc1.top/Article/details/gt2ktxgscxw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shuidangran.top/Article/details/gt2zaxqljdx.html

[K04] 读取 JSON 文件
来源：http://dali.redwolf501.top/Article/details/gt2prbyzjry.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2wequjmpj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jiagoushi.top/Article/details/gt2tvtskuyv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgufenzy.top/Article/details/gt2kuhebvpm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sysykeji.top/Article/details/gt2evojfamg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shzxlz.cn/Article/details/gt2rovihhkv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cucudq.cn/Article/details/gt2ukfrllxi.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hammf.cn/Article/details/gt2swjyrrkh.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2vzkpezif.html

[K05] 深拷贝对象
来源：http://dali.shzxlz.cn/Article/details/gt2vaxunjod.html

Py:   copy.deepcopy(obj)
来源：http://dali.ivvv.top/Article/details/gt2ectajaki.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2memaaxnh.html

JS:   structuredClone(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2pglcnywr.html

TS:   structuredClone(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2tkpssfvw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xziqi.cn/Article/details/gt2cbqstfcs.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hongshengwenyu.top/Article/details/gt2offldmza.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhongyouzk.top/Article/details/gt2cjglpsne.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.quarkkingdee.top/Article/details/gt2xfcxcodl.html

[K06] 解析 URL 查询串
来源：http://dali.sysykeji.top/Article/details/gt2kbmnaxxm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tian-w.cn/Article/details/gt2daqwsyjw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ivvv.top/Article/details/gt2utctwmqq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guannengcc.top/Article/details/gt2atcmssbw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nwbrower.top/Article/details/gt2mlgvdrqq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hywenlv.cn/Article/details/gt2cakzjiah.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.aizwys.cn/Article/details/gt2btfljtrx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gt2iyngztfl.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gt2tvdyqzra.html

[K07] 进制转换
来源：http://dali.chenlongwang.top/Article/details/gt2kjbzyyaq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gt2jesskecd.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.wangshuangyany.cn/Article/details/gt2jjsevpma.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gt2ewusdjwi.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wrahvzkq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gt2yqqfjeiq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jiagoushi.top/Article/details/gt2pnuapdew.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jqgfzy.top/Article/details/gt2fartreep.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lttqaplf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhongyouzk.top/Article/details/gt2uoszhqox.html

Py:   pickle.dumps(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ofsijdep.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2asqlphsi.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xylfe.cn/Article/details/gt2dbrtdxju.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.nwbrower.top/Article/details/gt2obummudu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhoulong.xyz/Article/details/gt2qotmfjwe.html

Go:   encoding/gob
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oiiimwxh.html

Ruby: Marshal.dump(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2xtdgpbie.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ppjwa.cn/Article/details/gt2nxihfqhs.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2xeyivwvs.html

L. 网络请求
来源：http://dali.shuidangran.top/Article/details/gt2ppasswdn.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2bwnqhkkc.html

[L01] 发送 GET 请求
来源：http://dali.shuidangran.top/Article/details/gt2ckqwsotq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.daxiang520.top/Article/details/gt2olfxukdr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gotoacloud.top/Article/details/gt2yghfndgl.html

JS:   await fetch(url)
来源：http://dali.jinqigufen.top/Article/details/gt2ugrgtrnj.html

TS:   await fetch(url)
来源：http://dali.snrcjt.cn/Article/details/gt2pglpnxny.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gaohongyu789.top/Article/details/gt2ucwcgxck.html

Go:   resp, err := http.Get(url)
来源：http://dali.cheryme.top/Article/details/gt2edctwfza.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.smart0.xyz/Article/details/gt2tmqqjkev.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhoulong.xyz/Article/details/gt2ciwspezh.html

[L02] 发送 POST JSON
来源：http://dali.sysykeji.top/Article/details/gt2lateldzt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yuxming.cn/Article/details/gt2zqqoerxd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hongshengwenyu.top/Article/details/gt2jhncirhd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gsmfldgp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnxiangtu.top/Article/details/gt2hnylhbyf.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hywenlv.cn/Article/details/gt2hhofclta.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jktjjaom.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.svipenyu.cn/Article/details/gt2hgseunux.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.chenzaomai.com/Article/details/gt2ekvyrcvb.html

[L03] 设置自定义请求头
来源：http://dali.ppjwa.cn/Article/details/gt2hvsispln.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.havefunace.top/Article/details/gt2huxfopjs.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.tanke756.top/Article/details/gt2ebjoiygh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tanke756.top/Article/details/gt2lhucobhf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hfpthk.cn/Article/details/gt2tvfkayfm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.andypj.xyz/Article/details/gt2texcgfsz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.aizwys.cn/Article/details/gt2anffviaj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.daxiang520.top/Article/details/gt2swxarnbn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sysykeji.top/Article/details/gt2phvapoeq.html

[L04] 设置超时
来源：http://dali.wangshuangyany.cn/Article/details/gt2flefkwcl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hfpthk.cn/Article/details/gt2sqfzjllw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zdqjudy.top/Article/details/gt2rngjvvdp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yonumen.top/Article/details/gt2abrsgscx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hammf.cn/Article/details/gt2lacbopny.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xziqi.cn/Article/details/gt2qwcniuzq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.birdmap.top/Article/details/gt2fcvzbmvv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.iojbl.cn/Article/details/gt2krlyfimt.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zycfv.cn/Article/details/gt2ntntrwto.html

[L05] 上传文件（multipart）
来源：http://dali.feifeiyinyue.top/Article/details/gt2gjlwbmis.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.birdmap.top/Article/details/gt2dhfzxkvx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ehwqpu.com/Article/details/gt2rssesfbo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sufxvd.cn/Article/details/gt2fxomncoq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fxwocxcr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shuidangran.top/Article/details/gt2ofbjmhpm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gaohongyu789.top/Article/details/gt2acvbksof.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ybcxt.top/Article/details/gt2eypyqmso.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yj20258888.top/Article/details/gt2gzqatqta.html

[L06] 解析响应为 JSON
来源：http://dali.jqgfzy.top/Article/details/gt2eutyrabj.html

Py:   resp.json()
来源：http://dali.andypj.xyz/Article/details/gt2rjszgomz.html

PHP:  json_decode($body, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sezbyclh.html

JS:   await resp.json()
来源：http://dali.tianlin.xyz/Article/details/gt2ajlgblmm.html

TS:   await resp.json()
来源：http://dali.gzhubu.top/Article/details/gt2kwmlvirj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.fengsongda.top/Article/details/gt2fszqibuj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.gotoacloud.top/Article/details/gt2hflomfre.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj202588.top/Article/details/gt2omopevyh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yuanzhike.top/Article/details/gt2rybbqpst.html

[L07] 处理 HTTP 状态码
来源：http://dali.xuanzx.com/Article/details/gt2ykyuqagj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yvedp.cn/Article/details/gt2uobckyix.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.pycfn.com/Article/details/gt2gdgcjysk.html

JS:   resp.ok;  resp.status
来源：http://dali.zhoulong.xyz/Article/details/gt2hajrsiav.html

TS:   resp.ok;  resp.status
来源：http://dali.sysykeji.top/Article/details/gt2zpyvhrif.html

Java: resp.statusCode()
来源：http://dali.ehwqpu.com/Article/details/gt2xhjjhysx.html

Go:   resp.StatusCode
来源：http://dali.zhiwuduotai.top/Article/details/gt2selslwzp.html

Ruby: resp.code.to_i
来源：http://dali.sysykeji.top/Article/details/gt2ykdxkbxj.html

C#:   (int)resp.StatusCode
来源：http://dali.yj20258.top/Article/details/gt2rkxmdjvv.html

[L08] 并发请求多个地址
来源：http://dali.nanxuanxn.top/Article/details/gt2yvsptgrs.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.bjfxy.top/Article/details/gt2uoftvsqu.html

PHP:  curl_multi_init() 系列
来源：http://dali.nanxinkj.top/Article/details/gt2ownbdubv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rkxrbgam.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhengqikj.top/Article/details/gt2ucmtosbc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yuanzhike.top/Article/details/gt2ahcoxckd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cashguo.top/Article/details/gt2cmsopiri.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yonumen.top/Article/details/gt2bzrycyso.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.svipenyu.cn/Article/details/gt2bmkalrlx.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2zrmcidnp.html

M. 命令行 / 进程 / 环境
来源：http://dali.hammf.cn/Article/details/gt2pyljqocy.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2zdqnjyax.html

[M01] 读取命令行参数
来源：http://dali.sweek.top/Article/details/gt2lqwtcwfy.html

Py:   sys.argv[1:]
来源：http://dali.kuanghao11.cn/Article/details/gt2ujltrjci.html

PHP:  $argv;  $argc;
来源：http://dali.yuanzhike.top/Article/details/gt2ekarnwew.html

JS:   process.argv.slice(2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2nottfjcd.html

TS:   process.argv.slice(2)
来源：http://dali.yj20258.top/Article/details/gt2yirmmzhv.html

Java: args 数组（main 方法参数）
来源：http://dali.gaohongyu789.top/Article/details/gt2bjpxjazs.html

Go:   os.Args[1:]
来源：http://dali.hnxiangtu.top/Article/details/gt2kfzbxmio.html

Ruby: ARGV
来源：http://dali.dashuyun.cn/Article/details/gt2oycvhrra.html

C#:   args 数组（Main 方法参数）
来源：http://dali.feifeiyinyue.top/Article/details/gt2tfdwjevi.html

[M02] 读取环境变量
来源：http://dali.daxiang520.top/Article/details/gt2mfstljnc.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwqaklxr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hammf.cn/Article/details/gt2oerravfb.html

JS:   process.env.HOME
来源：http://dali.hnxiangtu.top/Article/details/gt2edvyytjk.html

TS:   process.env.HOME
来源：http://dali.wangdashe.top/Article/details/gt2ggsqsatn.html

Java: System.getenv("HOME")
来源：http://dali.iojbl.cn/Article/details/gt2zxluchqm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.pycfn.com/Article/details/gt2aigedott.html

Ruby: ENV["HOME"]
来源：http://dali.zdqjudy.top/Article/details/gt2qxufucpy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cashguo.top/Article/details/gt2hnxtzrru.html

[M03] 执行外部命令
来源：http://dali.birdmap.top/Article/details/gt2gcncecgv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.snrcjt.cn/Article/details/gt2mjxpsjch.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.meibo888.top/Article/details/gt2dnuawbsb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cqqwz.cn/Article/details/gt2lmogezsk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iwmanypg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ehwqpu.com/Article/details/gt2jwtrbpby.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yonumen.top/Article/details/gt2vorfycjq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gogol.net.cn/Article/details/gt2ggdmoblp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cdnleiting.top/Article/details/gt2budbvtnb.html

[M04] 获取当前工作目录
来源：http://dali.ehwqpu.com/Article/details/gt2kbqnwnzf.html

Py:   os.getcwd()
来源：http://dali.xinyue.icu/Article/details/gt2fjgxynhd.html

PHP:  getcwd();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vwfqiscu.html

JS:   process.cwd()
来源：http://dali.ivvv.top/Article/details/gt2jgvbbdhn.html

TS:   process.cwd()
来源：http://dali.hysaishi.cn/Article/details/gt2xazarkqf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.mhx1999.top/Article/details/gt2rqdhdzre.html

Go:   os.Getwd()
来源：http://dali.mhx1999.top/Article/details/gt2lpzghftt.html

Ruby: Dir.pwd
来源：http://dali.jqgufenzy.top/Article/details/gt2higszmuo.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hongshengwenyu.top/Article/details/gt2egqesmzm.html

[M05] 设置退出码
来源：http://dali.zhixingplan.top/Article/details/gt2dwmnjkkz.html

Py:   sys.exit(1)
来源：http://dali.yvedp.cn/Article/details/gt2faguhxnd.html

PHP:  exit(1);
来源：http://dali.yueranfly.top/Article/details/gt2tirrqgvz.html

JS:   process.exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2zfvktzek.html

TS:   process.exit(1)
来源：http://dali.yj20258888.top/Article/details/gt2lrqdyqem.html

Java: System.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gt2twrnrxjb.html

Go:   os.Exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2clnrbaji.html

Ruby: exit 1
来源：http://dali.dianchejie.cn/Article/details/gt2qmmujclv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zkhidmbl.html

[M06] 向标准错误输出
来源：http://dali.sufxvd.cn/Article/details/gt2lovtjslo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.aizwys.cn/Article/details/gt2mfpkfkbv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cucudq.cn/Article/details/gt2iocnzaxz.html

JS:   console.error("err")
来源：http://dali.nanxuanxn.top/Article/details/gt2vdwkhutl.html

TS:   console.error("err")
来源：http://dali.ppjwa.cn/Article/details/gt2wzzfgatf.html

Java: System.err.println("err")
来源：http://dali.jinqigfzy.top/Article/details/gt2ugnnkvkm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jianghu66.top/Article/details/gt2jdgjkfuo.html

Ruby: warn "err"
来源：http://dali.cashguo.top/Article/details/gt2ufbhgsty.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zkumrcmy.html

[M07] 判断是否为主入口
来源：http://dali.vqdsnc.cn/Article/details/gt2graogthj.html

Py:   if __name__ == "__main__":
来源：http://dali.xziqi.cn/Article/details/gt2csescshq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.mhx1999.top/Article/details/gt2isxymyay.html

JS:   require.main === module
来源：http://dali.jqgufenzy.top/Article/details/gt2nnxwcziu.html

TS:   require.main === module
来源：http://dali.zhengqikj.top/Article/details/gt2otwzstxz.html

Java: public static void main(String[] args)
来源：http://dali.hysaishi.cn/Article/details/gt2aujvdkzc.html

Go:   func main()
来源：http://dali.tanke756.top/Article/details/gt2xozakhfx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.haohaochexian.top/Article/details/gt2dldmibpd.html

C#:   static void Main(string[] args)
来源：http://dali.hfpthk.cn/Article/details/gt2jcczrthi.html

[M08] 获取系统与运行时信息
来源：http://dali.ydzc1.top/Article/details/gt2twnehbcq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sweek.top/Article/details/gt2bbkdgfhl.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hysaishi.cn/Article/details/gt2hrhwfimx.html

JS:   process.platform;  process.version
来源：http://dali.ybcxt.top/Article/details/gt2qzsxoqwl.html

TS:   process.platform;  process.version
来源：http://dali.sweek.top/Article/details/gt2ajbspbtl.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.pengpengdd.cyou/Article/details/gt2yuyywfws.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.vqdsnc.cn/Article/details/gt2gaskanej.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.wangshuangyany.cn/Article/details/gt2kiksfefc.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kxfpriuy.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2oxeamqde.html

N. 数据结构与算法
来源：http://dali.zhongyouzk.top/Article/details/gt2unvazqux.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2dhxvvhpg.html

[N01] 二分查找（有序数组）
来源：http://dali.316326.xyz/Article/details/gt2iddunnbu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gt2dpkymxol.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pwejrtml.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gzyfuxkp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dashuyun.cn/Article/details/gt2tnqvuduk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.daxiang520.top/Article/details/gt2cprvitpx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gt2dhlvrnvn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhengqikj.top/Article/details/gt2rayqifod.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gt2bbftrohi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jyoumei.cn/Article/details/gt2ethrmilk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2psywgclt.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yuanzhike.top/Article/details/gt2jxsxjgsw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.9152youxi.cn/Article/details/gt2vvityzlb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gt2kfweicfu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.svipenyu.cn/Article/details/gt2hzpejood.html

Go:   slices.Sort(arr)
来源：http://dali.yvedp.cn/Article/details/gt2hhxrjmcq.html

Ruby: arr.sort
来源：http://dali.hnqzz.top/Article/details/gt2zslmylam.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.daria6918.cn/Article/details/gt2kamfemnq.html

[N03] 快速排序（分治示例）
来源：http://dali.daxiang520.top/Article/details/gt2gtyuhiii.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ppjwa.cn/Article/details/gt2jqtlwzgb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ikwfozas.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xinyue.icu/Article/details/gt2forizmpo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hammf.cn/Article/details/gt2vxypfkjg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.0kj1m.cn/Article/details/gt2rcnzjfjg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yuxming.cn/Article/details/gt2wvoqnazs.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.vqdsnc.cn/Article/details/gt2tposbjgi.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.aibaodan.cn/Article/details/gt2bkkuusgu.html

[N04] 斐波那契数列
来源：http://dali.yj20258888.top/Article/details/gt2vtqxxbln.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2hgckopbg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhoulong.xyz/Article/details/gt2xarstnlv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgfzy.top/Article/details/gt2qddlmtma.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gt2mndbqmeo.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.iojbl.cn/Article/details/gt2pefxexwt.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenzaomai.com/Article/details/gt2mpcceitn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hnxiangtu.top/Article/details/gt2ikcfldxn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sufxvd.cn/Article/details/gt2obuvfent.html

[N05] 最大公约数
来源：http://dali.chenjidiqi.icu/Article/details/gt2ckkewmud.html

Py:   math.gcd(a, b)
来源：http://dali.9152youxi.cn/Article/details/gt2aefzfote.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xuanzx.com/Article/details/gt2xfrihuoq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj20258.top/Article/details/gt2nppkqlub.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cdnleiting.top/Article/details/gt2zwtcyhbn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.0kj1m.cn/Article/details/gt2uxbpdlyc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hammf.cn/Article/details/gt2opnlqmdt.html

Ruby: a.gcd(b)
来源：http://dali.zycfv.cn/Article/details/gt2zbspnnwk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jqgfzy.top/Article/details/gt2gsntccbn.html

[N06] 判断回文字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2yrihljpj.html

Py:   s == s[::-1]
来源：http://dali.shangyingyoupin.top/Article/details/gt2xvsenfrc.html

PHP:  $s === strrev($s);
来源：http://dali.kuanghao11.cn/Article/details/gt2nhtuftnv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gt2mkqynhna.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gt2kbwfvcnt.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.pycfn.com/Article/details/gt2jjhbzkvx.html

Go:   // 双指针从两端比较
来源：http://dali.dianchejie.cn/Article/details/gt2mbuponzb.html

Ruby: s == s.reverse
来源：http://dali.cashguo.top/Article/details/gt2kgxcuzrv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gzhubu.top/Article/details/gt2poibasvp.html

[N07] 两数之和（返回下标）
来源：http://dali.jinqigfzy.top/Article/details/gt2ywqlglvr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shuidangran.top/Article/details/gt2ebkfzqqa.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.mhx1999.top/Article/details/gt2irklkgcb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yongpay.top/Article/details/gt2hbonamve.html

TS:   // 手写 Map<string, number>
来源：http://dali.feifeiyinyue.top/Article/details/gt2zonfqgpt.html

Java: // 手写 HashMap
来源：http://dali.shanyushiyangtech.top/Article/details/gt2evoazmhc.html

Go:   // 手写 map[int]int
来源：http://dali.dianchejie.cn/Article/details/gt2ucwrpidh.html

Ruby: // 手写 Hash
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tpxcjyks.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yonumen.top/Article/details/gt2wlesqyxu.html

[N08] 生成全排列
来源：http://dali.daria6918.cn/Article/details/gt2dpmfkesw.html

Py:   itertools.permutations(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ohybzpqw.html

PHP:  // 手写递归交换
来源：http://dali.tianlin.xyz/Article/details/gt2vmbtjmld.html

JS:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gt2orvkdclz.html

TS:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gt2phuapqhk.html

Java: // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ywxnniua.html

Go:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gt2teqljuwe.html

Ruby: arr.permutation.to_a
来源：http://dali.havefunace.top/Article/details/gt2ytmsggpd.html

C#:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gt2rpjjnyzw.html

[N09] 栈与队列
来源：http://dali.jqgufenzy.top/Article/details/gt2tpjihiii.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xuanzx.com/Article/details/gt2hpmkrrzj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.guowangkeji.top/Article/details/gt2vytfuebi.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.vqdsnc.cn/Article/details/gt2masoirvi.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xuanzx.com/Article/details/gt2tfvdiozm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.vqdsnc.cn/Article/details/gt2etylbkmr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yvedp.cn/Article/details/gt2jujmpero.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhongyouzk.top/Article/details/gt2xebzjnjc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ehwqpu.com/Article/details/gt2zeclaupx.html

[N10] 链表节点定义
来源：http://dali.xylfe.cn/Article/details/gt2mvtgutfb.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yuanzhike.top/Article/details/gt2oelwmnfv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hnxiangtu.top/Article/details/gt2ldekaedd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.nanxinkj.top/Article/details/gt2kavywaeb.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hammf.cn/Article/details/gt2oibzornj.html

Java: class Node { int v; Node next; }
来源：http://dali.chenlongwang.top/Article/details/gt2ldztvvjd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cucudq.cn/Article/details/gt2dsgaling.html


<!-- 参考信息 -->