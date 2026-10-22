代发 wailian999

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.9152youxi.cn/Article/details/gt2rbxamgtp.html

Go:   json.Marshal(obj)
来源：http://dali.xinyue.icu/Article/details/gt2tjvpfgtd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.vqdsnc.cn/Article/details/gt2zmyduoyv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xinyue.icu/Article/details/gt2gwuywxzs.html

[K02] JSON 字符串转对象
来源：http://dali.yj202588.top/Article/details/gt2npnlnmua.html

Py:   json.loads(s)
来源：http://dali.fzhhl.top/Article/details/gt2ujzslkya.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yvedp.cn/Article/details/gt2tgdyqbnz.html

JS:   JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dysqdxrs.html

TS:   JSON.parse(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tdqaiewq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhongyouzk.top/Article/details/gt2tdjahkgt.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gzhubu.top/Article/details/gt2iddlqkwz.html

Ruby: JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gt2sxhtsoum.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.haohaochexian.top/Article/details/gt2qgyhdxwa.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.aibaodan.cn/Article/details/gt2jxlpmyfw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jqgfzy.top/Article/details/gt2rbmwfymk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.wangshuangyany.cn/Article/details/gt2lzlgtslo.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sufxvd.cn/Article/details/gt2wmcaxald.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gt2vgknhfbs.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2eprmbugd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.andypj.xyz/Article/details/gt2mcpksuyx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2ynpxjdig.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xuanzx.com/Article/details/gt2gypdqpds.html

[K04] 读取 JSON 文件
来源：http://dali.guowangkeji.top/Article/details/gt2cexcocvm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yuanzhike.top/Article/details/gt2pkfjeliw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gaohongyu789.top/Article/details/gt2wgbbtwsk.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xinyue.icu/Article/details/gt2buyeugbl.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.dianchejie.cn/Article/details/gt2nfzlteem.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinqigufen.top/Article/details/gt2fbyjhiuv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ivvv.top/Article/details/gt2bufhgymk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.fzhhl.top/Article/details/gt2awtwctfs.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2ejrhuddd.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrrvoto.html

Py:   copy.deepcopy(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2equkzthn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.dashuyun.cn/Article/details/gt2etvwzpil.html

JS:   structuredClone(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2ojxancql.html

TS:   structuredClone(obj)
来源：http://dali.daria6918.cn/Article/details/gt2enppnioo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ehwqpu.com/Article/details/gt2lvrccgtm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinqigufen.top/Article/details/gt2ijvofnud.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.wangshuangyany.cn/Article/details/gt2mjyczgqo.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.svipenyu.cn/Article/details/gt2kdmkaela.html

[K06] 解析 URL 查询串
来源：http://dali.zhixingplan.top/Article/details/gt2qwppmqth.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yj20258888.top/Article/details/gt2jgkovxdy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj20258.top/Article/details/gt2yheiezsv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daria6918.cn/Article/details/gt2gizuvjxb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj202588.top/Article/details/gt2jezggumi.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sufxvd.cn/Article/details/gt2zsptjkan.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shuidangran.top/Article/details/gt2ltybzjub.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sweek.top/Article/details/gt2xjvbinxa.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.quarkkingdee.top/Article/details/gt2mfhjqzhq.html

[K07] 进制转换
来源：http://dali.jqgufenzy.top/Article/details/gt2uionxocl.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gt2xxttythp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.wangshuangyany.cn/Article/details/gt2yusvdpng.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gt2gdjhnwog.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gt2omtoxqqe.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gt2ssifnmci.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zdqjudy.top/Article/details/gt2rjcjwjec.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.haohaochexian.top/Article/details/gt2lumjygrf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gt2oruutuwn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.wangdashe.top/Article/details/gt2aqyzqloi.html

Py:   pickle.dumps(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2ubxzumlz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jianghu66.top/Article/details/gt2pmgujdtc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jiagoushi.top/Article/details/gt2ypaxfywu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hnxiangtu.top/Article/details/gt2yrsidjfj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xuanzx.com/Article/details/gt2ivvridsp.html

Go:   encoding/gob
来源：http://dali.jiagoushi.top/Article/details/gt2seykqdzr.html

Ruby: Marshal.dump(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hjuuxsos.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.haohaochexian.top/Article/details/gt2jufcgahn.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2fcrpcqda.html

L. 网络请求
来源：http://dali.cucudq.cn/Article/details/gt2jlszuypa.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2wqfgraya.html

[L01] 发送 GET 请求
来源：http://dali.iojbl.cn/Article/details/gt2lzoawwiw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xylfe.cn/Article/details/gt2qinfawdu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.meibo888.top/Article/details/gt2drrpogyq.html

JS:   await fetch(url)
来源：http://dali.havefunace.top/Article/details/gt2zsbtfpsx.html

TS:   await fetch(url)
来源：http://dali.kuanghao11.cn/Article/details/gt2nxrsqwtl.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.feifeiyinyue.top/Article/details/gt2balnmopk.html

Go:   resp, err := http.Get(url)
来源：http://dali.cheryme.top/Article/details/gt2kyiymvtl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.aizwys.cn/Article/details/gt2knvojtfe.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.tanke756.top/Article/details/gt2rfohqgpb.html

[L02] 发送 POST JSON
来源：http://dali.jqgfzy.top/Article/details/gt2kubtjlsz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.redwolf501.top/Article/details/gt2ssxqaazp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.dashuyun.cn/Article/details/gt2ivikaxdk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2jdagdqfp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cucudq.cn/Article/details/gt2fpxqamdi.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.aizwys.cn/Article/details/gt2oojvifvh.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.vqdsnc.cn/Article/details/gt2pkcwxdli.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sufxvd.cn/Article/details/gt2oiwoktrz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.nwbrower.top/Article/details/gt2meobsxqh.html

[L03] 设置自定义请求头
来源：http://dali.mhx1999.top/Article/details/gt2peffugfm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hfpthk.cn/Article/details/gt2hgkjkdpe.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xziqi.cn/Article/details/gt2eyytqxpu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sufxvd.cn/Article/details/gt2elvtfsvu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fzhhl.top/Article/details/gt2kgbnumdw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hammf.cn/Article/details/gt2syuxcoqa.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.havefunace.top/Article/details/gt2pjmlsyaq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ppjwa.cn/Article/details/gt2hunuwedo.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cheryme.top/Article/details/gt2tghybuio.html

[L04] 设置超时
来源：http://dali.gotoacloud.top/Article/details/gt2wihwrdug.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ppjwa.cn/Article/details/gt2igrulxlg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hongshengwenyu.top/Article/details/gt2fxvcnvlf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.redwolf501.top/Article/details/gt2nffiwxgy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.mhx1999.top/Article/details/gt2bubgckgx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gaohongyu789.top/Article/details/gt2poccjvvw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gogol.net.cn/Article/details/gt2pmdwkxxk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cashguo.top/Article/details/gt2lgnyncbg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.9152youxi.cn/Article/details/gt2pgnzphjd.html

[L05] 上传文件（multipart）
来源：http://dali.zhongyouzk.top/Article/details/gt2uowtxcta.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gotoacloud.top/Article/details/gt2afrfgner.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ydzc1.top/Article/details/gt2nejbjoct.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cashguo.top/Article/details/gt2xflmbmfb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuxming.cn/Article/details/gt2vooxpour.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hysaishi.cn/Article/details/gt2xxvsvwib.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wxonaxsg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gotoacloud.top/Article/details/gt2qbuiqyre.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2ywivpxgq.html

[L06] 解析响应为 JSON
来源：http://dali.kuanghao11.cn/Article/details/gt2jgcakniy.html

Py:   resp.json()
来源：http://dali.sxryk.cn/Article/details/gt2agqszfsk.html

PHP:  json_decode($body, true);
来源：http://dali.jinqigfzy.top/Article/details/gt2srfwogvu.html

JS:   await resp.json()
来源：http://dali.jiagoushi.top/Article/details/gt2qjzmsvly.html

TS:   await resp.json()
来源：http://dali.hysaishi.cn/Article/details/gt2phfjdzjw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.0kj1m.cn/Article/details/gt2yjesishv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.svipenyu.cn/Article/details/gt2gnqdribp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xervwbpd.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hywenlv.cn/Article/details/gt2yubnltiw.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhoulong.xyz/Article/details/gt2uertlyjn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xuetiantiany.cn/Article/details/gt2henihrvu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shzxlz.cn/Article/details/gt2vjutipnk.html

JS:   resp.ok;  resp.status
来源：http://dali.yueranfly.top/Article/details/gt2nzcqmpgh.html

TS:   resp.ok;  resp.status
来源：http://dali.daxiang520.top/Article/details/gt2psqdhziy.html

Java: resp.statusCode()
来源：http://dali.smart0.xyz/Article/details/gt2paknmygk.html

Go:   resp.StatusCode
来源：http://dali.jinqigfzy.top/Article/details/gt2naanqely.html

Ruby: resp.code.to_i
来源：http://dali.smart0.xyz/Article/details/gt2ootagtie.html

C#:   (int)resp.StatusCode
来源：http://dali.yj20258888.top/Article/details/gt2icjjkrlv.html

[L08] 并发请求多个地址
来源：http://dali.jiagoushi.top/Article/details/gt2jbmmjnab.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.pengpengdd.cyou/Article/details/gt2mhuwlsze.html

PHP:  curl_multi_init() 系列
来源：http://dali.quarkkingdee.top/Article/details/gt2sxkqyrxp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jyoumei.cn/Article/details/gt2wxcargkt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cucudq.cn/Article/details/gt2sgclpqfx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cqqwz.cn/Article/details/gt2xontkiiv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xziqi.cn/Article/details/gt2ozjkmwgm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cashguo.top/Article/details/gt2uvytouag.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.dianchejie.cn/Article/details/gt2ebdvlanf.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2kccfdklu.html

M. 命令行 / 进程 / 环境
来源：http://dali.nwbrower.top/Article/details/gt2conjzsec.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2ihjhipoq.html

[M01] 读取命令行参数
来源：http://dali.yj202588.top/Article/details/gt2mpqyugjq.html

Py:   sys.argv[1:]
来源：http://dali.cucudq.cn/Article/details/gt2wsrwpnis.html

PHP:  $argv;  $argc;
来源：http://dali.shzxlz.cn/Article/details/gt2wzvwjpph.html

JS:   process.argv.slice(2)
来源：http://dali.yueranfly.top/Article/details/gt2kdsbaold.html

TS:   process.argv.slice(2)
来源：http://dali.haohaochexian.top/Article/details/gt2xxqjpcqj.html

Java: args 数组（main 方法参数）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gkhglyfa.html

Go:   os.Args[1:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2loplouhh.html

Ruby: ARGV
来源：http://dali.chenzaomai.com/Article/details/gt2tqcoslph.html

C#:   args 数组（Main 方法参数）
来源：http://dali.tian-w.cn/Article/details/gt2krtmbxnp.html

[M02] 读取环境变量
来源：http://dali.hongshengwenyu.top/Article/details/gt2czweavco.html

Py:   os.environ.get("HOME")
来源：http://dali.chenlongwang.top/Article/details/gt2lvgiyesj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhixingplan.top/Article/details/gt2zequkyka.html

JS:   process.env.HOME
来源：http://dali.hfpthk.cn/Article/details/gt2xshocjmq.html

TS:   process.env.HOME
来源：http://dali.fzhhl.top/Article/details/gt2llsfkqje.html

Java: System.getenv("HOME")
来源：http://dali.gzhubu.top/Article/details/gt2navjtnhd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cdnleiting.top/Article/details/gt2fbwfwwvj.html

Ruby: ENV["HOME"]
来源：http://dali.yj202588.top/Article/details/gt2zkycrhrt.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yvedp.cn/Article/details/gt2fdsihcmk.html

[M03] 执行外部命令
来源：http://dali.hongshengwenyu.top/Article/details/gt2eoxntwdw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.dashuyun.cn/Article/details/gt2csnxscdo.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.andypj.xyz/Article/details/gt2tgmbvvcu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.quarkkingdee.top/Article/details/gt2zlaplskt.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hywenlv.cn/Article/details/gt2hrednefn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zdqjudy.top/Article/details/gt2zrjhfiwr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhoulong.xyz/Article/details/gt2exsdutmn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shangyingyoupin.top/Article/details/gt2dsxxcbhi.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hnzcprsr.html

[M04] 获取当前工作目录
来源：http://dali.cashguo.top/Article/details/gt2gcuygsmg.html

Py:   os.getcwd()
来源：http://dali.jinqigufen.top/Article/details/gt2gzkchjyp.html

PHP:  getcwd();
来源：http://dali.yvedp.cn/Article/details/gt2grkaddbc.html

JS:   process.cwd()
来源：http://dali.316326.xyz/Article/details/gt2wvqowxym.html

TS:   process.cwd()
来源：http://dali.nwbrower.top/Article/details/gt2xbeyunxs.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hongshengwenyu.top/Article/details/gt2lvggdgai.html

Go:   os.Getwd()
来源：http://dali.cheryme.top/Article/details/gt2dqcfmewx.html

Ruby: Dir.pwd
来源：http://dali.quarkkingdee.top/Article/details/gt2ivxcphex.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sufxvd.cn/Article/details/gt2tyksozrf.html

[M05] 设置退出码
来源：http://dali.316326.xyz/Article/details/gt2dfptsdjx.html

Py:   sys.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2kwenickf.html

PHP:  exit(1);
来源：http://dali.yj20258.top/Article/details/gt2clnkzlwa.html

JS:   process.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gt2uxefmsbk.html

TS:   process.exit(1)
来源：http://dali.c1oappe.top/Article/details/gt2izwnmcxx.html

Java: System.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2owrxfzmd.html

Go:   os.Exit(1)
来源：http://dali.yuanzhike.top/Article/details/gt2weyoowbm.html

Ruby: exit 1
来源：http://dali.smart0.xyz/Article/details/gt2xldhrzyh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.havefunace.top/Article/details/gt2vjrqwrgx.html

[M06] 向标准错误输出
来源：http://dali.gotoacloud.top/Article/details/gt2ngflbytp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xuanzx.com/Article/details/gt2rlkfpube.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhengqikj.top/Article/details/gt2eoaqvkmo.html

JS:   console.error("err")
来源：http://dali.tian-w.cn/Article/details/gt2tlhcyciu.html

TS:   console.error("err")
来源：http://dali.yuanzhike.top/Article/details/gt2dbwwknnl.html

Java: System.err.println("err")
来源：http://dali.quarkkingdee.top/Article/details/gt2peiiwmoo.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.daxiang520.top/Article/details/gt2gnysunzv.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2budtzlnk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.quarkkingdee.top/Article/details/gt2iexgcdow.html

[M07] 判断是否为主入口
来源：http://dali.chenzaomai.com/Article/details/gt2bmvwpbms.html

Py:   if __name__ == "__main__":
来源：http://dali.yongpay.top/Article/details/gt2ykfqglze.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xuetiantiany.cn/Article/details/gt2wyqxfmyr.html

JS:   require.main === module
来源：http://dali.yj202588.top/Article/details/gt2mpvmywcq.html

TS:   require.main === module
来源：http://dali.shangyingyoupin.top/Article/details/gt2odarhjgb.html

Java: public static void main(String[] args)
来源：http://dali.hnqzz.top/Article/details/gt2hszfmzyb.html

Go:   func main()
来源：http://dali.vqdsnc.cn/Article/details/gt2etxdepbt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.feifeiyinyue.top/Article/details/gt2pvbuhcdz.html

C#:   static void Main(string[] args)
来源：http://dali.yongpay.top/Article/details/gt2xffeijno.html

[M08] 获取系统与运行时信息
来源：http://dali.quarkkingdee.top/Article/details/gt2hnqalzxg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jianghu66.top/Article/details/gt2gkctcfna.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhixingplan.top/Article/details/gt2alcqxmxd.html

JS:   process.platform;  process.version
来源：http://dali.ehwqpu.com/Article/details/gt2hamqlwsg.html

TS:   process.platform;  process.version
来源：http://dali.aibaodan.cn/Article/details/gt2ckmuzfwx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.vqdsnc.cn/Article/details/gt2teypbxps.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xuanzx.com/Article/details/gt2cvqgrnam.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhongyouzk.top/Article/details/gt2sjiggcul.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hammf.cn/Article/details/gt2yckfyddt.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2lpjenyyo.html

N. 数据结构与算法
来源：http://dali.chenjidiqi.icu/Article/details/gt2oourkmjk.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2tuezklrh.html

[N01] 二分查找（有序数组）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tnzwzpry.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mesxhlec.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.iojbl.cn/Article/details/gt2zbhbstbp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pengpengdd.cyou/Article/details/gt2cohuefih.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gt2kdztstcz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gt2sqsmtfsf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2sidlgdxa.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ocvjroms.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hnqzz.top/Article/details/gt2fjwdffcz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ivvv.top/Article/details/gt2kzwugrdj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2npkiindk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xuanzx.com/Article/details/gt2afqvjsav.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zdqjudy.top/Article/details/gt2nasqsfat.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fzhhl.top/Article/details/gt2qsccvjin.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hfpthk.cn/Article/details/gt2tqhqexhi.html

Go:   slices.Sort(arr)
来源：http://dali.havefunace.top/Article/details/gt2hxnqalsd.html

Ruby: arr.sort
来源：http://dali.jinqigufen.top/Article/details/gt2scrmccpw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hfpthk.cn/Article/details/gt2pdbhacio.html

[N03] 快速排序（分治示例）
来源：http://dali.gotoacloud.top/Article/details/gt2hccuwbcm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.c1oappe.top/Article/details/gt2eqzbaxkh.html

PHP:  // 递归实现，或用 usort
来源：http://dali.daria6918.cn/Article/details/gt2rulhlthp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xziqi.cn/Article/details/gt2azzgkozc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xylfe.cn/Article/details/gt2raugchsc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj20258.top/Article/details/gt2achdfkvt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zdqjudy.top/Article/details/gt2xxsbegef.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.nwbrower.top/Article/details/gt2wipxeiar.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sysykeji.top/Article/details/gt2rsvyhcde.html

[N04] 斐波那契数列
来源：http://dali.fengsongda.top/Article/details/gt2bbgmunoz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.andypj.xyz/Article/details/gt2ynddslrz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.mhx1999.top/Article/details/gt2nsiyvdgr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gt2upxbdvbe.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.havefunace.top/Article/details/gt2xcazlpcm.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.birdmap.top/Article/details/gt2oehofbmr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yongpay.top/Article/details/gt2vmhitgwm.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gzhubu.top/Article/details/gt2ynujzlcq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jianghu66.top/Article/details/gt2ybwrzyuw.html

[N05] 最大公约数
来源：http://dali.9152youxi.cn/Article/details/gt2dbebqdas.html

Py:   math.gcd(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gt2iwmaikof.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhengqikj.top/Article/details/gt2wqedgtze.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhengqikj.top/Article/details/gt2zuthdelr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zycfv.cn/Article/details/gt2aqzbefkt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.redwolf501.top/Article/details/gt2vnaexkhh.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yuxming.cn/Article/details/gt2jmfvsduw.html

Ruby: a.gcd(b)
来源：http://dali.pycfn.com/Article/details/gt2bjamngbx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.daria6918.cn/Article/details/gt2gwlwdflf.html

[N06] 判断回文字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2fcdpbjnv.html

Py:   s == s[::-1]
来源：http://dali.xuanzx.com/Article/details/gt2cjjuakgn.html

PHP:  $s === strrev($s);
来源：http://dali.birdmap.top/Article/details/gt2xxxpcqdm.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gt2psksajuk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gt2swtbpjvv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sxryk.cn/Article/details/gt2zikcqaym.html

Go:   // 双指针从两端比较
来源：http://dali.zhoulong.xyz/Article/details/gt2avprxgxr.html

Ruby: s == s.reverse
来源：http://dali.zdqjudy.top/Article/details/gt2tgiaezqy.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sysykeji.top/Article/details/gt2aycgtpjg.html

[N07] 两数之和（返回下标）
来源：http://dali.c1oappe.top/Article/details/gt2ceinjwbb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ydzc1.top/Article/details/gt2yqmghkqm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.smart0.xyz/Article/details/gt2hvnevqtk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gaohongyu789.top/Article/details/gt2faommtkw.html

TS:   // 手写 Map<string, number>
来源：http://dali.xuetiantiany.cn/Article/details/gt2kxnpsjar.html

Java: // 手写 HashMap
来源：http://dali.sweek.top/Article/details/gt2tjkgwwfw.html

Go:   // 手写 map[int]int
来源：http://dali.wangshuangyany.cn/Article/details/gt2qskszpke.html

Ruby: // 手写 Hash
来源：http://dali.hnxiangtu.top/Article/details/gt2pmujgmbp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.daxiang520.top/Article/details/gt2ohrvhgfb.html

[N08] 生成全排列
来源：http://dali.c1oappe.top/Article/details/gt2znzcmejs.html

Py:   itertools.permutations(arr)
来源：http://dali.andypj.xyz/Article/details/gt2pciuqemz.html

PHP:  // 手写递归交换
来源：http://dali.smart0.xyz/Article/details/gt2bxnqsqja.html

JS:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gt2wbbyodni.html

TS:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gt2fomtwoar.html

Java: // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gt2hviyxdlm.html

Go:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gt2avcmvrkd.html

Ruby: arr.permutation.to_a
来源：http://dali.cheryme.top/Article/details/gt2kymeuleb.html

C#:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gt2okzzgjfg.html

[N09] 栈与队列
来源：http://dali.svipenyu.cn/Article/details/gt2dstfirri.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nugyqfpo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ivvv.top/Article/details/gt2ctezjnvt.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.bjfxy.top/Article/details/gt2wzyabvfg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ganrczuu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.svipenyu.cn/Article/details/gt2cyrkahbt.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.tanke756.top/Article/details/gt2lytjzfll.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pjvxfvik.html


<!-- 参考信息 -->