代发 wailian999

[K02] JSON 字符串转对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2szqbwflq.html

Py:   json.loads(s)
来源：http://dali.iojbl.cn/Article/details/gt2uzemawgy.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.redwolf501.top/Article/details/gt2bdxlaswr.html

JS:   JSON.parse(s)
来源：http://dali.gzhubu.top/Article/details/gt2twdisgne.html

TS:   JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gt2yqngmdnb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.tian-w.cn/Article/details/gt2tburcgia.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jianghu66.top/Article/details/gt2msaouytp.html

Ruby: JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2aavqfssm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2inxufrvg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinqigfzy.top/Article/details/gt2ogkmivqk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yvedp.cn/Article/details/gt2ihqqpuho.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.bjfxy.top/Article/details/gt2bzgmxjxw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ndslwhtq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cheryme.top/Article/details/gt2rbpfxgyk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.pycfn.com/Article/details/gt2sibkvsmu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhongyouzk.top/Article/details/gt2sinydhxb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.birdmap.top/Article/details/gt2zziofpwd.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hysaishi.cn/Article/details/gt2retltrus.html

[K04] 读取 JSON 文件
来源：http://dali.vqdsnc.cn/Article/details/gt2lxvxnula.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shuidangran.top/Article/details/gt2rtlxlvqm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhengqikj.top/Article/details/gt2sdgidfhu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigufen.top/Article/details/gt2msvylchv.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuanzx.com/Article/details/gt2ppubvrit.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jianghu66.top/Article/details/gt2qlsiceeh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.tanke756.top/Article/details/gt2clojydeb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sufxvd.cn/Article/details/gt2wfthwgmo.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.0kj1m.cn/Article/details/gt2jlutskpw.html

[K05] 深拷贝对象
来源：http://dali.hnqzz.top/Article/details/gt2ccqkhnxo.html

Py:   copy.deepcopy(obj)
来源：http://dali.hnqzz.top/Article/details/gt2awlywwqx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ehwqpu.com/Article/details/gt2ukgfxitz.html

