代发 wailian999

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gtxynbbnnf.html

Go:   json.Marshal(obj)
来源：http://dali.snrcjt.cn/Article/details/gtuheitqxy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.tianlin.xyz/Article/details/gtesytltbq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xziqi.cn/Article/details/gtsztybgyv.html

[K02] JSON 字符串转对象
来源：http://dali.zdqjudy.top/Article/details/gtwpoefpgl.html

Py:   json.loads(s)
来源：http://dali.meibo888.top/Article/details/gtjnoprmgb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbrygzhwa.html

JS:   JSON.parse(s)
来源：http://dali.jyoumei.cn/Article/details/gtqtzseyvt.html

TS:   JSON.parse(s)
来源：http://dali.tanke756.top/Article/details/gtqzalhdwk.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hammf.cn/Article/details/gtjedcjxio.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhengqikj.top/Article/details/gtnrrvvyru.html

Ruby: JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gthbvoypeo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtplsvwuhd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jiagoushi.top/Article/details/gtalmsmzpa.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cashguo.top/Article/details/gtpdjfjhfa.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yvedp.cn/Article/details/gtjnugpgin.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzmioqvwm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zdqjudy.top/Article/details/gtqxivtwvg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtnuyklztv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.aizwys.cn/Article/details/gteaylvbfe.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jianghu66.top/Article/details/gtgkigszha.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hysaishi.cn/Article/details/gtposbcdza.html

[K04] 读取 JSON 文件
来源：http://dali.jiagoushi.top/Article/details/gtpyjsdgqf.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ppjwa.cn/Article/details/gtbcmoognb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sysykeji.top/Article/details/gtujyhsdnj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hammf.cn/Article/details/gtefimpwfj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangshuangyany.cn/Article/details/gtrqofkxhx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yonumen.top/Article/details/gtbvhhvkvg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hywenlv.cn/Article/details/gtrndxpdmu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.haohaochexian.top/Article/details/gthojbvpth.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdiznejvz.html

[K05] 深拷贝对象
来源：http://dali.jyoumei.cn/Article/details/gtiwmuvwlp.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtddqxhjxb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jyoumei.cn/Article/details/gtihnekgeq.html

JS:   structuredClone(obj)
来源：http://dali.jqgfzy.top/Article/details/gtaptlzxgs.html

TS:   structuredClone(obj)
来源：http://dali.yj20258.top/Article/details/gtqfvqyxmj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.meibo888.top/Article/details/gtghxcechd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hongshengwenyu.top/Article/details/gtnclkcumc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.feifeiyinyue.top/Article/details/gtzkloukji.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.birdmap.top/Article/details/gtukstizql.html

[K06] 解析 URL 查询串
来源：http://dali.nanxinkj.top/Article/details/gttidnwrmo.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.havefunace.top/Article/details/gtgftgxxwx.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.wangdashe.top/Article/details/gtanhultbi.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuanzhike.top/Article/details/gtqzdgwevs.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnqzz.top/Article/details/gtozuikjth.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.fzhhl.top/Article/details/gtyljqrlmz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yvedp.cn/Article/details/gteixdaeqh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.pycfn.com/Article/details/gtccykwnww.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jlsjyb.cn/Article/details/gteombcckm.html

[K07] 进制转换
来源：http://dali.0kj1m.cn/Article/details/gtftrcvdyk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtboiccxbz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.c1oappe.top/Article/details/gtrytgmxwm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gtxavijgik.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtykauzdho.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gtjlmzxzvr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.wangdashe.top/Article/details/gtnlivawul.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.fzhhl.top/Article/details/gttzkfezqf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gtysmabjcy.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yj202588.top/Article/details/gtuovuiuye.html

