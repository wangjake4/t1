代发 wailian999

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shangyingyoupin.top/Article/details/gtmalqqfow.html

Go:   json.Marshal(obj)
来源：http://dali.shuidangran.top/Article/details/gtifelbnhp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cheryme.top/Article/details/gtgffrbzdv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jianghu66.top/Article/details/gtshuexzgi.html

[K02] JSON 字符串转对象
来源：http://dali.zhixingplan.top/Article/details/gtubvgahut.html

Py:   json.loads(s)
来源：http://dali.yj202588.top/Article/details/gtqtpelfsa.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hnqzz.top/Article/details/gtarjtwgth.html

JS:   JSON.parse(s)
来源：http://dali.sufxvd.cn/Article/details/gtxfxoaakr.html

TS:   JSON.parse(s)
来源：http://dali.ehwqpu.com/Article/details/gtamumcjfq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yangfankeji.com/Article/details/gtegodemgd.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.guowangkeji.top/Article/details/gtmguyhyhn.html

Ruby: JSON.parse(s)
来源：http://dali.yj202588.top/Article/details/gtdasetaks.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cucudq.cn/Article/details/gticgyatqh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhiwuduotai.top/Article/details/gtrgfhbucx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xuetiantiany.cn/Article/details/gtjspiwnvz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tian-w.cn/Article/details/gtppvuogyo.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xylfe.cn/Article/details/gtrguebwxe.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.9152youxi.cn/Article/details/gtbflkgics.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gaohongyu789.top/Article/details/gteafaciqw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shangyingyoupin.top/Article/details/gtoxtoqcsm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.guowangkeji.top/Article/details/gtichwuzeu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tanke756.top/Article/details/gtnpbcljkc.html

[K04] 读取 JSON 文件
来源：http://dali.gzhubu.top/Article/details/gtcnhhhika.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hfpthk.cn/Article/details/gtpfptddsm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yueranfly.top/Article/details/gtrvzrqozm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258.top/Article/details/gtsyvmgpdo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cdnleiting.top/Article/details/gtsjiideej.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gtveuthxtz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.fengsongda.top/Article/details/gtoqtwhxjv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sysykeji.top/Article/details/gttgznywjg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gzhubu.top/Article/details/gtlyvqwlmc.html

[K05] 深拷贝对象
来源：http://dali.nanxuanxn.top/Article/details/gtetzhkrfn.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtmmfukpxx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.fzhhl.top/Article/details/gtfaebakwv.html

JS:   structuredClone(obj)
来源：http://dali.vqdsnc.cn/Article/details/gttjyjezdz.html

TS:   structuredClone(obj)
来源：http://dali.daxiang520.top/Article/details/gtpuwwwilg.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinqigufen.top/Article/details/gtuyivirxo.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xuetiantiany.cn/Article/details/gtnrcbrfwp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhongyouzk.top/Article/details/gtwplevswr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hfpthk.cn/Article/details/gtljsawldo.html

[K06] 解析 URL 查询串
来源：http://dali.chenjidiqi.icu/Article/details/gtnvtcxram.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shzxlz.cn/Article/details/gtmseidsym.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.vqdsnc.cn/Article/details/gtiswnwjon.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hywenlv.cn/Article/details/gtnuxytoum.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yangfankeji.com/Article/details/gtkxedrkfr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cdnleiting.top/Article/details/gtgopoubrn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhixingplan.top/Article/details/gtnihzuhcj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shanyushiyangtech.top/Article/details/gtghvsijkn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hfpthk.cn/Article/details/gtmpqdcnhy.html

[K07] 进制转换
来源：http://dali.shuidangran.top/Article/details/gtkhawqzku.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gtfwbpkhmg.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.chenzaomai.com/Article/details/gtvrqmmhdd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuvullrgl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.meibo888.top/Article/details/gtvfvndpgy.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtdixczsru.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.andypj.xyz/Article/details/gtnvthhwgz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ydzc1.top/Article/details/gtfbbcnhqb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gtnsddstgb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xylfe.cn/Article/details/gtnwfrzdsv.html

