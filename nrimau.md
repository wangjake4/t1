代发 wailian999

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xuanzx.com/Article/details/gtstiqmuon.html

Go:   json.Marshal(obj)
来源：http://dali.aizwys.cn/Article/details/gtjabjlnpv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hnxiangtu.top/Article/details/gtpyzpexxl.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gterqehxur.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gtzraflhty.html

Py:   json.loads(s)
来源：http://dali.meibo888.top/Article/details/gtddgcihmf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shuidangran.top/Article/details/gtjhjsyiih.html

JS:   JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gtbbprywwg.html

TS:   JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gtonkpzcte.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.daria6918.cn/Article/details/gtylqsxqae.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.tian-w.cn/Article/details/gtplvklsaw.html

Ruby: JSON.parse(s)
来源：http://dali.yj20258888.top/Article/details/gtjrownndn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.wangdashe.top/Article/details/gtfbyzmwgv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shuidangran.top/Article/details/gtvmctticd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cashguo.top/Article/details/gtkentiwwf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yanxiufei.cn/Article/details/gtjriymhww.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258.top/Article/details/gtovhkoxtf.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zdqjudy.top/Article/details/gtncirzmbz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yuxming.cn/Article/details/gtdezenuph.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.fengsongda.top/Article/details/gtrzbtfymb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yangfankeji.com/Article/details/gtzspibtvw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nanxuanxn.top/Article/details/gtirkpzysq.html

[K04] 读取 JSON 文件
来源：http://dali.snrcjt.cn/Article/details/gtwotlwufg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtypxkedhn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.tian-w.cn/Article/details/gtfzrhjojb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.meibo888.top/Article/details/gtdypbvopb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jianghu66.top/Article/details/gtobzjmnov.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jianghu66.top/Article/details/gthotqjakx.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gttmmjahps.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jiagoushi.top/Article/details/gtgvadxrpq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.guannengcc.top/Article/details/gtauwzmune.html

[K05] 深拷贝对象
来源：http://dali.svipenyu.cn/Article/details/gtfkvjnfvs.html

Py:   copy.deepcopy(obj)
来源：http://dali.yuanzhike.top/Article/details/gticvvocbm.html

PHP:  unserialize(serialize($obj));
来源：http://dali.pengpengdd.cyou/Article/details/gtzrdgxxia.html

JS:   structuredClone(obj)
来源：http://dali.yj20258.top/Article/details/gtmnkllkci.html

TS:   structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gtiiaqulwh.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hnxiangtu.top/Article/details/gtkkqrffkf.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yvedp.cn/Article/details/gtnrixltmg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hysaishi.cn/Article/details/gtbzjaotyh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.aizwys.cn/Article/details/gtjgibvqvk.html

[K06] 解析 URL 查询串
来源：http://dali.chenzaomai.com/Article/details/gtvpthnhtl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.chenzaomai.com/Article/details/gthkhgjepf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zdqjudy.top/Article/details/gtxhirexru.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yanxiufei.cn/Article/details/gtppeowjhh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.0kj1m.cn/Article/details/gtjrsepchm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ywan-chungtsiang.top/Article/details/gteuvzhnvw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.mhx1999.top/Article/details/gtehjjxwuq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtawlctcof.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gtxevmvnvz.html

[K07] 进制转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsbvbetus.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtgzrdvhug.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jqgfzy.top/Article/details/gtadttivod.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gtuaqvjpkk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gtjcteyqhg.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsppkjkmh.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yangfankeji.com/Article/details/gtgbjvwxrq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.tian-w.cn/Article/details/gtcdmtpqlx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.sweek.top/Article/details/gttbqkifsi.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zycfv.cn/Article/details/gtiicdzyou.html

Py:   pickle.dumps(obj)
来源：http://dali.hammf.cn/Article/details/gtdxoirtoo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwaleuhno.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gtymwbzaec.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yuanzhike.top/Article/details/gtsxzqkkhv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ydzc1.top/Article/details/gtdxuhqqzu.html

Go:   encoding/gob
来源：http://dali.jinqigufen.top/Article/details/gtakwfqhmx.html

