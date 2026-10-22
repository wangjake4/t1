代发 wailian999

[K02] JSON 字符串转对象
来源：http://dali.nwbrower.top/Article/details/gt2tejwnoka.html

Py:   json.loads(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ywriqmkq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.fengsongda.top/Article/details/gt2bbdzjpxx.html

JS:   JSON.parse(s)
来源：http://dali.yj202588.top/Article/details/gt2pskkcpxl.html

TS:   JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gt2igpqwxws.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.havefunace.top/Article/details/gt2fplxyujc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lxsowsjv.html

Ruby: JSON.parse(s)
来源：http://dali.xylfe.cn/Article/details/gt2ulujjlnx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wqojsqgc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.aizwys.cn/Article/details/gt2peudtkrr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.tanke756.top/Article/details/gt2ezdwzfpd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xuetiantiany.cn/Article/details/gt2vkglcamu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gt2yzwkarve.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sweek.top/Article/details/gt2fkyeznjh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2wizypwko.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhengqikj.top/Article/details/gt2itycwbxd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.fengsongda.top/Article/details/gt2vawodjyv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yanxiufei.cn/Article/details/gt2umzbsmon.html

[K04] 读取 JSON 文件
来源：http://dali.pycfn.com/Article/details/gt2cnwwozin.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2hnwguwwr.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.tanke756.top/Article/details/gt2kfwjuxti.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cashguo.top/Article/details/gt2azxgnjsf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.redwolf501.top/Article/details/gt2xbchiyzb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jianghu66.top/Article/details/gt2vubrmxgv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.mhx1999.top/Article/details/gt2ehliqrui.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bwpdhmjg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhixingplan.top/Article/details/gt2iwqcucmj.html

[K05] 深拷贝对象
来源：http://dali.yj202588.top/Article/details/gt2zvsxwsko.html

Py:   copy.deepcopy(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2kqlkowpe.html

PHP:  unserialize(serialize($obj));
来源：http://dali.aibaodan.cn/Article/details/gt2yedkppbj.html

JS:   structuredClone(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vokusbmy.html

TS:   structuredClone(obj)
来源：http://dali.mhx1999.top/Article/details/gt2bzehqvji.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xylfe.cn/Article/details/gt2josfrmyj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yj20258.top/Article/details/gt2kkijdvyz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shuidangran.top/Article/details/gt2bdnrxcxr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zycfv.cn/Article/details/gt2lqrlqdjw.html

[K06] 解析 URL 查询串
来源：http://dali.cucudq.cn/Article/details/gt2cpqgafbt.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cqqwz.cn/Article/details/gt2fuczphpz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gaohongyu789.top/Article/details/gt2xwdwysqz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhengqikj.top/Article/details/gt2isxqcski.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yvedp.cn/Article/details/gt2mmgfahwh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sbpqmjoz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gt2aknwrynt.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gt2cvzuwmgi.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ydzc1.top/Article/details/gt2xafaxxxz.html

[K07] 进制转换
来源：http://dali.yongpay.top/Article/details/gt2zfingenm.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gt2ndmvycld.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.kuanghao11.cn/Article/details/gt2vnbkaftm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gt2ljogrqxk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gt2oadhocnm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yj20258.top/Article/details/gt2ldyqawxj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhiwuduotai.top/Article/details/gt2dshnbvna.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.vqdsnc.cn/Article/details/gt2xwhljgyj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2dalvgbqy.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gotoacloud.top/Article/details/gt2damlyjyi.html

Py:   pickle.dumps(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2cmvccrsg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jyoumei.cn/Article/details/gt2riosqtvi.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.redwolf501.top/Article/details/gt2bfspurhi.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.aizwys.cn/Article/details/gt2eyzpljun.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.tianlin.xyz/Article/details/gt2szgohiaa.html

Go:   encoding/gob
来源：http://dali.ybcxt.top/Article/details/gt2kjonrfif.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvkhbox.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cdnleiting.top/Article/details/gt2ueqsxaeg.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2adnljnll.html

L. 网络请求
来源：http://dali.tanke756.top/Article/details/gt2icjeswaw.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2xixctdtt.html

[L01] 发送 GET 请求
来源：http://dali.wangshuangyany.cn/Article/details/gt2mdudbgyy.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sweek.top/Article/details/gt2ejattpcz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zycfv.cn/Article/details/gt2jtaqgjdg.html

JS:   await fetch(url)
来源：http://dali.xuanzx.com/Article/details/gt2pbmywrmd.html

TS:   await fetch(url)
来源：http://dali.nanxuanxn.top/Article/details/gt2lmnhhuql.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cashguo.top/Article/details/gt2egdeygcy.html

Go:   resp, err := http.Get(url)
来源：http://dali.snrcjt.cn/Article/details/gt2pfeoodhj.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xinyue.icu/Article/details/gt2fehpxngo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yj20258.top/Article/details/gt2whmqcfmn.html

[L02] 发送 POST JSON
来源：http://dali.feifeiyinyue.top/Article/details/gt2tuduxbip.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.guannengcc.top/Article/details/gt2ncsepwqt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jyoumei.cn/Article/details/gt2jmgkpszu.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.smart0.xyz/Article/details/gt2rvbrwrpb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigfzy.top/Article/details/gt2rocmffxw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xziqi.cn/Article/details/gt2nayopaxp.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhengqikj.top/Article/details/gt2veiwajgu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.tianlin.xyz/Article/details/gt2sywlwrrf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.havefunace.top/Article/details/gt2sattonrl.html

[L03] 设置自定义请求头
来源：http://dali.shzxlz.cn/Article/details/gt2wzcjzuwn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yangfankeji.com/Article/details/gt2axnjreqj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jlsjyb.cn/Article/details/gt2cxmjufuz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.0kj1m.cn/Article/details/gt2wcxvswxf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.andypj.xyz/Article/details/gt2halmxwsq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.chenzaomai.com/Article/details/gt2zzzxbstb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gozvjscx.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xinyue.icu/Article/details/gt2kwmqizpn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xylfe.cn/Article/details/gt2bvbxhgsg.html

[L04] 设置超时
来源：http://dali.yongpay.top/Article/details/gt2ndpuppby.html

Py:   requests.get(url, timeout=5)
来源：http://dali.dashuyun.cn/Article/details/gt2ypwezagd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.nanxinkj.top/Article/details/gt2mfurcpqk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuanzhike.top/Article/details/gt2pleixeem.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.kuanghao11.cn/Article/details/gt2gydlkmut.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.mhx1999.top/Article/details/gt2xqfjhkwb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gaohongyu789.top/Article/details/gt2tzkhdxvs.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.dashuyun.cn/Article/details/gt2spscxpyf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yvedp.cn/Article/details/gt2bmcxbneu.html

[L05] 上传文件（multipart）
来源：http://dali.xuanzx.com/Article/details/gt2zldoobzb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ppjwa.cn/Article/details/gt2rwgaeyfm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.nwbrower.top/Article/details/gt2tqycgass.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tian-w.cn/Article/details/gt2tmqlzuwi.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.guannengcc.top/Article/details/gt2lpxlegwq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ptcllhyk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.nanxuanxn.top/Article/details/gt2kamvprrt.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.daxiang520.top/Article/details/gt2mqlyljrz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2ylzunmpq.html

[L06] 解析响应为 JSON
来源：http://dali.gotoacloud.top/Article/details/gt2vwfkgrxb.html

Py:   resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gt2vvyofjal.html

PHP:  json_decode($body, true);
来源：http://dali.zhengqikj.top/Article/details/gt2uhhzwrlq.html

JS:   await resp.json()
来源：http://dali.feifeiyinyue.top/Article/details/gt2cronstkq.html

TS:   await resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2waivcbwr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shuidangran.top/Article/details/gt2hdpurstz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jiagoushi.top/Article/details/gt2wbcjzvff.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj202588.top/Article/details/gt2bwzyuxfw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hnqzz.top/Article/details/gt2gwmmqshh.html

[L07] 处理 HTTP 状态码
来源：http://dali.fzhhl.top/Article/details/gt2zofbxhwf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj20258888.top/Article/details/gt2nzipzsdf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ppjwa.cn/Article/details/gt2bumzjwzp.html

JS:   resp.ok;  resp.status
来源：http://dali.chenlongwang.top/Article/details/gt2wuqzuaak.html

TS:   resp.ok;  resp.status
来源：http://dali.guowangkeji.top/Article/details/gt2rtcfbuap.html

Java: resp.statusCode()
来源：http://dali.yongpay.top/Article/details/gt2wwfpduhb.html

Go:   resp.StatusCode
来源：http://dali.sxryk.cn/Article/details/gt2anmulwab.html

Ruby: resp.code.to_i
来源：http://dali.shangyingyoupin.top/Article/details/gt2djyohwng.html

C#:   (int)resp.StatusCode
来源：http://dali.hysaishi.cn/Article/details/gt2jclmkhvy.html

[L08] 并发请求多个地址
来源：http://dali.jqgufenzy.top/Article/details/gt2cyevjweo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yj202588.top/Article/details/gt2tsvjuisw.html

PHP:  curl_multi_init() 系列
来源：http://dali.pycfn.com/Article/details/gt2bkwrrmfg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gt2hsiravxv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnxiangtu.top/Article/details/gt2ahuyunsj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cashguo.top/Article/details/gt2iubcqzaf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinqigfzy.top/Article/details/gt2dvljyoja.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jqgfzy.top/Article/details/gt2ximrgywp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sxryk.cn/Article/details/gt2ovobzztq.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2zgmscroh.html

M. 命令行 / 进程 / 环境
来源：http://dali.gogol.net.cn/Article/details/gt2vwsfhzfk.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2sltzugja.html

[M01] 读取命令行参数
来源：http://dali.pycfn.com/Article/details/gt2bsajkswm.html

Py:   sys.argv[1:]
来源：http://dali.zhoulong.xyz/Article/details/gt2fmbifsdh.html

PHP:  $argv;  $argc;
来源：http://dali.aibaodan.cn/Article/details/gt2ekbnperx.html

JS:   process.argv.slice(2)
来源：http://dali.nanxinkj.top/Article/details/gt2sykrengk.html

TS:   process.argv.slice(2)
来源：http://dali.bjfxy.top/Article/details/gt2apkzmmyc.html

Java: args 数组（main 方法参数）
来源：http://dali.jqgufenzy.top/Article/details/gt2rlvrlltz.html

Go:   os.Args[1:]
来源：http://dali.gzhubu.top/Article/details/gt2vvozfdxx.html

Ruby: ARGV
来源：http://dali.jinqigufen.top/Article/details/gt2vhqgmurm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.kuanghao11.cn/Article/details/gt2jsgbwhvz.html

[M02] 读取环境变量
来源：http://dali.tian-w.cn/Article/details/gt2bchguvuf.html

Py:   os.environ.get("HOME")
来源：http://dali.shzxlz.cn/Article/details/gt2ghyicjiw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhixingplan.top/Article/details/gt2swuyvvbd.html

JS:   process.env.HOME
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nzdbrirc.html

TS:   process.env.HOME
来源：http://dali.yanxiufei.cn/Article/details/gt2klzidmud.html

Java: System.getenv("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gt2aldyzslq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yangfankeji.com/Article/details/gt2uknodgsy.html

Ruby: ENV["HOME"]
来源：http://dali.0kj1m.cn/Article/details/gt2ckwlblqd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iaxddgkq.html

[M03] 执行外部命令
来源：http://dali.gzhubu.top/Article/details/gt2npvjwwwv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hnqzz.top/Article/details/gt2njkvwypk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ybcxt.top/Article/details/gt2jxnqmdup.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ydzc1.top/Article/details/gt2emzyvrvz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenzaomai.com/Article/details/gt2tmmhjtne.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.vqdsnc.cn/Article/details/gt2tgdcblzg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xinyue.icu/Article/details/gt2ilduhloc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shangyingyoupin.top/Article/details/gt2pxhnqoqh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhixingplan.top/Article/details/gt2gqraznzt.html

[M04] 获取当前工作目录
来源：http://dali.yuanzhike.top/Article/details/gt2bbadmhgm.html

Py:   os.getcwd()
来源：http://dali.zhoulong.xyz/Article/details/gt2hgxzbmhd.html

PHP:  getcwd();
来源：http://dali.yj20258.top/Article/details/gt2sembjqeq.html

JS:   process.cwd()
来源：http://dali.xuanzx.com/Article/details/gt2evakaict.html

TS:   process.cwd()
来源：http://dali.guowangkeji.top/Article/details/gt2ptqiszjt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xziqi.cn/Article/details/gt2lqsdscxq.html

Go:   os.Getwd()
来源：http://dali.c1oappe.top/Article/details/gt2nrgmgvai.html

Ruby: Dir.pwd
来源：http://dali.ybcxt.top/Article/details/gt2ffazysry.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.c1oappe.top/Article/details/gt2yqxjpjqh.html

[M05] 设置退出码
来源：http://dali.pengpengdd.cyou/Article/details/gt2svxbisjc.html

Py:   sys.exit(1)
来源：http://dali.redwolf501.top/Article/details/gt2wdsmzkqb.html

PHP:  exit(1);
来源：http://dali.nwbrower.top/Article/details/gt2mypqcykn.html

JS:   process.exit(1)
来源：http://dali.zycfv.cn/Article/details/gt2hprsueuf.html

TS:   process.exit(1)
来源：http://dali.sxryk.cn/Article/details/gt2vrqjykpu.html

Java: System.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gt2yasqfmmk.html

Go:   os.Exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2ksnwlcar.html

Ruby: exit 1
来源：http://dali.cashguo.top/Article/details/gt2ktzbuvsy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nanxinkj.top/Article/details/gt2swqugbnr.html

[M06] 向标准错误输出
来源：http://dali.jlsjyb.cn/Article/details/gt2lnsgagqv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sysykeji.top/Article/details/gt2ejimlneu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hnqzz.top/Article/details/gt2mkvgfvrd.html

JS:   console.error("err")
来源：http://dali.yj202588.top/Article/details/gt2hmgctvpk.html

TS:   console.error("err")
来源：http://dali.jiagoushi.top/Article/details/gt2egxdyhhg.html

Java: System.err.println("err")
来源：http://dali.cdnleiting.top/Article/details/gt2mebrwbgp.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.pycfn.com/Article/details/gt2midelzci.html

Ruby: warn "err"
来源：http://dali.wangdashe.top/Article/details/gt2oipvwgbt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.svipenyu.cn/Article/details/gt2xrnovqxl.html

[M07] 判断是否为主入口
来源：http://dali.aizwys.cn/Article/details/gt2ylbwytqc.html

Py:   if __name__ == "__main__":
来源：http://dali.yj20258888.top/Article/details/gt2lnyenyly.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.nwbrower.top/Article/details/gt2leulqlox.html

JS:   require.main === module
来源：http://dali.chenlongwang.top/Article/details/gt2knatguvu.html

TS:   require.main === module
来源：http://dali.aizwys.cn/Article/details/gt2rycpooqs.html

Java: public static void main(String[] args)
来源：http://dali.hysaishi.cn/Article/details/gt2gpwiivvd.html

Go:   func main()
来源：http://dali.ehwqpu.com/Article/details/gt2xrycetck.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.guowangkeji.top/Article/details/gt2jtqykfph.html

C#:   static void Main(string[] args)
来源：http://dali.zhongyouzk.top/Article/details/gt2ndijqhoa.html

[M08] 获取系统与运行时信息
来源：http://dali.gzhubu.top/Article/details/gt2eskbflsm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.fengsongda.top/Article/details/gt2ooczpsif.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.guowangkeji.top/Article/details/gt2apgwbyqz.html

JS:   process.platform;  process.version
来源：http://dali.nanxinkj.top/Article/details/gt2qpcaokwk.html

TS:   process.platform;  process.version
来源：http://dali.zhoulong.xyz/Article/details/gt2xuinhtul.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.tian-w.cn/Article/details/gt2wsuiwmks.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj20258.top/Article/details/gt2knyjqemv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jlsjyb.cn/Article/details/gt2vzcibhrg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sweek.top/Article/details/gt2uphvklub.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2bdnkgtny.html

N. 数据结构与算法
来源：http://dali.cdnleiting.top/Article/details/gt2qqasxcux.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2etezuvjy.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2oiezsiml.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.daria6918.cn/Article/details/gt2ycrxmvhq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.meibo888.top/Article/details/gt2gkvvrzrd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aibaodan.cn/Article/details/gt2egfmpguw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxinkj.top/Article/details/gt2gvbsehiw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gt2ntlizgoe.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2gspbzrxa.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cheryme.top/Article/details/gt2vqxektoh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vflfxnmt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhiwuduotai.top/Article/details/gt2fdwwkzkn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.9152youxi.cn/Article/details/gt2fvqnywax.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gt2vrfprpen.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sweek.top/Article/details/gt2zgwwzzjz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hywenlv.cn/Article/details/gt2swcgdono.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.kuanghao11.cn/Article/details/gt2wnqztgzf.html

Go:   slices.Sort(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jpesmezy.html

Ruby: arr.sort
来源：http://dali.aibaodan.cn/Article/details/gt2kphjigpj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zdqjudy.top/Article/details/gt2casvdpjm.html

[N03] 快速排序（分治示例）
来源：http://dali.9152youxi.cn/Article/details/gt2vqmgsqhf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shangyingyoupin.top/Article/details/gt2tdcxdbsj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gotoacloud.top/Article/details/gt2wcufmlxy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.svipenyu.cn/Article/details/gt2yzjmtgkj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tianlin.xyz/Article/details/gt2akxqqshc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yuanzhike.top/Article/details/gt2dcxandjt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jlsjyb.cn/Article/details/gt2tsdodlwd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ivvv.top/Article/details/gt2hbhceqdy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.guowangkeji.top/Article/details/gt2hmlgtukw.html

[N04] 斐波那契数列
来源：http://dali.fengsongda.top/Article/details/gt2dxoiroit.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.daria6918.cn/Article/details/gt2vkczklka.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gt2tblbrjpx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ydzc1.top/Article/details/gt2mnjojvkh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ydzc1.top/Article/details/gt2rlqubmff.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.chenzaomai.com/Article/details/gt2dcoeffdx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sxryk.cn/Article/details/gt2dciadwad.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2mzzxjfyf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.pycfn.com/Article/details/gt2jqocspfq.html

[N05] 最大公约数
来源：http://dali.jianghu66.top/Article/details/gt2hbkjbntv.html

Py:   math.gcd(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gt2sgbjdyij.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ydzc1.top/Article/details/gt2esoxyhcr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guowangkeji.top/Article/details/gt2wmuegplm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ooxdljrw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.aizwys.cn/Article/details/gt2iougjnnj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.fengsongda.top/Article/details/gt2ttshydkj.html

Ruby: a.gcd(b)
来源：http://dali.yongpay.top/Article/details/gt2usqreejn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.fzhhl.top/Article/details/gt2mwuooiei.html

[N06] 判断回文字符串
来源：http://dali.yvedp.cn/Article/details/gt2uqgyxkdl.html

Py:   s == s[::-1]
来源：http://dali.chenzaomai.com/Article/details/gt2wxpanavt.html

PHP:  $s === strrev($s);
来源：http://dali.ivvv.top/Article/details/gt2xyamkbcy.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gt2vtbhelyk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gt2ksoqsqmn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gotoacloud.top/Article/details/gt2pvqydgpa.html

Go:   // 双指针从两端比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nlrztpef.html

Ruby: s == s.reverse
来源：http://dali.nanxuanxn.top/Article/details/gt2yabibnty.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.wangshuangyany.cn/Article/details/gt2gnoclpkm.html

[N07] 两数之和（返回下标）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ihrsqqnr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jyoumei.cn/Article/details/gt2raqmdkha.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinqigfzy.top/Article/details/gt2xlkpygwd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.andypj.xyz/Article/details/gt2jkfjdqzb.html

TS:   // 手写 Map<string, number>
来源：http://dali.mhx1999.top/Article/details/gt2yzuwzcei.html

Java: // 手写 HashMap
来源：http://dali.yanxiufei.cn/Article/details/gt2ueqmcgtp.html

Go:   // 手写 map[int]int
来源：http://dali.9152youxi.cn/Article/details/gt2gqyfwftl.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2hlsdgxbs.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gzhubu.top/Article/details/gt2pppmwrii.html

[N08] 生成全排列
来源：http://dali.xziqi.cn/Article/details/gt2kpeygkkr.html

Py:   itertools.permutations(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2hvcpmviw.html

PHP:  // 手写递归交换
来源：http://dali.zhengqikj.top/Article/details/gt2qaumgbyl.html

JS:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gt2vegrwdnu.html

TS:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gt2pjnbpvzk.html

Java: // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gt2ahezhhon.html

Go:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gt2bpgihkqq.html

Ruby: arr.permutation.to_a
来源：http://dali.pycfn.com/Article/details/gt2nyohycme.html

C#:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gt2icmzdpwg.html

[N09] 栈与队列
来源：http://dali.bjfxy.top/Article/details/gt2qqccmdns.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yj20258.top/Article/details/gt2rrmcgiwt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gt2ujhteool.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.fengsongda.top/Article/details/gt2sjxbfdrl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nanxinkj.top/Article/details/gt2hjwslfwz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.havefunace.top/Article/details/gt2uhydusmp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinqigufen.top/Article/details/gt2sbiyfmjc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ybcxt.top/Article/details/gt2kctdpthk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2fiigvtnw.html

[N10] 链表节点定义
来源：http://dali.aizwys.cn/Article/details/gt2fyvizypk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.guowangkeji.top/Article/details/gt2kjdgteih.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ppjwa.cn/Article/details/gt2bxkfwsir.html


<!-- 参考信息 -->