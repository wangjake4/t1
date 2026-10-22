代发 wailian999

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ewllsddh.html

Go:   json.Marshal(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2gpucttzv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.tianlin.xyz/Article/details/gt2vofoudwg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xuanzx.com/Article/details/gt2lbsbejto.html

[K02] JSON 字符串转对象
来源：http://dali.shzxlz.cn/Article/details/gt2fhkvtjuh.html

Py:   json.loads(s)
来源：http://dali.yj20258888.top/Article/details/gt2anyluecg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenzaomai.com/Article/details/gt2bwyelypq.html

JS:   JSON.parse(s)
来源：http://dali.yangfankeji.com/Article/details/gt2geivioce.html

TS:   JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gt2qpyscepj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.dianchejie.cn/Article/details/gt2qymwyxln.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.0kj1m.cn/Article/details/gt2pavjhguv.html

Ruby: JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gt2ungpubds.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2ddpxxfdm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhiwuduotai.top/Article/details/gt2wxzftljd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.haohaochexian.top/Article/details/gt2orsxgzae.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.aibaodan.cn/Article/details/gt2gjqhzgbh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhengqikj.top/Article/details/gt2qautktlv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2vkmhkrju.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2egsxdswm.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sufxvd.cn/Article/details/gt2buexlqgq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2oztkpzov.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.feifeiyinyue.top/Article/details/gt2yihmivvo.html

[K04] 读取 JSON 文件
来源：http://dali.guannengcc.top/Article/details/gt2xqsydrta.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.nwbrower.top/Article/details/gt2kluvpzpz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.svipenyu.cn/Article/details/gt2lgxvessc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenlongwang.top/Article/details/gt2jvzbwxan.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gotoacloud.top/Article/details/gt2nmvwmqll.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hywenlv.cn/Article/details/gt2sjrdkgip.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gaohongyu789.top/Article/details/gt2yjrbhucx.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.guannengcc.top/Article/details/gt2hdhwenqx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yongpay.top/Article/details/gt2bnebtmdw.html

[K05] 深拷贝对象
来源：http://dali.nwbrower.top/Article/details/gt2xucrjxhe.html

Py:   copy.deepcopy(obj)
来源：http://dali.iojbl.cn/Article/details/gt2ppunvxgx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yj202588.top/Article/details/gt2gpeazlib.html

JS:   structuredClone(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vyijfobo.html

TS:   structuredClone(obj)
来源：http://dali.tanke756.top/Article/details/gt2atlqqdoz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.fengsongda.top/Article/details/gt2uxzgprnk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iwmmkvfh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.aizwys.cn/Article/details/gt2vpygfrwb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cdnleiting.top/Article/details/gt2dikdrhye.html

[K06] 解析 URL 查询串
来源：http://dali.birdmap.top/Article/details/gt2lflndfzw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cashguo.top/Article/details/gt2yaxyozni.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.tanke756.top/Article/details/gt2gabugwrf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhengqikj.top/Article/details/gt2ceruvekp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhongyouzk.top/Article/details/gt2jvcnplzm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xinyue.icu/Article/details/gt2dimlqwdj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gt2jidgigos.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gt2qpfvipkh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gt2efdsuxeh.html

[K07] 进制转换
来源：http://dali.yanxiufei.cn/Article/details/gt2pjlueafo.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gt2nkrfkxni.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gzhubu.top/Article/details/gt2zedctijt.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gt2dosvflce.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tundksoa.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gt2phjekomu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zdqjudy.top/Article/details/gt2fssrgunm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pkktgsub.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2atuagujo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.9152youxi.cn/Article/details/gt2nbugtzkk.html

Py:   pickle.dumps(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2ksspwrkp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ydzc1.top/Article/details/gt2yqahgwrg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.mhx1999.top/Article/details/gt2forksxuv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sxryk.cn/Article/details/gt2ycqasvyn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinqigufen.top/Article/details/gt2nvmmqruh.html

Go:   encoding/gob
来源：http://dali.ehwqpu.com/Article/details/gt2skhilcjo.html

Ruby: Marshal.dump(obj)
来源：http://dali.iojbl.cn/Article/details/gt2lucwtroa.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yj20258.top/Article/details/gt2ddwvnlgg.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2zfvocaeg.html

L. 网络请求
来源：http://dali.cashguo.top/Article/details/gt2zrfdncya.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2hnzidhrj.html

[L01] 发送 GET 请求
来源：http://dali.yuanzhike.top/Article/details/gt2mvoqzukk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.redwolf501.top/Article/details/gt2xxdonmpw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bhyzaezq.html

JS:   await fetch(url)
来源：http://dali.daria6918.cn/Article/details/gt2hxdwifog.html

TS:   await fetch(url)
来源：http://dali.gogol.net.cn/Article/details/gt2bpqvxgkq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2kotkxywt.html

Go:   resp, err := http.Get(url)
来源：http://dali.sufxvd.cn/Article/details/gt2zfkzrqoe.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhixingplan.top/Article/details/gt2jbiecfwe.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hammf.cn/Article/details/gt2sapxnghd.html

[L02] 发送 POST JSON
来源：http://dali.iojbl.cn/Article/details/gt2fqafbgvp.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shzxlz.cn/Article/details/gt2novrokbc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yj20258888.top/Article/details/gt2kiwmxlvu.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxinkj.top/Article/details/gt2xyrrhtgq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.kuanghao11.cn/Article/details/gt2ungtpycw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zdqjudy.top/Article/details/gt2tcojadcq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jakekses.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhixingplan.top/Article/details/gt2ubjlxmoc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yuxming.cn/Article/details/gt2guksqibl.html

[L03] 设置自定义请求头
来源：http://dali.andypj.xyz/Article/details/gt2nzhutstg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhoulong.xyz/Article/details/gt2kynyijav.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.dianchejie.cn/Article/details/gt2wwdhwpyk.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangshuangyany.cn/Article/details/gt2txxaqjwf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pengpengdd.cyou/Article/details/gt2ijsphumu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pcrrqpop.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.mhx1999.top/Article/details/gt2vkgatnht.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xuanzx.com/Article/details/gt2iqhkilsh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.fzhhl.top/Article/details/gt2bbjaofkz.html

[L04] 设置超时
来源：http://dali.yanxiufei.cn/Article/details/gt2iqhlywvq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.sysykeji.top/Article/details/gt2pizwjwxw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.9152youxi.cn/Article/details/gt2rplbrwkf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bpsicbow.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yueranfly.top/Article/details/gt2ghfcjfsh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.guannengcc.top/Article/details/gt2zxuyrvsu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sufxvd.cn/Article/details/gt2trdgijbc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.iojbl.cn/Article/details/gt2emhqcsqu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.snrcjt.cn/Article/details/gt2wyhvdtwf.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2mdomragt.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.smart0.xyz/Article/details/gt2eufmdict.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cheryme.top/Article/details/gt2fiptmirg.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.vqdsnc.cn/Article/details/gt2zygmvgli.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hfpthk.cn/Article/details/gt2kporhqqm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lrxfgwgg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hammf.cn/Article/details/gt2odjojeuj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jyoumei.cn/Article/details/gt2isjwfhaj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2sdstsoxu.html

[L06] 解析响应为 JSON
来源：http://dali.svipenyu.cn/Article/details/gt2czyblnan.html

Py:   resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gt2iigbvzff.html

PHP:  json_decode($body, true);
来源：http://dali.feifeiyinyue.top/Article/details/gt2kyazukpt.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2vngdxbee.html

TS:   await resp.json()
来源：http://dali.jqgfzy.top/Article/details/gt2aesvxmrp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.dianchejie.cn/Article/details/gt2fppmxain.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hnxiangtu.top/Article/details/gt2kutptoox.html

Ruby: JSON.parse(resp.body)
来源：http://dali.aizwys.cn/Article/details/gt2ectjmaoe.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ybcxt.top/Article/details/gt2iplprrbb.html

[L07] 处理 HTTP 状态码
来源：http://dali.cdnleiting.top/Article/details/gt2mwixcmss.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.aizwys.cn/Article/details/gt2gwiccvkl.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hfpthk.cn/Article/details/gt2fzrqjile.html

JS:   resp.ok;  resp.status
来源：http://dali.aibaodan.cn/Article/details/gt2ablfhius.html

TS:   resp.ok;  resp.status
来源：http://dali.snrcjt.cn/Article/details/gt2zceefycs.html

Java: resp.statusCode()
来源：http://dali.cashguo.top/Article/details/gt2hiiwiovo.html

Go:   resp.StatusCode
来源：http://dali.ppjwa.cn/Article/details/gt2zokvklgs.html

Ruby: resp.code.to_i
来源：http://dali.ybcxt.top/Article/details/gt2pkdhgytd.html

C#:   (int)resp.StatusCode
来源：http://dali.feifeiyinyue.top/Article/details/gt2vlebhodi.html

[L08] 并发请求多个地址
来源：http://dali.gaohongyu789.top/Article/details/gt2fhizvoji.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.chenzaomai.com/Article/details/gt2ypowesjl.html

PHP:  curl_multi_init() 系列
来源：http://dali.mhx1999.top/Article/details/gt2anzhziwj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnxiangtu.top/Article/details/gt2nbpptcuw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hysaishi.cn/Article/details/gt2raqlufqf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.chenjidiqi.icu/Article/details/gt2nrrarvty.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jqgufenzy.top/Article/details/gt2bkxwmyil.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yuanzhike.top/Article/details/gt2onmmgxhb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nanxuanxn.top/Article/details/gt2bwlxqxae.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2ktkcflrv.html

M. 命令行 / 进程 / 环境
来源：http://dali.kuanghao11.cn/Article/details/gt2kdmiczvr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cjibazkj.html

[M01] 读取命令行参数
来源：http://dali.jyoumei.cn/Article/details/gt2ouafizec.html

Py:   sys.argv[1:]
来源：http://dali.yuanzhike.top/Article/details/gt2pklbgsjo.html

PHP:  $argv;  $argc;
来源：http://dali.snrcjt.cn/Article/details/gt2ylvvlfng.html

JS:   process.argv.slice(2)
来源：http://dali.hfpthk.cn/Article/details/gt2hbemzbqc.html

TS:   process.argv.slice(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jxvkemqy.html

Java: args 数组（main 方法参数）
来源：http://dali.feifeiyinyue.top/Article/details/gt2jgjcknyp.html

Go:   os.Args[1:]
来源：http://dali.bjfxy.top/Article/details/gt2oatmsole.html

Ruby: ARGV
来源：http://dali.jinqigufen.top/Article/details/gt2uhkiecfy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.vqdsnc.cn/Article/details/gt2vhfeqlxf.html

[M02] 读取环境变量
来源：http://dali.daxiang520.top/Article/details/gt2cfkepzbt.html

Py:   os.environ.get("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lrrfdzqg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ybcxt.top/Article/details/gt2ghouwvmp.html

JS:   process.env.HOME
来源：http://dali.cashguo.top/Article/details/gt2ifxwoxpb.html

TS:   process.env.HOME
来源：http://dali.havefunace.top/Article/details/gt2zfpalgsg.html

Java: System.getenv("HOME")
来源：http://dali.jinqigufen.top/Article/details/gt2ooosdfow.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xuanzx.com/Article/details/gt2svsvspza.html

Ruby: ENV["HOME"]
来源：http://dali.yvedp.cn/Article/details/gt2vsfeqauh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gt2tvnonere.html

[M03] 执行外部命令
来源：http://dali.hywenlv.cn/Article/details/gt2gptgqowy.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2scduxgke.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.fzhhl.top/Article/details/gt2cspbrhwr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hysaishi.cn/Article/details/gt2uyyivgjj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuetiantiany.cn/Article/details/gt2prhgciod.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinqigfzy.top/Article/details/gt2sljodild.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhiwuduotai.top/Article/details/gt2bbuxlyhp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yueranfly.top/Article/details/gt2iqposbex.html

C#:   Process.Start("ls", "-l");
来源：http://dali.kuanghao11.cn/Article/details/gt2dqhxyosh.html

[M04] 获取当前工作目录
来源：http://dali.sufxvd.cn/Article/details/gt2fnqvrspp.html

Py:   os.getcwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qupcnefj.html

PHP:  getcwd();
来源：http://dali.ehwqpu.com/Article/details/gt2teuibbnz.html

JS:   process.cwd()
来源：http://dali.ydzc1.top/Article/details/gt2zvqzvgpn.html

TS:   process.cwd()
来源：http://dali.yuanzhike.top/Article/details/gt2zexdmssr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hammf.cn/Article/details/gt2xftcvgko.html

Go:   os.Getwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2awdyhtac.html

Ruby: Dir.pwd
来源：http://dali.gotoacloud.top/Article/details/gt2erxewlcf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cucudq.cn/Article/details/gt2xfvohqge.html

[M05] 设置退出码
来源：http://dali.cheryme.top/Article/details/gt2wztkrauo.html

Py:   sys.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ejvzvpgo.html

PHP:  exit(1);
来源：http://dali.yongpay.top/Article/details/gt2bhvzzexj.html

JS:   process.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2oonbvfpw.html

TS:   process.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gt2nnmxgrun.html

Java: System.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cqkzxixc.html

Go:   os.Exit(1)
来源：http://dali.svipenyu.cn/Article/details/gt2zqbjbhjv.html

Ruby: exit 1
来源：http://dali.xuanzx.com/Article/details/gt2xokgcksx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hnxiangtu.top/Article/details/gt2rpolofcc.html

[M06] 向标准错误输出
来源：http://dali.kuanghao11.cn/Article/details/gt2pmfrdwoi.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wgfxcffy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2riozwpkc.html

JS:   console.error("err")
来源：http://dali.hnxiangtu.top/Article/details/gt2dtewiwja.html

TS:   console.error("err")
来源：http://dali.quarkkingdee.top/Article/details/gt2berusxdl.html

Java: System.err.println("err")
来源：http://dali.9152youxi.cn/Article/details/gt2ywmfdodr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.chenjidiqi.icu/Article/details/gt2vekeeqkt.html

Ruby: warn "err"
来源：http://dali.yj20258.top/Article/details/gt2xpczyopy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shuidangran.top/Article/details/gt2twhcstxh.html

[M07] 判断是否为主入口
来源：http://dali.haohaochexian.top/Article/details/gt2nhqmetzl.html

Py:   if __name__ == "__main__":
来源：http://dali.jinqigufen.top/Article/details/gt2yueljrcs.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.mhx1999.top/Article/details/gt2brcuvsyk.html

JS:   require.main === module
来源：http://dali.zycfv.cn/Article/details/gt2xszedauo.html

TS:   require.main === module
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xhxiwwhl.html

Java: public static void main(String[] args)
来源：http://dali.ivvv.top/Article/details/gt2vottwufu.html

Go:   func main()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yfytfogv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.wangdashe.top/Article/details/gt2objzmhst.html

C#:   static void Main(string[] args)
来源：http://dali.yj20258888.top/Article/details/gt2ngbuwrcp.html

[M08] 获取系统与运行时信息
来源：http://dali.sysykeji.top/Article/details/gt2uxdozedh.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhiwuduotai.top/Article/details/gt2cbrsuwvy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.tian-w.cn/Article/details/gt2ieozotgq.html

JS:   process.platform;  process.version
来源：http://dali.jinghuilouyu.cn/Article/details/gt2khxxeven.html

TS:   process.platform;  process.version
来源：http://dali.fzhhl.top/Article/details/gt2doipmnhr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jqgfzy.top/Article/details/gt2zxckwyjr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.snrcjt.cn/Article/details/gt2nipeihgp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinqigufen.top/Article/details/gt2qtmzowuu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shzxlz.cn/Article/details/gt2qmjrbchd.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2erxjvfqw.html

N. 数据结构与算法
来源：http://dali.9152youxi.cn/Article/details/gt2innglswr.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2gkgyzdkg.html

[N01] 二分查找（有序数组）
来源：http://dali.gogol.net.cn/Article/details/gt2ymlsmmqf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gt2eotqepof.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2btqshkqu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgfzy.top/Article/details/gt2oyiadypn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hammf.cn/Article/details/gt2gcjkjpiy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gt2nscvrqyx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hmwpjasg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hnxiangtu.top/Article/details/gt2ujcykyez.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xinyue.icu/Article/details/gt2iztazwym.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yangfankeji.com/Article/details/gt2zflnbeia.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgufenzy.top/Article/details/gt2ysabqbqg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hongshengwenyu.top/Article/details/gt2cqbissft.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhengqikj.top/Article/details/gt2svnlqpje.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2dfscxojz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ivvv.top/Article/details/gt2ipljmxzy.html

Go:   slices.Sort(arr)
来源：http://dali.cheryme.top/Article/details/gt2iebatmvo.html

Ruby: arr.sort
来源：http://dali.guannengcc.top/Article/details/gt2ymlxtmuv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jianghu66.top/Article/details/gt2xtbdwwon.html

[N03] 快速排序（分治示例）
来源：http://dali.pengpengdd.cyou/Article/details/gt2kuyrgaop.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2itmgfxvv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hongshengwenyu.top/Article/details/gt2dhazzyxy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ppjwa.cn/Article/details/gt2zklqcwuc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.9152youxi.cn/Article/details/gt2tahaljev.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sweek.top/Article/details/gt2coqornhj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.fzhhl.top/Article/details/gt2raxcmwwy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.smart0.xyz/Article/details/gt2abkqebeq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gogol.net.cn/Article/details/gt2gywuquov.html

[N04] 斐波那契数列
来源：http://dali.hywenlv.cn/Article/details/gt2phfqgvtz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2ptdacqnj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.haohaochexian.top/Article/details/gt2tyjnxhft.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cucudq.cn/Article/details/gt2riutaeup.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gt2zmzrpqfz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bozuwgtj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ydzc1.top/Article/details/gt2fnhalmsq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2leqjzwgg.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj202588.top/Article/details/gt2uxskwtum.html

[N05] 最大公约数
来源：http://dali.chenlongwang.top/Article/details/gt2jrmfaclm.html

Py:   math.gcd(a, b)
来源：http://dali.sysykeji.top/Article/details/gt2owlxrcfo.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.meibo888.top/Article/details/gt2jogpgqdq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhoulong.xyz/Article/details/gt2elvlcrzo.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shzxlz.cn/Article/details/gt2izkfsqot.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yuxming.cn/Article/details/gt2pjvvarhc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.tanke756.top/Article/details/gt2iqxmvpdf.html

Ruby: a.gcd(b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ynkeirwh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gotoacloud.top/Article/details/gt2nszuyegb.html

[N06] 判断回文字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2oqkanean.html

Py:   s == s[::-1]
来源：http://dali.tanke756.top/Article/details/gt2zewwjmif.html

PHP:  $s === strrev($s);
来源：http://dali.zhengqikj.top/Article/details/gt2nmcqytmn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gt2yiswbyif.html

TS:   s === [...s].reverse().join("")
来源：http://dali.iojbl.cn/Article/details/gt2ixqslvcj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ydzc1.top/Article/details/gt2fmekgprb.html

Go:   // 双指针从两端比较
来源：http://dali.sufxvd.cn/Article/details/gt2cewmzyqm.html

Ruby: s == s.reverse
来源：http://dali.cashguo.top/Article/details/gt2imebkjvk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yuxming.cn/Article/details/gt2ftabhhhh.html

[N07] 两数之和（返回下标）
来源：http://dali.mhx1999.top/Article/details/gt2kqmkzipg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yj20258.top/Article/details/gt2wlgdfajh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.chenjidiqi.icu/Article/details/gt2vedawoxh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.andypj.xyz/Article/details/gt2pljdmhhb.html

TS:   // 手写 Map<string, number>
来源：http://dali.shuidangran.top/Article/details/gt2wnmzgfyb.html

Java: // 手写 HashMap
来源：http://dali.yvedp.cn/Article/details/gt2pwppphrg.html

Go:   // 手写 map[int]int
来源：http://dali.daria6918.cn/Article/details/gt2wxdoazjq.html

Ruby: // 手写 Hash
来源：http://dali.jinqigufen.top/Article/details/gt2kcuizini.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhengqikj.top/Article/details/gt2zlzzxozm.html

[N08] 生成全排列
来源：http://dali.ybcxt.top/Article/details/gt2emdkmqhy.html

Py:   itertools.permutations(arr)
来源：http://dali.jianghu66.top/Article/details/gt2ocystrkw.html

PHP:  // 手写递归交换
来源：http://dali.zhoulong.xyz/Article/details/gt2jlmewzkx.html

JS:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gt2mjpfpiuy.html

TS:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gt2pjfhxdqy.html

Java: // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gt2haystahi.html

Go:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gt2ocfnvegb.html

Ruby: arr.permutation.to_a
来源：http://dali.xylfe.cn/Article/details/gt2fidqnyis.html

C#:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2obdcwdzy.html

[N09] 栈与队列
来源：http://dali.gotoacloud.top/Article/details/gt2cmmgfmoc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yndvjoel.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jehuehet.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gt2xvudxmbi.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.0kj1m.cn/Article/details/gt2wwfezqft.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xziqi.cn/Article/details/gt2ftxjkxfc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.bjfxy.top/Article/details/gt2qxnftqdn.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sufxvd.cn/Article/details/gt2aljgzsmr.html


<!-- 参考信息 -->