Ruby: Marshal.dump(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmwcjxbrk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhiwuduotai.top/Article/details/gtwgukpgln.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtckvfwjea.html

L. 网络请求
来源：http://dali.jinyuanbaomall.cn/Article/details/gtulbyipwu.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtzxkzevqr.html

[L01] 发送 GET 请求
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfqhehxt.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shanyushiyangtech.top/Article/details/gtakzykolk.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.guowangkeji.top/Article/details/gtvbytagsz.html

JS:   await fetch(url)
来源：http://dali.9152youxi.cn/Article/details/gtbzhxidfg.html

TS:   await fetch(url)
来源：http://dali.yangfankeji.com/Article/details/gtaqtrxifa.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xinyue.icu/Article/details/gtrnkdjfpz.html

Go:   resp, err := http.Get(url)
来源：http://dali.jyoumei.cn/Article/details/gtgmvvaofp.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhixingplan.top/Article/details/gtxgkkwrcp.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinqigfzy.top/Article/details/gthkwcszbp.html

[L02] 发送 POST JSON
来源：http://dali.pengpengdd.cyou/Article/details/gtohajzdgh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.aizwys.cn/Article/details/gtwmxtpbkq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinghuilouyu.cn/Article/details/gthartpjym.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.quarkkingdee.top/Article/details/gtchrlugwh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gtcciscgnl.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.wangdashe.top/Article/details/gtlffehqut.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hnxiangtu.top/Article/details/gtgrguzeff.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpbbmzhgd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhoulong.xyz/Article/details/gtoqitsves.html

[L03] 设置自定义请求头
来源：http://dali.xinyue.icu/Article/details/gtcybigvvc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yj202588.top/Article/details/gtvpahbjal.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gogol.net.cn/Article/details/gttjxfpfue.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangtech.top/Article/details/gtghrbvnmj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cheryme.top/Article/details/gtojisrcku.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yj20258.top/Article/details/gtdqfhfsqk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhoulong.xyz/Article/details/gtpppxqmxh.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenjidiqi.icu/Article/details/gtdlxrpejh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nwbrower.top/Article/details/gtvgwicxue.html

[L04] 设置超时
来源：http://dali.wangdashe.top/Article/details/gtfnbukdvv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.guannengcc.top/Article/details/gtrfdqdzzv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hammf.cn/Article/details/gtkuszgbpg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cqqwz.cn/Article/details/gtxpsswbev.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gotoacloud.top/Article/details/gtvnxpwbpb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.birdmap.top/Article/details/gtyjbarivm.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yj20258.top/Article/details/gtsylqqcpi.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shangyingyoupin.top/Article/details/gtpuqymcvw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbxvrwgzi.html

[L05] 上传文件（multipart）
来源：http://dali.c1oappe.top/Article/details/gtsbcpgwwr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinqigufen.top/Article/details/gtsjfwqecz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.chenlongwang.top/Article/details/gtawbmuiqw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sweek.top/Article/details/gtyqiiqxxn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ybcxt.top/Article/details/gtiujpvdyw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.fzhhl.top/Article/details/gtfelcuzex.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuuiiheun.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cqqwz.cn/Article/details/gtkqbvzbin.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.aizwys.cn/Article/details/gtxbbbswve.html

[L06] 解析响应为 JSON
来源：http://dali.hfpthk.cn/Article/details/gtwdgormgl.html

Py:   resp.json()
来源：http://dali.zhongyouzk.top/Article/details/gtjorsytpj.html

PHP:  json_decode($body, true);
来源：http://dali.daria6918.cn/Article/details/gtdnyzisml.html

JS:   await resp.json()
来源：http://dali.feifeiyinyue.top/Article/details/gtwantbbrb.html

TS:   await resp.json()
来源：http://dali.havefunace.top/Article/details/gtuktdlnms.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.snrcjt.cn/Article/details/gtsmyluqcs.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xinyue.icu/Article/details/gtmidifhvz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.havefunace.top/Article/details/gtxrpycyab.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yongpay.top/Article/details/gthvqrkrkh.html

[L07] 处理 HTTP 状态码
来源：http://dali.snrcjt.cn/Article/details/gtlexsilbf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtemavwocb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhengqikj.top/Article/details/gtffhhufwp.html

JS:   resp.ok;  resp.status
来源：http://dali.chenzaomai.com/Article/details/gtfhwegamu.html

TS:   resp.ok;  resp.status
来源：http://dali.0kj1m.cn/Article/details/gtptdmbtas.html

Java: resp.statusCode()
来源：http://dali.cdnleiting.top/Article/details/gtrjrshhao.html

Go:   resp.StatusCode
来源：http://dali.xylfe.cn/Article/details/gthuwsurhk.html

Ruby: resp.code.to_i
来源：http://dali.sweek.top/Article/details/gtwomzurbw.html

C#:   (int)resp.StatusCode
来源：http://dali.mhx1999.top/Article/details/gtvhpvlixy.html

[L08] 并发请求多个地址
来源：http://dali.xinyue.icu/Article/details/gtebcadpgc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ehwqpu.com/Article/details/gtsaojwzvk.html

PHP:  curl_multi_init() 系列
来源：http://dali.chenzaomai.com/Article/details/gtczvtgxzc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhengqikj.top/Article/details/gtneiqdbka.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj202588.top/Article/details/gtlqyikkfl.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jqgufenzy.top/Article/details/gtmrnprldx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhiwuduotai.top/Article/details/gtojvcwyxi.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzenljfcd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.c1oappe.top/Article/details/gtfqcwrjrx.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtbkyvhivv.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhiwuduotai.top/Article/details/gtfkkapkqq.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtqvdzbinx.html

[M01] 读取命令行参数
来源：http://dali.yuxming.cn/Article/details/gtbiuejthp.html

Py:   sys.argv[1:]
来源：http://dali.hysaishi.cn/Article/details/gtukbwoxoh.html

PHP:  $argv;  $argc;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrdytjemy.html

JS:   process.argv.slice(2)
来源：http://dali.ppjwa.cn/Article/details/gtdfopwrty.html

TS:   process.argv.slice(2)
来源：http://dali.sufxvd.cn/Article/details/gtwmwycbbd.html

Java: args 数组（main 方法参数）
来源：http://dali.gzhubu.top/Article/details/gtfnfmeywk.html

Go:   os.Args[1:]
来源：http://dali.birdmap.top/Article/details/gtmlujrfou.html

Ruby: ARGV
来源：http://dali.feifeiyinyue.top/Article/details/gtoyykedzv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenjidiqi.icu/Article/details/gtrvkpucrf.html

[M02] 读取环境变量
来源：http://dali.nanxinkj.top/Article/details/gticmozicj.html

Py:   os.environ.get("HOME")
来源：http://dali.nanxinkj.top/Article/details/gtmkmggbkn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.0kj1m.cn/Article/details/gtczxlzdic.html

JS:   process.env.HOME
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgsrsadqr.html

TS:   process.env.HOME
来源：http://dali.cheryme.top/Article/details/gtrvdjewjn.html

Java: System.getenv("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gtuzihlosi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gtdllsnxoo.html

Ruby: ENV["HOME"]
来源：http://dali.nanxuanxn.top/Article/details/gtibyvkgbo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.nwbrower.top/Article/details/gtytrobvnh.html

[M03] 执行外部命令
来源：http://dali.wangshuangyany.cn/Article/details/gtubxrtxjt.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yj202588.top/Article/details/gtndhvdbom.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.smart0.xyz/Article/details/gtidwxnokv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hongshengwenyu.top/Article/details/gtbpfgydhe.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.bjfxy.top/Article/details/gtatqikzgj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cashguo.top/Article/details/gtbqseyicz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jiagoushi.top/Article/details/gtcdxhcvrr.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yvedp.cn/Article/details/gtyyomxsel.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jqgufenzy.top/Article/details/gtscrqaath.html

[M04] 获取当前工作目录
来源：http://dali.ppjwa.cn/Article/details/gtoniigdjc.html

Py:   os.getcwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrsiivjds.html

PHP:  getcwd();
来源：http://dali.hfpthk.cn/Article/details/gtvpczvnuv.html

JS:   process.cwd()
来源：http://dali.guowangkeji.top/Article/details/gtbqzobnxe.html

TS:   process.cwd()
来源：http://dali.pengpengdd.cyou/Article/details/gtswrntstt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.pycfn.com/Article/details/gttgkadczq.html

Go:   os.Getwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gtpncuegkq.html

Ruby: Dir.pwd
来源：http://dali.zhoulong.xyz/Article/details/gtvxplnyim.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.c1oappe.top/Article/details/gtwzptylhu.html

[M05] 设置退出码
来源：http://dali.sxryk.cn/Article/details/gtqnxgkeoi.html

Py:   sys.exit(1)
来源：http://dali.havefunace.top/Article/details/gtqsuvwusx.html

PHP:  exit(1);
来源：http://dali.birdmap.top/Article/details/gttcuoolbu.html

JS:   process.exit(1)
来源：http://dali.redwolf501.top/Article/details/gtjwydmpbv.html

TS:   process.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtabtiexlp.html

Java: System.exit(1)
来源：http://dali.guannengcc.top/Article/details/gtuitqhfzd.html

Go:   os.Exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtwjunxyts.html

Ruby: exit 1
来源：http://dali.yj20258.top/Article/details/gtficsbaqm.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.wangdashe.top/Article/details/gtywgzhkrb.html

[M06] 向标准错误输出
来源：http://dali.birdmap.top/Article/details/gtcmsbdypd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.vqdsnc.cn/Article/details/gtffoptshk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zycfv.cn/Article/details/gtbmuqqrod.html

JS:   console.error("err")
来源：http://dali.havefunace.top/Article/details/gtcuciwidv.html

TS:   console.error("err")
来源：http://dali.yongpay.top/Article/details/gtcfjtpyef.html

Java: System.err.println("err")
来源：http://dali.gzhubu.top/Article/details/gtnmcvlhco.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hnqzz.top/Article/details/gttgieucfv.html

Ruby: warn "err"
来源：http://dali.zdqjudy.top/Article/details/gtduccmhbk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.quarkkingdee.top/Article/details/gtxbfyrais.html

[M07] 判断是否为主入口
来源：http://dali.yj202588.top/Article/details/gtmhzhxykr.html

Py:   if __name__ == "__main__":
来源：http://dali.shuidangran.top/Article/details/gtlmdhfazf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yuxming.cn/Article/details/gtjbvafgsw.html

JS:   require.main === module
来源：http://dali.tanke756.top/Article/details/gtqsjfifxt.html

TS:   require.main === module
来源：http://dali.andypj.xyz/Article/details/gtkbiiafmx.html

Java: public static void main(String[] args)
来源：http://dali.bjfxy.top/Article/details/gtaflqfxis.html

Go:   func main()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkgnrxlxk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gzhubu.top/Article/details/gtnjpjyxrd.html

C#:   static void Main(string[] args)
来源：http://dali.316326.xyz/Article/details/gtbpnvnpzn.html

[M08] 获取系统与运行时信息
来源：http://dali.pycfn.com/Article/details/gtfhnooiis.html

Py:   platform.system();  platform.python_version()
来源：http://dali.svipenyu.cn/Article/details/gtpjskvgcc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cdnleiting.top/Article/details/gtulucoyud.html

JS:   process.platform;  process.version
来源：http://dali.gaohongyu789.top/Article/details/gtfikqpsmd.html

TS:   process.platform;  process.version
来源：http://dali.hysaishi.cn/Article/details/gthqyuuzjg.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnxiangtu.top/Article/details/gtjcgtdocx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ydzc1.top/Article/details/gtaemdogxx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xylfe.cn/Article/details/gtobmnmxpr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrwqitqzw.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtrygzklpf.html

N. 数据结构与算法
来源：http://dali.iojbl.cn/Article/details/gtvdtserub.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtpbmlspdv.html

[N01] 二分查找（有序数组）
来源：http://dali.shuidangran.top/Article/details/gtgsbbqsxs.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.316326.xyz/Article/details/gtshnuwxyh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.chenzaomai.com/Article/details/gtqpblhnpz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shuidangran.top/Article/details/gtqjpapmjh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cheryme.top/Article/details/gtqvkgjhmd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gteahavewh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yonumen.top/Article/details/gtksoszwnx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gtpvodumyh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sweek.top/Article/details/gtegsrfeis.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jianghu66.top/Article/details/gtdbfcjkqi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.havefunace.top/Article/details/gtycytfywa.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.guowangkeji.top/Article/details/gtjhlnbvws.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hongshengwenyu.top/Article/details/gtraspmskl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.c1oappe.top/Article/details/gtahnugrcx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.0kj1m.cn/Article/details/gtbaodtwkp.html

Go:   slices.Sort(arr)
来源：http://dali.cucudq.cn/Article/details/gtrrvehdsa.html

Ruby: arr.sort
来源：http://dali.aizwys.cn/Article/details/gtnzecihsq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.9152youxi.cn/Article/details/gtokzkdsob.html

[N03] 快速排序（分治示例）
来源：http://dali.zhiwuduotai.top/Article/details/gtxboxguls.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ehwqpu.com/Article/details/gtxkjckgai.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yj20258888.top/Article/details/gtfpxsgvgi.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.svipenyu.cn/Article/details/gtxnifuvmo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jlsjyb.cn/Article/details/gtrtoaqjrf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cucudq.cn/Article/details/gthwsaiacm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgmfasmcp.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hongshengwenyu.top/Article/details/gtfufhpopa.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cdnleiting.top/Article/details/gtywoesjuq.html

[N04] 斐波那契数列
来源：http://dali.daxiang520.top/Article/details/gtpjnopntj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cashguo.top/Article/details/gtuinykybx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shuidangran.top/Article/details/gtimdtwxbc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgfzy.top/Article/details/gtatqutjob.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hywenlv.cn/Article/details/gtdctvfhhz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwzfcujgg.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.c1oappe.top/Article/details/gtkaqqydow.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhixingplan.top/Article/details/gtdvobrwwb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shzxlz.cn/Article/details/gtgutxspdh.html

[N05] 最大公约数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjuhhcfws.html

Py:   math.gcd(a, b)
来源：http://dali.fzhhl.top/Article/details/gtprlsiuiy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhixingplan.top/Article/details/gtfkqnvdfc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtgfronakn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenlongwang.top/Article/details/gtakzwilrw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yuxming.cn/Article/details/gtmnzweuuk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cqqwz.cn/Article/details/gtfjkqdvai.html

Ruby: a.gcd(b)
来源：http://dali.jlsjyb.cn/Article/details/gtefouyseo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhengqikj.top/Article/details/gtgatncrzu.html

[N06] 判断回文字符串
来源：http://dali.0kj1m.cn/Article/details/gtjsotgbmb.html

Py:   s == s[::-1]
来源：http://dali.chenlongwang.top/Article/details/gtnvmvttst.html

PHP:  $s === strrev($s);
来源：http://dali.havefunace.top/Article/details/gtuijcdbyg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gtrsgsfbgw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gthagrlmpu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yvedp.cn/Article/details/gtxtfmebyw.html

Go:   // 双指针从两端比较
来源：http://dali.gotoacloud.top/Article/details/gtqxtvyntp.html

Ruby: s == s.reverse
来源：http://dali.cashguo.top/Article/details/gtjwjywbwx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.nanxinkj.top/Article/details/gtczbxbufp.html

[N07] 两数之和（返回下标）
来源：http://dali.cashguo.top/Article/details/gttupmodrj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.feifeiyinyue.top/Article/details/gtpnvbelnf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cucudq.cn/Article/details/gtdsjqthna.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cqqwz.cn/Article/details/gthyosshbv.html

TS:   // 手写 Map<string, number>
来源：http://dali.hysaishi.cn/Article/details/gtautfbhxg.html

Java: // 手写 HashMap
来源：http://dali.zhixingplan.top/Article/details/gtyumauuyz.html

Go:   // 手写 map[int]int
来源：http://dali.xylfe.cn/Article/details/gtrwfyxsrh.html

Ruby: // 手写 Hash
来源：http://dali.gogol.net.cn/Article/details/gtpodzzbyq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.guannengcc.top/Article/details/gtimrvmfyd.html

[N08] 生成全排列
来源：http://dali.redwolf501.top/Article/details/gtrnhnvyga.html

Py:   itertools.permutations(arr)
来源：http://dali.andypj.xyz/Article/details/gtmyktondq.html

PHP:  // 手写递归交换
来源：http://dali.jianghu66.top/Article/details/gtoodcdndt.html

JS:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gtcbnkumuf.html

TS:   // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gtigtgvuzk.html

Java: // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gtmlbaaiyy.html

Go:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjtccfgpn.html

Ruby: arr.permutation.to_a
来源：http://dali.birdmap.top/Article/details/gtuxyfmsaj.html

C#:   // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gtbkvqxvfq.html

[N09] 栈与队列
来源：http://dali.ydzc1.top/Article/details/gthcymigjh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.nwbrower.top/Article/details/gtnqyfyexv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jqgufenzy.top/Article/details/gtoimkhjts.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.vqdsnc.cn/Article/details/gtnpwwcaga.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xinyue.icu/Article/details/gtfdsieipw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.haohaochexian.top/Article/details/gtwpazmadu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yueranfly.top/Article/details/gtljzaxvgu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gtuhrwukpm.html


<!-- 参考信息 -->