JS:   structuredClone(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fyacavkg.html

TS:   structuredClone(obj)
来源：http://dali.guannengcc.top/Article/details/gt2pmqmtixh.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zycfv.cn/Article/details/gt2rdyjvivw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cucudq.cn/Article/details/gt2tdihsggr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nanxinkj.top/Article/details/gt2yyddsmtk.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nympjykj.html

[K06] 解析 URL 查询串
来源：http://dali.sxryk.cn/Article/details/gt2erxbkldl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.smart0.xyz/Article/details/gt2qgubdtif.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yvedp.cn/Article/details/gt2uahgiodm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigfzy.top/Article/details/gt2wdftirjk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ivvv.top/Article/details/gt2mfidfdoa.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cqqwz.cn/Article/details/gt2hohpgnvs.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gt2pdmnkbyl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hywenlv.cn/Article/details/gt2pelehlfe.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gt2gjwnfivw.html

[K07] 进制转换
来源：http://dali.gaohongyu789.top/Article/details/gt2nuwmhwrs.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gt2mypjezty.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.fzhhl.top/Article/details/gt2iusmbewx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gt2wpigswxv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gt2zfstfhmj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cashguo.top/Article/details/gt2fztxnahl.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xziqi.cn/Article/details/gt2onopwxoj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhengqikj.top/Article/details/gt2nvlixlaj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gt2caydmgab.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yj202588.top/Article/details/gt2kkglcond.html

Py:   pickle.dumps(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2wzsxsbzu.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yvedp.cn/Article/details/gt2gfumlvab.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.daxiang520.top/Article/details/gt2nuwgxpid.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhoulong.xyz/Article/details/gt2uftywcwd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shzxlz.cn/Article/details/gt2eiyfcsbl.html

Go:   encoding/gob
来源：http://dali.jinqigufen.top/Article/details/gt2ejnzyoyu.html

Ruby: Marshal.dump(obj)
来源：http://dali.sweek.top/Article/details/gt2uqxexfix.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ehwqpu.com/Article/details/gt2cejzunox.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2mxbugcig.html

L. 网络请求
来源：http://dali.jiagoushi.top/Article/details/gt2nyjxhzqz.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2wwfyozmh.html

[L01] 发送 GET 请求
来源：http://dali.xylfe.cn/Article/details/gt2swwljzky.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.dashuyun.cn/Article/details/gt2oruwdlor.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.dashuyun.cn/Article/details/gt2gejumxmg.html

JS:   await fetch(url)
来源：http://dali.shzxlz.cn/Article/details/gt2kckrvmmx.html

TS:   await fetch(url)
来源：http://dali.ydzc1.top/Article/details/gt2gvufqefr.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.tanke756.top/Article/details/gt2xyqpjzmq.html

Go:   resp, err := http.Get(url)
来源：http://dali.yonumen.top/Article/details/gt2booywalr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.bjfxy.top/Article/details/gt2zsfgupxj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezxkfqbf.html

[L02] 发送 POST JSON
来源：http://dali.bjfxy.top/Article/details/gt2ybhbqloh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.fzhhl.top/Article/details/gt2rwmatuht.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ivvv.top/Article/details/gt2eezxpoei.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yanxiufei.cn/Article/details/gt2lpsayipg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xylfe.cn/Article/details/gt2urnncmqd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ybcxt.top/Article/details/gt2ozvlyyty.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.316326.xyz/Article/details/gt2ujfqkgwb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yonumen.top/Article/details/gt2ssviwmle.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sxryk.cn/Article/details/gt2qdclytkj.html

[L03] 设置自定义请求头
来源：http://dali.fzhhl.top/Article/details/gt2itcyhwat.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hfpthk.cn/Article/details/gt2klkhyxin.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.redwolf501.top/Article/details/gt2amotwxwd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cdnleiting.top/Article/details/gt2jfvwptwo.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jyoumei.cn/Article/details/gt2idjhhjzf.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xuetiantiany.cn/Article/details/gt2zorabpge.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sufxvd.cn/Article/details/gt2eudgbvvv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yuanzhike.top/Article/details/gt2ibcvbpuf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jyoumei.cn/Article/details/gt2lxniittr.html

[L04] 设置超时
来源：http://dali.xylfe.cn/Article/details/gt2cwuuitss.html

Py:   requests.get(url, timeout=5)
来源：http://dali.meibo888.top/Article/details/gt2rbcwenek.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hnqzz.top/Article/details/gt2jmvbttym.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guannengcc.top/Article/details/gt2swkroewm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dashuyun.cn/Article/details/gt2aydxtkwg.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.dianchejie.cn/Article/details/gt2bcjqutjh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.fengsongda.top/Article/details/gt2jiprcecb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yuanzhike.top/Article/details/gt2blxtaqma.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.tian-w.cn/Article/details/gt2euwwszon.html

[L05] 上传文件（multipart）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sudoehgc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hnxiangtu.top/Article/details/gt2hcnonajq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xinyue.icu/Article/details/gt2fcjwmapf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenjidiqi.icu/Article/details/gt2vsrbylxa.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxuanxn.top/Article/details/gt2mqaaadxf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.svipenyu.cn/Article/details/gt2hrczgytw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zdqjudy.top/Article/details/gt2jjpldfxy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.0kj1m.cn/Article/details/gt2forknaan.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2biejnzps.html

[L06] 解析响应为 JSON
来源：http://dali.cdnleiting.top/Article/details/gt2hfzosnvd.html

Py:   resp.json()
来源：http://dali.fzhhl.top/Article/details/gt2emsqcnwl.html

PHP:  json_decode($body, true);
来源：http://dali.jianghu66.top/Article/details/gt2pvmpujnp.html

JS:   await resp.json()
来源：http://dali.shuidangran.top/Article/details/gt2udmusram.html

TS:   await resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qnzbijpq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.nwbrower.top/Article/details/gt2qhrftgbb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.dashuyun.cn/Article/details/gt2jxyksgvs.html

Ruby: JSON.parse(resp.body)
来源：http://dali.chenlongwang.top/Article/details/gt2pgsvkpjy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.smart0.xyz/Article/details/gt2juubewpn.html

[L07] 处理 HTTP 状态码
来源：http://dali.aibaodan.cn/Article/details/gt2mzuznulk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhongyouzk.top/Article/details/gt2jxbggugo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.haohaochexian.top/Article/details/gt2yxthcxas.html

JS:   resp.ok;  resp.status
来源：http://dali.gotoacloud.top/Article/details/gt2atgxmpks.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjqmcoy.html

Java: resp.statusCode()
来源：http://dali.yanxiufei.cn/Article/details/gt2qkswuzwi.html

Go:   resp.StatusCode
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wfnwkfmq.html

Ruby: resp.code.to_i
来源：http://dali.yangfankeji.com/Article/details/gt2fymamuuj.html

C#:   (int)resp.StatusCode
来源：http://dali.hammf.cn/Article/details/gt2fksyosen.html

[L08] 并发请求多个地址
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fkysasqo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.haohaochexian.top/Article/details/gt2hjdtenac.html

PHP:  curl_multi_init() 系列
来源：http://dali.quarkkingdee.top/Article/details/gt2rmygkhxu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.9152youxi.cn/Article/details/gt2gpkreojt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cheryme.top/Article/details/gt2qmrjixnk.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.andypj.xyz/Article/details/gt2rhqovaua.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shangyingyoupin.top/Article/details/gt2qaiigazv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.aibaodan.cn/Article/details/gt2adaxsfvx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zdqjudy.top/Article/details/gt2bxlttpip.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2galhhmmb.html

M. 命令行 / 进程 / 环境
来源：http://dali.shangyingyoupin.top/Article/details/gt2oihatbpj.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2udtvwbnj.html

[M01] 读取命令行参数
来源：http://dali.zdqjudy.top/Article/details/gt2khpodmke.html

Py:   sys.argv[1:]
来源：http://dali.zhiwuduotai.top/Article/details/gt2bjzsgjtt.html

PHP:  $argv;  $argc;
来源：http://dali.yuxming.cn/Article/details/gt2oxudxaws.html

JS:   process.argv.slice(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pkorlaqq.html

TS:   process.argv.slice(2)
来源：http://dali.havefunace.top/Article/details/gt2qokrpznb.html

Java: args 数组（main 方法参数）
来源：http://dali.shzxlz.cn/Article/details/gt2jmdprowm.html

Go:   os.Args[1:]
来源：http://dali.hnxiangtu.top/Article/details/gt2lxsrwksu.html

Ruby: ARGV
来源：http://dali.shangyingyoupin.top/Article/details/gt2iftvmohs.html

C#:   args 数组（Main 方法参数）
来源：http://dali.mhx1999.top/Article/details/gt2uokjnpjx.html

[M02] 读取环境变量
来源：http://dali.yj202588.top/Article/details/gt2xsgtfpku.html

Py:   os.environ.get("HOME")
来源：http://dali.chenzaomai.com/Article/details/gt2opbuumzy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.chenlongwang.top/Article/details/gt2ocpnbfxv.html

JS:   process.env.HOME
来源：http://dali.fzhhl.top/Article/details/gt2uunicval.html

TS:   process.env.HOME
来源：http://dali.bjfxy.top/Article/details/gt2zhkjgotl.html

Java: System.getenv("HOME")
来源：http://dali.yvedp.cn/Article/details/gt2qjkgqyjm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.tanke756.top/Article/details/gt2rbgsfdvg.html

Ruby: ENV["HOME"]
来源：http://dali.dianchejie.cn/Article/details/gt2xsxoheqr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.haohaochexian.top/Article/details/gt2fwvhohpr.html

[M03] 执行外部命令
来源：http://dali.cqqwz.cn/Article/details/gt2pihkaybb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ehwqpu.com/Article/details/gt2nbldevqg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cucudq.cn/Article/details/gt2tnibqsdd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.daxiang520.top/Article/details/gt2ihfuqide.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tanke756.top/Article/details/gt2mzlcjpdo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jyoumei.cn/Article/details/gt2zxwbgjnt.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xuetiantiany.cn/Article/details/gt2rpjpzvab.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.haohaochexian.top/Article/details/gt2ljkhjjcc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xziqi.cn/Article/details/gt2uapigbfs.html

[M04] 获取当前工作目录
来源：http://dali.tian-w.cn/Article/details/gt2thhkgwge.html

Py:   os.getcwd()
来源：http://dali.yonumen.top/Article/details/gt2lzrecbvx.html

PHP:  getcwd();
来源：http://dali.hfpthk.cn/Article/details/gt2jjwnvarx.html

JS:   process.cwd()
来源：http://dali.jqgufenzy.top/Article/details/gt2btiufjba.html

TS:   process.cwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2llfmlvfp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.nwbrower.top/Article/details/gt2pwsrqkpd.html

Go:   os.Getwd()
来源：http://dali.cdnleiting.top/Article/details/gt2ynmnrzig.html

Ruby: Dir.pwd
来源：http://dali.snrcjt.cn/Article/details/gt2voxjjipf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jiagoushi.top/Article/details/gt2xtgovcsr.html

[M05] 设置退出码
来源：http://dali.zhixingplan.top/Article/details/gt2gqwtzdhw.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxmnlam.html

PHP:  exit(1);
来源：http://dali.0kj1m.cn/Article/details/gt2qaeocwar.html

JS:   process.exit(1)
来源：http://dali.hammf.cn/Article/details/gt2hzgeevga.html

TS:   process.exit(1)
来源：http://dali.bjfxy.top/Article/details/gt2dxmuvcsy.html

Java: System.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2yytysxdk.html

Go:   os.Exit(1)
来源：http://dali.sysykeji.top/Article/details/gt2ltybpemv.html

Ruby: exit 1
来源：http://dali.ppjwa.cn/Article/details/gt2dsjtwocy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.havefunace.top/Article/details/gt2xreftsep.html

[M06] 向标准错误输出
来源：http://dali.aibaodan.cn/Article/details/gt2jsxmafbn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xuanzx.com/Article/details/gt2gevfdvrm.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qkzowwps.html

JS:   console.error("err")
来源：http://dali.hongshengwenyu.top/Article/details/gt2owsqcedj.html

TS:   console.error("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mkvtegro.html

Java: System.err.println("err")
来源：http://dali.sweek.top/Article/details/gt2tnstllfw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cdnleiting.top/Article/details/gt2wydailqy.html

Ruby: warn "err"
来源：http://dali.gogol.net.cn/Article/details/gt2kkialmnh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.kuanghao11.cn/Article/details/gt2phlluzfo.html

[M07] 判断是否为主入口
来源：http://dali.hysaishi.cn/Article/details/gt2mbfanhjt.html

Py:   if __name__ == "__main__":
来源：http://dali.aizwys.cn/Article/details/gt2hurlyjop.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinqigfzy.top/Article/details/gt2yxlwowet.html

JS:   require.main === module
来源：http://dali.haohaochexian.top/Article/details/gt2kzesyvhh.html

TS:   require.main === module
来源：http://dali.cashguo.top/Article/details/gt2ipfyusxc.html

Java: public static void main(String[] args)
来源：http://dali.hywenlv.cn/Article/details/gt2vafvouin.html

Go:   func main()
来源：http://dali.redwolf501.top/Article/details/gt2cztinqco.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenjidiqi.icu/Article/details/gt2rgepabeu.html

C#:   static void Main(string[] args)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wsjahnas.html

[M08] 获取系统与运行时信息
来源：http://dali.xinyue.icu/Article/details/gt2prwauzku.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sufxvd.cn/Article/details/gt2tuwcepeu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.dashuyun.cn/Article/details/gt2lrdirffz.html

JS:   process.platform;  process.version
来源：http://dali.andypj.xyz/Article/details/gt2yenvdboj.html

TS:   process.platform;  process.version
来源：http://dali.yangfankeji.com/Article/details/gt2ycugsghv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sysykeji.top/Article/details/gt2lnlyckdg.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sysykeji.top/Article/details/gt2xxoiqrff.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yongpay.top/Article/details/gt2qbhuxayd.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.aibaodan.cn/Article/details/gt2vmhtvwel.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2yyhlcpug.html

N. 数据结构与算法
来源：http://dali.cdnleiting.top/Article/details/gt2gxtvvnqx.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2imlxoquc.html

[N01] 二分查找（有序数组）
来源：http://dali.jqgfzy.top/Article/details/gt2squykiuf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gt2qpafjzgd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.mhx1999.top/Article/details/gt2veuazhez.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gt2ydlcfran.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wgirpicf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yj202588.top/Article/details/gt2alihzain.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.smart0.xyz/Article/details/gt2iihmwkoh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sxryk.cn/Article/details/gt2qwxgkpxh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gt2ncfscqgo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinqigfzy.top/Article/details/gt2oarhjwjm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gzhubu.top/Article/details/gt2bwxyipte.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhixingplan.top/Article/details/gt2geytcmmv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wmdoggka.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.c1oappe.top/Article/details/gt2txrufjau.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.pycfn.com/Article/details/gt2hkznppbx.html

Go:   slices.Sort(arr)
来源：http://dali.hnqzz.top/Article/details/gt2vtlukfcu.html

Ruby: arr.sort
来源：http://dali.sysykeji.top/Article/details/gt2vqzomnok.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.wangshuangyany.cn/Article/details/gt2vodgojqu.html

[N03] 快速排序（分治示例）
来源：http://dali.hysaishi.cn/Article/details/gt2bytlixto.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhoulong.xyz/Article/details/gt2ajyvbdie.html

PHP:  // 递归实现，或用 usort
来源：http://dali.pengpengdd.cyou/Article/details/gt2fhycezcs.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fzhhl.top/Article/details/gt2kzogccze.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhongyouzk.top/Article/details/gt2uieluzhe.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.daria6918.cn/Article/details/gt2dosnwagy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.svipenyu.cn/Article/details/gt2kzmlzjjz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xuetiantiany.cn/Article/details/gt2bdhpbkwg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.vqdsnc.cn/Article/details/gt2unglotee.html

[N04] 斐波那契数列
来源：http://dali.xuetiantiany.cn/Article/details/gt2gejouppr.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fkrrovwd.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hnqzz.top/Article/details/gt2dciucbgb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gt2kjhnxrho.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gt2lkcuuzts.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ivvv.top/Article/details/gt2ntyqqlbj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zycfv.cn/Article/details/gt2pndblczs.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2klbzmwmu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gt2sbdewpen.html

[N05] 最大公约数
来源：http://dali.gaohongyu789.top/Article/details/gt2ryydusug.html

Py:   math.gcd(a, b)
来源：http://dali.hysaishi.cn/Article/details/gt2ectudwsc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.nanxinkj.top/Article/details/gt2bcywtisk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hywenlv.cn/Article/details/gt2ziqhiuej.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2cpqwhciv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hnxiangtu.top/Article/details/gt2nxgyyfen.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.c1oappe.top/Article/details/gt2qswtgyel.html

Ruby: a.gcd(b)
来源：http://dali.daria6918.cn/Article/details/gt2ncvpagac.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gaohongyu789.top/Article/details/gt2raikgrft.html

[N06] 判断回文字符串
来源：http://dali.ppjwa.cn/Article/details/gt2kueeypeg.html

Py:   s == s[::-1]
来源：http://dali.cucudq.cn/Article/details/gt2lgvqhisc.html

PHP:  $s === strrev($s);
来源：http://dali.jinqigfzy.top/Article/details/gt2qldymdkq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gt2hrmddnrj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gt2sxraoake.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sysykeji.top/Article/details/gt2lzwpmyow.html

Go:   // 双指针从两端比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vkswpyhz.html

Ruby: s == s.reverse
来源：http://dali.zhiwuduotai.top/Article/details/gt2hcuzyzkz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.tian-w.cn/Article/details/gt2gbkcioez.html

[N07] 两数之和（返回下标）
来源：http://dali.gotoacloud.top/Article/details/gt2fgmnshxl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yvedp.cn/Article/details/gt2wnaxkikc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xziqi.cn/Article/details/gt2isvjngpm.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yj20258.top/Article/details/gt2mntmklys.html

TS:   // 手写 Map<string, number>
来源：http://dali.xziqi.cn/Article/details/gt2hrzxqrsf.html

Java: // 手写 HashMap
来源：http://dali.yvedp.cn/Article/details/gt2odjiqpkt.html

Go:   // 手写 map[int]int
来源：http://dali.cashguo.top/Article/details/gt2sqguifrd.html

Ruby: // 手写 Hash
来源：http://dali.ehwqpu.com/Article/details/gt2hekbcsfb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.316326.xyz/Article/details/gt2nuoyrigp.html

[N08] 生成全排列
来源：http://dali.yj20258.top/Article/details/gt2xxmxgtiy.html

Py:   itertools.permutations(arr)
来源：http://dali.sxryk.cn/Article/details/gt2dsynwxsm.html

PHP:  // 手写递归交换
来源：http://dali.cqqwz.cn/Article/details/gt2diiqwvmt.html

JS:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gt2fpcbvxzs.html

TS:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gt2dycxihec.html

Java: // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zswkoyyd.html

Go:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gt2amzekpof.html

Ruby: arr.permutation.to_a
来源：http://dali.sweek.top/Article/details/gt2heeotuev.html

C#:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gt2ugegzubr.html

[N09] 栈与队列
来源：http://dali.cqqwz.cn/Article/details/gt2okqiajnh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.pycfn.com/Article/details/gt2qbtxxusc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gt2isgxjzrw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.tanke756.top/Article/details/gt2hsbfjwmv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xinyue.icu/Article/details/gt2jcvecnwd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.guowangkeji.top/Article/details/gt2soqcaobz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.316326.xyz/Article/details/gt2nkxnbiyl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.guowangkeji.top/Article/details/gt2gmqvkesh.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cashguo.top/Article/details/gt2bfgjggmd.html

[N10] 链表节点定义
来源：http://dali.birdmap.top/Article/details/gt2avljujby.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hammf.cn/Article/details/gt2xwlchqwu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hywenlv.cn/Article/details/gt2wjqulolh.html


<!-- 参考信息 -->