代发 wailian999

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.daxiang520.top/Article/details/gtcbonxjag.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gtinvkttka.html

JS:   JSON.stringify(obj)
来源：http://dali.yueranfly.top/Article/details/gteauwmzlm.html

TS:   JSON.stringify(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtnlqzeyir.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jiagoushi.top/Article/details/gtyyuiqohn.html

Go:   json.Marshal(obj)
来源：http://dali.9152youxi.cn/Article/details/gtsakpdeps.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinghuilouyu.cn/Article/details/gtptczelzy.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zdqjudy.top/Article/details/gtcfqztnlr.html

[K02] JSON 字符串转对象
来源：http://dali.c1oappe.top/Article/details/gtafpsfeai.html

Py:   json.loads(s)
来源：http://dali.cashguo.top/Article/details/gtcrmhurri.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jqgfzy.top/Article/details/gtrvasayux.html

JS:   JSON.parse(s)
来源：http://dali.0kj1m.cn/Article/details/gtdbmskvfr.html

TS:   JSON.parse(s)
来源：http://dali.jinqigfzy.top/Article/details/gtwstrdeua.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.aibaodan.cn/Article/details/gtgrwhwcno.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.tianlin.xyz/Article/details/gtyvbucerf.html

Ruby: JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gtuadprnvj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nanxinkj.top/Article/details/gtfjkirthv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.nanxinkj.top/Article/details/gtahnwqpie.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shangyingyoupin.top/Article/details/gtagbbicts.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258888.top/Article/details/gtvozwmnby.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.fzhhl.top/Article/details/gtslaypkbr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yueranfly.top/Article/details/gtjzmaodlf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ehwqpu.com/Article/details/gtdblbgdfg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yuanzhike.top/Article/details/gtaopqpycu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xylfe.cn/Article/details/gtpgaltzam.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jianghu66.top/Article/details/gtfdssidzt.html

[K04] 读取 JSON 文件
来源：http://dali.316326.xyz/Article/details/gtlznqnjoi.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sweek.top/Article/details/gtaiarwbrx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrwrxriey.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cashguo.top/Article/details/gtozcjbpxd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shangyingyoupin.top/Article/details/gtqxeatbps.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cdnleiting.top/Article/details/gtqytmpcwx.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.0kj1m.cn/Article/details/gtjqcfmgfl.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xinyue.icu/Article/details/gthpogyseu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.fengsongda.top/Article/details/gtpjrwcfwl.html

[K05] 深拷贝对象
来源：http://dali.shzxlz.cn/Article/details/gtveuhzeta.html

Py:   copy.deepcopy(obj)
来源：http://dali.xuanzx.com/Article/details/gtvzlhkusc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.wangdashe.top/Article/details/gtujkakuya.html

JS:   structuredClone(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnobjcnlt.html

TS:   structuredClone(obj)
来源：http://dali.kuanghao11.cn/Article/details/gteqmkjlpb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.gogol.net.cn/Article/details/gtzfttptru.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jyoumei.cn/Article/details/gtuikxhmtb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.vqdsnc.cn/Article/details/gtmubfwqne.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sweek.top/Article/details/gtbvtxbyoa.html

[K06] 解析 URL 查询串
来源：http://dali.ivvv.top/Article/details/gtzopxsawc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgfzy.top/Article/details/gtchzbfrbn.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xylfe.cn/Article/details/gtqkirykkp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258.top/Article/details/gtqvgeyanh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sweek.top/Article/details/gttzmszjir.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.dianchejie.cn/Article/details/gtedsllpwg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.haohaochexian.top/Article/details/gtzovbvfay.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sysykeji.top/Article/details/gtmsjtalac.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gtuhtxcjob.html

[K07] 进制转换
来源：http://dali.yongpay.top/Article/details/gtvpjtkush.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtmqpdcjmu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.guowangkeji.top/Article/details/gtiiaoatzp.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.pycfn.com/Article/details/gtjeuxtjyd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gtxglyiiwi.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvbtgwrpr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.pengpengdd.cyou/Article/details/gtizavffab.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.iojbl.cn/Article/details/gtqjixdixe.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtuwobbqdb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hongshengwenyu.top/Article/details/gtzkgtyfpl.html

Py:   pickle.dumps(obj)
来源：http://dali.guannengcc.top/Article/details/gtoxagdazp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jlsjyb.cn/Article/details/gtphgamvxv.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hammf.cn/Article/details/gttbgwvsle.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.316326.xyz/Article/details/gtnmkjcjpo.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.aibaodan.cn/Article/details/gtvbhfispq.html

Go:   encoding/gob
来源：http://dali.tianlin.xyz/Article/details/gtfncrtoyi.html

Ruby: Marshal.dump(obj)
来源：http://dali.hysaishi.cn/Article/details/gtdgntkrff.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xinyue.icu/Article/details/gtkzdaujuv.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtltnvutaz.html

L. 网络请求
来源：http://dali.snrcjt.cn/Article/details/gtohvtittw.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtsvqnivdu.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gtobiwhmao.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.fzhhl.top/Article/details/gtqlgktykw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nanxinkj.top/Article/details/gtgmhuxrvb.html

JS:   await fetch(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrkyeblkr.html

TS:   await fetch(url)
来源：http://dali.chenjidiqi.icu/Article/details/gtdjipgzum.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shzxlz.cn/Article/details/gtgqpvapji.html

Go:   resp, err := http.Get(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpefoqwss.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.aibaodan.cn/Article/details/gthrblcaep.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cdnleiting.top/Article/details/gtxhblpmoz.html

[L02] 发送 POST JSON
来源：http://dali.ppjwa.cn/Article/details/gtvvwhwkdb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.haohaochexian.top/Article/details/gtwhghbrmj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xuetiantiany.cn/Article/details/gtvgbnfhdb.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tianlin.xyz/Article/details/gtwaipkcoc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.316326.xyz/Article/details/gtfilhaicv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenzaomai.com/Article/details/gtxdarqinn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.wangdashe.top/Article/details/gtdeicnrup.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.mhx1999.top/Article/details/gtslajgubj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shuidangran.top/Article/details/gtzcrxvccb.html

[L03] 设置自定义请求头
来源：http://dali.cheryme.top/Article/details/gtkpurofyp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtijwcodcr.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.bjfxy.top/Article/details/gtmqgekipm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fengsongda.top/Article/details/gtlzttakuz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.havefunace.top/Article/details/gtbymrgshg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zycfv.cn/Article/details/gtkqdcmtug.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gzhubu.top/Article/details/gtksfmzjka.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sweek.top/Article/details/gtfxllnmct.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sweek.top/Article/details/gtzbkmriyn.html

[L04] 设置超时
来源：http://dali.sxryk.cn/Article/details/gtkjcabwhz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.iojbl.cn/Article/details/gtgcgdrdad.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xuetiantiany.cn/Article/details/gtveqbqdib.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhoulong.xyz/Article/details/gtpnkwjtfz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.snrcjt.cn/Article/details/gtdquurvih.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gzhubu.top/Article/details/gtjisqjoia.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.haohaochexian.top/Article/details/gtkqzvieqw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.chenzaomai.com/Article/details/gtytsyhdbz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shangyingyoupin.top/Article/details/gtvrhmemyh.html

[L05] 上传文件（multipart）
来源：http://dali.chenzaomai.com/Article/details/gtupiugzqz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhoulong.xyz/Article/details/gtbyuchgfs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yuxming.cn/Article/details/gtowtzsnxz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.guannengcc.top/Article/details/gtjakelwgw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.kuanghao11.cn/Article/details/gtnlkqcdql.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhoulong.xyz/Article/details/gthrmmgxrk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gzhubu.top/Article/details/gtdhznviwq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hnqzz.top/Article/details/gtvxuduvlr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtbwgvvxxr.html

[L06] 解析响应为 JSON
来源：http://dali.yuxming.cn/Article/details/gtfxttqvmv.html

Py:   resp.json()
来源：http://dali.ybcxt.top/Article/details/gtsxzyjgmq.html

PHP:  json_decode($body, true);
来源：http://dali.c1oappe.top/Article/details/gtycclqlcq.html

JS:   await resp.json()
来源：http://dali.cucudq.cn/Article/details/gtnrtqgryk.html

TS:   await resp.json()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgakaamgo.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.0kj1m.cn/Article/details/gtspfytpww.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shuidangran.top/Article/details/gtgtowfdjz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.redwolf501.top/Article/details/gtosvrahxu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gogol.net.cn/Article/details/gtotpwehxb.html

[L07] 处理 HTTP 状态码
来源：http://dali.gaohongyu789.top/Article/details/gtigtcwgwi.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.fengsongda.top/Article/details/gtvpqbyhwp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cucudq.cn/Article/details/gtdmychnqp.html

JS:   resp.ok;  resp.status
来源：http://dali.xziqi.cn/Article/details/gtmekcmtfo.html

TS:   resp.ok;  resp.status
来源：http://dali.shangyingyoupin.top/Article/details/gtayfriqxg.html

Java: resp.statusCode()
来源：http://dali.svipenyu.cn/Article/details/gtwrgtakex.html

Go:   resp.StatusCode
来源：http://dali.zhengqikj.top/Article/details/gtwyrihdeo.html

Ruby: resp.code.to_i
来源：http://dali.daxiang520.top/Article/details/gtzpwgnrsl.html

C#:   (int)resp.StatusCode
来源：http://dali.ybcxt.top/Article/details/gtmhovqmdd.html

[L08] 并发请求多个地址
来源：http://dali.feifeiyinyue.top/Article/details/gtlpjezpzr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.quarkkingdee.top/Article/details/gtetqadzqy.html

PHP:  curl_multi_init() 系列
来源：http://dali.hnxiangtu.top/Article/details/gtmolesrzk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangshuangyany.cn/Article/details/gtncyabqyz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhixingplan.top/Article/details/gtjpcexrdk.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jqgfzy.top/Article/details/gtgmlthwtw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinqigfzy.top/Article/details/gtzakbcodc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.c1oappe.top/Article/details/gtdmbznwcn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.quarkkingdee.top/Article/details/gtujkqehhg.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtfwpsdncf.html

M. 命令行 / 进程 / 环境
来源：http://dali.birdmap.top/Article/details/gthocddggt.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtecapewmc.html

[M01] 读取命令行参数
来源：http://dali.zhiwuduotai.top/Article/details/gtnicmzonf.html

Py:   sys.argv[1:]
来源：http://dali.yuxming.cn/Article/details/gtoxdwxajp.html

PHP:  $argv;  $argc;
来源：http://dali.cashguo.top/Article/details/gtppctwrap.html

JS:   process.argv.slice(2)
来源：http://dali.hnxiangtu.top/Article/details/gtulztvlcr.html

TS:   process.argv.slice(2)
来源：http://dali.aibaodan.cn/Article/details/gtpzekjxsc.html

Java: args 数组（main 方法参数）
来源：http://dali.tanke756.top/Article/details/gtlnmdkylg.html

Go:   os.Args[1:]
来源：http://dali.kuanghao11.cn/Article/details/gtgfvxzcmu.html

Ruby: ARGV
来源：http://dali.xylfe.cn/Article/details/gtyndpfeis.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ybcxt.top/Article/details/gtmwrozoan.html

[M02] 读取环境变量
来源：http://dali.zycfv.cn/Article/details/gtehkcatvf.html

Py:   os.environ.get("HOME")
来源：http://dali.hysaishi.cn/Article/details/gtdertekkv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hammf.cn/Article/details/gtvlneuvox.html

JS:   process.env.HOME
来源：http://dali.xuetiantiany.cn/Article/details/gtoqezfwcg.html

TS:   process.env.HOME
来源：http://dali.jyoumei.cn/Article/details/gtqvovcxja.html

Java: System.getenv("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gtjnrlvxph.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yuxming.cn/Article/details/gtpdzddwtc.html

Ruby: ENV["HOME"]
来源：http://dali.wangshuangyany.cn/Article/details/gteipjojcd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gtwxfhihmr.html

[M03] 执行外部命令
来源：http://dali.c1oappe.top/Article/details/gtztyxmtzu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xuetiantiany.cn/Article/details/gtwyqcttcf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nwbrower.top/Article/details/gtdcvyalpj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ppjwa.cn/Article/details/gtcifcrapq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhiwuduotai.top/Article/details/gtjyqjmlsh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.wangshuangyany.cn/Article/details/gtwheqhxje.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nanxinkj.top/Article/details/gtkfmmtcxy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jianghu66.top/Article/details/gtuwuebmgk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.dashuyun.cn/Article/details/gtasbyatzx.html

[M04] 获取当前工作目录
来源：http://dali.tian-w.cn/Article/details/gtycbnbjyo.html

Py:   os.getcwd()
来源：http://dali.jiagoushi.top/Article/details/gtdzintquz.html

PHP:  getcwd();
来源：http://dali.aizwys.cn/Article/details/gtpfwaqbru.html

JS:   process.cwd()
来源：http://dali.c1oappe.top/Article/details/gtywdoaiak.html

TS:   process.cwd()
来源：http://dali.xinyue.icu/Article/details/gtpacvwwlx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.vqdsnc.cn/Article/details/gthscehdiz.html

Go:   os.Getwd()
来源：http://dali.c1oappe.top/Article/details/gtefyqjwgh.html

Ruby: Dir.pwd
来源：http://dali.jqgfzy.top/Article/details/gttrecjewp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.mhx1999.top/Article/details/gtbbmwiunr.html

[M05] 设置退出码
来源：http://dali.dashuyun.cn/Article/details/gtfuoxnpzn.html

Py:   sys.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmtngpzqg.html

PHP:  exit(1);
来源：http://dali.tianlin.xyz/Article/details/gtitewihfi.html

JS:   process.exit(1)
来源：http://dali.sysykeji.top/Article/details/gthwhslghg.html

TS:   process.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtifpuhniu.html

Java: System.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthqusspkz.html

Go:   os.Exit(1)
来源：http://dali.meibo888.top/Article/details/gtjnqjmpoy.html

Ruby: exit 1
来源：http://dali.havefunace.top/Article/details/gtwwgraqvt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.daria6918.cn/Article/details/gtxusnxadx.html

[M06] 向标准错误输出
来源：http://dali.zdqjudy.top/Article/details/gtvgpbehlp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jyoumei.cn/Article/details/gtqzumxygz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttexmjhew.html

JS:   console.error("err")
来源：http://dali.gaohongyu789.top/Article/details/gtnvquydoo.html

TS:   console.error("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtolnbitnq.html

Java: System.err.println("err")
来源：http://dali.hongshengwenyu.top/Article/details/gtpynydkdg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.9152youxi.cn/Article/details/gtgqkgydku.html

Ruby: warn "err"
来源：http://dali.xuetiantiany.cn/Article/details/gtkbbzddnt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tian-w.cn/Article/details/gtyeauoeye.html

[M07] 判断是否为主入口
来源：http://dali.jinqigfzy.top/Article/details/gtaowmsssr.html

Py:   if __name__ == "__main__":
来源：http://dali.cucudq.cn/Article/details/gtdfjxortv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sysykeji.top/Article/details/gtfscdvidf.html

JS:   require.main === module
来源：http://dali.birdmap.top/Article/details/gthacsfwhx.html

TS:   require.main === module
来源：http://dali.zhoulong.xyz/Article/details/gtkttalbex.html

Java: public static void main(String[] args)
来源：http://dali.yuanzhike.top/Article/details/gtapvfhwqu.html

Go:   func main()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwjjbedzi.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yuanzhike.top/Article/details/gteumayknv.html

C#:   static void Main(string[] args)
来源：http://dali.yj202588.top/Article/details/gtutuszdvh.html

[M08] 获取系统与运行时信息
来源：http://dali.hongshengwenyu.top/Article/details/gtaihtpvtm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zycfv.cn/Article/details/gtkueqriww.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hammf.cn/Article/details/gtjfapglyu.html

JS:   process.platform;  process.version
来源：http://dali.cqqwz.cn/Article/details/gtuocogcpv.html

TS:   process.platform;  process.version
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvasyhhvw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.vqdsnc.cn/Article/details/gttksgxcef.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.chenjidiqi.icu/Article/details/gtacztkbwm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xinyue.icu/Article/details/gteknqjmjp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhoulong.xyz/Article/details/gtzxeaazwm.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gttpefehlq.html

N. 数据结构与算法
来源：http://dali.gogol.net.cn/Article/details/gtmywegnpd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gterbmjhyv.html

[N01] 二分查找（有序数组）
来源：http://dali.gaohongyu789.top/Article/details/gtgllxvugt.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtxhzxbgow.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gtbrtnfveb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daria6918.cn/Article/details/gtewmenvry.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxuanxn.top/Article/details/gttbhcxdsm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtkjunmzof.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtkivoapcq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhiwuduotai.top/Article/details/gtwkwenxwz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yonumen.top/Article/details/gtsiwdwfzd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hfpthk.cn/Article/details/gtxbiubcfa.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pycfn.com/Article/details/gtzjixtuux.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.daxiang520.top/Article/details/gtvlrcdojd.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jiagoushi.top/Article/details/gtvozvrmgc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jyoumei.cn/Article/details/gtjjmripgn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cheryme.top/Article/details/gtokjxciez.html

Go:   slices.Sort(arr)
来源：http://dali.haohaochexian.top/Article/details/gtcllftltx.html

Ruby: arr.sort
来源：http://dali.xziqi.cn/Article/details/gtmowctsem.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.0kj1m.cn/Article/details/gtohjbszeq.html

[N03] 快速排序（分治示例）
来源：http://dali.shzxlz.cn/Article/details/gtdvcanhij.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdwhmypzc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.guannengcc.top/Article/details/gtwlmkfxim.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgfzy.top/Article/details/gtqdazldph.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jlsjyb.cn/Article/details/gtjoftyshy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdqdiozgz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.daria6918.cn/Article/details/gtfvugmixs.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.pycfn.com/Article/details/gtvsbtuexo.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhoulong.xyz/Article/details/gtanoeoczh.html

[N04] 斐波那契数列
来源：http://dali.sufxvd.cn/Article/details/gtyhorwbbx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xylfe.cn/Article/details/gtkdsikthf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhongyouzk.top/Article/details/gtqaspletg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sxryk.cn/Article/details/gtyhdrpljc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gtqshjstrd.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gtpyoqyrvd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.fengsongda.top/Article/details/gtsyvjvyke.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xziqi.cn/Article/details/gtgozwehxo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jyoumei.cn/Article/details/gtnycjytvk.html

[N05] 最大公约数
来源：http://dali.ehwqpu.com/Article/details/gtnmtsrxcf.html

Py:   math.gcd(a, b)
来源：http://dali.daxiang520.top/Article/details/gtqqqmmrqy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.chenjidiqi.icu/Article/details/gttmdzoxjl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hongshengwenyu.top/Article/details/gtwjjmrvhv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cheryme.top/Article/details/gttvdeiayv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.guowangkeji.top/Article/details/gtsuuqemsd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hnqzz.top/Article/details/gttnkiqoxk.html

Ruby: a.gcd(b)
来源：http://dali.sufxvd.cn/Article/details/gtyiapfrrp.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gzhubu.top/Article/details/gthwbrwhri.html

[N06] 判断回文字符串
来源：http://dali.xylfe.cn/Article/details/gtoafkpwhr.html

Py:   s == s[::-1]
来源：http://dali.zhengqikj.top/Article/details/gtoyfqujpa.html

PHP:  $s === strrev($s);
来源：http://dali.cheryme.top/Article/details/gtxtilqvdd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gteoracgzb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gtthzypjfz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cdnleiting.top/Article/details/gtaxtiuptl.html

Go:   // 双指针从两端比较
来源：http://dali.smart0.xyz/Article/details/gtvikbjetq.html

Ruby: s == s.reverse
来源：http://dali.haohaochexian.top/Article/details/gtfilxilgl.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yangfankeji.com/Article/details/gttejrjndq.html

[N07] 两数之和（返回下标）
来源：http://dali.cdnleiting.top/Article/details/gtoczxlbqm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.havefunace.top/Article/details/gtomihgtof.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xinyue.icu/Article/details/gtlxffyccd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zycfv.cn/Article/details/gtzxnxjzsz.html

TS:   // 手写 Map<string, number>
来源：http://dali.mhx1999.top/Article/details/gtbpfrzhor.html

Java: // 手写 HashMap
来源：http://dali.zhoulong.xyz/Article/details/gtpipcovoi.html

Go:   // 手写 map[int]int
来源：http://dali.xuanzx.com/Article/details/gtxcaqpbod.html

Ruby: // 手写 Hash
来源：http://dali.jiagoushi.top/Article/details/gtkpduaonr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xuetiantiany.cn/Article/details/gtshxhpxlr.html

[N08] 生成全排列
来源：http://dali.dashuyun.cn/Article/details/gtbxynffcj.html

Py:   itertools.permutations(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtryoxvkwu.html

PHP:  // 手写递归交换
来源：http://dali.yangfankeji.com/Article/details/gtozrgbvfq.html

JS:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gtznmjxgaz.html

TS:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gtfbffbcdn.html

Java: // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gtkkndfnbz.html

Go:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtdbvwedrg.html

Ruby: arr.permutation.to_a
来源：http://dali.nanxinkj.top/Article/details/gtykplbvmc.html

C#:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gtvrqtmkre.html

[N09] 栈与队列
来源：http://dali.andypj.xyz/Article/details/gtaslexlpo.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yanxiufei.cn/Article/details/gtuaiibjet.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gzhubu.top/Article/details/gtrzjyftnm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sweek.top/Article/details/gtxkwhqoxd.html


<!-- 参考信息 -->