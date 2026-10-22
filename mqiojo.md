代发 wailian999

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmukhjqby.html

Go:   json.Marshal(obj)
来源：http://dali.meibo888.top/Article/details/gtmdvzledb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.tianlin.xyz/Article/details/gtqnybamim.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.daria6918.cn/Article/details/gtsnfbpffo.html

[K02] JSON 字符串转对象
来源：http://dali.sufxvd.cn/Article/details/gtalvgljbz.html

Py:   json.loads(s)
来源：http://dali.meibo888.top/Article/details/gtheopgggx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.andypj.xyz/Article/details/gtqskcjudl.html

JS:   JSON.parse(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjashoiqd.html

TS:   JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtopdbzyyp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.guannengcc.top/Article/details/gtqiyaruna.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlvzsmcmn.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gtbetgkksv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.daxiang520.top/Article/details/gtrybikddx.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shzxlz.cn/Article/details/gtmtegimin.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinqigfzy.top/Article/details/gtjtypqchz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.daxiang520.top/Article/details/gtyzuvroof.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.0kj1m.cn/Article/details/gtujygsdrc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnsewcnpm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.aibaodan.cn/Article/details/gtansrudts.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cucudq.cn/Article/details/gtoajkclpm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.pycfn.com/Article/details/gtcduifect.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinqigufen.top/Article/details/gtrhlrxgqj.html

[K04] 读取 JSON 文件
来源：http://dali.nwbrower.top/Article/details/gtohgpyyuy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.c1oappe.top/Article/details/gtwfbyzkai.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jiagoushi.top/Article/details/gthzyqbaqw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.dashuyun.cn/Article/details/gtqxbhhdzf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ydzc1.top/Article/details/gtxbishyrz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sufxvd.cn/Article/details/gtutifqdge.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.316326.xyz/Article/details/gtlzofpzxf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtftoookac.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtnjwgpmyg.html

[K05] 深拷贝对象
来源：http://dali.zhiwuduotai.top/Article/details/gtuhzxwttd.html

Py:   copy.deepcopy(obj)
来源：http://dali.9152youxi.cn/Article/details/gtwxqwpxwg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.fzhhl.top/Article/details/gttihtksnd.html

JS:   structuredClone(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtcxqbavyh.html

TS:   structuredClone(obj)
来源：http://dali.yj20258.top/Article/details/gtqwucvfdw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shanyushiyangtech.top/Article/details/gtydkjlqcp.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xziqi.cn/Article/details/gthfesdoae.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinghuilouyu.cn/Article/details/gtgvnotihp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.fzhhl.top/Article/details/gtdkmfxfce.html

[K06] 解析 URL 查询串
来源：http://dali.chenjidiqi.icu/Article/details/gtjickzvbi.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xuetiantiany.cn/Article/details/gtarychydk.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yueranfly.top/Article/details/gtcjqqxjyn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuanzx.com/Article/details/gtqiovvwpx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.haohaochexian.top/Article/details/gtwizqakpx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gotoacloud.top/Article/details/gtwbamijls.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gtbrjfddcn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.feifeiyinyue.top/Article/details/gtxbqqihxi.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gtnzwazfka.html

[K07] 进制转换
来源：http://dali.bjfxy.top/Article/details/gtnbsropxq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtradqjjvf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.smart0.xyz/Article/details/gtmsjjywze.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gttbpcgtmk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cashguo.top/Article/details/gtvmohvgmt.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtzekxiess.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hfpthk.cn/Article/details/gtyxcuwfdx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdzcjhyhd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gtnbxfqqub.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hfpthk.cn/Article/details/gtyxmpgzzk.html

Py:   pickle.dumps(obj)
来源：http://dali.snrcjt.cn/Article/details/gtbewdmgnv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.meibo888.top/Article/details/gtothxqnzs.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.fzhhl.top/Article/details/gthvblojlp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.kuanghao11.cn/Article/details/gtjwvgjznb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj20258.top/Article/details/gtsrafukdu.html

Go:   encoding/gob
来源：http://dali.yvedp.cn/Article/details/gtyhztgpwb.html

Ruby: Marshal.dump(obj)
来源：http://dali.snrcjt.cn/Article/details/gtjxdrlepy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.tianlin.xyz/Article/details/gtzwqikvhn.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtzvptrjpw.html

L. 网络请求
来源：http://dali.vqdsnc.cn/Article/details/gtkussqbzn.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gttvrlqdeq.html

[L01] 发送 GET 请求
来源：http://dali.shanyushiyangkeji.top/Article/details/gtykdccrbx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ehwqpu.com/Article/details/gtynuzllnt.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ydzc1.top/Article/details/gtsqtmlnaf.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gtoeknjlrh.html

TS:   await fetch(url)
来源：http://dali.haohaochexian.top/Article/details/gtfrkkcyxe.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.daxiang520.top/Article/details/gtvazevhds.html

Go:   resp, err := http.Get(url)
来源：http://dali.xuanzx.com/Article/details/gtgsspzmup.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.quarkkingdee.top/Article/details/gtizqdfsll.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.chenjidiqi.icu/Article/details/gtceyxyksi.html

[L02] 发送 POST JSON
来源：http://dali.birdmap.top/Article/details/gtysmbbjat.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrxwyhakh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.kuanghao11.cn/Article/details/gtmhzfkare.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ehwqpu.com/Article/details/gtkhxjxqqe.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.bjfxy.top/Article/details/gthktcpvoq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jianghu66.top/Article/details/gtrqszlwuv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yvedp.cn/Article/details/gtyeequgnb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ppjwa.cn/Article/details/gttvvyhcpi.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtozgebdqx.html

[L03] 设置自定义请求头
来源：http://dali.redwolf501.top/Article/details/gtkhtwempy.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.svipenyu.cn/Article/details/gttrwtpabi.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cdnleiting.top/Article/details/gtxgeovzsv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zdqjudy.top/Article/details/gtvlggqfxf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aibaodan.cn/Article/details/gtbbevtnks.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hammf.cn/Article/details/gtkhsdjnxv.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yj20258.top/Article/details/gttryjvjvw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhongyouzk.top/Article/details/gtchmsjisk.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hnqzz.top/Article/details/gtjacivdng.html

[L04] 设置超时
来源：http://dali.nanxuanxn.top/Article/details/gthrhmvifd.html

Py:   requests.get(url, timeout=5)
来源：http://dali.pengpengdd.cyou/Article/details/gtvoybldzu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yanxiufei.cn/Article/details/gtximjcxgt.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxuanxn.top/Article/details/gtnawnpemi.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dashuyun.cn/Article/details/gtcqxbmzfp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.mhx1999.top/Article/details/gtkuxtvovz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hfpthk.cn/Article/details/gtvbsyrkea.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xuetiantiany.cn/Article/details/gtlbvtkowe.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.daria6918.cn/Article/details/gtsckpachi.html

[L05] 上传文件（multipart）
来源：http://dali.cqqwz.cn/Article/details/gtdswiifzg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jianghu66.top/Article/details/gtwfqtxwux.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yongpay.top/Article/details/gtoqgxdqpv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shangyingyoupin.top/Article/details/gtnujkqfjw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenlongwang.top/Article/details/gtolfuxwde.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhongyouzk.top/Article/details/gtkvinkelc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.tian-w.cn/Article/details/gtmoenznyj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xuanzx.com/Article/details/gtgmlmouqf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtpqzjjvrd.html

[L06] 解析响应为 JSON
来源：http://dali.chenzaomai.com/Article/details/gtbytplvvc.html

Py:   resp.json()
来源：http://dali.chenlongwang.top/Article/details/gtrxqcqlpb.html

PHP:  json_decode($body, true);
来源：http://dali.tianlin.xyz/Article/details/gtbgorhgpw.html

JS:   await resp.json()
来源：http://dali.yj202588.top/Article/details/gtoqfbixag.html

TS:   await resp.json()
来源：http://dali.yvedp.cn/Article/details/gtxlimhqdn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmqedckpa.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.fengsongda.top/Article/details/gtomgxokmq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.chenlongwang.top/Article/details/gtvkwpgiqj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.meibo888.top/Article/details/gtwyhptadb.html

[L07] 处理 HTTP 状态码
来源：http://dali.tianlin.xyz/Article/details/gtwmrrndkl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zdqjudy.top/Article/details/gtfveovocp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.daxiang520.top/Article/details/gtmuskwyrk.html

JS:   resp.ok;  resp.status
来源：http://dali.jinghuilouyu.cn/Article/details/gtbbdmtnpy.html

TS:   resp.ok;  resp.status
来源：http://dali.fengsongda.top/Article/details/gtqgfdfytd.html

Java: resp.statusCode()
来源：http://dali.cheryme.top/Article/details/gtokeiqavc.html

Go:   resp.StatusCode
来源：http://dali.gzhubu.top/Article/details/gtyyffmctv.html

Ruby: resp.code.to_i
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwqcbmztm.html

C#:   (int)resp.StatusCode
来源：http://dali.sxryk.cn/Article/details/gtjfuzxbrg.html

[L08] 并发请求多个地址
来源：http://dali.hnqzz.top/Article/details/gtximucvff.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xuanzx.com/Article/details/gtdpamcuvc.html

PHP:  curl_multi_init() 系列
来源：http://dali.redwolf501.top/Article/details/gtdtuvoipp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258888.top/Article/details/gtgcncaozm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.haohaochexian.top/Article/details/gtrdbtaaad.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ybcxt.top/Article/details/gtpbewbpct.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhongyouzk.top/Article/details/gtdmpjaavk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hywenlv.cn/Article/details/gtxtuwpjsc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.fengsongda.top/Article/details/gthbeuxsse.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtdmcicnud.html

M. 命令行 / 进程 / 环境
来源：http://dali.jqgufenzy.top/Article/details/gtjyuewxqu.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtxuqvobzb.html

[M01] 读取命令行参数
来源：http://dali.hnqzz.top/Article/details/gtyekymkhz.html

Py:   sys.argv[1:]
来源：http://dali.c1oappe.top/Article/details/gtknqxviag.html

PHP:  $argv;  $argc;
来源：http://dali.yj20258.top/Article/details/gtiwufbzqy.html

JS:   process.argv.slice(2)
来源：http://dali.chenlongwang.top/Article/details/gtjwipjetf.html

TS:   process.argv.slice(2)
来源：http://dali.jqgufenzy.top/Article/details/gtonghlaxv.html

Java: args 数组（main 方法参数）
来源：http://dali.gotoacloud.top/Article/details/gtzzvmocit.html

Go:   os.Args[1:]
来源：http://dali.redwolf501.top/Article/details/gtfcauwthe.html

Ruby: ARGV
来源：http://dali.hammf.cn/Article/details/gtdhematyc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.mhx1999.top/Article/details/gtrdyunpon.html

[M02] 读取环境变量
来源：http://dali.guannengcc.top/Article/details/gtofphuyxm.html

Py:   os.environ.get("HOME")
来源：http://dali.ybcxt.top/Article/details/gtubiwtbvq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tian-w.cn/Article/details/gtyaoifyql.html

JS:   process.env.HOME
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkbiokmpb.html

TS:   process.env.HOME
来源：http://dali.daxiang520.top/Article/details/gtysevekxx.html

Java: System.getenv("HOME")
来源：http://dali.xylfe.cn/Article/details/gtywrguvsh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtvuhxndxl.html

Ruby: ENV["HOME"]
来源：http://dali.haohaochexian.top/Article/details/gtnidckxya.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sweek.top/Article/details/gttjvkbefs.html

[M03] 执行外部命令
来源：http://dali.zycfv.cn/Article/details/gtjrvzbckd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinqigfzy.top/Article/details/gtpubcjlab.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj20258888.top/Article/details/gtfixdioto.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jyoumei.cn/Article/details/gtwnlssjcr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.haohaochexian.top/Article/details/gtwbzqbnjj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.haohaochexian.top/Article/details/gtetqxwytv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zdqjudy.top/Article/details/gtejjpaffi.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.0kj1m.cn/Article/details/gtizuxfytb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ppjwa.cn/Article/details/gtkzfgflsh.html

[M04] 获取当前工作目录
来源：http://dali.xuanzx.com/Article/details/gtgonpfzcj.html

Py:   os.getcwd()
来源：http://dali.gaohongyu789.top/Article/details/gtgcwlgmzk.html

PHP:  getcwd();
来源：http://dali.c1oappe.top/Article/details/gtcyrjoiox.html

JS:   process.cwd()
来源：http://dali.c1oappe.top/Article/details/gtzzwdxuzf.html

TS:   process.cwd()
来源：http://dali.c1oappe.top/Article/details/gtivsjquxv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.mhx1999.top/Article/details/gtmozlxwgc.html

Go:   os.Getwd()
来源：http://dali.sxryk.cn/Article/details/gttrzdniyw.html

Ruby: Dir.pwd
来源：http://dali.yj20258888.top/Article/details/gtssxzawrp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xinyue.icu/Article/details/gtqegchxkp.html

[M05] 设置退出码
来源：http://dali.birdmap.top/Article/details/gtzwrzrckz.html

Py:   sys.exit(1)
来源：http://dali.jianghu66.top/Article/details/gtspskjvum.html

PHP:  exit(1);
来源：http://dali.316326.xyz/Article/details/gtbsjuhpyz.html

JS:   process.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtmzebvvrj.html

TS:   process.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtpaijnzrj.html

Java: System.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsdjatnxx.html

Go:   os.Exit(1)
来源：http://dali.guannengcc.top/Article/details/gtfmqcxszj.html

Ruby: exit 1
来源：http://dali.ydzc1.top/Article/details/gtotdaslxn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.aibaodan.cn/Article/details/gtjpfmkwfc.html

[M06] 向标准错误输出
来源：http://dali.meibo888.top/Article/details/gtakyvwkqn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yonumen.top/Article/details/gtulqzages.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yj202588.top/Article/details/gtfhzkelwt.html

JS:   console.error("err")
来源：http://dali.jinqigfzy.top/Article/details/gtjinrdthv.html

TS:   console.error("err")
来源：http://dali.shangyingyoupin.top/Article/details/gtzycxglzm.html

Java: System.err.println("err")
来源：http://dali.gotoacloud.top/Article/details/gtlrzrcnfu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zycfv.cn/Article/details/gtrlfbtvcf.html

Ruby: warn "err"
来源：http://dali.yonumen.top/Article/details/gthnrnfahs.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ehwqpu.com/Article/details/gtrutztwpg.html

[M07] 判断是否为主入口
来源：http://dali.yuanzhike.top/Article/details/gtgzfpxuny.html

Py:   if __name__ == "__main__":
来源：http://dali.yj20258888.top/Article/details/gtvgsmhpsv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hywenlv.cn/Article/details/gtsezhzewk.html

JS:   require.main === module
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqmvzduas.html

TS:   require.main === module
来源：http://dali.jianghu66.top/Article/details/gtzahqehvt.html

Java: public static void main(String[] args)
来源：http://dali.birdmap.top/Article/details/gtncffqsnz.html

Go:   func main()
来源：http://dali.hammf.cn/Article/details/gtlwwwjbgx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shanyushiyangtech.top/Article/details/gtludwszdq.html

C#:   static void Main(string[] args)
来源：http://dali.daxiang520.top/Article/details/gtzehsfqhw.html

[M08] 获取系统与运行时信息
来源：http://dali.ywan-chungtsiang.top/Article/details/gtimcruyhu.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yueranfly.top/Article/details/gtfofklwkm.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.birdmap.top/Article/details/gtlgytzwyx.html

JS:   process.platform;  process.version
来源：http://dali.xinyue.icu/Article/details/gtjrkecyfc.html

TS:   process.platform;  process.version
来源：http://dali.yanxiufei.cn/Article/details/gtvadmmoxc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.mhx1999.top/Article/details/gthsjfbayk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.snrcjt.cn/Article/details/gtpgqpsjjw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.snrcjt.cn/Article/details/gtkyysbwpz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gogol.net.cn/Article/details/gtggwwmaxz.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtaarxvuvl.html

N. 数据结构与算法
来源：http://dali.pycfn.com/Article/details/gtdjbckloo.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtvvbwvzqn.html

[N01] 二分查找（有序数组）
来源：http://dali.ybcxt.top/Article/details/gthnesigep.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.wangdashe.top/Article/details/gthyectwmd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yj20258888.top/Article/details/gthrmohdcu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhengqikj.top/Article/details/gtbgsojoqd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvnscbsvr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtdfcevmgs.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtymhwphwv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ehwqpu.com/Article/details/gtegumsefx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.meibo888.top/Article/details/gtrvagjctj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yueranfly.top/Article/details/gtyntxumom.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gzhubu.top/Article/details/gthvsitijp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.vqdsnc.cn/Article/details/gtomnvnuxc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.bjfxy.top/Article/details/gtbqemzpww.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pengpengdd.cyou/Article/details/gttsupkjkl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.guowangkeji.top/Article/details/gtatvxmzci.html

Go:   slices.Sort(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtukfbfwze.html

Ruby: arr.sort
来源：http://dali.yongpay.top/Article/details/gtunatotgl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.fzhhl.top/Article/details/gtdyeetccr.html

[N03] 快速排序（分治示例）
来源：http://dali.dashuyun.cn/Article/details/gtgpkulrqc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.andypj.xyz/Article/details/gtuttcrjzn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yongpay.top/Article/details/gtxtcasbpi.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ivvv.top/Article/details/gtbrbnanbw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sysykeji.top/Article/details/gtzcvtloya.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xinyue.icu/Article/details/gtwtwnhdwt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.vqdsnc.cn/Article/details/gtciyjpaiy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shuidangran.top/Article/details/gttxkgnntg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yonumen.top/Article/details/gtwpqcgesk.html

[N04] 斐波那契数列
来源：http://dali.vqdsnc.cn/Article/details/gtagxwtdsu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jlsjyb.cn/Article/details/gtcpkkxxgp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.nanxuanxn.top/Article/details/gtxwzwohlx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.birdmap.top/Article/details/gtayeroecg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj20258888.top/Article/details/gtjckiugjv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zycfv.cn/Article/details/gtmnvmcfue.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenjidiqi.icu/Article/details/gtgovsonak.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cheryme.top/Article/details/gtjnygxfhf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gtrezgmesf.html

[N05] 最大公约数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpwmslvup.html

Py:   math.gcd(a, b)
来源：http://dali.nwbrower.top/Article/details/gtpsjdqoap.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.havefunace.top/Article/details/gtuibwmqbz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtubjgbohb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yonumen.top/Article/details/gtrojrbjmh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.guannengcc.top/Article/details/gtmlsqmxco.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.iojbl.cn/Article/details/gtfkoaoiic.html

Ruby: a.gcd(b)
来源：http://dali.zhoulong.xyz/Article/details/gtxdyqtqqb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.havefunace.top/Article/details/gteaqdtpar.html

[N06] 判断回文字符串
来源：http://dali.vqdsnc.cn/Article/details/gtxqjqimyo.html

Py:   s == s[::-1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtpehdmeud.html

PHP:  $s === strrev($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gteciabkeb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yuxming.cn/Article/details/gtvxonxxuv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ydzc1.top/Article/details/gtfluzibwj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinqigufen.top/Article/details/gtkpamceyo.html

Go:   // 双指针从两端比较
来源：http://dali.xuetiantiany.cn/Article/details/gtfhtgcqyd.html

Ruby: s == s.reverse
来源：http://dali.ivvv.top/Article/details/gtjdmqeeyp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.aizwys.cn/Article/details/gtogeygivk.html

[N07] 两数之和（返回下标）
来源：http://dali.jianghu66.top/Article/details/gtzpcifkvn.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cqqwz.cn/Article/details/gtvwekvekd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zycfv.cn/Article/details/gthylyxqvx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.nanxuanxn.top/Article/details/gthgsgpjyt.html

TS:   // 手写 Map<string, number>
来源：http://dali.tian-w.cn/Article/details/gtxxykneuk.html

Java: // 手写 HashMap
来源：http://dali.cdnleiting.top/Article/details/gtnxsjtjng.html

Go:   // 手写 map[int]int
来源：http://dali.shuidangran.top/Article/details/gtaawtpbvy.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gtbvszrdmx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hnqzz.top/Article/details/gtofgcbvwm.html

[N08] 生成全排列
来源：http://dali.chenjidiqi.icu/Article/details/gtftgvigjx.html

Py:   itertools.permutations(arr)
来源：http://dali.smart0.xyz/Article/details/gtvskozfgv.html

PHP:  // 手写递归交换
来源：http://dali.iojbl.cn/Article/details/gtjmvcozvh.html

JS:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gtqkolpzuh.html

TS:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gtjnlzlgqv.html

Java: // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gteofirenj.html

Go:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gtmnrwakrl.html

Ruby: arr.permutation.to_a
来源：http://dali.jlsjyb.cn/Article/details/gtekcjgtxi.html

C#:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gtvarelqdc.html

[N09] 栈与队列
来源：http://dali.cashguo.top/Article/details/gtyigiiffv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shuidangran.top/Article/details/gtbyprtsdw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.316326.xyz/Article/details/gtoheyixdn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhixingplan.top/Article/details/gtpwvsypre.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.wangshuangyany.cn/Article/details/gttazkkwuj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yj20258888.top/Article/details/gtfereonln.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hywenlv.cn/Article/details/gttdzwirlc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinqigufen.top/Article/details/gttbetywey.html


<!-- 参考信息 -->