Py:   pickle.dumps(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtczxncjuj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.vqdsnc.cn/Article/details/gttetvqejq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.haohaochexian.top/Article/details/gtkgtqaoek.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sysykeji.top/Article/details/gtendwoxfm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.daria6918.cn/Article/details/gtfmsrzbxi.html

Go:   encoding/gob
来源：http://dali.kuanghao11.cn/Article/details/gtzznndsvp.html

Ruby: Marshal.dump(obj)
来源：http://dali.fzhhl.top/Article/details/gterddergd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinqigfzy.top/Article/details/gtqccvhwje.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmiwrennc.html

L. 网络请求
来源：http://dali.aizwys.cn/Article/details/gtulbwsqwd.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtyhmxbouw.html

[L01] 发送 GET 请求
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxpnqrvhi.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.dianchejie.cn/Article/details/gttcnosrad.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ydzc1.top/Article/details/gtauwaelfq.html

JS:   await fetch(url)
来源：http://dali.ydzc1.top/Article/details/gtnlbxxhcn.html

TS:   await fetch(url)
来源：http://dali.meibo888.top/Article/details/gtcnbmvfbn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtinylpncw.html

Go:   resp, err := http.Get(url)
来源：http://dali.svipenyu.cn/Article/details/gtljxrydva.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sufxvd.cn/Article/details/gtfuvultdn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hfpthk.cn/Article/details/gtgvwdplyj.html

[L02] 发送 POST JSON
来源：http://dali.smart0.xyz/Article/details/gtlefqumbf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.daxiang520.top/Article/details/gtdqlbihzw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhoulong.xyz/Article/details/gtxxoyypab.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dianchejie.cn/Article/details/gtocmpgzqk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.bjfxy.top/Article/details/gtwzvffdhi.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hfpthk.cn/Article/details/gtvzdylhhy.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yangfankeji.com/Article/details/gtwmjftscu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jyoumei.cn/Article/details/gtmbscdaxo.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yj202588.top/Article/details/gtgmnfdvpd.html

[L03] 设置自定义请求头
来源：http://dali.chenjidiqi.icu/Article/details/gtipjgdnka.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.redwolf501.top/Article/details/gtfiqpakrx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.haohaochexian.top/Article/details/gtufqucwbj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sysykeji.top/Article/details/gtmepwddac.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cheryme.top/Article/details/gtlqbcjmqr.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.meibo888.top/Article/details/gtpavhkxcw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ybcxt.top/Article/details/gtrxphzxyx.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.redwolf501.top/Article/details/gtanbfiudd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.tanke756.top/Article/details/gtzchyltbn.html

[L04] 设置超时
来源：http://dali.vqdsnc.cn/Article/details/gtsodyndcn.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yanxiufei.cn/Article/details/gtknomkcvg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtajzidvzp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hfpthk.cn/Article/details/gtolbhmgsr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xinyue.icu/Article/details/gtomijyulq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhoulong.xyz/Article/details/gtrogfhdmo.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.andypj.xyz/Article/details/gtinidnlnp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jiagoushi.top/Article/details/gtucqzqjcj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hnqzz.top/Article/details/gtonmmjopz.html

[L05] 上传文件（multipart）
来源：http://dali.nanxinkj.top/Article/details/gttqxfczam.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jqgufenzy.top/Article/details/gtiwkuofaw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.tianlin.xyz/Article/details/gtfultcekp.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.kuanghao11.cn/Article/details/gtanpxskxu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shzxlz.cn/Article/details/gtcwgtrdyh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hysaishi.cn/Article/details/gtulfiamwc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ehwqpu.com/Article/details/gtrdpdmkac.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.9152youxi.cn/Article/details/gtgumrqkbr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jiagoushi.top/Article/details/gttzylqzvb.html

[L06] 解析响应为 JSON
来源：http://dali.hywenlv.cn/Article/details/gtmifwddbj.html

Py:   resp.json()
来源：http://dali.yuanzhike.top/Article/details/gthmorbwpu.html

PHP:  json_decode($body, true);
来源：http://dali.aizwys.cn/Article/details/gtjtheaiui.html

JS:   await resp.json()
来源：http://dali.daria6918.cn/Article/details/gttbacpvxm.html

TS:   await resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gtqvbqbiuh.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenlongwang.top/Article/details/gtlrsoevgo.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hnxiangtu.top/Article/details/gtyusbgtlh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gtloyyxoeb.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.meibo888.top/Article/details/gtjnmvulny.html

[L07] 处理 HTTP 状态码
来源：http://dali.havefunace.top/Article/details/gtafoyjkig.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.chenlongwang.top/Article/details/gtqnfmfcuj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.316326.xyz/Article/details/gtogzpqdrf.html

JS:   resp.ok;  resp.status
来源：http://dali.aizwys.cn/Article/details/gttasoerdv.html

TS:   resp.ok;  resp.status
来源：http://dali.jianghu66.top/Article/details/gtgnlrnfvp.html

Java: resp.statusCode()
来源：http://dali.svipenyu.cn/Article/details/gtpuktlfmg.html

Go:   resp.StatusCode
来源：http://dali.quarkkingdee.top/Article/details/gtjproehuk.html

Ruby: resp.code.to_i
来源：http://dali.pycfn.com/Article/details/gtwgfrsbfk.html

C#:   (int)resp.StatusCode
来源：http://dali.vqdsnc.cn/Article/details/gtarswhgtu.html

[L08] 并发请求多个地址
来源：http://dali.tianlin.xyz/Article/details/gthmbbwasb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zycfv.cn/Article/details/gtipsjykkq.html

PHP:  curl_multi_init() 系列
来源：http://dali.vqdsnc.cn/Article/details/gtruzjmjlv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cashguo.top/Article/details/gtsjqrdwqb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigufen.top/Article/details/gtsqixvxmj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ppjwa.cn/Article/details/gtqcyxvidt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jianghu66.top/Article/details/gtpbibdquw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.guowangkeji.top/Article/details/gtenqjffan.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yueranfly.top/Article/details/gtaejjgdva.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtyklgyxyt.html

M. 命令行 / 进程 / 环境
来源：http://dali.jiagoushi.top/Article/details/gtfnymqifw.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtrgrbtjne.html

[M01] 读取命令行参数
来源：http://dali.havefunace.top/Article/details/gtguippbvk.html

Py:   sys.argv[1:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcbrlyajh.html

PHP:  $argv;  $argc;
来源：http://dali.nanxinkj.top/Article/details/gtgprifxse.html

JS:   process.argv.slice(2)
来源：http://dali.yj20258888.top/Article/details/gtltmnxqwz.html

TS:   process.argv.slice(2)
来源：http://dali.snrcjt.cn/Article/details/gtxgswadbs.html

Java: args 数组（main 方法参数）
来源：http://dali.zhixingplan.top/Article/details/gtmmssxhza.html

Go:   os.Args[1:]
来源：http://dali.sufxvd.cn/Article/details/gtdsdbzoqs.html

Ruby: ARGV
来源：http://dali.feifeiyinyue.top/Article/details/gtwgecrhlp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.tianlin.xyz/Article/details/gtpumgyrmg.html

[M02] 读取环境变量
来源：http://dali.dashuyun.cn/Article/details/gtvfmtektk.html

Py:   os.environ.get("HOME")
来源：http://dali.gogol.net.cn/Article/details/gtqutmtycd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.0kj1m.cn/Article/details/gtrzigdnxs.html

JS:   process.env.HOME
来源：http://dali.ppjwa.cn/Article/details/gtfswougap.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gtaecelogd.html

Java: System.getenv("HOME")
来源：http://dali.cashguo.top/Article/details/gttweyeqis.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.bjfxy.top/Article/details/gtgfhmtpor.html

Ruby: ENV["HOME"]
来源：http://dali.cqqwz.cn/Article/details/gtheefkzwq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ivvv.top/Article/details/gtunyxbisy.html

[M03] 执行外部命令
来源：http://dali.hongshengwenyu.top/Article/details/gtrmfpducu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hywenlv.cn/Article/details/gtyznnnbvf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shuidangran.top/Article/details/gthderpddk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.daxiang520.top/Article/details/gtvtxjcbzs.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvieerwjp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cucudq.cn/Article/details/gtibfmrvgn.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cdnleiting.top/Article/details/gthcnkvpzn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zdqjudy.top/Article/details/gtvjapobwy.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zycfv.cn/Article/details/gtneraepnn.html

[M04] 获取当前工作目录
来源：http://dali.wangdashe.top/Article/details/gtmtoyaryb.html

Py:   os.getcwd()
来源：http://dali.hongshengwenyu.top/Article/details/gtcztcuabp.html

PHP:  getcwd();
来源：http://dali.yanxiufei.cn/Article/details/gtfryzmhzx.html

JS:   process.cwd()
来源：http://dali.cdnleiting.top/Article/details/gtbfytdbhd.html

TS:   process.cwd()
来源：http://dali.smart0.xyz/Article/details/gtmwoghwgw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ehwqpu.com/Article/details/gtcidmeymc.html

Go:   os.Getwd()
来源：http://dali.hammf.cn/Article/details/gtyjqabhxq.html

Ruby: Dir.pwd
来源：http://dali.shzxlz.cn/Article/details/gtyukhtaze.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hongshengwenyu.top/Article/details/gtmgbkumpy.html

[M05] 设置退出码
来源：http://dali.hammf.cn/Article/details/gtuclvefoa.html

Py:   sys.exit(1)
来源：http://dali.iojbl.cn/Article/details/gtjofyuaxn.html

PHP:  exit(1);
来源：http://dali.chenjidiqi.icu/Article/details/gtprzdcevv.html

JS:   process.exit(1)
来源：http://dali.xylfe.cn/Article/details/gtxchfecun.html

TS:   process.exit(1)
来源：http://dali.meibo888.top/Article/details/gttiuzlekn.html

Java: System.exit(1)
来源：http://dali.xinyue.icu/Article/details/gtwztsgsol.html

Go:   os.Exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gtfldpwtck.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gtfznwvtij.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.guowangkeji.top/Article/details/gtoftlnsov.html

[M06] 向标准错误输出
来源：http://dali.cdnleiting.top/Article/details/gtfkwvbcmo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xinyue.icu/Article/details/gtltjqzcnk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yuanzhike.top/Article/details/gttxvpvmts.html

JS:   console.error("err")
来源：http://dali.guowangkeji.top/Article/details/gtygpdnbsz.html

TS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gtcemnwinh.html

Java: System.err.println("err")
来源：http://dali.aibaodan.cn/Article/details/gterkvkxhp.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ehwqpu.com/Article/details/gttqikxwxr.html

Ruby: warn "err"
来源：http://dali.tanke756.top/Article/details/gtmehogbcm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.bjfxy.top/Article/details/gtjgbvtfgq.html

[M07] 判断是否为主入口
来源：http://dali.chenzaomai.com/Article/details/gtggtvzkdc.html

Py:   if __name__ == "__main__":
来源：http://dali.c1oappe.top/Article/details/gtqbssjdsp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jlsjyb.cn/Article/details/gtnsqyppkz.html

JS:   require.main === module
来源：http://dali.quarkkingdee.top/Article/details/gtmowptbjk.html

TS:   require.main === module
来源：http://dali.jinqigufen.top/Article/details/gtmodvagev.html

Java: public static void main(String[] args)
来源：http://dali.wangdashe.top/Article/details/gtuoojdooz.html

Go:   func main()
来源：http://dali.kuanghao11.cn/Article/details/gtjymqolxm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yonumen.top/Article/details/gtygdxaycz.html

C#:   static void Main(string[] args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtptjalvjs.html

[M08] 获取系统与运行时信息
来源：http://dali.aibaodan.cn/Article/details/gtkvvrpijy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.9152youxi.cn/Article/details/gtgskfmffx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cheryme.top/Article/details/gtxzdqbqyc.html

JS:   process.platform;  process.version
来源：http://dali.smart0.xyz/Article/details/gtecimkjfl.html

TS:   process.platform;  process.version
来源：http://dali.chenlongwang.top/Article/details/gtldcexoyc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrwfazlrl.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.meibo888.top/Article/details/gtboumbmeo.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.fengsongda.top/Article/details/gtzprflllg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.wangdashe.top/Article/details/gtljxyrkmz.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtanfbaias.html

N. 数据结构与算法
来源：http://dali.aibaodan.cn/Article/details/gttcyepfom.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtprwwiiny.html

[N01] 二分查找（有序数组）
来源：http://dali.hnqzz.top/Article/details/gtzjimfsmq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gtqfyxkijm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhiwuduotai.top/Article/details/gtpqpjdtql.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258888.top/Article/details/gtfqvlllnf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pycfn.com/Article/details/gtghpivkld.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtagpxyefn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtsgndryde.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhiwuduotai.top/Article/details/gteihmjkcy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtoivdbbvv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nwbrower.top/Article/details/gteybsceog.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fzhhl.top/Article/details/gtaykbbymt.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ehwqpu.com/Article/details/gtkdctapbd.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.9152youxi.cn/Article/details/gtexmlvkyp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hongshengwenyu.top/Article/details/gtcyuuxrlf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.pengpengdd.cyou/Article/details/gtujpwcrse.html

Go:   slices.Sort(arr)
来源：http://dali.pycfn.com/Article/details/gtwqriebdv.html

Ruby: arr.sort
来源：http://dali.yangfankeji.com/Article/details/gtlrmygkld.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hongshengwenyu.top/Article/details/gtusvgninu.html

[N03] 快速排序（分治示例）
来源：http://dali.yanxiufei.cn/Article/details/gtngdzmmvu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhixingplan.top/Article/details/gtghghhokg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.sxryk.cn/Article/details/gtlpaqttwu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gaohongyu789.top/Article/details/gtsyfonouk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.andypj.xyz/Article/details/gtdsddsyeg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yongpay.top/Article/details/gtttsfcgco.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yonumen.top/Article/details/gtfzeyacvg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yvedp.cn/Article/details/gtqpztekgg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tian-w.cn/Article/details/gtzttsgvii.html

[N04] 斐波那契数列
来源：http://dali.meibo888.top/Article/details/gtqmzgxcgf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sysykeji.top/Article/details/gtuibtezza.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cashguo.top/Article/details/gtxewpcrfc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ybcxt.top/Article/details/gtbwqrgnol.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gaohongyu789.top/Article/details/gtpplckrdw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.nanxinkj.top/Article/details/gtklyvhgbx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxtwppwue.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ivvv.top/Article/details/gtggpvjjtz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hnxiangtu.top/Article/details/gtkomdokbo.html

[N05] 最大公约数
来源：http://dali.shzxlz.cn/Article/details/gtaezbwlpb.html

Py:   math.gcd(a, b)
来源：http://dali.bjfxy.top/Article/details/gtowttnrig.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gogol.net.cn/Article/details/gtppwernce.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnxiangtu.top/Article/details/gtznrnutzp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.andypj.xyz/Article/details/gtaqsvftmj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yj20258888.top/Article/details/gtkalcqaqn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cqqwz.cn/Article/details/gtwnkwubab.html

Ruby: a.gcd(b)
来源：http://dali.shuidangran.top/Article/details/gtnzeklbdt.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.quarkkingdee.top/Article/details/gttyjxquah.html

[N06] 判断回文字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpneoheiz.html

Py:   s == s[::-1]
来源：http://dali.chenlongwang.top/Article/details/gtjpncacdj.html

PHP:  $s === strrev($s);
来源：http://dali.yuanzhike.top/Article/details/gtdglepelp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gtbyxufilu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gttmketxzk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhiwuduotai.top/Article/details/gtrzxpwoyw.html

Go:   // 双指针从两端比较
来源：http://dali.xinyue.icu/Article/details/gtxxikgczc.html

Ruby: s == s.reverse
来源：http://dali.jianghu66.top/Article/details/gtjrixfqla.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sxryk.cn/Article/details/gtpopyalkq.html

[N07] 两数之和（返回下标）
来源：http://dali.tianlin.xyz/Article/details/gtoowtrsqy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.dashuyun.cn/Article/details/gtaunwoxnp.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hammf.cn/Article/details/gtppapvdag.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.dianchejie.cn/Article/details/gtczrrlwdw.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhoulong.xyz/Article/details/gtmrhwqogg.html

Java: // 手写 HashMap
来源：http://dali.pengpengdd.cyou/Article/details/gtflogjqps.html

Go:   // 手写 map[int]int
来源：http://dali.jinqigufen.top/Article/details/gtvuajrvgf.html

Ruby: // 手写 Hash
来源：http://dali.chenzaomai.com/Article/details/gtwmgheerg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gaohongyu789.top/Article/details/gtxdgbvihw.html

[N08] 生成全排列
来源：http://dali.shanyushiyangtech.top/Article/details/gtdckritjh.html

Py:   itertools.permutations(arr)
来源：http://dali.zhengqikj.top/Article/details/gtpizghvog.html

PHP:  // 手写递归交换
来源：http://dali.yj20258888.top/Article/details/gteplwbqld.html

JS:   // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gtlmhludxc.html

TS:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gtrurxzimi.html

Java: // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gtauyipcrs.html

Go:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtxomhxfxn.html

Ruby: arr.permutation.to_a
来源：http://dali.birdmap.top/Article/details/gtbdibpayu.html

C#:   // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gtcuahlqff.html

[N09] 栈与队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtibjcvsox.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.kuanghao11.cn/Article/details/gtaitlzqan.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gtbuornykr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.kuanghao11.cn/Article/details/gtxxlzimdb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yueranfly.top/Article/details/gtcsmfcdco.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.feifeiyinyue.top/Article/details/gtwatsfomd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.9152youxi.cn/Article/details/gtpyqvgcdc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hammf.cn/Article/details/gtirfktujf.html


<!-- 参考信息 -->