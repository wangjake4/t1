代发 wailian999

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zdqjudy.top/Article/details/gt2huaelntq.html

Go:   json.Marshal(obj)
来源：http://dali.yvedp.cn/Article/details/gt2vjtveeyb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.aizwys.cn/Article/details/gt2tzrhcuun.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2gofxchgr.html

[K02] JSON 字符串转对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hpvthbhx.html

Py:   json.loads(s)
来源：http://dali.jyoumei.cn/Article/details/gt2znkbwahp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.9152youxi.cn/Article/details/gt2turiiarn.html

JS:   JSON.parse(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fillpahd.html

TS:   JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gt2zzktvavi.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxtvubu.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhoulong.xyz/Article/details/gt2fnzyhvde.html

Ruby: JSON.parse(s)
来源：http://dali.smart0.xyz/Article/details/gt2wtvfgmvd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hnqzz.top/Article/details/gt2hgepgpkx.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinqigufen.top/Article/details/gt2qxwhkans.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cqqwz.cn/Article/details/gt2jxorgydd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xziqi.cn/Article/details/gt2qfpqojfp.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.guannengcc.top/Article/details/gt2kqtbtfxy.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gogol.net.cn/Article/details/gt2sjmzdukd.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jianghu66.top/Article/details/gt2eizjcziv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gogol.net.cn/Article/details/gt2psohjugp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tanke756.top/Article/details/gt2ejfooulp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yuxming.cn/Article/details/gt2dvvoppli.html

[K04] 读取 JSON 文件
来源：http://dali.nanxinkj.top/Article/details/gt2vsjicomh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yongpay.top/Article/details/gt2lphurftl.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yuanzhike.top/Article/details/gt2qnqxnybh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuanzhike.top/Article/details/gt2lbiypfzn.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnqzz.top/Article/details/gt2qzsvmjvw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.316326.xyz/Article/details/gt2jbepjuxs.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yueranfly.top/Article/details/gt2dnqhshaa.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.tianlin.xyz/Article/details/gt2yauslrxr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hammf.cn/Article/details/gt2uvdejgbl.html

[K05] 深拷贝对象
来源：http://dali.jiagoushi.top/Article/details/gt2gowkxdng.html

Py:   copy.deepcopy(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2tmyigist.html

PHP:  unserialize(serialize($obj));
来源：http://dali.svipenyu.cn/Article/details/gt2mprjgvqv.html

JS:   structuredClone(obj)
来源：http://dali.sweek.top/Article/details/gt2wkcvqwnu.html

TS:   structuredClone(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2jhuidsil.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jyoumei.cn/Article/details/gt2wbztccyu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.snrcjt.cn/Article/details/gt2ocxmvbyu.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sxryk.cn/Article/details/gt2gugtqvzp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.tanke756.top/Article/details/gt2pbukzqut.html

[K06] 解析 URL 查询串
来源：http://dali.yj202588.top/Article/details/gt2eeegfdeg.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yj20258.top/Article/details/gt2ehzxdhdm.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj20258.top/Article/details/gt2btkiswiv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hongshengwenyu.top/Article/details/gt2bwtenejk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jlsjyb.cn/Article/details/gt2mhlwqrei.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jiagoushi.top/Article/details/gt2nnhjponp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gt2kgmqpfov.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gt2qtethmod.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gt2nmbmbxhx.html

[K07] 进制转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hbnqwinp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gt2epcspwfs.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xuetiantiany.cn/Article/details/gt2kdmrwyqa.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gt2qaweunvn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gt2kebgdnft.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zxkmoeuc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jiagoushi.top/Article/details/gt2zaxgowtu.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yj202588.top/Article/details/gt2bqvbhfbn.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gt2gnuthoqp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sweek.top/Article/details/gt2gkqczvlu.html

Py:   pickle.dumps(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2ldfharnc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jianghu66.top/Article/details/gt2wdlglxak.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yongpay.top/Article/details/gt2ujoecxpl.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hfpthk.cn/Article/details/gt2gdhvdwto.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.iojbl.cn/Article/details/gt2qfogetdd.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvaudlp.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2soprdtsg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kcgyemfv.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2unmtpmbn.html

L. 网络请求
来源：http://dali.0kj1m.cn/Article/details/gt2wsbdcvuf.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2bpzvweat.html

[L01] 发送 GET 请求
来源：http://dali.xuetiantiany.cn/Article/details/gt2luejjckd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hnxiangtu.top/Article/details/gt2sveeicqy.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zycfv.cn/Article/details/gt2oyxkbxcw.html

JS:   await fetch(url)
来源：http://dali.quarkkingdee.top/Article/details/gt2kgcnuevq.html

TS:   await fetch(url)
来源：http://dali.cucudq.cn/Article/details/gt2jandfiuq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yanxiufei.cn/Article/details/gt2bbshxzbp.html

Go:   resp, err := http.Get(url)
来源：http://dali.yonumen.top/Article/details/gt2ljdgmnld.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.0kj1m.cn/Article/details/gt2itiyyysf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.kuanghao11.cn/Article/details/gt2uynonqng.html

[L02] 发送 POST JSON
来源：http://dali.daria6918.cn/Article/details/gt2zajbxdvu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.quarkkingdee.top/Article/details/gt2pbrtfvho.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.aibaodan.cn/Article/details/gt2hjizrfvp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tian-w.cn/Article/details/gt2lftbzyof.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.feifeiyinyue.top/Article/details/gt2vhjlsqtt.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ppjwa.cn/Article/details/gt2rvslnqkl.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jlsjyb.cn/Article/details/gt2nhmnqwmv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hnqzz.top/Article/details/gt2chfphojg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yonumen.top/Article/details/gt2tvofnbal.html

[L03] 设置自定义请求头
来源：http://dali.sysykeji.top/Article/details/gt2iquvyhvm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.aizwys.cn/Article/details/gt2nopytxtw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gotoacloud.top/Article/details/gt2czdaqhlq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xylfe.cn/Article/details/gt2grbqomqk.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258.top/Article/details/gt2qwhiuunv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xylfe.cn/Article/details/gt2hqygpcmy.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.aizwys.cn/Article/details/gt2bevwzdju.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cashguo.top/Article/details/gt2nfrkznti.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gzhubu.top/Article/details/gt2oxrnsmxd.html

[L04] 设置超时
来源：http://dali.guannengcc.top/Article/details/gt2zbbcjipi.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xinyue.icu/Article/details/gt2zymscwtm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhongyouzk.top/Article/details/gt2qrusvbxy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuanzhike.top/Article/details/gt2aisjdsim.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dianchejie.cn/Article/details/gt2ftpufiaa.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ydzc1.top/Article/details/gt2bjkygobh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xuetiantiany.cn/Article/details/gt2qkkpnbrg.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sufxvd.cn/Article/details/gt2mzmhyubr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hywenlv.cn/Article/details/gt2cqsjjovi.html

[L05] 上传文件（multipart）
来源：http://dali.tanke756.top/Article/details/gt2zxpgjilq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yuanzhike.top/Article/details/gt2qczlyrhu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bcwtcwtl.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.mhx1999.top/Article/details/gt2pzenaxcp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zycfv.cn/Article/details/gt2fvxotrjb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lvgtodrw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jiagoushi.top/Article/details/gt2dyjrliuo.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zdqjudy.top/Article/details/gt2dhicaxvw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nwvwlnab.html

[L06] 解析响应为 JSON
来源：http://dali.wangshuangyany.cn/Article/details/gt2twfzplal.html

Py:   resp.json()
来源：http://dali.yangfankeji.com/Article/details/gt2iaxijgaa.html

PHP:  json_decode($body, true);
来源：http://dali.wangdashe.top/Article/details/gt2wqqhdtie.html

JS:   await resp.json()
来源：http://dali.fengsongda.top/Article/details/gt2xshabipk.html

TS:   await resp.json()
来源：http://dali.jiagoushi.top/Article/details/gt2mpismdys.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jqgfzy.top/Article/details/gt2kkyawunm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.daria6918.cn/Article/details/gt2lfilucwz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.haohaochexian.top/Article/details/gt2rxonxnte.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zdqjudy.top/Article/details/gt2zutjhmld.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhengqikj.top/Article/details/gt2obrdhmgf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.daria6918.cn/Article/details/gt2goiurnbn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xinyue.icu/Article/details/gt2bmdpfldc.html

JS:   resp.ok;  resp.status
来源：http://dali.yj20258.top/Article/details/gt2sqobjmfk.html

TS:   resp.ok;  resp.status
来源：http://dali.xinyue.icu/Article/details/gt2xazvowan.html

Java: resp.statusCode()
来源：http://dali.tanke756.top/Article/details/gt2ezasmeiv.html

Go:   resp.StatusCode
来源：http://dali.mhx1999.top/Article/details/gt2olbsgjwq.html

Ruby: resp.code.to_i
来源：http://dali.pycfn.com/Article/details/gt2frwotxvk.html

C#:   (int)resp.StatusCode
来源：http://dali.sufxvd.cn/Article/details/gt2fiatirtm.html

[L08] 并发请求多个地址
来源：http://dali.xziqi.cn/Article/details/gt2nqccywti.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yanxiufei.cn/Article/details/gt2sqwlgoob.html

PHP:  curl_multi_init() 系列
来源：http://dali.yuxming.cn/Article/details/gt2rgonvhzs.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenzaomai.com/Article/details/gt2pgkmcxkm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shzxlz.cn/Article/details/gt2szfcjojd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.havefunace.top/Article/details/gt2qxmtzjgb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sxryk.cn/Article/details/gt2xtlericy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.nwbrower.top/Article/details/gt2etlgbmhm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.fzhhl.top/Article/details/gt2nianarjy.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2lbnimzja.html

M. 命令行 / 进程 / 环境
来源：http://dali.kuanghao11.cn/Article/details/gt2wcwivmra.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2wqfunxwj.html

[M01] 读取命令行参数
来源：http://dali.9152youxi.cn/Article/details/gt2bjnxmdko.html

Py:   sys.argv[1:]
来源：http://dali.yvedp.cn/Article/details/gt2ghrpttea.html

PHP:  $argv;  $argc;
来源：http://dali.shangyingyoupin.top/Article/details/gt2pixufxsk.html

JS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gt2yneokjpf.html

TS:   process.argv.slice(2)
来源：http://dali.zhengqikj.top/Article/details/gt2hzkgcikp.html

Java: args 数组（main 方法参数）
来源：http://dali.xuanzx.com/Article/details/gt2hesohqsc.html

Go:   os.Args[1:]
来源：http://dali.316326.xyz/Article/details/gt2exwdlepo.html

Ruby: ARGV
来源：http://dali.jqgufenzy.top/Article/details/gt2mbkyfvvs.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ppjwa.cn/Article/details/gt2mjfnpmph.html

[M02] 读取环境变量
来源：http://dali.daxiang520.top/Article/details/gt2uscdggdj.html

Py:   os.environ.get("HOME")
来源：http://dali.nwbrower.top/Article/details/gt2jibuwtax.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sysykeji.top/Article/details/gt2vtrmaiun.html

JS:   process.env.HOME
来源：http://dali.0kj1m.cn/Article/details/gt2abjtwzxr.html

TS:   process.env.HOME
来源：http://dali.guannengcc.top/Article/details/gt2vbmledjj.html

Java: System.getenv("HOME")
来源：http://dali.c1oappe.top/Article/details/gt2jgdspkmf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.guowangkeji.top/Article/details/gt2emxdxofw.html

Ruby: ENV["HOME"]
来源：http://dali.xuanzx.com/Article/details/gt2rqfdveeg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenzaomai.com/Article/details/gt2zhrjshjy.html

[M03] 执行外部命令
来源：http://dali.c1oappe.top/Article/details/gt2gaqqidqx.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.dashuyun.cn/Article/details/gt2ebvlddpx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhongyouzk.top/Article/details/gt2cnohtwip.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenjidiqi.icu/Article/details/gt2kcomnrdp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenzaomai.com/Article/details/gt2xittvcym.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jlsjyb.cn/Article/details/gt2somzgcnz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.daria6918.cn/Article/details/gt2ezvxkeev.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sweek.top/Article/details/gt2cbytiqgq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.redwolf501.top/Article/details/gt2tmqwlkfw.html

[M04] 获取当前工作目录
来源：http://dali.pengpengdd.cyou/Article/details/gt2dfxjsozd.html

Py:   os.getcwd()
来源：http://dali.nanxinkj.top/Article/details/gt2qsoygari.html

PHP:  getcwd();
来源：http://dali.pengpengdd.cyou/Article/details/gt2ymupozbz.html

JS:   process.cwd()
来源：http://dali.tianlin.xyz/Article/details/gt2ozpwxilq.html

TS:   process.cwd()
来源：http://dali.zhongyouzk.top/Article/details/gt2wqspeisz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.tian-w.cn/Article/details/gt2bdgtgnrs.html

Go:   os.Getwd()
来源：http://dali.ehwqpu.com/Article/details/gt2wjiainie.html

Ruby: Dir.pwd
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fnxxeeqa.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.birdmap.top/Article/details/gt2onmerytu.html

[M05] 设置退出码
来源：http://dali.zhiwuduotai.top/Article/details/gt2mcmichvk.html

Py:   sys.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gt2khgabqjw.html

PHP:  exit(1);
来源：http://dali.yueranfly.top/Article/details/gt2ehosuhci.html

JS:   process.exit(1)
来源：http://dali.xuanzx.com/Article/details/gt2fdlpwwoy.html

TS:   process.exit(1)
来源：http://dali.pycfn.com/Article/details/gt2xhuzfkzj.html

Java: System.exit(1)
来源：http://dali.daria6918.cn/Article/details/gt2owvhowfp.html

Go:   os.Exit(1)
来源：http://dali.xylfe.cn/Article/details/gt2tustydxg.html

Ruby: exit 1
来源：http://dali.jianghu66.top/Article/details/gt2pcryxluc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.birdmap.top/Article/details/gt2crgwtqpe.html

[M06] 向标准错误输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ijyksiwx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gaohongyu789.top/Article/details/gt2csexbhbj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.bjfxy.top/Article/details/gt2ieqzjdbd.html

JS:   console.error("err")
来源：http://dali.zycfv.cn/Article/details/gt2ejbkryqj.html

TS:   console.error("err")
来源：http://dali.bjfxy.top/Article/details/gt2lgprocad.html

Java: System.err.println("err")
来源：http://dali.andypj.xyz/Article/details/gt2lvmvcadx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hnxiangtu.top/Article/details/gt2fvalucwl.html

Ruby: warn "err"
来源：http://dali.hysaishi.cn/Article/details/gt2qawtfgqs.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.chenzaomai.com/Article/details/gt2fzcwjcos.html

[M07] 判断是否为主入口
来源：http://dali.xuetiantiany.cn/Article/details/gt2pricbsqk.html

Py:   if __name__ == "__main__":
来源：http://dali.nanxuanxn.top/Article/details/gt2fmmndzmy.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ubjotkiv.html

JS:   require.main === module
来源：http://dali.dashuyun.cn/Article/details/gt2uysragxo.html

TS:   require.main === module
来源：http://dali.gotoacloud.top/Article/details/gt2tupkdjjd.html

Java: public static void main(String[] args)
来源：http://dali.quarkkingdee.top/Article/details/gt2umrewgtg.html

Go:   func main()
来源：http://dali.9152youxi.cn/Article/details/gt2shiitdas.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.smart0.xyz/Article/details/gt2amzbxsea.html

C#:   static void Main(string[] args)
来源：http://dali.9152youxi.cn/Article/details/gt2carvyale.html

[M08] 获取系统与运行时信息
来源：http://dali.vqdsnc.cn/Article/details/gt2nubhzkns.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ksiymfmq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhixingplan.top/Article/details/gt2erymejce.html

JS:   process.platform;  process.version
来源：http://dali.yongpay.top/Article/details/gt2jaarucwd.html

TS:   process.platform;  process.version
来源：http://dali.jqgfzy.top/Article/details/gt2zqciwlva.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rhjghqes.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj20258888.top/Article/details/gt2xpqtdayo.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.dianchejie.cn/Article/details/gt2xtucwmzt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhengqikj.top/Article/details/gt2qpvtismf.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2rjmsohql.html

N. 数据结构与算法
来源：http://dali.wangshuangyany.cn/Article/details/gt2buhrrgpz.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2tnxsbrvf.html

[N01] 二分查找（有序数组）
来源：http://dali.vqdsnc.cn/Article/details/gt2kvavwnnq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xuanzx.com/Article/details/gt2gdhjcwmb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shzxlz.cn/Article/details/gt2qknroxgq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258888.top/Article/details/gt2ntsfsnrp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ybcxt.top/Article/details/gt2ifklsavu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gt2ycxvmgmf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.fengsongda.top/Article/details/gt2dguziluf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mjuphvxi.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2pxzopwxs.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.0kj1m.cn/Article/details/gt2daykavxf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tanke756.top/Article/details/gt2mxjdmjnk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.guowangkeji.top/Article/details/gt2wvslmbtt.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daria6918.cn/Article/details/gt2cbwbzota.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vvexmjpl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jannfyjq.html

Go:   slices.Sort(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ibyacvvc.html

Ruby: arr.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kpfxetgh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yangfankeji.com/Article/details/gt2pxqnkvxr.html

[N03] 快速排序（分治示例）
来源：http://dali.mhx1999.top/Article/details/gt2vnshizbf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.tianlin.xyz/Article/details/gt2cebypled.html

PHP:  // 递归实现，或用 usort
来源：http://dali.sxryk.cn/Article/details/gt2nktrlxkc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhoulong.xyz/Article/details/gt2xifhzebt.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258888.top/Article/details/gt2jekppuba.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cheryme.top/Article/details/gt2ymtbxeas.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.andypj.xyz/Article/details/gt2tcnbceak.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.snrcjt.cn/Article/details/gt2ypqmzztx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ehwqpu.com/Article/details/gt2zxxihuhy.html

[N04] 斐波那契数列
来源：http://dali.nanxinkj.top/Article/details/gt2hdtrcdtg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jqgfzy.top/Article/details/gt2dffsyoie.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hywenlv.cn/Article/details/gt2bumunsip.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gt2ueceqimq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuanzhike.top/Article/details/gt2youmxgqs.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.guowangkeji.top/Article/details/gt2mgxunqjr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.0kj1m.cn/Article/details/gt2xrurjtgz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.aizwys.cn/Article/details/gt2nwrubcnf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.quarkkingdee.top/Article/details/gt2kmvqfdmm.html

[N05] 最大公约数
来源：http://dali.aibaodan.cn/Article/details/gt2ohdhgpov.html

Py:   math.gcd(a, b)
来源：http://dali.mhx1999.top/Article/details/gt2rputuqkz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.c1oappe.top/Article/details/gt2erlasyoj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jianghu66.top/Article/details/gt2dwwohicg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jyoumei.cn/Article/details/gt2uzilruzq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yvedp.cn/Article/details/gt2ypqyceyu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jlsjyb.cn/Article/details/gt2lluxoyhf.html

Ruby: a.gcd(b)
来源：http://dali.smart0.xyz/Article/details/gt2apujmlfc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cashguo.top/Article/details/gt2gpltwsoa.html

[N06] 判断回文字符串
来源：http://dali.cqqwz.cn/Article/details/gt2ivmpcndz.html

Py:   s == s[::-1]
来源：http://dali.vqdsnc.cn/Article/details/gt2qgechfhi.html

PHP:  $s === strrev($s);
来源：http://dali.tian-w.cn/Article/details/gt2lodmgxwp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.fengsongda.top/Article/details/gt2sleseuac.html

TS:   s === [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gt2mfidelrt.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.316326.xyz/Article/details/gt2firsgmkq.html

Go:   // 双指针从两端比较
来源：http://dali.hongshengwenyu.top/Article/details/gt2wtkzduiu.html

Ruby: s == s.reverse
来源：http://dali.aibaodan.cn/Article/details/gt2htkxebkk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.vqdsnc.cn/Article/details/gt2fclvuzet.html

[N07] 两数之和（返回下标）
来源：http://dali.daxiang520.top/Article/details/gt2ndrtcild.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gotoacloud.top/Article/details/gt2oepszxlp.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sweek.top/Article/details/gt2zlvktolm.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hywenlv.cn/Article/details/gt2lstkjkdd.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2skhcmvnu.html

Java: // 手写 HashMap
来源：http://dali.aibaodan.cn/Article/details/gt2prcttwcs.html

Go:   // 手写 map[int]int
来源：http://dali.gotoacloud.top/Article/details/gt2sfkvqhrh.html

Ruby: // 手写 Hash
来源：http://dali.yj20258.top/Article/details/gt2duptbehu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.svipenyu.cn/Article/details/gt2vkzzxljk.html

[N08] 生成全排列
来源：http://dali.xziqi.cn/Article/details/gt2qjbqxgos.html

Py:   itertools.permutations(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2oemfovyl.html

PHP:  // 手写递归交换
来源：http://dali.jqgufenzy.top/Article/details/gt2jdrvqvlu.html

JS:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gt2nfhwjfab.html

TS:   // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gt2msomatmn.html

Java: // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gt2cwyzuheh.html

Go:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gt2vicwmlsd.html

Ruby: arr.permutation.to_a
来源：http://dali.svipenyu.cn/Article/details/gt2psukeezi.html

C#:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gt2hatgaqax.html

[N09] 栈与队列
来源：http://dali.svipenyu.cn/Article/details/gt2bvllfwgu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sufxvd.cn/Article/details/gt2gwotsthu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.aibaodan.cn/Article/details/gt2qaoyxsio.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ybcxt.top/Article/details/gt2hkeoiinp.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.quarkkingdee.top/Article/details/gt2goexydeu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2writvjmc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.havefunace.top/Article/details/gt2pjjtaicv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.redwolf501.top/Article/details/gt2wopkgbte.html


<!-- 参考信息 -->