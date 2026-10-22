代发 wailian999

Ruby: JSON.pretty_generate(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2clxsrzzc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hywenlv.cn/Article/details/gt2hcymaokg.html

[K04] 读取 JSON 文件
来源：http://dali.dashuyun.cn/Article/details/gt2hxtzqvty.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.meibo888.top/Article/details/gt2glrrvbrm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.mhx1999.top/Article/details/gt2hnkqpmcx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.c1oappe.top/Article/details/gt2fsawkmcf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.9152youxi.cn/Article/details/gt2vmtjjdsl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nanxinkj.top/Article/details/gt2ickjmgpr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jyoumei.cn/Article/details/gt2snhlxsmp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yj202588.top/Article/details/gt2dljeahse.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2isiksdxh.html

[K05] 深拷贝对象
来源：http://dali.svipenyu.cn/Article/details/gt2xzjnmgvc.html

Py:   copy.deepcopy(obj)
来源：http://dali.ybcxt.top/Article/details/gt2ifauldsd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yj20258.top/Article/details/gt2dqjpvqll.html

JS:   structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gt2rqcfyaor.html

TS:   structuredClone(obj)
来源：http://dali.meibo888.top/Article/details/gt2wuntmqor.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinqigufen.top/Article/details/gt2hiyzwzbc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.guowangkeji.top/Article/details/gt2tmidjzvw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nanxinkj.top/Article/details/gt2deqtzpyo.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.chenlongwang.top/Article/details/gt2ncxhvvwy.html

[K06] 解析 URL 查询串
来源：http://dali.tianlin.xyz/Article/details/gt2rjwberky.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yongpay.top/Article/details/gt2bbcixfsv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ppjwa.cn/Article/details/gt2cocidtot.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigufen.top/Article/details/gt2qqefzvdb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.birdmap.top/Article/details/gt2bodjwvat.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2tywszgew.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gt2miqwmjzm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.tanke756.top/Article/details/gt2psqpugkx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hongshengwenyu.top/Article/details/gt2vhnmbpzg.html

[K07] 进制转换
来源：http://dali.hongshengwenyu.top/Article/details/gt2ffwgzhja.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gt2jhyukelm.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhixingplan.top/Article/details/gt2gjnyvjzo.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pdzehobz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gt2fiuvlqgm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dfsbiuoz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nwbrower.top/Article/details/gt2ynaovwwj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cdnleiting.top/Article/details/gt2orzofxvi.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gt2bcivdbpn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.guowangkeji.top/Article/details/gt2bvtfgidp.html

Py:   pickle.dumps(obj)
来源：http://dali.316326.xyz/Article/details/gt2tczzwrsn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nwbrower.top/Article/details/gt2qiiagamb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258.top/Article/details/gt2zyeciacb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ppjwa.cn/Article/details/gt2ttdhpgfi.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ehwqpu.com/Article/details/gt2fgxrmrnl.html

Go:   encoding/gob
来源：http://dali.gzhubu.top/Article/details/gt2huhcsfte.html

Ruby: Marshal.dump(obj)
来源：http://dali.redwolf501.top/Article/details/gt2xfbjfdft.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.kuanghao11.cn/Article/details/gt2pjyknvde.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2mxfqgdef.html

L. 网络请求
来源：http://dali.cdnleiting.top/Article/details/gt2hnvbkgls.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2vnwwdgfh.html

[L01] 发送 GET 请求
来源：http://dali.andypj.xyz/Article/details/gt2xcvqzfxd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yuxming.cn/Article/details/gt2xarfosid.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nanxuanxn.top/Article/details/gt2jbvlnwfs.html

JS:   await fetch(url)
来源：http://dali.zhixingplan.top/Article/details/gt2zxqummej.html

TS:   await fetch(url)
来源：http://dali.yj202588.top/Article/details/gt2srqyraij.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hnqzz.top/Article/details/gt2uvdfupyw.html

Go:   resp, err := http.Get(url)
来源：http://dali.sxryk.cn/Article/details/gt2kxbwqfxv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.fzhhl.top/Article/details/gt2eovgsdif.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.daria6918.cn/Article/details/gt2eoiawhmp.html

[L02] 发送 POST JSON
来源：http://dali.cucudq.cn/Article/details/gt2qzpiongg.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.daria6918.cn/Article/details/gt2qtltpnmm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.fengsongda.top/Article/details/gt2axfmzyxo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.9152youxi.cn/Article/details/gt2xyivxscc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dashuyun.cn/Article/details/gt2jdrokcfi.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hnqzz.top/Article/details/gt2hcjjhmzg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yvedp.cn/Article/details/gt2yxwwmihy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sufanegx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.guannengcc.top/Article/details/gt2yxkzjaia.html

[L03] 设置自定义请求头
来源：http://dali.zycfv.cn/Article/details/gt2sfopykyz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.c1oappe.top/Article/details/gt2vttudyrr.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hnxiangtu.top/Article/details/gt2cbqybdps.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guannengcc.top/Article/details/gt2cuxwwhsz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.smart0.xyz/Article/details/gt2zwqnrubg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ilghrzmu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hnqzz.top/Article/details/gt2stnzwupj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.guowangkeji.top/Article/details/gt2anngcmhw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gogol.net.cn/Article/details/gt2mixuiler.html

[L04] 设置超时
来源：http://dali.yj20258888.top/Article/details/gt2touhvkht.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hywenlv.cn/Article/details/gt2xightydv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xuetiantiany.cn/Article/details/gt2gmkupura.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ivvv.top/Article/details/gt2cycufnzu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gzhubu.top/Article/details/gt2drtuynrm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ybcxt.top/Article/details/gt2vzperxiz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.pengpengdd.cyou/Article/details/gt2dezrehyu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.haohaochexian.top/Article/details/gt2qimyvyim.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gzhubu.top/Article/details/gt2lrsplfpu.html

[L05] 上传文件（multipart）
来源：http://dali.ydzc1.top/Article/details/gt2buupmlvt.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xuanzx.com/Article/details/gt2xdxuddmt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ivvv.top/Article/details/gt2bpmyfprw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.andypj.xyz/Article/details/gt2ugyxrxkh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xinyue.icu/Article/details/gt2bckmdute.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.tanke756.top/Article/details/gt2zvwtqgwb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yuanzhike.top/Article/details/gt2jmrzdiaf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cqqwz.cn/Article/details/gt2sapfnrsa.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2dueniyiy.html

[L06] 解析响应为 JSON
来源：http://dali.chenlongwang.top/Article/details/gt2zamksxty.html

Py:   resp.json()
来源：http://dali.iojbl.cn/Article/details/gt2fgvuutng.html

PHP:  json_decode($body, true);
来源：http://dali.ehwqpu.com/Article/details/gt2fptprqfb.html

JS:   await resp.json()
来源：http://dali.xziqi.cn/Article/details/gt2hehzvzcw.html

TS:   await resp.json()
来源：http://dali.c1oappe.top/Article/details/gt2srontujt.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jlsjyb.cn/Article/details/gt2kdrrrcru.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2avpikqcp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shzxlz.cn/Article/details/gt2igxlwyyw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hfpthk.cn/Article/details/gt2kfoaghxw.html

[L07] 处理 HTTP 状态码
来源：http://dali.zdqjudy.top/Article/details/gt2yltfpvje.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.316326.xyz/Article/details/gt2tqkdhmes.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hongshengwenyu.top/Article/details/gt2zlxbhcfb.html

JS:   resp.ok;  resp.status
来源：http://dali.hongshengwenyu.top/Article/details/gt2jhgpngkr.html

TS:   resp.ok;  resp.status
来源：http://dali.hnqzz.top/Article/details/gt2vdftbhxl.html

Java: resp.statusCode()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uabrfcoc.html

Go:   resp.StatusCode
来源：http://dali.zhongyouzk.top/Article/details/gt2nastcbwk.html

Ruby: resp.code.to_i
来源：http://dali.tianlin.xyz/Article/details/gt2kflemthz.html

C#:   (int)resp.StatusCode
来源：http://dali.aibaodan.cn/Article/details/gt2wjbschcc.html

[L08] 并发请求多个地址
来源：http://dali.aibaodan.cn/Article/details/gt2kfmztixo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jyoumei.cn/Article/details/gt2qrygvfzp.html

PHP:  curl_multi_init() 系列
来源：http://dali.nanxinkj.top/Article/details/gt2eqcrrcur.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jianghu66.top/Article/details/gt2gowtwlpa.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nwbrower.top/Article/details/gt2dcwpwxsp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yonumen.top/Article/details/gt2tznlkthu.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj20258888.top/Article/details/gt2myssuwwm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sxryk.cn/Article/details/gt2bmuqoeoa.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhengqikj.top/Article/details/gt2degpxppr.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2zxrbsngr.html

M. 命令行 / 进程 / 环境
来源：http://dali.nanxuanxn.top/Article/details/gt2xebfhhbg.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2zbgexqfn.html

[M01] 读取命令行参数
来源：http://dali.mhx1999.top/Article/details/gt2agkdnplt.html

Py:   sys.argv[1:]
来源：http://dali.zdqjudy.top/Article/details/gt2orqzvrrm.html

PHP:  $argv;  $argc;
来源：http://dali.hnxiangtu.top/Article/details/gt2xoybjwlb.html

JS:   process.argv.slice(2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2drygmfzi.html

TS:   process.argv.slice(2)
来源：http://dali.316326.xyz/Article/details/gt2gdndcdzk.html

Java: args 数组（main 方法参数）
来源：http://dali.zhoulong.xyz/Article/details/gt2wyensedr.html

Go:   os.Args[1:]
来源：http://dali.aibaodan.cn/Article/details/gt2jrupvjeq.html

Ruby: ARGV
来源：http://dali.zhoulong.xyz/Article/details/gt2vknxzswb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.daxiang520.top/Article/details/gt2ytbizqep.html

[M02] 读取环境变量
来源：http://dali.ybcxt.top/Article/details/gt2xpjqinno.html

Py:   os.environ.get("HOME")
来源：http://dali.gotoacloud.top/Article/details/gt2crhxmoya.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cheryme.top/Article/details/gt2pupypoqo.html

JS:   process.env.HOME
来源：http://dali.yvedp.cn/Article/details/gt2bclpdcid.html

TS:   process.env.HOME
来源：http://dali.tanke756.top/Article/details/gt2pkczoezt.html

Java: System.getenv("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gt2myqynhlz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.meibo888.top/Article/details/gt2qfzkuakz.html

Ruby: ENV["HOME"]
来源：http://dali.0kj1m.cn/Article/details/gt2kzhwilex.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gogol.net.cn/Article/details/gt2ryeyoydl.html

[M03] 执行外部命令
来源：http://dali.yangfankeji.com/Article/details/gt2cmkprnfz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.guannengcc.top/Article/details/gt2zdmaksqb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.redwolf501.top/Article/details/gt2nrzczobx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.quarkkingdee.top/Article/details/gt2uqlvzhqw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxuanxn.top/Article/details/gt2olgjyodr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hammf.cn/Article/details/gt2oyovecfv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hywenlv.cn/Article/details/gt2ifibhber.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenzaomai.com/Article/details/gt2asvcsabh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fajzrsqt.html

[M04] 获取当前工作目录
来源：http://dali.guowangkeji.top/Article/details/gt2qqatrjfq.html

Py:   os.getcwd()
来源：http://dali.nwbrower.top/Article/details/gt2asxgwgtk.html

PHP:  getcwd();
来源：http://dali.aibaodan.cn/Article/details/gt2lsxlgsqs.html

JS:   process.cwd()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ocbhjyct.html

TS:   process.cwd()
来源：http://dali.tianlin.xyz/Article/details/gt2kvirrqwh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ppjwa.cn/Article/details/gt2doiqbvuc.html

Go:   os.Getwd()
来源：http://dali.zhongyouzk.top/Article/details/gt2obaqairi.html

Ruby: Dir.pwd
来源：http://dali.pengpengdd.cyou/Article/details/gt2bkvtbwpb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shzxlz.cn/Article/details/gt2wrwjfytc.html

[M05] 设置退出码
来源：http://dali.shanyushiyangtech.top/Article/details/gt2swefwwbx.html

Py:   sys.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2zmacyquc.html

PHP:  exit(1);
来源：http://dali.cqqwz.cn/Article/details/gt2efgpmxgb.html

JS:   process.exit(1)
来源：http://dali.daria6918.cn/Article/details/gt2wkrcqgqj.html

TS:   process.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gt2kzlexeis.html

Java: System.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2caavnixk.html

Go:   os.Exit(1)
来源：http://dali.zdqjudy.top/Article/details/gt2wgnuomjr.html

Ruby: exit 1
来源：http://dali.guannengcc.top/Article/details/gt2muelkpfg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.iojbl.cn/Article/details/gt2hwyqztem.html

[M06] 向标准错误输出
来源：http://dali.chenjidiqi.icu/Article/details/gt2ikvkpcrj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xylfe.cn/Article/details/gt2ruyweyge.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.aibaodan.cn/Article/details/gt2hydtioee.html

JS:   console.error("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fyaysjna.html

TS:   console.error("err")
来源：http://dali.jyoumei.cn/Article/details/gt2orfzputq.html

Java: System.err.println("err")
来源：http://dali.tian-w.cn/Article/details/gt2ajrdfwkn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yueranfly.top/Article/details/gt2grldagap.html

Ruby: warn "err"
来源：http://dali.gaohongyu789.top/Article/details/gt2ckuhrjgg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.chenzaomai.com/Article/details/gt2zrwerawv.html

[M07] 判断是否为主入口
来源：http://dali.shangyingyoupin.top/Article/details/gt2eqeptxkz.html

Py:   if __name__ == "__main__":
来源：http://dali.aibaodan.cn/Article/details/gt2abegzwuv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jianghu66.top/Article/details/gt2vqyltdaw.html

JS:   require.main === module
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zqjncjcj.html

TS:   require.main === module
来源：http://dali.guannengcc.top/Article/details/gt2msyjhziz.html

Java: public static void main(String[] args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oqhoveph.html

Go:   func main()
来源：http://dali.sysykeji.top/Article/details/gt2drhqobhz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cucudq.cn/Article/details/gt2drkgscvc.html

C#:   static void Main(string[] args)
来源：http://dali.sxryk.cn/Article/details/gt2dxoxeioz.html

[M08] 获取系统与运行时信息
来源：http://dali.haohaochexian.top/Article/details/gt2lmeifxdq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.fengsongda.top/Article/details/gt2piekdxyx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shangyingyoupin.top/Article/details/gt2glayxann.html

JS:   process.platform;  process.version
来源：http://dali.ydzc1.top/Article/details/gt2dbkjjqoy.html

TS:   process.platform;  process.version
来源：http://dali.yj20258888.top/Article/details/gt2fzwbiyfi.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cheryme.top/Article/details/gt2nqssxspm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xuanzx.com/Article/details/gt2furhfonx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.meibo888.top/Article/details/gt2elieinwz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2onqgpsbf.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2hnpwnncj.html

N. 数据结构与算法
来源：http://dali.cashguo.top/Article/details/gt2xteyhuvw.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2heiixjbd.html

[N01] 二分查找（有序数组）
来源：http://dali.chenjidiqi.icu/Article/details/gt2ntcmmzfz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.daxiang520.top/Article/details/gt2duazosjj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qcnriztm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cheryme.top/Article/details/gt2yecyytak.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwflxfhn.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gt2xcujgmap.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ivvv.top/Article/details/gt2urkxnrda.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yuxming.cn/Article/details/gt2tkuiunei.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.mhx1999.top/Article/details/gt2pzrbiyzs.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nwbrower.top/Article/details/gt2jarlawbi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jiagoushi.top/Article/details/gt2edbgcxjz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.dashuyun.cn/Article/details/gt2rdqipjef.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nwbrower.top/Article/details/gt2jesrzgmk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jiagoushi.top/Article/details/gt2gojrnnpi.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.havefunace.top/Article/details/gt2zbzzdivd.html

Go:   slices.Sort(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jfqrhwgd.html

Ruby: arr.sort
来源：http://dali.snrcjt.cn/Article/details/gt2achdosxs.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nwbrower.top/Article/details/gt2jwwkfrdq.html

[N03] 快速排序（分治示例）
来源：http://dali.dianchejie.cn/Article/details/gt2kegitjvu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hfpthk.cn/Article/details/gt2qohcorvw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhiwuduotai.top/Article/details/gt2weyqtpnr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigfzy.top/Article/details/gt2ghdysmxm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pycfn.com/Article/details/gt2trfhgjkc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yvedp.cn/Article/details/gt2qtmnorqo.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jmpmfilu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xuanzx.com/Article/details/gt2vkwwpent.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xuetiantiany.cn/Article/details/gt2anpsfjia.html

[N04] 斐波那契数列
来源：http://dali.dashuyun.cn/Article/details/gt2xxslhaxj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2dnomqudc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gogol.net.cn/Article/details/gt2zkatspwk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gzhubu.top/Article/details/gt2uykekbht.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gt2lbcopeei.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yonumen.top/Article/details/gt2stdpcbrq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.iojbl.cn/Article/details/gt2frmllvmk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sweek.top/Article/details/gt2yktexyav.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yangfankeji.com/Article/details/gt2ewjwqzkf.html

[N05] 最大公约数
来源：http://dali.shuidangran.top/Article/details/gt2qzeopwur.html

Py:   math.gcd(a, b)
来源：http://dali.wangdashe.top/Article/details/gt2ierztdff.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.vqdsnc.cn/Article/details/gt2fiahvjpo.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jiagoushi.top/Article/details/gt2igsxgkpi.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ydzc1.top/Article/details/gt2kiudmqxi.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jqgfzy.top/Article/details/gt2mafefxyc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shangyingyoupin.top/Article/details/gt2qagsfntq.html

Ruby: a.gcd(b)
来源：http://dali.hammf.cn/Article/details/gt2btxqenmn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.c1oappe.top/Article/details/gt2orebbkhr.html

[N06] 判断回文字符串
来源：http://dali.ppjwa.cn/Article/details/gt2asqminrw.html

Py:   s == s[::-1]
来源：http://dali.yueranfly.top/Article/details/gt2swnvbskr.html

PHP:  $s === strrev($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qcmfdtmt.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gt2qtaqfgxc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gt2hcvnrphg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iyzqpdpa.html

Go:   // 双指针从两端比较
来源：http://dali.gaohongyu789.top/Article/details/gt2shxexptw.html

Ruby: s == s.reverse
来源：http://dali.zhiwuduotai.top/Article/details/gt2haqbfdmb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.meibo888.top/Article/details/gt2ycoyxdwx.html

[N07] 两数之和（返回下标）
来源：http://dali.yuxming.cn/Article/details/gt2dfdsxgcv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhiwuduotai.top/Article/details/gt2rqccgzel.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jqgufenzy.top/Article/details/gt2elnimfql.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cdnleiting.top/Article/details/gt2gmswxjyc.html

TS:   // 手写 Map<string, number>
来源：http://dali.jlsjyb.cn/Article/details/gt2zbsxvjan.html

Java: // 手写 HashMap
来源：http://dali.hnqzz.top/Article/details/gt2wlnmfesl.html

Go:   // 手写 map[int]int
来源：http://dali.yanxiufei.cn/Article/details/gt2fmqzwgqo.html

Ruby: // 手写 Hash
来源：http://dali.jqgufenzy.top/Article/details/gt2mmfpxgtg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.tanke756.top/Article/details/gt2eagtwibu.html

[N08] 生成全排列
来源：http://dali.cqqwz.cn/Article/details/gt2dlgyzlzm.html

Py:   itertools.permutations(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2thlhosmi.html

PHP:  // 手写递归交换
来源：http://dali.kuanghao11.cn/Article/details/gt2zvspfbra.html

JS:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gt2jnfsafub.html

TS:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gt2kqeeskwb.html

Java: // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gt2motftnne.html

Go:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gt2wwzixwdw.html

Ruby: arr.permutation.to_a
来源：http://dali.ydzc1.top/Article/details/gt2lhepncvy.html

C#:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gt2zdnndkdp.html

[N09] 栈与队列
来源：http://dali.daria6918.cn/Article/details/gt2yrweibwz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zdqjudy.top/Article/details/gt2okrhwzmt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jqgufenzy.top/Article/details/gt2gcryeapn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ybcxt.top/Article/details/gt2yificwcn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.haohaochexian.top/Article/details/gt2ucskdwhd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zycfv.cn/Article/details/gt2tgfuimre.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zdqjudy.top/Article/details/gt2jvgrletn.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gzhubu.top/Article/details/gt2kdowgnwk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xdutteuv.html

[N10] 链表节点定义
来源：http://dali.gaohongyu789.top/Article/details/gt2rpulomio.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yuanzhike.top/Article/details/gt2lmmcgvcv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shzxlz.cn/Article/details/gt2bmputfae.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sxryk.cn/Article/details/gt2kfzcbkml.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.tanke756.top/Article/details/gt2vauwezoj.html

Java: class Node { int v; Node next; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2hbnhykdx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenlongwang.top/Article/details/gt2txmtcuql.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.nwbrower.top/Article/details/gt2qwudrify.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.chenlongwang.top/Article/details/gt2jeejylnu.html

[N11] 二叉树中序遍历
来源：http://dali.aizwys.cn/Article/details/gt2abukwbap.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinqigfzy.top/Article/details/gt2hftpvrpr.html

PHP:  // 手写递归函数
来源：http://dali.xinyue.icu/Article/details/gt2qbkldvgd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuanzhike.top/Article/details/gt2uywqmguo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gotoacloud.top/Article/details/gt2yvpqkjuq.html

Java: // 手写递归
来源：http://dali.jqgfzy.top/Article/details/gt2iglgbbxj.html

Go:   // 手写递归
来源：http://dali.zhengqikj.top/Article/details/gt2piknjyjc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.fengsongda.top/Article/details/gt2yuikptlr.html

C#:   // 手写递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dsfzolhl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zdqjudy.top/Article/details/gt2nvfofxrl.html


<!-- 参考信息 -->