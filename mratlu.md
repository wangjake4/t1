代发 wailian999

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.meibo888.top/Article/details/gt2jiammgny.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ehwqpu.com/Article/details/gt2ndnhmaqr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gogol.net.cn/Article/details/gt2aimlyvnp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cashguo.top/Article/details/gt2jqizbjiq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hongshengwenyu.top/Article/details/gt2aekcjofc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.meibo888.top/Article/details/gt2ubdhkrlm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yuxming.cn/Article/details/gt2rfkntpva.html

[K05] 深拷贝对象
来源：http://dali.shuidangran.top/Article/details/gt2vceerfiq.html

Py:   copy.deepcopy(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2mletztww.html

PHP:  unserialize(serialize($obj));
来源：http://dali.havefunace.top/Article/details/gt2ojwtymuo.html

JS:   structuredClone(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2sjakqcui.html

TS:   structuredClone(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2agoreenu.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jianghu66.top/Article/details/gt2pakgfggo.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.guannengcc.top/Article/details/gt2ooqhejvj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hnqzz.top/Article/details/gt2avjaedqo.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cashguo.top/Article/details/gt2mebbfcjt.html

[K06] 解析 URL 查询串
来源：http://dali.zhengqikj.top/Article/details/gt2ktjayrje.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xziqi.cn/Article/details/gt2lgwurbxt.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hammf.cn/Article/details/gt2xwrbhgme.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenjidiqi.icu/Article/details/gt2catxxrom.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pengpengdd.cyou/Article/details/gt2yhsrnylf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.wangshuangyany.cn/Article/details/gt2tvjkzkmo.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gt2nlgvmtea.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.bjfxy.top/Article/details/gt2ofsonaac.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gt2npwurqpo.html

[K07] 进制转换
来源：http://dali.tianlin.xyz/Article/details/gt2wtxzusjh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gt2snlfzqje.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.guannengcc.top/Article/details/gt2trogjueb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gt2jaaonohl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gt2zmnrmcbi.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gt2pljmiydf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinqigufen.top/Article/details/gt2txaaiomv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.tianlin.xyz/Article/details/gt2ixssghru.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.birdmap.top/Article/details/gt2hmpwscum.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hongshengwenyu.top/Article/details/gt2zcdpattg.html

Py:   pickle.dumps(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2matjiivj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhongyouzk.top/Article/details/gt2xmmbumjd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xylfe.cn/Article/details/gt2fyhholsu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.c1oappe.top/Article/details/gt2nsynxerk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.havefunace.top/Article/details/gt2flthneel.html

Go:   encoding/gob
来源：http://dali.yuxming.cn/Article/details/gt2cbdpxngp.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2mshrltkk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.fengsongda.top/Article/details/gt2hbvoxijr.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2etxbisct.html

L. 网络请求
来源：http://dali.yonumen.top/Article/details/gt2sipnyakj.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2uuawxhvz.html

[L01] 发送 GET 请求
来源：http://dali.yj20258.top/Article/details/gt2mhlhfges.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shangyingyoupin.top/Article/details/gt2vzummlqx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yj202588.top/Article/details/gt2lslaudhz.html

JS:   await fetch(url)
来源：http://dali.jqgfzy.top/Article/details/gt2ysjhwdmo.html

TS:   await fetch(url)
来源：http://dali.zhongyouzk.top/Article/details/gt2zfabngxz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhengqikj.top/Article/details/gt2ydvfpufq.html

Go:   resp, err := http.Get(url)
来源：http://dali.pycfn.com/Article/details/gt2sukyvsoz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yvedp.cn/Article/details/gt2nsnnfwxh.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.aibaodan.cn/Article/details/gt2opodpioj.html

[L02] 发送 POST JSON
来源：http://dali.mhx1999.top/Article/details/gt2vlujjsqx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhengqikj.top/Article/details/gt2kwgdrtbl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ybcxt.top/Article/details/gt2jqflxiuj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yongpay.top/Article/details/gt2aqpcnhwx.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fengsongda.top/Article/details/gt2bilygatn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.birdmap.top/Article/details/gt2pgkfrpqp.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gaohongyu789.top/Article/details/gt2floqbdrl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eqlmilyq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cqqwz.cn/Article/details/gt2nxtjgcfs.html

[L03] 设置自定义请求头
来源：http://dali.shangyingyoupin.top/Article/details/gt2ljutjlzt.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jianghu66.top/Article/details/gt2fpnpeygp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jlsjyb.cn/Article/details/gt2ejmcglmu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ivvv.top/Article/details/gt2livcjtqe.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgfzy.top/Article/details/gt2xgwnaucc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yueranfly.top/Article/details/gt2uuwnlnjn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sweek.top/Article/details/gt2uoqpqoej.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.daxiang520.top/Article/details/gt2cdthtuul.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.tanke756.top/Article/details/gt2vywzplag.html

[L04] 设置超时
来源：http://dali.yongpay.top/Article/details/gt2lkihwthu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2apuwjxhv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinqigfzy.top/Article/details/gt2aewiampv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuanzhike.top/Article/details/gt2hlkfybsy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnxiangtu.top/Article/details/gt2mmvoydbe.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.smart0.xyz/Article/details/gt2icfcvhnp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.fzhhl.top/Article/details/gt2zhhxknsj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lteohwtn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.0kj1m.cn/Article/details/gt2sniawdpv.html

[L05] 上传文件（multipart）
来源：http://dali.jinqigfzy.top/Article/details/gt2dvcjbxhw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.birdmap.top/Article/details/gt2fopzvzcz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.smart0.xyz/Article/details/gt2ezwbcmdf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xinyue.icu/Article/details/gt2vreuhils.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zycfv.cn/Article/details/gt2ighxdhdb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinqigufen.top/Article/details/gt2tnbojpsv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.andypj.xyz/Article/details/gt2gixeecjz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shangyingyoupin.top/Article/details/gt2bbwxdpja.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2vefsekfj.html

[L06] 解析响应为 JSON
来源：http://dali.cheryme.top/Article/details/gt2klsezuhf.html

Py:   resp.json()
来源：http://dali.jianghu66.top/Article/details/gt2fncerggd.html

PHP:  json_decode($body, true);
来源：http://dali.tian-w.cn/Article/details/gt2gzpnrijz.html

JS:   await resp.json()
来源：http://dali.yj20258.top/Article/details/gt2eyipmcgp.html

TS:   await resp.json()
来源：http://dali.smart0.xyz/Article/details/gt2scyjwjdr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.birdmap.top/Article/details/gt2gcmnetov.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.chenzaomai.com/Article/details/gt2ddgptajo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.dianchejie.cn/Article/details/gt2ygivrggx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xziqi.cn/Article/details/gt2npzsnhbv.html

[L07] 处理 HTTP 状态码
来源：http://dali.gzhubu.top/Article/details/gt2hazifcey.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.c1oappe.top/Article/details/gt2jojiezpy.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cqqwz.cn/Article/details/gt2bdxovlqo.html

JS:   resp.ok;  resp.status
来源：http://dali.cucudq.cn/Article/details/gt2cxneauhw.html

TS:   resp.ok;  resp.status
来源：http://dali.aizwys.cn/Article/details/gt2rcdgksza.html

Java: resp.statusCode()
来源：http://dali.ivvv.top/Article/details/gt2oecawura.html

Go:   resp.StatusCode
来源：http://dali.yueranfly.top/Article/details/gt2mmkzvwnq.html

Ruby: resp.code.to_i
来源：http://dali.xylfe.cn/Article/details/gt2llotuyke.html

C#:   (int)resp.StatusCode
来源：http://dali.ppjwa.cn/Article/details/gt2vxlshlng.html

[L08] 并发请求多个地址
来源：http://dali.feifeiyinyue.top/Article/details/gt2ofdwzcmv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.0kj1m.cn/Article/details/gt2rauyukfb.html

PHP:  curl_multi_init() 系列
来源：http://dali.xylfe.cn/Article/details/gt2rinpdpbz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.c1oappe.top/Article/details/gt2wzqkydyv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.meibo888.top/Article/details/gt2jadurqvh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nwmjhnbc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shangyingyoupin.top/Article/details/gt2sqswezuv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xuanzx.com/Article/details/gt2ydumpbuq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.dashuyun.cn/Article/details/gt2urphsefr.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2hgutuyfp.html

M. 命令行 / 进程 / 环境
来源：http://dali.jqgufenzy.top/Article/details/gt2jwjfemhj.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2cfclzaat.html

[M01] 读取命令行参数
来源：http://dali.xziqi.cn/Article/details/gt2pagduqdj.html

Py:   sys.argv[1:]
来源：http://dali.tian-w.cn/Article/details/gt2avtmbnjy.html

PHP:  $argv;  $argc;
来源：http://dali.gaohongyu789.top/Article/details/gt2tlrkhmyt.html

JS:   process.argv.slice(2)
来源：http://dali.nanxuanxn.top/Article/details/gt2dlmrdywp.html

TS:   process.argv.slice(2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dyfbsucb.html

Java: args 数组（main 方法参数）
来源：http://dali.zhengqikj.top/Article/details/gt2slksfevx.html

Go:   os.Args[1:]
来源：http://dali.guowangkeji.top/Article/details/gt2eefcnbjm.html

Ruby: ARGV
来源：http://dali.guannengcc.top/Article/details/gt2fihtvrgc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.tianlin.xyz/Article/details/gt2dmcrmcma.html

[M02] 读取环境变量
来源：http://dali.sxryk.cn/Article/details/gt2fwekuhzw.html

Py:   os.environ.get("HOME")
来源：http://dali.meibo888.top/Article/details/gt2fmfglmsn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cqqwz.cn/Article/details/gt2cyniitci.html

JS:   process.env.HOME
来源：http://dali.aizwys.cn/Article/details/gt2omrucohj.html

TS:   process.env.HOME
来源：http://dali.9152youxi.cn/Article/details/gt2cdkojbup.html

Java: System.getenv("HOME")
来源：http://dali.9152youxi.cn/Article/details/gt2veysjwgp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gogol.net.cn/Article/details/gt2wfgrdwsw.html

Ruby: ENV["HOME"]
来源：http://dali.hongshengwenyu.top/Article/details/gt2nndcoirn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.daxiang520.top/Article/details/gt2urqjirxg.html

[M03] 执行外部命令
来源：http://dali.redwolf501.top/Article/details/gt2ugduvumh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hysaishi.cn/Article/details/gt2acvqyllj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.snrcjt.cn/Article/details/gt2gfrfmnpo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cheryme.top/Article/details/gt2ezhhgtlu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jiagoushi.top/Article/details/gt2dbbxbtup.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.meibo888.top/Article/details/gt2uhbpfkar.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.svipenyu.cn/Article/details/gt2akwbpdsp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenjidiqi.icu/Article/details/gt2ctarfpst.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nanxuanxn.top/Article/details/gt2hnoghnep.html

[M04] 获取当前工作目录
来源：http://dali.sufxvd.cn/Article/details/gt2ojzjmytq.html

Py:   os.getcwd()
来源：http://dali.xziqi.cn/Article/details/gt2urxivime.html

PHP:  getcwd();
来源：http://dali.shangyingyoupin.top/Article/details/gt2bzxbigza.html

JS:   process.cwd()
来源：http://dali.andypj.xyz/Article/details/gt2mtxbhvvt.html

TS:   process.cwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rdljpqqj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yangfankeji.com/Article/details/gt2pbgestni.html

Go:   os.Getwd()
来源：http://dali.quarkkingdee.top/Article/details/gt2bhkmeizf.html

Ruby: Dir.pwd
来源：http://dali.dianchejie.cn/Article/details/gt2ydmksvsw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cmyzngye.html

[M05] 设置退出码
来源：http://dali.chenzaomai.com/Article/details/gt2scvnlddt.html

Py:   sys.exit(1)
来源：http://dali.yvedp.cn/Article/details/gt2puutxnjp.html

PHP:  exit(1);
来源：http://dali.zycfv.cn/Article/details/gt2hshzuqcj.html

JS:   process.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2egxzhqzz.html

TS:   process.exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2bhrmznkg.html

Java: System.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gt2bemvxhgu.html

Go:   os.Exit(1)
来源：http://dali.hfpthk.cn/Article/details/gt2xenkaiqh.html

Ruby: exit 1
来源：http://dali.ppjwa.cn/Article/details/gt2qcybwiig.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.iojbl.cn/Article/details/gt2lhcfpgae.html

[M06] 向标准错误输出
来源：http://dali.yj20258.top/Article/details/gt2lrshsjkk.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj20258888.top/Article/details/gt2migtkaod.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sweek.top/Article/details/gt2hlaweeit.html

JS:   console.error("err")
来源：http://dali.haohaochexian.top/Article/details/gt2jjikerwh.html

TS:   console.error("err")
来源：http://dali.shangyingyoupin.top/Article/details/gt2hslkbovm.html

Java: System.err.println("err")
来源：http://dali.yvedp.cn/Article/details/gt2pjickkap.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fmlkacrj.html

Ruby: warn "err"
来源：http://dali.chenjidiqi.icu/Article/details/gt2dwdlsjkm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.quarkkingdee.top/Article/details/gt2qkjoarce.html

[M07] 判断是否为主入口
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2apjkqchg.html

Py:   if __name__ == "__main__":
来源：http://dali.guannengcc.top/Article/details/gt2gnrlkgii.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.aizwys.cn/Article/details/gt2fcnvwdco.html

JS:   require.main === module
来源：http://dali.birdmap.top/Article/details/gt2kvmokeln.html

TS:   require.main === module
来源：http://dali.fengsongda.top/Article/details/gt2qvasymce.html

Java: public static void main(String[] args)
来源：http://dali.cheryme.top/Article/details/gt2wvueqanm.html

Go:   func main()
来源：http://dali.cheryme.top/Article/details/gt2vnhhrvlh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.wangshuangyany.cn/Article/details/gt2hhdjotou.html

C#:   static void Main(string[] args)
来源：http://dali.chenlongwang.top/Article/details/gt2busgxnkx.html

[M08] 获取系统与运行时信息
来源：http://dali.jqgfzy.top/Article/details/gt2qzokxxoh.html

Py:   platform.system();  platform.python_version()
来源：http://dali.nanxinkj.top/Article/details/gt2tbptlooe.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ztqlgfng.html

JS:   process.platform;  process.version
来源：http://dali.yangfankeji.com/Article/details/gt2cnwpucfx.html

TS:   process.platform;  process.version
来源：http://dali.yongpay.top/Article/details/gt2qfhotkmp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gotoacloud.top/Article/details/gt2ajktqnof.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.kuanghao11.cn/Article/details/gt2gatnhssz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.nwbrower.top/Article/details/gt2vushxezh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hnqzz.top/Article/details/gt2whxgiobr.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2fnmkmkif.html

N. 数据结构与算法
来源：http://dali.tian-w.cn/Article/details/gt2wvfrkypx.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2wqrfdvik.html

[N01] 二分查找（有序数组）
来源：http://dali.yvedp.cn/Article/details/gt2kdvdmgov.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jianghu66.top/Article/details/gt2qpggxayy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.andypj.xyz/Article/details/gt2axlktnwr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fengsongda.top/Article/details/gt2xrwspddp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tianlin.xyz/Article/details/gt2pmnqafog.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bxhezpuy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hnyuzrvt.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj202588.top/Article/details/gt2syrokfbi.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gt2jswqrbmg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shangyingyoupin.top/Article/details/gt2ztgocvxk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.9152youxi.cn/Article/details/gt2pzajkqfd.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.tian-w.cn/Article/details/gt2tvodeaee.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cehotaai.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aizwys.cn/Article/details/gt2rvqafzjv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.chenjidiqi.icu/Article/details/gt2sledyauv.html

Go:   slices.Sort(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vxuyjhua.html

Ruby: arr.sort
来源：http://dali.yuxming.cn/Article/details/gt2xaswoogx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nanxuanxn.top/Article/details/gt2tujvwtpw.html

[N03] 快速排序（分治示例）
来源：http://dali.xylfe.cn/Article/details/gt2wrrydmib.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.haohaochexian.top/Article/details/gt2mfgfkboz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.havefunace.top/Article/details/gt2jdlpnseh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guannengcc.top/Article/details/gt2zesgygea.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yongpay.top/Article/details/gt2bbbczabv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhixingplan.top/Article/details/gt2rtypyswk.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.birdmap.top/Article/details/gt2ijbklgua.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gotoacloud.top/Article/details/gt2hagvlqdr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zdqjudy.top/Article/details/gt2paejsqwt.html

[N04] 斐波那契数列
来源：http://dali.bjfxy.top/Article/details/gt2cugvasez.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hfpthk.cn/Article/details/gt2uqyembpi.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yuxming.cn/Article/details/gt2ovrjwiuu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.snrcjt.cn/Article/details/gt2gwjluaot.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gt2vqnzgxuj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2jfgibztj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.nanxuanxn.top/Article/details/gt2ctfjwkjn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sxryk.cn/Article/details/gt2rirzenjx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yuxming.cn/Article/details/gt2ihtzlvzo.html

[N05] 最大公约数
来源：http://dali.nwbrower.top/Article/details/gt2rsydrrdd.html

Py:   math.gcd(a, b)
来源：http://dali.hnxiangtu.top/Article/details/gt2xayxhylq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.redwolf501.top/Article/details/gt2zbltvozu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ztiazgmw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.meibo888.top/Article/details/gt2namozrkg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.smart0.xyz/Article/details/gt2zbkbhzmf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.haohaochexian.top/Article/details/gt2afjaqpfb.html

Ruby: a.gcd(b)
来源：http://dali.nwbrower.top/Article/details/gt2rdkymeki.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.aibaodan.cn/Article/details/gt2hrgpxmrp.html

[N06] 判断回文字符串
来源：http://dali.yj20258.top/Article/details/gt2cbszavmm.html

Py:   s == s[::-1]
来源：http://dali.zycfv.cn/Article/details/gt2chrlzlft.html

PHP:  $s === strrev($s);
来源：http://dali.zycfv.cn/Article/details/gt2ipndngyh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gt2jicmtqbn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gt2rpskyxxa.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.tanke756.top/Article/details/gt2yvxhpugr.html

Go:   // 双指针从两端比较
来源：http://dali.mhx1999.top/Article/details/gt2eidoysjm.html

Ruby: s == s.reverse
来源：http://dali.haohaochexian.top/Article/details/gt2opsqvoqx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sufxvd.cn/Article/details/gt2taiuzbbh.html

[N07] 两数之和（返回下标）
来源：http://dali.9152youxi.cn/Article/details/gt2vfwqudyr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hnxiangtu.top/Article/details/gt2tbjfzyac.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.fengsongda.top/Article/details/gt2rvmasanr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.chenlongwang.top/Article/details/gt2ghzospxn.html

TS:   // 手写 Map<string, number>
来源：http://dali.bjfxy.top/Article/details/gt2swmsvdlr.html

Java: // 手写 HashMap
来源：http://dali.hywenlv.cn/Article/details/gt2wyuppsip.html

Go:   // 手写 map[int]int
来源：http://dali.chenjidiqi.icu/Article/details/gt2oxbqnuhv.html

Ruby: // 手写 Hash
来源：http://dali.zhiwuduotai.top/Article/details/gt2texuyoee.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yvedp.cn/Article/details/gt2qlaecnku.html

[N08] 生成全排列
来源：http://dali.hnqzz.top/Article/details/gt2iqonxetm.html

Py:   itertools.permutations(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2lwwrmnwc.html

PHP:  // 手写递归交换
来源：http://dali.hfpthk.cn/Article/details/gt2ahesxaut.html

JS:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gt2qmdwaahd.html

TS:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gt2fvxjyjww.html

Java: // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gt2iakkhajm.html

Go:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gt2ejrsutxc.html

Ruby: arr.permutation.to_a
来源：http://dali.quarkkingdee.top/Article/details/gt2kbtccraf.html

C#:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gt2fthmxfmt.html

[N09] 栈与队列
来源：http://dali.cashguo.top/Article/details/gt2npwcnxui.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gogol.net.cn/Article/details/gt2unkdfmuu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yj20258888.top/Article/details/gt2uqlfobeb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yj202588.top/Article/details/gt2kooirxaz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.aizwys.cn/Article/details/gt2qzmydttf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yongpay.top/Article/details/gt2ypcfjkfa.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.aizwys.cn/Article/details/gt2joywvwrk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.316326.xyz/Article/details/gt2iacmjvwc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hnxiangtu.top/Article/details/gt2cqdpjucj.html

[N10] 链表节点定义
来源：http://dali.havefunace.top/Article/details/gt2ydvmaafa.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ivvv.top/Article/details/gt2mkmmnrsq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhongyouzk.top/Article/details/gt2rvlparob.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzyortcf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vvrtdqxs.html

Java: class Node { int v; Node next; }
来源：http://dali.jlsjyb.cn/Article/details/gt2rzwlytyv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.fzhhl.top/Article/details/gt2augzhees.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jqgufenzy.top/Article/details/gt2qvkbpptn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2krzvayew.html

[N11] 二叉树中序遍历
来源：http://dali.nanxinkj.top/Article/details/gt2fobldkna.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.tianlin.xyz/Article/details/gt2bsnlaklz.html

PHP:  // 手写递归函数
来源：http://dali.vqdsnc.cn/Article/details/gt2apmwahnw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenjidiqi.icu/Article/details/gt2xfymyrnp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuxming.cn/Article/details/gt2ushxywgh.html

Java: // 手写递归
来源：http://dali.ehwqpu.com/Article/details/gt2qazxmfbz.html

Go:   // 手写递归
来源：http://dali.vqdsnc.cn/Article/details/gt2vljmgbqv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinqigufen.top/Article/details/gt2sgxtvhqs.html

C#:   // 手写递归
来源：http://dali.xuetiantiany.cn/Article/details/gt2eerszpkp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sxryk.cn/Article/details/gt2aokywtqf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jqgfzy.top/Article/details/gt2bkclqfor.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.bjfxy.top/Article/details/gt2hrcoelew.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj202588.top/Article/details/gt2rkmwagxc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgufenzy.top/Article/details/gt2vjrmtogh.html


<!-- 参考信息 -->