Py:   pickle.dumps(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtsquxapsh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhengqikj.top/Article/details/gtrbjmywud.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cqqwz.cn/Article/details/gtkqfhpkwe.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhoulong.xyz/Article/details/gtwzzoxnth.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinghuilouyu.cn/Article/details/gtunehgzns.html

Go:   encoding/gob
来源：http://dali.shzxlz.cn/Article/details/gtgqomtetj.html

Ruby: Marshal.dump(obj)
来源：http://dali.fengsongda.top/Article/details/gtlqycgzjq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.havefunace.top/Article/details/gtdoubtgid.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtcbvminrn.html

L. 网络请求
来源：http://dali.9152youxi.cn/Article/details/gtjjvhivmh.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtvnfhketj.html

[L01] 发送 GET 请求
来源：http://dali.tianlin.xyz/Article/details/gtkgjulafo.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xziqi.cn/Article/details/gtyiyvobfn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfpqlfeyp.html

JS:   await fetch(url)
来源：http://dali.yj20258888.top/Article/details/gtmlunfrol.html

TS:   await fetch(url)
来源：http://dali.zhiwuduotai.top/Article/details/gtheonhqli.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinghuilouyu.cn/Article/details/gtownyvlfs.html

Go:   resp, err := http.Get(url)
来源：http://dali.yuanzhike.top/Article/details/gtzpnjbpdk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shangyingyoupin.top/Article/details/gtyasxkkhg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.pycfn.com/Article/details/gtvmemrakv.html

[L02] 发送 POST JSON
来源：http://dali.cdnleiting.top/Article/details/gtwnynpqok.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.iojbl.cn/Article/details/gtjdwmmlea.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yuxming.cn/Article/details/gtqbfipwrm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhengqikj.top/Article/details/gtbcwnnqsq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenzaomai.com/Article/details/gtavefzdpn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jyoumei.cn/Article/details/gtfpoikvdn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtblgdfbft.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.daxiang520.top/Article/details/gtepkxhhwu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jiagoushi.top/Article/details/gtshgqrhmt.html

[L03] 设置自定义请求头
来源：http://dali.tianlin.xyz/Article/details/gtqkedkltn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhoulong.xyz/Article/details/gtlqlzcgmm.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shuidangran.top/Article/details/gtbwcpnwbn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zycfv.cn/Article/details/gthhplpqhk.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangdashe.top/Article/details/gtlrmgvmnj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.smart0.xyz/Article/details/gtsajmtfnq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtagfzamhm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cqqwz.cn/Article/details/gtqipubvdg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sysykeji.top/Article/details/gtveclmilf.html

[L04] 设置超时
来源：http://dali.dianchejie.cn/Article/details/gtghugvpyb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsvvezika.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.fzhhl.top/Article/details/gtnaoqtljc.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gotoacloud.top/Article/details/gtqhomarip.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.havefunace.top/Article/details/gtnbxoqrtu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.316326.xyz/Article/details/gtlywqyslu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cqqwz.cn/Article/details/gtixikxwat.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yuanzhike.top/Article/details/gtcjtmgnqq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhiwuduotai.top/Article/details/gtmmumwaay.html

[L05] 上传文件（multipart）
来源：http://dali.jinghuilouyu.cn/Article/details/gtajpalzkp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cashguo.top/Article/details/gtpwmpqbsg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shuidangran.top/Article/details/gtwocdogqv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jiagoushi.top/Article/details/gtoyoyvain.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.andypj.xyz/Article/details/gtnhcufvgi.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yj20258.top/Article/details/gtcryrimez.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zycfv.cn/Article/details/gtaegvajrt.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jyoumei.cn/Article/details/gtrgcyqrvu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xziqi.cn/Article/details/gtwinjvwtg.html

[L06] 解析响应为 JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgomdxbmc.html

Py:   resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gtsvpuhwns.html

PHP:  json_decode($body, true);
来源：http://dali.jqgfzy.top/Article/details/gttctckkbz.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gtkawjkkfc.html

TS:   await resp.json()
来源：http://dali.tian-w.cn/Article/details/gttbndsbmu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj20258888.top/Article/details/gtictyyxvc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hongshengwenyu.top/Article/details/gtjyqwyyuc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xuetiantiany.cn/Article/details/gtlqonnodw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sufxvd.cn/Article/details/gthlfclgzk.html

[L07] 处理 HTTP 状态码
来源：http://dali.dianchejie.cn/Article/details/gtsaafozig.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhengqikj.top/Article/details/gtfokmidsp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sweek.top/Article/details/gtysxyeehd.html

JS:   resp.ok;  resp.status
来源：http://dali.gaohongyu789.top/Article/details/gtuapcqwbz.html

TS:   resp.ok;  resp.status
来源：http://dali.pengpengdd.cyou/Article/details/gtbavanqyd.html

Java: resp.statusCode()
来源：http://dali.jinqigfzy.top/Article/details/gtmnpjcado.html

Go:   resp.StatusCode
来源：http://dali.yongpay.top/Article/details/gtgmcvjdxi.html

Ruby: resp.code.to_i
来源：http://dali.hfpthk.cn/Article/details/gtgpsbikzo.html

C#:   (int)resp.StatusCode
来源：http://dali.yuxming.cn/Article/details/gtiwchhvjy.html

[L08] 并发请求多个地址
来源：http://dali.jinqigfzy.top/Article/details/gtseviojyi.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.daria6918.cn/Article/details/gtaswixxaq.html

PHP:  curl_multi_init() 系列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvzkavsca.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gtegjqkrtj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shuidangran.top/Article/details/gttgxbrckq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinghuilouyu.cn/Article/details/gtwavgluku.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jqgufenzy.top/Article/details/gtoobcrhqr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhongyouzk.top/Article/details/gtnajvlzoj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.0kj1m.cn/Article/details/gtnwoizdai.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtotapgumk.html

M. 命令行 / 进程 / 环境
来源：http://dali.jlsjyb.cn/Article/details/gtoatcnnux.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtvnlfvwdm.html

[M01] 读取命令行参数
来源：http://dali.zhoulong.xyz/Article/details/gtniyvvnjw.html

Py:   sys.argv[1:]
来源：http://dali.andypj.xyz/Article/details/gteehfuehy.html

PHP:  $argv;  $argc;
来源：http://dali.c1oappe.top/Article/details/gtiygscoop.html

JS:   process.argv.slice(2)
来源：http://dali.aizwys.cn/Article/details/gtjtpqkokp.html

TS:   process.argv.slice(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyljrkwoj.html

Java: args 数组（main 方法参数）
来源：http://dali.cdnleiting.top/Article/details/gtqgcrzgrr.html

Go:   os.Args[1:]
来源：http://dali.havefunace.top/Article/details/gtnxvpaaum.html

Ruby: ARGV
来源：http://dali.yj20258.top/Article/details/gttokjnzev.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shuidangran.top/Article/details/gtmuabdbzr.html

[M02] 读取环境变量
来源：http://dali.wangdashe.top/Article/details/gtcgkmegec.html

Py:   os.environ.get("HOME")
来源：http://dali.yj20258.top/Article/details/gtgextykjb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhoulong.xyz/Article/details/gtxmxzegvt.html

JS:   process.env.HOME
来源：http://dali.hnxiangtu.top/Article/details/gttvawxgbj.html

TS:   process.env.HOME
来源：http://dali.gogol.net.cn/Article/details/gtsvkkqpva.html

Java: System.getenv("HOME")
来源：http://dali.yj20258888.top/Article/details/gtdjkcpkll.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.mhx1999.top/Article/details/gtbtnvjvhn.html

Ruby: ENV["HOME"]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttdofsfvx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gtnvrtpsqu.html

[M03] 执行外部命令
来源：http://dali.nanxuanxn.top/Article/details/gtvfclhkbj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zdqjudy.top/Article/details/gtuspvmhjw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhixingplan.top/Article/details/gthdhsswdc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258.top/Article/details/gtjtbxeolf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.guowangkeji.top/Article/details/gtckippusl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.tanke756.top/Article/details/gtvqnkuord.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.pycfn.com/Article/details/gtbvdapqwo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.bjfxy.top/Article/details/gtckzdtbuj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.chenjidiqi.icu/Article/details/gtrjjpkfbf.html

[M04] 获取当前工作目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrvkhufiy.html

Py:   os.getcwd()
来源：http://dali.guowangkeji.top/Article/details/gtbekukoaj.html

PHP:  getcwd();
来源：http://dali.yj20258888.top/Article/details/gtaoigdzqo.html

JS:   process.cwd()
来源：http://dali.yangfankeji.com/Article/details/gtatwvftan.html

TS:   process.cwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtubdtodvs.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yvedp.cn/Article/details/gtckyzurjf.html

Go:   os.Getwd()
来源：http://dali.tanke756.top/Article/details/gtmzocnece.html

Ruby: Dir.pwd
来源：http://dali.nwbrower.top/Article/details/gtxzxtvgjf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.9152youxi.cn/Article/details/gtveqtdpxp.html

[M05] 设置退出码
来源：http://dali.aibaodan.cn/Article/details/gtxbwavvkj.html

Py:   sys.exit(1)
来源：http://dali.cucudq.cn/Article/details/gtyahexkef.html

PHP:  exit(1);
来源：http://dali.yvedp.cn/Article/details/gtlsljeawu.html

JS:   process.exit(1)
来源：http://dali.cheryme.top/Article/details/gtalarsdgz.html

TS:   process.exit(1)
来源：http://dali.redwolf501.top/Article/details/gtbczsoohk.html

Java: System.exit(1)
来源：http://dali.fengsongda.top/Article/details/gtyahvuxyw.html

Go:   os.Exit(1)
来源：http://dali.mhx1999.top/Article/details/gtnyqujupd.html

Ruby: exit 1
来源：http://dali.hfpthk.cn/Article/details/gtrkfngnwh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cheryme.top/Article/details/gthwzfunuz.html

[M06] 向标准错误输出
来源：http://dali.gzhubu.top/Article/details/gtlxmyugbm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gogol.net.cn/Article/details/gtkvoykzku.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jqgfzy.top/Article/details/gtmrpsnkfb.html

JS:   console.error("err")
来源：http://dali.dashuyun.cn/Article/details/gtcpooymaf.html

TS:   console.error("err")
来源：http://dali.chenjidiqi.icu/Article/details/gttzrnpfif.html

Java: System.err.println("err")
来源：http://dali.yangfankeji.com/Article/details/gtokjbdmjq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj20258888.top/Article/details/gtaouisydi.html

Ruby: warn "err"
来源：http://dali.chenlongwang.top/Article/details/gtdrkcnlvy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tanke756.top/Article/details/gtolgutfir.html

[M07] 判断是否为主入口
来源：http://dali.vqdsnc.cn/Article/details/gtmejejxmj.html

Py:   if __name__ == "__main__":
来源：http://dali.chenjidiqi.icu/Article/details/gtvmglsiar.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.daxiang520.top/Article/details/gtkihxkrug.html

JS:   require.main === module
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsacolyzt.html

TS:   require.main === module
来源：http://dali.zhongyouzk.top/Article/details/gtryrzqcpc.html

Java: public static void main(String[] args)
来源：http://dali.jinqigufen.top/Article/details/gtozevnbjw.html

Go:   func main()
来源：http://dali.fengsongda.top/Article/details/gtvclyhocb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.guowangkeji.top/Article/details/gtiombygwg.html

C#:   static void Main(string[] args)
来源：http://dali.nanxinkj.top/Article/details/gtgflxndzb.html

[M08] 获取系统与运行时信息
来源：http://dali.chenjidiqi.icu/Article/details/gtoptklezi.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jqgufenzy.top/Article/details/gtzognkucq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.birdmap.top/Article/details/gtawqrrqib.html

JS:   process.platform;  process.version
来源：http://dali.gzhubu.top/Article/details/gtgdhdxioy.html

TS:   process.platform;  process.version
来源：http://dali.cqqwz.cn/Article/details/gtboufjxaj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnxiangtu.top/Article/details/gtzvghwrie.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zdqjudy.top/Article/details/gtycglifju.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhaomingkeji.xyz/Article/details/gtovffoohm.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.wangdashe.top/Article/details/gtlrquygcj.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtiuebpxyn.html

N. 数据结构与算法
来源：http://dali.xuanzx.com/Article/details/gtnxjgpxaw.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtuxifmzse.html

[N01] 二分查找（有序数组）
来源：http://dali.chenjidiqi.icu/Article/details/gtdfqxwmzk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtcratpmaz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.pycfn.com/Article/details/gtiitwnkev.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258888.top/Article/details/gtlxmfretb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shangyingyoupin.top/Article/details/gtkqjetudf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtlwbcuoxj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtmfttmjzp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.tianlin.xyz/Article/details/gtkzenmbzq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hnqzz.top/Article/details/gtplxjdfyl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sweek.top/Article/details/gtwrvdkdua.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cashguo.top/Article/details/gtbivsdqau.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cdnleiting.top/Article/details/gtzhflnhez.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.snrcjt.cn/Article/details/gtbcxkgbeg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenjidiqi.icu/Article/details/gtlhpqgcrk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hfpthk.cn/Article/details/gthhahtkue.html

Go:   slices.Sort(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtyfuepoty.html

Ruby: arr.sort
来源：http://dali.guowangkeji.top/Article/details/gtfyzjhrud.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.wangdashe.top/Article/details/gtaoxxtvkg.html

[N03] 快速排序（分治示例）
来源：http://dali.kuanghao11.cn/Article/details/gtvdgkgyxf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.daria6918.cn/Article/details/gtuetaqmum.html

PHP:  // 递归实现，或用 usort
来源：http://dali.c1oappe.top/Article/details/gtxjrrgfdx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xziqi.cn/Article/details/gtzykbtrlu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cqqwz.cn/Article/details/gtencawgxl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.andypj.xyz/Article/details/gtlunjcqks.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.kuanghao11.cn/Article/details/gtxurjfzlu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cashguo.top/Article/details/gtihxbffyo.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sxryk.cn/Article/details/gtcpbseuiq.html

[N04] 斐波那契数列
来源：http://dali.gaohongyu789.top/Article/details/gtxoohtjcp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbtzmhmdx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gteisesskh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnqzz.top/Article/details/gtwpcghhxt.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gtrcldflal.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gogol.net.cn/Article/details/gtzbbfuwyf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zycfv.cn/Article/details/gtxmqfcgaf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hfpthk.cn/Article/details/gtcubdzyhc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhixingplan.top/Article/details/gtnjvnlrnp.html

[N05] 最大公约数
来源：http://dali.meibo888.top/Article/details/gtrkcsjklf.html

Py:   math.gcd(a, b)
来源：http://dali.fzhhl.top/Article/details/gtndfrynos.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.iojbl.cn/Article/details/gtryihwfvz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cheryme.top/Article/details/gtydoemaug.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tanke756.top/Article/details/gtronesxzs.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.meibo888.top/Article/details/gtuqbjdhsd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.guowangkeji.top/Article/details/gthzfjzwkf.html

Ruby: a.gcd(b)
来源：http://dali.shuidangran.top/Article/details/gtubfvkvdv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzlrbunmf.html

[N06] 判断回文字符串
来源：http://dali.zycfv.cn/Article/details/gtugsztjgn.html

Py:   s == s[::-1]
来源：http://dali.0kj1m.cn/Article/details/gtzfuxnecr.html

PHP:  $s === strrev($s);
来源：http://dali.yvedp.cn/Article/details/gtugrdztnf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gtcjpznnid.html

TS:   s === [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gtryrsykfk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.chenjidiqi.icu/Article/details/gtchagrpmc.html

Go:   // 双指针从两端比较
来源：http://dali.hfpthk.cn/Article/details/gtyjhjhpcg.html

Ruby: s == s.reverse
来源：http://dali.jinqigfzy.top/Article/details/gtxogprxcg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gzhubu.top/Article/details/gtcibujjhj.html

[N07] 两数之和（返回下标）
来源：http://dali.jinqigufen.top/Article/details/gtsgyjlbrf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.9152youxi.cn/Article/details/gtcujkxgxi.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xuanzx.com/Article/details/gtcogiuhkr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.feifeiyinyue.top/Article/details/gtvujkcgza.html

TS:   // 手写 Map<string, number>
来源：http://dali.316326.xyz/Article/details/gtkmifgyiw.html

Java: // 手写 HashMap
来源：http://dali.aibaodan.cn/Article/details/gtsfsmxtgl.html

Go:   // 手写 map[int]int
来源：http://dali.hysaishi.cn/Article/details/gtxnvkywvu.html

Ruby: // 手写 Hash
来源：http://dali.quarkkingdee.top/Article/details/gtrrluuook.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xinyue.icu/Article/details/gtfjoczvdv.html

[N08] 生成全排列
来源：http://dali.jinghuilouyu.cn/Article/details/gtongpttga.html

Py:   itertools.permutations(arr)
来源：http://dali.yuxming.cn/Article/details/gtbqfbfkgs.html

PHP:  // 手写递归交换
来源：http://dali.dashuyun.cn/Article/details/gtcjbnxnem.html

JS:   // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gtkxndbgbf.html

TS:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtjlvqunvk.html

Java: // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gteemjnhia.html

Go:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gtmpghaoqr.html

Ruby: arr.permutation.to_a
来源：http://dali.hfpthk.cn/Article/details/gtykowjztj.html

C#:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gtbmygawzh.html

[N09] 栈与队列
来源：http://dali.haohaochexian.top/Article/details/gtolmjslff.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhoulong.xyz/Article/details/gtsazipmvi.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cashguo.top/Article/details/gttlsdxate.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cucudq.cn/Article/details/gtlrguntfy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.316326.xyz/Article/details/gtmlswfrew.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shangyingyoupin.top/Article/details/gtawzpetuh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cqqwz.cn/Article/details/gtwjtgmzxg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.tian-w.cn/Article/details/gtlodaoqii.html


<!-- 参考信息 -->